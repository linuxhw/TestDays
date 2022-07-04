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

Total: 128

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Linux Lite 5.8 | 18        | 20%     |
| Linux Lite 5.0 | 17        | 18.89%  |
| Linux Lite 5.2 | 16        | 17.78%  |
| Linux Lite 5.4 | 15        | 16.67%  |
| Linux Lite 5.6 | 12        | 13.33%  |
| Linux Lite 3.8 | 5         | 5.56%   |
| Linux Lite 6.0 | 3         | 3.33%   |
| Linux Lite 4.8 | 2         | 2.22%   |
| Linux Lite 4.6 | 1         | 1.11%   |
| Linux Lite 4.4 | 1         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Lite | 89        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 6         | 6.32%   |
| 5.4.0-70-generic                   | 5         | 5.26%   |
| 5.4.0-91-generic                   | 4         | 4.21%   |
| 5.4.0-52-generic                   | 4         | 4.21%   |
| 5.4.0-40-generic                   | 4         | 4.21%   |
| 5.4.0-109-generic                  | 4         | 4.21%   |
| 5.4.0-104-generic                  | 4         | 4.21%   |
| 5.4.0-96-generic                   | 3         | 3.16%   |
| 5.4.0-58-generic                   | 3         | 3.16%   |
| 5.4.0-48-generic                   | 3         | 3.16%   |
| 5.4.0-113-generic                  | 3         | 3.16%   |
| 5.4.0-90-generic                   | 2         | 2.11%   |
| 5.4.0-88-generic                   | 2         | 2.11%   |
| 5.4.0-81-generic                   | 2         | 2.11%   |
| 5.4.0-80-generic                   | 2         | 2.11%   |
| 5.4.0-74-generic                   | 2         | 2.11%   |
| 5.4.0-54-generic                   | 2         | 2.11%   |
| 5.4.0-33-generic                   | 2         | 2.11%   |
| 5.4.0-110-generic                  | 2         | 2.11%   |
| 5.4.0-107-generic                  | 2         | 2.11%   |
| 5.4.0-105-generic                  | 2         | 2.11%   |
| 4.4.0-112-generic                  | 2         | 2.11%   |
| 5.9.0                              | 1         | 1.05%   |
| 5.4.0-99-generic                   | 1         | 1.05%   |
| 5.4.0-94-generic                   | 1         | 1.05%   |
| 5.4.0-77-generic                   | 1         | 1.05%   |
| 5.4.0-72-generic                   | 1         | 1.05%   |
| 5.4.0-71-generic                   | 1         | 1.05%   |
| 5.4.0-66-generic                   | 1         | 1.05%   |
| 5.4.0-65-generic                   | 1         | 1.05%   |
| 5.4.0-56-generic                   | 1         | 1.05%   |
| 5.4.0-45-generic                   | 1         | 1.05%   |
| 5.4.0-37-generic                   | 1         | 1.05%   |
| 5.4.0-100-generic                  | 1         | 1.05%   |
| 5.16.0                             | 1         | 1.05%   |
| 5.15.0-33-generic                  | 1         | 1.05%   |
| 5.15.0-30-generic                  | 1         | 1.05%   |
| 5.15.0-27-generic                  | 1         | 1.05%   |
| 5.15.0                             | 1         | 1.05%   |
| 5.13.0-linuxlite                   | 1         | 1.05%   |
| 5.13.0-44-lowlatency               | 1         | 1.05%   |
| 5.13.0-30-lowlatency               | 1         | 1.05%   |
| 5.10.0-051000daily20201222-generic | 1         | 1.05%   |
| 4.4.0-217-generic                  | 1         | 1.05%   |
| 4.4.0-210-generic                  | 1         | 1.05%   |
| 4.15.0-99-generic                  | 1         | 1.05%   |
| 4.15.0-91-generic                  | 1         | 1.05%   |
| 4.15.0-169-generic                 | 1         | 1.05%   |
| 4.15.0-166-generic                 | 1         | 1.05%   |
| 4.15.0-163-generic                 | 1         | 1.05%   |
| 4.15.0-162-generic                 | 1         | 1.05%   |
| 4.15.0-147-generic                 | 1         | 1.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 73        | 79.35%  |
| 4.15.0  | 5         | 5.43%   |
| 5.15.0  | 4         | 4.35%   |
| 4.4.0   | 4         | 4.35%   |
| 5.13.0  | 3         | 3.26%   |
| 5.9.0   | 1         | 1.09%   |
| 5.16.0  | 1         | 1.09%   |
| 5.10.0  | 1         | 1.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 73        | 79.35%  |
| 4.15    | 5         | 5.43%   |
| 5.15    | 4         | 4.35%   |
| 4.4     | 4         | 4.35%   |
| 5.13    | 3         | 3.26%   |
| 5.9     | 1         | 1.09%   |
| 5.16    | 1         | 1.09%   |
| 5.10    | 1         | 1.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 85        | 95.51%  |
| i686   | 4         | 4.49%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 63        | 70.79%  |
| GNOME   | 24        | 26.97%  |
| Deepin  | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 88        | 98.88%  |
| Unknown | 1         | 1.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 44        | 48.35%  |
| TDM     | 28        | 30.77%  |
| Unknown | 18        | 19.78%  |
| GDM     | 1         | 1.1%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 40        | 44.94%  |
| pt_BR | 6         | 6.74%   |
| fr_FR | 6         | 6.74%   |
| de_DE | 6         | 6.74%   |
| pl_PL | 5         | 5.62%   |
| en_GB | 5         | 5.62%   |
| ru_UA | 3         | 3.37%   |
| es_MX | 3         | 3.37%   |
| es_ES | 3         | 3.37%   |
| ru_RU | 2         | 2.25%   |
| tr_TR | 1         | 1.12%   |
| nl_NL | 1         | 1.12%   |
| it_IT | 1         | 1.12%   |
| fr_CA | 1         | 1.12%   |
| es_CO | 1         | 1.12%   |
| es_CL | 1         | 1.12%   |
| en_NZ | 1         | 1.12%   |
| en_IE | 1         | 1.12%   |
| en_CA | 1         | 1.12%   |
| da_DK | 1         | 1.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 53        | 59.55%  |
| EFI  | 36        | 40.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 77        | 86.52%  |
| Overlay | 9         | 10.11%  |
| Zfs     | 1         | 1.12%   |
| Ext3    | 1         | 1.12%   |
| Btrfs   | 1         | 1.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 33        | 37.08%  |
| MBR     | 29        | 32.58%  |
| GPT     | 27        | 30.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 80.9%   |
| Yes       | 17        | 19.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 67.78%  |
| Yes       | 29        | 32.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 18        | 20.22%  |
| ASUSTek Computer    | 12        | 13.48%  |
| Acer                | 11        | 12.36%  |
| Lenovo              | 10        | 11.24%  |
| Dell                | 9         | 10.11%  |
| Samsung Electronics | 3         | 3.37%   |
| MSI                 | 3         | 3.37%   |
| Gigabyte Technology | 3         | 3.37%   |
| Minix               | 2         | 2.25%   |
| Intel               | 2         | 2.25%   |
| Foxconn             | 2         | 2.25%   |
| ASRock              | 2         | 2.25%   |
| TR                  | 1         | 1.12%   |
| Toshiba             | 1         | 1.12%   |
| Pegatron            | 1         | 1.12%   |
| Jetway              | 1         | 1.12%   |
| Insignia            | 1         | 1.12%   |
| Google              | 1         | 1.12%   |
| Fujitsu             | 1         | 1.12%   |
| EVGA                | 1         | 1.12%   |
| Biostar             | 1         | 1.12%   |
| AWOW                | 1         | 1.12%   |
| Apple               | 1         | 1.12%   |
| ABIT                | 1         | 1.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| MSI MS-7758                            | 2         | 2.25%   |
| TR ST Pro-KN                           | 1         | 1.12%   |
| Toshiba Satellite T215D                | 1         | 1.12%   |
| Samsung NC110P/NC108P/NC111P           | 1         | 1.12%   |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 1.12%   |
| Samsung 530XBB                         | 1         | 1.12%   |
| Pegatron 520-1135la                    | 1         | 1.12%   |
| MSI FZ079AA-ABF a6625fr                | 1         | 1.12%   |
| Minix Z83-4                            | 1         | 1.12%   |
| Minix Z64                              | 1         | 1.12%   |
| Lenovo ThinkStation P320 30BH000BFR    | 1         | 1.12%   |
| Lenovo ThinkPad T400 6475E13           | 1         | 1.12%   |
| Lenovo ThinkCentre M91p 4524RS6        | 1         | 1.12%   |
| Lenovo ThinkCentre M91p 4518E2M        | 1         | 1.12%   |
| Lenovo ThinkCentre A55 9265BL7         | 1         | 1.12%   |
| Lenovo MIIX 300-10IBY 80NR             | 1         | 1.12%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1    | 1         | 1.12%   |
| Lenovo IdeaPad 320-15ABR 80XS          | 1         | 1.12%   |
| Lenovo H505S 10107                     | 1         | 1.12%   |
| Lenovo 3000 V200 0764A11               | 1         | 1.12%   |
| Jetway I61MG4                          | 1         | 1.12%   |
| Intel H61M-S1                          | 1         | 1.12%   |
| Intel DG31PR AAD97573-300              | 1         | 1.12%   |
| Insignia NS-P11W7100                   | 1         | 1.12%   |
| HP xw8600 Workstation                  | 1         | 1.12%   |
| HP x2 Detachable 10-p0XX               | 1         | 1.12%   |
| HP t5000 series                        | 1         | 1.12%   |
| HP Pavilion dv6500                     | 1         | 1.12%   |
| HP Laptop 17-by2xxx                    | 1         | 1.12%   |
| HP Laptop 15-dw3xxx                    | 1         | 1.12%   |
| HP Laptop 14-cm0xxx                    | 1         | 1.12%   |
| HP EliteBook Folio 9470m               | 1         | 1.12%   |
| HP EliteBook 8440p                     | 1         | 1.12%   |
| HP Compaq nw9440 (EY615ET#ABU)         | 1         | 1.12%   |
| HP Compaq dc7900 Convertible Minitower | 1         | 1.12%   |
| HP Compaq dc5800 Small Form Factor     | 1         | 1.12%   |
| HP Compaq CQ45                         | 1         | 1.12%   |
| HP Compaq 6005 Pro SFF PC              | 1         | 1.12%   |
| HP Compaq 2510p                        | 1         | 1.12%   |
| HP 655                                 | 1         | 1.12%   |
| HP 200-5320br                          | 1         | 1.12%   |
| HP 15 Notebook PC                      | 1         | 1.12%   |
| Google Chell                           | 1         | 1.12%   |
| Gigabyte X570 AORUS MASTER             | 1         | 1.12%   |
| Gigabyte GA-E350N                      | 1         | 1.12%   |
| Gigabyte B450M DS3H                    | 1         | 1.12%   |
| Fujitsu LIFEBOOK U747                  | 1         | 1.12%   |
| Foxconn 500B Microtower                | 1         | 1.12%   |
| Foxconn 45CMX/45GMX/45CMX-K            | 1         | 1.12%   |
| EVGA X58 SLI FTW3 Tylersburg           | 1         | 1.12%   |
| Dell Vostro1710                        | 1         | 1.12%   |
| Dell OptiPlex 790                      | 1         | 1.12%   |
| Dell MXG071                            | 1         | 1.12%   |
| Dell MXG061                            | 1         | 1.12%   |
| Dell Latitude D530                     | 1         | 1.12%   |
| Dell Inspiron 7559                     | 1         | 1.12%   |
| Dell Inspiron 560                      | 1         | 1.12%   |
| Dell Inspiron 5452                     | 1         | 1.12%   |
| Dell Inspiron 16 5620                  | 1         | 1.12%   |
| Biostar G41D3C                         | 1         | 1.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 7         | 7.87%   |
| HP Compaq            | 6         | 6.74%   |
| Dell Inspiron        | 4         | 4.49%   |
| Lenovo ThinkCentre   | 3         | 3.37%   |
| HP Laptop            | 3         | 3.37%   |
| MSI MS-7758          | 2         | 2.25%   |
| Lenovo IdeaPad       | 2         | 2.25%   |
| HP EliteBook         | 2         | 2.25%   |
| TR ST                | 1         | 1.12%   |
| Toshiba Satellite    | 1         | 1.12%   |
| Samsung NC110P       | 1         | 1.12%   |
| Samsung 905S3G       | 1         | 1.12%   |
| Samsung 530XBB       | 1         | 1.12%   |
| Pegatron 520-1135la  | 1         | 1.12%   |
| MSI FZ079AA-ABF      | 1         | 1.12%   |
| Minix Z83-4          | 1         | 1.12%   |
| Minix Z64            | 1         | 1.12%   |
| Lenovo ThinkStation  | 1         | 1.12%   |
| Lenovo ThinkPad      | 1         | 1.12%   |
| Lenovo MIIX          | 1         | 1.12%   |
| Lenovo H505S         | 1         | 1.12%   |
| Lenovo 3000          | 1         | 1.12%   |
| Jetway I61MG4        | 1         | 1.12%   |
| Intel H61M-S1        | 1         | 1.12%   |
| Intel DG31PR         | 1         | 1.12%   |
| Insignia NS-P11W7100 | 1         | 1.12%   |
| HP xw8600            | 1         | 1.12%   |
| HP x2                | 1         | 1.12%   |
| HP t5000             | 1         | 1.12%   |
| HP Pavilion          | 1         | 1.12%   |
| HP 655               | 1         | 1.12%   |
| HP 200-5320br        | 1         | 1.12%   |
| HP 15                | 1         | 1.12%   |
| Google Chell         | 1         | 1.12%   |
| Gigabyte X570        | 1         | 1.12%   |
| Gigabyte GA-E350N    | 1         | 1.12%   |
| Gigabyte B450M       | 1         | 1.12%   |
| Fujitsu LIFEBOOK     | 1         | 1.12%   |
| Foxconn 500B         | 1         | 1.12%   |
| Foxconn 45CMX        | 1         | 1.12%   |
| EVGA X58             | 1         | 1.12%   |
| Dell Vostro1710      | 1         | 1.12%   |
| Dell OptiPlex        | 1         | 1.12%   |
| Dell MXG071          | 1         | 1.12%   |
| Dell MXG061          | 1         | 1.12%   |
| Dell Latitude        | 1         | 1.12%   |
| Biostar G41D3C       | 1         | 1.12%   |
| AWOW PC              | 1         | 1.12%   |
| ASUS X751LD          | 1         | 1.12%   |
| ASUS X541SA          | 1         | 1.12%   |
| ASUS X540YA          | 1         | 1.12%   |
| ASUS VivoBook        | 1         | 1.12%   |
| ASUS TUF             | 1         | 1.12%   |
| ASUS N750JK          | 1         | 1.12%   |
| ASUS N53Jf           | 1         | 1.12%   |
| ASUS M5A78L          | 1         | 1.12%   |
| ASUS K54LY           | 1         | 1.12%   |
| ASUS K50IE           | 1         | 1.12%   |
| ASUS 900             | 1         | 1.12%   |
| ASUS 1001PX          | 1         | 1.12%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2008 | 13        | 14.61%  |
| 2012 | 10        | 11.24%  |
| 2011 | 10        | 11.24%  |
| 2010 | 9         | 10.11%  |
| 2007 | 7         | 7.87%   |
| 2018 | 6         | 6.74%   |
| 2016 | 6         | 6.74%   |
| 2020 | 5         | 5.62%   |
| 2015 | 4         | 4.49%   |
| 2014 | 4         | 4.49%   |
| 2019 | 3         | 3.37%   |
| 2017 | 3         | 3.37%   |
| 2021 | 2         | 2.25%   |
| 2009 | 2         | 2.25%   |
| 2006 | 2         | 2.25%   |
| 2022 | 1         | 1.12%   |
| 2013 | 1         | 1.12%   |
| 2004 | 1         | 1.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 50        | 56.18%  |
| Desktop    | 35        | 39.33%  |
| Tablet     | 2         | 2.25%   |
| Mini pc    | 1         | 1.12%   |
| All in one | 1         | 1.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 87        | 97.75%  |
| Enabled  | 2         | 2.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 88        | 98.88%  |
| Yes  | 1         | 1.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 30        | 33.71%  |
| 1.01-2.0   | 20        | 22.47%  |
| 4.01-8.0   | 13        | 14.61%  |
| 16.01-24.0 | 11        | 12.36%  |
| 8.01-16.0  | 6         | 6.74%   |
| 32.01-64.0 | 4         | 4.49%   |
| 0.51-1.0   | 3         | 3.37%   |
| 2.01-3.0   | 2         | 2.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 42        | 46.15%  |
| 2.01-3.0 | 18        | 19.78%  |
| 0.51-1.0 | 15        | 16.48%  |
| 3.01-4.0 | 8         | 8.79%   |
| 4.01-8.0 | 5         | 5.49%   |
| 0.01-0.5 | 3         | 3.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 61        | 68.54%  |
| 2      | 19        | 21.35%  |
| 3      | 5         | 5.62%   |
| 0      | 2         | 2.25%   |
| 5      | 1         | 1.12%   |
| 4      | 1         | 1.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 53.93%  |
| Yes       | 41        | 46.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 88.76%  |
| No        | 10        | 11.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 77.53%  |
| No        | 20        | 22.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 50.56%  |
| No        | 44        | 49.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 11        | 12.36%  |
| Brazil      | 11        | 12.36%  |
| Germany     | 7         | 7.87%   |
| France      | 6         | 6.74%   |
| Ukraine     | 5         | 5.62%   |
| UK          | 5         | 5.62%   |
| Poland      | 5         | 5.62%   |
| Mexico      | 4         | 4.49%   |
| Canada      | 4         | 4.49%   |
| Spain       | 3         | 3.37%   |
| Russia      | 3         | 3.37%   |
| Romania     | 3         | 3.37%   |
| Peru        | 3         | 3.37%   |
| Turkey      | 2         | 2.25%   |
| Netherlands | 2         | 2.25%   |
| Chile       | 2         | 2.25%   |
| Slovakia    | 1         | 1.12%   |
| Qatar       | 1         | 1.12%   |
| Philippines | 1         | 1.12%   |
| New Zealand | 1         | 1.12%   |
| Myanmar     | 1         | 1.12%   |
| Malaysia    | 1         | 1.12%   |
| Italy       | 1         | 1.12%   |
| Ireland     | 1         | 1.12%   |
| Iran        | 1         | 1.12%   |
| Guadeloupe  | 1         | 1.12%   |
| Greenland   | 1         | 1.12%   |
| Colombia    | 1         | 1.12%   |
| Australia   | 1         | 1.12%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Pabianice            | 3         | 3.33%   |
| Würzburg            | 2         | 2.22%   |
| Warsaw               | 2         | 2.22%   |
| Sao Paulo            | 2         | 2.22%   |
| Odessa               | 2         | 2.22%   |
| Lima                 | 2         | 2.22%   |
| Kyiv                 | 2         | 2.22%   |
| Yangon               | 1         | 1.11%   |
| Wiesbaden            | 1         | 1.11%   |
| Wellington           | 1         | 1.11%   |
| Waterbury            | 1         | 1.11%   |
| Wahroonga            | 1         | 1.11%   |
| Voluntari            | 1         | 1.11%   |
| Vinnytsia            | 1         | 1.11%   |
| Varennes-les-Narcy   | 1         | 1.11%   |
| Vancouver            | 1         | 1.11%   |
| Valencia             | 1         | 1.11%   |
| Trujillo             | 1         | 1.11%   |
| Thetford-Mines       | 1         | 1.11%   |
| Teresina             | 1         | 1.11%   |
| Tarragona            | 1         | 1.11%   |
| Sydney               | 1         | 1.11%   |
| Svidník             | 1         | 1.11%   |
| St. Petersburg       | 1         | 1.11%   |
| Shadrinsk            | 1         | 1.11%   |
| Sabadell             | 1         | 1.11%   |
| Rio de Janeiro       | 1         | 1.11%   |
| Queretaro            | 1         | 1.11%   |
| Purmerend            | 1         | 1.11%   |
| Porto Velho          | 1         | 1.11%   |
| Porto Alegre         | 1         | 1.11%   |
| Paris                | 1         | 1.11%   |
| Paranaque City       | 1         | 1.11%   |
| Ottawa               | 1         | 1.11%   |
| Ossining             | 1         | 1.11%   |
| Osasco               | 1         | 1.11%   |
| Oldenburg            | 1         | 1.11%   |
| Nudlingen            | 1         | 1.11%   |
| Novaci               | 1         | 1.11%   |
| Nashville            | 1         | 1.11%   |
| Narbonne             | 1         | 1.11%   |
| Moscow               | 1         | 1.11%   |
| Milan                | 1         | 1.11%   |
| Mexico City          | 1         | 1.11%   |
| Marseille            | 1         | 1.11%   |
| Madrid               | 1         | 1.11%   |
| Long Seridan         | 1         | 1.11%   |
| London               | 1         | 1.11%   |
| Les Abymes           | 1         | 1.11%   |
| La Glacerie          | 1         | 1.11%   |
| Kingston upon Thames | 1         | 1.11%   |
| Jaraguá do Sul      | 1         | 1.11%   |
| Izmir                | 1         | 1.11%   |
| Istanbul             | 1         | 1.11%   |
| Ilulissat            | 1         | 1.11%   |
| Hedon                | 1         | 1.11%   |
| Gorgan               | 1         | 1.11%   |
| Frankfurt am Main    | 1         | 1.11%   |
| Fortin de las Flores | 1         | 1.11%   |
| Eggenfelden          | 1         | 1.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 27     | 22.32%  |
| WDC                 | 21        | 28     | 18.75%  |
| Toshiba             | 11        | 12     | 9.82%   |
| Samsung Electronics | 10        | 11     | 8.93%   |
| Unknown             | 7         | 9      | 6.25%   |
| Kingston            | 7         | 9      | 6.25%   |
| SanDisk             | 4         | 4      | 3.57%   |
| Hitachi             | 4         | 4      | 3.57%   |
| Goodram             | 3         | 3      | 2.68%   |
| Crucial             | 3         | 3      | 2.68%   |
| Micron Technology   | 2         | 3      | 1.79%   |
| HGST                | 2         | 2      | 1.79%   |
| SK hynix            | 1         | 1      | 0.89%   |
| PNY                 | 1         | 1      | 0.89%   |
| Phison              | 1         | 1      | 0.89%   |
| OCZ                 | 1         | 1      | 0.89%   |
| Maxtor              | 1         | 1      | 0.89%   |
| Mass                | 1         | 1      | 0.89%   |
| LITEON              | 1         | 1      | 0.89%   |
| Intel               | 1         | 1      | 0.89%   |
| HPE                 | 1         | 1      | 0.89%   |
| Hewlett-Packard     | 1         | 1      | 0.89%   |
| Gigabyte Technology | 1         | 1      | 0.89%   |
| ASUS-PHISON         | 1         | 2      | 0.89%   |
| ASMT                | 1         | 1      | 0.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                | 3         | 2.5%    |
| Toshiba MQ01ABF050 500GB              | 3         | 2.5%    |
| Seagate ST500DM002-1BD142 500GB       | 3         | 2.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 2         | 1.67%   |
| WDC WD5000AAKX-001CA0 500GB           | 2         | 1.67%   |
| WDC WD10JPVX-75JC3T0 1TB              | 2         | 1.67%   |
| Seagate ST9320325AS 320GB             | 2         | 1.67%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 1.67%   |
| WDC WDS250G2B0A 250GB SSD             | 1         | 0.83%   |
| WDC WD800JD-60LSA0 80GB               | 1         | 0.83%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 0.83%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 0.83%   |
| WDC WD5000AAKS-60WWPA0 500GB          | 1         | 0.83%   |
| WDC WD5000AACS-00G8B1 500GB           | 1         | 0.83%   |
| WDC WD2500BEVE-00A0HT0 250GB          | 1         | 0.83%   |
| WDC WD20PURX-64PFUY0 2TB              | 1         | 0.83%   |
| WDC WD2005FBYZ-01YCBB2 2TB            | 1         | 0.83%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.83%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 0.83%   |
| WDC WD10EZEX-07WN4A0 1TB              | 1         | 0.83%   |
| WDC WD10EADS-00L5B1 1TB               | 1         | 0.83%   |
| WDC WD1003FBYX-01Y7B1 1TB             | 1         | 0.83%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB    | 1         | 0.83%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 0.83%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB  | 1         | 0.83%   |
| Unknown SD64G  64GB                   | 1         | 0.83%   |
| Unknown SC64G  64GB                   | 1         | 0.83%   |
| Unknown NCard  32GB                   | 1         | 0.83%   |
| Unknown HBG4a2  32GB                  | 1         | 0.83%   |
| Unknown DA4064  64GB                  | 1         | 0.83%   |
| Unknown BGND3R  32GB                  | 1         | 0.83%   |
| Toshiba MQ04ABF100 1TB                | 1         | 0.83%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.83%   |
| Toshiba MQ01ABD050 500GB              | 1         | 0.83%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 0.83%   |
| Toshiba MK1059GSM 1TB                 | 1         | 0.83%   |
| Toshiba MK1011GAH 100GB               | 1         | 0.83%   |
| Toshiba HDWD110 1TB                   | 1         | 0.83%   |
| Toshiba DT01ACA100 1TB                | 1         | 0.83%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 0.83%   |
| Seagate ST980811AS 80GB               | 1         | 0.83%   |
| Seagate ST9500423AS 500GB             | 1         | 0.83%   |
| Seagate ST9500325AS 500GB             | 1         | 0.83%   |
| Seagate ST9160823ASG 160GB            | 1         | 0.83%   |
| Seagate ST9160301AS 160GB             | 1         | 0.83%   |
| Seagate ST640LM0 00 HM641JI 640GB     | 1         | 0.83%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 0.83%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 0.83%   |
| Seagate ST500LM030-1RK17D 500GB       | 1         | 0.83%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 0.83%   |
| Seagate ST500DM002-1BC142 500GB       | 1         | 0.83%   |
| Seagate ST3750640NS 752GB             | 1         | 0.83%   |
| Seagate ST3320620A 320GB              | 1         | 0.83%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 0.83%   |
| Seagate ST320LM001 HN-M320MBB 320GB   | 1         | 0.83%   |
| Seagate ST320LM000 HM321HI 320GB      | 1         | 0.83%   |
| Seagate ST3120026A 120GB              | 1         | 0.83%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 0.83%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 0.83%   |
| Seagate ST1000LM010-9YH146 1TB        | 1         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 27     | 40.98%  |
| WDC                 | 16        | 19     | 26.23%  |
| Toshiba             | 11        | 12     | 18.03%  |
| Hitachi             | 4         | 4      | 6.56%   |
| Samsung Electronics | 2         | 3      | 3.28%   |
| HGST                | 2         | 2      | 3.28%   |
| Maxtor              | 1         | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 8      | 18.18%  |
| Samsung Electronics | 4         | 4      | 12.12%  |
| WDC                 | 3         | 4      | 9.09%   |
| SanDisk             | 3         | 3      | 9.09%   |
| Goodram             | 3         | 3      | 9.09%   |
| Crucial             | 3         | 3      | 9.09%   |
| Micron Technology   | 2         | 3      | 6.06%   |
| SK hynix            | 1         | 1      | 3.03%   |
| PNY                 | 1         | 1      | 3.03%   |
| OCZ                 | 1         | 1      | 3.03%   |
| LITEON              | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |
| Gigabyte Technology | 1         | 1      | 3.03%   |
| ASUS-PHISON         | 1         | 2      | 3.03%   |
| ASMT                | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 56        | 68     | 53.33%  |
| SSD     | 31        | 38     | 29.52%  |
| MMC     | 8         | 10     | 7.62%   |
| NVMe    | 8         | 11     | 7.62%   |
| Unknown | 2         | 2      | 1.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 73        | 104    | 78.49%  |
| NVMe | 8         | 11     | 8.6%    |
| MMC  | 8         | 10     | 8.6%    |
| SAS  | 4         | 4      | 4.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 60        | 79     | 70.59%  |
| 0.51-1.0   | 21        | 22     | 24.71%  |
| 1.01-2.0   | 4         | 5      | 4.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 27.78%  |
| 251-500        | 20        | 22.22%  |
| 51-100         | 14        | 15.56%  |
| 1-20           | 9         | 10%     |
| 21-50          | 8         | 8.89%   |
| 501-1000       | 7         | 7.78%   |
| More than 3000 | 4         | 4.44%   |
| 1001-2000      | 3         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 46        | 50.55%  |
| 21-50     | 18        | 19.78%  |
| 51-100    | 11        | 12.09%  |
| 101-250   | 8         | 8.79%   |
| 251-500   | 3         | 3.3%    |
| 2001-3000 | 2         | 2.2%    |
| 501-1000  | 2         | 2.2%    |
| 1001-2000 | 1         | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD800JD-60LSA0 80GB         | 1         | 1      | 6.25%   |
| WDC WD5000AAKX-001CA0 500GB     | 1         | 1      | 6.25%   |
| WDC WD5000AAKS-60WWPA0 500GB    | 1         | 1      | 6.25%   |
| WDC WD10JPVX-22JC3T0 1TB        | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD050 500GB        | 1         | 1      | 6.25%   |
| Toshiba MK1059GSM 1TB           | 1         | 1      | 6.25%   |
| Seagate ST980811AS 80GB         | 1         | 1      | 6.25%   |
| Seagate ST9500423AS 500GB       | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB       | 1         | 1      | 6.25%   |
| Seagate ST9320325AS 320GB       | 1         | 1      | 6.25%   |
| Seagate ST9160823ASG 160GB      | 1         | 1      | 6.25%   |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 6.25%   |
| Seagate ST3120026A 120GB        | 1         | 1      | 6.25%   |
| Hitachi HTS545016B9A300 160GB   | 1         | 1      | 6.25%   |
| Hitachi HDS722020ALA330 2TB     | 1         | 1      | 6.25%   |
| Hitachi HDS721616PLA380 160GB   | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 43.75%  |
| WDC     | 4         | 4      | 25%     |
| Hitachi | 3         | 3      | 18.75%  |
| Toshiba | 2         | 2      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 43.75%  |
| WDC     | 4         | 4      | 25%     |
| Hitachi | 3         | 3      | 18.75%  |
| Toshiba | 2         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 16     | 100%    |

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
| Detected | 39        | 61     | 42.86%  |
| Works    | 38        | 52     | 41.76%  |
| Malfunc  | 14        | 16     | 15.38%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 64        | 67.37%  |
| AMD                         | 16        | 16.84%  |
| Samsung Electronics         | 4         | 4.21%   |
| SanDisk                     | 3         | 3.16%   |
| Nvidia                      | 2         | 2.11%   |
| Phison Electronics          | 1         | 1.05%   |
| Marvell Technology Group    | 1         | 1.05%   |
| LSI Logic / Symbios Logic   | 1         | 1.05%   |
| Kingston Technology Company | 1         | 1.05%   |
| JMicron Technology          | 1         | 1.05%   |
| Broadcom / LSI              | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10        | 7.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 6.3%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 4.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 4.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 3.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 3.15%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3         | 2.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.57%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.57%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.57%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 2         | 1.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1.57%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 1.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 1.57%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.57%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 1.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.79%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.79%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.79%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.79%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.79%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.79%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1         | 0.79%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1         | 0.79%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1         | 0.79%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 0.79%   |
| JMicron JMB368 IDE controller                                                           | 1         | 0.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 0.79%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                             | 1         | 0.79%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.79%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1         | 0.79%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1         | 0.79%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 0.79%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 0.79%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 1         | 0.79%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                  | 1         | 0.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 0.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 0.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 0.79%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 1         | 0.79%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1         | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 60        | 57.14%  |
| IDE  | 33        | 31.43%  |
| NVMe | 8         | 7.62%   |
| RAID | 3         | 2.86%   |
| SCSI | 1         | 0.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 72        | 80.9%   |
| AMD    | 17        | 19.1%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 2.25%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 2.25%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 2.25%   |
| Intel Core 2 CPU T7600 @ 2.33GHz            | 2         | 2.25%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 2.25%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 2.25%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 1.12%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1         | 1.12%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.12%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 1.12%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 1.12%   |
| Intel Pentium D CPU 3.40GHz                 | 1         | 1.12%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1.12%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.12%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.12%   |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1         | 1.12%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.12%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 1.12%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 1.12%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.12%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 1.12%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.12%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.12%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.12%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 1.12%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1         | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.12%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1         | 1.12%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.12%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1         | 1.12%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1         | 1.12%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1         | 1.12%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.12%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.12%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.12%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1         | 1.12%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1         | 1.12%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.12%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 1.12%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1         | 1.12%   |
| Intel Core 2 Extreme CPU X7900 @ 2.80GHz    | 1         | 1.12%   |
| Intel Core 2 Duo CPU U7600 @ 1.20GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 1         | 1.12%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1         | 1.12%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.12%   |
| Intel Celeron M processor 900MHz            | 1         | 1.12%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 1.12%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1         | 1.12%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 1         | 1.12%   |
| Intel Celeron CPU B830 @ 1.80GHz            | 1         | 1.12%   |
| Intel Celeron CPU 723 @ 1.20GHz             | 1         | 1.12%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 12        | 13.48%  |
| Intel Core i5           | 10        | 11.24%  |
| Intel Core i3           | 8         | 8.99%   |
| Intel Core i7           | 7         | 7.87%   |
| Intel Atom              | 7         | 7.87%   |
| Intel Celeron           | 6         | 6.74%   |
| Intel Pentium           | 5         | 5.62%   |
| Intel Pentium Dual-Core | 4         | 4.49%   |
| Other                   | 3         | 3.37%   |
| Intel Xeon              | 2         | 2.25%   |
| Intel Core 2            | 2         | 2.25%   |
| AMD E2                  | 2         | 2.25%   |
| AMD E                   | 2         | 2.25%   |
| Intel Pentium Dual      | 1         | 1.12%   |
| Intel Pentium D         | 1         | 1.12%   |
| Intel Genuine           | 1         | 1.12%   |
| Intel Core m7           | 1         | 1.12%   |
| Intel Core 2 Extreme    | 1         | 1.12%   |
| Intel Celeron M         | 1         | 1.12%   |
| AMD Turion 64 X2 Mobile | 1         | 1.12%   |
| AMD Ryzen 9             | 1         | 1.12%   |
| AMD Ryzen 5             | 1         | 1.12%   |
| AMD Ryzen 3             | 1         | 1.12%   |
| AMD Quad-Core           | 1         | 1.12%   |
| AMD Phenom II X2        | 1         | 1.12%   |
| AMD FX                  | 1         | 1.12%   |
| AMD Athlon II X2        | 1         | 1.12%   |
| AMD Athlon II Neo       | 1         | 1.12%   |
| AMD A8                  | 1         | 1.12%   |
| AMD A6                  | 1         | 1.12%   |
| AMD A12                 | 1         | 1.12%   |
| AMD A10                 | 1         | 1.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 51        | 57.3%   |
| 4      | 26        | 29.21%  |
| 1      | 5         | 5.62%   |
| 6      | 4         | 4.49%   |
| 12     | 1         | 1.12%   |
| 10     | 1         | 1.12%   |
| 8      | 1         | 1.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 88        | 98.88%  |
| 2      | 1         | 1.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 65.17%  |
| 2      | 31        | 34.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 87        | 97.75%  |
| 32-bit         | 2         | 2.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 10        | 11.24%  |
| 0x206a7    | 9         | 10.11%  |
| Unknown    | 7         | 7.87%   |
| 0x6fd      | 4         | 4.49%   |
| 0x30678    | 4         | 4.49%   |
| 0x10676    | 4         | 4.49%   |
| 0x6fb      | 3         | 3.37%   |
| 0x406c4    | 3         | 3.37%   |
| 0x20655    | 3         | 3.37%   |
| 0x010000c8 | 3         | 3.37%   |
| 0x806c1    | 2         | 2.25%   |
| 0x6f6      | 2         | 2.25%   |
| 0x506c9    | 2         | 2.25%   |
| 0x406c3    | 2         | 2.25%   |
| 0x05000119 | 2         | 2.25%   |
| 0xf64      | 1         | 1.12%   |
| 0xa0653    | 1         | 1.12%   |
| 0x906ea    | 1         | 1.12%   |
| 0x906e9    | 1         | 1.12%   |
| 0x906a4    | 1         | 1.12%   |
| 0x806ec    | 1         | 1.12%   |
| 0x806eb    | 1         | 1.12%   |
| 0x806ea    | 1         | 1.12%   |
| 0x806e9    | 1         | 1.12%   |
| 0x706a1    | 1         | 1.12%   |
| 0x6fa      | 1         | 1.12%   |
| 0x6d8      | 1         | 1.12%   |
| 0x506e3    | 1         | 1.12%   |
| 0x406e3    | 1         | 1.12%   |
| 0x40651    | 1         | 1.12%   |
| 0x306c3    | 1         | 1.12%   |
| 0x306a9    | 1         | 1.12%   |
| 0x30661    | 1         | 1.12%   |
| 0x206c2    | 1         | 1.12%   |
| 0x106ca    | 1         | 1.12%   |
| 0x08701013 | 1         | 1.12%   |
| 0x0810100b | 1         | 1.12%   |
| 0x0800820d | 1         | 1.12%   |
| 0x06006705 | 1         | 1.12%   |
| 0x06006118 | 1         | 1.12%   |
| 0x06001119 | 1         | 1.12%   |
| 0x06000852 | 1         | 1.12%   |
| 0x05000029 | 1         | 1.12%   |
| 0x03000027 | 1         | 1.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 14        | 15.73%  |
| Core             | 10        | 11.24%  |
| Silvermont       | 9         | 10.11%  |
| SandyBridge      | 9         | 10.11%  |
| KabyLake         | 7         | 7.87%   |
| Westmere         | 4         | 4.49%   |
| K10              | 3         | 3.37%   |
| IvyBridge        | 3         | 3.37%   |
| Bobcat           | 3         | 3.37%   |
| TigerLake        | 2         | 2.25%   |
| Skylake          | 2         | 2.25%   |
| Piledriver       | 2         | 2.25%   |
| P6               | 2         | 2.25%   |
| Haswell          | 2         | 2.25%   |
| Goldmont         | 2         | 2.25%   |
| Excavator        | 2         | 2.25%   |
| Bonnell          | 2         | 2.25%   |
| Zen+             | 1         | 1.12%   |
| Zen 2            | 1         | 1.12%   |
| Zen              | 1         | 1.12%   |
| Puma             | 1         | 1.12%   |
| NetBurst         | 1         | 1.12%   |
| K8 Hammer        | 1         | 1.12%   |
| K10 Llano        | 1         | 1.12%   |
| Jaguar           | 1         | 1.12%   |
| Goldmont plus    | 1         | 1.12%   |
| CometLake        | 1         | 1.12%   |
| Alderlake Hybrid | 1         | 1.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 53        | 55.79%  |
| Nvidia | 22        | 23.16%  |
| AMD    | 20        | 21.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 4.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 4.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 4.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 3.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 3.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.94%   |
| Intel HD Graphics 500                                                                    | 2         | 1.94%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 1.94%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 1.94%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.97%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.97%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.97%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.97%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.97%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.97%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.97%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 0.97%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 0.97%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1         | 0.97%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 0.97%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 0.97%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1         | 0.97%   |
| Nvidia G84 [GeForce 8400 GS]                                                             | 1         | 0.97%   |
| Nvidia G72 [GeForce 7300 GS]                                                             | 1         | 0.97%   |
| Nvidia G71M [GeForce Go 7950 GTX]                                                        | 1         | 0.97%   |
| Nvidia G71GLM [Quadro FX 1500M]                                                          | 1         | 0.97%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 0.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.97%   |
| Intel VGA compatible controller                                                          | 1         | 0.97%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.97%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.97%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.97%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 0.97%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 0.97%   |
| Intel HD Graphics 630                                                                    | 1         | 0.97%   |
| Intel HD Graphics 620                                                                    | 1         | 0.97%   |
| Intel HD Graphics 530                                                                    | 1         | 0.97%   |
| Intel HD Graphics 515                                                                    | 1         | 0.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.97%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.97%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.97%   |
| Intel 82Q33 Express Integrated Graphics Controller                                       | 1         | 0.97%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 0.97%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1         | 0.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.97%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 0.97%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 0.97%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 0.97%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 52.81%  |
| 1 x AMD        | 18        | 20.22%  |
| 1 x Nvidia     | 16        | 17.98%  |
| Intel + Nvidia | 6         | 6.74%   |
| 2 x AMD        | 2         | 2.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 76        | 84.44%  |
| Proprietary | 13        | 14.44%  |
| Unknown     | 1         | 1.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 53.93%  |
| 0.01-0.5   | 24        | 26.97%  |
| 1.01-2.0   | 6         | 6.74%   |
| 0.51-1.0   | 6         | 6.74%   |
| 3.01-4.0   | 3         | 3.37%   |
| 5.01-6.0   | 2         | 2.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 18.68%  |
| AU Optronics            | 12        | 13.19%  |
| LG Display              | 8         | 8.79%   |
| Hewlett-Packard         | 7         | 7.69%   |
| Goldstar                | 6         | 6.59%   |
| Chi Mei Optoelectronics | 6         | 6.59%   |
| Chimei Innolux          | 4         | 4.4%    |
| BOE                     | 4         | 4.4%    |
| Acer                    | 4         | 4.4%    |
| NEC Computers           | 3         | 3.3%    |
| ViewSonic               | 2         | 2.2%    |
| Sony                    | 2         | 2.2%    |
| Seiko/Epson             | 1         | 1.1%    |
| SANYO                   | 1         | 1.1%    |
| Philips                 | 1         | 1.1%    |
| PANDA                   | 1         | 1.1%    |
| MSI                     | 1         | 1.1%    |
| LG Philips              | 1         | 1.1%    |
| Lenovo                  | 1         | 1.1%    |
| Hitachi                 | 1         | 1.1%    |
| HannStar                | 1         | 1.1%    |
| eMachines               | 1         | 1.1%    |
| CPT                     | 1         | 1.1%    |
| BenQ                    | 1         | 1.1%    |
| Apple                   | 1         | 1.1%    |
| AOC                     | 1         | 1.1%    |
| Ancor Communications    | 1         | 1.1%    |
| Unknown                 | 1         | 1.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 2.08%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1         | 1.04%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1         | 1.04%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1         | 1.04%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 1.04%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                    | 1         | 1.04%   |
| Seiko/Epson LCD Monitor                                               | 1         | 1.04%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 1.04%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1         | 1.04%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 1.04%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch  | 1         | 1.04%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 1.04%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1         | 1.04%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 1.04%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1         | 1.04%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 1.04%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                    | 1         | 1.04%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 1.04%   |
| NEC Computers LCD1990SXi NEC66AC 1280x1024 376x301mm 19.0-inch        | 1         | 1.04%   |
| NEC Computers EA244WMi NEC68D7 1920x1200 519x324mm 24.1-inch          | 1         | 1.04%   |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch            | 1         | 1.04%   |
| MSI G271 MSI3CB5 1920x1080 598x336mm 27.0-inch                        | 1         | 1.04%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 1.04%   |
| LG Display LCD Monitor LGD03E3 1366x768 309x174mm 14.0-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch           | 1         | 1.04%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch               | 1         | 1.04%   |
| Hitachi N91W DVI HIT6D0D 1440x900 410x260mm 19.1-inch                 | 1         | 1.04%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 337x270mm 17.0-inch            | 1         | 1.04%   |
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 1         | 1.04%   |
| Hewlett-Packard P201 HWP3056 1600x900 443x249mm 20.0-inch             | 1         | 1.04%   |
| Hewlett-Packard LV2311 HWP3006 1920x1080 510x287mm 23.0-inch          | 1         | 1.04%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1         | 1.04%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1         | 1.04%   |
| Hewlett-Packard f1503 HWP2590 1024x768 304x228mm 15.0-inch            | 1         | 1.04%   |
| Hewlett-Packard All-in-One HWP4211 1920x1080 509x286mm 23.0-inch      | 1         | 1.04%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.04%   |
| Goldstar W2254 GSM56DE 1680x1050 474x296mm 22.0-inch                  | 1         | 1.04%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                  | 1         | 1.04%   |
| Goldstar LS1920wG GSM4BF0 1366x768 410x230mm 18.5-inch                | 1         | 1.04%   |
| Goldstar 22EA53 GSM59A5 1920x1080 480x270mm 21.7-inch                 | 1         | 1.04%   |
| eMachines E190HQV EMA0212 1280x1024 440x250mm 19.9-inch               | 1         | 1.04%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                  | 1         | 1.04%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 1         | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 25        | 27.47%  |
| 1920x1080 (FHD)    | 23        | 25.27%  |
| 1920x1200 (WUXGA)  | 10        | 10.99%  |
| 1280x800 (WXGA)    | 6         | 6.59%   |
| 3840x2160 (4K)     | 5         | 5.49%   |
| 1600x900 (HD+)     | 4         | 4.4%    |
| 1280x1024 (SXGA)   | 4         | 4.4%    |
| 1680x1050 (WSXGA+) | 3         | 3.3%    |
| 1440x900 (WXGA+)   | 3         | 3.3%    |
| Unknown            | 2         | 2.2%    |
| 5280x1080          | 1         | 1.1%    |
| 3840x2400          | 1         | 1.1%    |
| 2560x1440 (QHD)    | 1         | 1.1%    |
| 1360x768           | 1         | 1.1%    |
| 1024x768 (XGA)     | 1         | 1.1%    |
| 1024x600           | 1         | 1.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 20        | 21.74%  |
| 17      | 9         | 9.78%   |
| 24      | 7         | 7.61%   |
| 14      | 7         | 7.61%   |
| Unknown | 7         | 7.61%   |
| 21      | 6         | 6.52%   |
| 19      | 5         | 5.43%   |
| 18      | 4         | 4.35%   |
| 13      | 4         | 4.35%   |
| 27      | 3         | 3.26%   |
| 23      | 3         | 3.26%   |
| 20      | 3         | 3.26%   |
| 11      | 3         | 3.26%   |
| 10      | 3         | 3.26%   |
| 12      | 2         | 2.17%   |
| 72      | 1         | 1.09%   |
| 65      | 1         | 1.09%   |
| 46      | 1         | 1.09%   |
| 28      | 1         | 1.09%   |
| 22      | 1         | 1.09%   |
| 16      | 1         | 1.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 35.16%  |
| 401-500     | 16        | 17.58%  |
| 501-600     | 13        | 14.29%  |
| 201-300     | 10        | 10.99%  |
| 351-400     | 9         | 9.89%   |
| Unknown     | 7         | 7.69%   |
| 1001-1500   | 2         | 2.2%    |
| 601-700     | 1         | 1.1%    |
| 1501-2000   | 1         | 1.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 54        | 63.53%  |
| 16/10   | 21        | 24.71%  |
| Unknown | 5         | 5.88%   |
| 5/4     | 4         | 4.71%   |
| 4/3     | 1         | 1.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 21.74%  |
| 201-250        | 11        | 11.96%  |
| 81-90          | 9         | 9.78%   |
| 151-200        | 9         | 9.78%   |
| Unknown        | 7         | 7.61%   |
| 141-150        | 6         | 6.52%   |
| 251-300        | 5         | 5.43%   |
| 131-140        | 4         | 4.35%   |
| 51-60          | 3         | 3.26%   |
| 41-50          | 3         | 3.26%   |
| 301-350        | 3         | 3.26%   |
| 121-130        | 3         | 3.26%   |
| More than 1000 | 2         | 2.17%   |
| 71-80          | 2         | 2.17%   |
| 61-70          | 2         | 2.17%   |
| 351-500        | 1         | 1.09%   |
| 111-120        | 1         | 1.09%   |
| 501-1000       | 1         | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 33        | 37.08%  |
| 101-120       | 23        | 25.84%  |
| 121-160       | 20        | 22.47%  |
| Unknown       | 7         | 7.87%   |
| More than 240 | 2         | 2.25%   |
| 1-50          | 2         | 2.25%   |
| 161-240       | 2         | 2.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 79        | 87.78%  |
| 2     | 10        | 11.11%  |
| 3     | 1         | 1.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 47        | 34.31%  |
| Intel                                 | 32        | 23.36%  |
| Qualcomm Atheros                      | 21        | 15.33%  |
| Broadcom                              | 14        | 10.22%  |
| Broadcom Limited                      | 4         | 2.92%   |
| Ralink Technology                     | 3         | 2.19%   |
| Ralink                                | 2         | 1.46%   |
| Marvell Technology Group              | 2         | 1.46%   |
| TP-Link                               | 1         | 0.73%   |
| Sierra Wireless                       | 1         | 0.73%   |
| Samsung Electronics                   | 1         | 0.73%   |
| Qualcomm Atheros Communications       | 1         | 0.73%   |
| Nvidia                                | 1         | 0.73%   |
| Microsoft                             | 1         | 0.73%   |
| Linksys                               | 1         | 0.73%   |
| D-Link                                | 1         | 0.73%   |
| ASUSTek Computer                      | 1         | 0.73%   |
| ASIX Electronics                      | 1         | 0.73%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.73%   |
| 3Com                                  | 1         | 0.73%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 33        | 20.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 10        | 6.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 3.16%   |
| Intel Wireless 3165                                                                           | 4         | 2.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4         | 2.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 1.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 1.27%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 1.27%   |
| Ralink MT7601U Wireless Adapter                                                               | 2         | 1.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 2         | 1.27%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2         | 1.27%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                        | 2         | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.27%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 0.63%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1         | 0.63%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.63%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 0.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 0.63%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.63%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.63%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 0.63%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                    | 1         | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.63%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1         | 0.63%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.63%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 0.63%   |
| Nvidia MCP61 Ethernet                                                                         | 1         | 0.63%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1         | 0.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.63%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                           | 1         | 0.63%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 0.63%   |
| Intel Wireless 7265                                                                           | 1         | 0.63%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 0.63%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 0.63%   |
| Intel I211 Gigabit Network Connection                                                         | 1         | 0.63%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 1         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                                         | 1         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 22        | 30.14%  |
| Qualcomm Atheros                      | 19        | 26.03%  |
| Realtek Semiconductor                 | 12        | 16.44%  |
| Broadcom                              | 5         | 6.85%   |
| Ralink Technology                     | 3         | 4.11%   |
| Ralink                                | 2         | 2.74%   |
| Broadcom Limited                      | 2         | 2.74%   |
| TP-Link                               | 1         | 1.37%   |
| Sierra Wireless                       | 1         | 1.37%   |
| Qualcomm Atheros Communications       | 1         | 1.37%   |
| Microsoft                             | 1         | 1.37%   |
| Linksys                               | 1         | 1.37%   |
| D-Link                                | 1         | 1.37%   |
| ASUSTek Computer                      | 1         | 1.37%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Computers | Percent |
|--------------------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                             | 5         | 6.85%   |
| Intel Wireless 3165                                                                                    | 4         | 5.48%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                          | 4         | 5.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 3         | 4.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 3         | 4.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                                  | 3         | 4.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                               | 2         | 2.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                                        | 2         | 2.74%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz]          | 2         | 2.74%   |
| Ralink MT7601U Wireless Adapter                                                                        | 2         | 2.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                                    | 2         | 2.74%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                                | 1         | 1.37%   |
| Sierra Wireless EM7305 Modem                                                                           | 1         | 1.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                               | 1         | 1.37%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                | 1         | 1.37%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                               | 1         | 1.37%   |
| Realtek RTL8723DE Wireless Network Adapter                                                             | 1         | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 1         | 1.37%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                              | 1         | 1.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 1         | 1.37%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                                 | 1         | 1.37%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                              | 1         | 1.37%   |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                       | 1         | 1.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 1         | 1.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                         | 1         | 1.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                         | 1         | 1.37%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                                       | 1         | 1.37%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                             | 1         | 1.37%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                                | 1         | 1.37%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                                | 1         | 1.37%   |
| Microsoft Xbox 360 Wireless Adapter                                                                    | 1         | 1.37%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                    | 1         | 1.37%   |
| Intel Wireless 8265 / 8275                                                                             | 1         | 1.37%   |
| Intel Wireless 7265                                                                                    | 1         | 1.37%   |
| Intel Wi-Fi 6 AX201                                                                                    | 1         | 1.37%   |
| Intel Wi-Fi 6 AX200                                                                                    | 1         | 1.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                                                        | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 1         | 1.37%   |
| Intel Centrino Wireless-N 130                                                                          | 1         | 1.37%   |
| Intel Centrino Advanced-N 6200                                                                         | 1         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                               | 1         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                        | 1         | 1.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                       | 1         | 1.37%   |
| D-Link WLAN controller                                                                                 | 1         | 1.37%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                              | 1         | 1.37%   |
| Broadcom Limited BCM4311 802.11b/g WLAN                                                                | 1         | 1.37%   |
| Broadcom BCM43225 802.11b/g/n                                                                          | 1         | 1.37%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                         | 1         | 1.37%   |
| Broadcom BCM4311 802.11b/g WLAN                                                                        | 1         | 1.37%   |
| ASUS WL-167G v2 802.11g Adapter [Ralink RT2571W]                                                       | 1         | 1.37%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v2 Dual-Band Wireless-N Network Adapter [Ralink RT3572] | 1         | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 46        | 54.76%  |
| Intel                    | 14        | 16.67%  |
| Broadcom                 | 9         | 10.71%  |
| Qualcomm Atheros         | 7         | 8.33%   |
| Marvell Technology Group | 2         | 2.38%   |
| Broadcom Limited         | 2         | 2.38%   |
| Samsung Electronics      | 1         | 1.19%   |
| Nvidia                   | 1         | 1.19%   |
| ASIX Electronics         | 1         | 1.19%   |
| 3Com                     | 1         | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 33        | 38.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10        | 11.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 4.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 2.35%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 2.35%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 2.35%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 1.18%   |
| Realtek USB 10/100 LAN                                                        | 1         | 1.18%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.18%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.18%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 1.18%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 1.18%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 1.18%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 1.18%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 1.18%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 1.18%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 1.18%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 1.18%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.18%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 1.18%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.18%   |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 1.18%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 1.18%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 1.18%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express                      | 1         | 1.18%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 1.18%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.18%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 1         | 1.18%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 1         | 1.18%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express              | 1         | 1.18%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express              | 1         | 1.18%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1         | 1.18%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 1         | 1.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 79        | 53.38%  |
| WiFi     | 69        | 46.62%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 54        | 57.45%  |
| Ethernet | 40        | 42.55%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 50        | 56.18%  |
| 1     | 34        | 38.2%   |
| 3     | 2         | 2.25%   |
| 0     | 2         | 2.25%   |
| 4     | 1         | 1.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 76        | 85.39%  |
| Yes  | 13        | 14.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 31.11%  |
| Realtek Semiconductor           | 6         | 13.33%  |
| Lite-On Technology              | 4         | 8.89%   |
| Cambridge Silicon Radio         | 4         | 8.89%   |
| Broadcom                        | 4         | 8.89%   |
| Qualcomm Atheros Communications | 3         | 6.67%   |
| IMC Networks                    | 3         | 6.67%   |
| Hewlett-Packard                 | 3         | 6.67%   |
| Dell                            | 2         | 4.44%   |
| Toshiba                         | 1         | 2.22%   |
| Apple                           | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 13.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 8.89%   |
| Realtek Bluetooth Radio                             | 3         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 4.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 4.44%   |
| Intel Bluetooth Device                              | 2         | 4.44%   |
| IMC Networks Bluetooth Device                       | 2         | 4.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 4.44%   |
| Dell Wireless 355 Bluetooth                         | 2         | 4.44%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 4.44%   |
| Toshiba Askey Bluetooth Module                      | 1         | 2.22%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.22%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 2.22%   |
| Lite-On Bluetooth Device                            | 1         | 2.22%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.22%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.22%   |
| Intel AX200 Bluetooth                               | 1         | 2.22%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 2.22%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.22%   |
| Broadcom HP Portable Valentine                      | 1         | 2.22%   |
| Broadcom HP Bluethunder                             | 1         | 2.22%   |
| Apple Bluetooth HCI                                 | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 66        | 62.26%  |
| AMD                   | 21        | 19.81%  |
| Nvidia                | 11        | 10.38%  |
| C-Media Electronics   | 2         | 1.89%   |
| Texas Instruments     | 1         | 0.94%   |
| Realtek Semiconductor | 1         | 0.94%   |
| Logitech              | 1         | 0.94%   |
| Ensoniq               | 1         | 0.94%   |
| Creative Labs         | 1         | 0.94%   |
| Blue Microphones      | 1         | 0.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 9.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 6.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 6.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 4.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 4.13%   |
| AMD FCH Azalia Controller                                                                         | 5         | 4.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 3.31%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 2.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.48%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 2.48%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.48%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 2.48%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.65%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.65%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.65%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.83%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1         | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.83%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.83%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.83%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Logitech Wireless Headset                                                                         | 1         | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.83%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.83%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.83%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.83%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 0.83%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 1         | 0.83%   |
| Ensoniq 5880B / Creative Labs CT5880                                                              | 1         | 0.83%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1         | 0.83%   |
| C-Media Electronics Multimedia Headset [Gigaware by Ignition L.P.]                                | 1         | 0.83%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.83%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 0.83%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.83%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.83%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 0.83%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.83%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.83%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 16        | 19.28%  |
| Samsung Electronics | 15        | 18.07%  |
| Kingston            | 11        | 13.25%  |
| SK hynix            | 10        | 12.05%  |
| Micron Technology   | 10        | 12.05%  |
| Unknown             | 3         | 3.61%   |
| Unknown (ABCD)      | 2         | 2.41%   |
| Nanya Technology    | 2         | 2.41%   |
| Elpida              | 2         | 2.41%   |
| A-DATA Technology   | 2         | 2.41%   |
| Transcend           | 1         | 1.2%    |
| Qumo                | 1         | 1.2%    |
| Qimonda             | 1         | 1.2%    |
| GeIL                | 1         | 1.2%    |
| Corsair             | 1         | 1.2%    |
| Avant               | 1         | 1.2%    |
| 2C0C1121390963FE    | 1         | 1.2%    |
| 2C0C1121390963FD    | 1         | 1.2%    |
| 2C0C1121390963F9    | 1         | 1.2%    |
| 2C0C1121390963F8    | 1         | 1.2%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 3         | 3.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 2.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 1         | 1.18%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                             | 1         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 1.18%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 1         | 1.18%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 1.18%   |
| Unknown RAM Module 2048MB DIMM DDR2                                 | 1         | 1.18%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                          | 1         | 1.18%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                          | 1         | 1.18%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                              | 1         | 1.18%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                      | 1         | 1.18%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 1.18%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                       | 1         | 1.18%   |
| Unknown RAM Module 1024MB DIMM DDR2                                 | 1         | 1.18%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                          | 1         | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 1         | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.18%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.18%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                       | 1         | 1.18%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s               | 1         | 1.18%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s            | 1         | 1.18%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.18%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.18%   |
| SK hynix RAM HMT112U6TFR8C-H9 1024MB DIMM DDR3 1333MT/s             | 1         | 1.18%   |
| SK hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s                | 1         | 1.18%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 1.18%   |
| SK hynix RAM H5TC4G63CFR-PBA 2048MB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 1.18%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.18%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 1.18%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 1.18%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.18%   |
| Samsung RAM M4 70T5669AZ0-CE6 2GB SODIMM DDR2 667MT/s               | 1         | 1.18%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s              | 1         | 1.18%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR2 2048MT/s              | 1         | 1.18%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s                 | 1         | 1.18%   |
| Samsung RAM M378B2873FH0-CH9 1024MB DIMM DDR3 1333MT/s              | 1         | 1.18%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s                 | 1         | 1.18%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 1639MT/s                | 1         | 1.18%   |
| Qumo RAM Module 4096MB DIMM DDR3 1333MT/s                           | 1         | 1.18%   |
| Qimonda RAM 64T128021EDL2.5B2 1024MB SODIMM DDR2 800MT/s            | 1         | 1.18%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                | 1         | 1.18%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2048MB SODIMM DDR2 2048MT/s             | 1         | 1.18%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                            | 1         | 1.18%   |
| Micron RAM 8HTF12864AY-800G1 1024MB DIMM DDR2 800MT/s               | 1         | 1.18%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 1         | 1.18%   |
| Micron RAM 4KTF25664HZ-1G6P1 2GB SODIMM DDR3 1600MT/s               | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 1         | 1.18%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 1         | 1.18%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.18%   |
| Micron RAM 16KTF51264AZ-1G6M1 4096MB DIMM DDR3 1600MT/s             | 1         | 1.18%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB DIMM DDR3 1066MT/s              | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 23        | 33.33%  |
| DDR2    | 15        | 21.74%  |
| DDR4    | 13        | 18.84%  |
| SDRAM   | 8         | 11.59%  |
| Unknown | 4         | 5.8%    |
| LPDDR4  | 3         | 4.35%   |
| DDR     | 3         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 38        | 56.72%  |
| DIMM    | 28        | 41.79%  |
| FB-DIMM | 1         | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 28        | 37.84%  |
| 4096  | 18        | 24.32%  |
| 8192  | 13        | 17.57%  |
| 1024  | 12        | 16.22%  |
| 16384 | 3         | 4.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 14        | 19.44%  |
| 1333    | 7         | 9.72%   |
| 3200    | 6         | 8.33%   |
| 667     | 6         | 8.33%   |
| Unknown | 6         | 8.33%   |
| 2667    | 5         | 6.94%   |
| 2400    | 3         | 4.17%   |
| 975     | 3         | 4.17%   |
| 800     | 3         | 4.17%   |
| 4199    | 2         | 2.78%   |
| 2133    | 2         | 2.78%   |
| 2048    | 2         | 2.78%   |
| 1066    | 2         | 2.78%   |
| 400     | 2         | 2.78%   |
| 49926   | 1         | 1.39%   |
| 19791   | 1         | 1.39%   |
| 3500    | 1         | 1.39%   |
| 3266    | 1         | 1.39%   |
| 1866    | 1         | 1.39%   |
| 1639    | 1         | 1.39%   |
| 1334    | 1         | 1.39%   |
| 1033    | 1         | 1.39%   |
| 133     | 1         | 1.39%   |

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
| Chicony Electronics                    | 13        | 26.53%  |
| Quanta                                 | 5         | 10.2%   |
| Suyin                                  | 4         | 8.16%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 8.16%   |
| Silicon Motion                         | 3         | 6.12%   |
| IMC Networks                           | 3         | 6.12%   |
| Sunplus Innovation Technology          | 2         | 4.08%   |
| Apple                                  | 2         | 4.08%   |
| Alcor Micro                            | 2         | 4.08%   |
| Z-Star Microelectronics                | 1         | 2.04%   |
| Unknown                                | 1         | 2.04%   |
| Realtek Semiconductor                  | 1         | 2.04%   |
| OmniVision Technologies                | 1         | 2.04%   |
| Microsoft                              | 1         | 2.04%   |
| Microdia                               | 1         | 2.04%   |
| Logitech                               | 1         | 2.04%   |
| Jieli Technology                       | 1         | 2.04%   |
| Hewlett-Packard                        | 1         | 2.04%   |
| Generalplus Technology                 | 1         | 2.04%   |
| Aveo Technology                        | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                               | 3         | 6.12%   |
| Quanta HP TrueVision HD Camera                              | 2         | 4.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 4.08%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 2.04%   |
| Unknown Integrated RGB Camera                               | 1         | 2.04%   |
| Suyin USB 2.0 Camera                                        | 1         | 2.04%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 2.04%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 1         | 2.04%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 2.04%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 2.04%   |
| Sunplus HD WebCam                                           | 1         | 2.04%   |
| Silicon Motion WebCam SC-10HDD13335N                        | 1         | 2.04%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 2.04%   |
| Silicon Motion Web Camera                                   | 1         | 2.04%   |
| Realtek USB Camera                                          | 1         | 2.04%   |
| Quanta VGA WebCam                                           | 1         | 2.04%   |
| Quanta HP Truevision HD                                     | 1         | 2.04%   |
| Quanta HD Webcam                                            | 1         | 2.04%   |
| OmniVision OV2640 Webcam                                    | 1         | 2.04%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks         | 1         | 2.04%   |
| Microdia Integrated_Webcam_FHD                              | 1         | 2.04%   |
| Logitech HD Webcam C615                                     | 1         | 2.04%   |
| Jieli USB PHY 2.0                                           | 1         | 2.04%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 2.04%   |
| IMC Networks EasyCamera                                     | 1         | 2.04%   |
| IMC Networks 2M Integrated Webcam                           | 1         | 2.04%   |
| HP Webcam HD 2300                                           | 1         | 2.04%   |
| Generalplus GENERAL WEBCAM                                  | 1         | 2.04%   |
| Chicony VGA Webcam                                          | 1         | 2.04%   |
| Chicony USB 2.0 Camera                                      | 1         | 2.04%   |
| Chicony Integrated Camera                                   | 1         | 2.04%   |
| Chicony HP Webcam                                           | 1         | 2.04%   |
| Chicony HP TrueVision HD                                    | 1         | 2.04%   |
| Chicony HP High Definition 1MP Webcam                       | 1         | 2.04%   |
| Chicony HD WebCam (Asus N-series)                           | 1         | 2.04%   |
| Chicony HD WebCam                                           | 1         | 2.04%   |
| Chicony FJ Camera                                           | 1         | 2.04%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 2.04%   |
| Aveo USB2.0 Camera                                          | 1         | 2.04%   |
| Apple iPhone 5/5C/5S/6/SE                                   | 1         | 2.04%   |
| Apple Built-in iSight                                       | 1         | 2.04%   |
| Alcor Micro Asus Integrated Webcam                          | 1         | 2.04%   |
| Alcor Micro Acer Integrated Webcam                          | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 3         | 50%     |
| Validity Sensors      | 1         | 16.67%  |
| Samsung Electronics   | 1         | 16.67%  |
| LighTuning Technology | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor        | 2         | 33.33%  |
| Validity Sensors VFS451 Fingerprint Reader  | 1         | 16.67%  |
| Samsung Fingerprint Device                  | 1         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 16.67%  |
| AuthenTec AES1600                           | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| O2 Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| O2 Micro Oz776 SmartCard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 73        | 81.11%  |
| 1     | 15        | 16.67%  |
| 2     | 2         | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 31.58%  |
| Net/wireless             | 4         | 21.05%  |
| Graphics card            | 2         | 10.53%  |
| Unassigned class         | 1         | 5.26%   |
| Storage                  | 1         | 5.26%   |
| Sound                    | 1         | 5.26%   |
| Net/ethernet             | 1         | 5.26%   |
| Dvb card                 | 1         | 5.26%   |
| Communication controller | 1         | 5.26%   |
| Chipcard                 | 1         | 5.26%   |

