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

Total: 152

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple    | Mac-F2268DAE                | All in one  | [9224597686](https://linux-hardware.org/?probe=9224597686) | Oct 28, 2022 |
| UMAX     | VisionBook 12Wi 64G         | Notebook    | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| HP       | Compaq Presario CQ50        | Notebook    | [8546f55697](https://linux-hardware.org/?probe=8546f55697) | Oct 24, 2022 |
| HP       | Compaq Presario CQ50        | Notebook    | [3b1b5c18c6](https://linux-hardware.org/?probe=3b1b5c18c6) | Oct 24, 2022 |
| Acer     | Aspire 5600                 | Notebook    | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| MSI      | MS-N014                     | Notebook    | [4c41640fd3](https://linux-hardware.org/?probe=4c41640fd3) | Oct 12, 2022 |
| MSI      | MS-N014                     | Notebook    | [3144cac65a](https://linux-hardware.org/?probe=3144cac65a) | Oct 12, 2022 |
| Lenovo   | IdeaPad 100-14IBY 80MH      | Notebook    | [676289f650](https://linux-hardware.org/?probe=676289f650) | Oct 02, 2022 |
| HP       | Compaq 420                  | Notebook    | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP       | 1632                        | Desktop     | [f510159333](https://linux-hardware.org/?probe=f510159333) | Sep 19, 2022 |
| HP       | Presario V6000 (RG289UA#... | Notebook    | [7f0113694a](https://linux-hardware.org/?probe=7f0113694a) | Sep 15, 2022 |
| Apple    | Mac-63001698E7A34814 iMa... | All in one  | [1a999b09ae](https://linux-hardware.org/?probe=1a999b09ae) | Sep 12, 2022 |
| HP       | 1632                        | Desktop     | [f14389b9dd](https://linux-hardware.org/?probe=f14389b9dd) | Sep 10, 2022 |
| Samsung  | X420/X520                   | Notebook    | [a8ca7bb005](https://linux-hardware.org/?probe=a8ca7bb005) | Sep 04, 2022 |
| Fujitsu  | FMVNQ8P6                    | Notebook    | [5e34698f14](https://linux-hardware.org/?probe=5e34698f14) | Aug 28, 2022 |
| Sony     | VAIO                        | All in one  | [3ed1ad79e4](https://linux-hardware.org/?probe=3ed1ad79e4) | Aug 24, 2022 |
| ASUSTek  | UX303LN                     | Notebook    | [63d5525864](https://linux-hardware.org/?probe=63d5525864) | Aug 16, 2022 |
| Inventec | Dell Wyse Thin Client De... | Mini pc     | [86523f9a5f](https://linux-hardware.org/?probe=86523f9a5f) | Aug 11, 2022 |
| Lenovo   | ThinkPad L480 20LS001AMC    | Notebook    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| Apple    | MacBookAir6,1               | Notebook    | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| ASUSTek  | VivoBook 14_ASUS Laptop ... | Notebook    | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| ASUSTek  | M51BC                       | Desktop     | [fd0a9ef1c8](https://linux-hardware.org/?probe=fd0a9ef1c8) | Jul 08, 2022 |
| ASUSTek  | M51BC                       | Desktop     | [cc2f84d5d3](https://linux-hardware.org/?probe=cc2f84d5d3) | Jul 08, 2022 |
| HP       | Pavilion g4                 | Notebook    | [330078dbac](https://linux-hardware.org/?probe=330078dbac) | Jul 04, 2022 |
| ASUSTek  | X555YI                      | Notebook    | [762b96a2de](https://linux-hardware.org/?probe=762b96a2de) | Jul 02, 2022 |
| HP       | EliteBook 8440p             | Notebook    | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| Lenovo   | 103D SDK0J40697 WIN 3305... | Desktop     | [03c6ee002e](https://linux-hardware.org/?probe=03c6ee002e) | Jun 07, 2022 |
| Samsung  | 530XBB                      | Notebook    | [485a99ca42](https://linux-hardware.org/?probe=485a99ca42) | Jun 03, 2022 |
| Acer     | Aspire TC-895 V:1.0         | Desktop     | [19a5c1de8e](https://linux-hardware.org/?probe=19a5c1de8e) | May 29, 2022 |
| Minix    | Z64 V1.2                    | Notebook    | [97525a1dc3](https://linux-hardware.org/?probe=97525a1dc3) | May 27, 2022 |
| Lenovo   | Remore CRB Win8 STD MM D... | Desktop     | [eb96be3541](https://linux-hardware.org/?probe=eb96be3541) | May 24, 2022 |
| Lenovo   | Remore CRB Win8 STD MM D... | Desktop     | [f1a79871f7](https://linux-hardware.org/?probe=f1a79871f7) | May 24, 2022 |
| HP       | 3047h                       | Desktop     | [cc184c817b](https://linux-hardware.org/?probe=cc184c817b) | May 16, 2022 |
| Dell     | Inspiron 16 5620            | Notebook    | [b42e1cf95b](https://linux-hardware.org/?probe=b42e1cf95b) | May 13, 2022 |
| Minix    | Z64 V1.2                    | Notebook    | [8796deded0](https://linux-hardware.org/?probe=8796deded0) | May 12, 2022 |
| Dell     | MXG061                      | Notebook    | [119f6dd774](https://linux-hardware.org/?probe=119f6dd774) | May 09, 2022 |
| Lenovo   | ThinkCentre M91p 4518E2M    | Desktop     | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo   | ThinkCentre M91p 4518E2M    | Desktop     | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| Lenovo   | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [ab553d3a2f](https://linux-hardware.org/?probe=ab553d3a2f) | May 01, 2022 |
| Acer     | Extensa 5220                | Notebook    | [ebbd01171d](https://linux-hardware.org/?probe=ebbd01171d) | May 01, 2022 |
| ASUSTek  | TUF B450-PLUS GAMING        | Desktop     | [f7838121d2](https://linux-hardware.org/?probe=f7838121d2) | Apr 23, 2022 |
| Acer     | Aspire 1410                 | Notebook    | [703c2ec84a](https://linux-hardware.org/?probe=703c2ec84a) | Apr 21, 2022 |
| Lenovo   | ThinkPad T400 6475E13       | Notebook    | [cd49ac8445](https://linux-hardware.org/?probe=cd49ac8445) | Apr 08, 2022 |
| Dell     | 018D1Y A00                  | Desktop     | [0c6fc3cae4](https://linux-hardware.org/?probe=0c6fc3cae4) | Apr 07, 2022 |
| Dell     | MXG061                      | Notebook    | [9c91bd9487](https://linux-hardware.org/?probe=9c91bd9487) | Apr 06, 2022 |
| HP       | 2820h                       | Desktop     | [c4461b3710](https://linux-hardware.org/?probe=c4461b3710) | Apr 04, 2022 |
| Insignia | NS-P11W7100                 | Notebook    | [daa476af8c](https://linux-hardware.org/?probe=daa476af8c) | Mar 28, 2022 |
| Dell     | MXG071                      | Notebook    | [ac0158dcb9](https://linux-hardware.org/?probe=ac0158dcb9) | Mar 27, 2022 |
| Dell     | 0HY9JP A02                  | Desktop     | [693b66ce17](https://linux-hardware.org/?probe=693b66ce17) | Mar 27, 2022 |
| Gigabyte | B450M DS3H-CF               | Desktop     | [badb9dcc14](https://linux-hardware.org/?probe=badb9dcc14) | Mar 26, 2022 |
| Gigabyte | B450M DS3H-CF               | Desktop     | [32115c5548](https://linux-hardware.org/?probe=32115c5548) | Mar 26, 2022 |
| HP       | 15 Notebook PC              | Notebook    | [0f99b7ff76](https://linux-hardware.org/?probe=0f99b7ff76) | Mar 21, 2022 |
| Dell     | 0HY9JP A02                  | Desktop     | [bc850554b2](https://linux-hardware.org/?probe=bc850554b2) | Mar 16, 2022 |
| Foxconn  | 2A8C                        | Desktop     | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| HP       | Compaq CQ45                 | Notebook    | [99286efd08](https://linux-hardware.org/?probe=99286efd08) | Mar 10, 2022 |
| HP       | Laptop 15-dw3xxx            | Notebook    | [2b748962fa](https://linux-hardware.org/?probe=2b748962fa) | Mar 06, 2022 |
| ASUSTek  | 900                         | Notebook    | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Acer     | Aspire A315-53              | Notebook    | [6134bb8cba](https://linux-hardware.org/?probe=6134bb8cba) | Feb 18, 2022 |
| ABIT     | IP35-E                      | Desktop     | [67d9f7e94e](https://linux-hardware.org/?probe=67d9f7e94e) | Feb 17, 2022 |
| Acer     | Aspire 5600                 | Notebook    | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| Pegatron | 2ACB                        | Desktop     | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| HP       | Laptop 15-dw3xxx            | Notebook    | [b596d9fdb1](https://linux-hardware.org/?probe=b596d9fdb1) | Feb 09, 2022 |
| Acer     | Aspire TC-895 V:1.0         | Desktop     | [4fe66f8af6](https://linux-hardware.org/?probe=4fe66f8af6) | Feb 09, 2022 |
| HP       | Compaq nw9440 (EY615ET#A... | Notebook    | [6a5c3254ab](https://linux-hardware.org/?probe=6a5c3254ab) | Jan 30, 2022 |
| HP       | Pavilion dv6500             | Notebook    | [15838ae11b](https://linux-hardware.org/?probe=15838ae11b) | Jan 12, 2022 |
| ASUSTek  | N53Jf                       | Notebook    | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek  | N53Jf                       | Notebook    | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| EVGA     | X58 SLI FTW3 Tylersburg     | Desktop     | [9e4639427d](https://linux-hardware.org/?probe=9e4639427d) | Jan 03, 2022 |
| EVGA     | X58 SLI FTW3 Tylersburg     | Desktop     | [d351220ea5](https://linux-hardware.org/?probe=d351220ea5) | Jan 02, 2022 |
| EVGA     | X58 SLI FTW3 Tylersburg     | Desktop     | [b2786130fb](https://linux-hardware.org/?probe=b2786130fb) | Jan 02, 2022 |
| ASUSTek  | X541SA                      | Notebook    | [26f2eeeefc](https://linux-hardware.org/?probe=26f2eeeefc) | Dec 31, 2021 |
| HP       | Pavilion dv6500             | Notebook    | [978ee4328d](https://linux-hardware.org/?probe=978ee4328d) | Dec 19, 2021 |
| ASRock   | H61M-VG3                    | Desktop     | [392a957541](https://linux-hardware.org/?probe=392a957541) | Dec 17, 2021 |
| Acer     | Aspire 5600                 | Notebook    | [25b1e50c64](https://linux-hardware.org/?probe=25b1e50c64) | Dec 12, 2021 |
| Gigabyte | GA-E350N                    | Desktop     | [10d55dd433](https://linux-hardware.org/?probe=10d55dd433) | Dec 02, 2021 |
| Apple    | Mac-F42386C8 PVT            | All in one  | [64eba568a1](https://linux-hardware.org/?probe=64eba568a1) | Nov 25, 2021 |
| HP       | Compaq 2510p                | Notebook    | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| HP       | Compaq 2510p                | Notebook    | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| Samsung  | 905S3G/906S3G/915S3G/930... | Notebook    | [b7306537cc](https://linux-hardware.org/?probe=b7306537cc) | Nov 10, 2021 |
| Acer     | Aspire 5600                 | Notebook    | [7e2da6d3e9](https://linux-hardware.org/?probe=7e2da6d3e9) | Oct 26, 2021 |
| Dell     | MXG061                      | Notebook    | [89a5b20193](https://linux-hardware.org/?probe=89a5b20193) | Oct 10, 2021 |
| Biostar  | G41D3C                      | Desktop     | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Biostar  | G41D3C                      | Desktop     | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| Acer     | Swift SF314-56              | Notebook    | [263d6e38b7](https://linux-hardware.org/?probe=263d6e38b7) | Oct 01, 2021 |
| Acer     | Swift SF314-56              | Notebook    | [bb0f894bce](https://linux-hardware.org/?probe=bb0f894bce) | Oct 01, 2021 |
| ASUSTek  | M5A78L LE                   | Desktop     | [ddb041ded0](https://linux-hardware.org/?probe=ddb041ded0) | Sep 15, 2021 |
| ASUSTek  | M5A78L LE                   | Desktop     | [a9335318aa](https://linux-hardware.org/?probe=a9335318aa) | Sep 15, 2021 |
| Dell     | Vostro1710                  | Notebook    | [d50123c66a](https://linux-hardware.org/?probe=d50123c66a) | Sep 01, 2021 |
| Dell     | Inspiron 5452               | Notebook    | [0c9b3ec7a9](https://linux-hardware.org/?probe=0c9b3ec7a9) | Aug 07, 2021 |
| Intel    | DG31PR AAD97573-300         | Desktop     | [0a0a8059c2](https://linux-hardware.org/?probe=0a0a8059c2) | Aug 04, 2021 |
| Intel    | DG31PR AAD97573-300         | Desktop     | [6b7f5cdcc8](https://linux-hardware.org/?probe=6b7f5cdcc8) | Jul 21, 2021 |
| HP       | EliteBook Folio 9470m       | Notebook    | [b2b851f7d2](https://linux-hardware.org/?probe=b2b851f7d2) | Jul 12, 2021 |
| ASUSTek  | X541SA                      | Notebook    | [ed8bb15f60](https://linux-hardware.org/?probe=ed8bb15f60) | Jul 11, 2021 |
| HP       | 0A98h                       | Desktop     | [9844591cd4](https://linux-hardware.org/?probe=9844591cd4) | Jul 02, 2021 |
| ECS      | Livermore                   | Desktop     | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| HP       | Laptop 14-cm0xxx            | Notebook    | [5943266aca](https://linux-hardware.org/?probe=5943266aca) | Jun 18, 2021 |
| HP       | Laptop 14-cm0xxx            | Notebook    | [3b4a122b75](https://linux-hardware.org/?probe=3b4a122b75) | Jun 18, 2021 |
| Fujitsu  | LIFEBOOK U747               | Notebook    | [117e8bf660](https://linux-hardware.org/?probe=117e8bf660) | Jun 17, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a9255b2217](https://linux-hardware.org/?probe=a9255b2217) | Jun 04, 2021 |
| MSI      | Boston                      | Desktop     | [5cca21c281](https://linux-hardware.org/?probe=5cca21c281) | Apr 26, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop E203... | Notebook    | [58bf661e8d](https://linux-hardware.org/?probe=58bf661e8d) | Apr 15, 2021 |
| ASUSTek  | K50IE                       | Notebook    | [b0bcc6c31c](https://linux-hardware.org/?probe=b0bcc6c31c) | Apr 12, 2021 |
| MSI      | B75A-G43                    | Desktop     | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| AWOW     | PC BOX                      | Mini pc     | [b9140b8786](https://linux-hardware.org/?probe=b9140b8786) | Mar 29, 2021 |
| ASUSTek  | K54LY                       | Notebook    | [dc7d86f51e](https://linux-hardware.org/?probe=dc7d86f51e) | Mar 21, 2021 |
| Acer     | Aspire V5-552               | Notebook    | [7a32a8a1c3](https://linux-hardware.org/?probe=7a32a8a1c3) | Mar 03, 2021 |
| HP       | Compaq 6735b                | Notebook    | [0f2afbc99a](https://linux-hardware.org/?probe=0f2afbc99a) | Feb 18, 2021 |
| Dell     | Inspiron 7559               | Notebook    | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| HP       | Laptop 17-by2xxx            | Notebook    | [729abf0085](https://linux-hardware.org/?probe=729abf0085) | Jan 30, 2021 |
| Acer     | Predator PH317-52           | Notebook    | [1bd05ad341](https://linux-hardware.org/?probe=1bd05ad341) | Jan 24, 2021 |
| Gigabyte | X570 AORUS MASTER           | Desktop     | [84cb4ded95](https://linux-hardware.org/?probe=84cb4ded95) | Dec 30, 2020 |
| HP       | 655                         | Notebook    | [a6913cacf3](https://linux-hardware.org/?probe=a6913cacf3) | Dec 28, 2020 |
| HP       | 655                         | Notebook    | [2a4c81218e](https://linux-hardware.org/?probe=2a4c81218e) | Dec 27, 2020 |
| Toshiba  | Satellite T215D             | Notebook    | [084f254e1f](https://linux-hardware.org/?probe=084f254e1f) | Dec 23, 2020 |
| Toshiba  | Satellite T215D             | Notebook    | [bdb8fe4e55](https://linux-hardware.org/?probe=bdb8fe4e55) | Dec 23, 2020 |
| Minix    | NEO Z83-4 V1.1              | Desktop     | [19e83c7c24](https://linux-hardware.org/?probe=19e83c7c24) | Dec 21, 2020 |
| Gigabyte | X570 AORUS MASTER           | Desktop     | [77f93a017c](https://linux-hardware.org/?probe=77f93a017c) | Dec 21, 2020 |
| Gigabyte | X570 AORUS MASTER           | Desktop     | [a6654cf4f1](https://linux-hardware.org/?probe=a6654cf4f1) | Dec 21, 2020 |
| Minix    | NEO Z83-4 V1.1              | Desktop     | [8f8f606051](https://linux-hardware.org/?probe=8f8f606051) | Dec 16, 2020 |
| Lenovo   | IdeaPad 320-15ABR 80XS      | Notebook    | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| ASUSTek  | 1001PX                      | Notebook    | [9f911bde1c](https://linux-hardware.org/?probe=9f911bde1c) | Dec 11, 2020 |
| Acer     | Aspire 5750                 | Notebook    | [ba47872fd5](https://linux-hardware.org/?probe=ba47872fd5) | Dec 02, 2020 |
| Acer     | Aspire 5750                 | Notebook    | [c4216f5d80](https://linux-hardware.org/?probe=c4216f5d80) | Dec 02, 2020 |
| HP       | 0ACCh                       | Desktop     | [7f4d2a2df4](https://linux-hardware.org/?probe=7f4d2a2df4) | Nov 23, 2020 |
| HP       | 0ACCh                       | Desktop     | [d28f3f3195](https://linux-hardware.org/?probe=d28f3f3195) | Nov 23, 2020 |
| Lenovo   | ThinkCentre M91p 4524RS6    | Desktop     | [cf9c213443](https://linux-hardware.org/?probe=cf9c213443) | Nov 21, 2020 |
| Lenovo   | ThinkCentre M91p 4524RS6    | Desktop     | [66d1757c3f](https://linux-hardware.org/?probe=66d1757c3f) | Nov 21, 2020 |
| HP       | 3032h                       | Desktop     | [1a10cb8912](https://linux-hardware.org/?probe=1a10cb8912) | Nov 20, 2020 |
| Intel    | H61M-S1                     | Desktop     | [f31ad89e75](https://linux-hardware.org/?probe=f31ad89e75) | Nov 02, 2020 |
| Intel    | H61M-S1                     | Desktop     | [f381b5e487](https://linux-hardware.org/?probe=f381b5e487) | Nov 02, 2020 |
| Lenovo   | ThinkCentre A55 9265BL7     | Desktop     | [1e00064286](https://linux-hardware.org/?probe=1e00064286) | Oct 30, 2020 |
| HP       | 2AA6 PVT                    | Desktop     | [3ee3ed2e83](https://linux-hardware.org/?probe=3ee3ed2e83) | Oct 06, 2020 |
| Dell     | Latitude D530               | Notebook    | [4fe18e86ac](https://linux-hardware.org/?probe=4fe18e86ac) | Sep 27, 2020 |
| MSI      | Z77A-G43                    | Desktop     | [4420c076a7](https://linux-hardware.org/?probe=4420c076a7) | Sep 03, 2020 |
| HP       | x2 Detachable 10-p0XX       | Tablet      | [2a6ae45bc4](https://linux-hardware.org/?probe=2a6ae45bc4) | Aug 20, 2020 |
| ASRock   | N68C-S UCC                  | Desktop     | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASRock   | N68C-S UCC                  | Desktop     | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| Jetway   | I61MG4                      | Desktop     | [f677e427be](https://linux-hardware.org/?probe=f677e427be) | Jul 30, 2020 |
| Jetway   | I61MG4                      | Desktop     | [2e5f79f476](https://linux-hardware.org/?probe=2e5f79f476) | Jul 29, 2020 |
| Lenovo   | MIIX 300-10IBY 80NR         | Tablet      | [cf8c7c6ae6](https://linux-hardware.org/?probe=cf8c7c6ae6) | Jul 29, 2020 |
| Acer     | Aspire ES1-511              | Notebook    | [63a7ae1967](https://linux-hardware.org/?probe=63a7ae1967) | Jul 24, 2020 |
| Google   | Chell                       | Notebook    | [cf727e9a6e](https://linux-hardware.org/?probe=cf727e9a6e) | Jul 23, 2020 |
| ASUSTek  | X751LD                      | Notebook    | [2d9ea757d1](https://linux-hardware.org/?probe=2d9ea757d1) | Jul 14, 2020 |
| ASUSTek  | X751LD                      | Notebook    | [1a4ee704d9](https://linux-hardware.org/?probe=1a4ee704d9) | Jul 14, 2020 |
| Lenovo   | 3000 V200 0764A11           | Notebook    | [8492023ae0](https://linux-hardware.org/?probe=8492023ae0) | Jul 13, 2020 |
| TR       | ST Pro-KN                   | Notebook    | [e78b2937ef](https://linux-hardware.org/?probe=e78b2937ef) | Jul 01, 2020 |
| Acer     | EQ35M                       | Desktop     | [f2dbd9e441](https://linux-hardware.org/?probe=f2dbd9e441) | Jun 23, 2020 |
| Acer     | EQ35M                       | Desktop     | [5ebf9a4f1a](https://linux-hardware.org/?probe=5ebf9a4f1a) | Jun 23, 2020 |
| Foxconn  | 45CMX/45GMX/45CMX-K         | Desktop     | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |
| ASUSTek  | N750JK                      | Notebook    | [9102fbcf41](https://linux-hardware.org/?probe=9102fbcf41) | Jun 02, 2020 |
| Samsung  | NC110P/NC108P/NC111P        | Notebook    | [92c219ffb4](https://linux-hardware.org/?probe=92c219ffb4) | May 14, 2020 |
| ASUSTek  | X540YA                      | Notebook    | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Linux Lite 5.8 | 20        | 18.35%  |
| Linux Lite 6.0 | 17        | 15.6%   |
| Linux Lite 5.0 | 17        | 15.6%   |
| Linux Lite 5.2 | 16        | 14.68%  |
| Linux Lite 5.4 | 15        | 13.76%  |
| Linux Lite 5.6 | 13        | 11.93%  |
| Linux Lite 3.8 | 5         | 4.59%   |
| Linux Lite 4.8 | 2         | 1.83%   |
| Linux Lite 6.2 | 1         | 0.92%   |
| Linux Lite 4.6 | 1         | 0.92%   |
| Linux Lite 4.4 | 1         | 0.92%   |
| Linux Lite 4.2 | 1         | 0.92%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Lite | 108       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 6         | 5.22%   |
| 5.4.0-70-generic  | 5         | 4.35%   |
| 5.4.0-91-generic  | 4         | 3.48%   |
| 5.4.0-52-generic  | 4         | 3.48%   |
| 5.4.0-40-generic  | 4         | 3.48%   |
| 5.4.0-109-generic | 4         | 3.48%   |
| 5.4.0-104-generic | 4         | 3.48%   |
| 5.4.0-96-generic  | 3         | 2.61%   |
| 5.4.0-58-generic  | 3         | 2.61%   |
| 5.4.0-48-generic  | 3         | 2.61%   |
| 5.4.0-113-generic | 3         | 2.61%   |
| 5.4.0-107-generic | 3         | 2.61%   |
| 5.15.0-52-generic | 3         | 2.61%   |
| 5.15.0-47-generic | 3         | 2.61%   |
| 5.15.0-46-generic | 3         | 2.61%   |
| 5.15.0-33-generic | 3         | 2.61%   |
| 5.4.0-90-generic  | 2         | 1.74%   |
| 5.4.0-88-generic  | 2         | 1.74%   |
| 5.4.0-81-generic  | 2         | 1.74%   |
| 5.4.0-80-generic  | 2         | 1.74%   |
| 5.4.0-74-generic  | 2         | 1.74%   |
| 5.4.0-54-generic  | 2         | 1.74%   |
| 5.4.0-33-generic  | 2         | 1.74%   |
| 5.4.0-110-generic | 2         | 1.74%   |
| 5.4.0-105-generic | 2         | 1.74%   |
| 5.15.0-48-generic | 2         | 1.74%   |
| 4.4.0-112-generic | 2         | 1.74%   |
| 6.0.0             | 1         | 0.87%   |
| 5.9.0             | 1         | 0.87%   |
| 5.4.0-99-generic  | 1         | 0.87%   |
| 5.4.0-94-generic  | 1         | 0.87%   |
| 5.4.0-77-generic  | 1         | 0.87%   |
| 5.4.0-72-generic  | 1         | 0.87%   |
| 5.4.0-71-generic  | 1         | 0.87%   |
| 5.4.0-66-generic  | 1         | 0.87%   |
| 5.4.0-65-generic  | 1         | 0.87%   |
| 5.4.0-56-generic  | 1         | 0.87%   |
| 5.4.0-45-generic  | 1         | 0.87%   |
| 5.4.0-37-generic  | 1         | 0.87%   |
| 5.4.0-124-generic | 1         | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 76        | 68.47%  |
| 5.15.0  | 18        | 16.22%  |
| 4.15.0  | 5         | 4.5%    |
| 4.4.0   | 4         | 3.6%    |
| 5.13.0  | 3         | 2.7%    |
| 6.0.0   | 1         | 0.9%    |
| 5.9.0   | 1         | 0.9%    |
| 5.16.9  | 1         | 0.9%    |
| 5.16.0  | 1         | 0.9%    |
| 5.10.0  | 1         | 0.9%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 76        | 68.47%  |
| 5.15    | 18        | 16.22%  |
| 4.15    | 5         | 4.5%    |
| 4.4     | 4         | 3.6%    |
| 5.13    | 3         | 2.7%    |
| 5.16    | 2         | 1.8%    |
| 6.0     | 1         | 0.9%    |
| 5.9     | 1         | 0.9%    |
| 5.10    | 1         | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 104       | 96.3%   |
| i686   | 4         | 3.7%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 80        | 74.07%  |
| GNOME   | 25        | 23.15%  |
| Unknown | 2         | 1.85%   |
| Deepin  | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 106       | 98.15%  |
| Tty     | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 61        | 55.45%  |
| TDM     | 28        | 25.45%  |
| Unknown | 20        | 18.18%  |
| GDM     | 1         | 0.91%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 54        | 50%     |
| de_DE | 7         | 6.48%   |
| pt_BR | 6         | 5.56%   |
| pl_PL | 6         | 5.56%   |
| fr_FR | 6         | 5.56%   |
| en_GB | 5         | 4.63%   |
| ru_UA | 3         | 2.78%   |
| es_MX | 3         | 2.78%   |
| es_ES | 3         | 2.78%   |
| ru_RU | 2         | 1.85%   |
| it_IT | 2         | 1.85%   |
| zh_CN | 1         | 0.93%   |
| tr_TR | 1         | 0.93%   |
| nl_NL | 1         | 0.93%   |
| fr_CA | 1         | 0.93%   |
| es_CO | 1         | 0.93%   |
| es_CL | 1         | 0.93%   |
| en_NZ | 1         | 0.93%   |
| en_IE | 1         | 0.93%   |
| en_CA | 1         | 0.93%   |
| en_AU | 1         | 0.93%   |
| da_DK | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 60        | 55.56%  |
| EFI  | 48        | 44.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 95        | 87.96%  |
| Overlay | 9         | 8.33%   |
| Btrfs   | 2         | 1.85%   |
| Zfs     | 1         | 0.93%   |
| Ext3    | 1         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 41        | 37.96%  |
| Unknown | 36        | 33.33%  |
| MBR     | 31        | 28.7%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 82.41%  |
| Yes       | 19        | 17.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 69.72%  |
| Yes       | 33        | 30.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 23        | 21.3%   |
| ASUSTek Computer    | 15        | 13.89%  |
| Lenovo              | 12        | 11.11%  |
| Acer                | 11        | 10.19%  |
| Dell                | 9         | 8.33%   |
| Samsung Electronics | 4         | 3.7%    |
| MSI                 | 4         | 3.7%    |
| Apple               | 4         | 3.7%    |
| Gigabyte Technology | 3         | 2.78%   |
| Minix               | 2         | 1.85%   |
| Intel               | 2         | 1.85%   |
| Fujitsu             | 2         | 1.85%   |
| Foxconn             | 2         | 1.85%   |
| ASRock              | 2         | 1.85%   |
| UMAX                | 1         | 0.93%   |
| TR                  | 1         | 0.93%   |
| Toshiba             | 1         | 0.93%   |
| Sony                | 1         | 0.93%   |
| Pegatron            | 1         | 0.93%   |
| Jetway              | 1         | 0.93%   |
| Inventec            | 1         | 0.93%   |
| Insignia            | 1         | 0.93%   |
| Google              | 1         | 0.93%   |
| EVGA                | 1         | 0.93%   |
| Biostar             | 1         | 0.93%   |
| AWOW                | 1         | 0.93%   |
| ABIT                | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| MSI MS-7758                            | 2         | 1.85%   |
| UMAX VisionBook 12Wi 64G               | 1         | 0.93%   |
| TR ST Pro-KN                           | 1         | 0.93%   |
| Toshiba Satellite T215D                | 1         | 0.93%   |
| Sony VGC-JS54FB_W                      | 1         | 0.93%   |
| Samsung X420/X520                      | 1         | 0.93%   |
| Samsung NC110P/NC108P/NC111P           | 1         | 0.93%   |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 0.93%   |
| Samsung 530XBB                         | 1         | 0.93%   |
| Pegatron 520-1135la                    | 1         | 0.93%   |
| MSI MS-N014                            | 1         | 0.93%   |
| MSI FZ079AA-ABF a6625fr                | 1         | 0.93%   |
| Minix Z83-4                            | 1         | 0.93%   |
| Minix Z64                              | 1         | 0.93%   |
| Lenovo ThinkStation P320 30BH000BFR    | 1         | 0.93%   |
| Lenovo ThinkPad T400 6475E13           | 1         | 0.93%   |
| Lenovo ThinkPad L480 20LS001AMC        | 1         | 0.93%   |
| Lenovo ThinkCentre M91p 4524RS6        | 1         | 0.93%   |
| Lenovo ThinkCentre M91p 4518E2M        | 1         | 0.93%   |
| Lenovo ThinkCentre A55 9265BL7         | 1         | 0.93%   |
| Lenovo MIIX 300-10IBY 80NR             | 1         | 0.93%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1    | 1         | 0.93%   |
| Lenovo IdeaPad 320-15ABR 80XS          | 1         | 0.93%   |
| Lenovo IdeaPad 100-14IBY 80MH          | 1         | 0.93%   |
| Lenovo H505S 10107                     | 1         | 0.93%   |
| Lenovo 3000 V200 0764A11               | 1         | 0.93%   |
| Jetway I61MG4                          | 1         | 0.93%   |
| Inventec Dell Thin Client Desktop 3290 | 1         | 0.93%   |
| Intel H61M-S1                          | 1         | 0.93%   |
| Intel DG31PR AAD97573-300              | 1         | 0.93%   |
| Insignia NS-P11W7100                   | 1         | 0.93%   |
| HP xw8600 Workstation                  | 1         | 0.93%   |
| HP x2 Detachable 10-p0XX               | 1         | 0.93%   |
| HP t5000 series                        | 1         | 0.93%   |
| HP rp5800                              | 1         | 0.93%   |
| HP Presario V6000 (RG289UA#ABA)        | 1         | 0.93%   |
| HP Pavilion g4                         | 1         | 0.93%   |
| HP Pavilion dv6500                     | 1         | 0.93%   |
| HP Laptop 17-by2xxx                    | 1         | 0.93%   |
| HP Laptop 15-dw3xxx                    | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| HP Compaq            | 8         | 7.41%   |
| Acer Aspire          | 7         | 6.48%   |
| Dell Inspiron        | 4         | 3.7%    |
| Lenovo ThinkCentre   | 3         | 2.78%   |
| Lenovo IdeaPad       | 3         | 2.78%   |
| HP Laptop            | 3         | 2.78%   |
| MSI MS-7758          | 2         | 1.85%   |
| Lenovo ThinkPad      | 2         | 1.85%   |
| HP Pavilion          | 2         | 1.85%   |
| HP EliteBook         | 2         | 1.85%   |
| ASUS VivoBook        | 2         | 1.85%   |
| UMAX VisionBook      | 1         | 0.93%   |
| TR ST                | 1         | 0.93%   |
| Toshiba Satellite    | 1         | 0.93%   |
| Sony VGC-JS54FB      | 1         | 0.93%   |
| Samsung X420         | 1         | 0.93%   |
| Samsung NC110P       | 1         | 0.93%   |
| Samsung 905S3G       | 1         | 0.93%   |
| Samsung 530XBB       | 1         | 0.93%   |
| Pegatron 520-1135la  | 1         | 0.93%   |
| MSI MS-N014          | 1         | 0.93%   |
| MSI FZ079AA-ABF      | 1         | 0.93%   |
| Minix Z83-4          | 1         | 0.93%   |
| Minix Z64            | 1         | 0.93%   |
| Lenovo ThinkStation  | 1         | 0.93%   |
| Lenovo MIIX          | 1         | 0.93%   |
| Lenovo H505S         | 1         | 0.93%   |
| Lenovo 3000          | 1         | 0.93%   |
| Jetway I61MG4        | 1         | 0.93%   |
| Inventec Dell        | 1         | 0.93%   |
| Intel H61M-S1        | 1         | 0.93%   |
| Intel DG31PR         | 1         | 0.93%   |
| Insignia NS-P11W7100 | 1         | 0.93%   |
| HP xw8600            | 1         | 0.93%   |
| HP x2                | 1         | 0.93%   |
| HP t5000             | 1         | 0.93%   |
| HP rp5800            | 1         | 0.93%   |
| HP Presario          | 1         | 0.93%   |
| HP 655               | 1         | 0.93%   |
| HP 200-5320br        | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2008 | 15        | 13.89%  |
| 2011 | 12        | 11.11%  |
| 2010 | 12        | 11.11%  |
| 2012 | 10        | 9.26%   |
| 2018 | 8         | 7.41%   |
| 2014 | 8         | 7.41%   |
| 2007 | 8         | 7.41%   |
| 2020 | 6         | 5.56%   |
| 2016 | 6         | 5.56%   |
| 2015 | 6         | 5.56%   |
| 2019 | 4         | 3.7%    |
| 2017 | 3         | 2.78%   |
| 2009 | 3         | 2.78%   |
| 2021 | 2         | 1.85%   |
| 2006 | 2         | 1.85%   |
| 2022 | 1         | 0.93%   |
| 2013 | 1         | 0.93%   |
| 2004 | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 64        | 59.26%  |
| Desktop    | 36        | 33.33%  |
| All in one | 4         | 3.7%    |
| Tablet     | 2         | 1.85%   |
| Mini pc    | 2         | 1.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 105       | 97.22%  |
| Enabled  | 3         | 2.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 107       | 99.07%  |
| Yes  | 1         | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 36        | 33.33%  |
| 1.01-2.0   | 23        | 21.3%   |
| 4.01-8.0   | 18        | 16.67%  |
| 16.01-24.0 | 12        | 11.11%  |
| 8.01-16.0  | 8         | 7.41%   |
| 32.01-64.0 | 4         | 3.7%    |
| 0.51-1.0   | 4         | 3.7%    |
| 2.01-3.0   | 3         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 55        | 50%     |
| 2.01-3.0  | 20        | 18.18%  |
| 0.51-1.0  | 18        | 16.36%  |
| 3.01-4.0  | 8         | 7.27%   |
| 4.01-8.0  | 5         | 4.55%   |
| 0.01-0.5  | 3         | 2.73%   |
| 8.01-16.0 | 1         | 0.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 77        | 71.3%   |
| 2      | 21        | 19.44%  |
| 3      | 6         | 5.56%   |
| 0      | 2         | 1.85%   |
| 5      | 1         | 0.93%   |
| 4      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 55.56%  |
| Yes       | 48        | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 87.96%  |
| No        | 13        | 12.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 79.63%  |
| No        | 22        | 20.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 50.93%  |
| No        | 53        | 49.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 18        | 16.67%  |
| Brazil      | 11        | 10.19%  |
| Germany     | 8         | 7.41%   |
| France      | 7         | 6.48%   |
| Poland      | 6         | 5.56%   |
| Ukraine     | 5         | 4.63%   |
| UK          | 5         | 4.63%   |
| Romania     | 4         | 3.7%    |
| Mexico      | 4         | 3.7%    |
| Canada      | 4         | 3.7%    |
| Spain       | 3         | 2.78%   |
| Russia      | 3         | 2.78%   |
| Peru        | 3         | 2.78%   |
| Italy       | 3         | 2.78%   |
| Turkey      | 2         | 1.85%   |
| Netherlands | 2         | 1.85%   |
| Chile       | 2         | 1.85%   |
| Australia   | 2         | 1.85%   |
| Venezuela   | 1         | 0.93%   |
| Slovakia    | 1         | 0.93%   |
| Qatar       | 1         | 0.93%   |
| Philippines | 1         | 0.93%   |
| New Zealand | 1         | 0.93%   |
| Myanmar     | 1         | 0.93%   |
| Malaysia    | 1         | 0.93%   |
| Japan       | 1         | 0.93%   |
| Ireland     | 1         | 0.93%   |
| Iran        | 1         | 0.93%   |
| Indonesia   | 1         | 0.93%   |
| Guadeloupe  | 1         | 0.93%   |
| Greenland   | 1         | 0.93%   |
| El Salvador | 1         | 0.93%   |
| Czechia     | 1         | 0.93%   |
| Colombia    | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Pabianice          | 3         | 2.73%   |
| Würzburg          | 2         | 1.82%   |
| Warsaw             | 2         | 1.82%   |
| Sydney             | 2         | 1.82%   |
| Sao Paulo          | 2         | 1.82%   |
| Odessa             | 2         | 1.82%   |
| Lima               | 2         | 1.82%   |
| Kyiv               | 2         | 1.82%   |
| Żywiec            | 1         | 0.91%   |
| Yangon             | 1         | 0.91%   |
| Wiesbaden          | 1         | 0.91%   |
| Wellington         | 1         | 0.91%   |
| Waterbury          | 1         | 0.91%   |
| Washington         | 1         | 0.91%   |
| Wahroonga          | 1         | 0.91%   |
| Voluntari          | 1         | 0.91%   |
| Vinnytsia          | 1         | 0.91%   |
| Varennes-les-Narcy | 1         | 0.91%   |
| Vancouver          | 1         | 0.91%   |
| Valencia           | 1         | 0.91%   |
| Tucape             | 1         | 0.91%   |
| Trujillo           | 1         | 0.91%   |
| Thetford-Mines     | 1         | 0.91%   |
| Teresina           | 1         | 0.91%   |
| Tarragona          | 1         | 0.91%   |
| Svidník           | 1         | 0.91%   |
| Surabaya           | 1         | 0.91%   |
| Studenka           | 1         | 0.91%   |
| St. Petersburg     | 1         | 0.91%   |
| Shadrinsk          | 1         | 0.91%   |
| Sabadell           | 1         | 0.91%   |
| Rio de Janeiro     | 1         | 0.91%   |
| Queretaro          | 1         | 0.91%   |
| Purmerend          | 1         | 0.91%   |
| Porto Velho        | 1         | 0.91%   |
| Porto Alegre       | 1         | 0.91%   |
| Paris              | 1         | 0.91%   |
| Paranaque City     | 1         | 0.91%   |
| Ottawa             | 1         | 0.91%   |
| Ossining           | 1         | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 29     | 20.15%  |
| WDC                 | 24        | 32     | 17.91%  |
| Samsung Electronics | 17        | 18     | 12.69%  |
| Toshiba             | 11        | 12     | 8.21%   |
| Unknown             | 8         | 11     | 5.97%   |
| Kingston            | 8         | 10     | 5.97%   |
| Hitachi             | 5         | 5      | 3.73%   |
| SanDisk             | 4         | 4      | 2.99%   |
| Crucial             | 4         | 4      | 2.99%   |
| Micron Technology   | 3         | 4      | 2.24%   |
| HGST                | 3         | 3      | 2.24%   |
| GOODRAM             | 3         | 3      | 2.24%   |
| Apple               | 2         | 2      | 1.49%   |
| SK hynix            | 1         | 1      | 0.75%   |
| PNY                 | 1         | 1      | 0.75%   |
| Phison              | 1         | 1      | 0.75%   |
| OCZ                 | 1         | 1      | 0.75%   |
| Maxtor              | 1         | 1      | 0.75%   |
| Mass                | 1         | 1      | 0.75%   |
| LITEON              | 1         | 1      | 0.75%   |
| Intel               | 1         | 1      | 0.75%   |
| HPE                 | 1         | 1      | 0.75%   |
| Hewlett-Packard     | 1         | 1      | 0.75%   |
| Gigabyte Technology | 1         | 1      | 0.75%   |
| ASUS-PHISON         | 1         | 2      | 0.75%   |
| ASMT                | 1         | 1      | 0.75%   |
| Apacer              | 1         | 1      | 0.75%   |
| Unknown             | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 3         | 2.1%    |
| Toshiba MQ01ABF050 500GB             | 3         | 2.1%    |
| Seagate ST500DM002-1BD142 500GB      | 3         | 2.1%    |
| Kingston SA400S37240G 240GB SSD      | 3         | 2.1%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 1.4%    |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 1.4%    |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 1.4%    |
| Seagate ST9320325AS 320GB            | 2         | 1.4%    |
| Micron MTFDDAK256MAM-1K12 256GB SSD  | 2         | 1.4%    |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.7%    |
| WDC WDS250G2B0A 250GB SSD            | 1         | 0.7%    |
| WDC WD800JD-60LSA0 80GB              | 1         | 0.7%    |
| WDC WD5000LPCX-75VHAT0 500GB         | 1         | 0.7%    |
| WDC WD5000AAKX-003CA0 500GB          | 1         | 0.7%    |
| WDC WD5000AAKS-60WWPA0 500GB         | 1         | 0.7%    |
| WDC WD5000AACS-00G8B1 500GB          | 1         | 0.7%    |
| WDC WD2500BEVS-00UST0 250GB          | 1         | 0.7%    |
| WDC WD2500BEVE-00A0HT0 250GB         | 1         | 0.7%    |
| WDC WD20PURX-64PFUY0 2TB             | 1         | 0.7%    |
| WDC WD2005FBYZ-01YCBB2 2TB           | 1         | 0.7%    |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.7%    |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.7%    |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.7%    |
| WDC WD10EZEX-07WN4A0 1TB             | 1         | 0.7%    |
| WDC WD10EADS-00L5B1 1TB              | 1         | 0.7%    |
| WDC WD1003FBYX-01Y7B1 1TB            | 1         | 0.7%    |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB   | 1         | 0.7%    |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.7%    |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.7%    |
| Unknown SLD64G  64GB                 | 1         | 0.7%    |
| Unknown SD64G  64GB                  | 1         | 0.7%    |
| Unknown SD16G  16GB                  | 1         | 0.7%    |
| Unknown SC64G  64GB                  | 1         | 0.7%    |
| Unknown NCard  32GB                  | 1         | 0.7%    |
| Unknown HBG4a2  32GB                 | 1         | 0.7%    |
| Unknown DA4064  64GB                 | 1         | 0.7%    |
| Unknown BGND3R  32GB                 | 1         | 0.7%    |
| Toshiba MQ04ABF100 1TB               | 1         | 0.7%    |
| Toshiba MQ01ABD100 1TB               | 1         | 0.7%    |
| Toshiba MQ01ABD050 500GB             | 1         | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 29     | 38.57%  |
| WDC                 | 18        | 22     | 25.71%  |
| Toshiba             | 11        | 12     | 15.71%  |
| Hitachi             | 5         | 5      | 7.14%   |
| Samsung Electronics | 3         | 4      | 4.29%   |
| HGST                | 3         | 3      | 4.29%   |
| Maxtor              | 1         | 1      | 1.43%   |
| ASMT                | 1         | 1      | 1.43%   |
| Apple               | 1         | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 20.93%  |
| Kingston            | 7         | 9      | 16.28%  |
| WDC                 | 4         | 5      | 9.3%    |
| Crucial             | 4         | 4      | 9.3%    |
| SanDisk             | 3         | 3      | 6.98%   |
| Micron Technology   | 3         | 4      | 6.98%   |
| GOODRAM             | 3         | 3      | 6.98%   |
| SK hynix            | 1         | 1      | 2.33%   |
| PNY                 | 1         | 1      | 2.33%   |
| OCZ                 | 1         | 1      | 2.33%   |
| LITEON              | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| Hewlett-Packard     | 1         | 1      | 2.33%   |
| Gigabyte Technology | 1         | 1      | 2.33%   |
| ASUS-PHISON         | 1         | 2      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |
| Apacer              | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 63        | 78     | 50.4%   |
| SSD     | 41        | 48     | 32.8%   |
| MMC     | 10        | 13     | 8%      |
| NVMe    | 9         | 12     | 7.2%    |
| Unknown | 2         | 2      | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 91        | 123    | 79.13%  |
| MMC  | 10        | 13     | 8.7%    |
| NVMe | 9         | 12     | 7.83%   |
| SAS  | 5         | 5      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 96     | 72.82%  |
| 0.51-1.0   | 23        | 24     | 22.33%  |
| 1.01-2.0   | 4         | 5      | 3.88%   |
| 3.01-4.0   | 1         | 1      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 31.19%  |
| 251-500        | 23        | 21.1%   |
| 51-100         | 17        | 15.6%   |
| 1-20           | 10        | 9.17%   |
| 21-50          | 9         | 8.26%   |
| 501-1000       | 8         | 7.34%   |
| More than 3000 | 5         | 4.59%   |
| 1001-2000      | 3         | 2.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 58        | 52.73%  |
| 21-50     | 24        | 21.82%  |
| 51-100    | 11        | 10%     |
| 101-250   | 8         | 7.27%   |
| 251-500   | 3         | 2.73%   |
| 2001-3000 | 2         | 1.82%   |
| 1001-2000 | 2         | 1.82%   |
| 501-1000  | 2         | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 4.76%   |
| WDC WD800JD-60LSA0 80GB                        | 1         | 1      | 4.76%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 4.76%   |
| WDC WD5000AAKS-60WWPA0 500GB                   | 1         | 1      | 4.76%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 4.76%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 4.76%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 4.76%   |
| Seagate ST980811AS 80GB                        | 1         | 1      | 4.76%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 4.76%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 4.76%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 4.76%   |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 4.76%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 4.76%   |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 4.76%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 4.76%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 4.76%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 4.76%   |
| Hitachi HDS721616PLA380 160GB                  | 1         | 1      | 4.76%   |
| Apacer 16GB SATA Flash Drive SSD               | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 33.33%  |
| WDC                 | 6         | 6      | 28.57%  |
| Hitachi             | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| Apacer              | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 38.89%  |
| WDC                 | 5         | 5      | 27.78%  |
| Hitachi             | 3         | 3      | 16.67%  |
| Toshiba             | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 18     | 84.21%  |
| SSD  | 3         | 3      | 15.79%  |

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
| Works    | 49        | 63     | 43.75%  |
| Detected | 44        | 69     | 39.29%  |
| Malfunc  | 19        | 21     | 16.96%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 77        | 68.14%  |
| AMD                         | 17        | 15.04%  |
| Samsung Electronics         | 5         | 4.42%   |
| Nvidia                      | 4         | 3.54%   |
| SanDisk                     | 3         | 2.65%   |
| Marvell Technology Group    | 2         | 1.77%   |
| Phison Electronics          | 1         | 0.88%   |
| LSI Logic / Symbios Logic   | 1         | 0.88%   |
| Kingston Technology Company | 1         | 0.88%   |
| JMicron Technology          | 1         | 0.88%   |
| Broadcom / LSI              | 1         | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11        | 7.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 5.44%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 4.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 4.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 3.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 3.4%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 2.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 2.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 2.04%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3         | 2.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.36%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.36%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.36%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1.36%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.36%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.36%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 1.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 1.36%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.36%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.68%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.68%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.68%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 73        | 59.35%  |
| IDE  | 36        | 29.27%  |
| NVMe | 9         | 7.32%   |
| RAID | 4         | 3.25%   |
| SCSI | 1         | 0.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 88        | 81.48%  |
| AMD    | 20        | 18.52%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 2.78%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 1.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 1.85%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 1.85%   |
| Intel Core 2 CPU T7600 @ 2.33GHz            | 2         | 1.85%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 1.85%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.85%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 0.93%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 0.93%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.93%   |
| Intel Pentium D CPU 3.40GHz                 | 1         | 0.93%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.93%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.93%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.93%   |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1         | 0.93%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.93%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.93%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 0.93%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.93%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.93%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.93%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.93%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 0.93%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1         | 0.93%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.93%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.93%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1         | 0.93%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 0.93%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 0.93%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 0.93%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1         | 0.93%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1         | 0.93%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 15        | 13.89%  |
| Intel Core 2 Duo        | 13        | 12.04%  |
| Intel Core i3           | 10        | 9.26%   |
| Intel Celeron           | 9         | 8.33%   |
| Intel Atom              | 9         | 8.33%   |
| Intel Core i7           | 8         | 7.41%   |
| Intel Pentium Dual-Core | 5         | 4.63%   |
| Intel Pentium           | 5         | 4.63%   |
| Other                   | 3         | 2.78%   |
| Intel Xeon              | 2         | 1.85%   |
| Intel Genuine           | 2         | 1.85%   |
| Intel Core 2            | 2         | 1.85%   |
| AMD Turion 64 X2 Mobile | 2         | 1.85%   |
| AMD E2                  | 2         | 1.85%   |
| AMD E                   | 2         | 1.85%   |
| AMD A8                  | 2         | 1.85%   |
| Intel Pentium Dual      | 1         | 0.93%   |
| Intel Pentium D         | 1         | 0.93%   |
| Intel Core m7           | 1         | 0.93%   |
| Intel Core 2 Extreme    | 1         | 0.93%   |
| Intel Celeron M         | 1         | 0.93%   |
| AMD Turion Dual-Core    | 1         | 0.93%   |
| AMD Ryzen 9             | 1         | 0.93%   |
| AMD Ryzen 5             | 1         | 0.93%   |
| AMD Ryzen 3             | 1         | 0.93%   |
| AMD Quad-Core           | 1         | 0.93%   |
| AMD Phenom II X2        | 1         | 0.93%   |
| AMD FX                  | 1         | 0.93%   |
| AMD Athlon II X2        | 1         | 0.93%   |
| AMD Athlon II Neo       | 1         | 0.93%   |
| AMD A6                  | 1         | 0.93%   |
| AMD A12                 | 1         | 0.93%   |
| AMD A10                 | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 63        | 58.33%  |
| 4      | 32        | 29.63%  |
| 1      | 6         | 5.56%   |
| 6      | 4         | 3.7%    |
| 12     | 1         | 0.93%   |
| 10     | 1         | 0.93%   |
| 8      | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 107       | 99.07%  |
| 2      | 1         | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 69        | 63.89%  |
| 2      | 39        | 36.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 106       | 98.15%  |
| 32-bit         | 2         | 1.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 12        | 11.11%  |
| 0x206a7    | 10        | 9.26%   |
| Unknown    | 10        | 9.26%   |
| 0x30678    | 6         | 5.56%   |
| 0x6fd      | 4         | 3.7%    |
| 0x406c4    | 4         | 3.7%    |
| 0x10676    | 4         | 3.7%    |
| 0x6fb      | 3         | 2.78%   |
| 0x40651    | 3         | 2.78%   |
| 0x306a9    | 3         | 2.78%   |
| 0x20655    | 3         | 2.78%   |
| 0x010000c8 | 3         | 2.78%   |
| 0x806ea    | 2         | 1.85%   |
| 0x806e9    | 2         | 1.85%   |
| 0x806c1    | 2         | 1.85%   |
| 0x6f6      | 2         | 1.85%   |
| 0x506c9    | 2         | 1.85%   |
| 0x406c3    | 2         | 1.85%   |
| 0x106ca    | 2         | 1.85%   |
| 0x05000119 | 2         | 1.85%   |
| 0xf64      | 1         | 0.93%   |
| 0xa0653    | 1         | 0.93%   |
| 0x906eb    | 1         | 0.93%   |
| 0x906ea    | 1         | 0.93%   |
| 0x906e9    | 1         | 0.93%   |
| 0x906a4    | 1         | 0.93%   |
| 0x806ec    | 1         | 0.93%   |
| 0x806eb    | 1         | 0.93%   |
| 0x706a1    | 1         | 0.93%   |
| 0x6fa      | 1         | 0.93%   |
| 0x6d8      | 1         | 0.93%   |
| 0x506e3    | 1         | 0.93%   |
| 0x406e3    | 1         | 0.93%   |
| 0x306c3    | 1         | 0.93%   |
| 0x30661    | 1         | 0.93%   |
| 0x206c2    | 1         | 0.93%   |
| 0x08701013 | 1         | 0.93%   |
| 0x0810100b | 1         | 0.93%   |
| 0x0800820d | 1         | 0.93%   |
| 0x07030105 | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 17        | 15.74%  |
| Silvermont       | 12        | 11.11%  |
| SandyBridge      | 10        | 9.26%   |
| KabyLake         | 10        | 9.26%   |
| Core             | 10        | 9.26%   |
| IvyBridge        | 5         | 4.63%   |
| Westmere         | 4         | 3.7%    |
| Haswell          | 4         | 3.7%    |
| K10              | 3         | 2.78%   |
| Bonnell          | 3         | 2.78%   |
| Bobcat           | 3         | 2.78%   |
| TigerLake        | 2         | 1.85%   |
| Skylake          | 2         | 1.85%   |
| Puma             | 2         | 1.85%   |
| Piledriver       | 2         | 1.85%   |
| P6               | 2         | 1.85%   |
| K8 Hammer        | 2         | 1.85%   |
| Goldmont         | 2         | 1.85%   |
| Excavator        | 2         | 1.85%   |
| Zen+             | 1         | 0.93%   |
| Zen 2            | 1         | 0.93%   |
| Zen              | 1         | 0.93%   |
| NetBurst         | 1         | 0.93%   |
| Nehalem          | 1         | 0.93%   |
| K8 & K10 hybrid  | 1         | 0.93%   |
| K10 Llano        | 1         | 0.93%   |
| Jaguar           | 1         | 0.93%   |
| Goldmont plus    | 1         | 0.93%   |
| CometLake        | 1         | 0.93%   |
| Alderlake Hybrid | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 67        | 58.26%  |
| Nvidia | 25        | 21.74%  |
| AMD    | 23        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 4.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 4.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 4.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 4.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 4.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 4.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.42%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.61%   |
| Intel HD Graphics 500                                                                    | 2         | 1.61%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.61%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 1.61%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.61%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 1.61%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.81%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.81%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.81%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.81%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.81%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.81%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.81%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.81%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.81%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 0.81%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 0.81%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1         | 0.81%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 0.81%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 0.81%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1         | 0.81%   |
| Nvidia G84 [GeForce 8400 GS]                                                             | 1         | 0.81%   |
| Nvidia G72 [GeForce 7300 GS]                                                             | 1         | 0.81%   |
| Nvidia G71M [GeForce Go 7950 GTX]                                                        | 1         | 0.81%   |
| Nvidia G71GLM [Quadro FX 1500M]                                                          | 1         | 0.81%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 60        | 55.56%  |
| 1 x AMD        | 20        | 18.52%  |
| 1 x Nvidia     | 18        | 16.67%  |
| Intel + Nvidia | 7         | 6.48%   |
| 2 x AMD        | 3         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 93        | 85.32%  |
| Proprietary | 14        | 12.84%  |
| Unknown     | 2         | 1.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 58.33%  |
| 0.01-0.5   | 26        | 24.07%  |
| 1.01-2.0   | 7         | 6.48%   |
| 0.51-1.0   | 7         | 6.48%   |
| 3.01-4.0   | 3         | 2.78%   |
| 5.01-6.0   | 2         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 19        | 17.43%  |
| AU Optronics            | 13        | 11.93%  |
| LG Display              | 10        | 9.17%   |
| Hewlett-Packard         | 8         | 7.34%   |
| BOE                     | 7         | 6.42%   |
| Goldstar                | 6         | 5.5%    |
| Chimei Innolux          | 6         | 5.5%    |
| Chi Mei Optoelectronics | 6         | 5.5%    |
| Acer                    | 5         | 4.59%   |
| NEC Computers           | 3         | 2.75%   |
| Apple                   | 3         | 2.75%   |
| ViewSonic               | 2         | 1.83%   |
| Sony                    | 2         | 1.83%   |
| LG Philips              | 2         | 1.83%   |
| HannStar                | 2         | 1.83%   |
| CPT                     | 2         | 1.83%   |
| Ancor Communications    | 2         | 1.83%   |
| Seiko/Epson             | 1         | 0.92%   |
| SANYO                   | 1         | 0.92%   |
| Philips                 | 1         | 0.92%   |
| PANDA                   | 1         | 0.92%   |
| MSI                     | 1         | 0.92%   |
| Lenovo                  | 1         | 0.92%   |
| Hitachi                 | 1         | 0.92%   |
| eMachines               | 1         | 0.92%   |
| BenQ                    | 1         | 0.92%   |
| AOC                     | 1         | 0.92%   |
| Unknown                 | 1         | 0.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.75%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.75%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1         | 0.88%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1         | 0.88%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1         | 0.88%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.88%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                   | 1         | 0.88%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.88%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch  | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 0.88%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1         | 0.88%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.88%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.88%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1         | 0.88%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3155 1366x768 293x165mm 13.2-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1         | 0.88%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                    | 1         | 0.88%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 0.88%   |
| NEC Computers LCD1990SXi NEC66AC 1280x1024 376x301mm 19.0-inch        | 1         | 0.88%   |
| NEC Computers EA244WMi NEC68D7 1920x1200 519x324mm 24.1-inch          | 1         | 0.88%   |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch            | 1         | 0.88%   |
| MSI G271 MSI3CB5 1920x1080 598x336mm 27.0-inch                        | 1         | 0.88%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch           | 1         | 0.88%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 33        | 30.28%  |
| 1920x1080 (FHD)    | 27        | 24.77%  |
| 1920x1200 (WUXGA)  | 10        | 9.17%   |
| 1280x800 (WXGA)    | 8         | 7.34%   |
| 3840x2160 (4K)     | 6         | 5.5%    |
| 1600x900 (HD+)     | 4         | 3.67%   |
| 1440x900 (WXGA+)   | 4         | 3.67%   |
| 1280x1024 (SXGA)   | 4         | 3.67%   |
| 1680x1050 (WSXGA+) | 3         | 2.75%   |
| 1024x600           | 2         | 1.83%   |
| Unknown            | 2         | 1.83%   |
| 5280x1080          | 1         | 0.92%   |
| 3840x2400          | 1         | 0.92%   |
| 2560x1440 (QHD)    | 1         | 0.92%   |
| 1360x768           | 1         | 0.92%   |
| 1280x720 (HD)      | 1         | 0.92%   |
| 1024x768 (XGA)     | 1         | 0.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 21.82%  |
| 17      | 10        | 9.09%   |
| 14      | 9         | 8.18%   |
| 13      | 9         | 8.18%   |
| 24      | 7         | 6.36%   |
| 21      | 7         | 6.36%   |
| Unknown | 7         | 6.36%   |
| 23      | 5         | 4.55%   |
| 19      | 5         | 4.55%   |
| 18      | 5         | 4.55%   |
| 11      | 5         | 4.55%   |
| 27      | 3         | 2.73%   |
| 20      | 3         | 2.73%   |
| 10      | 3         | 2.73%   |
| 12      | 2         | 1.82%   |
| 72      | 1         | 0.91%   |
| 65      | 1         | 0.91%   |
| 46      | 1         | 0.91%   |
| 28      | 1         | 0.91%   |
| 22      | 1         | 0.91%   |
| 16      | 1         | 0.91%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 39.45%  |
| 401-500     | 18        | 16.51%  |
| 501-600     | 15        | 13.76%  |
| 201-300     | 13        | 11.93%  |
| 351-400     | 9         | 8.26%   |
| Unknown     | 7         | 6.42%   |
| 1001-1500   | 2         | 1.83%   |
| 601-700     | 1         | 0.92%   |
| 1501-2000   | 1         | 0.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 68        | 66.02%  |
| 16/10   | 24        | 23.3%   |
| 5/4     | 5         | 4.85%   |
| Unknown | 5         | 4.85%   |
| 4/3     | 1         | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 21.82%  |
| 81-90          | 15        | 13.64%  |
| 201-250        | 13        | 11.82%  |
| 151-200        | 11        | 10%     |
| 141-150        | 7         | 6.36%   |
| Unknown        | 7         | 6.36%   |
| 51-60          | 5         | 4.55%   |
| 251-300        | 5         | 4.55%   |
| 131-140        | 4         | 3.64%   |
| 71-80          | 3         | 2.73%   |
| 41-50          | 3         | 2.73%   |
| 301-350        | 3         | 2.73%   |
| 121-130        | 3         | 2.73%   |
| More than 1000 | 2         | 1.82%   |
| 61-70          | 2         | 1.82%   |
| 351-500        | 1         | 0.91%   |
| 111-120        | 1         | 0.91%   |
| 501-1000       | 1         | 0.91%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 38        | 35.85%  |
| 101-120       | 31        | 29.25%  |
| 121-160       | 23        | 21.7%   |
| Unknown       | 7         | 6.6%    |
| 161-240       | 3         | 2.83%   |
| More than 240 | 2         | 1.89%   |
| 1-50          | 2         | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 95        | 87.16%  |
| 2     | 12        | 11.01%  |
| 3     | 1         | 0.92%   |
| 0     | 1         | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 55        | 33.33%  |
| Intel                                 | 38        | 23.03%  |
| Qualcomm Atheros                      | 26        | 15.76%  |
| Broadcom                              | 17        | 10.3%   |
| Broadcom Limited                      | 5         | 3.03%   |
| Ralink Technology                     | 4         | 2.42%   |
| Ralink                                | 3         | 1.82%   |
| Nvidia                                | 3         | 1.82%   |
| Marvell Technology Group              | 2         | 1.21%   |
| ASIX Electronics                      | 2         | 1.21%   |
| TP-Link                               | 1         | 0.61%   |
| Sierra Wireless                       | 1         | 0.61%   |
| Samsung Electronics                   | 1         | 0.61%   |
| Qualcomm Atheros Communications       | 1         | 0.61%   |
| Microsoft                             | 1         | 0.61%   |
| Linksys                               | 1         | 0.61%   |
| D-Link                                | 1         | 0.61%   |
| ASUSTek Computer                      | 1         | 0.61%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.61%   |
| 3Com                                  | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 18.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 7.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 2.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 2.08%   |
| Intel Wireless 3165                                               | 4         | 2.08%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 4         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.56%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.56%   |
| Realtek 802.11ac WLAN Adapter                                     | 2         | 1.04%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.04%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.04%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 1.04%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.04%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 2         | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.04%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                           | 1         | 0.52%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.52%   |
| Realtek USB 10/100 LAN                                            | 1         | 0.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.52%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.52%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.52%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.52%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 1         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.52%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 25        | 27.78%  |
| Qualcomm Atheros                      | 24        | 26.67%  |
| Realtek Semiconductor                 | 16        | 17.78%  |
| Broadcom                              | 7         | 7.78%   |
| Ralink Technology                     | 4         | 4.44%   |
| Ralink                                | 3         | 3.33%   |
| Broadcom Limited                      | 3         | 3.33%   |
| TP-Link                               | 1         | 1.11%   |
| Sierra Wireless                       | 1         | 1.11%   |
| Qualcomm Atheros Communications       | 1         | 1.11%   |
| Microsoft                             | 1         | 1.11%   |
| Linksys                               | 1         | 1.11%   |
| D-Link                                | 1         | 1.11%   |
| ASUSTek Computer                      | 1         | 1.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 5.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 4.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 4.44%   |
| Intel Wireless 3165                                                     | 4         | 4.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.33%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 3.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 3.33%   |
| Realtek 802.11ac WLAN Adapter                                           | 2         | 2.22%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.22%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 2.22%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                 | 1         | 1.11%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 1.11%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.11%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.11%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.11%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.11%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 1.11%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.11%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 1         | 1.11%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.11%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 1.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.11%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.11%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 1.11%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 1.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.11%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express) | 1         | 1.11%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 1.11%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 1.11%   |
| Intel Wireless 7265                                                     | 1         | 1.11%   |
| Intel Wireless 7260                                                     | 1         | 1.11%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 53%     |
| Intel                    | 18        | 18%     |
| Broadcom                 | 11        | 11%     |
| Qualcomm Atheros         | 7         | 7%      |
| Nvidia                   | 3         | 3%      |
| Marvell Technology Group | 2         | 2%      |
| Broadcom Limited         | 2         | 2%      |
| ASIX Electronics         | 2         | 2%      |
| Samsung Electronics      | 1         | 1%      |
| 3Com                     | 1         | 1%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 35        | 34.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 15        | 14.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 5.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 1.98%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 1.98%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 1.98%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 2         | 1.98%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.99%   |
| Realtek USB 10/100 LAN                                                        | 1         | 0.99%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.99%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.99%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.99%   |
| Nvidia MCP77 Ethernet                                                         | 1         | 0.99%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.99%   |
| Nvidia MCP51 Ethernet Controller                                              | 1         | 0.99%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.99%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.99%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 0.99%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 0.99%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.99%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1         | 0.99%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.99%   |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 0.99%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 0.99%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 0.99%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 0.99%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 0.99%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express                      | 1         | 0.99%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 0.99%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 0.99%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 1         | 0.99%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 95        | 52.2%   |
| WiFi     | 86        | 47.25%  |
| Unknown  | 1         | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 68        | 60.18%  |
| Ethernet | 45        | 39.82%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 64        | 59.26%  |
| 1     | 38        | 35.19%  |
| 0     | 3         | 2.78%   |
| 3     | 2         | 1.85%   |
| 4     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 88        | 80.73%  |
| Yes  | 21        | 19.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 29.09%  |
| Realtek Semiconductor           | 7         | 12.73%  |
| Lite-On Technology              | 4         | 7.27%   |
| IMC Networks                    | 4         | 7.27%   |
| Hewlett-Packard                 | 4         | 7.27%   |
| Cambridge Silicon Radio         | 4         | 7.27%   |
| Broadcom                        | 4         | 7.27%   |
| Qualcomm Atheros Communications | 3         | 5.45%   |
| Apple                           | 3         | 5.45%   |
| Dell                            | 2         | 3.64%   |
| Toshiba                         | 1         | 1.82%   |
| Ralink                          | 1         | 1.82%   |
| Foxconn / Hon Hai               | 1         | 1.82%   |
| Chicony Electronics             | 1         | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 14.55%  |
| Realtek Bluetooth Radio                             | 4         | 7.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 7.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 3.64%   |
| IMC Networks Bluetooth Device                       | 2         | 3.64%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 3.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 3.64%   |
| Dell Wireless 355 Bluetooth                         | 2         | 3.64%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 3.64%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.82%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.82%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.82%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.82%   |
| Lite-On Bluetooth Device                            | 1         | 1.82%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.82%   |
| Intel Bluetooth Device                              | 1         | 1.82%   |
| Intel AX201 Bluetooth                               | 1         | 1.82%   |
| Intel AX200 Bluetooth                               | 1         | 1.82%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.82%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.82%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.82%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 1.82%   |
| Broadcom HP Portable Valentine                      | 1         | 1.82%   |
| Broadcom HP Bluethunder                             | 1         | 1.82%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.82%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.82%   |
| Apple Bluetooth HCI                                 | 1         | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 81        | 63.78%  |
| AMD                   | 24        | 18.9%   |
| Nvidia                | 13        | 10.24%  |
| Logitech              | 2         | 1.57%   |
| C-Media Electronics   | 2         | 1.57%   |
| Texas Instruments     | 1         | 0.79%   |
| Realtek Semiconductor | 1         | 0.79%   |
| Ensoniq               | 1         | 0.79%   |
| Creative Labs         | 1         | 0.79%   |
| Blue Microphones      | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 8.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 6.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 5.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 4.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.14%   |
| AMD FCH Azalia Controller                                                                         | 6         | 4.14%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 3.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 3.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 2.76%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 2.07%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.07%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 2.07%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 2.07%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.38%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.38%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.38%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.69%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1         | 0.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.69%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.69%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.69%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.69%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.69%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Logitech Wireless Headset                                                                         | 1         | 0.69%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 20        | 19.61%  |
| Samsung Electronics | 18        | 17.65%  |
| SK hynix            | 14        | 13.73%  |
| Micron Technology   | 12        | 11.76%  |
| Kingston            | 11        | 10.78%  |
| Unknown             | 5         | 4.9%    |
| Elpida              | 3         | 2.94%   |
| Unknown (ABCD)      | 2         | 1.96%   |
| Ramaxel Technology  | 2         | 1.96%   |
| Nanya Technology    | 2         | 1.96%   |
| A-DATA Technology   | 2         | 1.96%   |
| Transcend           | 1         | 0.98%   |
| Qumo                | 1         | 0.98%   |
| Qimonda             | 1         | 0.98%   |
| GeIL                | 1         | 0.98%   |
| G.Skill             | 1         | 0.98%   |
| Corsair             | 1         | 0.98%   |
| Avant               | 1         | 0.98%   |
| 2C0C1121390963FE    | 1         | 0.98%   |
| 2C0C1121390963FD    | 1         | 0.98%   |
| 2C0C1121390963F9    | 1         | 0.98%   |
| 2C0C1121390963F8    | 1         | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 4.76%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.9%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.9%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.95%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                          | 1         | 0.95%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.95%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.95%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.95%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.95%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.95%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.95%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.95%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.95%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                       | 1         | 0.95%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1         | 0.95%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                            | 1         | 0.95%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                   | 1         | 0.95%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.95%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                    | 1         | 0.95%   |
| Unknown RAM Module 1024MB DIMM DDR2                              | 1         | 0.95%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                       | 1         | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s     | 1         | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.95%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s               | 1         | 0.95%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.95%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.95%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 1         | 0.95%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 1         | 0.95%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.95%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s             | 1         | 0.95%   |
| SK hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s             | 1         | 0.95%   |
| SK hynix RAM H5TC4G63CFR-PBA 2GB SODIMM DDR3 1600MT/s            | 1         | 0.95%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 31        | 36.05%  |
| DDR2    | 18        | 20.93%  |
| DDR4    | 16        | 18.6%   |
| SDRAM   | 8         | 9.3%    |
| Unknown | 5         | 5.81%   |
| LPDDR4  | 4         | 4.65%   |
| DDR     | 3         | 3.49%   |
| DRAM    | 1         | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 53        | 63.86%  |
| DIMM    | 29        | 34.94%  |
| FB-DIMM | 1         | 1.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 32        | 34.78%  |
| 4096  | 26        | 28.26%  |
| 8192  | 16        | 17.39%  |
| 1024  | 15        | 16.3%   |
| 16384 | 3         | 3.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 22        | 25%     |
| 667     | 9         | 10.23%  |
| 2667    | 8         | 9.09%   |
| 3200    | 7         | 7.95%   |
| Unknown | 7         | 7.95%   |
| 1333    | 6         | 6.82%   |
| 800     | 4         | 4.55%   |
| 2400    | 3         | 3.41%   |
| 975     | 3         | 3.41%   |
| 4199    | 2         | 2.27%   |
| 2048    | 2         | 2.27%   |
| 1066    | 2         | 2.27%   |
| 400     | 2         | 2.27%   |
| 49926   | 1         | 1.14%   |
| 19791   | 1         | 1.14%   |
| 3500    | 1         | 1.14%   |
| 3266    | 1         | 1.14%   |
| 2133    | 1         | 1.14%   |
| 1866    | 1         | 1.14%   |
| 1639    | 1         | 1.14%   |
| 1334    | 1         | 1.14%   |
| 1067    | 1         | 1.14%   |
| 1033    | 1         | 1.14%   |
| 133     | 1         | 1.14%   |

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


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 CU | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 17        | 26.56%  |
| Suyin                                  | 5         | 7.81%   |
| Quanta                                 | 5         | 7.81%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 7.81%   |
| Apple                                  | 5         | 7.81%   |
| Silicon Motion                         | 3         | 4.69%   |
| IMC Networks                           | 3         | 4.69%   |
| Z-Star Microelectronics                | 2         | 3.13%   |
| Sunplus Innovation Technology          | 2         | 3.13%   |
| Realtek Semiconductor                  | 2         | 3.13%   |
| Microdia                               | 2         | 3.13%   |
| Alcor Micro                            | 2         | 3.13%   |
| Unknown                                | 1         | 1.56%   |
| Syntek                                 | 1         | 1.56%   |
| Ricoh                                  | 1         | 1.56%   |
| OmniVision Technologies                | 1         | 1.56%   |
| Microsoft                              | 1         | 1.56%   |
| Logitech                               | 1         | 1.56%   |
| Lite-On Technology                     | 1         | 1.56%   |
| Jieli Technology                       | 1         | 1.56%   |
| Hewlett-Packard                        | 1         | 1.56%   |
| Generalplus Technology                 | 1         | 1.56%   |
| Aveo Technology                        | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                       | 5         | 7.81%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 3.13%   |
| Quanta HP TrueVision HD Camera                      | 2         | 3.13%   |
| Chicony FJ Camera                                   | 2         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 3.13%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 3.13%   |
| Apple Built-in iSight                               | 2         | 3.13%   |
| Z-Star Webcam                                       | 1         | 1.56%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 1.56%   |
| Unknown Integrated RGB Camera                       | 1         | 1.56%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.56%   |
| Suyin USB 2.0 Camera                                | 1         | 1.56%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.56%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 1.56%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.56%   |
| Sunplus HD WebCam                                   | 1         | 1.56%   |
| Silicon Motion WebCam SC-10HDD13335N                | 1         | 1.56%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 1.56%   |
| Silicon Motion Web Camera                           | 1         | 1.56%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.56%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.56%   |
| Realtek USB Camera                                  | 1         | 1.56%   |
| Quanta VGA WebCam                                   | 1         | 1.56%   |
| Quanta HP Truevision HD                             | 1         | 1.56%   |
| Quanta HD Webcam                                    | 1         | 1.56%   |
| OmniVision OV2640 Webcam                            | 1         | 1.56%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1         | 1.56%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.56%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.56%   |
| Logitech HD Webcam C615                             | 1         | 1.56%   |
| Lite-On Integrated Camera                           | 1         | 1.56%   |
| Jieli USB PHY 2.0                                   | 1         | 1.56%   |
| IMC Networks USB2.0 UVC VGA WebCam                  | 1         | 1.56%   |
| IMC Networks EasyCamera                             | 1         | 1.56%   |
| IMC Networks 2M Integrated Webcam                   | 1         | 1.56%   |
| HP Webcam HD 2300                                   | 1         | 1.56%   |
| Generalplus GENERAL WEBCAM                          | 1         | 1.56%   |
| Chicony VGA Webcam                                  | 1         | 1.56%   |
| Chicony USB 2.0 Camera                              | 1         | 1.56%   |
| Chicony Integrated Camera                           | 1         | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| O2 Micro Oz776 SmartCard Reader     | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 86        | 78.9%   |
| 1     | 19        | 17.43%  |
| 2     | 4         | 3.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 29.63%  |
| Net/wireless             | 4         | 14.81%  |
| Graphics card            | 3         | 11.11%  |
| Chipcard                 | 2         | 7.41%   |
| Bluetooth                | 2         | 7.41%   |
| Unassigned class         | 1         | 3.7%    |
| Storage                  | 1         | 3.7%    |
| Sound                    | 1         | 3.7%    |
| Network                  | 1         | 3.7%    |
| Net/ethernet             | 1         | 3.7%    |
| Multimedia controller    | 1         | 3.7%    |
| Dvb card                 | 1         | 3.7%    |
| Communication controller | 1         | 3.7%    |

