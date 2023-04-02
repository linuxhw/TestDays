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

Total: 182

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Linux Lite 5.8 | 23        | 18.11%  |
| Linux Lite 6.0 | 19        | 14.96%  |
| Linux Lite 5.2 | 17        | 13.39%  |
| Linux Lite 5.0 | 17        | 13.39%  |
| Linux Lite 5.4 | 16        | 12.6%   |
| Linux Lite 5.6 | 13        | 10.24%  |
| Linux Lite 6.2 | 12        | 9.45%   |
| Linux Lite 3.8 | 5         | 3.94%   |
| Linux Lite 4.8 | 2         | 1.57%   |
| Linux Lite 4.6 | 1         | 0.79%   |
| Linux Lite 4.4 | 1         | 0.79%   |
| Linux Lite 4.2 | 1         | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Lite | 125       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 6         | 4.48%   |
| 5.4.0-70-generic  | 5         | 3.73%   |
| 5.4.0-96-generic  | 4         | 2.99%   |
| 5.4.0-91-generic  | 4         | 2.99%   |
| 5.4.0-52-generic  | 4         | 2.99%   |
| 5.4.0-40-generic  | 4         | 2.99%   |
| 5.4.0-109-generic | 4         | 2.99%   |
| 5.4.0-104-generic | 4         | 2.99%   |
| 5.15.0-33-generic | 4         | 2.99%   |
| 5.4.0-58-generic  | 3         | 2.24%   |
| 5.4.0-48-generic  | 3         | 2.24%   |
| 5.4.0-113-generic | 3         | 2.24%   |
| 5.4.0-107-generic | 3         | 2.24%   |
| 5.15.0-58-generic | 3         | 2.24%   |
| 5.15.0-52-generic | 3         | 2.24%   |
| 5.15.0-47-generic | 3         | 2.24%   |
| 5.15.0-46-generic | 3         | 2.24%   |
| 5.4.0-90-generic  | 2         | 1.49%   |
| 5.4.0-88-generic  | 2         | 1.49%   |
| 5.4.0-81-generic  | 2         | 1.49%   |
| 5.4.0-80-generic  | 2         | 1.49%   |
| 5.4.0-74-generic  | 2         | 1.49%   |
| 5.4.0-54-generic  | 2         | 1.49%   |
| 5.4.0-33-generic  | 2         | 1.49%   |
| 5.4.0-110-generic | 2         | 1.49%   |
| 5.4.0-105-generic | 2         | 1.49%   |
| 5.15.0-69-generic | 2         | 1.49%   |
| 5.15.0-60-generic | 2         | 1.49%   |
| 5.15.0-56-generic | 2         | 1.49%   |
| 5.15.0-48-generic | 2         | 1.49%   |
| 4.4.0-112-generic | 2         | 1.49%   |
| 6.1.0-1.linuxlite | 1         | 0.75%   |
| 6.0.0-1.linuxlite | 1         | 0.75%   |
| 6.0.0             | 1         | 0.75%   |
| 5.9.0             | 1         | 0.75%   |
| 5.4.0-99-generic  | 1         | 0.75%   |
| 5.4.0-94-generic  | 1         | 0.75%   |
| 5.4.0-77-generic  | 1         | 0.75%   |
| 5.4.0-72-generic  | 1         | 0.75%   |
| 5.4.0-71-generic  | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 80        | 62.02%  |
| 5.15.0  | 29        | 22.48%  |
| 4.15.0  | 5         | 3.88%   |
| 4.4.0   | 4         | 3.1%    |
| 5.13.0  | 3         | 2.33%   |
| 6.0.0   | 2         | 1.55%   |
| 6.1.0   | 1         | 0.78%   |
| 5.9.0   | 1         | 0.78%   |
| 5.19.0  | 1         | 0.78%   |
| 5.16.9  | 1         | 0.78%   |
| 5.16.0  | 1         | 0.78%   |
| 5.10.0  | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 80        | 62.02%  |
| 5.15    | 29        | 22.48%  |
| 4.15    | 5         | 3.88%   |
| 4.4     | 4         | 3.1%    |
| 5.13    | 3         | 2.33%   |
| 6.0     | 2         | 1.55%   |
| 5.16    | 2         | 1.55%   |
| 6.1     | 1         | 0.78%   |
| 5.9     | 1         | 0.78%   |
| 5.19    | 1         | 0.78%   |
| 5.10    | 1         | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 121       | 96.8%   |
| i686   | 4         | 3.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 97        | 77.6%   |
| GNOME   | 25        | 20%     |
| Unknown | 2         | 1.6%    |
| Deepin  | 1         | 0.8%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 123       | 98.4%   |
| Tty     | 1         | 0.8%    |
| Unknown | 1         | 0.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 75        | 59.06%  |
| TDM     | 28        | 22.05%  |
| Unknown | 23        | 18.11%  |
| GDM     | 1         | 0.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 64        | 51.2%   |
| pt_BR | 7         | 5.6%    |
| de_DE | 7         | 5.6%    |
| pl_PL | 6         | 4.8%    |
| fr_FR | 6         | 4.8%    |
| en_GB | 6         | 4.8%    |
| es_MX | 4         | 3.2%    |
| ru_UA | 3         | 2.4%    |
| es_ES | 3         | 2.4%    |
| ru_RU | 2         | 1.6%    |
| it_IT | 2         | 1.6%    |
| en_CA | 2         | 1.6%    |
| zh_CN | 1         | 0.8%    |
| tr_TR | 1         | 0.8%    |
| pt_PT | 1         | 0.8%    |
| nl_NL | 1         | 0.8%    |
| hu_HU | 1         | 0.8%    |
| fr_CA | 1         | 0.8%    |
| es_CO | 1         | 0.8%    |
| es_CL | 1         | 0.8%    |
| en_NZ | 1         | 0.8%    |
| en_IE | 1         | 0.8%    |
| en_AU | 1         | 0.8%    |
| da_DK | 1         | 0.8%    |
| C     | 1         | 0.8%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 73        | 58.4%   |
| EFI  | 52        | 41.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 112       | 89.6%   |
| Overlay | 9         | 7.2%    |
| Btrfs   | 2         | 1.6%    |
| Zfs     | 1         | 0.8%    |
| Ext3    | 1         | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 51        | 40.8%   |
| Unknown | 39        | 31.2%   |
| MBR     | 35        | 28%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 103       | 81.75%  |
| Yes       | 23        | 18.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 90        | 71.43%  |
| Yes       | 36        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 26        | 20.8%   |
| ASUSTek Computer    | 18        | 14.4%   |
| Lenovo              | 13        | 10.4%   |
| Acer                | 12        | 9.6%    |
| Dell                | 9         | 7.2%    |
| MSI                 | 5         | 4%      |
| Samsung Electronics | 4         | 3.2%    |
| Apple               | 4         | 3.2%    |
| Pegatron            | 3         | 2.4%    |
| Gigabyte Technology | 3         | 2.4%    |
| Fujitsu             | 3         | 2.4%    |
| Toshiba             | 2         | 1.6%    |
| Minix               | 2         | 1.6%    |
| Intel               | 2         | 1.6%    |
| Foxconn             | 2         | 1.6%    |
| ASRock              | 2         | 1.6%    |
| UMAX                | 1         | 0.8%    |
| TR                  | 1         | 0.8%    |
| Thomson             | 1         | 0.8%    |
| Sony                | 1         | 0.8%    |
| Packard Bell        | 1         | 0.8%    |
| Jetway              | 1         | 0.8%    |
| Inventec            | 1         | 0.8%    |
| Insignia            | 1         | 0.8%    |
| Google              | 1         | 0.8%    |
| Gateway             | 1         | 0.8%    |
| EVGA                | 1         | 0.8%    |
| Braview             | 1         | 0.8%    |
| Biostar             | 1         | 0.8%    |
| AWOW                | 1         | 0.8%    |
| ABIT                | 1         | 0.8%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| MSI MS-7758                            | 2         | 1.6%    |
| UMAX VisionBook 12Wi 64G               | 1         | 0.8%    |
| TR ST Pro-KN                           | 1         | 0.8%    |
| Toshiba Satellite T215D                | 1         | 0.8%    |
| Toshiba QOSMIO X70-B                   | 1         | 0.8%    |
| Thomson PT-NEO14A.2WH32                | 1         | 0.8%    |
| Sony VGC-JS54FB_W                      | 1         | 0.8%    |
| Samsung X420/X520                      | 1         | 0.8%    |
| Samsung NC110P/NC108P/NC111P           | 1         | 0.8%    |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 0.8%    |
| Samsung 530XBB                         | 1         | 0.8%    |
| Pegatron H36FF                         | 1         | 0.8%    |
| Pegatron 520-1135la                    | 1         | 0.8%    |
| Pegatron 520-1030a                     | 1         | 0.8%    |
| Packard Bell ISTART D2314              | 1         | 0.8%    |
| MSI MS-N014                            | 1         | 0.8%    |
| MSI MS-7C95                            | 1         | 0.8%    |
| MSI FZ079AA-ABF a6625fr                | 1         | 0.8%    |
| Minix Z83-4                            | 1         | 0.8%    |
| Minix Z64                              | 1         | 0.8%    |
| Lenovo ThinkStation P320 30BH000BFR    | 1         | 0.8%    |
| Lenovo ThinkPad T400 6475E13           | 1         | 0.8%    |
| Lenovo ThinkPad L480 20LS001AMC        | 1         | 0.8%    |
| Lenovo ThinkPad A475 20KMS08300        | 1         | 0.8%    |
| Lenovo ThinkCentre M91p 4524RS6        | 1         | 0.8%    |
| Lenovo ThinkCentre M91p 4518E2M        | 1         | 0.8%    |
| Lenovo ThinkCentre A55 9265BL7         | 1         | 0.8%    |
| Lenovo MIIX 300-10IBY 80NR             | 1         | 0.8%    |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1    | 1         | 0.8%    |
| Lenovo IdeaPad 320-15ABR 80XS          | 1         | 0.8%    |
| Lenovo IdeaPad 100-14IBY 80MH          | 1         | 0.8%    |
| Lenovo H505S 10107                     | 1         | 0.8%    |
| Lenovo 3000 V200 0764A11               | 1         | 0.8%    |
| Jetway I61MG4                          | 1         | 0.8%    |
| Inventec Dell Thin Client Desktop 3290 | 1         | 0.8%    |
| Intel H61M-S1                          | 1         | 0.8%    |
| Intel DG31PR AAD97573-300              | 1         | 0.8%    |
| Insignia NS-P11W7100                   | 1         | 0.8%    |
| HP Z400 Workstation                    | 1         | 0.8%    |
| HP xw8600 Workstation                  | 1         | 0.8%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HP Compaq               | 8         | 6.4%    |
| Acer Aspire             | 7         | 5.6%    |
| Dell Inspiron           | 4         | 3.2%    |
| Lenovo ThinkPad         | 3         | 2.4%    |
| Lenovo ThinkCentre      | 3         | 2.4%    |
| Lenovo IdeaPad          | 3         | 2.4%    |
| HP Laptop               | 3         | 2.4%    |
| HP EliteBook            | 3         | 2.4%    |
| MSI MS-7758             | 2         | 1.6%    |
| HP Pavilion             | 2         | 1.6%    |
| ASUS VivoBook           | 2         | 1.6%    |
| UMAX VisionBook         | 1         | 0.8%    |
| TR ST                   | 1         | 0.8%    |
| Toshiba Satellite       | 1         | 0.8%    |
| Toshiba QOSMIO          | 1         | 0.8%    |
| Thomson PT-NEO14A.2WH32 | 1         | 0.8%    |
| Sony VGC-JS54FB         | 1         | 0.8%    |
| Samsung X420            | 1         | 0.8%    |
| Samsung NC110P          | 1         | 0.8%    |
| Samsung 905S3G          | 1         | 0.8%    |
| Samsung 530XBB          | 1         | 0.8%    |
| Pegatron H36FF          | 1         | 0.8%    |
| Pegatron 520-1135la     | 1         | 0.8%    |
| Pegatron 520-1030a      | 1         | 0.8%    |
| Packard Bell ISTART     | 1         | 0.8%    |
| MSI MS-N014             | 1         | 0.8%    |
| MSI MS-7C95             | 1         | 0.8%    |
| MSI FZ079AA-ABF         | 1         | 0.8%    |
| Minix Z83-4             | 1         | 0.8%    |
| Minix Z64               | 1         | 0.8%    |
| Lenovo ThinkStation     | 1         | 0.8%    |
| Lenovo MIIX             | 1         | 0.8%    |
| Lenovo H505S            | 1         | 0.8%    |
| Lenovo 3000             | 1         | 0.8%    |
| Jetway I61MG4           | 1         | 0.8%    |
| Inventec Dell           | 1         | 0.8%    |
| Intel H61M-S1           | 1         | 0.8%    |
| Intel DG31PR            | 1         | 0.8%    |
| Insignia NS-P11W7100    | 1         | 0.8%    |
| HP Z400                 | 1         | 0.8%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2008 | 16        | 12.8%   |
| 2010 | 15        | 12%     |
| 2011 | 14        | 11.2%   |
| 2012 | 11        | 8.8%    |
| 2014 | 10        | 8%      |
| 2007 | 10        | 8%      |
| 2018 | 9         | 7.2%    |
| 2020 | 7         | 5.6%    |
| 2016 | 6         | 4.8%    |
| 2015 | 6         | 4.8%    |
| 2017 | 5         | 4%      |
| 2019 | 4         | 3.2%    |
| 2009 | 3         | 2.4%    |
| 2022 | 2         | 1.6%    |
| 2021 | 2         | 1.6%    |
| 2013 | 2         | 1.6%    |
| 2006 | 2         | 1.6%    |
| 2004 | 1         | 0.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 73        | 58.4%   |
| Desktop    | 44        | 35.2%   |
| All in one | 4         | 3.2%    |
| Tablet     | 2         | 1.6%    |
| Mini pc    | 2         | 1.6%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 121       | 96.8%   |
| Enabled  | 4         | 3.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 124       | 99.2%   |
| Yes  | 1         | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 41        | 32.8%   |
| 1.01-2.0   | 26        | 20.8%   |
| 4.01-8.0   | 20        | 16%     |
| 16.01-24.0 | 14        | 11.2%   |
| 8.01-16.0  | 11        | 8.8%    |
| 32.01-64.0 | 5         | 4%      |
| 0.51-1.0   | 4         | 3.2%    |
| 2.01-3.0   | 3         | 2.4%    |
| 24.01-32.0 | 1         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 62        | 48.44%  |
| 2.01-3.0  | 25        | 19.53%  |
| 0.51-1.0  | 20        | 15.63%  |
| 3.01-4.0  | 9         | 7.03%   |
| 4.01-8.0  | 7         | 5.47%   |
| 0.01-0.5  | 3         | 2.34%   |
| 8.01-16.0 | 2         | 1.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 87        | 69.6%   |
| 2      | 27        | 21.6%   |
| 3      | 7         | 5.6%    |
| 0      | 2         | 1.6%    |
| 5      | 1         | 0.8%    |
| 4      | 1         | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 56.8%   |
| Yes       | 54        | 43.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 88%     |
| No        | 15        | 12%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 80.8%   |
| No        | 24        | 19.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 51.2%   |
| Yes       | 61        | 48.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 21        | 16.8%   |
| Brazil      | 12        | 9.6%    |
| Germany     | 9         | 7.2%    |
| France      | 7         | 5.6%    |
| UK          | 6         | 4.8%    |
| Romania     | 6         | 4.8%    |
| Poland      | 6         | 4.8%    |
| Ukraine     | 5         | 4%      |
| Mexico      | 5         | 4%      |
| Canada      | 5         | 4%      |
| Italy       | 4         | 3.2%    |
| Turkey      | 3         | 2.4%    |
| Spain       | 3         | 2.4%    |
| Russia      | 3         | 2.4%    |
| Peru        | 3         | 2.4%    |
| Australia   | 3         | 2.4%    |
| Netherlands | 2         | 1.6%    |
| Chile       | 2         | 1.6%    |
| Venezuela   | 1         | 0.8%    |
| Thailand    | 1         | 0.8%    |
| Slovakia    | 1         | 0.8%    |
| Serbia      | 1         | 0.8%    |
| Qatar       | 1         | 0.8%    |
| Portugal    | 1         | 0.8%    |
| Philippines | 1         | 0.8%    |
| New Zealand | 1         | 0.8%    |
| Myanmar     | 1         | 0.8%    |
| Malaysia    | 1         | 0.8%    |
| Japan       | 1         | 0.8%    |
| Ireland     | 1         | 0.8%    |
| Iran        | 1         | 0.8%    |
| Indonesia   | 1         | 0.8%    |
| Hungary     | 1         | 0.8%    |
| Guadeloupe  | 1         | 0.8%    |
| Greenland   | 1         | 0.8%    |
| El Salvador | 1         | 0.8%    |
| Czechia     | 1         | 0.8%    |
| Colombia    | 1         | 0.8%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Pabianice          | 3         | 2.34%   |
| Würzburg          | 2         | 1.56%   |
| Warsaw             | 2         | 1.56%   |
| Sydney             | 2         | 1.56%   |
| Sao Paulo          | 2         | 1.56%   |
| Ottawa             | 2         | 1.56%   |
| Odessa             | 2         | 1.56%   |
| Mexico City        | 2         | 1.56%   |
| Lima               | 2         | 1.56%   |
| Kyiv               | 2         | 1.56%   |
| Frankfurt am Main  | 2         | 1.56%   |
| Żywiec            | 1         | 0.78%   |
| Yangon             | 1         | 0.78%   |
| Wiesbaden          | 1         | 0.78%   |
| Wellington         | 1         | 0.78%   |
| Waterbury          | 1         | 0.78%   |
| Washington         | 1         | 0.78%   |
| Wahroonga          | 1         | 0.78%   |
| Voluntari          | 1         | 0.78%   |
| Vinnytsia          | 1         | 0.78%   |
| Varennes-les-Narcy | 1         | 0.78%   |
| Vancouver          | 1         | 0.78%   |
| Valencia           | 1         | 0.78%   |
| Tucape             | 1         | 0.78%   |
| Trujillo           | 1         | 0.78%   |
| Thetford-Mines     | 1         | 0.78%   |
| Teresina           | 1         | 0.78%   |
| Tekirdağ          | 1         | 0.78%   |
| Tarragona          | 1         | 0.78%   |
| Svidník           | 1         | 0.78%   |
| Surabaya           | 1         | 0.78%   |
| Subotica           | 1         | 0.78%   |
| Studenka           | 1         | 0.78%   |
| St. Petersburg     | 1         | 0.78%   |
| Shadrinsk          | 1         | 0.78%   |
| Salerno            | 1         | 0.78%   |
| Sabadell           | 1         | 0.78%   |
| Roswell            | 1         | 0.78%   |
| Rio de Janeiro     | 1         | 0.78%   |
| Queretaro          | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 35     | 19.48%  |
| WDC                 | 26        | 35     | 16.88%  |
| Samsung Electronics | 19        | 20     | 12.34%  |
| Toshiba             | 12        | 13     | 7.79%   |
| Unknown             | 10        | 14     | 6.49%   |
| Kingston            | 8         | 10     | 5.19%   |
| SanDisk             | 6         | 6      | 3.9%    |
| Hitachi             | 5         | 5      | 3.25%   |
| Micron Technology   | 4         | 5      | 2.6%    |
| HGST                | 4         | 4      | 2.6%    |
| Crucial             | 4         | 4      | 2.6%    |
| Goodram             | 3         | 3      | 1.95%   |
| SK hynix            | 2         | 3      | 1.3%    |
| Apple               | 2         | 2      | 1.3%    |
| A-DATA Technology   | 2         | 2      | 1.3%    |
| PNY                 | 1         | 1      | 0.65%   |
| Phison              | 1         | 1      | 0.65%   |
| OCZ                 | 1         | 1      | 0.65%   |
| Maxtor              | 1         | 1      | 0.65%   |
| Mass                | 1         | 1      | 0.65%   |
| LITEON              | 1         | 1      | 0.65%   |
| Intenso             | 1         | 1      | 0.65%   |
| Intel               | 1         | 1      | 0.65%   |
| HPE                 | 1         | 1      | 0.65%   |
| Hewlett-Packard     | 1         | 1      | 0.65%   |
| Gigabyte Technology | 1         | 1      | 0.65%   |
| Fanxiang            | 1         | 2      | 0.65%   |
| China               | 1         | 1      | 0.65%   |
| ASUS-PHISON         | 1         | 2      | 0.65%   |
| ASMT                | 1         | 1      | 0.65%   |
| Apacer              | 1         | 1      | 0.65%   |
| Unknown             | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 4         | 2.41%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.81%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 1.81%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.81%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 1.2%    |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 1.2%    |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 1.2%    |
| Seagate ST9320325AS 320GB            | 2         | 1.2%    |
| Seagate ST3500418AS 500GB            | 2         | 1.2%    |
| Micron MTFDDAK256MAM-1K12 256GB SSD  | 2         | 1.2%    |
| HGST HTS725050A7E630 500GB           | 2         | 1.2%    |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.6%    |
| WDC WDS250G2B0A 250GB SSD            | 1         | 0.6%    |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.6%    |
| WDC WD800JD-60LSA0 80GB              | 1         | 0.6%    |
| WDC WD5000LPCX-75VHAT0 500GB         | 1         | 0.6%    |
| WDC WD5000AAKX-003CA0 500GB          | 1         | 0.6%    |
| WDC WD5000AAKS-60WWPA0 500GB         | 1         | 0.6%    |
| WDC WD5000AADS-56S9B0 500GB          | 1         | 0.6%    |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 0.6%    |
| WDC WD5000AACS-00G8B1 500GB          | 1         | 0.6%    |
| WDC WD2500BEVS-00UST0 250GB          | 1         | 0.6%    |
| WDC WD2500BEVE-00A0HT0 250GB         | 1         | 0.6%    |
| WDC WD20PURX-64PFUY0 2TB             | 1         | 0.6%    |
| WDC WD2005FBYZ-01YCBB2 2TB           | 1         | 0.6%    |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.6%    |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.6%    |
| WDC WD10EZEX-07WN4A0 1TB             | 1         | 0.6%    |
| WDC WD10EADS-00L5B1 1TB              | 1         | 0.6%    |
| WDC WD1003FBYX-01Y7B1 1TB            | 1         | 0.6%    |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB   | 1         | 0.6%    |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.6%    |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.6%    |
| Unknown SN64G  64GB                  | 1         | 0.6%    |
| Unknown SLD64G  64GB                 | 1         | 0.6%    |
| Unknown SD64G  64GB                  | 1         | 0.6%    |
| Unknown SD16G  16GB                  | 1         | 0.6%    |
| Unknown SC64G  64GB                  | 1         | 0.6%    |
| Unknown NCard  32GB                  | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 35     | 38.96%  |
| WDC                 | 19        | 24     | 24.68%  |
| Toshiba             | 12        | 13     | 15.58%  |
| Hitachi             | 5         | 5      | 6.49%   |
| HGST                | 4         | 4      | 5.19%   |
| Samsung Electronics | 3         | 4      | 3.9%    |
| Maxtor              | 1         | 1      | 1.3%    |
| HPE                 | 1         | 1      | 1.3%    |
| ASMT                | 1         | 1      | 1.3%    |
| Apple               | 1         | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 18%     |
| Kingston            | 7         | 9      | 14%     |
| WDC                 | 5         | 6      | 10%     |
| SanDisk             | 5         | 5      | 10%     |
| Crucial             | 4         | 4      | 8%      |
| Micron Technology   | 3         | 4      | 6%      |
| GOODRAM             | 3         | 3      | 6%      |
| A-DATA Technology   | 2         | 2      | 4%      |
| SK hynix            | 1         | 2      | 2%      |
| PNY                 | 1         | 1      | 2%      |
| OCZ                 | 1         | 1      | 2%      |
| LITEON              | 1         | 1      | 2%      |
| Intel               | 1         | 1      | 2%      |
| Hewlett-Packard     | 1         | 1      | 2%      |
| Gigabyte Technology | 1         | 1      | 2%      |
| Fanxiang            | 1         | 2      | 2%      |
| China               | 1         | 1      | 2%      |
| ASUS-PHISON         | 1         | 2      | 2%      |
| Apple               | 1         | 1      | 2%      |
| Apacer              | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 69        | 89     | 47.92%  |
| SSD     | 48        | 57     | 33.33%  |
| MMC     | 13        | 17     | 9.03%   |
| NVMe    | 12        | 15     | 8.33%   |
| Unknown | 2         | 2      | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 103       | 143    | 77.44%  |
| MMC  | 13        | 17     | 9.77%   |
| NVMe | 12        | 15     | 9.02%   |
| SAS  | 5         | 5      | 3.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 85        | 112    | 72.65%  |
| 0.51-1.0   | 27        | 28     | 23.08%  |
| 1.01-2.0   | 4         | 5      | 3.42%   |
| 3.01-4.0   | 1         | 1      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 42        | 33.07%  |
| 251-500        | 27        | 21.26%  |
| 51-100         | 20        | 15.75%  |
| 21-50          | 10        | 7.87%   |
| 1-20           | 10        | 7.87%   |
| 501-1000       | 10        | 7.87%   |
| More than 3000 | 5         | 3.94%   |
| 1001-2000      | 3         | 2.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 63        | 49.22%  |
| 21-50     | 28        | 21.88%  |
| 51-100    | 17        | 13.28%  |
| 101-250   | 11        | 8.59%   |
| 251-500   | 3         | 2.34%   |
| 2001-3000 | 2         | 1.56%   |
| 1001-2000 | 2         | 1.56%   |
| 501-1000  | 2         | 1.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 4.17%   |
| WDC WD800JD-60LSA0 80GB                        | 1         | 1      | 4.17%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 4.17%   |
| WDC WD5000AAKS-60WWPA0 500GB                   | 1         | 1      | 4.17%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 4.17%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 4.17%   |
| Toshiba MK3265GSX 320GB                        | 1         | 1      | 4.17%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 4.17%   |
| Seagate ST980811AS 80GB                        | 1         | 1      | 4.17%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 4.17%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 4.17%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 4.17%   |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 4.17%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 4.17%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 4.17%   |
| SanDisk SSD PLUS 120GB                         | 1         | 1      | 4.17%   |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 4.17%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 4.17%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 4.17%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 4.17%   |
| Hitachi HDS721616PLA380 160GB                  | 1         | 1      | 4.17%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 4.17%   |
| Apacer 16GB SATA Flash Drive SSD               | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 29.17%  |
| WDC                 | 6         | 6      | 25%     |
| Toshiba             | 3         | 3      | 12.5%   |
| Hitachi             | 3         | 3      | 12.5%   |
| SanDisk             | 1         | 1      | 4.17%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| HGST                | 1         | 1      | 4.17%   |
| Apacer              | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 35%     |
| WDC                 | 5         | 5      | 25%     |
| Toshiba             | 3         | 3      | 15%     |
| Hitachi             | 3         | 3      | 15%     |
| Samsung Electronics | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 20     | 81.82%  |
| SSD  | 4         | 4      | 18.18%  |

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
| Works    | 55        | 71     | 42.31%  |
| Detected | 54        | 85     | 41.54%  |
| Malfunc  | 21        | 24     | 16.15%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 86        | 65.65%  |
| AMD                         | 21        | 16.03%  |
| Samsung Electronics         | 7         | 5.34%   |
| Nvidia                      | 6         | 4.58%   |
| SanDisk                     | 3         | 2.29%   |
| Marvell Technology Group    | 2         | 1.53%   |
| Phison Electronics          | 1         | 0.76%   |
| Micron Technology           | 1         | 0.76%   |
| LSI Logic / Symbios Logic   | 1         | 0.76%   |
| Kingston Technology Company | 1         | 0.76%   |
| JMicron Technology          | 1         | 0.76%   |
| Broadcom / LSI              | 1         | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13        | 7.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 4.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 4.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7         | 4.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 2.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 2.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 1.76%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 1.76%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 1.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.76%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3         | 1.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 1.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.18%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.18%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 2         | 1.18%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2         | 1.18%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.18%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.18%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 1.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 1.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.18%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 85        | 58.62%  |
| IDE  | 41        | 28.28%  |
| NVMe | 12        | 8.28%   |
| RAID | 6         | 4.14%   |
| SCSI | 1         | 0.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 100       | 80%     |
| AMD    | 25        | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 4         | 3.2%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3         | 2.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.6%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 1.6%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 1.6%    |
| Intel Core 2 CPU T7600 @ 2.33GHz            | 2         | 1.6%    |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.6%    |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 1.6%    |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.6%    |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.8%    |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 0.8%    |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1         | 0.8%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.8%    |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.8%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 0.8%    |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.8%    |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.8%    |
| Intel Pentium D CPU 3.40GHz                 | 1         | 0.8%    |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.8%    |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.8%    |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.8%    |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1         | 0.8%    |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.8%    |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.8%    |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 0.8%    |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 0.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.8%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.8%    |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.8%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 0.8%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 0.8%    |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 0.8%    |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1         | 0.8%    |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.8%    |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.8%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1         | 0.8%    |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 16        | 12.8%   |
| Intel Core 2 Duo        | 14        | 11.2%   |
| Intel Celeron           | 11        | 8.8%    |
| Intel Core i7           | 10        | 8%      |
| Intel Core i3           | 10        | 8%      |
| Intel Atom              | 10        | 8%      |
| Intel Pentium Dual-Core | 6         | 4.8%    |
| Other                   | 5         | 4%      |
| Intel Pentium           | 5         | 4%      |
| Intel Xeon              | 3         | 2.4%    |
| Intel Core 2            | 3         | 2.4%    |
| Intel Pentium Dual      | 2         | 1.6%    |
| Intel Genuine           | 2         | 1.6%    |
| AMD Turion 64 X2 Mobile | 2         | 1.6%    |
| AMD Ryzen 5             | 2         | 1.6%    |
| AMD E2                  | 2         | 1.6%    |
| AMD E                   | 2         | 1.6%    |
| AMD Athlon II X2        | 2         | 1.6%    |
| AMD A8                  | 2         | 1.6%    |
| AMD A6                  | 2         | 1.6%    |
| Intel Pentium D         | 1         | 0.8%    |
| Intel Core m7           | 1         | 0.8%    |
| Intel Core 2 Extreme    | 1         | 0.8%    |
| Intel Celeron M         | 1         | 0.8%    |
| AMD Turion Dual-Core    | 1         | 0.8%    |
| AMD Sempron             | 1         | 0.8%    |
| AMD Ryzen 9             | 1         | 0.8%    |
| AMD Ryzen 3             | 1         | 0.8%    |
| AMD Quad-Core           | 1         | 0.8%    |
| AMD Phenom II X2        | 1         | 0.8%    |
| AMD FX                  | 1         | 0.8%    |
| AMD Athlon II Neo       | 1         | 0.8%    |
| AMD A12                 | 1         | 0.8%    |
| AMD A10                 | 1         | 0.8%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 72        | 57.6%   |
| 4      | 36        | 28.8%   |
| 1      | 7         | 5.6%    |
| 6      | 6         | 4.8%    |
| 14     | 1         | 0.8%    |
| 12     | 1         | 0.8%    |
| 10     | 1         | 0.8%    |
| 8      | 1         | 0.8%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 124       | 99.2%   |
| 2      | 1         | 0.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 79        | 63.2%   |
| 2      | 46        | 36.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 123       | 98.4%   |
| 32-bit         | 2         | 1.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 12.7%   |
| 0x1067a    | 14        | 11.11%  |
| 0x206a7    | 11        | 8.73%   |
| 0x30678    | 7         | 5.56%   |
| 0x406c4    | 5         | 3.97%   |
| 0x6fd      | 4         | 3.17%   |
| 0x20655    | 4         | 3.17%   |
| 0x10676    | 4         | 3.17%   |
| 0x010000c8 | 4         | 3.17%   |
| 0x6fb      | 3         | 2.38%   |
| 0x40651    | 3         | 2.38%   |
| 0x306a9    | 3         | 2.38%   |
| 0x806ea    | 2         | 1.59%   |
| 0x806e9    | 2         | 1.59%   |
| 0x806c1    | 2         | 1.59%   |
| 0x6f6      | 2         | 1.59%   |
| 0x506c9    | 2         | 1.59%   |
| 0x406c3    | 2         | 1.59%   |
| 0x306c3    | 2         | 1.59%   |
| 0x206c2    | 2         | 1.59%   |
| 0x106ca    | 2         | 1.59%   |
| 0x05000119 | 2         | 1.59%   |
| 0xf64      | 1         | 0.79%   |
| 0xa0653    | 1         | 0.79%   |
| 0x906eb    | 1         | 0.79%   |
| 0x906ea    | 1         | 0.79%   |
| 0x906e9    | 1         | 0.79%   |
| 0x906a4    | 1         | 0.79%   |
| 0x906a3    | 1         | 0.79%   |
| 0x806ec    | 1         | 0.79%   |
| 0x806eb    | 1         | 0.79%   |
| 0x706a1    | 1         | 0.79%   |
| 0x6fa      | 1         | 0.79%   |
| 0x6d8      | 1         | 0.79%   |
| 0x506e3    | 1         | 0.79%   |
| 0x406e3    | 1         | 0.79%   |
| 0x30661    | 1         | 0.79%   |
| 0x0a50000d | 1         | 0.79%   |
| 0x08701013 | 1         | 0.79%   |
| 0x0810100b | 1         | 0.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 19        | 15.2%   |
| Silvermont       | 15        | 12%     |
| Core             | 12        | 9.6%    |
| SandyBridge      | 11        | 8.8%    |
| KabyLake         | 10        | 8%      |
| Westmere         | 6         | 4.8%    |
| K10              | 5         | 4%      |
| IvyBridge        | 5         | 4%      |
| Haswell          | 5         | 4%      |
| Excavator        | 3         | 2.4%    |
| Bonnell          | 3         | 2.4%    |
| Bobcat           | 3         | 2.4%    |
| TigerLake        | 2         | 1.6%    |
| Skylake          | 2         | 1.6%    |
| Puma             | 2         | 1.6%    |
| Piledriver       | 2         | 1.6%    |
| P6               | 2         | 1.6%    |
| K8 Hammer        | 2         | 1.6%    |
| K10 Llano        | 2         | 1.6%    |
| Goldmont         | 2         | 1.6%    |
| Alderlake Hybrid | 2         | 1.6%    |
| Zen+             | 1         | 0.8%    |
| Zen 3            | 1         | 0.8%    |
| Zen 2            | 1         | 0.8%    |
| Zen              | 1         | 0.8%    |
| NetBurst         | 1         | 0.8%    |
| Nehalem          | 1         | 0.8%    |
| K8 & K10 hybrid  | 1         | 0.8%    |
| Jaguar           | 1         | 0.8%    |
| Goldmont plus    | 1         | 0.8%    |
| CometLake        | 1         | 0.8%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 74        | 54.81%  |
| Nvidia | 32        | 23.7%   |
| AMD    | 29        | 21.48%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 5.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 4.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 3.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 3.47%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 3.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 3.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 3.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.08%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 2.08%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.39%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.39%   |
| Intel HD Graphics 620                                                                    | 2         | 1.39%   |
| Intel HD Graphics 500                                                                    | 2         | 1.39%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.39%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.39%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 1.39%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.39%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.69%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.69%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 0.69%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.69%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.69%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.69%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.69%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.69%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 0.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.69%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 0.69%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 0.69%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 0.69%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.69%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1         | 0.69%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 64        | 51.2%   |
| 1 x AMD        | 25        | 20%     |
| 1 x Nvidia     | 23        | 18.4%   |
| Intel + Nvidia | 9         | 7.2%    |
| 2 x AMD        | 3         | 2.4%    |
| Intel + AMD    | 1         | 0.8%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 107       | 84.92%  |
| Proprietary | 16        | 12.7%   |
| Unknown     | 3         | 2.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 60%     |
| 0.01-0.5   | 27        | 21.6%   |
| 0.51-1.0   | 8         | 6.4%    |
| 1.01-2.0   | 7         | 5.6%    |
| 3.01-4.0   | 5         | 4%      |
| 5.01-6.0   | 3         | 2.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 20        | 16%     |
| AU Optronics            | 14        | 11.2%   |
| LG Display              | 10        | 8%      |
| Hewlett-Packard         | 9         | 7.2%    |
| Chimei Innolux          | 9         | 7.2%    |
| Chi Mei Optoelectronics | 8         | 6.4%    |
| Goldstar                | 7         | 5.6%    |
| BOE                     | 7         | 5.6%    |
| Acer                    | 5         | 4%      |
| Sony                    | 3         | 2.4%    |
| NEC Computers           | 3         | 2.4%    |
| Apple                   | 3         | 2.4%    |
| Ancor Communications    | 3         | 2.4%    |
| ViewSonic               | 2         | 1.6%    |
| LG Philips              | 2         | 1.6%    |
| HannStar                | 2         | 1.6%    |
| CPT                     | 2         | 1.6%    |
| Unknown                 | 2         | 1.6%    |
| Toshiba                 | 1         | 0.8%    |
| Seiko/Epson             | 1         | 0.8%    |
| SANYO                   | 1         | 0.8%    |
| Philips                 | 1         | 0.8%    |
| PANDA                   | 1         | 0.8%    |
| OEM                     | 1         | 0.8%    |
| MSI                     | 1         | 0.8%    |
| Lenovo                  | 1         | 0.8%    |
| InfoVision              | 1         | 0.8%    |
| Hitachi                 | 1         | 0.8%    |
| eMachines               | 1         | 0.8%    |
| BenQ                    | 1         | 0.8%    |
| Belinea                 | 1         | 0.8%    |
| AOC                     | 1         | 0.8%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 2         | 1.54%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.54%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.54%   |
| Unknown                                                               | 2         | 1.54%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1         | 0.77%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1         | 0.77%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1         | 0.77%   |
| Toshiba L705A LCD705A 1280x1024 340x270mm 17.1-inch                   | 1         | 0.77%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.77%   |
| Sony TV SNYDC01 1360x768                                              | 1         | 0.77%   |
| Sony TV *00 SNY8004 3840x2160 1439x809mm 65.0-inch                    | 1         | 0.77%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.77%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.77%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1         | 0.77%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 0.77%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch  | 1         | 0.77%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 0.77%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1         | 0.77%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.77%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.77%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1         | 0.77%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3155 1366x768 293x165mm 13.2-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch | 1         | 0.77%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 0.77%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                    | 1         | 0.77%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 0.77%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 1         | 0.77%   |
| NEC Computers LCD1990SXi NEC66AC 1280x1024 376x301mm 19.0-inch        | 1         | 0.77%   |
| NEC Computers EA244WMi NEC68D7 1920x1200 519x324mm 24.1-inch          | 1         | 0.77%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 36        | 28.8%   |
| 1920x1080 (FHD)    | 32        | 25.6%   |
| 1920x1200 (WUXGA)  | 10        | 8%      |
| 1280x800 (WXGA)    | 9         | 7.2%    |
| 3840x2160 (4K)     | 6         | 4.8%    |
| 1280x1024 (SXGA)   | 6         | 4.8%    |
| 1680x1050 (WSXGA+) | 4         | 3.2%    |
| 1600x900 (HD+)     | 4         | 3.2%    |
| 1440x900 (WXGA+)   | 4         | 3.2%    |
| 1360x768           | 3         | 2.4%    |
| 2560x1440 (QHD)    | 2         | 1.6%    |
| 1024x600           | 2         | 1.6%    |
| Unknown            | 2         | 1.6%    |
| 5280x1080          | 1         | 0.8%    |
| 3840x2400          | 1         | 0.8%    |
| 1920x540           | 1         | 0.8%    |
| 1280x720 (HD)      | 1         | 0.8%    |
| 1024x768 (XGA)     | 1         | 0.8%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 20.63%  |
| 17      | 13        | 10.32%  |
| 14      | 10        | 7.94%   |
| 13      | 10        | 7.94%   |
| 24      | 8         | 6.35%   |
| 21      | 8         | 6.35%   |
| Unknown | 8         | 6.35%   |
| 23      | 6         | 4.76%   |
| 19      | 5         | 3.97%   |
| 18      | 5         | 3.97%   |
| 11      | 5         | 3.97%   |
| 27      | 4         | 3.17%   |
| 20      | 3         | 2.38%   |
| 16      | 3         | 2.38%   |
| 12      | 3         | 2.38%   |
| 10      | 3         | 2.38%   |
| 72      | 2         | 1.59%   |
| 65      | 1         | 0.79%   |
| 46      | 1         | 0.79%   |
| 28      | 1         | 0.79%   |
| 22      | 1         | 0.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 38.71%  |
| 401-500     | 19        | 15.32%  |
| 501-600     | 18        | 14.52%  |
| 201-300     | 14        | 11.29%  |
| 351-400     | 12        | 9.68%   |
| Unknown     | 8         | 6.45%   |
| 1501-2000   | 2         | 1.61%   |
| 1001-1500   | 2         | 1.61%   |
| 601-700     | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 79        | 66.39%  |
| 16/10   | 25        | 21.01%  |
| 5/4     | 6         | 5.04%   |
| Unknown | 6         | 5.04%   |
| 6/5     | 1         | 0.84%   |
| 4/3     | 1         | 0.84%   |
| 3/2     | 1         | 0.84%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 20.63%  |
| 81-90          | 17        | 13.49%  |
| 201-250        | 16        | 12.7%   |
| 151-200        | 11        | 8.73%   |
| 141-150        | 8         | 6.35%   |
| Unknown        | 8         | 6.35%   |
| 121-130        | 6         | 4.76%   |
| 51-60          | 5         | 3.97%   |
| 251-300        | 5         | 3.97%   |
| 131-140        | 5         | 3.97%   |
| 301-350        | 4         | 3.17%   |
| More than 1000 | 3         | 2.38%   |
| 71-80          | 3         | 2.38%   |
| 61-70          | 3         | 2.38%   |
| 41-50          | 3         | 2.38%   |
| 351-500        | 1         | 0.79%   |
| 111-120        | 1         | 0.79%   |
| 501-1000       | 1         | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 42        | 34.43%  |
| 101-120       | 37        | 30.33%  |
| 121-160       | 27        | 22.13%  |
| Unknown       | 8         | 6.56%   |
| 1-50          | 3         | 2.46%   |
| 161-240       | 3         | 2.46%   |
| More than 240 | 2         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 111       | 88.1%   |
| 2     | 13        | 10.32%  |
| 3     | 1         | 0.79%   |
| 0     | 1         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 66        | 34.2%   |
| Intel                                 | 43        | 22.28%  |
| Qualcomm Atheros                      | 28        | 14.51%  |
| Broadcom                              | 18        | 9.33%   |
| Ralink Technology                     | 5         | 2.59%   |
| Ralink                                | 5         | 2.59%   |
| Broadcom Limited                      | 5         | 2.59%   |
| Nvidia                                | 4         | 2.07%   |
| Sierra Wireless                       | 2         | 1.04%   |
| Marvell Technology Group              | 2         | 1.04%   |
| ASUSTek Computer                      | 2         | 1.04%   |
| ASIX Electronics                      | 2         | 1.04%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.52%   |
| TP-Link                               | 1         | 0.52%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.52%   |
| Samsung Electronics                   | 1         | 0.52%   |
| Qualcomm Atheros Communications       | 1         | 0.52%   |
| Microsoft                             | 1         | 0.52%   |
| MediaTek                              | 1         | 0.52%   |
| Linksys                               | 1         | 0.52%   |
| D-Link                                | 1         | 0.52%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.52%   |
| 3Com                                  | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 42        | 18.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 16        | 7.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 6         | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 2.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 5         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 5         | 2.22%   |
| Ralink MT7601U Wireless Adapter                                            | 4         | 1.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 4         | 1.78%   |
| Intel Wireless 3165                                                        | 4         | 1.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection              | 4         | 1.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 4         | 1.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 3         | 1.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 3         | 1.33%   |
| Realtek 802.11ac WLAN Adapter                                              | 2         | 0.89%   |
| Nvidia MCP77 Ethernet                                                      | 2         | 0.89%   |
| Intel Wireless 8265 / 8275                                                 | 2         | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                           | 2         | 0.89%   |
| Intel 82567LM Gigabit Network Connection                                   | 2         | 0.89%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 2         | 0.89%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2         | 0.89%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                     | 2         | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 2         | 0.89%   |
| Broadcom BCM4311 802.11b/g WLAN                                            | 2         | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                              | 2         | 0.89%   |
| ZTE WCDMA MSM ZTE BLADE A530                                               | 1         | 0.44%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                    | 1         | 0.44%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.44%   |
| Sierra Wireless EM7455                                                     | 1         | 0.44%   |
| Sierra Wireless EM7305 Modem                                               | 1         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1         | 0.44%   |
| Realtek USB 10/100 LAN                                                     | 1         | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1         | 0.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.44%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                    | 1         | 0.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.44%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 0.44%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                | 1         | 0.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 1         | 0.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 30        | 28.3%   |
| Qualcomm Atheros                      | 25        | 23.58%  |
| Realtek Semiconductor                 | 20        | 18.87%  |
| Broadcom                              | 7         | 6.6%    |
| Ralink Technology                     | 5         | 4.72%   |
| Ralink                                | 5         | 4.72%   |
| Broadcom Limited                      | 3         | 2.83%   |
| Sierra Wireless                       | 2         | 1.89%   |
| ASUSTek Computer                      | 2         | 1.89%   |
| TP-Link                               | 1         | 0.94%   |
| Qualcomm Atheros Communications       | 1         | 0.94%   |
| Microsoft                             | 1         | 0.94%   |
| MediaTek                              | 1         | 0.94%   |
| Linksys                               | 1         | 0.94%   |
| D-Link                                | 1         | 0.94%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 5.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 4.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 4.67%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 3.74%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 3.74%   |
| Intel Wireless 3165                                            | 4         | 3.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 4         | 3.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 3.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.8%    |
| Realtek 802.11ac WLAN Adapter                                  | 2         | 1.87%   |
| Intel Wireless 8265 / 8275                                     | 2         | 1.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.87%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 1.87%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                        | 1         | 0.93%   |
| Sierra Wireless EM7455                                         | 1         | 0.93%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.93%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.93%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.93%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.93%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 1         | 0.93%   |
| Realtek 802.11ac NIC                                           | 1         | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.93%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 0.93%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.93%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 62        | 53.45%  |
| Intel                             | 20        | 17.24%  |
| Broadcom                          | 12        | 10.34%  |
| Qualcomm Atheros                  | 8         | 6.9%    |
| Nvidia                            | 4         | 3.45%   |
| Marvell Technology Group          | 2         | 1.72%   |
| Broadcom Limited                  | 2         | 1.72%   |
| ASIX Electronics                  | 2         | 1.72%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.86%   |
| Sundance Technology Inc / IC Plus | 1         | 0.86%   |
| Samsung Electronics               | 1         | 0.86%   |
| 3Com                              | 1         | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 42        | 35.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 16        | 13.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 5.13%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 3         | 2.56%   |
| Nvidia MCP77 Ethernet                                                         | 2         | 1.71%   |
| Intel 82567LM Gigabit Network Connection                                      | 2         | 1.71%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 1.71%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 1.71%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 1.71%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 1.71%   |
| ZTE WCDMA MSM ZTE BLADE A530                                                  | 1         | 0.85%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1         | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.85%   |
| Realtek USB 10/100 LAN                                                        | 1         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.85%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.85%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.85%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.85%   |
| Nvidia MCP51 Ethernet Controller                                              | 1         | 0.85%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.85%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 0.85%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.85%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.85%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1         | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.85%   |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 0.85%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 0.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 0.85%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 110       | 51.89%  |
| WiFi     | 101       | 47.64%  |
| Unknown  | 1         | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 59.54%  |
| Ethernet | 53        | 40.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 74        | 59.2%   |
| 1     | 44        | 35.2%   |
| 0     | 4         | 3.2%    |
| 3     | 2         | 1.6%    |
| 4     | 1         | 0.8%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 100       | 79.37%  |
| Yes  | 26        | 20.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 29.51%  |
| Realtek Semiconductor           | 9         | 14.75%  |
| Hewlett-Packard                 | 5         | 8.2%    |
| Lite-On Technology              | 4         | 6.56%   |
| IMC Networks                    | 4         | 6.56%   |
| Cambridge Silicon Radio         | 4         | 6.56%   |
| Broadcom                        | 4         | 6.56%   |
| Qualcomm Atheros Communications | 3         | 4.92%   |
| Apple                           | 3         | 4.92%   |
| Dell                            | 2         | 3.28%   |
| Toshiba                         | 1         | 1.64%   |
| Ralink                          | 1         | 1.64%   |
| Foxconn / Hon Hai               | 1         | 1.64%   |
| Chicony Electronics             | 1         | 1.64%   |
| ASUSTek Computer                | 1         | 1.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 14.75%  |
| Realtek Bluetooth Radio                             | 5         | 8.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 6.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.92%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 4.92%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.28%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 3.28%   |
| Intel AX201 Bluetooth                               | 2         | 3.28%   |
| IMC Networks Bluetooth Device                       | 2         | 3.28%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 3.28%   |
| Dell Wireless 355 Bluetooth                         | 2         | 3.28%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 3.28%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.64%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.64%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.64%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.64%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.64%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.64%   |
| Lite-On Bluetooth Device                            | 1         | 1.64%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.64%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.64%   |
| Intel Bluetooth Device                              | 1         | 1.64%   |
| Intel AX200 Bluetooth                               | 1         | 1.64%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.64%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.64%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.64%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 1.64%   |
| Broadcom HP Portable Valentine                      | 1         | 1.64%   |
| Broadcom HP Bluethunder                             | 1         | 1.64%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.64%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.64%   |
| Apple Bluetooth HCI                                 | 1         | 1.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 91        | 61.07%  |
| AMD                   | 29        | 19.46%  |
| Nvidia                | 19        | 12.75%  |
| Logitech              | 2         | 1.34%   |
| C-Media Electronics   | 2         | 1.34%   |
| Texas Instruments     | 1         | 0.67%   |
| Realtek Semiconductor | 1         | 0.67%   |
| JMTek                 | 1         | 0.67%   |
| Ensoniq               | 1         | 0.67%   |
| Creative Labs         | 1         | 0.67%   |
| Blue Microphones      | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 8.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 5.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 4.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 4.65%   |
| AMD FCH Azalia Controller                                                                         | 7         | 4.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 3.49%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 2.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 2.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.91%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5         | 2.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 2.33%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.74%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.74%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.74%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.16%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.16%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.16%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.16%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.16%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.58%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1         | 0.58%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.58%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.58%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 0.58%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.58%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.58%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.58%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 24        | 20.87%  |
| Samsung Electronics | 20        | 17.39%  |
| SK hynix            | 17        | 14.78%  |
| Kingston            | 13        | 11.3%   |
| Micron Technology   | 12        | 10.43%  |
| Unknown             | 5         | 4.35%   |
| Elpida              | 3         | 2.61%   |
| A-DATA Technology   | 3         | 2.61%   |
| Unknown (ABCD)      | 2         | 1.74%   |
| Ramaxel Technology  | 2         | 1.74%   |
| Nanya Technology    | 2         | 1.74%   |
| Corsair             | 2         | 1.74%   |
| Transcend           | 1         | 0.87%   |
| Qumo                | 1         | 0.87%   |
| Qimonda             | 1         | 0.87%   |
| GeIL                | 1         | 0.87%   |
| G.Skill             | 1         | 0.87%   |
| Avant               | 1         | 0.87%   |
| 2C0C1121390963FE    | 1         | 0.87%   |
| 2C0C1121390963FD    | 1         | 0.87%   |
| 2C0C1121390963F9    | 1         | 0.87%   |
| 2C0C1121390963F8    | 1         | 0.87%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 4.2%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.68%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.84%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                          | 1         | 0.84%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.84%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 0.84%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.84%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.84%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.84%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.84%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.84%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.84%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.84%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.84%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.84%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.84%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                       | 1         | 0.84%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1         | 0.84%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                            | 1         | 0.84%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                   | 1         | 0.84%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.84%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                    | 1         | 0.84%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.84%   |
| Unknown RAM Module 1024MB DIMM DDR2                              | 1         | 0.84%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                       | 1         | 0.84%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.84%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 1         | 0.84%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s               | 1         | 0.84%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.84%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.84%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 1         | 0.84%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 1         | 0.84%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 0.84%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 0.84%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.84%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.84%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.84%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 35        | 36.08%  |
| DDR2    | 21        | 21.65%  |
| DDR4    | 18        | 18.56%  |
| SDRAM   | 9         | 9.28%   |
| Unknown | 6         | 6.19%   |
| LPDDR4  | 4         | 4.12%   |
| DDR     | 3         | 3.09%   |
| DRAM    | 1         | 1.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 59        | 62.77%  |
| DIMM    | 34        | 36.17%  |
| FB-DIMM | 1         | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 37        | 35.24%  |
| 4096  | 29        | 27.62%  |
| 8192  | 18        | 17.14%  |
| 1024  | 16        | 15.24%  |
| 16384 | 5         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 26        | 25.74%  |
| 667     | 10        | 9.9%    |
| 3200    | 9         | 8.91%   |
| 2667    | 8         | 7.92%   |
| 1333    | 8         | 7.92%   |
| Unknown | 8         | 7.92%   |
| 800     | 6         | 5.94%   |
| 2400    | 3         | 2.97%   |
| 975     | 3         | 2.97%   |
| 4199    | 2         | 1.98%   |
| 2048    | 2         | 1.98%   |
| 1334    | 2         | 1.98%   |
| 1066    | 2         | 1.98%   |
| 400     | 2         | 1.98%   |
| 49926   | 1         | 0.99%   |
| 19791   | 1         | 0.99%   |
| 3500    | 1         | 0.99%   |
| 3266    | 1         | 0.99%   |
| 2133    | 1         | 0.99%   |
| 1866    | 1         | 0.99%   |
| 1639    | 1         | 0.99%   |
| 1067    | 1         | 0.99%   |
| 1033    | 1         | 0.99%   |
| 133     | 1         | 0.99%   |

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
| Mustek Systems  | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 CU | 1         | 50%     |
| HP ScanJet 5200c                   | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 28.17%  |
| Quanta                                 | 6         | 8.45%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 8.45%   |
| Suyin                                  | 5         | 7.04%   |
| Apple                                  | 5         | 7.04%   |
| Silicon Motion                         | 3         | 4.23%   |
| IMC Networks                           | 3         | 4.23%   |
| Alcor Micro                            | 3         | 4.23%   |
| Z-Star Microelectronics                | 2         | 2.82%   |
| Syntek                                 | 2         | 2.82%   |
| Sunplus Innovation Technology          | 2         | 2.82%   |
| Realtek Semiconductor                  | 2         | 2.82%   |
| Microdia                               | 2         | 2.82%   |
| Ricoh                                  | 1         | 1.41%   |
| OmniVision Technologies                | 1         | 1.41%   |
| Microsoft                              | 1         | 1.41%   |
| Logitech                               | 1         | 1.41%   |
| Lite-On Technology                     | 1         | 1.41%   |
| Jieli Technology                       | 1         | 1.41%   |
| Hopewin Electronic Material            | 1         | 1.41%   |
| Hewlett-Packard                        | 1         | 1.41%   |
| Generalplus Technology                 | 1         | 1.41%   |
| Aveo Technology                        | 1         | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                       | 5         | 7.04%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 2.82%   |
| Quanta HP TrueVision HD Camera                      | 2         | 2.82%   |
| Chicony Integrated Camera                           | 2         | 2.82%   |
| Chicony HP High Definition 1MP Webcam               | 2         | 2.82%   |
| Chicony FJ Camera                                   | 2         | 2.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 2.82%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 2         | 2.82%   |
| Apple Built-in iSight                               | 2         | 2.82%   |
| Z-Star Webcam                                       | 1         | 1.41%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 1.41%   |
| Syntek USB Video Device                             | 1         | 1.41%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.41%   |
| Suyin USB 2.0 Camera                                | 1         | 1.41%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.41%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 1.41%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.41%   |
| Sunplus HD WebCam                                   | 1         | 1.41%   |
| Silicon Motion WebCam SC-10HDD13335N                | 1         | 1.41%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 1.41%   |
| Silicon Motion Web Camera                           | 1         | 1.41%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.41%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.41%   |
| Realtek USB Camera                                  | 1         | 1.41%   |
| Quanta VGA WebCam                                   | 1         | 1.41%   |
| Quanta HP Truevision HD                             | 1         | 1.41%   |
| Quanta HD Webcam                                    | 1         | 1.41%   |
| Quanta ACER HD User Facing                          | 1         | 1.41%   |
| OmniVision OV2640 Webcam                            | 1         | 1.41%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1         | 1.41%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.41%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.41%   |
| Logitech HD Webcam C615                             | 1         | 1.41%   |
| Lite-On Integrated Camera                           | 1         | 1.41%   |
| Jieli USB PHY 2.0                                   | 1         | 1.41%   |
| IMC Networks USB2.0 UVC VGA WebCam                  | 1         | 1.41%   |
| IMC Networks EasyCamera                             | 1         | 1.41%   |
| IMC Networks 2M Integrated Webcam                   | 1         | 1.41%   |
| Hopewin Electronic Material Integrated RGB Camera   | 1         | 1.41%   |
| HP Webcam HD 2300                                   | 1         | 1.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 4         | 44.44%  |
| Validity Sensors      | 2         | 22.22%  |
| Synaptics             | 1         | 11.11%  |
| Samsung Electronics   | 1         | 11.11%  |
| LighTuning Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor             | 2         | 22.22%  |
| Validity Sensors VFS451 Fingerprint Reader       | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                  | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 11.11%  |
| Samsung Fingerprint Device                       | 1         | 11.11%  |
| LighTuning EgisTec Touch Fingerprint Sensor      | 1         | 11.11%  |
| AuthenTec Fingerprint Sensor                     | 1         | 11.11%  |
| AuthenTec AES1600                                | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| O2 Micro Oz776 SmartCard Reader     | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 94        | 74.6%   |
| 1     | 27        | 21.43%  |
| 2     | 5         | 3.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 9         | 24.32%  |
| Fingerprint reader       | 9         | 24.32%  |
| Net/wireless             | 5         | 13.51%  |
| Multimedia controller    | 2         | 5.41%   |
| Chipcard                 | 2         | 5.41%   |
| Bluetooth                | 2         | 5.41%   |
| Unassigned class         | 1         | 2.7%    |
| Storage                  | 1         | 2.7%    |
| Sound                    | 1         | 2.7%    |
| Network                  | 1         | 2.7%    |
| Net/ethernet             | 1         | 2.7%    |
| Dvb card                 | 1         | 2.7%    |
| Communication controller | 1         | 2.7%    |
| Camera                   | 1         | 2.7%    |

