Linux in Belarus - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Belarus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Belarus/Desktop/README.md) and [notebooks](/Location/Belarus/Notebook/README.md).

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

Total: 1315

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [414795a69b](https://linux-hardware.org/?probe=414795a69b) | Aug 29, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d9d75bc1f0](https://linux-hardware.org/?probe=d9d75bc1f0) | Aug 29, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [2ee74a388d](https://linux-hardware.org/?probe=2ee74a388d) | Aug 25, 2022 |
| HP            | Compaq 610                  | Notebook    | [538b6ae6f8](https://linux-hardware.org/?probe=538b6ae6f8) | Aug 24, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [79d380d4af](https://linux-hardware.org/?probe=79d380d4af) | Aug 21, 2022 |
| Acer          | Aspire 7750ZG               | Notebook    | [e0d514dd08](https://linux-hardware.org/?probe=e0d514dd08) | Aug 21, 2022 |
| Lenovo        | Z710 20250                  | Notebook    | [8c7e567f41](https://linux-hardware.org/?probe=8c7e567f41) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| HP            | Compaq 610                  | Notebook    | [2b90520f8f](https://linux-hardware.org/?probe=2b90520f8f) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f685da542](https://linux-hardware.org/?probe=3f685da542) | Aug 17, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [3decfcd64a](https://linux-hardware.org/?probe=3decfcd64a) | Aug 14, 2022 |
| Huanan        | X99-BD4 V1.33               | Desktop     | [a250b39eec](https://linux-hardware.org/?probe=a250b39eec) | Aug 13, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [1e1745d32c](https://linux-hardware.org/?probe=1e1745d32c) | Aug 12, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [a763c682f5](https://linux-hardware.org/?probe=a763c682f5) | Aug 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f41308ccdc](https://linux-hardware.org/?probe=f41308ccdc) | Aug 12, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [b73567b27b](https://linux-hardware.org/?probe=b73567b27b) | Aug 09, 2022 |
| Sony          | SVF1521L1RW                 | Notebook    | [c5f143f93d](https://linux-hardware.org/?probe=c5f143f93d) | Aug 09, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [4b4e4d693e](https://linux-hardware.org/?probe=4b4e4d693e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [feb8312a2c](https://linux-hardware.org/?probe=feb8312a2c) | Aug 04, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [462af39f9d](https://linux-hardware.org/?probe=462af39f9d) | Aug 01, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [97f6892c6c](https://linux-hardware.org/?probe=97f6892c6c) | Jul 30, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [c8562d4bac](https://linux-hardware.org/?probe=c8562d4bac) | Jul 27, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e899f43a3f](https://linux-hardware.org/?probe=e899f43a3f) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [4e757278be](https://linux-hardware.org/?probe=4e757278be) | Jul 24, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [1ee2492f24](https://linux-hardware.org/?probe=1ee2492f24) | Jul 23, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [2d2a17094e](https://linux-hardware.org/?probe=2d2a17094e) | Jul 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [6089dc323f](https://linux-hardware.org/?probe=6089dc323f) | Jul 17, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [7142849ed0](https://linux-hardware.org/?probe=7142849ed0) | Jul 17, 2022 |
| Fujitsu       | AMILO Pi 3560               | Notebook    | [aed2d10046](https://linux-hardware.org/?probe=aed2d10046) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5638d3552](https://linux-hardware.org/?probe=e5638d3552) | Jul 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c81bc160f7](https://linux-hardware.org/?probe=c81bc160f7) | Jul 13, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [3f20ad2267](https://linux-hardware.org/?probe=3f20ad2267) | Jul 11, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [bb760c59ed](https://linux-hardware.org/?probe=bb760c59ed) | Jul 11, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [b7adccb849](https://linux-hardware.org/?probe=b7adccb849) | Jul 09, 2022 |
| Samsung       | 535U3C                      | Notebook    | [80b2b79e75](https://linux-hardware.org/?probe=80b2b79e75) | Jul 09, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [15a618f993](https://linux-hardware.org/?probe=15a618f993) | Jul 08, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [2ef855cc9c](https://linux-hardware.org/?probe=2ef855cc9c) | Jul 07, 2022 |
| HP            | Compaq 610                  | Notebook    | [62287cff21](https://linux-hardware.org/?probe=62287cff21) | Jul 06, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [26cbd669e4](https://linux-hardware.org/?probe=26cbd669e4) | Jul 05, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [2fb330049e](https://linux-hardware.org/?probe=2fb330049e) | Jul 04, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [2b31833bfe](https://linux-hardware.org/?probe=2b31833bfe) | Jul 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [06d4d79742](https://linux-hardware.org/?probe=06d4d79742) | Jul 01, 2022 |
| Biostar       | TA790GX 128M                | Desktop     | [c7021e0b8c](https://linux-hardware.org/?probe=c7021e0b8c) | Jul 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| Prestigio     | Multipad Visconte V         | Notebook    | [fd38a70070](https://linux-hardware.org/?probe=fd38a70070) | Jun 29, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [8cb88942e3](https://linux-hardware.org/?probe=8cb88942e3) | Jun 28, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [e52ad13385](https://linux-hardware.org/?probe=e52ad13385) | Jun 25, 2022 |
| NCS-Tech      | B300                        | Notebook    | [ff8382e269](https://linux-hardware.org/?probe=ff8382e269) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| NCS-Tech      | B300                        | Notebook    | [d0b0703736](https://linux-hardware.org/?probe=d0b0703736) | Jun 23, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [6dd752fab5](https://linux-hardware.org/?probe=6dd752fab5) | Jun 23, 2022 |
| Dell          | 0PGMR1 A00                  | All in one  | [bf057e65d8](https://linux-hardware.org/?probe=bf057e65d8) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| HP            | Notebook                    | Notebook    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Acer          | Extensa 5220                | Notebook    | [dd0d362582](https://linux-hardware.org/?probe=dd0d362582) | Jun 15, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [d381bbec9f](https://linux-hardware.org/?probe=d381bbec9f) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [8e7a43f724](https://linux-hardware.org/?probe=8e7a43f724) | Jun 13, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [fd45495f2a](https://linux-hardware.org/?probe=fd45495f2a) | Jun 12, 2022 |
| HP            | Notebook                    | Notebook    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [595e4c8656](https://linux-hardware.org/?probe=595e4c8656) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [0ee020dd5a](https://linux-hardware.org/?probe=0ee020dd5a) | Jun 09, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [e057e3b6d8](https://linux-hardware.org/?probe=e057e3b6d8) | Jun 07, 2022 |
| HP            | Mini 110-4100               | Notebook    | [62932d62d5](https://linux-hardware.org/?probe=62932d62d5) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3aa4194ab3](https://linux-hardware.org/?probe=3aa4194ab3) | Jun 02, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [88d5e21b42](https://linux-hardware.org/?probe=88d5e21b42) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [50927f5cae](https://linux-hardware.org/?probe=50927f5cae) | May 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1be8c71a37](https://linux-hardware.org/?probe=1be8c71a37) | May 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [2669150033](https://linux-hardware.org/?probe=2669150033) | May 29, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee508ca972](https://linux-hardware.org/?probe=ee508ca972) | May 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [4b1c87e746](https://linux-hardware.org/?probe=4b1c87e746) | May 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [dd317d92a3](https://linux-hardware.org/?probe=dd317d92a3) | May 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| HP            | Mini 110-4100               | Notebook    | [c09a467c25](https://linux-hardware.org/?probe=c09a467c25) | May 24, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d2dbdbd444](https://linux-hardware.org/?probe=d2dbdbd444) | May 22, 2022 |
| ECS           | IC780M-A2                   | Desktop     | [135f0a4328](https://linux-hardware.org/?probe=135f0a4328) | May 21, 2022 |
| MSI           | MS-7309                     | Desktop     | [9093ca0773](https://linux-hardware.org/?probe=9093ca0773) | May 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9e7bf270db](https://linux-hardware.org/?probe=9e7bf270db) | May 17, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [934bd75010](https://linux-hardware.org/?probe=934bd75010) | May 16, 2022 |
| ASUSTek       | M51Sr                       | Notebook    | [ebcb6315c9](https://linux-hardware.org/?probe=ebcb6315c9) | May 16, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [ec4bd74f0b](https://linux-hardware.org/?probe=ec4bd74f0b) | May 13, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [a53ce6039b](https://linux-hardware.org/?probe=a53ce6039b) | May 12, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [46481247b1](https://linux-hardware.org/?probe=46481247b1) | May 12, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [2a916e3eb5](https://linux-hardware.org/?probe=2a916e3eb5) | May 09, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [fbe61c70ff](https://linux-hardware.org/?probe=fbe61c70ff) | May 09, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [edefb39601](https://linux-hardware.org/?probe=edefb39601) | May 08, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [76e67361ea](https://linux-hardware.org/?probe=76e67361ea) | May 08, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [8926d96550](https://linux-hardware.org/?probe=8926d96550) | May 07, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7c8dbdcffc](https://linux-hardware.org/?probe=7c8dbdcffc) | May 05, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8fbc520a1b](https://linux-hardware.org/?probe=8fbc520a1b) | May 03, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [9390db3498](https://linux-hardware.org/?probe=9390db3498) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [7fb6e94bab](https://linux-hardware.org/?probe=7fb6e94bab) | Apr 27, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [ff5ff260a0](https://linux-hardware.org/?probe=ff5ff260a0) | Apr 26, 2022 |
| ASUSTek       | ROG Maximus XI CODE         | Desktop     | [8cca49b0ee](https://linux-hardware.org/?probe=8cca49b0ee) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [18a941a40d](https://linux-hardware.org/?probe=18a941a40d) | Apr 19, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [1bfd1d7042](https://linux-hardware.org/?probe=1bfd1d7042) | Apr 18, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [e2034a7617](https://linux-hardware.org/?probe=e2034a7617) | Apr 17, 2022 |
| HP            | Notebook                    | Notebook    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [ab464ae6a9](https://linux-hardware.org/?probe=ab464ae6a9) | Apr 15, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [46b7178535](https://linux-hardware.org/?probe=46b7178535) | Apr 14, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [155e5c0ef5](https://linux-hardware.org/?probe=155e5c0ef5) | Apr 14, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [07de6c8eb6](https://linux-hardware.org/?probe=07de6c8eb6) | Apr 12, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [6273f8eefb](https://linux-hardware.org/?probe=6273f8eefb) | Apr 12, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [1dff7e3c31](https://linux-hardware.org/?probe=1dff7e3c31) | Apr 11, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [292cc244de](https://linux-hardware.org/?probe=292cc244de) | Apr 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [90a9483531](https://linux-hardware.org/?probe=90a9483531) | Apr 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6099079c27](https://linux-hardware.org/?probe=6099079c27) | Apr 09, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [9ea9a7e8ef](https://linux-hardware.org/?probe=9ea9a7e8ef) | Apr 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [a096b22b37](https://linux-hardware.org/?probe=a096b22b37) | Apr 09, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [993ad2218a](https://linux-hardware.org/?probe=993ad2218a) | Apr 07, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [bcbdedc21a](https://linux-hardware.org/?probe=bcbdedc21a) | Apr 07, 2022 |
| ASUSTek       | X541NC                      | Notebook    | [a7af7e79fd](https://linux-hardware.org/?probe=a7af7e79fd) | Apr 06, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [6d2f9e0fce](https://linux-hardware.org/?probe=6d2f9e0fce) | Apr 05, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [2b9c6b4b05](https://linux-hardware.org/?probe=2b9c6b4b05) | Apr 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [2d741207c5](https://linux-hardware.org/?probe=2d741207c5) | Mar 30, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [50780eda28](https://linux-hardware.org/?probe=50780eda28) | Mar 30, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [026a52c3bf](https://linux-hardware.org/?probe=026a52c3bf) | Mar 27, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [803a20d0cb](https://linux-hardware.org/?probe=803a20d0cb) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | Notebook    | [ef7133f14a](https://linux-hardware.org/?probe=ef7133f14a) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [49853bb240](https://linux-hardware.org/?probe=49853bb240) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | Notebook    | [06883f214a](https://linux-hardware.org/?probe=06883f214a) | Mar 25, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [9e554de092](https://linux-hardware.org/?probe=9e554de092) | Mar 24, 2022 |
| Gigabyte      | B450M S2H V2                | Desktop     | [a8e8d6dd5e](https://linux-hardware.org/?probe=a8e8d6dd5e) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [378bbcd029](https://linux-hardware.org/?probe=378bbcd029) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6ede510a1b](https://linux-hardware.org/?probe=6ede510a1b) | Mar 22, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [db687b8693](https://linux-hardware.org/?probe=db687b8693) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [770f279722](https://linux-hardware.org/?probe=770f279722) | Mar 13, 2022 |
| ASRock        | FM2A55M-VG3                 | Desktop     | [96683b7f45](https://linux-hardware.org/?probe=96683b7f45) | Mar 12, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [517ef58b87](https://linux-hardware.org/?probe=517ef58b87) | Mar 11, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [69fd2b147f](https://linux-hardware.org/?probe=69fd2b147f) | Mar 11, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [55ce4f1460](https://linux-hardware.org/?probe=55ce4f1460) | Mar 11, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [73d930be97](https://linux-hardware.org/?probe=73d930be97) | Mar 10, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [a6fc7b9f12](https://linux-hardware.org/?probe=a6fc7b9f12) | Mar 10, 2022 |
| Intel         | D945GCLF2 AAE46416-101      | Desktop     | [800bc08dbd](https://linux-hardware.org/?probe=800bc08dbd) | Mar 09, 2022 |
| HP            | Mini 110-4100               | Notebook    | [2c1bf1951f](https://linux-hardware.org/?probe=2c1bf1951f) | Mar 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [aebf1eb00c](https://linux-hardware.org/?probe=aebf1eb00c) | Mar 07, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [18486d2474](https://linux-hardware.org/?probe=18486d2474) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [949d0886a1](https://linux-hardware.org/?probe=949d0886a1) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [f5241bc829](https://linux-hardware.org/?probe=f5241bc829) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| HP            | 635                         | Notebook    | [0d571de480](https://linux-hardware.org/?probe=0d571de480) | Mar 03, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [bdba90c583](https://linux-hardware.org/?probe=bdba90c583) | Mar 03, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d2e96e523e](https://linux-hardware.org/?probe=d2e96e523e) | Mar 03, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [880490eb1e](https://linux-hardware.org/?probe=880490eb1e) | Mar 01, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [79cc0b97a4](https://linux-hardware.org/?probe=79cc0b97a4) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [74bc866ab2](https://linux-hardware.org/?probe=74bc866ab2) | Feb 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7ce556e43a](https://linux-hardware.org/?probe=7ce556e43a) | Feb 26, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [39389b9ddf](https://linux-hardware.org/?probe=39389b9ddf) | Feb 26, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [013e049a4d](https://linux-hardware.org/?probe=013e049a4d) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [885239a137](https://linux-hardware.org/?probe=885239a137) | Feb 24, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [34e4b434b4](https://linux-hardware.org/?probe=34e4b434b4) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| ASUSTek       | K50C                        | Notebook    | [01079b722b](https://linux-hardware.org/?probe=01079b722b) | Feb 11, 2022 |
| ASUSTek       | K50C                        | Notebook    | [8bb8c751f8](https://linux-hardware.org/?probe=8bb8c751f8) | Feb 11, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [601f46e5a4](https://linux-hardware.org/?probe=601f46e5a4) | Feb 09, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7966e303e6](https://linux-hardware.org/?probe=7966e303e6) | Feb 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a32dfea06a](https://linux-hardware.org/?probe=a32dfea06a) | Feb 07, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [e2a7b380d8](https://linux-hardware.org/?probe=e2a7b380d8) | Feb 06, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d7796dd19f](https://linux-hardware.org/?probe=d7796dd19f) | Feb 05, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [8b9e72e0ed](https://linux-hardware.org/?probe=8b9e72e0ed) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [ce0fa6ccd3](https://linux-hardware.org/?probe=ce0fa6ccd3) | Feb 03, 2022 |
| MSI           | B150M PRO-VH                | Desktop     | [583a1313c8](https://linux-hardware.org/?probe=583a1313c8) | Feb 01, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [0bcf18e1fc](https://linux-hardware.org/?probe=0bcf18e1fc) | Feb 01, 2022 |
| HP            | Compaq 8710w (GC124EA#AC... | Notebook    | [b21e187792](https://linux-hardware.org/?probe=b21e187792) | Jan 29, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [ed633ddd09](https://linux-hardware.org/?probe=ed633ddd09) | Jan 29, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [607ade73d0](https://linux-hardware.org/?probe=607ade73d0) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | H87M-E35                    | Desktop     | [0cfdd2b772](https://linux-hardware.org/?probe=0cfdd2b772) | Jan 28, 2022 |
| HP            | Presario CQ57               | Notebook    | [6a8428a112](https://linux-hardware.org/?probe=6a8428a112) | Jan 27, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [abed2f64a1](https://linux-hardware.org/?probe=abed2f64a1) | Jan 26, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [7dbefa64bc](https://linux-hardware.org/?probe=7dbefa64bc) | Jan 23, 2022 |
| Kllisre       | X79 V1.2                    | Desktop     | [84bd3ccecf](https://linux-hardware.org/?probe=84bd3ccecf) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e00760f649](https://linux-hardware.org/?probe=e00760f649) | Jan 21, 2022 |
| MSI           | B150M PRO-VH                | Desktop     | [de22d479a4](https://linux-hardware.org/?probe=de22d479a4) | Jan 20, 2022 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [8b2f4ffccd](https://linux-hardware.org/?probe=8b2f4ffccd) | Jan 16, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [291a3e234b](https://linux-hardware.org/?probe=291a3e234b) | Jan 14, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [8f9c010abb](https://linux-hardware.org/?probe=8f9c010abb) | Jan 10, 2022 |
| Kllisre       | X79 V1.2                    | Desktop     | [239547a419](https://linux-hardware.org/?probe=239547a419) | Jan 09, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| Dell          | G7 7700                     | Notebook    | [f02bcbdcfe](https://linux-hardware.org/?probe=f02bcbdcfe) | Jan 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| MSI           | GT75 Titan 8RG              | Notebook    | [77e24243cf](https://linux-hardware.org/?probe=77e24243cf) | Jan 02, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [5d9026b1c0](https://linux-hardware.org/?probe=5d9026b1c0) | Jan 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [9f9fe096db](https://linux-hardware.org/?probe=9f9fe096db) | Dec 30, 2021 |
| MSI           | MS-7922                     | Desktop     | [d0837f687b](https://linux-hardware.org/?probe=d0837f687b) | Dec 27, 2021 |
| Lenovo        | ThinkPad E15 20RD003KRT     | Notebook    | [62e3c3073b](https://linux-hardware.org/?probe=62e3c3073b) | Dec 26, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [29b9cc77f1](https://linux-hardware.org/?probe=29b9cc77f1) | Dec 21, 2021 |
| Gigabyte      | M61SME-S2                   | Desktop     | [be9f6cac13](https://linux-hardware.org/?probe=be9f6cac13) | Dec 20, 2021 |
| ASUSTek       | X540UA                      | Notebook    | [4d399918f0](https://linux-hardware.org/?probe=4d399918f0) | Dec 20, 2021 |
| HONOR         | BMH-WCX9                    | Notebook    | [46395a1450](https://linux-hardware.org/?probe=46395a1450) | Dec 19, 2021 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [7f0853c09e](https://linux-hardware.org/?probe=7f0853c09e) | Dec 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0642db16f6](https://linux-hardware.org/?probe=0642db16f6) | Dec 19, 2021 |
| MSI           | GL63 9SC                    | Notebook    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Fujitsu       | LIFEBOOK NH532              | Notebook    | [84be255271](https://linux-hardware.org/?probe=84be255271) | Dec 15, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [0573beab82](https://linux-hardware.org/?probe=0573beab82) | Dec 15, 2021 |
| BenQ          | Joybook R56                 | Notebook    | [e05d04b5ec](https://linux-hardware.org/?probe=e05d04b5ec) | Dec 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [43f645de28](https://linux-hardware.org/?probe=43f645de28) | Dec 11, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [a2e037ba0e](https://linux-hardware.org/?probe=a2e037ba0e) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f9ada169fd](https://linux-hardware.org/?probe=f9ada169fd) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d39826b60](https://linux-hardware.org/?probe=7d39826b60) | Dec 09, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [610d56a10a](https://linux-hardware.org/?probe=610d56a10a) | Dec 08, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [3c415780c5](https://linux-hardware.org/?probe=3c415780c5) | Dec 06, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| LG Electro... | R510                        | Notebook    | [13f4496897](https://linux-hardware.org/?probe=13f4496897) | Nov 28, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [00c297540d](https://linux-hardware.org/?probe=00c297540d) | Nov 27, 2021 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [0162ece16f](https://linux-hardware.org/?probe=0162ece16f) | Nov 25, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c420169ce7](https://linux-hardware.org/?probe=c420169ce7) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b9e2d78f66](https://linux-hardware.org/?probe=b9e2d78f66) | Nov 23, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [53e26c9677](https://linux-hardware.org/?probe=53e26c9677) | Nov 22, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [488cdb831c](https://linux-hardware.org/?probe=488cdb831c) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1784f93056](https://linux-hardware.org/?probe=1784f93056) | Nov 18, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [8cf8f98a53](https://linux-hardware.org/?probe=8cf8f98a53) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [696ee320dd](https://linux-hardware.org/?probe=696ee320dd) | Nov 11, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [039315b907](https://linux-hardware.org/?probe=039315b907) | Nov 10, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [e290db920f](https://linux-hardware.org/?probe=e290db920f) | Nov 08, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [c04f0fcb02](https://linux-hardware.org/?probe=c04f0fcb02) | Nov 06, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [5010ca9e9a](https://linux-hardware.org/?probe=5010ca9e9a) | Nov 06, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| ASUSTek       | V241EA                      | All in one  | [ffb4ed2207](https://linux-hardware.org/?probe=ffb4ed2207) | Nov 02, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [0233ae7054](https://linux-hardware.org/?probe=0233ae7054) | Oct 31, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2ba5ae42bb](https://linux-hardware.org/?probe=2ba5ae42bb) | Oct 31, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [04c5f1689d](https://linux-hardware.org/?probe=04c5f1689d) | Oct 27, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [0f23350175](https://linux-hardware.org/?probe=0f23350175) | Oct 27, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [a56c0a6b4d](https://linux-hardware.org/?probe=a56c0a6b4d) | Oct 26, 2021 |
| Samsung       | R508                        | Notebook    | [89842bec44](https://linux-hardware.org/?probe=89842bec44) | Oct 25, 2021 |
| HP            | Notebook                    | Notebook    | [1963a09646](https://linux-hardware.org/?probe=1963a09646) | Oct 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4bc3faf49f](https://linux-hardware.org/?probe=4bc3faf49f) | Oct 24, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [8061e7314a](https://linux-hardware.org/?probe=8061e7314a) | Oct 23, 2021 |
| HP            | 86F0 11000                  | All in one  | [75738404ae](https://linux-hardware.org/?probe=75738404ae) | Oct 21, 2021 |
| ASUSTek       | K53BR                       | Notebook    | [af980dc491](https://linux-hardware.org/?probe=af980dc491) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N2000KRT    | Notebook    | [55daad7a3a](https://linux-hardware.org/?probe=55daad7a3a) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [1f4f861804](https://linux-hardware.org/?probe=1f4f861804) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [acb07e4c72](https://linux-hardware.org/?probe=acb07e4c72) | Oct 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f874da9f03](https://linux-hardware.org/?probe=f874da9f03) | Oct 12, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [9fd17a6579](https://linux-hardware.org/?probe=9fd17a6579) | Oct 09, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [9b4b3c9f77](https://linux-hardware.org/?probe=9b4b3c9f77) | Oct 09, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [b99c6d022e](https://linux-hardware.org/?probe=b99c6d022e) | Oct 05, 2021 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [0d6bbd5c75](https://linux-hardware.org/?probe=0d6bbd5c75) | Oct 05, 2021 |
| Acer          | Aspire A515-44G             | Notebook    | [264badf289](https://linux-hardware.org/?probe=264badf289) | Oct 01, 2021 |
| HP            | Pavilion dv4000 (PX306UA... | Notebook    | [fdc2b74a29](https://linux-hardware.org/?probe=fdc2b74a29) | Oct 01, 2021 |
| Lenovo        | ThinkPad T480s 20L8SB9Y0... | Notebook    | [75356ac5ee](https://linux-hardware.org/?probe=75356ac5ee) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e5838666c2](https://linux-hardware.org/?probe=e5838666c2) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b69288527f](https://linux-hardware.org/?probe=b69288527f) | Oct 01, 2021 |
| Intel         | H61M-S1                     | Desktop     | [ba0b4c102b](https://linux-hardware.org/?probe=ba0b4c102b) | Sep 30, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| HP            | 86F0 11000                  | All in one  | [d94d1dcab2](https://linux-hardware.org/?probe=d94d1dcab2) | Sep 29, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e8c44e9282](https://linux-hardware.org/?probe=e8c44e9282) | Sep 26, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [bea6762fb6](https://linux-hardware.org/?probe=bea6762fb6) | Sep 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [49a6459ecf](https://linux-hardware.org/?probe=49a6459ecf) | Sep 23, 2021 |
| HONOR         | HLYL-WXX9                   | Notebook    | [f21200b164](https://linux-hardware.org/?probe=f21200b164) | Sep 23, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [80b6244981](https://linux-hardware.org/?probe=80b6244981) | Sep 21, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [bc0974da01](https://linux-hardware.org/?probe=bc0974da01) | Sep 19, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9cf1061bcb](https://linux-hardware.org/?probe=9cf1061bcb) | Sep 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [84678f812f](https://linux-hardware.org/?probe=84678f812f) | Sep 18, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [f8bb575441](https://linux-hardware.org/?probe=f8bb575441) | Sep 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [a64387b07d](https://linux-hardware.org/?probe=a64387b07d) | Sep 15, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [01cd639b37](https://linux-hardware.org/?probe=01cd639b37) | Sep 11, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [04e9d9ef11](https://linux-hardware.org/?probe=04e9d9ef11) | Sep 10, 2021 |
| HP            | ProBook 4515s               | Notebook    | [f421481ba4](https://linux-hardware.org/?probe=f421481ba4) | Sep 09, 2021 |
| HP            | ProBook 4515s               | Notebook    | [308aea486b](https://linux-hardware.org/?probe=308aea486b) | Sep 09, 2021 |
| ASUSTek       | G71V                        | Notebook    | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [248b63572e](https://linux-hardware.org/?probe=248b63572e) | Sep 08, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [07db84c018](https://linux-hardware.org/?probe=07db84c018) | Sep 07, 2021 |
| Samsung       | R508                        | Notebook    | [9e358e751b](https://linux-hardware.org/?probe=9e358e751b) | Sep 06, 2021 |
| HP            | Compaq 610                  | Notebook    | [a8792baad7](https://linux-hardware.org/?probe=a8792baad7) | Sep 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [11fce4275a](https://linux-hardware.org/?probe=11fce4275a) | Sep 01, 2021 |
| ASUSTek       | K53BR                       | Notebook    | [989a6f27be](https://linux-hardware.org/?probe=989a6f27be) | Aug 29, 2021 |
| Biostar       | A960D+V3                    | Desktop     | [f65660cdbe](https://linux-hardware.org/?probe=f65660cdbe) | Aug 26, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [89dcb140f5](https://linux-hardware.org/?probe=89dcb140f5) | Aug 26, 2021 |
| Intel         | H61M-S1                     | Desktop     | [46407e3bfe](https://linux-hardware.org/?probe=46407e3bfe) | Aug 24, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7928c7e6e6](https://linux-hardware.org/?probe=7928c7e6e6) | Aug 23, 2021 |
| Acer          | Extensa 2511G               | Notebook    | [d74e3d1835](https://linux-hardware.org/?probe=d74e3d1835) | Aug 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [240d31631f](https://linux-hardware.org/?probe=240d31631f) | Aug 19, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6bcc5abfa7](https://linux-hardware.org/?probe=6bcc5abfa7) | Aug 18, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [735e9cba22](https://linux-hardware.org/?probe=735e9cba22) | Aug 18, 2021 |
| Biostar       | Hi-Fi A75S3                 | Desktop     | [f75bdb68fa](https://linux-hardware.org/?probe=f75bdb68fa) | Aug 14, 2021 |
| Acer          | Veriton N4660G              | Desktop     | [7ee989172f](https://linux-hardware.org/?probe=7ee989172f) | Aug 13, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [9b490356cb](https://linux-hardware.org/?probe=9b490356cb) | Aug 11, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [21914d4123](https://linux-hardware.org/?probe=21914d4123) | Aug 11, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [52a8d13536](https://linux-hardware.org/?probe=52a8d13536) | Aug 08, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b3dfe4bfe4](https://linux-hardware.org/?probe=b3dfe4bfe4) | Aug 07, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [11621d5877](https://linux-hardware.org/?probe=11621d5877) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [6e05bc86aa](https://linux-hardware.org/?probe=6e05bc86aa) | Aug 06, 2021 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [0fac51313a](https://linux-hardware.org/?probe=0fac51313a) | Aug 06, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [94d76843e6](https://linux-hardware.org/?probe=94d76843e6) | Aug 03, 2021 |
| Lenovo        | ThinkPad P50 20EQS33800     | Notebook    | [2e1468bf31](https://linux-hardware.org/?probe=2e1468bf31) | Aug 02, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [6d45e5794a](https://linux-hardware.org/?probe=6d45e5794a) | Jul 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c90b5a2e7d](https://linux-hardware.org/?probe=c90b5a2e7d) | Jul 28, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| Prestigio     | PSB141C03                   | Notebook    | [60fe58fa1b](https://linux-hardware.org/?probe=60fe58fa1b) | Jul 27, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [92c5d52e50](https://linux-hardware.org/?probe=92c5d52e50) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [960c966e4b](https://linux-hardware.org/?probe=960c966e4b) | Jul 24, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3006193ccc](https://linux-hardware.org/?probe=3006193ccc) | Jul 22, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [af87c52a43](https://linux-hardware.org/?probe=af87c52a43) | Jul 20, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ab8b0d224b](https://linux-hardware.org/?probe=ab8b0d224b) | Jul 16, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [30dd6fa596](https://linux-hardware.org/?probe=30dd6fa596) | Jul 14, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [ce3b5ecb17](https://linux-hardware.org/?probe=ce3b5ecb17) | Jul 13, 2021 |
| MSI           | MS-7369                     | Desktop     | [caf783ce91](https://linux-hardware.org/?probe=caf783ce91) | Jul 10, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [cda1d2d081](https://linux-hardware.org/?probe=cda1d2d081) | Jul 09, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [a9b1ac4bdb](https://linux-hardware.org/?probe=a9b1ac4bdb) | Jul 07, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [7e2f0e6a10](https://linux-hardware.org/?probe=7e2f0e6a10) | Jul 06, 2021 |
| Sony          | SVE1512N1RW                 | Notebook    | [9cfa353121](https://linux-hardware.org/?probe=9cfa353121) | Jul 05, 2021 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [09ee8c08c7](https://linux-hardware.org/?probe=09ee8c08c7) | Jul 05, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e807bd56bc](https://linux-hardware.org/?probe=e807bd56bc) | Jul 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8dd431f915](https://linux-hardware.org/?probe=8dd431f915) | Jul 03, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a0792e787d](https://linux-hardware.org/?probe=a0792e787d) | Jun 30, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [945132609d](https://linux-hardware.org/?probe=945132609d) | Jun 30, 2021 |
| Intel         | H61M-S1                     | Desktop     | [10ef09acce](https://linux-hardware.org/?probe=10ef09acce) | Jun 28, 2021 |
| Samsung       | RV413/RV513                 | Notebook    | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [48f732d759](https://linux-hardware.org/?probe=48f732d759) | Jun 23, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [b34ddd69c9](https://linux-hardware.org/?probe=b34ddd69c9) | Jun 21, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [7fe08a233a](https://linux-hardware.org/?probe=7fe08a233a) | Jun 20, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [073ee459eb](https://linux-hardware.org/?probe=073ee459eb) | Jun 16, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [f6436bedb8](https://linux-hardware.org/?probe=f6436bedb8) | Jun 16, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [ec0c189e56](https://linux-hardware.org/?probe=ec0c189e56) | Jun 15, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a1f4d070a3](https://linux-hardware.org/?probe=a1f4d070a3) | Jun 14, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0c5e09b00c](https://linux-hardware.org/?probe=0c5e09b00c) | Jun 14, 2021 |
| MSI           | MS-7369                     | Desktop     | [9852368309](https://linux-hardware.org/?probe=9852368309) | Jun 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [c2803c157e](https://linux-hardware.org/?probe=c2803c157e) | Jun 13, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [8380ef5fcb](https://linux-hardware.org/?probe=8380ef5fcb) | Jun 11, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [301f84c1e8](https://linux-hardware.org/?probe=301f84c1e8) | Jun 09, 2021 |
| HP            | Pavilion 15                 | Notebook    | [8c0f52c64d](https://linux-hardware.org/?probe=8c0f52c64d) | Jun 08, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5e75af2ba4](https://linux-hardware.org/?probe=5e75af2ba4) | May 31, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [8bdfad6e5a](https://linux-hardware.org/?probe=8bdfad6e5a) | May 27, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8e85b5f3cf](https://linux-hardware.org/?probe=8e85b5f3cf) | May 26, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8ffe17b548](https://linux-hardware.org/?probe=8ffe17b548) | May 24, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| ASUSTek       | X541UJ                      | Notebook    | [22f4d0228f](https://linux-hardware.org/?probe=22f4d0228f) | May 16, 2021 |
| Timi          | TM1703                      | Notebook    | [a8c47ad7f6](https://linux-hardware.org/?probe=a8c47ad7f6) | May 15, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| ECS           | Livermore8                  | Desktop     | [fba5a0dbb7](https://linux-hardware.org/?probe=fba5a0dbb7) | May 12, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [3eefcf4b58](https://linux-hardware.org/?probe=3eefcf4b58) | May 11, 2021 |
| Lenovo        | Z710 20250                  | Notebook    | [f3d7663214](https://linux-hardware.org/?probe=f3d7663214) | May 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [06af60abdc](https://linux-hardware.org/?probe=06af60abdc) | May 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [b71c62e752](https://linux-hardware.org/?probe=b71c62e752) | May 09, 2021 |
| Biostar       | H81MLC                      | Desktop     | [d8da680e51](https://linux-hardware.org/?probe=d8da680e51) | May 08, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [ec9321bd41](https://linux-hardware.org/?probe=ec9321bd41) | May 08, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [06558373ef](https://linux-hardware.org/?probe=06558373ef) | May 07, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [46872b4b26](https://linux-hardware.org/?probe=46872b4b26) | May 02, 2021 |
| HP            | ProBook 4525s               | Notebook    | [809516ad9a](https://linux-hardware.org/?probe=809516ad9a) | May 01, 2021 |
| Dell          | 0CRH6C A02                  | Desktop     | [69cbbfec14](https://linux-hardware.org/?probe=69cbbfec14) | Apr 30, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [fb5b8d0021](https://linux-hardware.org/?probe=fb5b8d0021) | Apr 29, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [7ec9efef18](https://linux-hardware.org/?probe=7ec9efef18) | Apr 29, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [3f2270faad](https://linux-hardware.org/?probe=3f2270faad) | Apr 26, 2021 |
| Intel         | H61M-S1                     | Desktop     | [36129cbfda](https://linux-hardware.org/?probe=36129cbfda) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [644dd10952](https://linux-hardware.org/?probe=644dd10952) | Apr 22, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [1832412dab](https://linux-hardware.org/?probe=1832412dab) | Apr 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b60d916c33](https://linux-hardware.org/?probe=b60d916c33) | Apr 19, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [309d8603b2](https://linux-hardware.org/?probe=309d8603b2) | Apr 15, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [d945be0db8](https://linux-hardware.org/?probe=d945be0db8) | Apr 15, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [d6c3e7cb89](https://linux-hardware.org/?probe=d6c3e7cb89) | Apr 15, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [1e11286470](https://linux-hardware.org/?probe=1e11286470) | Apr 15, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [099a3d1264](https://linux-hardware.org/?probe=099a3d1264) | Apr 15, 2021 |
| HP            | ProBook 445 G6              | Notebook    | [520083c016](https://linux-hardware.org/?probe=520083c016) | Apr 14, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [15bd22b48d](https://linux-hardware.org/?probe=15bd22b48d) | Apr 11, 2021 |
| HP            | 304Ah                       | Desktop     | [66228ce4df](https://linux-hardware.org/?probe=66228ce4df) | Apr 09, 2021 |
| HP            | 304Ah                       | Desktop     | [5d8e8d559a](https://linux-hardware.org/?probe=5d8e8d559a) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8de936a2ca](https://linux-hardware.org/?probe=8de936a2ca) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ebd6174247](https://linux-hardware.org/?probe=ebd6174247) | Apr 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [0362943e9e](https://linux-hardware.org/?probe=0362943e9e) | Apr 02, 2021 |
| Lenovo        | ThinkPad X230 23252QG       | Notebook    | [a3e8c4ecb4](https://linux-hardware.org/?probe=a3e8c4ecb4) | Mar 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [3228126df8](https://linux-hardware.org/?probe=3228126df8) | Mar 29, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [1dc07212db](https://linux-hardware.org/?probe=1dc07212db) | Mar 28, 2021 |
| Gigabyte      | GA-770T-D3L                 | Desktop     | [eeeb3a5b5d](https://linux-hardware.org/?probe=eeeb3a5b5d) | Mar 27, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [35964432d7](https://linux-hardware.org/?probe=35964432d7) | Mar 26, 2021 |
| Lenovo        | ThinkPad T420 4236GH6       | Notebook    | [102d74838a](https://linux-hardware.org/?probe=102d74838a) | Mar 25, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [973d60c63e](https://linux-hardware.org/?probe=973d60c63e) | Mar 24, 2021 |
| HP            | ProBook 4525s               | Notebook    | [e4df2fd0b0](https://linux-hardware.org/?probe=e4df2fd0b0) | Mar 24, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [02a403c967](https://linux-hardware.org/?probe=02a403c967) | Mar 24, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | Notebook    | [3157cd3bfe](https://linux-hardware.org/?probe=3157cd3bfe) | Mar 23, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | Notebook    | [97df6a4a9a](https://linux-hardware.org/?probe=97df6a4a9a) | Mar 23, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d2e63cfaa6](https://linux-hardware.org/?probe=d2e63cfaa6) | Mar 22, 2021 |
| Dell          | 0P4T42 A01                  | All in one  | [2f14bf6c71](https://linux-hardware.org/?probe=2f14bf6c71) | Mar 22, 2021 |
| ASUSTek       | P5B                         | Desktop     | [a24c9c6d6a](https://linux-hardware.org/?probe=a24c9c6d6a) | Mar 22, 2021 |
| Gigabyte      | P55A-UD3                    | Desktop     | [c947af2b99](https://linux-hardware.org/?probe=c947af2b99) | Mar 21, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [c6506a0289](https://linux-hardware.org/?probe=c6506a0289) | Mar 21, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [18d693f712](https://linux-hardware.org/?probe=18d693f712) | Mar 21, 2021 |
| ASUSTek       | N752VX                      | Notebook    | [48cb617015](https://linux-hardware.org/?probe=48cb617015) | Mar 20, 2021 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [3e2336037f](https://linux-hardware.org/?probe=3e2336037f) | Mar 20, 2021 |
| Acer          | Aspire 5551G                | Notebook    | [1002c3efd0](https://linux-hardware.org/?probe=1002c3efd0) | Mar 19, 2021 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [c63de512e5](https://linux-hardware.org/?probe=c63de512e5) | Mar 18, 2021 |
| HP            | 250 G1                      | Notebook    | [7b14b4e7e5](https://linux-hardware.org/?probe=7b14b4e7e5) | Mar 18, 2021 |
| HP            | ProBook 4525s               | Notebook    | [f9830feb98](https://linux-hardware.org/?probe=f9830feb98) | Mar 17, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [d2dde464de](https://linux-hardware.org/?probe=d2dde464de) | Mar 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [12eebe7515](https://linux-hardware.org/?probe=12eebe7515) | Mar 17, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [e688898ed8](https://linux-hardware.org/?probe=e688898ed8) | Mar 17, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [8e8d411ccb](https://linux-hardware.org/?probe=8e8d411ccb) | Mar 17, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [658c4e0d17](https://linux-hardware.org/?probe=658c4e0d17) | Mar 17, 2021 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [1b6cfd046e](https://linux-hardware.org/?probe=1b6cfd046e) | Mar 17, 2021 |
| Prestigio     | PSB141C03                   | Notebook    | [82f601055a](https://linux-hardware.org/?probe=82f601055a) | Mar 17, 2021 |
| ASRock        | 990FX Extreme4              | Desktop     | [d1536bcdfa](https://linux-hardware.org/?probe=d1536bcdfa) | Mar 17, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [863c6c5d68](https://linux-hardware.org/?probe=863c6c5d68) | Mar 17, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [51bf91aae7](https://linux-hardware.org/?probe=51bf91aae7) | Mar 14, 2021 |
| HP            | Mini 210-4000               | Notebook    | [9301f9c8ef](https://linux-hardware.org/?probe=9301f9c8ef) | Mar 12, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [72f398fcff](https://linux-hardware.org/?probe=72f398fcff) | Mar 11, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [83f50b266f](https://linux-hardware.org/?probe=83f50b266f) | Mar 11, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [ed293423f3](https://linux-hardware.org/?probe=ed293423f3) | Mar 11, 2021 |
| HP            | ProBook 4525s               | Notebook    | [912c2f075f](https://linux-hardware.org/?probe=912c2f075f) | Mar 09, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [f63d1b8f0b](https://linux-hardware.org/?probe=f63d1b8f0b) | Mar 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [28a8889148](https://linux-hardware.org/?probe=28a8889148) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1df473b11e](https://linux-hardware.org/?probe=1df473b11e) | Mar 03, 2021 |
| Dell          | System XPS L702X            | Notebook    | [1cce147fd2](https://linux-hardware.org/?probe=1cce147fd2) | Feb 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [902d3d474e](https://linux-hardware.org/?probe=902d3d474e) | Feb 25, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [390003cc95](https://linux-hardware.org/?probe=390003cc95) | Feb 24, 2021 |
| MSI           | MS-7250                     | Desktop     | [bd7bbadaad](https://linux-hardware.org/?probe=bd7bbadaad) | Feb 23, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [77748ba0e4](https://linux-hardware.org/?probe=77748ba0e4) | Feb 22, 2021 |
| ASUSTek       | K50C                        | Notebook    | [e6cc5c82bf](https://linux-hardware.org/?probe=e6cc5c82bf) | Feb 21, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [8d2b36f7c1](https://linux-hardware.org/?probe=8d2b36f7c1) | Feb 20, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [80cea1a03a](https://linux-hardware.org/?probe=80cea1a03a) | Feb 19, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CD00A... | Notebook    | [0f4f85b4c1](https://linux-hardware.org/?probe=0f4f85b4c1) | Feb 19, 2021 |
| Packard Be... | EasyNote TM86               | Notebook    | [f548aa653a](https://linux-hardware.org/?probe=f548aa653a) | Feb 18, 2021 |
| Acer          | Extensa 5230                | Notebook    | [b128a06266](https://linux-hardware.org/?probe=b128a06266) | Feb 17, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [1a52fb16f9](https://linux-hardware.org/?probe=1a52fb16f9) | Feb 16, 2021 |
| Dell          | Inspiron 5748               | Notebook    | [8bb7ec1035](https://linux-hardware.org/?probe=8bb7ec1035) | Feb 15, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [c5877ecd52](https://linux-hardware.org/?probe=c5877ecd52) | Feb 14, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [c500f1eff8](https://linux-hardware.org/?probe=c500f1eff8) | Feb 14, 2021 |
| Gigabyte      | H77-DS3H                    | Desktop     | [76e29e229d](https://linux-hardware.org/?probe=76e29e229d) | Feb 13, 2021 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [6262cc3afd](https://linux-hardware.org/?probe=6262cc3afd) | Feb 13, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [6969353956](https://linux-hardware.org/?probe=6969353956) | Feb 13, 2021 |
| ASUSTek       | X540NV                      | Notebook    | [3a64cfa43e](https://linux-hardware.org/?probe=3a64cfa43e) | Feb 13, 2021 |
| HP            | Mini 210-4000               | Notebook    | [966136f01f](https://linux-hardware.org/?probe=966136f01f) | Feb 13, 2021 |
| ASUSTek       | X540NV                      | Notebook    | [2e31ed1ec6](https://linux-hardware.org/?probe=2e31ed1ec6) | Feb 13, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [bbc60c2820](https://linux-hardware.org/?probe=bbc60c2820) | Feb 13, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8f8fd2975a](https://linux-hardware.org/?probe=8f8fd2975a) | Feb 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [440af1645f](https://linux-hardware.org/?probe=440af1645f) | Feb 13, 2021 |
| Gigabyte      | H77-DS3H                    | Desktop     | [02fd7c81f6](https://linux-hardware.org/?probe=02fd7c81f6) | Feb 11, 2021 |
| Acer          | Extensa 7630EZ              | Notebook    | [9a0378eb4d](https://linux-hardware.org/?probe=9a0378eb4d) | Feb 11, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [bbd0961627](https://linux-hardware.org/?probe=bbd0961627) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [6487d4bd7c](https://linux-hardware.org/?probe=6487d4bd7c) | Feb 09, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8c35b025b2](https://linux-hardware.org/?probe=8c35b025b2) | Feb 08, 2021 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [cbd3e60242](https://linux-hardware.org/?probe=cbd3e60242) | Feb 07, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [d9218caa35](https://linux-hardware.org/?probe=d9218caa35) | Feb 05, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [f4611ac89e](https://linux-hardware.org/?probe=f4611ac89e) | Feb 04, 2021 |
| HP            | 635                         | Notebook    | [e83d58e706](https://linux-hardware.org/?probe=e83d58e706) | Feb 03, 2021 |
| Acer          | Aspire 5551G                | Notebook    | [811535132b](https://linux-hardware.org/?probe=811535132b) | Feb 02, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [e86c3d781d](https://linux-hardware.org/?probe=e86c3d781d) | Jan 31, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [6f78493e97](https://linux-hardware.org/?probe=6f78493e97) | Jan 29, 2021 |
| Lenovo        | ThinkPad T410 2537V28       | Notebook    | [126c75190e](https://linux-hardware.org/?probe=126c75190e) | Jan 22, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [e04d0e066e](https://linux-hardware.org/?probe=e04d0e066e) | Jan 22, 2021 |
| HP            | 255 G2                      | Notebook    | [3ebc0a9b9b](https://linux-hardware.org/?probe=3ebc0a9b9b) | Jan 21, 2021 |
| MSI           | 760GM-P33                   | Desktop     | [f7dbe6391b](https://linux-hardware.org/?probe=f7dbe6391b) | Jan 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14022d5350](https://linux-hardware.org/?probe=14022d5350) | Jan 20, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [48644938e9](https://linux-hardware.org/?probe=48644938e9) | Jan 17, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [b3bfbdace0](https://linux-hardware.org/?probe=b3bfbdace0) | Jan 10, 2021 |
| ASUSTek       | N550JK                      | Notebook    | [f12a646f8b](https://linux-hardware.org/?probe=f12a646f8b) | Jan 09, 2021 |
| Acer          | Extensa 2511G               | Notebook    | [ca3628282a](https://linux-hardware.org/?probe=ca3628282a) | Jan 06, 2021 |
| HP            | Mini 5102                   | Notebook    | [76f0b2193f](https://linux-hardware.org/?probe=76f0b2193f) | Jan 06, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [76f271acf1](https://linux-hardware.org/?probe=76f271acf1) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [b005d0780d](https://linux-hardware.org/?probe=b005d0780d) | Jan 04, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [7c04f61d39](https://linux-hardware.org/?probe=7c04f61d39) | Jan 04, 2021 |
| Samsung       | SR58P                       | Notebook    | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| MSI           | 760GM-P33                   | Desktop     | [9af10be990](https://linux-hardware.org/?probe=9af10be990) | Jan 03, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [f49ba1df9c](https://linux-hardware.org/?probe=f49ba1df9c) | Jan 01, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [997fd6a726](https://linux-hardware.org/?probe=997fd6a726) | Dec 30, 2020 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [8eb79a3a10](https://linux-hardware.org/?probe=8eb79a3a10) | Dec 29, 2020 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [1b0941ddec](https://linux-hardware.org/?probe=1b0941ddec) | Dec 26, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [c560d2aa9b](https://linux-hardware.org/?probe=c560d2aa9b) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [8286c6ca5c](https://linux-hardware.org/?probe=8286c6ca5c) | Dec 23, 2020 |
| Gigabyte      | P35-S3G                     | Desktop     | [be95d225fe](https://linux-hardware.org/?probe=be95d225fe) | Dec 22, 2020 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [cf0c42c323](https://linux-hardware.org/?probe=cf0c42c323) | Dec 18, 2020 |
| HP            | 81BA                        | All in one  | [00a2be4ed1](https://linux-hardware.org/?probe=00a2be4ed1) | Dec 18, 2020 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [43c86b0f1e](https://linux-hardware.org/?probe=43c86b0f1e) | Dec 18, 2020 |
| HP            | 81BA                        | All in one  | [1c8a356387](https://linux-hardware.org/?probe=1c8a356387) | Dec 17, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [f4ae75d77c](https://linux-hardware.org/?probe=f4ae75d77c) | Dec 16, 2020 |
| Dell          | Inspiron 5748               | Notebook    | [091c74353b](https://linux-hardware.org/?probe=091c74353b) | Dec 16, 2020 |
| Lenovo        | B5400 20278                 | Notebook    | [56ea17c80b](https://linux-hardware.org/?probe=56ea17c80b) | Dec 15, 2020 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [5e1b23e45c](https://linux-hardware.org/?probe=5e1b23e45c) | Dec 14, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [b987e4cc7c](https://linux-hardware.org/?probe=b987e4cc7c) | Dec 11, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [f6e40ea1a0](https://linux-hardware.org/?probe=f6e40ea1a0) | Dec 11, 2020 |
| Samsung       | R530/R730                   | Notebook    | [eaf1fed190](https://linux-hardware.org/?probe=eaf1fed190) | Dec 11, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d0d9126db4](https://linux-hardware.org/?probe=d0d9126db4) | Dec 08, 2020 |
| Gigabyte      | H81M-S2H                    | Desktop     | [c6b4560c3e](https://linux-hardware.org/?probe=c6b4560c3e) | Dec 07, 2020 |
| Prestigio     | PSB141C03                   | Notebook    | [4087902d18](https://linux-hardware.org/?probe=4087902d18) | Dec 07, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [a566f76ca4](https://linux-hardware.org/?probe=a566f76ca4) | Dec 07, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [27a4e636f6](https://linux-hardware.org/?probe=27a4e636f6) | Dec 02, 2020 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [54886a9cc0](https://linux-hardware.org/?probe=54886a9cc0) | Nov 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [91ff5fdd53](https://linux-hardware.org/?probe=91ff5fdd53) | Nov 28, 2020 |
| ASUSTek       | P5K WS                      | Desktop     | [89a2e1b515](https://linux-hardware.org/?probe=89a2e1b515) | Nov 28, 2020 |
| ASUSTek       | K52N                        | Notebook    | [94f1b7362b](https://linux-hardware.org/?probe=94f1b7362b) | Nov 25, 2020 |
| Acer          | Aspire E1-530               | Notebook    | [e343493113](https://linux-hardware.org/?probe=e343493113) | Nov 25, 2020 |
| Lenovo        | ThinkPad T470 20HD005QRT    | Notebook    | [b265ff82a7](https://linux-hardware.org/?probe=b265ff82a7) | Nov 21, 2020 |
| Lenovo        | ThinkPad E15 20RD0014RT     | Notebook    | [81de71766f](https://linux-hardware.org/?probe=81de71766f) | Nov 21, 2020 |
| Prestigio     | PSB141C02                   | Notebook    | [08aa1ee2ff](https://linux-hardware.org/?probe=08aa1ee2ff) | Nov 20, 2020 |
| ASUSTek       | X541UAK                     | Notebook    | [bada67f585](https://linux-hardware.org/?probe=bada67f585) | Nov 20, 2020 |
| Gigabyte      | H81M-S2H                    | Desktop     | [05314304a4](https://linux-hardware.org/?probe=05314304a4) | Nov 19, 2020 |
| ASUSTek       | V200IB                      | Desktop     | [910d5a3bfd](https://linux-hardware.org/?probe=910d5a3bfd) | Nov 19, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [9687208571](https://linux-hardware.org/?probe=9687208571) | Nov 19, 2020 |
| ASUSTek       | X541UAK                     | Notebook    | [c914110be9](https://linux-hardware.org/?probe=c914110be9) | Nov 19, 2020 |
| Acer          | Aspire E1-532G              | Notebook    | [dd90b2f3e2](https://linux-hardware.org/?probe=dd90b2f3e2) | Nov 18, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [6abee99a84](https://linux-hardware.org/?probe=6abee99a84) | Nov 18, 2020 |
| Gigabyte      | H81M-S2H                    | Desktop     | [72f585d3fd](https://linux-hardware.org/?probe=72f585d3fd) | Nov 18, 2020 |
| ASUSTek       | V200IB                      | All in one  | [e20ac63341](https://linux-hardware.org/?probe=e20ac63341) | Nov 18, 2020 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [f8de57d305](https://linux-hardware.org/?probe=f8de57d305) | Nov 16, 2020 |
| Samsung       | R508                        | Notebook    | [937a0199e0](https://linux-hardware.org/?probe=937a0199e0) | Nov 16, 2020 |
| ASUSTek       | K52N                        | Notebook    | [a96cd62a24](https://linux-hardware.org/?probe=a96cd62a24) | Nov 14, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [225c61e941](https://linux-hardware.org/?probe=225c61e941) | Nov 13, 2020 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [4eefad2a8b](https://linux-hardware.org/?probe=4eefad2a8b) | Nov 13, 2020 |
| Dell          | Inspiron 5521               | Notebook    | [1080310f19](https://linux-hardware.org/?probe=1080310f19) | Nov 11, 2020 |
| Intel         | SharkBay Platform           | Notebook    | [21647cb222](https://linux-hardware.org/?probe=21647cb222) | Nov 09, 2020 |
| Unknown       | Unknown                     | Notebook    | [091af6961a](https://linux-hardware.org/?probe=091af6961a) | Nov 08, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [5da1ec78a0](https://linux-hardware.org/?probe=5da1ec78a0) | Nov 07, 2020 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [df41815a21](https://linux-hardware.org/?probe=df41815a21) | Nov 06, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | Notebook    | [412e6eca38](https://linux-hardware.org/?probe=412e6eca38) | Nov 05, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | Notebook    | [6fb42db6e5](https://linux-hardware.org/?probe=6fb42db6e5) | Nov 05, 2020 |
| ASRock        | Z370M Pro4                  | Desktop     | [85e45a95e0](https://linux-hardware.org/?probe=85e45a95e0) | Nov 04, 2020 |
| Intel         | SharkBay Platform           | Notebook    | [dcd49fdf3b](https://linux-hardware.org/?probe=dcd49fdf3b) | Nov 04, 2020 |
| Samsung       | R508                        | Notebook    | [7915a99545](https://linux-hardware.org/?probe=7915a99545) | Nov 03, 2020 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [45666ff7af](https://linux-hardware.org/?probe=45666ff7af) | Nov 01, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [830c1ed47a](https://linux-hardware.org/?probe=830c1ed47a) | Nov 01, 2020 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f5328a95d5](https://linux-hardware.org/?probe=f5328a95d5) | Oct 31, 2020 |
| Dell          | Inspiron 15 5501            | Notebook    | [557aca340e](https://linux-hardware.org/?probe=557aca340e) | Oct 27, 2020 |
| Olimex        | A20-OLinuXino-LIME2         | Soc         | [5a543f3e3e](https://linux-hardware.org/?probe=5a543f3e3e) | Oct 26, 2020 |
| MSI           | 760GM-P33                   | Desktop     | [c611e5bbe5](https://linux-hardware.org/?probe=c611e5bbe5) | Oct 26, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7ae3293c6d](https://linux-hardware.org/?probe=7ae3293c6d) | Oct 26, 2020 |
| Timi          | TM1701                      | Notebook    | [36446e6594](https://linux-hardware.org/?probe=36446e6594) | Oct 26, 2020 |
| Dell          | Inspiron 15 5501            | Notebook    | [92fa11d82d](https://linux-hardware.org/?probe=92fa11d82d) | Oct 25, 2020 |
| Dell          | Inspiron 15 5501            | Notebook    | [6a18afe215](https://linux-hardware.org/?probe=6a18afe215) | Oct 25, 2020 |
| ASUSTek       | H81M-E                      | Desktop     | [e149fb7dc2](https://linux-hardware.org/?probe=e149fb7dc2) | Oct 23, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [b0e3f9ed28](https://linux-hardware.org/?probe=b0e3f9ed28) | Oct 21, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [f21f5a008c](https://linux-hardware.org/?probe=f21f5a008c) | Oct 21, 2020 |
| Gigabyte      | Z390 D                      | Desktop     | [1610651aa5](https://linux-hardware.org/?probe=1610651aa5) | Oct 21, 2020 |
| HP            | 250 G2                      | Notebook    | [164b391add](https://linux-hardware.org/?probe=164b391add) | Oct 20, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [50cb6d53ef](https://linux-hardware.org/?probe=50cb6d53ef) | Oct 18, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [0e1b75fc55](https://linux-hardware.org/?probe=0e1b75fc55) | Oct 18, 2020 |
| Acer          | Unknown                     | Notebook    | [5dc51268a1](https://linux-hardware.org/?probe=5dc51268a1) | Oct 17, 2020 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [2fa1f3048b](https://linux-hardware.org/?probe=2fa1f3048b) | Oct 13, 2020 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [ee0649427b](https://linux-hardware.org/?probe=ee0649427b) | Oct 12, 2020 |
| Prestigio     | PSB141C03                   | Notebook    | [eb6b709b25](https://linux-hardware.org/?probe=eb6b709b25) | Oct 12, 2020 |
| Lenovo        | ThinkPad T400 7417CTO       | Notebook    | [41f5d8bbb1](https://linux-hardware.org/?probe=41f5d8bbb1) | Oct 12, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [479a1ad655](https://linux-hardware.org/?probe=479a1ad655) | Oct 11, 2020 |
| MSI           | MS-7250                     | Desktop     | [c4ef765de1](https://linux-hardware.org/?probe=c4ef765de1) | Oct 10, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [eefad2dd0f](https://linux-hardware.org/?probe=eefad2dd0f) | Oct 10, 2020 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [1d6ca8e5fc](https://linux-hardware.org/?probe=1d6ca8e5fc) | Oct 09, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b0244dd7f4](https://linux-hardware.org/?probe=b0244dd7f4) | Oct 08, 2020 |
| ASUSTek       | H61M-K                      | Desktop     | [f813fe20d2](https://linux-hardware.org/?probe=f813fe20d2) | Oct 04, 2020 |
| Dell          | G5 5587                     | Notebook    | [7ec299e574](https://linux-hardware.org/?probe=7ec299e574) | Oct 03, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [4308201e9f](https://linux-hardware.org/?probe=4308201e9f) | Sep 28, 2020 |
| ASRock        | 970 Pro3                    | Desktop     | [c4459c622c](https://linux-hardware.org/?probe=c4459c622c) | Sep 27, 2020 |
| Samsung       | R518                        | Notebook    | [c4db2214cd](https://linux-hardware.org/?probe=c4db2214cd) | Sep 27, 2020 |
| Timi          | TM1709                      | Notebook    | [9d4bd50d80](https://linux-hardware.org/?probe=9d4bd50d80) | Sep 25, 2020 |
| HP            | 250 G2                      | Notebook    | [0721c128e6](https://linux-hardware.org/?probe=0721c128e6) | Sep 22, 2020 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [271a7bcbeb](https://linux-hardware.org/?probe=271a7bcbeb) | Sep 19, 2020 |
| ASUSTek       | P5KPL-C                     | Desktop     | [6812da21fd](https://linux-hardware.org/?probe=6812da21fd) | Sep 15, 2020 |
| HP            | 304Ah                       | Desktop     | [5acd57b9db](https://linux-hardware.org/?probe=5acd57b9db) | Sep 15, 2020 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [586f647e41](https://linux-hardware.org/?probe=586f647e41) | Sep 13, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [52a401fb4d](https://linux-hardware.org/?probe=52a401fb4d) | Sep 08, 2020 |
| ASRock        | FM2A75M-DGS                 | Desktop     | [a827ce3df1](https://linux-hardware.org/?probe=a827ce3df1) | Sep 02, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [41ed89087e](https://linux-hardware.org/?probe=41ed89087e) | Aug 31, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ed88384ae9](https://linux-hardware.org/?probe=ed88384ae9) | Aug 31, 2020 |
| MSI           | PS42 Modern 8RA             | Notebook    | [ab71a04043](https://linux-hardware.org/?probe=ab71a04043) | Aug 29, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [22adb53a27](https://linux-hardware.org/?probe=22adb53a27) | Aug 29, 2020 |
| Dell          | Precision 7540              | Notebook    | [8e97d27134](https://linux-hardware.org/?probe=8e97d27134) | Aug 27, 2020 |
| ASUSTek       | U36SG                       | Notebook    | [103ce98981](https://linux-hardware.org/?probe=103ce98981) | Aug 27, 2020 |
| ASRock        | H61M-HVS                    | Desktop     | [4052b1ff8b](https://linux-hardware.org/?probe=4052b1ff8b) | Aug 25, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [aaae1d3e78](https://linux-hardware.org/?probe=aaae1d3e78) | Aug 24, 2020 |
| Dell          | Vostro 5490                 | Notebook    | [873e3c07c7](https://linux-hardware.org/?probe=873e3c07c7) | Aug 24, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a7b737f065](https://linux-hardware.org/?probe=a7b737f065) | Aug 23, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [494bb32560](https://linux-hardware.org/?probe=494bb32560) | Aug 23, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [9c05eb6ed3](https://linux-hardware.org/?probe=9c05eb6ed3) | Aug 20, 2020 |
| ASRock        | 990FX Extreme4              | Desktop     | [9d89158c0c](https://linux-hardware.org/?probe=9d89158c0c) | Aug 19, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [42cfca7021](https://linux-hardware.org/?probe=42cfca7021) | Aug 14, 2020 |
| Acer          | Aspire 4810T                | Notebook    | [5ff79d2a64](https://linux-hardware.org/?probe=5ff79d2a64) | Aug 09, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [16796af2c3](https://linux-hardware.org/?probe=16796af2c3) | Aug 06, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [6ca9ef29fc](https://linux-hardware.org/?probe=6ca9ef29fc) | Aug 02, 2020 |
| ASUSTek       | P8H61 R2.0                  | Desktop     | [b9790bef81](https://linux-hardware.org/?probe=b9790bef81) | Aug 02, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [9b0eb8f018](https://linux-hardware.org/?probe=9b0eb8f018) | Aug 01, 2020 |
| Timi          | TM1701                      | Notebook    | [71882c9121](https://linux-hardware.org/?probe=71882c9121) | Jul 31, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [d38b29e9f6](https://linux-hardware.org/?probe=d38b29e9f6) | Jul 29, 2020 |
| ASRock        | Z77 Extreme4-M              | Desktop     | [8d5ce15006](https://linux-hardware.org/?probe=8d5ce15006) | Jul 29, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [b5e0ef963b](https://linux-hardware.org/?probe=b5e0ef963b) | Jul 26, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [def2e542ec](https://linux-hardware.org/?probe=def2e542ec) | Jul 25, 2020 |
| ASUSTek       | P8H77-V                     | Desktop     | [ad01a90f9c](https://linux-hardware.org/?probe=ad01a90f9c) | Jul 23, 2020 |
| Timi          | TM1701                      | Notebook    | [024ed71324](https://linux-hardware.org/?probe=024ed71324) | Jul 22, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [791afa1495](https://linux-hardware.org/?probe=791afa1495) | Jul 16, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [220af5d9fe](https://linux-hardware.org/?probe=220af5d9fe) | Jul 15, 2020 |
| Acer          | Aspire E1-731               | Notebook    | [e055f89ff6](https://linux-hardware.org/?probe=e055f89ff6) | Jul 15, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [acd59fc735](https://linux-hardware.org/?probe=acd59fc735) | Jul 15, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [744a29218a](https://linux-hardware.org/?probe=744a29218a) | Jul 09, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [986a151279](https://linux-hardware.org/?probe=986a151279) | Jul 09, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [322ef5e555](https://linux-hardware.org/?probe=322ef5e555) | Jul 06, 2020 |
| HP            | ProBook 445 G6              | Notebook    | [e82b679ba1](https://linux-hardware.org/?probe=e82b679ba1) | Jul 05, 2020 |
| eMachines     | eME728                      | Notebook    | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| ASUSTek       | X705UQR                     | Notebook    | [caebcd4a78](https://linux-hardware.org/?probe=caebcd4a78) | Jul 03, 2020 |
| Intel         | Braswell Platform           | Tablet      | [009bee9446](https://linux-hardware.org/?probe=009bee9446) | Jul 01, 2020 |
| Intel         | Braswell Platform           | Tablet      | [00c847073c](https://linux-hardware.org/?probe=00c847073c) | Jul 01, 2020 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [a6dcbcadc4](https://linux-hardware.org/?probe=a6dcbcadc4) | Jun 30, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [0e0fe8368c](https://linux-hardware.org/?probe=0e0fe8368c) | Jun 30, 2020 |
| HP            | Stream x360 Convertible ... | Convertible | [95bded4004](https://linux-hardware.org/?probe=95bded4004) | Jun 29, 2020 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [df5777de6d](https://linux-hardware.org/?probe=df5777de6d) | Jun 29, 2020 |
| LG Electro... | R510                        | Notebook    | [51967b227c](https://linux-hardware.org/?probe=51967b227c) | Jun 29, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [b439507f1a](https://linux-hardware.org/?probe=b439507f1a) | Jun 25, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [4d3573e05d](https://linux-hardware.org/?probe=4d3573e05d) | Jun 18, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [31fcf823d4](https://linux-hardware.org/?probe=31fcf823d4) | Jun 18, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [566a257192](https://linux-hardware.org/?probe=566a257192) | Jun 07, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [59c6b9d06f](https://linux-hardware.org/?probe=59c6b9d06f) | Jun 06, 2020 |
| ASUSTek       | X540NV                      | Notebook    | [f1a595ed8a](https://linux-hardware.org/?probe=f1a595ed8a) | Jun 05, 2020 |
| ASUSTek       | X541UJ                      | Notebook    | [4116c24ad8](https://linux-hardware.org/?probe=4116c24ad8) | Jun 03, 2020 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [53eafad041](https://linux-hardware.org/?probe=53eafad041) | Jun 02, 2020 |
| HP            | ProBook 4740s               | Notebook    | [bac1c80c34](https://linux-hardware.org/?probe=bac1c80c34) | Jun 02, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [b73508569c](https://linux-hardware.org/?probe=b73508569c) | May 30, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [178a726d73](https://linux-hardware.org/?probe=178a726d73) | May 28, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [dbfbd4b70e](https://linux-hardware.org/?probe=dbfbd4b70e) | May 28, 2020 |
| ASUSTek       | S551LB                      | Notebook    | [4aed54f228](https://linux-hardware.org/?probe=4aed54f228) | May 28, 2020 |
| HP            | 255 G2                      | Notebook    | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Acer          | Aspire VN7-592G             | Notebook    | [aa51c338b2](https://linux-hardware.org/?probe=aa51c338b2) | May 26, 2020 |
| HP            | Notebook                    | Notebook    | [672d0acfa1](https://linux-hardware.org/?probe=672d0acfa1) | May 26, 2020 |
| HP            | Notebook                    | Notebook    | [1fa50923d3](https://linux-hardware.org/?probe=1fa50923d3) | May 26, 2020 |
| ASRock        | P43D1600Twins-1394          | Desktop     | [9eb0959f24](https://linux-hardware.org/?probe=9eb0959f24) | May 25, 2020 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [ed7fe704dd](https://linux-hardware.org/?probe=ed7fe704dd) | May 25, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [670301a3f3](https://linux-hardware.org/?probe=670301a3f3) | May 25, 2020 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [f27378d43f](https://linux-hardware.org/?probe=f27378d43f) | May 25, 2020 |
| Acer          | AOA150                      | Notebook    | [4879ee6a95](https://linux-hardware.org/?probe=4879ee6a95) | May 24, 2020 |
| Gigabyte      | P55M-UD4                    | Desktop     | [cb5f5644c1](https://linux-hardware.org/?probe=cb5f5644c1) | May 21, 2020 |
| ASRock        | Z77 Extreme3                | Desktop     | [46d7fb23b0](https://linux-hardware.org/?probe=46d7fb23b0) | May 21, 2020 |
| Digma         | CITI 1804 CS1069EW          | Tablet      | [ea033fde6a](https://linux-hardware.org/?probe=ea033fde6a) | May 15, 2020 |
| Prestigio     | Multipad Visconte V         | Notebook    | [d3f3e2e2b4](https://linux-hardware.org/?probe=d3f3e2e2b4) | May 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e82eb79af2](https://linux-hardware.org/?probe=e82eb79af2) | May 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [06d027143f](https://linux-hardware.org/?probe=06d027143f) | May 11, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [ff446033f4](https://linux-hardware.org/?probe=ff446033f4) | May 07, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [9b3d9029ea](https://linux-hardware.org/?probe=9b3d9029ea) | May 03, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [fbdced7593](https://linux-hardware.org/?probe=fbdced7593) | Apr 30, 2020 |
| Timi          | TM1613                      | Notebook    | [5f55af6b8d](https://linux-hardware.org/?probe=5f55af6b8d) | Apr 27, 2020 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [828fc9a788](https://linux-hardware.org/?probe=828fc9a788) | Apr 26, 2020 |
| MSI           | MS-7250                     | Desktop     | [9aafa9594b](https://linux-hardware.org/?probe=9aafa9594b) | Apr 18, 2020 |
| ASUSTek       | N551JM                      | Notebook    | [cd375242d3](https://linux-hardware.org/?probe=cd375242d3) | Apr 15, 2020 |
| MSI           | MS-7507                     | Desktop     | [f33b052aed](https://linux-hardware.org/?probe=f33b052aed) | Apr 14, 2020 |
| Gigabyte      | D525TUD                     | Desktop     | [16b44a22f0](https://linux-hardware.org/?probe=16b44a22f0) | Apr 13, 2020 |
| Acer          | Aspire A315-42G             | Notebook    | [e050431a72](https://linux-hardware.org/?probe=e050431a72) | Apr 09, 2020 |
| Acer          | Aspire A315-42G             | Notebook    | [13a642b394](https://linux-hardware.org/?probe=13a642b394) | Apr 09, 2020 |
| HP            | ProBook 4710s               | Notebook    | [56f533f0f5](https://linux-hardware.org/?probe=56f533f0f5) | Apr 07, 2020 |
| HP            | Notebook                    | Notebook    | [d32a1f4247](https://linux-hardware.org/?probe=d32a1f4247) | Mar 30, 2020 |
| Acer          | Aspire 4810T                | Notebook    | [b7d82235f8](https://linux-hardware.org/?probe=b7d82235f8) | Mar 22, 2020 |
| Acer          | TravelMate P259-M           | Notebook    | [596bd79c7a](https://linux-hardware.org/?probe=596bd79c7a) | Mar 22, 2020 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [b0522c8711](https://linux-hardware.org/?probe=b0522c8711) | Mar 19, 2020 |
| Lenovo        | ThinkPad T61 7661WPF        | Notebook    | [ce22405483](https://linux-hardware.org/?probe=ce22405483) | Mar 19, 2020 |
| ASUSTek       | K52N                        | Notebook    | [a1fea085d9](https://linux-hardware.org/?probe=a1fea085d9) | Mar 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0e0fa6f7e5](https://linux-hardware.org/?probe=0e0fa6f7e5) | Mar 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0c7024795f](https://linux-hardware.org/?probe=0c7024795f) | Mar 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [526830e223](https://linux-hardware.org/?probe=526830e223) | Mar 17, 2020 |
| ASUSTek       | X540NV                      | Notebook    | [e37fc99e67](https://linux-hardware.org/?probe=e37fc99e67) | Mar 11, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [efbd3772bc](https://linux-hardware.org/?probe=efbd3772bc) | Mar 09, 2020 |
| ASUSTek       | X540NV                      | Notebook    | [123e49a129](https://linux-hardware.org/?probe=123e49a129) | Mar 07, 2020 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [a451b0d94d](https://linux-hardware.org/?probe=a451b0d94d) | Mar 07, 2020 |
| Dell          | Inspiron 3576               | Notebook    | [2938ca5aec](https://linux-hardware.org/?probe=2938ca5aec) | Mar 03, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [7c909cb955](https://linux-hardware.org/?probe=7c909cb955) | Mar 01, 2020 |
| Acer          | Extensa 5220                | Notebook    | [3ac52b68ad](https://linux-hardware.org/?probe=3ac52b68ad) | Mar 01, 2020 |
| Dell          | Inspiron 3576               | Notebook    | [c0fb2f48aa](https://linux-hardware.org/?probe=c0fb2f48aa) | Feb 29, 2020 |
| ASUSTek       | X705UQR                     | Notebook    | [a5cca23283](https://linux-hardware.org/?probe=a5cca23283) | Feb 29, 2020 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [18f5afd1ed](https://linux-hardware.org/?probe=18f5afd1ed) | Feb 28, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [88acae56fa](https://linux-hardware.org/?probe=88acae56fa) | Feb 28, 2020 |
| Packard Be... | DOT S                       | Notebook    | [cd2b5a2715](https://linux-hardware.org/?probe=cd2b5a2715) | Feb 28, 2020 |
| Packard Be... | DOT S                       | Notebook    | [8db7395b33](https://linux-hardware.org/?probe=8db7395b33) | Feb 27, 2020 |
| ASUSTek       | K53SV                       | Notebook    | [9192ccbb93](https://linux-hardware.org/?probe=9192ccbb93) | Feb 26, 2020 |
| Timi          | TM1701                      | Notebook    | [4185035b5f](https://linux-hardware.org/?probe=4185035b5f) | Feb 26, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [619c9af84e](https://linux-hardware.org/?probe=619c9af84e) | Feb 25, 2020 |
| HP            | Pavilion g6                 | Notebook    | [4e0759261c](https://linux-hardware.org/?probe=4e0759261c) | Feb 24, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [8e0229807b](https://linux-hardware.org/?probe=8e0229807b) | Feb 24, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [dda987c8c9](https://linux-hardware.org/?probe=dda987c8c9) | Feb 24, 2020 |
| Acer          | Aspire E1-571G              | Notebook    | [9951bcb215](https://linux-hardware.org/?probe=9951bcb215) | Feb 23, 2020 |
| Packard Be... | DOT S                       | Notebook    | [ef2c3a6924](https://linux-hardware.org/?probe=ef2c3a6924) | Feb 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f3185269f](https://linux-hardware.org/?probe=3f3185269f) | Feb 18, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [fe39ad1f52](https://linux-hardware.org/?probe=fe39ad1f52) | Feb 13, 2020 |
| ASUSTek       | K70AE                       | Notebook    | [1c9b37e0bf](https://linux-hardware.org/?probe=1c9b37e0bf) | Feb 12, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [8d3edd49c5](https://linux-hardware.org/?probe=8d3edd49c5) | Feb 11, 2020 |
| Dell          | System XPS L702X            | Notebook    | [17383a48fc](https://linux-hardware.org/?probe=17383a48fc) | Feb 06, 2020 |
| Lenovo        | ThinkPad T470 20HD005QRT    | Notebook    | [1864afd83f](https://linux-hardware.org/?probe=1864afd83f) | Feb 03, 2020 |
| ASUSTek       | X705UQR                     | Notebook    | [8b15a6370b](https://linux-hardware.org/?probe=8b15a6370b) | Feb 01, 2020 |
| Acer          | Aspire V5-561G              | Notebook    | [a646ea611f](https://linux-hardware.org/?probe=a646ea611f) | Jan 29, 2020 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [cd7471d773](https://linux-hardware.org/?probe=cd7471d773) | Jan 25, 2020 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [38709aec79](https://linux-hardware.org/?probe=38709aec79) | Jan 25, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [c97d5c5a5e](https://linux-hardware.org/?probe=c97d5c5a5e) | Jan 24, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [659e0d3a62](https://linux-hardware.org/?probe=659e0d3a62) | Jan 24, 2020 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [1c4e4c5a2d](https://linux-hardware.org/?probe=1c4e4c5a2d) | Jan 24, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [3e955a15c1](https://linux-hardware.org/?probe=3e955a15c1) | Jan 22, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [adc392749f](https://linux-hardware.org/?probe=adc392749f) | Jan 22, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [485f1149df](https://linux-hardware.org/?probe=485f1149df) | Jan 20, 2020 |
| ASUSTek       | X705UQR                     | Notebook    | [87c3bdc009](https://linux-hardware.org/?probe=87c3bdc009) | Jan 19, 2020 |
| ASUSTek       | X705UQR                     | Notebook    | [bc34d4d0e9](https://linux-hardware.org/?probe=bc34d4d0e9) | Jan 19, 2020 |
| ASUSTek       | UL30A                       | Notebook    | [f9f8ddf425](https://linux-hardware.org/?probe=f9f8ddf425) | Jan 14, 2020 |
| ASRock        | Z77 Extreme4-M              | Desktop     | [14e729f5aa](https://linux-hardware.org/?probe=14e729f5aa) | Jan 13, 2020 |
| ASUSTek       | X540SA                      | Notebook    | [22047ce8bb](https://linux-hardware.org/?probe=22047ce8bb) | Jan 11, 2020 |
| HP            | Unknown                     | Notebook    | [7845d03a39](https://linux-hardware.org/?probe=7845d03a39) | Jan 11, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [87e363c1ed](https://linux-hardware.org/?probe=87e363c1ed) | Jan 10, 2020 |
| Biostar       | NF520-A2 TE                 | Desktop     | [cd41d93f63](https://linux-hardware.org/?probe=cd41d93f63) | Jan 06, 2020 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [a3ff07d84b](https://linux-hardware.org/?probe=a3ff07d84b) | Jan 04, 2020 |
| HP            | ProBook 455 G1              | Notebook    | [08dcbaa82a](https://linux-hardware.org/?probe=08dcbaa82a) | Jan 02, 2020 |
| HP            | ProBook 4530s               | Notebook    | [48ca791cd2](https://linux-hardware.org/?probe=48ca791cd2) | Jan 02, 2020 |
| Samsung       | R519/R719                   | Notebook    | [1a0ac991d0](https://linux-hardware.org/?probe=1a0ac991d0) | Jan 01, 2020 |
| ASUSTek       | K53Z                        | Notebook    | [51da8ec92c](https://linux-hardware.org/?probe=51da8ec92c) | Jan 01, 2020 |
| Unknown       | Unknown                     | Phone       | [fb11f725d3](https://linux-hardware.org/?probe=fb11f725d3) | Dec 31, 2019 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [54845cd095](https://linux-hardware.org/?probe=54845cd095) | Dec 29, 2019 |
| Acer          | Veriton N4660G              | Desktop     | [9afe548805](https://linux-hardware.org/?probe=9afe548805) | Dec 29, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [e96c98384b](https://linux-hardware.org/?probe=e96c98384b) | Dec 28, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [9f38052441](https://linux-hardware.org/?probe=9f38052441) | Dec 28, 2019 |
| Toshiba       | Satellite L850D-BJS         | Notebook    | [c77563a5fb](https://linux-hardware.org/?probe=c77563a5fb) | Dec 23, 2019 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [02221c3f6b](https://linux-hardware.org/?probe=02221c3f6b) | Dec 19, 2019 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [60a1413416](https://linux-hardware.org/?probe=60a1413416) | Dec 19, 2019 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [2575da9f64](https://linux-hardware.org/?probe=2575da9f64) | Dec 18, 2019 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [57160cc915](https://linux-hardware.org/?probe=57160cc915) | Dec 16, 2019 |
| Samsung       | R508                        | Notebook    | [f2d52e0253](https://linux-hardware.org/?probe=f2d52e0253) | Dec 12, 2019 |
| ASUSTek       | X540NV                      | Notebook    | [e1396088af](https://linux-hardware.org/?probe=e1396088af) | Dec 11, 2019 |
| ASUSTek       | X540NV                      | Notebook    | [0649347201](https://linux-hardware.org/?probe=0649347201) | Dec 11, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c6838b1dba](https://linux-hardware.org/?probe=c6838b1dba) | Dec 11, 2019 |
| Packard Be... | DOT S                       | Notebook    | [5bd4609615](https://linux-hardware.org/?probe=5bd4609615) | Dec 09, 2019 |
| HP            | Pavilion 17                 | Notebook    | [e5c53c61e8](https://linux-hardware.org/?probe=e5c53c61e8) | Dec 08, 2019 |
| Lenovo        | ThinkPad SL510 2875RS2      | Notebook    | [4b5548d0bb](https://linux-hardware.org/?probe=4b5548d0bb) | Dec 05, 2019 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [3d3f27a3f9](https://linux-hardware.org/?probe=3d3f27a3f9) | Dec 04, 2019 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [559d304205](https://linux-hardware.org/?probe=559d304205) | Dec 04, 2019 |
| Dell          | G3 3579                     | Notebook    | [c4fe97cca2](https://linux-hardware.org/?probe=c4fe97cca2) | Dec 04, 2019 |
| Dell          | G3 3579                     | Notebook    | [ada421696a](https://linux-hardware.org/?probe=ada421696a) | Dec 04, 2019 |
| HP            | Pavilion 15                 | Notebook    | [03188ddfb3](https://linux-hardware.org/?probe=03188ddfb3) | Dec 03, 2019 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [08835d6477](https://linux-hardware.org/?probe=08835d6477) | Dec 03, 2019 |
| ASRock        | G31M-S                      | Desktop     | [674951f8cf](https://linux-hardware.org/?probe=674951f8cf) | Dec 03, 2019 |
| MSI           | 760GM-P33                   | Desktop     | [b14d738927](https://linux-hardware.org/?probe=b14d738927) | Dec 02, 2019 |
| Dell          | Inspiron 5559               | Notebook    | [5a4aaf46f2](https://linux-hardware.org/?probe=5a4aaf46f2) | Dec 02, 2019 |
| HP            | ProBook 450 G5              | Notebook    | [9441c13ce5](https://linux-hardware.org/?probe=9441c13ce5) | Dec 02, 2019 |
| MSI           | GP72 7RDX                   | Notebook    | [445ae9719a](https://linux-hardware.org/?probe=445ae9719a) | Dec 02, 2019 |
| Dell          | Latitude E5450              | Notebook    | [9d71909e26](https://linux-hardware.org/?probe=9d71909e26) | Dec 02, 2019 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [15a59f41a1](https://linux-hardware.org/?probe=15a59f41a1) | Nov 27, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [320dde739d](https://linux-hardware.org/?probe=320dde739d) | Nov 27, 2019 |
| Acer          | Aspire E1-530               | Notebook    | [47bc99ddc7](https://linux-hardware.org/?probe=47bc99ddc7) | Nov 27, 2019 |
| Lenovo        | Remore CRB No DPK           | All in one  | [cd624c7ba5](https://linux-hardware.org/?probe=cd624c7ba5) | Nov 27, 2019 |
| Acer          | Aspire E1-532               | Notebook    | [ecb10a3db1](https://linux-hardware.org/?probe=ecb10a3db1) | Nov 27, 2019 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a7b57eaddf](https://linux-hardware.org/?probe=a7b57eaddf) | Nov 27, 2019 |
| Gigabyte      | H81M-S2H                    | Desktop     | [bcb59e4acf](https://linux-hardware.org/?probe=bcb59e4acf) | Nov 27, 2019 |
| Gigabyte      | H81M-S2H                    | Desktop     | [67a75ff7c4](https://linux-hardware.org/?probe=67a75ff7c4) | Nov 26, 2019 |
| ASUSTek       | V200IB                      | All in one  | [da374c3c83](https://linux-hardware.org/?probe=da374c3c83) | Nov 26, 2019 |
| ASUSTek       | V200IB                      | Desktop     | [61357ecaed](https://linux-hardware.org/?probe=61357ecaed) | Nov 26, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3baee5b588](https://linux-hardware.org/?probe=3baee5b588) | Nov 26, 2019 |
| Acer          | Aspire E1-530               | Notebook    | [e6b4056c8c](https://linux-hardware.org/?probe=e6b4056c8c) | Nov 26, 2019 |
| ASRock        | H61M-VG4                    | Desktop     | [787fad97da](https://linux-hardware.org/?probe=787fad97da) | Nov 26, 2019 |
| Toshiba       | SATEGO X200                 | Notebook    | [087c0e291d](https://linux-hardware.org/?probe=087c0e291d) | Nov 25, 2019 |
| Packard Be... | EasyNote TK36               | Notebook    | [b85f41a113](https://linux-hardware.org/?probe=b85f41a113) | Nov 24, 2019 |
| Packard Be... | EasyNote TK36               | Notebook    | [5ded5e4dc0](https://linux-hardware.org/?probe=5ded5e4dc0) | Nov 24, 2019 |
| Packard Be... | EasyNote TK36               | Notebook    | [b0e6d88437](https://linux-hardware.org/?probe=b0e6d88437) | Nov 23, 2019 |
| Packard Be... | EasyNote TK36               | Notebook    | [f86cacb590](https://linux-hardware.org/?probe=f86cacb590) | Nov 23, 2019 |
| Gigabyte      | B450M S2H                   | Desktop     | [1fc5f15d9a](https://linux-hardware.org/?probe=1fc5f15d9a) | Nov 23, 2019 |
| Gigabyte      | B450M S2H                   | Desktop     | [4de9a6fdb0](https://linux-hardware.org/?probe=4de9a6fdb0) | Nov 23, 2019 |
| ASRock        | G31M-S                      | Desktop     | [9a60dcb468](https://linux-hardware.org/?probe=9a60dcb468) | Nov 22, 2019 |
| Lenovo        | S20-30 20421                | Notebook    | [969154a207](https://linux-hardware.org/?probe=969154a207) | Nov 21, 2019 |
| Lenovo        | S20-30 20421                | Notebook    | [d2625b22e1](https://linux-hardware.org/?probe=d2625b22e1) | Nov 19, 2019 |
| HP            | Pavilion 15                 | Notebook    | [ae59f09d06](https://linux-hardware.org/?probe=ae59f09d06) | Nov 19, 2019 |
| ASUSTek       | M2N-X                       | Desktop     | [69669b5bdd](https://linux-hardware.org/?probe=69669b5bdd) | Nov 18, 2019 |
| Lenovo        | ThinkPad T470 20HD005QRT    | Notebook    | [403acf7be3](https://linux-hardware.org/?probe=403acf7be3) | Nov 16, 2019 |
| ASRock        | G31M-S                      | Desktop     | [26c06abca8](https://linux-hardware.org/?probe=26c06abca8) | Nov 11, 2019 |
| ASUSTek       | X541UAK                     | Notebook    | [a765714f02](https://linux-hardware.org/?probe=a765714f02) | Nov 07, 2019 |
| MSI           | Z77A-G41                    | Desktop     | [213b4c47a0](https://linux-hardware.org/?probe=213b4c47a0) | Nov 04, 2019 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [a1b106dc08](https://linux-hardware.org/?probe=a1b106dc08) | Nov 04, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [292caf76d2](https://linux-hardware.org/?probe=292caf76d2) | Nov 01, 2019 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [c43d48a7e8](https://linux-hardware.org/?probe=c43d48a7e8) | Oct 31, 2019 |
| Samsung       | RV408/RV508                 | Notebook    | [e4e8ab57d3](https://linux-hardware.org/?probe=e4e8ab57d3) | Oct 31, 2019 |
| Lenovo        | B50-30 20382                | Notebook    | [c21f8427bb](https://linux-hardware.org/?probe=c21f8427bb) | Oct 31, 2019 |
| BenQ          | JoyBook A53                 | Notebook    | [244ee24b1d](https://linux-hardware.org/?probe=244ee24b1d) | Oct 30, 2019 |
| Dream Mach... | N8xEJEK                     | Notebook    | [7d9991c02f](https://linux-hardware.org/?probe=7d9991c02f) | Oct 30, 2019 |
| ASRock        | H61M-HVGS                   | Desktop     | [04ed30a83f](https://linux-hardware.org/?probe=04ed30a83f) | Oct 30, 2019 |
| ASRock        | G31M-S                      | Desktop     | [e78c58b8f7](https://linux-hardware.org/?probe=e78c58b8f7) | Oct 30, 2019 |
| MSI           | PS63 Modern 8M              | Notebook    | [3442120f57](https://linux-hardware.org/?probe=3442120f57) | Oct 29, 2019 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [9f3722cd19](https://linux-hardware.org/?probe=9f3722cd19) | Oct 27, 2019 |
| Samsung       | R528/R728                   | Notebook    | [72819f11a2](https://linux-hardware.org/?probe=72819f11a2) | Oct 26, 2019 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a5ccfe7480](https://linux-hardware.org/?probe=a5ccfe7480) | Oct 23, 2019 |
| ASUSTek       | N550JV                      | Notebook    | [091b2a9dda](https://linux-hardware.org/?probe=091b2a9dda) | Oct 22, 2019 |
| Acer          | Aspire 4810T                | Notebook    | [f177f662c9](https://linux-hardware.org/?probe=f177f662c9) | Oct 21, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3eade14c1a](https://linux-hardware.org/?probe=3eade14c1a) | Oct 18, 2019 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [4a653fdd06](https://linux-hardware.org/?probe=4a653fdd06) | Oct 12, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [d0e6b3a935](https://linux-hardware.org/?probe=d0e6b3a935) | Oct 08, 2019 |
| Supermicro    | X10DRiB                     | Server      | [0f42b6c827](https://linux-hardware.org/?probe=0f42b6c827) | Oct 08, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5b817a0d34](https://linux-hardware.org/?probe=5b817a0d34) | Oct 06, 2019 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [c9b3479419](https://linux-hardware.org/?probe=c9b3479419) | Oct 05, 2019 |
| ASRock        | H97 Anniversary             | Desktop     | [f9f19da3b0](https://linux-hardware.org/?probe=f9f19da3b0) | Sep 29, 2019 |
| ASRock        | H97 Anniversary             | Desktop     | [48920360b7](https://linux-hardware.org/?probe=48920360b7) | Sep 29, 2019 |
| ASUSTek       | 1101HA                      | Notebook    | [61837b2a0e](https://linux-hardware.org/?probe=61837b2a0e) | Sep 27, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ab7f8a4bba](https://linux-hardware.org/?probe=ab7f8a4bba) | Sep 25, 2019 |
| Dell          | Inspiron 13-5378            | Notebook    | [37c0832ec3](https://linux-hardware.org/?probe=37c0832ec3) | Sep 20, 2019 |
| Gigabyte      | C847N                       | Desktop     | [dd58b111d2](https://linux-hardware.org/?probe=dd58b111d2) | Sep 20, 2019 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [4c465e5a03](https://linux-hardware.org/?probe=4c465e5a03) | Sep 19, 2019 |
| ASRock        | H61M-HVGS                   | Desktop     | [8fba013175](https://linux-hardware.org/?probe=8fba013175) | Sep 15, 2019 |
| ASUSTek       | 1101HA                      | Notebook    | [8ad347373c](https://linux-hardware.org/?probe=8ad347373c) | Sep 15, 2019 |
| ASUSTek       | X541UAK                     | Notebook    | [a8ec17e19a](https://linux-hardware.org/?probe=a8ec17e19a) | Sep 13, 2019 |
| Dell          | Vostro 5581                 | Notebook    | [137d404b4f](https://linux-hardware.org/?probe=137d404b4f) | Sep 04, 2019 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65edd09a48](https://linux-hardware.org/?probe=65edd09a48) | Sep 02, 2019 |
| Packard Be... | ONETWO M3700                | All in one  | [19fbb5d44c](https://linux-hardware.org/?probe=19fbb5d44c) | Sep 02, 2019 |
| ASRock        | N68C-GS FX                  | Desktop     | [df9e40504c](https://linux-hardware.org/?probe=df9e40504c) | Sep 02, 2019 |
| Samsung       | R528/R728                   | Notebook    | [9a81ee014c](https://linux-hardware.org/?probe=9a81ee014c) | Aug 31, 2019 |
| ASRock        | N68C-GS FX                  | Desktop     | [df615d6ccf](https://linux-hardware.org/?probe=df615d6ccf) | Aug 29, 2019 |
| ASUSTek       | K501UX                      | Notebook    | [5e0c250961](https://linux-hardware.org/?probe=5e0c250961) | Aug 22, 2019 |
| Dell          | Vostro 5581                 | Notebook    | [6d17449b1e](https://linux-hardware.org/?probe=6d17449b1e) | Aug 19, 2019 |
| Dell          | Vostro 5581                 | Notebook    | [e890c77b5d](https://linux-hardware.org/?probe=e890c77b5d) | Aug 18, 2019 |
| MSI           | 0A90                        | Desktop     | [64c0075cf9](https://linux-hardware.org/?probe=64c0075cf9) | Aug 18, 2019 |
| ASRock        | H61M-HVGS                   | Desktop     | [48c5aab4be](https://linux-hardware.org/?probe=48c5aab4be) | Aug 17, 2019 |
| Lenovo        | ThinkPad SL510 2875RS2      | Notebook    | [85f5a138a1](https://linux-hardware.org/?probe=85f5a138a1) | Aug 16, 2019 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ce436327da](https://linux-hardware.org/?probe=ce436327da) | Aug 16, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [03e68e8b7c](https://linux-hardware.org/?probe=03e68e8b7c) | Aug 14, 2019 |
| Gigabyte      | 945PL-S3                    | Desktop     | [f235798c9e](https://linux-hardware.org/?probe=f235798c9e) | Aug 09, 2019 |
| Intel         | SKYBAY                      | Desktop     | [cdcd16d077](https://linux-hardware.org/?probe=cdcd16d077) | Aug 09, 2019 |
| Samsung       | R580/R590                   | Notebook    | [ef8583eaed](https://linux-hardware.org/?probe=ef8583eaed) | Aug 09, 2019 |
| Gigabyte      | H81M-S2H                    | Desktop     | [98c28c0cba](https://linux-hardware.org/?probe=98c28c0cba) | Aug 08, 2019 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5fe6d47df5](https://linux-hardware.org/?probe=5fe6d47df5) | Aug 05, 2019 |
| Packard Be... | ONETWO M3700                | All in one  | [dc0da982f7](https://linux-hardware.org/?probe=dc0da982f7) | Aug 03, 2019 |
| HP            | Pavilion 17                 | Notebook    | [24e7df16f9](https://linux-hardware.org/?probe=24e7df16f9) | Aug 03, 2019 |
| HP            | 0A54h                       | Desktop     | [ff6685ad25](https://linux-hardware.org/?probe=ff6685ad25) | Aug 02, 2019 |
| ASUSTek       | 1011PX                      | Notebook    | [5b135fd648](https://linux-hardware.org/?probe=5b135fd648) | Aug 01, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [47bfe0724a](https://linux-hardware.org/?probe=47bfe0724a) | Jul 30, 2019 |
| ASUSTek       | K54HR                       | Notebook    | [5e03bd6730](https://linux-hardware.org/?probe=5e03bd6730) | Jul 29, 2019 |
| Acer          | Extensa 2510G               | Notebook    | [1c77d7a584](https://linux-hardware.org/?probe=1c77d7a584) | Jul 27, 2019 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [66a5ea0be5](https://linux-hardware.org/?probe=66a5ea0be5) | Jul 26, 2019 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [34021fd6bd](https://linux-hardware.org/?probe=34021fd6bd) | Jul 25, 2019 |
| ASRock        | H310M-HDV                   | Desktop     | [39c0fbe126](https://linux-hardware.org/?probe=39c0fbe126) | Jul 25, 2019 |
| Acer          | Nitro AN515-31              | Notebook    | [c1f4538adb](https://linux-hardware.org/?probe=c1f4538adb) | Jul 24, 2019 |
| Lenovo        | G570 20079                  | Notebook    | [a7618091fb](https://linux-hardware.org/?probe=a7618091fb) | Jul 23, 2019 |
| Acer          | Extensa 2508                | Notebook    | [a1d2e02773](https://linux-hardware.org/?probe=a1d2e02773) | Jul 22, 2019 |
| ASUSTek       | X540SA                      | Notebook    | [9964879fbe](https://linux-hardware.org/?probe=9964879fbe) | Jul 21, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a385ff1671](https://linux-hardware.org/?probe=a385ff1671) | Jul 20, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1a41f9e428](https://linux-hardware.org/?probe=1a41f9e428) | Jul 20, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [03b0e6294f](https://linux-hardware.org/?probe=03b0e6294f) | Jul 19, 2019 |
| MSI           | MS-N014                     | Notebook    | [a6b6d22f92](https://linux-hardware.org/?probe=a6b6d22f92) | Jul 18, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [00eecf27f3](https://linux-hardware.org/?probe=00eecf27f3) | Jul 16, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [b724162662](https://linux-hardware.org/?probe=b724162662) | Jul 10, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6b13d225c0](https://linux-hardware.org/?probe=6b13d225c0) | Jul 09, 2019 |
| Acer          | Aspire E1-771               | Notebook    | [4a1964118d](https://linux-hardware.org/?probe=4a1964118d) | Jul 04, 2019 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [0c91aab0ff](https://linux-hardware.org/?probe=0c91aab0ff) | Jun 27, 2019 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [b147e4676b](https://linux-hardware.org/?probe=b147e4676b) | Jun 25, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [7c80bf6fda](https://linux-hardware.org/?probe=7c80bf6fda) | Jun 20, 2019 |
| Acer          | Aspire V3-772G              | Notebook    | [6cc64da5c5](https://linux-hardware.org/?probe=6cc64da5c5) | Jun 20, 2019 |
| MSI           | MS-7250                     | Desktop     | [005023ee9d](https://linux-hardware.org/?probe=005023ee9d) | Jun 19, 2019 |
| MSI           | MS-7250                     | Desktop     | [cd4ecc0b42](https://linux-hardware.org/?probe=cd4ecc0b42) | Jun 19, 2019 |
| Gigabyte      | 945PL-S3                    | Desktop     | [7b106b9427](https://linux-hardware.org/?probe=7b106b9427) | Jun 17, 2019 |
| Gigabyte      | P55M-UD4                    | Desktop     | [98980d3cde](https://linux-hardware.org/?probe=98980d3cde) | Jun 17, 2019 |
| Biostar       | A780L3L                     | Desktop     | [2de6892c13](https://linux-hardware.org/?probe=2de6892c13) | Jun 15, 2019 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [678d443649](https://linux-hardware.org/?probe=678d443649) | Jun 14, 2019 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [f72a609702](https://linux-hardware.org/?probe=f72a609702) | Jun 13, 2019 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [a3afa44f01](https://linux-hardware.org/?probe=a3afa44f01) | Jun 11, 2019 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [13b9b4e6e9](https://linux-hardware.org/?probe=13b9b4e6e9) | Jun 09, 2019 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [b74e6f3a71](https://linux-hardware.org/?probe=b74e6f3a71) | Jun 08, 2019 |
| HP            | ENVY 17                     | Notebook    | [9f9eeecefa](https://linux-hardware.org/?probe=9f9eeecefa) | Jun 05, 2019 |
| Acer          | Aspire 4810T                | Notebook    | [0b3243adb4](https://linux-hardware.org/?probe=0b3243adb4) | May 29, 2019 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [9c885eb562](https://linux-hardware.org/?probe=9c885eb562) | May 25, 2019 |
| Acer          | Aspire 5349                 | Notebook    | [8e79cddbda](https://linux-hardware.org/?probe=8e79cddbda) | May 23, 2019 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [8358a6f5f5](https://linux-hardware.org/?probe=8358a6f5f5) | May 22, 2019 |
| ASUSTek       | X551MA                      | Notebook    | [ef445a792b](https://linux-hardware.org/?probe=ef445a792b) | May 20, 2019 |
| ASUSTek       | X551MA                      | Notebook    | [5ad90522ec](https://linux-hardware.org/?probe=5ad90522ec) | May 20, 2019 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [ba1f9829de](https://linux-hardware.org/?probe=ba1f9829de) | May 19, 2019 |
| ASUSTek       | X751SA                      | Notebook    | [412366312b](https://linux-hardware.org/?probe=412366312b) | May 18, 2019 |
| Dell          | Inspiron 7577               | Notebook    | [ae6c3a51b8](https://linux-hardware.org/?probe=ae6c3a51b8) | May 17, 2019 |
| ASUSTek       | X751SA                      | Notebook    | [bb1fd1c382](https://linux-hardware.org/?probe=bb1fd1c382) | May 17, 2019 |
| ASUSTek       | X751SA                      | Notebook    | [130b715a25](https://linux-hardware.org/?probe=130b715a25) | May 17, 2019 |
| Samsung       | RV413/RV513                 | Notebook    | [539459e889](https://linux-hardware.org/?probe=539459e889) | May 16, 2019 |
| Samsung       | RV413/RV513                 | Notebook    | [c6e6520b11](https://linux-hardware.org/?probe=c6e6520b11) | May 16, 2019 |
| ASRock        | N68C-GS FX                  | Desktop     | [becfb6b881](https://linux-hardware.org/?probe=becfb6b881) | May 14, 2019 |
| ASUSTek       | UL30A                       | Notebook    | [6dac8a4d6f](https://linux-hardware.org/?probe=6dac8a4d6f) | May 13, 2019 |
| Jetway        | TI41M                       | Desktop     | [5c923195ab](https://linux-hardware.org/?probe=5c923195ab) | May 12, 2019 |
| Lenovo        | 3000                        | Desktop     | [de702ed343](https://linux-hardware.org/?probe=de702ed343) | May 10, 2019 |
| HP            | ProBook 455 G1              | Notebook    | [185cf26f05](https://linux-hardware.org/?probe=185cf26f05) | May 09, 2019 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [988dbccf88](https://linux-hardware.org/?probe=988dbccf88) | May 09, 2019 |
| ASUSTek       | WS X299 PRO                 | Desktop     | [b31f25bbb7](https://linux-hardware.org/?probe=b31f25bbb7) | May 07, 2019 |
| ASUSTek       | X510UA                      | Notebook    | [f6c30b2027](https://linux-hardware.org/?probe=f6c30b2027) | May 05, 2019 |
| MSI           | Z97 GAMING 5                | Desktop     | [fd97593820](https://linux-hardware.org/?probe=fd97593820) | May 01, 2019 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [d90cc4cbe3](https://linux-hardware.org/?probe=d90cc4cbe3) | Apr 27, 2019 |
| Lenovo        | 3000                        | Desktop     | [08b71be3a2](https://linux-hardware.org/?probe=08b71be3a2) | Apr 26, 2019 |
| MSI           | Z97 GAMING 5                | Desktop     | [f7e37a8a8d](https://linux-hardware.org/?probe=f7e37a8a8d) | Apr 23, 2019 |
| Gigabyte      | P35-DS3L                    | Desktop     | [626c138c66](https://linux-hardware.org/?probe=626c138c66) | Apr 22, 2019 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [4a9dc9c551](https://linux-hardware.org/?probe=4a9dc9c551) | Apr 21, 2019 |
| Acer          | Nitro AN515-31              | Notebook    | [7a2df83bd4](https://linux-hardware.org/?probe=7a2df83bd4) | Apr 20, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [67a4e2a8a4](https://linux-hardware.org/?probe=67a4e2a8a4) | Apr 18, 2019 |
| Acer          | Nitro AN515-31              | Notebook    | [7ffaa2afa6](https://linux-hardware.org/?probe=7ffaa2afa6) | Apr 16, 2019 |
| ASUSTek       | UL30A                       | Notebook    | [46271f4c83](https://linux-hardware.org/?probe=46271f4c83) | Apr 07, 2019 |
| Biostar       | TA75A+                      | Desktop     | [5bd842f25a](https://linux-hardware.org/?probe=5bd842f25a) | Apr 06, 2019 |
| ASUSTek       | UX550VD                     | Notebook    | [c440ebc340](https://linux-hardware.org/?probe=c440ebc340) | Apr 04, 2019 |
| ASUSTek       | UL30A                       | Notebook    | [059a9e0d5f](https://linux-hardware.org/?probe=059a9e0d5f) | Apr 02, 2019 |
| Gigabyte      | 970A-DS3                    | Desktop     | [8ad8dd2388](https://linux-hardware.org/?probe=8ad8dd2388) | Apr 02, 2019 |
| HP            | Notebook                    | Notebook    | [b09be0c6da](https://linux-hardware.org/?probe=b09be0c6da) | Mar 31, 2019 |
| Gigabyte      | M4HM87P-00                  | Desktop     | [831597ffda](https://linux-hardware.org/?probe=831597ffda) | Mar 31, 2019 |
| MSI           | H87M-E35                    | Desktop     | [a4408c4eea](https://linux-hardware.org/?probe=a4408c4eea) | Mar 29, 2019 |
| ASRock        | Z87 Pro4                    | Desktop     | [0fdbdd7257](https://linux-hardware.org/?probe=0fdbdd7257) | Mar 28, 2019 |
| Lenovo        | B590 20206                  | Notebook    | [c0039b9d80](https://linux-hardware.org/?probe=c0039b9d80) | Mar 27, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f801da09f7](https://linux-hardware.org/?probe=f801da09f7) | Mar 26, 2019 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [18af0d2322](https://linux-hardware.org/?probe=18af0d2322) | Mar 26, 2019 |
| Lenovo        | IdeaPad Z565 20066          | Notebook    | [6e6d9742ed](https://linux-hardware.org/?probe=6e6d9742ed) | Mar 23, 2019 |
| ASUSTek       | K50IP                       | Notebook    | [16e798fc6d](https://linux-hardware.org/?probe=16e798fc6d) | Mar 22, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [61650808a4](https://linux-hardware.org/?probe=61650808a4) | Mar 16, 2019 |
| ASUSTek       | X541NA                      | Notebook    | [339f40edee](https://linux-hardware.org/?probe=339f40edee) | Mar 16, 2019 |
| ASUSTek       | X541NA                      | Notebook    | [deef5c1776](https://linux-hardware.org/?probe=deef5c1776) | Mar 16, 2019 |
| Lenovo        | G700 20251                  | Notebook    | [31a2a66abd](https://linux-hardware.org/?probe=31a2a66abd) | Mar 15, 2019 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [29d403e18d](https://linux-hardware.org/?probe=29d403e18d) | Mar 15, 2019 |
| Lenovo        | G570 20079                  | Notebook    | [dddc5b738c](https://linux-hardware.org/?probe=dddc5b738c) | Mar 12, 2019 |
| HP            | 635                         | Notebook    | [c510246cec](https://linux-hardware.org/?probe=c510246cec) | Mar 09, 2019 |
| MSI           | MS-7369                     | Desktop     | [5824a23fe2](https://linux-hardware.org/?probe=5824a23fe2) | Mar 08, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [bf7d967cac](https://linux-hardware.org/?probe=bf7d967cac) | Mar 05, 2019 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [42c1b17429](https://linux-hardware.org/?probe=42c1b17429) | Feb 28, 2019 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [9898edbaf1](https://linux-hardware.org/?probe=9898edbaf1) | Feb 27, 2019 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [44cefd50de](https://linux-hardware.org/?probe=44cefd50de) | Feb 27, 2019 |
| ASUSTek       | N73JF                       | Notebook    | [ac3cf92791](https://linux-hardware.org/?probe=ac3cf92791) | Feb 24, 2019 |
| ASUSTek       | N73JF                       | Notebook    | [74010f75ff](https://linux-hardware.org/?probe=74010f75ff) | Feb 24, 2019 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [48438c8714](https://linux-hardware.org/?probe=48438c8714) | Feb 14, 2019 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [4c611c79d7](https://linux-hardware.org/?probe=4c611c79d7) | Feb 13, 2019 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [cbe60f7c7a](https://linux-hardware.org/?probe=cbe60f7c7a) | Feb 13, 2019 |
| Acer          | Aspire 3810TZ               | Notebook    | [1af1fd4358](https://linux-hardware.org/?probe=1af1fd4358) | Feb 08, 2019 |
| Dell          | Inspiron 5558               | Notebook    | [74b5e8085f](https://linux-hardware.org/?probe=74b5e8085f) | Feb 06, 2019 |
| HP            | EliteBook 840 G3            | Notebook    | [9246996d88](https://linux-hardware.org/?probe=9246996d88) | Feb 04, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [5c2493db94](https://linux-hardware.org/?probe=5c2493db94) | Feb 03, 2019 |
| Biostar       | MCP6P3                      | Desktop     | [68bd47f661](https://linux-hardware.org/?probe=68bd47f661) | Feb 03, 2019 |
| MSI           | Z97-G43                     | Desktop     | [186dbb4515](https://linux-hardware.org/?probe=186dbb4515) | Feb 03, 2019 |
| ASUSTek       | E402NA                      | Notebook    | [84151cf35d](https://linux-hardware.org/?probe=84151cf35d) | Jan 30, 2019 |
| Samsung       | R519/R719                   | Notebook    | [c2367f286b](https://linux-hardware.org/?probe=c2367f286b) | Jan 26, 2019 |
| ASUSTek       | X540NV                      | Notebook    | [fd26f0c83a](https://linux-hardware.org/?probe=fd26f0c83a) | Jan 22, 2019 |
| HP            | G62                         | Notebook    | [63c41b239d](https://linux-hardware.org/?probe=63c41b239d) | Jan 21, 2019 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [f41b882a8e](https://linux-hardware.org/?probe=f41b882a8e) | Jan 19, 2019 |
| ASRock        | G31M-S                      | Desktop     | [e8737c8ac8](https://linux-hardware.org/?probe=e8737c8ac8) | Jan 17, 2019 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [e9c51ee187](https://linux-hardware.org/?probe=e9c51ee187) | Jan 13, 2019 |
| HP            | Laptop 15-rb0xx             | Notebook    | [e4399cedcf](https://linux-hardware.org/?probe=e4399cedcf) | Jan 10, 2019 |
| HP            | Laptop 15-rb0xx             | Notebook    | [c4ca5d85f2](https://linux-hardware.org/?probe=c4ca5d85f2) | Jan 10, 2019 |
| Biostar       | MCP6P3                      | Desktop     | [b324f9754a](https://linux-hardware.org/?probe=b324f9754a) | Jan 10, 2019 |
| ASUSTek       | T101MT                      | Notebook    | [742c2cd59e](https://linux-hardware.org/?probe=742c2cd59e) | Jan 10, 2019 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [f1a0693718](https://linux-hardware.org/?probe=f1a0693718) | Jan 09, 2019 |
| MSI           | Z77A-G45 GAMING             | Desktop     | [a0f7438599](https://linux-hardware.org/?probe=a0f7438599) | Jan 01, 2019 |
| HP            | Notebook                    | Notebook    | [93451d1d63](https://linux-hardware.org/?probe=93451d1d63) | Dec 31, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [441e47c023](https://linux-hardware.org/?probe=441e47c023) | Dec 30, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5d942bb34d](https://linux-hardware.org/?probe=5d942bb34d) | Dec 30, 2018 |
| Samsung       | RV408/RV508                 | Notebook    | [f67c14e4d6](https://linux-hardware.org/?probe=f67c14e4d6) | Dec 27, 2018 |
| ASRock        | Z77 Extreme4-M              | Desktop     | [c65b222ea1](https://linux-hardware.org/?probe=c65b222ea1) | Dec 25, 2018 |
| Samsung       | R508                        | Notebook    | [c9ea0249f2](https://linux-hardware.org/?probe=c9ea0249f2) | Dec 24, 2018 |
| Acer          | AOD257                      | Notebook    | [d6763cd3ef](https://linux-hardware.org/?probe=d6763cd3ef) | Dec 23, 2018 |
| MSI           | MS-7309                     | Desktop     | [a77abcc8cf](https://linux-hardware.org/?probe=a77abcc8cf) | Dec 22, 2018 |
| Samsung       | RV413/RV513                 | Notebook    | [d069cd58a8](https://linux-hardware.org/?probe=d069cd58a8) | Dec 20, 2018 |
| Acer          | Extensa 7630EZ              | Notebook    | [ff4bc33ec4](https://linux-hardware.org/?probe=ff4bc33ec4) | Dec 18, 2018 |
| ASUSTek       | M51Sr                       | Notebook    | [c91fc1e6b1](https://linux-hardware.org/?probe=c91fc1e6b1) | Dec 15, 2018 |
| Acer          | TravelMate 5760             | Notebook    | [fd0de5be57](https://linux-hardware.org/?probe=fd0de5be57) | Dec 14, 2018 |
| Acer          | Aspire ES1-523              | Notebook    | [b586596a6a](https://linux-hardware.org/?probe=b586596a6a) | Dec 10, 2018 |
| Lenovo        | Z50-70 20354                | Notebook    | [5d8804f368](https://linux-hardware.org/?probe=5d8804f368) | Dec 07, 2018 |
| Acer          | TravelMate 8481T            | Notebook    | [af2aaf56d9](https://linux-hardware.org/?probe=af2aaf56d9) | Dec 07, 2018 |
| MSI           | Z77A-G45 GAMING             | Desktop     | [c0dd7b7123](https://linux-hardware.org/?probe=c0dd7b7123) | Dec 01, 2018 |
| ASUSTek       | N76VJ                       | Notebook    | [2fa5ed1dfc](https://linux-hardware.org/?probe=2fa5ed1dfc) | Nov 30, 2018 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [da78c40bba](https://linux-hardware.org/?probe=da78c40bba) | Nov 30, 2018 |
| Toshiba       | Satellite L300              | Notebook    | [8585fa81bc](https://linux-hardware.org/?probe=8585fa81bc) | Nov 29, 2018 |
| HP            | ProBook 4515s               | Notebook    | [1842a1b183](https://linux-hardware.org/?probe=1842a1b183) | Nov 29, 2018 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [b41b61d2c4](https://linux-hardware.org/?probe=b41b61d2c4) | Nov 29, 2018 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [14a756e743](https://linux-hardware.org/?probe=14a756e743) | Nov 29, 2018 |
| Lenovo        | B590 20206                  | Notebook    | [020331dd95](https://linux-hardware.org/?probe=020331dd95) | Nov 29, 2018 |
| Lenovo        | B590 20206                  | Notebook    | [9cb3062067](https://linux-hardware.org/?probe=9cb3062067) | Nov 29, 2018 |
| ASUSTek       | X510UNR                     | Notebook    | [8cc859859e](https://linux-hardware.org/?probe=8cc859859e) | Nov 28, 2018 |
| ASUSTek       | P5K PRO                     | Desktop     | [a92cebea4d](https://linux-hardware.org/?probe=a92cebea4d) | Nov 28, 2018 |
| Acer          | Aspire 5750ZG               | Notebook    | [d138e04435](https://linux-hardware.org/?probe=d138e04435) | Nov 27, 2018 |
| Acer          | Aspire 5750ZG               | Notebook    | [516c88099e](https://linux-hardware.org/?probe=516c88099e) | Nov 23, 2018 |
| Lenovo        | B590 20206                  | Notebook    | [0cd011a796](https://linux-hardware.org/?probe=0cd011a796) | Nov 14, 2018 |
| Dell          | Inspiron M5010              | Notebook    | [2457e3698d](https://linux-hardware.org/?probe=2457e3698d) | Nov 05, 2018 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [a196f24690](https://linux-hardware.org/?probe=a196f24690) | Nov 01, 2018 |
| Toshiba       | Satellite A215              | Notebook    | [8bf0975fb2](https://linux-hardware.org/?probe=8bf0975fb2) | Oct 31, 2018 |
| Lenovo        | G700 20251                  | Notebook    | [e8d909b0fa](https://linux-hardware.org/?probe=e8d909b0fa) | Oct 27, 2018 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [fddef6b216](https://linux-hardware.org/?probe=fddef6b216) | Oct 25, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2d1c5d19bf](https://linux-hardware.org/?probe=2d1c5d19bf) | Oct 25, 2018 |
| ASUSTek       | U32VJ                       | Notebook    | [a1d3315657](https://linux-hardware.org/?probe=a1d3315657) | Oct 24, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0a670684fa](https://linux-hardware.org/?probe=0a670684fa) | Oct 24, 2018 |
| Lenovo        | G700 20251                  | Notebook    | [c556cef805](https://linux-hardware.org/?probe=c556cef805) | Oct 19, 2018 |
| Intel         | SKYBAY                      | Desktop     | [00c8a206a0](https://linux-hardware.org/?probe=00c8a206a0) | Oct 19, 2018 |
| Acer          | Aspire ES1-520              | Notebook    | [7734a8cc4b](https://linux-hardware.org/?probe=7734a8cc4b) | Oct 19, 2018 |
| Toshiba       | Satellite L650              | Notebook    | [3c94da7bb6](https://linux-hardware.org/?probe=3c94da7bb6) | Oct 17, 2018 |
| Gigabyte      | M61PME-S2                   | Desktop     | [c1bd028326](https://linux-hardware.org/?probe=c1bd028326) | Oct 17, 2018 |
| Samsung       | RV413/RV513                 | Notebook    | [6045dbdc70](https://linux-hardware.org/?probe=6045dbdc70) | Oct 14, 2018 |
| Lenovo        | V580c 20160                 | Notebook    | [9322372044](https://linux-hardware.org/?probe=9322372044) | Oct 05, 2018 |
| ASUSTek       | X55A                        | Notebook    | [5137394ef1](https://linux-hardware.org/?probe=5137394ef1) | Oct 04, 2018 |
| HP            | Pavilion dv6                | Notebook    | [b4469a7aa8](https://linux-hardware.org/?probe=b4469a7aa8) | Oct 02, 2018 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [94ac1919d7](https://linux-hardware.org/?probe=94ac1919d7) | Sep 22, 2018 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [392729da7e](https://linux-hardware.org/?probe=392729da7e) | Sep 21, 2018 |
| ASUSTek       | K42Jr                       | Notebook    | [4f4c1ec561](https://linux-hardware.org/?probe=4f4c1ec561) | Sep 19, 2018 |
| ASUSTek       | A68HM-K                     | Desktop     | [b1808c2eb4](https://linux-hardware.org/?probe=b1808c2eb4) | Sep 18, 2018 |
| Samsung       | RV413/RV513                 | Notebook    | [074d9a8a6c](https://linux-hardware.org/?probe=074d9a8a6c) | Sep 15, 2018 |
| HP            | ProBook 450 G1              | Notebook    | [a451edb119](https://linux-hardware.org/?probe=a451edb119) | Sep 15, 2018 |
| ASUSTek       | K54L                        | Notebook    | [5db2420e7b](https://linux-hardware.org/?probe=5db2420e7b) | Sep 15, 2018 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e2a67e2574](https://linux-hardware.org/?probe=e2a67e2574) | Sep 09, 2018 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [9e22b8f4c0](https://linux-hardware.org/?probe=9e22b8f4c0) | Sep 06, 2018 |
| Samsung       | RV408/RV508                 | Notebook    | [0fcb4ce699](https://linux-hardware.org/?probe=0fcb4ce699) | Sep 06, 2018 |
| ASUSTek       | P5B SE                      | Desktop     | [46ab71b84f](https://linux-hardware.org/?probe=46ab71b84f) | Sep 04, 2018 |
| Acer          | Extensa 5620                | Notebook    | [59004a5a4d](https://linux-hardware.org/?probe=59004a5a4d) | Aug 28, 2018 |
| Nvidia        | NF-MCP61                    | Desktop     | [92a93942ed](https://linux-hardware.org/?probe=92a93942ed) | Aug 27, 2018 |
| MSI           | MS-7922                     | Desktop     | [77fd2cc323](https://linux-hardware.org/?probe=77fd2cc323) | Aug 23, 2018 |
| ZOTAC         | NM10                        | Desktop     | [e9be5383cf](https://linux-hardware.org/?probe=e9be5383cf) | Aug 22, 2018 |
| HP            | Presario CQ57               | Notebook    | [983b775183](https://linux-hardware.org/?probe=983b775183) | Aug 18, 2018 |
| Acer          | Extensa 5220                | Notebook    | [953f048aa5](https://linux-hardware.org/?probe=953f048aa5) | Aug 12, 2018 |
| Samsung       | N100SP                      | Notebook    | [ef7b7f37ee](https://linux-hardware.org/?probe=ef7b7f37ee) | Aug 07, 2018 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [ac4484fb91](https://linux-hardware.org/?probe=ac4484fb91) | Aug 06, 2018 |
| ASRock        | N68C-S UCC                  | Desktop     | [b3239b74e2](https://linux-hardware.org/?probe=b3239b74e2) | Aug 06, 2018 |
| Lenovo        | G50-30 80G0                 | Notebook    | [b64c5d0ebc](https://linux-hardware.org/?probe=b64c5d0ebc) | Jul 24, 2018 |
| Acer          | Aspire E1-571G              | Notebook    | [86481cccd4](https://linux-hardware.org/?probe=86481cccd4) | Jul 22, 2018 |
| HP            | ProBook 455 G1              | Notebook    | [ca9f342b1a](https://linux-hardware.org/?probe=ca9f342b1a) | Jul 19, 2018 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [3fb448c842](https://linux-hardware.org/?probe=3fb448c842) | Jul 18, 2018 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [f0bef09470](https://linux-hardware.org/?probe=f0bef09470) | Jul 13, 2018 |
| HP            | Laptop 15-bs0xx             | Notebook    | [069c204d22](https://linux-hardware.org/?probe=069c204d22) | Jul 09, 2018 |
| Gigabyte      | 970A-DS3                    | Desktop     | [a8cb099c5a](https://linux-hardware.org/?probe=a8cb099c5a) | Jul 06, 2018 |
| Lenovo        | G700 20251                  | Notebook    | [8f57f46f49](https://linux-hardware.org/?probe=8f57f46f49) | Jun 26, 2018 |
| HP            | ProBook 4530s               | Notebook    | [993712a06c](https://linux-hardware.org/?probe=993712a06c) | Jun 21, 2018 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [2ce150a93d](https://linux-hardware.org/?probe=2ce150a93d) | Jun 20, 2018 |
| MSI           | MS-7309                     | Desktop     | [85c343f098](https://linux-hardware.org/?probe=85c343f098) | Jun 20, 2018 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1558d7c30e](https://linux-hardware.org/?probe=1558d7c30e) | Jun 10, 2018 |
| Samsung       | N100SP                      | Notebook    | [b9449f3937](https://linux-hardware.org/?probe=b9449f3937) | Jun 03, 2018 |
| ASUSTek       | X502CA                      | Notebook    | [2867d3e608](https://linux-hardware.org/?probe=2867d3e608) | Jun 03, 2018 |
| ASUSTek       | X502CA                      | Notebook    | [c0ca1e77e7](https://linux-hardware.org/?probe=c0ca1e77e7) | Jun 02, 2018 |
| ASRock        | N68C-GS FX                  | Desktop     | [a742697557](https://linux-hardware.org/?probe=a742697557) | May 28, 2018 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [c49afc2dd2](https://linux-hardware.org/?probe=c49afc2dd2) | May 28, 2018 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [493526b0cd](https://linux-hardware.org/?probe=493526b0cd) | May 27, 2018 |
| ASRock        | N68C-GS FX                  | Desktop     | [6ba14be353](https://linux-hardware.org/?probe=6ba14be353) | May 18, 2018 |
| Acer          | Aspire E1-571G              | Notebook    | [d850e72e1e](https://linux-hardware.org/?probe=d850e72e1e) | May 16, 2018 |
| Sony          | VGN-FW235J                  | Notebook    | [9320f505e2](https://linux-hardware.org/?probe=9320f505e2) | May 15, 2018 |
| ASUSTek       | P5P800-MX                   | Desktop     | [f1ce220fd5](https://linux-hardware.org/?probe=f1ce220fd5) | May 15, 2018 |
| ASUSTek       | P5P800-MX                   | Desktop     | [060a56de61](https://linux-hardware.org/?probe=060a56de61) | May 15, 2018 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3a38db14d4](https://linux-hardware.org/?probe=3a38db14d4) | May 11, 2018 |
| ASRock        | A780LM-S                    | Desktop     | [5b53dd6dd0](https://linux-hardware.org/?probe=5b53dd6dd0) | May 05, 2018 |
| Nvidia        | NF-MCP61                    | Desktop     | [65c435fd00](https://linux-hardware.org/?probe=65c435fd00) | Apr 29, 2018 |
| ASRock        | G31M-VS2                    | Desktop     | [37efe4e43f](https://linux-hardware.org/?probe=37efe4e43f) | Apr 28, 2018 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [f3c9a3eb76](https://linux-hardware.org/?probe=f3c9a3eb76) | Apr 24, 2018 |
| ASUSTek       | K53E                        | Notebook    | [e590bb8d6f](https://linux-hardware.org/?probe=e590bb8d6f) | Apr 23, 2018 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [dff9b15427](https://linux-hardware.org/?probe=dff9b15427) | Apr 22, 2018 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [d5a992e215](https://linux-hardware.org/?probe=d5a992e215) | Apr 20, 2018 |
| Acer          | Aspire 3810TZ               | Notebook    | [a02d089fef](https://linux-hardware.org/?probe=a02d089fef) | Apr 19, 2018 |
| Lenovo        | G50-80 80E5                 | Notebook    | [fbd53229e1](https://linux-hardware.org/?probe=fbd53229e1) | Apr 17, 2018 |
| MSI           | MS-7309 10                  | Desktop     | [71b8fc0632](https://linux-hardware.org/?probe=71b8fc0632) | Apr 16, 2018 |
| MSI           | MS-7309 10                  | Desktop     | [7b960f4558](https://linux-hardware.org/?probe=7b960f4558) | Apr 16, 2018 |
| ASUSTek       | VM60                        | Desktop     | [c123099e37](https://linux-hardware.org/?probe=c123099e37) | Apr 15, 2018 |
| ASUSTek       | VM60                        | Desktop     | [bd1d814d83](https://linux-hardware.org/?probe=bd1d814d83) | Apr 15, 2018 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [c44fded5bf](https://linux-hardware.org/?probe=c44fded5bf) | Apr 12, 2018 |
| Lenovo        | G50-30 80G0                 | Notebook    | [e0a99c9020](https://linux-hardware.org/?probe=e0a99c9020) | Apr 11, 2018 |
| ASUSTek       | 1005PX                      | Notebook    | [3bd5d73da2](https://linux-hardware.org/?probe=3bd5d73da2) | Apr 09, 2018 |
| Lenovo        | G505 20240                  | Notebook    | [94360ae24c](https://linux-hardware.org/?probe=94360ae24c) | Apr 07, 2018 |
| Prestigio     | PNT10130C                   | Convertible | [00d3ef2d8a](https://linux-hardware.org/?probe=00d3ef2d8a) | Apr 05, 2018 |
| ASUSTek       | X551MA                      | Notebook    | [a941a24e7c](https://linux-hardware.org/?probe=a941a24e7c) | Mar 29, 2018 |
| HP            | ProBook 4540s               | Notebook    | [c79bd3efcd](https://linux-hardware.org/?probe=c79bd3efcd) | Mar 28, 2018 |
| ASRock        | A780LM-S                    | Desktop     | [aa1be7d4e9](https://linux-hardware.org/?probe=aa1be7d4e9) | Mar 25, 2018 |
| Acer          | Aspire ES1-523              | Notebook    | [d3f9785c45](https://linux-hardware.org/?probe=d3f9785c45) | Mar 25, 2018 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [27e9317f47](https://linux-hardware.org/?probe=27e9317f47) | Mar 22, 2018 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [7190c0818e](https://linux-hardware.org/?probe=7190c0818e) | Mar 18, 2018 |
| Gigabyte      | GA-A75-D3H                  | Desktop     | [235900b4b2](https://linux-hardware.org/?probe=235900b4b2) | Mar 17, 2018 |
| Dell          | Inspiron 1521               | Notebook    | [ceed13b4fc](https://linux-hardware.org/?probe=ceed13b4fc) | Mar 15, 2018 |
| Toshiba       | Satellite L650              | Notebook    | [15735e6616](https://linux-hardware.org/?probe=15735e6616) | Mar 08, 2018 |
| Dell          | Latitude E6410              | Notebook    | [c714bf47fb](https://linux-hardware.org/?probe=c714bf47fb) | Mar 08, 2018 |
| Apple         | MacBookPro9,2               | Notebook    | [93a5831bf0](https://linux-hardware.org/?probe=93a5831bf0) | Mar 07, 2018 |
| Toshiba       | PLCSF                       | Notebook    | [b2185404aa](https://linux-hardware.org/?probe=b2185404aa) | Mar 07, 2018 |
| ASUSTek       | UL30A                       | Notebook    | [921f5d069e](https://linux-hardware.org/?probe=921f5d069e) | Mar 04, 2018 |
| ASUSTek       | UL30A                       | Notebook    | [0baf4ccbe8](https://linux-hardware.org/?probe=0baf4ccbe8) | Mar 04, 2018 |
| ASUSTek       | K50IJ                       | Notebook    | [4ab4ba786a](https://linux-hardware.org/?probe=4ab4ba786a) | Mar 03, 2018 |
| Sony          | VGN-FW235J                  | Notebook    | [8b36bcb7f3](https://linux-hardware.org/?probe=8b36bcb7f3) | Feb 26, 2018 |
| Gigabyte      | P31-DS3L                    | Desktop     | [c1417adcb7](https://linux-hardware.org/?probe=c1417adcb7) | Feb 26, 2018 |
| Gigabyte      | B85M-HD3                    | Desktop     | [3202c90e49](https://linux-hardware.org/?probe=3202c90e49) | Feb 25, 2018 |
| ASUSTek       | X540LJ                      | Notebook    | [1e9c4a36ab](https://linux-hardware.org/?probe=1e9c4a36ab) | Feb 20, 2018 |
| ASUSTek       | P5B SE                      | Desktop     | [cda181fdbf](https://linux-hardware.org/?probe=cda181fdbf) | Feb 17, 2018 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [ebdd218c0a](https://linux-hardware.org/?probe=ebdd218c0a) | Feb 17, 2018 |
| ASUSTek       | M2N-MX                      | Desktop     | [586a8fc1a0](https://linux-hardware.org/?probe=586a8fc1a0) | Feb 16, 2018 |
| HP            | 655                         | Notebook    | [7d65695404](https://linux-hardware.org/?probe=7d65695404) | Feb 13, 2018 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [72636405d7](https://linux-hardware.org/?probe=72636405d7) | Feb 11, 2018 |
| ASUSTek       | P5B                         | Desktop     | [64a6603145](https://linux-hardware.org/?probe=64a6603145) | Feb 11, 2018 |
| ASUSTek       | A88XM-A                     | Desktop     | [3694e448ee](https://linux-hardware.org/?probe=3694e448ee) | Feb 09, 2018 |
| Fujitsu Si... | LIFEBOOK S6410              | Notebook    | [0ce4f9b4f0](https://linux-hardware.org/?probe=0ce4f9b4f0) | Feb 09, 2018 |
| ASUSTek       | P5K PRO                     | Desktop     | [fb241733d7](https://linux-hardware.org/?probe=fb241733d7) | Feb 08, 2018 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [e4820de986](https://linux-hardware.org/?probe=e4820de986) | Feb 08, 2018 |
| MSI           | CR500                       | Notebook    | [34f7962c46](https://linux-hardware.org/?probe=34f7962c46) | Feb 06, 2018 |
| Acer          | Aspire E1-532G              | Notebook    | [fafd8a85b2](https://linux-hardware.org/?probe=fafd8a85b2) | Feb 01, 2018 |
| MSI           | MS-7250                     | Desktop     | [00cf2d12a7](https://linux-hardware.org/?probe=00cf2d12a7) | Jan 29, 2018 |
| MSI           | MS-7250                     | Desktop     | [e7ad29832b](https://linux-hardware.org/?probe=e7ad29832b) | Jan 29, 2018 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [7fd5e7b200](https://linux-hardware.org/?probe=7fd5e7b200) | Jan 28, 2018 |
| MSI           | MS-7369                     | Desktop     | [67881bd907](https://linux-hardware.org/?probe=67881bd907) | Jan 27, 2018 |
| Intel         | Pine Trail - M Revision ... | Notebook    | [65eaa7c7b0](https://linux-hardware.org/?probe=65eaa7c7b0) | Jan 26, 2018 |
| ASUSTek       | P4S800-MX SE                | Desktop     | [fa04955b88](https://linux-hardware.org/?probe=fa04955b88) | Jan 22, 2018 |
| HP            | 625                         | Notebook    | [249a8b5fdd](https://linux-hardware.org/?probe=249a8b5fdd) | Jan 20, 2018 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [213e2f388c](https://linux-hardware.org/?probe=213e2f388c) | Jan 20, 2018 |
| HP            | 655                         | Notebook    | [0b1492a552](https://linux-hardware.org/?probe=0b1492a552) | Jan 19, 2018 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4bd68b7165](https://linux-hardware.org/?probe=4bd68b7165) | Jan 18, 2018 |
| HP            | ProBook 4545s               | Notebook    | [7d82dfba11](https://linux-hardware.org/?probe=7d82dfba11) | Jan 18, 2018 |
| Dell          | Inspiron 5547               | Notebook    | [fab8b9e9b9](https://linux-hardware.org/?probe=fab8b9e9b9) | Jan 18, 2018 |
| Dell          | Inspiron 5547               | Notebook    | [c01a939820](https://linux-hardware.org/?probe=c01a939820) | Jan 17, 2018 |
| ASRock        | FM2A55 Pro+                 | Desktop     | [5eeb1370c2](https://linux-hardware.org/?probe=5eeb1370c2) | Jan 17, 2018 |
| Acer          | Aspire V5-123               | Notebook    | [bcd1391d57](https://linux-hardware.org/?probe=bcd1391d57) | Jan 16, 2018 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [3880e14ae9](https://linux-hardware.org/?probe=3880e14ae9) | Jan 16, 2018 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [f57558ef8e](https://linux-hardware.org/?probe=f57558ef8e) | Jan 15, 2018 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [400fef0f85](https://linux-hardware.org/?probe=400fef0f85) | Jan 14, 2018 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [c8b498a8d0](https://linux-hardware.org/?probe=c8b498a8d0) | Jan 14, 2018 |
| HP            | Pavilion dv6                | Notebook    | [3fbd1376b7](https://linux-hardware.org/?probe=3fbd1376b7) | Jan 09, 2018 |
| Samsung       | RV413/RV513                 | Notebook    | [7ca80b846a](https://linux-hardware.org/?probe=7ca80b846a) | Jan 07, 2018 |
| HP            | Pavilion dv6                | Notebook    | [0810aed827](https://linux-hardware.org/?probe=0810aed827) | Jan 07, 2018 |
| HP            | 655                         | Notebook    | [dde30fdece](https://linux-hardware.org/?probe=dde30fdece) | Jan 06, 2018 |
| HP            | 655                         | Notebook    | [00bccddf88](https://linux-hardware.org/?probe=00bccddf88) | Jan 06, 2018 |
| ASUSTek       | 1015PW                      | Notebook    | [b3bc5400d4](https://linux-hardware.org/?probe=b3bc5400d4) | Jan 06, 2018 |
| HP            | Pavilion dv6                | Notebook    | [f8e6613c03](https://linux-hardware.org/?probe=f8e6613c03) | Jan 06, 2018 |
| Lenovo        | B50-30 20382                | Notebook    | [6804eb0dbd](https://linux-hardware.org/?probe=6804eb0dbd) | Jan 06, 2018 |
| HP            | ProBook 4545s               | Notebook    | [331866b4c7](https://linux-hardware.org/?probe=331866b4c7) | Jan 03, 2018 |
| Gigabyte      | M4HM87P-00                  | Desktop     | [518ffe426a](https://linux-hardware.org/?probe=518ffe426a) | Dec 31, 2017 |
| HP            | ProBook 4545s               | Notebook    | [10c7a2f540](https://linux-hardware.org/?probe=10c7a2f540) | Dec 30, 2017 |
| Dell          | Inspiron 1011               | Notebook    | [c66fdb41dd](https://linux-hardware.org/?probe=c66fdb41dd) | Dec 29, 2017 |
| Dell          | Inspiron 1011               | Notebook    | [4fbadfa275](https://linux-hardware.org/?probe=4fbadfa275) | Dec 29, 2017 |
| Lenovo        | G570 20079                  | Notebook    | [bdd7629c53](https://linux-hardware.org/?probe=bdd7629c53) | Dec 26, 2017 |
| HP            | Presario CQ56               | Notebook    | [55af7d7fe8](https://linux-hardware.org/?probe=55af7d7fe8) | Dec 24, 2017 |
| Samsung       | 730U3E/740U3E               | Notebook    | [7012ff7276](https://linux-hardware.org/?probe=7012ff7276) | Dec 22, 2017 |
| ASRock        | G31M-S                      | Desktop     | [6bf5a923b3](https://linux-hardware.org/?probe=6bf5a923b3) | Dec 20, 2017 |
| ASRock        | G31M-S                      | Desktop     | [57cbfce000](https://linux-hardware.org/?probe=57cbfce000) | Dec 20, 2017 |
| ASUSTek       | M2N-E                       | Desktop     | [7a7af75075](https://linux-hardware.org/?probe=7a7af75075) | Dec 19, 2017 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [855c603767](https://linux-hardware.org/?probe=855c603767) | Dec 17, 2017 |
| Lenovo        | G505 20240                  | Notebook    | [7d9cdbcb00](https://linux-hardware.org/?probe=7d9cdbcb00) | Dec 16, 2017 |
| ASRock        | N68C-GS FX                  | Desktop     | [c88c80e415](https://linux-hardware.org/?probe=c88c80e415) | Dec 14, 2017 |
| ASRock        | Z97M Pro4                   | Desktop     | [beedba2b85](https://linux-hardware.org/?probe=beedba2b85) | Dec 13, 2017 |
| ASUSTek       | P4S800-MX SE                | Desktop     | [c34c626f63](https://linux-hardware.org/?probe=c34c626f63) | Dec 13, 2017 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [3547011cc9](https://linux-hardware.org/?probe=3547011cc9) | Dec 07, 2017 |
| Acer          | Aspire E1-731               | Notebook    | [784a423bb4](https://linux-hardware.org/?probe=784a423bb4) | Dec 06, 2017 |
| Acer          | Aspire 5715Z                | Notebook    | [4a8d94b93c](https://linux-hardware.org/?probe=4a8d94b93c) | Dec 03, 2017 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [3aac9757b6](https://linux-hardware.org/?probe=3aac9757b6) | Dec 03, 2017 |
| Lenovo        | G580 20157                  | Notebook    | [1e8e60ca9b](https://linux-hardware.org/?probe=1e8e60ca9b) | Nov 30, 2017 |
| Acer          | Aspire E1-530               | Notebook    | [4c35840f32](https://linux-hardware.org/?probe=4c35840f32) | Nov 30, 2017 |
| Lenovo        | G580 20157                  | Notebook    | [f1fe4f2dcf](https://linux-hardware.org/?probe=f1fe4f2dcf) | Nov 29, 2017 |
| MSI           | K9A2GM V3                   | Desktop     | [b340e7a1b4](https://linux-hardware.org/?probe=b340e7a1b4) | Nov 29, 2017 |
| ASRock        | Z77 Extreme4-M              | Desktop     | [9a96bd84af](https://linux-hardware.org/?probe=9a96bd84af) | Nov 28, 2017 |
| Lenovo        | Remore CRB No DPK           | All in one  | [f0735457a7](https://linux-hardware.org/?probe=f0735457a7) | Nov 27, 2017 |
| Lenovo        | G50-30 80G0                 | Notebook    | [46cc147da2](https://linux-hardware.org/?probe=46cc147da2) | Nov 23, 2017 |
| Acer          | Aspire E1-530               | Notebook    | [928cb28dfb](https://linux-hardware.org/?probe=928cb28dfb) | Nov 23, 2017 |
| Gigabyte      | 945PL-S3                    | Desktop     | [28a334bdb8](https://linux-hardware.org/?probe=28a334bdb8) | Nov 21, 2017 |
| Lenovo        | ThinkPad SL510 2875RS2      | Notebook    | [bac0b17fd2](https://linux-hardware.org/?probe=bac0b17fd2) | Nov 16, 2017 |
| Gigabyte      | 945PL-S3                    | Desktop     | [82f58ad883](https://linux-hardware.org/?probe=82f58ad883) | Nov 16, 2017 |
| Gigabyte      | H81M-S2H                    | Desktop     | [eb798e5e53](https://linux-hardware.org/?probe=eb798e5e53) | Nov 15, 2017 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d0d8e703c3](https://linux-hardware.org/?probe=d0d8e703c3) | Nov 14, 2017 |
| Biostar       | N520D-A2                    | Desktop     | [b130eb7077](https://linux-hardware.org/?probe=b130eb7077) | Nov 11, 2017 |
| ASUSTek       | M2N-VM DVI                  | Desktop     | [85f6c5411f](https://linux-hardware.org/?probe=85f6c5411f) | Nov 08, 2017 |
| Dell          | Vostro A860                 | Notebook    | [2af75a3d92](https://linux-hardware.org/?probe=2af75a3d92) | Nov 07, 2017 |
| Acer          | TravelMate 5760             | Notebook    | [9c0d8f5802](https://linux-hardware.org/?probe=9c0d8f5802) | Nov 06, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [c7d2faa40e](https://linux-hardware.org/?probe=c7d2faa40e) | Nov 04, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [a9540b0804](https://linux-hardware.org/?probe=a9540b0804) | Nov 03, 2017 |
| ASUSTek       | M2N-VM DVI                  | Desktop     | [09112fec20](https://linux-hardware.org/?probe=09112fec20) | Nov 02, 2017 |
| MSI           | U90/U100                    | Notebook    | [2c8b8dc1fb](https://linux-hardware.org/?probe=2c8b8dc1fb) | Oct 30, 2017 |
| Samsung       | R508                        | Notebook    | [cd09147d1a](https://linux-hardware.org/?probe=cd09147d1a) | Oct 26, 2017 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [fa20a27efd](https://linux-hardware.org/?probe=fa20a27efd) | Oct 17, 2017 |
| HP            | Pavilion g6                 | Notebook    | [ad6ea79e40](https://linux-hardware.org/?probe=ad6ea79e40) | Oct 15, 2017 |
| ASRock        | Z77 Extreme4-M              | Desktop     | [66a51f97dc](https://linux-hardware.org/?probe=66a51f97dc) | Oct 15, 2017 |
| ASUSTek       | M2N-VM DVI                  | Desktop     | [89e0964dc9](https://linux-hardware.org/?probe=89e0964dc9) | Oct 14, 2017 |
| ASUSTek       | X553MA                      | Notebook    | [566133cd83](https://linux-hardware.org/?probe=566133cd83) | Sep 24, 2017 |
| Gigabyte      | GA-A75-D3H                  | Desktop     | [6d696fe86b](https://linux-hardware.org/?probe=6d696fe86b) | Sep 20, 2017 |
| Acer          | TravelMate 5760             | Notebook    | [6ee2556405](https://linux-hardware.org/?probe=6ee2556405) | Sep 16, 2017 |
| Acer          | Extensa 5220                | Notebook    | [5abac2fefd](https://linux-hardware.org/?probe=5abac2fefd) | Sep 14, 2017 |
| MSI           | MS-7369                     | Desktop     | [70b368bd84](https://linux-hardware.org/?probe=70b368bd84) | Sep 12, 2017 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [e9e5ce8e71](https://linux-hardware.org/?probe=e9e5ce8e71) | Sep 10, 2017 |
| ASUSTek       | X540LJ                      | Notebook    | [f2e803d3b4](https://linux-hardware.org/?probe=f2e803d3b4) | Sep 07, 2017 |
| ASRock        | A75M-HVS                    | Desktop     | [9500615990](https://linux-hardware.org/?probe=9500615990) | Sep 06, 2017 |
| Gigabyte      | H81M-S2H                    | Desktop     | [29cbcdc9d8](https://linux-hardware.org/?probe=29cbcdc9d8) | Sep 05, 2017 |
| Dell          | Inspiron M5110              | Notebook    | [47d26c92c9](https://linux-hardware.org/?probe=47d26c92c9) | Sep 01, 2017 |
| HP            | ProBook 455 G1              | Notebook    | [065581e1a2](https://linux-hardware.org/?probe=065581e1a2) | Aug 31, 2017 |
| ASRock        | H61M-VG3                    | Desktop     | [c9d4e962d5](https://linux-hardware.org/?probe=c9d4e962d5) | Aug 29, 2017 |
| ASUSTek       | X550CC                      | Notebook    | [9417e4c182](https://linux-hardware.org/?probe=9417e4c182) | Aug 23, 2017 |
| Gigabyte      | 945PL-S3                    | Desktop     | [1d54471054](https://linux-hardware.org/?probe=1d54471054) | Aug 18, 2017 |
| ASRock        | H61M-VG4                    | Desktop     | [7eb620e199](https://linux-hardware.org/?probe=7eb620e199) | Aug 18, 2017 |
| Gigabyte      | H81M-S2H                    | Desktop     | [76e8046e3a](https://linux-hardware.org/?probe=76e8046e3a) | Aug 17, 2017 |
| MSI           | G41M-P28                    | Desktop     | [60a8e2650b](https://linux-hardware.org/?probe=60a8e2650b) | Aug 16, 2017 |
| MSI           | MS-7369                     | Desktop     | [5b8fc5f2a5](https://linux-hardware.org/?probe=5b8fc5f2a5) | Aug 16, 2017 |
| ASUSTek       | A6J                         | Notebook    | [f680730915](https://linux-hardware.org/?probe=f680730915) | Aug 14, 2017 |
| Gigabyte      | H81M-S2H                    | Desktop     | [4021bd50a2](https://linux-hardware.org/?probe=4021bd50a2) | Aug 14, 2017 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [eb120c5904](https://linux-hardware.org/?probe=eb120c5904) | Aug 07, 2017 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [835629a8a7](https://linux-hardware.org/?probe=835629a8a7) | Aug 02, 2017 |
| ASUSTek       | X550MJ                      | Notebook    | [62be56c501](https://linux-hardware.org/?probe=62be56c501) | Jul 31, 2017 |
| HP            | ProBook 455 G1              | Notebook    | [bd1f5d775f](https://linux-hardware.org/?probe=bd1f5d775f) | Jul 29, 2017 |
| MSI           | 880GMS-E35                  | Desktop     | [fb3a9b38ae](https://linux-hardware.org/?probe=fb3a9b38ae) | Jul 25, 2017 |
| Gigabyte      | 945PL-S3                    | Desktop     | [28f8ab3aa3](https://linux-hardware.org/?probe=28f8ab3aa3) | Jul 25, 2017 |
| Gigabyte      | G31M-S2L                    | Desktop     | [c40f9d969e](https://linux-hardware.org/?probe=c40f9d969e) | Jul 23, 2017 |
| Gigabyte      | G31M-S2L                    | Desktop     | [bb1624ea3a](https://linux-hardware.org/?probe=bb1624ea3a) | Jul 21, 2017 |
| Lenovo        | B590 20206                  | Notebook    | [06b36668b9](https://linux-hardware.org/?probe=06b36668b9) | Jul 18, 2017 |
| ASUSTek       | N55SL                       | Notebook    | [fe8018c4c4](https://linux-hardware.org/?probe=fe8018c4c4) | Jul 15, 2017 |
| Acer          | TravelMate 5760             | Notebook    | [d04461240c](https://linux-hardware.org/?probe=d04461240c) | Jul 08, 2017 |
| HP            | Presario CQ56               | Notebook    | [de976cca7a](https://linux-hardware.org/?probe=de976cca7a) | Jul 08, 2017 |
| ASUSTek       | A6J                         | Notebook    | [e417c347d8](https://linux-hardware.org/?probe=e417c347d8) | Jul 04, 2017 |
| ASUSTek       | A6J                         | Notebook    | [cd68b9194b](https://linux-hardware.org/?probe=cd68b9194b) | Jul 03, 2017 |
| ASUSTek       | A6J                         | Notebook    | [e591d8bdd0](https://linux-hardware.org/?probe=e591d8bdd0) | Jul 03, 2017 |
| Lenovo        | G50-30 80G0                 | Notebook    | [83327d6299](https://linux-hardware.org/?probe=83327d6299) | Jul 03, 2017 |
| ASUSTek       | A6J                         | Notebook    | [ef5284d65a](https://linux-hardware.org/?probe=ef5284d65a) | Jul 03, 2017 |
| ASUSTek       | M2N-E                       | Desktop     | [535b9a0e13](https://linux-hardware.org/?probe=535b9a0e13) | Jul 03, 2017 |
| MSI           | CR650                       | Notebook    | [bb97b32449](https://linux-hardware.org/?probe=bb97b32449) | Jul 03, 2017 |
| ASUSTek       | A6J                         | Notebook    | [4cb6f17eb2](https://linux-hardware.org/?probe=4cb6f17eb2) | Jul 01, 2017 |
| ASUSTek       | 1011PX                      | Notebook    | [b4698e905d](https://linux-hardware.org/?probe=b4698e905d) | Jun 29, 2017 |
| ASUSTek       | H81M-K                      | Desktop     | [4081269972](https://linux-hardware.org/?probe=4081269972) | Jun 21, 2017 |
| Dell          | System XPS L702X            | Notebook    | [791ca50070](https://linux-hardware.org/?probe=791ca50070) | Jun 14, 2017 |
| IBM           | ThinkPad X41 2525FAG        | Notebook    | [671ec7621b](https://linux-hardware.org/?probe=671ec7621b) | Jun 13, 2017 |
| Foxconn       | G41MXP/G41MXP-V             | Desktop     | [6ca14da0fa](https://linux-hardware.org/?probe=6ca14da0fa) | Jun 13, 2017 |
| ASUSTek       | N55SL                       | Notebook    | [ae2875f46b](https://linux-hardware.org/?probe=ae2875f46b) | Jun 12, 2017 |
| ASUSTek       | B85M-G                      | Desktop     | [019ca7700b](https://linux-hardware.org/?probe=019ca7700b) | Jun 11, 2017 |
| ASUSTek       | A88XM-A                     | Desktop     | [d8164c7f9b](https://linux-hardware.org/?probe=d8164c7f9b) | Jun 11, 2017 |
| Lenovo        | G50-30 80G0                 | Notebook    | [58235630a7](https://linux-hardware.org/?probe=58235630a7) | Jun 11, 2017 |
| HP            | Pavilion g6                 | Notebook    | [897e37b204](https://linux-hardware.org/?probe=897e37b204) | Jun 10, 2017 |
| ASRock        | Z87 Pro4                    | Desktop     | [97b7d095b4](https://linux-hardware.org/?probe=97b7d095b4) | Jun 02, 2017 |
| Toshiba       | Satellite L50-A-K3S         | Notebook    | [6c7996782a](https://linux-hardware.org/?probe=6c7996782a) | Jun 01, 2017 |
| ASUSTek       | F1A55-M LE R2.0             | Desktop     | [e8697ba8fa](https://linux-hardware.org/?probe=e8697ba8fa) | Jun 01, 2017 |
| IBM           | ThinkPad X41 2525FAG        | Notebook    | [b69e0c7e24](https://linux-hardware.org/?probe=b69e0c7e24) | May 27, 2017 |
| Lenovo        | G500 20236                  | Notebook    | [8fc07a6f38](https://linux-hardware.org/?probe=8fc07a6f38) | May 26, 2017 |
| ASUSTek       | A88XM-A                     | Desktop     | [eea79c39d3](https://linux-hardware.org/?probe=eea79c39d3) | May 24, 2017 |
| HP            | ProBook 6570b               | Notebook    | [a5fcc33bca](https://linux-hardware.org/?probe=a5fcc33bca) | May 23, 2017 |
| Acer          | Extensa 5220                | Notebook    | [986f64cc82](https://linux-hardware.org/?probe=986f64cc82) | May 22, 2017 |
| Acer          | Extensa 5220                | Notebook    | [94ac9a45f4](https://linux-hardware.org/?probe=94ac9a45f4) | May 22, 2017 |
| Gigabyte      | M68M-S2P                    | Desktop     | [8713e6047d](https://linux-hardware.org/?probe=8713e6047d) | May 20, 2017 |
| Acer          | Extensa 5230                | Notebook    | [5d9b4a011a](https://linux-hardware.org/?probe=5d9b4a011a) | May 19, 2017 |
| HP            | ProBook 455 G1              | Notebook    | [d986e13cd8](https://linux-hardware.org/?probe=d986e13cd8) | May 17, 2017 |
| ASUSTek       | P8H77-V                     | Desktop     | [17efba7efa](https://linux-hardware.org/?probe=17efba7efa) | May 15, 2017 |
| MSI           | MS-7235                     | Desktop     | [d02a8f3ba9](https://linux-hardware.org/?probe=d02a8f3ba9) | May 14, 2017 |
| MSI           | MS-7235                     | Desktop     | [4960ca8e5b](https://linux-hardware.org/?probe=4960ca8e5b) | May 14, 2017 |
| Dell          | Inspiron 14-3452            | Notebook    | [f2e5a3b622](https://linux-hardware.org/?probe=f2e5a3b622) | May 12, 2017 |
| Acer          | TravelMate 2490             | Notebook    | [b26e098033](https://linux-hardware.org/?probe=b26e098033) | May 11, 2017 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [050ee437d3](https://linux-hardware.org/?probe=050ee437d3) | May 07, 2017 |
| ASRock        | H81M-VG4 R3.0               | Desktop     | [04edba406f](https://linux-hardware.org/?probe=04edba406f) | May 03, 2017 |
| MSI           | MS-7507                     | Desktop     | [949758a7bb](https://linux-hardware.org/?probe=949758a7bb) | May 02, 2017 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [6f7f681b65](https://linux-hardware.org/?probe=6f7f681b65) | Apr 29, 2017 |
| HP            | Pavilion dv7                | Notebook    | [2db47d03ca](https://linux-hardware.org/?probe=2db47d03ca) | Apr 27, 2017 |
| MSI           | MS-7507                     | Desktop     | [2ceaf8753e](https://linux-hardware.org/?probe=2ceaf8753e) | Apr 26, 2017 |
| Gigabyte      | GA-A75-D3H                  | Desktop     | [8b50649a40](https://linux-hardware.org/?probe=8b50649a40) | Apr 22, 2017 |
| Acer          | Aspire 7552                 | Notebook    | [e54de6ed57](https://linux-hardware.org/?probe=e54de6ed57) | Apr 19, 2017 |
| Biostar       | TZ77B                       | Desktop     | [6933983fab](https://linux-hardware.org/?probe=6933983fab) | Apr 14, 2017 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a85e718859](https://linux-hardware.org/?probe=a85e718859) | Apr 11, 2017 |
| ASUSTek       | K53U                        | Notebook    | [8250fd2ed0](https://linux-hardware.org/?probe=8250fd2ed0) | Apr 11, 2017 |
| Samsung       | R710                        | Notebook    | [7694ff8186](https://linux-hardware.org/?probe=7694ff8186) | Apr 09, 2017 |
| Acer          | Aspire E1-531               | Notebook    | [abadda8c39](https://linux-hardware.org/?probe=abadda8c39) | Apr 09, 2017 |
| ViewSonic     | ViewBook                    | Notebook    | [510f3cfb16](https://linux-hardware.org/?probe=510f3cfb16) | Apr 09, 2017 |
| Gigabyte      | GA-A75-D3H                  | Desktop     | [3b7982d37e](https://linux-hardware.org/?probe=3b7982d37e) | Apr 08, 2017 |
| MSI           | 870-C45                     | Desktop     | [425f287926](https://linux-hardware.org/?probe=425f287926) | Apr 04, 2017 |
| ASRock        | Z77 Extreme4-M              | Desktop     | [b0529aa0d7](https://linux-hardware.org/?probe=b0529aa0d7) | Mar 28, 2017 |
| MSI           | MS-7369                     | Desktop     | [34d1480ef5](https://linux-hardware.org/?probe=34d1480ef5) | Mar 26, 2017 |
| Samsung       | R508                        | Notebook    | [0cf5690d55](https://linux-hardware.org/?probe=0cf5690d55) | Mar 26, 2017 |
| Lenovo        | G580 20150                  | Notebook    | [5fc4eab41d](https://linux-hardware.org/?probe=5fc4eab41d) | Mar 26, 2017 |
| ASUSTek       | H81M-K                      | Desktop     | [8f8055f6cd](https://linux-hardware.org/?probe=8f8055f6cd) | Mar 22, 2017 |
| MSI           | 0A90                        | Desktop     | [34768ffe2a](https://linux-hardware.org/?probe=34768ffe2a) | Mar 19, 2017 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [e67693985e](https://linux-hardware.org/?probe=e67693985e) | Mar 19, 2017 |
| HP            | Pavilion g7                 | Notebook    | [2c52ae0e3d](https://linux-hardware.org/?probe=2c52ae0e3d) | Mar 12, 2017 |
| ASUSTek       | X101CH                      | Notebook    | [c29cb19972](https://linux-hardware.org/?probe=c29cb19972) | Mar 12, 2017 |
| Gigabyte      | M68M-S2P                    | Desktop     | [e924c4feaf](https://linux-hardware.org/?probe=e924c4feaf) | Mar 10, 2017 |
| HP            | ProBook 4530s               | Notebook    | [b0cd8c5a7b](https://linux-hardware.org/?probe=b0cd8c5a7b) | Mar 05, 2017 |
| Lenovo        | G580 20157                  | Notebook    | [05b88b336c](https://linux-hardware.org/?probe=05b88b336c) | Mar 04, 2017 |
| HP            | Pavilion 15                 | Notebook    | [9371b21011](https://linux-hardware.org/?probe=9371b21011) | Feb 26, 2017 |
| ASUSTek       | B85-PLUS                    | Desktop     | [50d7b843c4](https://linux-hardware.org/?probe=50d7b843c4) | Feb 22, 2017 |
| ASUSTek       | B85-PLUS                    | Desktop     | [349264c475](https://linux-hardware.org/?probe=349264c475) | Feb 22, 2017 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [1e85560547](https://linux-hardware.org/?probe=1e85560547) | Feb 22, 2017 |
| Lenovo        | G570 20079                  | Notebook    | [ba04639760](https://linux-hardware.org/?probe=ba04639760) | Feb 18, 2017 |
| Lenovo        | G570 20079                  | Notebook    | [a399e00c28](https://linux-hardware.org/?probe=a399e00c28) | Feb 16, 2017 |
| Acer          | Aspire E1-531               | Notebook    | [57b6913eb0](https://linux-hardware.org/?probe=57b6913eb0) | Feb 16, 2017 |
| HP            | ProBook 4530s               | Notebook    | [f5e02506e2](https://linux-hardware.org/?probe=f5e02506e2) | Feb 15, 2017 |
| Lenovo        | G580 20150                  | Notebook    | [33ead87e53](https://linux-hardware.org/?probe=33ead87e53) | Feb 14, 2017 |
| Samsung       | 730U3E/740U3E               | Notebook    | [74ba47c62b](https://linux-hardware.org/?probe=74ba47c62b) | Feb 14, 2017 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [eccb2a2c63](https://linux-hardware.org/?probe=eccb2a2c63) | Feb 14, 2017 |
| DNS           | W9x0LU                      | Notebook    | [3f2e919f1f](https://linux-hardware.org/?probe=3f2e919f1f) | Feb 11, 2017 |
| Lenovo        | ThinkPad L420 7854RP1       | Notebook    | [f0510e8901](https://linux-hardware.org/?probe=f0510e8901) | Feb 08, 2017 |
| Acer          | Aspire 5551G                | Notebook    | [63ee188b0a](https://linux-hardware.org/?probe=63ee188b0a) | Feb 06, 2017 |
| Acer          | Aspire 4810T                | Notebook    | [e114bc3f93](https://linux-hardware.org/?probe=e114bc3f93) | Feb 06, 2017 |
| HP            | Mini 5102                   | Notebook    | [0d1332f164](https://linux-hardware.org/?probe=0d1332f164) | Feb 03, 2017 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [67f7100c09](https://linux-hardware.org/?probe=67f7100c09) | Jan 31, 2017 |
| ASUSTek       | K52Dr                       | Notebook    | [b34ce135d6](https://linux-hardware.org/?probe=b34ce135d6) | Jan 22, 2017 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [2dd2f77057](https://linux-hardware.org/?probe=2dd2f77057) | Jan 21, 2017 |
| MSI           | MS-7250                     | Desktop     | [0950917e81](https://linux-hardware.org/?probe=0950917e81) | Jan 20, 2017 |
| Acer          | TravelMate 5760             | Notebook    | [961b65d4ed](https://linux-hardware.org/?probe=961b65d4ed) | Jan 19, 2017 |
| Dell          | System XPS L702X            | Notebook    | [a1c104a5ee](https://linux-hardware.org/?probe=a1c104a5ee) | Jan 19, 2017 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [37e989c6f3](https://linux-hardware.org/?probe=37e989c6f3) | Jan 18, 2017 |
| ECS           | GeForce7050M-M              | Desktop     | [2322d5cb22](https://linux-hardware.org/?probe=2322d5cb22) | Jan 17, 2017 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [b21fc55767](https://linux-hardware.org/?probe=b21fc55767) | Jan 09, 2017 |
| ASUSTek       | X751LN                      | Notebook    | [e5a04c21f6](https://linux-hardware.org/?probe=e5a04c21f6) | Jan 09, 2017 |
| MSI           | G41M-P26                    | Desktop     | [2c92dfc348](https://linux-hardware.org/?probe=2c92dfc348) | Jan 05, 2017 |
| Dell          | System XPS L702X            | Notebook    | [46163e82b9](https://linux-hardware.org/?probe=46163e82b9) | Jan 01, 2017 |
| Samsung       | 730U3E/740U3E               | Notebook    | [c322226444](https://linux-hardware.org/?probe=c322226444) | Dec 29, 2016 |
| Toshiba       | Satellite P500              | Notebook    | [3308602af5](https://linux-hardware.org/?probe=3308602af5) | Dec 25, 2016 |
| Gigabyte      | GA-MA74GM-S2                | Desktop     | [b73f9cc351](https://linux-hardware.org/?probe=b73f9cc351) | Dec 21, 2016 |
| ECS           | GeForce7050M-M              | Desktop     | [ea41b9c6cf](https://linux-hardware.org/?probe=ea41b9c6cf) | Dec 21, 2016 |
| EPoX Compu... | i915P DDR + DDR2: 5EDAI     | Desktop     | [bb2baf4caa](https://linux-hardware.org/?probe=bb2baf4caa) | Dec 11, 2016 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [5201188f4f](https://linux-hardware.org/?probe=5201188f4f) | Dec 09, 2016 |
| Gigabyte      | M68M-S2P                    | Desktop     | [a39dfe883b](https://linux-hardware.org/?probe=a39dfe883b) | Dec 05, 2016 |
| MSI           | Z77A-G45 GAMING             | Desktop     | [ef3b22aa83](https://linux-hardware.org/?probe=ef3b22aa83) | Nov 28, 2016 |
| HP            | Mini 5102                   | Notebook    | [241bbbc5d3](https://linux-hardware.org/?probe=241bbbc5d3) | Nov 22, 2016 |
| ASUSTek       | K56CA                       | Notebook    | [17622d480a](https://linux-hardware.org/?probe=17622d480a) | Nov 18, 2016 |
| ASUSTek       | K56CA                       | Notebook    | [c465d23083](https://linux-hardware.org/?probe=c465d23083) | Nov 18, 2016 |
| Gateway       | MT3705                      | Notebook    | [7b425074da](https://linux-hardware.org/?probe=7b425074da) | Nov 17, 2016 |
| Gigabyte      | Z87-HD3                     | Desktop     | [7e7a86540c](https://linux-hardware.org/?probe=7e7a86540c) | Nov 13, 2016 |
| MSI           | MS-N014                     | Notebook    | [d9d05c3d89](https://linux-hardware.org/?probe=d9d05c3d89) | Nov 13, 2016 |
| ASUSTek       | P8P67                       | Desktop     | [5a00910b95](https://linux-hardware.org/?probe=5a00910b95) | Nov 09, 2016 |
| Acer          | Aspire V5-531G              | Notebook    | [cbda54c9f4](https://linux-hardware.org/?probe=cbda54c9f4) | Nov 07, 2016 |
| HP            | Presario CQ57               | Notebook    | [de1cbe1e61](https://linux-hardware.org/?probe=de1cbe1e61) | Nov 06, 2016 |
| ASUSTek       | V200IB                      | All in one  | [12e9cf8a7d](https://linux-hardware.org/?probe=12e9cf8a7d) | Nov 03, 2016 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [f8433b752a](https://linux-hardware.org/?probe=f8433b752a) | Nov 03, 2016 |
| Nvidia        | NF-MCP61                    | Desktop     | [5c7c6bc310](https://linux-hardware.org/?probe=5c7c6bc310) | Nov 02, 2016 |
| MSI           | 760GM-P33                   | Desktop     | [05c4ad2044](https://linux-hardware.org/?probe=05c4ad2044) | Oct 28, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ROSA R10                     | 123       | 12.91%  |
| ROSA R11                     | 106       | 11.12%  |
| ROSA R8.1                    | 81        | 8.5%    |
| Ubuntu 20.04                 | 59        | 6.19%   |
| ROSA R9                      | 49        | 5.14%   |
| ROSA R11.1                   | 45        | 4.72%   |
| Ubuntu 18.04                 | 39        | 4.09%   |
| ROSA R8                      | 37        | 3.88%   |
| ROSA 12.2                    | 29        | 3.04%   |
| OpenMandriva 4.2             | 24        | 2.52%   |
| Manjaro                      | 15        | 1.57%   |
| Linux Mint 19.3              | 13        | 1.36%   |
| KDE neon 20.04               | 12        | 1.26%   |
| Fedora 35                    | 12        | 1.26%   |
| Linux Mint 20.3              | 11        | 1.15%   |
| Arch                         | 11        | 1.15%   |
| Fedora 34                    | 10        | 1.05%   |
| Debian 11                    | 10        | 1.05%   |
| Kubuntu 20.04                | 9         | 0.94%   |
| Fedora 36                    | 9         | 0.94%   |
| OpenMandriva 4.3             | 8         | 0.84%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 0.63%   |
| Fedora 32                    | 6         | 0.63%   |
| Fedora 31                    | 6         | 0.63%   |
| Arch Rolling                 | 6         | 0.63%   |
| Ubuntu 21.04                 | 5         | 0.52%   |
| Manjaro 20.2.1               | 5         | 0.52%   |
| Linux Mint 20                | 5         | 0.52%   |
| Linux Mint 19.1              | 5         | 0.52%   |
| Linux Mint 19                | 5         | 0.52%   |
| Fedora 33                    | 5         | 0.52%   |
| Debian 10                    | 5         | 0.52%   |
| Xubuntu 20.04                | 4         | 0.42%   |
| Ubuntu 20.10                 | 4         | 0.42%   |
| ROSA 12.1                    | 4         | 0.42%   |
| Manjaro 20.0.3               | 4         | 0.42%   |
| Linux Mint 20.1              | 4         | 0.42%   |
| Linux Mint 18.3              | 4         | 0.42%   |
| Gentoo 2.8                   | 4         | 0.42%   |
| Gentoo 2.7                   | 4         | 0.42%   |
| Debian Testing               | 4         | 0.42%   |
| Zorin 16                     | 3         | 0.31%   |
| Ubuntu 19.04                 | 3         | 0.31%   |
| Pop!_OS 20.04                | 3         | 0.31%   |
| Manjaro 21.0                 | 3         | 0.31%   |
| LMDE 4                       | 3         | 0.31%   |
| Endless 3.7.7                | 3         | 0.31%   |
| Endless 3.5.8                | 3         | 0.31%   |
| Endless 3.3.19               | 3         | 0.31%   |
| Elementary 6.1               | 3         | 0.31%   |
| Debian Unstable              | 3         | 0.31%   |
| BlackPanther 18.1            | 3         | 0.31%   |
| Xubuntu 18.04                | 2         | 0.21%   |
| Ubuntu MATE 20.04            | 2         | 0.21%   |
| Ubuntu 19.10                 | 2         | 0.21%   |
| ROSA 12                      | 2         | 0.21%   |
| OpenMandriva 4.50            | 2         | 0.21%   |
| Manjaro 21.1.0               | 2         | 0.21%   |
| Manjaro 21.0.7               | 2         | 0.21%   |
| Manjaro 20.2                 | 2         | 0.21%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| ROSA             | 402       | 47.69%  |
| Ubuntu           | 113       | 13.4%   |
| Linux Mint       | 52        | 6.17%   |
| Endless          | 38        | 4.51%   |
| Manjaro          | 36        | 4.27%   |
| OpenMandriva     | 35        | 4.15%   |
| Fedora           | 35        | 4.15%   |
| Debian           | 20        | 2.37%   |
| Arch             | 16        | 1.9%    |
| Kubuntu          | 13        | 1.54%   |
| KDE neon         | 13        | 1.54%   |
| Gentoo           | 10        | 1.19%   |
| openSUSE         | 7         | 0.83%   |
| Xubuntu          | 6         | 0.71%   |
| Pop!_OS          | 5         | 0.59%   |
| Elementary       | 5         | 0.59%   |
| LMDE             | 4         | 0.47%   |
| Zorin            | 3         | 0.36%   |
| Ubuntu MATE      | 3         | 0.36%   |
| Lubuntu          | 3         | 0.36%   |
| BlackPanther     | 3         | 0.36%   |
| MX               | 2         | 0.24%   |
| Clear Linux      | 2         | 0.24%   |
| CentOS           | 2         | 0.24%   |
| ArcoLinux        | 2         | 0.24%   |
| ALT Linux        | 2         | 0.24%   |
| Solus            | 1         | 0.12%   |
| RHEL             | 1         | 0.12%   |
| Q4OS             | 1         | 0.12%   |
| Peppermint       | 1         | 0.12%   |
| Parrot           | 1         | 0.12%   |
| org.kde.Platform | 1         | 0.12%   |
| Mageia           | 1         | 0.12%   |
| Kali             | 1         | 0.12%   |
| Devuan           | 1         | 0.12%   |
| Deepin           | 1         | 0.12%   |
| Android          | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 60        | 5.64%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 42        | 3.95%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 39        | 3.67%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 29        | 2.73%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 27        | 2.54%   |
| 5.10.14-desktop-1omv4002            | 23        | 2.16%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 20        | 1.88%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 19        | 1.79%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 18        | 1.69%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 16        | 1.5%    |
| 5.4.83-generic-2rosa-x86_64         | 15        | 1.41%   |
| 4.15.0-desktop-45.1rosa-i586        | 15        | 1.41%   |
| 5.4.0-42-generic                    | 13        | 1.22%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 13        | 1.22%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 12        | 1.13%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 11        | 1.03%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 10        | 0.94%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 10        | 0.94%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 9         | 0.85%   |
| 5.16.7-desktop-1omv4003             | 8         | 0.75%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 8         | 0.75%   |
| 4.9.155-nrj-laptop-1rosa-x86_64     | 7         | 0.66%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 7         | 0.66%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 7         | 0.66%   |
| 5.9.16-1-MANJARO                    | 6         | 0.56%   |
| 5.8.0-14-generic                    | 6         | 0.56%   |
| 5.4.32-generic-2rosa-x86_64         | 6         | 0.56%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 6         | 0.56%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 6         | 0.56%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 6         | 0.56%   |
| 5.4.0-58-generic                    | 5         | 0.47%   |
| 5.4.0-48-generic                    | 5         | 0.47%   |
| 5.3.0-28-generic                    | 5         | 0.47%   |
| 5.0.0-37-generic                    | 5         | 0.47%   |
| 4.9.87-nrj-desktop-2rosa-x86_64     | 5         | 0.47%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 5         | 0.47%   |
| 4.15.0-desktop-54.1rosa-x86_64      | 5         | 0.47%   |
| 4.13.0-32-generic                   | 5         | 0.47%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 5         | 0.47%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 5         | 0.47%   |
| 5.8.0-50-generic                    | 4         | 0.38%   |
| 5.4.83-generic-2rosa-i586           | 4         | 0.38%   |
| 5.4.0-65-generic                    | 4         | 0.38%   |
| 5.4.0-40-generic                    | 4         | 0.38%   |
| 5.4.0-26-generic                    | 4         | 0.38%   |
| 5.4.0-19-generic                    | 4         | 0.38%   |
| 5.11.0-43-generic                   | 4         | 0.38%   |
| 5.11.0-35-generic                   | 4         | 0.38%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 4         | 0.38%   |
| 5.0.0-25-generic                    | 4         | 0.38%   |
| 4.9.76-nrj-desktop-1rosa-i586       | 4         | 0.38%   |
| 4.9.41-nrj-desktop-1rosa-i586       | 4         | 0.38%   |
| 4.1.38-nrj-desktop-1rosa-x86_64     | 4         | 0.38%   |
| 5.8.0-48-generic                    | 3         | 0.28%   |
| 5.8.0-45-generic                    | 3         | 0.28%   |
| 5.8.0-43-generic                    | 3         | 0.28%   |
| 5.4.0-72-generic                    | 3         | 0.28%   |
| 5.4.0-51-generic                    | 3         | 0.28%   |
| 5.3.0-46-generic                    | 3         | 0.28%   |
| 5.3.0-40-generic                    | 3         | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 138       | 13.33%  |
| 5.4.0    | 79        | 7.63%   |
| 4.9.60   | 71        | 6.86%   |
| 4.9.20   | 49        | 4.73%   |
| 4.9.124  | 33        | 3.19%   |
| 5.8.0    | 31        | 3%      |
| 5.10.74  | 29        | 2.8%    |
| 4.9.155  | 27        | 2.61%   |
| 4.1.38   | 27        | 2.61%   |
| 5.11.0   | 25        | 2.42%   |
| 4.1.34   | 25        | 2.42%   |
| 5.10.14  | 23        | 2.22%   |
| 5.0.0    | 22        | 2.13%   |
| 4.9.9    | 22        | 2.13%   |
| 4.9.76   | 22        | 2.13%   |
| 5.3.0    | 20        | 1.93%   |
| 5.13.0   | 20        | 1.93%   |
| 5.4.83   | 19        | 1.84%   |
| 5.10.0   | 17        | 1.64%   |
| 4.9.41   | 14        | 1.35%   |
| 4.18.0   | 13        | 1.26%   |
| 5.15.0   | 9         | 0.87%   |
| 4.19.0   | 9         | 0.87%   |
| 4.13.0   | 9         | 0.87%   |
| 5.9.16   | 8         | 0.77%   |
| 5.16.7   | 8         | 0.77%   |
| 5.4.32   | 7         | 0.68%   |
| 4.9.95   | 7         | 0.68%   |
| 4.9.87   | 6         | 0.58%   |
| 4.9.111  | 6         | 0.58%   |
| 5.10.118 | 4         | 0.39%   |
| 4.9.34   | 4         | 0.39%   |
| 4.8.17   | 4         | 0.39%   |
| 5.9.11   | 3         | 0.29%   |
| 5.6.14   | 3         | 0.29%   |
| 5.3.12   | 3         | 0.29%   |
| 5.17.5   | 3         | 0.29%   |
| 5.16.5   | 3         | 0.29%   |
| 5.15.5   | 3         | 0.29%   |
| 5.15.32  | 3         | 0.29%   |
| 5.14.15  | 3         | 0.29%   |
| 5.14.0   | 3         | 0.29%   |
| 5.12.9   | 3         | 0.29%   |
| 4.4.0    | 3         | 0.29%   |
| 4.18.16  | 3         | 0.29%   |
| 4.1.25   | 3         | 0.29%   |
| 5.9.8    | 2         | 0.19%   |
| 5.9.0    | 2         | 0.19%   |
| 5.8.13   | 2         | 0.19%   |
| 5.8.11   | 2         | 0.19%   |
| 5.7.9    | 2         | 0.19%   |
| 5.7.0    | 2         | 0.19%   |
| 5.6.19   | 2         | 0.19%   |
| 5.6.0    | 2         | 0.19%   |
| 5.5.11   | 2         | 0.19%   |
| 5.4.60   | 2         | 0.19%   |
| 5.4.15   | 2         | 0.19%   |
| 5.4.13   | 2         | 0.19%   |
| 5.3.13   | 2         | 0.19%   |
| 5.3.11   | 2         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 214       | 22.38%  |
| 4.15    | 138       | 14.44%  |
| 5.4     | 121       | 12.66%  |
| 5.10    | 83        | 8.68%   |
| 4.1     | 55        | 5.75%   |
| 5.8     | 39        | 4.08%   |
| 5.11    | 35        | 3.66%   |
| 5.3     | 29        | 3.03%   |
| 5.13    | 29        | 3.03%   |
| 5.15    | 28        | 2.93%   |
| 5.0     | 23        | 2.41%   |
| 5.9     | 19        | 1.99%   |
| 4.18    | 16        | 1.67%   |
| 4.19    | 14        | 1.46%   |
| 5.16    | 13        | 1.36%   |
| 5.18    | 12        | 1.26%   |
| 5.6     | 11        | 1.15%   |
| 5.14    | 11        | 1.15%   |
| 5.17    | 9         | 0.94%   |
| 4.13    | 9         | 0.94%   |
| 5.12    | 8         | 0.84%   |
| 4.8     | 8         | 0.84%   |
| 5.7     | 5         | 0.52%   |
| 4.4     | 5         | 0.52%   |
| 4.14    | 5         | 0.52%   |
| 5.5     | 4         | 0.42%   |
| 4.17    | 3         | 0.31%   |
| 4.16    | 3         | 0.31%   |
| 4.10    | 2         | 0.21%   |
| 5.19    | 1         | 0.1%    |
| 5.1     | 1         | 0.1%    |
| 4.20    | 1         | 0.1%    |
| 4.12    | 1         | 0.1%    |
| 3.4     | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 741       | 89.17%  |
| i686   | 88        | 10.59%  |
| armv7l | 2         | 0.24%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE4       | 277       | 31.37%  |
| KDE5       | 216       | 24.46%  |
| GNOME      | 179       | 20.27%  |
| Unknown    | 73        | 8.27%   |
| XFCE       | 38        | 4.3%    |
| X-Cinnamon | 26        | 2.94%   |
| MATE       | 17        | 1.93%   |
| LXQt       | 16        | 1.81%   |
| KDE        | 15        | 1.7%    |
| Cinnamon   | 11        | 1.25%   |
| Pantheon   | 4         | 0.45%   |
| LXDE       | 3         | 0.34%   |
| i3         | 2         | 0.23%   |
| Deepin     | 2         | 0.23%   |
| Unity      | 1         | 0.11%   |
| Trinity    | 1         | 0.11%   |
| Openbox    | 1         | 0.11%   |
| Budgie     | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 724       | 85.99%  |
| Wayland | 70        | 8.31%   |
| Unknown | 38        | 4.51%   |
| Tty     | 10        | 1.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDM     | 279       | 31.96%  |
| SDDM    | 226       | 25.89%  |
| Unknown | 200       | 22.91%  |
| GDM     | 89        | 10.19%  |
| LightDM | 34        | 3.89%   |
| TDM     | 29        | 3.32%   |
| GDM3    | 13        | 1.49%   |
| MDM     | 2         | 0.23%   |
| SLiM    | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 416       | 48.65%  |
| ru_RU       | 269       | 31.46%  |
| en_US       | 136       | 15.91%  |
| be_BY       | 10        | 1.17%   |
| en_GB       | 9         | 1.05%   |
| ru_RU.UTF_8 | 6         | 0.7%    |
| C           | 3         | 0.35%   |
| ru_UA       | 2         | 0.23%   |
| cv_RU       | 2         | 0.23%   |
| ru_BY       | 1         | 0.12%   |
| en_CA       | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 504       | 60%     |
| EFI  | 336       | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 539       | 61.39%  |
| Unknown | 242       | 27.56%  |
| Btrfs   | 47        | 5.35%   |
| Overlay | 34        | 3.87%   |
| Xfs     | 5         | 0.57%   |
| Ext3    | 4         | 0.46%   |
| F2fs    | 2         | 0.23%   |
| Ext2    | 2         | 0.23%   |
| Zfs     | 1         | 0.11%   |
| Tmpfs   | 1         | 0.11%   |
| SAMSUNG | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 321       | 36.64%  |
| Unknown | 304       | 34.7%   |
| GPT     | 251       | 28.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 734       | 86.56%  |
| Yes       | 114       | 13.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 579       | 66.86%  |
| Yes       | 287       | 33.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 186       | 22.68%  |
| Lenovo              | 105       | 12.8%   |
| Hewlett-Packard     | 96        | 11.71%  |
| Gigabyte Technology | 87        | 10.61%  |
| Acer                | 71        | 8.66%   |
| ASRock              | 66        | 8.05%   |
| MSI                 | 45        | 5.49%   |
| Dell                | 36        | 4.39%   |
| Samsung Electronics | 32        | 3.9%    |
| Intel               | 10        | 1.22%   |
| Biostar             | 10        | 1.22%   |
| Toshiba             | 9         | 1.1%    |
| Timi                | 8         | 0.98%   |
| Sony                | 6         | 0.73%   |
| Prestigio           | 5         | 0.61%   |
| Packard Bell        | 5         | 0.61%   |
| HONOR               | 4         | 0.49%   |
| Fujitsu             | 4         | 0.49%   |
| Fujitsu Siemens     | 3         | 0.37%   |
| ECS                 | 3         | 0.37%   |
| Nvidia              | 2         | 0.24%   |
| BenQ                | 2         | 0.24%   |
| Apple               | 2         | 0.24%   |
| Unknown             | 2         | 0.24%   |
| ZOTAC               | 1         | 0.12%   |
| ViewSonic           | 1         | 0.12%   |
| VIA Technologies    | 1         | 0.12%   |
| Supermicro          | 1         | 0.12%   |
| Quanta              | 1         | 0.12%   |
| Olimex              | 1         | 0.12%   |
| NCS-Tech            | 1         | 0.12%   |
| Microsoft           | 1         | 0.12%   |
| LG Electronics      | 1         | 0.12%   |
| Kllisre             | 1         | 0.12%   |
| Jetway              | 1         | 0.12%   |
| IBM                 | 1         | 0.12%   |
| HUAWEI              | 1         | 0.12%   |
| Huanan              | 1         | 0.12%   |
| Gateway             | 1         | 0.12%   |
| Foxconn             | 1         | 0.12%   |
| EPoX Computer       | 1         | 0.12%   |
| eMachines           | 1         | 0.12%   |
| Dream Machines      | 1         | 0.12%   |
| DNS                 | 1         | 0.12%   |
| Digma               | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo G50-30 80G0                         | 7         | 0.85%   |
| HP Notebook                                | 6         | 0.73%   |
| ASRock N68C-GS FX                          | 5         | 0.61%   |
| Acer Extensa 5220                          | 5         | 0.61%   |
| Timi TM1701                                | 4         | 0.49%   |
| MSI MS-7369                                | 4         | 0.49%   |
| Lenovo IdeaPad 320-15IAP 80XR              | 4         | 0.49%   |
| HP ProBook 455 G1                          | 4         | 0.49%   |
| Gigabyte 970A-DS3P                         | 4         | 0.49%   |
| ASUS X540NV                                | 4         | 0.49%   |
| ASUS All Series                            | 4         | 0.49%   |
| ASRock N68-VS3 UCC                         | 4         | 0.49%   |
| Acer Aspire E1-571G                        | 4         | 0.49%   |
| Unknown                                    | 4         | 0.49%   |
| Samsung RV413/RV513                        | 3         | 0.37%   |
| MSI MS-7309                                | 3         | 0.37%   |
| Lenovo IdeaPad Z570 HuronRiver Platform    | 3         | 0.37%   |
| Lenovo G570 20079                          | 3         | 0.37%   |
| Lenovo B590 20206                          | 3         | 0.37%   |
| Lenovo B50-30 20382                        | 3         | 0.37%   |
| HP Pavilion g6                             | 3         | 0.37%   |
| HP Pavilion 15                             | 3         | 0.37%   |
| HP 635                                     | 3         | 0.37%   |
| Gigabyte M61SME-S2                         | 3         | 0.37%   |
| Gigabyte H81M-S2H                          | 3         | 0.37%   |
| Gigabyte GA-MA74GM-S2H                     | 3         | 0.37%   |
| Gigabyte GA-780T-D3L                       | 3         | 0.37%   |
| Gigabyte B450M S2H                         | 3         | 0.37%   |
| Gigabyte B450M DS3H                        | 3         | 0.37%   |
| ASUS ZenBook UX431DA_UM431DA               | 3         | 0.37%   |
| ASUS X541UAK                               | 3         | 0.37%   |
| ASUS TUF B450-PRO GAMING                   | 3         | 0.37%   |
| ASUS P8H77-V                               | 3         | 0.37%   |
| ASRock N68-VGS3 FX                         | 3         | 0.37%   |
| Acer Aspire V3-571G                        | 3         | 0.37%   |
| Acer Aspire 4810T                          | 3         | 0.37%   |
| Timi TM1613                                | 2         | 0.24%   |
| Samsung R528/R728                          | 2         | 0.24%   |
| Samsung R508                               | 2         | 0.24%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 2         | 0.24%   |
| Samsung 305E4Z/305E5Z/305E7Z               | 2         | 0.24%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 2         | 0.24%   |
| Prestigio Multipad Visconte V              | 2         | 0.24%   |
| Nvidia NF-MCP61                            | 2         | 0.24%   |
| MSI MS-N014                                | 2         | 0.24%   |
| MSI MS-7996                                | 2         | 0.24%   |
| MSI MS-7846                                | 2         | 0.24%   |
| MSI MS-7623                                | 2         | 0.24%   |
| MSI MS-7592                                | 2         | 0.24%   |
| MSI MS-7250                                | 2         | 0.24%   |
| MSI GF63 Thin 9SCSR                        | 2         | 0.24%   |
| Lenovo Z710 20250                          | 2         | 0.24%   |
| Lenovo Z50-70 20354                        | 2         | 0.24%   |
| Lenovo V580c 20160                         | 2         | 0.24%   |
| Lenovo Legion 5 15ARH05 82B5               | 2         | 0.24%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL      | 2         | 0.24%   |
| Lenovo IdeaPad L340-15API 81LW             | 2         | 0.24%   |
| Lenovo IdeaPad 100-15IBY 80MJ              | 2         | 0.24%   |
| Lenovo G580 20157                          | 2         | 0.24%   |
| Lenovo G500 20236                          | 2         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 45        | 5.49%   |
| Lenovo IdeaPad         | 31        | 3.78%   |
| Lenovo ThinkPad        | 27        | 3.29%   |
| HP ProBook             | 27        | 3.29%   |
| Dell Inspiron          | 20        | 2.44%   |
| ASUS VivoBook          | 20        | 2.44%   |
| HP Pavilion            | 19        | 2.32%   |
| Acer Extensa           | 13        | 1.59%   |
| HP Laptop              | 8         | 0.98%   |
| ASUS ZenBook           | 8         | 0.98%   |
| Toshiba Satellite      | 7         | 0.85%   |
| Lenovo G50-30          | 7         | 0.85%   |
| Gigabyte B450M         | 7         | 0.85%   |
| HP Notebook            | 6         | 0.73%   |
| HP EliteBook           | 6         | 0.73%   |
| ASUS PRIME             | 6         | 0.73%   |
| HP Compaq              | 5         | 0.61%   |
| ASUS TUF               | 5         | 0.61%   |
| ASUS ROG               | 5         | 0.61%   |
| ASRock N68C-GS         | 5         | 0.61%   |
| ASRock N68-VS3         | 5         | 0.61%   |
| Timi TM1701            | 4         | 0.49%   |
| MSI MS-7369            | 4         | 0.49%   |
| Lenovo Legion          | 4         | 0.49%   |
| Gigabyte 970A-DS3P     | 4         | 0.49%   |
| Dell XPS               | 4         | 0.49%   |
| Dell Vostro            | 4         | 0.49%   |
| ASUS X540NV            | 4         | 0.49%   |
| ASUS P8H77-V           | 4         | 0.49%   |
| ASUS All               | 4         | 0.49%   |
| Acer TravelMate        | 4         | 0.49%   |
| Unknown                | 4         | 0.49%   |
| Samsung RV413          | 3         | 0.37%   |
| Packard Bell EasyNote  | 3         | 0.37%   |
| MSI MS-7309            | 3         | 0.37%   |
| Lenovo G580            | 3         | 0.37%   |
| Lenovo G570            | 3         | 0.37%   |
| Lenovo B590            | 3         | 0.37%   |
| Lenovo B50-30          | 3         | 0.37%   |
| HP Presario            | 3         | 0.37%   |
| HP Mini                | 3         | 0.37%   |
| HP 635                 | 3         | 0.37%   |
| HP 250                 | 3         | 0.37%   |
| Gigabyte Z390          | 3         | 0.37%   |
| Gigabyte M61SME-S2     | 3         | 0.37%   |
| Gigabyte H81M-S2H      | 3         | 0.37%   |
| Gigabyte GA-MA74GM-S2H | 3         | 0.37%   |
| Gigabyte GA-780T-D3L   | 3         | 0.37%   |
| ASUS X541UAK           | 3         | 0.37%   |
| ASUS P5B               | 3         | 0.37%   |
| ASUS M5A97             | 3         | 0.37%   |
| ASUS ASUS              | 3         | 0.37%   |
| ASRock N68-VGS3        | 3         | 0.37%   |
| Acer Nitro             | 3         | 0.37%   |
| Timi TM1613            | 2         | 0.24%   |
| Samsung R528           | 2         | 0.24%   |
| Samsung R508           | 2         | 0.24%   |
| Samsung 355V4C         | 2         | 0.24%   |
| Samsung 305E4Z         | 2         | 0.24%   |
| Samsung 300E4A         | 2         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 92        | 11.22%  |
| 2012    | 86        | 10.49%  |
| 2013    | 81        | 9.88%   |
| 2018    | 72        | 8.78%   |
| 2017    | 59        | 7.2%    |
| 2010    | 55        | 6.71%   |
| 2014    | 49        | 5.98%   |
| 2007    | 49        | 5.98%   |
| 2009    | 48        | 5.85%   |
| 2019    | 46        | 5.61%   |
| 2020    | 43        | 5.24%   |
| 2015    | 34        | 4.15%   |
| 2008    | 34        | 4.15%   |
| 2016    | 28        | 3.41%   |
| 2021    | 19        | 2.32%   |
| 2006    | 16        | 1.95%   |
| 2005    | 5         | 0.61%   |
| Unknown | 2         | 0.24%   |
| 2022    | 1         | 0.12%   |
| 2003    | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 506       | 61.71%  |
| Desktop        | 292       | 35.61%  |
| All in one     | 8         | 0.98%   |
| Convertible    | 4         | 0.49%   |
| Tablet         | 3         | 0.37%   |
| Mini pc        | 3         | 0.37%   |
| Server         | 2         | 0.24%   |
| Phone          | 1         | 0.12%   |
| System on chip | 1         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 783       | 95.26%  |
| Enabled  | 39        | 4.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 820       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 247       | 29.4%   |
| 4.01-8.0    | 190       | 22.62%  |
| 8.01-16.0   | 126       | 15%     |
| 16.01-24.0  | 100       | 11.9%   |
| 1.01-2.0    | 77        | 9.17%   |
| 2.01-3.0    | 38        | 4.52%   |
| 32.01-64.0  | 32        | 3.81%   |
| 0.51-1.0    | 20        | 2.38%   |
| 24.01-32.0  | 5         | 0.6%    |
| 64.01-256.0 | 4         | 0.48%   |
| 0.01-0.5    | 1         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 341       | 35.78%  |
| 0.51-1.0   | 243       | 25.5%   |
| 2.01-3.0   | 164       | 17.21%  |
| 4.01-8.0   | 81        | 8.5%    |
| 3.01-4.0   | 75        | 7.87%   |
| 0.01-0.5   | 22        | 2.31%   |
| 8.01-16.0  | 19        | 1.99%   |
| 16.01-24.0 | 4         | 0.42%   |
| 24.01-32.0 | 2         | 0.21%   |
| 32.01-64.0 | 1         | 0.1%    |
| Unknown    | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 547       | 64.05%  |
| 2      | 216       | 25.29%  |
| 3      | 61        | 7.14%   |
| 4      | 17        | 1.99%   |
| 5      | 7         | 0.82%   |
| 0      | 4         | 0.47%   |
| 9      | 1         | 0.12%   |
| 6      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 461       | 55.61%  |
| Yes       | 368       | 44.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 732       | 89.16%  |
| No        | 89        | 10.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 597       | 72.54%  |
| No        | 226       | 27.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 434       | 52.35%  |
| No        | 395       | 47.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Belarus | 820       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Minsk          | 386       | 42.75%  |
| Vitebsk        | 95        | 10.52%  |
| Gomel          | 79        | 8.75%   |
| Hrodna         | 51        | 5.65%   |
| Mogilev        | 49        | 5.43%   |
| Brest          | 44        | 4.87%   |
| Orsha          | 17        | 1.88%   |
| Babruysk       | 16        | 1.77%   |
| Polatsk        | 15        | 1.66%   |
| Borisov        | 9         | 1%      |
| Lida           | 8         | 0.89%   |
| Baranovichi    | 8         | 0.89%   |
| Slutsk         | 7         | 0.78%   |
| Zhlobin        | 6         | 0.66%   |
| Mazyr          | 6         | 0.66%   |
| Bogushevichi   | 6         | 0.66%   |
| Zhodzina       | 5         | 0.55%   |
| Vawkavysk      | 5         | 0.55%   |
| Pinsk          | 4         | 0.44%   |
| Klyetsk        | 4         | 0.44%   |
| Syanno         | 3         | 0.33%   |
| Smalyavichy    | 3         | 0.33%   |
| Slonim         | 3         | 0.33%   |
| Rahachow       | 3         | 0.33%   |
| Navapolatsk    | 3         | 0.33%   |
| Fedorovka      | 3         | 0.33%   |
| Dubovka        | 3         | 0.33%   |
| Baran'         | 3         | 0.33%   |
| Aleksandrovo   | 3         | 0.33%   |
| Svyetlahorsk   | 2         | 0.22%   |
| Snitovo        | 2         | 0.22%   |
| Salihorsk      | 2         | 0.22%   |
| Pruzhany       | 2         | 0.22%   |
| Ogorodniki     | 2         | 0.22%   |
| Murava         | 2         | 0.22%   |
| Masty          | 2         | 0.22%   |
| Maladzyechna   | 2         | 0.22%   |
| Lyepyel'       | 2         | 0.22%   |
| Loshnitsa      | 2         | 0.22%   |
| Krupki         | 2         | 0.22%   |
| Kolodishchi    | 2         | 0.22%   |
| Drahichyn      | 2         | 0.22%   |
| Byshanka       | 2         | 0.22%   |
| Zaslawye       | 1         | 0.11%   |
| Vilyeyka       | 1         | 0.11%   |
| Stolin         | 1         | 0.11%   |
| Skoki          | 1         | 0.11%   |
| Shklow         | 1         | 0.11%   |
| Rechytsa       | 1         | 0.11%   |
| Rakov          | 1         | 0.11%   |
| Pyetrykaw      | 1         | 0.11%   |
| Pastavy        | 1         | 0.11%   |
| Osipovichi     | 1         | 0.11%   |
| Olekhnoviche   | 1         | 0.11%   |
| Narowlya       | 1         | 0.11%   |
| Myadzyel       | 1         | 0.11%   |
| Magistral'naya | 1         | 0.11%   |
| Korobchicy     | 1         | 0.11%   |
| Klimavichy     | 1         | 0.11%   |
| Kirawsk        | 1         | 0.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 200       | 317    | 17.48%  |
| Seagate             | 199       | 304    | 17.4%   |
| Samsung Electronics | 154       | 221    | 13.46%  |
| Toshiba             | 125       | 190    | 10.93%  |
| Hitachi             | 79        | 104    | 6.91%   |
| Kingston            | 72        | 96     | 6.29%   |
| HGST                | 41        | 61     | 3.58%   |
| SK hynix            | 31        | 34     | 2.71%   |
| Intel               | 24        | 33     | 2.1%    |
| Crucial             | 23        | 29     | 2.01%   |
| Unknown             | 21        | 28     | 1.84%   |
| SanDisk             | 21        | 26     | 1.84%   |
| Patriot             | 14        | 17     | 1.22%   |
| Fujitsu             | 12        | 17     | 1.05%   |
| A-DATA Technology   | 11        | 12     | 0.96%   |
| OCZ                 | 10        | 11     | 0.87%   |
| KingSpec            | 9         | 17     | 0.79%   |
| China               | 9         | 11     | 0.79%   |
| Micron Technology   | 7         | 12     | 0.61%   |
| GOODRAM             | 7         | 7      | 0.61%   |
| Gigabyte Technology | 7         | 8      | 0.61%   |
| SPCC                | 5         | 10     | 0.44%   |
| Plextor             | 5         | 6      | 0.44%   |
| Transcend           | 4         | 5      | 0.35%   |
| Maxtor              | 4         | 4      | 0.35%   |
| Smartbuy            | 3         | 3      | 0.26%   |
| Silicon Motion      | 3         | 4      | 0.26%   |
| Netac               | 3         | 3      | 0.26%   |
| JMicron Technology  | 3         | 3      | 0.26%   |
| XPG                 | 2         | 2      | 0.17%   |
| Team                | 2         | 2      | 0.17%   |
| LITEONIT            | 2         | 2      | 0.17%   |
| Lenovo              | 2         | 5      | 0.17%   |
| KIOXIA              | 2         | 12     | 0.17%   |
| KingDian            | 2         | 4      | 0.17%   |
| External            | 2         | 2      | 0.17%   |
| Corsair             | 2         | 6      | 0.17%   |
| Apacer              | 2         | 3      | 0.17%   |
| Zheino              | 1         | 2      | 0.09%   |
| XrayDisk            | 1         | 1      | 0.09%   |
| WD MediaMax         | 1         | 1      | 0.09%   |
| USB3.0              | 1         | 1      | 0.09%   |
| Union Memory        | 1         | 1      | 0.09%   |
| Synopsys            | 1         | 1      | 0.09%   |
| SINTECHI            | 1         | 1      | 0.09%   |
| SAGE                | 1         | 1      | 0.09%   |
| PNY                 | 1         | 4      | 0.09%   |
| Phison              | 1         | 1      | 0.09%   |
| OSCOO               | 1         | 1      | 0.09%   |
| OCZ-VERTEX3         | 1         | 2      | 0.09%   |
| OCZ-VERTEX          | 1         | 1      | 0.09%   |
| MSS4FV-MP           | 1         | 1      | 0.09%   |
| Kllisre             | 1         | 1      | 0.09%   |
| HUAWEI              | 1         | 1      | 0.09%   |
| ASMT                | 1         | 1      | 0.09%   |
| Apple               | 1         | 1      | 0.09%   |
| AMD                 | 1         | 1      | 0.09%   |
| Acer                | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 24        | 1.94%   |
| Toshiba DT01ACA050 500GB             | 19        | 1.53%   |
| Samsung SSD 860 EVO 250GB            | 17        | 1.37%   |
| Kingston SA400S37120G 120GB SSD      | 17        | 1.37%   |
| Seagate ST500LT012-1DG142 500GB      | 16        | 1.29%   |
| Seagate ST1000LM035-1RK172 1TB       | 16        | 1.29%   |
| Toshiba DT01ACA100 1TB               | 15        | 1.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 14        | 1.13%   |
| Samsung SSD 860 EVO 500GB            | 11        | 0.89%   |
| Toshiba DT01ACA200 2TB               | 10        | 0.81%   |
| Seagate ST9320325AS 320GB            | 10        | 0.81%   |
| Seagate ST500DM002-1BD142 500GB      | 9         | 0.73%   |
| Samsung NVMe SSD Drive 256GB         | 9         | 0.73%   |
| HGST HTS545050A7E680 500GB           | 9         | 0.73%   |
| Crucial CT120BX500SSD1 120GB         | 9         | 0.73%   |
| Toshiba MQ04ABF100 1TB               | 8         | 0.65%   |
| SK hynix NVMe SSD Drive 512GB        | 8         | 0.65%   |
| Samsung SSD 850 EVO 250GB            | 8         | 0.65%   |
| Kingston SA400S37240G 240GB SSD      | 8         | 0.65%   |
| Hitachi HTS543232A7A384 320GB        | 8         | 0.65%   |
| WDC WD10JPVX-22JC3T0 1TB             | 7         | 0.56%   |
| Toshiba MQ01ABD100 1TB               | 7         | 0.56%   |
| Toshiba MQ01ABD032 320GB             | 7         | 0.56%   |
| Toshiba MQ01ABD075 752GB             | 6         | 0.48%   |
| Seagate ST9500325AS 500GB            | 6         | 0.48%   |
| Seagate ST9250315AS 250GB            | 6         | 0.48%   |
| Patriot Burst 120GB SSD              | 6         | 0.48%   |
| OCZ VERTEX4 128GB SSD                | 6         | 0.48%   |
| Kingston SUV400S37120G 120GB SSD     | 6         | 0.48%   |
| Hitachi HTS545050B9A300 500GB        | 6         | 0.48%   |
| HGST HTS541010A9E680 1TB             | 6         | 0.48%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 5         | 0.4%    |
| Seagate ST500LT012-9WS142 500GB      | 5         | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB       | 5         | 0.4%    |
| Samsung SSD 850 EVO 500GB            | 5         | 0.4%    |
| Samsung HD160JJ 160GB                | 5         | 0.4%    |
| Hitachi HTS547575A9E384 752GB        | 5         | 0.4%    |
| Hitachi HTS547550A9E384 500GB        | 5         | 0.4%    |
| Hitachi HDS721010CLA330 1TB          | 5         | 0.4%    |
| Hitachi HDP725050GLA360 500GB        | 5         | 0.4%    |
| HGST HTS541010B7E610 1TB             | 5         | 0.4%    |
| WDC WD3200BPVT-35ZEST0 320GB         | 4         | 0.32%   |
| WDC WD20EARS-00MVWB0 2TB             | 4         | 0.32%   |
| SK hynix NVMe SSD Drive 256GB        | 4         | 0.32%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 4         | 0.32%   |
| Seagate ST380817AS 80GB              | 4         | 0.32%   |
| Seagate ST3500413AS 500GB            | 4         | 0.32%   |
| Seagate ST3160815AS 160GB            | 4         | 0.32%   |
| Seagate ST2000DM008-2FR102 2TB       | 4         | 0.32%   |
| Seagate ST1000DM003-1ER162 1TB       | 4         | 0.32%   |
| Seagate ST1000DM003-1CH162 1TB       | 4         | 0.32%   |
| SanDisk NVMe SSD Drive 256GB         | 4         | 0.32%   |
| Samsung NVMe SSD Drive 512GB         | 4         | 0.32%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 0.32%   |
| Samsung HM500JI 500GB                | 4         | 0.32%   |
| Patriot Burst 240GB SSD              | 4         | 0.32%   |
| Hitachi HDS721050CLA360 500GB        | 4         | 0.32%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 4         | 0.32%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.32%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 3         | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 198       | 302    | 28.78%  |
| WDC                 | 183       | 281    | 26.6%   |
| Toshiba             | 118       | 179    | 17.15%  |
| Hitachi             | 79        | 104    | 11.48%  |
| Samsung Electronics | 46        | 72     | 6.69%   |
| HGST                | 41        | 61     | 5.96%   |
| Fujitsu             | 12        | 17     | 1.74%   |
| Maxtor              | 4         | 4      | 0.58%   |
| WD MediaMax         | 1         | 1      | 0.15%   |
| USB3.0              | 1         | 1      | 0.15%   |
| Unknown             | 1         | 1      | 0.15%   |
| SINTECHI            | 1         | 1      | 0.15%   |
| SAGE                | 1         | 1      | 0.15%   |
| External            | 1         | 1      | 0.15%   |
| Apple               | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 65        | 88     | 22.18%  |
| Kingston            | 55        | 74     | 18.77%  |
| Crucial             | 23        | 29     | 7.85%   |
| SanDisk             | 13        | 18     | 4.44%   |
| Patriot             | 12        | 15     | 4.1%    |
| WDC                 | 11        | 23     | 3.75%   |
| OCZ                 | 10        | 11     | 3.41%   |
| Intel               | 10        | 10     | 3.41%   |
| KingSpec            | 9         | 17     | 3.07%   |
| China               | 9         | 11     | 3.07%   |
| A-DATA Technology   | 7         | 8      | 2.39%   |
| SK hynix            | 6         | 6      | 2.05%   |
| GOODRAM             | 6         | 6      | 2.05%   |
| Gigabyte Technology | 6         | 7      | 2.05%   |
| SPCC                | 5         | 10     | 1.71%   |
| Plextor             | 5         | 6      | 1.71%   |
| Transcend           | 4         | 5      | 1.37%   |
| Unknown             | 3         | 3      | 1.02%   |
| Toshiba             | 3         | 3      | 1.02%   |
| Smartbuy            | 3         | 3      | 1.02%   |
| Netac               | 3         | 3      | 1.02%   |
| JMicron Technology  | 3         | 3      | 1.02%   |
| Team                | 2         | 2      | 0.68%   |
| Seagate             | 2         | 2      | 0.68%   |
| LITEONIT            | 2         | 2      | 0.68%   |
| KingDian            | 2         | 4      | 0.68%   |
| Corsair             | 2         | 6      | 0.68%   |
| Apacer              | 2         | 3      | 0.68%   |
| Zheino              | 1         | 2      | 0.34%   |
| XrayDisk            | 1         | 1      | 0.34%   |
| Union Memory        | 1         | 1      | 0.34%   |
| PNY                 | 1         | 4      | 0.34%   |
| OSCOO               | 1         | 1      | 0.34%   |
| OCZ-VERTEX3         | 1         | 2      | 0.34%   |
| OCZ-VERTEX          | 1         | 1      | 0.34%   |
| MSS4FV-MP           | 1         | 1      | 0.34%   |
| AMD                 | 1         | 1      | 0.34%   |
| Acer                | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 600       | 1027   | 57.42%  |
| SSD     | 273       | 393    | 26.12%  |
| NVMe    | 151       | 207    | 14.45%  |
| MMC     | 19        | 27     | 1.82%   |
| Unknown | 2         | 2      | 0.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 704       | 1405   | 79.19%  |
| NVMe | 151       | 206    | 16.99%  |
| MMC  | 19        | 27     | 2.14%   |
| SAS  | 15        | 18     | 1.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 582       | 978    | 67.83%  |
| 0.51-1.0   | 215       | 328    | 25.06%  |
| 1.01-2.0   | 36        | 74     | 4.2%    |
| 3.01-4.0   | 9         | 12     | 1.05%   |
| 2.01-3.0   | 8         | 13     | 0.93%   |
| 4.01-10.0  | 5         | 11     | 0.58%   |
| 10.01-20.0 | 3         | 4      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 234       | 25.66%  |
| 251-500        | 228       | 25%     |
| 501-1000       | 117       | 12.83%  |
| 1-20           | 94        | 10.31%  |
| 51-100         | 78        | 8.55%   |
| 21-50          | 58        | 6.36%   |
| 1001-2000      | 58        | 6.36%   |
| More than 3000 | 18        | 1.97%   |
| Unknown        | 16        | 1.75%   |
| 2001-3000      | 11        | 1.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 416       | 44.83%  |
| 21-50          | 133       | 14.33%  |
| 101-250        | 104       | 11.21%  |
| 51-100         | 102       | 10.99%  |
| 251-500        | 72        | 7.76%   |
| 501-1000       | 48        | 5.17%   |
| 1001-2000      | 20        | 2.16%   |
| Unknown        | 16        | 1.72%   |
| 2001-3000      | 9         | 0.97%   |
| More than 3000 | 7         | 0.75%   |
| 0              | 1         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB          | 6         | 6      | 2.42%   |
| Seagate ST500LT012-1DG142 500GB    | 6         | 7      | 2.42%   |
| HGST HTS545050A7E680 500GB         | 5         | 6      | 2.02%   |
| Toshiba MQ01ABF050 500GB           | 4         | 5      | 1.61%   |
| Toshiba DT01ACA100 1TB             | 4         | 5      | 1.61%   |
| Seagate ST9500325AS 500GB          | 4         | 5      | 1.61%   |
| Seagate ST9250315AS 250GB          | 4         | 4      | 1.61%   |
| Seagate ST500LT012-9WS142 500GB    | 4         | 4      | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 5      | 1.61%   |
| Hitachi HTS545050B9A300 500GB      | 4         | 5      | 1.61%   |
| Hitachi HDP725050GLA360 500GB      | 4         | 8      | 1.61%   |
| WDC WD20EARS-00MVWB0 2TB           | 3         | 6      | 1.21%   |
| Toshiba MQ01ABD032 320GB           | 3         | 3      | 1.21%   |
| Toshiba DT01ACA200 2TB             | 3         | 5      | 1.21%   |
| Seagate ST9500420AS 500GB          | 3         | 3      | 1.21%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 10     | 1.21%   |
| Samsung Electronics HD160JJ 160GB  | 3         | 3      | 1.21%   |
| WDC WD5000AAKS-00A7B0 500GB        | 2         | 2      | 0.81%   |
| WDC WD3200BPVT-35ZEST0 320GB       | 2         | 6      | 0.81%   |
| WDC WD30EFRX-68EUZN0 3TB           | 2         | 3      | 0.81%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 2      | 0.81%   |
| Toshiba MK3259GSXP 320GB           | 2         | 3      | 0.81%   |
| Seagate STM3500418AS 499GB         | 2         | 2      | 0.81%   |
| Seagate ST9120822AS 120GB          | 2         | 3      | 0.81%   |
| Seagate ST3500320AS 500GB          | 2         | 3      | 0.81%   |
| Seagate ST340016A 40GB             | 2         | 3      | 0.81%   |
| Seagate ST3250820AS 250GB          | 2         | 2      | 0.81%   |
| Seagate ST3160812A 160GB           | 2         | 4      | 0.81%   |
| Seagate ST2000DM001-1CH164 2TB     | 2         | 2      | 0.81%   |
| Samsung Electronics SP0802N 80GB   | 2         | 2      | 0.81%   |
| Samsung Electronics HD161HJ 160GB  | 2         | 3      | 0.81%   |
| Samsung Electronics HD103SJ 1TB    | 2         | 2      | 0.81%   |
| OCZ VERTEX4 128GB SSD              | 2         | 2      | 0.81%   |
| Hitachi HTS722010K9SA00 100GB      | 2         | 2      | 0.81%   |
| Hitachi HTS547575A9E384 752GB      | 2         | 2      | 0.81%   |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 0.81%   |
| Hitachi HTS545025B9A300 250GB      | 2         | 2      | 0.81%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 3      | 0.81%   |
| Hitachi HDS721010DLE630 1TB        | 2         | 2      | 0.81%   |
| Hitachi HDS721010CLA330 1TB        | 2         | 3      | 0.81%   |
| Fujitsu MHZ2160BH G2 160GB         | 2         | 2      | 0.81%   |
| WDC WD800BB-56JKC0 80GB            | 1         | 1      | 0.4%    |
| WDC WD6000HLHX-01JJPV0 600GB       | 1         | 1      | 0.4%    |
| WDC WD5000LPVX-60V0TT0 500GB       | 1         | 2      | 0.4%    |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 0.4%    |
| WDC WD5000BPVT-24HXZT3 500GB       | 1         | 1      | 0.4%    |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 1      | 0.4%    |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 2      | 0.4%    |
| WDC WD5000AAKX-083CA1 500GB        | 1         | 1      | 0.4%    |
| WDC WD5000AAKX-00U6AA0 500GB       | 1         | 1      | 0.4%    |
| WDC WD5000AAKX-001CA0 500GB        | 1         | 1      | 0.4%    |
| WDC WD5000AAKS-00UU3A0 500GB       | 1         | 1      | 0.4%    |
| WDC WD5000AAKB-00H8A0 500GB        | 1         | 1      | 0.4%    |
| WDC WD5000AADS-56S9B0 500GB        | 1         | 1      | 0.4%    |
| WDC WD400EB-00CPF0 40GB            | 1         | 1      | 0.4%    |
| WDC WD4003FZEX-00Z4SA0 4TB         | 1         | 1      | 0.4%    |
| WDC WD3200BEVT-80A0RT0 320GB       | 1         | 2      | 0.4%    |
| WDC WD3200BEVT-60A23T0 320GB       | 1         | 1      | 0.4%    |
| WDC WD3200BEVT-22A23T0 320GB       | 1         | 2      | 0.4%    |
| WDC WD3200BEVT-22A0RT0 320GB       | 1         | 1      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 81     | 25.42%  |
| WDC                 | 57        | 73     | 23.75%  |
| Hitachi             | 41        | 54     | 17.08%  |
| Toshiba             | 22        | 28     | 9.17%   |
| Samsung Electronics | 20        | 30     | 8.33%   |
| HGST                | 8         | 9      | 3.33%   |
| Fujitsu             | 6         | 7      | 2.5%    |
| Kingston            | 5         | 5      | 2.08%   |
| OCZ                 | 4         | 4      | 1.67%   |
| Crucial             | 3         | 3      | 1.25%   |
| Maxtor              | 2         | 2      | 0.83%   |
| WD MediaMax         | 1         | 1      | 0.42%   |
| SK hynix            | 1         | 1      | 0.42%   |
| SanDisk             | 1         | 1      | 0.42%   |
| PNY                 | 1         | 3      | 0.42%   |
| OCZ-VERTEX3         | 1         | 2      | 0.42%   |
| Micron Technology   | 1         | 1      | 0.42%   |
| LITEONIT            | 1         | 1      | 0.42%   |
| KingSpec            | 1         | 6      | 0.42%   |
| Intel               | 1         | 1      | 0.42%   |
| Corsair             | 1         | 3      | 0.42%   |
| A-DATA Technology   | 1         | 1      | 0.42%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 81     | 27.98%  |
| WDC                 | 57        | 73     | 26.15%  |
| Hitachi             | 41        | 54     | 18.81%  |
| Toshiba             | 22        | 28     | 10.09%  |
| Samsung Electronics | 20        | 30     | 9.17%   |
| HGST                | 8         | 9      | 3.67%   |
| Fujitsu             | 6         | 7      | 2.75%   |
| Maxtor              | 2         | 2      | 0.92%   |
| WD MediaMax         | 1         | 1      | 0.46%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 201       | 285    | 90.13%  |
| SSD  | 20        | 30     | 8.97%   |
| NVMe | 2         | 2      | 0.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-80HXZT3 500GB      | 1         | 1      | 16.67%  |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 16.67%  |
| Samsung Electronics HM500JI 500GB | 1         | 1      | 16.67%  |
| Maxtor STM380211AS 80GB           | 1         | 1      | 16.67%  |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 33.33%  |
| Seagate             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Maxtor              | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 486       | 927    | 51.37%  |
| Detected | 234       | 406    | 24.74%  |
| Malfunc  | 220       | 317    | 23.26%  |
| Failed   | 6         | 6      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 540       | 56.25%  |
| AMD                              | 185       | 19.27%  |
| Samsung Electronics              | 52        | 5.42%   |
| Nvidia                           | 47        | 4.9%    |
| SK hynix                         | 24        | 2.5%    |
| JMicron Technology               | 19        | 1.98%   |
| SanDisk                          | 18        | 1.88%   |
| Kingston Technology Company      | 17        | 1.77%   |
| Marvell Technology Group         | 8         | 0.83%   |
| Micron Technology                | 7         | 0.73%   |
| ASMedia Technology               | 7         | 0.73%   |
| Toshiba America Info Systems     | 6         | 0.63%   |
| Silicon Motion                   | 5         | 0.52%   |
| VIA Technologies                 | 4         | 0.42%   |
| Silicon Integrated Systems [SiS] | 4         | 0.42%   |
| Phison Electronics               | 4         | 0.42%   |
| Realtek Semiconductor            | 3         | 0.31%   |
| Lenovo                           | 2         | 0.21%   |
| KIOXIA                           | 2         | 0.21%   |
| ADATA Technology                 | 2         | 0.21%   |
| Synopsys                         | 1         | 0.1%    |
| Silicon Image                    | 1         | 0.1%    |
| Integrated Technology Express    | 1         | 0.1%    |
| Broadcom / LSI                   | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 88        | 7.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 55        | 4.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 45        | 3.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 44        | 3.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 40        | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 34        | 2.88%   |
| Nvidia MCP61 SATA Controller                                                            | 32        | 2.71%   |
| Nvidia MCP61 IDE                                                                        | 32        | 2.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 31        | 2.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 29        | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 28        | 2.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 27        | 2.29%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 24        | 2.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 19        | 1.61%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 18        | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 18        | 1.53%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 17        | 1.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 17        | 1.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 17        | 1.44%   |
| AMD 400 Series Chipset SATA Controller                                                  | 17        | 1.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 14        | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14        | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 13        | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12        | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12        | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11        | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11        | 0.93%   |
| AMD FCH IDE Controller                                                                  | 11        | 0.93%   |
| Samsung NVMe SSD Controller 980                                                         | 10        | 0.85%   |
| Intel SSD 660P Series                                                                   | 10        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 10        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10        | 0.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 9         | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 9         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 9         | 0.76%   |
| JMicron JMB368 IDE controller                                                           | 8         | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 8         | 0.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 8         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8         | 0.68%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 8         | 0.68%   |
| SK hynix BC511                                                                          | 7         | 0.59%   |
| Nvidia MCP65 IDE                                                                        | 7         | 0.59%   |
| Micron Non-Volatile memory controller                                                   | 7         | 0.59%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7         | 0.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 0.59%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7         | 0.59%   |
| Kingston Company Company Non-Volatile memory controller                                 | 6         | 0.51%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 6         | 0.51%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 6         | 0.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 6         | 0.51%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 6         | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5         | 0.42%   |
| Nvidia MCP65 SATA Controller                                                            | 5         | 0.42%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 5         | 0.42%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 619       | 60.81%  |
| IDE  | 218       | 21.41%  |
| NVMe | 152       | 14.93%  |
| RAID | 28        | 2.75%   |
| SCSI | 1         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 580       | 70.73%  |
| AMD    | 238       | 29.02%  |
| ARM    | 2         | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 14        | 1.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 12        | 1.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 1.09%   |
| AMD E-450 APU with Radeon HD Graphics         | 9         | 1.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 0.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 0.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 7         | 0.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 0.85%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 6         | 0.73%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 6         | 0.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 0.73%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.73%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 0.73%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 0.73%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 0.73%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 0.73%   |
| AMD Athlon 64 X2 Dual Core Processor 5600+    | 6         | 0.73%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.61%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 0.61%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.61%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 5         | 0.61%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.61%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 5         | 0.61%   |
| AMD Athlon II X2 240 Processor                | 5         | 0.61%   |
| AMD A4-4300M APU with Radeon HD Graphics      | 5         | 0.61%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 4         | 0.48%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 4         | 0.48%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 4         | 0.48%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.48%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 0.48%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 0.48%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.48%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 4         | 0.48%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 4         | 0.48%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 4         | 0.48%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 4         | 0.48%   |
| Intel Celeron CPU B800 @ 1.50GHz              | 4         | 0.48%   |
| Intel Atom CPU N570 @ 1.66GHz                 | 4         | 0.48%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 4         | 0.48%   |
| AMD Athlon II X2 245 Processor                | 4         | 0.48%   |
| AMD Athlon II X2 215 Processor                | 4         | 0.48%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+    | 4         | 0.48%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 0.36%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 3         | 0.36%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 0.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.36%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.36%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.36%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3         | 0.36%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.36%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 0.36%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 3         | 0.36%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.36%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 3         | 0.36%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 134       | 16.26%  |
| Intel Core i7                        | 88        | 10.68%  |
| Intel Celeron                        | 71        | 8.62%   |
| Intel Core i3                        | 67        | 8.13%   |
| Intel Pentium                        | 53        | 6.43%   |
| Intel Core 2 Duo                     | 41        | 4.98%   |
| Intel Atom                           | 34        | 4.13%   |
| AMD Ryzen 5                          | 34        | 4.13%   |
| Other                                | 25        | 3.03%   |
| AMD Athlon 64 X2                     | 23        | 2.79%   |
| AMD Athlon II X2                     | 21        | 2.55%   |
| AMD FX                               | 19        | 2.31%   |
| Intel Pentium Dual-Core              | 16        | 1.94%   |
| AMD Ryzen 3                          | 12        | 1.46%   |
| AMD E                                | 12        | 1.46%   |
| AMD A4                               | 12        | 1.46%   |
| Intel Xeon                           | 11        | 1.33%   |
| AMD Athlon II X3                     | 10        | 1.21%   |
| AMD A6                               | 10        | 1.21%   |
| AMD Ryzen 7                          | 9         | 1.09%   |
| Intel Pentium Dual                   | 8         | 0.97%   |
| AMD A10                              | 8         | 0.97%   |
| AMD E1                               | 7         | 0.85%   |
| Intel Pentium Silver                 | 6         | 0.73%   |
| AMD Phenom II X4                     | 6         | 0.73%   |
| AMD A8                               | 6         | 0.73%   |
| Intel Genuine                        | 5         | 0.61%   |
| Intel Core i9                        | 5         | 0.61%   |
| AMD Athlon X4                        | 5         | 0.61%   |
| AMD Athlon                           | 5         | 0.61%   |
| Intel Pentium 4                      | 4         | 0.49%   |
| AMD Turion II                        | 4         | 0.49%   |
| AMD Athlon II X4                     | 4         | 0.49%   |
| AMD Athlon II                        | 4         | 0.49%   |
| Intel Core 2 Solo                    | 3         | 0.36%   |
| Intel Core 2                         | 3         | 0.36%   |
| Intel Celeron Dual-Core              | 3         | 0.36%   |
| AMD Ryzen 9                          | 3         | 0.36%   |
| AMD Phenom II                        | 3         | 0.36%   |
| AMD E2                               | 3         | 0.36%   |
| Intel Pentium M                      | 2         | 0.24%   |
| AMD Turion 64 X2 Mobile              | 2         | 0.24%   |
| AMD Sempron                          | 2         | 0.24%   |
| AMD Athlon 64                        | 2         | 0.24%   |
| Intel Pentium Gold                   | 1         | 0.12%   |
| Intel Core Duo                       | 1         | 0.12%   |
| Intel Core 2 Quad                    | 1         | 0.12%   |
| Intel Core 2 Extreme                 | 1         | 0.12%   |
| Intel Celeron M                      | 1         | 0.12%   |
| ARM ARMv7                            | 1         | 0.12%   |
| ARM Allwinner                        | 1         | 0.12%   |
| AMD V140                             | 1         | 0.12%   |
| AMD Turion II Ultra Dual-Core Mobile | 1         | 0.12%   |
| AMD Turion II Dual-Core              | 1         | 0.12%   |
| AMD Ryzen 7 PRO                      | 1         | 0.12%   |
| AMD Ryzen 3 PRO                      | 1         | 0.12%   |
| AMD Phenom II X6                     | 1         | 0.12%   |
| AMD Phenom II X3                     | 1         | 0.12%   |
| AMD Phenom II X2                     | 1         | 0.12%   |
| AMD Phenom                           | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 433       | 51.86%  |
| 4       | 234       | 28.02%  |
| 6       | 48        | 5.75%   |
| 1       | 47        | 5.63%   |
| Unknown | 35        | 4.19%   |
| 8       | 18        | 2.16%   |
| 3       | 16        | 1.92%   |
| 10      | 3         | 0.36%   |
| 12      | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 819       | 99.88%  |
| 2      | 1         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 404       | 48.27%  |
| 2       | 398       | 47.55%  |
| Unknown | 35        | 4.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 784       | 95.38%  |
| Unknown        | 21        | 2.55%   |
| 32-bit         | 17        | 2.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 99        | 11.81%  |
| 0x206a7    | 64        | 7.64%   |
| 0x306a9    | 57        | 6.8%    |
| 0x1067a    | 42        | 5.01%   |
| 0x306c3    | 37        | 4.42%   |
| 0x010000c8 | 36        | 4.3%    |
| 0x806ea    | 23        | 2.74%   |
| 0x906ea    | 20        | 2.39%   |
| 0x30678    | 19        | 2.27%   |
| 0x806ec    | 17        | 2.03%   |
| 0x806c1    | 17        | 2.03%   |
| 0x06001119 | 17        | 2.03%   |
| 0x6fd      | 16        | 1.91%   |
| 0x106ca    | 15        | 1.79%   |
| 0x406e3    | 14        | 1.67%   |
| 0x05000119 | 14        | 1.67%   |
| 0x40651    | 13        | 1.55%   |
| 0x010000c7 | 13        | 1.55%   |
| 0x506c9    | 12        | 1.43%   |
| 0x306d4    | 12        | 1.43%   |
| 0x506e3    | 11        | 1.31%   |
| 0x906e9    | 10        | 1.19%   |
| 0x806e9    | 10        | 1.19%   |
| 0x10676    | 9         | 1.07%   |
| 0x10661    | 9         | 1.07%   |
| 0x08108102 | 9         | 1.07%   |
| 0x06000852 | 9         | 1.07%   |
| 0x03000027 | 8         | 0.95%   |
| 0x706a1    | 7         | 0.84%   |
| 0x6fb      | 7         | 0.84%   |
| 0x20652    | 7         | 0.84%   |
| 0x106c2    | 7         | 0.84%   |
| 0x08101016 | 7         | 0.84%   |
| 0x406c4    | 6         | 0.72%   |
| 0x406c3    | 6         | 0.72%   |
| 0x20655    | 6         | 0.72%   |
| 0x106e5    | 6         | 0.72%   |
| 0x0700010f | 6         | 0.72%   |
| 0x0600084f | 6         | 0.72%   |
| 0x906ed    | 5         | 0.6%    |
| 0x806eb    | 5         | 0.6%    |
| 0x706e5    | 5         | 0.6%    |
| 0x30661    | 5         | 0.6%    |
| 0x0810100b | 5         | 0.6%    |
| 0x0800820d | 5         | 0.6%    |
| 0x06006705 | 5         | 0.6%    |
| 0x010000db | 5         | 0.6%    |
| 0x0a50000c | 4         | 0.48%   |
| 0x08600104 | 4         | 0.48%   |
| 0x07030105 | 4         | 0.48%   |
| 0x806d1    | 3         | 0.36%   |
| 0x6fa      | 3         | 0.36%   |
| 0x30673    | 3         | 0.36%   |
| 0x08600106 | 3         | 0.36%   |
| 0x08600103 | 3         | 0.36%   |
| 0x08001137 | 3         | 0.36%   |
| 0x06003106 | 3         | 0.36%   |
| 0x0600111f | 3         | 0.36%   |
| 0xf49      | 2         | 0.24%   |
| 0x6f6      | 2         | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 106       | 12.85%  |
| SandyBridge   | 68        | 8.24%   |
| K10           | 62        | 7.52%   |
| IvyBridge     | 62        | 7.52%   |
| Haswell       | 57        | 6.91%   |
| Penryn        | 55        | 6.67%   |
| Core          | 42        | 5.09%   |
| Silvermont    | 35        | 4.24%   |
| Piledriver    | 34        | 4.12%   |
| Skylake       | 30        | 3.64%   |
| K8 Hammer     | 29        | 3.52%   |
| Bonnell       | 27        | 3.27%   |
| Zen           | 20        | 2.42%   |
| Zen+          | 19        | 2.3%    |
| TigerLake     | 18        | 2.18%   |
| Zen 2         | 16        | 1.94%   |
| Bobcat        | 15        | 1.82%   |
| Westmere      | 14        | 1.7%    |
| Goldmont      | 14        | 1.7%    |
| Broadwell     | 13        | 1.58%   |
| Icelake       | 10        | 1.21%   |
| Unknown       | 10        | 1.21%   |
| Goldmont plus | 9         | 1.09%   |
| K10 Llano     | 8         | 0.97%   |
| Excavator     | 8         | 0.97%   |
| Zen 3         | 6         | 0.73%   |
| NetBurst      | 6         | 0.73%   |
| Nehalem       | 6         | 0.73%   |
| Jaguar        | 6         | 0.73%   |
| Puma          | 5         | 0.61%   |
| P6            | 5         | 0.61%   |
| Bulldozer     | 4         | 0.48%   |
| Steamroller   | 3         | 0.36%   |
| CometLake     | 2         | 0.24%   |
| Tremont       | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 447       | 44.26%  |
| Nvidia                           | 338       | 33.47%  |
| AMD                              | 219       | 21.68%  |
| Silicon Integrated Systems [SiS] | 3         | 0.3%    |
| Matrox Electronics Systems       | 1         | 0.1%    |
| ATI Technologies                 | 1         | 0.1%    |
| ASPEED Technology                | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 52        | 4.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 42        | 3.93%   |
| Intel UHD Graphics 620                                                                   | 25        | 2.34%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 25        | 2.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22        | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 1.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 1.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 1.5%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.4%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 15        | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 1.22%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 13        | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.12%   |
| AMD Renoir                                                                               | 12        | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 1.12%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 11        | 1.03%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.03%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 0.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 0.94%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.94%   |
| Intel HD Graphics 620                                                                    | 9         | 0.84%   |
| Intel HD Graphics 500                                                                    | 9         | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 0.84%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 9         | 0.84%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 8         | 0.75%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 8         | 0.75%   |
| Intel HD Graphics 630                                                                    | 8         | 0.75%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 8         | 0.75%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 8         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.66%   |
| Nvidia GM108M [GeForce MX110]                                                            | 7         | 0.66%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 7         | 0.66%   |
| Nvidia GM108M [GeForce 840M]                                                             | 7         | 0.66%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 7         | 0.66%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 7         | 0.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 0.66%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 7         | 0.66%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 0.66%   |
| Nvidia GT218 [GeForce 210]                                                               | 6         | 0.56%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 6         | 0.56%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 6         | 0.56%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 6         | 0.56%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 6         | 0.56%   |
| Intel HD Graphics 530                                                                    | 6         | 0.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.56%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 6         | 0.56%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 6         | 0.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.56%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 6         | 0.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.47%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 5         | 0.47%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.47%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 0.47%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.47%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 5         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 267       | 32.44%  |
| 1 x Nvidia     | 194       | 23.57%  |
| 1 x AMD        | 145       | 17.62%  |
| Intel + Nvidia | 134       | 16.28%  |
| Intel + AMD    | 40        | 4.86%   |
| 2 x AMD        | 27        | 3.28%   |
| AMD + Nvidia   | 8         | 0.97%   |
| 1 x SiS        | 3         | 0.36%   |
| Other          | 2         | 0.24%   |
| 2 x Nvidia     | 1         | 0.12%   |
| 1 x Matrox     | 1         | 0.12%   |
| 1 x ASPEED     | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 666       | 78.82%  |
| Proprietary | 140       | 16.57%  |
| Unknown     | 39        | 4.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 264       | 31.02%  |
| 1.01-2.0   | 223       | 26.2%   |
| 0.01-0.5   | 191       | 22.44%  |
| 0.51-1.0   | 90        | 10.58%  |
| 3.01-4.0   | 54        | 6.35%   |
| 7.01-8.0   | 12        | 1.41%   |
| 5.01-6.0   | 10        | 1.18%   |
| 8.01-16.0  | 4         | 0.47%   |
| 2.01-3.0   | 2         | 0.24%   |
| 4.01-5.0   | 1         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 143       | 16.78%  |
| AU Optronics            | 120       | 14.08%  |
| Goldstar                | 86        | 10.09%  |
| LG Display              | 70        | 8.22%   |
| Chimei Innolux          | 68        | 7.98%   |
| BOE                     | 65        | 7.63%   |
| Chi Mei Optoelectronics | 45        | 5.28%   |
| Dell                    | 35        | 4.11%   |
| Philips                 | 33        | 3.87%   |
| BenQ                    | 28        | 3.29%   |
| AOC                     | 17        | 2%      |
| ViewSonic               | 13        | 1.53%   |
| PANDA                   | 12        | 1.41%   |
| Lenovo                  | 10        | 1.17%   |
| HannStar                | 9         | 1.06%   |
| CPT                     | 9         | 1.06%   |
| Acer                    | 9         | 1.06%   |
| NEC Computers           | 7         | 0.82%   |
| Hewlett-Packard         | 7         | 0.82%   |
| Ancor Communications    | 7         | 0.82%   |
| Sharp                   | 6         | 0.7%    |
| LG Philips              | 6         | 0.7%    |
| Unknown                 | 5         | 0.59%   |
| Sony                    | 5         | 0.59%   |
| Iiyama                  | 5         | 0.59%   |
| LG Electronics          | 4         | 0.47%   |
| XYK                     | 3         | 0.35%   |
| ASUSTek Computer        | 3         | 0.35%   |
| Apple                   | 3         | 0.35%   |
| Plain Tree Systems      | 2         | 0.23%   |
| LGD                     | 2         | 0.23%   |
| Toshiba                 | 1         | 0.12%   |
| SKK                     | 1         | 0.12%   |
| Seiko/Epson             | 1         | 0.12%   |
| Quanta Display          | 1         | 0.12%   |
| PCL                     | 1         | 0.12%   |
| Packard Bell            | 1         | 0.12%   |
| MStar                   | 1         | 0.12%   |
| MiTAC                   | 1         | 0.12%   |
| Lenovo Group Limited    | 1         | 0.12%   |
| KDC                     | 1         | 0.12%   |
| ITE                     | 1         | 0.12%   |
| InnoLux Display         | 1         | 0.12%   |
| IBM                     | 1         | 0.12%   |
| Eizo                    | 1         | 0.12%   |
| BBK                     | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 1.5%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 10        | 1.16%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 1.04%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 7         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 6         | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.69%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 350x190mm 15.7-inch | 6         | 0.69%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 6         | 0.69%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.69%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 6         | 0.69%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch            | 6         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 5         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 5         | 0.58%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                     | 5         | 0.58%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 5         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 5         | 0.58%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch            | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.58%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 4         | 0.46%   |
| Goldstar L1919S GSM4AF2 1280x1024 376x301mm 19.0-inch                    | 4         | 0.46%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 4         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 4         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.46%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.46%   |
| XYK Monitor XYK2360 1920x1080 477x268mm 21.5-inch                        | 3         | 0.35%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 3         | 0.35%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 3         | 0.35%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch    | 3         | 0.35%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 3         | 0.35%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 3         | 0.35%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 3         | 0.35%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 3         | 0.35%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                      | 3         | 0.35%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch                 | 3         | 0.35%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 3         | 0.35%   |
| Goldstar L1953S GSM4B3E 1280x1024 376x301mm 19.0-inch                    | 3         | 0.35%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 3         | 0.35%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                       | 3         | 0.35%   |
| Dell U2312HM DEL4071 1920x1080 510x287mm 23.0-inch                       | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 3         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1680 1366x768 344x193mm 15.5-inch | 3         | 0.35%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.35%   |
| BenQ G2220HDA BNQ7820 1920x1080 477x268mm 21.5-inch                      | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 3         | 0.35%   |
| ViewSonic VX2370 SERIES VSC342C 1920x1080 509x286mm 23.0-inch            | 2         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 317       | 38.1%   |
| 1366x768 (WXGA)    | 230       | 27.64%  |
| 1280x1024 (SXGA)   | 57        | 6.85%   |
| 1600x900 (HD+)     | 42        | 5.05%   |
| 3840x2160 (4K)     | 27        | 3.25%   |
| 1440x900 (WXGA+)   | 27        | 3.25%   |
| 1280x800 (WXGA)    | 26        | 3.13%   |
| 1680x1050 (WSXGA+) | 23        | 2.76%   |
| 1024x600           | 20        | 2.4%    |
| 2560x1440 (QHD)    | 18        | 2.16%   |
| 2560x1080          | 9         | 1.08%   |
| 1920x1200 (WUXGA)  | 7         | 0.84%   |
| 1360x768           | 4         | 0.48%   |
| 1024x768 (XGA)     | 4         | 0.48%   |
| 2288x1287          | 3         | 0.36%   |
| 3440x1440          | 2         | 0.24%   |
| 1600x1200          | 2         | 0.24%   |
| 1152x864           | 2         | 0.24%   |
| Unknown            | 2         | 0.24%   |
| 4480x1200          | 1         | 0.12%   |
| 3840x2400          | 1         | 0.12%   |
| 3840x1080          | 1         | 0.12%   |
| 2880x1800          | 1         | 0.12%   |
| 2736x1824          | 1         | 0.12%   |
| 2560x1600          | 1         | 0.12%   |
| 2048x1536          | 1         | 0.12%   |
| 1920x540           | 1         | 0.12%   |
| 1680x945           | 1         | 0.12%   |
| 1400x1050          | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 327       | 38.43%  |
| 17      | 70        | 8.23%   |
| 21      | 64        | 7.52%   |
| 23      | 55        | 6.46%   |
| 19      | 51        | 5.99%   |
| 13      | 41        | 4.82%   |
| 14      | 37        | 4.35%   |
| 24      | 36        | 4.23%   |
| 27      | 29        | 3.41%   |
| Unknown | 23        | 2.7%    |
| 18      | 20        | 2.35%   |
| 10      | 20        | 2.35%   |
| 22      | 14        | 1.65%   |
| 20      | 11        | 1.29%   |
| 34      | 10        | 1.18%   |
| 31      | 8         | 0.94%   |
| 11      | 6         | 0.71%   |
| 72      | 4         | 0.47%   |
| 12      | 4         | 0.47%   |
| 142     | 3         | 0.35%   |
| 54      | 3         | 0.35%   |
| 40      | 3         | 0.35%   |
| 16      | 3         | 0.35%   |
| 52      | 2         | 0.24%   |
| 46      | 2         | 0.24%   |
| 84      | 1         | 0.12%   |
| 55      | 1         | 0.12%   |
| 42      | 1         | 0.12%   |
| 9       | 1         | 0.12%   |
| 8       | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 400       | 47.56%  |
| 401-500        | 124       | 14.74%  |
| 501-600        | 111       | 13.2%   |
| 351-400        | 88        | 10.46%  |
| 201-300        | 52        | 6.18%   |
| Unknown        | 23        | 2.73%   |
| 601-700        | 11        | 1.31%   |
| 701-800        | 10        | 1.19%   |
| 1001-1500      | 8         | 0.95%   |
| 1501-2000      | 5         | 0.59%   |
| More than 2000 | 3         | 0.36%   |
| 801-900        | 3         | 0.36%   |
| 101-200        | 2         | 0.24%   |
| 901-1000       | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 614       | 76.18%  |
| 16/10   | 87        | 10.79%  |
| 5/4     | 54        | 6.7%    |
| Unknown | 21        | 2.61%   |
| 4/3     | 12        | 1.49%   |
| 21/9    | 10        | 1.24%   |
| 3/2     | 4         | 0.5%    |
| 1.00    | 4         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 329       | 38.84%  |
| 201-250        | 141       | 16.65%  |
| 151-200        | 77        | 9.09%   |
| 81-90          | 57        | 6.73%   |
| 141-150        | 39        | 4.6%    |
| 121-130        | 37        | 4.37%   |
| 301-350        | 29        | 3.42%   |
| Unknown        | 23        | 2.72%   |
| 41-50          | 21        | 2.48%   |
| 71-80          | 19        | 2.24%   |
| 351-500        | 18        | 2.13%   |
| More than 1000 | 14        | 1.65%   |
| 251-300        | 12        | 1.42%   |
| 131-140        | 11        | 1.3%    |
| 51-60          | 6         | 0.71%   |
| 501-1000       | 6         | 0.71%   |
| 61-70          | 4         | 0.47%   |
| 111-120        | 2         | 0.24%   |
| 1-40           | 1         | 0.12%   |
| 91-100         | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 295       | 35.5%   |
| 101-120       | 291       | 35.02%  |
| 121-160       | 174       | 20.94%  |
| Unknown       | 23        | 2.77%   |
| 1-50          | 19        | 2.29%   |
| 161-240       | 17        | 2.05%   |
| More than 240 | 12        | 1.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 728       | 88.03%  |
| 2     | 73        | 8.83%   |
| 0     | 24        | 2.9%    |
| 3     | 2         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 493       | 40.21%  |
| Qualcomm Atheros                       | 233       | 19%     |
| Intel                                  | 209       | 17.05%  |
| Broadcom                               | 97        | 7.91%   |
| Nvidia                                 | 35        | 2.85%   |
| Marvell Technology Group               | 29        | 2.37%   |
| Ralink Technology                      | 19        | 1.55%   |
| Ralink                                 | 17        | 1.39%   |
| TP-Link                                | 16        | 1.31%   |
| Broadcom Limited                       | 15        | 1.22%   |
| Huawei Technologies                    | 6         | 0.49%   |
| VIA Technologies                       | 5         | 0.41%   |
| D-Link                                 | 5         | 0.41%   |
| JMicron Technology                     | 4         | 0.33%   |
| Xiaomi                                 | 3         | 0.24%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.24%   |
| Sierra Wireless                        | 3         | 0.24%   |
| MediaTek                               | 3         | 0.24%   |
| D-Link System                          | 3         | 0.24%   |
| Attansic Technology                    | 3         | 0.24%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.16%   |
| Qualcomm Atheros Communications        | 2         | 0.16%   |
| Qualcomm                               | 2         | 0.16%   |
| IMC Networks                           | 2         | 0.16%   |
| Hewlett-Packard                        | 2         | 0.16%   |
| Fibocom                                | 2         | 0.16%   |
| Aquantia                               | 2         | 0.16%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.08%   |
| Texas Instruments                      | 1         | 0.08%   |
| STMicroelectronics                     | 1         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| Samsung Electronics                    | 1         | 0.08%   |
| Motorola PCS                           | 1         | 0.08%   |
| Microsoft                              | 1         | 0.08%   |
| Lenovo                                 | 1         | 0.08%   |
| HTC (High Tech Computer)               | 1         | 0.08%   |
| HMD Global                             | 1         | 0.08%   |
| Davicom Semiconductor                  | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 356       | 25.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 95        | 6.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 47        | 3.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 38        | 2.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 33        | 2.36%   |
| Intel Wireless 8265 / 8275                                              | 32        | 2.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 30        | 2.15%   |
| Nvidia MCP61 Ethernet                                                   | 26        | 1.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 20        | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 1.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 1.07%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 1%      |
| Intel Wi-Fi 6 AX200                                                     | 14        | 1%      |
| Ralink MT7601U Wireless Adapter                                         | 13        | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 13        | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 0.93%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 12        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 0.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 0.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 11        | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 9         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                    | 9         | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 8         | 0.57%   |
| Intel Wireless 7260                                                     | 8         | 0.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.5%    |
| Intel Wireless 7265                                                     | 7         | 0.5%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.5%    |
| Intel I211 Gigabit Network Connection                                   | 7         | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 6         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 6         | 0.43%   |
| Intel Wireless 8260                                                     | 6         | 0.43%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 6         | 0.43%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 6         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.36%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 0.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.36%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 5         | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 5         | 0.36%   |
| Intel WiFi Link 5100                                                    | 5         | 0.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 0.36%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 4         | 0.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 0.29%   |
| Ralink RT5370 Wireless Adapter                                          | 4         | 0.29%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 4         | 0.29%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.29%   |
| Intel Wireless 3165                                                     | 4         | 0.29%   |
| Intel Centrino Wireless-N 130                                           | 4         | 0.29%   |
| Intel 82579V Gigabit Network Connection                                 | 4         | 0.29%   |
| Intel 82566MM Gigabit Network Connection                                | 4         | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 183       | 29.37%  |
| Intel                           | 178       | 28.57%  |
| Realtek Semiconductor           | 111       | 17.82%  |
| Broadcom                        | 70        | 11.24%  |
| Ralink Technology               | 19        | 3.05%   |
| Ralink                          | 17        | 2.73%   |
| TP-Link                         | 14        | 2.25%   |
| Broadcom Limited                | 9         | 1.44%   |
| D-Link                          | 5         | 0.8%    |
| Sierra Wireless                 | 3         | 0.48%   |
| MediaTek                        | 3         | 0.48%   |
| Qualcomm Atheros Communications | 2         | 0.32%   |
| IMC Networks                    | 2         | 0.32%   |
| Texas Instruments               | 1         | 0.16%   |
| Qualcomm                        | 1         | 0.16%   |
| Microsoft                       | 1         | 0.16%   |
| Marvell Technology Group        | 1         | 0.16%   |
| Hewlett-Packard                 | 1         | 0.16%   |
| Fibocom                         | 1         | 0.16%   |
| D-Link System                   | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 47        | 7.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 38        | 6.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 33        | 5.28%   |
| Intel Wireless 8265 / 8275                                              | 32        | 5.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 30        | 4.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 3.84%   |
| Broadcom BCM43142 802.11b/g/n                                           | 20        | 3.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 2.4%    |
| Intel Wi-Fi 6 AX201                                                     | 14        | 2.24%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 2.24%   |
| Ralink MT7601U Wireless Adapter                                         | 13        | 2.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 1.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 1.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 1.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 1.28%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.28%   |
| Intel Wireless 7260                                                     | 8         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 1.12%   |
| Intel Wireless 7265                                                     | 7         | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.96%   |
| Intel Wireless 8260                                                     | 6         | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.8%    |
| Intel WiFi Link 5100                                                    | 5         | 0.8%    |
| Ralink RT5370 Wireless Adapter                                          | 4         | 0.64%   |
| Intel Wireless 3165                                                     | 4         | 0.64%   |
| Intel Centrino Wireless-N 130                                           | 4         | 0.64%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 0.64%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.64%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.48%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 3         | 0.48%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.48%   |
| Intel Wireless 3160                                                     | 3         | 0.48%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.48%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.48%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.48%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.48%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 3         | 0.48%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.48%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 2         | 0.32%   |
| TP-Link TL-WN722N v2                                                    | 2         | 0.32%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 2         | 0.32%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 2         | 0.32%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 2         | 0.32%   |
| TP-Link 802.11n NIC                                                     | 2         | 0.32%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.32%   |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 0.32%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 470       | 62.09%  |
| Qualcomm Atheros                       | 78        | 10.3%   |
| Intel                                  | 66        | 8.72%   |
| Broadcom                               | 37        | 4.89%   |
| Nvidia                                 | 35        | 4.62%   |
| Marvell Technology Group               | 28        | 3.7%    |
| Broadcom Limited                       | 6         | 0.79%   |
| VIA Technologies                       | 5         | 0.66%   |
| JMicron Technology                     | 4         | 0.53%   |
| Xiaomi                                 | 3         | 0.4%    |
| Sundance Technology Inc / IC Plus      | 3         | 0.4%    |
| Huawei Technologies                    | 3         | 0.4%    |
| Attansic Technology                    | 3         | 0.4%    |
| TP-Link                                | 2         | 0.26%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.26%   |
| D-Link System                          | 2         | 0.26%   |
| Aquantia                               | 2         | 0.26%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.13%   |
| Samsung Electronics                    | 1         | 0.13%   |
| Qualcomm                               | 1         | 0.13%   |
| Motorola PCS                           | 1         | 0.13%   |
| Lenovo                                 | 1         | 0.13%   |
| HTC (High Tech Computer)               | 1         | 0.13%   |
| HMD Global                             | 1         | 0.13%   |
| Davicom Semiconductor                  | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 356       | 46.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 95        | 12.43%  |
| Nvidia MCP61 Ethernet                                                          | 26        | 3.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 13        | 1.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 12        | 1.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 11        | 1.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 9         | 1.18%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 9         | 1.18%   |
| Intel Ethernet Connection (2) I219-V                                           | 9         | 1.18%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 8         | 1.05%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 0.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 6         | 0.79%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 6         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 5         | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 5         | 0.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 0.65%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 4         | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 0.52%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 4         | 0.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 4         | 0.52%   |
| Intel 82579V Gigabit Network Connection                                        | 4         | 0.52%   |
| Intel 82566MM Gigabit Network Connection                                       | 4         | 0.52%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.39%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 3         | 0.39%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.39%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 3         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 0.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.39%   |
| Nvidia MCP65 Ethernet                                                          | 3         | 0.39%   |
| Nvidia MCP55 Ethernet                                                          | 3         | 0.39%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 3         | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 3         | 0.39%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 3         | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.39%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.39%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.39%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.39%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.39%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 3         | 0.39%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.26%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.26%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.26%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.26%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.26%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.26%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.26%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.26%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 2         | 0.26%   |
| Intel WiMAX Connection 2400m                                                   | 2         | 0.26%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.26%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.26%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.26%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.26%   |
| Huawei JNY-LX1                                                                 | 2         | 0.26%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 2         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 730       | 54.68%  |
| WiFi     | 597       | 44.72%  |
| Modem    | 6         | 0.45%   |
| Unknown  | 2         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 506       | 58.91%  |
| Ethernet | 353       | 41.09%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 481       | 58.59%  |
| 1     | 322       | 39.22%  |
| 0     | 12        | 1.46%   |
| 3     | 6         | 0.73%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 813       | 98.67%  |
| Yes  | 11        | 1.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 143       | 32.43%  |
| Realtek Semiconductor           | 59        | 13.38%  |
| Qualcomm Atheros Communications | 50        | 11.34%  |
| Broadcom                        | 32        | 7.26%   |
| IMC Networks                    | 29        | 6.58%   |
| Lite-On Technology              | 24        | 5.44%   |
| Cambridge Silicon Radio         | 22        | 4.99%   |
| Foxconn / Hon Hai               | 19        | 4.31%   |
| ASUSTek Computer                | 14        | 3.17%   |
| Ralink                          | 10        | 2.27%   |
| Foxconn International           | 10        | 2.27%   |
| Hewlett-Packard                 | 6         | 1.36%   |
| Toshiba                         | 5         | 1.13%   |
| Taiyo Yuden                     | 2         | 0.45%   |
| Ralink Technology               | 2         | 0.45%   |
| Qcom                            | 2         | 0.45%   |
| Integrated System Solution      | 2         | 0.45%   |
| Dell                            | 2         | 0.45%   |
| Apple                           | 2         | 0.45%   |
| USI                             | 1         | 0.23%   |
| Realtek                         | 1         | 0.23%   |
| Micro Star International        | 1         | 0.23%   |
| MediaTek                        | 1         | 0.23%   |
| Marvell Semiconductor           | 1         | 0.23%   |
| Alps Electric                   | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 61        | 13.83%  |
| Realtek Bluetooth Radio                             | 39        | 8.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 7.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22        | 4.99%   |
| Intel AX201 Bluetooth                               | 21        | 4.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 17        | 3.85%   |
| Intel AX200 Bluetooth                               | 14        | 3.17%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 13        | 2.95%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 2.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 2.27%   |
| Ralink RT3290 Bluetooth                             | 10        | 2.27%   |
| Foxconn International BCM43142A0 Bluetooth module   | 10        | 2.27%   |
| Lite-On Bluetooth Device                            | 9         | 2.04%   |
| IMC Networks Bluetooth Radio                        | 9         | 2.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 9         | 2.04%   |
| IMC Networks Bluetooth Device                       | 8         | 1.81%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 7         | 1.59%   |
| Qualcomm Atheros Bluetooth                          | 6         | 1.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.36%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 1.36%   |
| Broadcom BCM2070 Bluetooth Device                   | 6         | 1.36%   |
| Realtek RTL8723B Bluetooth                          | 5         | 1.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.13%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 1.13%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.91%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.91%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 0.91%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.68%   |
| IMC Networks Bluetooth USB Host Controller          | 3         | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.68%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.68%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 0.68%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 0.68%   |
| ASUS BT-270 Bluetooth Adapter                       | 3         | 0.68%   |
| ASUS BT-253 Bluetooth Adapter                       | 3         | 0.68%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.45%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 2         | 0.45%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 2         | 0.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.45%   |
| Qcom Broadcom Bluetooth USB                         | 2         | 0.45%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.45%   |
| Integrated System Solution Bluetooth Device         | 2         | 0.45%   |
| IMC Networks Wireless_Device                        | 2         | 0.45%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.45%   |
| Foxconn / Hon Hai BCM43142A0                        | 2         | 0.45%   |
| Broadcom HP Portable Valentine                      | 2         | 0.45%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.45%   |
| ASUS Qualcomm Bluetooth 4.1                         | 2         | 0.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.45%   |
| ASUS Bluetooth Radio                                | 2         | 0.45%   |
| USI Bluetooth Module BCM92070                       | 1         | 0.23%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.23%   |
| Toshiba Bluetooth Device                            | 1         | 0.23%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.23%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.23%   |
| Realtek Bluetooth Radio                             | 1         | 0.23%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.23%   |
| Micro Star International Bluetooth EDR Device       | 1         | 0.23%   |
| MediaTek BT                                         | 1         | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 558       | 53.14%  |
| AMD                              | 225       | 21.43%  |
| Nvidia                           | 196       | 18.67%  |
| C-Media Electronics              | 13        | 1.24%   |
| Creative Labs                    | 10        | 0.95%   |
| Logitech                         | 6         | 0.57%   |
| JMTek                            | 5         | 0.48%   |
| Texas Instruments                | 4         | 0.38%   |
| Silicon Integrated Systems [SiS] | 4         | 0.38%   |
| Generalplus Technology           | 3         | 0.29%   |
| Conexant Systems                 | 3         | 0.29%   |
| SteelSeries ApS                  | 2         | 0.19%   |
| M-Audio                          | 2         | 0.19%   |
| GYROCOM C&C                      | 2         | 0.19%   |
| ESS Technology                   | 2         | 0.19%   |
| Yamaha                           | 1         | 0.1%    |
| VIA Technologies                 | 1         | 0.1%    |
| Tenx Technology                  | 1         | 0.1%    |
| ROCCAT                           | 1         | 0.1%    |
| Realtek Semiconductor            | 1         | 0.1%    |
| Plantronics                      | 1         | 0.1%    |
| Pixart Imaging                   | 1         | 0.1%    |
| NXP Semiconductors               | 1         | 0.1%    |
| iCreate Technologies             | 1         | 0.1%    |
| Huawei Technologies              | 1         | 0.1%    |
| GN Netcom                        | 1         | 0.1%    |
| Edifier Technology               | 1         | 0.1%    |
| Creative Technology              | 1         | 0.1%    |
| BEHRINGER International          | 1         | 0.1%    |
| ATI Technologies                 | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                                      | 78        | 6.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 74        | 5.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 52        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 51        | 4.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 48        | 3.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 46        | 3.69%   |
| AMD FCH Azalia Controller                                                                         | 44        | 3.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 39        | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 35        | 2.81%   |
| Nvidia MCP61 High Definition Audio                                                                | 31        | 2.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 27        | 2.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 27        | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 27        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 1.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 1.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 18        | 1.44%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 17        | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 17        | 1.36%   |
| Intel 8 Series HD Audio Controller                                                                | 17        | 1.36%   |
| Nvidia High Definition Audio Controller                                                           | 16        | 1.28%   |
| AMD Trinity HDMI Audio Controller                                                                 | 15        | 1.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 12        | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 12        | 0.96%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 0.96%   |
| AMD Wrestler HDMI Audio                                                                           | 11        | 0.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 11        | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 10        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 0.8%    |
| Intel 200 Series PCH HD Audio                                                                     | 10        | 0.8%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 10        | 0.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 10        | 0.8%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 9         | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 0.72%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 9         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 8         | 0.64%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 8         | 0.64%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 8         | 0.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 0.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 0.56%   |
| Nvidia MCP65 High Definition Audio                                                                | 7         | 0.56%   |
| Intel CM238 HD Audio Controller                                                                   | 7         | 0.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 6         | 0.48%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 6         | 0.48%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.48%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 0.48%   |
| AMD High Definition Audio Controller                                                              | 6         | 0.48%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 6         | 0.48%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.4%    |
| Nvidia GF106 High Definition Audio Controller                                                     | 5         | 0.4%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 5         | 0.4%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 5         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 175       | 23.46%  |
| Samsung Electronics   | 134       | 17.96%  |
| SK hynix              | 104       | 13.94%  |
| Kingston              | 102       | 13.67%  |
| Micron Technology     | 49        | 6.57%   |
| Crucial               | 45        | 6.03%   |
| Elpida                | 18        | 2.41%   |
| Ramaxel Technology    | 16        | 2.14%   |
| Nanya Technology      | 14        | 1.88%   |
| A-DATA Technology     | 13        | 1.74%   |
| Patriot               | 11        | 1.47%   |
| Corsair               | 11        | 1.47%   |
| Silicon Power         | 7         | 0.94%   |
| Goodram               | 6         | 0.8%    |
| G.Skill               | 6         | 0.8%    |
| ASint Technology      | 6         | 0.8%    |
| Transcend             | 4         | 0.54%   |
| Team                  | 3         | 0.4%    |
| GeIL                  | 3         | 0.4%    |
| Unknown (ABCD)        | 2         | 0.27%   |
| TakeMS                | 2         | 0.27%   |
| Qumo                  | 2         | 0.27%   |
| Kingmax               | 2         | 0.27%   |
| Apacer                | 2         | 0.27%   |
| 48spaces              | 2         | 0.27%   |
| Wilk Elektronik       | 1         | 0.13%   |
| SHARETRONIC           | 1         | 0.13%   |
| PNY                   | 1         | 0.13%   |
| Kllisre               | 1         | 0.13%   |
| Kingmax Semiconductor | 1         | 0.13%   |
| Goldkey               | 1         | 0.13%   |
| AMD                   | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 11        | 1.34%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s   | 9         | 1.1%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 8         | 0.97%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 7         | 0.85%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 6         | 0.73%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s              | 6         | 0.73%   |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 6         | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 6         | 0.73%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 6         | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s   | 6         | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s   | 6         | 0.73%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s     | 6         | 0.73%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 5         | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR2                        | 5         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s              | 5         | 0.61%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 5         | 0.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s               | 4         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 4         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s              | 4         | 0.49%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 4         | 0.49%   |
| Unknown RAM Module 1024MB DIMM DDR2                        | 4         | 0.49%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                     | 4         | 0.49%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s     | 4         | 0.49%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s     | 4         | 0.49%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s            | 4         | 0.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s      | 4         | 0.49%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s   | 4         | 0.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 4         | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s      | 4         | 0.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s      | 4         | 0.49%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s      | 4         | 0.49%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s    | 4         | 0.49%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s       | 4         | 0.49%   |
| Kingston RAM 99U5469-070.A00LF 4GB SODIMM DDR3             | 4         | 0.49%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 3         | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                    | 3         | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                    | 3         | 0.37%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 3         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR2                      | 3         | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                | 3         | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                 | 3         | 0.37%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 3         | 0.37%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                     | 3         | 0.37%   |
| Unknown RAM Module 1024MB DIMM                             | 3         | 0.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 3         | 0.37%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s     | 3         | 0.37%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 3         | 0.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 3         | 0.37%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s             | 3         | 0.37%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s      | 3         | 0.37%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1334MT/s      | 3         | 0.37%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s      | 3         | 0.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 3         | 0.37%   |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s | 3         | 0.37%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s       | 3         | 0.37%   |
| Micron RAM 8KTF51264HZ-1G9P2 4GB SODIMM DDR3 1867MT/s      | 3         | 0.37%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s      | 3         | 0.37%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 3         | 0.37%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s    | 3         | 0.37%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s        | 3         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 283       | 43.67%  |
| DDR4    | 152       | 23.46%  |
| DDR2    | 72        | 11.11%  |
| Unknown | 72        | 11.11%  |
| SDRAM   | 42        | 6.48%   |
| LPDDR4  | 13        | 2.01%   |
| DDR     | 9         | 1.39%   |
| DRAM    | 4         | 0.62%   |
| LPDDR3  | 1         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 377       | 59.18%  |
| DIMM         | 247       | 38.78%  |
| Row Of Chips | 13        | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 277       | 37.69%  |
| 2048  | 201       | 27.35%  |
| 8192  | 125       | 17.01%  |
| 1024  | 64        | 8.71%   |
| 16384 | 51        | 6.94%   |
| 512   | 14        | 1.9%    |
| 256   | 2         | 0.27%   |
| 16    | 1         | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 189       | 26.96%  |
| 2667    | 57        | 8.13%   |
| 1333    | 56        | 7.99%   |
| 2400    | 43        | 6.13%   |
| 800     | 43        | 6.13%   |
| 3200    | 40        | 5.71%   |
| 667     | 40        | 5.71%   |
| Unknown | 40        | 5.71%   |
| 1334    | 39        | 5.56%   |
| 2133    | 16        | 2.28%   |
| 1067    | 14        | 2%      |
| 1066    | 13        | 1.85%   |
| 4199    | 12        | 1.71%   |
| 533     | 12        | 1.71%   |
| 400     | 12        | 1.71%   |
| 3600    | 7         | 1%      |
| 1867    | 7         | 1%      |
| 3466    | 6         | 0.86%   |
| 3266    | 6         | 0.86%   |
| 2048    | 6         | 0.86%   |
| 333     | 6         | 0.86%   |
| 4267    | 5         | 0.71%   |
| 1866    | 5         | 0.71%   |
| 49926   | 2         | 0.29%   |
| 8400    | 2         | 0.29%   |
| 4266    | 2         | 0.29%   |
| 3733    | 2         | 0.29%   |
| 3400    | 2         | 0.29%   |
| 1800    | 2         | 0.29%   |
| 1639    | 2         | 0.29%   |
| 266     | 2         | 0.29%   |
| 65535   | 1         | 0.14%   |
| 3800    | 1         | 0.14%   |
| 3000    | 1         | 0.14%   |
| 2733    | 1         | 0.14%   |
| 2666    | 1         | 0.14%   |
| 2187    | 1         | 0.14%   |
| 2134    | 1         | 0.14%   |
| 666     | 1         | 0.14%   |
| 200     | 1         | 0.14%   |
| 133     | 1         | 0.14%   |
| 66      | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Canon                 | 6         | 28.57%  |
| Hewlett-Packard       | 5         | 23.81%  |
| Seiko Epson           | 4         | 19.05%  |
| Samsung Electronics   | 3         | 14.29%  |
| Ricoh                 | 1         | 4.76%   |
| QinHeng Electronics   | 1         | 4.76%   |
| Lexmark International | 1         | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Canon LBP6030/6030B/6018L         | 2         | 9.09%   |
| Seiko Epson M100 Series           | 1         | 4.55%   |
| Seiko Epson L805 Series           | 1         | 4.55%   |
| Seiko Epson L365 Series           | 1         | 4.55%   |
| Seiko Epson L220 Series           | 1         | 4.55%   |
| Samsung SCX-4300 Series           | 1         | 4.55%   |
| Samsung SCX-4200 series           | 1         | 4.55%   |
| Samsung Laser Printer             | 1         | 4.55%   |
| Ricoh SP 212SUw                   | 1         | 4.55%   |
| QinHeng CH340S                    | 1         | 4.55%   |
| Lexmark International Z35 Printer | 1         | 4.55%   |
| HP LaserJet P2055 series          | 1         | 4.55%   |
| HP LaserJet P1006                 | 1         | 4.55%   |
| HP LaserJet P1005                 | 1         | 4.55%   |
| HP LaserJet 1300                  | 1         | 4.55%   |
| HP DeskJet 840c                   | 1         | 4.55%   |
| Canon MF4410                      | 1         | 4.55%   |
| Canon MF4010 series               | 1         | 4.55%   |
| Canon MF3010                      | 1         | 4.55%   |
| Canon LBP6020                     | 1         | 4.55%   |
| Canon G1000 series                | 1         | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 4         | 66.67%  |
| Ultima Electronics | 1         | 16.67%  |
| Seiko Epson        | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 16.67%  |
| Seiko Epson Stylus Photo RX500/510                                                    | 1         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1         | 16.67%  |
| Canon CanoScan LiDE 600F                                                              | 1         | 16.67%  |
| Canon CanoScan LiDE 60                                                                | 1         | 16.67%  |
| Canon CanoScan LIDE 25                                                                | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 114       | 20.99%  |
| IMC Networks                           | 82        | 15.1%   |
| Acer                                   | 35        | 6.45%   |
| Logitech                               | 33        | 6.08%   |
| Realtek Semiconductor                  | 32        | 5.89%   |
| Suyin                                  | 30        | 5.52%   |
| Quanta                                 | 28        | 5.16%   |
| Sunplus Innovation Technology          | 23        | 4.24%   |
| Z-Star Microelectronics                | 22        | 4.05%   |
| Syntek                                 | 20        | 3.68%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 3.68%   |
| Silicon Motion                         | 19        | 3.5%    |
| Microdia                               | 16        | 2.95%   |
| Lite-On Technology                     | 15        | 2.76%   |
| Alcor Micro                            | 9         | 1.66%   |
| Apple                                  | 5         | 0.92%   |
| Samsung Electronics                    | 3         | 0.55%   |
| Microsoft                              | 3         | 0.55%   |
| Luxvisions Innotech Limited            | 3         | 0.55%   |
| lihappe8                               | 3         | 0.55%   |
| Lenovo                                 | 3         | 0.55%   |
| Importek                               | 3         | 0.55%   |
| DigiTech                               | 3         | 0.55%   |
| Cubeternet                             | 3         | 0.55%   |
| Aveo Technology                        | 3         | 0.55%   |
| Ricoh                                  | 2         | 0.37%   |
| Primax Electronics                     | 2         | 0.37%   |
| Arkmicro Technologies                  | 2         | 0.37%   |
| Sonix Technology                       | 1         | 0.18%   |
| Pixart Imaging                         | 1         | 0.18%   |
| Nokia Mobile Phones                    | 1         | 0.18%   |
| KYE Systems (Mouse Systems)            | 1         | 0.18%   |
| GEMBIRD                                | 1         | 0.18%   |
| Fly                                    | 1         | 0.18%   |
| ALi                                    | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                              | 27        | 4.96%   |
| Logitech Webcam C270                                            | 14        | 2.57%   |
| Chicony Integrated Camera                                       | 13        | 2.39%   |
| Acer Lenovo Integrated Webcam                                   | 11        | 2.02%   |
| Sunplus HD WebCam                                               | 10        | 1.84%   |
| Realtek Integrated_Webcam_HD                                    | 10        | 1.84%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 10        | 1.84%   |
| IMC Networks Integrated Camera                                  | 10        | 1.84%   |
| Chicony HD WebCam                                               | 10        | 1.84%   |
| Acer Lenovo EasyCamera                                          | 10        | 1.84%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 9         | 1.65%   |
| Chicony Lenovo EasyCamera                                       | 8         | 1.47%   |
| Syntek Integrated Camera                                        | 7         | 1.29%   |
| Syntek EasyCamera                                               | 7         | 1.29%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 7         | 1.29%   |
| Logitech Webcam C310                                            | 6         | 1.1%    |
| Suyin HP TrueVision HD                                          | 5         | 0.92%   |
| Quanta HD Webcam                                                | 5         | 0.92%   |
| Microdia Integrated_Webcam_HD                                   | 5         | 0.92%   |
| Lite-On Integrated Camera                                       | 5         | 0.92%   |
| Lite-On HP HD Camera                                            | 5         | 0.92%   |
| IMC Networks UVC VGA Webcam                                     | 5         | 0.92%   |
| IMC Networks Integrated Webcam                                  | 5         | 0.92%   |
| Z-Star Venus USB2.0 Camera                                      | 4         | 0.74%   |
| Z-Star A4 TECH USB2.0 PC Camera J                               | 4         | 0.74%   |
| Syntek Lenovo EasyCamera                                        | 4         | 0.74%   |
| Suyin HD Video WebCam                                           | 4         | 0.74%   |
| Silicon Motion WebCam SC-03FFL11939N                            | 4         | 0.74%   |
| Silicon Motion WebCam SC-0311139N                               | 4         | 0.74%   |
| Quanta HP HD Camera                                             | 4         | 0.74%   |
| Microdia Camera                                                 | 4         | 0.74%   |
| Chicony HP Truevision HD camera                                 | 4         | 0.74%   |
| Chicony HD WebCam (Acer)                                        | 4         | 0.74%   |
| Chicony EasyCamera                                              | 4         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam    | 4         | 0.74%   |
| Z-Star WebCam SC-03FFL11739P                                    | 3         | 0.55%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 3         | 0.55%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 3         | 0.55%   |
| Suyin 1.3M HD WebCam                                            | 3         | 0.55%   |
| Silicon Motion WebCam SC-13HDL11939N                            | 3         | 0.55%   |
| Realtek USB Camera                                              | 3         | 0.55%   |
| Quanta VGA WebCam                                               | 3         | 0.55%   |
| Quanta HD User Facing                                           | 3         | 0.55%   |
| Logitech Webcam C210                                            | 3         | 0.55%   |
| Lite-On HP HD Webcam                                            | 3         | 0.55%   |
| lihappe8 USB 2.0 Camera                                         | 3         | 0.55%   |
| IMC Networks USB2.0 HD IR UVC WebCam                            | 3         | 0.55%   |
| IMC Networks HD Camera                                          | 3         | 0.55%   |
| DigiTech USB 2.0 PC Camera                                      | 3         | 0.55%   |
| Chicony XiaoMi USB 2.0 Webcam                                   | 3         | 0.55%   |
| Chicony VGA WebCam                                              | 3         | 0.55%   |
| Chicony USB2.0 HD UVC WebCam                                    | 3         | 0.55%   |
| Chicony USB2.0 0.3M UVC WebCam                                  | 3         | 0.55%   |
| Chicony HP Webcam                                               | 3         | 0.55%   |
| Chicony HP TrueVision HD                                        | 3         | 0.55%   |
| Chicony HP HD Camera                                            | 3         | 0.55%   |
| Chicony CNFA078                                                 | 3         | 0.55%   |
| Chicony CNF8243 Webcam                                          | 3         | 0.55%   |
| Chicony 1.3M Webcam                                             | 3         | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 3         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 27.87%  |
| Synaptics                  | 13        | 21.31%  |
| Elan Microelectronics      | 10        | 16.39%  |
| Shenzhen Goodix Technology | 9         | 14.75%  |
| AuthenTec                  | 6         | 9.84%   |
| STMicroelectronics         | 3         | 4.92%   |
| Upek                       | 2         | 3.28%   |
| LighTuning Technology      | 1         | 1.64%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 9         | 14.75%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 6.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 6.56%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 6.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 6.56%   |
| Unknown                                                                    | 4         | 6.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.92%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.92%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 4.92%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.28%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 3.28%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.28%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 3.28%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 3.28%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.64%   |
| Validity Sensors VFS491                                                    | 1         | 1.64%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.64%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.64%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.64%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.64%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.64%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.64%   |
| AuthenTec AES2810                                                          | 1         | 1.64%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.64%   |
| AuthenTec AES1600                                                          | 1         | 1.64%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 6         | 46.15%  |
| Lenovo      | 4         | 30.77%  |
| Broadcom    | 2         | 15.38%  |
| Upek        | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 46.15%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 30.77%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 644       | 76.85%  |
| 1     | 160       | 19.09%  |
| 2     | 28        | 3.34%   |
| 3     | 5         | 0.6%    |
| 4     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 81        | 36.82%  |
| Fingerprint reader       | 59        | 26.82%  |
| Net/wireless             | 17        | 7.73%   |
| Multimedia controller    | 12        | 5.45%   |
| Chipcard                 | 11        | 5%      |
| Communication controller | 10        | 4.55%   |
| Bluetooth                | 10        | 4.55%   |
| Camera                   | 8         | 3.64%   |
| Storage                  | 4         | 1.82%   |
| Sound                    | 3         | 1.36%   |
| Unassigned class         | 1         | 0.45%   |
| Net/ethernet             | 1         | 0.45%   |
| Modem                    | 1         | 0.45%   |
| Flash memory             | 1         | 0.45%   |
| Card reader              | 1         | 0.45%   |

