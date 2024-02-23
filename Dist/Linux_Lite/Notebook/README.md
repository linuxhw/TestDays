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

Total: 139

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | G460 20041                  | [becc9c140b](https://linux-hardware.org/?probe=becc9c140b) | Jan 21, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [92f943771a](https://linux-hardware.org/?probe=92f943771a) | Jan 19, 2024 |
| Acer          | Aspire 7750G                | [cdbe6b267f](https://linux-hardware.org/?probe=cdbe6b267f) | Dec 19, 2023 |
| Acer          | Aspire 7750G                | [6fc9570e4f](https://linux-hardware.org/?probe=6fc9570e4f) | Dec 19, 2023 |
| ASUSTek       | K52Jc                       | [54e52154d1](https://linux-hardware.org/?probe=54e52154d1) | Dec 07, 2023 |
| Sony          | VGN-SZ750N                  | [aa0a3e3559](https://linux-hardware.org/?probe=aa0a3e3559) | Nov 13, 2023 |
| Intel         | Jasper Lake Client Platf... | [75a2534386](https://linux-hardware.org/?probe=75a2534386) | Nov 07, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [639a14d08d](https://linux-hardware.org/?probe=639a14d08d) | Nov 01, 2023 |
| Compaq(Int... | Michelangelo(LT1504)        | [678614e123](https://linux-hardware.org/?probe=678614e123) | Oct 27, 2023 |
| Acer          | Aspire ES1-572              | [2e48163fbd](https://linux-hardware.org/?probe=2e48163fbd) | Oct 06, 2023 |
| Acer          | Aspire ES1-572              | [651a8f8f97](https://linux-hardware.org/?probe=651a8f8f97) | Oct 05, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [12331db1c1](https://linux-hardware.org/?probe=12331db1c1) | Oct 03, 2023 |
| ASUSTek       | X550CL                      | [6c2de2dfb8](https://linux-hardware.org/?probe=6c2de2dfb8) | Sep 21, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | [5f99185bbb](https://linux-hardware.org/?probe=5f99185bbb) | Sep 17, 2023 |
| Toshiba       | Satellite P305              | [d5ac020866](https://linux-hardware.org/?probe=d5ac020866) | Sep 15, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | [eaaac22962](https://linux-hardware.org/?probe=eaaac22962) | Sep 15, 2023 |
| Toshiba       | Satellite C850-C1S          | [ce5643add2](https://linux-hardware.org/?probe=ce5643add2) | Sep 09, 2023 |
| Lenovo        | ThinkPad T430s 2356H83      | [d623d73283](https://linux-hardware.org/?probe=d623d73283) | Aug 28, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [546610fecb](https://linux-hardware.org/?probe=546610fecb) | Aug 20, 2023 |
| Dell          | Latitude E7240              | [87a0310cf0](https://linux-hardware.org/?probe=87a0310cf0) | Aug 02, 2023 |
| ASUSTek       | X502CA                      | [a2f77869ad](https://linux-hardware.org/?probe=a2f77869ad) | Jul 14, 2023 |
| Medion        | Akoya E6418 MD99620         | [7416e91f77](https://linux-hardware.org/?probe=7416e91f77) | Jul 14, 2023 |
| HP            | Laptop 14-dk1xxx            | [8a66b6d6b6](https://linux-hardware.org/?probe=8a66b6d6b6) | Jul 03, 2023 |
| Lenovo        | IdeaPad 310S-14AST 80UL     | [f897f42089](https://linux-hardware.org/?probe=f897f42089) | Jul 03, 2023 |
| HP            | Laptop 15-db0xxx            | [892229f999](https://linux-hardware.org/?probe=892229f999) | Jun 28, 2023 |
| HP            | Laptop 15-db0xxx            | [6d470794e9](https://linux-hardware.org/?probe=6d470794e9) | Jun 28, 2023 |
| UNOWHY        | Y13G010S4EI                 | [b36de255fe](https://linux-hardware.org/?probe=b36de255fe) | Jun 22, 2023 |
| UNOWHY        | Y13G010S4EI                 | [f8f4049a95](https://linux-hardware.org/?probe=f8f4049a95) | Jun 22, 2023 |
| Dell          | Latitude E6420              | [e86a159ec5](https://linux-hardware.org/?probe=e86a159ec5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [01cd20c83d](https://linux-hardware.org/?probe=01cd20c83d) | Jun 03, 2023 |
| Lenovo        | ThinkPad X240 20AMS1J100    | [86edc6c6d6](https://linux-hardware.org/?probe=86edc6c6d6) | May 11, 2023 |
| Apple         | MacBookAir4,1               | [87ab055a31](https://linux-hardware.org/?probe=87ab055a31) | Apr 27, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [c5c1b213f2](https://linux-hardware.org/?probe=c5c1b213f2) | Apr 16, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [d79463ea93](https://linux-hardware.org/?probe=d79463ea93) | Apr 04, 2023 |
| Toshiba       | QOSMIO X70-B                | [8d94a6c8e7](https://linux-hardware.org/?probe=8d94a6c8e7) | Mar 28, 2023 |
| HP            | EliteBook 2530p             | [06ad8714ea](https://linux-hardware.org/?probe=06ad8714ea) | Mar 22, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | [b42df5cbe0](https://linux-hardware.org/?probe=b42df5cbe0) | Mar 11, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | [17a3030488](https://linux-hardware.org/?probe=17a3030488) | Mar 11, 2023 |
| Gateway       | Sonic-C                     | [b9f775b14e](https://linux-hardware.org/?probe=b9f775b14e) | Feb 28, 2023 |
| Gateway       | Sonic-C                     | [6def275f9b](https://linux-hardware.org/?probe=6def275f9b) | Feb 26, 2023 |
| ASUSTek       | G73Sw                       | [199c8805ee](https://linux-hardware.org/?probe=199c8805ee) | Feb 10, 2023 |
| HP            | 240 G3                      | [a977b66ced](https://linux-hardware.org/?probe=a977b66ced) | Feb 02, 2023 |
| HP            | 240 G3                      | [816a3f4b28](https://linux-hardware.org/?probe=816a3f4b28) | Feb 02, 2023 |
| ASUSTek       | G73Sw                       | [b8891cfc9b](https://linux-hardware.org/?probe=b8891cfc9b) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | [fb0a23c0e6](https://linux-hardware.org/?probe=fb0a23c0e6) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | [24b6a47ebb](https://linux-hardware.org/?probe=24b6a47ebb) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | [adbc469f95](https://linux-hardware.org/?probe=adbc469f95) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | [9249ff32b3](https://linux-hardware.org/?probe=9249ff32b3) | Jan 22, 2023 |
| HP            | Stream Notebook PC 13       | [b31d60976b](https://linux-hardware.org/?probe=b31d60976b) | Jan 14, 2023 |
| Acer          | Aspire A315-53              | [eb42b5e055](https://linux-hardware.org/?probe=eb42b5e055) | Dec 24, 2022 |
| Pegatron      | H36FF                       | [f27fc61f18](https://linux-hardware.org/?probe=f27fc61f18) | Dec 18, 2022 |
| Thomson       | PT-NEO14A.2WH32             | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| Pegatron      | H36FF                       | [692955be3d](https://linux-hardware.org/?probe=692955be3d) | Dec 18, 2022 |
| Acer          | Nitro AN515-58              | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| UMAX          | VisionBook 12Wi 64G         | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| HP            | Compaq Presario CQ50        | [8546f55697](https://linux-hardware.org/?probe=8546f55697) | Oct 24, 2022 |
| HP            | Compaq Presario CQ50        | [3b1b5c18c6](https://linux-hardware.org/?probe=3b1b5c18c6) | Oct 24, 2022 |
| Acer          | Aspire 5600                 | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| MSI           | MS-N014                     | [4c41640fd3](https://linux-hardware.org/?probe=4c41640fd3) | Oct 12, 2022 |
| MSI           | MS-N014                     | [3144cac65a](https://linux-hardware.org/?probe=3144cac65a) | Oct 12, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [676289f650](https://linux-hardware.org/?probe=676289f650) | Oct 02, 2022 |
| HP            | Compaq 420                  | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | Presario V6000 (RG289UA#... | [7f0113694a](https://linux-hardware.org/?probe=7f0113694a) | Sep 15, 2022 |
| Samsung       | X420/X520                   | [a8ca7bb005](https://linux-hardware.org/?probe=a8ca7bb005) | Sep 04, 2022 |
| Fujitsu       | FMVNQ8P6                    | [5e34698f14](https://linux-hardware.org/?probe=5e34698f14) | Aug 28, 2022 |
| ASUSTek       | UX303LN                     | [63d5525864](https://linux-hardware.org/?probe=63d5525864) | Aug 16, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| Apple         | MacBookAir6,1               | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| HP            | Pavilion g4                 | [330078dbac](https://linux-hardware.org/?probe=330078dbac) | Jul 04, 2022 |
| ASUSTek       | X555YI                      | [762b96a2de](https://linux-hardware.org/?probe=762b96a2de) | Jul 02, 2022 |
| HP            | EliteBook 8440p             | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| Samsung       | 530XBB                      | [485a99ca42](https://linux-hardware.org/?probe=485a99ca42) | Jun 03, 2022 |
| Minix         | Z64 V1.2                    | [97525a1dc3](https://linux-hardware.org/?probe=97525a1dc3) | May 27, 2022 |
| Dell          | Inspiron 16 5620            | [b42e1cf95b](https://linux-hardware.org/?probe=b42e1cf95b) | May 13, 2022 |
| Minix         | Z64 V1.2                    | [8796deded0](https://linux-hardware.org/?probe=8796deded0) | May 12, 2022 |
| Dell          | MXG061                      | [119f6dd774](https://linux-hardware.org/?probe=119f6dd774) | May 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [ab553d3a2f](https://linux-hardware.org/?probe=ab553d3a2f) | May 01, 2022 |
| Acer          | Extensa 5220                | [ebbd01171d](https://linux-hardware.org/?probe=ebbd01171d) | May 01, 2022 |
| Acer          | Aspire 1410                 | [703c2ec84a](https://linux-hardware.org/?probe=703c2ec84a) | Apr 21, 2022 |
| Lenovo        | ThinkPad T400 6475E13       | [cd49ac8445](https://linux-hardware.org/?probe=cd49ac8445) | Apr 08, 2022 |
| Dell          | MXG061                      | [9c91bd9487](https://linux-hardware.org/?probe=9c91bd9487) | Apr 06, 2022 |
| Insignia      | NS-P11W7100                 | [daa476af8c](https://linux-hardware.org/?probe=daa476af8c) | Mar 28, 2022 |
| Dell          | MXG071                      | [ac0158dcb9](https://linux-hardware.org/?probe=ac0158dcb9) | Mar 27, 2022 |
| HP            | 15 Notebook PC              | [0f99b7ff76](https://linux-hardware.org/?probe=0f99b7ff76) | Mar 21, 2022 |
| HP            | Compaq CQ45                 | [99286efd08](https://linux-hardware.org/?probe=99286efd08) | Mar 10, 2022 |
| HP            | Laptop 15-dw3xxx            | [2b748962fa](https://linux-hardware.org/?probe=2b748962fa) | Mar 06, 2022 |
| ASUSTek       | 900                         | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Acer          | Aspire A315-53              | [6134bb8cba](https://linux-hardware.org/?probe=6134bb8cba) | Feb 18, 2022 |
| Acer          | Aspire 5600                 | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| HP            | Laptop 15-dw3xxx            | [b596d9fdb1](https://linux-hardware.org/?probe=b596d9fdb1) | Feb 09, 2022 |
| HP            | Compaq nw9440 (EY615ET#A... | [6a5c3254ab](https://linux-hardware.org/?probe=6a5c3254ab) | Jan 30, 2022 |
| HP            | Pavilion dv6500             | [15838ae11b](https://linux-hardware.org/?probe=15838ae11b) | Jan 12, 2022 |
| ASUSTek       | N53Jf                       | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| ASUSTek       | X541SA                      | [26f2eeeefc](https://linux-hardware.org/?probe=26f2eeeefc) | Dec 31, 2021 |
| HP            | Pavilion dv6500             | [978ee4328d](https://linux-hardware.org/?probe=978ee4328d) | Dec 19, 2021 |
| Acer          | Aspire 5600                 | [25b1e50c64](https://linux-hardware.org/?probe=25b1e50c64) | Dec 12, 2021 |
| HP            | Compaq 2510p                | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| HP            | Compaq 2510p                | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [b7306537cc](https://linux-hardware.org/?probe=b7306537cc) | Nov 10, 2021 |
| Acer          | Aspire 5600                 | [7e2da6d3e9](https://linux-hardware.org/?probe=7e2da6d3e9) | Oct 26, 2021 |
| Dell          | MXG061                      | [89a5b20193](https://linux-hardware.org/?probe=89a5b20193) | Oct 10, 2021 |
| Acer          | Swift SF314-56              | [263d6e38b7](https://linux-hardware.org/?probe=263d6e38b7) | Oct 01, 2021 |
| Acer          | Swift SF314-56              | [bb0f894bce](https://linux-hardware.org/?probe=bb0f894bce) | Oct 01, 2021 |
| Dell          | Vostro1710                  | [d50123c66a](https://linux-hardware.org/?probe=d50123c66a) | Sep 01, 2021 |
| Dell          | Inspiron 5452               | [0c9b3ec7a9](https://linux-hardware.org/?probe=0c9b3ec7a9) | Aug 07, 2021 |
| HP            | EliteBook Folio 9470m       | [b2b851f7d2](https://linux-hardware.org/?probe=b2b851f7d2) | Jul 12, 2021 |
| ASUSTek       | X541SA                      | [ed8bb15f60](https://linux-hardware.org/?probe=ed8bb15f60) | Jul 11, 2021 |
| HP            | Laptop 14-cm0xxx            | [5943266aca](https://linux-hardware.org/?probe=5943266aca) | Jun 18, 2021 |
| HP            | Laptop 14-cm0xxx            | [3b4a122b75](https://linux-hardware.org/?probe=3b4a122b75) | Jun 18, 2021 |
| Fujitsu       | LIFEBOOK U747               | [117e8bf660](https://linux-hardware.org/?probe=117e8bf660) | Jun 17, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [a9255b2217](https://linux-hardware.org/?probe=a9255b2217) | Jun 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [58bf661e8d](https://linux-hardware.org/?probe=58bf661e8d) | Apr 15, 2021 |
| ASUSTek       | K50IE                       | [b0bcc6c31c](https://linux-hardware.org/?probe=b0bcc6c31c) | Apr 12, 2021 |
| ASUSTek       | K54LY                       | [dc7d86f51e](https://linux-hardware.org/?probe=dc7d86f51e) | Mar 21, 2021 |
| Acer          | Aspire V5-552               | [7a32a8a1c3](https://linux-hardware.org/?probe=7a32a8a1c3) | Mar 03, 2021 |
| HP            | Compaq 6735b                | [0f2afbc99a](https://linux-hardware.org/?probe=0f2afbc99a) | Feb 18, 2021 |
| Dell          | Inspiron 7559               | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| HP            | Laptop 17-by2xxx            | [729abf0085](https://linux-hardware.org/?probe=729abf0085) | Jan 30, 2021 |
| Acer          | Predator PH317-52           | [1bd05ad341](https://linux-hardware.org/?probe=1bd05ad341) | Jan 24, 2021 |
| HP            | 655                         | [a6913cacf3](https://linux-hardware.org/?probe=a6913cacf3) | Dec 28, 2020 |
| HP            | 655                         | [2a4c81218e](https://linux-hardware.org/?probe=2a4c81218e) | Dec 27, 2020 |
| Toshiba       | Satellite T215D             | [084f254e1f](https://linux-hardware.org/?probe=084f254e1f) | Dec 23, 2020 |
| Toshiba       | Satellite T215D             | [bdb8fe4e55](https://linux-hardware.org/?probe=bdb8fe4e55) | Dec 23, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| ASUSTek       | 1001PX                      | [9f911bde1c](https://linux-hardware.org/?probe=9f911bde1c) | Dec 11, 2020 |
| Acer          | Aspire 5750                 | [ba47872fd5](https://linux-hardware.org/?probe=ba47872fd5) | Dec 02, 2020 |
| Acer          | Aspire 5750                 | [c4216f5d80](https://linux-hardware.org/?probe=c4216f5d80) | Dec 02, 2020 |
| Dell          | Latitude D530               | [4fe18e86ac](https://linux-hardware.org/?probe=4fe18e86ac) | Sep 27, 2020 |
| Acer          | Aspire ES1-511              | [63a7ae1967](https://linux-hardware.org/?probe=63a7ae1967) | Jul 24, 2020 |
| Google        | Chell                       | [cf727e9a6e](https://linux-hardware.org/?probe=cf727e9a6e) | Jul 23, 2020 |
| ASUSTek       | X751LD                      | [2d9ea757d1](https://linux-hardware.org/?probe=2d9ea757d1) | Jul 14, 2020 |
| ASUSTek       | X751LD                      | [1a4ee704d9](https://linux-hardware.org/?probe=1a4ee704d9) | Jul 14, 2020 |
| Lenovo        | 3000 V200 0764A11           | [8492023ae0](https://linux-hardware.org/?probe=8492023ae0) | Jul 13, 2020 |
| TR            | ST Pro-KN                   | [e78b2937ef](https://linux-hardware.org/?probe=e78b2937ef) | Jul 01, 2020 |
| ASUSTek       | N750JK                      | [9102fbcf41](https://linux-hardware.org/?probe=9102fbcf41) | Jun 02, 2020 |
| Samsung       | NC110P/NC108P/NC111P        | [92c219ffb4](https://linux-hardware.org/?probe=92c219ffb4) | May 14, 2020 |
| ASUSTek       | X540YA                      | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Linux Lite 5.8 | 14        | 13.73%  |
| Linux Lite 6.0 | 13        | 12.75%  |
| Linux Lite 6.2 | 12        | 11.76%  |
| Linux Lite 6.4 | 11        | 10.78%  |
| Linux Lite 5.4 | 11        | 10.78%  |
| Linux Lite 6.6 | 9         | 8.82%   |
| Linux Lite 5.2 | 9         | 8.82%   |
| Linux Lite 5.0 | 9         | 8.82%   |
| Linux Lite 5.6 | 7         | 6.86%   |
| Linux Lite 3.8 | 3         | 2.94%   |
| Linux Lite 4.8 | 2         | 1.96%   |
| Linux Lite 4.4 | 1         | 0.98%   |
| Linux Lite 4.2 | 1         | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Linux Lite | 100       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-69-generic | 6         | 5.5%    |
| 5.4.0-40-generic  | 4         | 3.67%   |
| 5.15.0-91-generic | 4         | 3.67%   |
| 5.15.0-76-generic | 4         | 3.67%   |
| 5.4.0-70-generic  | 3         | 2.75%   |
| 5.4.0-52-generic  | 3         | 2.75%   |
| 5.4.0-109-generic | 3         | 2.75%   |
| 5.15.0-33-generic | 3         | 2.75%   |
| 5.4.0-91-generic  | 2         | 1.83%   |
| 5.4.0-90-generic  | 2         | 1.83%   |
| 5.4.0-81-generic  | 2         | 1.83%   |
| 5.4.0-74-generic  | 2         | 1.83%   |
| 5.4.0-58-generic  | 2         | 1.83%   |
| 5.4.0-42-generic  | 2         | 1.83%   |
| 5.4.0-107-generic | 2         | 1.83%   |
| 5.4.0-104-generic | 2         | 1.83%   |
| 5.15.0-88-generic | 2         | 1.83%   |
| 5.15.0-83-generic | 2         | 1.83%   |
| 5.15.0-82-generic | 2         | 1.83%   |
| 5.15.0-60-generic | 2         | 1.83%   |
| 5.15.0-56-generic | 2         | 1.83%   |
| 5.15.0-52-generic | 2         | 1.83%   |
| 5.15.0-48-generic | 2         | 1.83%   |
| 5.15.0-47-generic | 2         | 1.83%   |
| 6.1.0-1.linuxlite | 1         | 0.92%   |
| 6.0.0             | 1         | 0.92%   |
| 5.4.0-96-generic  | 1         | 0.92%   |
| 5.4.0-94-generic  | 1         | 0.92%   |
| 5.4.0-88-generic  | 1         | 0.92%   |
| 5.4.0-77-generic  | 1         | 0.92%   |
| 5.4.0-71-generic  | 1         | 0.92%   |
| 5.4.0-66-generic  | 1         | 0.92%   |
| 5.4.0-65-generic  | 1         | 0.92%   |
| 5.4.0-56-generic  | 1         | 0.92%   |
| 5.4.0-48-generic  | 1         | 0.92%   |
| 5.4.0-33-generic  | 1         | 0.92%   |
| 5.4.0-156-generic | 1         | 0.92%   |
| 5.4.0-152-generic | 1         | 0.92%   |
| 5.4.0-124-generic | 1         | 0.92%   |
| 5.4.0-122-generic | 1         | 0.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 46        | 44.66%  |
| 5.15.0  | 45        | 43.69%  |
| 4.15.0  | 4         | 3.88%   |
| 4.4.0   | 2         | 1.94%   |
| 6.1.0   | 1         | 0.97%   |
| 6.0.0   | 1         | 0.97%   |
| 5.19.0  | 1         | 0.97%   |
| 5.16.0  | 1         | 0.97%   |
| 5.13.0  | 1         | 0.97%   |
| 5.10.0  | 1         | 0.97%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 46        | 44.66%  |
| 5.15    | 45        | 43.69%  |
| 4.15    | 4         | 3.88%   |
| 4.4     | 2         | 1.94%   |
| 6.1     | 1         | 0.97%   |
| 6.0     | 1         | 0.97%   |
| 5.19    | 1         | 0.97%   |
| 5.16    | 1         | 0.97%   |
| 5.13    | 1         | 0.97%   |
| 5.10    | 1         | 0.97%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 98        | 98%     |
| i686   | 2         | 2%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 84        | 84%     |
| GNOME   | 12        | 12%     |
| Unknown | 2         | 2%      |
| Deepin  | 1         | 1%      |
| Budgie  | 1         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 98        | 98%     |
| Tty     | 1         | 1%      |
| Unknown | 1         | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 71        | 69.61%  |
| TDM     | 15        | 14.71%  |
| Unknown | 14        | 13.73%  |
| GDM3    | 1         | 0.98%   |
| GDM     | 1         | 0.98%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 54        | 54%     |
| de_DE | 8         | 8%      |
| fr_FR | 6         | 6%      |
| pl_PL | 5         | 5%      |
| it_IT | 4         | 4%      |
| en_GB | 4         | 4%      |
| ru_RU | 3         | 3%      |
| pt_BR | 3         | 3%      |
| es_ES | 3         | 3%      |
| ru_UA | 2         | 2%      |
| pt_PT | 2         | 2%      |
| zh_CN | 1         | 1%      |
| es_CO | 1         | 1%      |
| en_PH | 1         | 1%      |
| en_IN | 1         | 1%      |
| en_IE | 1         | 1%      |
| en_AU | 1         | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 52        | 51.49%  |
| BIOS | 49        | 48.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 85        | 85%     |
| Overlay | 7         | 7%      |
| Tmpfs   | 5         | 5%      |
| Btrfs   | 2         | 2%      |
| Zfs     | 1         | 1%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 54        | 54%     |
| Unknown | 25        | 25%     |
| MBR     | 21        | 21%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 86        | 85.15%  |
| Yes       | 15        | 14.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 74.26%  |
| Yes       | 26        | 25.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 19        | 19%     |
| ASUSTek Computer    | 18        | 18%     |
| Lenovo              | 15        | 15%     |
| Acer                | 12        | 12%     |
| Dell                | 9         | 9%      |
| Toshiba             | 4         | 4%      |
| Samsung Electronics | 4         | 4%      |
| Fujitsu             | 2         | 2%      |
| Apple               | 2         | 2%      |
| UNOWHY              | 1         | 1%      |
| UMAX                | 1         | 1%      |
| TR                  | 1         | 1%      |
| Thomson             | 1         | 1%      |
| Sony                | 1         | 1%      |
| Pegatron            | 1         | 1%      |
| MSI                 | 1         | 1%      |
| Minix               | 1         | 1%      |
| Medion              | 1         | 1%      |
| Intel               | 1         | 1%      |
| Insignia            | 1         | 1%      |
| Google              | 1         | 1%      |
| Gateway             | 1         | 1%      |
| Fujitsu Siemens     | 1         | 1%      |
| Compaq(Intel)       | 1         | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| UNOWHY Y13G010S4EI                  | 1         | 1%      |
| UMAX VisionBook 12Wi 64G            | 1         | 1%      |
| TR ST Pro-KN                        | 1         | 1%      |
| Toshiba Satellite T215D             | 1         | 1%      |
| Toshiba Satellite P305              | 1         | 1%      |
| Toshiba Satellite C850-C1S          | 1         | 1%      |
| Toshiba QOSMIO X70-B                | 1         | 1%      |
| Thomson PT-NEO14A.2WH32             | 1         | 1%      |
| Sony VGN-SZ750N                     | 1         | 1%      |
| Samsung X420/X520                   | 1         | 1%      |
| Samsung NC110P/NC108P/NC111P        | 1         | 1%      |
| Samsung 905S3G/906S3G/915S3G/9305SG | 1         | 1%      |
| Samsung 530XBB                      | 1         | 1%      |
| Pegatron H36FF                      | 1         | 1%      |
| MSI MS-N014                         | 1         | 1%      |
| Minix Z64                           | 1         | 1%      |
| Medion Akoya E6418 MD99620          | 1         | 1%      |
| Lenovo ThinkPad X240 20AMS1J100     | 1         | 1%      |
| Lenovo ThinkPad T430s 2356H83       | 1         | 1%      |
| Lenovo ThinkPad T400 6475E13        | 1         | 1%      |
| Lenovo ThinkPad L480 20LS001AMC     | 1         | 1%      |
| Lenovo ThinkPad A475 20KMS08300     | 1         | 1%      |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1 | 1         | 1%      |
| Lenovo IdeaPad 330S-15AST 81F9      | 1         | 1%      |
| Lenovo IdeaPad 330-14IGM 81D0       | 1         | 1%      |
| Lenovo IdeaPad 320-15ABR 80XS       | 1         | 1%      |
| Lenovo IdeaPad 310S-14AST 80UL      | 1         | 1%      |
| Lenovo IdeaPad 100-15IBY 80MJ       | 1         | 1%      |
| Lenovo IdeaPad 100-14IBY 80MH       | 1         | 1%      |
| Lenovo IdeaPad 1 15AMN7 82VG        | 1         | 1%      |
| Lenovo G460 20041                   | 1         | 1%      |
| Lenovo 3000 V200 0764A11            | 1         | 1%      |
| Intel Jasper Lake Client Platform   | 1         | 1%      |
| Insignia NS-P11W7100                | 1         | 1%      |
| HP Stream Notebook PC 13            | 1         | 1%      |
| HP Presario V6000 (RG289UA#ABA)     | 1         | 1%      |
| HP Pavilion g4                      | 1         | 1%      |
| HP Pavilion dv6500                  | 1         | 1%      |
| HP Laptop 17-by2xxx                 | 1         | 1%      |
| HP Laptop 15-dw3xxx                 | 1         | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo IdeaPad          | 8         | 8%      |
| Acer Aspire             | 8         | 8%      |
| Lenovo ThinkPad         | 5         | 5%      |
| HP Laptop               | 5         | 5%      |
| HP Compaq               | 5         | 5%      |
| Toshiba Satellite       | 3         | 3%      |
| HP EliteBook            | 3         | 3%      |
| Dell Latitude           | 3         | 3%      |
| Dell Inspiron           | 3         | 3%      |
| ASUS VivoBook           | 3         | 3%      |
| HP Pavilion             | 2         | 2%      |
| UNOWHY Y13G010S4EI      | 1         | 1%      |
| UMAX VisionBook         | 1         | 1%      |
| TR ST                   | 1         | 1%      |
| Toshiba QOSMIO          | 1         | 1%      |
| Thomson PT-NEO14A.2WH32 | 1         | 1%      |
| Sony VGN-SZ750N         | 1         | 1%      |
| Samsung X420            | 1         | 1%      |
| Samsung NC110P          | 1         | 1%      |
| Samsung 905S3G          | 1         | 1%      |
| Samsung 530XBB          | 1         | 1%      |
| Pegatron H36FF          | 1         | 1%      |
| MSI MS-N014             | 1         | 1%      |
| Minix Z64               | 1         | 1%      |
| Medion Akoya            | 1         | 1%      |
| Lenovo G460             | 1         | 1%      |
| Lenovo 3000             | 1         | 1%      |
| Intel Jasper            | 1         | 1%      |
| Insignia NS-P11W7100    | 1         | 1%      |
| HP Stream               | 1         | 1%      |
| HP Presario             | 1         | 1%      |
| HP 655                  | 1         | 1%      |
| HP 15                   | 1         | 1%      |
| Google Chell            | 1         | 1%      |
| Gateway Sonic-C         | 1         | 1%      |
| Fujitsu Siemens ESPRIMO | 1         | 1%      |
| Fujitsu LIFEBOOK        | 1         | 1%      |
| Fujitsu FMVNQ8P6        | 1         | 1%      |
| Dell Vostro1710         | 1         | 1%      |
| Dell MXG071             | 1         | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 10        | 10%     |
| 2010 | 10        | 10%     |
| 2008 | 9         | 9%      |
| 2012 | 8         | 8%      |
| 2007 | 8         | 8%      |
| 2015 | 7         | 7%      |
| 2014 | 7         | 7%      |
| 2013 | 6         | 6%      |
| 2011 | 6         | 6%      |
| 2017 | 5         | 5%      |
| 2016 | 5         | 5%      |
| 2022 | 4         | 4%      |
| 2020 | 4         | 4%      |
| 2019 | 4         | 4%      |
| 2021 | 2         | 2%      |
| 2006 | 2         | 2%      |
| 2023 | 1         | 1%      |
| 2009 | 1         | 1%      |
| 2004 | 1         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 100       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 93        | 93%     |
| Enabled  | 7         | 7%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 99        | 99%     |
| Yes  | 1         | 1%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 39        | 39%     |
| 1.01-2.0   | 20        | 20%     |
| 4.01-8.0   | 17        | 17%     |
| 16.01-24.0 | 9         | 9%      |
| 8.01-16.0  | 8         | 8%      |
| 0.51-1.0   | 4         | 4%      |
| 2.01-3.0   | 2         | 2%      |
| 32.01-64.0 | 1         | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 52        | 50.49%  |
| 2.01-3.0  | 23        | 22.33%  |
| 0.51-1.0  | 14        | 13.59%  |
| 3.01-4.0  | 8         | 7.77%   |
| 0.01-0.5  | 3         | 2.91%   |
| 4.01-8.0  | 2         | 1.94%   |
| 8.01-16.0 | 1         | 0.97%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 79        | 79%     |
| 2      | 20        | 20%     |
| 3      | 1         | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 56%     |
| Yes       | 44        | 44%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 83%     |
| No        | 17        | 17%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 98%     |
| No        | 2         | 2%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 68.32%  |
| No        | 32        | 31.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 14        | 14%     |
| Germany     | 10        | 10%     |
| France      | 8         | 8%      |
| Brazil      | 7         | 7%      |
| UK          | 5         | 5%      |
| Romania     | 5         | 5%      |
| Italy       | 5         | 5%      |
| Ukraine     | 4         | 4%      |
| Russia      | 4         | 4%      |
| Poland      | 4         | 4%      |
| Spain       | 3         | 3%      |
| Turkey      | 2         | 2%      |
| Portugal    | 2         | 2%      |
| Philippines | 2         | 2%      |
| Netherlands | 2         | 2%      |
| Indonesia   | 2         | 2%      |
| Australia   | 2         | 2%      |
| Venezuela   | 1         | 1%      |
| Thailand    | 1         | 1%      |
| Sweden      | 1         | 1%      |
| Slovakia    | 1         | 1%      |
| Serbia      | 1         | 1%      |
| Myanmar     | 1         | 1%      |
| Morocco     | 1         | 1%      |
| Mexico      | 1         | 1%      |
| Ireland     | 1         | 1%      |
| Iran        | 1         | 1%      |
| India       | 1         | 1%      |
| Guadeloupe  | 1         | 1%      |
| Greece      | 1         | 1%      |
| El Salvador | 1         | 1%      |
| Czechia     | 1         | 1%      |
| Colombia    | 1         | 1%      |
| Chile       | 1         | 1%      |
| Canada      | 1         | 1%      |
| Argentina   | 1         | 1%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Valencia               | 2         | 1.94%   |
| Sydney                 | 2         | 1.94%   |
| Paris                  | 2         | 1.94%   |
| Pabianice              | 2         | 1.94%   |
| Odessa                 | 2         | 1.94%   |
| Moscow                 | 2         | 1.94%   |
| Frankfurt am Main      | 2         | 1.94%   |
| Żywiec                | 1         | 0.97%   |
| Yangon                 | 1         | 0.97%   |
| Würzburg              | 1         | 0.97%   |
| Wiesbaden              | 1         | 0.97%   |
| Washington             | 1         | 0.97%   |
| Warsaw                 | 1         | 0.97%   |
| Wahroonga              | 1         | 0.97%   |
| Voluntari              | 1         | 0.97%   |
| Vinnytsia              | 1         | 0.97%   |
| Villingen-Schwenningen | 1         | 0.97%   |
| Varennes-les-Narcy     | 1         | 0.97%   |
| Tucape                 | 1         | 0.97%   |
| The Hague              | 1         | 0.97%   |
| Teresina               | 1         | 0.97%   |
| Tekirdağ              | 1         | 0.97%   |
| Tarragona              | 1         | 0.97%   |
| Tamm                   | 1         | 0.97%   |
| Svidník               | 1         | 0.97%   |
| Surabaya               | 1         | 0.97%   |
| Subotica               | 1         | 0.97%   |
| Studenka               | 1         | 0.97%   |
| Strasbourg             | 1         | 0.97%   |
| St. Petersburg         | 1         | 0.97%   |
| South Shields          | 1         | 0.97%   |
| Shadrinsk              | 1         | 0.97%   |
| Sartrouville           | 1         | 0.97%   |
| Sao Paulo              | 1         | 0.97%   |
| Santiago del Estero    | 1         | 0.97%   |
| Salerno                | 1         | 0.97%   |
| Sabadell               | 1         | 0.97%   |
| Roswell                | 1         | 0.97%   |
| Randolph               | 1         | 0.97%   |
| Queretaro              | 1         | 0.97%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 16.96%  |
| WDC                 | 15        | 19     | 13.39%  |
| Toshiba             | 12        | 13     | 10.71%  |
| Samsung Electronics | 12        | 15     | 10.71%  |
| Unknown             | 8         | 11     | 7.14%   |
| Micron Technology   | 6         | 7      | 5.36%   |
| Kingston            | 6         | 6      | 5.36%   |
| Hitachi             | 6         | 6      | 5.36%   |
| HGST                | 6         | 6      | 5.36%   |
| SanDisk             | 4         | 4      | 3.57%   |
| SK hynix            | 3         | 4      | 2.68%   |
| GOODRAM             | 2         | 2      | 1.79%   |
| Crucial             | 2         | 2      | 1.79%   |
| China               | 2         | 2      | 1.79%   |
| Apple               | 2         | 2      | 1.79%   |
| Phison              | 1         | 1      | 0.89%   |
| LITEON              | 1         | 1      | 0.89%   |
| Intel               | 1         | 1      | 0.89%   |
| Fujitsu             | 1         | 1      | 0.89%   |
| ASUS-PHISON         | 1         | 2      | 0.89%   |
| ASMT                | 1         | 1      | 0.89%   |
| A-DATA Technology   | 1         | 1      | 0.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                | 3         | 2.56%   |
| Toshiba MQ01ABF050 500GB              | 3         | 2.56%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 2.56%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 1.71%   |
| Unknown DA4064  64GB                  | 2         | 1.71%   |
| Toshiba MQ04ABF100 1TB                | 2         | 1.71%   |
| Toshiba MQ01ABD100 1TB                | 2         | 1.71%   |
| Seagate ST9320325AS 320GB             | 2         | 1.71%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 1.71%   |
| Samsung SSD 850 EVO 250GB             | 2         | 1.71%   |
| Samsung MZVLB256HAHQ-000L7 256GB      | 2         | 1.71%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD   | 2         | 1.71%   |
| Hitachi HTS543232A7A384 320GB         | 2         | 1.71%   |
| HGST HTS725050A7E630 500GB            | 2         | 1.71%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 0.85%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.85%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 0.85%   |
| WDC WD5000LPVX-80V0TT0 500GB          | 1         | 0.85%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 0.85%   |
| WDC WD2500BEVS-00UST0 250GB           | 1         | 0.85%   |
| WDC WD2500BEVE-00A0HT0 250GB          | 1         | 0.85%   |
| WDC WD1600BEVT-22A23T0 160GB          | 1         | 0.85%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.85%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.85%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 0.85%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 0.85%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB  | 1         | 0.85%   |
| Unknown SN64G  64GB                   | 1         | 0.85%   |
| Unknown SLD64G  64GB                  | 1         | 0.85%   |
| Unknown SD64G  64GB                   | 1         | 0.85%   |
| Unknown SD16G  16GB                   | 1         | 0.85%   |
| Unknown NCard  32GB                   | 1         | 0.85%   |
| Unknown MMC Card  128GB               | 1         | 0.85%   |
| Toshiba THNSNJ128GCSU 128GB SSD       | 1         | 0.85%   |
| Toshiba MQ01ABD050 500GB              | 1         | 0.85%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 0.85%   |
| Toshiba MK3265GSX 320GB               | 1         | 0.85%   |
| Toshiba MK1011GAH 100GB               | 1         | 0.85%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 0.85%   |
| SK hynix HFM128GDHTNG-8310A 128GB     | 1         | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 33.93%  |
| Toshiba             | 11        | 12     | 19.64%  |
| WDC                 | 10        | 13     | 17.86%  |
| Hitachi             | 6         | 6      | 10.71%  |
| HGST                | 6         | 6      | 10.71%  |
| Samsung Electronics | 2         | 3      | 3.57%   |
| Fujitsu             | 1         | 1      | 1.79%   |
| ASMT                | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 14.29%  |
| Kingston            | 5         | 5      | 14.29%  |
| Micron Technology   | 4         | 5      | 11.43%  |
| WDC                 | 3         | 3      | 8.57%   |
| SanDisk             | 3         | 3      | 8.57%   |
| GOODRAM             | 2         | 2      | 5.71%   |
| Crucial             | 2         | 2      | 5.71%   |
| China               | 2         | 2      | 5.71%   |
| Apple               | 2         | 2      | 5.71%   |
| Toshiba             | 1         | 1      | 2.86%   |
| SK hynix            | 1         | 2      | 2.86%   |
| Phison              | 1         | 1      | 2.86%   |
| LITEON              | 1         | 1      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |
| ASUS-PHISON         | 1         | 2      | 2.86%   |
| A-DATA Technology   | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 55        | 64     | 50.46%  |
| SSD  | 34        | 38     | 31.19%  |
| MMC  | 10        | 13     | 9.17%   |
| NVMe | 10        | 14     | 9.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 81        | 100    | 78.64%  |
| NVMe | 10        | 14     | 9.71%   |
| MMC  | 10        | 13     | 9.71%   |
| SAS  | 2         | 2      | 1.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 77     | 71.59%  |
| 0.51-1.0   | 24        | 24     | 27.27%  |
| 1.01-2.0   | 1         | 1      | 1.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 38.83%  |
| 251-500        | 25        | 24.27%  |
| 51-100         | 13        | 12.62%  |
| 501-1000       | 11        | 10.68%  |
| 1-20           | 7         | 6.8%    |
| 21-50          | 6         | 5.83%   |
| More than 3000 | 1         | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 53        | 51.46%  |
| 21-50     | 25        | 24.27%  |
| 101-250   | 13        | 12.62%  |
| 51-100    | 11        | 10.68%  |
| 2001-3000 | 1         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 5%      |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 5%      |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 5%      |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 5%      |
| Toshiba MK3265GSX 320GB                        | 1         | 1      | 5%      |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 5%      |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 5%      |
| Seagate ST9320320AS 320GB                      | 1         | 1      | 5%      |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 5%      |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 5%      |
| Seagate ST1000LM048-2E7172 1TB                 | 1         | 1      | 5%      |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 5%      |
| SanDisk SSD PLUS 120GB                         | 1         | 1      | 5%      |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 5%      |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 5%      |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 5%      |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 5%      |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 5%      |
| Apple SSD SM128C 121GB                         | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 40%     |
| WDC                 | 3         | 3      | 15%     |
| Toshiba             | 2         | 2      | 10%     |
| Hitachi             | 2         | 2      | 10%     |
| SanDisk             | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| Micron Technology   | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |
| Apple               | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 50%     |
| WDC                 | 2         | 2      | 12.5%   |
| Toshiba             | 2         | 2      | 12.5%   |
| Hitachi             | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 80%     |
| SSD  | 4         | 4      | 20%     |

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
| Works    | 46        | 54     | 44.66%  |
| Detected | 38        | 55     | 36.89%  |
| Malfunc  | 19        | 20     | 18.45%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 74        | 72.55%  |
| AMD                         | 13        | 12.75%  |
| Samsung Electronics         | 5         | 4.9%    |
| Nvidia                      | 3         | 2.94%   |
| SanDisk                     | 2         | 1.96%   |
| Micron Technology           | 2         | 1.96%   |
| SK hynix                    | 1         | 0.98%   |
| Marvell Technology Group    | 1         | 0.98%   |
| Kingston Technology Company | 1         | 0.98%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 10%     |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 7.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 6.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 4.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 3.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 4         | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 3.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 3.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 3.33%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 2.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 2.5%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 2.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.67%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 1.67%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.67%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 1.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.67%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.83%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 0.83%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.83%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.83%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.83%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.83%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.83%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.83%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 1         | 0.83%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 1         | 0.83%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.83%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                   | 1         | 0.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 0.83%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 0.83%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 76        | 68.47%  |
| IDE  | 19        | 17.12%  |
| NVMe | 10        | 9.01%   |
| RAID | 6         | 5.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 84        | 84%     |
| AMD    | 16        | 16%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2%      |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 2%      |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 2%      |
| Intel Core 2 CPU T7600 @ 2.33GHz              | 2         | 2%      |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 2%      |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 2%      |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 2%      |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 2%      |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 2%      |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1%      |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 1%      |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1%      |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 1%      |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 1%      |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 1%      |
| Intel Genuine CPU T2050 @ 1.60GHz             | 1         | 1%      |
| Intel Core m7-6Y75 CPU @ 1.20GHz              | 1         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1%      |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1%      |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1%      |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 1%      |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 1%      |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 1%      |
| Intel Core i5-5257U CPU @ 2.70GHz             | 1         | 1%      |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 1%      |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1%      |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 1%      |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1%      |
| Intel Core i5-3427U CPU @ 1.80GHz             | 1         | 1%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1%      |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1%      |
| Intel Core i5-2467M CPU @ 1.60GHz             | 1         | 1%      |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1%      |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1%      |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1%      |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 1%      |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 1%      |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 20%     |
| Intel Core 2 Duo        | 12        | 12%     |
| Intel Celeron           | 12        | 12%     |
| Intel Core i7           | 7         | 7%      |
| Intel Core i3           | 7         | 7%      |
| Intel Atom              | 7         | 7%      |
| Other                   | 6         | 6%      |
| Intel Pentium           | 5         | 5%      |
| Intel Core 2            | 3         | 3%      |
| AMD E2                  | 3         | 3%      |
| Intel Genuine           | 2         | 2%      |
| AMD A8                  | 2         | 2%      |
| Intel Pentium Silver    | 1         | 1%      |
| Intel Pentium Dual-Core | 1         | 1%      |
| Intel Core m7           | 1         | 1%      |
| Intel Celeron M         | 1         | 1%      |
| Intel Celeron Dual-Core | 1         | 1%      |
| AMD Turion Dual-Core    | 1         | 1%      |
| AMD Turion 64 X2 Mobile | 1         | 1%      |
| AMD Ryzen 5             | 1         | 1%      |
| AMD Ryzen 3             | 1         | 1%      |
| AMD Quad-Core           | 1         | 1%      |
| AMD Athlon II Neo       | 1         | 1%      |
| AMD A6                  | 1         | 1%      |
| AMD A12                 | 1         | 1%      |
| AMD A10                 | 1         | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 66        | 66%     |
| 4      | 26        | 26%     |
| 1      | 5         | 5%      |
| 14     | 1         | 1%      |
| 10     | 1         | 1%      |
| 6      | 1         | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 100       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 53%     |
| 2      | 47        | 47%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 98        | 98%     |
| 32-bit         | 2         | 2%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 12.75%  |
| 0x206a7    | 8         | 7.84%   |
| 0x306a9    | 6         | 5.88%   |
| 0x30678    | 6         | 5.88%   |
| 0x1067a    | 6         | 5.88%   |
| 0x40651    | 5         | 4.9%    |
| 0x706a1    | 4         | 3.92%   |
| 0x6fd      | 4         | 3.92%   |
| 0x20655    | 3         | 2.94%   |
| 0x06006705 | 3         | 2.94%   |
| 0x906c0    | 2         | 1.96%   |
| 0x806ea    | 2         | 1.96%   |
| 0x806e9    | 2         | 1.96%   |
| 0x806c1    | 2         | 1.96%   |
| 0x6fb      | 2         | 1.96%   |
| 0x6f6      | 2         | 1.96%   |
| 0x406e3    | 2         | 1.96%   |
| 0x406c4    | 2         | 1.96%   |
| 0x406c3    | 2         | 1.96%   |
| 0x306c3    | 2         | 1.96%   |
| 0x106ca    | 2         | 1.96%   |
| 0x10676    | 2         | 1.96%   |
| 0x906ea    | 1         | 0.98%   |
| 0x906e9    | 1         | 0.98%   |
| 0x906a4    | 1         | 0.98%   |
| 0x906a3    | 1         | 0.98%   |
| 0x806ec    | 1         | 0.98%   |
| 0x806eb    | 1         | 0.98%   |
| 0x6d8      | 1         | 0.98%   |
| 0x506e3    | 1         | 0.98%   |
| 0x506c9    | 1         | 0.98%   |
| 0x306d4    | 1         | 0.98%   |
| 0x30661    | 1         | 0.98%   |
| 0x08a00006 | 1         | 0.98%   |
| 0x07030105 | 1         | 0.98%   |
| 0x06006704 | 1         | 0.98%   |
| 0x0600611a | 1         | 0.98%   |
| 0x06006118 | 1         | 0.98%   |
| 0x06001119 | 1         | 0.98%   |
| 0x05000119 | 1         | 0.98%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Silvermont       | 11        | 11%     |
| Penryn           | 10        | 10%     |
| Core             | 9         | 9%      |
| SandyBridge      | 8         | 8%      |
| KabyLake         | 8         | 8%      |
| Haswell          | 7         | 7%      |
| IvyBridge        | 6         | 6%      |
| Excavator        | 6         | 6%      |
| Westmere         | 5         | 5%      |
| Goldmont plus    | 4         | 4%      |
| Skylake          | 3         | 3%      |
| Bonnell          | 3         | 3%      |
| Tremont          | 2         | 2%      |
| TigerLake        | 2         | 2%      |
| Puma             | 2         | 2%      |
| P6               | 2         | 2%      |
| Alderlake Hybrid | 2         | 2%      |
| Zen+             | 1         | 1%      |
| Piledriver       | 1         | 1%      |
| K8 Hammer        | 1         | 1%      |
| K8 & K10 hybrid  | 1         | 1%      |
| K10              | 1         | 1%      |
| Jaguar           | 1         | 1%      |
| Goldmont         | 1         | 1%      |
| Broadwell        | 1         | 1%      |
| Bobcat           | 1         | 1%      |
| Unknown          | 1         | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 73        | 65.18%  |
| Nvidia | 21        | 18.75%  |
| AMD    | 18        | 16.07%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 5%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 5%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 4.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 4.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 4.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 4.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 4.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 3.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 2.5%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.67%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.67%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.67%   |
| Intel HD Graphics 620                                                                    | 2         | 1.67%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.67%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.67%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.67%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.83%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.83%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.83%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.83%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.83%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.83%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.83%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 0.83%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 0.83%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.83%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 0.83%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 0.83%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 0.83%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 0.83%   |
| Nvidia G71M [GeForce Go 7950 GTX]                                                        | 1         | 0.83%   |
| Nvidia G71GLM [Quadro FX 1500M]                                                          | 1         | 0.83%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 1         | 0.83%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 0.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 61        | 61%     |
| 1 x AMD        | 15        | 15%     |
| Intel + Nvidia | 11        | 11%     |
| 1 x Nvidia     | 10        | 10%     |
| 2 x AMD        | 2         | 2%      |
| Intel + AMD    | 1         | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 90        | 89.11%  |
| Proprietary | 9         | 8.91%   |
| Unknown     | 2         | 1.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 72.28%  |
| 0.01-0.5   | 15        | 14.85%  |
| 0.51-1.0   | 6         | 5.94%   |
| 3.01-4.0   | 3         | 2.97%   |
| 1.01-2.0   | 3         | 2.97%   |
| 5.01-6.0   | 1         | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 16        | 15.24%  |
| Samsung Electronics     | 14        | 13.33%  |
| LG Display              | 13        | 12.38%  |
| Chimei Innolux          | 13        | 12.38%  |
| BOE                     | 12        | 11.43%  |
| Chi Mei Optoelectronics | 8         | 7.62%   |
| LG Philips              | 3         | 2.86%   |
| Goldstar                | 3         | 2.86%   |
| CPT                     | 3         | 2.86%   |
| PANDA                   | 2         | 1.9%    |
| Lenovo                  | 2         | 1.9%    |
| InfoVision              | 2         | 1.9%    |
| HannStar                | 2         | 1.9%    |
| Apple                   | 2         | 1.9%    |
| ViewSonic               | 1         | 0.95%   |
| Sony                    | 1         | 0.95%   |
| Seiko/Epson             | 1         | 0.95%   |
| SANYO                   | 1         | 0.95%   |
| OEM                     | 1         | 0.95%   |
| Hewlett-Packard         | 1         | 0.95%   |
| eMachines               | 1         | 0.95%   |
| BenQ                    | 1         | 0.95%   |
| Belinea                 | 1         | 0.95%   |
| Unknown                 | 1         | 0.95%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 2.86%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.9%    |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                  | 2         | 1.9%    |
| ViewSonic VA2026w VSC5020 1680x1050 433x271mm 20.1-inch               | 1         | 0.95%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                    | 1         | 0.95%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.95%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.95%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.95%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1         | 0.95%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 0.95%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.95%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                       | 1         | 0.95%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch           | 1         | 0.95%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch           | 1         | 0.95%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD0505 1366x768 344x194mm 15.5-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD03E3 1366x768 310x174mm 14.0-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD038C 1366x768 256x144mm 11.6-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch           | 1         | 0.95%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 48        | 45.71%  |
| 1920x1080 (FHD)    | 25        | 23.81%  |
| 1280x800 (WXGA)    | 9         | 8.57%   |
| 1920x1200 (WUXGA)  | 6         | 5.71%   |
| 1600x900 (HD+)     | 4         | 3.81%   |
| 3840x2160 (4K)     | 2         | 1.9%    |
| 1680x1050 (WSXGA+) | 2         | 1.9%    |
| 1440x900 (WXGA+)   | 2         | 1.9%    |
| 1024x600           | 2         | 1.9%    |
| 3840x2400          | 1         | 0.95%   |
| 1920x540           | 1         | 0.95%   |
| 1360x768           | 1         | 0.95%   |
| 1280x1024 (SXGA)   | 1         | 0.95%   |
| Unknown            | 1         | 0.95%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 35        | 33.33%  |
| 14      | 14        | 13.33%  |
| 13      | 14        | 13.33%  |
| 17      | 11        | 10.48%  |
| 11      | 6         | 5.71%   |
| 12      | 5         | 4.76%   |
| 24      | 3         | 2.86%   |
| 23      | 3         | 2.86%   |
| 16      | 3         | 2.86%   |
| Unknown | 3         | 2.86%   |
| 21      | 2         | 1.9%    |
| 10      | 2         | 1.9%    |
| 65      | 1         | 0.95%   |
| 46      | 1         | 0.95%   |
| 20      | 1         | 0.95%   |
| 19      | 1         | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 60        | 57.69%  |
| 201-300     | 17        | 16.35%  |
| 351-400     | 12        | 11.54%  |
| 501-600     | 6         | 5.77%   |
| 401-500     | 4         | 3.85%   |
| Unknown     | 3         | 2.88%   |
| 1001-1500   | 2         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 77        | 78.57%  |
| 16/10   | 17        | 17.35%  |
| Unknown | 2         | 2.04%   |
| 6/5     | 1         | 1.02%   |
| 3/2     | 1         | 1.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 33.33%  |
| 81-90          | 24        | 22.86%  |
| 201-250        | 7         | 6.67%   |
| 121-130        | 7         | 6.67%   |
| 51-60          | 6         | 5.71%   |
| 131-140        | 6         | 5.71%   |
| 61-70          | 5         | 4.76%   |
| 71-80          | 4         | 3.81%   |
| Unknown        | 3         | 2.86%   |
| 41-50          | 2         | 1.9%    |
| 151-200        | 2         | 1.9%    |
| More than 1000 | 1         | 0.95%   |
| 251-300        | 1         | 0.95%   |
| 111-120        | 1         | 0.95%   |
| 501-1000       | 1         | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 43        | 42.16%  |
| 121-160       | 31        | 30.39%  |
| 51-100        | 19        | 18.63%  |
| 161-240       | 3         | 2.94%   |
| Unknown       | 3         | 2.94%   |
| More than 240 | 2         | 1.96%   |
| 1-50          | 1         | 0.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 88        | 87.13%  |
| 2     | 11        | 10.89%  |
| 0     | 2         | 1.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 54        | 35.06%  |
| Intel                             | 37        | 24.03%  |
| Qualcomm Atheros                  | 33        | 21.43%  |
| Broadcom                          | 10        | 6.49%   |
| Broadcom Limited                  | 4         | 2.6%    |
| Ralink                            | 3         | 1.95%   |
| Sierra Wireless                   | 2         | 1.3%    |
| Nvidia                            | 2         | 1.3%    |
| Marvell Technology Group          | 2         | 1.3%    |
| Ralink Technology                 | 1         | 0.65%   |
| OPPO Electronics                  | 1         | 0.65%   |
| JMicron Technology                | 1         | 0.65%   |
| Ericsson Business Mobile Networks | 1         | 0.65%   |
| Dell                              | 1         | 0.65%   |
| D-Link                            | 1         | 0.65%   |
| ASIX Electronics                  | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 28        | 14.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 16        | 8.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 4.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 3.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.16%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 3.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 2.11%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 1.58%   |
| Intel Wireless 7260                                                     | 3         | 1.58%   |
| Intel Wireless 3165                                                     | 3         | 1.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.05%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.05%   |
| Intel Wireless 3160                                                     | 2         | 1.05%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.05%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.05%   |
| Sierra Wireless EM7455                                                  | 1         | 0.53%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.53%   |
| Realtek USB 10/100 LAN                                                  | 1         | 0.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.53%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.53%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.53%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 33.65%  |
| Qualcomm Atheros      | 30        | 28.85%  |
| Realtek Semiconductor | 24        | 23.08%  |
| Broadcom              | 5         | 4.81%   |
| Ralink                | 3         | 2.88%   |
| Sierra Wireless       | 2         | 1.92%   |
| Broadcom Limited      | 2         | 1.92%   |
| Ralink Technology     | 1         | 0.96%   |
| Dell                  | 1         | 0.96%   |
| D-Link                | 1         | 0.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 8         | 7.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 8         | 7.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 5.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 6         | 5.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 6         | 5.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 5         | 4.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 3.81%   |
| Intel Wireless 7260                                                                           | 3         | 2.86%   |
| Intel Wireless 3165                                                                           | 3         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 1.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 2         | 1.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2         | 1.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 2         | 1.9%    |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.9%    |
| Intel Wireless 3160                                                                           | 2         | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 2         | 1.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.9%    |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 1.9%    |
| Sierra Wireless EM7455                                                                        | 1         | 0.95%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.95%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.95%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 0.95%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.95%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.95%   |
| Realtek 802.11ac NIC                                                                          | 1         | 0.95%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.95%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.95%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.95%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 0.95%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 0.95%   |
| Intel Wireless 7265                                                                           | 1         | 0.95%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 47        | 56.63%  |
| Intel                    | 13        | 15.66%  |
| Qualcomm Atheros         | 9         | 10.84%  |
| Broadcom                 | 5         | 6.02%   |
| Nvidia                   | 2         | 2.41%   |
| Marvell Technology Group | 2         | 2.41%   |
| Broadcom Limited         | 2         | 2.41%   |
| OPPO Electronics         | 1         | 1.2%    |
| JMicron Technology       | 1         | 1.2%    |
| ASIX Electronics         | 1         | 1.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 16        | 19.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 4.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 3.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 2.38%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 2.38%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 2.38%   |
| Realtek USB 10/100 LAN                                                 | 1         | 1.19%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1.19%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.19%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.19%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1         | 1.19%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.19%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.19%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 1         | 1.19%   |
| Nvidia MCP77 Ethernet                                                  | 1         | 1.19%   |
| Nvidia MCP51 Ethernet Controller                                       | 1         | 1.19%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.19%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 1         | 1.19%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.19%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.19%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.19%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 1.19%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.19%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express               | 1         | 1.19%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 1.19%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.19%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 1.19%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.19%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express       | 1         | 1.19%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express       | 1         | 1.19%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 53.85%  |
| Ethernet | 83        | 45.6%   |
| Modem    | 1         | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 78.85%  |
| Ethernet | 22        | 21.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 79        | 79%     |
| 1     | 18        | 18%     |
| 0     | 3         | 3%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 75.25%  |
| Yes  | 25        | 24.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 27.54%  |
| Realtek Semiconductor           | 15        | 21.74%  |
| Qualcomm Atheros Communications | 5         | 7.25%   |
| IMC Networks                    | 5         | 7.25%   |
| Hewlett-Packard                 | 5         | 7.25%   |
| Lite-On Technology              | 4         | 5.8%    |
| Broadcom                        | 4         | 5.8%    |
| Dell                            | 2         | 2.9%    |
| Chicony Electronics             | 2         | 2.9%    |
| Cambridge Silicon Radio         | 2         | 2.9%    |
| Apple                           | 2         | 2.9%    |
| Toshiba                         | 1         | 1.45%   |
| Ralink                          | 1         | 1.45%   |
| Foxconn / Hon Hai               | 1         | 1.45%   |
| ASUSTek Computer                | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 15.94%  |
| Realtek Bluetooth Radio                             | 10        | 14.49%  |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.35%   |
| IMC Networks Bluetooth Device                       | 3         | 4.35%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 4.35%   |
| Intel Bluetooth Device                              | 2         | 2.9%    |
| Intel AX201 Bluetooth                               | 2         | 2.9%    |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.9%    |
| Dell Wireless 355 Bluetooth                         | 2         | 2.9%    |
| Chicony Bluetooth Radio                             | 2         | 2.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.9%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 2.9%    |
| Toshiba Askey Bluetooth Module                      | 1         | 1.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.45%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.45%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.45%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 1.45%   |
| Lite-On Bluetooth Device                            | 1         | 1.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.45%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.45%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.45%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.45%   |
| Broadcom HP Portable Valentine                      | 1         | 1.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.45%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.45%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 79        | 71.82%  |
| AMD                     | 17        | 15.45%  |
| Nvidia                  | 10        | 9.09%   |
| Logitech                | 1         | 0.91%   |
| Blue Microphones        | 1         | 0.91%   |
| BEHRINGER International | 1         | 0.91%   |
| ATI Technologies        | 1         | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 6.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 6.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 5.3%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 4.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 4.55%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 4.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 3.79%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 3.79%   |
| AMD FCH Azalia Controller                                                                         | 5         | 3.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 3.03%   |
| AMD High Definition Audio Controller                                                              | 3         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.52%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.52%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.76%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.76%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.76%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.76%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.76%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.76%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.76%   |
| Nvidia Audio device                                                                               | 1         | 0.76%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.76%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.76%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.76%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 25.81%  |
| SK hynix            | 19        | 20.43%  |
| Kingston            | 10        | 10.75%  |
| Unknown             | 9         | 9.68%   |
| Micron Technology   | 9         | 9.68%   |
| Elpida              | 4         | 4.3%    |
| Unknown             | 4         | 4.3%    |
| Nanya Technology    | 3         | 3.23%   |
| A-DATA Technology   | 3         | 3.23%   |
| Unknown (ABCD)      | 2         | 2.15%   |
| Ramaxel Technology  | 2         | 2.15%   |
| Transcend           | 1         | 1.08%   |
| Smart               | 1         | 1.08%   |
| Qimonda             | 1         | 1.08%   |
| G.Skill             | 1         | 1.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 4         | 4.17%   |
| Unknown                                                             | 4         | 4.17%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 3.13%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 2.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 2.08%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 2.08%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s               | 2         | 2.08%   |
| Kingston RAM ACR256X64D3S1333C9 2GB SODIMM DDR3 1333MT/s            | 2         | 2.08%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                          | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                          | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                               | 1         | 1.04%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                      | 1         | 1.04%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                       | 1         | 1.04%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.04%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s               | 1         | 1.04%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 1.04%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 1         | 1.04%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                       | 1         | 1.04%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s               | 1         | 1.04%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s             | 1         | 1.04%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.04%   |
| SK hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s                | 1         | 1.04%   |
| SK hynix RAM HMP125S6EFR8C-Y5 2GB SODIMM DDR2 667MT/s               | 1         | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 1.04%   |
| Samsung RAM Module 6GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 1.04%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 1.04%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 1.04%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 1         | 1.04%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s               | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 35        | 42.68%  |
| DDR4    | 18        | 21.95%  |
| DDR2    | 12        | 14.63%  |
| SDRAM   | 6         | 7.32%   |
| LPDDR4  | 6         | 7.32%   |
| Unknown | 2         | 2.44%   |
| LPDDR5  | 1         | 1.22%   |
| DRAM    | 1         | 1.22%   |
| DDR     | 1         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 97.47%  |
| Row Of Chips | 1         | 1.27%   |
| DIMM         | 1         | 1.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 29        | 32.58%  |
| 4096  | 26        | 29.21%  |
| 8192  | 20        | 22.47%  |
| 1024  | 9         | 10.11%  |
| 16384 | 3         | 3.37%   |
| 32768 | 1         | 1.12%   |
| 6144  | 1         | 1.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 28        | 32.56%  |
| 2667    | 9         | 10.47%  |
| 667     | 9         | 10.47%  |
| 3200    | 8         | 9.3%    |
| 3266    | 4         | 4.65%   |
| 2400    | 4         | 4.65%   |
| 1333    | 4         | 4.65%   |
| 4199    | 3         | 3.49%   |
| 2048    | 3         | 3.49%   |
| 975     | 3         | 3.49%   |
| 1334    | 2         | 2.33%   |
| 1066    | 2         | 2.33%   |
| 800     | 2         | 2.33%   |
| 6400    | 1         | 1.16%   |
| 4267    | 1         | 1.16%   |
| 1866    | 1         | 1.16%   |
| 400     | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

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


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 29.76%  |
| Quanta                                 | 6         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 7.14%   |
| Suyin                                  | 5         | 5.95%   |
| Realtek Semiconductor                  | 5         | 5.95%   |
| IMC Networks                           | 5         | 5.95%   |
| Alcor Micro                            | 5         | 5.95%   |
| Apple                                  | 4         | 4.76%   |
| Syntek                                 | 3         | 3.57%   |
| Silicon Motion                         | 3         | 3.57%   |
| Microdia                               | 3         | 3.57%   |
| Lite-On Technology                     | 3         | 3.57%   |
| Sunplus Innovation Technology          | 2         | 2.38%   |
| Bison Electronics                      | 2         | 2.38%   |
| Z-Star Microelectronics                | 1         | 1.19%   |
| Samsung Electronics                    | 1         | 1.19%   |
| Ricoh                                  | 1         | 1.19%   |
| Pixart Imaging                         | 1         | 1.19%   |
| OmniVision Technologies                | 1         | 1.19%   |
| Logitech                               | 1         | 1.19%   |
| Aveo Technology                        | 1         | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                       | 6         | 7.14%   |
| Chicony Integrated Camera                           | 3         | 3.57%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 3         | 3.57%   |
| Syntek Lenovo EasyCamera                            | 2         | 2.38%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 2.38%   |
| Realtek USB Camera                                  | 2         | 2.38%   |
| Quanta HP TrueVision HD Camera                      | 2         | 2.38%   |
| Lite-On HP Webcam                                   | 2         | 2.38%   |
| Chicony USB 2.0 Camera                              | 2         | 2.38%   |
| Chicony FJ Camera                                   | 2         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 2.38%   |
| Alcor Micro USB 2.0 Camera                          | 2         | 2.38%   |
| Alcor Micro Acer Integrated Webcam                  | 2         | 2.38%   |
| Z-Star Webcam                                       | 1         | 1.19%   |
| Syntek USB Video Device                             | 1         | 1.19%   |
| Suyin USB 2.0 Camera                                | 1         | 1.19%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.19%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 1.19%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.19%   |
| Sunplus HD WebCam                                   | 1         | 1.19%   |
| Silicon Motion WebCam SC-10HDD13335N                | 1         | 1.19%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 1.19%   |
| Silicon Motion Web Camera                           | 1         | 1.19%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.19%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 1.19%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.19%   |
| Realtek Built-In Video Camera                       | 1         | 1.19%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 1.19%   |
| Quanta VGA WebCam                                   | 1         | 1.19%   |
| Quanta HP Truevision HD                             | 1         | 1.19%   |
| Quanta HD Webcam                                    | 1         | 1.19%   |
| Quanta ACER HD User Facing                          | 1         | 1.19%   |
| Pixart Imaging USB_2.0_Webcam                       | 1         | 1.19%   |
| OmniVision OV2640 Webcam                            | 1         | 1.19%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.19%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.19%   |
| Microdia Integrated Webcam                          | 1         | 1.19%   |
| Logitech HD Webcam C615                             | 1         | 1.19%   |
| Lite-On Integrated Camera                           | 1         | 1.19%   |
| IMC Networks USB2.0 UVC VGA WebCam                  | 1         | 1.19%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 4         | 40%     |
| Validity Sensors      | 2         | 20%     |
| Upek                  | 1         | 10%     |
| Synaptics             | 1         | 10%     |
| Samsung Electronics   | 1         | 10%     |
| LighTuning Technology | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 10%     |
| Validity Sensors Synaptics WBDI                        | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 10%     |
| Samsung Fingerprint Device                             | 1         | 10%     |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 10%     |
| AuthenTec Fingerprint Sensor                           | 1         | 10%     |
| AuthenTec AES1600                                      | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Upek        | 1         | 20%     |
| O2 Micro    | 1         | 20%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 20%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 69        | 68.32%  |
| 1     | 26        | 25.74%  |
| 2     | 6         | 5.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 26.32%  |
| Graphics card            | 6         | 15.79%  |
| Net/wireless             | 5         | 13.16%  |
| Chipcard                 | 5         | 13.16%  |
| Storage                  | 3         | 7.89%   |
| Multimedia controller    | 2         | 5.26%   |
| Bluetooth                | 2         | 5.26%   |
| Sound                    | 1         | 2.63%   |
| Net/ethernet             | 1         | 2.63%   |
| Dvb card                 | 1         | 2.63%   |
| Communication controller | 1         | 2.63%   |
| Camera                   | 1         | 2.63%   |

