EndeavourOS - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/EndeavourOS/Desktop/README.md) and [notebooks](/Dist/EndeavourOS/Notebook/README.md).

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

Total: 2015

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | K53BR                       | Notebook    | [bd5284a0e8](https://linux-hardware.org/?probe=bd5284a0e8) | Feb 02, 2024 |
| Schenker      | XMG PRO (Late 2021)         | Notebook    | [502d4a5570](https://linux-hardware.org/?probe=502d4a5570) | Feb 02, 2024 |
| MSI           | Prestige 13 AI Evo A1MG     | Notebook    | [abc18d1a9e](https://linux-hardware.org/?probe=abc18d1a9e) | Feb 02, 2024 |
| Schenker      | XMG PRO (Late 2021)         | Notebook    | [0bd25ae10e](https://linux-hardware.org/?probe=0bd25ae10e) | Feb 02, 2024 |
| Intel         | DH61HO AAG62445-102         | Desktop     | [f6db94d707](https://linux-hardware.org/?probe=f6db94d707) | Feb 01, 2024 |
| Intel         | DH61HO AAG62445-102         | Desktop     | [4752f66f57](https://linux-hardware.org/?probe=4752f66f57) | Feb 01, 2024 |
| ALTYK         | L14F-I5U16-N1               | Notebook    | [7cb618fcca](https://linux-hardware.org/?probe=7cb618fcca) | Feb 01, 2024 |
| ALTYK         | L14F-I5U16-N1               | Notebook    | [81274a6f09](https://linux-hardware.org/?probe=81274a6f09) | Feb 01, 2024 |
| Apple         | Mac-F2218EA9                | All in one  | [87634c39d0](https://linux-hardware.org/?probe=87634c39d0) | Jan 31, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [cbcf46b2fa](https://linux-hardware.org/?probe=cbcf46b2fa) | Jan 31, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [40f306477e](https://linux-hardware.org/?probe=40f306477e) | Jan 31, 2024 |
| Dell          | 0GDJXY A00                  | All in one  | [667766f245](https://linux-hardware.org/?probe=667766f245) | Jan 31, 2024 |
| Biostar       | MCP6P3                      | Desktop     | [cbb6a42f28](https://linux-hardware.org/?probe=cbb6a42f28) | Jan 30, 2024 |
| Biostar       | MCP6P3                      | Desktop     | [55f83d7c17](https://linux-hardware.org/?probe=55f83d7c17) | Jan 30, 2024 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [aecdf1facc](https://linux-hardware.org/?probe=aecdf1facc) | Jan 30, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [033b656553](https://linux-hardware.org/?probe=033b656553) | Jan 30, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [5af523a874](https://linux-hardware.org/?probe=5af523a874) | Jan 29, 2024 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | Notebook    | [c0c78e6476](https://linux-hardware.org/?probe=c0c78e6476) | Jan 29, 2024 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ffc3c06598](https://linux-hardware.org/?probe=ffc3c06598) | Jan 29, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e79ecc48d8](https://linux-hardware.org/?probe=e79ecc48d8) | Jan 29, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [0a4a1cabfc](https://linux-hardware.org/?probe=0a4a1cabfc) | Jan 29, 2024 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [156193b673](https://linux-hardware.org/?probe=156193b673) | Jan 28, 2024 |
| HP            | 84EE 1100                   | All in one  | [eed1f038fe](https://linux-hardware.org/?probe=eed1f038fe) | Jan 28, 2024 |
| EVOO          | EG-LP6                      | Notebook    | [94916a68a1](https://linux-hardware.org/?probe=94916a68a1) | Jan 28, 2024 |
| HP            | 158A                        | Desktop     | [03d463519d](https://linux-hardware.org/?probe=03d463519d) | Jan 27, 2024 |
| System76      | Gazelle                     | Notebook    | [317f744565](https://linux-hardware.org/?probe=317f744565) | Jan 27, 2024 |
| System76      | Gazelle                     | Notebook    | [27bb9a725a](https://linux-hardware.org/?probe=27bb9a725a) | Jan 27, 2024 |
| Lenovo        | ThinkPad T470s 20HGS3AX0... | Notebook    | [c777cd17b5](https://linux-hardware.org/?probe=c777cd17b5) | Jan 26, 2024 |
| Monster       | ABRA A7 V13.3               | Notebook    | [08516ca0c2](https://linux-hardware.org/?probe=08516ca0c2) | Jan 26, 2024 |
| Acer          | Aspire A315-55G             | Notebook    | [c04d6bddfb](https://linux-hardware.org/?probe=c04d6bddfb) | Jan 24, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [e691b608fb](https://linux-hardware.org/?probe=e691b608fb) | Jan 24, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [f37a4265ba](https://linux-hardware.org/?probe=f37a4265ba) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [73c0dd5770](https://linux-hardware.org/?probe=73c0dd5770) | Jan 23, 2024 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [8d46c388c2](https://linux-hardware.org/?probe=8d46c388c2) | Jan 22, 2024 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [03a6ed21ba](https://linux-hardware.org/?probe=03a6ed21ba) | Jan 22, 2024 |
| ASUSTek       | G2S                         | Notebook    | [534f9d0459](https://linux-hardware.org/?probe=534f9d0459) | Jan 22, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [3d7c0f1d64](https://linux-hardware.org/?probe=3d7c0f1d64) | Jan 22, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [0d82cd43ff](https://linux-hardware.org/?probe=0d82cd43ff) | Jan 22, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e47b62e5ed](https://linux-hardware.org/?probe=e47b62e5ed) | Jan 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [dc6c66931e](https://linux-hardware.org/?probe=dc6c66931e) | Jan 22, 2024 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [9bef2c44db](https://linux-hardware.org/?probe=9bef2c44db) | Jan 21, 2024 |
| ASUSTek       | M4N78-AM V2                 | Desktop     | [e8953a5a08](https://linux-hardware.org/?probe=e8953a5a08) | Jan 21, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [833af537d7](https://linux-hardware.org/?probe=833af537d7) | Jan 21, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [1ad08b8198](https://linux-hardware.org/?probe=1ad08b8198) | Jan 21, 2024 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [7f7ae7af9f](https://linux-hardware.org/?probe=7f7ae7af9f) | Jan 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [1427f84afd](https://linux-hardware.org/?probe=1427f84afd) | Jan 18, 2024 |
| Acer          | Nitro AN517-54              | Notebook    | [e736d57544](https://linux-hardware.org/?probe=e736d57544) | Jan 18, 2024 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [817d6ac197](https://linux-hardware.org/?probe=817d6ac197) | Jan 18, 2024 |
| HP            | OMEN by Transcend Gaming... | Notebook    | [6690260fd8](https://linux-hardware.org/?probe=6690260fd8) | Jan 18, 2024 |
| Dell          | Inspiron 3583               | Notebook    | [e70de12740](https://linux-hardware.org/?probe=e70de12740) | Jan 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [89d8674908](https://linux-hardware.org/?probe=89d8674908) | Jan 18, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9b8ccd69ac](https://linux-hardware.org/?probe=9b8ccd69ac) | Jan 17, 2024 |
| Unknown       | X99                         | Desktop     | [7106b28d5f](https://linux-hardware.org/?probe=7106b28d5f) | Jan 16, 2024 |
| Unknown       | X99                         | Desktop     | [c4818c1229](https://linux-hardware.org/?probe=c4818c1229) | Jan 16, 2024 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [b17351aa59](https://linux-hardware.org/?probe=b17351aa59) | Jan 15, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [38fedf44ef](https://linux-hardware.org/?probe=38fedf44ef) | Jan 14, 2024 |
| Sony          | SVE1713X1EB                 | Notebook    | [43af98d3bc](https://linux-hardware.org/?probe=43af98d3bc) | Jan 14, 2024 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [7f3e95be9c](https://linux-hardware.org/?probe=7f3e95be9c) | Jan 14, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [c7e19dad56](https://linux-hardware.org/?probe=c7e19dad56) | Jan 14, 2024 |
| Dell          | Latitude E6420              | Notebook    | [78cffcaf30](https://linux-hardware.org/?probe=78cffcaf30) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [e2058a8b66](https://linux-hardware.org/?probe=e2058a8b66) | Jan 14, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0823cf66ec](https://linux-hardware.org/?probe=0823cf66ec) | Jan 13, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [49e9436217](https://linux-hardware.org/?probe=49e9436217) | Jan 13, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [bcd08b212b](https://linux-hardware.org/?probe=bcd08b212b) | Jan 13, 2024 |
| MSI           | MPG Z390 GAMING EDGE AC     | Notebook    | [4fc5db3901](https://linux-hardware.org/?probe=4fc5db3901) | Jan 13, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [0b0fb2477f](https://linux-hardware.org/?probe=0b0fb2477f) | Jan 13, 2024 |
| HP            | 8715                        | Mini pc     | [a7372e4bbc](https://linux-hardware.org/?probe=a7372e4bbc) | Jan 12, 2024 |
| HP            | 806A                        | Desktop     | [ab302e2dd9](https://linux-hardware.org/?probe=ab302e2dd9) | Jan 11, 2024 |
| HP            | 8715                        | Mini pc     | [912c2d5843](https://linux-hardware.org/?probe=912c2d5843) | Jan 11, 2024 |
| HP            | 8715                        | Mini pc     | [eb1b7c94e2](https://linux-hardware.org/?probe=eb1b7c94e2) | Jan 11, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f5226841b7](https://linux-hardware.org/?probe=f5226841b7) | Jan 11, 2024 |
| Dell          | Latitude E5470              | Notebook    | [a2211d635f](https://linux-hardware.org/?probe=a2211d635f) | Jan 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [14eff97de5](https://linux-hardware.org/?probe=14eff97de5) | Jan 10, 2024 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [0442afbbcd](https://linux-hardware.org/?probe=0442afbbcd) | Jan 10, 2024 |
| Dell          | Latitude 7280               | Notebook    | [de1f6a94e6](https://linux-hardware.org/?probe=de1f6a94e6) | Jan 08, 2024 |
| Dell          | G3 3579                     | Notebook    | [5c48d53216](https://linux-hardware.org/?probe=5c48d53216) | Jan 07, 2024 |
| Dell          | G3 3579                     | Notebook    | [6ee6a6d56a](https://linux-hardware.org/?probe=6ee6a6d56a) | Jan 07, 2024 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [8118029878](https://linux-hardware.org/?probe=8118029878) | Jan 06, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [cd2d137285](https://linux-hardware.org/?probe=cd2d137285) | Jan 05, 2024 |
| HP            | 18E4                        | Desktop     | [e89784f165](https://linux-hardware.org/?probe=e89784f165) | Jan 05, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [8db2d4319e](https://linux-hardware.org/?probe=8db2d4319e) | Jan 05, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a4d59d675c](https://linux-hardware.org/?probe=a4d59d675c) | Jan 04, 2024 |
| Dell          | Inspiron 14 5425            | Notebook    | [a66f85e48e](https://linux-hardware.org/?probe=a66f85e48e) | Jan 03, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | Notebook    | [ccc67d11a0](https://linux-hardware.org/?probe=ccc67d11a0) | Jan 03, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [abd73c6a90](https://linux-hardware.org/?probe=abd73c6a90) | Jan 03, 2024 |
| Sony          | SVE1713X1EB                 | Notebook    | [6c3167a5a7](https://linux-hardware.org/?probe=6c3167a5a7) | Jan 02, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [502ebc99c3](https://linux-hardware.org/?probe=502ebc99c3) | Jan 02, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f7f3e0ddc9](https://linux-hardware.org/?probe=f7f3e0ddc9) | Jan 01, 2024 |
| Dell          | 0YXT71 A02                  | Desktop     | [e08ca6924a](https://linux-hardware.org/?probe=e08ca6924a) | Jan 01, 2024 |
| Sony          | SVE1713X1EB                 | Notebook    | [f9081b680a](https://linux-hardware.org/?probe=f9081b680a) | Jan 01, 2024 |
| ASUSTek       | T102HA                      | Tablet      | [9238ebe65d](https://linux-hardware.org/?probe=9238ebe65d) | Jan 01, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [4fb6fd51a2](https://linux-hardware.org/?probe=4fb6fd51a2) | Jan 01, 2024 |
| Huanan        | X58 V1.0                    | Desktop     | [d13c9b1573](https://linux-hardware.org/?probe=d13c9b1573) | Dec 31, 2023 |
| ASUSTek       | PRIME X570-P                | Notebook    | [12b2d456ed](https://linux-hardware.org/?probe=12b2d456ed) | Dec 30, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [e61eb5428f](https://linux-hardware.org/?probe=e61eb5428f) | Dec 30, 2023 |
| HP            | 8374 1100                   | All in one  | [29b989dbb6](https://linux-hardware.org/?probe=29b989dbb6) | Dec 30, 2023 |
| ASUSTek       | PRIME X570-P                | Notebook    | [596a41673a](https://linux-hardware.org/?probe=596a41673a) | Dec 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2490d5b834](https://linux-hardware.org/?probe=2490d5b834) | Dec 30, 2023 |
| Dell          | Latitude 5580               | Notebook    | [3079edcb81](https://linux-hardware.org/?probe=3079edcb81) | Dec 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [55340871af](https://linux-hardware.org/?probe=55340871af) | Dec 29, 2023 |
| HP            | 212B                        | Desktop     | [6afcd77ad6](https://linux-hardware.org/?probe=6afcd77ad6) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3b6d015d5a](https://linux-hardware.org/?probe=3b6d015d5a) | Dec 29, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0060... | Notebook    | [485c94e992](https://linux-hardware.org/?probe=485c94e992) | Dec 29, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [d9e57db214](https://linux-hardware.org/?probe=d9e57db214) | Dec 28, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [8532e3dcca](https://linux-hardware.org/?probe=8532e3dcca) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [a1652ba789](https://linux-hardware.org/?probe=a1652ba789) | Dec 28, 2023 |
| GPD           | G1619-04                    | Notebook    | [f77175c08b](https://linux-hardware.org/?probe=f77175c08b) | Dec 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f58bf5fe4c](https://linux-hardware.org/?probe=f58bf5fe4c) | Dec 26, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [b08bd5ba2c](https://linux-hardware.org/?probe=b08bd5ba2c) | Dec 25, 2023 |
| Acer          | Swift SF314-51              | Notebook    | [a2f71698e2](https://linux-hardware.org/?probe=a2f71698e2) | Dec 25, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [da58685854](https://linux-hardware.org/?probe=da58685854) | Dec 25, 2023 |
| Gigabyte      | B460M GAMING HD             | Desktop     | [6669971369](https://linux-hardware.org/?probe=6669971369) | Dec 23, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [76b5abd1bd](https://linux-hardware.org/?probe=76b5abd1bd) | Dec 23, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [a7194ce97c](https://linux-hardware.org/?probe=a7194ce97c) | Dec 23, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [5aae7c7b5c](https://linux-hardware.org/?probe=5aae7c7b5c) | Dec 23, 2023 |
| HP            | 8299                        | Desktop     | [7cb3e71107](https://linux-hardware.org/?probe=7cb3e71107) | Dec 23, 2023 |
| Huanan        | X58 V1.0                    | Desktop     | [ac62468ad1](https://linux-hardware.org/?probe=ac62468ad1) | Dec 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [13b303a58b](https://linux-hardware.org/?probe=13b303a58b) | Dec 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [9fea6c876a](https://linux-hardware.org/?probe=9fea6c876a) | Dec 21, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [dd67c36ae3](https://linux-hardware.org/?probe=dd67c36ae3) | Dec 21, 2023 |
| MSI           | B85M-G43                    | Desktop     | [f2b41e4ce3](https://linux-hardware.org/?probe=f2b41e4ce3) | Dec 21, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [dac9572e21](https://linux-hardware.org/?probe=dac9572e21) | Dec 20, 2023 |
| Acer          | Swift SF314-57G             | Notebook    | [b822161722](https://linux-hardware.org/?probe=b822161722) | Dec 19, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [55a83cf2cb](https://linux-hardware.org/?probe=55a83cf2cb) | Dec 19, 2023 |
| TUXEDO        | Aura 14 Gen3                | Notebook    | [bdc38bf0fd](https://linux-hardware.org/?probe=bdc38bf0fd) | Dec 19, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [b6ca701110](https://linux-hardware.org/?probe=b6ca701110) | Dec 18, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [dec9660b8e](https://linux-hardware.org/?probe=dec9660b8e) | Dec 18, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [02ffa90273](https://linux-hardware.org/?probe=02ffa90273) | Dec 18, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [cc0dbece31](https://linux-hardware.org/?probe=cc0dbece31) | Dec 18, 2023 |
| HP            | 86EE                        | All in one  | [b577da610e](https://linux-hardware.org/?probe=b577da610e) | Dec 17, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [185314f313](https://linux-hardware.org/?probe=185314f313) | Dec 17, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [87d3b447bb](https://linux-hardware.org/?probe=87d3b447bb) | Dec 17, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [74584680bb](https://linux-hardware.org/?probe=74584680bb) | Dec 17, 2023 |
| Shenzhen D... | MP80                        | Mini pc     | [adced59500](https://linux-hardware.org/?probe=adced59500) | Dec 17, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [723eb61284](https://linux-hardware.org/?probe=723eb61284) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [2c4dba512d](https://linux-hardware.org/?probe=2c4dba512d) | Dec 16, 2023 |
| Acer          | Nitro AN715-51              | Notebook    | [279ade4fb0](https://linux-hardware.org/?probe=279ade4fb0) | Dec 16, 2023 |
| ASUSTek       | UX490UAR                    | Notebook    | [e8aa69b910](https://linux-hardware.org/?probe=e8aa69b910) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [db30b82451](https://linux-hardware.org/?probe=db30b82451) | Dec 16, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [50ad2630fb](https://linux-hardware.org/?probe=50ad2630fb) | Dec 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7b209666a3](https://linux-hardware.org/?probe=7b209666a3) | Dec 16, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [93fea0297b](https://linux-hardware.org/?probe=93fea0297b) | Dec 15, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [3d4b7d5e8b](https://linux-hardware.org/?probe=3d4b7d5e8b) | Dec 15, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [06a409ecda](https://linux-hardware.org/?probe=06a409ecda) | Dec 15, 2023 |
| Samsung       | 960QFG                      | Convertible | [dddfdbbe1c](https://linux-hardware.org/?probe=dddfdbbe1c) | Dec 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [726676ca8d](https://linux-hardware.org/?probe=726676ca8d) | Dec 13, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [efe4c56706](https://linux-hardware.org/?probe=efe4c56706) | Dec 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8339b9aa1a](https://linux-hardware.org/?probe=8339b9aa1a) | Dec 13, 2023 |
| ASUSTek       | G15DK                       | Desktop     | [b1fb7727ce](https://linux-hardware.org/?probe=b1fb7727ce) | Dec 13, 2023 |
| Universal ... | MONTENERO-C                 | Notebook    | [dcab78af9a](https://linux-hardware.org/?probe=dcab78af9a) | Dec 13, 2023 |
| Dell          | Inspiron 16 Plus 7630       | Notebook    | [25017a9de6](https://linux-hardware.org/?probe=25017a9de6) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [6a742a5308](https://linux-hardware.org/?probe=6a742a5308) | Dec 13, 2023 |
| Lenovo        | ThinkPad W530 24382KU       | Notebook    | [b389060869](https://linux-hardware.org/?probe=b389060869) | Dec 12, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [34c5aec887](https://linux-hardware.org/?probe=34c5aec887) | Dec 12, 2023 |
| HP            | EliteBook 840 14 inch G1... | Notebook    | [17dd4245b8](https://linux-hardware.org/?probe=17dd4245b8) | Dec 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bc96bd94d2](https://linux-hardware.org/?probe=bc96bd94d2) | Dec 11, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [41f57147de](https://linux-hardware.org/?probe=41f57147de) | Dec 10, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [242f306b04](https://linux-hardware.org/?probe=242f306b04) | Dec 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e7b5bdd470](https://linux-hardware.org/?probe=e7b5bdd470) | Dec 09, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [a51f4ce5e5](https://linux-hardware.org/?probe=a51f4ce5e5) | Dec 09, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [5e6fc96a08](https://linux-hardware.org/?probe=5e6fc96a08) | Dec 09, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [3bca387137](https://linux-hardware.org/?probe=3bca387137) | Dec 09, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [dd7e60da66](https://linux-hardware.org/?probe=dd7e60da66) | Dec 09, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [40fae6bc6c](https://linux-hardware.org/?probe=40fae6bc6c) | Dec 08, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [1ce8dbd527](https://linux-hardware.org/?probe=1ce8dbd527) | Dec 08, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [b848110f65](https://linux-hardware.org/?probe=b848110f65) | Dec 08, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [be2c5bcf98](https://linux-hardware.org/?probe=be2c5bcf98) | Dec 07, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [7c4bc43db7](https://linux-hardware.org/?probe=7c4bc43db7) | Dec 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [06fe795e93](https://linux-hardware.org/?probe=06fe795e93) | Dec 05, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [1ac83c7edd](https://linux-hardware.org/?probe=1ac83c7edd) | Dec 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [3c8e9b9cc4](https://linux-hardware.org/?probe=3c8e9b9cc4) | Dec 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d02d11b0df](https://linux-hardware.org/?probe=d02d11b0df) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | Notebook    | [c0681fbe8a](https://linux-hardware.org/?probe=c0681fbe8a) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | Notebook    | [54178ea597](https://linux-hardware.org/?probe=54178ea597) | Dec 03, 2023 |
| Shenzhen D... | MP80                        | Mini pc     | [af649a6096](https://linux-hardware.org/?probe=af649a6096) | Dec 03, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [4b1c01f9b4](https://linux-hardware.org/?probe=4b1c01f9b4) | Dec 02, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [288b6a2f75](https://linux-hardware.org/?probe=288b6a2f75) | Dec 02, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [707fd0c687](https://linux-hardware.org/?probe=707fd0c687) | Dec 02, 2023 |
| HP            | 3397                        | Desktop     | [a858c3e80b](https://linux-hardware.org/?probe=a858c3e80b) | Dec 01, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [5f31cddd2f](https://linux-hardware.org/?probe=5f31cddd2f) | Dec 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [6a029b4d87](https://linux-hardware.org/?probe=6a029b4d87) | Nov 30, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a803eec9f3](https://linux-hardware.org/?probe=a803eec9f3) | Nov 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [62b38954c4](https://linux-hardware.org/?probe=62b38954c4) | Nov 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ad9b9e5fd1](https://linux-hardware.org/?probe=ad9b9e5fd1) | Nov 30, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [aca3298198](https://linux-hardware.org/?probe=aca3298198) | Nov 28, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [0dbf67ab6f](https://linux-hardware.org/?probe=0dbf67ab6f) | Nov 28, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [d5d85d7080](https://linux-hardware.org/?probe=d5d85d7080) | Nov 27, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [36fb8bfcab](https://linux-hardware.org/?probe=36fb8bfcab) | Nov 27, 2023 |
| HP            | EliteBook 745 G4            | Notebook    | [c3c18efc38](https://linux-hardware.org/?probe=c3c18efc38) | Nov 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [61a33862ad](https://linux-hardware.org/?probe=61a33862ad) | Nov 26, 2023 |
| HP            | EliteBook 745 G4            | Notebook    | [33d8baae78](https://linux-hardware.org/?probe=33d8baae78) | Nov 26, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [a80073b9be](https://linux-hardware.org/?probe=a80073b9be) | Nov 25, 2023 |
| HP            | 3397                        | Desktop     | [ea69fd3531](https://linux-hardware.org/?probe=ea69fd3531) | Nov 25, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | Notebook    | [06170c8841](https://linux-hardware.org/?probe=06170c8841) | Nov 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [5bbefae656](https://linux-hardware.org/?probe=5bbefae656) | Nov 25, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [261d00b9c1](https://linux-hardware.org/?probe=261d00b9c1) | Nov 25, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [fe4e9cf955](https://linux-hardware.org/?probe=fe4e9cf955) | Nov 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [ac2895b3d7](https://linux-hardware.org/?probe=ac2895b3d7) | Nov 24, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | Notebook    | [a58a5557e6](https://linux-hardware.org/?probe=a58a5557e6) | Nov 24, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [7881b2e888](https://linux-hardware.org/?probe=7881b2e888) | Nov 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [bfb322c3dc](https://linux-hardware.org/?probe=bfb322c3dc) | Nov 24, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | Notebook    | [7cd9c24a07](https://linux-hardware.org/?probe=7cd9c24a07) | Nov 23, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [eaa5c5a6ba](https://linux-hardware.org/?probe=eaa5c5a6ba) | Nov 23, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [9d7f74829e](https://linux-hardware.org/?probe=9d7f74829e) | Nov 23, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [298883c961](https://linux-hardware.org/?probe=298883c961) | Nov 23, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [6bc9169e34](https://linux-hardware.org/?probe=6bc9169e34) | Nov 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [f41a7c6412](https://linux-hardware.org/?probe=f41a7c6412) | Nov 22, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [ce955eaeb4](https://linux-hardware.org/?probe=ce955eaeb4) | Nov 22, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [194465c3c5](https://linux-hardware.org/?probe=194465c3c5) | Nov 22, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [79c38d7dd7](https://linux-hardware.org/?probe=79c38d7dd7) | Nov 22, 2023 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [d1fbe0a436](https://linux-hardware.org/?probe=d1fbe0a436) | Nov 21, 2023 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [6a6293fda8](https://linux-hardware.org/?probe=6a6293fda8) | Nov 21, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [a6efd4193b](https://linux-hardware.org/?probe=a6efd4193b) | Nov 21, 2023 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [412a97e883](https://linux-hardware.org/?probe=412a97e883) | Nov 21, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [86845a8402](https://linux-hardware.org/?probe=86845a8402) | Nov 20, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [a5406ad359](https://linux-hardware.org/?probe=a5406ad359) | Nov 20, 2023 |
| Fujitsu       | FMVC06001                   | Notebook    | [122e4a9608](https://linux-hardware.org/?probe=122e4a9608) | Nov 20, 2023 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | Notebook    | [b7e16888b9](https://linux-hardware.org/?probe=b7e16888b9) | Nov 20, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [9274d4e825](https://linux-hardware.org/?probe=9274d4e825) | Nov 20, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [03c5ac12be](https://linux-hardware.org/?probe=03c5ac12be) | Nov 20, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [2482b30a58](https://linux-hardware.org/?probe=2482b30a58) | Nov 19, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [c3769c8a57](https://linux-hardware.org/?probe=c3769c8a57) | Nov 18, 2023 |
| TUXEDO        | Gemini Gen2                 | Notebook    | [43d1c51e23](https://linux-hardware.org/?probe=43d1c51e23) | Nov 17, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [58e714af7e](https://linux-hardware.org/?probe=58e714af7e) | Nov 16, 2023 |
| MSI           | Z87-G43 GAMING              | Desktop     | [71786a484b](https://linux-hardware.org/?probe=71786a484b) | Nov 16, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [04d65c8c40](https://linux-hardware.org/?probe=04d65c8c40) | Nov 15, 2023 |
| MSI           | Z87-G43 GAMING              | Desktop     | [1cf432335c](https://linux-hardware.org/?probe=1cf432335c) | Nov 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [59f539dd3b](https://linux-hardware.org/?probe=59f539dd3b) | Nov 14, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [3be8e07c6c](https://linux-hardware.org/?probe=3be8e07c6c) | Nov 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [018253183e](https://linux-hardware.org/?probe=018253183e) | Nov 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ed85cdf855](https://linux-hardware.org/?probe=ed85cdf855) | Nov 13, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [0029d3638f](https://linux-hardware.org/?probe=0029d3638f) | Nov 12, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [03a619e930](https://linux-hardware.org/?probe=03a619e930) | Nov 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4a09ae9d2](https://linux-hardware.org/?probe=e4a09ae9d2) | Nov 10, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [1aeeebf4b2](https://linux-hardware.org/?probe=1aeeebf4b2) | Nov 10, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [62ccd07f15](https://linux-hardware.org/?probe=62ccd07f15) | Nov 10, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [26f1a89e53](https://linux-hardware.org/?probe=26f1a89e53) | Nov 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [b299fd1fe9](https://linux-hardware.org/?probe=b299fd1fe9) | Nov 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [2adf99d3df](https://linux-hardware.org/?probe=2adf99d3df) | Nov 09, 2023 |
| Lenovo        | ThinkPad T430s 23553J2      | Notebook    | [d035513169](https://linux-hardware.org/?probe=d035513169) | Nov 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [b8a00231d6](https://linux-hardware.org/?probe=b8a00231d6) | Nov 08, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [16cf6c0ede](https://linux-hardware.org/?probe=16cf6c0ede) | Nov 08, 2023 |
| Medion        | P6681 MD60814               | Notebook    | [a17f8ffc19](https://linux-hardware.org/?probe=a17f8ffc19) | Nov 07, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [6f5721955b](https://linux-hardware.org/?probe=6f5721955b) | Nov 07, 2023 |
| Dell          | G7 7700                     | Notebook    | [0fc7811fdd](https://linux-hardware.org/?probe=0fc7811fdd) | Nov 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [744716992d](https://linux-hardware.org/?probe=744716992d) | Nov 06, 2023 |
| Lenovo        | 3734 SDK0R32862 WIN 3258... | All in one  | [b153378dab](https://linux-hardware.org/?probe=b153378dab) | Nov 06, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [985ed440bf](https://linux-hardware.org/?probe=985ed440bf) | Nov 06, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [1cf99ffe12](https://linux-hardware.org/?probe=1cf99ffe12) | Nov 05, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [cf8911c5e0](https://linux-hardware.org/?probe=cf8911c5e0) | Nov 05, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [451abee058](https://linux-hardware.org/?probe=451abee058) | Nov 05, 2023 |
| ASUSTek       | UX370UAR                    | Convertible | [754b927267](https://linux-hardware.org/?probe=754b927267) | Nov 05, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [9f19a2ba3a](https://linux-hardware.org/?probe=9f19a2ba3a) | Nov 04, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [d3a8398c99](https://linux-hardware.org/?probe=d3a8398c99) | Nov 04, 2023 |
| Acer          | Aspire R5-571TG             | Convertible | [f0e8c6a66f](https://linux-hardware.org/?probe=f0e8c6a66f) | Nov 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d95fab9dc1](https://linux-hardware.org/?probe=d95fab9dc1) | Nov 04, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [b213aefe09](https://linux-hardware.org/?probe=b213aefe09) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [db71fb65bf](https://linux-hardware.org/?probe=db71fb65bf) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b592d36d74](https://linux-hardware.org/?probe=b592d36d74) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [da695062ba](https://linux-hardware.org/?probe=da695062ba) | Nov 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a08b1cfa29](https://linux-hardware.org/?probe=a08b1cfa29) | Nov 03, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [de293a4621](https://linux-hardware.org/?probe=de293a4621) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b0c996ac38](https://linux-hardware.org/?probe=b0c996ac38) | Nov 02, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [47abbeb9c1](https://linux-hardware.org/?probe=47abbeb9c1) | Nov 01, 2023 |
| MSI           | GV62 8RD                    | Notebook    | [d85cb220a0](https://linux-hardware.org/?probe=d85cb220a0) | Nov 01, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [5116fa401d](https://linux-hardware.org/?probe=5116fa401d) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [865e6764f2](https://linux-hardware.org/?probe=865e6764f2) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [bf87ba6b55](https://linux-hardware.org/?probe=bf87ba6b55) | Nov 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [c950f24711](https://linux-hardware.org/?probe=c950f24711) | Nov 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [6af2aaed4e](https://linux-hardware.org/?probe=6af2aaed4e) | Nov 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [0dc16901b7](https://linux-hardware.org/?probe=0dc16901b7) | Nov 01, 2023 |
| Microsoft     | Surface Laptop Go 3         | Tablet      | [efa4316df1](https://linux-hardware.org/?probe=efa4316df1) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | Notebook    | [0b21a4419d](https://linux-hardware.org/?probe=0b21a4419d) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | Notebook    | [757199e3cf](https://linux-hardware.org/?probe=757199e3cf) | Nov 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6c1c4ea069](https://linux-hardware.org/?probe=6c1c4ea069) | Oct 31, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUA... | Notebook    | [701a08bdb6](https://linux-hardware.org/?probe=701a08bdb6) | Oct 31, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [b4e85014cc](https://linux-hardware.org/?probe=b4e85014cc) | Oct 31, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [62adc05f6a](https://linux-hardware.org/?probe=62adc05f6a) | Oct 31, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [55f41faf27](https://linux-hardware.org/?probe=55f41faf27) | Oct 31, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [64292785b9](https://linux-hardware.org/?probe=64292785b9) | Oct 31, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [413254deb3](https://linux-hardware.org/?probe=413254deb3) | Oct 30, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [0b62ec2df6](https://linux-hardware.org/?probe=0b62ec2df6) | Oct 30, 2023 |
| MSI           | Modern 15 A11M              | Notebook    | [43161bd5f4](https://linux-hardware.org/?probe=43161bd5f4) | Oct 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [508c244637](https://linux-hardware.org/?probe=508c244637) | Oct 30, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [f19f70993f](https://linux-hardware.org/?probe=f19f70993f) | Oct 30, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3f0259e17b](https://linux-hardware.org/?probe=3f0259e17b) | Oct 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | Notebook    | [448c3ca446](https://linux-hardware.org/?probe=448c3ca446) | Oct 30, 2023 |
| Acer          | Aspire R5-571TG             | Convertible | [024085ccb0](https://linux-hardware.org/?probe=024085ccb0) | Oct 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [c1d00eb91f](https://linux-hardware.org/?probe=c1d00eb91f) | Oct 29, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [c9a6bd4217](https://linux-hardware.org/?probe=c9a6bd4217) | Oct 29, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [aaf303e411](https://linux-hardware.org/?probe=aaf303e411) | Oct 28, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [0e1711e674](https://linux-hardware.org/?probe=0e1711e674) | Oct 28, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | Notebook    | [e0dc47cf61](https://linux-hardware.org/?probe=e0dc47cf61) | Oct 28, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [96710ad70e](https://linux-hardware.org/?probe=96710ad70e) | Oct 28, 2023 |
| Gigabyte      | Z590 Gaming X               | Desktop     | [86bb741092](https://linux-hardware.org/?probe=86bb741092) | Oct 27, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [1f5d6e4141](https://linux-hardware.org/?probe=1f5d6e4141) | Oct 27, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | Desktop     | [db2952a9d8](https://linux-hardware.org/?probe=db2952a9d8) | Oct 27, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [21bcc65553](https://linux-hardware.org/?probe=21bcc65553) | Oct 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [5aef96bd0e](https://linux-hardware.org/?probe=5aef96bd0e) | Oct 25, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [6cd6569138](https://linux-hardware.org/?probe=6cd6569138) | Oct 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [95b5ac0a0e](https://linux-hardware.org/?probe=95b5ac0a0e) | Oct 24, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [9c37fcb5c9](https://linux-hardware.org/?probe=9c37fcb5c9) | Oct 24, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [8a67a1a41a](https://linux-hardware.org/?probe=8a67a1a41a) | Oct 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [e2e4b18ec2](https://linux-hardware.org/?probe=e2e4b18ec2) | Oct 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [9649ffc088](https://linux-hardware.org/?probe=9649ffc088) | Oct 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [79ef1e4f2b](https://linux-hardware.org/?probe=79ef1e4f2b) | Oct 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a5c33d9a5a](https://linux-hardware.org/?probe=a5c33d9a5a) | Oct 22, 2023 |
| ASRock        | B450M/ac R2.0               | Desktop     | [c1313fc22e](https://linux-hardware.org/?probe=c1313fc22e) | Oct 22, 2023 |
| HP            | Snappy                      | Notebook    | [2d0c13b032](https://linux-hardware.org/?probe=2d0c13b032) | Oct 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [f103762ce5](https://linux-hardware.org/?probe=f103762ce5) | Oct 21, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [147d6ad175](https://linux-hardware.org/?probe=147d6ad175) | Oct 21, 2023 |
| Gigabyte      | B760 GAMING X AX DDR4       | Desktop     | [eb5de485aa](https://linux-hardware.org/?probe=eb5de485aa) | Oct 21, 2023 |
| HP            | Snappy                      | Notebook    | [b8dc14dc5d](https://linux-hardware.org/?probe=b8dc14dc5d) | Oct 21, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [cd302f735e](https://linux-hardware.org/?probe=cd302f735e) | Oct 21, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [e5362858a0](https://linux-hardware.org/?probe=e5362858a0) | Oct 20, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [01544384cc](https://linux-hardware.org/?probe=01544384cc) | Oct 20, 2023 |
| Acer          | Aspire R5-571TG             | Convertible | [7e85436ec2](https://linux-hardware.org/?probe=7e85436ec2) | Oct 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [7deca235e3](https://linux-hardware.org/?probe=7deca235e3) | Oct 20, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [c01a27db62](https://linux-hardware.org/?probe=c01a27db62) | Oct 20, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [8fbbe4eec8](https://linux-hardware.org/?probe=8fbbe4eec8) | Oct 20, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [12b93b3f48](https://linux-hardware.org/?probe=12b93b3f48) | Oct 20, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [240879310d](https://linux-hardware.org/?probe=240879310d) | Oct 19, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [41666281fc](https://linux-hardware.org/?probe=41666281fc) | Oct 19, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ec015a6c9e](https://linux-hardware.org/?probe=ec015a6c9e) | Oct 19, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [e350eec913](https://linux-hardware.org/?probe=e350eec913) | Oct 19, 2023 |
| LTD Delovo... | EVE 1494E ES1280EW          | Tablet      | [97c02ed2e9](https://linux-hardware.org/?probe=97c02ed2e9) | Oct 17, 2023 |
| Positivo      | POS-PIG43BC SIM             | Desktop     | [ded7e15a49](https://linux-hardware.org/?probe=ded7e15a49) | Oct 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [172cfdcd26](https://linux-hardware.org/?probe=172cfdcd26) | Oct 16, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [5ee2d06317](https://linux-hardware.org/?probe=5ee2d06317) | Oct 15, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [0d80ec0e27](https://linux-hardware.org/?probe=0d80ec0e27) | Oct 15, 2023 |
| Toshiba       | Satellite C855-1KF          | Notebook    | [1dbc7c0de3](https://linux-hardware.org/?probe=1dbc7c0de3) | Oct 15, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [740122e9fa](https://linux-hardware.org/?probe=740122e9fa) | Oct 15, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bc47dea2fe](https://linux-hardware.org/?probe=bc47dea2fe) | Oct 14, 2023 |
| Dell          | Inspiron 16 7630 2-in-1     | Convertible | [1156f51af6](https://linux-hardware.org/?probe=1156f51af6) | Oct 12, 2023 |
| MSI           | GS63 Stealth 8RE            | Notebook    | [a83fe5a954](https://linux-hardware.org/?probe=a83fe5a954) | Oct 11, 2023 |
| MSI           | GS63 Stealth 8RE            | Notebook    | [5f9d5460fb](https://linux-hardware.org/?probe=5f9d5460fb) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [d44d655589](https://linux-hardware.org/?probe=d44d655589) | Oct 11, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [3df74e5b96](https://linux-hardware.org/?probe=3df74e5b96) | Oct 11, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [04fbcfc11b](https://linux-hardware.org/?probe=04fbcfc11b) | Oct 10, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4071bd53ce](https://linux-hardware.org/?probe=4071bd53ce) | Oct 10, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [e1dc170ad7](https://linux-hardware.org/?probe=e1dc170ad7) | Oct 09, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [5089a21326](https://linux-hardware.org/?probe=5089a21326) | Oct 07, 2023 |
| System76      | Gazelle                     | Notebook    | [1a40053c3e](https://linux-hardware.org/?probe=1a40053c3e) | Oct 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2d73d7e286](https://linux-hardware.org/?probe=2d73d7e286) | Oct 06, 2023 |
| Acer          | Aspire 7730G                | Notebook    | [d48f861a2e](https://linux-hardware.org/?probe=d48f861a2e) | Oct 05, 2023 |
| HP            | ZBook 14u G4                | Notebook    | [1d14da7190](https://linux-hardware.org/?probe=1d14da7190) | Oct 05, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | Notebook    | [cc02a5e08e](https://linux-hardware.org/?probe=cc02a5e08e) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8e0792976d](https://linux-hardware.org/?probe=8e0792976d) | Oct 03, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ca5985274a](https://linux-hardware.org/?probe=ca5985274a) | Oct 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [b992cbe7ae](https://linux-hardware.org/?probe=b992cbe7ae) | Oct 02, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [b5fcc0da7b](https://linux-hardware.org/?probe=b5fcc0da7b) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b8068a8e68](https://linux-hardware.org/?probe=b8068a8e68) | Oct 02, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cacc534be7](https://linux-hardware.org/?probe=cacc534be7) | Oct 02, 2023 |
| Razer         | Blade 15 Base Model (Lat... | Notebook    | [4e1788f184](https://linux-hardware.org/?probe=4e1788f184) | Oct 02, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [35830807d4](https://linux-hardware.org/?probe=35830807d4) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [1c4b1aa68d](https://linux-hardware.org/?probe=1c4b1aa68d) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [988f015a89](https://linux-hardware.org/?probe=988f015a89) | Sep 30, 2023 |
| Lenovo        | ThinkPad E495 20NES07V00    | Notebook    | [935dc10f6b](https://linux-hardware.org/?probe=935dc10f6b) | Sep 30, 2023 |
| Dell          | Latitude 5410               | Notebook    | [d13c5769a3](https://linux-hardware.org/?probe=d13c5769a3) | Sep 30, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [0e67f3a0f3](https://linux-hardware.org/?probe=0e67f3a0f3) | Sep 29, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [670f7351b5](https://linux-hardware.org/?probe=670f7351b5) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1543bac588](https://linux-hardware.org/?probe=1543bac588) | Sep 27, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ed68f904fe](https://linux-hardware.org/?probe=ed68f904fe) | Sep 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e24beff974](https://linux-hardware.org/?probe=e24beff974) | Sep 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [b8b2b3ff7e](https://linux-hardware.org/?probe=b8b2b3ff7e) | Sep 26, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6677b81417](https://linux-hardware.org/?probe=6677b81417) | Sep 26, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [0dca41ca4e](https://linux-hardware.org/?probe=0dca41ca4e) | Sep 25, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [94ce4b6306](https://linux-hardware.org/?probe=94ce4b6306) | Sep 25, 2023 |
| MSI           | GS63VR 6RF                  | Notebook    | [03a9aed3c9](https://linux-hardware.org/?probe=03a9aed3c9) | Sep 25, 2023 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [7ea3152d65](https://linux-hardware.org/?probe=7ea3152d65) | Sep 25, 2023 |
| Dell          | G5 5505                     | Notebook    | [e9c461d44d](https://linux-hardware.org/?probe=e9c461d44d) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [cada97becf](https://linux-hardware.org/?probe=cada97becf) | Sep 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2b371179db](https://linux-hardware.org/?probe=2b371179db) | Sep 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [2bb252778b](https://linux-hardware.org/?probe=2bb252778b) | Sep 25, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [f6369d0be5](https://linux-hardware.org/?probe=f6369d0be5) | Sep 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [2d1e14cb66](https://linux-hardware.org/?probe=2d1e14cb66) | Sep 23, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [0f276cde5a](https://linux-hardware.org/?probe=0f276cde5a) | Sep 23, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [c6211ac3aa](https://linux-hardware.org/?probe=c6211ac3aa) | Sep 22, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [3a965cb7e3](https://linux-hardware.org/?probe=3a965cb7e3) | Sep 22, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [90c9ffe2e0](https://linux-hardware.org/?probe=90c9ffe2e0) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [45f00aaf92](https://linux-hardware.org/?probe=45f00aaf92) | Sep 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [7f327aca42](https://linux-hardware.org/?probe=7f327aca42) | Sep 21, 2023 |
| HP            | 212B                        | Desktop     | [f961d48c51](https://linux-hardware.org/?probe=f961d48c51) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [9fdc142c76](https://linux-hardware.org/?probe=9fdc142c76) | Sep 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [d940deb0df](https://linux-hardware.org/?probe=d940deb0df) | Sep 19, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [2b913a2e83](https://linux-hardware.org/?probe=2b913a2e83) | Sep 19, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [5cab8957eb](https://linux-hardware.org/?probe=5cab8957eb) | Sep 18, 2023 |
| HP            | Dragonfly Pro               | Notebook    | [0c5d439504](https://linux-hardware.org/?probe=0c5d439504) | Sep 18, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [a93d60a237](https://linux-hardware.org/?probe=a93d60a237) | Sep 17, 2023 |
| ASUSTek       | PRIME H770-PLUS             | Desktop     | [c58fea9225](https://linux-hardware.org/?probe=c58fea9225) | Sep 16, 2023 |
| Dell          | Latitude E5470              | Notebook    | [0602c2deb2](https://linux-hardware.org/?probe=0602c2deb2) | Sep 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aea37f693f](https://linux-hardware.org/?probe=aea37f693f) | Sep 15, 2023 |
| ASRock        | B450M/ac R2.0               | Desktop     | [804b890928](https://linux-hardware.org/?probe=804b890928) | Sep 15, 2023 |
| MSI           | MEG Z790 GODLIKE            | Desktop     | [ef63882e50](https://linux-hardware.org/?probe=ef63882e50) | Sep 15, 2023 |
| MSI           | MEG Z790 GODLIKE            | Desktop     | [688462f949](https://linux-hardware.org/?probe=688462f949) | Sep 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [c954042e8b](https://linux-hardware.org/?probe=c954042e8b) | Sep 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [452d16c55c](https://linux-hardware.org/?probe=452d16c55c) | Sep 13, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2260bcd7af](https://linux-hardware.org/?probe=2260bcd7af) | Sep 12, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2284d8a2dd](https://linux-hardware.org/?probe=2284d8a2dd) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [dca28b0d09](https://linux-hardware.org/?probe=dca28b0d09) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [6c6c4a19ec](https://linux-hardware.org/?probe=6c6c4a19ec) | Sep 12, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [e72c31a6fc](https://linux-hardware.org/?probe=e72c31a6fc) | Sep 11, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [4628c4e630](https://linux-hardware.org/?probe=4628c4e630) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6d8ac2101a](https://linux-hardware.org/?probe=6d8ac2101a) | Sep 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [16b6bd1d3d](https://linux-hardware.org/?probe=16b6bd1d3d) | Sep 09, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [bdd270eddd](https://linux-hardware.org/?probe=bdd270eddd) | Sep 09, 2023 |
| ASUSTek       | ROG Maximus XI EXTREME      | Desktop     | [37efc0526e](https://linux-hardware.org/?probe=37efc0526e) | Sep 09, 2023 |
| ASUSTek       | ROG Maximus XI EXTREME      | Desktop     | [035446631a](https://linux-hardware.org/?probe=035446631a) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [5b0ce3438c](https://linux-hardware.org/?probe=5b0ce3438c) | Sep 08, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [178d6df21a](https://linux-hardware.org/?probe=178d6df21a) | Sep 08, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [6870581b7c](https://linux-hardware.org/?probe=6870581b7c) | Sep 08, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [872f12f24c](https://linux-hardware.org/?probe=872f12f24c) | Sep 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [d5430e9279](https://linux-hardware.org/?probe=d5430e9279) | Sep 08, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [5b22cd283b](https://linux-hardware.org/?probe=5b22cd283b) | Sep 08, 2023 |
| ASRock        | B450M/ac R2.0               | Desktop     | [82266958be](https://linux-hardware.org/?probe=82266958be) | Sep 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [003d136012](https://linux-hardware.org/?probe=003d136012) | Sep 07, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [79ddc77f63](https://linux-hardware.org/?probe=79ddc77f63) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [a5506bdc30](https://linux-hardware.org/?probe=a5506bdc30) | Sep 07, 2023 |
| Acer          | Aspire GX-785               | Desktop     | [e33b7b35bf](https://linux-hardware.org/?probe=e33b7b35bf) | Sep 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fafd1b4cf2](https://linux-hardware.org/?probe=fafd1b4cf2) | Sep 06, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f7c65dc902](https://linux-hardware.org/?probe=f7c65dc902) | Sep 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [38aad324f2](https://linux-hardware.org/?probe=38aad324f2) | Sep 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [cd1be324d4](https://linux-hardware.org/?probe=cd1be324d4) | Sep 05, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [82fd19c99e](https://linux-hardware.org/?probe=82fd19c99e) | Sep 05, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [08dd85e58d](https://linux-hardware.org/?probe=08dd85e58d) | Sep 05, 2023 |
| MSI           | GS75 Stealth 8SG            | Notebook    | [fc603fc196](https://linux-hardware.org/?probe=fc603fc196) | Sep 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | Notebook    | [13b7789482](https://linux-hardware.org/?probe=13b7789482) | Sep 04, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [8a4af58adc](https://linux-hardware.org/?probe=8a4af58adc) | Sep 04, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [3ee4e0f848](https://linux-hardware.org/?probe=3ee4e0f848) | Sep 02, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [f23cf01c1c](https://linux-hardware.org/?probe=f23cf01c1c) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [db2e607ae6](https://linux-hardware.org/?probe=db2e607ae6) | Sep 02, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [d8e4c2da1e](https://linux-hardware.org/?probe=d8e4c2da1e) | Sep 01, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [b652970974](https://linux-hardware.org/?probe=b652970974) | Sep 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [4725c2be8e](https://linux-hardware.org/?probe=4725c2be8e) | Sep 01, 2023 |
| HP            | Pavilion Aero Laptop 13z... | Notebook    | [afa88a8a6a](https://linux-hardware.org/?probe=afa88a8a6a) | Sep 01, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [ce1e538f59](https://linux-hardware.org/?probe=ce1e538f59) | Sep 01, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [a6619c179c](https://linux-hardware.org/?probe=a6619c179c) | Aug 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [578f5e581e](https://linux-hardware.org/?probe=578f5e581e) | Aug 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [0bf7d37cc9](https://linux-hardware.org/?probe=0bf7d37cc9) | Aug 30, 2023 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [7cf4986142](https://linux-hardware.org/?probe=7cf4986142) | Aug 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [320e8d218f](https://linux-hardware.org/?probe=320e8d218f) | Aug 28, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [d238cd036a](https://linux-hardware.org/?probe=d238cd036a) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [01a0f80107](https://linux-hardware.org/?probe=01a0f80107) | Aug 27, 2023 |
| ASUSTek       | X550VXK                     | Notebook    | [897e4f89ec](https://linux-hardware.org/?probe=897e4f89ec) | Aug 27, 2023 |
| Samsung       | 930QCG                      | Convertible | [3fb44943e6](https://linux-hardware.org/?probe=3fb44943e6) | Aug 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [95d23ba555](https://linux-hardware.org/?probe=95d23ba555) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [657c08f61f](https://linux-hardware.org/?probe=657c08f61f) | Aug 27, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ab8f75bb84](https://linux-hardware.org/?probe=ab8f75bb84) | Aug 27, 2023 |
| Unknown       | V00                         | Mini pc     | [81085cf18b](https://linux-hardware.org/?probe=81085cf18b) | Aug 26, 2023 |
| Google        | Madoo                       | Notebook    | [6644bab363](https://linux-hardware.org/?probe=6644bab363) | Aug 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [2bbc495ee5](https://linux-hardware.org/?probe=2bbc495ee5) | Aug 25, 2023 |
| HP            | EliteBook 645 14 inch G9... | Notebook    | [d02a7851a6](https://linux-hardware.org/?probe=d02a7851a6) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [3eea0be3b4](https://linux-hardware.org/?probe=3eea0be3b4) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [53ba2f91cd](https://linux-hardware.org/?probe=53ba2f91cd) | Aug 24, 2023 |
| HP            | 1589                        | Desktop     | [982f4f1442](https://linux-hardware.org/?probe=982f4f1442) | Aug 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [637ccef7bd](https://linux-hardware.org/?probe=637ccef7bd) | Aug 24, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [34a96cbdc8](https://linux-hardware.org/?probe=34a96cbdc8) | Aug 24, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [816f3ce721](https://linux-hardware.org/?probe=816f3ce721) | Aug 24, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [ef3454780b](https://linux-hardware.org/?probe=ef3454780b) | Aug 23, 2023 |
| HP            | 250 G4                      | Notebook    | [1eb6dc4c12](https://linux-hardware.org/?probe=1eb6dc4c12) | Aug 23, 2023 |
| HP            | 18E4                        | Desktop     | [0235c76e04](https://linux-hardware.org/?probe=0235c76e04) | Aug 23, 2023 |
| Lenovo        | ThinkPad E495 20NES0KM00    | Notebook    | [783db5b84d](https://linux-hardware.org/?probe=783db5b84d) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [26d59e1060](https://linux-hardware.org/?probe=26d59e1060) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [d10b0c4ca0](https://linux-hardware.org/?probe=d10b0c4ca0) | Aug 23, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [c6a3274c8f](https://linux-hardware.org/?probe=c6a3274c8f) | Aug 21, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [165cab2421](https://linux-hardware.org/?probe=165cab2421) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [6112b46746](https://linux-hardware.org/?probe=6112b46746) | Aug 21, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6cee16ebd6](https://linux-hardware.org/?probe=6cee16ebd6) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [b883100fd3](https://linux-hardware.org/?probe=b883100fd3) | Aug 21, 2023 |
| MSI           | Katana 15 B13VGK            | Notebook    | [c21afd5e9f](https://linux-hardware.org/?probe=c21afd5e9f) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b6aa75cb80](https://linux-hardware.org/?probe=b6aa75cb80) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [71853f1c36](https://linux-hardware.org/?probe=71853f1c36) | Aug 20, 2023 |
| Packard Be... | EasyNote TJ66               | Notebook    | [7e5e1655a6](https://linux-hardware.org/?probe=7e5e1655a6) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [d6df464cc7](https://linux-hardware.org/?probe=d6df464cc7) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [471f5f6132](https://linux-hardware.org/?probe=471f5f6132) | Aug 20, 2023 |
| Lenovo        | IdeaPad 110-15AST 80TR      | Notebook    | [60385dd9f0](https://linux-hardware.org/?probe=60385dd9f0) | Aug 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e797880ede](https://linux-hardware.org/?probe=e797880ede) | Aug 19, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8bb2d02e4d](https://linux-hardware.org/?probe=8bb2d02e4d) | Aug 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [867105e269](https://linux-hardware.org/?probe=867105e269) | Aug 18, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [f99d3dca93](https://linux-hardware.org/?probe=f99d3dca93) | Aug 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [5ed6b3612a](https://linux-hardware.org/?probe=5ed6b3612a) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [6e6a7171bf](https://linux-hardware.org/?probe=6e6a7171bf) | Aug 16, 2023 |
| HP            | 18E4                        | Desktop     | [4fd89c22ae](https://linux-hardware.org/?probe=4fd89c22ae) | Aug 14, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [1632c89b98](https://linux-hardware.org/?probe=1632c89b98) | Aug 13, 2023 |
| HP            | 8055                        | Desktop     | [a4c4208546](https://linux-hardware.org/?probe=a4c4208546) | Aug 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [246c60a344](https://linux-hardware.org/?probe=246c60a344) | Aug 13, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [6cbef2a38d](https://linux-hardware.org/?probe=6cbef2a38d) | Aug 13, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d760e3f4c4](https://linux-hardware.org/?probe=d760e3f4c4) | Aug 13, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [17dacd99a6](https://linux-hardware.org/?probe=17dacd99a6) | Aug 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [083e25221d](https://linux-hardware.org/?probe=083e25221d) | Aug 10, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f6040edeb0](https://linux-hardware.org/?probe=f6040edeb0) | Aug 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5a2d81b438](https://linux-hardware.org/?probe=5a2d81b438) | Aug 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3b02fcaeb7](https://linux-hardware.org/?probe=3b02fcaeb7) | Aug 09, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [bdc11616d7](https://linux-hardware.org/?probe=bdc11616d7) | Aug 08, 2023 |
| ASUSTek       | ROG Flow X16 GV601VI_GV6... | Convertible | [99ffb28c11](https://linux-hardware.org/?probe=99ffb28c11) | Aug 08, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [bc55c09547](https://linux-hardware.org/?probe=bc55c09547) | Aug 06, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [0e79a19ed6](https://linux-hardware.org/?probe=0e79a19ed6) | Aug 06, 2023 |
| Dell          | Latitude E5570              | Notebook    | [cbcea81a37](https://linux-hardware.org/?probe=cbcea81a37) | Aug 06, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [34e27f60e0](https://linux-hardware.org/?probe=34e27f60e0) | Aug 05, 2023 |
| Toshiba       | PORTEGE R700                | Notebook    | [f0df061bb2](https://linux-hardware.org/?probe=f0df061bb2) | Aug 04, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [5f63621af2](https://linux-hardware.org/?probe=5f63621af2) | Aug 04, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [4c677637c2](https://linux-hardware.org/?probe=4c677637c2) | Aug 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [731ae84313](https://linux-hardware.org/?probe=731ae84313) | Aug 04, 2023 |
| Acer          | TravelMate P614-51-G2       | Notebook    | [33dd52a94f](https://linux-hardware.org/?probe=33dd52a94f) | Aug 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [7372322587](https://linux-hardware.org/?probe=7372322587) | Aug 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [efa0df50dc](https://linux-hardware.org/?probe=efa0df50dc) | Aug 02, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a08886d394](https://linux-hardware.org/?probe=a08886d394) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [fc2f2f7f45](https://linux-hardware.org/?probe=fc2f2f7f45) | Aug 02, 2023 |
| Sony          | VPCSB1V9R                   | Notebook    | [8d809c3877](https://linux-hardware.org/?probe=8d809c3877) | Aug 02, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [46ca3ef1f4](https://linux-hardware.org/?probe=46ca3ef1f4) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [fd9503645f](https://linux-hardware.org/?probe=fd9503645f) | Aug 01, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [9e892c6bc7](https://linux-hardware.org/?probe=9e892c6bc7) | Aug 01, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [3f1af34e1b](https://linux-hardware.org/?probe=3f1af34e1b) | Aug 01, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [37be164783](https://linux-hardware.org/?probe=37be164783) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [e24869945e](https://linux-hardware.org/?probe=e24869945e) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [a2148fe49f](https://linux-hardware.org/?probe=a2148fe49f) | Aug 01, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [13a4427208](https://linux-hardware.org/?probe=13a4427208) | Jul 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [5d12cf34ca](https://linux-hardware.org/?probe=5d12cf34ca) | Jul 31, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [ae14da63f3](https://linux-hardware.org/?probe=ae14da63f3) | Jul 30, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4f94bdf300](https://linux-hardware.org/?probe=4f94bdf300) | Jul 30, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [f1db906c7c](https://linux-hardware.org/?probe=f1db906c7c) | Jul 30, 2023 |
| Samsung       | 960QFG                      | Convertible | [c14544a7ff](https://linux-hardware.org/?probe=c14544a7ff) | Jul 30, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [963eb3c0a8](https://linux-hardware.org/?probe=963eb3c0a8) | Jul 29, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [cb13e61bae](https://linux-hardware.org/?probe=cb13e61bae) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e08f65110d](https://linux-hardware.org/?probe=e08f65110d) | Jul 27, 2023 |
| Google        | Fleex                       | Notebook    | [977fa266d3](https://linux-hardware.org/?probe=977fa266d3) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | Notebook    | [045470ba6d](https://linux-hardware.org/?probe=045470ba6d) | Jul 26, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [7de233f9bd](https://linux-hardware.org/?probe=7de233f9bd) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [2cd6047230](https://linux-hardware.org/?probe=2cd6047230) | Jul 25, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [85168259e3](https://linux-hardware.org/?probe=85168259e3) | Jul 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [0b4b6b015b](https://linux-hardware.org/?probe=0b4b6b015b) | Jul 24, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [351ebe5f4f](https://linux-hardware.org/?probe=351ebe5f4f) | Jul 24, 2023 |
| HP            | 250 G3                      | Notebook    | [5580b343bd](https://linux-hardware.org/?probe=5580b343bd) | Jul 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [8b89c63576](https://linux-hardware.org/?probe=8b89c63576) | Jul 24, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [86035a17da](https://linux-hardware.org/?probe=86035a17da) | Jul 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a179c222ea](https://linux-hardware.org/?probe=a179c222ea) | Jul 23, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f2dfaee237](https://linux-hardware.org/?probe=f2dfaee237) | Jul 23, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [7f3a5aa8cd](https://linux-hardware.org/?probe=7f3a5aa8cd) | Jul 22, 2023 |
| HP            | 86F3 00100                  | All in one  | [26504c2968](https://linux-hardware.org/?probe=26504c2968) | Jul 22, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VU_GZ3... | Tablet      | [7387b87abf](https://linux-hardware.org/?probe=7387b87abf) | Jul 21, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [2a3971e2fc](https://linux-hardware.org/?probe=2a3971e2fc) | Jul 21, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [788fc0bfc9](https://linux-hardware.org/?probe=788fc0bfc9) | Jul 21, 2023 |
| ASUSTek       | G551JK                      | Notebook    | [fed0cf1fce](https://linux-hardware.org/?probe=fed0cf1fce) | Jul 20, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [9a705d5047](https://linux-hardware.org/?probe=9a705d5047) | Jul 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [cc73a658d1](https://linux-hardware.org/?probe=cc73a658d1) | Jul 19, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [89340a2cf7](https://linux-hardware.org/?probe=89340a2cf7) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [7733ed8a40](https://linux-hardware.org/?probe=7733ed8a40) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [4bba49b11c](https://linux-hardware.org/?probe=4bba49b11c) | Jul 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [e6cf0622b0](https://linux-hardware.org/?probe=e6cf0622b0) | Jul 19, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [91f1d1f94f](https://linux-hardware.org/?probe=91f1d1f94f) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [69a47b22c4](https://linux-hardware.org/?probe=69a47b22c4) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [32fbe34ce0](https://linux-hardware.org/?probe=32fbe34ce0) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [25aef4eda4](https://linux-hardware.org/?probe=25aef4eda4) | Jul 18, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [ef2395800e](https://linux-hardware.org/?probe=ef2395800e) | Jul 16, 2023 |
| Teclast       | F7 Plus                     | Notebook    | [1c317224d2](https://linux-hardware.org/?probe=1c317224d2) | Jul 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [52870865a4](https://linux-hardware.org/?probe=52870865a4) | Jul 15, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d589d40102](https://linux-hardware.org/?probe=d589d40102) | Jul 15, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7e0ff09c1f](https://linux-hardware.org/?probe=7e0ff09c1f) | Jul 15, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [44a9f08c5e](https://linux-hardware.org/?probe=44a9f08c5e) | Jul 15, 2023 |
| Notebook      | NH5x_7xRCx,RDx              | Notebook    | [9e8ab59ea8](https://linux-hardware.org/?probe=9e8ab59ea8) | Jul 14, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [2d03b5f0b6](https://linux-hardware.org/?probe=2d03b5f0b6) | Jul 14, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [13961b824f](https://linux-hardware.org/?probe=13961b824f) | Jul 14, 2023 |
| MSI           | B150M ECO                   | Desktop     | [84601cd9dc](https://linux-hardware.org/?probe=84601cd9dc) | Jul 14, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | Notebook    | [2213337296](https://linux-hardware.org/?probe=2213337296) | Jul 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [093938a09b](https://linux-hardware.org/?probe=093938a09b) | Jul 13, 2023 |
| OriginPC      | EVO16-S                     | Notebook    | [f3b1c85a1a](https://linux-hardware.org/?probe=f3b1c85a1a) | Jul 11, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [fddf95e5c8](https://linux-hardware.org/?probe=fddf95e5c8) | Jul 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4347661295](https://linux-hardware.org/?probe=4347661295) | Jul 11, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [a497806f86](https://linux-hardware.org/?probe=a497806f86) | Jul 10, 2023 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [93fcbdf5d5](https://linux-hardware.org/?probe=93fcbdf5d5) | Jul 10, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [160af9ddfb](https://linux-hardware.org/?probe=160af9ddfb) | Jul 09, 2023 |
| Lenovo        | ThinkPad A275 20KCS08C0K    | Notebook    | [9857dab3ab](https://linux-hardware.org/?probe=9857dab3ab) | Jul 08, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [7fde9afaf1](https://linux-hardware.org/?probe=7fde9afaf1) | Jul 08, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [09ada263c3](https://linux-hardware.org/?probe=09ada263c3) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [33e4bac631](https://linux-hardware.org/?probe=33e4bac631) | Jul 05, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [60c1acd1fc](https://linux-hardware.org/?probe=60c1acd1fc) | Jul 04, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16IAH7 8... | Notebook    | [ad57a8dd50](https://linux-hardware.org/?probe=ad57a8dd50) | Jul 04, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0064c1c269](https://linux-hardware.org/?probe=0064c1c269) | Jul 03, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f9e366002e](https://linux-hardware.org/?probe=f9e366002e) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [c1a241c0a5](https://linux-hardware.org/?probe=c1a241c0a5) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [6df7cc5145](https://linux-hardware.org/?probe=6df7cc5145) | Jul 02, 2023 |
| Dell          | Latitude E5470              | Notebook    | [0a50455c18](https://linux-hardware.org/?probe=0a50455c18) | Jul 02, 2023 |
| Lenovo        | Legion Y9000X IAH7 82TF     | Notebook    | [efb7d0f42a](https://linux-hardware.org/?probe=efb7d0f42a) | Jul 02, 2023 |
| Dell          | XPS L521X                   | Notebook    | [b80baf340c](https://linux-hardware.org/?probe=b80baf340c) | Jul 02, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [83dd07d2a7](https://linux-hardware.org/?probe=83dd07d2a7) | Jul 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [cf9a80fbbc](https://linux-hardware.org/?probe=cf9a80fbbc) | Jul 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [1ab74730be](https://linux-hardware.org/?probe=1ab74730be) | Jul 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b5f1dc88df](https://linux-hardware.org/?probe=b5f1dc88df) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [916b60f6f7](https://linux-hardware.org/?probe=916b60f6f7) | Jun 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f3cb4dc749](https://linux-hardware.org/?probe=f3cb4dc749) | Jun 29, 2023 |
| eMachines     | eME728                      | Notebook    | [37dc0ef617](https://linux-hardware.org/?probe=37dc0ef617) | Jun 29, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [89f1647ea1](https://linux-hardware.org/?probe=89f1647ea1) | Jun 29, 2023 |
| MSI           | A320M PRO-VH                | Desktop     | [1a84c61bd4](https://linux-hardware.org/?probe=1a84c61bd4) | Jun 27, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [c147d5716d](https://linux-hardware.org/?probe=c147d5716d) | Jun 27, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d0d602b518](https://linux-hardware.org/?probe=d0d602b518) | Jun 27, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [f664b455eb](https://linux-hardware.org/?probe=f664b455eb) | Jun 26, 2023 |
| Google        | Sasuke                      | Notebook    | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e0f5116d38](https://linux-hardware.org/?probe=e0f5116d38) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7ac67acfed](https://linux-hardware.org/?probe=7ac67acfed) | Jun 21, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [481ef14837](https://linux-hardware.org/?probe=481ef14837) | Jun 21, 2023 |
| MSI           | B450M PRO-VDH               | Desktop     | [ed8ee7af2c](https://linux-hardware.org/?probe=ed8ee7af2c) | Jun 19, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [78207fbf49](https://linux-hardware.org/?probe=78207fbf49) | Jun 19, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [90720c3820](https://linux-hardware.org/?probe=90720c3820) | Jun 18, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [4b184d1037](https://linux-hardware.org/?probe=4b184d1037) | Jun 18, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [2bcd63ec1e](https://linux-hardware.org/?probe=2bcd63ec1e) | Jun 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [bc3ba9b05e](https://linux-hardware.org/?probe=bc3ba9b05e) | Jun 15, 2023 |
| ZOTAC         | ZBOX-EN760                  | Mini pc     | [e36c953da7](https://linux-hardware.org/?probe=e36c953da7) | Jun 14, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [1050576987](https://linux-hardware.org/?probe=1050576987) | Jun 14, 2023 |
| Dell          | Latitude E5570              | Notebook    | [43171e0f19](https://linux-hardware.org/?probe=43171e0f19) | Jun 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e8ed28dba0](https://linux-hardware.org/?probe=e8ed28dba0) | Jun 14, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [3528d095e0](https://linux-hardware.org/?probe=3528d095e0) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2db1bbb316](https://linux-hardware.org/?probe=2db1bbb316) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [507d8cc765](https://linux-hardware.org/?probe=507d8cc765) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21a8144a2e](https://linux-hardware.org/?probe=21a8144a2e) | Jun 13, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [51a3b444dd](https://linux-hardware.org/?probe=51a3b444dd) | Jun 13, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c433d533f0](https://linux-hardware.org/?probe=c433d533f0) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3c7683dfc4](https://linux-hardware.org/?probe=3c7683dfc4) | Jun 11, 2023 |
| ASUSTek       | CM6850                      | Desktop     | [33579719ed](https://linux-hardware.org/?probe=33579719ed) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1d46e48d92](https://linux-hardware.org/?probe=1d46e48d92) | Jun 10, 2023 |
| Dell          | Latitude E6510              | Notebook    | [e7c1e59ac7](https://linux-hardware.org/?probe=e7c1e59ac7) | Jun 10, 2023 |
| Dell          | 0DWPVW A00                  | Desktop     | [ffad802816](https://linux-hardware.org/?probe=ffad802816) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [a597fc235e](https://linux-hardware.org/?probe=a597fc235e) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [6a368b8ecc](https://linux-hardware.org/?probe=6a368b8ecc) | Jun 09, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [2f0f8eb596](https://linux-hardware.org/?probe=2f0f8eb596) | Jun 09, 2023 |
| VIT           | P2402                       | Notebook    | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [52df878410](https://linux-hardware.org/?probe=52df878410) | Jun 08, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [0f41ab04b6](https://linux-hardware.org/?probe=0f41ab04b6) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [3e38c53463](https://linux-hardware.org/?probe=3e38c53463) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [0e24e0ad6c](https://linux-hardware.org/?probe=0e24e0ad6c) | Jun 07, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [33fb312b6d](https://linux-hardware.org/?probe=33fb312b6d) | Jun 05, 2023 |
| Dell          | 0D24M8 A00                  | Desktop     | [92fe930ecf](https://linux-hardware.org/?probe=92fe930ecf) | Jun 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [bfe6623b23](https://linux-hardware.org/?probe=bfe6623b23) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [c3dae64ee6](https://linux-hardware.org/?probe=c3dae64ee6) | Jun 03, 2023 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [1b01df33d2](https://linux-hardware.org/?probe=1b01df33d2) | Jun 03, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [04830d213f](https://linux-hardware.org/?probe=04830d213f) | Jun 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [4ccfddd671](https://linux-hardware.org/?probe=4ccfddd671) | Jun 02, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [becb85a201](https://linux-hardware.org/?probe=becb85a201) | Jun 02, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [c4cd05b00f](https://linux-hardware.org/?probe=c4cd05b00f) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [7d35807036](https://linux-hardware.org/?probe=7d35807036) | Jun 01, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3de415ea72](https://linux-hardware.org/?probe=3de415ea72) | Jun 01, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [8bc281486e](https://linux-hardware.org/?probe=8bc281486e) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c198463bc3](https://linux-hardware.org/?probe=c198463bc3) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [a1f825f4e5](https://linux-hardware.org/?probe=a1f825f4e5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | Notebook    | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | Notebook    | [0b04d3bf20](https://linux-hardware.org/?probe=0b04d3bf20) | May 28, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [574e88c4f3](https://linux-hardware.org/?probe=574e88c4f3) | May 28, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [af33101302](https://linux-hardware.org/?probe=af33101302) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| HP            | 86EE                        | All in one  | [ba49672c5b](https://linux-hardware.org/?probe=ba49672c5b) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4362f979b8](https://linux-hardware.org/?probe=4362f979b8) | May 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a36e1c1d5](https://linux-hardware.org/?probe=2a36e1c1d5) | May 26, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [4c22ef876f](https://linux-hardware.org/?probe=4c22ef876f) | May 26, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [46cb91a74d](https://linux-hardware.org/?probe=46cb91a74d) | May 25, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [48bd340a09](https://linux-hardware.org/?probe=48bd340a09) | May 24, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [7f5d36cc34](https://linux-hardware.org/?probe=7f5d36cc34) | May 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b7fbda70d3](https://linux-hardware.org/?probe=b7fbda70d3) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a605d12e2d](https://linux-hardware.org/?probe=a605d12e2d) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a1770c45b0](https://linux-hardware.org/?probe=a1770c45b0) | May 23, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [0cba90ce8e](https://linux-hardware.org/?probe=0cba90ce8e) | May 23, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [a48977a871](https://linux-hardware.org/?probe=a48977a871) | May 22, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| HP            | 18E4                        | Desktop     | [5601900c8b](https://linux-hardware.org/?probe=5601900c8b) | May 22, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [1125a4111e](https://linux-hardware.org/?probe=1125a4111e) | May 19, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [1edee9f902](https://linux-hardware.org/?probe=1edee9f902) | May 18, 2023 |
| Lenovo        | 3734 SDK0R32862 WIN 3258... | All in one  | [da9ebc680a](https://linux-hardware.org/?probe=da9ebc680a) | May 16, 2023 |
| HP            | 18E4                        | Desktop     | [7560196205](https://linux-hardware.org/?probe=7560196205) | May 16, 2023 |
| HP            | 18E4                        | Desktop     | [4dc91feab7](https://linux-hardware.org/?probe=4dc91feab7) | May 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [59a9ba6e16](https://linux-hardware.org/?probe=59a9ba6e16) | May 13, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [4fd655c0aa](https://linux-hardware.org/?probe=4fd655c0aa) | May 13, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [e4bfe14f2d](https://linux-hardware.org/?probe=e4bfe14f2d) | May 13, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [bc0dacd119](https://linux-hardware.org/?probe=bc0dacd119) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [35d056f8bd](https://linux-hardware.org/?probe=35d056f8bd) | May 11, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| HP            | 18E4                        | Desktop     | [2a528dc758](https://linux-hardware.org/?probe=2a528dc758) | May 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b81c403545](https://linux-hardware.org/?probe=b81c403545) | May 09, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [3346a6a326](https://linux-hardware.org/?probe=3346a6a326) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [2a7a243899](https://linux-hardware.org/?probe=2a7a243899) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [c7a298018f](https://linux-hardware.org/?probe=c7a298018f) | May 08, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [a916fc6080](https://linux-hardware.org/?probe=a916fc6080) | May 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7a1ffd8bd2](https://linux-hardware.org/?probe=7a1ffd8bd2) | May 07, 2023 |
| Timi          | TM1701                      | Notebook    | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [7ab24c2d1a](https://linux-hardware.org/?probe=7ab24c2d1a) | May 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [df58b07032](https://linux-hardware.org/?probe=df58b07032) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [91c6b0d769](https://linux-hardware.org/?probe=91c6b0d769) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| HP            | 1589                        | Desktop     | [dd3e55b423](https://linux-hardware.org/?probe=dd3e55b423) | May 05, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8ff62a5045](https://linux-hardware.org/?probe=8ff62a5045) | May 05, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [bac25fa124](https://linux-hardware.org/?probe=bac25fa124) | May 04, 2023 |
| Lenovo        | ThinkPad W530 24473F2       | Notebook    | [937dddbff0](https://linux-hardware.org/?probe=937dddbff0) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e49682836a](https://linux-hardware.org/?probe=e49682836a) | May 04, 2023 |
| HP            | 18E4                        | Desktop     | [d1344e36dd](https://linux-hardware.org/?probe=d1344e36dd) | May 03, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [9984dd7707](https://linux-hardware.org/?probe=9984dd7707) | May 03, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [16ac84221b](https://linux-hardware.org/?probe=16ac84221b) | May 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [96402fa64a](https://linux-hardware.org/?probe=96402fa64a) | May 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [07324ae678](https://linux-hardware.org/?probe=07324ae678) | May 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [24363c23cf](https://linux-hardware.org/?probe=24363c23cf) | May 01, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1a343a4622](https://linux-hardware.org/?probe=1a343a4622) | Apr 30, 2023 |
| Dell          | Latitude 5580               | Notebook    | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [54f8ed91cf](https://linux-hardware.org/?probe=54f8ed91cf) | Apr 30, 2023 |
| HP            | 18E4                        | Desktop     | [da858ea464](https://linux-hardware.org/?probe=da858ea464) | Apr 30, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [8c4352985e](https://linux-hardware.org/?probe=8c4352985e) | Apr 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c1e0f0fa03](https://linux-hardware.org/?probe=c1e0f0fa03) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| HP            | 8715                        | Mini pc     | [8d210cce39](https://linux-hardware.org/?probe=8d210cce39) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f1d5d361d5](https://linux-hardware.org/?probe=f1d5d361d5) | Apr 27, 2023 |
| MSI           | Modern 14 C7M               | Notebook    | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [17ae2e245a](https://linux-hardware.org/?probe=17ae2e245a) | Apr 22, 2023 |
| Notebook      | W65_W67RB                   | Notebook    | [f34e442b8b](https://linux-hardware.org/?probe=f34e442b8b) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | Notebook    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [00f7379c8f](https://linux-hardware.org/?probe=00f7379c8f) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [c27abc2880](https://linux-hardware.org/?probe=c27abc2880) | Apr 17, 2023 |
| ASUSTek       | X55A                        | Notebook    | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | Notebook    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f6a652b68d](https://linux-hardware.org/?probe=f6a652b68d) | Apr 14, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [8eaac4a62d](https://linux-hardware.org/?probe=8eaac4a62d) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [47f2ba894b](https://linux-hardware.org/?probe=47f2ba894b) | Apr 12, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [07353da9f6](https://linux-hardware.org/?probe=07353da9f6) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d9f95c9169](https://linux-hardware.org/?probe=d9f95c9169) | Apr 11, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [0e074bebcf](https://linux-hardware.org/?probe=0e074bebcf) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59db7a4f11](https://linux-hardware.org/?probe=59db7a4f11) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [01cae1e152](https://linux-hardware.org/?probe=01cae1e152) | Apr 10, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| HP            | 18E4                        | Desktop     | [54c681affc](https://linux-hardware.org/?probe=54c681affc) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [15d7d40bed](https://linux-hardware.org/?probe=15d7d40bed) | Apr 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | Notebook    | [aee22ee8b3](https://linux-hardware.org/?probe=aee22ee8b3) | Apr 08, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [d1167f66b8](https://linux-hardware.org/?probe=d1167f66b8) | Apr 08, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [a6c5efe560](https://linux-hardware.org/?probe=a6c5efe560) | Apr 07, 2023 |
| HP            | 250 G4                      | Notebook    | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| HP            | Unknown                     | Notebook    | [0af30fd642](https://linux-hardware.org/?probe=0af30fd642) | Apr 06, 2023 |
| Gigabyte      | H87M-D3H                    | Desktop     | [b9c169025d](https://linux-hardware.org/?probe=b9c169025d) | Apr 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5012c822d7](https://linux-hardware.org/?probe=5012c822d7) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [33eb81c75e](https://linux-hardware.org/?probe=33eb81c75e) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | Notebook    | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [546e8e3742](https://linux-hardware.org/?probe=546e8e3742) | Apr 04, 2023 |
| Samsung       | 950QDB                      | Convertible | [967646c481](https://linux-hardware.org/?probe=967646c481) | Apr 04, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [5035f094da](https://linux-hardware.org/?probe=5035f094da) | Apr 03, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [d3a27ee996](https://linux-hardware.org/?probe=d3a27ee996) | Apr 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [9ba99b597e](https://linux-hardware.org/?probe=9ba99b597e) | Apr 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [d64af320d7](https://linux-hardware.org/?probe=d64af320d7) | Apr 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [3400bd9412](https://linux-hardware.org/?probe=3400bd9412) | Apr 02, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | Notebook    | [edb6e927bd](https://linux-hardware.org/?probe=edb6e927bd) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | Notebook    | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [bfba694531](https://linux-hardware.org/?probe=bfba694531) | Apr 01, 2023 |
| HP            | 8715                        | Mini pc     | [bcd377dcb7](https://linux-hardware.org/?probe=bcd377dcb7) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [4169f13182](https://linux-hardware.org/?probe=4169f13182) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [3ac0a9cc94](https://linux-hardware.org/?probe=3ac0a9cc94) | Mar 31, 2023 |
| GPD           | G1621-02                    | Notebook    | [7d000ab41b](https://linux-hardware.org/?probe=7d000ab41b) | Mar 31, 2023 |
| HP            | 8715                        | Mini pc     | [222fde0a83](https://linux-hardware.org/?probe=222fde0a83) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [008eb6ad60](https://linux-hardware.org/?probe=008eb6ad60) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4dd142ab8f](https://linux-hardware.org/?probe=4dd142ab8f) | Mar 31, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [d1295d9d1e](https://linux-hardware.org/?probe=d1295d9d1e) | Mar 30, 2023 |
| AWOW          | AL34                        | Notebook    | [19f60f27c8](https://linux-hardware.org/?probe=19f60f27c8) | Mar 29, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [65671e15cb](https://linux-hardware.org/?probe=65671e15cb) | Mar 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [b165f54c80](https://linux-hardware.org/?probe=b165f54c80) | Mar 28, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [d80388d7ef](https://linux-hardware.org/?probe=d80388d7ef) | Mar 27, 2023 |
| HP            | 18E4                        | Desktop     | [5d10e73e1d](https://linux-hardware.org/?probe=5d10e73e1d) | Mar 26, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a8d31fc431](https://linux-hardware.org/?probe=a8d31fc431) | Mar 26, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [4253088a92](https://linux-hardware.org/?probe=4253088a92) | Mar 25, 2023 |
| Samsung       | 550XDA                      | Notebook    | [058982f7d8](https://linux-hardware.org/?probe=058982f7d8) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [18cd806803](https://linux-hardware.org/?probe=18cd806803) | Mar 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E6C... | Notebook    | [3042a430c0](https://linux-hardware.org/?probe=3042a430c0) | Mar 24, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e923cf7edb](https://linux-hardware.org/?probe=e923cf7edb) | Mar 24, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [5bd922e142](https://linux-hardware.org/?probe=5bd922e142) | Mar 23, 2023 |
| AZW           | GK35                        | Desktop     | [bd935978b7](https://linux-hardware.org/?probe=bd935978b7) | Mar 22, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| GPD           | G1619-04                    | Notebook    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [e0ec2e73be](https://linux-hardware.org/?probe=e0ec2e73be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Acer          | Swift SF315-52G             | Notebook    | [f6042580d0](https://linux-hardware.org/?probe=f6042580d0) | Mar 20, 2023 |
| Notebook      | N150ZU                      | Notebook    | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [a911c14f22](https://linux-hardware.org/?probe=a911c14f22) | Mar 19, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5f14b733bb](https://linux-hardware.org/?probe=5f14b733bb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| ASUSTek       | UX301LAA                    | Notebook    | [882d4d095b](https://linux-hardware.org/?probe=882d4d095b) | Mar 18, 2023 |
| HP            | 8715                        | Mini pc     | [1c2c765978](https://linux-hardware.org/?probe=1c2c765978) | Mar 18, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [a3e8bcd9dd](https://linux-hardware.org/?probe=a3e8bcd9dd) | Mar 18, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [ae4d8ba68c](https://linux-hardware.org/?probe=ae4d8ba68c) | Mar 18, 2023 |
| AZW           | U59                         | Desktop     | [ce6bd37711](https://linux-hardware.org/?probe=ce6bd37711) | Mar 18, 2023 |
| HP            | 8715                        | Mini pc     | [cd9310c350](https://linux-hardware.org/?probe=cd9310c350) | Mar 17, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [b43ea7bb6e](https://linux-hardware.org/?probe=b43ea7bb6e) | Mar 17, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [c6ef926aa6](https://linux-hardware.org/?probe=c6ef926aa6) | Mar 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d95b09eda0](https://linux-hardware.org/?probe=d95b09eda0) | Mar 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [066f0cd17b](https://linux-hardware.org/?probe=066f0cd17b) | Mar 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | Notebook    | [b588252431](https://linux-hardware.org/?probe=b588252431) | Mar 14, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [0f3b7bd317](https://linux-hardware.org/?probe=0f3b7bd317) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Notebook    | [7f58d0d0a0](https://linux-hardware.org/?probe=7f58d0d0a0) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Notebook    | [0c58b8ebad](https://linux-hardware.org/?probe=0c58b8ebad) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [fc04961aef](https://linux-hardware.org/?probe=fc04961aef) | Mar 11, 2023 |
| Unknown       | HX90                        | Desktop     | [51aca581e4](https://linux-hardware.org/?probe=51aca581e4) | Mar 11, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [bf6081f2af](https://linux-hardware.org/?probe=bf6081f2af) | Mar 09, 2023 |
| Dell          | Precision 7720              | Notebook    | [6132f690aa](https://linux-hardware.org/?probe=6132f690aa) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [8a33917a89](https://linux-hardware.org/?probe=8a33917a89) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [f4d71dcbd0](https://linux-hardware.org/?probe=f4d71dcbd0) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0fdb67b9d2](https://linux-hardware.org/?probe=0fdb67b9d2) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2e48f233a0](https://linux-hardware.org/?probe=2e48f233a0) | Mar 09, 2023 |
| Dell          | Precision 7720              | Notebook    | [e4a1149bcb](https://linux-hardware.org/?probe=e4a1149bcb) | Mar 08, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [af171db9dc](https://linux-hardware.org/?probe=af171db9dc) | Mar 08, 2023 |
| Timi          | TM1701                      | Notebook    | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [f363dca8ca](https://linux-hardware.org/?probe=f363dca8ca) | Mar 07, 2023 |
| HP            | 8860 A                      | Desktop     | [78c9aa9174](https://linux-hardware.org/?probe=78c9aa9174) | Mar 07, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3519073f46](https://linux-hardware.org/?probe=3519073f46) | Mar 07, 2023 |
| Dell          | Latitude 5289               | Notebook    | [dcac5b8ebc](https://linux-hardware.org/?probe=dcac5b8ebc) | Mar 06, 2023 |
| Google        | Rammus                      | Notebook    | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| HP            | 18E4                        | Desktop     | [a277b636c1](https://linux-hardware.org/?probe=a277b636c1) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
| HP            | 18E4                        | Desktop     | [8e76736e7e](https://linux-hardware.org/?probe=8e76736e7e) | Mar 02, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [80dca547fc](https://linux-hardware.org/?probe=80dca547fc) | Mar 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [89fb184b09](https://linux-hardware.org/?probe=89fb184b09) | Mar 01, 2023 |
| HP            | 18E4                        | Desktop     | [cab6d807e9](https://linux-hardware.org/?probe=cab6d807e9) | Feb 27, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1412fd5885](https://linux-hardware.org/?probe=1412fd5885) | Feb 26, 2023 |
| HP            | 18E4                        | Desktop     | [5c7c3413c9](https://linux-hardware.org/?probe=5c7c3413c9) | Feb 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [ccff1403b0](https://linux-hardware.org/?probe=ccff1403b0) | Feb 24, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [32f4f192fa](https://linux-hardware.org/?probe=32f4f192fa) | Feb 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [576a0fc8f5](https://linux-hardware.org/?probe=576a0fc8f5) | Feb 23, 2023 |
| Medion        | Akoya E6412T                | Notebook    | [2915d1c409](https://linux-hardware.org/?probe=2915d1c409) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [e8963c4e59](https://linux-hardware.org/?probe=e8963c4e59) | Feb 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d5f5531b82](https://linux-hardware.org/?probe=d5f5531b82) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [6234395029](https://linux-hardware.org/?probe=6234395029) | Feb 18, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7af4d238e8](https://linux-hardware.org/?probe=7af4d238e8) | Feb 18, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [09b0c2bf17](https://linux-hardware.org/?probe=09b0c2bf17) | Feb 17, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f594570a77](https://linux-hardware.org/?probe=f594570a77) | Feb 16, 2023 |
| Google        | Helios                      | Notebook    | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [b0693958a6](https://linux-hardware.org/?probe=b0693958a6) | Feb 15, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [c84212b39c](https://linux-hardware.org/?probe=c84212b39c) | Feb 15, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [6c540405e8](https://linux-hardware.org/?probe=6c540405e8) | Feb 15, 2023 |
| GPD           | G1621-02                    | Notebook    | [5d584fa1cf](https://linux-hardware.org/?probe=5d584fa1cf) | Feb 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4b0331863e](https://linux-hardware.org/?probe=4b0331863e) | Feb 14, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [d8ed5d5e88](https://linux-hardware.org/?probe=d8ed5d5e88) | Feb 14, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [820aa2bf49](https://linux-hardware.org/?probe=820aa2bf49) | Feb 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM    | Notebook    | [9e0e0bef82](https://linux-hardware.org/?probe=9e0e0bef82) | Feb 13, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [debdb17904](https://linux-hardware.org/?probe=debdb17904) | Feb 12, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8133fc11b8](https://linux-hardware.org/?probe=8133fc11b8) | Feb 12, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [05d11c4fe3](https://linux-hardware.org/?probe=05d11c4fe3) | Feb 12, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| HP            | Compaq 6820s                | Notebook    | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [0c6da36f9d](https://linux-hardware.org/?probe=0c6da36f9d) | Feb 11, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [059d515c3c](https://linux-hardware.org/?probe=059d515c3c) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Dell          | 0Y5FXV A00                  | Desktop     | [692b7eab6b](https://linux-hardware.org/?probe=692b7eab6b) | Feb 08, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2LN0... | Notebook    | [4fdb5d662c](https://linux-hardware.org/?probe=4fdb5d662c) | Feb 08, 2023 |
| HP            | ENVY Notebook PC            | Convertible | [a8165997b7](https://linux-hardware.org/?probe=a8165997b7) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [43c3e4d160](https://linux-hardware.org/?probe=43c3e4d160) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [f2a6af1f7e](https://linux-hardware.org/?probe=f2a6af1f7e) | Feb 06, 2023 |
| HP            | Setzer                      | Notebook    | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [e523dbd162](https://linux-hardware.org/?probe=e523dbd162) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [96847498e3](https://linux-hardware.org/?probe=96847498e3) | Feb 02, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [ecf260f299](https://linux-hardware.org/?probe=ecf260f299) | Feb 01, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [de7f0840d1](https://linux-hardware.org/?probe=de7f0840d1) | Feb 01, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [455825998f](https://linux-hardware.org/?probe=455825998f) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4251ab2f9a](https://linux-hardware.org/?probe=4251ab2f9a) | Feb 01, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [bcaa2e6b1a](https://linux-hardware.org/?probe=bcaa2e6b1a) | Jan 30, 2023 |
| Dell          | Latitude 5400               | Notebook    | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [3e957e185d](https://linux-hardware.org/?probe=3e957e185d) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [849d901314](https://linux-hardware.org/?probe=849d901314) | Jan 28, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [b15899ef80](https://linux-hardware.org/?probe=b15899ef80) | Jan 27, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [357a0cd22d](https://linux-hardware.org/?probe=357a0cd22d) | Jan 27, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Dell          | Latitude E5410              | Notebook    | [22df8731a9](https://linux-hardware.org/?probe=22df8731a9) | Jan 26, 2023 |
| Google        | Magpie                      | Notebook    | [34506f260e](https://linux-hardware.org/?probe=34506f260e) | Jan 26, 2023 |
| HP            | 86EE                        | All in one  | [2632541785](https://linux-hardware.org/?probe=2632541785) | Jan 25, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [55b2bf8aea](https://linux-hardware.org/?probe=55b2bf8aea) | Jan 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [56a9b7ad32](https://linux-hardware.org/?probe=56a9b7ad32) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [f371c1c8b6](https://linux-hardware.org/?probe=f371c1c8b6) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Notebook    | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [1153793fd9](https://linux-hardware.org/?probe=1153793fd9) | Jan 22, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [10796ad8f6](https://linux-hardware.org/?probe=10796ad8f6) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [f1d22db1d7](https://linux-hardware.org/?probe=f1d22db1d7) | Jan 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [2c44f8275e](https://linux-hardware.org/?probe=2c44f8275e) | Jan 17, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [25cbbcfc98](https://linux-hardware.org/?probe=25cbbcfc98) | Jan 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [2e40c15660](https://linux-hardware.org/?probe=2e40c15660) | Jan 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [8b1ccef51d](https://linux-hardware.org/?probe=8b1ccef51d) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [154dafff1e](https://linux-hardware.org/?probe=154dafff1e) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [ce588e0413](https://linux-hardware.org/?probe=ce588e0413) | Jan 14, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [1681bdc38e](https://linux-hardware.org/?probe=1681bdc38e) | Jan 14, 2023 |
| Dell          | Precision M4800             | Notebook    | [c5deb205c7](https://linux-hardware.org/?probe=c5deb205c7) | Jan 14, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [425fb5340d](https://linux-hardware.org/?probe=425fb5340d) | Jan 13, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [4fc1f3aff0](https://linux-hardware.org/?probe=4fc1f3aff0) | Jan 11, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [878c92decc](https://linux-hardware.org/?probe=878c92decc) | Jan 11, 2023 |
| HP            | 18E4                        | Desktop     | [600d82b264](https://linux-hardware.org/?probe=600d82b264) | Jan 11, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| HP            | 18E4                        | Desktop     | [3386d53667](https://linux-hardware.org/?probe=3386d53667) | Jan 10, 2023 |
| HP            | 2179                        | Desktop     | [ad75cc2104](https://linux-hardware.org/?probe=ad75cc2104) | Jan 10, 2023 |
| Dell          | 0NRKPK A01                  | Desktop     | [f5bdf45b4a](https://linux-hardware.org/?probe=f5bdf45b4a) | Jan 08, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [c18913a39e](https://linux-hardware.org/?probe=c18913a39e) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [28ed8a48bd](https://linux-hardware.org/?probe=28ed8a48bd) | Jan 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4947d17a2b](https://linux-hardware.org/?probe=4947d17a2b) | Jan 06, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [b2dfc2437e](https://linux-hardware.org/?probe=b2dfc2437e) | Jan 06, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [81431f1578](https://linux-hardware.org/?probe=81431f1578) | Jan 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [cef6a9db45](https://linux-hardware.org/?probe=cef6a9db45) | Jan 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [8defa5d641](https://linux-hardware.org/?probe=8defa5d641) | Jan 05, 2023 |
| Dell          | XPS 9320                    | Notebook    | [8684c6d86b](https://linux-hardware.org/?probe=8684c6d86b) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c84118baf](https://linux-hardware.org/?probe=0c84118baf) | Jan 03, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [be6730b67b](https://linux-hardware.org/?probe=be6730b67b) | Jan 03, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [2d0530b779](https://linux-hardware.org/?probe=2d0530b779) | Jan 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [bc57a904f7](https://linux-hardware.org/?probe=bc57a904f7) | Jan 03, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [d94e8b5637](https://linux-hardware.org/?probe=d94e8b5637) | Jan 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1be42c9032](https://linux-hardware.org/?probe=1be42c9032) | Jan 02, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [b613cd1179](https://linux-hardware.org/?probe=b613cd1179) | Jan 02, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [8f923bc065](https://linux-hardware.org/?probe=8f923bc065) | Jan 01, 2023 |
| Toshiba       | EQUIUM A100                 | Notebook    | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [6def847114](https://linux-hardware.org/?probe=6def847114) | Jan 01, 2023 |
| HP            | 18E4                        | Desktop     | [c83c8341e3](https://linux-hardware.org/?probe=c83c8341e3) | Jan 01, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [20eb2d93e2](https://linux-hardware.org/?probe=20eb2d93e2) | Jan 01, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [e0cb4d278d](https://linux-hardware.org/?probe=e0cb4d278d) | Dec 31, 2022 |
| HP            | 18E4                        | Desktop     | [1b1eccbbe1](https://linux-hardware.org/?probe=1b1eccbbe1) | Dec 31, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [9aba0ac647](https://linux-hardware.org/?probe=9aba0ac647) | Dec 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [30e1303337](https://linux-hardware.org/?probe=30e1303337) | Dec 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4d915292f4](https://linux-hardware.org/?probe=4d915292f4) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [b38e3cc51e](https://linux-hardware.org/?probe=b38e3cc51e) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ce45aaceaf](https://linux-hardware.org/?probe=ce45aaceaf) | Dec 29, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [adb13e2649](https://linux-hardware.org/?probe=adb13e2649) | Dec 29, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [e422b934d0](https://linux-hardware.org/?probe=e422b934d0) | Dec 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b8099c7a94](https://linux-hardware.org/?probe=b8099c7a94) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [475b76e98a](https://linux-hardware.org/?probe=475b76e98a) | Dec 28, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [cd90f1782c](https://linux-hardware.org/?probe=cd90f1782c) | Dec 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [78418bfaa6](https://linux-hardware.org/?probe=78418bfaa6) | Dec 25, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | Notebook    | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [416b0bb4e1](https://linux-hardware.org/?probe=416b0bb4e1) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [244ad65a78](https://linux-hardware.org/?probe=244ad65a78) | Dec 24, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/EndeavourOS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 1213      | 88.67%  |
| EndeavourOS         | 154       | 11.26%  |
| EndeavourOS 23.1.0  | 1         | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| EndeavourOS | 1356      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 6.5.9-arch2-1    | 29        | 1.82%   |
| 6.4.12-arch1-1   | 23        | 1.44%   |
| 6.6.7-arch1-1    | 22        | 1.38%   |
| 6.6.1-arch1-1    | 20        | 1.25%   |
| 6.2.8-arch1-1    | 20        | 1.25%   |
| 5.15.12-arch1-1  | 20        | 1.25%   |
| 6.6.8-arch1-1    | 16        | 1%      |
| 6.1.1-arch1-1    | 16        | 1%      |
| 6.3.9-arch1-1    | 15        | 0.94%   |
| 6.6.2-arch1-1    | 13        | 0.81%   |
| 6.5.7-arch1-1    | 13        | 0.81%   |
| 6.3.1-arch1-1    | 13        | 0.81%   |
| 6.1.12-arch1-1   | 13        | 0.81%   |
| 6.7.0-arch3-1    | 12        | 0.75%   |
| 6.5.3-arch1-1    | 12        | 0.75%   |
| 6.3.4-arch1-1    | 12        | 0.75%   |
| 6.2.2-arch1-1    | 11        | 0.69%   |
| 6.2.13-arch1-1   | 11        | 0.69%   |
| 6.2.10-arch1-1   | 11        | 0.69%   |
| 6.0.9-arch1-1    | 11        | 0.69%   |
| 6.0.2-arch1-1    | 11        | 0.69%   |
| 5.17.1-arch1-1   | 11        | 0.69%   |
| 6.6.4-arch1-1    | 10        | 0.63%   |
| 6.6.10-arch1-1   | 10        | 0.63%   |
| 6.5.5-arch1-1    | 10        | 0.63%   |
| 6.4.11-arch2-1   | 10        | 0.63%   |
| 5.19.7-arch1-1   | 10        | 0.63%   |
| 5.17.5-arch1-1   | 10        | 0.63%   |
| 6.5.8-arch1-1    | 9         | 0.56%   |
| 6.0.2-zen1-1-zen | 9         | 0.56%   |
| 6.0.12-arch1-1   | 9         | 0.56%   |
| 5.15.10-arch1-1  | 9         | 0.56%   |
| 6.6.3-arch1-1    | 8         | 0.5%    |
| 6.4.7-arch1-1    | 8         | 0.5%    |
| 6.2.9-arch1-1    | 8         | 0.5%    |
| 5.17.9-arch1-1   | 8         | 0.5%    |
| 5.15.7-arch1-1   | 8         | 0.5%    |
| 5.14.9-arch2-1   | 8         | 0.5%    |
| 5.13.13-arch1-1  | 8         | 0.5%    |
| 5.11.11-arch1-1  | 8         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5.9   | 33        | 2.07%   |
| 6.4.12  | 29        | 1.82%   |
| 5.15.12 | 28        | 1.75%   |
| 6.6.1   | 27        | 1.69%   |
| 6.6.7   | 24        | 1.5%    |
| 6.3.1   | 23        | 1.44%   |
| 6.1.1   | 23        | 1.44%   |
| 6.2.8   | 22        | 1.38%   |
| 6.0.2   | 22        | 1.38%   |
| 6.6.8   | 18        | 1.13%   |
| 6.6.2   | 18        | 1.13%   |
| 6.7.0   | 16        | 1%      |
| 6.5.8   | 16        | 1%      |
| 6.5.3   | 16        | 1%      |
| 6.4.11  | 16        | 1%      |
| 6.3.9   | 16        | 1%      |
| 6.3.4   | 16        | 1%      |
| 6.5.7   | 15        | 0.94%   |
| 6.4.7   | 15        | 0.94%   |
| 6.4.3   | 15        | 0.94%   |
| 6.1.12  | 15        | 0.94%   |
| 6.0.9   | 15        | 0.94%   |
| 5.17.1  | 15        | 0.94%   |
| 6.2.2   | 14        | 0.88%   |
| 6.2.13  | 14        | 0.88%   |
| 5.17.5  | 14        | 0.88%   |
| 6.6.10  | 13        | 0.81%   |
| 6.5.5   | 13        | 0.81%   |
| 6.2.10  | 13        | 0.81%   |
| 6.6.4   | 12        | 0.75%   |
| 6.0.6   | 12        | 0.75%   |
| 6.0.12  | 12        | 0.75%   |
| 5.19.7  | 12        | 0.75%   |
| 5.13.13 | 12        | 0.75%   |
| 6.2.9   | 11        | 0.69%   |
| 5.18.12 | 11        | 0.69%   |
| 5.17.9  | 11        | 0.69%   |
| 6.7.2   | 10        | 0.63%   |
| 6.5.4   | 10        | 0.63%   |
| 6.4.1   | 10        | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 159       | 10.35%  |
| 5.15    | 139       | 9.05%   |
| 6.6     | 137       | 8.92%   |
| 6.4     | 116       | 7.55%   |
| 6.5     | 113       | 7.36%   |
| 6.2     | 105       | 6.84%   |
| 6.3     | 86        | 5.6%    |
| 6.0     | 83        | 5.4%    |
| 5.19    | 79        | 5.14%   |
| 5.16    | 66        | 4.3%    |
| 5.17    | 64        | 4.17%   |
| 5.18    | 60        | 3.91%   |
| 5.14    | 52        | 3.39%   |
| 5.12    | 38        | 2.47%   |
| 5.10    | 38        | 2.47%   |
| 5.11    | 37        | 2.41%   |
| 5.9     | 35        | 2.28%   |
| 5.13    | 35        | 2.28%   |
| 6.7     | 30        | 1.95%   |
| 5.8     | 24        | 1.56%   |
| 5.7     | 21        | 1.37%   |
| 5.4     | 7         | 0.46%   |
| 5.6     | 5         | 0.33%   |
| 5.5     | 2         | 0.13%   |
| 4.19    | 2         | 0.13%   |
| 5.2     | 1         | 0.07%   |
| 5.17.1  | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1355      | 99.93%  |
| aarch64 | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 563       | 40.01%  |
| GNOME           | 291       | 20.68%  |
| XFCE            | 240       | 17.06%  |
| i3              | 59        | 4.19%   |
| X-Cinnamon      | 49        | 3.48%   |
| Budgie          | 33        | 2.35%   |
| KDE             | 28        | 1.99%   |
| Unknown         | 27        | 1.92%   |
| Hyprland        | 19        | 1.35%   |
| Cinnamon        | 19        | 1.35%   |
| sway            | 17        | 1.21%   |
| MATE            | 15        | 1.07%   |
| LXQt            | 10        | 0.71%   |
| Deepin          | 6         | 0.43%   |
| bspwm           | 5         | 0.36%   |
| openbox         | 4         | 0.28%   |
| LXDE            | 4         | 0.28%   |
| GNOME Flashback | 4         | 0.28%   |
| awesome         | 4         | 0.28%   |
| qtile           | 3         | 0.21%   |
| xmonad          | 1         | 0.07%   |
| LeftWM          | 1         | 0.07%   |
| jwm             | 1         | 0.07%   |
| herbstluftwm    | 1         | 0.07%   |
| GNOME Classic   | 1         | 0.07%   |
| dwm             | 1         | 0.07%   |
| chadwm          | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1005      | 72.09%  |
| Wayland | 318       | 22.81%  |
| Tty     | 47        | 3.37%   |
| Unknown | 23        | 1.65%   |
| Web     | 1         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 426       | 30.45%  |
| SDDM    | 381       | 27.23%  |
| Unknown | 367       | 26.23%  |
| GDM     | 167       | 11.94%  |
| TDM     | 48        | 3.43%   |
| LY-DM   | 5         | 0.36%   |
| GREETD  | 3         | 0.21%   |
| LXDM    | 1         | 0.07%   |
| LEMURS  | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 671       | 49.05%  |
| en_GB   | 99        | 7.24%   |
| it_IT   | 98        | 7.16%   |
| de_DE   | 84        | 6.14%   |
| en_CA   | 56        | 4.09%   |
| ru_RU   | 35        | 2.56%   |
| fr_FR   | 31        | 2.27%   |
| en_IN   | 31        | 2.27%   |
| es_ES   | 21        | 1.54%   |
| en_AU   | 21        | 1.54%   |
| Unknown | 18        | 1.32%   |
| pl_PL   | 17        | 1.24%   |
| pt_BR   | 15        | 1.1%    |
| nl_NL   | 11        | 0.8%    |
| de_AT   | 11        | 0.8%    |
| tr_TR   | 10        | 0.73%   |
| sv_SE   | 10        | 0.73%   |
| es_MX   | 10        | 0.73%   |
| fi_FI   | 9         | 0.66%   |
| es_AR   | 9         | 0.66%   |
| en_DK   | 8         | 0.58%   |
| en_NZ   | 6         | 0.44%   |
| en_AG   | 6         | 0.44%   |
| pt_PT   | 5         | 0.37%   |
| nl_BE   | 5         | 0.37%   |
| en_ZA   | 5         | 0.37%   |
| en_PH   | 5         | 0.37%   |
| en_HK   | 5         | 0.37%   |
| de_CH   | 4         | 0.29%   |
| cs_CZ   | 4         | 0.29%   |
| zh_CN   | 3         | 0.22%   |
| hu_HU   | 3         | 0.22%   |
| es_CL   | 3         | 0.22%   |
| en_SG   | 3         | 0.22%   |
| zh_TW   | 2         | 0.15%   |
| ru_UA   | 2         | 0.15%   |
| es_CO   | 2         | 0.15%   |
| en_IL   | 2         | 0.15%   |
| da_DK   | 2         | 0.15%   |
| C       | 2         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 877       | 63.78%  |
| BIOS | 498       | 36.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 955       | 69.71%  |
| Btrfs   | 348       | 25.4%   |
| Overlay | 31        | 2.26%   |
| Xfs     | 14        | 1.02%   |
| Tmpfs   | 13        | 0.95%   |
| F2fs    | 3         | 0.22%   |
| Unknown | 3         | 0.22%   |
| Zfs     | 1         | 0.07%   |
| XXX4    | 1         | 0.07%   |
| Ext2    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 918       | 66.91%  |
| Unknown | 363       | 26.46%  |
| MBR     | 91        | 6.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1171      | 85.47%  |
| Yes       | 199       | 14.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 928       | 67.05%  |
| Yes       | 456       | 32.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 274       | 20.21%  |
| Lenovo                  | 259       | 19.1%   |
| Hewlett-Packard         | 171       | 12.61%  |
| MSI                     | 127       | 9.37%   |
| Dell                    | 119       | 8.78%   |
| Gigabyte Technology     | 95        | 7.01%   |
| Acer                    | 61        | 4.5%    |
| ASRock                  | 37        | 2.73%   |
| Apple                   | 33        | 2.43%   |
| HUAWEI                  | 15        | 1.11%   |
| Microsoft               | 12        | 0.88%   |
| Google                  | 12        | 0.88%   |
| Timi                    | 11        | 0.81%   |
| Samsung Electronics     | 11        | 0.81%   |
| Unknown                 | 11        | 0.81%   |
| Toshiba                 | 9         | 0.66%   |
| TUXEDO                  | 7         | 0.52%   |
| Notebook                | 7         | 0.52%   |
| Sony                    | 5         | 0.37%   |
| Intel                   | 5         | 0.37%   |
| Fujitsu                 | 5         | 0.37%   |
| Schenker                | 4         | 0.29%   |
| Positivo                | 4         | 0.29%   |
| ZOTAC                   | 3         | 0.22%   |
| Packard Bell            | 3         | 0.22%   |
| Huanan                  | 3         | 0.22%   |
| GPD                     | 3         | 0.22%   |
| Biostar                 | 3         | 0.22%   |
| AZW                     | 3         | 0.22%   |
| TrekStor                | 2         | 0.15%   |
| System76                | 2         | 0.15%   |
| Razer                   | 2         | 0.15%   |
| Medion                  | 2         | 0.15%   |
| Framework               | 2         | 0.15%   |
| Chuwi                   | 2         | 0.15%   |
| BESSTAR Tech            | 2         | 0.15%   |
| AMI                     | 2         | 0.15%   |
| Alienware               | 2         | 0.15%   |
| VIT                     | 1         | 0.07%   |
| Universal Exports Group | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7C37                           | 12        | 0.88%   |
| Unknown                               | 12        | 0.88%   |
| ASUS TUF Gaming X570-PLUS             | 11        | 0.81%   |
| ASUS All Series                       | 10        | 0.74%   |
| Apple MacBookAir7,2                   | 7         | 0.52%   |
| MSI MS-7A38                           | 6         | 0.44%   |
| Gigabyte B550 AORUS ELITE V2          | 6         | 0.44%   |
| MSI MS-7C02                           | 5         | 0.37%   |
| Microsoft Surface Laptop Go           | 5         | 0.37%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 5         | 0.37%   |
| Gigabyte B450M DS3H                   | 5         | 0.37%   |
| Gigabyte B450 AORUS ELITE             | 5         | 0.37%   |
| ASUS ROG STRIX X570-E GAMING          | 5         | 0.37%   |
| MSI MS-7C91                           | 4         | 0.29%   |
| MSI MS-7C56                           | 4         | 0.29%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 4         | 0.29%   |
| ASUS PRIME X570-P                     | 4         | 0.29%   |
| ASRock B450M Pro4                     | 4         | 0.29%   |
| ASRock B450 Pro4                      | 4         | 0.29%   |
| MSI MS-7C84                           | 3         | 0.22%   |
| MSI MS-7C52                           | 3         | 0.22%   |
| MSI MS-7B86                           | 3         | 0.22%   |
| MSI MS-7B79                           | 3         | 0.22%   |
| MSI Modern 14 B5M                     | 3         | 0.22%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.22%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 3         | 0.22%   |
| Lenovo Legion 5 15ACH6H 82JU          | 3         | 0.22%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5      | 3         | 0.22%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 3         | 0.22%   |
| HUAWEI KLVL-WXX9                      | 3         | 0.22%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 3         | 0.22%   |
| HP Laptop 15-db0xxx                   | 3         | 0.22%   |
| Gigabyte X670 AORUS ELITE AX          | 3         | 0.22%   |
| Gigabyte B550M AORUS PRO              | 3         | 0.22%   |
| Dell XPS 15 9520                      | 3         | 0.22%   |
| Dell OptiPlex 7010                    | 3         | 0.22%   |
| Dell Latitude E5470                   | 3         | 0.22%   |
| Dell Inspiron 3583                    | 3         | 0.22%   |
| Dell Inspiron 3542                    | 3         | 0.22%   |
| ASUS TUF Gaming B550-PLUS             | 3         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 113       | 8.33%   |
| ASUS ROG           | 67        | 4.94%   |
| Lenovo IdeaPad     | 61        | 4.5%    |
| ASUS TUF           | 37        | 2.73%   |
| Acer Aspire        | 35        | 2.58%   |
| HP Pavilion        | 34        | 2.51%   |
| Dell Inspiron      | 32        | 2.36%   |
| Dell Latitude      | 31        | 2.29%   |
| ASUS PRIME         | 31        | 2.29%   |
| HP EliteBook       | 25        | 1.84%   |
| ASUS VivoBook      | 24        | 1.77%   |
| Lenovo Yoga        | 22        | 1.62%   |
| Lenovo Legion      | 22        | 1.62%   |
| HP Laptop          | 17        | 1.25%   |
| Dell OptiPlex      | 15        | 1.11%   |
| Dell XPS           | 14        | 1.03%   |
| ASUS ASUS          | 14        | 1.03%   |
| Lenovo ThinkBook   | 13        | 0.96%   |
| HP ENVY            | 13        | 0.96%   |
| MSI MS-7C37        | 12        | 0.88%   |
| Microsoft Surface  | 12        | 0.88%   |
| ASUS ZenBook       | 12        | 0.88%   |
| Unknown            | 12        | 0.88%   |
| Gigabyte B550      | 10        | 0.74%   |
| Dell Precision     | 10        | 0.74%   |
| ASUS All           | 10        | 0.74%   |
| MSI Modern         | 9         | 0.66%   |
| HP ProBook         | 9         | 0.66%   |
| Gigabyte B450      | 8         | 0.59%   |
| Acer Swift         | 8         | 0.59%   |
| Acer Nitro         | 8         | 0.59%   |
| Toshiba Satellite  | 7         | 0.52%   |
| HP ZBook           | 7         | 0.52%   |
| HP 255             | 7         | 0.52%   |
| Gigabyte X570      | 7         | 0.52%   |
| Gigabyte B450M     | 7         | 0.52%   |
| ASRock B450        | 7         | 0.52%   |
| Apple MacBookAir7  | 7         | 0.52%   |
| MSI MS-7A38        | 6         | 0.44%   |
| Lenovo IdeaPadFlex | 6         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 187       | 13.79%  |
| 2021    | 179       | 13.2%   |
| 2019    | 170       | 12.54%  |
| 2018    | 153       | 11.28%  |
| 2022    | 125       | 9.22%   |
| 2017    | 92        | 6.78%   |
| 2016    | 68        | 5.01%   |
| 2013    | 65        | 4.79%   |
| 2012    | 62        | 4.57%   |
| 2015    | 56        | 4.13%   |
| 2014    | 53        | 3.91%   |
| 2023    | 44        | 3.24%   |
| 2011    | 30        | 2.21%   |
| 2010    | 20        | 1.47%   |
| 2009    | 18        | 1.33%   |
| 2008    | 18        | 1.33%   |
| 2007    | 15        | 1.11%   |
| Unknown | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 790       | 58.26%  |
| Desktop     | 450       | 33.19%  |
| Convertible | 60        | 4.42%   |
| All in one  | 21        | 1.55%   |
| Tablet      | 19        | 1.4%    |
| Mini pc     | 15        | 1.11%   |
| Server      | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1347      | 99.26%  |
| Enabled  | 10        | 0.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1340      | 98.82%  |
| Yes  | 16        | 1.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 344       | 25.11%  |
| 8.01-16.0   | 293       | 21.39%  |
| 4.01-8.0    | 262       | 19.12%  |
| 32.01-64.0  | 252       | 18.39%  |
| 3.01-4.0    | 103       | 7.52%   |
| 24.01-32.0  | 52        | 3.8%    |
| 64.01-256.0 | 51        | 3.72%   |
| 1.01-2.0    | 9         | 0.66%   |
| 2.01-3.0    | 3         | 0.22%   |
| Unknown     | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 400       | 26.92%  |
| 2.01-3.0   | 350       | 23.55%  |
| 1.01-2.0   | 277       | 18.64%  |
| 3.01-4.0   | 269       | 18.1%   |
| 8.01-16.0  | 131       | 8.82%   |
| 0.51-1.0   | 33        | 2.22%   |
| 16.01-24.0 | 18        | 1.21%   |
| 24.01-32.0 | 5         | 0.34%   |
| 0.01-0.5   | 2         | 0.13%   |
| Unknown    | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 723       | 51.72%  |
| 2      | 371       | 26.54%  |
| 3      | 139       | 9.94%   |
| 4      | 89        | 6.37%   |
| 5      | 37        | 2.65%   |
| 6      | 23        | 1.65%   |
| 7      | 5         | 0.36%   |
| 0      | 5         | 0.36%   |
| 9      | 3         | 0.21%   |
| 8      | 2         | 0.14%   |
| 10     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1116      | 82%     |
| Yes       | 245       | 18%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1093      | 80.19%  |
| No        | 270       | 19.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1148      | 84.29%  |
| No        | 214       | 15.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1085      | 79.31%  |
| No        | 283       | 20.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 296       | 21.59%  |
| Germany     | 134       | 9.77%   |
| Italy       | 132       | 9.63%   |
| Canada      | 62        | 4.52%   |
| France      | 51        | 3.72%   |
| UK          | 41        | 2.99%   |
| Russia      | 41        | 2.99%   |
| India       | 41        | 2.99%   |
| Poland      | 38        | 2.77%   |
| Netherlands | 37        | 2.7%    |
| Brazil      | 30        | 2.19%   |
| Spain       | 29        | 2.12%   |
| Turkey      | 28        | 2.04%   |
| Sweden      | 26        | 1.9%    |
| Austria     | 25        | 1.82%   |
| Australia   | 23        | 1.68%   |
| Finland     | 22        | 1.6%    |
| Mexico      | 19        | 1.39%   |
| Belgium     | 18        | 1.31%   |
| Switzerland | 13        | 0.95%   |
| Indonesia   | 12        | 0.88%   |
| Hungary     | 12        | 0.88%   |
| Argentina   | 12        | 0.88%   |
| Romania     | 9         | 0.66%   |
| Denmark     | 9         | 0.66%   |
| Vietnam     | 8         | 0.58%   |
| Portugal    | 8         | 0.58%   |
| Hong Kong   | 8         | 0.58%   |
| Czechia     | 8         | 0.58%   |
| Serbia      | 7         | 0.51%   |
| New Zealand | 7         | 0.51%   |
| Bangladesh  | 7         | 0.51%   |
| Ukraine     | 6         | 0.44%   |
| Taiwan      | 6         | 0.44%   |
| Slovakia    | 6         | 0.44%   |
| Norway      | 6         | 0.44%   |
| Malaysia    | 6         | 0.44%   |
| Greece      | 6         | 0.44%   |
| Colombia    | 6         | 0.44%   |
| Chile       | 6         | 0.44%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Milan             | 17        | 1.17%   |
| Montreal          | 16        | 1.11%   |
| Berlin            | 16        | 1.11%   |
| St Petersburg     | 12        | 0.83%   |
| Helsinki          | 12        | 0.83%   |
| Amsterdam         | 12        | 0.83%   |
| Istanbul          | 11        | 0.76%   |
| Rome              | 10        | 0.69%   |
| Hamburg           | 10        | 0.69%   |
| Frankfurt am Main | 10        | 0.69%   |
| Warsaw            | 9         | 0.62%   |
| Vienna            | 8         | 0.55%   |
| Sydney            | 8         | 0.55%   |
| Paris             | 8         | 0.55%   |
| Melbourne         | 8         | 0.55%   |
| Hyderabad         | 8         | 0.55%   |
| Turin             | 7         | 0.48%   |
| Toms River        | 7         | 0.48%   |
| Moscow            | 7         | 0.48%   |
| Belgrade          | 7         | 0.48%   |
| Victoria          | 6         | 0.41%   |
| Toronto           | 6         | 0.41%   |
| Mesa              | 6         | 0.41%   |
| Madrid            | 6         | 0.41%   |
| Budapest          | 6         | 0.41%   |
| Wroclaw           | 5         | 0.35%   |
| Seattle           | 5         | 0.35%   |
| Portland          | 5         | 0.35%   |
| Ottawa            | 5         | 0.35%   |
| Naples            | 5         | 0.35%   |
| Los Angeles       | 5         | 0.35%   |
| Jacksonville      | 5         | 0.35%   |
| Houston           | 5         | 0.35%   |
| Florence          | 5         | 0.35%   |
| Delhi             | 5         | 0.35%   |
| Cologne           | 5         | 0.35%   |
| Bengaluru         | 5         | 0.35%   |
| Barberton         | 5         | 0.35%   |
| Zurich            | 4         | 0.28%   |
| Zirl              | 4         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 459       | 710    | 20.36%  |
| Seagate                     | 254       | 356    | 11.27%  |
| WDC                         | 242       | 367    | 10.74%  |
| Sandisk                     | 164       | 203    | 7.28%   |
| Kingston                    | 134       | 189    | 5.94%   |
| Crucial                     | 92        | 133    | 4.08%   |
| Toshiba                     | 88        | 105    | 3.9%    |
| SK hynix                    | 84        | 105    | 3.73%   |
| Intel                       | 59        | 74     | 2.62%   |
| Micron Technology           | 57        | 67     | 2.53%   |
| Unknown                     | 53        | 72     | 2.35%   |
| Phison Electronics          | 37        | 43     | 1.64%   |
| KIOXIA                      | 32        | 33     | 1.42%   |
| HGST                        | 32        | 41     | 1.42%   |
| Hitachi                     | 31        | 36     | 1.38%   |
| Micron/Crucial Technology   | 26        | 38     | 1.15%   |
| Apple                       | 26        | 35     | 1.15%   |
| Kingston Technology Company | 25        | 28     | 1.11%   |
| A-DATA Technology           | 25        | 36     | 1.11%   |
| Phison                      | 21        | 22     | 0.93%   |
| China                       | 18        | 18     | 0.8%    |
| SPCC                        | 12        | 13     | 0.53%   |
| Silicon Motion              | 11        | 11     | 0.49%   |
| Patriot                     | 11        | 14     | 0.49%   |
| Corsair                     | 11        | 11     | 0.49%   |
| MAXIO Technology (Hangzhou) | 10        | 10     | 0.44%   |
| PNY                         | 9         | 10     | 0.4%    |
| Intenso                     | 9         | 11     | 0.4%    |
| ADATA Technology            | 9         | 9      | 0.4%    |
| OCZ                         | 8         | 8      | 0.35%   |
| LITEONIT                    | 8         | 9      | 0.35%   |
| Transcend                   | 7         | 8      | 0.31%   |
| JMicron Technology          | 7         | 8      | 0.31%   |
| Gigabyte Technology         | 7         | 9      | 0.31%   |
| Realtek Semiconductor       | 6         | 6      | 0.27%   |
| XPG                         | 5         | 5      | 0.22%   |
| Union Memory (Shenzhen)     | 5         | 5      | 0.22%   |
| SABRENT                     | 5         | 7      | 0.22%   |
| Realtek                     | 5         | 9      | 0.22%   |
| Mushkin                     | 5         | 5      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 83        | 3.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 42        | 1.67%   |
| Seagate ST2000DM008-2FR102 2TB                        | 31        | 1.23%   |
| Kingston SA400S37240G 240GB SSD                       | 27        | 1.07%   |
| Samsung SSD 860 EVO 500GB                             | 23        | 0.91%   |
| Samsung SSD 860 EVO 1TB                               | 23        | 0.91%   |
| Crucial CT500MX500SSD1 500GB                          | 22        | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB                        | 21        | 0.83%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 20        | 0.79%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 20        | 0.79%   |
| Samsung SSD 850 EVO 250GB                             | 18        | 0.71%   |
| Samsung SSD 870 QVO 1TB                               | 17        | 0.68%   |
| Kingston SA400S37480G 480GB SSD                       | 17        | 0.68%   |
| Samsung SSD 850 EVO 500GB                             | 16        | 0.64%   |
| Samsung SSD 980 1TB                                   | 15        | 0.6%    |
| Samsung SSD 860 EVO 250GB                             | 15        | 0.6%    |
| Kingston SA400S37120G 120GB SSD                       | 15        | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB                              | 14        | 0.56%   |
| Seagate ST4000DM004-2CV104 4TB                        | 13        | 0.52%   |
| Phison E12 NVMe Controller 1TB                        | 13        | 0.52%   |
| HGST HTS721010A9E630 1TB                              | 13        | 0.52%   |
| Crucial CT240BX500SSD1 240GB                          | 13        | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB                        | 12        | 0.48%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 12        | 0.48%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 11        | 0.44%   |
| Samsung SSD 870 EVO 1TB                               | 11        | 0.44%   |
| Phison E16 PCIe4 NVMe Controller 2TB                  | 11        | 0.44%   |
| Toshiba MQ01ABD100 1TB                                | 10        | 0.4%    |
| Samsung SSD 980 500GB                                 | 10        | 0.4%    |
| Intel SSD 660P Series 1024GB                          | 10        | 0.4%    |
| Crucial CT1000MX500SSD1 1TB                           | 10        | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 9         | 0.36%   |
| Unknown MMC Card  128GB                               | 9         | 0.36%   |
| Seagate ST500LT012-1DG142 500GB                       | 9         | 0.36%   |
| Samsung SSD 970 EVO 500GB                             | 9         | 0.36%   |
| Unknown SD/MMC/MS PRO 256GB                           | 8         | 0.32%   |
| Unknown MMC Card  64GB                                | 8         | 0.32%   |
| Toshiba DT01ACA100 1TB                                | 8         | 0.32%   |
| Seagate ST2000DM006-2DM164 2TB                        | 8         | 0.32%   |
| Seagate ST1000LM049-2GH172 1TB                        | 8         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 243       | 339    | 41.19%  |
| WDC                 | 177       | 258    | 30%     |
| Toshiba             | 56        | 63     | 9.49%   |
| HGST                | 32        | 41     | 5.42%   |
| Hitachi             | 31        | 36     | 5.25%   |
| Samsung Electronics | 14        | 36     | 2.37%   |
| Unknown             | 8         | 8      | 1.36%   |
| Maxtor              | 4         | 5      | 0.68%   |
| Apple               | 4         | 4      | 0.68%   |
| Maxone              | 3         | 3      | 0.51%   |
| Fujitsu             | 3         | 3      | 0.51%   |
| ASMT                | 3         | 6      | 0.51%   |
| StoreJet            | 2         | 2      | 0.34%   |
| JMicron Technology  | 2         | 2      | 0.34%   |
| RSH-319             | 1         | 2      | 0.17%   |
| PI-041              | 1         | 1      | 0.17%   |
| MaxDigital          | 1         | 2      | 0.17%   |
| Intenso             | 1         | 1      | 0.17%   |
| HPE                 | 1         | 1      | 0.17%   |
| Generic-            | 1         | 1      | 0.17%   |
| Fantom              | 1         | 3      | 0.17%   |
| Unknown             | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 217       | 306    | 28.18%  |
| Kingston            | 92        | 131    | 11.95%  |
| Crucial             | 84        | 116    | 10.91%  |
| SanDisk             | 54        | 61     | 7.01%   |
| WDC                 | 53        | 67     | 6.88%   |
| SK hynix            | 18        | 24     | 2.34%   |
| China               | 18        | 18     | 2.34%   |
| A-DATA Technology   | 18        | 22     | 2.34%   |
| Intel               | 15        | 19     | 1.95%   |
| Apple               | 14        | 18     | 1.82%   |
| Micron Technology   | 13        | 17     | 1.69%   |
| Toshiba             | 11        | 13     | 1.43%   |
| Patriot             | 11        | 14     | 1.43%   |
| SPCC                | 10        | 11     | 1.3%    |
| OCZ                 | 8         | 8      | 1.04%   |
| LITEONIT            | 8         | 9      | 1.04%   |
| Intenso             | 7         | 9      | 0.91%   |
| Corsair             | 7         | 7      | 0.91%   |
| Transcend           | 6         | 6      | 0.78%   |
| Seagate             | 6         | 9      | 0.78%   |
| PNY                 | 6         | 7      | 0.78%   |
| Gigabyte Technology | 6         | 7      | 0.78%   |
| SABRENT             | 5         | 7      | 0.65%   |
| Mushkin             | 4         | 4      | 0.52%   |
| LITEON              | 4         | 5      | 0.52%   |
| KingSpec            | 4         | 4      | 0.52%   |
| GOODRAM             | 4         | 4      | 0.52%   |
| Netac               | 3         | 4      | 0.39%   |
| KingFast            | 3         | 3      | 0.39%   |
| Hewlett-Packard     | 3         | 3      | 0.39%   |
| Emtec               | 3         | 3      | 0.39%   |
| WDC WDS             | 2         | 2      | 0.26%   |
| Teclast             | 2         | 4      | 0.26%   |
| Team                | 2         | 3      | 0.26%   |
| Plextor             | 2         | 3      | 0.26%   |
| Phison              | 2         | 2      | 0.26%   |
| Leven               | 2         | 3      | 0.26%   |
| HS-SSD-C100         | 2         | 2      | 0.26%   |
| Apacer              | 2         | 2      | 0.26%   |
| Unknown             | 2         | 2      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 792       | 1140   | 40.59%  |
| SSD     | 606       | 1015   | 31.06%  |
| HDD     | 483       | 818    | 24.76%  |
| MMC     | 41        | 52     | 2.1%    |
| Unknown | 29        | 41     | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 802       | 1715   | 45.75%  |
| NVMe | 791       | 1127   | 45.12%  |
| SAS  | 119       | 172    | 6.79%   |
| MMC  | 41        | 52     | 2.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 575       | 986    | 49.06%  |
| 0.51-1.0   | 370       | 525    | 31.57%  |
| 1.01-2.0   | 125       | 190    | 10.67%  |
| 3.01-4.0   | 48        | 67     | 4.1%    |
| 4.01-10.0  | 27        | 36     | 2.3%    |
| 2.01-3.0   | 21        | 23     | 1.79%   |
| 10.01-20.0 | 6         | 6      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 275       | 19.34%  |
| 251-500        | 254       | 17.86%  |
| 1001-2000      | 228       | 16.03%  |
| 501-1000       | 216       | 15.19%  |
| More than 3000 | 141       | 9.92%   |
| 1-20           | 80        | 5.63%   |
| Unknown        | 80        | 5.63%   |
| 2001-3000      | 76        | 5.34%   |
| 51-100         | 48        | 3.38%   |
| 21-50          | 24        | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 323       | 21.72%  |
| 101-250        | 230       | 15.47%  |
| 21-50          | 217       | 14.59%  |
| 51-100         | 186       | 12.51%  |
| 251-500        | 148       | 9.95%   |
| 501-1000       | 124       | 8.34%   |
| 1001-2000      | 100       | 6.72%   |
| Unknown        | 80        | 5.38%   |
| More than 3000 | 45        | 3.03%   |
| 2001-3000      | 28        | 1.88%   |
| 0              | 6         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB       | 6         | 11     | 4.32%   |
| HGST HTS721010A9E630 1TB         | 4         | 4      | 2.88%   |
| Seagate ST500LT012-1DG142 500GB  | 3         | 3      | 2.16%   |
| Hitachi HTS545050A7E380 500GB    | 3         | 3      | 2.16%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2         | 2      | 1.44%   |
| WDC WD20EARX-00PASB0 2TB         | 2         | 2      | 1.44%   |
| Toshiba MQ01ABD100 1TB           | 2         | 2      | 1.44%   |
| Seagate ST9320325AS 320GB        | 2         | 5      | 1.44%   |
| Seagate ST500LM021-1KJ152 500GB  | 2         | 8      | 1.44%   |
| Seagate ST4000DM004-2CV104 4TB   | 2         | 2      | 1.44%   |
| Seagate ST1000LM035-1RK172 1TB   | 2         | 2      | 1.44%   |
| Samsung Electronics SSD 980 1TB  | 2         | 2      | 1.44%   |
| Samsung Electronics HD103SI 1TB  | 2         | 3      | 1.44%   |
| Crucial CT1050MX300SSD1 1050GB   | 2         | 2      | 1.44%   |
| Corsair Force LS SSD 120GB       | 2         | 2      | 1.44%   |
| ZEB-SD26 SSD 256G                | 1         | 1      | 0.72%   |
| XPG GAMMIX S11 240GB             | 1         | 1      | 0.72%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 1      | 0.72%   |
| WDC WD6400AAKS-00A7B2 640GB      | 1         | 1      | 0.72%   |
| WDC WD5000LPVT-22G33T0 500GB     | 1         | 1      | 0.72%   |
| WDC WD5000BPVT-60HXZT3 500GB     | 1         | 1      | 0.72%   |
| WDC WD5000AZRX-00A8LB0 500GB     | 1         | 1      | 0.72%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1         | 1      | 0.72%   |
| WDC WD5000AADS-00L4B1 500GB      | 1         | 1      | 0.72%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1         | 2      | 0.72%   |
| WDC WD2500AAJS-75M0A0 249GB      | 1         | 1      | 0.72%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1         | 2      | 0.72%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1         | 1      | 0.72%   |
| WDC WD2002FYPS-01U1B0 2TB        | 1         | 1      | 0.72%   |
| WDC WD2000FYYZ-01UL1B2 2TB       | 1         | 1      | 0.72%   |
| WDC WD15EARS-00Z5B1 1TB          | 1         | 1      | 0.72%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 1      | 0.72%   |
| WDC WD10SPCX-22HWST0 1TB         | 1         | 1      | 0.72%   |
| WDC WD10JPVX-22JC3T0 1TB         | 1         | 1      | 0.72%   |
| WDC WD10EZRX-00D8PB0 1TB         | 1         | 1      | 0.72%   |
| WDC WD10EARS-00MVWB0 1TB         | 1         | 1      | 0.72%   |
| WDC WD10EACS-00D6B1 1TB          | 1         | 1      | 0.72%   |
| WDC WD1003FBYZ-010FB0 1TB        | 1         | 2      | 0.72%   |
| WDC WD1002FBYS-02A6B0 1TB        | 1         | 1      | 0.72%   |
| WDC WD Blue SA510 2.5 1TB        | 1         | 2      | 0.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 32     | 19.85%  |
| Seagate             | 27        | 40     | 19.85%  |
| Samsung Electronics | 12        | 18     | 8.82%   |
| Toshiba             | 11        | 13     | 8.09%   |
| HGST                | 11        | 16     | 8.09%   |
| SK hynix            | 6         | 6      | 4.41%   |
| SanDisk             | 5         | 6      | 3.68%   |
| Hitachi             | 5         | 5      | 3.68%   |
| Crucial             | 5         | 15     | 3.68%   |
| Kingston            | 3         | 3      | 2.21%   |
| Intel               | 3         | 3      | 2.21%   |
| Patriot             | 2         | 2      | 1.47%   |
| Corsair             | 2         | 2      | 1.47%   |
| China               | 2         | 2      | 1.47%   |
| Apple               | 2         | 2      | 1.47%   |
| ZEB-SD26            | 1         | 1      | 0.74%   |
| XPG                 | 1         | 1      | 0.74%   |
| Transcend           | 1         | 1      | 0.74%   |
| SSSTC               | 1         | 1      | 0.74%   |
| OCZ                 | 1         | 1      | 0.74%   |
| Micron Technology   | 1         | 1      | 0.74%   |
| Maxtor              | 1         | 2      | 0.74%   |
| LITEONIT            | 1         | 1      | 0.74%   |
| Fujitsu             | 1         | 1      | 0.74%   |
| Drevo               | 1         | 1      | 0.74%   |
| ASMT                | 1         | 2      | 0.74%   |
| Actseno             | 1         | 1      | 0.74%   |
| A-DATA Technology   | 1         | 1      | 0.74%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 40     | 34.18%  |
| WDC                 | 23        | 26     | 29.11%  |
| HGST                | 11        | 16     | 13.92%  |
| Toshiba             | 8         | 10     | 10.13%  |
| Hitachi             | 5         | 5      | 6.33%   |
| Samsung Electronics | 2         | 3      | 2.53%   |
| Maxtor              | 1         | 2      | 1.27%   |
| Fujitsu             | 1         | 1      | 1.27%   |
| ASMT                | 1         | 2      | 1.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 75        | 105    | 57.69%  |
| SSD  | 46        | 61     | 35.38%  |
| NVMe | 9         | 14     | 6.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9320320AS 320GB                        | 1         | 1      | 20%     |
| Seagate ST500DM002-1BC142 500GB                  | 1         | 1      | 20%     |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB | 1         | 1      | 20%     |
| Samsung Electronics HD252HJ 250GB                | 1         | 1      | 20%     |
| LITEON CA3-8D512 512GB                           | 1         | 2      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 40%     |
| Sandisk             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| LITEON              | 1         | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 928       | 1867   | 60.53%  |
| Detected | 476       | 1013   | 31.05%  |
| Malfunc  | 124       | 180    | 8.09%   |
| Failed   | 5         | 6      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 704       | 35.57%  |
| AMD                            | 340       | 17.18%  |
| Samsung Electronics            | 293       | 14.81%  |
| SanDisk                        | 146       | 7.38%   |
| Kingston Technology Company    | 70        | 3.54%   |
| SK hynix                       | 65        | 3.28%   |
| Phison Electronics             | 64        | 3.23%   |
| Micron Technology              | 45        | 2.27%   |
| ASMedia Technology             | 39        | 1.97%   |
| Micron/Crucial Technology      | 34        | 1.72%   |
| KIOXIA                         | 34        | 1.72%   |
| Toshiba America Info Systems   | 21        | 1.06%   |
| ADATA Technology               | 16        | 0.81%   |
| Silicon Motion                 | 14        | 0.71%   |
| MAXIO Technology (Hangzhou)    | 11        | 0.56%   |
| Realtek Semiconductor          | 10        | 0.51%   |
| JMicron Technology             | 9         | 0.45%   |
| Solid State Storage Technology | 8         | 0.4%    |
| Nvidia                         | 8         | 0.4%    |
| Marvell Technology Group       | 8         | 0.4%    |
| Apple                          | 8         | 0.4%    |
| Union Memory (Shenzhen)        | 7         | 0.35%   |
| Seagate Technology             | 5         | 0.25%   |
| Shenzhen Longsys Electronics   | 4         | 0.2%    |
| Lenovo                         | 3         | 0.15%   |
| Yangtze Memory Technologies    | 2         | 0.1%    |
| Transcend                      | 2         | 0.1%    |
| Nextorage                      | 2         | 0.1%    |
| Lite-On Technology             | 2         | 0.1%    |
| VIA Technologies               | 1         | 0.05%   |
| LSI Logic / Symbios Logic      | 1         | 0.05%   |
| INNOGRIT                       | 1         | 0.05%   |
| Broadcom / LSI                 | 1         | 0.05%   |
| Biwin Storage Technology       | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 236       | 10.94%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 132       | 6.12%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 77        | 3.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 73        | 3.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 68        | 3.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 51        | 2.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 51        | 2.36%   |
| Intel Volume Management Device NVMe RAID Controller                            | 44        | 2.04%   |
| AMD 500 Series Chipset SATA Controller                                         | 44        | 2.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 42        | 1.95%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 38        | 1.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 37        | 1.72%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 33        | 1.53%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 32        | 1.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 30        | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 30        | 1.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 30        | 1.39%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 28        | 1.3%    |
| Phison E12 NVMe Controller                                                     | 26        | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 25        | 1.16%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 22        | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 22        | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 22        | 1.02%   |
| Intel SSD 660P Series                                                          | 20        | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                               | 19        | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                            | 19        | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 19        | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 17        | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 17        | 0.79%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 16        | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 16        | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 16        | 0.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 15        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 14        | 0.65%   |
| AMD 600 Series Chipset SATA Controller                                         | 14        | 0.65%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 13        | 0.6%    |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 13        | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 12        | 0.56%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 12        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 930       | 49.34%  |
| NVMe | 790       | 41.91%  |
| RAID | 114       | 6.05%   |
| IDE  | 45        | 2.39%   |
| SAS  | 6         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 864       | 63.67%  |
| AMD     | 491       | 36.18%  |
| ARM     | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 23        | 1.69%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 23        | 1.69%   |
| AMD Ryzen 5 3600 6-Core Processor             | 21        | 1.55%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 20        | 1.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 19        | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.25%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 1.25%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 16        | 1.18%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 15        | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 13        | 0.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 13        | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 0.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 0.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 13        | 0.96%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 0.96%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 12        | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 12        | 0.88%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 12        | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 11        | 0.81%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 11        | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.81%   |
| Intel 12th Gen Core i7-12700H                 | 11        | 0.81%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 11        | 0.81%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 11        | 0.81%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 10        | 0.74%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 10        | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 10        | 0.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 0.66%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 8         | 0.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 0.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 8         | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.59%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 8         | 0.59%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 8         | 0.59%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 8         | 0.59%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 8         | 0.59%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 8         | 0.59%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 286       | 21.08%  |
| Intel Core i7           | 249       | 18.35%  |
| AMD Ryzen 7             | 165       | 12.16%  |
| AMD Ryzen 5             | 165       | 12.16%  |
| Other                   | 159       | 11.72%  |
| AMD Ryzen 9             | 61        | 4.5%    |
| Intel Core i3           | 51        | 3.76%   |
| Intel Celeron           | 41        | 3.02%   |
| Intel Core 2 Duo        | 23        | 1.69%   |
| Intel Xeon              | 22        | 1.62%   |
| AMD Ryzen 7 PRO         | 21        | 1.55%   |
| AMD Ryzen 3             | 21        | 1.55%   |
| Intel Pentium           | 11        | 0.81%   |
| Intel Core i9           | 10        | 0.74%   |
| AMD A4                  | 8         | 0.59%   |
| AMD FX                  | 7         | 0.52%   |
| AMD Athlon              | 5         | 0.37%   |
| Intel Core m3           | 4         | 0.29%   |
| AMD Ryzen 5 PRO         | 4         | 0.29%   |
| AMD A8                  | 4         | 0.29%   |
| Intel Core 2 Quad       | 3         | 0.22%   |
| Intel Atom              | 3         | 0.22%   |
| AMD Ryzen Threadripper  | 3         | 0.22%   |
| AMD A10                 | 3         | 0.22%   |
| Intel Pentium Gold      | 2         | 0.15%   |
| Intel Pentium Dual-Core | 2         | 0.15%   |
| Intel Core 2            | 2         | 0.15%   |
| AMD E1                  | 2         | 0.15%   |
| AMD E                   | 2         | 0.15%   |
| AMD Athlon II X2        | 2         | 0.15%   |
| Intel Pentium Silver    | 1         | 0.07%   |
| Intel Pentium Dual      | 1         | 0.07%   |
| Intel Genuine           | 1         | 0.07%   |
| Intel Core m5           | 1         | 0.07%   |
| Intel Core M            | 1         | 0.07%   |
| Intel Core 2 Extreme    | 1         | 0.07%   |
| Intel Core              | 1         | 0.07%   |
| AMD PRO A10             | 1         | 0.07%   |
| AMD Phenom II X6        | 1         | 0.07%   |
| AMD Phenom II X4        | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 455       | 33.51%  |
| 2       | 319       | 23.49%  |
| 8       | 247       | 18.19%  |
| 6       | 212       | 15.61%  |
| 12      | 45        | 3.31%   |
| 14      | 28        | 2.06%   |
| 16      | 20        | 1.47%   |
| 10      | 19        | 1.4%    |
| 24      | 6         | 0.44%   |
| 3       | 3         | 0.22%   |
| 32      | 1         | 0.07%   |
| 5       | 1         | 0.07%   |
| 1       | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1350      | 99.41%  |
| 2       | 7         | 0.52%   |
| Unknown | 1         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1112      | 81.89%  |
| 1       | 245       | 18.04%  |
| Unknown | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1353      | 99.71%  |
| Unknown        | 3         | 0.22%   |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 664       | 47.6%   |
| 0x0a50000c | 44        | 3.15%   |
| 0x08701021 | 34        | 2.44%   |
| 0x306c3    | 32        | 2.29%   |
| 0x806ea    | 25        | 1.79%   |
| 0x306a9    | 25        | 1.79%   |
| 0x08108109 | 25        | 1.79%   |
| 0x406e3    | 22        | 1.58%   |
| 0x806e9    | 21        | 1.51%   |
| 0x08600106 | 21        | 1.51%   |
| 0x906ea    | 20        | 1.43%   |
| 0x506e3    | 19        | 1.36%   |
| 0x806ec    | 18        | 1.29%   |
| 0x806c1    | 18        | 1.29%   |
| 0x08608103 | 18        | 1.29%   |
| 0x40651    | 17        | 1.22%   |
| 0x0a50000d | 17        | 1.22%   |
| 0x08600104 | 17        | 1.22%   |
| 0x906e9    | 15        | 1.08%   |
| 0x0a404102 | 15        | 1.08%   |
| 0x706e5    | 12        | 0.86%   |
| 0x0a201016 | 12        | 0.86%   |
| 0x0a201009 | 12        | 0.86%   |
| 0x08108102 | 12        | 0.86%   |
| 0x906a3    | 11        | 0.79%   |
| 0x206a7    | 11        | 0.79%   |
| 0x0a20120a | 11        | 0.79%   |
| 0x08701013 | 11        | 0.79%   |
| 0x706a1    | 9         | 0.65%   |
| 0x306d4    | 9         | 0.65%   |
| 0x1067a    | 9         | 0.65%   |
| 0x0800820d | 8         | 0.57%   |
| 0xa0652    | 7         | 0.5%    |
| 0x406c4    | 7         | 0.5%    |
| 0x0a601203 | 7         | 0.5%    |
| 0x08001138 | 7         | 0.5%    |
| 0x806d1    | 6         | 0.43%   |
| 0x06006705 | 6         | 0.43%   |
| 0xa0655    | 5         | 0.36%   |
| 0x20655    | 5         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 248       | 18.26%  |
| Zen 3             | 147       | 10.82%  |
| Zen 2             | 127       | 9.35%   |
| Unknown           | 114       | 8.39%   |
| Haswell           | 104       | 7.66%   |
| Skylake           | 79        | 5.82%   |
| Zen+              | 64        | 4.71%   |
| IvyBridge         | 57        | 4.2%    |
| Alderlake Hybrid  | 57        | 4.2%    |
| TigerLake         | 51        | 3.76%   |
| CometLake         | 41        | 3.02%   |
| IceLake           | 40        | 2.95%   |
| SandyBridge       | 34        | 2.5%    |
| Zen               | 27        | 1.99%   |
| Broadwell         | 25        | 1.84%   |
| Penryn            | 24        | 1.77%   |
| Excavator         | 19        | 1.4%    |
| Goldmont plus     | 18        | 1.33%   |
| Silvermont        | 16        | 1.18%   |
| Westmere          | 14        | 1.03%   |
| Core              | 11        | 0.81%   |
| Piledriver        | 7         | 0.52%   |
| Nehalem           | 6         | 0.44%   |
| Jaguar            | 6         | 0.44%   |
| K10               | 5         | 0.37%   |
| Goldmont          | 4         | 0.29%   |
| Tremont           | 3         | 0.22%   |
| Bulldozer         | 3         | 0.22%   |
| Puma              | 2         | 0.15%   |
| Bobcat            | 2         | 0.15%   |
| Steamroller       | 1         | 0.07%   |
| Meteorlake Hybrid | 1         | 0.07%   |
| K10 Llano         | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 681       | 40.3%   |
| Nvidia | 529       | 31.3%   |
| AMD    | 480       | 28.4%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 58        | 3.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 55        | 3.15%   |
| Intel UHD Graphics 620                                                      | 50        | 2.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 49        | 2.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 44        | 2.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 38        | 2.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 36        | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 33        | 1.89%   |
| Intel HD Graphics 620                                                       | 31        | 1.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 31        | 1.78%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 31        | 1.78%   |
| AMD Rembrandt [Radeon 680M]                                                 | 29        | 1.66%   |
| AMD Lucienne                                                                | 28        | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 26        | 1.49%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 26        | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 24        | 1.38%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 24        | 1.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 23        | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 22        | 1.26%   |
| Intel HD Graphics 530                                                       | 22        | 1.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 21        | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 20        | 1.15%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 19        | 1.09%   |
| Intel HD Graphics 630                                                       | 19        | 1.09%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 19        | 1.09%   |
| AMD Barcelo                                                                 | 19        | 1.09%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 17        | 0.97%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 17        | 0.97%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 17        | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 16        | 0.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 16        | 0.92%   |
| Intel HD Graphics 5500                                                      | 16        | 0.92%   |
| Nvidia GP108M [GeForce MX150]                                               | 14        | 0.8%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 14        | 0.8%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 14        | 0.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 13        | 0.75%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 13        | 0.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 13        | 0.75%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 13        | 0.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 12        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 408       | 29.93%  |
| 1 x AMD                  | 343       | 25.17%  |
| 1 x Nvidia               | 235       | 17.24%  |
| Intel + Nvidia           | 225       | 16.51%  |
| AMD + Nvidia             | 63        | 4.62%   |
| 2 x AMD                  | 46        | 3.37%   |
| Intel + AMD              | 31        | 2.27%   |
| 2 x Intel                | 5         | 0.37%   |
| 2 x Nvidia               | 4         | 0.29%   |
| Other                    | 2         | 0.15%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 960       | 70.28%  |
| Proprietary | 404       | 29.58%  |
| Unknown     | 2         | 0.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 773       | 55.89%  |
| 0.01-0.5   | 135       | 9.76%   |
| 1.01-2.0   | 118       | 8.53%   |
| 7.01-8.0   | 102       | 7.38%   |
| 3.01-4.0   | 85        | 6.15%   |
| 8.01-16.0  | 62        | 4.48%   |
| 5.01-6.0   | 52        | 3.76%   |
| 0.51-1.0   | 39        | 2.82%   |
| 2.01-3.0   | 9         | 0.65%   |
| 16.01-24.0 | 8         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 190       | 11.26%  |
| Samsung Electronics     | 176       | 10.43%  |
| BOE                     | 166       | 9.83%   |
| Chimei Innolux          | 155       | 9.18%   |
| LG Display              | 125       | 7.41%   |
| Goldstar                | 92        | 5.45%   |
| Dell                    | 84        | 4.98%   |
| Acer                    | 60        | 3.55%   |
| AOC                     | 56        | 3.32%   |
| Ancor Communications    | 49        | 2.9%    |
| Hewlett-Packard         | 44        | 2.61%   |
| Lenovo                  | 43        | 2.55%   |
| BenQ                    | 41        | 2.43%   |
| ASUSTek Computer        | 36        | 2.13%   |
| PANDA                   | 33        | 1.95%   |
| Apple                   | 31        | 1.84%   |
| Sharp                   | 27        | 1.6%    |
| Philips                 | 22        | 1.3%    |
| ViewSonic               | 21        | 1.24%   |
| Iiyama                  | 18        | 1.07%   |
| Gigabyte Technology     | 15        | 0.89%   |
| InfoVision              | 14        | 0.83%   |
| TMX                     | 12        | 0.71%   |
| CSO                     | 12        | 0.71%   |
| Vizio                   | 9         | 0.53%   |
| Unknown                 | 8         | 0.47%   |
| MSI                     | 8         | 0.47%   |
| LG Electronics          | 8         | 0.47%   |
| Pixio                   | 6         | 0.36%   |
| Chi Mei Optoelectronics | 6         | 0.36%   |
| Toshiba                 | 5         | 0.3%    |
| Sony                    | 5         | 0.3%    |
| Fujitsu Siemens         | 5         | 0.3%    |
| Valve                   | 4         | 0.24%   |
| Sceptre Tech            | 4         | 0.24%   |
| JDI                     | 4         | 0.24%   |
| Eizo                    | 4         | 0.24%   |
| ___                     | 3         | 0.18%   |
| RTK                     | 3         | 0.18%   |
| Panasonic               | 3         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 10        | 0.57%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 9         | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.52%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 8         | 0.46%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.46%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 7         | 0.4%    |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                  | 7         | 0.4%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.4%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 7         | 0.4%    |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 6         | 0.34%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 6         | 0.34%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 6         | 0.34%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 5         | 0.29%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 5         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 5         | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.29%   |
| Pixio U29I WAM2900 2560x1080 690x260mm 29.0-inch                      | 5         | 0.29%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 5         | 0.29%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 5         | 0.29%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5         | 0.29%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 5         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 5         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 5         | 0.29%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 5         | 0.29%   |
| Valve Index HMD VLV91A8                                               | 4         | 0.23%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 4         | 0.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.23%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.23%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 0.23%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 0.23%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 0.23%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch              | 4         | 0.23%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch        | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 4         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 774       | 48.96%  |
| 1366x768 (WXGA)    | 169       | 10.69%  |
| 2560x1440 (QHD)    | 142       | 8.98%   |
| 3840x2160 (4K)     | 117       | 7.4%    |
| 2560x1600          | 49        | 3.1%    |
| 1920x1200 (WUXGA)  | 43        | 2.72%   |
| 1440x900 (WXGA+)   | 31        | 1.96%   |
| 3440x1440          | 26        | 1.64%   |
| 2560x1080          | 26        | 1.64%   |
| 1600x900 (HD+)     | 25        | 1.58%   |
| 1280x1024 (SXGA)   | 22        | 1.39%   |
| 2880x1800          | 19        | 1.2%    |
| 1680x1050 (WSXGA+) | 19        | 1.2%    |
| Unknown            | 16        | 1.01%   |
| 1280x800 (WXGA)    | 9         | 0.57%   |
| 3840x1080          | 8         | 0.51%   |
| 2736x1824          | 8         | 0.51%   |
| 3200x2000          | 7         | 0.44%   |
| 2160x1440          | 7         | 0.44%   |
| 3840x2400          | 6         | 0.38%   |
| 1360x768           | 6         | 0.38%   |
| 3200x1800 (QHD+)   | 4         | 0.25%   |
| 1920x540           | 4         | 0.25%   |
| 3456x2160          | 3         | 0.19%   |
| 3072x1920          | 3         | 0.19%   |
| 3000x2000          | 3         | 0.19%   |
| 2288x1287          | 3         | 0.19%   |
| 2240x1400          | 3         | 0.19%   |
| 1600x1200          | 3         | 0.19%   |
| 3840x1600          | 2         | 0.13%   |
| 2256x1504          | 2         | 0.13%   |
| 2160x1200          | 2         | 0.13%   |
| 1920x1280          | 2         | 0.13%   |
| 1800x1200          | 2         | 0.13%   |
| 1024x768 (XGA)     | 2         | 0.13%   |
| 9840x3840          | 1         | 0.06%   |
| 5760x1080          | 1         | 0.06%   |
| 4480x1440          | 1         | 0.06%   |
| 3840x2560          | 1         | 0.06%   |
| 3840x1440          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 371       | 21.89%  |
| 13      | 173       | 10.21%  |
| 27      | 170       | 10.03%  |
| 24      | 167       | 9.85%   |
| 14      | 154       | 9.09%   |
| 23      | 90        | 5.31%   |
| 21      | 76        | 4.48%   |
| 17      | 61        | 3.6%    |
| 31      | 59        | 3.48%   |
| 16      | 52        | 3.07%   |
| Unknown | 46        | 2.71%   |
| 34      | 45        | 2.65%   |
| 12      | 26        | 1.53%   |
| 19      | 24        | 1.42%   |
| 18      | 19        | 1.12%   |
| 22      | 16        | 0.94%   |
| 20      | 16        | 0.94%   |
| 11      | 14        | 0.83%   |
| 54      | 13        | 0.77%   |
| 40      | 10        | 0.59%   |
| 32      | 9         | 0.53%   |
| 84      | 8         | 0.47%   |
| 72      | 7         | 0.41%   |
| 29      | 6         | 0.35%   |
| 42      | 5         | 0.29%   |
| 28      | 5         | 0.29%   |
| 10      | 5         | 0.29%   |
| 49      | 4         | 0.24%   |
| 46      | 4         | 0.24%   |
| 35      | 4         | 0.24%   |
| 142     | 3         | 0.18%   |
| 74      | 3         | 0.18%   |
| 52      | 3         | 0.18%   |
| 37      | 3         | 0.18%   |
| 26      | 3         | 0.18%   |
| 25      | 3         | 0.18%   |
| 86      | 2         | 0.12%   |
| 69      | 2         | 0.12%   |
| 65      | 2         | 0.12%   |
| 58      | 2         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 653       | 40.14%  |
| 501-600        | 364       | 22.37%  |
| 201-300        | 134       | 8.24%   |
| 401-500        | 133       | 8.17%   |
| 601-700        | 81        | 4.98%   |
| 351-400        | 79        | 4.86%   |
| 701-800        | 57        | 3.5%    |
| Unknown        | 46        | 2.83%   |
| 1001-1500      | 33        | 2.03%   |
| 1501-2000      | 20        | 1.23%   |
| 801-900        | 18        | 1.11%   |
| 901-1000       | 5         | 0.31%   |
| More than 2000 | 3         | 0.18%   |
| 101-200        | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1091      | 75.55%  |
| 16/10   | 192       | 13.3%   |
| 21/9    | 51        | 3.53%   |
| Unknown | 35        | 2.42%   |
| 3/2     | 29        | 2.01%   |
| 5/4     | 17        | 1.18%   |
| 4/3     | 8         | 0.55%   |
| 32/9    | 5         | 0.35%   |
| 2.65    | 5         | 0.35%   |
| 6/5     | 4         | 0.28%   |
| 1.00    | 3         | 0.21%   |
| 0.56    | 2         | 0.14%   |
| 3.40    | 1         | 0.07%   |
| 0.62    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 372       | 22.29%  |
| 201-250        | 266       | 15.94%  |
| 81-90          | 255       | 15.28%  |
| 301-350        | 174       | 10.43%  |
| 351-500        | 117       | 7.01%   |
| 71-80          | 77        | 4.61%   |
| 151-200        | 58        | 3.48%   |
| 251-300        | 55        | 3.3%    |
| More than 1000 | 48        | 2.88%   |
| 121-130        | 47        | 2.82%   |
| 111-120        | 47        | 2.82%   |
| Unknown        | 46        | 2.76%   |
| 501-1000       | 31        | 1.86%   |
| 141-150        | 24        | 1.44%   |
| 61-70          | 16        | 0.96%   |
| 51-60          | 15        | 0.9%    |
| 131-140        | 11        | 0.66%   |
| 41-50          | 5         | 0.3%    |
| 91-100         | 4         | 0.24%   |
| 1-40           | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 527       | 33.14%  |
| 51-100        | 451       | 28.36%  |
| 101-120       | 310       | 19.5%   |
| 161-240       | 160       | 10.06%  |
| More than 240 | 55        | 3.46%   |
| Unknown       | 46        | 2.89%   |
| 1-50          | 41        | 2.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1034      | 74.5%   |
| 2     | 302       | 21.76%  |
| 3     | 44        | 3.17%   |
| 4     | 4         | 0.29%   |
| 0     | 4         | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 798       | 38.55%  |
| Intel                             | 764       | 36.91%  |
| Qualcomm Atheros                  | 145       | 7%      |
| MediaTek                          | 82        | 3.96%   |
| Broadcom                          | 58        | 2.8%    |
| ASIX Electronics                  | 22        | 1.06%   |
| TP-Link                           | 19        | 0.92%   |
| Microsoft                         | 17        | 0.82%   |
| Broadcom Limited                  | 16        | 0.77%   |
| D-Link                            | 14        | 0.68%   |
| DisplayLink                       | 10        | 0.48%   |
| Sierra Wireless                   | 8         | 0.39%   |
| Qualcomm                          | 8         | 0.39%   |
| Lenovo                            | 8         | 0.39%   |
| Ralink                            | 7         | 0.34%   |
| Aquantia                          | 7         | 0.34%   |
| Nvidia                            | 6         | 0.29%   |
| Cypress Semiconductor             | 6         | 0.29%   |
| Samsung Electronics               | 5         | 0.24%   |
| Ralink Technology                 | 5         | 0.24%   |
| Qualcomm Atheros Communications   | 5         | 0.24%   |
| OPPO Electronics                  | 5         | 0.24%   |
| Marvell Technology Group          | 5         | 0.24%   |
| Huawei Technologies               | 4         | 0.19%   |
| Hewlett-Packard                   | 4         | 0.19%   |
| Google                            | 4         | 0.19%   |
| Apple                             | 4         | 0.19%   |
| Xiaomi                            | 3         | 0.14%   |
| D-Link System                     | 3         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.1%    |
| Oculus VR                         | 2         | 0.1%    |
| NetGear                           | 2         | 0.1%    |
| Microchip Technology              | 2         | 0.1%    |
| Linksys                           | 2         | 0.1%    |
| ICS Advent                        | 2         | 0.1%    |
| Ericsson Business Mobile Networks | 2         | 0.1%    |
| Wilocity                          | 1         | 0.05%   |
| Tenda                             | 1         | 0.05%   |
| Quectel Wireless Solutions        | 1         | 0.05%   |
| Qualcomm Technologies             | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 538       | 21.82%  |
| Intel Wi-Fi 6 AX200                                                    | 115       | 4.66%   |
| Realtek RTL8125 2.5GbE Controller                                      | 82        | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 53        | 2.15%   |
| Intel Wireless 8265 / 8275                                             | 50        | 2.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 45        | 1.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 43        | 1.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 42        | 1.7%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 42        | 1.7%    |
| Intel I211 Gigabit Network Connection                                  | 42        | 1.7%    |
| Intel Wi-Fi 6 AX201                                                    | 37        | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 36        | 1.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 36        | 1.46%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 35        | 1.42%   |
| Intel Wireless 7265                                                    | 33        | 1.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 32        | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 31        | 1.26%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 28        | 1.14%   |
| Intel Wireless 8260                                                    | 27        | 1.09%   |
| Intel Wireless 7260                                                    | 26        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 25        | 1.01%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 24        | 0.97%   |
| Intel Ethernet Controller I225-V                                       | 23        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                   | 23        | 0.93%   |
| Intel Ethernet Connection I217-LM                                      | 21        | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 20        | 0.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 20        | 0.81%   |
| Intel Wireless 3165                                                    | 19        | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                   | 19        | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                          | 19        | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 16        | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 15        | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                                  | 15        | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 15        | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 14        | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 14        | 0.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 14        | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 14        | 0.57%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 14        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 655       | 53.87%  |
| Realtek Semiconductor                 | 207       | 17.02%  |
| Qualcomm Atheros                      | 115       | 9.46%   |
| MediaTek                              | 81        | 6.66%   |
| Broadcom                              | 45        | 3.7%    |
| TP-Link                               | 17        | 1.4%    |
| Microsoft                             | 16        | 1.32%   |
| D-Link                                | 14        | 1.15%   |
| Broadcom Limited                      | 14        | 1.15%   |
| Sierra Wireless                       | 8         | 0.66%   |
| Ralink                                | 7         | 0.58%   |
| Qualcomm                              | 7         | 0.58%   |
| Ralink Technology                     | 5         | 0.41%   |
| Qualcomm Atheros Communications       | 5         | 0.41%   |
| Marvell Technology Group              | 4         | 0.33%   |
| Linksys                               | 2         | 0.16%   |
| D-Link System                         | 2         | 0.16%   |
| Wilocity                              | 1         | 0.08%   |
| Tenda                                 | 1         | 0.08%   |
| Quectel Wireless Solutions            | 1         | 0.08%   |
| Qualcomm Technologies                 | 1         | 0.08%   |
| NetGear                               | 1         | 0.08%   |
| Fibocom                               | 1         | 0.08%   |
| Ericsson Business Mobile Networks     | 1         | 0.08%   |
| Edimax Technology                     | 1         | 0.08%   |
| Dell                                  | 1         | 0.08%   |
| Belkin Components                     | 1         | 0.08%   |
| AVM                                   | 1         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 115       | 9.36%   |
| Intel Wireless 8265 / 8275                                           | 50        | 4.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 45        | 3.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 42        | 3.42%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 42        | 3.42%   |
| Intel Wi-Fi 6 AX201                                                  | 37        | 3.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 36        | 2.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 36        | 2.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 35        | 2.85%   |
| Intel Wireless 7265                                                  | 33        | 2.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 31        | 2.52%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 28        | 2.28%   |
| Intel Wireless 8260                                                  | 27        | 2.2%    |
| Intel Wireless 7260                                                  | 26        | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 25        | 2.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 24        | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 20        | 1.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 20        | 1.63%   |
| Intel Wireless 3165                                                  | 19        | 1.55%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 19        | 1.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 16        | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 15        | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 15        | 1.22%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 14        | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 14        | 1.14%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 14        | 1.14%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 14        | 1.14%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 14        | 1.14%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 13        | 1.06%   |
| Realtek 802.11ac NIC                                                 | 13        | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 13        | 1.06%   |
| Microsoft Xbox Wireless Adapter for Windows                          | 12        | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 11        | 0.9%    |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 11        | 0.9%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 10        | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 10        | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 10        | 0.81%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 10        | 0.81%   |
| Intel Wireless 3160                                                  | 9         | 0.73%   |
| D-Link 802.11ac NIC                                                  | 9         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 714       | 60.51%  |
| Intel                         | 304       | 25.76%  |
| Qualcomm Atheros              | 44        | 3.73%   |
| Broadcom                      | 22        | 1.86%   |
| ASIX Electronics              | 22        | 1.86%   |
| DisplayLink                   | 10        | 0.85%   |
| Aquantia                      | 7         | 0.59%   |
| Nvidia                        | 6         | 0.51%   |
| Lenovo                        | 6         | 0.51%   |
| Cypress Semiconductor         | 6         | 0.51%   |
| OPPO Electronics              | 5         | 0.42%   |
| Samsung Electronics           | 4         | 0.34%   |
| Google                        | 4         | 0.34%   |
| Apple                         | 4         | 0.34%   |
| Xiaomi                        | 3         | 0.25%   |
| TP-Link                       | 2         | 0.17%   |
| ICS Advent                    | 2         | 0.17%   |
| D-Link                        | 2         | 0.17%   |
| Broadcom Limited              | 2         | 0.17%   |
| Qualcomm                      | 1         | 0.08%   |
| OnePlus Technology (Shenzhen) | 1         | 0.08%   |
| NetGear                       | 1         | 0.08%   |
| Motorola PCS                  | 1         | 0.08%   |
| Microsoft                     | 1         | 0.08%   |
| Mellanox Technologies         | 1         | 0.08%   |
| MediaTek                      | 1         | 0.08%   |
| Marvell Technology Group      | 1         | 0.08%   |
| Huawei Technologies           | 1         | 0.08%   |
| Hewlett-Packard               | 1         | 0.08%   |
| D-Link System                 | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 538       | 44.13%  |
| Realtek RTL8125 2.5GbE Controller                                      | 82        | 6.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 53        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 43        | 3.53%   |
| Intel I211 Gigabit Network Connection                                  | 42        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 32        | 2.63%   |
| Intel Ethernet Controller I225-V                                       | 23        | 1.89%   |
| Intel Ethernet Connection (2) I219-V                                   | 23        | 1.89%   |
| Intel Ethernet Connection I217-LM                                      | 21        | 1.72%   |
| Intel Ethernet Connection (7) I219-V                                   | 19        | 1.56%   |
| ASIX AX88179 Gigabit Ethernet                                          | 19        | 1.56%   |
| Intel Ethernet Connection (4) I219-LM                                  | 15        | 1.23%   |
| Intel Ethernet Connection I219-LM                                      | 11        | 0.9%    |
| Intel Ethernet Connection (4) I219-V                                   | 11        | 0.9%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 10        | 0.82%   |
| Intel Ethernet Connection I218-LM                                      | 10        | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                                  | 10        | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 7         | 0.57%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 6         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.49%   |
| Intel Ethernet Connection I217-V                                       | 6         | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                   | 6         | 0.49%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.49%   |
| Cypress K38231_03                                                      | 6         | 0.49%   |
| Realtek Killer E2600 GbE Controller                                    | 5         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 0.41%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 5         | 0.41%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 0.41%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 5         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 0.33%   |
| Intel Ethernet Controller I226-V                                       | 4         | 0.33%   |
| Intel Ethernet Connection (6) I219-V                                   | 4         | 0.33%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4         | 0.33%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.33%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.33%   |
| Intel 82574L Gigabit Network Connection                                | 4         | 0.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 4         | 0.33%   |
| Apple iBridge                                                          | 4         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1145      | 50.87%  |
| Ethernet | 1088      | 48.33%  |
| Modem    | 16        | 0.71%   |
| Unknown  | 2         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 927       | 64.24%  |
| Ethernet | 516       | 35.76%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 740       | 54.29%  |
| 1     | 570       | 41.82%  |
| 3     | 40        | 2.93%   |
| 0     | 8         | 0.59%   |
| 4     | 5         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1036      | 75.02%  |
| Yes  | 345       | 24.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 593       | 52.99%  |
| Realtek Semiconductor           | 128       | 11.44%  |
| Cambridge Silicon Radio         | 58        | 5.18%   |
| IMC Networks                    | 53        | 4.74%   |
| Qualcomm Atheros Communications | 50        | 4.47%   |
| Foxconn / Hon Hai               | 47        | 4.2%    |
| Lite-On Technology              | 34        | 3.04%   |
| Broadcom                        | 33        | 2.95%   |
| Apple                           | 25        | 2.23%   |
| MediaTek                        | 22        | 1.97%   |
| ASUSTek Computer                | 22        | 1.97%   |
| Realtek                         | 10        | 0.89%   |
| TP-Link                         | 7         | 0.63%   |
| Toshiba                         | 6         | 0.54%   |
| USI                             | 5         | 0.45%   |
| Ralink                          | 4         | 0.36%   |
| HTC (High Tech Computer)        | 4         | 0.36%   |
| Hewlett-Packard                 | 4         | 0.36%   |
| Dell                            | 4         | 0.36%   |
| Marvell Semiconductor           | 3         | 0.27%   |
| Opticis                         | 2         | 0.18%   |
| Foxconn International           | 1         | 0.09%   |
| Edimax Technology               | 1         | 0.09%   |
| Dynex                           | 1         | 0.09%   |
| Alps Electric                   | 1         | 0.09%   |
| Actions                         | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 173       | 15.41%  |
| Intel AX201 Bluetooth                                                | 112       | 9.97%   |
| Intel AX200 Bluetooth                                                | 110       | 9.8%    |
| Realtek Bluetooth Radio                                              | 95        | 8.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 65        | 5.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 58        | 5.16%   |
| Intel Bluetooth Device                                               | 51        | 4.54%   |
| Intel AX210 Bluetooth                                                | 41        | 3.65%   |
| Qualcomm Atheros  Bluetooth Device                                   | 33        | 2.94%   |
| Foxconn / Hon Hai Wireless_Device                                    | 32        | 2.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 26        | 2.32%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 23        | 2.05%   |
| MediaTek Wireless_Device                                             | 21        | 1.87%   |
| IMC Networks Bluetooth Radio                                         | 21        | 1.87%   |
| IMC Networks Wireless_Device                                         | 20        | 1.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 14        | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 14        | 1.25%   |
| Apple Bluetooth USB Host Controller                                  | 13        | 1.16%   |
| Realtek Bluetooth Radio                                              | 10        | 0.89%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 8         | 0.71%   |
| Lite-On Bluetooth Device                                             | 8         | 0.71%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 8         | 0.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 8         | 0.71%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 8         | 0.71%   |
| TP-Link UB500 Adapter                                                | 7         | 0.62%   |
| IMC Networks Bluetooth Device                                        | 7         | 0.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 6         | 0.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 6         | 0.53%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 6         | 0.53%   |
| Apple Bluetooth Host Controller                                      | 6         | 0.53%   |
| USI Bluetooth Device                                                 | 5         | 0.45%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 5         | 0.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 5         | 0.45%   |
| Ralink RT3290 Bluetooth                                              | 4         | 0.36%   |
| Lite-On Wireless_Device                                              | 4         | 0.36%   |
| Lite-On Bluetooth Radio                                              | 4         | 0.36%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4         | 0.36%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 4         | 0.36%   |
| ASUS ASUS USB-BT500                                                  | 4         | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 3         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 850       | 38.55%  |
| AMD                                          | 542       | 24.58%  |
| Nvidia                                       | 393       | 17.82%  |
| C-Media Electronics                          | 50        | 2.27%   |
| Logitech                                     | 32        | 1.45%   |
| SteelSeries ApS                              | 25        | 1.13%   |
| Texas Instruments                            | 22        | 1%      |
| Kingston Technology                          | 20        | 0.91%   |
| Creative Technology                          | 13        | 0.59%   |
| Creative Labs                                | 13        | 0.59%   |
| Focusrite-Novation                           | 12        | 0.54%   |
| Sony                                         | 11        | 0.5%    |
| Razer USA                                    | 11        | 0.5%    |
| JMTek                                        | 11        | 0.5%    |
| Corsair                                      | 11        | 0.5%    |
| Realtek Semiconductor                        | 10        | 0.45%   |
| Blue Microphones                             | 9         | 0.41%   |
| Micro Star International                     | 8         | 0.36%   |
| Lenovo                                       | 8         | 0.36%   |
| Hewlett-Packard                              | 8         | 0.36%   |
| RODE Microphones                             | 7         | 0.32%   |
| Generalplus Technology                       | 7         | 0.32%   |
| KORG                                         | 6         | 0.27%   |
| XMOS                                         | 5         | 0.23%   |
| Valve Software                               | 5         | 0.23%   |
| Samson Technologies                          | 5         | 0.23%   |
| NAD Electronics                              | 5         | 0.23%   |
| ASUSTek Computer                             | 5         | 0.23%   |
| Apple                                        | 5         | 0.23%   |
| AKAI                                         | 5         | 0.23%   |
| KTMicro                                      | 4         | 0.18%   |
| DSEA A/S                                     | 4         | 0.18%   |
| AKAI Professional M.I.                       | 4         | 0.18%   |
| Trust                                        | 3         | 0.14%   |
| GYROCOM C&C                                  | 3         | 0.14%   |
| FiiO Electronics Technology                  | 3         | 0.14%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.09%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.09%   |
| Tenx Technology                              | 2         | 0.09%   |
| Plantronics                                  | 2         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 277       | 10.19%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 152       | 5.59%   |
| Intel Sunrise Point-LP HD Audio                                            | 128       | 4.71%   |
| AMD Starship/Matisse HD Audio Controller                                   | 124       | 4.56%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 68        | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 61        | 2.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 58        | 2.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 56        | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 53        | 1.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 51        | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 44        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 43        | 1.58%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 42        | 1.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 39        | 1.43%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 38        | 1.4%    |
| Nvidia GA104 High Definition Audio Controller                              | 35        | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 33        | 1.21%   |
| Intel 8 Series HD Audio Controller                                         | 33        | 1.21%   |
| Nvidia TU106 High Definition Audio Controller                              | 32        | 1.18%   |
| Intel Haswell-ULT HD Audio Controller                                      | 32        | 1.18%   |
| Nvidia TU116 High Definition Audio Controller                              | 31        | 1.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 30        | 1.1%    |
| Nvidia GA106 High Definition Audio Controller                              | 29        | 1.07%   |
| Nvidia Audio device                                                        | 28        | 1.03%   |
| Intel Comet Lake PCH-LP cAVS                                               | 28        | 1.03%   |
| Intel Comet Lake PCH cAVS                                                  | 27        | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 27        | 0.99%   |
| Intel 200 Series PCH HD Audio                                              | 27        | 0.99%   |
| Nvidia GP104 High Definition Audio Controller                              | 26        | 0.96%   |
| Intel Broadwell-U Audio Controller                                         | 25        | 0.92%   |
| AMD Navi 10 HDMI Audio                                                     | 25        | 0.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 24        | 0.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 24        | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 23        | 0.85%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 21        | 0.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 20        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 20        | 0.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 19        | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 18        | 0.66%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 18        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 304       | 25.5%   |
| SK hynix            | 206       | 17.28%  |
| Micron Technology   | 131       | 10.99%  |
| Kingston            | 107       | 8.98%   |
| Corsair             | 92        | 7.72%   |
| G.Skill             | 80        | 6.71%   |
| Crucial             | 79        | 6.63%   |
| Unknown             | 43        | 3.61%   |
| A-DATA Technology   | 20        | 1.68%   |
| Ramaxel Technology  | 18        | 1.51%   |
| Team                | 15        | 1.26%   |
| Patriot             | 13        | 1.09%   |
| Unknown (ABCD)      | 9         | 0.76%   |
| Elpida              | 9         | 0.76%   |
| Unknown             | 9         | 0.76%   |
| Nanya Technology    | 6         | 0.5%    |
| Kllisre             | 4         | 0.34%   |
| GOODRAM             | 4         | 0.34%   |
| Neo Forza           | 3         | 0.25%   |
| Transcend           | 2         | 0.17%   |
| Teikon              | 2         | 0.17%   |
| Silicon Power       | 2         | 0.17%   |
| Shenzhen Mic        | 2         | 0.17%   |
| KLEVV               | 2         | 0.17%   |
| Hikvision           | 2         | 0.17%   |
| Golden Empire       | 2         | 0.17%   |
| Apacer              | 2         | 0.17%   |
| Wilk                | 1         | 0.08%   |
| V-GeN               | 1         | 0.08%   |
| Unknown (0x5846)    | 1         | 0.08%   |
| Unknown (0x0C97)    | 1         | 0.08%   |
| Toshiba             | 1         | 0.08%   |
| Strontium           | 1         | 0.08%   |
| Smart Brazil        | 1         | 0.08%   |
| Smart               | 1         | 0.08%   |
| Sesame              | 1         | 0.08%   |
| Qimonda             | 1         | 0.08%   |
| PNY                 | 1         | 0.08%   |
| OLOY                | 1         | 0.08%   |
| MAXSUN              | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 21        | 1.64%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 17        | 1.32%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 15        | 1.17%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 14        | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 14        | 1.09%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 12        | 0.93%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 11        | 0.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 11        | 0.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 11        | 0.86%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 0.86%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 10        | 0.78%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s               | 10        | 0.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 9         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 9         | 0.7%    |
| Unknown                                                             | 9         | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 8         | 0.62%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 8         | 0.62%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 8         | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 7         | 0.55%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 7         | 0.55%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 7         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 7         | 0.55%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s                | 7         | 0.55%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 6         | 0.47%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 6         | 0.47%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 6         | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 6         | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 6         | 0.47%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 6         | 0.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 6         | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 5         | 0.39%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 5         | 0.39%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 5         | 0.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 5         | 0.39%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s             | 5         | 0.39%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s        | 5         | 0.39%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 5         | 0.39%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 5         | 0.39%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s              | 5         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 637       | 62.09%  |
| DDR3    | 190       | 18.52%  |
| LPDDR4  | 54        | 5.26%   |
| DDR5    | 52        | 5.07%   |
| LPDDR3  | 35        | 3.41%   |
| LPDDR5  | 26        | 2.53%   |
| DDR2    | 15        | 1.46%   |
| SDRAM   | 9         | 0.88%   |
| Unknown | 7         | 0.68%   |
| DDR     | 1         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 589       | 57.41%  |
| DIMM         | 302       | 29.43%  |
| Row Of Chips | 122       | 11.89%  |
| Chip         | 7         | 0.68%   |
| Unknown      | 4         | 0.39%   |
| RIMM         | 1         | 0.1%    |
| FB-DIMM      | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 534       | 47.85%  |
| 4096  | 235       | 21.06%  |
| 16384 | 223       | 19.98%  |
| 32768 | 59        | 5.29%   |
| 2048  | 57        | 5.11%   |
| 1024  | 7         | 0.63%   |
| 49152 | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 285       | 25.42%  |
| 2667    | 175       | 15.61%  |
| 1600    | 148       | 13.2%   |
| 2400    | 65        | 5.8%    |
| 3600    | 55        | 4.91%   |
| 2133    | 51        | 4.55%   |
| 4800    | 35        | 3.12%   |
| 1333    | 30        | 2.68%   |
| 6400    | 27        | 2.41%   |
| 3266    | 24        | 2.14%   |
| 1867    | 23        | 2.05%   |
| 4267    | 21        | 1.87%   |
| 3733    | 20        | 1.78%   |
| 3800    | 13        | 1.16%   |
| 3533    | 11        | 0.98%   |
| 1334    | 11        | 0.98%   |
| 5600    | 9         | 0.8%    |
| 3400    | 8         | 0.71%   |
| 3866    | 7         | 0.62%   |
| 800     | 7         | 0.62%   |
| 667     | 7         | 0.62%   |
| 2666    | 6         | 0.54%   |
| Unknown | 6         | 0.54%   |
| 3000    | 5         | 0.45%   |
| 1800    | 5         | 0.45%   |
| 6000    | 4         | 0.36%   |
| 4266    | 4         | 0.36%   |
| 2933    | 4         | 0.36%   |
| 2800    | 4         | 0.36%   |
| 1067    | 4         | 0.36%   |
| 3500    | 3         | 0.27%   |
| 2048    | 3         | 0.27%   |
| 1066    | 3         | 0.27%   |
| 8400    | 2         | 0.18%   |
| 5200    | 2         | 0.18%   |
| 4000    | 2         | 0.18%   |
| 3666    | 2         | 0.18%   |
| 3534    | 2         | 0.18%   |
| 3466    | 2         | 0.18%   |
| 3066    | 2         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 25%     |
| Brother Industries  | 6         | 25%     |
| Canon               | 3         | 12.5%   |
| Xerox               | 2         | 8.33%   |
| Seiko Epson         | 2         | 8.33%   |
| Samsung Electronics | 2         | 8.33%   |
| Prolific Technology | 2         | 8.33%   |
| Pantum              | 1         | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Xerox B210                           | 2         | 8.33%   |
| Prolific PL2305 Parallel Port        | 2         | 8.33%   |
| Seiko Epson WF-2010 Series           | 1         | 4.17%   |
| Seiko Epson ET-2850 Series           | 1         | 4.17%   |
| Samsung ML-331x Series Laser Printer | 1         | 4.17%   |
| Samsung M2020 Series                 | 1         | 4.17%   |
| Pantum P2500W series                 | 1         | 4.17%   |
| HP Smart Tank 530 series             | 1         | 4.17%   |
| HP OfficeJet Pro 8020 series         | 1         | 4.17%   |
| HP ENVY 5540 series                  | 1         | 4.17%   |
| HP ENVY 5000 series                  | 1         | 4.17%   |
| HP DeskJet 2130 series               | 1         | 4.17%   |
| HP ColorLaserJet M253-M254           | 1         | 4.17%   |
| Canon PIXMA MG2500 Series            | 1         | 4.17%   |
| Canon MF260 II Series                | 1         | 4.17%   |
| Canon iP4200                         | 1         | 4.17%   |
| Brother Printer                      | 1         | 4.17%   |
| Brother MFC-L2710DW series           | 1         | 4.17%   |
| Brother MFC-J4535DW                  | 1         | 4.17%   |
| Brother HL-2130 series               | 1         | 4.17%   |
| Brother DCP-9020CDW                  | 1         | 4.17%   |
| Brother DCP-9015CDW                  | 1         | 4.17%   |

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
| Chicony Electronics                    | 177       | 18.14%  |
| IMC Networks                           | 127       | 13.01%  |
| Logitech                               | 83        | 8.5%    |
| Microdia                               | 68        | 6.97%   |
| Bison Electronics                      | 59        | 6.05%   |
| Quanta                                 | 51        | 5.23%   |
| Realtek Semiconductor                  | 42        | 4.3%    |
| Sunplus Innovation Technology          | 38        | 3.89%   |
| Cheng Uei Precision Industry (Foxlink) | 38        | 3.89%   |
| Syntek                                 | 32        | 3.28%   |
| Apple                                  | 32        | 3.28%   |
| Acer                                   | 28        | 2.87%   |
| Luxvisions Innotech Limited            | 27        | 2.77%   |
| Lite-On Technology                     | 27        | 2.77%   |
| Sonix Technology                       | 18        | 1.84%   |
| Microsoft                              | 14        | 1.43%   |
| Suyin                                  | 9         | 0.92%   |
| Samsung Electronics                    | 7         | 0.72%   |
| MacroSilicon                           | 6         | 0.61%   |
| Valve Software                         | 5         | 0.51%   |
| Lenovo                                 | 5         | 0.51%   |
| Hewlett-Packard                        | 5         | 0.51%   |
| Silicon Motion                         | 4         | 0.41%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.41%   |
| Google                                 | 4         | 0.41%   |
| Alcor Micro                            | 4         | 0.41%   |
| Primax Electronics                     | 3         | 0.31%   |
| Jieli Technology                       | 3         | 0.31%   |
| Generalplus Technology                 | 3         | 0.31%   |
| GEMBIRD                                | 3         | 0.31%   |
| Y Media                                | 2         | 0.2%    |
| Trust                                  | 2         | 0.2%    |
| Tripath Technology                     | 2         | 0.2%    |
| ShineTech                              | 2         | 0.2%    |
| Ricoh                                  | 2         | 0.2%    |
| LG Electronics                         | 2         | 0.2%    |
| KYE Systems (Mouse Systems)            | 2         | 0.2%    |
| Intel                                  | 2         | 0.2%    |
| Huawei Technologies                    | 2         | 0.2%    |
| Creative Technology                    | 2         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 56        | 5.71%   |
| IMC Networks Integrated Camera                       | 48        | 4.89%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 47        | 4.79%   |
| Microdia Integrated_Webcam_HD                        | 26        | 2.65%   |
| Chicony HD Webcam                                    | 26        | 2.65%   |
| Bison Integrated Camera                              | 26        | 2.65%   |
| Syntek Integrated Camera                             | 22        | 2.24%   |
| Logitech HD Pro Webcam C920                          | 18        | 1.83%   |
| Realtek Integrated_Webcam_HD                         | 17        | 1.73%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                   | 16        | 1.63%   |
| Logitech Webcam C270                                 | 15        | 1.53%   |
| Sonix USB2.0 HD UVC WebCam                           | 12        | 1.22%   |
| Microdia USB 2.0 Camera                              | 10        | 1.02%   |
| Bison BisonCam,NB Pro                                | 10        | 1.02%   |
| Apple FaceTime HD Camera (Built-in)                  | 10        | 1.02%   |
| Acer HD Webcam                                       | 10        | 1.02%   |
| Sunplus Integrated_Webcam_HD                         | 9         | 0.92%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 9         | 0.92%   |
| Logitech C920 PRO HD Webcam                          | 9         | 0.92%   |
| Quanta USB2.0 HD UVC WebCam                          | 8         | 0.82%   |
| Microdia Webcam Vitade AF                            | 8         | 0.82%   |
| Logitech C922 Pro Stream Webcam                      | 8         | 0.82%   |
| Lite-On Integrated Camera                            | 8         | 0.82%   |
| Sunplus HD WebCam                                    | 7         | 0.71%   |
| Samsung Galaxy series, misc. (MTP mode)              | 7         | 0.71%   |
| Quanta HP TrueVision HD Camera                       | 7         | 0.71%   |
| Quanta HD User Facing                                | 7         | 0.71%   |
| Microsoft LifeCam HD-3000                            | 7         | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                         | 7         | 0.71%   |
| Chicony HP Wide Vision HD Camera                     | 7         | 0.71%   |
| Sonix USB2.0 FHD UVC WebCam                          | 6         | 0.61%   |
| Quanta HP HD Camera                                  | 6         | 0.61%   |
| Quanta HD Camera                                     | 6         | 0.61%   |
| Microdia Integrated_Webcam_FHD                       | 6         | 0.61%   |
| Microdia Integrated Webcam                           | 6         | 0.61%   |
| Logitech StreamCam                                   | 6         | 0.61%   |
| IMC Networks ov9734_azurewave_camera                 | 6         | 0.61%   |
| Chicony HD User Facing                               | 6         | 0.61%   |
| Acer SunplusIT Integrated Camera                     | 6         | 0.61%   |
| Valve Software 3D Camera                             | 5         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 65        | 36.93%  |
| Validity Sensors                   | 42        | 23.86%  |
| Shenzhen Goodix Technology         | 30        | 17.05%  |
| Elan Microelectronics              | 21        | 11.93%  |
| LighTuning Technology              | 7         | 3.98%   |
| Upek                               | 3         | 1.7%    |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.7%    |
| Samsung Electronics                | 2         | 1.14%   |
| AuthenTec                          | 2         | 1.14%   |
| Focal-systems.Corp                 | 1         | 0.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 10.23%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 9.09%   |
| Elan ELAN:Fingerprint                                                      | 13        | 7.39%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 6.82%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 5.68%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 5.11%   |
| Synaptics  WBDI                                                            | 8         | 4.55%   |
| Elan ELAN:ARM-M4                                                           | 8         | 4.55%   |
| Synaptics WBDI                                                             | 6         | 3.41%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 3.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 3.41%   |
| Synaptics UWP WBDI                                                         | 5         | 2.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.27%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 2.27%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.27%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 2.27%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.7%    |
| Validity Sensors VFS491                                                    | 3         | 1.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 1.7%    |
| Synaptics UWP WBDI Device                                                  | 3         | 1.7%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.7%    |
| Unknown                                                                    | 3         | 1.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.14%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 1.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.57%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.57%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.57%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.57%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 0.57%   |
| AuthenTec AES2810                                                          | 1         | 0.57%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 28        | 48.28%  |
| Alcor Micro | 18        | 31.03%  |
| Upek        | 4         | 6.9%    |
| Lenovo      | 4         | 6.9%    |
| O2 Micro    | 2         | 3.45%   |
| HID Global  | 1         | 1.72%   |
| Cherry      | 1         | 1.72%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 28.81%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 18.64%  |
| Broadcom 5880                                                                | 9         | 15.25%  |
| Broadcom 58200                                                               | 6         | 10.17%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 6.78%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.78%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 5.08%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.39%   |
| HID Global USB Reader V3                                                     | 1         | 1.69%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.69%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 952       | 68.34%  |
| 1     | 367       | 26.35%  |
| 2     | 67        | 4.81%   |
| 3     | 5         | 0.36%   |
| 8     | 1         | 0.07%   |
| 4     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 174       | 35.08%  |
| Multimedia controller    | 57        | 11.49%  |
| Net/ethernet             | 55        | 11.09%  |
| Chipcard                 | 54        | 10.89%  |
| Graphics card            | 51        | 10.28%  |
| Net/wireless             | 38        | 7.66%   |
| Camera                   | 21        | 4.23%   |
| Bluetooth                | 13        | 2.62%   |
| Network                  | 7         | 1.41%   |
| Unassigned class         | 5         | 1.01%   |
| Storage                  | 4         | 0.81%   |
| Sound                    | 3         | 0.6%    |
| Dvb card                 | 3         | 0.6%    |
| Communication controller | 3         | 0.6%    |
| Storage/nvme             | 2         | 0.4%    |
| Modem                    | 2         | 0.4%    |
| Card reader              | 2         | 0.4%    |
| Storage/raid             | 1         | 0.2%    |
| Storage/ata              | 1         | 0.2%    |

