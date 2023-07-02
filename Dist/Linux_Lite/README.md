Linux Lite - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Linux Lite.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Linux_Lite/Desktop/README.md) and [notebooks](/Dist/Linux_Lite/Notebook/README.md).

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

Total: 204

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-db0xxx            | Notebook    | [892229f999](https://linux-hardware.org/?probe=892229f999) | Jun 28, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [6d470794e9](https://linux-hardware.org/?probe=6d470794e9) | Jun 28, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [dff301aade](https://linux-hardware.org/?probe=dff301aade) | Jun 25, 2023 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [b36de255fe](https://linux-hardware.org/?probe=b36de255fe) | Jun 22, 2023 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [f8f4049a95](https://linux-hardware.org/?probe=f8f4049a95) | Jun 22, 2023 |
| AMI           | Intel                       | Desktop     | [72c570c2fa](https://linux-hardware.org/?probe=72c570c2fa) | Jun 14, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [d22b8a57cf](https://linux-hardware.org/?probe=d22b8a57cf) | Jun 13, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e86a159ec5](https://linux-hardware.org/?probe=e86a159ec5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [01cd20c83d](https://linux-hardware.org/?probe=01cd20c83d) | Jun 03, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [b160fbf41e](https://linux-hardware.org/?probe=b160fbf41e) | May 21, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [cc90a5ca05](https://linux-hardware.org/?probe=cc90a5ca05) | May 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [72adb50172](https://linux-hardware.org/?probe=72adb50172) | May 20, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [50e85498e7](https://linux-hardware.org/?probe=50e85498e7) | May 20, 2023 |
| Lenovo        | ThinkPad X240 20AMS1J100    | Notebook    | [86edc6c6d6](https://linux-hardware.org/?probe=86edc6c6d6) | May 11, 2023 |
| American M... | IPPBT-RO                    | All in one  | [ea620e0681](https://linux-hardware.org/?probe=ea620e0681) | May 04, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [b77341d8f0](https://linux-hardware.org/?probe=b77341d8f0) | May 01, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [b971501e28](https://linux-hardware.org/?probe=b971501e28) | May 01, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [87ab055a31](https://linux-hardware.org/?probe=87ab055a31) | Apr 27, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [c5c1b213f2](https://linux-hardware.org/?probe=c5c1b213f2) | Apr 16, 2023 |
| Lenovo        | Yoga C740 81TC              | Convertible | [087e19943f](https://linux-hardware.org/?probe=087e19943f) | Apr 11, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [cf325779ee](https://linux-hardware.org/?probe=cf325779ee) | Apr 08, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [d79463ea93](https://linux-hardware.org/?probe=d79463ea93) | Apr 04, 2023 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [8d94a6c8e7](https://linux-hardware.org/?probe=8d94a6c8e7) | Mar 28, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [06ad8714ea](https://linux-hardware.org/?probe=06ad8714ea) | Mar 22, 2023 |
| HP            | 0AE4h C                     | Desktop     | [fe2502088a](https://linux-hardware.org/?probe=fe2502088a) | Mar 21, 2023 |
| HP            | 0AE4h C                     | Desktop     | [71bdbbb36f](https://linux-hardware.org/?probe=71bdbbb36f) | Mar 19, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [16b1b61892](https://linux-hardware.org/?probe=16b1b61892) | Mar 17, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [b42df5cbe0](https://linux-hardware.org/?probe=b42df5cbe0) | Mar 11, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [17a3030488](https://linux-hardware.org/?probe=17a3030488) | Mar 11, 2023 |
| Gateway       | Sonic-C                     | Notebook    | [b9f775b14e](https://linux-hardware.org/?probe=b9f775b14e) | Feb 28, 2023 |
| Gateway       | Sonic-C                     | Notebook    | [6def275f9b](https://linux-hardware.org/?probe=6def275f9b) | Feb 26, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [199c8805ee](https://linux-hardware.org/?probe=199c8805ee) | Feb 10, 2023 |
| HP            | 240 G3                      | Notebook    | [a977b66ced](https://linux-hardware.org/?probe=a977b66ced) | Feb 02, 2023 |
| HP            | 240 G3                      | Notebook    | [816a3f4b28](https://linux-hardware.org/?probe=816a3f4b28) | Feb 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [cad4d19ab7](https://linux-hardware.org/?probe=cad4d19ab7) | Feb 02, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [4762c2a35b](https://linux-hardware.org/?probe=4762c2a35b) | Jan 31, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [b8891cfc9b](https://linux-hardware.org/?probe=b8891cfc9b) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [fb0a23c0e6](https://linux-hardware.org/?probe=fb0a23c0e6) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [24b6a47ebb](https://linux-hardware.org/?probe=24b6a47ebb) | Jan 27, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [b0289f0ef8](https://linux-hardware.org/?probe=b0289f0ef8) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [adbc469f95](https://linux-hardware.org/?probe=adbc469f95) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [9249ff32b3](https://linux-hardware.org/?probe=9249ff32b3) | Jan 22, 2023 |
| HP            | Stream Notebook PC 13       | Notebook    | [b31d60976b](https://linux-hardware.org/?probe=b31d60976b) | Jan 14, 2023 |
| ASUSTek       | M4N72-E                     | Desktop     | [1902350147](https://linux-hardware.org/?probe=1902350147) | Dec 28, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [eb42b5e055](https://linux-hardware.org/?probe=eb42b5e055) | Dec 24, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [f77ff3b9b5](https://linux-hardware.org/?probe=f77ff3b9b5) | Dec 19, 2022 |
| Pegatron      | H36FF                       | Notebook    | [f27fc61f18](https://linux-hardware.org/?probe=f27fc61f18) | Dec 18, 2022 |
| Thomson       | PT-NEO14A.2WH32             | Notebook    | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| Pegatron      | H36FF                       | Notebook    | [692955be3d](https://linux-hardware.org/?probe=692955be3d) | Dec 18, 2022 |
| Braview       | BRW-BSWI-D2                 | Desktop     | [1568a74103](https://linux-hardware.org/?probe=1568a74103) | Dec 11, 2022 |
| Packard Be... | MCP73VT-PM                  | Desktop     | [e2e6da1ef3](https://linux-hardware.org/?probe=e2e6da1ef3) | Nov 27, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [9224597686](https://linux-hardware.org/?probe=9224597686) | Oct 28, 2022 |
| UMAX          | VisionBook 12Wi 64G         | Notebook    | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [8546f55697](https://linux-hardware.org/?probe=8546f55697) | Oct 24, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [3b1b5c18c6](https://linux-hardware.org/?probe=3b1b5c18c6) | Oct 24, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| MSI           | MS-N014                     | Notebook    | [4c41640fd3](https://linux-hardware.org/?probe=4c41640fd3) | Oct 12, 2022 |
| MSI           | MS-N014                     | Notebook    | [3144cac65a](https://linux-hardware.org/?probe=3144cac65a) | Oct 12, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [676289f650](https://linux-hardware.org/?probe=676289f650) | Oct 02, 2022 |
| HP            | Compaq 420                  | Notebook    | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | 1632                        | Desktop     | [f510159333](https://linux-hardware.org/?probe=f510159333) | Sep 19, 2022 |
| HP            | Presario V6000 (RG289UA#... | Notebook    | [7f0113694a](https://linux-hardware.org/?probe=7f0113694a) | Sep 15, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [1a999b09ae](https://linux-hardware.org/?probe=1a999b09ae) | Sep 12, 2022 |
| HP            | 1632                        | Desktop     | [f14389b9dd](https://linux-hardware.org/?probe=f14389b9dd) | Sep 10, 2022 |
| Samsung       | X420/X520                   | Notebook    | [a8ca7bb005](https://linux-hardware.org/?probe=a8ca7bb005) | Sep 04, 2022 |
| Fujitsu       | FMVNQ8P6                    | Notebook    | [5e34698f14](https://linux-hardware.org/?probe=5e34698f14) | Aug 28, 2022 |
| Sony          | VAIO                        | All in one  | [3ed1ad79e4](https://linux-hardware.org/?probe=3ed1ad79e4) | Aug 24, 2022 |
| ASUSTek       | UX303LN                     | Notebook    | [63d5525864](https://linux-hardware.org/?probe=63d5525864) | Aug 16, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [86523f9a5f](https://linux-hardware.org/?probe=86523f9a5f) | Aug 11, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | Notebook    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [fd0a9ef1c8](https://linux-hardware.org/?probe=fd0a9ef1c8) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [cc2f84d5d3](https://linux-hardware.org/?probe=cc2f84d5d3) | Jul 08, 2022 |
| HP            | Pavilion g4                 | Notebook    | [330078dbac](https://linux-hardware.org/?probe=330078dbac) | Jul 04, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [762b96a2de](https://linux-hardware.org/?probe=762b96a2de) | Jul 02, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | Desktop     | [03c6ee002e](https://linux-hardware.org/?probe=03c6ee002e) | Jun 07, 2022 |
| Samsung       | 530XBB                      | Notebook    | [485a99ca42](https://linux-hardware.org/?probe=485a99ca42) | Jun 03, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [19a5c1de8e](https://linux-hardware.org/?probe=19a5c1de8e) | May 29, 2022 |
| Minix         | Z64 V1.2                    | Notebook    | [97525a1dc3](https://linux-hardware.org/?probe=97525a1dc3) | May 27, 2022 |
| Lenovo        | Remore CRB Win8 STD MM D... | Desktop     | [eb96be3541](https://linux-hardware.org/?probe=eb96be3541) | May 24, 2022 |
| Lenovo        | Remore CRB Win8 STD MM D... | Desktop     | [f1a79871f7](https://linux-hardware.org/?probe=f1a79871f7) | May 24, 2022 |
| HP            | 3047h                       | Desktop     | [cc184c817b](https://linux-hardware.org/?probe=cc184c817b) | May 16, 2022 |
| Dell          | Inspiron 16 5620            | Notebook    | [b42e1cf95b](https://linux-hardware.org/?probe=b42e1cf95b) | May 13, 2022 |
| Minix         | Z64 V1.2                    | Notebook    | [8796deded0](https://linux-hardware.org/?probe=8796deded0) | May 12, 2022 |
| Dell          | MXG061                      | Notebook    | [119f6dd774](https://linux-hardware.org/?probe=119f6dd774) | May 09, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [ab553d3a2f](https://linux-hardware.org/?probe=ab553d3a2f) | May 01, 2022 |
| Acer          | Extensa 5220                | Notebook    | [ebbd01171d](https://linux-hardware.org/?probe=ebbd01171d) | May 01, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [f7838121d2](https://linux-hardware.org/?probe=f7838121d2) | Apr 23, 2022 |
| Acer          | Aspire 1410                 | Notebook    | [703c2ec84a](https://linux-hardware.org/?probe=703c2ec84a) | Apr 21, 2022 |
| Lenovo        | ThinkPad T400 6475E13       | Notebook    | [cd49ac8445](https://linux-hardware.org/?probe=cd49ac8445) | Apr 08, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [0c6fc3cae4](https://linux-hardware.org/?probe=0c6fc3cae4) | Apr 07, 2022 |
| Dell          | MXG061                      | Notebook    | [9c91bd9487](https://linux-hardware.org/?probe=9c91bd9487) | Apr 06, 2022 |
| HP            | 2820h                       | Desktop     | [c4461b3710](https://linux-hardware.org/?probe=c4461b3710) | Apr 04, 2022 |
| Insignia      | NS-P11W7100                 | Notebook    | [daa476af8c](https://linux-hardware.org/?probe=daa476af8c) | Mar 28, 2022 |
| Dell          | MXG071                      | Notebook    | [ac0158dcb9](https://linux-hardware.org/?probe=ac0158dcb9) | Mar 27, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [693b66ce17](https://linux-hardware.org/?probe=693b66ce17) | Mar 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [badb9dcc14](https://linux-hardware.org/?probe=badb9dcc14) | Mar 26, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [32115c5548](https://linux-hardware.org/?probe=32115c5548) | Mar 26, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [0f99b7ff76](https://linux-hardware.org/?probe=0f99b7ff76) | Mar 21, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [bc850554b2](https://linux-hardware.org/?probe=bc850554b2) | Mar 16, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| HP            | Compaq CQ45                 | Notebook    | [99286efd08](https://linux-hardware.org/?probe=99286efd08) | Mar 10, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [2b748962fa](https://linux-hardware.org/?probe=2b748962fa) | Mar 06, 2022 |
| ASUSTek       | 900                         | Notebook    | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [6134bb8cba](https://linux-hardware.org/?probe=6134bb8cba) | Feb 18, 2022 |
| ABIT          | IP35-E                      | Desktop     | [67d9f7e94e](https://linux-hardware.org/?probe=67d9f7e94e) | Feb 17, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [b596d9fdb1](https://linux-hardware.org/?probe=b596d9fdb1) | Feb 09, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [4fe66f8af6](https://linux-hardware.org/?probe=4fe66f8af6) | Feb 09, 2022 |
| HP            | Compaq nw9440 (EY615ET#A... | Notebook    | [6a5c3254ab](https://linux-hardware.org/?probe=6a5c3254ab) | Jan 30, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [15838ae11b](https://linux-hardware.org/?probe=15838ae11b) | Jan 12, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | Desktop     | [9e4639427d](https://linux-hardware.org/?probe=9e4639427d) | Jan 03, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | Desktop     | [d351220ea5](https://linux-hardware.org/?probe=d351220ea5) | Jan 02, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | Desktop     | [b2786130fb](https://linux-hardware.org/?probe=b2786130fb) | Jan 02, 2022 |
| ASUSTek       | X541SA                      | Notebook    | [26f2eeeefc](https://linux-hardware.org/?probe=26f2eeeefc) | Dec 31, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [978ee4328d](https://linux-hardware.org/?probe=978ee4328d) | Dec 19, 2021 |
| ASRock        | H61M-VG3                    | Desktop     | [392a957541](https://linux-hardware.org/?probe=392a957541) | Dec 17, 2021 |
| Acer          | Aspire 5600                 | Notebook    | [25b1e50c64](https://linux-hardware.org/?probe=25b1e50c64) | Dec 12, 2021 |
| Gigabyte      | GA-E350N                    | Desktop     | [10d55dd433](https://linux-hardware.org/?probe=10d55dd433) | Dec 02, 2021 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [64eba568a1](https://linux-hardware.org/?probe=64eba568a1) | Nov 25, 2021 |
| HP            | Compaq 2510p                | Notebook    | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| HP            | Compaq 2510p                | Notebook    | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [b7306537cc](https://linux-hardware.org/?probe=b7306537cc) | Nov 10, 2021 |
| Acer          | Aspire 5600                 | Notebook    | [7e2da6d3e9](https://linux-hardware.org/?probe=7e2da6d3e9) | Oct 26, 2021 |
| Dell          | MXG061                      | Notebook    | [89a5b20193](https://linux-hardware.org/?probe=89a5b20193) | Oct 10, 2021 |
| Biostar       | G41D3C                      | Desktop     | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Biostar       | G41D3C                      | Desktop     | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| Acer          | Swift SF314-56              | Notebook    | [263d6e38b7](https://linux-hardware.org/?probe=263d6e38b7) | Oct 01, 2021 |
| Acer          | Swift SF314-56              | Notebook    | [bb0f894bce](https://linux-hardware.org/?probe=bb0f894bce) | Oct 01, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [ddb041ded0](https://linux-hardware.org/?probe=ddb041ded0) | Sep 15, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [a9335318aa](https://linux-hardware.org/?probe=a9335318aa) | Sep 15, 2021 |
| Dell          | Vostro1710                  | Notebook    | [d50123c66a](https://linux-hardware.org/?probe=d50123c66a) | Sep 01, 2021 |
| Dell          | Inspiron 5452               | Notebook    | [0c9b3ec7a9](https://linux-hardware.org/?probe=0c9b3ec7a9) | Aug 07, 2021 |
| Intel         | DG31PR AAD97573-300         | Desktop     | [0a0a8059c2](https://linux-hardware.org/?probe=0a0a8059c2) | Aug 04, 2021 |
| Intel         | DG31PR AAD97573-300         | Desktop     | [6b7f5cdcc8](https://linux-hardware.org/?probe=6b7f5cdcc8) | Jul 21, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b2b851f7d2](https://linux-hardware.org/?probe=b2b851f7d2) | Jul 12, 2021 |
| ASUSTek       | X541SA                      | Notebook    | [ed8bb15f60](https://linux-hardware.org/?probe=ed8bb15f60) | Jul 11, 2021 |
| HP            | 0A98h                       | Desktop     | [9844591cd4](https://linux-hardware.org/?probe=9844591cd4) | Jul 02, 2021 |
| ECS           | Livermore                   | Desktop     | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [5943266aca](https://linux-hardware.org/?probe=5943266aca) | Jun 18, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [3b4a122b75](https://linux-hardware.org/?probe=3b4a122b75) | Jun 18, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [117e8bf660](https://linux-hardware.org/?probe=117e8bf660) | Jun 17, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a9255b2217](https://linux-hardware.org/?probe=a9255b2217) | Jun 04, 2021 |
| MSI           | Boston                      | Desktop     | [5cca21c281](https://linux-hardware.org/?probe=5cca21c281) | Apr 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [58bf661e8d](https://linux-hardware.org/?probe=58bf661e8d) | Apr 15, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [b0bcc6c31c](https://linux-hardware.org/?probe=b0bcc6c31c) | Apr 12, 2021 |
| MSI           | B75A-G43                    | Desktop     | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [b9140b8786](https://linux-hardware.org/?probe=b9140b8786) | Mar 29, 2021 |
| ASUSTek       | K54LY                       | Notebook    | [dc7d86f51e](https://linux-hardware.org/?probe=dc7d86f51e) | Mar 21, 2021 |
| Acer          | Aspire V5-552               | Notebook    | [7a32a8a1c3](https://linux-hardware.org/?probe=7a32a8a1c3) | Mar 03, 2021 |
| HP            | Compaq 6735b                | Notebook    | [0f2afbc99a](https://linux-hardware.org/?probe=0f2afbc99a) | Feb 18, 2021 |
| Dell          | Inspiron 7559               | Notebook    | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| HP            | Laptop 17-by2xxx            | Notebook    | [729abf0085](https://linux-hardware.org/?probe=729abf0085) | Jan 30, 2021 |
| Acer          | Predator PH317-52           | Notebook    | [1bd05ad341](https://linux-hardware.org/?probe=1bd05ad341) | Jan 24, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [84cb4ded95](https://linux-hardware.org/?probe=84cb4ded95) | Dec 30, 2020 |
| HP            | 655                         | Notebook    | [a6913cacf3](https://linux-hardware.org/?probe=a6913cacf3) | Dec 28, 2020 |
| HP            | 655                         | Notebook    | [2a4c81218e](https://linux-hardware.org/?probe=2a4c81218e) | Dec 27, 2020 |
| Toshiba       | Satellite T215D             | Notebook    | [084f254e1f](https://linux-hardware.org/?probe=084f254e1f) | Dec 23, 2020 |
| Toshiba       | Satellite T215D             | Notebook    | [bdb8fe4e55](https://linux-hardware.org/?probe=bdb8fe4e55) | Dec 23, 2020 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [19e83c7c24](https://linux-hardware.org/?probe=19e83c7c24) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [77f93a017c](https://linux-hardware.org/?probe=77f93a017c) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a6654cf4f1](https://linux-hardware.org/?probe=a6654cf4f1) | Dec 21, 2020 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [8f8f606051](https://linux-hardware.org/?probe=8f8f606051) | Dec 16, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| ASUSTek       | 1001PX                      | Notebook    | [9f911bde1c](https://linux-hardware.org/?probe=9f911bde1c) | Dec 11, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [ba47872fd5](https://linux-hardware.org/?probe=ba47872fd5) | Dec 02, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [c4216f5d80](https://linux-hardware.org/?probe=c4216f5d80) | Dec 02, 2020 |
| HP            | 0ACCh                       | Desktop     | [7f4d2a2df4](https://linux-hardware.org/?probe=7f4d2a2df4) | Nov 23, 2020 |
| HP            | 0ACCh                       | Desktop     | [d28f3f3195](https://linux-hardware.org/?probe=d28f3f3195) | Nov 23, 2020 |
| Lenovo        | ThinkCentre M91p 4524RS6    | Desktop     | [cf9c213443](https://linux-hardware.org/?probe=cf9c213443) | Nov 21, 2020 |
| Lenovo        | ThinkCentre M91p 4524RS6    | Desktop     | [66d1757c3f](https://linux-hardware.org/?probe=66d1757c3f) | Nov 21, 2020 |
| HP            | 3032h                       | Desktop     | [1a10cb8912](https://linux-hardware.org/?probe=1a10cb8912) | Nov 20, 2020 |
| Intel         | H61M-S1                     | Desktop     | [f31ad89e75](https://linux-hardware.org/?probe=f31ad89e75) | Nov 02, 2020 |
| Intel         | H61M-S1                     | Desktop     | [f381b5e487](https://linux-hardware.org/?probe=f381b5e487) | Nov 02, 2020 |
| Lenovo        | ThinkCentre A55 9265BL7     | Desktop     | [1e00064286](https://linux-hardware.org/?probe=1e00064286) | Oct 30, 2020 |
| HP            | 2AA6 PVT                    | Desktop     | [3ee3ed2e83](https://linux-hardware.org/?probe=3ee3ed2e83) | Oct 06, 2020 |
| Dell          | Latitude D530               | Notebook    | [4fe18e86ac](https://linux-hardware.org/?probe=4fe18e86ac) | Sep 27, 2020 |
| MSI           | Z77A-G43                    | Desktop     | [4420c076a7](https://linux-hardware.org/?probe=4420c076a7) | Sep 03, 2020 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [2a6ae45bc4](https://linux-hardware.org/?probe=2a6ae45bc4) | Aug 20, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| Jetway        | I61MG4                      | Desktop     | [f677e427be](https://linux-hardware.org/?probe=f677e427be) | Jul 30, 2020 |
| Jetway        | I61MG4                      | Desktop     | [2e5f79f476](https://linux-hardware.org/?probe=2e5f79f476) | Jul 29, 2020 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [cf8c7c6ae6](https://linux-hardware.org/?probe=cf8c7c6ae6) | Jul 29, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [63a7ae1967](https://linux-hardware.org/?probe=63a7ae1967) | Jul 24, 2020 |
| Google        | Chell                       | Notebook    | [cf727e9a6e](https://linux-hardware.org/?probe=cf727e9a6e) | Jul 23, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [2d9ea757d1](https://linux-hardware.org/?probe=2d9ea757d1) | Jul 14, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [1a4ee704d9](https://linux-hardware.org/?probe=1a4ee704d9) | Jul 14, 2020 |
| Lenovo        | 3000 V200 0764A11           | Notebook    | [8492023ae0](https://linux-hardware.org/?probe=8492023ae0) | Jul 13, 2020 |
| TR            | ST Pro-KN                   | Notebook    | [e78b2937ef](https://linux-hardware.org/?probe=e78b2937ef) | Jul 01, 2020 |
| Acer          | EQ35M                       | Desktop     | [f2dbd9e441](https://linux-hardware.org/?probe=f2dbd9e441) | Jun 23, 2020 |
| Acer          | EQ35M                       | Desktop     | [5ebf9a4f1a](https://linux-hardware.org/?probe=5ebf9a4f1a) | Jun 23, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |
| ASUSTek       | N750JK                      | Notebook    | [9102fbcf41](https://linux-hardware.org/?probe=9102fbcf41) | Jun 02, 2020 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [92c219ffb4](https://linux-hardware.org/?probe=92c219ffb4) | May 14, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Linux Lite 5.8 | 25        | 17.36%  |
| Linux Lite 6.0 | 19        | 13.19%  |
| Linux Lite 5.4 | 17        | 11.81%  |
| Linux Lite 5.2 | 17        | 11.81%  |
| Linux Lite 5.0 | 17        | 11.81%  |
| Linux Lite 5.6 | 15        | 10.42%  |
| Linux Lite 6.2 | 14        | 9.72%   |
| Linux Lite 6.4 | 10        | 6.94%   |
| Linux Lite 3.8 | 5         | 3.47%   |
| Linux Lite 4.8 | 2         | 1.39%   |
| Linux Lite 4.6 | 1         | 0.69%   |
| Linux Lite 4.4 | 1         | 0.69%   |
| Linux Lite 4.2 | 1         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Lite | 142       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 6         | 3.97%   |
| 5.15.0-69-generic | 6         | 3.97%   |
| 5.4.0-91-generic  | 5         | 3.31%   |
| 5.4.0-70-generic  | 5         | 3.31%   |
| 5.4.0-96-generic  | 4         | 2.65%   |
| 5.4.0-52-generic  | 4         | 2.65%   |
| 5.4.0-40-generic  | 4         | 2.65%   |
| 5.4.0-109-generic | 4         | 2.65%   |
| 5.4.0-104-generic | 4         | 2.65%   |
| 5.15.0-71-generic | 4         | 2.65%   |
| 5.15.0-33-generic | 4         | 2.65%   |
| 5.4.0-81-generic  | 3         | 1.99%   |
| 5.4.0-58-generic  | 3         | 1.99%   |
| 5.4.0-48-generic  | 3         | 1.99%   |
| 5.4.0-113-generic | 3         | 1.99%   |
| 5.4.0-107-generic | 3         | 1.99%   |
| 5.15.0-58-generic | 3         | 1.99%   |
| 5.15.0-52-generic | 3         | 1.99%   |
| 5.15.0-47-generic | 3         | 1.99%   |
| 5.15.0-46-generic | 3         | 1.99%   |
| 5.4.0-90-generic  | 2         | 1.32%   |
| 5.4.0-88-generic  | 2         | 1.32%   |
| 5.4.0-80-generic  | 2         | 1.32%   |
| 5.4.0-74-generic  | 2         | 1.32%   |
| 5.4.0-54-generic  | 2         | 1.32%   |
| 5.4.0-33-generic  | 2         | 1.32%   |
| 5.4.0-110-generic | 2         | 1.32%   |
| 5.4.0-105-generic | 2         | 1.32%   |
| 5.15.0-73-generic | 2         | 1.32%   |
| 5.15.0-60-generic | 2         | 1.32%   |
| 5.15.0-56-generic | 2         | 1.32%   |
| 5.15.0-48-generic | 2         | 1.32%   |
| 4.4.0-112-generic | 2         | 1.32%   |
| 6.1.0-1.linuxlite | 1         | 0.66%   |
| 6.0.0-1.linuxlite | 1         | 0.66%   |
| 6.0.0             | 1         | 0.66%   |
| 5.9.0             | 1         | 0.66%   |
| 5.4.0-99-generic  | 1         | 0.66%   |
| 5.4.0-94-generic  | 1         | 0.66%   |
| 5.4.0-77-generic  | 1         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 85        | 58.22%  |
| 5.15.0  | 41        | 28.08%  |
| 4.15.0  | 5         | 3.42%   |
| 4.4.0   | 4         | 2.74%   |
| 5.13.0  | 3         | 2.05%   |
| 6.0.0   | 2         | 1.37%   |
| 6.1.0   | 1         | 0.68%   |
| 5.9.0   | 1         | 0.68%   |
| 5.19.0  | 1         | 0.68%   |
| 5.16.9  | 1         | 0.68%   |
| 5.16.0  | 1         | 0.68%   |
| 5.10.0  | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 85        | 58.22%  |
| 5.15    | 41        | 28.08%  |
| 4.15    | 5         | 3.42%   |
| 4.4     | 4         | 2.74%   |
| 5.13    | 3         | 2.05%   |
| 6.0     | 2         | 1.37%   |
| 5.16    | 2         | 1.37%   |
| 6.1     | 1         | 0.68%   |
| 5.9     | 1         | 0.68%   |
| 5.19    | 1         | 0.68%   |
| 5.10    | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 138       | 97.18%  |
| i686   | 4         | 2.82%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 114       | 80.28%  |
| GNOME   | 25        | 17.61%  |
| Unknown | 2         | 1.41%   |
| Deepin  | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 140       | 98.59%  |
| Tty     | 1         | 0.7%    |
| Unknown | 1         | 0.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 91        | 63.19%  |
| TDM     | 28        | 19.44%  |
| Unknown | 24        | 16.67%  |
| GDM     | 1         | 0.69%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 68        | 47.89%  |
| de_DE | 10        | 7.04%   |
| pl_PL | 8         | 5.63%   |
| pt_BR | 7         | 4.93%   |
| fr_FR | 7         | 4.93%   |
| en_GB | 6         | 4.23%   |
| es_MX | 4         | 2.82%   |
| es_ES | 4         | 2.82%   |
| ru_UA | 3         | 2.11%   |
| en_CA | 3         | 2.11%   |
| ru_RU | 2         | 1.41%   |
| it_IT | 2         | 1.41%   |
| zh_CN | 1         | 0.7%    |
| tr_TR | 1         | 0.7%    |
| pt_PT | 1         | 0.7%    |
| nl_NL | 1         | 0.7%    |
| hu_HU | 1         | 0.7%    |
| fr_CA | 1         | 0.7%    |
| es_CO | 1         | 0.7%    |
| es_CL | 1         | 0.7%    |
| es_AR | 1         | 0.7%    |
| en_SG | 1         | 0.7%    |
| en_PH | 1         | 0.7%    |
| en_NZ | 1         | 0.7%    |
| en_IN | 1         | 0.7%    |
| en_IE | 1         | 0.7%    |
| en_AU | 1         | 0.7%    |
| da_DK | 1         | 0.7%    |
| C     | 1         | 0.7%    |
| ar_SA | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 79        | 55.63%  |
| EFI  | 63        | 44.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 126       | 88.73%  |
| Overlay | 10        | 7.04%   |
| Tmpfs   | 2         | 1.41%   |
| Btrfs   | 2         | 1.41%   |
| Zfs     | 1         | 0.7%    |
| Ext3    | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 63        | 44.37%  |
| Unknown | 40        | 28.17%  |
| MBR     | 39        | 27.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 82.52%  |
| Yes       | 25        | 17.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 70.63%  |
| Yes       | 42        | 29.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 27        | 19.01%  |
| ASUSTek Computer    | 19        | 13.38%  |
| Lenovo              | 18        | 12.68%  |
| Acer                | 12        | 8.45%   |
| Dell                | 10        | 7.04%   |
| MSI                 | 6         | 4.23%   |
| Apple               | 6         | 4.23%   |
| Samsung Electronics | 4         | 2.82%   |
| Pegatron            | 3         | 2.11%   |
| Gigabyte Technology | 3         | 2.11%   |
| Fujitsu             | 3         | 2.11%   |
| ASRock              | 3         | 2.11%   |
| Toshiba             | 2         | 1.41%   |
| Minix               | 2         | 1.41%   |
| Inventec            | 2         | 1.41%   |
| Intel               | 2         | 1.41%   |
| Foxconn             | 2         | 1.41%   |
| UNOWHY              | 1         | 0.7%    |
| UMAX                | 1         | 0.7%    |
| TR                  | 1         | 0.7%    |
| Thomson             | 1         | 0.7%    |
| Sony                | 1         | 0.7%    |
| Packard Bell        | 1         | 0.7%    |
| Jetway              | 1         | 0.7%    |
| Insignia            | 1         | 0.7%    |
| Google              | 1         | 0.7%    |
| Gateway             | 1         | 0.7%    |
| Fujitsu Siemens     | 1         | 0.7%    |
| EVGA                | 1         | 0.7%    |
| Braview             | 1         | 0.7%    |
| Biostar             | 1         | 0.7%    |
| AWOW                | 1         | 0.7%    |
| AMI                 | 1         | 0.7%    |
| American Megatrends | 1         | 0.7%    |
| ABIT                | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7758                           | 2         | 1.41%   |
| UNOWHY Y13G010S4EI                    | 1         | 0.7%    |
| UMAX VisionBook 12Wi 64G              | 1         | 0.7%    |
| TR ST Pro-KN                          | 1         | 0.7%    |
| Toshiba Satellite T215D               | 1         | 0.7%    |
| Toshiba QOSMIO X70-B                  | 1         | 0.7%    |
| Thomson PT-NEO14A.2WH32               | 1         | 0.7%    |
| Sony VGC-JS54FB_W                     | 1         | 0.7%    |
| Samsung X420/X520                     | 1         | 0.7%    |
| Samsung NC110P/NC108P/NC111P          | 1         | 0.7%    |
| Samsung 905S3G/906S3G/915S3G/9305SG   | 1         | 0.7%    |
| Samsung 530XBB                        | 1         | 0.7%    |
| Pegatron H36FF                        | 1         | 0.7%    |
| Pegatron 520-1135la                   | 1         | 0.7%    |
| Pegatron 520-1030a                    | 1         | 0.7%    |
| Packard Bell ISTART D2314             | 1         | 0.7%    |
| MSI MS-N014                           | 1         | 0.7%    |
| MSI MS-7C95                           | 1         | 0.7%    |
| MSI MS-7996                           | 1         | 0.7%    |
| MSI FZ079AA-ABF a6625fr               | 1         | 0.7%    |
| Minix Z83-4                           | 1         | 0.7%    |
| Minix Z64                             | 1         | 0.7%    |
| Lenovo Yoga C740 81TC                 | 1         | 0.7%    |
| Lenovo ThinkStation P320 30BH000BFR   | 1         | 0.7%    |
| Lenovo ThinkPad X240 20AMS1J100       | 1         | 0.7%    |
| Lenovo ThinkPad T400 6475E13          | 1         | 0.7%    |
| Lenovo ThinkPad L480 20LS001AMC       | 1         | 0.7%    |
| Lenovo ThinkPad A475 20KMS08300       | 1         | 0.7%    |
| Lenovo ThinkCentre neo 50t Gen 3 11SE | 1         | 0.7%    |
| Lenovo ThinkCentre M91p 4524RS6       | 1         | 0.7%    |
| Lenovo ThinkCentre M91p 4518E2M       | 1         | 0.7%    |
| Lenovo ThinkCentre A55 9265BL7        | 1         | 0.7%    |
| Lenovo MIIX 300-10IBY 80NR            | 1         | 0.7%    |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1   | 1         | 0.7%    |
| Lenovo IdeaPad 330S-15AST 81F9        | 1         | 0.7%    |
| Lenovo IdeaPad 320-15ABR 80XS         | 1         | 0.7%    |
| Lenovo IdeaPad 100-15IBY 80MJ         | 1         | 0.7%    |
| Lenovo IdeaPad 100-14IBY 80MH         | 1         | 0.7%    |
| Lenovo H505S 10107                    | 1         | 0.7%    |
| Lenovo 3000 V200 0764A11              | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HP Compaq               | 8         | 5.63%   |
| Acer Aspire             | 7         | 4.93%   |
| Lenovo IdeaPad          | 5         | 3.52%   |
| Lenovo ThinkPad         | 4         | 2.82%   |
| Lenovo ThinkCentre      | 4         | 2.82%   |
| HP Laptop               | 4         | 2.82%   |
| Dell Inspiron           | 4         | 2.82%   |
| HP EliteBook            | 3         | 2.11%   |
| MSI MS-7758             | 2         | 1.41%   |
| Inventec Dell           | 2         | 1.41%   |
| HP Pavilion             | 2         | 1.41%   |
| Dell Latitude           | 2         | 1.41%   |
| ASUS VivoBook           | 2         | 1.41%   |
| UNOWHY Y13G010S4EI      | 1         | 0.7%    |
| UMAX VisionBook         | 1         | 0.7%    |
| TR ST                   | 1         | 0.7%    |
| Toshiba Satellite       | 1         | 0.7%    |
| Toshiba QOSMIO          | 1         | 0.7%    |
| Thomson PT-NEO14A.2WH32 | 1         | 0.7%    |
| Sony VGC-JS54FB         | 1         | 0.7%    |
| Samsung X420            | 1         | 0.7%    |
| Samsung NC110P          | 1         | 0.7%    |
| Samsung 905S3G          | 1         | 0.7%    |
| Samsung 530XBB          | 1         | 0.7%    |
| Pegatron H36FF          | 1         | 0.7%    |
| Pegatron 520-1135la     | 1         | 0.7%    |
| Pegatron 520-1030a      | 1         | 0.7%    |
| Packard Bell ISTART     | 1         | 0.7%    |
| MSI MS-N014             | 1         | 0.7%    |
| MSI MS-7C95             | 1         | 0.7%    |
| MSI MS-7996             | 1         | 0.7%    |
| MSI FZ079AA-ABF         | 1         | 0.7%    |
| Minix Z83-4             | 1         | 0.7%    |
| Minix Z64               | 1         | 0.7%    |
| Lenovo Yoga             | 1         | 0.7%    |
| Lenovo ThinkStation     | 1         | 0.7%    |
| Lenovo MIIX             | 1         | 0.7%    |
| Lenovo H505S            | 1         | 0.7%    |
| Lenovo 3000             | 1         | 0.7%    |
| Jetway I61MG4           | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2008 | 16        | 11.27%  |
| 2011 | 15        | 10.56%  |
| 2010 | 15        | 10.56%  |
| 2012 | 12        | 8.45%   |
| 2018 | 11        | 7.75%   |
| 2007 | 11        | 7.75%   |
| 2014 | 10        | 7.04%   |
| 2020 | 9         | 6.34%   |
| 2015 | 8         | 5.63%   |
| 2016 | 7         | 4.93%   |
| 2019 | 5         | 3.52%   |
| 2017 | 5         | 3.52%   |
| 2013 | 4         | 2.82%   |
| 2009 | 4         | 2.82%   |
| 2022 | 3         | 2.11%   |
| 2021 | 3         | 2.11%   |
| 2006 | 2         | 1.41%   |
| 2023 | 1         | 0.7%    |
| 2004 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 80        | 56.34%  |
| Desktop     | 51        | 35.92%  |
| All in one  | 5         | 3.52%   |
| Mini pc     | 3         | 2.11%   |
| Tablet      | 2         | 1.41%   |
| Convertible | 1         | 0.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 136       | 95.77%  |
| Enabled  | 6         | 4.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 141       | 99.3%   |
| Yes  | 1         | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 47        | 33.1%   |
| 1.01-2.0   | 27        | 19.01%  |
| 4.01-8.0   | 25        | 17.61%  |
| 16.01-24.0 | 15        | 10.56%  |
| 8.01-16.0  | 14        | 9.86%   |
| 32.01-64.0 | 6         | 4.23%   |
| 0.51-1.0   | 4         | 2.82%   |
| 2.01-3.0   | 3         | 2.11%   |
| 24.01-32.0 | 1         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 69        | 47.59%  |
| 2.01-3.0  | 31        | 21.38%  |
| 0.51-1.0  | 21        | 14.48%  |
| 3.01-4.0  | 10        | 6.9%    |
| 4.01-8.0  | 9         | 6.21%   |
| 0.01-0.5  | 3         | 2.07%   |
| 8.01-16.0 | 2         | 1.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 100       | 70.42%  |
| 2      | 31        | 21.83%  |
| 3      | 7         | 4.93%   |
| 0      | 2         | 1.41%   |
| 5      | 1         | 0.7%    |
| 4      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 57.04%  |
| Yes       | 61        | 42.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 86.62%  |
| No        | 19        | 13.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 80.99%  |
| No        | 27        | 19.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 50.7%   |
| No        | 70        | 49.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 23        | 16.2%   |
| Germany      | 12        | 8.45%   |
| Brazil       | 12        | 8.45%   |
| France       | 9         | 6.34%   |
| Poland       | 8         | 5.63%   |
| UK           | 7         | 4.93%   |
| Romania      | 6         | 4.23%   |
| Canada       | 6         | 4.23%   |
| Ukraine      | 5         | 3.52%   |
| Mexico       | 5         | 3.52%   |
| Spain        | 4         | 2.82%   |
| Italy        | 4         | 2.82%   |
| Turkey       | 3         | 2.11%   |
| Russia       | 3         | 2.11%   |
| Peru         | 3         | 2.11%   |
| Australia    | 3         | 2.11%   |
| Philippines  | 2         | 1.41%   |
| Netherlands  | 2         | 1.41%   |
| Chile        | 2         | 1.41%   |
| Venezuela    | 1         | 0.7%    |
| Thailand     | 1         | 0.7%    |
| Slovakia     | 1         | 0.7%    |
| Singapore    | 1         | 0.7%    |
| Serbia       | 1         | 0.7%    |
| Saudi Arabia | 1         | 0.7%    |
| Qatar        | 1         | 0.7%    |
| Portugal     | 1         | 0.7%    |
| New Zealand  | 1         | 0.7%    |
| Myanmar      | 1         | 0.7%    |
| Malaysia     | 1         | 0.7%    |
| Japan        | 1         | 0.7%    |
| Ireland      | 1         | 0.7%    |
| Iran         | 1         | 0.7%    |
| Indonesia    | 1         | 0.7%    |
| India        | 1         | 0.7%    |
| Hungary      | 1         | 0.7%    |
| Guadeloupe   | 1         | 0.7%    |
| Greenland    | 1         | 0.7%    |
| El Salvador  | 1         | 0.7%    |
| Czechia      | 1         | 0.7%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Pabianice          | 3         | 2.07%   |
| Würzburg          | 2         | 1.38%   |
| Warsaw             | 2         | 1.38%   |
| Sydney             | 2         | 1.38%   |
| Sao Paulo          | 2         | 1.38%   |
| Paris              | 2         | 1.38%   |
| Ottawa             | 2         | 1.38%   |
| Odessa             | 2         | 1.38%   |
| Mexico City        | 2         | 1.38%   |
| Lublin             | 2         | 1.38%   |
| Lima               | 2         | 1.38%   |
| Kyiv               | 2         | 1.38%   |
| Frankfurt am Main  | 2         | 1.38%   |
| Żywiec            | 1         | 0.69%   |
| Yangon             | 1         | 0.69%   |
| Wiesbaden          | 1         | 0.69%   |
| Wellington         | 1         | 0.69%   |
| Waterbury          | 1         | 0.69%   |
| Washington         | 1         | 0.69%   |
| Wahroonga          | 1         | 0.69%   |
| Voluntari          | 1         | 0.69%   |
| Vinnytsia          | 1         | 0.69%   |
| Varennes-les-Narcy | 1         | 0.69%   |
| Vancouver          | 1         | 0.69%   |
| Valencia           | 1         | 0.69%   |
| Tucape             | 1         | 0.69%   |
| Trujillo           | 1         | 0.69%   |
| Toronto            | 1         | 0.69%   |
| Thetford-Mines     | 1         | 0.69%   |
| Teresina           | 1         | 0.69%   |
| Tekirdağ          | 1         | 0.69%   |
| Tarragona          | 1         | 0.69%   |
| Tamm               | 1         | 0.69%   |
| Svidník           | 1         | 0.69%   |
| Surabaya           | 1         | 0.69%   |
| Subotica           | 1         | 0.69%   |
| Studenka           | 1         | 0.69%   |
| St. Petersburg     | 1         | 0.69%   |
| Singapore          | 1         | 0.69%   |
| Shadrinsk          | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 40     | 19.89%  |
| WDC                 | 27        | 36     | 15.34%  |
| Samsung Electronics | 20        | 21     | 11.36%  |
| Toshiba             | 13        | 14     | 7.39%   |
| Unknown             | 12        | 16     | 6.82%   |
| Kingston            | 9         | 11     | 5.11%   |
| SanDisk             | 7         | 7      | 3.98%   |
| SK hynix            | 5         | 6      | 2.84%   |
| Hitachi             | 5         | 5      | 2.84%   |
| HGST                | 5         | 5      | 2.84%   |
| Crucial             | 5         | 5      | 2.84%   |
| Micron Technology   | 4         | 5      | 2.27%   |
| Goodram             | 3         | 3      | 1.7%    |
| Apple               | 3         | 3      | 1.7%    |
| A-DATA Technology   | 3         | 3      | 1.7%    |
| China               | 2         | 2      | 1.14%   |
| PNY                 | 1         | 1      | 0.57%   |
| Phison              | 1         | 1      | 0.57%   |
| OCZ                 | 1         | 1      | 0.57%   |
| Maxtor              | 1         | 1      | 0.57%   |
| Mass                | 1         | 1      | 0.57%   |
| LITEON              | 1         | 1      | 0.57%   |
| Intenso             | 1         | 1      | 0.57%   |
| Intel               | 1         | 1      | 0.57%   |
| HS-SSD-E100         | 1         | 1      | 0.57%   |
| HPE                 | 1         | 1      | 0.57%   |
| Hewlett-Packard     | 1         | 1      | 0.57%   |
| Gigabyte Technology | 1         | 1      | 0.57%   |
| Fujitsu             | 1         | 1      | 0.57%   |
| Fanxiang            | 1         | 2      | 0.57%   |
| ASUS-PHISON         | 1         | 2      | 0.57%   |
| ASMT                | 1         | 1      | 0.57%   |
| Apacer              | 1         | 1      | 0.57%   |
| Unknown             | 1         | 1      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 4         | 2.13%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.6%    |
| Seagate ST500DM002-1BD142 500GB      | 3         | 1.6%    |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.6%    |
| WDC WDS120G2G0A-00JH30 128GB SSD     | 2         | 1.06%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 1.06%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 1.06%   |
| Unknown DA4064  64GB                 | 2         | 1.06%   |
| Seagate ST9320325AS 320GB            | 2         | 1.06%   |
| Seagate ST3500418AS 500GB            | 2         | 1.06%   |
| SanDisk SDSSDA240G 240GB             | 2         | 1.06%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD  | 2         | 1.06%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.06%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.53%   |
| WDC WDS250G2B0A 250GB SSD            | 1         | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.53%   |
| WDC WD800JD-60LSA0 80GB              | 1         | 0.53%   |
| WDC WD5000LPCX-75VHAT0 500GB         | 1         | 0.53%   |
| WDC WD5000AAKX-003CA0 500GB          | 1         | 0.53%   |
| WDC WD5000AAKS-60WWPA0 500GB         | 1         | 0.53%   |
| WDC WD5000AADS-56S9B0 500GB          | 1         | 0.53%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 0.53%   |
| WDC WD5000AACS-00G8B1 500GB          | 1         | 0.53%   |
| WDC WD2500BEVS-00UST0 250GB          | 1         | 0.53%   |
| WDC WD2500BEVE-00A0HT0 250GB         | 1         | 0.53%   |
| WDC WD20PURX-64PFUY0 2TB             | 1         | 0.53%   |
| WDC WD2005FBYZ-01YCBB2 2TB           | 1         | 0.53%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.53%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1         | 0.53%   |
| WDC WD10EZEX-07WN4A0 1TB             | 1         | 0.53%   |
| WDC WD10EADS-00L5B1 1TB              | 1         | 0.53%   |
| WDC WD1003FBYX-01Y7B1 1TB            | 1         | 0.53%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB   | 1         | 0.53%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.53%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.53%   |
| Unknown SN64G  64GB                  | 1         | 0.53%   |
| Unknown SLD64G  64GB                 | 1         | 0.53%   |
| Unknown SD64G  64GB                  | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 40     | 41.67%  |
| WDC                 | 20        | 25     | 23.81%  |
| Toshiba             | 12        | 13     | 14.29%  |
| Hitachi             | 5         | 5      | 5.95%   |
| HGST                | 5         | 5      | 5.95%   |
| Samsung Electronics | 3         | 4      | 3.57%   |
| Maxtor              | 1         | 1      | 1.19%   |
| HPE                 | 1         | 1      | 1.19%   |
| Fujitsu             | 1         | 1      | 1.19%   |
| Apple               | 1         | 1      | 1.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 10     | 17.24%  |
| Kingston            | 7         | 9      | 12.07%  |
| SanDisk             | 6         | 6      | 10.34%  |
| WDC                 | 5         | 6      | 8.62%   |
| Crucial             | 5         | 5      | 8.62%   |
| Micron Technology   | 3         | 4      | 5.17%   |
| GOODRAM             | 3         | 3      | 5.17%   |
| A-DATA Technology   | 3         | 3      | 5.17%   |
| China               | 2         | 2      | 3.45%   |
| Apple               | 2         | 2      | 3.45%   |
| Toshiba             | 1         | 1      | 1.72%   |
| SK hynix            | 1         | 2      | 1.72%   |
| PNY                 | 1         | 1      | 1.72%   |
| OCZ                 | 1         | 1      | 1.72%   |
| LITEON              | 1         | 1      | 1.72%   |
| Intel               | 1         | 1      | 1.72%   |
| Hewlett-Packard     | 1         | 1      | 1.72%   |
| Gigabyte Technology | 1         | 1      | 1.72%   |
| Fanxiang            | 1         | 2      | 1.72%   |
| ASUS-PHISON         | 1         | 2      | 1.72%   |
| ASMT                | 1         | 1      | 1.72%   |
| Apacer              | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 77        | 96     | 46.11%  |
| SSD     | 56        | 65     | 33.53%  |
| NVMe    | 16        | 19     | 9.58%   |
| MMC     | 15        | 19     | 8.98%   |
| Unknown | 3         | 3      | 1.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 116       | 158    | 75.82%  |
| NVMe | 16        | 19     | 10.46%  |
| MMC  | 15        | 19     | 9.8%    |
| SAS  | 6         | 6      | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 95        | 123    | 72.52%  |
| 0.51-1.0   | 31        | 32     | 23.66%  |
| 1.01-2.0   | 4         | 5      | 3.05%   |
| 4.01-10.0  | 1         | 1      | 0.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 51        | 35.42%  |
| 251-500        | 28        | 19.44%  |
| 51-100         | 22        | 15.28%  |
| 501-1000       | 12        | 8.33%   |
| 21-50          | 11        | 7.64%   |
| 1-20           | 10        | 6.94%   |
| More than 3000 | 5         | 3.47%   |
| 1001-2000      | 4         | 2.78%   |
| 2001-3000      | 1         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 65        | 44.83%  |
| 21-50     | 35        | 24.14%  |
| 51-100    | 20        | 13.79%  |
| 101-250   | 14        | 9.66%   |
| 501-1000  | 4         | 2.76%   |
| 251-500   | 3         | 2.07%   |
| 2001-3000 | 2         | 1.38%   |
| 1001-2000 | 2         | 1.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 3.57%   |
| WDC WD800JD-60LSA0 80GB                        | 1         | 1      | 3.57%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 3.57%   |
| WDC WD5000AAKS-60WWPA0 500GB                   | 1         | 1      | 3.57%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 3.57%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 3.57%   |
| Toshiba MK3265GSX 320GB                        | 1         | 1      | 3.57%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 3.57%   |
| Seagate ST980811AS 80GB                        | 1         | 1      | 3.57%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 3.57%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 3.57%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 3.57%   |
| Seagate ST9320320AS 320GB                      | 1         | 1      | 3.57%   |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 3.57%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 3.57%   |
| Seagate ST3750528AS 752GB                      | 1         | 1      | 3.57%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 3.57%   |
| SanDisk SSD PLUS 120GB                         | 1         | 1      | 3.57%   |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 3.57%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 3.57%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 3.57%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 3.57%   |
| Hitachi HDS721616PLA380 160GB                  | 1         | 1      | 3.57%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 3.57%   |
| Apple SSD SM128C 121GB                         | 1         | 1      | 3.57%   |
| Apacer 16GB SATA Flash Drive SSD               | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 35.71%  |
| WDC                 | 6         | 6      | 21.43%  |
| Toshiba             | 3         | 3      | 10.71%  |
| Hitachi             | 3         | 3      | 10.71%  |
| SanDisk             | 1         | 1      | 3.57%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Apple               | 1         | 1      | 3.57%   |
| Apacer              | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 43.48%  |
| WDC                 | 5         | 5      | 21.74%  |
| Toshiba             | 3         | 3      | 13.04%  |
| Hitachi             | 3         | 3      | 13.04%  |
| Samsung Electronics | 1         | 1      | 4.35%   |
| HGST                | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 23     | 80.77%  |
| SSD  | 5         | 5      | 19.23%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 64        | 83     | 43.24%  |
| Detected | 59        | 91     | 39.86%  |
| Malfunc  | 25        | 28     | 16.89%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 99        | 65.13%  |
| AMD                         | 25        | 16.45%  |
| Samsung Electronics         | 7         | 4.61%   |
| Nvidia                      | 6         | 3.95%   |
| SK hynix                    | 3         | 1.97%   |
| SanDisk                     | 3         | 1.97%   |
| Marvell Technology Group    | 2         | 1.32%   |
| Kingston Technology Company | 2         | 1.32%   |
| Phison Electronics          | 1         | 0.66%   |
| Micron Technology           | 1         | 0.66%   |
| LSI Logic / Symbios Logic   | 1         | 0.66%   |
| JMicron Technology          | 1         | 0.66%   |
| Broadcom / LSI              | 1         | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 8.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 4.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 3.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7         | 3.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 3.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 2.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 2.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 2.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 1.55%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 1.55%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 1.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.55%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3         | 1.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 1.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 1.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 2         | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.04%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.04%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 2         | 1.04%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2         | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.04%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 1.04%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 1.04%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.04%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 101       | 60.12%  |
| IDE  | 43        | 25.6%   |
| NVMe | 16        | 9.52%   |
| RAID | 7         | 4.17%   |
| SCSI | 1         | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 113       | 79.58%  |
| AMD    | 29        | 20.42%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 2.82%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 3         | 2.11%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 1.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 1.41%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2         | 1.41%   |
| Intel Core 2 CPU T7600 @ 2.33GHz              | 2         | 1.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.41%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.41%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.41%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.41%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 1.41%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.41%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.7%    |
| Intel Xeon CPU E5450 @ 3.00GHz                | 1         | 0.7%    |
| Intel Xeon CPU E5410 @ 2.33GHz                | 1         | 0.7%    |
| Intel Xeon CPU 5150 @ 2.66GHz                 | 1         | 0.7%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.7%    |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz   | 1         | 0.7%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1         | 0.7%    |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 1         | 0.7%    |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.7%    |
| Intel Pentium D CPU 3.40GHz                   | 1         | 0.7%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.7%    |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.7%    |
| Intel Pentium CPU J2850 @ 2.41GHz             | 1         | 0.7%    |
| Intel Pentium CPU E5500 @ 2.80GHz             | 1         | 0.7%    |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 0.7%    |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.7%    |
| Intel Genuine CPU T2050 @ 1.60GHz             | 1         | 0.7%    |
| Intel Core m7-6Y75 CPU @ 1.20GHz              | 1         | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.7%    |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.7%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.7%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.7%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.7%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 14.08%  |
| Intel Core 2 Duo        | 14        | 9.86%   |
| Intel Celeron           | 13        | 9.15%   |
| Intel Core i7           | 11        | 7.75%   |
| Intel Core i3           | 11        | 7.75%   |
| Intel Atom              | 10        | 7.04%   |
| Intel Pentium           | 7         | 4.93%   |
| Other                   | 6         | 4.23%   |
| Intel Pentium Dual-Core | 6         | 4.23%   |
| Intel Xeon              | 4         | 2.82%   |
| Intel Core 2            | 3         | 2.11%   |
| AMD Ryzen 5             | 3         | 2.11%   |
| AMD E2                  | 3         | 2.11%   |
| AMD A6                  | 3         | 2.11%   |
| Intel Pentium Dual      | 2         | 1.41%   |
| Intel Genuine           | 2         | 1.41%   |
| AMD Turion 64 X2 Mobile | 2         | 1.41%   |
| AMD E                   | 2         | 1.41%   |
| AMD Athlon II X2        | 2         | 1.41%   |
| AMD A8                  | 2         | 1.41%   |
| Intel Pentium D         | 1         | 0.7%    |
| Intel Core m7           | 1         | 0.7%    |
| Intel Core 2 Quad       | 1         | 0.7%    |
| Intel Core 2 Extreme    | 1         | 0.7%    |
| Intel Celeron M         | 1         | 0.7%    |
| AMD Turion Dual-Core    | 1         | 0.7%    |
| AMD Sempron             | 1         | 0.7%    |
| AMD Ryzen 9             | 1         | 0.7%    |
| AMD Ryzen 3             | 1         | 0.7%    |
| AMD Quad-Core           | 1         | 0.7%    |
| AMD Phenom II X2        | 1         | 0.7%    |
| AMD GX                  | 1         | 0.7%    |
| AMD FX                  | 1         | 0.7%    |
| AMD Athlon II Neo       | 1         | 0.7%    |
| AMD A12                 | 1         | 0.7%    |
| AMD A10                 | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 79        | 55.63%  |
| 4      | 45        | 31.69%  |
| 6      | 7         | 4.93%   |
| 1      | 7         | 4.93%   |
| 14     | 1         | 0.7%    |
| 12     | 1         | 0.7%    |
| 10     | 1         | 0.7%    |
| 8      | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 140       | 98.59%  |
| 2      | 2         | 1.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 88        | 61.97%  |
| 2      | 54        | 38.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 140       | 98.59%  |
| 32-bit         | 2         | 1.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 12.59%  |
| 0x1067a    | 15        | 10.49%  |
| 0x206a7    | 13        | 9.09%   |
| 0x30678    | 8         | 5.59%   |
| 0x406c4    | 5         | 3.5%    |
| 0x6fd      | 4         | 2.8%    |
| 0x40651    | 4         | 2.8%    |
| 0x20655    | 4         | 2.8%    |
| 0x10676    | 4         | 2.8%    |
| 0x010000c8 | 4         | 2.8%    |
| 0x6fb      | 3         | 2.1%    |
| 0x6f6      | 3         | 2.1%    |
| 0x506c9    | 3         | 2.1%    |
| 0x306c3    | 3         | 2.1%    |
| 0x306a9    | 3         | 2.1%    |
| 0x06006705 | 3         | 2.1%    |
| 0x806ec    | 2         | 1.4%    |
| 0x806ea    | 2         | 1.4%    |
| 0x806e9    | 2         | 1.4%    |
| 0x806c1    | 2         | 1.4%    |
| 0x706a1    | 2         | 1.4%    |
| 0x506e3    | 2         | 1.4%    |
| 0x406c3    | 2         | 1.4%    |
| 0x206c2    | 2         | 1.4%    |
| 0x106ca    | 2         | 1.4%    |
| 0x07030105 | 2         | 1.4%    |
| 0x05000119 | 2         | 1.4%    |
| 0xf64      | 1         | 0.7%    |
| 0xa0653    | 1         | 0.7%    |
| 0x906eb    | 1         | 0.7%    |
| 0x906ea    | 1         | 0.7%    |
| 0x906e9    | 1         | 0.7%    |
| 0x906a4    | 1         | 0.7%    |
| 0x906a3    | 1         | 0.7%    |
| 0x806eb    | 1         | 0.7%    |
| 0x6fa      | 1         | 0.7%    |
| 0x6d8      | 1         | 0.7%    |
| 0x406e3    | 1         | 0.7%    |
| 0x30661    | 1         | 0.7%    |
| 0x0a50000d | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 20        | 14.08%  |
| Silvermont       | 17        | 11.97%  |
| SandyBridge      | 13        | 9.15%   |
| Core             | 13        | 9.15%   |
| KabyLake         | 11        | 7.75%   |
| Haswell          | 7         | 4.93%   |
| Westmere         | 6         | 4.23%   |
| K10              | 5         | 3.52%   |
| IvyBridge        | 5         | 3.52%   |
| Excavator        | 5         | 3.52%   |
| Skylake          | 3         | 2.11%   |
| Puma             | 3         | 2.11%   |
| Goldmont         | 3         | 2.11%   |
| Bonnell          | 3         | 2.11%   |
| Bobcat           | 3         | 2.11%   |
| Zen 3            | 2         | 1.41%   |
| TigerLake        | 2         | 1.41%   |
| Piledriver       | 2         | 1.41%   |
| P6               | 2         | 1.41%   |
| K8 Hammer        | 2         | 1.41%   |
| K10 Llano        | 2         | 1.41%   |
| Goldmont plus    | 2         | 1.41%   |
| Alderlake Hybrid | 2         | 1.41%   |
| Zen+             | 1         | 0.7%    |
| Zen 2            | 1         | 0.7%    |
| Zen              | 1         | 0.7%    |
| NetBurst         | 1         | 0.7%    |
| Nehalem          | 1         | 0.7%    |
| K8 & K10 hybrid  | 1         | 0.7%    |
| Jaguar           | 1         | 0.7%    |
| CometLake        | 1         | 0.7%    |
| Unknown          | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 85        | 55.56%  |
| Nvidia | 34        | 22.22%  |
| AMD    | 34        | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 5.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 4.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 3.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 3.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 3.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 3.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 2.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.47%   |
| Intel HD Graphics 500                                                                    | 3         | 1.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 1.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.85%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.85%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 1.85%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.23%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.23%   |
| Intel HD Graphics 620                                                                    | 2         | 1.23%   |
| Intel HD Graphics 530                                                                    | 2         | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.23%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.23%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.23%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.23%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.62%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.62%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.62%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 0.62%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.62%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.62%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.62%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.62%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.62%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.62%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 0.62%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 74        | 52.11%  |
| 1 x AMD        | 30        | 21.13%  |
| 1 x Nvidia     | 24        | 16.9%   |
| Intel + Nvidia | 10        | 7.04%   |
| 2 x AMD        | 3         | 2.11%   |
| Intel + AMD    | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 123       | 86.01%  |
| Proprietary | 17        | 11.89%  |
| Unknown     | 3         | 2.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 85        | 59.86%  |
| 0.01-0.5   | 31        | 21.83%  |
| 0.51-1.0   | 10        | 7.04%   |
| 1.01-2.0   | 8         | 5.63%   |
| 3.01-4.0   | 5         | 3.52%   |
| 5.01-6.0   | 3         | 2.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 21        | 14.69%  |
| AU Optronics            | 14        | 9.79%   |
| LG Display              | 11        | 7.69%   |
| Chimei Innolux          | 11        | 7.69%   |
| Hewlett-Packard         | 10        | 6.99%   |
| Goldstar                | 9         | 6.29%   |
| BOE                     | 9         | 6.29%   |
| Chi Mei Optoelectronics | 8         | 5.59%   |
| Acer                    | 6         | 4.2%    |
| Apple                   | 5         | 3.5%    |
| Sony                    | 4         | 2.8%    |
| Ancor Communications    | 4         | 2.8%    |
| NEC Computers           | 3         | 2.1%    |
| ViewSonic               | 2         | 1.4%    |
| PANDA                   | 2         | 1.4%    |
| LG Philips              | 2         | 1.4%    |
| InfoVision              | 2         | 1.4%    |
| HannStar                | 2         | 1.4%    |
| CPT                     | 2         | 1.4%    |
| Unknown                 | 2         | 1.4%    |
| Toshiba                 | 1         | 0.7%    |
| TCL                     | 1         | 0.7%    |
| Seiko/Epson             | 1         | 0.7%    |
| SANYO                   | 1         | 0.7%    |
| Philips                 | 1         | 0.7%    |
| OEM                     | 1         | 0.7%    |
| NCS                     | 1         | 0.7%    |
| MSI                     | 1         | 0.7%    |
| Lenovo                  | 1         | 0.7%    |
| Hitachi                 | 1         | 0.7%    |
| eMachines               | 1         | 0.7%    |
| BenQ                    | 1         | 0.7%    |
| Belinea                 | 1         | 0.7%    |
| AOC                     | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 2         | 1.34%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch              | 2         | 1.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.34%   |
| Unknown                                                               | 2         | 1.34%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1         | 0.67%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1         | 0.67%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1         | 0.67%   |
| Toshiba L705A LCD705A 1280x1024 340x270mm 17.1-inch                   | 1         | 0.67%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.67%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.67%   |
| Sony TV SNYDC01 1360x768                                              | 1         | 0.67%   |
| Sony TV SNY3002 1920x1080 1018x573mm 46.0-inch                        | 1         | 0.67%   |
| Sony TV *00 SNY8004 3840x2160 1085x610mm 49.0-inch                    | 1         | 0.67%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.67%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.67%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch  | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 0.67%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1         | 0.67%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.67%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 440x250mm 19.9-inch      | 1         | 0.67%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1         | 0.67%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1         | 0.67%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                    | 1         | 0.67%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 42        | 29.37%  |
| 1920x1080 (FHD)    | 40        | 27.97%  |
| 1920x1200 (WUXGA)  | 11        | 7.69%   |
| 1280x800 (WXGA)    | 9         | 6.29%   |
| 3840x2160 (4K)     | 8         | 5.59%   |
| 1280x1024 (SXGA)   | 6         | 4.2%    |
| 1680x1050 (WSXGA+) | 5         | 3.5%    |
| 1600x900 (HD+)     | 4         | 2.8%    |
| 1440x900 (WXGA+)   | 4         | 2.8%    |
| 1360x768           | 3         | 2.1%    |
| 2560x1440 (QHD)    | 2         | 1.4%    |
| 1024x600           | 2         | 1.4%    |
| Unknown            | 2         | 1.4%    |
| 5280x1080          | 1         | 0.7%    |
| 3840x2400          | 1         | 0.7%    |
| 1920x540           | 1         | 0.7%    |
| 1280x720 (HD)      | 1         | 0.7%    |
| 1024x768 (XGA)     | 1         | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 29        | 20.14%  |
| 17      | 13        | 9.03%   |
| 14      | 12        | 8.33%   |
| 13      | 11        | 7.64%   |
| 24      | 9         | 6.25%   |
| 21      | 8         | 5.56%   |
| Unknown | 8         | 5.56%   |
| 23      | 7         | 4.86%   |
| 11      | 6         | 4.17%   |
| 27      | 5         | 3.47%   |
| 19      | 5         | 3.47%   |
| 18      | 5         | 3.47%   |
| 12      | 5         | 3.47%   |
| 20      | 4         | 2.78%   |
| 16      | 3         | 2.08%   |
| 10      | 3         | 2.08%   |
| 72      | 2         | 1.39%   |
| 46      | 2         | 1.39%   |
| 22      | 2         | 1.39%   |
| 65      | 1         | 0.69%   |
| 32      | 1         | 0.69%   |
| 31      | 1         | 0.69%   |
| 28      | 1         | 0.69%   |
| 26      | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 37.32%  |
| 401-500     | 22        | 15.49%  |
| 501-600     | 20        | 14.08%  |
| 201-300     | 18        | 12.68%  |
| 351-400     | 12        | 8.45%   |
| Unknown     | 8         | 5.63%   |
| 601-700     | 3         | 2.11%   |
| 1001-1500   | 3         | 2.11%   |
| 1501-2000   | 2         | 1.41%   |
| 701-800     | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 93        | 67.88%  |
| 16/10   | 28        | 20.44%  |
| 5/4     | 6         | 4.38%   |
| Unknown | 6         | 4.38%   |
| 4/3     | 2         | 1.46%   |
| 6/5     | 1         | 0.73%   |
| 3/2     | 1         | 0.73%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 20.14%  |
| 81-90          | 19        | 13.19%  |
| 201-250        | 19        | 13.19%  |
| 151-200        | 12        | 8.33%   |
| 141-150        | 8         | 5.56%   |
| Unknown        | 8         | 5.56%   |
| 51-60          | 6         | 4.17%   |
| 301-350        | 6         | 4.17%   |
| 121-130        | 6         | 4.17%   |
| 71-80          | 5         | 3.47%   |
| 251-300        | 5         | 3.47%   |
| 131-140        | 5         | 3.47%   |
| 61-70          | 4         | 2.78%   |
| More than 1000 | 3         | 2.08%   |
| 351-500        | 3         | 2.08%   |
| 41-50          | 3         | 2.08%   |
| 501-1000       | 2         | 1.39%   |
| 111-120        | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 47        | 33.57%  |
| 101-120       | 42        | 30%     |
| 121-160       | 32        | 22.86%  |
| Unknown       | 8         | 5.71%   |
| 161-240       | 5         | 3.57%   |
| 1-50          | 4         | 2.86%   |
| More than 240 | 2         | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 126       | 88.11%  |
| 2     | 15        | 10.49%  |
| 3     | 1         | 0.7%    |
| 0     | 1         | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 76        | 35.02%  |
| Intel                                 | 51        | 23.5%   |
| Qualcomm Atheros                      | 29        | 13.36%  |
| Broadcom                              | 19        | 8.76%   |
| Ralink Technology                     | 5         | 2.3%    |
| Ralink                                | 5         | 2.3%    |
| Broadcom Limited                      | 5         | 2.3%    |
| TP-Link                               | 4         | 1.84%   |
| Nvidia                                | 4         | 1.84%   |
| Sierra Wireless                       | 2         | 0.92%   |
| Qualcomm Atheros Communications       | 2         | 0.92%   |
| Marvell Technology Group              | 2         | 0.92%   |
| ASUSTek Computer                      | 2         | 0.92%   |
| ASIX Electronics                      | 2         | 0.92%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.46%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.46%   |
| Samsung Electronics                   | 1         | 0.46%   |
| Microsoft                             | 1         | 0.46%   |
| MediaTek                              | 1         | 0.46%   |
| Linksys                               | 1         | 0.46%   |
| D-Link                                | 1         | 0.46%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.46%   |
| 3Com                                  | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 49        | 19.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 17        | 6.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 7         | 2.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 6         | 2.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 2.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 2.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 1.95%   |
| Intel Wireless 3165                                                                           | 5         | 1.95%   |
| Ralink MT7601U Wireless Adapter                                                               | 4         | 1.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4         | 1.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 1.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 3         | 1.17%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 2         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2         | 0.78%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 0.78%   |
| Realtek 802.11ac NIC                                                                          | 2         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 0.78%   |
| Nvidia MCP77 Ethernet                                                                         | 2         | 0.78%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 0.78%   |
| Intel Wireless 7260                                                                           | 2         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 0.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                                                      | 2         | 0.78%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2         | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                             | 2         | 0.78%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                        | 2         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 0.78%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                                                 | 2         | 0.78%   |
| ZTE WCDMA MSM Android                                                                         | 1         | 0.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1         | 0.39%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 0.39%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY                    | 1         | 0.39%   |
| Sierra Wireless EM7455                                                                        | 1         | 0.39%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1         | 0.39%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 35        | 28.46%  |
| Realtek Semiconductor                 | 26        | 21.14%  |
| Qualcomm Atheros                      | 26        | 21.14%  |
| Broadcom                              | 8         | 6.5%    |
| Ralink Technology                     | 5         | 4.07%   |
| Ralink                                | 5         | 4.07%   |
| TP-Link                               | 4         | 3.25%   |
| Broadcom Limited                      | 3         | 2.44%   |
| Sierra Wireless                       | 2         | 1.63%   |
| Qualcomm Atheros Communications       | 2         | 1.63%   |
| ASUSTek Computer                      | 2         | 1.63%   |
| Microsoft                             | 1         | 0.81%   |
| MediaTek                              | 1         | 0.81%   |
| Linksys                               | 1         | 0.81%   |
| D-Link                                | 1         | 0.81%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 6         | 4.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 4.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 4.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 4.03%   |
| Intel Wireless 3165                                                                           | 5         | 4.03%   |
| Ralink MT7601U Wireless Adapter                                                               | 4         | 3.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4         | 3.23%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 3.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 2.42%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 2         | 1.61%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2         | 1.61%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 1.61%   |
| Realtek 802.11ac NIC                                                                          | 2         | 1.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 1.61%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.61%   |
| Intel Wireless 7260                                                                           | 2         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 1.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.61%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 1.61%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1         | 0.81%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 0.81%   |
| Sierra Wireless EM7455                                                                        | 1         | 0.81%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.81%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 0.81%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.81%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 0.81%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.81%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1         | 0.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.81%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.81%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.81%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 70        | 54.26%  |
| Intel                             | 25        | 19.38%  |
| Broadcom                          | 12        | 9.3%    |
| Qualcomm Atheros                  | 8         | 6.2%    |
| Nvidia                            | 4         | 3.1%    |
| Marvell Technology Group          | 2         | 1.55%   |
| Broadcom Limited                  | 2         | 1.55%   |
| ASIX Electronics                  | 2         | 1.55%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.78%   |
| Sundance Technology Inc / IC Plus | 1         | 0.78%   |
| Samsung Electronics               | 1         | 0.78%   |
| 3Com                              | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 49        | 37.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 17        | 12.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 5.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 3         | 2.29%   |
| Nvidia MCP77 Ethernet                                                         | 2         | 1.53%   |
| Intel 82567LM Gigabit Network Connection                                      | 2         | 1.53%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 1.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 1.53%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 1.53%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 1.53%   |
| ZTE WCDMA MSM Android                                                         | 1         | 0.76%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.76%   |
| Realtek USB 10/100 LAN                                                        | 1         | 0.76%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.76%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.76%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.76%   |
| Nvidia MCP51 Ethernet Controller                                              | 1         | 0.76%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.76%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.76%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 0.76%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.76%   |
| Intel Ethernet Connection (17) I219-V                                         | 1         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 0.76%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.76%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.76%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1         | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.76%   |
| Intel 82567LF-3 Gigabit Network Connection                                    | 1         | 0.76%   |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 123       | 51.46%  |
| WiFi     | 115       | 48.12%  |
| Unknown  | 1         | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 92        | 61.74%  |
| Ethernet | 57        | 38.26%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 84        | 59.15%  |
| 1     | 50        | 35.21%  |
| 0     | 4         | 2.82%   |
| 3     | 3         | 2.11%   |
| 4     | 1         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 111       | 77.62%  |
| Yes  | 32        | 22.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 30.56%  |
| Realtek Semiconductor           | 12        | 16.67%  |
| Lite-On Technology              | 5         | 6.94%   |
| Hewlett-Packard                 | 5         | 6.94%   |
| Cambridge Silicon Radio         | 5         | 6.94%   |
| IMC Networks                    | 4         | 5.56%   |
| Broadcom                        | 4         | 5.56%   |
| Apple                           | 4         | 5.56%   |
| Qualcomm Atheros Communications | 3         | 4.17%   |
| Dell                            | 2         | 2.78%   |
| Chicony Electronics             | 2         | 2.78%   |
| Toshiba                         | 1         | 1.39%   |
| Ralink                          | 1         | 1.39%   |
| Foxconn / Hon Hai               | 1         | 1.39%   |
| ASUSTek Computer                | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 15.28%  |
| Realtek Bluetooth Radio                             | 7         | 9.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 6.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.17%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 4.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.78%   |
| Lite-On Bluetooth Device                            | 2         | 2.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.78%   |
| Intel AX201 Bluetooth                               | 2         | 2.78%   |
| IMC Networks Bluetooth Device                       | 2         | 2.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.78%   |
| Dell Wireless 355 Bluetooth                         | 2         | 2.78%   |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 2.78%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 2.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 2.78%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.39%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.39%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.39%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.39%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.39%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.39%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.39%   |
| Intel Bluetooth Device                              | 1         | 1.39%   |
| Intel AX200 Bluetooth                               | 1         | 1.39%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.39%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.39%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.39%   |
| Broadcom HP Portable Valentine                      | 1         | 1.39%   |
| Broadcom HP Bluethunder                             | 1         | 1.39%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.39%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.39%   |
| Apple Bluetooth HCI                                 | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 104       | 60.82%  |
| AMD                   | 34        | 19.88%  |
| Nvidia                | 21        | 12.28%  |
| C-Media Electronics   | 3         | 1.75%   |
| Logitech              | 2         | 1.17%   |
| JMTek                 | 2         | 1.17%   |
| Texas Instruments     | 1         | 0.58%   |
| Realtek Semiconductor | 1         | 0.58%   |
| Ensoniq               | 1         | 0.58%   |
| Creative Labs         | 1         | 0.58%   |
| Blue Microphones      | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 7%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 6%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 4%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 4%      |
| AMD FCH Azalia Controller                                                                         | 8         | 4%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 3.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 3%      |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 3%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 2.5%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5         | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 2%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 2%      |
| Intel 8 Series HD Audio Controller                                                                | 4         | 2%      |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.5%    |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.5%    |
| AMD High Definition Audio Controller                                                              | 3         | 1.5%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.5%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 1%      |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1%      |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1%      |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 2         | 1%      |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1%      |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.5%    |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1         | 0.5%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 25        | 18.94%  |
| Samsung Electronics | 25        | 18.94%  |
| SK hynix            | 19        | 14.39%  |
| Kingston            | 16        | 12.12%  |
| Micron Technology   | 13        | 9.85%   |
| Unknown             | 5         | 3.79%   |
| Unknown (ABCD)      | 4         | 3.03%   |
| Nanya Technology    | 3         | 2.27%   |
| Elpida              | 3         | 2.27%   |
| A-DATA Technology   | 3         | 2.27%   |
| Ramaxel Technology  | 2         | 1.52%   |
| Corsair             | 2         | 1.52%   |
| Unknown (0x7F61)    | 1         | 0.76%   |
| Transcend           | 1         | 0.76%   |
| Qumo                | 1         | 0.76%   |
| Qimonda             | 1         | 0.76%   |
| GeIL                | 1         | 0.76%   |
| G.Skill             | 1         | 0.76%   |
| G Skil              | 1         | 0.76%   |
| Avant               | 1         | 0.76%   |
| 2C0C1121390963FE    | 1         | 0.76%   |
| 2C0C1121390963FD    | 1         | 0.76%   |
| 2C0C1121390963F9    | 1         | 0.76%   |
| 2C0C1121390963F8    | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 3.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 2.16%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.44%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 1.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 1.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.72%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                          | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.72%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 0.72%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.72%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                       | 1         | 0.72%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1         | 0.72%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                            | 1         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                   | 1         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                    | 1         | 0.72%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR2                              | 1         | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                       | 1         | 0.72%   |
| Unknown (0x7F61) RAM Module 1GB FB-DIMM DDR2 667MT/s             | 1         | 0.72%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s               | 1         | 0.72%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.72%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.72%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 1         | 0.72%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 1         | 0.72%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 0.72%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 41        | 36.61%  |
| DDR4    | 23        | 20.54%  |
| DDR2    | 23        | 20.54%  |
| SDRAM   | 9         | 8.04%   |
| LPDDR4  | 6         | 5.36%   |
| Unknown | 6         | 5.36%   |
| DDR     | 3         | 2.68%   |
| DRAM    | 1         | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 61.47%  |
| DIMM         | 39        | 35.78%  |
| FB-DIMM      | 2         | 1.83%   |
| Row Of Chips | 1         | 0.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 41        | 33.61%  |
| 4096  | 37        | 30.33%  |
| 8192  | 19        | 15.57%  |
| 1024  | 17        | 13.93%  |
| 16384 | 6         | 4.92%   |
| 32768 | 1         | 0.82%   |
| 512   | 1         | 0.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 31        | 26.27%  |
| 667     | 12        | 10.17%  |
| 1333    | 10        | 8.47%   |
| 3200    | 9         | 7.63%   |
| 2667    | 9         | 7.63%   |
| Unknown | 8         | 6.78%   |
| 800     | 6         | 5.08%   |
| 2400    | 5         | 4.24%   |
| 3266    | 3         | 2.54%   |
| 975     | 3         | 2.54%   |
| 4199    | 2         | 1.69%   |
| 2133    | 2         | 1.69%   |
| 2048    | 2         | 1.69%   |
| 1334    | 2         | 1.69%   |
| 1066    | 2         | 1.69%   |
| 400     | 2         | 1.69%   |
| 49926   | 1         | 0.85%   |
| 19791   | 1         | 0.85%   |
| 3933    | 1         | 0.85%   |
| 3500    | 1         | 0.85%   |
| 2666    | 1         | 0.85%   |
| 1866    | 1         | 0.85%   |
| 1639    | 1         | 0.85%   |
| 1067    | 1         | 0.85%   |
| 1033    | 1         | 0.85%   |
| 133     | 1         | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Mustek Systems  | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 CU | 1         | 33.33%  |
| HP ScanJet 5200c                   | 1         | 33.33%  |
| Canon CanoScan LiDE 110            | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 26.25%  |
| Quanta                                 | 6         | 7.5%    |
| Cheng Uei Precision Industry (Foxlink) | 6         | 7.5%    |
| Apple                                  | 6         | 7.5%    |
| Syntek                                 | 5         | 6.25%   |
| Suyin                                  | 5         | 6.25%   |
| IMC Networks                           | 4         | 5%      |
| Alcor Micro                            | 4         | 5%      |
| Silicon Motion                         | 3         | 3.75%   |
| Z-Star Microelectronics                | 2         | 2.5%    |
| Sunplus Innovation Technology          | 2         | 2.5%    |
| Realtek Semiconductor                  | 2         | 2.5%    |
| Microdia                               | 2         | 2.5%    |
| Lite-On Technology                     | 2         | 2.5%    |
| Ricoh                                  | 1         | 1.25%   |
| Pixart Imaging                         | 1         | 1.25%   |
| OmniVision Technologies                | 1         | 1.25%   |
| Microsoft                              | 1         | 1.25%   |
| Logitech                               | 1         | 1.25%   |
| Jieli Technology                       | 1         | 1.25%   |
| Hopewin Electronic Material            | 1         | 1.25%   |
| Hewlett-Packard                        | 1         | 1.25%   |
| Generalplus Technology                 | 1         | 1.25%   |
| Aveo Technology                        | 1         | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                       | 5         | 6.25%   |
| Chicony Integrated Camera                           | 3         | 3.75%   |
| Syntek USB Video Device                             | 2         | 2.5%    |
| Syntek Lenovo EasyCamera                            | 2         | 2.5%    |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 2.5%    |
| Quanta HP TrueVision HD Camera                      | 2         | 2.5%    |
| Chicony HP High Definition 1MP Webcam               | 2         | 2.5%    |
| Chicony FJ Camera                                   | 2         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 2.5%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 2         | 2.5%    |
| Apple Built-in iSight                               | 2         | 2.5%    |
| Alcor Micro USB 2.0 Camera                          | 2         | 2.5%    |
| Z-Star Webcam                                       | 1         | 1.25%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 1.25%   |
| Syntek Integrated Camera                            | 1         | 1.25%   |
| Suyin USB 2.0 Camera                                | 1         | 1.25%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.25%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 1.25%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.25%   |
| Sunplus HD WebCam                                   | 1         | 1.25%   |
| Silicon Motion WebCam SC-10HDD13335N                | 1         | 1.25%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 1.25%   |
| Silicon Motion Web Camera                           | 1         | 1.25%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.25%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.25%   |
| Realtek USB Camera                                  | 1         | 1.25%   |
| Quanta VGA WebCam                                   | 1         | 1.25%   |
| Quanta HP Truevision HD                             | 1         | 1.25%   |
| Quanta HD Webcam                                    | 1         | 1.25%   |
| Quanta ACER HD User Facing                          | 1         | 1.25%   |
| Pixart Imaging USB_2.0_Webcam                       | 1         | 1.25%   |
| OmniVision OV2640 Webcam                            | 1         | 1.25%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1         | 1.25%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.25%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.25%   |
| Logitech HD Webcam C615                             | 1         | 1.25%   |
| Lite-On Integrated Camera                           | 1         | 1.25%   |
| Lite-On HP Webcam                                   | 1         | 1.25%   |
| Jieli USB PHY 2.0                                   | 1         | 1.25%   |
| IMC Networks USB2.0 UVC VGA WebCam                  | 1         | 1.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 4         | 40%     |
| Validity Sensors      | 2         | 20%     |
| Synaptics             | 2         | 20%     |
| Samsung Electronics   | 1         | 10%     |
| LighTuning Technology | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor             | 2         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader       | 1         | 10%     |
| Validity Sensors Synaptics WBDI                  | 1         | 10%     |
| Synaptics WBDI                                   | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 10%     |
| Samsung Fingerprint Device                       | 1         | 10%     |
| LighTuning EgisTec Touch Fingerprint Sensor      | 1         | 10%     |
| AuthenTec Fingerprint Sensor                     | 1         | 10%     |
| AuthenTec AES1600                                | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| O2 Micro Oz776 SmartCard Reader                | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 108       | 75.52%  |
| 1     | 29        | 20.28%  |
| 2     | 6         | 4.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 24.39%  |
| Graphics card            | 9         | 21.95%  |
| Net/wireless             | 6         | 14.63%  |
| Chipcard                 | 3         | 7.32%   |
| Storage                  | 2         | 4.88%   |
| Multimedia controller    | 2         | 4.88%   |
| Bluetooth                | 2         | 4.88%   |
| Unassigned class         | 1         | 2.44%   |
| Sound                    | 1         | 2.44%   |
| Network                  | 1         | 2.44%   |
| Net/ethernet             | 1         | 2.44%   |
| Dvb card                 | 1         | 2.44%   |
| Communication controller | 1         | 2.44%   |
| Camera                   | 1         | 2.44%   |

