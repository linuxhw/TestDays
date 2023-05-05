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

Total: 108

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Linux Lite 6.0 | 13        | 16.67%  |
| Linux Lite 5.8 | 12        | 15.38%  |
| Linux Lite 6.2 | 11        | 14.1%   |
| Linux Lite 5.4 | 9         | 11.54%  |
| Linux Lite 5.2 | 9         | 11.54%  |
| Linux Lite 5.0 | 8         | 10.26%  |
| Linux Lite 5.6 | 7         | 8.97%   |
| Linux Lite 3.8 | 3         | 3.85%   |
| Linux Lite 6.4 | 2         | 2.56%   |
| Linux Lite 4.8 | 2         | 2.56%   |
| Linux Lite 4.4 | 1         | 1.28%   |
| Linux Lite 4.2 | 1         | 1.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Linux Lite | 76        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.4.0-40-generic      | 4         | 4.76%   |
| 5.15.0-69-generic     | 4         | 4.76%   |
| 5.4.0-70-generic      | 3         | 3.57%   |
| 5.4.0-52-generic      | 3         | 3.57%   |
| 5.4.0-109-generic     | 3         | 3.57%   |
| 5.15.0-33-generic     | 3         | 3.57%   |
| 5.4.0-90-generic      | 2         | 2.38%   |
| 5.4.0-81-generic      | 2         | 2.38%   |
| 5.4.0-74-generic      | 2         | 2.38%   |
| 5.4.0-58-generic      | 2         | 2.38%   |
| 5.4.0-42-generic      | 2         | 2.38%   |
| 5.4.0-107-generic     | 2         | 2.38%   |
| 5.4.0-104-generic     | 2         | 2.38%   |
| 5.15.0-60-generic     | 2         | 2.38%   |
| 5.15.0-56-generic     | 2         | 2.38%   |
| 5.15.0-52-generic     | 2         | 2.38%   |
| 5.15.0-48-generic     | 2         | 2.38%   |
| 5.15.0-47-generic     | 2         | 2.38%   |
| 6.1.0-1.linuxlite     | 1         | 1.19%   |
| 6.0.0                 | 1         | 1.19%   |
| 5.4.0-96-generic      | 1         | 1.19%   |
| 5.4.0-94-generic      | 1         | 1.19%   |
| 5.4.0-91-generic      | 1         | 1.19%   |
| 5.4.0-88-generic      | 1         | 1.19%   |
| 5.4.0-77-generic      | 1         | 1.19%   |
| 5.4.0-71-generic      | 1         | 1.19%   |
| 5.4.0-66-generic      | 1         | 1.19%   |
| 5.4.0-65-generic      | 1         | 1.19%   |
| 5.4.0-56-generic      | 1         | 1.19%   |
| 5.4.0-48-generic      | 1         | 1.19%   |
| 5.4.0-33-generic      | 1         | 1.19%   |
| 5.4.0-124-generic     | 1         | 1.19%   |
| 5.4.0-122-generic     | 1         | 1.19%   |
| 5.4.0-113-generic     | 1         | 1.19%   |
| 5.4.0-110-generic     | 1         | 1.19%   |
| 5.4.0-105-generic     | 1         | 1.19%   |
| 5.4.0-100-generic     | 1         | 1.19%   |
| 5.19.0-051900-generic | 1         | 1.19%   |
| 5.16.0                | 1         | 1.19%   |
| 5.15.0-71-generic     | 1         | 1.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 43        | 54.43%  |
| 5.15.0  | 24        | 30.38%  |
| 4.15.0  | 4         | 5.06%   |
| 4.4.0   | 2         | 2.53%   |
| 6.1.0   | 1         | 1.27%   |
| 6.0.0   | 1         | 1.27%   |
| 5.19.0  | 1         | 1.27%   |
| 5.16.0  | 1         | 1.27%   |
| 5.13.0  | 1         | 1.27%   |
| 5.10.0  | 1         | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 43        | 54.43%  |
| 5.15    | 24        | 30.38%  |
| 4.15    | 4         | 5.06%   |
| 4.4     | 2         | 2.53%   |
| 6.1     | 1         | 1.27%   |
| 6.0     | 1         | 1.27%   |
| 5.19    | 1         | 1.27%   |
| 5.16    | 1         | 1.27%   |
| 5.13    | 1         | 1.27%   |
| 5.10    | 1         | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 74        | 97.37%  |
| i686   | 2         | 2.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 61        | 80.26%  |
| GNOME   | 12        | 15.79%  |
| Unknown | 2         | 2.63%   |
| Deepin  | 1         | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 74        | 97.37%  |
| Tty     | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 49        | 62.82%  |
| TDM     | 15        | 19.23%  |
| Unknown | 13        | 16.67%  |
| GDM     | 1         | 1.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 44        | 57.89%  |
| pl_PL | 5         | 6.58%   |
| de_DE | 5         | 6.58%   |
| fr_FR | 4         | 5.26%   |
| en_GB | 3         | 3.95%   |
| ru_UA | 2         | 2.63%   |
| ru_RU | 2         | 2.63%   |
| pt_BR | 2         | 2.63%   |
| it_IT | 2         | 2.63%   |
| es_ES | 2         | 2.63%   |
| zh_CN | 1         | 1.32%   |
| pt_PT | 1         | 1.32%   |
| es_CO | 1         | 1.32%   |
| en_PH | 1         | 1.32%   |
| en_AU | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 40        | 52.63%  |
| BIOS | 36        | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 66        | 86.84%  |
| Overlay | 7         | 9.21%   |
| Btrfs   | 2         | 2.63%   |
| Zfs     | 1         | 1.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 35        | 46.05%  |
| Unknown | 24        | 31.58%  |
| MBR     | 17        | 22.37%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 85.71%  |
| Yes       | 11        | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 68.83%  |
| Yes       | 24        | 31.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 17        | 22.37%  |
| ASUSTek Computer    | 14        | 18.42%  |
| Acer                | 10        | 13.16%  |
| Lenovo              | 9         | 11.84%  |
| Dell                | 7         | 9.21%   |
| Samsung Electronics | 4         | 5.26%   |
| Toshiba             | 2         | 2.63%   |
| Fujitsu             | 2         | 2.63%   |
| Apple               | 2         | 2.63%   |
| UMAX                | 1         | 1.32%   |
| TR                  | 1         | 1.32%   |
| Thomson             | 1         | 1.32%   |
| Pegatron            | 1         | 1.32%   |
| MSI                 | 1         | 1.32%   |
| Minix               | 1         | 1.32%   |
| Insignia            | 1         | 1.32%   |
| Google              | 1         | 1.32%   |
| Gateway             | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| UMAX VisionBook 12Wi 64G            | 1         | 1.32%   |
| TR ST Pro-KN                        | 1         | 1.32%   |
| Toshiba Satellite T215D             | 1         | 1.32%   |
| Toshiba QOSMIO X70-B                | 1         | 1.32%   |
| Thomson PT-NEO14A.2WH32             | 1         | 1.32%   |
| Samsung X420/X520                   | 1         | 1.32%   |
| Samsung NC110P/NC108P/NC111P        | 1         | 1.32%   |
| Samsung 905S3G/906S3G/915S3G/9305SG | 1         | 1.32%   |
| Samsung 530XBB                      | 1         | 1.32%   |
| Pegatron H36FF                      | 1         | 1.32%   |
| MSI MS-N014                         | 1         | 1.32%   |
| Minix Z64                           | 1         | 1.32%   |
| Lenovo ThinkPad T400 6475E13        | 1         | 1.32%   |
| Lenovo ThinkPad L480 20LS001AMC     | 1         | 1.32%   |
| Lenovo ThinkPad A475 20KMS08300     | 1         | 1.32%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1 | 1         | 1.32%   |
| Lenovo IdeaPad 330S-15AST 81F9      | 1         | 1.32%   |
| Lenovo IdeaPad 320-15ABR 80XS       | 1         | 1.32%   |
| Lenovo IdeaPad 100-15IBY 80MJ       | 1         | 1.32%   |
| Lenovo IdeaPad 100-14IBY 80MH       | 1         | 1.32%   |
| Lenovo 3000 V200 0764A11            | 1         | 1.32%   |
| Insignia NS-P11W7100                | 1         | 1.32%   |
| HP Stream Notebook PC 13            | 1         | 1.32%   |
| HP Presario V6000 (RG289UA#ABA)     | 1         | 1.32%   |
| HP Pavilion g4                      | 1         | 1.32%   |
| HP Pavilion dv6500                  | 1         | 1.32%   |
| HP Laptop 17-by2xxx                 | 1         | 1.32%   |
| HP Laptop 15-dw3xxx                 | 1         | 1.32%   |
| HP Laptop 14-cm0xxx                 | 1         | 1.32%   |
| HP EliteBook Folio 9470m            | 1         | 1.32%   |
| HP EliteBook 8440p                  | 1         | 1.32%   |
| HP EliteBook 2530p                  | 1         | 1.32%   |
| HP Compaq Presario CQ50             | 1         | 1.32%   |
| HP Compaq nw9440 (EY615ET#ABU)      | 1         | 1.32%   |
| HP Compaq CQ45                      | 1         | 1.32%   |
| HP Compaq 420                       | 1         | 1.32%   |
| HP Compaq 2510p                     | 1         | 1.32%   |
| HP 655                              | 1         | 1.32%   |
| HP 15 Notebook PC                   | 1         | 1.32%   |
| Google Chell                        | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 6         | 7.89%   |
| Lenovo IdeaPad          | 5         | 6.58%   |
| HP Compaq               | 5         | 6.58%   |
| Lenovo ThinkPad         | 3         | 3.95%   |
| HP Laptop               | 3         | 3.95%   |
| HP EliteBook            | 3         | 3.95%   |
| Dell Inspiron           | 3         | 3.95%   |
| HP Pavilion             | 2         | 2.63%   |
| ASUS VivoBook           | 2         | 2.63%   |
| UMAX VisionBook         | 1         | 1.32%   |
| TR ST                   | 1         | 1.32%   |
| Toshiba Satellite       | 1         | 1.32%   |
| Toshiba QOSMIO          | 1         | 1.32%   |
| Thomson PT-NEO14A.2WH32 | 1         | 1.32%   |
| Samsung X420            | 1         | 1.32%   |
| Samsung NC110P          | 1         | 1.32%   |
| Samsung 905S3G          | 1         | 1.32%   |
| Samsung 530XBB          | 1         | 1.32%   |
| Pegatron H36FF          | 1         | 1.32%   |
| MSI MS-N014             | 1         | 1.32%   |
| Minix Z64               | 1         | 1.32%   |
| Lenovo 3000             | 1         | 1.32%   |
| Insignia NS-P11W7100    | 1         | 1.32%   |
| HP Stream               | 1         | 1.32%   |
| HP Presario             | 1         | 1.32%   |
| HP 655                  | 1         | 1.32%   |
| HP 15                   | 1         | 1.32%   |
| Google Chell            | 1         | 1.32%   |
| Gateway Sonic-C         | 1         | 1.32%   |
| Fujitsu LIFEBOOK        | 1         | 1.32%   |
| Fujitsu FMVNQ8P6        | 1         | 1.32%   |
| Dell Vostro1710         | 1         | 1.32%   |
| Dell MXG071             | 1         | 1.32%   |
| Dell MXG061             | 1         | 1.32%   |
| Dell Latitude           | 1         | 1.32%   |
| ASUS X751LD             | 1         | 1.32%   |
| ASUS X555YI             | 1         | 1.32%   |
| ASUS X541SA             | 1         | 1.32%   |
| ASUS X540YA             | 1         | 1.32%   |
| ASUS UX303LN            | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2014 | 8         | 10.53%  |
| 2010 | 8         | 10.53%  |
| 2018 | 7         | 9.21%   |
| 2008 | 7         | 9.21%   |
| 2007 | 7         | 9.21%   |
| 2015 | 6         | 7.89%   |
| 2012 | 5         | 6.58%   |
| 2019 | 4         | 5.26%   |
| 2017 | 4         | 5.26%   |
| 2016 | 4         | 5.26%   |
| 2011 | 4         | 5.26%   |
| 2020 | 3         | 3.95%   |
| 2022 | 2         | 2.63%   |
| 2013 | 2         | 2.63%   |
| 2006 | 2         | 2.63%   |
| 2021 | 1         | 1.32%   |
| 2009 | 1         | 1.32%   |
| 2004 | 1         | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 76        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 72        | 94.74%  |
| Enabled  | 4         | 5.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 75        | 98.68%  |
| Yes  | 1         | 1.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 28        | 36.84%  |
| 1.01-2.0   | 16        | 21.05%  |
| 4.01-8.0   | 11        | 14.47%  |
| 16.01-24.0 | 8         | 10.53%  |
| 8.01-16.0  | 6         | 7.89%   |
| 0.51-1.0   | 4         | 5.26%   |
| 2.01-3.0   | 2         | 2.63%   |
| 32.01-64.0 | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 39        | 49.37%  |
| 2.01-3.0  | 17        | 21.52%  |
| 0.51-1.0  | 12        | 15.19%  |
| 3.01-4.0  | 5         | 6.33%   |
| 0.01-0.5  | 3         | 3.8%    |
| 4.01-8.0  | 2         | 2.53%   |
| 8.01-16.0 | 1         | 1.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 61        | 80.26%  |
| 2      | 14        | 18.42%  |
| 3      | 1         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 59.21%  |
| Yes       | 31        | 40.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 81.58%  |
| No        | 14        | 18.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 97.37%  |
| No        | 2         | 2.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 69.74%  |
| No        | 23        | 30.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 10        | 13.16%  |
| Germany     | 7         | 9.21%   |
| Romania     | 5         | 6.58%   |
| France      | 5         | 6.58%   |
| Brazil      | 5         | 6.58%   |
| Ukraine     | 4         | 5.26%   |
| UK          | 4         | 5.26%   |
| Poland      | 4         | 5.26%   |
| Italy       | 4         | 5.26%   |
| Spain       | 3         | 3.95%   |
| Russia      | 3         | 3.95%   |
| Turkey      | 2         | 2.63%   |
| Philippines | 2         | 2.63%   |
| Australia   | 2         | 2.63%   |
| Venezuela   | 1         | 1.32%   |
| Thailand    | 1         | 1.32%   |
| Slovakia    | 1         | 1.32%   |
| Serbia      | 1         | 1.32%   |
| Portugal    | 1         | 1.32%   |
| Netherlands | 1         | 1.32%   |
| Myanmar     | 1         | 1.32%   |
| Mexico      | 1         | 1.32%   |
| Iran        | 1         | 1.32%   |
| Indonesia   | 1         | 1.32%   |
| Guadeloupe  | 1         | 1.32%   |
| El Salvador | 1         | 1.32%   |
| Czechia     | 1         | 1.32%   |
| Colombia    | 1         | 1.32%   |
| Chile       | 1         | 1.32%   |
| Canada      | 1         | 1.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Sydney             | 2         | 2.53%   |
| Pabianice          | 2         | 2.53%   |
| Odessa             | 2         | 2.53%   |
| Frankfurt am Main  | 2         | 2.53%   |
| Żywiec            | 1         | 1.27%   |
| Yangon             | 1         | 1.27%   |
| Würzburg          | 1         | 1.27%   |
| Wiesbaden          | 1         | 1.27%   |
| Washington         | 1         | 1.27%   |
| Warsaw             | 1         | 1.27%   |
| Wahroonga          | 1         | 1.27%   |
| Voluntari          | 1         | 1.27%   |
| Vinnytsia          | 1         | 1.27%   |
| Varennes-les-Narcy | 1         | 1.27%   |
| Valencia           | 1         | 1.27%   |
| Tucape             | 1         | 1.27%   |
| Teresina           | 1         | 1.27%   |
| Tekirdağ          | 1         | 1.27%   |
| Tarragona          | 1         | 1.27%   |
| Svidník           | 1         | 1.27%   |
| Surabaya           | 1         | 1.27%   |
| Subotica           | 1         | 1.27%   |
| Studenka           | 1         | 1.27%   |
| St. Petersburg     | 1         | 1.27%   |
| Shadrinsk          | 1         | 1.27%   |
| Sao Paulo          | 1         | 1.27%   |
| Salerno            | 1         | 1.27%   |
| Sabadell           | 1         | 1.27%   |
| Roswell            | 1         | 1.27%   |
| Queretaro          | 1         | 1.27%   |
| Póvoa de Varzim   | 1         | 1.27%   |
| Paris              | 1         | 1.27%   |
| Paranaque City     | 1         | 1.27%   |
| Nudlingen          | 1         | 1.27%   |
| Novaci             | 1         | 1.27%   |
| Moscow             | 1         | 1.27%   |
| Milan              | 1         | 1.27%   |
| Marseille          | 1         | 1.27%   |
| Madrid             | 1         | 1.27%   |
| London             | 1         | 1.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 17     | 16.47%  |
| WDC                 | 12        | 16     | 14.12%  |
| Samsung Electronics | 10        | 11     | 11.76%  |
| Toshiba             | 9         | 10     | 10.59%  |
| Unknown             | 7         | 10     | 8.24%   |
| Kingston            | 5         | 5      | 5.88%   |
| Micron Technology   | 4         | 5      | 4.71%   |
| HGST                | 4         | 4      | 4.71%   |
| SK hynix            | 3         | 4      | 3.53%   |
| SanDisk             | 3         | 3      | 3.53%   |
| Hitachi             | 3         | 3      | 3.53%   |
| GOODRAM             | 2         | 2      | 2.35%   |
| Crucial             | 2         | 2      | 2.35%   |
| Apple               | 2         | 2      | 2.35%   |
| LITEON              | 1         | 1      | 1.18%   |
| Intel               | 1         | 1      | 1.18%   |
| ASUS-PHISON         | 1         | 2      | 1.18%   |
| ASMT                | 1         | 1      | 1.18%   |
| A-DATA Technology   | 1         | 1      | 1.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                | 3         | 3.37%   |
| Toshiba MQ01ABF050 500GB              | 3         | 3.37%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 3.37%   |
| Seagate ST9320325AS 320GB             | 2         | 2.25%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD   | 2         | 2.25%   |
| HGST HTS725050A7E630 500GB            | 2         | 2.25%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1.12%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1.12%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 1.12%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 1.12%   |
| WDC WD2500BEVS-00UST0 250GB           | 1         | 1.12%   |
| WDC WD2500BEVE-00A0HT0 250GB          | 1         | 1.12%   |
| WDC WD1600BEVT-22A23T0 160GB          | 1         | 1.12%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1.12%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 1.12%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1.12%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 1.12%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB  | 1         | 1.12%   |
| Unknown SN64G  64GB                   | 1         | 1.12%   |
| Unknown SLD64G  64GB                  | 1         | 1.12%   |
| Unknown SD64G  64GB                   | 1         | 1.12%   |
| Unknown SD16G  16GB                   | 1         | 1.12%   |
| Unknown NCard  32GB                   | 1         | 1.12%   |
| Unknown MMC Card  128GB               | 1         | 1.12%   |
| Unknown DA4064  64GB                  | 1         | 1.12%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1.12%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1.12%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1.12%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 1.12%   |
| Toshiba MK3265GSX 320GB               | 1         | 1.12%   |
| Toshiba MK1011GAH 100GB               | 1         | 1.12%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1.12%   |
| SK hynix HFM128GDHTNG-8310A 128GB     | 1         | 1.12%   |
| SK hynix HBG4e  32GB                  | 1         | 1.12%   |
| Seagate ST95005620AS 500GB            | 1         | 1.12%   |
| Seagate ST9500423AS 500GB             | 1         | 1.12%   |
| Seagate ST9160823ASG 160GB            | 1         | 1.12%   |
| Seagate ST9160301AS 160GB             | 1         | 1.12%   |
| Seagate ST640LM0 00 HM641JI 640GB     | 1         | 1.12%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 1.12%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 17     | 35.9%   |
| Toshiba             | 9         | 10     | 23.08%  |
| WDC                 | 7         | 10     | 17.95%  |
| HGST                | 4         | 4      | 10.26%  |
| Hitachi             | 3         | 3      | 7.69%   |
| Samsung Electronics | 2         | 3      | 5.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 4      | 14.81%  |
| WDC                 | 3         | 3      | 11.11%  |
| Samsung Electronics | 3         | 3      | 11.11%  |
| Micron Technology   | 3         | 4      | 11.11%  |
| SanDisk             | 2         | 2      | 7.41%   |
| GOODRAM             | 2         | 2      | 7.41%   |
| Crucial             | 2         | 2      | 7.41%   |
| Apple               | 2         | 2      | 7.41%   |
| SK hynix            | 1         | 2      | 3.7%    |
| LITEON              | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| ASUS-PHISON         | 1         | 2      | 3.7%    |
| ASMT                | 1         | 1      | 3.7%    |
| A-DATA Technology   | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 47     | 46.99%  |
| SSD  | 26        | 30     | 31.33%  |
| MMC  | 9         | 12     | 10.84%  |
| NVMe | 9         | 11     | 10.84%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 75     | 74.68%  |
| NVMe | 9         | 11     | 11.39%  |
| MMC  | 9         | 12     | 11.39%  |
| SAS  | 2         | 2      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 63     | 77.78%  |
| 0.51-1.0   | 13        | 13     | 20.63%  |
| 1.01-2.0   | 1         | 1      | 1.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 38.46%  |
| 251-500        | 18        | 23.08%  |
| 51-100         | 12        | 15.38%  |
| 1-20           | 7         | 8.97%   |
| 21-50          | 5         | 6.41%   |
| 501-1000       | 5         | 6.41%   |
| More than 3000 | 1         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 44        | 55.7%   |
| 21-50     | 17        | 21.52%  |
| 51-100    | 11        | 13.92%  |
| 101-250   | 6         | 7.59%   |
| 2001-3000 | 1         | 1.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 6.25%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 6.25%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 6.25%   |
| Toshiba MK3265GSX 320GB                        | 1         | 1      | 6.25%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 6.25%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 6.25%   |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 6.25%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 6.25%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 6.25%   |
| SanDisk SSD PLUS 120GB                         | 1         | 1      | 6.25%   |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 6.25%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 6.25%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 6.25%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 6.25%   |
| Apple SSD SM128C 121GB                         | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 31.25%  |
| WDC                 | 3         | 3      | 18.75%  |
| Toshiba             | 2         | 2      | 12.5%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |
| Apple               | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 41.67%  |
| WDC                 | 2         | 2      | 16.67%  |
| Toshiba             | 2         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 75%     |
| SSD  | 4         | 4      | 25%     |

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
| Detected | 32        | 48     | 41.03%  |
| Works    | 31        | 36     | 39.74%  |
| Malfunc  | 15        | 16     | 19.23%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 54        | 69.23%  |
| AMD                         | 10        | 12.82%  |
| Samsung Electronics         | 5         | 6.41%   |
| Nvidia                      | 3         | 3.85%   |
| SanDisk                     | 2         | 2.56%   |
| SK hynix                    | 1         | 1.28%   |
| Micron Technology           | 1         | 1.28%   |
| Marvell Technology Group    | 1         | 1.28%   |
| Kingston Technology Company | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 9.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 7.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 5.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 4.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 4.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 4.26%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 3.19%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 3.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 3.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 2.13%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.13%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 2.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 2.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 2.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 2.13%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 1.06%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.06%   |
| SanDisk NVMe Controller                                                          | 1         | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.06%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.06%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 1.06%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 1.06%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.06%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.06%   |
| Micron NVMe Storage Controller                                                   | 1         | 1.06%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 1.06%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.06%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 1.06%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 1.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.06%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 57        | 65.52%  |
| IDE  | 16        | 18.39%  |
| NVMe | 9         | 10.34%  |
| RAID | 5         | 5.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 64        | 84.21%  |
| AMD    | 12        | 15.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 2.63%   |
| Intel Core 2 CPU T7600 @ 2.33GHz            | 2         | 2.63%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 2.63%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 2.63%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 2.63%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.32%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1.32%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.32%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.32%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 1.32%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 1.32%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.32%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.32%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.32%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.32%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 1.32%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 1.32%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.32%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 1.32%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.32%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i5-2467M CPU @ 1.60GHz           | 1         | 1.32%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.32%   |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 1         | 1.32%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.32%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.32%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.32%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1         | 1.32%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.32%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 1.32%   |
| Intel Core 2 Duo CPU U7600 @ 1.20GHz        | 1         | 1.32%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz        | 1         | 1.32%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 1.32%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz        | 1         | 1.32%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.32%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 14.47%  |
| Intel Core 2 Duo        | 10        | 13.16%  |
| Intel Core i7           | 7         | 9.21%   |
| Intel Celeron           | 7         | 9.21%   |
| Intel Atom              | 7         | 9.21%   |
| Other                   | 5         | 6.58%   |
| Intel Pentium           | 5         | 6.58%   |
| Intel Core i3           | 5         | 6.58%   |
| Intel Core 2            | 3         | 3.95%   |
| Intel Genuine           | 2         | 2.63%   |
| AMD E2                  | 2         | 2.63%   |
| AMD A8                  | 2         | 2.63%   |
| Intel Pentium Dual-Core | 1         | 1.32%   |
| Intel Core m7           | 1         | 1.32%   |
| Intel Celeron M         | 1         | 1.32%   |
| AMD Turion Dual-Core    | 1         | 1.32%   |
| AMD Turion 64 X2 Mobile | 1         | 1.32%   |
| AMD Quad-Core           | 1         | 1.32%   |
| AMD Athlon II Neo       | 1         | 1.32%   |
| AMD A6                  | 1         | 1.32%   |
| AMD A12                 | 1         | 1.32%   |
| AMD A10                 | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 47        | 61.84%  |
| 4      | 21        | 27.63%  |
| 1      | 5         | 6.58%   |
| 14     | 1         | 1.32%   |
| 10     | 1         | 1.32%   |
| 6      | 1         | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 76        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 42        | 55.26%  |
| 2      | 34        | 44.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 74        | 97.37%  |
| 32-bit         | 2         | 2.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 11.69%  |
| 0x30678    | 6         | 7.79%   |
| 0x206a7    | 5         | 6.49%   |
| 0x1067a    | 5         | 6.49%   |
| 0x6fd      | 3         | 3.9%    |
| 0x40651    | 3         | 3.9%    |
| 0x306a9    | 3         | 3.9%    |
| 0x20655    | 3         | 3.9%    |
| 0x806ea    | 2         | 2.6%    |
| 0x806e9    | 2         | 2.6%    |
| 0x806c1    | 2         | 2.6%    |
| 0x6fb      | 2         | 2.6%    |
| 0x6f6      | 2         | 2.6%    |
| 0x406c4    | 2         | 2.6%    |
| 0x406c3    | 2         | 2.6%    |
| 0x306c3    | 2         | 2.6%    |
| 0x106ca    | 2         | 2.6%    |
| 0x10676    | 2         | 2.6%    |
| 0x06006705 | 2         | 2.6%    |
| 0x906ea    | 1         | 1.3%    |
| 0x906e9    | 1         | 1.3%    |
| 0x906a4    | 1         | 1.3%    |
| 0x906a3    | 1         | 1.3%    |
| 0x806ec    | 1         | 1.3%    |
| 0x806eb    | 1         | 1.3%    |
| 0x706a1    | 1         | 1.3%    |
| 0x6d8      | 1         | 1.3%    |
| 0x506e3    | 1         | 1.3%    |
| 0x506c9    | 1         | 1.3%    |
| 0x406e3    | 1         | 1.3%    |
| 0x30661    | 1         | 1.3%    |
| 0x07030105 | 1         | 1.3%    |
| 0x06006118 | 1         | 1.3%    |
| 0x06001119 | 1         | 1.3%    |
| 0x05000119 | 1         | 1.3%    |
| 0x02000057 | 1         | 1.3%    |
| 0x010000c8 | 1         | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Silvermont       | 11        | 14.47%  |
| Penryn           | 8         | 10.53%  |
| KabyLake         | 8         | 10.53%  |
| Core             | 8         | 10.53%  |
| SandyBridge      | 5         | 6.58%   |
| Haswell          | 5         | 6.58%   |
| Excavator        | 4         | 5.26%   |
| Westmere         | 3         | 3.95%   |
| IvyBridge        | 3         | 3.95%   |
| Bonnell          | 3         | 3.95%   |
| TigerLake        | 2         | 2.63%   |
| Skylake          | 2         | 2.63%   |
| Puma             | 2         | 2.63%   |
| P6               | 2         | 2.63%   |
| Alderlake Hybrid | 2         | 2.63%   |
| Piledriver       | 1         | 1.32%   |
| K8 Hammer        | 1         | 1.32%   |
| K8 & K10 hybrid  | 1         | 1.32%   |
| K10              | 1         | 1.32%   |
| Jaguar           | 1         | 1.32%   |
| Goldmont plus    | 1         | 1.32%   |
| Goldmont         | 1         | 1.32%   |
| Bobcat           | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 65.12%  |
| Nvidia | 18        | 20.93%  |
| AMD    | 12        | 13.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 6.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 5.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 5.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 5.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 5.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.23%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.15%   |
| Intel HD Graphics 620                                                                    | 2         | 2.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.15%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 2.15%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 2.15%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.15%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.08%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.08%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.08%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.08%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.08%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 1.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.08%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 1.08%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 1.08%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.08%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 1.08%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 1.08%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 1.08%   |
| Nvidia G71M [GeForce Go 7950 GTX]                                                        | 1         | 1.08%   |
| Nvidia G71GLM [Quadro FX 1500M]                                                          | 1         | 1.08%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 1         | 1.08%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.08%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 1.08%   |
| Intel HD Graphics 630                                                                    | 1         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 60.53%  |
| 1 x AMD        | 10        | 13.16%  |
| 1 x Nvidia     | 9         | 11.84%  |
| Intel + Nvidia | 9         | 11.84%  |
| 2 x AMD        | 1         | 1.32%   |
| Intel + AMD    | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 67        | 87.01%  |
| Proprietary | 9         | 11.69%  |
| Unknown     | 1         | 1.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 71.05%  |
| 0.01-0.5   | 12        | 15.79%  |
| 0.51-1.0   | 4         | 5.26%   |
| 3.01-4.0   | 3         | 3.95%   |
| 1.01-2.0   | 2         | 2.63%   |
| 5.01-6.0   | 1         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 16.25%  |
| Samsung Electronics     | 11        | 13.75%  |
| LG Display              | 10        | 12.5%   |
| Chimei Innolux          | 10        | 12.5%   |
| BOE                     | 8         | 10%     |
| Chi Mei Optoelectronics | 7         | 8.75%   |
| LG Philips              | 2         | 2.5%    |
| HannStar                | 2         | 2.5%    |
| Goldstar                | 2         | 2.5%    |
| CPT                     | 2         | 2.5%    |
| Apple                   | 2         | 2.5%    |
| Sony                    | 1         | 1.25%   |
| Seiko/Epson             | 1         | 1.25%   |
| SANYO                   | 1         | 1.25%   |
| PANDA                   | 1         | 1.25%   |
| OEM                     | 1         | 1.25%   |
| Lenovo                  | 1         | 1.25%   |
| InfoVision              | 1         | 1.25%   |
| eMachines               | 1         | 1.25%   |
| BenQ                    | 1         | 1.25%   |
| Belinea                 | 1         | 1.25%   |
| Unknown                 | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 2.5%    |
| Sony TV *00 SNY8004 3840x2160 1439x809mm 65.0-inch                    | 1         | 1.25%   |
| Seiko/Epson LCD Monitor                                               | 1         | 1.25%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 1.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 1.25%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 1.25%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 1         | 1.25%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch           | 1         | 1.25%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGD03E3 1366x768 310x174mm 14.0-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD038C 1366x768 256x144mm 11.6-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 1         | 1.25%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch               | 1         | 1.25%   |
| InfoVision LCD Monitor IVO057C 1366x768 309x174mm 14.0-inch           | 1         | 1.25%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                  | 1         | 1.25%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                 | 1         | 1.25%   |
| eMachines E190HQV EMA0212 1366x768 409x230mm 18.5-inch                | 1         | 1.25%   |
| CPT LCD Monitor CPT14BF 1366x768 344x193mm 15.5-inch                  | 1         | 1.25%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                  | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1737 1920x1080 381x214mm 17.2-inch      | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch       | 1         | 1.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 34        | 42.5%   |
| 1920x1080 (FHD)    | 19        | 23.75%  |
| 1280x800 (WXGA)    | 8         | 10%     |
| 1920x1200 (WUXGA)  | 6         | 7.5%    |
| 3840x2160 (4K)     | 2         | 2.5%    |
| 1600x900 (HD+)     | 2         | 2.5%    |
| 1024x600           | 2         | 2.5%    |
| 3840x2400          | 1         | 1.25%   |
| 1920x540           | 1         | 1.25%   |
| 1680x1050 (WSXGA+) | 1         | 1.25%   |
| 1440x900 (WXGA+)   | 1         | 1.25%   |
| 1360x768           | 1         | 1.25%   |
| 1280x1024 (SXGA)   | 1         | 1.25%   |
| Unknown            | 1         | 1.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 26        | 32.5%   |
| 14      | 10        | 12.5%   |
| 13      | 10        | 12.5%   |
| 17      | 9         | 11.25%  |
| 11      | 6         | 7.5%    |
| 16      | 3         | 3.75%   |
| 12      | 3         | 3.75%   |
| Unknown | 3         | 3.75%   |
| 24      | 2         | 2.5%    |
| 21      | 2         | 2.5%    |
| 10      | 2         | 2.5%    |
| 65      | 1         | 1.25%   |
| 46      | 1         | 1.25%   |
| 23      | 1         | 1.25%   |
| 19      | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 44        | 55.7%   |
| 201-300     | 14        | 17.72%  |
| 351-400     | 10        | 12.66%  |
| 501-600     | 3         | 3.8%    |
| 401-500     | 3         | 3.8%    |
| Unknown     | 3         | 3.8%    |
| 1001-1500   | 2         | 2.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 57        | 75%     |
| 16/10   | 15        | 19.74%  |
| Unknown | 2         | 2.63%   |
| 6/5     | 1         | 1.32%   |
| 3/2     | 1         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 32.5%   |
| 81-90          | 17        | 21.25%  |
| 51-60          | 6         | 7.5%    |
| 121-130        | 6         | 7.5%    |
| 131-140        | 5         | 6.25%   |
| 201-250        | 4         | 5%      |
| 71-80          | 3         | 3.75%   |
| 61-70          | 3         | 3.75%   |
| Unknown        | 3         | 3.75%   |
| 41-50          | 2         | 2.5%    |
| More than 1000 | 1         | 1.25%   |
| 251-300        | 1         | 1.25%   |
| 151-200        | 1         | 1.25%   |
| 111-120        | 1         | 1.25%   |
| 501-1000       | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 31        | 39.74%  |
| 121-160       | 26        | 33.33%  |
| 51-100        | 13        | 16.67%  |
| Unknown       | 3         | 3.85%   |
| More than 240 | 2         | 2.56%   |
| 161-240       | 2         | 2.56%   |
| 1-50          | 1         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 69        | 89.61%  |
| 2     | 8         | 10.39%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 41        | 35.34%  |
| Intel                 | 29        | 25%     |
| Qualcomm Atheros      | 23        | 19.83%  |
| Broadcom              | 10        | 8.62%   |
| Broadcom Limited      | 4         | 3.45%   |
| Sierra Wireless       | 2         | 1.72%   |
| Ralink                | 2         | 1.72%   |
| Nvidia                | 2         | 1.72%   |
| Ralink Technology     | 1         | 0.86%   |
| D-Link                | 1         | 0.86%   |
| ASIX Electronics      | 1         | 0.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 20        | 13.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 13        | 9.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 4.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 4.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 3.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4         | 2.8%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 2.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 2.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 3         | 2.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 1.4%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 2         | 1.4%    |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.4%    |
| Intel Wireless 3165                                                                           | 2         | 1.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2         | 1.4%    |
| Intel 82567LM Gigabit Network Connection                                                      | 2         | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.4%    |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 1.4%    |
| Sierra Wireless EM7455                                                                        | 1         | 0.7%    |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.7%    |
| Realtek USB 10/100 LAN                                                                        | 1         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.7%    |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 0.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1         | 0.7%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                                              | 1         | 0.7%    |
| Realtek 802.11ac NIC                                                                          | 1         | 0.7%    |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.7%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 0.7%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                    | 1         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 34.18%  |
| Qualcomm Atheros      | 21        | 26.58%  |
| Realtek Semiconductor | 18        | 22.78%  |
| Broadcom              | 5         | 6.33%   |
| Sierra Wireless       | 2         | 2.53%   |
| Ralink                | 2         | 2.53%   |
| Broadcom Limited      | 2         | 2.53%   |
| Ralink Technology     | 1         | 1.27%   |
| D-Link                | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 7.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 6         | 7.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4         | 5%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 5%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 2.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 2         | 2.5%    |
| Intel Wireless 8265 / 8275                                                                    | 2         | 2.5%    |
| Intel Wireless 3165                                                                           | 2         | 2.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.5%    |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 2.5%    |
| Sierra Wireless EM7455                                                                        | 1         | 1.25%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 1.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.25%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1.25%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 1.25%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 1.25%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 1.25%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.25%   |
| Realtek 802.11ac NIC                                                                          | 1         | 1.25%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.25%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 1.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.25%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 1.25%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.25%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 1.25%   |
| Intel Wireless 7265                                                                           | 1         | 1.25%   |
| Intel Wireless 7260                                                                           | 1         | 1.25%   |
| Intel Wireless 3160                                                                           | 1         | 1.25%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.25%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.25%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 1.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 36        | 58.06%  |
| Intel                 | 9         | 14.52%  |
| Qualcomm Atheros      | 7         | 11.29%  |
| Broadcom              | 5         | 8.06%   |
| Nvidia                | 2         | 3.23%   |
| Broadcom Limited      | 2         | 3.23%   |
| ASIX Electronics      | 1         | 1.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 31.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 20.63%  |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.17%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 3.17%   |
| Realtek USB 10/100 LAN                                            | 1         | 1.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.59%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.59%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.59%   |
| Nvidia MCP77 Ethernet                                             | 1         | 1.59%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.59%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.59%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.59%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.59%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express          | 1         | 1.59%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.59%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.59%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.59%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.59%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 1.59%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express  | 1         | 1.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 54.41%  |
| Ethernet | 62        | 45.59%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 76.25%  |
| Ethernet | 19        | 23.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 59        | 77.63%  |
| 1     | 14        | 18.42%  |
| 0     | 3         | 3.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 61        | 79.22%  |
| Yes  | 16        | 20.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 28.3%   |
| Realtek Semiconductor           | 10        | 18.87%  |
| Hewlett-Packard                 | 5         | 9.43%   |
| IMC Networks                    | 4         | 7.55%   |
| Qualcomm Atheros Communications | 3         | 5.66%   |
| Lite-On Technology              | 3         | 5.66%   |
| Broadcom                        | 3         | 5.66%   |
| Dell                            | 2         | 3.77%   |
| Chicony Electronics             | 2         | 3.77%   |
| Apple                           | 2         | 3.77%   |
| Toshiba                         | 1         | 1.89%   |
| Ralink                          | 1         | 1.89%   |
| Foxconn / Hon Hai               | 1         | 1.89%   |
| ASUSTek Computer                | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 7         | 13.21%  |
| Realtek Bluetooth Radio                          | 6         | 11.32%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 3         | 5.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 3         | 5.66%   |
| Realtek  Bluetooth 4.2 Adapter                   | 2         | 3.77%   |
| Intel AX201 Bluetooth                            | 2         | 3.77%   |
| IMC Networks Bluetooth Device                    | 2         | 3.77%   |
| HP Broadcom 2070 Bluetooth Combo                 | 2         | 3.77%   |
| Dell Wireless 355 Bluetooth                      | 2         | 3.77%   |
| Chicony Bluetooth (RTL8723BE)                    | 2         | 3.77%   |
| Broadcom BCM2045 Bluetooth                       | 2         | 3.77%   |
| Toshiba Askey Bluetooth Module                   | 1         | 1.89%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter          | 1         | 1.89%   |
| Realtek RTL8821A Bluetooth                       | 1         | 1.89%   |
| Ralink RT3290 Bluetooth                          | 1         | 1.89%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 1.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 1.89%   |
| Qualcomm Atheros AR3012 Bluetooth                | 1         | 1.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 1.89%   |
| Lite-On Bluetooth Device                         | 1         | 1.89%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 1.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 1.89%   |
| Intel Bluetooth Device                           | 1         | 1.89%   |
| IMC Networks Bluetooth USB Host Controller       | 1         | 1.89%   |
| IMC Networks Bluetooth Radio                     | 1         | 1.89%   |
| Foxconn / Hon Hai BCM20702A0                     | 1         | 1.89%   |
| Broadcom HP Portable Valentine                   | 1         | 1.89%   |
| ASUS BT-270 Bluetooth Adapter                    | 1         | 1.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI             | 1         | 1.89%   |
| Apple Bluetooth USB Host Controller              | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 59        | 72.84%  |
| AMD              | 11        | 13.58%  |
| Nvidia           | 9         | 11.11%  |
| Logitech         | 1         | 1.23%   |
| Blue Microphones | 1         | 1.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 7.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 7.22%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 5.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 5.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 5.15%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 5.15%   |
| AMD FCH Azalia Controller                                                                         | 5         | 5.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 4.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 4.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.09%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 3.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 2.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.06%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.06%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.03%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 1.03%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.03%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.03%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.03%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 1.03%   |
| Nvidia Audio device                                                                               | 1         | 1.03%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 1.03%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.03%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.03%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 1.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.03%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 1.03%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 25.35%  |
| SK hynix            | 14        | 19.72%  |
| Unknown             | 8         | 11.27%  |
| Micron Technology   | 7         | 9.86%   |
| Kingston            | 7         | 9.86%   |
| Elpida              | 3         | 4.23%   |
| A-DATA Technology   | 3         | 4.23%   |
| Unknown             | 3         | 4.23%   |
| Ramaxel Technology  | 2         | 2.82%   |
| Nanya Technology    | 2         | 2.82%   |
| Unknown (ABCD)      | 1         | 1.41%   |
| Transcend           | 1         | 1.41%   |
| Qimonda             | 1         | 1.41%   |
| G.Skill             | 1         | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 3         | 4.05%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 2.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.7%    |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 1.35%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 1.35%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.35%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.35%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                            | 1         | 1.35%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                   | 1         | 1.35%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 1.35%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                    | 1         | 1.35%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 1.35%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.35%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 1.35%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 1         | 1.35%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 1.35%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 1.35%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s             | 1         | 1.35%   |
| SK hynix RAM HMP125S6EFR8C-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 1.35%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.35%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.35%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.35%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 26        | 42.62%  |
| DDR4    | 13        | 21.31%  |
| DDR2    | 11        | 18.03%  |
| SDRAM   | 4         | 6.56%   |
| LPDDR4  | 3         | 4.92%   |
| Unknown | 2         | 3.28%   |
| DRAM    | 1         | 1.64%   |
| DDR     | 1         | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 57        | 98.28%  |
| DIMM   | 1         | 1.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 23        | 34.33%  |
| 4096  | 20        | 29.85%  |
| 8192  | 13        | 19.4%   |
| 1024  | 9         | 13.43%  |
| 16384 | 2         | 2.99%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 21        | 32.81%  |
| 667     | 8         | 12.5%   |
| 2667    | 7         | 10.94%  |
| 3200    | 5         | 7.81%   |
| 1333    | 3         | 4.69%   |
| 975     | 3         | 4.69%   |
| 4199    | 2         | 3.13%   |
| 3266    | 2         | 3.13%   |
| 2400    | 2         | 3.13%   |
| 2048    | 2         | 3.13%   |
| 1334    | 2         | 3.13%   |
| 1066    | 2         | 3.13%   |
| 800     | 2         | 3.13%   |
| 1866    | 1         | 1.56%   |
| 400     | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

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
| Chicony Electronics                    | 16        | 26.67%  |
| Quanta                                 | 6         | 10%     |
| Cheng Uei Precision Industry (Foxlink) | 6         | 10%     |
| Suyin                                  | 5         | 8.33%   |
| IMC Networks                           | 4         | 6.67%   |
| Syntek                                 | 3         | 5%      |
| Silicon Motion                         | 3         | 5%      |
| Apple                                  | 3         | 5%      |
| Alcor Micro                            | 3         | 5%      |
| Sunplus Innovation Technology          | 2         | 3.33%   |
| Realtek Semiconductor                  | 2         | 3.33%   |
| Microdia                               | 2         | 3.33%   |
| Z-Star Microelectronics                | 1         | 1.67%   |
| OmniVision Technologies                | 1         | 1.67%   |
| Logitech                               | 1         | 1.67%   |
| Lite-On Technology                     | 1         | 1.67%   |
| Aveo Technology                        | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                    | 5         | 8.33%   |
| Syntek Lenovo EasyCamera                         | 2         | 3.33%   |
| Suyin HP TrueVision HD Integrated Webcam         | 2         | 3.33%   |
| Quanta HP TrueVision HD Camera                   | 2         | 3.33%   |
| Chicony Integrated Camera                        | 2         | 3.33%   |
| Chicony FJ Camera                                | 2         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 3.33%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 2         | 3.33%   |
| Z-Star Webcam                                    | 1         | 1.67%   |
| Syntek USB Video Device                          | 1         | 1.67%   |
| Suyin USB 2.0 Camera                             | 1         | 1.67%   |
| Suyin Integrated_Webcam_HD                       | 1         | 1.67%   |
| Suyin Acer/Lenovo Webcam [CN0316]                | 1         | 1.67%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 1.67%   |
| Sunplus HD WebCam                                | 1         | 1.67%   |
| Silicon Motion WebCam SC-10HDD13335N             | 1         | 1.67%   |
| Silicon Motion WebCam SC-0311139N                | 1         | 1.67%   |
| Silicon Motion Web Camera                        | 1         | 1.67%   |
| Realtek USB2.0 HD UVC WebCam                     | 1         | 1.67%   |
| Realtek USB Camera                               | 1         | 1.67%   |
| Quanta VGA WebCam                                | 1         | 1.67%   |
| Quanta HP Truevision HD                          | 1         | 1.67%   |
| Quanta HD Webcam                                 | 1         | 1.67%   |
| Quanta ACER HD User Facing                       | 1         | 1.67%   |
| OmniVision OV2640 Webcam                         | 1         | 1.67%   |
| Microdia Sonix USB 2.0 Camera                    | 1         | 1.67%   |
| Microdia Integrated_Webcam_FHD                   | 1         | 1.67%   |
| Logitech HD Webcam C615                          | 1         | 1.67%   |
| Lite-On Integrated Camera                        | 1         | 1.67%   |
| IMC Networks USB2.0 UVC VGA WebCam               | 1         | 1.67%   |
| IMC Networks Integrated Camera                   | 1         | 1.67%   |
| IMC Networks EasyCamera                          | 1         | 1.67%   |
| IMC Networks 2M Integrated Webcam                | 1         | 1.67%   |
| Chicony VGA Webcam                               | 1         | 1.67%   |
| Chicony USB 2.0 Camera                           | 1         | 1.67%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 1.67%   |
| Chicony HP Laptop Integrated Webcam [2 MP Fixed] | 1         | 1.67%   |
| Chicony HD WebCam (Asus N-series)                | 1         | 1.67%   |
| Chicony HD WebCam                                | 1         | 1.67%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 1         | 1.67%   |

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
| O2 Micro    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| O2 Micro Oz776 SmartCard Reader     | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 50        | 64.94%  |
| 1     | 22        | 28.57%  |
| 2     | 5         | 6.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 28.13%  |
| Graphics card            | 6         | 18.75%  |
| Net/wireless             | 5         | 15.63%  |
| Multimedia controller    | 2         | 6.25%   |
| Chipcard                 | 2         | 6.25%   |
| Bluetooth                | 2         | 6.25%   |
| Storage                  | 1         | 3.13%   |
| Sound                    | 1         | 3.13%   |
| Net/ethernet             | 1         | 3.13%   |
| Dvb card                 | 1         | 3.13%   |
| Communication controller | 1         | 3.13%   |
| Camera                   | 1         | 3.13%   |

