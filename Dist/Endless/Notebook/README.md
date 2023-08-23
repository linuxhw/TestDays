Endless - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Endless.

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

Total: 4335

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Nitro AN515-52              | [30748e95eb](https://linux-hardware.org/?probe=30748e95eb) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [dd127ca2df](https://linux-hardware.org/?probe=dd127ca2df) | Aug 08, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [ae5361d56f](https://linux-hardware.org/?probe=ae5361d56f) | Aug 05, 2023 |
| Acer          | Aspire VN7-793G             | [c7e996a3c2](https://linux-hardware.org/?probe=c7e996a3c2) | Aug 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ee147b0313](https://linux-hardware.org/?probe=ee147b0313) | Aug 03, 2023 |
| HP            | ProBook 445 G7              | [96e95e4bd2](https://linux-hardware.org/?probe=96e95e4bd2) | Jul 31, 2023 |
| Acer          | Nitro AN515-52              | [393c4b7fd3](https://linux-hardware.org/?probe=393c4b7fd3) | Jul 29, 2023 |
| HP            | 250 G5 Notebook PC          | [572537c287](https://linux-hardware.org/?probe=572537c287) | Jul 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [501969ed00](https://linux-hardware.org/?probe=501969ed00) | Jul 15, 2023 |
| Dell          | XPS 13 9380                 | [ad75f0a6e0](https://linux-hardware.org/?probe=ad75f0a6e0) | Jul 12, 2023 |
| Acer          | Aspire A515-54              | [64e1f03cea](https://linux-hardware.org/?probe=64e1f03cea) | Jul 12, 2023 |
| Acer          | Aspire A315-53              | [488366cee5](https://linux-hardware.org/?probe=488366cee5) | Jul 08, 2023 |
| Acer          | Nitro AN515-44              | [d695952680](https://linux-hardware.org/?probe=d695952680) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7991ee84b](https://linux-hardware.org/?probe=f7991ee84b) | Jul 06, 2023 |
| Acer          | Nitro AN517-54              | [2943ff2787](https://linux-hardware.org/?probe=2943ff2787) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [708fb65c2c](https://linux-hardware.org/?probe=708fb65c2c) | Jul 05, 2023 |
| Acer          | Aspire ES1-411              | [898ea84872](https://linux-hardware.org/?probe=898ea84872) | Jul 04, 2023 |
| Toshiba       | Satellite L550              | [321ec36f85](https://linux-hardware.org/?probe=321ec36f85) | Jun 25, 2023 |
| Acer          | Aspire A517-51              | [7f4ad14efb](https://linux-hardware.org/?probe=7f4ad14efb) | Jun 25, 2023 |
| Acer          | Aspire A517-51G             | [dc2aebbc48](https://linux-hardware.org/?probe=dc2aebbc48) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | [a8a9689ea6](https://linux-hardware.org/?probe=a8a9689ea6) | Jun 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [84239b2594](https://linux-hardware.org/?probe=84239b2594) | Jun 23, 2023 |
| Acer          | Nitro AN515-44              | [d43ff293c1](https://linux-hardware.org/?probe=d43ff293c1) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [817361caf5](https://linux-hardware.org/?probe=817361caf5) | Jun 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c0dc86bdc1](https://linux-hardware.org/?probe=c0dc86bdc1) | Jun 19, 2023 |
| Lenovo        | G550 20023                  | [a1eac5da7c](https://linux-hardware.org/?probe=a1eac5da7c) | Jun 18, 2023 |
| HP            | ProBook 445 G7              | [71c3b52599](https://linux-hardware.org/?probe=71c3b52599) | Jun 17, 2023 |
| ASUSTek       | GL552VW                     | [f3b0b03ace](https://linux-hardware.org/?probe=f3b0b03ace) | Jun 12, 2023 |
| Acer          | Aspire A517-51              | [01cfb1c93f](https://linux-hardware.org/?probe=01cfb1c93f) | Jun 10, 2023 |
| Acer          | Nitro AN515-44              | [b3531502a8](https://linux-hardware.org/?probe=b3531502a8) | Jun 10, 2023 |
| Dell          | Vostro 1310                 | [05fc6f167c](https://linux-hardware.org/?probe=05fc6f167c) | Jun 09, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [5c63c42a5c](https://linux-hardware.org/?probe=5c63c42a5c) | Jun 04, 2023 |
| Acer          | Aspire A517-51G             | [dc0e29f0bb](https://linux-hardware.org/?probe=dc0e29f0bb) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | [693005f5b4](https://linux-hardware.org/?probe=693005f5b4) | Jun 02, 2023 |
| Acer          | AO756                       | [e135dbe37e](https://linux-hardware.org/?probe=e135dbe37e) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [86666c3371](https://linux-hardware.org/?probe=86666c3371) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8fb981666f](https://linux-hardware.org/?probe=8fb981666f) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [84717aefdf](https://linux-hardware.org/?probe=84717aefdf) | May 22, 2023 |
| HP            | 2000                        | [f0abebdc1e](https://linux-hardware.org/?probe=f0abebdc1e) | May 18, 2023 |
| Sony          | VPCF11M1E                   | [b42c56ac73](https://linux-hardware.org/?probe=b42c56ac73) | May 14, 2023 |
| Lenovo        | G550 20023                  | [33cc483e77](https://linux-hardware.org/?probe=33cc483e77) | May 09, 2023 |
| MSI           | GE75 Raider 10SF            | [e10ccc96bd](https://linux-hardware.org/?probe=e10ccc96bd) | May 07, 2023 |
| MSI           | GE75 Raider 10SF            | [edcaaeed46](https://linux-hardware.org/?probe=edcaaeed46) | May 07, 2023 |
| HP            | Pavilion g6                 | [26830f860f](https://linux-hardware.org/?probe=26830f860f) | May 06, 2023 |
| HP            | Pavilion g6                 | [a78e3941f5](https://linux-hardware.org/?probe=a78e3941f5) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f2c390eb7e](https://linux-hardware.org/?probe=f2c390eb7e) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7046c6c99](https://linux-hardware.org/?probe=f7046c6c99) | May 05, 2023 |
| Acer          | Aspire E1-421               | [45bca26278](https://linux-hardware.org/?probe=45bca26278) | May 05, 2023 |
| HP            | 255 G8 Notebook PC          | [b1429990db](https://linux-hardware.org/?probe=b1429990db) | May 01, 2023 |
| HP            | 255 G8 Notebook PC          | [6d1a7c83c5](https://linux-hardware.org/?probe=6d1a7c83c5) | May 01, 2023 |
| Acer          | Aspire A515-51G             | [388b693b6d](https://linux-hardware.org/?probe=388b693b6d) | May 01, 2023 |
| Sony          | VPCF11M1E                   | [16772fe220](https://linux-hardware.org/?probe=16772fe220) | Apr 29, 2023 |
| Acer          | Nitro AN515-44              | [12ca37afd3](https://linux-hardware.org/?probe=12ca37afd3) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cd6431fbf5](https://linux-hardware.org/?probe=cd6431fbf5) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8a7681ab18](https://linux-hardware.org/?probe=8a7681ab18) | Apr 03, 2023 |
| Acer          | Aspire A515-51G             | [efc8399ce9](https://linux-hardware.org/?probe=efc8399ce9) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7597a96654](https://linux-hardware.org/?probe=7597a96654) | Mar 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2df4a612b4](https://linux-hardware.org/?probe=2df4a612b4) | Mar 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [27ff485a92](https://linux-hardware.org/?probe=27ff485a92) | Mar 25, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [117d507724](https://linux-hardware.org/?probe=117d507724) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a9ffd21a7f](https://linux-hardware.org/?probe=a9ffd21a7f) | Mar 24, 2023 |
| Gigabyte      | G5 KD                       | [32afc6a4cf](https://linux-hardware.org/?probe=32afc6a4cf) | Mar 23, 2023 |
| HP            | EliteBook 840 G3            | [35e1ff95a5](https://linux-hardware.org/?probe=35e1ff95a5) | Mar 23, 2023 |
| HP            | EliteBook 840 G3            | [1a75f9d839](https://linux-hardware.org/?probe=1a75f9d839) | Mar 23, 2023 |
| Acer          | Nitro AN515-44              | [fca39bd9eb](https://linux-hardware.org/?probe=fca39bd9eb) | Mar 22, 2023 |
| Acer          | Nitro AN515-44              | [e07e3320b1](https://linux-hardware.org/?probe=e07e3320b1) | Mar 22, 2023 |
| HP            | Pavilion 17                 | [cb6b6bc8d2](https://linux-hardware.org/?probe=cb6b6bc8d2) | Mar 22, 2023 |
| Lenovo        | S20-30 20421                | [3c1dd3564d](https://linux-hardware.org/?probe=3c1dd3564d) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1292539ef0](https://linux-hardware.org/?probe=1292539ef0) | Mar 19, 2023 |
| Lenovo        | G550 20023                  | [6296457407](https://linux-hardware.org/?probe=6296457407) | Mar 18, 2023 |
| Lenovo        | G550 20023                  | [f5bd764775](https://linux-hardware.org/?probe=f5bd764775) | Mar 18, 2023 |
| Acer          | Nitro AN515-44              | [dd12b2101e](https://linux-hardware.org/?probe=dd12b2101e) | Mar 17, 2023 |
| Lenovo        | G550 20023                  | [c356d98a54](https://linux-hardware.org/?probe=c356d98a54) | Mar 17, 2023 |
| Acer          | Aspire A315-34              | [63676e7012](https://linux-hardware.org/?probe=63676e7012) | Mar 16, 2023 |
| Acer          | Aspire A515-51              | [6e1d22df26](https://linux-hardware.org/?probe=6e1d22df26) | Mar 15, 2023 |
| Acer          | Aspire A315-34              | [bbb4128793](https://linux-hardware.org/?probe=bbb4128793) | Mar 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [1169593829](https://linux-hardware.org/?probe=1169593829) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [76e4cc71f5](https://linux-hardware.org/?probe=76e4cc71f5) | Mar 12, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [8e12f88524](https://linux-hardware.org/?probe=8e12f88524) | Mar 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [06814e6afa](https://linux-hardware.org/?probe=06814e6afa) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [15dd4409fc](https://linux-hardware.org/?probe=15dd4409fc) | Mar 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [3f007adfc7](https://linux-hardware.org/?probe=3f007adfc7) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6ae7081970](https://linux-hardware.org/?probe=6ae7081970) | Mar 10, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e7429f9be3](https://linux-hardware.org/?probe=e7429f9be3) | Mar 09, 2023 |
| ASUSTek       | X541SA                      | [4adcb5ab0f](https://linux-hardware.org/?probe=4adcb5ab0f) | Mar 08, 2023 |
| VTEX          | NOTEBOOK                    | [0b91c54846](https://linux-hardware.org/?probe=0b91c54846) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | [4687219ca3](https://linux-hardware.org/?probe=4687219ca3) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | [687328ccb0](https://linux-hardware.org/?probe=687328ccb0) | Mar 06, 2023 |
| VTEX          | NOTEBOOK                    | [b12a53ec1e](https://linux-hardware.org/?probe=b12a53ec1e) | Mar 06, 2023 |
| HP            | EliteBook 2560p             | [e7040c89e1](https://linux-hardware.org/?probe=e7040c89e1) | Mar 06, 2023 |
| Dell          | Inspiron 5523               | [495dfc19dc](https://linux-hardware.org/?probe=495dfc19dc) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2e4f2069e8](https://linux-hardware.org/?probe=2e4f2069e8) | Mar 06, 2023 |
| Acer          | Aspire A515-54              | [a544ef69d8](https://linux-hardware.org/?probe=a544ef69d8) | Mar 05, 2023 |
| Acer          | Aspire A515-54              | [6c190c594b](https://linux-hardware.org/?probe=6c190c594b) | Mar 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [4cb7f38354](https://linux-hardware.org/?probe=4cb7f38354) | Mar 05, 2023 |
| Acer          | Nitro AN515-54              | [463de722cd](https://linux-hardware.org/?probe=463de722cd) | Mar 04, 2023 |
| Acer          | Aspire A315-53              | [d16e7dcded](https://linux-hardware.org/?probe=d16e7dcded) | Mar 03, 2023 |
| Dell          | Inspiron 5523               | [09ccf58a6b](https://linux-hardware.org/?probe=09ccf58a6b) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [86fac430ca](https://linux-hardware.org/?probe=86fac430ca) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5c3d39f884](https://linux-hardware.org/?probe=5c3d39f884) | Feb 25, 2023 |
| Dell          | Latitude E6440              | [003611b4c7](https://linux-hardware.org/?probe=003611b4c7) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6dd01c6a20](https://linux-hardware.org/?probe=6dd01c6a20) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1b5b668cea](https://linux-hardware.org/?probe=1b5b668cea) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [39f48414bc](https://linux-hardware.org/?probe=39f48414bc) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fe9944c457](https://linux-hardware.org/?probe=fe9944c457) | Feb 23, 2023 |
| Dell          | Vostro 3446                 | [c6df0f1b65](https://linux-hardware.org/?probe=c6df0f1b65) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c99d1595ec](https://linux-hardware.org/?probe=c99d1595ec) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [caccb434d2](https://linux-hardware.org/?probe=caccb434d2) | Feb 21, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6c02ec2d87](https://linux-hardware.org/?probe=6c02ec2d87) | Feb 19, 2023 |
| HP            | 250 G5 Notebook PC          | [ca676dc566](https://linux-hardware.org/?probe=ca676dc566) | Feb 19, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [2953555c08](https://linux-hardware.org/?probe=2953555c08) | Feb 19, 2023 |
| Acer          | Aspire A315-21              | [fe42379585](https://linux-hardware.org/?probe=fe42379585) | Feb 18, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [f53b1c8aeb](https://linux-hardware.org/?probe=f53b1c8aeb) | Feb 18, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [6d7740ca9d](https://linux-hardware.org/?probe=6d7740ca9d) | Feb 17, 2023 |
| Acer          | Nitro AN515-54              | [4e0f0e0310](https://linux-hardware.org/?probe=4e0f0e0310) | Feb 15, 2023 |
| ASUSTek       | X200MA                      | [b01624da44](https://linux-hardware.org/?probe=b01624da44) | Feb 15, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [d177dc7b4d](https://linux-hardware.org/?probe=d177dc7b4d) | Feb 15, 2023 |
| ASUSTek       | X540NA                      | [706e39729c](https://linux-hardware.org/?probe=706e39729c) | Feb 14, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [76621da580](https://linux-hardware.org/?probe=76621da580) | Feb 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [03f90da8d3](https://linux-hardware.org/?probe=03f90da8d3) | Feb 14, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [a8a5ef19de](https://linux-hardware.org/?probe=a8a5ef19de) | Feb 13, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [608ce76690](https://linux-hardware.org/?probe=608ce76690) | Feb 13, 2023 |
| Acer          | Aspire ES1-572              | [24c1c37b05](https://linux-hardware.org/?probe=24c1c37b05) | Feb 13, 2023 |
| ASUSTek       | X541UAK                     | [e27e733bc0](https://linux-hardware.org/?probe=e27e733bc0) | Feb 12, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | [682be07637](https://linux-hardware.org/?probe=682be07637) | Feb 11, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [f8f0fb1a21](https://linux-hardware.org/?probe=f8f0fb1a21) | Feb 11, 2023 |
| HP            | 250 G5 Notebook PC          | [72b0ba099a](https://linux-hardware.org/?probe=72b0ba099a) | Feb 11, 2023 |
| Toshiba       | Satellite L450              | [5a16ded274](https://linux-hardware.org/?probe=5a16ded274) | Feb 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [87b269febc](https://linux-hardware.org/?probe=87b269febc) | Feb 08, 2023 |
| Acer          | Aspire A517-51              | [ab27353a60](https://linux-hardware.org/?probe=ab27353a60) | Feb 08, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [06ffbacba3](https://linux-hardware.org/?probe=06ffbacba3) | Feb 08, 2023 |
| HP            | Notebook                    | [eb0699bb89](https://linux-hardware.org/?probe=eb0699bb89) | Feb 07, 2023 |
| ASUSTek       | X541UAK                     | [62acbef04d](https://linux-hardware.org/?probe=62acbef04d) | Feb 07, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [6fcc29607c](https://linux-hardware.org/?probe=6fcc29607c) | Feb 06, 2023 |
| Acer          | Aspire E5-476G              | [3b8e69dd3a](https://linux-hardware.org/?probe=3b8e69dd3a) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [cfc187a64c](https://linux-hardware.org/?probe=cfc187a64c) | Feb 05, 2023 |
| Acer          | Aspire A515-51G             | [2b37c84303](https://linux-hardware.org/?probe=2b37c84303) | Feb 04, 2023 |
| Microtech     | CoreBook                    | [2ee0649a6e](https://linux-hardware.org/?probe=2ee0649a6e) | Feb 03, 2023 |
| HP            | Stream Notebook PC 14       | [69628da41b](https://linux-hardware.org/?probe=69628da41b) | Feb 03, 2023 |
| HP            | 250 G5 Notebook PC          | [687b1ec2d7](https://linux-hardware.org/?probe=687b1ec2d7) | Feb 02, 2023 |
| Acer          | Nitro AN515-54              | [9aee0a798c](https://linux-hardware.org/?probe=9aee0a798c) | Feb 01, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [4febaa325b](https://linux-hardware.org/?probe=4febaa325b) | Jan 31, 2023 |
| Acer          | Aspire A517-51              | [cb65ba4ce5](https://linux-hardware.org/?probe=cb65ba4ce5) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f1f5def619](https://linux-hardware.org/?probe=f1f5def619) | Jan 28, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [5a32be51f4](https://linux-hardware.org/?probe=5a32be51f4) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [3b41afb262](https://linux-hardware.org/?probe=3b41afb262) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [5d58c53672](https://linux-hardware.org/?probe=5d58c53672) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [b352f0af44](https://linux-hardware.org/?probe=b352f0af44) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [acf75dbe88](https://linux-hardware.org/?probe=acf75dbe88) | Jan 26, 2023 |
| ASUSTek       | Z550SA                      | [f5ac147c1e](https://linux-hardware.org/?probe=f5ac147c1e) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [364a07a435](https://linux-hardware.org/?probe=364a07a435) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [546a896e7f](https://linux-hardware.org/?probe=546a896e7f) | Jan 22, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [53fb561c53](https://linux-hardware.org/?probe=53fb561c53) | Jan 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ed9d60d9b7](https://linux-hardware.org/?probe=ed9d60d9b7) | Jan 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [183de4d0f6](https://linux-hardware.org/?probe=183de4d0f6) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62aa341472](https://linux-hardware.org/?probe=62aa341472) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [22d07dfddf](https://linux-hardware.org/?probe=22d07dfddf) | Jan 18, 2023 |
| Dell          | XPS 13 9360                 | [7302e1ecb2](https://linux-hardware.org/?probe=7302e1ecb2) | Jan 17, 2023 |
| Lenovo        | G450 2949                   | [f9141ba069](https://linux-hardware.org/?probe=f9141ba069) | Jan 17, 2023 |
| Lenovo        | G450 2949                   | [923765c4aa](https://linux-hardware.org/?probe=923765c4aa) | Jan 17, 2023 |
| Acer          | Aspire A315-21              | [b035fd60cd](https://linux-hardware.org/?probe=b035fd60cd) | Jan 15, 2023 |
| Packard Be... | EasyNote ML65               | [e3599cb723](https://linux-hardware.org/?probe=e3599cb723) | Jan 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [f32463429a](https://linux-hardware.org/?probe=f32463429a) | Jan 14, 2023 |
| Acer          | Nitro AN515-44              | [66d71f6da1](https://linux-hardware.org/?probe=66d71f6da1) | Jan 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a33cdf7213](https://linux-hardware.org/?probe=a33cdf7213) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [83f2f14d5c](https://linux-hardware.org/?probe=83f2f14d5c) | Jan 10, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ef10fbe492](https://linux-hardware.org/?probe=ef10fbe492) | Jan 09, 2023 |
| ASUSTek       | S301LA                      | [9745e5ae33](https://linux-hardware.org/?probe=9745e5ae33) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [313f5897bd](https://linux-hardware.org/?probe=313f5897bd) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [79c60c460a](https://linux-hardware.org/?probe=79c60c460a) | Jan 07, 2023 |
| Acer          | Nitro AN515-44              | [1e24b872bd](https://linux-hardware.org/?probe=1e24b872bd) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | [758acf54ff](https://linux-hardware.org/?probe=758acf54ff) | Jan 06, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6e3d10ba74](https://linux-hardware.org/?probe=6e3d10ba74) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | [caa3df2f1c](https://linux-hardware.org/?probe=caa3df2f1c) | Jan 05, 2023 |
| Acer          | Nitro AN515-44              | [c1375455dc](https://linux-hardware.org/?probe=c1375455dc) | Jan 05, 2023 |
| Acer          | Aspire A315-54              | [22b6517ed2](https://linux-hardware.org/?probe=22b6517ed2) | Jan 05, 2023 |
| Acer          | Nitro AN515-54              | [26165b2acb](https://linux-hardware.org/?probe=26165b2acb) | Jan 04, 2023 |
| Acer          | Nitro AN515-54              | [1fd86a44c5](https://linux-hardware.org/?probe=1fd86a44c5) | Jan 04, 2023 |
| ASUSTek       | X510UNR                     | [5ac1da09ba](https://linux-hardware.org/?probe=5ac1da09ba) | Jan 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [37cbf7c1a4](https://linux-hardware.org/?probe=37cbf7c1a4) | Jan 03, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d44828a455](https://linux-hardware.org/?probe=d44828a455) | Dec 30, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [8db34630c3](https://linux-hardware.org/?probe=8db34630c3) | Dec 29, 2022 |
| HP            | Pavilion 17                 | [03976dea5a](https://linux-hardware.org/?probe=03976dea5a) | Dec 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [942fbb1ccb](https://linux-hardware.org/?probe=942fbb1ccb) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d702a6b606](https://linux-hardware.org/?probe=d702a6b606) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [28b89e2321](https://linux-hardware.org/?probe=28b89e2321) | Dec 24, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [81f7e4d804](https://linux-hardware.org/?probe=81f7e4d804) | Dec 22, 2022 |
| Acer          | Aspire 5735                 | [d2850b2e08](https://linux-hardware.org/?probe=d2850b2e08) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [751834957d](https://linux-hardware.org/?probe=751834957d) | Dec 20, 2022 |
| Acer          | Nitro AN515-54              | [5254697dbb](https://linux-hardware.org/?probe=5254697dbb) | Dec 19, 2022 |
| ASUSTek       | X451CAP                     | [358fa50e0c](https://linux-hardware.org/?probe=358fa50e0c) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7b1655d054](https://linux-hardware.org/?probe=7b1655d054) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [07ae580adc](https://linux-hardware.org/?probe=07ae580adc) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5c0150b6ae](https://linux-hardware.org/?probe=5c0150b6ae) | Dec 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7bcd1aa991](https://linux-hardware.org/?probe=7bcd1aa991) | Dec 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [711364b4dd](https://linux-hardware.org/?probe=711364b4dd) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0da6ba8094](https://linux-hardware.org/?probe=0da6ba8094) | Dec 15, 2022 |
| ASUSTek       | N71Vn                       | [579adf052e](https://linux-hardware.org/?probe=579adf052e) | Dec 15, 2022 |
| Acer          | Nitro AN517-51              | [a621dbb00e](https://linux-hardware.org/?probe=a621dbb00e) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [a1f1288337](https://linux-hardware.org/?probe=a1f1288337) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [726380956e](https://linux-hardware.org/?probe=726380956e) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [d262eae22d](https://linux-hardware.org/?probe=d262eae22d) | Dec 12, 2022 |
| Dell          | Inspiron 3542               | [eb1d437253](https://linux-hardware.org/?probe=eb1d437253) | Dec 10, 2022 |
| Dell          | Latitude E6520              | [ec32b72261](https://linux-hardware.org/?probe=ec32b72261) | Dec 09, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [660fe07867](https://linux-hardware.org/?probe=660fe07867) | Dec 07, 2022 |
| Acer          | Aspire A515-54G             | [0bcc1e2664](https://linux-hardware.org/?probe=0bcc1e2664) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2bde4950e9](https://linux-hardware.org/?probe=2bde4950e9) | Dec 02, 2022 |
| Dell          | Latitude E6530              | [c90145516a](https://linux-hardware.org/?probe=c90145516a) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | [81eca2f60e](https://linux-hardware.org/?probe=81eca2f60e) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | [5841aa11f1](https://linux-hardware.org/?probe=5841aa11f1) | Nov 30, 2022 |
| HP            | Pavilion g6                 | [c552ca011c](https://linux-hardware.org/?probe=c552ca011c) | Nov 30, 2022 |
| Acer          | Aspire 5738                 | [a9697f1e7a](https://linux-hardware.org/?probe=a9697f1e7a) | Nov 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c3e10b2149](https://linux-hardware.org/?probe=c3e10b2149) | Nov 26, 2022 |
| Dell          | Latitude E6530              | [9f1bcb6f10](https://linux-hardware.org/?probe=9f1bcb6f10) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9836f71cb7](https://linux-hardware.org/?probe=9836f71cb7) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9b9a13f34f](https://linux-hardware.org/?probe=9b9a13f34f) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [47116ddd3e](https://linux-hardware.org/?probe=47116ddd3e) | Nov 24, 2022 |
| Medion        | Akoya P2214T                | [eb9e0cfbf8](https://linux-hardware.org/?probe=eb9e0cfbf8) | Nov 20, 2022 |
| ASUSTek       | X541UAK                     | [75af06e026](https://linux-hardware.org/?probe=75af06e026) | Nov 20, 2022 |
| Acer          | Nitro AN515-44              | [c6b85f956a](https://linux-hardware.org/?probe=c6b85f956a) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e777561ba5](https://linux-hardware.org/?probe=e777561ba5) | Nov 19, 2022 |
| HP            | 255 G8 Notebook PC          | [218b12df90](https://linux-hardware.org/?probe=218b12df90) | Nov 19, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [5605c0fd97](https://linux-hardware.org/?probe=5605c0fd97) | Nov 19, 2022 |
| HP            | Laptop 15-dy2xxx            | [a49a9f72c4](https://linux-hardware.org/?probe=a49a9f72c4) | Nov 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61bcea3891](https://linux-hardware.org/?probe=61bcea3891) | Nov 13, 2022 |
| Acer          | Aspire 5720Z                | [264c30fac3](https://linux-hardware.org/?probe=264c30fac3) | Nov 13, 2022 |
| Acer          | Aspire 5720Z                | [6e596d88da](https://linux-hardware.org/?probe=6e596d88da) | Nov 12, 2022 |
| Google        | Volet                       | [ad7d4384bc](https://linux-hardware.org/?probe=ad7d4384bc) | Nov 11, 2022 |
| Acer          | Nitro AN515-44              | [91851e068d](https://linux-hardware.org/?probe=91851e068d) | Nov 06, 2022 |
| Intel         | powered classmate PC        | [5e9392864a](https://linux-hardware.org/?probe=5e9392864a) | Nov 03, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c83f37c114](https://linux-hardware.org/?probe=c83f37c114) | Nov 01, 2022 |
| Dell          | Latitude E6530              | [5f82f9b682](https://linux-hardware.org/?probe=5f82f9b682) | Oct 31, 2022 |
| Acer          | Predator G3-571             | [a5c2027983](https://linux-hardware.org/?probe=a5c2027983) | Oct 28, 2022 |
| Acer          | Nitro AN515-44              | [189ac65e5b](https://linux-hardware.org/?probe=189ac65e5b) | Oct 27, 2022 |
| HP            | G71                         | [3223e2fcc8](https://linux-hardware.org/?probe=3223e2fcc8) | Oct 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7daabab955](https://linux-hardware.org/?probe=7daabab955) | Oct 27, 2022 |
| Lenovo        | G500 20236                  | [b5508a855e](https://linux-hardware.org/?probe=b5508a855e) | Oct 26, 2022 |
| Toshiba       | NB300                       | [c5aa7d3c5f](https://linux-hardware.org/?probe=c5aa7d3c5f) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [7274eca48b](https://linux-hardware.org/?probe=7274eca48b) | Oct 23, 2022 |
| ASUSTek       | X540NA                      | [73799d57b3](https://linux-hardware.org/?probe=73799d57b3) | Oct 22, 2022 |
| ASUSTek       | X540NA                      | [bef64e98af](https://linux-hardware.org/?probe=bef64e98af) | Oct 21, 2022 |
| HP            | G71                         | [46b6033e1e](https://linux-hardware.org/?probe=46b6033e1e) | Oct 17, 2022 |
| Acer          | Aspire 5750                 | [4e90ad293c](https://linux-hardware.org/?probe=4e90ad293c) | Oct 17, 2022 |
| Acer          | Nitro AN515-44              | [7293f219d8](https://linux-hardware.org/?probe=7293f219d8) | Oct 16, 2022 |
| Dell          | Latitude E6530              | [174d5aa79f](https://linux-hardware.org/?probe=174d5aa79f) | Oct 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a2e0ee2043](https://linux-hardware.org/?probe=a2e0ee2043) | Oct 15, 2022 |
| Acer          | Aspire A315-34              | [a95d9e55ba](https://linux-hardware.org/?probe=a95d9e55ba) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [62dbb6973e](https://linux-hardware.org/?probe=62dbb6973e) | Oct 11, 2022 |
| Acer          | Aspire A317-52              | [af63fa24cb](https://linux-hardware.org/?probe=af63fa24cb) | Oct 09, 2022 |
| Acer          | Swift SF314-511             | [6270245e93](https://linux-hardware.org/?probe=6270245e93) | Oct 08, 2022 |
| ASUSTek       | X505BP                      | [3ebba89d5e](https://linux-hardware.org/?probe=3ebba89d5e) | Oct 07, 2022 |
| Dell          | Inspiron 3542               | [f8d7d79e14](https://linux-hardware.org/?probe=f8d7d79e14) | Oct 07, 2022 |
| Acer          | Aspire A317-52              | [9e6708de22](https://linux-hardware.org/?probe=9e6708de22) | Oct 06, 2022 |
| Acer          | Swift SF113-31              | [be00c7fd40](https://linux-hardware.org/?probe=be00c7fd40) | Oct 06, 2022 |
| Acer          | Swift SF113-31              | [6821710730](https://linux-hardware.org/?probe=6821710730) | Oct 06, 2022 |
| Dell          | XPS 13 9360                 | [1454b8225c](https://linux-hardware.org/?probe=1454b8225c) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | [10fec0d039](https://linux-hardware.org/?probe=10fec0d039) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | [f30bf7e978](https://linux-hardware.org/?probe=f30bf7e978) | Oct 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c277d88bb6](https://linux-hardware.org/?probe=c277d88bb6) | Oct 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [bec157dc7a](https://linux-hardware.org/?probe=bec157dc7a) | Oct 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [d209f29b89](https://linux-hardware.org/?probe=d209f29b89) | Oct 03, 2022 |
| Acer          | Aspire A317-52              | [c59c599497](https://linux-hardware.org/?probe=c59c599497) | Oct 02, 2022 |
| Acer          | TravelMate 8572T            | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Acer          | Nitro AN515-44              | [149337514c](https://linux-hardware.org/?probe=149337514c) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [fa00f3d0ca](https://linux-hardware.org/?probe=fa00f3d0ca) | Sep 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [05927ed93f](https://linux-hardware.org/?probe=05927ed93f) | Sep 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [53cedccf43](https://linux-hardware.org/?probe=53cedccf43) | Sep 28, 2022 |
| Acer          | Aspire A317-52              | [6cc6160f7c](https://linux-hardware.org/?probe=6cc6160f7c) | Sep 27, 2022 |
| Positivo      | S14CT01                     | [2191cd2dd1](https://linux-hardware.org/?probe=2191cd2dd1) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [de8412e05c](https://linux-hardware.org/?probe=de8412e05c) | Sep 25, 2022 |
| Dell          | Latitude E7240              | [75501a47b5](https://linux-hardware.org/?probe=75501a47b5) | Sep 24, 2022 |
| Acer          | Nitro AN515-44              | [b02d161acb](https://linux-hardware.org/?probe=b02d161acb) | Sep 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b73b2224d1](https://linux-hardware.org/?probe=b73b2224d1) | Sep 23, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [65d258e56a](https://linux-hardware.org/?probe=65d258e56a) | Sep 21, 2022 |
| ASUSTek       | X541UAK                     | [b5a6e3ca5e](https://linux-hardware.org/?probe=b5a6e3ca5e) | Sep 20, 2022 |
| Dell          | XPS 13 9360                 | [2b0c376f77](https://linux-hardware.org/?probe=2b0c376f77) | Sep 20, 2022 |
| ASUSTek       | X441NA                      | [282f984233](https://linux-hardware.org/?probe=282f984233) | Sep 19, 2022 |
| Dell          | XPS 13 9360                 | [01aee97dbd](https://linux-hardware.org/?probe=01aee97dbd) | Sep 15, 2022 |
| HP            | 255 G8 Notebook PC          | [37effb8b3c](https://linux-hardware.org/?probe=37effb8b3c) | Sep 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e2c85682b5](https://linux-hardware.org/?probe=e2c85682b5) | Sep 13, 2022 |
| Sony          | SVE1712L1EW                 | [18400c7a0d](https://linux-hardware.org/?probe=18400c7a0d) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [16cf967fc8](https://linux-hardware.org/?probe=16cf967fc8) | Sep 13, 2022 |
| Sony          | SVE1712L1EW                 | [6a797dc1cf](https://linux-hardware.org/?probe=6a797dc1cf) | Sep 12, 2022 |
| Acer          | Nitro AN515-44              | [9f5bc258b6](https://linux-hardware.org/?probe=9f5bc258b6) | Sep 10, 2022 |
| Acer          | TravelMate P449-G3-MG       | [25d82e82b7](https://linux-hardware.org/?probe=25d82e82b7) | Sep 09, 2022 |
| Acer          | Aspire A515-54              | [745c098d8a](https://linux-hardware.org/?probe=745c098d8a) | Sep 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cc0a825c8e](https://linux-hardware.org/?probe=cc0a825c8e) | Sep 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2959121934](https://linux-hardware.org/?probe=2959121934) | Sep 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0356a8d7a1](https://linux-hardware.org/?probe=0356a8d7a1) | Sep 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f3dcbfead7](https://linux-hardware.org/?probe=f3dcbfead7) | Sep 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [93980a32fc](https://linux-hardware.org/?probe=93980a32fc) | Sep 02, 2022 |
| Dell          | Inspiron 1545               | [6cd44f1137](https://linux-hardware.org/?probe=6cd44f1137) | Sep 02, 2022 |
| Acer          | Nitro AN515-54              | [211edd7b18](https://linux-hardware.org/?probe=211edd7b18) | Aug 28, 2022 |
| Acer          | Aspire A315-53              | [6ba36ee616](https://linux-hardware.org/?probe=6ba36ee616) | Aug 28, 2022 |
| Dell          | Inspiron 1545               | [ff02214b7f](https://linux-hardware.org/?probe=ff02214b7f) | Aug 28, 2022 |
| Acer          | Nitro AN515-44              | [7d3e13cfa9](https://linux-hardware.org/?probe=7d3e13cfa9) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0cadff108e](https://linux-hardware.org/?probe=0cadff108e) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [cc7a3508d4](https://linux-hardware.org/?probe=cc7a3508d4) | Aug 27, 2022 |
| Acer          | Nitro AN515-44              | [b456a14fe0](https://linux-hardware.org/?probe=b456a14fe0) | Aug 24, 2022 |
| Acer          | Nitro AN515-44              | [092dcdf5b7](https://linux-hardware.org/?probe=092dcdf5b7) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d64f8a64fa](https://linux-hardware.org/?probe=d64f8a64fa) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [bb928725a6](https://linux-hardware.org/?probe=bb928725a6) | Aug 23, 2022 |
| Dell          | Latitude E6530              | [2dc6598431](https://linux-hardware.org/?probe=2dc6598431) | Aug 21, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | [ce5ed849b0](https://linux-hardware.org/?probe=ce5ed849b0) | Aug 21, 2022 |
| Acer          | Aspire 7750ZG               | [e0d514dd08](https://linux-hardware.org/?probe=e0d514dd08) | Aug 21, 2022 |
| Acer          | Aspire A517-51              | [0cff943f6b](https://linux-hardware.org/?probe=0cff943f6b) | Aug 20, 2022 |
| Lenovo        | G50-45 80E3                 | [0ed8a39444](https://linux-hardware.org/?probe=0ed8a39444) | Aug 19, 2022 |
| Acer          | Nitro AN515-44              | [aa18fee893](https://linux-hardware.org/?probe=aa18fee893) | Aug 18, 2022 |
| Positivo      | S14CT01                     | [22d8d4f3a2](https://linux-hardware.org/?probe=22d8d4f3a2) | Aug 17, 2022 |
| Positivo      | S14CT01                     | [2b561def97](https://linux-hardware.org/?probe=2b561def97) | Aug 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [837e6e891d](https://linux-hardware.org/?probe=837e6e891d) | Aug 13, 2022 |
| Acer          | Aspire V3-571G              | [f45a97ca40](https://linux-hardware.org/?probe=f45a97ca40) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [074b25e3a3](https://linux-hardware.org/?probe=074b25e3a3) | Aug 12, 2022 |
| Positivo      | C14CR21                     | [6e7b0da365](https://linux-hardware.org/?probe=6e7b0da365) | Aug 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e97781a7cc](https://linux-hardware.org/?probe=e97781a7cc) | Aug 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [19c10fbafb](https://linux-hardware.org/?probe=19c10fbafb) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d34fcfc4f7](https://linux-hardware.org/?probe=d34fcfc4f7) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [350a6d8583](https://linux-hardware.org/?probe=350a6d8583) | Aug 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [abe7afa30f](https://linux-hardware.org/?probe=abe7afa30f) | Aug 09, 2022 |
| Acer          | Nitro AN515-54              | [221d7636db](https://linux-hardware.org/?probe=221d7636db) | Aug 08, 2022 |
| Lenovo        | ThinkPad Edge 0578A25       | [ef0500a1f2](https://linux-hardware.org/?probe=ef0500a1f2) | Aug 04, 2022 |
| Lenovo        | ThinkPad Edge 0578A25       | [b7bd71930c](https://linux-hardware.org/?probe=b7bd71930c) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [03770f280e](https://linux-hardware.org/?probe=03770f280e) | Aug 02, 2022 |
| Sony          | VPCEG33FL                   | [6d371d6c32](https://linux-hardware.org/?probe=6d371d6c32) | Jul 31, 2022 |
| Acer          | Nitro AN515-44              | [1c907403d4](https://linux-hardware.org/?probe=1c907403d4) | Jul 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8b3fd99e18](https://linux-hardware.org/?probe=8b3fd99e18) | Jul 27, 2022 |
| Sony          | VPCEG33FL                   | [886dfc7777](https://linux-hardware.org/?probe=886dfc7777) | Jul 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4ee4fc0689](https://linux-hardware.org/?probe=4ee4fc0689) | Jul 26, 2022 |
| Sony          | VPCEG33FL                   | [8767e87e9e](https://linux-hardware.org/?probe=8767e87e9e) | Jul 24, 2022 |
| Acer          | TravelMate 8572T            | [54e7b50fc7](https://linux-hardware.org/?probe=54e7b50fc7) | Jul 18, 2022 |
| Acer          | Aspire A515-54              | [bffac60888](https://linux-hardware.org/?probe=bffac60888) | Jul 16, 2022 |
| Acer          | Aspire A515-54              | [d52eabbac8](https://linux-hardware.org/?probe=d52eabbac8) | Jul 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [046794ca90](https://linux-hardware.org/?probe=046794ca90) | Jul 15, 2022 |
| Chuwi         | LarkBook                    | [501967d2e1](https://linux-hardware.org/?probe=501967d2e1) | Jul 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [55efce6cdc](https://linux-hardware.org/?probe=55efce6cdc) | Jul 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6231802178](https://linux-hardware.org/?probe=6231802178) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1b31625c12](https://linux-hardware.org/?probe=1b31625c12) | Jul 12, 2022 |
| AMI           | Cherry Trail CR             | [b89687ff8f](https://linux-hardware.org/?probe=b89687ff8f) | Jul 12, 2022 |
| Sony          | VPCEA26FG                   | [c5432e157a](https://linux-hardware.org/?probe=c5432e157a) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [d25b4ecc69](https://linux-hardware.org/?probe=d25b4ecc69) | Jul 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1f42376321](https://linux-hardware.org/?probe=1f42376321) | Jul 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a5c61fc1cf](https://linux-hardware.org/?probe=a5c61fc1cf) | Jul 08, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [41840a0102](https://linux-hardware.org/?probe=41840a0102) | Jul 08, 2022 |
| Acer          | Nitro AN515-44              | [d52a3dc4ed](https://linux-hardware.org/?probe=d52a3dc4ed) | Jul 06, 2022 |
| Acer          | Aspire F5-573G              | [c1978d81c7](https://linux-hardware.org/?probe=c1978d81c7) | Jul 05, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bc1f4a78a2](https://linux-hardware.org/?probe=bc1f4a78a2) | Jul 04, 2022 |
| Sony          | VPCEA26FG                   | [2075c04c4c](https://linux-hardware.org/?probe=2075c04c4c) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [81fff806a4](https://linux-hardware.org/?probe=81fff806a4) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [294f501cdd](https://linux-hardware.org/?probe=294f501cdd) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [af946ca10b](https://linux-hardware.org/?probe=af946ca10b) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d68cd17ca2](https://linux-hardware.org/?probe=d68cd17ca2) | Jun 30, 2022 |
| Dell          | Inspiron 1525               | [8f507b2e8c](https://linux-hardware.org/?probe=8f507b2e8c) | Jun 29, 2022 |
| HP            | Pavilion dv7                | [6338462156](https://linux-hardware.org/?probe=6338462156) | Jun 27, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b56f69ff9c](https://linux-hardware.org/?probe=b56f69ff9c) | Jun 26, 2022 |
| Acer          | Nitro AN515-44              | [694f0baf86](https://linux-hardware.org/?probe=694f0baf86) | Jun 26, 2022 |
| AMI           | Cherry Trail CR             | [0ea2a1f20a](https://linux-hardware.org/?probe=0ea2a1f20a) | Jun 26, 2022 |
| ASUSTek       | X542UN                      | [56e348118b](https://linux-hardware.org/?probe=56e348118b) | Jun 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [87f6da99c4](https://linux-hardware.org/?probe=87f6da99c4) | Jun 25, 2022 |
| Acer          | Nitro AN515-54              | [7559b1f8fa](https://linux-hardware.org/?probe=7559b1f8fa) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | [eb8dbfaa92](https://linux-hardware.org/?probe=eb8dbfaa92) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5eaea4e568](https://linux-hardware.org/?probe=5eaea4e568) | Jun 22, 2022 |
| Dell          | Latitude E6530              | [d456333df9](https://linux-hardware.org/?probe=d456333df9) | Jun 21, 2022 |
| Packard Be... | EasyNote MH36               | [ecd7a50e8e](https://linux-hardware.org/?probe=ecd7a50e8e) | Jun 20, 2022 |
| ASUSTek       | X542UN                      | [83a04b4dc4](https://linux-hardware.org/?probe=83a04b4dc4) | Jun 17, 2022 |
| Acer          | Nitro AN515-44              | [5b70211c3a](https://linux-hardware.org/?probe=5b70211c3a) | Jun 16, 2022 |
| Acer          | Nitro AN515-44              | [edf78ac5ae](https://linux-hardware.org/?probe=edf78ac5ae) | Jun 15, 2022 |
| Acer          | Nitro AN515-44              | [ce3588c536](https://linux-hardware.org/?probe=ce3588c536) | Jun 15, 2022 |
| ASUSTek       | Z550SA                      | [c1c96fa0a4](https://linux-hardware.org/?probe=c1c96fa0a4) | Jun 14, 2022 |
| Acer          | Aspire E1-421               | [7cbe6cfc8f](https://linux-hardware.org/?probe=7cbe6cfc8f) | Jun 13, 2022 |
| Acer          | Aspire E1-421               | [8ac8a79ce1](https://linux-hardware.org/?probe=8ac8a79ce1) | Jun 13, 2022 |
| Acer          | Aspire A514-54G             | [a74cd897c5](https://linux-hardware.org/?probe=a74cd897c5) | Jun 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [35dc89f7ff](https://linux-hardware.org/?probe=35dc89f7ff) | Jun 09, 2022 |
| ASUSTek       | X541UAK                     | [92a20ee191](https://linux-hardware.org/?probe=92a20ee191) | Jun 08, 2022 |
| Positivo      | J14GL11                     | [62ab2ad5f4](https://linux-hardware.org/?probe=62ab2ad5f4) | Jun 08, 2022 |
| Dell          | Latitude E6530              | [f155f4f9a3](https://linux-hardware.org/?probe=f155f4f9a3) | Jun 08, 2022 |
| HP            | Laptop 17z-ca100            | [700d19ab97](https://linux-hardware.org/?probe=700d19ab97) | Jun 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9801d8d5c3](https://linux-hardware.org/?probe=9801d8d5c3) | Jun 05, 2022 |
| Dell          | Latitude E6330              | [775f5f5b15](https://linux-hardware.org/?probe=775f5f5b15) | Jun 03, 2022 |
| Dell          | Latitude E6330              | [e471e0e49d](https://linux-hardware.org/?probe=e471e0e49d) | Jun 03, 2022 |
| Acer          | Aspire A514-54G             | [1019de0d68](https://linux-hardware.org/?probe=1019de0d68) | Jun 01, 2022 |
| Dell          | Inspiron 1525               | [246387e9bc](https://linux-hardware.org/?probe=246387e9bc) | Jun 01, 2022 |
| Dell          | Inspiron 1525               | [1b82b95b9a](https://linux-hardware.org/?probe=1b82b95b9a) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ce70b34b9e](https://linux-hardware.org/?probe=ce70b34b9e) | May 31, 2022 |
| Acer          | Aspire A315-34              | [8b9190338e](https://linux-hardware.org/?probe=8b9190338e) | May 31, 2022 |
| Acer          | Nitro AN515-44              | [c3c66e49ab](https://linux-hardware.org/?probe=c3c66e49ab) | May 30, 2022 |
| Acer          | Aspire A315-51              | [083e3a354a](https://linux-hardware.org/?probe=083e3a354a) | May 29, 2022 |
| Acer          | Nitro AN515-44              | [2383d77ab9](https://linux-hardware.org/?probe=2383d77ab9) | May 29, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [ad2442631e](https://linux-hardware.org/?probe=ad2442631e) | May 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [21c0d575b0](https://linux-hardware.org/?probe=21c0d575b0) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [26d3a29dc1](https://linux-hardware.org/?probe=26d3a29dc1) | May 23, 2022 |
| Acer          | Nitro AN515-54              | [5408aee890](https://linux-hardware.org/?probe=5408aee890) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [d972595598](https://linux-hardware.org/?probe=d972595598) | May 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8f9ca8d66b](https://linux-hardware.org/?probe=8f9ca8d66b) | May 20, 2022 |
| Acer          | Nitro AN515-44              | [82a239d311](https://linux-hardware.org/?probe=82a239d311) | May 18, 2022 |
| Acer          | Nitro AN515-44              | [d93d2fe653](https://linux-hardware.org/?probe=d93d2fe653) | May 17, 2022 |
| Acer          | Nitro AN515-44              | [1752fe60cc](https://linux-hardware.org/?probe=1752fe60cc) | May 17, 2022 |
| Acer          | Nitro AN515-44              | [a9e249f407](https://linux-hardware.org/?probe=a9e249f407) | May 16, 2022 |
| Acer          | Nitro AN515-44              | [412fd25cbf](https://linux-hardware.org/?probe=412fd25cbf) | May 15, 2022 |
| Acer          | Swift SF314-54              | [1624fff74b](https://linux-hardware.org/?probe=1624fff74b) | May 15, 2022 |
| Lenovo        | S10-3                       | [b2eb29a65e](https://linux-hardware.org/?probe=b2eb29a65e) | May 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e7fcde8001](https://linux-hardware.org/?probe=e7fcde8001) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [e633129a51](https://linux-hardware.org/?probe=e633129a51) | May 13, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e90b6752ba](https://linux-hardware.org/?probe=e90b6752ba) | May 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [47e5498b35](https://linux-hardware.org/?probe=47e5498b35) | May 12, 2022 |
| Acer          | Nitro AN515-44              | [e3b90bb036](https://linux-hardware.org/?probe=e3b90bb036) | May 11, 2022 |
| Acer          | Nitro AN515-44              | [241c777ac9](https://linux-hardware.org/?probe=241c777ac9) | May 11, 2022 |
| ASUSTek       | X541UAK                     | [50747765ef](https://linux-hardware.org/?probe=50747765ef) | May 10, 2022 |
| ASUSTek       | X541UAK                     | [c1c837e821](https://linux-hardware.org/?probe=c1c837e821) | May 10, 2022 |
| Lenovo        | V14-IGL 82C2                | [0d1e1d71ee](https://linux-hardware.org/?probe=0d1e1d71ee) | May 08, 2022 |
| Acer          | Aspire A514-54G             | [ec1fa8e360](https://linux-hardware.org/?probe=ec1fa8e360) | May 08, 2022 |
| Lenovo        | V14-IGL 82C2                | [3ad9fd00c2](https://linux-hardware.org/?probe=3ad9fd00c2) | May 08, 2022 |
| Lenovo        | ThinkPad X131e 33691J6      | [1f492cb261](https://linux-hardware.org/?probe=1f492cb261) | May 08, 2022 |
| Acer          | Aspire A514-54G             | [b4b52aad69](https://linux-hardware.org/?probe=b4b52aad69) | May 07, 2022 |
| Dell          | Inspiron 5558               | [3cab561b32](https://linux-hardware.org/?probe=3cab561b32) | May 04, 2022 |
| Dell          | Latitude E6420              | [77d218efc8](https://linux-hardware.org/?probe=77d218efc8) | May 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4516542417](https://linux-hardware.org/?probe=4516542417) | May 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| HP            | 250 G5 Notebook PC          | [0e6717d54b](https://linux-hardware.org/?probe=0e6717d54b) | May 02, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [112d0557c3](https://linux-hardware.org/?probe=112d0557c3) | May 01, 2022 |
| ASUSTek       | X540UA                      | [af0ed39935](https://linux-hardware.org/?probe=af0ed39935) | May 01, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [633bddd44b](https://linux-hardware.org/?probe=633bddd44b) | Apr 30, 2022 |
| Google        | Fleex                       | [212ff0673f](https://linux-hardware.org/?probe=212ff0673f) | Apr 30, 2022 |
| Lenovo        | S10-3                       | [712c2dced9](https://linux-hardware.org/?probe=712c2dced9) | Apr 30, 2022 |
| ASUSTek       | X541UAK                     | [7bac9962d9](https://linux-hardware.org/?probe=7bac9962d9) | Apr 29, 2022 |
| HP            | Pavilion 14                 | [84bde5e223](https://linux-hardware.org/?probe=84bde5e223) | Apr 29, 2022 |
| HP            | Pavilion dv7                | [fd2d8cc4f6](https://linux-hardware.org/?probe=fd2d8cc4f6) | Apr 29, 2022 |
| Acer          | Nitro AN515-44              | [11b568f82d](https://linux-hardware.org/?probe=11b568f82d) | Apr 28, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [58076aa8e9](https://linux-hardware.org/?probe=58076aa8e9) | Apr 28, 2022 |
| Acer          | Aspire A315-34              | [a49e25f2b8](https://linux-hardware.org/?probe=a49e25f2b8) | Apr 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcc0c7612d](https://linux-hardware.org/?probe=bcc0c7612d) | Apr 26, 2022 |
| Acer          | Nitro AN515-44              | [319cbc94dd](https://linux-hardware.org/?probe=319cbc94dd) | Apr 25, 2022 |
| HP            | Notebook                    | [4772a69956](https://linux-hardware.org/?probe=4772a69956) | Apr 23, 2022 |
| Acer          | Nitro AN515-44              | [6e05fa6a88](https://linux-hardware.org/?probe=6e05fa6a88) | Apr 23, 2022 |
| ASUSTek       | X450CP                      | [2518b6daad](https://linux-hardware.org/?probe=2518b6daad) | Apr 22, 2022 |
| ASUSTek       | X450CP                      | [17d51c502f](https://linux-hardware.org/?probe=17d51c502f) | Apr 22, 2022 |
| Dell          | Inspiron 1525               | [b5dbaddd84](https://linux-hardware.org/?probe=b5dbaddd84) | Apr 22, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [b53c2836e9](https://linux-hardware.org/?probe=b53c2836e9) | Apr 21, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [cb2bc8f53e](https://linux-hardware.org/?probe=cb2bc8f53e) | Apr 21, 2022 |
| ASUSTek       | X541UAK                     | [8b54af493a](https://linux-hardware.org/?probe=8b54af493a) | Apr 19, 2022 |
| HP            | 250 G5 Notebook PC          | [5cb8325ed4](https://linux-hardware.org/?probe=5cb8325ed4) | Apr 18, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [7855e19861](https://linux-hardware.org/?probe=7855e19861) | Apr 17, 2022 |
| ASUSTek       | X541UAK                     | [811e032c61](https://linux-hardware.org/?probe=811e032c61) | Apr 16, 2022 |
| Acer          | Aspire E1-572               | [27d5f97167](https://linux-hardware.org/?probe=27d5f97167) | Apr 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [ce5b3c38ab](https://linux-hardware.org/?probe=ce5b3c38ab) | Apr 13, 2022 |
| Fujitsu       | LIFEBOOK A512               | [a477479700](https://linux-hardware.org/?probe=a477479700) | Apr 12, 2022 |
| ASUSTek       | X451CA                      | [865aec543f](https://linux-hardware.org/?probe=865aec543f) | Apr 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [dcd1291b92](https://linux-hardware.org/?probe=dcd1291b92) | Apr 11, 2022 |
| Acer          | Nitro AN515-44              | [6748a96716](https://linux-hardware.org/?probe=6748a96716) | Apr 11, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [e6adfda5ec](https://linux-hardware.org/?probe=e6adfda5ec) | Apr 11, 2022 |
| ASUSTek       | X541UAK                     | [ffb5635168](https://linux-hardware.org/?probe=ffb5635168) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ab7173f335](https://linux-hardware.org/?probe=ab7173f335) | Apr 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b86cec3f38](https://linux-hardware.org/?probe=b86cec3f38) | Apr 10, 2022 |
| ASUSTek       | X540LJ                      | [2eb11881fa](https://linux-hardware.org/?probe=2eb11881fa) | Apr 09, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [4c367d8a9c](https://linux-hardware.org/?probe=4c367d8a9c) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [54bc7d6864](https://linux-hardware.org/?probe=54bc7d6864) | Apr 07, 2022 |
| Acer          | Nitro AN515-44              | [8c8679b57b](https://linux-hardware.org/?probe=8c8679b57b) | Apr 06, 2022 |
| ASUSTek       | 1015PE                      | [0643abbf5b](https://linux-hardware.org/?probe=0643abbf5b) | Apr 05, 2022 |
| Acer          | Nitro AN515-44              | [e007605c2c](https://linux-hardware.org/?probe=e007605c2c) | Apr 05, 2022 |
| Acer          | Nitro AN515-44              | [ab77f43b05](https://linux-hardware.org/?probe=ab77f43b05) | Apr 03, 2022 |
| Acer          | Nitro AN515-44              | [53c0c6467d](https://linux-hardware.org/?probe=53c0c6467d) | Apr 01, 2022 |
| Acer          | Nitro AN515-44              | [6a7bc096c0](https://linux-hardware.org/?probe=6a7bc096c0) | Apr 01, 2022 |
| Multilaser    | PC13X                       | [d62e1676c3](https://linux-hardware.org/?probe=d62e1676c3) | Apr 01, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [21a9f5c811](https://linux-hardware.org/?probe=21a9f5c811) | Apr 01, 2022 |
| Dell          | Latitude E5430 non-vPro     | [28ddf22c68](https://linux-hardware.org/?probe=28ddf22c68) | Mar 31, 2022 |
| Multilaser    | PC13X                       | [e0e93fcf81](https://linux-hardware.org/?probe=e0e93fcf81) | Mar 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2d741207c5](https://linux-hardware.org/?probe=2d741207c5) | Mar 30, 2022 |
| Acer          | Aspire A515-54G             | [b4864a1611](https://linux-hardware.org/?probe=b4864a1611) | Mar 27, 2022 |
| Acer          | Nitro AN515-44              | [29d034d804](https://linux-hardware.org/?probe=29d034d804) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | [d2733b3c95](https://linux-hardware.org/?probe=d2733b3c95) | Mar 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8d1c371df2](https://linux-hardware.org/?probe=8d1c371df2) | Mar 21, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [99dc5cde41](https://linux-hardware.org/?probe=99dc5cde41) | Mar 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d74cd69ff9](https://linux-hardware.org/?probe=d74cd69ff9) | Mar 20, 2022 |
| Acer          | Nitro AN515-44              | [519b33398d](https://linux-hardware.org/?probe=519b33398d) | Mar 20, 2022 |
| Compal        | NCL60/61                    | [39c9e97e85](https://linux-hardware.org/?probe=39c9e97e85) | Mar 19, 2022 |
| HP            | Laptop 17z-ca100            | [048eff2daf](https://linux-hardware.org/?probe=048eff2daf) | Mar 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [591f5cdcc0](https://linux-hardware.org/?probe=591f5cdcc0) | Mar 18, 2022 |
| Philco        | 14I                         | [ceefb7fc2f](https://linux-hardware.org/?probe=ceefb7fc2f) | Mar 18, 2022 |
| Acer          | Nitro AN515-44              | [be2d436df6](https://linux-hardware.org/?probe=be2d436df6) | Mar 17, 2022 |
| Acer          | Nitro AN515-44              | [05d071af74](https://linux-hardware.org/?probe=05d071af74) | Mar 16, 2022 |
| Acer          | Nitro AN515-44              | [83d37bb724](https://linux-hardware.org/?probe=83d37bb724) | Mar 16, 2022 |
| Acer          | Nitro AN515-44              | [e5d7cda06b](https://linux-hardware.org/?probe=e5d7cda06b) | Mar 16, 2022 |
| Intel         | powered classmate PC        | [6938945c70](https://linux-hardware.org/?probe=6938945c70) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [373fa69bd1](https://linux-hardware.org/?probe=373fa69bd1) | Mar 14, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [5ee92a3245](https://linux-hardware.org/?probe=5ee92a3245) | Mar 13, 2022 |
| HP            | 250 G5 Notebook PC          | [3e67ab27db](https://linux-hardware.org/?probe=3e67ab27db) | Mar 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [770f279722](https://linux-hardware.org/?probe=770f279722) | Mar 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [21dfbc138d](https://linux-hardware.org/?probe=21dfbc138d) | Mar 13, 2022 |
| Positivo      | S14CT01                     | [198fc329a3](https://linux-hardware.org/?probe=198fc329a3) | Mar 12, 2022 |
| Acer          | Aspire A114-31              | [aa9bcbb679](https://linux-hardware.org/?probe=aa9bcbb679) | Mar 11, 2022 |
| Acer          | Nitro AN515-54              | [cca64bfd46](https://linux-hardware.org/?probe=cca64bfd46) | Mar 10, 2022 |
| Acer          | Aspire A315-56              | [dbc222289c](https://linux-hardware.org/?probe=dbc222289c) | Mar 10, 2022 |
| Acer          | Aspire 4745Z                | [a3021ea674](https://linux-hardware.org/?probe=a3021ea674) | Mar 06, 2022 |
| Toshiba       | Satellite L755              | [1bb7472f87](https://linux-hardware.org/?probe=1bb7472f87) | Mar 06, 2022 |
| HP            | Laptop 17z-ca100            | [a646411afd](https://linux-hardware.org/?probe=a646411afd) | Mar 06, 2022 |
| Acer          | Aspire A515-54              | [5119ee3a39](https://linux-hardware.org/?probe=5119ee3a39) | Mar 05, 2022 |
| Acer          | Aspire A515-51              | [77e4345afe](https://linux-hardware.org/?probe=77e4345afe) | Mar 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [95296f29bb](https://linux-hardware.org/?probe=95296f29bb) | Mar 02, 2022 |
| ASUSTek       | X451CAP                     | [733cc22d43](https://linux-hardware.org/?probe=733cc22d43) | Feb 26, 2022 |
| Acer          | Nitro AN515-44              | [8340571f28](https://linux-hardware.org/?probe=8340571f28) | Feb 25, 2022 |
| Acer          | Aspire A315-53              | [903ce0415a](https://linux-hardware.org/?probe=903ce0415a) | Feb 25, 2022 |
| HP            | Pavilion dv7                | [46280b758c](https://linux-hardware.org/?probe=46280b758c) | Feb 25, 2022 |
| Acer          | Aspire A315-34              | [d02db54216](https://linux-hardware.org/?probe=d02db54216) | Feb 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [baa1d24da5](https://linux-hardware.org/?probe=baa1d24da5) | Feb 24, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [34efccbe97](https://linux-hardware.org/?probe=34efccbe97) | Feb 22, 2022 |
| Toshiba       | Satellite C50-A-19T         | [c0735b93a0](https://linux-hardware.org/?probe=c0735b93a0) | Feb 22, 2022 |
| Toshiba       | Satellite C50-A-19T         | [c307c3abc8](https://linux-hardware.org/?probe=c307c3abc8) | Feb 22, 2022 |
| Acer          | Aspire A315-54              | [1a5f1021df](https://linux-hardware.org/?probe=1a5f1021df) | Feb 21, 2022 |
| HP            | Pavilion dv7                | [fd1bbe1769](https://linux-hardware.org/?probe=fd1bbe1769) | Feb 21, 2022 |
| HP            | Pavilion dv7                | [da9449422c](https://linux-hardware.org/?probe=da9449422c) | Feb 21, 2022 |
| DEXP          | NH5BT15                     | [c6ef26c1ae](https://linux-hardware.org/?probe=c6ef26c1ae) | Feb 20, 2022 |
| Acer          | Aspire A315-34              | [642e1f0705](https://linux-hardware.org/?probe=642e1f0705) | Feb 20, 2022 |
| Acer          | Aspire A315-34              | [8c976c5259](https://linux-hardware.org/?probe=8c976c5259) | Feb 20, 2022 |
| Acer          | Nitro AN515-44              | [198452fc15](https://linux-hardware.org/?probe=198452fc15) | Feb 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [86af1dc736](https://linux-hardware.org/?probe=86af1dc736) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [823e19e6d3](https://linux-hardware.org/?probe=823e19e6d3) | Feb 19, 2022 |
| Acer          | Nitro AN515-44              | [cce1f45d54](https://linux-hardware.org/?probe=cce1f45d54) | Feb 19, 2022 |
| Lenovo        | G700 20251                  | [2e68ddfdd3](https://linux-hardware.org/?probe=2e68ddfdd3) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [489854bd7b](https://linux-hardware.org/?probe=489854bd7b) | Feb 18, 2022 |
| ASUSTek       | T100TA                      | [9f0a454d8b](https://linux-hardware.org/?probe=9f0a454d8b) | Feb 18, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1582806778](https://linux-hardware.org/?probe=1582806778) | Feb 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ed75c609e4](https://linux-hardware.org/?probe=ed75c609e4) | Feb 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [470a550d41](https://linux-hardware.org/?probe=470a550d41) | Feb 16, 2022 |
| Acer          | Nitro AN515-44              | [21d0529167](https://linux-hardware.org/?probe=21d0529167) | Feb 16, 2022 |
| HP            | Laptop 15s-gr0xxx           | [db6e83a4b8](https://linux-hardware.org/?probe=db6e83a4b8) | Feb 14, 2022 |
| Acer          | Aspire A315-53              | [2a2ca89607](https://linux-hardware.org/?probe=2a2ca89607) | Feb 13, 2022 |
| Acer          | Nitro AN515-44              | [dbacdb1c14](https://linux-hardware.org/?probe=dbacdb1c14) | Feb 11, 2022 |
| Acer          | Nitro AN515-44              | [f886f43d19](https://linux-hardware.org/?probe=f886f43d19) | Feb 11, 2022 |
| Acer          | Nitro AN515-54              | [3f2bbe863b](https://linux-hardware.org/?probe=3f2bbe863b) | Feb 09, 2022 |
| Acer          | Nitro AN515-44              | [74eb28f4a3](https://linux-hardware.org/?probe=74eb28f4a3) | Feb 08, 2022 |
| Acer          | Aspire A315-53              | [345a864747](https://linux-hardware.org/?probe=345a864747) | Feb 06, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [14cfb63e15](https://linux-hardware.org/?probe=14cfb63e15) | Feb 06, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [310e0596c7](https://linux-hardware.org/?probe=310e0596c7) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eed6d95df2](https://linux-hardware.org/?probe=eed6d95df2) | Feb 03, 2022 |
| Dell          | Vostro 2520                 | [a78ce3401f](https://linux-hardware.org/?probe=a78ce3401f) | Jan 31, 2022 |
| Acer          | Nitro AN515-44              | [313d4824d2](https://linux-hardware.org/?probe=313d4824d2) | Jan 29, 2022 |
| Acer          | Aspire A315-53              | [e0b0cbe190](https://linux-hardware.org/?probe=e0b0cbe190) | Jan 29, 2022 |
| Dell          | Inspiron 1525               | [cf0c5309ad](https://linux-hardware.org/?probe=cf0c5309ad) | Jan 29, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6ba91410f8](https://linux-hardware.org/?probe=6ba91410f8) | Jan 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [48ad956cc2](https://linux-hardware.org/?probe=48ad956cc2) | Jan 28, 2022 |
| Acer          | Aspire A517-51              | [62a28ff4d9](https://linux-hardware.org/?probe=62a28ff4d9) | Jan 23, 2022 |
| Acer          | Aspire A315-34              | [8a843419b7](https://linux-hardware.org/?probe=8a843419b7) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c77e8f334](https://linux-hardware.org/?probe=4c77e8f334) | Jan 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f5e870f95b](https://linux-hardware.org/?probe=f5e870f95b) | Jan 21, 2022 |
| ASUSTek       | N55SF                       | [e800e249d1](https://linux-hardware.org/?probe=e800e249d1) | Jan 19, 2022 |
| ASUSTek       | X541UAK                     | [2f55e0a142](https://linux-hardware.org/?probe=2f55e0a142) | Jan 19, 2022 |
| ASUSTek       | N55SF                       | [104263a808](https://linux-hardware.org/?probe=104263a808) | Jan 19, 2022 |
| Acer          | Nitro AN517-51              | [fbcf7fffa8](https://linux-hardware.org/?probe=fbcf7fffa8) | Jan 19, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [1d9c3b162d](https://linux-hardware.org/?probe=1d9c3b162d) | Jan 18, 2022 |
| Acer          | Nitro AN515-54              | [b6d4b36704](https://linux-hardware.org/?probe=b6d4b36704) | Jan 18, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [a84625d725](https://linux-hardware.org/?probe=a84625d725) | Jan 18, 2022 |
| eMachines     | G640                        | [3d750908c7](https://linux-hardware.org/?probe=3d750908c7) | Jan 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3f953ad7f3](https://linux-hardware.org/?probe=3f953ad7f3) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [eecedd12b2](https://linux-hardware.org/?probe=eecedd12b2) | Jan 14, 2022 |
| Acer          | Aspire A515-54              | [3ea50d80ec](https://linux-hardware.org/?probe=3ea50d80ec) | Jan 14, 2022 |
| ASUSTek       | Z550SA                      | [322fa160ae](https://linux-hardware.org/?probe=322fa160ae) | Jan 11, 2022 |
| Acer          | Aspire A315-34              | [52197b0dea](https://linux-hardware.org/?probe=52197b0dea) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [04cd3cf175](https://linux-hardware.org/?probe=04cd3cf175) | Jan 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e23725a744](https://linux-hardware.org/?probe=e23725a744) | Jan 10, 2022 |
| Acer          | Aspire A315-34              | [609662084d](https://linux-hardware.org/?probe=609662084d) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [56d6ea164b](https://linux-hardware.org/?probe=56d6ea164b) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d9bd1bab23](https://linux-hardware.org/?probe=d9bd1bab23) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0ca0e6ddd6](https://linux-hardware.org/?probe=0ca0e6ddd6) | Jan 08, 2022 |
| ASUSTek       | X541UAK                     | [353534e82a](https://linux-hardware.org/?probe=353534e82a) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [bdfe615a8e](https://linux-hardware.org/?probe=bdfe615a8e) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [ca2b9fac6f](https://linux-hardware.org/?probe=ca2b9fac6f) | Jan 07, 2022 |
| HP            | EliteBook 1040 G2           | [ca6f52fbeb](https://linux-hardware.org/?probe=ca6f52fbeb) | Jan 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d453a69dad](https://linux-hardware.org/?probe=d453a69dad) | Jan 06, 2022 |
| Acer          | Aspire A315-51              | [4f31432ca6](https://linux-hardware.org/?probe=4f31432ca6) | Jan 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a43e15b7ad](https://linux-hardware.org/?probe=a43e15b7ad) | Jan 06, 2022 |
| Acer          | Aspire A315-21              | [91548d30f5](https://linux-hardware.org/?probe=91548d30f5) | Jan 06, 2022 |
| HP            | Compaq Mini CQ10-400        | [643f4e101f](https://linux-hardware.org/?probe=643f4e101f) | Jan 05, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [1533754d35](https://linux-hardware.org/?probe=1533754d35) | Jan 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcc46e9fcb](https://linux-hardware.org/?probe=bcc46e9fcb) | Jan 05, 2022 |
| HP            | Compaq Mini CQ10-400        | [ca3df238bc](https://linux-hardware.org/?probe=ca3df238bc) | Jan 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [762281ace3](https://linux-hardware.org/?probe=762281ace3) | Jan 04, 2022 |
| ASUSTek       | X541UAK                     | [bd5145c8b1](https://linux-hardware.org/?probe=bd5145c8b1) | Jan 03, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [4e5ce73412](https://linux-hardware.org/?probe=4e5ce73412) | Jan 02, 2022 |
| Acer          | Swift SF113-31              | [7122c86d4f](https://linux-hardware.org/?probe=7122c86d4f) | Jan 02, 2022 |
| Acer          | Nitro AN515-44              | [be76922082](https://linux-hardware.org/?probe=be76922082) | Jan 02, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [86160c79c7](https://linux-hardware.org/?probe=86160c79c7) | Jan 01, 2022 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | [46498e6c58](https://linux-hardware.org/?probe=46498e6c58) | Dec 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0b4b86fd4d](https://linux-hardware.org/?probe=0b4b86fd4d) | Dec 30, 2021 |
| Sony          | SVF1521A7EB                 | [5d72995b21](https://linux-hardware.org/?probe=5d72995b21) | Dec 30, 2021 |
| Sony          | SVF1521A7EB                 | [7bb54a83fc](https://linux-hardware.org/?probe=7bb54a83fc) | Dec 30, 2021 |
| Acer          | Nitro AN515-54              | [deb4e10a41](https://linux-hardware.org/?probe=deb4e10a41) | Dec 29, 2021 |
| Acer          | Nitro AN515-44              | [0ba9ee7a74](https://linux-hardware.org/?probe=0ba9ee7a74) | Dec 29, 2021 |
| Acer          | Aspire A315-34              | [93ddeaab25](https://linux-hardware.org/?probe=93ddeaab25) | Dec 29, 2021 |
| Acer          | Aspire A315-54K             | [b662c9c046](https://linux-hardware.org/?probe=b662c9c046) | Dec 28, 2021 |
| Acer          | Aspire A315-34              | [af582ea780](https://linux-hardware.org/?probe=af582ea780) | Dec 28, 2021 |
| ASUSTek       | G74Sx                       | [7ae1568f36](https://linux-hardware.org/?probe=7ae1568f36) | Dec 27, 2021 |
| Positivo      | V142N_4G                    | [fb167e6518](https://linux-hardware.org/?probe=fb167e6518) | Dec 27, 2021 |
| Acer          | Nitro AN515-44              | [d0bf339bdf](https://linux-hardware.org/?probe=d0bf339bdf) | Dec 26, 2021 |
| Dell          | System Vostro 3450          | [9499015c46](https://linux-hardware.org/?probe=9499015c46) | Dec 23, 2021 |
| Acer          | Nitro AN515-54              | [3a101db74b](https://linux-hardware.org/?probe=3a101db74b) | Dec 23, 2021 |
| Acer          | Aspire A315-34              | [40e8ac4ece](https://linux-hardware.org/?probe=40e8ac4ece) | Dec 23, 2021 |
| Positivo      | CHT14B                      | [ae9f7801cf](https://linux-hardware.org/?probe=ae9f7801cf) | Dec 23, 2021 |
| Positivo      | CHT14B                      | [3efc353498](https://linux-hardware.org/?probe=3efc353498) | Dec 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [492fc37142](https://linux-hardware.org/?probe=492fc37142) | Dec 22, 2021 |
| ASUSTek       | G74Sx                       | [ac5f615cbd](https://linux-hardware.org/?probe=ac5f615cbd) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [da08b0d873](https://linux-hardware.org/?probe=da08b0d873) | Dec 22, 2021 |
| ASUSTek       | X540UA                      | [4d399918f0](https://linux-hardware.org/?probe=4d399918f0) | Dec 20, 2021 |
| HP            | Notebook                    | [f83e86b312](https://linux-hardware.org/?probe=f83e86b312) | Dec 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e8a4a4a5f4](https://linux-hardware.org/?probe=e8a4a4a5f4) | Dec 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0642db16f6](https://linux-hardware.org/?probe=0642db16f6) | Dec 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ce1a1eb460](https://linux-hardware.org/?probe=ce1a1eb460) | Dec 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bfdb06c0ae](https://linux-hardware.org/?probe=bfdb06c0ae) | Dec 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [75183b17a9](https://linux-hardware.org/?probe=75183b17a9) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d3de4858ff](https://linux-hardware.org/?probe=d3de4858ff) | Dec 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ecf858d3fa](https://linux-hardware.org/?probe=ecf858d3fa) | Dec 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [baac720c6c](https://linux-hardware.org/?probe=baac720c6c) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ac40d89d27](https://linux-hardware.org/?probe=ac40d89d27) | Dec 16, 2021 |
| Acer          | Aspire A315-34              | [c76d68c4fd](https://linux-hardware.org/?probe=c76d68c4fd) | Dec 15, 2021 |
| Acer          | Nitro AN515-44              | [4a44000cf0](https://linux-hardware.org/?probe=4a44000cf0) | Dec 14, 2021 |
| Acer          | Nitro AN515-44              | [44d2be94f6](https://linux-hardware.org/?probe=44d2be94f6) | Dec 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e40a285a7e](https://linux-hardware.org/?probe=e40a285a7e) | Dec 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b2dc5e9741](https://linux-hardware.org/?probe=b2dc5e9741) | Dec 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [74591e1700](https://linux-hardware.org/?probe=74591e1700) | Dec 12, 2021 |
| Acer          | Nitro AN515-44              | [f5ae8cd0ac](https://linux-hardware.org/?probe=f5ae8cd0ac) | Dec 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b328ed77b4](https://linux-hardware.org/?probe=b328ed77b4) | Dec 11, 2021 |
| Dell          | Inspiron 3180               | [0a4edcaa69](https://linux-hardware.org/?probe=0a4edcaa69) | Dec 11, 2021 |
| Toshiba       | Satellite P75-A             | [a225156d55](https://linux-hardware.org/?probe=a225156d55) | Dec 11, 2021 |
| ASUSTek       | X705UAR                     | [74b8b78444](https://linux-hardware.org/?probe=74b8b78444) | Dec 11, 2021 |
| Acer          | Nitro AN515-44              | [1acc5eb194](https://linux-hardware.org/?probe=1acc5eb194) | Dec 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [191c3b9c7e](https://linux-hardware.org/?probe=191c3b9c7e) | Dec 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c7efd05b73](https://linux-hardware.org/?probe=c7efd05b73) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [18e35161ad](https://linux-hardware.org/?probe=18e35161ad) | Dec 10, 2021 |
| Acer          | Aspire A315-34              | [862ca9280c](https://linux-hardware.org/?probe=862ca9280c) | Dec 10, 2021 |
| Chuwi         | HeroBook Air                | [dd5567d4dc](https://linux-hardware.org/?probe=dd5567d4dc) | Dec 08, 2021 |
| Toshiba       | Satellite L300              | [a676b11b67](https://linux-hardware.org/?probe=a676b11b67) | Dec 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2ac4810e93](https://linux-hardware.org/?probe=2ac4810e93) | Dec 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5f9f761ed0](https://linux-hardware.org/?probe=5f9f761ed0) | Dec 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [669a87825e](https://linux-hardware.org/?probe=669a87825e) | Dec 08, 2021 |
| HP            | Unknown                     | [33ca2db025](https://linux-hardware.org/?probe=33ca2db025) | Dec 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [db73d74107](https://linux-hardware.org/?probe=db73d74107) | Dec 07, 2021 |
| Acer          | Aspire A315-34              | [7fe252c0cd](https://linux-hardware.org/?probe=7fe252c0cd) | Dec 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8ef0bff5e1](https://linux-hardware.org/?probe=8ef0bff5e1) | Dec 07, 2021 |
| Acer          | Nitro AN515-44              | [88d9ee29b4](https://linux-hardware.org/?probe=88d9ee29b4) | Dec 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [059c42fd1a](https://linux-hardware.org/?probe=059c42fd1a) | Dec 06, 2021 |
| Acer          | Nitro AN515-54              | [7763d72707](https://linux-hardware.org/?probe=7763d72707) | Dec 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a838b63586](https://linux-hardware.org/?probe=a838b63586) | Dec 05, 2021 |
| Acer          | Aspire E1-572               | [a3524e5c56](https://linux-hardware.org/?probe=a3524e5c56) | Dec 05, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [aa4d4e3b08](https://linux-hardware.org/?probe=aa4d4e3b08) | Dec 04, 2021 |
| Acer          | Nitro AN515-44              | [a824747d21](https://linux-hardware.org/?probe=a824747d21) | Dec 02, 2021 |
| Acer          | Aspire A315-34              | [9bbfd01bca](https://linux-hardware.org/?probe=9bbfd01bca) | Dec 01, 2021 |
| Acer          | Aspire A315-53              | [18d91295e1](https://linux-hardware.org/?probe=18d91295e1) | Dec 01, 2021 |
| Acer          | Nitro AN515-54              | [991967c2ff](https://linux-hardware.org/?probe=991967c2ff) | Nov 30, 2021 |
| Acer          | Nitro AN515-44              | [7edf9fe1b5](https://linux-hardware.org/?probe=7edf9fe1b5) | Nov 30, 2021 |
| Acer          | Nitro AN517-51              | [e7af37db76](https://linux-hardware.org/?probe=e7af37db76) | Nov 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ea985c61da](https://linux-hardware.org/?probe=ea985c61da) | Nov 29, 2021 |
| Acer          | TravelMate P253             | [cc535c766a](https://linux-hardware.org/?probe=cc535c766a) | Nov 29, 2021 |
| Acer          | Nitro AN515-44              | [71e47d66a9](https://linux-hardware.org/?probe=71e47d66a9) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | [7add4c45f0](https://linux-hardware.org/?probe=7add4c45f0) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | [c3ac874c98](https://linux-hardware.org/?probe=c3ac874c98) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | [02b7a680cd](https://linux-hardware.org/?probe=02b7a680cd) | Nov 28, 2021 |
| ASUSTek       | X541UAK                     | [bb138385d2](https://linux-hardware.org/?probe=bb138385d2) | Nov 27, 2021 |
| Acer          | Nitro AN515-54              | [b63d468197](https://linux-hardware.org/?probe=b63d468197) | Nov 27, 2021 |
| Sony          | VPCCB35FG                   | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [d6acd43784](https://linux-hardware.org/?probe=d6acd43784) | Nov 25, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [e820cb3456](https://linux-hardware.org/?probe=e820cb3456) | Nov 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [c420169ce7](https://linux-hardware.org/?probe=c420169ce7) | Nov 25, 2021 |
| Acer          | Nitro AN515-54              | [4766af9ef7](https://linux-hardware.org/?probe=4766af9ef7) | Nov 25, 2021 |
| Acer          | Aspire A315-53              | [9dcd5129ea](https://linux-hardware.org/?probe=9dcd5129ea) | Nov 24, 2021 |
| Dell          | Inspiron N5110              | [ea27790fc4](https://linux-hardware.org/?probe=ea27790fc4) | Nov 23, 2021 |
| Acer          | Nitro AN515-44              | [9fd987e7d8](https://linux-hardware.org/?probe=9fd987e7d8) | Nov 23, 2021 |
| Acer          | Nitro AN515-43              | [457a2ff293](https://linux-hardware.org/?probe=457a2ff293) | Nov 23, 2021 |
| Toshiba       | Satellite Pro C850-1D5      | [22ed560714](https://linux-hardware.org/?probe=22ed560714) | Nov 21, 2021 |
| ASUSTek       | X450CP                      | [7228a5157c](https://linux-hardware.org/?probe=7228a5157c) | Nov 20, 2021 |
| Toshiba       | IS 1462B                    | [682a8f788c](https://linux-hardware.org/?probe=682a8f788c) | Nov 20, 2021 |
| Acer          | Aspire 4745                 | [9edc4a1dd4](https://linux-hardware.org/?probe=9edc4a1dd4) | Nov 19, 2021 |
| HP            | ENVY 15                     | [31e0758aad](https://linux-hardware.org/?probe=31e0758aad) | Nov 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1784f93056](https://linux-hardware.org/?probe=1784f93056) | Nov 18, 2021 |
| Acer          | Nitro AN515-44              | [d71fa6378d](https://linux-hardware.org/?probe=d71fa6378d) | Nov 17, 2021 |
| MSI           | VR610                       | [9dd3927cf1](https://linux-hardware.org/?probe=9dd3927cf1) | Nov 15, 2021 |
| MSI           | VR610                       | [fa0f1da6d7](https://linux-hardware.org/?probe=fa0f1da6d7) | Nov 15, 2021 |
| Acer          | Nitro AN515-44              | [328668f616](https://linux-hardware.org/?probe=328668f616) | Nov 14, 2021 |
| Acer          | Aspire A515-54              | [7f5b5d0c7a](https://linux-hardware.org/?probe=7f5b5d0c7a) | Nov 13, 2021 |
| Acer          | Aspire A315-34              | [e9840b2a27](https://linux-hardware.org/?probe=e9840b2a27) | Nov 13, 2021 |
| Acer          | Nitro AN515-54              | [2a98c5ad7b](https://linux-hardware.org/?probe=2a98c5ad7b) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [e0c343709d](https://linux-hardware.org/?probe=e0c343709d) | Nov 12, 2021 |
| ASUSTek       | X540NA                      | [86bce5bb0d](https://linux-hardware.org/?probe=86bce5bb0d) | Nov 12, 2021 |
| Packard Be... | EasyNote TN36               | [17ebc64721](https://linux-hardware.org/?probe=17ebc64721) | Nov 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [b79aef683b](https://linux-hardware.org/?probe=b79aef683b) | Nov 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b2e5c211fc](https://linux-hardware.org/?probe=b2e5c211fc) | Nov 10, 2021 |
| HP            | Pavilion dv7                | [3c3e5bc872](https://linux-hardware.org/?probe=3c3e5bc872) | Nov 08, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | [4bc0687791](https://linux-hardware.org/?probe=4bc0687791) | Nov 08, 2021 |
| HP            | 255 G8 Notebook PC          | [8b35cac0f6](https://linux-hardware.org/?probe=8b35cac0f6) | Nov 07, 2021 |
| HP            | 255 G8 Notebook PC          | [fd582fb82b](https://linux-hardware.org/?probe=fd582fb82b) | Nov 07, 2021 |
| Dell          | Latitude E7440              | [816aaeac91](https://linux-hardware.org/?probe=816aaeac91) | Nov 06, 2021 |
| Dell          | Latitude E7440              | [bdd82f1a23](https://linux-hardware.org/?probe=bdd82f1a23) | Nov 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [81d7a98b1a](https://linux-hardware.org/?probe=81d7a98b1a) | Nov 05, 2021 |
| Acer          | Aspire ES1-533              | [14a4c57e27](https://linux-hardware.org/?probe=14a4c57e27) | Nov 05, 2021 |
| Toshiba       | IS 1462B                    | [a5538db795](https://linux-hardware.org/?probe=a5538db795) | Nov 04, 2021 |
| ASUSTek       | X442UAR                     | [0db140fa3d](https://linux-hardware.org/?probe=0db140fa3d) | Nov 03, 2021 |
| Sony          | VPCYB1S1E                   | [bbe04676c1](https://linux-hardware.org/?probe=bbe04676c1) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | [09eba8bb5f](https://linux-hardware.org/?probe=09eba8bb5f) | Nov 02, 2021 |
| Acer          | Nitro AN515-44              | [754d944557](https://linux-hardware.org/?probe=754d944557) | Nov 01, 2021 |
| Acer          | Aspire A315-53              | [4faa88a423](https://linux-hardware.org/?probe=4faa88a423) | Nov 01, 2021 |
| Acer          | Aspire A515-54G             | [807a8b23ce](https://linux-hardware.org/?probe=807a8b23ce) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8cdb34dbc8](https://linux-hardware.org/?probe=8cdb34dbc8) | Nov 01, 2021 |
| Standard      | AHV                         | [a960753588](https://linux-hardware.org/?probe=a960753588) | Oct 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [67a9ba5988](https://linux-hardware.org/?probe=67a9ba5988) | Oct 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9145964032](https://linux-hardware.org/?probe=9145964032) | Oct 30, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [34f2870a95](https://linux-hardware.org/?probe=34f2870a95) | Oct 30, 2021 |
| Acer          | Nitro AN515-54              | [bc9dc107d1](https://linux-hardware.org/?probe=bc9dc107d1) | Oct 30, 2021 |
| Acer          | Aspire A515-54G             | [7463facb20](https://linux-hardware.org/?probe=7463facb20) | Oct 29, 2021 |
| Acer          | Aspire A515-54G             | [270d4c1d21](https://linux-hardware.org/?probe=270d4c1d21) | Oct 28, 2021 |
| Dell          | Latitude E7240              | [18213a2e29](https://linux-hardware.org/?probe=18213a2e29) | Oct 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c4ffe3d08b](https://linux-hardware.org/?probe=c4ffe3d08b) | Oct 28, 2021 |
| Chuwi         | GemiBook                    | [f40d5fd5a7](https://linux-hardware.org/?probe=f40d5fd5a7) | Oct 27, 2021 |
| Acer          | Nitro AN515-55              | [2b3ef0e291](https://linux-hardware.org/?probe=2b3ef0e291) | Oct 26, 2021 |
| ASUSTek       | X540LA                      | [c947e5b1ea](https://linux-hardware.org/?probe=c947e5b1ea) | Oct 26, 2021 |
| Acer          | Nitro AN515-55              | [2d7ac3338d](https://linux-hardware.org/?probe=2d7ac3338d) | Oct 26, 2021 |
| Acer          | Aspire A315-53              | [e348a818bd](https://linux-hardware.org/?probe=e348a818bd) | Oct 26, 2021 |
| Acer          | Nitro AN515-43              | [1e8a2612aa](https://linux-hardware.org/?probe=1e8a2612aa) | Oct 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [905ef359d4](https://linux-hardware.org/?probe=905ef359d4) | Oct 24, 2021 |
| HP            | 650                         | [22e5d1948a](https://linux-hardware.org/?probe=22e5d1948a) | Oct 24, 2021 |
| Acer          | Aspire A315-34              | [f901b7640e](https://linux-hardware.org/?probe=f901b7640e) | Oct 24, 2021 |
| Acer          | Nitro AN517-51              | [271c2188cb](https://linux-hardware.org/?probe=271c2188cb) | Oct 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2f6634b953](https://linux-hardware.org/?probe=2f6634b953) | Oct 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [985d10d314](https://linux-hardware.org/?probe=985d10d314) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [35a40c6757](https://linux-hardware.org/?probe=35a40c6757) | Oct 21, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [21379aad70](https://linux-hardware.org/?probe=21379aad70) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fb8b55960a](https://linux-hardware.org/?probe=fb8b55960a) | Oct 20, 2021 |
| Acer          | Nitro AN515-44              | [e00a2deae3](https://linux-hardware.org/?probe=e00a2deae3) | Oct 20, 2021 |
| Notebook      | W840SN Series               | [4baeb2cafc](https://linux-hardware.org/?probe=4baeb2cafc) | Oct 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [05fb4b3bb3](https://linux-hardware.org/?probe=05fb4b3bb3) | Oct 20, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [cc0290a8df](https://linux-hardware.org/?probe=cc0290a8df) | Oct 18, 2021 |
| ASUSTek       | X540NV                      | [9b9d65fa43](https://linux-hardware.org/?probe=9b9d65fa43) | Oct 17, 2021 |
| ASUSTek       | X540NV                      | [e6c44be17a](https://linux-hardware.org/?probe=e6c44be17a) | Oct 17, 2021 |
| Acer          | Aspire A515-54G             | [baebf9648a](https://linux-hardware.org/?probe=baebf9648a) | Oct 17, 2021 |
| Acer          | Aspire A515-54G             | [a306e628c3](https://linux-hardware.org/?probe=a306e628c3) | Oct 17, 2021 |
| Acer          | Nitro AN515-54              | [ec55317836](https://linux-hardware.org/?probe=ec55317836) | Oct 16, 2021 |
| ASUSTek       | Z550SA                      | [9728ec8a83](https://linux-hardware.org/?probe=9728ec8a83) | Oct 15, 2021 |
| Acer          | Nitro AN517-51              | [a6d2f51c46](https://linux-hardware.org/?probe=a6d2f51c46) | Oct 15, 2021 |
| LG Electro... | U460-G.BG31P1               | [082c923ad8](https://linux-hardware.org/?probe=082c923ad8) | Oct 15, 2021 |
| LG Electro... | U460-G.BG31P1               | [a2979e1c5f](https://linux-hardware.org/?probe=a2979e1c5f) | Oct 15, 2021 |
| Intel         | Unknown                     | [6173409d40](https://linux-hardware.org/?probe=6173409d40) | Oct 15, 2021 |
| HP            | 2000                        | [e46637441a](https://linux-hardware.org/?probe=e46637441a) | Oct 13, 2021 |
| Acer          | Aspire A315-53              | [0a00ed81de](https://linux-hardware.org/?probe=0a00ed81de) | Oct 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [13085adae8](https://linux-hardware.org/?probe=13085adae8) | Oct 12, 2021 |
| Acer          | Aspire A315-42G             | [5b667bff5d](https://linux-hardware.org/?probe=5b667bff5d) | Oct 12, 2021 |
| Acer          | Nitro AN515-43              | [e6eee85025](https://linux-hardware.org/?probe=e6eee85025) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [0acb396573](https://linux-hardware.org/?probe=0acb396573) | Oct 11, 2021 |
| Acer          | Aspire A315-51              | [d79188a009](https://linux-hardware.org/?probe=d79188a009) | Oct 10, 2021 |
| Acer          | Aspire A315-51              | [aae51881da](https://linux-hardware.org/?probe=aae51881da) | Oct 10, 2021 |
| Acer          | Nitro AN515-54              | [47d670e622](https://linux-hardware.org/?probe=47d670e622) | Oct 10, 2021 |
| Acer          | Nitro AN515-54              | [5bba08307b](https://linux-hardware.org/?probe=5bba08307b) | Oct 10, 2021 |
| Acer          | Nitro AN515-54              | [f15efc966d](https://linux-hardware.org/?probe=f15efc966d) | Oct 08, 2021 |
| Acer          | Aspire A515-54              | [d5dbcb7130](https://linux-hardware.org/?probe=d5dbcb7130) | Oct 06, 2021 |
| Acer          | Aspire A515-54              | [4ca9b7c23a](https://linux-hardware.org/?probe=4ca9b7c23a) | Oct 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [008072f061](https://linux-hardware.org/?probe=008072f061) | Oct 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0ea95296c3](https://linux-hardware.org/?probe=0ea95296c3) | Oct 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9620b94a87](https://linux-hardware.org/?probe=9620b94a87) | Oct 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de1fa7c989](https://linux-hardware.org/?probe=de1fa7c989) | Oct 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [44813d71e9](https://linux-hardware.org/?probe=44813d71e9) | Oct 03, 2021 |
| Acer          | Nitro AN515-54              | [f6aeb86bde](https://linux-hardware.org/?probe=f6aeb86bde) | Oct 02, 2021 |
| Acer          | Aspire A315-34              | [ffb9699d7a](https://linux-hardware.org/?probe=ffb9699d7a) | Oct 02, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [3a0cd09aa4](https://linux-hardware.org/?probe=3a0cd09aa4) | Oct 01, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [c69f22bca8](https://linux-hardware.org/?probe=c69f22bca8) | Oct 01, 2021 |
| Acer          | Aspire A315-21              | [1b6bb85e6b](https://linux-hardware.org/?probe=1b6bb85e6b) | Sep 30, 2021 |
| Acer          | Aspire A315-21              | [aa5e0ddd18](https://linux-hardware.org/?probe=aa5e0ddd18) | Sep 30, 2021 |
| Sony          | VPCCB3P1E                   | [963f47731d](https://linux-hardware.org/?probe=963f47731d) | Sep 28, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [032d34e75b](https://linux-hardware.org/?probe=032d34e75b) | Sep 28, 2021 |
| Dell          | Latitude E5520              | [9b959d4529](https://linux-hardware.org/?probe=9b959d4529) | Sep 28, 2021 |
| HP            | Pavilion g4                 | [bb0793d3ab](https://linux-hardware.org/?probe=bb0793d3ab) | Sep 27, 2021 |
| Sony          | VPCEA47FX                   | [630184b246](https://linux-hardware.org/?probe=630184b246) | Sep 27, 2021 |
| Acer          | Aspire A515-54G             | [65f21b6089](https://linux-hardware.org/?probe=65f21b6089) | Sep 26, 2021 |
| Acer          | Aspire 5715Z                | [a44995aac4](https://linux-hardware.org/?probe=a44995aac4) | Sep 25, 2021 |
| ASUSTek       | X510UN                      | [438b06795d](https://linux-hardware.org/?probe=438b06795d) | Sep 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5dc4b1b49b](https://linux-hardware.org/?probe=5dc4b1b49b) | Sep 25, 2021 |
| Acer          | Nitro AN515-54              | [1f03dc33de](https://linux-hardware.org/?probe=1f03dc33de) | Sep 23, 2021 |
| Acer          | Aspire A315-54              | [f06a523887](https://linux-hardware.org/?probe=f06a523887) | Sep 21, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [1e0de1e13f](https://linux-hardware.org/?probe=1e0de1e13f) | Sep 20, 2021 |
| ASUSTek       | X541UAK                     | [c0303b03f0](https://linux-hardware.org/?probe=c0303b03f0) | Sep 20, 2021 |
| Positivo      | S14CT01                     | [0d1ab84e09](https://linux-hardware.org/?probe=0d1ab84e09) | Sep 19, 2021 |
| Acer          | Nitro AN515-54              | [25fd382b32](https://linux-hardware.org/?probe=25fd382b32) | Sep 19, 2021 |
| HP            | Pavilion x2 Detachable P... | [1332fd2ca2](https://linux-hardware.org/?probe=1332fd2ca2) | Sep 16, 2021 |
| HP            | Pavilion x2 Detachable P... | [bf8d32d4f7](https://linux-hardware.org/?probe=bf8d32d4f7) | Sep 16, 2021 |
| Gateway       | NV47H                       | [8cef362c2e](https://linux-hardware.org/?probe=8cef362c2e) | Sep 15, 2021 |
| Gateway       | NV47H                       | [0ad04889c5](https://linux-hardware.org/?probe=0ad04889c5) | Sep 15, 2021 |
| Acer          | Nitro AN515-54              | [6a3592ad63](https://linux-hardware.org/?probe=6a3592ad63) | Sep 15, 2021 |
| HP            | Pavilion x2 Detachable P... | [c33e445621](https://linux-hardware.org/?probe=c33e445621) | Sep 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4f393c5347](https://linux-hardware.org/?probe=4f393c5347) | Sep 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1465a2e9d6](https://linux-hardware.org/?probe=1465a2e9d6) | Sep 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [a6221df8f8](https://linux-hardware.org/?probe=a6221df8f8) | Sep 10, 2021 |
| Acer          | Nitro AN515-54              | [62020026f9](https://linux-hardware.org/?probe=62020026f9) | Sep 07, 2021 |
| Acer          | Nitro AN515-44              | [550876baee](https://linux-hardware.org/?probe=550876baee) | Sep 07, 2021 |
| Acer          | Nitro AN515-54              | [ff1e6a6f98](https://linux-hardware.org/?probe=ff1e6a6f98) | Sep 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9e4676c4a4](https://linux-hardware.org/?probe=9e4676c4a4) | Sep 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c751938f66](https://linux-hardware.org/?probe=c751938f66) | Sep 03, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9df60e9850](https://linux-hardware.org/?probe=9df60e9850) | Sep 03, 2021 |
| Acer          | Nitro AN515-44              | [556461d567](https://linux-hardware.org/?probe=556461d567) | Sep 03, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0e9da9320c](https://linux-hardware.org/?probe=0e9da9320c) | Sep 03, 2021 |
| Acer          | Aspire A515-54              | [71929d46ed](https://linux-hardware.org/?probe=71929d46ed) | Sep 02, 2021 |
| Acer          | Extensa 2540                | [aadcdfe942](https://linux-hardware.org/?probe=aadcdfe942) | Sep 02, 2021 |
| Acer          | Unknown                     | [e05afa34e0](https://linux-hardware.org/?probe=e05afa34e0) | Sep 02, 2021 |
| Dell          | Latitude E7450              | [3bcc5591b8](https://linux-hardware.org/?probe=3bcc5591b8) | Sep 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [47c2053681](https://linux-hardware.org/?probe=47c2053681) | Sep 02, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [4765b87a68](https://linux-hardware.org/?probe=4765b87a68) | Sep 01, 2021 |
| HP            | Notebook                    | [7b28a98a35](https://linux-hardware.org/?probe=7b28a98a35) | Sep 01, 2021 |
| HP            | Notebook                    | [7fada0ab8c](https://linux-hardware.org/?probe=7fada0ab8c) | Sep 01, 2021 |
| Acer          | Nitro AN515-54              | [7a1f1f60c1](https://linux-hardware.org/?probe=7a1f1f60c1) | Aug 31, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [c2b7f1ee7c](https://linux-hardware.org/?probe=c2b7f1ee7c) | Aug 30, 2021 |
| HP            | Pavilion x2 Detachable      | [6624e2e100](https://linux-hardware.org/?probe=6624e2e100) | Aug 30, 2021 |
| Acer          | Aspire A515-54G             | [d072375b90](https://linux-hardware.org/?probe=d072375b90) | Aug 30, 2021 |
| Toshiba       | Satellite C55-C             | [ebe9f952cc](https://linux-hardware.org/?probe=ebe9f952cc) | Aug 29, 2021 |
| ASUSTek       | X450CP                      | [d646ffd8db](https://linux-hardware.org/?probe=d646ffd8db) | Aug 29, 2021 |
| Toshiba       | Satellite L850-B4S          | [f4f5b3c9aa](https://linux-hardware.org/?probe=f4f5b3c9aa) | Aug 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | [954900ccc6](https://linux-hardware.org/?probe=954900ccc6) | Aug 28, 2021 |
| Acer          | Nitro AN515-44              | [b962febc08](https://linux-hardware.org/?probe=b962febc08) | Aug 27, 2021 |
| Acer          | Nitro AN515-44              | [9860810902](https://linux-hardware.org/?probe=9860810902) | Aug 27, 2021 |
| Acer          | Nitro AN515-43              | [051ab1f020](https://linux-hardware.org/?probe=051ab1f020) | Aug 25, 2021 |
| Acer          | Aspire A315-34              | [2bafe062e1](https://linux-hardware.org/?probe=2bafe062e1) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [7e6a9f0430](https://linux-hardware.org/?probe=7e6a9f0430) | Aug 25, 2021 |
| HP            | 2000                        | [468208d07b](https://linux-hardware.org/?probe=468208d07b) | Aug 24, 2021 |
| Acer          | Nitro AN517-51              | [71ccda2082](https://linux-hardware.org/?probe=71ccda2082) | Aug 24, 2021 |
| Acer          | Nitro AN515-44              | [9d3109723f](https://linux-hardware.org/?probe=9d3109723f) | Aug 24, 2021 |
| Toshiba       | Satellite L850-B4S          | [c6554594e6](https://linux-hardware.org/?probe=c6554594e6) | Aug 23, 2021 |
| HP            | 2000                        | [51508a6277](https://linux-hardware.org/?probe=51508a6277) | Aug 23, 2021 |
| LG Electro... | N450-P.BE55P1               | [45e186ba9b](https://linux-hardware.org/?probe=45e186ba9b) | Aug 23, 2021 |
| LG Electro... | N450-P.BE55P1               | [c36379f182](https://linux-hardware.org/?probe=c36379f182) | Aug 23, 2021 |
| Unknown       | Unknown                     | [e492f61253](https://linux-hardware.org/?probe=e492f61253) | Aug 22, 2021 |
| Unknown       | Unknown                     | [cd6f08757d](https://linux-hardware.org/?probe=cd6f08757d) | Aug 22, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [dd684f03ed](https://linux-hardware.org/?probe=dd684f03ed) | Aug 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [04b98d9bb1](https://linux-hardware.org/?probe=04b98d9bb1) | Aug 21, 2021 |
| Acer          | Nitro AN515-44              | [c8d4e3b3d3](https://linux-hardware.org/?probe=c8d4e3b3d3) | Aug 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6c1165c1e8](https://linux-hardware.org/?probe=6c1165c1e8) | Aug 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [aac5b963b0](https://linux-hardware.org/?probe=aac5b963b0) | Aug 19, 2021 |
| Acer          | Aspire A315-34              | [a33d74d8e4](https://linux-hardware.org/?probe=a33d74d8e4) | Aug 19, 2021 |
| Acer          | Nitro AN515-44              | [4cb9827a7f](https://linux-hardware.org/?probe=4cb9827a7f) | Aug 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [edb03c8635](https://linux-hardware.org/?probe=edb03c8635) | Aug 19, 2021 |
| Acer          | Nitro AN515-54              | [52732fb8ca](https://linux-hardware.org/?probe=52732fb8ca) | Aug 19, 2021 |
| Positivo      | WCBT1013                    | [83538351b9](https://linux-hardware.org/?probe=83538351b9) | Aug 18, 2021 |
| Acer          | Aspire A315-34              | [19982a455b](https://linux-hardware.org/?probe=19982a455b) | Aug 18, 2021 |
| Acer          | Nitro AN515-54              | [646a9b0d66](https://linux-hardware.org/?probe=646a9b0d66) | Aug 17, 2021 |
| Acer          | Predator G3-571             | [779126deb2](https://linux-hardware.org/?probe=779126deb2) | Aug 17, 2021 |
| Acer          | Aspire A315-33              | [a35ed6ad38](https://linux-hardware.org/?probe=a35ed6ad38) | Aug 15, 2021 |
| Acer          | Nitro AN515-44              | [d7303a008e](https://linux-hardware.org/?probe=d7303a008e) | Aug 15, 2021 |
| Acer          | Nitro AN515-44              | [c30f044292](https://linux-hardware.org/?probe=c30f044292) | Aug 15, 2021 |
| Acer          | Aspire A515-54G             | [b259e8a5e4](https://linux-hardware.org/?probe=b259e8a5e4) | Aug 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [f9bd04ed57](https://linux-hardware.org/?probe=f9bd04ed57) | Aug 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d2601ba1b4](https://linux-hardware.org/?probe=d2601ba1b4) | Aug 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [92440ecd49](https://linux-hardware.org/?probe=92440ecd49) | Aug 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [c8b1a45676](https://linux-hardware.org/?probe=c8b1a45676) | Aug 13, 2021 |
| Acer          | Aspire A517-51G             | [6387ddee62](https://linux-hardware.org/?probe=6387ddee62) | Aug 13, 2021 |
| Acer          | Nitro AN515-44              | [be5e662b8b](https://linux-hardware.org/?probe=be5e662b8b) | Aug 12, 2021 |
| Acer          | Nitro AN515-54              | [59cbec874f](https://linux-hardware.org/?probe=59cbec874f) | Aug 12, 2021 |
| Acer          | Nitro AN515-54              | [278d8c1623](https://linux-hardware.org/?probe=278d8c1623) | Aug 12, 2021 |
| Acer          | Nitro AN515-54              | [80e53d2ec8](https://linux-hardware.org/?probe=80e53d2ec8) | Aug 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [20a828b938](https://linux-hardware.org/?probe=20a828b938) | Aug 11, 2021 |
| Positivo B... | VJFE41F11X                  | [4b6dfe8371](https://linux-hardware.org/?probe=4b6dfe8371) | Aug 11, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [f4a04901f8](https://linux-hardware.org/?probe=f4a04901f8) | Aug 10, 2021 |
| Sony          | VPCCB35FG                   | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1f76a0939f](https://linux-hardware.org/?probe=1f76a0939f) | Aug 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ca859cbf25](https://linux-hardware.org/?probe=ca859cbf25) | Aug 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bc88ed9f71](https://linux-hardware.org/?probe=bc88ed9f71) | Aug 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8e20b8e1ff](https://linux-hardware.org/?probe=8e20b8e1ff) | Aug 06, 2021 |
| Acer          | Aspire A515-54              | [a1d988707a](https://linux-hardware.org/?probe=a1d988707a) | Aug 04, 2021 |
| Acer          | Aspire A515-54              | [f1c771a10e](https://linux-hardware.org/?probe=f1c771a10e) | Aug 04, 2021 |
| Acer          | Aspire A315-54K             | [9c4ca39872](https://linux-hardware.org/?probe=9c4ca39872) | Aug 03, 2021 |
| Samsung       | 800G5M/800G5W               | [72323e95ac](https://linux-hardware.org/?probe=72323e95ac) | Aug 01, 2021 |
| Acer          | Nitro AN515-43              | [a84b8b8484](https://linux-hardware.org/?probe=a84b8b8484) | Aug 01, 2021 |
| Acer          | Aspire A315-54K             | [494562b622](https://linux-hardware.org/?probe=494562b622) | Aug 01, 2021 |
| HP            | 15                          | [715128c8f0](https://linux-hardware.org/?probe=715128c8f0) | Jul 31, 2021 |
| Acer          | Nitro AN515-54              | [f70d19b81f](https://linux-hardware.org/?probe=f70d19b81f) | Jul 30, 2021 |
| Acer          | Nitro AN515-54              | [1978fa6aeb](https://linux-hardware.org/?probe=1978fa6aeb) | Jul 30, 2021 |
| Acer          | Nitro AN515-54              | [bd29363ad5](https://linux-hardware.org/?probe=bd29363ad5) | Jul 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [77529337bc](https://linux-hardware.org/?probe=77529337bc) | Jul 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [8279602440](https://linux-hardware.org/?probe=8279602440) | Jul 29, 2021 |
| Positivo      | H14BT58                     | [4bd1d4c963](https://linux-hardware.org/?probe=4bd1d4c963) | Jul 28, 2021 |
| Acer          | Aspire A315-21G             | [f6f7c5c935](https://linux-hardware.org/?probe=f6f7c5c935) | Jul 27, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a135d4a9cc](https://linux-hardware.org/?probe=a135d4a9cc) | Jul 25, 2021 |
| Dell          | Inspiron 1420               | [1dae73900e](https://linux-hardware.org/?probe=1dae73900e) | Jul 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f281a6eac9](https://linux-hardware.org/?probe=f281a6eac9) | Jul 23, 2021 |
| Acer          | Aspire A315-34              | [69ef9cdbb5](https://linux-hardware.org/?probe=69ef9cdbb5) | Jul 23, 2021 |
| Acer          | Aspire A315-34              | [8f2809e187](https://linux-hardware.org/?probe=8f2809e187) | Jul 22, 2021 |
| Toshiba       | Satellite P775              | [bb08c4c4ff](https://linux-hardware.org/?probe=bb08c4c4ff) | Jul 22, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [6679012f73](https://linux-hardware.org/?probe=6679012f73) | Jul 22, 2021 |
| Packard Be... | EasyNote TM98               | [abd6d053df](https://linux-hardware.org/?probe=abd6d053df) | Jul 19, 2021 |
| Acer          | Aspire A315-54K             | [10eac9e8d2](https://linux-hardware.org/?probe=10eac9e8d2) | Jul 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [791281a212](https://linux-hardware.org/?probe=791281a212) | Jul 17, 2021 |
| ASUSTek       | X406UAR                     | [f50ab25a97](https://linux-hardware.org/?probe=f50ab25a97) | Jul 17, 2021 |
| ASUSTek       | X406UAR                     | [594955a00b](https://linux-hardware.org/?probe=594955a00b) | Jul 17, 2021 |
| Acer          | Aspire A315-53              | [734ffe5fc6](https://linux-hardware.org/?probe=734ffe5fc6) | Jul 17, 2021 |
| iRULU         | W1004                       | [61bd6bde50](https://linux-hardware.org/?probe=61bd6bde50) | Jul 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [36b0d241cd](https://linux-hardware.org/?probe=36b0d241cd) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3c938f74fd](https://linux-hardware.org/?probe=3c938f74fd) | Jul 16, 2021 |
| Acer          | Nitro AN515-54              | [c8642b1182](https://linux-hardware.org/?probe=c8642b1182) | Jul 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [876c8173d3](https://linux-hardware.org/?probe=876c8173d3) | Jul 13, 2021 |
| Toshiba       | Satellite P775              | [8d3294334b](https://linux-hardware.org/?probe=8d3294334b) | Jul 13, 2021 |
| ASUSTek       | N53SV                       | [8044015dd8](https://linux-hardware.org/?probe=8044015dd8) | Jul 12, 2021 |
| Toshiba       | Satellite L755              | [14bed35ae4](https://linux-hardware.org/?probe=14bed35ae4) | Jul 11, 2021 |
| Toshiba       | Satellite L755              | [d205c666da](https://linux-hardware.org/?probe=d205c666da) | Jul 11, 2021 |
| ASUSTek       | X441NA                      | [8e90e38d19](https://linux-hardware.org/?probe=8e90e38d19) | Jul 11, 2021 |
| Lenovo        | G460e 1049                  | [444c0fb58d](https://linux-hardware.org/?probe=444c0fb58d) | Jul 11, 2021 |
| Lenovo        | G460e 1049                  | [89b02002a5](https://linux-hardware.org/?probe=89b02002a5) | Jul 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5ba1737f70](https://linux-hardware.org/?probe=5ba1737f70) | Jul 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e3066c8ce2](https://linux-hardware.org/?probe=e3066c8ce2) | Jul 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c9c8fdd393](https://linux-hardware.org/?probe=c9c8fdd393) | Jul 11, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [b61460e3b1](https://linux-hardware.org/?probe=b61460e3b1) | Jul 11, 2021 |
| Lenovo        | ThinkPad X220 4286A35       | [690c11d9b2](https://linux-hardware.org/?probe=690c11d9b2) | Jul 10, 2021 |
| ASUSTek       | E203NA                      | [a4aa015f4e](https://linux-hardware.org/?probe=a4aa015f4e) | Jul 09, 2021 |
| Acer          | Aspire A515-54G             | [e7561debf6](https://linux-hardware.org/?probe=e7561debf6) | Jul 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [cca31087c0](https://linux-hardware.org/?probe=cca31087c0) | Jul 08, 2021 |
| Acer          | Nitro AN517-51              | [20e31ad5b3](https://linux-hardware.org/?probe=20e31ad5b3) | Jul 08, 2021 |
| Acer          | Nitro AN517-51              | [90e68f86cf](https://linux-hardware.org/?probe=90e68f86cf) | Jul 08, 2021 |
| Acer          | Nitro AN515-54              | [4b3c9afde7](https://linux-hardware.org/?probe=4b3c9afde7) | Jul 07, 2021 |
| Standard      | AHV                         | [b2c72bc162](https://linux-hardware.org/?probe=b2c72bc162) | Jul 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8e3d43d0c9](https://linux-hardware.org/?probe=8e3d43d0c9) | Jul 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [307428e41c](https://linux-hardware.org/?probe=307428e41c) | Jul 07, 2021 |
| Lenovo        | IdeaPad Z500 20202          | [62f902e5b2](https://linux-hardware.org/?probe=62f902e5b2) | Jul 06, 2021 |
| Lenovo        | IdeaPad Z500 20202          | [98f068fb9d](https://linux-hardware.org/?probe=98f068fb9d) | Jul 06, 2021 |
| ASUSTek       | X540UA                      | [b9169c0ae3](https://linux-hardware.org/?probe=b9169c0ae3) | Jul 05, 2021 |
| Acer          | Predator PH315-52           | [9768281e5c](https://linux-hardware.org/?probe=9768281e5c) | Jul 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [048d10c013](https://linux-hardware.org/?probe=048d10c013) | Jul 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f2d67e7bde](https://linux-hardware.org/?probe=f2d67e7bde) | Jul 04, 2021 |
| HP            | ProBook 450 G1              | [9b296f3c9c](https://linux-hardware.org/?probe=9b296f3c9c) | Jul 03, 2021 |
| HP            | 15                          | [b435e6f220](https://linux-hardware.org/?probe=b435e6f220) | Jul 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [035585af97](https://linux-hardware.org/?probe=035585af97) | Jul 02, 2021 |
| Positivo      | S14CT01                     | [a2a7c040a8](https://linux-hardware.org/?probe=a2a7c040a8) | Jul 01, 2021 |
| Positivo      | S14CT01                     | [2988ca2bae](https://linux-hardware.org/?probe=2988ca2bae) | Jul 01, 2021 |
| Acer          | Aspire A315-34              | [2e6400b3fb](https://linux-hardware.org/?probe=2e6400b3fb) | Jun 30, 2021 |
| Positivo      | Smash                       | [78aff01d49](https://linux-hardware.org/?probe=78aff01d49) | Jun 30, 2021 |
| Acer          | Predator PH315-52           | [fbe99870e9](https://linux-hardware.org/?probe=fbe99870e9) | Jun 29, 2021 |
| Dell          | Inspiron N5110              | [b24be80abf](https://linux-hardware.org/?probe=b24be80abf) | Jun 29, 2021 |
| Acer          | Aspire E5-473               | [4ee1cfe01b](https://linux-hardware.org/?probe=4ee1cfe01b) | Jun 28, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4a3a417531](https://linux-hardware.org/?probe=4a3a417531) | Jun 28, 2021 |
| Acer          | Nitro AN515-54              | [42e31b505d](https://linux-hardware.org/?probe=42e31b505d) | Jun 28, 2021 |
| Dell          | Vostro 1000                 | [9230a6f1a1](https://linux-hardware.org/?probe=9230a6f1a1) | Jun 28, 2021 |
| Acer          | Nitro AN515-54              | [db60dbc891](https://linux-hardware.org/?probe=db60dbc891) | Jun 27, 2021 |
| ASUSTek       | X441NA                      | [c3916da9d8](https://linux-hardware.org/?probe=c3916da9d8) | Jun 26, 2021 |
| Acer          | Aspire A517-51              | [816ec9e355](https://linux-hardware.org/?probe=816ec9e355) | Jun 26, 2021 |
| HP            | ProBook 4730s               | [7e3d750bcf](https://linux-hardware.org/?probe=7e3d750bcf) | Jun 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [383c88772d](https://linux-hardware.org/?probe=383c88772d) | Jun 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5f09d7cbdd](https://linux-hardware.org/?probe=5f09d7cbdd) | Jun 26, 2021 |
| ASUSTek       | X441UA                      | [3574e8459f](https://linux-hardware.org/?probe=3574e8459f) | Jun 25, 2021 |
| Acer          | Nitro AN517-51              | [91a3c1eeed](https://linux-hardware.org/?probe=91a3c1eeed) | Jun 25, 2021 |
| Acer          | Nitro AN515-54              | [2d9860375c](https://linux-hardware.org/?probe=2d9860375c) | Jun 24, 2021 |
| Acer          | Nitro AN515-54              | [9d6c6de501](https://linux-hardware.org/?probe=9d6c6de501) | Jun 24, 2021 |
| Acer          | Nitro AN517-51              | [22656657b7](https://linux-hardware.org/?probe=22656657b7) | Jun 23, 2021 |
| Acer          | Aspire A515-54G             | [a655a71d5e](https://linux-hardware.org/?probe=a655a71d5e) | Jun 23, 2021 |
| Lenovo        | B50-30 80ES                 | [b9d0b5be2d](https://linux-hardware.org/?probe=b9d0b5be2d) | Jun 23, 2021 |
| Acer          | Nitro AN515-54              | [e3cd8efc89](https://linux-hardware.org/?probe=e3cd8efc89) | Jun 23, 2021 |
| Lenovo        | B50-30 80ES                 | [e2b40afe3c](https://linux-hardware.org/?probe=e2b40afe3c) | Jun 23, 2021 |
| Acer          | Aspire A515-54G             | [bda57ce6d5](https://linux-hardware.org/?probe=bda57ce6d5) | Jun 22, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [f19497e31d](https://linux-hardware.org/?probe=f19497e31d) | Jun 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [878096682f](https://linux-hardware.org/?probe=878096682f) | Jun 22, 2021 |
| Positivo      | WCBT1013                    | [58031e1391](https://linux-hardware.org/?probe=58031e1391) | Jun 21, 2021 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [07cc916c5e](https://linux-hardware.org/?probe=07cc916c5e) | Jun 21, 2021 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | [3e980445c3](https://linux-hardware.org/?probe=3e980445c3) | Jun 20, 2021 |
| Dell          | Inspiron 3501               | [0fa2846047](https://linux-hardware.org/?probe=0fa2846047) | Jun 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4be49a109b](https://linux-hardware.org/?probe=4be49a109b) | Jun 18, 2021 |
| Acer          | Extensa 2540                | [5b4619d24c](https://linux-hardware.org/?probe=5b4619d24c) | Jun 18, 2021 |
| Acer          | Nitro AN515-54              | [f6b425c110](https://linux-hardware.org/?probe=f6b425c110) | Jun 18, 2021 |
| ASUSTek       | G551JK                      | [aace05a48f](https://linux-hardware.org/?probe=aace05a48f) | Jun 17, 2021 |
| ASUSTek       | G551JK                      | [2947ae8fc2](https://linux-hardware.org/?probe=2947ae8fc2) | Jun 17, 2021 |
| Acer          | Nitro AN517-51              | [af372ea58f](https://linux-hardware.org/?probe=af372ea58f) | Jun 17, 2021 |
| Acer          | Nitro AN515-54              | [245cf00853](https://linux-hardware.org/?probe=245cf00853) | Jun 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [80b26a6c37](https://linux-hardware.org/?probe=80b26a6c37) | Jun 16, 2021 |
| Acer          | Aspire A315-53              | [e4943aaa7f](https://linux-hardware.org/?probe=e4943aaa7f) | Jun 16, 2021 |
| Acer          | Aspire A315-53              | [9ea373a7f8](https://linux-hardware.org/?probe=9ea373a7f8) | Jun 16, 2021 |
| Acer          | Nitro AN515-54              | [943e70a605](https://linux-hardware.org/?probe=943e70a605) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1TP0... | [ced1770bb4](https://linux-hardware.org/?probe=ced1770bb4) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | [1ba4841746](https://linux-hardware.org/?probe=1ba4841746) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1TP0... | [779877342f](https://linux-hardware.org/?probe=779877342f) | Jun 15, 2021 |
| Intel         | W7650                       | [05cc2213db](https://linux-hardware.org/?probe=05cc2213db) | Jun 15, 2021 |
| Acer          | Nitro AN515-54              | [d0a7fa08b3](https://linux-hardware.org/?probe=d0a7fa08b3) | Jun 13, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [ef3ce7621e](https://linux-hardware.org/?probe=ef3ce7621e) | Jun 13, 2021 |
| HP            | Presario CQ56               | [8475580183](https://linux-hardware.org/?probe=8475580183) | Jun 12, 2021 |
| ASUSTek       | K73SV                       | [228feaed8e](https://linux-hardware.org/?probe=228feaed8e) | Jun 12, 2021 |
| Acer          | Nitro AN517-51              | [6a1ada92f8](https://linux-hardware.org/?probe=6a1ada92f8) | Jun 12, 2021 |
| Acer          | Nitro AN517-51              | [2ecd9ea4b7](https://linux-hardware.org/?probe=2ecd9ea4b7) | Jun 12, 2021 |
| HP            | 255 G8 Notebook PC          | [a671b3aae7](https://linux-hardware.org/?probe=a671b3aae7) | Jun 11, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [82aa15746c](https://linux-hardware.org/?probe=82aa15746c) | Jun 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5f45108c0b](https://linux-hardware.org/?probe=5f45108c0b) | Jun 11, 2021 |
| ASUSTek       | 1015PE                      | [d1ee176a23](https://linux-hardware.org/?probe=d1ee176a23) | Jun 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [18fd922adc](https://linux-hardware.org/?probe=18fd922adc) | Jun 10, 2021 |
| Acer          | Aspire A315-54K             | [755664a6d6](https://linux-hardware.org/?probe=755664a6d6) | Jun 10, 2021 |
| Acer          | Nitro AN517-51              | [5cb8ba3d0d](https://linux-hardware.org/?probe=5cb8ba3d0d) | Jun 10, 2021 |
| Acer          | Nitro AN515-54              | [8c6e41fe04](https://linux-hardware.org/?probe=8c6e41fe04) | Jun 09, 2021 |
| Acer          | Nitro AN517-51              | [907bcbc57d](https://linux-hardware.org/?probe=907bcbc57d) | Jun 08, 2021 |
| Toshiba       | Satellite L750              | [e0c6618369](https://linux-hardware.org/?probe=e0c6618369) | Jun 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d8c1e89dd9](https://linux-hardware.org/?probe=d8c1e89dd9) | Jun 07, 2021 |
| Acer          | Aspire A315-34              | [da0e968ed6](https://linux-hardware.org/?probe=da0e968ed6) | Jun 07, 2021 |
| Acer          | Aspire A315-53              | [c54e5ca421](https://linux-hardware.org/?probe=c54e5ca421) | Jun 07, 2021 |
| Acer          | Nitro AN517-51              | [d087cc40ee](https://linux-hardware.org/?probe=d087cc40ee) | Jun 07, 2021 |
| Acer          | Extensa 2540                | [fd8ee74d2b](https://linux-hardware.org/?probe=fd8ee74d2b) | Jun 06, 2021 |
| LG Electro... | N450-P.BE55P1               | [0151392f82](https://linux-hardware.org/?probe=0151392f82) | Jun 05, 2021 |
| LG Electro... | N450-P.BE55P1               | [5665115bf7](https://linux-hardware.org/?probe=5665115bf7) | Jun 05, 2021 |
| HP            | Pavilion dv6                | [a22da50b18](https://linux-hardware.org/?probe=a22da50b18) | Jun 05, 2021 |
| Acer          | Nitro AN515-54              | [a55e132655](https://linux-hardware.org/?probe=a55e132655) | Jun 05, 2021 |
| Acer          | Swift SF314-51              | [9d864598e3](https://linux-hardware.org/?probe=9d864598e3) | Jun 04, 2021 |
| Acer          | Nitro AN517-51              | [c825606f49](https://linux-hardware.org/?probe=c825606f49) | Jun 02, 2021 |
| Acer          | Nitro AN517-51              | [895977603b](https://linux-hardware.org/?probe=895977603b) | Jun 01, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d816dafe7](https://linux-hardware.org/?probe=7d816dafe7) | Jun 01, 2021 |
| Acer          | Aspire A315-56              | [883283c763](https://linux-hardware.org/?probe=883283c763) | May 31, 2021 |
| Positivo      | CHT14B                      | [1b5e908cff](https://linux-hardware.org/?probe=1b5e908cff) | May 31, 2021 |
| Acer          | Aspire A315-34              | [c4fa352d95](https://linux-hardware.org/?probe=c4fa352d95) | May 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [6aff8771b1](https://linux-hardware.org/?probe=6aff8771b1) | May 30, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [570905286f](https://linux-hardware.org/?probe=570905286f) | May 29, 2021 |
| Acer          | Aspire A315-56              | [313b51bb15](https://linux-hardware.org/?probe=313b51bb15) | May 28, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Endless/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Endless 3.7.8          | 257       | 8.31%   |
| Endless 3.9.5          | 146       | 4.72%   |
| Endless 3.9.1          | 125       | 4.04%   |
| Endless 3.8.7          | 113       | 3.65%   |
| Endless 3.8.6          | 111       | 3.59%   |
| Endless 3.8.0          | 111       | 3.59%   |
| Endless 3.8.4          | 106       | 3.43%   |
| Endless 3.9.4          | 105       | 3.39%   |
| Endless 3.9.3          | 104       | 3.36%   |
| Endless 3.8.3          | 82        | 2.65%   |
| Endless 3.9.0          | 81        | 2.62%   |
| Endless 3.5.8          | 66        | 2.13%   |
| Endless 3.7.4          | 65        | 2.1%    |
| Endless 3.7.5          | 64        | 2.07%   |
| Endless 3.8.1          | 62        | 2%      |
| Endless 3.8.5          | 61        | 1.97%   |
| Endless 3.7.6          | 59        | 1.91%   |
| Endless 3.7.7          | 57        | 1.84%   |
| Endless 4.0.2          | 56        | 1.81%   |
| Endless 3.3.19         | 53        | 1.71%   |
| Endless 3.9.2          | 51        | 1.65%   |
| Endless 3.6.2          | 47        | 1.52%   |
| Endless 3.9.7          | 46        | 1.49%   |
| Endless 3.6.4          | 46        | 1.49%   |
| Endless 3.3.19-nexthw1 | 44        | 1.42%   |
| Endless 3.5.7          | 43        | 1.39%   |
| Endless 3.7.3          | 40        | 1.29%   |
| Endless 4.0.13         | 39        | 1.26%   |
| Endless 3.6.1          | 39        | 1.26%   |
| Endless 3.6.0          | 38        | 1.23%   |
| Endless 4.0.6          | 34        | 1.1%    |
| Endless 3.6.3          | 34        | 1.1%    |
| Endless 3.3.20-nexthw1 | 32        | 1.03%   |
| Endless 3.5.4          | 31        | 1%      |
| Endless 3.4.2-nexthw1  | 31        | 1%      |
| Endless 4.0.0          | 28        | 0.9%    |
| Endless 3.5.3          | 28        | 0.9%    |
| Endless 3.9.6          | 27        | 0.87%   |
| Endless 4.0.3          | 24        | 0.78%   |
| Endless 3.5.6          | 24        | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Endless | 2634      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.8.0-14-generic  | 623       | 21.17%  |
| 5.4.0-19-generic  | 342       | 11.62%  |
| 5.3.0-28-generic  | 309       | 10.5%   |
| 5.11.0-35-generic | 274       | 9.31%   |
| 5.4.0-42-generic  | 220       | 7.48%   |
| 5.3.0-23-generic  | 126       | 4.28%   |
| 4.18.0-15-generic | 124       | 4.21%   |
| 4.15.0-15-generic | 81        | 2.75%   |
| 4.13.0-32-generic | 79        | 2.68%   |
| 5.0.0-25-generic  | 78        | 2.65%   |
| 5.3.0-19-generic  | 65        | 2.21%   |
| 5.4.0-39-generic  | 61        | 2.07%   |
| 4.18.0-12-generic | 58        | 1.97%   |
| 5.3.0-12-generic  | 54        | 1.83%   |
| 5.15.0-47-generic | 49        | 1.66%   |
| 4.16.0-4-generic  | 48        | 1.63%   |
| 5.0.0-20-generic  | 47        | 1.6%    |
| 4.18.0-10-generic | 40        | 1.36%   |
| 5.0.0-17-generic  | 39        | 1.33%   |
| 5.0.0-15-generic  | 38        | 1.29%   |
| 4.18.0-11-generic | 36        | 1.22%   |
| 4.15.0-34-generic | 24        | 0.82%   |
| 5.11.0-12-generic | 23        | 0.78%   |
| 5.1.0-2-generic   | 20        | 0.68%   |
| 4.15.0-12-generic | 18        | 0.61%   |
| 5.4.0-7-generic   | 11        | 0.37%   |
| 5.0.0-7-generic   | 9         | 0.31%   |
| 5.6.0-7-generic   | 8         | 0.27%   |
| 4.18.0-7-generic  | 8         | 0.27%   |
| 4.17.0-4-generic  | 8         | 0.27%   |
| 4.15.0-23-generic | 6         | 0.2%    |
| 5.10.0-10-generic | 5         | 0.17%   |
| 4.13.0-19-generic | 4         | 0.14%   |
| 5.0.0-8-generic   | 2         | 0.07%   |
| 4.15.0-22-generic | 2         | 0.07%   |
| 6.1.0-14-generic  | 1         | 0.03%   |
| 4.15.0-33-generic | 1         | 0.03%   |
| 4.14.0-16-generic | 1         | 0.03%   |
| Unknown           | 1         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.8.0   | 623       | 21.73%  |
| 5.4.0   | 602       | 21%     |
| 5.3.0   | 536       | 18.7%   |
| 5.11.0  | 297       | 10.36%  |
| 4.18.0  | 248       | 8.65%   |
| 5.0.0   | 205       | 7.15%   |
| 4.15.0  | 132       | 4.6%    |
| 4.13.0  | 83        | 2.9%    |
| 5.15.0  | 49        | 1.71%   |
| 4.16.0  | 48        | 1.67%   |
| 5.1.0   | 20        | 0.7%    |
| 5.6.0   | 8         | 0.28%   |
| 4.17.0  | 8         | 0.28%   |
| 5.10.0  | 5         | 0.17%   |
| 6.1.0   | 1         | 0.03%   |
| 4.14.0  | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.8     | 623       | 21.73%  |
| 5.4     | 602       | 21%     |
| 5.3     | 536       | 18.7%   |
| 5.11    | 297       | 10.36%  |
| 4.18    | 248       | 8.65%   |
| 5.0     | 205       | 7.15%   |
| 4.15    | 132       | 4.6%    |
| 4.13    | 83        | 2.9%    |
| 5.15    | 49        | 1.71%   |
| 4.16    | 48        | 1.67%   |
| 5.1     | 20        | 0.7%    |
| 5.6     | 8         | 0.28%   |
| 4.17    | 8         | 0.28%   |
| 5.10    | 5         | 0.17%   |
| 6.1     | 1         | 0.03%   |
| 4.14    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2634      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 2112      | 78.86%  |
| Unknown | 566       | 21.14%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2072      | 77.05%  |
| Unknown | 567       | 21.09%  |
| Wayland | 50        | 1.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2634      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| pt_BR       | 791       | 29.42%  |
| Unknown     | 569       | 21.16%  |
| en_US       | 484       | 18%     |
| ru_RU       | 143       | 5.32%   |
| ro_RO       | 77        | 2.86%   |
| es_ES       | 67        | 2.49%   |
| de_DE       | 61        | 2.27%   |
| hu_HU       | 52        | 1.93%   |
| fr_FR       | 42        | 1.56%   |
| es_MX       | 39        | 1.45%   |
| ru_RU.UTF_8 | 35        | 1.3%    |
| ru_UA       | 34        | 1.26%   |
| it_IT       | 33        | 1.23%   |
| es_CO       | 30        | 1.12%   |
| en_GB       | 25        | 0.93%   |
| es_AR       | 22        | 0.82%   |
| tr_TR       | 16        | 0.6%    |
| pt_PT       | 16        | 0.6%    |
| uk_UA       | 15        | 0.56%   |
| pl_PL       | 14        | 0.52%   |
| bg_BG       | 11        | 0.41%   |
| sr_RS@latin | 10        | 0.37%   |
| hr_HR       | 7         | 0.26%   |
| el_GR       | 7         | 0.26%   |
| de_AT       | 6         | 0.22%   |
| nl_NL       | 5         | 0.19%   |
| id_ID       | 5         | 0.19%   |
| cs_CZ       | 5         | 0.19%   |
| sl_SI       | 4         | 0.15%   |
| en_IN       | 4         | 0.15%   |
| ca_ES       | 4         | 0.15%   |
| vi_VN       | 3         | 0.11%   |
| sv_SE       | 3         | 0.11%   |
| sk_SK       | 3         | 0.11%   |
| nl_BE       | 3         | 0.11%   |
| es_CL       | 3         | 0.11%   |
| en_CA       | 3         | 0.11%   |
| zh_TW       | 2         | 0.07%   |
| nds_DE      | 2         | 0.07%   |
| lt_LT       | 2         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1897      | 70.18%  |
| BIOS | 806       | 29.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2013      | 75.2%   |
| Unknown | 603       | 22.53%  |
| Tmpfs   | 60        | 2.24%   |
| Overlay | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2628      | 99.73%  |
| GPT     | 7         | 0.27%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2633      | 99.96%  |
| Yes       | 1         | 0.04%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2631      | 99.89%  |
| Yes       | 3         | 0.11%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| ASUSTek Computer      | 1002      | 38.04%  |
| Acer                  | 862       | 32.73%  |
| Hewlett-Packard       | 181       | 6.87%   |
| Lenovo                | 159       | 6.04%   |
| Dell                  | 128       | 4.86%   |
| Toshiba               | 52        | 1.97%   |
| Positivo              | 48        | 1.82%   |
| Samsung Electronics   | 31        | 1.18%   |
| Sony                  | 21        | 0.8%    |
| Apple                 | 11        | 0.42%   |
| Packard Bell          | 10        | 0.38%   |
| Intel                 | 9         | 0.34%   |
| LG Electronics        | 8         | 0.3%    |
| Digibras              | 8         | 0.3%    |
| Itautec               | 7         | 0.27%   |
| MSI                   | 5         | 0.19%   |
| Google                | 5         | 0.19%   |
| Fujitsu Siemens       | 5         | 0.19%   |
| Semp Toshiba          | 4         | 0.15%   |
| Philco                | 4         | 0.15%   |
| Medion                | 4         | 0.15%   |
| Gateway               | 4         | 0.15%   |
| eMachines             | 4         | 0.15%   |
| Chuwi                 | 4         | 0.15%   |
| Unknown               | 4         | 0.15%   |
| Notebook              | 3         | 0.11%   |
| AMI                   | 3         | 0.11%   |
| OEM                   | 2         | 0.08%   |
| Multilaser            | 2         | 0.08%   |
| MODECOM               | 2         | 0.08%   |
| HUAWEI                | 2         | 0.08%   |
| Fujitsu               | 2         | 0.08%   |
| Compal                | 2         | 0.08%   |
| Clevo                 | 2         | 0.08%   |
| VTEX                  | 1         | 0.04%   |
| TPVAOC                | 1         | 0.04%   |
| Standard              | 1         | 0.04%   |
| Positivo Bahia - VAIO | 1         | 0.04%   |
| Phoenix/SiS           | 1         | 0.04%   |
| Pegatron              | 1         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer Nitro AN515-54                        | 124       | 4.71%   |
| Acer Nitro AN515-44                        | 74        | 2.81%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 61        | 2.32%   |
| Acer Aspire A315-53                        | 55        | 2.09%   |
| Acer Nitro AN517-51                        | 49        | 1.86%   |
| Acer Aspire A315-34                        | 49        | 1.86%   |
| ASUS X541NA                                | 43        | 1.63%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 43        | 1.63%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 41        | 1.56%   |
| Acer Nitro AN515-43                        | 40        | 1.52%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 35        | 1.33%   |
| Acer Nitro AN515-52                        | 28        | 1.06%   |
| ASUS ZenBook UX431DA_UM431DA               | 26        | 0.99%   |
| ASUS X540NA                                | 26        | 0.99%   |
| Acer Aspire A315-21                        | 22        | 0.84%   |
| ASUS VivoBook_ASUSLaptop X515JA_X515JA     | 21        | 0.8%    |
| ASUS VivoBook_ASUSLaptop X515DA_X515DA     | 20        | 0.76%   |
| Acer Aspire A315-51                        | 20        | 0.76%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR       | 19        | 0.72%   |
| Acer Aspire A515-54G                       | 19        | 0.72%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA     | 18        | 0.68%   |
| Acer Aspire A515-51G                       | 17        | 0.65%   |
| Acer Aspire A315-31                        | 17        | 0.65%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 16        | 0.61%   |
| ASUS X541UAK                               | 15        | 0.57%   |
| Acer Aspire A315-54                        | 15        | 0.57%   |
| HP Notebook                                | 14        | 0.53%   |
| ASUS VivoBook_ASUSLaptop X570ZD_X570ZD     | 14        | 0.53%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA    | 14        | 0.53%   |
| Acer Aspire A315-54K                       | 14        | 0.53%   |
| Positivo S14CT01                           | 13        | 0.49%   |
| Acer Aspire A517-51G                       | 13        | 0.49%   |
| Acer Aspire A515-51                        | 13        | 0.49%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA     | 12        | 0.46%   |
| ASUS VivoBook 15_ASUS Laptop X507MA_X507MA | 12        | 0.46%   |
| Unknown                                    | 12        | 0.46%   |
| Acer Nitro AN515-51                        | 11        | 0.42%   |
| Acer Extensa 2540                          | 11        | 0.42%   |
| Acer Aspire A315-33                        | 11        | 0.42%   |
| Positivo Mobile                            | 10        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| ASUS VivoBook         | 642       | 24.37%  |
| Acer Aspire           | 440       | 16.7%   |
| Acer Nitro            | 332       | 12.6%   |
| Lenovo IdeaPad        | 63        | 2.39%   |
| Dell Inspiron         | 63        | 2.39%   |
| HP Pavilion           | 47        | 1.78%   |
| Toshiba Satellite     | 45        | 1.71%   |
| Dell Latitude         | 45        | 1.71%   |
| Lenovo ThinkPad       | 44        | 1.67%   |
| ASUS X541NA           | 43        | 1.63%   |
| ASUS ZenBook          | 36        | 1.37%   |
| Acer TravelMate       | 27        | 1.03%   |
| ASUS X540NA           | 26        | 0.99%   |
| HP ProBook            | 22        | 0.84%   |
| Acer Swift            | 20        | 0.76%   |
| HP Laptop             | 19        | 0.72%   |
| Acer Extensa          | 17        | 0.65%   |
| Acer Predator         | 16        | 0.61%   |
| ASUS X541UAK          | 15        | 0.57%   |
| HP Notebook           | 14        | 0.53%   |
| HP EliteBook          | 14        | 0.53%   |
| Positivo S14CT01      | 13        | 0.49%   |
| Dell Vostro           | 13        | 0.49%   |
| Unknown               | 12        | 0.46%   |
| Positivo Mobile       | 10        | 0.38%   |
| Packard Bell EasyNote | 10        | 0.38%   |
| ASUS X540LA           | 10        | 0.38%   |
| ASUS ASUSPRO          | 10        | 0.38%   |
| ASUS ASUS             | 9         | 0.34%   |
| HP Compaq             | 8         | 0.3%    |
| Itautec Infoway       | 7         | 0.27%   |
| HP 255                | 7         | 0.27%   |
| HP 2000               | 7         | 0.27%   |
| ASUS Z550SA           | 7         | 0.27%   |
| ASUS X542UN           | 7         | 0.27%   |
| ASUS X540NV           | 7         | 0.27%   |
| HP 250                | 6         | 0.23%   |
| Digibras NH4CU53      | 6         | 0.23%   |
| ASUS TUF              | 6         | 0.23%   |
| ASUS GL753VD          | 6         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 578       | 21.94%  |
| 2018    | 527       | 20.01%  |
| 2017    | 376       | 14.27%  |
| 2020    | 185       | 7.02%   |
| 2016    | 138       | 5.24%   |
| 2011    | 123       | 4.67%   |
| 2013    | 98        | 3.72%   |
| 2012    | 94        | 3.57%   |
| 2015    | 92        | 3.49%   |
| 2010    | 89        | 3.38%   |
| 2021    | 82        | 3.11%   |
| 2014    | 75        | 2.85%   |
| 2008    | 74        | 2.81%   |
| 2009    | 63        | 2.39%   |
| 2007    | 28        | 1.06%   |
| 2022    | 6         | 0.23%   |
| 2006    | 4         | 0.15%   |
| 2004    | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2634      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1892      | 71.1%   |
| Enabled  | 769       | 28.9%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2629      | 99.81%  |
| Yes  | 5         | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 1107      | 41.84%  |
| 4.01-8.0    | 1014      | 38.32%  |
| 8.01-16.0   | 197       | 7.45%   |
| 1.01-2.0    | 177       | 6.69%   |
| 16.01-24.0  | 101       | 3.82%   |
| 2.01-3.0    | 31        | 1.17%   |
| 0.51-1.0    | 8         | 0.3%    |
| 24.01-32.0  | 6         | 0.23%   |
| 32.01-64.0  | 3         | 0.11%   |
| 64.01-256.0 | 1         | 0.04%   |
| Unknown     | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 1476      | 50.39%  |
| 2.01-3.0  | 698       | 23.83%  |
| 0.51-1.0  | 430       | 14.68%  |
| 3.01-4.0  | 208       | 7.1%    |
| 4.01-8.0  | 111       | 3.79%   |
| 8.01-16.0 | 3         | 0.1%    |
| 0.01-0.5  | 2         | 0.07%   |
| Unknown   | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2108      | 79.07%  |
| 2      | 534       | 20.03%  |
| 3      | 18        | 0.68%   |
| 0      | 6         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1867      | 70.72%  |
| Yes       | 773       | 29.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1845      | 69.81%  |
| No        | 798       | 30.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2572      | 97.57%  |
| No        | 64        | 2.43%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2202      | 83.09%  |
| No        | 448       | 16.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| Brazil          | 880       | 33.25%  |
| Russia          | 215       | 8.12%   |
| Romania         | 210       | 7.93%   |
| USA             | 163       | 6.16%   |
| Germany         | 105       | 3.97%   |
| Spain           | 100       | 3.78%   |
| Ukraine         | 98        | 3.7%    |
| Hungary         | 73        | 2.76%   |
| Colombia        | 64        | 2.42%   |
| France          | 43        | 1.62%   |
| Italy           | 38        | 1.44%   |
| India           | 36        | 1.36%   |
| Belarus         | 36        | 1.36%   |
| Argentina       | 34        | 1.28%   |
| Portugal        | 32        | 1.21%   |
| Serbia          | 31        | 1.17%   |
| UK              | 28        | 1.06%   |
| Bulgaria        | 24        | 0.91%   |
| Poland          | 23        | 0.87%   |
| Croatia         | 22        | 0.83%   |
| Indonesia       | 20        | 0.76%   |
| Turkey          | 18        | 0.68%   |
| Kazakhstan      | 18        | 0.68%   |
| Canada          | 17        | 0.64%   |
| Philippines     | 15        | 0.57%   |
| Iran            | 14        | 0.53%   |
| Greece          | 14        | 0.53%   |
| Saudi Arabia    | 13        | 0.49%   |
| Georgia         | 13        | 0.49%   |
| Mexico          | 12        | 0.45%   |
| Australia       | 12        | 0.45%   |
| Sweden          | 9         | 0.34%   |
| Austria         | 9         | 0.34%   |
| Slovenia        | 8         | 0.3%    |
| North Macedonia | 8         | 0.3%    |
| Kenya           | 8         | 0.3%    |
| Egypt           | 8         | 0.3%    |
| Czechia         | 8         | 0.3%    |
| Vietnam         | 7         | 0.26%   |
| South Africa    | 7         | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Sao Paulo        | 110       | 3.87%   |
| Moscow           | 72        | 2.53%   |
| Bucharest        | 70        | 2.46%   |
| Rio de Janeiro   | 49        | 1.72%   |
| Budapest         | 35        | 1.23%   |
| Kyiv             | 33        | 1.16%   |
| Brasília        | 31        | 1.09%   |
| Curitiba         | 25        | 0.88%   |
| Bogotá          | 25        | 0.88%   |
| St Petersburg    | 23        | 0.81%   |
| Belgrade         | 22        | 0.77%   |
| Cluj-Napoca      | 21        | 0.74%   |
| Salvador         | 19        | 0.67%   |
| Belo Horizonte   | 19        | 0.67%   |
| Fortaleza        | 18        | 0.63%   |
| Porto Alegre     | 16        | 0.56%   |
| Minsk            | 14        | 0.49%   |
| Sofia            | 13        | 0.46%   |
| Iasi             | 12        | 0.42%   |
| Recife           | 11        | 0.39%   |
| Niterói         | 11        | 0.39%   |
| Barcelona        | 11        | 0.39%   |
| Santo André     | 10        | 0.35%   |
| Popesti-Leordeni | 10        | 0.35%   |
| Madrid           | 10        | 0.35%   |
| Campinas         | 10        | 0.35%   |
| Warsaw           | 9         | 0.32%   |
| Tehran           | 9         | 0.32%   |
| Paris            | 9         | 0.32%   |
| Osasco           | 9         | 0.32%   |
| Lisbon           | 9         | 0.32%   |
| Jakarta          | 9         | 0.32%   |
| Campo Grande     | 9         | 0.32%   |
| Sao Carlos       | 8         | 0.28%   |
| Ploieşti        | 8         | 0.28%   |
| Medellín        | 8         | 0.28%   |
| Manaus           | 8         | 0.28%   |
| Istanbul         | 8         | 0.28%   |
| Guarulhos        | 8         | 0.28%   |
| Florianópolis   | 8         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 606       | 725    | 19.42%  |
| Seagate                     | 443       | 564    | 14.19%  |
| Toshiba                     | 342       | 427    | 10.96%  |
| Intel                       | 287       | 347    | 9.2%    |
| SanDisk                     | 269       | 315    | 8.62%   |
| Kingston                    | 210       | 274    | 6.73%   |
| Unknown                     | 174       | 217    | 5.58%   |
| Samsung Electronics         | 123       | 153    | 3.94%   |
| SK hynix                    | 109       | 134    | 3.49%   |
| HGST                        | 89        | 112    | 2.85%   |
| A-DATA Technology           | 87        | 98     | 2.79%   |
| ADATA Technology            | 68        | 72     | 2.18%   |
| Micron Technology           | 56        | 81     | 1.79%   |
| Hitachi                     | 55        | 59     | 1.76%   |
| Crucial                     | 22        | 24     | 0.7%    |
| China                       | 16        | 17     | 0.51%   |
| Fujitsu                     | 13        | 13     | 0.42%   |
| Silicon Motion              | 10        | 10     | 0.32%   |
| Phison                      | 9         | 9      | 0.29%   |
| LITEON                      | 9         | 10     | 0.29%   |
| Apple                       | 8         | 8      | 0.26%   |
| OCZ                         | 7         | 7      | 0.22%   |
| Transcend                   | 5         | 7      | 0.16%   |
| Phison Electronics          | 5         | 5      | 0.16%   |
| SPCC                        | 4         | 5      | 0.13%   |
| Netac                       | 4         | 4      | 0.13%   |
| LITEONIT                    | 4         | 5      | 0.13%   |
| Kingston Technology Company | 4         | 5      | 0.13%   |
| Realtek Semiconductor       | 3         | 4      | 0.1%    |
| PNY                         | 3         | 4      | 0.1%    |
| Patriot                     | 3         | 3      | 0.1%    |
| KingFast                    | 3         | 5      | 0.1%    |
| Intenso                     | 3         | 3      | 0.1%    |
| Hewlett-Packard             | 3         | 13     | 0.1%    |
| GOODRAM                     | 3         | 3      | 0.1%    |
| Win Memory                  | 2         | 3      | 0.06%   |
| Verbatim                    | 2         | 2      | 0.06%   |
| Team                        | 2         | 2      | 0.06%   |
| StoreJet                    | 2         | 3      | 0.06%   |
| Lite-On                     | 2         | 2      | 0.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB              | 368       | 11.68%  |
| Seagate ST1000LM035-1RK172 1TB        | 181       | 5.74%   |
| Toshiba MQ01ABF050 500GB              | 132       | 4.19%   |
| Intel NVMe SSD Drive 512GB            | 122       | 3.87%   |
| Toshiba MQ04ABF100 1TB                | 112       | 3.55%   |
| Unknown MMC Card  32GB                | 77        | 2.44%   |
| Intel NVMe SSD Drive 256GB            | 74        | 2.35%   |
| SanDisk NVMe SSD Drive 512GB          | 70        | 2.22%   |
| A-DATA IM2S3338-128GD2 128GB SSD      | 70        | 2.22%   |
| Intel SSDPEKKW256G7 256GB             | 69        | 2.19%   |
| Kingston RBUSC180DS37256GJ 256GB SSD  | 66        | 2.09%   |
| Seagate ST500LT012-1DG142 500GB       | 47        | 1.49%   |
| Unknown MMC Card  64GB                | 35        | 1.11%   |
| ADATA SM2P32A8-256GC1 256GB           | 32        | 1.02%   |
| Seagate ST500LM030-1RK17D 500GB       | 30        | 0.95%   |
| WDC WD5000LPCX-21VHAT0 500GB          | 29        | 0.92%   |
| SanDisk NVMe SSD Drive 256GB          | 29        | 0.92%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD   | 28        | 0.89%   |
| Toshiba MQ01ABD100 1TB                | 27        | 0.86%   |
| SK hynix NVMe SSD Drive 256GB         | 27        | 0.86%   |
| Kingston NVMe SSD Drive 256GB         | 26        | 0.83%   |
| SanDisk SD9SB8W256G1002 256GB SSD     | 25        | 0.79%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 22        | 0.7%    |
| Sandisk WD Blue SN550 NVMe SSD 250GB  | 22        | 0.7%    |
| SK hynix NVMe SSD Drive 512GB         | 21        | 0.67%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 21        | 0.67%   |
| Kingston SA400S37240G 240GB SSD       | 21        | 0.67%   |
| ADATA NVMe SSD Drive 128GB            | 21        | 0.67%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 20        | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 20        | 0.63%   |
| HGST HTS545050B7E660 500GB            | 19        | 0.6%    |
| Unknown MMC Card  16GB                | 17        | 0.54%   |
| Samsung NVMe SSD Drive 256GB          | 17        | 0.54%   |
| HGST HTS541010B7E610 1TB              | 17        | 0.54%   |
| SanDisk SD9SN8W256G1102 256GB SSD     | 16        | 0.51%   |
| WDC WD5000LPCX-80VHAT1 500GB          | 15        | 0.48%   |
| ADATA NVMe SSD Drive 256GB            | 15        | 0.48%   |
| Kingston RBUSNS8180DS3256GJ 256GB SSD | 14        | 0.44%   |
| Seagate ST9500325AS 500GB             | 13        | 0.41%   |
| Seagate ST2000LM007-1R8174 2TB        | 12        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 586       | 693    | 37.35%  |
| Seagate             | 443       | 563    | 28.23%  |
| Toshiba             | 332       | 415    | 21.16%  |
| HGST                | 89        | 112    | 5.67%   |
| Hitachi             | 55        | 59     | 3.51%   |
| Samsung Electronics | 32        | 36     | 2.04%   |
| Fujitsu             | 13        | 13     | 0.83%   |
| Unknown             | 8         | 8      | 0.51%   |
| Intenso             | 3         | 3      | 0.19%   |
| JMicron Technology  | 2         | 2      | 0.13%   |
| Apple               | 2         | 2      | 0.13%   |
| USB3.0              | 1         | 1      | 0.06%   |
| StoreJet            | 1         | 2      | 0.06%   |
| HGST HTS            | 1         | 1      | 0.06%   |
| ASMT                | 1         | 3      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 173       | 231    | 23.6%   |
| SanDisk             | 142       | 183    | 19.37%  |
| A-DATA Technology   | 87        | 98     | 11.87%  |
| Samsung Electronics | 56        | 72     | 7.64%   |
| SK hynix            | 54        | 74     | 7.37%   |
| Micron Technology   | 46        | 71     | 6.28%   |
| Crucial             | 22        | 24     | 3%      |
| WDC                 | 21        | 29     | 2.86%   |
| China               | 16        | 17     | 2.18%   |
| LITEON              | 9         | 10     | 1.23%   |
| Intel               | 9         | 16     | 1.23%   |
| Unknown             | 7         | 8      | 0.95%   |
| Toshiba             | 7         | 7      | 0.95%   |
| OCZ                 | 7         | 7      | 0.95%   |
| Apple               | 6         | 6      | 0.82%   |
| Transcend           | 5         | 7      | 0.68%   |
| SPCC                | 4         | 5      | 0.55%   |
| Netac               | 4         | 4      | 0.55%   |
| LITEONIT            | 4         | 5      | 0.55%   |
| PNY                 | 3         | 4      | 0.41%   |
| Patriot             | 3         | 3      | 0.41%   |
| Hewlett-Packard     | 3         | 13     | 0.41%   |
| GOODRAM             | 3         | 3      | 0.41%   |
| Win Memory          | 2         | 3      | 0.27%   |
| Verbatim            | 2         | 2      | 0.27%   |
| Team                | 2         | 2      | 0.27%   |
| Kingmax             | 2         | 2      | 0.27%   |
| FORESEE             | 2         | 3      | 0.27%   |
| Dell                | 2         | 2      | 0.27%   |
| Corsair             | 2         | 2      | 0.27%   |
| Zheino              | 1         | 1      | 0.14%   |
| XrayDisk            | 1         | 1      | 0.14%   |
| Wellcomm            | 1         | 1      | 0.14%   |
| V7                  | 1         | 1      | 0.14%   |
| Union Memory        | 1         | 1      | 0.14%   |
| TO Exter            | 1         | 3      | 0.14%   |
| Timetec             | 1         | 2      | 0.14%   |
| StoreJet            | 1         | 1      | 0.14%   |
| SPCC Sol            | 1         | 1      | 0.14%   |
| Seagate             | 1         | 1      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1551      | 1913   | 50.32%  |
| SSD     | 711       | 952    | 23.07%  |
| NVMe    | 657       | 746    | 21.32%  |
| MMC     | 150       | 191    | 4.87%   |
| Unknown | 13        | 19     | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2058      | 2839   | 70.87%  |
| NVMe | 657       | 746    | 22.62%  |
| MMC  | 150       | 191    | 5.17%   |
| SAS  | 39        | 45     | 1.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1332      | 1750   | 59.41%  |
| 0.51-1.0   | 881       | 1070   | 39.3%   |
| 1.01-2.0   | 27        | 43     | 1.2%    |
| 4.01-10.0  | 2         | 2      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 787       | 29.28%  |
| 251-500        | 727       | 27.05%  |
| 501-1000       | 659       | 24.52%  |
| 21-50          | 188       | 6.99%   |
| 51-100         | 126       | 4.69%   |
| 1-20           | 111       | 4.13%   |
| 1001-2000      | 56        | 2.08%   |
| 2001-3000      | 22        | 0.82%   |
| Unknown        | 9         | 0.33%   |
| More than 3000 | 3         | 0.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 1437      | 51.36%  |
| 1-20           | 611       | 21.84%  |
| 51-100         | 405       | 14.47%  |
| 101-250        | 204       | 7.29%   |
| 251-500        | 76        | 2.72%   |
| 501-1000       | 34        | 1.22%   |
| 1001-2000      | 17        | 0.61%   |
| Unknown        | 9         | 0.32%   |
| 2001-3000      | 4         | 0.14%   |
| More than 3000 | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZVPW128HEGM-00000 128GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 100%    |

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
| Detected | 2626      | 3810   | 99.62%  |
| Works    | 9         | 10     | 0.34%   |
| Malfunc  | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2047      | 70.05%  |
| AMD                              | 466       | 15.95%  |
| SanDisk                          | 127       | 4.35%   |
| ADATA Technology                 | 76        | 2.6%    |
| SK hynix                         | 55        | 1.88%   |
| Kingston Technology Company      | 41        | 1.4%    |
| Samsung Electronics              | 40        | 1.37%   |
| Phison Electronics               | 14        | 0.48%   |
| Silicon Motion                   | 10        | 0.34%   |
| Silicon Integrated Systems [SiS] | 10        | 0.34%   |
| Micron Technology                | 10        | 0.34%   |
| Nvidia                           | 8         | 0.27%   |
| Toshiba America Info Systems     | 5         | 0.17%   |
| Realtek Semiconductor            | 4         | 0.14%   |
| VIA Technologies                 | 2         | 0.07%   |
| Lite-On Technology               | 2         | 0.07%   |
| KIOXIA                           | 2         | 0.07%   |
| Union Memory (Shenzhen)          | 1         | 0.03%   |
| Marvell Technology Group         | 1         | 0.03%   |
| JMicron Technology               | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 458       | 13.73%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 425       | 12.74%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 417       | 12.5%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 253       | 7.58%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 251       | 7.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 146       | 4.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 111       | 3.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 93        | 2.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 85        | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 76        | 2.28%   |
| Intel Volume Management Device NVMe RAID Controller                              | 57        | 1.71%   |
| Intel Tiger Lake-LP SATA Controller                                              | 54        | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 50        | 1.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 46        | 1.38%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 43        | 1.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 42        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 39        | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 38        | 1.14%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                      | 37        | 1.11%   |
| ADATA A Non-Volatile memory controller                                           | 36        | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 35        | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 33        | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 31        | 0.93%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 27        | 0.81%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 27        | 0.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 27        | 0.81%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 26        | 0.78%   |
| Samsung NVMe SSD Controller 980                                                  | 21        | 0.63%   |
| Intel SSD 660P Series                                                            | 21        | 0.63%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 20        | 0.6%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 19        | 0.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 0.51%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 15        | 0.45%   |
| Phison PS5013 E13 NVMe Controller                                                | 13        | 0.39%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 0.39%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 10        | 0.3%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 10        | 0.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 10        | 0.3%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 9         | 0.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 0.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2092      | 63.45%  |
| NVMe | 658       | 19.96%  |
| RAID | 438       | 13.28%  |
| IDE  | 109       | 3.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2150      | 81.62%  |
| AMD    | 484       | 18.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 134       | 5.09%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 125       | 4.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 89        | 3.38%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 89        | 3.38%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 81        | 3.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 67        | 2.54%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 63        | 2.39%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 60        | 2.28%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 55        | 2.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 55        | 2.09%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 42        | 1.59%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 41        | 1.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 41        | 1.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 38        | 1.44%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 35        | 1.33%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 34        | 1.29%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 32        | 1.21%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 31        | 1.18%   |
| Intel Pentium CPU 4417U @ 2.30GHz             | 29        | 1.1%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 29        | 1.1%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 29        | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 28        | 1.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 27        | 1.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 27        | 1.03%   |
| Intel Celeron N4000C CPU @ 1.10GHz            | 25        | 0.95%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 25        | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 24        | 0.91%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 24        | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 23        | 0.87%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 23        | 0.87%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 22        | 0.84%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 22        | 0.84%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 21        | 0.8%    |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 20        | 0.76%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 19        | 0.72%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 19        | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 17        | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 0.65%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 17        | 0.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 17        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 562       | 21.34%  |
| Intel Celeron                        | 435       | 16.51%  |
| Intel Core i3                        | 422       | 16.02%  |
| Intel Core i7                        | 267       | 10.14%  |
| AMD Ryzen 5                          | 131       | 4.97%   |
| Intel Pentium                        | 122       | 4.63%   |
| AMD Ryzen 7                          | 106       | 4.02%   |
| Other                                | 91        | 3.45%   |
| Intel Core 2 Duo                     | 87        | 3.3%    |
| Intel Atom                           | 83        | 3.15%   |
| Intel Pentium Silver                 | 45        | 1.71%   |
| AMD A6                               | 40        | 1.52%   |
| AMD Ryzen 3                          | 33        | 1.25%   |
| Intel Pentium Dual-Core              | 30        | 1.14%   |
| AMD A4                               | 24        | 0.91%   |
| AMD E                                | 18        | 0.68%   |
| AMD E2                               | 17        | 0.65%   |
| Intel Pentium Dual                   | 13        | 0.49%   |
| AMD E1                               | 12        | 0.46%   |
| AMD A8                               | 10        | 0.38%   |
| Intel Genuine                        | 9         | 0.34%   |
| AMD Athlon                           | 8         | 0.3%    |
| AMD C-70                             | 6         | 0.23%   |
| AMD A12                              | 6         | 0.23%   |
| AMD A10                              | 5         | 0.19%   |
| Intel Core 2                         | 4         | 0.15%   |
| AMD Turion 64 X2 Mobile              | 4         | 0.15%   |
| AMD Mobile Sempron                   | 4         | 0.15%   |
| AMD FX                               | 4         | 0.15%   |
| Intel Celeron Dual-Core              | 3         | 0.11%   |
| AMD V120                             | 3         | 0.11%   |
| Intel Core M                         | 2         | 0.08%   |
| AMD Turion X2 Dual-Core Mobile       | 2         | 0.08%   |
| AMD Turion II Ultra Dual-Core Mobile | 2         | 0.08%   |
| AMD Phenom II                        | 2         | 0.08%   |
| AMD C-50                             | 2         | 0.08%   |
| AMD Athlon II Dual-Core              | 2         | 0.08%   |
| AMD Athlon II                        | 2         | 0.08%   |
| Intel Pentium Gold                   | 1         | 0.04%   |
| Intel Core m3                        | 1         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1501      | 56.99%  |
| 4      | 917       | 34.81%  |
| 6      | 107       | 4.06%   |
| 8      | 60        | 2.28%   |
| 1      | 47        | 1.78%   |
| 10     | 1         | 0.04%   |
| 3      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2634      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1641      | 62.3%   |
| 1      | 993       | 37.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2115      | 78.98%  |
| Unknown        | 563       | 21.02%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 280       | 10.42%  |
| 0x906ea    | 185       | 6.89%   |
| 0x706a1    | 185       | 6.89%   |
| 0x806ea    | 179       | 6.66%   |
| 0x806e9    | 146       | 5.43%   |
| 0x506c9    | 126       | 4.69%   |
| 0x406e3    | 109       | 4.06%   |
| 0x206a7    | 106       | 3.94%   |
| 0x806ec    | 102       | 3.8%    |
| 0x08108109 | 91        | 3.39%   |
| 0x306a9    | 83        | 3.09%   |
| 0x08600103 | 76        | 2.83%   |
| 0x706e5    | 70        | 2.61%   |
| 0x406c4    | 65        | 2.42%   |
| 0x1067a    | 65        | 2.42%   |
| 0x06006705 | 60        | 2.23%   |
| 0x806c1    | 57        | 2.12%   |
| 0x08108102 | 49        | 1.82%   |
| 0x906ed    | 46        | 1.71%   |
| 0x706a8    | 44        | 1.64%   |
| 0x30678    | 43        | 1.6%    |
| 0x906e9    | 42        | 1.56%   |
| 0x40651    | 42        | 1.56%   |
| 0x306d4    | 37        | 1.38%   |
| 0x20655    | 36        | 1.34%   |
| 0x6fd      | 35        | 1.3%    |
| 0x806eb    | 33        | 1.23%   |
| 0x406c3    | 30        | 1.12%   |
| 0x0810100b | 26        | 0.97%   |
| 0x05000119 | 26        | 0.97%   |
| 0x08101007 | 21        | 0.78%   |
| 0x306c3    | 20        | 0.74%   |
| 0x106ca    | 18        | 0.67%   |
| 0x06006704 | 18        | 0.67%   |
| 0x10676    | 14        | 0.52%   |
| 0x07030105 | 13        | 0.48%   |
| 0x20652    | 12        | 0.45%   |
| 0x6fb      | 8         | 0.3%    |
| 0x010000c8 | 8         | 0.3%    |
| 0xa0652    | 7         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 765       | 29.04%  |
| Goldmont plus    | 257       | 9.76%   |
| Silvermont       | 150       | 5.69%   |
| Zen+             | 147       | 5.58%   |
| Goldmont         | 146       | 5.54%   |
| Skylake          | 126       | 4.78%   |
| SandyBridge      | 123       | 4.67%   |
| Penryn           | 102       | 3.87%   |
| Excavator        | 98        | 3.72%   |
| IvyBridge        | 89        | 3.38%   |
| Zen 2            | 81        | 3.08%   |
| IceLake          | 77        | 2.92%   |
| Haswell          | 69        | 2.62%   |
| TigerLake        | 57        | 2.16%   |
| Core             | 57        | 2.16%   |
| Westmere         | 56        | 2.13%   |
| Zen              | 48        | 1.82%   |
| Broadwell        | 40        | 1.52%   |
| Bobcat           | 35        | 1.33%   |
| Bonnell          | 23        | 0.87%   |
| Puma             | 19        | 0.72%   |
| K10              | 15        | 0.57%   |
| K8 Hammer        | 13        | 0.49%   |
| Piledriver       | 9         | 0.34%   |
| Jaguar           | 9         | 0.34%   |
| CometLake        | 8         | 0.3%    |
| Nehalem          | 4         | 0.15%   |
| K8 & K10 hybrid  | 3         | 0.11%   |
| K10 Llano        | 3         | 0.11%   |
| Steamroller      | 2         | 0.08%   |
| Unknown          | 2         | 0.08%   |
| Alderlake Hybrid | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2066      | 60.43%  |
| Nvidia                           | 801       | 23.43%  |
| AMD                              | 540       | 15.79%  |
| Silicon Integrated Systems [SiS] | 10        | 0.29%   |
| VIA Technologies                 | 2         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 229       | 6.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 212       | 6.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 211       | 6.04%   |
| Intel HD Graphics 620                                                                    | 158       | 4.52%   |
| Intel UHD Graphics 620                                                                   | 154       | 4.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 148       | 4.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 116       | 3.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 113       | 3.23%   |
| Intel HD Graphics 500                                                                    | 110       | 3.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 99        | 2.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 89        | 2.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 87        | 2.49%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 86        | 2.46%   |
| AMD Renoir                                                                               | 80        | 2.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 76        | 2.17%   |
| Nvidia TU117M                                                                            | 75        | 2.15%   |
| Nvidia GM108M [GeForce MX110]                                                            | 72        | 2.06%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 72        | 2.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 70        | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 61        | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 51        | 1.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 1.34%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 47        | 1.34%   |
| Nvidia GP108M [GeForce MX150]                                                            | 46        | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 46        | 1.32%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 45        | 1.29%   |
| Intel HD Graphics 630                                                                    | 42        | 1.2%    |
| Nvidia GM108M [GeForce MX130]                                                            | 37        | 1.06%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 36        | 1.03%   |
| Intel HD Graphics 5500                                                                   | 34        | 0.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 32        | 0.92%   |
| Intel HD Graphics 610                                                                    | 32        | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 29        | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 29        | 0.83%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 25        | 0.72%   |
| Nvidia GP108M [GeForce MX250]                                                            | 24        | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 20        | 0.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 0.54%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 18        | 0.52%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 18        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1422      | 53.99%  |
| Intel + Nvidia | 609       | 23.12%  |
| 1 x AMD        | 321       | 12.19%  |
| AMD + Nvidia   | 141       | 5.35%   |
| 1 x Nvidia     | 50        | 1.9%    |
| 2 x AMD        | 44        | 1.67%   |
| Intel + AMD    | 34        | 1.29%   |
| 1 x SiS        | 10        | 0.38%   |
| 1 x VIA        | 2         | 0.08%   |
| Other          | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1981      | 75.07%  |
| Proprietary | 644       | 24.4%   |
| Unknown     | 14        | 0.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1895      | 71.03%  |
| 0.01-0.5   | 291       | 10.91%  |
| 1.01-2.0   | 204       | 7.65%   |
| 3.01-4.0   | 182       | 6.82%   |
| 0.51-1.0   | 96        | 3.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 659       | 25.43%  |
| AU Optronics            | 550       | 21.23%  |
| Chimei Innolux          | 540       | 20.84%  |
| LG Display              | 311       | 12%     |
| Samsung Electronics     | 155       | 5.98%   |
| PANDA                   | 122       | 4.71%   |
| Chi Mei Optoelectronics | 45        | 1.74%   |
| LG Philips              | 25        | 0.96%   |
| InfoVision              | 18        | 0.69%   |
| Goldstar                | 18        | 0.69%   |
| Lenovo                  | 15        | 0.58%   |
| Dell                    | 13        | 0.5%    |
| Apple                   | 11        | 0.42%   |
| Sony                    | 10        | 0.39%   |
| HannStar                | 8         | 0.31%   |
| CPT                     | 7         | 0.27%   |
| Philips                 | 6         | 0.23%   |
| KDC                     | 6         | 0.23%   |
| AOC                     | 6         | 0.23%   |
| Acer                    | 6         | 0.23%   |
| InnoLux Display         | 5         | 0.19%   |
| BenQ                    | 4         | 0.15%   |
| Ancor Communications    | 4         | 0.15%   |
| Vestel Elektronik       | 3         | 0.12%   |
| SLD                     | 3         | 0.12%   |
| Sharp                   | 3         | 0.12%   |
| RTK                     | 3         | 0.12%   |
| Panasonic               | 3         | 0.12%   |
| Hewlett-Packard         | 3         | 0.12%   |
| Toshiba                 | 2         | 0.08%   |
| STA                     | 2         | 0.08%   |
| SKY                     | 2         | 0.08%   |
| MTD                     | 2         | 0.08%   |
| Hitachi                 | 2         | 0.08%   |
| Vizio                   | 1         | 0.04%   |
| Unknown                 | 1         | 0.04%   |
| Seiki                   | 1         | 0.04%   |
| Optoma                  | 1         | 0.04%   |
| OEM                     | 1         | 0.04%   |
| MUL                     | 1         | 0.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 107       | 4.12%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 101       | 3.89%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 88        | 3.39%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 84        | 3.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 75        | 2.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 75        | 2.89%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 66        | 2.54%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 58        | 2.24%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 53        | 2.04%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 49        | 1.89%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 46        | 1.77%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 45        | 1.73%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 44        | 1.7%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 43        | 1.66%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 42        | 1.62%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 41        | 1.58%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 37        | 1.43%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                 | 33        | 1.27%   |
| BOE LCD Monitor BOE0839 1920x1080 382x215mm 17.3-inch                | 32        | 1.23%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 32        | 1.23%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch              | 28        | 1.08%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 27        | 1.04%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                | 26        | 1%      |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch         | 23        | 0.89%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 22        | 0.85%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch              | 21        | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 18        | 0.69%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch         | 17        | 0.66%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 16        | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 15        | 0.58%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch         | 14        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 14        | 0.54%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 14        | 0.54%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 13        | 0.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 12        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 12        | 0.46%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 12        | 0.46%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch              | 11        | 0.42%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 10        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 9         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1239      | 48.34%  |
| 1920x1080 (FHD)    | 1072      | 41.83%  |
| 1280x800 (WXGA)    | 77        | 3%      |
| 1600x900 (HD+)     | 76        | 2.97%   |
| 1440x900 (WXGA+)   | 18        | 0.7%    |
| 3840x2160 (4K)     | 16        | 0.62%   |
| 1024x600           | 11        | 0.43%   |
| 1920x540           | 8         | 0.31%   |
| 1360x768           | 8         | 0.31%   |
| 1280x1024 (SXGA)   | 7         | 0.27%   |
| 3200x1800 (QHD+)   | 5         | 0.2%    |
| 1680x1050 (WSXGA+) | 5         | 0.2%    |
| 1920x1200 (WUXGA)  | 4         | 0.16%   |
| 2560x1440 (QHD)    | 3         | 0.12%   |
| 2560x1080          | 3         | 0.12%   |
| 2160x1440          | 2         | 0.08%   |
| 1280x720 (HD)      | 2         | 0.08%   |
| 1024x768 (XGA)     | 2         | 0.08%   |
| 3456x2160          | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2880x1800          | 1         | 0.04%   |
| 2288x1287          | 1         | 0.04%   |
| 1680x945           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1727      | 66.63%  |
| 13      | 237       | 9.14%   |
| 14      | 210       | 8.1%    |
| 17      | 185       | 7.14%   |
| 11      | 66        | 2.55%   |
| 12      | 22        | 0.85%   |
| 23      | 21        | 0.81%   |
| 21      | 15        | 0.58%   |
| 10      | 14        | 0.54%   |
| 24      | 12        | 0.46%   |
| 84      | 10        | 0.39%   |
| 31      | 9         | 0.35%   |
| 72      | 6         | 0.23%   |
| 54      | 6         | 0.23%   |
| 40      | 6         | 0.23%   |
| 18      | 6         | 0.23%   |
| 27      | 5         | 0.19%   |
| 32      | 4         | 0.15%   |
| 19      | 4         | 0.15%   |
| 52      | 3         | 0.12%   |
| 37      | 3         | 0.12%   |
| 34      | 3         | 0.12%   |
| 22      | 3         | 0.12%   |
| 16      | 3         | 0.12%   |
| Unknown | 3         | 0.12%   |
| 46      | 2         | 0.08%   |
| 65      | 1         | 0.04%   |
| 63      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 33      | 1         | 0.04%   |
| 29      | 1         | 0.04%   |
| 26      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2091      | 80.83%  |
| 351-400     | 209       | 8.08%   |
| 201-300     | 161       | 6.22%   |
| 501-600     | 39        | 1.51%   |
| 401-500     | 26        | 1.01%   |
| 1501-2000   | 16        | 0.62%   |
| 1001-1500   | 15        | 0.58%   |
| 601-700     | 10        | 0.39%   |
| 801-900     | 9         | 0.35%   |
| 701-800     | 8         | 0.31%   |
| Unknown     | 3         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 2376      | 95.12%  |
| 16/10 | 105       | 4.2%    |
| 5/4   | 6         | 0.24%   |
| 3/2   | 5         | 0.2%    |
| 4/3   | 3         | 0.12%   |
| 21/9  | 3         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1726      | 66.62%  |
| 81-90          | 398       | 15.36%  |
| 121-130        | 171       | 6.6%    |
| 51-60          | 66        | 2.55%   |
| 71-80          | 48        | 1.85%   |
| 201-250        | 47        | 1.81%   |
| More than 1000 | 29        | 1.12%   |
| 61-70          | 22        | 0.85%   |
| 351-500        | 18        | 0.69%   |
| 41-50          | 14        | 0.54%   |
| 131-140        | 11        | 0.42%   |
| 501-1000       | 11        | 0.42%   |
| 141-150        | 8         | 0.31%   |
| 151-200        | 7         | 0.27%   |
| 301-350        | 6         | 0.23%   |
| 91-100         | 4         | 0.15%   |
| Unknown        | 3         | 0.12%   |
| 251-300        | 1         | 0.04%   |
| 111-120        | 1         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1225      | 47.41%  |
| 121-160       | 1110      | 42.96%  |
| 51-100        | 184       | 7.12%   |
| 1-50          | 32        | 1.24%   |
| 161-240       | 22        | 0.85%   |
| More than 240 | 8         | 0.31%   |
| Unknown       | 3         | 0.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2476      | 93.22%  |
| 2     | 125       | 4.71%   |
| 0     | 52        | 1.96%   |
| 3     | 3         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1826      | 44.04%  |
| Intel                             | 988       | 23.83%  |
| Qualcomm Atheros                  | 892       | 21.51%  |
| Broadcom                          | 167       | 4.03%   |
| Broadcom Limited                  | 45        | 1.09%   |
| Marvell Technology Group          | 37        | 0.89%   |
| Ralink                            | 26        | 0.63%   |
| Ralink Technology                 | 21        | 0.51%   |
| JMicron Technology                | 17        | 0.41%   |
| TP-Link                           | 12        | 0.29%   |
| MediaTek                          | 11        | 0.27%   |
| Samsung Electronics               | 10        | 0.24%   |
| Xiaomi                            | 9         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.22%   |
| Nvidia                            | 7         | 0.17%   |
| Ericsson Business Mobile Networks | 7         | 0.17%   |
| ASIX Electronics                  | 7         | 0.17%   |
| Huawei Technologies               | 6         | 0.14%   |
| Dell                              | 6         | 0.14%   |
| Qualcomm Atheros Communications   | 5         | 0.12%   |
| NetGear                           | 4         | 0.1%    |
| Hewlett-Packard                   | 4         | 0.1%    |
| D-Link                            | 4         | 0.1%    |
| VIA Technologies                  | 2         | 0.05%   |
| Motorola PCS                      | 2         | 0.05%   |
| ICS Advent                        | 2         | 0.05%   |
| ASUSTek Computer                  | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.02%   |
| U.S. Robotics                     | 1         | 0.02%   |
| Texas Instruments                 | 1         | 0.02%   |
| T & A Mobile Phones               | 1         | 0.02%   |
| Sierra Wireless                   | 1         | 0.02%   |
| OPPO Electronics                  | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.02%   |
| Micro Star International          | 1         | 0.02%   |
| Linksys                           | 1         | 0.02%   |
| LG Electronics                    | 1         | 0.02%   |
| Lenovo                            | 1         | 0.02%   |
| Google                            | 1         | 0.02%   |
| Edimax Technology                 | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1067      | 23.53%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 448       | 9.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 297       | 6.55%   |
| Intel Wi-Fi 6 AX200                                                     | 253       | 5.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 228       | 5.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 160       | 3.53%   |
| Intel Wireless 8265 / 8275                                              | 153       | 3.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 106       | 2.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 86        | 1.9%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 77        | 1.7%    |
| Intel Wireless 7265                                                     | 72        | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 62        | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 59        | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 55        | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 53        | 1.17%   |
| Intel Wi-Fi 6 AX201                                                     | 50        | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 48        | 1.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 45        | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 41        | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 40        | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 39        | 0.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 38        | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 38        | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 27        | 0.6%    |
| Intel Wireless 7260                                                     | 24        | 0.53%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 20        | 0.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 0.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 19        | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 18        | 0.4%    |
| Intel Wireless 8260                                                     | 18        | 0.4%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 17        | 0.37%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 16        | 0.35%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 15        | 0.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 15        | 0.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.31%   |
| Intel WiFi Link 5100                                                    | 13        | 0.29%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 13        | 0.29%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 13        | 0.29%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 12        | 0.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 0.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 967       | 36.59%  |
| Qualcomm Atheros                      | 835       | 31.59%  |
| Realtek Semiconductor                 | 597       | 22.59%  |
| Broadcom                              | 130       | 4.92%   |
| Ralink                                | 26        | 0.98%   |
| Broadcom Limited                      | 24        | 0.91%   |
| Ralink Technology                     | 21        | 0.79%   |
| MediaTek                              | 9         | 0.34%   |
| TP-Link                               | 7         | 0.26%   |
| Qualcomm Atheros Communications       | 5         | 0.19%   |
| Dell                                  | 4         | 0.15%   |
| NetGear                               | 3         | 0.11%   |
| D-Link                                | 3         | 0.11%   |
| Hewlett-Packard                       | 2         | 0.08%   |
| ASUSTek Computer                      | 2         | 0.08%   |
| U.S. Robotics                         | 1         | 0.04%   |
| Sierra Wireless                       | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| Linksys                               | 1         | 0.04%   |
| Edimax Technology                     | 1         | 0.04%   |
| AirTies Wireless Networks             | 1         | 0.04%   |
| Accton Technology                     | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 448       | 16.9%   |
| Intel Wi-Fi 6 AX200                                                     | 253       | 9.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 228       | 8.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 160       | 6.04%   |
| Intel Wireless 8265 / 8275                                              | 153       | 5.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 106       | 4%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 86        | 3.24%   |
| Intel Wireless 7265                                                     | 72        | 2.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 62        | 2.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 59        | 2.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 55        | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 53        | 2%      |
| Intel Wi-Fi 6 AX201                                                     | 50        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 48        | 1.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 45        | 1.7%    |
| Broadcom BCM43142 802.11b/g/n                                           | 41        | 1.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 40        | 1.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 39        | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 38        | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 27        | 1.02%   |
| Intel Wireless 7260                                                     | 24        | 0.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 20        | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 0.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 19        | 0.72%   |
| Intel Wireless 8260                                                     | 18        | 0.68%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 17        | 0.64%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 16        | 0.6%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 15        | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.53%   |
| Intel WiFi Link 5100                                                    | 13        | 0.49%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 13        | 0.49%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 12        | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 12        | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 0.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 0.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 0.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.41%   |
| Intel Wireless 3165                                                     | 11        | 0.41%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1459      | 78.23%  |
| Intel                            | 117       | 6.27%   |
| Qualcomm Atheros                 | 101       | 5.42%   |
| Broadcom                         | 45        | 2.41%   |
| Marvell Technology Group         | 37        | 1.98%   |
| Broadcom Limited                 | 22        | 1.18%   |
| JMicron Technology               | 17        | 0.91%   |
| Xiaomi                           | 9         | 0.48%   |
| Silicon Integrated Systems [SiS] | 9         | 0.48%   |
| Samsung Electronics              | 7         | 0.38%   |
| Nvidia                           | 7         | 0.38%   |
| ASIX Electronics                 | 7         | 0.38%   |
| TP-Link                          | 5         | 0.27%   |
| Huawei Technologies              | 4         | 0.21%   |
| VIA Technologies                 | 2         | 0.11%   |
| MediaTek                         | 2         | 0.11%   |
| ICS Advent                       | 2         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.05%   |
| T & A Mobile Phones              | 1         | 0.05%   |
| OPPO Electronics                 | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.05%   |
| NetGear                          | 1         | 0.05%   |
| Motorola PCS                     | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Google                           | 1         | 0.05%   |
| Digitech Systems                 | 1         | 0.05%   |
| D-Link                           | 1         | 0.05%   |
| Attansic Technology              | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1067      | 57.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 297       | 15.91%  |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 77        | 4.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38        | 2.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.96%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 15        | 0.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 13        | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 12        | 0.64%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 12        | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 11        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 0.54%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 10        | 0.54%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 9         | 0.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 9         | 0.48%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 8         | 0.43%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 0.43%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 7         | 0.37%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.37%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 7         | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.32%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 6         | 0.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 6         | 0.32%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 5         | 0.27%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 5         | 0.27%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 5         | 0.27%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5         | 0.27%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 5         | 0.27%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 5         | 0.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.21%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 0.21%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2572      | 58.11%  |
| Ethernet | 1837      | 41.5%   |
| Modem    | 17        | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2384      | 89.12%  |
| Ethernet | 291       | 10.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1761      | 66.73%  |
| 1     | 807       | 30.58%  |
| 0     | 68        | 2.58%   |
| 3     | 3         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2372      | 88.81%  |
| Yes  | 299       | 11.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 820       | 37.21%  |
| Lite-On Technology              | 470       | 21.32%  |
| IMC Networks                    | 461       | 20.92%  |
| Realtek Semiconductor           | 158       | 7.17%   |
| Qualcomm Atheros Communications | 88        | 3.99%   |
| Broadcom                        | 59        | 2.68%   |
| Foxconn / Hon Hai               | 26        | 1.18%   |
| Dell                            | 24        | 1.09%   |
| Hewlett-Packard                 | 20        | 0.91%   |
| Cambridge Silicon Radio         | 19        | 0.86%   |
| Toshiba                         | 15        | 0.68%   |
| Apple                           | 12        | 0.54%   |
| Ralink                          | 10        | 0.45%   |
| Foxconn International           | 8         | 0.36%   |
| ASUSTek Computer                | 3         | 0.14%   |
| Alps Electric                   | 3         | 0.14%   |
| Qcom                            | 2         | 0.09%   |
| Smart Modular Technologies      | 1         | 0.05%   |
| Realtek                         | 1         | 0.05%   |
| Ralink Technology               | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 313       | 14.2%   |
| IMC Networks Bluetooth Radio                                                        | 299       | 13.57%  |
| Intel Bluetooth wireless interface                                                  | 285       | 12.93%  |
| Intel AX200 Bluetooth                                                               | 252       | 11.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 177       | 8.03%   |
| IMC Networks Bluetooth Device                                                       | 146       | 6.62%   |
| Lite-On Bluetooth Device                                                            | 124       | 5.63%   |
| Realtek Bluetooth Radio                                                             | 117       | 5.31%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 45        | 2.04%   |
| Intel AX201 Bluetooth                                                               | 42        | 1.91%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 38        | 1.72%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 24        | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 19        | 0.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 19        | 0.86%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 17        | 0.77%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 15        | 0.68%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 0.59%   |
| Ralink RT3290 Bluetooth                                                             | 10        | 0.45%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 10        | 0.45%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 9         | 0.41%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 9         | 0.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 8         | 0.36%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 8         | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 7         | 0.32%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 7         | 0.32%   |
| Realtek RTL8821A Bluetooth                                                          | 6         | 0.27%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 6         | 0.27%   |
| Dell DW375 Bluetooth Module                                                         | 6         | 0.27%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 0.27%   |
| Toshiba BCM43142A0                                                                  | 5         | 0.23%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 0.23%   |
| IMC Networks Wireless_Device                                                        | 5         | 0.23%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.23%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 0.23%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 5         | 0.23%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 0.23%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 5         | 0.23%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 5         | 0.23%   |
| Toshiba Bluetooth Device                                                            | 4         | 0.18%   |
| Lite-On Bluetooth Radio                                                             | 4         | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 2078      | 68.81%  |
| AMD                                             | 505       | 16.72%  |
| Nvidia                                          | 388       | 12.85%  |
| Silicon Integrated Systems [SiS]                | 10        | 0.33%   |
| Generalplus Technology                          | 5         | 0.17%   |
| Logitech                                        | 4         | 0.13%   |
| Plantronics                                     | 3         | 0.1%    |
| JMTek                                           | 3         | 0.1%    |
| C-Media Electronics                             | 3         | 0.1%    |
| VIA Technologies                                | 2         | 0.07%   |
| Texas Instruments                               | 2         | 0.07%   |
| Corsair                                         | 2         | 0.07%   |
| Tdlasunnic                                      | 1         | 0.03%   |
| Sony                                            | 1         | 0.03%   |
| Sennheiser Communications                       | 1         | 0.03%   |
| Samsung Electronics                             | 1         | 0.03%   |
| Realtek Semiconductor                           | 1         | 0.03%   |
| Pioneer DJ                                      | 1         | 0.03%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.03%   |
| Lenovo                                          | 1         | 0.03%   |
| Kingston Technology                             | 1         | 0.03%   |
| Google                                          | 1         | 0.03%   |
| Edifier Technology                              | 1         | 0.03%   |
| EasyPass Industrial                             | 1         | 0.03%   |
| Dell                                            | 1         | 0.03%   |
| Creative Technology                             | 1         | 0.03%   |
| Blue Microphones                                | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 464       | 13.21%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 277       | 7.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 257       | 7.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 250       | 7.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 232       | 6.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 191       | 5.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 146       | 4.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 122       | 3.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 98        | 2.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 98        | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 90        | 2.56%   |
| AMD High Definition Audio Controller                                                              | 86        | 2.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 82        | 2.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 74        | 2.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 64        | 1.82%   |
| AMD FCH Azalia Controller                                                                         | 63        | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 61        | 1.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 60        | 1.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 57        | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 49        | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 47        | 1.34%   |
| Intel 8 Series HD Audio Controller                                                                | 47        | 1.34%   |
| Intel CM238 HD Audio Controller                                                                   | 43        | 1.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 43        | 1.22%   |
| Intel Broadwell-U Audio Controller                                                                | 40        | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 40        | 1.14%   |
| AMD Kabini HDMI/DP Audio                                                                          | 40        | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 39        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 32        | 0.91%   |
| AMD Wrestler HDMI Audio                                                                           | 31        | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 26        | 0.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 22        | 0.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 19        | 0.54%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 0.43%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 11        | 0.31%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 11        | 0.31%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 11        | 0.31%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 10        | 0.28%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 10        | 0.28%   |
| Nvidia High Definition Audio Controller                                                           | 9         | 0.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown (ABCD)      | 2         | 18.18%  |
| Elpida              | 2         | 18.18%  |
| Unknown             | 1         | 9.09%   |
| SK hynix            | 1         | 9.09%   |
| Samsung Electronics | 1         | 9.09%   |
| Patriot             | 1         | 9.09%   |
| Micron Technology   | 1         | 9.09%   |
| Kingston            | 1         | 9.09%   |
| Apacer              | 1         | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 18.18%  |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 9.09%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 9.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 9.09%   |
| Patriot RAM PSD38G1600L2S 8GB SODIMM DDR3 1600MT/s               | 1         | 9.09%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 9.09%   |
| Kingston RAM 99U5428-073.A00G 8GB SODIMM DDR3 1600MT/s           | 1         | 9.09%   |
| Elpida RAM Module 4096MB SODIMM LPDDR3 1600MT/s                  | 1         | 9.09%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 9.09%   |
| Apacer RAM 76.D305G.D390B 16GB SODIMM DDR4 2400MT/s              | 1         | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 4         | 36.36%  |
| DDR3   | 4         | 36.36%  |
| LPDDR4 | 2         | 18.18%  |
| LPDDR3 | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 11        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 5         | 45.45%  |
| 8192  | 4         | 36.36%  |
| 16384 | 2         | 18.18%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 5         | 45.45%  |
| 2400  | 4         | 36.36%  |
| 3266  | 1         | 9.09%   |
| 3200  | 1         | 9.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 27        | 34.18%  |
| Seiko Epson            | 17        | 21.52%  |
| Canon                  | 14        | 17.72%  |
| Brother Industries     | 10        | 12.66%  |
| Samsung Electronics    | 5         | 6.33%   |
| Xerox                  | 2         | 2.53%   |
| Pantum                 | 2         | 2.53%   |
| Ricoh                  | 1         | 1.27%   |
| Panasonic (Matsushita) | 1         | 1.27%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                    | 4         | 5.06%   |
| HP LaserJet 1020                              | 3         | 3.8%    |
| HP LaserJet 1018                              | 3         | 3.8%    |
| Xerox Phaser 3020                             | 2         | 2.53%   |
| Seiko Epson L396 Series                       | 2         | 2.53%   |
| Samsung M2020 Series                          | 2         | 2.53%   |
| HP DeskJet F4200 series                       | 2         | 2.53%   |
| HP DeskJet 2130 series                        | 2         | 2.53%   |
| HP Deskjet 1510                               | 2         | 2.53%   |
| HP Color Laser 150nw                          | 2         | 2.53%   |
| Brother DCP-T310                              | 2         | 2.53%   |
| Seiko Epson ME-100 Series                     | 1         | 1.27%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.27%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]  | 1         | 1.27%   |
| Seiko Epson L380 Series                       | 1         | 1.27%   |
| Seiko Epson L365 Series                       | 1         | 1.27%   |
| Seiko Epson L360 Series                       | 1         | 1.27%   |
| Seiko Epson L355 Series                       | 1         | 1.27%   |
| Seiko Epson L3110 Series                      | 1         | 1.27%   |
| Seiko Epson L210 Series                       | 1         | 1.27%   |
| Seiko Epson L120 Series                       | 1         | 1.27%   |
| Seiko Epson AcuLaser C1700                    | 1         | 1.27%   |
| Samsung M332x 382x 402x Series                | 1         | 1.27%   |
| Samsung M2070 Series                          | 1         | 1.27%   |
| Samsung Composite Device                      | 1         | 1.27%   |
| Ricoh SP 150SUw                               | 1         | 1.27%   |
| Pantum PMF22 series                           | 1         | 1.27%   |
| Pantum M6500W series                          | 1         | 1.27%   |
| Panasonic (Matsushita) KX-MB1500RU            | 1         | 1.27%   |
| HP OfficeJet 4650 series                      | 1         | 1.27%   |
| HP Officejet 4620 series                      | 1         | 1.27%   |
| HP LaserJet Professional P1102w               | 1         | 1.27%   |
| HP LaserJet Pro M148f-M149f                   | 1         | 1.27%   |
| HP Laser 107w                                 | 1         | 1.27%   |
| HP ENVY Pro 6400 series                       | 1         | 1.27%   |
| HP DeskJet F300 series                        | 1         | 1.27%   |
| HP DeskJet 3630 series                        | 1         | 1.27%   |
| HP Deskjet 3050 J610 series                   | 1         | 1.27%   |
| HP DeskJet 2700 series                        | 1         | 1.27%   |
| HP DeskJet 2620 All-in-One Printer            | 1         | 1.27%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Seiko Epson                 | 1         | 50%     |
| Acer Peripherals (now BenQ) | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-F670 [Perfection V200 Photo] | 1         | 50%     |
| Acer Peripherals (now BenQ) Benq 5000       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 799       | 31.74%  |
| Chicony Electronics                    | 604       | 24%     |
| Quanta                                 | 470       | 18.67%  |
| Realtek Semiconductor                  | 102       | 4.05%   |
| Microdia                               | 74        | 2.94%   |
| Suyin                                  | 62        | 2.46%   |
| Sunplus Innovation Technology          | 55        | 2.19%   |
| Bison Electronics                      | 54        | 2.15%   |
| Sonix Technology                       | 40        | 1.59%   |
| Silicon Motion                         | 32        | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) | 30        | 1.19%   |
| Alcor Micro                            | 24        | 0.95%   |
| Syntek                                 | 20        | 0.79%   |
| Samsung Electronics                    | 17        | 0.68%   |
| Acer                                   | 17        | 0.68%   |
| Apple                                  | 15        | 0.6%    |
| Lite-On Technology                     | 14        | 0.56%   |
| Ricoh                                  | 11        | 0.44%   |
| OmniVision Technologies                | 10        | 0.4%    |
| ALi                                    | 10        | 0.4%    |
| Luxvisions Innotech Limited            | 7         | 0.28%   |
| Logitech                               | 7         | 0.28%   |
| Lenovo                                 | 7         | 0.28%   |
| Importek                               | 6         | 0.24%   |
| Z-Star Microelectronics                | 3         | 0.12%   |
| Primax Electronics                     | 3         | 0.12%   |
| Microsoft                              | 3         | 0.12%   |
| GEMBIRD                                | 2         | 0.08%   |
| vivo                                   | 1         | 0.04%   |
| Unknown                                | 1         | 0.04%   |
| Sunplus Technology                     | 1         | 0.04%   |
| Pixart Imaging                         | 1         | 0.04%   |
| Philips (or NXP)                       | 1         | 0.04%   |
| Novatek Microelectronics               | 1         | 0.04%   |
| Nebraska Furniture Mart                | 1         | 0.04%   |
| LG Electronics                         | 1         | 0.04%   |
| JMicron Technology                     | 1         | 0.04%   |
| Intel                                  | 1         | 0.04%   |
| Image Processor                        | 1         | 0.04%   |
| icSpring                               | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                      | 575       | 22.84%  |
| Quanta HD User Facing                                   | 186       | 7.39%   |
| Chicony HD User Facing                                  | 176       | 6.99%   |
| Quanta VGA WebCam                                       | 156       | 6.2%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 140       | 5.56%   |
| Chicony VGA WebCam                                      | 90        | 3.57%   |
| Chicony USB2.0 VGA UVC WebCam                           | 89        | 3.53%   |
| Quanta HD Webcam                                        | 85        | 3.38%   |
| Chicony HD WebCam                                       | 63        | 2.5%    |
| Sonix USB2.0 HD UVC WebCam                              | 37        | 1.47%   |
| IMC Networks VGA UVC WebCam                             | 21        | 0.83%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 17        | 0.68%   |
| Realtek Acer 640 x 480 laptop camera                    | 17        | 0.68%   |
| Chicony USB2.0 HD UVC WebCam                            | 17        | 0.68%   |
| Chicony Integrated Camera                               | 17        | 0.68%   |
| Sunplus HD WebCam                                       | 16        | 0.64%   |
| Quanta USB2.0 HD UVC WebCam                             | 15        | 0.6%    |
| Microdia Integrated_Webcam_HD                           | 14        | 0.56%   |
| Alcor Micro USB 2.0 Camera                              | 14        | 0.56%   |
| Realtek HD WebCam                                       | 13        | 0.52%   |
| IMC Networks Integrated Camera                          | 13        | 0.52%   |
| Realtek USB2.0 HD UVC WebCam                            | 12        | 0.48%   |
| Quanta USB2.0 VGA UVC WebCam                            | 11        | 0.44%   |
| Microdia Integrated Webcam                              | 11        | 0.44%   |
| Bison VGA WebCam                                        | 11        | 0.44%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 11        | 0.44%   |
| Sunplus Integrated_Webcam_HD                            | 10        | 0.4%    |
| OmniVision OV2640 Webcam                                | 10        | 0.4%    |
| Chicony HP Truevision HD                                | 10        | 0.4%    |
| Realtek USB Camera                                      | 9         | 0.36%   |
| Quanta HP Webcam                                        | 9         | 0.36%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 9         | 0.36%   |
| IMC Networks Lenovo EasyCamera                          | 9         | 0.36%   |
| Chicony USB 2.0 Camera                                  | 9         | 0.36%   |
| Chicony TOSHIBA Web Camera - HD                         | 9         | 0.36%   |
| Chicony Lenovo EasyCamera                               | 9         | 0.36%   |
| Chicony HP Truevision HD camera                         | 9         | 0.36%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 9         | 0.36%   |
| ALi Gateway Webcam                                      | 9         | 0.36%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 8         | 0.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 40        | 30.77%  |
| Elan Microelectronics      | 32        | 24.62%  |
| LighTuning Technology      | 26        | 20%     |
| AuthenTec                  | 12        | 9.23%   |
| Upek                       | 10        | 7.69%   |
| Synaptics                  | 4         | 3.08%   |
| STMicroelectronics         | 4         | 3.08%   |
| Shenzhen Goodix Technology | 2         | 1.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                  | 31        | 23.85%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 21        | 16.15%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 8         | 6.15%   |
| Validity Sensors VFS495 Fingerprint Reader             | 6         | 4.62%   |
| Validity Sensors VFS471 Fingerprint Reader             | 6         | 4.62%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 5         | 3.85%   |
| Validity Sensors VFS491                                | 4         | 3.08%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 4         | 3.08%   |
| STMicroelectronics Fingerprint Reader                  | 4         | 3.08%   |
| AuthenTec Fingerprint Sensor                           | 4         | 3.08%   |
| Validity Sensors VFS301 Fingerprint Reader             | 3         | 2.31%   |
| Validity Sensors VFS101 Fingerprint Reader             | 3         | 2.31%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 3         | 2.31%   |
| AuthenTec AES2810                                      | 3         | 2.31%   |
| AuthenTec AES1600                                      | 3         | 2.31%   |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 1.54%   |
| Validity Sensors VFS Fingerprint sensor                | 2         | 1.54%   |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 1.54%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 1.54%   |
| Synaptics  WBDI                                        | 2         | 1.54%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 1.54%   |
| LighTuning Fingerprint Reader                          | 2         | 1.54%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 1.54%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 0.77%   |
| Validity Sensors VFS300 Fingerprint Reader             | 1         | 0.77%   |
| Validity Sensors Synaptics WBDI                        | 1         | 0.77%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 0.77%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 0.77%   |
| Elan ELAN:ARM-M4                                       | 1         | 0.77%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 27        | 61.36%  |
| O2 Micro    | 8         | 18.18%  |
| Alcor Micro | 6         | 13.64%  |
| Lenovo      | 3         | 6.82%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 40.91%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 15.91%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 15.91%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 13.64%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.82%   |
| Broadcom 5880                                                                | 2         | 4.55%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2144      | 81.12%  |
| 1     | 436       | 16.5%   |
| 2     | 61        | 2.31%   |
| 4     | 1         | 0.04%   |
| 3     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Multimedia controller    | 192       | 33.86%  |
| Fingerprint reader       | 130       | 22.93%  |
| Net/wireless             | 74        | 13.05%  |
| Graphics card            | 59        | 10.41%  |
| Chipcard                 | 44        | 7.76%   |
| Storage                  | 19        | 3.35%   |
| Communication controller | 17        | 3%      |
| Bluetooth                | 13        | 2.29%   |
| Camera                   | 9         | 1.59%   |
| Net/ethernet             | 3         | 0.53%   |
| Storage/nvme             | 2         | 0.35%   |
| Storage/ide              | 1         | 0.18%   |
| Sound                    | 1         | 0.18%   |
| Network                  | 1         | 0.18%   |
| Modem                    | 1         | 0.18%   |
| Flash memory             | 1         | 0.18%   |

