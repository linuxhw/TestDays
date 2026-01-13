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

Total: 197

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire ES1-521              | [6c3ad2b59f](https://linux-hardware.org/?probe=6c3ad2b59f) | Dec 31, 2025 |
| Acer          | Aspire ES1-521              | [33ed3f8ac4](https://linux-hardware.org/?probe=33ed3f8ac4) | Dec 31, 2025 |
| Acer          | Aspire E5-553               | [7d30225b40](https://linux-hardware.org/?probe=7d30225b40) | Dec 19, 2025 |
| VIT           | P2400                       | [fd53bea2e1](https://linux-hardware.org/?probe=fd53bea2e1) | Nov 17, 2025 |
| HP            | EliteBook 8460p             | [37b10d88d8](https://linux-hardware.org/?probe=37b10d88d8) | Nov 08, 2025 |
| HP            | Notebook                    | [5dc610343e](https://linux-hardware.org/?probe=5dc610343e) | Nov 05, 2025 |
| HP            | Notebook                    | [cbc5387b7a](https://linux-hardware.org/?probe=cbc5387b7a) | Nov 05, 2025 |
| HP            | Laptop 14-cf2xxx            | [77b5d4b762](https://linux-hardware.org/?probe=77b5d4b762) | Sep 08, 2025 |
| Dell          | Inspiron 1545               | [46311632f7](https://linux-hardware.org/?probe=46311632f7) | Aug 21, 2025 |
| Dell          | Inspiron 1545               | [42869a1896](https://linux-hardware.org/?probe=42869a1896) | Aug 19, 2025 |
| Lenovo        | ThinkPad T440p 20AN00C6G... | [a6720311da](https://linux-hardware.org/?probe=a6720311da) | Aug 12, 2025 |
| ASUSTek       | UX330UAK                    | [8182fc3560](https://linux-hardware.org/?probe=8182fc3560) | Jun 20, 2025 |
| Acer          | Aspire VN7-592G             | [a111583d6f](https://linux-hardware.org/?probe=a111583d6f) | Jun 19, 2025 |
| HUAWEI        | BOHK-WAX9X                  | [d3af1fc036](https://linux-hardware.org/?probe=d3af1fc036) | Jun 14, 2025 |
| HUAWEI        | BOHK-WAX9X                  | [a6c52c4ea4](https://linux-hardware.org/?probe=a6c52c4ea4) | Jun 14, 2025 |
| HUAWEI        | BOHK-WAX9X                  | [fc7894571e](https://linux-hardware.org/?probe=fc7894571e) | Jun 14, 2025 |
| Dell          | Latitude E5250              | [d78e89d8bc](https://linux-hardware.org/?probe=d78e89d8bc) | Jun 02, 2025 |
| Dell          | Latitude E5250              | [e1e616c675](https://linux-hardware.org/?probe=e1e616c675) | Jun 02, 2025 |
| Toshiba       | Satellite C655D             | [a32078a93a](https://linux-hardware.org/?probe=a32078a93a) | Jun 02, 2025 |
| Lenovo        | Z50-75 80EC                 | [87ca33e404](https://linux-hardware.org/?probe=87ca33e404) | May 31, 2025 |
| HP            | Laptop 14s-dq0xxx           | [585fc97e17](https://linux-hardware.org/?probe=585fc97e17) | May 28, 2025 |
| Dell          | Latitude 3140               | [f7ff9dc774](https://linux-hardware.org/?probe=f7ff9dc774) | May 19, 2025 |
| HP            | Pavilion g6                 | [219f699b2b](https://linux-hardware.org/?probe=219f699b2b) | May 04, 2025 |
| Dell          | Latitude E7240              | [709fb17f28](https://linux-hardware.org/?probe=709fb17f28) | Apr 29, 2025 |
| Dell          | Latitude E7240              | [8f183dfd6e](https://linux-hardware.org/?probe=8f183dfd6e) | Apr 29, 2025 |
| Dell          | Inspiron N4050              | [50ef56e888](https://linux-hardware.org/?probe=50ef56e888) | Apr 20, 2025 |
| HP            | Compaq 15                   | [84ddb2a884](https://linux-hardware.org/?probe=84ddb2a884) | Apr 11, 2025 |
| Sony          | VGNFW468J/B                 | [c0d51ba059](https://linux-hardware.org/?probe=c0d51ba059) | Apr 10, 2025 |
| HP            | Compaq 15                   | [612fc4b67c](https://linux-hardware.org/?probe=612fc4b67c) | Apr 09, 2025 |
| Dell          | Latitude E6220              | [1c3ec272a9](https://linux-hardware.org/?probe=1c3ec272a9) | Apr 01, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c769caad0e](https://linux-hardware.org/?probe=c769caad0e) | Mar 12, 2025 |
| Acer          | Aspire V5-571PG             | [e30b0b990d](https://linux-hardware.org/?probe=e30b0b990d) | Feb 01, 2025 |
| HP            | Pro Tabley 610 G1           | [93a3240615](https://linux-hardware.org/?probe=93a3240615) | Feb 01, 2025 |
| I-Life Dig... | ZED AIR PRO                 | [452f7db032](https://linux-hardware.org/?probe=452f7db032) | Jan 26, 2025 |
| Acer          | Aspire A315-53              | [39534d4985](https://linux-hardware.org/?probe=39534d4985) | Jan 07, 2025 |
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
| Linux Lite 6.6 | 18        | 12.5%   |
| Linux Lite 5.8 | 14        | 9.72%   |
| Linux Lite 6.4 | 13        | 9.03%   |
| Linux Lite 6.0 | 13        | 9.03%   |
| Linux Lite 6.2 | 12        | 8.33%   |
| Linux Lite 5.4 | 12        | 8.33%   |
| Linux Lite 7.4 | 9         | 6.25%   |
| Linux Lite 5.2 | 9         | 6.25%   |
| Linux Lite 5.0 | 9         | 6.25%   |
| Linux Lite 7.2 | 8         | 5.56%   |
| Linux Lite 7.0 | 7         | 4.86%   |
| Linux Lite 5.6 | 7         | 4.86%   |
| Linux Lite 7.6 | 6         | 4.17%   |
| Linux Lite 3.8 | 3         | 2.08%   |
| Linux Lite 4.8 | 2         | 1.39%   |
| Linux Lite 4.4 | 1         | 0.69%   |
| Linux Lite 4.2 | 1         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Linux Lite | 140       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.15.0-69-generic   | 7         | 4.58%   |
| 5.15.0-82-generic   | 5         | 3.27%   |
| 6.8.0-60-generic    | 4         | 2.61%   |
| 6.8.0-56-generic    | 4         | 2.61%   |
| 6.8.0-47-generic    | 4         | 2.61%   |
| 5.4.0-70-generic    | 4         | 2.61%   |
| 5.4.0-40-generic    | 4         | 2.61%   |
| 5.15.0-91-generic   | 4         | 2.61%   |
| 5.15.0-76-generic   | 4         | 2.61%   |
| 6.8.0-57-generic    | 3         | 1.96%   |
| 5.4.0-52-generic    | 3         | 1.96%   |
| 5.4.0-109-generic   | 3         | 1.96%   |
| 5.15.0-33-generic   | 3         | 1.96%   |
| 6.8.0-87-generic    | 2         | 1.31%   |
| 5.4.0-91-generic    | 2         | 1.31%   |
| 5.4.0-90-generic    | 2         | 1.31%   |
| 5.4.0-81-generic    | 2         | 1.31%   |
| 5.4.0-74-generic    | 2         | 1.31%   |
| 5.4.0-58-generic    | 2         | 1.31%   |
| 5.4.0-42-generic    | 2         | 1.31%   |
| 5.4.0-107-generic   | 2         | 1.31%   |
| 5.4.0-104-generic   | 2         | 1.31%   |
| 5.15.0-88-generic   | 2         | 1.31%   |
| 5.15.0-83-generic   | 2         | 1.31%   |
| 5.15.0-60-generic   | 2         | 1.31%   |
| 5.15.0-56-generic   | 2         | 1.31%   |
| 5.15.0-52-generic   | 2         | 1.31%   |
| 5.15.0-48-generic   | 2         | 1.31%   |
| 5.15.0-47-generic   | 2         | 1.31%   |
| 6.8.0-90-lowlatency | 1         | 0.65%   |
| 6.8.0-90-generic    | 1         | 0.65%   |
| 6.8.0-79-generic    | 1         | 0.65%   |
| 6.8.0-78-generic    | 1         | 0.65%   |
| 6.8.0-58-generic    | 1         | 0.65%   |
| 6.8.0-52-generic    | 1         | 0.65%   |
| 6.8.0-51-generic    | 1         | 0.65%   |
| 6.8.0-49-generic    | 1         | 0.65%   |
| 6.8.0-41-generic    | 1         | 0.65%   |
| 6.8.0-39-generic    | 1         | 0.65%   |
| 6.8.0-38-generic    | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 56        | 38.89%  |
| 5.4.0   | 47        | 32.64%  |
| 6.8.0   | 28        | 19.44%  |
| 4.15.0  | 4         | 2.78%   |
| 4.4.0   | 2         | 1.39%   |
| 6.17.0  | 1         | 0.69%   |
| 6.1.0   | 1         | 0.69%   |
| 6.0.0   | 1         | 0.69%   |
| 5.19.0  | 1         | 0.69%   |
| 5.16.0  | 1         | 0.69%   |
| 5.13.0  | 1         | 0.69%   |
| 5.10.0  | 1         | 0.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 56        | 38.89%  |
| 5.4     | 47        | 32.64%  |
| 6.8     | 28        | 19.44%  |
| 4.15    | 4         | 2.78%   |
| 4.4     | 2         | 1.39%   |
| 6.17    | 1         | 0.69%   |
| 6.1     | 1         | 0.69%   |
| 6.0     | 1         | 0.69%   |
| 5.19    | 1         | 0.69%   |
| 5.16    | 1         | 0.69%   |
| 5.13    | 1         | 0.69%   |
| 5.10    | 1         | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 138       | 98.57%  |
| i686   | 2         | 1.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 124       | 88.57%  |
| GNOME   | 12        | 8.57%   |
| Unknown | 2         | 1.43%   |
| Deepin  | 1         | 0.71%   |
| Budgie  | 1         | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 138       | 98.57%  |
| Tty     | 1         | 0.71%   |
| Unknown | 1         | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 104       | 73.24%  |
| Unknown | 21        | 14.79%  |
| TDM     | 15        | 10.56%  |
| GDM3    | 1         | 0.7%    |
| GDM     | 1         | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 80        | 57.14%  |
| de_DE | 11        | 7.86%   |
| it_IT | 6         | 4.29%   |
| fr_FR | 6         | 4.29%   |
| es_ES | 6         | 4.29%   |
| en_GB | 6         | 4.29%   |
| pl_PL | 5         | 3.57%   |
| pt_BR | 4         | 2.86%   |
| ru_RU | 3         | 2.14%   |
| ru_UA | 2         | 1.43%   |
| pt_PT | 2         | 1.43%   |
| zh_CN | 1         | 0.71%   |
| th_TH | 1         | 0.71%   |
| id_ID | 1         | 0.71%   |
| es_CO | 1         | 0.71%   |
| en_PH | 1         | 0.71%   |
| en_IN | 1         | 0.71%   |
| en_IE | 1         | 0.71%   |
| en_AU | 1         | 0.71%   |
| el_GR | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 71        | 50.35%  |
| EFI  | 70        | 49.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 115       | 82.14%  |
| Tmpfs   | 13        | 9.29%   |
| Overlay | 9         | 6.43%   |
| Btrfs   | 2         | 1.43%   |
| Zfs     | 1         | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 84        | 60%     |
| Unknown | 32        | 22.86%  |
| MBR     | 24        | 17.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 85.82%  |
| Yes       | 20        | 14.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 105       | 73.94%  |
| Yes       | 37        | 26.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 27        | 19.29%  |
| Lenovo                      | 21        | 15%     |
| ASUSTek Computer            | 21        | 15%     |
| Dell                        | 17        | 12.14%  |
| Acer                        | 17        | 12.14%  |
| Toshiba                     | 5         | 3.57%   |
| Samsung Electronics         | 4         | 2.86%   |
| Google                      | 3         | 2.14%   |
| Fujitsu                     | 3         | 2.14%   |
| Sony                        | 2         | 1.43%   |
| Apple                       | 2         | 1.43%   |
| VIT                         | 1         | 0.71%   |
| UNOWHY                      | 1         | 0.71%   |
| UMAX                        | 1         | 0.71%   |
| TR                          | 1         | 0.71%   |
| Thomson                     | 1         | 0.71%   |
| Pegatron                    | 1         | 0.71%   |
| MSI                         | 1         | 0.71%   |
| Minix                       | 1         | 0.71%   |
| Medion                      | 1         | 0.71%   |
| Intel                       | 1         | 0.71%   |
| Insignia                    | 1         | 0.71%   |
| I-Life Digital Technologies | 1         | 0.71%   |
| HUAWEI                      | 1         | 0.71%   |
| Gateway                     | 1         | 0.71%   |
| Fujitsu Siemens             | 1         | 0.71%   |
| CSL-Computer                | 1         | 0.71%   |
| Compaq(Intel)               | 1         | 0.71%   |
| Compal                      | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Notebook                         | 2         | 1.43%   |
| Dell Latitude E7240                 | 2         | 1.43%   |
| VIT P2400                           | 1         | 0.71%   |
| UNOWHY Y13G010S4EI                  | 1         | 0.71%   |
| UMAX VisionBook 12Wi 64G            | 1         | 0.71%   |
| TR ST Pro-KN                        | 1         | 0.71%   |
| Toshiba Satellite T215D             | 1         | 0.71%   |
| Toshiba Satellite P305              | 1         | 0.71%   |
| Toshiba Satellite C850-C1S          | 1         | 0.71%   |
| Toshiba Satellite C655D             | 1         | 0.71%   |
| Toshiba QOSMIO X70-B                | 1         | 0.71%   |
| Thomson PT-NEO14A.2WH32             | 1         | 0.71%   |
| Sony VGNFW468J/B                    | 1         | 0.71%   |
| Sony VGN-SZ750N                     | 1         | 0.71%   |
| Samsung X420/X520                   | 1         | 0.71%   |
| Samsung NC110P/NC108P/NC111P        | 1         | 0.71%   |
| Samsung 905S3G/906S3G/915S3G/9305SG | 1         | 0.71%   |
| Samsung 530XBB                      | 1         | 0.71%   |
| Pegatron H36FF                      | 1         | 0.71%   |
| MSI MS-N014                         | 1         | 0.71%   |
| Minix Z64                           | 1         | 0.71%   |
| Medion Akoya E6418 MD99620          | 1         | 0.71%   |
| Lenovo Z50-75 80EC                  | 1         | 0.71%   |
| Lenovo ThinkPad X240 20AMS1J100     | 1         | 0.71%   |
| Lenovo ThinkPad T440p 20AN00C6GE    | 1         | 0.71%   |
| Lenovo ThinkPad T430s 2356H83       | 1         | 0.71%   |
| Lenovo ThinkPad T400 6475E13        | 1         | 0.71%   |
| Lenovo ThinkPad L480 20LS001AMC     | 1         | 0.71%   |
| Lenovo ThinkPad A475 20KMS08300     | 1         | 0.71%   |
| Lenovo ThinkBook 15 G2 ITL 20VE     | 1         | 0.71%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1 | 1         | 0.71%   |
| Lenovo IdeaPad 330S-15AST 81F9      | 1         | 0.71%   |
| Lenovo IdeaPad 330-14IGM 81D0       | 1         | 0.71%   |
| Lenovo IdeaPad 320-15IKB 80YH       | 1         | 0.71%   |
| Lenovo IdeaPad 320-15ABR 80XS       | 1         | 0.71%   |
| Lenovo IdeaPad 310S-14AST 80UL      | 1         | 0.71%   |
| Lenovo IdeaPad 100-15IBY 80MJ       | 1         | 0.71%   |
| Lenovo IdeaPad 100-14IBY 80MH       | 1         | 0.71%   |
| Lenovo IdeaPad 1 15AMN7 82VG        | 1         | 0.71%   |
| Lenovo IdeaPad 1 14IGL05 81VU       | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 12        | 8.57%   |
| Lenovo IdeaPad          | 10        | 7.14%   |
| Dell Latitude           | 9         | 6.43%   |
| HP Laptop               | 7         | 5%      |
| Lenovo ThinkPad         | 6         | 4.29%   |
| HP Compaq               | 6         | 4.29%   |
| Dell Inspiron           | 5         | 3.57%   |
| Toshiba Satellite       | 4         | 2.86%   |
| HP EliteBook            | 4         | 2.86%   |
| ASUS VivoBook           | 4         | 2.86%   |
| HP Pavilion             | 3         | 2.14%   |
| HP Notebook             | 2         | 1.43%   |
| Fujitsu LIFEBOOK        | 2         | 1.43%   |
| VIT P2400               | 1         | 0.71%   |
| UNOWHY Y13G010S4EI      | 1         | 0.71%   |
| UMAX VisionBook         | 1         | 0.71%   |
| TR ST                   | 1         | 0.71%   |
| Toshiba QOSMIO          | 1         | 0.71%   |
| Thomson PT-NEO14A.2WH32 | 1         | 0.71%   |
| Sony VGNFW468J          | 1         | 0.71%   |
| Sony VGN-SZ750N         | 1         | 0.71%   |
| Samsung X420            | 1         | 0.71%   |
| Samsung NC110P          | 1         | 0.71%   |
| Samsung 905S3G          | 1         | 0.71%   |
| Samsung 530XBB          | 1         | 0.71%   |
| Pegatron H36FF          | 1         | 0.71%   |
| MSI MS-N014             | 1         | 0.71%   |
| Minix Z64               | 1         | 0.71%   |
| Medion Akoya            | 1         | 0.71%   |
| Lenovo Z50-75           | 1         | 0.71%   |
| Lenovo ThinkBook        | 1         | 0.71%   |
| Lenovo G460             | 1         | 0.71%   |
| Lenovo G40-45           | 1         | 0.71%   |
| Lenovo 3000             | 1         | 0.71%   |
| Intel Jasper            | 1         | 0.71%   |
| Insignia NS-P11W7100    | 1         | 0.71%   |
| I-Life Digital ZED      | 1         | 0.71%   |
| HUAWEI BOHK-WAX9X       | 1         | 0.71%   |
| HP Stream               | 1         | 0.71%   |
| HP Pro                  | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 12        | 8.57%   |
| 2010 | 12        | 8.57%   |
| 2014 | 11        | 7.86%   |
| 2008 | 11        | 7.86%   |
| 2012 | 10        | 7.14%   |
| 2011 | 10        | 7.14%   |
| 2019 | 9         | 6.43%   |
| 2015 | 9         | 6.43%   |
| 2007 | 9         | 6.43%   |
| 2020 | 8         | 5.71%   |
| 2017 | 8         | 5.71%   |
| 2013 | 8         | 5.71%   |
| 2016 | 7         | 5%      |
| 2022 | 4         | 2.86%   |
| 2023 | 3         | 2.14%   |
| 2009 | 3         | 2.14%   |
| 2024 | 2         | 1.43%   |
| 2006 | 2         | 1.43%   |
| 2021 | 1         | 0.71%   |
| 2004 | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 140       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 131       | 93.57%  |
| Enabled  | 9         | 6.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 137       | 97.86%  |
| Yes  | 3         | 2.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 56        | 40%     |
| 4.01-8.0    | 28        | 20%     |
| 1.01-2.0    | 24        | 17.14%  |
| 16.01-24.0  | 12        | 8.57%   |
| 8.01-16.0   | 11        | 7.86%   |
| 0.51-1.0    | 4         | 2.86%   |
| 2.01-3.0    | 3         | 2.14%   |
| 32.01-64.0  | 1         | 0.71%   |
| 64.01-256.0 | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 72        | 50.7%   |
| 2.01-3.0  | 37        | 26.06%  |
| 0.51-1.0  | 16        | 11.27%  |
| 3.01-4.0  | 9         | 6.34%   |
| 4.01-8.0  | 4         | 2.82%   |
| 0.01-0.5  | 3         | 2.11%   |
| 8.01-16.0 | 1         | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 111       | 78.72%  |
| 2      | 27        | 19.15%  |
| 3      | 2         | 1.42%   |
| 4      | 1         | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 56.43%  |
| Yes       | 61        | 43.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 82.86%  |
| No        | 24        | 17.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 97.14%  |
| No        | 4         | 2.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 73.05%  |
| No        | 38        | 26.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 25        | 17.86%  |
| Germany      | 13        | 9.29%   |
| Italy        | 8         | 5.71%   |
| France       | 8         | 5.71%   |
| Brazil       | 8         | 5.71%   |
| UK           | 7         | 5%      |
| Russia       | 5         | 3.57%   |
| Romania      | 5         | 3.57%   |
| Poland       | 5         | 3.57%   |
| Ukraine      | 4         | 2.86%   |
| Thailand     | 3         | 2.14%   |
| Spain        | 3         | 2.14%   |
| Indonesia    | 3         | 2.14%   |
| Colombia     | 3         | 2.14%   |
| Canada       | 3         | 2.14%   |
| Venezuela    | 2         | 1.43%   |
| Turkey       | 2         | 1.43%   |
| Portugal     | 2         | 1.43%   |
| Philippines  | 2         | 1.43%   |
| Netherlands  | 2         | 1.43%   |
| Mexico       | 2         | 1.43%   |
| India        | 2         | 1.43%   |
| Greece       | 2         | 1.43%   |
| Australia    | 2         | 1.43%   |
| Sweden       | 1         | 0.71%   |
| South Africa | 1         | 0.71%   |
| Slovakia     | 1         | 0.71%   |
| Serbia       | 1         | 0.71%   |
| Qatar        | 1         | 0.71%   |
| Peru         | 1         | 0.71%   |
| Namibia      | 1         | 0.71%   |
| Myanmar      | 1         | 0.71%   |
| Morocco      | 1         | 0.71%   |
| Ireland      | 1         | 0.71%   |
| Iran         | 1         | 0.71%   |
| Guadeloupe   | 1         | 0.71%   |
| El Salvador  | 1         | 0.71%   |
| Ecuador      | 1         | 0.71%   |
| Czechia      | 1         | 0.71%   |
| Chile        | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Moscow                 | 3         | 2.07%   |
| Bangkok                | 3         | 2.07%   |
| Valencia               | 2         | 1.38%   |
| Tamm                   | 2         | 1.38%   |
| Sydney                 | 2         | 1.38%   |
| Paris                  | 2         | 1.38%   |
| Pabianice              | 2         | 1.38%   |
| Odessa                 | 2         | 1.38%   |
| Frankfurt am Main      | 2         | 1.38%   |
| Delhi                  | 2         | 1.38%   |
| Żywiec                | 1         | 0.69%   |
| Yangon                 | 1         | 0.69%   |
| Würzburg              | 1         | 0.69%   |
| Wiesbaden              | 1         | 0.69%   |
| Washington             | 1         | 0.69%   |
| Warsaw                 | 1         | 0.69%   |
| Wahroonga              | 1         | 0.69%   |
| Voluntari              | 1         | 0.69%   |
| Virginia Beach         | 1         | 0.69%   |
| Vinnytsia              | 1         | 0.69%   |
| Villingen-Schwenningen | 1         | 0.69%   |
| Varennes-les-Narcy     | 1         | 0.69%   |
| Vancouver              | 1         | 0.69%   |
| Turin                  | 1         | 0.69%   |
| Tucape                 | 1         | 0.69%   |
| The Hague              | 1         | 0.69%   |
| Teresina               | 1         | 0.69%   |
| Tekirdağ              | 1         | 0.69%   |
| Tarragona              | 1         | 0.69%   |
| Tangier                | 1         | 0.69%   |
| Svidník               | 1         | 0.69%   |
| Surrey                 | 1         | 0.69%   |
| Surabaya               | 1         | 0.69%   |
| Subotica               | 1         | 0.69%   |
| Studenka               | 1         | 0.69%   |
| Strasbourg             | 1         | 0.69%   |
| St. Petersburg         | 1         | 0.69%   |
| South Shields          | 1         | 0.69%   |
| Shadrinsk              | 1         | 0.69%   |
| Sartrouville           | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 26     | 14.29%  |
| WDC                 | 20        | 24     | 12.42%  |
| Toshiba             | 17        | 19     | 10.56%  |
| Samsung Electronics | 17        | 20     | 10.56%  |
| Kingston            | 14        | 14     | 8.7%    |
| Unknown             | 13        | 16     | 8.07%   |
| Micron Technology   | 7         | 9      | 4.35%   |
| Hitachi             | 7         | 7      | 4.35%   |
| HGST                | 6         | 6      | 3.73%   |
| SK hynix            | 4         | 7      | 2.48%   |
| SanDisk             | 4         | 4      | 2.48%   |
| Intel               | 2         | 2      | 1.24%   |
| GOODRAM             | 2         | 2      | 1.24%   |
| Crucial             | 2         | 2      | 1.24%   |
| China               | 2         | 2      | 1.24%   |
| ASMT                | 2         | 2      | 1.24%   |
| Apple               | 2         | 2      | 1.24%   |
| A-DATA Technology   | 2         | 2      | 1.24%   |
| Unknown             | 2         | 2      | 1.24%   |
| SSSTC               | 1         | 1      | 0.62%   |
| PNY                 | 1         | 1      | 0.62%   |
| Phison              | 1         | 1      | 0.62%   |
| MD20000             | 1         | 1      | 0.62%   |
| LITEONIT            | 1         | 1      | 0.62%   |
| LITEON              | 1         | 1      | 0.62%   |
| Lexar               | 1         | 1      | 0.62%   |
| KIOXIA              | 1         | 1      | 0.62%   |
| JMicron Technology  | 1         | 1      | 0.62%   |
| Hewlett-Packard     | 1         | 1      | 0.62%   |
| Fujitsu             | 1         | 1      | 0.62%   |
| CT1000MX            | 1         | 1      | 0.62%   |
| ASUS-PHISON         | 1         | 2      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 7         | 4.22%   |
| Unknown MMC Card  32GB                            | 5         | 3.01%   |
| Toshiba MQ01ABF050 500GB                          | 5         | 3.01%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 3         | 1.81%   |
| Toshiba MQ01ABD100 1TB                            | 3         | 1.81%   |
| Unknown NCard  32GB                               | 2         | 1.2%    |
| Unknown DA4064  64GB                              | 2         | 1.2%    |
| Toshiba MQ04ABF100 1TB                            | 2         | 1.2%    |
| Toshiba MQ01ABD050 500GB                          | 2         | 1.2%    |
| Toshiba MK3265GSX 320GB                           | 2         | 1.2%    |
| Seagate ST9320325AS 320GB                         | 2         | 1.2%    |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB                    | 2         | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 1.2%    |
| Samsung SSD PM851 mSATA 256GB                     | 2         | 1.2%    |
| Samsung SSD 850 EVO 250GB                         | 2         | 1.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 1.2%    |
| Samsung MZVLB256HAHQ-000L7 256GB                  | 2         | 1.2%    |
| Samsung HM160HI 160GB                             | 2         | 1.2%    |
| Micron MTFDDAK256MAM-1K12 256GB SSD               | 2         | 1.2%    |
| Hitachi HTS543232A7A384 320GB                     | 2         | 1.2%    |
| HGST HTS725050A7E630 500GB                        | 2         | 1.2%    |
| Unknown                                           | 2         | 1.2%    |
| WDC WDS480G2G0A-00JH30 480GB SSD                  | 1         | 0.6%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 1         | 0.6%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1         | 0.6%    |
| WDC WD5000LPVX-80V0TT0 500GB                      | 1         | 0.6%    |
| WDC WD5000LPCX-75VHAT0 500GB                      | 1         | 0.6%    |
| WDC WD3200BPVT-22JJ5T0 320GB                      | 1         | 0.6%    |
| WDC WD3200BEKT-60PVMT0 320GB                      | 1         | 0.6%    |
| WDC WD2500BEVS-00UST0 250GB                       | 1         | 0.6%    |
| WDC WD2500BEVE-00A0HT0 250GB                      | 1         | 0.6%    |
| WDC WD1600BEVT-22A23T0 160GB                      | 1         | 0.6%    |
| WDC WD10SPZX-80Z10T2 1TB                          | 1         | 0.6%    |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 0.6%    |
| WDC WD10SPZX-24Z10 1TB                            | 1         | 0.6%    |
| WDC WD10JPVX-75JC3T0 1TB                          | 1         | 0.6%    |
| WDC WD Blue SA510 M.2 2280 1000GB                 | 1         | 0.6%    |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB              | 1         | 0.6%    |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB              | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 25     | 30.56%  |
| Toshiba             | 16        | 18     | 22.22%  |
| WDC                 | 14        | 17     | 19.44%  |
| Hitachi             | 7         | 7      | 9.72%   |
| HGST                | 6         | 6      | 8.33%   |
| Samsung Electronics | 4         | 5      | 5.56%   |
| JMicron Technology  | 1         | 1      | 1.39%   |
| Fujitsu             | 1         | 1      | 1.39%   |
| ASMT                | 1         | 1      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 11     | 21.15%  |
| Samsung Electronics | 7         | 7      | 13.46%  |
| WDC                 | 4         | 4      | 7.69%   |
| Micron Technology   | 4         | 6      | 7.69%   |
| SanDisk             | 3         | 3      | 5.77%   |
| GOODRAM             | 2         | 2      | 3.85%   |
| Crucial             | 2         | 2      | 3.85%   |
| China               | 2         | 2      | 3.85%   |
| Apple               | 2         | 2      | 3.85%   |
| A-DATA Technology   | 2         | 2      | 3.85%   |
| Unknown             | 1         | 1      | 1.92%   |
| Toshiba             | 1         | 1      | 1.92%   |
| SK hynix            | 1         | 4      | 1.92%   |
| PNY                 | 1         | 1      | 1.92%   |
| Phison              | 1         | 1      | 1.92%   |
| LITEONIT            | 1         | 1      | 1.92%   |
| LITEON              | 1         | 1      | 1.92%   |
| Lexar               | 1         | 1      | 1.92%   |
| Intel               | 1         | 1      | 1.92%   |
| Hewlett-Packard     | 1         | 1      | 1.92%   |
| CT1000MX            | 1         | 1      | 1.92%   |
| ASUS-PHISON         | 1         | 2      | 1.92%   |
| ASMT                | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 71        | 81     | 45.51%  |
| SSD     | 49        | 58     | 31.41%  |
| MMC     | 17        | 20     | 10.9%   |
| NVMe    | 17        | 21     | 10.9%   |
| Unknown | 2         | 2      | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 110       | 134    | 73.33%  |
| NVMe | 17        | 21     | 11.33%  |
| MMC  | 17        | 20     | 11.33%  |
| SAS  | 6         | 7      | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 83        | 103    | 70.34%  |
| 0.51-1.0   | 34        | 35     | 28.81%  |
| 1.01-2.0   | 1         | 1      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 51        | 35.42%  |
| 251-500        | 37        | 25.69%  |
| 51-100         | 19        | 13.19%  |
| 501-1000       | 15        | 10.42%  |
| 1-20           | 11        | 7.64%   |
| 21-50          | 7         | 4.86%   |
| More than 3000 | 2         | 1.39%   |
| 1001-2000      | 2         | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 71        | 48.97%  |
| 21-50     | 37        | 25.52%  |
| 101-250   | 17        | 11.72%  |
| 51-100    | 15        | 10.34%  |
| 251-500   | 3         | 2.07%   |
| 2001-3000 | 1         | 0.69%   |
| 1001-2000 | 1         | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MK3265GSX 320GB                        | 2         | 2      | 8%      |
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 4%      |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 4%      |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 4%      |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 4%      |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 1         | 2      | 4%      |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 4%      |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 4%      |
| Seagate ST9320320AS 320GB                      | 1         | 1      | 4%      |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 4%      |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 4%      |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 4%      |
| Seagate ST1000LM048-2E7172 1TB                 | 1         | 1      | 4%      |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 4%      |
| SanDisk SSD PLUS 120GB                         | 1         | 1      | 4%      |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 4%      |
| Samsung Electronics HM160HI 160GB              | 1         | 1      | 4%      |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 4%      |
| Kingston SUV400S37240G 240GB SSD               | 1         | 1      | 4%      |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 4%      |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 4%      |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 4%      |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 4%      |
| Apple SSD SM128C 121GB                         | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 32%     |
| WDC                 | 3         | 3      | 12%     |
| Toshiba             | 3         | 3      | 12%     |
| Hitachi             | 3         | 3      | 12%     |
| Samsung Electronics | 2         | 2      | 8%      |
| SK hynix            | 1         | 2      | 4%      |
| SanDisk             | 1         | 1      | 4%      |
| Micron Technology   | 1         | 1      | 4%      |
| Kingston            | 1         | 1      | 4%      |
| HGST                | 1         | 1      | 4%      |
| Apple               | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 42.11%  |
| Toshiba             | 3         | 3      | 15.79%  |
| Hitachi             | 3         | 3      | 15.79%  |
| WDC                 | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| HGST                | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 19     | 76%     |
| SSD  | 6         | 7      | 24%     |

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
| Works    | 62        | 73     | 42.18%  |
| Detected | 61        | 83     | 41.5%   |
| Malfunc  | 24        | 26     | 16.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 97        | 69.29%  |
| AMD                            | 22        | 15.71%  |
| Samsung Electronics            | 6         | 4.29%   |
| Nvidia                         | 3         | 2.14%   |
| Micron Technology              | 3         | 2.14%   |
| Kingston Technology Company    | 3         | 2.14%   |
| SanDisk                        | 2         | 1.43%   |
| Solid State Storage Technology | 1         | 0.71%   |
| SK hynix                       | 1         | 0.71%   |
| Marvell Technology Group       | 1         | 0.71%   |
| KIOXIA                         | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 11.66%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 6.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 6.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 4.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 4.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 3.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 3.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 3.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 5         | 3.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 3.07%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 2.45%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 2.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 2.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 2.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.84%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 1.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.84%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 1.23%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 2         | 1.23%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 1.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 1.23%   |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                           | 1         | 0.61%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.61%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 1         | 0.61%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.61%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.61%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.61%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.61%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.61%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.61%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 99        | 65.56%  |
| IDE  | 24        | 15.89%  |
| NVMe | 17        | 11.26%  |
| RAID | 11        | 7.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 114       | 81.43%  |
| AMD    | 26        | 18.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 2.14%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 3         | 2.14%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 1.43%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 1.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.43%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.43%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 1.43%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 1.43%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 2         | 1.43%   |
| Intel Core 2 CPU T7600 @ 2.33GHz              | 2         | 1.43%   |
| Intel Celeron N4120 CPU @ 1.10GHz             | 2         | 1.43%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.43%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 1.43%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.43%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 1.43%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.43%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 1.43%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.71%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.71%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.71%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.71%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 0.71%   |
| Intel N100                                    | 1         | 0.71%   |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.71%   |
| Intel Genuine CPU T2050 @ 1.60GHz             | 1         | 0.71%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz              | 1         | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.71%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.71%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.71%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.71%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.71%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.71%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.71%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 0.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.71%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 1         | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 20.71%  |
| Intel Celeron           | 16        | 11.43%  |
| Intel Core 2 Duo        | 15        | 10.71%  |
| Intel Core i3           | 12        | 8.57%   |
| Intel Atom              | 10        | 7.14%   |
| Intel Core i7           | 9         | 6.43%   |
| Other                   | 8         | 5.71%   |
| Intel Pentium           | 5         | 3.57%   |
| Intel Core 2            | 3         | 2.14%   |
| AMD Ryzen 5             | 3         | 2.14%   |
| AMD E2                  | 3         | 2.14%   |
| AMD A8                  | 3         | 2.14%   |
| AMD A10                 | 3         | 2.14%   |
| Intel Pentium Silver    | 2         | 1.43%   |
| Intel Pentium Dual-Core | 2         | 1.43%   |
| Intel Genuine           | 2         | 1.43%   |
| AMD E1                  | 2         | 1.43%   |
| AMD A6                  | 2         | 1.43%   |
| Intel Core m7           | 1         | 0.71%   |
| Intel Celeron M         | 1         | 0.71%   |
| Intel Celeron Dual-Core | 1         | 0.71%   |
| AMD Turion Dual-Core    | 1         | 0.71%   |
| AMD Turion 64 X2 Mobile | 1         | 0.71%   |
| AMD Ryzen 3             | 1         | 0.71%   |
| AMD Quad-Core           | 1         | 0.71%   |
| AMD Athlon II Neo       | 1         | 0.71%   |
| AMD Athlon II           | 1         | 0.71%   |
| AMD A4                  | 1         | 0.71%   |
| AMD A12                 | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 92        | 65.71%  |
| 4      | 38        | 27.14%  |
| 1      | 6         | 4.29%   |
| 6      | 2         | 1.43%   |
| 14     | 1         | 0.71%   |
| 10     | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 140       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 71        | 50.71%  |
| 2      | 69        | 49.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 138       | 98.57%  |
| 32-bit         | 2         | 1.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 32.64%  |
| 0x206a7    | 9         | 6.25%   |
| 0x30678    | 7         | 4.86%   |
| 0x306a9    | 6         | 4.17%   |
| 0x1067a    | 6         | 4.17%   |
| 0x40651    | 5         | 3.47%   |
| 0x706a1    | 4         | 2.78%   |
| 0x6fd      | 4         | 2.78%   |
| 0x20655    | 4         | 2.78%   |
| 0x806c1    | 3         | 2.08%   |
| 0x306c3    | 3         | 2.08%   |
| 0x06006705 | 3         | 2.08%   |
| 0x906c0    | 2         | 1.39%   |
| 0x806ec    | 2         | 1.39%   |
| 0x806ea    | 2         | 1.39%   |
| 0x806e9    | 2         | 1.39%   |
| 0x6fb      | 2         | 1.39%   |
| 0x6f6      | 2         | 1.39%   |
| 0x406e3    | 2         | 1.39%   |
| 0x406c4    | 2         | 1.39%   |
| 0x406c3    | 2         | 1.39%   |
| 0x106ca    | 2         | 1.39%   |
| 0x10676    | 2         | 1.39%   |
| 0x906ea    | 1         | 0.69%   |
| 0x906e9    | 1         | 0.69%   |
| 0x906a4    | 1         | 0.69%   |
| 0x906a3    | 1         | 0.69%   |
| 0x806eb    | 1         | 0.69%   |
| 0x6d8      | 1         | 0.69%   |
| 0x506e3    | 1         | 0.69%   |
| 0x506c9    | 1         | 0.69%   |
| 0x306d4    | 1         | 0.69%   |
| 0x30661    | 1         | 0.69%   |
| 0x08a00006 | 1         | 0.69%   |
| 0x08608103 | 1         | 0.69%   |
| 0x07030105 | 1         | 0.69%   |
| 0x07030104 | 1         | 0.69%   |
| 0x06006704 | 1         | 0.69%   |
| 0x0600611a | 1         | 0.69%   |
| 0x06006118 | 1         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Silvermont       | 14        | 10%     |
| Penryn           | 14        | 10%     |
| SandyBridge      | 12        | 8.57%   |
| KabyLake         | 10        | 7.14%   |
| Haswell          | 10        | 7.14%   |
| Core             | 9         | 6.43%   |
| IvyBridge        | 8         | 5.71%   |
| Goldmont plus    | 8         | 5.71%   |
| Excavator        | 7         | 5%      |
| Westmere         | 6         | 4.29%   |
| Skylake          | 6         | 4.29%   |
| Puma             | 6         | 4.29%   |
| Bonnell          | 4         | 2.86%   |
| TigerLake        | 3         | 2.14%   |
| Zen+             | 2         | 1.43%   |
| Tremont          | 2         | 1.43%   |
| P6               | 2         | 1.43%   |
| K10              | 2         | 1.43%   |
| Jaguar           | 2         | 1.43%   |
| Broadwell        | 2         | 1.43%   |
| Alderlake Hybrid | 2         | 1.43%   |
| Unknown          | 2         | 1.43%   |
| Steamroller      | 1         | 0.71%   |
| Piledriver       | 1         | 0.71%   |
| K8 Hammer        | 1         | 0.71%   |
| K8 & K10 hybrid  | 1         | 0.71%   |
| Gracemont        | 1         | 0.71%   |
| Goldmont         | 1         | 0.71%   |
| Bobcat           | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 101       | 64.74%  |
| AMD    | 29        | 18.59%  |
| Nvidia | 26        | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 5.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 4.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 4.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 4.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 4.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 3.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 3.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 3.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 3.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 3.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.41%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 2.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.81%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 3         | 1.81%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.81%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.2%    |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 2         | 1.2%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 2         | 1.2%    |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.2%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.2%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.2%    |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 2         | 1.2%    |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.6%    |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.6%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.6%    |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.6%    |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.6%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.6%    |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.6%    |
| Nvidia GK208M [GeForce GT 730M]                                                          | 1         | 0.6%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.6%    |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.6%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.6%    |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 0.6%    |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 82        | 58.57%  |
| 1 x AMD        | 25        | 17.86%  |
| Intel + Nvidia | 15        | 10.71%  |
| 1 x Nvidia     | 11        | 7.86%   |
| 2 x AMD        | 3         | 2.14%   |
| 2 x Intel      | 2         | 1.43%   |
| Other          | 1         | 0.71%   |
| Intel + AMD    | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 127       | 90.07%  |
| Proprietary | 11        | 7.8%    |
| Unknown     | 3         | 2.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 101       | 70.63%  |
| 0.01-0.5   | 22        | 15.38%  |
| 0.51-1.0   | 10        | 6.99%   |
| 1.01-2.0   | 6         | 4.2%    |
| 3.01-4.0   | 3         | 2.1%    |
| 5.01-6.0   | 1         | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 17.01%  |
| BOE                     | 24        | 16.33%  |
| LG Display              | 18        | 12.24%  |
| Chimei Innolux          | 18        | 12.24%  |
| Samsung Electronics     | 16        | 10.88%  |
| Chi Mei Optoelectronics | 9         | 6.12%   |
| Goldstar                | 4         | 2.72%   |
| CPT                     | 4         | 2.72%   |
| LG Philips              | 3         | 2.04%   |
| InfoVision              | 3         | 2.04%   |
| PANDA                   | 2         | 1.36%   |
| Lenovo                  | 2         | 1.36%   |
| HannStar                | 2         | 1.36%   |
| Apple                   | 2         | 1.36%   |
| ViewSonic               | 1         | 0.68%   |
| Vestel Elektronik       | 1         | 0.68%   |
| Unknown                 | 1         | 0.68%   |
| Sony                    | 1         | 0.68%   |
| Seiko/Epson             | 1         | 0.68%   |
| SANYO                   | 1         | 0.68%   |
| OEM                     | 1         | 0.68%   |
| InnoLux Display         | 1         | 0.68%   |
| Hewlett-Packard         | 1         | 0.68%   |
| eMachines               | 1         | 0.68%   |
| Dell                    | 1         | 0.68%   |
| cPATH                   | 1         | 0.68%   |
| BenQ                    | 1         | 0.68%   |
| Belinea                 | 1         | 0.68%   |
| Unknown                 | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 2.04%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 3         | 2.04%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 2         | 1.36%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.36%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                  | 2         | 1.36%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 1.36%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 1.36%   |
| BOE LCD Monitor BOE05DA 1366x768 277x156mm 12.5-inch                  | 2         | 1.36%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 1.36%   |
| ViewSonic VA2026w VSC5020 1680x1050 433x271mm 20.1-inch               | 1         | 0.68%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch  | 1         | 0.68%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.68%   |
| Sony TV *00 SNY8004 3840x2160 1439x809mm 65.0-inch                    | 1         | 0.68%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.68%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.68%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.68%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC3150 1920x1080 344x194mm 15.5-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 0.68%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch               | 1         | 0.68%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.68%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 1         | 0.68%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch           | 1         | 0.68%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch           | 1         | 0.68%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch          | 1         | 0.68%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 0.68%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch          | 1         | 0.68%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 73        | 49.66%  |
| 1920x1080 (FHD)    | 34        | 23.13%  |
| 1280x800 (WXGA)    | 11        | 7.48%   |
| 1920x1200 (WUXGA)  | 8         | 5.44%   |
| 1600x900 (HD+)     | 5         | 3.4%    |
| 3840x2160 (4K)     | 3         | 2.04%   |
| 1024x600           | 3         | 2.04%   |
| 1680x1050 (WSXGA+) | 2         | 1.36%   |
| 1440x900 (WXGA+)   | 2         | 1.36%   |
| 3840x2400          | 1         | 0.68%   |
| 2288x1287          | 1         | 0.68%   |
| 1920x540           | 1         | 0.68%   |
| 1360x768           | 1         | 0.68%   |
| 1280x1024 (SXGA)   | 1         | 0.68%   |
| Unknown            | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 52        | 35.37%  |
| 13      | 21        | 14.29%  |
| 14      | 19        | 12.93%  |
| 17      | 11        | 7.48%   |
| 12      | 9         | 6.12%   |
| 11      | 8         | 5.44%   |
| 21      | 4         | 2.72%   |
| 10      | 4         | 2.72%   |
| Unknown | 4         | 2.72%   |
| 24      | 3         | 2.04%   |
| 23      | 3         | 2.04%   |
| 16      | 3         | 2.04%   |
| 142     | 1         | 0.68%   |
| 84      | 1         | 0.68%   |
| 65      | 1         | 0.68%   |
| 46      | 1         | 0.68%   |
| 20      | 1         | 0.68%   |
| 19      | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 87        | 59.59%  |
| 201-300        | 27        | 18.49%  |
| 351-400        | 12        | 8.22%   |
| 501-600        | 6         | 4.11%   |
| 401-500        | 6         | 4.11%   |
| Unknown        | 4         | 2.74%   |
| 1001-1500      | 2         | 1.37%   |
| More than 2000 | 1         | 0.68%   |
| 1501-2000      | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 113       | 81.88%  |
| 16/10   | 19        | 13.77%  |
| Unknown | 3         | 2.17%   |
| 6/5     | 1         | 0.72%   |
| 3/2     | 1         | 0.72%   |
| 1.00    | 1         | 0.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 52        | 35.37%  |
| 81-90          | 34        | 23.13%  |
| 61-70          | 9         | 6.12%   |
| 201-250        | 9         | 6.12%   |
| 51-60          | 8         | 5.44%   |
| 121-130        | 7         | 4.76%   |
| 71-80          | 6         | 4.08%   |
| 131-140        | 6         | 4.08%   |
| 41-50          | 4         | 2.72%   |
| Unknown        | 4         | 2.72%   |
| More than 1000 | 3         | 2.04%   |
| 151-200        | 2         | 1.36%   |
| 251-300        | 1         | 0.68%   |
| 111-120        | 1         | 0.68%   |
| 501-1000       | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 67        | 46.53%  |
| 121-160       | 44        | 30.56%  |
| 51-100        | 20        | 13.89%  |
| 161-240       | 5         | 3.47%   |
| Unknown       | 4         | 2.78%   |
| More than 240 | 2         | 1.39%   |
| 1-50          | 2         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 125       | 88.65%  |
| 2     | 14        | 9.93%   |
| 0     | 2         | 1.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 75        | 34.56%  |
| Intel                             | 53        | 24.42%  |
| Qualcomm Atheros                  | 46        | 21.2%   |
| Broadcom                          | 13        | 5.99%   |
| Broadcom Limited                  | 6         | 2.76%   |
| Sierra Wireless                   | 4         | 1.84%   |
| Marvell Technology Group          | 4         | 1.84%   |
| Ralink                            | 3         | 1.38%   |
| Xiaomi                            | 2         | 0.92%   |
| Nvidia                            | 2         | 0.92%   |
| Dell                              | 2         | 0.92%   |
| Ralink Technology                 | 1         | 0.46%   |
| OPPO Electronics                  | 1         | 0.46%   |
| MediaTek                          | 1         | 0.46%   |
| JMicron Technology                | 1         | 0.46%   |
| Ericsson Business Mobile Networks | 1         | 0.46%   |
| D-Link                            | 1         | 0.46%   |
| ASIX Electronics                  | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 40        | 15.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 21        | 7.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 4.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 3.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 3.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 3.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 2.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 2.26%   |
| Intel Wireless 7260                                                     | 5         | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.13%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 1.13%   |
| Intel Wireless 7265                                                     | 3         | 1.13%   |
| Intel Wireless 3165                                                     | 3         | 1.13%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 1.13%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 1.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.75%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.75%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 0.75%   |
| Intel Wireless 8265 / 8275                                              | 2         | 0.75%   |
| Intel Wireless 8260                                                     | 2         | 0.75%   |
| Intel Wireless 3160                                                     | 2         | 0.75%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.75%   |
| Dell Hub of E-Port Replicator                                           | 2         | 0.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 34.93%  |
| Qualcomm Atheros      | 43        | 29.45%  |
| Realtek Semiconductor | 30        | 20.55%  |
| Broadcom              | 6         | 4.11%   |
| Sierra Wireless       | 4         | 2.74%   |
| Broadcom Limited      | 4         | 2.74%   |
| Ralink                | 3         | 2.05%   |
| Dell                  | 2         | 1.37%   |
| Ralink Technology     | 1         | 0.68%   |
| MediaTek              | 1         | 0.68%   |
| D-Link                | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 7.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 6.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 6.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 5.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 5.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 4.08%   |
| Intel Wireless 7260                                                     | 5         | 3.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 2.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 2.04%   |
| Intel Wireless 7265                                                     | 3         | 2.04%   |
| Intel Wireless 3165                                                     | 3         | 2.04%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 2.04%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.36%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.36%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.36%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.36%   |
| Intel Wireless 8260                                                     | 2         | 1.36%   |
| Intel Wireless 3160                                                     | 2         | 1.36%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.36%   |
| Dell Hub of E-Port Replicator                                           | 2         | 1.36%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.36%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.36%   |
| Sierra Wireless EM7455                                                  | 1         | 0.68%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.68%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.68%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.68%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 66        | 56.41%  |
| Intel                    | 20        | 17.09%  |
| Qualcomm Atheros         | 11        | 9.4%    |
| Broadcom                 | 7         | 5.98%   |
| Marvell Technology Group | 4         | 3.42%   |
| Xiaomi                   | 2         | 1.71%   |
| Nvidia                   | 2         | 1.71%   |
| Broadcom Limited         | 2         | 1.71%   |
| OPPO Electronics         | 1         | 0.85%   |
| JMicron Technology       | 1         | 0.85%   |
| ASIX Electronics         | 1         | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 40        | 33.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 17.8%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 5.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 2.54%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 2.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 1.69%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 1.69%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.69%   |
| Realtek USB 10/100 LAN                                                 | 1         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.85%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.85%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.85%   |
| OPPO Ace 3V                                                            | 1         | 0.85%   |
| Nvidia MCP77 Ethernet                                                  | 1         | 0.85%   |
| Nvidia MCP51 Ethernet Controller                                       | 1         | 0.85%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 1         | 0.85%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.85%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.85%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.85%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 0.85%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 0.85%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                      | 1         | 0.85%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 0.85%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express               | 1         | 0.85%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 0.85%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 0.85%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 136       | 53.75%  |
| Ethernet | 116       | 45.85%  |
| Modem    | 1         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 115       | 79.31%  |
| Ethernet | 30        | 20.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 109       | 77.86%  |
| 1     | 26        | 18.57%  |
| 0     | 5         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 96        | 68.09%  |
| Yes  | 45        | 31.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 30.1%   |
| Realtek Semiconductor           | 19        | 18.45%  |
| Qualcomm Atheros Communications | 8         | 7.77%   |
| Lite-On Technology              | 7         | 6.8%    |
| IMC Networks                    | 6         | 5.83%   |
| Hewlett-Packard                 | 6         | 5.83%   |
| Broadcom                        | 6         | 5.83%   |
| Dell                            | 4         | 3.88%   |
| Foxconn / Hon Hai               | 2         | 1.94%   |
| Chicony Electronics             | 2         | 1.94%   |
| Cambridge Silicon Radio         | 2         | 1.94%   |
| ASUSTek Computer                | 2         | 1.94%   |
| Apple                           | 2         | 1.94%   |
| Toshiba                         | 1         | 0.97%   |
| Smart Modular Technologies      | 1         | 0.97%   |
| Realtek                         | 1         | 0.97%   |
| Ralink                          | 1         | 0.97%   |
| MediaTek                        | 1         | 0.97%   |
| Alps Electric                   | 1         | 0.97%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 16.5%   |
| Realtek Bluetooth Radio                             | 12        | 11.65%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 5.83%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.88%   |
| Intel AX201 Bluetooth                               | 4         | 3.88%   |
| IMC Networks Bluetooth Device                       | 4         | 3.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.91%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.91%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 2.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.94%   |
| Lite-On Bluetooth Device                            | 2         | 1.94%   |
| Dell Wireless 355 Bluetooth                         | 2         | 1.94%   |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 1.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.94%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.94%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.94%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.97%   |
| Smart Modular Bluetooth Device                      | 1         | 0.97%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.97%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.97%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.97%   |
| Realtek Bluetooth Radio                             | 1         | 0.97%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.97%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.97%   |
| MediaTek Wireless_Device                            | 1         | 0.97%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.97%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.97%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.97%   |
| Intel Bluetooth Device                              | 1         | 0.97%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.97%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.97%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.97%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.97%   |
| Dell Wireless 360 Bluetooth                         | 1         | 0.97%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.97%   |
| Broadcom HP Portable Valentine                      | 1         | 0.97%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 107       | 70.39%  |
| AMD                     | 28        | 18.42%  |
| Nvidia                  | 12        | 7.89%   |
| Logitech                | 1         | 0.66%   |
| JMTek                   | 1         | 0.66%   |
| Blue Microphones        | 1         | 0.66%   |
| BEHRINGER International | 1         | 0.66%   |
| ATI Technologies        | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 5.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 5.88%   |
| AMD FCH Azalia Controller                                                                         | 11        | 5.88%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 5.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 5.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 4.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 4.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 4.28%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.74%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 3.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 3.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 2.67%   |
| AMD Ryzen HD Audio Controller                                                                     | 4         | 2.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.6%    |
| AMD High Definition Audio Controller                                                              | 3         | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.07%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.07%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.07%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.07%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.53%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.53%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.53%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.53%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.53%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.53%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.53%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.53%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.53%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 1         | 0.53%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 26.19%  |
| SK hynix            | 26        | 20.63%  |
| Kingston            | 16        | 12.7%   |
| Unknown             | 13        | 10.32%  |
| Micron Technology   | 11        | 8.73%   |
| Elpida              | 5         | 3.97%   |
| Unknown             | 5         | 3.97%   |
| A-DATA Technology   | 4         | 3.17%   |
| Ramaxel Technology  | 3         | 2.38%   |
| Nanya Technology    | 3         | 2.38%   |
| Unknown (ABCD)      | 2         | 1.59%   |
| Transcend           | 1         | 0.79%   |
| Smart               | 1         | 0.79%   |
| Qimonda             | 1         | 0.79%   |
| KingSpec            | 1         | 0.79%   |
| G.Skill             | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 3.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 3.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 3.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.31%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 3         | 2.31%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.54%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.54%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.54%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 1.54%   |
| Kingston RAM ACR256X64D3S1333C9 2GB SODIMM DDR3 1333MT/s         | 2         | 1.54%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 1.54%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.77%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.77%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.77%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.77%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.77%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                            | 1         | 0.77%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                   | 1         | 0.77%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.77%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                    | 1         | 0.77%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s               | 1         | 0.77%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.77%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.77%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.77%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 1         | 0.77%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 0.77%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.77%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s          | 1         | 0.77%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.77%   |
| SK hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s             | 1         | 0.77%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 48        | 42.86%  |
| DDR4    | 28        | 25%     |
| DDR2    | 15        | 13.39%  |
| SDRAM   | 7         | 6.25%   |
| LPDDR4  | 7         | 6.25%   |
| LPDDR5  | 2         | 1.79%   |
| Unknown | 2         | 1.79%   |
| LPDDR3  | 1         | 0.89%   |
| DRAM    | 1         | 0.89%   |
| DDR     | 1         | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 103       | 94.5%   |
| Row Of Chips | 5         | 4.59%   |
| DIMM         | 1         | 0.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 39        | 32.23%  |
| 4096  | 35        | 28.93%  |
| 8192  | 30        | 24.79%  |
| 1024  | 10        | 8.26%   |
| 16384 | 4         | 3.31%   |
| 32768 | 2         | 1.65%   |
| 6144  | 1         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 36        | 30.51%  |
| 2667    | 16        | 13.56%  |
| 3200    | 15        | 12.71%  |
| 667     | 11        | 9.32%   |
| 4199    | 4         | 3.39%   |
| 3266    | 4         | 3.39%   |
| 2400    | 4         | 3.39%   |
| 1333    | 4         | 3.39%   |
| 975     | 4         | 3.39%   |
| 2048    | 3         | 2.54%   |
| 1334    | 3         | 2.54%   |
| 1066    | 3         | 2.54%   |
| 6400    | 2         | 1.69%   |
| 800     | 2         | 1.69%   |
| Unknown | 2         | 1.69%   |
| 4267    | 1         | 0.85%   |
| 2133    | 1         | 0.85%   |
| 1867    | 1         | 0.85%   |
| 1866    | 1         | 0.85%   |
| 400     | 1         | 0.85%   |

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
| Chicony Electronics                    | 31        | 26.05%  |
| Realtek Semiconductor                  | 10        | 8.4%    |
| IMC Networks                           | 9         | 7.56%   |
| Suyin                                  | 7         | 5.88%   |
| Quanta                                 | 7         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 5.88%   |
| Sunplus Innovation Technology          | 6         | 5.04%   |
| Microdia                               | 6         | 5.04%   |
| Alcor Micro                            | 6         | 5.04%   |
| Silicon Motion                         | 4         | 3.36%   |
| Lite-On Technology                     | 4         | 3.36%   |
| Apple                                  | 4         | 3.36%   |
| Syntek                                 | 3         | 2.52%   |
| Ricoh                                  | 3         | 2.52%   |
| Bison Electronics                      | 3         | 2.52%   |
| Z-Star Microelectronics                | 1         | 0.84%   |
| Samsung Electronics                    | 1         | 0.84%   |
| Pixart Imaging                         | 1         | 0.84%   |
| OmniVision Technologies                | 1         | 0.84%   |
| Luxvisions Innotech Limited            | 1         | 0.84%   |
| Logitech                               | 1         | 0.84%   |
| Aveo Technology                        | 1         | 0.84%   |
| ALi                                    | 1         | 0.84%   |
| Acer                                   | 1         | 0.84%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                           | 6         | 5.04%   |
| Chicony Integrated Camera                               | 5         | 4.2%    |
| Chicony USB 2.0 Camera                                  | 3         | 2.52%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 3         | 2.52%   |
| Alcor Micro USB 2.0 Camera                              | 3         | 2.52%   |
| Syntek Lenovo EasyCamera                                | 2         | 1.68%   |
| Suyin HP TrueVision HD Integrated Webcam                | 2         | 1.68%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.68%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.68%   |
| Quanta HP TrueVision HD Camera                          | 2         | 1.68%   |
| Microdia Integrated Webcam                              | 2         | 1.68%   |
| Lite-On Integrated Camera                               | 2         | 1.68%   |
| Lite-On HP Webcam                                       | 2         | 1.68%   |
| IMC Networks EasyCamera                                 | 2         | 1.68%   |
| Chicony VGA Webcam                                      | 2         | 1.68%   |
| Chicony HP Webcam                                       | 2         | 1.68%   |
| Chicony FJ Camera                                       | 2         | 1.68%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.68%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.68%   |
| Bison Lenovo EasyCamera                                 | 2         | 1.68%   |
| Alcor Micro Acer Integrated Webcam                      | 2         | 1.68%   |
| Z-Star Webcam                                           | 1         | 0.84%   |
| Syntek USB Video Device                                 | 1         | 0.84%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.84%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.84%   |
| Suyin HP Truevision HD                                  | 1         | 0.84%   |
| Suyin HD WebCam                                         | 1         | 0.84%   |
| Suyin Acer/Lenovo Webcam [CN0316]                       | 1         | 0.84%   |
| Sunplus MTD camera                                      | 1         | 0.84%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.84%   |
| Sunplus HP Universal Camera                             | 1         | 0.84%   |
| Sunplus HD WebCam                                       | 1         | 0.84%   |
| Silicon Motion WebCam SC-10HDD13335N                    | 1         | 0.84%   |
| Silicon Motion WebCam SC-0311139N                       | 1         | 0.84%   |
| Silicon Motion Web Camera                               | 1         | 0.84%   |
| Silicon Motion Real HD WebCam                           | 1         | 0.84%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 1         | 0.84%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870]     | 1         | 0.84%   |
| Ricoh Sony Vaio Integrated Webcam                       | 1         | 0.84%   |
| Ricoh Integrated Webcam                                 | 1         | 0.84%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 22.22%  |
| AuthenTec                  | 4         | 22.22%  |
| Upek                       | 2         | 11.11%  |
| Shenzhen Goodix Technology | 2         | 11.11%  |
| LighTuning Technology      | 2         | 11.11%  |
| Synaptics                  | 1         | 5.56%   |
| Samsung Electronics        | 1         | 5.56%   |
| Focal-systems.Corp         | 1         | 5.56%   |
| Elan Microelectronics      | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 11.11%  |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 11.11%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 11.11%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5.56%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 5.56%   |
| Validity Sensors Synaptics WBDI                        | 1         | 5.56%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 5.56%   |
| Samsung Fingerprint Device                             | 1         | 5.56%   |
| LighTuning Fingerprint Reader                          | 1         | 5.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.56%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 5.56%   |
| Elan ELAN:Fingerprint                                  | 1         | 5.56%   |
| AuthenTec Fingerprint Sensor                           | 1         | 5.56%   |
| AuthenTec AES1600                                      | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 40%     |
| Alcor Micro | 3         | 30%     |
| O2 Micro    | 2         | 20%     |
| Upek        | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 20%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 10%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 91        | 64.54%  |
| 1     | 42        | 29.79%  |
| 2     | 8         | 5.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 30.51%  |
| Graphics card            | 12        | 20.34%  |
| Chipcard                 | 10        | 16.95%  |
| Net/wireless             | 5         | 8.47%   |
| Storage                  | 4         | 6.78%   |
| Bluetooth                | 3         | 5.08%   |
| Multimedia controller    | 2         | 3.39%   |
| Sound                    | 1         | 1.69%   |
| Net/ethernet             | 1         | 1.69%   |
| Dvb card                 | 1         | 1.69%   |
| Communication controller | 1         | 1.69%   |
| Camera                   | 1         | 1.69%   |

