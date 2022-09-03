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

Total: 139

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Linux Lite 5.8 | 20        | 20.2%   |
| Linux Lite 5.0 | 17        | 17.17%  |
| Linux Lite 5.2 | 16        | 16.16%  |
| Linux Lite 5.4 | 15        | 15.15%  |
| Linux Lite 5.6 | 13        | 13.13%  |
| Linux Lite 6.0 | 9         | 9.09%   |
| Linux Lite 3.8 | 5         | 5.05%   |
| Linux Lite 4.8 | 2         | 2.02%   |
| Linux Lite 4.6 | 1         | 1.01%   |
| Linux Lite 4.4 | 1         | 1.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Lite | 98        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 6         | 5.77%   |
| 5.4.0-70-generic                   | 5         | 4.81%   |
| 5.4.0-91-generic                   | 4         | 3.85%   |
| 5.4.0-52-generic                   | 4         | 3.85%   |
| 5.4.0-40-generic                   | 4         | 3.85%   |
| 5.4.0-109-generic                  | 4         | 3.85%   |
| 5.4.0-104-generic                  | 4         | 3.85%   |
| 5.4.0-96-generic                   | 3         | 2.88%   |
| 5.4.0-58-generic                   | 3         | 2.88%   |
| 5.4.0-48-generic                   | 3         | 2.88%   |
| 5.4.0-113-generic                  | 3         | 2.88%   |
| 5.4.0-107-generic                  | 3         | 2.88%   |
| 5.15.0-33-generic                  | 3         | 2.88%   |
| 5.4.0-90-generic                   | 2         | 1.92%   |
| 5.4.0-88-generic                   | 2         | 1.92%   |
| 5.4.0-81-generic                   | 2         | 1.92%   |
| 5.4.0-80-generic                   | 2         | 1.92%   |
| 5.4.0-74-generic                   | 2         | 1.92%   |
| 5.4.0-54-generic                   | 2         | 1.92%   |
| 5.4.0-33-generic                   | 2         | 1.92%   |
| 5.4.0-110-generic                  | 2         | 1.92%   |
| 5.4.0-105-generic                  | 2         | 1.92%   |
| 4.4.0-112-generic                  | 2         | 1.92%   |
| 5.9.0                              | 1         | 0.96%   |
| 5.4.0-99-generic                   | 1         | 0.96%   |
| 5.4.0-94-generic                   | 1         | 0.96%   |
| 5.4.0-77-generic                   | 1         | 0.96%   |
| 5.4.0-72-generic                   | 1         | 0.96%   |
| 5.4.0-71-generic                   | 1         | 0.96%   |
| 5.4.0-66-generic                   | 1         | 0.96%   |
| 5.4.0-65-generic                   | 1         | 0.96%   |
| 5.4.0-56-generic                   | 1         | 0.96%   |
| 5.4.0-45-generic                   | 1         | 0.96%   |
| 5.4.0-37-generic                   | 1         | 0.96%   |
| 5.4.0-124-generic                  | 1         | 0.96%   |
| 5.4.0-122-generic                  | 1         | 0.96%   |
| 5.4.0-100-generic                  | 1         | 0.96%   |
| 5.16.9                             | 1         | 0.96%   |
| 5.16.0                             | 1         | 0.96%   |
| 5.15.0-47-generic                  | 1         | 0.96%   |
| 5.15.0-46-generic                  | 1         | 0.96%   |
| 5.15.0-40-generic                  | 1         | 0.96%   |
| 5.15.0-30-generic                  | 1         | 0.96%   |
| 5.15.0-27-generic                  | 1         | 0.96%   |
| 5.15.0                             | 1         | 0.96%   |
| 5.13.0-linuxlite                   | 1         | 0.96%   |
| 5.13.0-44-lowlatency               | 1         | 0.96%   |
| 5.13.0-30-lowlatency               | 1         | 0.96%   |
| 5.10.0-051000daily20201222-generic | 1         | 0.96%   |
| 4.4.0-217-generic                  | 1         | 0.96%   |
| 4.4.0-210-generic                  | 1         | 0.96%   |
| 4.15.0-99-generic                  | 1         | 0.96%   |
| 4.15.0-91-generic                  | 1         | 0.96%   |
| 4.15.0-169-generic                 | 1         | 0.96%   |
| 4.15.0-166-generic                 | 1         | 0.96%   |
| 4.15.0-163-generic                 | 1         | 0.96%   |
| 4.15.0-162-generic                 | 1         | 0.96%   |
| 4.15.0-147-generic                 | 1         | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 76        | 75.25%  |
| 5.15.0  | 9         | 8.91%   |
| 4.15.0  | 5         | 4.95%   |
| 4.4.0   | 4         | 3.96%   |
| 5.13.0  | 3         | 2.97%   |
| 5.9.0   | 1         | 0.99%   |
| 5.16.9  | 1         | 0.99%   |
| 5.16.0  | 1         | 0.99%   |
| 5.10.0  | 1         | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 76        | 75.25%  |
| 5.15    | 9         | 8.91%   |
| 4.15    | 5         | 4.95%   |
| 4.4     | 4         | 3.96%   |
| 5.13    | 3         | 2.97%   |
| 5.16    | 2         | 1.98%   |
| 5.9     | 1         | 0.99%   |
| 5.10    | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 94        | 95.92%  |
| i686   | 4         | 4.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 72        | 73.47%  |
| GNOME   | 24        | 24.49%  |
| Deepin  | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 97        | 98.98%  |
| Unknown | 1         | 1.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 53        | 53%     |
| TDM     | 28        | 28%     |
| Unknown | 18        | 18%     |
| GDM     | 1         | 1%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 45        | 45.92%  |
| pt_BR | 6         | 6.12%   |
| pl_PL | 6         | 6.12%   |
| fr_FR | 6         | 6.12%   |
| de_DE | 6         | 6.12%   |
| en_GB | 5         | 5.1%    |
| ru_UA | 3         | 3.06%   |
| es_MX | 3         | 3.06%   |
| es_ES | 3         | 3.06%   |
| ru_RU | 2         | 2.04%   |
| it_IT | 2         | 2.04%   |
| zh_CN | 1         | 1.02%   |
| tr_TR | 1         | 1.02%   |
| nl_NL | 1         | 1.02%   |
| fr_CA | 1         | 1.02%   |
| es_CO | 1         | 1.02%   |
| es_CL | 1         | 1.02%   |
| en_NZ | 1         | 1.02%   |
| en_IE | 1         | 1.02%   |
| en_CA | 1         | 1.02%   |
| en_AU | 1         | 1.02%   |
| da_DK | 1         | 1.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 54        | 55.1%   |
| EFI  | 44        | 44.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 85        | 86.73%  |
| Overlay | 9         | 9.18%   |
| Btrfs   | 2         | 2.04%   |
| Zfs     | 1         | 1.02%   |
| Ext3    | 1         | 1.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 36        | 36.73%  |
| Unknown | 33        | 33.67%  |
| MBR     | 29        | 29.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 82.65%  |
| Yes       | 17        | 17.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 68.69%  |
| Yes       | 31        | 31.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 19        | 19.39%  |
| ASUSTek Computer    | 15        | 15.31%  |
| Lenovo              | 11        | 11.22%  |
| Acer                | 11        | 11.22%  |
| Dell                | 9         | 9.18%   |
| Samsung Electronics | 3         | 3.06%   |
| MSI                 | 3         | 3.06%   |
| Gigabyte Technology | 3         | 3.06%   |
| Minix               | 2         | 2.04%   |
| Intel               | 2         | 2.04%   |
| Fujitsu             | 2         | 2.04%   |
| Foxconn             | 2         | 2.04%   |
| ASRock              | 2         | 2.04%   |
| Apple               | 2         | 2.04%   |
| TR                  | 1         | 1.02%   |
| Toshiba             | 1         | 1.02%   |
| Sony                | 1         | 1.02%   |
| Pegatron            | 1         | 1.02%   |
| Jetway              | 1         | 1.02%   |
| Inventec            | 1         | 1.02%   |
| Insignia            | 1         | 1.02%   |
| Google              | 1         | 1.02%   |
| EVGA                | 1         | 1.02%   |
| Biostar             | 1         | 1.02%   |
| AWOW                | 1         | 1.02%   |
| ABIT                | 1         | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| MSI MS-7758                            | 2         | 2.04%   |
| TR ST Pro-KN                           | 1         | 1.02%   |
| Toshiba Satellite T215D                | 1         | 1.02%   |
| Sony VGC-JS54FB_W                      | 1         | 1.02%   |
| Samsung NC110P/NC108P/NC111P           | 1         | 1.02%   |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 1.02%   |
| Samsung 530XBB                         | 1         | 1.02%   |
| Pegatron 520-1135la                    | 1         | 1.02%   |
| MSI FZ079AA-ABF a6625fr                | 1         | 1.02%   |
| Minix Z83-4                            | 1         | 1.02%   |
| Minix Z64                              | 1         | 1.02%   |
| Lenovo ThinkStation P320 30BH000BFR    | 1         | 1.02%   |
| Lenovo ThinkPad T400 6475E13           | 1         | 1.02%   |
| Lenovo ThinkPad L480 20LS001AMC        | 1         | 1.02%   |
| Lenovo ThinkCentre M91p 4524RS6        | 1         | 1.02%   |
| Lenovo ThinkCentre M91p 4518E2M        | 1         | 1.02%   |
| Lenovo ThinkCentre A55 9265BL7         | 1         | 1.02%   |
| Lenovo MIIX 300-10IBY 80NR             | 1         | 1.02%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1    | 1         | 1.02%   |
| Lenovo IdeaPad 320-15ABR 80XS          | 1         | 1.02%   |
| Lenovo H505S 10107                     | 1         | 1.02%   |
| Lenovo 3000 V200 0764A11               | 1         | 1.02%   |
| Jetway I61MG4                          | 1         | 1.02%   |
| Inventec Dell Thin Client Desktop 3290 | 1         | 1.02%   |
| Intel H61M-S1                          | 1         | 1.02%   |
| Intel DG31PR AAD97573-300              | 1         | 1.02%   |
| Insignia NS-P11W7100                   | 1         | 1.02%   |
| HP xw8600 Workstation                  | 1         | 1.02%   |
| HP x2 Detachable 10-p0XX               | 1         | 1.02%   |
| HP t5000 series                        | 1         | 1.02%   |
| HP Pavilion g4                         | 1         | 1.02%   |
| HP Pavilion dv6500                     | 1         | 1.02%   |
| HP Laptop 17-by2xxx                    | 1         | 1.02%   |
| HP Laptop 15-dw3xxx                    | 1         | 1.02%   |
| HP Laptop 14-cm0xxx                    | 1         | 1.02%   |
| HP EliteBook Folio 9470m               | 1         | 1.02%   |
| HP EliteBook 8440p                     | 1         | 1.02%   |
| HP Compaq nw9440 (EY615ET#ABU)         | 1         | 1.02%   |
| HP Compaq dc7900 Convertible Minitower | 1         | 1.02%   |
| HP Compaq dc5800 Small Form Factor     | 1         | 1.02%   |
| HP Compaq CQ45                         | 1         | 1.02%   |
| HP Compaq 6005 Pro SFF PC              | 1         | 1.02%   |
| HP Compaq 2510p                        | 1         | 1.02%   |
| HP 655                                 | 1         | 1.02%   |
| HP 200-5320br                          | 1         | 1.02%   |
| HP 15 Notebook PC                      | 1         | 1.02%   |
| Google Chell                           | 1         | 1.02%   |
| Gigabyte X570 AORUS MASTER             | 1         | 1.02%   |
| Gigabyte GA-E350N                      | 1         | 1.02%   |
| Gigabyte B450M DS3H                    | 1         | 1.02%   |
| Fujitsu LIFEBOOK U747                  | 1         | 1.02%   |
| Fujitsu FMVNQ8P6                       | 1         | 1.02%   |
| Foxconn 500B Microtower                | 1         | 1.02%   |
| Foxconn 45CMX/45GMX/45CMX-K            | 1         | 1.02%   |
| EVGA X58 SLI FTW3 Tylersburg           | 1         | 1.02%   |
| Dell Vostro1710                        | 1         | 1.02%   |
| Dell OptiPlex 790                      | 1         | 1.02%   |
| Dell MXG071                            | 1         | 1.02%   |
| Dell MXG061                            | 1         | 1.02%   |
| Dell Latitude D530                     | 1         | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 7         | 7.14%   |
| HP Compaq            | 6         | 6.12%   |
| Dell Inspiron        | 4         | 4.08%   |
| Lenovo ThinkCentre   | 3         | 3.06%   |
| HP Laptop            | 3         | 3.06%   |
| MSI MS-7758          | 2         | 2.04%   |
| Lenovo ThinkPad      | 2         | 2.04%   |
| Lenovo IdeaPad       | 2         | 2.04%   |
| HP Pavilion          | 2         | 2.04%   |
| HP EliteBook         | 2         | 2.04%   |
| ASUS VivoBook        | 2         | 2.04%   |
| TR ST                | 1         | 1.02%   |
| Toshiba Satellite    | 1         | 1.02%   |
| Sony VGC-JS54FB      | 1         | 1.02%   |
| Samsung NC110P       | 1         | 1.02%   |
| Samsung 905S3G       | 1         | 1.02%   |
| Samsung 530XBB       | 1         | 1.02%   |
| Pegatron 520-1135la  | 1         | 1.02%   |
| MSI FZ079AA-ABF      | 1         | 1.02%   |
| Minix Z83-4          | 1         | 1.02%   |
| Minix Z64            | 1         | 1.02%   |
| Lenovo ThinkStation  | 1         | 1.02%   |
| Lenovo MIIX          | 1         | 1.02%   |
| Lenovo H505S         | 1         | 1.02%   |
| Lenovo 3000          | 1         | 1.02%   |
| Jetway I61MG4        | 1         | 1.02%   |
| Inventec Dell        | 1         | 1.02%   |
| Intel H61M-S1        | 1         | 1.02%   |
| Intel DG31PR         | 1         | 1.02%   |
| Insignia NS-P11W7100 | 1         | 1.02%   |
| HP xw8600            | 1         | 1.02%   |
| HP x2                | 1         | 1.02%   |
| HP t5000             | 1         | 1.02%   |
| HP 655               | 1         | 1.02%   |
| HP 200-5320br        | 1         | 1.02%   |
| HP 15                | 1         | 1.02%   |
| Google Chell         | 1         | 1.02%   |
| Gigabyte X570        | 1         | 1.02%   |
| Gigabyte GA-E350N    | 1         | 1.02%   |
| Gigabyte B450M       | 1         | 1.02%   |
| Fujitsu LIFEBOOK     | 1         | 1.02%   |
| Fujitsu FMVNQ8P6     | 1         | 1.02%   |
| Foxconn 500B         | 1         | 1.02%   |
| Foxconn 45CMX        | 1         | 1.02%   |
| EVGA X58             | 1         | 1.02%   |
| Dell Vostro1710      | 1         | 1.02%   |
| Dell OptiPlex        | 1         | 1.02%   |
| Dell MXG071          | 1         | 1.02%   |
| Dell MXG061          | 1         | 1.02%   |
| Dell Latitude        | 1         | 1.02%   |
| Biostar G41D3C       | 1         | 1.02%   |
| AWOW PC              | 1         | 1.02%   |
| ASUS X751LD          | 1         | 1.02%   |
| ASUS X555YI          | 1         | 1.02%   |
| ASUS X541SA          | 1         | 1.02%   |
| ASUS X540YA          | 1         | 1.02%   |
| ASUS UX303LN         | 1         | 1.02%   |
| ASUS TUF             | 1         | 1.02%   |
| ASUS N750JK          | 1         | 1.02%   |
| ASUS N53Jf           | 1         | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2008 | 13        | 13.27%  |
| 2011 | 11        | 11.22%  |
| 2012 | 10        | 10.2%   |
| 2010 | 9         | 9.18%   |
| 2018 | 8         | 8.16%   |
| 2014 | 8         | 8.16%   |
| 2007 | 7         | 7.14%   |
| 2016 | 6         | 6.12%   |
| 2020 | 5         | 5.1%    |
| 2015 | 5         | 5.1%    |
| 2019 | 3         | 3.06%   |
| 2017 | 3         | 3.06%   |
| 2009 | 3         | 3.06%   |
| 2021 | 2         | 2.04%   |
| 2006 | 2         | 2.04%   |
| 2022 | 1         | 1.02%   |
| 2013 | 1         | 1.02%   |
| 2004 | 1         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 57        | 58.16%  |
| Desktop    | 35        | 35.71%  |
| Tablet     | 2         | 2.04%   |
| Mini pc    | 2         | 2.04%   |
| All in one | 2         | 2.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 95        | 96.94%  |
| Enabled  | 3         | 3.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 97        | 98.98%  |
| Yes  | 1         | 1.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 34        | 34.69%  |
| 1.01-2.0   | 20        | 20.41%  |
| 4.01-8.0   | 17        | 17.35%  |
| 16.01-24.0 | 11        | 11.22%  |
| 8.01-16.0  | 7         | 7.14%   |
| 32.01-64.0 | 4         | 4.08%   |
| 0.51-1.0   | 3         | 3.06%   |
| 2.01-3.0   | 2         | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 48        | 48%     |
| 2.01-3.0  | 20        | 20%     |
| 0.51-1.0  | 15        | 15%     |
| 3.01-4.0  | 8         | 8%      |
| 4.01-8.0  | 5         | 5%      |
| 0.01-0.5  | 3         | 3%      |
| 8.01-16.0 | 1         | 1%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 70        | 71.43%  |
| 2      | 19        | 19.39%  |
| 3      | 5         | 5.1%    |
| 0      | 2         | 2.04%   |
| 5      | 1         | 1.02%   |
| 4      | 1         | 1.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 56.12%  |
| Yes       | 43        | 43.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 86.73%  |
| No        | 13        | 13.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 78.57%  |
| No        | 21        | 21.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 53.06%  |
| No        | 46        | 46.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 12        | 12.24%  |
| Brazil      | 11        | 11.22%  |
| Germany     | 7         | 7.14%   |
| France      | 7         | 7.14%   |
| Poland      | 6         | 6.12%   |
| Ukraine     | 5         | 5.1%    |
| UK          | 5         | 5.1%    |
| Romania     | 4         | 4.08%   |
| Mexico      | 4         | 4.08%   |
| Canada      | 4         | 4.08%   |
| Spain       | 3         | 3.06%   |
| Russia      | 3         | 3.06%   |
| Peru        | 3         | 3.06%   |
| Turkey      | 2         | 2.04%   |
| Netherlands | 2         | 2.04%   |
| Italy       | 2         | 2.04%   |
| Chile       | 2         | 2.04%   |
| Australia   | 2         | 2.04%   |
| Venezuela   | 1         | 1.02%   |
| Slovakia    | 1         | 1.02%   |
| Qatar       | 1         | 1.02%   |
| Philippines | 1         | 1.02%   |
| New Zealand | 1         | 1.02%   |
| Myanmar     | 1         | 1.02%   |
| Malaysia    | 1         | 1.02%   |
| Japan       | 1         | 1.02%   |
| Ireland     | 1         | 1.02%   |
| Iran        | 1         | 1.02%   |
| Guadeloupe  | 1         | 1.02%   |
| Greenland   | 1         | 1.02%   |
| El Salvador | 1         | 1.02%   |
| Colombia    | 1         | 1.02%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Pabianice            | 3         | 3.03%   |
| Würzburg            | 2         | 2.02%   |
| Warsaw               | 2         | 2.02%   |
| Sydney               | 2         | 2.02%   |
| Sao Paulo            | 2         | 2.02%   |
| Odessa               | 2         | 2.02%   |
| Lima                 | 2         | 2.02%   |
| Kyiv                 | 2         | 2.02%   |
| Żywiec              | 1         | 1.01%   |
| Yangon               | 1         | 1.01%   |
| Wiesbaden            | 1         | 1.01%   |
| Wellington           | 1         | 1.01%   |
| Waterbury            | 1         | 1.01%   |
| Wahroonga            | 1         | 1.01%   |
| Voluntari            | 1         | 1.01%   |
| Vinnytsia            | 1         | 1.01%   |
| Varennes-les-Narcy   | 1         | 1.01%   |
| Vancouver            | 1         | 1.01%   |
| Valencia             | 1         | 1.01%   |
| Tucape               | 1         | 1.01%   |
| Trujillo             | 1         | 1.01%   |
| Thetford-Mines       | 1         | 1.01%   |
| Teresina             | 1         | 1.01%   |
| Tarragona            | 1         | 1.01%   |
| Svidník             | 1         | 1.01%   |
| St. Petersburg       | 1         | 1.01%   |
| Shadrinsk            | 1         | 1.01%   |
| Sabadell             | 1         | 1.01%   |
| Rio de Janeiro       | 1         | 1.01%   |
| Queretaro            | 1         | 1.01%   |
| Purmerend            | 1         | 1.01%   |
| Porto Velho          | 1         | 1.01%   |
| Porto Alegre         | 1         | 1.01%   |
| Paris                | 1         | 1.01%   |
| Paranaque City       | 1         | 1.01%   |
| Ottawa               | 1         | 1.01%   |
| Ossining             | 1         | 1.01%   |
| Osasco               | 1         | 1.01%   |
| Oldenburg            | 1         | 1.01%   |
| Nudlingen            | 1         | 1.01%   |
| Novaci               | 1         | 1.01%   |
| Nashville            | 1         | 1.01%   |
| Narbonne             | 1         | 1.01%   |
| Nagano               | 1         | 1.01%   |
| Moscow               | 1         | 1.01%   |
| Milan                | 1         | 1.01%   |
| Mexico City          | 1         | 1.01%   |
| Marseille            | 1         | 1.01%   |
| Madrid               | 1         | 1.01%   |
| Long Seridan         | 1         | 1.01%   |
| London               | 1         | 1.01%   |
| Les Abymes           | 1         | 1.01%   |
| La Libertad          | 1         | 1.01%   |
| La Glacerie          | 1         | 1.01%   |
| Kingston upon Thames | 1         | 1.01%   |
| Jaraguá do Sul      | 1         | 1.01%   |
| Izmir                | 1         | 1.01%   |
| Istanbul             | 1         | 1.01%   |
| Ilulissat            | 1         | 1.01%   |
| Iasi                 | 1         | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 28     | 21.31%  |
| WDC                 | 22        | 29     | 18.03%  |
| Samsung Electronics | 13        | 14     | 10.66%  |
| Toshiba             | 11        | 12     | 9.02%   |
| Kingston            | 8         | 10     | 6.56%   |
| Unknown             | 7         | 9      | 5.74%   |
| SanDisk             | 4         | 4      | 3.28%   |
| Hitachi             | 4         | 4      | 3.28%   |
| Crucial             | 4         | 4      | 3.28%   |
| HGST                | 3         | 3      | 2.46%   |
| GOODRAM             | 3         | 3      | 2.46%   |
| Micron Technology   | 2         | 3      | 1.64%   |
| SK hynix            | 1         | 1      | 0.82%   |
| PNY                 | 1         | 1      | 0.82%   |
| Phison              | 1         | 1      | 0.82%   |
| OCZ                 | 1         | 1      | 0.82%   |
| Maxtor              | 1         | 1      | 0.82%   |
| Mass                | 1         | 1      | 0.82%   |
| LITEON              | 1         | 1      | 0.82%   |
| Intel               | 1         | 1      | 0.82%   |
| HPE                 | 1         | 1      | 0.82%   |
| Hewlett-Packard     | 1         | 1      | 0.82%   |
| Gigabyte Technology | 1         | 1      | 0.82%   |
| ASUS-PHISON         | 1         | 2      | 0.82%   |
| ASMT                | 1         | 1      | 0.82%   |
| Apple               | 1         | 1      | 0.82%   |
| Apacer              | 1         | 1      | 0.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                | 3         | 2.31%   |
| Toshiba MQ01ABF050 500GB              | 3         | 2.31%   |
| Seagate ST500DM002-1BD142 500GB       | 3         | 2.31%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 2.31%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 2         | 1.54%   |
| WDC WD5000AAKX-001CA0 500GB           | 2         | 1.54%   |
| WDC WD10JPVX-75JC3T0 1TB              | 2         | 1.54%   |
| Seagate ST9320325AS 320GB             | 2         | 1.54%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 0.77%   |
| WDC WDS250G2B0A 250GB SSD             | 1         | 0.77%   |
| WDC WD800JD-60LSA0 80GB               | 1         | 0.77%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 0.77%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 0.77%   |
| WDC WD5000AAKS-60WWPA0 500GB          | 1         | 0.77%   |
| WDC WD5000AACS-00G8B1 500GB           | 1         | 0.77%   |
| WDC WD2500BEVE-00A0HT0 250GB          | 1         | 0.77%   |
| WDC WD20PURX-64PFUY0 2TB              | 1         | 0.77%   |
| WDC WD2005FBYZ-01YCBB2 2TB            | 1         | 0.77%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.77%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 0.77%   |
| WDC WD10EZEX-07WN4A0 1TB              | 1         | 0.77%   |
| WDC WD10EADS-00L5B1 1TB               | 1         | 0.77%   |
| WDC WD1003FBYX-01Y7B1 1TB             | 1         | 0.77%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB    | 1         | 0.77%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 0.77%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB  | 1         | 0.77%   |
| Unknown SD64G  64GB                   | 1         | 0.77%   |
| Unknown SC64G  64GB                   | 1         | 0.77%   |
| Unknown NCard  32GB                   | 1         | 0.77%   |
| Unknown HBG4a2  32GB                  | 1         | 0.77%   |
| Unknown DA4064  64GB                  | 1         | 0.77%   |
| Unknown BGND3R  32GB                  | 1         | 0.77%   |
| Toshiba MQ04ABF100 1TB                | 1         | 0.77%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.77%   |
| Toshiba MQ01ABD050 500GB              | 1         | 0.77%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 0.77%   |
| Toshiba MK1059GSM 1TB                 | 1         | 0.77%   |
| Toshiba MK1011GAH 100GB               | 1         | 0.77%   |
| Toshiba HDWD110 1TB                   | 1         | 0.77%   |
| Toshiba DT01ACA100 1TB                | 1         | 0.77%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 0.77%   |
| Seagate ST980811AS 80GB               | 1         | 0.77%   |
| Seagate ST9500423AS 500GB             | 1         | 0.77%   |
| Seagate ST9500325AS 500GB             | 1         | 0.77%   |
| Seagate ST9160823ASG 160GB            | 1         | 0.77%   |
| Seagate ST9160301AS 160GB             | 1         | 0.77%   |
| Seagate ST640LM0 00 HM641JI 640GB     | 1         | 0.77%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 0.77%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 0.77%   |
| Seagate ST500LM030-1RK17D 500GB       | 1         | 0.77%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 0.77%   |
| Seagate ST500DM002-1BC142 500GB       | 1         | 0.77%   |
| Seagate ST3750640NS 752GB             | 1         | 0.77%   |
| Seagate ST3500418AS 500GB             | 1         | 0.77%   |
| Seagate ST3320620A 320GB              | 1         | 0.77%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 0.77%   |
| Seagate ST320LM001 HN-M320MBB 320GB   | 1         | 0.77%   |
| Seagate ST320LM000 HM321HI 320GB      | 1         | 0.77%   |
| Seagate ST3120026A 120GB              | 1         | 0.77%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 0.77%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 28     | 40.63%  |
| WDC                 | 16        | 19     | 25%     |
| Toshiba             | 11        | 12     | 17.19%  |
| Hitachi             | 4         | 4      | 6.25%   |
| HGST                | 3         | 3      | 4.69%   |
| Samsung Electronics | 2         | 3      | 3.13%   |
| Maxtor              | 1         | 1      | 1.56%   |
| ASMT                | 1         | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 9      | 17.95%  |
| Samsung Electronics | 6         | 6      | 15.38%  |
| WDC                 | 4         | 5      | 10.26%  |
| Crucial             | 4         | 4      | 10.26%  |
| SanDisk             | 3         | 3      | 7.69%   |
| Goodram             | 3         | 3      | 7.69%   |
| Micron Technology   | 2         | 3      | 5.13%   |
| SK hynix            | 1         | 1      | 2.56%   |
| PNY                 | 1         | 1      | 2.56%   |
| OCZ                 | 1         | 1      | 2.56%   |
| LITEON              | 1         | 1      | 2.56%   |
| Intel               | 1         | 1      | 2.56%   |
| Hewlett-Packard     | 1         | 1      | 2.56%   |
| Gigabyte Technology | 1         | 1      | 2.56%   |
| ASUS-PHISON         | 1         | 2      | 2.56%   |
| Apple               | 1         | 1      | 2.56%   |
| Apacer              | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 58        | 71     | 50.88%  |
| SSD     | 37        | 44     | 32.46%  |
| NVMe    | 9         | 12     | 7.89%   |
| MMC     | 8         | 10     | 7.02%   |
| Unknown | 2         | 2      | 1.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 82        | 113    | 79.61%  |
| NVMe | 9         | 12     | 8.74%   |
| MMC  | 8         | 10     | 7.77%   |
| SAS  | 4         | 4      | 3.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 86     | 71.28%  |
| 0.51-1.0   | 22        | 23     | 23.4%   |
| 1.01-2.0   | 4         | 5      | 4.26%   |
| 4.01-10.0  | 1         | 1      | 1.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 29.29%  |
| 251-500        | 22        | 22.22%  |
| 51-100         | 15        | 15.15%  |
| 1-20           | 10        | 10.1%   |
| 21-50          | 8         | 8.08%   |
| 501-1000       | 8         | 8.08%   |
| More than 3000 | 4         | 4.04%   |
| 1001-2000      | 3         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 51        | 51%     |
| 21-50     | 22        | 22%     |
| 51-100    | 11        | 11%     |
| 101-250   | 8         | 8%      |
| 251-500   | 3         | 3%      |
| 2001-3000 | 2         | 2%      |
| 501-1000  | 2         | 2%      |
| 1001-2000 | 1         | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 1      | 5.56%   |
| WDC WD800JD-60LSA0 80GB          | 1         | 1      | 5.56%   |
| WDC WD5000AAKX-001CA0 500GB      | 1         | 1      | 5.56%   |
| WDC WD5000AAKS-60WWPA0 500GB     | 1         | 1      | 5.56%   |
| WDC WD10JPVX-22JC3T0 1TB         | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD050 500GB         | 1         | 1      | 5.56%   |
| Toshiba MK1059GSM 1TB            | 1         | 1      | 5.56%   |
| Seagate ST980811AS 80GB          | 1         | 1      | 5.56%   |
| Seagate ST9500423AS 500GB        | 1         | 1      | 5.56%   |
| Seagate ST9500325AS 500GB        | 1         | 1      | 5.56%   |
| Seagate ST9320325AS 320GB        | 1         | 1      | 5.56%   |
| Seagate ST9160823ASG 160GB       | 1         | 1      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB  | 1         | 1      | 5.56%   |
| Seagate ST3120026A 120GB         | 1         | 1      | 5.56%   |
| Hitachi HTS545016B9A300 160GB    | 1         | 1      | 5.56%   |
| Hitachi HDS722020ALA330 2TB      | 1         | 1      | 5.56%   |
| Hitachi HDS721616PLA380 160GB    | 1         | 1      | 5.56%   |
| Apacer 16GB SATA Flash Drive SSD | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 38.89%  |
| WDC     | 5         | 5      | 27.78%  |
| Hitachi | 3         | 3      | 16.67%  |
| Toshiba | 2         | 2      | 11.11%  |
| Apacer  | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 43.75%  |
| WDC     | 4         | 4      | 25%     |
| Hitachi | 3         | 3      | 18.75%  |
| Toshiba | 2         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 16     | 87.5%   |
| SSD  | 2         | 2      | 12.5%   |

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
| Works    | 45        | 59     | 44.55%  |
| Detected | 40        | 62     | 39.6%   |
| Malfunc  | 16        | 18     | 15.84%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 70        | 67.31%  |
| AMD                         | 17        | 16.35%  |
| Samsung Electronics         | 5         | 4.81%   |
| SanDisk                     | 3         | 2.88%   |
| Nvidia                      | 2         | 1.92%   |
| Marvell Technology Group    | 2         | 1.92%   |
| Phison Electronics          | 1         | 0.96%   |
| LSI Logic / Symbios Logic   | 1         | 0.96%   |
| Kingston Technology Company | 1         | 0.96%   |
| JMicron Technology          | 1         | 0.96%   |
| Broadcom / LSI              | 1         | 0.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11        | 8.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 5.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 4.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 4.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 3.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 2.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 2.21%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3         | 2.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.47%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.47%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.47%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 1.47%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 1.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.47%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.47%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 1.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.47%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.47%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.74%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.74%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.74%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.74%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.74%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.74%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 1         | 0.74%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1         | 0.74%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1         | 0.74%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1         | 0.74%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 0.74%   |
| JMicron JMB368 IDE controller                                                           | 1         | 0.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 0.74%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                             | 1         | 0.74%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.74%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1         | 0.74%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 0.74%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1         | 0.74%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 0.74%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 0.74%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 1         | 0.74%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                  | 1         | 0.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 66        | 57.89%  |
| IDE  | 34        | 29.82%  |
| NVMe | 9         | 7.89%   |
| RAID | 4         | 3.51%   |
| SCSI | 1         | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 80        | 81.63%  |
| AMD    | 18        | 18.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 2.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 2.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 2.04%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 2.04%   |
| Intel Core 2 CPU T7600 @ 2.33GHz            | 2         | 2.04%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 2.04%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 2.04%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 2.04%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 1.02%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1         | 1.02%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.02%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 1.02%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 1.02%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 1.02%   |
| Intel Pentium D CPU 3.40GHz                 | 1         | 1.02%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1.02%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.02%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.02%   |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1         | 1.02%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.02%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 1.02%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 1.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.02%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.02%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.02%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.02%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 1.02%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1         | 1.02%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 1.02%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.02%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1         | 1.02%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 1.02%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.02%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.02%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1         | 1.02%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1         | 1.02%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1         | 1.02%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.02%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.02%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.02%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.02%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1         | 1.02%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1         | 1.02%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.02%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 1.02%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1         | 1.02%   |
| Intel Core 2 Extreme CPU X7900 @ 2.80GHz    | 1         | 1.02%   |
| Intel Core 2 Duo CPU U7600 @ 1.20GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 1         | 1.02%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 15        | 15.31%  |
| Intel Core 2 Duo        | 12        | 12.24%  |
| Intel Core i3           | 9         | 9.18%   |
| Intel Core i7           | 7         | 7.14%   |
| Intel Celeron           | 7         | 7.14%   |
| Intel Atom              | 7         | 7.14%   |
| Intel Pentium Dual-Core | 5         | 5.1%    |
| Intel Pentium           | 5         | 5.1%    |
| Other                   | 3         | 3.06%   |
| Intel Xeon              | 2         | 2.04%   |
| Intel Core 2            | 2         | 2.04%   |
| AMD E2                  | 2         | 2.04%   |
| AMD E                   | 2         | 2.04%   |
| AMD A8                  | 2         | 2.04%   |
| Intel Pentium Dual      | 1         | 1.02%   |
| Intel Pentium D         | 1         | 1.02%   |
| Intel Genuine           | 1         | 1.02%   |
| Intel Core m7           | 1         | 1.02%   |
| Intel Core 2 Extreme    | 1         | 1.02%   |
| Intel Celeron M         | 1         | 1.02%   |
| AMD Turion 64 X2 Mobile | 1         | 1.02%   |
| AMD Ryzen 9             | 1         | 1.02%   |
| AMD Ryzen 5             | 1         | 1.02%   |
| AMD Ryzen 3             | 1         | 1.02%   |
| AMD Quad-Core           | 1         | 1.02%   |
| AMD Phenom II X2        | 1         | 1.02%   |
| AMD FX                  | 1         | 1.02%   |
| AMD Athlon II X2        | 1         | 1.02%   |
| AMD Athlon II Neo       | 1         | 1.02%   |
| AMD A6                  | 1         | 1.02%   |
| AMD A12                 | 1         | 1.02%   |
| AMD A10                 | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 58        | 59.18%  |
| 4      | 28        | 28.57%  |
| 1      | 5         | 5.1%    |
| 6      | 4         | 4.08%   |
| 12     | 1         | 1.02%   |
| 10     | 1         | 1.02%   |
| 8      | 1         | 1.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 97        | 98.98%  |
| 2      | 1         | 1.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 61        | 62.24%  |
| 2      | 37        | 37.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 96        | 97.96%  |
| 32-bit         | 2         | 2.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 11        | 11.22%  |
| 0x206a7    | 9         | 9.18%   |
| Unknown    | 7         | 7.14%   |
| 0x30678    | 5         | 5.1%    |
| 0x6fd      | 4         | 4.08%   |
| 0x10676    | 4         | 4.08%   |
| 0x6fb      | 3         | 3.06%   |
| 0x406c4    | 3         | 3.06%   |
| 0x40651    | 3         | 3.06%   |
| 0x306a9    | 3         | 3.06%   |
| 0x20655    | 3         | 3.06%   |
| 0x010000c8 | 3         | 3.06%   |
| 0x806ea    | 2         | 2.04%   |
| 0x806e9    | 2         | 2.04%   |
| 0x806c1    | 2         | 2.04%   |
| 0x6f6      | 2         | 2.04%   |
| 0x506c9    | 2         | 2.04%   |
| 0x406c3    | 2         | 2.04%   |
| 0x05000119 | 2         | 2.04%   |
| 0xf64      | 1         | 1.02%   |
| 0xa0653    | 1         | 1.02%   |
| 0x906ea    | 1         | 1.02%   |
| 0x906e9    | 1         | 1.02%   |
| 0x906a4    | 1         | 1.02%   |
| 0x806ec    | 1         | 1.02%   |
| 0x806eb    | 1         | 1.02%   |
| 0x706a1    | 1         | 1.02%   |
| 0x6fa      | 1         | 1.02%   |
| 0x6d8      | 1         | 1.02%   |
| 0x506e3    | 1         | 1.02%   |
| 0x406e3    | 1         | 1.02%   |
| 0x306c3    | 1         | 1.02%   |
| 0x30661    | 1         | 1.02%   |
| 0x206c2    | 1         | 1.02%   |
| 0x106ca    | 1         | 1.02%   |
| 0x08701013 | 1         | 1.02%   |
| 0x0810100b | 1         | 1.02%   |
| 0x0800820d | 1         | 1.02%   |
| 0x07030105 | 1         | 1.02%   |
| 0x06006705 | 1         | 1.02%   |
| 0x06006118 | 1         | 1.02%   |
| 0x06001119 | 1         | 1.02%   |
| 0x06000852 | 1         | 1.02%   |
| 0x05000029 | 1         | 1.02%   |
| 0x03000027 | 1         | 1.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 15        | 15.31%  |
| Silvermont       | 10        | 10.2%   |
| Core             | 10        | 10.2%   |
| SandyBridge      | 9         | 9.18%   |
| KabyLake         | 9         | 9.18%   |
| IvyBridge        | 5         | 5.1%    |
| Westmere         | 4         | 4.08%   |
| Haswell          | 4         | 4.08%   |
| K10              | 3         | 3.06%   |
| Bobcat           | 3         | 3.06%   |
| TigerLake        | 2         | 2.04%   |
| Skylake          | 2         | 2.04%   |
| Puma             | 2         | 2.04%   |
| Piledriver       | 2         | 2.04%   |
| P6               | 2         | 2.04%   |
| Goldmont         | 2         | 2.04%   |
| Excavator        | 2         | 2.04%   |
| Bonnell          | 2         | 2.04%   |
| Zen+             | 1         | 1.02%   |
| Zen 2            | 1         | 1.02%   |
| Zen              | 1         | 1.02%   |
| NetBurst         | 1         | 1.02%   |
| K8 Hammer        | 1         | 1.02%   |
| K10 Llano        | 1         | 1.02%   |
| Jaguar           | 1         | 1.02%   |
| Goldmont plus    | 1         | 1.02%   |
| CometLake        | 1         | 1.02%   |
| Alderlake Hybrid | 1         | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 61        | 58.1%   |
| Nvidia | 23        | 21.9%   |
| AMD    | 21        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 4.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 4.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 4.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 4.39%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 4.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 3.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.63%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.75%   |
| Intel HD Graphics 500                                                                    | 2         | 1.75%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 1.75%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.75%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 1.75%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.88%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.88%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.88%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.88%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.88%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.88%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.88%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 0.88%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 0.88%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1         | 0.88%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 0.88%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 0.88%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1         | 0.88%   |
| Nvidia G84 [GeForce 8400 GS]                                                             | 1         | 0.88%   |
| Nvidia G72 [GeForce 7300 GS]                                                             | 1         | 0.88%   |
| Nvidia G71M [GeForce Go 7950 GTX]                                                        | 1         | 0.88%   |
| Nvidia G71GLM [Quadro FX 1500M]                                                          | 1         | 0.88%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 0.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.88%   |
| Intel VGA compatible controller                                                          | 1         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.88%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 0.88%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 1         | 0.88%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 0.88%   |
| Intel HD Graphics 630                                                                    | 1         | 0.88%   |
| Intel HD Graphics 620                                                                    | 1         | 0.88%   |
| Intel HD Graphics 530                                                                    | 1         | 0.88%   |
| Intel HD Graphics 515                                                                    | 1         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.88%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.88%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.88%   |
| Intel 82Q33 Express Integrated Graphics Controller                                       | 1         | 0.88%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 0.88%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1         | 0.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 54        | 55.1%   |
| 1 x AMD        | 18        | 18.37%  |
| 1 x Nvidia     | 16        | 16.33%  |
| Intel + Nvidia | 7         | 7.14%   |
| 2 x AMD        | 3         | 3.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 84        | 84.85%  |
| Proprietary | 14        | 14.14%  |
| Unknown     | 1         | 1.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 57.14%  |
| 0.01-0.5   | 24        | 24.49%  |
| 0.51-1.0   | 7         | 7.14%   |
| 1.01-2.0   | 6         | 6.12%   |
| 3.01-4.0   | 3         | 3.06%   |
| 5.01-6.0   | 2         | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 17.17%  |
| AU Optronics            | 13        | 13.13%  |
| LG Display              | 9         | 9.09%   |
| Hewlett-Packard         | 7         | 7.07%   |
| Goldstar                | 6         | 6.06%   |
| Chimei Innolux          | 6         | 6.06%   |
| Chi Mei Optoelectronics | 6         | 6.06%   |
| BOE                     | 6         | 6.06%   |
| Acer                    | 5         | 5.05%   |
| NEC Computers           | 3         | 3.03%   |
| ViewSonic               | 2         | 2.02%   |
| Sony                    | 2         | 2.02%   |
| Apple                   | 2         | 2.02%   |
| Seiko/Epson             | 1         | 1.01%   |
| SANYO                   | 1         | 1.01%   |
| Philips                 | 1         | 1.01%   |
| PANDA                   | 1         | 1.01%   |
| MSI                     | 1         | 1.01%   |
| LG Philips              | 1         | 1.01%   |
| Lenovo                  | 1         | 1.01%   |
| Hitachi                 | 1         | 1.01%   |
| HannStar                | 1         | 1.01%   |
| eMachines               | 1         | 1.01%   |
| CPT                     | 1         | 1.01%   |
| BenQ                    | 1         | 1.01%   |
| AOC                     | 1         | 1.01%   |
| Ancor Communications    | 1         | 1.01%   |
| Unknown                 | 1         | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.92%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1         | 0.96%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1         | 0.96%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1         | 0.96%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.96%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                   | 1         | 0.96%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.96%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.96%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1         | 0.96%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 0.96%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch  | 1         | 0.96%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 0.96%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1         | 0.96%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.96%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1         | 0.96%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 0.96%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                    | 1         | 0.96%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 0.96%   |
| NEC Computers LCD1990SXi NEC66AC 1280x1024 376x301mm 19.0-inch        | 1         | 0.96%   |
| NEC Computers EA244WMi NEC68D7 1920x1200 519x324mm 24.1-inch          | 1         | 0.96%   |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch            | 1         | 0.96%   |
| MSI G271 MSI3CB5 1920x1080 598x336mm 27.0-inch                        | 1         | 0.96%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 0.96%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD03E3 1366x768 309x174mm 14.0-inch           | 1         | 0.96%   |
| LG Display LCD Monitor LGD038C 1366x768 256x144mm 11.6-inch           | 1         | 0.96%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 1         | 0.96%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch           | 1         | 0.96%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch               | 1         | 0.96%   |
| Hitachi N91W DVI HIT6D0D 1440x900 410x260mm 19.1-inch                 | 1         | 0.96%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 337x270mm 17.0-inch            | 1         | 0.96%   |
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 1         | 0.96%   |
| Hewlett-Packard P201 HWP3056 1600x900 443x249mm 20.0-inch             | 1         | 0.96%   |
| Hewlett-Packard LV2311 HWP3006 1920x1080 510x287mm 23.0-inch          | 1         | 0.96%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1         | 0.96%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1         | 0.96%   |
| Hewlett-Packard f1503 HWP2590 1024x768 304x228mm 15.0-inch            | 1         | 0.96%   |
| Hewlett-Packard All-in-One HWP4211 1920x1080 509x286mm 23.0-inch      | 1         | 0.96%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 0.96%   |
| Goldstar W2254 GSM56DE 1680x1050 474x296mm 22.0-inch                  | 1         | 0.96%   |
| Goldstar W2243 GSM56FF 1920x1080 480x270mm 21.7-inch                  | 1         | 0.96%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                   | 1         | 0.96%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                 | 1         | 0.96%   |
| eMachines E190HQV EMA0212 1280x1024 440x250mm 19.9-inch               | 1         | 0.96%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                  | 1         | 0.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 30        | 30.3%   |
| 1920x1080 (FHD)    | 26        | 26.26%  |
| 1920x1200 (WUXGA)  | 10        | 10.1%   |
| 1280x800 (WXGA)    | 6         | 6.06%   |
| 3840x2160 (4K)     | 5         | 5.05%   |
| 1600x900 (HD+)     | 4         | 4.04%   |
| 1280x1024 (SXGA)   | 4         | 4.04%   |
| 1680x1050 (WSXGA+) | 3         | 3.03%   |
| 1440x900 (WXGA+)   | 3         | 3.03%   |
| Unknown            | 2         | 2.02%   |
| 5280x1080          | 1         | 1.01%   |
| 3840x2400          | 1         | 1.01%   |
| 2560x1440 (QHD)    | 1         | 1.01%   |
| 1360x768           | 1         | 1.01%   |
| 1024x768 (XGA)     | 1         | 1.01%   |
| 1024x600           | 1         | 1.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 21%     |
| 17      | 9         | 9%      |
| 14      | 8         | 8%      |
| 13      | 8         | 8%      |
| 24      | 7         | 7%      |
| Unknown | 7         | 7%      |
| 21      | 6         | 6%      |
| 19      | 5         | 5%      |
| 11      | 5         | 5%      |
| 23      | 4         | 4%      |
| 18      | 4         | 4%      |
| 27      | 3         | 3%      |
| 20      | 3         | 3%      |
| 12      | 2         | 2%      |
| 10      | 2         | 2%      |
| 72      | 1         | 1%      |
| 65      | 1         | 1%      |
| 46      | 1         | 1%      |
| 28      | 1         | 1%      |
| 22      | 1         | 1%      |
| 16      | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 37.37%  |
| 401-500     | 16        | 16.16%  |
| 501-600     | 14        | 14.14%  |
| 201-300     | 12        | 12.12%  |
| 351-400     | 9         | 9.09%   |
| Unknown     | 7         | 7.07%   |
| 1001-1500   | 2         | 2.02%   |
| 601-700     | 1         | 1.01%   |
| 1501-2000   | 1         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 62        | 66.67%  |
| 16/10   | 21        | 22.58%  |
| Unknown | 5         | 5.38%   |
| 5/4     | 4         | 4.3%    |
| 4/3     | 1         | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 21%     |
| 81-90          | 13        | 13%     |
| 201-250        | 12        | 12%     |
| 151-200        | 9         | 9%      |
| Unknown        | 7         | 7%      |
| 141-150        | 6         | 6%      |
| 51-60          | 5         | 5%      |
| 251-300        | 5         | 5%      |
| 131-140        | 4         | 4%      |
| 71-80          | 3         | 3%      |
| 301-350        | 3         | 3%      |
| 121-130        | 3         | 3%      |
| More than 1000 | 2         | 2%      |
| 61-70          | 2         | 2%      |
| 41-50          | 2         | 2%      |
| 351-500        | 1         | 1%      |
| 111-120        | 1         | 1%      |
| 501-1000       | 1         | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 34        | 35.05%  |
| 101-120       | 27        | 27.84%  |
| 121-160       | 23        | 23.71%  |
| Unknown       | 7         | 7.22%   |
| More than 240 | 2         | 2.06%   |
| 1-50          | 2         | 2.06%   |
| 161-240       | 2         | 2.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 87        | 87.88%  |
| 2     | 11        | 11.11%  |
| 3     | 1         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 51        | 34.23%  |
| Intel                                 | 37        | 24.83%  |
| Qualcomm Atheros                      | 22        | 14.77%  |
| Broadcom                              | 14        | 9.4%    |
| Broadcom Limited                      | 5         | 3.36%   |
| Ralink Technology                     | 3         | 2.01%   |
| Ralink                                | 3         | 2.01%   |
| Marvell Technology Group              | 2         | 1.34%   |
| TP-Link                               | 1         | 0.67%   |
| Sierra Wireless                       | 1         | 0.67%   |
| Samsung Electronics                   | 1         | 0.67%   |
| Qualcomm Atheros Communications       | 1         | 0.67%   |
| Nvidia                                | 1         | 0.67%   |
| Microsoft                             | 1         | 0.67%   |
| Linksys                               | 1         | 0.67%   |
| D-Link                                | 1         | 0.67%   |
| ASUSTek Computer                      | 1         | 0.67%   |
| ASIX Electronics                      | 1         | 0.67%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.67%   |
| 3Com                                  | 1         | 0.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 35        | 20.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 11        | 6.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 5         | 2.89%   |
| Intel Wireless 3165                                                                           | 4         | 2.31%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 2.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 3         | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 1.73%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 1.16%   |
| Ralink MT7601U Wireless Adapter                                                               | 2         | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 2         | 1.16%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 2         | 1.16%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.16%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2         | 1.16%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                        | 2         | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.16%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 0.58%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1         | 0.58%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.58%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1         | 0.58%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 0.58%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1         | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.58%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.58%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 0.58%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                    | 1         | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.58%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1         | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1         | 0.58%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.58%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 0.58%   |
| Nvidia MCP61 Ethernet                                                                         | 1         | 0.58%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1         | 0.58%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.58%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                           | 1         | 0.58%   |
| Intel Wireless 7265                                                                           | 1         | 0.58%   |
| Intel Wireless 7260                                                                           | 1         | 0.58%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 0.58%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 0.58%   |
| Intel I211 Gigabit Network Connection                                                         | 1         | 0.58%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 25        | 30.86%  |
| Qualcomm Atheros                      | 20        | 24.69%  |
| Realtek Semiconductor                 | 14        | 17.28%  |
| Broadcom                              | 5         | 6.17%   |
| Ralink Technology                     | 3         | 3.7%    |
| Ralink                                | 3         | 3.7%    |
| Broadcom Limited                      | 3         | 3.7%    |
| TP-Link                               | 1         | 1.23%   |
| Sierra Wireless                       | 1         | 1.23%   |
| Qualcomm Atheros Communications       | 1         | 1.23%   |
| Microsoft                             | 1         | 1.23%   |
| Linksys                               | 1         | 1.23%   |
| D-Link                                | 1         | 1.23%   |
| ASUSTek Computer                      | 1         | 1.23%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Computers | Percent |
|--------------------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                             | 5         | 6.17%   |
| Intel Wireless 3165                                                                                    | 4         | 4.94%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                          | 4         | 4.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                               | 3         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                                        | 3         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 3         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 3         | 3.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                                  | 3         | 3.7%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz]          | 2         | 2.47%   |
| Ralink MT7601U Wireless Adapter                                                                        | 2         | 2.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                         | 2         | 2.47%   |
| Intel Wireless 8265 / 8275                                                                             | 2         | 2.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                                    | 2         | 2.47%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                                | 1         | 1.23%   |
| Sierra Wireless EM7305 Modem                                                                           | 1         | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                               | 1         | 1.23%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                | 1         | 1.23%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                               | 1         | 1.23%   |
| Realtek RTL8723DE Wireless Network Adapter                                                             | 1         | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 1         | 1.23%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                              | 1         | 1.23%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 1         | 1.23%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                                 | 1         | 1.23%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                              | 1         | 1.23%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                              | 1         | 1.23%   |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                       | 1         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 1         | 1.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                         | 1         | 1.23%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                                       | 1         | 1.23%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                             | 1         | 1.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                                | 1         | 1.23%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                                | 1         | 1.23%   |
| Microsoft Xbox 360 Wireless Adapter                                                                    | 1         | 1.23%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                    | 1         | 1.23%   |
| Intel Wireless 7265                                                                                    | 1         | 1.23%   |
| Intel Wireless 7260                                                                                    | 1         | 1.23%   |
| Intel Wi-Fi 6 AX201                                                                                    | 1         | 1.23%   |
| Intel Wi-Fi 6 AX200                                                                                    | 1         | 1.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                                                        | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 1         | 1.23%   |
| Intel Centrino Wireless-N 130                                                                          | 1         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                           | 1         | 1.23%   |
| Intel Centrino Advanced-N 6200                                                                         | 1         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                               | 1         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                        | 1         | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                       | 1         | 1.23%   |
| D-Link WLAN controller                                                                                 | 1         | 1.23%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                             | 1         | 1.23%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                              | 1         | 1.23%   |
| Broadcom Limited BCM4311 802.11b/g WLAN                                                                | 1         | 1.23%   |
| Broadcom BCM43225 802.11b/g/n                                                                          | 1         | 1.23%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                         | 1         | 1.23%   |
| Broadcom BCM4311 802.11b/g WLAN                                                                        | 1         | 1.23%   |
| ASUS WL-167G v2 802.11g Adapter [Ralink RT2571W]                                                       | 1         | 1.23%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v2 Dual-Band Wireless-N Network Adapter [Ralink RT3572] | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 49        | 54.44%  |
| Intel                    | 17        | 18.89%  |
| Broadcom                 | 9         | 10%     |
| Qualcomm Atheros         | 7         | 7.78%   |
| Marvell Technology Group | 2         | 2.22%   |
| Broadcom Limited         | 2         | 2.22%   |
| Samsung Electronics      | 1         | 1.11%   |
| Nvidia                   | 1         | 1.11%   |
| ASIX Electronics         | 1         | 1.11%   |
| 3Com                     | 1         | 1.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 35        | 38.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 11        | 12.09%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5         | 5.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 2.2%    |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 2.2%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 2.2%    |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 1.1%    |
| Realtek USB 10/100 LAN                                                        | 1         | 1.1%    |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.1%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 1.1%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 1.1%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 1.1%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 1.1%    |
| Nvidia MCP61 Ethernet                                                         | 1         | 1.1%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 1.1%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 1.1%    |
| Intel I211 Gigabit Network Connection                                         | 1         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 1.1%    |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 1.1%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.1%    |
| Intel 82567V-2 Gigabit Network Connection                                     | 1         | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 1.1%    |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.1%    |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 1.1%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 1.1%    |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 1.1%    |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express                      | 1         | 1.1%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 1.1%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.1%    |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 1         | 1.1%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 1         | 1.1%    |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express              | 1         | 1.1%    |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express              | 1         | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                                 | 1         | 1.1%    |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 1         | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 85        | 52.15%  |
| WiFi     | 77        | 47.24%  |
| Unknown  | 1         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 60.19%  |
| Ethernet | 41        | 39.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 56        | 57.14%  |
| 1     | 37        | 37.76%  |
| 3     | 2         | 2.04%   |
| 0     | 2         | 2.04%   |
| 4     | 1         | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 81        | 82.65%  |
| Yes  | 17        | 17.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 30.77%  |
| Realtek Semiconductor           | 7         | 13.46%  |
| Lite-On Technology              | 4         | 7.69%   |
| IMC Networks                    | 4         | 7.69%   |
| Cambridge Silicon Radio         | 4         | 7.69%   |
| Broadcom                        | 4         | 7.69%   |
| Qualcomm Atheros Communications | 3         | 5.77%   |
| Hewlett-Packard                 | 3         | 5.77%   |
| Dell                            | 2         | 3.85%   |
| Apple                           | 2         | 3.85%   |
| Toshiba                         | 1         | 1.92%   |
| Ralink                          | 1         | 1.92%   |
| Foxconn / Hon Hai               | 1         | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 15.38%  |
| Realtek Bluetooth Radio                             | 4         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.77%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 3.85%   |
| IMC Networks Bluetooth Device                       | 2         | 3.85%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 3.85%   |
| Dell Wireless 355 Bluetooth                         | 2         | 3.85%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 3.85%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.92%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.92%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.92%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.92%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.92%   |
| Lite-On Bluetooth Device                            | 1         | 1.92%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.92%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.92%   |
| Intel Bluetooth Device                              | 1         | 1.92%   |
| Intel AX201 Bluetooth                               | 1         | 1.92%   |
| Intel AX200 Bluetooth                               | 1         | 1.92%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.92%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.92%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.92%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.92%   |
| Broadcom HP Portable Valentine                      | 1         | 1.92%   |
| Broadcom HP Bluethunder                             | 1         | 1.92%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.92%   |
| Apple Bluetooth HCI                                 | 1         | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 74        | 63.79%  |
| AMD                   | 22        | 18.97%  |
| Nvidia                | 11        | 9.48%   |
| Logitech              | 2         | 1.72%   |
| C-Media Electronics   | 2         | 1.72%   |
| Texas Instruments     | 1         | 0.86%   |
| Realtek Semiconductor | 1         | 0.86%   |
| Ensoniq               | 1         | 0.86%   |
| Creative Labs         | 1         | 0.86%   |
| Blue Microphones      | 1         | 0.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 8.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 5.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.48%   |
| AMD FCH Azalia Controller                                                                         | 6         | 4.48%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 3.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 3.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 3.73%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 2.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.24%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 2.24%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.24%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 2.24%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 2.24%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.49%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.49%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.49%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.49%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.75%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1         | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.75%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.75%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Logitech Wireless Headset                                                                         | 1         | 0.75%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.75%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.75%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.75%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.75%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.75%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 1         | 0.75%   |
| Ensoniq 5880B / Creative Labs CT5880                                                              | 1         | 0.75%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1         | 0.75%   |
| C-Media Electronics Multimedia Headset [Gigaware by Ignition L.P.]                                | 1         | 0.75%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.75%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 0.75%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.75%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.75%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 0.75%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.75%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 17        | 18.28%  |
| Samsung Electronics | 16        | 17.2%   |
| SK hynix            | 13        | 13.98%  |
| Micron Technology   | 11        | 11.83%  |
| Kingston            | 11        | 11.83%  |
| Unknown             | 4         | 4.3%    |
| Elpida              | 3         | 3.23%   |
| Unknown (ABCD)      | 2         | 2.15%   |
| Ramaxel Technology  | 2         | 2.15%   |
| Nanya Technology    | 2         | 2.15%   |
| A-DATA Technology   | 2         | 2.15%   |
| Transcend           | 1         | 1.08%   |
| Qumo                | 1         | 1.08%   |
| Qimonda             | 1         | 1.08%   |
| GeIL                | 1         | 1.08%   |
| Corsair             | 1         | 1.08%   |
| Avant               | 1         | 1.08%   |
| 2C0C1121390963FE    | 1         | 1.08%   |
| 2C0C1121390963FD    | 1         | 1.08%   |
| 2C0C1121390963F9    | 1         | 1.08%   |
| 2C0C1121390963F8    | 1         | 1.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 4         | 4.17%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 2         | 2.08%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 2.08%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 2.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 1         | 1.04%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                             | 1         | 1.04%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 1         | 1.04%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 1.04%   |
| Unknown RAM Module 2048MB DIMM DDR2                                 | 1         | 1.04%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                          | 1         | 1.04%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                          | 1         | 1.04%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                              | 1         | 1.04%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                      | 1         | 1.04%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 1024MB DIMM DDR2                                 | 1         | 1.04%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                          | 1         | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s        | 1         | 1.04%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.04%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 1.04%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                       | 1         | 1.04%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s               | 1         | 1.04%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s               | 1         | 1.04%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT112U6TFR8C-H9 1024MB DIMM DDR3 1333MT/s             | 1         | 1.04%   |
| SK hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s                | 1         | 1.04%   |
| SK hynix RAM H5TC4G63CFR-PBA 2048MB SODIMM DDR3 1600MT/s            | 1         | 1.04%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 1.04%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 1.04%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.04%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.04%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 1.04%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 1.04%   |
| Samsung RAM M471A1G44BB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.04%   |
| Samsung RAM M4 70T5669AZ0-CE6 2GB SODIMM DDR2 667MT/s               | 1         | 1.04%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s           | 1         | 1.04%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR 2048MT/s               | 1         | 1.04%   |
| Samsung RAM M378B5673FH0-CH9 2048MB DIMM DDR3 1600MT/s              | 1         | 1.04%   |
| Samsung RAM M378B2873FH0-CH9 1024MB DIMM DDR3 1333MT/s              | 1         | 1.04%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s              | 1         | 1.04%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 1639MT/s                | 1         | 1.04%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 1.04%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 1         | 1.04%   |
| Qumo RAM Module 4096MB DIMM DDR3 1333MT/s                           | 1         | 1.04%   |
| Qimonda RAM 64T128021EDL2.5B2 1024MB SODIMM DDR2 800MT/s            | 1         | 1.04%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                | 1         | 1.04%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR2 2048MT/s                | 1         | 1.04%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                            | 1         | 1.04%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| Micron RAM 8HTF12864AY-800G1 1GB DIMM DDR 800MT/s                   | 1         | 1.04%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 35.9%   |
| DDR2    | 16        | 20.51%  |
| DDR4    | 15        | 19.23%  |
| SDRAM   | 8         | 10.26%  |
| LPDDR4  | 4         | 5.13%   |
| Unknown | 4         | 5.13%   |
| DDR     | 3         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 46        | 61.33%  |
| DIMM    | 28        | 37.33%  |
| FB-DIMM | 1         | 1.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 30        | 36.14%  |
| 4096  | 23        | 27.71%  |
| 8192  | 15        | 18.07%  |
| 1024  | 12        | 14.46%  |
| 16384 | 3         | 3.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 20        | 25%     |
| 3200    | 7         | 8.75%   |
| 2667    | 7         | 8.75%   |
| Unknown | 7         | 8.75%   |
| 1333    | 6         | 7.5%    |
| 667     | 6         | 7.5%    |
| 2400    | 3         | 3.75%   |
| 975     | 3         | 3.75%   |
| 800     | 3         | 3.75%   |
| 4199    | 2         | 2.5%    |
| 2048    | 2         | 2.5%    |
| 1066    | 2         | 2.5%    |
| 400     | 2         | 2.5%    |
| 49926   | 1         | 1.25%   |
| 19791   | 1         | 1.25%   |
| 3500    | 1         | 1.25%   |
| 3266    | 1         | 1.25%   |
| 2133    | 1         | 1.25%   |
| 1866    | 1         | 1.25%   |
| 1639    | 1         | 1.25%   |
| 1334    | 1         | 1.25%   |
| 1033    | 1         | 1.25%   |
| 133     | 1         | 1.25%   |

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
| Chicony Electronics                    | 16        | 28.07%  |
| Suyin                                  | 5         | 8.77%   |
| Quanta                                 | 5         | 8.77%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 8.77%   |
| Silicon Motion                         | 3         | 5.26%   |
| IMC Networks                           | 3         | 5.26%   |
| Sunplus Innovation Technology          | 2         | 3.51%   |
| Realtek Semiconductor                  | 2         | 3.51%   |
| Apple                                  | 2         | 3.51%   |
| Alcor Micro                            | 2         | 3.51%   |
| Z-Star Microelectronics                | 1         | 1.75%   |
| Unknown                                | 1         | 1.75%   |
| Ricoh                                  | 1         | 1.75%   |
| OmniVision Technologies                | 1         | 1.75%   |
| Microsoft                              | 1         | 1.75%   |
| Microdia                               | 1         | 1.75%   |
| Logitech                               | 1         | 1.75%   |
| Lite-On Technology                     | 1         | 1.75%   |
| Jieli Technology                       | 1         | 1.75%   |
| Hewlett-Packard                        | 1         | 1.75%   |
| Generalplus Technology                 | 1         | 1.75%   |
| Aveo Technology                        | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                               | 5         | 8.77%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 2         | 3.51%   |
| Quanta HP TrueVision HD Camera                              | 2         | 3.51%   |
| Chicony FJ Camera                                           | 2         | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 3.51%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 1.75%   |
| Unknown Integrated RGB Camera                               | 1         | 1.75%   |
| Suyin USB 2.0 Camera                                        | 1         | 1.75%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 1.75%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 1.75%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.75%   |
| Sunplus HD WebCam                                           | 1         | 1.75%   |
| Silicon Motion WebCam SC-10HDD13335N                        | 1         | 1.75%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 1.75%   |
| Silicon Motion Web Camera                                   | 1         | 1.75%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 1.75%   |
| Realtek USB2.0 HD UVC WebCam                                | 1         | 1.75%   |
| Realtek USB Camera                                          | 1         | 1.75%   |
| Quanta VGA WebCam                                           | 1         | 1.75%   |
| Quanta HP Truevision HD                                     | 1         | 1.75%   |
| Quanta HD Webcam                                            | 1         | 1.75%   |
| OmniVision OV2640 Webcam                                    | 1         | 1.75%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks         | 1         | 1.75%   |
| Microdia Integrated_Webcam_FHD                              | 1         | 1.75%   |
| Logitech HD Webcam C615                                     | 1         | 1.75%   |
| Lite-On Integrated Camera                                   | 1         | 1.75%   |
| Jieli USB PHY 2.0                                           | 1         | 1.75%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 1.75%   |
| IMC Networks EasyCamera                                     | 1         | 1.75%   |
| IMC Networks 2M Integrated Webcam                           | 1         | 1.75%   |
| HP Webcam HD 2300                                           | 1         | 1.75%   |
| Generalplus GENERAL WEBCAM                                  | 1         | 1.75%   |
| Chicony VGA Webcam                                          | 1         | 1.75%   |
| Chicony USB 2.0 Camera                                      | 1         | 1.75%   |
| Chicony Integrated Camera                                   | 1         | 1.75%   |
| Chicony HP Webcam                                           | 1         | 1.75%   |
| Chicony HP TrueVision HD                                    | 1         | 1.75%   |
| Chicony HP High Definition 1MP Webcam                       | 1         | 1.75%   |
| Chicony HD WebCam (Asus N-series)                           | 1         | 1.75%   |
| Chicony HD WebCam                                           | 1         | 1.75%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) FJ 5M Camera         | 1         | 1.75%   |
| Aveo USB2.0 Camera                                          | 1         | 1.75%   |
| Apple iPhone 5/5C/5S/6/SE                                   | 1         | 1.75%   |
| Apple Built-in iSight                                       | 1         | 1.75%   |
| Alcor Micro Asus Integrated Webcam                          | 1         | 1.75%   |
| Alcor Micro Acer Integrated Webcam                          | 1         | 1.75%   |

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
| 0     | 77        | 77.78%  |
| 1     | 18        | 18.18%  |
| 2     | 4         | 4.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 30.77%  |
| Net/wireless             | 4         | 15.38%  |
| Graphics card            | 2         | 7.69%   |
| Chipcard                 | 2         | 7.69%   |
| Bluetooth                | 2         | 7.69%   |
| Unassigned class         | 1         | 3.85%   |
| Storage                  | 1         | 3.85%   |
| Sound                    | 1         | 3.85%   |
| Network                  | 1         | 3.85%   |
| Net/ethernet             | 1         | 3.85%   |
| Multimedia controller    | 1         | 3.85%   |
| Dvb card                 | 1         | 3.85%   |
| Communication controller | 1         | 3.85%   |

