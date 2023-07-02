Linux in India - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in India.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/India/Desktop/README.md) and [notebooks](/Location/India/Notebook/README.md).

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

Total: 6152

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire E5-575G              | Notebook    | [f127804b4a](https://linux-hardware.org/?probe=f127804b4a) | Jun 30, 2023 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [5ac29ea67f](https://linux-hardware.org/?probe=5ac29ea67f) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [10467d9f3e](https://linux-hardware.org/?probe=10467d9f3e) | Jun 30, 2023 |
| HP            | 15                          | Notebook    | [2d80407689](https://linux-hardware.org/?probe=2d80407689) | Jun 30, 2023 |
| HP            | 15                          | Notebook    | [398d659d8c](https://linux-hardware.org/?probe=398d659d8c) | Jun 30, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [602d134940](https://linux-hardware.org/?probe=602d134940) | Jun 30, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [eab5331f66](https://linux-hardware.org/?probe=eab5331f66) | Jun 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [0ad496c06d](https://linux-hardware.org/?probe=0ad496c06d) | Jun 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0f0defbd9c](https://linux-hardware.org/?probe=0f0defbd9c) | Jun 29, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [0086cae258](https://linux-hardware.org/?probe=0086cae258) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [5d30ae9d05](https://linux-hardware.org/?probe=5d30ae9d05) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6a29eda577](https://linux-hardware.org/?probe=6a29eda577) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bf4abd6e9e](https://linux-hardware.org/?probe=bf4abd6e9e) | Jun 28, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [4baea798b1](https://linux-hardware.org/?probe=4baea798b1) | Jun 27, 2023 |
| Acer          | Swift SFG14-71              | Notebook    | [f66ac636e6](https://linux-hardware.org/?probe=f66ac636e6) | Jun 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [fc7f2b378b](https://linux-hardware.org/?probe=fc7f2b378b) | Jun 27, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [d6b3d5cb90](https://linux-hardware.org/?probe=d6b3d5cb90) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [13c7f88d66](https://linux-hardware.org/?probe=13c7f88d66) | Jun 26, 2023 |
| ASUSTek       | H61M-CS                     | Desktop     | [2878c06857](https://linux-hardware.org/?probe=2878c06857) | Jun 26, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [08ba4bf92b](https://linux-hardware.org/?probe=08ba4bf92b) | Jun 26, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [3dc15705c8](https://linux-hardware.org/?probe=3dc15705c8) | Jun 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA    | Notebook    | [8a764f6629](https://linux-hardware.org/?probe=8a764f6629) | Jun 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [aeb1c6b8d2](https://linux-hardware.org/?probe=aeb1c6b8d2) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1a21c582de](https://linux-hardware.org/?probe=1a21c582de) | Jun 26, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [23499b1838](https://linux-hardware.org/?probe=23499b1838) | Jun 25, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1fc0c8e328](https://linux-hardware.org/?probe=1fc0c8e328) | Jun 25, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [2f5357533f](https://linux-hardware.org/?probe=2f5357533f) | Jun 25, 2023 |
| Lenovo        | E41-55 82FJ                 | Notebook    | [f725e1bd1a](https://linux-hardware.org/?probe=f725e1bd1a) | Jun 25, 2023 |
| Dell          | Precision M6400             | Notebook    | [b68c09e274](https://linux-hardware.org/?probe=b68c09e274) | Jun 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [14cc9e067f](https://linux-hardware.org/?probe=14cc9e067f) | Jun 25, 2023 |
| Dell          | Precision 5540              | Notebook    | [7d6c1fe39d](https://linux-hardware.org/?probe=7d6c1fe39d) | Jun 25, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [7f8217bce2](https://linux-hardware.org/?probe=7f8217bce2) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5679200535](https://linux-hardware.org/?probe=5679200535) | Jun 24, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [9279842ec3](https://linux-hardware.org/?probe=9279842ec3) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [628fca0448](https://linux-hardware.org/?probe=628fca0448) | Jun 24, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [77473ea84c](https://linux-hardware.org/?probe=77473ea84c) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [de0580cf77](https://linux-hardware.org/?probe=de0580cf77) | Jun 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [b8d79ce295](https://linux-hardware.org/?probe=b8d79ce295) | Jun 24, 2023 |
| Dell          | G5 5505                     | Notebook    | [dbe52869d7](https://linux-hardware.org/?probe=dbe52869d7) | Jun 23, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [515f5a5392](https://linux-hardware.org/?probe=515f5a5392) | Jun 23, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [15fd4078ea](https://linux-hardware.org/?probe=15fd4078ea) | Jun 23, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [4d9c9f9bd0](https://linux-hardware.org/?probe=4d9c9f9bd0) | Jun 23, 2023 |
| Dell          | G5 5505                     | Notebook    | [f435440e91](https://linux-hardware.org/?probe=f435440e91) | Jun 23, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [5c76172491](https://linux-hardware.org/?probe=5c76172491) | Jun 22, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | Notebook    | [110c366456](https://linux-hardware.org/?probe=110c366456) | Jun 22, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [7cc301b3f7](https://linux-hardware.org/?probe=7cc301b3f7) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [baab7764b1](https://linux-hardware.org/?probe=baab7764b1) | Jun 21, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [ab7c961e2b](https://linux-hardware.org/?probe=ab7c961e2b) | Jun 21, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [1ba2e18bc1](https://linux-hardware.org/?probe=1ba2e18bc1) | Jun 21, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [c80413d259](https://linux-hardware.org/?probe=c80413d259) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [3375eaaeb3](https://linux-hardware.org/?probe=3375eaaeb3) | Jun 20, 2023 |
| Dell          | Precision 5560              | Notebook    | [ee53248c8c](https://linux-hardware.org/?probe=ee53248c8c) | Jun 20, 2023 |
| Intel         | H61                         | Desktop     | [d8de2bb1a7](https://linux-hardware.org/?probe=d8de2bb1a7) | Jun 20, 2023 |
| POWERX        | G41                         | Desktop     | [5d1b37ec3a](https://linux-hardware.org/?probe=5d1b37ec3a) | Jun 20, 2023 |
| Lenovo        | ThinkPad T460s 20F9005BU... | Notebook    | [59a527c934](https://linux-hardware.org/?probe=59a527c934) | Jun 20, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [f975205ebd](https://linux-hardware.org/?probe=f975205ebd) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [6dea148dd7](https://linux-hardware.org/?probe=6dea148dd7) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [63381e724a](https://linux-hardware.org/?probe=63381e724a) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [4b20fef62f](https://linux-hardware.org/?probe=4b20fef62f) | Jun 19, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [e195f838c3](https://linux-hardware.org/?probe=e195f838c3) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [94999d2965](https://linux-hardware.org/?probe=94999d2965) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | Notebook    | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| HP            | EliteBook x360 1030 G4      | Convertible | [acaa27666b](https://linux-hardware.org/?probe=acaa27666b) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [a585caa218](https://linux-hardware.org/?probe=a585caa218) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [4907b6927a](https://linux-hardware.org/?probe=4907b6927a) | Jun 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [edd82d072b](https://linux-hardware.org/?probe=edd82d072b) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [ccb49000fa](https://linux-hardware.org/?probe=ccb49000fa) | Jun 16, 2023 |
| Unknown       | G41 Series                  | Desktop     | [07122155fa](https://linux-hardware.org/?probe=07122155fa) | Jun 15, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [20ddd7a28b](https://linux-hardware.org/?probe=20ddd7a28b) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [69048c54c9](https://linux-hardware.org/?probe=69048c54c9) | Jun 14, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [fe39c9b2ce](https://linux-hardware.org/?probe=fe39c9b2ce) | Jun 14, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [2b4d088695](https://linux-hardware.org/?probe=2b4d088695) | Jun 14, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [a5143e68f8](https://linux-hardware.org/?probe=a5143e68f8) | Jun 14, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [138e3687ac](https://linux-hardware.org/?probe=138e3687ac) | Jun 14, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [fffb0a25f1](https://linux-hardware.org/?probe=fffb0a25f1) | Jun 13, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [1ede32fb28](https://linux-hardware.org/?probe=1ede32fb28) | Jun 13, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [9ab7a065c4](https://linux-hardware.org/?probe=9ab7a065c4) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [5e636c4693](https://linux-hardware.org/?probe=5e636c4693) | Jun 13, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [c0e73c1ff8](https://linux-hardware.org/?probe=c0e73c1ff8) | Jun 12, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [e6713db4c3](https://linux-hardware.org/?probe=e6713db4c3) | Jun 12, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [f31365f369](https://linux-hardware.org/?probe=f31365f369) | Jun 12, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [ffd9da63dd](https://linux-hardware.org/?probe=ffd9da63dd) | Jun 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [0d80451f80](https://linux-hardware.org/?probe=0d80451f80) | Jun 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [b25c3a4ecb](https://linux-hardware.org/?probe=b25c3a4ecb) | Jun 11, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [a192769f1b](https://linux-hardware.org/?probe=a192769f1b) | Jun 11, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [66aa96212a](https://linux-hardware.org/?probe=66aa96212a) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [864729436a](https://linux-hardware.org/?probe=864729436a) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1d46e48d92](https://linux-hardware.org/?probe=1d46e48d92) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [7ab0866235](https://linux-hardware.org/?probe=7ab0866235) | Jun 10, 2023 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [6090a53f8a](https://linux-hardware.org/?probe=6090a53f8a) | Jun 10, 2023 |
| HP            | 339A                        | Desktop     | [348ce53f71](https://linux-hardware.org/?probe=348ce53f71) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [1eeb12a5ca](https://linux-hardware.org/?probe=1eeb12a5ca) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [e46f2fe66e](https://linux-hardware.org/?probe=e46f2fe66e) | Jun 10, 2023 |
| HP            | G42                         | Notebook    | [83eca37118](https://linux-hardware.org/?probe=83eca37118) | Jun 10, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [5dd8c1fed8](https://linux-hardware.org/?probe=5dd8c1fed8) | Jun 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [b23bc1dc48](https://linux-hardware.org/?probe=b23bc1dc48) | Jun 08, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [fb6aca39d9](https://linux-hardware.org/?probe=fb6aca39d9) | Jun 08, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [e103817b2d](https://linux-hardware.org/?probe=e103817b2d) | Jun 07, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [6062ee64a9](https://linux-hardware.org/?probe=6062ee64a9) | Jun 07, 2023 |
| Dell          | G15 5511                    | Notebook    | [ddee46cbfa](https://linux-hardware.org/?probe=ddee46cbfa) | Jun 07, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [14016f0f6f](https://linux-hardware.org/?probe=14016f0f6f) | Jun 07, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [721ff5908a](https://linux-hardware.org/?probe=721ff5908a) | Jun 06, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Dell          | Latitude E6430              | Notebook    | [bfa5da5406](https://linux-hardware.org/?probe=bfa5da5406) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [1e5a50fa47](https://linux-hardware.org/?probe=1e5a50fa47) | Jun 06, 2023 |
| Acer          | Aspire A314-36M             | Notebook    | [7cab0d1591](https://linux-hardware.org/?probe=7cab0d1591) | Jun 06, 2023 |
| HP            | 3397                        | Desktop     | [f85e642ee3](https://linux-hardware.org/?probe=f85e642ee3) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [503bc1f4cc](https://linux-hardware.org/?probe=503bc1f4cc) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [31a814cd0e](https://linux-hardware.org/?probe=31a814cd0e) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [2a612dc748](https://linux-hardware.org/?probe=2a612dc748) | Jun 06, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [5159be9e2b](https://linux-hardware.org/?probe=5159be9e2b) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Sony          | VPCEH25EN                   | Notebook    | [2b47c1b9a5](https://linux-hardware.org/?probe=2b47c1b9a5) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [ea59ba572e](https://linux-hardware.org/?probe=ea59ba572e) | Jun 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [6528b4bffe](https://linux-hardware.org/?probe=6528b4bffe) | Jun 05, 2023 |
| Dell          | Latitude 3460               | Notebook    | [1a92cd0779](https://linux-hardware.org/?probe=1a92cd0779) | Jun 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [dbc9b8df0b](https://linux-hardware.org/?probe=dbc9b8df0b) | Jun 05, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [ceab55a00c](https://linux-hardware.org/?probe=ceab55a00c) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [e9dd850e23](https://linux-hardware.org/?probe=e9dd850e23) | Jun 05, 2023 |
| BY OEM        | ZRD1103                     | Desktop     | [316792c3ac](https://linux-hardware.org/?probe=316792c3ac) | Jun 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | Notebook    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| AVITA         | NS14A8                      | Notebook    | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [87b33e1181](https://linux-hardware.org/?probe=87b33e1181) | Jun 04, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [1e4ffa48ce](https://linux-hardware.org/?probe=1e4ffa48ce) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e86a159ec5](https://linux-hardware.org/?probe=e86a159ec5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [01cd20c83d](https://linux-hardware.org/?probe=01cd20c83d) | Jun 03, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [a0cc355293](https://linux-hardware.org/?probe=a0cc355293) | Jun 03, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [a080a07f52](https://linux-hardware.org/?probe=a080a07f52) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [b8c8f96b56](https://linux-hardware.org/?probe=b8c8f96b56) | Jun 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [13adb1e221](https://linux-hardware.org/?probe=13adb1e221) | Jun 02, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [0acaadb3d1](https://linux-hardware.org/?probe=0acaadb3d1) | Jun 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [af2f742bc5](https://linux-hardware.org/?probe=af2f742bc5) | Jun 01, 2023 |
| OEM           | Intel H81                   | Desktop     | [b62ec659fa](https://linux-hardware.org/?probe=b62ec659fa) | Jun 01, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [b7032438d2](https://linux-hardware.org/?probe=b7032438d2) | May 31, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [2c315764a9](https://linux-hardware.org/?probe=2c315764a9) | May 31, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6c814f5bb5](https://linux-hardware.org/?probe=6c814f5bb5) | May 31, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [cee0a13d3f](https://linux-hardware.org/?probe=cee0a13d3f) | May 31, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [dc6256036e](https://linux-hardware.org/?probe=dc6256036e) | May 30, 2023 |
| Intel         | DH61BF AAG81311-102         | Desktop     | [22123492ab](https://linux-hardware.org/?probe=22123492ab) | May 30, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [c15d9d37c7](https://linux-hardware.org/?probe=c15d9d37c7) | May 30, 2023 |
| Lenovo        | 36C5 SDK0Q55724 WIN 3273... | Desktop     | [01076d8e8b](https://linux-hardware.org/?probe=01076d8e8b) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [7653baa0f8](https://linux-hardware.org/?probe=7653baa0f8) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [89bb5ff663](https://linux-hardware.org/?probe=89bb5ff663) | May 29, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | Notebook    | [087565aed3](https://linux-hardware.org/?probe=087565aed3) | May 29, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [108833c92b](https://linux-hardware.org/?probe=108833c92b) | May 29, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [c5b13d6ea2](https://linux-hardware.org/?probe=c5b13d6ea2) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | Notebook    | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [423fe90cad](https://linux-hardware.org/?probe=423fe90cad) | May 28, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [a1aa06298d](https://linux-hardware.org/?probe=a1aa06298d) | May 28, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [4d8767d94b](https://linux-hardware.org/?probe=4d8767d94b) | May 28, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [902b837f1a](https://linux-hardware.org/?probe=902b837f1a) | May 27, 2023 |
| Dell          | Latitude 7480               | Notebook    | [2c74ec8198](https://linux-hardware.org/?probe=2c74ec8198) | May 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [5cf35078b0](https://linux-hardware.org/?probe=5cf35078b0) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c9c4e5ddb5](https://linux-hardware.org/?probe=c9c4e5ddb5) | May 26, 2023 |
| Dell          | 0H6C3V A00                  | All in one  | [16ce047abb](https://linux-hardware.org/?probe=16ce047abb) | May 26, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [4a59deb075](https://linux-hardware.org/?probe=4a59deb075) | May 25, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [0316f8d274](https://linux-hardware.org/?probe=0316f8d274) | May 25, 2023 |
| Dell          | 0H6C3V A00                  | All in one  | [a6b57b9588](https://linux-hardware.org/?probe=a6b57b9588) | May 25, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [270540781d](https://linux-hardware.org/?probe=270540781d) | May 25, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [53cbfa6255](https://linux-hardware.org/?probe=53cbfa6255) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1fea1a6529](https://linux-hardware.org/?probe=1fea1a6529) | May 25, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [490c47960a](https://linux-hardware.org/?probe=490c47960a) | May 25, 2023 |
| MSI           | GF63 Thin 9RC               | Notebook    | [aef2c48b64](https://linux-hardware.org/?probe=aef2c48b64) | May 24, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [ae4f8dba2c](https://linux-hardware.org/?probe=ae4f8dba2c) | May 24, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [ebff669275](https://linux-hardware.org/?probe=ebff669275) | May 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [bcb5af2775](https://linux-hardware.org/?probe=bcb5af2775) | May 24, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [e8bc14fc34](https://linux-hardware.org/?probe=e8bc14fc34) | May 23, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [c5615351bb](https://linux-hardware.org/?probe=c5615351bb) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [691b17e221](https://linux-hardware.org/?probe=691b17e221) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [d704fd9efd](https://linux-hardware.org/?probe=d704fd9efd) | May 23, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [7d93944943](https://linux-hardware.org/?probe=7d93944943) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [aec9e5a959](https://linux-hardware.org/?probe=aec9e5a959) | May 22, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [5838a30c8b](https://linux-hardware.org/?probe=5838a30c8b) | May 22, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | Notebook    | [33773ecf4d](https://linux-hardware.org/?probe=33773ecf4d) | May 22, 2023 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [7d81e00b27](https://linux-hardware.org/?probe=7d81e00b27) | May 22, 2023 |
| HP            | 8599                        | Desktop     | [2e9caaf13a](https://linux-hardware.org/?probe=2e9caaf13a) | May 22, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [88d77ec57e](https://linux-hardware.org/?probe=88d77ec57e) | May 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [59464cac80](https://linux-hardware.org/?probe=59464cac80) | May 20, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [ff730fcbf6](https://linux-hardware.org/?probe=ff730fcbf6) | May 20, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [7aef6229db](https://linux-hardware.org/?probe=7aef6229db) | May 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| HP            | Laptop 15s-dr3xxx           | Notebook    | [4c44db2d32](https://linux-hardware.org/?probe=4c44db2d32) | May 19, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [61f60c8a7d](https://linux-hardware.org/?probe=61f60c8a7d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b0ed659e7d](https://linux-hardware.org/?probe=b0ed659e7d) | May 19, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [7b98244b73](https://linux-hardware.org/?probe=7b98244b73) | May 19, 2023 |
| Fujitsu       | JIB75Y3                     | Desktop     | [1926915856](https://linux-hardware.org/?probe=1926915856) | May 19, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [b8a04e73b8](https://linux-hardware.org/?probe=b8a04e73b8) | May 18, 2023 |
| Dell          | Inspiron 14 5408            | Notebook    | [c1853f7df2](https://linux-hardware.org/?probe=c1853f7df2) | May 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [da7af17667](https://linux-hardware.org/?probe=da7af17667) | May 17, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [ddc3152cbc](https://linux-hardware.org/?probe=ddc3152cbc) | May 17, 2023 |
| MSI           | GF63 Thin 9RC               | Notebook    | [b8f2e92853](https://linux-hardware.org/?probe=b8f2e92853) | May 16, 2023 |
| HP            | 339A                        | Desktop     | [72433c7d24](https://linux-hardware.org/?probe=72433c7d24) | May 16, 2023 |
| Lenovo        | 3168 NOK                    | Desktop     | [d541bf827b](https://linux-hardware.org/?probe=d541bf827b) | May 15, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [3e34d3a71c](https://linux-hardware.org/?probe=3e34d3a71c) | May 15, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [000f3c2444](https://linux-hardware.org/?probe=000f3c2444) | May 15, 2023 |
| Fujitsu       | JIB75Y3                     | Desktop     | [31146fe86e](https://linux-hardware.org/?probe=31146fe86e) | May 15, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [b938ce8d64](https://linux-hardware.org/?probe=b938ce8d64) | May 15, 2023 |
| HP            | 3397                        | Desktop     | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [fb4bda01b7](https://linux-hardware.org/?probe=fb4bda01b7) | May 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0060b3cb1c](https://linux-hardware.org/?probe=0060b3cb1c) | May 14, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [b9e5026a6a](https://linux-hardware.org/?probe=b9e5026a6a) | May 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [4a322b398b](https://linux-hardware.org/?probe=4a322b398b) | May 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [d251ccd249](https://linux-hardware.org/?probe=d251ccd249) | May 13, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [bc0dacd119](https://linux-hardware.org/?probe=bc0dacd119) | May 13, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [d06731c12e](https://linux-hardware.org/?probe=d06731c12e) | May 13, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [677e681a2d](https://linux-hardware.org/?probe=677e681a2d) | May 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a8c81eafb0](https://linux-hardware.org/?probe=a8c81eafb0) | May 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [388408dc4b](https://linux-hardware.org/?probe=388408dc4b) | May 13, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [e0c2e78cad](https://linux-hardware.org/?probe=e0c2e78cad) | May 13, 2023 |
| AVITA         | NS14A6                      | Notebook    | [253f084ba1](https://linux-hardware.org/?probe=253f084ba1) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c9597b5b24](https://linux-hardware.org/?probe=c9597b5b24) | May 11, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [6cd766b17e](https://linux-hardware.org/?probe=6cd766b17e) | May 11, 2023 |
| Dell          | Latitude E5470              | Notebook    | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| AVITA         | NS14A6                      | Notebook    | [d2cdbff22c](https://linux-hardware.org/?probe=d2cdbff22c) | May 11, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [328d899b1c](https://linux-hardware.org/?probe=328d899b1c) | May 11, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [040f5917ec](https://linux-hardware.org/?probe=040f5917ec) | May 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [601a09abf6](https://linux-hardware.org/?probe=601a09abf6) | May 10, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [02c4a35621](https://linux-hardware.org/?probe=02c4a35621) | May 10, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | Notebook    | [0308c5d0c5](https://linux-hardware.org/?probe=0308c5d0c5) | May 10, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [d2d1037c9d](https://linux-hardware.org/?probe=d2d1037c9d) | May 09, 2023 |
| Dell          | Latitude 3490               | Notebook    | [f9ed2aa5ab](https://linux-hardware.org/?probe=f9ed2aa5ab) | May 09, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [745096932c](https://linux-hardware.org/?probe=745096932c) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [dfe5f362e2](https://linux-hardware.org/?probe=dfe5f362e2) | May 09, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [cbc45e8ffa](https://linux-hardware.org/?probe=cbc45e8ffa) | May 09, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [c4a2b98dc5](https://linux-hardware.org/?probe=c4a2b98dc5) | May 09, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [bcccbb24de](https://linux-hardware.org/?probe=bcccbb24de) | May 09, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [e1313af3e6](https://linux-hardware.org/?probe=e1313af3e6) | May 08, 2023 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [410350c836](https://linux-hardware.org/?probe=410350c836) | May 08, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [c74bb83ac9](https://linux-hardware.org/?probe=c74bb83ac9) | May 08, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [f5acf4a186](https://linux-hardware.org/?probe=f5acf4a186) | May 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7e003cf7a9](https://linux-hardware.org/?probe=7e003cf7a9) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [99fbd772e8](https://linux-hardware.org/?probe=99fbd772e8) | May 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b1b0fa7485](https://linux-hardware.org/?probe=b1b0fa7485) | May 07, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [08b1152328](https://linux-hardware.org/?probe=08b1152328) | May 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [741b9f90e1](https://linux-hardware.org/?probe=741b9f90e1) | May 07, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [1dbc92c072](https://linux-hardware.org/?probe=1dbc92c072) | May 07, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [845c2112be](https://linux-hardware.org/?probe=845c2112be) | May 06, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [3569e8fb31](https://linux-hardware.org/?probe=3569e8fb31) | May 06, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [5b49eec8c6](https://linux-hardware.org/?probe=5b49eec8c6) | May 06, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [20461b100d](https://linux-hardware.org/?probe=20461b100d) | May 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [834d2304aa](https://linux-hardware.org/?probe=834d2304aa) | May 06, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [dd6f6a940f](https://linux-hardware.org/?probe=dd6f6a940f) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7b66fbdc3](https://linux-hardware.org/?probe=c7b66fbdc3) | May 05, 2023 |
| Acer          | Aspire E5-576               | Notebook    | [a73b11b28f](https://linux-hardware.org/?probe=a73b11b28f) | May 05, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [36de4a9de4](https://linux-hardware.org/?probe=36de4a9de4) | May 05, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS0SE00     | Notebook    | [c5d4b5a3a7](https://linux-hardware.org/?probe=c5d4b5a3a7) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [b7a4021d1f](https://linux-hardware.org/?probe=b7a4021d1f) | May 05, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [4cc44f819d](https://linux-hardware.org/?probe=4cc44f819d) | May 05, 2023 |
| Sony          | SVE15117FNW                 | Notebook    | [7ec421e4a1](https://linux-hardware.org/?probe=7ec421e4a1) | May 04, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [e60b96481a](https://linux-hardware.org/?probe=e60b96481a) | May 04, 2023 |
| Gateway       | NE46R                       | Notebook    | [05291d9029](https://linux-hardware.org/?probe=05291d9029) | May 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| Dell          | Latitude 5490               | Notebook    | [2ce70b7a2c](https://linux-hardware.org/?probe=2ce70b7a2c) | May 04, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [ac499d5a17](https://linux-hardware.org/?probe=ac499d5a17) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [6116c0df52](https://linux-hardware.org/?probe=6116c0df52) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [f115dd1851](https://linux-hardware.org/?probe=f115dd1851) | May 03, 2023 |
| Dell          | Latitude 5480               | Notebook    | [a8b85d06d8](https://linux-hardware.org/?probe=a8b85d06d8) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [530aaeef9d](https://linux-hardware.org/?probe=530aaeef9d) | May 02, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [eae11b1ac4](https://linux-hardware.org/?probe=eae11b1ac4) | May 02, 2023 |
| HP            | 86FC MVB                    | Desktop     | [de40052f4c](https://linux-hardware.org/?probe=de40052f4c) | May 02, 2023 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [0873c73291](https://linux-hardware.org/?probe=0873c73291) | May 02, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [e94ef67ab2](https://linux-hardware.org/?probe=e94ef67ab2) | May 01, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [cc65b3de6f](https://linux-hardware.org/?probe=cc65b3de6f) | May 01, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [842333a8da](https://linux-hardware.org/?probe=842333a8da) | May 01, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [4f72daaab8](https://linux-hardware.org/?probe=4f72daaab8) | May 01, 2023 |
| Dell          | Latitude E5420              | Notebook    | [df8c9e7f40](https://linux-hardware.org/?probe=df8c9e7f40) | Apr 30, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [7077a00b02](https://linux-hardware.org/?probe=7077a00b02) | Apr 30, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ccb46c2a2b](https://linux-hardware.org/?probe=ccb46c2a2b) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [446a548122](https://linux-hardware.org/?probe=446a548122) | Apr 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [2c335c5bfb](https://linux-hardware.org/?probe=2c335c5bfb) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [0ea5e1926e](https://linux-hardware.org/?probe=0ea5e1926e) | Apr 29, 2023 |
| Dell          | Latitude E5470              | Notebook    | [c6c943679f](https://linux-hardware.org/?probe=c6c943679f) | Apr 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [216a4b9b67](https://linux-hardware.org/?probe=216a4b9b67) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [6736f3d911](https://linux-hardware.org/?probe=6736f3d911) | Apr 28, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [2ba1bab0fe](https://linux-hardware.org/?probe=2ba1bab0fe) | Apr 28, 2023 |
| Dell          | 0DNMV1 A01                  | Desktop     | [ab17992052](https://linux-hardware.org/?probe=ab17992052) | Apr 28, 2023 |
| Dell          | 0DNMV1 A01                  | Desktop     | [04bfccce7b](https://linux-hardware.org/?probe=04bfccce7b) | Apr 28, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | Notebook    | [65f390b956](https://linux-hardware.org/?probe=65f390b956) | Apr 28, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [eb327f9dc8](https://linux-hardware.org/?probe=eb327f9dc8) | Apr 28, 2023 |
| Unknown       | G41                         | Desktop     | [2a6a185bec](https://linux-hardware.org/?probe=2a6a185bec) | Apr 28, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [000022b2dd](https://linux-hardware.org/?probe=000022b2dd) | Apr 28, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [ca9179cae4](https://linux-hardware.org/?probe=ca9179cae4) | Apr 28, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [2499c633a5](https://linux-hardware.org/?probe=2499c633a5) | Apr 27, 2023 |
| MSI           | Modern 14 C7M               | Notebook    | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [a23cf53cec](https://linux-hardware.org/?probe=a23cf53cec) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3e8fe7fed4](https://linux-hardware.org/?probe=3e8fe7fed4) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | Notebook    | [4bdb6b2a7f](https://linux-hardware.org/?probe=4bdb6b2a7f) | Apr 27, 2023 |
| Dell          | Vostro 1550                 | Notebook    | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [7ab7e066cf](https://linux-hardware.org/?probe=7ab7e066cf) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [e0d69966e9](https://linux-hardware.org/?probe=e0d69966e9) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [ab52633e07](https://linux-hardware.org/?probe=ab52633e07) | Apr 26, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [b6b7cdfe22](https://linux-hardware.org/?probe=b6b7cdfe22) | Apr 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a2c2f1f536](https://linux-hardware.org/?probe=a2c2f1f536) | Apr 25, 2023 |
| Lenovo        | ThinkPad E14 20RAS1DB00     | Notebook    | [8e09a153f5](https://linux-hardware.org/?probe=8e09a153f5) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [45199e8296](https://linux-hardware.org/?probe=45199e8296) | Apr 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [2787d97e6e](https://linux-hardware.org/?probe=2787d97e6e) | Apr 24, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | Notebook    | [8bfea5add2](https://linux-hardware.org/?probe=8bfea5add2) | Apr 24, 2023 |
| HP            | G42                         | Notebook    | [58b0a0981e](https://linux-hardware.org/?probe=58b0a0981e) | Apr 23, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [45af810de1](https://linux-hardware.org/?probe=45af810de1) | Apr 21, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [cb9c1bfb3c](https://linux-hardware.org/?probe=cb9c1bfb3c) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [888b7bed45](https://linux-hardware.org/?probe=888b7bed45) | Apr 21, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [8578f44f47](https://linux-hardware.org/?probe=8578f44f47) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [91999697ba](https://linux-hardware.org/?probe=91999697ba) | Apr 20, 2023 |
| Acer          | Aspire 5745                 | Notebook    | [19e6d70ce0](https://linux-hardware.org/?probe=19e6d70ce0) | Apr 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHS... | Notebook    | [59d7ef5ddd](https://linux-hardware.org/?probe=59d7ef5ddd) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [46ade409df](https://linux-hardware.org/?probe=46ade409df) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [954388c5e0](https://linux-hardware.org/?probe=954388c5e0) | Apr 19, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0W    | Notebook    | [97447a0777](https://linux-hardware.org/?probe=97447a0777) | Apr 19, 2023 |
| MSI           | 0B58h                       | Desktop     | [6473456480](https://linux-hardware.org/?probe=6473456480) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [3a855386b4](https://linux-hardware.org/?probe=3a855386b4) | Apr 18, 2023 |
| MSI           | GP65 Leopard 10SEK          | Notebook    | [3b852bad57](https://linux-hardware.org/?probe=3b852bad57) | Apr 18, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [10bfabc1b8](https://linux-hardware.org/?probe=10bfabc1b8) | Apr 18, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [bafa62c759](https://linux-hardware.org/?probe=bafa62c759) | Apr 18, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [f129cb2de1](https://linux-hardware.org/?probe=f129cb2de1) | Apr 18, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [6041b126fa](https://linux-hardware.org/?probe=6041b126fa) | Apr 18, 2023 |
| HP            | 630                         | Notebook    | [daeae9f12e](https://linux-hardware.org/?probe=daeae9f12e) | Apr 18, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [9be6e0f395](https://linux-hardware.org/?probe=9be6e0f395) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d1d3cf9928](https://linux-hardware.org/?probe=d1d3cf9928) | Apr 17, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [786daebed0](https://linux-hardware.org/?probe=786daebed0) | Apr 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [dbd2cfbd81](https://linux-hardware.org/?probe=dbd2cfbd81) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| ASUSTek       | EX-B560M-V5                 | Desktop     | [243b7b3722](https://linux-hardware.org/?probe=243b7b3722) | Apr 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7f5feb82ab](https://linux-hardware.org/?probe=7f5feb82ab) | Apr 17, 2023 |
| Gigabyte      | H81M-S                      | Desktop     | [db6516c973](https://linux-hardware.org/?probe=db6516c973) | Apr 16, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [0dfc78d12a](https://linux-hardware.org/?probe=0dfc78d12a) | Apr 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [bfaea1065e](https://linux-hardware.org/?probe=bfaea1065e) | Apr 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3738d57a9c](https://linux-hardware.org/?probe=3738d57a9c) | Apr 15, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [bc7d49c64c](https://linux-hardware.org/?probe=bc7d49c64c) | Apr 15, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7d9278e08a](https://linux-hardware.org/?probe=7d9278e08a) | Apr 15, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [c99626b458](https://linux-hardware.org/?probe=c99626b458) | Apr 14, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [a2b5435974](https://linux-hardware.org/?probe=a2b5435974) | Apr 14, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [50a9e6f749](https://linux-hardware.org/?probe=50a9e6f749) | Apr 14, 2023 |
| Acer          | AO756                       | Notebook    | [c17d5276ec](https://linux-hardware.org/?probe=c17d5276ec) | Apr 14, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6106a2c31f](https://linux-hardware.org/?probe=6106a2c31f) | Apr 13, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [42e4889a44](https://linux-hardware.org/?probe=42e4889a44) | Apr 13, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [f63c87bf19](https://linux-hardware.org/?probe=f63c87bf19) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0d0ff5240b](https://linux-hardware.org/?probe=0d0ff5240b) | Apr 12, 2023 |
| ASUSTek       | K53U                        | Notebook    | [19ec753136](https://linux-hardware.org/?probe=19ec753136) | Apr 12, 2023 |
| Dell          | Precision 5520              | Notebook    | [32eb960b25](https://linux-hardware.org/?probe=32eb960b25) | Apr 12, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [8b0573684a](https://linux-hardware.org/?probe=8b0573684a) | Apr 12, 2023 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [3225aa17d2](https://linux-hardware.org/?probe=3225aa17d2) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [40c7ac46e2](https://linux-hardware.org/?probe=40c7ac46e2) | Apr 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [b9d22dfaea](https://linux-hardware.org/?probe=b9d22dfaea) | Apr 10, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [bc18513752](https://linux-hardware.org/?probe=bc18513752) | Apr 09, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [0bbe9702ca](https://linux-hardware.org/?probe=0bbe9702ca) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [c82c56c81e](https://linux-hardware.org/?probe=c82c56c81e) | Apr 09, 2023 |
| Dell          | Latitude 7275               | Notebook    | [d1a55f8f55](https://linux-hardware.org/?probe=d1a55f8f55) | Apr 09, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [51c8f59aeb](https://linux-hardware.org/?probe=51c8f59aeb) | Apr 08, 2023 |
| Dell          | Latitude 3410               | Notebook    | [9fd7d9d439](https://linux-hardware.org/?probe=9fd7d9d439) | Apr 08, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [10c9b38ed6](https://linux-hardware.org/?probe=10c9b38ed6) | Apr 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [133568abf2](https://linux-hardware.org/?probe=133568abf2) | Apr 07, 2023 |
| ASUSTek       | K54C                        | Notebook    | [4f37849c94](https://linux-hardware.org/?probe=4f37849c94) | Apr 07, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [122c9d0ae2](https://linux-hardware.org/?probe=122c9d0ae2) | Apr 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f29d8154a2](https://linux-hardware.org/?probe=f29d8154a2) | Apr 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [c26cae6392](https://linux-hardware.org/?probe=c26cae6392) | Apr 05, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [62bdbae29c](https://linux-hardware.org/?probe=62bdbae29c) | Apr 05, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [fef3cbc941](https://linux-hardware.org/?probe=fef3cbc941) | Apr 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [8425bb5da3](https://linux-hardware.org/?probe=8425bb5da3) | Apr 04, 2023 |
| HP            | 1495                        | Desktop     | [c0665ecb23](https://linux-hardware.org/?probe=c0665ecb23) | Apr 04, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [d56565f374](https://linux-hardware.org/?probe=d56565f374) | Apr 04, 2023 |
| Dell          | Latitude E6420              | Notebook    | [b35bf27d28](https://linux-hardware.org/?probe=b35bf27d28) | Apr 04, 2023 |
| HP            | 1000                        | Notebook    | [111c9bd980](https://linux-hardware.org/?probe=111c9bd980) | Apr 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [7325272558](https://linux-hardware.org/?probe=7325272558) | Apr 04, 2023 |
| Lenovo        | Unknown                     | Notebook    | [4216d2969c](https://linux-hardware.org/?probe=4216d2969c) | Apr 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [d3a27ee996](https://linux-hardware.org/?probe=d3a27ee996) | Apr 03, 2023 |
| Lenovo        | 3724                        | All in one  | [690f25d1ab](https://linux-hardware.org/?probe=690f25d1ab) | Apr 03, 2023 |
| Gateway       | NE56R                       | Notebook    | [ffa6b1d3f3](https://linux-hardware.org/?probe=ffa6b1d3f3) | Apr 03, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [4145a32920](https://linux-hardware.org/?probe=4145a32920) | Apr 03, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | Notebook    | [6ace928ea5](https://linux-hardware.org/?probe=6ace928ea5) | Apr 03, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [cc341f3faf](https://linux-hardware.org/?probe=cc341f3faf) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Lenovo        | ThinkPad E14 20RAS0D800     | Notebook    | [ea2f5b484f](https://linux-hardware.org/?probe=ea2f5b484f) | Apr 02, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [1561095eff](https://linux-hardware.org/?probe=1561095eff) | Apr 02, 2023 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [5380352186](https://linux-hardware.org/?probe=5380352186) | Apr 02, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [d018871b72](https://linux-hardware.org/?probe=d018871b72) | Apr 02, 2023 |
| HP            | Laptop 15q-ds0xxx           | Notebook    | [42bd53a04e](https://linux-hardware.org/?probe=42bd53a04e) | Apr 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [bfba694531](https://linux-hardware.org/?probe=bfba694531) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [4169f13182](https://linux-hardware.org/?probe=4169f13182) | Apr 01, 2023 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [cd6dee4651](https://linux-hardware.org/?probe=cd6dee4651) | Apr 01, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [d93b1d27e1](https://linux-hardware.org/?probe=d93b1d27e1) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [0992e2d8d8](https://linux-hardware.org/?probe=0992e2d8d8) | Mar 31, 2023 |
| HP            | 250 G3                      | Notebook    | [519b0e31a8](https://linux-hardware.org/?probe=519b0e31a8) | Mar 30, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [3636f7f999](https://linux-hardware.org/?probe=3636f7f999) | Mar 30, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [f24b481b5b](https://linux-hardware.org/?probe=f24b481b5b) | Mar 30, 2023 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [c68415cbb6](https://linux-hardware.org/?probe=c68415cbb6) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [d1295d9d1e](https://linux-hardware.org/?probe=d1295d9d1e) | Mar 30, 2023 |
| Acer          | Extensa 215-23              | Notebook    | [bf5730d468](https://linux-hardware.org/?probe=bf5730d468) | Mar 29, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [a2ba637448](https://linux-hardware.org/?probe=a2ba637448) | Mar 29, 2023 |
| Dell          | 0T2HR0 A02                  | Desktop     | [bf959f65d2](https://linux-hardware.org/?probe=bf959f65d2) | Mar 29, 2023 |
| Intel         | H61                         | Desktop     | [bb6e201a08](https://linux-hardware.org/?probe=bb6e201a08) | Mar 29, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [d6be820d7d](https://linux-hardware.org/?probe=d6be820d7d) | Mar 29, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [c800850b44](https://linux-hardware.org/?probe=c800850b44) | Mar 29, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [67789fc0d1](https://linux-hardware.org/?probe=67789fc0d1) | Mar 28, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [21504643b4](https://linux-hardware.org/?probe=21504643b4) | Mar 28, 2023 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [428dc61d58](https://linux-hardware.org/?probe=428dc61d58) | Mar 28, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [c7f5eaf3f1](https://linux-hardware.org/?probe=c7f5eaf3f1) | Mar 28, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [0a1739f44c](https://linux-hardware.org/?probe=0a1739f44c) | Mar 28, 2023 |
| Dell          | G15 5511                    | Notebook    | [7f15a1e2c7](https://linux-hardware.org/?probe=7f15a1e2c7) | Mar 28, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [83407cead8](https://linux-hardware.org/?probe=83407cead8) | Mar 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [046b4b7497](https://linux-hardware.org/?probe=046b4b7497) | Mar 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [d484c5e138](https://linux-hardware.org/?probe=d484c5e138) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [5b1971e361](https://linux-hardware.org/?probe=5b1971e361) | Mar 27, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8ffc3ea292](https://linux-hardware.org/?probe=8ffc3ea292) | Mar 26, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [70c5569887](https://linux-hardware.org/?probe=70c5569887) | Mar 26, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [3c7b4a17ed](https://linux-hardware.org/?probe=3c7b4a17ed) | Mar 26, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [14cc8c6a5e](https://linux-hardware.org/?probe=14cc8c6a5e) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [fc01cd79a4](https://linux-hardware.org/?probe=fc01cd79a4) | Mar 26, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [1b5f2b52bc](https://linux-hardware.org/?probe=1b5f2b52bc) | Mar 25, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [bad00d337f](https://linux-hardware.org/?probe=bad00d337f) | Mar 25, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [9d9e4e184f](https://linux-hardware.org/?probe=9d9e4e184f) | Mar 25, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [6c4d5eee3f](https://linux-hardware.org/?probe=6c4d5eee3f) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| Lenovo        | ThinkPad T470 20HES4EG00    | Notebook    | [20f698f6d1](https://linux-hardware.org/?probe=20f698f6d1) | Mar 24, 2023 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [882f1dbee1](https://linux-hardware.org/?probe=882f1dbee1) | Mar 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [19efb75aa1](https://linux-hardware.org/?probe=19efb75aa1) | Mar 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [6c184935d3](https://linux-hardware.org/?probe=6c184935d3) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [85accc79b1](https://linux-hardware.org/?probe=85accc79b1) | Mar 23, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f8cd7d94b2](https://linux-hardware.org/?probe=f8cd7d94b2) | Mar 23, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [21f61b5987](https://linux-hardware.org/?probe=21f61b5987) | Mar 23, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [8c48ff04b2](https://linux-hardware.org/?probe=8c48ff04b2) | Mar 23, 2023 |
| Dell          | Precision 7720              | Notebook    | [c3ef75d6eb](https://linux-hardware.org/?probe=c3ef75d6eb) | Mar 23, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [25c6ad6f8b](https://linux-hardware.org/?probe=25c6ad6f8b) | Mar 23, 2023 |
| OEM           | H110 Ver:2.21               | Desktop     | [4b80817d4b](https://linux-hardware.org/?probe=4b80817d4b) | Mar 22, 2023 |
| Intel         | G41                         | Desktop     | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [8c5fde8c1e](https://linux-hardware.org/?probe=8c5fde8c1e) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | Desktop     | [9c01b0ee80](https://linux-hardware.org/?probe=9c01b0ee80) | Mar 22, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [e885d387ee](https://linux-hardware.org/?probe=e885d387ee) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [d068d67f2d](https://linux-hardware.org/?probe=d068d67f2d) | Mar 21, 2023 |
| Dell          | Latitude E6420              | Notebook    | [0ed503758b](https://linux-hardware.org/?probe=0ed503758b) | Mar 20, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [a98665cff1](https://linux-hardware.org/?probe=a98665cff1) | Mar 20, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [8c46e42391](https://linux-hardware.org/?probe=8c46e42391) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [3f233b6f9d](https://linux-hardware.org/?probe=3f233b6f9d) | Mar 20, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [a911c14f22](https://linux-hardware.org/?probe=a911c14f22) | Mar 19, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [28092bd4a4](https://linux-hardware.org/?probe=28092bd4a4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ee8b155a83](https://linux-hardware.org/?probe=ee8b155a83) | Mar 18, 2023 |
| Intel         | H55                         | Desktop     | [2b6fdbe93c](https://linux-hardware.org/?probe=2b6fdbe93c) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [928a8fe84e](https://linux-hardware.org/?probe=928a8fe84e) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [00dc1c3b6e](https://linux-hardware.org/?probe=00dc1c3b6e) | Mar 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [d91eb1923c](https://linux-hardware.org/?probe=d91eb1923c) | Mar 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a0555ea0f6](https://linux-hardware.org/?probe=a0555ea0f6) | Mar 17, 2023 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [8f1c6b4288](https://linux-hardware.org/?probe=8f1c6b4288) | Mar 17, 2023 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [571d56ae48](https://linux-hardware.org/?probe=571d56ae48) | Mar 17, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6bee303acb](https://linux-hardware.org/?probe=6bee303acb) | Mar 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [06dd580c2e](https://linux-hardware.org/?probe=06dd580c2e) | Mar 16, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [e5ec1e2903](https://linux-hardware.org/?probe=e5ec1e2903) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [2eff18f570](https://linux-hardware.org/?probe=2eff18f570) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [2c0d31ff9e](https://linux-hardware.org/?probe=2c0d31ff9e) | Mar 16, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [87046cb547](https://linux-hardware.org/?probe=87046cb547) | Mar 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a85b96633c](https://linux-hardware.org/?probe=a85b96633c) | Mar 16, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [33c9adbcee](https://linux-hardware.org/?probe=33c9adbcee) | Mar 16, 2023 |
| Dell          | Latitude 3490               | Notebook    | [ec0778fc94](https://linux-hardware.org/?probe=ec0778fc94) | Mar 15, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [8272edb058](https://linux-hardware.org/?probe=8272edb058) | Mar 15, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | Notebook    | [af254fca4d](https://linux-hardware.org/?probe=af254fca4d) | Mar 15, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [6c73c46184](https://linux-hardware.org/?probe=6c73c46184) | Mar 15, 2023 |
| Lenovo        | ThinkPad E480 20KNA01HIG    | Notebook    | [c8054d1090](https://linux-hardware.org/?probe=c8054d1090) | Mar 15, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [a87952a308](https://linux-hardware.org/?probe=a87952a308) | Mar 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [a13648959d](https://linux-hardware.org/?probe=a13648959d) | Mar 14, 2023 |
| Dell          | Latitude 3490               | Notebook    | [bd46ba543b](https://linux-hardware.org/?probe=bd46ba543b) | Mar 14, 2023 |
| RDP           | ThinBook 1010               | Notebook    | [fe650dfe16](https://linux-hardware.org/?probe=fe650dfe16) | Mar 14, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [8ff2a816b5](https://linux-hardware.org/?probe=8ff2a816b5) | Mar 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [e9844f7162](https://linux-hardware.org/?probe=e9844f7162) | Mar 13, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [fc24776ab1](https://linux-hardware.org/?probe=fc24776ab1) | Mar 13, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [8c91461d71](https://linux-hardware.org/?probe=8c91461d71) | Mar 12, 2023 |
| Dell          | Latitude 3510               | Notebook    | [13ed29770d](https://linux-hardware.org/?probe=13ed29770d) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [d1bf2f0a8b](https://linux-hardware.org/?probe=d1bf2f0a8b) | Mar 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d98940e14](https://linux-hardware.org/?probe=3d98940e14) | Mar 12, 2023 |
| Infinix       | INBOOK X2 PLUS              | Notebook    | [62b4169c3e](https://linux-hardware.org/?probe=62b4169c3e) | Mar 11, 2023 |
| Dell          | G15 Special Edition 5521    | Notebook    | [f6b2a6bfe0](https://linux-hardware.org/?probe=f6b2a6bfe0) | Mar 11, 2023 |
| Dell          | G15 Special Edition 5521    | Notebook    | [9fab787ede](https://linux-hardware.org/?probe=9fab787ede) | Mar 11, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [36133f02b8](https://linux-hardware.org/?probe=36133f02b8) | Mar 11, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [a493a6ea35](https://linux-hardware.org/?probe=a493a6ea35) | Mar 11, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [126b4a73a2](https://linux-hardware.org/?probe=126b4a73a2) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS55Q1... | Notebook    | [302abad9dc](https://linux-hardware.org/?probe=302abad9dc) | Mar 11, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [f9cf8b06f6](https://linux-hardware.org/?probe=f9cf8b06f6) | Mar 10, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [bdf01893f8](https://linux-hardware.org/?probe=bdf01893f8) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d35772b8bc](https://linux-hardware.org/?probe=d35772b8bc) | Mar 09, 2023 |
| HP            | Notebook                    | Notebook    | [b5ee32f085](https://linux-hardware.org/?probe=b5ee32f085) | Mar 09, 2023 |
| HP            | Pavilion 15                 | Notebook    | [80a4b9038d](https://linux-hardware.org/?probe=80a4b9038d) | Mar 09, 2023 |
| Dell          | 0XW3KG A02                  | All in one  | [d45b4c63fa](https://linux-hardware.org/?probe=d45b4c63fa) | Mar 09, 2023 |
| Dell          | 0XW3KG A02                  | All in one  | [f4e6d8e7a0](https://linux-hardware.org/?probe=f4e6d8e7a0) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [187761b57d](https://linux-hardware.org/?probe=187761b57d) | Mar 09, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [9c59079b1f](https://linux-hardware.org/?probe=9c59079b1f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4e1196658a](https://linux-hardware.org/?probe=4e1196658a) | Mar 09, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [07f4220473](https://linux-hardware.org/?probe=07f4220473) | Mar 09, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [bdfaf09cd0](https://linux-hardware.org/?probe=bdfaf09cd0) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [3e32daea8a](https://linux-hardware.org/?probe=3e32daea8a) | Mar 09, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [6328a68180](https://linux-hardware.org/?probe=6328a68180) | Mar 09, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [24444c6d30](https://linux-hardware.org/?probe=24444c6d30) | Mar 08, 2023 |
| Lenovo        | IdeaPad S540-15IML D 81N... | Notebook    | [31e144de96](https://linux-hardware.org/?probe=31e144de96) | Mar 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [79f2717461](https://linux-hardware.org/?probe=79f2717461) | Mar 08, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [face0290e3](https://linux-hardware.org/?probe=face0290e3) | Mar 08, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [3087a03cb5](https://linux-hardware.org/?probe=3087a03cb5) | Mar 08, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [3089c37fd4](https://linux-hardware.org/?probe=3089c37fd4) | Mar 08, 2023 |
| Intel         | Raptor Lake Client Platf... | Notebook    | [f52d925104](https://linux-hardware.org/?probe=f52d925104) | Mar 08, 2023 |
| Dell          | Latitude 5400               | Notebook    | [3d2504745e](https://linux-hardware.org/?probe=3d2504745e) | Mar 08, 2023 |
| Dell          | G15 5515                    | Notebook    | [fc1b55ddc1](https://linux-hardware.org/?probe=fc1b55ddc1) | Mar 07, 2023 |
| HP            | Laptop 15s-dr1xxx           | Notebook    | [be222c3e23](https://linux-hardware.org/?probe=be222c3e23) | Mar 07, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [ff582d0370](https://linux-hardware.org/?probe=ff582d0370) | Mar 07, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [16d683966c](https://linux-hardware.org/?probe=16d683966c) | Mar 07, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [d00485842a](https://linux-hardware.org/?probe=d00485842a) | Mar 06, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [a7a9f81898](https://linux-hardware.org/?probe=a7a9f81898) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [896ab1f527](https://linux-hardware.org/?probe=896ab1f527) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [0328fa718e](https://linux-hardware.org/?probe=0328fa718e) | Mar 06, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [75dab4cddf](https://linux-hardware.org/?probe=75dab4cddf) | Mar 06, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [b75483941a](https://linux-hardware.org/?probe=b75483941a) | Mar 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [c4e5e8923c](https://linux-hardware.org/?probe=c4e5e8923c) | Mar 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [657175938b](https://linux-hardware.org/?probe=657175938b) | Mar 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [2a93373173](https://linux-hardware.org/?probe=2a93373173) | Mar 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5871fdcf26](https://linux-hardware.org/?probe=5871fdcf26) | Mar 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [50a27abb52](https://linux-hardware.org/?probe=50a27abb52) | Mar 04, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5a15c4c2b0](https://linux-hardware.org/?probe=5a15c4c2b0) | Mar 03, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [20dc6b7a10](https://linux-hardware.org/?probe=20dc6b7a10) | Mar 03, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [aefdf1040c](https://linux-hardware.org/?probe=aefdf1040c) | Mar 03, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [1a24f06457](https://linux-hardware.org/?probe=1a24f06457) | Mar 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [5823762138](https://linux-hardware.org/?probe=5823762138) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| Acer          | H110D4-M1                   | Desktop     | [65210fefa2](https://linux-hardware.org/?probe=65210fefa2) | Mar 03, 2023 |
| Lenovo        | ThinkPad W530 2447C83       | Notebook    | [c5f046d2fb](https://linux-hardware.org/?probe=c5f046d2fb) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [edf5f00bf8](https://linux-hardware.org/?probe=edf5f00bf8) | Mar 01, 2023 |
| HP            | 834F                        | Desktop     | [96631603b3](https://linux-hardware.org/?probe=96631603b3) | Mar 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [23d5a9e0a8](https://linux-hardware.org/?probe=23d5a9e0a8) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [94809b7bc2](https://linux-hardware.org/?probe=94809b7bc2) | Mar 01, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [e9b7ee04ec](https://linux-hardware.org/?probe=e9b7ee04ec) | Mar 01, 2023 |
| Getac         | B360                        | Notebook    | [c4bd09adf1](https://linux-hardware.org/?probe=c4bd09adf1) | Mar 01, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [ecdef0f6db](https://linux-hardware.org/?probe=ecdef0f6db) | Mar 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [e1733fa8c9](https://linux-hardware.org/?probe=e1733fa8c9) | Mar 01, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [166a6bbb4b](https://linux-hardware.org/?probe=166a6bbb4b) | Feb 28, 2023 |
| Lenovo        | 3102 NOK                    | Desktop     | [17a2e663e1](https://linux-hardware.org/?probe=17a2e663e1) | Feb 28, 2023 |
| Lenovo        | 3102 NOK                    | Desktop     | [6dabaffa28](https://linux-hardware.org/?probe=6dabaffa28) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [672684e416](https://linux-hardware.org/?probe=672684e416) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [edf2240a74](https://linux-hardware.org/?probe=edf2240a74) | Feb 28, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [5a6d88e081](https://linux-hardware.org/?probe=5a6d88e081) | Feb 28, 2023 |
| Lenovo        | ThinkPad T460s 20FAS55Q1... | Notebook    | [815b6ea9f2](https://linux-hardware.org/?probe=815b6ea9f2) | Feb 27, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | Desktop     | [686c8d56c4](https://linux-hardware.org/?probe=686c8d56c4) | Feb 27, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [4c96506f38](https://linux-hardware.org/?probe=4c96506f38) | Feb 27, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | Notebook    | [82a40f1881](https://linux-hardware.org/?probe=82a40f1881) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [fe8735a027](https://linux-hardware.org/?probe=fe8735a027) | Feb 26, 2023 |
| Dell          | Vostro 3578                 | Notebook    | [da6968c8ac](https://linux-hardware.org/?probe=da6968c8ac) | Feb 26, 2023 |
| Gigabyte      | H510M S2                    | Desktop     | [24ea8468ca](https://linux-hardware.org/?probe=24ea8468ca) | Feb 26, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [1c93095718](https://linux-hardware.org/?probe=1c93095718) | Feb 26, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [b410d220e6](https://linux-hardware.org/?probe=b410d220e6) | Feb 26, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b05fb1c01b](https://linux-hardware.org/?probe=b05fb1c01b) | Feb 26, 2023 |
| HP            | Victus by 16 Laptop PC      | Notebook    | [05ef574a7c](https://linux-hardware.org/?probe=05ef574a7c) | Feb 25, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [27fa5a62b6](https://linux-hardware.org/?probe=27fa5a62b6) | Feb 24, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [99b5c2f7f9](https://linux-hardware.org/?probe=99b5c2f7f9) | Feb 24, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [0bb7bc3713](https://linux-hardware.org/?probe=0bb7bc3713) | Feb 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [64504d9860](https://linux-hardware.org/?probe=64504d9860) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [787270bc9e](https://linux-hardware.org/?probe=787270bc9e) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [759b3114be](https://linux-hardware.org/?probe=759b3114be) | Feb 24, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [f4e2bfd7a0](https://linux-hardware.org/?probe=f4e2bfd7a0) | Feb 24, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [e0fcd4e578](https://linux-hardware.org/?probe=e0fcd4e578) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f7063f868f](https://linux-hardware.org/?probe=f7063f868f) | Feb 24, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [7686bcd76d](https://linux-hardware.org/?probe=7686bcd76d) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [93dfbdd8cd](https://linux-hardware.org/?probe=93dfbdd8cd) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05C 82AU      | Notebook    | [a5a58a8dc4](https://linux-hardware.org/?probe=a5a58a8dc4) | Feb 23, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [ead0af8ae4](https://linux-hardware.org/?probe=ead0af8ae4) | Feb 23, 2023 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [523ab73c43](https://linux-hardware.org/?probe=523ab73c43) | Feb 23, 2023 |
| Dell          | Vostro 3446                 | Notebook    | [c6df0f1b65](https://linux-hardware.org/?probe=c6df0f1b65) | Feb 23, 2023 |
| Dell          | Studio 1450                 | Notebook    | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [a39eba7e6a](https://linux-hardware.org/?probe=a39eba7e6a) | Feb 22, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d196877f8d](https://linux-hardware.org/?probe=d196877f8d) | Feb 22, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [9485c15a78](https://linux-hardware.org/?probe=9485c15a78) | Feb 22, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [b517bb25cc](https://linux-hardware.org/?probe=b517bb25cc) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d09dc2494a](https://linux-hardware.org/?probe=d09dc2494a) | Feb 21, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [73f07e0ebf](https://linux-hardware.org/?probe=73f07e0ebf) | Feb 21, 2023 |
| HP            | Stream 8 Tablet             | Tablet      | [211438a893](https://linux-hardware.org/?probe=211438a893) | Feb 20, 2023 |
| Dell          | Vostro 3491                 | Notebook    | [d557c581cf](https://linux-hardware.org/?probe=d557c581cf) | Feb 20, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0c7a3d458a](https://linux-hardware.org/?probe=0c7a3d458a) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [c3f49d4cee](https://linux-hardware.org/?probe=c3f49d4cee) | Feb 20, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [d495b4eb1e](https://linux-hardware.org/?probe=d495b4eb1e) | Feb 20, 2023 |
| HP            | Laptop 15s-dr0xxx           | Notebook    | [6733a448f9](https://linux-hardware.org/?probe=6733a448f9) | Feb 20, 2023 |
| HP            | Pavilion 15                 | Notebook    | [7c652212fb](https://linux-hardware.org/?probe=7c652212fb) | Feb 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [cecc8c4a23](https://linux-hardware.org/?probe=cecc8c4a23) | Feb 19, 2023 |
| Acer          | G43T-AM3                    | Desktop     | [5ec1aa8af7](https://linux-hardware.org/?probe=5ec1aa8af7) | Feb 19, 2023 |
| Dell          | Precision 3510              | Notebook    | [b20156e847](https://linux-hardware.org/?probe=b20156e847) | Feb 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [affa3bb9f1](https://linux-hardware.org/?probe=affa3bb9f1) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [7e5327c1ed](https://linux-hardware.org/?probe=7e5327c1ed) | Feb 19, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [f6372e6b96](https://linux-hardware.org/?probe=f6372e6b96) | Feb 19, 2023 |
| HP            | ProBook 445 G1              | Notebook    | [bcd5c952f1](https://linux-hardware.org/?probe=bcd5c952f1) | Feb 18, 2023 |
| HP            | Unknown                     | Notebook    | [3fea6a053b](https://linux-hardware.org/?probe=3fea6a053b) | Feb 18, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [7daf230ef2](https://linux-hardware.org/?probe=7daf230ef2) | Feb 18, 2023 |
| HP            | 15                          | Notebook    | [4db2520843](https://linux-hardware.org/?probe=4db2520843) | Feb 18, 2023 |
| Dell          | G7 7588                     | Notebook    | [caf1cd6176](https://linux-hardware.org/?probe=caf1cd6176) | Feb 18, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [be751c4a5b](https://linux-hardware.org/?probe=be751c4a5b) | Feb 18, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [7890bf1c68](https://linux-hardware.org/?probe=7890bf1c68) | Feb 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e67f600749](https://linux-hardware.org/?probe=e67f600749) | Feb 16, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [32794e5a2e](https://linux-hardware.org/?probe=32794e5a2e) | Feb 16, 2023 |
| Dell          | Latitude 7490               | Notebook    | [796443d889](https://linux-hardware.org/?probe=796443d889) | Feb 16, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [7b90c0a5cc](https://linux-hardware.org/?probe=7b90c0a5cc) | Feb 15, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [0488cd4f01](https://linux-hardware.org/?probe=0488cd4f01) | Feb 15, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [561e1a6160](https://linux-hardware.org/?probe=561e1a6160) | Feb 14, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [0206821577](https://linux-hardware.org/?probe=0206821577) | Feb 14, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [fcbd0e4770](https://linux-hardware.org/?probe=fcbd0e4770) | Feb 14, 2023 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [beaef7f0ab](https://linux-hardware.org/?probe=beaef7f0ab) | Feb 14, 2023 |
| HP            | Pavilion 15                 | Notebook    | [7f54c595f1](https://linux-hardware.org/?probe=7f54c595f1) | Feb 14, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [4750f3ad3a](https://linux-hardware.org/?probe=4750f3ad3a) | Feb 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [31593ae5b9](https://linux-hardware.org/?probe=31593ae5b9) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | Notebook    | [a6af7624cd](https://linux-hardware.org/?probe=a6af7624cd) | Feb 13, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [debdb17904](https://linux-hardware.org/?probe=debdb17904) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [566c6a5316](https://linux-hardware.org/?probe=566c6a5316) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [a833fa9a0c](https://linux-hardware.org/?probe=a833fa9a0c) | Feb 12, 2023 |
| HP            | Notebook                    | Notebook    | [a17adfd867](https://linux-hardware.org/?probe=a17adfd867) | Feb 12, 2023 |
| HP            | 430                         | Notebook    | [9350af0a6b](https://linux-hardware.org/?probe=9350af0a6b) | Feb 12, 2023 |
| Dell          | Vostro 3446                 | Notebook    | [e3784684f4](https://linux-hardware.org/?probe=e3784684f4) | Feb 11, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [321710ca2d](https://linux-hardware.org/?probe=321710ca2d) | Feb 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | Notebook    | [5f2fb779b4](https://linux-hardware.org/?probe=5f2fb779b4) | Feb 11, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [4403212f84](https://linux-hardware.org/?probe=4403212f84) | Feb 11, 2023 |
| ASUSTek       | K52F                        | Notebook    | [6820e56394](https://linux-hardware.org/?probe=6820e56394) | Feb 11, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [92b7a6f08d](https://linux-hardware.org/?probe=92b7a6f08d) | Feb 11, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [687573b718](https://linux-hardware.org/?probe=687573b718) | Feb 10, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [34e8df3dea](https://linux-hardware.org/?probe=34e8df3dea) | Feb 10, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [043eef223c](https://linux-hardware.org/?probe=043eef223c) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [482b3ea2be](https://linux-hardware.org/?probe=482b3ea2be) | Feb 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [8e014440da](https://linux-hardware.org/?probe=8e014440da) | Feb 10, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [c4ba4f3bc6](https://linux-hardware.org/?probe=c4ba4f3bc6) | Feb 10, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [812df42bc4](https://linux-hardware.org/?probe=812df42bc4) | Feb 10, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | Notebook    | [fc292cd441](https://linux-hardware.org/?probe=fc292cd441) | Feb 09, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [69949c02d9](https://linux-hardware.org/?probe=69949c02d9) | Feb 09, 2023 |
| Dell          | Latitude 5410               | Notebook    | [08ab3250ae](https://linux-hardware.org/?probe=08ab3250ae) | Feb 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [ce71e8ab61](https://linux-hardware.org/?probe=ce71e8ab61) | Feb 08, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [722d0ce3be](https://linux-hardware.org/?probe=722d0ce3be) | Feb 07, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [fa97fe509b](https://linux-hardware.org/?probe=fa97fe509b) | Feb 07, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [b84a916a22](https://linux-hardware.org/?probe=b84a916a22) | Feb 07, 2023 |
| HP            | ENVY Notebook PC            | Convertible | [a8165997b7](https://linux-hardware.org/?probe=a8165997b7) | Feb 06, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [3e487446eb](https://linux-hardware.org/?probe=3e487446eb) | Feb 06, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [1f2418bafb](https://linux-hardware.org/?probe=1f2418bafb) | Feb 06, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [31e2c2f5e1](https://linux-hardware.org/?probe=31e2c2f5e1) | Feb 06, 2023 |
| Dell          | Latitude 7480               | Notebook    | [850e6ed168](https://linux-hardware.org/?probe=850e6ed168) | Feb 06, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [1ce10af418](https://linux-hardware.org/?probe=1ce10af418) | Feb 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d95f28d447](https://linux-hardware.org/?probe=d95f28d447) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [400b29056d](https://linux-hardware.org/?probe=400b29056d) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [de72d92ada](https://linux-hardware.org/?probe=de72d92ada) | Feb 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b8ecfb712c](https://linux-hardware.org/?probe=b8ecfb712c) | Feb 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [aa51c3690f](https://linux-hardware.org/?probe=aa51c3690f) | Feb 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [00ebdfe948](https://linux-hardware.org/?probe=00ebdfe948) | Feb 04, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c12f38950f](https://linux-hardware.org/?probe=c12f38950f) | Feb 04, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [8fd252af27](https://linux-hardware.org/?probe=8fd252af27) | Feb 04, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [e08416e7a9](https://linux-hardware.org/?probe=e08416e7a9) | Feb 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [b3eac5c97d](https://linux-hardware.org/?probe=b3eac5c97d) | Feb 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a5508059a1](https://linux-hardware.org/?probe=a5508059a1) | Feb 04, 2023 |
| Unknown       | G41 Series                  | Desktop     | [69d4cb64a2](https://linux-hardware.org/?probe=69d4cb64a2) | Feb 03, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [5bfa4ad142](https://linux-hardware.org/?probe=5bfa4ad142) | Feb 02, 2023 |
| MSI           | GE63 Raider RGB 9SE         | Notebook    | [b7ec016843](https://linux-hardware.org/?probe=b7ec016843) | Feb 02, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| Dell          | Inspiron 3584               | Notebook    | [4bfcbe7c13](https://linux-hardware.org/?probe=4bfcbe7c13) | Feb 02, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [09d76d7d2a](https://linux-hardware.org/?probe=09d76d7d2a) | Feb 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [2cb0ec3b98](https://linux-hardware.org/?probe=2cb0ec3b98) | Feb 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [22abfb4a79](https://linux-hardware.org/?probe=22abfb4a79) | Feb 01, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | Notebook    | [8360c9e13f](https://linux-hardware.org/?probe=8360c9e13f) | Feb 01, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [d897ec0114](https://linux-hardware.org/?probe=d897ec0114) | Feb 01, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [07b498f669](https://linux-hardware.org/?probe=07b498f669) | Feb 01, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e3adac798e](https://linux-hardware.org/?probe=e3adac798e) | Jan 30, 2023 |
| HP            | 15                          | Notebook    | [409a15bdf3](https://linux-hardware.org/?probe=409a15bdf3) | Jan 30, 2023 |
| ASUSTek       | X507UA                      | Notebook    | [49cc52b5b2](https://linux-hardware.org/?probe=49cc52b5b2) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [47438e081a](https://linux-hardware.org/?probe=47438e081a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [4b8206c892](https://linux-hardware.org/?probe=4b8206c892) | Jan 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c5ac9f6d89](https://linux-hardware.org/?probe=c5ac9f6d89) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [621aca8707](https://linux-hardware.org/?probe=621aca8707) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [55fe252b4e](https://linux-hardware.org/?probe=55fe252b4e) | Jan 29, 2023 |
| Lenovo        | ThinkPad X61 7674BE1        | Notebook    | [a22ac0a9f5](https://linux-hardware.org/?probe=a22ac0a9f5) | Jan 28, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [f5492fbdaa](https://linux-hardware.org/?probe=f5492fbdaa) | Jan 27, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [33905a4ee9](https://linux-hardware.org/?probe=33905a4ee9) | Jan 26, 2023 |
| Dell          | Latitude 7480               | Notebook    | [3cb61c5b71](https://linux-hardware.org/?probe=3cb61c5b71) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e3ac708616](https://linux-hardware.org/?probe=e3ac708616) | Jan 26, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [a95489f0b7](https://linux-hardware.org/?probe=a95489f0b7) | Jan 24, 2023 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [edbaabb13a](https://linux-hardware.org/?probe=edbaabb13a) | Jan 24, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [32a1eb6d60](https://linux-hardware.org/?probe=32a1eb6d60) | Jan 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [07005e3e32](https://linux-hardware.org/?probe=07005e3e32) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [348a78bb64](https://linux-hardware.org/?probe=348a78bb64) | Jan 22, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [b4419e8fce](https://linux-hardware.org/?probe=b4419e8fce) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [c6a463e92f](https://linux-hardware.org/?probe=c6a463e92f) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a09d1d224c](https://linux-hardware.org/?probe=a09d1d224c) | Jan 22, 2023 |
| HP            | 2B00 A01                    | Desktop     | [467ef856dd](https://linux-hardware.org/?probe=467ef856dd) | Jan 21, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [441e45daa2](https://linux-hardware.org/?probe=441e45daa2) | Jan 21, 2023 |
| Timi          | Mi Notebook Pro             | Notebook    | [1db1382f0b](https://linux-hardware.org/?probe=1db1382f0b) | Jan 21, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [329f1d0701](https://linux-hardware.org/?probe=329f1d0701) | Jan 21, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | Desktop     | [36e6df452d](https://linux-hardware.org/?probe=36e6df452d) | Jan 21, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ce99cb312d](https://linux-hardware.org/?probe=ce99cb312d) | Jan 20, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [9a17165647](https://linux-hardware.org/?probe=9a17165647) | Jan 20, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [e1003a85c9](https://linux-hardware.org/?probe=e1003a85c9) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6b1a8f8d9d](https://linux-hardware.org/?probe=6b1a8f8d9d) | Jan 20, 2023 |
| HP            | 85A2                        | All in one  | [13fcd2dd69](https://linux-hardware.org/?probe=13fcd2dd69) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [0f079e1dc7](https://linux-hardware.org/?probe=0f079e1dc7) | Jan 19, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [90049e4bb7](https://linux-hardware.org/?probe=90049e4bb7) | Jan 19, 2023 |
| Dell          | Latitude E6510              | Notebook    | [4b10c4532e](https://linux-hardware.org/?probe=4b10c4532e) | Jan 19, 2023 |
| Dell          | Latitude E6510              | Notebook    | [6b8112e4c1](https://linux-hardware.org/?probe=6b8112e4c1) | Jan 19, 2023 |
| Lenovo        | ThinkPad X200 7459VB9       | Notebook    | [a58c604cf7](https://linux-hardware.org/?probe=a58c604cf7) | Jan 18, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [04fe55a1a1](https://linux-hardware.org/?probe=04fe55a1a1) | Jan 18, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [533d99e2f1](https://linux-hardware.org/?probe=533d99e2f1) | Jan 18, 2023 |
| HP            | 15                          | Notebook    | [cebe1b150e](https://linux-hardware.org/?probe=cebe1b150e) | Jan 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [f050195c33](https://linux-hardware.org/?probe=f050195c33) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [681de2b0c1](https://linux-hardware.org/?probe=681de2b0c1) | Jan 17, 2023 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [592a29d649](https://linux-hardware.org/?probe=592a29d649) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [f1ee502754](https://linux-hardware.org/?probe=f1ee502754) | Jan 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0d91852ebf](https://linux-hardware.org/?probe=0d91852ebf) | Jan 17, 2023 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [9c5bf0d05c](https://linux-hardware.org/?probe=9c5bf0d05c) | Jan 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1a51848ffb](https://linux-hardware.org/?probe=1a51848ffb) | Jan 16, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [1b195c04d8](https://linux-hardware.org/?probe=1b195c04d8) | Jan 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X600    | Notebook    | [2c2e9caacc](https://linux-hardware.org/?probe=2c2e9caacc) | Jan 16, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9cdfb3119e](https://linux-hardware.org/?probe=9cdfb3119e) | Jan 15, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [30917eef19](https://linux-hardware.org/?probe=30917eef19) | Jan 15, 2023 |
| Lenovo        | ThinkPad T440p 20AN00DJA... | Notebook    | [250aa5a61b](https://linux-hardware.org/?probe=250aa5a61b) | Jan 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fba7cebfff](https://linux-hardware.org/?probe=fba7cebfff) | Jan 14, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [ffb8653d34](https://linux-hardware.org/?probe=ffb8653d34) | Jan 14, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [0ac9fa6100](https://linux-hardware.org/?probe=0ac9fa6100) | Jan 14, 2023 |
| Lenovo        | ThinkPad W540 20BHS1840P    | Notebook    | [0046521475](https://linux-hardware.org/?probe=0046521475) | Jan 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [bff6278ed8](https://linux-hardware.org/?probe=bff6278ed8) | Jan 14, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [10a9c33aed](https://linux-hardware.org/?probe=10a9c33aed) | Jan 13, 2023 |
| Gigabyte      | 970A-DS3                    | Desktop     | [c6819f38a0](https://linux-hardware.org/?probe=c6819f38a0) | Jan 13, 2023 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [3ba9f40d9b](https://linux-hardware.org/?probe=3ba9f40d9b) | Jan 13, 2023 |
| Gigabyte      | H81M-S                      | Desktop     | [77fc83eb85](https://linux-hardware.org/?probe=77fc83eb85) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| HP            | 245 G7 Notebook PC          | Notebook    | [3997d98a9a](https://linux-hardware.org/?probe=3997d98a9a) | Jan 11, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [6c67fc3995](https://linux-hardware.org/?probe=6c67fc3995) | Jan 11, 2023 |
| Acer          | TravelMate P245-M           | Notebook    | [1722e41c8d](https://linux-hardware.org/?probe=1722e41c8d) | Jan 11, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [4e7660a1e0](https://linux-hardware.org/?probe=4e7660a1e0) | Jan 10, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [a786384700](https://linux-hardware.org/?probe=a786384700) | Jan 10, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [8367c27d81](https://linux-hardware.org/?probe=8367c27d81) | Jan 10, 2023 |
| ITI LIMITE... | ITI SMAASH ITIB11LCE        | Convertible | [a01c6e0730](https://linux-hardware.org/?probe=a01c6e0730) | Jan 10, 2023 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [805265229e](https://linux-hardware.org/?probe=805265229e) | Jan 10, 2023 |
| ASUSTek       | K53SM                       | Notebook    | [f1ac679157](https://linux-hardware.org/?probe=f1ac679157) | Jan 10, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [7ac5117a93](https://linux-hardware.org/?probe=7ac5117a93) | Jan 09, 2023 |
| Acer          | H110D4-M1                   | Desktop     | [c652bb7179](https://linux-hardware.org/?probe=c652bb7179) | Jan 09, 2023 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | Notebook    | [debe9fa9d2](https://linux-hardware.org/?probe=debe9fa9d2) | Jan 08, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d759bb7551](https://linux-hardware.org/?probe=d759bb7551) | Jan 08, 2023 |
| Lenovo        | ThinkPad T430 2349E56       | Notebook    | [ff2639c47b](https://linux-hardware.org/?probe=ff2639c47b) | Jan 07, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [e8f5b2590f](https://linux-hardware.org/?probe=e8f5b2590f) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [f191d63ace](https://linux-hardware.org/?probe=f191d63ace) | Jan 07, 2023 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [a6b7ce48a7](https://linux-hardware.org/?probe=a6b7ce48a7) | Jan 07, 2023 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [a3cc92ede0](https://linux-hardware.org/?probe=a3cc92ede0) | Jan 07, 2023 |
| MSI           | GF63 8RD                    | Notebook    | [d9fc4d53c9](https://linux-hardware.org/?probe=d9fc4d53c9) | Jan 07, 2023 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [702bf83225](https://linux-hardware.org/?probe=702bf83225) | Jan 06, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [2dd2c1c022](https://linux-hardware.org/?probe=2dd2c1c022) | Jan 06, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [f3d1187b29](https://linux-hardware.org/?probe=f3d1187b29) | Jan 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fd5120fea6](https://linux-hardware.org/?probe=fd5120fea6) | Jan 06, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [762142dfbb](https://linux-hardware.org/?probe=762142dfbb) | Jan 06, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [00212160f7](https://linux-hardware.org/?probe=00212160f7) | Jan 05, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [482205e492](https://linux-hardware.org/?probe=482205e492) | Jan 05, 2023 |
| HP            | Notebook                    | Notebook    | [611e618b60](https://linux-hardware.org/?probe=611e618b60) | Jan 03, 2023 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [29970ac3f3](https://linux-hardware.org/?probe=29970ac3f3) | Jan 03, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [4a37b87ecf](https://linux-hardware.org/?probe=4a37b87ecf) | Jan 02, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [8706565860](https://linux-hardware.org/?probe=8706565860) | Jan 02, 2023 |
| Lenovo        | ThinkPad E490 20N8S0H300    | Notebook    | [fb3233e525](https://linux-hardware.org/?probe=fb3233e525) | Jan 02, 2023 |
| ITI LIMITE... | ITI Smaash ITIB15LI3        | Notebook    | [6e271cd1c3](https://linux-hardware.org/?probe=6e271cd1c3) | Jan 02, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| HP            | Laptop HP Laptop 14s-dr1... | Notebook    | [2a27236865](https://linux-hardware.org/?probe=2a27236865) | Jan 01, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d25dd69250](https://linux-hardware.org/?probe=d25dd69250) | Jan 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [60b4a8e506](https://linux-hardware.org/?probe=60b4a8e506) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b1dc879a16](https://linux-hardware.org/?probe=b1dc879a16) | Jan 01, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [5d0ff5ea2d](https://linux-hardware.org/?probe=5d0ff5ea2d) | Dec 31, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d2cd50a2a6](https://linux-hardware.org/?probe=d2cd50a2a6) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [ae7d821823](https://linux-hardware.org/?probe=ae7d821823) | Dec 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7be9115c85](https://linux-hardware.org/?probe=7be9115c85) | Dec 30, 2022 |
| Intel         | H61                         | Desktop     | [b294748570](https://linux-hardware.org/?probe=b294748570) | Dec 30, 2022 |
| ITI LIMITE... | ITI Smaash ITIB15LI3        | Notebook    | [6a08f378e2](https://linux-hardware.org/?probe=6a08f378e2) | Dec 30, 2022 |
| ITI LIMITE... | ITI Smaash ITIB15LI3        | Notebook    | [282a44d1ff](https://linux-hardware.org/?probe=282a44d1ff) | Dec 30, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [3a7cfd8073](https://linux-hardware.org/?probe=3a7cfd8073) | Dec 30, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [9aba0ac647](https://linux-hardware.org/?probe=9aba0ac647) | Dec 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [30e1303337](https://linux-hardware.org/?probe=30e1303337) | Dec 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | Notebook    | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | Notebook    | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ce45aaceaf](https://linux-hardware.org/?probe=ce45aaceaf) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [264e3738ec](https://linux-hardware.org/?probe=264e3738ec) | Dec 29, 2022 |
| Intel         | H61                         | Desktop     | [39f3cddffb](https://linux-hardware.org/?probe=39f3cddffb) | Dec 29, 2022 |
| Dell          | Latitude 3420               | Notebook    | [eb6d4c6921](https://linux-hardware.org/?probe=eb6d4c6921) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [d5be261567](https://linux-hardware.org/?probe=d5be261567) | Dec 29, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [0382c36a9d](https://linux-hardware.org/?probe=0382c36a9d) | Dec 28, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [a42da327a2](https://linux-hardware.org/?probe=a42da327a2) | Dec 28, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [c25b644aca](https://linux-hardware.org/?probe=c25b644aca) | Dec 28, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [5054f77353](https://linux-hardware.org/?probe=5054f77353) | Dec 27, 2022 |
| Timi          | RedmiBook 15                | Notebook    | [cf38b14bc5](https://linux-hardware.org/?probe=cf38b14bc5) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c8b85cb0cd](https://linux-hardware.org/?probe=c8b85cb0cd) | Dec 26, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [812d6eb07e](https://linux-hardware.org/?probe=812d6eb07e) | Dec 26, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [69ac8a9522](https://linux-hardware.org/?probe=69ac8a9522) | Dec 26, 2022 |
| Dell          | Latitude E6400              | Notebook    | [435ac90ddc](https://linux-hardware.org/?probe=435ac90ddc) | Dec 26, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [40ac0f9ffc](https://linux-hardware.org/?probe=40ac0f9ffc) | Dec 25, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [576fb3852f](https://linux-hardware.org/?probe=576fb3852f) | Dec 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [2bd2de39fb](https://linux-hardware.org/?probe=2bd2de39fb) | Dec 24, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [05ab61864f](https://linux-hardware.org/?probe=05ab61864f) | Dec 23, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [53aa474cf5](https://linux-hardware.org/?probe=53aa474cf5) | Dec 23, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [19909aa86b](https://linux-hardware.org/?probe=19909aa86b) | Dec 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [0256ea50a4](https://linux-hardware.org/?probe=0256ea50a4) | Dec 23, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [a208b5598e](https://linux-hardware.org/?probe=a208b5598e) | Dec 22, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [cccd3d01d7](https://linux-hardware.org/?probe=cccd3d01d7) | Dec 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b221e3103a](https://linux-hardware.org/?probe=b221e3103a) | Dec 22, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [505ab3f60a](https://linux-hardware.org/?probe=505ab3f60a) | Dec 22, 2022 |
| Acer          | Gateway NE46Rs1             | Notebook    | [45a25a89d7](https://linux-hardware.org/?probe=45a25a89d7) | Dec 21, 2022 |
| MSI           | GL65 Leopard 10SDK          | Notebook    | [2c6e6ec3ec](https://linux-hardware.org/?probe=2c6e6ec3ec) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [9438c80c85](https://linux-hardware.org/?probe=9438c80c85) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7d5914dcb2](https://linux-hardware.org/?probe=7d5914dcb2) | Dec 21, 2022 |
| Timi          | Mi NoteBook Pro             | Notebook    | [b5bbb4f410](https://linux-hardware.org/?probe=b5bbb4f410) | Dec 21, 2022 |
| HP            | ZBook 15                    | Notebook    | [a3bf671d64](https://linux-hardware.org/?probe=a3bf671d64) | Dec 20, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [005d388376](https://linux-hardware.org/?probe=005d388376) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | Notebook    | [93eff781da](https://linux-hardware.org/?probe=93eff781da) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | Notebook    | [0b7352a343](https://linux-hardware.org/?probe=0b7352a343) | Dec 20, 2022 |
| Dell          | Inspiron 7572               | Notebook    | [418178c3ca](https://linux-hardware.org/?probe=418178c3ca) | Dec 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [c67b4d2b31](https://linux-hardware.org/?probe=c67b4d2b31) | Dec 19, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [a2bee3bb3f](https://linux-hardware.org/?probe=a2bee3bb3f) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [08e38b2be9](https://linux-hardware.org/?probe=08e38b2be9) | Dec 18, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [eaf1b6a773](https://linux-hardware.org/?probe=eaf1b6a773) | Dec 17, 2022 |
| HP            | 245 G3                      | Notebook    | [ceee8f33ca](https://linux-hardware.org/?probe=ceee8f33ca) | Dec 17, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [b0f674ae6f](https://linux-hardware.org/?probe=b0f674ae6f) | Dec 17, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [acca7c4697](https://linux-hardware.org/?probe=acca7c4697) | Dec 17, 2022 |
| HP            | 250 G1                      | Notebook    | [07f20cc1ec](https://linux-hardware.org/?probe=07f20cc1ec) | Dec 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [f6e6cfc7b3](https://linux-hardware.org/?probe=f6e6cfc7b3) | Dec 17, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [3b5142322b](https://linux-hardware.org/?probe=3b5142322b) | Dec 16, 2022 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [bf511c3913](https://linux-hardware.org/?probe=bf511c3913) | Dec 16, 2022 |
| HP            | Laptop 15q-bu0xx            | Notebook    | [d291ab8cf8](https://linux-hardware.org/?probe=d291ab8cf8) | Dec 16, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [f54a021496](https://linux-hardware.org/?probe=f54a021496) | Dec 16, 2022 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [3a524796f6](https://linux-hardware.org/?probe=3a524796f6) | Dec 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | Notebook    | [7aab463e8e](https://linux-hardware.org/?probe=7aab463e8e) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7ea1bad26b](https://linux-hardware.org/?probe=7ea1bad26b) | Dec 15, 2022 |
| Dell          | Latitude 3420               | Notebook    | [a6c668f4a2](https://linux-hardware.org/?probe=a6c668f4a2) | Dec 15, 2022 |
| Acer          | Veriton Series              | Desktop     | [1bd09d0c08](https://linux-hardware.org/?probe=1bd09d0c08) | Dec 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | Notebook    | [484c320457](https://linux-hardware.org/?probe=484c320457) | Dec 14, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [70992b154e](https://linux-hardware.org/?probe=70992b154e) | Dec 14, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [9a958b68ec](https://linux-hardware.org/?probe=9a958b68ec) | Dec 14, 2022 |
| Intel         | NUC7JYB J67967-405          | Mini pc     | [9fac25564e](https://linux-hardware.org/?probe=9fac25564e) | Dec 12, 2022 |
| Lenovo        | 3140 NO DPK                 | Desktop     | [4a114b9cc1](https://linux-hardware.org/?probe=4a114b9cc1) | Dec 12, 2022 |
| Lenovo        | 3140 NO DPK                 | Desktop     | [d4abe79f4f](https://linux-hardware.org/?probe=d4abe79f4f) | Dec 12, 2022 |
| Dell          | 0MGK50 A01                  | Desktop     | [439311be3e](https://linux-hardware.org/?probe=439311be3e) | Dec 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | Notebook    | [7ffd00681b](https://linux-hardware.org/?probe=7ffd00681b) | Dec 12, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [811092647b](https://linux-hardware.org/?probe=811092647b) | Dec 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [964081eed7](https://linux-hardware.org/?probe=964081eed7) | Dec 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [bde36454f9](https://linux-hardware.org/?probe=bde36454f9) | Dec 11, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [400a0b555d](https://linux-hardware.org/?probe=400a0b555d) | Dec 10, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [36af891d5d](https://linux-hardware.org/?probe=36af891d5d) | Dec 10, 2022 |
| Lenovo        | IdeaPadS540 81NE            | Notebook    | [3e5b528d0f](https://linux-hardware.org/?probe=3e5b528d0f) | Dec 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [d737aa3978](https://linux-hardware.org/?probe=d737aa3978) | Dec 09, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [c291bac936](https://linux-hardware.org/?probe=c291bac936) | Dec 09, 2022 |
| Dynabook      | Satellite Pro C40-H Y030... | Notebook    | [a804b63bcd](https://linux-hardware.org/?probe=a804b63bcd) | Dec 09, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [30cc472125](https://linux-hardware.org/?probe=30cc472125) | Dec 08, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [9d46a5fb80](https://linux-hardware.org/?probe=9d46a5fb80) | Dec 08, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [e04f421926](https://linux-hardware.org/?probe=e04f421926) | Dec 08, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [383bc11a0d](https://linux-hardware.org/?probe=383bc11a0d) | Dec 07, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8442e3381c](https://linux-hardware.org/?probe=8442e3381c) | Dec 06, 2022 |
| Dynabook      | Satellite Pro C40-H Y030... | Notebook    | [3167658218](https://linux-hardware.org/?probe=3167658218) | Dec 06, 2022 |
| Dell          | Inspiron 5482               | Convertible | [1acc329a88](https://linux-hardware.org/?probe=1acc329a88) | Dec 06, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | Notebook    | [4dc49eeb10](https://linux-hardware.org/?probe=4dc49eeb10) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP47... | Convertible | [269fc93641](https://linux-hardware.org/?probe=269fc93641) | Dec 06, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [53689d832d](https://linux-hardware.org/?probe=53689d832d) | Dec 06, 2022 |
| Dell          | Latitude E5430 vPro         | Notebook    | [9ccc3c8d05](https://linux-hardware.org/?probe=9ccc3c8d05) | Dec 06, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [9af2847ac7](https://linux-hardware.org/?probe=9af2847ac7) | Dec 06, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [496bcc21ca](https://linux-hardware.org/?probe=496bcc21ca) | Dec 05, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [3a74cfee45](https://linux-hardware.org/?probe=3a74cfee45) | Dec 05, 2022 |
| HP            | 430                         | Notebook    | [3c0de30201](https://linux-hardware.org/?probe=3c0de30201) | Dec 04, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [16f43f11a1](https://linux-hardware.org/?probe=16f43f11a1) | Dec 04, 2022 |
| ASUSTek       | V222UA                      | All in one  | [0ed5f3eccd](https://linux-hardware.org/?probe=0ed5f3eccd) | Dec 04, 2022 |
| HP            | 247 G8                      | Notebook    | [f7cc5f6544](https://linux-hardware.org/?probe=f7cc5f6544) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3d8af3595b](https://linux-hardware.org/?probe=3d8af3595b) | Dec 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [416fba6c0c](https://linux-hardware.org/?probe=416fba6c0c) | Dec 03, 2022 |
| Acer          | Aspire A715-51G             | Notebook    | [65aa3f7e69](https://linux-hardware.org/?probe=65aa3f7e69) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [dc80fd6907](https://linux-hardware.org/?probe=dc80fd6907) | Dec 02, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [b28f5fee52](https://linux-hardware.org/?probe=b28f5fee52) | Dec 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f6d1014498](https://linux-hardware.org/?probe=f6d1014498) | Dec 02, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [bdb8b7f059](https://linux-hardware.org/?probe=bdb8b7f059) | Dec 02, 2022 |
| Lenovo        | 510-15IKB 80SV              | Notebook    | [9378fc7d09](https://linux-hardware.org/?probe=9378fc7d09) | Dec 02, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [39557e6703](https://linux-hardware.org/?probe=39557e6703) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [2397eee427](https://linux-hardware.org/?probe=2397eee427) | Dec 01, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [c9ccbe1018](https://linux-hardware.org/?probe=c9ccbe1018) | Dec 01, 2022 |
| HP            | Notebook                    | Notebook    | [7c22b96a9a](https://linux-hardware.org/?probe=7c22b96a9a) | Dec 01, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [65fa0de0a2](https://linux-hardware.org/?probe=65fa0de0a2) | Dec 01, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [ee99c81e47](https://linux-hardware.org/?probe=ee99c81e47) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [b315e85bda](https://linux-hardware.org/?probe=b315e85bda) | Nov 30, 2022 |
| HP            | Notebook                    | Notebook    | [afac08b852](https://linux-hardware.org/?probe=afac08b852) | Nov 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [fa36933936](https://linux-hardware.org/?probe=fa36933936) | Nov 29, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Dell          | Latitude 3500               | Notebook    | [de0731ac74](https://linux-hardware.org/?probe=de0731ac74) | Nov 29, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [fab21fa561](https://linux-hardware.org/?probe=fab21fa561) | Nov 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [16705fe86c](https://linux-hardware.org/?probe=16705fe86c) | Nov 28, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [15909202b8](https://linux-hardware.org/?probe=15909202b8) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2aba12235d](https://linux-hardware.org/?probe=2aba12235d) | Nov 27, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [26083dd909](https://linux-hardware.org/?probe=26083dd909) | Nov 27, 2022 |
| AVITA         | NS14A6                      | Notebook    | [b9cc8fe757](https://linux-hardware.org/?probe=b9cc8fe757) | Nov 27, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [350202deed](https://linux-hardware.org/?probe=350202deed) | Nov 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [dc561bb107](https://linux-hardware.org/?probe=dc561bb107) | Nov 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [336d829333](https://linux-hardware.org/?probe=336d829333) | Nov 26, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [847b1cb39a](https://linux-hardware.org/?probe=847b1cb39a) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [2902b75068](https://linux-hardware.org/?probe=2902b75068) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [973662f8d5](https://linux-hardware.org/?probe=973662f8d5) | Nov 26, 2022 |
| Dell          | Latitude 5490               | Notebook    | [7aedc1fbd7](https://linux-hardware.org/?probe=7aedc1fbd7) | Nov 26, 2022 |
| ASUSTek       | Zenbook UP5401ZA_UP5401Z... | Convertible | [bb84c0cdc2](https://linux-hardware.org/?probe=bb84c0cdc2) | Nov 26, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00d2cc22aa](https://linux-hardware.org/?probe=00d2cc22aa) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [376fc86892](https://linux-hardware.org/?probe=376fc86892) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [f46e1bc341](https://linux-hardware.org/?probe=f46e1bc341) | Nov 25, 2022 |
| HP            | 245 G3                      | Notebook    | [c155a2a926](https://linux-hardware.org/?probe=c155a2a926) | Nov 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [32ab0a36a4](https://linux-hardware.org/?probe=32ab0a36a4) | Nov 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ce5f08445d](https://linux-hardware.org/?probe=ce5f08445d) | Nov 24, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [469b2c3fd4](https://linux-hardware.org/?probe=469b2c3fd4) | Nov 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d84bc82678](https://linux-hardware.org/?probe=d84bc82678) | Nov 23, 2022 |
| HP            | 15                          | Notebook    | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [1071e10a2c](https://linux-hardware.org/?probe=1071e10a2c) | Nov 23, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [0483728614](https://linux-hardware.org/?probe=0483728614) | Nov 23, 2022 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [2f32726e0d](https://linux-hardware.org/?probe=2f32726e0d) | Nov 23, 2022 |
| ASUSTek       | H81M-V3                     | Desktop     | [f6be8306c7](https://linux-hardware.org/?probe=f6be8306c7) | Nov 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [2eec6b4f39](https://linux-hardware.org/?probe=2eec6b4f39) | Nov 22, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [88f4469c5d](https://linux-hardware.org/?probe=88f4469c5d) | Nov 21, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [bce41d01ae](https://linux-hardware.org/?probe=bce41d01ae) | Nov 21, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [687044a497](https://linux-hardware.org/?probe=687044a497) | Nov 21, 2022 |
| HP            | 245 G5 Notebook PC          | Notebook    | [deed1dcf4d](https://linux-hardware.org/?probe=deed1dcf4d) | Nov 21, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2da86d4e21](https://linux-hardware.org/?probe=2da86d4e21) | Nov 21, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [634f7d190d](https://linux-hardware.org/?probe=634f7d190d) | Nov 21, 2022 |
| HP            | 1998                        | Desktop     | [7290e58261](https://linux-hardware.org/?probe=7290e58261) | Nov 21, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a5af222fa3](https://linux-hardware.org/?probe=a5af222fa3) | Nov 21, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [88bbdb925b](https://linux-hardware.org/?probe=88bbdb925b) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [8b07bd39c9](https://linux-hardware.org/?probe=8b07bd39c9) | Nov 19, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [a90cea62ff](https://linux-hardware.org/?probe=a90cea62ff) | Nov 19, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [3d78ceb657](https://linux-hardware.org/?probe=3d78ceb657) | Nov 19, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [cb719dbd60](https://linux-hardware.org/?probe=cb719dbd60) | Nov 19, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [ea2f588ed8](https://linux-hardware.org/?probe=ea2f588ed8) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L6S3L400    | Notebook    | [ae98e93989](https://linux-hardware.org/?probe=ae98e93989) | Nov 18, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [785ae6891c](https://linux-hardware.org/?probe=785ae6891c) | Nov 17, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [190c6d9cc7](https://linux-hardware.org/?probe=190c6d9cc7) | Nov 17, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e48c737ed6](https://linux-hardware.org/?probe=e48c737ed6) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [5c49c7037b](https://linux-hardware.org/?probe=5c49c7037b) | Nov 16, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [15cc03ec87](https://linux-hardware.org/?probe=15cc03ec87) | Nov 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [94983688d2](https://linux-hardware.org/?probe=94983688d2) | Nov 16, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [6b14e6a41b](https://linux-hardware.org/?probe=6b14e6a41b) | Nov 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [119f9da4af](https://linux-hardware.org/?probe=119f9da4af) | Nov 16, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [ddc155c281](https://linux-hardware.org/?probe=ddc155c281) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [dea1636b05](https://linux-hardware.org/?probe=dea1636b05) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [9ed613b632](https://linux-hardware.org/?probe=9ed613b632) | Nov 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [35cb137655](https://linux-hardware.org/?probe=35cb137655) | Nov 15, 2022 |
| Dell          | Precision 7510              | Notebook    | [111903e578](https://linux-hardware.org/?probe=111903e578) | Nov 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [9708710429](https://linux-hardware.org/?probe=9708710429) | Nov 14, 2022 |
| Dell          | Latitude 7480               | Notebook    | [2e485b361c](https://linux-hardware.org/?probe=2e485b361c) | Nov 14, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [e8acccbe3c](https://linux-hardware.org/?probe=e8acccbe3c) | Nov 13, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [5279c2e222](https://linux-hardware.org/?probe=5279c2e222) | Nov 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e19fef63c9](https://linux-hardware.org/?probe=e19fef63c9) | Nov 12, 2022 |
| Intel         | H61                         | Desktop     | [8b718d964b](https://linux-hardware.org/?probe=8b718d964b) | Nov 12, 2022 |
| Dell          | Inspiron 7373               | Convertible | [fddce72af0](https://linux-hardware.org/?probe=fddce72af0) | Nov 12, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [2cfd92452e](https://linux-hardware.org/?probe=2cfd92452e) | Nov 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c73b422075](https://linux-hardware.org/?probe=c73b422075) | Nov 12, 2022 |
| HP            | Notebook                    | Notebook    | [2419e7d149](https://linux-hardware.org/?probe=2419e7d149) | Nov 12, 2022 |
| HP            | Notebook                    | Notebook    | [97c6c3c412](https://linux-hardware.org/?probe=97c6c3c412) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [adf09c8455](https://linux-hardware.org/?probe=adf09c8455) | Nov 11, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [0e0de3ee86](https://linux-hardware.org/?probe=0e0de3ee86) | Nov 11, 2022 |
| Dell          | Latitude E6420              | Notebook    | [70ebe12e06](https://linux-hardware.org/?probe=70ebe12e06) | Nov 11, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [671714bc5a](https://linux-hardware.org/?probe=671714bc5a) | Nov 11, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [d020fa04fe](https://linux-hardware.org/?probe=d020fa04fe) | Nov 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3bcdc36fff](https://linux-hardware.org/?probe=3bcdc36fff) | Nov 11, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [a069831b82](https://linux-hardware.org/?probe=a069831b82) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [217544b651](https://linux-hardware.org/?probe=217544b651) | Nov 11, 2022 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [4ff5cb368c](https://linux-hardware.org/?probe=4ff5cb368c) | Nov 10, 2022 |
| HP            | 2000                        | Notebook    | [5045f21cc3](https://linux-hardware.org/?probe=5045f21cc3) | Nov 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [4be923e459](https://linux-hardware.org/?probe=4be923e459) | Nov 10, 2022 |
| HP            | 8717                        | Desktop     | [57479419c9](https://linux-hardware.org/?probe=57479419c9) | Nov 10, 2022 |
| Samsung       | 950QED                      | Convertible | [c68fd01b4c](https://linux-hardware.org/?probe=c68fd01b4c) | Nov 10, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [4366631db8](https://linux-hardware.org/?probe=4366631db8) | Nov 09, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [0b1b8bf15d](https://linux-hardware.org/?probe=0b1b8bf15d) | Nov 09, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [bc5466e5ac](https://linux-hardware.org/?probe=bc5466e5ac) | Nov 08, 2022 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [bbc7236402](https://linux-hardware.org/?probe=bbc7236402) | Nov 08, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [cb9f2f3d87](https://linux-hardware.org/?probe=cb9f2f3d87) | Nov 08, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [27fcb50d7a](https://linux-hardware.org/?probe=27fcb50d7a) | Nov 07, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [43db111de5](https://linux-hardware.org/?probe=43db111de5) | Nov 07, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| Acer          | H81H3-M4                    | Desktop     | [40c67913d8](https://linux-hardware.org/?probe=40c67913d8) | Nov 06, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [006e91ea03](https://linux-hardware.org/?probe=006e91ea03) | Nov 06, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [43c1e8b8a8](https://linux-hardware.org/?probe=43c1e8b8a8) | Nov 06, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | Notebook    | [1f4a1244b3](https://linux-hardware.org/?probe=1f4a1244b3) | Nov 06, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [390f51010e](https://linux-hardware.org/?probe=390f51010e) | Nov 06, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [1fd362dd3c](https://linux-hardware.org/?probe=1fd362dd3c) | Nov 06, 2022 |
| HP            | 245 G5 Notebook PC          | Notebook    | [4d52b15940](https://linux-hardware.org/?probe=4d52b15940) | Nov 06, 2022 |
| HP            | Notebook                    | Notebook    | [49e26e62f7](https://linux-hardware.org/?probe=49e26e62f7) | Nov 05, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [625b40327b](https://linux-hardware.org/?probe=625b40327b) | Nov 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/India/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 925       | 20.21%  |
| Ubuntu 18.04                 | 413       | 9.02%   |
| Ubuntu 22.04                 | 289       | 6.31%   |
| Arch                         | 104       | 2.27%   |
| Arch Rolling                 | 95        | 2.08%   |
| Zorin 16                     | 86        | 1.88%   |
| KDE neon 20.04               | 84        | 1.84%   |
| Pop!_OS 22.04                | 78        | 1.7%    |
| OpenMandriva 4.3             | 77        | 1.68%   |
| ArcoLinux Rolling            | 71        | 1.55%   |
| Fedora 36                    | 69        | 1.51%   |
| Pop!_OS 20.04                | 67        | 1.46%   |
| Pop!_OS 21.04                | 60        | 1.31%   |
| Ubuntu 20.10                 | 58        | 1.27%   |
| Fedora 37                    | 58        | 1.27%   |
| Fedora 34                    | 58        | 1.27%   |
| OpenMandriva 4.2             | 57        | 1.25%   |
| Zorin 15                     | 56        | 1.22%   |
| Ubuntu 21.04                 | 54        | 1.18%   |
| Manjaro                      | 52        | 1.14%   |
| Ubuntu 19.10                 | 51        | 1.11%   |
| Ubuntu 21.10                 | 45        | 0.98%   |
| Ubuntu 19.04                 | 45        | 0.98%   |
| Pop!_OS 20.10                | 44        | 0.96%   |
| Debian 11                    | 42        | 0.92%   |
| Fedora 35                    | 40        | 0.87%   |
| Fedora 32                    | 39        | 0.85%   |
| Linux Mint 21.1              | 36        | 0.79%   |
| Fedora 38                    | 35        | 0.76%   |
| Ubuntu Unity 16.04           | 34        | 0.74%   |
| Linux Mint 20                | 34        | 0.74%   |
| Fedora 33                    | 34        | 0.74%   |
| Ubuntu 16.04                 | 32        | 0.7%    |
| Linux Mint 20.2              | 32        | 0.7%    |
| Linux Mint 20.3              | 31        | 0.68%   |
| Linux Mint 20.1              | 30        | 0.66%   |
| OpenMandriva 23.03           | 29        | 0.63%   |
| Debian 10                    | 28        | 0.61%   |
| openSUSE Tumbleweed-XXXXXXXX | 27        | 0.59%   |
| Ubuntu 22.10                 | 24        | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1915      | 43.47%  |
| Fedora        | 335       | 7.6%    |
| Pop!_OS       | 262       | 5.95%   |
| Linux Mint    | 199       | 4.52%   |
| OpenMandriva  | 194       | 4.4%    |
| Arch          | 191       | 4.34%   |
| Zorin         | 142       | 3.22%   |
| Manjaro       | 127       | 2.88%   |
| KDE neon      | 116       | 2.63%   |
| Debian        | 93        | 2.11%   |
| Kali          | 82        | 1.86%   |
| ArcoLinux     | 77        | 1.75%   |
| Kubuntu       | 73        | 1.66%   |
| Ubuntu Unity  | 60        | 1.36%   |
| Elementary    | 55        | 1.25%   |
| Endless       | 51        | 1.16%   |
| Xubuntu       | 36        | 0.82%   |
| openSUSE      | 33        | 0.75%   |
| EndeavourOS   | 28        | 0.64%   |
| CentOS        | 27        | 0.61%   |
| RHEL          | 24        | 0.54%   |
| Garuda Linux  | 24        | 0.54%   |
| ROSA          | 22        | 0.5%    |
| Clear Linux   | 22        | 0.5%    |
| Ubuntu Budgie | 16        | 0.36%   |
| Parrot        | 15        | 0.34%   |
| MX            | 15        | 0.34%   |
| Xero          | 13        | 0.3%    |
| Ubuntu MATE   | 13        | 0.3%    |
| Lubuntu       | 12        | 0.27%   |
| Void Linux    | 10        | 0.23%   |
| Solus         | 9         | 0.2%    |
| Gentoo        | 9         | 0.2%    |
| Artix         | 8         | 0.18%   |
| Peppermint    | 7         | 0.16%   |
| Nobara        | 7         | 0.16%   |
| BlackPanther  | 6         | 0.14%   |
| Slackware     | 5         | 0.11%   |
| LMDE          | 5         | 0.11%   |
| LinuxFX       | 4         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 153       | 3.11%   |
| 5.16.7-desktop-1omv4003  | 73        | 1.49%   |
| 5.4.0-40-generic         | 61        | 1.24%   |
| 5.10.14-desktop-1omv4002 | 57        | 1.16%   |
| 5.15.0-56-generic        | 53        | 1.08%   |
| 5.4.0-48-generic         | 47        | 0.96%   |
| 5.4.0-58-generic         | 43        | 0.88%   |
| 5.4.0-52-generic         | 40        | 0.81%   |
| 5.4.0-26-generic         | 40        | 0.81%   |
| 5.11.0-27-generic        | 40        | 0.81%   |
| 5.4.0-47-generic         | 39        | 0.79%   |
| 5.11.0-25-generic        | 35        | 0.71%   |
| 5.11.0-7620-generic      | 34        | 0.69%   |
| 5.4.0-29-generic         | 33        | 0.67%   |
| 5.15.0-52-generic        | 32        | 0.65%   |
| 5.15.0-46-generic        | 31        | 0.63%   |
| 5.8.0-48-generic         | 29        | 0.59%   |
| 5.3.0-28-generic         | 29        | 0.59%   |
| 5.15.0-58-generic        | 29        | 0.59%   |
| 5.11.0-40-generic        | 29        | 0.59%   |
| 6.2.6-desktop-1omv2390   | 28        | 0.57%   |
| 5.8.0-53-generic         | 28        | 0.57%   |
| 5.8.0-55-generic         | 27        | 0.55%   |
| 5.8.0-43-generic         | 27        | 0.55%   |
| 5.4.0-37-generic         | 27        | 0.55%   |
| 5.11.0-43-generic        | 26        | 0.53%   |
| 5.11.0-38-generic        | 26        | 0.53%   |
| 5.11.0-37-generic        | 26        | 0.53%   |
| 5.0.0-37-generic         | 25        | 0.51%   |
| 5.8.0-59-generic         | 24        | 0.49%   |
| 5.8.0-44-generic         | 24        | 0.49%   |
| 5.4.0-74-generic         | 24        | 0.49%   |
| 5.3.0-40-generic         | 24        | 0.49%   |
| 5.19.0-41-generic        | 24        | 0.49%   |
| 5.19.0-38-generic        | 24        | 0.49%   |
| 5.13.0-30-generic        | 24        | 0.49%   |
| 4.15.0-45-generic        | 24        | 0.49%   |
| 5.4.0-45-generic         | 23        | 0.47%   |
| 5.3.0-51-generic         | 23        | 0.47%   |
| 5.15.0-48-generic        | 22        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 867       | 18.47%  |
| 5.15.0  | 380       | 8.1%    |
| 5.11.0  | 335       | 7.14%   |
| 5.8.0   | 310       | 6.6%    |
| 4.15.0  | 237       | 5.05%   |
| 5.13.0  | 206       | 4.39%   |
| 5.3.0   | 192       | 4.09%   |
| 5.19.0  | 158       | 3.37%   |
| 5.0.0   | 130       | 2.77%   |
| 4.18.0  | 103       | 2.19%   |
| 5.16.7  | 75        | 1.6%    |
| 5.10.0  | 73        | 1.56%   |
| 5.10.14 | 57        | 1.21%   |
| 6.2.6   | 41        | 0.87%   |
| 5.14.0  | 32        | 0.68%   |
| 4.19.0  | 30        | 0.64%   |
| 4.4.0   | 25        | 0.53%   |
| 6.1.0   | 23        | 0.49%   |
| 6.1.1   | 22        | 0.47%   |
| 5.17.5  | 22        | 0.47%   |
| 6.2.0   | 19        | 0.4%    |
| 6.0.12  | 19        | 0.4%    |
| 6.0.0   | 16        | 0.34%   |
| 5.7.0   | 14        | 0.3%    |
| 6.0.8   | 13        | 0.28%   |
| 6.0.6   | 13        | 0.28%   |
| 5.18.0  | 13        | 0.28%   |
| 5.15.11 | 13        | 0.28%   |
| 6.0.9   | 12        | 0.26%   |
| 5.9.0   | 12        | 0.26%   |
| 3.10.0  | 12        | 0.26%   |
| 5.17.9  | 11        | 0.23%   |
| 6.3.5   | 10        | 0.21%   |
| 5.16.11 | 10        | 0.21%   |
| 5.16.0  | 10        | 0.21%   |
| 5.13.12 | 10        | 0.21%   |
| 6.2.8   | 9         | 0.19%   |
| 5.6.6   | 9         | 0.19%   |
| 5.15.8  | 9         | 0.19%   |
| 5.15.5  | 9         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 907       | 19.52%  |
| 5.15    | 512       | 11.02%  |
| 5.11    | 374       | 8.05%   |
| 5.8     | 370       | 7.96%   |
| 5.13    | 260       | 5.6%    |
| 4.15    | 240       | 5.17%   |
| 5.3     | 218       | 4.69%   |
| 5.19    | 213       | 4.58%   |
| 5.10    | 202       | 4.35%   |
| 5.16    | 140       | 3.01%   |
| 5.0     | 135       | 2.91%   |
| 6.2     | 118       | 2.54%   |
| 6.0     | 109       | 2.35%   |
| 4.18    | 109       | 2.35%   |
| 6.1     | 108       | 2.32%   |
| 5.14    | 84        | 1.81%   |
| 5.17    | 83        | 1.79%   |
| 5.18    | 70        | 1.51%   |
| 5.12    | 56        | 1.21%   |
| 5.9     | 51        | 1.1%    |
| 5.7     | 49        | 1.05%   |
| 4.19    | 42        | 0.9%    |
| 5.6     | 41        | 0.88%   |
| 6.3     | 40        | 0.86%   |
| 4.4     | 28        | 0.6%    |
| 5.5     | 26        | 0.56%   |
| 4.9     | 16        | 0.34%   |
| 3.10    | 12        | 0.26%   |
| 5.2     | 8         | 0.17%   |
| 4.13    | 5         | 0.11%   |
| 5.1     | 4         | 0.09%   |
| 4.20    | 3         | 0.06%   |
| 3.16    | 3         | 0.06%   |
| 4.14    | 2         | 0.04%   |
| 4.1     | 2         | 0.04%   |
| 5       | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| 4.16    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4162      | 97.93%  |
| i686    | 69        | 1.62%   |
| aarch64 | 13        | 0.31%   |
| armv7l  | 6         | 0.14%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 2500      | 56.61%  |
| KDE5              | 561       | 12.7%   |
| Unknown           | 472       | 10.69%  |
| XFCE              | 210       | 4.76%   |
| X-Cinnamon        | 165       | 3.74%   |
| KDE               | 106       | 2.4%    |
| Unity             | 61        | 1.38%   |
| Pantheon          | 53        | 1.2%    |
| MATE              | 51        | 1.15%   |
| Cinnamon          | 34        | 0.77%   |
| i3                | 26        | 0.59%   |
| GNOME Flashback   | 25        | 0.57%   |
| Budgie            | 23        | 0.52%   |
| LXDE              | 17        | 0.38%   |
| LXQt              | 15        | 0.34%   |
| Deepin            | 14        | 0.32%   |
| KDE4              | 11        | 0.25%   |
| awesome           | 11        | 0.25%   |
| bspwm             | 10        | 0.23%   |
| GNOME Classic     | 9         | 0.2%    |
| sway              | 6         | 0.14%   |
| Hyprland          | 6         | 0.14%   |
| qtile             | 5         | 0.11%   |
| openbox           | 5         | 0.11%   |
| dwm               | 5         | 0.11%   |
| xmonad            | 4         | 0.09%   |
| LeftWM            | 4         | 0.09%   |
| lightdm-xsession  | 2         | 0.05%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| i3-with-shmlog    | 1         | 0.02%   |
| i3-gaps           | 1         | 0.02%   |
| Enlightenment     | 1         | 0.02%   |
| chadwm            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3248      | 74.36%  |
| Wayland | 782       | 17.9%   |
| Unknown | 288       | 6.59%   |
| Tty     | 50        | 1.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2182      | 49.69%  |
| GDM     | 742       | 16.9%   |
| GDM3    | 526       | 11.98%  |
| SDDM    | 507       | 11.55%  |
| LightDM | 302       | 6.88%   |
| TDM     | 105       | 2.39%   |
| KDM     | 9         | 0.2%    |
| XDM     | 7         | 0.16%   |
| LXDM    | 4         | 0.09%   |
| SLiM    | 3         | 0.07%   |
| Ly      | 3         | 0.07%   |
| GREETD  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_IN   | 2647      | 60.34%  |
| en_US   | 1172      | 26.72%  |
| Unknown | 377       | 8.59%   |
| en_GB   | 81        | 1.85%   |
| C       | 72        | 1.64%   |
| en_AG   | 8         | 0.18%   |
| en_CA   | 5         | 0.11%   |
| zh_TW   | 2         | 0.05%   |
| POSIX   | 2         | 0.05%   |
| mr_IN   | 2         | 0.05%   |
| mni_IN  | 2         | 0.05%   |
| en_IE   | 2         | 0.05%   |
| en_AU   | 2         | 0.05%   |
| ta_LK   | 1         | 0.02%   |
| sa_IN   | 1         | 0.02%   |
| pl_PL   | 1         | 0.02%   |
| ks_IN   | 1         | 0.02%   |
| es_ES   | 1         | 0.02%   |
| en_SG   | 1         | 0.02%   |
| en_NG   | 1         | 0.02%   |
| en_DK   | 1         | 0.02%   |
| en_BW   | 1         | 0.02%   |
| de_DE   | 1         | 0.02%   |
| Default | 1         | 0.02%   |
| C.UTF8  | 1         | 0.02%   |
| aa_DJ   | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2513      | 58.12%  |
| BIOS | 1811      | 41.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3486      | 80.21%  |
| Btrfs   | 405       | 9.32%   |
| Overlay | 202       | 4.65%   |
| Unknown | 79        | 1.82%   |
| Xfs     | 72        | 1.66%   |
| Tmpfs   | 47        | 1.08%   |
| Zfs     | 20        | 0.46%   |
| Ext2    | 13        | 0.3%    |
| F2fs    | 11        | 0.25%   |
| Ext3    | 9         | 0.21%   |
| Jfs     | 1         | 0.02%   |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2317      | 53.52%  |
| GPT     | 1674      | 38.67%  |
| MBR     | 338       | 7.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3747      | 86.74%  |
| Yes       | 573       | 13.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2601      | 60.25%  |
| Yes       | 1716      | 39.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 841       | 19.8%   |
| Hewlett-Packard         | 816       | 19.21%  |
| Dell                    | 796       | 18.74%  |
| ASUSTek Computer        | 539       | 12.69%  |
| Acer                    | 271       | 6.38%   |
| Gigabyte Technology     | 252       | 5.93%   |
| MSI                     | 136       | 3.2%    |
| Intel                   | 129       | 3.04%   |
| Unknown                 | 66        | 1.55%   |
| Sony                    | 49        | 1.15%   |
| Toshiba                 | 34        | 0.8%    |
| ASRock                  | 33        | 0.78%   |
| Apple                   | 31        | 0.73%   |
| Samsung Electronics     | 26        | 0.61%   |
| Timi                    | 25        | 0.59%   |
| AVITA                   | 21        | 0.49%   |
| OEM                     | 14        | 0.33%   |
| ECS                     | 11        | 0.26%   |
| Biostar                 | 11        | 0.26%   |
| Raspberry Pi Foundation | 10        | 0.24%   |
| AMI                     | 9         | 0.21%   |
| HCL Infosystems Limited | 8         | 0.19%   |
| Fujitsu                 | 8         | 0.19%   |
| Foxconn                 | 8         | 0.19%   |
| HUAWEI                  | 7         | 0.16%   |
| HONOR                   | 7         | 0.16%   |
| Google                  | 6         | 0.14%   |
| LG Electronics          | 5         | 0.12%   |
| Radxa                   | 4         | 0.09%   |
| ITI LIMITED             | 4         | 0.09%   |
| Gateway                 | 4         | 0.09%   |
| eMachines               | 4         | 0.09%   |
| Alienware               | 4         | 0.09%   |
| WIPRO                   | 3         | 0.07%   |
| Valve                   | 3         | 0.07%   |
| realme                  | 3         | 0.07%   |
| Pegatron                | 3         | 0.07%   |
| LORD ELECTRONICS        | 3         | 0.07%   |
| Supermicro              | 2         | 0.05%   |
| Razer                   | 2         | 0.05%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 91        | 2.14%   |
| HP Notebook                            | 74        | 1.74%   |
| HP 15                                  | 31        | 0.73%   |
| HP Pavilion 15                         | 30        | 0.71%   |
| HP Pavilion g6                         | 27        | 0.64%   |
| Dell Inspiron 3542                     | 26        | 0.61%   |
| Gigabyte H410M H V3                    | 23        | 0.54%   |
| Dell Inspiron 15-3567                  | 22        | 0.52%   |
| Lenovo E41-25 81FS                     | 21        | 0.49%   |
| HP Laptop 15-bs0xx                     | 21        | 0.49%   |
| Dell Inspiron 5570                     | 20        | 0.47%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 18        | 0.42%   |
| Dell Inspiron 3521                     | 18        | 0.42%   |
| Intel H61                              | 17        | 0.4%    |
| ASUS TUF Gaming FX505DT_FX505DT        | 17        | 0.4%    |
| HP Pavilion Notebook                   | 16        | 0.38%   |
| Acer Aspire A715-75G                   | 16        | 0.38%   |
| Lenovo G50-80 80E5                     | 15        | 0.35%   |
| Dell Vostro 3480                       | 15        | 0.35%   |
| Dell Vostro 15-3568                    | 15        | 0.35%   |
| Gigabyte H81M-S                        | 14        | 0.33%   |
| Gigabyte H61MS                         | 14        | 0.33%   |
| HP Laptop 15-da0xxx                    | 13        | 0.31%   |
| Dell Vostro 3578                       | 13        | 0.31%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 12        | 0.28%   |
| Dell Inspiron 5559                     | 12        | 0.28%   |
| ASUS X510UNR                           | 12        | 0.28%   |
| Lenovo IdeaPad 320-15ISK 80XH          | 11        | 0.26%   |
| Lenovo G50-45 80E3                     | 11        | 0.26%   |
| HP Laptop 15-bw0xx                     | 11        | 0.26%   |
| Gigabyte H310M S2 2.0                  | 11        | 0.26%   |
| Gigabyte H110M-S2                      | 11        | 0.26%   |
| Dell Inspiron N5010                    | 11        | 0.26%   |
| Dell Inspiron 1545                     | 11        | 0.26%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR   | 11        | 0.26%   |
| ASUS TUF Gaming FX505DY_FX505DY        | 11        | 0.26%   |
| Intel HCL Desktop                      | 10        | 0.24%   |
| HP Pavilion x360 Convertible 14-dh1xxx | 10        | 0.24%   |
| HP Pavilion Laptop 14-dv0xxx           | 10        | 0.24%   |
| HP Pavilion dv6                        | 10        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 357       | 8.4%    |
| Lenovo ThinkPad    | 267       | 6.29%   |
| Lenovo IdeaPad     | 266       | 6.26%   |
| HP Pavilion        | 227       | 5.34%   |
| HP Laptop          | 158       | 3.72%   |
| ASUS VivoBook      | 151       | 3.55%   |
| Dell Latitude      | 150       | 3.53%   |
| Dell Vostro        | 144       | 3.39%   |
| Acer Aspire        | 144       | 3.39%   |
| Unknown            | 91        | 2.14%   |
| HP Notebook        | 75        | 1.77%   |
| ASUS TUF           | 57        | 1.34%   |
| HP EliteBook       | 56        | 1.32%   |
| ASUS ROG           | 52        | 1.22%   |
| HP ProBook         | 47        | 1.11%   |
| Dell OptiPlex      | 45        | 1.06%   |
| ASUS ASUS          | 45        | 1.06%   |
| ASUS PRIME         | 35        | 0.82%   |
| Acer Nitro         | 35        | 0.82%   |
| Lenovo Legion      | 32        | 0.75%   |
| HP 15              | 32        | 0.75%   |
| Dell XPS           | 32        | 0.75%   |
| HP ENVY            | 30        | 0.71%   |
| Toshiba Satellite  | 29        | 0.68%   |
| Gigabyte H410M     | 29        | 0.68%   |
| Lenovo ThinkBook   | 28        | 0.66%   |
| Dell Precision     | 28        | 0.66%   |
| Acer Swift         | 27        | 0.64%   |
| HP Compaq          | 26        | 0.61%   |
| Gigabyte H310M     | 22        | 0.52%   |
| Lenovo ThinkCentre | 21        | 0.49%   |
| Lenovo E41-25      | 21        | 0.49%   |
| Lenovo Yoga        | 18        | 0.42%   |
| Lenovo IdeaPadFlex | 18        | 0.42%   |
| Intel H61          | 17        | 0.4%    |
| Acer Veriton       | 17        | 0.4%    |
| Timi Mi            | 16        | 0.38%   |
| ASUS ZenBook       | 16        | 0.38%   |
| Acer Predator      | 16        | 0.38%   |
| Lenovo G50-80      | 15        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 578       | 13.61%  |
| 2019    | 561       | 13.21%  |
| 2020    | 437       | 10.29%  |
| 2021    | 378       | 8.9%    |
| 2017    | 366       | 8.62%   |
| 2016    | 267       | 6.29%   |
| 2012    | 261       | 6.14%   |
| 2013    | 249       | 5.86%   |
| 2014    | 248       | 5.84%   |
| 2011    | 228       | 5.37%   |
| 2015    | 184       | 4.33%   |
| 2010    | 165       | 3.88%   |
| 2022    | 122       | 2.87%   |
| 2008    | 75        | 1.77%   |
| 2009    | 68        | 1.6%    |
| 2007    | 25        | 0.59%   |
| Unknown | 17        | 0.4%    |
| 2006    | 8         | 0.19%   |
| 2023    | 7         | 0.16%   |
| 2005    | 3         | 0.07%   |
| 2003    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3090      | 72.74%  |
| Desktop        | 944       | 22.22%  |
| Convertible    | 115       | 2.71%   |
| Mini pc        | 31        | 0.73%   |
| All in one     | 29        | 0.68%   |
| System on chip | 18        | 0.42%   |
| Tablet         | 11        | 0.26%   |
| Server         | 10        | 0.24%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3751      | 87.62%  |
| Enabled  | 530       | 12.38%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4235      | 99.69%  |
| Yes  | 13        | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1367      | 31.78%  |
| 3.01-4.0    | 997       | 23.18%  |
| 8.01-16.0   | 830       | 19.29%  |
| 16.01-24.0  | 691       | 16.06%  |
| 1.01-2.0    | 152       | 3.53%   |
| 32.01-64.0  | 146       | 3.39%   |
| 2.01-3.0    | 41        | 0.95%   |
| 64.01-256.0 | 35        | 0.81%   |
| 24.01-32.0  | 24        | 0.56%   |
| 0.51-1.0    | 17        | 0.4%    |
| 0.01-0.5    | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1492      | 32.15%  |
| 2.01-3.0   | 1457      | 31.39%  |
| 4.01-8.0   | 677       | 14.59%  |
| 3.01-4.0   | 663       | 14.29%  |
| 0.51-1.0   | 169       | 3.64%   |
| 8.01-16.0  | 136       | 2.93%   |
| 0.01-0.5   | 32        | 0.69%   |
| 16.01-24.0 | 10        | 0.22%   |
| 32.01-64.0 | 2         | 0.04%   |
| 24.01-32.0 | 2         | 0.04%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3025      | 70.23%  |
| 2      | 1045      | 24.26%  |
| 3      | 142       | 3.3%    |
| 4      | 37        | 0.86%   |
| 0      | 30        | 0.7%    |
| 5      | 15        | 0.35%   |
| 6      | 8         | 0.19%   |
| 7      | 3         | 0.07%   |
| 9      | 1         | 0.02%   |
| 8      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2851      | 66.67%  |
| Yes       | 1425      | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3524      | 82.8%   |
| No        | 732       | 17.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3724      | 87.32%  |
| No        | 541       | 12.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3148      | 73.28%  |
| No        | 1148      | 26.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| India   | 4248      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Bengaluru     | 537       | 11.86%  |
| Mumbai        | 298       | 6.58%   |
| Chennai       | 288       | 6.36%   |
| Hyderabad     | 261       | 5.76%   |
| Delhi         | 222       | 4.9%    |
| Pune          | 220       | 4.86%   |
| Kolkata       | 192       | 4.24%   |
| New Delhi     | 191       | 4.22%   |
| Ahmedabad     | 100       | 2.21%   |
| Lucknow       | 84        | 1.85%   |
| Ernakulam     | 79        | 1.74%   |
| Patna         | 78        | 1.72%   |
| Jaipur        | 75        | 1.66%   |
| Gurgaon       | 65        | 1.44%   |
| Indore        | 58        | 1.28%   |
| Coimbatore    | 53        | 1.17%   |
| Bhopal        | 53        | 1.17%   |
| Navi Mumbai   | 51        | 1.13%   |
| Kochi         | 50        | 1.1%    |
| Trivandrum    | 46        | 1.02%   |
| Thrissur      | 45        | 0.99%   |
| Surat         | 44        | 0.97%   |
| Guwahati      | 38        | 0.84%   |
| Malappuram    | 35        | 0.77%   |
| Ludhiana      | 33        | 0.73%   |
| Nagpur        | 32        | 0.71%   |
| Bhubaneswar   | 32        | 0.71%   |
| Noida         | 26        | 0.57%   |
| Thane         | 23        | 0.51%   |
| Vadodara      | 22        | 0.49%   |
| Gonikoppal    | 22        | 0.49%   |
| Ghaziabad     | 22        | 0.49%   |
| Visakhapatnam | 21        | 0.46%   |
| Chandigarh    | 21        | 0.46%   |
| Vijayawada    | 20        | 0.44%   |
| Kanpur        | 20        | 0.44%   |
| Dehradun      | 19        | 0.42%   |
| Mangalore     | 18        | 0.4%    |
| Tiruchi       | 17        | 0.38%   |
| Mohali        | 17        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1167      | 1518   | 21.51%  |
| WDC                         | 1005      | 1294   | 18.52%  |
| Toshiba                     | 542       | 621    | 9.99%   |
| Samsung Electronics         | 510       | 655    | 9.4%    |
| SanDisk                     | 224       | 276    | 4.13%   |
| Crucial                     | 214       | 278    | 3.94%   |
| Kingston                    | 210       | 252    | 3.87%   |
| SK hynix                    | 187       | 212    | 3.45%   |
| Intel                       | 178       | 237    | 3.28%   |
| HGST                        | 173       | 205    | 3.19%   |
| Micron Technology           | 136       | 154    | 2.51%   |
| Unknown                     | 124       | 153    | 2.29%   |
| Hitachi                     | 106       | 128    | 1.95%   |
| KIOXIA                      | 73        | 86     | 1.35%   |
| A-DATA Technology           | 70        | 76     | 1.29%   |
| China                       | 44        | 52     | 0.81%   |
| Unknown                     | 28        | 33     | 0.52%   |
| Gigabyte Technology         | 27        | 31     | 0.5%    |
| Micron/Crucial Technology   | 24        | 26     | 0.44%   |
| FORESEE                     | 19        | 21     | 0.35%   |
| Apple                       | 19        | 26     | 0.35%   |
| UMIS                        | 18        | 21     | 0.33%   |
| Silicon Motion              | 17        | 20     | 0.31%   |
| Phison                      | 16        | 19     | 0.29%   |
| LITEON                      | 16        | 20     | 0.29%   |
| Hewlett-Packard             | 16        | 22     | 0.29%   |
| Lexar                       | 11        | 11     | 0.2%    |
| SPCC                        | 10        | 17     | 0.18%   |
| Maxtor                      | 10        | 25     | 0.18%   |
| Kingston Technology Company | 10        | 11     | 0.18%   |
| Realtek Semiconductor       | 9         | 13     | 0.17%   |
| Fujitsu                     | 9         | 9      | 0.17%   |
| Acer                        | 9         | 9      | 0.17%   |
| XPG                         | 8         | 9      | 0.15%   |
| Transcend                   | 8         | 9      | 0.15%   |
| TO Exter                    | 7         | 7      | 0.13%   |
| Union Memory (Shenzhen)     | 6         | 6      | 0.11%   |
| Union Memory                | 6         | 7      | 0.11%   |
| PNY                         | 6         | 8      | 0.11%   |
| ADATA Technology            | 6         | 8      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 282       | 4.94%   |
| Toshiba MQ04ABF100 1TB             | 150       | 2.63%   |
| Toshiba MQ01ABD100 1TB             | 107       | 1.87%   |
| Seagate ST1000DM010-2EP102 1TB     | 82        | 1.44%   |
| Crucial CT240BX500SSD1 240GB       | 72        | 1.26%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 71        | 1.24%   |
| Seagate ST1000LM049-2GH172 1TB     | 66        | 1.16%   |
| Seagate ST500LT012-1DG142 500GB    | 61        | 1.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 60        | 1.05%   |
| Kingston SA400S37240G 240GB SSD    | 53        | 0.93%   |
| Intel NVMe SSD Drive 512GB         | 52        | 0.91%   |
| Toshiba MQ01ABF050 500GB           | 44        | 0.77%   |
| Seagate ST500DM002-1BD142 500GB    | 42        | 0.74%   |
| Toshiba DT01ACA100 1TB             | 40        | 0.7%    |
| SanDisk NVMe SSD Drive 512GB       | 40        | 0.7%    |
| HGST HTS541010A9E680 1TB           | 39        | 0.68%   |
| SanDisk NVMe SSD Drive 256GB       | 38        | 0.67%   |
| WDC WD10SPZX-60Z10T0 1TB           | 37        | 0.65%   |
| Intel SSDPEKNW512G8 512GB          | 37        | 0.65%   |
| Seagate ST9500325AS 500GB          | 36        | 0.63%   |
| Samsung NVMe SSD Drive 512GB       | 36        | 0.63%   |
| Seagate ST2000LM007-1R8174 2TB     | 34        | 0.6%    |
| WDC WD10SPZX-24Z10 1TB             | 33        | 0.58%   |
| Seagate ST1000LM048-2E7172 1TB     | 32        | 0.56%   |
| HGST HTS721010A9E630 1TB           | 32        | 0.56%   |
| SK hynix NVMe SSD Drive 512GB      | 30        | 0.53%   |
| Unknown                            | 28        | 0.49%   |
| WDC WD10JPVX-60JC3T1 1TB           | 27        | 0.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 26        | 0.46%   |
| Samsung NVMe SSD Drive 256GB       | 26        | 0.46%   |
| HGST HTS545050A7E680 500GB         | 26        | 0.46%   |
| Crucial CT480BX500SSD1 480GB       | 26        | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB           | 25        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB           | 24        | 0.42%   |
| Samsung SSD 860 EVO 250GB          | 24        | 0.42%   |
| A-DATA SU750 256GB SSD             | 23        | 0.4%    |
| Seagate ST500LT012-9WS142 500GB    | 22        | 0.39%   |
| Seagate ST3500418AS 500GB          | 22        | 0.39%   |
| Kingston SA400S37480G 480GB SSD    | 22        | 0.39%   |
| Kingston SA400S37120G 120GB SSD    | 22        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1153      | 1500   | 42.1%   |
| WDC                 | 755       | 934    | 27.56%  |
| Toshiba             | 479       | 538    | 17.49%  |
| HGST                | 173       | 205    | 6.32%   |
| Hitachi             | 106       | 128    | 3.87%   |
| Samsung Electronics | 23        | 26     | 0.84%   |
| Unknown             | 18        | 22     | 0.66%   |
| Fujitsu             | 9         | 9      | 0.33%   |
| Apple               | 7         | 7      | 0.26%   |
| Hewlett-Packard     | 5         | 6      | 0.18%   |
| Maxtor              | 3         | 3      | 0.11%   |
| WD MediaMax         | 1         | 1      | 0.04%   |
| Synology            | 1         | 1      | 0.04%   |
| StoreJet            | 1         | 1      | 0.04%   |
| MARSHAL             | 1         | 1      | 0.04%   |
| Lenovo              | 1         | 1      | 0.04%   |
| KESU                | 1         | 2      | 0.04%   |
| IBM                 | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 191       | 244    | 15.71%  |
| Crucial             | 191       | 253    | 15.71%  |
| WDC                 | 177       | 219    | 14.56%  |
| Kingston            | 146       | 181    | 12.01%  |
| SanDisk             | 63        | 82     | 5.18%   |
| A-DATA Technology   | 63        | 69     | 5.18%   |
| China               | 43        | 51     | 3.54%   |
| SK hynix            | 36        | 38     | 2.96%   |
| Micron Technology   | 26        | 34     | 2.14%   |
| Intel               | 22        | 23     | 1.81%   |
| Gigabyte Technology | 22        | 24     | 1.81%   |
| FORESEE             | 17        | 19     | 1.4%    |
| Toshiba             | 14        | 15     | 1.15%   |
| LITEON              | 14        | 18     | 1.15%   |
| Unknown             | 14        | 14     | 1.15%   |
| Lexar               | 11        | 11     | 0.9%    |
| Hewlett-Packard     | 10        | 15     | 0.82%   |
| Seagate             | 9         | 9      | 0.74%   |
| Apple               | 9         | 13     | 0.74%   |
| Transcend           | 7         | 8      | 0.58%   |
| TO Exter            | 7         | 7      | 0.58%   |
| SPCC                | 7         | 11     | 0.58%   |
| Maxtor              | 7         | 22     | 0.58%   |
| Acer                | 7         | 7      | 0.58%   |
| PNY                 | 6         | 8      | 0.49%   |
| Unknown             | 5         | 5      | 0.41%   |
| External            | 5         | 9      | 0.41%   |
| Netac               | 4         | 4      | 0.33%   |
| Leven               | 4         | 4      | 0.33%   |
| KingSpec            | 4         | 4      | 0.33%   |
| EVM                 | 4         | 5      | 0.33%   |
| StoreJet            | 3         | 3      | 0.25%   |
| Plextor             | 3         | 3      | 0.25%   |
| LITEONIT            | 3         | 6      | 0.25%   |
| KLEVV               | 3         | 4      | 0.25%   |
| HS-SSD-C100         | 3         | 4      | 0.25%   |
| Zebronics           | 2         | 2      | 0.16%   |
| Unknown (690)       | 2         | 2      | 0.16%   |
| Team                | 2         | 2      | 0.16%   |
| POWER               | 2         | 2      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2600      | 3387   | 49.91%  |
| NVMe    | 1322      | 1689   | 25.38%  |
| SSD     | 1146      | 1508   | 22%     |
| MMC     | 100       | 129    | 1.92%   |
| Unknown | 41        | 51     | 0.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3237      | 4793   | 67.75%  |
| NVMe | 1321      | 1687   | 27.65%  |
| SAS  | 120       | 155    | 2.51%   |
| MMC  | 100       | 129    | 2.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1954      | 2567   | 51.95%  |
| 0.51-1.0   | 1608      | 2013   | 42.75%  |
| 1.01-2.0   | 135       | 200    | 3.59%   |
| 3.01-4.0   | 39        | 70     | 1.04%   |
| 4.01-10.0  | 12        | 22     | 0.32%   |
| 2.01-3.0   | 10        | 16     | 0.27%   |
| 10.01-20.0 | 3         | 7      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1189      | 26.66%  |
| 101-250        | 1148      | 25.74%  |
| 501-1000       | 755       | 16.93%  |
| 51-100         | 405       | 9.08%   |
| 1001-2000      | 275       | 6.17%   |
| 21-50          | 268       | 6.01%   |
| 1-20           | 231       | 5.18%   |
| More than 3000 | 70        | 1.57%   |
| Unknown        | 64        | 1.43%   |
| 2001-3000      | 55        | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1762      | 38.18%  |
| 21-50          | 961       | 20.82%  |
| 101-250        | 632       | 13.69%  |
| 51-100         | 563       | 12.2%   |
| 251-500        | 343       | 7.43%   |
| 501-1000       | 194       | 4.2%    |
| Unknown        | 64        | 1.39%   |
| 1001-2000      | 63        | 1.37%   |
| More than 3000 | 21        | 0.46%   |
| 2001-3000      | 11        | 0.24%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 25        | 26     | 6.36%   |
| HGST HTS541010A9E680 1TB             | 14        | 14     | 3.56%   |
| Seagate ST500DM002-1BD142 500GB      | 11        | 11     | 2.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 11        | 11     | 2.8%    |
| HGST HTS545050A7E680 500GB           | 11        | 15     | 2.8%    |
| Toshiba MQ01ABD100 1TB               | 10        | 10     | 2.54%   |
| Seagate ST500LT012-1DG142 500GB      | 10        | 10     | 2.54%   |
| Seagate ST9500325AS 500GB            | 9         | 9      | 2.29%   |
| Seagate ST1000LM049-2GH172 1TB       | 9         | 11     | 2.29%   |
| Toshiba MQ04ABF100 1TB               | 6         | 7      | 1.53%   |
| Seagate ST500LT012-9WS142 500GB      | 6         | 7      | 1.53%   |
| Seagate ST500LM021-1KJ152 500GB      | 6         | 6      | 1.53%   |
| Toshiba MQ01ABF050 500GB             | 5         | 5      | 1.27%   |
| Seagate ST3500418AS 500GB            | 5         | 5      | 1.27%   |
| HGST HTS721010A9E630 1TB             | 5         | 5      | 1.27%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 4      | 1.02%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 4      | 1.02%   |
| HGST HTS545050A7E380 500GB           | 4         | 4      | 1.02%   |
| WDC WD10JPVX-60JC3T1 1TB             | 3         | 3      | 0.76%   |
| Toshiba DT01ACA100 1TB               | 3         | 5      | 0.76%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 3         | 3      | 0.76%   |
| Seagate ST9320325AS 320GB            | 3         | 3      | 0.76%   |
| Seagate ST9160314AS 160GB            | 3         | 4      | 0.76%   |
| Seagate ST2000LM007-1R8174 2TB       | 3         | 3      | 0.76%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 0.76%   |
| Seagate ST1000DM003-1ER162 1TB       | 3         | 3      | 0.76%   |
| Hitachi HTS547575A9E384 752GB        | 3         | 3      | 0.76%   |
| HGST HTS725050A7E630 500GB           | 3         | 3      | 0.76%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 2      | 0.51%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 2      | 0.51%   |
| WDC WD5000LPVT-22G33T0 500GB         | 2         | 2      | 0.51%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 2         | 2      | 0.51%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 6      | 0.51%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 2         | 2      | 0.51%   |
| WDC WD3200AAJS-00L7A0 320GB          | 2         | 2      | 0.51%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 2      | 0.51%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 2      | 0.51%   |
| Toshiba MQ01ABD050 500GB             | 2         | 2      | 0.51%   |
| Toshiba HDWD110 1TB                  | 2         | 2      | 0.51%   |
| SK hynix PC711 HFS001TDE9X073N 1TB   | 2         | 2      | 0.51%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 156       | 169    | 40.41%  |
| WDC                 | 68        | 80     | 17.62%  |
| HGST                | 41        | 45     | 10.62%  |
| Toshiba             | 40        | 44     | 10.36%  |
| Hitachi             | 26        | 29     | 6.74%   |
| SK hynix            | 13        | 14     | 3.37%   |
| Samsung Electronics | 9         | 11     | 2.33%   |
| SanDisk             | 6         | 6      | 1.55%   |
| Intel               | 4         | 4      | 1.04%   |
| Crucial             | 4         | 5      | 1.04%   |
| A-DATA Technology   | 3         | 3      | 0.78%   |
| Apple               | 2         | 2      | 0.52%   |
| Unknown             | 2         | 2      | 0.52%   |
| YS                  | 1         | 1      | 0.26%   |
| Wibtek              | 1         | 1      | 0.26%   |
| Unknown             | 1         | 1      | 0.26%   |
| SPCC                | 1         | 1      | 0.26%   |
| Micron Technology   | 1         | 1      | 0.26%   |
| MARSHAL             | 1         | 1      | 0.26%   |
| LITEON              | 1         | 1      | 0.26%   |
| Leven               | 1         | 1      | 0.26%   |
| Lenovo              | 1         | 2      | 0.26%   |
| Innodisk            | 1         | 1      | 0.26%   |
| IBM                 | 1         | 1      | 0.26%   |
| China               | 1         | 1      | 0.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 156       | 169    | 46.71%  |
| WDC                 | 63        | 74     | 18.86%  |
| HGST                | 41        | 45     | 12.28%  |
| Toshiba             | 39        | 43     | 11.68%  |
| Hitachi             | 26        | 29     | 7.78%   |
| Samsung Electronics | 5         | 6      | 1.5%    |
| Apple               | 2         | 2      | 0.6%    |
| MARSHAL             | 1         | 1      | 0.3%    |
| IBM                 | 1         | 1      | 0.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 331       | 370    | 86.42%  |
| SSD  | 33        | 36     | 8.62%   |
| NVMe | 19        | 21     | 4.96%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB         | 1         | 1      | 12.5%   |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 1      | 12.5%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 12.5%   |
| Seagate ST3320418AS 320GB           | 1         | 1      | 12.5%   |
| Seagate ST1000LM 024 HN-M101MBB 1TB | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 980 500GB   | 1         | 2      | 12.5%   |
| Apple HDD HTS545050A7E362 500GB     | 1         | 1      | 12.5%   |
| Acer SSD FA100 256GB                | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 37.5%   |
| WDC                 | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 2      | 12.5%   |
| Apple               | 1         | 1      | 12.5%   |
| Acer                | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2570      | 4005   | 56.86%  |
| Works    | 1565      | 2323   | 34.62%  |
| Malfunc  | 377       | 427    | 8.34%   |
| Failed   | 8         | 9      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3169      | 61.76%  |
| AMD                              | 660       | 12.86%  |
| Samsung Electronics              | 319       | 6.22%   |
| SanDisk                          | 264       | 5.15%   |
| SK hynix                         | 150       | 2.92%   |
| Micron Technology                | 110       | 2.14%   |
| KIOXIA                           | 77        | 1.5%    |
| Kingston Technology Company      | 74        | 1.44%   |
| Toshiba America Info Systems     | 60        | 1.17%   |
| Micron/Crucial Technology        | 46        | 0.9%    |
| Union Memory (Shenzhen)          | 28        | 0.55%   |
| ASMedia Technology               | 23        | 0.45%   |
| Silicon Motion                   | 22        | 0.43%   |
| Phison Electronics               | 22        | 0.43%   |
| ADATA Technology                 | 18        | 0.35%   |
| Nvidia                           | 17        | 0.33%   |
| Realtek Semiconductor            | 14        | 0.27%   |
| JMicron Technology               | 8         | 0.16%   |
| Yangtze Memory Technologies      | 7         | 0.14%   |
| Solid State Storage Technology   | 7         | 0.14%   |
| Marvell Technology Group         | 6         | 0.12%   |
| Silicon Integrated Systems [SiS] | 4         | 0.08%   |
| Shenzhen Longsys Electronics     | 4         | 0.08%   |
| Lite-On Technology               | 4         | 0.08%   |
| LSI Logic / Symbios Logic        | 3         | 0.06%   |
| Lenovo                           | 3         | 0.06%   |
| Broadcom / LSI                   | 3         | 0.06%   |
| Apple                            | 3         | 0.06%   |
| VIA Technologies                 | 2         | 0.04%   |
| INNOGRIT                         | 2         | 0.04%   |
| Seagate Technology               | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 566       | 9.87%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 471       | 8.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 324       | 5.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 199       | 3.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 178       | 3.1%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 159       | 2.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 140       | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 135       | 2.35%   |
| Samsung NVMe SSD Controller 980                                                         | 131       | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 127       | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 117       | 2.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 116       | 2.02%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 113       | 1.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 111       | 1.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 106       | 1.85%   |
| Intel SSD 660P Series                                                                   | 101       | 1.76%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 95        | 1.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 92        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 78        | 1.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 71        | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 70        | 1.22%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 68        | 1.19%   |
| Micron NVMe Storage Controller                                                          | 63        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 60        | 1.05%   |
| AMD 400 Series Chipset SATA Controller                                                  | 58        | 1.01%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 53        | 0.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 52        | 0.91%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 50        | 0.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 48        | 0.84%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 47        | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 46        | 0.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 44        | 0.77%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 43        | 0.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 41        | 0.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 39        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 39        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 39        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 39        | 0.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 38        | 0.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 38        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3074      | 57.97%  |
| NVMe | 1331      | 25.1%   |
| RAID | 531       | 10.01%  |
| IDE  | 363       | 6.85%   |
| SAS  | 2         | 0.04%   |
| SCSI | 2         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3395      | 79.92%  |
| AMD          | 833       | 19.61%  |
| ARM          | 19        | 0.45%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 191       | 4.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 121       | 2.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 97        | 2.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 90        | 2.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 80        | 1.88%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 75        | 1.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 56        | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 51        | 1.2%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 50        | 1.18%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 49        | 1.15%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 48        | 1.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 47        | 1.11%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 45        | 1.06%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 44        | 1.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 43        | 1.01%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 38        | 0.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 37        | 0.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 36        | 0.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 35        | 0.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 34        | 0.8%    |
| Intel Core i3-10110U CPU @ 2.10GHz            | 34        | 0.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 32        | 0.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 31        | 0.73%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 31        | 0.73%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 30        | 0.71%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 30        | 0.71%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 0.68%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 28        | 0.66%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 27        | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 0.64%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 27        | 0.64%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 26        | 0.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 25        | 0.59%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 24        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 23        | 0.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 23        | 0.54%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 23        | 0.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 23        | 0.54%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 23        | 0.54%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 23        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1293      | 30.43%  |
| Intel Core i3           | 715       | 16.83%  |
| Intel Core i7           | 531       | 12.5%   |
| Other                   | 359       | 8.45%   |
| AMD Ryzen 5             | 330       | 7.77%   |
| Intel Pentium           | 135       | 3.18%   |
| AMD Ryzen 7             | 134       | 3.15%   |
| Intel Core 2 Duo        | 127       | 2.99%   |
| Intel Celeron           | 79        | 1.86%   |
| AMD Ryzen 3             | 67        | 1.58%   |
| Intel Pentium Dual-Core | 58        | 1.37%   |
| AMD A6                  | 43        | 1.01%   |
| AMD A8                  | 32        | 0.75%   |
| AMD A4                  | 29        | 0.68%   |
| AMD Ryzen 9             | 28        | 0.66%   |
| Intel Atom              | 27        | 0.64%   |
| Intel Xeon              | 23        | 0.54%   |
| AMD FX                  | 23        | 0.54%   |
| Intel Pentium Dual      | 19        | 0.45%   |
| Intel Core 2            | 18        | 0.42%   |
| AMD A10                 | 16        | 0.38%   |
| Intel Core 2 Quad       | 15        | 0.35%   |
| AMD E1                  | 15        | 0.35%   |
| Intel Pentium Silver    | 12        | 0.28%   |
| Intel Core i9           | 9         | 0.21%   |
| AMD Ryzen 7 PRO         | 8         | 0.19%   |
| AMD E2                  | 8         | 0.19%   |
| Intel Pentium Gold      | 7         | 0.16%   |
| Intel Pentium 4         | 7         | 0.16%   |
| AMD Athlon II X2        | 7         | 0.16%   |
| AMD Ryzen 5 PRO         | 6         | 0.14%   |
| AMD E                   | 6         | 0.14%   |
| ARM BCM                 | 5         | 0.12%   |
| AMD Sempron             | 5         | 0.12%   |
| Intel Pentium D         | 4         | 0.09%   |
| AMD Ryzen Threadripper  | 4         | 0.09%   |
| AMD Phenom II X4        | 4         | 0.09%   |
| AMD Phenom II X2        | 4         | 0.09%   |
| AMD Athlon              | 4         | 0.09%   |
| Intel Xeon Silver       | 3         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1965      | 46.22%  |
| 4      | 1549      | 36.44%  |
| 6      | 382       | 8.99%   |
| 8      | 207       | 4.87%   |
| 1      | 53        | 1.25%   |
| 12     | 40        | 0.94%   |
| 10     | 19        | 0.45%   |
| 14     | 12        | 0.28%   |
| 16     | 10        | 0.24%   |
| 3      | 7         | 0.16%   |
| 24     | 3         | 0.07%   |
| 32     | 2         | 0.05%   |
| 36     | 1         | 0.02%   |
| 20     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4234      | 99.67%  |
| 2      | 14        | 0.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 3245      | 76.39%  |
| 1      | 1001      | 23.56%  |
| 12     | 1         | 0.02%   |
| 4      | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4193      | 98.64%  |
| Unknown        | 51        | 1.2%    |
| 32-bit         | 6         | 0.14%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 916       | 20.93%  |
| 0x806ea    | 229       | 5.23%   |
| 0x306a9    | 229       | 5.23%   |
| 0x806ec    | 222       | 5.07%   |
| 0x206a7    | 209       | 4.78%   |
| 0x806c1    | 160       | 3.66%   |
| 0x906ea    | 154       | 3.52%   |
| 0x40651    | 152       | 3.47%   |
| 0x406e3    | 147       | 3.36%   |
| 0x806e9    | 144       | 3.29%   |
| 0x1067a    | 119       | 2.72%   |
| 0x306c3    | 110       | 2.51%   |
| 0x306d4    | 107       | 2.45%   |
| 0x08108109 | 85        | 1.94%   |
| 0x706e5    | 79        | 1.81%   |
| 0x20655    | 63        | 1.44%   |
| 0x906e9    | 62        | 1.42%   |
| 0x806eb    | 61        | 1.39%   |
| 0x0a50000c | 57        | 1.3%    |
| 0x506e3    | 56        | 1.28%   |
| 0x08108102 | 50        | 1.14%   |
| 0xa0652    | 44        | 1.01%   |
| 0x06006705 | 40        | 0.91%   |
| 0x6fd      | 37        | 0.85%   |
| 0x08600106 | 33        | 0.75%   |
| 0x07030105 | 31        | 0.71%   |
| 0x20652    | 30        | 0.69%   |
| 0x08608103 | 29        | 0.66%   |
| 0x08600104 | 29        | 0.66%   |
| 0x0810100b | 28        | 0.64%   |
| 0xa0655    | 27        | 0.62%   |
| 0x906a3    | 27        | 0.62%   |
| 0x08701021 | 25        | 0.57%   |
| 0x906ed    | 23        | 0.53%   |
| 0x30678    | 22        | 0.5%    |
| 0x08101007 | 20        | 0.46%   |
| 0x06001119 | 20        | 0.46%   |
| 0x010000c8 | 20        | 0.46%   |
| 0x706a1    | 16        | 0.37%   |
| 0x506c9    | 16        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1111      | 26.15%  |
| Haswell          | 322       | 7.58%   |
| IvyBridge        | 281       | 6.61%   |
| Skylake          | 260       | 6.12%   |
| SandyBridge      | 256       | 6.02%   |
| TigerLake        | 198       | 4.66%   |
| Zen+             | 185       | 4.35%   |
| Penryn           | 169       | 3.98%   |
| Zen 2            | 149       | 3.51%   |
| Broadwell        | 135       | 3.18%   |
| IceLake          | 116       | 2.73%   |
| Westmere         | 115       | 2.71%   |
| Unknown          | 111       | 2.61%   |
| CometLake        | 110       | 2.59%   |
| Zen 3            | 101       | 2.38%   |
| Zen              | 85        | 2%      |
| Excavator        | 81        | 1.91%   |
| Core             | 77        | 1.81%   |
| Silvermont       | 63        | 1.48%   |
| Alderlake Hybrid | 60        | 1.41%   |
| Puma             | 52        | 1.22%   |
| Piledriver       | 44        | 1.04%   |
| Goldmont plus    | 29        | 0.68%   |
| K10              | 24        | 0.56%   |
| Goldmont         | 23        | 0.54%   |
| Nehalem          | 15        | 0.35%   |
| K10 Llano        | 13        | 0.31%   |
| Bobcat           | 13        | 0.31%   |
| NetBurst         | 12        | 0.28%   |
| Bonnell          | 11        | 0.26%   |
| Jaguar           | 6         | 0.14%   |
| Bulldozer        | 6         | 0.14%   |
| Steamroller      | 5         | 0.12%   |
| Tremont          | 4         | 0.09%   |
| K8 Hammer        | 4         | 0.09%   |
| P6               | 3         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3096      | 57.01%  |
| Nvidia                           | 1250      | 23.02%  |
| AMD                              | 1074      | 19.78%  |
| Silicon Integrated Systems [SiS] | 4         | 0.07%   |
| Matrox Electronics Systems       | 3         | 0.06%   |
| ASPEED Technology                | 2         | 0.04%   |
| VIA Technologies                 | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 260       | 4.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 226       | 4.08%   |
| Intel HD Graphics 620                                                                 | 191       | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 184       | 3.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 181       | 3.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 180       | 3.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 162       | 2.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 162       | 2.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 157       | 2.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 156       | 2.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 145       | 2.62%   |
| Intel HD Graphics 5500                                                                | 119       | 2.15%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 110       | 1.99%   |
| AMD Renoir                                                                            | 99        | 1.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 93        | 1.68%   |
| Intel Core Processor Integrated Graphics Controller                                   | 85        | 1.53%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 78        | 1.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 73        | 1.32%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 72        | 1.3%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 70        | 1.26%   |
| Nvidia TU117M                                                                         | 68        | 1.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 65        | 1.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 64        | 1.16%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 63        | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 60        | 1.08%   |
| Intel HD Graphics 630                                                                 | 58        | 1.05%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 57        | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 54        | 0.97%   |
| Nvidia GP108M [GeForce MX250]                                                         | 51        | 0.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 50        | 0.9%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 50        | 0.9%    |
| AMD Lucienne                                                                          | 47        | 0.85%   |
| Nvidia GP108M [GeForce MX150]                                                         | 44        | 0.79%   |
| Nvidia GM108M [GeForce MX130]                                                         | 41        | 0.74%   |
| Intel HD Graphics 530                                                                 | 41        | 0.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 41        | 0.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 40        | 0.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 39        | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                         | 38        | 0.69%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 36        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2040      | 47.78%  |
| Intel + Nvidia     | 746       | 17.47%  |
| 1 x AMD            | 570       | 13.35%  |
| 1 x Nvidia         | 356       | 8.34%   |
| Intel + AMD        | 286       | 6.7%    |
| AMD + Nvidia       | 144       | 3.37%   |
| 2 x AMD            | 79        | 1.85%   |
| Other              | 25        | 0.59%   |
| 2 x Intel          | 10        | 0.23%   |
| 1 x SiS            | 4         | 0.09%   |
| 2 x Nvidia         | 3         | 0.07%   |
| 1 x Matrox         | 3         | 0.07%   |
| 1 x VIA            | 1         | 0.02%   |
| Nvidia + ASPEED    | 1         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |
| 1 x ASPEED         | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3495      | 81.18%  |
| Proprietary | 672       | 15.61%  |
| Unknown     | 138       | 3.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2652      | 60.73%  |
| 1.01-2.0   | 681       | 15.59%  |
| 0.01-0.5   | 381       | 8.72%   |
| 3.01-4.0   | 321       | 7.35%   |
| 0.51-1.0   | 205       | 4.69%   |
| 5.01-6.0   | 64        | 1.47%   |
| 7.01-8.0   | 37        | 0.85%   |
| 8.01-16.0  | 15        | 0.34%   |
| 16.01-24.0 | 6         | 0.14%   |
| 2.01-3.0   | 5         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 710       | 16.37%  |
| Chimei Innolux          | 661       | 15.24%  |
| AU Optronics            | 660       | 15.22%  |
| LG Display              | 527       | 12.15%  |
| Samsung Electronics     | 352       | 8.12%   |
| Dell                    | 248       | 5.72%   |
| Goldstar                | 179       | 4.13%   |
| BenQ                    | 122       | 2.81%   |
| Acer                    | 116       | 2.68%   |
| PANDA                   | 106       | 2.44%   |
| Hewlett-Packard         | 81        | 1.87%   |
| Lenovo                  | 71        | 1.64%   |
| AOC                     | 54        | 1.25%   |
| Sharp                   | 48        | 1.11%   |
| Chi Mei Optoelectronics | 41        | 0.95%   |
| InfoVision              | 37        | 0.85%   |
| ViewSonic               | 25        | 0.58%   |
| Sony                    | 25        | 0.58%   |
| Apple                   | 25        | 0.58%   |
| HCL                     | 19        | 0.44%   |
| Unknown                 | 14        | 0.32%   |
| Philips                 | 14        | 0.32%   |
| LG Electronics          | 13        | 0.3%    |
| TMX                     | 11        | 0.25%   |
| ASUSTek Computer        | 9         | 0.21%   |
| LG Philips              | 7         | 0.16%   |
| InnoLux Display         | 7         | 0.16%   |
| Toshiba                 | 6         | 0.14%   |
| STD                     | 6         | 0.14%   |
| Panasonic               | 6         | 0.14%   |
| CSO                     | 6         | 0.14%   |
| Ancor Communications    | 6         | 0.14%   |
| HKC                     | 5         | 0.12%   |
| Gigabyte Technology     | 5         | 0.12%   |
| Xiaomi                  | 4         | 0.09%   |
| SGT                     | 4         | 0.09%   |
| MSI                     | 4         | 0.09%   |
| AOpen                   | 4         | 0.09%   |
| Valve                   | 3         | 0.07%   |
| RTK                     | 3         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 86        | 1.96%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 70        | 1.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 42        | 0.96%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 39        | 0.89%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 37        | 0.84%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 36        | 0.82%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 34        | 0.78%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                     | 33        | 0.75%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 33        | 0.75%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 30        | 0.68%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 29        | 0.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 27        | 0.62%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 27        | 0.62%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 25        | 0.57%   |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                    | 25        | 0.57%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 24        | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 23        | 0.52%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 22        | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 22        | 0.5%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 22        | 0.5%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 21        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 21        | 0.48%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 21        | 0.48%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 20        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 20        | 0.46%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 20        | 0.46%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 19        | 0.43%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 18        | 0.41%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 16        | 0.37%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 16        | 0.37%   |
| BOE LCD Monitor BOE07BD 1920x1080 309x174mm 14.0-inch                | 16        | 0.37%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 16        | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 15        | 0.34%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 14        | 0.32%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 14        | 0.32%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 14        | 0.32%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                    | 14        | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 14        | 0.32%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 14        | 0.32%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch       | 14        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2051      | 48.68%  |
| 1366x768 (WXGA)    | 1497      | 35.53%  |
| 1600x900 (HD+)     | 131       | 3.11%   |
| 3840x2160 (4K)     | 96        | 2.28%   |
| 2560x1440 (QHD)    | 66        | 1.57%   |
| 1440x900 (WXGA+)   | 61        | 1.45%   |
| 1280x800 (WXGA)    | 44        | 1.04%   |
| 1920x1200 (WUXGA)  | 41        | 0.97%   |
| 2560x1600          | 28        | 0.66%   |
| 1360x768           | 26        | 0.62%   |
| 1280x1024 (SXGA)   | 25        | 0.59%   |
| 2560x1080          | 19        | 0.45%   |
| 1680x1050 (WSXGA+) | 17        | 0.4%    |
| 2880x1800          | 15        | 0.36%   |
| Unknown            | 15        | 0.36%   |
| 3840x1080          | 9         | 0.21%   |
| 1024x768 (XGA)     | 8         | 0.19%   |
| 1024x600           | 7         | 0.17%   |
| 3200x2000          | 6         | 0.14%   |
| 1280x720 (HD)      | 6         | 0.14%   |
| 3840x2400          | 4         | 0.09%   |
| 800x1280           | 3         | 0.07%   |
| 4093x4093          | 3         | 0.07%   |
| 3440x1440          | 3         | 0.07%   |
| 2160x1440          | 3         | 0.07%   |
| 3456x2160          | 2         | 0.05%   |
| 3072x1920          | 2         | 0.05%   |
| 2736x1824          | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |
| 2240x1400          | 2         | 0.05%   |
| 1280x768           | 2         | 0.05%   |
| 1152x864           | 2         | 0.05%   |
| 8160x4627          | 1         | 0.02%   |
| 6400x2160          | 1         | 0.02%   |
| 5760x2160          | 1         | 0.02%   |
| 4480x1080          | 1         | 0.02%   |
| 3840x1100          | 1         | 0.02%   |
| 3286x1080          | 1         | 0.02%   |
| 3200x900           | 1         | 0.02%   |
| 3200x1800 (QHD+)   | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1863      | 43.01%  |
| 13      | 574       | 13.25%  |
| 14      | 545       | 12.58%  |
| 21      | 258       | 5.96%   |
| 18      | 229       | 5.29%   |
| 24      | 128       | 2.95%   |
| 19      | 105       | 2.42%   |
| Unknown | 100       | 2.31%   |
| 23      | 95        | 2.19%   |
| 27      | 80        | 1.85%   |
| 20      | 53        | 1.22%   |
| 12      | 50        | 1.15%   |
| 17      | 47        | 1.08%   |
| 31      | 30        | 0.69%   |
| 16      | 30        | 0.69%   |
| 11      | 19        | 0.44%   |
| 34      | 18        | 0.42%   |
| 26      | 13        | 0.3%    |
| 72      | 12        | 0.28%   |
| 40      | 11        | 0.25%   |
| 22      | 10        | 0.23%   |
| 10      | 10        | 0.23%   |
| 32      | 9         | 0.21%   |
| 84      | 7         | 0.16%   |
| 46      | 6         | 0.14%   |
| 65      | 5         | 0.12%   |
| 25      | 4         | 0.09%   |
| 54      | 3         | 0.07%   |
| 52      | 3         | 0.07%   |
| 42      | 3         | 0.07%   |
| 39      | 3         | 0.07%   |
| 7       | 3         | 0.07%   |
| 36      | 2         | 0.05%   |
| 142     | 1         | 0.02%   |
| 63      | 1         | 0.02%   |
| 58      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2833      | 65.64%  |
| 401-500        | 644       | 14.92%  |
| 501-600        | 298       | 6.9%    |
| 201-300        | 222       | 5.14%   |
| Unknown        | 100       | 2.32%   |
| 351-400        | 90        | 2.09%   |
| 601-700        | 40        | 0.93%   |
| 701-800        | 29        | 0.67%   |
| 1001-1500      | 20        | 0.46%   |
| 1501-2000      | 19        | 0.44%   |
| 801-900        | 14        | 0.32%   |
| 901-1000       | 3         | 0.07%   |
| 1-100          | 3         | 0.07%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3671      | 90.11%  |
| 16/10   | 216       | 5.3%    |
| Unknown | 96        | 2.36%   |
| 4/3     | 25        | 0.61%   |
| 5/4     | 21        | 0.52%   |
| 21/9    | 18        | 0.44%   |
| 3/2     | 11        | 0.27%   |
| 6/5     | 6         | 0.15%   |
| 2.00    | 4         | 0.1%    |
| 0.67    | 3         | 0.07%   |
| 32/9    | 1         | 0.02%   |
| 3.40    | 1         | 0.02%   |
| 1.00    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1847      | 42.66%  |
| 81-90          | 1006      | 23.23%  |
| 201-250        | 420       | 9.7%    |
| 141-150        | 237       | 5.47%   |
| 151-200        | 210       | 4.85%   |
| 71-80          | 115       | 2.66%   |
| Unknown        | 100       | 2.31%   |
| 301-350        | 84        | 1.94%   |
| 351-500        | 57        | 1.32%   |
| 61-70          | 42        | 0.97%   |
| More than 1000 | 33        | 0.76%   |
| 251-300        | 32        | 0.74%   |
| 121-130        | 32        | 0.74%   |
| 111-120        | 29        | 0.67%   |
| 501-1000       | 26        | 0.6%    |
| 51-60          | 20        | 0.46%   |
| 91-100         | 17        | 0.39%   |
| 41-50          | 10        | 0.23%   |
| 131-140        | 10        | 0.23%   |
| 1-40           | 3         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1610      | 37.58%  |
| 101-120       | 1452      | 33.89%  |
| 51-100        | 863       | 20.14%  |
| 161-240       | 173       | 4.04%   |
| Unknown       | 100       | 2.33%   |
| More than 240 | 48        | 1.12%   |
| 1-50          | 38        | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3828      | 88.96%  |
| 2     | 332       | 7.72%   |
| 0     | 134       | 3.11%   |
| 3     | 9         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2869      | 42.47%  |
| Intel                             | 1739      | 25.74%  |
| Qualcomm Atheros                  | 848       | 12.55%  |
| Broadcom                          | 282       | 4.17%   |
| Ralink Technology                 | 125       | 1.85%   |
| Xiaomi                            | 106       | 1.57%   |
| MediaTek                          | 95        | 1.41%   |
| TP-Link                           | 91        | 1.35%   |
| Ralink                            | 68        | 1.01%   |
| Samsung Electronics               | 63        | 0.93%   |
| OPPO Electronics                  | 60        | 0.89%   |
| Broadcom Limited                  | 54        | 0.8%    |
| Qualcomm                          | 41        | 0.61%   |
| D-Link                            | 33        | 0.49%   |
| Marvell Technology Group          | 31        | 0.46%   |
| ASIX Electronics                  | 25        | 0.37%   |
| OnePlus Technology (Shenzhen)     | 24        | 0.36%   |
| Huawei Technologies               | 24        | 0.36%   |
| Motorola PCS                      | 19        | 0.28%   |
| Foxconn / Hon Hai                 | 15        | 0.22%   |
| Qualcomm Atheros Communications   | 13        | 0.19%   |
| Nvidia                            | 13        | 0.19%   |
| ICS Advent                        | 9         | 0.13%   |
| Google                            | 8         | 0.12%   |
| NetGear                           | 7         | 0.1%    |
| Lenovo                            | 7         | 0.1%    |
| vivo                              | 6         | 0.09%   |
| JMicron Technology                | 6         | 0.09%   |
| Edimax Technology                 | 6         | 0.09%   |
| NTmore                            | 5         | 0.07%   |
| HMD Global                        | 5         | 0.07%   |
| DisplayLink                       | 5         | 0.07%   |
| ASUSTek Computer                  | 5         | 0.07%   |
| Microchip Technology              | 4         | 0.06%   |
| D-Link System                     | 4         | 0.06%   |
| Ericsson Business Mobile Networks | 3         | 0.04%   |
| Dell                              | 3         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.03%   |
| Spreadtrum Communications         | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1886      | 24.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 660       | 8.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 305       | 3.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 152       | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 148       | 1.88%   |
| Intel Wi-Fi 6 AX200                                               | 147       | 1.87%   |
| Intel Wi-Fi 6 AX201                                               | 146       | 1.86%   |
| Intel Wireless 8265 / 8275                                        | 141       | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 120       | 1.53%   |
| Ralink MT7601U Wireless Adapter                                   | 111       | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 108       | 1.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 108       | 1.38%   |
| Broadcom BCM43142 802.11b/g/n                                     | 104       | 1.32%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 102       | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 100       | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 97        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 91        | 1.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 87        | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 85        | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 85        | 1.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 80        | 1.02%   |
| Intel Wireless 7265                                               | 79        | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 78        | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 76        | 0.97%   |
| Intel Wireless 3165                                               | 76        | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 63        | 0.8%    |
| Intel Wireless 3160                                               | 61        | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 58        | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 57        | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 53        | 0.67%   |
| OPPO CPH2411                                                      | 52        | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 50        | 0.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 48        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 47        | 0.6%    |
| Intel Wireless 8260                                               | 47        | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 41        | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 41        | 0.52%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 40        | 0.51%   |
| Intel Wireless 7260                                               | 39        | 0.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 36        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1503      | 39.01%  |
| Realtek Semiconductor           | 880       | 22.84%  |
| Qualcomm Atheros                | 756       | 19.62%  |
| Broadcom                        | 238       | 6.18%   |
| Ralink Technology               | 125       | 3.24%   |
| TP-Link                         | 83        | 2.15%   |
| MediaTek                        | 78        | 2.02%   |
| Ralink                          | 67        | 1.74%   |
| Broadcom Limited                | 42        | 1.09%   |
| D-Link                          | 33        | 0.86%   |
| Qualcomm Atheros Communications | 13        | 0.34%   |
| Qualcomm                        | 7         | 0.18%   |
| NetGear                         | 7         | 0.18%   |
| Edimax Technology               | 6         | 0.16%   |
| Dell                            | 3         | 0.08%   |
| Sierra Wireless                 | 2         | 0.05%   |
| D-Link System                   | 2         | 0.05%   |
| ASUSTek Computer                | 2         | 0.05%   |
| Wacom                           | 1         | 0.03%   |
| Philips (or NXP)                | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Marvell Technology Group        | 1         | 0.03%   |
| IMC Networks                    | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 305       | 7.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 152       | 3.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 148       | 3.82%   |
| Intel Wi-Fi 6 AX200                                                  | 147       | 3.8%    |
| Intel Wi-Fi 6 AX201                                                  | 146       | 3.77%   |
| Intel Wireless 8265 / 8275                                           | 141       | 3.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 120       | 3.1%    |
| Ralink MT7601U Wireless Adapter                                      | 111       | 2.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 108       | 2.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 108       | 2.79%   |
| Broadcom BCM43142 802.11b/g/n                                        | 104       | 2.69%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 102       | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 100       | 2.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 97        | 2.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 91        | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 85        | 2.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 85        | 2.2%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 80        | 2.07%   |
| Intel Wireless 7265                                                  | 79        | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 78        | 2.01%   |
| Intel Wireless 3165                                                  | 76        | 1.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 63        | 1.63%   |
| Intel Wireless 3160                                                  | 61        | 1.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 58        | 1.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 57        | 1.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 53        | 1.37%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 50        | 1.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 48        | 1.24%   |
| Intel Wireless 8260                                                  | 47        | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 41        | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 41        | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 40        | 1.03%   |
| Intel Wireless 7260                                                  | 39        | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 36        | 0.93%   |
| Intel Wireless-AC 9260                                               | 31        | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 31        | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                           | 25        | 0.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 23        | 0.59%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 21        | 0.54%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 20        | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2626      | 67.8%   |
| Intel                            | 566       | 14.61%  |
| Qualcomm Atheros                 | 136       | 3.51%   |
| Xiaomi                           | 106       | 2.74%   |
| Broadcom                         | 65        | 1.68%   |
| OPPO Electronics                 | 60        | 1.55%   |
| Samsung Electronics              | 47        | 1.21%   |
| Qualcomm                         | 34        | 0.88%   |
| Marvell Technology Group         | 30        | 0.77%   |
| ASIX Electronics                 | 25        | 0.65%   |
| Huawei Technologies              | 20        | 0.52%   |
| OnePlus Technology (Shenzhen)    | 18        | 0.46%   |
| MediaTek                         | 18        | 0.46%   |
| Nvidia                           | 12        | 0.31%   |
| Motorola PCS                     | 12        | 0.31%   |
| Broadcom Limited                 | 12        | 0.31%   |
| ICS Advent                       | 9         | 0.23%   |
| TP-Link                          | 8         | 0.21%   |
| Google                           | 8         | 0.21%   |
| vivo                             | 6         | 0.15%   |
| Lenovo                           | 6         | 0.15%   |
| JMicron Technology               | 6         | 0.15%   |
| NTmore                           | 5         | 0.13%   |
| HMD Global                       | 5         | 0.13%   |
| DisplayLink                      | 5         | 0.13%   |
| Foxconn / Hon Hai                | 4         | 0.1%    |
| Microchip Technology             | 3         | 0.08%   |
| ASUSTek Computer                 | 3         | 0.08%   |
| Spreadtrum Communications        | 2         | 0.05%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| D-Link System                    | 2         | 0.05%   |
| Attansic Technology              | 2         | 0.05%   |
| Aquantia                         | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| VIA Technologies                 | 1         | 0.03%   |
| Standard Microsystems            | 1         | 0.03%   |
| LG Electronics                   | 1         | 0.03%   |
| LeEco                            | 1         | 0.03%   |
| HTC (High Tech Computer)         | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1886      | 48.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 660       | 16.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 87        | 2.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 76        | 1.94%   |
| OPPO CPH2411                                                      | 52        | 1.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 47        | 1.2%    |
| Intel Ethernet Connection (4) I219-V                              | 34        | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 31        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 30        | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                 | 30        | 0.77%   |
| Qualcomm Nokia G400 5G                                            | 30        | 0.77%   |
| Intel Ethernet Connection I217-LM                                 | 30        | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 27        | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 0.66%   |
| Intel I211 Gigabit Network Connection                             | 26        | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 26        | 0.66%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 23        | 0.59%   |
| Intel Ethernet Controller I225-V                                  | 19        | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                     | 19        | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 18        | 0.46%   |
| OnePlus (Shenzhen) OnePlus                                        | 18        | 0.46%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.41%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.38%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.38%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 0.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 14        | 0.36%   |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13        | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 13        | 0.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 0.33%   |
| MediaTek Armor X10 Pro                                            | 13        | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 13        | 0.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 13        | 0.33%   |
| Motorola PCS moto g(30)                                           | 12        | 0.31%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 0.31%   |
| Intel Ethernet Connection (6) I219-LM                             | 12        | 0.31%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 11        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3723      | 50.94%  |
| Ethernet | 3518      | 48.14%  |
| Modem    | 35        | 0.48%   |
| Unknown  | 32        | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3081      | 73.13%  |
| Ethernet | 1126      | 26.73%  |
| Unknown  | 4         | 0.09%   |
| Modem    | 2         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2591      | 60.85%  |
| 1     | 1567      | 36.8%   |
| 0     | 62        | 1.46%   |
| 3     | 31        | 0.73%   |
| 4     | 6         | 0.14%   |
| 6     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3510      | 81.29%  |
| Yes  | 808       | 18.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1307      | 41.24%  |
| Realtek Semiconductor           | 503       | 15.87%  |
| Qualcomm Atheros Communications | 462       | 14.58%  |
| Broadcom                        | 163       | 5.14%   |
| IMC Networks                    | 156       | 4.92%   |
| Cambridge Silicon Radio         | 137       | 4.32%   |
| Lite-On Technology              | 125       | 3.94%   |
| Foxconn / Hon Hai               | 96        | 3.03%   |
| Ralink                          | 53        | 1.67%   |
| Dell                            | 36        | 1.14%   |
| Apple                           | 29        | 0.92%   |
| TP-Link                         | 16        | 0.5%    |
| Hewlett-Packard                 | 16        | 0.5%    |
| MediaTek                        | 11        | 0.35%   |
| Foxconn International           | 10        | 0.32%   |
| Toshiba                         | 8         | 0.25%   |
| ASUSTek Computer                | 8         | 0.25%   |
| Realtek                         | 7         | 0.22%   |
| Ralink Technology               | 7         | 0.22%   |
| Opticis                         | 5         | 0.16%   |
| Integrated System Solution      | 4         | 0.13%   |
| USI                             | 2         | 0.06%   |
| SINO WEALTH                     | 2         | 0.06%   |
| Chicony Electronics             | 2         | 0.06%   |
| Micro Star International        | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |
| Alps Electric                   | 1         | 0.03%   |
| Accel Semiconductor             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 436       | 13.75%  |
| Realtek Bluetooth Radio                                                             | 305       | 9.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 302       | 9.53%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 274       | 8.64%   |
| Intel AX201 Bluetooth                                                               | 270       | 8.52%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 149       | 4.7%    |
| Intel AX200 Bluetooth                                                               | 144       | 4.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 137       | 4.32%   |
| IMC Networks Bluetooth Radio                                                        | 59        | 1.86%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 58        | 1.83%   |
| IMC Networks Bluetooth Device                                                       | 54        | 1.7%    |
| Ralink RT3290 Bluetooth                                                             | 53        | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 47        | 1.48%   |
| Lite-On Bluetooth Device                                                            | 45        | 1.42%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 44        | 1.39%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 41        | 1.29%   |
| IMC Networks Wireless_Device                                                        | 40        | 1.26%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 39        | 1.23%   |
| Intel Bluetooth Device                                                              | 39        | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 37        | 1.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 29        | 0.91%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 29        | 0.91%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 25        | 0.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 21        | 0.66%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 21        | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 18        | 0.57%   |
| Realtek RTL8821A Bluetooth                                                          | 17        | 0.54%   |
| TP-Link UB500 Adapter                                                               | 16        | 0.5%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 15        | 0.47%   |
| Realtek RTL8723B Bluetooth                                                          | 15        | 0.47%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 15        | 0.47%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 15        | 0.47%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 15        | 0.47%   |
| Apple Bluetooth USB Host Controller                                                 | 15        | 0.47%   |
| Dell Wireless 365 Bluetooth                                                         | 13        | 0.41%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 12        | 0.38%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 12        | 0.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 12        | 0.38%   |
| Qualcomm Atheros Bluetooth                                                          | 11        | 0.35%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 11        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3352      | 65.34%  |
| AMD                                          | 892       | 17.39%  |
| Nvidia                                       | 695       | 13.55%  |
| C-Media Electronics                          | 32        | 0.62%   |
| GN Netcom                                    | 19        | 0.37%   |
| Creative Labs                                | 10        | 0.19%   |
| Generalplus Technology                       | 9         | 0.18%   |
| Plantronics                                  | 8         | 0.16%   |
| JMTek                                        | 8         | 0.16%   |
| Realtek Semiconductor                        | 7         | 0.14%   |
| Texas Instruments                            | 6         | 0.12%   |
| Logitech                                     | 6         | 0.12%   |
| ASUSTek Computer                             | 6         | 0.12%   |
| Tenx Technology                              | 5         | 0.1%    |
| Creative Technology                          | 5         | 0.1%    |
| SteelSeries ApS                              | 4         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.08%   |
| Sennheiser Communications                    | 4         | 0.08%   |
| Micro Star International                     | 3         | 0.06%   |
| Lenovo                                       | 3         | 0.06%   |
| Hewlett-Packard                              | 3         | 0.06%   |
| OPPO Electronics                             | 2         | 0.04%   |
| M-Audio                                      | 2         | 0.04%   |
| Jieli Technology                             | 2         | 0.04%   |
| Giga-Byte Technology                         | 2         | 0.04%   |
| Focusrite-Novation                           | 2         | 0.04%   |
| DCMT Technology                              | 2         | 0.04%   |
| Corsair                                      | 2         | 0.04%   |
| Cambridge Silicon Radio                      | 2         | 0.04%   |
| Apple                                        | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| ZOOM                                         | 1         | 0.02%   |
| Yamaha                                       | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |
| VIA Technologies                             | 1         | 0.02%   |
| Vault                                        | 1         | 0.02%   |
| SZSanJing                                    | 1         | 0.02%   |
| Synaptics                                    | 1         | 0.02%   |
| Sony                                         | 1         | 0.02%   |
| Shenzhen Rapoo Technology                    | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 639       | 10.32%  |
| AMD Family 17h/19h HD Audio Controller                                     | 476       | 7.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 270       | 4.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 262       | 4.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 198       | 3.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 198       | 3.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 191       | 3.08%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 186       | 3%      |
| Intel 8 Series HD Audio Controller                                         | 184       | 2.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 183       | 2.95%   |
| Intel Haswell-ULT HD Audio Controller                                      | 182       | 2.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 161       | 2.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 152       | 2.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 150       | 2.42%   |
| Intel Broadwell-U Audio Controller                                         | 131       | 2.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 130       | 2.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 127       | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 127       | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 110       | 1.78%   |
| AMD FCH Azalia Controller                                                  | 107       | 1.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 103       | 1.66%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 93        | 1.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 86        | 1.39%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 79        | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                   | 72        | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 67        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 65        | 1.05%   |
| AMD High Definition Audio Controller                                       | 62        | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 61        | 0.98%   |
| Intel 200 Series PCH HD Audio                                              | 60        | 0.97%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 58        | 0.94%   |
| AMD Starship/Matisse HD Audio Controller                                   | 58        | 0.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 52        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 49        | 0.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 43        | 0.69%   |
| Nvidia High Definition Audio Controller                                    | 42        | 0.68%   |
| Intel CM238 HD Audio Controller                                            | 36        | 0.58%   |
| Nvidia GF119 HDMI Audio Controller                                         | 31        | 0.5%    |
| Nvidia GA106 High Definition Audio Controller                              | 30        | 0.48%   |
| Nvidia Audio device                                                        | 29        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 722       | 25.65%  |
| SK hynix                     | 669       | 23.77%  |
| Micron Technology            | 365       | 12.97%  |
| Kingston                     | 243       | 8.63%   |
| Crucial                      | 164       | 5.83%   |
| Unknown                      | 139       | 4.94%   |
| A-DATA Technology            | 108       | 3.84%   |
| Corsair                      | 102       | 3.62%   |
| Ramaxel Technology           | 99        | 3.52%   |
| Transcend                    | 56        | 1.99%   |
| G.Skill                      | 31        | 1.1%    |
| CSX                          | 26        | 0.92%   |
| Nanya Technology             | 20        | 0.71%   |
| Elpida                       | 20        | 0.71%   |
| Unknown (ABCD)               | 7         | 0.25%   |
| OM Nanotech                  | 6         | 0.21%   |
| Unknown                      | 6         | 0.21%   |
| Silicon Power                | 4         | 0.14%   |
| Avant                        | 3         | 0.11%   |
| ZION                         | 2         | 0.07%   |
| Team                         | 2         | 0.07%   |
| Kllisre                      | 2         | 0.07%   |
| ASint Technology             | 2         | 0.07%   |
| Apacer                       | 2         | 0.07%   |
| Unknown (0xAD44594E45540000) | 1         | 0.04%   |
| Unknown (0x1007)             | 1         | 0.04%   |
| Unknown (0x0CDC)             | 1         | 0.04%   |
| Unknown (09D5)               | 1         | 0.04%   |
| Unknown (07F7)               | 1         | 0.04%   |
| Strontium                    | 1         | 0.04%   |
| SHARETRONIC                  | 1         | 0.04%   |
| Ramos Technology             | 1         | 0.04%   |
| Qumo                         | 1         | 0.04%   |
| Qimonda                      | 1         | 0.04%   |
| Patriot Memory (PDP Systems) | 1         | 0.04%   |
| NETSOL                       | 1         | 0.04%   |
| Lexar Co Limited             | 1         | 0.04%   |
| Goldkey                      | 1         | 0.04%   |
| Gold Key                     | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 67        | 2.26%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 60        | 2.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 54        | 1.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 42        | 1.42%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 40        | 1.35%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 40        | 1.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 35        | 1.18%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 33        | 1.12%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 32        | 1.08%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 31        | 1.05%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 31        | 1.05%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 30        | 1.01%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 28        | 0.95%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 27        | 0.91%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 24        | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 23        | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 23        | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 21        | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s    | 21        | 0.71%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 21        | 0.71%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 21        | 0.71%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 21        | 0.71%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s   | 20        | 0.68%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 19        | 0.64%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 19        | 0.64%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 18        | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 17        | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s      | 17        | 0.57%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                    | 17        | 0.57%   |
| Crucial RAM CB8GS2400.C8ET 8GB SODIMM DDR4 2667MT/s         | 17        | 0.57%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s        | 16        | 0.54%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s      | 16        | 0.54%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 15        | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 14        | 0.47%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s       | 14        | 0.47%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s       | 14        | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 13        | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 13        | 0.44%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 13        | 0.44%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 13        | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1453      | 62.74%  |
| DDR3    | 606       | 26.17%  |
| LPDDR4  | 79        | 3.41%   |
| SDRAM   | 54        | 2.33%   |
| DDR2    | 43        | 1.86%   |
| LPDDR3  | 29        | 1.25%   |
| Unknown | 20        | 0.86%   |
| DDR5    | 15        | 0.65%   |
| LPDDR5  | 12        | 0.52%   |
| DDR     | 5         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1715      | 74.57%  |
| DIMM         | 426       | 18.52%  |
| Row Of Chips | 152       | 6.61%   |
| Chip         | 4         | 0.17%   |
| Unknown      | 2         | 0.09%   |
| RIMM         | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1175      | 46.13%  |
| 4096  | 795       | 31.21%  |
| 16384 | 296       | 11.62%  |
| 2048  | 219       | 8.6%    |
| 1024  | 34        | 1.33%   |
| 32768 | 23        | 0.9%    |
| 512   | 4         | 0.16%   |
| 1536  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 647       | 25.65%  |
| 3200    | 509       | 20.18%  |
| 1600    | 454       | 18%     |
| 2400    | 238       | 9.44%   |
| 1333    | 103       | 4.08%   |
| 2133    | 87        | 3.45%   |
| 3266    | 67        | 2.66%   |
| 1334    | 61        | 2.42%   |
| Unknown | 40        | 1.59%   |
| 3600    | 32        | 1.27%   |
| 2666    | 29        | 1.15%   |
| 667     | 29        | 1.15%   |
| 4267    | 23        | 0.91%   |
| 1067    | 22        | 0.87%   |
| 4199    | 19        | 0.75%   |
| 3000    | 17        | 0.67%   |
| 2800    | 16        | 0.63%   |
| 1867    | 16        | 0.63%   |
| 800     | 15        | 0.59%   |
| 6400    | 13        | 0.52%   |
| 4800    | 12        | 0.48%   |
| 975     | 12        | 0.48%   |
| 1866    | 8         | 0.32%   |
| 3733    | 6         | 0.24%   |
| 8400    | 4         | 0.16%   |
| 2048    | 4         | 0.16%   |
| 1800    | 4         | 0.16%   |
| 1066    | 4         | 0.16%   |
| 4266    | 3         | 0.12%   |
| 3400    | 3         | 0.12%   |
| 3866    | 2         | 0.08%   |
| 3466    | 2         | 0.08%   |
| 3066    | 2         | 0.08%   |
| 2933    | 2         | 0.08%   |
| 1648    | 2         | 0.08%   |
| 1400    | 2         | 0.08%   |
| 533     | 2         | 0.08%   |
| 5600    | 1         | 0.04%   |
| 5200    | 1         | 0.04%   |
| 3666    | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 20        | 42.55%  |
| Seiko Epson         | 11        | 23.4%   |
| Canon               | 8         | 17.02%  |
| Brother Industries  | 4         | 8.51%   |
| STMicroelectronics  | 1         | 2.13%   |
| Samsung Electronics | 1         | 2.13%   |
| Ricoh               | 1         | 2.13%   |
| Konica Minolta      | 1         | 2.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                                      | 6         | 12.77%  |
| HP Ink Tank 310 series                                                | 3         | 6.38%   |
| Seiko Epson L380 Series                                               | 2         | 4.26%   |
| HP DeskJet 2130 series                                                | 2         | 4.26%   |
| HP DeskJet 1110 series                                                | 2         | 4.26%   |
| Canon PIXMA MG2500 Series                                             | 2         | 4.26%   |
| Canon LBP2900                                                         | 2         | 4.26%   |
| STMicroelectronics USB Printer P                                      | 1         | 2.13%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                                 | 1         | 2.13%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 2.13%   |
| Seiko Epson M100 Series                                               | 1         | 2.13%   |
| Seiko Epson L405 Series                                               | 1         | 2.13%   |
| Seiko Epson L3200 Series                                              | 1         | 2.13%   |
| Seiko Epson L3110 Series                                              | 1         | 2.13%   |
| Seiko Epson L220 Series                                               | 1         | 2.13%   |
| Seiko Epson L132 Series                                               | 1         | 2.13%   |
| Seiko Epson ET-2710 Series                                            | 1         | 2.13%   |
| Samsung ML-1640 Series Laser Printer                                  | 1         | 2.13%   |
| Ricoh SP 112SU                                                        | 1         | 2.13%   |
| Konica Minolta 206                                                    | 1         | 2.13%   |
| HP Smart Install                                                      | 1         | 2.13%   |
| HP Printing Support                                                   | 1         | 2.13%   |
| HP LaserJet Professional P1566                                        | 1         | 2.13%   |
| HP LaserJet Pro M201dw                                                | 1         | 2.13%   |
| HP DeskJet 3630 series                                                | 1         | 2.13%   |
| HP DeskJet 2620 All-in-One Printer                                    | 1         | 2.13%   |
| HP Deskjet 1510                                                       | 1         | 2.13%   |
| Canon PIXMA MP280                                                     | 1         | 2.13%   |
| Canon PIXMA MP190                                                     | 1         | 2.13%   |
| Canon MF4800 Series                                                   | 1         | 2.13%   |
| Canon G2000 series                                                    | 1         | 2.13%   |
| Brother Printer                                                       | 1         | 2.13%   |
| Brother HL-L2320D series                                              | 1         | 2.13%   |
| Brother DCP-T510W                                                     | 1         | 2.13%   |
| Brother DCP-T310                                                      | 1         | 2.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 75%     |
| Seiko Epson     | 1         | 12.5%   |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                     | 5         | 62.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 12.5%   |
| HP ScanJet 2200c                            | 1         | 12.5%   |
| Canon CanoScan LiDE 120                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 589       | 18.48%  |
| IMC Networks                           | 458       | 14.37%  |
| Realtek Semiconductor                  | 324       | 10.17%  |
| Microdia                               | 318       | 9.98%   |
| Quanta                                 | 210       | 6.59%   |
| Sunplus Innovation Technology          | 186       | 5.84%   |
| Cheng Uei Precision Industry (Foxlink) | 154       | 4.83%   |
| Syntek                                 | 124       | 3.89%   |
| Bison Electronics                      | 124       | 3.89%   |
| Suyin                                  | 120       | 3.77%   |
| Acer                                   | 87        | 2.73%   |
| Luxvisions Innotech Limited            | 75        | 2.35%   |
| Logitech                               | 67        | 2.1%    |
| Lite-On Technology                     | 58        | 1.82%   |
| Alcor Micro                            | 34        | 1.07%   |
| Sonix Technology                       | 27        | 0.85%   |
| Samsung Electronics                    | 25        | 0.78%   |
| Apple                                  | 24        | 0.75%   |
| Silicon Motion                         | 21        | 0.66%   |
| Ricoh                                  | 14        | 0.44%   |
| Lenovo                                 | 14        | 0.44%   |
| Importek                               | 12        | 0.38%   |
| Z-Star Microelectronics                | 10        | 0.31%   |
| Primax Electronics                     | 10        | 0.31%   |
| Unknown                                | 9         | 0.28%   |
| OmniVision Technologies                | 8         | 0.25%   |
| SunplusIT                              | 6         | 0.19%   |
| Microsoft                              | 6         | 0.19%   |
| GEMBIRD                                | 6         | 0.19%   |
| Arkmicro Technologies                  | 6         | 0.19%   |
| Intel                                  | 5         | 0.16%   |
| Pixart Imaging                         | 4         | 0.13%   |
| OPPO Electronics                       | 4         | 0.13%   |
| Cubeternet                             | 4         | 0.13%   |
| vivo                                   | 3         | 0.09%   |
| MSD                                    | 3         | 0.09%   |
| MacroSilicon                           | 3         | 0.09%   |
| Jieli Technology                       | 3         | 0.09%   |
| ValueHD                                | 2         | 0.06%   |
| Spreadtrum Communications              | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 164       | 5.14%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 150       | 4.7%    |
| Realtek Integrated_Webcam_HD                                   | 131       | 4.1%    |
| IMC Networks Integrated Camera                                 | 125       | 3.92%   |
| Chicony Integrated Camera                                      | 118       | 3.7%    |
| Sunplus Integrated_Webcam_HD                                   | 93        | 2.91%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 83        | 2.6%    |
| Syntek Integrated Camera                                       | 70        | 2.19%   |
| Realtek Integrated Webcam                                      | 60        | 1.88%   |
| Chicony HP Truevision HD camera                                | 60        | 1.88%   |
| Chicony HP Truevision HD                                       | 55        | 1.72%   |
| Chicony EasyCamera                                             | 48        | 1.5%    |
| Quanta HP TrueVision HD Camera                                 | 47        | 1.47%   |
| Chicony HD WebCam                                              | 46        | 1.44%   |
| Suyin HP TrueVision HD                                         | 40        | 1.25%   |
| Quanta HD User Facing                                          | 40        | 1.25%   |
| Logitech Webcam C270                                           | 39        | 1.22%   |
| Bison Integrated Camera                                        | 38        | 1.19%   |
| Acer Integrated Camera                                         | 34        | 1.07%   |
| Syntek EasyCamera                                              | 33        | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 33        | 1.03%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 31        | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 31        | 0.97%   |
| Quanta HP Wide Vision HD Camera                                | 30        | 0.94%   |
| Chicony HP Wide Vision HD Camera                               | 29        | 0.91%   |
| Chicony HD User Facing                                         | 29        | 0.91%   |
| Lite-On Integrated Camera                                      | 26        | 0.81%   |
| IMC Networks HP TrueVision HD Camera                           | 26        | 0.81%   |
| Samsung Galaxy A5 (MTP)                                        | 25        | 0.78%   |
| Suyin Integrated_Webcam_HD                                     | 24        | 0.75%   |
| Sonix USB2.0 HD UVC WebCam                                     | 23        | 0.72%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 23        | 0.72%   |
| Microdia Integrated Webcam                                     | 23        | 0.72%   |
| Realtek EasyCamera                                             | 22        | 0.69%   |
| Quanta VGA WebCam                                              | 21        | 0.66%   |
| Quanta HD Webcam                                               | 20        | 0.63%   |
| Luxvisions Innotech Limited Integrated Camera                  | 20        | 0.63%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 20        | 0.63%   |
| Chicony Integrated Camera (1280x720@30)                        | 20        | 0.63%   |
| Bison SunplusIT Integrated Camera                              | 19        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 179       | 30.86%  |
| Synaptics                          | 131       | 22.59%  |
| Shenzhen Goodix Technology         | 125       | 21.55%  |
| Elan Microelectronics              | 86        | 14.83%  |
| LighTuning Technology              | 21        | 3.62%   |
| AuthenTec                          | 12        | 2.07%   |
| Upek                               | 10        | 1.72%   |
| Realtek USB2.0 Finger Print Bridge | 7         | 1.21%   |
| Focal-systems.Corp                 | 6         | 1.03%   |
| STMicroelectronics                 | 1         | 0.17%   |
| Futronic Technology                | 1         | 0.17%   |
| DigitalPersona                     | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 67        | 11.55%  |
| Elan ELAN:ARM-M4                                                           | 53        | 9.14%   |
| Shenzhen Goodix Fingerprint Reader                                         | 52        | 8.97%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 48        | 8.28%   |
| Elan ELAN:Fingerprint                                                      | 30        | 5.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 25        | 4.31%   |
| Synaptics WBDI                                                             | 25        | 4.31%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 4.14%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 23        | 3.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 3.62%   |
| Synaptics UWP WBDI                                                         | 19        | 3.28%   |
| Synaptics  WBDI                                                            | 19        | 3.28%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 2.93%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 14        | 2.41%   |
| Validity Sensors VFS491                                                    | 11        | 1.9%    |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 1.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 1.9%    |
| Validity Sensors Synaptics WBDI                                            | 9         | 1.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 1.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.21%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 7         | 1.21%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.03%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.03%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 1.03%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 6         | 1.03%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 0.86%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 0.86%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.69%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 0.69%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 3         | 0.52%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.34%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 0.34%   |
| AuthenTec AES2810                                                          | 2         | 0.34%   |
| AuthenTec AES1600                                                          | 2         | 0.34%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.17%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.17%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 61        | 63.54%  |
| Alcor Micro           | 19        | 19.79%  |
| Upek                  | 8         | 8.33%   |
| O2 Micro              | 3         | 3.13%   |
| Lenovo                | 3         | 3.13%   |
| Gemalto (was Gemplus) | 1         | 1.04%   |
| Clay Logic            | 1         | 1.04%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 22.68%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 19.59%  |
| Broadcom 5880                                                                | 17        | 17.53%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 13.4%   |
| Broadcom 58200                                                               | 10        | 10.31%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 8.25%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.06%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.03%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.03%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 1.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2922      | 67.17%  |
| 1     | 1192      | 27.4%   |
| 2     | 188       | 4.32%   |
| 3     | 26        | 0.6%    |
| 4     | 13        | 0.3%    |
| 5     | 6         | 0.14%   |
| 9     | 2         | 0.05%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 575       | 34.27%  |
| Graphics card            | 392       | 23.36%  |
| Net/wireless             | 263       | 15.67%  |
| Chipcard                 | 92        | 5.48%   |
| Bluetooth                | 84        | 5.01%   |
| Multimedia controller    | 77        | 4.59%   |
| Communication controller | 55        | 3.28%   |
| Camera                   | 51        | 3.04%   |
| Net/ethernet             | 23        | 1.37%   |
| Sound                    | 20        | 1.19%   |
| Storage                  | 12        | 0.72%   |
| Unassigned class         | 9         | 0.54%   |
| Network                  | 9         | 0.54%   |
| Modem                    | 7         | 0.42%   |
| Card reader              | 5         | 0.3%    |
| Storage/raid             | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ide              | 1         | 0.06%   |
| Firewire controller      | 1         | 0.06%   |

