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

Total: 125

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Acer     | Aspire TC-895 V:1.0         | Desktop     | [fb0408c4ea](https://linux-hardware.org/?probe=fb0408c4ea) | Feb 10, 2022 |
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

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Linux Lite 5.0 | 17        | 19.54%  |
| Linux Lite 5.8 | 16        | 18.39%  |
| Linux Lite 5.2 | 16        | 18.39%  |
| Linux Lite 5.4 | 15        | 17.24%  |
| Linux Lite 5.6 | 12        | 13.79%  |
| Linux Lite 3.8 | 5         | 5.75%   |
| Linux Lite 6.0 | 2         | 2.3%    |
| Linux Lite 4.8 | 2         | 2.3%    |
| Linux Lite 4.6 | 1         | 1.15%   |
| Linux Lite 4.4 | 1         | 1.15%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Lite | 86        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 6         | 6.52%   |
| 5.4.0-70-generic                   | 5         | 5.43%   |
| 5.4.0-91-generic                   | 4         | 4.35%   |
| 5.4.0-52-generic                   | 4         | 4.35%   |
| 5.4.0-40-generic                   | 4         | 4.35%   |
| 5.4.0-109-generic                  | 4         | 4.35%   |
| 5.4.0-104-generic                  | 4         | 4.35%   |
| 5.4.0-96-generic                   | 3         | 3.26%   |
| 5.4.0-58-generic                   | 3         | 3.26%   |
| 5.4.0-48-generic                   | 3         | 3.26%   |
| 5.4.0-90-generic                   | 2         | 2.17%   |
| 5.4.0-88-generic                   | 2         | 2.17%   |
| 5.4.0-81-generic                   | 2         | 2.17%   |
| 5.4.0-80-generic                   | 2         | 2.17%   |
| 5.4.0-74-generic                   | 2         | 2.17%   |
| 5.4.0-54-generic                   | 2         | 2.17%   |
| 5.4.0-33-generic                   | 2         | 2.17%   |
| 5.4.0-110-generic                  | 2         | 2.17%   |
| 5.4.0-107-generic                  | 2         | 2.17%   |
| 5.4.0-105-generic                  | 2         | 2.17%   |
| 4.4.0-112-generic                  | 2         | 2.17%   |
| 5.9.0                              | 1         | 1.09%   |
| 5.4.0-99-generic                   | 1         | 1.09%   |
| 5.4.0-94-generic                   | 1         | 1.09%   |
| 5.4.0-77-generic                   | 1         | 1.09%   |
| 5.4.0-72-generic                   | 1         | 1.09%   |
| 5.4.0-71-generic                   | 1         | 1.09%   |
| 5.4.0-66-generic                   | 1         | 1.09%   |
| 5.4.0-65-generic                   | 1         | 1.09%   |
| 5.4.0-56-generic                   | 1         | 1.09%   |
| 5.4.0-45-generic                   | 1         | 1.09%   |
| 5.4.0-37-generic                   | 1         | 1.09%   |
| 5.4.0-113-generic                  | 1         | 1.09%   |
| 5.4.0-100-generic                  | 1         | 1.09%   |
| 5.16.0                             | 1         | 1.09%   |
| 5.15.0-30-generic                  | 1         | 1.09%   |
| 5.15.0-27-generic                  | 1         | 1.09%   |
| 5.15.0                             | 1         | 1.09%   |
| 5.13.0-linuxlite                   | 1         | 1.09%   |
| 5.13.0-44-lowlatency               | 1         | 1.09%   |
| 5.13.0-30-lowlatency               | 1         | 1.09%   |
| 5.10.0-051000daily20201222-generic | 1         | 1.09%   |
| 4.4.0-217-generic                  | 1         | 1.09%   |
| 4.4.0-210-generic                  | 1         | 1.09%   |
| 4.15.0-99-generic                  | 1         | 1.09%   |
| 4.15.0-91-generic                  | 1         | 1.09%   |
| 4.15.0-169-generic                 | 1         | 1.09%   |
| 4.15.0-166-generic                 | 1         | 1.09%   |
| 4.15.0-163-generic                 | 1         | 1.09%   |
| 4.15.0-162-generic                 | 1         | 1.09%   |
| 4.15.0-147-generic                 | 1         | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 71        | 79.78%  |
| 4.15.0  | 5         | 5.62%   |
| 4.4.0   | 4         | 4.49%   |
| 5.15.0  | 3         | 3.37%   |
| 5.13.0  | 3         | 3.37%   |
| 5.9.0   | 1         | 1.12%   |
| 5.16.0  | 1         | 1.12%   |
| 5.10.0  | 1         | 1.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 71        | 79.78%  |
| 4.15    | 5         | 5.62%   |
| 4.4     | 4         | 4.49%   |
| 5.15    | 3         | 3.37%   |
| 5.13    | 3         | 3.37%   |
| 5.9     | 1         | 1.12%   |
| 5.16    | 1         | 1.12%   |
| 5.10    | 1         | 1.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 82        | 95.35%  |
| i686   | 4         | 4.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 61        | 70.93%  |
| GNOME   | 23        | 26.74%  |
| Deepin  | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 85        | 98.84%  |
| Unknown | 1         | 1.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 41        | 46.59%  |
| TDM     | 28        | 31.82%  |
| Unknown | 18        | 20.45%  |
| GDM     | 1         | 1.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 39        | 45.35%  |
| de_DE | 6         | 6.98%   |
| pt_BR | 5         | 5.81%   |
| pl_PL | 5         | 5.81%   |
| fr_FR | 5         | 5.81%   |
| en_GB | 5         | 5.81%   |
| ru_UA | 3         | 3.49%   |
| es_MX | 3         | 3.49%   |
| es_ES | 3         | 3.49%   |
| ru_RU | 2         | 2.33%   |
| tr_TR | 1         | 1.16%   |
| nl_NL | 1         | 1.16%   |
| it_IT | 1         | 1.16%   |
| fr_CA | 1         | 1.16%   |
| es_CO | 1         | 1.16%   |
| es_CL | 1         | 1.16%   |
| en_NZ | 1         | 1.16%   |
| en_IE | 1         | 1.16%   |
| en_CA | 1         | 1.16%   |
| da_DK | 1         | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 53        | 61.63%  |
| EFI  | 33        | 38.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 75        | 87.21%  |
| Overlay | 8         | 9.3%    |
| Zfs     | 1         | 1.16%   |
| Ext3    | 1         | 1.16%   |
| Btrfs   | 1         | 1.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 37.21%  |
| MBR     | 28        | 32.56%  |
| GPT     | 26        | 30.23%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 80.23%  |
| Yes       | 17        | 19.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 68.97%  |
| Yes       | 27        | 31.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 17        | 19.77%  |
| ASUSTek Computer    | 12        | 13.95%  |
| Acer                | 11        | 12.79%  |
| Lenovo              | 9         | 10.47%  |
| Dell                | 9         | 10.47%  |
| MSI                 | 3         | 3.49%   |
| Gigabyte Technology | 3         | 3.49%   |
| Samsung Electronics | 2         | 2.33%   |
| Minix               | 2         | 2.33%   |
| Intel               | 2         | 2.33%   |
| Foxconn             | 2         | 2.33%   |
| ASRock              | 2         | 2.33%   |
| TR                  | 1         | 1.16%   |
| Toshiba             | 1         | 1.16%   |
| Pegatron            | 1         | 1.16%   |
| Jetway              | 1         | 1.16%   |
| Insignia            | 1         | 1.16%   |
| Google              | 1         | 1.16%   |
| Fujitsu             | 1         | 1.16%   |
| EVGA                | 1         | 1.16%   |
| Biostar             | 1         | 1.16%   |
| AWOW                | 1         | 1.16%   |
| Apple               | 1         | 1.16%   |
| ABIT                | 1         | 1.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| MSI MS-7758                            | 2         | 2.33%   |
| TR ST Pro-KN                           | 1         | 1.16%   |
| Toshiba Satellite T215D                | 1         | 1.16%   |
| Samsung NC110P/NC108P/NC111P           | 1         | 1.16%   |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 1.16%   |
| Pegatron 520-1135la                    | 1         | 1.16%   |
| MSI FZ079AA-ABF a6625fr                | 1         | 1.16%   |
| Minix Z83-4                            | 1         | 1.16%   |
| Minix Z64                              | 1         | 1.16%   |
| Lenovo ThinkPad T400 6475E13           | 1         | 1.16%   |
| Lenovo ThinkCentre M91p 4524RS6        | 1         | 1.16%   |
| Lenovo ThinkCentre M91p 4518E2M        | 1         | 1.16%   |
| Lenovo ThinkCentre A55 9265BL7         | 1         | 1.16%   |
| Lenovo MIIX 300-10IBY 80NR             | 1         | 1.16%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1    | 1         | 1.16%   |
| Lenovo IdeaPad 320-15ABR 80XS          | 1         | 1.16%   |
| Lenovo H505S 10107                     | 1         | 1.16%   |
| Lenovo 3000 V200 0764A11               | 1         | 1.16%   |
| Jetway I61MG4                          | 1         | 1.16%   |
| Intel H61M-S1                          | 1         | 1.16%   |
| Intel DG31PR AAD97573-300              | 1         | 1.16%   |
| Insignia NS-P11W7100                   | 1         | 1.16%   |
| HP xw8600 Workstation                  | 1         | 1.16%   |
| HP x2 Detachable 10-p0XX               | 1         | 1.16%   |
| HP t5000 series                        | 1         | 1.16%   |
| HP Pavilion dv6500                     | 1         | 1.16%   |
| HP Laptop 17-by2xxx                    | 1         | 1.16%   |
| HP Laptop 15-dw3xxx                    | 1         | 1.16%   |
| HP Laptop 14-cm0xxx                    | 1         | 1.16%   |
| HP EliteBook Folio 9470m               | 1         | 1.16%   |
| HP Compaq nw9440 (EY615ET#ABU)         | 1         | 1.16%   |
| HP Compaq dc7900 Convertible Minitower | 1         | 1.16%   |
| HP Compaq dc5800 Small Form Factor     | 1         | 1.16%   |
| HP Compaq CQ45                         | 1         | 1.16%   |
| HP Compaq 6005 Pro SFF PC              | 1         | 1.16%   |
| HP Compaq 2510p                        | 1         | 1.16%   |
| HP 655                                 | 1         | 1.16%   |
| HP 200-5320br                          | 1         | 1.16%   |
| HP 15 Notebook PC                      | 1         | 1.16%   |
| Google Chell                           | 1         | 1.16%   |
| Gigabyte X570 AORUS MASTER             | 1         | 1.16%   |
| Gigabyte GA-E350N                      | 1         | 1.16%   |
| Gigabyte B450M DS3H                    | 1         | 1.16%   |
| Fujitsu LIFEBOOK U747                  | 1         | 1.16%   |
| Foxconn 500B Microtower                | 1         | 1.16%   |
| Foxconn 45CMX/45GMX/45CMX-K            | 1         | 1.16%   |
| EVGA X58 SLI FTW3 Tylersburg           | 1         | 1.16%   |
| Dell Vostro1710                        | 1         | 1.16%   |
| Dell OptiPlex 790                      | 1         | 1.16%   |
| Dell MXG071                            | 1         | 1.16%   |
| Dell MXG061                            | 1         | 1.16%   |
| Dell Latitude D530                     | 1         | 1.16%   |
| Dell Inspiron 7559                     | 1         | 1.16%   |
| Dell Inspiron 560                      | 1         | 1.16%   |
| Dell Inspiron 5452                     | 1         | 1.16%   |
| Dell Inspiron 16 5620                  | 1         | 1.16%   |
| Biostar G41D3C                         | 1         | 1.16%   |
| AWOW PC BOX                            | 1         | 1.16%   |
| ASUS X751LD                            | 1         | 1.16%   |
| ASUS X541SA                            | 1         | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 7         | 8.14%   |
| HP Compaq            | 6         | 6.98%   |
| Dell Inspiron        | 4         | 4.65%   |
| Lenovo ThinkCentre   | 3         | 3.49%   |
| HP Laptop            | 3         | 3.49%   |
| MSI MS-7758          | 2         | 2.33%   |
| Lenovo IdeaPad       | 2         | 2.33%   |
| TR ST                | 1         | 1.16%   |
| Toshiba Satellite    | 1         | 1.16%   |
| Samsung NC110P       | 1         | 1.16%   |
| Samsung 905S3G       | 1         | 1.16%   |
| Pegatron 520-1135la  | 1         | 1.16%   |
| MSI FZ079AA-ABF      | 1         | 1.16%   |
| Minix Z83-4          | 1         | 1.16%   |
| Minix Z64            | 1         | 1.16%   |
| Lenovo ThinkPad      | 1         | 1.16%   |
| Lenovo MIIX          | 1         | 1.16%   |
| Lenovo H505S         | 1         | 1.16%   |
| Lenovo 3000          | 1         | 1.16%   |
| Jetway I61MG4        | 1         | 1.16%   |
| Intel H61M-S1        | 1         | 1.16%   |
| Intel DG31PR         | 1         | 1.16%   |
| Insignia NS-P11W7100 | 1         | 1.16%   |
| HP xw8600            | 1         | 1.16%   |
| HP x2                | 1         | 1.16%   |
| HP t5000             | 1         | 1.16%   |
| HP Pavilion          | 1         | 1.16%   |
| HP EliteBook         | 1         | 1.16%   |
| HP 655               | 1         | 1.16%   |
| HP 200-5320br        | 1         | 1.16%   |
| HP 15                | 1         | 1.16%   |
| Google Chell         | 1         | 1.16%   |
| Gigabyte X570        | 1         | 1.16%   |
| Gigabyte GA-E350N    | 1         | 1.16%   |
| Gigabyte B450M       | 1         | 1.16%   |
| Fujitsu LIFEBOOK     | 1         | 1.16%   |
| Foxconn 500B         | 1         | 1.16%   |
| Foxconn 45CMX        | 1         | 1.16%   |
| EVGA X58             | 1         | 1.16%   |
| Dell Vostro1710      | 1         | 1.16%   |
| Dell OptiPlex        | 1         | 1.16%   |
| Dell MXG071          | 1         | 1.16%   |
| Dell MXG061          | 1         | 1.16%   |
| Dell Latitude        | 1         | 1.16%   |
| Biostar G41D3C       | 1         | 1.16%   |
| AWOW PC              | 1         | 1.16%   |
| ASUS X751LD          | 1         | 1.16%   |
| ASUS X541SA          | 1         | 1.16%   |
| ASUS X540YA          | 1         | 1.16%   |
| ASUS VivoBook        | 1         | 1.16%   |
| ASUS TUF             | 1         | 1.16%   |
| ASUS N750JK          | 1         | 1.16%   |
| ASUS N53Jf           | 1         | 1.16%   |
| ASUS M5A78L          | 1         | 1.16%   |
| ASUS K54LY           | 1         | 1.16%   |
| ASUS K50IE           | 1         | 1.16%   |
| ASUS 900             | 1         | 1.16%   |
| ASUS 1001PX          | 1         | 1.16%   |
| ASRock N68C-S        | 1         | 1.16%   |
| ASRock H61M-VG3      | 1         | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2008 | 13        | 15.12%  |
| 2012 | 10        | 11.63%  |
| 2011 | 10        | 11.63%  |
| 2010 | 8         | 9.3%    |
| 2007 | 7         | 8.14%   |
| 2018 | 6         | 6.98%   |
| 2016 | 6         | 6.98%   |
| 2020 | 5         | 5.81%   |
| 2015 | 4         | 4.65%   |
| 2014 | 4         | 4.65%   |
| 2017 | 3         | 3.49%   |
| 2019 | 2         | 2.33%   |
| 2009 | 2         | 2.33%   |
| 2006 | 2         | 2.33%   |
| 2022 | 1         | 1.16%   |
| 2021 | 1         | 1.16%   |
| 2013 | 1         | 1.16%   |
| 2004 | 1         | 1.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 48        | 55.81%  |
| Desktop    | 34        | 39.53%  |
| Tablet     | 2         | 2.33%   |
| Mini pc    | 1         | 1.16%   |
| All in one | 1         | 1.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 84        | 97.67%  |
| Enabled  | 2         | 2.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 85        | 98.84%  |
| Yes  | 1         | 1.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 28        | 32.56%  |
| 1.01-2.0   | 20        | 23.26%  |
| 4.01-8.0   | 13        | 15.12%  |
| 16.01-24.0 | 10        | 11.63%  |
| 8.01-16.0  | 6         | 6.98%   |
| 32.01-64.0 | 4         | 4.65%   |
| 0.51-1.0   | 3         | 3.49%   |
| 2.01-3.0   | 2         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 41        | 46.59%  |
| 2.01-3.0 | 16        | 18.18%  |
| 0.51-1.0 | 15        | 17.05%  |
| 3.01-4.0 | 8         | 9.09%   |
| 4.01-8.0 | 5         | 5.68%   |
| 0.01-0.5 | 3         | 3.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 59        | 68.6%   |
| 2      | 19        | 22.09%  |
| 3      | 4         | 4.65%   |
| 0      | 2         | 2.33%   |
| 5      | 1         | 1.16%   |
| 4      | 1         | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 55.81%  |
| Yes       | 38        | 44.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 89.53%  |
| No        | 9         | 10.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 77.91%  |
| No        | 19        | 22.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 50%     |
| No        | 43        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 11        | 12.79%  |
| Brazil      | 10        | 11.63%  |
| Germany     | 7         | 8.14%   |
| Ukraine     | 5         | 5.81%   |
| UK          | 5         | 5.81%   |
| Poland      | 5         | 5.81%   |
| France      | 5         | 5.81%   |
| Mexico      | 4         | 4.65%   |
| Canada      | 4         | 4.65%   |
| Spain       | 3         | 3.49%   |
| Russia      | 3         | 3.49%   |
| Romania     | 3         | 3.49%   |
| Peru        | 3         | 3.49%   |
| Turkey      | 2         | 2.33%   |
| Netherlands | 2         | 2.33%   |
| Chile       | 2         | 2.33%   |
| Slovakia    | 1         | 1.16%   |
| Qatar       | 1         | 1.16%   |
| Philippines | 1         | 1.16%   |
| New Zealand | 1         | 1.16%   |
| Myanmar     | 1         | 1.16%   |
| Malaysia    | 1         | 1.16%   |
| Italy       | 1         | 1.16%   |
| Ireland     | 1         | 1.16%   |
| Guadeloupe  | 1         | 1.16%   |
| Greenland   | 1         | 1.16%   |
| Colombia    | 1         | 1.16%   |
| Australia   | 1         | 1.16%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Pabianice            | 3         | 3.45%   |
| Würzburg            | 2         | 2.3%    |
| Warsaw               | 2         | 2.3%    |
| Odessa               | 2         | 2.3%    |
| Lima                 | 2         | 2.3%    |
| Kyiv                 | 2         | 2.3%    |
| Yangon               | 1         | 1.15%   |
| Wiesbaden            | 1         | 1.15%   |
| Wellington           | 1         | 1.15%   |
| Waterbury            | 1         | 1.15%   |
| Wahroonga            | 1         | 1.15%   |
| Voluntari            | 1         | 1.15%   |
| Vinnytsia            | 1         | 1.15%   |
| Varennes-les-Narcy   | 1         | 1.15%   |
| Vancouver            | 1         | 1.15%   |
| Valencia             | 1         | 1.15%   |
| Trujillo             | 1         | 1.15%   |
| Thetford-Mines       | 1         | 1.15%   |
| Teresina             | 1         | 1.15%   |
| Tarragona            | 1         | 1.15%   |
| Sydney               | 1         | 1.15%   |
| Svidník             | 1         | 1.15%   |
| St. Petersburg       | 1         | 1.15%   |
| Shadrinsk            | 1         | 1.15%   |
| Sao Paulo            | 1         | 1.15%   |
| Sabadell             | 1         | 1.15%   |
| Rio de Janeiro       | 1         | 1.15%   |
| Queretaro            | 1         | 1.15%   |
| Purmerend            | 1         | 1.15%   |
| Porto Velho          | 1         | 1.15%   |
| Porto Alegre         | 1         | 1.15%   |
| Paris                | 1         | 1.15%   |
| Paranaque City       | 1         | 1.15%   |
| Ottawa               | 1         | 1.15%   |
| Ossining             | 1         | 1.15%   |
| Osasco               | 1         | 1.15%   |
| Oldenburg            | 1         | 1.15%   |
| Nudlingen            | 1         | 1.15%   |
| Novaci               | 1         | 1.15%   |
| Nashville            | 1         | 1.15%   |
| Narbonne             | 1         | 1.15%   |
| Moscow               | 1         | 1.15%   |
| Milan                | 1         | 1.15%   |
| Mexico City          | 1         | 1.15%   |
| Marseille            | 1         | 1.15%   |
| Madrid               | 1         | 1.15%   |
| Long Seridan         | 1         | 1.15%   |
| London               | 1         | 1.15%   |
| Les Abymes           | 1         | 1.15%   |
| La Glacerie          | 1         | 1.15%   |
| Kingston upon Thames | 1         | 1.15%   |
| Jaraguá do Sul      | 1         | 1.15%   |
| Izmir                | 1         | 1.15%   |
| Istanbul             | 1         | 1.15%   |
| Ilulissat            | 1         | 1.15%   |
| Hedon                | 1         | 1.15%   |
| Frankfurt am Main    | 1         | 1.15%   |
| Fortin de las Flores | 1         | 1.15%   |
| Eggenfelden          | 1         | 1.15%   |
| Edmonton             | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 27     | 23.15%  |
| WDC                 | 20        | 26     | 18.52%  |
| Toshiba             | 10        | 11     | 9.26%   |
| Samsung Electronics | 9         | 10     | 8.33%   |
| Kingston            | 7         | 9      | 6.48%   |
| Unknown             | 6         | 8      | 5.56%   |
| SanDisk             | 4         | 4      | 3.7%    |
| Hitachi             | 4         | 4      | 3.7%    |
| GOODRAM             | 3         | 3      | 2.78%   |
| Crucial             | 3         | 3      | 2.78%   |
| Micron Technology   | 2         | 3      | 1.85%   |
| HGST                | 2         | 2      | 1.85%   |
| SK Hynix            | 1         | 1      | 0.93%   |
| PNY                 | 1         | 1      | 0.93%   |
| Phison              | 1         | 1      | 0.93%   |
| OCZ                 | 1         | 1      | 0.93%   |
| MAXTOR              | 1         | 1      | 0.93%   |
| Mass                | 1         | 1      | 0.93%   |
| LITEON              | 1         | 1      | 0.93%   |
| Intel               | 1         | 1      | 0.93%   |
| HPE                 | 1         | 1      | 0.93%   |
| Hewlett-Packard     | 1         | 1      | 0.93%   |
| Gigabyte Technology | 1         | 1      | 0.93%   |
| ASUS-PHISON         | 1         | 2      | 0.93%   |
| ASMT                | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                | 3         | 2.61%   |
| Toshiba MQ01ABF050 500GB              | 3         | 2.61%   |
| Seagate ST500DM002-1BD142 500GB       | 3         | 2.61%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 2         | 1.74%   |
| WDC WD5000AAKX-001CA0 500GB           | 2         | 1.74%   |
| WDC WD10JPVX-75JC3T0 1TB              | 2         | 1.74%   |
| Seagate ST9320325AS 320GB             | 2         | 1.74%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 1.74%   |
| WDC WD800JD-60LSA0 80GB               | 1         | 0.87%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 0.87%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 0.87%   |
| WDC WD5000AAKS-60WWPA0 500GB          | 1         | 0.87%   |
| WDC WD5000AACS-00G8B1 500GB           | 1         | 0.87%   |
| WDC WD2500BEVE-00A0HT0 250GB          | 1         | 0.87%   |
| WDC WD20PURX-64PFUY0 2TB              | 1         | 0.87%   |
| WDC WD2005FBYZ-01YCBB2 2TB            | 1         | 0.87%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.87%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 0.87%   |
| WDC WD10EADS-00L5B1 1TB               | 1         | 0.87%   |
| WDC WD1003FBYX-01Y7B1 1TB             | 1         | 0.87%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB    | 1         | 0.87%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 0.87%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB  | 1         | 0.87%   |
| Unknown SD64G  64GB                   | 1         | 0.87%   |
| Unknown SC64G  64GB                   | 1         | 0.87%   |
| Unknown NCard  32GB                   | 1         | 0.87%   |
| Unknown HBG4a2  32GB                  | 1         | 0.87%   |
| Unknown BGND3R  32GB                  | 1         | 0.87%   |
| Toshiba MQ04ABF100 1TB                | 1         | 0.87%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.87%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 0.87%   |
| Toshiba MK1059GSM 1TB                 | 1         | 0.87%   |
| Toshiba MK1011GAH 100GB               | 1         | 0.87%   |
| Toshiba HDWD110 1TB                   | 1         | 0.87%   |
| Toshiba DT01ACA100 1TB                | 1         | 0.87%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1         | 0.87%   |
| Seagate ST980811AS 80GB               | 1         | 0.87%   |
| Seagate ST9500423AS 500GB             | 1         | 0.87%   |
| Seagate ST9500325AS 500GB             | 1         | 0.87%   |
| Seagate ST9160823ASG 160GB            | 1         | 0.87%   |
| Seagate ST9160301AS 160GB             | 1         | 0.87%   |
| Seagate ST640LM0 00 HM641JI 640GB     | 1         | 0.87%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 0.87%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 0.87%   |
| Seagate ST500LM030-1RK17D 500GB       | 1         | 0.87%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 0.87%   |
| Seagate ST500DM002-1BC142 500GB       | 1         | 0.87%   |
| Seagate ST3750640NS 752GB             | 1         | 0.87%   |
| Seagate ST3320620A 320GB              | 1         | 0.87%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 0.87%   |
| Seagate ST320LM001 HN-M320MBB 320GB   | 1         | 0.87%   |
| Seagate ST320LM000 HM321HI 320GB      | 1         | 0.87%   |
| Seagate ST3120026A 120GB              | 1         | 0.87%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 0.87%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 0.87%   |
| Seagate ST1000LM010-9YH146 1TB        | 1         | 0.87%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 0.87%   |
| SanDisk Z400s M.2 2280 128GB SSD      | 1         | 0.87%   |
| SanDisk SDSSDH3250G 250GB             | 1         | 0.87%   |
| SanDisk SDSSDA240G 240GB              | 1         | 0.87%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 27     | 42.37%  |
| WDC                 | 15        | 18     | 25.42%  |
| Toshiba             | 10        | 11     | 16.95%  |
| Hitachi             | 4         | 4      | 6.78%   |
| Samsung Electronics | 2         | 3      | 3.39%   |
| HGST                | 2         | 2      | 3.39%   |
| MAXTOR              | 1         | 1      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 8      | 18.75%  |
| Samsung Electronics | 4         | 4      | 12.5%   |
| SanDisk             | 3         | 3      | 9.38%   |
| GOODRAM             | 3         | 3      | 9.38%   |
| Crucial             | 3         | 3      | 9.38%   |
| WDC                 | 2         | 3      | 6.25%   |
| Micron Technology   | 2         | 3      | 6.25%   |
| SK Hynix            | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| LITEON              | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |
| Gigabyte Technology | 1         | 1      | 3.13%   |
| ASUS-PHISON         | 1         | 2      | 3.13%   |
| ASMT                | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 54        | 66     | 54%     |
| SSD     | 30        | 37     | 30%     |
| MMC     | 7         | 9      | 7%      |
| NVMe    | 7         | 10     | 7%      |
| Unknown | 2         | 2      | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 71        | 101    | 79.78%  |
| NVMe | 7         | 10     | 7.87%   |
| MMC  | 7         | 9      | 7.87%   |
| SAS  | 4         | 4      | 4.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 77     | 70.73%  |
| 0.51-1.0   | 20        | 21     | 24.39%  |
| 1.01-2.0   | 4         | 5      | 4.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 27.59%  |
| 251-500        | 20        | 22.99%  |
| 51-100         | 13        | 14.94%  |
| 1-20           | 9         | 10.34%  |
| 21-50          | 8         | 9.2%    |
| 501-1000       | 7         | 8.05%   |
| More than 3000 | 4         | 4.6%    |
| 1001-2000      | 2         | 2.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 46        | 52.27%  |
| 21-50     | 17        | 19.32%  |
| 51-100    | 10        | 11.36%  |
| 101-250   | 8         | 9.09%   |
| 251-500   | 3         | 3.41%   |
| 2001-3000 | 2         | 2.27%   |
| 1001-2000 | 1         | 1.14%   |
| 501-1000  | 1         | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD800JD-60LSA0 80GB         | 1         | 1      | 6.67%   |
| WDC WD5000AAKX-001CA0 500GB     | 1         | 1      | 6.67%   |
| WDC WD5000AAKS-60WWPA0 500GB    | 1         | 1      | 6.67%   |
| WDC WD10JPVX-22JC3T0 1TB        | 1         | 1      | 6.67%   |
| Toshiba MK1059GSM 1TB           | 1         | 1      | 6.67%   |
| Seagate ST980811AS 80GB         | 1         | 1      | 6.67%   |
| Seagate ST9500423AS 500GB       | 1         | 1      | 6.67%   |
| Seagate ST9500325AS 500GB       | 1         | 1      | 6.67%   |
| Seagate ST9320325AS 320GB       | 1         | 1      | 6.67%   |
| Seagate ST9160823ASG 160GB      | 1         | 1      | 6.67%   |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 6.67%   |
| Seagate ST3120026A 120GB        | 1         | 1      | 6.67%   |
| Hitachi HTS545016B9A300 160GB   | 1         | 1      | 6.67%   |
| Hitachi HDS722020ALA330 2TB     | 1         | 1      | 6.67%   |
| Hitachi HDS721616PLA380 164GB   | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 46.67%  |
| WDC     | 4         | 4      | 26.67%  |
| Hitachi | 3         | 3      | 20%     |
| Toshiba | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 46.67%  |
| WDC     | 4         | 4      | 26.67%  |
| Hitachi | 3         | 3      | 20%     |
| Toshiba | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 15     | 100%    |

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
| Detected | 38        | 60     | 43.18%  |
| Works    | 37        | 49     | 42.05%  |
| Malfunc  | 13        | 15     | 14.77%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 61        | 67.03%  |
| AMD                         | 16        | 17.58%  |
| Sandisk                     | 3         | 3.3%    |
| Samsung Electronics         | 3         | 3.3%    |
| Nvidia                      | 2         | 2.2%    |
| Phison Electronics          | 1         | 1.1%    |
| Marvell Technology Group    | 1         | 1.1%    |
| LSI Logic / Symbios Logic   | 1         | 1.1%    |
| Kingston Technology Company | 1         | 1.1%    |
| JMicron Technology          | 1         | 1.1%    |
| Broadcom / LSI              | 1         | 1.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10        | 8.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 6.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 4.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 4.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 3.28%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3         | 2.46%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.64%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.64%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 2         | 1.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1.64%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 1.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 1.64%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.64%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 1.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.64%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.64%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.82%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.82%   |
| Sandisk Non-Volatile memory controller                                                  | 1         | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.82%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.82%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.82%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.82%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.82%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1         | 0.82%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1         | 0.82%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1         | 0.82%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 0.82%   |
| JMicron JMB368 IDE controller                                                           | 1         | 0.82%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                             | 1         | 0.82%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.82%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1         | 0.82%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1         | 0.82%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 0.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 0.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 1         | 0.82%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                  | 1         | 0.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 0.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 0.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 0.82%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 1         | 0.82%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 58        | 57.43%  |
| IDE  | 32        | 31.68%  |
| NVMe | 7         | 6.93%   |
| RAID | 3         | 2.97%   |
| SCSI | 1         | 0.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 69        | 80.23%  |
| AMD    | 17        | 19.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 2.33%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 2.33%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 2.33%   |
| Intel Core 2 CPU T7600 @ 2.33GHz            | 2         | 2.33%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 2.33%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 2.33%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 1.16%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1         | 1.16%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.16%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 1.16%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 1.16%   |
| Intel Pentium D CPU 3.40GHz                 | 1         | 1.16%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1.16%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.16%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.16%   |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1         | 1.16%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.16%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 1.16%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.16%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.16%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.16%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 1.16%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1         | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.16%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1         | 1.16%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.16%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1         | 1.16%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1         | 1.16%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1         | 1.16%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.16%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.16%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1         | 1.16%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1         | 1.16%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.16%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 1.16%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1         | 1.16%   |
| Intel Core 2 Extreme CPU X7900 @ 2.80GHz    | 1         | 1.16%   |
| Intel Core 2 Duo CPU U7600 @ 1.20GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1         | 1.16%   |
| Intel Celeron M processor 900MHz            | 1         | 1.16%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 1.16%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1         | 1.16%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 1         | 1.16%   |
| Intel Celeron CPU B830 @ 1.80GHz            | 1         | 1.16%   |
| Intel Celeron CPU 723 @ 1.20GHz             | 1         | 1.16%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 1         | 1.16%   |
| Intel Atom CPU N450 @ 1.66GHz               | 1         | 1.16%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 1         | 1.16%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 12        | 13.95%  |
| Intel Core i5           | 9         | 10.47%  |
| Intel Core i3           | 8         | 9.3%    |
| Intel Atom              | 7         | 8.14%   |
| Intel Core i7           | 6         | 6.98%   |
| Intel Pentium           | 5         | 5.81%   |
| Intel Celeron           | 5         | 5.81%   |
| Intel Pentium Dual-Core | 4         | 4.65%   |
| Other                   | 3         | 3.49%   |
| Intel Xeon              | 2         | 2.33%   |
| Intel Core 2            | 2         | 2.33%   |
| AMD E2                  | 2         | 2.33%   |
| AMD E                   | 2         | 2.33%   |
| Intel Pentium Dual      | 1         | 1.16%   |
| Intel Pentium D         | 1         | 1.16%   |
| Intel Genuine           | 1         | 1.16%   |
| Intel Core m7           | 1         | 1.16%   |
| Intel Core 2 Extreme    | 1         | 1.16%   |
| Intel Celeron M         | 1         | 1.16%   |
| AMD Turion 64 X2 Mobile | 1         | 1.16%   |
| AMD Ryzen 9             | 1         | 1.16%   |
| AMD Ryzen 5             | 1         | 1.16%   |
| AMD Ryzen 3             | 1         | 1.16%   |
| AMD Quad-Core           | 1         | 1.16%   |
| AMD Phenom II X2        | 1         | 1.16%   |
| AMD FX                  | 1         | 1.16%   |
| AMD Athlon II X2        | 1         | 1.16%   |
| AMD Athlon II Neo       | 1         | 1.16%   |
| AMD A8                  | 1         | 1.16%   |
| AMD A6                  | 1         | 1.16%   |
| AMD A12                 | 1         | 1.16%   |
| AMD A10                 | 1         | 1.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 49        | 56.98%  |
| 4      | 25        | 29.07%  |
| 1      | 5         | 5.81%   |
| 6      | 4         | 4.65%   |
| 12     | 1         | 1.16%   |
| 10     | 1         | 1.16%   |
| 8      | 1         | 1.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 85        | 98.84%  |
| 2      | 1         | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 57        | 66.28%  |
| 2      | 29        | 33.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 84        | 97.67%  |
| 32-bit         | 2         | 2.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 10        | 11.63%  |
| 0x206a7    | 9         | 10.47%  |
| Unknown    | 6         | 6.98%   |
| 0x6fd      | 4         | 4.65%   |
| 0x30678    | 4         | 4.65%   |
| 0x10676    | 4         | 4.65%   |
| 0x6fb      | 3         | 3.49%   |
| 0x406c4    | 3         | 3.49%   |
| 0x010000c8 | 3         | 3.49%   |
| 0x806c1    | 2         | 2.33%   |
| 0x6f6      | 2         | 2.33%   |
| 0x506c9    | 2         | 2.33%   |
| 0x406c3    | 2         | 2.33%   |
| 0x20655    | 2         | 2.33%   |
| 0x05000119 | 2         | 2.33%   |
| 0xf64      | 1         | 1.16%   |
| 0xa0653    | 1         | 1.16%   |
| 0x906ea    | 1         | 1.16%   |
| 0x906e9    | 1         | 1.16%   |
| 0x906a4    | 1         | 1.16%   |
| 0x806ec    | 1         | 1.16%   |
| 0x806eb    | 1         | 1.16%   |
| 0x806ea    | 1         | 1.16%   |
| 0x806e9    | 1         | 1.16%   |
| 0x6fa      | 1         | 1.16%   |
| 0x6d8      | 1         | 1.16%   |
| 0x506e3    | 1         | 1.16%   |
| 0x406e3    | 1         | 1.16%   |
| 0x40651    | 1         | 1.16%   |
| 0x306c3    | 1         | 1.16%   |
| 0x306a9    | 1         | 1.16%   |
| 0x30661    | 1         | 1.16%   |
| 0x206c2    | 1         | 1.16%   |
| 0x106ca    | 1         | 1.16%   |
| 0x08701013 | 1         | 1.16%   |
| 0x0810100b | 1         | 1.16%   |
| 0x0800820d | 1         | 1.16%   |
| 0x06006705 | 1         | 1.16%   |
| 0x06006118 | 1         | 1.16%   |
| 0x06001119 | 1         | 1.16%   |
| 0x06000852 | 1         | 1.16%   |
| 0x05000029 | 1         | 1.16%   |
| 0x03000027 | 1         | 1.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 14        | 16.28%  |
| Core             | 10        | 11.63%  |
| Silvermont       | 9         | 10.47%  |
| SandyBridge      | 9         | 10.47%  |
| KabyLake         | 6         | 6.98%   |
| Westmere         | 3         | 3.49%   |
| K10              | 3         | 3.49%   |
| IvyBridge        | 3         | 3.49%   |
| Bobcat           | 3         | 3.49%   |
| TigerLake        | 2         | 2.33%   |
| Skylake          | 2         | 2.33%   |
| Piledriver       | 2         | 2.33%   |
| P6               | 2         | 2.33%   |
| Haswell          | 2         | 2.33%   |
| Goldmont         | 2         | 2.33%   |
| Excavator        | 2         | 2.33%   |
| Bonnell          | 2         | 2.33%   |
| Zen+             | 1         | 1.16%   |
| Zen 2            | 1         | 1.16%   |
| Zen              | 1         | 1.16%   |
| Puma             | 1         | 1.16%   |
| NetBurst         | 1         | 1.16%   |
| K8 Hammer        | 1         | 1.16%   |
| K10 Llano        | 1         | 1.16%   |
| Jaguar           | 1         | 1.16%   |
| CometLake        | 1         | 1.16%   |
| Alderlake Hybrid | 1         | 1.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 51        | 55.43%  |
| Nvidia | 21        | 22.83%  |
| AMD    | 20        | 21.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 5%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 5%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 5%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 4%      |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 4%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2%      |
| Intel HD Graphics 500                                                                    | 2         | 2%      |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2%      |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 2%      |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 2%      |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 1%      |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1%      |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 1%      |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1%      |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1%      |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1%      |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1%      |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 1%      |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 1%      |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1         | 1%      |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 1%      |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 1%      |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1         | 1%      |
| Nvidia G84 [GeForce 8400 GS]                                                             | 1         | 1%      |
| Nvidia G72 [GeForce 7300 GS]                                                             | 1         | 1%      |
| Nvidia G71M [GeForce Go 7950 GTX]                                                        | 1         | 1%      |
| Nvidia G71GLM [Quadro FX 1500M]                                                          | 1         | 1%      |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1%      |
| Intel VGA compatible controller                                                          | 1         | 1%      |
| Intel UHD Graphics 620                                                                   | 1         | 1%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1%      |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1%      |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 1%      |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1%      |
| Intel HD Graphics 630                                                                    | 1         | 1%      |
| Intel HD Graphics 620                                                                    | 1         | 1%      |
| Intel HD Graphics 530                                                                    | 1         | 1%      |
| Intel HD Graphics 515                                                                    | 1         | 1%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1%      |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 1%      |
| Intel 82Q33 Express Integrated Graphics Controller                                       | 1         | 1%      |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1%      |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1         | 1%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1%      |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1%      |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 1%      |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1%      |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1%      |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 1%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 52.33%  |
| 1 x AMD        | 18        | 20.93%  |
| 1 x Nvidia     | 15        | 17.44%  |
| Intel + Nvidia | 6         | 6.98%   |
| 2 x AMD        | 2         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 74        | 85.06%  |
| Proprietary | 12        | 13.79%  |
| Unknown     | 1         | 1.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 53.49%  |
| 0.01-0.5   | 24        | 27.91%  |
| 0.51-1.0   | 6         | 6.98%   |
| 1.01-2.0   | 5         | 5.81%   |
| 3.01-4.0   | 3         | 3.49%   |
| 5.01-6.0   | 2         | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 19.32%  |
| AU Optronics            | 11        | 12.5%   |
| LG Display              | 8         | 9.09%   |
| Hewlett-Packard         | 7         | 7.95%   |
| Goldstar                | 6         | 6.82%   |
| Chi Mei Optoelectronics | 6         | 6.82%   |
| Chimei Innolux          | 4         | 4.55%   |
| BOE                     | 4         | 4.55%   |
| NEC Computers           | 3         | 3.41%   |
| Acer                    | 3         | 3.41%   |
| ViewSonic               | 2         | 2.27%   |
| Sony                    | 2         | 2.27%   |
| Seiko/Epson             | 1         | 1.14%   |
| Sanyo                   | 1         | 1.14%   |
| Philips                 | 1         | 1.14%   |
| MSI                     | 1         | 1.14%   |
| LG Philips              | 1         | 1.14%   |
| Lenovo                  | 1         | 1.14%   |
| Hitachi                 | 1         | 1.14%   |
| HannStar                | 1         | 1.14%   |
| eMachines               | 1         | 1.14%   |
| CPT                     | 1         | 1.14%   |
| BenQ                    | 1         | 1.14%   |
| Apple                   | 1         | 1.14%   |
| AOC                     | 1         | 1.14%   |
| Ancor Communications    | 1         | 1.14%   |
| Unknown                 | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 2.15%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1         | 1.08%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1         | 1.08%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1         | 1.08%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 1.08%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                    | 1         | 1.08%   |
| Seiko/Epson LCD Monitor                                               | 1         | 1.08%   |
| Sanyo LCD SAN1207 1360x768                                            | 1         | 1.08%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1         | 1.08%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 1.08%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch  | 1         | 1.08%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 1.08%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1         | 1.08%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 1.08%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1         | 1.08%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1         | 1.08%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                    | 1         | 1.08%   |
| NEC Computers LCD1990SXi NEC66AC 1280x1024 376x301mm 19.0-inch        | 1         | 1.08%   |
| NEC Computers EA244WMi NEC68D7 1920x1200 519x324mm 24.1-inch          | 1         | 1.08%   |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch            | 1         | 1.08%   |
| MSI G271 MSI3CB5 1920x1080 598x336mm 27.0-inch                        | 1         | 1.08%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD03E3 1366x768 310x174mm 14.0-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch               | 1         | 1.08%   |
| Hitachi N91W DVI HIT6D0D 1440x900 410x260mm 19.1-inch                 | 1         | 1.08%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 337x270mm 17.0-inch            | 1         | 1.08%   |
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 1         | 1.08%   |
| Hewlett-Packard P201 HWP3056 1600x900 443x249mm 20.0-inch             | 1         | 1.08%   |
| Hewlett-Packard LV2311 HWP3006 1920x1080 510x287mm 23.0-inch          | 1         | 1.08%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1         | 1.08%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1         | 1.08%   |
| Hewlett-Packard f1503 HWP2590 1024x768 304x228mm 15.0-inch            | 1         | 1.08%   |
| Hewlett-Packard All-in-One HWP4211 1920x1080 509x286mm 23.0-inch      | 1         | 1.08%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.08%   |
| Goldstar W2254 GSM56DE 1680x1050 474x296mm 22.0-inch                  | 1         | 1.08%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                  | 1         | 1.08%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                   | 1         | 1.08%   |
| Goldstar 22EA53 GSM59A5 1920x1080 480x270mm 21.7-inch                 | 1         | 1.08%   |
| eMachines E190HQV EMA0212 1280x1024 440x250mm 19.9-inch               | 1         | 1.08%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                  | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 1         | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 24        | 27.27%  |
| 1920x1080 (FHD)    | 21        | 23.86%  |
| 1920x1200 (WUXGA)  | 10        | 11.36%  |
| 1280x800 (WXGA)    | 6         | 6.82%   |
| 3840x2160 (4K)     | 5         | 5.68%   |
| 1600x900 (HD+)     | 4         | 4.55%   |
| 1280x1024 (SXGA)   | 4         | 4.55%   |
| 1680x1050 (WSXGA+) | 3         | 3.41%   |
| 1440x900 (WXGA+)   | 3         | 3.41%   |
| Unknown            | 2         | 2.27%   |
| 5280x1080          | 1         | 1.14%   |
| 3200x1800 (QHD+)   | 1         | 1.14%   |
| 2560x1440 (QHD)    | 1         | 1.14%   |
| 1360x768           | 1         | 1.14%   |
| 1024x768 (XGA)     | 1         | 1.14%   |
| 1024x600           | 1         | 1.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 20        | 22.47%  |
| 17      | 9         | 10.11%  |
| Unknown | 7         | 7.87%   |
| 24      | 6         | 6.74%   |
| 21      | 6         | 6.74%   |
| 14      | 6         | 6.74%   |
| 19      | 5         | 5.62%   |
| 18      | 4         | 4.49%   |
| 27      | 3         | 3.37%   |
| 23      | 3         | 3.37%   |
| 20      | 3         | 3.37%   |
| 13      | 3         | 3.37%   |
| 11      | 3         | 3.37%   |
| 10      | 3         | 3.37%   |
| 12      | 2         | 2.25%   |
| 72      | 1         | 1.12%   |
| 65      | 1         | 1.12%   |
| 40      | 1         | 1.12%   |
| 28      | 1         | 1.12%   |
| 22      | 1         | 1.12%   |
| 16      | 1         | 1.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 34.09%  |
| 401-500     | 16        | 18.18%  |
| 501-600     | 12        | 13.64%  |
| 201-300     | 10        | 11.36%  |
| 351-400     | 9         | 10.23%  |
| Unknown     | 7         | 7.95%   |
| 801-900     | 1         | 1.14%   |
| 601-700     | 1         | 1.14%   |
| 1501-2000   | 1         | 1.14%   |
| 1001-1500   | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 52        | 63.41%  |
| 16/10   | 20        | 24.39%  |
| Unknown | 5         | 6.1%    |
| 5/4     | 4         | 4.88%   |
| 4/3     | 1         | 1.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 22.47%  |
| 201-250        | 10        | 11.24%  |
| 151-200        | 9         | 10.11%  |
| 81-90          | 7         | 7.87%   |
| Unknown        | 7         | 7.87%   |
| 141-150        | 6         | 6.74%   |
| 251-300        | 5         | 5.62%   |
| 131-140        | 4         | 4.49%   |
| 51-60          | 3         | 3.37%   |
| 41-50          | 3         | 3.37%   |
| 301-350        | 3         | 3.37%   |
| 121-130        | 3         | 3.37%   |
| More than 1000 | 2         | 2.25%   |
| 71-80          | 2         | 2.25%   |
| 61-70          | 2         | 2.25%   |
| 351-500        | 1         | 1.12%   |
| 111-120        | 1         | 1.12%   |
| 501-1000       | 1         | 1.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 33        | 38.37%  |
| 101-120       | 22        | 25.58%  |
| 121-160       | 20        | 23.26%  |
| Unknown       | 7         | 8.14%   |
| More than 240 | 2         | 2.33%   |
| 1-50          | 1         | 1.16%   |
| 161-240       | 1         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 76        | 87.36%  |
| 2     | 10        | 11.49%  |
| 3     | 1         | 1.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 47        | 35.07%  |
| Intel                                 | 29        | 21.64%  |
| Qualcomm Atheros                      | 21        | 15.67%  |
| Broadcom                              | 14        | 10.45%  |
| Broadcom Limited                      | 4         | 2.99%   |
| Ralink Technology                     | 3         | 2.24%   |
| Ralink                                | 2         | 1.49%   |
| Marvell Technology Group              | 2         | 1.49%   |
| TP-Link                               | 1         | 0.75%   |
| Sierra Wireless                       | 1         | 0.75%   |
| Samsung Electronics                   | 1         | 0.75%   |
| Qualcomm Atheros Communications       | 1         | 0.75%   |
| Nvidia                                | 1         | 0.75%   |
| Microsoft                             | 1         | 0.75%   |
| Linksys                               | 1         | 0.75%   |
| D-Link                                | 1         | 0.75%   |
| ASUSTek Computer                      | 1         | 0.75%   |
| ASIX Electronics                      | 1         | 0.75%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.75%   |
| 3Com                                  | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 33        | 21.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 10        | 6.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 3.25%   |
| Intel Wireless 3165                                                                           | 4         | 2.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4         | 2.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 1.3%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 1.3%    |
| Ralink MT7601U Wireless Adapter                                                               | 2         | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 2         | 1.3%    |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2         | 1.3%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                        | 2         | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.3%    |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 0.65%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1         | 0.65%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.65%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 0.65%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 0.65%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1         | 0.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.65%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.65%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 0.65%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 0.65%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                    | 1         | 0.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.65%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1         | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1         | 0.65%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.65%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 0.65%   |
| Nvidia MCP61 Ethernet                                                                         | 1         | 0.65%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1         | 0.65%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.65%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.65%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                           | 1         | 0.65%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 0.65%   |
| Intel Wireless 7265                                                                           | 1         | 0.65%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 0.65%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 0.65%   |
| Intel I211 Gigabit Network Connection                                                         | 1         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                                                         | 1         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 0.65%   |
| Intel Centrino Wireless-N 130                                                                 | 1         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 20        | 28.17%  |
| Qualcomm Atheros                      | 19        | 26.76%  |
| Realtek Semiconductor                 | 12        | 16.9%   |
| Broadcom                              | 5         | 7.04%   |
| Ralink Technology                     | 3         | 4.23%   |
| Ralink                                | 2         | 2.82%   |
| Broadcom Limited                      | 2         | 2.82%   |
| TP-Link                               | 1         | 1.41%   |
| Sierra Wireless                       | 1         | 1.41%   |
| Qualcomm Atheros Communications       | 1         | 1.41%   |
| Microsoft                             | 1         | 1.41%   |
| Linksys                               | 1         | 1.41%   |
| D-Link                                | 1         | 1.41%   |
| ASUSTek Computer                      | 1         | 1.41%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 1.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Computers | Percent |
|--------------------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                             | 5         | 7.04%   |
| Intel Wireless 3165                                                                                    | 4         | 5.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                          | 4         | 5.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 3         | 4.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 3         | 4.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                                  | 3         | 4.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                               | 2         | 2.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                                        | 2         | 2.82%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz]          | 2         | 2.82%   |
| Ralink MT7601U Wireless Adapter                                                                        | 2         | 2.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                                    | 2         | 2.82%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                                | 1         | 1.41%   |
| Sierra Wireless EM7305 Modem                                                                           | 1         | 1.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                               | 1         | 1.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                | 1         | 1.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                               | 1         | 1.41%   |
| Realtek RTL8723DE Wireless Network Adapter                                                             | 1         | 1.41%   |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 1         | 1.41%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                              | 1         | 1.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 1         | 1.41%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                                 | 1         | 1.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                              | 1         | 1.41%   |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1         | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                       | 1         | 1.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 1         | 1.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                         | 1         | 1.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                         | 1         | 1.41%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                                       | 1         | 1.41%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                             | 1         | 1.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                                | 1         | 1.41%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                                | 1         | 1.41%   |
| Microsoft Xbox 360 Wireless Adapter                                                                    | 1         | 1.41%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                    | 1         | 1.41%   |
| Intel Wireless 8265 / 8275                                                                             | 1         | 1.41%   |
| Intel Wireless 7265                                                                                    | 1         | 1.41%   |
| Intel Wi-Fi 6 AX201                                                                                    | 1         | 1.41%   |
| Intel Wi-Fi 6 AX200                                                                                    | 1         | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 1         | 1.41%   |
| Intel Centrino Wireless-N 130                                                                          | 1         | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                               | 1         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                        | 1         | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                       | 1         | 1.41%   |
| D-Link WLAN controller                                                                                 | 1         | 1.41%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                              | 1         | 1.41%   |
| Broadcom Limited BCM4311 802.11b/g WLAN                                                                | 1         | 1.41%   |
| Broadcom BCM43225 802.11b/g/n                                                                          | 1         | 1.41%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                         | 1         | 1.41%   |
| Broadcom BCM4311 802.11b/g WLAN                                                                        | 1         | 1.41%   |
| ASUS WL-167G v2 802.11g Adapter [Ralink RT2571W]                                                       | 1         | 1.41%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v2 Dual-Band Wireless-N Network Adapter [Ralink RT3572] | 1         | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 46        | 56.1%   |
| Intel                    | 12        | 14.63%  |
| Broadcom                 | 9         | 10.98%  |
| Qualcomm Atheros         | 7         | 8.54%   |
| Marvell Technology Group | 2         | 2.44%   |
| Broadcom Limited         | 2         | 2.44%   |
| Samsung Electronics      | 1         | 1.22%   |
| Nvidia                   | 1         | 1.22%   |
| ASIX Electronics         | 1         | 1.22%   |
| 3Com                     | 1         | 1.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 33        | 39.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10        | 12.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 4.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 2.41%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 2.41%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 2.41%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 1.2%    |
| Realtek USB 10/100 LAN                                                        | 1         | 1.2%    |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.2%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 1.2%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 1.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 1.2%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 1.2%    |
| Nvidia MCP61 Ethernet                                                         | 1         | 1.2%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 1.2%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 1.2%    |
| Intel I211 Gigabit Network Connection                                         | 1         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.2%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.2%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 1.2%    |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.2%    |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 1.2%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 1.2%    |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 1.2%    |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express                      | 1         | 1.2%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 1.2%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.2%    |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 1         | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 1         | 1.2%    |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express              | 1         | 1.2%    |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express              | 1         | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                                 | 1         | 1.2%    |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 1         | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 77        | 53.47%  |
| WiFi     | 67        | 46.53%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 57.14%  |
| Ethernet | 39        | 42.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 49        | 56.98%  |
| 1     | 32        | 37.21%  |
| 3     | 2         | 2.33%   |
| 0     | 2         | 2.33%   |
| 4     | 1         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 75        | 87.21%  |
| Yes  | 11        | 12.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 30.23%  |
| Realtek Semiconductor           | 6         | 13.95%  |
| Lite-On Technology              | 4         | 9.3%    |
| Cambridge Silicon Radio         | 4         | 9.3%    |
| Broadcom                        | 4         | 9.3%    |
| Qualcomm Atheros Communications | 3         | 6.98%   |
| IMC Networks                    | 3         | 6.98%   |
| Hewlett-Packard                 | 2         | 4.65%   |
| Dell                            | 2         | 4.65%   |
| Toshiba                         | 1         | 2.33%   |
| Apple                           | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 13.95%  |
| Realtek Bluetooth Radio                             | 4         | 9.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 9.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 4.65%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 4.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 4.65%   |
| IMC Networks Bluetooth Device                       | 2         | 4.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 4.65%   |
| Dell Wireless 355 Bluetooth                         | 2         | 4.65%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 4.65%   |
| Toshiba Askey Bluetooth Module                      | 1         | 2.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.33%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 2.33%   |
| Lite-On Bluetooth Device                            | 1         | 2.33%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.33%   |
| Intel Bluetooth Device                              | 1         | 2.33%   |
| Intel AX201 Bluetooth                               | 1         | 2.33%   |
| Intel AX200 Bluetooth                               | 1         | 2.33%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 2.33%   |
| Broadcom HP Portable Valentine                      | 1         | 2.33%   |
| Broadcom HP Bluethunder                             | 1         | 2.33%   |
| Apple Bluetooth HCI                                 | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 63        | 62.38%  |
| AMD                 | 21        | 20.79%  |
| Nvidia              | 10        | 9.9%    |
| C-Media Electronics | 2         | 1.98%   |
| Texas Instruments   | 1         | 0.99%   |
| Logitech            | 1         | 0.99%   |
| Ensoniq             | 1         | 0.99%   |
| Creative Labs       | 1         | 0.99%   |
| Blue Microphones    | 1         | 0.99%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 9.48%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 6.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 4.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 4.31%   |
| AMD FCH Azalia Controller                                                                         | 5         | 4.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 3.45%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 2.59%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 2.59%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.59%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 2.59%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.72%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.72%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.72%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.86%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.86%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.86%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.86%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 0.86%   |
| Logitech Wireless Headset                                                                         | 1         | 0.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.86%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.86%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.86%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.86%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.86%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.86%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 0.86%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 1         | 0.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.86%   |
| Ensoniq 5880B / Creative Labs CT5880                                                              | 1         | 0.86%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1         | 0.86%   |
| C-Media Electronics Multimedia Headset [Gigaware by Ignition L.P.]                                | 1         | 0.86%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.86%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 0.86%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.86%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.86%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 0.86%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.86%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.86%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 0.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.86%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 16        | 20%     |
| Samsung Electronics | 13        | 16.25%  |
| Kingston            | 11        | 13.75%  |
| SK Hynix            | 10        | 12.5%   |
| Micron Technology   | 10        | 12.5%   |
| Unknown             | 3         | 3.75%   |
| Nanya Technology    | 2         | 2.5%    |
| Elpida              | 2         | 2.5%    |
| A-DATA Technology   | 2         | 2.5%    |
| Unknown (ABCD)      | 1         | 1.25%   |
| Transcend           | 1         | 1.25%   |
| Qumo                | 1         | 1.25%   |
| Qimonda             | 1         | 1.25%   |
| GEIL                | 1         | 1.25%   |
| Corsair             | 1         | 1.25%   |
| Avant               | 1         | 1.25%   |
| 2C0C1121390963FE    | 1         | 1.25%   |
| 2C0C1121390963FD    | 1         | 1.25%   |
| 2C0C1121390963F9    | 1         | 1.25%   |
| 2C0C1121390963F8    | 1         | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 3         | 3.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 2.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1         | 1.22%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                        | 1         | 1.22%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 1.22%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1         | 1.22%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                 | 1         | 1.22%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.22%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 1.22%   |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 1         | 1.22%   |
| Unknown RAM Module 2048MB DIMM DDR2                            | 1         | 1.22%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                     | 1         | 1.22%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                     | 1         | 1.22%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                         | 1         | 1.22%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                 | 1         | 1.22%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 1         | 1.22%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                  | 1         | 1.22%   |
| Unknown RAM Module 1024MB DIMM DDR2                            | 1         | 1.22%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                     | 1         | 1.22%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 1.22%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s             | 1         | 1.22%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s                  | 1         | 1.22%   |
| SK Hynix RAM HYMP125U64CP8-S6 2048MB DIMM DDR2 49926MT/s       | 1         | 1.22%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s           | 1         | 1.22%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.22%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.22%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.22%   |
| SK Hynix RAM HMT112U6TFR8C-H9 1024MB DIMM DDR3 1333MT/s        | 1         | 1.22%   |
| SK Hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s           | 1         | 1.22%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 1.22%   |
| SK Hynix RAM H5TC4G63CFR-PBA 2048MB SODIMM DDR3 1600MT/s       | 1         | 1.22%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.22%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 1.22%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s      | 1         | 1.22%   |
| Samsung RAM M471A1G44BB0-CWE 8192MB SODIMM DDR4 3200MT/s       | 1         | 1.22%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.22%   |
| Samsung RAM M4 70T5669AZ0-CE6 2GB SODIMM DDR2 667MT/s          | 1         | 1.22%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s         | 1         | 1.22%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR 2048MT/s          | 1         | 1.22%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 1         | 1.22%   |
| Samsung RAM M378B2873FH0-CH9 1024MB DIMM DDR3 1333MT/s         | 1         | 1.22%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 1639MT/s           | 1         | 1.22%   |
| Qumo RAM Module 4096MB DIMM DDR3 1333MT/s                      | 1         | 1.22%   |
| Qimonda RAM 64T128021EDL2.5B2 1024MB SODIMM DDR2 800MT/s       | 1         | 1.22%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR 2048MT/s            | 1         | 1.22%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                       | 1         | 1.22%   |
| Micron RAM 8HTF12864AY-800G1 1024MB DIMM DDR2 800MT/s          | 1         | 1.22%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 1.22%   |
| Micron RAM 4KTF25664HZ-1G6P1 2GB SODIMM DDR3 1600MT/s          | 1         | 1.22%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 1         | 1.22%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s          | 1         | 1.22%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s           | 1         | 1.22%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 1         | 1.22%   |
| Micron RAM 16KTF51264AZ-1G6M1 4096MB DIMM DDR3 1600MT/s        | 1         | 1.22%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB DIMM DDR3 1066MT/s         | 1         | 1.22%   |
| Kingston RAM Module 2048MB SODIMM DDR2 667MT/s                 | 1         | 1.22%   |
| Kingston RAM Module 2048MB SODIMM DDR 667MT/s                  | 1         | 1.22%   |
| Kingston RAM Module 1GB DIMM DDR2 667MT/s                      | 1         | 1.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 33.33%  |
| DDR2    | 15        | 22.73%  |
| DDR4    | 12        | 18.18%  |
| SDRAM   | 8         | 12.12%  |
| Unknown | 4         | 6.06%   |
| DDR     | 3         | 4.55%   |
| LPDDR4  | 2         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 36        | 56.25%  |
| DIMM    | 27        | 42.19%  |
| FB-DIMM | 1         | 1.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 27        | 38.03%  |
| 4096  | 17        | 23.94%  |
| 8192  | 12        | 16.9%   |
| 1024  | 12        | 16.9%   |
| 16384 | 3         | 4.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 14        | 20.29%  |
| 1333    | 7         | 10.14%  |
| 3200    | 6         | 8.7%    |
| 667     | 6         | 8.7%    |
| Unknown | 6         | 8.7%    |
| 2667    | 5         | 7.25%   |
| 975     | 3         | 4.35%   |
| 800     | 3         | 4.35%   |
| 4199    | 2         | 2.9%    |
| 2400    | 2         | 2.9%    |
| 2133    | 2         | 2.9%    |
| 2048    | 2         | 2.9%    |
| 1066    | 2         | 2.9%    |
| 400     | 2         | 2.9%    |
| 49926   | 1         | 1.45%   |
| 19791   | 1         | 1.45%   |
| 3266    | 1         | 1.45%   |
| 1866    | 1         | 1.45%   |
| 1639    | 1         | 1.45%   |
| 1033    | 1         | 1.45%   |
| 133     | 1         | 1.45%   |

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


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 CU | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 27.66%  |
| Quanta                                 | 5         | 10.64%  |
| Suyin                                  | 4         | 8.51%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 8.51%   |
| IMC Networks                           | 3         | 6.38%   |
| Sunplus Innovation Technology          | 2         | 4.26%   |
| Silicon Motion                         | 2         | 4.26%   |
| Apple                                  | 2         | 4.26%   |
| Alcor Micro                            | 2         | 4.26%   |
| Z-Star Microelectronics                | 1         | 2.13%   |
| Realtek Semiconductor                  | 1         | 2.13%   |
| OmniVision Technologies                | 1         | 2.13%   |
| Microsoft                              | 1         | 2.13%   |
| Microdia                               | 1         | 2.13%   |
| Logitech                               | 1         | 2.13%   |
| Jieli Technology                       | 1         | 2.13%   |
| Hewlett-Packard                        | 1         | 2.13%   |
| Generalplus Technology                 | 1         | 2.13%   |
| Aveo Technology                        | 1         | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                               | 3         | 6.38%   |
| Quanta HP TrueVision HD Camera                              | 2         | 4.26%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 4.26%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 2.13%   |
| Suyin USB 2.0 Camera                                        | 1         | 2.13%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 2.13%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 1         | 2.13%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 2.13%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 2.13%   |
| Sunplus HD WebCam                                           | 1         | 2.13%   |
| Silicon Motion WebCam SC-10HDD13335N                        | 1         | 2.13%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 2.13%   |
| Realtek USB Camera                                          | 1         | 2.13%   |
| Quanta VGA WebCam                                           | 1         | 2.13%   |
| Quanta HP Truevision HD                                     | 1         | 2.13%   |
| Quanta HD Webcam                                            | 1         | 2.13%   |
| OmniVision OV2640 Webcam                                    | 1         | 2.13%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks         | 1         | 2.13%   |
| Microdia Integrated_Webcam_FHD                              | 1         | 2.13%   |
| Logitech HD Webcam C615                                     | 1         | 2.13%   |
| Jieli USB PHY 2.0                                           | 1         | 2.13%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 2.13%   |
| IMC Networks EasyCamera                                     | 1         | 2.13%   |
| IMC Networks 2M Integrated Webcam                           | 1         | 2.13%   |
| HP Webcam HD 2300                                           | 1         | 2.13%   |
| Generalplus CAMERA - UVC                                    | 1         | 2.13%   |
| Chicony VGA Webcam                                          | 1         | 2.13%   |
| Chicony USB 2.0 Camera                                      | 1         | 2.13%   |
| Chicony Integrated Camera                                   | 1         | 2.13%   |
| Chicony HP Webcam                                           | 1         | 2.13%   |
| Chicony HP TrueVision HD                                    | 1         | 2.13%   |
| Chicony HP High Definition 1MP Webcam                       | 1         | 2.13%   |
| Chicony HD WebCam (Asus N-series)                           | 1         | 2.13%   |
| Chicony HD WebCam                                           | 1         | 2.13%   |
| Chicony FJ Camera                                           | 1         | 2.13%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 2.13%   |
| Aveo USB2.0 Camera                                          | 1         | 2.13%   |
| Apple iPhone 5/5C/5S/6/SE                                   | 1         | 2.13%   |
| Apple Built-in iSight                                       | 1         | 2.13%   |
| Alcor Micro Asus Integrated Webcam                          | 1         | 2.13%   |
| Alcor Micro Acer Integrated Webcam                          | 1         | 2.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 3         | 75%     |
| LighTuning Technology | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor        | 2         | 50%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 25%     |
| AuthenTec AES1600                           | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| O2 Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| O2 Micro Oz776 SmartCard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 72        | 82.76%  |
| 1     | 13        | 14.94%  |
| 2     | 2         | 2.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 4         | 23.53%  |
| Fingerprint reader       | 4         | 23.53%  |
| Graphics card            | 2         | 11.76%  |
| Unassigned class         | 1         | 5.88%   |
| Storage                  | 1         | 5.88%   |
| Sound                    | 1         | 5.88%   |
| Net/ethernet             | 1         | 5.88%   |
| Dvb card                 | 1         | 5.88%   |
| Communication controller | 1         | 5.88%   |
| Chipcard                 | 1         | 5.88%   |

