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

Total: 169

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Linux Lite 5.8 | 22        | 18.18%  |
| Linux Lite 6.0 | 18        | 14.88%  |
| Linux Lite 5.2 | 17        | 14.05%  |
| Linux Lite 5.0 | 17        | 14.05%  |
| Linux Lite 5.4 | 16        | 13.22%  |
| Linux Lite 5.6 | 13        | 10.74%  |
| Linux Lite 6.2 | 8         | 6.61%   |
| Linux Lite 3.8 | 5         | 4.13%   |
| Linux Lite 4.8 | 2         | 1.65%   |
| Linux Lite 4.6 | 1         | 0.83%   |
| Linux Lite 4.4 | 1         | 0.83%   |
| Linux Lite 4.2 | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Lite | 119       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 6         | 4.72%   |
| 5.4.0-70-generic  | 5         | 3.94%   |
| 5.4.0-91-generic  | 4         | 3.15%   |
| 5.4.0-52-generic  | 4         | 3.15%   |
| 5.4.0-40-generic  | 4         | 3.15%   |
| 5.4.0-109-generic | 4         | 3.15%   |
| 5.4.0-104-generic | 4         | 3.15%   |
| 5.4.0-96-generic  | 3         | 2.36%   |
| 5.4.0-58-generic  | 3         | 2.36%   |
| 5.4.0-48-generic  | 3         | 2.36%   |
| 5.4.0-113-generic | 3         | 2.36%   |
| 5.4.0-107-generic | 3         | 2.36%   |
| 5.15.0-58-generic | 3         | 2.36%   |
| 5.15.0-52-generic | 3         | 2.36%   |
| 5.15.0-47-generic | 3         | 2.36%   |
| 5.15.0-46-generic | 3         | 2.36%   |
| 5.15.0-33-generic | 3         | 2.36%   |
| 5.4.0-90-generic  | 2         | 1.57%   |
| 5.4.0-88-generic  | 2         | 1.57%   |
| 5.4.0-81-generic  | 2         | 1.57%   |
| 5.4.0-80-generic  | 2         | 1.57%   |
| 5.4.0-74-generic  | 2         | 1.57%   |
| 5.4.0-54-generic  | 2         | 1.57%   |
| 5.4.0-33-generic  | 2         | 1.57%   |
| 5.4.0-110-generic | 2         | 1.57%   |
| 5.4.0-105-generic | 2         | 1.57%   |
| 5.15.0-56-generic | 2         | 1.57%   |
| 5.15.0-48-generic | 2         | 1.57%   |
| 4.4.0-112-generic | 2         | 1.57%   |
| 6.1.0-1.linuxlite | 1         | 0.79%   |
| 6.0.0-1.linuxlite | 1         | 0.79%   |
| 6.0.0             | 1         | 0.79%   |
| 5.9.0             | 1         | 0.79%   |
| 5.4.0-99-generic  | 1         | 0.79%   |
| 5.4.0-94-generic  | 1         | 0.79%   |
| 5.4.0-77-generic  | 1         | 0.79%   |
| 5.4.0-72-generic  | 1         | 0.79%   |
| 5.4.0-71-generic  | 1         | 0.79%   |
| 5.4.0-66-generic  | 1         | 0.79%   |
| 5.4.0-65-generic  | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 79        | 64.23%  |
| 5.15.0  | 24        | 19.51%  |
| 4.15.0  | 5         | 4.07%   |
| 4.4.0   | 4         | 3.25%   |
| 5.13.0  | 3         | 2.44%   |
| 6.0.0   | 2         | 1.63%   |
| 6.1.0   | 1         | 0.81%   |
| 5.9.0   | 1         | 0.81%   |
| 5.19.0  | 1         | 0.81%   |
| 5.16.9  | 1         | 0.81%   |
| 5.16.0  | 1         | 0.81%   |
| 5.10.0  | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 79        | 64.23%  |
| 5.15    | 24        | 19.51%  |
| 4.15    | 5         | 4.07%   |
| 4.4     | 4         | 3.25%   |
| 5.13    | 3         | 2.44%   |
| 6.0     | 2         | 1.63%   |
| 5.16    | 2         | 1.63%   |
| 6.1     | 1         | 0.81%   |
| 5.9     | 1         | 0.81%   |
| 5.19    | 1         | 0.81%   |
| 5.10    | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 115       | 96.64%  |
| i686   | 4         | 3.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 91        | 76.47%  |
| GNOME   | 25        | 21.01%  |
| Unknown | 2         | 1.68%   |
| Deepin  | 1         | 0.84%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 117       | 98.32%  |
| Tty     | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 71        | 58.68%  |
| TDM     | 28        | 23.14%  |
| Unknown | 21        | 17.36%  |
| GDM     | 1         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 59        | 49.58%  |
| pt_BR | 7         | 5.88%   |
| de_DE | 7         | 5.88%   |
| pl_PL | 6         | 5.04%   |
| fr_FR | 6         | 5.04%   |
| en_GB | 6         | 5.04%   |
| ru_UA | 3         | 2.52%   |
| es_MX | 3         | 2.52%   |
| es_ES | 3         | 2.52%   |
| ru_RU | 2         | 1.68%   |
| it_IT | 2         | 1.68%   |
| en_CA | 2         | 1.68%   |
| zh_CN | 1         | 0.84%   |
| tr_TR | 1         | 0.84%   |
| pt_PT | 1         | 0.84%   |
| nl_NL | 1         | 0.84%   |
| hu_HU | 1         | 0.84%   |
| fr_CA | 1         | 0.84%   |
| es_CO | 1         | 0.84%   |
| es_CL | 1         | 0.84%   |
| en_NZ | 1         | 0.84%   |
| en_IE | 1         | 0.84%   |
| en_AU | 1         | 0.84%   |
| da_DK | 1         | 0.84%   |
| C     | 1         | 0.84%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 67        | 56.3%   |
| EFI  | 52        | 43.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 106       | 89.08%  |
| Overlay | 9         | 7.56%   |
| Btrfs   | 2         | 1.68%   |
| Zfs     | 1         | 0.84%   |
| Ext3    | 1         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 48        | 40.34%  |
| Unknown | 37        | 31.09%  |
| MBR     | 34        | 28.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 81.67%  |
| Yes       | 22        | 18.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 85        | 70.83%  |
| Yes       | 35        | 29.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 20.17%  |
| ASUSTek Computer    | 17        | 14.29%  |
| Lenovo              | 12        | 10.08%  |
| Acer                | 12        | 10.08%  |
| Dell                | 9         | 7.56%   |
| MSI                 | 5         | 4.2%    |
| Samsung Electronics | 4         | 3.36%   |
| Apple               | 4         | 3.36%   |
| Pegatron            | 3         | 2.52%   |
| Gigabyte Technology | 3         | 2.52%   |
| Fujitsu             | 3         | 2.52%   |
| Minix               | 2         | 1.68%   |
| Intel               | 2         | 1.68%   |
| Foxconn             | 2         | 1.68%   |
| ASRock              | 2         | 1.68%   |
| UMAX                | 1         | 0.84%   |
| TR                  | 1         | 0.84%   |
| Toshiba             | 1         | 0.84%   |
| Thomson             | 1         | 0.84%   |
| Sony                | 1         | 0.84%   |
| Packard Bell        | 1         | 0.84%   |
| Jetway              | 1         | 0.84%   |
| Inventec            | 1         | 0.84%   |
| Insignia            | 1         | 0.84%   |
| Google              | 1         | 0.84%   |
| EVGA                | 1         | 0.84%   |
| Braview             | 1         | 0.84%   |
| Biostar             | 1         | 0.84%   |
| AWOW                | 1         | 0.84%   |
| ABIT                | 1         | 0.84%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| MSI MS-7758                            | 2         | 1.68%   |
| UMAX VisionBook 12Wi 64G               | 1         | 0.84%   |
| TR ST Pro-KN                           | 1         | 0.84%   |
| Toshiba Satellite T215D                | 1         | 0.84%   |
| Thomson PT-NEO14A.2WH32                | 1         | 0.84%   |
| Sony VGC-JS54FB_W                      | 1         | 0.84%   |
| Samsung X420/X520                      | 1         | 0.84%   |
| Samsung NC110P/NC108P/NC111P           | 1         | 0.84%   |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 0.84%   |
| Samsung 530XBB                         | 1         | 0.84%   |
| Pegatron H36FF                         | 1         | 0.84%   |
| Pegatron 520-1135la                    | 1         | 0.84%   |
| Pegatron 520-1030a                     | 1         | 0.84%   |
| Packard Bell ISTART D2314              | 1         | 0.84%   |
| MSI MS-N014                            | 1         | 0.84%   |
| MSI MS-7C95                            | 1         | 0.84%   |
| MSI FZ079AA-ABF a6625fr                | 1         | 0.84%   |
| Minix Z83-4                            | 1         | 0.84%   |
| Minix Z64                              | 1         | 0.84%   |
| Lenovo ThinkStation P320 30BH000BFR    | 1         | 0.84%   |
| Lenovo ThinkPad T400 6475E13           | 1         | 0.84%   |
| Lenovo ThinkPad L480 20LS001AMC        | 1         | 0.84%   |
| Lenovo ThinkCentre M91p 4524RS6        | 1         | 0.84%   |
| Lenovo ThinkCentre M91p 4518E2M        | 1         | 0.84%   |
| Lenovo ThinkCentre A55 9265BL7         | 1         | 0.84%   |
| Lenovo MIIX 300-10IBY 80NR             | 1         | 0.84%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1    | 1         | 0.84%   |
| Lenovo IdeaPad 320-15ABR 80XS          | 1         | 0.84%   |
| Lenovo IdeaPad 100-14IBY 80MH          | 1         | 0.84%   |
| Lenovo H505S 10107                     | 1         | 0.84%   |
| Lenovo 3000 V200 0764A11               | 1         | 0.84%   |
| Jetway I61MG4                          | 1         | 0.84%   |
| Inventec Dell Thin Client Desktop 3290 | 1         | 0.84%   |
| Intel H61M-S1                          | 1         | 0.84%   |
| Intel DG31PR AAD97573-300              | 1         | 0.84%   |
| Insignia NS-P11W7100                   | 1         | 0.84%   |
| HP xw8600 Workstation                  | 1         | 0.84%   |
| HP x2 Detachable 10-p0XX               | 1         | 0.84%   |
| HP t5000 series                        | 1         | 0.84%   |
| HP Stream Notebook PC 13               | 1         | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HP Compaq               | 8         | 6.72%   |
| Acer Aspire             | 7         | 5.88%   |
| Dell Inspiron           | 4         | 3.36%   |
| Lenovo ThinkCentre      | 3         | 2.52%   |
| Lenovo IdeaPad          | 3         | 2.52%   |
| HP Laptop               | 3         | 2.52%   |
| MSI MS-7758             | 2         | 1.68%   |
| Lenovo ThinkPad         | 2         | 1.68%   |
| HP Pavilion             | 2         | 1.68%   |
| HP EliteBook            | 2         | 1.68%   |
| ASUS VivoBook           | 2         | 1.68%   |
| UMAX VisionBook         | 1         | 0.84%   |
| TR ST                   | 1         | 0.84%   |
| Toshiba Satellite       | 1         | 0.84%   |
| Thomson PT-NEO14A.2WH32 | 1         | 0.84%   |
| Sony VGC-JS54FB         | 1         | 0.84%   |
| Samsung X420            | 1         | 0.84%   |
| Samsung NC110P          | 1         | 0.84%   |
| Samsung 905S3G          | 1         | 0.84%   |
| Samsung 530XBB          | 1         | 0.84%   |
| Pegatron H36FF          | 1         | 0.84%   |
| Pegatron 520-1135la     | 1         | 0.84%   |
| Pegatron 520-1030a      | 1         | 0.84%   |
| Packard Bell ISTART     | 1         | 0.84%   |
| MSI MS-N014             | 1         | 0.84%   |
| MSI MS-7C95             | 1         | 0.84%   |
| MSI FZ079AA-ABF         | 1         | 0.84%   |
| Minix Z83-4             | 1         | 0.84%   |
| Minix Z64               | 1         | 0.84%   |
| Lenovo ThinkStation     | 1         | 0.84%   |
| Lenovo MIIX             | 1         | 0.84%   |
| Lenovo H505S            | 1         | 0.84%   |
| Lenovo 3000             | 1         | 0.84%   |
| Jetway I61MG4           | 1         | 0.84%   |
| Inventec Dell           | 1         | 0.84%   |
| Intel H61M-S1           | 1         | 0.84%   |
| Intel DG31PR            | 1         | 0.84%   |
| Insignia NS-P11W7100    | 1         | 0.84%   |
| HP xw8600               | 1         | 0.84%   |
| HP x2                   | 1         | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2010 | 15        | 12.61%  |
| 2008 | 15        | 12.61%  |
| 2011 | 13        | 10.92%  |
| 2012 | 11        | 9.24%   |
| 2014 | 9         | 7.56%   |
| 2007 | 9         | 7.56%   |
| 2018 | 8         | 6.72%   |
| 2020 | 7         | 5.88%   |
| 2016 | 6         | 5.04%   |
| 2015 | 6         | 5.04%   |
| 2017 | 5         | 4.2%    |
| 2019 | 4         | 3.36%   |
| 2009 | 3         | 2.52%   |
| 2022 | 2         | 1.68%   |
| 2021 | 2         | 1.68%   |
| 2006 | 2         | 1.68%   |
| 2013 | 1         | 0.84%   |
| 2004 | 1         | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 69        | 57.98%  |
| Desktop    | 42        | 35.29%  |
| All in one | 4         | 3.36%   |
| Tablet     | 2         | 1.68%   |
| Mini pc    | 2         | 1.68%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 115       | 96.64%  |
| Enabled  | 4         | 3.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 118       | 99.16%  |
| Yes  | 1         | 0.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 38        | 31.93%  |
| 1.01-2.0   | 26        | 21.85%  |
| 4.01-8.0   | 20        | 16.81%  |
| 16.01-24.0 | 13        | 10.92%  |
| 8.01-16.0  | 10        | 8.4%    |
| 32.01-64.0 | 4         | 3.36%   |
| 0.51-1.0   | 4         | 3.36%   |
| 2.01-3.0   | 3         | 2.52%   |
| 24.01-32.0 | 1         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 58        | 47.93%  |
| 2.01-3.0  | 23        | 19.01%  |
| 0.51-1.0  | 20        | 16.53%  |
| 3.01-4.0  | 9         | 7.44%   |
| 4.01-8.0  | 7         | 5.79%   |
| 0.01-0.5  | 3         | 2.48%   |
| 8.01-16.0 | 1         | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 83        | 69.75%  |
| 2      | 26        | 21.85%  |
| 3      | 6         | 5.04%   |
| 0      | 2         | 1.68%   |
| 5      | 1         | 0.84%   |
| 4      | 1         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 57.14%  |
| Yes       | 51        | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 87.39%  |
| No        | 15        | 12.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 79.83%  |
| No        | 24        | 20.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 51.26%  |
| Yes       | 58        | 48.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 19        | 15.97%  |
| Brazil      | 12        | 10.08%  |
| Germany     | 8         | 6.72%   |
| France      | 7         | 5.88%   |
| UK          | 6         | 5.04%   |
| Romania     | 6         | 5.04%   |
| Poland      | 6         | 5.04%   |
| Ukraine     | 5         | 4.2%    |
| Canada      | 5         | 4.2%    |
| Mexico      | 4         | 3.36%   |
| Italy       | 4         | 3.36%   |
| Turkey      | 3         | 2.52%   |
| Spain       | 3         | 2.52%   |
| Russia      | 3         | 2.52%   |
| Peru        | 3         | 2.52%   |
| Australia   | 3         | 2.52%   |
| Netherlands | 2         | 1.68%   |
| Chile       | 2         | 1.68%   |
| Venezuela   | 1         | 0.84%   |
| Slovakia    | 1         | 0.84%   |
| Qatar       | 1         | 0.84%   |
| Portugal    | 1         | 0.84%   |
| Philippines | 1         | 0.84%   |
| New Zealand | 1         | 0.84%   |
| Myanmar     | 1         | 0.84%   |
| Malaysia    | 1         | 0.84%   |
| Japan       | 1         | 0.84%   |
| Ireland     | 1         | 0.84%   |
| Iran        | 1         | 0.84%   |
| Indonesia   | 1         | 0.84%   |
| Hungary     | 1         | 0.84%   |
| Guadeloupe  | 1         | 0.84%   |
| Greenland   | 1         | 0.84%   |
| El Salvador | 1         | 0.84%   |
| Czechia     | 1         | 0.84%   |
| Colombia    | 1         | 0.84%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Pabianice          | 3         | 2.46%   |
| Würzburg          | 2         | 1.64%   |
| Warsaw             | 2         | 1.64%   |
| Sydney             | 2         | 1.64%   |
| Sao Paulo          | 2         | 1.64%   |
| Ottawa             | 2         | 1.64%   |
| Odessa             | 2         | 1.64%   |
| Lima               | 2         | 1.64%   |
| Kyiv               | 2         | 1.64%   |
| Żywiec            | 1         | 0.82%   |
| Yangon             | 1         | 0.82%   |
| Wiesbaden          | 1         | 0.82%   |
| Wellington         | 1         | 0.82%   |
| Waterbury          | 1         | 0.82%   |
| Washington         | 1         | 0.82%   |
| Wahroonga          | 1         | 0.82%   |
| Voluntari          | 1         | 0.82%   |
| Vinnytsia          | 1         | 0.82%   |
| Varennes-les-Narcy | 1         | 0.82%   |
| Vancouver          | 1         | 0.82%   |
| Valencia           | 1         | 0.82%   |
| Tucape             | 1         | 0.82%   |
| Trujillo           | 1         | 0.82%   |
| Thetford-Mines     | 1         | 0.82%   |
| Teresina           | 1         | 0.82%   |
| Tekirdağ          | 1         | 0.82%   |
| Tarragona          | 1         | 0.82%   |
| Svidník           | 1         | 0.82%   |
| Surabaya           | 1         | 0.82%   |
| Studenka           | 1         | 0.82%   |
| St. Petersburg     | 1         | 0.82%   |
| Shadrinsk          | 1         | 0.82%   |
| Salerno            | 1         | 0.82%   |
| Sabadell           | 1         | 0.82%   |
| Rio de Janeiro     | 1         | 0.82%   |
| Queretaro          | 1         | 0.82%   |
| Purmerend          | 1         | 0.82%   |
| Póvoa de Varzim   | 1         | 0.82%   |
| Porto Velho        | 1         | 0.82%   |
| Porto Alegre       | 1         | 0.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 32     | 19.86%  |
| WDC                 | 25        | 34     | 17.12%  |
| Samsung Electronics | 18        | 19     | 12.33%  |
| Toshiba             | 12        | 13     | 8.22%   |
| Unknown             | 9         | 13     | 6.16%   |
| Kingston            | 8         | 10     | 5.48%   |
| SanDisk             | 6         | 6      | 4.11%   |
| Hitachi             | 5         | 5      | 3.42%   |
| Micron Technology   | 4         | 5      | 2.74%   |
| Crucial             | 4         | 4      | 2.74%   |
| HGST                | 3         | 3      | 2.05%   |
| Goodram             | 3         | 3      | 2.05%   |
| SK hynix            | 2         | 3      | 1.37%   |
| Apple               | 2         | 2      | 1.37%   |
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
| Unknown MMC Card  32GB               | 4         | 2.55%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.91%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 1.91%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.91%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 1.27%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 1.27%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 1.27%   |
| Seagate ST9320325AS 320GB            | 2         | 1.27%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD  | 2         | 1.27%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.64%   |
| WDC WDS250G2B0A 250GB SSD            | 1         | 0.64%   |
| WDC WD800JD-60LSA0 80GB              | 1         | 0.64%   |
| WDC WD5000LPCX-75VHAT0 500GB         | 1         | 0.64%   |
| WDC WD5000AAKX-003CA0 500GB          | 1         | 0.64%   |
| WDC WD5000AAKS-60WWPA0 500GB         | 1         | 0.64%   |
| WDC WD5000AADS-56S9B0 500GB          | 1         | 0.64%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 0.64%   |
| WDC WD5000AACS-00G8B1 500GB          | 1         | 0.64%   |
| WDC WD2500BEVS-00UST0 250GB          | 1         | 0.64%   |
| WDC WD2500BEVE-00A0HT0 250GB         | 1         | 0.64%   |
| WDC WD20PURX-64PFUY0 2TB             | 1         | 0.64%   |
| WDC WD2005FBYZ-01YCBB2 2TB           | 1         | 0.64%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.64%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.64%   |
| WDC WD10EZEX-07WN4A0 1TB             | 1         | 0.64%   |
| WDC WD10EADS-00L5B1 1TB              | 1         | 0.64%   |
| WDC WD1003FBYX-01Y7B1 1TB            | 1         | 0.64%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB   | 1         | 0.64%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.64%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.64%   |
| Unknown SLD64G  64GB                 | 1         | 0.64%   |
| Unknown SD64G  64GB                  | 1         | 0.64%   |
| Unknown SD16G  16GB                  | 1         | 0.64%   |
| Unknown SC64G  64GB                  | 1         | 0.64%   |
| Unknown NCard  32GB                  | 1         | 0.64%   |
| Unknown MMC Card  128GB              | 1         | 0.64%   |
| Unknown HBG4a2  32GB                 | 1         | 0.64%   |
| Unknown DA4064  64GB                 | 1         | 0.64%   |
| Unknown BGND3R  32GB                 | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 32     | 39.19%  |
| WDC                 | 19        | 24     | 25.68%  |
| Toshiba             | 12        | 13     | 16.22%  |
| Hitachi             | 5         | 5      | 6.76%   |
| Samsung Electronics | 3         | 4      | 4.05%   |
| HGST                | 3         | 3      | 4.05%   |
| Maxtor              | 1         | 1      | 1.35%   |
| ASMT                | 1         | 1      | 1.35%   |
| Apple               | 1         | 1      | 1.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 19.57%  |
| Kingston            | 7         | 9      | 15.22%  |
| SanDisk             | 5         | 5      | 10.87%  |
| WDC                 | 4         | 5      | 8.7%    |
| Crucial             | 4         | 4      | 8.7%    |
| Micron Technology   | 3         | 4      | 6.52%   |
| Goodram             | 3         | 3      | 6.52%   |
| SK hynix            | 1         | 2      | 2.17%   |
| PNY                 | 1         | 1      | 2.17%   |
| OCZ                 | 1         | 1      | 2.17%   |
| LITEON              | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| Hewlett-Packard     | 1         | 1      | 2.17%   |
| Gigabyte Technology | 1         | 1      | 2.17%   |
| China               | 1         | 1      | 2.17%   |
| ASUS-PHISON         | 1         | 2      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |
| Apacer              | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 67        | 84     | 48.91%  |
| SSD     | 44        | 52     | 32.12%  |
| MMC     | 12        | 16     | 8.76%   |
| NVMe    | 11        | 14     | 8.03%   |
| Unknown | 3         | 3      | 2.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 98        | 134    | 77.78%  |
| MMC  | 12        | 16     | 9.52%   |
| NVMe | 11        | 14     | 8.73%   |
| SAS  | 5         | 5      | 3.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 106    | 74.31%  |
| 0.51-1.0   | 23        | 24     | 21.1%   |
| 1.01-2.0   | 4         | 5      | 3.67%   |
| 3.01-4.0   | 1         | 1      | 0.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 33.06%  |
| 251-500        | 25        | 20.66%  |
| 51-100         | 19        | 15.7%   |
| 21-50          | 10        | 8.26%   |
| 1-20           | 10        | 8.26%   |
| 501-1000       | 9         | 7.44%   |
| More than 3000 | 5         | 4.13%   |
| 1001-2000      | 3         | 2.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 61        | 50%     |
| 21-50     | 26        | 21.31%  |
| 51-100    | 16        | 13.11%  |
| 101-250   | 10        | 8.2%    |
| 251-500   | 3         | 2.46%   |
| 2001-3000 | 2         | 1.64%   |
| 1001-2000 | 2         | 1.64%   |
| 501-1000  | 2         | 1.64%   |

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
| Works    | 53        | 69     | 43.09%  |
| Detected | 50        | 77     | 40.65%  |
| Malfunc  | 20        | 23     | 16.26%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 82        | 66.13%  |
| AMD                         | 19        | 15.32%  |
| Samsung Electronics         | 6         | 4.84%   |
| Nvidia                      | 6         | 4.84%   |
| SanDisk                     | 3         | 2.42%   |
| Marvell Technology Group    | 2         | 1.61%   |
| Phison Electronics          | 1         | 0.81%   |
| Micron Technology           | 1         | 0.81%   |
| LSI Logic / Symbios Logic   | 1         | 0.81%   |
| Kingston Technology Company | 1         | 0.81%   |
| JMicron Technology          | 1         | 0.81%   |
| Broadcom / LSI              | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12        | 7.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 4.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 4.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 3.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 3.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 2.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 2.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.48%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 1.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.86%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3         | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.24%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.24%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 2         | 1.24%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2         | 1.24%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.24%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.24%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.24%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.24%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 1.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.24%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.62%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.62%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 80        | 58.82%  |
| IDE  | 39        | 28.68%  |
| NVMe | 11        | 8.09%   |
| RAID | 5         | 3.68%   |
| SCSI | 1         | 0.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 96        | 80.67%  |
| AMD    | 23        | 19.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 4         | 3.36%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3         | 2.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 1.68%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 1.68%   |
| Intel Core 2 CPU T7600 @ 2.33GHz            | 2         | 1.68%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.68%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 1.68%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.68%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 0.84%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1         | 0.84%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.84%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.84%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 0.84%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.84%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.84%   |
| Intel Pentium D CPU 3.40GHz                 | 1         | 0.84%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.84%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.84%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.84%   |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1         | 0.84%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.84%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.84%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 0.84%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 0.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.84%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.84%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.84%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.84%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 0.84%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 0.84%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1         | 0.84%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.84%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 0.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.84%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1         | 0.84%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 0.84%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 0.84%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 16        | 13.45%  |
| Intel Core 2 Duo        | 13        | 10.92%  |
| Intel Celeron           | 11        | 9.24%   |
| Intel Core i3           | 10        | 8.4%    |
| Intel Atom              | 10        | 8.4%    |
| Intel Core i7           | 9         | 7.56%   |
| Intel Pentium Dual-Core | 6         | 5.04%   |
| Intel Pentium           | 5         | 4.2%    |
| Other                   | 4         | 3.36%   |
| Intel Xeon              | 2         | 1.68%   |
| Intel Pentium Dual      | 2         | 1.68%   |
| Intel Genuine           | 2         | 1.68%   |
| Intel Core 2            | 2         | 1.68%   |
| AMD Turion 64 X2 Mobile | 2         | 1.68%   |
| AMD Ryzen 5             | 2         | 1.68%   |
| AMD E2                  | 2         | 1.68%   |
| AMD E                   | 2         | 1.68%   |
| AMD Athlon II X2        | 2         | 1.68%   |
| AMD A8                  | 2         | 1.68%   |
| AMD A6                  | 2         | 1.68%   |
| Intel Pentium D         | 1         | 0.84%   |
| Intel Core m7           | 1         | 0.84%   |
| Intel Core 2 Extreme    | 1         | 0.84%   |
| Intel Celeron M         | 1         | 0.84%   |
| AMD Turion Dual-Core    | 1         | 0.84%   |
| AMD Ryzen 9             | 1         | 0.84%   |
| AMD Ryzen 3             | 1         | 0.84%   |
| AMD Quad-Core           | 1         | 0.84%   |
| AMD Phenom II X2        | 1         | 0.84%   |
| AMD FX                  | 1         | 0.84%   |
| AMD Athlon II Neo       | 1         | 0.84%   |
| AMD A12                 | 1         | 0.84%   |
| AMD A10                 | 1         | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 69        | 57.98%  |
| 4      | 35        | 29.41%  |
| 1      | 6         | 5.04%   |
| 6      | 5         | 4.2%    |
| 14     | 1         | 0.84%   |
| 12     | 1         | 0.84%   |
| 10     | 1         | 0.84%   |
| 8      | 1         | 0.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 118       | 99.16%  |
| 2      | 1         | 0.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 76        | 63.87%  |
| 2      | 43        | 36.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 117       | 98.32%  |
| 32-bit         | 2         | 1.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 13        | 10.92%  |
| Unknown    | 13        | 10.92%  |
| 0x206a7    | 11        | 9.24%   |
| 0x30678    | 7         | 5.88%   |
| 0x406c4    | 5         | 4.2%    |
| 0x6fd      | 4         | 3.36%   |
| 0x20655    | 4         | 3.36%   |
| 0x10676    | 4         | 3.36%   |
| 0x6fb      | 3         | 2.52%   |
| 0x40651    | 3         | 2.52%   |
| 0x306a9    | 3         | 2.52%   |
| 0x010000c8 | 3         | 2.52%   |
| 0x806ea    | 2         | 1.68%   |
| 0x806e9    | 2         | 1.68%   |
| 0x806c1    | 2         | 1.68%   |
| 0x6f6      | 2         | 1.68%   |
| 0x506c9    | 2         | 1.68%   |
| 0x406c3    | 2         | 1.68%   |
| 0x106ca    | 2         | 1.68%   |
| 0x05000119 | 2         | 1.68%   |
| 0xf64      | 1         | 0.84%   |
| 0xa0653    | 1         | 0.84%   |
| 0x906eb    | 1         | 0.84%   |
| 0x906ea    | 1         | 0.84%   |
| 0x906e9    | 1         | 0.84%   |
| 0x906a4    | 1         | 0.84%   |
| 0x906a3    | 1         | 0.84%   |
| 0x806ec    | 1         | 0.84%   |
| 0x806eb    | 1         | 0.84%   |
| 0x706a1    | 1         | 0.84%   |
| 0x6fa      | 1         | 0.84%   |
| 0x6d8      | 1         | 0.84%   |
| 0x506e3    | 1         | 0.84%   |
| 0x406e3    | 1         | 0.84%   |
| 0x306c3    | 1         | 0.84%   |
| 0x30661    | 1         | 0.84%   |
| 0x206c2    | 1         | 0.84%   |
| 0x0a50000d | 1         | 0.84%   |
| 0x08701013 | 1         | 0.84%   |
| 0x0810100b | 1         | 0.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 18        | 15.13%  |
| Silvermont       | 15        | 12.61%  |
| SandyBridge      | 11        | 9.24%   |
| Core             | 11        | 9.24%   |
| KabyLake         | 10        | 8.4%    |
| Westmere         | 5         | 4.2%    |
| IvyBridge        | 5         | 4.2%    |
| K10              | 4         | 3.36%   |
| Haswell          | 4         | 3.36%   |
| Bonnell          | 3         | 2.52%   |
| Bobcat           | 3         | 2.52%   |
| TigerLake        | 2         | 1.68%   |
| Skylake          | 2         | 1.68%   |
| Puma             | 2         | 1.68%   |
| Piledriver       | 2         | 1.68%   |
| P6               | 2         | 1.68%   |
| K8 Hammer        | 2         | 1.68%   |
| K10 Llano        | 2         | 1.68%   |
| Goldmont         | 2         | 1.68%   |
| Excavator        | 2         | 1.68%   |
| Alderlake Hybrid | 2         | 1.68%   |
| Zen+             | 1         | 0.84%   |
| Zen 3            | 1         | 0.84%   |
| Zen 2            | 1         | 0.84%   |
| Zen              | 1         | 0.84%   |
| NetBurst         | 1         | 0.84%   |
| Nehalem          | 1         | 0.84%   |
| K8 & K10 hybrid  | 1         | 0.84%   |
| Jaguar           | 1         | 0.84%   |
| Goldmont plus    | 1         | 0.84%   |
| CometLake        | 1         | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 72        | 56.25%  |
| Nvidia | 30        | 23.44%  |
| AMD    | 26        | 20.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 5.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 5.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 3.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 3.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 3.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 3.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.19%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 2.19%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.46%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.46%   |
| Intel HD Graphics 620                                                                    | 2         | 1.46%   |
| Intel HD Graphics 500                                                                    | 2         | 1.46%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.46%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 1.46%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.46%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.73%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.73%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 0.73%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.73%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.73%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.73%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.73%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.73%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 0.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.73%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 0.73%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 0.73%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 0.73%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.73%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1         | 0.73%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 0.73%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 0.73%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1         | 0.73%   |
| Nvidia G84 [GeForce 8400 GS]                                                             | 1         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 63        | 52.94%  |
| 1 x AMD        | 23        | 19.33%  |
| 1 x Nvidia     | 21        | 17.65%  |
| Intel + Nvidia | 9         | 7.56%   |
| 2 x AMD        | 3         | 2.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 102       | 85%     |
| Proprietary | 15        | 12.5%   |
| Unknown     | 3         | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 60.5%   |
| 0.01-0.5   | 26        | 21.85%  |
| 0.51-1.0   | 8         | 6.72%   |
| 1.01-2.0   | 7         | 5.88%   |
| 3.01-4.0   | 4         | 3.36%   |
| 5.01-6.0   | 2         | 1.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 19        | 15.97%  |
| AU Optronics            | 14        | 11.76%  |
| LG Display              | 10        | 8.4%    |
| Hewlett-Packard         | 9         | 7.56%   |
| Goldstar                | 7         | 5.88%   |
| Chimei Innolux          | 7         | 5.88%   |
| Chi Mei Optoelectronics | 7         | 5.88%   |
| BOE                     | 7         | 5.88%   |
| Acer                    | 5         | 4.2%    |
| NEC Computers           | 3         | 2.52%   |
| Apple                   | 3         | 2.52%   |
| Ancor Communications    | 3         | 2.52%   |
| ViewSonic               | 2         | 1.68%   |
| Sony                    | 2         | 1.68%   |
| LG Philips              | 2         | 1.68%   |
| HannStar                | 2         | 1.68%   |
| CPT                     | 2         | 1.68%   |
| Toshiba                 | 1         | 0.84%   |
| Seiko/Epson             | 1         | 0.84%   |
| SANYO                   | 1         | 0.84%   |
| Philips                 | 1         | 0.84%   |
| PANDA                   | 1         | 0.84%   |
| OEM                     | 1         | 0.84%   |
| MSI                     | 1         | 0.84%   |
| Lenovo                  | 1         | 0.84%   |
| InfoVision              | 1         | 0.84%   |
| Hitachi                 | 1         | 0.84%   |
| eMachines               | 1         | 0.84%   |
| BenQ                    | 1         | 0.84%   |
| Belinea                 | 1         | 0.84%   |
| AOC                     | 1         | 0.84%   |
| Unknown                 | 1         | 0.84%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 2         | 1.61%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch              | 2         | 1.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.61%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1         | 0.81%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1         | 0.81%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1         | 0.81%   |
| Toshiba L705A LCD705A 1280x1024 340x270mm 17.1-inch                   | 1         | 0.81%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.81%   |
| Sony TV  *00 SNY8004 3840x2160 1440x810mm 65.0-inch                   | 1         | 0.81%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.81%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch  | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 0.81%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1         | 0.81%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.81%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.81%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1         | 0.81%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3155 1366x768 293x165mm 13.2-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 0.81%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                    | 1         | 0.81%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 0.81%   |
| OEM 22W_LCD_TV OEM3700 1920x1080                                      | 1         | 0.81%   |
| NEC Computers LCD1990SXi NEC66AC 1280x1024 376x301mm 19.0-inch        | 1         | 0.81%   |
| NEC Computers EA244WMi NEC68D7 1920x1200 519x324mm 24.1-inch          | 1         | 0.81%   |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch            | 1         | 0.81%   |
| MSI G272 MSI3CB5 1920x1080 598x336mm 27.0-inch                        | 1         | 0.81%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch           | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 35        | 29.41%  |
| 1920x1080 (FHD)    | 31        | 26.05%  |
| 1920x1200 (WUXGA)  | 10        | 8.4%    |
| 1280x800 (WXGA)    | 8         | 6.72%   |
| 3840x2160 (4K)     | 6         | 5.04%   |
| 1280x1024 (SXGA)   | 6         | 5.04%   |
| 1600x900 (HD+)     | 4         | 3.36%   |
| 1440x900 (WXGA+)   | 4         | 3.36%   |
| 1680x1050 (WSXGA+) | 3         | 2.52%   |
| 2560x1440 (QHD)    | 2         | 1.68%   |
| 1024x600           | 2         | 1.68%   |
| Unknown            | 2         | 1.68%   |
| 5280x1080          | 1         | 0.84%   |
| 3840x2400          | 1         | 0.84%   |
| 1920x540           | 1         | 0.84%   |
| 1360x768           | 1         | 0.84%   |
| 1280x720 (HD)      | 1         | 0.84%   |
| 1024x768 (XGA)     | 1         | 0.84%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 21.67%  |
| 17      | 12        | 10%     |
| 14      | 10        | 8.33%   |
| 13      | 9         | 7.5%    |
| 24      | 8         | 6.67%   |
| 21      | 8         | 6.67%   |
| Unknown | 7         | 5.83%   |
| 23      | 6         | 5%      |
| 19      | 5         | 4.17%   |
| 18      | 5         | 4.17%   |
| 11      | 5         | 4.17%   |
| 27      | 4         | 3.33%   |
| 20      | 3         | 2.5%    |
| 10      | 3         | 2.5%    |
| 16      | 2         | 1.67%   |
| 12      | 2         | 1.67%   |
| 72      | 1         | 0.83%   |
| 65      | 1         | 0.83%   |
| 46      | 1         | 0.83%   |
| 28      | 1         | 0.83%   |
| 22      | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 39.83%  |
| 401-500     | 19        | 16.1%   |
| 501-600     | 18        | 15.25%  |
| 201-300     | 13        | 11.02%  |
| 351-400     | 10        | 8.47%   |
| Unknown     | 7         | 5.93%   |
| 1001-1500   | 2         | 1.69%   |
| 601-700     | 1         | 0.85%   |
| 1501-2000   | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 76        | 67.26%  |
| 16/10   | 24        | 21.24%  |
| 5/4     | 6         | 5.31%   |
| Unknown | 5         | 4.42%   |
| 6/5     | 1         | 0.88%   |
| 4/3     | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 21.67%  |
| 81-90          | 16        | 13.33%  |
| 201-250        | 16        | 13.33%  |
| 151-200        | 11        | 9.17%   |
| 141-150        | 8         | 6.67%   |
| Unknown        | 7         | 5.83%   |
| 51-60          | 5         | 4.17%   |
| 251-300        | 5         | 4.17%   |
| 131-140        | 5         | 4.17%   |
| 301-350        | 4         | 3.33%   |
| 121-130        | 4         | 3.33%   |
| 71-80          | 3         | 2.5%    |
| 41-50          | 3         | 2.5%    |
| More than 1000 | 2         | 1.67%   |
| 61-70          | 2         | 1.67%   |
| 351-500        | 1         | 0.83%   |
| 111-120        | 1         | 0.83%   |
| 501-1000       | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 42        | 36.21%  |
| 101-120       | 35        | 30.17%  |
| 121-160       | 25        | 21.55%  |
| Unknown       | 7         | 6.03%   |
| 161-240       | 3         | 2.59%   |
| More than 240 | 2         | 1.72%   |
| 1-50          | 2         | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 105       | 87.5%   |
| 2     | 13        | 10.83%  |
| 3     | 1         | 0.83%   |
| 0     | 1         | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 63        | 34.43%  |
| Intel                                 | 40        | 21.86%  |
| Qualcomm Atheros                      | 28        | 15.3%   |
| Broadcom                              | 17        | 9.29%   |
| Broadcom Limited                      | 5         | 2.73%   |
| Ralink Technology                     | 4         | 2.19%   |
| Ralink                                | 4         | 2.19%   |
| Nvidia                                | 4         | 2.19%   |
| Marvell Technology Group              | 2         | 1.09%   |
| ASUSTek Computer                      | 2         | 1.09%   |
| ASIX Electronics                      | 2         | 1.09%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.55%   |
| TP-Link                               | 1         | 0.55%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.55%   |
| Sierra Wireless                       | 1         | 0.55%   |
| Samsung Electronics                   | 1         | 0.55%   |
| Qualcomm Atheros Communications       | 1         | 0.55%   |
| Microsoft                             | 1         | 0.55%   |
| MediaTek                              | 1         | 0.55%   |
| Linksys                               | 1         | 0.55%   |
| D-Link                                | 1         | 0.55%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.55%   |
| 3Com                                  | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 39        | 18.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 16        | 7.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 2.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 6         | 2.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 5         | 2.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 2.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4         | 1.89%   |
| Intel Wireless 3165                                                                           | 4         | 1.89%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.42%   |
| Ralink MT7601U Wireless Adapter                                                               | 3         | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 1.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 3         | 1.42%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 1.42%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 0.94%   |
| Nvidia MCP77 Ethernet                                                                         | 2         | 0.94%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 0.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 0.94%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2         | 0.94%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                        | 2         | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 0.94%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                                                 | 2         | 0.94%   |
| ZTE WCDMA MSM Spreadtrum Phone                                                                | 1         | 0.47%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 0.47%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY                    | 1         | 0.47%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1         | 0.47%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 0.47%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.47%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 0.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 0.47%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 27        | 27.27%  |
| Qualcomm Atheros                      | 25        | 25.25%  |
| Realtek Semiconductor                 | 19        | 19.19%  |
| Broadcom                              | 7         | 7.07%   |
| Ralink Technology                     | 4         | 4.04%   |
| Ralink                                | 4         | 4.04%   |
| Broadcom Limited                      | 3         | 3.03%   |
| ASUSTek Computer                      | 2         | 2.02%   |
| TP-Link                               | 1         | 1.01%   |
| Sierra Wireless                       | 1         | 1.01%   |
| Qualcomm Atheros Communications       | 1         | 1.01%   |
| Microsoft                             | 1         | 1.01%   |
| MediaTek                              | 1         | 1.01%   |
| Linksys                               | 1         | 1.01%   |
| D-Link                                | 1         | 1.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 1.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 6%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 5         | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 5%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4         | 4%      |
| Intel Wireless 3165                                                                           | 4         | 4%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 3%      |
| Ralink MT7601U Wireless Adapter                                                               | 3         | 3%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 3%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 3%      |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 2%      |
| Intel Wireless 8265 / 8275                                                                    | 2         | 2%      |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2%      |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 2%      |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 1%      |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 1%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1%      |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1%      |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 1%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 1%      |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1         | 1%      |
| Realtek 802.11ac NIC                                                                          | 1         | 1%      |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 1%      |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 1%      |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1%      |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 1%      |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1         | 1%      |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 1%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1%      |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 1%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 59        | 53.64%  |
| Intel                             | 18        | 16.36%  |
| Broadcom                          | 11        | 10%     |
| Qualcomm Atheros                  | 8         | 7.27%   |
| Nvidia                            | 4         | 3.64%   |
| Marvell Technology Group          | 2         | 1.82%   |
| Broadcom Limited                  | 2         | 1.82%   |
| ASIX Electronics                  | 2         | 1.82%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.91%   |
| Sundance Technology Inc / IC Plus | 1         | 0.91%   |
| Samsung Electronics               | 1         | 0.91%   |
| 3Com                              | 1         | 0.91%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 39        | 35.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 16        | 14.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 5.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 3         | 2.7%    |
| Nvidia MCP77 Ethernet                                                         | 2         | 1.8%    |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 1.8%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 1.8%    |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 1.8%    |
| ZTE WCDMA MSM Spreadtrum Phone                                                | 1         | 0.9%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1         | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.9%    |
| Realtek USB 10/100 LAN                                                        | 1         | 0.9%    |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.9%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.9%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.9%    |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.9%    |
| Nvidia MCP51 Ethernet Controller                                              | 1         | 0.9%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.9%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.9%    |
| Intel I211 Gigabit Network Connection                                         | 1         | 0.9%    |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 0.9%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.9%    |
| Intel 82567V-2 Gigabit Network Connection                                     | 1         | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.9%    |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.9%    |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 0.9%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 0.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 0.9%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 0.9%    |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 0.9%    |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express                      | 1         | 0.9%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 104       | 52%     |
| WiFi     | 95        | 47.5%   |
| Unknown  | 1         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 60%     |
| Ethernet | 50        | 40%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 69        | 57.98%  |
| 1     | 43        | 36.13%  |
| 0     | 4         | 3.36%   |
| 3     | 2         | 1.68%   |
| 4     | 1         | 0.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 95        | 79.17%  |
| Yes  | 25        | 20.83%  |

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
| Lite-On Bluetooth Device                            | 3         | 5.17%   |
| Intel Bluetooth Device                              | 3         | 5.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.45%   |
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
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.72%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.72%   |
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
| Intel                 | 87        | 61.7%   |
| AMD                   | 27        | 19.15%  |
| Nvidia                | 18        | 12.77%  |
| Logitech              | 2         | 1.42%   |
| C-Media Electronics   | 2         | 1.42%   |
| Texas Instruments     | 1         | 0.71%   |
| Realtek Semiconductor | 1         | 0.71%   |
| Ensoniq               | 1         | 0.71%   |
| Creative Labs         | 1         | 0.71%   |
| Blue Microphones      | 1         | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 8.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 6.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 4.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 4.32%   |
| AMD FCH Azalia Controller                                                                         | 7         | 4.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.7%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 3.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 3.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 3.09%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5         | 3.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 2.47%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.85%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.85%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.85%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.23%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.23%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.23%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.23%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.62%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1         | 0.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.62%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.62%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 0.62%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.62%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.62%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.62%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.62%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 23        | 20.54%  |
| Samsung Electronics | 19        | 16.96%  |
| SK hynix            | 16        | 14.29%  |
| Kingston            | 13        | 11.61%  |
| Micron Technology   | 12        | 10.71%  |
| Unknown             | 5         | 4.46%   |
| Elpida              | 3         | 2.68%   |
| A-DATA Technology   | 3         | 2.68%   |
| Unknown (ABCD)      | 2         | 1.79%   |
| Ramaxel Technology  | 2         | 1.79%   |
| Nanya Technology    | 2         | 1.79%   |
| Corsair             | 2         | 1.79%   |
| Transcend           | 1         | 0.89%   |
| Qumo                | 1         | 0.89%   |
| Qimonda             | 1         | 0.89%   |
| GeIL                | 1         | 0.89%   |
| G.Skill             | 1         | 0.89%   |
| Avant               | 1         | 0.89%   |
| 2C0C1121390963FE    | 1         | 0.89%   |
| 2C0C1121390963FD    | 1         | 0.89%   |
| 2C0C1121390963F9    | 1         | 0.89%   |
| 2C0C1121390963F8    | 1         | 0.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 4.35%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.74%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.74%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.87%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                          | 1         | 0.87%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.87%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 0.87%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.87%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.87%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.87%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.87%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.87%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.87%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.87%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.87%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.87%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                       | 1         | 0.87%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1         | 0.87%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                            | 1         | 0.87%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                   | 1         | 0.87%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.87%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                    | 1         | 0.87%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.87%   |
| Unknown RAM Module 1024MB DIMM DDR2                              | 1         | 0.87%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                       | 1         | 0.87%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.87%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.87%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s               | 1         | 0.87%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.87%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.87%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 1         | 0.87%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 1         | 0.87%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 0.87%   |
| SK hynix RAM HMT451S6DFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.87%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.87%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.87%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.87%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.87%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.87%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 34        | 36.17%  |
| DDR2    | 20        | 21.28%  |
| DDR4    | 18        | 19.15%  |
| SDRAM   | 9         | 9.57%   |
| Unknown | 5         | 5.32%   |
| LPDDR4  | 4         | 4.26%   |
| DDR     | 3         | 3.19%   |
| DRAM    | 1         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 57        | 62.64%  |
| DIMM    | 33        | 36.26%  |
| FB-DIMM | 1         | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 36        | 35.29%  |
| 4096  | 28        | 27.45%  |
| 8192  | 17        | 16.67%  |
| 1024  | 16        | 15.69%  |
| 16384 | 5         | 4.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 24        | 24.49%  |
| 3200    | 9         | 9.18%   |
| 667     | 9         | 9.18%   |
| 2667    | 8         | 8.16%   |
| 1333    | 8         | 8.16%   |
| Unknown | 8         | 8.16%   |
| 800     | 6         | 6.12%   |
| 2400    | 3         | 3.06%   |
| 975     | 3         | 3.06%   |
| 4199    | 2         | 2.04%   |
| 2048    | 2         | 2.04%   |
| 1334    | 2         | 2.04%   |
| 1066    | 2         | 2.04%   |
| 400     | 2         | 2.04%   |
| 49926   | 1         | 1.02%   |
| 19791   | 1         | 1.02%   |
| 3500    | 1         | 1.02%   |
| 3266    | 1         | 1.02%   |
| 2133    | 1         | 1.02%   |
| 1866    | 1         | 1.02%   |
| 1639    | 1         | 1.02%   |
| 1067    | 1         | 1.02%   |
| 1033    | 1         | 1.02%   |
| 133     | 1         | 1.02%   |

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
| 0     | 91        | 75.83%  |
| 1     | 25        | 20.83%  |
| 2     | 4         | 3.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 24.24%  |
| Graphics card            | 6         | 18.18%  |
| Net/wireless             | 5         | 15.15%  |
| Multimedia controller    | 2         | 6.06%   |
| Chipcard                 | 2         | 6.06%   |
| Bluetooth                | 2         | 6.06%   |
| Unassigned class         | 1         | 3.03%   |
| Storage                  | 1         | 3.03%   |
| Sound                    | 1         | 3.03%   |
| Network                  | 1         | 3.03%   |
| Net/ethernet             | 1         | 3.03%   |
| Dvb card                 | 1         | 3.03%   |
| Communication controller | 1         | 3.03%   |
| Camera                   | 1         | 3.03%   |

