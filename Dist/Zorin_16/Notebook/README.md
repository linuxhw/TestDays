Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 1267

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Gaming Laptop 1... | [f54987d748](https://linux-hardware.org/?probe=f54987d748) | Jul 01, 2022 |
| MSI           | CR620                       | [0968b18823](https://linux-hardware.org/?probe=0968b18823) | Jun 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [7d85e08611](https://linux-hardware.org/?probe=7d85e08611) | Jun 29, 2022 |
| Dell          | Inspiron 3531               | [2c8286100d](https://linux-hardware.org/?probe=2c8286100d) | Jun 29, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [3e451a9d00](https://linux-hardware.org/?probe=3e451a9d00) | Jun 28, 2022 |
| HP            | Pavilion Notebook           | [6e098b9c49](https://linux-hardware.org/?probe=6e098b9c49) | Jun 27, 2022 |
| Lenovo        | V14-IIL 82C4                | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Dell          | XPS 15 9570                 | [8cf2281f01](https://linux-hardware.org/?probe=8cf2281f01) | Jun 27, 2022 |
| Acer          | Aspire A515-55G             | [d05c52e40b](https://linux-hardware.org/?probe=d05c52e40b) | Jun 26, 2022 |
| Google        | Candy                       | [8888e44843](https://linux-hardware.org/?probe=8888e44843) | Jun 25, 2022 |
| HP            | Laptop 15-db0xxx            | [26cd390b15](https://linux-hardware.org/?probe=26cd390b15) | Jun 24, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [8f8ce01734](https://linux-hardware.org/?probe=8f8ce01734) | Jun 24, 2022 |
| Lenovo        | ThinkPad T420 4236J73       | [088ba8b97c](https://linux-hardware.org/?probe=088ba8b97c) | Jun 23, 2022 |
| Dell          | XPS 13 9360                 | [d5d7479c46](https://linux-hardware.org/?probe=d5d7479c46) | Jun 22, 2022 |
| Acer          | Swift SF314-54              | [3e80b4439f](https://linux-hardware.org/?probe=3e80b4439f) | Jun 22, 2022 |
| Dell          | Inspiron 5537               | [6b549dfe09](https://linux-hardware.org/?probe=6b549dfe09) | Jun 22, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [3bd256be91](https://linux-hardware.org/?probe=3bd256be91) | Jun 21, 2022 |
| Lenovo        | ThinkPad T430s 23539MU      | [cb159502de](https://linux-hardware.org/?probe=cb159502de) | Jun 21, 2022 |
| Dell          | Latitude E6540              | [c0f2801648](https://linux-hardware.org/?probe=c0f2801648) | Jun 21, 2022 |
| Dell          | XPS 12 9Q23                 | [463461920a](https://linux-hardware.org/?probe=463461920a) | Jun 21, 2022 |
| Dell          | Latitude E6540              | [7d19e0b30e](https://linux-hardware.org/?probe=7d19e0b30e) | Jun 20, 2022 |
| Toshiba       | Satellite C870-1C2          | [421b2e1975](https://linux-hardware.org/?probe=421b2e1975) | Jun 20, 2022 |
| Lenovo        | Flex 2-15 20405             | [0cae0765c9](https://linux-hardware.org/?probe=0cae0765c9) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| HP            | EliteBook 840 G1            | [4a3e29a7c0](https://linux-hardware.org/?probe=4a3e29a7c0) | Jun 20, 2022 |
| Global Dis... | W11651                      | [a28b308f7f](https://linux-hardware.org/?probe=a28b308f7f) | Jun 19, 2022 |
| Dell          | Inspiron N5010              | [82ab434998](https://linux-hardware.org/?probe=82ab434998) | Jun 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a20ee1d5b6](https://linux-hardware.org/?probe=a20ee1d5b6) | Jun 17, 2022 |
| Dell          | Latitude E6540              | [4806aec13b](https://linux-hardware.org/?probe=4806aec13b) | Jun 16, 2022 |
| ASUSTek       | X540LJ                      | [a07f3b6954](https://linux-hardware.org/?probe=a07f3b6954) | Jun 16, 2022 |
| Dell          | Precision M4700             | [3d10ec3c17](https://linux-hardware.org/?probe=3d10ec3c17) | Jun 15, 2022 |
| Primux Tec... | Primux_1402F_W10            | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dell          | XPS 12 9Q23                 | [77c4dc4a62](https://linux-hardware.org/?probe=77c4dc4a62) | Jun 14, 2022 |
| GPU Compan... | GWTC116-2                   | [e849fd55ad](https://linux-hardware.org/?probe=e849fd55ad) | Jun 14, 2022 |
| Positivo      | Q464C                       | [1cb4cb4da1](https://linux-hardware.org/?probe=1cb4cb4da1) | Jun 13, 2022 |
| Positivo      | Q464C                       | [a772cd7eae](https://linux-hardware.org/?probe=a772cd7eae) | Jun 13, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [9baa7ce30e](https://linux-hardware.org/?probe=9baa7ce30e) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| HP            | Pavilion 17                 | [bed3614b80](https://linux-hardware.org/?probe=bed3614b80) | Jun 11, 2022 |
| Positivo      | C4500D                      | [70dc4735fa](https://linux-hardware.org/?probe=70dc4735fa) | Jun 11, 2022 |
| Acer          | Aspire 5736Z                | [dcaa9a66f4](https://linux-hardware.org/?probe=dcaa9a66f4) | Jun 10, 2022 |
| Lenovo        | G50-70 20351                | [828f110a40](https://linux-hardware.org/?probe=828f110a40) | Jun 10, 2022 |
| Dell          | Inspiron 5520               | [d80ec10f91](https://linux-hardware.org/?probe=d80ec10f91) | Jun 09, 2022 |
| Dell          | Inspiron 5520               | [39e10fd449](https://linux-hardware.org/?probe=39e10fd449) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | [8b2e214403](https://linux-hardware.org/?probe=8b2e214403) | Jun 08, 2022 |
| Samsung       | 600B4B/600B5B               | [431ccbf84a](https://linux-hardware.org/?probe=431ccbf84a) | Jun 08, 2022 |
| Toshiba       | Satellite A200              | [9719a84d3e](https://linux-hardware.org/?probe=9719a84d3e) | Jun 08, 2022 |
| Dell          | Inspiron 11-3168            | [9651975542](https://linux-hardware.org/?probe=9651975542) | Jun 07, 2022 |
| Dell          | Inspiron 11-3168            | [b43b02cdeb](https://linux-hardware.org/?probe=b43b02cdeb) | Jun 07, 2022 |
| HP            | Laptop 14-dq0xxx            | [39cfb21bae](https://linux-hardware.org/?probe=39cfb21bae) | Jun 07, 2022 |
| Lenovo        | ThinkPad T540p 20BF0038G... | [e7d830048d](https://linux-hardware.org/?probe=e7d830048d) | Jun 06, 2022 |
| Dell          | Inspiron 3521               | [81fad50492](https://linux-hardware.org/?probe=81fad50492) | Jun 06, 2022 |
| Lenovo        | V14-ADA 82C6                | [94d4930070](https://linux-hardware.org/?probe=94d4930070) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [2e08398c9a](https://linux-hardware.org/?probe=2e08398c9a) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [8edffcde03](https://linux-hardware.org/?probe=8edffcde03) | Jun 06, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [96ed2caf25](https://linux-hardware.org/?probe=96ed2caf25) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [4af3ead1a7](https://linux-hardware.org/?probe=4af3ead1a7) | Jun 06, 2022 |
| Dell          | Latitude E6430              | [0ebbfb5b74](https://linux-hardware.org/?probe=0ebbfb5b74) | Jun 05, 2022 |
| HP            | ProBook 450 G3              | [654b62a3bb](https://linux-hardware.org/?probe=654b62a3bb) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [63467c4755](https://linux-hardware.org/?probe=63467c4755) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8577975269](https://linux-hardware.org/?probe=8577975269) | Jun 05, 2022 |
| HP            | Pavilion dv6                | [8e20121256](https://linux-hardware.org/?probe=8e20121256) | Jun 04, 2022 |
| Dell          | Inspiron 15-5578            | [d88547de78](https://linux-hardware.org/?probe=d88547de78) | Jun 04, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Ematic        | EWT935DK                    | [13c5b6c48c](https://linux-hardware.org/?probe=13c5b6c48c) | Jun 03, 2022 |
| Medion        | WIM2180                     | [0548ef61b7](https://linux-hardware.org/?probe=0548ef61b7) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| Medion        | WIM2180                     | [b645a2fa42](https://linux-hardware.org/?probe=b645a2fa42) | Jun 03, 2022 |
| Lenovo        | G780 2182                   | [878e602f7d](https://linux-hardware.org/?probe=878e602f7d) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [71e59838a5](https://linux-hardware.org/?probe=71e59838a5) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [702f836250](https://linux-hardware.org/?probe=702f836250) | Jun 02, 2022 |
| Dell          | XPS 15 9510                 | [5eff529610](https://linux-hardware.org/?probe=5eff529610) | Jun 02, 2022 |
| Dell          | Inspiron 15-5578            | [7c1c1fa1ce](https://linux-hardware.org/?probe=7c1c1fa1ce) | Jun 01, 2022 |
| Apple         | MacBook2,1                  | [12cfa4cdb2](https://linux-hardware.org/?probe=12cfa4cdb2) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| HP            | EliteBook 8460p             | [a9cca9972f](https://linux-hardware.org/?probe=a9cca9972f) | May 31, 2022 |
| HP            | EliteBook 8460p             | [f05323c723](https://linux-hardware.org/?probe=f05323c723) | May 31, 2022 |
| Dell          | Inspiron 5770               | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| ASUSTek       | X450LD                      | [b77a4297da](https://linux-hardware.org/?probe=b77a4297da) | May 31, 2022 |
| Dell          | Inspiron 3541               | [20b5815ca3](https://linux-hardware.org/?probe=20b5815ca3) | May 31, 2022 |
| Dell          | Latitude E6510              | [4fe104ba1c](https://linux-hardware.org/?probe=4fe104ba1c) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | [dbf473f0a0](https://linux-hardware.org/?probe=dbf473f0a0) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | [574439c3c6](https://linux-hardware.org/?probe=574439c3c6) | May 30, 2022 |
| HP            | Compaq 6510b (KE135EA#AK... | [28c05654fc](https://linux-hardware.org/?probe=28c05654fc) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [33de40a2e1](https://linux-hardware.org/?probe=33de40a2e1) | May 29, 2022 |
| HP            | Laptop 14-dq0xxx            | [fac9e55ae9](https://linux-hardware.org/?probe=fac9e55ae9) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [0bf1fadaa2](https://linux-hardware.org/?probe=0bf1fadaa2) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [8895ea240a](https://linux-hardware.org/?probe=8895ea240a) | May 29, 2022 |
| Dell          | Latitude 3410               | [b1115f6bbc](https://linux-hardware.org/?probe=b1115f6bbc) | May 28, 2022 |
| HP            | Laptop 14-dq0xxx            | [7d47123b6c](https://linux-hardware.org/?probe=7d47123b6c) | May 28, 2022 |
| Dell          | Latitude D630               | [0560d4c462](https://linux-hardware.org/?probe=0560d4c462) | May 27, 2022 |
| Dell          | Inspiron 5423               | [bd9cd24b2d](https://linux-hardware.org/?probe=bd9cd24b2d) | May 26, 2022 |
| Acer          | Aspire E3-112M              | [240ed3197a](https://linux-hardware.org/?probe=240ed3197a) | May 26, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [ba19793a38](https://linux-hardware.org/?probe=ba19793a38) | May 26, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | [7a7ef6ced7](https://linux-hardware.org/?probe=7a7ef6ced7) | May 26, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [9d27d641ca](https://linux-hardware.org/?probe=9d27d641ca) | May 25, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [db3577b92d](https://linux-hardware.org/?probe=db3577b92d) | May 25, 2022 |
| Lenovo        | ThinkPad X230 2324FV6       | [6386696f31](https://linux-hardware.org/?probe=6386696f31) | May 25, 2022 |
| HP            | ZBook 15 G2                 | [42ebc7f075](https://linux-hardware.org/?probe=42ebc7f075) | May 25, 2022 |
| HP            | EliteBook 8760w             | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| ASUSTek       | X201EP                      | [a6e55f9bd8](https://linux-hardware.org/?probe=a6e55f9bd8) | May 25, 2022 |
| Toshiba       | Satellite C55-C             | [0c52032af4](https://linux-hardware.org/?probe=0c52032af4) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [a439693491](https://linux-hardware.org/?probe=a439693491) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [cca71eec7f](https://linux-hardware.org/?probe=cca71eec7f) | May 24, 2022 |
| Dell          | Venue 8 Pro 5830            | [c07937f5ea](https://linux-hardware.org/?probe=c07937f5ea) | May 24, 2022 |
| ASUSTek       | X201EP                      | [783e306676](https://linux-hardware.org/?probe=783e306676) | May 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | [aeb154944d](https://linux-hardware.org/?probe=aeb154944d) | May 24, 2022 |
| Dell          | Latitude D520               | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Lenovo        | ThinkPad X301 277418G       | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | [bcccd55aab](https://linux-hardware.org/?probe=bcccd55aab) | May 24, 2022 |
| Toshiba       | Satellite L75D-A            | [0a4b6bedbf](https://linux-hardware.org/?probe=0a4b6bedbf) | May 24, 2022 |
| ASUSTek       | X756UQ                      | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| Toshiba       | Satellite L10W-C            | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| ASUSTek       | K43U                        | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| Positivo      | CHT14B                      | [435bbd3b75](https://linux-hardware.org/?probe=435bbd3b75) | May 20, 2022 |
| HP            | Laptop 15-bs1xx             | [e2a3654000](https://linux-hardware.org/?probe=e2a3654000) | May 20, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [8e5e8ea1ba](https://linux-hardware.org/?probe=8e5e8ea1ba) | May 20, 2022 |
| Medion        | Akoya S6214T                | [b0a0df98e0](https://linux-hardware.org/?probe=b0a0df98e0) | May 20, 2022 |
| HP            | EliteBook Folio 1040 G3     | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| ASUSTek       | K43U                        | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| HP            | Pavilion g4                 | [dcb7b65b12](https://linux-hardware.org/?probe=dcb7b65b12) | May 18, 2022 |
| Gateway       | NV55C                       | [16404d222a](https://linux-hardware.org/?probe=16404d222a) | May 18, 2022 |
| Gateway       | NV55C                       | [82fcde80bb](https://linux-hardware.org/?probe=82fcde80bb) | May 18, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ecfb1c48d9](https://linux-hardware.org/?probe=ecfb1c48d9) | May 17, 2022 |
| Sony          | VGN-FW51MF_H                | [084402167e](https://linux-hardware.org/?probe=084402167e) | May 17, 2022 |
| ASUSTek       | ROG Strix G713IM_G713IM     | [eb1da20105](https://linux-hardware.org/?probe=eb1da20105) | May 17, 2022 |
| HP            | EliteBook 2570p             | [70ba6585e8](https://linux-hardware.org/?probe=70ba6585e8) | May 16, 2022 |
| Unknown       | Unknown                     | [bb968f8b83](https://linux-hardware.org/?probe=bb968f8b83) | May 16, 2022 |
| Dell          | Vostro 3500                 | [b95339f19d](https://linux-hardware.org/?probe=b95339f19d) | May 15, 2022 |
| ASUSTek       | GL552VW                     | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [ddadf86375](https://linux-hardware.org/?probe=ddadf86375) | May 15, 2022 |
| HP            | ProBook 450 G1              | [c9da66f0e8](https://linux-hardware.org/?probe=c9da66f0e8) | May 15, 2022 |
| Thomson       | NEO14SBK                    | [2ae5fbd212](https://linux-hardware.org/?probe=2ae5fbd212) | May 15, 2022 |
| ASUSTek       | N80Vb                       | [74cb7e076b](https://linux-hardware.org/?probe=74cb7e076b) | May 13, 2022 |
| Acer          | Aspire E1-522               | [21a4fc80c7](https://linux-hardware.org/?probe=21a4fc80c7) | May 13, 2022 |
| Alienware     | 17                          | [b9be04342c](https://linux-hardware.org/?probe=b9be04342c) | May 13, 2022 |
| HP            | OMEN by Laptop              | [f08cef4e3b](https://linux-hardware.org/?probe=f08cef4e3b) | May 13, 2022 |
| Lenovo        | ThinkPad T61 7661V72        | [3d40fb11e8](https://linux-hardware.org/?probe=3d40fb11e8) | May 13, 2022 |
| Toshiba       | Satellite C55-C             | [2695dd828d](https://linux-hardware.org/?probe=2695dd828d) | May 13, 2022 |
| Acer          | Aspire E1-522               | [77fdc036b0](https://linux-hardware.org/?probe=77fdc036b0) | May 13, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [048951833f](https://linux-hardware.org/?probe=048951833f) | May 13, 2022 |
| Dell          | Vostro 3500                 | [3824ac02d2](https://linux-hardware.org/?probe=3824ac02d2) | May 12, 2022 |
| Dell          | Latitude E6540              | [422c7a9209](https://linux-hardware.org/?probe=422c7a9209) | May 11, 2022 |
| Acer          | Aspire E1-571               | [72b102de04](https://linux-hardware.org/?probe=72b102de04) | May 10, 2022 |
| ASUSTek       | X200CA                      | [e041ed14b2](https://linux-hardware.org/?probe=e041ed14b2) | May 10, 2022 |
| Apple         | MacBookPro8,1               | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [81cd3de099](https://linux-hardware.org/?probe=81cd3de099) | May 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [a5deca63d5](https://linux-hardware.org/?probe=a5deca63d5) | May 09, 2022 |
| HP            | Laptop 15-db0xxx            | [42f2a531b5](https://linux-hardware.org/?probe=42f2a531b5) | May 09, 2022 |
| HP            | Pavilion Notebook           | [637a04a2d1](https://linux-hardware.org/?probe=637a04a2d1) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [911b8e4c5b](https://linux-hardware.org/?probe=911b8e4c5b) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8e43525285](https://linux-hardware.org/?probe=8e43525285) | May 09, 2022 |
| HP            | Pavilion dv7                | [709b7bc3e0](https://linux-hardware.org/?probe=709b7bc3e0) | May 09, 2022 |
| ASUSTek       | G74Sx                       | [0ed6635d41](https://linux-hardware.org/?probe=0ed6635d41) | May 09, 2022 |
| ASUSTek       | U43F                        | [ad1a88d120](https://linux-hardware.org/?probe=ad1a88d120) | May 08, 2022 |
| Lenovo        | IdeaPad Z580                | [a0751c16d5](https://linux-hardware.org/?probe=a0751c16d5) | May 08, 2022 |
| HP            | Compaq 6530b (WA484LA#AB... | [13cda8fea2](https://linux-hardware.org/?probe=13cda8fea2) | May 08, 2022 |
| ASUSTek       | X200CA                      | [bed44df427](https://linux-hardware.org/?probe=bed44df427) | May 07, 2022 |
| Acer          | Aspire F5-573               | [d6961632c4](https://linux-hardware.org/?probe=d6961632c4) | May 07, 2022 |
| ASUSTek       | G74Sx                       | [44f45ca8ea](https://linux-hardware.org/?probe=44f45ca8ea) | May 07, 2022 |
| Toshiba       | TECRA A50-E                 | [29935ac4c6](https://linux-hardware.org/?probe=29935ac4c6) | May 06, 2022 |
| Lenovo        | G500 20236                  | [8439c948ec](https://linux-hardware.org/?probe=8439c948ec) | May 06, 2022 |
| HP            | Compaq 6730s                | [d1902442d8](https://linux-hardware.org/?probe=d1902442d8) | May 06, 2022 |
| HP            | Compaq 6730s                | [2e53f00a60](https://linux-hardware.org/?probe=2e53f00a60) | May 06, 2022 |
| Google        | Candy                       | [d461281743](https://linux-hardware.org/?probe=d461281743) | May 04, 2022 |
| HP            | Notebook                    | [05f1b18534](https://linux-hardware.org/?probe=05f1b18534) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8aadfc9dc1](https://linux-hardware.org/?probe=8aadfc9dc1) | May 04, 2022 |
| Google        | Candy                       | [2c41b3e736](https://linux-hardware.org/?probe=2c41b3e736) | May 04, 2022 |
| ASUSTek       | E200HA                      | [399a40cb14](https://linux-hardware.org/?probe=399a40cb14) | May 03, 2022 |
| ASUSTek       | X550CL                      | [b224821361](https://linux-hardware.org/?probe=b224821361) | May 03, 2022 |
| HP            | Pavilion dv6                | [7587fe8761](https://linux-hardware.org/?probe=7587fe8761) | May 03, 2022 |
| HP            | Pavilion dv6                | [bf79099573](https://linux-hardware.org/?probe=bf79099573) | May 03, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [4e21e1d28e](https://linux-hardware.org/?probe=4e21e1d28e) | May 02, 2022 |
| ASUSTek       | X550CL                      | [5340c940c2](https://linux-hardware.org/?probe=5340c940c2) | May 02, 2022 |
| ASUSTek       | X756UQ                      | [130944084d](https://linux-hardware.org/?probe=130944084d) | May 01, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [317736e849](https://linux-hardware.org/?probe=317736e849) | May 01, 2022 |
| Lenovo        | Yoga 2 13 20344             | [ce528c379a](https://linux-hardware.org/?probe=ce528c379a) | May 01, 2022 |
| Acer          | Aspire V3-571               | [9cab38ff4f](https://linux-hardware.org/?probe=9cab38ff4f) | May 01, 2022 |
| Acer          | Aspire 5741                 | [f82c315ff4](https://linux-hardware.org/?probe=f82c315ff4) | May 01, 2022 |
| Acer          | V5-171                      | [a07ba20ff0](https://linux-hardware.org/?probe=a07ba20ff0) | Apr 30, 2022 |
| ASUSTek       | X756UQ                      | [2543d87831](https://linux-hardware.org/?probe=2543d87831) | Apr 30, 2022 |
| Toshiba       | Satellite C55-A-1J8         | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| Acer          | V5-171                      | [8500a1c376](https://linux-hardware.org/?probe=8500a1c376) | Apr 30, 2022 |
| ASUSTek       | X411UN                      | [c864c65ec1](https://linux-hardware.org/?probe=c864c65ec1) | Apr 29, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [c4021bd208](https://linux-hardware.org/?probe=c4021bd208) | Apr 29, 2022 |
| Toshiba       | Satellite Pro R50-B         | [6a8bdd387c](https://linux-hardware.org/?probe=6a8bdd387c) | Apr 29, 2022 |
| Toshiba       | Satellite C55-C             | [35e8d13a74](https://linux-hardware.org/?probe=35e8d13a74) | Apr 27, 2022 |
| Razer         | Blade                       | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| HP            | 15                          | [63e5782bc3](https://linux-hardware.org/?probe=63e5782bc3) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | [d48006a0b2](https://linux-hardware.org/?probe=d48006a0b2) | Apr 26, 2022 |
| Toshiba       | Satellite C55-C             | [e9bc1aaf05](https://linux-hardware.org/?probe=e9bc1aaf05) | Apr 26, 2022 |
| HP            | Compaq Presario CQ70        | [ebfb06702f](https://linux-hardware.org/?probe=ebfb06702f) | Apr 25, 2022 |
| Dell          | Inspiron 1525               | [47a349b8db](https://linux-hardware.org/?probe=47a349b8db) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | [982005a931](https://linux-hardware.org/?probe=982005a931) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | [8e0c841b78](https://linux-hardware.org/?probe=8e0c841b78) | Apr 25, 2022 |
| Toshiba       | Satellite A200              | [f940bea00c](https://linux-hardware.org/?probe=f940bea00c) | Apr 25, 2022 |
| Toshiba       | Satellite A200              | [b1594df62f](https://linux-hardware.org/?probe=b1594df62f) | Apr 25, 2022 |
| Packard Be... | EasyNote TS11HR             | [e1731ce27f](https://linux-hardware.org/?probe=e1731ce27f) | Apr 25, 2022 |
| Packard Be... | EasyNote TS11HR             | [a681022e30](https://linux-hardware.org/?probe=a681022e30) | Apr 25, 2022 |
| HP            | Laptop 15-db0xxx            | [127dd69ddf](https://linux-hardware.org/?probe=127dd69ddf) | Apr 25, 2022 |
| HP            | Notebook                    | [339f862ddd](https://linux-hardware.org/?probe=339f862ddd) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [c954cb4ba4](https://linux-hardware.org/?probe=c954cb4ba4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [ab88dc2482](https://linux-hardware.org/?probe=ab88dc2482) | Apr 24, 2022 |
| Dell          | Latitude 3440               | [a0c0358f78](https://linux-hardware.org/?probe=a0c0358f78) | Apr 24, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [9edf97b766](https://linux-hardware.org/?probe=9edf97b766) | Apr 24, 2022 |
| Samsung       | 550XCJ/550XCR               | [4f5bd4cb03](https://linux-hardware.org/?probe=4f5bd4cb03) | Apr 23, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [f57f07921b](https://linux-hardware.org/?probe=f57f07921b) | Apr 23, 2022 |
| ASUSTek       | X55A                        | [9188b40f88](https://linux-hardware.org/?probe=9188b40f88) | Apr 23, 2022 |
| ASUSTek       | X401A1                      | [883c933519](https://linux-hardware.org/?probe=883c933519) | Apr 23, 2022 |
| ASUSTek       | X401A1                      | [9b960298ef](https://linux-hardware.org/?probe=9b960298ef) | Apr 23, 2022 |
| Dell          | Latitude E5440              | [91744e20c7](https://linux-hardware.org/?probe=91744e20c7) | Apr 22, 2022 |
| Google        | Candy                       | [5a31bd1da8](https://linux-hardware.org/?probe=5a31bd1da8) | Apr 22, 2022 |
| Gateway       | NV59C                       | [c7f652c9f8](https://linux-hardware.org/?probe=c7f652c9f8) | Apr 21, 2022 |
| HP            | Laptop 15-bw0xx             | [b251d7f8e6](https://linux-hardware.org/?probe=b251d7f8e6) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4286A78       | [d5c9254caa](https://linux-hardware.org/?probe=d5c9254caa) | Apr 20, 2022 |
| HP            | Laptop 15s-du2xxx           | [fe39cbe3d1](https://linux-hardware.org/?probe=fe39cbe3d1) | Apr 20, 2022 |
| Acer          | Nitro AN515-44              | [5549666ce7](https://linux-hardware.org/?probe=5549666ce7) | Apr 20, 2022 |
| Lenovo        | Z40-70 20366                | [c77a5735b7](https://linux-hardware.org/?probe=c77a5735b7) | Apr 20, 2022 |
| HP            | Notebook                    | [f6d84934cd](https://linux-hardware.org/?probe=f6d84934cd) | Apr 19, 2022 |
| Dell          | Inspiron M5010              | [eff0448051](https://linux-hardware.org/?probe=eff0448051) | Apr 19, 2022 |
| Acer          | Aspire A515-54              | [c1a060dd90](https://linux-hardware.org/?probe=c1a060dd90) | Apr 19, 2022 |
| Toshiba       | Satellite C870-1C2          | [c8917c947b](https://linux-hardware.org/?probe=c8917c947b) | Apr 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [ab4247484f](https://linux-hardware.org/?probe=ab4247484f) | Apr 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [3bf424720c](https://linux-hardware.org/?probe=3bf424720c) | Apr 18, 2022 |
| ASUSTek       | K73BR                       | [596b3b2df6](https://linux-hardware.org/?probe=596b3b2df6) | Apr 18, 2022 |
| Acer          | Aspire V3-112P              | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | [7b1d2ec5a1](https://linux-hardware.org/?probe=7b1d2ec5a1) | Apr 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1825f45bfa](https://linux-hardware.org/?probe=1825f45bfa) | Apr 17, 2022 |
| Lenovo        | G40-80 80JE                 | [28c58e21e0](https://linux-hardware.org/?probe=28c58e21e0) | Apr 16, 2022 |
| Lenovo        | ThinkPad E520 11433BU       | [eb10b5f739](https://linux-hardware.org/?probe=eb10b5f739) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [7e7136d915](https://linux-hardware.org/?probe=7e7136d915) | Apr 16, 2022 |
| Dell          | Inspiron N5110              | [5ae4706be7](https://linux-hardware.org/?probe=5ae4706be7) | Apr 15, 2022 |
| Insignia      | NS-P89W6100 V1.0            | [dabc8a93a8](https://linux-hardware.org/?probe=dabc8a93a8) | Apr 15, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c1273dfd07](https://linux-hardware.org/?probe=c1273dfd07) | Apr 15, 2022 |
| Toshiba       | Satellite P50t-A            | [f2eef93c50](https://linux-hardware.org/?probe=f2eef93c50) | Apr 15, 2022 |
| Notebook      | NJ50_70CU                   | [1ec86958b8](https://linux-hardware.org/?probe=1ec86958b8) | Apr 15, 2022 |
| AMI           | Intel                       | [bfee32835f](https://linux-hardware.org/?probe=bfee32835f) | Apr 14, 2022 |
| AMI           | Intel                       | [b7c76035df](https://linux-hardware.org/?probe=b7c76035df) | Apr 14, 2022 |
| Fujitsu       | LIFEBOOK S760               | [6cb98b4c28](https://linux-hardware.org/?probe=6cb98b4c28) | Apr 12, 2022 |
| Toshiba       | Satellite E55-A             | [dc9e2fd729](https://linux-hardware.org/?probe=dc9e2fd729) | Apr 11, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [9a6b2ad9f9](https://linux-hardware.org/?probe=9a6b2ad9f9) | Apr 11, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [574edf3e3b](https://linux-hardware.org/?probe=574edf3e3b) | Apr 11, 2022 |
| Framework     | Laptop                      | [14cf383f81](https://linux-hardware.org/?probe=14cf383f81) | Apr 09, 2022 |
| Lenovo        | Flex 2-15 20405             | [b7d6ae3171](https://linux-hardware.org/?probe=b7d6ae3171) | Apr 08, 2022 |
| HP            | Pavilion Notebook           | [94a611644c](https://linux-hardware.org/?probe=94a611644c) | Apr 07, 2022 |
| HP            | ZBook 15 G3                 | [27bddd0a9c](https://linux-hardware.org/?probe=27bddd0a9c) | Apr 07, 2022 |
| Dell          | Latitude E6530              | [46bbc49e43](https://linux-hardware.org/?probe=46bbc49e43) | Apr 07, 2022 |
| Dell          | Studio 1749                 | [14d44c44fc](https://linux-hardware.org/?probe=14d44c44fc) | Apr 07, 2022 |
| Toshiba       | Satellite L755              | [be86a2f36e](https://linux-hardware.org/?probe=be86a2f36e) | Apr 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [0f8f2d9229](https://linux-hardware.org/?probe=0f8f2d9229) | Apr 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | [5cc1a973d7](https://linux-hardware.org/?probe=5cc1a973d7) | Apr 06, 2022 |
| HP            | ProBook 4530s               | [1b32584f41](https://linux-hardware.org/?probe=1b32584f41) | Apr 06, 2022 |
| HP            | ProBook 4530s               | [f4dfc894d9](https://linux-hardware.org/?probe=f4dfc894d9) | Apr 06, 2022 |
| Dell          | Inspiron 1545               | [af6989215e](https://linux-hardware.org/?probe=af6989215e) | Apr 06, 2022 |
| Multilaser    | PC121                       | [f93e89718f](https://linux-hardware.org/?probe=f93e89718f) | Apr 05, 2022 |
| Multilaser    | PC121                       | [31f2c02434](https://linux-hardware.org/?probe=31f2c02434) | Apr 05, 2022 |
| HP            | EliteBook 8760w             | [e3a9cdfd95](https://linux-hardware.org/?probe=e3a9cdfd95) | Apr 05, 2022 |
| Lenovo        | B590 37612LG                | [153a6c2343](https://linux-hardware.org/?probe=153a6c2343) | Apr 04, 2022 |
| Medion        | S6417 MD99651               | [2911120bc0](https://linux-hardware.org/?probe=2911120bc0) | Apr 04, 2022 |
| ASUSTek       | T100TA                      | [dbfc15621f](https://linux-hardware.org/?probe=dbfc15621f) | Apr 04, 2022 |
| Dell          | Inspiron 1545               | [8e5b3df957](https://linux-hardware.org/?probe=8e5b3df957) | Apr 03, 2022 |
| Dell          | Inspiron 3185               | [17c6187b71](https://linux-hardware.org/?probe=17c6187b71) | Apr 03, 2022 |
| Lenovo        | ThinkPad T430 23473B2       | [aa0ad3f513](https://linux-hardware.org/?probe=aa0ad3f513) | Apr 03, 2022 |
| Toshiba       | BDB                         | [985b6a2865](https://linux-hardware.org/?probe=985b6a2865) | Apr 03, 2022 |
| HP            | Notebook                    | [e1af57dc16](https://linux-hardware.org/?probe=e1af57dc16) | Apr 02, 2022 |
| Apple         | MacBookAir5,1               | [d8657defc8](https://linux-hardware.org/?probe=d8657defc8) | Apr 02, 2022 |
| HP            | 240 G3                      | [3e6387008c](https://linux-hardware.org/?probe=3e6387008c) | Apr 02, 2022 |
| HP            | Compaq 6730b (NN204ET#AB... | [4f09568c52](https://linux-hardware.org/?probe=4f09568c52) | Apr 01, 2022 |
| Dell          | Latitude E5430 non-vPro     | [b47f5b30db](https://linux-hardware.org/?probe=b47f5b30db) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [e81da10444](https://linux-hardware.org/?probe=e81da10444) | Apr 01, 2022 |
| HP            | 255 G8 Notebook PC          | [1b1917729b](https://linux-hardware.org/?probe=1b1917729b) | Apr 01, 2022 |
| HP            | Pavilion dv6000 (GA443UA... | [b9a90b57c8](https://linux-hardware.org/?probe=b9a90b57c8) | Apr 01, 2022 |
| ASUSTek       | K55A                        | [71137b6a1e](https://linux-hardware.org/?probe=71137b6a1e) | Apr 01, 2022 |
| ASUSTek       | X102BA                      | [78ecf202d2](https://linux-hardware.org/?probe=78ecf202d2) | Apr 01, 2022 |
| Acer          | Nitro AN515-51              | [61a7788bfa](https://linux-hardware.org/?probe=61a7788bfa) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d13496f68a](https://linux-hardware.org/?probe=d13496f68a) | Mar 31, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [19aa2cf50d](https://linux-hardware.org/?probe=19aa2cf50d) | Mar 31, 2022 |
| Dell          | Venue 8 Pro 5855            | [35a463a0fb](https://linux-hardware.org/?probe=35a463a0fb) | Mar 31, 2022 |
| Toshiba       | Satellite C660              | [60a6bafd86](https://linux-hardware.org/?probe=60a6bafd86) | Mar 30, 2022 |
| Acer          | Aspire ES1-572              | [bf6df72edf](https://linux-hardware.org/?probe=bf6df72edf) | Mar 29, 2022 |
| Notebook      | NJ50_70CU                   | [ba5b62756b](https://linux-hardware.org/?probe=ba5b62756b) | Mar 29, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [a6218b029c](https://linux-hardware.org/?probe=a6218b029c) | Mar 29, 2022 |
| HP            | Pavilion dv3                | [bd8d09108e](https://linux-hardware.org/?probe=bd8d09108e) | Mar 28, 2022 |
| Acer          | Nitro AN515-44              | [36681f4a2f](https://linux-hardware.org/?probe=36681f4a2f) | Mar 28, 2022 |
| ASUSTek       | T100TA                      | [fa6858ef16](https://linux-hardware.org/?probe=fa6858ef16) | Mar 28, 2022 |
| Dell          | Precision M4800             | [1eacfc1ab5](https://linux-hardware.org/?probe=1eacfc1ab5) | Mar 27, 2022 |
| Acer          | Predator G9-792             | [4720698441](https://linux-hardware.org/?probe=4720698441) | Mar 27, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [09cccd4869](https://linux-hardware.org/?probe=09cccd4869) | Mar 27, 2022 |
| Dell          | Inspiron M5030              | [7bc7e689a4](https://linux-hardware.org/?probe=7bc7e689a4) | Mar 26, 2022 |
| Insyde        | GeminiLake                  | [44967ed898](https://linux-hardware.org/?probe=44967ed898) | Mar 26, 2022 |
| HP            | ProBook 4530s               | [f4d3c7fddf](https://linux-hardware.org/?probe=f4d3c7fddf) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [09576b4897](https://linux-hardware.org/?probe=09576b4897) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [610b3ad535](https://linux-hardware.org/?probe=610b3ad535) | Mar 25, 2022 |
| Dell          | Latitude E5540              | [c743515039](https://linux-hardware.org/?probe=c743515039) | Mar 25, 2022 |
| Dell          | Latitude E5540              | [0059ee485d](https://linux-hardware.org/?probe=0059ee485d) | Mar 25, 2022 |
| Toshiba       | Satellite S55t-C            | [0bebc02627](https://linux-hardware.org/?probe=0bebc02627) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Lenovo        | ThinkPad SL500 274677G      | [1fcd4e44f1](https://linux-hardware.org/?probe=1fcd4e44f1) | Mar 25, 2022 |
| HP            | Laptop 15-bw0xx             | [eb140d5b4d](https://linux-hardware.org/?probe=eb140d5b4d) | Mar 25, 2022 |
| Sony          | SVT13125CLS                 | [5332da89c8](https://linux-hardware.org/?probe=5332da89c8) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | [4e75dbe2d2](https://linux-hardware.org/?probe=4e75dbe2d2) | Mar 23, 2022 |
| Positivo      | C14CU51                     | [1ca3c10e9b](https://linux-hardware.org/?probe=1ca3c10e9b) | Mar 23, 2022 |
| ASUSTek       | X405UA                      | [1895364071](https://linux-hardware.org/?probe=1895364071) | Mar 22, 2022 |
| Apple         | MacBookPro12,1              | [a39345cbf9](https://linux-hardware.org/?probe=a39345cbf9) | Mar 22, 2022 |
| Gateway       | NV59C                       | [ce722c3cc0](https://linux-hardware.org/?probe=ce722c3cc0) | Mar 22, 2022 |
| MSI           | CR643                       | [24e9c1fe40](https://linux-hardware.org/?probe=24e9c1fe40) | Mar 22, 2022 |
| ASUSTek       | G75VW                       | [202d109eb5](https://linux-hardware.org/?probe=202d109eb5) | Mar 22, 2022 |
| HP            | EliteBook 8540p             | [15a215fc17](https://linux-hardware.org/?probe=15a215fc17) | Mar 22, 2022 |
| HP            | EliteBook 8540p             | [f0915a2702](https://linux-hardware.org/?probe=f0915a2702) | Mar 22, 2022 |
| HP            | Laptop 15-db0xxx            | [e0f906e560](https://linux-hardware.org/?probe=e0f906e560) | Mar 21, 2022 |
| HP            | Pavilion g6                 | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| HP            | ENVY dv7                    | [b15a265c66](https://linux-hardware.org/?probe=b15a265c66) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a3859ab679](https://linux-hardware.org/?probe=a3859ab679) | Mar 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9323d5d425](https://linux-hardware.org/?probe=9323d5d425) | Mar 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a2f09086d6](https://linux-hardware.org/?probe=a2f09086d6) | Mar 19, 2022 |
| HP            | Pavilion Notebook           | [02e461a122](https://linux-hardware.org/?probe=02e461a122) | Mar 19, 2022 |
| HP            | Pavilion dv3                | [3dbd970796](https://linux-hardware.org/?probe=3dbd970796) | Mar 19, 2022 |
| Apple         | MacBookPro10,1              | [6da9c9f35d](https://linux-hardware.org/?probe=6da9c9f35d) | Mar 19, 2022 |
| Dell          | Inspiron 5770               | [77492abdcf](https://linux-hardware.org/?probe=77492abdcf) | Mar 19, 2022 |
| Lenovo        | ThinkPad T520 424067G       | [3e6c1f772d](https://linux-hardware.org/?probe=3e6c1f772d) | Mar 18, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3603330b59](https://linux-hardware.org/?probe=3603330b59) | Mar 18, 2022 |
| ASUSTek       | ZenBook UX433FN_U4300FN     | [0228881558](https://linux-hardware.org/?probe=0228881558) | Mar 18, 2022 |
| Dell          | Vostro 1500                 | [b2d732d46b](https://linux-hardware.org/?probe=b2d732d46b) | Mar 18, 2022 |
| Dell          | Vostro 1500                 | [6dbcdd388c](https://linux-hardware.org/?probe=6dbcdd388c) | Mar 18, 2022 |
| Dell          | Inspiron 7737               | [99852ed093](https://linux-hardware.org/?probe=99852ed093) | Mar 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [c3ffdf7791](https://linux-hardware.org/?probe=c3ffdf7791) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [77b0be92c8](https://linux-hardware.org/?probe=77b0be92c8) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [47a984d336](https://linux-hardware.org/?probe=47a984d336) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [662aed3d5d](https://linux-hardware.org/?probe=662aed3d5d) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [b3fc1a1d0f](https://linux-hardware.org/?probe=b3fc1a1d0f) | Mar 17, 2022 |
| Dell          | Latitude E4200              | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| HP            | ProBook 450 G2              | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |
| Toshiba       | Satellite C855              | [71d2d562d7](https://linux-hardware.org/?probe=71d2d562d7) | Mar 16, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [9aa148dba8](https://linux-hardware.org/?probe=9aa148dba8) | Mar 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [116bb6c003](https://linux-hardware.org/?probe=116bb6c003) | Mar 15, 2022 |
| Sony          | VGN-FW21E                   | [1dbc74cf43](https://linux-hardware.org/?probe=1dbc74cf43) | Mar 15, 2022 |
| Insyde        | i101c                       | [1d1171c005](https://linux-hardware.org/?probe=1d1171c005) | Mar 15, 2022 |
| Gigabyte      | P64V7                       | [13f2e44186](https://linux-hardware.org/?probe=13f2e44186) | Mar 15, 2022 |
| Toshiba       | Satellite C55-C             | [8fade33706](https://linux-hardware.org/?probe=8fade33706) | Mar 15, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [0755c3c4a6](https://linux-hardware.org/?probe=0755c3c4a6) | Mar 14, 2022 |
| Acer          | Aspire E5-571P              | [dd68b81b43](https://linux-hardware.org/?probe=dd68b81b43) | Mar 14, 2022 |
| Acer          | Aspire SW3-016              | [6988255f00](https://linux-hardware.org/?probe=6988255f00) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z580                | [b5a56fb84b](https://linux-hardware.org/?probe=b5a56fb84b) | Mar 14, 2022 |
| ASUSTek       | X550LC                      | [cb90a1c509](https://linux-hardware.org/?probe=cb90a1c509) | Mar 13, 2022 |
| Lenovo        | IdeaPad 320S-15IKB 81BQ     | [088d2bf23b](https://linux-hardware.org/?probe=088d2bf23b) | Mar 13, 2022 |
| HP            | Notebook                    | [2a7e60663b](https://linux-hardware.org/?probe=2a7e60663b) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| HP            | Laptop 14-ck0xxx            | [92c7141f37](https://linux-hardware.org/?probe=92c7141f37) | Mar 12, 2022 |
| HP            | 1000                        | [c43fd3bfa5](https://linux-hardware.org/?probe=c43fd3bfa5) | Mar 11, 2022 |
| Lenovo        | V110-15IAP 80TG             | [5989c71041](https://linux-hardware.org/?probe=5989c71041) | Mar 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [14237b32d9](https://linux-hardware.org/?probe=14237b32d9) | Mar 11, 2022 |
| Dell          | Inspiron 5520               | [5d8f77310a](https://linux-hardware.org/?probe=5d8f77310a) | Mar 11, 2022 |
| Chuwi         | HeroBook Air                | [674a4fbede](https://linux-hardware.org/?probe=674a4fbede) | Mar 10, 2022 |
| HP            | 15 Notebook PC              | [8714d12640](https://linux-hardware.org/?probe=8714d12640) | Mar 09, 2022 |
| HP            | Laptop 14-dq2xxx            | [cb5d9880c6](https://linux-hardware.org/?probe=cb5d9880c6) | Mar 09, 2022 |
| Packard Be... | EasyNote LS11HR             | [7a99940861](https://linux-hardware.org/?probe=7a99940861) | Mar 08, 2022 |
| Dell          | Inspiron 13-7378            | [6c40e8cf0f](https://linux-hardware.org/?probe=6c40e8cf0f) | Mar 08, 2022 |
| Dell          | Vostro 3550                 | [25951f4351](https://linux-hardware.org/?probe=25951f4351) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8a4f961472](https://linux-hardware.org/?probe=8a4f961472) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4d33fc28da](https://linux-hardware.org/?probe=4d33fc28da) | Mar 08, 2022 |
| Toshiba       | Satellite L875              | [ad99a6a57b](https://linux-hardware.org/?probe=ad99a6a57b) | Mar 07, 2022 |
| Acer          | TP-W700-53334G12            | [61d5d1483d](https://linux-hardware.org/?probe=61d5d1483d) | Mar 07, 2022 |
| HP            | ProBook 640 G1              | [bf9c067da8](https://linux-hardware.org/?probe=bf9c067da8) | Mar 07, 2022 |
| Toshiba       | Satellite L875              | [a5487c84f8](https://linux-hardware.org/?probe=a5487c84f8) | Mar 07, 2022 |
| HP            | Notebook                    | [a15666c682](https://linux-hardware.org/?probe=a15666c682) | Mar 07, 2022 |
| HP            | Notebook                    | [85eb96edd4](https://linux-hardware.org/?probe=85eb96edd4) | Mar 07, 2022 |
| ASUSTek       | X550LC                      | [97f4cf8c40](https://linux-hardware.org/?probe=97f4cf8c40) | Mar 06, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [6e8e3f12d0](https://linux-hardware.org/?probe=6e8e3f12d0) | Mar 06, 2022 |
| AXDIA Inte... | WINBOOK 13                  | [6cf2cc07ed](https://linux-hardware.org/?probe=6cf2cc07ed) | Mar 06, 2022 |
| Toshiba       | Satellite C855              | [6911de7c71](https://linux-hardware.org/?probe=6911de7c71) | Mar 05, 2022 |
| Acer          | TP-W700-53334G12            | [cf6bad7b5c](https://linux-hardware.org/?probe=cf6bad7b5c) | Mar 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [14fc889e5f](https://linux-hardware.org/?probe=14fc889e5f) | Mar 05, 2022 |
| Dell          | Precision M6700             | [c5cb8cd111](https://linux-hardware.org/?probe=c5cb8cd111) | Mar 05, 2022 |
| Dell          | Latitude E5500              | [0f590ac9e5](https://linux-hardware.org/?probe=0f590ac9e5) | Mar 05, 2022 |
| Toshiba       | Satellite A660              | [1a6607437d](https://linux-hardware.org/?probe=1a6607437d) | Mar 04, 2022 |
| Toshiba       | Satellite A660              | [584c89737c](https://linux-hardware.org/?probe=584c89737c) | Mar 04, 2022 |
| HP            | ProBook 4720s               | [631600dd74](https://linux-hardware.org/?probe=631600dd74) | Mar 04, 2022 |
| ASUSTek       | T100TA                      | [485c2b3aa7](https://linux-hardware.org/?probe=485c2b3aa7) | Mar 04, 2022 |
| HP            | Pavilion dv7                | [db550138fb](https://linux-hardware.org/?probe=db550138fb) | Mar 03, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d09a669d80](https://linux-hardware.org/?probe=d09a669d80) | Mar 03, 2022 |
| Acer          | V5-171                      | [8c620eae72](https://linux-hardware.org/?probe=8c620eae72) | Mar 03, 2022 |
| Lenovo        | G560 0679                   | [07bbbdef41](https://linux-hardware.org/?probe=07bbbdef41) | Mar 03, 2022 |
| HP            | ProBook 4720s               | [8afd2b3c97](https://linux-hardware.org/?probe=8afd2b3c97) | Mar 03, 2022 |
| HP            | ProBook 640 G1              | [6acfc75347](https://linux-hardware.org/?probe=6acfc75347) | Mar 03, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82C5     | [d4b6e7276e](https://linux-hardware.org/?probe=d4b6e7276e) | Mar 03, 2022 |
| Lenovo        | HuronRiver Platform         | [a34efebccf](https://linux-hardware.org/?probe=a34efebccf) | Mar 02, 2022 |
| HP            | Compaq 6730b (NN204ET#AB... | [f20f8759b1](https://linux-hardware.org/?probe=f20f8759b1) | Mar 02, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [fb9f8e44d0](https://linux-hardware.org/?probe=fb9f8e44d0) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [46271114d7](https://linux-hardware.org/?probe=46271114d7) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [1df5245912](https://linux-hardware.org/?probe=1df5245912) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [bd438d0f08](https://linux-hardware.org/?probe=bd438d0f08) | Mar 01, 2022 |
| Dell          | Latitude 3550               | [5b0d9e3d13](https://linux-hardware.org/?probe=5b0d9e3d13) | Feb 28, 2022 |
| Dell          | G5 5590                     | [f553433011](https://linux-hardware.org/?probe=f553433011) | Feb 27, 2022 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [f67c401f47](https://linux-hardware.org/?probe=f67c401f47) | Feb 27, 2022 |
| Acer          | Swift SF114-34              | [49fb58c88b](https://linux-hardware.org/?probe=49fb58c88b) | Feb 27, 2022 |
| Dell          | Latitude E5500              | [c84caad5a2](https://linux-hardware.org/?probe=c84caad5a2) | Feb 26, 2022 |
| Dell          | Latitude E5500              | [38a51b4721](https://linux-hardware.org/?probe=38a51b4721) | Feb 26, 2022 |
| HP            | 630                         | [6bf505d86b](https://linux-hardware.org/?probe=6bf505d86b) | Feb 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [359368d345](https://linux-hardware.org/?probe=359368d345) | Feb 26, 2022 |
| HP            | EliteBook 840 G6            | [fabf12f128](https://linux-hardware.org/?probe=fabf12f128) | Feb 26, 2022 |
| Dell          | Inspiron 5448               | [2458e07e0d](https://linux-hardware.org/?probe=2458e07e0d) | Feb 25, 2022 |
| Lenovo        | G40-80 80JE                 | [c55ba8cab2](https://linux-hardware.org/?probe=c55ba8cab2) | Feb 25, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [b1354ad7df](https://linux-hardware.org/?probe=b1354ad7df) | Feb 24, 2022 |
| Toshiba       | Satellite C55-B             | [ae66a9051d](https://linux-hardware.org/?probe=ae66a9051d) | Feb 24, 2022 |
| Packard Be... | DOT S                       | [e90543b727](https://linux-hardware.org/?probe=e90543b727) | Feb 24, 2022 |
| Fujitsu       | LIFEBOOK AH512              | [d7889a52d1](https://linux-hardware.org/?probe=d7889a52d1) | Feb 24, 2022 |
| HP            | Stream Laptop 11-ah0XX      | [e224468100](https://linux-hardware.org/?probe=e224468100) | Feb 23, 2022 |
| HP            | Pavilion g6                 | [1c1f4685eb](https://linux-hardware.org/?probe=1c1f4685eb) | Feb 22, 2022 |
| Dell          | XPS 15 9510                 | [6c5203e00a](https://linux-hardware.org/?probe=6c5203e00a) | Feb 22, 2022 |
| Acer          | V5-171                      | [2ef877834d](https://linux-hardware.org/?probe=2ef877834d) | Feb 22, 2022 |
| Gigabyte      | P64V7                       | [fdac76c228](https://linux-hardware.org/?probe=fdac76c228) | Feb 22, 2022 |
| Toshiba       | Satellite S55t-C            | [45b90ca745](https://linux-hardware.org/?probe=45b90ca745) | Feb 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [85c2284ffa](https://linux-hardware.org/?probe=85c2284ffa) | Feb 21, 2022 |
| Multilaser    | PC130                       | [4a49294d21](https://linux-hardware.org/?probe=4a49294d21) | Feb 20, 2022 |
| Multilaser    | PC130                       | [4681b7ae9e](https://linux-hardware.org/?probe=4681b7ae9e) | Feb 20, 2022 |
| Dell          | Studio 1555                 | [19d02a6eb8](https://linux-hardware.org/?probe=19d02a6eb8) | Feb 20, 2022 |
| Dell          | Precision M4800             | [9734390386](https://linux-hardware.org/?probe=9734390386) | Feb 19, 2022 |
| GEO           | GeoBook 120                 | [3eeed29e23](https://linux-hardware.org/?probe=3eeed29e23) | Feb 19, 2022 |
| GEO           | GeoBook 120                 | [5c26a23921](https://linux-hardware.org/?probe=5c26a23921) | Feb 19, 2022 |
| Google        | Akemi                       | [fc9b479395](https://linux-hardware.org/?probe=fc9b479395) | Feb 19, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4425c178f2](https://linux-hardware.org/?probe=4425c178f2) | Feb 19, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| Lenovo        | ThinkPad T61 7658CTO        | [99465a8eb3](https://linux-hardware.org/?probe=99465a8eb3) | Feb 19, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [aad26f0aa8](https://linux-hardware.org/?probe=aad26f0aa8) | Feb 19, 2022 |
| ASUSTek       | X555LAB                     | [413a122ef8](https://linux-hardware.org/?probe=413a122ef8) | Feb 19, 2022 |
| Lenovo        | ThinkPad T440 20B7008ABR    | [b690de8548](https://linux-hardware.org/?probe=b690de8548) | Feb 19, 2022 |
| Dell          | Inspiron MM061              | [bc37eeb385](https://linux-hardware.org/?probe=bc37eeb385) | Feb 19, 2022 |
| Dell          | Inspiron MM061              | [e5dd39a008](https://linux-hardware.org/?probe=e5dd39a008) | Feb 18, 2022 |
| Gigabyte      | P64V7                       | [646aa28c13](https://linux-hardware.org/?probe=646aa28c13) | Feb 18, 2022 |
| Dell          | Latitude 5179               | [b28766add3](https://linux-hardware.org/?probe=b28766add3) | Feb 18, 2022 |
| HP            | 255 G2                      | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| HP            | OMEN Notebook               | [a952f9c2f2](https://linux-hardware.org/?probe=a952f9c2f2) | Feb 17, 2022 |
| ASUSTek       | ZenBook UX334FL_UX334FL     | [89c2a0f939](https://linux-hardware.org/?probe=89c2a0f939) | Feb 17, 2022 |
| Lenovo        | ThinkPad Edge E530 32599... | [d6fafc8b8b](https://linux-hardware.org/?probe=d6fafc8b8b) | Feb 17, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [59f1a1a3e0](https://linux-hardware.org/?probe=59f1a1a3e0) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a62793c371](https://linux-hardware.org/?probe=a62793c371) | Feb 16, 2022 |
| Packard Be... | EasyNote TK85               | [9abcb12076](https://linux-hardware.org/?probe=9abcb12076) | Feb 16, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [311429d9ef](https://linux-hardware.org/?probe=311429d9ef) | Feb 16, 2022 |
| Dell          | Vostro 1700                 | [efaa6a2512](https://linux-hardware.org/?probe=efaa6a2512) | Feb 16, 2022 |
| HP            | Pavilion dv6500             | [70b0938bc3](https://linux-hardware.org/?probe=70b0938bc3) | Feb 15, 2022 |
| HP            | Pavilion dv6500             | [918d93ea7a](https://linux-hardware.org/?probe=918d93ea7a) | Feb 15, 2022 |
| Acer          | E1-510                      | [0120aaf250](https://linux-hardware.org/?probe=0120aaf250) | Feb 15, 2022 |
| Acer          | E1-510                      | [7a3678f7d1](https://linux-hardware.org/?probe=7a3678f7d1) | Feb 15, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [8306c2af49](https://linux-hardware.org/?probe=8306c2af49) | Feb 15, 2022 |
| Dell          | Vostro 1500                 | [1780b4d18b](https://linux-hardware.org/?probe=1780b4d18b) | Feb 14, 2022 |
| Toshiba       | QOSMIO X70-A                | [c3c921f8e2](https://linux-hardware.org/?probe=c3c921f8e2) | Feb 14, 2022 |
| Lenovo        | ThinkPad T420 4178A47       | [cda9da09dc](https://linux-hardware.org/?probe=cda9da09dc) | Feb 14, 2022 |
| E-shop.gr     | V113                        | [e9a1ae2e96](https://linux-hardware.org/?probe=e9a1ae2e96) | Feb 14, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | [0412384bc2](https://linux-hardware.org/?probe=0412384bc2) | Feb 13, 2022 |
| HP            | Unknown                     | [2f4edd8b04](https://linux-hardware.org/?probe=2f4edd8b04) | Feb 13, 2022 |
| HP            | Unknown                     | [1284e8c58f](https://linux-hardware.org/?probe=1284e8c58f) | Feb 13, 2022 |
| Toshiba       | Satellite C50-A283          | [66f810c5f5](https://linux-hardware.org/?probe=66f810c5f5) | Feb 13, 2022 |
| E-shop.gr     | V113                        | [6d015f399b](https://linux-hardware.org/?probe=6d015f399b) | Feb 12, 2022 |
| Lenovo        | Flex 2-15 20405             | [7ae6513197](https://linux-hardware.org/?probe=7ae6513197) | Feb 12, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [bd8bfe9447](https://linux-hardware.org/?probe=bd8bfe9447) | Feb 12, 2022 |
| Sony          | VGN-Z575FN                  | [4998f7ae6d](https://linux-hardware.org/?probe=4998f7ae6d) | Feb 11, 2022 |
| HP            | ProBook 4525s               | [2db6879863](https://linux-hardware.org/?probe=2db6879863) | Feb 11, 2022 |
| HP            | ProBook 450 G5              | [804f3b74e0](https://linux-hardware.org/?probe=804f3b74e0) | Feb 10, 2022 |
| HP            | ProBook 450 G5              | [9e1c3acaf3](https://linux-hardware.org/?probe=9e1c3acaf3) | Feb 10, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [3dffdcc5d3](https://linux-hardware.org/?probe=3dffdcc5d3) | Feb 09, 2022 |
| HP            | 550                         | [7e286dd830](https://linux-hardware.org/?probe=7e286dd830) | Feb 08, 2022 |
| Samsung       | 600B4B/600B5B               | [2558403513](https://linux-hardware.org/?probe=2558403513) | Feb 08, 2022 |
| Samsung       | 600B4B/600B5B               | [f37984fec2](https://linux-hardware.org/?probe=f37984fec2) | Feb 08, 2022 |
| Apple         | MacBookPro11,1              | [8233b1191c](https://linux-hardware.org/?probe=8233b1191c) | Feb 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Dell          | Inspiron N5010              | [d14b339c4f](https://linux-hardware.org/?probe=d14b339c4f) | Feb 07, 2022 |
| ASUSTek       | T101HA                      | [3ec67a3424](https://linux-hardware.org/?probe=3ec67a3424) | Feb 06, 2022 |
| Dell          | Vostro 1700                 | [56ab8ae4cc](https://linux-hardware.org/?probe=56ab8ae4cc) | Feb 06, 2022 |
| Lenovo        | G40-80 80JE                 | [dd6e3f3a64](https://linux-hardware.org/?probe=dd6e3f3a64) | Feb 06, 2022 |
| HP            | 635                         | [3f689c9c23](https://linux-hardware.org/?probe=3f689c9c23) | Feb 06, 2022 |
| Unknown       | Unknown                     | [7848918b1d](https://linux-hardware.org/?probe=7848918b1d) | Feb 05, 2022 |
| ASUSTek       | ROG Strix G513QR            | [f562940afa](https://linux-hardware.org/?probe=f562940afa) | Feb 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [25fa8ea018](https://linux-hardware.org/?probe=25fa8ea018) | Feb 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [4b20e9f979](https://linux-hardware.org/?probe=4b20e9f979) | Feb 04, 2022 |
| HP            | ProBook 445 G7              | [3f45fd6cf2](https://linux-hardware.org/?probe=3f45fd6cf2) | Feb 03, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [71b93f7b57](https://linux-hardware.org/?probe=71b93f7b57) | Feb 03, 2022 |
| Novatech      | 15.6 nSpire Laptop          | [6fe78d2f4b](https://linux-hardware.org/?probe=6fe78d2f4b) | Feb 02, 2022 |
| HP            | ProBook 4310s               | [6d2a66aa1e](https://linux-hardware.org/?probe=6d2a66aa1e) | Feb 02, 2022 |
| Lenovo        | G710 20252                  | [5683d776e0](https://linux-hardware.org/?probe=5683d776e0) | Feb 02, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e14121100b](https://linux-hardware.org/?probe=e14121100b) | Feb 02, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | [ae25a7a57d](https://linux-hardware.org/?probe=ae25a7a57d) | Feb 02, 2022 |
| Dell          | Inspiron 5748               | [07c8076d3e](https://linux-hardware.org/?probe=07c8076d3e) | Feb 01, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [3e6d5943dd](https://linux-hardware.org/?probe=3e6d5943dd) | Feb 01, 2022 |
| HP            | Pavilion Laptop 15z-eh00... | [76a973d25c](https://linux-hardware.org/?probe=76a973d25c) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | [70e86eb89a](https://linux-hardware.org/?probe=70e86eb89a) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | [cf01ca64c3](https://linux-hardware.org/?probe=cf01ca64c3) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | [17015b4fbe](https://linux-hardware.org/?probe=17015b4fbe) | Jan 30, 2022 |
| Dell          | Latitude E5420              | [89a74ff338](https://linux-hardware.org/?probe=89a74ff338) | Jan 29, 2022 |
| HP            | Pavilion dv7                | [504e2036d3](https://linux-hardware.org/?probe=504e2036d3) | Jan 29, 2022 |
| Dell          | Latitude E6220              | [808db5a1c8](https://linux-hardware.org/?probe=808db5a1c8) | Jan 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [95423d6649](https://linux-hardware.org/?probe=95423d6649) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | [ccc3361d04](https://linux-hardware.org/?probe=ccc3361d04) | Jan 28, 2022 |
| Apple         | MacBookPro6,2               | [0143cbef50](https://linux-hardware.org/?probe=0143cbef50) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | [6b9b9f727e](https://linux-hardware.org/?probe=6b9b9f727e) | Jan 28, 2022 |
| Jumper        | EZbook                      | [4fa449c0ce](https://linux-hardware.org/?probe=4fa449c0ce) | Jan 27, 2022 |
| Acer          | Aspire 5552                 | [ef57c29f8c](https://linux-hardware.org/?probe=ef57c29f8c) | Jan 27, 2022 |
| HP            | Pavilion dv7                | [927e580b5a](https://linux-hardware.org/?probe=927e580b5a) | Jan 26, 2022 |
| ASUSTek       | ROG Strix G513QR            | [fb81914651](https://linux-hardware.org/?probe=fb81914651) | Jan 26, 2022 |
| Lenovo        | ThinkPad X61 7673C44        | [ab461bd99e](https://linux-hardware.org/?probe=ab461bd99e) | Jan 26, 2022 |
| HP            | Pavilion dv7                | [c639bc4c98](https://linux-hardware.org/?probe=c639bc4c98) | Jan 25, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [7078a1a373](https://linux-hardware.org/?probe=7078a1a373) | Jan 25, 2022 |
| Acer          | Aspire V3-571               | [ed5c6cf88d](https://linux-hardware.org/?probe=ed5c6cf88d) | Jan 24, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Toshiba       | Satellite C660              | [b3aec22953](https://linux-hardware.org/?probe=b3aec22953) | Jan 24, 2022 |
| ASUSTek       | ROG Strix G513QR            | [a31fd268eb](https://linux-hardware.org/?probe=a31fd268eb) | Jan 24, 2022 |
| ASUSTek       | X550CC                      | [5fa0a123f4](https://linux-hardware.org/?probe=5fa0a123f4) | Jan 24, 2022 |
| Dell          | Latitude E6420              | [1cf74dd114](https://linux-hardware.org/?probe=1cf74dd114) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [06eb5b9d8d](https://linux-hardware.org/?probe=06eb5b9d8d) | Jan 23, 2022 |
| Toshiba       | TECRA A9                    | [7ba32a721d](https://linux-hardware.org/?probe=7ba32a721d) | Jan 23, 2022 |
| Acer          | NC-E1-572-54208G            | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| Clevo         | W24/250CU                   | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| ASUSTek       | T100TAS                     | [a37b7c51fd](https://linux-hardware.org/?probe=a37b7c51fd) | Jan 22, 2022 |
| HP            | Laptop 14q-cs0xxx           | [ec9061dcb1](https://linux-hardware.org/?probe=ec9061dcb1) | Jan 22, 2022 |
| Lenovo        | G780 20138                  | [4b5e81151e](https://linux-hardware.org/?probe=4b5e81151e) | Jan 22, 2022 |
| ASUSTek       | E200HA                      | [0d0222d2e9](https://linux-hardware.org/?probe=0d0222d2e9) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4c95ae549f](https://linux-hardware.org/?probe=4c95ae549f) | Jan 21, 2022 |
| Dell          | Latitude E5470              | [df22d71530](https://linux-hardware.org/?probe=df22d71530) | Jan 21, 2022 |
| HP            | EliteBook 820 G3            | [81cbc7d48a](https://linux-hardware.org/?probe=81cbc7d48a) | Jan 21, 2022 |
| HP            | EliteBook 820 G3            | [c56fbf1529](https://linux-hardware.org/?probe=c56fbf1529) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c996d7e988](https://linux-hardware.org/?probe=c996d7e988) | Jan 20, 2022 |
| HP            | Notebook                    | [25a9e6d8a1](https://linux-hardware.org/?probe=25a9e6d8a1) | Jan 20, 2022 |
| ASUSTek       | X540YA                      | [99ff6cb58a](https://linux-hardware.org/?probe=99ff6cb58a) | Jan 20, 2022 |
| Acer          | Aspire V5-571PG             | [19c732cd05](https://linux-hardware.org/?probe=19c732cd05) | Jan 20, 2022 |
| Multilaser    | UB32X                       | [bd6f4152df](https://linux-hardware.org/?probe=bd6f4152df) | Jan 20, 2022 |
| ASUSTek       | GL552VW                     | [4544642750](https://linux-hardware.org/?probe=4544642750) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [81be3d94a3](https://linux-hardware.org/?probe=81be3d94a3) | Jan 18, 2022 |
| Acer          | Aspire ES1-531              | [d089029f6c](https://linux-hardware.org/?probe=d089029f6c) | Jan 18, 2022 |
| ASUSTek       | K93SV                       | [30f5830a2d](https://linux-hardware.org/?probe=30f5830a2d) | Jan 18, 2022 |
| ASUSTek       | T100TAS                     | [86df8cdba1](https://linux-hardware.org/?probe=86df8cdba1) | Jan 18, 2022 |
| HP            | 15                          | [4dde4c5c0e](https://linux-hardware.org/?probe=4dde4c5c0e) | Jan 17, 2022 |
| Google        | Ultima                      | [d942b9081b](https://linux-hardware.org/?probe=d942b9081b) | Jan 16, 2022 |
| HP            | 250 G4                      | [4de0cf1eb0](https://linux-hardware.org/?probe=4de0cf1eb0) | Jan 16, 2022 |
| Lenovo        | ThinkPad T460s 20FAS09Y0... | [339ea299c8](https://linux-hardware.org/?probe=339ea299c8) | Jan 16, 2022 |
| Acer          | Aspire A315-53              | [4bcdec655f](https://linux-hardware.org/?probe=4bcdec655f) | Jan 16, 2022 |
| Lenovo        | ThinkPad X230 2325WR3       | [decbecce89](https://linux-hardware.org/?probe=decbecce89) | Jan 16, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [7136b51cd1](https://linux-hardware.org/?probe=7136b51cd1) | Jan 15, 2022 |
| Acer          | Aspire 5552                 | [5d3b462042](https://linux-hardware.org/?probe=5d3b462042) | Jan 14, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| ASUSTek       | K52JT                       | [8545fedf93](https://linux-hardware.org/?probe=8545fedf93) | Jan 14, 2022 |
| ASUSTek       | X550CC                      | [0607e7f57e](https://linux-hardware.org/?probe=0607e7f57e) | Jan 14, 2022 |
| HP            | ProBook 640 G1              | [6261e290d6](https://linux-hardware.org/?probe=6261e290d6) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | [edb752adea](https://linux-hardware.org/?probe=edb752adea) | Jan 13, 2022 |
| ASUSTek       | K54C                        | [048477ec85](https://linux-hardware.org/?probe=048477ec85) | Jan 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [b694d6fa5f](https://linux-hardware.org/?probe=b694d6fa5f) | Jan 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [0f2222fc06](https://linux-hardware.org/?probe=0f2222fc06) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | [eb7e68d366](https://linux-hardware.org/?probe=eb7e68d366) | Jan 13, 2022 |
| Razer         | Blade Stealth               | [3e3430ddeb](https://linux-hardware.org/?probe=3e3430ddeb) | Jan 13, 2022 |
| Acer          | Aspire E5-774G              | [bd6fa29ee0](https://linux-hardware.org/?probe=bd6fa29ee0) | Jan 13, 2022 |
| Toshiba       | Satellite C660              | [a4b1346944](https://linux-hardware.org/?probe=a4b1346944) | Jan 13, 2022 |
| Mediacom      | GTZS                        | [ad6de0b39b](https://linux-hardware.org/?probe=ad6de0b39b) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [086b27dc7a](https://linux-hardware.org/?probe=086b27dc7a) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [c16f448f2e](https://linux-hardware.org/?probe=c16f448f2e) | Jan 12, 2022 |
| HP            | Pavilion g6                 | [e14f742bb9](https://linux-hardware.org/?probe=e14f742bb9) | Jan 12, 2022 |
| HP            | Pavilion g6                 | [62f049acf1](https://linux-hardware.org/?probe=62f049acf1) | Jan 12, 2022 |
| ASUSTek       | X542BA                      | [d5180ebfbc](https://linux-hardware.org/?probe=d5180ebfbc) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| Acer          | Predator G9-792             | [908edac358](https://linux-hardware.org/?probe=908edac358) | Jan 11, 2022 |
| Dell          | Vostro 1500                 | [d81572b40f](https://linux-hardware.org/?probe=d81572b40f) | Jan 11, 2022 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [4013d5dc28](https://linux-hardware.org/?probe=4013d5dc28) | Jan 11, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [3cd5068430](https://linux-hardware.org/?probe=3cd5068430) | Jan 10, 2022 |
| HP            | ProBook 6450b               | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Lenovo        | V14-IIL 82C4                | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| Dell          | Latitude E6510              | [df2d1f8aa1](https://linux-hardware.org/?probe=df2d1f8aa1) | Jan 09, 2022 |
| HP            | Pavilion 15                 | [95f3d87b66](https://linux-hardware.org/?probe=95f3d87b66) | Jan 09, 2022 |
| HP            | Compaq 8510p                | [94c5350957](https://linux-hardware.org/?probe=94c5350957) | Jan 09, 2022 |
| ASUSTek       | K52JT                       | [c5d880e138](https://linux-hardware.org/?probe=c5d880e138) | Jan 09, 2022 |
| Unknown       | SCHNEIDER                   | [03b1f6dfed](https://linux-hardware.org/?probe=03b1f6dfed) | Jan 09, 2022 |
| ASUSTek       | GL552VW                     | [69a4959007](https://linux-hardware.org/?probe=69a4959007) | Jan 09, 2022 |
| ASUSTek       | X553MA                      | [cdf5230fdb](https://linux-hardware.org/?probe=cdf5230fdb) | Jan 09, 2022 |
| Samsung       | R59P/R60P/R61P              | [dd061ae267](https://linux-hardware.org/?probe=dd061ae267) | Jan 08, 2022 |
| HP            | Laptop 15s-du2xxx           | [e6c704567e](https://linux-hardware.org/?probe=e6c704567e) | Jan 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [95c067b96e](https://linux-hardware.org/?probe=95c067b96e) | Jan 07, 2022 |
| MSI           | GE75 Raider 8SF             | [23aab4b14f](https://linux-hardware.org/?probe=23aab4b14f) | Jan 06, 2022 |
| ASUSTek       | X542BP                      | [1f13c19485](https://linux-hardware.org/?probe=1f13c19485) | Jan 06, 2022 |
| Toshiba       | Satellite A200              | [613096a5ad](https://linux-hardware.org/?probe=613096a5ad) | Jan 06, 2022 |
| HP            | Laptop 15s-dr0xxx           | [be60e498db](https://linux-hardware.org/?probe=be60e498db) | Jan 06, 2022 |
| HP            | ProBook 4510s               | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Inspiron M5030              | [1715a3e584](https://linux-hardware.org/?probe=1715a3e584) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Acer          | Aspire 7741                 | [2f03831c23](https://linux-hardware.org/?probe=2f03831c23) | Jan 05, 2022 |
| Acer          | E1-510                      | [f5a0998e25](https://linux-hardware.org/?probe=f5a0998e25) | Jan 05, 2022 |
| ASUSTek       | X555QG                      | [a10e6b5ec0](https://linux-hardware.org/?probe=a10e6b5ec0) | Jan 04, 2022 |
| Acer          | Aspire 6930G                | [929cea53e3](https://linux-hardware.org/?probe=929cea53e3) | Jan 04, 2022 |
| Dell          | Inspiron 1750               | [827adb411f](https://linux-hardware.org/?probe=827adb411f) | Jan 04, 2022 |
| Lenovo        | G50-70 20351                | [04b904c594](https://linux-hardware.org/?probe=04b904c594) | Jan 04, 2022 |
| NEC Comput... | PC-LL550RG                  | [43435578b7](https://linux-hardware.org/?probe=43435578b7) | Jan 04, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [9f6ca62b59](https://linux-hardware.org/?probe=9f6ca62b59) | Jan 04, 2022 |
| ASUSTek       | X555QG                      | [9062bc4b1d](https://linux-hardware.org/?probe=9062bc4b1d) | Jan 03, 2022 |
| Dell          | Inspiron 13-5378            | [8d019441d1](https://linux-hardware.org/?probe=8d019441d1) | Jan 03, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [22a9d41db0](https://linux-hardware.org/?probe=22a9d41db0) | Jan 02, 2022 |
| Dell          | Latitude E7440              | [9df6480d3e](https://linux-hardware.org/?probe=9df6480d3e) | Jan 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [6100abe0e1](https://linux-hardware.org/?probe=6100abe0e1) | Jan 02, 2022 |
| Lenovo        | ThinkPad T490 20N3S6US00    | [087fbff7d6](https://linux-hardware.org/?probe=087fbff7d6) | Jan 02, 2022 |
| Dell          | Inspiron 5770               | [0e81199f2c](https://linux-hardware.org/?probe=0e81199f2c) | Jan 02, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| Lenovo        | V14-IIL 82C4                | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Lenovo        | ThinkPad T490 20N3S6US00    | [f748f15a80](https://linux-hardware.org/?probe=f748f15a80) | Jan 01, 2022 |
| Jumper        | EZbook                      | [aed28b71f9](https://linux-hardware.org/?probe=aed28b71f9) | Jan 01, 2022 |
| MSI           | EX705                       | [a969bd4369](https://linux-hardware.org/?probe=a969bd4369) | Dec 31, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [0bfa74fa9f](https://linux-hardware.org/?probe=0bfa74fa9f) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [90d57a20ee](https://linux-hardware.org/?probe=90d57a20ee) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [4db624e8a0](https://linux-hardware.org/?probe=4db624e8a0) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [b79e118712](https://linux-hardware.org/?probe=b79e118712) | Dec 31, 2021 |
| MSI           | GE-700                      | [9ccf434539](https://linux-hardware.org/?probe=9ccf434539) | Dec 31, 2021 |
| MSI           | GE-700                      | [dd9998069e](https://linux-hardware.org/?probe=dd9998069e) | Dec 31, 2021 |
| Toshiba       | Satellite L300              | [fc547136cc](https://linux-hardware.org/?probe=fc547136cc) | Dec 31, 2021 |
| HP            | Pavilion dv5                | [7017ea359e](https://linux-hardware.org/?probe=7017ea359e) | Dec 31, 2021 |
| Acer          | Aspire 1810TZ               | [0b7bd5c1fa](https://linux-hardware.org/?probe=0b7bd5c1fa) | Dec 30, 2021 |
| MSI           | GT70 2OC/2OD                | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | [f20a77fa7e](https://linux-hardware.org/?probe=f20a77fa7e) | Dec 29, 2021 |
| Packard Be... | EasyNote TK85               | [cef3f4f826](https://linux-hardware.org/?probe=cef3f4f826) | Dec 28, 2021 |
| HP            | ProBook 4730s               | [08cca0b4b5](https://linux-hardware.org/?probe=08cca0b4b5) | Dec 28, 2021 |
| Lenovo        | ThinkPad L540 20AV0031MB    | [5abe6c6347](https://linux-hardware.org/?probe=5abe6c6347) | Dec 28, 2021 |
| ASUSTek       | X302LA                      | [3c747e6bb0](https://linux-hardware.org/?probe=3c747e6bb0) | Dec 28, 2021 |
| Dell          | Latitude 7490               | [044b1ea3d3](https://linux-hardware.org/?probe=044b1ea3d3) | Dec 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [55b2c93259](https://linux-hardware.org/?probe=55b2c93259) | Dec 28, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [82c3a0ea01](https://linux-hardware.org/?probe=82c3a0ea01) | Dec 28, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [fa2df1f6f0](https://linux-hardware.org/?probe=fa2df1f6f0) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| Lenovo        | V14-IIL 82C4                | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | [1cd129ee35](https://linux-hardware.org/?probe=1cd129ee35) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | [f2deb9ec59](https://linux-hardware.org/?probe=f2deb9ec59) | Dec 27, 2021 |
| Dell          | Inspiron 3583               | [adcf14bf31](https://linux-hardware.org/?probe=adcf14bf31) | Dec 27, 2021 |
| Acer          | Aspire M5-481T              | [2515a869a5](https://linux-hardware.org/?probe=2515a869a5) | Dec 26, 2021 |
| Acer          | Aspire M5-481T              | [1ef9b940b2](https://linux-hardware.org/?probe=1ef9b940b2) | Dec 26, 2021 |
| Fusion5       | FWIN232_PLUS                | [ce10f25e8c](https://linux-hardware.org/?probe=ce10f25e8c) | Dec 25, 2021 |
| Dell          | Latitude 12 Rugged Table... | [13cc8e2abf](https://linux-hardware.org/?probe=13cc8e2abf) | Dec 25, 2021 |
| ASUSTek       | M50Vm                       | [bc36782a82](https://linux-hardware.org/?probe=bc36782a82) | Dec 25, 2021 |
| Dell          | Latitude 3440               | [e80fdcee0c](https://linux-hardware.org/?probe=e80fdcee0c) | Dec 25, 2021 |
| Toshiba       | TECRA S11                   | [b846fd9c93](https://linux-hardware.org/?probe=b846fd9c93) | Dec 24, 2021 |
| Dell          | Latitude 3540               | [7e7f291d68](https://linux-hardware.org/?probe=7e7f291d68) | Dec 24, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [3415419b6b](https://linux-hardware.org/?probe=3415419b6b) | Dec 23, 2021 |
| Acer          | Aspire E1-531               | [d1d6054fc3](https://linux-hardware.org/?probe=d1d6054fc3) | Dec 22, 2021 |
| ASUSTek       | K53E                        | [0a089d38c0](https://linux-hardware.org/?probe=0a089d38c0) | Dec 21, 2021 |
| Sony          | VGN-FW21E                   | [0c58cd8d69](https://linux-hardware.org/?probe=0c58cd8d69) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | [a7e83ee775](https://linux-hardware.org/?probe=a7e83ee775) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | [f10ab27170](https://linux-hardware.org/?probe=f10ab27170) | Dec 20, 2021 |
| HP            | EliteBook 2570p             | [462b93b05b](https://linux-hardware.org/?probe=462b93b05b) | Dec 20, 2021 |
| Digibras      | NH4CU03                     | [517425552d](https://linux-hardware.org/?probe=517425552d) | Dec 19, 2021 |
| Sony          | VGN-FW21E                   | [d90a22e7b0](https://linux-hardware.org/?probe=d90a22e7b0) | Dec 19, 2021 |
| Acer          | Aspire V3-571               | [5189bf7726](https://linux-hardware.org/?probe=5189bf7726) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | [2013d9d5d8](https://linux-hardware.org/?probe=2013d9d5d8) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | [67286f0d11](https://linux-hardware.org/?probe=67286f0d11) | Dec 19, 2021 |
| Packard Be... | EasyNote TE11BZ             | [24fef50189](https://linux-hardware.org/?probe=24fef50189) | Dec 19, 2021 |
| HP            | EliteBook 8440p             | [0dc23e59a4](https://linux-hardware.org/?probe=0dc23e59a4) | Dec 19, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [897b589a83](https://linux-hardware.org/?probe=897b589a83) | Dec 19, 2021 |
| ASUSTek       | K53SD                       | [68a3cbb84c](https://linux-hardware.org/?probe=68a3cbb84c) | Dec 18, 2021 |
| HP            | Laptop 15-db1xxx            | [20f9c7a4ef](https://linux-hardware.org/?probe=20f9c7a4ef) | Dec 18, 2021 |
| Toshiba       | Satellite C660              | [6f860db242](https://linux-hardware.org/?probe=6f860db242) | Dec 18, 2021 |
| Dell          | Latitude E6500              | [5a29db9bdf](https://linux-hardware.org/?probe=5a29db9bdf) | Dec 18, 2021 |
| Lenovo        | ThinkPad X230 2325SYU       | [3b01a9e8eb](https://linux-hardware.org/?probe=3b01a9e8eb) | Dec 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dda5e17a21](https://linux-hardware.org/?probe=dda5e17a21) | Dec 17, 2021 |
| Toshiba       | TECRA A9                    | [53cba6b9d1](https://linux-hardware.org/?probe=53cba6b9d1) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | [58eb588f8b](https://linux-hardware.org/?probe=58eb588f8b) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | [84cabc70f7](https://linux-hardware.org/?probe=84cabc70f7) | Dec 16, 2021 |
| Compaq        | Presario 21                 | [86e7a85db3](https://linux-hardware.org/?probe=86e7a85db3) | Dec 16, 2021 |
| Toshiba       | QOSMIO X770                 | [c8c9ab4cf8](https://linux-hardware.org/?probe=c8c9ab4cf8) | Dec 16, 2021 |
| HP            | ZBook 17 G5                 | [761a2419e5](https://linux-hardware.org/?probe=761a2419e5) | Dec 16, 2021 |
| RCA           | WT9503W004                  | [c858eb3cbc](https://linux-hardware.org/?probe=c858eb3cbc) | Dec 15, 2021 |
| Dell          | Latitude E6400              | [dc0d35221e](https://linux-hardware.org/?probe=dc0d35221e) | Dec 15, 2021 |
| HP            | EliteBook 8730w             | [e35ce8395b](https://linux-hardware.org/?probe=e35ce8395b) | Dec 15, 2021 |
| HP            | ProBook 450 G3              | [d197761676](https://linux-hardware.org/?probe=d197761676) | Dec 15, 2021 |
| Google        | Squawks                     | [e75aa07dad](https://linux-hardware.org/?probe=e75aa07dad) | Dec 15, 2021 |
| Acer          | Aspire V3-571               | [071a8f0709](https://linux-hardware.org/?probe=071a8f0709) | Dec 15, 2021 |
| Dell          | Inspiron 3501               | [6cf66f6290](https://linux-hardware.org/?probe=6cf66f6290) | Dec 15, 2021 |
| Lenovo        | G580 20150                  | [6ff1581ca6](https://linux-hardware.org/?probe=6ff1581ca6) | Dec 14, 2021 |
| Acer          | AOD255                      | [08a007120e](https://linux-hardware.org/?probe=08a007120e) | Dec 14, 2021 |
| HP            | EliteBook Folio 9480m       | [11eea57427](https://linux-hardware.org/?probe=11eea57427) | Dec 14, 2021 |
| Toshiba       | Satellite L655              | [0db50aad32](https://linux-hardware.org/?probe=0db50aad32) | Dec 14, 2021 |
| Digibras      | NH4CU03                     | [97b0f21219](https://linux-hardware.org/?probe=97b0f21219) | Dec 14, 2021 |
| MSI           | PS42 Modern 8RC             | [2686d73cb8](https://linux-hardware.org/?probe=2686d73cb8) | Dec 13, 2021 |
| Lenovo        | ThinkPad X270 20HN0043AD    | [24160af893](https://linux-hardware.org/?probe=24160af893) | Dec 13, 2021 |
| Google        | Squawks                     | [31cb595893](https://linux-hardware.org/?probe=31cb595893) | Dec 13, 2021 |
| Digibras      | NH4CU03                     | [5ffb383677](https://linux-hardware.org/?probe=5ffb383677) | Dec 13, 2021 |
| Acer          | Aspire V3-571               | [54680bac44](https://linux-hardware.org/?probe=54680bac44) | Dec 12, 2021 |
| Dell          | Precision M4600             | [32034c26c7](https://linux-hardware.org/?probe=32034c26c7) | Dec 12, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d364ff0c44](https://linux-hardware.org/?probe=d364ff0c44) | Dec 12, 2021 |
| HP            | ProBook 450 G3              | [54846cdc88](https://linux-hardware.org/?probe=54846cdc88) | Dec 12, 2021 |
| Dell          | Latitude E5410              | [8b6bc5cf8e](https://linux-hardware.org/?probe=8b6bc5cf8e) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | [7bf355c3c1](https://linux-hardware.org/?probe=7bf355c3c1) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [807bd77769](https://linux-hardware.org/?probe=807bd77769) | Dec 12, 2021 |
| Positivo      | CHT14B                      | [6ebdfd7b1f](https://linux-hardware.org/?probe=6ebdfd7b1f) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| Dell          | Precision M4600             | [f3f7be37a2](https://linux-hardware.org/?probe=f3f7be37a2) | Dec 12, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [0fb07d458a](https://linux-hardware.org/?probe=0fb07d458a) | Dec 12, 2021 |
| Acer          | Aspire A517-52              | [a51b1f9eb7](https://linux-hardware.org/?probe=a51b1f9eb7) | Dec 11, 2021 |
| Acer          | Aspire A517-52              | [bbf5c7ea28](https://linux-hardware.org/?probe=bbf5c7ea28) | Dec 11, 2021 |
| Dell          | Latitude E5400              | [2444de97e0](https://linux-hardware.org/?probe=2444de97e0) | Dec 11, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [a5528e8f98](https://linux-hardware.org/?probe=a5528e8f98) | Dec 11, 2021 |
| Chuwi         | GemiBook Pro                | [493d55cb16](https://linux-hardware.org/?probe=493d55cb16) | Dec 11, 2021 |
| TCL Commun... | 8085                        | [3d795ceee0](https://linux-hardware.org/?probe=3d795ceee0) | Dec 11, 2021 |
| Dell          | Latitude E5400              | [212020992c](https://linux-hardware.org/?probe=212020992c) | Dec 11, 2021 |
| HP            | Pavilion dv3                | [484e48a117](https://linux-hardware.org/?probe=484e48a117) | Dec 11, 2021 |
| HP            | 15 Notebook PC              | [3be4065d87](https://linux-hardware.org/?probe=3be4065d87) | Dec 10, 2021 |
| HP            | 15 Notebook PC              | [c06d1d8915](https://linux-hardware.org/?probe=c06d1d8915) | Dec 10, 2021 |
| Dell          | Latitude E7440              | [ff067012c5](https://linux-hardware.org/?probe=ff067012c5) | Dec 09, 2021 |
| Samsung       | N150P/N210P/N220P           | [eed2dcde15](https://linux-hardware.org/?probe=eed2dcde15) | Dec 09, 2021 |
| Apple         | MacBook4,1                  | [cfa6005bc4](https://linux-hardware.org/?probe=cfa6005bc4) | Dec 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [dc07419c59](https://linux-hardware.org/?probe=dc07419c59) | Dec 08, 2021 |
| Lenovo        | ThinkPad T400 741722U       | [2739940ec1](https://linux-hardware.org/?probe=2739940ec1) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [c31f062314](https://linux-hardware.org/?probe=c31f062314) | Dec 07, 2021 |
| HP            | HDX 16                      | [cf114f9094](https://linux-hardware.org/?probe=cf114f9094) | Dec 07, 2021 |
| Unknown       | Unknown                     | [9e9e0598b6](https://linux-hardware.org/?probe=9e9e0598b6) | Dec 07, 2021 |
| HP            | Stream Laptop 14-cb1XX      | [4853c251a8](https://linux-hardware.org/?probe=4853c251a8) | Dec 07, 2021 |
| Apple         | MacBookPro8,1               | [85d594af54](https://linux-hardware.org/?probe=85d594af54) | Dec 07, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [9c64eb115e](https://linux-hardware.org/?probe=9c64eb115e) | Dec 07, 2021 |
| Lenovo        | ThinkPad T400 741722U       | [2933ad8c69](https://linux-hardware.org/?probe=2933ad8c69) | Dec 07, 2021 |
| Dell          | Inspiron 5748               | [77f278682e](https://linux-hardware.org/?probe=77f278682e) | Dec 06, 2021 |
| Apple         | MacBookPro11,1              | [f454c30e46](https://linux-hardware.org/?probe=f454c30e46) | Dec 05, 2021 |
| Acer          | Aspire V3-571G              | [3acb23e27c](https://linux-hardware.org/?probe=3acb23e27c) | Dec 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [fc540c3951](https://linux-hardware.org/?probe=fc540c3951) | Dec 05, 2021 |
| Dell          | Inspiron 5770               | [c8a717a1c9](https://linux-hardware.org/?probe=c8a717a1c9) | Dec 05, 2021 |
| ASUSTek       | X553MA                      | [958551b7eb](https://linux-hardware.org/?probe=958551b7eb) | Dec 05, 2021 |
| Sony          | SVF1532Z1EB                 | [d65626b69d](https://linux-hardware.org/?probe=d65626b69d) | Dec 04, 2021 |
| ASUSTek       | X553MA                      | [78414b8bc4](https://linux-hardware.org/?probe=78414b8bc4) | Dec 04, 2021 |
| Lenovo        | G700                        | [2b7a430fcd](https://linux-hardware.org/?probe=2b7a430fcd) | Dec 04, 2021 |
| Toshiba       | Satellite C660              | [4d64247a8a](https://linux-hardware.org/?probe=4d64247a8a) | Dec 04, 2021 |
| ASUSTek       | K53TK                       | [043ef58552](https://linux-hardware.org/?probe=043ef58552) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | [6c468accc0](https://linux-hardware.org/?probe=6c468accc0) | Dec 03, 2021 |
| Acer          | Aspire A315-58G             | [48e3c0e6c7](https://linux-hardware.org/?probe=48e3c0e6c7) | Dec 03, 2021 |
| HP            | OMEN Notebook               | [5b8b235c98](https://linux-hardware.org/?probe=5b8b235c98) | Dec 03, 2021 |
| Samsung       | 700T                        | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| Dell          | Latitude E6530              | [fe6dbdef48](https://linux-hardware.org/?probe=fe6dbdef48) | Dec 03, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [29ff3edb05](https://linux-hardware.org/?probe=29ff3edb05) | Dec 03, 2021 |
| Toshiba       | Satellite L655              | [0e3a82aad6](https://linux-hardware.org/?probe=0e3a82aad6) | Dec 03, 2021 |
| Dell          | Latitude 7280               | [8baf21a38d](https://linux-hardware.org/?probe=8baf21a38d) | Dec 02, 2021 |
| HUAWEI        | KLVL-WXX9                   | [57b4dae376](https://linux-hardware.org/?probe=57b4dae376) | Dec 02, 2021 |
| HP            | 15                          | [8d1ef12e0e](https://linux-hardware.org/?probe=8d1ef12e0e) | Dec 02, 2021 |
| HP            | ProBook 450 G3              | [ca49dc0eee](https://linux-hardware.org/?probe=ca49dc0eee) | Dec 02, 2021 |
| HP            | 15                          | [b374916ca6](https://linux-hardware.org/?probe=b374916ca6) | Dec 02, 2021 |
| Toshiba       | Satellite L55-B             | [0bc52401f0](https://linux-hardware.org/?probe=0bc52401f0) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [cb2302b704](https://linux-hardware.org/?probe=cb2302b704) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [f580be444b](https://linux-hardware.org/?probe=f580be444b) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [e2fbd06e2a](https://linux-hardware.org/?probe=e2fbd06e2a) | Dec 02, 2021 |
| TUXEDO        | Pulse 14 Gen1               | [c7eeb775f9](https://linux-hardware.org/?probe=c7eeb775f9) | Dec 02, 2021 |
| HP            | 15                          | [cb278b1a6b](https://linux-hardware.org/?probe=cb278b1a6b) | Dec 02, 2021 |
| Dell          | Latitude E5570              | [d7beab52f4](https://linux-hardware.org/?probe=d7beab52f4) | Dec 02, 2021 |
| Avell High... | B.ON                        | [a7513f22ee](https://linux-hardware.org/?probe=a7513f22ee) | Dec 02, 2021 |
| Primux        | 15R5A                       | [3aef7d25e8](https://linux-hardware.org/?probe=3aef7d25e8) | Dec 01, 2021 |
| ASUSTek       | X751LAB                     | [4383b601f4](https://linux-hardware.org/?probe=4383b601f4) | Nov 30, 2021 |
| MSI           | GF63 Thin 10SC              | [5f908f227a](https://linux-hardware.org/?probe=5f908f227a) | Nov 30, 2021 |
| HP            | EliteBook 8440p             | [cecc697189](https://linux-hardware.org/?probe=cecc697189) | Nov 30, 2021 |
| Dell          | Inspiron 15-3567            | [3a2bf12582](https://linux-hardware.org/?probe=3a2bf12582) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [7184635417](https://linux-hardware.org/?probe=7184635417) | Nov 29, 2021 |
| Dell          | Latitude 7275               | [bf808d506c](https://linux-hardware.org/?probe=bf808d506c) | Nov 29, 2021 |
| Chuwi         | GemiBook                    | [911b855817](https://linux-hardware.org/?probe=911b855817) | Nov 28, 2021 |
| Chuwi         | GemiBook                    | [b8f87029fa](https://linux-hardware.org/?probe=b8f87029fa) | Nov 28, 2021 |
| Dell          | Latitude E5420              | [9f504b4e6b](https://linux-hardware.org/?probe=9f504b4e6b) | Nov 28, 2021 |
| ASUSTek       | P453UJ                      | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| ASUSTek       | X455LJ                      | [018d5bcbac](https://linux-hardware.org/?probe=018d5bcbac) | Nov 27, 2021 |
| Acer          | Aspire A315-42              | [a0483c5539](https://linux-hardware.org/?probe=a0483c5539) | Nov 27, 2021 |
| Toshiba       | Satellite L500              | [24645f6ab5](https://linux-hardware.org/?probe=24645f6ab5) | Nov 26, 2021 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [25e2834604](https://linux-hardware.org/?probe=25e2834604) | Nov 25, 2021 |
| Notebook      | NH50_70RA                   | [baa1c5d2ca](https://linux-hardware.org/?probe=baa1c5d2ca) | Nov 24, 2021 |
| HP            | Elite x2 1012 G1            | [5e2d2a574d](https://linux-hardware.org/?probe=5e2d2a574d) | Nov 24, 2021 |
| Lenovo        | Flex 2-14 20404             | [74894434bb](https://linux-hardware.org/?probe=74894434bb) | Nov 24, 2021 |
| Sony          | SVE1713Y1EB                 | [755b7b85f5](https://linux-hardware.org/?probe=755b7b85f5) | Nov 24, 2021 |
| HP            | EliteBook 8460p             | [ca30b13118](https://linux-hardware.org/?probe=ca30b13118) | Nov 24, 2021 |
| HP            | EliteBook 8570p             | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| Acer          | Okinawa                     | [2953f32ed9](https://linux-hardware.org/?probe=2953f32ed9) | Nov 23, 2021 |
| HP            | Pavilion 17                 | [315037ddfd](https://linux-hardware.org/?probe=315037ddfd) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | [33a3597313](https://linux-hardware.org/?probe=33a3597313) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | [c1bf05d67a](https://linux-hardware.org/?probe=c1bf05d67a) | Nov 23, 2021 |
| ASUSTek       | GL552VW                     | [59670a3933](https://linux-hardware.org/?probe=59670a3933) | Nov 23, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [56ff76e064](https://linux-hardware.org/?probe=56ff76e064) | Nov 23, 2021 |
| ASUSTek       | G750JX                      | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| Lenovo        | G580 20150                  | [baade6ba54](https://linux-hardware.org/?probe=baade6ba54) | Nov 22, 2021 |
| Lenovo        | G580 20150                  | [b7718027af](https://linux-hardware.org/?probe=b7718027af) | Nov 22, 2021 |
| HP            | 15                          | [1753404669](https://linux-hardware.org/?probe=1753404669) | Nov 22, 2021 |
| HP            | Notebook                    | [9e9ce14e95](https://linux-hardware.org/?probe=9e9ce14e95) | Nov 22, 2021 |
| ASUSTek       | X751SA                      | [d19fd8c59f](https://linux-hardware.org/?probe=d19fd8c59f) | Nov 22, 2021 |
| Toshiba       | Satellite L500              | [30bfdcb5ff](https://linux-hardware.org/?probe=30bfdcb5ff) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| Fujitsu Si... | AMILO Pa 1510               | [9f731acb7e](https://linux-hardware.org/?probe=9f731acb7e) | Nov 22, 2021 |
| HP            | 15                          | [bca58eb5e0](https://linux-hardware.org/?probe=bca58eb5e0) | Nov 22, 2021 |
| Apple         | MacBookPro5,3               | [5a4e91eace](https://linux-hardware.org/?probe=5a4e91eace) | Nov 22, 2021 |
| ASUSTek       | U56E                        | [2b347f1923](https://linux-hardware.org/?probe=2b347f1923) | Nov 22, 2021 |
| Lenovo        | G560 0679                   | [15348ebbf9](https://linux-hardware.org/?probe=15348ebbf9) | Nov 22, 2021 |
| HP            | Pavilion 15                 | [0f1442bb2c](https://linux-hardware.org/?probe=0f1442bb2c) | Nov 22, 2021 |
| Toshiba       | PORTEGE R705                | [47688cd36a](https://linux-hardware.org/?probe=47688cd36a) | Nov 21, 2021 |
| Toshiba       | Satellite U300              | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| HP            | ENVY Notebook               | [09767edae3](https://linux-hardware.org/?probe=09767edae3) | Nov 21, 2021 |
| Dell          | Latitude E6440              | [babff23db6](https://linux-hardware.org/?probe=babff23db6) | Nov 21, 2021 |
| Dell          | G7 7700                     | [730daa1080](https://linux-hardware.org/?probe=730daa1080) | Nov 21, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [c99c5700f6](https://linux-hardware.org/?probe=c99c5700f6) | Nov 20, 2021 |
| HP            | Pavilion Notebook           | [ca1ccc6e65](https://linux-hardware.org/?probe=ca1ccc6e65) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [12136b1cbd](https://linux-hardware.org/?probe=12136b1cbd) | Nov 20, 2021 |
| HP            | Pavilion 15                 | [687ecf1c58](https://linux-hardware.org/?probe=687ecf1c58) | Nov 20, 2021 |
| Sony          | SVE1713D1EW                 | [20d3ee7401](https://linux-hardware.org/?probe=20d3ee7401) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [5a5b8c420f](https://linux-hardware.org/?probe=5a5b8c420f) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [89fdff42c1](https://linux-hardware.org/?probe=89fdff42c1) | Nov 20, 2021 |
| Dell          | Precision M6700             | [a8bf3915fb](https://linux-hardware.org/?probe=a8bf3915fb) | Nov 20, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [7ddd35d3e8](https://linux-hardware.org/?probe=7ddd35d3e8) | Nov 20, 2021 |
| Sony          | SVE1713Y1EB                 | [4a77a751d9](https://linux-hardware.org/?probe=4a77a751d9) | Nov 20, 2021 |
| Toshiba       | Satellite C50D-B            | [6c92d7fef6](https://linux-hardware.org/?probe=6c92d7fef6) | Nov 19, 2021 |
| Dell          | Latitude E5550              | [2f52aa274c](https://linux-hardware.org/?probe=2f52aa274c) | Nov 19, 2021 |
| LG Electro... | S460-G.BG31P1               | [96d8266022](https://linux-hardware.org/?probe=96d8266022) | Nov 19, 2021 |
| Sony          | SVE1713D1EW                 | [cf21ed12bc](https://linux-hardware.org/?probe=cf21ed12bc) | Nov 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S1GW1Q    | [3b8a61e460](https://linux-hardware.org/?probe=3b8a61e460) | Nov 18, 2021 |
| Google        | Lars                        | [c346746b7e](https://linux-hardware.org/?probe=c346746b7e) | Nov 18, 2021 |
| Dell          | Latitude 5590               | [8bef1790bd](https://linux-hardware.org/?probe=8bef1790bd) | Nov 18, 2021 |
| Acer          | TravelMate 6292             | [2cec3b7547](https://linux-hardware.org/?probe=2cec3b7547) | Nov 17, 2021 |
| HP            | ENVY m7 Notebook            | [4b101cc132](https://linux-hardware.org/?probe=4b101cc132) | Nov 17, 2021 |
| HP            | Stream Notebook PC 14       | [31499aa79d](https://linux-hardware.org/?probe=31499aa79d) | Nov 17, 2021 |
| HP            | Stream Notebook PC 14       | [8c30001e99](https://linux-hardware.org/?probe=8c30001e99) | Nov 17, 2021 |
| Lenovo        | ThinkPad T430 23445PU       | [e5fe64db56](https://linux-hardware.org/?probe=e5fe64db56) | Nov 16, 2021 |
| Toshiba       | Satellite C655D             | [cd8abc5170](https://linux-hardware.org/?probe=cd8abc5170) | Nov 16, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [bfef77542f](https://linux-hardware.org/?probe=bfef77542f) | Nov 15, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [76b69deb69](https://linux-hardware.org/?probe=76b69deb69) | Nov 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| HP            | Notebook                    | [226dc7dc39](https://linux-hardware.org/?probe=226dc7dc39) | Nov 12, 2021 |
| HP            | Notebook                    | [c03f407f50](https://linux-hardware.org/?probe=c03f407f50) | Nov 12, 2021 |
| HP            | Notebook                    | [a2bae8d4b8](https://linux-hardware.org/?probe=a2bae8d4b8) | Nov 12, 2021 |
| HP            | Notebook                    | [87dec3cf7c](https://linux-hardware.org/?probe=87dec3cf7c) | Nov 12, 2021 |
| HP            | EliteBook 2560p             | [e3997c3bcb](https://linux-hardware.org/?probe=e3997c3bcb) | Nov 12, 2021 |
| Dell          | Inspiron 15-3567            | [e8879e98df](https://linux-hardware.org/?probe=e8879e98df) | Nov 12, 2021 |
| Google        | Kindred                     | [0046ef8942](https://linux-hardware.org/?probe=0046ef8942) | Nov 12, 2021 |
| Google        | Kindred                     | [9d72c8972c](https://linux-hardware.org/?probe=9d72c8972c) | Nov 12, 2021 |
| Acer          | Aspire 4830T                | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| Notebook      | N85_N87HCHNHZ               | [32988fae95](https://linux-hardware.org/?probe=32988fae95) | Nov 11, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [c948868090](https://linux-hardware.org/?probe=c948868090) | Nov 11, 2021 |
| Dell          | Inspiron 1750               | [6ffff20ec8](https://linux-hardware.org/?probe=6ffff20ec8) | Nov 11, 2021 |
| Sony          | SVF14211CLB                 | [7c0dacdd54](https://linux-hardware.org/?probe=7c0dacdd54) | Nov 10, 2021 |
| HUAWEI        | BOHB-WAX9                   | [3b1f90f3ab](https://linux-hardware.org/?probe=3b1f90f3ab) | Nov 10, 2021 |
| HUAWEI        | BOHB-WAX9                   | [3858faa240](https://linux-hardware.org/?probe=3858faa240) | Nov 10, 2021 |
| Sony          | SVF14211CLB                 | [fdfd650fcc](https://linux-hardware.org/?probe=fdfd650fcc) | Nov 10, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [94da614270](https://linux-hardware.org/?probe=94da614270) | Nov 10, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [72dd15e9c5](https://linux-hardware.org/?probe=72dd15e9c5) | Nov 10, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [0d017f9835](https://linux-hardware.org/?probe=0d017f9835) | Nov 10, 2021 |
| ASUSTek       | U46E                        | [d52a43c7fd](https://linux-hardware.org/?probe=d52a43c7fd) | Nov 10, 2021 |
| Dell          | Latitude 3440               | [eb76b9d1cf](https://linux-hardware.org/?probe=eb76b9d1cf) | Nov 09, 2021 |
| HP            | Pavilion dv6                | [605479abf7](https://linux-hardware.org/?probe=605479abf7) | Nov 08, 2021 |
| HP            | Pavilion dv6                | [b7a410c2e6](https://linux-hardware.org/?probe=b7a410c2e6) | Nov 08, 2021 |
| MSI           | GF63 Thin 9SC               | [d85e7a0ad3](https://linux-hardware.org/?probe=d85e7a0ad3) | Nov 07, 2021 |
| Dell          | Latitude E5420              | [b53c6bd6d2](https://linux-hardware.org/?probe=b53c6bd6d2) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [520a472266](https://linux-hardware.org/?probe=520a472266) | Nov 07, 2021 |
| HP            | Compaq 8510p                | [ddecc261a1](https://linux-hardware.org/?probe=ddecc261a1) | Nov 07, 2021 |
| HP            | Compaq 8510p                | [c2434c1c08](https://linux-hardware.org/?probe=c2434c1c08) | Nov 07, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [a0d13572a5](https://linux-hardware.org/?probe=a0d13572a5) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | [746f64d20b](https://linux-hardware.org/?probe=746f64d20b) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | [245941966f](https://linux-hardware.org/?probe=245941966f) | Nov 06, 2021 |
| Sony          | SVE1713D1EW                 | [45609f28be](https://linux-hardware.org/?probe=45609f28be) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | [5d577f71a4](https://linux-hardware.org/?probe=5d577f71a4) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | [c37780e9ad](https://linux-hardware.org/?probe=c37780e9ad) | Nov 06, 2021 |
| ASUSTek       | K53TA                       | [e924b214bc](https://linux-hardware.org/?probe=e924b214bc) | Nov 06, 2021 |
| Acer          | Aspire ES1-521              | [5ef4af5924](https://linux-hardware.org/?probe=5ef4af5924) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [73b5ea9e0b](https://linux-hardware.org/?probe=73b5ea9e0b) | Nov 06, 2021 |
| HP            | ProBook 450 G4              | [a96a96d455](https://linux-hardware.org/?probe=a96a96d455) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Sony          | VPCEG23EL                   | [cc967c03fb](https://linux-hardware.org/?probe=cc967c03fb) | Nov 05, 2021 |
| Acer          | Swift SF314-54              | [b506625dc2](https://linux-hardware.org/?probe=b506625dc2) | Nov 05, 2021 |
| ASUSTek       | X751NV                      | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| Dell          | Precision M6700             | [1865ed7cca](https://linux-hardware.org/?probe=1865ed7cca) | Nov 03, 2021 |
| Dell          | Latitude 5490               | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | Notebook                    | [ee3bc3deef](https://linux-hardware.org/?probe=ee3bc3deef) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [3acc230d6a](https://linux-hardware.org/?probe=3acc230d6a) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c88adaac6e](https://linux-hardware.org/?probe=c88adaac6e) | Nov 02, 2021 |
| Lenovo        | ThinkPad T430 2349ED5       | [0697993e7c](https://linux-hardware.org/?probe=0697993e7c) | Nov 02, 2021 |
| HP            | ProBook 440 G4              | [695b9a4e0c](https://linux-hardware.org/?probe=695b9a4e0c) | Nov 01, 2021 |
| HP            | ProBook 440 G4              | [4bba4734e8](https://linux-hardware.org/?probe=4bba4734e8) | Nov 01, 2021 |
| Dell          | XPS 15 9510                 | [9ad082f18e](https://linux-hardware.org/?probe=9ad082f18e) | Nov 01, 2021 |
| ASUSTek       | K52Jc                       | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| HP            | 255 G8 Notebook PC          | [600b7b9957](https://linux-hardware.org/?probe=600b7b9957) | Nov 01, 2021 |
| Acer          | Aspire E1-522               | [56b475a93d](https://linux-hardware.org/?probe=56b475a93d) | Nov 01, 2021 |
| Toshiba       | Satellite Pro T110          | [3ae7a19459](https://linux-hardware.org/?probe=3ae7a19459) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | [e3fc4e0622](https://linux-hardware.org/?probe=e3fc4e0622) | Oct 31, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [83d642714b](https://linux-hardware.org/?probe=83d642714b) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | [eabb3946ad](https://linux-hardware.org/?probe=eabb3946ad) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | [3861fce83e](https://linux-hardware.org/?probe=3861fce83e) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | [2388e68622](https://linux-hardware.org/?probe=2388e68622) | Oct 31, 2021 |
| Dell          | Inspiron 7720               | [9f298535a5](https://linux-hardware.org/?probe=9f298535a5) | Oct 31, 2021 |
| HP            | 255 G8 Notebook PC          | [cb9c15cf6f](https://linux-hardware.org/?probe=cb9c15cf6f) | Oct 30, 2021 |
| Dell          | Latitude E6500              | [e475348b1e](https://linux-hardware.org/?probe=e475348b1e) | Oct 30, 2021 |
| MECER         | Z140C+Home                  | [2fbf6f153b](https://linux-hardware.org/?probe=2fbf6f153b) | Oct 30, 2021 |
| HP            | Pavilion Notebook           | [85a55f5c3c](https://linux-hardware.org/?probe=85a55f5c3c) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | [6260be6de5](https://linux-hardware.org/?probe=6260be6de5) | Oct 30, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [af0a995721](https://linux-hardware.org/?probe=af0a995721) | Oct 30, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [88286c36e9](https://linux-hardware.org/?probe=88286c36e9) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | [f5f4e2457b](https://linux-hardware.org/?probe=f5f4e2457b) | Oct 29, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c74557d180](https://linux-hardware.org/?probe=c74557d180) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | [35b5fcb787](https://linux-hardware.org/?probe=35b5fcb787) | Oct 28, 2021 |
| ASUSTek       | N71Jv                       | [29e3747e17](https://linux-hardware.org/?probe=29e3747e17) | Oct 28, 2021 |
| ASUSTek       | X750JB                      | [90fd9f38fc](https://linux-hardware.org/?probe=90fd9f38fc) | Oct 27, 2021 |
| Lenovo        | G570 4334                   | [cc07ebf9b6](https://linux-hardware.org/?probe=cc07ebf9b6) | Oct 27, 2021 |
| HP            | EliteBook 8440p             | [f527983cc9](https://linux-hardware.org/?probe=f527983cc9) | Oct 27, 2021 |
| Toshiba       | PORTEGE Z20t-C              | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| Lenovo        | Legion Y920-17IKB Laptop... | [830d4c9d9d](https://linux-hardware.org/?probe=830d4c9d9d) | Oct 26, 2021 |
| Acer          | Aspire 5737Z                | [9bbf3befab](https://linux-hardware.org/?probe=9bbf3befab) | Oct 26, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [4104e265ea](https://linux-hardware.org/?probe=4104e265ea) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [3da20846f5](https://linux-hardware.org/?probe=3da20846f5) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [2d19155e7f](https://linux-hardware.org/?probe=2d19155e7f) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [ed4e9d1a03](https://linux-hardware.org/?probe=ed4e9d1a03) | Oct 26, 2021 |
| HP            | ProBook 445 G7              | [87b3274937](https://linux-hardware.org/?probe=87b3274937) | Oct 26, 2021 |
| HP            | Stream Notebook PC 11       | [c240a088a9](https://linux-hardware.org/?probe=c240a088a9) | Oct 26, 2021 |
| HP            | ENVY m7 Notebook            | [235fa5cacd](https://linux-hardware.org/?probe=235fa5cacd) | Oct 25, 2021 |
| Dell          | Latitude E6430              | [fa4d12994d](https://linux-hardware.org/?probe=fa4d12994d) | Oct 25, 2021 |
| Schenker      | VIA 15 Pro                  | [7242436545](https://linux-hardware.org/?probe=7242436545) | Oct 24, 2021 |
| Toshiba       | Satellite C70-B             | [a17b7c3888](https://linux-hardware.org/?probe=a17b7c3888) | Oct 24, 2021 |
| Thomson       | N17C512                     | [20abb09d3a](https://linux-hardware.org/?probe=20abb09d3a) | Oct 24, 2021 |
| Notebook      | X170SM                      | [2054d0dee6](https://linux-hardware.org/?probe=2054d0dee6) | Oct 24, 2021 |
| Notebook      | X170SM                      | [f704af17a3](https://linux-hardware.org/?probe=f704af17a3) | Oct 24, 2021 |
| Dell          | Latitude D630               | [1cfebe8169](https://linux-hardware.org/?probe=1cfebe8169) | Oct 23, 2021 |
| Dell          | Latitude E6410              | [f4cdc942dc](https://linux-hardware.org/?probe=f4cdc942dc) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [db85bd77fc](https://linux-hardware.org/?probe=db85bd77fc) | Oct 23, 2021 |
| HP            | ProBook 6550b               | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | [248ab157b8](https://linux-hardware.org/?probe=248ab157b8) | Oct 23, 2021 |
| HP            | Notebook                    | [11013f1334](https://linux-hardware.org/?probe=11013f1334) | Oct 22, 2021 |
| Google        | Kindred                     | [675265477a](https://linux-hardware.org/?probe=675265477a) | Oct 22, 2021 |
| HP            | 255 G4 Notebook PC          | [e7e49e8cc0](https://linux-hardware.org/?probe=e7e49e8cc0) | Oct 22, 2021 |
| Dell          | Latitude E7470              | [061c5e449c](https://linux-hardware.org/?probe=061c5e449c) | Oct 22, 2021 |
| MSI           | Modern 14 B10MW             | [ae43e74753](https://linux-hardware.org/?probe=ae43e74753) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [8668abcc62](https://linux-hardware.org/?probe=8668abcc62) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [18cf55aa72](https://linux-hardware.org/?probe=18cf55aa72) | Oct 21, 2021 |
| Toshiba       | Satellite L755              | [985ff9ba03](https://linux-hardware.org/?probe=985ff9ba03) | Oct 21, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | [6d2d97674c](https://linux-hardware.org/?probe=6d2d97674c) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | [facdd98487](https://linux-hardware.org/?probe=facdd98487) | Oct 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [961f066acf](https://linux-hardware.org/?probe=961f066acf) | Oct 19, 2021 |
| Dell          | Latitude E7470              | [fdc6203a6e](https://linux-hardware.org/?probe=fdc6203a6e) | Oct 18, 2021 |
| Dell          | Latitude E6420              | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6210b749a1](https://linux-hardware.org/?probe=6210b749a1) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dbf1e020b0](https://linux-hardware.org/?probe=dbf1e020b0) | Oct 18, 2021 |
| Dell          | Inspiron 3521               | [2ffe8489e1](https://linux-hardware.org/?probe=2ffe8489e1) | Oct 18, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [10f8e5f5cf](https://linux-hardware.org/?probe=10f8e5f5cf) | Oct 17, 2021 |
| Acer          | Aspire R3-131T              | [014464c088](https://linux-hardware.org/?probe=014464c088) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [15ce74dcd6](https://linux-hardware.org/?probe=15ce74dcd6) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [97c3495c65](https://linux-hardware.org/?probe=97c3495c65) | Oct 17, 2021 |
| Unknown       | CherryTrail                 | [01d095b201](https://linux-hardware.org/?probe=01d095b201) | Oct 17, 2021 |
| Acer          | Aspire E5-571               | [76090a2652](https://linux-hardware.org/?probe=76090a2652) | Oct 16, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [ff6de8e062](https://linux-hardware.org/?probe=ff6de8e062) | Oct 16, 2021 |
| Lenovo        | G50-70 20351                | [d0d0d99be6](https://linux-hardware.org/?probe=d0d0d99be6) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | [4fc5c2f99f](https://linux-hardware.org/?probe=4fc5c2f99f) | Oct 16, 2021 |
| Dell          | Latitude E7440              | [cfe53904bc](https://linux-hardware.org/?probe=cfe53904bc) | Oct 16, 2021 |
| Unknown       | Unknown                     | [3233e1293c](https://linux-hardware.org/?probe=3233e1293c) | Oct 15, 2021 |
| Acer          | Aspire E5-576G              | [6f17f5d2c0](https://linux-hardware.org/?probe=6f17f5d2c0) | Oct 15, 2021 |
| HP            | ENVY m7 Notebook            | [f0af05f6f9](https://linux-hardware.org/?probe=f0af05f6f9) | Oct 15, 2021 |
| Unknown       | Unknown                     | [ddc6d80716](https://linux-hardware.org/?probe=ddc6d80716) | Oct 15, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [3f90ae6d67](https://linux-hardware.org/?probe=3f90ae6d67) | Oct 14, 2021 |
| Dell          | Latitude E6420              | [14b08ab14d](https://linux-hardware.org/?probe=14b08ab14d) | Oct 14, 2021 |
| ASUSTek       | GL702VI                     | [c342d6fdc1](https://linux-hardware.org/?probe=c342d6fdc1) | Oct 14, 2021 |
| HP            | 15                          | [5534f9e3fc](https://linux-hardware.org/?probe=5534f9e3fc) | Oct 14, 2021 |
| Acer          | Swift SF314-59              | [2cd9b13bb1](https://linux-hardware.org/?probe=2cd9b13bb1) | Oct 14, 2021 |
| HP            | 15                          | [bfc196e22b](https://linux-hardware.org/?probe=bfc196e22b) | Oct 13, 2021 |
| ASUSTek       | X501A1                      | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Dell          | Inspiron 5721               | [a13d0383b6](https://linux-hardware.org/?probe=a13d0383b6) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | [686377ccd0](https://linux-hardware.org/?probe=686377ccd0) | Oct 12, 2021 |
| HP            | EliteBook 840 G1            | [9bb8ba744e](https://linux-hardware.org/?probe=9bb8ba744e) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [01a3f25bec](https://linux-hardware.org/?probe=01a3f25bec) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [d8de6fc953](https://linux-hardware.org/?probe=d8de6fc953) | Oct 12, 2021 |
| Giani Limi... | ENY1158M                    | [1f9a85e980](https://linux-hardware.org/?probe=1f9a85e980) | Oct 11, 2021 |
| Giani Limi... | ENY1158M                    | [4516242881](https://linux-hardware.org/?probe=4516242881) | Oct 11, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [471414140c](https://linux-hardware.org/?probe=471414140c) | Oct 11, 2021 |
| Unknown       | Z3735F-T02 V1.2             | [6ef4e9edf6](https://linux-hardware.org/?probe=6ef4e9edf6) | Oct 11, 2021 |
| Dell          | Inspiron 3537               | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f5147cd609](https://linux-hardware.org/?probe=f5147cd609) | Oct 10, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [e1a73cbf10](https://linux-hardware.org/?probe=e1a73cbf10) | Oct 09, 2021 |
| Samsung       | 700Z3C/700Z5C               | [007ba2bac1](https://linux-hardware.org/?probe=007ba2bac1) | Oct 09, 2021 |
| Acer          | Aspire E5-571               | [e988105956](https://linux-hardware.org/?probe=e988105956) | Oct 09, 2021 |
| ASUSTek       | X555YA                      | [7bbcc6c5af](https://linux-hardware.org/?probe=7bbcc6c5af) | Oct 09, 2021 |
| HP            | Laptop 17z-cp000            | [db7c1566db](https://linux-hardware.org/?probe=db7c1566db) | Oct 09, 2021 |
| HP            | ENVY dv6                    | [21a3477c3d](https://linux-hardware.org/?probe=21a3477c3d) | Oct 08, 2021 |
| MSI           | GE66 Raider 10UH            | [43c72c2ff3](https://linux-hardware.org/?probe=43c72c2ff3) | Oct 08, 2021 |
| HP            | Unknown                     | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| Acer          | TravelMate P259-MG          | [c62543cf86](https://linux-hardware.org/?probe=c62543cf86) | Oct 07, 2021 |
| HP            | Laptop 15s-fq1xxx           | [b81ab61049](https://linux-hardware.org/?probe=b81ab61049) | Oct 07, 2021 |
| Lenovo        | Z50-75 80EC                 | [2550a17ad0](https://linux-hardware.org/?probe=2550a17ad0) | Oct 07, 2021 |
| Star Labs     | LabTop                      | [711f2b9e6d](https://linux-hardware.org/?probe=711f2b9e6d) | Oct 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ae113c0df0](https://linux-hardware.org/?probe=ae113c0df0) | Oct 06, 2021 |
| Dell          | Latitude E5400              | [6878f58676](https://linux-hardware.org/?probe=6878f58676) | Oct 06, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a87e581c64](https://linux-hardware.org/?probe=a87e581c64) | Oct 06, 2021 |
| Dell          | Latitude E5400              | [b69897eca3](https://linux-hardware.org/?probe=b69897eca3) | Oct 06, 2021 |
| Dell          | Latitude E5530 non-vPro     | [afe8fca994](https://linux-hardware.org/?probe=afe8fca994) | Oct 06, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [dc9074514c](https://linux-hardware.org/?probe=dc9074514c) | Oct 06, 2021 |
| ASUSTek       | X550LB                      | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6717c35dc9](https://linux-hardware.org/?probe=6717c35dc9) | Oct 05, 2021 |
| Dell          | Inspiron 3542               | [f67c2f8d32](https://linux-hardware.org/?probe=f67c2f8d32) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| Dell          | Inspiron 3521               | [9e18ebff31](https://linux-hardware.org/?probe=9e18ebff31) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [ccc6db1c41](https://linux-hardware.org/?probe=ccc6db1c41) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [55ec005acb](https://linux-hardware.org/?probe=55ec005acb) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| HP            | ProBook 430 G1              | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Toshiba       | Satellite C70-B             | [2d4b467fdc](https://linux-hardware.org/?probe=2d4b467fdc) | Oct 04, 2021 |
| Dell          | Latitude E5570              | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | EliteBook 8440p             | [0890806446](https://linux-hardware.org/?probe=0890806446) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [6d94d45cf0](https://linux-hardware.org/?probe=6d94d45cf0) | Oct 04, 2021 |
| Dell          | Latitude 7390               | [50080eb85e](https://linux-hardware.org/?probe=50080eb85e) | Oct 03, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [a2ee189c63](https://linux-hardware.org/?probe=a2ee189c63) | Oct 03, 2021 |
| Dell          | Inspiron 7773               | [2713f21dd7](https://linux-hardware.org/?probe=2713f21dd7) | Oct 03, 2021 |
| Dell          | Latitude E5400              | [ffc2d5a399](https://linux-hardware.org/?probe=ffc2d5a399) | Oct 03, 2021 |
| Toshiba       | Satellite L455D             | [9413906eaa](https://linux-hardware.org/?probe=9413906eaa) | Oct 03, 2021 |
| Dell          | Inspiron 3542               | [e3247b14fa](https://linux-hardware.org/?probe=e3247b14fa) | Oct 02, 2021 |
| Dell          | Latitude E5400              | [529e29fb9d](https://linux-hardware.org/?probe=529e29fb9d) | Oct 02, 2021 |
| Toshiba       | Satellite Pro T110          | [3bd8210e7e](https://linux-hardware.org/?probe=3bd8210e7e) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| Dell          | Latitude E6520              | [e1bf1df5ae](https://linux-hardware.org/?probe=e1bf1df5ae) | Oct 01, 2021 |
| Unknown       | Unknown                     | [f92fca6d48](https://linux-hardware.org/?probe=f92fca6d48) | Oct 01, 2021 |
| Acer          | Nitro AN515-44              | [a7a50b0dbf](https://linux-hardware.org/?probe=a7a50b0dbf) | Oct 01, 2021 |
| Apple         | MacBook5,2                  | [359171629f](https://linux-hardware.org/?probe=359171629f) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [4e125287e4](https://linux-hardware.org/?probe=4e125287e4) | Sep 30, 2021 |
| HP            | EliteBook 830 G5            | [d0c34db7d4](https://linux-hardware.org/?probe=d0c34db7d4) | Sep 29, 2021 |
| HP            | ENVY 15                     | [4b949c1a1b](https://linux-hardware.org/?probe=4b949c1a1b) | Sep 29, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [3688fae067](https://linux-hardware.org/?probe=3688fae067) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [3befe3f6e3](https://linux-hardware.org/?probe=3befe3f6e3) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [cc9cc9e925](https://linux-hardware.org/?probe=cc9cc9e925) | Sep 28, 2021 |
| HP            | Pavilion dv7                | [7e0b76f736](https://linux-hardware.org/?probe=7e0b76f736) | Sep 28, 2021 |
| Acer          | Aspire A315-56              | [3fc47b2c92](https://linux-hardware.org/?probe=3fc47b2c92) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| ASUSTek       | X405UA                      | [3a78f7edf5](https://linux-hardware.org/?probe=3a78f7edf5) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| Lenovo        | ThinkPad T520 4242W19       | [0bbb8d9004](https://linux-hardware.org/?probe=0bbb8d9004) | Sep 26, 2021 |
| Acer          | Aspire 5738                 | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| Acer          | Aspire V3-571G              | [8bc152aa27](https://linux-hardware.org/?probe=8bc152aa27) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [5404d5874a](https://linux-hardware.org/?probe=5404d5874a) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Dell          | Latitude E6220              | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | [9d3daebd14](https://linux-hardware.org/?probe=9d3daebd14) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6b6f1c017d](https://linux-hardware.org/?probe=6b6f1c017d) | Sep 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [953ed13df8](https://linux-hardware.org/?probe=953ed13df8) | Sep 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | [a65f8af3ac](https://linux-hardware.org/?probe=a65f8af3ac) | Sep 24, 2021 |
| Apple         | MacBookPro14,1              | [2d0d6ceff3](https://linux-hardware.org/?probe=2d0d6ceff3) | Sep 24, 2021 |
| Kogan         | KAL11C250SB                 | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1af2027db5](https://linux-hardware.org/?probe=1af2027db5) | Sep 24, 2021 |
| Dell          | Latitude E6430              | [5e66bde0c9](https://linux-hardware.org/?probe=5e66bde0c9) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| HP            | Presario V6000 (GM018UA#... | [944d6af89a](https://linux-hardware.org/?probe=944d6af89a) | Sep 23, 2021 |
| MSI           | Modern 15 A11M              | [fe99af6254](https://linux-hardware.org/?probe=fe99af6254) | Sep 23, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [4d2aa790e0](https://linux-hardware.org/?probe=4d2aa790e0) | Sep 23, 2021 |
| Apple         | MacBookPro9,2               | [effa7b0365](https://linux-hardware.org/?probe=effa7b0365) | Sep 22, 2021 |
| Dynabook      | PORTEGE A30-E               | [93fd738472](https://linux-hardware.org/?probe=93fd738472) | Sep 21, 2021 |
| Dynabook      | PORTEGE A30-E               | [0ec5acd020](https://linux-hardware.org/?probe=0ec5acd020) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [a43f2dc4bf](https://linux-hardware.org/?probe=a43f2dc4bf) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [069c0cafd0](https://linux-hardware.org/?probe=069c0cafd0) | Sep 21, 2021 |
| Toshiba       | Satellite L755              | [10baeecbf5](https://linux-hardware.org/?probe=10baeecbf5) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [699803b74c](https://linux-hardware.org/?probe=699803b74c) | Sep 21, 2021 |
| UNOWHY        | Y13G011S4EI                 | [70511c9675](https://linux-hardware.org/?probe=70511c9675) | Sep 21, 2021 |
| Lenovo        | G580                        | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [91055c07be](https://linux-hardware.org/?probe=91055c07be) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | [ae16407ef3](https://linux-hardware.org/?probe=ae16407ef3) | Sep 20, 2021 |
| Acer          | Aspire E1-532               | [b0407bdd1c](https://linux-hardware.org/?probe=b0407bdd1c) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| TianBei       | TB-H7                       | [06300b96a7](https://linux-hardware.org/?probe=06300b96a7) | Sep 19, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| Apple         | MacBookPro9,2               | [37f34b16c5](https://linux-hardware.org/?probe=37f34b16c5) | Sep 19, 2021 |
| Acer          | Aspire 4352                 | [3a9aedb538](https://linux-hardware.org/?probe=3a9aedb538) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| Dell          | XPS 13 9350                 | [4dda7e9a7e](https://linux-hardware.org/?probe=4dda7e9a7e) | Sep 18, 2021 |
| ASUSTek       | U31F                        | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Dell          | System XPS L321X            | [2345076968](https://linux-hardware.org/?probe=2345076968) | Sep 18, 2021 |
| Dell          | Latitude E6430              | [2d96c4a645](https://linux-hardware.org/?probe=2d96c4a645) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [42d68963c6](https://linux-hardware.org/?probe=42d68963c6) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [50f90e7684](https://linux-hardware.org/?probe=50f90e7684) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [73a4cd0692](https://linux-hardware.org/?probe=73a4cd0692) | Sep 17, 2021 |
| HP            | Unknown                     | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [518209a322](https://linux-hardware.org/?probe=518209a322) | Sep 17, 2021 |
| Dell          | Latitude E5470              | [9a036a26a4](https://linux-hardware.org/?probe=9a036a26a4) | Sep 17, 2021 |
| Dell          | Latitude E5500              | [286c99863b](https://linux-hardware.org/?probe=286c99863b) | Sep 16, 2021 |
| HP            | 245 G5 Notebook PC          | [ece740cf39](https://linux-hardware.org/?probe=ece740cf39) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [04ba56c326](https://linux-hardware.org/?probe=04ba56c326) | Sep 16, 2021 |
| Toshiba       | Satellite C75D-B            | [152dd3680d](https://linux-hardware.org/?probe=152dd3680d) | Sep 16, 2021 |
| Jumper        | EZpad .A002                 | [c62d842a68](https://linux-hardware.org/?probe=c62d842a68) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [6d381b570b](https://linux-hardware.org/?probe=6d381b570b) | Sep 15, 2021 |
| HP            | 255 G4 Notebook PC          | [c8a384ed00](https://linux-hardware.org/?probe=c8a384ed00) | Sep 15, 2021 |
| HP            | EliteBook 840 G5            | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Latitude E7440              | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| Dell          | Latitude E6520              | [1bd8b6a82f](https://linux-hardware.org/?probe=1bd8b6a82f) | Sep 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [983922cfbf](https://linux-hardware.org/?probe=983922cfbf) | Sep 15, 2021 |
| Acer          | Aspire 5733Z                | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Notebook                    | [d6825ad86c](https://linux-hardware.org/?probe=d6825ad86c) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Sony          | VGN-SR5                     | [199ae9a9dd](https://linux-hardware.org/?probe=199ae9a9dd) | Sep 14, 2021 |
| Sony          | VPCF215FX                   | [173d8636d4](https://linux-hardware.org/?probe=173d8636d4) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | [b054524aac](https://linux-hardware.org/?probe=b054524aac) | Sep 14, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | [864dde8a99](https://linux-hardware.org/?probe=864dde8a99) | Sep 13, 2021 |
| Toshiba       | Satellite C870-1C2          | [3818ff8f07](https://linux-hardware.org/?probe=3818ff8f07) | Sep 12, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [6a980ac620](https://linux-hardware.org/?probe=6a980ac620) | Sep 12, 2021 |
| Dell          | Latitude E6430              | [aff84b5ec1](https://linux-hardware.org/?probe=aff84b5ec1) | Sep 12, 2021 |
| Google        | Kindred                     | [c9ee8560b8](https://linux-hardware.org/?probe=c9ee8560b8) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [404d33775d](https://linux-hardware.org/?probe=404d33775d) | Sep 12, 2021 |
| Dell          | Latitude E5500              | [1e20247950](https://linux-hardware.org/?probe=1e20247950) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [3dcddbd59e](https://linux-hardware.org/?probe=3dcddbd59e) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| HP            | Laptop 15-dy1xxx            | [728e0facd6](https://linux-hardware.org/?probe=728e0facd6) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [33fd6d8c8f](https://linux-hardware.org/?probe=33fd6d8c8f) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [fa33f94b27](https://linux-hardware.org/?probe=fa33f94b27) | Sep 11, 2021 |
| MSI           | GE75 Raider 8RF             | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| Toshiba       | Satellite Pro L450D         | [a15c916899](https://linux-hardware.org/?probe=a15c916899) | Sep 10, 2021 |
| Toshiba       | Satellite C850-1CP          | [8cec9884a8](https://linux-hardware.org/?probe=8cec9884a8) | Sep 10, 2021 |
| Unknown       | Unknown                     | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [f6d8fa5367](https://linux-hardware.org/?probe=f6d8fa5367) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [87b52d41c7](https://linux-hardware.org/?probe=87b52d41c7) | Sep 10, 2021 |
| HP            | Notebook                    | [24690d1b8b](https://linux-hardware.org/?probe=24690d1b8b) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| HP            | 255 G7 Notebook PC          | [6ab68f26ba](https://linux-hardware.org/?probe=6ab68f26ba) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | [ccb4dc3d9a](https://linux-hardware.org/?probe=ccb4dc3d9a) | Sep 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 20RAS1Q800     | [a4d93ee5d2](https://linux-hardware.org/?probe=a4d93ee5d2) | Sep 08, 2021 |
| HP            | EliteBook 8560p             | [6bff88fb9e](https://linux-hardware.org/?probe=6bff88fb9e) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [3fc588a18d](https://linux-hardware.org/?probe=3fc588a18d) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [fd38e5bf9d](https://linux-hardware.org/?probe=fd38e5bf9d) | Sep 08, 2021 |
| HP            | EliteBook 840 G3            | [22d88098a9](https://linux-hardware.org/?probe=22d88098a9) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [47317abce2](https://linux-hardware.org/?probe=47317abce2) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [98874d48b2](https://linux-hardware.org/?probe=98874d48b2) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f872b42a74](https://linux-hardware.org/?probe=f872b42a74) | Sep 07, 2021 |
| Acer          | V5-171                      | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| HP            | Notebook                    | [62a2618cde](https://linux-hardware.org/?probe=62a2618cde) | Sep 07, 2021 |
| Toshiba       | Satellite L755              | [92d22f65bf](https://linux-hardware.org/?probe=92d22f65bf) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Dell          | Precision 3520              | [15e6e2c91d](https://linux-hardware.org/?probe=15e6e2c91d) | Sep 07, 2021 |
| Dell          | Precision 5550              | [8ae36d685d](https://linux-hardware.org/?probe=8ae36d685d) | Sep 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | [368f488133](https://linux-hardware.org/?probe=368f488133) | Sep 07, 2021 |
| MSI           | GL62 7RDX                   | [be53fd4c86](https://linux-hardware.org/?probe=be53fd4c86) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| HP            | Pavilion dv5                | [27607d962e](https://linux-hardware.org/?probe=27607d962e) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | [46499caf7a](https://linux-hardware.org/?probe=46499caf7a) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Lenovo        | G505s 20255                 | [263eeefef0](https://linux-hardware.org/?probe=263eeefef0) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | [8cd745db58](https://linux-hardware.org/?probe=8cd745db58) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | 255 G3                      | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Acer          | Aspire A315-31              | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| HP            | EliteBook 840 G1            | [980716e0a8](https://linux-hardware.org/?probe=980716e0a8) | Sep 03, 2021 |
| ASUSTek       | GR8                         | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire E5-521G              | [d1aa71f003](https://linux-hardware.org/?probe=d1aa71f003) | Sep 02, 2021 |
| Acer          | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Acer          | Aspire E1-522               | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Toshiba       | Satellite C850D-11C         | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | ENVY 15                     | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Insyde        | i101c                       | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | Pavilion 15                 | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Acer          | Aspire 5100                 | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Acer          | AO722                       | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| TianBei       | TB-H7                       | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| Acer          | Aspire 8940G                | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| HP            | ProBook 450 G2              | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| Acer          | Nitro AN515-55              | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| Acer          | Swift SF114-34              | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| HP            | ProBook 450 G2              | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| Dell          | Inspiron 7537               | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Dell          | XPS L501X                   | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| Dell          | Inspiron 3582               | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| Dell          | XPS 13 9370                 | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Dell          | Inspiron 3582               | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| HP            | ProBook 650 G2              | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| HP            | Unknown                     | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| Razer         | Book 13 - RZ09-0357         | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Dell          | Vostro 5490                 | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.11.0-38-generic           | 97        | 9.85%   |
| 5.11.0-27-generic           | 91        | 9.24%   |
| 5.11.0-37-generic           | 67        | 6.8%    |
| 5.11.0-40-generic           | 65        | 6.6%    |
| 5.11.0-41-generic           | 62        | 6.29%   |
| 5.13.0-39-generic           | 59        | 5.99%   |
| 5.13.0-30-generic           | 58        | 5.89%   |
| 5.11.0-34-generic           | 57        | 5.79%   |
| 5.11.0-43-generic           | 56        | 5.69%   |
| 5.13.0-44-generic           | 48        | 4.87%   |
| 5.13.0-40-generic           | 44        | 4.47%   |
| 5.13.0-35-generic           | 41        | 4.16%   |
| 5.13.0-28-generic           | 35        | 3.55%   |
| 5.13.0-27-generic           | 28        | 2.84%   |
| 5.11.0-46-generic           | 26        | 2.64%   |
| 5.13.0-41-generic           | 25        | 2.54%   |
| 5.11.0-36-generic           | 22        | 2.23%   |
| 5.11.0-44-generic           | 18        | 1.83%   |
| 5.13.0-51-generic           | 15        | 1.52%   |
| 5.13.0-37-generic           | 15        | 1.52%   |
| 5.13.0-48-generic           | 11        | 1.12%   |
| 5.11.0-25-generic           | 9         | 0.91%   |
| 5.8.0-53-generic            | 6         | 0.61%   |
| 5.8.0-59-generic            | 5         | 0.51%   |
| 5.8.0-55-generic            | 5         | 0.51%   |
| 5.8.0-50-generic            | 4         | 0.41%   |
| 5.8.0-63-generic            | 1         | 0.1%    |
| 5.8.0-49-generic            | 1         | 0.1%    |
| 5.16.12-051612-generic      | 1         | 0.1%    |
| 5.16.0-051600rc8-lowlatency | 1         | 0.1%    |
| 5.16.0-051600rc4-generic    | 1         | 0.1%    |
| 5.15.49-xanmod1             | 1         | 0.1%    |
| 5.15.24-xanmod1             | 1         | 0.1%    |
| 5.15.0-8.1-liquorix-amd64   | 1         | 0.1%    |
| 5.14.0-15.1-liquorix-amd64  | 1         | 0.1%    |
| 5.14.0-1038-oem             | 1         | 0.1%    |
| 5.14.0-1033-oem             | 1         | 0.1%    |
| 5.13.18-xanmod1             | 1         | 0.1%    |
| 5.13.0-25-generic           | 1         | 0.1%    |
| 5.13.0-1020-oem             | 1         | 0.1%    |
| 5.10.0-1052-oem             | 1         | 0.1%    |
| 5.10.0-1044-oem             | 1         | 0.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 543       | 58.32%  |
| 5.13.0  | 354       | 38.02%  |
| 5.8.0   | 22        | 2.36%   |
| 5.14.0  | 3         | 0.32%   |
| 5.16.0  | 2         | 0.21%   |
| 5.10.0  | 2         | 0.21%   |
| 5.16.12 | 1         | 0.11%   |
| 5.15.49 | 1         | 0.11%   |
| 5.15.24 | 1         | 0.11%   |
| 5.15.0  | 1         | 0.11%   |
| 5.13.18 | 1         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 543       | 58.32%  |
| 5.13    | 355       | 38.13%  |
| 5.8     | 22        | 2.36%   |
| 5.16    | 3         | 0.32%   |
| 5.15    | 3         | 0.32%   |
| 5.14    | 3         | 0.32%   |
| 5.10    | 2         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 900       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 813       | 89.83%  |
| XFCE       | 81        | 8.95%   |
| Unknown    | 6         | 0.66%   |
| X-Cinnamon | 2         | 0.22%   |
| KDE5       | 1         | 0.11%   |
| KDE        | 1         | 0.11%   |
| Cinnamon   | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 888       | 98.01%  |
| Wayland | 16        | 1.77%   |
| Unknown | 2         | 0.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 693       | 76.32%  |
| GDM3    | 98        | 10.79%  |
| GDM     | 94        | 10.35%  |
| LightDM | 22        | 2.42%   |
| SDDM    | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 351       | 38.78%  |
| de_DE | 79        | 8.73%   |
| en_GB | 64        | 7.07%   |
| pt_BR | 56        | 6.19%   |
| es_ES | 32        | 3.54%   |
| en_IN | 32        | 3.54%   |
| en_CA | 27        | 2.98%   |
| fr_FR | 26        | 2.87%   |
| pl_PL | 20        | 2.21%   |
| it_IT | 20        | 2.21%   |
| es_MX | 19        | 2.1%    |
| en_AU | 17        | 1.88%   |
| nl_NL | 16        | 1.77%   |
| ru_RU | 14        | 1.55%   |
| en_ZA | 13        | 1.44%   |
| pt_PT | 11        | 1.22%   |
| cs_CZ | 11        | 1.22%   |
| fr_BE | 10        | 1.1%    |
| sv_SE | 7         | 0.77%   |
| es_CL | 7         | 0.77%   |
| tr_TR | 5         | 0.55%   |
| en_NZ | 5         | 0.55%   |
| de_AT | 5         | 0.55%   |
| nl_BE | 4         | 0.44%   |
| es_CO | 4         | 0.44%   |
| hu_HU | 3         | 0.33%   |
| es_AR | 3         | 0.33%   |
| el_GR | 3         | 0.33%   |
| de_CH | 3         | 0.33%   |
| bg_BG | 3         | 0.33%   |
| ar_EG | 3         | 0.33%   |
| ru_UA | 2         | 0.22%   |
| nb_NO | 2         | 0.22%   |
| lt_LT | 2         | 0.22%   |
| ja_JP | 2         | 0.22%   |
| hr_HR | 2         | 0.22%   |
| es_PE | 2         | 0.22%   |
| es_EC | 2         | 0.22%   |
| es_BO | 2         | 0.22%   |
| en_PH | 2         | 0.22%   |
| en_IL | 2         | 0.22%   |
| sl_SI | 1         | 0.11%   |
| sk_SK | 1         | 0.11%   |
| ro_RO | 1         | 0.11%   |
| fr_CA | 1         | 0.11%   |
| fi_FI | 1         | 0.11%   |
| es_UY | 1         | 0.11%   |
| es_PA | 1         | 0.11%   |
| es_CR | 1         | 0.11%   |
| en_SG | 1         | 0.11%   |
| en_IE | 1         | 0.11%   |
| da_DK | 1         | 0.11%   |
| C     | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 536       | 59.03%  |
| BIOS | 372       | 40.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 855       | 94.68%  |
| Zfs     | 16        | 1.77%   |
| Overlay | 15        | 1.66%   |
| Btrfs   | 13        | 1.44%   |
| Xfs     | 3         | 0.33%   |
| Ext2    | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 791       | 87.31%  |
| GPT     | 94        | 10.38%  |
| MBR     | 21        | 2.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 887       | 98.34%  |
| Yes       | 15        | 1.66%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 822       | 90.93%  |
| Yes       | 82        | 9.07%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 193       | 21.44%  |
| Lenovo                  | 150       | 16.67%  |
| Dell                    | 143       | 15.89%  |
| ASUSTek Computer        | 114       | 12.67%  |
| Acer                    | 77        | 8.56%   |
| Toshiba                 | 47        | 5.22%   |
| Apple                   | 21        | 2.33%   |
| MSI                     | 15        | 1.67%   |
| Sony                    | 14        | 1.56%   |
| Samsung Electronics     | 13        | 1.44%   |
| Unknown                 | 11        | 1.22%   |
| Google                  | 8         | 0.89%   |
| Packard Bell            | 6         | 0.67%   |
| Notebook                | 5         | 0.56%   |
| HUAWEI                  | 5         | 0.56%   |
| Razer                   | 4         | 0.44%   |
| Positivo                | 4         | 0.44%   |
| LG Electronics          | 4         | 0.44%   |
| Fujitsu Siemens         | 4         | 0.44%   |
| Fujitsu                 | 4         | 0.44%   |
| Chuwi                   | 4         | 0.44%   |
| Multilaser              | 3         | 0.33%   |
| Medion                  | 3         | 0.33%   |
| Jumper                  | 3         | 0.33%   |
| Insyde                  | 3         | 0.33%   |
| TUXEDO                  | 2         | 0.22%   |
| Thomson                 | 2         | 0.22%   |
| GPU Company             | 2         | 0.22%   |
| Gateway                 | 2         | 0.22%   |
| Digibras                | 2         | 0.22%   |
| UNOWHY                  | 1         | 0.11%   |
| TrekStor                | 1         | 0.11%   |
| TianBei                 | 1         | 0.11%   |
| TCL Communication       | 1         | 0.11%   |
| Star Labs               | 1         | 0.11%   |
| Schenker                | 1         | 0.11%   |
| RCA                     | 1         | 0.11%   |
| Primux Tech             | 1         | 0.11%   |
| Primux                  | 1         | 0.11%   |
| Novatech                | 1         | 0.11%   |
| NEC Computers           | 1         | 0.11%   |
| mPTech                  | 1         | 0.11%   |
| Mediacom                | 1         | 0.11%   |
| MECER                   | 1         | 0.11%   |
| Login Informatica       | 1         | 0.11%   |
| Kogan                   | 1         | 0.11%   |
| Insignia                | 1         | 0.11%   |
| Global Distribution FZE | 1         | 0.11%   |
| Gigabyte Technology     | 1         | 0.11%   |
| Giani Limited           | 1         | 0.11%   |
| GEO                     | 1         | 0.11%   |
| Fusion5                 | 1         | 0.11%   |
| Framework               | 1         | 0.11%   |
| Ematic                  | 1         | 0.11%   |
| E-shop.gr               | 1         | 0.11%   |
| Dynabook                | 1         | 0.11%   |
| Compaq                  | 1         | 0.11%   |
| Clevo                   | 1         | 0.11%   |
| AXDIA International     | 1         | 0.11%   |
| Avell High Performance  | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP Notebook                                           | 13        | 1.44%   |
| Unknown                                               | 13        | 1.44%   |
| HP Pavilion Notebook                                  | 7         | 0.78%   |
| HP 15                                                 | 6         | 0.67%   |
| HP Pavilion dv7                                       | 4         | 0.44%   |
| HP Pavilion 15                                        | 4         | 0.44%   |
| HP Laptop 15-bw0xx                                    | 4         | 0.44%   |
| Dell Latitude E7440                                   | 4         | 0.44%   |
| Apple MacBookPro8,1                                   | 4         | 0.44%   |
| Toshiba Satellite C55-C                               | 3         | 0.33%   |
| Lenovo Yoga 3 Pro-1370 80HE                           | 3         | 0.33%   |
| Lenovo IdeaPad S340-14API 81NB                        | 3         | 0.33%   |
| Lenovo IdeaPad S145-15API 81V7                        | 3         | 0.33%   |
| Lenovo IdeaPad Flex-14API 81SS                        | 3         | 0.33%   |
| Lenovo G50-70 20351                                   | 3         | 0.33%   |
| HUAWEI NBLK-WAX9X                                     | 3         | 0.33%   |
| HP ProBook 640 G1                                     | 3         | 0.33%   |
| HP Pavilion g6                                        | 3         | 0.33%   |
| HP Pavilion dv6                                       | 3         | 0.33%   |
| HP OMEN by Laptop 15-dc1xxx                           | 3         | 0.33%   |
| HP EliteBook 840 G1                                   | 3         | 0.33%   |
| Dell Latitude E6430                                   | 3         | 0.33%   |
| Dell Latitude E6420                                   | 3         | 0.33%   |
| Dell Latitude E5500                                   | 3         | 0.33%   |
| Dell Latitude 3440                                    | 3         | 0.33%   |
| Apple MacBookPro11,1                                  | 3         | 0.33%   |
| Acer V5-171                                           | 3         | 0.33%   |
| Acer Aspire E1-522                                    | 3         | 0.33%   |
| Toshiba Satellite C660                                | 2         | 0.22%   |
| Toshiba Satellite A200                                | 2         | 0.22%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 2         | 0.22%   |
| Packard Bell EasyNote TK85                            | 2         | 0.22%   |
| Lenovo V14-IIL 82C4                                   | 2         | 0.22%   |
| Lenovo IdeaPad Yoga 13 20175                          | 2         | 0.22%   |
| Lenovo IdeaPad 330-15IKB 81DE                         | 2         | 0.22%   |
| Lenovo IdeaPad 3 15IIL05 81WE                         | 2         | 0.22%   |
| Lenovo G560 0679                                      | 2         | 0.22%   |
| Lenovo G500 20236                                     | 2         | 0.22%   |
| Lenovo G50-30 80G0                                    | 2         | 0.22%   |
| Jumper EZbook                                         | 2         | 0.22%   |
| Insyde i101c                                          | 2         | 0.22%   |
| HP ProBook 6450b                                      | 2         | 0.22%   |
| HP ProBook 4530s                                      | 2         | 0.22%   |
| HP ProBook 450 G2                                     | 2         | 0.22%   |
| HP Pavilion Laptop 15-cs3xxx                          | 2         | 0.22%   |
| HP Pavilion dv5                                       | 2         | 0.22%   |
| HP Pavilion dv3                                       | 2         | 0.22%   |
| HP Pavilion 17                                        | 2         | 0.22%   |
| HP OMEN Notebook                                      | 2         | 0.22%   |
| HP Laptop 15-db0xxx                                   | 2         | 0.22%   |
| HP ENVY Sleekbook 4 PC                                | 2         | 0.22%   |
| HP EliteBook Folio 9470m                              | 2         | 0.22%   |
| HP EliteBook 8760w                                    | 2         | 0.22%   |
| HP EliteBook 8460p                                    | 2         | 0.22%   |
| HP EliteBook 8440p                                    | 2         | 0.22%   |
| HP EliteBook 2570p                                    | 2         | 0.22%   |
| HP Compaq 8510p                                       | 2         | 0.22%   |
| HP 255 G8 Notebook PC                                 | 2         | 0.22%   |
| GPU Company GWTC116-2                                 | 2         | 0.22%   |
| Google Kindred                                        | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 59        | 6.56%   |
| Dell Latitude           | 59        | 6.56%   |
| Acer Aspire             | 54        | 6%      |
| Dell Inspiron           | 48        | 5.33%   |
| Lenovo IdeaPad          | 45        | 5%      |
| HP Pavilion             | 43        | 4.78%   |
| Toshiba Satellite       | 37        | 4.11%   |
| HP EliteBook            | 27        | 3%      |
| HP ProBook              | 24        | 2.67%   |
| HP Laptop               | 18        | 2%      |
| ASUS VivoBook           | 18        | 2%      |
| HP Notebook             | 13        | 1.44%   |
| Unknown                 | 13        | 1.44%   |
| Dell XPS                | 11        | 1.22%   |
| HP ENVY                 | 10        | 1.11%   |
| HP OMEN                 | 9         | 1%      |
| HP Compaq               | 9         | 1%      |
| Dell Vostro             | 9         | 1%      |
| Dell Precision          | 8         | 0.89%   |
| ASUS ZenBook            | 8         | 0.89%   |
| HP Stream               | 7         | 0.78%   |
| HP 15                   | 7         | 0.78%   |
| HP 255                  | 6         | 0.67%   |
| ASUS ROG                | 6         | 0.67%   |
| ASUS ASUS               | 6         | 0.67%   |
| Acer Swift              | 6         | 0.67%   |
| Packard Bell EasyNote   | 5         | 0.56%   |
| Lenovo Yoga             | 5         | 0.56%   |
| Apple MacBookPro11      | 5         | 0.56%   |
| Toshiba PORTEGE         | 4         | 0.44%   |
| Lenovo ThinkBook        | 4         | 0.44%   |
| HP ZBook                | 4         | 0.44%   |
| Fujitsu LIFEBOOK        | 4         | 0.44%   |
| ASUS TUF                | 4         | 0.44%   |
| Apple MacBookPro8       | 4         | 0.44%   |
| Acer Nitro              | 4         | 0.44%   |
| Toshiba TECRA           | 3         | 0.33%   |
| Razer Blade             | 3         | 0.33%   |
| Lenovo Legion           | 3         | 0.33%   |
| Lenovo G50-70           | 3         | 0.33%   |
| HUAWEI NBLK-WAX9X       | 3         | 0.33%   |
| Fujitsu Siemens ESPRIMO | 3         | 0.33%   |
| Chuwi GemiBook          | 3         | 0.33%   |
| Acer V5-171             | 3         | 0.33%   |
| Toshiba QOSMIO          | 2         | 0.22%   |
| Samsung 300E5EV         | 2         | 0.22%   |
| MSI Modern              | 2         | 0.22%   |
| MSI GF63                | 2         | 0.22%   |
| MSI GE75                | 2         | 0.22%   |
| Lenovo V14-IIL          | 2         | 0.22%   |
| Lenovo G780             | 2         | 0.22%   |
| Lenovo G580             | 2         | 0.22%   |
| Lenovo G560             | 2         | 0.22%   |
| Lenovo G500             | 2         | 0.22%   |
| Lenovo G50-30           | 2         | 0.22%   |
| Lenovo Flex             | 2         | 0.22%   |
| Jumper EZbook           | 2         | 0.22%   |
| Insyde i101c            | 2         | 0.22%   |
| GPU Company GWTC116-2   | 2         | 0.22%   |
| Google Kindred          | 2         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 91        | 10.11%  |
| 2012 | 90        | 10%     |
| 2013 | 83        | 9.22%   |
| 2019 | 74        | 8.22%   |
| 2020 | 71        | 7.89%   |
| 2021 | 67        | 7.44%   |
| 2014 | 66        | 7.33%   |
| 2017 | 58        | 6.44%   |
| 2010 | 53        | 5.89%   |
| 2018 | 52        | 5.78%   |
| 2015 | 51        | 5.67%   |
| 2016 | 50        | 5.56%   |
| 2008 | 41        | 4.56%   |
| 2009 | 26        | 2.89%   |
| 2007 | 22        | 2.44%   |
| 2006 | 4         | 0.44%   |
| 2022 | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 900       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 777       | 85.57%  |
| Enabled  | 131       | 14.43%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 891       | 99%     |
| Yes  | 9         | 1%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 311       | 34.56%  |
| 3.01-4.0    | 251       | 27.89%  |
| 8.01-16.0   | 132       | 14.67%  |
| 16.01-24.0  | 93        | 10.33%  |
| 1.01-2.0    | 52        | 5.78%   |
| 32.01-64.0  | 37        | 4.11%   |
| 2.01-3.0    | 13        | 1.44%   |
| 64.01-256.0 | 7         | 0.78%   |
| 24.01-32.0  | 2         | 0.22%   |
| 0.51-1.0    | 2         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 407       | 42.48%  |
| 2.01-3.0   | 312       | 32.57%  |
| 3.01-4.0   | 125       | 13.05%  |
| 4.01-8.0   | 83        | 8.66%   |
| 0.51-1.0   | 20        | 2.09%   |
| 8.01-16.0  | 9         | 0.94%   |
| 24.01-32.0 | 2         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 682       | 74.78%  |
| 2      | 196       | 21.49%  |
| 3      | 24        | 2.63%   |
| 4      | 6         | 0.66%   |
| 0      | 4         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 498       | 55.09%  |
| Yes       | 406       | 44.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 721       | 80.02%  |
| No        | 180       | 19.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 865       | 96.11%  |
| No        | 35        | 3.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 657       | 72.44%  |
| No        | 250       | 27.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 199       | 22.06%  |
| Germany                | 88        | 9.76%   |
| Brazil                 | 67        | 7.43%   |
| UK                     | 50        | 5.54%   |
| Spain                  | 34        | 3.77%   |
| India                  | 33        | 3.66%   |
| Canada                 | 32        | 3.55%   |
| Mexico                 | 24        | 2.66%   |
| France                 | 24        | 2.66%   |
| Netherlands            | 21        | 2.33%   |
| Italy                  | 21        | 2.33%   |
| South Africa           | 18        | 2%      |
| Poland                 | 17        | 1.88%   |
| Belgium                | 17        | 1.88%   |
| Australia              | 16        | 1.77%   |
| Russia                 | 15        | 1.66%   |
| Austria                | 14        | 1.55%   |
| Portugal               | 12        | 1.33%   |
| Sweden                 | 11        | 1.22%   |
| Czechia                | 11        | 1.22%   |
| Turkey                 | 10        | 1.11%   |
| Switzerland            | 9         | 1%      |
| Romania                | 8         | 0.89%   |
| Chile                  | 8         | 0.89%   |
| Norway                 | 7         | 0.78%   |
| Japan                  | 7         | 0.78%   |
| Greece                 | 7         | 0.78%   |
| Colombia               | 6         | 0.67%   |
| Bulgaria               | 6         | 0.67%   |
| New Zealand            | 5         | 0.55%   |
| Indonesia              | 5         | 0.55%   |
| Hungary                | 5         | 0.55%   |
| Argentina              | 5         | 0.55%   |
| Slovenia               | 4         | 0.44%   |
| Morocco                | 4         | 0.44%   |
| Lithuania              | 4         | 0.44%   |
| Kenya                  | 4         | 0.44%   |
| Ireland                | 4         | 0.44%   |
| Ukraine                | 3         | 0.33%   |
| Saudi Arabia           | 3         | 0.33%   |
| Philippines            | 3         | 0.33%   |
| Israel                 | 3         | 0.33%   |
| Finland                | 3         | 0.33%   |
| Croatia                | 3         | 0.33%   |
| Bosnia and Herzegovina | 3         | 0.33%   |
| Vietnam                | 2         | 0.22%   |
| Thailand               | 2         | 0.22%   |
| Singapore              | 2         | 0.22%   |
| Panama                 | 2         | 0.22%   |
| Pakistan               | 2         | 0.22%   |
| Moldova                | 2         | 0.22%   |
| Malaysia               | 2         | 0.22%   |
| Egypt                  | 2         | 0.22%   |
| Ecuador                | 2         | 0.22%   |
| Bolivia                | 2         | 0.22%   |
| Bangladesh             | 2         | 0.22%   |
| Venezuela              | 1         | 0.11%   |
| Uruguay                | 1         | 0.11%   |
| U.S. Virgin Islands    | 1         | 0.11%   |
| Tanzania               | 1         | 0.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Athens            | 8         | 0.86%   |
| Vienna            | 7         | 0.76%   |
| New York          | 7         | 0.76%   |
| Glasgow           | 7         | 0.76%   |
| Sydney            | 6         | 0.65%   |
| Munich            | 5         | 0.54%   |
| Montreal          | 5         | 0.54%   |
| Madrid            | 5         | 0.54%   |
| Johannesburg      | 5         | 0.54%   |
| Dallas            | 5         | 0.54%   |
| Bogotá           | 5         | 0.54%   |
| Berlin            | 5         | 0.54%   |
| Toronto           | 4         | 0.43%   |
| Stockholm         | 4         | 0.43%   |
| Sao Paulo         | 4         | 0.43%   |
| Rome              | 4         | 0.43%   |
| Moscow            | 4         | 0.43%   |
| London            | 4         | 0.43%   |
| Hamburg           | 4         | 0.43%   |
| Frankfurt am Main | 4         | 0.43%   |
| Chicago           | 4         | 0.43%   |
| Bernissart        | 4         | 0.43%   |
| Austin            | 4         | 0.43%   |
| Auckland          | 4         | 0.43%   |
| Amsterdam         | 4         | 0.43%   |
| Zagreb            | 3         | 0.32%   |
| Washington        | 3         | 0.32%   |
| Warsaw            | 3         | 0.32%   |
| Valencia          | 3         | 0.32%   |
| Stuttgart         | 3         | 0.32%   |
| Seattle           | 3         | 0.32%   |
| Sao Luís         | 3         | 0.32%   |
| Salt Lake City    | 3         | 0.32%   |
| Rio de Janeiro    | 3         | 0.32%   |
| Richmond          | 3         | 0.32%   |
| Paris             | 3         | 0.32%   |
| Nairobi           | 3         | 0.32%   |
| Minneapolis       | 3         | 0.32%   |
| Melbourne         | 3         | 0.32%   |
| La Louvière      | 3         | 0.32%   |
| Jakarta           | 3         | 0.32%   |
| Edinburgh         | 3         | 0.32%   |
| Charlotte         | 3         | 0.32%   |
| Cape Town         | 3         | 0.32%   |
| Cancún           | 3         | 0.32%   |
| Brussels          | 3         | 0.32%   |
| Birmingham        | 3         | 0.32%   |
| Bengaluru         | 3         | 0.32%   |
| Barcelona         | 3         | 0.32%   |
| Ankara            | 3         | 0.32%   |
| Zurich            | 2         | 0.22%   |
| Woking            | 2         | 0.22%   |
| Viña del Mar     | 2         | 0.22%   |
| Vilnius           | 2         | 0.22%   |
| Vila Nova de Gaia | 2         | 0.22%   |
| Velikiye Luki     | 2         | 0.22%   |
| Tel Aviv          | 2         | 0.22%   |
| Taboao da Serra   | 2         | 0.22%   |
| Stavanger         | 2         | 0.22%   |
| St Petersburg     | 2         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 142       | 175    | 13.27%  |
| Samsung Electronics         | 141       | 180    | 13.18%  |
| WDC                         | 121       | 136    | 11.31%  |
| Toshiba                     | 106       | 115    | 9.91%   |
| Unknown                     | 89        | 114    | 8.32%   |
| SanDisk                     | 76        | 84     | 7.1%    |
| Kingston                    | 51        | 59     | 4.77%   |
| Crucial                     | 42        | 49     | 3.93%   |
| SK hynix                    | 30        | 37     | 2.8%    |
| Hitachi                     | 29        | 32     | 2.71%   |
| HGST                        | 29        | 33     | 2.71%   |
| Intel                       | 28        | 32     | 2.62%   |
| Micron Technology           | 18        | 19     | 1.68%   |
| A-DATA Technology           | 14        | 15     | 1.31%   |
| China                       | 10        | 12     | 0.93%   |
| Intenso                     | 9         | 9      | 0.84%   |
| Apple                       | 9         | 10     | 0.84%   |
| KIOXIA                      | 8         | 8      | 0.75%   |
| Netac                       | 7         | 7      | 0.65%   |
| LITEONIT                    | 7         | 8      | 0.65%   |
| SPCC                        | 6         | 8      | 0.56%   |
| PNY                         | 6         | 7      | 0.56%   |
| LITEON                      | 6         | 7      | 0.56%   |
| Fujitsu                     | 6         | 7      | 0.56%   |
| Transcend                   | 5         | 6      | 0.47%   |
| Patriot                     | 5         | 5      | 0.47%   |
| Lite-On                     | 5         | 7      | 0.47%   |
| Goodram                     | 5         | 6      | 0.47%   |
| Team                        | 4         | 4      | 0.37%   |
| Phison                      | 4         | 5      | 0.37%   |
| JMicron Technology          | 4         | 5      | 0.37%   |
| SABRENT                     | 3         | 4      | 0.28%   |
| OCZ                         | 3         | 4      | 0.28%   |
| Lexar                       | 3         | 3      | 0.28%   |
| ASMT                        | 3         | 3      | 0.28%   |
| Micron/Crucial Technology   | 2         | 2      | 0.19%   |
| KingSpec                    | 2         | 2      | 0.19%   |
| HS-SSD-E100                 | 2         | 2      | 0.19%   |
| Hewlett-Packard             | 2         | 2      | 0.19%   |
| BHT                         | 2         | 3      | 0.19%   |
| Unknown                     | 2         | 2      | 0.19%   |
| Yangtze Memory Technologies | 1         | 1      | 0.09%   |
| Verbatim                    | 1         | 1      | 0.09%   |
| Vaseky                      | 1         | 2      | 0.09%   |
| TO Exter                    | 1         | 1      | 0.09%   |
| Teclast                     | 1         | 1      | 0.09%   |
| T-FORCE                     | 1         | 1      | 0.09%   |
| Star                        | 1         | 1      | 0.09%   |
| Space ke                    | 1         | 1      | 0.09%   |
| S3+                         | 1         | 2      | 0.09%   |
| Realtek Semiconductor       | 1         | 1      | 0.09%   |
| Plextor                     | 1         | 1      | 0.09%   |
| OSCOO                       | 1         | 1      | 0.09%   |
| Mushkin                     | 1         | 1      | 0.09%   |
| MidasForce                  | 1         | 1      | 0.09%   |
| LS                          | 1         | 1      | 0.09%   |
| Leven                       | 1         | 1      | 0.09%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.09%   |
| KESU                        | 1         | 1      | 0.09%   |
| HS-SSD-C100                 | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 31        | 2.78%   |
| Unknown MMC Card  64GB                 | 27        | 2.42%   |
| Seagate ST1000LM035-1RK172 1TB         | 20        | 1.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 17        | 1.52%   |
| Toshiba MQ01ABD100 1TB                 | 16        | 1.43%   |
| SanDisk NVMe SSD Drive 256GB           | 16        | 1.43%   |
| Samsung NVMe SSD Drive 512GB           | 16        | 1.43%   |
| Toshiba MQ01ABF050 500GB               | 13        | 1.16%   |
| Toshiba MQ04ABF100 1TB                 | 12        | 1.07%   |
| Kingston SA400S37240G 240GB SSD        | 12        | 1.07%   |
| Unknown MMC Card  128GB                | 10        | 0.9%    |
| SanDisk NVMe SSD Drive 512GB           | 10        | 0.9%    |
| Samsung NVMe SSD Drive 256GB           | 10        | 0.9%    |
| Kingston SA400S37120G 120GB SSD        | 10        | 0.9%    |
| Unknown MMC Card  16GB                 | 9         | 0.81%   |
| Intel NVMe SSD Drive 512GB             | 9         | 0.81%   |
| Crucial CT240BX500SSD1 240GB           | 9         | 0.81%   |
| Seagate ST9500325AS 500GB              | 8         | 0.72%   |
| Samsung SSD 860 EVO 500GB              | 8         | 0.72%   |
| Crucial CT500MX500SSD1 500GB           | 8         | 0.72%   |
| Seagate Expansion 1TB                  | 7         | 0.63%   |
| Kingston SA400S37480G 480GB SSD        | 7         | 0.63%   |
| HGST HTS721010A9E630 1TB               | 7         | 0.63%   |
| WDC WD10SPZX-24Z10 1TB                 | 6         | 0.54%   |
| Unknown SD/MMC/MS PRO 128GB            | 6         | 0.54%   |
| SK hynix NVMe SSD Drive 256GB          | 6         | 0.54%   |
| Seagate ST500LT012-1DG142 500GB        | 6         | 0.54%   |
| Samsung SSD 860 EVO 250GB              | 6         | 0.54%   |
| Samsung SSD 850 EVO 500GB              | 6         | 0.54%   |
| HGST HTS725050A7E630 500GB             | 6         | 0.54%   |
| SK hynix NVMe SSD Drive 512GB          | 5         | 0.45%   |
| Seagate ST1000LM049-2GH172 1TB         | 5         | 0.45%   |
| SanDisk X400 M.2 2280 256GB SSD        | 5         | 0.45%   |
| Samsung NVMe SSD Drive 2TB             | 5         | 0.45%   |
| Hitachi HTS545050A7E380 500GB          | 5         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 4         | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB               | 4         | 0.36%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 4         | 0.36%   |
| Seagate ST9500420AS 500GB              | 4         | 0.36%   |
| Seagate ST750LM022 HN-M750MBB 752GB    | 4         | 0.36%   |
| Seagate ST500LM021-1KJ152 500GB        | 4         | 0.36%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 4         | 0.36%   |
| Seagate ST2000LM007-1R8174 2TB         | 4         | 0.36%   |
| SanDisk NVMe SSD Drive 1TB             | 4         | 0.36%   |
| Samsung SSD 860 EVO 1TB                | 4         | 0.36%   |
| Samsung SSD 850 EVO 250GB              | 4         | 0.36%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 4         | 0.36%   |
| Samsung NVMe SSD Drive 1TB             | 4         | 0.36%   |
| Micron NVMe SSD Drive 512GB            | 4         | 0.36%   |
| KIOXIA NVMe SSD Drive 512GB            | 4         | 0.36%   |
| Intel NVMe SSD Drive 1024GB            | 4         | 0.36%   |
| HGST HTS545050A7E380 500GB             | 4         | 0.36%   |
| HGST HTS541010A9E680 1TB               | 4         | 0.36%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 3         | 0.27%   |
| WDC WD5000LPVT-22G33T0 500GB           | 3         | 0.27%   |
| WDC WD1600BEVS-60RST0 160GB            | 3         | 0.27%   |
| WDC WD10JPVX-60JC3T0 1TB               | 3         | 0.27%   |
| Unknown NCard  32GB                    | 3         | 0.27%   |
| Unknown MMC Card  4GB                  | 3         | 0.27%   |
| Toshiba MQ01ABD075 752GB               | 3         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 141       | 173    | 34.9%   |
| WDC                 | 96        | 105    | 23.76%  |
| Toshiba             | 82        | 88     | 20.3%   |
| Hitachi             | 29        | 32     | 7.18%   |
| HGST                | 29        | 33     | 7.18%   |
| Unknown             | 6         | 6      | 1.49%   |
| Fujitsu             | 6         | 7      | 1.49%   |
| Samsung Electronics | 5         | 5      | 1.24%   |
| JMicron Technology  | 3         | 4      | 0.74%   |
| ASMT                | 3         | 3      | 0.74%   |
| SABRENT             | 1         | 1      | 0.25%   |
| KESU                | 1         | 1      | 0.25%   |
| Intenso             | 1         | 1      | 0.25%   |
| Apple               | 1         | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 83        | 101    | 21.5%   |
| Kingston            | 44        | 52     | 11.4%   |
| Crucial             | 41        | 47     | 10.62%  |
| SanDisk             | 39        | 44     | 10.1%   |
| WDC                 | 17        | 21     | 4.4%    |
| Toshiba             | 17        | 18     | 4.4%    |
| SK hynix            | 12        | 12     | 3.11%   |
| Micron Technology   | 10        | 11     | 2.59%   |
| China               | 10        | 12     | 2.59%   |
| A-DATA Technology   | 10        | 11     | 2.59%   |
| Intel               | 9         | 10     | 2.33%   |
| Netac               | 7         | 7      | 1.81%   |
| LITEONIT            | 7         | 8      | 1.81%   |
| Intenso             | 7         | 7      | 1.81%   |
| Apple               | 7         | 7      | 1.81%   |
| PNY                 | 6         | 7      | 1.55%   |
| LITEON              | 6         | 7      | 1.55%   |
| Transcend           | 5         | 6      | 1.3%    |
| SPCC                | 5         | 7      | 1.3%    |
| Patriot             | 5         | 5      | 1.3%    |
| Goodram             | 5         | 6      | 1.3%    |
| Team                | 4         | 4      | 1.04%   |
| OCZ                 | 3         | 4      | 0.78%   |
| Lexar               | 2         | 2      | 0.52%   |
| KingSpec            | 2         | 2      | 0.52%   |
| HS-SSD-E100         | 2         | 2      | 0.52%   |
| Hewlett-Packard     | 2         | 2      | 0.52%   |
| BHT                 | 2         | 3      | 0.52%   |
| Verbatim            | 1         | 1      | 0.26%   |
| TO Exter            | 1         | 1      | 0.26%   |
| Teclast             | 1         | 1      | 0.26%   |
| Star                | 1         | 1      | 0.26%   |
| S3+                 | 1         | 2      | 0.26%   |
| Plextor             | 1         | 1      | 0.26%   |
| OSCOO               | 1         | 1      | 0.26%   |
| Mushkin             | 1         | 1      | 0.26%   |
| MidasForce          | 1         | 1      | 0.26%   |
| Lite-On             | 1         | 1      | 0.26%   |
| Leven               | 1         | 1      | 0.26%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.26%   |
| HS-SSD-C100         | 1         | 1      | 0.26%   |
| FORESEE             | 1         | 1      | 0.26%   |
| Dell                | 1         | 1      | 0.26%   |
| BUFFALO             | 1         | 1      | 0.26%   |
| Unknown             | 1         | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 395       | 460    | 38.05%  |
| SSD     | 368       | 443    | 35.45%  |
| NVMe    | 176       | 226    | 16.96%  |
| MMC     | 89        | 113    | 8.57%   |
| Unknown | 10        | 12     | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 702       | 871    | 70.13%  |
| NVMe | 175       | 223    | 17.48%  |
| MMC  | 89        | 113    | 8.89%   |
| SAS  | 35        | 47     | 3.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 516       | 615    | 68.62%  |
| 0.51-1.0   | 215       | 254    | 28.59%  |
| 1.01-2.0   | 16        | 24     | 2.13%   |
| 4.01-10.0  | 3         | 5      | 0.4%    |
| 3.01-4.0   | 2         | 5      | 0.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 310       | 33.88%  |
| 251-500        | 239       | 26.12%  |
| 501-1000       | 138       | 15.08%  |
| 51-100         | 89        | 9.73%   |
| 21-50          | 57        | 6.23%   |
| 1001-2000      | 29        | 3.17%   |
| 1-20           | 20        | 2.19%   |
| Unknown        | 13        | 1.42%   |
| More than 3000 | 11        | 1.2%    |
| 2001-3000      | 9         | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 425       | 44.93%  |
| 21-50          | 265       | 28.01%  |
| 51-100         | 89        | 9.41%   |
| 101-250        | 85        | 8.99%   |
| 251-500        | 42        | 4.44%   |
| 501-1000       | 21        | 2.22%   |
| Unknown        | 13        | 1.37%   |
| More than 3000 | 4         | 0.42%   |
| 2001-3000      | 2         | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB                       | 2         | 2      | 11.11%  |
| WDC WD5000LPVX-75V0TT0 500GB                  | 1         | 1      | 5.56%   |
| WDC WD10SPZX-75Z10T2 1TB                      | 1         | 1      | 5.56%   |
| WDC WD10JPVX-22JC3T0 1TB                      | 1         | 1      | 5.56%   |
| WDC WD10JPVT-55A1YT0 1TB                      | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD075 752GB                      | 1         | 1      | 5.56%   |
| Seagate ST9500420AS 500GB                     | 1         | 1      | 5.56%   |
| Seagate ST9200420ASG 200GB                    | 1         | 1      | 5.56%   |
| Seagate ST500LM000-SSHD-8GB                   | 1         | 1      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 5.56%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD | 1         | 1      | 5.56%   |
| Kingston SUV400S37240G 240GB SSD              | 1         | 1      | 5.56%   |
| Hitachi HTS725032A9A364 320GB                 | 1         | 1      | 5.56%   |
| HGST HTS725050A7E630 500GB                    | 1         | 1      | 5.56%   |
| HGST HTS545050A7E680 500GB                    | 1         | 1      | 5.56%   |
| Hewlett-Packard SSD S600 240GB                | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 22.22%  |
| Toshiba             | 4         | 4      | 22.22%  |
| Seagate             | 4         | 4      | 22.22%  |
| HGST                | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |
| Kingston            | 1         | 1      | 5.56%   |
| Hitachi             | 1         | 1      | 5.56%   |
| Hewlett-Packard     | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 26.67%  |
| Toshiba | 4         | 4      | 26.67%  |
| Seagate | 4         | 4      | 26.67%  |
| HGST    | 2         | 2      | 13.33%  |
| Hitachi | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 83.33%  |
| SSD  | 3         | 3      | 16.67%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 795       | 1116   | 86.7%   |
| Works    | 103       | 119    | 11.23%  |
| Malfunc  | 18        | 18     | 1.96%   |
| Failed   | 1         | 1      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 673       | 69.1%   |
| AMD                              | 116       | 11.91%  |
| Samsung Electronics              | 64        | 6.57%   |
| SanDisk                          | 38        | 3.9%    |
| SK hynix                         | 17        | 1.75%   |
| KIOXIA                           | 9         | 0.92%   |
| Micron Technology                | 8         | 0.82%   |
| Toshiba America Info Systems     | 7         | 0.72%   |
| Kingston Technology Company      | 7         | 0.72%   |
| Phison Electronics               | 4         | 0.41%   |
| Nvidia                           | 4         | 0.41%   |
| Micron/Crucial Technology        | 4         | 0.41%   |
| Lite-On Technology               | 4         | 0.41%   |
| ADATA Technology                 | 4         | 0.41%   |
| Marvell Technology Group         | 3         | 0.31%   |
| ASMedia Technology               | 3         | 0.31%   |
| Silicon Integrated Systems [SiS] | 2         | 0.21%   |
| Realtek Semiconductor            | 2         | 0.21%   |
| Yangtze Memory Technologies      | 1         | 0.1%    |
| VIA Technologies                 | 1         | 0.1%    |
| Silicon Motion                   | 1         | 0.1%    |
| Silicon Image                    | 1         | 0.1%    |
| Apple                            | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 96        | 9.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 95        | 9.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 68        | 6.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 63        | 6%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 63        | 6%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 50        | 4.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 37        | 3.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 34        | 3.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 30        | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 28        | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 27        | 2.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 26        | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 20        | 1.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 18        | 1.71%   |
| Samsung NVMe SSD Controller 980                                                        | 17        | 1.62%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 17        | 1.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 16        | 1.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 16        | 1.52%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 14        | 1.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 14        | 1.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 13        | 1.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 13        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 13        | 1.24%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 12        | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 11        | 1.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 10        | 0.95%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 9         | 0.86%   |
| KIOXIA Non-Volatile memory controller                                                  | 9         | 0.86%   |
| Intel SSD 660P Series                                                                  | 9         | 0.86%   |
| Micron Non-Volatile memory controller                                                  | 8         | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 7         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 7         | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 7         | 0.67%   |
| SK hynix Gold P31 SSD                                                                  | 6         | 0.57%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 6         | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 6         | 0.57%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 6         | 0.57%   |
| Intel Non-Volatile memory controller                                                   | 6         | 0.57%   |
| SK hynix BC511                                                                         | 4         | 0.38%   |
| SanDisk Non-Volatile memory controller                                                 | 4         | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 4         | 0.38%   |
| Lite-On Non-Volatile memory controller                                                 | 4         | 0.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 4         | 0.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 4         | 0.38%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 4         | 0.38%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.38%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 4         | 0.38%   |
| AMD FCH IDE Controller                                                                 | 4         | 0.38%   |
| SanDisk PC SN520 NVMe SSD                                                              | 3         | 0.29%   |
| Samsung Apple PCIe SSD                                                                 | 3         | 0.29%   |
| Nvidia MCP79 AHCI Controller                                                           | 3         | 0.29%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 3         | 0.29%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 0.29%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 3         | 0.29%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 3         | 0.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 3         | 0.29%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                   | 2         | 0.19%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 0.19%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 2         | 0.19%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 2         | 0.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 693       | 68.07%  |
| NVMe | 176       | 17.29%  |
| RAID | 85        | 8.35%   |
| IDE  | 64        | 6.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 759       | 84.33%  |
| AMD    | 141       | 15.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.78%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 14        | 1.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 1.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 12        | 1.33%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 12        | 1.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 1.22%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 1.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 10        | 1.11%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 10        | 1.11%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 1.11%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 1%      |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 9         | 1%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.89%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 8         | 0.89%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 8         | 0.89%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 8         | 0.89%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 0.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 0.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.78%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 7         | 0.78%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 7         | 0.78%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 7         | 0.78%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 7         | 0.78%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 7         | 0.78%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 6         | 0.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.67%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 6         | 0.67%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 6         | 0.67%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 6         | 0.67%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 6         | 0.67%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 6         | 0.67%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 0.67%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 6         | 0.67%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 0.67%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 6         | 0.67%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 6         | 0.67%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 6         | 0.67%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 6         | 0.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 0.67%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 5         | 0.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 0.56%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 5         | 0.56%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 5         | 0.56%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 5         | 0.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.56%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 5         | 0.56%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 5         | 0.56%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 5         | 0.56%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 5         | 0.56%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 5         | 0.56%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.56%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 5         | 0.56%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 0.56%   |
| AMD E-450 APU with Radeon HD Graphics         | 5         | 0.56%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 4         | 0.44%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 4         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 231       | 25.67%  |
| Intel Core i7                        | 162       | 18%     |
| Intel Core i3                        | 103       | 11.44%  |
| Intel Celeron                        | 70        | 7.78%   |
| Intel Core 2 Duo                     | 59        | 6.56%   |
| Intel Pentium                        | 41        | 4.56%   |
| Intel Atom                           | 34        | 3.78%   |
| Other                                | 33        | 3.67%   |
| AMD Ryzen 5                          | 31        | 3.44%   |
| AMD Ryzen 7                          | 23        | 2.56%   |
| AMD A6                               | 20        | 2.22%   |
| AMD A10                              | 10        | 1.11%   |
| AMD E1                               | 7         | 0.78%   |
| AMD E                                | 7         | 0.78%   |
| AMD A4                               | 7         | 0.78%   |
| AMD A8                               | 6         | 0.67%   |
| Intel Pentium Dual-Core              | 5         | 0.56%   |
| Intel Pentium Dual                   | 4         | 0.44%   |
| Intel Core m5                        | 4         | 0.44%   |
| Intel Core M                         | 4         | 0.44%   |
| AMD Ryzen 3                          | 4         | 0.44%   |
| Intel Core 2                         | 3         | 0.33%   |
| AMD Athlon II                        | 3         | 0.33%   |
| Intel Pentium Silver                 | 2         | 0.22%   |
| Intel Genuine                        | 2         | 0.22%   |
| Intel Core i9                        | 2         | 0.22%   |
| Intel Celeron Dual-Core              | 2         | 0.22%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.22%   |
| AMD Turion 64 X2 Mobile              | 2         | 0.22%   |
| AMD FX                               | 2         | 0.22%   |
| AMD E2                               | 2         | 0.22%   |
| AMD Athlon                           | 2         | 0.22%   |
| Intel Xeon                           | 1         | 0.11%   |
| Intel Core 2 Extreme                 | 1         | 0.11%   |
| Intel Celeron M                      | 1         | 0.11%   |
| AMD Turion II                        | 1         | 0.11%   |
| AMD Turion 64 Mobile                 | 1         | 0.11%   |
| AMD Sempron                          | 1         | 0.11%   |
| AMD Ryzen 9                          | 1         | 0.11%   |
| AMD Ryzen 7 PRO                      | 1         | 0.11%   |
| AMD Phenom II                        | 1         | 0.11%   |
| AMD C-60                             | 1         | 0.11%   |
| AMD Athlon X2                        | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 553       | 61.44%  |
| 4      | 275       | 30.56%  |
| 6      | 34        | 3.78%   |
| 8      | 29        | 3.22%   |
| 1      | 7         | 0.78%   |
| 10     | 1         | 0.11%   |
| 3      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 900       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 601       | 66.78%  |
| 1      | 299       | 33.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 900       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 88        | 9.65%   |
| 0x306a9    | 86        | 9.43%   |
| Unknown    | 60        | 6.58%   |
| 0x40651    | 55        | 6.03%   |
| 0x20655    | 34        | 3.73%   |
| 0x406e3    | 33        | 3.62%   |
| 0x1067a    | 31        | 3.4%    |
| 0x806ea    | 29        | 3.18%   |
| 0x306d4    | 29        | 3.18%   |
| 0x30678    | 26        | 2.85%   |
| 0x806ec    | 25        | 2.74%   |
| 0x306c3    | 25        | 2.74%   |
| 0x806e9    | 21        | 2.3%    |
| 0x806c1    | 20        | 2.19%   |
| 0x406c4    | 20        | 2.19%   |
| 0x906ea    | 17        | 1.86%   |
| 0x706e5    | 16        | 1.75%   |
| 0x706a8    | 15        | 1.64%   |
| 0x6fd      | 15        | 1.64%   |
| 0x506c9    | 15        | 1.64%   |
| 0x20652    | 15        | 1.64%   |
| 0x10676    | 15        | 1.64%   |
| 0x906e9    | 13        | 1.43%   |
| 0x406c3    | 13        | 1.43%   |
| 0x08108109 | 13        | 1.43%   |
| 0x08108102 | 12        | 1.32%   |
| 0x07030105 | 12        | 1.32%   |
| 0x6fb      | 10        | 1.1%    |
| 0x08600106 | 9         | 0.99%   |
| 0xa0652    | 8         | 0.88%   |
| 0x06006704 | 8         | 0.88%   |
| 0x0a50000c | 7         | 0.77%   |
| 0x0700010f | 7         | 0.77%   |
| 0x06006705 | 7         | 0.77%   |
| 0x05000119 | 7         | 0.77%   |
| 0x506e3    | 6         | 0.66%   |
| 0x08608103 | 6         | 0.66%   |
| 0x806eb    | 5         | 0.55%   |
| 0x806d1    | 5         | 0.55%   |
| 0x106e5    | 5         | 0.55%   |
| 0x08600103 | 5         | 0.55%   |
| 0x010000c8 | 5         | 0.55%   |
| 0x706a1    | 4         | 0.44%   |
| 0x30673    | 4         | 0.44%   |
| 0x07030106 | 4         | 0.44%   |
| 0x0600611a | 4         | 0.44%   |
| 0x6fa      | 3         | 0.33%   |
| 0x6f6      | 3         | 0.33%   |
| 0x08600104 | 3         | 0.33%   |
| 0x06003106 | 3         | 0.33%   |
| 0x03000027 | 3         | 0.33%   |
| 0x02000057 | 3         | 0.33%   |
| 0x906c0    | 2         | 0.22%   |
| 0x40661    | 2         | 0.22%   |
| 0x30661    | 2         | 0.22%   |
| 0x106ca    | 2         | 0.22%   |
| 0x0a50000b | 2         | 0.22%   |
| 0x07000110 | 2         | 0.22%   |
| 0x06001119 | 2         | 0.22%   |
| 0xa0660    | 1         | 0.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 126       | 14%     |
| SandyBridge     | 90        | 10%     |
| IvyBridge       | 90        | 10%     |
| Haswell         | 87        | 9.67%   |
| Silvermont      | 64        | 7.11%   |
| Westmere        | 50        | 5.56%   |
| Penryn          | 46        | 5.11%   |
| Skylake         | 41        | 4.56%   |
| Core            | 33        | 3.67%   |
| Broadwell       | 29        | 3.22%   |
| Zen+            | 26        | 2.89%   |
| TigerLake       | 23        | 2.56%   |
| Icelake         | 22        | 2.44%   |
| Excavator       | 20        | 2.22%   |
| Goldmont plus   | 19        | 2.11%   |
| Zen 2           | 18        | 2%      |
| Puma            | 17        | 1.89%   |
| Goldmont        | 16        | 1.78%   |
| Zen 3           | 11        | 1.22%   |
| CometLake       | 11        | 1.22%   |
| Jaguar          | 9         | 1%      |
| Bobcat          | 9         | 1%      |
| Unknown         | 7         | 0.78%   |
| Nehalem         | 6         | 0.67%   |
| K10             | 5         | 0.56%   |
| Piledriver      | 4         | 0.44%   |
| K8 & K10 hybrid | 4         | 0.44%   |
| K10 Llano       | 4         | 0.44%   |
| Bonnell         | 4         | 0.44%   |
| Steamroller     | 3         | 0.33%   |
| K8 Hammer       | 3         | 0.33%   |
| Tremont         | 2         | 0.22%   |
| Zen             | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 688       | 63.47%  |
| Nvidia                           | 202       | 18.63%  |
| AMD                              | 192       | 17.71%  |
| Silicon Integrated Systems [SiS] | 2         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 87        | 7.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 78        | 6.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 58        | 5.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 41        | 3.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 33        | 2.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 31        | 2.76%   |
| Intel UHD Graphics 620                                                                   | 30        | 2.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 29        | 2.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 29        | 2.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 2.41%   |
| Intel HD Graphics 620                                                                    | 23        | 2.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 22        | 1.96%   |
| Intel HD Graphics 5500                                                                   | 21        | 1.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 18        | 1.6%    |
| AMD Renoir                                                                               | 18        | 1.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 1.43%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 15        | 1.34%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 14        | 1.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.25%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 13        | 1.16%   |
| Intel HD Graphics 630                                                                    | 13        | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 1.07%   |
| Intel HD Graphics 500                                                                    | 12        | 1.07%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 12        | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 0.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.8%    |
| AMD Cezanne                                                                              | 9         | 0.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 0.71%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 0.62%   |
| AMD Lucienne                                                                             | 7         | 0.62%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.53%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 6         | 0.53%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 0.53%   |
| Intel HD Graphics 530                                                                    | 6         | 0.53%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.53%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.45%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 5         | 0.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 0.45%   |
| Intel HD Graphics 5300                                                                   | 5         | 0.45%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 0.45%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 5         | 0.45%   |
| Nvidia TU117M                                                                            | 4         | 0.36%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.36%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 4         | 0.36%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 4         | 0.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 0.36%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.36%   |
| Intel HD Graphics 515                                                                    | 4         | 0.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 4         | 0.36%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 4         | 0.36%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 4         | 0.36%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 4         | 0.36%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 3         | 0.27%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 0.27%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.27%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 520       | 57.71%  |
| Intel + Nvidia | 135       | 14.98%  |
| 1 x AMD        | 127       | 14.1%   |
| 1 x Nvidia     | 51        | 5.66%   |
| Intel + AMD    | 34        | 3.77%   |
| 2 x AMD        | 16        | 1.78%   |
| AMD + Nvidia   | 15        | 1.66%   |
| 1 x SiS        | 2         | 0.22%   |
| 2 x Nvidia     | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 775       | 85.92%  |
| Proprietary | 114       | 12.64%  |
| Unknown     | 13        | 1.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 605       | 66.34%  |
| 0.01-0.5   | 101       | 11.07%  |
| 1.01-2.0   | 86        | 9.43%   |
| 0.51-1.0   | 64        | 7.02%   |
| 3.01-4.0   | 28        | 3.07%   |
| 5.01-6.0   | 14        | 1.54%   |
| 7.01-8.0   | 10        | 1.1%    |
| 2.01-3.0   | 3         | 0.33%   |
| 8.01-16.0  | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 180       | 18.89%  |
| LG Display              | 145       | 15.22%  |
| Chimei Innolux          | 145       | 15.22%  |
| Samsung Electronics     | 131       | 13.75%  |
| BOE                     | 106       | 11.12%  |
| Chi Mei Optoelectronics | 32        | 3.36%   |
| Goldstar                | 21        | 2.2%    |
| Apple                   | 21        | 2.2%    |
| Lenovo                  | 19        | 1.99%   |
| Sharp                   | 18        | 1.89%   |
| Dell                    | 18        | 1.89%   |
| PANDA                   | 12        | 1.26%   |
| LG Philips              | 11        | 1.15%   |
| CPT                     | 7         | 0.73%   |
| Vizio                   | 5         | 0.52%   |
| LGD                     | 5         | 0.52%   |
| Acer                    | 5         | 0.52%   |
| Philips                 | 4         | 0.42%   |
| InfoVision              | 4         | 0.42%   |
| Hewlett-Packard         | 4         | 0.42%   |
| BenQ                    | 4         | 0.42%   |
| AOC                     | 4         | 0.42%   |
| Sony                    | 3         | 0.31%   |
| KDC                     | 3         | 0.31%   |
| HannStar                | 3         | 0.31%   |
| BOE Technology Group    | 3         | 0.31%   |
| Toshiba                 | 2         | 0.21%   |
| SANYO                   | 2         | 0.21%   |
| Quanta Display          | 2         | 0.21%   |
| ITE                     | 2         | 0.21%   |
| InnoLux Display         | 2         | 0.21%   |
| Iiyama                  | 2         | 0.21%   |
| Eizo                    | 2         | 0.21%   |
| VIE                     | 1         | 0.1%    |
| Unknown (XXX)           | 1         | 0.1%    |
| Unknown                 | 1         | 0.1%    |
| TMX                     | 1         | 0.1%    |
| STD                     | 1         | 0.1%    |
| SLD                     | 1         | 0.1%    |
| Sceptre Tech            | 1         | 0.1%    |
| Panasonic               | 1         | 0.1%    |
| ONB                     | 1         | 0.1%    |
| MStar                   | 1         | 0.1%    |
| MSI                     | 1         | 0.1%    |
| KTC                     | 1         | 0.1%    |
| KDB                     | 1         | 0.1%    |
| HSI                     | 1         | 0.1%    |
| HRG                     | 1         | 0.1%    |
| HIC                     | 1         | 0.1%    |
| HDE                     | 1         | 0.1%    |
| Gateway                 | 1         | 0.1%    |
| Fujitsu Siemens         | 1         | 0.1%    |
| Envision                | 1         | 0.1%    |
| ELD                     | 1         | 0.1%    |
| CMN                     | 1         | 0.1%    |
| Belinea                 | 1         | 0.1%    |
| ASUSTek Computer        | 1         | 0.1%    |
| Ancor Communications    | 1         | 0.1%    |
| Unknown                 | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 10        | 1.04%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 8         | 0.83%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 8         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 8         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 7         | 0.73%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.73%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.62%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 6         | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.62%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 5         | 0.52%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 5         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 5         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 5         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 5         | 0.52%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 5         | 0.52%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.52%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 4         | 0.42%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.42%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 4         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 4         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 4         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch          | 4         | 0.42%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 4         | 0.42%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch     | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch    | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 3         | 0.31%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 3         | 0.31%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 3         | 0.31%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 3         | 0.31%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.31%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 3         | 0.31%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch          | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 309x174mm 14.0-inch          | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch          | 3         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 3         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1590 1366x768 344x194mm 15.5-inch | 3         | 0.31%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 3         | 0.31%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 3         | 0.31%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                    | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO30ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 3         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 393       | 42.49%  |
| 1920x1080 (FHD)    | 288       | 31.14%  |
| 1600x900 (HD+)     | 68        | 7.35%   |
| 1280x800 (WXGA)    | 49        | 5.3%    |
| 3840x2160 (4K)     | 21        | 2.27%   |
| 1440x900 (WXGA+)   | 15        | 1.62%   |
| 2560x1440 (QHD)    | 11        | 1.19%   |
| 2560x1600          | 8         | 0.86%   |
| 1680x1050 (WSXGA+) | 8         | 0.86%   |
| 1360x768           | 6         | 0.65%   |
| Unknown            | 6         | 0.65%   |
| 3200x1800 (QHD+)   | 5         | 0.54%   |
| 2560x1080          | 5         | 0.54%   |
| 1280x1024 (SXGA)   | 5         | 0.54%   |
| 2880x1800          | 4         | 0.43%   |
| 2256x1504          | 4         | 0.43%   |
| 2160x1440          | 4         | 0.43%   |
| 1920x1200 (WUXGA)  | 4         | 0.43%   |
| 3840x2400          | 3         | 0.32%   |
| 1024x600           | 3         | 0.32%   |
| 5760x1080          | 2         | 0.22%   |
| 3440x1440          | 2         | 0.22%   |
| 1920x540           | 2         | 0.22%   |
| 1920x515           | 2         | 0.22%   |
| 4480x1600          | 1         | 0.11%   |
| 3840x1200          | 1         | 0.11%   |
| 3840x1080          | 1         | 0.11%   |
| 3600x1080          | 1         | 0.11%   |
| 1920x1280          | 1         | 0.11%   |
| 1680x945           | 1         | 0.11%   |
| 1280x720 (HD)      | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 411       | 43.31%  |
| 13      | 136       | 14.33%  |
| 14      | 110       | 11.59%  |
| 17      | 81        | 8.54%   |
| 11      | 33        | 3.48%   |
| 12      | 27        | 2.85%   |
| Unknown | 26        | 2.74%   |
| 27      | 17        | 1.79%   |
| 24      | 16        | 1.69%   |
| 23      | 12        | 1.26%   |
| 18      | 12        | 1.26%   |
| 34      | 8         | 0.84%   |
| 31      | 7         | 0.74%   |
| 21      | 7         | 0.74%   |
| 16      | 6         | 0.63%   |
| 20      | 5         | 0.53%   |
| 10      | 5         | 0.53%   |
| 19      | 4         | 0.42%   |
| 54      | 3         | 0.32%   |
| 25      | 3         | 0.32%   |
| 22      | 3         | 0.32%   |
| 72      | 2         | 0.21%   |
| 40      | 2         | 0.21%   |
| 32      | 2         | 0.21%   |
| 26      | 2         | 0.21%   |
| 84      | 1         | 0.11%   |
| 74      | 1         | 0.11%   |
| 64      | 1         | 0.11%   |
| 52      | 1         | 0.11%   |
| 49      | 1         | 0.11%   |
| 48      | 1         | 0.11%   |
| 47      | 1         | 0.11%   |
| 37      | 1         | 0.11%   |
| 8       | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 581       | 61.48%  |
| 201-300     | 132       | 13.97%  |
| 351-400     | 95        | 10.05%  |
| 501-600     | 44        | 4.66%   |
| 401-500     | 31        | 3.28%   |
| Unknown     | 26        | 2.75%   |
| 701-800     | 10        | 1.06%   |
| 601-700     | 10        | 1.06%   |
| 1001-1500   | 8         | 0.85%   |
| 1501-2000   | 4         | 0.42%   |
| 801-900     | 3         | 0.32%   |
| 101-200     | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 739       | 84.75%  |
| 16/10   | 87        | 9.98%   |
| Unknown | 18        | 2.06%   |
| 3/2     | 10        | 1.15%   |
| 21/9    | 8         | 0.92%   |
| 5/4     | 4         | 0.46%   |
| 4/3     | 2         | 0.23%   |
| 3.73    | 2         | 0.23%   |
| 32/9    | 1         | 0.11%   |
| 0.62    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 413       | 43.47%  |
| 81-90          | 196       | 20.63%  |
| 121-130        | 69        | 7.26%   |
| 71-80          | 50        | 5.26%   |
| 201-250        | 36        | 3.79%   |
| 51-60          | 33        | 3.47%   |
| 61-70          | 26        | 2.74%   |
| Unknown        | 26        | 2.74%   |
| 301-350        | 18        | 1.89%   |
| 351-500        | 17        | 1.79%   |
| 141-150        | 15        | 1.58%   |
| More than 1000 | 11        | 1.16%   |
| 151-200        | 11        | 1.16%   |
| 131-140        | 8         | 0.84%   |
| 41-50          | 5         | 0.53%   |
| 251-300        | 5         | 0.53%   |
| 111-120        | 4         | 0.42%   |
| 501-1000       | 4         | 0.42%   |
| 91-100         | 2         | 0.21%   |
| 1-40           | 1         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 401       | 42.75%  |
| 121-160       | 289       | 30.81%  |
| 51-100        | 143       | 15.25%  |
| 161-240       | 47        | 5.01%   |
| Unknown       | 26        | 2.77%   |
| More than 240 | 18        | 1.92%   |
| 1-50          | 14        | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 783       | 86.14%  |
| 2     | 107       | 11.77%  |
| 0     | 12        | 1.32%   |
| 3     | 6         | 0.66%   |
| 4     | 1         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 463       | 32.61%  |
| Intel                             | 398       | 28.03%  |
| Qualcomm Atheros                  | 242       | 17.04%  |
| Broadcom                          | 121       | 8.52%   |
| Broadcom Limited                  | 40        | 2.82%   |
| Ralink                            | 18        | 1.27%   |
| Marvell Technology Group          | 16        | 1.13%   |
| ASIX Electronics                  | 14        | 0.99%   |
| Dell                              | 11        | 0.77%   |
| Ralink Technology                 | 10        | 0.7%    |
| TP-Link                           | 8         | 0.56%   |
| MediaTek                          | 8         | 0.56%   |
| Xiaomi                            | 7         | 0.49%   |
| Samsung Electronics               | 7         | 0.49%   |
| Hewlett-Packard                   | 5         | 0.35%   |
| DisplayLink                       | 5         | 0.35%   |
| Sierra Wireless                   | 4         | 0.28%   |
| Huawei Technologies               | 4         | 0.28%   |
| OnePlus Technology (Shenzhen)     | 3         | 0.21%   |
| Nvidia                            | 3         | 0.21%   |
| JMicron Technology                | 3         | 0.21%   |
| Ericsson Business Mobile Networks | 3         | 0.21%   |
| Edimax Technology                 | 3         | 0.21%   |
| T & A Mobile Phones               | 2         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.14%   |
| Qualcomm                          | 2         | 0.14%   |
| OPPO Electronics                  | 2         | 0.14%   |
| Linksys                           | 2         | 0.14%   |
| D-Link System                     | 2         | 0.14%   |
| ZyXEL Communications              | 1         | 0.07%   |
| ZyDAS                             | 1         | 0.07%   |
| U-Blox                            | 1         | 0.07%   |
| Qualcomm Atheros Communications   | 1         | 0.07%   |
| Novatel Wireless                  | 1         | 0.07%   |
| NetGear                           | 1         | 0.07%   |
| Motorola PCS                      | 1         | 0.07%   |
| Motorola BCS                      | 1         | 0.07%   |
| Lenovo                            | 1         | 0.07%   |
| ICS Advent                        | 1         | 0.07%   |
| Exar                              | 1         | 0.07%   |
| DJI Technology                    | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 264       | 15.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 113       | 6.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 63        | 3.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 49        | 2.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 37        | 2.19%   |
| Intel Wireless 7260                                                     | 37        | 2.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 35        | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 33        | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 33        | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 1.54%   |
| Intel Wireless 8260                                                     | 26        | 1.54%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 24        | 1.42%   |
| Intel Wireless 7265                                                     | 23        | 1.36%   |
| Intel Wireless 8265 / 8275                                              | 22        | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 1.19%   |
| Intel Wireless 3165                                                     | 20        | 1.19%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 14        | 0.83%   |
| Intel WiFi Link 5100                                                    | 14        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 13        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 13        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 0.77%   |
| Intel Ethernet Connection I219-LM                                       | 12        | 0.71%   |
| Intel 82577LM Gigabit Network Connection                                | 12        | 0.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 12        | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                           | 12        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 11        | 0.65%   |
| Intel Ethernet Connection I218-LM                                       | 11        | 0.65%   |
| Intel Ethernet Connection I217-LM                                       | 11        | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 10        | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 0.59%   |
| Intel Centrino Advanced-N 6200                                          | 10        | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 0.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 9         | 0.53%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 9         | 0.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 9         | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 8         | 0.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.47%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.47%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 7         | 0.42%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.42%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 0.42%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 7         | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 6         | 0.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 6         | 0.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 6         | 0.36%   |
| Intel Wireless 3160                                                     | 6         | 0.36%   |
| Intel Ethernet Connection I219-V                                        | 6         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 380       | 41.76%  |
| Qualcomm Atheros                | 208       | 22.86%  |
| Realtek Semiconductor           | 145       | 15.93%  |
| Broadcom                        | 92        | 10.11%  |
| Broadcom Limited                | 24        | 2.64%   |
| Ralink                          | 18        | 1.98%   |
| Ralink Technology               | 10        | 1.1%    |
| MediaTek                        | 7         | 0.77%   |
| Dell                            | 5         | 0.55%   |
| TP-Link                         | 4         | 0.44%   |
| Sierra Wireless                 | 4         | 0.44%   |
| Edimax Technology               | 3         | 0.33%   |
| Linksys                         | 2         | 0.22%   |
| D-Link System                   | 2         | 0.22%   |
| ZyXEL Communications            | 1         | 0.11%   |
| ZyDAS                           | 1         | 0.11%   |
| Qualcomm Atheros Communications | 1         | 0.11%   |
| Qualcomm                        | 1         | 0.11%   |
| NetGear                         | 1         | 0.11%   |
| Hewlett-Packard                 | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 63        | 6.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 37        | 4.03%   |
| Intel Wireless 7260                                                     | 37        | 4.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 35        | 3.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 33        | 3.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 33        | 3.6%    |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 3.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 2.84%   |
| Intel Wireless 8260                                                     | 26        | 2.84%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 2.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 24        | 2.62%   |
| Intel Wireless 7265                                                     | 23        | 2.51%   |
| Intel Wireless 8265 / 8275                                              | 22        | 2.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 2.18%   |
| Intel Wireless 3165                                                     | 20        | 2.18%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 1.74%   |
| Intel WiFi Link 5100                                                    | 14        | 1.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 13        | 1.42%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 1.42%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 11        | 1.2%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 10        | 1.09%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 1.09%   |
| Intel Centrino Advanced-N 6200                                          | 10        | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 1.09%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 9         | 0.98%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 9         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.87%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.87%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 7         | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 0.76%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 7         | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.65%   |
| Intel Wireless 3160                                                     | 6         | 0.65%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.65%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 6         | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 5         | 0.55%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 5         | 0.55%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.55%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.55%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 5         | 0.55%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 0.44%   |
| Realtek 802.11n WLAN Adapter                                            | 4         | 0.44%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.44%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.44%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 4         | 0.44%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 4         | 0.44%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 401       | 53.68%  |
| Intel                            | 149       | 19.95%  |
| Qualcomm Atheros                 | 61        | 8.17%   |
| Broadcom                         | 42        | 5.62%   |
| Broadcom Limited                 | 18        | 2.41%   |
| Marvell Technology Group         | 16        | 2.14%   |
| ASIX Electronics                 | 14        | 1.87%   |
| Xiaomi                           | 7         | 0.94%   |
| Samsung Electronics              | 7         | 0.94%   |
| DisplayLink                      | 5         | 0.67%   |
| TP-Link                          | 4         | 0.54%   |
| Nvidia                           | 3         | 0.4%    |
| JMicron Technology               | 3         | 0.4%    |
| Huawei Technologies              | 3         | 0.4%    |
| Silicon Integrated Systems [SiS] | 2         | 0.27%   |
| OPPO Electronics                 | 2         | 0.27%   |
| Hewlett-Packard                  | 2         | 0.27%   |
| Qualcomm                         | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.13%   |
| Novatel Wireless                 | 1         | 0.13%   |
| Motorola PCS                     | 1         | 0.13%   |
| Motorola BCS                     | 1         | 0.13%   |
| MediaTek                         | 1         | 0.13%   |
| Lenovo                           | 1         | 0.13%   |
| ICS Advent                       | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 264       | 35.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 113       | 15.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 49        | 6.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 1.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 1.73%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 1.6%    |
| Intel 82577LM Gigabit Network Connection                          | 12        | 1.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 1.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 1.6%    |
| Intel Ethernet Connection I218-LM                                 | 11        | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 1.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 9         | 1.2%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 8         | 1.07%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.8%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.8%    |
| Intel Ethernet Connection I219-V                                  | 6         | 0.8%    |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.8%    |
| Intel 82566MM Gigabit Network Connection                          | 6         | 0.8%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6         | 0.8%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.67%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 4         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.53%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 4         | 0.53%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 4         | 0.53%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 4         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.4%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.4%    |
| Intel 82577LC Gigabit Network Connection                          | 3         | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.4%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 3         | 0.4%    |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 3         | 0.4%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.27%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.27%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.27%   |
| OPPO Find X2 Lite                                                 | 2         | 0.27%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.27%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 2         | 0.27%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.27%   |
| Intel Ethernet controller                                         | 2         | 0.27%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.27%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.27%   |
| Intel 82562GT 10/100 Network Connection                           | 2         | 0.27%   |
| Huawei E353/E3131                                                 | 2         | 0.27%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.27%   |
| DisplayLink USB-C Dual-4K Dock                                    | 2         | 0.27%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 865       | 53.96%  |
| Ethernet | 719       | 44.85%  |
| Modem    | 15        | 0.94%   |
| Unknown  | 4         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 726       | 78.32%  |
| Ethernet | 200       | 21.57%  |
| Unknown  | 1         | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 665       | 73.89%  |
| 1     | 191       | 21.22%  |
| 0     | 40        | 4.44%   |
| 3     | 4         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 641       | 70.52%  |
| Yes  | 268       | 29.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 259       | 38.89%  |
| Qualcomm Atheros Communications | 82        | 12.31%  |
| Realtek Semiconductor           | 77        | 11.56%  |
| Broadcom                        | 48        | 7.21%   |
| IMC Networks                    | 37        | 5.56%   |
| Lite-On Technology              | 27        | 4.05%   |
| Foxconn / Hon Hai               | 25        | 3.75%   |
| Dell                            | 19        | 2.85%   |
| Apple                           | 19        | 2.85%   |
| Hewlett-Packard                 | 16        | 2.4%    |
| Toshiba                         | 15        | 2.25%   |
| Ralink                          | 10        | 1.5%    |
| Cambridge Silicon Radio         | 9         | 1.35%   |
| ASUSTek Computer                | 5         | 0.75%   |
| Realtek                         | 4         | 0.6%    |
| Foxconn International           | 4         | 0.6%    |
| Alps Electric                   | 3         | 0.45%   |
| Integrated System Solution      | 2         | 0.3%    |
| Askey Computer                  | 2         | 0.3%    |
| MediaTek                        | 1         | 0.15%   |
| Chicony Electronics             | 1         | 0.15%   |
| Unknown                         | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 131       | 19.67%  |
| Realtek Bluetooth Radio                                                             | 46        | 6.91%   |
| Intel Bluetooth Device                                                              | 37        | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 35        | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 34        | 5.11%   |
| Intel AX200 Bluetooth                                                               | 24        | 3.6%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 20        | 3%      |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 17        | 2.55%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 15        | 2.25%   |
| IMC Networks Bluetooth Device                                                       | 14        | 2.1%    |
| Apple Bluetooth Host Controller                                                     | 12        | 1.8%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 11        | 1.65%   |
| Ralink RT3290 Bluetooth                                                             | 10        | 1.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 10        | 1.5%    |
| IMC Networks Bluetooth Radio                                                        | 10        | 1.5%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 10        | 1.5%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 10        | 1.5%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 9         | 1.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 1.35%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 9         | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 8         | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 8         | 1.2%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 7         | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 6         | 0.9%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 6         | 0.9%    |
| Dell DW375 Bluetooth Module                                                         | 6         | 0.9%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 6         | 0.9%    |
| Realtek RTL8723B Bluetooth                                                          | 5         | 0.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 5         | 0.75%   |
| Intel AX210 Bluetooth                                                               | 5         | 0.75%   |
| IMC Networks Wireless_Device                                                        | 5         | 0.75%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 5         | 0.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 5         | 0.75%   |
| Toshiba Bluetooth Device                                                            | 4         | 0.6%    |
| Toshiba BCM43142A0                                                                  | 4         | 0.6%    |
| Realtek Bluetooth Radio                                                             | 4         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 4         | 0.6%    |
| Lite-On Bluetooth Device                                                            | 4         | 0.6%    |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 0.6%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 4         | 0.6%    |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 4         | 0.6%    |
| Apple Bluetooth HCI                                                                 | 4         | 0.6%    |
| Toshiba Integrated Bluetooth HCI                                                    | 3         | 0.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 3         | 0.45%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 3         | 0.45%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 0.45%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 3         | 0.45%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 3         | 0.45%   |
| Dell Wireless 365 Bluetooth                                                         | 3         | 0.45%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 3         | 0.45%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.3%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 2         | 0.3%    |
| IMC Networks BCM20702A0                                                             | 2         | 0.3%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.3%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 2         | 0.3%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.3%    |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.3%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.3%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 725       | 70.05%  |
| AMD                                  | 163       | 15.75%  |
| Nvidia                               | 124       | 11.98%  |
| Realtek Semiconductor                | 3         | 0.29%   |
| SteelSeries ApS                      | 2         | 0.19%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.19%   |
| Sennheiser Communications            | 2         | 0.19%   |
| Generalplus Technology               | 2         | 0.19%   |
| Focusrite-Novation                   | 2         | 0.19%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.1%    |
| Tenx Technology                      | 1         | 0.1%    |
| Razer USA                            | 1         | 0.1%    |
| PreSonus Audio Electronics           | 1         | 0.1%    |
| Lenovo                               | 1         | 0.1%    |
| GN Netcom                            | 1         | 0.1%    |
| Creative Technology                  | 1         | 0.1%    |
| Corsair                              | 1         | 0.1%    |
| Conexant Systems                     | 1         | 0.1%    |
| C-Media Electronics                  | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 109       | 8.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 92        | 7.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 71        | 5.6%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 62        | 4.89%   |
| Intel 8 Series HD Audio Controller                                                                | 58        | 4.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 56        | 4.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 54        | 4.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 40        | 3.16%   |
| AMD FCH Azalia Controller                                                                         | 40        | 3.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 31        | 2.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 29        | 2.29%   |
| Intel Broadwell-U Audio Controller                                                                | 29        | 2.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 29        | 2.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 29        | 2.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 28        | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 24        | 1.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 23        | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 1.74%   |
| Intel Cannon Lake PCH cAVS                                                                        | 22        | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 22        | 1.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 20        | 1.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 19        | 1.5%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 1.42%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 17        | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 17        | 1.34%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 16        | 1.26%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 1.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 16        | 1.26%   |
| Intel CM238 HD Audio Controller                                                                   | 15        | 1.18%   |
| AMD High Definition Audio Controller                                                              | 15        | 1.18%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 14        | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 0.79%   |
| Nvidia High Definition Audio Controller                                                           | 9         | 0.71%   |
| Nvidia Audio device                                                                               | 9         | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 8         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 0.63%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 0.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.47%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.39%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 0.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.39%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.32%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.32%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 0.32%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 0.32%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 4         | 0.32%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.32%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 4         | 0.32%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.24%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.24%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.24%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 3         | 0.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series Low Power Engine Audio           | 3         | 0.24%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 3         | 0.24%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 57        | 28.08%  |
| SK hynix            | 50        | 24.63%  |
| Micron Technology   | 26        | 12.81%  |
| Kingston            | 13        | 6.4%    |
| Unknown             | 11        | 5.42%   |
| Unknown (ABCD)      | 8         | 3.94%   |
| Crucial             | 8         | 3.94%   |
| A-DATA Technology   | 6         | 2.96%   |
| Nanya Technology    | 4         | 1.97%   |
| Elpida              | 4         | 1.97%   |
| Ramaxel Technology  | 3         | 1.48%   |
| Patriot             | 2         | 0.99%   |
| Unknown (08B5)      | 1         | 0.49%   |
| Transcend           | 1         | 0.49%   |
| Timetec             | 1         | 0.49%   |
| Teikon              | 1         | 0.49%   |
| Team                | 1         | 0.49%   |
| Strontium           | 1         | 0.49%   |
| Smart               | 1         | 0.49%   |
| PUSKILL             | 1         | 0.49%   |
| Netlist             | 1         | 0.49%   |
| Axiom               | 1         | 0.49%   |
| Avant               | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 7         | 3.29%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 2.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 4         | 1.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 1.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.41%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 3         | 1.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 1.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 1.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 3         | 1.41%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 3         | 1.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 3         | 1.41%   |
| Kingston RAM ACR16D3LS1KFG/4G 4096MB SODIMM DDR3 1600MT/s           | 3         | 1.41%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s            | 3         | 1.41%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.94%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 2         | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.94%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.94%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.94%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.94%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.94%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.94%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 0.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 2         | 0.94%   |
| Samsung RAM M471A5244BB0-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.94%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 2         | 0.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 0.94%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.94%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 2         | 0.94%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 2         | 0.94%   |
| Kingston RAM 99U5428-040.A01LF 4096MB SODIMM DDR3 1334MT/s          | 2         | 0.94%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s             | 2         | 0.94%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s              | 2         | 0.94%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                        | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1333MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s                      | 1         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 1         | 0.47%   |
| Unknown (08B5) RAM IM308GU16N16 8192MB SODIMM DDR3 1333MT/s         | 1         | 0.47%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s              | 1         | 0.47%   |
| Timetec RAM SD3-1600 8192MB SODIMM DDR3 1600MT/s                    | 1         | 0.47%   |
| Teikon RAM TMT351S6EFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s              | 1         | 0.47%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s               | 1         | 0.47%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s                | 1         | 0.47%   |
| Smart RAM SH564128FJ8NZRNSDG 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.47%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                   | 1         | 0.47%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1066MT/s                     | 1         | 0.47%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1066MT/s                     | 1         | 0.47%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                       | 1         | 0.47%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s            | 1         | 0.47%   |
| SK hynix RAM HYMP112S64CP6-Y5 1024MB SODIMM DDR2 667MT/s            | 1         | 0.47%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.47%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 70        | 41.18%  |
| DDR3   | 68        | 40%     |
| LPDDR4 | 14        | 8.24%   |
| LPDDR3 | 7         | 4.12%   |
| DDR2   | 6         | 3.53%   |
| SDRAM  | 5         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 148       | 87.06%  |
| Row Of Chips | 19        | 11.18%  |
| DIMM         | 2         | 1.18%   |
| Chip         | 1         | 0.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 83        | 43.46%  |
| 8192  | 58        | 30.37%  |
| 2048  | 28        | 14.66%  |
| 16384 | 16        | 8.38%   |
| 1024  | 5         | 2.62%   |
| 32768 | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 48        | 25.81%  |
| 2667    | 36        | 19.35%  |
| 3200    | 23        | 12.37%  |
| 2400    | 18        | 9.68%   |
| 1334    | 13        | 6.99%   |
| 1333    | 7         | 3.76%   |
| 2133    | 6         | 3.23%   |
| 4267    | 5         | 2.69%   |
| 3266    | 5         | 2.69%   |
| 1066    | 4         | 2.15%   |
| 667     | 4         | 2.15%   |
| Unknown | 4         | 2.15%   |
| 2048    | 3         | 1.61%   |
| 800     | 3         | 1.61%   |
| 4199    | 2         | 1.08%   |
| 1867    | 2         | 1.08%   |
| 8400    | 1         | 0.54%   |
| 1067    | 1         | 0.54%   |
| 975     | 1         | 0.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 55.56%  |
| Canon               | 2         | 22.22%  |
| Seiko Epson         | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| HP ENVY Photo 6200 series | 2         | 22.22%  |
| Seiko Epson L3110 Series  | 1         | 11.11%  |
| Samsung M2020 Series      | 1         | 11.11%  |
| HP LaserJet 1200          | 1         | 11.11%  |
| HP LaserJet 1000          | 1         | 11.11%  |
| HP DeskJet 1110 series    | 1         | 11.11%  |
| Canon TS3100 series       | 1         | 11.11%  |
| Canon PIXMA MG3000 series | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 66.67%  |
| Canon       | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 66.67%  |
| Canon CanoScan LiDE 90                      | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 200       | 25.97%  |
| Realtek Semiconductor                  | 76        | 9.87%   |
| IMC Networks                           | 73        | 9.48%   |
| Microdia                               | 65        | 8.44%   |
| Sunplus Innovation Technology          | 45        | 5.84%   |
| Acer                                   | 43        | 5.58%   |
| Cheng Uei Precision Industry (Foxlink) | 39        | 5.06%   |
| Suyin                                  | 31        | 4.03%   |
| Quanta                                 | 31        | 4.03%   |
| Syntek                                 | 23        | 2.99%   |
| Apple                                  | 18        | 2.34%   |
| Lite-On Technology                     | 14        | 1.82%   |
| Silicon Motion                         | 13        | 1.69%   |
| Ricoh                                  | 13        | 1.69%   |
| Alcor Micro                            | 13        | 1.69%   |
| Luxvisions Innotech Limited            | 12        | 1.56%   |
| Primax Electronics                     | 7         | 0.91%   |
| Samsung Electronics                    | 6         | 0.78%   |
| ALi                                    | 5         | 0.65%   |
| Sunplus Technology                     | 3         | 0.39%   |
| Sonix Technology                       | 3         | 0.39%   |
| Logitech                               | 3         | 0.39%   |
| Lenovo                                 | 3         | 0.39%   |
| Importek                               | 3         | 0.39%   |
| icSpring                               | 3         | 0.39%   |
| Z-Star Microelectronics                | 2         | 0.26%   |
| SunplusIT                              | 2         | 0.26%   |
| OmniVision Technologies                | 2         | 0.26%   |
| Genesys Logic                          | 2         | 0.26%   |
| Generalplus Technology                 | 2         | 0.26%   |
| GEMBIRD                                | 2         | 0.26%   |
| ARC International                      | 2         | 0.26%   |
| YGTek                                  | 1         | 0.13%   |
| Y Media                                | 1         | 0.13%   |
| Pixart Imaging                         | 1         | 0.13%   |
| Panasonic (Matsushita)                 | 1         | 0.13%   |
| Microsoft                              | 1         | 0.13%   |
| LG Electronics                         | 1         | 0.13%   |
| KYE Systems (Mouse Systems)            | 1         | 0.13%   |
| Huawei Technologies                    | 1         | 0.13%   |
| GenesysLogic Technology                | 1         | 0.13%   |
| DigiTech                               | 1         | 0.13%   |
| Denron                                 | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 25        | 3.24%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 21        | 2.72%   |
| Microdia Integrated_Webcam_HD                                              | 18        | 2.33%   |
| Chicony HD WebCam                                                          | 18        | 2.33%   |
| Chicony TOSHIBA Web Camera - HD                                            | 16        | 2.07%   |
| Realtek USB Camera                                                         | 13        | 1.68%   |
| Realtek Integrated_Webcam_HD                                               | 13        | 1.68%   |
| Microdia Integrated Webcam                                                 | 13        | 1.68%   |
| Syntek Integrated Camera                                                   | 12        | 1.55%   |
| Chicony HP Truevision HD                                                   | 12        | 1.55%   |
| Acer Integrated Camera                                                     | 12        | 1.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 10        | 1.3%    |
| IMC Networks Integrated Camera                                             | 9         | 1.17%   |
| Sunplus HD WebCam                                                          | 8         | 1.04%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 8         | 1.04%   |
| Chicony Lenovo EasyCamera                                                  | 8         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 8         | 1.04%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 8         | 1.04%   |
| Acer Lenovo EasyCamera                                                     | 8         | 1.04%   |
| Sunplus Integrated_Webcam_HD                                               | 7         | 0.91%   |
| Realtek Integrated Webcam                                                  | 7         | 0.91%   |
| Chicony USB2.0 HD UVC WebCam                                               | 7         | 0.91%   |
| Alcor Micro USB 2.0 Camera                                                 | 7         | 0.91%   |
| Syntek Lenovo EasyCamera                                                   | 6         | 0.78%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 6         | 0.78%   |
| Realtek Integrated Webcam HD                                               | 6         | 0.78%   |
| Quanta VGA WebCam                                                          | 6         | 0.78%   |
| Quanta HD User Facing                                                      | 6         | 0.78%   |
| Chicony USB 2.0 Camera                                                     | 6         | 0.78%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 6         | 0.78%   |
| Chicony HP Truevision HD camera                                            | 6         | 0.78%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 5         | 0.65%   |
| Quanta HP Webcam                                                           | 5         | 0.65%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 0.65%   |
| Microdia Webcam Vitade AF                                                  | 5         | 0.65%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 5         | 0.65%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 5         | 0.65%   |
| Lite-On HP HD Camera                                                       | 5         | 0.65%   |
| Chicony VGA Webcam                                                         | 5         | 0.65%   |
| Chicony HP Webcam                                                          | 5         | 0.65%   |
| Chicony HP HD Webcam                                                       | 5         | 0.65%   |
| Chicony HD User Facing                                                     | 5         | 0.65%   |
| Chicony EasyCamera                                                         | 5         | 0.65%   |
| Chicony CNFA078                                                            | 5         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 5         | 0.65%   |
| Apple FaceTime HD Camera                                                   | 5         | 0.65%   |
| ALi Gateway Webcam                                                         | 5         | 0.65%   |
| Acer Lenovo Integrated Webcam                                              | 5         | 0.65%   |
| Suyin HP TrueVision HD                                                     | 4         | 0.52%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 4         | 0.52%   |
| Sunplus Asus Webcam                                                        | 4         | 0.52%   |
| Ricoh USB2.0 Camera                                                        | 4         | 0.52%   |
| Realtek Lenovo EasyCamera                                                  | 4         | 0.52%   |
| Realtek HP Truevision HD integrated webcam                                 | 4         | 0.52%   |
| Realtek HP Truevision HD                                                   | 4         | 0.52%   |
| IMC Networks USB Camera                                                    | 4         | 0.52%   |
| Chicony HP HD Webcam [Fixed]                                               | 4         | 0.52%   |
| Chicony HP HD Camera                                                       | 4         | 0.52%   |
| Chicony CNF9055 Toshiba Webcam                                             | 4         | 0.52%   |
| Alcor Micro Asus Integrated Webcam                                         | 4         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 65        | 46.76%  |
| Upek                       | 17        | 12.23%  |
| Shenzhen Goodix Technology | 16        | 11.51%  |
| AuthenTec                  | 15        | 10.79%  |
| Synaptics                  | 9         | 6.47%   |
| Elan Microelectronics      | 7         | 5.04%   |
| LighTuning Technology      | 5         | 3.6%    |
| STMicroelectronics         | 4         | 2.88%   |
| Focal-systems.Corp         | 1         | 0.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 11.51%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 10.07%  |
| Shenzhen Goodix  Fingerprint Device                                        | 10        | 7.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 6.47%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.32%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 4.32%   |
| AuthenTec AES2810                                                          | 6         | 4.32%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.88%   |
| Validity Sensors VFS491                                                    | 4         | 2.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.88%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 2.88%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 2.88%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.88%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.16%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.16%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.16%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 2.16%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.16%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 2.16%   |
| AuthenTec AES1600                                                          | 3         | 2.16%   |
| Unknown                                                                    | 3         | 2.16%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.44%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.44%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.44%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.44%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.44%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.72%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.72%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.72%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.72%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.72%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.72%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.72%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 35        | 55.56%  |
| Alcor Micro                       | 10        | 15.87%  |
| Upek                              | 5         | 7.94%   |
| O2 Micro                          | 5         | 7.94%   |
| Lenovo                            | 3         | 4.76%   |
| Yubico.com                        | 2         | 3.17%   |
| VASCO Data Security International | 1         | 1.59%   |
| SCM Microsystems                  | 1         | 1.59%   |
| OmniKey                           | 1         | 1.59%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 20.63%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 17.46%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 15.87%  |
| Broadcom 5880                                                                | 9         | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 7.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 7.94%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.76%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 3.17%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 3.17%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 1.59%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.59%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.59%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 605       | 66.63%  |
| 1     | 242       | 26.65%  |
| 2     | 55        | 6.06%   |
| 3     | 6         | 0.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 135       | 37.19%  |
| Chipcard                 | 56        | 15.43%  |
| Graphics card            | 55        | 15.15%  |
| Multimedia controller    | 38        | 10.47%  |
| Net/wireless             | 36        | 9.92%   |
| Bluetooth                | 13        | 3.58%   |
| Storage                  | 12        | 3.31%   |
| Sound                    | 4         | 1.1%    |
| Net/ethernet             | 3         | 0.83%   |
| Flash memory             | 2         | 0.55%   |
| Camera                   | 2         | 0.55%   |
| Unclassified device      | 1         | 0.28%   |
| Storage/ide              | 1         | 0.28%   |
| Network                  | 1         | 0.28%   |
| Modem                    | 1         | 0.28%   |
| Dvb card                 | 1         | 0.28%   |
| Communication controller | 1         | 0.28%   |
| Card reader              | 1         | 0.28%   |

