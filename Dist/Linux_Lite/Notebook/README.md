Linux Lite - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Linux Lite.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 115

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | Laptop 15-db0xxx            | [892229f999](https://linux-hardware.org/?probe=892229f999) | Jun 28, 2023 |
| HP       | Laptop 15-db0xxx            | [6d470794e9](https://linux-hardware.org/?probe=6d470794e9) | Jun 28, 2023 |
| UNOWHY   | Y13G010S4EI                 | [b36de255fe](https://linux-hardware.org/?probe=b36de255fe) | Jun 22, 2023 |
| UNOWHY   | Y13G010S4EI                 | [f8f4049a95](https://linux-hardware.org/?probe=f8f4049a95) | Jun 22, 2023 |
| Dell     | Latitude E6420              | [e86a159ec5](https://linux-hardware.org/?probe=e86a159ec5) | Jun 03, 2023 |
| Dell     | Latitude E6420              | [01cd20c83d](https://linux-hardware.org/?probe=01cd20c83d) | Jun 03, 2023 |
| Lenovo   | ThinkPad X240 20AMS1J100    | [86edc6c6d6](https://linux-hardware.org/?probe=86edc6c6d6) | May 11, 2023 |
| Apple    | MacBookAir4,1               | [87ab055a31](https://linux-hardware.org/?probe=87ab055a31) | Apr 27, 2023 |
| Lenovo   | IdeaPad 100-15IBY 80MJ      | [c5c1b213f2](https://linux-hardware.org/?probe=c5c1b213f2) | Apr 16, 2023 |
| Lenovo   | IdeaPad 330S-15AST 81F9     | [d79463ea93](https://linux-hardware.org/?probe=d79463ea93) | Apr 04, 2023 |
| Toshiba  | QOSMIO X70-B                | [8d94a6c8e7](https://linux-hardware.org/?probe=8d94a6c8e7) | Mar 28, 2023 |
| HP       | EliteBook 2530p             | [06ad8714ea](https://linux-hardware.org/?probe=06ad8714ea) | Mar 22, 2023 |
| Lenovo   | ThinkPad A475 20KMS08300    | [b42df5cbe0](https://linux-hardware.org/?probe=b42df5cbe0) | Mar 11, 2023 |
| Lenovo   | ThinkPad A475 20KMS08300    | [17a3030488](https://linux-hardware.org/?probe=17a3030488) | Mar 11, 2023 |
| Gateway  | Sonic-C                     | [b9f775b14e](https://linux-hardware.org/?probe=b9f775b14e) | Feb 28, 2023 |
| Gateway  | Sonic-C                     | [6def275f9b](https://linux-hardware.org/?probe=6def275f9b) | Feb 26, 2023 |
| ASUSTek  | G73Sw                       | [199c8805ee](https://linux-hardware.org/?probe=199c8805ee) | Feb 10, 2023 |
| HP       | 240 G3                      | [a977b66ced](https://linux-hardware.org/?probe=a977b66ced) | Feb 02, 2023 |
| HP       | 240 G3                      | [816a3f4b28](https://linux-hardware.org/?probe=816a3f4b28) | Feb 02, 2023 |
| ASUSTek  | G73Sw                       | [b8891cfc9b](https://linux-hardware.org/?probe=b8891cfc9b) | Jan 27, 2023 |
| ASUSTek  | G73Sw                       | [fb0a23c0e6](https://linux-hardware.org/?probe=fb0a23c0e6) | Jan 27, 2023 |
| ASUSTek  | G73Sw                       | [24b6a47ebb](https://linux-hardware.org/?probe=24b6a47ebb) | Jan 27, 2023 |
| ASUSTek  | G73Sw                       | [adbc469f95](https://linux-hardware.org/?probe=adbc469f95) | Jan 22, 2023 |
| ASUSTek  | G73Sw                       | [9249ff32b3](https://linux-hardware.org/?probe=9249ff32b3) | Jan 22, 2023 |
| HP       | Stream Notebook PC 13       | [b31d60976b](https://linux-hardware.org/?probe=b31d60976b) | Jan 14, 2023 |
| Acer     | Aspire A315-53              | [eb42b5e055](https://linux-hardware.org/?probe=eb42b5e055) | Dec 24, 2022 |
| Pegatron | H36FF                       | [f27fc61f18](https://linux-hardware.org/?probe=f27fc61f18) | Dec 18, 2022 |
| Thomson  | PT-NEO14A.2WH32             | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| Pegatron | H36FF                       | [692955be3d](https://linux-hardware.org/?probe=692955be3d) | Dec 18, 2022 |
| Acer     | Nitro AN515-58              | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| UMAX     | VisionBook 12Wi 64G         | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| HP       | Compaq Presario CQ50        | [8546f55697](https://linux-hardware.org/?probe=8546f55697) | Oct 24, 2022 |
| HP       | Compaq Presario CQ50        | [3b1b5c18c6](https://linux-hardware.org/?probe=3b1b5c18c6) | Oct 24, 2022 |
| Acer     | Aspire 5600                 | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| MSI      | MS-N014                     | [4c41640fd3](https://linux-hardware.org/?probe=4c41640fd3) | Oct 12, 2022 |
| MSI      | MS-N014                     | [3144cac65a](https://linux-hardware.org/?probe=3144cac65a) | Oct 12, 2022 |
| Lenovo   | IdeaPad 100-14IBY 80MH      | [676289f650](https://linux-hardware.org/?probe=676289f650) | Oct 02, 2022 |
| HP       | Compaq 420                  | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP       | Presario V6000 (RG289UA#... | [7f0113694a](https://linux-hardware.org/?probe=7f0113694a) | Sep 15, 2022 |
| Samsung  | X420/X520                   | [a8ca7bb005](https://linux-hardware.org/?probe=a8ca7bb005) | Sep 04, 2022 |
| Fujitsu  | FMVNQ8P6                    | [5e34698f14](https://linux-hardware.org/?probe=5e34698f14) | Aug 28, 2022 |
| ASUSTek  | UX303LN                     | [63d5525864](https://linux-hardware.org/?probe=63d5525864) | Aug 16, 2022 |
| Lenovo   | ThinkPad L480 20LS001AMC    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| Apple    | MacBookAir6,1               | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| ASUSTek  | VivoBook 14_ASUS Laptop ... | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| HP       | Pavilion g4                 | [330078dbac](https://linux-hardware.org/?probe=330078dbac) | Jul 04, 2022 |
| ASUSTek  | X555YI                      | [762b96a2de](https://linux-hardware.org/?probe=762b96a2de) | Jul 02, 2022 |
| HP       | EliteBook 8440p             | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| Samsung  | 530XBB                      | [485a99ca42](https://linux-hardware.org/?probe=485a99ca42) | Jun 03, 2022 |
| Minix    | Z64 V1.2                    | [97525a1dc3](https://linux-hardware.org/?probe=97525a1dc3) | May 27, 2022 |
| Dell     | Inspiron 16 5620            | [b42e1cf95b](https://linux-hardware.org/?probe=b42e1cf95b) | May 13, 2022 |
| Minix    | Z64 V1.2                    | [8796deded0](https://linux-hardware.org/?probe=8796deded0) | May 12, 2022 |
| Dell     | MXG061                      | [119f6dd774](https://linux-hardware.org/?probe=119f6dd774) | May 09, 2022 |
| Lenovo   | IdeaPad Gaming 3 15IHU6 ... | [ab553d3a2f](https://linux-hardware.org/?probe=ab553d3a2f) | May 01, 2022 |
| Acer     | Extensa 5220                | [ebbd01171d](https://linux-hardware.org/?probe=ebbd01171d) | May 01, 2022 |
| Acer     | Aspire 1410                 | [703c2ec84a](https://linux-hardware.org/?probe=703c2ec84a) | Apr 21, 2022 |
| Lenovo   | ThinkPad T400 6475E13       | [cd49ac8445](https://linux-hardware.org/?probe=cd49ac8445) | Apr 08, 2022 |
| Dell     | MXG061                      | [9c91bd9487](https://linux-hardware.org/?probe=9c91bd9487) | Apr 06, 2022 |
| Insignia | NS-P11W7100                 | [daa476af8c](https://linux-hardware.org/?probe=daa476af8c) | Mar 28, 2022 |
| Dell     | MXG071                      | [ac0158dcb9](https://linux-hardware.org/?probe=ac0158dcb9) | Mar 27, 2022 |
| HP       | 15 Notebook PC              | [0f99b7ff76](https://linux-hardware.org/?probe=0f99b7ff76) | Mar 21, 2022 |
| HP       | Compaq CQ45                 | [99286efd08](https://linux-hardware.org/?probe=99286efd08) | Mar 10, 2022 |
| HP       | Laptop 15-dw3xxx            | [2b748962fa](https://linux-hardware.org/?probe=2b748962fa) | Mar 06, 2022 |
| ASUSTek  | 900                         | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Acer     | Aspire A315-53              | [6134bb8cba](https://linux-hardware.org/?probe=6134bb8cba) | Feb 18, 2022 |
| Acer     | Aspire 5600                 | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| HP       | Laptop 15-dw3xxx            | [b596d9fdb1](https://linux-hardware.org/?probe=b596d9fdb1) | Feb 09, 2022 |
| HP       | Compaq nw9440 (EY615ET#A... | [6a5c3254ab](https://linux-hardware.org/?probe=6a5c3254ab) | Jan 30, 2022 |
| HP       | Pavilion dv6500             | [15838ae11b](https://linux-hardware.org/?probe=15838ae11b) | Jan 12, 2022 |
| ASUSTek  | N53Jf                       | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek  | N53Jf                       | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| ASUSTek  | X541SA                      | [26f2eeeefc](https://linux-hardware.org/?probe=26f2eeeefc) | Dec 31, 2021 |
| HP       | Pavilion dv6500             | [978ee4328d](https://linux-hardware.org/?probe=978ee4328d) | Dec 19, 2021 |
| Acer     | Aspire 5600                 | [25b1e50c64](https://linux-hardware.org/?probe=25b1e50c64) | Dec 12, 2021 |
| HP       | Compaq 2510p                | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| HP       | Compaq 2510p                | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| Samsung  | 905S3G/906S3G/915S3G/930... | [b7306537cc](https://linux-hardware.org/?probe=b7306537cc) | Nov 10, 2021 |
| Acer     | Aspire 5600                 | [7e2da6d3e9](https://linux-hardware.org/?probe=7e2da6d3e9) | Oct 26, 2021 |
| Dell     | MXG061                      | [89a5b20193](https://linux-hardware.org/?probe=89a5b20193) | Oct 10, 2021 |
| Acer     | Swift SF314-56              | [263d6e38b7](https://linux-hardware.org/?probe=263d6e38b7) | Oct 01, 2021 |
| Acer     | Swift SF314-56              | [bb0f894bce](https://linux-hardware.org/?probe=bb0f894bce) | Oct 01, 2021 |
| Dell     | Vostro1710                  | [d50123c66a](https://linux-hardware.org/?probe=d50123c66a) | Sep 01, 2021 |
| Dell     | Inspiron 5452               | [0c9b3ec7a9](https://linux-hardware.org/?probe=0c9b3ec7a9) | Aug 07, 2021 |
| HP       | EliteBook Folio 9470m       | [b2b851f7d2](https://linux-hardware.org/?probe=b2b851f7d2) | Jul 12, 2021 |
| ASUSTek  | X541SA                      | [ed8bb15f60](https://linux-hardware.org/?probe=ed8bb15f60) | Jul 11, 2021 |
| HP       | Laptop 14-cm0xxx            | [5943266aca](https://linux-hardware.org/?probe=5943266aca) | Jun 18, 2021 |
| HP       | Laptop 14-cm0xxx            | [3b4a122b75](https://linux-hardware.org/?probe=3b4a122b75) | Jun 18, 2021 |
| Fujitsu  | LIFEBOOK U747               | [117e8bf660](https://linux-hardware.org/?probe=117e8bf660) | Jun 17, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [a9255b2217](https://linux-hardware.org/?probe=a9255b2217) | Jun 04, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop E203... | [58bf661e8d](https://linux-hardware.org/?probe=58bf661e8d) | Apr 15, 2021 |
| ASUSTek  | K50IE                       | [b0bcc6c31c](https://linux-hardware.org/?probe=b0bcc6c31c) | Apr 12, 2021 |
| ASUSTek  | K54LY                       | [dc7d86f51e](https://linux-hardware.org/?probe=dc7d86f51e) | Mar 21, 2021 |
| Acer     | Aspire V5-552               | [7a32a8a1c3](https://linux-hardware.org/?probe=7a32a8a1c3) | Mar 03, 2021 |
| HP       | Compaq 6735b                | [0f2afbc99a](https://linux-hardware.org/?probe=0f2afbc99a) | Feb 18, 2021 |
| Dell     | Inspiron 7559               | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| HP       | Laptop 17-by2xxx            | [729abf0085](https://linux-hardware.org/?probe=729abf0085) | Jan 30, 2021 |
| Acer     | Predator PH317-52           | [1bd05ad341](https://linux-hardware.org/?probe=1bd05ad341) | Jan 24, 2021 |
| HP       | 655                         | [a6913cacf3](https://linux-hardware.org/?probe=a6913cacf3) | Dec 28, 2020 |
| HP       | 655                         | [2a4c81218e](https://linux-hardware.org/?probe=2a4c81218e) | Dec 27, 2020 |
| Toshiba  | Satellite T215D             | [084f254e1f](https://linux-hardware.org/?probe=084f254e1f) | Dec 23, 2020 |
| Toshiba  | Satellite T215D             | [bdb8fe4e55](https://linux-hardware.org/?probe=bdb8fe4e55) | Dec 23, 2020 |
| Lenovo   | IdeaPad 320-15ABR 80XS      | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| ASUSTek  | 1001PX                      | [9f911bde1c](https://linux-hardware.org/?probe=9f911bde1c) | Dec 11, 2020 |
| Acer     | Aspire 5750                 | [ba47872fd5](https://linux-hardware.org/?probe=ba47872fd5) | Dec 02, 2020 |
| Acer     | Aspire 5750                 | [c4216f5d80](https://linux-hardware.org/?probe=c4216f5d80) | Dec 02, 2020 |
| Dell     | Latitude D530               | [4fe18e86ac](https://linux-hardware.org/?probe=4fe18e86ac) | Sep 27, 2020 |
| Acer     | Aspire ES1-511              | [63a7ae1967](https://linux-hardware.org/?probe=63a7ae1967) | Jul 24, 2020 |
| Google   | Chell                       | [cf727e9a6e](https://linux-hardware.org/?probe=cf727e9a6e) | Jul 23, 2020 |
| ASUSTek  | X751LD                      | [2d9ea757d1](https://linux-hardware.org/?probe=2d9ea757d1) | Jul 14, 2020 |
| ASUSTek  | X751LD                      | [1a4ee704d9](https://linux-hardware.org/?probe=1a4ee704d9) | Jul 14, 2020 |
| Lenovo   | 3000 V200 0764A11           | [8492023ae0](https://linux-hardware.org/?probe=8492023ae0) | Jul 13, 2020 |
| TR       | ST Pro-KN                   | [e78b2937ef](https://linux-hardware.org/?probe=e78b2937ef) | Jul 01, 2020 |
| ASUSTek  | N750JK                      | [9102fbcf41](https://linux-hardware.org/?probe=9102fbcf41) | Jun 02, 2020 |
| Samsung  | NC110P/NC108P/NC111P        | [92c219ffb4](https://linux-hardware.org/?probe=92c219ffb4) | May 14, 2020 |
| ASUSTek  | X540YA                      | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Linux Lite 6.0 | 13        | 15.85%  |
| Linux Lite 5.8 | 13        | 15.85%  |
| Linux Lite 6.2 | 11        | 13.41%  |
| Linux Lite 5.4 | 10        | 12.2%   |
| Linux Lite 5.2 | 9         | 10.98%  |
| Linux Lite 5.0 | 8         | 9.76%   |
| Linux Lite 5.6 | 7         | 8.54%   |
| Linux Lite 6.4 | 4         | 4.88%   |
| Linux Lite 3.8 | 3         | 3.66%   |
| Linux Lite 4.8 | 2         | 2.44%   |
| Linux Lite 4.4 | 1         | 1.22%   |
| Linux Lite 4.2 | 1         | 1.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Linux Lite | 80        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.4.0-40-generic      | 4         | 4.55%   |
| 5.15.0-69-generic     | 4         | 4.55%   |
| 5.4.0-70-generic      | 3         | 3.41%   |
| 5.4.0-52-generic      | 3         | 3.41%   |
| 5.4.0-109-generic     | 3         | 3.41%   |
| 5.15.0-33-generic     | 3         | 3.41%   |
| 5.4.0-91-generic      | 2         | 2.27%   |
| 5.4.0-90-generic      | 2         | 2.27%   |
| 5.4.0-81-generic      | 2         | 2.27%   |
| 5.4.0-74-generic      | 2         | 2.27%   |
| 5.4.0-58-generic      | 2         | 2.27%   |
| 5.4.0-42-generic      | 2         | 2.27%   |
| 5.4.0-107-generic     | 2         | 2.27%   |
| 5.4.0-104-generic     | 2         | 2.27%   |
| 5.15.0-60-generic     | 2         | 2.27%   |
| 5.15.0-56-generic     | 2         | 2.27%   |
| 5.15.0-52-generic     | 2         | 2.27%   |
| 5.15.0-48-generic     | 2         | 2.27%   |
| 5.15.0-47-generic     | 2         | 2.27%   |
| 6.1.0-1.linuxlite     | 1         | 1.14%   |
| 6.0.0                 | 1         | 1.14%   |
| 5.4.0-96-generic      | 1         | 1.14%   |
| 5.4.0-94-generic      | 1         | 1.14%   |
| 5.4.0-88-generic      | 1         | 1.14%   |
| 5.4.0-77-generic      | 1         | 1.14%   |
| 5.4.0-71-generic      | 1         | 1.14%   |
| 5.4.0-66-generic      | 1         | 1.14%   |
| 5.4.0-65-generic      | 1         | 1.14%   |
| 5.4.0-56-generic      | 1         | 1.14%   |
| 5.4.0-48-generic      | 1         | 1.14%   |
| 5.4.0-33-generic      | 1         | 1.14%   |
| 5.4.0-152-generic     | 1         | 1.14%   |
| 5.4.0-124-generic     | 1         | 1.14%   |
| 5.4.0-122-generic     | 1         | 1.14%   |
| 5.4.0-113-generic     | 1         | 1.14%   |
| 5.4.0-110-generic     | 1         | 1.14%   |
| 5.4.0-105-generic     | 1         | 1.14%   |
| 5.4.0-100-generic     | 1         | 1.14%   |
| 5.19.0-051900-generic | 1         | 1.14%   |
| 5.16.0                | 1         | 1.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 45        | 54.22%  |
| 5.15.0  | 26        | 31.33%  |
| 4.15.0  | 4         | 4.82%   |
| 4.4.0   | 2         | 2.41%   |
| 6.1.0   | 1         | 1.2%    |
| 6.0.0   | 1         | 1.2%    |
| 5.19.0  | 1         | 1.2%    |
| 5.16.0  | 1         | 1.2%    |
| 5.13.0  | 1         | 1.2%    |
| 5.10.0  | 1         | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 45        | 54.22%  |
| 5.15    | 26        | 31.33%  |
| 4.15    | 4         | 4.82%   |
| 4.4     | 2         | 2.41%   |
| 6.1     | 1         | 1.2%    |
| 6.0     | 1         | 1.2%    |
| 5.19    | 1         | 1.2%    |
| 5.16    | 1         | 1.2%    |
| 5.13    | 1         | 1.2%    |
| 5.10    | 1         | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 78        | 97.5%   |
| i686   | 2         | 2.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 65        | 81.25%  |
| GNOME   | 12        | 15%     |
| Unknown | 2         | 2.5%    |
| Deepin  | 1         | 1.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 78        | 97.5%   |
| Tty     | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 53        | 64.63%  |
| TDM     | 15        | 18.29%  |
| Unknown | 13        | 15.85%  |
| GDM     | 1         | 1.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 45        | 56.25%  |
| de_DE | 6         | 7.5%    |
| pl_PL | 5         | 6.25%   |
| fr_FR | 5         | 6.25%   |
| en_GB | 3         | 3.75%   |
| ru_UA | 2         | 2.5%    |
| ru_RU | 2         | 2.5%    |
| pt_BR | 2         | 2.5%    |
| it_IT | 2         | 2.5%    |
| es_ES | 2         | 2.5%    |
| zh_CN | 1         | 1.25%   |
| pt_PT | 1         | 1.25%   |
| es_CO | 1         | 1.25%   |
| en_PH | 1         | 1.25%   |
| en_IN | 1         | 1.25%   |
| en_AU | 1         | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 42        | 52.5%   |
| BIOS | 38        | 47.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 69        | 86.25%  |
| Overlay | 7         | 8.75%   |
| Btrfs   | 2         | 2.5%    |
| Zfs     | 1         | 1.25%   |
| Tmpfs   | 1         | 1.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 38        | 47.5%   |
| Unknown | 24        | 30%     |
| MBR     | 18        | 22.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 86.42%  |
| Yes       | 11        | 13.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 70.37%  |
| Yes       | 24        | 29.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 18        | 22.5%   |
| ASUSTek Computer    | 14        | 17.5%   |
| Lenovo              | 10        | 12.5%   |
| Acer                | 10        | 12.5%   |
| Dell                | 8         | 10%     |
| Samsung Electronics | 4         | 5%      |
| Toshiba             | 2         | 2.5%    |
| Fujitsu             | 2         | 2.5%    |
| Apple               | 2         | 2.5%    |
| UNOWHY              | 1         | 1.25%   |
| UMAX                | 1         | 1.25%   |
| TR                  | 1         | 1.25%   |
| Thomson             | 1         | 1.25%   |
| Pegatron            | 1         | 1.25%   |
| MSI                 | 1         | 1.25%   |
| Minix               | 1         | 1.25%   |
| Insignia            | 1         | 1.25%   |
| Google              | 1         | 1.25%   |
| Gateway             | 1         | 1.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| UNOWHY Y13G010S4EI                  | 1         | 1.25%   |
| UMAX VisionBook 12Wi 64G            | 1         | 1.25%   |
| TR ST Pro-KN                        | 1         | 1.25%   |
| Toshiba Satellite T215D             | 1         | 1.25%   |
| Toshiba QOSMIO X70-B                | 1         | 1.25%   |
| Thomson PT-NEO14A.2WH32             | 1         | 1.25%   |
| Samsung X420/X520                   | 1         | 1.25%   |
| Samsung NC110P/NC108P/NC111P        | 1         | 1.25%   |
| Samsung 905S3G/906S3G/915S3G/9305SG | 1         | 1.25%   |
| Samsung 530XBB                      | 1         | 1.25%   |
| Pegatron H36FF                      | 1         | 1.25%   |
| MSI MS-N014                         | 1         | 1.25%   |
| Minix Z64                           | 1         | 1.25%   |
| Lenovo ThinkPad X240 20AMS1J100     | 1         | 1.25%   |
| Lenovo ThinkPad T400 6475E13        | 1         | 1.25%   |
| Lenovo ThinkPad L480 20LS001AMC     | 1         | 1.25%   |
| Lenovo ThinkPad A475 20KMS08300     | 1         | 1.25%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1 | 1         | 1.25%   |
| Lenovo IdeaPad 330S-15AST 81F9      | 1         | 1.25%   |
| Lenovo IdeaPad 320-15ABR 80XS       | 1         | 1.25%   |
| Lenovo IdeaPad 100-15IBY 80MJ       | 1         | 1.25%   |
| Lenovo IdeaPad 100-14IBY 80MH       | 1         | 1.25%   |
| Lenovo 3000 V200 0764A11            | 1         | 1.25%   |
| Insignia NS-P11W7100                | 1         | 1.25%   |
| HP Stream Notebook PC 13            | 1         | 1.25%   |
| HP Presario V6000 (RG289UA#ABA)     | 1         | 1.25%   |
| HP Pavilion g4                      | 1         | 1.25%   |
| HP Pavilion dv6500                  | 1         | 1.25%   |
| HP Laptop 17-by2xxx                 | 1         | 1.25%   |
| HP Laptop 15-dw3xxx                 | 1         | 1.25%   |
| HP Laptop 15-db0xxx                 | 1         | 1.25%   |
| HP Laptop 14-cm0xxx                 | 1         | 1.25%   |
| HP EliteBook Folio 9470m            | 1         | 1.25%   |
| HP EliteBook 8440p                  | 1         | 1.25%   |
| HP EliteBook 2530p                  | 1         | 1.25%   |
| HP Compaq Presario CQ50             | 1         | 1.25%   |
| HP Compaq nw9440 (EY615ET#ABU)      | 1         | 1.25%   |
| HP Compaq CQ45                      | 1         | 1.25%   |
| HP Compaq 420                       | 1         | 1.25%   |
| HP Compaq 2510p                     | 1         | 1.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 6         | 7.5%    |
| Lenovo IdeaPad          | 5         | 6.25%   |
| HP Compaq               | 5         | 6.25%   |
| Lenovo ThinkPad         | 4         | 5%      |
| HP Laptop               | 4         | 5%      |
| HP EliteBook            | 3         | 3.75%   |
| Dell Inspiron           | 3         | 3.75%   |
| HP Pavilion             | 2         | 2.5%    |
| Dell Latitude           | 2         | 2.5%    |
| ASUS VivoBook           | 2         | 2.5%    |
| UNOWHY Y13G010S4EI      | 1         | 1.25%   |
| UMAX VisionBook         | 1         | 1.25%   |
| TR ST                   | 1         | 1.25%   |
| Toshiba Satellite       | 1         | 1.25%   |
| Toshiba QOSMIO          | 1         | 1.25%   |
| Thomson PT-NEO14A.2WH32 | 1         | 1.25%   |
| Samsung X420            | 1         | 1.25%   |
| Samsung NC110P          | 1         | 1.25%   |
| Samsung 905S3G          | 1         | 1.25%   |
| Samsung 530XBB          | 1         | 1.25%   |
| Pegatron H36FF          | 1         | 1.25%   |
| MSI MS-N014             | 1         | 1.25%   |
| Minix Z64               | 1         | 1.25%   |
| Lenovo 3000             | 1         | 1.25%   |
| Insignia NS-P11W7100    | 1         | 1.25%   |
| HP Stream               | 1         | 1.25%   |
| HP Presario             | 1         | 1.25%   |
| HP 655                  | 1         | 1.25%   |
| HP 15                   | 1         | 1.25%   |
| Google Chell            | 1         | 1.25%   |
| Gateway Sonic-C         | 1         | 1.25%   |
| Fujitsu LIFEBOOK        | 1         | 1.25%   |
| Fujitsu FMVNQ8P6        | 1         | 1.25%   |
| Dell Vostro1710         | 1         | 1.25%   |
| Dell MXG071             | 1         | 1.25%   |
| Dell MXG061             | 1         | 1.25%   |
| ASUS X751LD             | 1         | 1.25%   |
| ASUS X555YI             | 1         | 1.25%   |
| ASUS X541SA             | 1         | 1.25%   |
| ASUS X540YA             | 1         | 1.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 8         | 10%     |
| 2014 | 8         | 10%     |
| 2010 | 8         | 10%     |
| 2008 | 7         | 8.75%   |
| 2007 | 7         | 8.75%   |
| 2015 | 6         | 7.5%    |
| 2012 | 5         | 6.25%   |
| 2011 | 5         | 6.25%   |
| 2020 | 4         | 5%      |
| 2019 | 4         | 5%      |
| 2017 | 4         | 5%      |
| 2016 | 4         | 5%      |
| 2013 | 3         | 3.75%   |
| 2022 | 2         | 2.5%    |
| 2006 | 2         | 2.5%    |
| 2021 | 1         | 1.25%   |
| 2009 | 1         | 1.25%   |
| 2004 | 1         | 1.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 80        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 75        | 93.75%  |
| Enabled  | 5         | 6.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 79        | 98.75%  |
| Yes  | 1         | 1.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 32        | 40%     |
| 1.01-2.0   | 16        | 20%     |
| 4.01-8.0   | 11        | 13.75%  |
| 16.01-24.0 | 8         | 10%     |
| 8.01-16.0  | 6         | 7.5%    |
| 0.51-1.0   | 4         | 5%      |
| 2.01-3.0   | 2         | 2.5%    |
| 32.01-64.0 | 1         | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 41        | 49.4%   |
| 2.01-3.0  | 19        | 22.89%  |
| 0.51-1.0  | 12        | 14.46%  |
| 3.01-4.0  | 5         | 6.02%   |
| 0.01-0.5  | 3         | 3.61%   |
| 4.01-8.0  | 2         | 2.41%   |
| 8.01-16.0 | 1         | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 65        | 81.25%  |
| 2      | 14        | 17.5%   |
| 3      | 1         | 1.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 58.75%  |
| Yes       | 33        | 41.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 81.25%  |
| No        | 15        | 18.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 97.5%   |
| No        | 2         | 2.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 70%     |
| No        | 24        | 30%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 10        | 12.5%   |
| Germany     | 8         | 10%     |
| France      | 7         | 8.75%   |
| Romania     | 5         | 6.25%   |
| Brazil      | 5         | 6.25%   |
| Ukraine     | 4         | 5%      |
| UK          | 4         | 5%      |
| Poland      | 4         | 5%      |
| Italy       | 4         | 5%      |
| Spain       | 3         | 3.75%   |
| Russia      | 3         | 3.75%   |
| Turkey      | 2         | 2.5%    |
| Philippines | 2         | 2.5%    |
| Australia   | 2         | 2.5%    |
| Venezuela   | 1         | 1.25%   |
| Thailand    | 1         | 1.25%   |
| Slovakia    | 1         | 1.25%   |
| Serbia      | 1         | 1.25%   |
| Portugal    | 1         | 1.25%   |
| Netherlands | 1         | 1.25%   |
| Myanmar     | 1         | 1.25%   |
| Mexico      | 1         | 1.25%   |
| Iran        | 1         | 1.25%   |
| Indonesia   | 1         | 1.25%   |
| India       | 1         | 1.25%   |
| Guadeloupe  | 1         | 1.25%   |
| El Salvador | 1         | 1.25%   |
| Czechia     | 1         | 1.25%   |
| Colombia    | 1         | 1.25%   |
| Chile       | 1         | 1.25%   |
| Canada      | 1         | 1.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Sydney             | 2         | 2.41%   |
| Paris              | 2         | 2.41%   |
| Pabianice          | 2         | 2.41%   |
| Odessa             | 2         | 2.41%   |
| Frankfurt am Main  | 2         | 2.41%   |
| Żywiec            | 1         | 1.2%    |
| Yangon             | 1         | 1.2%    |
| Würzburg          | 1         | 1.2%    |
| Wiesbaden          | 1         | 1.2%    |
| Washington         | 1         | 1.2%    |
| Warsaw             | 1         | 1.2%    |
| Wahroonga          | 1         | 1.2%    |
| Voluntari          | 1         | 1.2%    |
| Vinnytsia          | 1         | 1.2%    |
| Varennes-les-Narcy | 1         | 1.2%    |
| Valencia           | 1         | 1.2%    |
| Tucape             | 1         | 1.2%    |
| Teresina           | 1         | 1.2%    |
| Tekirdağ          | 1         | 1.2%    |
| Tarragona          | 1         | 1.2%    |
| Tamm               | 1         | 1.2%    |
| Svidník           | 1         | 1.2%    |
| Surabaya           | 1         | 1.2%    |
| Subotica           | 1         | 1.2%    |
| Studenka           | 1         | 1.2%    |
| St. Petersburg     | 1         | 1.2%    |
| Shadrinsk          | 1         | 1.2%    |
| Sartrouville       | 1         | 1.2%    |
| Sao Paulo          | 1         | 1.2%    |
| Salerno            | 1         | 1.2%    |
| Sabadell           | 1         | 1.2%    |
| Roswell            | 1         | 1.2%    |
| Queretaro          | 1         | 1.2%    |
| Póvoa de Varzim   | 1         | 1.2%    |
| Paranaque City     | 1         | 1.2%    |
| Nudlingen          | 1         | 1.2%    |
| Novaci             | 1         | 1.2%    |
| Moscow             | 1         | 1.2%    |
| Milan              | 1         | 1.2%    |
| Marseille          | 1         | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 18     | 16.85%  |
| WDC                 | 12        | 16     | 13.48%  |
| Toshiba             | 10        | 11     | 11.24%  |
| Samsung Electronics | 10        | 11     | 11.24%  |
| Unknown             | 8         | 11     | 8.99%   |
| Kingston            | 5         | 5      | 5.62%   |
| HGST                | 5         | 5      | 5.62%   |
| Micron Technology   | 4         | 5      | 4.49%   |
| SK hynix            | 3         | 4      | 3.37%   |
| SanDisk             | 3         | 3      | 3.37%   |
| Hitachi             | 3         | 3      | 3.37%   |
| GOODRAM             | 2         | 2      | 2.25%   |
| Crucial             | 2         | 2      | 2.25%   |
| Apple               | 2         | 2      | 2.25%   |
| LITEON              | 1         | 1      | 1.12%   |
| Intel               | 1         | 1      | 1.12%   |
| ASUS-PHISON         | 1         | 2      | 1.12%   |
| ASMT                | 1         | 1      | 1.12%   |
| A-DATA Technology   | 1         | 1      | 1.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                | 3         | 3.23%   |
| Toshiba MQ01ABF050 500GB              | 3         | 3.23%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 3.23%   |
| Unknown DA4064  64GB                  | 2         | 2.15%   |
| Seagate ST9320325AS 320GB             | 2         | 2.15%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD   | 2         | 2.15%   |
| HGST HTS725050A7E630 500GB            | 2         | 2.15%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1.08%   |
| WDC WDS120G2G0A-00JH30 128GB SSD      | 1         | 1.08%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 1.08%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 1.08%   |
| WDC WD2500BEVS-00UST0 250GB           | 1         | 1.08%   |
| WDC WD2500BEVE-00A0HT0 250GB          | 1         | 1.08%   |
| WDC WD1600BEVT-22A23T0 160GB          | 1         | 1.08%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1.08%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1.08%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 1.08%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB  | 1         | 1.08%   |
| Unknown SN64G  64GB                   | 1         | 1.08%   |
| Unknown SLD64G  64GB                  | 1         | 1.08%   |
| Unknown SD64G  64GB                   | 1         | 1.08%   |
| Unknown SD16G  16GB                   | 1         | 1.08%   |
| Unknown NCard  32GB                   | 1         | 1.08%   |
| Unknown MMC Card  128GB               | 1         | 1.08%   |
| Toshiba THNSNJ128GCSU 128GB SSD       | 1         | 1.08%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1.08%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1.08%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1.08%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 1.08%   |
| Toshiba MK3265GSX 320GB               | 1         | 1.08%   |
| Toshiba MK1011GAH 100GB               | 1         | 1.08%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1.08%   |
| SK hynix HFM128GDHTNG-8310A 128GB     | 1         | 1.08%   |
| SK hynix HBG4e  32GB                  | 1         | 1.08%   |
| Seagate ST95005620AS 500GB            | 1         | 1.08%   |
| Seagate ST9500423AS 500GB             | 1         | 1.08%   |
| Seagate ST9320320AS 320GB             | 1         | 1.08%   |
| Seagate ST9160823ASG 160GB            | 1         | 1.08%   |
| Seagate ST9160301AS 160GB             | 1         | 1.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 18     | 36.59%  |
| Toshiba             | 9         | 10     | 21.95%  |
| WDC                 | 7         | 10     | 17.07%  |
| HGST                | 5         | 5      | 12.2%   |
| Hitachi             | 3         | 3      | 7.32%   |
| Samsung Electronics | 2         | 3      | 4.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 4      | 14.29%  |
| WDC                 | 3         | 3      | 10.71%  |
| Samsung Electronics | 3         | 3      | 10.71%  |
| Micron Technology   | 3         | 4      | 10.71%  |
| SanDisk             | 2         | 2      | 7.14%   |
| GOODRAM             | 2         | 2      | 7.14%   |
| Crucial             | 2         | 2      | 7.14%   |
| Apple               | 2         | 2      | 7.14%   |
| Toshiba             | 1         | 1      | 3.57%   |
| SK hynix            | 1         | 2      | 3.57%   |
| LITEON              | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| ASUS-PHISON         | 1         | 2      | 3.57%   |
| ASMT                | 1         | 1      | 3.57%   |
| A-DATA Technology   | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 49     | 47.13%  |
| SSD  | 27        | 31     | 31.03%  |
| MMC  | 10        | 13     | 11.49%  |
| NVMe | 9         | 11     | 10.34%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 62        | 78     | 74.7%   |
| MMC  | 10        | 13     | 12.05%  |
| NVMe | 9         | 11     | 10.84%  |
| SAS  | 2         | 2      | 2.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 65     | 77.27%  |
| 0.51-1.0   | 14        | 14     | 21.21%  |
| 1.01-2.0   | 1         | 1      | 1.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 37.8%   |
| 251-500        | 19        | 23.17%  |
| 51-100         | 13        | 15.85%  |
| 1-20           | 7         | 8.54%   |
| 501-1000       | 6         | 7.32%   |
| 21-50          | 5         | 6.1%    |
| More than 3000 | 1         | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 44        | 53.01%  |
| 21-50     | 20        | 24.1%   |
| 51-100    | 11        | 13.25%  |
| 101-250   | 7         | 8.43%   |
| 2001-3000 | 1         | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 5.88%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 5.88%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 5.88%   |
| Toshiba MK3265GSX 320GB                        | 1         | 1      | 5.88%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 5.88%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 5.88%   |
| Seagate ST9320320AS 320GB                      | 1         | 1      | 5.88%   |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 5.88%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 5.88%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 5.88%   |
| SanDisk SSD PLUS 120GB                         | 1         | 1      | 5.88%   |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 5.88%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 5.88%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 5.88%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 5.88%   |
| Apple SSD SM128C 121GB                         | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 35.29%  |
| WDC                 | 3         | 3      | 17.65%  |
| Toshiba             | 2         | 2      | 11.76%  |
| SanDisk             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |
| Hitachi             | 1         | 1      | 5.88%   |
| HGST                | 1         | 1      | 5.88%   |
| Apple               | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 46.15%  |
| WDC                 | 2         | 2      | 15.38%  |
| Toshiba             | 2         | 2      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 76.47%  |
| SSD  | 4         | 4      | 23.53%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 33        | 49     | 40.24%  |
| Works    | 33        | 38     | 40.24%  |
| Malfunc  | 16        | 17     | 19.51%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 57        | 69.51%  |
| AMD                         | 11        | 13.41%  |
| Samsung Electronics         | 5         | 6.1%    |
| Nvidia                      | 3         | 3.66%   |
| SanDisk                     | 2         | 2.44%   |
| SK hynix                    | 1         | 1.22%   |
| Micron Technology           | 1         | 1.22%   |
| Marvell Technology Group    | 1         | 1.22%   |
| Kingston Technology Company | 1         | 1.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 10.2%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 7.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 5.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 4.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 4.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 4.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 3.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 3.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 3.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 3.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 3.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 2.04%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.04%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 2.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 2.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 2.04%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 2.04%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 1.02%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.02%   |
| SanDisk PC SN530 NVMe SSD                                                        | 1         | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.02%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.02%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 1.02%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 1.02%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.02%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.02%   |
| Micron NVMe Storage Controller                                                   | 1         | 1.02%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 1.02%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.02%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 1.02%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.02%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 60        | 65.93%  |
| IDE  | 16        | 17.58%  |
| NVMe | 9         | 9.89%   |
| RAID | 6         | 6.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 67        | 83.75%  |
| AMD    | 13        | 16.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 2.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.5%    |
| Intel Core 2 CPU T7600 @ 2.33GHz              | 2         | 2.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 2.5%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 2.5%    |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 2.5%    |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 2.5%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 1.25%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.25%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 1.25%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 1.25%   |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 1.25%   |
| Intel Genuine CPU T2050 @ 1.60GHz             | 1         | 1.25%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz              | 1         | 1.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.25%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.25%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.25%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 1.25%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 1.25%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 1.25%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.25%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 1.25%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.25%   |
| Intel Core i5-3427U CPU @ 1.80GHz             | 1         | 1.25%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.25%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.25%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 1         | 1.25%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.25%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.25%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 1.25%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.25%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 1.25%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.25%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 1.25%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.25%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 1.25%   |
| Intel Core 2 Duo CPU U7600 @ 1.20GHz          | 1         | 1.25%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz          | 1         | 1.25%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 13        | 16.25%  |
| Intel Core 2 Duo        | 10        | 12.5%   |
| Intel Celeron           | 8         | 10%     |
| Intel Core i7           | 7         | 8.75%   |
| Intel Atom              | 7         | 8.75%   |
| Other                   | 5         | 6.25%   |
| Intel Pentium           | 5         | 6.25%   |
| Intel Core i3           | 5         | 6.25%   |
| Intel Core 2            | 3         | 3.75%   |
| AMD E2                  | 3         | 3.75%   |
| Intel Genuine           | 2         | 2.5%    |
| AMD A8                  | 2         | 2.5%    |
| Intel Pentium Dual-Core | 1         | 1.25%   |
| Intel Core m7           | 1         | 1.25%   |
| Intel Celeron M         | 1         | 1.25%   |
| AMD Turion Dual-Core    | 1         | 1.25%   |
| AMD Turion 64 X2 Mobile | 1         | 1.25%   |
| AMD Quad-Core           | 1         | 1.25%   |
| AMD Athlon II Neo       | 1         | 1.25%   |
| AMD A6                  | 1         | 1.25%   |
| AMD A12                 | 1         | 1.25%   |
| AMD A10                 | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 50        | 62.5%   |
| 4      | 22        | 27.5%   |
| 1      | 5         | 6.25%   |
| 14     | 1         | 1.25%   |
| 10     | 1         | 1.25%   |
| 6      | 1         | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 80        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 55%     |
| 2      | 36        | 45%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 78        | 97.5%   |
| 32-bit         | 2         | 2.5%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 11.11%  |
| 0x30678    | 6         | 7.41%   |
| 0x206a7    | 6         | 7.41%   |
| 0x1067a    | 5         | 6.17%   |
| 0x40651    | 4         | 4.94%   |
| 0x6fd      | 3         | 3.7%    |
| 0x306a9    | 3         | 3.7%    |
| 0x20655    | 3         | 3.7%    |
| 0x06006705 | 3         | 3.7%    |
| 0x806ea    | 2         | 2.47%   |
| 0x806e9    | 2         | 2.47%   |
| 0x806c1    | 2         | 2.47%   |
| 0x706a1    | 2         | 2.47%   |
| 0x6fb      | 2         | 2.47%   |
| 0x6f6      | 2         | 2.47%   |
| 0x406c4    | 2         | 2.47%   |
| 0x406c3    | 2         | 2.47%   |
| 0x306c3    | 2         | 2.47%   |
| 0x106ca    | 2         | 2.47%   |
| 0x10676    | 2         | 2.47%   |
| 0x906ea    | 1         | 1.23%   |
| 0x906e9    | 1         | 1.23%   |
| 0x906a4    | 1         | 1.23%   |
| 0x906a3    | 1         | 1.23%   |
| 0x806ec    | 1         | 1.23%   |
| 0x806eb    | 1         | 1.23%   |
| 0x6d8      | 1         | 1.23%   |
| 0x506e3    | 1         | 1.23%   |
| 0x506c9    | 1         | 1.23%   |
| 0x406e3    | 1         | 1.23%   |
| 0x30661    | 1         | 1.23%   |
| 0x07030105 | 1         | 1.23%   |
| 0x06006118 | 1         | 1.23%   |
| 0x06001119 | 1         | 1.23%   |
| 0x05000119 | 1         | 1.23%   |
| 0x02000057 | 1         | 1.23%   |
| 0x010000c8 | 1         | 1.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Silvermont       | 11        | 13.75%  |
| Penryn           | 8         | 10%     |
| KabyLake         | 8         | 10%     |
| Core             | 8         | 10%     |
| SandyBridge      | 6         | 7.5%    |
| Haswell          | 6         | 7.5%    |
| Excavator        | 5         | 6.25%   |
| Westmere         | 3         | 3.75%   |
| IvyBridge        | 3         | 3.75%   |
| Bonnell          | 3         | 3.75%   |
| TigerLake        | 2         | 2.5%    |
| Skylake          | 2         | 2.5%    |
| Puma             | 2         | 2.5%    |
| P6               | 2         | 2.5%    |
| Goldmont plus    | 2         | 2.5%    |
| Alderlake Hybrid | 2         | 2.5%    |
| Piledriver       | 1         | 1.25%   |
| K8 Hammer        | 1         | 1.25%   |
| K8 & K10 hybrid  | 1         | 1.25%   |
| K10              | 1         | 1.25%   |
| Jaguar           | 1         | 1.25%   |
| Goldmont         | 1         | 1.25%   |
| Bobcat           | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 64.84%  |
| Nvidia | 19        | 20.88%  |
| AMD    | 13        | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 6.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 5.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 5.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 5.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 5.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 4.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.06%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 3.06%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.04%   |
| Intel HD Graphics 620                                                                    | 2         | 2.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.04%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.04%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 2.04%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.04%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.02%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.02%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.02%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.02%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.02%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 1.02%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 1.02%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.02%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 1.02%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 1.02%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.02%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 1.02%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 1.02%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 1.02%   |
| Nvidia G71M [GeForce Go 7950 GTX]                                                        | 1         | 1.02%   |
| Nvidia G71GLM [Quadro FX 1500M]                                                          | 1         | 1.02%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 1         | 1.02%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 1.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.02%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.02%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 60%     |
| 1 x AMD        | 11        | 13.75%  |
| Intel + Nvidia | 10        | 12.5%   |
| 1 x Nvidia     | 9         | 11.25%  |
| 2 x AMD        | 1         | 1.25%   |
| Intel + AMD    | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 71        | 87.65%  |
| Proprietary | 9         | 11.11%  |
| Unknown     | 1         | 1.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 70%     |
| 0.01-0.5   | 14        | 17.5%   |
| 0.51-1.0   | 4         | 5%      |
| 3.01-4.0   | 3         | 3.75%   |
| 1.01-2.0   | 2         | 2.5%    |
| 5.01-6.0   | 1         | 1.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 15.48%  |
| Samsung Electronics     | 11        | 13.1%   |
| LG Display              | 11        | 13.1%   |
| Chimei Innolux          | 11        | 13.1%   |
| BOE                     | 8         | 9.52%   |
| Chi Mei Optoelectronics | 7         | 8.33%   |
| PANDA                   | 2         | 2.38%   |
| LG Philips              | 2         | 2.38%   |
| InfoVision              | 2         | 2.38%   |
| HannStar                | 2         | 2.38%   |
| Goldstar                | 2         | 2.38%   |
| CPT                     | 2         | 2.38%   |
| Apple                   | 2         | 2.38%   |
| Sony                    | 1         | 1.19%   |
| Seiko/Epson             | 1         | 1.19%   |
| SANYO                   | 1         | 1.19%   |
| OEM                     | 1         | 1.19%   |
| Lenovo                  | 1         | 1.19%   |
| eMachines               | 1         | 1.19%   |
| BenQ                    | 1         | 1.19%   |
| Belinea                 | 1         | 1.19%   |
| Unknown                 | 1         | 1.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch              | 2         | 2.38%   |
| Sony TV *00 SNY8004 3840x2160 1085x610mm 49.0-inch                    | 1         | 1.19%   |
| Seiko/Epson LCD Monitor                                               | 1         | 1.19%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 1.19%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1         | 1.19%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 1.19%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 1.19%   |
| OEM 26_LCD_TV OEM3700 1920x1080                                       | 1         | 1.19%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch           | 1         | 1.19%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD03E3 1366x768 310x174mm 14.0-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD038C 1366x768 256x144mm 11.6-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 1         | 1.19%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 1         | 1.19%   |
| InfoVision LCD Monitor IVO057C 1366x768 309x174mm 14.0-inch           | 1         | 1.19%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 1         | 1.19%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                  | 1         | 1.19%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                 | 1         | 1.19%   |
| eMachines E190HQV EMA0212 1366x768 409x230mm 18.5-inch                | 1         | 1.19%   |
| CPT LCD Monitor CPT14BF 1366x768 344x193mm 15.5-inch                  | 1         | 1.19%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                  | 1         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1737 1920x1080 381x214mm 17.2-inch      | 1         | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 37        | 44.05%  |
| 1920x1080 (FHD)    | 20        | 23.81%  |
| 1280x800 (WXGA)    | 8         | 9.52%   |
| 1920x1200 (WUXGA)  | 6         | 7.14%   |
| 3840x2160 (4K)     | 2         | 2.38%   |
| 1600x900 (HD+)     | 2         | 2.38%   |
| 1024x600           | 2         | 2.38%   |
| 3840x2400          | 1         | 1.19%   |
| 1920x540           | 1         | 1.19%   |
| 1680x1050 (WSXGA+) | 1         | 1.19%   |
| 1440x900 (WXGA+)   | 1         | 1.19%   |
| 1360x768           | 1         | 1.19%   |
| 1280x1024 (SXGA)   | 1         | 1.19%   |
| Unknown            | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 27        | 32.14%  |
| 14      | 11        | 13.1%   |
| 13      | 11        | 13.1%   |
| 17      | 9         | 10.71%  |
| 11      | 6         | 7.14%   |
| 12      | 4         | 4.76%   |
| 16      | 3         | 3.57%   |
| Unknown | 3         | 3.57%   |
| 24      | 2         | 2.38%   |
| 21      | 2         | 2.38%   |
| 10      | 2         | 2.38%   |
| 65      | 1         | 1.19%   |
| 46      | 1         | 1.19%   |
| 23      | 1         | 1.19%   |
| 19      | 1         | 1.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 55.42%  |
| 201-300     | 16        | 19.28%  |
| 351-400     | 10        | 12.05%  |
| 501-600     | 3         | 3.61%   |
| 401-500     | 3         | 3.61%   |
| Unknown     | 3         | 3.61%   |
| 1001-1500   | 2         | 2.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 61        | 76.25%  |
| 16/10   | 15        | 18.75%  |
| Unknown | 2         | 2.5%    |
| 6/5     | 1         | 1.25%   |
| 3/2     | 1         | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 32.14%  |
| 81-90          | 18        | 21.43%  |
| 51-60          | 6         | 7.14%   |
| 121-130        | 6         | 7.14%   |
| 131-140        | 5         | 5.95%   |
| 71-80          | 4         | 4.76%   |
| 61-70          | 4         | 4.76%   |
| 201-250        | 4         | 4.76%   |
| Unknown        | 3         | 3.57%   |
| 41-50          | 2         | 2.38%   |
| More than 1000 | 1         | 1.19%   |
| 251-300        | 1         | 1.19%   |
| 151-200        | 1         | 1.19%   |
| 111-120        | 1         | 1.19%   |
| 501-1000       | 1         | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 33        | 40.24%  |
| 121-160       | 27        | 32.93%  |
| 51-100        | 13        | 15.85%  |
| 161-240       | 3         | 3.66%   |
| Unknown       | 3         | 3.66%   |
| More than 240 | 2         | 2.44%   |
| 1-50          | 1         | 1.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 73        | 90.12%  |
| 2     | 8         | 9.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 42        | 35%     |
| Intel                 | 32        | 26.67%  |
| Qualcomm Atheros      | 23        | 19.17%  |
| Broadcom              | 10        | 8.33%   |
| Broadcom Limited      | 4         | 3.33%   |
| Sierra Wireless       | 2         | 1.67%   |
| Ralink                | 2         | 1.67%   |
| Nvidia                | 2         | 1.67%   |
| Ralink Technology     | 1         | 0.83%   |
| D-Link                | 1         | 0.83%   |
| ASIX Electronics      | 1         | 0.83%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 21        | 14%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 13        | 8.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 4%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5         | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 3.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 2.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 2.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 3         | 2%      |
| Intel Wireless 3165                                                                           | 3         | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 3         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 2         | 1.33%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.33%   |
| Intel Wireless 7260                                                                           | 2         | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.33%   |
| Intel 82567LM Gigabit Network Connection                                                      | 2         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.33%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 1.33%   |
| Sierra Wireless EM7455                                                                        | 1         | 0.67%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.67%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.67%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 0.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1         | 0.67%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                                              | 1         | 0.67%   |
| Realtek 802.11ac NIC                                                                          | 1         | 0.67%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.67%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 0.67%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                    | 1         | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 36.14%  |
| Qualcomm Atheros      | 21        | 25.3%   |
| Realtek Semiconductor | 19        | 22.89%  |
| Broadcom              | 5         | 6.02%   |
| Sierra Wireless       | 2         | 2.41%   |
| Ralink                | 2         | 2.41%   |
| Broadcom Limited      | 2         | 2.41%   |
| Ralink Technology     | 1         | 1.2%    |
| D-Link                | 1         | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 7.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5         | 5.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 5.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 4.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 4.76%   |
| Intel Wireless 3165                                                                           | 3         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 2.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 2         | 2.38%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 2.38%   |
| Intel Wireless 7260                                                                           | 2         | 2.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.38%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 2.38%   |
| Sierra Wireless EM7455                                                                        | 1         | 1.19%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 1.19%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.19%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1.19%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 1.19%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 1.19%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.19%   |
| Realtek 802.11ac NIC                                                                          | 1         | 1.19%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.19%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 1.19%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 1.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 1.19%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.19%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 1.19%   |
| Intel Wireless 7265                                                                           | 1         | 1.19%   |
| Intel Wireless 3160                                                                           | 1         | 1.19%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.19%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.19%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 1         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 37        | 56.92%  |
| Intel                 | 11        | 16.92%  |
| Qualcomm Atheros      | 7         | 10.77%  |
| Broadcom              | 5         | 7.69%   |
| Nvidia                | 2         | 3.08%   |
| Broadcom Limited      | 2         | 3.08%   |
| ASIX Electronics      | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 31.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 19.7%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.55%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 3.03%   |
| Realtek USB 10/100 LAN                                            | 1         | 1.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.52%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.52%   |
| Nvidia MCP77 Ethernet                                             | 1         | 1.52%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 1.52%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.52%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.52%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.52%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.52%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.52%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express          | 1         | 1.52%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.52%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.52%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.52%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 1.52%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express  | 1         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 54.55%  |
| Ethernet | 65        | 45.45%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 77.38%  |
| Ethernet | 19        | 22.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 62        | 77.5%   |
| 1     | 15        | 18.75%  |
| 0     | 3         | 3.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 77.78%  |
| Yes  | 18        | 22.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 30.36%  |
| Realtek Semiconductor           | 11        | 19.64%  |
| Hewlett-Packard                 | 5         | 8.93%   |
| IMC Networks                    | 4         | 7.14%   |
| Qualcomm Atheros Communications | 3         | 5.36%   |
| Lite-On Technology              | 3         | 5.36%   |
| Broadcom                        | 3         | 5.36%   |
| Dell                            | 2         | 3.57%   |
| Chicony Electronics             | 2         | 3.57%   |
| Apple                           | 2         | 3.57%   |
| Toshiba                         | 1         | 1.79%   |
| Ralink                          | 1         | 1.79%   |
| Foxconn / Hon Hai               | 1         | 1.79%   |
| ASUSTek Computer                | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 9         | 16.07%  |
| Realtek Bluetooth Radio                          | 6         | 10.71%  |
| Realtek  Bluetooth 4.2 Adapter                   | 3         | 5.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 3         | 5.36%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 3         | 5.36%   |
| Intel AX201 Bluetooth                            | 2         | 3.57%   |
| IMC Networks Bluetooth Device                    | 2         | 3.57%   |
| HP Broadcom 2070 Bluetooth Combo                 | 2         | 3.57%   |
| Dell Wireless 355 Bluetooth                      | 2         | 3.57%   |
| Chicony Bluetooth (RTL8723BE)                    | 2         | 3.57%   |
| Broadcom BCM2045 Bluetooth                       | 2         | 3.57%   |
| Toshiba Askey Bluetooth Module                   | 1         | 1.79%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter          | 1         | 1.79%   |
| Realtek RTL8821A Bluetooth                       | 1         | 1.79%   |
| Ralink RT3290 Bluetooth                          | 1         | 1.79%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth                | 1         | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 1.79%   |
| Lite-On Bluetooth Device                         | 1         | 1.79%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 1.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 1.79%   |
| Intel Bluetooth Device                           | 1         | 1.79%   |
| IMC Networks Bluetooth USB Host Controller       | 1         | 1.79%   |
| IMC Networks Bluetooth Radio                     | 1         | 1.79%   |
| Foxconn / Hon Hai BCM20702A0                     | 1         | 1.79%   |
| Broadcom HP Portable Valentine                   | 1         | 1.79%   |
| ASUS BT-270 Bluetooth Adapter                    | 1         | 1.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI             | 1         | 1.79%   |
| Apple Bluetooth USB Host Controller              | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 62        | 72.09%  |
| AMD              | 12        | 13.95%  |
| Nvidia           | 10        | 11.63%  |
| Logitech         | 1         | 1.16%   |
| Blue Microphones | 1         | 1.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 6.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 6.73%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 4.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 4.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 4.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 4.81%   |
| AMD FCH Azalia Controller                                                                         | 5         | 4.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 4.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.85%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 3.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.88%   |
| AMD High Definition Audio Controller                                                              | 3         | 2.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.92%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.92%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.96%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.96%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.96%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.96%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.96%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.96%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.96%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.96%   |
| Nvidia Audio device                                                                               | 1         | 0.96%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.96%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.96%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.96%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.96%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 25.33%  |
| SK hynix            | 15        | 20%     |
| Unknown             | 8         | 10.67%  |
| Micron Technology   | 7         | 9.33%   |
| Kingston            | 7         | 9.33%   |
| Nanya Technology    | 3         | 4%      |
| Elpida              | 3         | 4%      |
| A-DATA Technology   | 3         | 4%      |
| Unknown             | 3         | 4%      |
| Unknown (ABCD)      | 2         | 2.67%   |
| Ramaxel Technology  | 2         | 2.67%   |
| Transcend           | 1         | 1.33%   |
| Qimonda             | 1         | 1.33%   |
| G.Skill             | 1         | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 3.85%   |
| Unknown                                                          | 3         | 3.85%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 2.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.56%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 2.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.56%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 1.28%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 1.28%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.28%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.28%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                            | 1         | 1.28%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                   | 1         | 1.28%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 1.28%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                    | 1         | 1.28%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s               | 1         | 1.28%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.28%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 1.28%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 1         | 1.28%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 1.28%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 1.28%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s             | 1         | 1.28%   |
| SK hynix RAM HMP125S6EFR8C-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 1.28%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.28%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.28%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.28%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.28%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 43.08%  |
| DDR4    | 14        | 21.54%  |
| DDR2    | 11        | 16.92%  |
| SDRAM   | 4         | 6.15%   |
| LPDDR4  | 4         | 6.15%   |
| Unknown | 2         | 3.08%   |
| DRAM    | 1         | 1.54%   |
| DDR     | 1         | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 61        | 98.39%  |
| DIMM   | 1         | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 24        | 33.8%   |
| 4096  | 22        | 30.99%  |
| 8192  | 14        | 19.72%  |
| 1024  | 9         | 12.68%  |
| 16384 | 2         | 2.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 23        | 33.82%  |
| 667     | 8         | 11.76%  |
| 2667    | 7         | 10.29%  |
| 3200    | 5         | 7.35%   |
| 3266    | 3         | 4.41%   |
| 2400    | 3         | 4.41%   |
| 1333    | 3         | 4.41%   |
| 975     | 3         | 4.41%   |
| 4199    | 2         | 2.94%   |
| 2048    | 2         | 2.94%   |
| 1334    | 2         | 2.94%   |
| 1066    | 2         | 2.94%   |
| 800     | 2         | 2.94%   |
| 1866    | 1         | 1.47%   |
| 400     | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

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

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 17        | 26.56%  |
| Quanta                                 | 6         | 9.38%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 9.38%   |
| Suyin                                  | 5         | 7.81%   |
| IMC Networks                           | 4         | 6.25%   |
| Alcor Micro                            | 4         | 6.25%   |
| Syntek                                 | 3         | 4.69%   |
| Silicon Motion                         | 3         | 4.69%   |
| Apple                                  | 3         | 4.69%   |
| Sunplus Innovation Technology          | 2         | 3.13%   |
| Realtek Semiconductor                  | 2         | 3.13%   |
| Microdia                               | 2         | 3.13%   |
| Lite-On Technology                     | 2         | 3.13%   |
| Z-Star Microelectronics                | 1         | 1.56%   |
| Pixart Imaging                         | 1         | 1.56%   |
| OmniVision Technologies                | 1         | 1.56%   |
| Logitech                               | 1         | 1.56%   |
| Aveo Technology                        | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                    | 5         | 7.81%   |
| Chicony Integrated Camera                        | 3         | 4.69%   |
| Syntek Lenovo EasyCamera                         | 2         | 3.13%   |
| Suyin HP TrueVision HD Integrated Webcam         | 2         | 3.13%   |
| Quanta HP TrueVision HD Camera                   | 2         | 3.13%   |
| Chicony FJ Camera                                | 2         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 3.13%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 2         | 3.13%   |
| Alcor Micro USB 2.0 Camera                       | 2         | 3.13%   |
| Z-Star Webcam                                    | 1         | 1.56%   |
| Syntek USB Video Device                          | 1         | 1.56%   |
| Suyin USB 2.0 Camera                             | 1         | 1.56%   |
| Suyin Integrated_Webcam_HD                       | 1         | 1.56%   |
| Suyin Acer/Lenovo Webcam [CN0316]                | 1         | 1.56%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 1.56%   |
| Sunplus HD WebCam                                | 1         | 1.56%   |
| Silicon Motion WebCam SC-10HDD13335N             | 1         | 1.56%   |
| Silicon Motion WebCam SC-0311139N                | 1         | 1.56%   |
| Silicon Motion Web Camera                        | 1         | 1.56%   |
| Realtek USB2.0 HD UVC WebCam                     | 1         | 1.56%   |
| Realtek USB Camera                               | 1         | 1.56%   |
| Quanta VGA WebCam                                | 1         | 1.56%   |
| Quanta HP Truevision HD                          | 1         | 1.56%   |
| Quanta HD Webcam                                 | 1         | 1.56%   |
| Quanta ACER HD User Facing                       | 1         | 1.56%   |
| Pixart Imaging USB_2.0_Webcam                    | 1         | 1.56%   |
| OmniVision OV2640 Webcam                         | 1         | 1.56%   |
| Microdia Sonix USB 2.0 Camera                    | 1         | 1.56%   |
| Microdia Integrated_Webcam_FHD                   | 1         | 1.56%   |
| Logitech HD Webcam C615                          | 1         | 1.56%   |
| Lite-On Integrated Camera                        | 1         | 1.56%   |
| Lite-On HP Webcam                                | 1         | 1.56%   |
| IMC Networks USB2.0 UVC VGA WebCam               | 1         | 1.56%   |
| IMC Networks Integrated Camera                   | 1         | 1.56%   |
| IMC Networks EasyCamera                          | 1         | 1.56%   |
| IMC Networks 2M Integrated Webcam                | 1         | 1.56%   |
| Chicony VGA Webcam                               | 1         | 1.56%   |
| Chicony USB 2.0 Camera                           | 1         | 1.56%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 1.56%   |
| Chicony HP Laptop Integrated Webcam [2 MP Fixed] | 1         | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
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


| Model                                            | Notebooks | Percent |
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


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| O2 Micro Oz776 SmartCard Reader                | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 54        | 66.67%  |
| 1     | 21        | 25.93%  |
| 2     | 6         | 7.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 27.27%  |
| Net/wireless             | 5         | 15.15%  |
| Graphics card            | 5         | 15.15%  |
| Chipcard                 | 3         | 9.09%   |
| Storage                  | 2         | 6.06%   |
| Multimedia controller    | 2         | 6.06%   |
| Bluetooth                | 2         | 6.06%   |
| Sound                    | 1         | 3.03%   |
| Net/ethernet             | 1         | 3.03%   |
| Dvb card                 | 1         | 3.03%   |
| Communication controller | 1         | 3.03%   |
| Camera                   | 1         | 3.03%   |

