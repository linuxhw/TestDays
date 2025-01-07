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

Total: 162

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0bc7f79026](https://linux-hardware.org/?probe=0bc7f79026) | Dec 16, 2024 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [1193f44f20](https://linux-hardware.org/?probe=1193f44f20) | Dec 08, 2024 |
| Acer          | TravelMate 8372             | [fb1751719f](https://linux-hardware.org/?probe=fb1751719f) | Nov 30, 2024 |
| ASUSTek       | 1008P                       | [6484520857](https://linux-hardware.org/?probe=6484520857) | Oct 31, 2024 |
| Google        | Droid                       | [4879fa61ce](https://linux-hardware.org/?probe=4879fa61ce) | Oct 23, 2024 |
| CSL-Comput... | C15 5500U                   | [98b09fe8bb](https://linux-hardware.org/?probe=98b09fe8bb) | Sep 30, 2024 |
| CSL-Comput... | C15 5500U                   | [008e0d5421](https://linux-hardware.org/?probe=008e0d5421) | Sep 16, 2024 |
| Dell          | Latitude 5400               | [ee7fe19f16](https://linux-hardware.org/?probe=ee7fe19f16) | Aug 26, 2024 |
| HP            | Notebook                    | [8330d22ee5](https://linux-hardware.org/?probe=8330d22ee5) | Aug 23, 2024 |
| Acer          | Aspire A315-53              | [c20748d891](https://linux-hardware.org/?probe=c20748d891) | Jul 29, 2024 |
| Fujitsu       | LIFEBOOK E756               | [4833f5a1a9](https://linux-hardware.org/?probe=4833f5a1a9) | Jul 12, 2024 |
| Acer          | Aspire E5-573G              | [81a22d43ad](https://linux-hardware.org/?probe=81a22d43ad) | Jun 09, 2024 |
| Compal        | JHL90 REFERENCE             | [c477434d4e](https://linux-hardware.org/?probe=c477434d4e) | May 09, 2024 |
| Dell          | Latitude D630               | [c9ae85eecc](https://linux-hardware.org/?probe=c9ae85eecc) | Apr 30, 2024 |
| Acer          | Aspire 7750G                | [961d70c1de](https://linux-hardware.org/?probe=961d70c1de) | Apr 27, 2024 |
| Dell          | Latitude D630               | [f59eb192f4](https://linux-hardware.org/?probe=f59eb192f4) | Apr 03, 2024 |
| Google        | Celes                       | [996befe940](https://linux-hardware.org/?probe=996befe940) | Mar 13, 2024 |
| Lenovo        | G40-45 80E1                 | [df12996678](https://linux-hardware.org/?probe=df12996678) | Feb 25, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [eaca048668](https://linux-hardware.org/?probe=eaca048668) | Feb 24, 2024 |
| Acer          | Aspire A315-24P             | [9925fee177](https://linux-hardware.org/?probe=9925fee177) | Feb 23, 2024 |
| Acer          | Aspire A315-24P             | [b76bdbcd5d](https://linux-hardware.org/?probe=b76bdbcd5d) | Feb 18, 2024 |
| Acer          | Aspire A315-24P             | [4abd6b79ce](https://linux-hardware.org/?probe=4abd6b79ce) | Feb 17, 2024 |
| Lenovo        | ThinkPad T430s 2356H83      | [7ee978c5e1](https://linux-hardware.org/?probe=7ee978c5e1) | Feb 08, 2024 |
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
| Linux Lite 6.6 | 17        | 14.41%  |
| Linux Lite 5.8 | 14        | 11.86%  |
| Linux Lite 6.0 | 13        | 11.02%  |
| Linux Lite 6.2 | 12        | 10.17%  |
| Linux Lite 6.4 | 11        | 9.32%   |
| Linux Lite 5.4 | 11        | 9.32%   |
| Linux Lite 5.2 | 9         | 7.63%   |
| Linux Lite 5.0 | 9         | 7.63%   |
| Linux Lite 5.6 | 7         | 5.93%   |
| Linux Lite 7.0 | 5         | 4.24%   |
| Linux Lite 7.2 | 3         | 2.54%   |
| Linux Lite 3.8 | 3         | 2.54%   |
| Linux Lite 4.8 | 2         | 1.69%   |
| Linux Lite 4.4 | 1         | 0.85%   |
| Linux Lite 4.2 | 1         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Linux Lite | 115       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-69-generic | 6         | 4.72%   |
| 5.15.0-82-generic | 5         | 3.94%   |
| 5.4.0-40-generic  | 4         | 3.15%   |
| 5.15.0-91-generic | 4         | 3.15%   |
| 5.15.0-76-generic | 4         | 3.15%   |
| 6.8.0-47-generic  | 3         | 2.36%   |
| 5.4.0-70-generic  | 3         | 2.36%   |
| 5.4.0-52-generic  | 3         | 2.36%   |
| 5.4.0-109-generic | 3         | 2.36%   |
| 5.15.0-33-generic | 3         | 2.36%   |
| 5.4.0-91-generic  | 2         | 1.57%   |
| 5.4.0-90-generic  | 2         | 1.57%   |
| 5.4.0-81-generic  | 2         | 1.57%   |
| 5.4.0-74-generic  | 2         | 1.57%   |
| 5.4.0-58-generic  | 2         | 1.57%   |
| 5.4.0-42-generic  | 2         | 1.57%   |
| 5.4.0-107-generic | 2         | 1.57%   |
| 5.4.0-104-generic | 2         | 1.57%   |
| 5.15.0-88-generic | 2         | 1.57%   |
| 5.15.0-83-generic | 2         | 1.57%   |
| 5.15.0-60-generic | 2         | 1.57%   |
| 5.15.0-56-generic | 2         | 1.57%   |
| 5.15.0-52-generic | 2         | 1.57%   |
| 5.15.0-48-generic | 2         | 1.57%   |
| 5.15.0-47-generic | 2         | 1.57%   |
| 6.8.0-49-generic  | 1         | 0.79%   |
| 6.8.0-41-generic  | 1         | 0.79%   |
| 6.8.0-39-generic  | 1         | 0.79%   |
| 6.8.0-38-generic  | 1         | 0.79%   |
| 6.8.0-35-generic  | 1         | 0.79%   |
| 6.1.0-1.linuxlite | 1         | 0.79%   |
| 6.0.0             | 1         | 0.79%   |
| 5.4.0-96-generic  | 1         | 0.79%   |
| 5.4.0-94-generic  | 1         | 0.79%   |
| 5.4.0-88-generic  | 1         | 0.79%   |
| 5.4.0-77-generic  | 1         | 0.79%   |
| 5.4.0-71-generic  | 1         | 0.79%   |
| 5.4.0-66-generic  | 1         | 0.79%   |
| 5.4.0-65-generic  | 1         | 0.79%   |
| 5.4.0-56-generic  | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 53        | 44.54%  |
| 5.4.0   | 46        | 38.66%  |
| 6.8.0   | 8         | 6.72%   |
| 4.15.0  | 4         | 3.36%   |
| 4.4.0   | 2         | 1.68%   |
| 6.1.0   | 1         | 0.84%   |
| 6.0.0   | 1         | 0.84%   |
| 5.19.0  | 1         | 0.84%   |
| 5.16.0  | 1         | 0.84%   |
| 5.13.0  | 1         | 0.84%   |
| 5.10.0  | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 53        | 44.54%  |
| 5.4     | 46        | 38.66%  |
| 6.8     | 8         | 6.72%   |
| 4.15    | 4         | 3.36%   |
| 4.4     | 2         | 1.68%   |
| 6.1     | 1         | 0.84%   |
| 6.0     | 1         | 0.84%   |
| 5.19    | 1         | 0.84%   |
| 5.16    | 1         | 0.84%   |
| 5.13    | 1         | 0.84%   |
| 5.10    | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 113       | 98.26%  |
| i686   | 2         | 1.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 99        | 86.09%  |
| GNOME   | 12        | 10.43%  |
| Unknown | 2         | 1.74%   |
| Deepin  | 1         | 0.87%   |
| Budgie  | 1         | 0.87%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 113       | 98.26%  |
| Tty     | 1         | 0.87%   |
| Unknown | 1         | 0.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 83        | 70.94%  |
| Unknown | 17        | 14.53%  |
| TDM     | 15        | 12.82%  |
| GDM3    | 1         | 0.85%   |
| GDM     | 1         | 0.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 63        | 54.78%  |
| de_DE | 9         | 7.83%   |
| fr_FR | 6         | 5.22%   |
| pl_PL | 5         | 4.35%   |
| it_IT | 5         | 4.35%   |
| en_GB | 5         | 4.35%   |
| pt_BR | 4         | 3.48%   |
| ru_RU | 3         | 2.61%   |
| es_ES | 3         | 2.61%   |
| ru_UA | 2         | 1.74%   |
| pt_PT | 2         | 1.74%   |
| zh_CN | 1         | 0.87%   |
| id_ID | 1         | 0.87%   |
| es_CO | 1         | 0.87%   |
| en_PH | 1         | 0.87%   |
| en_IN | 1         | 0.87%   |
| en_IE | 1         | 0.87%   |
| en_AU | 1         | 0.87%   |
| el_GR | 1         | 0.87%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 59        | 50.86%  |
| EFI  | 57        | 49.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 95        | 82.61%  |
| Tmpfs   | 9         | 7.83%   |
| Overlay | 8         | 6.96%   |
| Btrfs   | 2         | 1.74%   |
| Zfs     | 1         | 0.87%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 64        | 55.65%  |
| Unknown | 28        | 24.35%  |
| MBR     | 23        | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 85.34%  |
| Yes       | 17        | 14.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 86        | 73.5%   |
| Yes       | 31        | 26.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 20        | 17.39%  |
| ASUSTek Computer    | 20        | 17.39%  |
| Lenovo              | 18        | 15.65%  |
| Acer                | 14        | 12.17%  |
| Dell                | 11        | 9.57%   |
| Toshiba             | 4         | 3.48%   |
| Samsung Electronics | 4         | 3.48%   |
| Google              | 3         | 2.61%   |
| Fujitsu             | 3         | 2.61%   |
| Apple               | 2         | 1.74%   |
| UNOWHY              | 1         | 0.87%   |
| UMAX                | 1         | 0.87%   |
| TR                  | 1         | 0.87%   |
| Thomson             | 1         | 0.87%   |
| Sony                | 1         | 0.87%   |
| Pegatron            | 1         | 0.87%   |
| MSI                 | 1         | 0.87%   |
| Minix               | 1         | 0.87%   |
| Medion              | 1         | 0.87%   |
| Intel               | 1         | 0.87%   |
| Insignia            | 1         | 0.87%   |
| Gateway             | 1         | 0.87%   |
| Fujitsu Siemens     | 1         | 0.87%   |
| CSL-Computer        | 1         | 0.87%   |
| Compaq(Intel)       | 1         | 0.87%   |
| Compal              | 1         | 0.87%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| UNOWHY Y13G010S4EI                  | 1         | 0.87%   |
| UMAX VisionBook 12Wi 64G            | 1         | 0.87%   |
| TR ST Pro-KN                        | 1         | 0.87%   |
| Toshiba Satellite T215D             | 1         | 0.87%   |
| Toshiba Satellite P305              | 1         | 0.87%   |
| Toshiba Satellite C850-C1S          | 1         | 0.87%   |
| Toshiba QOSMIO X70-B                | 1         | 0.87%   |
| Thomson PT-NEO14A.2WH32             | 1         | 0.87%   |
| Sony VGN-SZ750N                     | 1         | 0.87%   |
| Samsung X420/X520                   | 1         | 0.87%   |
| Samsung NC110P/NC108P/NC111P        | 1         | 0.87%   |
| Samsung 905S3G/906S3G/915S3G/9305SG | 1         | 0.87%   |
| Samsung 530XBB                      | 1         | 0.87%   |
| Pegatron H36FF                      | 1         | 0.87%   |
| MSI MS-N014                         | 1         | 0.87%   |
| Minix Z64                           | 1         | 0.87%   |
| Medion Akoya E6418 MD99620          | 1         | 0.87%   |
| Lenovo ThinkPad X240 20AMS1J100     | 1         | 0.87%   |
| Lenovo ThinkPad T430s 2356H83       | 1         | 0.87%   |
| Lenovo ThinkPad T400 6475E13        | 1         | 0.87%   |
| Lenovo ThinkPad L480 20LS001AMC     | 1         | 0.87%   |
| Lenovo ThinkPad A475 20KMS08300     | 1         | 0.87%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1 | 1         | 0.87%   |
| Lenovo IdeaPad 330S-15AST 81F9      | 1         | 0.87%   |
| Lenovo IdeaPad 330-14IGM 81D0       | 1         | 0.87%   |
| Lenovo IdeaPad 320-15IKB 80YH       | 1         | 0.87%   |
| Lenovo IdeaPad 320-15ABR 80XS       | 1         | 0.87%   |
| Lenovo IdeaPad 310S-14AST 80UL      | 1         | 0.87%   |
| Lenovo IdeaPad 100-15IBY 80MJ       | 1         | 0.87%   |
| Lenovo IdeaPad 100-14IBY 80MH       | 1         | 0.87%   |
| Lenovo IdeaPad 1 15AMN7 82VG        | 1         | 0.87%   |
| Lenovo IdeaPad 1 14IGL05 81VU       | 1         | 0.87%   |
| Lenovo G460 20041                   | 1         | 0.87%   |
| Lenovo G40-45 80E1                  | 1         | 0.87%   |
| Lenovo 3000 V200 0764A11            | 1         | 0.87%   |
| Intel Jasper Lake Client Platform   | 1         | 0.87%   |
| Insignia NS-P11W7100                | 1         | 0.87%   |
| HP Stream Notebook PC 13            | 1         | 0.87%   |
| HP Presario V6000 (RG289UA#ABA)     | 1         | 0.87%   |
| HP Pavilion g4                      | 1         | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo IdeaPad          | 10        | 8.7%    |
| Acer Aspire             | 9         | 7.83%   |
| Lenovo ThinkPad         | 5         | 4.35%   |
| HP Laptop               | 5         | 4.35%   |
| HP Compaq               | 5         | 4.35%   |
| Dell Latitude           | 5         | 4.35%   |
| ASUS VivoBook           | 4         | 3.48%   |
| Toshiba Satellite       | 3         | 2.61%   |
| HP EliteBook            | 3         | 2.61%   |
| Dell Inspiron           | 3         | 2.61%   |
| HP Pavilion             | 2         | 1.74%   |
| Fujitsu LIFEBOOK        | 2         | 1.74%   |
| UNOWHY Y13G010S4EI      | 1         | 0.87%   |
| UMAX VisionBook         | 1         | 0.87%   |
| TR ST                   | 1         | 0.87%   |
| Toshiba QOSMIO          | 1         | 0.87%   |
| Thomson PT-NEO14A.2WH32 | 1         | 0.87%   |
| Sony VGN-SZ750N         | 1         | 0.87%   |
| Samsung X420            | 1         | 0.87%   |
| Samsung NC110P          | 1         | 0.87%   |
| Samsung 905S3G          | 1         | 0.87%   |
| Samsung 530XBB          | 1         | 0.87%   |
| Pegatron H36FF          | 1         | 0.87%   |
| MSI MS-N014             | 1         | 0.87%   |
| Minix Z64               | 1         | 0.87%   |
| Medion Akoya            | 1         | 0.87%   |
| Lenovo G460             | 1         | 0.87%   |
| Lenovo G40-45           | 1         | 0.87%   |
| Lenovo 3000             | 1         | 0.87%   |
| Intel Jasper            | 1         | 0.87%   |
| Insignia NS-P11W7100    | 1         | 0.87%   |
| HP Stream               | 1         | 0.87%   |
| HP Presario             | 1         | 0.87%   |
| HP Notebook             | 1         | 0.87%   |
| HP 655                  | 1         | 0.87%   |
| HP 15                   | 1         | 0.87%   |
| Google Droid            | 1         | 0.87%   |
| Google Chell            | 1         | 0.87%   |
| Google Celes            | 1         | 0.87%   |
| Gateway Sonic-C         | 1         | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 12        | 10.43%  |
| 2010 | 12        | 10.43%  |
| 2008 | 10        | 8.7%    |
| 2007 | 9         | 7.83%   |
| 2015 | 8         | 6.96%   |
| 2014 | 8         | 6.96%   |
| 2012 | 8         | 6.96%   |
| 2017 | 6         | 5.22%   |
| 2016 | 6         | 5.22%   |
| 2013 | 6         | 5.22%   |
| 2011 | 6         | 5.22%   |
| 2020 | 5         | 4.35%   |
| 2019 | 5         | 4.35%   |
| 2022 | 4         | 3.48%   |
| 2023 | 3         | 2.61%   |
| 2021 | 2         | 1.74%   |
| 2006 | 2         | 1.74%   |
| 2024 | 1         | 0.87%   |
| 2009 | 1         | 0.87%   |
| 2004 | 1         | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 115       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 108       | 93.91%  |
| Enabled  | 7         | 6.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 112       | 97.39%  |
| Yes  | 3         | 2.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 46        | 40%     |
| 1.01-2.0    | 22        | 19.13%  |
| 4.01-8.0    | 21        | 18.26%  |
| 16.01-24.0  | 9         | 7.83%   |
| 8.01-16.0   | 9         | 7.83%   |
| 0.51-1.0    | 4         | 3.48%   |
| 2.01-3.0    | 2         | 1.74%   |
| 32.01-64.0  | 1         | 0.87%   |
| 64.01-256.0 | 1         | 0.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 60        | 51.28%  |
| 2.01-3.0  | 26        | 22.22%  |
| 0.51-1.0  | 16        | 13.68%  |
| 3.01-4.0  | 9         | 7.69%   |
| 0.01-0.5  | 3         | 2.56%   |
| 4.01-8.0  | 2         | 1.71%   |
| 8.01-16.0 | 1         | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 91        | 78.45%  |
| 2      | 24        | 20.69%  |
| 3      | 1         | 0.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 57.39%  |
| Yes       | 49        | 42.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 81.74%  |
| No        | 21        | 18.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 98.26%  |
| No        | 2         | 1.74%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 72.41%  |
| No        | 32        | 27.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 17        | 14.78%  |
| Germany      | 12        | 10.43%  |
| France       | 8         | 6.96%   |
| Brazil       | 8         | 6.96%   |
| UK           | 6         | 5.22%   |
| Italy        | 6         | 5.22%   |
| Russia       | 5         | 4.35%   |
| Romania      | 5         | 4.35%   |
| Ukraine      | 4         | 3.48%   |
| Poland       | 4         | 3.48%   |
| Spain        | 3         | 2.61%   |
| Indonesia    | 3         | 2.61%   |
| Turkey       | 2         | 1.74%   |
| Thailand     | 2         | 1.74%   |
| Portugal     | 2         | 1.74%   |
| Philippines  | 2         | 1.74%   |
| Netherlands  | 2         | 1.74%   |
| Mexico       | 2         | 1.74%   |
| India        | 2         | 1.74%   |
| Greece       | 2         | 1.74%   |
| Australia    | 2         | 1.74%   |
| Venezuela    | 1         | 0.87%   |
| Sweden       | 1         | 0.87%   |
| South Africa | 1         | 0.87%   |
| Slovakia     | 1         | 0.87%   |
| Serbia       | 1         | 0.87%   |
| Myanmar      | 1         | 0.87%   |
| Morocco      | 1         | 0.87%   |
| Ireland      | 1         | 0.87%   |
| Iran         | 1         | 0.87%   |
| Guadeloupe   | 1         | 0.87%   |
| El Salvador  | 1         | 0.87%   |
| Czechia      | 1         | 0.87%   |
| Colombia     | 1         | 0.87%   |
| Chile        | 1         | 0.87%   |
| Canada       | 1         | 0.87%   |
| Argentina    | 1         | 0.87%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Moscow                 | 3         | 2.5%    |
| Valencia               | 2         | 1.67%   |
| Sydney                 | 2         | 1.67%   |
| Paris                  | 2         | 1.67%   |
| Pabianice              | 2         | 1.67%   |
| Odessa                 | 2         | 1.67%   |
| Frankfurt am Main      | 2         | 1.67%   |
| Delhi                  | 2         | 1.67%   |
| Bangkok                | 2         | 1.67%   |
| Żywiec                | 1         | 0.83%   |
| Yangon                 | 1         | 0.83%   |
| Würzburg              | 1         | 0.83%   |
| Wiesbaden              | 1         | 0.83%   |
| Washington             | 1         | 0.83%   |
| Warsaw                 | 1         | 0.83%   |
| Wahroonga              | 1         | 0.83%   |
| Voluntari              | 1         | 0.83%   |
| Virginia Beach         | 1         | 0.83%   |
| Vinnytsia              | 1         | 0.83%   |
| Villingen-Schwenningen | 1         | 0.83%   |
| Varennes-les-Narcy     | 1         | 0.83%   |
| Turin                  | 1         | 0.83%   |
| Tucape                 | 1         | 0.83%   |
| The Hague              | 1         | 0.83%   |
| Teresina               | 1         | 0.83%   |
| Tekirdağ              | 1         | 0.83%   |
| Tarragona              | 1         | 0.83%   |
| Tangier                | 1         | 0.83%   |
| Tamm                   | 1         | 0.83%   |
| Svidník               | 1         | 0.83%   |
| Surabaya               | 1         | 0.83%   |
| Subotica               | 1         | 0.83%   |
| Studenka               | 1         | 0.83%   |
| Strasbourg             | 1         | 0.83%   |
| St. Petersburg         | 1         | 0.83%   |
| South Shields          | 1         | 0.83%   |
| Shadrinsk              | 1         | 0.83%   |
| Sartrouville           | 1         | 0.83%   |
| Sao Paulo              | 1         | 0.83%   |
| Santiago del Estero    | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 25     | 16.92%  |
| WDC                 | 17        | 21     | 13.08%  |
| Samsung Electronics | 14        | 17     | 10.77%  |
| Toshiba             | 13        | 15     | 10%     |
| Unknown             | 10        | 13     | 7.69%   |
| Kingston            | 10        | 10     | 7.69%   |
| Micron Technology   | 6         | 8      | 4.62%   |
| Hitachi             | 6         | 6      | 4.62%   |
| HGST                | 6         | 6      | 4.62%   |
| SanDisk             | 4         | 4      | 3.08%   |
| SK hynix            | 3         | 5      | 2.31%   |
| Intel               | 2         | 2      | 1.54%   |
| GOODRAM             | 2         | 2      | 1.54%   |
| Crucial             | 2         | 2      | 1.54%   |
| China               | 2         | 2      | 1.54%   |
| Apple               | 2         | 2      | 1.54%   |
| Phison              | 1         | 1      | 0.77%   |
| LITEON              | 1         | 1      | 0.77%   |
| Lexar               | 1         | 1      | 0.77%   |
| KIOXIA              | 1         | 1      | 0.77%   |
| Hewlett-Packard     | 1         | 1      | 0.77%   |
| Fujitsu             | 1         | 1      | 0.77%   |
| ASUS-PHISON         | 1         | 2      | 0.77%   |
| ASMT                | 1         | 1      | 0.77%   |
| A-DATA Technology   | 1         | 1      | 0.77%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD       | 6         | 4.44%   |
| Unknown MMC Card  32GB                | 5         | 3.7%    |
| Toshiba MQ01ABF050 500GB              | 4         | 2.96%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 1.48%   |
| Unknown DA4064  64GB                  | 2         | 1.48%   |
| Toshiba MQ04ABF100 1TB                | 2         | 1.48%   |
| Toshiba MQ01ABD100 1TB                | 2         | 1.48%   |
| Seagate ST9320325AS 320GB             | 2         | 1.48%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 1.48%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 1.48%   |
| Samsung SSD 850 EVO 250GB             | 2         | 1.48%   |
| Samsung MZVLB256HAHQ-000L7 256GB      | 2         | 1.48%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD   | 2         | 1.48%   |
| Hitachi HTS543232A7A384 320GB         | 2         | 1.48%   |
| HGST HTS725050A7E630 500GB            | 2         | 1.48%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 0.74%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 0.74%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 0.74%   |
| WDC WD5000LPVX-80V0TT0 500GB          | 1         | 0.74%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 0.74%   |
| WDC WD2500BEVS-00UST0 250GB           | 1         | 0.74%   |
| WDC WD2500BEVE-00A0HT0 250GB          | 1         | 0.74%   |
| WDC WD1600BEVT-22A23T0 160GB          | 1         | 0.74%   |
| WDC WD10SPZX-80Z10T2 1TB              | 1         | 0.74%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.74%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.74%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 0.74%   |
| WDC WD Blue SA510 M.2 2280 1000GB SSD | 1         | 0.74%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 0.74%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB  | 1         | 0.74%   |
| Unknown SN64G  64GB                   | 1         | 0.74%   |
| Unknown SLD64G  64GB                  | 1         | 0.74%   |
| Unknown SD64G  64GB                   | 1         | 0.74%   |
| Unknown SD16G  16GB                   | 1         | 0.74%   |
| Unknown NCard  32GB                   | 1         | 0.74%   |
| Unknown MMC Card  128GB               | 1         | 0.74%   |
| Toshiba THNSNJ128GCSU 128GB SSD       | 1         | 0.74%   |
| Toshiba MQ01ABD050 500GB              | 1         | 0.74%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 0.74%   |
| Toshiba MK3265GSX 320GB               | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 24     | 35%     |
| Toshiba             | 12        | 14     | 20%     |
| WDC                 | 11        | 14     | 18.33%  |
| Hitachi             | 6         | 6      | 10%     |
| HGST                | 6         | 6      | 10%     |
| Samsung Electronics | 3         | 4      | 5%      |
| Fujitsu             | 1         | 1      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 8      | 18.6%   |
| Samsung Electronics | 6         | 6      | 13.95%  |
| WDC                 | 4         | 4      | 9.3%    |
| Micron Technology   | 4         | 6      | 9.3%    |
| SanDisk             | 3         | 3      | 6.98%   |
| GOODRAM             | 2         | 2      | 4.65%   |
| Crucial             | 2         | 2      | 4.65%   |
| China               | 2         | 2      | 4.65%   |
| Apple               | 2         | 2      | 4.65%   |
| Toshiba             | 1         | 1      | 2.33%   |
| SK hynix            | 1         | 3      | 2.33%   |
| Phison              | 1         | 1      | 2.33%   |
| LITEON              | 1         | 1      | 2.33%   |
| Lexar               | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| Hewlett-Packard     | 1         | 1      | 2.33%   |
| ASUS-PHISON         | 1         | 2      | 2.33%   |
| ASMT                | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 60        | 69     | 46.88%  |
| SSD     | 42        | 48     | 32.81%  |
| NVMe    | 13        | 17     | 10.16%  |
| MMC     | 12        | 15     | 9.38%   |
| Unknown | 1         | 1      | 0.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 92        | 115    | 76.67%  |
| NVMe | 13        | 17     | 10.83%  |
| MMC  | 12        | 15     | 10%     |
| SAS  | 3         | 3      | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 71        | 88     | 71.72%  |
| 0.51-1.0   | 27        | 28     | 27.27%  |
| 1.01-2.0   | 1         | 1      | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 45        | 37.82%  |
| 251-500        | 29        | 24.37%  |
| 51-100         | 14        | 11.76%  |
| 501-1000       | 13        | 10.92%  |
| 1-20           | 9         | 7.56%   |
| 21-50          | 6         | 5.04%   |
| 1001-2000      | 2         | 1.68%   |
| More than 3000 | 1         | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 60        | 50.42%  |
| 21-50     | 29        | 24.37%  |
| 101-250   | 14        | 11.76%  |
| 51-100    | 12        | 10.08%  |
| 251-500   | 3         | 2.52%   |
| 2001-3000 | 1         | 0.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 4.76%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 4.76%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 4.76%   |
| Toshiba MK3265GSX 320GB                        | 1         | 1      | 4.76%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 1         | 1      | 4.76%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 4.76%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 4.76%   |
| Seagate ST9320320AS 320GB                      | 1         | 1      | 4.76%   |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 4.76%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 4.76%   |
| Seagate ST1000LM048-2E7172 1TB                 | 1         | 1      | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 4.76%   |
| SanDisk SSD PLUS 120GB                         | 1         | 1      | 4.76%   |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 4.76%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 4.76%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 4.76%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 4.76%   |
| Apple SSD SM128C 121GB                         | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 38.1%   |
| WDC                 | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 2      | 9.52%   |
| SK hynix            | 1         | 1      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |

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
| HDD  | 16        | 16     | 76.19%  |
| SSD  | 5         | 5      | 23.81%  |

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
| Works    | 54        | 64     | 45%     |
| Detected | 46        | 65     | 38.33%  |
| Malfunc  | 20        | 21     | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 84        | 71.79%  |
| AMD                         | 16        | 13.68%  |
| Samsung Electronics         | 5         | 4.27%   |
| Nvidia                      | 3         | 2.56%   |
| SanDisk                     | 2         | 1.71%   |
| Micron Technology           | 2         | 1.71%   |
| Kingston Technology Company | 2         | 1.71%   |
| SK hynix                    | 1         | 0.85%   |
| Marvell Technology Group    | 1         | 0.85%   |
| KIOXIA                      | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 10.22%  |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 7.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 5.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 3.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 3.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 5         | 3.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 3.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 3.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 2.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 2.92%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 2.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 2.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.92%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 2.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 2.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.46%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 1.46%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.46%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 1.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.46%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 1.46%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 1.46%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.73%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 1         | 0.73%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.73%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.73%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.73%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.73%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.73%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.73%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 1         | 0.73%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 1         | 0.73%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 84        | 66.67%  |
| IDE  | 22        | 17.46%  |
| NVMe | 13        | 10.32%  |
| RAID | 7         | 5.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 96        | 83.48%  |
| AMD    | 19        | 16.52%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 2.61%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 3         | 2.61%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 1.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.74%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 1.74%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 1.74%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 2         | 1.74%   |
| Intel Core 2 CPU T7600 @ 2.33GHz              | 2         | 1.74%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.74%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 1.74%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 1.74%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 1.74%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.87%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.87%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.87%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.87%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.87%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 0.87%   |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.87%   |
| Intel Genuine CPU T2050 @ 1.60GHz             | 1         | 0.87%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz              | 1         | 0.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.87%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.87%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.87%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.87%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.87%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 0.87%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 1         | 0.87%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 0.87%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.87%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 0.87%   |
| Intel Core i5-3427U CPU @ 1.80GHz             | 1         | 0.87%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.87%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.87%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 1         | 0.87%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 24        | 20.87%  |
| Intel Core 2 Duo        | 14        | 12.17%  |
| Intel Celeron           | 14        | 12.17%  |
| Intel Core i3           | 9         | 7.83%   |
| Intel Atom              | 8         | 6.96%   |
| Intel Core i7           | 7         | 6.09%   |
| Other                   | 6         | 5.22%   |
| Intel Pentium           | 5         | 4.35%   |
| Intel Core 2            | 3         | 2.61%   |
| AMD E2                  | 3         | 2.61%   |
| AMD A8                  | 3         | 2.61%   |
| Intel Pentium Silver    | 2         | 1.74%   |
| Intel Genuine           | 2         | 1.74%   |
| AMD Ryzen 5             | 2         | 1.74%   |
| Intel Pentium Dual-Core | 1         | 0.87%   |
| Intel Core m7           | 1         | 0.87%   |
| Intel Celeron M         | 1         | 0.87%   |
| Intel Celeron Dual-Core | 1         | 0.87%   |
| AMD Turion Dual-Core    | 1         | 0.87%   |
| AMD Turion 64 X2 Mobile | 1         | 0.87%   |
| AMD Ryzen 3             | 1         | 0.87%   |
| AMD Quad-Core           | 1         | 0.87%   |
| AMD E1                  | 1         | 0.87%   |
| AMD Athlon II Neo       | 1         | 0.87%   |
| AMD A6                  | 1         | 0.87%   |
| AMD A12                 | 1         | 0.87%   |
| AMD A10                 | 1         | 0.87%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 76        | 66.09%  |
| 4      | 29        | 25.22%  |
| 1      | 6         | 5.22%   |
| 6      | 2         | 1.74%   |
| 14     | 1         | 0.87%   |
| 10     | 1         | 0.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 115       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 52.17%  |
| 2      | 55        | 47.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 113       | 98.26%  |
| 32-bit         | 2         | 1.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 21.85%  |
| 0x206a7    | 8         | 6.72%   |
| 0x306a9    | 6         | 5.04%   |
| 0x30678    | 6         | 5.04%   |
| 0x1067a    | 6         | 5.04%   |
| 0x40651    | 5         | 4.2%    |
| 0x706a1    | 4         | 3.36%   |
| 0x6fd      | 4         | 3.36%   |
| 0x20655    | 4         | 3.36%   |
| 0x06006705 | 3         | 2.52%   |
| 0x906c0    | 2         | 1.68%   |
| 0x806ec    | 2         | 1.68%   |
| 0x806ea    | 2         | 1.68%   |
| 0x806e9    | 2         | 1.68%   |
| 0x806c1    | 2         | 1.68%   |
| 0x6fb      | 2         | 1.68%   |
| 0x6f6      | 2         | 1.68%   |
| 0x406e3    | 2         | 1.68%   |
| 0x406c4    | 2         | 1.68%   |
| 0x406c3    | 2         | 1.68%   |
| 0x306c3    | 2         | 1.68%   |
| 0x106ca    | 2         | 1.68%   |
| 0x10676    | 2         | 1.68%   |
| 0x906ea    | 1         | 0.84%   |
| 0x906e9    | 1         | 0.84%   |
| 0x906a4    | 1         | 0.84%   |
| 0x906a3    | 1         | 0.84%   |
| 0x806eb    | 1         | 0.84%   |
| 0x6d8      | 1         | 0.84%   |
| 0x506e3    | 1         | 0.84%   |
| 0x506c9    | 1         | 0.84%   |
| 0x306d4    | 1         | 0.84%   |
| 0x30661    | 1         | 0.84%   |
| 0x08a00006 | 1         | 0.84%   |
| 0x08608103 | 1         | 0.84%   |
| 0x07030105 | 1         | 0.84%   |
| 0x07030104 | 1         | 0.84%   |
| 0x06006704 | 1         | 0.84%   |
| 0x0600611a | 1         | 0.84%   |
| 0x06006118 | 1         | 0.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Silvermont       | 12        | 10.43%  |
| Penryn           | 12        | 10.43%  |
| KabyLake         | 9         | 7.83%   |
| Core             | 9         | 7.83%   |
| SandyBridge      | 8         | 6.96%   |
| Haswell          | 8         | 6.96%   |
| Westmere         | 6         | 5.22%   |
| Skylake          | 6         | 5.22%   |
| IvyBridge        | 6         | 5.22%   |
| Goldmont plus    | 6         | 5.22%   |
| Excavator        | 6         | 5.22%   |
| Puma             | 4         | 3.48%   |
| Bonnell          | 4         | 3.48%   |
| Tremont          | 2         | 1.74%   |
| TigerLake        | 2         | 1.74%   |
| P6               | 2         | 1.74%   |
| Alderlake Hybrid | 2         | 1.74%   |
| Unknown          | 2         | 1.74%   |
| Zen+             | 1         | 0.87%   |
| Piledriver       | 1         | 0.87%   |
| K8 Hammer        | 1         | 0.87%   |
| K8 & K10 hybrid  | 1         | 0.87%   |
| K10              | 1         | 0.87%   |
| Jaguar           | 1         | 0.87%   |
| Goldmont         | 1         | 0.87%   |
| Broadwell        | 1         | 0.87%   |
| Bobcat           | 1         | 0.87%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 84        | 65.12%  |
| Nvidia | 24        | 18.6%   |
| AMD    | 21        | 16.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 4.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 4.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 4.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 4.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 4.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 4.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 3.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.9%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.17%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 2.17%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 2.17%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.45%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.45%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.45%   |
| Intel HD Graphics 620                                                                    | 2         | 1.45%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.45%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.45%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.72%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.72%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.72%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.72%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.72%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 0.72%   |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.72%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.72%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 0.72%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 0.72%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 59.13%  |
| 1 x AMD        | 18        | 15.65%  |
| Intel + Nvidia | 13        | 11.3%   |
| 1 x Nvidia     | 11        | 9.57%   |
| 2 x AMD        | 2         | 1.74%   |
| Other          | 1         | 0.87%   |
| 2 x Intel      | 1         | 0.87%   |
| Intel + AMD    | 1         | 0.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 103       | 88.79%  |
| Proprietary | 11        | 9.48%   |
| Unknown     | 2         | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 84        | 71.19%  |
| 0.01-0.5   | 18        | 15.25%  |
| 1.01-2.0   | 6         | 5.08%   |
| 0.51-1.0   | 6         | 5.08%   |
| 3.01-4.0   | 3         | 2.54%   |
| 5.01-6.0   | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 15.83%  |
| BOE                     | 17        | 14.17%  |
| Chimei Innolux          | 16        | 13.33%  |
| Samsung Electronics     | 15        | 12.5%   |
| LG Display              | 14        | 11.67%  |
| Chi Mei Optoelectronics | 8         | 6.67%   |
| CPT                     | 4         | 3.33%   |
| LG Philips              | 3         | 2.5%    |
| Goldstar                | 3         | 2.5%    |
| PANDA                   | 2         | 1.67%   |
| Lenovo                  | 2         | 1.67%   |
| InfoVision              | 2         | 1.67%   |
| HannStar                | 2         | 1.67%   |
| Apple                   | 2         | 1.67%   |
| ViewSonic               | 1         | 0.83%   |
| Sony                    | 1         | 0.83%   |
| Seiko/Epson             | 1         | 0.83%   |
| SANYO                   | 1         | 0.83%   |
| OEM                     | 1         | 0.83%   |
| Hewlett-Packard         | 1         | 0.83%   |
| eMachines               | 1         | 0.83%   |
| cPATH                   | 1         | 0.83%   |
| BenQ                    | 1         | 0.83%   |
| Belinea                 | 1         | 0.83%   |
| Unknown                 | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 2.5%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.67%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                  | 2         | 1.67%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 1.67%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 1.67%   |
| ViewSonic VA2026w VSC5020 1680x1050 433x271mm 20.1-inch               | 1         | 0.83%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                   | 1         | 0.83%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.83%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.83%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.83%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC3150 1920x1080 344x194mm 15.5-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 0.83%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 0.83%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.83%   |
| OEM 215_LCD_TV OEM3700 1920x1080                                      | 1         | 0.83%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch           | 1         | 0.83%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch           | 1         | 0.83%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0505 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD043D 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD03E3 1366x768 310x174mm 14.0-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD038C 1366x768 256x144mm 11.6-inch           | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 56        | 46.67%  |
| 1920x1080 (FHD)    | 29        | 24.17%  |
| 1280x800 (WXGA)    | 11        | 9.17%   |
| 1920x1200 (WUXGA)  | 6         | 5%      |
| 1600x900 (HD+)     | 4         | 3.33%   |
| 1024x600           | 3         | 2.5%    |
| 3840x2160 (4K)     | 2         | 1.67%   |
| 1680x1050 (WSXGA+) | 2         | 1.67%   |
| 1440x900 (WXGA+)   | 2         | 1.67%   |
| 3840x2400          | 1         | 0.83%   |
| 1920x540           | 1         | 0.83%   |
| 1360x768           | 1         | 0.83%   |
| 1280x1024 (SXGA)   | 1         | 0.83%   |
| Unknown            | 1         | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 41        | 34.17%  |
| 13      | 18        | 15%     |
| 14      | 16        | 13.33%  |
| 17      | 11        | 9.17%   |
| 11      | 7         | 5.83%   |
| 12      | 5         | 4.17%   |
| Unknown | 4         | 3.33%   |
| 24      | 3         | 2.5%    |
| 23      | 3         | 2.5%    |
| 16      | 3         | 2.5%    |
| 10      | 3         | 2.5%    |
| 21      | 2         | 1.67%   |
| 65      | 1         | 0.83%   |
| 46      | 1         | 0.83%   |
| 20      | 1         | 0.83%   |
| 19      | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 71        | 59.66%  |
| 201-300     | 20        | 16.81%  |
| 351-400     | 12        | 10.08%  |
| 501-600     | 6         | 5.04%   |
| 401-500     | 4         | 3.36%   |
| Unknown     | 4         | 3.36%   |
| 1001-1500   | 2         | 1.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 90        | 79.65%  |
| 16/10   | 18        | 15.93%  |
| Unknown | 3         | 2.65%   |
| 6/5     | 1         | 0.88%   |
| 3/2     | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 34.17%  |
| 81-90          | 29        | 24.17%  |
| 51-60          | 7         | 5.83%   |
| 201-250        | 7         | 5.83%   |
| 121-130        | 7         | 5.83%   |
| 131-140        | 6         | 5%      |
| 71-80          | 5         | 4.17%   |
| 61-70          | 5         | 4.17%   |
| Unknown        | 4         | 3.33%   |
| 41-50          | 3         | 2.5%    |
| 151-200        | 2         | 1.67%   |
| More than 1000 | 1         | 0.83%   |
| 251-300        | 1         | 0.83%   |
| 111-120        | 1         | 0.83%   |
| 501-1000       | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 52        | 44.44%  |
| 121-160       | 36        | 30.77%  |
| 51-100        | 19        | 16.24%  |
| Unknown       | 4         | 3.42%   |
| 161-240       | 3         | 2.56%   |
| More than 240 | 2         | 1.71%   |
| 1-50          | 1         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 103       | 88.79%  |
| 2     | 11        | 9.48%   |
| 0     | 2         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 60        | 33.71%  |
| Intel                             | 43        | 24.16%  |
| Qualcomm Atheros                  | 38        | 21.35%  |
| Broadcom                          | 13        | 7.3%    |
| Broadcom Limited                  | 5         | 2.81%   |
| Sierra Wireless                   | 3         | 1.69%   |
| Ralink                            | 3         | 1.69%   |
| Nvidia                            | 2         | 1.12%   |
| Marvell Technology Group          | 2         | 1.12%   |
| Xiaomi                            | 1         | 0.56%   |
| Ralink Technology                 | 1         | 0.56%   |
| OPPO Electronics                  | 1         | 0.56%   |
| MediaTek                          | 1         | 0.56%   |
| JMicron Technology                | 1         | 0.56%   |
| Ericsson Business Mobile Networks | 1         | 0.56%   |
| Dell                              | 1         | 0.56%   |
| D-Link                            | 1         | 0.56%   |
| ASIX Electronics                  | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 33        | 15.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 7.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 4.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 3.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 2.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 1.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 1.37%   |
| Intel Wireless 7260                                                     | 3         | 1.37%   |
| Intel Wireless 3165                                                     | 3         | 1.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 1.37%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 0.91%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.91%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.91%   |
| Intel Wireless 8265 / 8275                                              | 2         | 0.91%   |
| Intel Wireless 7265                                                     | 2         | 0.91%   |
| Intel Wireless 3160                                                     | 2         | 0.91%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 0.91%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.91%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.46%   |
| Sierra Wireless EM7455                                                  | 1         | 0.46%   |
| Realtek USB 10/100 LAN                                                  | 1         | 0.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.46%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.46%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 33.88%  |
| Qualcomm Atheros      | 35        | 28.93%  |
| Realtek Semiconductor | 26        | 21.49%  |
| Broadcom              | 6         | 4.96%   |
| Sierra Wireless       | 3         | 2.48%   |
| Ralink                | 3         | 2.48%   |
| Broadcom Limited      | 3         | 2.48%   |
| Ralink Technology     | 1         | 0.83%   |
| MediaTek              | 1         | 0.83%   |
| Dell                  | 1         | 0.83%   |
| D-Link                | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 9         | 7.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 8         | 6.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 8         | 6.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 7         | 5.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 6         | 4.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 6         | 4.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 3.28%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3         | 2.46%   |
| Intel Wireless 7260                                                                           | 3         | 2.46%   |
| Intel Wireless 3165                                                                           | 3         | 2.46%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 3         | 2.46%   |
| Sierra Wireless EM7305 Modem                                                                  | 2         | 1.64%   |
| Realtek 802.11ac NIC                                                                          | 2         | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 1.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 2         | 1.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 2         | 1.64%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.64%   |
| Intel Wireless 7265                                                                           | 2         | 1.64%   |
| Intel Wireless 3160                                                                           | 2         | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 2         | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 2         | 1.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.64%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 1.64%   |
| Sierra Wireless EM7455                                                                        | 1         | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.82%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.82%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.82%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 0.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.82%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.82%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.82%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 55.79%  |
| Intel                    | 15        | 15.79%  |
| Qualcomm Atheros         | 10        | 10.53%  |
| Broadcom                 | 7         | 7.37%   |
| Nvidia                   | 2         | 2.11%   |
| Marvell Technology Group | 2         | 2.11%   |
| Broadcom Limited         | 2         | 2.11%   |
| Xiaomi                   | 1         | 1.05%   |
| OPPO Electronics         | 1         | 1.05%   |
| JMicron Technology       | 1         | 1.05%   |
| ASIX Electronics         | 1         | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 33        | 34.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 17.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 4.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 3.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 2.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 2.08%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 2.08%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 2.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.04%   |
| Realtek USB 10/100 LAN                                                 | 1         | 1.04%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1.04%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.04%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1         | 1.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.04%   |
| OPPO OnePlus Nord 4                                                    | 1         | 1.04%   |
| Nvidia MCP77 Ethernet                                                  | 1         | 1.04%   |
| Nvidia MCP51 Ethernet Controller                                       | 1         | 1.04%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.04%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 1         | 1.04%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.04%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.04%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.04%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.04%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 1.04%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.04%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                      | 1         | 1.04%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 1.04%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express               | 1         | 1.04%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 1.04%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.04%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.04%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express       | 1         | 1.04%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express       | 1         | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 54.33%  |
| Ethernet | 94        | 45.19%  |
| Modem    | 1         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 96        | 80%     |
| Ethernet | 24        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 90        | 78.26%  |
| 1     | 22        | 19.13%  |
| 0     | 3         | 2.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 71.55%  |
| Yes  | 33        | 28.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 28.57%  |
| Realtek Semiconductor           | 16        | 19.05%  |
| Qualcomm Atheros Communications | 6         | 7.14%   |
| IMC Networks                    | 6         | 7.14%   |
| Broadcom                        | 6         | 7.14%   |
| Lite-On Technology              | 5         | 5.95%   |
| Hewlett-Packard                 | 5         | 5.95%   |
| Dell                            | 3         | 3.57%   |
| Chicony Electronics             | 2         | 2.38%   |
| Cambridge Silicon Radio         | 2         | 2.38%   |
| ASUSTek Computer                | 2         | 2.38%   |
| Apple                           | 2         | 2.38%   |
| Toshiba                         | 1         | 1.19%   |
| Smart Modular Technologies      | 1         | 1.19%   |
| Ralink                          | 1         | 1.19%   |
| MediaTek                        | 1         | 1.19%   |
| Foxconn / Hon Hai               | 1         | 1.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13        | 15.48%  |
| Realtek Bluetooth Radio                             | 8         | 9.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 7.14%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 4.76%   |
| IMC Networks Bluetooth Device                       | 4         | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.57%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 3.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.38%   |
| Intel AX201 Bluetooth                               | 2         | 2.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.38%   |
| Dell Wireless 355 Bluetooth                         | 2         | 2.38%   |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 2.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.38%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 2.38%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 2.38%   |
| Toshiba Askey Bluetooth Module                      | 1         | 1.19%   |
| Smart Modular Bluetooth Device                      | 1         | 1.19%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.19%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.19%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.19%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.19%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.19%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.19%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.19%   |
| MediaTek Wireless_Device                            | 1         | 1.19%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 1.19%   |
| Lite-On Bluetooth Device                            | 1         | 1.19%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.19%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.19%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.19%   |
| Intel AX211 Bluetooth                               | 1         | 1.19%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.19%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.19%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.19%   |
| Dell Wireless 360 Bluetooth                         | 1         | 1.19%   |
| Broadcom HP Portable Valentine                      | 1         | 1.19%   |
| Broadcom Bluetooth                                  | 1         | 1.19%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.19%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 91        | 71.65%  |
| AMD                     | 20        | 15.75%  |
| Nvidia                  | 11        | 8.66%   |
| Logitech                | 1         | 0.79%   |
| JMTek                   | 1         | 0.79%   |
| Blue Microphones        | 1         | 0.79%   |
| BEHRINGER International | 1         | 0.79%   |
| ATI Technologies        | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 6.54%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 5.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 5.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 5.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 4.58%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 4.58%   |
| AMD FCH Azalia Controller                                                                         | 7         | 4.58%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 3.92%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 3.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 3.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 3.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.96%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.96%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 3         | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.31%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.31%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.31%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.65%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.65%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.65%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.65%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.65%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.65%   |
| JMTek USB Speaker                                                                                 | 1         | 0.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.65%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.65%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 26.47%  |
| SK hynix            | 22        | 21.57%  |
| Kingston            | 12        | 11.76%  |
| Unknown             | 10        | 9.8%    |
| Micron Technology   | 9         | 8.82%   |
| Elpida              | 4         | 3.92%   |
| Unknown             | 4         | 3.92%   |
| Nanya Technology    | 3         | 2.94%   |
| A-DATA Technology   | 3         | 2.94%   |
| Unknown (ABCD)      | 2         | 1.96%   |
| Ramaxel Technology  | 2         | 1.96%   |
| Transcend           | 1         | 0.98%   |
| Smart               | 1         | 0.98%   |
| Qimonda             | 1         | 0.98%   |
| G.Skill             | 1         | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 3.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 3.81%   |
| Unknown                                                          | 4         | 3.81%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 3         | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.9%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 1.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.9%    |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 1.9%    |
| Kingston RAM ACR256X64D3S1333C9 2GB SODIMM DDR3 1333MT/s         | 2         | 1.9%    |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.95%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.95%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                            | 1         | 0.95%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                   | 1         | 0.95%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.95%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                    | 1         | 0.95%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s               | 1         | 0.95%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.95%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.95%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.95%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 1         | 0.95%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 0.95%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 1         | 0.95%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.95%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s             | 1         | 0.95%   |
| SK hynix RAM HMP125S6EFR8C-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 0.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.95%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.95%   |
| Samsung RAM Module 6GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 38        | 41.76%  |
| DDR4    | 22        | 24.18%  |
| DDR2    | 13        | 14.29%  |
| LPDDR4  | 7         | 7.69%   |
| SDRAM   | 6         | 6.59%   |
| Unknown | 2         | 2.2%    |
| LPDDR5  | 1         | 1.1%    |
| DRAM    | 1         | 1.1%    |
| DDR     | 1         | 1.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 85        | 97.7%   |
| Row Of Chips | 1         | 1.15%   |
| DIMM         | 1         | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 32        | 32.65%  |
| 4096  | 27        | 27.55%  |
| 8192  | 24        | 24.49%  |
| 1024  | 9         | 9.18%   |
| 16384 | 3         | 3.06%   |
| 32768 | 2         | 2.04%   |
| 6144  | 1         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 29        | 30.53%  |
| 2667    | 12        | 12.63%  |
| 3200    | 11        | 11.58%  |
| 667     | 10        | 10.53%  |
| 3266    | 4         | 4.21%   |
| 2400    | 4         | 4.21%   |
| 4199    | 3         | 3.16%   |
| 2048    | 3         | 3.16%   |
| 1334    | 3         | 3.16%   |
| 1333    | 3         | 3.16%   |
| 975     | 3         | 3.16%   |
| 1066    | 2         | 2.11%   |
| 800     | 2         | 2.11%   |
| 6400    | 1         | 1.05%   |
| 4267    | 1         | 1.05%   |
| 2133    | 1         | 1.05%   |
| 1866    | 1         | 1.05%   |
| 400     | 1         | 1.05%   |
| Unknown | 1         | 1.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Canon LBP2900 | 1         | 100%    |

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
| Chicony Electronics                    | 27        | 27.55%  |
| Realtek Semiconductor                  | 8         | 8.16%   |
| IMC Networks                           | 8         | 8.16%   |
| Quanta                                 | 7         | 7.14%   |
| Suyin                                  | 6         | 6.12%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 6.12%   |
| Alcor Micro                            | 5         | 5.1%    |
| Silicon Motion                         | 4         | 4.08%   |
| Apple                                  | 4         | 4.08%   |
| Syntek                                 | 3         | 3.06%   |
| Sunplus Innovation Technology          | 3         | 3.06%   |
| Microdia                               | 3         | 3.06%   |
| Lite-On Technology                     | 3         | 3.06%   |
| Bison Electronics                      | 3         | 3.06%   |
| Z-Star Microelectronics                | 1         | 1.02%   |
| Samsung Electronics                    | 1         | 1.02%   |
| Ricoh                                  | 1         | 1.02%   |
| Pixart Imaging                         | 1         | 1.02%   |
| OmniVision Technologies                | 1         | 1.02%   |
| Logitech                               | 1         | 1.02%   |
| Aveo Technology                        | 1         | 1.02%   |
| ALi                                    | 1         | 1.02%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                       | 6         | 6.12%   |
| Chicony Integrated Camera                           | 4         | 4.08%   |
| Chicony USB 2.0 Camera                              | 3         | 3.06%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 3         | 3.06%   |
| Syntek Lenovo EasyCamera                            | 2         | 2.04%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 2.04%   |
| Quanta HP TrueVision HD Camera                      | 2         | 2.04%   |
| Lite-On HP Webcam                                   | 2         | 2.04%   |
| IMC Networks EasyCamera                             | 2         | 2.04%   |
| Chicony FJ Camera                                   | 2         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 2.04%   |
| Bison Lenovo EasyCamera                             | 2         | 2.04%   |
| Alcor Micro Acer Integrated Webcam                  | 2         | 2.04%   |
| Z-Star Webcam                                       | 1         | 1.02%   |
| Syntek USB Video Device                             | 1         | 1.02%   |
| Suyin USB 2.0 Camera                                | 1         | 1.02%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.02%   |
| Suyin HP Truevision HD                              | 1         | 1.02%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 1.02%   |
| Sunplus MTD camera                                  | 1         | 1.02%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.02%   |
| Sunplus HD WebCam                                   | 1         | 1.02%   |
| Silicon Motion WebCam SC-10HDD13335N                | 1         | 1.02%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 1.02%   |
| Silicon Motion Web Camera                           | 1         | 1.02%   |
| Silicon Motion Real HD WebCam                       | 1         | 1.02%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.02%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 1.02%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.02%   |
| Realtek USB2.0 camera                               | 1         | 1.02%   |
| Realtek USB Camera                                  | 1         | 1.02%   |
| Realtek Integrated_Webcam_HD                        | 1         | 1.02%   |
| Realtek HD Webcam - Realtek                         | 1         | 1.02%   |
| Realtek EasyCamera                                  | 1         | 1.02%   |
| Realtek Built-In Video Camera                       | 1         | 1.02%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 1.02%   |
| Quanta VGA WebCam                                   | 1         | 1.02%   |
| Quanta HP Truevision HD                             | 1         | 1.02%   |
| Quanta HD Webcam                                    | 1         | 1.02%   |
| Quanta HD User Facing                               | 1         | 1.02%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 4         | 28.57%  |
| Validity Sensors      | 3         | 21.43%  |
| Upek                  | 2         | 14.29%  |
| LighTuning Technology | 2         | 14.29%  |
| Synaptics             | 1         | 7.14%   |
| Samsung Electronics   | 1         | 7.14%   |
| Focal-systems.Corp    | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 14.29%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 14.29%  |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                        | 1         | 7.14%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 7.14%   |
| Samsung Fingerprint Device                             | 1         | 7.14%   |
| LighTuning Fingerprint Reader                          | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 7.14%   |
| Focal-systems.Corp FT9201Fingerprint.Ì              | 1         | 7.14%   |
| AuthenTec Fingerprint Sensor                           | 1         | 7.14%   |
| AuthenTec AES1600                                      | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 2         | 33.33%  |
| Broadcom    | 2         | 33.33%  |
| Upek        | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 16.67%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 75        | 64.66%  |
| 1     | 33        | 28.45%  |
| 2     | 8         | 6.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 28%     |
| Graphics card            | 13        | 26%     |
| Chipcard                 | 6         | 12%     |
| Net/wireless             | 5         | 10%     |
| Storage                  | 3         | 6%      |
| Multimedia controller    | 2         | 4%      |
| Bluetooth                | 2         | 4%      |
| Sound                    | 1         | 2%      |
| Net/ethernet             | 1         | 2%      |
| Dvb card                 | 1         | 2%      |
| Communication controller | 1         | 2%      |
| Camera                   | 1         | 2%      |

