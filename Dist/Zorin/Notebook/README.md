Zorin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 7227

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 640 G1              | [d6e43bba74](https://linux-hardware.org/?probe=d6e43bba74) | Jan 06, 2025 |
| HP            | ProBook 640 G1              | [7b033a8375](https://linux-hardware.org/?probe=7b033a8375) | Jan 06, 2025 |
| Lenovo        | IdeaPad Z400 VIWZ1          | [516947871e](https://linux-hardware.org/?probe=516947871e) | Jan 05, 2025 |
| ASUSTek       | K93SV                       | [01d0efaf46](https://linux-hardware.org/?probe=01d0efaf46) | Jan 05, 2025 |
| Acer          | TravelMate 5210             | [379e44855f](https://linux-hardware.org/?probe=379e44855f) | Jan 05, 2025 |
| Dell          | Inspiron N4050              | [6da56634e0](https://linux-hardware.org/?probe=6da56634e0) | Jan 05, 2025 |
| Acer          | Aspire 5750G                | [68404201a9](https://linux-hardware.org/?probe=68404201a9) | Jan 05, 2025 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [4a2cbc9a5c](https://linux-hardware.org/?probe=4a2cbc9a5c) | Jan 05, 2025 |
| Sony          | SVF15213CBW                 | [2a3349eb69](https://linux-hardware.org/?probe=2a3349eb69) | Jan 04, 2025 |
| HP            | EliteBook 840 G2            | [69146beeeb](https://linux-hardware.org/?probe=69146beeeb) | Jan 04, 2025 |
| Dell          | Inspiron 5566               | [9653ac70bc](https://linux-hardware.org/?probe=9653ac70bc) | Jan 04, 2025 |
| Dell          | Vostro 3420                 | [03772e7414](https://linux-hardware.org/?probe=03772e7414) | Jan 03, 2025 |
| Avell High... | Avell G1513 MUV / A52 MU... | [ca3162cf4a](https://linux-hardware.org/?probe=ca3162cf4a) | Jan 03, 2025 |
| Sony          | VGN-CR21S_W                 | [29a2c1f90e](https://linux-hardware.org/?probe=29a2c1f90e) | Jan 03, 2025 |
| HP            | Notebook                    | [b50d5a2974](https://linux-hardware.org/?probe=b50d5a2974) | Jan 03, 2025 |
| Toshiba       | Satellite C660              | [0767070a44](https://linux-hardware.org/?probe=0767070a44) | Jan 03, 2025 |
| Lenovo        | ThinkPad T430 2349H2G       | [afcca700da](https://linux-hardware.org/?probe=afcca700da) | Jan 03, 2025 |
| HP            | ProBook 445 G7              | [8e56333050](https://linux-hardware.org/?probe=8e56333050) | Jan 03, 2025 |
| HP            | EliteBook 840 G2            | [bb8d0a325f](https://linux-hardware.org/?probe=bb8d0a325f) | Jan 02, 2025 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [b58899eb8b](https://linux-hardware.org/?probe=b58899eb8b) | Jan 02, 2025 |
| Sony          | VGN-CS11Z_T                 | [28f8386e8f](https://linux-hardware.org/?probe=28f8386e8f) | Jan 01, 2025 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [eeb85155e5](https://linux-hardware.org/?probe=eeb85155e5) | Jan 01, 2025 |
| HP            | TouchSmart tm2              | [1750c192e9](https://linux-hardware.org/?probe=1750c192e9) | Jan 01, 2025 |
| Apple         | MacBookAir6,2               | [47b07545df](https://linux-hardware.org/?probe=47b07545df) | Dec 31, 2024 |
| Dell          | Latitude E6410              | [ce431d6def](https://linux-hardware.org/?probe=ce431d6def) | Dec 31, 2024 |
| Dell          | Latitude E6410              | [e5ad6fdba6](https://linux-hardware.org/?probe=e5ad6fdba6) | Dec 31, 2024 |
| Dell          | Inspiron N4050              | [5c2b2c9c8f](https://linux-hardware.org/?probe=5c2b2c9c8f) | Dec 31, 2024 |
| Lenovo        | ThinkPad Edge 0301FFG       | [526994e0a4](https://linux-hardware.org/?probe=526994e0a4) | Dec 31, 2024 |
| Dell          | Inspiron 7520               | [f60d84588c](https://linux-hardware.org/?probe=f60d84588c) | Dec 31, 2024 |
| HP            | ProBook 4540s               | [9bbe0a3b71](https://linux-hardware.org/?probe=9bbe0a3b71) | Dec 31, 2024 |
| Dell          | Vostro 1500                 | [b5ecc28563](https://linux-hardware.org/?probe=b5ecc28563) | Dec 31, 2024 |
| Toshiba       | Satellite C75D-B            | [728de620aa](https://linux-hardware.org/?probe=728de620aa) | Dec 31, 2024 |
| Lenovo        | ThinkPad T500 2241WKY       | [7b16eb5229](https://linux-hardware.org/?probe=7b16eb5229) | Dec 30, 2024 |
| HP            | 470 G8 Notebook PC          | [a14600050a](https://linux-hardware.org/?probe=a14600050a) | Dec 30, 2024 |
| Dell          | Latitude E7270              | [45d3b8797a](https://linux-hardware.org/?probe=45d3b8797a) | Dec 30, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [6d09d6c124](https://linux-hardware.org/?probe=6d09d6c124) | Dec 30, 2024 |
| ASUSTek       | N56JK                       | [d1c6ca3f72](https://linux-hardware.org/?probe=d1c6ca3f72) | Dec 29, 2024 |
| ASUSTek       | N56JK                       | [0114b99957](https://linux-hardware.org/?probe=0114b99957) | Dec 29, 2024 |
| Lenovo        | ThinkPad T460 20FN004CMN    | [c918606381](https://linux-hardware.org/?probe=c918606381) | Dec 29, 2024 |
| MSI           | GT72 2QD                    | [c8a2b702aa](https://linux-hardware.org/?probe=c8a2b702aa) | Dec 29, 2024 |
| Lenovo        | G585 20137                  | [28c0d1589f](https://linux-hardware.org/?probe=28c0d1589f) | Dec 28, 2024 |
| Lenovo        | G585 20137                  | [77d7e4f41b](https://linux-hardware.org/?probe=77d7e4f41b) | Dec 28, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [4d428ff2fd](https://linux-hardware.org/?probe=4d428ff2fd) | Dec 28, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [fd2a217520](https://linux-hardware.org/?probe=fd2a217520) | Dec 28, 2024 |
| Dell          | Latitude E4300              | [0c340c7391](https://linux-hardware.org/?probe=0c340c7391) | Dec 28, 2024 |
| GPD           | G1618-04                    | [f9fccc3291](https://linux-hardware.org/?probe=f9fccc3291) | Dec 28, 2024 |
| Acer          | Aspire 5750G                | [39cfeac033](https://linux-hardware.org/?probe=39cfeac033) | Dec 28, 2024 |
| Acer          | Aspire 5750G                | [ffcb19aa37](https://linux-hardware.org/?probe=ffcb19aa37) | Dec 28, 2024 |
| Lenovo        | ThinkPad T520 42424UU       | [b4a2895025](https://linux-hardware.org/?probe=b4a2895025) | Dec 28, 2024 |
| Toshiba       | Satellite P300              | [3174fc3f7e](https://linux-hardware.org/?probe=3174fc3f7e) | Dec 27, 2024 |
| Lenovo        | ThinkPad T420 418062U       | [f06b701043](https://linux-hardware.org/?probe=f06b701043) | Dec 27, 2024 |
| Dell          | Latitude E4300              | [e00b4f8165](https://linux-hardware.org/?probe=e00b4f8165) | Dec 27, 2024 |
| Lenovo        | V15 G2 ITL 82ME             | [4c710eefac](https://linux-hardware.org/?probe=4c710eefac) | Dec 27, 2024 |
| ASUSTek       | GL552VW                     | [dcb25941f6](https://linux-hardware.org/?probe=dcb25941f6) | Dec 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6d267dc1e6](https://linux-hardware.org/?probe=6d267dc1e6) | Dec 27, 2024 |
| Fujitsu Si... | LIFEBOOK S7220              | [7aa92e6daf](https://linux-hardware.org/?probe=7aa92e6daf) | Dec 27, 2024 |
| Medion        | ERAZER X7853 MD60603        | [9c5d2630f6](https://linux-hardware.org/?probe=9c5d2630f6) | Dec 27, 2024 |
| Acer          | Aspire E1-571G              | [6da76de24e](https://linux-hardware.org/?probe=6da76de24e) | Dec 27, 2024 |
| Fujitsu Si... | LIFEBOOK S7220              | [2f65653f5c](https://linux-hardware.org/?probe=2f65653f5c) | Dec 27, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [4bfed8719e](https://linux-hardware.org/?probe=4bfed8719e) | Dec 27, 2024 |
| Lenovo        | ThinkPad T520 42424UU       | [5de1acb22e](https://linux-hardware.org/?probe=5de1acb22e) | Dec 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | [32b3387f38](https://linux-hardware.org/?probe=32b3387f38) | Dec 26, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | [ce3b8aa0e6](https://linux-hardware.org/?probe=ce3b8aa0e6) | Dec 26, 2024 |
| Dell          | Latitude 14 Rugged (5404... | [ff70c71f76](https://linux-hardware.org/?probe=ff70c71f76) | Dec 26, 2024 |
| ASUSTek       | X455LD                      | [0695dcd803](https://linux-hardware.org/?probe=0695dcd803) | Dec 26, 2024 |
| Dell          | Latitude 5480               | [a43c9feb6e](https://linux-hardware.org/?probe=a43c9feb6e) | Dec 26, 2024 |
| Dell          | Latitude 5480               | [b0b2a919ce](https://linux-hardware.org/?probe=b0b2a919ce) | Dec 25, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b127afa2e4](https://linux-hardware.org/?probe=b127afa2e4) | Dec 25, 2024 |
| Dell          | Precision M6800             | [7d37225503](https://linux-hardware.org/?probe=7d37225503) | Dec 25, 2024 |
| Dell          | Precision M6800             | [d5733504f6](https://linux-hardware.org/?probe=d5733504f6) | Dec 25, 2024 |
| Apple         | MacBookPro8,1               | [3bb45810a1](https://linux-hardware.org/?probe=3bb45810a1) | Dec 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1c4acdd4ee](https://linux-hardware.org/?probe=1c4acdd4ee) | Dec 24, 2024 |
| Lenovo        | ThinkPad T460s 20F90042G... | [d007cb01ec](https://linux-hardware.org/?probe=d007cb01ec) | Dec 24, 2024 |
| Acer          | Nitro AN515-54              | [1205a81135](https://linux-hardware.org/?probe=1205a81135) | Dec 23, 2024 |
| Intel         | HM87                        | [06e9957440](https://linux-hardware.org/?probe=06e9957440) | Dec 23, 2024 |
| Teclast       | F6 Plus                     | [143094aa18](https://linux-hardware.org/?probe=143094aa18) | Dec 23, 2024 |
| Notebook      | W35xSTQ_370ST               | [ec6c6385d5](https://linux-hardware.org/?probe=ec6c6385d5) | Dec 23, 2024 |
| Acer          | Nitro AN515-54              | [d6756e38c9](https://linux-hardware.org/?probe=d6756e38c9) | Dec 23, 2024 |
| Dell          | Latitude E4300              | [cfcc3cbd9f](https://linux-hardware.org/?probe=cfcc3cbd9f) | Dec 23, 2024 |
| Dell          | Latitude E4300              | [e67d828b77](https://linux-hardware.org/?probe=e67d828b77) | Dec 23, 2024 |
| HP            | Laptop 14-cf2xxx            | [253b2b9f9f](https://linux-hardware.org/?probe=253b2b9f9f) | Dec 23, 2024 |
| Samsung       | R530/R730/P530              | [2c69e47fef](https://linux-hardware.org/?probe=2c69e47fef) | Dec 23, 2024 |
| Samsung       | R530/R730/P530              | [86fbdd5542](https://linux-hardware.org/?probe=86fbdd5542) | Dec 23, 2024 |
| Samsung       | 700G7A                      | [0f56340187](https://linux-hardware.org/?probe=0f56340187) | Dec 23, 2024 |
| Acer          | Aspire F5-573G              | [b5e37804c4](https://linux-hardware.org/?probe=b5e37804c4) | Dec 23, 2024 |
| Acer          | Aspire F5-573G              | [29bad5d443](https://linux-hardware.org/?probe=29bad5d443) | Dec 23, 2024 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [119c51368a](https://linux-hardware.org/?probe=119c51368a) | Dec 22, 2024 |
| Fujitsu       | LIFEBOOK A532               | [188aa532e9](https://linux-hardware.org/?probe=188aa532e9) | Dec 22, 2024 |
| Lenovo        | ThinkPad L540 20AUS02U00    | [b1e76585dc](https://linux-hardware.org/?probe=b1e76585dc) | Dec 21, 2024 |
| HP            | EliteBook 850 G5            | [e54906d193](https://linux-hardware.org/?probe=e54906d193) | Dec 21, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [d1d487fe68](https://linux-hardware.org/?probe=d1d487fe68) | Dec 21, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [8adc47d05f](https://linux-hardware.org/?probe=8adc47d05f) | Dec 21, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | [df6f512e3a](https://linux-hardware.org/?probe=df6f512e3a) | Dec 21, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | [7c430caf94](https://linux-hardware.org/?probe=7c430caf94) | Dec 21, 2024 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [69da2b0a14](https://linux-hardware.org/?probe=69da2b0a14) | Dec 20, 2024 |
| HUAWEI        | HN-WX9X                     | [2b2541ddf3](https://linux-hardware.org/?probe=2b2541ddf3) | Dec 20, 2024 |
| HUAWEI        | HN-WX9X                     | [7749a94f08](https://linux-hardware.org/?probe=7749a94f08) | Dec 20, 2024 |
| Fujitsu       | LIFEBOOK U727               | [b08ef8f5a1](https://linux-hardware.org/?probe=b08ef8f5a1) | Dec 20, 2024 |
| Dell          | Latitude 7420               | [754cef3d2f](https://linux-hardware.org/?probe=754cef3d2f) | Dec 20, 2024 |
| Acer          | Nitro AN517-52              | [4233b4277f](https://linux-hardware.org/?probe=4233b4277f) | Dec 20, 2024 |
| HP            | 15 Notebook PC              | [1d68c69eaf](https://linux-hardware.org/?probe=1d68c69eaf) | Dec 20, 2024 |
| Dell          | Latitude 5420 Rugged        | [5850f01900](https://linux-hardware.org/?probe=5850f01900) | Dec 19, 2024 |
| HP            | ProBook 640 G1              | [7c92813622](https://linux-hardware.org/?probe=7c92813622) | Dec 19, 2024 |
| Panasonic     | CF-31WFL52CM                | [566d39243d](https://linux-hardware.org/?probe=566d39243d) | Dec 18, 2024 |
| Proline       | V14664P                     | [3e422abecf](https://linux-hardware.org/?probe=3e422abecf) | Dec 18, 2024 |
| Lenovo        | S10-3                       | [3ba705e8e3](https://linux-hardware.org/?probe=3ba705e8e3) | Dec 18, 2024 |
| Unknown       | Unknown                     | [a1f0651a5b](https://linux-hardware.org/?probe=a1f0651a5b) | Dec 18, 2024 |
| Unknown       | Unknown                     | [f149e767ce](https://linux-hardware.org/?probe=f149e767ce) | Dec 18, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [837d0f44f3](https://linux-hardware.org/?probe=837d0f44f3) | Dec 17, 2024 |
| HP            | Laptop 15-bw0xx             | [3f960b1f4e](https://linux-hardware.org/?probe=3f960b1f4e) | Dec 17, 2024 |
| HP            | ProBook 450 G3              | [4f8f97ac4c](https://linux-hardware.org/?probe=4f8f97ac4c) | Dec 17, 2024 |
| HP            | Laptop 15-bw0xx             | [3c1c1b71e8](https://linux-hardware.org/?probe=3c1c1b71e8) | Dec 17, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [db89962085](https://linux-hardware.org/?probe=db89962085) | Dec 17, 2024 |
| Lenovo        | ThinkPad T570 20H90002RI    | [a1ff05a59d](https://linux-hardware.org/?probe=a1ff05a59d) | Dec 16, 2024 |
| HP            | ProBook 450 G6              | [74781357e5](https://linux-hardware.org/?probe=74781357e5) | Dec 16, 2024 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [6501a529f5](https://linux-hardware.org/?probe=6501a529f5) | Dec 16, 2024 |
| Dell          | Latitude 5490               | [e8d767b8cb](https://linux-hardware.org/?probe=e8d767b8cb) | Dec 16, 2024 |
| Toshiba       | Satellite A110              | [1d2307c817](https://linux-hardware.org/?probe=1d2307c817) | Dec 16, 2024 |
| Toshiba       | Satellite C50-A             | [9926e0ee70](https://linux-hardware.org/?probe=9926e0ee70) | Dec 15, 2024 |
| Toshiba       | Satellite P55-A             | [d54a3b360d](https://linux-hardware.org/?probe=d54a3b360d) | Dec 15, 2024 |
| Acer          | Aspire A315-34              | [6c8d585d0b](https://linux-hardware.org/?probe=6c8d585d0b) | Dec 15, 2024 |
| Apple         | MacBookPro12,1              | [612e52e652](https://linux-hardware.org/?probe=612e52e652) | Dec 14, 2024 |
| ASUSTek       | K54HR                       | [b839a0b9cf](https://linux-hardware.org/?probe=b839a0b9cf) | Dec 14, 2024 |
| ASUSTek       | K54HR                       | [9d14a14655](https://linux-hardware.org/?probe=9d14a14655) | Dec 14, 2024 |
| Dell          | Latitude E6420              | [6d4d0b3ad2](https://linux-hardware.org/?probe=6d4d0b3ad2) | Dec 14, 2024 |
| Lenovo        | G50-30 80G0                 | [5720b04708](https://linux-hardware.org/?probe=5720b04708) | Dec 13, 2024 |
| HP            | ProBook 445 14 inch G9 N... | [2b25226ef6](https://linux-hardware.org/?probe=2b25226ef6) | Dec 13, 2024 |
| Lenovo        | G50-30 80G0                 | [7c957f114c](https://linux-hardware.org/?probe=7c957f114c) | Dec 13, 2024 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [5a6473c245](https://linux-hardware.org/?probe=5a6473c245) | Dec 13, 2024 |
| Acer          | Aspire 5552                 | [1a998c8df4](https://linux-hardware.org/?probe=1a998c8df4) | Dec 13, 2024 |
| Dell          | Latitude E6430              | [200bed6a55](https://linux-hardware.org/?probe=200bed6a55) | Dec 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [c22f3c5d77](https://linux-hardware.org/?probe=c22f3c5d77) | Dec 12, 2024 |
| Dell          | Latitude E7440              | [f3ae8893e1](https://linux-hardware.org/?probe=f3ae8893e1) | Dec 12, 2024 |
| HP            | Laptop 15-fd0xxx            | [642094775c](https://linux-hardware.org/?probe=642094775c) | Dec 11, 2024 |
| Fujitsu       | LIFEBOOK E744               | [87de375a5f](https://linux-hardware.org/?probe=87de375a5f) | Dec 11, 2024 |
| Lenovo        | ThinkPad T590 20N5S56P00    | [3112d3b106](https://linux-hardware.org/?probe=3112d3b106) | Dec 11, 2024 |
| HP            | Laptop 15-fc0xxx            | [496d906ed4](https://linux-hardware.org/?probe=496d906ed4) | Dec 11, 2024 |
| Google        | Caroline                    | [cdad48b614](https://linux-hardware.org/?probe=cdad48b614) | Dec 11, 2024 |
| Gateway       | NE56R                       | [cefc202761](https://linux-hardware.org/?probe=cefc202761) | Dec 10, 2024 |
| HP            | Laptop 15-dw0xxx            | [a331c3b846](https://linux-hardware.org/?probe=a331c3b846) | Dec 10, 2024 |
| Acer          | TravelMate 7740G            | [6a53c529c4](https://linux-hardware.org/?probe=6a53c529c4) | Dec 10, 2024 |
| Fujitsu       | FMVA30DN                    | [b859d288a9](https://linux-hardware.org/?probe=b859d288a9) | Dec 10, 2024 |
| HP            | Pavilion g4                 | [be7deb3d00](https://linux-hardware.org/?probe=be7deb3d00) | Dec 10, 2024 |
| Apple         | MacBookPro6,2               | [b632a4d566](https://linux-hardware.org/?probe=b632a4d566) | Dec 10, 2024 |
| HP            | Pavilion g7                 | [3594243010](https://linux-hardware.org/?probe=3594243010) | Dec 09, 2024 |
| Dell          | Vostro 3400                 | [8280df7254](https://linux-hardware.org/?probe=8280df7254) | Dec 09, 2024 |
| Dell          | Vostro 3400                 | [9865d823ab](https://linux-hardware.org/?probe=9865d823ab) | Dec 09, 2024 |
| ASUSTek       | X555UB                      | [48b994930e](https://linux-hardware.org/?probe=48b994930e) | Dec 09, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [32b4864422](https://linux-hardware.org/?probe=32b4864422) | Dec 09, 2024 |
| Lenovo        | ThinkPad T430 2342CTO       | [1da6908bf8](https://linux-hardware.org/?probe=1da6908bf8) | Dec 07, 2024 |
| Fujitsu       | LIFEBOOK A532               | [1a8413b8c1](https://linux-hardware.org/?probe=1a8413b8c1) | Dec 07, 2024 |
| Google        | Caroline                    | [6a386f12ab](https://linux-hardware.org/?probe=6a386f12ab) | Dec 07, 2024 |
| Lenovo        | 100e 2nd Gen 82GJ           | [8171e07097](https://linux-hardware.org/?probe=8171e07097) | Dec 07, 2024 |
| Lenovo        | ThinkPad T430s 23539WU      | [3994091726](https://linux-hardware.org/?probe=3994091726) | Dec 07, 2024 |
| HP            | ENVY TS 15                  | [bc0ded78ae](https://linux-hardware.org/?probe=bc0ded78ae) | Dec 07, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [95f2f887d0](https://linux-hardware.org/?probe=95f2f887d0) | Dec 06, 2024 |
| PC Special... | Recoil VIII 17              | [bf09f105dc](https://linux-hardware.org/?probe=bf09f105dc) | Dec 06, 2024 |
| Toshiba       | Satellite C50-A             | [51c09a7ff2](https://linux-hardware.org/?probe=51c09a7ff2) | Dec 06, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [e2dc32e766](https://linux-hardware.org/?probe=e2dc32e766) | Dec 06, 2024 |
| HP            | Pavilion 17                 | [0ca43719ed](https://linux-hardware.org/?probe=0ca43719ed) | Dec 06, 2024 |
| Dell          | Inspiron 3543               | [b2ee97d3d8](https://linux-hardware.org/?probe=b2ee97d3d8) | Dec 05, 2024 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [b0508a61eb](https://linux-hardware.org/?probe=b0508a61eb) | Dec 05, 2024 |
| HP            | Pavilion g4                 | [bb26b30a98](https://linux-hardware.org/?probe=bb26b30a98) | Dec 05, 2024 |
| Acer          | Aspire 8940G                | [e2dceeb6db](https://linux-hardware.org/?probe=e2dceeb6db) | Dec 05, 2024 |
| MSI           | GF63 Thin 10SCXR            | [8c3060eca2](https://linux-hardware.org/?probe=8c3060eca2) | Dec 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [cfdba4136a](https://linux-hardware.org/?probe=cfdba4136a) | Dec 04, 2024 |
| Acer          | Aspire 5736Z                | [0ad38979a9](https://linux-hardware.org/?probe=0ad38979a9) | Dec 04, 2024 |
| Lenovo        | G580 2689K9G                | [7ebd98750f](https://linux-hardware.org/?probe=7ebd98750f) | Dec 04, 2024 |
| ASUSTek       | K53SC                       | [b7850939a4](https://linux-hardware.org/?probe=b7850939a4) | Dec 04, 2024 |
| Timi          | Mi NoteBook Ultra           | [12e0599060](https://linux-hardware.org/?probe=12e0599060) | Dec 04, 2024 |
| Apple         | MacBookPro7,1               | [c3faa55c34](https://linux-hardware.org/?probe=c3faa55c34) | Dec 04, 2024 |
| Lenovo        | Y50-70 20378                | [c70be6f167](https://linux-hardware.org/?probe=c70be6f167) | Dec 04, 2024 |
| MSI           | Prestige 16 A13UCX          | [3c4cfbe0c2](https://linux-hardware.org/?probe=3c4cfbe0c2) | Dec 04, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | [e292db7a28](https://linux-hardware.org/?probe=e292db7a28) | Dec 04, 2024 |
| HP            | ENVY Laptop 16-h1xxx        | [de8e216552](https://linux-hardware.org/?probe=de8e216552) | Dec 04, 2024 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [7f5a0eea32](https://linux-hardware.org/?probe=7f5a0eea32) | Dec 03, 2024 |
| Apple         | MacBookPro7,1               | [a806223e92](https://linux-hardware.org/?probe=a806223e92) | Dec 03, 2024 |
| Dell          | Inspiron 5759               | [9ca3f31d64](https://linux-hardware.org/?probe=9ca3f31d64) | Dec 03, 2024 |
| Intel Clie... | LAPBC710                    | [e603037ba8](https://linux-hardware.org/?probe=e603037ba8) | Dec 03, 2024 |
| Toshiba       | Satellite C660D             | [ae20ba1091](https://linux-hardware.org/?probe=ae20ba1091) | Dec 03, 2024 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [bda3d5d09a](https://linux-hardware.org/?probe=bda3d5d09a) | Dec 03, 2024 |
| Acer          | Aspire 8940G                | [b2a2802135](https://linux-hardware.org/?probe=b2a2802135) | Dec 02, 2024 |
| HP            | Pavilion g4                 | [42bd25b20f](https://linux-hardware.org/?probe=42bd25b20f) | Dec 02, 2024 |
| Dell          | Latitude 3420               | [bfa6a73c30](https://linux-hardware.org/?probe=bfa6a73c30) | Dec 02, 2024 |
| Dell          | Inspiron 3421               | [e5ed2eb5d8](https://linux-hardware.org/?probe=e5ed2eb5d8) | Dec 02, 2024 |
| HP            | ENVY dv6                    | [4540e135f3](https://linux-hardware.org/?probe=4540e135f3) | Dec 02, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [f660d8c779](https://linux-hardware.org/?probe=f660d8c779) | Dec 02, 2024 |
| Unknown       | YEPBOOK PRO                 | [a3393a26e8](https://linux-hardware.org/?probe=a3393a26e8) | Dec 01, 2024 |
| Apple         | MacBookPro9,1               | [b618babdf5](https://linux-hardware.org/?probe=b618babdf5) | Dec 01, 2024 |
| Dell          | Inspiron 13-5368            | [5f256e8e33](https://linux-hardware.org/?probe=5f256e8e33) | Dec 01, 2024 |
| Dell          | Latitude 5420               | [5002efd6a5](https://linux-hardware.org/?probe=5002efd6a5) | Dec 01, 2024 |
| Toshiba       | Satellite M840              | [63307beb47](https://linux-hardware.org/?probe=63307beb47) | Dec 01, 2024 |
| HP            | ProBook 6560b               | [a7224d17ca](https://linux-hardware.org/?probe=a7224d17ca) | Dec 01, 2024 |
| Dell          | Inspiron 11-3168            | [90456d790c](https://linux-hardware.org/?probe=90456d790c) | Dec 01, 2024 |
| Dell          | Inspiron 11-3168            | [35b3881cdb](https://linux-hardware.org/?probe=35b3881cdb) | Dec 01, 2024 |
| Apple         | MacBookAir6,2               | [95e149cabd](https://linux-hardware.org/?probe=95e149cabd) | Dec 01, 2024 |
| Lenovo        | ThinkPad T570 20H90002RI    | [9235c47547](https://linux-hardware.org/?probe=9235c47547) | Dec 01, 2024 |
| Alienware     | 17                          | [feba90fb9d](https://linux-hardware.org/?probe=feba90fb9d) | Nov 30, 2024 |
| LG Electro... | 17Z90R-G.AA77G              | [63b72a5f86](https://linux-hardware.org/?probe=63b72a5f86) | Nov 30, 2024 |
| Lenovo        | ThinkPad T460s 20F90042G... | [4b13d3f5ba](https://linux-hardware.org/?probe=4b13d3f5ba) | Nov 30, 2024 |
| Dell          | Vostro 3525                 | [e4ebed04a3](https://linux-hardware.org/?probe=e4ebed04a3) | Nov 30, 2024 |
| Apple         | MacBookPro5,5               | [a42179c4b6](https://linux-hardware.org/?probe=a42179c4b6) | Nov 30, 2024 |
| Dell          | Latitude E5400              | [64f3a906c9](https://linux-hardware.org/?probe=64f3a906c9) | Nov 29, 2024 |
| XIAOMI        | Redmi Book Pro 15 2023      | [7342faf26d](https://linux-hardware.org/?probe=7342faf26d) | Nov 29, 2024 |
| HP            | Laptop 15s-eq1xxx           | [3a04adcfd6](https://linux-hardware.org/?probe=3a04adcfd6) | Nov 29, 2024 |
| Dell          | Latitude E5430 non-vPro     | [f0a42c0331](https://linux-hardware.org/?probe=f0a42c0331) | Nov 29, 2024 |
| Dell          | Latitude 3420               | [d7a23c335f](https://linux-hardware.org/?probe=d7a23c335f) | Nov 29, 2024 |
| ASUSTek       | X541SA                      | [6e168a52c2](https://linux-hardware.org/?probe=6e168a52c2) | Nov 29, 2024 |
| Dell          | Latitude E5400              | [9c7aaedec7](https://linux-hardware.org/?probe=9c7aaedec7) | Nov 28, 2024 |
| Dell          | Precision M4800             | [c97548d58c](https://linux-hardware.org/?probe=c97548d58c) | Nov 28, 2024 |
| Dell          | Precision M4800             | [8cddfc2c38](https://linux-hardware.org/?probe=8cddfc2c38) | Nov 28, 2024 |
| Dell          | Precision M4800             | [932bc22167](https://linux-hardware.org/?probe=932bc22167) | Nov 28, 2024 |
| Toshiba       | Satellite S55-C             | [f2be068ec4](https://linux-hardware.org/?probe=f2be068ec4) | Nov 28, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [96a747160d](https://linux-hardware.org/?probe=96a747160d) | Nov 28, 2024 |
| Acer          | Aspire E5-521G              | [234e21b8b6](https://linux-hardware.org/?probe=234e21b8b6) | Nov 28, 2024 |
| Dell          | Inspiron 5570               | [d8fe08107c](https://linux-hardware.org/?probe=d8fe08107c) | Nov 27, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [97df382c2f](https://linux-hardware.org/?probe=97df382c2f) | Nov 27, 2024 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [70c8b6c941](https://linux-hardware.org/?probe=70c8b6c941) | Nov 27, 2024 |
| MSI           | MS-N014                     | [8f4f502803](https://linux-hardware.org/?probe=8f4f502803) | Nov 27, 2024 |
| ASUSTek       | Vivobook Go E1504GA_E150... | [ed20170ba7](https://linux-hardware.org/?probe=ed20170ba7) | Nov 27, 2024 |
| Medion        | P7812                       | [19f035bca6](https://linux-hardware.org/?probe=19f035bca6) | Nov 27, 2024 |
| Dell          | Latitude E5430 non-vPro     | [819377ad01](https://linux-hardware.org/?probe=819377ad01) | Nov 26, 2024 |
| HP            | 250 G7 Notebook PC          | [e3d6b07ecf](https://linux-hardware.org/?probe=e3d6b07ecf) | Nov 26, 2024 |
| MSI           | MS-N014                     | [789c4f8e10](https://linux-hardware.org/?probe=789c4f8e10) | Nov 26, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | [5dd1a2b1ec](https://linux-hardware.org/?probe=5dd1a2b1ec) | Nov 26, 2024 |
| Lenovo        | ThinkPad T430 2349LPG       | [c9caafc936](https://linux-hardware.org/?probe=c9caafc936) | Nov 26, 2024 |
| Teclast       | F15 Plus                    | [d3115c0e4f](https://linux-hardware.org/?probe=d3115c0e4f) | Nov 26, 2024 |
| HP            | EliteBook 840 G2            | [e7ffb651be](https://linux-hardware.org/?probe=e7ffb651be) | Nov 26, 2024 |
| HP            | Unknown                     | [cf8fe45f43](https://linux-hardware.org/?probe=cf8fe45f43) | Nov 26, 2024 |
| Alienware     | M15x                        | [6a413494a5](https://linux-hardware.org/?probe=6a413494a5) | Nov 26, 2024 |
| Unknown       | Unknown                     | [2800502e8a](https://linux-hardware.org/?probe=2800502e8a) | Nov 26, 2024 |
| Unknown       | Unknown                     | [e58584102b](https://linux-hardware.org/?probe=e58584102b) | Nov 26, 2024 |
| Dell          | Vostro 1510                 | [b7343f8cb8](https://linux-hardware.org/?probe=b7343f8cb8) | Nov 25, 2024 |
| HP            | Pavilion g6                 | [1e390a1633](https://linux-hardware.org/?probe=1e390a1633) | Nov 25, 2024 |
| HP            | ENVY Laptop 16-h1xxx        | [b575ef56e5](https://linux-hardware.org/?probe=b575ef56e5) | Nov 25, 2024 |
| ASUSTek       | X550CL                      | [4da2083b30](https://linux-hardware.org/?probe=4da2083b30) | Nov 25, 2024 |
| Dell          | Precision 5530              | [f03de6018a](https://linux-hardware.org/?probe=f03de6018a) | Nov 25, 2024 |
| Dell          | Latitude E6510              | [68f65df3f5](https://linux-hardware.org/?probe=68f65df3f5) | Nov 25, 2024 |
| Acer          | Aspire E5-521G              | [7a5907751e](https://linux-hardware.org/?probe=7a5907751e) | Nov 25, 2024 |
| Lenovo        | ThinkPad P51 20HJS1AM00     | [e40691b60f](https://linux-hardware.org/?probe=e40691b60f) | Nov 24, 2024 |
| HP            | ProBook 450 G8              | [7cffac8f5b](https://linux-hardware.org/?probe=7cffac8f5b) | Nov 24, 2024 |
| Lenovo        | G50-45 80E3                 | [1755731ed3](https://linux-hardware.org/?probe=1755731ed3) | Nov 24, 2024 |
| Lenovo        | ThinkPad T570 20H90002RI    | [d163c30bb6](https://linux-hardware.org/?probe=d163c30bb6) | Nov 24, 2024 |
| HP            | ProBook 450 G8              | [2d282337d2](https://linux-hardware.org/?probe=2d282337d2) | Nov 24, 2024 |
| Panasonic     | CF-30KTPJX2B                | [527ecd9958](https://linux-hardware.org/?probe=527ecd9958) | Nov 24, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [066e955a01](https://linux-hardware.org/?probe=066e955a01) | Nov 24, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | [50c436b911](https://linux-hardware.org/?probe=50c436b911) | Nov 24, 2024 |
| Jemper        | EZPAD WS_reserve            | [120200526f](https://linux-hardware.org/?probe=120200526f) | Nov 23, 2024 |
| Toshiba       | TECRA M10                   | [f2db588ac1](https://linux-hardware.org/?probe=f2db588ac1) | Nov 23, 2024 |
| HP            | 625                         | [b34c64fa81](https://linux-hardware.org/?probe=b34c64fa81) | Nov 23, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21HL... | [74baa5a8ae](https://linux-hardware.org/?probe=74baa5a8ae) | Nov 23, 2024 |
| HP            | Victus by Gaming Laptop ... | [a297024700](https://linux-hardware.org/?probe=a297024700) | Nov 23, 2024 |
| Exo           | Smart XL4                   | [b9367af1bd](https://linux-hardware.org/?probe=b9367af1bd) | Nov 23, 2024 |
| Exo           | Smart XL4                   | [264ffc04ec](https://linux-hardware.org/?probe=264ffc04ec) | Nov 23, 2024 |
| Toshiba       | Satellite L500              | [e84f351148](https://linux-hardware.org/?probe=e84f351148) | Nov 23, 2024 |
| ASUSTek       | Q550LF                      | [c909346ef8](https://linux-hardware.org/?probe=c909346ef8) | Nov 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [168a1bbabd](https://linux-hardware.org/?probe=168a1bbabd) | Nov 23, 2024 |
| MSI           | GF75 Thin 10UE              | [b6764cacc8](https://linux-hardware.org/?probe=b6764cacc8) | Nov 23, 2024 |
| Apple         | MacBookPro5,5               | [2ccd8e4d15](https://linux-hardware.org/?probe=2ccd8e4d15) | Nov 23, 2024 |
| Toshiba       | Satellite A200              | [11904bdfcd](https://linux-hardware.org/?probe=11904bdfcd) | Nov 22, 2024 |
| MSI           | GF75 Thin 10UE              | [90559a82e1](https://linux-hardware.org/?probe=90559a82e1) | Nov 22, 2024 |
| ASUSTek       | GL553VD                     | [2dc26b3608](https://linux-hardware.org/?probe=2dc26b3608) | Nov 22, 2024 |
| ASUSTek       | GL553VD                     | [05198e67f4](https://linux-hardware.org/?probe=05198e67f4) | Nov 22, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [4b11bad4e2](https://linux-hardware.org/?probe=4b11bad4e2) | Nov 21, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [8671b7ff77](https://linux-hardware.org/?probe=8671b7ff77) | Nov 21, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [412e0842bc](https://linux-hardware.org/?probe=412e0842bc) | Nov 21, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6cd8e82a85](https://linux-hardware.org/?probe=6cd8e82a85) | Nov 21, 2024 |
| Monster       | TULPAR T7 V19.3             | [a1fed284f5](https://linux-hardware.org/?probe=a1fed284f5) | Nov 21, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [437866e6de](https://linux-hardware.org/?probe=437866e6de) | Nov 21, 2024 |
| Acer          | Aspire 8940G                | [34cae8ce91](https://linux-hardware.org/?probe=34cae8ce91) | Nov 21, 2024 |
| HP            | ProBook 450 G8              | [5f49362c72](https://linux-hardware.org/?probe=5f49362c72) | Nov 21, 2024 |
| Apple         | MacBookAir6,2               | [3fe08ea4ca](https://linux-hardware.org/?probe=3fe08ea4ca) | Nov 21, 2024 |
| Apple         | MacBookPro12,1              | [eb7131a7ff](https://linux-hardware.org/?probe=eb7131a7ff) | Nov 20, 2024 |
| Apple         | MacBookPro12,1              | [0d9292a695](https://linux-hardware.org/?probe=0d9292a695) | Nov 20, 2024 |
| ASUSTek       | 1215N                       | [b7baad3524](https://linux-hardware.org/?probe=b7baad3524) | Nov 20, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d7a91ad89e](https://linux-hardware.org/?probe=d7a91ad89e) | Nov 20, 2024 |
| MSI           | Prestige 16 AI Studio B1... | [fa335a2999](https://linux-hardware.org/?probe=fa335a2999) | Nov 20, 2024 |
| VALE          | Notebook Classic C170       | [d5f2c08e9a](https://linux-hardware.org/?probe=d5f2c08e9a) | Nov 19, 2024 |
| ASUSTek       | N752VX                      | [b519a4ac5e](https://linux-hardware.org/?probe=b519a4ac5e) | Nov 19, 2024 |
| Lenovo        | ThinkPad T440 20B6008EUS    | [3e2fc33d80](https://linux-hardware.org/?probe=3e2fc33d80) | Nov 19, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [f32ad3a689](https://linux-hardware.org/?probe=f32ad3a689) | Nov 19, 2024 |
| Lenovo        | ThinkPad T430 2349LPG       | [dea56417dc](https://linux-hardware.org/?probe=dea56417dc) | Nov 19, 2024 |
| Acer          | Aspire 3810T                | [71d5b52553](https://linux-hardware.org/?probe=71d5b52553) | Nov 18, 2024 |
| Apple         | MacBookAir7,2               | [ba3ba814ee](https://linux-hardware.org/?probe=ba3ba814ee) | Nov 18, 2024 |
| Chuwi         | GemiBook Pro                | [d9d23cdc2c](https://linux-hardware.org/?probe=d9d23cdc2c) | Nov 18, 2024 |
| Chuwi         | GemiBook Pro                | [1a57440afe](https://linux-hardware.org/?probe=1a57440afe) | Nov 18, 2024 |
| Dell          | Latitude 3430               | [2aa0f80ba7](https://linux-hardware.org/?probe=2aa0f80ba7) | Nov 18, 2024 |
| Lenovo        | V14-IIL 82C4                | [586741cd8d](https://linux-hardware.org/?probe=586741cd8d) | Nov 18, 2024 |
| Compaq        | Presario CQ-23              | [a89bbf6c2d](https://linux-hardware.org/?probe=a89bbf6c2d) | Nov 16, 2024 |
| HP            | HDX18                       | [5c06e25998](https://linux-hardware.org/?probe=5c06e25998) | Nov 16, 2024 |
| HP            | HDX18                       | [84c4ca9b15](https://linux-hardware.org/?probe=84c4ca9b15) | Nov 16, 2024 |
| HP            | Pavilion dv6                | [3e5c98d0a7](https://linux-hardware.org/?probe=3e5c98d0a7) | Nov 16, 2024 |
| Lenovo        | ThinkPad X201 36803D7       | [2488665eda](https://linux-hardware.org/?probe=2488665eda) | Nov 15, 2024 |
| Acer          | Aspire A315-510P            | [d408ed76f5](https://linux-hardware.org/?probe=d408ed76f5) | Nov 15, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21HL... | [053ac6a237](https://linux-hardware.org/?probe=053ac6a237) | Nov 15, 2024 |
| HP            | Pavilion g6                 | [5b93f09faa](https://linux-hardware.org/?probe=5b93f09faa) | Nov 15, 2024 |
| Lenovo        | ThinkPad T420 4236QE0       | [655fe70c91](https://linux-hardware.org/?probe=655fe70c91) | Nov 15, 2024 |
| Apple         | MacBookPro5,5               | [865f61fac1](https://linux-hardware.org/?probe=865f61fac1) | Nov 15, 2024 |
| Dell          | Latitude 7420               | [38595a466f](https://linux-hardware.org/?probe=38595a466f) | Nov 14, 2024 |
| HP            | Pavilion g7                 | [97d1e7e615](https://linux-hardware.org/?probe=97d1e7e615) | Nov 14, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [84de7f4342](https://linux-hardware.org/?probe=84de7f4342) | Nov 13, 2024 |
| HP            | EliteBook 840 G3            | [c9a14a76c9](https://linux-hardware.org/?probe=c9a14a76c9) | Nov 13, 2024 |
| ASUSTek       | X541NA                      | [820c94c4ff](https://linux-hardware.org/?probe=820c94c4ff) | Nov 13, 2024 |
| Dell          | Inspiron 5420               | [00ddbfabc2](https://linux-hardware.org/?probe=00ddbfabc2) | Nov 13, 2024 |
| Lenovo        | ThinkPad L430 2466DN6       | [4f5a0a5c17](https://linux-hardware.org/?probe=4f5a0a5c17) | Nov 13, 2024 |
| Lenovo        | ThinkPad W530 244759G       | [6c04928748](https://linux-hardware.org/?probe=6c04928748) | Nov 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [16f0766161](https://linux-hardware.org/?probe=16f0766161) | Nov 12, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [4e89ce41d8](https://linux-hardware.org/?probe=4e89ce41d8) | Nov 12, 2024 |
| Lenovo        | ThinkPad T410 253725G       | [2f352dba44](https://linux-hardware.org/?probe=2f352dba44) | Nov 11, 2024 |
| HP            | Compaq 6710s (GC014ET#AB... | [f37a3d2488](https://linux-hardware.org/?probe=f37a3d2488) | Nov 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [c236922dba](https://linux-hardware.org/?probe=c236922dba) | Nov 11, 2024 |
| Apple         | MacBookPro7,1               | [7317bd38b4](https://linux-hardware.org/?probe=7317bd38b4) | Nov 11, 2024 |
| Dell          | Latitude 3420               | [f2a0eac267](https://linux-hardware.org/?probe=f2a0eac267) | Nov 11, 2024 |
| ASUSTek       | GL503VD                     | [d395d04c9f](https://linux-hardware.org/?probe=d395d04c9f) | Nov 11, 2024 |
| OEM           | Unknown                     | [da6c715062](https://linux-hardware.org/?probe=da6c715062) | Nov 11, 2024 |
| Dell          | XPS MXC062                  | [971fc4620d](https://linux-hardware.org/?probe=971fc4620d) | Nov 11, 2024 |
| ASUSTek       | GL552VW                     | [748450069e](https://linux-hardware.org/?probe=748450069e) | Nov 10, 2024 |
| RuggedPC      | RuggedBookR15               | [aa3abb03d5](https://linux-hardware.org/?probe=aa3abb03d5) | Nov 10, 2024 |
| HP            | Laptop 15-bw0xx             | [df8fc5ffa1](https://linux-hardware.org/?probe=df8fc5ffa1) | Nov 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7bba50e3f8](https://linux-hardware.org/?probe=7bba50e3f8) | Nov 10, 2024 |
| HP            | ProBook 4720s               | [e65d783c0d](https://linux-hardware.org/?probe=e65d783c0d) | Nov 10, 2024 |
| HP            | ProBook 4720s               | [4e2933c1be](https://linux-hardware.org/?probe=4e2933c1be) | Nov 10, 2024 |
| UNOWHY        | Y13G012S4EI                 | [bfaec6f29f](https://linux-hardware.org/?probe=bfaec6f29f) | Nov 10, 2024 |
| Lenovo        | ThinkPad Edge E320 1298A... | [0af8d792c0](https://linux-hardware.org/?probe=0af8d792c0) | Nov 10, 2024 |
| HP            | Compaq 6710s (GC014ET#AB... | [59cdfa97ac](https://linux-hardware.org/?probe=59cdfa97ac) | Nov 10, 2024 |
| UNOWHY        | Y13G012S4EI                 | [3578d7c78f](https://linux-hardware.org/?probe=3578d7c78f) | Nov 09, 2024 |
| HP            | EliteBook 820 G1            | [c4b2bda42d](https://linux-hardware.org/?probe=c4b2bda42d) | Nov 09, 2024 |
| Dell          | Inspiron 3542               | [8268a446ea](https://linux-hardware.org/?probe=8268a446ea) | Nov 09, 2024 |
| HP            | 240 G8                      | [690c75feed](https://linux-hardware.org/?probe=690c75feed) | Nov 08, 2024 |
| Lenovo        | ThinkPad X230 2324BN2       | [2040b5fccb](https://linux-hardware.org/?probe=2040b5fccb) | Nov 08, 2024 |
| Toshiba       | Satellite S50D-B            | [ce49220a67](https://linux-hardware.org/?probe=ce49220a67) | Nov 08, 2024 |
| Toshiba       | Satellite S50D-B            | [1f56de68ff](https://linux-hardware.org/?probe=1f56de68ff) | Nov 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [db35fd585c](https://linux-hardware.org/?probe=db35fd585c) | Nov 07, 2024 |
| MSI           | Prestige 16 AI Studio B1... | [f0052fafb7](https://linux-hardware.org/?probe=f0052fafb7) | Nov 07, 2024 |
| Medion        | P7812                       | [e1d13cf7b2](https://linux-hardware.org/?probe=e1d13cf7b2) | Nov 07, 2024 |
| HP            | 240 G8                      | [7144a2acc7](https://linux-hardware.org/?probe=7144a2acc7) | Nov 07, 2024 |
| Fujitsu Si... | LIFEBOOK S7110              | [39db395d37](https://linux-hardware.org/?probe=39db395d37) | Nov 06, 2024 |
| Unknown       | Unknown                     | [e10825d9a4](https://linux-hardware.org/?probe=e10825d9a4) | Nov 06, 2024 |
| Unknown       | Unknown                     | [385ca86468](https://linux-hardware.org/?probe=385ca86468) | Nov 06, 2024 |
| Lenovo        | G40-70 80GA                 | [ba688aca3d](https://linux-hardware.org/?probe=ba688aca3d) | Nov 05, 2024 |
| Lenovo        | G40-70 80GA                 | [5f8395be15](https://linux-hardware.org/?probe=5f8395be15) | Nov 05, 2024 |
| HP            | Pavilion Sleekbook 15 PC    | [06aea2ac21](https://linux-hardware.org/?probe=06aea2ac21) | Nov 05, 2024 |
| Lenovo        | V110-15ISK 80TL             | [baf7cf7f68](https://linux-hardware.org/?probe=baf7cf7f68) | Nov 05, 2024 |
| Chuwi         | FreeBook                    | [a381dac424](https://linux-hardware.org/?probe=a381dac424) | Nov 05, 2024 |
| Chuwi         | FreeBook                    | [3eaecb4536](https://linux-hardware.org/?probe=3eaecb4536) | Nov 05, 2024 |
| Dell          | Precision M6500             | [e588051942](https://linux-hardware.org/?probe=e588051942) | Nov 05, 2024 |
| Dell          | Precision M6500             | [e4897c55f4](https://linux-hardware.org/?probe=e4897c55f4) | Nov 05, 2024 |
| Lenovo        | ThinkPad X240 20AMS2GS00    | [500009e99f](https://linux-hardware.org/?probe=500009e99f) | Nov 05, 2024 |
| Lenovo        | ThinkPad T450s 20BX0049G... | [a95c95efaf](https://linux-hardware.org/?probe=a95c95efaf) | Nov 04, 2024 |
| Apple         | MacBookPro5,5               | [3395c22619](https://linux-hardware.org/?probe=3395c22619) | Nov 04, 2024 |
| Acer          | Aspire SW5-012              | [aed9a62d9a](https://linux-hardware.org/?probe=aed9a62d9a) | Nov 04, 2024 |
| Dell          | System XPS L502X            | [0780a4c2b1](https://linux-hardware.org/?probe=0780a4c2b1) | Nov 04, 2024 |
| HP            | Laptop 15-da0xxx            | [723e6b9be2](https://linux-hardware.org/?probe=723e6b9be2) | Nov 04, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | [d87047b8f7](https://linux-hardware.org/?probe=d87047b8f7) | Nov 04, 2024 |
| HP            | EliteBook 8570p             | [212f338f8a](https://linux-hardware.org/?probe=212f338f8a) | Nov 04, 2024 |
| ASUSTek       | GL503VD                     | [a6175c9826](https://linux-hardware.org/?probe=a6175c9826) | Nov 04, 2024 |
| HP            | 550                         | [70807a2c26](https://linux-hardware.org/?probe=70807a2c26) | Nov 04, 2024 |
| Samsung       | 700Z3C/700Z5C               | [4bc817a06d](https://linux-hardware.org/?probe=4bc817a06d) | Nov 03, 2024 |
| Sony          | SVE14A18ECH                 | [121ce83647](https://linux-hardware.org/?probe=121ce83647) | Nov 03, 2024 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [362643c5ee](https://linux-hardware.org/?probe=362643c5ee) | Nov 03, 2024 |
| Toshiba       | TECRA Z40-C                 | [8163b79289](https://linux-hardware.org/?probe=8163b79289) | Nov 03, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [355fdb65ca](https://linux-hardware.org/?probe=355fdb65ca) | Nov 03, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [6a6e58c0fd](https://linux-hardware.org/?probe=6a6e58c0fd) | Nov 03, 2024 |
| Acer          | Extensa 5635ZG              | [46d4a76e28](https://linux-hardware.org/?probe=46d4a76e28) | Nov 02, 2024 |
| Acer          | Aspire 8940G                | [bd62e27d46](https://linux-hardware.org/?probe=bd62e27d46) | Nov 02, 2024 |
| Dell          | Latitude 5580               | [171fb01f73](https://linux-hardware.org/?probe=171fb01f73) | Nov 02, 2024 |
| Lenovo        | ThinkPad T470 20HES2130Q    | [aa38d6e195](https://linux-hardware.org/?probe=aa38d6e195) | Nov 02, 2024 |
| Dell          | Latitude E6430              | [c2e60e88ed](https://linux-hardware.org/?probe=c2e60e88ed) | Nov 02, 2024 |
| Apple         | MacBookPro10,1              | [d993d0ced3](https://linux-hardware.org/?probe=d993d0ced3) | Nov 01, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [e0bb43c354](https://linux-hardware.org/?probe=e0bb43c354) | Nov 01, 2024 |
| Acer          | Aspire A115-32              | [d3dd3c61dd](https://linux-hardware.org/?probe=d3dd3c61dd) | Oct 31, 2024 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [cc4eefbf48](https://linux-hardware.org/?probe=cc4eefbf48) | Oct 31, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [dcd26cf495](https://linux-hardware.org/?probe=dcd26cf495) | Oct 31, 2024 |
| Dell          | Latitude E6540              | [c890aeb493](https://linux-hardware.org/?probe=c890aeb493) | Oct 30, 2024 |
| HP            | ProBook 450 15.6 inch G9... | [5133ff315e](https://linux-hardware.org/?probe=5133ff315e) | Oct 30, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [3b59592ecd](https://linux-hardware.org/?probe=3b59592ecd) | Oct 30, 2024 |
| HP            | ProBook 450 15.6 inch G9... | [7264124e00](https://linux-hardware.org/?probe=7264124e00) | Oct 30, 2024 |
| Dell          | Inspiron 7720               | [f308c7c570](https://linux-hardware.org/?probe=f308c7c570) | Oct 30, 2024 |
| Dell          | Latitude E6420              | [4570d16303](https://linux-hardware.org/?probe=4570d16303) | Oct 30, 2024 |
| Dell          | Latitude E6420              | [9870142d15](https://linux-hardware.org/?probe=9870142d15) | Oct 30, 2024 |
| Lenovo        | ThinkPad Edge E430 3254A... | [645dabbfd9](https://linux-hardware.org/?probe=645dabbfd9) | Oct 30, 2024 |
| HP            | ProBook 450 G3              | [14b49f275b](https://linux-hardware.org/?probe=14b49f275b) | Oct 30, 2024 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [81c61ad299](https://linux-hardware.org/?probe=81c61ad299) | Oct 30, 2024 |
| Acer          | Aspire M5-583P              | [af4d75f50b](https://linux-hardware.org/?probe=af4d75f50b) | Oct 30, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [9e438cb0e1](https://linux-hardware.org/?probe=9e438cb0e1) | Oct 30, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [dd9ac664ef](https://linux-hardware.org/?probe=dd9ac664ef) | Oct 30, 2024 |
| Lenovo        | Z70-80 80FG                 | [36e44b1959](https://linux-hardware.org/?probe=36e44b1959) | Oct 29, 2024 |
| Lenovo        | G70-35 80Q5                 | [83f8e03f32](https://linux-hardware.org/?probe=83f8e03f32) | Oct 29, 2024 |
| HUAWEI        | MCLF-XX                     | [6a8410a585](https://linux-hardware.org/?probe=6a8410a585) | Oct 29, 2024 |
| HP            | 255 G7 Notebook PC          | [7547bc75a9](https://linux-hardware.org/?probe=7547bc75a9) | Oct 29, 2024 |
| Acer          | Aspire 5830TG               | [f93513560e](https://linux-hardware.org/?probe=f93513560e) | Oct 29, 2024 |
| HUAWEI        | MCLF-XX                     | [eb4b7fdf89](https://linux-hardware.org/?probe=eb4b7fdf89) | Oct 29, 2024 |
| Apple         | MacBookPro8,1               | [f8111d2bcb](https://linux-hardware.org/?probe=f8111d2bcb) | Oct 29, 2024 |
| Intel         | Unknown                     | [ae6815487a](https://linux-hardware.org/?probe=ae6815487a) | Oct 29, 2024 |
| ASUSTek       | BU401LA                     | [544471cf95](https://linux-hardware.org/?probe=544471cf95) | Oct 29, 2024 |
| Acer          | Nitro AN515-57              | [5b8bbb16a9](https://linux-hardware.org/?probe=5b8bbb16a9) | Oct 28, 2024 |
| Dell          | Latitude 7640               | [db98adb76d](https://linux-hardware.org/?probe=db98adb76d) | Oct 28, 2024 |
| Lenovo        | IdeaPad S340-15APITouch ... | [808ef20234](https://linux-hardware.org/?probe=808ef20234) | Oct 28, 2024 |
| Dell          | Latitude D830               | [9dcccfc8bd](https://linux-hardware.org/?probe=9dcccfc8bd) | Oct 28, 2024 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [76d1943e3b](https://linux-hardware.org/?probe=76d1943e3b) | Oct 28, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | [9af6dd6ef4](https://linux-hardware.org/?probe=9af6dd6ef4) | Oct 28, 2024 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [2a1d98e302](https://linux-hardware.org/?probe=2a1d98e302) | Oct 27, 2024 |
| Lenovo        | ThinkPad Edge E320 1298A... | [db967cf215](https://linux-hardware.org/?probe=db967cf215) | Oct 27, 2024 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [729eac7b69](https://linux-hardware.org/?probe=729eac7b69) | Oct 27, 2024 |
| HP            | ProBook 4730s               | [8c5e435a6b](https://linux-hardware.org/?probe=8c5e435a6b) | Oct 27, 2024 |
| Dell          | XPS 15 9500                 | [26b8d8ffba](https://linux-hardware.org/?probe=26b8d8ffba) | Oct 27, 2024 |
| Sony          | VPCF12Z1E                   | [419e054c06](https://linux-hardware.org/?probe=419e054c06) | Oct 27, 2024 |
| Sony          | VPCF12Z1E                   | [f68f55bfd6](https://linux-hardware.org/?probe=f68f55bfd6) | Oct 27, 2024 |
| HP            | ProBook 4730s               | [98b5e041d8](https://linux-hardware.org/?probe=98b5e041d8) | Oct 27, 2024 |
| Apple         | MacBook7,1                  | [8031f48834](https://linux-hardware.org/?probe=8031f48834) | Oct 27, 2024 |
| MSI           | GP72 7RE                    | [3495e8b210](https://linux-hardware.org/?probe=3495e8b210) | Oct 27, 2024 |
| Juana Mans... | SF20GM7                     | [0b2f896cf6](https://linux-hardware.org/?probe=0b2f896cf6) | Oct 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [08b6a5d7d3](https://linux-hardware.org/?probe=08b6a5d7d3) | Oct 26, 2024 |
| Compumax C... | ONIX-CEL-0001               | [4ab4fd20bc](https://linux-hardware.org/?probe=4ab4fd20bc) | Oct 26, 2024 |
| Unknown       | CherryTrail                 | [be2389a1f2](https://linux-hardware.org/?probe=be2389a1f2) | Oct 26, 2024 |
| Compumax C... | ONIX-CEL-0001               | [7b016cc848](https://linux-hardware.org/?probe=7b016cc848) | Oct 26, 2024 |
| HP            | Laptop 14-dq0xxx            | [dcdaf50f9f](https://linux-hardware.org/?probe=dcdaf50f9f) | Oct 26, 2024 |
| Dell          | Latitude D530               | [c1459031b7](https://linux-hardware.org/?probe=c1459031b7) | Oct 25, 2024 |
| Lenovo        | ThinkPad T410s 291238G      | [7f94eafaf2](https://linux-hardware.org/?probe=7f94eafaf2) | Oct 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4b872572eb](https://linux-hardware.org/?probe=4b872572eb) | Oct 25, 2024 |
| Lenovo        | ThinkPad T410s 291238G      | [20e158e9fb](https://linux-hardware.org/?probe=20e158e9fb) | Oct 25, 2024 |
| HP            | Laptop 14-bs0xx             | [ff5be70e84](https://linux-hardware.org/?probe=ff5be70e84) | Oct 25, 2024 |
| ASUSTek       | K55A                        | [d0eea3c30a](https://linux-hardware.org/?probe=d0eea3c30a) | Oct 25, 2024 |
| Unknown       | W1415A                      | [d8206d7318](https://linux-hardware.org/?probe=d8206d7318) | Oct 24, 2024 |
| ASUSTek       | K50C                        | [4da330858c](https://linux-hardware.org/?probe=4da330858c) | Oct 24, 2024 |
| ASUSTek       | P50IJ                       | [bf855fcb57](https://linux-hardware.org/?probe=bf855fcb57) | Oct 24, 2024 |
| Samsung       | 700Z3C/700Z5C               | [d6561c30ac](https://linux-hardware.org/?probe=d6561c30ac) | Oct 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0a783a20c1](https://linux-hardware.org/?probe=0a783a20c1) | Oct 24, 2024 |
| Unknown       | YEPBOOK PRO                 | [0d3c07610a](https://linux-hardware.org/?probe=0d3c07610a) | Oct 24, 2024 |
| HP            | Pavilion Notebook           | [7abf782ae9](https://linux-hardware.org/?probe=7abf782ae9) | Oct 23, 2024 |
| Fujitsu Si... | AMILO Li 1718               | [8343c4f1d5](https://linux-hardware.org/?probe=8343c4f1d5) | Oct 23, 2024 |
| Fujitsu Si... | AMILO Li 1718               | [5873adb522](https://linux-hardware.org/?probe=5873adb522) | Oct 23, 2024 |
| HP            | Laptop 14-dq0xxx            | [466c92fa21](https://linux-hardware.org/?probe=466c92fa21) | Oct 23, 2024 |
| Apple         | MacBookAir7,1               | [3b54b1a84a](https://linux-hardware.org/?probe=3b54b1a84a) | Oct 23, 2024 |
| Apple         | MacBookAir7,1               | [8915d8d3bb](https://linux-hardware.org/?probe=8915d8d3bb) | Oct 23, 2024 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [a915ce3cad](https://linux-hardware.org/?probe=a915ce3cad) | Oct 22, 2024 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [97d5a16066](https://linux-hardware.org/?probe=97d5a16066) | Oct 22, 2024 |
| HP            | EliteBook 820 G2            | [8b3172d505](https://linux-hardware.org/?probe=8b3172d505) | Oct 22, 2024 |
| Dell          | Latitude 5490               | [3cabfe000a](https://linux-hardware.org/?probe=3cabfe000a) | Oct 22, 2024 |
| GEO           | GeoBook 240                 | [e7fdf54200](https://linux-hardware.org/?probe=e7fdf54200) | Oct 21, 2024 |
| ASUSTek       | K52JV                       | [3079996867](https://linux-hardware.org/?probe=3079996867) | Oct 21, 2024 |
| ASUSTek       | X441BA                      | [0481eb3049](https://linux-hardware.org/?probe=0481eb3049) | Oct 21, 2024 |
| Toshiba       | PORTEGE Z830                | [1d5f4bb615](https://linux-hardware.org/?probe=1d5f4bb615) | Oct 20, 2024 |
| Toshiba       | Satellite Pro C50-A-1K9     | [ee0af1751a](https://linux-hardware.org/?probe=ee0af1751a) | Oct 20, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [3d4a61447f](https://linux-hardware.org/?probe=3d4a61447f) | Oct 20, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [5ddfbb59eb](https://linux-hardware.org/?probe=5ddfbb59eb) | Oct 20, 2024 |
| Apple         | MacBookPro6,2               | [9f30927210](https://linux-hardware.org/?probe=9f30927210) | Oct 20, 2024 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [5cc130f16e](https://linux-hardware.org/?probe=5cc130f16e) | Oct 20, 2024 |
| Sony          | VPCEL3S1E                   | [befb361f1e](https://linux-hardware.org/?probe=befb361f1e) | Oct 20, 2024 |
| Acer          | Aspire V5-123               | [a47bf6ca57](https://linux-hardware.org/?probe=a47bf6ca57) | Oct 20, 2024 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [097be855e6](https://linux-hardware.org/?probe=097be855e6) | Oct 20, 2024 |
| ASUSTek       | X556UQ                      | [046fdf8e88](https://linux-hardware.org/?probe=046fdf8e88) | Oct 19, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [5754b92f35](https://linux-hardware.org/?probe=5754b92f35) | Oct 19, 2024 |
| Samsung       | 370E4K                      | [5316144029](https://linux-hardware.org/?probe=5316144029) | Oct 19, 2024 |
| ASUSTek       | G55VW                       | [a1b8fade8a](https://linux-hardware.org/?probe=a1b8fade8a) | Oct 19, 2024 |
| HP            | 15                          | [b9758a830e](https://linux-hardware.org/?probe=b9758a830e) | Oct 19, 2024 |
| HP            | 15                          | [2219fa443f](https://linux-hardware.org/?probe=2219fa443f) | Oct 19, 2024 |
| Samsung       | 370E4K                      | [72b8154d51](https://linux-hardware.org/?probe=72b8154d51) | Oct 19, 2024 |
| ASRock        | X670E PG Lightning          | [a82784b122](https://linux-hardware.org/?probe=a82784b122) | Oct 19, 2024 |
| Sony          | VPCEL3S1E                   | [7dd43d769b](https://linux-hardware.org/?probe=7dd43d769b) | Oct 19, 2024 |
| Acer          | Aspire 5738                 | [d550044553](https://linux-hardware.org/?probe=d550044553) | Oct 19, 2024 |
| Exo           | Smart Serie L               | [0ca04a37d8](https://linux-hardware.org/?probe=0ca04a37d8) | Oct 19, 2024 |
| Exo           | Smart Serie L               | [c2c7184260](https://linux-hardware.org/?probe=c2c7184260) | Oct 19, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [c494c18d97](https://linux-hardware.org/?probe=c494c18d97) | Oct 18, 2024 |
| Dell          | Latitude E5530 non-vPro     | [15d2f1b66d](https://linux-hardware.org/?probe=15d2f1b66d) | Oct 18, 2024 |
| HP            | G42                         | [72bf54ec1e](https://linux-hardware.org/?probe=72bf54ec1e) | Oct 18, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [7d19f92203](https://linux-hardware.org/?probe=7d19f92203) | Oct 18, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [7e4fe6c29c](https://linux-hardware.org/?probe=7e4fe6c29c) | Oct 18, 2024 |
| ASUSTek       | X540YA                      | [717f10e863](https://linux-hardware.org/?probe=717f10e863) | Oct 17, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [b9a1fce690](https://linux-hardware.org/?probe=b9a1fce690) | Oct 17, 2024 |
| Packard Be... | EasyNote_MX37-U-056NL       | [7a6a98e8e7](https://linux-hardware.org/?probe=7a6a98e8e7) | Oct 17, 2024 |
| Lenovo        | ThinkPad Edge 25453BG       | [1b7e79796e](https://linux-hardware.org/?probe=1b7e79796e) | Oct 17, 2024 |
| itel Mobil... | Epic 1                      | [d8b92ea891](https://linux-hardware.org/?probe=d8b92ea891) | Oct 17, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [260d61bcf0](https://linux-hardware.org/?probe=260d61bcf0) | Oct 17, 2024 |
| Positivo      | C8256AI-15                  | [c3bad33452](https://linux-hardware.org/?probe=c3bad33452) | Oct 16, 2024 |
| HP            | EliteBook 840 G1            | [ea6b8939d2](https://linux-hardware.org/?probe=ea6b8939d2) | Oct 16, 2024 |
| HP            | EliteBook 840 G1            | [42860ad3af](https://linux-hardware.org/?probe=42860ad3af) | Oct 16, 2024 |
| Sony          | SVE1711V1EB                 | [f57853bbf9](https://linux-hardware.org/?probe=f57853bbf9) | Oct 16, 2024 |
| Sony          | SVE1711V1EB                 | [8cfbbedec2](https://linux-hardware.org/?probe=8cfbbedec2) | Oct 16, 2024 |
| itel Mobil... | Epic 1                      | [b99b7f9e7a](https://linux-hardware.org/?probe=b99b7f9e7a) | Oct 16, 2024 |
| Sony          | VGN-AR41S                   | [d41cbf35f9](https://linux-hardware.org/?probe=d41cbf35f9) | Oct 16, 2024 |
| ASUSTek       | K54HR                       | [fc05d76312](https://linux-hardware.org/?probe=fc05d76312) | Oct 16, 2024 |
| Dell          | Latitude 3440               | [d6d3377f4d](https://linux-hardware.org/?probe=d6d3377f4d) | Oct 16, 2024 |
| HP            | ProBook 4510s               | [82921bfaa3](https://linux-hardware.org/?probe=82921bfaa3) | Oct 16, 2024 |
| Acer          | TravelMate P215-41-G2       | [abe078a53a](https://linux-hardware.org/?probe=abe078a53a) | Oct 15, 2024 |
| Intel         | Unknown                     | [800aa4f46b](https://linux-hardware.org/?probe=800aa4f46b) | Oct 15, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | [ae22524e06](https://linux-hardware.org/?probe=ae22524e06) | Oct 15, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | [e86ff90245](https://linux-hardware.org/?probe=e86ff90245) | Oct 15, 2024 |
| Getac         | B300G5                      | [5de20509e3](https://linux-hardware.org/?probe=5de20509e3) | Oct 15, 2024 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [3daad6b7aa](https://linux-hardware.org/?probe=3daad6b7aa) | Oct 14, 2024 |
| Dell          | Latitude 3540               | [08840c6bb5](https://linux-hardware.org/?probe=08840c6bb5) | Oct 13, 2024 |
| Dell          | Precision M4500             | [61cc876a50](https://linux-hardware.org/?probe=61cc876a50) | Oct 13, 2024 |
| Acer          | TravelMate P215-41-G2       | [f8f51b5bdb](https://linux-hardware.org/?probe=f8f51b5bdb) | Oct 13, 2024 |
| Dell          | Latitude E7450              | [7119b42c95](https://linux-hardware.org/?probe=7119b42c95) | Oct 13, 2024 |
| Apple         | MacBookAir6,2               | [e297bab7ce](https://linux-hardware.org/?probe=e297bab7ce) | Oct 13, 2024 |
| ASUSTek       | K50C                        | [8618444a5d](https://linux-hardware.org/?probe=8618444a5d) | Oct 12, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d8c217d807](https://linux-hardware.org/?probe=d8c217d807) | Oct 12, 2024 |
| ASUSTek       | G55VW                       | [101bba7262](https://linux-hardware.org/?probe=101bba7262) | Oct 12, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | [8e06db2e61](https://linux-hardware.org/?probe=8e06db2e61) | Oct 11, 2024 |
| HUAWEI        | FLMH-XX                     | [b05f724fb4](https://linux-hardware.org/?probe=b05f724fb4) | Oct 11, 2024 |
| HUAWEI        | FLMH-XX                     | [1467f8690d](https://linux-hardware.org/?probe=1467f8690d) | Oct 11, 2024 |
| Dell          | Latitude E7450              | [b5f8c62bb7](https://linux-hardware.org/?probe=b5f8c62bb7) | Oct 11, 2024 |
| Acer          | Aspire M5-583P              | [ff2ac16a5d](https://linux-hardware.org/?probe=ff2ac16a5d) | Oct 11, 2024 |
| HP            | 1000                        | [27c136a8c5](https://linux-hardware.org/?probe=27c136a8c5) | Oct 11, 2024 |
| Dell          | Latitude 7430               | [fbee722228](https://linux-hardware.org/?probe=fbee722228) | Oct 11, 2024 |
| OEM           | Unknown                     | [ceb87bcdba](https://linux-hardware.org/?probe=ceb87bcdba) | Oct 11, 2024 |
| Samsung       | 550XBE/350XBE               | [f6303aadd6](https://linux-hardware.org/?probe=f6303aadd6) | Oct 11, 2024 |
| HUAWEI        | BOD-WXX9                    | [6049e27844](https://linux-hardware.org/?probe=6049e27844) | Oct 10, 2024 |
| Dell          | Vostro 3550                 | [8ecca901ac](https://linux-hardware.org/?probe=8ecca901ac) | Oct 10, 2024 |
| HP            | 455                         | [1cf38a08fd](https://linux-hardware.org/?probe=1cf38a08fd) | Oct 10, 2024 |
| HP            | EliteBook 8760w             | [26485c8559](https://linux-hardware.org/?probe=26485c8559) | Oct 09, 2024 |
| HP            | ProBook 650 G1              | [2906c94383](https://linux-hardware.org/?probe=2906c94383) | Oct 09, 2024 |
| Acer          | Nitro AN515-58              | [ed859cf79b](https://linux-hardware.org/?probe=ed859cf79b) | Oct 09, 2024 |
| Lenovo        | V330-14IKB 81B0             | [6feeb04bd6](https://linux-hardware.org/?probe=6feeb04bd6) | Oct 09, 2024 |
| Toshiba       | Satellite C855-29M          | [759aa92d05](https://linux-hardware.org/?probe=759aa92d05) | Oct 09, 2024 |
| Dell          | Latitude E7440              | [d319ecb94f](https://linux-hardware.org/?probe=d319ecb94f) | Oct 09, 2024 |
| Dell          | Latitude E7440              | [4db806b12e](https://linux-hardware.org/?probe=4db806b12e) | Oct 09, 2024 |
| Itautec       | W7655                       | [b423f7e91d](https://linux-hardware.org/?probe=b423f7e91d) | Oct 09, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | [4994171903](https://linux-hardware.org/?probe=4994171903) | Oct 09, 2024 |
| Exo           | EXOMATE X5                  | [0db79727e7](https://linux-hardware.org/?probe=0db79727e7) | Oct 08, 2024 |
| Acer          | Aspire A315-44P             | [05330a1c5b](https://linux-hardware.org/?probe=05330a1c5b) | Oct 08, 2024 |
| Acer          | Extensa 5620                | [82f3c9f52b](https://linux-hardware.org/?probe=82f3c9f52b) | Oct 08, 2024 |
| HP            | Laptop 15-dy5xxx            | [8253f323a0](https://linux-hardware.org/?probe=8253f323a0) | Oct 07, 2024 |
| HP            | Laptop 15-dy5xxx            | [6273853b03](https://linux-hardware.org/?probe=6273853b03) | Oct 07, 2024 |
| HP            | Pavilion Notebook           | [69db239040](https://linux-hardware.org/?probe=69db239040) | Oct 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [ab67f0f4c4](https://linux-hardware.org/?probe=ab67f0f4c4) | Oct 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8dfb3bab34](https://linux-hardware.org/?probe=8dfb3bab34) | Oct 07, 2024 |
| Unknown       | W1415A                      | [a0c0ca59b5](https://linux-hardware.org/?probe=a0c0ca59b5) | Oct 07, 2024 |
| Dell          | Latitude E7450              | [49d9a72f4e](https://linux-hardware.org/?probe=49d9a72f4e) | Oct 07, 2024 |
| HONOR         | BBR-WAX9                    | [ca7c7ed0b0](https://linux-hardware.org/?probe=ca7c7ed0b0) | Oct 06, 2024 |
| Lenovo        | ThinkPad T570 20H90002RI    | [ef61fde952](https://linux-hardware.org/?probe=ef61fde952) | Oct 06, 2024 |
| HP            | Laptop 15-fd0xxx            | [0dbb83780d](https://linux-hardware.org/?probe=0dbb83780d) | Oct 06, 2024 |
| ASUSTek       | T300LA                      | [b6e3dc4b6e](https://linux-hardware.org/?probe=b6e3dc4b6e) | Oct 06, 2024 |
| HP            | Laptop 17-cn0xxx            | [9d8638d734](https://linux-hardware.org/?probe=9d8638d734) | Oct 06, 2024 |
| ASUSTek       | UX31E                       | [f8881d8b4e](https://linux-hardware.org/?probe=f8881d8b4e) | Oct 06, 2024 |
| HP            | ENVY 17 Leap Motion SE N... | [a8c1a124a9](https://linux-hardware.org/?probe=a8c1a124a9) | Oct 06, 2024 |
| HP            | EliteBook 820 G1            | [c14b9319d4](https://linux-hardware.org/?probe=c14b9319d4) | Oct 05, 2024 |
| HP            | Pavilion 11 x360 PC         | [fe5bb258a3](https://linux-hardware.org/?probe=fe5bb258a3) | Oct 05, 2024 |
| Dell          | Latitude D630               | [329c0abded](https://linux-hardware.org/?probe=329c0abded) | Oct 05, 2024 |
| Packard Be... | EasyNote LE69KB             | [793d87adb1](https://linux-hardware.org/?probe=793d87adb1) | Oct 05, 2024 |
| HP            | Pavilion 11 x360 PC         | [1856abb0a4](https://linux-hardware.org/?probe=1856abb0a4) | Oct 05, 2024 |
| Lenovo        | ThinkPad T420 4236QE0       | [0c7aff3c04](https://linux-hardware.org/?probe=0c7aff3c04) | Oct 05, 2024 |
| Dell          | Inspiron 3543               | [8867a3f043](https://linux-hardware.org/?probe=8867a3f043) | Oct 05, 2024 |
| Lenovo        | G550 2958                   | [93d0e9368e](https://linux-hardware.org/?probe=93d0e9368e) | Oct 05, 2024 |
| HP            | 625 (VW697EC)               | [ae4660d758](https://linux-hardware.org/?probe=ae4660d758) | Oct 04, 2024 |
| HP            | Snappy                      | [437d8947c4](https://linux-hardware.org/?probe=437d8947c4) | Oct 04, 2024 |
| HP            | Snappy                      | [4aac934df2](https://linux-hardware.org/?probe=4aac934df2) | Oct 04, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | [fbed489d65](https://linux-hardware.org/?probe=fbed489d65) | Oct 03, 2024 |
| HP            | 625 (VW697EC)               | [933fa4ee91](https://linux-hardware.org/?probe=933fa4ee91) | Oct 03, 2024 |
| ASUSTek       | X75VBP                      | [0c6a739c42](https://linux-hardware.org/?probe=0c6a739c42) | Oct 03, 2024 |
| ASUSTek       | X75VBP                      | [b34a212443](https://linux-hardware.org/?probe=b34a212443) | Oct 03, 2024 |
| Apple         | MacBookPro8,1               | [632dfc1140](https://linux-hardware.org/?probe=632dfc1140) | Oct 02, 2024 |
| HP            | Stream Laptop 11-ak0xxx     | [86046789e4](https://linux-hardware.org/?probe=86046789e4) | Oct 02, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1e94397b11](https://linux-hardware.org/?probe=1e94397b11) | Oct 02, 2024 |
| Dell          | Latitude 3420               | [621cf7dbc5](https://linux-hardware.org/?probe=621cf7dbc5) | Oct 02, 2024 |
| HP            | EliteBook 8470p             | [e9a9dd5664](https://linux-hardware.org/?probe=e9a9dd5664) | Oct 01, 2024 |
| UNOWHY        | Y13G010S4EI                 | [94201090b9](https://linux-hardware.org/?probe=94201090b9) | Oct 01, 2024 |
| HP            | ProBook 650 G1              | [ca529d5234](https://linux-hardware.org/?probe=ca529d5234) | Oct 01, 2024 |
| MOTILE        | M141                        | [de62b8afab](https://linux-hardware.org/?probe=de62b8afab) | Oct 01, 2024 |
| HP            | Stream Notebook PC 11       | [075ac358e1](https://linux-hardware.org/?probe=075ac358e1) | Oct 01, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [a53d5826f1](https://linux-hardware.org/?probe=a53d5826f1) | Oct 01, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | [63301b1c31](https://linux-hardware.org/?probe=63301b1c31) | Sep 30, 2024 |
| Dell          | Latitude E6520              | [4ed4a2acc3](https://linux-hardware.org/?probe=4ed4a2acc3) | Sep 30, 2024 |
| Dell          | Inspiron 1520               | [22b4245aa3](https://linux-hardware.org/?probe=22b4245aa3) | Sep 30, 2024 |
| Unknown       | Unknown                     | [b2ac2537df](https://linux-hardware.org/?probe=b2ac2537df) | Sep 29, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [64a20e4d8c](https://linux-hardware.org/?probe=64a20e4d8c) | Sep 29, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [6696fe76a8](https://linux-hardware.org/?probe=6696fe76a8) | Sep 29, 2024 |
| Dell          | Inspiron 3459               | [f36d24d646](https://linux-hardware.org/?probe=f36d24d646) | Sep 29, 2024 |
| Apple         | MacBookPro10,2              | [680a669b9e](https://linux-hardware.org/?probe=680a669b9e) | Sep 29, 2024 |
| SGIN          | M15                         | [16d90e5195](https://linux-hardware.org/?probe=16d90e5195) | Sep 29, 2024 |
| Acer          | Aspire ES1-711              | [b68a5e4910](https://linux-hardware.org/?probe=b68a5e4910) | Sep 28, 2024 |
| HP            | EliteBook 8470p             | [5f637ddf6b](https://linux-hardware.org/?probe=5f637ddf6b) | Sep 28, 2024 |
| HP            | Stream Notebook PC 14       | [bf5f7ae790](https://linux-hardware.org/?probe=bf5f7ae790) | Sep 28, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b3a8e4c5e9](https://linux-hardware.org/?probe=b3a8e4c5e9) | Sep 28, 2024 |
| TUXEDO        | Sirius 16 Gen1              | [e829303e25](https://linux-hardware.org/?probe=e829303e25) | Sep 27, 2024 |
| Digibras      | NH4CU53                     | [7254433879](https://linux-hardware.org/?probe=7254433879) | Sep 27, 2024 |
| Dell          | Latitude E5430 non-vPro     | [6ac57e29ba](https://linux-hardware.org/?probe=6ac57e29ba) | Sep 27, 2024 |
| Apple         | MacBookPro8,1               | [57f528793e](https://linux-hardware.org/?probe=57f528793e) | Sep 27, 2024 |
| Dell          | Latitude E5430 non-vPro     | [04b943d1ad](https://linux-hardware.org/?probe=04b943d1ad) | Sep 27, 2024 |
| HP            | ENVY TS m6 Sleekbook        | [0f503c4d45](https://linux-hardware.org/?probe=0f503c4d45) | Sep 27, 2024 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | [c891f656c5](https://linux-hardware.org/?probe=c891f656c5) | Sep 27, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [67736c95b5](https://linux-hardware.org/?probe=67736c95b5) | Sep 27, 2024 |
| LG Electro... | R510                        | [a37143fb1e](https://linux-hardware.org/?probe=a37143fb1e) | Sep 26, 2024 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | [116c290a50](https://linux-hardware.org/?probe=116c290a50) | Sep 26, 2024 |
| Dell          | Latitude 7640               | [c90fe866d1](https://linux-hardware.org/?probe=c90fe866d1) | Sep 26, 2024 |
| Google        | Peppy                       | [43b1f58c7d](https://linux-hardware.org/?probe=43b1f58c7d) | Sep 26, 2024 |
| ASUSTek       | K73SD                       | [f177a48833](https://linux-hardware.org/?probe=f177a48833) | Sep 26, 2024 |
| Dell          | Inspiron 5447               | [4543c01d21](https://linux-hardware.org/?probe=4543c01d21) | Sep 25, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [2f1952026d](https://linux-hardware.org/?probe=2f1952026d) | Sep 25, 2024 |
| Dell          | Inspiron 15-3567            | [a1569ace68](https://linux-hardware.org/?probe=a1569ace68) | Sep 25, 2024 |
| Lenovo        | Unknown                     | [e5d9460e3d](https://linux-hardware.org/?probe=e5d9460e3d) | Sep 24, 2024 |
| Apple         | MacBook7,1                  | [3910ad68a4](https://linux-hardware.org/?probe=3910ad68a4) | Sep 24, 2024 |
| HP            | ProBook 650 G5              | [21bbaa3557](https://linux-hardware.org/?probe=21bbaa3557) | Sep 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [69b3719446](https://linux-hardware.org/?probe=69b3719446) | Sep 24, 2024 |
| HP            | ENVY TS m6 Sleekbook        | [d495664aee](https://linux-hardware.org/?probe=d495664aee) | Sep 24, 2024 |
| HP            | ProBook 430 G8 Notebook ... | [cab80f4b28](https://linux-hardware.org/?probe=cab80f4b28) | Sep 23, 2024 |
| ASUSTek       | X405UA                      | [d9a22e6539](https://linux-hardware.org/?probe=d9a22e6539) | Sep 23, 2024 |
| Apple         | MacBookAir7,2               | [8173fdd55a](https://linux-hardware.org/?probe=8173fdd55a) | Sep 23, 2024 |
| Acer          | Swift SFX14-71G             | [47b57a8693](https://linux-hardware.org/?probe=47b57a8693) | Sep 23, 2024 |
| Samsung       | 300E5M/300E5L               | [2410e3bb5f](https://linux-hardware.org/?probe=2410e3bb5f) | Sep 23, 2024 |
| Samsung       | 700Z7C                      | [8107298d16](https://linux-hardware.org/?probe=8107298d16) | Sep 23, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRU9 83... | [ee0569f88c](https://linux-hardware.org/?probe=ee0569f88c) | Sep 22, 2024 |
| Tactus        | GeoBook 140                 | [a1ce5b2e82](https://linux-hardware.org/?probe=a1ce5b2e82) | Sep 22, 2024 |
| Tactus        | GeoBook 140                 | [b3f597938a](https://linux-hardware.org/?probe=b3f597938a) | Sep 22, 2024 |
| Acer          | Aspire one                  | [61a3d9531f](https://linux-hardware.org/?probe=61a3d9531f) | Sep 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [774755e30a](https://linux-hardware.org/?probe=774755e30a) | Sep 22, 2024 |
| Acer          | Aspire V3-472P              | [7c6795b09d](https://linux-hardware.org/?probe=7c6795b09d) | Sep 22, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [f5337edca2](https://linux-hardware.org/?probe=f5337edca2) | Sep 22, 2024 |
| Google        | Relm                        | [3d1c84f382](https://linux-hardware.org/?probe=3d1c84f382) | Sep 21, 2024 |
| HP            | 14                          | [3d21f34fbc](https://linux-hardware.org/?probe=3d21f34fbc) | Sep 21, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRU9 83... | [f875062c67](https://linux-hardware.org/?probe=f875062c67) | Sep 21, 2024 |
| Lenovo        | ThinkPad T420 4180CV1       | [6cbe581f38](https://linux-hardware.org/?probe=6cbe581f38) | Sep 21, 2024 |
| ASUSTek       | K72JT                       | [03aecb00be](https://linux-hardware.org/?probe=03aecb00be) | Sep 21, 2024 |
| ASUSTek       | G60JX                       | [a5bebe6bc8](https://linux-hardware.org/?probe=a5bebe6bc8) | Sep 21, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d0cdc2bf1e](https://linux-hardware.org/?probe=d0cdc2bf1e) | Sep 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0c5f6243f2](https://linux-hardware.org/?probe=0c5f6243f2) | Sep 20, 2024 |
| Dell          | System Inspiron N7110       | [a392cf876d](https://linux-hardware.org/?probe=a392cf876d) | Sep 20, 2024 |
| Samsung       | 700Z7C                      | [bfbda5980e](https://linux-hardware.org/?probe=bfbda5980e) | Sep 20, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [3cc7205695](https://linux-hardware.org/?probe=3cc7205695) | Sep 20, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [db35613f93](https://linux-hardware.org/?probe=db35613f93) | Sep 19, 2024 |
| HP            | Pavilion dv7                | [4bd0722ba7](https://linux-hardware.org/?probe=4bd0722ba7) | Sep 19, 2024 |
| HP            | Presario CQ57               | [e83a614323](https://linux-hardware.org/?probe=e83a614323) | Sep 19, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [c4777b62e2](https://linux-hardware.org/?probe=c4777b62e2) | Sep 19, 2024 |
| Acer          | Aspire 5733                 | [1a96d093f6](https://linux-hardware.org/?probe=1a96d093f6) | Sep 19, 2024 |
| Acer          | Aspire 5733                 | [369078d11f](https://linux-hardware.org/?probe=369078d11f) | Sep 19, 2024 |
| Dell          | Latitude E6530              | [d95ac73c9e](https://linux-hardware.org/?probe=d95ac73c9e) | Sep 19, 2024 |
| HP            | Pavilion dv6500             | [f9af2fb181](https://linux-hardware.org/?probe=f9af2fb181) | Sep 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c5b8360cb2](https://linux-hardware.org/?probe=c5b8360cb2) | Sep 19, 2024 |
| Chuwi         | Unknown                     | [45922bbe51](https://linux-hardware.org/?probe=45922bbe51) | Sep 19, 2024 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [3e8533679f](https://linux-hardware.org/?probe=3e8533679f) | Sep 18, 2024 |
| HUAWEI        | MCLG-XX                     | [5492ee99af](https://linux-hardware.org/?probe=5492ee99af) | Sep 18, 2024 |
| Acer          | Aspire A315-24P             | [c66c13efe7](https://linux-hardware.org/?probe=c66c13efe7) | Sep 17, 2024 |
| Apple         | MacBookPro5,5               | [ff464123a8](https://linux-hardware.org/?probe=ff464123a8) | Sep 17, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [02da0ba3a4](https://linux-hardware.org/?probe=02da0ba3a4) | Sep 17, 2024 |
| HP            | OMEN by Laptop              | [1eab45376e](https://linux-hardware.org/?probe=1eab45376e) | Sep 17, 2024 |
| Apple         | MacBookPro5,5               | [8633822abd](https://linux-hardware.org/?probe=8633822abd) | Sep 17, 2024 |
| MSI           | GS43VR 6RE                  | [bdccae4765](https://linux-hardware.org/?probe=bdccae4765) | Sep 16, 2024 |
| Lenovo        | ThinkPad P52 20M90010US     | [26da0cc730](https://linux-hardware.org/?probe=26da0cc730) | Sep 16, 2024 |
| Lenovo        | ThinkPad P52 20M90010US     | [0d6ed8b692](https://linux-hardware.org/?probe=0d6ed8b692) | Sep 16, 2024 |
| ASUSTek       | N55SF                       | [f49d65bd76](https://linux-hardware.org/?probe=f49d65bd76) | Sep 16, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [723a5d417e](https://linux-hardware.org/?probe=723a5d417e) | Sep 16, 2024 |
| Acer          | Aspire M5-583P              | [402d480ac7](https://linux-hardware.org/?probe=402d480ac7) | Sep 16, 2024 |
| Google        | Peppy                       | [2b8c99c805](https://linux-hardware.org/?probe=2b8c99c805) | Sep 15, 2024 |
| HP            | ProBook 6570b               | [5b28f08307](https://linux-hardware.org/?probe=5b28f08307) | Sep 15, 2024 |
| HP            | 245 G3                      | [25b9676ec6](https://linux-hardware.org/?probe=25b9676ec6) | Sep 15, 2024 |
| HP            | ProBook 650 G1              | [23bef23ee9](https://linux-hardware.org/?probe=23bef23ee9) | Sep 14, 2024 |
| HP            | 15                          | [58faedb138](https://linux-hardware.org/?probe=58faedb138) | Sep 14, 2024 |
| HP            | Compaq Presario CQ61        | [6c5ff283a3](https://linux-hardware.org/?probe=6c5ff283a3) | Sep 14, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [69358ccff4](https://linux-hardware.org/?probe=69358ccff4) | Sep 14, 2024 |
| Lenovo        | ThinkPad X250 20CLS87P00    | [f555873e62](https://linux-hardware.org/?probe=f555873e62) | Sep 14, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [a6b9e47c58](https://linux-hardware.org/?probe=a6b9e47c58) | Sep 13, 2024 |
| Apple         | MacBookPro14,1              | [1b50a503f5](https://linux-hardware.org/?probe=1b50a503f5) | Sep 13, 2024 |
| Apple         | MacBookPro14,1              | [6a82b07a2f](https://linux-hardware.org/?probe=6a82b07a2f) | Sep 13, 2024 |
| Dell          | Inspiron 3185               | [952bda6b1a](https://linux-hardware.org/?probe=952bda6b1a) | Sep 12, 2024 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [11256e3f7b](https://linux-hardware.org/?probe=11256e3f7b) | Sep 12, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [1a851f00af](https://linux-hardware.org/?probe=1a851f00af) | Sep 12, 2024 |
| Lenovo        | ThinkPad E550 20DF002YUS    | [771e8663d5](https://linux-hardware.org/?probe=771e8663d5) | Sep 12, 2024 |
| GPU Compan... | GGNC71719                   | [bbd12e9171](https://linux-hardware.org/?probe=bbd12e9171) | Sep 12, 2024 |
| Lenovo        | ThinkPad T430 23495W9       | [54c67b3aa6](https://linux-hardware.org/?probe=54c67b3aa6) | Sep 12, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a06804b41f](https://linux-hardware.org/?probe=a06804b41f) | Sep 12, 2024 |
| Apple         | MacBookPro14,1              | [0261f7cc23](https://linux-hardware.org/?probe=0261f7cc23) | Sep 11, 2024 |
| Positivo      | S14SL01                     | [c7cedf5551](https://linux-hardware.org/?probe=c7cedf5551) | Sep 11, 2024 |
| Apple         | MacBookPro14,1              | [5968522233](https://linux-hardware.org/?probe=5968522233) | Sep 11, 2024 |
| Lenovo        | ThinkPad Edge E431 62771... | [bbbe39a9e9](https://linux-hardware.org/?probe=bbbe39a9e9) | Sep 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [26e054dbe4](https://linux-hardware.org/?probe=26e054dbe4) | Sep 09, 2024 |
| HP            | ProBook 450 G8              | [b0ffe6c485](https://linux-hardware.org/?probe=b0ffe6c485) | Sep 08, 2024 |
| HP            | Pavilion 15                 | [eac3707cd6](https://linux-hardware.org/?probe=eac3707cd6) | Sep 08, 2024 |
| Apple         | MacBookAir7,2               | [e08807b6bb](https://linux-hardware.org/?probe=e08807b6bb) | Sep 08, 2024 |
| eMachines     | eME528                      | [644e28f53a](https://linux-hardware.org/?probe=644e28f53a) | Sep 08, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [904f6381b8](https://linux-hardware.org/?probe=904f6381b8) | Sep 08, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [4f805f1c14](https://linux-hardware.org/?probe=4f805f1c14) | Sep 08, 2024 |
| Dell          | System Inspiron N7110       | [31c1140517](https://linux-hardware.org/?probe=31c1140517) | Sep 07, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [ccdd0296cd](https://linux-hardware.org/?probe=ccdd0296cd) | Sep 07, 2024 |
| HP            | Pavilion dv6                | [821281eca4](https://linux-hardware.org/?probe=821281eca4) | Sep 07, 2024 |
| HP            | Compaq Presario CQ61        | [7f219497f7](https://linux-hardware.org/?probe=7f219497f7) | Sep 07, 2024 |
| HP            | Laptop 15-bw0xx             | [3aaf3aecaf](https://linux-hardware.org/?probe=3aaf3aecaf) | Sep 07, 2024 |
| HP            | ProBook 450 G8              | [d573dacb7a](https://linux-hardware.org/?probe=d573dacb7a) | Sep 07, 2024 |
| HP            | Pavilion dv6                | [eb8af19800](https://linux-hardware.org/?probe=eb8af19800) | Sep 06, 2024 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [4ce8d02b75](https://linux-hardware.org/?probe=4ce8d02b75) | Sep 06, 2024 |
| Lenovo        | ThinkPad X201 36803D7       | [0951b0296f](https://linux-hardware.org/?probe=0951b0296f) | Sep 06, 2024 |
| Alienware     | 14                          | [02b36f1577](https://linux-hardware.org/?probe=02b36f1577) | Sep 06, 2024 |
| Google        | Relm                        | [a69f9fe43f](https://linux-hardware.org/?probe=a69f9fe43f) | Sep 05, 2024 |
| HP            | 635                         | [791fd83191](https://linux-hardware.org/?probe=791fd83191) | Sep 05, 2024 |
| HP            | Compaq Presario CQ61        | [2f40a35a45](https://linux-hardware.org/?probe=2f40a35a45) | Sep 05, 2024 |
| Apple         | MacBookPro9,2               | [17b9716907](https://linux-hardware.org/?probe=17b9716907) | Sep 05, 2024 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [48629abb91](https://linux-hardware.org/?probe=48629abb91) | Sep 04, 2024 |
| HP            | 635                         | [5688007f52](https://linux-hardware.org/?probe=5688007f52) | Sep 04, 2024 |
| HP            | ENVY TS m6 Sleekbook        | [833cef2b94](https://linux-hardware.org/?probe=833cef2b94) | Sep 04, 2024 |
| Apple         | MacBookAir6,2               | [3045eea974](https://linux-hardware.org/?probe=3045eea974) | Sep 04, 2024 |
| Dell          | Latitude 5410               | [1bf48d02e9](https://linux-hardware.org/?probe=1bf48d02e9) | Sep 04, 2024 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [74b8bd7590](https://linux-hardware.org/?probe=74b8bd7590) | Sep 04, 2024 |
| Acer          | Nitro AN517-52              | [b88f93fd0c](https://linux-hardware.org/?probe=b88f93fd0c) | Sep 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ea03a78385](https://linux-hardware.org/?probe=ea03a78385) | Sep 03, 2024 |
| ASUSTek       | T100HAN                     | [6f00d9ab57](https://linux-hardware.org/?probe=6f00d9ab57) | Sep 03, 2024 |
| Lenovo        | ThinkPad T580 20LAS2X800    | [116bb82927](https://linux-hardware.org/?probe=116bb82927) | Sep 03, 2024 |
| Lenovo        | ThinkPad L460 20FVS0PA1H    | [1a67ec8391](https://linux-hardware.org/?probe=1a67ec8391) | Sep 03, 2024 |
| Lenovo        | Legion S7 16IAH7 82TF       | [615190ebfe](https://linux-hardware.org/?probe=615190ebfe) | Sep 03, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7a3f39e1c7](https://linux-hardware.org/?probe=7a3f39e1c7) | Sep 03, 2024 |
| Lenovo        | Legion S7 16IAH7 82TF       | [f846cf875c](https://linux-hardware.org/?probe=f846cf875c) | Sep 02, 2024 |
| VERO          | K147                        | [fa6457d35f](https://linux-hardware.org/?probe=fa6457d35f) | Sep 02, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [17b6d58dd6](https://linux-hardware.org/?probe=17b6d58dd6) | Sep 02, 2024 |
| Acer          | Aspire 5745G                | [778205b7cd](https://linux-hardware.org/?probe=778205b7cd) | Sep 02, 2024 |
| HP            | EliteBook 850 G1            | [c5f7728016](https://linux-hardware.org/?probe=c5f7728016) | Sep 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [ab4ea0dcac](https://linux-hardware.org/?probe=ab4ea0dcac) | Sep 01, 2024 |
| Acer          | A515-55                     | [a5c9d772bf](https://linux-hardware.org/?probe=a5c9d772bf) | Sep 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [2c9b283a47](https://linux-hardware.org/?probe=2c9b283a47) | Sep 01, 2024 |
| HP            | ENVY Laptop 17t-cw100       | [cce2bf73eb](https://linux-hardware.org/?probe=cce2bf73eb) | Sep 01, 2024 |
| HP            | EliteBook 850 G1            | [ee85acc05d](https://linux-hardware.org/?probe=ee85acc05d) | Sep 01, 2024 |
| Samsung       | 700Z7C                      | [2af9db39e9](https://linux-hardware.org/?probe=2af9db39e9) | Sep 01, 2024 |
| Apple         | MacBookPro8,1               | [62edf6c10f](https://linux-hardware.org/?probe=62edf6c10f) | Sep 01, 2024 |
| HP            | EliteBook 840 G2            | [70206460b9](https://linux-hardware.org/?probe=70206460b9) | Aug 31, 2024 |
| HP            | EliteBook 845 14 inch G9... | [8b86c31f23](https://linux-hardware.org/?probe=8b86c31f23) | Aug 31, 2024 |
| Dell          | Precision M4600             | [cbae618a59](https://linux-hardware.org/?probe=cbae618a59) | Aug 31, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | [0a47a5ee51](https://linux-hardware.org/?probe=0a47a5ee51) | Aug 31, 2024 |
| Dell          | Precision M4600             | [5252d14ef8](https://linux-hardware.org/?probe=5252d14ef8) | Aug 31, 2024 |
| Acer          | Swift SF114-34              | [f1c148d0f6](https://linux-hardware.org/?probe=f1c148d0f6) | Aug 31, 2024 |
| Apple         | MacBookPro14,1              | [fcd8ec0f22](https://linux-hardware.org/?probe=fcd8ec0f22) | Aug 31, 2024 |
| Acer          | Swift SF114-34              | [c4ec927e26](https://linux-hardware.org/?probe=c4ec927e26) | Aug 31, 2024 |
| Fujitsu Si... | AMILO Li3710                | [189e41c872](https://linux-hardware.org/?probe=189e41c872) | Aug 31, 2024 |
| Lenovo        | ThinkPad T430 2349430       | [2e64baff6a](https://linux-hardware.org/?probe=2e64baff6a) | Aug 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [e7e08390e3](https://linux-hardware.org/?probe=e7e08390e3) | Aug 30, 2024 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [d329d90711](https://linux-hardware.org/?probe=d329d90711) | Aug 30, 2024 |
| Acer          | Aspire E5-475               | [8c11c9123e](https://linux-hardware.org/?probe=8c11c9123e) | Aug 30, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [e9c6b514ef](https://linux-hardware.org/?probe=e9c6b514ef) | Aug 30, 2024 |
| Apple         | MacBookPro11,1              | [fcd59758e3](https://linux-hardware.org/?probe=fcd59758e3) | Aug 30, 2024 |
| Dell          | Latitude E7240              | [81904cae54](https://linux-hardware.org/?probe=81904cae54) | Aug 30, 2024 |
| HP            | ProBook 6450b               | [f5302408a2](https://linux-hardware.org/?probe=f5302408a2) | Aug 30, 2024 |
| HP            | Pavilion g7                 | [c4630f4d2c](https://linux-hardware.org/?probe=c4630f4d2c) | Aug 29, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [3a7f0764b0](https://linux-hardware.org/?probe=3a7f0764b0) | Aug 29, 2024 |
| ASUSTek       | PU551JA                     | [53f643f10e](https://linux-hardware.org/?probe=53f643f10e) | Aug 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [7bb96789ca](https://linux-hardware.org/?probe=7bb96789ca) | Aug 29, 2024 |
| HP            | ZBook Studio G5             | [441ce69609](https://linux-hardware.org/?probe=441ce69609) | Aug 29, 2024 |
| HP            | ZBook Studio G5             | [01c25ba48a](https://linux-hardware.org/?probe=01c25ba48a) | Aug 29, 2024 |
| HP            | ProBook 450 G8              | [01c461d8b5](https://linux-hardware.org/?probe=01c461d8b5) | Aug 29, 2024 |
| ASUSTek       | PU551JA                     | [5f45b0b05c](https://linux-hardware.org/?probe=5f45b0b05c) | Aug 29, 2024 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [29dbb95c7c](https://linux-hardware.org/?probe=29dbb95c7c) | Aug 29, 2024 |
| Comexr        | Clevo                       | [fe48e0834d](https://linux-hardware.org/?probe=fe48e0834d) | Aug 28, 2024 |
| Unknown       | Unknown                     | [5e7a0795ec](https://linux-hardware.org/?probe=5e7a0795ec) | Aug 28, 2024 |
| MSI           | Bravo 15 C7VFKP             | [1a65a8d444](https://linux-hardware.org/?probe=1a65a8d444) | Aug 28, 2024 |
| Lenovo        | ThinkPad L460 20FVS0PA1H    | [be660ad979](https://linux-hardware.org/?probe=be660ad979) | Aug 28, 2024 |
| Toshiba       | TECRA S11                   | [4617ceeeec](https://linux-hardware.org/?probe=4617ceeeec) | Aug 28, 2024 |
| ASUSTek       | X540LJ                      | [82349f49b3](https://linux-hardware.org/?probe=82349f49b3) | Aug 28, 2024 |
| ASUSTek       | G750JX                      | [9e273b8471](https://linux-hardware.org/?probe=9e273b8471) | Aug 27, 2024 |
| ASUSTek       | G750JX                      | [24468fe950](https://linux-hardware.org/?probe=24468fe950) | Aug 27, 2024 |
| Toshiba       | Satellite A200              | [d03a05b58f](https://linux-hardware.org/?probe=d03a05b58f) | Aug 27, 2024 |
| Lenovo        | V14-IIL 82C4                | [6cce07e59a](https://linux-hardware.org/?probe=6cce07e59a) | Aug 27, 2024 |
| Lenovo        | G50-80 80R0                 | [fef5f4b6e6](https://linux-hardware.org/?probe=fef5f4b6e6) | Aug 27, 2024 |
| Medion        | P662X                       | [05299731e3](https://linux-hardware.org/?probe=05299731e3) | Aug 27, 2024 |
| ASUSTek       | K93SV                       | [d5fdd94286](https://linux-hardware.org/?probe=d5fdd94286) | Aug 27, 2024 |
| ASUSTek       | K93SV                       | [22b7252c1e](https://linux-hardware.org/?probe=22b7252c1e) | Aug 27, 2024 |
| HUAWEI        | BOHB-WAX9                   | [93ade204e2](https://linux-hardware.org/?probe=93ade204e2) | Aug 26, 2024 |
| HP            | ProBook 6450b               | [005b0c483a](https://linux-hardware.org/?probe=005b0c483a) | Aug 26, 2024 |
| Apple         | MacBookPro8,1               | [39f15cf286](https://linux-hardware.org/?probe=39f15cf286) | Aug 26, 2024 |
| Lenovo        | G50-80 80R0                 | [e2934da80c](https://linux-hardware.org/?probe=e2934da80c) | Aug 26, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [1d4609e7fd](https://linux-hardware.org/?probe=1d4609e7fd) | Aug 25, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [81f1605c7a](https://linux-hardware.org/?probe=81f1605c7a) | Aug 25, 2024 |
| Acer          | Aspire A515-51              | [9e95831bce](https://linux-hardware.org/?probe=9e95831bce) | Aug 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5b0fc0a233](https://linux-hardware.org/?probe=5b0fc0a233) | Aug 25, 2024 |
| Lenovo        | Y720-15IKB 80VR             | [39bbdd5225](https://linux-hardware.org/?probe=39bbdd5225) | Aug 25, 2024 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [49be3fb790](https://linux-hardware.org/?probe=49be3fb790) | Aug 25, 2024 |
| Acer          | Aspire VN7-792G             | [5b9c3467d8](https://linux-hardware.org/?probe=5b9c3467d8) | Aug 25, 2024 |
| Apple         | MacBook4,1                  | [ee38a0b3e4](https://linux-hardware.org/?probe=ee38a0b3e4) | Aug 25, 2024 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [7380931289](https://linux-hardware.org/?probe=7380931289) | Aug 24, 2024 |
| Lenovo        | ThinkPad T430 2349430       | [14f0a3544e](https://linux-hardware.org/?probe=14f0a3544e) | Aug 24, 2024 |
| Lenovo        | G510 20238                  | [cc4ef84b83](https://linux-hardware.org/?probe=cc4ef84b83) | Aug 24, 2024 |
| Lenovo        | ThinkPad T430 2349430       | [f4d43322a9](https://linux-hardware.org/?probe=f4d43322a9) | Aug 24, 2024 |
| Lenovo        | G510 20238                  | [dd429b2d62](https://linux-hardware.org/?probe=dd429b2d62) | Aug 23, 2024 |
| HP            | 15 TS                       | [b23e3c74fc](https://linux-hardware.org/?probe=b23e3c74fc) | Aug 23, 2024 |
| Apple         | MacBook4,1                  | [d50c6168cd](https://linux-hardware.org/?probe=d50c6168cd) | Aug 23, 2024 |
| HP            | 15 TS                       | [1498cfa38b](https://linux-hardware.org/?probe=1498cfa38b) | Aug 23, 2024 |
| HP            | EliteBook 845 14 inch G1... | [d4e3d0d8b8](https://linux-hardware.org/?probe=d4e3d0d8b8) | Aug 23, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [aebff54b72](https://linux-hardware.org/?probe=aebff54b72) | Aug 23, 2024 |
| Technopc      | TI15N33W                    | [4845d584a3](https://linux-hardware.org/?probe=4845d584a3) | Aug 23, 2024 |
| Technopc      | TI15N33W                    | [9ec875165c](https://linux-hardware.org/?probe=9ec875165c) | Aug 23, 2024 |
| Unknown       | Unknown                     | [d7d0b9502f](https://linux-hardware.org/?probe=d7d0b9502f) | Aug 22, 2024 |
| HUAWEI        | HVY-WXX9                    | [1fa7cb693c](https://linux-hardware.org/?probe=1fa7cb693c) | Aug 22, 2024 |
| Dell          | Precision M4600             | [3d6e13b7f2](https://linux-hardware.org/?probe=3d6e13b7f2) | Aug 22, 2024 |
| HP            | ProBook 470 G1              | [4cf40ec6f2](https://linux-hardware.org/?probe=4cf40ec6f2) | Aug 22, 2024 |
| HP            | ProBook 470 G1              | [e68252f252](https://linux-hardware.org/?probe=e68252f252) | Aug 22, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [72eca7fd69](https://linux-hardware.org/?probe=72eca7fd69) | Aug 22, 2024 |
| ASUSTek       | N551JK                      | [68cbab902c](https://linux-hardware.org/?probe=68cbab902c) | Aug 22, 2024 |
| Acer          | AO722                       | [edeba77549](https://linux-hardware.org/?probe=edeba77549) | Aug 21, 2024 |
| HP            | Compaq CQ58                 | [26e954c5fa](https://linux-hardware.org/?probe=26e954c5fa) | Aug 21, 2024 |
| MSI           | GF63 Thin 9RCX              | [6ebcf05841](https://linux-hardware.org/?probe=6ebcf05841) | Aug 21, 2024 |
| HP            | ZBook 14u G6                | [7a917ff115](https://linux-hardware.org/?probe=7a917ff115) | Aug 21, 2024 |
| Dell          | G15 5530                    | [f8aa12b742](https://linux-hardware.org/?probe=f8aa12b742) | Aug 20, 2024 |
| Toshiba       | dynabook TX/66JBL           | [ee2b9fdb4c](https://linux-hardware.org/?probe=ee2b9fdb4c) | Aug 20, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [326698319c](https://linux-hardware.org/?probe=326698319c) | Aug 20, 2024 |
| HP            | EliteBook 8540p             | [9e8a7b912b](https://linux-hardware.org/?probe=9e8a7b912b) | Aug 19, 2024 |
| Toshiba       | dynabook TX/66JBL           | [167feb9699](https://linux-hardware.org/?probe=167feb9699) | Aug 19, 2024 |
| Lenovo        | ThinkPad T420 4180CV1       | [104ed80155](https://linux-hardware.org/?probe=104ed80155) | Aug 19, 2024 |
| Acer          | Nitro AN515-44              | [0a1309c9da](https://linux-hardware.org/?probe=0a1309c9da) | Aug 19, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [5af8f48189](https://linux-hardware.org/?probe=5af8f48189) | Aug 19, 2024 |
| Apple         | MacBookPro15,1              | [e688cf6bf0](https://linux-hardware.org/?probe=e688cf6bf0) | Aug 18, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f461574001](https://linux-hardware.org/?probe=f461574001) | Aug 18, 2024 |
| HP            | ProBook 6570b               | [742d48f2c5](https://linux-hardware.org/?probe=742d48f2c5) | Aug 18, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [43c423e685](https://linux-hardware.org/?probe=43c423e685) | Aug 18, 2024 |
| Medion        | S5610                       | [937ba1b04e](https://linux-hardware.org/?probe=937ba1b04e) | Aug 18, 2024 |
| Apple         | MacBookPro11,5              | [aadf5e1578](https://linux-hardware.org/?probe=aadf5e1578) | Aug 18, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d55a76a395](https://linux-hardware.org/?probe=d55a76a395) | Aug 17, 2024 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [c478363aa1](https://linux-hardware.org/?probe=c478363aa1) | Aug 17, 2024 |
| Medion        | S5610                       | [a01de63ae7](https://linux-hardware.org/?probe=a01de63ae7) | Aug 17, 2024 |
| Avell High... | A60 MUV                     | [4ae33dd238](https://linux-hardware.org/?probe=4ae33dd238) | Aug 17, 2024 |
| Lenovo        | V130-15IKB 81HN             | [8ec02ba84a](https://linux-hardware.org/?probe=8ec02ba84a) | Aug 16, 2024 |
| Lenovo        | V130-15IKB 81HN             | [72e2ad48fe](https://linux-hardware.org/?probe=72e2ad48fe) | Aug 16, 2024 |
| Dell          | Inspiron 5447               | [3ca233c313](https://linux-hardware.org/?probe=3ca233c313) | Aug 16, 2024 |
| Toshiba       | Satellite L50-B             | [fe95a4d9d9](https://linux-hardware.org/?probe=fe95a4d9d9) | Aug 16, 2024 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | [c97ceda149](https://linux-hardware.org/?probe=c97ceda149) | Aug 16, 2024 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [b4deb0d4f1](https://linux-hardware.org/?probe=b4deb0d4f1) | Aug 15, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7e1480b2f1](https://linux-hardware.org/?probe=7e1480b2f1) | Aug 15, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [76488f2345](https://linux-hardware.org/?probe=76488f2345) | Aug 15, 2024 |
| HP            | Laptop 14-ck2xxx            | [d1700c44a6](https://linux-hardware.org/?probe=d1700c44a6) | Aug 14, 2024 |
| HUAWEI        | HVY-WXX9                    | [456cf54e91](https://linux-hardware.org/?probe=456cf54e91) | Aug 14, 2024 |
| Acer          | Aspire ES1-711G             | [6cebec2d99](https://linux-hardware.org/?probe=6cebec2d99) | Aug 14, 2024 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [4c1c6b8a9b](https://linux-hardware.org/?probe=4c1c6b8a9b) | Aug 14, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5bb65aad1a](https://linux-hardware.org/?probe=5bb65aad1a) | Aug 14, 2024 |
| Apple         | MacBookPro5,5               | [1ffe238cbe](https://linux-hardware.org/?probe=1ffe238cbe) | Aug 14, 2024 |
| Sony          | VPCF215FX                   | [0d96c2f35a](https://linux-hardware.org/?probe=0d96c2f35a) | Aug 14, 2024 |
| Acer          | Nitro AN515-52              | [4105f16710](https://linux-hardware.org/?probe=4105f16710) | Aug 14, 2024 |
| Acer          | Nitro AN515-52              | [f7706f241c](https://linux-hardware.org/?probe=f7706f241c) | Aug 14, 2024 |
| HUAWEI        | MCLG-XX                     | [06195350d9](https://linux-hardware.org/?probe=06195350d9) | Aug 13, 2024 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [ba3fa007b2](https://linux-hardware.org/?probe=ba3fa007b2) | Aug 13, 2024 |
| Unknown       | Unknown                     | [bbbbf2ec13](https://linux-hardware.org/?probe=bbbbf2ec13) | Aug 13, 2024 |
| Apple         | MacBookPro7,1               | [949e7f3ff5](https://linux-hardware.org/?probe=949e7f3ff5) | Aug 13, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [aee1dc9bfe](https://linux-hardware.org/?probe=aee1dc9bfe) | Aug 13, 2024 |
| ASUSTek       | K70AC                       | [a7c5cd1b49](https://linux-hardware.org/?probe=a7c5cd1b49) | Aug 13, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [e322a156a0](https://linux-hardware.org/?probe=e322a156a0) | Aug 13, 2024 |
| Dell          | Venue 11 Pro 7130 MS        | [50090c21e6](https://linux-hardware.org/?probe=50090c21e6) | Aug 12, 2024 |
| Dell          | Venue 11 Pro 7130 MS        | [5041509cd8](https://linux-hardware.org/?probe=5041509cd8) | Aug 12, 2024 |
| HP            | Compaq nx6325 (EY785AV)     | [98b9ea7db1](https://linux-hardware.org/?probe=98b9ea7db1) | Aug 12, 2024 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [4e79a5dba0](https://linux-hardware.org/?probe=4e79a5dba0) | Aug 12, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [54c497ea27](https://linux-hardware.org/?probe=54c497ea27) | Aug 12, 2024 |
| Google        | Atlas                       | [934ab48745](https://linux-hardware.org/?probe=934ab48745) | Aug 12, 2024 |
| Dell          | Inspiron 1520               | [6a36187990](https://linux-hardware.org/?probe=6a36187990) | Aug 12, 2024 |
| Samsung       | 270E5J/2570EJ               | [a36ab4dcb6](https://linux-hardware.org/?probe=a36ab4dcb6) | Aug 12, 2024 |
| Sony          | VGN-SR5                     | [31e74dae77](https://linux-hardware.org/?probe=31e74dae77) | Aug 11, 2024 |
| Proline       | V14664P                     | [af66b82497](https://linux-hardware.org/?probe=af66b82497) | Aug 11, 2024 |
| Apple         | MacBookPro7,1               | [02e52027d7](https://linux-hardware.org/?probe=02e52027d7) | Aug 11, 2024 |
| Proline       | V14664P                     | [edb4696ad6](https://linux-hardware.org/?probe=edb4696ad6) | Aug 11, 2024 |
| HP            | Compaq nx6325 (EY785AV)     | [c4dc54fc5c](https://linux-hardware.org/?probe=c4dc54fc5c) | Aug 11, 2024 |
| HP            | ProBook 430 G5              | [f872b7c5ea](https://linux-hardware.org/?probe=f872b7c5ea) | Aug 11, 2024 |
| Exo           | C147                        | [9353e8ee75](https://linux-hardware.org/?probe=9353e8ee75) | Aug 11, 2024 |
| Dell          | XPS 17 9710                 | [9f4e780101](https://linux-hardware.org/?probe=9f4e780101) | Aug 11, 2024 |
| Dell          | Latitude E7270              | [420bcd60cb](https://linux-hardware.org/?probe=420bcd60cb) | Aug 11, 2024 |
| Dell          | Latitude 5290 2-in-1        | [a22f43f0b6](https://linux-hardware.org/?probe=a22f43f0b6) | Aug 10, 2024 |
| Apple         | MacBookPro7,1               | [39479dacac](https://linux-hardware.org/?probe=39479dacac) | Aug 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [bae0e4f85c](https://linux-hardware.org/?probe=bae0e4f85c) | Aug 09, 2024 |
| Dell          | Latitude 5290 2-in-1        | [917ad0d1c2](https://linux-hardware.org/?probe=917ad0d1c2) | Aug 09, 2024 |
| Lenovo        | ThinkPad W520 4282A57       | [c8cc2e437e](https://linux-hardware.org/?probe=c8cc2e437e) | Aug 09, 2024 |
| Dell          | Latitude 3420               | [dbe73490d2](https://linux-hardware.org/?probe=dbe73490d2) | Aug 08, 2024 |
| Positivo      | S14CT01                     | [4dd77dfb05](https://linux-hardware.org/?probe=4dd77dfb05) | Aug 08, 2024 |
| Dell          | Latitude 7640               | [cd57286388](https://linux-hardware.org/?probe=cd57286388) | Aug 08, 2024 |
| Sony          | VGN-CR21S_W                 | [807e3b496b](https://linux-hardware.org/?probe=807e3b496b) | Aug 08, 2024 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [ffd8750c5a](https://linux-hardware.org/?probe=ffd8750c5a) | Aug 08, 2024 |
| HP            | Pavilion dv2700             | [e8050764e2](https://linux-hardware.org/?probe=e8050764e2) | Aug 07, 2024 |
| Lenovo        | ThinkPad T420 4180CV1       | [465adc8932](https://linux-hardware.org/?probe=465adc8932) | Aug 07, 2024 |
| Lenovo        | ThinkPad T430s 2356JZ9      | [cc82e0e768](https://linux-hardware.org/?probe=cc82e0e768) | Aug 07, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [5580226a84](https://linux-hardware.org/?probe=5580226a84) | Aug 07, 2024 |
| HP            | Compaq Presario CQ61        | [46c8b43148](https://linux-hardware.org/?probe=46c8b43148) | Aug 06, 2024 |
| ASUSTek       | ZenBook Pro Duo UX581GV     | [41abcb5ab1](https://linux-hardware.org/?probe=41abcb5ab1) | Aug 06, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [999b794c48](https://linux-hardware.org/?probe=999b794c48) | Aug 06, 2024 |
| Apple         | MacBookAir1,1               | [ea0e1dc87f](https://linux-hardware.org/?probe=ea0e1dc87f) | Aug 06, 2024 |
| Toshiba       | QOSMIO X775                 | [0b2514d066](https://linux-hardware.org/?probe=0b2514d066) | Aug 06, 2024 |
| Apple         | MacBookPro6,2               | [6abef655ee](https://linux-hardware.org/?probe=6abef655ee) | Aug 05, 2024 |
| Dell          | Inspiron 3521               | [1fb8100a86](https://linux-hardware.org/?probe=1fb8100a86) | Aug 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [5b4b2e4b60](https://linux-hardware.org/?probe=5b4b2e4b60) | Aug 05, 2024 |
| HP            | Laptop 15-dw0xxx            | [11904eecc5](https://linux-hardware.org/?probe=11904eecc5) | Aug 05, 2024 |
| Mediacom      | SmartBook 14 FullHD - SB... | [c43de84b40](https://linux-hardware.org/?probe=c43de84b40) | Aug 05, 2024 |
| Mediacom      | SmartBook 14 FullHD - SB... | [bd3590e616](https://linux-hardware.org/?probe=bd3590e616) | Aug 05, 2024 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [b3dd1179a9](https://linux-hardware.org/?probe=b3dd1179a9) | Aug 05, 2024 |
| Dell          | Inspiron 5566               | [f7563bbfd1](https://linux-hardware.org/?probe=f7563bbfd1) | Aug 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [c81082512f](https://linux-hardware.org/?probe=c81082512f) | Aug 04, 2024 |
| Compaq        | PRESARIOCQ18                | [7dc3f2f2b2](https://linux-hardware.org/?probe=7dc3f2f2b2) | Aug 04, 2024 |
| HP            | Compaq 6820s                | [6a3adf5719](https://linux-hardware.org/?probe=6a3adf5719) | Aug 04, 2024 |
| MSI           | GL72 6QC                    | [b76a6d9ef2](https://linux-hardware.org/?probe=b76a6d9ef2) | Aug 04, 2024 |
| Lenovo        | Y720-15IKB 80VR             | [b433b2dd1d](https://linux-hardware.org/?probe=b433b2dd1d) | Aug 03, 2024 |
| Dell          | Inspiron 7720               | [81d069fd16](https://linux-hardware.org/?probe=81d069fd16) | Aug 03, 2024 |
| Samsung       | R530/R730                   | [c3b4d76a35](https://linux-hardware.org/?probe=c3b4d76a35) | Aug 03, 2024 |
| HP            | Laptop 15s-du3xxx           | [b08bd4b9be](https://linux-hardware.org/?probe=b08bd4b9be) | Aug 03, 2024 |
| Samsung       | R530/R730                   | [91671c5d85](https://linux-hardware.org/?probe=91671c5d85) | Aug 03, 2024 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [b7b82c2b2b](https://linux-hardware.org/?probe=b7b82c2b2b) | Aug 02, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [9000222a9f](https://linux-hardware.org/?probe=9000222a9f) | Aug 02, 2024 |
| Toshiba       | Satellite L50-B             | [00b4917faf](https://linux-hardware.org/?probe=00b4917faf) | Aug 02, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | [41bee1a398](https://linux-hardware.org/?probe=41bee1a398) | Aug 02, 2024 |
| Google        | Dorp                        | [15c619b435](https://linux-hardware.org/?probe=15c619b435) | Aug 02, 2024 |
| Jumper        | EZbook                      | [93a7fe3b09](https://linux-hardware.org/?probe=93a7fe3b09) | Aug 02, 2024 |
| HP            | 425                         | [aa91584619](https://linux-hardware.org/?probe=aa91584619) | Aug 02, 2024 |
| Dell          | Latitude 5420               | [f379ec2483](https://linux-hardware.org/?probe=f379ec2483) | Aug 02, 2024 |
| HP            | ENVY Laptop 13-ba1xxx       | [456bb30cc7](https://linux-hardware.org/?probe=456bb30cc7) | Aug 01, 2024 |
| Jumper        | EZbook                      | [1b6472ac3b](https://linux-hardware.org/?probe=1b6472ac3b) | Aug 01, 2024 |
| HP            | Notebook                    | [de52d867fa](https://linux-hardware.org/?probe=de52d867fa) | Aug 01, 2024 |
| Lenovo        | B550 0880                   | [37063d0481](https://linux-hardware.org/?probe=37063d0481) | Aug 01, 2024 |
| Lenovo        | B550 0880                   | [903fec303d](https://linux-hardware.org/?probe=903fec303d) | Aug 01, 2024 |
| NSX           | ARGUS                       | [3361cc21ed](https://linux-hardware.org/?probe=3361cc21ed) | Aug 01, 2024 |
| ASUSTek       | ASUS Vivobook Pro 15 N65... | [255cbfe1e4](https://linux-hardware.org/?probe=255cbfe1e4) | Aug 01, 2024 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | [3e4a1b333e](https://linux-hardware.org/?probe=3e4a1b333e) | Aug 01, 2024 |
| HP            | Notebook                    | [1c268d4b83](https://linux-hardware.org/?probe=1c268d4b83) | Aug 01, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [0024dd948a](https://linux-hardware.org/?probe=0024dd948a) | Jul 31, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [0ada37cfe0](https://linux-hardware.org/?probe=0ada37cfe0) | Jul 31, 2024 |
| Gigabyte      | X7                          | [677ac703ed](https://linux-hardware.org/?probe=677ac703ed) | Jul 31, 2024 |
| Dell          | Inspiron 5547               | [0d1c2ea0af](https://linux-hardware.org/?probe=0d1c2ea0af) | Jul 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ee57a214a5](https://linux-hardware.org/?probe=ee57a214a5) | Jul 31, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [846f130e8f](https://linux-hardware.org/?probe=846f130e8f) | Jul 30, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [99bd685bab](https://linux-hardware.org/?probe=99bd685bab) | Jul 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [10ab4142f0](https://linux-hardware.org/?probe=10ab4142f0) | Jul 30, 2024 |
| Sony          | VGN-FZ240N                  | [f0ba948fd2](https://linux-hardware.org/?probe=f0ba948fd2) | Jul 29, 2024 |
| HP            | 350 G1                      | [624229ef84](https://linux-hardware.org/?probe=624229ef84) | Jul 29, 2024 |
| HP            | 350 G1                      | [16df7a07fe](https://linux-hardware.org/?probe=16df7a07fe) | Jul 29, 2024 |
| HP            | 15 TS                       | [75411019b4](https://linux-hardware.org/?probe=75411019b4) | Jul 28, 2024 |
| HP            | 15 TS                       | [1407e7426f](https://linux-hardware.org/?probe=1407e7426f) | Jul 28, 2024 |
| Acer          | Aspire M5-583P              | [9b35f780ba](https://linux-hardware.org/?probe=9b35f780ba) | Jul 28, 2024 |
| HP            | Laptop 15-dy2xxx            | [97dc75cfad](https://linux-hardware.org/?probe=97dc75cfad) | Jul 28, 2024 |
| Acer          | Aspire V3-111P              | [ebb70938f3](https://linux-hardware.org/?probe=ebb70938f3) | Jul 28, 2024 |
| Acer          | Aspire V3-111P              | [fcea8ffb60](https://linux-hardware.org/?probe=fcea8ffb60) | Jul 28, 2024 |
| Medion        | S5610                       | [9f7039a688](https://linux-hardware.org/?probe=9f7039a688) | Jul 28, 2024 |
| Wortmann      | FR1220578_1470116           | [45c3f64216](https://linux-hardware.org/?probe=45c3f64216) | Jul 28, 2024 |
| HUAWEI        | MCLF-XX                     | [555f2bbeb6](https://linux-hardware.org/?probe=555f2bbeb6) | Jul 28, 2024 |
| Dell          | XPS 9315                    | [d380015a0d](https://linux-hardware.org/?probe=d380015a0d) | Jul 28, 2024 |
| Dell          | Inspiron 5420               | [66be781f5f](https://linux-hardware.org/?probe=66be781f5f) | Jul 28, 2024 |
| Dell          | Vostro 1000                 | [5fa48fafb4](https://linux-hardware.org/?probe=5fa48fafb4) | Jul 27, 2024 |
| Dell          | Vostro 1000                 | [35a0638ceb](https://linux-hardware.org/?probe=35a0638ceb) | Jul 27, 2024 |
| Toshiba       | STI NI 1401                 | [fcd906e15e](https://linux-hardware.org/?probe=fcd906e15e) | Jul 27, 2024 |
| Toshiba       | STI NI 1401                 | [5990ba6215](https://linux-hardware.org/?probe=5990ba6215) | Jul 27, 2024 |
| Lenovo        | IdeaPad U410                | [b8b8a7241d](https://linux-hardware.org/?probe=b8b8a7241d) | Jul 27, 2024 |
| Dell          | Latitude 7280               | [a9387349cd](https://linux-hardware.org/?probe=a9387349cd) | Jul 27, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | [bc4f13dbe8](https://linux-hardware.org/?probe=bc4f13dbe8) | Jul 27, 2024 |
| Apple         | MacBookPro6,2               | [a6f1ca976f](https://linux-hardware.org/?probe=a6f1ca976f) | Jul 27, 2024 |
| ASUSTek       | X550LD                      | [5cc7127ad9](https://linux-hardware.org/?probe=5cc7127ad9) | Jul 26, 2024 |
| Dell          | Latitude E4300              | [c4a12fa858](https://linux-hardware.org/?probe=c4a12fa858) | Jul 26, 2024 |
| Alienware     | 14                          | [4e739be9ba](https://linux-hardware.org/?probe=4e739be9ba) | Jul 26, 2024 |
| Acer          | Aspire M5-583P              | [5c5abd6cdc](https://linux-hardware.org/?probe=5c5abd6cdc) | Jul 25, 2024 |
| Dell          | Precision M4800             | [94d3bf01cc](https://linux-hardware.org/?probe=94d3bf01cc) | Jul 25, 2024 |
| ASUSTek       | X555LN                      | [1af7465509](https://linux-hardware.org/?probe=1af7465509) | Jul 25, 2024 |
| Apple         | MacBook6,1                  | [eac4844547](https://linux-hardware.org/?probe=eac4844547) | Jul 25, 2024 |
| ASUSTek       | K93SV                       | [5d544a09dd](https://linux-hardware.org/?probe=5d544a09dd) | Jul 25, 2024 |
| Toshiba       | QOSMIO X505                 | [27d3cf680a](https://linux-hardware.org/?probe=27d3cf680a) | Jul 25, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [0012829b12](https://linux-hardware.org/?probe=0012829b12) | Jul 24, 2024 |
| Lenovo        | ThinkPad T450s 20BWS2BC0... | [f4ac392dc5](https://linux-hardware.org/?probe=f4ac392dc5) | Jul 24, 2024 |
| HP            | 14                          | [6381dc091b](https://linux-hardware.org/?probe=6381dc091b) | Jul 24, 2024 |
| Lenovo        | V15 G4 AMN 82YU             | [c1f7c3f868](https://linux-hardware.org/?probe=c1f7c3f868) | Jul 24, 2024 |
| Lenovo        | ThinkPad Edge E420s 4401... | [d82b3e19a7](https://linux-hardware.org/?probe=d82b3e19a7) | Jul 24, 2024 |
| HP            | ENVY TouchSmart Sleekboo... | [627c85bc2a](https://linux-hardware.org/?probe=627c85bc2a) | Jul 24, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [a09f0b552b](https://linux-hardware.org/?probe=a09f0b552b) | Jul 24, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [5bd1845051](https://linux-hardware.org/?probe=5bd1845051) | Jul 24, 2024 |
| Apple         | MacBookPro11,1              | [b851bf3a8e](https://linux-hardware.org/?probe=b851bf3a8e) | Jul 23, 2024 |
| Intel         | HM87                        | [56ee39f6b2](https://linux-hardware.org/?probe=56ee39f6b2) | Jul 23, 2024 |
| HP            | Pavilion 17                 | [4252856a23](https://linux-hardware.org/?probe=4252856a23) | Jul 23, 2024 |
| Acer          | Aspire E1-571               | [c1984136dc](https://linux-hardware.org/?probe=c1984136dc) | Jul 23, 2024 |
| Toshiba       | Satellite L40               | [dac6bed959](https://linux-hardware.org/?probe=dac6bed959) | Jul 23, 2024 |
| Toshiba       | Satellite L40               | [be27198d96](https://linux-hardware.org/?probe=be27198d96) | Jul 23, 2024 |
| HP            | Laptop 14-cm0xxx            | [7f611e590b](https://linux-hardware.org/?probe=7f611e590b) | Jul 23, 2024 |
| HP            | Laptop 14-cm0xxx            | [763e1ecec4](https://linux-hardware.org/?probe=763e1ecec4) | Jul 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [5cd2fdb7f3](https://linux-hardware.org/?probe=5cd2fdb7f3) | Jul 23, 2024 |
| Lenovo        | Slim 7 14IRP8 83A4          | [3d4bb98dd8](https://linux-hardware.org/?probe=3d4bb98dd8) | Jul 23, 2024 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [afc53a28ac](https://linux-hardware.org/?probe=afc53a28ac) | Jul 23, 2024 |
| ASUSTek       | X555LN                      | [f80f9105c0](https://linux-hardware.org/?probe=f80f9105c0) | Jul 22, 2024 |
| HP            | 14                          | [0c704da202](https://linux-hardware.org/?probe=0c704da202) | Jul 22, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [dd6b222ed9](https://linux-hardware.org/?probe=dd6b222ed9) | Jul 22, 2024 |
| HP            | 2000                        | [08dc7124d2](https://linux-hardware.org/?probe=08dc7124d2) | Jul 22, 2024 |
| Acer          | Aspire A315-41              | [288f9de47d](https://linux-hardware.org/?probe=288f9de47d) | Jul 21, 2024 |
| Acer          | Aspire A115-32              | [abbcb6fa05](https://linux-hardware.org/?probe=abbcb6fa05) | Jul 21, 2024 |
| HP            | Pavilion 15                 | [a644b24aa1](https://linux-hardware.org/?probe=a644b24aa1) | Jul 20, 2024 |
| Dell          | Vostro 15 3510              | [b48a6b3ff7](https://linux-hardware.org/?probe=b48a6b3ff7) | Jul 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [977e94dbb3](https://linux-hardware.org/?probe=977e94dbb3) | Jul 20, 2024 |
| Toshiba       | QOSMIO X770                 | [c79d310c82](https://linux-hardware.org/?probe=c79d310c82) | Jul 20, 2024 |
| Dell          | Latitude 7390               | [7fbd8bda9a](https://linux-hardware.org/?probe=7fbd8bda9a) | Jul 20, 2024 |
| Toshiba       | QOSMIO X770                 | [8bc354cc7e](https://linux-hardware.org/?probe=8bc354cc7e) | Jul 20, 2024 |
| HP            | Pavilion 15                 | [0bea89495e](https://linux-hardware.org/?probe=0bea89495e) | Jul 20, 2024 |
| Acer          | Aspire A115-32              | [671a50cf4a](https://linux-hardware.org/?probe=671a50cf4a) | Jul 20, 2024 |
| Shenzhen B... | XN116B                      | [4ac9551481](https://linux-hardware.org/?probe=4ac9551481) | Jul 19, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [2c5c1a9aad](https://linux-hardware.org/?probe=2c5c1a9aad) | Jul 19, 2024 |
| Apple         | MacBookPro8,3               | [e12fd23e03](https://linux-hardware.org/?probe=e12fd23e03) | Jul 19, 2024 |
| Sony          | VGN-CR21S_W                 | [a6c8bc7a5c](https://linux-hardware.org/?probe=a6c8bc7a5c) | Jul 19, 2024 |
| Acer          | Nitro AN16-41               | [b79b63e5b6](https://linux-hardware.org/?probe=b79b63e5b6) | Jul 19, 2024 |
| Lenovo        | ThinkPad W530 2447HU5       | [c0c94e9bc3](https://linux-hardware.org/?probe=c0c94e9bc3) | Jul 19, 2024 |
| Lenovo        | ThinkPad W530 2447HU5       | [49ccd6c338](https://linux-hardware.org/?probe=49ccd6c338) | Jul 18, 2024 |
| Intel         | HM87                        | [5fd45faafb](https://linux-hardware.org/?probe=5fd45faafb) | Jul 18, 2024 |
| HP            | Pavilion 15                 | [b8ce888d87](https://linux-hardware.org/?probe=b8ce888d87) | Jul 18, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | [04aa911ebd](https://linux-hardware.org/?probe=04aa911ebd) | Jul 18, 2024 |
| Toshiba       | Satellite L350              | [cadf8c597e](https://linux-hardware.org/?probe=cadf8c597e) | Jul 18, 2024 |
| Apple         | MacBookPro14,2              | [5a98ca65c2](https://linux-hardware.org/?probe=5a98ca65c2) | Jul 18, 2024 |
| HP            | ENVY TS 15                  | [4896fc7c0e](https://linux-hardware.org/?probe=4896fc7c0e) | Jul 18, 2024 |
| Apple         | MacBookPro5,5               | [2e811ff6bf](https://linux-hardware.org/?probe=2e811ff6bf) | Jul 18, 2024 |
| ASUSTek       | X441UAK                     | [1eaca5d0f2](https://linux-hardware.org/?probe=1eaca5d0f2) | Jul 17, 2024 |
| Dell          | Latitude 5420               | [888c0e84bc](https://linux-hardware.org/?probe=888c0e84bc) | Jul 16, 2024 |
| Acer          | Aspire 5750G                | [f88408c7aa](https://linux-hardware.org/?probe=f88408c7aa) | Jul 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [c655d99937](https://linux-hardware.org/?probe=c655d99937) | Jul 16, 2024 |
| HP            | ProBook 4510s               | [3cc75dca74](https://linux-hardware.org/?probe=3cc75dca74) | Jul 16, 2024 |
| Alienware     | 14                          | [83f7f47ab3](https://linux-hardware.org/?probe=83f7f47ab3) | Jul 15, 2024 |
| Google        | Babytiger                   | [69ef38ce4f](https://linux-hardware.org/?probe=69ef38ce4f) | Jul 15, 2024 |
| Lenovo        | ThinkPad T430 23476W7       | [9033123c38](https://linux-hardware.org/?probe=9033123c38) | Jul 15, 2024 |
| Lenovo        | ThinkPad P50 20EQS0SS02     | [d40bef0611](https://linux-hardware.org/?probe=d40bef0611) | Jul 15, 2024 |
| Samsung       | 305U1A                      | [ddff0d5e20](https://linux-hardware.org/?probe=ddff0d5e20) | Jul 15, 2024 |
| HP            | 255 G8 Notebook PC          | [0e4c7a00b7](https://linux-hardware.org/?probe=0e4c7a00b7) | Jul 14, 2024 |
| HP            | ENVY Notebook               | [9928856c6b](https://linux-hardware.org/?probe=9928856c6b) | Jul 14, 2024 |
| Lenovo        | ThinkPad T470 20HES0J500    | [d4dd892eb5](https://linux-hardware.org/?probe=d4dd892eb5) | Jul 14, 2024 |
| ASUSTek       | UL50VT                      | [bc1ff179a3](https://linux-hardware.org/?probe=bc1ff179a3) | Jul 14, 2024 |
| Toshiba       | Satellite C870-D7K          | [448a44a1ec](https://linux-hardware.org/?probe=448a44a1ec) | Jul 14, 2024 |
| HP            | Pavilion g4                 | [5908dbb276](https://linux-hardware.org/?probe=5908dbb276) | Jul 14, 2024 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [037fb75cc0](https://linux-hardware.org/?probe=037fb75cc0) | Jul 14, 2024 |
| Acer          | Nitro AN515-58              | [d9aeff835a](https://linux-hardware.org/?probe=d9aeff835a) | Jul 13, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Zorin 16 | 2271      | 46.73%  |
| Zorin 17 | 1440      | 29.63%  |
| Zorin 15 | 1034      | 21.28%  |
| Zorin 12 | 115       | 2.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Zorin | 4794      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 6.8.0-40-generic  | 150       | 2.72%   |
| 6.5.0-35-generic  | 150       | 2.72%   |
| 5.15.0-56-generic | 136       | 2.47%   |
| 6.8.0-49-generic  | 120       | 2.18%   |
| 6.5.0-41-generic  | 106       | 1.92%   |
| 5.11.0-38-generic | 103       | 1.87%   |
| 6.5.0-28-generic  | 102       | 1.85%   |
| 6.2.0-39-generic  | 102       | 1.85%   |
| 5.11.0-27-generic | 95        | 1.72%   |
| 6.8.0-45-generic  | 93        | 1.69%   |
| 5.15.0-52-generic | 93        | 1.69%   |
| 5.15.0-58-generic | 91        | 1.65%   |
| 5.15.0-46-generic | 88        | 1.6%    |
| 5.15.0-91-generic | 83        | 1.51%   |
| 6.5.0-45-generic  | 81        | 1.47%   |
| 6.8.0-47-generic  | 77        | 1.4%    |
| 6.5.0-26-generic  | 77        | 1.4%    |
| 5.13.0-30-generic | 74        | 1.34%   |
| 5.15.0-78-generic | 71        | 1.29%   |
| 6.8.0-48-generic  | 68        | 1.23%   |
| 5.3.0-40-generic  | 67        | 1.22%   |
| 5.11.0-37-generic | 66        | 1.2%    |
| 5.15.0-67-generic | 65        | 1.18%   |
| 5.11.0-40-generic | 64        | 1.16%   |
| 5.15.0-69-generic | 63        | 1.14%   |
| 5.11.0-41-generic | 63        | 1.14%   |
| 5.4.0-42-generic  | 61        | 1.11%   |
| 5.15.0-88-generic | 60        | 1.09%   |
| 5.13.0-39-generic | 60        | 1.09%   |
| 5.15.0-60-generic | 58        | 1.05%   |
| 6.5.0-27-generic  | 57        | 1.03%   |
| 5.15.0-71-generic | 57        | 1.03%   |
| 5.11.0-34-generic | 57        | 1.03%   |
| 6.5.0-21-generic  | 56        | 1.02%   |
| 5.15.0-76-generic | 56        | 1.02%   |
| 5.11.0-43-generic | 55        | 1%      |
| 6.8.0-50-generic  | 54        | 0.98%   |
| 6.5.0-25-generic  | 54        | 0.98%   |
| 5.3.0-46-generic  | 53        | 0.96%   |
| 6.5.0-15-generic  | 51        | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 1336      | 26.56%  |
| 6.5.0   | 821       | 16.32%  |
| 5.4.0   | 613       | 12.18%  |
| 5.11.0  | 549       | 10.91%  |
| 6.8.0   | 539       | 10.71%  |
| 5.13.0  | 406       | 8.07%   |
| 5.3.0   | 312       | 6.2%    |
| 4.15.0  | 111       | 2.21%   |
| 6.2.0   | 107       | 2.13%   |
| 5.0.0   | 89        | 1.77%   |
| 4.18.0  | 45        | 0.89%   |
| 5.8.0   | 24        | 0.48%   |
| 5.14.0  | 8         | 0.16%   |
| 6.3.13  | 6         | 0.12%   |
| 4.4.0   | 4         | 0.08%   |
| 6.11.0  | 3         | 0.06%   |
| 6.9.9   | 2         | 0.04%   |
| 6.8.7   | 2         | 0.04%   |
| 6.8.10  | 2         | 0.04%   |
| 6.5.7   | 2         | 0.04%   |
| 6.2.16  | 2         | 0.04%   |
| 5.6.0   | 2         | 0.04%   |
| 5.19.0  | 2         | 0.04%   |
| 5.18.15 | 2         | 0.04%   |
| 5.16.0  | 2         | 0.04%   |
| 5.10.0  | 2         | 0.04%   |
| 6.8.9   | 1         | 0.02%   |
| 6.8.12  | 1         | 0.02%   |
| 6.7.3   | 1         | 0.02%   |
| 6.6.7   | 1         | 0.02%   |
| 6.6.13  | 1         | 0.02%   |
| 6.6.10  | 1         | 0.02%   |
| 6.6.1   | 1         | 0.02%   |
| 6.3.2   | 1         | 0.02%   |
| 6.3.1   | 1         | 0.02%   |
| 6.2.14  | 1         | 0.02%   |
| 6.12.5  | 1         | 0.02%   |
| 6.12.2  | 1         | 0.02%   |
| 6.10.9  | 1         | 0.02%   |
| 6.10.2  | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 1339      | 26.63%  |
| 6.5     | 823       | 16.37%  |
| 5.4     | 615       | 12.23%  |
| 5.11    | 549       | 10.92%  |
| 6.8     | 544       | 10.82%  |
| 5.13    | 408       | 8.11%   |
| 5.3     | 312       | 6.21%   |
| 4.15    | 111       | 2.21%   |
| 6.2     | 110       | 2.19%   |
| 5.0     | 89        | 1.77%   |
| 4.18    | 45        | 0.89%   |
| 5.8     | 24        | 0.48%   |
| 6.3     | 8         | 0.16%   |
| 5.14    | 8         | 0.16%   |
| 5.19    | 6         | 0.12%   |
| 6.6     | 4         | 0.08%   |
| 5.10    | 4         | 0.08%   |
| 4.4     | 4         | 0.08%   |
| 6.11    | 3         | 0.06%   |
| 5.18    | 3         | 0.06%   |
| 5.16    | 3         | 0.06%   |
| 6.9     | 2         | 0.04%   |
| 6.12    | 2         | 0.04%   |
| 6.10    | 2         | 0.04%   |
| 6.0     | 2         | 0.04%   |
| 5.9     | 2         | 0.04%   |
| 5.6     | 2         | 0.04%   |
| 6.7     | 1         | 0.02%   |
| 6.1     | 1         | 0.02%   |
| 5.7     | 1         | 0.02%   |
| 4.13    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 4503      | 93.87%  |
| i686   | 294       | 6.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 3746      | 77.4%   |
| XFCE            | 885       | 18.29%  |
| Unknown         | 178       | 3.68%   |
| X-Cinnamon      | 9         | 0.19%   |
| KDE5            | 7         | 0.14%   |
| Unity           | 3         | 0.06%   |
| KDE             | 3         | 0.06%   |
| Budgie          | 3         | 0.06%   |
| i3              | 2         | 0.04%   |
| LXQt            | 1         | 0.02%   |
| LXDE            | 1         | 0.02%   |
| GNOME Flashback | 1         | 0.02%   |
| Cinnamon        | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3515      | 71.95%  |
| Wayland | 1249      | 25.57%  |
| Unknown | 119       | 2.44%   |
| Tty     | 2         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3782      | 77.47%  |
| GDM3    | 547       | 11.2%   |
| GDM     | 300       | 6.15%   |
| LightDM | 244       | 5%      |
| TDM     | 6         | 0.12%   |
| SDDM    | 2         | 0.04%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1681      | 34.83%  |
| de_DE   | 409       | 8.47%   |
| pt_BR   | 338       | 7%      |
| en_GB   | 277       | 5.74%   |
| it_IT   | 198       | 4.1%    |
| fr_FR   | 180       | 3.73%   |
| es_ES   | 165       | 3.42%   |
| en_IN   | 134       | 2.78%   |
| en_CA   | 130       | 2.69%   |
| Unknown | 128       | 2.65%   |
| pl_PL   | 108       | 2.24%   |
| es_MX   | 79        | 1.64%   |
| nl_NL   | 71        | 1.47%   |
| en_AU   | 68        | 1.41%   |
| pt_PT   | 63        | 1.31%   |
| ru_RU   | 55        | 1.14%   |
| tr_TR   | 48        | 0.99%   |
| en_ZA   | 48        | 0.99%   |
| cs_CZ   | 48        | 0.99%   |
| es_AR   | 46        | 0.95%   |
| hu_HU   | 32        | 0.66%   |
| es_CL   | 32        | 0.66%   |
| sv_SE   | 31        | 0.64%   |
| de_AT   | 30        | 0.62%   |
| es_CO   | 25        | 0.52%   |
| en_NZ   | 25        | 0.52%   |
| de_CH   | 22        | 0.46%   |
| C       | 22        | 0.46%   |
| ja_JP   | 18        | 0.37%   |
| el_GR   | 17        | 0.35%   |
| nl_BE   | 16        | 0.33%   |
| da_DK   | 16        | 0.33%   |
| fr_CA   | 15        | 0.31%   |
| hr_HR   | 14        | 0.29%   |
| fr_BE   | 14        | 0.29%   |
| ro_RO   | 13        | 0.27%   |
| es_PE   | 12        | 0.25%   |
| es_EC   | 11        | 0.23%   |
| en_PH   | 11        | 0.23%   |
| en_IE   | 10        | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 2988      | 61.29%  |
| EFI  | 1887      | 38.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4313      | 88.95%  |
| Tmpfs   | 244       | 5.03%   |
| Overlay | 103       | 2.12%   |
| Zfs     | 87        | 1.79%   |
| Btrfs   | 49        | 1.01%   |
| Ext2    | 25        | 0.52%   |
| Unknown | 17        | 0.35%   |
| Ext3    | 6         | 0.12%   |
| Xfs     | 5         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4018      | 82.51%  |
| GPT     | 687       | 14.11%  |
| MBR     | 165       | 3.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4620      | 95.83%  |
| Yes       | 201       | 4.17%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4194      | 86.92%  |
| Yes       | 631       | 13.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 1043      | 21.76%  |
| Lenovo              | 794       | 16.56%  |
| Dell                | 709       | 14.79%  |
| ASUSTek Computer    | 481       | 10.03%  |
| Acer                | 376       | 7.84%   |
| Toshiba             | 223       | 4.65%   |
| Apple               | 178       | 3.71%   |
| Samsung Electronics | 91        | 1.9%    |
| Sony                | 80        | 1.67%   |
| MSI                 | 69        | 1.44%   |
| Unknown             | 53        | 1.11%   |
| HUAWEI              | 51        | 1.06%   |
| Google              | 46        | 0.96%   |
| Positivo            | 38        | 0.79%   |
| Packard Bell        | 38        | 0.79%   |
| Fujitsu             | 37        | 0.77%   |
| Medion              | 32        | 0.67%   |
| Fujitsu Siemens     | 27        | 0.56%   |
| Alienware           | 19        | 0.4%    |
| Notebook            | 18        | 0.38%   |
| Chuwi               | 15        | 0.31%   |
| Panasonic           | 12        | 0.25%   |
| AMI                 | 12        | 0.25%   |
| Gateway             | 11        | 0.23%   |
| Semp Toshiba        | 10        | 0.21%   |
| Multilaser          | 9         | 0.19%   |
| GPU Company         | 9         | 0.19%   |
| eMachines           | 9         | 0.19%   |
| NEC Computers       | 8         | 0.17%   |
| LG Electronics      | 8         | 0.17%   |
| Itautec             | 8         | 0.17%   |
| Jumper              | 7         | 0.15%   |
| Intel               | 7         | 0.15%   |
| Digibras            | 7         | 0.15%   |
| TUXEDO              | 6         | 0.13%   |
| Thomson             | 6         | 0.13%   |
| Teclast             | 6         | 0.13%   |
| Razer               | 6         | 0.13%   |
| Insyde              | 6         | 0.13%   |
| Gigabyte Technology | 6         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Unknown                | 93        | 1.94%   |
| HP Notebook            | 42        | 0.88%   |
| HP Pavilion dv6        | 25        | 0.52%   |
| HP 15                  | 21        | 0.44%   |
| HP Pavilion Notebook   | 20        | 0.42%   |
| HP Pavilion dv7        | 19        | 0.4%    |
| HP Pavilion 15         | 17        | 0.35%   |
| Dell Latitude E6400    | 14        | 0.29%   |
| Dell Inspiron 15-3567  | 14        | 0.29%   |
| Apple MacBookPro8,1    | 14        | 0.29%   |
| Dell Inspiron 1545     | 13        | 0.27%   |
| Apple MacBookPro9,2    | 13        | 0.27%   |
| Apple MacBookPro14,1   | 13        | 0.27%   |
| HP Pavilion g7         | 12        | 0.25%   |
| HP Pavilion g6         | 12        | 0.25%   |
| HP Laptop 15-bw0xx     | 12        | 0.25%   |
| Dell Latitude E6430    | 12        | 0.25%   |
| Dell Latitude D630     | 12        | 0.25%   |
| Toshiba Satellite C660 | 11        | 0.23%   |
| Dell Latitude E6540    | 11        | 0.23%   |
| Apple MacBookPro12,1   | 11        | 0.23%   |
| Apple MacBookPro11,1   | 11        | 0.23%   |
| HP EliteBook 840 G1    | 10        | 0.21%   |
| Dell Latitude E6520    | 10        | 0.21%   |
| HP Pavilion 17         | 9         | 0.19%   |
| HP EliteBook 8460p     | 9         | 0.19%   |
| Dell Latitude E7440    | 9         | 0.19%   |
| Dell Latitude E6420    | 9         | 0.19%   |
| Dell Latitude E6410    | 9         | 0.19%   |
| Dell Latitude E5470    | 9         | 0.19%   |
| Dell Inspiron 1525     | 9         | 0.19%   |
| Apple MacBookPro5,5    | 9         | 0.19%   |
| Apple MacBookAir7,2    | 9         | 0.19%   |
| HP ProBook 4540s       | 8         | 0.17%   |
| Dell Latitude E7450    | 8         | 0.17%   |
| Dell Inspiron 3521     | 8         | 0.17%   |
| HP ProBook 650 G1      | 7         | 0.15%   |
| HP ProBook 640 G1      | 7         | 0.15%   |
| HP Pavilion g4         | 7         | 0.15%   |
| HP Pavilion dv6700     | 7         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 340       | 7.09%   |
| Dell Latitude         | 279       | 5.82%   |
| Acer Aspire           | 265       | 5.53%   |
| HP Pavilion           | 241       | 5.03%   |
| Dell Inspiron         | 241       | 5.03%   |
| Lenovo IdeaPad        | 236       | 4.92%   |
| Toshiba Satellite     | 186       | 3.88%   |
| HP EliteBook          | 135       | 2.82%   |
| HP ProBook            | 126       | 2.63%   |
| HP Laptop             | 114       | 2.38%   |
| Unknown               | 93        | 1.94%   |
| ASUS VivoBook         | 82        | 1.71%   |
| HP Compaq             | 65        | 1.36%   |
| Dell Vostro           | 50        | 1.04%   |
| HP ENVY               | 44        | 0.92%   |
| HP Notebook           | 42        | 0.88%   |
| Dell XPS              | 42        | 0.88%   |
| Dell Precision        | 37        | 0.77%   |
| Packard Bell EasyNote | 36        | 0.75%   |
| ASUS Zenbook          | 32        | 0.67%   |
| ASUS ASUS             | 31        | 0.65%   |
| Fujitsu LIFEBOOK      | 29        | 0.6%    |
| HP 15                 | 28        | 0.58%   |
| ASUS ROG              | 28        | 0.58%   |
| HP ZBook              | 27        | 0.56%   |
| HP Stream             | 27        | 0.56%   |
| Acer Nitro            | 23        | 0.48%   |
| Lenovo Yoga           | 22        | 0.46%   |
| Lenovo Legion         | 21        | 0.44%   |
| Apple MacBookPro8     | 21        | 0.44%   |
| HP Presario           | 20        | 0.42%   |
| HP OMEN               | 19        | 0.4%    |
| HP 255                | 19        | 0.4%    |
| Apple MacBookPro11    | 19        | 0.4%    |
| Apple MacBookPro5     | 18        | 0.38%   |
| Dell System           | 17        | 0.35%   |
| Acer TravelMate       | 17        | 0.35%   |
| Lenovo ThinkBook      | 15        | 0.31%   |
| Dell Studio           | 15        | 0.31%   |
| Apple MacBookPro9     | 15        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 399       | 8.32%   |
| 2011    | 398       | 8.3%    |
| 2012    | 390       | 8.14%   |
| 2021    | 321       | 6.7%    |
| 2010    | 317       | 6.61%   |
| 2014    | 295       | 6.15%   |
| 2017    | 290       | 6.05%   |
| 2008    | 287       | 5.99%   |
| 2018    | 278       | 5.8%    |
| 2019    | 263       | 5.49%   |
| 2020    | 260       | 5.42%   |
| 2015    | 246       | 5.13%   |
| 2016    | 230       | 4.8%    |
| 2009    | 208       | 4.34%   |
| 2007    | 193       | 4.03%   |
| 2022    | 152       | 3.17%   |
| 2023    | 128       | 2.67%   |
| 2006    | 64        | 1.34%   |
| 2005    | 38        | 0.79%   |
| 2024    | 29        | 0.6%    |
| Unknown | 5         | 0.1%    |
| 2003    | 2         | 0.04%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4794      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4373      | 90.59%  |
| Enabled  | 454       | 9.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4739      | 98.85%  |
| Yes  | 55        | 1.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1495      | 30.87%  |
| 3.01-4.0    | 1308      | 27.01%  |
| 8.01-16.0   | 638       | 13.17%  |
| 16.01-24.0  | 570       | 11.77%  |
| 1.01-2.0    | 390       | 8.05%   |
| 32.01-64.0  | 170       | 3.51%   |
| 2.01-3.0    | 134       | 2.77%   |
| 0.51-1.0    | 76        | 1.57%   |
| 24.01-32.0  | 33        | 0.68%   |
| 64.01-256.0 | 29        | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1987      | 38.26%  |
| 2.01-3.0   | 1595      | 30.71%  |
| 3.01-4.0   | 637       | 12.27%  |
| 4.01-8.0   | 541       | 10.42%  |
| 0.51-1.0   | 328       | 6.32%   |
| 8.01-16.0  | 70        | 1.35%   |
| 0.01-0.5   | 26        | 0.5%    |
| 16.01-24.0 | 5         | 0.1%    |
| 24.01-32.0 | 3         | 0.06%   |
| 32.01-64.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3721      | 76.36%  |
| 2      | 1016      | 20.85%  |
| 3      | 100       | 2.05%   |
| 0      | 16        | 0.33%   |
| 4      | 14        | 0.29%   |
| 5      | 4         | 0.08%   |
| 8      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2687      | 55.8%   |
| Yes       | 2128      | 44.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3883      | 80.81%  |
| No        | 922       | 19.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4650      | 96.88%  |
| No        | 150       | 3.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3360      | 69.26%  |
| No        | 1491      | 30.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 912       | 18.93%  |
| Germany      | 461       | 9.57%   |
| Brazil       | 387       | 8.03%   |
| UK           | 258       | 5.36%   |
| Italy        | 213       | 4.42%   |
| France       | 175       | 3.63%   |
| Spain        | 168       | 3.49%   |
| Canada       | 163       | 3.38%   |
| India        | 141       | 2.93%   |
| Netherlands  | 122       | 2.53%   |
| Mexico       | 115       | 2.39%   |
| Poland       | 108       | 2.24%   |
| Portugal     | 74        | 1.54%   |
| Australia    | 72        | 1.49%   |
| Turkey       | 65        | 1.35%   |
| Sweden       | 58        | 1.2%    |
| Argentina    | 58        | 1.2%    |
| Austria      | 57        | 1.18%   |
| Belgium      | 56        | 1.16%   |
| South Africa | 55        | 1.14%   |
| Russia       | 55        | 1.14%   |
| Czechia      | 55        | 1.14%   |
| Switzerland  | 53        | 1.1%    |
| Romania      | 49        | 1.02%   |
| Indonesia    | 45        | 0.93%   |
| Greece       | 39        | 0.81%   |
| Hungary      | 35        | 0.73%   |
| Chile        | 35        | 0.73%   |
| Colombia     | 34        | 0.71%   |
| Egypt        | 33        | 0.69%   |
| New Zealand  | 29        | 0.6%    |
| Japan        | 29        | 0.6%    |
| Norway       | 28        | 0.58%   |
| Denmark      | 22        | 0.46%   |
| Finland      | 21        | 0.44%   |
| Bulgaria     | 21        | 0.44%   |
| Serbia       | 20        | 0.42%   |
| Philippines  | 18        | 0.37%   |
| Ireland      | 18        | 0.37%   |
| Kenya        | 15        | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 45        | 0.89%   |
| Berlin         | 33        | 0.65%   |
| Vienna         | 32        | 0.63%   |
| Madrid         | 29        | 0.57%   |
| Rio de Janeiro | 28        | 0.55%   |
| Milan          | 27        | 0.54%   |
| Sydney         | 26        | 0.52%   |
| Mexico City    | 26        | 0.52%   |
| Istanbul       | 25        | 0.5%    |
| Rome           | 24        | 0.48%   |
| Johannesburg   | 23        | 0.46%   |
| Munich         | 22        | 0.44%   |
| Hamburg        | 22        | 0.44%   |
| Amsterdam      | 21        | 0.42%   |
| New York       | 20        | 0.4%    |
| Cairo          | 19        | 0.38%   |
| Montreal       | 18        | 0.36%   |
| Prague         | 17        | 0.34%   |
| Paris          | 17        | 0.34%   |
| Budapest       | 17        | 0.34%   |
| Warsaw         | 16        | 0.32%   |
| Melbourne      | 16        | 0.32%   |
| Bogotá        | 16        | 0.32%   |
| Athens         | 16        | 0.32%   |
| Santiago       | 15        | 0.3%    |
| Moscow         | 15        | 0.3%    |
| London         | 15        | 0.3%    |
| Jakarta        | 15        | 0.3%    |
| Toronto        | 14        | 0.28%   |
| Stockholm      | 14        | 0.28%   |
| Seattle        | 14        | 0.28%   |
| Delhi          | 14        | 0.28%   |
| Bucharest      | 14        | 0.28%   |
| Valencia       | 13        | 0.26%   |
| Stuttgart      | 13        | 0.26%   |
| Nairobi        | 13        | 0.26%   |
| Dallas         | 13        | 0.26%   |
| Buenos Aires   | 13        | 0.26%   |
| Bengaluru      | 13        | 0.26%   |
| Barcelona      | 13        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 721       | 975    | 12.68%  |
| Seagate                     | 638       | 768    | 11.22%  |
| WDC                         | 612       | 757    | 10.76%  |
| Toshiba                     | 498       | 574    | 8.76%   |
| Unknown                     | 453       | 598    | 7.96%   |
| SanDisk                     | 350       | 421    | 6.15%   |
| Kingston                    | 272       | 326    | 4.78%   |
| Hitachi                     | 219       | 256    | 3.85%   |
| Crucial                     | 178       | 214    | 3.13%   |
| HGST                        | 159       | 192    | 2.8%    |
| SK hynix                    | 146       | 170    | 2.57%   |
| Intel                       | 136       | 160    | 2.39%   |
| Micron Technology           | 128       | 153    | 2.25%   |
| Apple                       | 85        | 106    | 1.49%   |
| China                       | 81        | 99     | 1.42%   |
| A-DATA Technology           | 76        | 86     | 1.34%   |
| Fujitsu                     | 54        | 57     | 0.95%   |
| Intenso                     | 47        | 54     | 0.83%   |
| KIOXIA                      | 46        | 54     | 0.81%   |
| Unknown                     | 38        | 42     | 0.67%   |
| PNY                         | 32        | 37     | 0.56%   |
| SPCC                        | 31        | 40     | 0.55%   |
| Phison                      | 25        | 33     | 0.44%   |
| LITEON                      | 25        | 29     | 0.44%   |
| LITEONIT                    | 24        | 30     | 0.42%   |
| Kingston Technology Company | 24        | 27     | 0.42%   |
| Netac                       | 23        | 24     | 0.4%    |
| Patriot                     | 21        | 25     | 0.37%   |
| Silicon Motion              | 20        | 23     | 0.35%   |
| JMicron Technology          | 20        | 21     | 0.35%   |
| Transcend                   | 19        | 26     | 0.33%   |
| Phison Electronics          | 19        | 24     | 0.33%   |
| MAXIO Technology (Hangzhou) | 19        | 20     | 0.33%   |
| Micron/Crucial Technology   | 17        | 19     | 0.3%    |
| GOODRAM                     | 17        | 21     | 0.3%    |
| ADATA Technology            | 17        | 17     | 0.3%    |
| Fanxiang                    | 16        | 20     | 0.28%   |
| OCZ                         | 15        | 17     | 0.26%   |
| Team                        | 14        | 15     | 0.25%   |
| Lexar                       | 13        | 14     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                               | 141       | 2.4%    |
| Unknown MMC Card  64GB                               | 133       | 2.27%   |
| Toshiba MQ01ABF050 500GB                             | 71        | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB                       | 69        | 1.18%   |
| Kingston SA400S37240G 240GB SSD                      | 62        | 1.06%   |
| Unknown MMC Card  128GB                              | 60        | 1.02%   |
| Toshiba MQ01ABD100 1TB                               | 58        | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 58        | 0.99%   |
| Seagate ST500LT012-1DG142 500GB                      | 52        | 0.89%   |
| Kingston SA400S37480G 480GB SSD                      | 51        | 0.87%   |
| Toshiba MQ04ABF100 1TB                               | 44        | 0.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 41        | 0.7%    |
| Seagate ST9500325AS 500GB                            | 40        | 0.68%   |
| Unknown                                              | 38        | 0.65%   |
| Unknown MMC Card  16GB                               | 33        | 0.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 30        | 0.51%   |
| Samsung SSD 850 EVO 250GB                            | 30        | 0.51%   |
| HGST HTS721010A9E630 1TB                             | 30        | 0.51%   |
| Crucial CT240BX500SSD1 240GB                         | 30        | 0.51%   |
| Kingston SA400S37120G 120GB SSD                      | 29        | 0.49%   |
| HGST HTS725050A7E630 500GB                           | 28        | 0.48%   |
| Samsung SSD 860 EVO 500GB                            | 27        | 0.46%   |
| HGST HTS545050A7E680 500GB                           | 27        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                         | 27        | 0.46%   |
| Samsung SSD 850 EVO 500GB                            | 26        | 0.44%   |
| HGST HTS541010A9E680 1TB                             | 26        | 0.44%   |
| Samsung NVMe SSD Drive 512GB                         | 24        | 0.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 22        | 0.37%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 21        | 0.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 21        | 0.36%   |
| Hitachi HTS545032B9A300 320GB                        | 21        | 0.36%   |
| Seagate Expansion 1TB                                | 20        | 0.34%   |
| SanDisk NVMe SSD Drive 256GB                         | 20        | 0.34%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 19        | 0.32%   |
| SanDisk NVMe SSD Drive 512GB                         | 19        | 0.32%   |
| Samsung NVMe SSD Drive 256GB                         | 19        | 0.32%   |
| Seagate ST500LM021-1KJ152 500GB                      | 18        | 0.31%   |
| Samsung SSD 860 EVO 250GB                            | 18        | 0.31%   |
| Unknown SD/MMC/MS PRO 128GB                          | 17        | 0.29%   |
| Toshiba MQ01ABD050 500GB                             | 17        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 628       | 752    | 29.86%  |
| WDC                 | 490       | 593    | 23.3%   |
| Toshiba             | 416       | 470    | 19.78%  |
| Hitachi             | 219       | 256    | 10.41%  |
| HGST                | 159       | 192    | 7.56%   |
| Samsung Electronics | 59        | 64     | 2.81%   |
| Fujitsu             | 54        | 57     | 2.57%   |
| Unknown             | 17        | 24     | 0.81%   |
| JMicron Technology  | 11        | 12     | 0.52%   |
| SABRENT             | 10        | 11     | 0.48%   |
| Apple               | 10        | 10     | 0.48%   |
| ASMT                | 7         | 7      | 0.33%   |
| TO Exter            | 4         | 5      | 0.19%   |
| IBM/Hitachi         | 4         | 5      | 0.19%   |
| KESU                | 2         | 2      | 0.1%    |
| Intenso             | 2         | 2      | 0.1%    |
| External            | 2         | 2      | 0.1%    |
| EAGET               | 2         | 2      | 0.1%    |
| ASMedia             | 2         | 2      | 0.1%    |
| XrayDisk            | 1         | 1      | 0.05%   |
| Min Yi U            | 1         | 1      | 0.05%   |
| LaCie               | 1         | 2      | 0.05%   |
| FC-1307             | 1         | 1      | 0.05%   |
| Apricorn            | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 375       | 509    | 19.64%  |
| Kingston            | 237       | 282    | 12.41%  |
| SanDisk             | 180       | 220    | 9.43%   |
| Crucial             | 171       | 205    | 8.96%   |
| WDC                 | 91        | 121    | 4.77%   |
| China               | 80        | 98     | 4.19%   |
| A-DATA Technology   | 64        | 74     | 3.35%   |
| Intel               | 57        | 63     | 2.99%   |
| Apple               | 55        | 59     | 2.88%   |
| Micron Technology   | 46        | 54     | 2.41%   |
| Toshiba             | 42        | 47     | 2.2%    |
| SK hynix            | 37        | 42     | 1.94%   |
| Intenso             | 34        | 37     | 1.78%   |
| PNY                 | 32        | 37     | 1.68%   |
| SPCC                | 30        | 39     | 1.57%   |
| LITEON              | 25        | 29     | 1.31%   |
| LITEONIT            | 24        | 30     | 1.26%   |
| Patriot             | 21        | 25     | 1.1%    |
| Netac               | 21        | 22     | 1.1%    |
| Transcend           | 19        | 26     | 1%      |
| GOODRAM             | 16        | 20     | 0.84%   |
| OCZ                 | 15        | 17     | 0.79%   |
| Team                | 14        | 15     | 0.73%   |
| Unknown             | 13        | 15     | 0.68%   |
| KingSpec            | 12        | 12     | 0.63%   |
| Lexar               | 11        | 11     | 0.58%   |
| Teclast             | 9         | 11     | 0.47%   |
| Hewlett-Packard     | 9         | 11     | 0.47%   |
| Phison              | 8         | 14     | 0.42%   |
| Apacer              | 8         | 8      | 0.42%   |
| Verbatim            | 7         | 7      | 0.37%   |
| Gigabyte Technology | 7         | 8      | 0.37%   |
| Fanxiang            | 7         | 8      | 0.37%   |
| Plextor             | 6         | 6      | 0.31%   |
| SSSTC               | 4         | 5      | 0.21%   |
| BHT                 | 4         | 5      | 0.21%   |
| XrayDisk            | 3         | 3      | 0.16%   |
| Wibtek              | 3         | 4      | 0.16%   |
| S3+                 | 3         | 5      | 0.16%   |
| Mushkin             | 3         | 3      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2045      | 2474   | 37.34%  |
| SSD     | 1819      | 2319   | 33.22%  |
| NVMe    | 1048      | 1397   | 19.14%  |
| MMC     | 447       | 590    | 8.16%   |
| Unknown | 117       | 140    | 2.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3608      | 4697   | 68.35%  |
| NVMe | 1047      | 1387   | 19.83%  |
| MMC  | 447       | 590    | 8.47%   |
| SAS  | 177       | 246    | 3.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2800      | 3493   | 73.16%  |
| 0.51-1.0   | 915       | 1157   | 23.91%  |
| 1.01-2.0   | 91        | 113    | 2.38%   |
| 3.01-4.0   | 11        | 20     | 0.29%   |
| 4.01-10.0  | 8         | 8      | 0.21%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |
| 10.01-20.0 | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1753      | 35.51%  |
| 251-500        | 1295      | 26.24%  |
| 501-1000       | 651       | 13.19%  |
| 51-100         | 494       | 10.01%  |
| 21-50          | 277       | 5.61%   |
| 1001-2000      | 165       | 3.34%   |
| 1-20           | 142       | 2.88%   |
| Unknown        | 71        | 1.44%   |
| More than 3000 | 50        | 1.01%   |
| 2001-3000      | 38        | 0.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2231      | 43.22%  |
| 21-50          | 1463      | 28.34%  |
| 51-100         | 565       | 10.95%  |
| 101-250        | 476       | 9.22%   |
| 251-500        | 213       | 4.13%   |
| 501-1000       | 95        | 1.84%   |
| Unknown        | 71        | 1.38%   |
| 1001-2000      | 23        | 0.45%   |
| More than 3000 | 17        | 0.33%   |
| 2001-3000      | 8         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                | 4         | 4      | 4.3%    |
| Toshiba MQ01ABD100 1TB                   | 3         | 3      | 3.23%   |
| Seagate ST500LM000-1EJ162 500GB          | 3         | 3      | 3.23%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 2.15%   |
| Toshiba MQ01ABF050 500GB                 | 2         | 2      | 2.15%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 2.15%   |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 2.15%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 2.15%   |
| Seagate ST1000LM048-2E7172 1TB           | 2         | 2      | 2.15%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 2.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 2      | 2.15%   |
| HGST HTS545050A7E680 500GB               | 2         | 2      | 2.15%   |
| HGST HTS545050A7E380 500GB               | 2         | 3      | 2.15%   |
| A-DATA Technology IM2P33F3A NVMe 256GB   | 2         | 2      | 2.15%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 1.08%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 1.08%   |
| WDC WD5000BPVT-75HXZT1 500GB             | 1         | 1      | 1.08%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 1.08%   |
| WDC WD3200BPVT-55ZEST0 320GB             | 1         | 1      | 1.08%   |
| WDC WD2500BEKT-75PVMT1 250GB             | 1         | 1      | 1.08%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 1.08%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.08%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 1.08%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 1.08%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 1.08%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 1.08%   |
| Toshiba MK6465GSX 640GB                  | 1         | 1      | 1.08%   |
| Toshiba MK5061GSY 500GB                  | 1         | 1      | 1.08%   |
| Toshiba MK2565GSX 250GB                  | 1         | 1      | 1.08%   |
| Toshiba MK2046GSX 200GB                  | 1         | 1      | 1.08%   |
| Teclast 128GB NS550-2242 SSD             | 1         | 1      | 1.08%   |
| Seagate ST9500420AS 500GB                | 1         | 1      | 1.08%   |
| Seagate ST9320325AS 320GB                | 1         | 1      | 1.08%   |
| Seagate ST9320310AS 320GB                | 1         | 1      | 1.08%   |
| Seagate ST9250315AS 250GB                | 1         | 1      | 1.08%   |
| Seagate ST9200420ASG 200GB               | 1         | 1      | 1.08%   |
| Seagate ST9160411ASG 160GB               | 1         | 1      | 1.08%   |
| Seagate ST9160314AS 160GB                | 1         | 1      | 1.08%   |
| Seagate ST9120822AS 120GB                | 1         | 1      | 1.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 29     | 31.18%  |
| Toshiba             | 14        | 14     | 15.05%  |
| WDC                 | 10        | 10     | 10.75%  |
| Hitachi             | 8         | 8      | 8.6%    |
| HGST                | 8         | 9      | 8.6%    |
| Samsung Electronics | 5         | 5      | 5.38%   |
| Kingston            | 3         | 3      | 3.23%   |
| SK hynix            | 2         | 2      | 2.15%   |
| Micron Technology   | 2         | 2      | 2.15%   |
| A-DATA Technology   | 2         | 2      | 2.15%   |
| Teclast             | 1         | 1      | 1.08%   |
| SanDisk             | 1         | 1      | 1.08%   |
| POLION              | 1         | 1      | 1.08%   |
| LITEONIT            | 1         | 1      | 1.08%   |
| KingFast            | 1         | 1      | 1.08%   |
| Intel               | 1         | 1      | 1.08%   |
| Hewlett-Packard     | 1         | 1      | 1.08%   |
| Drevo               | 1         | 1      | 1.08%   |
| BIWIN               | 1         | 1      | 1.08%   |
| Unknown             | 1         | 1      | 1.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 29     | 42.03%  |
| Toshiba             | 12        | 12     | 17.39%  |
| WDC                 | 10        | 10     | 14.49%  |
| Hitachi             | 8         | 8      | 11.59%  |
| HGST                | 8         | 9      | 11.59%  |
| Samsung Electronics | 2         | 2      | 2.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 69        | 70     | 74.19%  |
| SSD  | 20        | 20     | 21.51%  |
| NVMe | 4         | 4      | 4.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4325      | 6236   | 88.45%  |
| Works    | 471       | 587    | 9.63%   |
| Malfunc  | 91        | 94     | 1.86%   |
| Failed   | 2         | 2      | 0.04%   |
| Fixed    | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3439      | 65.64%  |
| AMD                              | 571       | 10.9%   |
| Samsung Electronics              | 339       | 6.47%   |
| SanDisk                          | 189       | 3.61%   |
| SK hynix                         | 106       | 2.02%   |
| Micron Technology                | 83        | 1.58%   |
| Nvidia                           | 73        | 1.39%   |
| Kingston Technology Company      | 58        | 1.11%   |
| KIOXIA                           | 47        | 0.9%    |
| Toshiba America Info Systems     | 42        | 0.8%    |
| Silicon Integrated Systems [SiS] | 38        | 0.73%   |
| Phison Electronics               | 38        | 0.73%   |
| ADATA Technology                 | 29        | 0.55%   |
| Silicon Motion                   | 26        | 0.5%    |
| Micron/Crucial Technology        | 24        | 0.46%   |
| MAXIO Technology (Hangzhou)      | 23        | 0.44%   |
| Apple                            | 19        | 0.36%   |
| VIA Technologies                 | 14        | 0.27%   |
| Marvell Technology Group         | 10        | 0.19%   |
| Solid State Storage Technology   | 9         | 0.17%   |
| Realtek Semiconductor            | 9         | 0.17%   |
| Shenzhen Longsys Electronics     | 7         | 0.13%   |
| Lite-On Technology               | 7         | 0.13%   |
| JMicron Technology               | 6         | 0.11%   |
| ASMedia Technology               | 6         | 0.11%   |
| Union Memory (Shenzhen)          | 5         | 0.1%    |
| Solidigm                         | 5         | 0.1%    |
| Yangtze Memory Technologies      | 4         | 0.08%   |
| Silicon Image                    | 3         | 0.06%   |
| Lenovo                           | 3         | 0.06%   |
| Seagate Technology               | 2         | 0.04%   |
| Netac Technology                 | 2         | 0.04%   |
| INNOGRIT                         | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 443       | 7.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 387       | 6.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 340       | 5.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 296       | 5.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 276       | 4.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 233       | 4.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 191       | 3.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 158       | 2.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 148       | 2.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 129       | 2.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 129       | 2.23%   |
| Intel Volume Management Device NVMe RAID Controller                              | 119       | 2.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 115       | 1.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 114       | 1.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 104       | 1.8%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 91        | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 79        | 1.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 75        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 71        | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 67        | 1.16%   |
| Intel Tiger Lake-LP SATA Controller                                              | 66        | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 61        | 1.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 60        | 1.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 58        | 1%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 57        | 0.99%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 43        | 0.74%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 43        | 0.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 40        | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                            | 40        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 40        | 0.69%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 37        | 0.64%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 36        | 0.62%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 36        | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 36        | 0.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 36        | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 35        | 0.61%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 33        | 0.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 32        | 0.55%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 31        | 0.54%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 31        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3433      | 62.52%  |
| NVMe | 1047      | 19.07%  |
| IDE  | 583       | 10.62%  |
| RAID | 428       | 7.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 4035      | 84.17%  |
| AMD          | 757       | 15.79%  |
| CentaurHauls | 2         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 59        | 1.23%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 59        | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 58        | 1.21%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 56        | 1.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 47        | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 47        | 0.98%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 46        | 0.96%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 46        | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 45        | 0.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 45        | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 42        | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 39        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 39        | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 38        | 0.79%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 35        | 0.73%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 34        | 0.71%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 34        | 0.71%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 33        | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 32        | 0.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 32        | 0.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 31        | 0.65%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 31        | 0.65%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 30        | 0.63%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 30        | 0.63%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 30        | 0.63%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 30        | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 29        | 0.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 29        | 0.6%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 28        | 0.58%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 27        | 0.56%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 27        | 0.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 26        | 0.54%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 26        | 0.54%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 26        | 0.54%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 26        | 0.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 25        | 0.52%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 25        | 0.52%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 25        | 0.52%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 24        | 0.5%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 24        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1071      | 22.32%  |
| Intel Core i7           | 730       | 15.21%  |
| Intel Core i3           | 468       | 9.75%   |
| Intel Celeron           | 419       | 8.73%   |
| Intel Core 2 Duo        | 355       | 7.4%    |
| Other                   | 344       | 7.17%   |
| Intel Atom              | 191       | 3.98%   |
| AMD Ryzen 5             | 140       | 2.92%   |
| Intel Pentium           | 136       | 2.83%   |
| AMD Ryzen 7             | 92        | 1.92%   |
| AMD A6                  | 71        | 1.48%   |
| Intel Pentium Dual-Core | 68        | 1.42%   |
| Intel Genuine           | 47        | 0.98%   |
| AMD A4                  | 47        | 0.98%   |
| Intel Pentium Dual      | 43        | 0.9%    |
| AMD Ryzen 3             | 41        | 0.85%   |
| AMD A8                  | 39        | 0.81%   |
| Intel Core 2            | 36        | 0.75%   |
| AMD E1                  | 36        | 0.75%   |
| AMD A10                 | 33        | 0.69%   |
| AMD E                   | 30        | 0.63%   |
| Intel Celeron M         | 28        | 0.58%   |
| Intel Pentium M         | 27        | 0.56%   |
| AMD Turion 64 X2 Mobile | 21        | 0.44%   |
| AMD Ryzen 9             | 20        | 0.42%   |
| Intel Pentium Silver    | 18        | 0.38%   |
| Intel Core M            | 15        | 0.31%   |
| AMD E2                  | 14        | 0.29%   |
| AMD Athlon II           | 14        | 0.29%   |
| Intel Celeron Dual-Core | 12        | 0.25%   |
| AMD Athlon              | 11        | 0.23%   |
| AMD Athlon 64 X2        | 10        | 0.21%   |
| Intel Core i9           | 9         | 0.19%   |
| AMD Turion 64 Mobile    | 9         | 0.19%   |
| AMD Ryzen 7 PRO         | 9         | 0.19%   |
| Intel Core m5           | 8         | 0.17%   |
| Intel Core Duo          | 8         | 0.17%   |
| AMD Mobile Sempron      | 8         | 0.17%   |
| AMD A12                 | 8         | 0.17%   |
| Intel Core              | 7         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2930      | 61.07%  |
| 4      | 1193      | 24.86%  |
| 1      | 216       | 4.5%    |
| 6      | 180       | 3.75%   |
| 8      | 152       | 3.17%   |
| 10     | 44        | 0.92%   |
| 14     | 36        | 0.75%   |
| 12     | 28        | 0.58%   |
| 16     | 9         | 0.19%   |
| 24     | 8         | 0.17%   |
| 3      | 2         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4794      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3026      | 63.08%  |
| 1      | 1771      | 36.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4666      | 97.31%  |
| 32-bit         | 127       | 2.65%   |
| Unknown        | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1699      | 34.74%  |
| 0x206a7    | 289       | 5.91%   |
| 0x306a9    | 252       | 5.15%   |
| 0x1067a    | 182       | 3.72%   |
| 0x40651    | 152       | 3.11%   |
| 0x406e3    | 121       | 2.47%   |
| 0x20655    | 117       | 2.39%   |
| 0x306d4    | 116       | 2.37%   |
| 0x6fd      | 101       | 2.07%   |
| 0x30678    | 97        | 1.98%   |
| 0x306c3    | 92        | 1.88%   |
| 0x806e9    | 89        | 1.82%   |
| 0x806ea    | 80        | 1.64%   |
| 0x806c1    | 78        | 1.6%    |
| 0x406c4    | 70        | 1.43%   |
| 0x806ec    | 68        | 1.39%   |
| 0x10676    | 59        | 1.21%   |
| 0x706a8    | 51        | 1.04%   |
| 0x906ea    | 49        | 1%      |
| 0x506c9    | 46        | 0.94%   |
| 0x406c3    | 46        | 0.94%   |
| 0x20652    | 43        | 0.88%   |
| 0x906e9    | 42        | 0.86%   |
| 0x706e5    | 42        | 0.86%   |
| 0x08108109 | 38        | 0.78%   |
| 0x106ca    | 37        | 0.76%   |
| 0x06006705 | 37        | 0.76%   |
| 0x6e8      | 32        | 0.65%   |
| 0x6d8      | 32        | 0.65%   |
| 0x6f6      | 29        | 0.59%   |
| 0x07030105 | 29        | 0.59%   |
| 0x05000119 | 28        | 0.57%   |
| 0x08108102 | 26        | 0.53%   |
| 0x0700010f | 26        | 0.53%   |
| 0x106c2    | 25        | 0.51%   |
| 0x706a1    | 24        | 0.49%   |
| 0x06001119 | 24        | 0.49%   |
| 0x6fb      | 23        | 0.47%   |
| 0x0a50000c | 23        | 0.47%   |
| 0xa0652    | 22        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 545       | 11.36%  |
| SandyBridge       | 410       | 8.55%   |
| Haswell           | 388       | 8.09%   |
| IvyBridge         | 370       | 7.71%   |
| Penryn            | 340       | 7.09%   |
| Silvermont        | 274       | 5.71%   |
| Core              | 235       | 4.9%    |
| Westmere          | 232       | 4.84%   |
| Skylake           | 222       | 4.63%   |
| Unknown           | 207       | 4.31%   |
| Broadwell         | 167       | 3.48%   |
| TigerLake         | 149       | 3.11%   |
| Goldmont plus     | 140       | 2.92%   |
| Zen+              | 89        | 1.85%   |
| P6                | 89        | 1.85%   |
| Excavator         | 89        | 1.85%   |
| Bonnell           | 77        | 1.6%    |
| IceLake           | 72        | 1.5%    |
| Goldmont          | 72        | 1.5%    |
| Zen 3             | 69        | 1.44%   |
| Puma              | 64        | 1.33%   |
| Zen 2             | 57        | 1.19%   |
| Bobcat            | 56        | 1.17%   |
| K8 Hammer         | 55        | 1.15%   |
| Alderlake Hybrid  | 51        | 1.06%   |
| CometLake         | 44        | 0.92%   |
| Jaguar            | 41        | 0.85%   |
| Piledriver        | 38        | 0.79%   |
| K10               | 34        | 0.71%   |
| Zen               | 27        | 0.56%   |
| K10 Llano         | 24        | 0.5%    |
| K8 & K10 hybrid   | 22        | 0.46%   |
| Nehalem           | 19        | 0.4%    |
| Tremont           | 13        | 0.27%   |
| Steamroller       | 9         | 0.19%   |
| NetBurst          | 4         | 0.08%   |
| Meteorlake Hybrid | 2         | 0.04%   |
| Gracemont         | 2         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3553      | 62.28%  |
| AMD                              | 1067      | 18.7%   |
| Nvidia                           | 1039      | 18.21%  |
| Silicon Integrated Systems [SiS] | 33        | 0.58%   |
| VIA Technologies                 | 13        | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 367       | 6.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 353       | 5.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 226       | 3.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 198       | 3.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 167       | 2.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 165       | 2.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 140       | 2.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 134       | 2.24%   |
| Intel HD Graphics 620                                                                    | 133       | 2.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 133       | 2.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 127       | 2.12%   |
| Intel HD Graphics 5500                                                                   | 122       | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 118       | 1.97%   |
| Intel UHD Graphics 620                                                                   | 114       | 1.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 105       | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 105       | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 95        | 1.59%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 85        | 1.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 70        | 1.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 66        | 1.1%    |
| Intel HD Graphics 500                                                                    | 62        | 1.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 60        | 1%      |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 59        | 0.99%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 56        | 0.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 55        | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 51        | 0.85%   |
| Intel HD Graphics 630                                                                    | 51        | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 49        | 0.82%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 46        | 0.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 44        | 0.73%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 43        | 0.72%   |
| AMD Lucienne                                                                             | 43        | 0.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 42        | 0.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 42        | 0.7%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 40        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 39        | 0.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 39        | 0.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 38        | 0.63%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 32        | 0.53%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 31        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 2702      | 56.26%  |
| 1 x AMD        | 732       | 15.24%  |
| Intel + Nvidia | 648       | 13.49%  |
| 1 x Nvidia     | 316       | 6.58%   |
| Intel + AMD    | 190       | 3.96%   |
| 2 x AMD        | 79        | 1.64%   |
| AMD + Nvidia   | 67        | 1.39%   |
| 1 x SiS        | 33        | 0.69%   |
| Other          | 13        | 0.27%   |
| 1 x VIA        | 13        | 0.27%   |
| 2 x Nvidia     | 10        | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4159      | 86.25%  |
| Proprietary | 492       | 10.2%   |
| Unknown     | 171       | 3.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3638      | 74.78%  |
| 0.01-0.5   | 564       | 11.59%  |
| 1.01-2.0   | 291       | 5.98%   |
| 0.51-1.0   | 206       | 4.23%   |
| 3.01-4.0   | 101       | 2.08%   |
| 5.01-6.0   | 25        | 0.51%   |
| 7.01-8.0   | 22        | 0.45%   |
| 2.01-3.0   | 14        | 0.29%   |
| 8.01-16.0  | 4         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 969       | 19.55%  |
| LG Display              | 696       | 14.04%  |
| BOE                     | 651       | 13.13%  |
| Samsung Electronics     | 626       | 12.63%  |
| Chimei Innolux          | 620       | 12.51%  |
| Apple                   | 178       | 3.59%   |
| Chi Mei Optoelectronics | 168       | 3.39%   |
| LG Philips              | 91        | 1.84%   |
| Lenovo                  | 82        | 1.65%   |
| Goldstar                | 80        | 1.61%   |
| Sharp                   | 79        | 1.59%   |
| Dell                    | 63        | 1.27%   |
| PANDA                   | 62        | 1.25%   |
| InfoVision              | 56        | 1.13%   |
| Hewlett-Packard         | 36        | 0.73%   |
| Acer                    | 30        | 0.61%   |
| CPT                     | 29        | 0.59%   |
| AOC                     | 22        | 0.44%   |
| HannStar                | 21        | 0.42%   |
| Toshiba                 | 20        | 0.4%    |
| Philips                 | 20        | 0.4%    |
| CSO                     | 20        | 0.4%    |
| BenQ                    | 20        | 0.4%    |
| Sony                    | 19        | 0.38%   |
| Panasonic               | 13        | 0.26%   |
| Vizio                   | 12        | 0.24%   |
| Quanta Display          | 12        | 0.24%   |
| InnoLux Display         | 12        | 0.24%   |
| LGD                     | 11        | 0.22%   |
| Ancor Communications    | 11        | 0.22%   |
| ASUSTek Computer        | 10        | 0.2%    |
| TMX                     | 9         | 0.18%   |
| SLD                     | 9         | 0.18%   |
| Seiko/Epson             | 9         | 0.18%   |
| Unknown                 | 9         | 0.18%   |
| ViewSonic               | 8         | 0.16%   |
| Eizo                    | 8         | 0.16%   |
| KDC                     | 7         | 0.14%   |
| Iiyama                  | 7         | 0.14%   |
| MSI                     | 6         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 54        | 1.08%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 33        | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 33        | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 31        | 0.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 26        | 0.52%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 23        | 0.46%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 23        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 22        | 0.44%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 22        | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 22        | 0.44%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 22        | 0.44%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 21        | 0.42%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 21        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 20        | 0.4%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 20        | 0.4%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 19        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 18        | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 18        | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 16        | 0.32%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 16        | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 16        | 0.32%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 16        | 0.32%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 15        | 0.3%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 15        | 0.3%    |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 15        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 15        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 15        | 0.3%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 15        | 0.3%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 14        | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 14        | 0.28%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 14        | 0.28%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 14        | 0.28%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch              | 13        | 0.26%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 13        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 12        | 0.24%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 12        | 0.24%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 12        | 0.24%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 12        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1880      | 38.99%  |
| 1920x1080 (FHD)    | 1510      | 31.31%  |
| 1280x800 (WXGA)    | 328       | 6.8%    |
| 1600x900 (HD+)     | 293       | 6.08%   |
| 1440x900 (WXGA+)   | 126       | 2.61%   |
| 3840x2160 (4K)     | 105       | 2.18%   |
| 1920x1200 (WUXGA)  | 86        | 1.78%   |
| 2560x1440 (QHD)    | 61        | 1.27%   |
| 2560x1600          | 59        | 1.22%   |
| 1024x600           | 54        | 1.12%   |
| 2880x1800          | 47        | 0.97%   |
| 1680x1050 (WSXGA+) | 47        | 0.97%   |
| 1280x1024 (SXGA)   | 20        | 0.41%   |
| 2560x1080          | 19        | 0.39%   |
| 1360x768           | 17        | 0.35%   |
| 2160x1440          | 14        | 0.29%   |
| 1024x768 (XGA)     | 13        | 0.27%   |
| 3200x1800 (QHD+)   | 12        | 0.25%   |
| Unknown            | 12        | 0.25%   |
| 3840x2400          | 11        | 0.23%   |
| 2256x1504          | 10        | 0.21%   |
| 1920x540           | 10        | 0.21%   |
| 1280x768           | 8         | 0.17%   |
| 3840x1080          | 7         | 0.15%   |
| 3440x1440          | 6         | 0.12%   |
| 3200x2000          | 6         | 0.12%   |
| 2304x1440          | 5         | 0.1%    |
| 1920x1280          | 5         | 0.1%    |
| 1680x945           | 5         | 0.1%    |
| 2880x1620          | 4         | 0.08%   |
| 1400x1050          | 4         | 0.08%   |
| 1920x515           | 3         | 0.06%   |
| 1024x576           | 3         | 0.06%   |
| 5760x1080          | 2         | 0.04%   |
| 504x315            | 2         | 0.04%   |
| 3840x1200          | 2         | 0.04%   |
| 3600x1080          | 2         | 0.04%   |
| 3072x1920          | 2         | 0.04%   |
| 2880x1920          | 2         | 0.04%   |
| 2520x1680          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2125      | 42.92%  |
| 13      | 714       | 14.42%  |
| 14      | 608       | 12.28%  |
| 17      | 398       | 8.04%   |
| 11      | 154       | 3.11%   |
| 12      | 134       | 2.71%   |
| Unknown | 88        | 1.78%   |
| 16      | 83        | 1.68%   |
| 27      | 82        | 1.66%   |
| 24      | 82        | 1.66%   |
| 10      | 69        | 1.39%   |
| 23      | 55        | 1.11%   |
| 21      | 53        | 1.07%   |
| 18      | 53        | 1.07%   |
| 31      | 45        | 0.91%   |
| 34      | 27        | 0.55%   |
| 19      | 19        | 0.38%   |
| 22      | 18        | 0.36%   |
| 20      | 16        | 0.32%   |
| 54      | 14        | 0.28%   |
| 84      | 13        | 0.26%   |
| 72      | 13        | 0.26%   |
| 40      | 13        | 0.26%   |
| 32      | 8         | 0.16%   |
| 52      | 7         | 0.14%   |
| 48      | 6         | 0.12%   |
| 25      | 6         | 0.12%   |
| 8       | 5         | 0.1%    |
| 26      | 4         | 0.08%   |
| 74      | 3         | 0.06%   |
| 58      | 3         | 0.06%   |
| 49      | 3         | 0.06%   |
| 46      | 3         | 0.06%   |
| 29      | 3         | 0.06%   |
| 65      | 2         | 0.04%   |
| 43      | 2         | 0.04%   |
| 42      | 2         | 0.04%   |
| 37      | 2         | 0.04%   |
| 36      | 2         | 0.04%   |
| 7       | 2         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 3116      | 63.2%   |
| 201-300     | 666       | 13.51%  |
| 351-400     | 495       | 10.04%  |
| 501-600     | 213       | 4.32%   |
| 401-500     | 154       | 3.12%   |
| Unknown     | 88        | 1.78%   |
| 601-700     | 57        | 1.16%   |
| 1001-1500   | 45        | 0.91%   |
| 701-800     | 38        | 0.77%   |
| 1501-2000   | 29        | 0.59%   |
| 801-900     | 17        | 0.34%   |
| 101-200     | 7         | 0.14%   |
| 901-1000    | 5         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3703      | 80.87%  |
| 16/10   | 688       | 15.03%  |
| Unknown | 60        | 1.31%   |
| 3/2     | 43        | 0.94%   |
| 21/9    | 27        | 0.59%   |
| 4/3     | 22        | 0.48%   |
| 5/4     | 18        | 0.39%   |
| 32/9    | 6         | 0.13%   |
| 3.73    | 3         | 0.07%   |
| 0.62    | 2         | 0.04%   |
| 6/5     | 1         | 0.02%   |
| 3.40    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.31    | 1         | 0.02%   |
| 0.25    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2123      | 42.93%  |
| 81-90          | 1112      | 22.49%  |
| 121-130        | 309       | 6.25%   |
| 71-80          | 199       | 4.02%   |
| 201-250        | 170       | 3.44%   |
| 51-60          | 156       | 3.15%   |
| 61-70          | 131       | 2.65%   |
| Unknown        | 88        | 1.78%   |
| 301-350        | 85        | 1.72%   |
| 131-140        | 83        | 1.68%   |
| 351-500        | 82        | 1.66%   |
| 41-50          | 68        | 1.38%   |
| More than 1000 | 66        | 1.33%   |
| 141-150        | 63        | 1.27%   |
| 111-120        | 63        | 1.27%   |
| 151-200        | 55        | 1.11%   |
| 501-1000       | 34        | 0.69%   |
| 251-300        | 26        | 0.53%   |
| 91-100         | 25        | 0.51%   |
| 1-40           | 7         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1995      | 40.91%  |
| 121-160       | 1594      | 32.68%  |
| 51-100        | 785       | 16.1%   |
| 161-240       | 267       | 5.47%   |
| Unknown       | 89        | 1.82%   |
| More than 240 | 85        | 1.74%   |
| 1-50          | 62        | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4134      | 84.73%  |
| 2     | 524       | 10.74%  |
| 0     | 179       | 3.67%   |
| 3     | 37        | 0.76%   |
| 4     | 4         | 0.08%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2467      | 32.06%  |
| Intel                             | 2140      | 27.81%  |
| Qualcomm Atheros                  | 1183      | 15.37%  |
| Broadcom                          | 708       | 9.2%    |
| Broadcom Limited                  | 216       | 2.81%   |
| Marvell Technology Group          | 127       | 1.65%   |
| Ralink                            | 91        | 1.18%   |
| MediaTek                          | 85        | 1.1%    |
| Nvidia                            | 60        | 0.78%   |
| TP-Link                           | 56        | 0.73%   |
| Samsung Electronics               | 47        | 0.61%   |
| Ralink Technology                 | 45        | 0.58%   |
| ASIX Electronics                  | 41        | 0.53%   |
| JMicron Technology                | 36        | 0.47%   |
| Dell                              | 36        | 0.47%   |
| Silicon Integrated Systems [SiS]  | 35        | 0.45%   |
| Sierra Wireless                   | 32        | 0.42%   |
| Hewlett-Packard                   | 24        | 0.31%   |
| Xiaomi                            | 21        | 0.27%   |
| DisplayLink                       | 21        | 0.27%   |
| Ericsson Business Mobile Networks | 16        | 0.21%   |
| Huawei Technologies               | 14        | 0.18%   |
| Qualcomm Atheros Communications   | 13        | 0.17%   |
| Qualcomm                          | 13        | 0.17%   |
| VIA Technologies                  | 12        | 0.16%   |
| OPPO Electronics                  | 12        | 0.16%   |
| NetGear                           | 11        | 0.14%   |
| Motorola PCS                      | 10        | 0.13%   |
| ASUSTek Computer                  | 10        | 0.13%   |
| Edimax Technology                 | 9         | 0.12%   |
| D-Link                            | 9         | 0.12%   |
| AMD                               | 8         | 0.1%    |
| Attansic Technology               | 7         | 0.09%   |
| Lenovo                            | 6         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.06%   |
| Google                            | 5         | 0.06%   |
| D-Link System                     | 5         | 0.06%   |
| Belkin Components                 | 5         | 0.06%   |
| T & A Mobile Phones               | 4         | 0.05%   |
| Linksys                           | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 1267      | 13.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 615       | 6.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 213       | 2.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 199       | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 187       | 2.03%   |
| Intel Wireless 7260                                                     | 178       | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 171       | 1.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 161       | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 136       | 1.48%   |
| Intel Wireless 7265                                                     | 133       | 1.45%   |
| Intel Wireless 8265 / 8275                                              | 127       | 1.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 116       | 1.26%   |
| Intel Wi-Fi 6 AX201                                                     | 112       | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 112       | 1.22%   |
| Intel Wireless 8260                                                     | 98        | 1.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 95        | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                           | 94        | 1.02%   |
| Intel Wireless 3165                                                     | 91        | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 88        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 84        | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 82        | 0.89%   |
| Intel Wi-Fi 6 AX200                                                     | 79        | 0.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 78        | 0.85%   |
| Intel WiFi Link 5100                                                    | 75        | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 71        | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 0.69%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 62        | 0.67%   |
| Intel Ethernet Connection I218-LM                                       | 56        | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 55        | 0.6%    |
| Intel Ethernet Connection I217-LM                                       | 55        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 54        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                          | 53        | 0.58%   |
| Intel Wireless 3160                                                     | 52        | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 52        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                                | 52        | 0.57%   |
| Intel Ethernet Connection I219-LM                                       | 51        | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 51        | 0.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 50        | 0.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 49        | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                   | 49        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2009      | 40.42%  |
| Qualcomm Atheros                | 1010      | 20.32%  |
| Realtek Semiconductor           | 845       | 17%     |
| Broadcom                        | 555       | 11.17%  |
| Broadcom Limited                | 151       | 3.04%   |
| Ralink                          | 91        | 1.83%   |
| MediaTek                        | 71        | 1.43%   |
| TP-Link                         | 46        | 0.93%   |
| Ralink Technology               | 45        | 0.91%   |
| Sierra Wireless                 | 32        | 0.64%   |
| Dell                            | 22        | 0.44%   |
| Qualcomm Atheros Communications | 13        | 0.26%   |
| NetGear                         | 11        | 0.22%   |
| Edimax Technology               | 9         | 0.18%   |
| D-Link                          | 9         | 0.18%   |
| ASUSTek Computer                | 8         | 0.16%   |
| Hewlett-Packard                 | 6         | 0.12%   |
| D-Link System                   | 5         | 0.1%    |
| Belkin Components               | 5         | 0.1%    |
| Qualcomm                        | 4         | 0.08%   |
| Microsoft                       | 3         | 0.06%   |
| Linksys                         | 3         | 0.06%   |
| ZyDAS                           | 2         | 0.04%   |
| TRENDnet                        | 2         | 0.04%   |
| Micro Star International        | 2         | 0.04%   |
| Fibocom                         | 2         | 0.04%   |
| ZyXEL Communications            | 1         | 0.02%   |
| Xiaomi                          | 1         | 0.02%   |
| Tenda                           | 1         | 0.02%   |
| Sitecom Europe                  | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Mercucys                        | 1         | 0.02%   |
| Lite-On Technology              | 1         | 0.02%   |
| IMC Networks                    | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 213       | 4.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 199       | 3.97%   |
| Intel Wireless 7260                                                     | 178       | 3.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 171       | 3.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 161       | 3.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 136       | 2.71%   |
| Intel Wireless 7265                                                     | 133       | 2.65%   |
| Intel Wireless 8265 / 8275                                              | 127       | 2.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 116       | 2.31%   |
| Intel Wi-Fi 6 AX201                                                     | 112       | 2.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 112       | 2.23%   |
| Intel Wireless 8260                                                     | 98        | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 94        | 1.88%   |
| Intel Wireless 3165                                                     | 91        | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 88        | 1.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 84        | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 82        | 1.64%   |
| Intel Wi-Fi 6 AX200                                                     | 79        | 1.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 78        | 1.56%   |
| Intel WiFi Link 5100                                                    | 75        | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 71        | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 1.26%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 62        | 1.24%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 55        | 1.1%    |
| Intel Centrino Ultimate-N 6300                                          | 53        | 1.06%   |
| Intel Wireless 3160                                                     | 52        | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 52        | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 51        | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 50        | 1%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 49        | 0.98%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 43        | 0.86%   |
| Intel Centrino Advanced-N 6200                                          | 43        | 0.86%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 41        | 0.82%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 41        | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 40        | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 40        | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 40        | 0.8%    |
| Intel Centrino Wireless-N 2230                                          | 39        | 0.78%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 39        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 38        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2086      | 51.8%   |
| Intel                                  | 816       | 20.26%  |
| Qualcomm Atheros                       | 309       | 7.67%   |
| Broadcom                               | 253       | 6.28%   |
| Marvell Technology Group               | 127       | 3.15%   |
| Broadcom Limited                       | 72        | 1.79%   |
| Nvidia                                 | 60        | 1.49%   |
| ASIX Electronics                       | 41        | 1.02%   |
| JMicron Technology                     | 36        | 0.89%   |
| Silicon Integrated Systems [SiS]       | 33        | 0.82%   |
| Samsung Electronics                    | 31        | 0.77%   |
| DisplayLink                            | 21        | 0.52%   |
| Xiaomi                                 | 20        | 0.5%    |
| MediaTek                               | 13        | 0.32%   |
| VIA Technologies                       | 12        | 0.3%    |
| OPPO Electronics                       | 12        | 0.3%    |
| TP-Link                                | 10        | 0.25%   |
| Motorola PCS                           | 10        | 0.25%   |
| Huawei Technologies                    | 10        | 0.25%   |
| Qualcomm                               | 9         | 0.22%   |
| Hewlett-Packard                        | 7         | 0.17%   |
| Attansic Technology                    | 7         | 0.17%   |
| Lenovo                                 | 6         | 0.15%   |
| Google                                 | 4         | 0.1%    |
| T & A Mobile Phones                    | 3         | 0.07%   |
| Spreadtrum Communications              | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.05%   |
| Davicom Semiconductor                  | 2         | 0.05%   |
| ASUSTek Computer                       | 2         | 0.05%   |
| vivo                                   | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| Motorola BCS                           | 1         | 0.02%   |
| Linksys                                | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| ICS Advent                             | 1         | 0.02%   |
| HTC (High Tech Computer)               | 1         | 0.02%   |
| HMD Global                             | 1         | 0.02%   |
| GoPro                                  | 1         | 0.02%   |
| Unknown                                | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1267      | 31.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 615       | 15.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 187       | 4.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 95        | 2.35%   |
| Intel Ethernet Connection I218-LM                                      | 56        | 1.38%   |
| Intel Ethernet Connection I217-LM                                      | 55        | 1.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 54        | 1.33%   |
| Intel 82577LM Gigabit Network Connection                               | 52        | 1.28%   |
| Intel Ethernet Connection I219-LM                                      | 51        | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                                  | 49        | 1.21%   |
| Intel 82567LM Gigabit Network Connection                               | 47        | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 43        | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                                  | 38        | 0.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 38        | 0.94%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 36        | 0.89%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 36        | 0.89%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 34        | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                          | 34        | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 31        | 0.77%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 30        | 0.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 30        | 0.74%   |
| Nvidia MCP79 Ethernet                                                  | 29        | 0.72%   |
| Intel Ethernet Connection I219-V                                       | 28        | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                   | 28        | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 27        | 0.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 26        | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 26        | 0.64%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 25        | 0.62%   |
| Intel 82566MM Gigabit Network Connection                               | 25        | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 24        | 0.59%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 22        | 0.54%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 21        | 0.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 21        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 20        | 0.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 19        | 0.47%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 19        | 0.47%   |
| Realtek Killer E2600 GbE Controller                                    | 18        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 18        | 0.44%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 18        | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 17        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4650      | 53.76%  |
| Ethernet | 3872      | 44.76%  |
| Modem    | 123       | 1.42%   |
| Unknown  | 5         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3946      | 79.41%  |
| Ethernet | 1021      | 20.55%  |
| Modem    | 1         | 0.02%   |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3554      | 74.06%  |
| 1     | 1059      | 22.07%  |
| 0     | 166       | 3.46%   |
| 3     | 19        | 0.4%    |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3507      | 72.04%  |
| Yes  | 1361      | 27.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1371      | 40.41%  |
| Realtek Semiconductor           | 401       | 11.82%  |
| Qualcomm Atheros Communications | 364       | 10.73%  |
| Broadcom                        | 222       | 6.54%   |
| IMC Networks                    | 156       | 4.6%    |
| Apple                           | 151       | 4.45%   |
| Lite-On Technology              | 119       | 3.51%   |
| Foxconn / Hon Hai               | 119       | 3.51%   |
| Dell                            | 99        | 2.92%   |
| Hewlett-Packard                 | 94        | 2.77%   |
| Toshiba                         | 64        | 1.89%   |
| Cambridge Silicon Radio         | 50        | 1.47%   |
| Ralink                          | 40        | 1.18%   |
| ASUSTek Computer                | 25        | 0.74%   |
| Alps Electric                   | 22        | 0.65%   |
| Realtek                         | 20        | 0.59%   |
| Foxconn International           | 16        | 0.47%   |
| Ralink Technology               | 9         | 0.27%   |
| MediaTek                        | 8         | 0.24%   |
| Askey Computer                  | 8         | 0.24%   |
| Taiyo Yuden                     | 6         | 0.18%   |
| Dynex                           | 4         | 0.12%   |
| Unknown                         | 4         | 0.12%   |
| TP-Link                         | 3         | 0.09%   |
| Qcom                            | 3         | 0.09%   |
| Chicony Electronics             | 3         | 0.09%   |
| Actions                         | 3         | 0.09%   |
| Integrated System Solution      | 2         | 0.06%   |
| USI                             | 1         | 0.03%   |
| Smart Modular Technologies      | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Conwise Technology              | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |
| Actiontec Electronics           | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 649       | 19.11%  |
| Realtek Bluetooth Radio                             | 239       | 7.04%   |
| Intel AX201 Bluetooth                               | 225       | 6.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 180       | 5.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 157       | 4.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 101       | 2.97%   |
| Apple Bluetooth Host Controller                     | 89        | 2.62%   |
| Intel AX200 Bluetooth                               | 77        | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 71        | 2.09%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 66        | 1.94%   |
| Intel AX211 Bluetooth                               | 60        | 1.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 56        | 1.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 53        | 1.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 50        | 1.47%   |
| IMC Networks Bluetooth Device                       | 46        | 1.35%   |
| Ralink RT3290 Bluetooth                             | 40        | 1.18%   |
| IMC Networks Wireless_Device                        | 39        | 1.15%   |
| IMC Networks Bluetooth Radio                        | 38        | 1.12%   |
| Apple Bluetooth USB Host Controller                 | 38        | 1.12%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 37        | 1.09%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 37        | 1.09%   |
| HP Broadcom 2070 Bluetooth Combo                    | 35        | 1.03%   |
| Lite-On Atheros AR3012 Bluetooth                    | 34        | 1%      |
| Foxconn / Hon Hai Bluetooth Device                  | 33        | 0.97%   |
| Intel AX210 Bluetooth                               | 32        | 0.94%   |
| Dell DW375 Bluetooth Module                         | 32        | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 31        | 0.91%   |
| Broadcom BCM2045B (BDC-2.1)                         | 30        | 0.88%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 29        | 0.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 27        | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 25        | 0.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 25        | 0.74%   |
| Lite-On Bluetooth Device                            | 24        | 0.71%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 24        | 0.71%   |
| Realtek 802.11ac WLAN Adapter                       | 23        | 0.68%   |
| Realtek Bluetooth Radio                             | 20        | 0.59%   |
| Toshiba Bluetooth Device                            | 17        | 0.5%    |
| Realtek RTL8723B Bluetooth                          | 17        | 0.5%    |
| Dell Wireless 365 Bluetooth                         | 17        | 0.5%    |
| Broadcom HP Portable SoftSailing                    | 17        | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3828      | 69.26%  |
| AMD                                  | 868       | 15.7%   |
| Nvidia                               | 599       | 10.84%  |
| Silicon Integrated Systems [SiS]     | 38        | 0.69%   |
| C-Media Electronics                  | 23        | 0.42%   |
| Generalplus Technology               | 14        | 0.25%   |
| VIA Technologies                     | 13        | 0.24%   |
| Logitech                             | 11        | 0.2%    |
| Realtek Semiconductor                | 9         | 0.16%   |
| Lenovo                               | 8         | 0.14%   |
| Texas Instruments                    | 7         | 0.13%   |
| GN Netcom                            | 7         | 0.13%   |
| Tenx Technology                      | 6         | 0.11%   |
| Plantronics                          | 6         | 0.11%   |
| JMTek                                | 6         | 0.11%   |
| SteelSeries ApS                      | 5         | 0.09%   |
| Sony                                 | 5         | 0.09%   |
| Creative Technology                  | 5         | 0.09%   |
| Apple                                | 5         | 0.09%   |
| Hewlett-Packard                      | 4         | 0.07%   |
| Focusrite-Novation                   | 4         | 0.07%   |
| PreSonus Audio Electronics           | 3         | 0.05%   |
| KTMicro                              | 3         | 0.05%   |
| ASUSTek Computer                     | 3         | 0.05%   |
| AKAI Professional M.I.               | 3         | 0.05%   |
| Unknown                              | 3         | 0.05%   |
| Yamaha                               | 2         | 0.04%   |
| Walmart                              | 2         | 0.04%   |
| SAVITECH                             | 2         | 0.04%   |
| Razer USA                            | 2         | 0.04%   |
| OPPO Electronics                     | 2         | 0.04%   |
| M-Audio                              | 2         | 0.04%   |
| FiiO Electronics Technology          | 2         | 0.04%   |
| Dell                                 | 2         | 0.04%   |
| Corsair                              | 2         | 0.04%   |
| Conexant Systems                     | 2         | 0.04%   |
| ZOOM                                 | 1         | 0.02%   |
| XMOS                                 | 1         | 0.02%   |
| Weltrend Semiconductor               | 1         | 0.02%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 465       | 6.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 445       | 6.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 334       | 4.99%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 314       | 4.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 282       | 4.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 251       | 3.75%   |
| Intel 8 Series HD Audio Controller                                                                | 229       | 3.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 225       | 3.36%   |
| AMD FCH Azalia Controller                                                                         | 194       | 2.9%    |
| Intel Broadwell-U Audio Controller                                                                | 167       | 2.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 167       | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 165       | 2.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 162       | 2.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 159       | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 149       | 2.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 144       | 2.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 140       | 2.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 128       | 1.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 128       | 1.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 105       | 1.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 102       | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 95        | 1.42%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 87        | 1.3%    |
| Intel Cannon Lake PCH cAVS                                                                        | 82        | 1.23%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 77        | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 73        | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 72        | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 68        | 1.02%   |
| AMD High Definition Audio Controller                                                              | 66        | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 65        | 0.97%   |
| Intel CM238 HD Audio Controller                                                                   | 61        | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 60        | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 54        | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 47        | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 43        | 0.64%   |
| AMD Wrestler HDMI Audio                                                                           | 43        | 0.64%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 42        | 0.63%   |
| Intel Comet Lake PCH cAVS                                                                         | 42        | 0.63%   |
| Nvidia High Definition Audio Controller                                                           | 38        | 0.57%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 37        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 303       | 27.32%  |
| SK hynix               | 249       | 22.45%  |
| Micron Technology      | 136       | 12.26%  |
| Unknown                | 96        | 8.66%   |
| Kingston               | 78        | 7.03%   |
| Crucial                | 38        | 3.43%   |
| Unknown (ABCD)         | 31        | 2.8%    |
| Elpida                 | 22        | 1.98%   |
| Ramaxel Technology     | 20        | 1.8%    |
| A-DATA Technology      | 20        | 1.8%    |
| Nanya Technology       | 16        | 1.44%   |
| Smart                  | 11        | 0.99%   |
| Corsair                | 9         | 0.81%   |
| Unknown                | 9         | 0.81%   |
| Team                   | 6         | 0.54%   |
| Transcend              | 5         | 0.45%   |
| G.Skill                | 5         | 0.45%   |
| Timetec                | 4         | 0.36%   |
| Qimonda                | 4         | 0.36%   |
| Patriot                | 4         | 0.36%   |
| Teikon                 | 3         | 0.27%   |
| Smart Brazil           | 3         | 0.27%   |
| SHARETRONIC            | 2         | 0.18%   |
| High Bridge            | 2         | 0.18%   |
| ff                     | 2         | 0.18%   |
| fef5                   | 2         | 0.18%   |
| Axiom                  | 2         | 0.18%   |
| 4ea5                   | 2         | 0.18%   |
| Walton Chaintech       | 1         | 0.09%   |
| Unknown (08B5)         | 1         | 0.09%   |
| Unknown (07F7)         | 1         | 0.09%   |
| Unknown (000080B30080) | 1         | 0.09%   |
| Toshiba                | 1         | 0.09%   |
| Strontium              | 1         | 0.09%   |
| Silicon Power          | 1         | 0.09%   |
| PUSKILL                | 1         | 0.09%   |
| ProMos/Mosel Vitelic   | 1         | 0.09%   |
| pqi                    | 1         | 0.09%   |
| PNY                    | 1         | 0.09%   |
| Netlist                | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 27        | 2.31%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 16        | 1.37%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 13        | 1.11%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 12        | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.02%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 12        | 1.02%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 11        | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.94%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.94%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.85%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.77%   |
| Unknown                                                          | 9         | 0.77%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 8         | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.68%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 8         | 0.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.6%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 7         | 0.6%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 7         | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.6%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 6         | 0.51%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 6         | 0.51%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 6         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.43%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.43%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 5         | 0.43%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.43%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 349       | 37.21%  |
| DDR3    | 334       | 35.61%  |
| DDR2    | 81        | 8.64%   |
| LPDDR4  | 64        | 6.82%   |
| SDRAM   | 31        | 3.3%    |
| LPDDR3  | 25        | 2.67%   |
| LPDDR5  | 20        | 2.13%   |
| DDR5    | 14        | 1.49%   |
| DDR     | 7         | 0.75%   |
| Unknown | 7         | 0.75%   |
| DRAM    | 6         | 0.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 801       | 85.67%  |
| Row Of Chips | 97        | 10.37%  |
| DIMM         | 16        | 1.71%   |
| Chip         | 11        | 1.18%   |
| Unknown      | 10        | 1.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 367       | 35.09%  |
| 4096  | 308       | 29.45%  |
| 2048  | 181       | 17.3%   |
| 16384 | 101       | 9.66%   |
| 1024  | 62        | 5.93%   |
| 32768 | 12        | 1.15%   |
| 512   | 12        | 1.15%   |
| 256   | 2         | 0.19%   |
| 12288 | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 226       | 22.38%  |
| 3200    | 160       | 15.84%  |
| 2667    | 150       | 14.85%  |
| 2400    | 86        | 8.51%   |
| 1334    | 50        | 4.95%   |
| 667     | 42        | 4.16%   |
| 1333    | 38        | 3.76%   |
| Unknown | 38        | 3.76%   |
| 2133    | 36        | 3.56%   |
| 1066    | 19        | 1.88%   |
| 800     | 18        | 1.78%   |
| 4267    | 16        | 1.58%   |
| 6400    | 15        | 1.49%   |
| 4199    | 12        | 1.19%   |
| 3266    | 12        | 1.19%   |
| 2048    | 12        | 1.19%   |
| 1067    | 11        | 1.09%   |
| 975     | 11        | 1.09%   |
| 4800    | 10        | 0.99%   |
| 533     | 10        | 0.99%   |
| 1867    | 9         | 0.89%   |
| 5600    | 5         | 0.5%    |
| 8400    | 4         | 0.4%    |
| 4266    | 3         | 0.3%    |
| 3733    | 3         | 0.3%    |
| 2933    | 3         | 0.3%    |
| 400     | 3         | 0.3%    |
| 7500    | 2         | 0.2%    |
| 7467    | 2         | 0.2%    |
| 8533    | 1         | 0.1%    |
| 5500    | 1         | 0.1%    |
| 1866    | 1         | 0.1%    |
| 1639    | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 20        | 41.67%  |
| Seiko Epson           | 9         | 18.75%  |
| Canon                 | 7         | 14.58%  |
| Brother Industries    | 4         | 8.33%   |
| Samsung Electronics   | 3         | 6.25%   |
| Zebra                 | 2         | 4.17%   |
| STMicroelectronics    | 1         | 2.08%   |
| Lexmark International | 1         | 2.08%   |
| Dymo-CoStar           | 1         | 2.08%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                          | 2         | 4.17%   |
| HP ENVY Photo 6200 series                                 | 2         | 4.17%   |
| HP Deskjet 1510                                           | 2         | 4.17%   |
| HP DeskJet 1110 series                                    | 2         | 4.17%   |
| Canon TS3100 series                                       | 2         | 4.17%   |
| Zebra ZP 450 Printer                                      | 1         | 2.08%   |
| Zebra GK420d Label Printer                                | 1         | 2.08%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.08%   |
| Seiko Epson XP-4100 Series                                | 1         | 2.08%   |
| Seiko Epson XP-235 Series                                 | 1         | 2.08%   |
| Seiko Epson WF-2010 Series                                | 1         | 2.08%   |
| Seiko Epson TM-T20X                                       | 1         | 2.08%   |
| Seiko Epson Printer                                       | 1         | 2.08%   |
| Seiko Epson L3150 Series                                  | 1         | 2.08%   |
| Seiko Epson L3110 Series                                  | 1         | 2.08%   |
| Seiko Epson ET-2810 Series                                | 1         | 2.08%   |
| Seiko Epson AcuLaser C1700                                | 1         | 2.08%   |
| Samsung M2020 Series                                      | 1         | 2.08%   |
| Samsung CLX-3300 Series                                   | 1         | 2.08%   |
| Samsung C43x Series                                       | 1         | 2.08%   |
| Lexmark International 2400 series                         | 1         | 2.08%   |
| HP Smart Tank 500 series                                  | 1         | 2.08%   |
| HP Printing Support                                       | 1         | 2.08%   |
| HP Laserjet P1505                                         | 1         | 2.08%   |
| HP LaserJet P1102                                         | 1         | 2.08%   |
| HP LaserJet 1200                                          | 1         | 2.08%   |
| HP LaserJet 1010                                          | 1         | 2.08%   |
| HP LaserJet 1000                                          | 1         | 2.08%   |
| HP HP LaserJet M14-M17                                    | 1         | 2.08%   |
| HP ENVY 4520 series                                       | 1         | 2.08%   |
| HP DeskJet 2700 series                                    | 1         | 2.08%   |
| HP DeskJet 2300 series                                    | 1         | 2.08%   |
| HP DeskJet 2130 series                                    | 1         | 2.08%   |
| Dymo-CoStar LabelWriter 450                               | 1         | 2.08%   |
| Canon PIXMA MX490 Series                                  | 1         | 2.08%   |
| Canon PIXMA MX340                                         | 1         | 2.08%   |
| Canon PIXMA MG3600 Series                                 | 1         | 2.08%   |
| Canon PIXMA MG3000 series                                 | 1         | 2.08%   |
| Canon MG2100 series                                       | 1         | 2.08%   |
| Brother MFC-L2730DW series                                | 1         | 2.08%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 7         | 63.64%  |
| Seiko Epson | 4         | 36.36%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo]       | 3         | 27.27%  |
| Canon CanoScan LiDE 110                           | 2         | 18.18%  |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 9.09%   |
| Canon CanoScan N670U/N676U/LiDE 20                | 1         | 9.09%   |
| Canon CanoScan LiDE 90                            | 1         | 9.09%   |
| Canon CanoScan LiDE 700F                          | 1         | 9.09%   |
| Canon CanoScan LIDE 25                            | 1         | 9.09%   |
| Canon CanoScan LiDE 200                           | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 971       | 24.21%  |
| Microdia                               | 355       | 8.85%   |
| Realtek Semiconductor                  | 321       | 8%      |
| IMC Networks                           | 306       | 7.63%   |
| Bison Electronics                      | 240       | 5.98%   |
| Sunplus Innovation Technology          | 232       | 5.78%   |
| Suyin                                  | 197       | 4.91%   |
| Quanta                                 | 192       | 4.79%   |
| Cheng Uei Precision Industry (Foxlink) | 178       | 4.44%   |
| Apple                                  | 122       | 3.04%   |
| Syntek                                 | 97        | 2.42%   |
| Lite-On Technology                     | 85        | 2.12%   |
| Silicon Motion                         | 84        | 2.09%   |
| Alcor Micro                            | 77        | 1.92%   |
| Acer                                   | 58        | 1.45%   |
| Luxvisions Innotech Limited            | 53        | 1.32%   |
| Ricoh                                  | 51        | 1.27%   |
| Sonix Technology                       | 40        | 1%      |
| Logitech                               | 33        | 0.82%   |
| icSpring                               | 26        | 0.65%   |
| Importek                               | 25        | 0.62%   |
| SunplusIT                              | 24        | 0.6%    |
| Samsung Electronics                    | 23        | 0.57%   |
| ALi                                    | 23        | 0.57%   |
| Primax Electronics                     | 20        | 0.5%    |
| Lenovo                                 | 17        | 0.42%   |
| OmniVision Technologies                | 14        | 0.35%   |
| Z-Star Microelectronics                | 13        | 0.32%   |
| ShineTech                              | 11        | 0.27%   |
| Y Media                                | 9         | 0.22%   |
| GEMBIRD                                | 9         | 0.22%   |
| Genesys Logic                          | 8         | 0.2%    |
| Unknown                                | 7         | 0.17%   |
| Sunplus Technology                     | 6         | 0.15%   |
| Microsoft                              | 6         | 0.15%   |
| Shine-optics                           | 5         | 0.12%   |
| Intel                                  | 5         | 0.12%   |
| Generalplus Technology                 | 5         | 0.12%   |
| DigiTech                               | 5         | 0.12%   |
| Nebraska Furniture Mart                | 4         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 140       | 3.48%   |
| Microdia Integrated_Webcam_HD                           | 82        | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 73        | 1.82%   |
| Bison Integrated Camera                                 | 68        | 1.69%   |
| Realtek Integrated_Webcam_HD                            | 67        | 1.67%   |
| Chicony HD Webcam                                       | 63        | 1.57%   |
| IMC Networks Integrated Camera                          | 56        | 1.39%   |
| Sunplus Integrated_Webcam_HD                            | 50        | 1.24%   |
| Chicony HP Truevision HD                                | 50        | 1.24%   |
| Syntek Integrated Camera                                | 48        | 1.19%   |
| Microdia Integrated Webcam                              | 48        | 1.19%   |
| Chicony TOSHIBA Web Camera - HD                         | 44        | 1.09%   |
| Chicony HP TrueVision HD Camera                         | 43        | 1.07%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 38        | 0.94%   |
| Apple Built-in iSight                                   | 37        | 0.92%   |
| Alcor Micro USB 2.0 Camera                              | 37        | 0.92%   |
| Realtek USB Camera                                      | 35        | 0.87%   |
| Bison Lenovo EasyCamera                                 | 35        | 0.87%   |
| Apple FaceTime HD Camera                                | 35        | 0.87%   |
| Sunplus HD WebCam                                       | 33        | 0.82%   |
| Chicony EasyCamera                                      | 32        | 0.8%    |
| Suyin HP Truevision HD                                  | 31        | 0.77%   |
| Realtek Integrated Webcam                               | 30        | 0.75%   |
| Lite-On HP HD Camera                                    | 30        | 0.75%   |
| Chicony USB 2.0 Camera                                  | 30        | 0.75%   |
| Chicony HP HD Webcam                                    | 30        | 0.75%   |
| Chicony Lenovo EasyCamera                               | 29        | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 29        | 0.72%   |
| Quanta HD User Facing                                   | 28        | 0.7%    |
| Chicony HP HD Camera                                    | 28        | 0.7%    |
| Chicony VGA Webcam                                      | 27        | 0.67%   |
| icSpring camera                                         | 26        | 0.65%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 26        | 0.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 25        | 0.62%   |
| Microdia Sonix USB 2.0 Camera                           | 24        | 0.6%    |
| Chicony HP Webcam                                       | 24        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 24        | 0.6%    |
| Sonix USB2.0 HD UVC WebCam                              | 23        | 0.57%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 23        | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 23        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 333       | 48.9%   |
| AuthenTec                          | 86        | 12.63%  |
| Synaptics                          | 70        | 10.28%  |
| Shenzhen Goodix Technology         | 68        | 9.99%   |
| Upek                               | 48        | 7.05%   |
| Elan Microelectronics              | 30        | 4.41%   |
| STMicroelectronics                 | 20        | 2.94%   |
| LighTuning Technology              | 14        | 2.06%   |
| Realtek USB2.0 Finger Print Bridge | 6         | 0.88%   |
| Samsung Electronics                | 3         | 0.44%   |
| Focal-systems.Corp                 | 2         | 0.29%   |
| FocalTech                          | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 76        | 11.16%  |
| Shenzhen Goodix  FingerPrint Device                                        | 48        | 7.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 45        | 6.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 37        | 5.43%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 36        | 5.29%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 4.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 29        | 4.26%   |
| Validity Sensors Fingerprint scanner                                       | 28        | 4.11%   |
| Validity Sensors VFS491                                                    | 26        | 3.82%   |
| AuthenTec AES2810                                                          | 23        | 3.38%   |
| Validity Sensors Synaptics WBDI                                            | 20        | 2.94%   |
| STMicroelectronics Fingerprint Reader                                      | 20        | 2.94%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 17        | 2.5%    |
| Elan ELAN:ARM-M4                                                           | 17        | 2.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 16        | 2.35%   |
| AuthenTec AES1600                                                          | 16        | 2.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 2.06%   |
| Synaptics Fingerprint reader [HP G6]                                       | 13        | 1.91%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 1.76%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 1.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.62%   |
| Elan ELAN:Fingerprint                                                      | 10        | 1.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 1.32%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 1.17%   |
| Shenzhen Goodix FingerPrint                                                | 8         | 1.17%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 1.17%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 7         | 1.03%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 1.03%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 6         | 0.88%   |
| LighTuning Fingerprint Reader                                              | 6         | 0.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 0.88%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.73%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 5         | 0.73%   |
| Synaptics  WBDI                                                            | 4         | 0.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.59%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 0.59%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.44%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.44%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 173       | 54.75%  |
| Alcor Micro                       | 53        | 16.77%  |
| O2 Micro                          | 36        | 11.39%  |
| Upek                              | 19        | 6.01%   |
| Lenovo                            | 17        | 5.38%   |
| SCM Microsystems                  | 5         | 1.58%   |
| Yubico.com                        | 2         | 0.63%   |
| VASCO Data Security International | 2         | 0.63%   |
| Realtek Semiconductor             | 2         | 0.63%   |
| Gemalto (was Gemplus)             | 2         | 0.63%   |
| Reiner SCT Kartensysteme          | 1         | 0.32%   |
| OmniKey                           | 1         | 0.32%   |
| Fujitsu Siemens Computers         | 1         | 0.32%   |
| Chicony Electronics               | 1         | 0.32%   |
| Athena Smartcard Solutions        | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 77        | 24.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 52        | 16.4%   |
| Broadcom 5880                                                                | 43        | 13.56%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 37        | 11.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 31        | 9.78%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 19        | 5.99%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 5.36%   |
| Broadcom 58200                                                               | 15        | 4.73%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.58%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 4         | 1.26%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.63%   |
| VASCO Data Security International DIGIPASS 870                               | 2         | 0.63%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.63%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.63%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.32%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.32%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.32%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.32%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.32%   |
| Athena Smartcard Solutions ASEDrive V3C                                      | 1         | 0.32%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3006      | 61.65%  |
| 1     | 1461      | 29.96%  |
| 2     | 356       | 7.3%    |
| 3     | 48        | 0.98%   |
| 4     | 3         | 0.06%   |
| 7     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 671       | 29.64%  |
| Graphics card            | 561       | 24.78%  |
| Chipcard                 | 303       | 13.38%  |
| Net/wireless             | 247       | 10.91%  |
| Multimedia controller    | 192       | 8.48%   |
| Storage                  | 69        | 3.05%   |
| Bluetooth                | 52        | 2.3%    |
| Modem                    | 38        | 1.68%   |
| Camera                   | 36        | 1.59%   |
| Sound                    | 22        | 0.97%   |
| Communication controller | 20        | 0.88%   |
| Flash memory             | 16        | 0.71%   |
| Net/ethernet             | 12        | 0.53%   |
| Card reader              | 8         | 0.35%   |
| Network                  | 6         | 0.27%   |
| Storage/ide              | 4         | 0.18%   |
| Unclassified device      | 2         | 0.09%   |
| Storage/nvme             | 2         | 0.09%   |
| Dvb card                 | 2         | 0.09%   |
| Storage/ata              | 1         | 0.04%   |

