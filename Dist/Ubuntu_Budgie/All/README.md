Ubuntu Budgie - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie/Notebook/README.md).

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

Total: 989

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | G50-45 80E3                 | Notebook    | [2ac9878b30](https://linux-hardware.org/?probe=2ac9878b30) | Nov 05, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [532db79d07](https://linux-hardware.org/?probe=532db79d07) | Nov 05, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a816b34b9e](https://linux-hardware.org/?probe=a816b34b9e) | Nov 03, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [e1edc2410b](https://linux-hardware.org/?probe=e1edc2410b) | Nov 03, 2023 |
| Dell          | Latitude E5470              | Notebook    | [b1be043dc0](https://linux-hardware.org/?probe=b1be043dc0) | Oct 31, 2023 |
| Sony          | SVS13A25PBS                 | Notebook    | [7cb087bd2d](https://linux-hardware.org/?probe=7cb087bd2d) | Oct 27, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [5236a2eca3](https://linux-hardware.org/?probe=5236a2eca3) | Oct 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [47186b8e71](https://linux-hardware.org/?probe=47186b8e71) | Oct 24, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [41f9f44ee1](https://linux-hardware.org/?probe=41f9f44ee1) | Oct 20, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [98f1b28357](https://linux-hardware.org/?probe=98f1b28357) | Oct 20, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [b3a6489f94](https://linux-hardware.org/?probe=b3a6489f94) | Oct 20, 2023 |
| IMUZ          | STORMBOOK14 APOLLO          | Notebook    | [6d8e8178b0](https://linux-hardware.org/?probe=6d8e8178b0) | Oct 19, 2023 |
| Google        | Kled                        | Notebook    | [4d546b71e7](https://linux-hardware.org/?probe=4d546b71e7) | Oct 17, 2023 |
| Gateway       | NV59C                       | Notebook    | [5a0c4e72d6](https://linux-hardware.org/?probe=5a0c4e72d6) | Oct 16, 2023 |
| Dell          | Inspiron 16 7630 2-in-1     | Convertible | [f4e2082297](https://linux-hardware.org/?probe=f4e2082297) | Oct 16, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [3055b32637](https://linux-hardware.org/?probe=3055b32637) | Oct 15, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [b09d2e33fd](https://linux-hardware.org/?probe=b09d2e33fd) | Oct 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [feb4113e4e](https://linux-hardware.org/?probe=feb4113e4e) | Oct 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6bb631736f](https://linux-hardware.org/?probe=6bb631736f) | Oct 15, 2023 |
| HP            | 8054                        | Desktop     | [66ad5550d1](https://linux-hardware.org/?probe=66ad5550d1) | Oct 10, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [c2205d1cf2](https://linux-hardware.org/?probe=c2205d1cf2) | Oct 10, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [a90e584705](https://linux-hardware.org/?probe=a90e584705) | Oct 04, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [657233bb53](https://linux-hardware.org/?probe=657233bb53) | Oct 02, 2023 |
| HONOR         | HLYL-WXX9                   | Notebook    | [5a440c873d](https://linux-hardware.org/?probe=5a440c873d) | Oct 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [73b5907f17](https://linux-hardware.org/?probe=73b5907f17) | Sep 30, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [1331a57778](https://linux-hardware.org/?probe=1331a57778) | Sep 27, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| Acer          | Aspire 7530G                | Notebook    | [37d34804dd](https://linux-hardware.org/?probe=37d34804dd) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [9a1d56bda1](https://linux-hardware.org/?probe=9a1d56bda1) | Sep 20, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [01e90212e5](https://linux-hardware.org/?probe=01e90212e5) | Sep 20, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [6588973c54](https://linux-hardware.org/?probe=6588973c54) | Sep 19, 2023 |
| Gateway       | NV59C                       | Notebook    | [0885dc9384](https://linux-hardware.org/?probe=0885dc9384) | Sep 16, 2023 |
| Dell          | Latitude 7280               | Notebook    | [ecca4887d5](https://linux-hardware.org/?probe=ecca4887d5) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [312d4a06dc](https://linux-hardware.org/?probe=312d4a06dc) | Sep 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [40c7e7f27b](https://linux-hardware.org/?probe=40c7e7f27b) | Aug 31, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [4fe996e64f](https://linux-hardware.org/?probe=4fe996e64f) | Aug 29, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [f09b86405b](https://linux-hardware.org/?probe=f09b86405b) | Aug 26, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [044deb0ad2](https://linux-hardware.org/?probe=044deb0ad2) | Aug 22, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [921d699e5d](https://linux-hardware.org/?probe=921d699e5d) | Aug 19, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [1e39da3f6e](https://linux-hardware.org/?probe=1e39da3f6e) | Aug 18, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [a34dfca1e3](https://linux-hardware.org/?probe=a34dfca1e3) | Aug 14, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [934ab444f2](https://linux-hardware.org/?probe=934ab444f2) | Aug 07, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [3f8e9bffbd](https://linux-hardware.org/?probe=3f8e9bffbd) | Aug 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [73efa45f4f](https://linux-hardware.org/?probe=73efa45f4f) | Aug 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [ce0e015b6e](https://linux-hardware.org/?probe=ce0e015b6e) | Aug 05, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [15fb5d0baf](https://linux-hardware.org/?probe=15fb5d0baf) | Aug 04, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e97688a8c1](https://linux-hardware.org/?probe=e97688a8c1) | Jul 27, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [7466fce2a2](https://linux-hardware.org/?probe=7466fce2a2) | Jul 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e31d121593](https://linux-hardware.org/?probe=e31d121593) | Jul 15, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [cabc9a2940](https://linux-hardware.org/?probe=cabc9a2940) | Jul 15, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [9c3135decf](https://linux-hardware.org/?probe=9c3135decf) | Jul 10, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ce4fed4466](https://linux-hardware.org/?probe=ce4fed4466) | Jul 08, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [12561e59a4](https://linux-hardware.org/?probe=12561e59a4) | Jul 07, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [48526cd359](https://linux-hardware.org/?probe=48526cd359) | Jul 07, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | Notebook    | [760a6712db](https://linux-hardware.org/?probe=760a6712db) | Jul 07, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [95fa9e14bf](https://linux-hardware.org/?probe=95fa9e14bf) | Jul 07, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | Notebook    | [3e7598da34](https://linux-hardware.org/?probe=3e7598da34) | Jul 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [dedd6c842c](https://linux-hardware.org/?probe=dedd6c842c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [dfe3274d7e](https://linux-hardware.org/?probe=dfe3274d7e) | Jul 03, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [aae865deb7](https://linux-hardware.org/?probe=aae865deb7) | Jul 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [89db1a9656](https://linux-hardware.org/?probe=89db1a9656) | Jul 02, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0e9e13c4b5](https://linux-hardware.org/?probe=0e9e13c4b5) | Jul 02, 2023 |
| BANGHO        | BES G0304                   | Notebook    | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [c9a8bc63d4](https://linux-hardware.org/?probe=c9a8bc63d4) | Jun 27, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [4428a36327](https://linux-hardware.org/?probe=4428a36327) | Jun 27, 2023 |
| HP            | EliteBook x360 1030 G4      | Convertible | [740bd03ee0](https://linux-hardware.org/?probe=740bd03ee0) | Jun 26, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [7cc301b3f7](https://linux-hardware.org/?probe=7cc301b3f7) | Jun 21, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [1ba2e18bc1](https://linux-hardware.org/?probe=1ba2e18bc1) | Jun 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [544b40258b](https://linux-hardware.org/?probe=544b40258b) | Jun 21, 2023 |
| Dell          | Inspiron 16 7630 2-in-1     | Convertible | [d003b60677](https://linux-hardware.org/?probe=d003b60677) | Jun 20, 2023 |
| Dell          | Inspiron 16 7630 2-in-1     | Convertible | [66607910c0](https://linux-hardware.org/?probe=66607910c0) | Jun 19, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f04b28a0e5](https://linux-hardware.org/?probe=f04b28a0e5) | Jun 10, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [f87fe0fe34](https://linux-hardware.org/?probe=f87fe0fe34) | Jun 08, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Gigabyte      | H310M HD2                   | Desktop     | [b28787ecb7](https://linux-hardware.org/?probe=b28787ecb7) | Jun 04, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [3903b22ffd](https://linux-hardware.org/?probe=3903b22ffd) | Jun 02, 2023 |
| HP            | Notebook                    | Notebook    | [c246477ea2](https://linux-hardware.org/?probe=c246477ea2) | May 31, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [d12d9a4fc2](https://linux-hardware.org/?probe=d12d9a4fc2) | May 29, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9cbdd21a81](https://linux-hardware.org/?probe=9cbdd21a81) | May 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [b63a3cbd7b](https://linux-hardware.org/?probe=b63a3cbd7b) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [3db7516231](https://linux-hardware.org/?probe=3db7516231) | May 25, 2023 |
| Dell          | Latitude 5521               | Notebook    | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [51c520b6e6](https://linux-hardware.org/?probe=51c520b6e6) | May 25, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [e484eaf025](https://linux-hardware.org/?probe=e484eaf025) | May 24, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [741d6fe6d2](https://linux-hardware.org/?probe=741d6fe6d2) | May 19, 2023 |
| HP            | Bloog                       | Notebook    | [4673a7630e](https://linux-hardware.org/?probe=4673a7630e) | May 16, 2023 |
| HP            | Bloog                       | Notebook    | [1c91d5ef51](https://linux-hardware.org/?probe=1c91d5ef51) | May 16, 2023 |
| Dell          | 024JD7 A00                  | Desktop     | [904e4e2a0d](https://linux-hardware.org/?probe=904e4e2a0d) | May 15, 2023 |
| Dell          | Latitude E5420              | Notebook    | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| TUXEDO        | Book XP1511                 | Notebook    | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [9ed744299a](https://linux-hardware.org/?probe=9ed744299a) | May 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [8a80fd7103](https://linux-hardware.org/?probe=8a80fd7103) | May 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3198c997b2](https://linux-hardware.org/?probe=3198c997b2) | May 04, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7a26c45568](https://linux-hardware.org/?probe=7a26c45568) | May 04, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [a0b1299baa](https://linux-hardware.org/?probe=a0b1299baa) | May 02, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [8a7ed180c0](https://linux-hardware.org/?probe=8a7ed180c0) | May 02, 2023 |
| Dell          | Latitude E5420              | Notebook    | [df8c9e7f40](https://linux-hardware.org/?probe=df8c9e7f40) | Apr 30, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [f87233a295](https://linux-hardware.org/?probe=f87233a295) | Apr 29, 2023 |
| Lenovo        | B50-30 80ES                 | Notebook    | [d84727b8e4](https://linux-hardware.org/?probe=d84727b8e4) | Apr 29, 2023 |
| Intel         | H61                         | Desktop     | [b8f0acdf61](https://linux-hardware.org/?probe=b8f0acdf61) | Apr 28, 2023 |
| ZOTAC         | ZBOX-ECM73070C/7307LH/53... | Mini pc     | [c3d1c96452](https://linux-hardware.org/?probe=c3d1c96452) | Apr 26, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c546b0771a](https://linux-hardware.org/?probe=c546b0771a) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [b402183807](https://linux-hardware.org/?probe=b402183807) | Apr 24, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [2508f138a4](https://linux-hardware.org/?probe=2508f138a4) | Apr 23, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [090405a4a7](https://linux-hardware.org/?probe=090405a4a7) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | Notebook    | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [8f9e883980](https://linux-hardware.org/?probe=8f9e883980) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [19fc60d2a5](https://linux-hardware.org/?probe=19fc60d2a5) | Apr 14, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| ZOTAC         | ZBOX-ECM73070C/7307LH/53... | Mini pc     | [6bdb0611ac](https://linux-hardware.org/?probe=6bdb0611ac) | Apr 10, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [683d3101d8](https://linux-hardware.org/?probe=683d3101d8) | Mar 31, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [e8fc7722ef](https://linux-hardware.org/?probe=e8fc7722ef) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1c517ff300](https://linux-hardware.org/?probe=1c517ff300) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [d714304a67](https://linux-hardware.org/?probe=d714304a67) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [f733f5b792](https://linux-hardware.org/?probe=f733f5b792) | Mar 27, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [ebd974c40f](https://linux-hardware.org/?probe=ebd974c40f) | Mar 23, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2536217d87](https://linux-hardware.org/?probe=2536217d87) | Mar 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [0301ad09f6](https://linux-hardware.org/?probe=0301ad09f6) | Mar 23, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [a3339e152a](https://linux-hardware.org/?probe=a3339e152a) | Mar 18, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [1ade706194](https://linux-hardware.org/?probe=1ade706194) | Mar 17, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [45537ae306](https://linux-hardware.org/?probe=45537ae306) | Mar 17, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d73bb5ec34](https://linux-hardware.org/?probe=d73bb5ec34) | Mar 15, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| ASUSTek       | K52F                        | Notebook    | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| HP            | 83E1                        | Desktop     | [86061f121d](https://linux-hardware.org/?probe=86061f121d) | Mar 08, 2023 |
| MSI           | Raider GE76 12UE            | Notebook    | [b78033fddd](https://linux-hardware.org/?probe=b78033fddd) | Mar 08, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [3c681075fb](https://linux-hardware.org/?probe=3c681075fb) | Mar 04, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [38a0ce48ed](https://linux-hardware.org/?probe=38a0ce48ed) | Mar 04, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [7997191f44](https://linux-hardware.org/?probe=7997191f44) | Feb 28, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [9a6bc5f3af](https://linux-hardware.org/?probe=9a6bc5f3af) | Feb 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [b80c1e685f](https://linux-hardware.org/?probe=b80c1e685f) | Feb 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [6b2160527d](https://linux-hardware.org/?probe=6b2160527d) | Feb 23, 2023 |
| MSI           | Z170-A PRO                  | Desktop     | [a5a54422a0](https://linux-hardware.org/?probe=a5a54422a0) | Feb 23, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [12f305c12f](https://linux-hardware.org/?probe=12f305c12f) | Feb 17, 2023 |
| Google        | Boten                       | Notebook    | [5562b4af15](https://linux-hardware.org/?probe=5562b4af15) | Feb 11, 2023 |
| Google        | Boten                       | Notebook    | [d07e5295bb](https://linux-hardware.org/?probe=d07e5295bb) | Feb 11, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [8c6fb84b12](https://linux-hardware.org/?probe=8c6fb84b12) | Feb 09, 2023 |
| ASRock        | Z390 Phantom Gaming 4-IB    | Desktop     | [3a9937a61b](https://linux-hardware.org/?probe=3a9937a61b) | Feb 09, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [5dfc3e2280](https://linux-hardware.org/?probe=5dfc3e2280) | Feb 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0e931084a7](https://linux-hardware.org/?probe=0e931084a7) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [866e97ab12](https://linux-hardware.org/?probe=866e97ab12) | Feb 03, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [9f812fe2a7](https://linux-hardware.org/?probe=9f812fe2a7) | Feb 02, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b5f0169944](https://linux-hardware.org/?probe=b5f0169944) | Jan 28, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [de3f21b51b](https://linux-hardware.org/?probe=de3f21b51b) | Jan 28, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [329e7b7105](https://linux-hardware.org/?probe=329e7b7105) | Jan 28, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a772965137](https://linux-hardware.org/?probe=a772965137) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [ee44dc2539](https://linux-hardware.org/?probe=ee44dc2539) | Jan 27, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [1d507a3cdc](https://linux-hardware.org/?probe=1d507a3cdc) | Jan 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [831fd897ec](https://linux-hardware.org/?probe=831fd897ec) | Jan 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [0c8a9895bd](https://linux-hardware.org/?probe=0c8a9895bd) | Jan 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [b3bc8de731](https://linux-hardware.org/?probe=b3bc8de731) | Jan 25, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [7bf2d60c0b](https://linux-hardware.org/?probe=7bf2d60c0b) | Jan 21, 2023 |
| Google        | Banjo                       | Notebook    | [30a528ac6b](https://linux-hardware.org/?probe=30a528ac6b) | Jan 14, 2023 |
| Google        | Banjo                       | Notebook    | [66dc97b0de](https://linux-hardware.org/?probe=66dc97b0de) | Jan 14, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [a5e1965b89](https://linux-hardware.org/?probe=a5e1965b89) | Jan 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [d83005eb10](https://linux-hardware.org/?probe=d83005eb10) | Jan 03, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [f560abfd7f](https://linux-hardware.org/?probe=f560abfd7f) | Jan 03, 2023 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [de65990b87](https://linux-hardware.org/?probe=de65990b87) | Jan 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP14... | Convertible | [195eb3e6eb](https://linux-hardware.org/?probe=195eb3e6eb) | Dec 31, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | Notebook    | [a14e00ab97](https://linux-hardware.org/?probe=a14e00ab97) | Dec 29, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | Notebook    | [00e25b3232](https://linux-hardware.org/?probe=00e25b3232) | Dec 29, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [2d653884d9](https://linux-hardware.org/?probe=2d653884d9) | Dec 29, 2022 |
| Dell          | System XPS L502X            | Notebook    | [db4f93ae82](https://linux-hardware.org/?probe=db4f93ae82) | Dec 22, 2022 |
| MSI           | GL65 Leopard 10SDK          | Notebook    | [2c6e6ec3ec](https://linux-hardware.org/?probe=2c6e6ec3ec) | Dec 21, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [1773b79334](https://linux-hardware.org/?probe=1773b79334) | Dec 17, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [e95599a479](https://linux-hardware.org/?probe=e95599a479) | Dec 09, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c40fd27f39](https://linux-hardware.org/?probe=c40fd27f39) | Dec 05, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [3272263f3b](https://linux-hardware.org/?probe=3272263f3b) | Dec 04, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [42efe1dfdf](https://linux-hardware.org/?probe=42efe1dfdf) | Dec 02, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [40111c09eb](https://linux-hardware.org/?probe=40111c09eb) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [cdd03a3498](https://linux-hardware.org/?probe=cdd03a3498) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [2731961e4c](https://linux-hardware.org/?probe=2731961e4c) | Nov 30, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [4e0102dff6](https://linux-hardware.org/?probe=4e0102dff6) | Nov 20, 2022 |
| Dell          | 0RW199                      | Desktop     | [2a2fa5baf8](https://linux-hardware.org/?probe=2a2fa5baf8) | Nov 20, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [cb719dbd60](https://linux-hardware.org/?probe=cb719dbd60) | Nov 19, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [afb716fb12](https://linux-hardware.org/?probe=afb716fb12) | Nov 18, 2022 |
| MSI           | GL65 Leopard 10SFKV         | Notebook    | [84668eb3a8](https://linux-hardware.org/?probe=84668eb3a8) | Nov 16, 2022 |
| MSI           | GL65 Leopard 10SFKV         | Notebook    | [316e275c13](https://linux-hardware.org/?probe=316e275c13) | Nov 16, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0f94a77355](https://linux-hardware.org/?probe=0f94a77355) | Nov 12, 2022 |
| Thomson       | N17V3C8WH512                | Notebook    | [f13487a2f3](https://linux-hardware.org/?probe=f13487a2f3) | Nov 07, 2022 |
| Thomson       | N17V3C8WH512                | Notebook    | [58d6a21b17](https://linux-hardware.org/?probe=58d6a21b17) | Nov 06, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [751669286c](https://linux-hardware.org/?probe=751669286c) | Nov 05, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [fd97cf3ecb](https://linux-hardware.org/?probe=fd97cf3ecb) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [26a8adcee2](https://linux-hardware.org/?probe=26a8adcee2) | Oct 31, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [3448172ca3](https://linux-hardware.org/?probe=3448172ca3) | Oct 29, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | Notebook    | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | Notebook    | [3cb2ce5a02](https://linux-hardware.org/?probe=3cb2ce5a02) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Dell          | Latitude E5420              | Notebook    | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| MSI           | H67MA-E35                   | Desktop     | [d4f5628033](https://linux-hardware.org/?probe=d4f5628033) | Oct 11, 2022 |
| AXIOO         | Slimbook 13                 | Notebook    | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | Notebook    | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | Notebook    | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | Notebook    | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [293e528545](https://linux-hardware.org/?probe=293e528545) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Gigabyte      | B75M-D3P                    | Desktop     | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [19a21d721c](https://linux-hardware.org/?probe=19a21d721c) | Sep 07, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [cc583599ef](https://linux-hardware.org/?probe=cc583599ef) | Aug 28, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Google        | Rabbid                      | Notebook    | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| HP            | 3397                        | Desktop     | [335f59c96f](https://linux-hardware.org/?probe=335f59c96f) | Aug 22, 2022 |
| Intel         | X79M-S                      | Desktop     | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| ASUSTek       | Berkeley                    | Desktop     | [e9998910ee](https://linux-hardware.org/?probe=e9998910ee) | Aug 17, 2022 |
| Acer          | TravelMate P653-M           | Notebook    | [1e33abf031](https://linux-hardware.org/?probe=1e33abf031) | Aug 17, 2022 |
| HP            | 828A                        | Desktop     | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Biostar       | A960D+V3                    | Desktop     | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [5d50a29ca9](https://linux-hardware.org/?probe=5d50a29ca9) | Aug 13, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [8c6f00600e](https://linux-hardware.org/?probe=8c6f00600e) | Aug 12, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [2a95697c62](https://linux-hardware.org/?probe=2a95697c62) | Jul 25, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Alienware     | M11xR3                      | Notebook    | [e479dcdefb](https://linux-hardware.org/?probe=e479dcdefb) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [d2ed25b6e8](https://linux-hardware.org/?probe=d2ed25b6e8) | Jul 16, 2022 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | Notebook    | [f1dcf09169](https://linux-hardware.org/?probe=f1dcf09169) | Jul 14, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| Google        | Eve                         | Convertible | [be0c82653c](https://linux-hardware.org/?probe=be0c82653c) | Jul 09, 2022 |
| HP            | ENVY 17                     | Notebook    | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Dell          | Latitude E7450              | Notebook    | [34913911ca](https://linux-hardware.org/?probe=34913911ca) | Jul 05, 2022 |
| Dell          | Latitude E7450              | Notebook    | [60e633e563](https://linux-hardware.org/?probe=60e633e563) | Jul 04, 2022 |
| Positivo      | Q232A                       | Notebook    | [c297e38afb](https://linux-hardware.org/?probe=c297e38afb) | Jun 27, 2022 |
| Positivo      | Q232A                       | Notebook    | [8774fcf3a2](https://linux-hardware.org/?probe=8774fcf3a2) | Jun 27, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [b48ce81bfa](https://linux-hardware.org/?probe=b48ce81bfa) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Lenovo        | ThinkPad T400 6475AT3       | Notebook    | [55fd247328](https://linux-hardware.org/?probe=55fd247328) | Jun 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| MSI           | GL62 6QF                    | Notebook    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | Notebook    | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Pavilion dv7                | Notebook    | [add98928e5](https://linux-hardware.org/?probe=add98928e5) | Jun 18, 2022 |
| HP            | Pavilion dv7                | Notebook    | [bfecf091a6](https://linux-hardware.org/?probe=bfecf091a6) | Jun 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [261466af7b](https://linux-hardware.org/?probe=261466af7b) | Jun 17, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [d4ad64d715](https://linux-hardware.org/?probe=d4ad64d715) | Jun 15, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8e47a3c188](https://linux-hardware.org/?probe=8e47a3c188) | Jun 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [3195007eb2](https://linux-hardware.org/?probe=3195007eb2) | May 30, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | Notebook    | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| MSI           | Modern 15 A10M              | Notebook    | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| HP            | 1825                        | Desktop     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [e97309bc05](https://linux-hardware.org/?probe=e97309bc05) | May 07, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9f241088c2](https://linux-hardware.org/?probe=9f241088c2) | May 06, 2022 |
| Google        | Boten                       | Notebook    | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| Samsung       | 740U3M                      | Convertible | [4ba9324ca5](https://linux-hardware.org/?probe=4ba9324ca5) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [9505d0e8b7](https://linux-hardware.org/?probe=9505d0e8b7) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| HP            | 8446                        | All in one  | [b13e626d1a](https://linux-hardware.org/?probe=b13e626d1a) | May 02, 2022 |
| HP            | 8446                        | All in one  | [14d68e146a](https://linux-hardware.org/?probe=14d68e146a) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Sony          | SVS13A25PBS                 | Notebook    | [c1be74b619](https://linux-hardware.org/?probe=c1be74b619) | Apr 25, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [089d81a936](https://linux-hardware.org/?probe=089d81a936) | Apr 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [51daefb9d3](https://linux-hardware.org/?probe=51daefb9d3) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [714396bc62](https://linux-hardware.org/?probe=714396bc62) | Apr 20, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [37fa300c26](https://linux-hardware.org/?probe=37fa300c26) | Apr 18, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | Notebook    | [c1a5e02fa5](https://linux-hardware.org/?probe=c1a5e02fa5) | Apr 17, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [96eae556f2](https://linux-hardware.org/?probe=96eae556f2) | Apr 15, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [ca66ed7272](https://linux-hardware.org/?probe=ca66ed7272) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| MSI           | H81M-E33                    | Desktop     | [33547f6d85](https://linux-hardware.org/?probe=33547f6d85) | Apr 11, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| Alienware     | m15                         | Notebook    | [0cd462faaa](https://linux-hardware.org/?probe=0cd462faaa) | Apr 07, 2022 |
| Lenovo        | ThinkPad E490 20N9001MBR    | Notebook    | [1b041100a3](https://linux-hardware.org/?probe=1b041100a3) | Apr 07, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| TUXEDO        | InfinityBook S 14 v5        | Notebook    | [6a5061e741](https://linux-hardware.org/?probe=6a5061e741) | Apr 03, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [860fedd7f0](https://linux-hardware.org/?probe=860fedd7f0) | Apr 01, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [995691e022](https://linux-hardware.org/?probe=995691e022) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| Packard Be... | ENLE11BZ                    | Notebook    | [4fb836698c](https://linux-hardware.org/?probe=4fb836698c) | Mar 26, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [2b82008ffc](https://linux-hardware.org/?probe=2b82008ffc) | Mar 23, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [ffc0cdf0bd](https://linux-hardware.org/?probe=ffc0cdf0bd) | Mar 22, 2022 |
| HP            | 8158 A01                    | Mini pc     | [3ba669d072](https://linux-hardware.org/?probe=3ba669d072) | Mar 20, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [ca76b3a899](https://linux-hardware.org/?probe=ca76b3a899) | Mar 18, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [f444e85d64](https://linux-hardware.org/?probe=f444e85d64) | Mar 18, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [63ea3e99c5](https://linux-hardware.org/?probe=63ea3e99c5) | Mar 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [08525a320d](https://linux-hardware.org/?probe=08525a320d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b61991cef4](https://linux-hardware.org/?probe=b61991cef4) | Mar 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [22452f39c2](https://linux-hardware.org/?probe=22452f39c2) | Mar 11, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [42921aebfd](https://linux-hardware.org/?probe=42921aebfd) | Mar 10, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [be60e729e2](https://linux-hardware.org/?probe=be60e729e2) | Mar 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| HP            | Pavilion dm4                | Notebook    | [4786fbfbdd](https://linux-hardware.org/?probe=4786fbfbdd) | Mar 04, 2022 |
| HP            | Pavilion dm4                | Notebook    | [8adb026a31](https://linux-hardware.org/?probe=8adb026a31) | Mar 04, 2022 |
| Google        | Rammus                      | Notebook    | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [5be284f90d](https://linux-hardware.org/?probe=5be284f90d) | Feb 26, 2022 |
| Microsoft     | Surface Book                | Tablet      | [a94d46ec1d](https://linux-hardware.org/?probe=a94d46ec1d) | Feb 25, 2022 |
| Microsoft     | Surface Book                | Tablet      | [f62d16f3b1](https://linux-hardware.org/?probe=f62d16f3b1) | Feb 25, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7fa418eb00](https://linux-hardware.org/?probe=7fa418eb00) | Feb 25, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [0ed28fa881](https://linux-hardware.org/?probe=0ed28fa881) | Feb 23, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9b8714532b](https://linux-hardware.org/?probe=9b8714532b) | Feb 20, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Dell          | 0RW199                      | Desktop     | [5cf70558c8](https://linux-hardware.org/?probe=5cf70558c8) | Feb 14, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [07233a144c](https://linux-hardware.org/?probe=07233a144c) | Feb 09, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2dd47c0a4b](https://linux-hardware.org/?probe=2dd47c0a4b) | Feb 08, 2022 |
| Viglen        | VUB1                        | Notebook    | [13f512e2d1](https://linux-hardware.org/?probe=13f512e2d1) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Razer         | Blade Stealth               | Notebook    | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | Notebook    | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| Acer          | Aspire 8940G                | Notebook    | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [f9e76db452](https://linux-hardware.org/?probe=f9e76db452) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [74533ff76f](https://linux-hardware.org/?probe=74533ff76f) | Jan 28, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [77a04d958e](https://linux-hardware.org/?probe=77a04d958e) | Jan 27, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [6f4c9d5553](https://linux-hardware.org/?probe=6f4c9d5553) | Jan 27, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [f7fafa6976](https://linux-hardware.org/?probe=f7fafa6976) | Jan 26, 2022 |
| TUXEDO        | Book XP1511                 | Notebook    | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [909aca1407](https://linux-hardware.org/?probe=909aca1407) | Jan 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e45b9230c9](https://linux-hardware.org/?probe=e45b9230c9) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [98ff0f7580](https://linux-hardware.org/?probe=98ff0f7580) | Jan 17, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| Viglen        | VUB1                        | Notebook    | [d16d7f30b3](https://linux-hardware.org/?probe=d16d7f30b3) | Jan 16, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [d7414a7101](https://linux-hardware.org/?probe=d7414a7101) | Jan 15, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [e4d4e112f7](https://linux-hardware.org/?probe=e4d4e112f7) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [172d5b0abc](https://linux-hardware.org/?probe=172d5b0abc) | Jan 12, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [ecaadc9cb3](https://linux-hardware.org/?probe=ecaadc9cb3) | Jan 04, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [bd181b10da](https://linux-hardware.org/?probe=bd181b10da) | Jan 04, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e55162d481](https://linux-hardware.org/?probe=e55162d481) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ee6ede67e9](https://linux-hardware.org/?probe=ee6ede67e9) | Jan 02, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [339ee3ca1c](https://linux-hardware.org/?probe=339ee3ca1c) | Dec 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [16855d1282](https://linux-hardware.org/?probe=16855d1282) | Dec 27, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [14323d7f2a](https://linux-hardware.org/?probe=14323d7f2a) | Dec 27, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| Teclast       | X6 plus                     | Tablet      | [d476f875d2](https://linux-hardware.org/?probe=d476f875d2) | Dec 23, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [f0e03ffaed](https://linux-hardware.org/?probe=f0e03ffaed) | Dec 22, 2021 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [ddf55561ad](https://linux-hardware.org/?probe=ddf55561ad) | Dec 21, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [8e1c093fb8](https://linux-hardware.org/?probe=8e1c093fb8) | Dec 20, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [7eabc884a6](https://linux-hardware.org/?probe=7eabc884a6) | Dec 19, 2021 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [d416ec7878](https://linux-hardware.org/?probe=d416ec7878) | Dec 17, 2021 |
| HP            | Pavilion dm1                | Notebook    | [5e63d24312](https://linux-hardware.org/?probe=5e63d24312) | Dec 17, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [f586c51674](https://linux-hardware.org/?probe=f586c51674) | Dec 17, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [2aaaff47a4](https://linux-hardware.org/?probe=2aaaff47a4) | Dec 17, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [d34989fcaa](https://linux-hardware.org/?probe=d34989fcaa) | Dec 16, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7587f8f78a](https://linux-hardware.org/?probe=7587f8f78a) | Dec 16, 2021 |
| Acer          | E3-112M-C6BV                | Notebook    | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [bd9653afdd](https://linux-hardware.org/?probe=bd9653afdd) | Dec 15, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [49234a5c74](https://linux-hardware.org/?probe=49234a5c74) | Dec 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [7cf830d39e](https://linux-hardware.org/?probe=7cf830d39e) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | Notebook    | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [b6c63776b5](https://linux-hardware.org/?probe=b6c63776b5) | Dec 10, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [b2d2913170](https://linux-hardware.org/?probe=b2d2913170) | Dec 07, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [429851405d](https://linux-hardware.org/?probe=429851405d) | Dec 07, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [ade1f1db1a](https://linux-hardware.org/?probe=ade1f1db1a) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [9721dbfb66](https://linux-hardware.org/?probe=9721dbfb66) | Dec 07, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [0e41e47583](https://linux-hardware.org/?probe=0e41e47583) | Dec 05, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [126c160ef3](https://linux-hardware.org/?probe=126c160ef3) | Dec 04, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [088fab187c](https://linux-hardware.org/?probe=088fab187c) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [2f6f3b14de](https://linux-hardware.org/?probe=2f6f3b14de) | Dec 03, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [945995abf6](https://linux-hardware.org/?probe=945995abf6) | Dec 02, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [35a82530fb](https://linux-hardware.org/?probe=35a82530fb) | Dec 02, 2021 |
| Sony          | VPCEJ1L1E                   | Notebook    | [a48a00bdbc](https://linux-hardware.org/?probe=a48a00bdbc) | Dec 02, 2021 |
| TUXEDO        | P95_HP                      | Notebook    | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [e62e98d46d](https://linux-hardware.org/?probe=e62e98d46d) | Nov 30, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [3cea520e1f](https://linux-hardware.org/?probe=3cea520e1f) | Nov 29, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [3fbd626bf6](https://linux-hardware.org/?probe=3fbd626bf6) | Nov 27, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [ba184983ea](https://linux-hardware.org/?probe=ba184983ea) | Nov 27, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [86f23cb2f4](https://linux-hardware.org/?probe=86f23cb2f4) | Nov 22, 2021 |
| HP            | 0A5Ch                       | Desktop     | [4858eb5c73](https://linux-hardware.org/?probe=4858eb5c73) | Nov 21, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [b397fce5b8](https://linux-hardware.org/?probe=b397fce5b8) | Nov 20, 2021 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [61f2f6aeab](https://linux-hardware.org/?probe=61f2f6aeab) | Nov 19, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [008cd729a5](https://linux-hardware.org/?probe=008cd729a5) | Nov 14, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [cb21aae05f](https://linux-hardware.org/?probe=cb21aae05f) | Nov 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [f18f314bc7](https://linux-hardware.org/?probe=f18f314bc7) | Nov 01, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [ef04c3c27a](https://linux-hardware.org/?probe=ef04c3c27a) | Oct 31, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [8ecbd29abd](https://linux-hardware.org/?probe=8ecbd29abd) | Oct 29, 2021 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [571936bc0d](https://linux-hardware.org/?probe=571936bc0d) | Oct 23, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [6a3a81abd6](https://linux-hardware.org/?probe=6a3a81abd6) | Oct 22, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [2f0f49590b](https://linux-hardware.org/?probe=2f0f49590b) | Oct 22, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [90e49546c2](https://linux-hardware.org/?probe=90e49546c2) | Oct 21, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [cc51204b2c](https://linux-hardware.org/?probe=cc51204b2c) | Oct 20, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | 0A5Ch                       | Desktop     | [8d102a03f6](https://linux-hardware.org/?probe=8d102a03f6) | Oct 19, 2021 |
| HP            | 0A5Ch                       | Desktop     | [139efd1a3d](https://linux-hardware.org/?probe=139efd1a3d) | Oct 19, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4cb5912db3](https://linux-hardware.org/?probe=4cb5912db3) | Oct 15, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [7a9034f398](https://linux-hardware.org/?probe=7a9034f398) | Oct 12, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [feb38e948d](https://linux-hardware.org/?probe=feb38e948d) | Sep 13, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [3ea6af2159](https://linux-hardware.org/?probe=3ea6af2159) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [981856c740](https://linux-hardware.org/?probe=981856c740) | Sep 09, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [17c9df42cd](https://linux-hardware.org/?probe=17c9df42cd) | Sep 07, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [01d203a7af](https://linux-hardware.org/?probe=01d203a7af) | Sep 07, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [4b6f0833eb](https://linux-hardware.org/?probe=4b6f0833eb) | Sep 02, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP            | x360 310 G2 PC              | Notebook    | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| Fujitsu       | LIFEBOOK U9311A             | Notebook    | [7d5eeb6448](https://linux-hardware.org/?probe=7d5eeb6448) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| ASRock        | H61M-VG3                    | Desktop     | [7257c7b0bb](https://linux-hardware.org/?probe=7257c7b0bb) | Aug 20, 2021 |
| Google        | Peppy                       | Notebook    | [b0be7ddeac](https://linux-hardware.org/?probe=b0be7ddeac) | Aug 18, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [15b41a9b17](https://linux-hardware.org/?probe=15b41a9b17) | Aug 16, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [dcbe85bfb3](https://linux-hardware.org/?probe=dcbe85bfb3) | Aug 16, 2021 |
| TUXEDO        | Book XP1511                 | Notebook    | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Unknown       | Unknown                     | Notebook    | [8ffbb927af](https://linux-hardware.org/?probe=8ffbb927af) | Aug 13, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [53a8be279f](https://linux-hardware.org/?probe=53a8be279f) | Aug 12, 2021 |
| Lenovo        | ThinkPad E490 20N8S07A00    | Notebook    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [c62d162396](https://linux-hardware.org/?probe=c62d162396) | Aug 02, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [9452fd6e14](https://linux-hardware.org/?probe=9452fd6e14) | Aug 02, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [cd96dbf86a](https://linux-hardware.org/?probe=cd96dbf86a) | Jul 30, 2021 |
| TUXEDO        | Book_XA1510                 | Notebook    | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO        | P95_HR                      | Notebook    | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| PC Special... | OctaneVI 15                 | Notebook    | [05e8f69907](https://linux-hardware.org/?probe=05e8f69907) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6f7de51af1](https://linux-hardware.org/?probe=6f7de51af1) | Jul 25, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [b983e48d71](https://linux-hardware.org/?probe=b983e48d71) | Jul 24, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [18951b50fd](https://linux-hardware.org/?probe=18951b50fd) | Jul 23, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [2335f32be7](https://linux-hardware.org/?probe=2335f32be7) | Jul 22, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [157b9695ae](https://linux-hardware.org/?probe=157b9695ae) | Jul 15, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e0f1466068](https://linux-hardware.org/?probe=e0f1466068) | Jul 09, 2021 |
| HP            | 1588h                       | Desktop     | [28a2da9b7f](https://linux-hardware.org/?probe=28a2da9b7f) | Jul 05, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [b2586cfeba](https://linux-hardware.org/?probe=b2586cfeba) | Jul 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [19f235e9dd](https://linux-hardware.org/?probe=19f235e9dd) | Jul 04, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [cd4215f3d2](https://linux-hardware.org/?probe=cd4215f3d2) | Jul 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [04c41fe4c2](https://linux-hardware.org/?probe=04c41fe4c2) | Jun 30, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [d2d1c6e65e](https://linux-hardware.org/?probe=d2d1c6e65e) | Jun 28, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | Notebook    | [5e91d6296d](https://linux-hardware.org/?probe=5e91d6296d) | Jun 27, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | Notebook    | [4e3ee76cd4](https://linux-hardware.org/?probe=4e3ee76cd4) | Jun 27, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [d90efe186a](https://linux-hardware.org/?probe=d90efe186a) | Jun 25, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [f8795e30bf](https://linux-hardware.org/?probe=f8795e30bf) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [143827e2e8](https://linux-hardware.org/?probe=143827e2e8) | Jun 16, 2021 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| HP            | Notebook                    | Notebook    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| BANGHO        | MAX G5 i1                   | Notebook    | [ca05e3a059](https://linux-hardware.org/?probe=ca05e3a059) | Jun 15, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| HP            | 1998                        | Desktop     | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| HP            | 1998                        | Desktop     | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [6a63f48182](https://linux-hardware.org/?probe=6a63f48182) | May 29, 2021 |
| AWOW          | AK41                        | Notebook    | [ca1ba6ce75](https://linux-hardware.org/?probe=ca1ba6ce75) | May 27, 2021 |
| Dell          | Latitude E6410              | Notebook    | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell          | Latitude E6410              | Notebook    | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [75877fb3b1](https://linux-hardware.org/?probe=75877fb3b1) | May 19, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [91cee123e9](https://linux-hardware.org/?probe=91cee123e9) | May 19, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| Dell          | Latitude E6540              | Notebook    | [6399cecb6f](https://linux-hardware.org/?probe=6399cecb6f) | May 19, 2021 |
| HP            | EliteBook 850 G1            | Notebook    | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [ec195ffe95](https://linux-hardware.org/?probe=ec195ffe95) | May 12, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7aa1f41d1e](https://linux-hardware.org/?probe=7aa1f41d1e) | May 12, 2021 |
| Dell          | Latitude 5480               | Notebook    | [e6d8aca46a](https://linux-hardware.org/?probe=e6d8aca46a) | May 11, 2021 |
| Packard Be... | EasyNote TM98               | Notebook    | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [8260769b47](https://linux-hardware.org/?probe=8260769b47) | May 01, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [a2fb8f6b18](https://linux-hardware.org/?probe=a2fb8f6b18) | May 01, 2021 |
| Dell          | Latitude D531               | Notebook    | [096370a055](https://linux-hardware.org/?probe=096370a055) | Apr 29, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| Dell          | Vostro 5460                 | Notebook    | [cf32099d64](https://linux-hardware.org/?probe=cf32099d64) | Apr 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [d7318b3c30](https://linux-hardware.org/?probe=d7318b3c30) | Apr 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ceee3d709c](https://linux-hardware.org/?probe=ceee3d709c) | Apr 26, 2021 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [289b0a89c0](https://linux-hardware.org/?probe=289b0a89c0) | Apr 25, 2021 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [2c0a43e573](https://linux-hardware.org/?probe=2c0a43e573) | Apr 24, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [28751098a6](https://linux-hardware.org/?probe=28751098a6) | Apr 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [c2c4591ef9](https://linux-hardware.org/?probe=c2c4591ef9) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | Notebook    | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | Notebook    | [a74abd0b52](https://linux-hardware.org/?probe=a74abd0b52) | Apr 16, 2021 |
| Sony          | SVS13A25PBS                 | Notebook    | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09dc9d1375](https://linux-hardware.org/?probe=09dc9d1375) | Apr 14, 2021 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [e0fa7ade7a](https://linux-hardware.org/?probe=e0fa7ade7a) | Apr 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9c8b7bc48a](https://linux-hardware.org/?probe=9c8b7bc48a) | Apr 06, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [3c414d527a](https://linux-hardware.org/?probe=3c414d527a) | Apr 05, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [383e2af37d](https://linux-hardware.org/?probe=383e2af37d) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire E1-431               | Notebook    | [0a6108eb22](https://linux-hardware.org/?probe=0a6108eb22) | Apr 04, 2021 |
| Huanan        | X79 249PC V2.2              | Desktop     | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [104c966a1a](https://linux-hardware.org/?probe=104c966a1a) | Mar 30, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [87168e11ee](https://linux-hardware.org/?probe=87168e11ee) | Mar 26, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [72adf1881e](https://linux-hardware.org/?probe=72adf1881e) | Mar 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f769aaeedd](https://linux-hardware.org/?probe=f769aaeedd) | Mar 26, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| ASUSTek       | Z77-A                       | Desktop     | [ca21510412](https://linux-hardware.org/?probe=ca21510412) | Mar 23, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c755699d3](https://linux-hardware.org/?probe=4c755699d3) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | Notebook    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | Notebook    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [282adc38a9](https://linux-hardware.org/?probe=282adc38a9) | Mar 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [c368ac7bac](https://linux-hardware.org/?probe=c368ac7bac) | Mar 20, 2021 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [83f55d5bf7](https://linux-hardware.org/?probe=83f55d5bf7) | Mar 20, 2021 |
| HP            | 3031h                       | Desktop     | [ee5e7baf77](https://linux-hardware.org/?probe=ee5e7baf77) | Mar 16, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [0cc10a7f8b](https://linux-hardware.org/?probe=0cc10a7f8b) | Mar 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [17a2a64f30](https://linux-hardware.org/?probe=17a2a64f30) | Mar 10, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [26c69c1a34](https://linux-hardware.org/?probe=26c69c1a34) | Mar 07, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [d9cc78fcff](https://linux-hardware.org/?probe=d9cc78fcff) | Mar 07, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [79b5c4e048](https://linux-hardware.org/?probe=79b5c4e048) | Mar 07, 2021 |
| HP            | ENVY 15                     | Notebook    | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [bc79c52365](https://linux-hardware.org/?probe=bc79c52365) | Mar 04, 2021 |
| Timi          | TM1701                      | Notebook    | [a47b371c00](https://linux-hardware.org/?probe=a47b371c00) | Mar 03, 2021 |
| Dell          | 0KJCC5 A00                  | Desktop     | [5587c00381](https://linux-hardware.org/?probe=5587c00381) | Mar 02, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d1866f15b4](https://linux-hardware.org/?probe=d1866f15b4) | Mar 02, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell          | Latitude 5590               | Notebook    | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [c6d24d073b](https://linux-hardware.org/?probe=c6d24d073b) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [f97163d774](https://linux-hardware.org/?probe=f97163d774) | Feb 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [290d20ab8b](https://linux-hardware.org/?probe=290d20ab8b) | Feb 23, 2021 |
| HP            | ENVY 15 x360 PC             | Notebook    | [1a67eafe01](https://linux-hardware.org/?probe=1a67eafe01) | Feb 22, 2021 |
| Dell          | Latitude E4300              | Notebook    | [ba125a9cb8](https://linux-hardware.org/?probe=ba125a9cb8) | Feb 22, 2021 |
| BCM           | RX965Q                      | Desktop     | [889ee09398](https://linux-hardware.org/?probe=889ee09398) | Feb 21, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [10e0380862](https://linux-hardware.org/?probe=10e0380862) | Feb 19, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [f747681c25](https://linux-hardware.org/?probe=f747681c25) | Feb 19, 2021 |
| ASUSTek       | H61M-A                      | Desktop     | [2b8de1db1f](https://linux-hardware.org/?probe=2b8de1db1f) | Feb 19, 2021 |
| Dell          | 0KRC95 A02                  | Desktop     | [745c1185fd](https://linux-hardware.org/?probe=745c1185fd) | Feb 18, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [d470929ba8](https://linux-hardware.org/?probe=d470929ba8) | Feb 14, 2021 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [24a9ae34ed](https://linux-hardware.org/?probe=24a9ae34ed) | Feb 13, 2021 |
| Lenovo        | 36F2 SDK0J40700 WIN 3258... | All in one  | [f172b5b1ea](https://linux-hardware.org/?probe=f172b5b1ea) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| Lenovo        | ThinkPad P1 20MES01400      | Notebook    | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [13979999ed](https://linux-hardware.org/?probe=13979999ed) | Feb 07, 2021 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [2028548034](https://linux-hardware.org/?probe=2028548034) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [f48bc9fc78](https://linux-hardware.org/?probe=f48bc9fc78) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [1f3b4b8203](https://linux-hardware.org/?probe=1f3b4b8203) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [005301f0e8](https://linux-hardware.org/?probe=005301f0e8) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [48a778609f](https://linux-hardware.org/?probe=48a778609f) | Feb 06, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [db6b98f685](https://linux-hardware.org/?probe=db6b98f685) | Feb 05, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell          | Latitude 5580               | Notebook    | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [771cb653c6](https://linux-hardware.org/?probe=771cb653c6) | Feb 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c94818db0e](https://linux-hardware.org/?probe=c94818db0e) | Feb 03, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [748cc10c8c](https://linux-hardware.org/?probe=748cc10c8c) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | Notebook    | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| Positivo      | C14CR21TV                   | Notebook    | [2133a41335](https://linux-hardware.org/?probe=2133a41335) | Feb 02, 2021 |
| MSI           | Prestige 14 A10SC           | Notebook    | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3d2867cd98](https://linux-hardware.org/?probe=3d2867cd98) | Jan 30, 2021 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [f519b82ae5](https://linux-hardware.org/?probe=f519b82ae5) | Jan 26, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [47517be667](https://linux-hardware.org/?probe=47517be667) | Jan 23, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI           | GP73 Leopard 8RE            | Notebook    | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [bb89e367c8](https://linux-hardware.org/?probe=bb89e367c8) | Jan 17, 2021 |
| Dell          | XPS L322X                   | Notebook    | [e65c21cdd5](https://linux-hardware.org/?probe=e65c21cdd5) | Jan 16, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [3a07ab383e](https://linux-hardware.org/?probe=3a07ab383e) | Jan 15, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [bb66f59b76](https://linux-hardware.org/?probe=bb66f59b76) | Jan 12, 2021 |
| HP            | 1589                        | Desktop     | [fe93b414cb](https://linux-hardware.org/?probe=fe93b414cb) | Jan 09, 2021 |
| MSI           | GE70 2PC\2PE                | Notebook    | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [92c9f3e6c5](https://linux-hardware.org/?probe=92c9f3e6c5) | Jan 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [276dda536a](https://linux-hardware.org/?probe=276dda536a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [bff63b3c48](https://linux-hardware.org/?probe=bff63b3c48) | Jan 05, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [a80e8c5eb0](https://linux-hardware.org/?probe=a80e8c5eb0) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| eMachines     | EZ1600                      | All in one  | [2c5f74bdac](https://linux-hardware.org/?probe=2c5f74bdac) | Jan 01, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| Toshiba       | Satellite P750              | Notebook    | [3d7045dbbf](https://linux-hardware.org/?probe=3d7045dbbf) | Dec 28, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [0d1e39a79a](https://linux-hardware.org/?probe=0d1e39a79a) | Dec 27, 2020 |
| HP            | Pavilion 17                 | Notebook    | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| eMachines     | EZ1600                      | All in one  | [2181178e2b](https://linux-hardware.org/?probe=2181178e2b) | Dec 25, 2020 |
| Dell          | 0PK096                      | Desktop     | [e1a520e089](https://linux-hardware.org/?probe=e1a520e089) | Dec 24, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [6260a9fb0f](https://linux-hardware.org/?probe=6260a9fb0f) | Dec 22, 2020 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [4f8b9f90d8](https://linux-hardware.org/?probe=4f8b9f90d8) | Dec 21, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [c671dc11ee](https://linux-hardware.org/?probe=c671dc11ee) | Dec 20, 2020 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [c32461bc20](https://linux-hardware.org/?probe=c32461bc20) | Dec 19, 2020 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [05c93972e0](https://linux-hardware.org/?probe=05c93972e0) | Dec 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [e81e3d85d6](https://linux-hardware.org/?probe=e81e3d85d6) | Dec 15, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [ff0cd7f2bc](https://linux-hardware.org/?probe=ff0cd7f2bc) | Dec 13, 2020 |
| ASUSTek       | F9E                         | Notebook    | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| HP            | EliteBook 850 G1            | Notebook    | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [d65d3733f6](https://linux-hardware.org/?probe=d65d3733f6) | Dec 07, 2020 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [25ff6d84d0](https://linux-hardware.org/?probe=25ff6d84d0) | Dec 07, 2020 |
| HP            | Pavilion dv1000 (EW999LA... | Notebook    | [6675bde630](https://linux-hardware.org/?probe=6675bde630) | Dec 07, 2020 |
| ASRock        | P67 Extreme4                | Desktop     | [ca2f3a785a](https://linux-hardware.org/?probe=ca2f3a785a) | Dec 06, 2020 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [d47823099d](https://linux-hardware.org/?probe=d47823099d) | Dec 02, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [465bfd7567](https://linux-hardware.org/?probe=465bfd7567) | Nov 28, 2020 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [77dc96c206](https://linux-hardware.org/?probe=77dc96c206) | Nov 27, 2020 |
| LattePanda    | Alpha                       | Desktop     | [706f930815](https://linux-hardware.org/?probe=706f930815) | Nov 26, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [c620f65d2b](https://linux-hardware.org/?probe=c620f65d2b) | Nov 25, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| LattePanda    | Alpha                       | Desktop     | [a5c3e54e65](https://linux-hardware.org/?probe=a5c3e54e65) | Nov 24, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [f391747dd0](https://linux-hardware.org/?probe=f391747dd0) | Nov 24, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [304945ac43](https://linux-hardware.org/?probe=304945ac43) | Nov 23, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [0afa851fa7](https://linux-hardware.org/?probe=0afa851fa7) | Nov 22, 2020 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [8bbc1a2d1c](https://linux-hardware.org/?probe=8bbc1a2d1c) | Nov 22, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [732043cc5f](https://linux-hardware.org/?probe=732043cc5f) | Nov 21, 2020 |
| ASUSTek       | P8Z68-V                     | Desktop     | [643bb20dc1](https://linux-hardware.org/?probe=643bb20dc1) | Nov 20, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [7e8af2342a](https://linux-hardware.org/?probe=7e8af2342a) | Nov 12, 2020 |
| ASUSTek       | K52De                       | Notebook    | [d95e3b8198](https://linux-hardware.org/?probe=d95e3b8198) | Nov 12, 2020 |
| ASUSTek       | K52De                       | Notebook    | [9aec230d46](https://linux-hardware.org/?probe=9aec230d46) | Nov 12, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Sony          | SVS13A25PBS                 | Notebook    | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Lenovo        | IdeaPad S100 20109          | Notebook    | [8f26323f1e](https://linux-hardware.org/?probe=8f26323f1e) | Nov 02, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [f403df4c45](https://linux-hardware.org/?probe=f403df4c45) | Nov 01, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [2e03e273f1](https://linux-hardware.org/?probe=2e03e273f1) | Oct 31, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [4a619e003e](https://linux-hardware.org/?probe=4a619e003e) | Oct 31, 2020 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [eb2134b274](https://linux-hardware.org/?probe=eb2134b274) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [e59b548946](https://linux-hardware.org/?probe=e59b548946) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [39348ac053](https://linux-hardware.org/?probe=39348ac053) | Oct 31, 2020 |
| Apple         | Mac-F2218FC8                | All in one  | [b72a5d9506](https://linux-hardware.org/?probe=b72a5d9506) | Oct 31, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [58b6426d57](https://linux-hardware.org/?probe=58b6426d57) | Oct 30, 2020 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [be195992d0](https://linux-hardware.org/?probe=be195992d0) | Oct 30, 2020 |
| Dell          | Latitude E6540              | Notebook    | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [aead0dde26](https://linux-hardware.org/?probe=aead0dde26) | Oct 27, 2020 |
| HP            | ZBook 14                    | Notebook    | [b282051085](https://linux-hardware.org/?probe=b282051085) | Oct 27, 2020 |
| HP            | Elite x2 1012 G1            | Notebook    | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP            | Elite x2 1012 G1            | Notebook    | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| HP            | Stream 7 Tablet             | Tablet      | [1cb5fb4518](https://linux-hardware.org/?probe=1cb5fb4518) | Oct 25, 2020 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [b5a98b7ffa](https://linux-hardware.org/?probe=b5a98b7ffa) | Oct 24, 2020 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [a5246866a5](https://linux-hardware.org/?probe=a5246866a5) | Oct 21, 2020 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [19879c3493](https://linux-hardware.org/?probe=19879c3493) | Oct 21, 2020 |
| Dell          | Latitude 5400               | Notebook    | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell          | Latitude 5400               | Notebook    | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP            | 1998                        | Desktop     | [e8076a87a0](https://linux-hardware.org/?probe=e8076a87a0) | Oct 20, 2020 |
| HP            | 1998                        | Desktop     | [69ed04c55d](https://linux-hardware.org/?probe=69ed04c55d) | Oct 20, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [25565a3bbf](https://linux-hardware.org/?probe=25565a3bbf) | Oct 19, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [3aa954c07b](https://linux-hardware.org/?probe=3aa954c07b) | Oct 19, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [7c78d9b4da](https://linux-hardware.org/?probe=7c78d9b4da) | Oct 18, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca85fa1d88](https://linux-hardware.org/?probe=ca85fa1d88) | Oct 18, 2020 |
| ASRock        | Q1900B-ITX                  | Desktop     | [527411a589](https://linux-hardware.org/?probe=527411a589) | Oct 15, 2020 |
| Unknown       | Unknown                     | Desktop     | [f82db8cb1c](https://linux-hardware.org/?probe=f82db8cb1c) | Oct 13, 2020 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [3d2cb2e4d1](https://linux-hardware.org/?probe=3d2cb2e4d1) | Oct 12, 2020 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [16d3bf5578](https://linux-hardware.org/?probe=16d3bf5578) | Oct 12, 2020 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [9d2f2dbd87](https://linux-hardware.org/?probe=9d2f2dbd87) | Oct 12, 2020 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | Notebook    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo        | 20SL                        | Notebook    | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | Notebook    | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| Dell          | 0M9KCM A00                  | Desktop     | [f884d19586](https://linux-hardware.org/?probe=f884d19586) | Oct 02, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [4a62de4c07](https://linux-hardware.org/?probe=4a62de4c07) | Oct 01, 2020 |
| MSI           | Modern 14 A10RB             | Notebook    | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [a996c3d55c](https://linux-hardware.org/?probe=a996c3d55c) | Sep 29, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | UX430UQ                     | Notebook    | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [5b7738af52](https://linux-hardware.org/?probe=5b7738af52) | Sep 23, 2020 |
| Dell          | Latitude 5400               | Notebook    | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| Dell          | 0RY007                      | Desktop     | [b1ca551538](https://linux-hardware.org/?probe=b1ca551538) | Sep 22, 2020 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [663a5ef41a](https://linux-hardware.org/?probe=663a5ef41a) | Sep 21, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [e91f9c04b9](https://linux-hardware.org/?probe=e91f9c04b9) | Sep 21, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [d746ae5a52](https://linux-hardware.org/?probe=d746ae5a52) | Sep 19, 2020 |
| HP            | ProBook 4730s               | Notebook    | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell          | Inspiron 7560               | Notebook    | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Radxa         | ROCK Pi 4A                  | Soc         | [b335776d4a](https://linux-hardware.org/?probe=b335776d4a) | Sep 14, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1037d2b746](https://linux-hardware.org/?probe=1037d2b746) | Sep 09, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [b3d6fb36eb](https://linux-hardware.org/?probe=b3d6fb36eb) | Sep 08, 2020 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [d36f3124d1](https://linux-hardware.org/?probe=d36f3124d1) | Sep 06, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [e90f4fb0e5](https://linux-hardware.org/?probe=e90f4fb0e5) | Sep 06, 2020 |
| PCSMART       | 6.0                         | Desktop     | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| MSI           | Z97 GAMING 5                | Desktop     | [3f1b387a92](https://linux-hardware.org/?probe=3f1b387a92) | Sep 04, 2020 |
| HP            | Pavilion g6                 | Notebook    | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell          | G7 7588                     | Notebook    | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [bc9c588fd8](https://linux-hardware.org/?probe=bc9c588fd8) | Aug 30, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [ed4a78cd06](https://linux-hardware.org/?probe=ed4a78cd06) | Aug 24, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| ASUSTek       | U47A                        | Notebook    | [39d5bde56a](https://linux-hardware.org/?probe=39d5bde56a) | Aug 19, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [75f32f4978](https://linux-hardware.org/?probe=75f32f4978) | Aug 16, 2020 |
| Sony          | VPCEK20AL                   | Notebook    | [2147eeff89](https://linux-hardware.org/?probe=2147eeff89) | Aug 16, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| ASUSTek       | U47A                        | Notebook    | [55022416f8](https://linux-hardware.org/?probe=55022416f8) | Aug 14, 2020 |
| ASUSTek       | U47A                        | Notebook    | [1c4676a5d6](https://linux-hardware.org/?probe=1c4676a5d6) | Aug 13, 2020 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [c908fd4599](https://linux-hardware.org/?probe=c908fd4599) | Aug 07, 2020 |
| Standard      | MT40II                      | Notebook    | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo        | ThinkPad T430s 23539WU      | Notebook    | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [d943208a7c](https://linux-hardware.org/?probe=d943208a7c) | Jul 30, 2020 |
| Apple         | MacBook3,1                  | Notebook    | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [cb5d511453](https://linux-hardware.org/?probe=cb5d511453) | Jul 28, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [87d7bc3077](https://linux-hardware.org/?probe=87d7bc3077) | Jul 28, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [f38e8a0201](https://linux-hardware.org/?probe=f38e8a0201) | Jul 26, 2020 |
| HP            | 82F2                        | Desktop     | [172d6aed2a](https://linux-hardware.org/?probe=172d6aed2a) | Jul 26, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [0479f5e75d](https://linux-hardware.org/?probe=0479f5e75d) | Jul 26, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP            | Pavilion 14                 | Notebook    | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP            | Pavilion dv6                | Notebook    | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell          | Latitude E6320              | Notebook    | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| HP            | 3397                        | Desktop     | [edd52c2428](https://linux-hardware.org/?probe=edd52c2428) | Jul 24, 2020 |
| HP            | 3397                        | Desktop     | [20b3d353d8](https://linux-hardware.org/?probe=20b3d353d8) | Jul 24, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [3ce4143dee](https://linux-hardware.org/?probe=3ce4143dee) | Jul 24, 2020 |
| Dell          | G3 3579                     | Notebook    | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell          | G7 7588                     | Notebook    | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek       | K53E                        | Notebook    | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI           | GL62M 7RD                   | Notebook    | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [12a4926d36](https://linux-hardware.org/?probe=12a4926d36) | Jul 17, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [534a204796](https://linux-hardware.org/?probe=534a204796) | Jul 17, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [fcc0f73453](https://linux-hardware.org/?probe=fcc0f73453) | Jul 15, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| Dell          | 0P301D A02                  | Desktop     | [709ca37e1e](https://linux-hardware.org/?probe=709ca37e1e) | Jul 12, 2020 |
| MSI           | GP72 7RE                    | Notebook    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c7cdebaa45](https://linux-hardware.org/?probe=c7cdebaa45) | Jul 09, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell          | XPS L401X                   | Notebook    | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [6af32ff946](https://linux-hardware.org/?probe=6af32ff946) | Jul 01, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [dd10caa4c9](https://linux-hardware.org/?probe=dd10caa4c9) | Jun 26, 2020 |
| Dell          | Latitude E6220              | Notebook    | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [33d1532efd](https://linux-hardware.org/?probe=33d1532efd) | Jun 23, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [110bf098e8](https://linux-hardware.org/?probe=110bf098e8) | Jun 22, 2020 |
| Dell          | 09KPNV A00                  | Desktop     | [9f63cccd5c](https://linux-hardware.org/?probe=9f63cccd5c) | Jun 21, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | Notebook    | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP            | ENVY 17                     | Notebook    | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell          | Inspiron 7590               | Notebook    | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony          | VPCCW25FL                   | Notebook    | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP            | ENVY 17                     | Notebook    | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [7c4e814d03](https://linux-hardware.org/?probe=7c4e814d03) | Jun 13, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [10875bae28](https://linux-hardware.org/?probe=10875bae28) | Jun 13, 2020 |
| Acer          | Aspire V3-572G              | Notebook    | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek       | X540LA                      | Notebook    | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP            | ENVY 17                     | Notebook    | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP            | ENVY 15                     | Notebook    | [3fa91961e1](https://linux-hardware.org/?probe=3fa91961e1) | Jun 07, 2020 |
| HP            | ENVY 17                     | Notebook    | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | Notebook    | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Acer          | Aspire ZC-105               | All in one  | [42b2dbab31](https://linux-hardware.org/?probe=42b2dbab31) | Jun 01, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | Notebook    | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [fbbc2c4d98](https://linux-hardware.org/?probe=fbbc2c4d98) | May 30, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [ca71847ca1](https://linux-hardware.org/?probe=ca71847ca1) | May 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP            | ENVY 17                     | Notebook    | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP            | ENVY 17                     | Notebook    | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo        | ThinkPad X260 20F5S2HF06    | Notebook    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [49486e2abf](https://linux-hardware.org/?probe=49486e2abf) | May 24, 2020 |
| Lenovo        | ThinkPad T430 2349P74       | Notebook    | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [cdaf886b58](https://linux-hardware.org/?probe=cdaf886b58) | May 20, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [e8b5bf55c7](https://linux-hardware.org/?probe=e8b5bf55c7) | May 20, 2020 |
| ASUSTek       | S400CA                      | Notebook    | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| Dell          | 0J32FG A06                  | Desktop     | [d5d2970bc5](https://linux-hardware.org/?probe=d5d2970bc5) | May 15, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [70c167639c](https://linux-hardware.org/?probe=70c167639c) | May 15, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [9eb9f125bf](https://linux-hardware.org/?probe=9eb9f125bf) | May 15, 2020 |
| Dell          | Latitude 5400               | Notebook    | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Acer          | Swift SF315-52              | Notebook    | [39a7bd47d7](https://linux-hardware.org/?probe=39a7bd47d7) | May 12, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Dell          | 0TNXNR A01                  | Desktop     | [c16ecd859c](https://linux-hardware.org/?probe=c16ecd859c) | May 11, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [f06dc42b2a](https://linux-hardware.org/?probe=f06dc42b2a) | May 10, 2020 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [eb7d6f2ec3](https://linux-hardware.org/?probe=eb7d6f2ec3) | May 10, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [3a72ff2108](https://linux-hardware.org/?probe=3a72ff2108) | May 09, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [e9d31442df](https://linux-hardware.org/?probe=e9d31442df) | May 09, 2020 |
| ASUSTek       | S551LN                      | Notebook    | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek       | S551LN                      | Notebook    | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta        | QL3 TBD                     | Notebook    | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte      | GB-BKi7A-7500               | Notebook    | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek       | G55VW                       | Notebook    | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [2e108e8f82](https://linux-hardware.org/?probe=2e108e8f82) | May 06, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [181868c1fe](https://linux-hardware.org/?probe=181868c1fe) | May 05, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ac74330be2](https://linux-hardware.org/?probe=ac74330be2) | May 03, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| HP            | Notebook                    | Notebook    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [f5c70a1643](https://linux-hardware.org/?probe=f5c70a1643) | Apr 30, 2020 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [7db8dc0e44](https://linux-hardware.org/?probe=7db8dc0e44) | Apr 28, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6982ff0a12](https://linux-hardware.org/?probe=6982ff0a12) | Apr 25, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| Dell          | Latitude 5400               | Notebook    | [7319cff553](https://linux-hardware.org/?probe=7319cff553) | Apr 22, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| HP            | 0A80h                       | Desktop     | [f51e29fc6f](https://linux-hardware.org/?probe=f51e29fc6f) | Apr 13, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e2fabad799](https://linux-hardware.org/?probe=e2fabad799) | Apr 13, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [3db29a7f67](https://linux-hardware.org/?probe=3db29a7f67) | Apr 12, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [c6df4257a4](https://linux-hardware.org/?probe=c6df4257a4) | Apr 11, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | Notebook    | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [d39e8563ca](https://linux-hardware.org/?probe=d39e8563ca) | Apr 07, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [f309322c77](https://linux-hardware.org/?probe=f309322c77) | Apr 04, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c17da47049](https://linux-hardware.org/?probe=c17da47049) | Apr 03, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [18f447ca5d](https://linux-hardware.org/?probe=18f447ca5d) | Apr 03, 2020 |
| HP            | 8433 11                     | Desktop     | [e20dd4e4a3](https://linux-hardware.org/?probe=e20dd4e4a3) | Apr 02, 2020 |
| HP            | 8433 11                     | Desktop     | [eafaace7ee](https://linux-hardware.org/?probe=eafaace7ee) | Apr 02, 2020 |
| HP            | 8433 11                     | Desktop     | [0e29f294ba](https://linux-hardware.org/?probe=0e29f294ba) | Apr 02, 2020 |
| HP            | 84EE 1100                   | All in one  | [870857c93c](https://linux-hardware.org/?probe=870857c93c) | Mar 30, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5b8ef620f7](https://linux-hardware.org/?probe=5b8ef620f7) | Mar 27, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [384177f515](https://linux-hardware.org/?probe=384177f515) | Mar 23, 2020 |
| HP            | Compaq 6720s                | Notebook    | [7a81993a9b](https://linux-hardware.org/?probe=7a81993a9b) | Mar 22, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [477afd03f4](https://linux-hardware.org/?probe=477afd03f4) | Mar 21, 2020 |
| Dell          | 0J32FG A06                  | Desktop     | [efb8737ca2](https://linux-hardware.org/?probe=efb8737ca2) | Mar 20, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | Notebook    | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| ASUSTek       | X750JB                      | Notebook    | [6d8e7e2bf9](https://linux-hardware.org/?probe=6d8e7e2bf9) | Mar 15, 2020 |
| MSI           | Z270-A PRO                  | Desktop     | [5e41eb4c66](https://linux-hardware.org/?probe=5e41eb4c66) | Mar 14, 2020 |
| Dell          | Latitude 5400               | Notebook    | [3bda0aef33](https://linux-hardware.org/?probe=3bda0aef33) | Mar 14, 2020 |
| HP            | 2000                        | Notebook    | [fa3539bb75](https://linux-hardware.org/?probe=fa3539bb75) | Mar 14, 2020 |
| Standard      | MT40II                      | Notebook    | [f11c251d38](https://linux-hardware.org/?probe=f11c251d38) | Mar 13, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [210b1c0abf](https://linux-hardware.org/?probe=210b1c0abf) | Mar 13, 2020 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [9ca13583bb](https://linux-hardware.org/?probe=9ca13583bb) | Mar 09, 2020 |
| Dell          | Latitude E6420              | Notebook    | [7653562a2f](https://linux-hardware.org/?probe=7653562a2f) | Mar 07, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [c4b9b4ab26](https://linux-hardware.org/?probe=c4b9b4ab26) | Mar 07, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e008a514e](https://linux-hardware.org/?probe=1e008a514e) | Mar 06, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [01c8982ddb](https://linux-hardware.org/?probe=01c8982ddb) | Mar 06, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [4b844d95eb](https://linux-hardware.org/?probe=4b844d95eb) | Mar 05, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [b88f46d2eb](https://linux-hardware.org/?probe=b88f46d2eb) | Mar 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1dba6c5acf](https://linux-hardware.org/?probe=1dba6c5acf) | Mar 03, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [5a7b311c84](https://linux-hardware.org/?probe=5a7b311c84) | Mar 02, 2020 |
| ASUSTek       | N751JK                      | Notebook    | [a08a81ed83](https://linux-hardware.org/?probe=a08a81ed83) | Mar 01, 2020 |
| eMachines     | EL1852G                     | Desktop     | [e90ac3f652](https://linux-hardware.org/?probe=e90ac3f652) | Feb 27, 2020 |
| HP            | ENVY x360 Convertible       | Convertible | [d98a9e0c48](https://linux-hardware.org/?probe=d98a9e0c48) | Feb 27, 2020 |
| Intel         | DQ965CO AAD34641-506        | Desktop     | [3c3c53b8e5](https://linux-hardware.org/?probe=3c3c53b8e5) | Feb 26, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [45382a84f3](https://linux-hardware.org/?probe=45382a84f3) | Feb 21, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [002a2b6abe](https://linux-hardware.org/?probe=002a2b6abe) | Feb 21, 2020 |
| HP            | 2215                        | Desktop     | [f9ecf106d2](https://linux-hardware.org/?probe=f9ecf106d2) | Feb 19, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [9e101537c5](https://linux-hardware.org/?probe=9e101537c5) | Feb 17, 2020 |
| Acer          | Veriton L4610G              | Desktop     | [e38723516e](https://linux-hardware.org/?probe=e38723516e) | Feb 17, 2020 |
| Acer          | Veriton L4610G              | Desktop     | [aef314a65c](https://linux-hardware.org/?probe=aef314a65c) | Feb 17, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [31a6b6bac8](https://linux-hardware.org/?probe=31a6b6bac8) | Feb 15, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [6cfda70306](https://linux-hardware.org/?probe=6cfda70306) | Feb 15, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [ac2755b222](https://linux-hardware.org/?probe=ac2755b222) | Feb 12, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [317f9ded14](https://linux-hardware.org/?probe=317f9ded14) | Feb 12, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [81d2b1c515](https://linux-hardware.org/?probe=81d2b1c515) | Jan 25, 2020 |
| Intel         | ChiefRiver                  | Desktop     | [1ca590a614](https://linux-hardware.org/?probe=1ca590a614) | Jan 22, 2020 |
| Unknown       | Unknown                     | Notebook    | [5603e706a3](https://linux-hardware.org/?probe=5603e706a3) | Jan 19, 2020 |
| Dell          | 0C27VV A01                  | Desktop     | [b896b0fef0](https://linux-hardware.org/?probe=b896b0fef0) | Jan 18, 2020 |
| Gigabyte      | MSH87TN-00                  | Desktop     | [624e731bcd](https://linux-hardware.org/?probe=624e731bcd) | Jan 16, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [912a2fc0df](https://linux-hardware.org/?probe=912a2fc0df) | Jan 16, 2020 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [df0bc17152](https://linux-hardware.org/?probe=df0bc17152) | Jan 13, 2020 |
| HP            | 2000                        | Notebook    | [adde2680e0](https://linux-hardware.org/?probe=adde2680e0) | Jan 08, 2020 |
| Lenovo        | ThinkPad T530 23943V0       | Notebook    | [fdb43e275c](https://linux-hardware.org/?probe=fdb43e275c) | Jan 05, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [ae8aac83f4](https://linux-hardware.org/?probe=ae8aac83f4) | Jan 05, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [282e4941e2](https://linux-hardware.org/?probe=282e4941e2) | Dec 27, 2019 |
| HP            | Compaq 8460p USAO           | Notebook    | [3eab448396](https://linux-hardware.org/?probe=3eab448396) | Dec 21, 2019 |
| ASUSTek       | N751JK                      | Notebook    | [a6b5f083ca](https://linux-hardware.org/?probe=a6b5f083ca) | Nov 21, 2019 |
| ASUSTek       | N751JK                      | Notebook    | [2c44aa3122](https://linux-hardware.org/?probe=2c44aa3122) | Nov 21, 2019 |
| Supermicro    | X9DRT                       | Server      | [f5f0a90676](https://linux-hardware.org/?probe=f5f0a90676) | Nov 19, 2019 |
| Dell          | Inspiron 5559               | Notebook    | [6571c933d2](https://linux-hardware.org/?probe=6571c933d2) | Mar 08, 2019 |
| ASUSTek       | T102HA                      | Tablet      | [7c47ab2fd4](https://linux-hardware.org/?probe=7c47ab2fd4) | Jun 14, 2018 |
| Dell          | 0G9322                      | Desktop     | [62b841a44f](https://linux-hardware.org/?probe=62b841a44f) | Jun 08, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_Budgie/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Budgie 20.04 | 258       | 36.96%  |
| Ubuntu Budgie 22.04 | 139       | 19.91%  |
| Ubuntu Budgie 20.10 | 61        | 8.74%   |
| Ubuntu Budgie 21.10 | 57        | 8.17%   |
| Ubuntu Budgie 18.04 | 41        | 5.87%   |
| Ubuntu Budgie 22.10 | 40        | 5.73%   |
| Ubuntu Budgie 21.04 | 37        | 5.3%    |
| Ubuntu Budgie 19.10 | 29        | 4.15%   |
| Ubuntu Budgie 23.04 | 25        | 3.58%   |
| Ubuntu Budgie 23.10 | 6         | 0.86%   |
| Ubuntu Budgie       | 3         | 0.43%   |
| Ubuntu Budgie 16.04 | 2         | 0.29%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 665       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 27        | 3.53%   |
| 5.3.0-40-generic  | 15        | 1.96%   |
| 5.13.0-22-generic | 14        | 1.83%   |
| 5.4.0-40-generic  | 13        | 1.7%    |
| 5.15.0-27-generic | 11        | 1.44%   |
| 6.2.0-20-generic  | 10        | 1.31%   |
| 5.4.0-52-generic  | 10        | 1.31%   |
| 5.4.0-37-generic  | 10        | 1.31%   |
| 5.13.0-39-generic | 10        | 1.31%   |
| 5.13.0-19-generic | 10        | 1.31%   |
| 5.4.0-58-generic  | 9         | 1.18%   |
| 5.4.0-48-generic  | 9         | 1.18%   |
| 5.4.0-29-generic  | 9         | 1.18%   |
| 5.15.0-52-generic | 9         | 1.18%   |
| 5.8.0-48-generic  | 8         | 1.05%   |
| 5.8.0-44-generic  | 8         | 1.05%   |
| 5.8.0-41-generic  | 8         | 1.05%   |
| 5.13.0-40-generic | 8         | 1.05%   |
| 5.13.0-30-generic | 8         | 1.05%   |
| 5.13.0-28-generic | 8         | 1.05%   |
| 5.11.0-41-generic | 8         | 1.05%   |
| 5.8.0-43-generic  | 7         | 0.92%   |
| 5.4.0-47-generic  | 7         | 0.92%   |
| 5.4.0-33-generic  | 7         | 0.92%   |
| 5.4.0-31-generic  | 7         | 0.92%   |
| 5.19.0-46-generic | 7         | 0.92%   |
| 5.19.0-38-generic | 7         | 0.92%   |
| 5.19.0-35-generic | 7         | 0.92%   |
| 5.19.0-26-generic | 7         | 0.92%   |
| 5.15.0-50-generic | 7         | 0.92%   |
| 5.15.0-46-generic | 7         | 0.92%   |
| 5.13.0-35-generic | 7         | 0.92%   |
| 6.2.0-26-generic  | 6         | 0.78%   |
| 5.8.0-53-generic  | 6         | 0.78%   |
| 5.8.0-45-generic  | 6         | 0.78%   |
| 5.8.0-29-generic  | 6         | 0.78%   |
| 5.15.0-56-generic | 6         | 0.78%   |
| 5.15.0-48-generic | 6         | 0.78%   |
| 5.15.0-30-generic | 6         | 0.78%   |
| 6.5.0-9-generic   | 5         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 176       | 24.79%  |
| 5.15.0  | 113       | 15.92%  |
| 5.8.0   | 89        | 12.54%  |
| 5.13.0  | 82        | 11.55%  |
| 5.19.0  | 62        | 8.73%   |
| 5.11.0  | 54        | 7.61%   |
| 5.3.0   | 42        | 5.92%   |
| 6.2.0   | 36        | 5.07%   |
| 4.15.0  | 14        | 1.97%   |
| 6.5.0   | 5         | 0.7%    |
| 5.6.0   | 3         | 0.42%   |
| 5.0.0   | 3         | 0.42%   |
| 5.6.7   | 2         | 0.28%   |
| 5.12.0  | 2         | 0.28%   |
| 5.10.0  | 2         | 0.28%   |
| 4.18.0  | 2         | 0.28%   |
| 6.5.7   | 1         | 0.14%   |
| 6.5.5   | 1         | 0.14%   |
| 6.3.1   | 1         | 0.14%   |
| 6.1.0   | 1         | 0.14%   |
| 5.9.1   | 1         | 0.14%   |
| 5.9.0   | 1         | 0.14%   |
| 5.8.6   | 1         | 0.14%   |
| 5.8.11  | 1         | 0.14%   |
| 5.7.7   | 1         | 0.14%   |
| 5.5.8   | 1         | 0.14%   |
| 5.5.0   | 1         | 0.14%   |
| 5.18.8  | 1         | 0.14%   |
| 5.17.2  | 1         | 0.14%   |
| 5.17.1  | 1         | 0.14%   |
| 5.16.2  | 1         | 0.14%   |
| 5.16.14 | 1         | 0.14%   |
| 5.15.92 | 1         | 0.14%   |
| 5.15.11 | 1         | 0.14%   |
| 5.14.2  | 1         | 0.14%   |
| 5.14.1  | 1         | 0.14%   |
| 5.10.11 | 1         | 0.14%   |
| 4.4.178 | 1         | 0.14%   |
| 4.4.0   | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 176       | 24.82%  |
| 5.15    | 115       | 16.22%  |
| 5.8     | 91        | 12.83%  |
| 5.13    | 82        | 11.57%  |
| 5.19    | 62        | 8.74%   |
| 5.11    | 54        | 7.62%   |
| 5.3     | 42        | 5.92%   |
| 6.2     | 36        | 5.08%   |
| 4.15    | 14        | 1.97%   |
| 6.5     | 7         | 0.99%   |
| 5.6     | 5         | 0.71%   |
| 5.10    | 3         | 0.42%   |
| 5.0     | 3         | 0.42%   |
| 5.9     | 2         | 0.28%   |
| 5.5     | 2         | 0.28%   |
| 5.17    | 2         | 0.28%   |
| 5.16    | 2         | 0.28%   |
| 5.12    | 2         | 0.28%   |
| 4.4     | 2         | 0.28%   |
| 4.18    | 2         | 0.28%   |
| 6.3     | 1         | 0.14%   |
| 6.1     | 1         | 0.14%   |
| 5.7     | 1         | 0.14%   |
| 5.18    | 1         | 0.14%   |
| 5.14    | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 652       | 98.05%  |
| i686    | 9         | 1.35%   |
| aarch64 | 3         | 0.45%   |
| armv7l  | 1         | 0.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Budgie     | 645       | 96.99%  |
| GNOME      | 15        | 2.26%   |
| XFCE       | 1         | 0.15%   |
| X-Cinnamon | 1         | 0.15%   |
| MATE       | 1         | 0.15%   |
| KDE5       | 1         | 0.15%   |
| KDE        | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 646       | 96.85%  |
| Wayland | 17        | 2.55%   |
| Tty     | 4         | 0.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 264       | 39.11%  |
| Unknown | 256       | 37.93%  |
| TDM     | 92        | 13.63%  |
| GDM     | 36        | 5.33%   |
| GDM3    | 24        | 3.56%   |
| SDDM    | 3         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 250       | 37.54%  |
| de_DE   | 82        | 12.31%  |
| fr_FR   | 46        | 6.91%   |
| pt_BR   | 41        | 6.16%   |
| en_GB   | 36        | 5.41%   |
| en_CA   | 24        | 3.6%    |
| it_IT   | 20        | 3%      |
| ru_RU   | 16        | 2.4%    |
| en_AU   | 14        | 2.1%    |
| es_ES   | 13        | 1.95%   |
| en_IN   | 13        | 1.95%   |
| es_AR   | 10        | 1.5%    |
| es_MX   | 9         | 1.35%   |
| C       | 7         | 1.05%   |
| pl_PL   | 6         | 0.9%    |
| Unknown | 6         | 0.9%    |
| pt_PT   | 5         | 0.75%   |
| es_CL   | 5         | 0.75%   |
| hu_HU   | 4         | 0.6%    |
| zh_TW   | 3         | 0.45%   |
| uk_UA   | 3         | 0.45%   |
| nl_NL   | 3         | 0.45%   |
| fr_BE   | 3         | 0.45%   |
| es_CO   | 3         | 0.45%   |
| en_IE   | 3         | 0.45%   |
| de_AT   | 3         | 0.45%   |
| cs_CZ   | 3         | 0.45%   |
| ja_JP   | 2         | 0.3%    |
| fr_CH   | 2         | 0.3%    |
| fi_FI   | 2         | 0.3%    |
| en_ZA   | 2         | 0.3%    |
| en_SG   | 2         | 0.3%    |
| de_CH   | 2         | 0.3%    |
| zh_CN   | 1         | 0.15%   |
| tr_TR   | 1         | 0.15%   |
| sv_SE   | 1         | 0.15%   |
| ru_UA   | 1         | 0.15%   |
| ro_RO   | 1         | 0.15%   |
| nl_BE   | 1         | 0.15%   |
| nb_NO   | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 352       | 51.61%  |
| BIOS | 330       | 48.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 597       | 89.24%  |
| Zfs     | 21        | 3.14%   |
| Tmpfs   | 20        | 2.99%   |
| Overlay | 17        | 2.54%   |
| Btrfs   | 10        | 1.49%   |
| Xfs     | 3         | 0.45%   |
| Jfs     | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 324       | 47.79%  |
| GPT     | 303       | 44.69%  |
| MBR     | 51        | 7.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 584       | 86.52%  |
| Yes       | 91        | 13.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 453       | 67.11%  |
| Yes       | 222       | 32.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 97        | 14.59%  |
| Hewlett-Packard         | 96        | 14.44%  |
| Lenovo                  | 92        | 13.83%  |
| Dell                    | 79        | 11.88%  |
| TUXEDO                  | 45        | 6.77%   |
| Gigabyte Technology     | 37        | 5.56%   |
| MSI                     | 36        | 5.41%   |
| Apple                   | 34        | 5.11%   |
| Acer                    | 27        | 4.06%   |
| ASRock                  | 15        | 2.26%   |
| Intel                   | 10        | 1.5%    |
| Fujitsu                 | 8         | 1.2%    |
| HUAWEI                  | 7         | 1.05%   |
| Google                  | 7         | 1.05%   |
| Unknown                 | 7         | 1.05%   |
| Sony                    | 6         | 0.9%    |
| Samsung Electronics     | 6         | 0.9%    |
| Toshiba                 | 5         | 0.75%   |
| Raspberry Pi Foundation | 3         | 0.45%   |
| Packard Bell            | 3         | 0.45%   |
| Timi                    | 2         | 0.3%    |
| Standard                | 2         | 0.3%    |
| Razer                   | 2         | 0.3%    |
| Positivo                | 2         | 0.3%    |
| Microsoft               | 2         | 0.3%    |
| eMachines               | 2         | 0.3%    |
| Biostar                 | 2         | 0.3%    |
| BANGHO                  | 2         | 0.3%    |
| AZW                     | 2         | 0.3%    |
| Alienware               | 2         | 0.3%    |
| ZOTAC                   | 1         | 0.15%   |
| Viglen                  | 1         | 0.15%   |
| THUNDEROBOT             | 1         | 0.15%   |
| Thomson                 | 1         | 0.15%   |
| Teclast                 | 1         | 0.15%   |
| Supermicro              | 1         | 0.15%   |
| Radxa                   | 1         | 0.15%   |
| Quanta                  | 1         | 0.15%   |
| Pegatron                | 1         | 0.15%   |
| PCSMART                 | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 17        | 2.56%   |
| ASUS All Series                    | 8         | 1.2%    |
| TUXEDO Pulse 15 Gen1               | 4         | 0.6%    |
| TUXEDO InfinityBook S 15 Gen6      | 3         | 0.45%   |
| TUXEDO Aura 15 Gen1                | 3         | 0.45%   |
| HP Pavilion g6                     | 3         | 0.45%   |
| HP Notebook                        | 3         | 0.45%   |
| Dell OptiPlex 780                  | 3         | 0.45%   |
| Dell Latitude E6420                | 3         | 0.45%   |
| TUXEDO Polaris 15 AMD Gen1         | 2         | 0.3%    |
| TUXEDO InfinityBook S 14 Gen6      | 2         | 0.3%    |
| TUXEDO InfinityBook Pro 14 Gen6    | 2         | 0.3%    |
| TUXEDO Book XP1511                 | 2         | 0.3%    |
| Standard MT40II                    | 2         | 0.3%    |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 2         | 0.3%    |
| MSI MS-7C84                        | 2         | 0.3%    |
| Lenovo ThinkPad E15 20RD003KHV     | 2         | 0.3%    |
| Lenovo ThinkBook 14-IML 20RV       | 2         | 0.3%    |
| Lenovo IdeaPad C340-14API 81N6     | 2         | 0.3%    |
| Lenovo IdeaPad 5 15ARE05 81YQ      | 2         | 0.3%    |
| Lenovo IdeaPad 330S-15ARR 81FB     | 2         | 0.3%    |
| Lenovo IdeaPad 320-15IKB 80XL      | 2         | 0.3%    |
| Lenovo IdeaPad 110-15ISK 80UD      | 2         | 0.3%    |
| Lenovo G500 20236                  | 2         | 0.3%    |
| Lenovo G50-45 80E3                 | 2         | 0.3%    |
| Intel DP55WB AAE64798-206          | 2         | 0.3%    |
| HP ZBook Studio G3                 | 2         | 0.3%    |
| HP ZBook 15 G4                     | 2         | 0.3%    |
| HP Pavilion dv7                    | 2         | 0.3%    |
| HP ENVY 17                         | 2         | 0.3%    |
| HP ENVY 15                         | 2         | 0.3%    |
| HP EliteDesk 800 G1 SFF            | 2         | 0.3%    |
| HP EliteBook 840 G8 Notebook PC    | 2         | 0.3%    |
| HP EliteBook 840 G3                | 2         | 0.3%    |
| HP Compaq Elite 8300 SFF           | 2         | 0.3%    |
| HP 2000                            | 2         | 0.3%    |
| Gigabyte Z68M-D2H                  | 2         | 0.3%    |
| Gigabyte AB350-Gaming 3            | 2         | 0.3%    |
| Dell XPS 13 9380                   | 2         | 0.3%    |
| Dell Precision WorkStation T3500   | 2         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 38        | 5.71%   |
| Dell Latitude       | 27        | 4.06%   |
| Lenovo IdeaPad      | 23        | 3.46%   |
| Dell Inspiron       | 19        | 2.86%   |
| HP Pavilion         | 18        | 2.71%   |
| Acer Aspire         | 17        | 2.56%   |
| Unknown             | 17        | 2.56%   |
| HP EliteBook        | 15        | 2.26%   |
| TUXEDO InfinityBook | 11        | 1.65%   |
| Dell XPS            | 11        | 1.65%   |
| ASUS ROG            | 11        | 1.65%   |
| Dell OptiPlex       | 10        | 1.5%    |
| ASUS VivoBook       | 10        | 1.5%    |
| ASUS PRIME          | 10        | 1.5%    |
| HP ENVY             | 8         | 1.2%    |
| ASUS All            | 8         | 1.2%    |
| HP Compaq           | 7         | 1.05%   |
| TUXEDO Polaris      | 6         | 0.9%    |
| TUXEDO Book         | 6         | 0.9%    |
| HP ZBook            | 6         | 0.9%    |
| HP ProBook          | 6         | 0.9%    |
| HP Laptop           | 6         | 0.9%    |
| Dell Precision      | 6         | 0.9%    |
| Toshiba Satellite   | 5         | 0.75%   |
| HP Spectre          | 5         | 0.75%   |
| HP EliteDesk        | 5         | 0.75%   |
| Acer Swift          | 5         | 0.75%   |
| TUXEDO Pulse        | 4         | 0.6%    |
| Lenovo ThinkBook    | 4         | 0.6%    |
| ASUS ASUS           | 4         | 0.6%    |
| TUXEDO Aura         | 3         | 0.45%   |
| RPi Raspberry       | 3         | 0.45%   |
| Lenovo Yoga         | 3         | 0.45%   |
| HP Notebook         | 3         | 0.45%   |
| Fujitsu LIFEBOOK    | 3         | 0.45%   |
| Fujitsu ESPRIMO     | 3         | 0.45%   |
| Dell Vostro         | 3         | 0.45%   |
| ASUS TUF            | 3         | 0.45%   |
| ASUS P8H77-M        | 3         | 0.45%   |
| Apple MacBookPro8   | 3         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 76        | 11.43%  |
| 2020    | 75        | 11.28%  |
| 2018    | 75        | 11.28%  |
| 2021    | 53        | 7.97%   |
| 2017    | 46        | 6.92%   |
| 2011    | 44        | 6.62%   |
| 2014    | 42        | 6.32%   |
| 2013    | 42        | 6.32%   |
| 2012    | 40        | 6.02%   |
| 2016    | 37        | 5.56%   |
| 2015    | 34        | 5.11%   |
| 2010    | 29        | 4.36%   |
| 2009    | 19        | 2.86%   |
| 2008    | 18        | 2.71%   |
| 2022    | 14        | 2.11%   |
| 2007    | 14        | 2.11%   |
| 2023    | 5         | 0.75%   |
| Unknown | 2         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 417       | 62.71%  |
| Desktop        | 189       | 28.42%  |
| Convertible    | 18        | 2.71%   |
| All in one     | 17        | 2.56%   |
| Mini pc        | 11        | 1.65%   |
| Tablet         | 8         | 1.2%    |
| System on chip | 4         | 0.6%    |
| Server         | 1         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 616       | 92.35%  |
| Enabled  | 51        | 7.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 657       | 98.8%   |
| Yes  | 8         | 1.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 169       | 25.15%  |
| 4.01-8.0        | 158       | 23.51%  |
| 8.01-16.0       | 114       | 16.96%  |
| 3.01-4.0        | 101       | 15.03%  |
| 32.01-64.0      | 67        | 9.97%   |
| 64.01-256.0     | 31        | 4.61%   |
| 1.01-2.0        | 13        | 1.93%   |
| 24.01-32.0      | 11        | 1.64%   |
| 2.01-3.0        | 5         | 0.74%   |
| 0.51-1.0        | 2         | 0.3%    |
| More than 256.0 | 1         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 229       | 31.63%  |
| 1.01-2.0   | 192       | 26.52%  |
| 4.01-8.0   | 135       | 18.65%  |
| 3.01-4.0   | 112       | 15.47%  |
| 8.01-16.0  | 36        | 4.97%   |
| 0.51-1.0   | 10        | 1.38%   |
| 16.01-24.0 | 6         | 0.83%   |
| 24.01-32.0 | 2         | 0.28%   |
| 32.01-64.0 | 1         | 0.14%   |
| 0.01-0.5   | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 402       | 59.2%   |
| 2      | 173       | 25.48%  |
| 3      | 53        | 7.81%   |
| 4      | 22        | 3.24%   |
| 5      | 14        | 2.06%   |
| 8      | 5         | 0.74%   |
| 6      | 5         | 0.74%   |
| 0      | 2         | 0.29%   |
| 11     | 1         | 0.15%   |
| 9      | 1         | 0.15%   |
| 7      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 447       | 66.92%  |
| Yes       | 221       | 33.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 558       | 83.66%  |
| No        | 109       | 16.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 560       | 83.83%  |
| No        | 108       | 16.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 478       | 71.34%  |
| No        | 192       | 28.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 124       | 18.62%  |
| Germany            | 97        | 14.56%  |
| France             | 49        | 7.36%   |
| Brazil             | 46        | 6.91%   |
| UK                 | 24        | 3.6%    |
| Italy              | 24        | 3.6%    |
| Canada             | 22        | 3.3%    |
| Russia             | 17        | 2.55%   |
| India              | 16        | 2.4%    |
| Netherlands        | 15        | 2.25%   |
| Spain              | 14        | 2.1%    |
| Poland             | 14        | 2.1%    |
| Australia          | 14        | 2.1%    |
| Argentina          | 14        | 2.1%    |
| Mexico             | 12        | 1.8%    |
| Switzerland        | 10        | 1.5%    |
| Austria            | 9         | 1.35%   |
| Ukraine            | 8         | 1.2%    |
| Portugal           | 7         | 1.05%   |
| Sweden             | 6         | 0.9%    |
| Norway             | 6         | 0.9%    |
| Japan              | 6         | 0.9%    |
| Hungary            | 6         | 0.9%    |
| Belgium            | 6         | 0.9%    |
| Greece             | 5         | 0.75%   |
| Colombia           | 5         | 0.75%   |
| Chile              | 5         | 0.75%   |
| South Africa       | 4         | 0.6%    |
| Romania            | 4         | 0.6%    |
| Ireland            | 4         | 0.6%    |
| Finland            | 4         | 0.6%    |
| Czechia            | 4         | 0.6%    |
| Croatia            | 4         | 0.6%    |
| Turkey             | 3         | 0.45%   |
| Slovenia           | 3         | 0.45%   |
| Saudi Arabia       | 3         | 0.45%   |
| Iran               | 3         | 0.45%   |
| Indonesia          | 3         | 0.45%   |
| Dominican Republic | 3         | 0.45%   |
| Taiwan             | 2         | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Berlin             | 9         | 1.31%   |
| Sao Paulo          | 8         | 1.16%   |
| Moscow             | 7         | 1.02%   |
| Ravensburg         | 5         | 0.73%   |
| Hamburg            | 5         | 0.73%   |
| Budapest           | 5         | 0.73%   |
| Brasília          | 5         | 0.73%   |
| Athens             | 5         | 0.73%   |
| Zurich             | 4         | 0.58%   |
| Vienna             | 4         | 0.58%   |
| Sydney             | 4         | 0.58%   |
| Paris              | 4         | 0.58%   |
| Munich             | 4         | 0.58%   |
| Montreal           | 4         | 0.58%   |
| Frankfurt am Main  | 4         | 0.58%   |
| Dublin             | 4         | 0.58%   |
| Barcelona          | 4         | 0.58%   |
| Zagreb             | 3         | 0.44%   |
| Warsaw             | 3         | 0.44%   |
| Tehran             | 3         | 0.44%   |
| St Petersburg      | 3         | 0.44%   |
| Santo Domingo Este | 3         | 0.44%   |
| San Francisco      | 3         | 0.44%   |
| Rio de Janeiro     | 3         | 0.44%   |
| Pune               | 3         | 0.44%   |
| Prague             | 3         | 0.44%   |
| New York           | 3         | 0.44%   |
| Mumbai             | 3         | 0.44%   |
| Milan              | 3         | 0.44%   |
| Miami              | 3         | 0.44%   |
| Los Angeles        | 3         | 0.44%   |
| Lisbon             | 3         | 0.44%   |
| Kyiv               | 3         | 0.44%   |
| Bogotá            | 3         | 0.44%   |
| Austin             | 3         | 0.44%   |
| Wolfsburg          | 2         | 0.29%   |
| Victoria           | 2         | 0.29%   |
| Vancouver          | 2         | 0.29%   |
| Uman               | 2         | 0.29%   |
| Trondheim          | 2         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 187       | 276    | 18.93%  |
| WDC                         | 127       | 180    | 12.85%  |
| Seagate                     | 127       | 184    | 12.85%  |
| Toshiba                     | 70        | 81     | 7.09%   |
| SanDisk                     | 52        | 65     | 5.26%   |
| Unknown                     | 49        | 58     | 4.96%   |
| Kingston                    | 41        | 53     | 4.15%   |
| Crucial                     | 32        | 41     | 3.24%   |
| Intel                       | 29        | 46     | 2.94%   |
| SK hynix                    | 25        | 27     | 2.53%   |
| Hitachi                     | 24        | 31     | 2.43%   |
| Micron Technology           | 19        | 23     | 1.92%   |
| HGST                        | 15        | 19     | 1.52%   |
| Apple                       | 15        | 18     | 1.52%   |
| Phison                      | 14        | 19     | 1.42%   |
| A-DATA Technology           | 14        | 19     | 1.42%   |
| China                       | 13        | 18     | 1.32%   |
| SPCC                        | 11        | 13     | 1.11%   |
| PNY                         | 10        | 13     | 1.01%   |
| KIOXIA                      | 6         | 7      | 0.61%   |
| JMicron Technology          | 6         | 7      | 0.61%   |
| Transcend                   | 5         | 5      | 0.51%   |
| OCZ                         | 5         | 8      | 0.51%   |
| Micron/Crucial Technology   | 5         | 5      | 0.51%   |
| Patriot                     | 4         | 6      | 0.4%    |
| Silicon Motion              | 3         | 5      | 0.3%    |
| SABRENT                     | 3         | 4      | 0.3%    |
| Netac                       | 3         | 4      | 0.3%    |
| Maxtor                      | 3         | 6      | 0.3%    |
| LITEON                      | 3         | 3      | 0.3%    |
| Intenso                     | 3         | 4      | 0.3%    |
| Teclast                     | 2         | 3      | 0.2%    |
| Realtek Semiconductor       | 2         | 3      | 0.2%    |
| Phison Electronics          | 2         | 2      | 0.2%    |
| Lenovo                      | 2         | 2      | 0.2%    |
| LaCie                       | 2         | 2      | 0.2%    |
| Kingston Technology Company | 2         | 2      | 0.2%    |
| KingSpec                    | 2         | 2      | 0.2%    |
| HS-SSD-C100                 | 2         | 2      | 0.2%    |
| Hewlett-Packard             | 2         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                            | 10        | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 9         | 0.81%   |
| Samsung SSD 860 EVO 500GB                         | 9         | 0.81%   |
| Samsung NVMe SSD Drive 512GB                      | 9         | 0.81%   |
| Toshiba MQ01ABD100 1TB                            | 8         | 0.72%   |
| Seagate ST9500325AS 500GB                         | 8         | 0.72%   |
| Samsung NVMe SSD Drive 500GB                      | 8         | 0.72%   |
| Unknown MMC Card  32GB                            | 7         | 0.63%   |
| Toshiba MQ04ABF100 1TB                            | 7         | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB                    | 7         | 0.63%   |
| Samsung SSD 860 QVO 1TB                           | 7         | 0.63%   |
| Samsung SSD 850 EVO 500GB                         | 7         | 0.63%   |
| Samsung NVMe SSD Drive 1TB                        | 7         | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 7         | 0.63%   |
| Kingston SA400S37480G 480GB SSD                   | 7         | 0.63%   |
| Kingston SA400S37240G 240GB SSD                   | 7         | 0.63%   |
| Unknown SD/MMC/MS PRO 16GB                        | 6         | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB                    | 6         | 0.54%   |
| Samsung SSD 860 EVO M.2 500GB                     | 6         | 0.54%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 6         | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 5         | 0.45%   |
| SK hynix NVMe SSD Drive 256GB                     | 5         | 0.45%   |
| Seagate ST500LT012-1DG142 500GB                   | 5         | 0.45%   |
| Seagate ST500DM002-1BD142 500GB                   | 5         | 0.45%   |
| Seagate ST2000DM008-2FR102 2TB                    | 5         | 0.45%   |
| SanDisk SDSSDA240G 240GB                          | 5         | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB                    | 5         | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB                      | 5         | 0.45%   |
| Samsung SSD 860 EVO M.2 250GB                     | 5         | 0.45%   |
| Samsung SSD 840 EVO 250GB                         | 5         | 0.45%   |
| Crucial CT480BX500SSD1 480GB                      | 5         | 0.45%   |
| Crucial CT240BX500SSD1 240GB                      | 5         | 0.45%   |
| WDC WD5000AAKS-00UU3A0 500GB                      | 4         | 0.36%   |
| Unknown MMC Card  16GB                            | 4         | 0.36%   |
| Seagate ST2000DM006-2DM164 2TB                    | 4         | 0.36%   |
| Seagate ST2000DM001-1ER164 2TB                    | 4         | 0.36%   |
| Seagate ST2000DM001-1CH164 2TB                    | 4         | 0.36%   |
| Seagate ST1000LM048-2E7172 1TB                    | 4         | 0.36%   |
| SanDisk SDSSDA120G 120GB                          | 4         | 0.36%   |
| SanDisk NVMe SSD Drive 512GB                      | 4         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 124       | 180    | 36.47%  |
| WDC                 | 94        | 141    | 27.65%  |
| Toshiba             | 55        | 59     | 16.18%  |
| Hitachi             | 24        | 31     | 7.06%   |
| HGST                | 15        | 19     | 4.41%   |
| Samsung Electronics | 8         | 9      | 2.35%   |
| Unknown             | 6         | 6      | 1.76%   |
| Apple               | 6         | 6      | 1.76%   |
| Maxtor              | 3         | 6      | 0.88%   |
| WD MediaMax         | 1         | 1      | 0.29%   |
| USB3.0              | 1         | 1      | 0.29%   |
| TDAS                | 1         | 3      | 0.29%   |
| Fujitsu             | 1         | 1      | 0.29%   |
| ASMT109x            | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 93        | 136    | 27.11%  |
| Kingston            | 35        | 43     | 10.2%   |
| SanDisk             | 34        | 42     | 9.91%   |
| Crucial             | 29        | 38     | 8.45%   |
| WDC                 | 20        | 22     | 5.83%   |
| China               | 13        | 18     | 3.79%   |
| SPCC                | 10        | 12     | 2.92%   |
| Intel               | 10        | 10     | 2.92%   |
| A-DATA Technology   | 10        | 14     | 2.92%   |
| PNY                 | 9         | 12     | 2.62%   |
| Micron Technology   | 8         | 9      | 2.33%   |
| Apple               | 8         | 8      | 2.33%   |
| SK hynix            | 5         | 5      | 1.46%   |
| Patriot             | 4         | 6      | 1.17%   |
| OCZ                 | 4         | 4      | 1.17%   |
| Transcend           | 3         | 3      | 0.87%   |
| Toshiba             | 3         | 3      | 0.87%   |
| SABRENT             | 3         | 4      | 0.87%   |
| LITEON              | 3         | 3      | 0.87%   |
| Teclast             | 2         | 3      | 0.58%   |
| Seagate             | 2         | 2      | 0.58%   |
| Netac               | 2         | 2      | 0.58%   |
| KingSpec            | 2         | 2      | 0.58%   |
| Intenso             | 2         | 3      | 0.58%   |
| Gigabyte Technology | 2         | 2      | 0.58%   |
| Apacer              | 2         | 2      | 0.58%   |
| AMD                 | 2         | 17     | 0.58%   |
| Zheino              | 1         | 2      | 0.29%   |
| VISIPRO             | 1         | 1      | 0.29%   |
| Vaseky              | 1         | 1      | 0.29%   |
| USB30               | 1         | 1      | 0.29%   |
| Unknown             | 1         | 1      | 0.29%   |
| Union Memory        | 1         | 1      | 0.29%   |
| TO Exter            | 1         | 1      | 0.29%   |
| Plextor             | 1         | 1      | 0.29%   |
| OWC                 | 1         | 1      | 0.29%   |
| Mushkin             | 1         | 1      | 0.29%   |
| MicroFrom           | 1         | 1      | 0.29%   |
| LITEONIT            | 1         | 1      | 0.29%   |
| Lexar               | 1         | 1      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 295       | 450    | 33.26%  |
| HDD     | 283       | 464    | 31.91%  |
| NVMe    | 246       | 346    | 27.73%  |
| MMC     | 45        | 55     | 5.07%   |
| Unknown | 18        | 19     | 2.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 466       | 894    | 58.91%  |
| NVMe | 244       | 342    | 30.85%  |
| MMC  | 45        | 55     | 5.69%   |
| SAS  | 36        | 43     | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 354       | 556    | 58.22%  |
| 0.51-1.0   | 169       | 232    | 27.8%   |
| 1.01-2.0   | 46        | 73     | 7.57%   |
| 3.01-4.0   | 21        | 29     | 3.45%   |
| 2.01-3.0   | 9         | 10     | 1.48%   |
| 4.01-10.0  | 8         | 11     | 1.32%   |
| 10.01-20.0 | 1         | 3      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 206       | 30.07%  |
| 251-500        | 180       | 26.28%  |
| 501-1000       | 103       | 15.04%  |
| 51-100         | 46        | 6.72%   |
| 1001-2000      | 45        | 6.57%   |
| 21-50          | 28        | 4.09%   |
| 1-20           | 28        | 4.09%   |
| More than 3000 | 27        | 3.94%   |
| 2001-3000      | 15        | 2.19%   |
| Unknown        | 7         | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 229       | 32.44%  |
| 21-50          | 135       | 19.12%  |
| 101-250        | 123       | 17.42%  |
| 51-100         | 90        | 12.75%  |
| 251-500        | 59        | 8.36%   |
| 501-1000       | 28        | 3.97%   |
| 1001-2000      | 23        | 3.26%   |
| More than 3000 | 9         | 1.27%   |
| Unknown        | 7         | 0.99%   |
| 2001-3000      | 3         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 3         | 3      | 5.77%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 3      | 5.77%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 2      | 3.85%   |
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 2      | 3.85%   |
| WDC WD6400BPVT-60HXZT3 640GB         | 1         | 1      | 1.92%   |
| WDC WD6000HLHX-01JJPV0 600GB         | 1         | 1      | 1.92%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 2      | 1.92%   |
| WDC WD5000BPVT-00HXZT1 500GB         | 1         | 1      | 1.92%   |
| WDC WD5000AVCS-632DY1 500GB          | 1         | 1      | 1.92%   |
| WDC WD5000AAKX-329BA0 500GB          | 1         | 1      | 1.92%   |
| WDC WD4003FZEX-00Z4SA0 4TB           | 1         | 1      | 1.92%   |
| WDC WD2500BEKT-75PVMT1 250GB         | 1         | 1      | 1.92%   |
| WDC WD2500AAJS-60M0A0 250GB          | 1         | 1      | 1.92%   |
| WDC WD20EFRX-68EUZN0 2TB             | 1         | 2      | 1.92%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1         | 1      | 1.92%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 1.92%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.92%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 1.92%   |
| Toshiba MK5055GSX 500GB              | 1         | 1      | 1.92%   |
| Toshiba MK3265GSXN 320GB             | 1         | 1      | 1.92%   |
| Toshiba MK2561GSYN 250GB             | 1         | 1      | 1.92%   |
| Seagate ST9750420AS 752GB            | 1         | 1      | 1.92%   |
| Seagate ST9500423AS 500GB            | 1         | 1      | 1.92%   |
| Seagate ST500LX012-1LM162-SSHD 500GB | 1         | 1      | 1.92%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 1.92%   |
| Seagate ST5000DM000-1FK178 5TB       | 1         | 1      | 1.92%   |
| Seagate ST3500320AS 500GB            | 1         | 1      | 1.92%   |
| Seagate ST3320620AS 320GB            | 1         | 1      | 1.92%   |
| Seagate ST3160815AS 160GB            | 1         | 1      | 1.92%   |
| Seagate ST1000DX001-1NS162 1TB       | 1         | 1      | 1.92%   |
| Seagate ST1000DM003-1SB102 1TB       | 1         | 1      | 1.92%   |
| PNY SSD2SC120G3LC709B121-460I 120GB  | 1         | 1      | 1.92%   |
| Patriot Pyro m3 240GB SSD            | 1         | 1      | 1.92%   |
| Maxtor STM3250310AS 250GB            | 1         | 1      | 1.92%   |
| Maxtor 6B200M0 208GB                 | 1         | 2      | 1.92%   |
| Kingston SNS4151S316G 16GB SSD       | 1         | 1      | 1.92%   |
| HP Phison PSSBN032GA27MC1 32GB       | 1         | 1      | 1.92%   |
| Hitachi HTS545025B9SA02 250GB        | 1         | 1      | 1.92%   |
| Hitachi HDS721032CLA362 320GB        | 1         | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 18        | 18     | 34.62%  |
| WDC       | 13        | 15     | 25%     |
| Toshiba   | 8         | 8      | 15.38%  |
| HGST      | 3         | 4      | 5.77%   |
| Maxtor    | 2         | 3      | 3.85%   |
| Hitachi   | 2         | 2      | 3.85%   |
| PNY       | 1         | 1      | 1.92%   |
| Patriot   | 1         | 1      | 1.92%   |
| Kingston  | 1         | 1      | 1.92%   |
| HP Phison | 1         | 1      | 1.92%   |
| Crucial   | 1         | 1      | 1.92%   |
| China     | 1         | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 18        | 18     | 39.13%  |
| WDC     | 13        | 15     | 28.26%  |
| Toshiba | 8         | 8      | 17.39%  |
| HGST    | 3         | 4      | 6.52%   |
| Maxtor  | 2         | 3      | 4.35%   |
| Hitachi | 2         | 2      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 50     | 87.23%  |
| SSD  | 5         | 5      | 10.64%  |
| NVMe | 1         | 1      | 2.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Apple  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 413       | 852    | 57.36%  |
| Works    | 260       | 425    | 36.11%  |
| Malfunc  | 46        | 56     | 6.39%   |
| Failed   | 1         | 1      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 453       | 54.64%  |
| Samsung Electronics            | 106       | 12.79%  |
| AMD                            | 96        | 11.58%  |
| SanDisk                        | 31        | 3.74%   |
| SK hynix                       | 18        | 2.17%   |
| Phison Electronics             | 17        | 2.05%   |
| Micron Technology              | 12        | 1.45%   |
| Marvell Technology Group       | 12        | 1.45%   |
| Toshiba America Info Systems   | 11        | 1.33%   |
| Kingston Technology Company    | 9         | 1.09%   |
| Micron/Crucial Technology      | 8         | 0.97%   |
| Nvidia                         | 7         | 0.84%   |
| KIOXIA                         | 7         | 0.84%   |
| Silicon Motion                 | 6         | 0.72%   |
| JMicron Technology             | 6         | 0.72%   |
| ASMedia Technology             | 6         | 0.72%   |
| ADATA Technology               | 5         | 0.6%    |
| Realtek Semiconductor          | 3         | 0.36%   |
| Solid State Storage Technology | 2         | 0.24%   |
| Lenovo                         | 2         | 0.24%   |
| Apple                          | 2         | 0.24%   |
| Yangtze Memory Technologies    | 1         | 0.12%   |
| Union Memory (Shenzhen)        | 1         | 0.12%   |
| Transcend                      | 1         | 0.12%   |
| Silicon Image                  | 1         | 0.12%   |
| Shenzhen Longsys Electronics   | 1         | 0.12%   |
| Seagate Technology             | 1         | 0.12%   |
| OCZ Technology Group           | 1         | 0.12%   |
| Netac Technology               | 1         | 0.12%   |
| Integrated Technology Express  | 1         | 0.12%   |
| Adaptec                        | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 72        | 7.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 56        | 6.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 43        | 4.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 33        | 3.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 27        | 2.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 25        | 2.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 2.48%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 1.94%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 16        | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 15        | 1.62%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 15        | 1.62%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 15        | 1.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 1.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 12        | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 1.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 12        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 12        | 1.3%    |
| AMD 400 Series Chipset SATA Controller                                         | 12        | 1.3%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 11        | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 1.08%   |
| Intel SATA Controller [RAID mode]                                              | 10        | 1.08%   |
| Intel SSD 660P Series                                                          | 9         | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 0.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9         | 0.97%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 9         | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9         | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                         | 9         | 0.97%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 8         | 0.86%   |
| Phison E12 NVMe Controller                                                     | 8         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8         | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 0.76%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 7         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 7         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 7         | 0.76%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 6         | 0.65%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 6         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 474       | 56.9%   |
| NVMe | 246       | 29.53%  |
| IDE  | 63        | 7.56%   |
| RAID | 48        | 5.76%   |
| SAS  | 2         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 536       | 80.6%   |
| AMD    | 125       | 18.8%   |
| ARM    | 4         | 0.6%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 18        | 2.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 2.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 10        | 1.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 1.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 1.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 1.05%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.9%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.9%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 0.9%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 0.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 0.75%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 5         | 0.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.75%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 0.75%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.75%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 4         | 0.6%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.6%    |
| Intel Core i7-4770 CPU @ 3.40GHz              | 4         | 0.6%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 0.6%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 0.6%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.6%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.6%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 0.6%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 0.6%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.6%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.6%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 3         | 0.45%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 3         | 0.45%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 189       | 28.38%  |
| Intel Core i5                  | 147       | 22.07%  |
| Other                          | 45        | 6.76%   |
| Intel Core i3                  | 41        | 6.16%   |
| AMD Ryzen 5                    | 36        | 5.41%   |
| AMD Ryzen 7                    | 32        | 4.8%    |
| Intel Celeron                  | 28        | 4.2%    |
| Intel Core 2 Duo               | 21        | 3.15%   |
| Intel Xeon                     | 13        | 1.95%   |
| Intel Pentium                  | 13        | 1.95%   |
| Intel Atom                     | 11        | 1.65%   |
| AMD Ryzen 9                    | 9         | 1.35%   |
| AMD Ryzen 3                    | 8         | 1.2%    |
| Intel Core i9                  | 7         | 1.05%   |
| Intel Pentium Silver           | 5         | 0.75%   |
| Intel Core 2                   | 5         | 0.75%   |
| Intel Pentium Dual             | 4         | 0.6%    |
| AMD FX                         | 4         | 0.6%    |
| AMD A8                         | 4         | 0.6%    |
| AMD A6                         | 4         | 0.6%    |
| Intel Pentium Dual-Core        | 3         | 0.45%   |
| Intel Genuine                  | 3         | 0.45%   |
| Intel Core 2 Quad              | 3         | 0.45%   |
| AMD E                          | 3         | 0.45%   |
| AMD A4                         | 3         | 0.45%   |
| AMD A10                        | 3         | 0.45%   |
| Intel Core m3                  | 2         | 0.3%    |
| AMD Turion 64 X2 Mobile        | 2         | 0.3%    |
| AMD E1                         | 2         | 0.3%    |
| Intel Pentium 4                | 1         | 0.15%   |
| Intel Core m5                  | 1         | 0.15%   |
| ARM BCM                        | 1         | 0.15%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.15%   |
| AMD Sempron                    | 1         | 0.15%   |
| AMD Ryzen Threadripper         | 1         | 0.15%   |
| AMD Ryzen 7 PRO                | 1         | 0.15%   |
| AMD Quad-Core                  | 1         | 0.15%   |
| AMD Phenom II X6               | 1         | 0.15%   |
| AMD Phenom II X4               | 1         | 0.15%   |
| AMD Phenom II X2               | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 279       | 41.95%  |
| 2      | 232       | 34.89%  |
| 6      | 63        | 9.47%   |
| 8      | 62        | 9.32%   |
| 1      | 8         | 1.2%    |
| 12     | 7         | 1.05%   |
| 16     | 6         | 0.9%    |
| 3      | 3         | 0.45%   |
| 14     | 2         | 0.3%    |
| 10     | 2         | 0.3%    |
| 24     | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 657       | 98.8%   |
| 2      | 8         | 1.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 476       | 71.47%  |
| 1      | 190       | 28.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 659       | 99.1%   |
| 32-bit         | 3         | 0.45%   |
| Unknown        | 3         | 0.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 241       | 34.78%  |
| 0x206a7    | 37        | 5.34%   |
| 0x306a9    | 33        | 4.76%   |
| 0x806ec    | 26        | 3.75%   |
| 0x306c3    | 24        | 3.46%   |
| 0x806ea    | 18        | 2.6%    |
| 0x906ea    | 17        | 2.45%   |
| 0x806e9    | 15        | 2.16%   |
| 0x806c1    | 14        | 2.02%   |
| 0x1067a    | 14        | 2.02%   |
| 0x506e3    | 12        | 1.73%   |
| 0x406e3    | 12        | 1.73%   |
| 0x40651    | 12        | 1.73%   |
| 0x906e9    | 11        | 1.59%   |
| 0x806eb    | 9         | 1.3%    |
| 0x306d4    | 9         | 1.3%    |
| 0x20655    | 8         | 1.15%   |
| 0xa0652    | 7         | 1.01%   |
| 0x106e5    | 7         | 1.01%   |
| 0x0a50000c | 6         | 0.87%   |
| 0x08600106 | 6         | 0.87%   |
| 0x08600103 | 6         | 0.87%   |
| 0x08108109 | 6         | 0.87%   |
| 0x706a8    | 5         | 0.72%   |
| 0x30678    | 5         | 0.72%   |
| 0x08701021 | 5         | 0.72%   |
| 0x08600104 | 5         | 0.72%   |
| 0x906ec    | 4         | 0.58%   |
| 0x806d1    | 4         | 0.58%   |
| 0x706e5    | 4         | 0.58%   |
| 0x6fd      | 4         | 0.58%   |
| 0x406c4    | 4         | 0.58%   |
| 0x10676    | 4         | 0.58%   |
| 0x0810100b | 4         | 0.58%   |
| 0x0800820d | 4         | 0.58%   |
| 0xa0671    | 3         | 0.43%   |
| 0xa0660    | 3         | 0.43%   |
| 0x906ed    | 3         | 0.43%   |
| 0x906a3    | 3         | 0.43%   |
| 0x706a1    | 3         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 148       | 22.26%  |
| Haswell          | 56        | 8.42%   |
| IvyBridge        | 50        | 7.52%   |
| SandyBridge      | 49        | 7.37%   |
| Zen 2            | 39        | 5.86%   |
| Skylake          | 35        | 5.26%   |
| Penryn           | 25        | 3.76%   |
| TigerLake        | 24        | 3.61%   |
| CometLake        | 22        | 3.31%   |
| Silvermont       | 19        | 2.86%   |
| Unknown          | 19        | 2.86%   |
| Zen+             | 18        | 2.71%   |
| Broadwell        | 18        | 2.71%   |
| Westmere         | 16        | 2.41%   |
| Core             | 15        | 2.26%   |
| IceLake          | 14        | 2.11%   |
| Goldmont plus    | 14        | 2.11%   |
| Zen 3            | 13        | 1.95%   |
| Zen              | 10        | 1.5%    |
| Nehalem          | 10        | 1.5%    |
| Excavator        | 7         | 1.05%   |
| Piledriver       | 6         | 0.9%    |
| K10              | 6         | 0.9%    |
| Goldmont         | 6         | 0.9%    |
| Puma             | 4         | 0.6%    |
| Jaguar           | 4         | 0.6%    |
| Bobcat           | 3         | 0.45%   |
| Alderlake Hybrid | 3         | 0.45%   |
| Steamroller      | 2         | 0.3%    |
| K8 Hammer        | 2         | 0.3%    |
| Bonnell          | 2         | 0.3%    |
| Tremont          | 1         | 0.15%   |
| P6               | 1         | 0.15%   |
| NetBurst         | 1         | 0.15%   |
| K8 & K10 hybrid  | 1         | 0.15%   |
| K10 Llano        | 1         | 0.15%   |
| Bulldozer        | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 429       | 53.49%  |
| Nvidia                     | 215       | 26.81%  |
| AMD                        | 156       | 19.45%  |
| Matrox Electronics Systems | 1         | 0.12%   |
| ASPEED Technology          | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 38        | 4.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 3.56%   |
| Intel UHD Graphics 620                                                                   | 27        | 3.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 3.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 2.82%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 23        | 2.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 2.33%   |
| Intel HD Graphics 620                                                                    | 18        | 2.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 2.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 14        | 1.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 14        | 1.72%   |
| Intel HD Graphics 5500                                                                   | 12        | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.35%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 1.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.23%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 1.1%    |
| Intel HD Graphics 630                                                                    | 9         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 1.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8         | 0.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 0.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 0.98%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 0.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 0.86%   |
| Intel HD Graphics 530                                                                    | 7         | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.74%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6         | 0.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 0.74%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.61%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.61%   |
| Intel HD Graphics 500                                                                    | 5         | 0.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.61%   |
| Intel Comet Lake UHD Graphics                                                            | 5         | 0.61%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 5         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 309       | 46.05%  |
| 1 x AMD         | 114       | 16.99%  |
| 1 x Nvidia      | 104       | 15.5%   |
| Intel + Nvidia  | 93        | 13.86%  |
| Intel + AMD     | 21        | 3.13%   |
| AMD + Nvidia    | 15        | 2.24%   |
| Other           | 5         | 0.75%   |
| 2 x AMD         | 5         | 0.75%   |
| 2 x Nvidia      | 2         | 0.3%    |
| 2 x Intel       | 1         | 0.15%   |
| Nvidia + Matrox | 1         | 0.15%   |
| 1 x ASPEED      | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 505       | 74.59%  |
| Proprietary | 152       | 22.45%  |
| Unknown     | 20        | 2.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 432       | 63.34%  |
| 1.01-2.0   | 67        | 9.82%   |
| 3.01-4.0   | 43        | 6.3%    |
| 0.01-0.5   | 42        | 6.16%   |
| 7.01-8.0   | 33        | 4.84%   |
| 0.51-1.0   | 32        | 4.69%   |
| 5.01-6.0   | 25        | 3.67%   |
| 2.01-3.0   | 4         | 0.59%   |
| 8.01-16.0  | 3         | 0.44%   |
| 16.01-24.0 | 1         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 95        | 12.31%  |
| Samsung Electronics     | 89        | 11.53%  |
| AU Optronics            | 88        | 11.4%   |
| BOE                     | 77        | 9.97%   |
| LG Display              | 58        | 7.51%   |
| Dell                    | 48        | 6.22%   |
| Goldstar                | 31        | 4.02%   |
| Apple                   | 27        | 3.5%    |
| Hewlett-Packard         | 23        | 2.98%   |
| AOC                     | 20        | 2.59%   |
| Acer                    | 17        | 2.2%    |
| BenQ                    | 16        | 2.07%   |
| Ancor Communications    | 16        | 2.07%   |
| Sharp                   | 14        | 1.81%   |
| Philips                 | 14        | 1.81%   |
| Chi Mei Optoelectronics | 12        | 1.55%   |
| Lenovo                  | 10        | 1.3%    |
| Unknown                 | 8         | 1.04%   |
| PANDA                   | 7         | 0.91%   |
| InfoVision              | 6         | 0.78%   |
| ASUSTek Computer        | 6         | 0.78%   |
| LG Electronics          | 5         | 0.65%   |
| Iiyama                  | 5         | 0.65%   |
| Fujitsu Siemens         | 5         | 0.65%   |
| Sony                    | 4         | 0.52%   |
| Idek Iiyama             | 4         | 0.52%   |
| MStar                   | 3         | 0.39%   |
| Medion                  | 3         | 0.39%   |
| LGD                     | 3         | 0.39%   |
| Eizo                    | 3         | 0.39%   |
| Vizio                   | 2         | 0.26%   |
| ViewSonic               | 2         | 0.26%   |
| Vestel Elektronik       | 2         | 0.26%   |
| Unknown (AAA)           | 2         | 0.26%   |
| Sceptre Tech            | 2         | 0.26%   |
| SANYO                   | 2         | 0.26%   |
| Panasonic               | 2         | 0.26%   |
| LG Philips              | 2         | 0.26%   |
| HKC                     | 2         | 0.26%   |
| Daewoo                  | 2         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 6         | 0.74%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 5         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 5         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.49%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 4         | 0.49%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 4         | 0.49%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 3         | 0.37%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.37%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.37%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 2         | 0.25%   |
| Unknown LCD Monitor SAMSUNG                                           | 2         | 0.25%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 2         | 0.25%   |
| Samsung Electronics S27B550 SAM091B 1920x1080 598x336mm 27.0-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SAM0BB4 3840x2160 890x500mm 40.2-inch | 2         | 0.25%   |
| Samsung Electronics LCD Monitor C34H89x 3440x1440                     | 2         | 0.25%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 2         | 0.25%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2         | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.25%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.25%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 2         | 0.25%   |
| Medion MD20338 MED3943 1600x900 462x272mm 21.1-inch                   | 2         | 0.25%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.25%   |
| LG Display LCD Monitor LGD0625 1920x1080 340x190mm 15.3-inch          | 2         | 0.25%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 2         | 0.25%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch          | 2         | 0.25%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 2         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 320       | 43.6%   |
| 1366x768 (WXGA)    | 136       | 18.53%  |
| 3840x2160 (4K)     | 44        | 5.99%   |
| 2560x1440 (QHD)    | 30        | 4.09%   |
| 1600x900 (HD+)     | 25        | 3.41%   |
| 1920x1200 (WUXGA)  | 18        | 2.45%   |
| 1280x1024 (SXGA)   | 18        | 2.45%   |
| Unknown            | 15        | 2.04%   |
| 1680x1050 (WSXGA+) | 14        | 1.91%   |
| 1280x800 (WXGA)    | 14        | 1.91%   |
| 3440x1440          | 13        | 1.77%   |
| 2560x1080          | 12        | 1.63%   |
| 1440x900 (WXGA+)   | 10        | 1.36%   |
| 3840x1080          | 7         | 0.95%   |
| 2880x1800          | 5         | 0.68%   |
| 2560x1600          | 5         | 0.68%   |
| 3200x1800 (QHD+)   | 4         | 0.54%   |
| 1920x540           | 4         | 0.54%   |
| 3000x2000          | 3         | 0.41%   |
| 2160x1440          | 3         | 0.41%   |
| 3520x1080          | 2         | 0.27%   |
| 2256x1504          | 2         | 0.27%   |
| 1600x1200          | 2         | 0.27%   |
| 1360x768           | 2         | 0.27%   |
| 7680x2160          | 1         | 0.14%   |
| 5760x2160          | 1         | 0.14%   |
| 4480x1440          | 1         | 0.14%   |
| 4480x1080          | 1         | 0.14%   |
| 3840x2400          | 1         | 0.14%   |
| 3840x1440          | 1         | 0.14%   |
| 3840x1200          | 1         | 0.14%   |
| 3840x1100          | 1         | 0.14%   |
| 3600x1080          | 1         | 0.14%   |
| 3456x2160          | 1         | 0.14%   |
| 3280x1080          | 1         | 0.14%   |
| 2880x1920          | 1         | 0.14%   |
| 2736x1824          | 1         | 0.14%   |
| 2646x768           | 1         | 0.14%   |
| 2560x1024          | 1         | 0.14%   |
| 2520x1680          | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 197       | 25.58%  |
| 13      | 102       | 13.25%  |
| 14      | 66        | 8.57%   |
| Unknown | 56        | 7.27%   |
| 24      | 55        | 7.14%   |
| 27      | 51        | 6.62%   |
| 23      | 42        | 5.45%   |
| 17      | 38        | 4.94%   |
| 21      | 27        | 3.51%   |
| 34      | 20        | 2.6%    |
| 19      | 14        | 1.82%   |
| 12      | 13        | 1.69%   |
| 31      | 12        | 1.56%   |
| 11      | 11        | 1.43%   |
| 22      | 7         | 0.91%   |
| 84      | 6         | 0.78%   |
| 54      | 6         | 0.78%   |
| 20      | 6         | 0.78%   |
| 18      | 6         | 0.78%   |
| 40      | 4         | 0.52%   |
| 72      | 3         | 0.39%   |
| 48      | 3         | 0.39%   |
| 32      | 3         | 0.39%   |
| 28      | 3         | 0.39%   |
| 16      | 3         | 0.39%   |
| 52      | 2         | 0.26%   |
| 33      | 2         | 0.26%   |
| 29      | 2         | 0.26%   |
| 142     | 1         | 0.13%   |
| 63      | 1         | 0.13%   |
| 60      | 1         | 0.13%   |
| 46      | 1         | 0.13%   |
| 44      | 1         | 0.13%   |
| 42      | 1         | 0.13%   |
| 37      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |
| 25      | 1         | 0.13%   |
| 10      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 315       | 41.23%  |
| 501-600        | 137       | 17.93%  |
| 201-300        | 77        | 10.08%  |
| Unknown        | 56        | 7.33%   |
| 401-500        | 51        | 6.68%   |
| 351-400        | 48        | 6.28%   |
| 701-800        | 25        | 3.27%   |
| 601-700        | 24        | 3.14%   |
| 1001-1500      | 14        | 1.83%   |
| 1501-2000      | 9         | 1.18%   |
| 801-900        | 5         | 0.65%   |
| 901-1000       | 2         | 0.26%   |
| More than 2000 | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 500       | 72.67%  |
| 16/10   | 73        | 10.61%  |
| Unknown | 49        | 7.12%   |
| 21/9    | 22        | 3.2%    |
| 5/4     | 15        | 2.18%   |
| 3/2     | 13        | 1.89%   |
| 4/3     | 8         | 1.16%   |
| 32/9    | 4         | 0.58%   |
| 1.00    | 2         | 0.29%   |
| 6/5     | 1         | 0.15%   |
| 3.40    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 196       | 25.69%  |
| 81-90          | 128       | 16.78%  |
| 201-250        | 94        | 12.32%  |
| Unknown        | 56        | 7.34%   |
| 301-350        | 51        | 6.68%   |
| 71-80          | 40        | 5.24%   |
| 351-500        | 40        | 5.24%   |
| 151-200        | 31        | 4.06%   |
| 121-130        | 26        | 3.41%   |
| 251-300        | 24        | 3.15%   |
| More than 1000 | 21        | 2.75%   |
| 51-60          | 12        | 1.57%   |
| 141-150        | 11        | 1.44%   |
| 61-70          | 10        | 1.31%   |
| 501-1000       | 10        | 1.31%   |
| 131-140        | 7         | 0.92%   |
| 91-100         | 4         | 0.52%   |
| 41-50          | 1         | 0.13%   |
| 111-120        | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 209       | 27.98%  |
| 51-100        | 201       | 26.91%  |
| 101-120       | 176       | 23.56%  |
| 161-240       | 58        | 7.76%   |
| Unknown       | 56        | 7.5%    |
| More than 240 | 27        | 3.61%   |
| 1-50          | 20        | 2.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 513       | 75.22%  |
| 2     | 134       | 19.65%  |
| 0     | 19        | 2.79%   |
| 3     | 15        | 2.2%    |
| 4     | 1         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 373       | 36.32%  |
| Realtek Semiconductor             | 346       | 33.69%  |
| Qualcomm Atheros                  | 106       | 10.32%  |
| Broadcom                          | 65        | 6.33%   |
| Broadcom Limited                  | 20        | 1.95%   |
| MediaTek                          | 11        | 1.07%   |
| Ralink Technology                 | 10        | 0.97%   |
| Marvell Technology Group          | 10        | 0.97%   |
| Ralink                            | 7         | 0.68%   |
| Nvidia                            | 6         | 0.58%   |
| Xiaomi                            | 5         | 0.49%   |
| NetGear                           | 5         | 0.49%   |
| Hewlett-Packard                   | 5         | 0.49%   |
| ASIX Electronics                  | 5         | 0.49%   |
| Microsoft                         | 4         | 0.39%   |
| Lenovo                            | 4         | 0.39%   |
| Qualcomm Atheros Communications   | 3         | 0.29%   |
| JMicron Technology                | 3         | 0.29%   |
| Huawei Technologies               | 3         | 0.29%   |
| D-Link System                     | 3         | 0.29%   |
| D-Link                            | 3         | 0.29%   |
| TP-Link                           | 2         | 0.19%   |
| Sierra Wireless                   | 2         | 0.19%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.19%   |
| Linksys                           | 2         | 0.19%   |
| DisplayLink                       | 2         | 0.19%   |
| Belkin Components                 | 2         | 0.19%   |
| ASUSTek Computer                  | 2         | 0.19%   |
| Wacom                             | 1         | 0.1%    |
| T & A Mobile Phones               | 1         | 0.1%    |
| Samsung Electronics               | 1         | 0.1%    |
| Novatek Microelectronics          | 1         | 0.1%    |
| Motorola PCS                      | 1         | 0.1%    |
| Mercucys                          | 1         | 0.1%    |
| Luminary Micro                    | 1         | 0.1%    |
| Google                            | 1         | 0.1%    |
| Fibocom                           | 1         | 0.1%    |
| Exar                              | 1         | 0.1%    |
| Ericsson Business Mobile Networks | 1         | 0.1%    |
| Edimax Technology                 | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 222       | 18.3%   |
| Intel Wi-Fi 6 AX200                                               | 60        | 4.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 3.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36        | 2.97%   |
| Intel Wireless 8265 / 8275                                        | 32        | 2.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26        | 2.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 23        | 1.9%    |
| Intel Wireless-AC 9260                                            | 19        | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 1.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 1.32%   |
| Intel Wireless 7265                                               | 16        | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15        | 1.24%   |
| Intel Wireless 8260                                               | 15        | 1.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 1.15%   |
| Intel Wi-Fi 6 AX201                                               | 14        | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12        | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 11        | 0.91%   |
| Intel Wireless 7260                                               | 10        | 0.82%   |
| Intel I211 Gigabit Network Connection                             | 10        | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 0.82%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.66%   |
| Intel Wireless 3165                                               | 8         | 0.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 0.66%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 8         | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 0.58%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.58%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 7         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 0.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.49%   |
| Intel Ethernet Controller I225-V                                  | 6         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 302       | 51.19%  |
| Qualcomm Atheros                      | 83        | 14.07%  |
| Realtek Semiconductor                 | 81        | 13.73%  |
| Broadcom                              | 46        | 7.8%    |
| Broadcom Limited                      | 14        | 2.37%   |
| MediaTek                              | 11        | 1.86%   |
| Ralink Technology                     | 10        | 1.69%   |
| Ralink                                | 7         | 1.19%   |
| NetGear                               | 5         | 0.85%   |
| Microsoft                             | 4         | 0.68%   |
| Qualcomm Atheros Communications       | 3         | 0.51%   |
| D-Link                                | 3         | 0.51%   |
| TP-Link                               | 2         | 0.34%   |
| Sierra Wireless                       | 2         | 0.34%   |
| Marvell Technology Group              | 2         | 0.34%   |
| Linksys                               | 2         | 0.34%   |
| D-Link System                         | 2         | 0.34%   |
| Belkin Components                     | 2         | 0.34%   |
| ASUSTek Computer                      | 2         | 0.34%   |
| Wacom                                 | 1         | 0.17%   |
| Mercucys                              | 1         | 0.17%   |
| Hewlett-Packard                       | 1         | 0.17%   |
| Fibocom                               | 1         | 0.17%   |
| Edimax Technology                     | 1         | 0.17%   |
| BUFFALO                               | 1         | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 60        | 10.08%  |
| Intel Wireless 8265 / 8275                                           | 32        | 5.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 23        | 3.87%   |
| Intel Wireless-AC 9260                                               | 19        | 3.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 18        | 3.03%   |
| Intel Wireless 7265                                                  | 16        | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 15        | 2.52%   |
| Intel Wireless 8260                                                  | 15        | 2.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 14        | 2.35%   |
| Intel Wi-Fi 6 AX201                                                  | 14        | 2.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 13        | 2.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 12        | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 12        | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 11        | 1.85%   |
| Intel Wireless 7260                                                  | 10        | 1.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 10        | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 9         | 1.51%   |
| Broadcom BCM43142 802.11b/g/n                                        | 9         | 1.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 8         | 1.34%   |
| Intel Wireless 3165                                                  | 8         | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 8         | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 7         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 7         | 1.18%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 7         | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 6         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 6         | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 6         | 1.01%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 6         | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 5         | 0.84%   |
| Realtek 802.11ac NIC                                                 | 5         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 5         | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 5         | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 5         | 0.84%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 5         | 0.84%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 5         | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 4         | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 4         | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 4         | 0.67%   |
| Intel Centrino Wireless-N 2230                                       | 4         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 311       | 52.8%   |
| Intel                         | 166       | 28.18%  |
| Broadcom                      | 33        | 5.6%    |
| Qualcomm Atheros              | 31        | 5.26%   |
| Marvell Technology Group      | 8         | 1.36%   |
| Nvidia                        | 6         | 1.02%   |
| Broadcom Limited              | 6         | 1.02%   |
| Xiaomi                        | 5         | 0.85%   |
| ASIX Electronics              | 5         | 0.85%   |
| Lenovo                        | 4         | 0.68%   |
| JMicron Technology            | 3         | 0.51%   |
| OnePlus Technology (Shenzhen) | 2         | 0.34%   |
| Hewlett-Packard               | 2         | 0.34%   |
| DisplayLink                   | 2         | 0.34%   |
| T & A Mobile Phones           | 1         | 0.17%   |
| Samsung Electronics           | 1         | 0.17%   |
| Google                        | 1         | 0.17%   |
| D-Link System                 | 1         | 0.17%   |
| Apple                         | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 222       | 36.57%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 6.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36        | 5.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26        | 4.28%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 2.64%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 2.31%   |
| Intel I211 Gigabit Network Connection                             | 10        | 1.65%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 1.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 1.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 1.32%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 8         | 1.32%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 1.15%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.99%   |
| Intel Ethernet Controller I225-V                                  | 6         | 0.99%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.82%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.82%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.82%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.66%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.66%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.66%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.66%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.66%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.49%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.49%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.49%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.49%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 0.49%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 559       | 49.6%   |
| Ethernet | 557       | 49.42%  |
| Modem    | 10        | 0.89%   |
| Unknown  | 1         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 448       | 63.64%  |
| Ethernet | 256       | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 390       | 58.56%  |
| 1     | 246       | 36.94%  |
| 0     | 16        | 2.4%    |
| 3     | 14        | 2.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 545       | 80.62%  |
| Yes  | 131       | 19.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 255       | 52.9%   |
| Realtek Semiconductor           | 35        | 7.26%   |
| Qualcomm Atheros Communications | 35        | 7.26%   |
| Apple                           | 29        | 6.02%   |
| Cambridge Silicon Radio         | 25        | 5.19%   |
| Broadcom                        | 22        | 4.56%   |
| IMC Networks                    | 16        | 3.32%   |
| Foxconn / Hon Hai               | 13        | 2.7%    |
| Lite-On Technology              | 12        | 2.49%   |
| Dell                            | 10        | 2.07%   |
| Hewlett-Packard                 | 6         | 1.24%   |
| Realtek                         | 5         | 1.04%   |
| Ralink                          | 3         | 0.62%   |
| Belkin Components               | 3         | 0.62%   |
| ASUSTek Computer                | 3         | 0.62%   |
| Toshiba                         | 2         | 0.41%   |
| MediaTek                        | 2         | 0.41%   |
| Marvell Semiconductor           | 2         | 0.41%   |
| Foxconn International           | 2         | 0.41%   |
| Smart Modular Technologies      | 1         | 0.21%   |
| Integrated System Solution      | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 85        | 17.63%  |
| Intel AX200 Bluetooth                                 | 58        | 12.03%  |
| Intel AX201 Bluetooth                                 | 38        | 7.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 26        | 5.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 25        | 5.19%   |
| Qualcomm Atheros  Bluetooth Device                    | 19        | 3.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 19        | 3.94%   |
| Realtek Bluetooth Radio                               | 18        | 3.73%   |
| Intel Wireless-AC 3168 Bluetooth                      | 11        | 2.28%   |
| Apple Bluetooth USB Host Controller                   | 11        | 2.28%   |
| Apple Bluetooth Host Controller                       | 10        | 2.07%   |
| Dell DW375 Bluetooth Module                           | 9         | 1.87%   |
| Realtek  Bluetooth 4.2 Adapter                        | 8         | 1.66%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 8         | 1.66%   |
| Intel AX210 Bluetooth                                 | 7         | 1.45%   |
| Intel Bluetooth Device                                | 6         | 1.24%   |
| Realtek RTL8723B Bluetooth                            | 5         | 1.04%   |
| Realtek Bluetooth Radio                               | 5         | 1.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 5         | 1.04%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 5         | 1.04%   |
| IMC Networks Bluetooth Radio                          | 5         | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                    | 5         | 1.04%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 5         | 1.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 4         | 0.83%   |
| IMC Networks Wireless_Device                          | 4         | 0.83%   |
| IMC Networks Bluetooth Device                         | 4         | 0.83%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4         | 0.83%   |
| Realtek RTL8821A Bluetooth                            | 3         | 0.62%   |
| Ralink RT3290 Bluetooth                               | 3         | 0.62%   |
| Lite-On Bluetooth Device                              | 3         | 0.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 3         | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                      | 3         | 0.62%   |
| Foxconn / Hon Hai Wireless_Device                     | 3         | 0.62%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 3         | 0.62%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 3         | 0.62%   |
| Apple Bluetooth HCI                                   | 3         | 0.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 0.41%   |
| MediaTek Wireless_Device                              | 2         | 0.41%   |
| Lite-On Atheros AR3012 Bluetooth                      | 2         | 0.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 2         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 517       | 55%     |
| AMD                        | 160       | 17.02%  |
| Nvidia                     | 157       | 16.7%   |
| C-Media Electronics        | 11        | 1.17%   |
| Logitech                   | 10        | 1.06%   |
| Realtek Semiconductor      | 9         | 0.96%   |
| GN Netcom                  | 8         | 0.85%   |
| Texas Instruments          | 5         | 0.53%   |
| JMTek                      | 5         | 0.53%   |
| Plantronics                | 4         | 0.43%   |
| DSEA A/S                   | 4         | 0.43%   |
| Creative Technology        | 4         | 0.43%   |
| Creative Labs              | 4         | 0.43%   |
| Kingston Technology        | 3         | 0.32%   |
| Apple                      | 3         | 0.32%   |
| Samson Technologies        | 2         | 0.21%   |
| Lenovo                     | 2         | 0.21%   |
| Focusrite-Novation         | 2         | 0.21%   |
| Blue Microphones           | 2         | 0.21%   |
| ASUSTek Computer           | 2         | 0.21%   |
| AKAI Professional M.I.     | 2         | 0.21%   |
| XMOS                       | 1         | 0.11%   |
| SteelSeries ApS            | 1         | 0.11%   |
| Shure                      | 1         | 0.11%   |
| Sennheiser Communications  | 1         | 0.11%   |
| Razer USA                  | 1         | 0.11%   |
| PreSonus Audio Electronics | 1         | 0.11%   |
| OPPO Electronics           | 1         | 0.11%   |
| No brand                   | 1         | 0.11%   |
| Native Instruments         | 1         | 0.11%   |
| Nam Tai E&E Products       | 1         | 0.11%   |
| Microsoft                  | 1         | 0.11%   |
| M-Audio                    | 1         | 0.11%   |
| LINE TECH INDUSTRIAL       | 1         | 0.11%   |
| Hewlett-Packard            | 1         | 0.11%   |
| GYROCOM C&C                | 1         | 0.11%   |
| Giga-Byte Technology       | 1         | 0.11%   |
| Generalplus Technology     | 1         | 0.11%   |
| Conexant Systems           | 1         | 0.11%   |
| CMX Systems                | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 70        | 6.4%    |
| AMD Family 17h/19h HD Audio Controller                                     | 59        | 5.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 49        | 4.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 45        | 4.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 32        | 2.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 31        | 2.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 29        | 2.65%   |
| Intel Cannon Lake PCH cAVS                                                 | 29        | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 24        | 2.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 24        | 2.2%    |
| Intel Comet Lake PCH-LP cAVS                                               | 24        | 2.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 21        | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 20        | 1.83%   |
| AMD Starship/Matisse HD Audio Controller                                   | 19        | 1.74%   |
| Nvidia TU106 High Definition Audio Controller                              | 17        | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 17        | 1.56%   |
| Intel 8 Series HD Audio Controller                                         | 17        | 1.56%   |
| AMD FCH Azalia Controller                                                  | 17        | 1.56%   |
| Intel Broadwell-U Audio Controller                                         | 16        | 1.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 1.37%   |
| Nvidia GP106 High Definition Audio Controller                              | 14        | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 14        | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14        | 1.28%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 1.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 12        | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 12        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 11        | 1.01%   |
| Intel CM238 HD Audio Controller                                            | 10        | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 0.91%   |
| Realtek Semiconductor USB Audio                                            | 9         | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9         | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 9         | 0.82%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                         | 8         | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 0.73%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 0.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 0.73%   |
| Intel 200 Series PCH HD Audio                                              | 8         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 123       | 27.77%  |
| SK hynix            | 84        | 18.96%  |
| Micron Technology   | 45        | 10.16%  |
| Kingston            | 44        | 9.93%   |
| Crucial             | 31        | 7%      |
| Unknown             | 26        | 5.87%   |
| Ramaxel Technology  | 12        | 2.71%   |
| Corsair             | 12        | 2.71%   |
| A-DATA Technology   | 9         | 2.03%   |
| G.Skill             | 7         | 1.58%   |
| Unknown (ABCD)      | 6         | 1.35%   |
| Team                | 5         | 1.13%   |
| Elpida              | 5         | 1.13%   |
| Nanya Technology    | 3         | 0.68%   |
| Unknown             | 3         | 0.68%   |
| Transcend           | 2         | 0.45%   |
| Timetec             | 2         | 0.45%   |
| Teikon              | 2         | 0.45%   |
| Smart               | 2         | 0.45%   |
| PNY                 | 2         | 0.45%   |
| GOODRAM             | 2         | 0.45%   |
| Unknown (F301)      | 1         | 0.23%   |
| Unknown (0x873E)    | 1         | 0.23%   |
| Smart Brazil        | 1         | 0.23%   |
| Sesame              | 1         | 0.23%   |
| Patriot             | 1         | 0.23%   |
| Magnum Tech         | 1         | 0.23%   |
| Kingmax             | 1         | 0.23%   |
| Goldkey             | 1         | 0.23%   |
| fef5                | 1         | 0.23%   |
| Cors                | 1         | 0.23%   |
| ChangXin Memory     | 1         | 0.23%   |
| Avant               | 1         | 0.23%   |
| ASint Technology    | 1         | 0.23%   |
| Apacer              | 1         | 0.23%   |
| AMD                 | 1         | 0.23%   |
| 8945000080AD        | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 10        | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 1.71%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 1.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.28%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.28%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 1.28%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.07%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.85%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 4         | 0.85%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 0.85%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.64%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.64%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.64%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 3         | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.64%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.64%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.64%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.64%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.64%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.64%   |
| Unknown                                                          | 3         | 0.64%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                    | 2         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.43%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.43%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.43%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 2         | 0.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.43%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.43%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 0.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.43%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.43%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.43%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.43%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 0.43%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 2         | 0.43%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 189       | 50%     |
| DDR3    | 123       | 32.54%  |
| LPDDR4  | 20        | 5.29%   |
| LPDDR3  | 16        | 4.23%   |
| DDR2    | 11        | 2.91%   |
| SDRAM   | 9         | 2.38%   |
| Unknown | 6         | 1.59%   |
| DDR5    | 2         | 0.53%   |
| DDR     | 2         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 252       | 67.56%  |
| DIMM         | 83        | 22.25%  |
| Row Of Chips | 30        | 8.04%   |
| Unknown      | 3         | 0.8%    |
| FB-DIMM      | 2         | 0.54%   |
| Chip         | 2         | 0.54%   |
| RIMM         | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 152       | 37.62%  |
| 4096  | 111       | 27.48%  |
| 16384 | 63        | 15.59%  |
| 2048  | 39        | 9.65%   |
| 32768 | 26        | 6.44%   |
| 1024  | 11        | 2.72%   |
| 512   | 2         | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 86        | 20.57%  |
| 2667    | 78        | 18.66%  |
| 3200    | 64        | 15.31%  |
| 2400    | 33        | 7.89%   |
| 2133    | 28        | 6.7%    |
| 1333    | 23        | 5.5%    |
| 1334    | 12        | 2.87%   |
| 3266    | 9         | 2.15%   |
| 1867    | 9         | 2.15%   |
| Unknown | 8         | 1.91%   |
| 1067    | 7         | 1.67%   |
| 4267    | 6         | 1.44%   |
| 667     | 6         | 1.44%   |
| 4199    | 4         | 0.96%   |
| 3733    | 4         | 0.96%   |
| 1066    | 4         | 0.96%   |
| 800     | 4         | 0.96%   |
| 8400    | 3         | 0.72%   |
| 533     | 3         | 0.72%   |
| 4800    | 2         | 0.48%   |
| 4266    | 2         | 0.48%   |
| 3600    | 2         | 0.48%   |
| 3400    | 2         | 0.48%   |
| 3000    | 2         | 0.48%   |
| 2472    | 2         | 0.48%   |
| 1800    | 2         | 0.48%   |
| 3866    | 1         | 0.24%   |
| 3800    | 1         | 0.24%   |
| 3666    | 1         | 0.24%   |
| 3500    | 1         | 0.24%   |
| 3007    | 1         | 0.24%   |
| 2933    | 1         | 0.24%   |
| 2666    | 1         | 0.24%   |
| 2134    | 1         | 0.24%   |
| 2048    | 1         | 0.24%   |
| 1866    | 1         | 0.24%   |
| 1639    | 1         | 0.24%   |
| 1331    | 1         | 0.24%   |
| 400     | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 31.25%  |
| Canon               | 4         | 25%     |
| Samsung Electronics | 2         | 12.5%   |
| Brother Industries  | 2         | 12.5%   |
| Sharp               | 1         | 6.25%   |
| Fuji Xerox          | 1         | 6.25%   |
| Dymo-CoStar         | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Sharp AL-2030                 | 1         | 6.25%   |
| Samsung ML-1510 Laser Printer | 1         | 6.25%   |
| Samsung M2020 Series          | 1         | 6.25%   |
| HP LaserJet 1320              | 1         | 6.25%   |
| HP DeskJet 3700 series        | 1         | 6.25%   |
| HP Deskjet 3050 J610 series   | 1         | 6.25%   |
| HP Deskjet 2540 series        | 1         | 6.25%   |
| HP DeskJet 2130 series        | 1         | 6.25%   |
| Fuji Xerox DocuPrint CM305 df | 1         | 6.25%   |
| Dymo-CoStar LabelWriter 450   | 1         | 6.25%   |
| Canon TR7500 series           | 1         | 6.25%   |
| Canon MF4010 series           | 1         | 6.25%   |
| Canon MF240 Series UFRII LT   | 1         | 6.25%   |
| Canon LiDE 400                | 1         | 6.25%   |
| Brother MFC-1810              | 1         | 6.25%   |
| Brother HL-2240 series        | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 33.33%  |
| Canon CanoScan LiDE 120 | 1         | 33.33%  |
| Canon CanoScan LiDE 110 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 109       | 23.85%  |
| IMC Networks                           | 40        | 8.75%   |
| Sunplus Innovation Technology          | 36        | 7.88%   |
| Realtek Semiconductor                  | 33        | 7.22%   |
| Microdia                               | 31        | 6.78%   |
| Bison Electronics                      | 29        | 6.35%   |
| Apple                                  | 23        | 5.03%   |
| Logitech                               | 20        | 4.38%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 3.72%   |
| Quanta                                 | 15        | 3.28%   |
| Syntek                                 | 12        | 2.63%   |
| Suyin                                  | 11        | 2.41%   |
| Acer                                   | 10        | 2.19%   |
| Lite-On Technology                     | 7         | 1.53%   |
| Silicon Motion                         | 6         | 1.31%   |
| Luxvisions Innotech Limited            | 6         | 1.31%   |
| Samsung Electronics                    | 5         | 1.09%   |
| Generalplus Technology                 | 5         | 1.09%   |
| Microsoft                              | 4         | 0.88%   |
| Alcor Micro                            | 4         | 0.88%   |
| Ricoh                                  | 3         | 0.66%   |
| Z-Star Microelectronics                | 2         | 0.44%   |
| LG Electronics                         | 2         | 0.44%   |
| Importek                               | 2         | 0.44%   |
| ARC International                      | 2         | 0.44%   |
| Unknown                                | 2         | 0.44%   |
| Y Media                                | 1         | 0.22%   |
| ValueHD                                | 1         | 0.22%   |
| Unknown (3730304233345731394146)       | 1         | 0.22%   |
| Unknown                                | 1         | 0.22%   |
| Tobii Technology AB                    | 1         | 0.22%   |
| Sonix Technology                       | 1         | 0.22%   |
| Primax Electronics                     | 1         | 0.22%   |
| Polycom                                | 1         | 0.22%   |
| OPPO Electronics                       | 1         | 0.22%   |
| Omnivision                             | 1         | 0.22%   |
| Linux Foundation                       | 1         | 0.22%   |
| IPEVO                                  | 1         | 0.22%   |
| icSpring                               | 1         | 0.22%   |
| Guillemot                              | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                       | 20        | 4.35%   |
| Chicony USB2.0 Camera                                   | 18        | 3.91%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 13        | 2.83%   |
| Chicony Integrated Camera                               | 13        | 2.83%   |
| Microdia Integrated_Webcam_HD                           | 12        | 2.61%   |
| IMC Networks Integrated Camera                          | 12        | 2.61%   |
| Realtek Integrated_Webcam_HD                            | 11        | 2.39%   |
| Chicony HP HD Camera                                    | 9         | 1.96%   |
| Apple FaceTime HD Camera (Built-in)                     | 8         | 1.74%   |
| Logitech HD Pro Webcam C920                             | 7         | 1.52%   |
| Bison HD Webcam                                         | 7         | 1.52%   |
| Bison BisonCam,NB Pro                                   | 7         | 1.52%   |
| Syntek Integrated Camera                                | 6         | 1.3%    |
| Sunplus HD WebCam                                       | 6         | 1.3%    |
| Apple Built-in iSight                                   | 6         | 1.3%    |
| Sunplus Integrated_Webcam_HD                            | 5         | 1.09%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 5         | 1.09%   |
| Apple FaceTime HD Camera                                | 5         | 1.09%   |
| IMC Networks VGA UVC WebCam                             | 4         | 0.87%   |
| Chicony EasyCamera                                      | 4         | 0.87%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 4         | 0.87%   |
| Bison SunplusIT Integrated Camera                       | 4         | 0.87%   |
| Bison Integrated Camera                                 | 4         | 0.87%   |
| Acer Integrated Camera                                  | 4         | 0.87%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 3         | 0.65%   |
| Sunplus Integrated_Webcam_FHD                           | 3         | 0.65%   |
| Sunplus Asus Webcam                                     | 3         | 0.65%   |
| Realtek USB2.0 HD UVC WebCam                            | 3         | 0.65%   |
| Realtek Lenovo EasyCamera                               | 3         | 0.65%   |
| Realtek Integrated Webcam                               | 3         | 0.65%   |
| Realtek HD WebCam                                       | 3         | 0.65%   |
| Quanta HD User Facing                                   | 3         | 0.65%   |
| Microdia Sonix USB 2.0 Camera                           | 3         | 0.65%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 0.65%   |
| IMC Networks ov9734_azurewave_camera                    | 3         | 0.65%   |
| Generalplus GENERAL WEBCAM                              | 3         | 0.65%   |
| Chicony USB2.0 VGA UVC WebCam                           | 3         | 0.65%   |
| Chicony Integrated Camera [ThinkPad]                    | 3         | 0.65%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 0.65%   |
| Chicony HP Truevision HD                                | 3         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 39        | 36.79%  |
| Validity Sensors           | 31        | 29.25%  |
| Shenzhen Goodix Technology | 18        | 16.98%  |
| LighTuning Technology      | 8         | 7.55%   |
| Elan Microelectronics      | 6         | 5.66%   |
| AuthenTec                  | 4         | 3.77%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 10.38%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 9.43%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 7.55%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 4.72%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 4.72%   |
| Elan ELAN:Fingerprint                                                      | 5         | 4.72%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.77%   |
| Synaptics WBDI Device                                                      | 4         | 3.77%   |
| Synaptics TouchPad                                                         | 4         | 3.77%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.77%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 3.77%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.83%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 3         | 2.83%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.83%   |
| Unknown                                                                    | 3         | 2.83%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.89%   |
| Validity Sensors VFS491                                                    | 2         | 1.89%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.89%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.89%   |
| Synaptics UWP WBDI                                                         | 2         | 1.89%   |
| Synaptics  WBDI                                                            | 2         | 1.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.89%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.89%   |
| AuthenTec AES1600                                                          | 2         | 1.89%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.94%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.94%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 0.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.94%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.94%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.94%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.94%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.94%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.94%   |
| AuthenTec AES2810                                                          | 1         | 0.94%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.94%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 16        | 50%     |
| Alcor Micro           | 8         | 25%     |
| Upek                  | 5         | 15.63%  |
| Lenovo                | 2         | 6.25%   |
| Gemalto (was Gemplus) | 1         | 3.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 21.88%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 21.88%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 15.63%  |
| Broadcom 5880                                                                | 5         | 15.63%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.25%   |
| Broadcom 58200                                                               | 2         | 6.25%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 3.13%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 3.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 439       | 64.94%  |
| 1     | 186       | 27.51%  |
| 2     | 40        | 5.92%   |
| 3     | 6         | 0.89%   |
| 4     | 2         | 0.3%    |
| 9     | 1         | 0.15%   |
| 7     | 1         | 0.15%   |
| 5     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 105       | 36.84%  |
| Graphics card            | 52        | 18.25%  |
| Chipcard                 | 31        | 10.88%  |
| Net/wireless             | 27        | 9.47%   |
| Communication controller | 20        | 7.02%   |
| Multimedia controller    | 9         | 3.16%   |
| Camera                   | 9         | 3.16%   |
| Sound                    | 8         | 2.81%   |
| Bluetooth                | 7         | 2.46%   |
| Card reader              | 6         | 2.11%   |
| Storage                  | 5         | 1.75%   |
| Unassigned class         | 4         | 1.4%    |
| Net/ethernet             | 2         | 0.7%    |

