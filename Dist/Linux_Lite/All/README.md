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

Total: 211

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E7240              | Notebook    | [87a0310cf0](https://linux-hardware.org/?probe=87a0310cf0) | Aug 02, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [41ad8c7fc0](https://linux-hardware.org/?probe=41ad8c7fc0) | Jul 26, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [a2f77869ad](https://linux-hardware.org/?probe=a2f77869ad) | Jul 14, 2023 |
| Medion        | Akoya E6418 MD99620         | Notebook    | [7416e91f77](https://linux-hardware.org/?probe=7416e91f77) | Jul 14, 2023 |
| Dell          | 0GN4PW A00                  | Desktop     | [8380b94e4f](https://linux-hardware.org/?probe=8380b94e4f) | Jul 06, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [8a66b6d6b6](https://linux-hardware.org/?probe=8a66b6d6b6) | Jul 03, 2023 |
| Lenovo        | IdeaPad 310S-14AST 80UL     | Notebook    | [f897f42089](https://linux-hardware.org/?probe=f897f42089) | Jul 03, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Linux Lite 5.8 | 25        | 16.56%  |
| Linux Lite 6.0 | 19        | 12.58%  |
| Linux Lite 5.4 | 18        | 11.92%  |
| Linux Lite 5.2 | 17        | 11.26%  |
| Linux Lite 5.0 | 17        | 11.26%  |
| Linux Lite 6.4 | 16        | 10.6%   |
| Linux Lite 5.6 | 15        | 9.93%   |
| Linux Lite 6.2 | 14        | 9.27%   |
| Linux Lite 3.8 | 5         | 3.31%   |
| Linux Lite 4.8 | 2         | 1.32%   |
| Linux Lite 4.6 | 1         | 0.66%   |
| Linux Lite 4.4 | 1         | 0.66%   |
| Linux Lite 4.2 | 1         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Lite | 149       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 6         | 3.8%    |
| 5.15.0-69-generic | 6         | 3.8%    |
| 5.4.0-91-generic  | 5         | 3.16%   |
| 5.4.0-70-generic  | 5         | 3.16%   |
| 5.15.0-76-generic | 5         | 3.16%   |
| 5.4.0-96-generic  | 4         | 2.53%   |
| 5.4.0-52-generic  | 4         | 2.53%   |
| 5.4.0-40-generic  | 4         | 2.53%   |
| 5.4.0-109-generic | 4         | 2.53%   |
| 5.4.0-104-generic | 4         | 2.53%   |
| 5.15.0-71-generic | 4         | 2.53%   |
| 5.15.0-33-generic | 4         | 2.53%   |
| 5.4.0-81-generic  | 3         | 1.9%    |
| 5.4.0-58-generic  | 3         | 1.9%    |
| 5.4.0-48-generic  | 3         | 1.9%    |
| 5.4.0-113-generic | 3         | 1.9%    |
| 5.4.0-107-generic | 3         | 1.9%    |
| 5.15.0-75-generic | 3         | 1.9%    |
| 5.15.0-58-generic | 3         | 1.9%    |
| 5.15.0-52-generic | 3         | 1.9%    |
| 5.15.0-47-generic | 3         | 1.9%    |
| 5.15.0-46-generic | 3         | 1.9%    |
| 5.4.0-90-generic  | 2         | 1.27%   |
| 5.4.0-88-generic  | 2         | 1.27%   |
| 5.4.0-80-generic  | 2         | 1.27%   |
| 5.4.0-74-generic  | 2         | 1.27%   |
| 5.4.0-54-generic  | 2         | 1.27%   |
| 5.4.0-33-generic  | 2         | 1.27%   |
| 5.4.0-110-generic | 2         | 1.27%   |
| 5.4.0-105-generic | 2         | 1.27%   |
| 5.15.0-73-generic | 2         | 1.27%   |
| 5.15.0-60-generic | 2         | 1.27%   |
| 5.15.0-56-generic | 2         | 1.27%   |
| 5.15.0-48-generic | 2         | 1.27%   |
| 4.4.0-112-generic | 2         | 1.27%   |
| 6.1.0-1.linuxlite | 1         | 0.63%   |
| 6.0.0-1.linuxlite | 1         | 0.63%   |
| 6.0.0             | 1         | 0.63%   |
| 5.9.0             | 1         | 0.63%   |
| 5.4.0-99-generic  | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 85        | 55.56%  |
| 5.15.0  | 48        | 31.37%  |
| 4.15.0  | 5         | 3.27%   |
| 4.4.0   | 4         | 2.61%   |
| 5.13.0  | 3         | 1.96%   |
| 6.0.0   | 2         | 1.31%   |
| 6.1.0   | 1         | 0.65%   |
| 5.9.0   | 1         | 0.65%   |
| 5.19.0  | 1         | 0.65%   |
| 5.16.9  | 1         | 0.65%   |
| 5.16.0  | 1         | 0.65%   |
| 5.10.0  | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 85        | 55.56%  |
| 5.15    | 48        | 31.37%  |
| 4.15    | 5         | 3.27%   |
| 4.4     | 4         | 2.61%   |
| 5.13    | 3         | 1.96%   |
| 6.0     | 2         | 1.31%   |
| 5.16    | 2         | 1.31%   |
| 6.1     | 1         | 0.65%   |
| 5.9     | 1         | 0.65%   |
| 5.19    | 1         | 0.65%   |
| 5.10    | 1         | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 145       | 97.32%  |
| i686   | 4         | 2.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 121       | 81.21%  |
| GNOME   | 25        | 16.78%  |
| Unknown | 2         | 1.34%   |
| Deepin  | 1         | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 147       | 98.66%  |
| Tty     | 1         | 0.67%   |
| Unknown | 1         | 0.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 97        | 64.24%  |
| TDM     | 28        | 18.54%  |
| Unknown | 24        | 15.89%  |
| GDM3    | 1         | 0.66%   |
| GDM     | 1         | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 73        | 48.99%  |
| de_DE | 11        | 7.38%   |
| pl_PL | 8         | 5.37%   |
| pt_BR | 7         | 4.7%    |
| fr_FR | 7         | 4.7%    |
| en_GB | 6         | 4.03%   |
| es_ES | 5         | 3.36%   |
| es_MX | 4         | 2.68%   |
| ru_UA | 3         | 2.01%   |
| en_CA | 3         | 2.01%   |
| ru_RU | 2         | 1.34%   |
| it_IT | 2         | 1.34%   |
| zh_CN | 1         | 0.67%   |
| tr_TR | 1         | 0.67%   |
| pt_PT | 1         | 0.67%   |
| nl_NL | 1         | 0.67%   |
| hu_HU | 1         | 0.67%   |
| fr_CA | 1         | 0.67%   |
| es_CO | 1         | 0.67%   |
| es_CL | 1         | 0.67%   |
| es_AR | 1         | 0.67%   |
| en_SG | 1         | 0.67%   |
| en_PH | 1         | 0.67%   |
| en_NZ | 1         | 0.67%   |
| en_IN | 1         | 0.67%   |
| en_IE | 1         | 0.67%   |
| en_AU | 1         | 0.67%   |
| da_DK | 1         | 0.67%   |
| C     | 1         | 0.67%   |
| ar_SA | 1         | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 80        | 53.69%  |
| EFI  | 69        | 46.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 132       | 88.59%  |
| Overlay | 10        | 6.71%   |
| Tmpfs   | 3         | 2.01%   |
| Btrfs   | 2         | 1.34%   |
| Zfs     | 1         | 0.67%   |
| Ext3    | 1         | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 70        | 46.98%  |
| Unknown | 40        | 26.85%  |
| MBR     | 39        | 26.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 123       | 82%     |
| Yes       | 27        | 18%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 107       | 71.33%  |
| Yes       | 43        | 28.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 28        | 18.79%  |
| ASUSTek Computer    | 20        | 13.42%  |
| Lenovo              | 19        | 12.75%  |
| Dell                | 12        | 8.05%   |
| Acer                | 12        | 8.05%   |
| MSI                 | 6         | 4.03%   |
| Apple               | 6         | 4.03%   |
| Samsung Electronics | 4         | 2.68%   |
| Gigabyte Technology | 4         | 2.68%   |
| Pegatron            | 3         | 2.01%   |
| Fujitsu             | 3         | 2.01%   |
| ASRock              | 3         | 2.01%   |
| Toshiba             | 2         | 1.34%   |
| Minix               | 2         | 1.34%   |
| Inventec            | 2         | 1.34%   |
| Intel               | 2         | 1.34%   |
| Foxconn             | 2         | 1.34%   |
| UNOWHY              | 1         | 0.67%   |
| UMAX                | 1         | 0.67%   |
| TR                  | 1         | 0.67%   |
| Thomson             | 1         | 0.67%   |
| Sony                | 1         | 0.67%   |
| Packard Bell        | 1         | 0.67%   |
| Medion              | 1         | 0.67%   |
| Jetway              | 1         | 0.67%   |
| Insignia            | 1         | 0.67%   |
| Google              | 1         | 0.67%   |
| Gateway             | 1         | 0.67%   |
| Fujitsu Siemens     | 1         | 0.67%   |
| EVGA                | 1         | 0.67%   |
| Braview             | 1         | 0.67%   |
| Biostar             | 1         | 0.67%   |
| AWOW                | 1         | 0.67%   |
| AMI                 | 1         | 0.67%   |
| American Megatrends | 1         | 0.67%   |
| ABIT                | 1         | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7758                           | 2         | 1.34%   |
| UNOWHY Y13G010S4EI                    | 1         | 0.67%   |
| UMAX VisionBook 12Wi 64G              | 1         | 0.67%   |
| TR ST Pro-KN                          | 1         | 0.67%   |
| Toshiba Satellite T215D               | 1         | 0.67%   |
| Toshiba QOSMIO X70-B                  | 1         | 0.67%   |
| Thomson PT-NEO14A.2WH32               | 1         | 0.67%   |
| Sony VGC-JS54FB_W                     | 1         | 0.67%   |
| Samsung X420/X520                     | 1         | 0.67%   |
| Samsung NC110P/NC108P/NC111P          | 1         | 0.67%   |
| Samsung 905S3G/906S3G/915S3G/9305SG   | 1         | 0.67%   |
| Samsung 530XBB                        | 1         | 0.67%   |
| Pegatron H36FF                        | 1         | 0.67%   |
| Pegatron 520-1135la                   | 1         | 0.67%   |
| Pegatron 520-1030a                    | 1         | 0.67%   |
| Packard Bell ISTART D2314             | 1         | 0.67%   |
| MSI MS-N014                           | 1         | 0.67%   |
| MSI MS-7C95                           | 1         | 0.67%   |
| MSI MS-7996                           | 1         | 0.67%   |
| MSI FZ079AA-ABF a6625fr               | 1         | 0.67%   |
| Minix Z83-4                           | 1         | 0.67%   |
| Minix Z64                             | 1         | 0.67%   |
| Medion Akoya E6418 MD99620            | 1         | 0.67%   |
| Lenovo Yoga C740 81TC                 | 1         | 0.67%   |
| Lenovo ThinkStation P320 30BH000BFR   | 1         | 0.67%   |
| Lenovo ThinkPad X240 20AMS1J100       | 1         | 0.67%   |
| Lenovo ThinkPad T400 6475E13          | 1         | 0.67%   |
| Lenovo ThinkPad L480 20LS001AMC       | 1         | 0.67%   |
| Lenovo ThinkPad A475 20KMS08300       | 1         | 0.67%   |
| Lenovo ThinkCentre neo 50t Gen 3 11SE | 1         | 0.67%   |
| Lenovo ThinkCentre M91p 4524RS6       | 1         | 0.67%   |
| Lenovo ThinkCentre M91p 4518E2M       | 1         | 0.67%   |
| Lenovo ThinkCentre A55 9265BL7        | 1         | 0.67%   |
| Lenovo MIIX 300-10IBY 80NR            | 1         | 0.67%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1   | 1         | 0.67%   |
| Lenovo IdeaPad 330S-15AST 81F9        | 1         | 0.67%   |
| Lenovo IdeaPad 320-15ABR 80XS         | 1         | 0.67%   |
| Lenovo IdeaPad 310S-14AST 80UL        | 1         | 0.67%   |
| Lenovo IdeaPad 100-15IBY 80MJ         | 1         | 0.67%   |
| Lenovo IdeaPad 100-14IBY 80MH         | 1         | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HP Compaq               | 8         | 5.37%   |
| Acer Aspire             | 7         | 4.7%    |
| Lenovo IdeaPad          | 6         | 4.03%   |
| HP Laptop               | 5         | 3.36%   |
| Dell Inspiron           | 5         | 3.36%   |
| Lenovo ThinkPad         | 4         | 2.68%   |
| Lenovo ThinkCentre      | 4         | 2.68%   |
| HP EliteBook            | 3         | 2.01%   |
| Dell Latitude           | 3         | 2.01%   |
| MSI MS-7758             | 2         | 1.34%   |
| Inventec Dell           | 2         | 1.34%   |
| HP Pavilion             | 2         | 1.34%   |
| ASUS VivoBook           | 2         | 1.34%   |
| UNOWHY Y13G010S4EI      | 1         | 0.67%   |
| UMAX VisionBook         | 1         | 0.67%   |
| TR ST                   | 1         | 0.67%   |
| Toshiba Satellite       | 1         | 0.67%   |
| Toshiba QOSMIO          | 1         | 0.67%   |
| Thomson PT-NEO14A.2WH32 | 1         | 0.67%   |
| Sony VGC-JS54FB         | 1         | 0.67%   |
| Samsung X420            | 1         | 0.67%   |
| Samsung NC110P          | 1         | 0.67%   |
| Samsung 905S3G          | 1         | 0.67%   |
| Samsung 530XBB          | 1         | 0.67%   |
| Pegatron H36FF          | 1         | 0.67%   |
| Pegatron 520-1135la     | 1         | 0.67%   |
| Pegatron 520-1030a      | 1         | 0.67%   |
| Packard Bell ISTART     | 1         | 0.67%   |
| MSI MS-N014             | 1         | 0.67%   |
| MSI MS-7C95             | 1         | 0.67%   |
| MSI MS-7996             | 1         | 0.67%   |
| MSI FZ079AA-ABF         | 1         | 0.67%   |
| Minix Z83-4             | 1         | 0.67%   |
| Minix Z64               | 1         | 0.67%   |
| Medion Akoya            | 1         | 0.67%   |
| Lenovo Yoga             | 1         | 0.67%   |
| Lenovo ThinkStation     | 1         | 0.67%   |
| Lenovo MIIX             | 1         | 0.67%   |
| Lenovo H505S            | 1         | 0.67%   |
| Lenovo 3000             | 1         | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2008 | 16        | 10.74%  |
| 2011 | 15        | 10.07%  |
| 2010 | 15        | 10.07%  |
| 2012 | 13        | 8.72%   |
| 2018 | 12        | 8.05%   |
| 2007 | 11        | 7.38%   |
| 2015 | 10        | 6.71%   |
| 2014 | 10        | 6.71%   |
| 2020 | 9         | 6.04%   |
| 2016 | 7         | 4.7%    |
| 2017 | 6         | 4.03%   |
| 2013 | 6         | 4.03%   |
| 2019 | 5         | 3.36%   |
| 2009 | 4         | 2.68%   |
| 2022 | 3         | 2.01%   |
| 2021 | 3         | 2.01%   |
| 2006 | 2         | 1.34%   |
| 2023 | 1         | 0.67%   |
| 2004 | 1         | 0.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 85        | 57.05%  |
| Desktop     | 53        | 35.57%  |
| All in one  | 5         | 3.36%   |
| Mini pc     | 3         | 2.01%   |
| Tablet      | 2         | 1.34%   |
| Convertible | 1         | 0.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 141       | 94.63%  |
| Enabled  | 8         | 5.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 148       | 99.33%  |
| Yes  | 1         | 0.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 48        | 32.21%  |
| 4.01-8.0   | 29        | 19.46%  |
| 1.01-2.0   | 27        | 18.12%  |
| 16.01-24.0 | 17        | 11.41%  |
| 8.01-16.0  | 14        | 9.4%    |
| 32.01-64.0 | 6         | 4.03%   |
| 0.51-1.0   | 4         | 2.68%   |
| 2.01-3.0   | 3         | 2.01%   |
| 24.01-32.0 | 1         | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 72        | 47.37%  |
| 2.01-3.0  | 33        | 21.71%  |
| 0.51-1.0  | 22        | 14.47%  |
| 3.01-4.0  | 11        | 7.24%   |
| 4.01-8.0  | 9         | 5.92%   |
| 0.01-0.5  | 3         | 1.97%   |
| 8.01-16.0 | 2         | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 106       | 71.14%  |
| 2      | 32        | 21.48%  |
| 3      | 8         | 5.37%   |
| 0      | 2         | 1.34%   |
| 5      | 1         | 0.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 86        | 57.72%  |
| Yes       | 63        | 42.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 87.25%  |
| No        | 19        | 12.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 81.21%  |
| No        | 28        | 18.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 51.68%  |
| No        | 72        | 48.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 26        | 17.45%  |
| Germany      | 13        | 8.72%   |
| Brazil       | 12        | 8.05%   |
| France       | 9         | 6.04%   |
| Poland       | 8         | 5.37%   |
| UK           | 7         | 4.7%    |
| Romania      | 6         | 4.03%   |
| Canada       | 6         | 4.03%   |
| Ukraine      | 5         | 3.36%   |
| Mexico       | 5         | 3.36%   |
| Spain        | 4         | 2.68%   |
| Italy        | 4         | 2.68%   |
| Turkey       | 3         | 2.01%   |
| Russia       | 3         | 2.01%   |
| Peru         | 3         | 2.01%   |
| Australia    | 3         | 2.01%   |
| Philippines  | 2         | 1.34%   |
| Netherlands  | 2         | 1.34%   |
| Chile        | 2         | 1.34%   |
| Argentina    | 2         | 1.34%   |
| Venezuela    | 1         | 0.67%   |
| Thailand     | 1         | 0.67%   |
| Sweden       | 1         | 0.67%   |
| Slovakia     | 1         | 0.67%   |
| Singapore    | 1         | 0.67%   |
| Serbia       | 1         | 0.67%   |
| Saudi Arabia | 1         | 0.67%   |
| Qatar        | 1         | 0.67%   |
| Portugal     | 1         | 0.67%   |
| New Zealand  | 1         | 0.67%   |
| Myanmar      | 1         | 0.67%   |
| Malaysia     | 1         | 0.67%   |
| Japan        | 1         | 0.67%   |
| Ireland      | 1         | 0.67%   |
| Iran         | 1         | 0.67%   |
| Indonesia    | 1         | 0.67%   |
| India        | 1         | 0.67%   |
| Hungary      | 1         | 0.67%   |
| Guadeloupe   | 1         | 0.67%   |
| Greenland    | 1         | 0.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Pabianice              | 3         | 1.97%   |
| Würzburg              | 2         | 1.32%   |
| Warsaw                 | 2         | 1.32%   |
| Sydney                 | 2         | 1.32%   |
| Sao Paulo              | 2         | 1.32%   |
| Paris                  | 2         | 1.32%   |
| Ottawa                 | 2         | 1.32%   |
| Odessa                 | 2         | 1.32%   |
| Mexico City            | 2         | 1.32%   |
| Lublin                 | 2         | 1.32%   |
| Lima                   | 2         | 1.32%   |
| Kyiv                   | 2         | 1.32%   |
| Frankfurt am Main      | 2         | 1.32%   |
| Żywiec                | 1         | 0.66%   |
| Yangon                 | 1         | 0.66%   |
| Wiesbaden              | 1         | 0.66%   |
| Wellington             | 1         | 0.66%   |
| Waterbury              | 1         | 0.66%   |
| Washington             | 1         | 0.66%   |
| Wahroonga              | 1         | 0.66%   |
| Voluntari              | 1         | 0.66%   |
| Vinnytsia              | 1         | 0.66%   |
| Villingen-Schwenningen | 1         | 0.66%   |
| Varennes-les-Narcy     | 1         | 0.66%   |
| Vancouver              | 1         | 0.66%   |
| Valencia               | 1         | 0.66%   |
| Tucape                 | 1         | 0.66%   |
| Trujillo               | 1         | 0.66%   |
| Toronto                | 1         | 0.66%   |
| Thetford-Mines         | 1         | 0.66%   |
| Teresina               | 1         | 0.66%   |
| Tekirdağ              | 1         | 0.66%   |
| Tarragona              | 1         | 0.66%   |
| Tamm                   | 1         | 0.66%   |
| Svidník               | 1         | 0.66%   |
| Surabaya               | 1         | 0.66%   |
| Subotica               | 1         | 0.66%   |
| Studenka               | 1         | 0.66%   |
| St. Petersburg         | 1         | 0.66%   |
| Singapore              | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 41     | 19.57%  |
| WDC                 | 29        | 38     | 15.76%  |
| Samsung Electronics | 22        | 23     | 11.96%  |
| Toshiba             | 14        | 15     | 7.61%   |
| Unknown             | 12        | 16     | 6.52%   |
| Kingston            | 9         | 11     | 4.89%   |
| SanDisk             | 7         | 7      | 3.8%    |
| SK hynix            | 5         | 6      | 2.72%   |
| Hitachi             | 5         | 5      | 2.72%   |
| HGST                | 5         | 5      | 2.72%   |
| Crucial             | 5         | 5      | 2.72%   |
| Micron Technology   | 4         | 5      | 2.17%   |
| Goodram             | 3         | 3      | 1.63%   |
| Apple               | 3         | 3      | 1.63%   |
| A-DATA Technology   | 3         | 3      | 1.63%   |
| Phison              | 2         | 2      | 1.09%   |
| China               | 2         | 2      | 1.09%   |
| PNY                 | 1         | 1      | 0.54%   |
| OCZ                 | 1         | 1      | 0.54%   |
| Maxtor              | 1         | 1      | 0.54%   |
| Mass                | 1         | 1      | 0.54%   |
| LITEON              | 1         | 1      | 0.54%   |
| Intenso             | 1         | 1      | 0.54%   |
| Intel               | 1         | 1      | 0.54%   |
| HS-SSD-E100         | 1         | 1      | 0.54%   |
| HPE                 | 1         | 1      | 0.54%   |
| Hewlett-Packard     | 1         | 1      | 0.54%   |
| Gigabyte Technology | 1         | 1      | 0.54%   |
| Fujitsu             | 1         | 1      | 0.54%   |
| Fanxiang            | 1         | 2      | 0.54%   |
| Dogfish             | 1         | 1      | 0.54%   |
| ASUS-PHISON         | 1         | 2      | 0.54%   |
| ASMT                | 1         | 1      | 0.54%   |
| Apacer              | 1         | 1      | 0.54%   |
| Unknown             | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 4         | 2.04%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.53%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 1.53%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.53%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 1.02%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 1.02%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 1.02%   |
| Unknown DA4064  64GB                 | 2         | 1.02%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.02%   |
| Seagate ST9320325AS 320GB            | 2         | 1.02%   |
| Seagate ST3500418AS 500GB            | 2         | 1.02%   |
| SanDisk SDSSDA240G 240GB             | 2         | 1.02%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.02%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD  | 2         | 1.02%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.02%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.51%   |
| WDC WDS250G2B0A 250GB SSD            | 1         | 0.51%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.51%   |
| WDC WD800JD-60LSA0 80GB              | 1         | 0.51%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.51%   |
| WDC WD5000LPCX-75VHAT0 500GB         | 1         | 0.51%   |
| WDC WD5000AAKX-003CA0 500GB          | 1         | 0.51%   |
| WDC WD5000AAKS-60WWPA0 500GB         | 1         | 0.51%   |
| WDC WD5000AADS-56S9B0 500GB          | 1         | 0.51%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 0.51%   |
| WDC WD5000AACS-00G8B1 500GB          | 1         | 0.51%   |
| WDC WD2500BEVS-00UST0 250GB          | 1         | 0.51%   |
| WDC WD2500BEVE-00A0HT0 250GB         | 1         | 0.51%   |
| WDC WD20PURX-64PFUY0 2TB             | 1         | 0.51%   |
| WDC WD2005FBYZ-01YCBB2 2TB           | 1         | 0.51%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.51%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.51%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1         | 0.51%   |
| WDC WD10EZEX-07WN4A0 1TB             | 1         | 0.51%   |
| WDC WD10EADS-00L5B1 1TB              | 1         | 0.51%   |
| WDC WD1003FBYX-01Y7B1 1TB            | 1         | 0.51%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB   | 1         | 0.51%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 41     | 40.91%  |
| WDC                 | 22        | 27     | 25%     |
| Toshiba             | 13        | 14     | 14.77%  |
| Hitachi             | 5         | 5      | 5.68%   |
| HGST                | 5         | 5      | 5.68%   |
| Samsung Electronics | 3         | 4      | 3.41%   |
| Maxtor              | 1         | 1      | 1.14%   |
| HPE                 | 1         | 1      | 1.14%   |
| Fujitsu             | 1         | 1      | 1.14%   |
| Apple               | 1         | 1      | 1.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 12     | 19.35%  |
| Kingston            | 7         | 9      | 11.29%  |
| SanDisk             | 6         | 6      | 9.68%   |
| WDC                 | 5         | 6      | 8.06%   |
| Crucial             | 5         | 5      | 8.06%   |
| Micron Technology   | 3         | 4      | 4.84%   |
| Goodram             | 3         | 3      | 4.84%   |
| A-DATA Technology   | 3         | 3      | 4.84%   |
| China               | 2         | 2      | 3.23%   |
| Apple               | 2         | 2      | 3.23%   |
| Toshiba             | 1         | 1      | 1.61%   |
| SK hynix            | 1         | 2      | 1.61%   |
| PNY                 | 1         | 1      | 1.61%   |
| Phison              | 1         | 1      | 1.61%   |
| OCZ                 | 1         | 1      | 1.61%   |
| LITEON              | 1         | 1      | 1.61%   |
| Intel               | 1         | 1      | 1.61%   |
| Hewlett-Packard     | 1         | 1      | 1.61%   |
| Gigabyte Technology | 1         | 1      | 1.61%   |
| Fanxiang            | 1         | 2      | 1.61%   |
| Dogfish             | 1         | 1      | 1.61%   |
| ASUS-PHISON         | 1         | 2      | 1.61%   |
| ASMT                | 1         | 1      | 1.61%   |
| Apacer              | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 81        | 100    | 46.29%  |
| SSD     | 60        | 69     | 34.29%  |
| NVMe    | 16        | 19     | 9.14%   |
| MMC     | 15        | 19     | 8.57%   |
| Unknown | 3         | 3      | 1.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 123       | 166    | 76.88%  |
| NVMe | 16        | 19     | 10%     |
| MMC  | 15        | 19     | 9.38%   |
| SAS  | 6         | 6      | 3.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 100       | 128    | 71.94%  |
| 0.51-1.0   | 34        | 35     | 24.46%  |
| 1.01-2.0   | 4         | 5      | 2.88%   |
| 4.01-10.0  | 1         | 1      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 54        | 35.76%  |
| 251-500        | 29        | 19.21%  |
| 51-100         | 23        | 15.23%  |
| 501-1000       | 14        | 9.27%   |
| 21-50          | 11        | 7.28%   |
| 1-20           | 10        | 6.62%   |
| More than 3000 | 5         | 3.31%   |
| 1001-2000      | 4         | 2.65%   |
| 2001-3000      | 1         | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 69        | 45.39%  |
| 21-50     | 35        | 23.03%  |
| 51-100    | 21        | 13.82%  |
| 101-250   | 16        | 10.53%  |
| 501-1000  | 4         | 2.63%   |
| 251-500   | 3         | 1.97%   |
| 2001-3000 | 2         | 1.32%   |
| 1001-2000 | 2         | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 3.45%   |
| WDC WD800JD-60LSA0 80GB                        | 1         | 1      | 3.45%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 3.45%   |
| WDC WD5000AAKS-60WWPA0 500GB                   | 1         | 1      | 3.45%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 3.45%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 3.45%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 3.45%   |
| Toshiba MK3265GSX 320GB                        | 1         | 1      | 3.45%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 3.45%   |
| Seagate ST980811AS 80GB                        | 1         | 1      | 3.45%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 3.45%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 3.45%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 3.45%   |
| Seagate ST9320320AS 320GB                      | 1         | 1      | 3.45%   |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 3.45%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 3.45%   |
| Seagate ST3750528AS 752GB                      | 1         | 1      | 3.45%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 3.45%   |
| SanDisk SSD PLUS 120GB                         | 1         | 1      | 3.45%   |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 3.45%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 3.45%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 3.45%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 3.45%   |
| Hitachi HDS721616PLA380 160GB                  | 1         | 1      | 3.45%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 3.45%   |
| Apple SSD SM128C 121GB                         | 1         | 1      | 3.45%   |
| Apacer 16GB SATA Flash Drive SSD               | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 37.93%  |
| WDC                 | 6         | 6      | 20.69%  |
| Toshiba             | 3         | 3      | 10.34%  |
| Hitachi             | 3         | 3      | 10.34%  |
| SanDisk             | 1         | 1      | 3.45%   |
| Samsung Electronics | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |
| Apacer              | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 45.83%  |
| WDC                 | 5         | 5      | 20.83%  |
| Toshiba             | 3         | 3      | 12.5%   |
| Hitachi             | 3         | 3      | 12.5%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| HGST                | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 24     | 81.48%  |
| SSD  | 5         | 5      | 18.52%  |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 69        | 89     | 44.52%  |
| Detected | 60        | 92     | 38.71%  |
| Malfunc  | 26        | 29     | 16.77%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 104       | 65%     |
| AMD                         | 27        | 16.88%  |
| Samsung Electronics         | 7         | 4.38%   |
| Nvidia                      | 6         | 3.75%   |
| SK hynix                    | 3         | 1.88%   |
| SanDisk                     | 3         | 1.88%   |
| Marvell Technology Group    | 3         | 1.88%   |
| Kingston Technology Company | 2         | 1.25%   |
| Phison Electronics          | 1         | 0.63%   |
| Micron Technology           | 1         | 0.63%   |
| LSI Logic / Symbios Logic   | 1         | 0.63%   |
| JMicron Technology          | 1         | 0.63%   |
| Broadcom / LSI              | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 8.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 3.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 3.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 3.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7         | 3.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 2.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 2.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 2.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 2.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 1.49%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 1.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.49%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3         | 1.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 1.49%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 2         | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1%      |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1%      |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 2         | 1%      |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2         | 1%      |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1%      |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1%      |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 1%      |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 1%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 1%      |
| Intel 631xESB/632xESB IDE Controller                                                    | 2         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 108       | 61.71%  |
| IDE  | 43        | 24.57%  |
| NVMe | 16        | 9.14%   |
| RAID | 7         | 4%      |
| SCSI | 1         | 0.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 118       | 79.19%  |
| AMD    | 31        | 20.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 2.68%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 3         | 2.01%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 1.34%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.34%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 2         | 1.34%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 1.34%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2         | 1.34%   |
| Intel Core 2 CPU T7600 @ 2.33GHz              | 2         | 1.34%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.34%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.34%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.34%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.34%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 1.34%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.34%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.67%   |
| Intel Xeon CPU E5450 @ 3.00GHz                | 1         | 0.67%   |
| Intel Xeon CPU E5410 @ 2.33GHz                | 1         | 0.67%   |
| Intel Xeon CPU 5150 @ 2.66GHz                 | 1         | 0.67%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.67%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz   | 1         | 0.67%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1         | 0.67%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 1         | 0.67%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.67%   |
| Intel Pentium D CPU 3.40GHz                   | 1         | 0.67%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.67%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.67%   |
| Intel Pentium CPU J2850 @ 2.41GHz             | 1         | 0.67%   |
| Intel Pentium CPU E5500 @ 2.80GHz             | 1         | 0.67%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 0.67%   |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.67%   |
| Intel Genuine CPU T2050 @ 1.60GHz             | 1         | 0.67%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz              | 1         | 0.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.67%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.67%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.67%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.67%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 15.44%  |
| Intel Core 2 Duo        | 14        | 9.4%    |
| Intel Celeron           | 14        | 9.4%    |
| Intel Core i3           | 12        | 8.05%   |
| Intel Core i7           | 11        | 7.38%   |
| Intel Atom              | 10        | 6.71%   |
| Other                   | 7         | 4.7%    |
| Intel Pentium           | 7         | 4.7%    |
| Intel Pentium Dual-Core | 6         | 4.03%   |
| Intel Xeon              | 4         | 2.68%   |
| Intel Core 2            | 3         | 2.01%   |
| AMD Ryzen 5             | 3         | 2.01%   |
| AMD E2                  | 3         | 2.01%   |
| AMD A6                  | 3         | 2.01%   |
| Intel Pentium Dual      | 2         | 1.34%   |
| Intel Genuine           | 2         | 1.34%   |
| AMD Turion 64 X2 Mobile | 2         | 1.34%   |
| AMD Ryzen 3             | 2         | 1.34%   |
| AMD E                   | 2         | 1.34%   |
| AMD Athlon II X2        | 2         | 1.34%   |
| AMD A8                  | 2         | 1.34%   |
| Intel Pentium D         | 1         | 0.67%   |
| Intel Core m7           | 1         | 0.67%   |
| Intel Core 2 Quad       | 1         | 0.67%   |
| Intel Core 2 Extreme    | 1         | 0.67%   |
| Intel Celeron M         | 1         | 0.67%   |
| AMD Turion Dual-Core    | 1         | 0.67%   |
| AMD Sempron             | 1         | 0.67%   |
| AMD Ryzen 9             | 1         | 0.67%   |
| AMD Quad-Core           | 1         | 0.67%   |
| AMD Phenom II X2        | 1         | 0.67%   |
| AMD GX                  | 1         | 0.67%   |
| AMD FX                  | 1         | 0.67%   |
| AMD Athlon II Neo       | 1         | 0.67%   |
| AMD A12                 | 1         | 0.67%   |
| AMD A10                 | 1         | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 85        | 57.05%  |
| 4      | 46        | 30.87%  |
| 6      | 7         | 4.7%    |
| 1      | 7         | 4.7%    |
| 14     | 1         | 0.67%   |
| 12     | 1         | 0.67%   |
| 10     | 1         | 0.67%   |
| 8      | 1         | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 147       | 98.66%  |
| 2      | 2         | 1.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 91        | 61.07%  |
| 2      | 58        | 38.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 147       | 98.66%  |
| 32-bit         | 2         | 1.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 12.67%  |
| 0x1067a    | 15        | 10%     |
| 0x206a7    | 13        | 8.67%   |
| 0x30678    | 9         | 6%      |
| 0x406c4    | 5         | 3.33%   |
| 0x40651    | 5         | 3.33%   |
| 0x306a9    | 5         | 3.33%   |
| 0x6fd      | 4         | 2.67%   |
| 0x20655    | 4         | 2.67%   |
| 0x10676    | 4         | 2.67%   |
| 0x010000c8 | 4         | 2.67%   |
| 0x6fb      | 3         | 2%      |
| 0x6f6      | 3         | 2%      |
| 0x506c9    | 3         | 2%      |
| 0x306c3    | 3         | 2%      |
| 0x06006705 | 3         | 2%      |
| 0x806ec    | 2         | 1.33%   |
| 0x806ea    | 2         | 1.33%   |
| 0x806e9    | 2         | 1.33%   |
| 0x806c1    | 2         | 1.33%   |
| 0x706a1    | 2         | 1.33%   |
| 0x506e3    | 2         | 1.33%   |
| 0x406c3    | 2         | 1.33%   |
| 0x206c2    | 2         | 1.33%   |
| 0x106ca    | 2         | 1.33%   |
| 0x07030105 | 2         | 1.33%   |
| 0x05000119 | 2         | 1.33%   |
| 0xf64      | 1         | 0.67%   |
| 0xa0653    | 1         | 0.67%   |
| 0x906eb    | 1         | 0.67%   |
| 0x906ea    | 1         | 0.67%   |
| 0x906e9    | 1         | 0.67%   |
| 0x906a4    | 1         | 0.67%   |
| 0x906a3    | 1         | 0.67%   |
| 0x806eb    | 1         | 0.67%   |
| 0x6fa      | 1         | 0.67%   |
| 0x6d8      | 1         | 0.67%   |
| 0x406e3    | 1         | 0.67%   |
| 0x306d4    | 1         | 0.67%   |
| 0x30661    | 1         | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 20        | 13.42%  |
| Silvermont       | 18        | 12.08%  |
| SandyBridge      | 13        | 8.72%   |
| Core             | 13        | 8.72%   |
| KabyLake         | 11        | 7.38%   |
| Haswell          | 8         | 5.37%   |
| IvyBridge        | 7         | 4.7%    |
| Westmere         | 6         | 4.03%   |
| Excavator        | 6         | 4.03%   |
| K10              | 5         | 3.36%   |
| Skylake          | 3         | 2.01%   |
| Puma             | 3         | 2.01%   |
| Goldmont         | 3         | 2.01%   |
| Bonnell          | 3         | 2.01%   |
| Bobcat           | 3         | 2.01%   |
| Zen+             | 2         | 1.34%   |
| Zen 3            | 2         | 1.34%   |
| TigerLake        | 2         | 1.34%   |
| Piledriver       | 2         | 1.34%   |
| P6               | 2         | 1.34%   |
| K8 Hammer        | 2         | 1.34%   |
| K10 Llano        | 2         | 1.34%   |
| Goldmont plus    | 2         | 1.34%   |
| Alderlake Hybrid | 2         | 1.34%   |
| Zen 2            | 1         | 0.67%   |
| Zen              | 1         | 0.67%   |
| NetBurst         | 1         | 0.67%   |
| Nehalem          | 1         | 0.67%   |
| K8 & K10 hybrid  | 1         | 0.67%   |
| Jaguar           | 1         | 0.67%   |
| CometLake        | 1         | 0.67%   |
| Broadwell        | 1         | 0.67%   |
| Unknown          | 1         | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 89        | 55.63%  |
| AMD    | 36        | 22.5%   |
| Nvidia | 35        | 21.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 5.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 4.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 2.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 2.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 2.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.35%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.35%   |
| Intel HD Graphics 500                                                                    | 3         | 1.76%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.76%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 1.76%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.18%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.18%   |
| Intel HD Graphics 620                                                                    | 2         | 1.18%   |
| Intel HD Graphics 530                                                                    | 2         | 1.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.18%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.18%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.18%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.18%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.59%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.59%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.59%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 0.59%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.59%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.59%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.59%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.59%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.59%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.59%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.59%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 78        | 52.35%  |
| 1 x AMD        | 31        | 20.81%  |
| 1 x Nvidia     | 25        | 16.78%  |
| Intel + Nvidia | 10        | 6.71%   |
| 2 x AMD        | 4         | 2.68%   |
| Intel + AMD    | 1         | 0.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 129       | 86%     |
| Proprietary | 18        | 12%     |
| Unknown     | 3         | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 60.4%   |
| 0.01-0.5   | 31        | 20.81%  |
| 1.01-2.0   | 10        | 6.71%   |
| 0.51-1.0   | 10        | 6.71%   |
| 3.01-4.0   | 5         | 3.36%   |
| 5.01-6.0   | 3         | 2.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 22        | 14.67%  |
| AU Optronics            | 14        | 9.33%   |
| LG Display              | 12        | 8%      |
| Chimei Innolux          | 12        | 8%      |
| BOE                     | 11        | 7.33%   |
| Hewlett-Packard         | 10        | 6.67%   |
| Goldstar                | 9         | 6%      |
| Chi Mei Optoelectronics | 8         | 5.33%   |
| Acer                    | 6         | 4%      |
| Apple                   | 5         | 3.33%   |
| Sony                    | 4         | 2.67%   |
| Ancor Communications    | 4         | 2.67%   |
| NEC Computers           | 3         | 2%      |
| ViewSonic               | 2         | 1.33%   |
| PANDA                   | 2         | 1.33%   |
| LG Philips              | 2         | 1.33%   |
| InfoVision              | 2         | 1.33%   |
| HannStar                | 2         | 1.33%   |
| Dell                    | 2         | 1.33%   |
| CPT                     | 2         | 1.33%   |
| Unknown                 | 2         | 1.33%   |
| Toshiba                 | 1         | 0.67%   |
| TCL                     | 1         | 0.67%   |
| Seiko/Epson             | 1         | 0.67%   |
| SANYO                   | 1         | 0.67%   |
| Philips                 | 1         | 0.67%   |
| OEM                     | 1         | 0.67%   |
| NCS                     | 1         | 0.67%   |
| MSI                     | 1         | 0.67%   |
| Lenovo                  | 1         | 0.67%   |
| Hitachi                 | 1         | 0.67%   |
| eMachines               | 1         | 0.67%   |
| BenQ                    | 1         | 0.67%   |
| Belinea                 | 1         | 0.67%   |
| AOC                     | 1         | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 2         | 1.28%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.28%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 2         | 1.28%   |
| Unknown                                                               | 2         | 1.28%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1         | 0.64%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1         | 0.64%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1         | 0.64%   |
| Toshiba L705A LCD705A 1280x1024 340x270mm 17.1-inch                   | 1         | 0.64%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.64%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.64%   |
| Sony TV SNYDC01 1360x768                                              | 1         | 0.64%   |
| Sony TV SNY3002 1920x1080 531x299mm 24.0-inch                         | 1         | 0.64%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                    | 1         | 0.64%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.64%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.64%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch  | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 0.64%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1         | 0.64%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.64%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.64%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1         | 0.64%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch | 1         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 46        | 30.67%  |
| 1920x1080 (FHD)    | 43        | 28.67%  |
| 1920x1200 (WUXGA)  | 11        | 7.33%   |
| 1280x800 (WXGA)    | 9         | 6%      |
| 3840x2160 (4K)     | 8         | 5.33%   |
| 1280x1024 (SXGA)   | 6         | 4%      |
| 1680x1050 (WSXGA+) | 5         | 3.33%   |
| 1600x900 (HD+)     | 4         | 2.67%   |
| 1440x900 (WXGA+)   | 4         | 2.67%   |
| 1360x768           | 3         | 2%      |
| 2560x1440 (QHD)    | 2         | 1.33%   |
| 1024x600           | 2         | 1.33%   |
| Unknown            | 2         | 1.33%   |
| 5280x1080          | 1         | 0.67%   |
| 3840x2400          | 1         | 0.67%   |
| 1920x540           | 1         | 0.67%   |
| 1280x720 (HD)      | 1         | 0.67%   |
| 1024x768 (XGA)     | 1         | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 20.53%  |
| 17      | 13        | 8.61%   |
| 14      | 13        | 8.61%   |
| 13      | 12        | 7.95%   |
| 24      | 10        | 6.62%   |
| 23      | 8         | 5.3%    |
| 21      | 8         | 5.3%    |
| Unknown | 8         | 5.3%    |
| 12      | 6         | 3.97%   |
| 11      | 6         | 3.97%   |
| 27      | 5         | 3.31%   |
| 19      | 5         | 3.31%   |
| 18      | 5         | 3.31%   |
| 20      | 4         | 2.65%   |
| 16      | 3         | 1.99%   |
| 10      | 3         | 1.99%   |
| 72      | 2         | 1.32%   |
| 46      | 2         | 1.32%   |
| 22      | 2         | 1.32%   |
| 65      | 1         | 0.66%   |
| 32      | 1         | 0.66%   |
| 31      | 1         | 0.66%   |
| 28      | 1         | 0.66%   |
| 26      | 1         | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 57        | 38.26%  |
| 501-600     | 22        | 14.77%  |
| 401-500     | 22        | 14.77%  |
| 201-300     | 19        | 12.75%  |
| 351-400     | 12        | 8.05%   |
| Unknown     | 8         | 5.37%   |
| 601-700     | 3         | 2.01%   |
| 1001-1500   | 3         | 2.01%   |
| 1501-2000   | 2         | 1.34%   |
| 701-800     | 1         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 100       | 69.44%  |
| 16/10   | 28        | 19.44%  |
| 5/4     | 6         | 4.17%   |
| Unknown | 6         | 4.17%   |
| 4/3     | 2         | 1.39%   |
| 6/5     | 1         | 0.69%   |
| 3/2     | 1         | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 31        | 20.53%  |
| 81-90          | 21        | 13.91%  |
| 201-250        | 21        | 13.91%  |
| 151-200        | 12        | 7.95%   |
| 141-150        | 8         | 5.3%    |
| Unknown        | 8         | 5.3%    |
| 51-60          | 6         | 3.97%   |
| 301-350        | 6         | 3.97%   |
| 121-130        | 6         | 3.97%   |
| 71-80          | 5         | 3.31%   |
| 61-70          | 5         | 3.31%   |
| 251-300        | 5         | 3.31%   |
| 131-140        | 5         | 3.31%   |
| More than 1000 | 3         | 1.99%   |
| 351-500        | 3         | 1.99%   |
| 41-50          | 3         | 1.99%   |
| 501-1000       | 2         | 1.32%   |
| 111-120        | 1         | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 49        | 33.33%  |
| 101-120       | 45        | 30.61%  |
| 121-160       | 34        | 23.13%  |
| Unknown       | 8         | 5.44%   |
| 161-240       | 5         | 3.4%    |
| 1-50          | 4         | 2.72%   |
| More than 240 | 2         | 1.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 133       | 88.67%  |
| 2     | 15        | 10%     |
| 3     | 1         | 0.67%   |
| 0     | 1         | 0.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 80        | 34.93%  |
| Intel                                 | 54        | 23.58%  |
| Qualcomm Atheros                      | 32        | 13.97%  |
| Broadcom                              | 19        | 8.3%    |
| Ralink                                | 6         | 2.62%   |
| Ralink Technology                     | 5         | 2.18%   |
| Broadcom Limited                      | 5         | 2.18%   |
| TP-Link                               | 4         | 1.75%   |
| Nvidia                                | 4         | 1.75%   |
| Sierra Wireless                       | 2         | 0.87%   |
| Qualcomm Atheros Communications       | 2         | 0.87%   |
| Marvell Technology Group              | 2         | 0.87%   |
| ASUSTek Computer                      | 2         | 0.87%   |
| ASIX Electronics                      | 2         | 0.87%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.44%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.44%   |
| Samsung Electronics                   | 1         | 0.44%   |
| Microsoft                             | 1         | 0.44%   |
| MediaTek                              | 1         | 0.44%   |
| Linksys                               | 1         | 0.44%   |
| Dell                                  | 1         | 0.44%   |
| D-Link                                | 1         | 0.44%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.44%   |
| 3Com                                  | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 53        | 19.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 17        | 6.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 7         | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 7         | 2.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 1.85%   |
| Intel Wireless 3165                                                                           | 5         | 1.85%   |
| Ralink MT7601U Wireless Adapter                                                               | 4         | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 4         | 1.48%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4         | 1.48%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 1.48%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 1.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 3         | 1.11%   |
| Intel Wireless 7260                                                                           | 3         | 1.11%   |
| Intel Wireless 3160                                                                           | 3         | 1.11%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 2         | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2         | 0.74%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 0.74%   |
| Realtek 802.11ac NIC                                                                          | 2         | 0.74%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 2         | 0.74%   |
| Nvidia MCP77 Ethernet                                                                         | 2         | 0.74%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 0.74%   |
| Intel Ethernet Connection I218-LM                                                             | 2         | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 0.74%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 0.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 0.74%   |
| Intel 82567LM Gigabit Network Connection                                                      | 2         | 0.74%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2         | 0.74%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                             | 2         | 0.74%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                        | 2         | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 0.74%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                                                 | 2         | 0.74%   |
| ZTE WCDMA MSM Android                                                                         | 1         | 0.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1         | 0.37%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 0.37%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY                    | 1         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 38        | 29.23%  |
| Realtek Semiconductor                 | 27        | 20.77%  |
| Qualcomm Atheros                      | 27        | 20.77%  |
| Broadcom                              | 8         | 6.15%   |
| Ralink                                | 6         | 4.62%   |
| Ralink Technology                     | 5         | 3.85%   |
| TP-Link                               | 4         | 3.08%   |
| Broadcom Limited                      | 3         | 2.31%   |
| Sierra Wireless                       | 2         | 1.54%   |
| Qualcomm Atheros Communications       | 2         | 1.54%   |
| ASUSTek Computer                      | 2         | 1.54%   |
| Microsoft                             | 1         | 0.77%   |
| MediaTek                              | 1         | 0.77%   |
| Linksys                               | 1         | 0.77%   |
| Dell                                  | 1         | 0.77%   |
| D-Link                                | 1         | 0.77%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.77%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 7         | 5.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 4.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 4.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 3.82%   |
| Intel Wireless 3165                                                                           | 5         | 3.82%   |
| Ralink MT7601U Wireless Adapter                                                               | 4         | 3.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 4         | 3.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4         | 3.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 3.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 3.05%   |
| Intel Wireless 7260                                                                           | 3         | 2.29%   |
| Intel Wireless 3160                                                                           | 3         | 2.29%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 2         | 1.53%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2         | 1.53%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 1.53%   |
| Realtek 802.11ac NIC                                                                          | 2         | 1.53%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 1.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 1.53%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 1.53%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.53%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 1.53%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1         | 0.76%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 0.76%   |
| Sierra Wireless EM7455                                                                        | 1         | 0.76%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 0.76%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.76%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.76%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1         | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.76%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 74        | 54.41%  |
| Intel                             | 26        | 19.12%  |
| Broadcom                          | 12        | 8.82%   |
| Qualcomm Atheros                  | 10        | 7.35%   |
| Nvidia                            | 4         | 2.94%   |
| Marvell Technology Group          | 2         | 1.47%   |
| Broadcom Limited                  | 2         | 1.47%   |
| ASIX Electronics                  | 2         | 1.47%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.74%   |
| Sundance Technology Inc / IC Plus | 1         | 0.74%   |
| Samsung Electronics               | 1         | 0.74%   |
| 3Com                              | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 53        | 38.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 17        | 12.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 5.07%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 3         | 2.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 1.45%   |
| Nvidia MCP77 Ethernet                                                         | 2         | 1.45%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 1.45%   |
| Intel 82567LM Gigabit Network Connection                                      | 2         | 1.45%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 1.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 1.45%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 1.45%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 1.45%   |
| ZTE WCDMA MSM Android                                                         | 1         | 0.72%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1         | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.72%   |
| Realtek USB 10/100 LAN                                                        | 1         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.72%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.72%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.72%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.72%   |
| Nvidia MCP51 Ethernet Controller                                              | 1         | 0.72%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.72%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.72%   |
| Intel Ethernet Connection (17) I219-V                                         | 1         | 0.72%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 0.72%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.72%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.72%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1         | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.72%   |
| Intel 82567LF-3 Gigabit Network Connection                                    | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 130       | 51.59%  |
| WiFi     | 121       | 48.02%  |
| Unknown  | 1         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 62.82%  |
| Ethernet | 58        | 37.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 90        | 60.4%   |
| 1     | 51        | 34.23%  |
| 0     | 4         | 2.68%   |
| 3     | 3         | 2.01%   |
| 4     | 1         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 116       | 77.33%  |
| Yes  | 34        | 22.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 32.47%  |
| Realtek Semiconductor           | 13        | 16.88%  |
| Lite-On Technology              | 5         | 6.49%   |
| Hewlett-Packard                 | 5         | 6.49%   |
| Cambridge Silicon Radio         | 5         | 6.49%   |
| Qualcomm Atheros Communications | 4         | 5.19%   |
| IMC Networks                    | 4         | 5.19%   |
| Broadcom                        | 4         | 5.19%   |
| Apple                           | 4         | 5.19%   |
| Dell                            | 2         | 2.6%    |
| Chicony Electronics             | 2         | 2.6%    |
| Toshiba                         | 1         | 1.3%    |
| Ralink                          | 1         | 1.3%    |
| Foxconn / Hon Hai               | 1         | 1.3%    |
| ASUSTek Computer                | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 18.18%  |
| Realtek Bluetooth Radio                             | 7         | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 6.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.19%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 3.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.6%    |
| Lite-On Bluetooth Device                            | 2         | 2.6%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.6%    |
| Intel AX201 Bluetooth                               | 2         | 2.6%    |
| IMC Networks Bluetooth Device                       | 2         | 2.6%    |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.6%    |
| Dell Wireless 355 Bluetooth                         | 2         | 2.6%    |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 2.6%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 2.6%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 2.6%    |
| Toshiba Askey Bluetooth Module                      | 1         | 1.3%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.3%    |
| Realtek RTL8821A Bluetooth                          | 1         | 1.3%    |
| Ralink RT3290 Bluetooth                             | 1         | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.3%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.3%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.3%    |
| Intel Bluetooth Device                              | 1         | 1.3%    |
| Intel AX200 Bluetooth                               | 1         | 1.3%    |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.3%    |
| IMC Networks Bluetooth Radio                        | 1         | 1.3%    |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.3%    |
| Broadcom HP Portable Valentine                      | 1         | 1.3%    |
| Broadcom HP Bluethunder                             | 1         | 1.3%    |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.3%    |
| Apple Bluetooth USB Host Controller                 | 1         | 1.3%    |
| Apple Bluetooth HCI                                 | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 109       | 60.56%  |
| AMD                   | 36        | 20%     |
| Nvidia                | 22        | 12.22%  |
| C-Media Electronics   | 3         | 1.67%   |
| Logitech              | 2         | 1.11%   |
| JMTek                 | 2         | 1.11%   |
| Texas Instruments     | 1         | 0.56%   |
| Realtek Semiconductor | 1         | 0.56%   |
| Ensoniq               | 1         | 0.56%   |
| Creative Labs         | 1         | 0.56%   |
| Blue Microphones      | 1         | 0.56%   |
| ATI Technologies      | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 6.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 3.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 3.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 3.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 3.77%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 2.83%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 2.83%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 2.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.36%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.36%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5         | 2.36%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 1.89%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 1.89%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.42%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.42%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.42%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.94%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.94%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 2         | 0.94%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.94%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.47%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 18.84%  |
| Unknown             | 25        | 18.12%  |
| SK hynix            | 22        | 15.94%  |
| Kingston            | 16        | 11.59%  |
| Micron Technology   | 13        | 9.42%   |
| Unknown             | 5         | 3.62%   |
| Unknown (ABCD)      | 4         | 2.9%    |
| Elpida              | 4         | 2.9%    |
| Nanya Technology    | 3         | 2.17%   |
| Corsair             | 3         | 2.17%   |
| A-DATA Technology   | 3         | 2.17%   |
| Ramaxel Technology  | 2         | 1.45%   |
| Unknown (0x7F61)    | 1         | 0.72%   |
| Transcend           | 1         | 0.72%   |
| Qumo                | 1         | 0.72%   |
| Qimonda             | 1         | 0.72%   |
| GeIL                | 1         | 0.72%   |
| G.Skill             | 1         | 0.72%   |
| G Skil              | 1         | 0.72%   |
| Avant               | 1         | 0.72%   |
| 2C0C1121390963FE    | 1         | 0.72%   |
| 2C0C1121390963FD    | 1         | 0.72%   |
| 2C0C1121390963F9    | 1         | 0.72%   |
| 2C0C1121390963F8    | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 5         | 3.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 3         | 2.07%   |
| Unknown RAM Module 2GB SODIMM DDR2                                | 2         | 1.38%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 2         | 1.38%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2         | 1.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 1.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s         | 2         | 1.38%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s          | 2         | 1.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1         | 0.69%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                           | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                        | 1         | 0.69%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                          | 1         | 0.69%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                        | 1         | 0.69%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 1         | 0.69%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                    | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR2                             | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM SDRAM                              | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                       | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM DDR2                               | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                        | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                        | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                            | 1         | 0.69%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                             | 1         | 0.69%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                    | 1         | 0.69%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                     | 1         | 0.69%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                     | 1         | 0.69%   |
| Unknown RAM Module 1024MB DIMM SDRAM                              | 1         | 0.69%   |
| Unknown RAM Module 1024MB DIMM DDR2                               | 1         | 0.69%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                        | 1         | 0.69%   |
| Unknown (0x7F61) RAM Module 1GB FB-DIMM DDR2 667MT/s              | 1         | 0.69%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s                | 1         | 0.69%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.69%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.69%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                     | 1         | 0.69%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s             | 1         | 0.69%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s             | 1         | 0.69%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s              | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 46        | 38.98%  |
| DDR4    | 24        | 20.34%  |
| DDR2    | 23        | 19.49%  |
| SDRAM   | 9         | 7.63%   |
| LPDDR4  | 6         | 5.08%   |
| Unknown | 6         | 5.08%   |
| DDR     | 3         | 2.54%   |
| DRAM    | 1         | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 72        | 62.61%  |
| DIMM         | 40        | 34.78%  |
| FB-DIMM      | 2         | 1.74%   |
| Row Of Chips | 1         | 0.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 41        | 32.03%  |
| 4096  | 40        | 31.25%  |
| 8192  | 22        | 17.19%  |
| 1024  | 17        | 13.28%  |
| 16384 | 6         | 4.69%   |
| 32768 | 1         | 0.78%   |
| 512   | 1         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 35        | 28.23%  |
| 667     | 12        | 9.68%   |
| 2667    | 10        | 8.06%   |
| 1333    | 10        | 8.06%   |
| 3200    | 9         | 7.26%   |
| Unknown | 8         | 6.45%   |
| 2400    | 6         | 4.84%   |
| 800     | 6         | 4.84%   |
| 3266    | 3         | 2.42%   |
| 975     | 3         | 2.42%   |
| 4199    | 2         | 1.61%   |
| 2133    | 2         | 1.61%   |
| 2048    | 2         | 1.61%   |
| 1334    | 2         | 1.61%   |
| 1066    | 2         | 1.61%   |
| 400     | 2         | 1.61%   |
| 49926   | 1         | 0.81%   |
| 19791   | 1         | 0.81%   |
| 3933    | 1         | 0.81%   |
| 3500    | 1         | 0.81%   |
| 1866    | 1         | 0.81%   |
| 1800    | 1         | 0.81%   |
| 1639    | 1         | 0.81%   |
| 1067    | 1         | 0.81%   |
| 1033    | 1         | 0.81%   |
| 133     | 1         | 0.81%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Mustek Systems  | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 22        | 25.88%  |
| Quanta                                 | 6         | 7.06%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 7.06%   |
| Apple                                  | 6         | 7.06%   |
| Syntek                                 | 5         | 5.88%   |
| Suyin                                  | 5         | 5.88%   |
| IMC Networks                           | 5         | 5.88%   |
| Alcor Micro                            | 4         | 4.71%   |
| Silicon Motion                         | 3         | 3.53%   |
| Realtek Semiconductor                  | 3         | 3.53%   |
| Microdia                               | 3         | 3.53%   |
| Lite-On Technology                     | 3         | 3.53%   |
| Z-Star Microelectronics                | 2         | 2.35%   |
| Sunplus Innovation Technology          | 2         | 2.35%   |
| Ricoh                                  | 1         | 1.18%   |
| Pixart Imaging                         | 1         | 1.18%   |
| OmniVision Technologies                | 1         | 1.18%   |
| Microsoft                              | 1         | 1.18%   |
| Logitech                               | 1         | 1.18%   |
| Jieli Technology                       | 1         | 1.18%   |
| Hopewin Electronic Material            | 1         | 1.18%   |
| Hewlett-Packard                        | 1         | 1.18%   |
| Generalplus Technology                 | 1         | 1.18%   |
| Aveo Technology                        | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                       | 5         | 5.88%   |
| Chicony Integrated Camera                           | 3         | 3.53%   |
| Syntek USB Video Device                             | 2         | 2.35%   |
| Syntek Lenovo EasyCamera                            | 2         | 2.35%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 2.35%   |
| Quanta HP TrueVision HD Camera                      | 2         | 2.35%   |
| Lite-On HP Webcam                                   | 2         | 2.35%   |
| Chicony HP High Definition 1MP Webcam               | 2         | 2.35%   |
| Chicony FJ Camera                                   | 2         | 2.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 2.35%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 2         | 2.35%   |
| Apple Built-in iSight                               | 2         | 2.35%   |
| Alcor Micro USB 2.0 Camera                          | 2         | 2.35%   |
| Z-Star Webcam                                       | 1         | 1.18%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 1.18%   |
| Syntek Integrated Camera                            | 1         | 1.18%   |
| Suyin USB 2.0 Camera                                | 1         | 1.18%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.18%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 1.18%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.18%   |
| Sunplus HD WebCam                                   | 1         | 1.18%   |
| Silicon Motion WebCam SC-10HDD13335N                | 1         | 1.18%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 1.18%   |
| Silicon Motion Web Camera                           | 1         | 1.18%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.18%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.18%   |
| Realtek USB Camera                                  | 1         | 1.18%   |
| Realtek Built-In Video Camera                       | 1         | 1.18%   |
| Quanta VGA WebCam                                   | 1         | 1.18%   |
| Quanta HP Truevision HD                             | 1         | 1.18%   |
| Quanta HD Webcam                                    | 1         | 1.18%   |
| Quanta ACER HD User Facing                          | 1         | 1.18%   |
| Pixart Imaging USB_2.0_Webcam                       | 1         | 1.18%   |
| OmniVision OV2640 Webcam                            | 1         | 1.18%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1         | 1.18%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.18%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.18%   |
| Microdia Integrated Webcam                          | 1         | 1.18%   |
| Logitech HD Webcam C615                             | 1         | 1.18%   |
| Lite-On Integrated Camera                           | 1         | 1.18%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| O2 Micro    | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 114       | 76%     |
| 1     | 30        | 20%     |
| 2     | 6         | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 23.81%  |
| Graphics card            | 9         | 21.43%  |
| Net/wireless             | 6         | 14.29%  |
| Chipcard                 | 4         | 9.52%   |
| Storage                  | 2         | 4.76%   |
| Multimedia controller    | 2         | 4.76%   |
| Bluetooth                | 2         | 4.76%   |
| Unassigned class         | 1         | 2.38%   |
| Sound                    | 1         | 2.38%   |
| Network                  | 1         | 2.38%   |
| Net/ethernet             | 1         | 2.38%   |
| Dvb card                 | 1         | 2.38%   |
| Communication controller | 1         | 2.38%   |
| Camera                   | 1         | 2.38%   |

