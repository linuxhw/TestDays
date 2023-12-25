Ubuntu 22.04 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_22.04/Notebook/README.md).

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

Total: 19815

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 03X6X0 A06                  | Server      | [ca9bb6b7ff](https://linux-hardware.org/?probe=ca9bb6b7ff) | Dec 24, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [f666ec3927](https://linux-hardware.org/?probe=f666ec3927) | Dec 24, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [334b43f409](https://linux-hardware.org/?probe=334b43f409) | Dec 24, 2023 |
| Dell          | Latitude 7490               | Notebook    | [69205c648f](https://linux-hardware.org/?probe=69205c648f) | Dec 24, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [cc87c11e7b](https://linux-hardware.org/?probe=cc87c11e7b) | Dec 24, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [1cb09f63f9](https://linux-hardware.org/?probe=1cb09f63f9) | Dec 24, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [f8abeb2607](https://linux-hardware.org/?probe=f8abeb2607) | Dec 24, 2023 |
| Dell          | 0P658H A05                  | Server      | [14a0701959](https://linux-hardware.org/?probe=14a0701959) | Dec 24, 2023 |
| Google        | Magolor                     | Notebook    | [f5d079bc79](https://linux-hardware.org/?probe=f5d079bc79) | Dec 24, 2023 |
| Dell          | Latitude 12 Rugged Table... | Notebook    | [7690d56522](https://linux-hardware.org/?probe=7690d56522) | Dec 24, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [c9555a34f2](https://linux-hardware.org/?probe=c9555a34f2) | Dec 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [ef80f96d40](https://linux-hardware.org/?probe=ef80f96d40) | Dec 23, 2023 |
| Sony          | VPCEA1S1E                   | Notebook    | [af850dd5f3](https://linux-hardware.org/?probe=af850dd5f3) | Dec 23, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [b1c3408d24](https://linux-hardware.org/?probe=b1c3408d24) | Dec 23, 2023 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [76d95ab75c](https://linux-hardware.org/?probe=76d95ab75c) | Dec 23, 2023 |
| TUXEDO        | N24_25JU                    | Notebook    | [8a1a153723](https://linux-hardware.org/?probe=8a1a153723) | Dec 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [6f36390142](https://linux-hardware.org/?probe=6f36390142) | Dec 23, 2023 |
| ASRock        | AMCP7A-ION                  | Desktop     | [fb0acc2d50](https://linux-hardware.org/?probe=fb0acc2d50) | Dec 23, 2023 |
| Lenovo        | ThinkPad T410 2537E82       | Notebook    | [d153c701cc](https://linux-hardware.org/?probe=d153c701cc) | Dec 23, 2023 |
| Unknown       | FastRhino R66S              | Soc         | [a9cd767c91](https://linux-hardware.org/?probe=a9cd767c91) | Dec 23, 2023 |
| HP            | 1497                        | Desktop     | [9d5244b557](https://linux-hardware.org/?probe=9d5244b557) | Dec 23, 2023 |
| Lenovo        | ThinkPad T410 2537E82       | Notebook    | [398233e395](https://linux-hardware.org/?probe=398233e395) | Dec 23, 2023 |
| Lenovo        | ThinkCentre M58 7373AJ5     | Desktop     | [201981bc3f](https://linux-hardware.org/?probe=201981bc3f) | Dec 23, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [f30aec24c2](https://linux-hardware.org/?probe=f30aec24c2) | Dec 23, 2023 |
| ASRock        | AMCP7A-ION                  | Desktop     | [7d19dec574](https://linux-hardware.org/?probe=7d19dec574) | Dec 23, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [69571c0b91](https://linux-hardware.org/?probe=69571c0b91) | Dec 23, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [db76245a52](https://linux-hardware.org/?probe=db76245a52) | Dec 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d3dabca767](https://linux-hardware.org/?probe=d3dabca767) | Dec 23, 2023 |
| Dell          | Latitude E6330              | Notebook    | [afca8c73b2](https://linux-hardware.org/?probe=afca8c73b2) | Dec 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [26673c372e](https://linux-hardware.org/?probe=26673c372e) | Dec 23, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [2fcf77279a](https://linux-hardware.org/?probe=2fcf77279a) | Dec 23, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [8f2f7cd8c9](https://linux-hardware.org/?probe=8f2f7cd8c9) | Dec 23, 2023 |
| HP            | Laptop 17-bs1xx             | Notebook    | [984a979a7b](https://linux-hardware.org/?probe=984a979a7b) | Dec 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [19e33f2ead](https://linux-hardware.org/?probe=19e33f2ead) | Dec 23, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [9b8ad6a3f1](https://linux-hardware.org/?probe=9b8ad6a3f1) | Dec 23, 2023 |
| eMachines     | EL1360                      | Desktop     | [af31609559](https://linux-hardware.org/?probe=af31609559) | Dec 23, 2023 |
| ASUSTek       | P6T                         | Desktop     | [d90adb3a12](https://linux-hardware.org/?probe=d90adb3a12) | Dec 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [1a10fd9a2e](https://linux-hardware.org/?probe=1a10fd9a2e) | Dec 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [da051b693c](https://linux-hardware.org/?probe=da051b693c) | Dec 23, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | Notebook    | [6ba8bb7550](https://linux-hardware.org/?probe=6ba8bb7550) | Dec 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [0f2cad4391](https://linux-hardware.org/?probe=0f2cad4391) | Dec 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [e778e7923a](https://linux-hardware.org/?probe=e778e7923a) | Dec 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b601b75917](https://linux-hardware.org/?probe=b601b75917) | Dec 22, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [a3fc39604c](https://linux-hardware.org/?probe=a3fc39604c) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [bbdb2204d8](https://linux-hardware.org/?probe=bbdb2204d8) | Dec 22, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [2268342e9f](https://linux-hardware.org/?probe=2268342e9f) | Dec 22, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [89ef1fa23c](https://linux-hardware.org/?probe=89ef1fa23c) | Dec 22, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [84275b737e](https://linux-hardware.org/?probe=84275b737e) | Dec 22, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [c81a75e686](https://linux-hardware.org/?probe=c81a75e686) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c9bee45423](https://linux-hardware.org/?probe=c9bee45423) | Dec 22, 2023 |
| Intel         | H61                         | Desktop     | [72c7724ef0](https://linux-hardware.org/?probe=72c7724ef0) | Dec 22, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | Notebook    | [937842fe5d](https://linux-hardware.org/?probe=937842fe5d) | Dec 22, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6ff6445717](https://linux-hardware.org/?probe=6ff6445717) | Dec 22, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [27a132c185](https://linux-hardware.org/?probe=27a132c185) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [03ddd69e34](https://linux-hardware.org/?probe=03ddd69e34) | Dec 22, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [8e38fb94ba](https://linux-hardware.org/?probe=8e38fb94ba) | Dec 22, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [30e988edc9](https://linux-hardware.org/?probe=30e988edc9) | Dec 22, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [9ff527cfd0](https://linux-hardware.org/?probe=9ff527cfd0) | Dec 22, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [3e49a75ff4](https://linux-hardware.org/?probe=3e49a75ff4) | Dec 22, 2023 |
| HP            | 8626                        | Desktop     | [b04d9fcad9](https://linux-hardware.org/?probe=b04d9fcad9) | Dec 22, 2023 |
| ASUSTek       | M3702WFA                    | All in one  | [9091136a65](https://linux-hardware.org/?probe=9091136a65) | Dec 22, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [6f47019169](https://linux-hardware.org/?probe=6f47019169) | Dec 22, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [8a2d46dced](https://linux-hardware.org/?probe=8a2d46dced) | Dec 22, 2023 |
| Allview       | Allbook I/1                 | Notebook    | [960dfde4cd](https://linux-hardware.org/?probe=960dfde4cd) | Dec 22, 2023 |
| Dell          | Latitude 5414               | Notebook    | [9b02eedb05](https://linux-hardware.org/?probe=9b02eedb05) | Dec 22, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [d2c7d30632](https://linux-hardware.org/?probe=d2c7d30632) | Dec 22, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [60690b9d12](https://linux-hardware.org/?probe=60690b9d12) | Dec 22, 2023 |
| LattePanda    | Sigma                       | Desktop     | [09cb864933](https://linux-hardware.org/?probe=09cb864933) | Dec 22, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [d705d8ee57](https://linux-hardware.org/?probe=d705d8ee57) | Dec 22, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [5f1c04a086](https://linux-hardware.org/?probe=5f1c04a086) | Dec 22, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [2af66f541d](https://linux-hardware.org/?probe=2af66f541d) | Dec 22, 2023 |
| Entroware     | Hybris                      | Notebook    | [870d0c5323](https://linux-hardware.org/?probe=870d0c5323) | Dec 22, 2023 |
| Dell          | Latitude 5501               | Notebook    | [0b6206153c](https://linux-hardware.org/?probe=0b6206153c) | Dec 22, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [1f9d486306](https://linux-hardware.org/?probe=1f9d486306) | Dec 22, 2023 |
| Supermicro    | X8DTH                       | Server      | [e00e89ffec](https://linux-hardware.org/?probe=e00e89ffec) | Dec 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [3ff2f289b9](https://linux-hardware.org/?probe=3ff2f289b9) | Dec 22, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [dbc2e93666](https://linux-hardware.org/?probe=dbc2e93666) | Dec 21, 2023 |
| Dell          | Latitude E6440              | Notebook    | [904540fc01](https://linux-hardware.org/?probe=904540fc01) | Dec 21, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [67f350fefc](https://linux-hardware.org/?probe=67f350fefc) | Dec 21, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [b3c6d4826f](https://linux-hardware.org/?probe=b3c6d4826f) | Dec 21, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [3441fd68be](https://linux-hardware.org/?probe=3441fd68be) | Dec 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [628ca02992](https://linux-hardware.org/?probe=628ca02992) | Dec 21, 2023 |
| ASUSTek       | M3702WFA                    | All in one  | [a6d6ecda48](https://linux-hardware.org/?probe=a6d6ecda48) | Dec 21, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [907851c66b](https://linux-hardware.org/?probe=907851c66b) | Dec 21, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [c5c9d669ae](https://linux-hardware.org/?probe=c5c9d669ae) | Dec 21, 2023 |
| Dell          | Precision 3581              | Notebook    | [aa0186ade6](https://linux-hardware.org/?probe=aa0186ade6) | Dec 21, 2023 |
| HP            | ProBook 445 14 inch G10 ... | Notebook    | [0e95b32d0b](https://linux-hardware.org/?probe=0e95b32d0b) | Dec 21, 2023 |
| Dell          | Inspiron 15 3535            | Notebook    | [466204d787](https://linux-hardware.org/?probe=466204d787) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK U749               | Notebook    | [75a3ef28b0](https://linux-hardware.org/?probe=75a3ef28b0) | Dec 21, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f95bb7d27c](https://linux-hardware.org/?probe=f95bb7d27c) | Dec 21, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [49e514e9c4](https://linux-hardware.org/?probe=49e514e9c4) | Dec 21, 2023 |
| Intel         | NUC7i5BNB J31144-309        | Mini pc     | [75c700e92a](https://linux-hardware.org/?probe=75c700e92a) | Dec 21, 2023 |
| Acer          | Aspire XC-1760              | Desktop     | [ac3910a453](https://linux-hardware.org/?probe=ac3910a453) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [27e7d6f705](https://linux-hardware.org/?probe=27e7d6f705) | Dec 21, 2023 |
| Dell          | Latitude 7490               | Notebook    | [d0ea360540](https://linux-hardware.org/?probe=d0ea360540) | Dec 21, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [d8e473e1e4](https://linux-hardware.org/?probe=d8e473e1e4) | Dec 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [ef719917ef](https://linux-hardware.org/?probe=ef719917ef) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | Desktop     | [1ba9d3bc0c](https://linux-hardware.org/?probe=1ba9d3bc0c) | Dec 21, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [ebaf3f3e71](https://linux-hardware.org/?probe=ebaf3f3e71) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | Desktop     | [066ebdde5b](https://linux-hardware.org/?probe=066ebdde5b) | Dec 21, 2023 |
| Neousys Te... | NVS-10000 Rev. A2           | Server      | [cde616cde3](https://linux-hardware.org/?probe=cde616cde3) | Dec 21, 2023 |
| HP            | Notebook                    | Notebook    | [9010ced489](https://linux-hardware.org/?probe=9010ced489) | Dec 21, 2023 |
| Dell          | Inspiron 5448               | Notebook    | [edf818740d](https://linux-hardware.org/?probe=edf818740d) | Dec 21, 2023 |
| Lenovo        | ThinkPad 20FRS22T00         | Convertible | [d52b91f681](https://linux-hardware.org/?probe=d52b91f681) | Dec 21, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [e3a45d6095](https://linux-hardware.org/?probe=e3a45d6095) | Dec 21, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [191d4913cd](https://linux-hardware.org/?probe=191d4913cd) | Dec 21, 2023 |
| Lenovo        | ThinkPad 20FRS22T00         | Convertible | [1d07dbc740](https://linux-hardware.org/?probe=1d07dbc740) | Dec 21, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [735572694e](https://linux-hardware.org/?probe=735572694e) | Dec 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [cd7f768fe8](https://linux-hardware.org/?probe=cd7f768fe8) | Dec 21, 2023 |
| HP            | 18E7                        | Desktop     | [ad6cf02d18](https://linux-hardware.org/?probe=ad6cf02d18) | Dec 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [e36c36774e](https://linux-hardware.org/?probe=e36c36774e) | Dec 21, 2023 |
| HP            | 18E7                        | Desktop     | [fdb8b2d229](https://linux-hardware.org/?probe=fdb8b2d229) | Dec 21, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [8eca3c15e7](https://linux-hardware.org/?probe=8eca3c15e7) | Dec 21, 2023 |
| ASUSTek       | Z10PG-D16 Series            | Desktop     | [6b3c6c4099](https://linux-hardware.org/?probe=6b3c6c4099) | Dec 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [9e16e8b2a6](https://linux-hardware.org/?probe=9e16e8b2a6) | Dec 21, 2023 |
| MSI           | NF725M-P43                  | Desktop     | [43756d6fad](https://linux-hardware.org/?probe=43756d6fad) | Dec 21, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [93a7029d22](https://linux-hardware.org/?probe=93a7029d22) | Dec 21, 2023 |
| Dell          | Inspiron 7572               | Notebook    | [cd9385a64b](https://linux-hardware.org/?probe=cd9385a64b) | Dec 21, 2023 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [4bd3fc58a8](https://linux-hardware.org/?probe=4bd3fc58a8) | Dec 21, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [7597019eca](https://linux-hardware.org/?probe=7597019eca) | Dec 21, 2023 |
| Panasonic     | CF-19RDRCHH7                | Notebook    | [0e67081368](https://linux-hardware.org/?probe=0e67081368) | Dec 21, 2023 |
| HP            | Spectre x360 Convertible    | Convertible | [3aec09e469](https://linux-hardware.org/?probe=3aec09e469) | Dec 21, 2023 |
| ASUSTek       | VM40B                       | Desktop     | [8deb79e86e](https://linux-hardware.org/?probe=8deb79e86e) | Dec 20, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [6e7f8b2300](https://linux-hardware.org/?probe=6e7f8b2300) | Dec 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [4f307c792f](https://linux-hardware.org/?probe=4f307c792f) | Dec 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [da159da872](https://linux-hardware.org/?probe=da159da872) | Dec 20, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [1da522781e](https://linux-hardware.org/?probe=1da522781e) | Dec 20, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f080cc67aa](https://linux-hardware.org/?probe=f080cc67aa) | Dec 20, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [35547b20b3](https://linux-hardware.org/?probe=35547b20b3) | Dec 20, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [393c13e870](https://linux-hardware.org/?probe=393c13e870) | Dec 20, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [09af8afa56](https://linux-hardware.org/?probe=09af8afa56) | Dec 20, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [dfd0e27118](https://linux-hardware.org/?probe=dfd0e27118) | Dec 20, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [f46e034f2c](https://linux-hardware.org/?probe=f46e034f2c) | Dec 20, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [e696fd9ae0](https://linux-hardware.org/?probe=e696fd9ae0) | Dec 20, 2023 |
| Lenovo        | ThinkPad T410 2537HN2       | Notebook    | [c268085f95](https://linux-hardware.org/?probe=c268085f95) | Dec 20, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [06984b497c](https://linux-hardware.org/?probe=06984b497c) | Dec 20, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [7cd9f2379e](https://linux-hardware.org/?probe=7cd9f2379e) | Dec 20, 2023 |
| Dell          | Precision 5510              | Notebook    | [033bf69fdf](https://linux-hardware.org/?probe=033bf69fdf) | Dec 20, 2023 |
| Dell          | Precision 5510              | Notebook    | [a40fa883d2](https://linux-hardware.org/?probe=a40fa883d2) | Dec 20, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [c931f0f65a](https://linux-hardware.org/?probe=c931f0f65a) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [71bc732b86](https://linux-hardware.org/?probe=71bc732b86) | Dec 20, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [58517da295](https://linux-hardware.org/?probe=58517da295) | Dec 20, 2023 |
| Dell          | G7 7700                     | Notebook    | [506de63cb5](https://linux-hardware.org/?probe=506de63cb5) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [5d14b45611](https://linux-hardware.org/?probe=5d14b45611) | Dec 20, 2023 |
| Lenovo        | ThinkPad T520 42404AU       | Notebook    | [2b29070879](https://linux-hardware.org/?probe=2b29070879) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [71d03541a9](https://linux-hardware.org/?probe=71d03541a9) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6f7295809b](https://linux-hardware.org/?probe=6f7295809b) | Dec 20, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [2b2e293dc4](https://linux-hardware.org/?probe=2b2e293dc4) | Dec 20, 2023 |
| Unknown       | Orange Pi 5B                | Soc         | [f809840436](https://linux-hardware.org/?probe=f809840436) | Dec 20, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [7aa12c94c1](https://linux-hardware.org/?probe=7aa12c94c1) | Dec 20, 2023 |
| Daten Tecn... | DT02-M4                     | Notebook    | [8f754589f6](https://linux-hardware.org/?probe=8f754589f6) | Dec 19, 2023 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [09ab03cdcd](https://linux-hardware.org/?probe=09ab03cdcd) | Dec 19, 2023 |
| ANGXUN        | X79-VG2 V1.3                | Desktop     | [532c5b5ddc](https://linux-hardware.org/?probe=532c5b5ddc) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [dbbab5f96b](https://linux-hardware.org/?probe=dbbab5f96b) | Dec 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [775e2dfe26](https://linux-hardware.org/?probe=775e2dfe26) | Dec 19, 2023 |
| Google        | Swanky                      | Notebook    | [46b7f27873](https://linux-hardware.org/?probe=46b7f27873) | Dec 19, 2023 |
| MSI           | B85-G43                     | Desktop     | [2c855d2376](https://linux-hardware.org/?probe=2c855d2376) | Dec 19, 2023 |
| Mediacom      | GTZS                        | Notebook    | [f326507469](https://linux-hardware.org/?probe=f326507469) | Dec 19, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [3cc3621576](https://linux-hardware.org/?probe=3cc3621576) | Dec 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [b97589a2bc](https://linux-hardware.org/?probe=b97589a2bc) | Dec 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [5dd323e917](https://linux-hardware.org/?probe=5dd323e917) | Dec 19, 2023 |
| HP            | EliteBook 840 14 inch G1... | Notebook    | [2222f1a1fb](https://linux-hardware.org/?probe=2222f1a1fb) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [1b5268d64f](https://linux-hardware.org/?probe=1b5268d64f) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [1290fe8e5a](https://linux-hardware.org/?probe=1290fe8e5a) | Dec 19, 2023 |
| Dell          | Latitude E6510              | Notebook    | [e9aceddae8](https://linux-hardware.org/?probe=e9aceddae8) | Dec 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a4efec2a2c](https://linux-hardware.org/?probe=a4efec2a2c) | Dec 19, 2023 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [f09218ee8f](https://linux-hardware.org/?probe=f09218ee8f) | Dec 19, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [11f6da5848](https://linux-hardware.org/?probe=11f6da5848) | Dec 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [6f1ca9e563](https://linux-hardware.org/?probe=6f1ca9e563) | Dec 19, 2023 |
| Dell          | Precision M2800             | Notebook    | [8800042fb5](https://linux-hardware.org/?probe=8800042fb5) | Dec 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [13072c9ecc](https://linux-hardware.org/?probe=13072c9ecc) | Dec 19, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [843515c201](https://linux-hardware.org/?probe=843515c201) | Dec 19, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [91c6527140](https://linux-hardware.org/?probe=91c6527140) | Dec 19, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [1038e25caf](https://linux-hardware.org/?probe=1038e25caf) | Dec 19, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [35b8611349](https://linux-hardware.org/?probe=35b8611349) | Dec 19, 2023 |
| ASUSTek       | H81-PLUS                    | Desktop     | [359af07cb2](https://linux-hardware.org/?probe=359af07cb2) | Dec 19, 2023 |
| ASUSTek       | H81-PLUS                    | Desktop     | [b4b91802b5](https://linux-hardware.org/?probe=b4b91802b5) | Dec 19, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [3cf8d970f8](https://linux-hardware.org/?probe=3cf8d970f8) | Dec 19, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d41e584b48](https://linux-hardware.org/?probe=d41e584b48) | Dec 19, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [3a4a73b5f1](https://linux-hardware.org/?probe=3a4a73b5f1) | Dec 19, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [5781ca34c8](https://linux-hardware.org/?probe=5781ca34c8) | Dec 19, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [a2bb7b1e00](https://linux-hardware.org/?probe=a2bb7b1e00) | Dec 19, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [a2a69a3d09](https://linux-hardware.org/?probe=a2a69a3d09) | Dec 19, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [2feb704b34](https://linux-hardware.org/?probe=2feb704b34) | Dec 19, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [705321d0b6](https://linux-hardware.org/?probe=705321d0b6) | Dec 19, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4220452f9d](https://linux-hardware.org/?probe=4220452f9d) | Dec 18, 2023 |
| HP            | 3647h                       | Desktop     | [0e741d6d7c](https://linux-hardware.org/?probe=0e741d6d7c) | Dec 18, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [55a802f43c](https://linux-hardware.org/?probe=55a802f43c) | Dec 18, 2023 |
| Supermicro    | X7DWA                       | Desktop     | [2ea00dfda4](https://linux-hardware.org/?probe=2ea00dfda4) | Dec 18, 2023 |
| Supermicro    | X7DWA                       | Desktop     | [6357637f80](https://linux-hardware.org/?probe=6357637f80) | Dec 18, 2023 |
| Dell          | Latitude 3420               | Notebook    | [5fdda723cd](https://linux-hardware.org/?probe=5fdda723cd) | Dec 18, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [31b0444771](https://linux-hardware.org/?probe=31b0444771) | Dec 18, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [923f390d62](https://linux-hardware.org/?probe=923f390d62) | Dec 18, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [f93e198dd4](https://linux-hardware.org/?probe=f93e198dd4) | Dec 18, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [1232ff1050](https://linux-hardware.org/?probe=1232ff1050) | Dec 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [498141a78c](https://linux-hardware.org/?probe=498141a78c) | Dec 18, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [8a224cfad3](https://linux-hardware.org/?probe=8a224cfad3) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [0cf5577833](https://linux-hardware.org/?probe=0cf5577833) | Dec 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [0376612ef7](https://linux-hardware.org/?probe=0376612ef7) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [45a0b94112](https://linux-hardware.org/?probe=45a0b94112) | Dec 18, 2023 |
| Dell          | Latitude 7440               | Notebook    | [644c46aba6](https://linux-hardware.org/?probe=644c46aba6) | Dec 18, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [100bef421f](https://linux-hardware.org/?probe=100bef421f) | Dec 18, 2023 |
| Dell          | 06FW8P A02                  | Desktop     | [7b66e504eb](https://linux-hardware.org/?probe=7b66e504eb) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [2bee7533b2](https://linux-hardware.org/?probe=2bee7533b2) | Dec 18, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [941f6d849a](https://linux-hardware.org/?probe=941f6d849a) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [fcc1139818](https://linux-hardware.org/?probe=fcc1139818) | Dec 18, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [312fe4e212](https://linux-hardware.org/?probe=312fe4e212) | Dec 18, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [f81cd33147](https://linux-hardware.org/?probe=f81cd33147) | Dec 18, 2023 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [054ed4fad9](https://linux-hardware.org/?probe=054ed4fad9) | Dec 18, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [0c3974dad9](https://linux-hardware.org/?probe=0c3974dad9) | Dec 18, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [f4412027d4](https://linux-hardware.org/?probe=f4412027d4) | Dec 18, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [6ecd3ce2c3](https://linux-hardware.org/?probe=6ecd3ce2c3) | Dec 18, 2023 |
| DTV           | G5A-BTJ1900                 | Other       | [f6c12e7381](https://linux-hardware.org/?probe=f6c12e7381) | Dec 18, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [d1dcdfda30](https://linux-hardware.org/?probe=d1dcdfda30) | Dec 17, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [4802066fc1](https://linux-hardware.org/?probe=4802066fc1) | Dec 17, 2023 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [0f7c6a7383](https://linux-hardware.org/?probe=0f7c6a7383) | Dec 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [8425b10899](https://linux-hardware.org/?probe=8425b10899) | Dec 17, 2023 |
| Acer          | Aspire S7-391               | Notebook    | [ab734913e8](https://linux-hardware.org/?probe=ab734913e8) | Dec 17, 2023 |
| Acer          | Aspire S7-391               | Notebook    | [1d66b3f887](https://linux-hardware.org/?probe=1d66b3f887) | Dec 17, 2023 |
| Acer          | Swift SF315-41              | Notebook    | [300b426183](https://linux-hardware.org/?probe=300b426183) | Dec 17, 2023 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [17b157ef44](https://linux-hardware.org/?probe=17b157ef44) | Dec 17, 2023 |
| Dell          | 07N90W A02                  | Desktop     | [0c471e8b44](https://linux-hardware.org/?probe=0c471e8b44) | Dec 17, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [ead1dfb3ae](https://linux-hardware.org/?probe=ead1dfb3ae) | Dec 17, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [a845742a42](https://linux-hardware.org/?probe=a845742a42) | Dec 17, 2023 |
| Sony          | SVD1321L2EW                 | Notebook    | [b753425d70](https://linux-hardware.org/?probe=b753425d70) | Dec 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [342d099a7f](https://linux-hardware.org/?probe=342d099a7f) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [78a88bfe8c](https://linux-hardware.org/?probe=78a88bfe8c) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [8833b0a058](https://linux-hardware.org/?probe=8833b0a058) | Dec 17, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [341ecee745](https://linux-hardware.org/?probe=341ecee745) | Dec 17, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [987ab63f96](https://linux-hardware.org/?probe=987ab63f96) | Dec 17, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [d3e1291358](https://linux-hardware.org/?probe=d3e1291358) | Dec 17, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [b652245cca](https://linux-hardware.org/?probe=b652245cca) | Dec 17, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1f0e0f04f8](https://linux-hardware.org/?probe=1f0e0f04f8) | Dec 17, 2023 |
| HP            | 1790                        | Desktop     | [2d8c859110](https://linux-hardware.org/?probe=2d8c859110) | Dec 17, 2023 |
| Dell          | 03X6X0 A06                  | Server      | [65557703dc](https://linux-hardware.org/?probe=65557703dc) | Dec 17, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [91a9e2e8c4](https://linux-hardware.org/?probe=91a9e2e8c4) | Dec 17, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [efc671c7c2](https://linux-hardware.org/?probe=efc671c7c2) | Dec 17, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [c99e0d38ea](https://linux-hardware.org/?probe=c99e0d38ea) | Dec 17, 2023 |
| HP            | 2000                        | Notebook    | [3570eb7cd0](https://linux-hardware.org/?probe=3570eb7cd0) | Dec 17, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [e85c54f3fd](https://linux-hardware.org/?probe=e85c54f3fd) | Dec 17, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [f84bfa5707](https://linux-hardware.org/?probe=f84bfa5707) | Dec 17, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [a77869199a](https://linux-hardware.org/?probe=a77869199a) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [8adfc82dc5](https://linux-hardware.org/?probe=8adfc82dc5) | Dec 17, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [d5632292b6](https://linux-hardware.org/?probe=d5632292b6) | Dec 17, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [6745d8d399](https://linux-hardware.org/?probe=6745d8d399) | Dec 17, 2023 |
| Lenovo        | ThinkPad W530 24491D1       | Notebook    | [bab70d44b1](https://linux-hardware.org/?probe=bab70d44b1) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [1c0bbe412c](https://linux-hardware.org/?probe=1c0bbe412c) | Dec 17, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [de9dcb40ba](https://linux-hardware.org/?probe=de9dcb40ba) | Dec 17, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [b280c267db](https://linux-hardware.org/?probe=b280c267db) | Dec 17, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [492e654dfb](https://linux-hardware.org/?probe=492e654dfb) | Dec 17, 2023 |
| Shenzhen M... | TH80                        | Desktop     | [1ad9ee524d](https://linux-hardware.org/?probe=1ad9ee524d) | Dec 16, 2023 |
| LG Electro... | 16Z90R-A.ADC8U1             | Notebook    | [5ae89dd818](https://linux-hardware.org/?probe=5ae89dd818) | Dec 16, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [73df6dfb3b](https://linux-hardware.org/?probe=73df6dfb3b) | Dec 16, 2023 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [e3d139cdb3](https://linux-hardware.org/?probe=e3d139cdb3) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [646c403e2f](https://linux-hardware.org/?probe=646c403e2f) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [7fc71d8954](https://linux-hardware.org/?probe=7fc71d8954) | Dec 16, 2023 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [a7dd86011c](https://linux-hardware.org/?probe=a7dd86011c) | Dec 16, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [efe58ba5df](https://linux-hardware.org/?probe=efe58ba5df) | Dec 16, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [6e6dfdc457](https://linux-hardware.org/?probe=6e6dfdc457) | Dec 16, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [e6019b847e](https://linux-hardware.org/?probe=e6019b847e) | Dec 16, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [2167a2f148](https://linux-hardware.org/?probe=2167a2f148) | Dec 16, 2023 |
| HP            | 2B05                        | Desktop     | [81e68a1fb8](https://linux-hardware.org/?probe=81e68a1fb8) | Dec 16, 2023 |
| HP            | 2B05                        | Desktop     | [2063743d90](https://linux-hardware.org/?probe=2063743d90) | Dec 16, 2023 |
| Acer          | EG43M                       | Desktop     | [62c8e8acf8](https://linux-hardware.org/?probe=62c8e8acf8) | Dec 16, 2023 |
| HP            | 1790                        | Desktop     | [9bb2d6fcb4](https://linux-hardware.org/?probe=9bb2d6fcb4) | Dec 16, 2023 |
| Acer          | Aspire 6930G                | Notebook    | [3e93a62792](https://linux-hardware.org/?probe=3e93a62792) | Dec 16, 2023 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [862ce85408](https://linux-hardware.org/?probe=862ce85408) | Dec 16, 2023 |
| Lenovo        | ThinkPad T420 4238AW2       | Notebook    | [01fae631cf](https://linux-hardware.org/?probe=01fae631cf) | Dec 16, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [8297f20357](https://linux-hardware.org/?probe=8297f20357) | Dec 16, 2023 |
| Allview       | Allbook H                   | Notebook    | [2da4fcb35c](https://linux-hardware.org/?probe=2da4fcb35c) | Dec 16, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [e9f2e211bd](https://linux-hardware.org/?probe=e9f2e211bd) | Dec 16, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [109311067f](https://linux-hardware.org/?probe=109311067f) | Dec 16, 2023 |
| Dell          | 0RT6HT A01                  | Desktop     | [3509be8560](https://linux-hardware.org/?probe=3509be8560) | Dec 16, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [2598a81fd9](https://linux-hardware.org/?probe=2598a81fd9) | Dec 16, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [6458d64d28](https://linux-hardware.org/?probe=6458d64d28) | Dec 16, 2023 |
| Lenovo        | IdeaPad S400 20195          | Notebook    | [f4c6ceeca3](https://linux-hardware.org/?probe=f4c6ceeca3) | Dec 16, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [7b3d7fcb72](https://linux-hardware.org/?probe=7b3d7fcb72) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [026638d09e](https://linux-hardware.org/?probe=026638d09e) | Dec 16, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [251ac554a9](https://linux-hardware.org/?probe=251ac554a9) | Dec 16, 2023 |
| Dell          | Precision 5540              | Notebook    | [ff22e47089](https://linux-hardware.org/?probe=ff22e47089) | Dec 16, 2023 |
| HP            | Notebook                    | Notebook    | [5bbbe8e356](https://linux-hardware.org/?probe=5bbbe8e356) | Dec 16, 2023 |
| ROMBICA       | myBook Discovery            | Notebook    | [c7b69fb478](https://linux-hardware.org/?probe=c7b69fb478) | Dec 16, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [3f47a63c82](https://linux-hardware.org/?probe=3f47a63c82) | Dec 16, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [933e5b48f2](https://linux-hardware.org/?probe=933e5b48f2) | Dec 16, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [9df7fd000e](https://linux-hardware.org/?probe=9df7fd000e) | Dec 16, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [12c5d1d331](https://linux-hardware.org/?probe=12c5d1d331) | Dec 16, 2023 |
| Medion        | E6417 MD99252               | Notebook    | [26e9c2ba0c](https://linux-hardware.org/?probe=26e9c2ba0c) | Dec 15, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [1eb5b02078](https://linux-hardware.org/?probe=1eb5b02078) | Dec 15, 2023 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [2d3b97c04a](https://linux-hardware.org/?probe=2d3b97c04a) | Dec 15, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [199ffa8815](https://linux-hardware.org/?probe=199ffa8815) | Dec 15, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a5431ec5e0](https://linux-hardware.org/?probe=a5431ec5e0) | Dec 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5223e586fd](https://linux-hardware.org/?probe=5223e586fd) | Dec 15, 2023 |
| Lenovo        | B590 62742QG                | Notebook    | [edb1cd89f6](https://linux-hardware.org/?probe=edb1cd89f6) | Dec 15, 2023 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [b60d191f59](https://linux-hardware.org/?probe=b60d191f59) | Dec 15, 2023 |
| VIT           | M2400-01                    | Mini pc     | [8c80d8ce0c](https://linux-hardware.org/?probe=8c80d8ce0c) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [9e63ff66cb](https://linux-hardware.org/?probe=9e63ff66cb) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [1fae1d3423](https://linux-hardware.org/?probe=1fae1d3423) | Dec 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7863fae702](https://linux-hardware.org/?probe=7863fae702) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [1a70a13ff4](https://linux-hardware.org/?probe=1a70a13ff4) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [8be30808ec](https://linux-hardware.org/?probe=8be30808ec) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [1e0ba866f7](https://linux-hardware.org/?probe=1e0ba866f7) | Dec 15, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [638a0b8c0c](https://linux-hardware.org/?probe=638a0b8c0c) | Dec 15, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [035b37d481](https://linux-hardware.org/?probe=035b37d481) | Dec 15, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [618978da16](https://linux-hardware.org/?probe=618978da16) | Dec 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b7194dbbb8](https://linux-hardware.org/?probe=b7194dbbb8) | Dec 15, 2023 |
| HP            | Laptop 17-bs1xx             | Notebook    | [ef29718fd5](https://linux-hardware.org/?probe=ef29718fd5) | Dec 15, 2023 |
| Google        | Guado                       | Desktop     | [e981ac3399](https://linux-hardware.org/?probe=e981ac3399) | Dec 15, 2023 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [6358b586ac](https://linux-hardware.org/?probe=6358b586ac) | Dec 15, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [051090b9e0](https://linux-hardware.org/?probe=051090b9e0) | Dec 15, 2023 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [6af7c135e1](https://linux-hardware.org/?probe=6af7c135e1) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [d8db62d461](https://linux-hardware.org/?probe=d8db62d461) | Dec 15, 2023 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [a0eaa74105](https://linux-hardware.org/?probe=a0eaa74105) | Dec 15, 2023 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [db4a7dea97](https://linux-hardware.org/?probe=db4a7dea97) | Dec 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [166f55ae0b](https://linux-hardware.org/?probe=166f55ae0b) | Dec 15, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [7e43febcae](https://linux-hardware.org/?probe=7e43febcae) | Dec 15, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | Notebook    | [e4542af709](https://linux-hardware.org/?probe=e4542af709) | Dec 15, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | Notebook    | [46fbc450b5](https://linux-hardware.org/?probe=46fbc450b5) | Dec 14, 2023 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [5dca430907](https://linux-hardware.org/?probe=5dca430907) | Dec 14, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [eb487bbab2](https://linux-hardware.org/?probe=eb487bbab2) | Dec 14, 2023 |
| Dell          | Latitude E5450              | Notebook    | [b616faa68f](https://linux-hardware.org/?probe=b616faa68f) | Dec 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9fb745d9fe](https://linux-hardware.org/?probe=9fb745d9fe) | Dec 14, 2023 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [48c963a11d](https://linux-hardware.org/?probe=48c963a11d) | Dec 14, 2023 |
| Google        | Guado                       | Desktop     | [50ceaa2515](https://linux-hardware.org/?probe=50ceaa2515) | Dec 14, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [9609ed5138](https://linux-hardware.org/?probe=9609ed5138) | Dec 14, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [b537ee14db](https://linux-hardware.org/?probe=b537ee14db) | Dec 14, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | Desktop     | [742681b576](https://linux-hardware.org/?probe=742681b576) | Dec 14, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | Desktop     | [72cd581273](https://linux-hardware.org/?probe=72cd581273) | Dec 14, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [7f788f5265](https://linux-hardware.org/?probe=7f788f5265) | Dec 14, 2023 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [fabfe15230](https://linux-hardware.org/?probe=fabfe15230) | Dec 14, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [d4d42016ea](https://linux-hardware.org/?probe=d4d42016ea) | Dec 14, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ac8fb0b18d](https://linux-hardware.org/?probe=ac8fb0b18d) | Dec 14, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [101f8237e0](https://linux-hardware.org/?probe=101f8237e0) | Dec 14, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [6da01d5871](https://linux-hardware.org/?probe=6da01d5871) | Dec 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bfca25b6c1](https://linux-hardware.org/?probe=bfca25b6c1) | Dec 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [adbfbb8174](https://linux-hardware.org/?probe=adbfbb8174) | Dec 13, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [0a2b707101](https://linux-hardware.org/?probe=0a2b707101) | Dec 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [9d0aff4b01](https://linux-hardware.org/?probe=9d0aff4b01) | Dec 13, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [1522c84fb7](https://linux-hardware.org/?probe=1522c84fb7) | Dec 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [9c3e8b880d](https://linux-hardware.org/?probe=9c3e8b880d) | Dec 13, 2023 |
| HP            | 83EF                        | Desktop     | [e2a7a03e4c](https://linux-hardware.org/?probe=e2a7a03e4c) | Dec 13, 2023 |
| HP            | 83EF                        | Desktop     | [d5d568c47c](https://linux-hardware.org/?probe=d5d568c47c) | Dec 13, 2023 |
| HP            | 829A                        | Mini pc     | [4a18e66bdc](https://linux-hardware.org/?probe=4a18e66bdc) | Dec 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [ab0ac93be6](https://linux-hardware.org/?probe=ab0ac93be6) | Dec 13, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e70de29c90](https://linux-hardware.org/?probe=e70de29c90) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [f845d7a88e](https://linux-hardware.org/?probe=f845d7a88e) | Dec 13, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [de6e3bf0eb](https://linux-hardware.org/?probe=de6e3bf0eb) | Dec 13, 2023 |
| Lenovo        | ThinkPad X201 3626W1P       | Notebook    | [bf54dfd215](https://linux-hardware.org/?probe=bf54dfd215) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [9d192a95d8](https://linux-hardware.org/?probe=9d192a95d8) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [19e6b5a871](https://linux-hardware.org/?probe=19e6b5a871) | Dec 13, 2023 |
| HP            | 18E9                        | Desktop     | [ab47a5d40b](https://linux-hardware.org/?probe=ab47a5d40b) | Dec 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [e196db2480](https://linux-hardware.org/?probe=e196db2480) | Dec 13, 2023 |
| Unknown       | Unknown                     | Soc         | [abf8ea1275](https://linux-hardware.org/?probe=abf8ea1275) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [4a5e5bbe29](https://linux-hardware.org/?probe=4a5e5bbe29) | Dec 13, 2023 |
| Unknown       | Unknown                     | Soc         | [4d27eccf69](https://linux-hardware.org/?probe=4d27eccf69) | Dec 13, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [6e8b956266](https://linux-hardware.org/?probe=6e8b956266) | Dec 13, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e198c73fa2](https://linux-hardware.org/?probe=e198c73fa2) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [f18bd26311](https://linux-hardware.org/?probe=f18bd26311) | Dec 13, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [cdcd6ddfc6](https://linux-hardware.org/?probe=cdcd6ddfc6) | Dec 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [963ff854d9](https://linux-hardware.org/?probe=963ff854d9) | Dec 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [01915c7894](https://linux-hardware.org/?probe=01915c7894) | Dec 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [a8d24008e2](https://linux-hardware.org/?probe=a8d24008e2) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [ed5de838eb](https://linux-hardware.org/?probe=ed5de838eb) | Dec 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [05ff735f51](https://linux-hardware.org/?probe=05ff735f51) | Dec 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [4517e8a60b](https://linux-hardware.org/?probe=4517e8a60b) | Dec 13, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [227af40d05](https://linux-hardware.org/?probe=227af40d05) | Dec 13, 2023 |
| ASUSTek       | Basswood3G                  | Desktop     | [f686ec5ba9](https://linux-hardware.org/?probe=f686ec5ba9) | Dec 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [fd405f79f2](https://linux-hardware.org/?probe=fd405f79f2) | Dec 13, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [9c38707d13](https://linux-hardware.org/?probe=9c38707d13) | Dec 13, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [f837c928be](https://linux-hardware.org/?probe=f837c928be) | Dec 13, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [ce858f7f7c](https://linux-hardware.org/?probe=ce858f7f7c) | Dec 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [e764bfc760](https://linux-hardware.org/?probe=e764bfc760) | Dec 13, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [01f7be08ae](https://linux-hardware.org/?probe=01f7be08ae) | Dec 13, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [e6f39159ad](https://linux-hardware.org/?probe=e6f39159ad) | Dec 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [4f1419b521](https://linux-hardware.org/?probe=4f1419b521) | Dec 12, 2023 |
| HP            | 3048h                       | Desktop     | [bb95017425](https://linux-hardware.org/?probe=bb95017425) | Dec 12, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | Notebook    | [2b589c71b3](https://linux-hardware.org/?probe=2b589c71b3) | Dec 12, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | Desktop     | [eadc049e56](https://linux-hardware.org/?probe=eadc049e56) | Dec 12, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [bcf9fba46f](https://linux-hardware.org/?probe=bcf9fba46f) | Dec 12, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [da78a4dd31](https://linux-hardware.org/?probe=da78a4dd31) | Dec 12, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [2f96568c78](https://linux-hardware.org/?probe=2f96568c78) | Dec 12, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [68fe94d3be](https://linux-hardware.org/?probe=68fe94d3be) | Dec 12, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [98f2d76ef0](https://linux-hardware.org/?probe=98f2d76ef0) | Dec 12, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [c4de324273](https://linux-hardware.org/?probe=c4de324273) | Dec 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af7be431fb](https://linux-hardware.org/?probe=af7be431fb) | Dec 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a128efcd01](https://linux-hardware.org/?probe=a128efcd01) | Dec 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [4293932b86](https://linux-hardware.org/?probe=4293932b86) | Dec 12, 2023 |
| Lenovo        | ThinkPad X201 3626W1P       | Notebook    | [695a85cd79](https://linux-hardware.org/?probe=695a85cd79) | Dec 12, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [dff662b36c](https://linux-hardware.org/?probe=dff662b36c) | Dec 12, 2023 |
| Lenovo        | ThinkPad E490 20N9S13000    | Notebook    | [d93593921b](https://linux-hardware.org/?probe=d93593921b) | Dec 12, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [0ad101e0f2](https://linux-hardware.org/?probe=0ad101e0f2) | Dec 12, 2023 |
| MSI           | A320M PRO-VD/S              | Desktop     | [c2a6947086](https://linux-hardware.org/?probe=c2a6947086) | Dec 12, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [e438bd7bc2](https://linux-hardware.org/?probe=e438bd7bc2) | Dec 12, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [4576cb723a](https://linux-hardware.org/?probe=4576cb723a) | Dec 12, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [0ba0422412](https://linux-hardware.org/?probe=0ba0422412) | Dec 12, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [d5cb60727d](https://linux-hardware.org/?probe=d5cb60727d) | Dec 12, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [41ff1cd0ca](https://linux-hardware.org/?probe=41ff1cd0ca) | Dec 12, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8e66dfbc28](https://linux-hardware.org/?probe=8e66dfbc28) | Dec 12, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [1e1b5e9985](https://linux-hardware.org/?probe=1e1b5e9985) | Dec 12, 2023 |
| HP            | 0AECh D                     | Desktop     | [b1856b493c](https://linux-hardware.org/?probe=b1856b493c) | Dec 12, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [06f64404ec](https://linux-hardware.org/?probe=06f64404ec) | Dec 12, 2023 |
| Sony          | VPCEH25EN                   | Notebook    | [284401858f](https://linux-hardware.org/?probe=284401858f) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [84fd94c616](https://linux-hardware.org/?probe=84fd94c616) | Dec 12, 2023 |
| Sony          | VPCCW1S1E                   | Notebook    | [361d9573dd](https://linux-hardware.org/?probe=361d9573dd) | Dec 12, 2023 |
| HP            | Pavilion 15                 | Notebook    | [235d10da72](https://linux-hardware.org/?probe=235d10da72) | Dec 12, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fd466b16c8](https://linux-hardware.org/?probe=fd466b16c8) | Dec 12, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [e72a787933](https://linux-hardware.org/?probe=e72a787933) | Dec 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d27df22c9a](https://linux-hardware.org/?probe=d27df22c9a) | Dec 11, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [f2e813a565](https://linux-hardware.org/?probe=f2e813a565) | Dec 11, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [ee39e0724c](https://linux-hardware.org/?probe=ee39e0724c) | Dec 11, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [0d3866e04a](https://linux-hardware.org/?probe=0d3866e04a) | Dec 11, 2023 |
| Dell          | 0Y2YM6 A01                  | Desktop     | [c3fee04c74](https://linux-hardware.org/?probe=c3fee04c74) | Dec 11, 2023 |
| MSI           | GX60 1AC/GX60 3AE/GX60 3... | Notebook    | [262637b1e2](https://linux-hardware.org/?probe=262637b1e2) | Dec 11, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [ccd16e5c8d](https://linux-hardware.org/?probe=ccd16e5c8d) | Dec 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S1FW00    | Notebook    | [9ea0dccce0](https://linux-hardware.org/?probe=9ea0dccce0) | Dec 11, 2023 |
| Dell          | 07VWPG A01                  | Desktop     | [a9ad39cd38](https://linux-hardware.org/?probe=a9ad39cd38) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [e3afd2e002](https://linux-hardware.org/?probe=e3afd2e002) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [656bfe20f4](https://linux-hardware.org/?probe=656bfe20f4) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [b1c994920c](https://linux-hardware.org/?probe=b1c994920c) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [cc7c14dd72](https://linux-hardware.org/?probe=cc7c14dd72) | Dec 11, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [bd1772e0a0](https://linux-hardware.org/?probe=bd1772e0a0) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [b7c06bf365](https://linux-hardware.org/?probe=b7c06bf365) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [8badd81a74](https://linux-hardware.org/?probe=8badd81a74) | Dec 11, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [8a11fe8107](https://linux-hardware.org/?probe=8a11fe8107) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [448dc8ed72](https://linux-hardware.org/?probe=448dc8ed72) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [472c013f53](https://linux-hardware.org/?probe=472c013f53) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [8cb24408c9](https://linux-hardware.org/?probe=8cb24408c9) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [df2e9cf858](https://linux-hardware.org/?probe=df2e9cf858) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [c8d223020d](https://linux-hardware.org/?probe=c8d223020d) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [70364f28ab](https://linux-hardware.org/?probe=70364f28ab) | Dec 11, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [deced1a058](https://linux-hardware.org/?probe=deced1a058) | Dec 11, 2023 |
| Gigabyte      | D-700                       | Desktop     | [18e3ee84cc](https://linux-hardware.org/?probe=18e3ee84cc) | Dec 11, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [e96af5da4d](https://linux-hardware.org/?probe=e96af5da4d) | Dec 11, 2023 |
| ASUSTek       | X202E                       | Notebook    | [3d45a17e7f](https://linux-hardware.org/?probe=3d45a17e7f) | Dec 11, 2023 |
| Intel         | H61                         | Desktop     | [611b51b6c1](https://linux-hardware.org/?probe=611b51b6c1) | Dec 11, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [32d436e221](https://linux-hardware.org/?probe=32d436e221) | Dec 11, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [f8b53d98cc](https://linux-hardware.org/?probe=f8b53d98cc) | Dec 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [c2dd869dcf](https://linux-hardware.org/?probe=c2dd869dcf) | Dec 10, 2023 |
| Acer          | Aspire 7520                 | Notebook    | [70405c9fa1](https://linux-hardware.org/?probe=70405c9fa1) | Dec 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [e70fd6bdb5](https://linux-hardware.org/?probe=e70fd6bdb5) | Dec 10, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [59846b1d85](https://linux-hardware.org/?probe=59846b1d85) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [96b05f5be6](https://linux-hardware.org/?probe=96b05f5be6) | Dec 10, 2023 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [9b40e5889d](https://linux-hardware.org/?probe=9b40e5889d) | Dec 10, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [11f857231b](https://linux-hardware.org/?probe=11f857231b) | Dec 10, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [48fffc72b6](https://linux-hardware.org/?probe=48fffc72b6) | Dec 10, 2023 |
| Sony          | VGN-AR51M                   | Notebook    | [d1c67ac651](https://linux-hardware.org/?probe=d1c67ac651) | Dec 10, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [237db70b40](https://linux-hardware.org/?probe=237db70b40) | Dec 10, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [5d07d03602](https://linux-hardware.org/?probe=5d07d03602) | Dec 10, 2023 |
| VIT           | M2400-01                    | Mini pc     | [a7c0e03aa5](https://linux-hardware.org/?probe=a7c0e03aa5) | Dec 10, 2023 |
| Acer          | Aspire 6930G                | Notebook    | [eea9d9e525](https://linux-hardware.org/?probe=eea9d9e525) | Dec 10, 2023 |
| Pegatron      | IPMH61P1                    | Desktop     | [0d0474a798](https://linux-hardware.org/?probe=0d0474a798) | Dec 10, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [1eaf3dd454](https://linux-hardware.org/?probe=1eaf3dd454) | Dec 10, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [1e96233f59](https://linux-hardware.org/?probe=1e96233f59) | Dec 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [b9c86c02e7](https://linux-hardware.org/?probe=b9c86c02e7) | Dec 10, 2023 |
| Dell          | 0TP406                      | Desktop     | [1b81a10a36](https://linux-hardware.org/?probe=1b81a10a36) | Dec 10, 2023 |
| Panasonic     | CF-33-1                     | Tablet      | [f4a9e22711](https://linux-hardware.org/?probe=f4a9e22711) | Dec 10, 2023 |
| Panasonic     | CF-33-1                     | Tablet      | [8651294cc1](https://linux-hardware.org/?probe=8651294cc1) | Dec 10, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [37214745c0](https://linux-hardware.org/?probe=37214745c0) | Dec 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [aa1aa7d695](https://linux-hardware.org/?probe=aa1aa7d695) | Dec 10, 2023 |
| Intel         | NUC7i5BNB J31144-309        | Mini pc     | [0b97746a2b](https://linux-hardware.org/?probe=0b97746a2b) | Dec 10, 2023 |
| Intel         | NUC7i5BNB J31144-309        | Mini pc     | [d68da09499](https://linux-hardware.org/?probe=d68da09499) | Dec 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [4c72e88035](https://linux-hardware.org/?probe=4c72e88035) | Dec 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [9f822d68bb](https://linux-hardware.org/?probe=9f822d68bb) | Dec 10, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [3831586b47](https://linux-hardware.org/?probe=3831586b47) | Dec 10, 2023 |
| Lenovo        | ThinkPad E560 20EWS0M900    | Notebook    | [c753b49018](https://linux-hardware.org/?probe=c753b49018) | Dec 10, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [e87dcf9ee2](https://linux-hardware.org/?probe=e87dcf9ee2) | Dec 10, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [e5f4045026](https://linux-hardware.org/?probe=e5f4045026) | Dec 10, 2023 |
| Irbis         | NB290                       | Notebook    | [dcea177b24](https://linux-hardware.org/?probe=dcea177b24) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [63b05d421b](https://linux-hardware.org/?probe=63b05d421b) | Dec 10, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [d49b26fe0c](https://linux-hardware.org/?probe=d49b26fe0c) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1ecb7258d5](https://linux-hardware.org/?probe=1ecb7258d5) | Dec 10, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [8e1c466924](https://linux-hardware.org/?probe=8e1c466924) | Dec 09, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [2bc305a065](https://linux-hardware.org/?probe=2bc305a065) | Dec 09, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [f8bd255155](https://linux-hardware.org/?probe=f8bd255155) | Dec 09, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [1465cf0eac](https://linux-hardware.org/?probe=1465cf0eac) | Dec 09, 2023 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | Desktop     | [af3f6d16ac](https://linux-hardware.org/?probe=af3f6d16ac) | Dec 09, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [0de5475eb8](https://linux-hardware.org/?probe=0de5475eb8) | Dec 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f0bcb0009e](https://linux-hardware.org/?probe=f0bcb0009e) | Dec 09, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [0989548d19](https://linux-hardware.org/?probe=0989548d19) | Dec 09, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [5121b6a20c](https://linux-hardware.org/?probe=5121b6a20c) | Dec 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [04ed98dd4a](https://linux-hardware.org/?probe=04ed98dd4a) | Dec 09, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [d9d22e25cb](https://linux-hardware.org/?probe=d9d22e25cb) | Dec 09, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [e35af0e70a](https://linux-hardware.org/?probe=e35af0e70a) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [237110c8c0](https://linux-hardware.org/?probe=237110c8c0) | Dec 09, 2023 |
| Medion        | P8614                       | Notebook    | [a7689ec115](https://linux-hardware.org/?probe=a7689ec115) | Dec 09, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [283ae39c42](https://linux-hardware.org/?probe=283ae39c42) | Dec 09, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ae0afe3e73](https://linux-hardware.org/?probe=ae0afe3e73) | Dec 09, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [a869089d9a](https://linux-hardware.org/?probe=a869089d9a) | Dec 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e800d95054](https://linux-hardware.org/?probe=e800d95054) | Dec 09, 2023 |
| Gigabyte      | B550M K                     | Desktop     | [bbf66f105d](https://linux-hardware.org/?probe=bbf66f105d) | Dec 09, 2023 |
| Gigabyte      | B550M K                     | Desktop     | [e44ea6cf67](https://linux-hardware.org/?probe=e44ea6cf67) | Dec 09, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [945c57d421](https://linux-hardware.org/?probe=945c57d421) | Dec 09, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [9f3fb37b64](https://linux-hardware.org/?probe=9f3fb37b64) | Dec 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [130b4fa28a](https://linux-hardware.org/?probe=130b4fa28a) | Dec 09, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [acb9e267c5](https://linux-hardware.org/?probe=acb9e267c5) | Dec 09, 2023 |
| Lenovo        | ThinkCentre M58p 6234AE5    | Desktop     | [4cf3efef96](https://linux-hardware.org/?probe=4cf3efef96) | Dec 09, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [490ad0881a](https://linux-hardware.org/?probe=490ad0881a) | Dec 09, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [26c99ed573](https://linux-hardware.org/?probe=26c99ed573) | Dec 09, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [22d34b64f2](https://linux-hardware.org/?probe=22d34b64f2) | Dec 09, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [634d1d56b8](https://linux-hardware.org/?probe=634d1d56b8) | Dec 09, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [3c06d9b7a8](https://linux-hardware.org/?probe=3c06d9b7a8) | Dec 09, 2023 |
| Notebook      | N24_25JU                    | Notebook    | [48dc91498c](https://linux-hardware.org/?probe=48dc91498c) | Dec 09, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [3c17f8cde4](https://linux-hardware.org/?probe=3c17f8cde4) | Dec 08, 2023 |
| Dell          | Latitude 7400               | Notebook    | [71ba2c1398](https://linux-hardware.org/?probe=71ba2c1398) | Dec 08, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H3C... | Notebook    | [2c3c1f7ad2](https://linux-hardware.org/?probe=2c3c1f7ad2) | Dec 08, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b00663cde8](https://linux-hardware.org/?probe=b00663cde8) | Dec 08, 2023 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [957289310d](https://linux-hardware.org/?probe=957289310d) | Dec 08, 2023 |
| HP            | Pavilion dv6                | Notebook    | [3ffa0f12b7](https://linux-hardware.org/?probe=3ffa0f12b7) | Dec 08, 2023 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [a7dccd5888](https://linux-hardware.org/?probe=a7dccd5888) | Dec 08, 2023 |
| ASRock        | H510M-ITX/ac                | Desktop     | [4850c05764](https://linux-hardware.org/?probe=4850c05764) | Dec 08, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [7082f03269](https://linux-hardware.org/?probe=7082f03269) | Dec 08, 2023 |
| Sony          | SVE1713Q1EB                 | Notebook    | [482c83143b](https://linux-hardware.org/?probe=482c83143b) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [6cd48c055d](https://linux-hardware.org/?probe=6cd48c055d) | Dec 08, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [6452783d8a](https://linux-hardware.org/?probe=6452783d8a) | Dec 08, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [4f2070eb15](https://linux-hardware.org/?probe=4f2070eb15) | Dec 08, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [69df0251d9](https://linux-hardware.org/?probe=69df0251d9) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [2d85c45e57](https://linux-hardware.org/?probe=2d85c45e57) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [01177d538f](https://linux-hardware.org/?probe=01177d538f) | Dec 08, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [c23042b293](https://linux-hardware.org/?probe=c23042b293) | Dec 08, 2023 |
| Timi          | RedmiBook 13 R              | Notebook    | [6b3b67cc8b](https://linux-hardware.org/?probe=6b3b67cc8b) | Dec 08, 2023 |
| HP            | Compaq 6720s                | Notebook    | [63200c945b](https://linux-hardware.org/?probe=63200c945b) | Dec 08, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [9af0655380](https://linux-hardware.org/?probe=9af0655380) | Dec 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [56eae53402](https://linux-hardware.org/?probe=56eae53402) | Dec 08, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [44e608daff](https://linux-hardware.org/?probe=44e608daff) | Dec 08, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [254b936002](https://linux-hardware.org/?probe=254b936002) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [afc78e9ba2](https://linux-hardware.org/?probe=afc78e9ba2) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [a6b0055398](https://linux-hardware.org/?probe=a6b0055398) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [8198e47786](https://linux-hardware.org/?probe=8198e47786) | Dec 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [529932bcd4](https://linux-hardware.org/?probe=529932bcd4) | Dec 08, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [37a360ec8a](https://linux-hardware.org/?probe=37a360ec8a) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [6e7af6d32b](https://linux-hardware.org/?probe=6e7af6d32b) | Dec 07, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [b4da4c1d8a](https://linux-hardware.org/?probe=b4da4c1d8a) | Dec 07, 2023 |
| ASUSTek       | X555BP                      | Notebook    | [b7680df948](https://linux-hardware.org/?probe=b7680df948) | Dec 07, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [b56d3e163b](https://linux-hardware.org/?probe=b56d3e163b) | Dec 07, 2023 |
| HP            | 8184 X4                     | Desktop     | [bad08bc9a0](https://linux-hardware.org/?probe=bad08bc9a0) | Dec 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [16b14ad0a7](https://linux-hardware.org/?probe=16b14ad0a7) | Dec 07, 2023 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | Notebook    | [f7511ff0d0](https://linux-hardware.org/?probe=f7511ff0d0) | Dec 07, 2023 |
| HP            | 18E9                        | Desktop     | [80f4acdcfd](https://linux-hardware.org/?probe=80f4acdcfd) | Dec 07, 2023 |
| Dell          | Latitude E5540              | Notebook    | [208d70d734](https://linux-hardware.org/?probe=208d70d734) | Dec 07, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [572afff34b](https://linux-hardware.org/?probe=572afff34b) | Dec 07, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [2fc70886c6](https://linux-hardware.org/?probe=2fc70886c6) | Dec 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [04dd7cde77](https://linux-hardware.org/?probe=04dd7cde77) | Dec 07, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [d96cb11edc](https://linux-hardware.org/?probe=d96cb11edc) | Dec 07, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [f85ac7ef66](https://linux-hardware.org/?probe=f85ac7ef66) | Dec 07, 2023 |
| Pegatron      | IPMH61P1                    | Desktop     | [264229998e](https://linux-hardware.org/?probe=264229998e) | Dec 07, 2023 |
| Lenovo        | ThinkPad T540p 20BFS2600... | Notebook    | [b6ec0a5c30](https://linux-hardware.org/?probe=b6ec0a5c30) | Dec 07, 2023 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [66917779ad](https://linux-hardware.org/?probe=66917779ad) | Dec 07, 2023 |
| Supermicro    | X9DRW                       | Server      | [d94874353c](https://linux-hardware.org/?probe=d94874353c) | Dec 07, 2023 |
| HP            | 09F8h                       | Desktop     | [c988ff1e96](https://linux-hardware.org/?probe=c988ff1e96) | Dec 07, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [5f96473345](https://linux-hardware.org/?probe=5f96473345) | Dec 07, 2023 |
| Medion        | Unknown                     | Notebook    | [58a27e1f8f](https://linux-hardware.org/?probe=58a27e1f8f) | Dec 07, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [237e573bfe](https://linux-hardware.org/?probe=237e573bfe) | Dec 07, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [8a4776f925](https://linux-hardware.org/?probe=8a4776f925) | Dec 07, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [0e087e0b94](https://linux-hardware.org/?probe=0e087e0b94) | Dec 07, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [7843d89bd3](https://linux-hardware.org/?probe=7843d89bd3) | Dec 07, 2023 |
| ASUSTek       | PRIME B650M-A AX II         | Desktop     | [68ae754b57](https://linux-hardware.org/?probe=68ae754b57) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [cf8f25ba97](https://linux-hardware.org/?probe=cf8f25ba97) | Dec 07, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [e9ddadffad](https://linux-hardware.org/?probe=e9ddadffad) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [673016ba0f](https://linux-hardware.org/?probe=673016ba0f) | Dec 07, 2023 |
| MSI           | CX62 7QL                    | Notebook    | [33cd9ad75d](https://linux-hardware.org/?probe=33cd9ad75d) | Dec 07, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [018aab637c](https://linux-hardware.org/?probe=018aab637c) | Dec 07, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [90ffb00870](https://linux-hardware.org/?probe=90ffb00870) | Dec 07, 2023 |
| Gigabyte      | G1.Sniper M3                | Desktop     | [d81e8e0452](https://linux-hardware.org/?probe=d81e8e0452) | Dec 07, 2023 |
| Gigabyte      | G1.Sniper M3                | Desktop     | [ac25bf99a5](https://linux-hardware.org/?probe=ac25bf99a5) | Dec 07, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [d124640ef5](https://linux-hardware.org/?probe=d124640ef5) | Dec 06, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [77a21a8df4](https://linux-hardware.org/?probe=77a21a8df4) | Dec 06, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [766521b0e1](https://linux-hardware.org/?probe=766521b0e1) | Dec 06, 2023 |
| HP            | 0AECh D                     | Desktop     | [d58cc2f609](https://linux-hardware.org/?probe=d58cc2f609) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [2c7c5b2119](https://linux-hardware.org/?probe=2c7c5b2119) | Dec 06, 2023 |
| HP            | Pavilion 17                 | Notebook    | [93ecaf88d6](https://linux-hardware.org/?probe=93ecaf88d6) | Dec 06, 2023 |
| Dell          | Latitude E5440              | Notebook    | [56987fc258](https://linux-hardware.org/?probe=56987fc258) | Dec 06, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [2d3f4ca82c](https://linux-hardware.org/?probe=2d3f4ca82c) | Dec 06, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [d1337f45be](https://linux-hardware.org/?probe=d1337f45be) | Dec 06, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [f2a72d7b29](https://linux-hardware.org/?probe=f2a72d7b29) | Dec 06, 2023 |
| ALDO          | C2016-BSWI-D2               | Desktop     | [4dec414c2e](https://linux-hardware.org/?probe=4dec414c2e) | Dec 06, 2023 |
| Dell          | Latitude E5440              | Notebook    | [6cdafbd9d1](https://linux-hardware.org/?probe=6cdafbd9d1) | Dec 06, 2023 |
| Dell          | 0RY007                      | Desktop     | [2c93573995](https://linux-hardware.org/?probe=2c93573995) | Dec 06, 2023 |
| ASUSTek       | GL702VSK                    | Notebook    | [d8547acd71](https://linux-hardware.org/?probe=d8547acd71) | Dec 06, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [ee4cab6d84](https://linux-hardware.org/?probe=ee4cab6d84) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [30c6080de4](https://linux-hardware.org/?probe=30c6080de4) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [0226f5545c](https://linux-hardware.org/?probe=0226f5545c) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [cf63284103](https://linux-hardware.org/?probe=cf63284103) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [6d0a010766](https://linux-hardware.org/?probe=6d0a010766) | Dec 06, 2023 |
| Supermicro    | X9DRW                       | Desktop     | [485f869e9b](https://linux-hardware.org/?probe=485f869e9b) | Dec 06, 2023 |
| ASUSTek       | UX510UWK                    | Notebook    | [30a7e501ad](https://linux-hardware.org/?probe=30a7e501ad) | Dec 06, 2023 |
| HP            | 82F1                        | Desktop     | [3a292e8aaa](https://linux-hardware.org/?probe=3a292e8aaa) | Dec 06, 2023 |
| Supermicro    | X9DRW                       | Server      | [4cdf66bc48](https://linux-hardware.org/?probe=4cdf66bc48) | Dec 06, 2023 |
| Dell          | 0P42M6 A01                  | Desktop     | [2deb37f773](https://linux-hardware.org/?probe=2deb37f773) | Dec 06, 2023 |
| Supermicro    | X10DRL-i                    | Desktop     | [f30d1a0a40](https://linux-hardware.org/?probe=f30d1a0a40) | Dec 06, 2023 |
| Supermicro    | X10DRL-i                    | Desktop     | [7f6c70bab0](https://linux-hardware.org/?probe=7f6c70bab0) | Dec 06, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [747cf33a22](https://linux-hardware.org/?probe=747cf33a22) | Dec 06, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [896cdac0e2](https://linux-hardware.org/?probe=896cdac0e2) | Dec 06, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [c7a3277bfa](https://linux-hardware.org/?probe=c7a3277bfa) | Dec 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [52ee43b1e5](https://linux-hardware.org/?probe=52ee43b1e5) | Dec 06, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [1b3a42caac](https://linux-hardware.org/?probe=1b3a42caac) | Dec 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9b6cdd96f4](https://linux-hardware.org/?probe=9b6cdd96f4) | Dec 06, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [3176cf1b45](https://linux-hardware.org/?probe=3176cf1b45) | Dec 06, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [7d11b1aed9](https://linux-hardware.org/?probe=7d11b1aed9) | Dec 06, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [68f538dbc9](https://linux-hardware.org/?probe=68f538dbc9) | Dec 06, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [e31bacf81a](https://linux-hardware.org/?probe=e31bacf81a) | Dec 06, 2023 |
| HP            | Notebook                    | Notebook    | [8431ed2498](https://linux-hardware.org/?probe=8431ed2498) | Dec 06, 2023 |
| YiFang        | NXM1106CWP                  | Tablet      | [2a43b298f8](https://linux-hardware.org/?probe=2a43b298f8) | Dec 06, 2023 |
| HP            | 2AF7                        | Desktop     | [4d98ac755f](https://linux-hardware.org/?probe=4d98ac755f) | Dec 06, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [6bac81f943](https://linux-hardware.org/?probe=6bac81f943) | Dec 06, 2023 |
| Unknown       | G-GLK01                     | Desktop     | [5c5efbafff](https://linux-hardware.org/?probe=5c5efbafff) | Dec 06, 2023 |
| Lenovo        | ThinkPad E460 20ET0014US    | Notebook    | [b1cf294932](https://linux-hardware.org/?probe=b1cf294932) | Dec 06, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c1a6e3eb9e](https://linux-hardware.org/?probe=c1a6e3eb9e) | Dec 06, 2023 |
| Dell          | Inspiron 7472               | Notebook    | [ef77efb220](https://linux-hardware.org/?probe=ef77efb220) | Dec 06, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [a59c9d08c1](https://linux-hardware.org/?probe=a59c9d08c1) | Dec 06, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [b70e2e4765](https://linux-hardware.org/?probe=b70e2e4765) | Dec 05, 2023 |
| NEC Infron... | MS-9888 10h                 | Desktop     | [8a1a2b9976](https://linux-hardware.org/?probe=8a1a2b9976) | Dec 05, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [3f2a30851e](https://linux-hardware.org/?probe=3f2a30851e) | Dec 05, 2023 |
| Supermicro    | X9DRW-7/iTPF                | Server      | [9ec583de91](https://linux-hardware.org/?probe=9ec583de91) | Dec 05, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [1297909900](https://linux-hardware.org/?probe=1297909900) | Dec 05, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [0e8746ee4e](https://linux-hardware.org/?probe=0e8746ee4e) | Dec 05, 2023 |
| Toshiba       | Satellite S75-B             | Notebook    | [dbec4c564e](https://linux-hardware.org/?probe=dbec4c564e) | Dec 05, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [196d6bc9e8](https://linux-hardware.org/?probe=196d6bc9e8) | Dec 05, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [a47e6e3616](https://linux-hardware.org/?probe=a47e6e3616) | Dec 05, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [1a357b73a8](https://linux-hardware.org/?probe=1a357b73a8) | Dec 05, 2023 |
| Google        | Robo                        | Notebook    | [52fb2b7262](https://linux-hardware.org/?probe=52fb2b7262) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [5e59f15fed](https://linux-hardware.org/?probe=5e59f15fed) | Dec 05, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [8d46bb6a3c](https://linux-hardware.org/?probe=8d46bb6a3c) | Dec 05, 2023 |
| Google        | Robo                        | Notebook    | [f18235e8ca](https://linux-hardware.org/?probe=f18235e8ca) | Dec 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0JC0... | Notebook    | [11fdf05513](https://linux-hardware.org/?probe=11fdf05513) | Dec 05, 2023 |
| Google        | Relm                        | Notebook    | [577c8dbfe0](https://linux-hardware.org/?probe=577c8dbfe0) | Dec 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f665409b48](https://linux-hardware.org/?probe=f665409b48) | Dec 05, 2023 |
| HP            | 3646h                       | Desktop     | [df62144cda](https://linux-hardware.org/?probe=df62144cda) | Dec 05, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [8fbe891429](https://linux-hardware.org/?probe=8fbe891429) | Dec 05, 2023 |
| SDZ           | X133                        | Notebook    | [6e7c008a6a](https://linux-hardware.org/?probe=6e7c008a6a) | Dec 05, 2023 |
| HP            | 339A                        | Desktop     | [53b6aa6808](https://linux-hardware.org/?probe=53b6aa6808) | Dec 05, 2023 |
| Hardkernel    | Odroid XU4                  | Soc         | [8ce2d62401](https://linux-hardware.org/?probe=8ce2d62401) | Dec 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [6d790b9d8c](https://linux-hardware.org/?probe=6d790b9d8c) | Dec 05, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [3937003fd0](https://linux-hardware.org/?probe=3937003fd0) | Dec 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [3306bdcb6c](https://linux-hardware.org/?probe=3306bdcb6c) | Dec 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [c64bc46e3a](https://linux-hardware.org/?probe=c64bc46e3a) | Dec 05, 2023 |
| HP            | 550                         | Notebook    | [a3dc2d4062](https://linux-hardware.org/?probe=a3dc2d4062) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [fa61806ea8](https://linux-hardware.org/?probe=fa61806ea8) | Dec 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [becdc5222d](https://linux-hardware.org/?probe=becdc5222d) | Dec 05, 2023 |
| Dell          | Latitude E6440              | Notebook    | [74db313788](https://linux-hardware.org/?probe=74db313788) | Dec 05, 2023 |
| ASUSTek       | GL702VSK                    | Notebook    | [20e6076fd3](https://linux-hardware.org/?probe=20e6076fd3) | Dec 05, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [a13beb506c](https://linux-hardware.org/?probe=a13beb506c) | Dec 05, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [ee36539c94](https://linux-hardware.org/?probe=ee36539c94) | Dec 05, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [8725242a43](https://linux-hardware.org/?probe=8725242a43) | Dec 04, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [599d20e4ef](https://linux-hardware.org/?probe=599d20e4ef) | Dec 04, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [bab7262ca5](https://linux-hardware.org/?probe=bab7262ca5) | Dec 04, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [0c467a2af3](https://linux-hardware.org/?probe=0c467a2af3) | Dec 04, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [dfc33bff7a](https://linux-hardware.org/?probe=dfc33bff7a) | Dec 04, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [9cbacbf139](https://linux-hardware.org/?probe=9cbacbf139) | Dec 04, 2023 |
| Supermicro    | X10DRG-Q                    | Desktop     | [5844ee0f43](https://linux-hardware.org/?probe=5844ee0f43) | Dec 04, 2023 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [9edd2d878e](https://linux-hardware.org/?probe=9edd2d878e) | Dec 04, 2023 |
| HP            | Laptop 17t-cn200            | Notebook    | [26c356c486](https://linux-hardware.org/?probe=26c356c486) | Dec 04, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [a1b25ec823](https://linux-hardware.org/?probe=a1b25ec823) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [fd95385327](https://linux-hardware.org/?probe=fd95385327) | Dec 04, 2023 |
| Supermicro    | X10DRG-Q                    | Desktop     | [175bbb55cb](https://linux-hardware.org/?probe=175bbb55cb) | Dec 04, 2023 |
| Foxconn       | 2AB1                        | Desktop     | [93bbf17266](https://linux-hardware.org/?probe=93bbf17266) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c2d2b59a76](https://linux-hardware.org/?probe=c2d2b59a76) | Dec 04, 2023 |
| MSI           | Z97 GAMING 7                | Desktop     | [887cbb52f3](https://linux-hardware.org/?probe=887cbb52f3) | Dec 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [cea029e467](https://linux-hardware.org/?probe=cea029e467) | Dec 04, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [29d253c1cd](https://linux-hardware.org/?probe=29d253c1cd) | Dec 04, 2023 |
| ZOTAC         | NM10                        | Desktop     | [a567bbf0a7](https://linux-hardware.org/?probe=a567bbf0a7) | Dec 04, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [d088539ba0](https://linux-hardware.org/?probe=d088539ba0) | Dec 04, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [6658671550](https://linux-hardware.org/?probe=6658671550) | Dec 04, 2023 |
| ASRock        | H97 Performance             | Desktop     | [dc36b5ee77](https://linux-hardware.org/?probe=dc36b5ee77) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [b5726693c1](https://linux-hardware.org/?probe=b5726693c1) | Dec 04, 2023 |
| Dell          | 05R2TK A01                  | All in one  | [441bd970bb](https://linux-hardware.org/?probe=441bd970bb) | Dec 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [18e4bdaa86](https://linux-hardware.org/?probe=18e4bdaa86) | Dec 04, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [dc816e1423](https://linux-hardware.org/?probe=dc816e1423) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [80d59e5b16](https://linux-hardware.org/?probe=80d59e5b16) | Dec 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6c24e26ef9](https://linux-hardware.org/?probe=6c24e26ef9) | Dec 03, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [8bca63eb54](https://linux-hardware.org/?probe=8bca63eb54) | Dec 03, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [c093780dc5](https://linux-hardware.org/?probe=c093780dc5) | Dec 03, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [25fe8ecf87](https://linux-hardware.org/?probe=25fe8ecf87) | Dec 03, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [0926acf98a](https://linux-hardware.org/?probe=0926acf98a) | Dec 03, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [6e9e9a487a](https://linux-hardware.org/?probe=6e9e9a487a) | Dec 03, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [c265401f64](https://linux-hardware.org/?probe=c265401f64) | Dec 03, 2023 |
| Dell          | Precision 5680              | Notebook    | [6982d86e8c](https://linux-hardware.org/?probe=6982d86e8c) | Dec 03, 2023 |
| ASUSTek       | GL703VM                     | Notebook    | [616bfbe220](https://linux-hardware.org/?probe=616bfbe220) | Dec 03, 2023 |
| MSI           | A75MA-G55                   | Desktop     | [02a8179117](https://linux-hardware.org/?probe=02a8179117) | Dec 03, 2023 |
| HP            | 2B46                        | Desktop     | [5bfce44b96](https://linux-hardware.org/?probe=5bfce44b96) | Dec 03, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [1f8c488e82](https://linux-hardware.org/?probe=1f8c488e82) | Dec 03, 2023 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [d481339f2f](https://linux-hardware.org/?probe=d481339f2f) | Dec 03, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [0ae6e0f882](https://linux-hardware.org/?probe=0ae6e0f882) | Dec 03, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [f04a8e4722](https://linux-hardware.org/?probe=f04a8e4722) | Dec 03, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8d214d7977](https://linux-hardware.org/?probe=8d214d7977) | Dec 03, 2023 |
| Lenovo        | IdeaPad 320S-15IKB 81BQ     | Notebook    | [9cedc35586](https://linux-hardware.org/?probe=9cedc35586) | Dec 03, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [3cd6a2e9dc](https://linux-hardware.org/?probe=3cd6a2e9dc) | Dec 03, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [a0306c58e5](https://linux-hardware.org/?probe=a0306c58e5) | Dec 03, 2023 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [359c30e001](https://linux-hardware.org/?probe=359c30e001) | Dec 03, 2023 |
| MSI           | PS63 Modern 8RC             | Notebook    | [76f07c96fd](https://linux-hardware.org/?probe=76f07c96fd) | Dec 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [2d7c4215b0](https://linux-hardware.org/?probe=2d7c4215b0) | Dec 03, 2023 |
| Lenovo        | ThinkPad T440p 20AWA02M0... | Notebook    | [c977bbe2c4](https://linux-hardware.org/?probe=c977bbe2c4) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S9UY00    | Notebook    | [318a41e343](https://linux-hardware.org/?probe=318a41e343) | Dec 03, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fecd529c90](https://linux-hardware.org/?probe=fecd529c90) | Dec 03, 2023 |
| Google        | Wukong                      | Desktop     | [e665343907](https://linux-hardware.org/?probe=e665343907) | Dec 03, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [f5b7c2899a](https://linux-hardware.org/?probe=f5b7c2899a) | Dec 03, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [4cb46d807d](https://linux-hardware.org/?probe=4cb46d807d) | Dec 03, 2023 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [4587cd55f9](https://linux-hardware.org/?probe=4587cd55f9) | Dec 03, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [0c74d4b343](https://linux-hardware.org/?probe=0c74d4b343) | Dec 03, 2023 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [c5f6a282c6](https://linux-hardware.org/?probe=c5f6a282c6) | Dec 03, 2023 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [ee04da9a30](https://linux-hardware.org/?probe=ee04da9a30) | Dec 03, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [e2d48a6b41](https://linux-hardware.org/?probe=e2d48a6b41) | Dec 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1d3323974f](https://linux-hardware.org/?probe=1d3323974f) | Dec 03, 2023 |
| Lenovo        | ThinkPad T420 4180PBG       | Notebook    | [7922226a1c](https://linux-hardware.org/?probe=7922226a1c) | Dec 02, 2023 |
| Shuttle       | DS10U                       | Desktop     | [4e3fa0f845](https://linux-hardware.org/?probe=4e3fa0f845) | Dec 02, 2023 |
| Lenovo        | ThinkPad T420 4180PBG       | Notebook    | [cb2b5c10a7](https://linux-hardware.org/?probe=cb2b5c10a7) | Dec 02, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [ff08e31f5b](https://linux-hardware.org/?probe=ff08e31f5b) | Dec 02, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [165571d0a3](https://linux-hardware.org/?probe=165571d0a3) | Dec 02, 2023 |
| Dell          | Latitude E6430              | Notebook    | [fedc3b8a8d](https://linux-hardware.org/?probe=fedc3b8a8d) | Dec 02, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [9cdf3ecc77](https://linux-hardware.org/?probe=9cdf3ecc77) | Dec 02, 2023 |
| Medion        | E3223                       | Convertible | [1c5d81c584](https://linux-hardware.org/?probe=1c5d81c584) | Dec 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHS... | Notebook    | [b7acc6efe8](https://linux-hardware.org/?probe=b7acc6efe8) | Dec 02, 2023 |
| ASUSTek       | K53E                        | Notebook    | [4b184d1d81](https://linux-hardware.org/?probe=4b184d1d81) | Dec 02, 2023 |
| MSI           | GE72 6QD                    | Notebook    | [2e250b81a4](https://linux-hardware.org/?probe=2e250b81a4) | Dec 02, 2023 |
| MSI           | GE72 6QF                    | Notebook    | [2cce4d92fe](https://linux-hardware.org/?probe=2cce4d92fe) | Dec 02, 2023 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [3b3d0cb740](https://linux-hardware.org/?probe=3b3d0cb740) | Dec 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [5923988290](https://linux-hardware.org/?probe=5923988290) | Dec 02, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [514428be56](https://linux-hardware.org/?probe=514428be56) | Dec 02, 2023 |
| Dell          | Latitude E6430              | Notebook    | [980a0b89b5](https://linux-hardware.org/?probe=980a0b89b5) | Dec 02, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [61e9871a33](https://linux-hardware.org/?probe=61e9871a33) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [a1a93224e4](https://linux-hardware.org/?probe=a1a93224e4) | Dec 02, 2023 |
| SK hynix      | HyBook                      | Notebook    | [4c0f06eb94](https://linux-hardware.org/?probe=4c0f06eb94) | Dec 02, 2023 |
| Sony          | VPCEB1S1E                   | Notebook    | [d240ac5f41](https://linux-hardware.org/?probe=d240ac5f41) | Dec 02, 2023 |
| Dell          | G15 5510                    | Notebook    | [bdfca2648a](https://linux-hardware.org/?probe=bdfca2648a) | Dec 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e62aa2185a](https://linux-hardware.org/?probe=e62aa2185a) | Dec 02, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [186eb0ce63](https://linux-hardware.org/?probe=186eb0ce63) | Dec 02, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [6f6f496558](https://linux-hardware.org/?probe=6f6f496558) | Dec 01, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2f6585635f](https://linux-hardware.org/?probe=2f6585635f) | Dec 01, 2023 |
| Acer          | Predator PH317-52           | Notebook    | [013bd43bc7](https://linux-hardware.org/?probe=013bd43bc7) | Dec 01, 2023 |
| Supermicro    | X8DTU                       | Server      | [93c745dd29](https://linux-hardware.org/?probe=93c745dd29) | Dec 01, 2023 |
| Supermicro    | X8DTU                       | Server      | [65d0d8ca5c](https://linux-hardware.org/?probe=65d0d8ca5c) | Dec 01, 2023 |
| Dell          | Studio 1737                 | Notebook    | [4e400ded4b](https://linux-hardware.org/?probe=4e400ded4b) | Dec 01, 2023 |
| HP            | 3398                        | Desktop     | [26c9b1fa25](https://linux-hardware.org/?probe=26c9b1fa25) | Dec 01, 2023 |
| Supermicro    | X8DAH                       | Server      | [54aa001997](https://linux-hardware.org/?probe=54aa001997) | Dec 01, 2023 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [1645df2234](https://linux-hardware.org/?probe=1645df2234) | Dec 01, 2023 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [570da1b5b2](https://linux-hardware.org/?probe=570da1b5b2) | Dec 01, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4cbc340e7c](https://linux-hardware.org/?probe=4cbc340e7c) | Dec 01, 2023 |
| Supermicro    | X10SLM-F                    | Server      | [7e32def223](https://linux-hardware.org/?probe=7e32def223) | Dec 01, 2023 |
| Gigabyte      | B150M-DS3H-CF               | Desktop     | [50332d509a](https://linux-hardware.org/?probe=50332d509a) | Dec 01, 2023 |
| Toshiba       | Satellite C870-1F3          | Notebook    | [adb628ff38](https://linux-hardware.org/?probe=adb628ff38) | Dec 01, 2023 |
| Toshiba       | Satellite C870-1F3          | Notebook    | [93907ea0f4](https://linux-hardware.org/?probe=93907ea0f4) | Dec 01, 2023 |
| Dell          | Latitude 5520               | Notebook    | [5b61695af2](https://linux-hardware.org/?probe=5b61695af2) | Dec 01, 2023 |
| Supermicro    | X9DRW                       | Server      | [aa8a2f6c7d](https://linux-hardware.org/?probe=aa8a2f6c7d) | Dec 01, 2023 |
| Supermicro    | X8DTT                       | Server      | [a0a8c069f4](https://linux-hardware.org/?probe=a0a8c069f4) | Dec 01, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [bc4ff37548](https://linux-hardware.org/?probe=bc4ff37548) | Dec 01, 2023 |
| Acer          | Predator PH317-52           | Notebook    | [abb14dcedb](https://linux-hardware.org/?probe=abb14dcedb) | Dec 01, 2023 |
| Lenovo        | K14 G2 IRU 21G1             | Notebook    | [22af506155](https://linux-hardware.org/?probe=22af506155) | Dec 01, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [90e07856e4](https://linux-hardware.org/?probe=90e07856e4) | Dec 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [e7cb2d834a](https://linux-hardware.org/?probe=e7cb2d834a) | Dec 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [89ec59d64e](https://linux-hardware.org/?probe=89ec59d64e) | Dec 01, 2023 |
| Lenovo        | ThinkPad X60 1706M8U        | Notebook    | [ab0582fe71](https://linux-hardware.org/?probe=ab0582fe71) | Dec 01, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [9c81768619](https://linux-hardware.org/?probe=9c81768619) | Dec 01, 2023 |
| Dell          | Latitude E6520              | Notebook    | [1cb2209cef](https://linux-hardware.org/?probe=1cb2209cef) | Dec 01, 2023 |
| Fujitsu       | D2939-A1 S26361-D2939-A1... | Server      | [f2d7b77663](https://linux-hardware.org/?probe=f2d7b77663) | Dec 01, 2023 |
| Fujitsu       | D2939-A1 S26361-D2939-A1... | Server      | [43b4648ca6](https://linux-hardware.org/?probe=43b4648ca6) | Dec 01, 2023 |
| HP            | 2B0B 100                    | Desktop     | [48cb125554](https://linux-hardware.org/?probe=48cb125554) | Dec 01, 2023 |
| Dell          | XPS420                      | Notebook    | [2204a9646d](https://linux-hardware.org/?probe=2204a9646d) | Dec 01, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [80d4969c23](https://linux-hardware.org/?probe=80d4969c23) | Dec 01, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [d59279f095](https://linux-hardware.org/?probe=d59279f095) | Dec 01, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [41ae74c0ef](https://linux-hardware.org/?probe=41ae74c0ef) | Dec 01, 2023 |
| HP            | Pavilion 15                 | Notebook    | [4282694224](https://linux-hardware.org/?probe=4282694224) | Dec 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [dd82ddf299](https://linux-hardware.org/?probe=dd82ddf299) | Dec 01, 2023 |
| Lenovo        | ThinkPad T490s 20NYS02A0... | Notebook    | [a23499d148](https://linux-hardware.org/?probe=a23499d148) | Nov 30, 2023 |
| Acer          | Aspire V5-573               | Notebook    | [8a76c8baac](https://linux-hardware.org/?probe=8a76c8baac) | Nov 30, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [7b700be3e2](https://linux-hardware.org/?probe=7b700be3e2) | Nov 30, 2023 |
| HP            | 15                          | Notebook    | [df51360bdd](https://linux-hardware.org/?probe=df51360bdd) | Nov 30, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [2f200bcee9](https://linux-hardware.org/?probe=2f200bcee9) | Nov 30, 2023 |
| Clevo         | C4100/C5100                 | Notebook    | [8e2637b70f](https://linux-hardware.org/?probe=8e2637b70f) | Nov 30, 2023 |
| Clevo         | C4100/C5100                 | Notebook    | [ea98614215](https://linux-hardware.org/?probe=ea98614215) | Nov 30, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [120ad9d1f3](https://linux-hardware.org/?probe=120ad9d1f3) | Nov 30, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [3e97ecc95d](https://linux-hardware.org/?probe=3e97ecc95d) | Nov 30, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [988e96f53c](https://linux-hardware.org/?probe=988e96f53c) | Nov 30, 2023 |
| Kelyx Arge... | Kelyx KL3450                | Notebook    | [0d6ca3bd1a](https://linux-hardware.org/?probe=0d6ca3bd1a) | Nov 30, 2023 |
| Intel         | S1200RP G62251-407          | Server      | [806a2b0d98](https://linux-hardware.org/?probe=806a2b0d98) | Nov 30, 2023 |
| ASUSTek       | Q505UAR                     | Convertible | [2f1181b138](https://linux-hardware.org/?probe=2f1181b138) | Nov 30, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [bb1fc18586](https://linux-hardware.org/?probe=bb1fc18586) | Nov 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f36afef418](https://linux-hardware.org/?probe=f36afef418) | Nov 30, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [bc9394652a](https://linux-hardware.org/?probe=bc9394652a) | Nov 30, 2023 |
| MSI           | Prestige 16Studio A13VF     | Notebook    | [dc93bfeb80](https://linux-hardware.org/?probe=dc93bfeb80) | Nov 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d92b5d4caf](https://linux-hardware.org/?probe=d92b5d4caf) | Nov 30, 2023 |
| Lenovo        | B50-50 80S2                 | Notebook    | [51d5653319](https://linux-hardware.org/?probe=51d5653319) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [96a30d5a91](https://linux-hardware.org/?probe=96a30d5a91) | Nov 30, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [4c24f3fddf](https://linux-hardware.org/?probe=4c24f3fddf) | Nov 30, 2023 |
| HP            | 2B3B                        | All in one  | [6b7b46ffef](https://linux-hardware.org/?probe=6b7b46ffef) | Nov 30, 2023 |
| Kllisre       | X79 V2.72S                  | Desktop     | [cd66ba8786](https://linux-hardware.org/?probe=cd66ba8786) | Nov 30, 2023 |
| System Mfg    | Unknown                     | Tablet      | [198c15e90a](https://linux-hardware.org/?probe=198c15e90a) | Nov 30, 2023 |
| Irbis         | NB290                       | Notebook    | [75805d6558](https://linux-hardware.org/?probe=75805d6558) | Nov 29, 2023 |
| ASUSTek       | CG5275                      | Desktop     | [13c8d80b5d](https://linux-hardware.org/?probe=13c8d80b5d) | Nov 29, 2023 |
| Google        | Nautilus                    | Notebook    | [1b255e77a3](https://linux-hardware.org/?probe=1b255e77a3) | Nov 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [3bbd848840](https://linux-hardware.org/?probe=3bbd848840) | Nov 29, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [1074904ba9](https://linux-hardware.org/?probe=1074904ba9) | Nov 29, 2023 |
| PC Special... | Recoil 16                   | Notebook    | [3dd3569b17](https://linux-hardware.org/?probe=3dd3569b17) | Nov 29, 2023 |
| Foxconn       | nT-330i                     | Desktop     | [e20a015b3a](https://linux-hardware.org/?probe=e20a015b3a) | Nov 29, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [cd5316e290](https://linux-hardware.org/?probe=cd5316e290) | Nov 29, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [29e5da6013](https://linux-hardware.org/?probe=29e5da6013) | Nov 29, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [6074c742c1](https://linux-hardware.org/?probe=6074c742c1) | Nov 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2d1452d207](https://linux-hardware.org/?probe=2d1452d207) | Nov 29, 2023 |
| ASUSTek       | N71Jq                       | Notebook    | [f13e32bb82](https://linux-hardware.org/?probe=f13e32bb82) | Nov 29, 2023 |
| HP            | 1905                        | Desktop     | [8d1dfc94c1](https://linux-hardware.org/?probe=8d1dfc94c1) | Nov 29, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | Notebook    | [0524ad397b](https://linux-hardware.org/?probe=0524ad397b) | Nov 29, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [2ad6007c7f](https://linux-hardware.org/?probe=2ad6007c7f) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK E5512              | Notebook    | [9df65d1a3d](https://linux-hardware.org/?probe=9df65d1a3d) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [d1dc329e65](https://linux-hardware.org/?probe=d1dc329e65) | Nov 29, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [15c78cff63](https://linux-hardware.org/?probe=15c78cff63) | Nov 29, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4d9e778bd2](https://linux-hardware.org/?probe=4d9e778bd2) | Nov 29, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [e6c589b9b0](https://linux-hardware.org/?probe=e6c589b9b0) | Nov 29, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | Notebook    | [6b83c6bd43](https://linux-hardware.org/?probe=6b83c6bd43) | Nov 29, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [d9e4a9a2cd](https://linux-hardware.org/?probe=d9e4a9a2cd) | Nov 29, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e3e8042ebf](https://linux-hardware.org/?probe=e3e8042ebf) | Nov 29, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [62cb0079ed](https://linux-hardware.org/?probe=62cb0079ed) | Nov 29, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [6965a13f84](https://linux-hardware.org/?probe=6965a13f84) | Nov 29, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [bb2313602b](https://linux-hardware.org/?probe=bb2313602b) | Nov 29, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [363701a47c](https://linux-hardware.org/?probe=363701a47c) | Nov 29, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [77e37462eb](https://linux-hardware.org/?probe=77e37462eb) | Nov 29, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [a9f36d870b](https://linux-hardware.org/?probe=a9f36d870b) | Nov 28, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [da395dd09e](https://linux-hardware.org/?probe=da395dd09e) | Nov 28, 2023 |
| Neousys Te... | Nuvo-2600 Series Rev. ES... | Server      | [d04f27866a](https://linux-hardware.org/?probe=d04f27866a) | Nov 28, 2023 |
| Pegatron      | EVANS                       | Desktop     | [0d15cfcfb2](https://linux-hardware.org/?probe=0d15cfcfb2) | Nov 28, 2023 |
| MSI           | GF63 Thin 11UD              | Notebook    | [bde4e92728](https://linux-hardware.org/?probe=bde4e92728) | Nov 28, 2023 |
| ASUSTek       | X200CA                      | Notebook    | [d0ea54e4fa](https://linux-hardware.org/?probe=d0ea54e4fa) | Nov 28, 2023 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [ebf45c9457](https://linux-hardware.org/?probe=ebf45c9457) | Nov 28, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [ee5fe89209](https://linux-hardware.org/?probe=ee5fe89209) | Nov 28, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [bbfe8e99fc](https://linux-hardware.org/?probe=bbfe8e99fc) | Nov 28, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [4fbfde63e3](https://linux-hardware.org/?probe=4fbfde63e3) | Nov 28, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [b1f194a955](https://linux-hardware.org/?probe=b1f194a955) | Nov 28, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [ff997b6ca3](https://linux-hardware.org/?probe=ff997b6ca3) | Nov 28, 2023 |
| HP            | 18E5                        | Desktop     | [a078eaa1d4](https://linux-hardware.org/?probe=a078eaa1d4) | Nov 28, 2023 |
| Sony          | VPCF13M1E                   | Notebook    | [4a6e054f68](https://linux-hardware.org/?probe=4a6e054f68) | Nov 28, 2023 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [72f7a18db5](https://linux-hardware.org/?probe=72f7a18db5) | Nov 28, 2023 |
| HP            | 8055                        | Desktop     | [a35b553ba1](https://linux-hardware.org/?probe=a35b553ba1) | Nov 28, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [144a7d4106](https://linux-hardware.org/?probe=144a7d4106) | Nov 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [49fad3d40c](https://linux-hardware.org/?probe=49fad3d40c) | Nov 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [33388f794b](https://linux-hardware.org/?probe=33388f794b) | Nov 28, 2023 |
| HP            | G60                         | Notebook    | [eb7f66cedc](https://linux-hardware.org/?probe=eb7f66cedc) | Nov 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [34cbcf6478](https://linux-hardware.org/?probe=34cbcf6478) | Nov 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [9f9e92a1f6](https://linux-hardware.org/?probe=9f9e92a1f6) | Nov 28, 2023 |
| Dell          | Latitude 7440               | Notebook    | [aa4dce8576](https://linux-hardware.org/?probe=aa4dce8576) | Nov 27, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [4819314a84](https://linux-hardware.org/?probe=4819314a84) | Nov 27, 2023 |
| Intel         | JSL MRD                     | Desktop     | [6c635f4665](https://linux-hardware.org/?probe=6c635f4665) | Nov 27, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [f5f1058473](https://linux-hardware.org/?probe=f5f1058473) | Nov 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [330921f980](https://linux-hardware.org/?probe=330921f980) | Nov 27, 2023 |
| Lenovo        | ThinkPad T520 4243PH3       | Notebook    | [63ba3b10d4](https://linux-hardware.org/?probe=63ba3b10d4) | Nov 27, 2023 |
| Dell          | Precision 5520              | Notebook    | [4d773def1d](https://linux-hardware.org/?probe=4d773def1d) | Nov 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8739388aac](https://linux-hardware.org/?probe=8739388aac) | Nov 27, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [85217c44b9](https://linux-hardware.org/?probe=85217c44b9) | Nov 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [b760a588ee](https://linux-hardware.org/?probe=b760a588ee) | Nov 27, 2023 |
| Intel         | HM570                       | Desktop     | [69eb6aa616](https://linux-hardware.org/?probe=69eb6aa616) | Nov 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [9ba9e50996](https://linux-hardware.org/?probe=9ba9e50996) | Nov 27, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [fc0cf53ff2](https://linux-hardware.org/?probe=fc0cf53ff2) | Nov 27, 2023 |
| Supermicro    | X9DRW                       | Server      | [9659a14b3a](https://linux-hardware.org/?probe=9659a14b3a) | Nov 27, 2023 |
| Supermicro    | X8DTT                       | Server      | [9441542792](https://linux-hardware.org/?probe=9441542792) | Nov 27, 2023 |
| Supermicro    | X8DTU                       | Server      | [3e4d7ab614](https://linux-hardware.org/?probe=3e4d7ab614) | Nov 27, 2023 |
| HUAWEI        | BC11HGSC0 V100R003          | Server      | [b5b7543006](https://linux-hardware.org/?probe=b5b7543006) | Nov 27, 2023 |
| Supermicro    | X8DTU                       | Server      | [08be50f76f](https://linux-hardware.org/?probe=08be50f76f) | Nov 27, 2023 |
| Dell          | 0WWR83 A05                  | Server      | [dc735b9dc9](https://linux-hardware.org/?probe=dc735b9dc9) | Nov 27, 2023 |
| Supermicro    | X8DTU                       | Server      | [3ec4e5f544](https://linux-hardware.org/?probe=3ec4e5f544) | Nov 27, 2023 |
| Supermicro    | X10DRL-i                    | Desktop     | [5ef70291dd](https://linux-hardware.org/?probe=5ef70291dd) | Nov 27, 2023 |
| Supermicro    | X10DRU-i+A                  | Desktop     | [1dc89f1473](https://linux-hardware.org/?probe=1dc89f1473) | Nov 27, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [be5b9fb33d](https://linux-hardware.org/?probe=be5b9fb33d) | Nov 27, 2023 |
| Supermicro    | X8DTL                       | Server      | [98e4f680a0](https://linux-hardware.org/?probe=98e4f680a0) | Nov 27, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [bbfc69ba62](https://linux-hardware.org/?probe=bbfc69ba62) | Nov 27, 2023 |
| Supermicro    | X9DRW                       | Server      | [824c861a29](https://linux-hardware.org/?probe=824c861a29) | Nov 27, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [8b660a9e8d](https://linux-hardware.org/?probe=8b660a9e8d) | Nov 27, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [6dac06687b](https://linux-hardware.org/?probe=6dac06687b) | Nov 27, 2023 |
| Supermicro    | X9DRW                       | Desktop     | [86356d229c](https://linux-hardware.org/?probe=86356d229c) | Nov 27, 2023 |
| Supermicro    | X10DRL-i                    | Desktop     | [258e338541](https://linux-hardware.org/?probe=258e338541) | Nov 27, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [75e08bab32](https://linux-hardware.org/?probe=75e08bab32) | Nov 27, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [0063d09560](https://linux-hardware.org/?probe=0063d09560) | Nov 27, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [fa631784ee](https://linux-hardware.org/?probe=fa631784ee) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [dd750184ff](https://linux-hardware.org/?probe=dd750184ff) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [275dfaabe4](https://linux-hardware.org/?probe=275dfaabe4) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [7a9789da62](https://linux-hardware.org/?probe=7a9789da62) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [792780c033](https://linux-hardware.org/?probe=792780c033) | Nov 27, 2023 |
| Supermicro    | X9DRW                       | Desktop     | [c764c8a98e](https://linux-hardware.org/?probe=c764c8a98e) | Nov 27, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [03586846aa](https://linux-hardware.org/?probe=03586846aa) | Nov 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [7d36a1431f](https://linux-hardware.org/?probe=7d36a1431f) | Nov 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [c594f5ae7a](https://linux-hardware.org/?probe=c594f5ae7a) | Nov 27, 2023 |
| Gigabyte      | Z490 UD                     | Desktop     | [38d2e85b40](https://linux-hardware.org/?probe=38d2e85b40) | Nov 27, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [aadba04a83](https://linux-hardware.org/?probe=aadba04a83) | Nov 27, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [caddbf7d43](https://linux-hardware.org/?probe=caddbf7d43) | Nov 27, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DU14    | Notebook    | [37cb36a6fa](https://linux-hardware.org/?probe=37cb36a6fa) | Nov 27, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [63c8ac9339](https://linux-hardware.org/?probe=63c8ac9339) | Nov 27, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [59d1928371](https://linux-hardware.org/?probe=59d1928371) | Nov 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [ade10d9872](https://linux-hardware.org/?probe=ade10d9872) | Nov 27, 2023 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [9704afc74e](https://linux-hardware.org/?probe=9704afc74e) | Nov 27, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [1138c4c71b](https://linux-hardware.org/?probe=1138c4c71b) | Nov 27, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [096f432812](https://linux-hardware.org/?probe=096f432812) | Nov 27, 2023 |
| Intel         | HM570                       | Desktop     | [1cb9f8c891](https://linux-hardware.org/?probe=1cb9f8c891) | Nov 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [06bf1b0f79](https://linux-hardware.org/?probe=06bf1b0f79) | Nov 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [956dbda516](https://linux-hardware.org/?probe=956dbda516) | Nov 26, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | Notebook    | [92f23bf41c](https://linux-hardware.org/?probe=92f23bf41c) | Nov 26, 2023 |
| SHENZHEN Y... | XBOOK-3                     | Notebook    | [beeefc2461](https://linux-hardware.org/?probe=beeefc2461) | Nov 26, 2023 |
| Dell          | Latitude 5590               | Notebook    | [cd823db120](https://linux-hardware.org/?probe=cd823db120) | Nov 26, 2023 |
| Intel         | H61                         | Desktop     | [5146767aa6](https://linux-hardware.org/?probe=5146767aa6) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [c090300c01](https://linux-hardware.org/?probe=c090300c01) | Nov 26, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [203375fd6b](https://linux-hardware.org/?probe=203375fd6b) | Nov 26, 2023 |
| HP            | Notebook                    | Notebook    | [d13874e201](https://linux-hardware.org/?probe=d13874e201) | Nov 26, 2023 |
| HP            | Notebook                    | Notebook    | [6d348c3a7a](https://linux-hardware.org/?probe=6d348c3a7a) | Nov 26, 2023 |
| MSI           | Modern 15 A10M              | Notebook    | [105e84e282](https://linux-hardware.org/?probe=105e84e282) | Nov 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [351dde4845](https://linux-hardware.org/?probe=351dde4845) | Nov 26, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [9827dd50ff](https://linux-hardware.org/?probe=9827dd50ff) | Nov 26, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [8378baf644](https://linux-hardware.org/?probe=8378baf644) | Nov 26, 2023 |
| Intel         | B75                         | Desktop     | [fab278b6c3](https://linux-hardware.org/?probe=fab278b6c3) | Nov 26, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [a2e8f90bc6](https://linux-hardware.org/?probe=a2e8f90bc6) | Nov 26, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [2ca445207e](https://linux-hardware.org/?probe=2ca445207e) | Nov 26, 2023 |
| Lenovo        | ThinkPad R400 7440DQ6       | Notebook    | [3720b52e84](https://linux-hardware.org/?probe=3720b52e84) | Nov 26, 2023 |
| Lenovo        | Aptio CRB 31900058 STD      | Mini pc     | [bd08d681a3](https://linux-hardware.org/?probe=bd08d681a3) | Nov 26, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [47ec694370](https://linux-hardware.org/?probe=47ec694370) | Nov 26, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [22dbbee029](https://linux-hardware.org/?probe=22dbbee029) | Nov 26, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [ed6b4827c0](https://linux-hardware.org/?probe=ed6b4827c0) | Nov 26, 2023 |
| HP            | Notebook                    | Notebook    | [671f5f59ac](https://linux-hardware.org/?probe=671f5f59ac) | Nov 26, 2023 |
| BCM           | RX67Q                       | Desktop     | [59c8825b99](https://linux-hardware.org/?probe=59c8825b99) | Nov 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [7ea3637c4f](https://linux-hardware.org/?probe=7ea3637c4f) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [d3e69f25a6](https://linux-hardware.org/?probe=d3e69f25a6) | Nov 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [7b30223421](https://linux-hardware.org/?probe=7b30223421) | Nov 26, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ed18c0bb54](https://linux-hardware.org/?probe=ed18c0bb54) | Nov 26, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [06a2e5b5a8](https://linux-hardware.org/?probe=06a2e5b5a8) | Nov 26, 2023 |
| Dell          | 03X6X0 A06                  | Server      | [df0eef24f1](https://linux-hardware.org/?probe=df0eef24f1) | Nov 26, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [6e903b92f6](https://linux-hardware.org/?probe=6e903b92f6) | Nov 26, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e09777761c](https://linux-hardware.org/?probe=e09777761c) | Nov 26, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [ac50bb87af](https://linux-hardware.org/?probe=ac50bb87af) | Nov 26, 2023 |
| Dell          | 0GYT9V A00                  | Desktop     | [a0fe7b3987](https://linux-hardware.org/?probe=a0fe7b3987) | Nov 26, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [5910ef90fd](https://linux-hardware.org/?probe=5910ef90fd) | Nov 26, 2023 |
| AZW           | MINI S 10                   | Desktop     | [32c65d600d](https://linux-hardware.org/?probe=32c65d600d) | Nov 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a41a3d9679](https://linux-hardware.org/?probe=a41a3d9679) | Nov 26, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [6505e0c278](https://linux-hardware.org/?probe=6505e0c278) | Nov 26, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [d327adff80](https://linux-hardware.org/?probe=d327adff80) | Nov 26, 2023 |
| Gigabyte      | Z170X-Gaming 5              | Desktop     | [555e8e34b6](https://linux-hardware.org/?probe=555e8e34b6) | Nov 26, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [b9c7f5de5b](https://linux-hardware.org/?probe=b9c7f5de5b) | Nov 26, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [e7c6d5b018](https://linux-hardware.org/?probe=e7c6d5b018) | Nov 26, 2023 |
| Panasonic     | CF-53JALZY1M                | Notebook    | [e90faa0f97](https://linux-hardware.org/?probe=e90faa0f97) | Nov 26, 2023 |
| Gigabyte      | Z170X-Gaming 5              | Desktop     | [b153aa9661](https://linux-hardware.org/?probe=b153aa9661) | Nov 26, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [36cde2f22a](https://linux-hardware.org/?probe=36cde2f22a) | Nov 25, 2023 |
| HP            | 81C7 MVB 0C                 | Server      | [03e2a5bac1](https://linux-hardware.org/?probe=03e2a5bac1) | Nov 25, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [5ebfeb3392](https://linux-hardware.org/?probe=5ebfeb3392) | Nov 25, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [99daa92571](https://linux-hardware.org/?probe=99daa92571) | Nov 25, 2023 |
| Foxconn       | H61MXT1/F2/-S/-V            | Desktop     | [0529750c82](https://linux-hardware.org/?probe=0529750c82) | Nov 25, 2023 |
| HP            | 2B3E                        | All in one  | [f7c1b836da](https://linux-hardware.org/?probe=f7c1b836da) | Nov 25, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a9d03c8349](https://linux-hardware.org/?probe=a9d03c8349) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [ea362b85cf](https://linux-hardware.org/?probe=ea362b85cf) | Nov 25, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3ff2b07867](https://linux-hardware.org/?probe=3ff2b07867) | Nov 25, 2023 |
| Dell          | 0RT6HT A01                  | Desktop     | [aedd0fa212](https://linux-hardware.org/?probe=aedd0fa212) | Nov 25, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | Notebook    | [8973295484](https://linux-hardware.org/?probe=8973295484) | Nov 25, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [7359fe59a4](https://linux-hardware.org/?probe=7359fe59a4) | Nov 25, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [cff699d67d](https://linux-hardware.org/?probe=cff699d67d) | Nov 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [23914b5dc2](https://linux-hardware.org/?probe=23914b5dc2) | Nov 25, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [f8200e619a](https://linux-hardware.org/?probe=f8200e619a) | Nov 25, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [e7d72eaf1d](https://linux-hardware.org/?probe=e7d72eaf1d) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a727d2b744](https://linux-hardware.org/?probe=a727d2b744) | Nov 25, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [0a3b2f3f70](https://linux-hardware.org/?probe=0a3b2f3f70) | Nov 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [a719bb0ba3](https://linux-hardware.org/?probe=a719bb0ba3) | Nov 25, 2023 |
| Lenovo        | ThinkPad E560 20EWS0M900    | Notebook    | [344eaa9a2a](https://linux-hardware.org/?probe=344eaa9a2a) | Nov 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [436499a8a7](https://linux-hardware.org/?probe=436499a8a7) | Nov 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [d32adc8fff](https://linux-hardware.org/?probe=d32adc8fff) | Nov 24, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [4f1442fcc4](https://linux-hardware.org/?probe=4f1442fcc4) | Nov 24, 2023 |
| Dell          | Latitude D830               | Notebook    | [472b675869](https://linux-hardware.org/?probe=472b675869) | Nov 24, 2023 |
| Supermicro    | X8DAH                       | Server      | [b789dcc3ed](https://linux-hardware.org/?probe=b789dcc3ed) | Nov 24, 2023 |
| ASRock        | Z370 Killer SLI/ac          | Desktop     | [c2d9f4aefb](https://linux-hardware.org/?probe=c2d9f4aefb) | Nov 24, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [1bf1e47f81](https://linux-hardware.org/?probe=1bf1e47f81) | Nov 24, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [fb9766adc5](https://linux-hardware.org/?probe=fb9766adc5) | Nov 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [dcc7dca975](https://linux-hardware.org/?probe=dcc7dca975) | Nov 24, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [013087de59](https://linux-hardware.org/?probe=013087de59) | Nov 24, 2023 |
| Dell          | Latitude 7400               | Notebook    | [86a9de8212](https://linux-hardware.org/?probe=86a9de8212) | Nov 24, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [f4a77c64b0](https://linux-hardware.org/?probe=f4a77c64b0) | Nov 24, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [6a47a3a5de](https://linux-hardware.org/?probe=6a47a3a5de) | Nov 24, 2023 |
| Unknown       | Unknown                     | Notebook    | [b96d7a11ef](https://linux-hardware.org/?probe=b96d7a11ef) | Nov 24, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [9b44768188](https://linux-hardware.org/?probe=9b44768188) | Nov 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5a01c502bd](https://linux-hardware.org/?probe=5a01c502bd) | Nov 24, 2023 |
| Supermicro    | X8DT6                       | Server      | [81026f48e2](https://linux-hardware.org/?probe=81026f48e2) | Nov 24, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [6c51befccc](https://linux-hardware.org/?probe=6c51befccc) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [d262dd65d4](https://linux-hardware.org/?probe=d262dd65d4) | Nov 24, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [90499ad4f0](https://linux-hardware.org/?probe=90499ad4f0) | Nov 24, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [37984277e9](https://linux-hardware.org/?probe=37984277e9) | Nov 24, 2023 |
| Packard Be... | EasyNote ENLG71BM           | Notebook    | [25ae01fde2](https://linux-hardware.org/?probe=25ae01fde2) | Nov 24, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [aa4097f060](https://linux-hardware.org/?probe=aa4097f060) | Nov 24, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [e210f3a972](https://linux-hardware.org/?probe=e210f3a972) | Nov 24, 2023 |
| HP            | 2B0B 100                    | Desktop     | [908fb46664](https://linux-hardware.org/?probe=908fb46664) | Nov 24, 2023 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [1192e07984](https://linux-hardware.org/?probe=1192e07984) | Nov 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f17333cca3](https://linux-hardware.org/?probe=f17333cca3) | Nov 24, 2023 |
| HP            | 339A                        | Desktop     | [3168ba2168](https://linux-hardware.org/?probe=3168ba2168) | Nov 24, 2023 |
| HP            | 2B3E                        | All in one  | [c153fdce60](https://linux-hardware.org/?probe=c153fdce60) | Nov 24, 2023 |
| Dell          | 0TP406                      | Desktop     | [cc0c592ca4](https://linux-hardware.org/?probe=cc0c592ca4) | Nov 24, 2023 |
| Dell          | XPS 13 9315 2-in-1          | Tablet      | [3b70c03197](https://linux-hardware.org/?probe=3b70c03197) | Nov 24, 2023 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | Notebook    | [d733fc5f50](https://linux-hardware.org/?probe=d733fc5f50) | Nov 24, 2023 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | Notebook    | [17fd894479](https://linux-hardware.org/?probe=17fd894479) | Nov 24, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5417165a43](https://linux-hardware.org/?probe=5417165a43) | Nov 24, 2023 |
| HP            | Presario CQ61               | Notebook    | [5c7a775c76](https://linux-hardware.org/?probe=5c7a775c76) | Nov 24, 2023 |
| Samsung       | 960XFH                      | Notebook    | [2ad3d93589](https://linux-hardware.org/?probe=2ad3d93589) | Nov 24, 2023 |
| Dell          | Latitude E5550              | Notebook    | [96a4d03e8c](https://linux-hardware.org/?probe=96a4d03e8c) | Nov 23, 2023 |
| Supermicro    | X10DAI                      | Desktop     | [00b8c3c935](https://linux-hardware.org/?probe=00b8c3c935) | Nov 23, 2023 |
| Linx          | LINX1010L                   | Notebook    | [07d470eaac](https://linux-hardware.org/?probe=07d470eaac) | Nov 23, 2023 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [db22f8c316](https://linux-hardware.org/?probe=db22f8c316) | Nov 23, 2023 |
| AZW           | SEi V1.0                    | Desktop     | [d18296a25c](https://linux-hardware.org/?probe=d18296a25c) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0LE0... | Notebook    | [3da7eab7e8](https://linux-hardware.org/?probe=3da7eab7e8) | Nov 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b98f204f02](https://linux-hardware.org/?probe=b98f204f02) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [ca5e9fbf52](https://linux-hardware.org/?probe=ca5e9fbf52) | Nov 23, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [ae2a4ee822](https://linux-hardware.org/?probe=ae2a4ee822) | Nov 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [94fc35a5f9](https://linux-hardware.org/?probe=94fc35a5f9) | Nov 23, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [49ec5aa905](https://linux-hardware.org/?probe=49ec5aa905) | Nov 23, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d4a222fa3e](https://linux-hardware.org/?probe=d4a222fa3e) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [ab672024d6](https://linux-hardware.org/?probe=ab672024d6) | Nov 23, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [1c9b64b051](https://linux-hardware.org/?probe=1c9b64b051) | Nov 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [7d55f31a65](https://linux-hardware.org/?probe=7d55f31a65) | Nov 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 789       | 5.16%   |
| 5.15.0-52-generic | 680       | 4.45%   |
| 5.15.0-58-generic | 644       | 4.21%   |
| 6.2.0-26-generic  | 634       | 4.15%   |
| 5.19.0-32-generic | 562       | 3.68%   |
| 5.15.0-43-generic | 562       | 3.68%   |
| 5.19.0-35-generic | 533       | 3.49%   |
| 5.15.0-48-generic | 528       | 3.45%   |
| 5.15.0-47-generic | 490       | 3.21%   |
| 5.19.0-38-generic | 477       | 3.12%   |
| 5.19.0-41-generic | 452       | 2.96%   |
| 6.2.0-36-generic  | 427       | 2.79%   |
| 5.19.0-46-generic | 416       | 2.72%   |
| 5.15.0-46-generic | 407       | 2.66%   |
| 5.15.0-53-generic | 394       | 2.58%   |
| 6.2.0-37-generic  | 391       | 2.56%   |
| 5.15.0-25-generic | 347       | 2.27%   |
| 6.2.0-34-generic  | 343       | 2.24%   |
| 5.15.0-27-generic | 308       | 2.01%   |
| 6.2.0-33-generic  | 304       | 1.99%   |
| 5.19.0-43-generic | 287       | 1.88%   |
| 6.2.0-32-generic  | 285       | 1.86%   |
| 5.15.0-40-generic | 284       | 1.86%   |
| 5.15.0-41-generic | 279       | 1.82%   |
| 6.2.0-35-generic  | 245       | 1.6%    |
| 5.15.0-60-generic | 244       | 1.6%    |
| 5.15.0-50-generic | 242       | 1.58%   |
| 5.19.0-45-generic | 204       | 1.33%   |
| 5.15.0-57-generic | 202       | 1.32%   |
| 6.2.0-39-generic  | 183       | 1.2%    |
| 5.15.0-33-generic | 178       | 1.16%   |
| 5.19.0-40-generic | 172       | 1.13%   |
| 5.19.0-50-generic | 162       | 1.06%   |
| 5.15.0-30-generic | 157       | 1.03%   |
| 5.15.0-69-generic | 148       | 0.97%   |
| 5.15.0-39-generic | 135       | 0.88%   |
| 5.19.0-42-generic | 133       | 0.87%   |
| 6.2.0-31-generic  | 121       | 0.79%   |
| 5.15.0-37-generic | 107       | 0.7%    |
| 5.15.0-35-generic | 101       | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 7541      | 53.03%  |
| 5.19.0   | 3205      | 22.54%  |
| 6.2.0    | 2800      | 19.69%  |
| 5.17.0   | 93        | 0.65%   |
| 6.1.0    | 45        | 0.32%   |
| 5.14.0   | 38        | 0.27%   |
| 6.0.0    | 33        | 0.23%   |
| 5.13.0   | 31        | 0.22%   |
| 6.5.0    | 22        | 0.15%   |
| 5.18.0   | 17        | 0.12%   |
| 5.19.5   | 11        | 0.08%   |
| 6.4.0    | 10        | 0.07%   |
| 6.2.11   | 10        | 0.07%   |
| 5.10.110 | 10        | 0.07%   |
| 6.0.9    | 9         | 0.06%   |
| 6.2.2    | 8         | 0.06%   |
| 5.17.5   | 8         | 0.06%   |
| 5.17.1   | 8         | 0.06%   |
| 5.10.160 | 8         | 0.06%   |
| 6.3.1    | 7         | 0.05%   |
| 6.2.8    | 7         | 0.05%   |
| 6.2.10   | 7         | 0.05%   |
| 5.4.0    | 6         | 0.04%   |
| 6.4.3    | 5         | 0.04%   |
| 6.4.12   | 5         | 0.04%   |
| 6.4.11   | 5         | 0.04%   |
| 6.0.1    | 5         | 0.04%   |
| 5.18.10  | 5         | 0.04%   |
| 5.17.9   | 5         | 0.04%   |
| 6.6.0    | 4         | 0.03%   |
| 6.5.1    | 4         | 0.03%   |
| 6.4.6    | 4         | 0.03%   |
| 6.4.10   | 4         | 0.03%   |
| 6.3.3    | 4         | 0.03%   |
| 6.2.9    | 4         | 0.03%   |
| 6.2.6    | 4         | 0.03%   |
| 6.2.1    | 4         | 0.03%   |
| 6.1.12   | 4         | 0.03%   |
| 6.1.11   | 4         | 0.03%   |
| 6.0.6    | 4         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 7566      | 53.25%  |
| 5.19    | 3230      | 22.73%  |
| 6.2     | 2852      | 20.07%  |
| 5.17    | 136       | 0.96%   |
| 6.1     | 82        | 0.58%   |
| 6.0     | 66        | 0.46%   |
| 5.18    | 44        | 0.31%   |
| 6.5     | 39        | 0.27%   |
| 6.4     | 39        | 0.27%   |
| 5.14    | 38        | 0.27%   |
| 5.13    | 35        | 0.25%   |
| 5.10    | 23        | 0.16%   |
| 6.3     | 21        | 0.15%   |
| 5.4     | 9         | 0.06%   |
| 6.6     | 8         | 0.06%   |
| 5.16    | 7         | 0.05%   |
| 5.11    | 4         | 0.03%   |
| 5.8     | 3         | 0.02%   |
| 6.7     | 1         | 0.01%   |
| 6       | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |
| 4.19    | 1         | 0.01%   |
| 3.16    | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 13421     | 99.06%  |
| aarch64 | 119       | 0.88%   |
| armv7l  | 8         | 0.06%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 12587     | 92.7%   |
| Unknown           | 667       | 4.91%   |
| X-Cinnamon        | 111       | 0.82%   |
| GNUstep           | 73        | 0.54%   |
| GNOME Flashback   | 63        | 0.46%   |
| i3                | 21        | 0.15%   |
| GNOME Classic     | 18        | 0.13%   |
| Enlightenment     | 9         | 0.07%   |
| Cinnamon          | 7         | 0.05%   |
| sway              | 5         | 0.04%   |
| awesome           | 5         | 0.04%   |
| dwm               | 2         | 0.01%   |
| Yaru:ubuntu:GNOME | 1         | 0.01%   |
| xsession          | 1         | 0.01%   |
| ubuntu=GNOME      | 1         | 0.01%   |
| ubuntu            | 1         | 0.01%   |
| ratflow           | 1         | 0.01%   |
| Pantheon          | 1         | 0.01%   |
| openbox           | 1         | 0.01%   |
| INPT              | 1         | 0.01%   |
| i3-with-shmlog    | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 8577      | 62.17%  |
| X11     | 4342      | 31.48%  |
| Unknown | 439       | 3.18%   |
| Tty     | 435       | 3.15%   |
| Web     | 2         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM3    | 12094     | 88.85%  |
| Unknown | 1132      | 8.32%   |
| LightDM | 277       | 2.03%   |
| GDM     | 49        | 0.36%   |
| SDDM    | 45        | 0.33%   |
| SLiM    | 12        | 0.09%   |
| XDM     | 2         | 0.01%   |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 6227      | 45.8%   |
| de_DE   | 1125      | 8.27%   |
| fr_FR   | 838       | 6.16%   |
| en_GB   | 660       | 4.85%   |
| pt_BR   | 493       | 3.63%   |
| it_IT   | 435       | 3.2%    |
| en_IN   | 355       | 2.61%   |
| ru_RU   | 354       | 2.6%    |
| es_ES   | 316       | 2.32%   |
| en_CA   | 316       | 2.32%   |
| C       | 267       | 1.96%   |
| en_AU   | 195       | 1.43%   |
| pl_PL   | 175       | 1.29%   |
| nl_NL   | 138       | 1.01%   |
| Unknown | 129       | 0.95%   |
| zh_CN   | 99        | 0.73%   |
| es_MX   | 98        | 0.72%   |
| cs_CZ   | 87        | 0.64%   |
| hu_HU   | 77        | 0.57%   |
| es_AR   | 72        | 0.53%   |
| en_ZA   | 66        | 0.49%   |
| sv_SE   | 65        | 0.48%   |
| de_AT   | 64        | 0.47%   |
| ja_JP   | 60        | 0.44%   |
| pt_PT   | 56        | 0.41%   |
| tr_TR   | 50        | 0.37%   |
| de_CH   | 42        | 0.31%   |
| en_NZ   | 41        | 0.3%    |
| en_PH   | 40        | 0.29%   |
| fi_FI   | 39        | 0.29%   |
| es_CO   | 39        | 0.29%   |
| fr_BE   | 33        | 0.24%   |
| ko_KR   | 30        | 0.22%   |
| el_GR   | 27        | 0.2%    |
| da_DK   | 25        | 0.18%   |
| es_CL   | 24        | 0.18%   |
| en_IL   | 24        | 0.18%   |
| en_HK   | 24        | 0.18%   |
| fr_CA   | 23        | 0.17%   |
| nb_NO   | 22        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 8117      | 59.17%  |
| EFI  | 5601      | 40.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type          | Computers | Percent |
|---------------|-----------|---------|
| Ext4          | 10215     | 73.48%  |
| Tmpfs         | 2754      | 19.81%  |
| Overlay       | 478       | 3.44%   |
| Zfs           | 258       | 1.86%   |
| Btrfs         | 120       | 0.86%   |
| Xfs           | 40        | 0.29%   |
| Ext2          | 18        | 0.13%   |
| Ext3          | 10        | 0.07%   |
| Unknown       | 4         | 0.03%   |
| XXXX          | 1         | 0.01%   |
| XXX4          | 1         | 0.01%   |
| Jfs           | 1         | 0.01%   |
| Fuse.snapfuse | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 10026     | 72.49%  |
| Unknown | 2666      | 19.28%  |
| MBR     | 1138      | 8.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 12052     | 88.02%  |
| Yes       | 1640      | 11.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 8599      | 62.92%  |
| Yes       | 5067      | 37.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 2026      | 14.95%  |
| Hewlett-Packard         | 1962      | 14.48%  |
| Lenovo                  | 1903      | 14.05%  |
| Dell                    | 1898      | 14.01%  |
| MSI                     | 725       | 5.35%   |
| Gigabyte Technology     | 699       | 5.16%   |
| Acer                    | 692       | 5.11%   |
| Apple                   | 413       | 3.05%   |
| ASRock                  | 366       | 2.7%    |
| Intel                   | 258       | 1.9%    |
| HUAWEI                  | 191       | 1.41%   |
| Toshiba                 | 159       | 1.17%   |
| Unknown                 | 139       | 1.03%   |
| Supermicro              | 138       | 1.02%   |
| Samsung Electronics     | 138       | 1.02%   |
| Fujitsu                 | 135       | 1%      |
| Raspberry Pi Foundation | 83        | 0.61%   |
| Medion                  | 80        | 0.59%   |
| Sony                    | 77        | 0.57%   |
| Microsoft               | 64        | 0.47%   |
| Notebook                | 63        | 0.47%   |
| Google                  | 62        | 0.46%   |
| Alienware               | 56        | 0.41%   |
| AZW                     | 49        | 0.36%   |
| Timi                    | 48        | 0.35%   |
| Pegatron                | 46        | 0.34%   |
| Positivo                | 39        | 0.29%   |
| Foxconn                 | 39        | 0.29%   |
| Chuwi                   | 38        | 0.28%   |
| Packard Bell            | 34        | 0.25%   |
| Biostar                 | 32        | 0.24%   |
| LG Electronics          | 31        | 0.23%   |
| Gateway                 | 29        | 0.21%   |
| ECS                     | 24        | 0.18%   |
| BESSTAR Tech            | 23        | 0.17%   |
| AMI                     | 23        | 0.17%   |
| TUXEDO                  | 22        | 0.16%   |
| ETegro Technologies     | 22        | 0.16%   |
| Shuttle                 | 20        | 0.15%   |
| System76                | 19        | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 167       | 1.23%   |
| ASUS All Series                 | 111       | 0.82%   |
| RPi Raspberry Pi                | 49        | 0.36%   |
| HP Notebook                     | 44        | 0.32%   |
| Dell OptiPlex 7010              | 35        | 0.26%   |
| Dell OptiPlex 9020              | 32        | 0.24%   |
| ASUS PRIME A320M-K              | 28        | 0.21%   |
| Supermicro Super Server         | 24        | 0.18%   |
| ASUS TUF Gaming X570-PLUS       | 24        | 0.18%   |
| HP Pavilion Notebook            | 23        | 0.17%   |
| HP Pavilion 15                  | 22        | 0.16%   |
| ETegro Hyperion RS125 G4        | 22        | 0.16%   |
| Supermicro X9DRW                | 21        | 0.16%   |
| MSI MS-7C37                     | 21        | 0.16%   |
| Dell OptiPlex 3020              | 21        | 0.16%   |
| Dell Latitude 5420              | 21        | 0.16%   |
| HUAWEI BOM-WXX9                 | 20        | 0.15%   |
| HP Pavilion dv6                 | 20        | 0.15%   |
| Dell OptiPlex 790               | 20        | 0.15%   |
| Supermicro X8DTU                | 19        | 0.14%   |
| MSI MS-7C91                     | 19        | 0.14%   |
| MSI MS-7721                     | 19        | 0.14%   |
| HP Pavilion g6                  | 19        | 0.14%   |
| HP 15                           | 19        | 0.14%   |
| Dell XPS 15 9520                | 19        | 0.14%   |
| HUAWEI NBLB-WAX9N               | 18        | 0.13%   |
| HUAWEI BOD-WXX9                 | 18        | 0.13%   |
| HP EliteBook 840 G3             | 18        | 0.13%   |
| ASUS PRIME Z590-P               | 18        | 0.13%   |
| HUAWEI HVY-WXX9                 | 17        | 0.13%   |
| HP Pavilion dv7                 | 17        | 0.13%   |
| HP EliteBook 840 G8 Notebook PC | 17        | 0.13%   |
| HP EliteBook 840 G5             | 17        | 0.13%   |
| Dell XPS 15 9500                | 17        | 0.13%   |
| Dell OptiPlex 3050              | 17        | 0.13%   |
| ASUS ROG STRIX B550-F GAMING    | 17        | 0.13%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 16        | 0.12%   |
| Intel H61                       | 16        | 0.12%   |
| Dell XPS 15 7590                | 16        | 0.12%   |
| HUAWEI BOHB-WAX9                | 15        | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 790       | 5.83%   |
| Dell Latitude      | 474       | 3.5%    |
| Acer Aspire        | 455       | 3.36%   |
| Dell Inspiron      | 398       | 2.94%   |
| Lenovo IdeaPad     | 374       | 2.76%   |
| Dell OptiPlex      | 319       | 2.35%   |
| HP Pavilion        | 317       | 2.34%   |
| HP EliteBook       | 281       | 2.07%   |
| ASUS PRIME         | 255       | 1.88%   |
| ASUS VivoBook      | 247       | 1.82%   |
| ASUS ROG           | 241       | 1.78%   |
| Dell XPS           | 233       | 1.72%   |
| HP ProBook         | 206       | 1.52%   |
| Dell Precision     | 205       | 1.51%   |
| HP Laptop          | 188       | 1.39%   |
| Unknown            | 167       | 1.23%   |
| HP Compaq          | 142       | 1.05%   |
| ASUS TUF           | 133       | 0.98%   |
| Lenovo ThinkCentre | 129       | 0.95%   |
| Toshiba Satellite  | 125       | 0.92%   |
| HP ENVY            | 119       | 0.88%   |
| Dell Vostro        | 116       | 0.86%   |
| ASUS All           | 111       | 0.82%   |
| Lenovo Yoga        | 90        | 0.66%   |
| ASUS Zenbook       | 90        | 0.66%   |
| Lenovo ThinkBook   | 89        | 0.66%   |
| Lenovo Legion      | 86        | 0.63%   |
| RPi Raspberry      | 83        | 0.61%   |
| HP ZBook           | 73        | 0.54%   |
| HP EliteDesk       | 69        | 0.51%   |
| ASUS ASUS          | 68        | 0.5%    |
| Microsoft Surface  | 64        | 0.47%   |
| Acer Swift         | 61        | 0.45%   |
| Acer Nitro         | 59        | 0.44%   |
| Dell PowerEdge     | 54        | 0.4%    |
| HP ProDesk         | 49        | 0.36%   |
| Fujitsu ESPRIMO    | 48        | 0.35%   |
| Fujitsu LIFEBOOK   | 47        | 0.35%   |
| HP Notebook        | 45        | 0.33%   |
| HP Spectre         | 43        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 1629      | 12.02%  |
| 2020    | 1381      | 10.19%  |
| 2022    | 1104      | 8.15%   |
| 2019    | 1089      | 8.04%   |
| 2018    | 1062      | 7.84%   |
| 2013    | 930       | 6.86%   |
| 2012    | 898       | 6.63%   |
| 2017    | 828       | 6.11%   |
| 2011    | 780       | 5.76%   |
| 2014    | 723       | 5.34%   |
| 2015    | 678       | 5%      |
| 2016    | 586       | 4.33%   |
| 2010    | 546       | 4.03%   |
| 2009    | 358       | 2.64%   |
| 2023    | 334       | 2.47%   |
| 2008    | 296       | 2.18%   |
| 2007    | 147       | 1.09%   |
| Unknown | 129       | 0.95%   |
| 2006    | 42        | 0.31%   |
| 2005    | 7         | 0.05%   |
| 2004    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 7426      | 54.81%  |
| Desktop        | 4663      | 34.42%  |
| Convertible    | 438       | 3.23%   |
| Mini pc        | 277       | 2.04%   |
| Server         | 253       | 1.87%   |
| All in one     | 233       | 1.72%   |
| Tablet         | 133       | 0.98%   |
| System on chip | 124       | 0.92%   |
| Other          | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 12219     | 89.75%  |
| Enabled  | 1395      | 10.25%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 13469     | 99.42%  |
| Yes  | 79        | 0.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 3387      | 24.8%   |
| 16.01-24.0      | 3162      | 23.15%  |
| 8.01-16.0       | 2267      | 16.6%   |
| 3.01-4.0        | 1938      | 14.19%  |
| 32.01-64.0      | 1636      | 11.98%  |
| 64.01-256.0     | 570       | 4.17%   |
| 24.01-32.0      | 302       | 2.21%   |
| 1.01-2.0        | 215       | 1.57%   |
| 2.01-3.0        | 103       | 0.75%   |
| More than 256.0 | 64        | 0.47%   |
| 0.51-1.0        | 12        | 0.09%   |
| 0.01-0.5        | 2         | 0.01%   |
| Unknown         | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 4456      | 30.88%  |
| 1.01-2.0        | 4023      | 27.88%  |
| 4.01-8.0        | 2489      | 17.25%  |
| 3.01-4.0        | 2288      | 15.86%  |
| 8.01-16.0       | 740       | 5.13%   |
| 0.51-1.0        | 205       | 1.42%   |
| 16.01-24.0      | 97        | 0.67%   |
| 0.01-0.5        | 62        | 0.43%   |
| 24.01-32.0      | 38        | 0.26%   |
| 32.01-64.0      | 20        | 0.14%   |
| 64.01-256.0     | 8         | 0.06%   |
| More than 256.0 | 1         | 0.01%   |
| Unknown         | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 8745      | 63.34%  |
| 2      | 3217      | 23.3%   |
| 3      | 903       | 6.54%   |
| 4      | 389       | 2.82%   |
| 5      | 179       | 1.3%    |
| 0      | 142       | 1.03%   |
| 6      | 86        | 0.62%   |
| 7      | 56        | 0.41%   |
| 8      | 22        | 0.16%   |
| 9      | 21        | 0.15%   |
| 11     | 19        | 0.14%   |
| 10     | 9         | 0.07%   |
| 13     | 5         | 0.04%   |
| 12     | 3         | 0.02%   |
| 25     | 2         | 0.01%   |
| 40     | 1         | 0.01%   |
| 38     | 1         | 0.01%   |
| 27     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |
| 20     | 1         | 0.01%   |
| 17     | 1         | 0.01%   |
| 14     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 9289      | 68.23%  |
| Yes       | 4326      | 31.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 11132     | 82%     |
| No        | 2443      | 18%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10509     | 77.32%  |
| No        | 3082      | 22.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8712      | 63.86%  |
| No        | 4931      | 36.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2559      | 18.82%  |
| Germany      | 1434      | 10.55%  |
| France       | 968       | 7.12%   |
| Brazil       | 695       | 5.11%   |
| Russia       | 644       | 4.74%   |
| Italy        | 601       | 4.42%   |
| UK           | 569       | 4.18%   |
| Canada       | 405       | 2.98%   |
| Spain        | 403       | 2.96%   |
| India        | 396       | 2.91%   |
| Netherlands  | 311       | 2.29%   |
| Poland       | 302       | 2.22%   |
| Switzerland  | 257       | 1.89%   |
| Australia    | 207       | 1.52%   |
| Mexico       | 185       | 1.36%   |
| Sweden       | 165       | 1.21%   |
| Turkey       | 148       | 1.09%   |
| Czechia      | 141       | 1.04%   |
| Austria      | 137       | 1.01%   |
| Argentina    | 133       | 0.98%   |
| Belgium      | 131       | 0.96%   |
| Hungary      | 129       | 0.95%   |
| China        | 121       | 0.89%   |
| Romania      | 107       | 0.79%   |
| Portugal     | 104       | 0.76%   |
| Japan        | 95        | 0.7%    |
| Finland      | 95        | 0.7%    |
| Greece       | 91        | 0.67%   |
| Indonesia    | 79        | 0.58%   |
| South Africa | 73        | 0.54%   |
| Colombia     | 71        | 0.52%   |
| Bulgaria     | 68        | 0.5%    |
| Norway       | 66        | 0.49%   |
| Denmark      | 65        | 0.48%   |
| South Korea  | 59        | 0.43%   |
| Iran         | 54        | 0.4%    |
| New Zealand  | 53        | 0.39%   |
| Serbia       | 52        | 0.38%   |
| Egypt        | 51        | 0.38%   |
| Chile        | 50        | 0.37%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 259       | 1.83%   |
| Berlin            | 144       | 1.02%   |
| Paris             | 140       | 0.99%   |
| Zurich            | 110       | 0.78%   |
| Milan             | 99        | 0.7%    |
| St Petersburg     | 83        | 0.59%   |
| Madrid            | 83        | 0.59%   |
| Sao Paulo         | 78        | 0.55%   |
| Vienna            | 75        | 0.53%   |
| Rome              | 75        | 0.53%   |
| Warsaw            | 73        | 0.52%   |
| Sydney            | 67        | 0.47%   |
| Budapest          | 62        | 0.44%   |
| Munich            | 61        | 0.43%   |
| Istanbul          | 58        | 0.41%   |
| Prague            | 57        | 0.4%    |
| Barcelona         | 57        | 0.4%    |
| Hamburg           | 56        | 0.4%    |
| New York          | 55        | 0.39%   |
| Rio de Janeiro    | 54        | 0.38%   |
| Bengaluru         | 52        | 0.37%   |
| Toronto           | 51        | 0.36%   |
| Amsterdam         | 51        | 0.36%   |
| Melbourne         | 49        | 0.35%   |
| Helsinki          | 49        | 0.35%   |
| London            | 48        | 0.34%   |
| Athens            | 48        | 0.34%   |
| Los Angeles       | 47        | 0.33%   |
| Frankfurt am Main | 41        | 0.29%   |
| Sofia             | 39        | 0.28%   |
| Singapore         | 38        | 0.27%   |
| Tehran            | 37        | 0.26%   |
| Stockholm         | 37        | 0.26%   |
| Seattle           | 37        | 0.26%   |
| Mexico City       | 34        | 0.24%   |
| Belgrade          | 34        | 0.24%   |
| Dallas            | 33        | 0.23%   |
| Montreal          | 32        | 0.23%   |
| Bogotá           | 32        | 0.23%   |
| San Jose          | 31        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 3047      | 4166   | 16.2%   |
| WDC                         | 2414      | 3618   | 12.84%  |
| Seagate                     | 2338      | 3468   | 12.43%  |
| SanDisk                     | 1065      | 1359   | 5.66%   |
| Toshiba                     | 1036      | 1249   | 5.51%   |
| Kingston                    | 1009      | 1201   | 5.37%   |
| Unknown                     | 724       | 930    | 3.85%   |
| Crucial                     | 669       | 906    | 3.56%   |
| SK hynix                    | 652       | 736    | 3.47%   |
| Intel                       | 573       | 812    | 3.05%   |
| Micron Technology           | 475       | 543    | 2.53%   |
| Hitachi                     | 450       | 578    | 2.39%   |
| HGST                        | 298       | 400    | 1.58%   |
| A-DATA Technology           | 263       | 311    | 1.4%    |
| KIOXIA                      | 259       | 304    | 1.38%   |
| Apple                       | 219       | 267    | 1.16%   |
| China                       | 178       | 209    | 0.95%   |
| Phison Electronics          | 136       | 169    | 0.72%   |
| Unknown                     | 132       | 139    | 0.7%    |
| Phison                      | 131       | 158    | 0.7%    |
| Silicon Motion              | 130       | 158    | 0.69%   |
| Micron/Crucial Technology   | 119       | 147    | 0.63%   |
| Kingston Technology Company | 119       | 144    | 0.63%   |
| Intenso                     | 106       | 139    | 0.56%   |
| Fujitsu                     | 106       | 274    | 0.56%   |
| PNY                         | 104       | 121    | 0.55%   |
| SPCC                        | 100       | 145    | 0.53%   |
| LITEON                      | 83        | 91     | 0.44%   |
| Netac                       | 61        | 74     | 0.32%   |
| Transcend                   | 57        | 61     | 0.3%    |
| Hewlett-Packard             | 57        | 180    | 0.3%    |
| ADATA Technology            | 55        | 68     | 0.29%   |
| Patriot                     | 54        | 65     | 0.29%   |
| Gigabyte Technology         | 52        | 62     | 0.28%   |
| Team                        | 51        | 66     | 0.27%   |
| Lexar                       | 50        | 55     | 0.27%   |
| OCZ                         | 48        | 66     | 0.26%   |
| JMicron Technology          | 46        | 50     | 0.24%   |
| Corsair                     | 41        | 49     | 0.22%   |
| GOODRAM                     | 40        | 51     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 246       | 1.2%    |
| Kingston SA400S37240G 240GB SSD                       | 198       | 0.97%   |
| Seagate ST1000LM035-1RK172 1TB                        | 133       | 0.65%   |
| Unknown                                               | 132       | 0.64%   |
| Kingston SA400S37480G 480GB SSD                       | 131       | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 129       | 0.63%   |
| Samsung SSD 860 EVO 500GB                             | 121       | 0.59%   |
| Seagate ST500DM002-1BD142 500GB                       | 119       | 0.58%   |
| Unknown MMC Card  64GB                                | 114       | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB                        | 114       | 0.56%   |
| Samsung SSD 850 EVO 500GB                             | 108       | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB                        | 106       | 0.52%   |
| Unknown MMC Card  32GB                                | 105       | 0.51%   |
| Samsung SSD 850 EVO 250GB                             | 104       | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 100       | 0.49%   |
| Crucial CT500MX500SSD1 500GB                          | 97        | 0.47%   |
| Toshiba MQ01ABD100 1TB                                | 94        | 0.46%   |
| Toshiba MQ04ABF100 1TB                                | 90        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                           | 87        | 0.42%   |
| Samsung SSD 980 PRO 1TB                               | 85        | 0.41%   |
| Kingston SA400S37120G 120GB SSD                       | 85        | 0.41%   |
| SanDisk NVMe SSD Drive 1TB                            | 83        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                          | 82        | 0.4%    |
| Unknown SD/MMC/MS PRO 128GB                           | 79        | 0.39%   |
| Samsung SSD 980 1TB                                   | 76        | 0.37%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 74        | 0.36%   |
| Unknown MMC Card  128GB                               | 72        | 0.35%   |
| Toshiba DT01ACA100 1TB                                | 72        | 0.35%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 72        | 0.35%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 70        | 0.34%   |
| Seagate ST500LT012-1DG142 500GB                       | 64        | 0.31%   |
| Toshiba MQ01ABF050 500GB                              | 63        | 0.31%   |
| Intel SSDPEKNU512GZ 512GB                             | 63        | 0.31%   |
| Seagate ST1000DM003-1CH162 1TB                        | 61        | 0.3%    |
| HGST HTS721010A9E630 1TB                              | 61        | 0.3%    |
| WDC WD10EZEX-08WN4A0 1TB                              | 60        | 0.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 60        | 0.29%   |
| Seagate ST4000DM004-2CV104 4TB                        | 59        | 0.29%   |
| Samsung SSD 970 EVO Plus 1TB                          | 59        | 0.29%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 56        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2271      | 3362   | 36.35%  |
| WDC                 | 1838      | 2835   | 29.42%  |
| Toshiba             | 737       | 891    | 11.8%   |
| Hitachi             | 447       | 575    | 7.15%   |
| HGST                | 298       | 396    | 4.77%   |
| Samsung Electronics | 231       | 324    | 3.7%    |
| Fujitsu             | 106       | 274    | 1.7%    |
| Unknown             | 89        | 113    | 1.42%   |
| Apple               | 65        | 73     | 1.04%   |
| Maxtor              | 30        | 39     | 0.48%   |
| Intenso             | 21        | 23     | 0.34%   |
| ASMT                | 14        | 23     | 0.22%   |
| Hewlett-Packard     | 12        | 65     | 0.19%   |
| USB3.0              | 11        | 12     | 0.18%   |
| External            | 10        | 18     | 0.16%   |
| SSK                 | 6         | 7      | 0.1%    |
| SABRENT             | 6         | 8      | 0.1%    |
| USB                 | 5         | 5      | 0.08%   |
| StoreJet            | 5         | 5      | 0.08%   |
| WD MediaMax         | 4         | 4      | 0.06%   |
| TO Exter            | 4         | 4      | 0.06%   |
| LaCie               | 4         | 5      | 0.06%   |
| ExcelStor           | 4         | 4      | 0.06%   |
| Inateck             | 3         | 3      | 0.05%   |
| IBM-ESXS            | 3         | 8      | 0.05%   |
| HPE                 | 3         | 5      | 0.05%   |
| TDAS                | 2         | 11     | 0.03%   |
| SAGE                | 2         | 2      | 0.03%   |
| HGST HTS            | 2         | 3      | 0.03%   |
| ASMedia             | 2         | 2      | 0.03%   |
| Unknown             | 2         | 2      | 0.03%   |
| RSH-339             | 1         | 1      | 0.02%   |
| QUANTUM             | 1         | 1      | 0.02%   |
| Min Yi U            | 1         | 2      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| MARSHAL             | 1         | 1      | 0.02%   |
| Lenovo              | 1         | 2      | 0.02%   |
| JMicron Technology  | 1         | 1      | 0.02%   |
| Initio              | 1         | 1      | 0.02%   |
| DellEMC             | 1         | 8      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1227      | 1581   | 21.17%  |
| Kingston            | 763       | 922    | 13.16%  |
| Crucial             | 584       | 797    | 10.07%  |
| SanDisk             | 484       | 634    | 8.35%   |
| WDC                 | 321       | 403    | 5.54%   |
| A-DATA Technology   | 184       | 219    | 3.17%   |
| Intel               | 178       | 283    | 3.07%   |
| China               | 174       | 200    | 3%      |
| Micron Technology   | 122       | 149    | 2.1%    |
| SK hynix            | 118       | 144    | 2.04%   |
| Toshiba             | 110       | 123    | 1.9%    |
| PNY                 | 95        | 111    | 1.64%   |
| SPCC                | 91        | 135    | 1.57%   |
| Apple               | 81        | 86     | 1.4%    |
| LITEON              | 79        | 87     | 1.36%   |
| Intenso             | 60        | 84     | 1.04%   |
| Patriot             | 53        | 64     | 0.91%   |
| Netac               | 53        | 64     | 0.91%   |
| Transcend           | 52        | 56     | 0.9%    |
| OCZ                 | 46        | 52     | 0.79%   |
| Team                | 45        | 58     | 0.78%   |
| Unknown             | 44        | 45     | 0.76%   |
| GOODRAM             | 37        | 48     | 0.64%   |
| Lexar               | 36        | 40     | 0.62%   |
| KingSpec            | 36        | 38     | 0.62%   |
| Gigabyte Technology | 36        | 45     | 0.62%   |
| Hewlett-Packard     | 35        | 75     | 0.6%    |
| JMicron Technology  | 33        | 35     | 0.57%   |
| LITEONIT            | 30        | 39     | 0.52%   |
| Apacer              | 28        | 28     | 0.48%   |
| Corsair             | 26        | 29     | 0.45%   |
| Emtec               | 18        | 20     | 0.31%   |
| Seagate             | 17        | 21     | 0.29%   |
| ASMT                | 17        | 27     | 0.29%   |
| FORESEE             | 16        | 16     | 0.28%   |
| Teclast             | 15        | 16     | 0.26%   |
| Fanxiang            | 15        | 19     | 0.26%   |
| Dogfish             | 14        | 18     | 0.24%   |
| Plextor             | 11        | 11     | 0.19%   |
| Verbatim            | 10        | 11     | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 5654      | 7357   | 32.96%  |
| HDD     | 5322      | 9123   | 31.02%  |
| SSD     | 5186      | 7305   | 30.23%  |
| MMC     | 656       | 816    | 3.82%   |
| Unknown | 338       | 484    | 1.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 8606      | 15634  | 54.77%  |
| NVMe | 5626      | 7302   | 35.81%  |
| SAS  | 824       | 1333   | 5.24%   |
| MMC  | 656       | 816    | 4.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 6037      | 8901   | 55.01%  |
| 0.51-1.0   | 3306      | 4699   | 30.12%  |
| 1.01-2.0   | 879       | 1350   | 8.01%   |
| 3.01-4.0   | 302       | 497    | 2.75%   |
| 4.01-10.0  | 229       | 533    | 2.09%   |
| 2.01-3.0   | 156       | 243    | 1.42%   |
| 10.01-20.0 | 65        | 204    | 0.59%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3916      | 28.07%  |
| 251-500        | 3536      | 25.35%  |
| 501-1000       | 2317      | 16.61%  |
| 1001-2000      | 978       | 7.01%   |
| 51-100         | 826       | 5.92%   |
| 1-20           | 647       | 4.64%   |
| More than 3000 | 605       | 4.34%   |
| 21-50          | 454       | 3.25%   |
| 2001-3000      | 357       | 2.56%   |
| Unknown        | 313       | 2.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 4933      | 34.37%  |
| 21-50          | 2978      | 20.75%  |
| 51-100         | 1902      | 13.25%  |
| 101-250        | 1888      | 13.15%  |
| 251-500        | 1026      | 7.15%   |
| 501-1000       | 637       | 4.44%   |
| 1001-2000      | 326       | 2.27%   |
| Unknown        | 313       | 2.18%   |
| More than 3000 | 238       | 1.66%   |
| 2001-3000      | 109       | 0.76%   |
| 0              | 2         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 11        | 11     | 1.38%   |
| Seagate ST1000LM035-1RK172 1TB        | 10        | 10     | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 9         | 12     | 1.13%   |
| WDC WD40EFRX-68WT0N0 4TB              | 8         | 10     | 1%      |
| Toshiba MQ01ABD100 1TB                | 8         | 8      | 1%      |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 8         | 8      | 1%      |
| Seagate ST9500325AS 500GB             | 7         | 7      | 0.88%   |
| Seagate ST500LT012-9WS142 500GB       | 7         | 7      | 0.88%   |
| Toshiba MQ04ABF100 1TB                | 6         | 6      | 0.75%   |
| HGST HTS541010A9E680 1TB              | 6         | 6      | 0.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 5         | 5      | 0.63%   |
| Seagate ST500LT012-1DG142 500GB       | 5         | 5      | 0.63%   |
| Seagate ST500LM021-1KJ152 500GB       | 5         | 7      | 0.63%   |
| Seagate ST3500418AS 500GB             | 5         | 7      | 0.63%   |
| Seagate ST1000LX015-1U7172 1TB        | 5         | 5      | 0.63%   |
| Seagate ST1000LM014-1EJ164 1TB        | 5         | 6      | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB        | 5         | 5      | 0.63%   |
| SanDisk SSD PLUS 480GB                | 5         | 5      | 0.63%   |
| Samsung Electronics SSD 870 EVO 500GB | 5         | 5      | 0.63%   |
| Kingston SV300S37A120G 120GB SSD      | 5         | 6      | 0.63%   |
| HGST HTS725050A7E630 500GB            | 5         | 5      | 0.63%   |
| HGST HTS545050A7E680 500GB            | 5         | 5      | 0.63%   |
| WDC WD10JPVX-60JC3T0 1TB              | 4         | 4      | 0.5%    |
| WDC WD10EARS-00Y5B1 1TB               | 4         | 5      | 0.5%    |
| SK hynix HFS256G39TND-N210A 256GB SSD | 4         | 4      | 0.5%    |
| Seagate ST31000528AS 1TB              | 4         | 4      | 0.5%    |
| Seagate ST2000DM001-1CH164 2TB        | 4         | 4      | 0.5%    |
| Seagate ST1000LM014-SSHD-8GB          | 4         | 4      | 0.5%    |
| Seagate ST1000DM003-1CH162 1TB        | 4         | 5      | 0.5%    |
| Samsung Electronics SSD 970 EVO 500GB | 4         | 4      | 0.5%    |
| Samsung Electronics SSD 870 EVO 1TB   | 4         | 4      | 0.5%    |
| Kingston SA400S37240G 240GB SSD       | 4         | 4      | 0.5%    |
| Hitachi HTS545050A7E380 500GB         | 4         | 4      | 0.5%    |
| Hitachi HTS543232A7A384 320GB         | 4         | 4      | 0.5%    |
| HGST HTS721010A9E630 1TB              | 4         | 5      | 0.5%    |
| HGST HTS541075A9E680 752GB            | 4         | 4      | 0.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 3         | 3      | 0.38%   |
| WDC WD5002ABYS-02B1B0 500GB           | 3         | 6      | 0.38%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 3         | 3      | 0.38%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 3         | 4      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 182       | 226    | 23.18%  |
| WDC                 | 177       | 214    | 22.55%  |
| Samsung Electronics | 65        | 72     | 8.28%   |
| Toshiba             | 55        | 62     | 7.01%   |
| Hitachi             | 47        | 52     | 5.99%   |
| SK hynix            | 39        | 39     | 4.97%   |
| Intel               | 35        | 52     | 4.46%   |
| HGST                | 31        | 33     | 3.95%   |
| SanDisk             | 21        | 26     | 2.68%   |
| Kingston            | 20        | 22     | 2.55%   |
| Micron Technology   | 18        | 24     | 2.29%   |
| Crucial             | 16        | 19     | 2.04%   |
| A-DATA Technology   | 12        | 13     | 1.53%   |
| Apple               | 8         | 10     | 1.02%   |
| LITEON              | 6         | 6      | 0.76%   |
| China               | 6         | 6      | 0.76%   |
| Maxtor              | 5         | 6      | 0.64%   |
| LITEONIT            | 4         | 4      | 0.51%   |
| LDLC                | 3         | 3      | 0.38%   |
| Intenso             | 3         | 3      | 0.38%   |
| Netac               | 2         | 3      | 0.25%   |
| KingSpec            | 2         | 2      | 0.25%   |
| Fujitsu             | 2         | 2      | 0.25%   |
| Corsair             | 2         | 2      | 0.25%   |
| Unknown             | 2         | 2      | 0.25%   |
| YS                  | 1         | 1      | 0.13%   |
| XPG                 | 1         | 1      | 0.13%   |
| WD MediaMax         | 1         | 1      | 0.13%   |
| WALRAM              | 1         | 1      | 0.13%   |
| VISIPRO             | 1         | 1      | 0.13%   |
| Unknown             | 1         | 1      | 0.13%   |
| tecmiyo             | 1         | 1      | 0.13%   |
| SSSTC               | 1         | 1      | 0.13%   |
| Silicon Motion      | 1         | 1      | 0.13%   |
| ShiJi               | 1         | 1      | 0.13%   |
| RX7                 | 1         | 1      | 0.13%   |
| PNY                 | 1         | 1      | 0.13%   |
| Phison              | 1         | 1      | 0.13%   |
| Patriot             | 1         | 1      | 0.13%   |
| OCZ                 | 1         | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 182       | 226    | 35.69%  |
| WDC                 | 158       | 193    | 30.98%  |
| Toshiba             | 51        | 58     | 10%     |
| Hitachi             | 47        | 52     | 9.22%   |
| HGST                | 31        | 33     | 6.08%   |
| Samsung Electronics | 26        | 29     | 5.1%    |
| Apple               | 6         | 8      | 1.18%   |
| Maxtor              | 5         | 6      | 0.98%   |
| Fujitsu             | 2         | 2      | 0.39%   |
| WD MediaMax         | 1         | 1      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 487       | 609    | 63.99%  |
| SSD  | 211       | 249    | 27.73%  |
| NVMe | 63        | 67     | 8.28%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB                               | 3         | 3      | 16.67%  |
| WDC WD800BB-00FJA0 80GB                                         | 1         | 1      | 5.56%   |
| WDC WD7500BPVT-22HXZT1 752GB                                    | 1         | 1      | 5.56%   |
| WDC WD5000BEVT-22A0RT0 500GB                                    | 1         | 1      | 5.56%   |
| WDC WD3200AAJS-22VWA0 320GB                                     | 1         | 1      | 5.56%   |
| Seagate ST3500630AS 500GB                                       | 1         | 1      | 5.56%   |
| Seagate ST3300657SS 304GB                                       | 1         | 2      | 5.56%   |
| Samsung Electronics SSD 960 EVO 250GB                           | 1         | 1      | 5.56%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 5.56%   |
| Intel SSDSC2BB480G7 480GB                                       | 1         | 4      | 5.56%   |
| Intel SSDPEKKW256G7 256GB                                       | 1         | 1      | 5.56%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 5.56%   |
| Hewlett-Packard EF0450FARMV 450GB                               | 1         | 4      | 5.56%   |
| Crucial M4-CT256M4SSD3 256GB                                    | 1         | 1      | 5.56%   |
| Apple SSD TS256C 256GB                                          | 1         | 1      | 5.56%   |
| A-DATA Technology SX8200PNP 256GB                               | 1         | 1      | 5.56%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 27.78%  |
| WDC                 | 4         | 4      | 22.22%  |
| Seagate             | 2         | 3      | 11.11%  |
| Intel               | 2         | 5      | 11.11%  |
| HGST                | 1         | 1      | 5.56%   |
| Hewlett-Packard     | 1         | 4      | 5.56%   |
| Crucial             | 1         | 1      | 5.56%   |
| Apple               | 1         | 1      | 5.56%   |
| A-DATA Technology   | 1         | 1      | 5.56%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 8346      | 15852  | 58.21%  |
| Works    | 5241      | 8282   | 36.56%  |
| Malfunc  | 731       | 925    | 5.1%    |
| Failed   | 18        | 25     | 0.13%   |
| Fixed    | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 8812      | 49.71%  |
| AMD                                     | 2261      | 12.75%  |
| Samsung Electronics                     | 1801      | 10.16%  |
| SanDisk                                 | 887       | 5%      |
| SK hynix                                | 524       | 2.96%   |
| Kingston Technology Company             | 369       | 2.08%   |
| Micron Technology                       | 355       | 2%      |
| Phison Electronics                      | 296       | 1.67%   |
| ASMedia Technology                      | 264       | 1.49%   |
| KIOXIA                                  | 250       | 1.41%   |
| Toshiba America Info Systems            | 225       | 1.27%   |
| Micron/Crucial Technology               | 208       | 1.17%   |
| Silicon Motion                          | 171       | 0.96%   |
| Marvell Technology Group                | 168       | 0.95%   |
| Nvidia                                  | 166       | 0.94%   |
| ADATA Technology                        | 130       | 0.73%   |
| JMicron Technology                      | 123       | 0.69%   |
| LSI Logic / Symbios Logic               | 119       | 0.67%   |
| Apple                                   | 73        | 0.41%   |
| Broadcom / LSI                          | 64        | 0.36%   |
| Solid State Storage Technology          | 60        | 0.34%   |
| Union Memory (Shenzhen)                 | 50        | 0.28%   |
| MAXIO Technology (Hangzhou)             | 48        | 0.27%   |
| Realtek Semiconductor                   | 43        | 0.24%   |
| Shenzhen Longsys Electronics            | 36        | 0.2%    |
| Adaptec                                 | 28        | 0.16%   |
| Hewlett-Packard                         | 25        | 0.14%   |
| Seagate Technology                      | 23        | 0.13%   |
| VIA Technologies                        | 22        | 0.12%   |
| Silicon Image                           | 20        | 0.11%   |
| Yangtze Memory Technologies             | 17        | 0.1%    |
| Lite-On Technology                      | 13        | 0.07%   |
| Solidigm                                | 9         | 0.05%   |
| Lenovo                                  | 9         | 0.05%   |
| INNOGRIT                                | 9         | 0.05%   |
| Transcend                               | 6         | 0.03%   |
| Biwin Storage Technology                | 6         | 0.03%   |
| Netac Technology                        | 5         | 0.03%   |
| Shenzhen Unionmemory Information System | 4         | 0.02%   |
| Unknown                                 | 4         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1548      | 7.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 658       | 3.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 657       | 3.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 647       | 3.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 607       | 3.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 472       | 2.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 460       | 2.31%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 457       | 2.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 417       | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 325       | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 319       | 1.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 284       | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 283       | 1.42%   |
| Intel SATA Controller [RAID mode]                                              | 261       | 1.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 258       | 1.3%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 249       | 1.25%   |
| AMD 400 Series Chipset SATA Controller                                         | 237       | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 235       | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                          | 229       | 1.15%   |
| Intel Tiger Lake-LP SATA Controller                                            | 227       | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 224       | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 221       | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 217       | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 216       | 1.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 209       | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 191       | 0.96%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 185       | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 177       | 0.89%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 176       | 0.89%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 173       | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 172       | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 163       | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 155       | 0.78%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 141       | 0.71%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 138       | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 132       | 0.66%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 131       | 0.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 128       | 0.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 128       | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 128       | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 9238      | 51.77%  |
| NVMe | 5625      | 31.52%  |
| RAID | 1656      | 9.28%   |
| IDE  | 1160      | 6.5%    |
| SAS  | 119       | 0.67%   |
| SCSI | 45        | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 10405     | 76.8%   |
| AMD          | 3015      | 22.25%  |
| ARM          | 126       | 0.93%   |
| CentaurHauls | 2         | 0.01%   |
| Phytium      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 246       | 1.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 235       | 1.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 134       | 0.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 121       | 0.89%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 121       | 0.89%   |
| ARM Processor                                 | 118       | 0.87%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 111       | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 109       | 0.8%    |
| Intel 12th Gen Core i7-12700H                 | 103       | 0.76%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 97        | 0.71%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 96        | 0.71%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 96        | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 91        | 0.67%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 89        | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 88        | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 87        | 0.64%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 86        | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 85        | 0.63%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 81        | 0.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 74        | 0.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 74        | 0.55%   |
| AMD Ryzen 5 3600 6-Core Processor             | 72        | 0.53%   |
| Intel 12th Gen Core i7-1260P                  | 70        | 0.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 68        | 0.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 68        | 0.5%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 68        | 0.5%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 67        | 0.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 63        | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 62        | 0.46%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 62        | 0.46%   |
| Intel 12th Gen Core i7-1255U                  | 61        | 0.45%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 58        | 0.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 58        | 0.43%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 58        | 0.43%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 57        | 0.42%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 56        | 0.41%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 56        | 0.41%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 55        | 0.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 55        | 0.41%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 54        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2889      | 21.31%  |
| Intel Core i7           | 2403      | 17.73%  |
| Other                   | 1971      | 14.54%  |
| Intel Core i3           | 950       | 7.01%   |
| AMD Ryzen 5             | 816       | 6.02%   |
| AMD Ryzen 7             | 669       | 4.93%   |
| Intel Celeron           | 666       | 4.91%   |
| Intel Xeon              | 547       | 4.03%   |
| Intel Core 2 Duo        | 324       | 2.39%   |
| Intel Pentium           | 255       | 1.88%   |
| AMD Ryzen 9             | 253       | 1.87%   |
| AMD FX                  | 155       | 1.14%   |
| AMD Ryzen 3             | 140       | 1.03%   |
| Intel Atom              | 126       | 0.93%   |
| AMD A6                  | 99        | 0.73%   |
| Intel Core 2 Quad       | 98        | 0.72%   |
| AMD A10                 | 95        | 0.7%    |
| AMD A8                  | 85        | 0.63%   |
| Intel Pentium Dual-Core | 79        | 0.58%   |
| Intel Core i9           | 75        | 0.55%   |
| AMD A4                  | 65        | 0.48%   |
| AMD Ryzen 7 PRO         | 57        | 0.42%   |
| AMD Phenom II X4        | 43        | 0.32%   |
| AMD Ryzen 5 PRO         | 38        | 0.28%   |
| Intel Pentium Silver    | 37        | 0.27%   |
| AMD Ryzen Threadripper  | 37        | 0.27%   |
| AMD Athlon II X2        | 37        | 0.27%   |
| AMD Athlon              | 37        | 0.27%   |
| Intel Core 2            | 33        | 0.24%   |
| AMD E2                  | 32        | 0.24%   |
| Intel Pentium Dual      | 31        | 0.23%   |
| AMD E1                  | 25        | 0.18%   |
| AMD Athlon 64 X2        | 25        | 0.18%   |
| AMD E                   | 24        | 0.18%   |
| AMD Athlon II X4        | 20        | 0.15%   |
| AMD Phenom II X6        | 19        | 0.14%   |
| Intel Pentium Gold      | 16        | 0.12%   |
| Intel Genuine           | 15        | 0.11%   |
| Intel Core m3           | 14        | 0.1%    |
| Intel Xeon Gold         | 13        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 5047      | 37.21%  |
| 2       | 4436      | 32.71%  |
| 6       | 1382      | 10.19%  |
| 8       | 1243      | 9.17%   |
| 12      | 434       | 3.2%    |
| 10      | 225       | 1.66%   |
| 14      | 219       | 1.61%   |
| 16      | 195       | 1.44%   |
| 1       | 112       | 0.83%   |
| 3       | 65        | 0.48%   |
| 24      | 61        | 0.45%   |
| Unknown | 36        | 0.27%   |
| 28      | 31        | 0.23%   |
| 32      | 16        | 0.12%   |
| 20      | 16        | 0.12%   |
| 40      | 7         | 0.05%   |
| 64      | 6         | 0.04%   |
| 18      | 6         | 0.04%   |
| 48      | 5         | 0.04%   |
| 44      | 5         | 0.04%   |
| 36      | 4         | 0.03%   |
| 5       | 4         | 0.03%   |
| 128     | 2         | 0.01%   |
| 104     | 2         | 0.01%   |
| 80      | 1         | 0.01%   |
| 52      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 13193     | 97.37%  |
| 2       | 313       | 2.31%   |
| Unknown | 36        | 0.27%   |
| 4       | 5         | 0.04%   |
| 3       | 2         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 9608      | 70.86%  |
| 1       | 3914      | 28.86%  |
| Unknown | 36        | 0.27%   |
| 6       | 1         | 0.01%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 13476     | 99.45%  |
| Unknown        | 68        | 0.5%    |
| 64-bit         | 6         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8344      | 60.2%   |
| 0x806c1    | 394       | 2.84%   |
| 0x306a9    | 260       | 1.88%   |
| 0x806ec    | 243       | 1.75%   |
| 0x306c3    | 242       | 1.75%   |
| 0x206a7    | 210       | 1.52%   |
| 0x806ea    | 188       | 1.36%   |
| 0x0a50000c | 179       | 1.29%   |
| 0x906a3    | 171       | 1.23%   |
| 0x906ea    | 169       | 1.22%   |
| 0x506e3    | 137       | 0.99%   |
| 0x08608103 | 131       | 0.95%   |
| 0x906e9    | 109       | 0.79%   |
| 0x806e9    | 103       | 0.74%   |
| 0x406e3    | 103       | 0.74%   |
| 0x40651    | 101       | 0.73%   |
| 0x08108109 | 101       | 0.73%   |
| 0x706e5    | 96        | 0.69%   |
| 0x306d4    | 91        | 0.66%   |
| 0x706a8    | 87        | 0.63%   |
| 0x08600106 | 87        | 0.63%   |
| 0x806d1    | 86        | 0.62%   |
| 0xa0652    | 85        | 0.61%   |
| 0x0a50000d | 83        | 0.6%    |
| 0x08701021 | 72        | 0.52%   |
| 0x1067a    | 70        | 0.51%   |
| 0x906a4    | 68        | 0.49%   |
| 0x906ed    | 56        | 0.4%    |
| 0x306f2    | 54        | 0.39%   |
| 0x20655    | 53        | 0.38%   |
| 0x406f1    | 51        | 0.37%   |
| 0x90672    | 48        | 0.35%   |
| 0x306e4    | 48        | 0.35%   |
| 0x0a20120a | 46        | 0.33%   |
| 0x06000852 | 42        | 0.3%    |
| 0x806eb    | 41        | 0.3%    |
| 0x0a601203 | 41        | 0.3%    |
| 0x0800820d | 41        | 0.3%    |
| 0x0a201016 | 39        | 0.28%   |
| 0x506c9    | 38        | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2094      | 15.43%  |
| Haswell          | 1208      | 8.9%    |
| Unknown          | 999       | 7.36%   |
| IvyBridge        | 898       | 6.62%   |
| SandyBridge      | 831       | 6.12%   |
| Skylake          | 755       | 5.56%   |
| TigerLake        | 753       | 5.55%   |
| Zen 3            | 654       | 4.82%   |
| Alderlake Hybrid | 500       | 3.68%   |
| Zen 2            | 464       | 3.42%   |
| Penryn           | 435       | 3.2%    |
| Westmere         | 403       | 2.97%   |
| Zen+             | 360       | 2.65%   |
| IceLake          | 358       | 2.64%   |
| Broadwell        | 342       | 2.52%   |
| CometLake        | 323       | 2.38%   |
| Silvermont       | 287       | 2.11%   |
| Goldmont plus    | 280       | 2.06%   |
| Piledriver       | 228       | 1.68%   |
| Core             | 202       | 1.49%   |
| K10              | 197       | 1.45%   |
| Zen              | 167       | 1.23%   |
| Excavator        | 160       | 1.18%   |
| Nehalem          | 131       | 0.97%   |
| Goldmont         | 118       | 0.87%   |
| Puma             | 73        | 0.54%   |
| Steamroller      | 60        | 0.44%   |
| K8 Hammer        | 54        | 0.4%    |
| Bobcat           | 53        | 0.39%   |
| Jaguar           | 44        | 0.32%   |
| Tremont          | 31        | 0.23%   |
| K10 Llano        | 31        | 0.23%   |
| Bulldozer        | 31        | 0.23%   |
| K8 & K10 hybrid  | 16        | 0.12%   |
| Bonnell          | 15        | 0.11%   |
| NetBurst         | 14        | 0.1%    |
| Gracemont        | 5         | 0.04%   |
| Sapphire Rapids  | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 8149      | 50.65%  |
| Nvidia                                       | 4305      | 26.76%  |
| AMD                                          | 3338      | 20.75%  |
| Matrox Electronics Systems                   | 159       | 0.99%   |
| ASPEED Technology                            | 124       | 0.77%   |
| ATI Technologies                             | 7         | 0.04%   |
| Zhaoxin                                      | 2         | 0.01%   |
| Huawei Technologies                          | 2         | 0.01%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| VIA Technologies                             | 1         | 0.01%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 672       | 4.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 591       | 3.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 446       | 2.73%   |
| Intel UHD Graphics 620                                                                   | 371       | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 323       | 1.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 309       | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 300       | 1.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 291       | 1.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 291       | 1.78%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 288       | 1.76%   |
| Intel HD Graphics 620                                                                    | 262       | 1.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 260       | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 249       | 1.52%   |
| Intel HD Graphics 530                                                                    | 242       | 1.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 241       | 1.47%   |
| AMD Lucienne                                                                             | 232       | 1.42%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 220       | 1.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 215       | 1.31%   |
| Intel HD Graphics 5500                                                                   | 198       | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 190       | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 182       | 1.11%   |
| Intel HD Graphics 630                                                                    | 161       | 0.98%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 159       | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 155       | 0.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 151       | 0.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 149       | 0.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 148       | 0.9%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 148       | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 141       | 0.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 140       | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 132       | 0.81%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 124       | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 123       | 0.75%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 111       | 0.68%   |
| Intel HD Graphics 500                                                                    | 104       | 0.64%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 103       | 0.63%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 98        | 0.6%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 98        | 0.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 95        | 0.58%   |
| AMD Barcelo                                                                              | 92        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 5863      | 43.11%  |
| 1 x AMD                  | 2581      | 18.98%  |
| 1 x Nvidia               | 2149      | 15.8%   |
| Intel + Nvidia           | 1782      | 13.1%   |
| Intel + AMD              | 309       | 2.27%   |
| AMD + Nvidia             | 300       | 2.21%   |
| Other                    | 144       | 1.06%   |
| 2 x AMD                  | 139       | 1.02%   |
| 1 x Matrox               | 139       | 1.02%   |
| 1 x ASPEED               | 98        | 0.72%   |
| 2 x Nvidia               | 32        | 0.24%   |
| Nvidia + ASPEED          | 18        | 0.13%   |
| Nvidia + Matrox          | 12        | 0.09%   |
| AMD + Matrox             | 7         | 0.05%   |
| AMD + ASPEED             | 4         | 0.03%   |
| 2 x Nvidia + 1 x ASPEED  | 2         | 0.01%   |
| 2 x Intel                | 2         | 0.01%   |
| 1 x Zhaoxin              | 2         | 0.01%   |
| 1 x Intel + 3 x Nvidia   | 2         | 0.01%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.01%   |
| 1 x Huawei Technologies  | 2         | 0.01%   |
| 3 x Nvidia + 1 x ASPEED  | 1         | 0.01%   |
| 3 x AMD                  | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.01%   |
| 1 x XGI                  | 1         | 0.01%   |
| 1 x VIA                  | 1         | 0.01%   |
| 1 x SiS                  | 1         | 0.01%   |
| Intel + 2 x Nvidia       | 1         | 0.01%   |
| Intel + 2 x AMD          | 1         | 0.01%   |
| Intel + ASPEED           | 1         | 0.01%   |
| Intel + AMD + 3 x Nvidia | 1         | 0.01%   |
| AMD + 2 x Nvidia         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 10522     | 76.92%  |
| Proprietary | 2491      | 18.21%  |
| Unknown     | 667       | 4.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 10880     | 79.47%  |
| 0.01-0.5   | 709       | 5.18%   |
| 1.01-2.0   | 698       | 5.1%    |
| 0.51-1.0   | 428       | 3.13%   |
| 3.01-4.0   | 393       | 2.87%   |
| 7.01-8.0   | 244       | 1.78%   |
| 5.01-6.0   | 129       | 0.94%   |
| 8.01-16.0  | 119       | 0.87%   |
| 2.01-3.0   | 47        | 0.34%   |
| 16.01-24.0 | 35        | 0.26%   |
| 4.01-5.0   | 7         | 0.05%   |
| 32.01-64.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1793      | 12.18%  |
| AU Optronics            | 1709      | 11.61%  |
| BOE                     | 1529      | 10.39%  |
| Chimei Innolux          | 1295      | 8.8%    |
| LG Display              | 1161      | 7.89%   |
| Dell                    | 939       | 6.38%   |
| Goldstar                | 708       | 4.81%   |
| Hewlett-Packard         | 509       | 3.46%   |
| Acer                    | 432       | 2.93%   |
| Apple                   | 347       | 2.36%   |
| AOC                     | 317       | 2.15%   |
| Philips                 | 308       | 2.09%   |
| Sharp                   | 301       | 2.04%   |
| BenQ                    | 281       | 1.91%   |
| Lenovo                  | 265       | 1.8%    |
| Ancor Communications    | 260       | 1.77%   |
| Iiyama                  | 176       | 1.2%    |
| PANDA                   | 167       | 1.13%   |
| Chi Mei Optoelectronics | 144       | 0.98%   |
| ViewSonic               | 138       | 0.94%   |
| ASUSTek Computer        | 135       | 0.92%   |
| Sony                    | 118       | 0.8%    |
| InfoVision              | 114       | 0.77%   |
| CSO                     | 85        | 0.58%   |
| Panasonic               | 65        | 0.44%   |
| Vizio                   | 57        | 0.39%   |
| MSI                     | 55        | 0.37%   |
| Fujitsu Siemens         | 51        | 0.35%   |
| Eizo                    | 48        | 0.33%   |
| Sceptre Tech            | 47        | 0.32%   |
| NEC Computers           | 41        | 0.28%   |
| LG Electronics          | 40        | 0.27%   |
| Unknown                 | 37        | 0.25%   |
| Toshiba                 | 36        | 0.24%   |
| HannStar                | 34        | 0.23%   |
| LG Philips              | 31        | 0.21%   |
| RTK                     | 30        | 0.2%    |
| Mi                      | 29        | 0.2%    |
| TMX                     | 27        | 0.18%   |
| Medion                  | 25        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 72        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 69        | 0.46%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 56        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 55        | 0.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 55        | 0.36%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 46        | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 46        | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 44        | 0.29%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 42        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 39        | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 39        | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 35        | 0.23%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 34        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 34        | 0.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 34        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 33        | 0.22%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 31        | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 31        | 0.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 30        | 0.2%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 30        | 0.2%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 30        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch         | 29        | 0.19%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 28        | 0.18%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 28        | 0.18%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 28        | 0.18%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 28        | 0.18%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 27        | 0.18%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                        | 27        | 0.18%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                       | 27        | 0.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 26        | 0.17%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 25        | 0.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 25        | 0.17%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 25        | 0.17%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 24        | 0.16%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 0.16%   |
| Unknown                                                                  | 24        | 0.16%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 23        | 0.15%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 23        | 0.15%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 23        | 0.15%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                    | 22        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 6617      | 47.31%  |
| 1366x768 (WXGA)    | 2179      | 15.58%  |
| 3840x2160 (4K)     | 1025      | 7.33%   |
| 2560x1440 (QHD)    | 676       | 4.83%   |
| 1600x900 (HD+)     | 559       | 4%      |
| 1920x1200 (WUXGA)  | 443       | 3.17%   |
| 1680x1050 (WSXGA+) | 319       | 2.28%   |
| 1280x1024 (SXGA)   | 305       | 2.18%   |
| 1440x900 (WXGA+)   | 247       | 1.77%   |
| 2560x1600          | 198       | 1.42%   |
| 1280x800 (WXGA)    | 184       | 1.32%   |
| 3440x1440          | 146       | 1.04%   |
| 2560x1080          | 136       | 0.97%   |
| 2880x1800          | 122       | 0.87%   |
| 1360x768           | 86        | 0.61%   |
| 3840x2400          | 74        | 0.53%   |
| Unknown            | 70        | 0.5%    |
| 1920x540           | 63        | 0.45%   |
| 2160x1440          | 62        | 0.44%   |
| 3840x1080          | 48        | 0.34%   |
| 1024x768 (XGA)     | 41        | 0.29%   |
| 1280x720 (HD)      | 29        | 0.21%   |
| 1600x1200          | 23        | 0.16%   |
| 2736x1824          | 22        | 0.16%   |
| 2256x1504          | 22        | 0.16%   |
| 3840x1600          | 20        | 0.14%   |
| 3200x1800 (QHD+)   | 20        | 0.14%   |
| 1920x1280          | 18        | 0.13%   |
| 3000x2000          | 14        | 0.1%    |
| 2288x1287          | 14        | 0.1%    |
| 3200x2000          | 13        | 0.09%   |
| 3072x1920          | 13        | 0.09%   |
| 2880x1620          | 13        | 0.09%   |
| 2520x1680          | 13        | 0.09%   |
| 3456x2160          | 10        | 0.07%   |
| 2048x1152          | 8         | 0.06%   |
| 1400x1050          | 8         | 0.06%   |
| 2160x1350          | 7         | 0.05%   |
| 1680x945           | 7         | 0.05%   |
| 1280x960           | 7         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3687      | 25.04%  |
| 13      | 1459      | 9.91%   |
| 14      | 1227      | 8.33%   |
| 27      | 1147      | 7.79%   |
| 24      | 1101      | 7.48%   |
| 23      | 925       | 6.28%   |
| 21      | 806       | 5.47%   |
| 17      | 776       | 5.27%   |
| Unknown | 404       | 2.74%   |
| 31      | 358       | 2.43%   |
| 19      | 348       | 2.36%   |
| 16      | 246       | 1.67%   |
| 34      | 235       | 1.6%    |
| 18      | 226       | 1.54%   |
| 20      | 207       | 1.41%   |
| 22      | 205       | 1.39%   |
| 12      | 192       | 1.3%    |
| 11      | 159       | 1.08%   |
| 84      | 121       | 0.82%   |
| 32      | 95        | 0.65%   |
| 40      | 88        | 0.6%    |
| 72      | 85        | 0.58%   |
| 54      | 81        | 0.55%   |
| 25      | 53        | 0.36%   |
| 28      | 46        | 0.31%   |
| 26      | 45        | 0.31%   |
| 10      | 36        | 0.24%   |
| 37      | 28        | 0.19%   |
| 46      | 27        | 0.18%   |
| 52      | 25        | 0.17%   |
| 43      | 24        | 0.16%   |
| 65      | 23        | 0.16%   |
| 42      | 23        | 0.16%   |
| 48      | 22        | 0.15%   |
| 29      | 22        | 0.15%   |
| 49      | 21        | 0.14%   |
| 36      | 15        | 0.1%    |
| 35      | 10        | 0.07%   |
| 86      | 9         | 0.06%   |
| 74      | 9         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 5838      | 40.25%  |
| 501-600        | 2957      | 20.39%  |
| 401-500        | 1607      | 11.08%  |
| 201-300        | 1166      | 8.04%   |
| 351-400        | 928       | 6.4%    |
| 601-700        | 561       | 3.87%   |
| Unknown        | 404       | 2.79%   |
| 701-800        | 353       | 2.43%   |
| 1001-1500      | 249       | 1.72%   |
| 1501-2000      | 231       | 1.59%   |
| 801-900        | 141       | 0.97%   |
| 901-1000       | 52        | 0.36%   |
| More than 2000 | 8         | 0.06%   |
| 101-200        | 7         | 0.05%   |
| 1-100          | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 10202     | 77.46%  |
| 16/10   | 1692      | 12.85%  |
| 5/4     | 296       | 2.25%   |
| 21/9    | 294       | 2.23%   |
| Unknown | 294       | 2.23%   |
| 3/2     | 200       | 1.52%   |
| 4/3     | 86        | 0.65%   |
| 32/9    | 49        | 0.37%   |
| 6/5     | 17        | 0.13%   |
| 0.56    | 10        | 0.08%   |
| 1.00    | 9         | 0.07%   |
| 3.40    | 3         | 0.02%   |
| 2.12    | 3         | 0.02%   |
| 2.00    | 3         | 0.02%   |
| 0.62    | 3         | 0.02%   |
| 3.20    | 2         | 0.02%   |
| 1.96    | 2         | 0.02%   |
| 3.73    | 1         | 0.01%   |
| 3.33    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.75    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 3674      | 25.17%  |
| 201-250        | 2375      | 16.27%  |
| 81-90          | 2069      | 14.18%  |
| 301-350        | 1186      | 8.13%   |
| 151-200        | 801       | 5.49%   |
| 351-500        | 740       | 5.07%   |
| 71-80          | 616       | 4.22%   |
| 121-130        | 573       | 3.93%   |
| More than 1000 | 421       | 2.88%   |
| 251-300        | 419       | 2.87%   |
| Unknown        | 404       | 2.77%   |
| 141-150        | 332       | 2.27%   |
| 501-1000       | 266       | 1.82%   |
| 111-120        | 229       | 1.57%   |
| 51-60          | 166       | 1.14%   |
| 61-70          | 163       | 1.12%   |
| 131-140        | 72        | 0.49%   |
| 91-100         | 49        | 0.34%   |
| 41-50          | 33        | 0.23%   |
| 1-40           | 7         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 4434      | 31.21%  |
| 121-160       | 4162      | 29.29%  |
| 101-120       | 3257      | 22.92%  |
| 161-240       | 1184      | 8.33%   |
| More than 240 | 410       | 2.89%   |
| Unknown       | 404       | 2.84%   |
| 1-50          | 357       | 2.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 10343     | 75.09%  |
| 2     | 2245      | 16.3%   |
| 0     | 875       | 6.35%   |
| 3     | 278       | 2.02%   |
| 4     | 28        | 0.2%    |
| 5     | 3         | 0.02%   |
| 6     | 2         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 7097      | 35.57%  |
| Realtek Semiconductor             | 7051      | 35.34%  |
| Qualcomm Atheros                  | 1777      | 8.91%   |
| Broadcom                          | 1071      | 5.37%   |
| MediaTek                          | 483       | 2.42%   |
| TP-Link                           | 223       | 1.12%   |
| Broadcom Limited                  | 222       | 1.11%   |
| Ralink Technology                 | 163       | 0.82%   |
| Marvell Technology Group          | 159       | 0.8%    |
| ASIX Electronics                  | 158       | 0.79%   |
| Ralink                            | 154       | 0.77%   |
| Nvidia                            | 132       | 0.66%   |
| Samsung Electronics               | 86        | 0.43%   |
| DisplayLink                       | 85        | 0.43%   |
| NetGear                           | 66        | 0.33%   |
| Xiaomi                            | 60        | 0.3%    |
| Sierra Wireless                   | 53        | 0.27%   |
| Aquantia                          | 53        | 0.27%   |
| Dell                              | 52        | 0.26%   |
| Qualcomm                          | 50        | 0.25%   |
| Qualcomm Atheros Communications   | 45        | 0.23%   |
| Microsoft                         | 41        | 0.21%   |
| Lenovo                            | 38        | 0.19%   |
| D-Link System                     | 34        | 0.17%   |
| D-Link                            | 32        | 0.16%   |
| Hewlett-Packard                   | 28        | 0.14%   |
| Ericsson Business Mobile Networks | 28        | 0.14%   |
| Huawei Technologies               | 27        | 0.14%   |
| JMicron Technology                | 24        | 0.12%   |
| Google                            | 24        | 0.12%   |
| Edimax Technology                 | 24        | 0.12%   |
| ASUSTek Computer                  | 24        | 0.12%   |
| Apple                             | 24        | 0.12%   |
| OPPO Electronics                  | 23        | 0.12%   |
| ICS Advent                        | 20        | 0.1%    |
| Linksys                           | 19        | 0.1%    |
| IMC Networks                      | 14        | 0.07%   |
| Mellanox Technologies             | 13        | 0.07%   |
| Motorola PCS                      | 12        | 0.06%   |
| Fibocom                           | 11        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4552      | 19.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 630       | 2.68%   |
| Intel Wi-Fi 6 AX201                                               | 579       | 2.46%   |
| Intel Wi-Fi 6 AX200                                               | 526       | 2.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 503       | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 439       | 1.87%   |
| Intel Wireless 8265 / 8275                                        | 427       | 1.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 400       | 1.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 400       | 1.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 320       | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 300       | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 280       | 1.19%   |
| Intel Wireless 7265                                               | 278       | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 269       | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 240       | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 236       | 1%      |
| Intel Ethernet Connection I217-LM                                 | 232       | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 230       | 0.98%   |
| Intel I211 Gigabit Network Connection                             | 229       | 0.97%   |
| Intel Wireless 7260                                               | 227       | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 225       | 0.96%   |
| Intel Wireless 8260                                               | 222       | 0.94%   |
| Intel Ethernet Controller I225-V                                  | 208       | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 203       | 0.86%   |
| Intel Wireless 3165                                               | 172       | 0.73%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 171       | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 171       | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 166       | 0.71%   |
| Intel Ethernet Connection (2) I219-V                              | 165       | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 164       | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 155       | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 148       | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 138       | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 135       | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 132       | 0.56%   |
| Realtek 802.11ac NIC                                              | 125       | 0.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 125       | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 123       | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 118       | 0.5%    |
| Intel Ethernet Connection I219-LM                                 | 115       | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 5293      | 47.94%  |
| Realtek Semiconductor                 | 1937      | 17.54%  |
| Qualcomm Atheros                      | 1445      | 13.09%  |
| Broadcom                              | 682       | 6.18%   |
| MediaTek                              | 464       | 4.2%    |
| TP-Link                               | 204       | 1.85%   |
| Ralink Technology                     | 163       | 1.48%   |
| Ralink                                | 154       | 1.39%   |
| Broadcom Limited                      | 152       | 1.38%   |
| NetGear                               | 65        | 0.59%   |
| Sierra Wireless                       | 53        | 0.48%   |
| Qualcomm Atheros Communications       | 45        | 0.41%   |
| Dell                                  | 40        | 0.36%   |
| Marvell Technology Group              | 37        | 0.34%   |
| Microsoft                             | 35        | 0.32%   |
| Qualcomm                              | 32        | 0.29%   |
| D-Link                                | 31        | 0.28%   |
| D-Link System                         | 26        | 0.24%   |
| Edimax Technology                     | 24        | 0.22%   |
| ASUSTek Computer                      | 23        | 0.21%   |
| Linksys                               | 17        | 0.15%   |
| IMC Networks                          | 14        | 0.13%   |
| Fibocom                               | 11        | 0.1%    |
| Ericsson Business Mobile Networks     | 10        | 0.09%   |
| Hewlett-Packard                       | 9         | 0.08%   |
| Belkin Components                     | 9         | 0.08%   |
| AVM                                   | 9         | 0.08%   |
| Mercucys                              | 8         | 0.07%   |
| Sitecom Europe                        | 7         | 0.06%   |
| BUFFALO                               | 6         | 0.05%   |
| ZyDAS                                 | 5         | 0.05%   |
| Wilocity                              | 4         | 0.04%   |
| TRENDnet                              | 3         | 0.03%   |
| Micro Star International              | 3         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.03%   |
| Qualcomm Technologies                 | 2         | 0.02%   |
| Guillemot                             | 2         | 0.02%   |
| Gemtek                                | 2         | 0.02%   |
| Encore Electronics                    | 2         | 0.02%   |
| ZyXEL Communications                  | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 579       | 5.2%    |
| Intel Wi-Fi 6 AX200                                            | 526       | 4.72%   |
| Intel Wireless 8265 / 8275                                     | 427       | 3.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 400       | 3.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 320       | 2.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 300       | 2.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 280       | 2.51%   |
| Intel Wireless 7265                                            | 278       | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 269       | 2.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 240       | 2.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 236       | 2.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 230       | 2.07%   |
| Intel Wireless 7260                                            | 227       | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 225       | 2.02%   |
| Intel Wireless 8260                                            | 222       | 1.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 203       | 1.82%   |
| Intel Wireless 3165                                            | 172       | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 171       | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 171       | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 166       | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 164       | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 148       | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 135       | 1.21%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 132       | 1.19%   |
| Realtek 802.11ac NIC                                           | 125       | 1.12%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 125       | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 111       | 1%      |
| Intel Wireless-AC 9260                                         | 110       | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 108       | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 108       | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 107       | 0.96%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 105       | 0.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 99        | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 94        | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                  | 94        | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 83        | 0.75%   |
| Intel Wireless 3160                                            | 73        | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 72        | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 71        | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 70        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 6178      | 52.06%  |
| Intel                                  | 3561      | 30.01%  |
| Broadcom                               | 559       | 4.71%   |
| Qualcomm Atheros                       | 486       | 4.1%    |
| ASIX Electronics                       | 158       | 1.33%   |
| Nvidia                                 | 132       | 1.11%   |
| Marvell Technology Group               | 122       | 1.03%   |
| DisplayLink                            | 85        | 0.72%   |
| Broadcom Limited                       | 73        | 0.62%   |
| Samsung Electronics                    | 63        | 0.53%   |
| Xiaomi                                 | 60        | 0.51%   |
| Aquantia                               | 53        | 0.45%   |
| Lenovo                                 | 38        | 0.32%   |
| JMicron Technology                     | 24        | 0.2%    |
| OPPO Electronics                       | 23        | 0.19%   |
| Google                                 | 23        | 0.19%   |
| Apple                                  | 23        | 0.19%   |
| ICS Advent                             | 20        | 0.17%   |
| TP-Link                                | 19        | 0.16%   |
| MediaTek                               | 18        | 0.15%   |
| Huawei Technologies                    | 17        | 0.14%   |
| Qualcomm                               | 16        | 0.13%   |
| Motorola PCS                           | 8         | 0.07%   |
| D-Link System                          | 8         | 0.07%   |
| Hewlett-Packard                        | 7         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 6         | 0.05%   |
| Mellanox Technologies                  | 6         | 0.05%   |
| IBM                                    | 6         | 0.05%   |
| VIA Technologies                       | 5         | 0.04%   |
| Microsoft                              | 5         | 0.04%   |
| Microchip Technology                   | 5         | 0.04%   |
| Insyde Software                        | 5         | 0.04%   |
| Dell                                   | 5         | 0.04%   |
| Chelsio Communications                 | 4         | 0.03%   |
| American Megatrends                    | 4         | 0.03%   |
| Spreadtrum Communications              | 3         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.03%   |
| Tehuti Networks                        | 2         | 0.02%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4552      | 37.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 630       | 5.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 503       | 4.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 439       | 3.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 400       | 3.28%   |
| Intel Ethernet Connection I217-LM                                 | 232       | 1.9%    |
| Intel I211 Gigabit Network Connection                             | 229       | 1.88%   |
| Intel Ethernet Controller I225-V                                  | 208       | 1.71%   |
| Intel Ethernet Connection (2) I219-V                              | 165       | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 155       | 1.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 138       | 1.13%   |
| Intel 82579V Gigabit Network Connection                           | 123       | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                             | 118       | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 115       | 0.94%   |
| Intel I350 Gigabit Network Connection                             | 102       | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 100       | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 86        | 0.71%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 85        | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 84        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 81        | 0.66%   |
| Intel I210 Gigabit Network Connection                             | 76        | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 73        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                          | 72        | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 71        | 0.58%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 67        | 0.55%   |
| Intel 82574L Gigabit Network Connection                           | 64        | 0.52%   |
| Intel Ethernet Connection (4) I219-V                              | 63        | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 62        | 0.51%   |
| Intel Ethernet Connection (6) I219-V                              | 61        | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 61        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 59        | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 58        | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 56        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 55        | 0.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 55        | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                            | 51        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 49        | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                             | 49        | 0.4%    |
| Intel Ethernet Connection (16) I219-V                             | 49        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 48        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 11104     | 50.9%   |
| WiFi     | 10511     | 48.18%  |
| Modem    | 160       | 0.73%   |
| Unknown  | 40        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 8205      | 58.25%  |
| Ethernet | 5878      | 41.73%  |
| Modem    | 2         | 0.01%   |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 7053      | 51.94%  |
| 1     | 5767      | 42.47%  |
| 3     | 313       | 2.31%   |
| 0     | 290       | 2.14%   |
| 4     | 111       | 0.82%   |
| 5     | 20        | 0.15%   |
| 6     | 8         | 0.06%   |
| 8     | 7         | 0.05%   |
| 7     | 4         | 0.03%   |
| 10    | 3         | 0.02%   |
| 12    | 1         | 0.01%   |
| 11    | 1         | 0.01%   |
| 9     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9389      | 68.51%  |
| Yes  | 4316      | 31.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 4613      | 52.37%  |
| Realtek Semiconductor           | 904       | 10.26%  |
| Qualcomm Atheros Communications | 572       | 6.49%   |
| IMC Networks                    | 427       | 4.85%   |
| Cambridge Silicon Radio         | 361       | 4.1%    |
| Apple                           | 333       | 3.78%   |
| Foxconn / Hon Hai               | 300       | 3.41%   |
| Broadcom                        | 297       | 3.37%   |
| Lite-On Technology              | 275       | 3.12%   |
| ASUSTek Computer                | 115       | 1.31%   |
| Dell                            | 88        | 1%      |
| Realtek                         | 86        | 0.98%   |
| MediaTek                        | 79        | 0.9%    |
| Hewlett-Packard                 | 64        | 0.73%   |
| Ralink                          | 47        | 0.53%   |
| Toshiba                         | 41        | 0.47%   |
| Marvell Semiconductor           | 40        | 0.45%   |
| TP-Link                         | 35        | 0.4%    |
| Alps Electric                   | 19        | 0.22%   |
| USI                             | 12        | 0.14%   |
| Foxconn International           | 12        | 0.14%   |
| Ralink Technology               | 11        | 0.12%   |
| Integrated System Solution      | 8         | 0.09%   |
| Belkin Components               | 8         | 0.09%   |
| Opticis                         | 7         | 0.08%   |
| Micro Star International        | 7         | 0.08%   |
| Edimax Technology               | 7         | 0.08%   |
| Askey Computer                  | 6         | 0.07%   |
| Logitech                        | 5         | 0.06%   |
| Dynex                           | 4         | 0.05%   |
| Unknown                         | 4         | 0.05%   |
| Actions                         | 3         | 0.03%   |
| Taiyo Yuden                     | 2         | 0.02%   |
| Mobile Action Technology        | 2         | 0.02%   |
| HTC (High Tech Computer)        | 2         | 0.02%   |
| D-Link System                   | 2         | 0.02%   |
| Conwise Technology              | 2         | 0.02%   |
| TRENDnet                        | 1         | 0.01%   |
| Smart Modular Technologies      | 1         | 0.01%   |
| Roper                           | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1368      | 15.52%  |
| Intel AX201 Bluetooth                               | 1149      | 13.03%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 613       | 6.95%   |
| Realtek Bluetooth Radio                             | 577       | 6.54%   |
| Intel AX200 Bluetooth                               | 493       | 5.59%   |
| Intel Bluetooth Device                              | 427       | 4.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 361       | 4.09%   |
| Qualcomm Atheros  Bluetooth Device                  | 279       | 3.16%   |
| Intel AX210 Bluetooth                               | 193       | 2.19%   |
| IMC Networks Wireless_Device                        | 168       | 1.91%   |
| Realtek  Bluetooth 4.2 Adapter                      | 158       | 1.79%   |
| Apple Bluetooth Host Controller                     | 151       | 1.71%   |
| IMC Networks Bluetooth Radio                        | 136       | 1.54%   |
| Intel Wireless-AC 3168 Bluetooth                    | 131       | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 113       | 1.28%   |
| Realtek 802.11ac WLAN Adapter                       | 104       | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 103       | 1.17%   |
| Apple Bluetooth USB Host Controller                 | 91        | 1.03%   |
| Foxconn / Hon Hai Bluetooth Device                  | 85        | 0.96%   |
| MediaTek Wireless_Device                            | 79        | 0.9%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 78        | 0.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 78        | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 75        | 0.85%   |
| Realtek 802.11ac WLAN Adapter                       | 73        | 0.83%   |
| IMC Networks Bluetooth Device                       | 72        | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 66        | 0.75%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 64        | 0.73%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 64        | 0.73%   |
| Lite-On Bluetooth Device                            | 63        | 0.71%   |
| Foxconn / Hon Hai Wireless_Device                   | 52        | 0.59%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 50        | 0.57%   |
| Lite-On Wireless_Device                             | 48        | 0.54%   |
| Ralink RT3290 Bluetooth                             | 47        | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                    | 46        | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                    | 42        | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 40        | 0.45%   |
| TP-Link TP-Cdj+ UB5A Adapter                        | 35        | 0.4%    |
| Broadcom BCM2045B (BDC-2.1)                         | 34        | 0.39%   |
| ASUS ASUS USB-BT500                                 | 34        | 0.39%   |
| Dell DW375 Bluetooth Module                         | 32        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 9858      | 53.85%  |
| AMD                                          | 3596      | 19.64%  |
| Nvidia                                       | 3150      | 17.21%  |
| C-Media Electronics                          | 218       | 1.19%   |
| Logitech                                     | 139       | 0.76%   |
| GN Netcom                                    | 91        | 0.5%    |
| Creative Labs                                | 75        | 0.41%   |
| Realtek Semiconductor                        | 74        | 0.4%    |
| ASUSTek Computer                             | 68        | 0.37%   |
| Apple                                        | 58        | 0.32%   |
| Hewlett-Packard                              | 57        | 0.31%   |
| Plantronics                                  | 51        | 0.28%   |
| JMTek                                        | 51        | 0.28%   |
| Lenovo                                       | 49        | 0.27%   |
| Generalplus Technology                       | 49        | 0.27%   |
| Texas Instruments                            | 47        | 0.26%   |
| Kingston Technology                          | 43        | 0.23%   |
| Razer USA                                    | 40        | 0.22%   |
| Corsair                                      | 38        | 0.21%   |
| Micro Star International                     | 37        | 0.2%    |
| Creative Technology                          | 32        | 0.17%   |
| SteelSeries ApS                              | 30        | 0.16%   |
| Focusrite-Novation                           | 29        | 0.16%   |
| DSEA A/S                                     | 27        | 0.15%   |
| Zoran Co. Personal Media Division (Nogatech) | 14        | 0.08%   |
| Dell                                         | 14        | 0.08%   |
| Tenx Technology                              | 12        | 0.07%   |
| Sony                                         | 12        | 0.07%   |
| BR25                                         | 12        | 0.07%   |
| Microsoft                                    | 10        | 0.05%   |
| DCMT Technology                              | 9         | 0.05%   |
| Blue Microphones                             | 9         | 0.05%   |
| VIA Technologies                             | 8         | 0.04%   |
| M-Audio                                      | 8         | 0.04%   |
| KTMicro                                      | 8         | 0.04%   |
| Giga-Byte Technology                         | 8         | 0.04%   |
| BEHRINGER International                      | 8         | 0.04%   |
| Sennheiser Communications                    | 7         | 0.04%   |
| RODE Microphones                             | 7         | 0.04%   |
| Conexant Systems                             | 7         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1345      | 6.22%   |
| Intel Sunrise Point-LP HD Audio                                            | 1038      | 4.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 817       | 3.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 810       | 3.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 751       | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 751       | 3.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 701       | 3.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 511       | 2.36%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 480       | 2.22%   |
| AMD Starship/Matisse HD Audio Controller                                   | 451       | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 442       | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 374       | 1.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 372       | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 352       | 1.63%   |
| AMD FCH Azalia Controller                                                  | 333       | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 328       | 1.52%   |
| Intel 8 Series HD Audio Controller                                         | 328       | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 319       | 1.48%   |
| Intel Comet Lake PCH-LP cAVS                                               | 305       | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 286       | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 280       | 1.29%   |
| Intel Broadwell-U Audio Controller                                         | 260       | 1.2%    |
| Intel 200 Series PCH HD Audio                                              | 255       | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 242       | 1.12%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 240       | 1.11%   |
| Intel Comet Lake PCH cAVS                                                  | 215       | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 214       | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 211       | 0.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 211       | 0.98%   |
| Nvidia Audio device                                                        | 209       | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 207       | 0.96%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 189       | 0.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 187       | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 175       | 0.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 172       | 0.8%    |
| AMD Kabini HDMI/DP Audio                                                   | 166       | 0.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 166       | 0.77%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 153       | 0.71%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 152       | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 148       | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 2081      | 24.96%  |
| SK hynix                                | 1601      | 19.2%   |
| Micron Technology                       | 984       | 11.8%   |
| Kingston                                | 907       | 10.88%  |
| Crucial                                 | 484       | 5.81%   |
| Corsair                                 | 414       | 4.97%   |
| Unknown                                 | 385       | 4.62%   |
| G.Skill                                 | 236       | 2.83%   |
| A-DATA Technology                       | 188       | 2.26%   |
| Unknown (ABCD)                          | 134       | 1.61%   |
| Ramaxel Technology                      | 118       | 1.42%   |
| Unknown                                 | 108       | 1.3%    |
| Nanya Technology                        | 77        | 0.92%   |
| Team                                    | 69        | 0.83%   |
| Elpida                                  | 62        | 0.74%   |
| Smart                                   | 45        | 0.54%   |
| Patriot                                 | 39        | 0.47%   |
| Transcend                               | 33        | 0.4%    |
| Hewlett-Packard                         | 21        | 0.25%   |
| GOODRAM                                 | 19        | 0.23%   |
| ChangXin Memory                         | 15        | 0.18%   |
| Apacer                                  | 15        | 0.18%   |
| PNY                                     | 13        | 0.16%   |
| Avant                                   | 11        | 0.13%   |
| AMD                                     | 11        | 0.13%   |
| Smart Brazil                            | 10        | 0.12%   |
| ASint Technology                        | 10        | 0.12%   |
| Timetec                                 | 9         | 0.11%   |
| Silicon Power                           | 9         | 0.11%   |
| Teikon                                  | 8         | 0.1%    |
| Neo Forza                               | 8         | 0.1%    |
| Goldkey                                 | 8         | 0.1%    |
| Hikvision                               | 7         | 0.08%   |
| Innodisk                                | 6         | 0.07%   |
| Silicon Power Computer & Communications | 5         | 0.06%   |
| Patriot Memory (PDP Systems)            | 5         | 0.06%   |
| KLEVV                                   | 5         | 0.06%   |
| GeIL                                    | 5         | 0.06%   |
| Atermiter                               | 5         | 0.06%   |
| Wilk                                    | 4         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 113       | 1.28%   |
| Unknown                                                           | 108       | 1.22%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 98        | 1.11%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 81        | 0.91%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 76        | 0.86%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 60        | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 59        | 0.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 58        | 0.65%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s             | 58        | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 55        | 0.62%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s             | 53        | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 52        | 0.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 50        | 0.56%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s              | 49        | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s        | 46        | 0.52%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s             | 41        | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 39        | 0.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 39        | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 39        | 0.44%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s          | 38        | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s      | 37        | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 36        | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s              | 36        | 0.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 35        | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 34        | 0.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 34        | 0.38%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s              | 34        | 0.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 33        | 0.37%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 31        | 0.35%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s          | 31        | 0.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s            | 30        | 0.34%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 29        | 0.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 28        | 0.32%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 28        | 0.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 27        | 0.3%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 27        | 0.3%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                      | 27        | 0.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 26        | 0.29%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s            | 26        | 0.29%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s              | 26        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 3908      | 54.03%  |
| DDR3         | 1832      | 25.33%  |
| LPDDR4       | 485       | 6.71%   |
| DDR5         | 303       | 4.19%   |
| LPDDR3       | 206       | 2.85%   |
| LPDDR5       | 134       | 1.85%   |
| DDR2         | 122       | 1.69%   |
| Unknown      | 121       | 1.67%   |
| SDRAM        | 90        | 1.24%   |
| DDR          | 18        | 0.25%   |
| DRAM         | 13        | 0.18%   |
| DDR2 FB-DIMM | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 4124      | 56.91%  |
| DIMM            | 2176      | 30.03%  |
| Row Of Chips    | 862       | 11.89%  |
| Unknown         | 36        | 0.5%    |
| Chip            | 30        | 0.41%   |
| RIMM            | 10        | 0.14%   |
| FB-DIMM         | 6         | 0.08%   |
| Proprietary Car | 3         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 3210      | 41.15%  |
| 4096   | 1851      | 23.73%  |
| 16384  | 1594      | 20.44%  |
| 2048   | 566       | 7.26%   |
| 32768  | 431       | 5.53%   |
| 1024   | 120       | 1.54%   |
| 65536  | 15        | 0.19%   |
| 6144   | 4         | 0.05%   |
| 131072 | 2         | 0.03%   |
| 49152  | 2         | 0.03%   |
| 12288  | 2         | 0.03%   |
| 512    | 2         | 0.03%   |
| 1536   | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 1840      | 23.78%  |
| 1600    | 1202      | 15.53%  |
| 2667    | 1109      | 14.33%  |
| 2400    | 616       | 7.96%   |
| 1333    | 406       | 5.25%   |
| 2133    | 389       | 5.03%   |
| 4800    | 225       | 2.91%   |
| 4267    | 205       | 2.65%   |
| 3600    | 158       | 2.04%   |
| 1334    | 151       | 1.95%   |
| 1867    | 141       | 1.82%   |
| 6400    | 137       | 1.77%   |
| 800     | 71        | 0.92%   |
| 3733    | 69        | 0.89%   |
| 3266    | 69        | 0.89%   |
| 667     | 69        | 0.89%   |
| 1067    | 61        | 0.79%   |
| 2666    | 52        | 0.67%   |
| 3000    | 51        | 0.66%   |
| Unknown | 51        | 0.66%   |
| 2933    | 47        | 0.61%   |
| 1066    | 46        | 0.59%   |
| 4266    | 42        | 0.54%   |
| 5600    | 38        | 0.49%   |
| 1800    | 35        | 0.45%   |
| 3400    | 33        | 0.43%   |
| 1866    | 33        | 0.43%   |
| 3800    | 31        | 0.4%    |
| 3533    | 26        | 0.34%   |
| 4199    | 23        | 0.3%    |
| 8400    | 17        | 0.22%   |
| 3534    | 16        | 0.21%   |
| 3466    | 14        | 0.18%   |
| 3066    | 13        | 0.17%   |
| 6000    | 12        | 0.16%   |
| 5200    | 12        | 0.16%   |
| 3666    | 12        | 0.16%   |
| 2800    | 11        | 0.14%   |
| 3500    | 10        | 0.13%   |
| 2048    | 10        | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 103       | 32.91%  |
| Brother Industries     | 72        | 23%     |
| Canon                  | 46        | 14.7%   |
| Seiko Epson            | 30        | 9.58%   |
| Samsung Electronics    | 27        | 8.63%   |
| Dymo-CoStar            | 5         | 1.6%    |
| STMicroelectronics     | 4         | 1.28%   |
| Lexmark International  | 4         | 1.28%   |
| Kyocera                | 4         | 1.28%   |
| QinHeng Electronics    | 3         | 0.96%   |
| Prolific Technology    | 3         | 0.96%   |
| Xerox                  | 2         | 0.64%   |
| Zebra                  | 1         | 0.32%   |
| Xiaomi                 | 1         | 0.32%   |
| Pantum                 | 1         | 0.32%   |
| Oki Data               | 1         | 0.32%   |
| Fuji Xerox             | 1         | 0.32%   |
| Dell                   | 1         | 0.32%   |
| Custom Engineering SPA | 1         | 0.32%   |
| BESTEASY               | 1         | 0.32%   |
| Apple                  | 1         | 0.32%   |
| Unknown                | 1         | 0.32%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2300 series                                    | 6         | 1.89%   |
| HP DeskJet 2700 series                                    | 5         | 1.57%   |
| HP DeskJet 2130 series                                    | 5         | 1.57%   |
| Seiko Epson L360 Series                                   | 4         | 1.26%   |
| Dymo-CoStar LabelWriter 400                               | 4         | 1.26%   |
| Canon PIXMA MG2500 Series                                 | 4         | 1.26%   |
| Brother MFC-L2700DW                                       | 4         | 1.26%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 3         | 0.94%   |
| Seiko Epson ET-2720 Series                                | 3         | 0.94%   |
| Samsung ML-216x Series Laser Printer                      | 3         | 0.94%   |
| Samsung Composite Device                                  | 3         | 0.94%   |
| QinHeng CH340S                                            | 3         | 0.94%   |
| Prolific PL2305 Parallel Port                             | 3         | 0.94%   |
| HP OfficeJet 5600 (USBHUB)                                | 3         | 0.94%   |
| HP Officejet 4500 G510n-z                                 | 3         | 0.94%   |
| HP OfficeJet 3830 series                                  | 3         | 0.94%   |
| HP LaserJet M14-M17                                       | 3         | 0.94%   |
| HP LaserJet 4250                                          | 3         | 0.94%   |
| HP DeskJet 2620 All-in-One Printer                        | 3         | 0.94%   |
| Canon TS3100 series                                       | 3         | 0.94%   |
| Canon LBP2900                                             | 3         | 0.94%   |
| Brother Printer                                           | 3         | 0.94%   |
| Brother HL-L2350DW series                                 | 3         | 0.94%   |
| Brother HL-1440 Laser Printer                             | 3         | 0.94%   |
| Brother DCP-1510                                          | 3         | 0.94%   |
| Seiko Epson XP-2100 Series                                | 2         | 0.63%   |
| Seiko Epson L3150 Series                                  | 2         | 0.63%   |
| Seiko Epson L3110 Series                                  | 2         | 0.63%   |
| Seiko Epson ET-4800 Series                                | 2         | 0.63%   |
| Seiko Epson ET-2810 Series                                | 2         | 0.63%   |
| Seiko Epson ET-2600 Series                                | 2         | 0.63%   |
| Samsung SCX-472x Series                                   | 2         | 0.63%   |
| Samsung M2070 Series                                      | 2         | 0.63%   |
| Samsung C460 Series                                       | 2         | 0.63%   |
| Samsung C43x Series                                       | 2         | 0.63%   |
| HP LaserJet P1005                                         | 2         | 0.63%   |
| HP LaserJet M203-M206                                     | 2         | 0.63%   |
| HP LaserJet 3015                                          | 2         | 0.63%   |
| HP LaserJet 1020                                          | 2         | 0.63%   |
| HP HP OfficeJet Pro 8020 series                           | 2         | 0.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 29        | 53.7%   |
| Seiko Epson                 | 12        | 22.22%  |
| Hewlett-Packard             | 8         | 14.81%  |
| UMAX                        | 1         | 1.85%   |
| Mustek Systems              | 1         | 1.85%   |
| KYE Systems (Mouse Systems) | 1         | 1.85%   |
| AGFA-Gevaert NV             | 1         | 1.85%   |
| Acer Peripherals (now BenQ) | 1         | 1.85%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                                  | 6         | 11.11%  |
| Canon CanoScan LiDE 110                                  | 4         | 7.41%   |
| Canon CanoScan LiDE 100                                  | 4         | 7.41%   |
| Canon CanoScan LiDE 220                                  | 3         | 5.56%   |
| Seiko Epson GT-F700 [Perfection V350]                    | 2         | 3.7%    |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 2         | 3.7%    |
| Canon CanoScan LIDE 25                                   | 2         | 3.7%    |
| Canon CanoScan 4200F                                     | 2         | 3.7%    |
| UMAX Astra 2200/2200SU                                   | 1         | 1.85%   |
| Seiko Epson GT-X770 [Perfection V500]                    | 1         | 1.85%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 1.85%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 1         | 1.85%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 1         | 1.85%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]            | 1         | 1.85%   |
| Seiko Epson GT-7700U [Perfection 1240U]                  | 1         | 1.85%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1         | 1.85%   |
| Seiko Epson ES-D200 [GT-S50]                             | 1         | 1.85%   |
| Mustek Systems BearPaw 2448 CU Pro                       | 1         | 1.85%   |
| KYE Systems (Mouse Systems) ColorPage-SF600              | 1         | 1.85%   |
| HP Scanjet N6010                                         | 1         | 1.85%   |
| HP ScanJet G4010                                         | 1         | 1.85%   |
| HP Scanjet G2710                                         | 1         | 1.85%   |
| HP ScanJet 7400c                                         | 1         | 1.85%   |
| HP ScanJet 4850C/4890C                                   | 1         | 1.85%   |
| HP ScanJet 3970c                                         | 1         | 1.85%   |
| HP ScanJet 3400cse                                       | 1         | 1.85%   |
| HP OfficeJet 6110                                        | 1         | 1.85%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1         | 1.85%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 1.85%   |
| Canon CanoScan LiDE 70                                   | 1         | 1.85%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 1.85%   |
| Canon CanoScan LiDE 210                                  | 1         | 1.85%   |
| Canon CanoScan LiDE 200                                  | 1         | 1.85%   |
| Canon CanoScan 9000F Mark II                             | 1         | 1.85%   |
| Canon CanoScan 1220U                                     | 1         | 1.85%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                       | 1         | 1.85%   |
| Acer Peripherals (now BenQ) Benq 5000                    | 1         | 1.85%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1580      | 18.75%  |
| IMC Networks                           | 837       | 9.93%   |
| Microdia                               | 785       | 9.32%   |
| Realtek Semiconductor                  | 621       | 7.37%   |
| Quanta                                 | 505       | 5.99%   |
| Sunplus Innovation Technology          | 490       | 5.82%   |
| Bison Electronics                      | 466       | 5.53%   |
| Logitech                               | 437       | 5.19%   |
| Apple                                  | 319       | 3.79%   |
| Cheng Uei Precision Industry (Foxlink) | 310       | 3.68%   |
| Syntek                                 | 224       | 2.66%   |
| Luxvisions Innotech Limited            | 223       | 2.65%   |
| Suyin                                  | 189       | 2.24%   |
| Lite-On Technology                     | 170       | 2.02%   |
| Acer                                   | 102       | 1.21%   |
| Samsung Electronics                    | 89        | 1.06%   |
| Microsoft                              | 87        | 1.03%   |
| Sonix Technology                       | 84        | 1%      |
| Silicon Motion                         | 82        | 0.97%   |
| Alcor Micro                            | 82        | 0.97%   |
| Ricoh                                  | 55        | 0.65%   |
| SunplusIT                              | 53        | 0.63%   |
| Z-Star Microelectronics                | 41        | 0.49%   |
| Generalplus Technology                 | 32        | 0.38%   |
| icSpring                               | 31        | 0.37%   |
| Importek                               | 29        | 0.34%   |
| ARC International                      | 27        | 0.32%   |
| Lenovo                                 | 26        | 0.31%   |
| Primax Electronics                     | 23        | 0.27%   |
| ALi                                    | 21        | 0.25%   |
| Y Media                                | 17        | 0.2%    |
| Sunplus Technology                     | 14        | 0.17%   |
| Trust                                  | 13        | 0.15%   |
| HDR webcam                             | 13        | 0.15%   |
| KYE Systems (Mouse Systems)            | 12        | 0.14%   |
| Jieli Technology                       | 12        | 0.14%   |
| Creative Technology                    | 12        | 0.14%   |
| ShineTech                              | 11        | 0.13%   |
| Cubeternet                             | 10        | 0.12%   |
| WaveRider Communications               | 9         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 385       | 4.53%   |
| Chicony Integrated Camera                           | 356       | 4.19%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 262       | 3.08%   |
| Realtek Integrated_Webcam_HD                        | 229       | 2.69%   |
| IMC Networks Integrated Camera                      | 221       | 2.6%    |
| Bison Integrated Camera                             | 175       | 2.06%   |
| Syntek Integrated Camera                            | 157       | 1.85%   |
| Chicony HD WebCam                                   | 130       | 1.53%   |
| Sunplus Integrated_Webcam_HD                        | 124       | 1.46%   |
| Apple FaceTime HD Camera (Built-in)                 | 104       | 1.22%   |
| Logitech Webcam C270                                | 101       | 1.19%   |
| Chicony HP HD Camera                                | 100       | 1.18%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 88        | 1.03%   |
| Samsung Galaxy series, misc. (MTP mode)             | 87        | 1.02%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 82        | 0.96%   |
| Realtek USB Camera                                  | 80        | 0.94%   |
| Apple Built-in iSight                               | 78        | 0.92%   |
| Quanta HP HD Camera                                 | 74        | 0.87%   |
| Quanta HD User Facing                               | 73        | 0.86%   |
| Logitech HD Pro Webcam C920                         | 66        | 0.78%   |
| Bison HD Webcam                                     | 65        | 0.76%   |
| IMC Networks HD Camera                              | 60        | 0.71%   |
| Quanta HP TrueVision HD Camera                      | 58        | 0.68%   |
| Lite-On Integrated Camera                           | 57        | 0.67%   |
| Chicony HP Wide Vision HD Camera                    | 57        | 0.67%   |
| Chicony HP TrueVision HD Camera                     | 55        | 0.65%   |
| Sunplus HD WebCam                                   | 54        | 0.63%   |
| Microdia Webcam Vitade AF                           | 53        | 0.62%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 52        | 0.61%   |
| Chicony TOSHIBA Web Camera - HD                     | 51        | 0.6%    |
| Chicony HD User Facing                              | 50        | 0.59%   |
| Chicony USB2.0 HD UVC WebCam                        | 49        | 0.58%   |
| Sonix USB2.0 HD UVC WebCam                          | 48        | 0.56%   |
| Quanta HP Wide Vision HD Camera                     | 48        | 0.56%   |
| Luxvisions Innotech Limited HP HD Camera            | 48        | 0.56%   |
| Quanta ACER HD User Facing                          | 47        | 0.55%   |
| Luxvisions Innotech Limited Integrated Camera       | 47        | 0.55%   |
| Alcor Micro USB 2.0 Camera                          | 45        | 0.53%   |
| Microdia Integrated Webcam                          | 44        | 0.52%   |
| Chicony HP TrueVision HD                            | 44        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 505       | 30.06%  |
| Validity Sensors                   | 490       | 29.17%  |
| Shenzhen Goodix Technology         | 351       | 20.89%  |
| Elan Microelectronics              | 129       | 7.68%   |
| Upek                               | 50        | 2.98%   |
| AuthenTec                          | 46        | 2.74%   |
| LighTuning Technology              | 40        | 2.38%   |
| Realtek USB2.0 Finger Print Bridge | 29        | 1.73%   |
| STMicroelectronics                 | 11        | 0.65%   |
| Samsung Electronics                | 9         | 0.54%   |
| Focal-systems.Corp                 | 7         | 0.42%   |
| HOLTEK                             | 5         | 0.3%    |
| GDMicroelectronics                 | 3         | 0.18%   |
| DigitalPersona                     | 2         | 0.12%   |
| Dell                               | 2         | 0.12%   |
| Microsoft                          | 1         | 0.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 240       | 14.28%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 119       | 7.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 114       | 6.78%   |
| Elan ELAN:ARM-M4                                                           | 77        | 4.58%   |
| Shenzhen Goodix Fingerprint Reader                                         | 69        | 4.1%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 58        | 3.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 54        | 3.21%   |
| Elan ELAN:Fingerprint                                                      | 51        | 3.03%   |
| Validity Sensors Synaptics WBDI                                            | 47        | 2.8%    |
| Synaptics WBDI                                                             | 46        | 2.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 45        | 2.68%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 42        | 2.5%    |
| Shenzhen Goodix FingerPrint                                                | 42        | 2.5%    |
| Synaptics UWP WBDI                                                         | 40        | 2.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 39        | 2.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 37        | 2.2%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 37        | 2.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 37        | 2.2%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 29        | 1.73%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 29        | 1.73%   |
| Validity Sensors VFS491                                                    | 28        | 1.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 25        | 1.49%   |
| Validity Sensors Fingerprint scanner                                       | 25        | 1.49%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 25        | 1.49%   |
| Synaptics UWP WBDI Device                                                  | 24        | 1.43%   |
| Synaptics Fingerprint reader [HP G6]                                       | 24        | 1.43%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 23        | 1.37%   |
| Synaptics  WBDI                                                            | 22        | 1.31%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 21        | 1.25%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 1.25%   |
| AuthenTec Fingerprint Sensor                                               | 18        | 1.07%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 17        | 1.01%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 11        | 0.65%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 0.65%   |
| Unknown                                                                    | 11        | 0.65%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 0.54%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 0.54%   |
| AuthenTec AES2810                                                          | 8         | 0.48%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 0.42%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 7         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 349       | 53.36%  |
| Alcor Micro               | 175       | 26.76%  |
| O2 Micro                  | 27        | 4.13%   |
| Upek                      | 20        | 3.06%   |
| Gemalto (was Gemplus)     | 14        | 2.14%   |
| Lenovo                    | 13        | 1.99%   |
| SCM Microsystems          | 11        | 1.68%   |
| Advanced Card Systems     | 10        | 1.53%   |
| Realtek Semiconductor     | 6         | 0.92%   |
| Chicony Electronics       | 5         | 0.76%   |
| Aladdin Knowledge Systems | 4         | 0.61%   |
| Giesecke & Devrient       | 3         | 0.46%   |
| Cherry                    | 3         | 0.46%   |
| Watchdata                 | 2         | 0.31%   |
| Reiner SCT Kartensysteme  | 2         | 0.31%   |
| OmniKey                   | 2         | 0.31%   |
| Fujitsu Siemens Computers | 2         | 0.31%   |
| Bit4id                    | 2         | 0.31%   |
| NXP Semiconductors        | 1         | 0.15%   |
| Feitian Technologies      | 1         | 0.15%   |
| C3PO                      | 1         | 0.15%   |
| Aktiv                     | 1         | 0.15%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 174       | 26.61%  |
| Broadcom 58200                                                               | 120       | 18.35%  |
| Broadcom BCM5880 Secure Applications Processor                               | 97        | 14.83%  |
| Broadcom 5880                                                                | 88        | 13.46%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 44        | 6.73%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 25        | 3.82%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 20        | 3.06%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 1.83%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 11        | 1.68%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 9         | 1.38%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 6         | 0.92%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 5         | 0.76%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 5         | 0.76%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 0.61%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 3         | 0.46%   |
| Advanced Card Systems ACR122U                                                | 3         | 0.46%   |
| Watchdata USB Key                                                            | 2         | 0.31%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.31%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 0.31%   |
| Giesecke & Devrient StarSign CUT S                                           | 2         | 0.31%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.31%   |
| SCM Microsystems SCR35xx USB Smart Card Reader                               | 1         | 0.15%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.15%   |
| OmniKey CardMan 4321                                                         | 1         | 0.15%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.15%   |
| NXP Semiconductors PR533                                                     | 1         | 0.15%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.15%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.15%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.15%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.15%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.15%   |
| Feitian Technologies FIDO CCID KB                                            | 1         | 0.15%   |
| C3PO LTC31v2                                                                 | 1         | 0.15%   |
| Bit4id miniLector-s                                                          | 1         | 0.15%   |
| Bit4id miniLector EVO                                                        | 1         | 0.15%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.15%   |
| Aktiv Rutoken lite                                                           | 1         | 0.15%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.15%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.15%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 9138      | 66.48%  |
| 1     | 3622      | 26.35%  |
| 2     | 730       | 5.31%   |
| 3     | 149       | 1.08%   |
| 4     | 64        | 0.47%   |
| 5     | 16        | 0.12%   |
| 6     | 13        | 0.09%   |
| 8     | 4         | 0.03%   |
| 7     | 4         | 0.03%   |
| 9     | 3         | 0.02%   |
| 10    | 2         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1643      | 28.77%  |
| Graphics card            | 1459      | 25.55%  |
| Chipcard                 | 606       | 10.61%  |
| Net/wireless             | 564       | 9.88%   |
| Camera                   | 289       | 5.06%   |
| Communication controller | 244       | 4.27%   |
| Multimedia controller    | 210       | 3.68%   |
| Unassigned class         | 196       | 3.43%   |
| Sound                    | 138       | 2.42%   |
| Bluetooth                | 119       | 2.08%   |
| Storage                  | 62        | 1.09%   |
| Card reader              | 47        | 0.82%   |
| Net/ethernet             | 44        | 0.77%   |
| Network                  | 33        | 0.58%   |
| Storage/raid             | 22        | 0.39%   |
| Dvb card                 | 8         | 0.14%   |
| Modem                    | 6         | 0.11%   |
| Storage/nvme             | 4         | 0.07%   |
| Storage/ata              | 4         | 0.07%   |
| Flash memory             | 3         | 0.05%   |
| Wireless                 | 2         | 0.04%   |
| Tv card                  | 2         | 0.04%   |
| Storage/ide              | 2         | 0.04%   |
| Firewire controller      | 2         | 0.04%   |
| Unclassified device      | 1         | 0.02%   |

