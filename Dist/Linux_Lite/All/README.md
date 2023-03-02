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

Total: 175

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Linux Lite 5.8 | 22        | 17.89%  |
| Linux Lite 6.0 | 19        | 15.45%  |
| Linux Lite 5.2 | 17        | 13.82%  |
| Linux Lite 5.0 | 17        | 13.82%  |
| Linux Lite 5.4 | 16        | 13.01%  |
| Linux Lite 5.6 | 13        | 10.57%  |
| Linux Lite 6.2 | 9         | 7.32%   |
| Linux Lite 3.8 | 5         | 4.07%   |
| Linux Lite 4.8 | 2         | 1.63%   |
| Linux Lite 4.6 | 1         | 0.81%   |
| Linux Lite 4.4 | 1         | 0.81%   |
| Linux Lite 4.2 | 1         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Lite | 121       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 6         | 4.62%   |
| 5.4.0-70-generic  | 5         | 3.85%   |
| 5.4.0-91-generic  | 4         | 3.08%   |
| 5.4.0-52-generic  | 4         | 3.08%   |
| 5.4.0-40-generic  | 4         | 3.08%   |
| 5.4.0-109-generic | 4         | 3.08%   |
| 5.4.0-104-generic | 4         | 3.08%   |
| 5.15.0-33-generic | 4         | 3.08%   |
| 5.4.0-96-generic  | 3         | 2.31%   |
| 5.4.0-58-generic  | 3         | 2.31%   |
| 5.4.0-48-generic  | 3         | 2.31%   |
| 5.4.0-113-generic | 3         | 2.31%   |
| 5.4.0-107-generic | 3         | 2.31%   |
| 5.15.0-58-generic | 3         | 2.31%   |
| 5.15.0-52-generic | 3         | 2.31%   |
| 5.15.0-47-generic | 3         | 2.31%   |
| 5.15.0-46-generic | 3         | 2.31%   |
| 5.4.0-90-generic  | 2         | 1.54%   |
| 5.4.0-88-generic  | 2         | 1.54%   |
| 5.4.0-81-generic  | 2         | 1.54%   |
| 5.4.0-80-generic  | 2         | 1.54%   |
| 5.4.0-74-generic  | 2         | 1.54%   |
| 5.4.0-54-generic  | 2         | 1.54%   |
| 5.4.0-33-generic  | 2         | 1.54%   |
| 5.4.0-110-generic | 2         | 1.54%   |
| 5.4.0-105-generic | 2         | 1.54%   |
| 5.15.0-60-generic | 2         | 1.54%   |
| 5.15.0-56-generic | 2         | 1.54%   |
| 5.15.0-48-generic | 2         | 1.54%   |
| 4.4.0-112-generic | 2         | 1.54%   |
| 6.1.0-1.linuxlite | 1         | 0.77%   |
| 6.0.0-1.linuxlite | 1         | 0.77%   |
| 6.0.0             | 1         | 0.77%   |
| 5.9.0             | 1         | 0.77%   |
| 5.4.0-99-generic  | 1         | 0.77%   |
| 5.4.0-94-generic  | 1         | 0.77%   |
| 5.4.0-77-generic  | 1         | 0.77%   |
| 5.4.0-72-generic  | 1         | 0.77%   |
| 5.4.0-71-generic  | 1         | 0.77%   |
| 5.4.0-66-generic  | 1         | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 79        | 63.2%   |
| 5.15.0  | 26        | 20.8%   |
| 4.15.0  | 5         | 4%      |
| 4.4.0   | 4         | 3.2%    |
| 5.13.0  | 3         | 2.4%    |
| 6.0.0   | 2         | 1.6%    |
| 6.1.0   | 1         | 0.8%    |
| 5.9.0   | 1         | 0.8%    |
| 5.19.0  | 1         | 0.8%    |
| 5.16.9  | 1         | 0.8%    |
| 5.16.0  | 1         | 0.8%    |
| 5.10.0  | 1         | 0.8%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 79        | 63.2%   |
| 5.15    | 26        | 20.8%   |
| 4.15    | 5         | 4%      |
| 4.4     | 4         | 3.2%    |
| 5.13    | 3         | 2.4%    |
| 6.0     | 2         | 1.6%    |
| 5.16    | 2         | 1.6%    |
| 6.1     | 1         | 0.8%    |
| 5.9     | 1         | 0.8%    |
| 5.19    | 1         | 0.8%    |
| 5.10    | 1         | 0.8%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 117       | 96.69%  |
| i686   | 4         | 3.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 93        | 76.86%  |
| GNOME   | 25        | 20.66%  |
| Unknown | 2         | 1.65%   |
| Deepin  | 1         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 119       | 98.35%  |
| Tty     | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 72        | 58.54%  |
| TDM     | 28        | 22.76%  |
| Unknown | 22        | 17.89%  |
| GDM     | 1         | 0.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 60        | 49.59%  |
| pt_BR | 7         | 5.79%   |
| de_DE | 7         | 5.79%   |
| pl_PL | 6         | 4.96%   |
| fr_FR | 6         | 4.96%   |
| en_GB | 6         | 4.96%   |
| es_MX | 4         | 3.31%   |
| ru_UA | 3         | 2.48%   |
| es_ES | 3         | 2.48%   |
| ru_RU | 2         | 1.65%   |
| it_IT | 2         | 1.65%   |
| en_CA | 2         | 1.65%   |
| zh_CN | 1         | 0.83%   |
| tr_TR | 1         | 0.83%   |
| pt_PT | 1         | 0.83%   |
| nl_NL | 1         | 0.83%   |
| hu_HU | 1         | 0.83%   |
| fr_CA | 1         | 0.83%   |
| es_CO | 1         | 0.83%   |
| es_CL | 1         | 0.83%   |
| en_NZ | 1         | 0.83%   |
| en_IE | 1         | 0.83%   |
| en_AU | 1         | 0.83%   |
| da_DK | 1         | 0.83%   |
| C     | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 69        | 57.02%  |
| EFI  | 52        | 42.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 108       | 89.26%  |
| Overlay | 9         | 7.44%   |
| Btrfs   | 2         | 1.65%   |
| Zfs     | 1         | 0.83%   |
| Ext3    | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 49        | 40.5%   |
| Unknown | 38        | 31.4%   |
| MBR     | 34        | 28.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 81.97%  |
| Yes       | 22        | 18.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 71.31%  |
| Yes       | 35        | 28.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 19.83%  |
| ASUSTek Computer    | 18        | 14.88%  |
| Lenovo              | 12        | 9.92%   |
| Acer                | 12        | 9.92%   |
| Dell                | 9         | 7.44%   |
| MSI                 | 5         | 4.13%   |
| Samsung Electronics | 4         | 3.31%   |
| Apple               | 4         | 3.31%   |
| Pegatron            | 3         | 2.48%   |
| Gigabyte Technology | 3         | 2.48%   |
| Fujitsu             | 3         | 2.48%   |
| Minix               | 2         | 1.65%   |
| Intel               | 2         | 1.65%   |
| Foxconn             | 2         | 1.65%   |
| ASRock              | 2         | 1.65%   |
| UMAX                | 1         | 0.83%   |
| TR                  | 1         | 0.83%   |
| Toshiba             | 1         | 0.83%   |
| Thomson             | 1         | 0.83%   |
| Sony                | 1         | 0.83%   |
| Packard Bell        | 1         | 0.83%   |
| Jetway              | 1         | 0.83%   |
| Inventec            | 1         | 0.83%   |
| Insignia            | 1         | 0.83%   |
| Google              | 1         | 0.83%   |
| Gateway             | 1         | 0.83%   |
| EVGA                | 1         | 0.83%   |
| Braview             | 1         | 0.83%   |
| Biostar             | 1         | 0.83%   |
| AWOW                | 1         | 0.83%   |
| ABIT                | 1         | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| MSI MS-7758                            | 2         | 1.65%   |
| UMAX VisionBook 12Wi 64G               | 1         | 0.83%   |
| TR ST Pro-KN                           | 1         | 0.83%   |
| Toshiba Satellite T215D                | 1         | 0.83%   |
| Thomson PT-NEO14A.2WH32                | 1         | 0.83%   |
| Sony VGC-JS54FB_W                      | 1         | 0.83%   |
| Samsung X420/X520                      | 1         | 0.83%   |
| Samsung NC110P/NC108P/NC111P           | 1         | 0.83%   |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 0.83%   |
| Samsung 530XBB                         | 1         | 0.83%   |
| Pegatron H36FF                         | 1         | 0.83%   |
| Pegatron 520-1135la                    | 1         | 0.83%   |
| Pegatron 520-1030a                     | 1         | 0.83%   |
| Packard Bell ISTART D2314              | 1         | 0.83%   |
| MSI MS-N014                            | 1         | 0.83%   |
| MSI MS-7C95                            | 1         | 0.83%   |
| MSI FZ079AA-ABF a6625fr                | 1         | 0.83%   |
| Minix Z83-4                            | 1         | 0.83%   |
| Minix Z64                              | 1         | 0.83%   |
| Lenovo ThinkStation P320 30BH000BFR    | 1         | 0.83%   |
| Lenovo ThinkPad T400 6475E13           | 1         | 0.83%   |
| Lenovo ThinkPad L480 20LS001AMC        | 1         | 0.83%   |
| Lenovo ThinkCentre M91p 4524RS6        | 1         | 0.83%   |
| Lenovo ThinkCentre M91p 4518E2M        | 1         | 0.83%   |
| Lenovo ThinkCentre A55 9265BL7         | 1         | 0.83%   |
| Lenovo MIIX 300-10IBY 80NR             | 1         | 0.83%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1    | 1         | 0.83%   |
| Lenovo IdeaPad 320-15ABR 80XS          | 1         | 0.83%   |
| Lenovo IdeaPad 100-14IBY 80MH          | 1         | 0.83%   |
| Lenovo H505S 10107                     | 1         | 0.83%   |
| Lenovo 3000 V200 0764A11               | 1         | 0.83%   |
| Jetway I61MG4                          | 1         | 0.83%   |
| Inventec Dell Thin Client Desktop 3290 | 1         | 0.83%   |
| Intel H61M-S1                          | 1         | 0.83%   |
| Intel DG31PR AAD97573-300              | 1         | 0.83%   |
| Insignia NS-P11W7100                   | 1         | 0.83%   |
| HP xw8600 Workstation                  | 1         | 0.83%   |
| HP x2 Detachable 10-p0XX               | 1         | 0.83%   |
| HP t5000 series                        | 1         | 0.83%   |
| HP Stream Notebook PC 13               | 1         | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HP Compaq               | 8         | 6.61%   |
| Acer Aspire             | 7         | 5.79%   |
| Dell Inspiron           | 4         | 3.31%   |
| Lenovo ThinkCentre      | 3         | 2.48%   |
| Lenovo IdeaPad          | 3         | 2.48%   |
| HP Laptop               | 3         | 2.48%   |
| MSI MS-7758             | 2         | 1.65%   |
| Lenovo ThinkPad         | 2         | 1.65%   |
| HP Pavilion             | 2         | 1.65%   |
| HP EliteBook            | 2         | 1.65%   |
| ASUS VivoBook           | 2         | 1.65%   |
| UMAX VisionBook         | 1         | 0.83%   |
| TR ST                   | 1         | 0.83%   |
| Toshiba Satellite       | 1         | 0.83%   |
| Thomson PT-NEO14A.2WH32 | 1         | 0.83%   |
| Sony VGC-JS54FB         | 1         | 0.83%   |
| Samsung X420            | 1         | 0.83%   |
| Samsung NC110P          | 1         | 0.83%   |
| Samsung 905S3G          | 1         | 0.83%   |
| Samsung 530XBB          | 1         | 0.83%   |
| Pegatron H36FF          | 1         | 0.83%   |
| Pegatron 520-1135la     | 1         | 0.83%   |
| Pegatron 520-1030a      | 1         | 0.83%   |
| Packard Bell ISTART     | 1         | 0.83%   |
| MSI MS-N014             | 1         | 0.83%   |
| MSI MS-7C95             | 1         | 0.83%   |
| MSI FZ079AA-ABF         | 1         | 0.83%   |
| Minix Z83-4             | 1         | 0.83%   |
| Minix Z64               | 1         | 0.83%   |
| Lenovo ThinkStation     | 1         | 0.83%   |
| Lenovo MIIX             | 1         | 0.83%   |
| Lenovo H505S            | 1         | 0.83%   |
| Lenovo 3000             | 1         | 0.83%   |
| Jetway I61MG4           | 1         | 0.83%   |
| Inventec Dell           | 1         | 0.83%   |
| Intel H61M-S1           | 1         | 0.83%   |
| Intel DG31PR            | 1         | 0.83%   |
| Insignia NS-P11W7100    | 1         | 0.83%   |
| HP xw8600               | 1         | 0.83%   |
| HP x2                   | 1         | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2010 | 15        | 12.4%   |
| 2008 | 15        | 12.4%   |
| 2011 | 14        | 11.57%  |
| 2012 | 11        | 9.09%   |
| 2007 | 10        | 8.26%   |
| 2014 | 9         | 7.44%   |
| 2018 | 8         | 6.61%   |
| 2020 | 7         | 5.79%   |
| 2016 | 6         | 4.96%   |
| 2015 | 6         | 4.96%   |
| 2017 | 5         | 4.13%   |
| 2019 | 4         | 3.31%   |
| 2009 | 3         | 2.48%   |
| 2022 | 2         | 1.65%   |
| 2021 | 2         | 1.65%   |
| 2006 | 2         | 1.65%   |
| 2013 | 1         | 0.83%   |
| 2004 | 1         | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 70        | 57.85%  |
| Desktop    | 43        | 35.54%  |
| All in one | 4         | 3.31%   |
| Tablet     | 2         | 1.65%   |
| Mini pc    | 2         | 1.65%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 117       | 96.69%  |
| Enabled  | 4         | 3.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 120       | 99.17%  |
| Yes  | 1         | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 40        | 33.06%  |
| 1.01-2.0   | 26        | 21.49%  |
| 4.01-8.0   | 20        | 16.53%  |
| 16.01-24.0 | 13        | 10.74%  |
| 8.01-16.0  | 10        | 8.26%   |
| 32.01-64.0 | 4         | 3.31%   |
| 0.51-1.0   | 4         | 3.31%   |
| 2.01-3.0   | 3         | 2.48%   |
| 24.01-32.0 | 1         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 60        | 48.39%  |
| 2.01-3.0  | 24        | 19.35%  |
| 0.51-1.0  | 20        | 16.13%  |
| 3.01-4.0  | 9         | 7.26%   |
| 4.01-8.0  | 7         | 5.65%   |
| 0.01-0.5  | 3         | 2.42%   |
| 8.01-16.0 | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 85        | 70.25%  |
| 2      | 26        | 21.49%  |
| 3      | 6         | 4.96%   |
| 0      | 2         | 1.65%   |
| 5      | 1         | 0.83%   |
| 4      | 1         | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 56.2%   |
| Yes       | 53        | 43.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 87.6%   |
| No        | 15        | 12.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 80.17%  |
| No        | 24        | 19.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 63        | 52.07%  |
| Yes       | 58        | 47.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 20        | 16.53%  |
| Brazil      | 12        | 9.92%   |
| Germany     | 8         | 6.61%   |
| France      | 7         | 5.79%   |
| UK          | 6         | 4.96%   |
| Romania     | 6         | 4.96%   |
| Poland      | 6         | 4.96%   |
| Ukraine     | 5         | 4.13%   |
| Mexico      | 5         | 4.13%   |
| Canada      | 5         | 4.13%   |
| Italy       | 4         | 3.31%   |
| Turkey      | 3         | 2.48%   |
| Spain       | 3         | 2.48%   |
| Russia      | 3         | 2.48%   |
| Peru        | 3         | 2.48%   |
| Australia   | 3         | 2.48%   |
| Netherlands | 2         | 1.65%   |
| Chile       | 2         | 1.65%   |
| Venezuela   | 1         | 0.83%   |
| Slovakia    | 1         | 0.83%   |
| Qatar       | 1         | 0.83%   |
| Portugal    | 1         | 0.83%   |
| Philippines | 1         | 0.83%   |
| New Zealand | 1         | 0.83%   |
| Myanmar     | 1         | 0.83%   |
| Malaysia    | 1         | 0.83%   |
| Japan       | 1         | 0.83%   |
| Ireland     | 1         | 0.83%   |
| Iran        | 1         | 0.83%   |
| Indonesia   | 1         | 0.83%   |
| Hungary     | 1         | 0.83%   |
| Guadeloupe  | 1         | 0.83%   |
| Greenland   | 1         | 0.83%   |
| El Salvador | 1         | 0.83%   |
| Czechia     | 1         | 0.83%   |
| Colombia    | 1         | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Pabianice          | 3         | 2.42%   |
| Würzburg          | 2         | 1.61%   |
| Warsaw             | 2         | 1.61%   |
| Sydney             | 2         | 1.61%   |
| Sao Paulo          | 2         | 1.61%   |
| Ottawa             | 2         | 1.61%   |
| Odessa             | 2         | 1.61%   |
| Mexico City        | 2         | 1.61%   |
| Lima               | 2         | 1.61%   |
| Kyiv               | 2         | 1.61%   |
| Żywiec            | 1         | 0.81%   |
| Yangon             | 1         | 0.81%   |
| Wiesbaden          | 1         | 0.81%   |
| Wellington         | 1         | 0.81%   |
| Waterbury          | 1         | 0.81%   |
| Washington         | 1         | 0.81%   |
| Wahroonga          | 1         | 0.81%   |
| Voluntari          | 1         | 0.81%   |
| Vinnytsia          | 1         | 0.81%   |
| Varennes-les-Narcy | 1         | 0.81%   |
| Vancouver          | 1         | 0.81%   |
| Valencia           | 1         | 0.81%   |
| Tucape             | 1         | 0.81%   |
| Trujillo           | 1         | 0.81%   |
| Thetford-Mines     | 1         | 0.81%   |
| Teresina           | 1         | 0.81%   |
| Tekirdağ          | 1         | 0.81%   |
| Tarragona          | 1         | 0.81%   |
| Svidník           | 1         | 0.81%   |
| Surabaya           | 1         | 0.81%   |
| Studenka           | 1         | 0.81%   |
| St. Petersburg     | 1         | 0.81%   |
| Shadrinsk          | 1         | 0.81%   |
| Salerno            | 1         | 0.81%   |
| Sabadell           | 1         | 0.81%   |
| Roswell            | 1         | 0.81%   |
| Rio de Janeiro     | 1         | 0.81%   |
| Queretaro          | 1         | 0.81%   |
| Purmerend          | 1         | 0.81%   |
| Póvoa de Varzim   | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 34     | 19.59%  |
| WDC                 | 25        | 34     | 16.89%  |
| Samsung Electronics | 18        | 19     | 12.16%  |
| Toshiba             | 12        | 13     | 8.11%   |
| Unknown             | 9         | 13     | 6.08%   |
| Kingston            | 8         | 10     | 5.41%   |
| SanDisk             | 6         | 6      | 4.05%   |
| Hitachi             | 5         | 5      | 3.38%   |
| Micron Technology   | 4         | 5      | 2.7%    |
| Crucial             | 4         | 4      | 2.7%    |
| HGST                | 3         | 3      | 2.03%   |
| GOODRAM             | 3         | 3      | 2.03%   |
| SK hynix            | 2         | 3      | 1.35%   |
| Apple               | 2         | 2      | 1.35%   |
| A-DATA Technology   | 2         | 2      | 1.35%   |
| PNY                 | 1         | 1      | 0.68%   |
| Phison              | 1         | 1      | 0.68%   |
| OCZ                 | 1         | 1      | 0.68%   |
| Maxtor              | 1         | 1      | 0.68%   |
| Mass                | 1         | 1      | 0.68%   |
| LITEON              | 1         | 1      | 0.68%   |
| Intenso             | 1         | 1      | 0.68%   |
| Intel               | 1         | 1      | 0.68%   |
| HPE                 | 1         | 1      | 0.68%   |
| Hewlett-Packard     | 1         | 1      | 0.68%   |
| Gigabyte Technology | 1         | 1      | 0.68%   |
| China               | 1         | 1      | 0.68%   |
| ASUS-PHISON         | 1         | 2      | 0.68%   |
| ASMT                | 1         | 1      | 0.68%   |
| Apacer              | 1         | 1      | 0.68%   |
| Unknown             | 1         | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 4         | 2.52%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.89%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 1.89%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.89%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 1.26%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 1.26%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 1.26%   |
| Seagate ST9320325AS 320GB            | 2         | 1.26%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD  | 2         | 1.26%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.63%   |
| WDC WDS250G2B0A 250GB SSD            | 1         | 0.63%   |
| WDC WD800JD-60LSA0 80GB              | 1         | 0.63%   |
| WDC WD5000LPCX-75VHAT0 500GB         | 1         | 0.63%   |
| WDC WD5000AAKX-003CA0 500GB          | 1         | 0.63%   |
| WDC WD5000AAKS-60WWPA0 500GB         | 1         | 0.63%   |
| WDC WD5000AADS-56S9B0 500GB          | 1         | 0.63%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 0.63%   |
| WDC WD5000AACS-00G8B1 500GB          | 1         | 0.63%   |
| WDC WD2500BEVS-00UST0 250GB          | 1         | 0.63%   |
| WDC WD2500BEVE-00A0HT0 250GB         | 1         | 0.63%   |
| WDC WD20PURX-64PFUY0 2TB             | 1         | 0.63%   |
| WDC WD2005FBYZ-01YCBB2 2TB           | 1         | 0.63%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.63%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.63%   |
| WDC WD10EZEX-07WN4A0 1TB             | 1         | 0.63%   |
| WDC WD10EADS-00L5B1 1TB              | 1         | 0.63%   |
| WDC WD1003FBYX-01Y7B1 1TB            | 1         | 0.63%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB   | 1         | 0.63%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.63%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.63%   |
| Unknown SLD64G  64GB                 | 1         | 0.63%   |
| Unknown SD64G  64GB                  | 1         | 0.63%   |
| Unknown SD16G  16GB                  | 1         | 0.63%   |
| Unknown SC64G  64GB                  | 1         | 0.63%   |
| Unknown NCard  32GB                  | 1         | 0.63%   |
| Unknown MMC Card  128GB              | 1         | 0.63%   |
| Unknown HBG4a2  32GB                 | 1         | 0.63%   |
| Unknown DA4064  64GB                 | 1         | 0.63%   |
| Unknown BGND3R  32GB                 | 1         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 34     | 38.67%  |
| WDC                 | 19        | 24     | 25.33%  |
| Toshiba             | 12        | 13     | 16%     |
| Hitachi             | 5         | 5      | 6.67%   |
| Samsung Electronics | 3         | 4      | 4%      |
| HGST                | 3         | 3      | 4%      |
| Maxtor              | 1         | 1      | 1.33%   |
| HPE                 | 1         | 1      | 1.33%   |
| ASMT                | 1         | 1      | 1.33%   |
| Apple               | 1         | 1      | 1.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 18.75%  |
| Kingston            | 7         | 9      | 14.58%  |
| SanDisk             | 5         | 5      | 10.42%  |
| WDC                 | 4         | 5      | 8.33%   |
| Crucial             | 4         | 4      | 8.33%   |
| Micron Technology   | 3         | 4      | 6.25%   |
| GOODRAM             | 3         | 3      | 6.25%   |
| A-DATA Technology   | 2         | 2      | 4.17%   |
| SK hynix            | 1         | 2      | 2.08%   |
| PNY                 | 1         | 1      | 2.08%   |
| OCZ                 | 1         | 1      | 2.08%   |
| LITEON              | 1         | 1      | 2.08%   |
| Intel               | 1         | 1      | 2.08%   |
| Hewlett-Packard     | 1         | 1      | 2.08%   |
| Gigabyte Technology | 1         | 1      | 2.08%   |
| China               | 1         | 1      | 2.08%   |
| ASUS-PHISON         | 1         | 2      | 2.08%   |
| Apple               | 1         | 1      | 2.08%   |
| Apacer              | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 67        | 87     | 48.55%  |
| SSD     | 46        | 54     | 33.33%  |
| MMC     | 12        | 16     | 8.7%    |
| NVMe    | 11        | 14     | 7.97%   |
| Unknown | 2         | 2      | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 100       | 138    | 78.13%  |
| MMC  | 12        | 16     | 9.38%   |
| NVMe | 11        | 14     | 8.59%   |
| SAS  | 5         | 5      | 3.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 83        | 110    | 74.11%  |
| 0.51-1.0   | 24        | 25     | 21.43%  |
| 1.01-2.0   | 4         | 5      | 3.57%   |
| 4.01-10.0  | 1         | 1      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 41        | 33.33%  |
| 251-500        | 26        | 21.14%  |
| 51-100         | 19        | 15.45%  |
| 21-50          | 10        | 8.13%   |
| 1-20           | 10        | 8.13%   |
| 501-1000       | 9         | 7.32%   |
| More than 3000 | 5         | 4.07%   |
| 1001-2000      | 3         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 62        | 50%     |
| 21-50     | 26        | 20.97%  |
| 51-100    | 17        | 13.71%  |
| 101-250   | 10        | 8.06%   |
| 251-500   | 3         | 2.42%   |
| 2001-3000 | 2         | 1.61%   |
| 1001-2000 | 2         | 1.61%   |
| 501-1000  | 2         | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 4.35%   |
| WDC WD800JD-60LSA0 80GB                        | 1         | 1      | 4.35%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 4.35%   |
| WDC WD5000AAKS-60WWPA0 500GB                   | 1         | 1      | 4.35%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 4.35%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 4.35%   |
| Toshiba MK3265GSX 320GB                        | 1         | 1      | 4.35%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 4.35%   |
| Seagate ST980811AS 80GB                        | 1         | 1      | 4.35%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 4.35%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 4.35%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 4.35%   |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 4.35%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 4.35%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 4.35%   |
| SanDisk SSD PLUS 120GB                         | 1         | 1      | 4.35%   |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 4.35%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 4.35%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 4.35%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 4.35%   |
| Hitachi HDS721616PLA380 160GB                  | 1         | 1      | 4.35%   |
| Apacer 16GB SATA Flash Drive SSD               | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 30.43%  |
| WDC                 | 6         | 6      | 26.09%  |
| Toshiba             | 3         | 3      | 13.04%  |
| Hitachi             | 3         | 3      | 13.04%  |
| SanDisk             | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| Micron Technology   | 1         | 1      | 4.35%   |
| Apacer              | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 36.84%  |
| WDC                 | 5         | 5      | 26.32%  |
| Toshiba             | 3         | 3      | 15.79%  |
| Hitachi             | 3         | 3      | 15.79%  |
| Samsung Electronics | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 19     | 80.95%  |
| SSD  | 4         | 4      | 19.05%  |

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
| Works    | 54        | 70     | 43.2%   |
| Detected | 51        | 80     | 40.8%   |
| Malfunc  | 20        | 23     | 16%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 83        | 65.87%  |
| AMD                         | 20        | 15.87%  |
| Samsung Electronics         | 6         | 4.76%   |
| Nvidia                      | 6         | 4.76%   |
| SanDisk                     | 3         | 2.38%   |
| Marvell Technology Group    | 2         | 1.59%   |
| Phison Electronics          | 1         | 0.79%   |
| Micron Technology           | 1         | 0.79%   |
| LSI Logic / Symbios Logic   | 1         | 0.79%   |
| Kingston Technology Company | 1         | 0.79%   |
| JMicron Technology          | 1         | 0.79%   |
| Broadcom / LSI              | 1         | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12        | 7.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 4.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 4.24%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7         | 4.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 3.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 2.42%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 2.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.42%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 1.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.82%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3         | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 1.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.21%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.21%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 2         | 1.21%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2         | 1.21%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.21%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.21%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.21%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 1.21%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 1.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.21%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.21%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 82        | 58.57%  |
| IDE  | 41        | 29.29%  |
| NVMe | 11        | 7.86%   |
| RAID | 5         | 3.57%   |
| SCSI | 1         | 0.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 97        | 80.17%  |
| AMD    | 24        | 19.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 4         | 3.31%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3         | 2.48%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 1.65%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 1.65%   |
| Intel Core 2 CPU T7600 @ 2.33GHz            | 2         | 1.65%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.65%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 1.65%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.65%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 0.83%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1         | 0.83%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.83%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.83%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 0.83%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.83%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.83%   |
| Intel Pentium D CPU 3.40GHz                 | 1         | 0.83%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.83%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.83%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.83%   |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1         | 0.83%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.83%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.83%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 0.83%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 0.83%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.83%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.83%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.83%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 0.83%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 0.83%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1         | 0.83%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.83%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 0.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.83%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1         | 0.83%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 0.83%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 0.83%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 16        | 13.22%  |
| Intel Core 2 Duo        | 13        | 10.74%  |
| Intel Celeron           | 11        | 9.09%   |
| Intel Core i3           | 10        | 8.26%   |
| Intel Atom              | 10        | 8.26%   |
| Intel Core i7           | 9         | 7.44%   |
| Intel Pentium Dual-Core | 6         | 4.96%   |
| Intel Pentium           | 5         | 4.13%   |
| Other                   | 4         | 3.31%   |
| Intel Core 2            | 3         | 2.48%   |
| Intel Xeon              | 2         | 1.65%   |
| Intel Pentium Dual      | 2         | 1.65%   |
| Intel Genuine           | 2         | 1.65%   |
| AMD Turion 64 X2 Mobile | 2         | 1.65%   |
| AMD Ryzen 5             | 2         | 1.65%   |
| AMD E2                  | 2         | 1.65%   |
| AMD E                   | 2         | 1.65%   |
| AMD Athlon II X2        | 2         | 1.65%   |
| AMD A8                  | 2         | 1.65%   |
| AMD A6                  | 2         | 1.65%   |
| Intel Pentium D         | 1         | 0.83%   |
| Intel Core m7           | 1         | 0.83%   |
| Intel Core 2 Extreme    | 1         | 0.83%   |
| Intel Celeron M         | 1         | 0.83%   |
| AMD Turion Dual-Core    | 1         | 0.83%   |
| AMD Sempron             | 1         | 0.83%   |
| AMD Ryzen 9             | 1         | 0.83%   |
| AMD Ryzen 3             | 1         | 0.83%   |
| AMD Quad-Core           | 1         | 0.83%   |
| AMD Phenom II X2        | 1         | 0.83%   |
| AMD FX                  | 1         | 0.83%   |
| AMD Athlon II Neo       | 1         | 0.83%   |
| AMD A12                 | 1         | 0.83%   |
| AMD A10                 | 1         | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 70        | 57.85%  |
| 4      | 35        | 28.93%  |
| 1      | 7         | 5.79%   |
| 6      | 5         | 4.13%   |
| 14     | 1         | 0.83%   |
| 12     | 1         | 0.83%   |
| 10     | 1         | 0.83%   |
| 8      | 1         | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 120       | 99.17%  |
| 2      | 1         | 0.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 78        | 64.46%  |
| 2      | 43        | 35.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 119       | 98.35%  |
| 32-bit         | 2         | 1.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 12.3%   |
| 0x1067a    | 13        | 10.66%  |
| 0x206a7    | 11        | 9.02%   |
| 0x30678    | 7         | 5.74%   |
| 0x406c4    | 5         | 4.1%    |
| 0x6fd      | 4         | 3.28%   |
| 0x20655    | 4         | 3.28%   |
| 0x10676    | 4         | 3.28%   |
| 0x010000c8 | 4         | 3.28%   |
| 0x6fb      | 3         | 2.46%   |
| 0x40651    | 3         | 2.46%   |
| 0x306a9    | 3         | 2.46%   |
| 0x806ea    | 2         | 1.64%   |
| 0x806e9    | 2         | 1.64%   |
| 0x806c1    | 2         | 1.64%   |
| 0x6f6      | 2         | 1.64%   |
| 0x506c9    | 2         | 1.64%   |
| 0x406c3    | 2         | 1.64%   |
| 0x106ca    | 2         | 1.64%   |
| 0x05000119 | 2         | 1.64%   |
| 0xf64      | 1         | 0.82%   |
| 0xa0653    | 1         | 0.82%   |
| 0x906eb    | 1         | 0.82%   |
| 0x906ea    | 1         | 0.82%   |
| 0x906e9    | 1         | 0.82%   |
| 0x906a4    | 1         | 0.82%   |
| 0x906a3    | 1         | 0.82%   |
| 0x806ec    | 1         | 0.82%   |
| 0x806eb    | 1         | 0.82%   |
| 0x706a1    | 1         | 0.82%   |
| 0x6fa      | 1         | 0.82%   |
| 0x6d8      | 1         | 0.82%   |
| 0x506e3    | 1         | 0.82%   |
| 0x406e3    | 1         | 0.82%   |
| 0x306c3    | 1         | 0.82%   |
| 0x30661    | 1         | 0.82%   |
| 0x206c2    | 1         | 0.82%   |
| 0x0a50000d | 1         | 0.82%   |
| 0x08701013 | 1         | 0.82%   |
| 0x0810100b | 1         | 0.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 18        | 14.88%  |
| Silvermont       | 15        | 12.4%   |
| Core             | 12        | 9.92%   |
| SandyBridge      | 11        | 9.09%   |
| KabyLake         | 10        | 8.26%   |
| Westmere         | 5         | 4.13%   |
| K10              | 5         | 4.13%   |
| IvyBridge        | 5         | 4.13%   |
| Haswell          | 4         | 3.31%   |
| Bonnell          | 3         | 2.48%   |
| Bobcat           | 3         | 2.48%   |
| TigerLake        | 2         | 1.65%   |
| Skylake          | 2         | 1.65%   |
| Puma             | 2         | 1.65%   |
| Piledriver       | 2         | 1.65%   |
| P6               | 2         | 1.65%   |
| K8 Hammer        | 2         | 1.65%   |
| K10 Llano        | 2         | 1.65%   |
| Goldmont         | 2         | 1.65%   |
| Excavator        | 2         | 1.65%   |
| Alderlake Hybrid | 2         | 1.65%   |
| Zen+             | 1         | 0.83%   |
| Zen 3            | 1         | 0.83%   |
| Zen 2            | 1         | 0.83%   |
| Zen              | 1         | 0.83%   |
| NetBurst         | 1         | 0.83%   |
| Nehalem          | 1         | 0.83%   |
| K8 & K10 hybrid  | 1         | 0.83%   |
| Jaguar           | 1         | 0.83%   |
| Goldmont plus    | 1         | 0.83%   |
| CometLake        | 1         | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 72        | 55.38%  |
| Nvidia | 31        | 23.85%  |
| AMD    | 27        | 20.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 5.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 5.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 3.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 3.6%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 3.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 3.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.16%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 2.16%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.44%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.44%   |
| Intel HD Graphics 620                                                                    | 2         | 1.44%   |
| Intel HD Graphics 500                                                                    | 2         | 1.44%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.44%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 1.44%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.44%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.72%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.72%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.72%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.72%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 0.72%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 0.72%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.72%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1         | 0.72%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 0.72%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 0.72%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1         | 0.72%   |
| Nvidia G84 [GeForce 8400 GS]                                                             | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 63        | 52.07%  |
| 1 x AMD        | 24        | 19.83%  |
| 1 x Nvidia     | 22        | 18.18%  |
| Intel + Nvidia | 9         | 7.44%   |
| 2 x AMD        | 3         | 2.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 104       | 85.25%  |
| Proprietary | 15        | 12.3%   |
| Unknown     | 3         | 2.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 60.33%  |
| 0.01-0.5   | 27        | 22.31%  |
| 0.51-1.0   | 8         | 6.61%   |
| 1.01-2.0   | 7         | 5.79%   |
| 3.01-4.0   | 4         | 3.31%   |
| 5.01-6.0   | 2         | 1.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 20        | 16.53%  |
| AU Optronics            | 14        | 11.57%  |
| LG Display              | 10        | 8.26%   |
| Hewlett-Packard         | 9         | 7.44%   |
| Goldstar                | 7         | 5.79%   |
| Chimei Innolux          | 7         | 5.79%   |
| Chi Mei Optoelectronics | 7         | 5.79%   |
| BOE                     | 7         | 5.79%   |
| Acer                    | 5         | 4.13%   |
| Sony                    | 3         | 2.48%   |
| NEC Computers           | 3         | 2.48%   |
| Apple                   | 3         | 2.48%   |
| Ancor Communications    | 3         | 2.48%   |
| ViewSonic               | 2         | 1.65%   |
| LG Philips              | 2         | 1.65%   |
| HannStar                | 2         | 1.65%   |
| CPT                     | 2         | 1.65%   |
| Toshiba                 | 1         | 0.83%   |
| Seiko/Epson             | 1         | 0.83%   |
| SANYO                   | 1         | 0.83%   |
| Philips                 | 1         | 0.83%   |
| PANDA                   | 1         | 0.83%   |
| OEM                     | 1         | 0.83%   |
| MSI                     | 1         | 0.83%   |
| Lenovo                  | 1         | 0.83%   |
| InfoVision              | 1         | 0.83%   |
| Hitachi                 | 1         | 0.83%   |
| eMachines               | 1         | 0.83%   |
| BenQ                    | 1         | 0.83%   |
| Belinea                 | 1         | 0.83%   |
| AOC                     | 1         | 0.83%   |
| Unknown                 | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 2         | 1.59%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.59%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.59%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1         | 0.79%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1         | 0.79%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1         | 0.79%   |
| Toshiba L705A LCD705A 1280x1024 340x270mm 17.1-inch                   | 1         | 0.79%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.79%   |
| Sony TV SNYDC01 1360x768                                              | 1         | 0.79%   |
| Sony TV *00 SNY8004 3840x2160 1439x809mm 65.0-inch                    | 1         | 0.79%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.79%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch  | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 0.79%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1         | 0.79%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.79%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.79%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1         | 0.79%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 0.79%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                    | 1         | 0.79%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 0.79%   |
| OEM 22W_LCD_TV OEM3700 1920x1080                                      | 1         | 0.79%   |
| NEC Computers LCD1990SXi NEC66AC 1280x1024 376x301mm 19.0-inch        | 1         | 0.79%   |
| NEC Computers EA244WMi NEC68D7 1920x1200 519x324mm 24.1-inch          | 1         | 0.79%   |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch            | 1         | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 35        | 28.93%  |
| 1920x1080 (FHD)    | 31        | 25.62%  |
| 1920x1200 (WUXGA)  | 10        | 8.26%   |
| 1280x800 (WXGA)    | 8         | 6.61%   |
| 3840x2160 (4K)     | 6         | 4.96%   |
| 1280x1024 (SXGA)   | 6         | 4.96%   |
| 1680x1050 (WSXGA+) | 4         | 3.31%   |
| 1600x900 (HD+)     | 4         | 3.31%   |
| 1440x900 (WXGA+)   | 4         | 3.31%   |
| 2560x1440 (QHD)    | 2         | 1.65%   |
| 1360x768           | 2         | 1.65%   |
| 1024x600           | 2         | 1.65%   |
| Unknown            | 2         | 1.65%   |
| 5280x1080          | 1         | 0.83%   |
| 3840x2400          | 1         | 0.83%   |
| 1920x540           | 1         | 0.83%   |
| 1280x720 (HD)      | 1         | 0.83%   |
| 1024x768 (XGA)     | 1         | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 21.31%  |
| 17      | 12        | 9.84%   |
| 14      | 10        | 8.2%    |
| 13      | 9         | 7.38%   |
| 24      | 8         | 6.56%   |
| 21      | 8         | 6.56%   |
| Unknown | 7         | 5.74%   |
| 23      | 6         | 4.92%   |
| 19      | 5         | 4.1%    |
| 18      | 5         | 4.1%    |
| 11      | 5         | 4.1%    |
| 27      | 4         | 3.28%   |
| 20      | 3         | 2.46%   |
| 16      | 3         | 2.46%   |
| 10      | 3         | 2.46%   |
| 72      | 2         | 1.64%   |
| 12      | 2         | 1.64%   |
| 65      | 1         | 0.82%   |
| 46      | 1         | 0.82%   |
| 28      | 1         | 0.82%   |
| 22      | 1         | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 39.17%  |
| 401-500     | 19        | 15.83%  |
| 501-600     | 18        | 15%     |
| 201-300     | 13        | 10.83%  |
| 351-400     | 11        | 9.17%   |
| Unknown     | 7         | 5.83%   |
| 1501-2000   | 2         | 1.67%   |
| 1001-1500   | 2         | 1.67%   |
| 601-700     | 1         | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 77        | 66.96%  |
| 16/10   | 25        | 21.74%  |
| 5/4     | 6         | 5.22%   |
| Unknown | 5         | 4.35%   |
| 6/5     | 1         | 0.87%   |
| 4/3     | 1         | 0.87%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 21.31%  |
| 81-90          | 16        | 13.11%  |
| 201-250        | 16        | 13.11%  |
| 151-200        | 11        | 9.02%   |
| 141-150        | 8         | 6.56%   |
| Unknown        | 7         | 5.74%   |
| 51-60          | 5         | 4.1%    |
| 251-300        | 5         | 4.1%    |
| 131-140        | 5         | 4.1%    |
| 121-130        | 5         | 4.1%    |
| 301-350        | 4         | 3.28%   |
| More than 1000 | 3         | 2.46%   |
| 71-80          | 3         | 2.46%   |
| 41-50          | 3         | 2.46%   |
| 61-70          | 2         | 1.64%   |
| 351-500        | 1         | 0.82%   |
| 111-120        | 1         | 0.82%   |
| 501-1000       | 1         | 0.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 42        | 35.59%  |
| 101-120       | 36        | 30.51%  |
| 121-160       | 25        | 21.19%  |
| Unknown       | 7         | 5.93%   |
| 1-50          | 3         | 2.54%   |
| 161-240       | 3         | 2.54%   |
| More than 240 | 2         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 107       | 87.7%   |
| 2     | 13        | 10.66%  |
| 3     | 1         | 0.82%   |
| 0     | 1         | 0.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 64        | 34.41%  |
| Intel                                 | 41        | 22.04%  |
| Qualcomm Atheros                      | 28        | 15.05%  |
| Broadcom                              | 17        | 9.14%   |
| Ralink                                | 5         | 2.69%   |
| Broadcom Limited                      | 5         | 2.69%   |
| Ralink Technology                     | 4         | 2.15%   |
| Nvidia                                | 4         | 2.15%   |
| Marvell Technology Group              | 2         | 1.08%   |
| ASUSTek Computer                      | 2         | 1.08%   |
| ASIX Electronics                      | 2         | 1.08%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.54%   |
| TP-Link                               | 1         | 0.54%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.54%   |
| Sierra Wireless                       | 1         | 0.54%   |
| Samsung Electronics                   | 1         | 0.54%   |
| Qualcomm Atheros Communications       | 1         | 0.54%   |
| Microsoft                             | 1         | 0.54%   |
| MediaTek                              | 1         | 0.54%   |
| Linksys                               | 1         | 0.54%   |
| D-Link                                | 1         | 0.54%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.54%   |
| 3Com                                  | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 40        | 18.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 16        | 7.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 6         | 2.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 5         | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 2.31%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4         | 1.85%   |
| Intel Wireless 3165                                                                           | 4         | 1.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.39%   |
| Ralink MT7601U Wireless Adapter                                                               | 3         | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 1.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 3         | 1.39%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 0.93%   |
| Nvidia MCP77 Ethernet                                                                         | 2         | 0.93%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 0.93%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2         | 0.93%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                        | 2         | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 0.93%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                                                 | 2         | 0.93%   |
| ZTE WCDMA MSM Spreadtrum Phone                                                                | 1         | 0.46%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 0.46%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY                    | 1         | 0.46%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1         | 0.46%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 0.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.46%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 0.46%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.46%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.46%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 0.46%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 0.46%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 28        | 27.72%  |
| Qualcomm Atheros                      | 25        | 24.75%  |
| Realtek Semiconductor                 | 19        | 18.81%  |
| Broadcom                              | 7         | 6.93%   |
| Ralink                                | 5         | 4.95%   |
| Ralink Technology                     | 4         | 3.96%   |
| Broadcom Limited                      | 3         | 2.97%   |
| ASUSTek Computer                      | 2         | 1.98%   |
| TP-Link                               | 1         | 0.99%   |
| Sierra Wireless                       | 1         | 0.99%   |
| Qualcomm Atheros Communications       | 1         | 0.99%   |
| Microsoft                             | 1         | 0.99%   |
| MediaTek                              | 1         | 0.99%   |
| Linksys                               | 1         | 0.99%   |
| D-Link                                | 1         | 0.99%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 5.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 5         | 4.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 4.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4         | 3.92%   |
| Intel Wireless 3165                                                                           | 4         | 3.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 3.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 3.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 2.94%   |
| Ralink MT7601U Wireless Adapter                                                               | 3         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 2.94%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 1.96%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.96%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 1.96%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 0.98%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.98%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 0.98%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.98%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.98%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 0.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.98%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1         | 0.98%   |
| Realtek 802.11ac NIC                                                                          | 1         | 0.98%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.98%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.98%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.98%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.98%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1         | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.98%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1         | 0.98%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 60        | 53.57%  |
| Intel                             | 19        | 16.96%  |
| Broadcom                          | 11        | 9.82%   |
| Qualcomm Atheros                  | 8         | 7.14%   |
| Nvidia                            | 4         | 3.57%   |
| Marvell Technology Group          | 2         | 1.79%   |
| Broadcom Limited                  | 2         | 1.79%   |
| ASIX Electronics                  | 2         | 1.79%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.89%   |
| Sundance Technology Inc / IC Plus | 1         | 0.89%   |
| Samsung Electronics               | 1         | 0.89%   |
| 3Com                              | 1         | 0.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 40        | 35.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 16        | 14.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 5.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 3         | 2.65%   |
| Nvidia MCP77 Ethernet                                                         | 2         | 1.77%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 1.77%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 1.77%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 1.77%   |
| ZTE WCDMA MSM Spreadtrum Phone                                                | 1         | 0.88%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1         | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.88%   |
| Realtek USB 10/100 LAN                                                        | 1         | 0.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.88%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.88%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.88%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.88%   |
| Nvidia MCP51 Ethernet Controller                                              | 1         | 0.88%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.88%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.88%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 0.88%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.88%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.88%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1         | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.88%   |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 0.88%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 0.88%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 0.88%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 0.88%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 106       | 51.96%  |
| WiFi     | 97        | 47.55%  |
| Unknown  | 1         | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 59.06%  |
| Ethernet | 52        | 40.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 58.68%  |
| 1     | 43        | 35.54%  |
| 0     | 4         | 3.31%   |
| 3     | 2         | 1.65%   |
| 4     | 1         | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 96        | 78.69%  |
| Yes  | 26        | 21.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 29.31%  |
| Realtek Semiconductor           | 8         | 13.79%  |
| Lite-On Technology              | 4         | 6.9%    |
| IMC Networks                    | 4         | 6.9%    |
| Hewlett-Packard                 | 4         | 6.9%    |
| Cambridge Silicon Radio         | 4         | 6.9%    |
| Broadcom                        | 4         | 6.9%    |
| Qualcomm Atheros Communications | 3         | 5.17%   |
| Apple                           | 3         | 5.17%   |
| Dell                            | 2         | 3.45%   |
| Toshiba                         | 1         | 1.72%   |
| Ralink                          | 1         | 1.72%   |
| Foxconn / Hon Hai               | 1         | 1.72%   |
| Chicony Electronics             | 1         | 1.72%   |
| ASUSTek Computer                | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 13.79%  |
| Realtek Bluetooth Radio                             | 5         | 8.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 3.45%   |
| Intel AX201 Bluetooth                               | 2         | 3.45%   |
| IMC Networks Bluetooth Device                       | 2         | 3.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 3.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 3.45%   |
| Dell Wireless 355 Bluetooth                         | 2         | 3.45%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 3.45%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.72%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.72%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.72%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.72%   |
| Lite-On Bluetooth Device                            | 1         | 1.72%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.72%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.72%   |
| Intel Bluetooth Device                              | 1         | 1.72%   |
| Intel AX200 Bluetooth                               | 1         | 1.72%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.72%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.72%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.72%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 1.72%   |
| Broadcom HP Portable Valentine                      | 1         | 1.72%   |
| Broadcom HP Bluethunder                             | 1         | 1.72%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.72%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.72%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.72%   |
| Apple Bluetooth HCI                                 | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 88        | 61.11%  |
| AMD                   | 28        | 19.44%  |
| Nvidia                | 18        | 12.5%   |
| Logitech              | 2         | 1.39%   |
| C-Media Electronics   | 2         | 1.39%   |
| Texas Instruments     | 1         | 0.69%   |
| Realtek Semiconductor | 1         | 0.69%   |
| JMTek                 | 1         | 0.69%   |
| Ensoniq               | 1         | 0.69%   |
| Creative Labs         | 1         | 0.69%   |
| Blue Microphones      | 1         | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 8.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 6.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 4.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 4.24%   |
| AMD FCH Azalia Controller                                                                         | 7         | 4.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.64%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 3.64%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 3.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.03%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5         | 3.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 2.42%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.82%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.82%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.82%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.21%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.21%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.21%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.21%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.21%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.21%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.61%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1         | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.61%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.61%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 0.61%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.61%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.61%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.61%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 24        | 21.24%  |
| Samsung Electronics | 19        | 16.81%  |
| SK hynix            | 16        | 14.16%  |
| Kingston            | 13        | 11.5%   |
| Micron Technology   | 12        | 10.62%  |
| Unknown             | 5         | 4.42%   |
| Elpida              | 3         | 2.65%   |
| A-DATA Technology   | 3         | 2.65%   |
| Unknown (ABCD)      | 2         | 1.77%   |
| Ramaxel Technology  | 2         | 1.77%   |
| Nanya Technology    | 2         | 1.77%   |
| Corsair             | 2         | 1.77%   |
| Transcend           | 1         | 0.88%   |
| Qumo                | 1         | 0.88%   |
| Qimonda             | 1         | 0.88%   |
| GeIL                | 1         | 0.88%   |
| G.Skill             | 1         | 0.88%   |
| Avant               | 1         | 0.88%   |
| 2C0C1121390963FE    | 1         | 0.88%   |
| 2C0C1121390963FD    | 1         | 0.88%   |
| 2C0C1121390963F9    | 1         | 0.88%   |
| 2C0C1121390963F8    | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 4.31%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.72%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.72%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.86%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                          | 1         | 0.86%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.86%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 0.86%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.86%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.86%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.86%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.86%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.86%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.86%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.86%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.86%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.86%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.86%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                       | 1         | 0.86%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1         | 0.86%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                            | 1         | 0.86%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                   | 1         | 0.86%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.86%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                    | 1         | 0.86%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.86%   |
| Unknown RAM Module 1024MB DIMM DDR2                              | 1         | 0.86%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                       | 1         | 0.86%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.86%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.86%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s               | 1         | 0.86%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.86%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.86%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 1         | 0.86%   |
| SK hynix RAM HYMP125U64CP8-S6 2048MB DIMM DDR2 49926MT/s         | 1         | 0.86%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.86%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 34        | 35.79%  |
| DDR2    | 20        | 21.05%  |
| DDR4    | 18        | 18.95%  |
| SDRAM   | 9         | 9.47%   |
| Unknown | 6         | 6.32%   |
| LPDDR4  | 4         | 4.21%   |
| DDR     | 3         | 3.16%   |
| DRAM    | 1         | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 57        | 61.96%  |
| DIMM    | 34        | 36.96%  |
| FB-DIMM | 1         | 1.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 36        | 34.95%  |
| 4096  | 29        | 28.16%  |
| 8192  | 17        | 16.5%   |
| 1024  | 16        | 15.53%  |
| 16384 | 5         | 4.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 25        | 25.25%  |
| 3200    | 9         | 9.09%   |
| 667     | 9         | 9.09%   |
| 2667    | 8         | 8.08%   |
| 1333    | 8         | 8.08%   |
| Unknown | 8         | 8.08%   |
| 800     | 6         | 6.06%   |
| 2400    | 3         | 3.03%   |
| 975     | 3         | 3.03%   |
| 4199    | 2         | 2.02%   |
| 2048    | 2         | 2.02%   |
| 1334    | 2         | 2.02%   |
| 1066    | 2         | 2.02%   |
| 400     | 2         | 2.02%   |
| 49926   | 1         | 1.01%   |
| 19791   | 1         | 1.01%   |
| 3500    | 1         | 1.01%   |
| 3266    | 1         | 1.01%   |
| 2133    | 1         | 1.01%   |
| 1866    | 1         | 1.01%   |
| 1639    | 1         | 1.01%   |
| 1067    | 1         | 1.01%   |
| 1033    | 1         | 1.01%   |
| 133     | 1         | 1.01%   |

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
| Chicony Electronics                    | 18        | 26.09%  |
| Quanta                                 | 6         | 8.7%    |
| Cheng Uei Precision Industry (Foxlink) | 6         | 8.7%    |
| Suyin                                  | 5         | 7.25%   |
| Apple                                  | 5         | 7.25%   |
| Silicon Motion                         | 3         | 4.35%   |
| IMC Networks                           | 3         | 4.35%   |
| Alcor Micro                            | 3         | 4.35%   |
| Z-Star Microelectronics                | 2         | 2.9%    |
| Syntek                                 | 2         | 2.9%    |
| Sunplus Innovation Technology          | 2         | 2.9%    |
| Realtek Semiconductor                  | 2         | 2.9%    |
| Microdia                               | 2         | 2.9%    |
| Unknown                                | 1         | 1.45%   |
| Ricoh                                  | 1         | 1.45%   |
| OmniVision Technologies                | 1         | 1.45%   |
| Microsoft                              | 1         | 1.45%   |
| Logitech                               | 1         | 1.45%   |
| Lite-On Technology                     | 1         | 1.45%   |
| Jieli Technology                       | 1         | 1.45%   |
| Hewlett-Packard                        | 1         | 1.45%   |
| Generalplus Technology                 | 1         | 1.45%   |
| Aveo Technology                        | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                       | 5         | 7.25%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 2.9%    |
| Quanta HP TrueVision HD Camera                      | 2         | 2.9%    |
| Chicony HP High Definition 1MP Webcam               | 2         | 2.9%    |
| Chicony FJ Camera                                   | 2         | 2.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 2.9%    |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 2.9%    |
| Apple Built-in iSight                               | 2         | 2.9%    |
| Z-Star Webcam                                       | 1         | 1.45%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 1.45%   |
| Unknown Integrated RGB Camera                       | 1         | 1.45%   |
| Syntek USB Video Device                             | 1         | 1.45%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.45%   |
| Suyin USB 2.0 Camera                                | 1         | 1.45%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.45%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 1.45%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.45%   |
| Sunplus HD WebCam                                   | 1         | 1.45%   |
| Silicon Motion WebCam SC-10HDD13335N                | 1         | 1.45%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 1.45%   |
| Silicon Motion Web Camera                           | 1         | 1.45%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.45%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.45%   |
| Realtek USB Camera                                  | 1         | 1.45%   |
| Quanta VGA WebCam                                   | 1         | 1.45%   |
| Quanta HP Truevision HD                             | 1         | 1.45%   |
| Quanta HD Webcam                                    | 1         | 1.45%   |
| Quanta ACER HD User Facing                          | 1         | 1.45%   |
| OmniVision OV2640 Webcam                            | 1         | 1.45%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1         | 1.45%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.45%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.45%   |
| Logitech HD Webcam C615                             | 1         | 1.45%   |
| Lite-On Integrated Camera                           | 1         | 1.45%   |
| Jieli USB PHY 2.0                                   | 1         | 1.45%   |
| IMC Networks USB2.0 UVC VGA WebCam                  | 1         | 1.45%   |
| IMC Networks EasyCamera                             | 1         | 1.45%   |
| IMC Networks 2M Integrated Webcam                   | 1         | 1.45%   |
| HP Webcam HD 2300                                   | 1         | 1.45%   |
| Generalplus GENERAL WEBCAM                          | 1         | 1.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 4         | 50%     |
| Validity Sensors      | 1         | 12.5%   |
| Synaptics             | 1         | 12.5%   |
| Samsung Electronics   | 1         | 12.5%   |
| LighTuning Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor             | 2         | 25%     |
| Validity Sensors VFS451 Fingerprint Reader       | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 12.5%   |
| Samsung Fingerprint Device                       | 1         | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor      | 1         | 12.5%   |
| AuthenTec Fingerprint Sensor                     | 1         | 12.5%   |
| AuthenTec AES1600                                | 1         | 12.5%   |

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
| 0     | 92        | 75.41%  |
| 1     | 26        | 21.31%  |
| 2     | 4         | 3.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 23.53%  |
| Graphics card            | 7         | 20.59%  |
| Net/wireless             | 5         | 14.71%  |
| Multimedia controller    | 2         | 5.88%   |
| Chipcard                 | 2         | 5.88%   |
| Bluetooth                | 2         | 5.88%   |
| Unassigned class         | 1         | 2.94%   |
| Storage                  | 1         | 2.94%   |
| Sound                    | 1         | 2.94%   |
| Network                  | 1         | 2.94%   |
| Net/ethernet             | 1         | 2.94%   |
| Dvb card                 | 1         | 2.94%   |
| Communication controller | 1         | 2.94%   |
| Camera                   | 1         | 2.94%   |

