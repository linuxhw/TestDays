ArcoLinux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

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

Total: 1187

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Gaming Laptop 1... | [446a548122](https://linux-hardware.org/?probe=446a548122) | Apr 30, 2023 |
| Acer          | Aspire A514-54G             | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [0ea5e1926e](https://linux-hardware.org/?probe=0ea5e1926e) | Apr 29, 2023 |
| Dell          | Inspiron 3558               | [1ef93daf0b](https://linux-hardware.org/?probe=1ef93daf0b) | Apr 28, 2023 |
| Dell          | Latitude E6440              | [d55c77598b](https://linux-hardware.org/?probe=d55c77598b) | Apr 27, 2023 |
| Dell          | Inspiron 3558               | [add3c03eef](https://linux-hardware.org/?probe=add3c03eef) | Apr 26, 2023 |
| System76      | Oryx Pro                    | [298bf97b70](https://linux-hardware.org/?probe=298bf97b70) | Apr 25, 2023 |
| Dell          | Inspiron 5759               | [90fa428095](https://linux-hardware.org/?probe=90fa428095) | Apr 25, 2023 |
| Dell          | Inspiron 5548               | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [5b14b21a19](https://linux-hardware.org/?probe=5b14b21a19) | Apr 21, 2023 |
| Acer          | Swift SF114-32              | [7641434e4d](https://linux-hardware.org/?probe=7641434e4d) | Apr 21, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [4e69a80310](https://linux-hardware.org/?probe=4e69a80310) | Apr 21, 2023 |
| Packard Be... | EasyNote TSX62HR            | [7e7dbc9acd](https://linux-hardware.org/?probe=7e7dbc9acd) | Apr 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c10e38e18e](https://linux-hardware.org/?probe=c10e38e18e) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [2afe988f2e](https://linux-hardware.org/?probe=2afe988f2e) | Apr 20, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [8e02f43636](https://linux-hardware.org/?probe=8e02f43636) | Apr 20, 2023 |
| Acer          | Predator G9-793             | [664d6de816](https://linux-hardware.org/?probe=664d6de816) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | [46ade409df](https://linux-hardware.org/?probe=46ade409df) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [618b59dac2](https://linux-hardware.org/?probe=618b59dac2) | Apr 19, 2023 |
| Acer          | Aspire A715-42G             | [954388c5e0](https://linux-hardware.org/?probe=954388c5e0) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4185aada87](https://linux-hardware.org/?probe=4185aada87) | Apr 19, 2023 |
| Lenovo        | E41-25 81FS                 | [10bfabc1b8](https://linux-hardware.org/?probe=10bfabc1b8) | Apr 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6ce11cef12](https://linux-hardware.org/?probe=6ce11cef12) | Apr 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [efdcb6b99e](https://linux-hardware.org/?probe=efdcb6b99e) | Apr 18, 2023 |
| Dell          | Inspiron 5566               | [3decfdc1f6](https://linux-hardware.org/?probe=3decfdc1f6) | Apr 15, 2023 |
| Acer          | Aspire E5-575G              | [6f8dbb2e8e](https://linux-hardware.org/?probe=6f8dbb2e8e) | Apr 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2e6b5600aa](https://linux-hardware.org/?probe=2e6b5600aa) | Apr 14, 2023 |
| Dell          | Latitude 3590               | [eed6f4df10](https://linux-hardware.org/?probe=eed6f4df10) | Apr 14, 2023 |
| HP            | ENVY 15                     | [5ecc7b36c8](https://linux-hardware.org/?probe=5ecc7b36c8) | Apr 09, 2023 |
| ASUSTek       | Zenbook UX7602ZM            | [aeded4c133](https://linux-hardware.org/?probe=aeded4c133) | Apr 08, 2023 |
| HP            | Pavilion dv4                | [a554538ed8](https://linux-hardware.org/?probe=a554538ed8) | Apr 07, 2023 |
| ASUSTek       | K54C                        | [4f37849c94](https://linux-hardware.org/?probe=4f37849c94) | Apr 07, 2023 |
| Unknown       | Unknown                     | [ebc3f9d008](https://linux-hardware.org/?probe=ebc3f9d008) | Apr 06, 2023 |
| HP            | Pavilion dv7                | [bdb5d286b5](https://linux-hardware.org/?probe=bdb5d286b5) | Apr 06, 2023 |
| Dell          | Latitude 3510               | [e927d04a2d](https://linux-hardware.org/?probe=e927d04a2d) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [6eb533f1d7](https://linux-hardware.org/?probe=6eb533f1d7) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490s 20NXS0DS0... | [1228998af5](https://linux-hardware.org/?probe=1228998af5) | Mar 31, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7554f35f1d](https://linux-hardware.org/?probe=7554f35f1d) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [2f1975360e](https://linux-hardware.org/?probe=2f1975360e) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [b960038661](https://linux-hardware.org/?probe=b960038661) | Mar 27, 2023 |
| ASUSTek       | X540UP                      | [39802560c1](https://linux-hardware.org/?probe=39802560c1) | Mar 27, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [1ed601999d](https://linux-hardware.org/?probe=1ed601999d) | Mar 27, 2023 |
| Unknown       | Unknown                     | [1988691e71](https://linux-hardware.org/?probe=1988691e71) | Mar 27, 2023 |
| Unknown       | Unknown                     | [dd081eb573](https://linux-hardware.org/?probe=dd081eb573) | Mar 27, 2023 |
| ASUSTek       | X550LD                      | [6ac498fa82](https://linux-hardware.org/?probe=6ac498fa82) | Mar 26, 2023 |
| Toshiba       | Satellite C50-A510          | [69eb2dad8f](https://linux-hardware.org/?probe=69eb2dad8f) | Mar 26, 2023 |
| Dell          | XPS 13 7390                 | [7c10ad8eb9](https://linux-hardware.org/?probe=7c10ad8eb9) | Mar 26, 2023 |
| MSI           | GT70                        | [8b00b28b12](https://linux-hardware.org/?probe=8b00b28b12) | Mar 26, 2023 |
| Medion        | P7624                       | [fe5c568f41](https://linux-hardware.org/?probe=fe5c568f41) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [22e7978cc8](https://linux-hardware.org/?probe=22e7978cc8) | Mar 26, 2023 |
| Medion        | P7624                       | [778f5948f1](https://linux-hardware.org/?probe=778f5948f1) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [f889f2ddf5](https://linux-hardware.org/?probe=f889f2ddf5) | Mar 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [513b14ace5](https://linux-hardware.org/?probe=513b14ace5) | Mar 25, 2023 |
| Lenovo        | E41-25 81FS                 | [9d9e4e184f](https://linux-hardware.org/?probe=9d9e4e184f) | Mar 25, 2023 |
| Lenovo        | ThinkPad Edge S430 33643... | [f6b05c3b0b](https://linux-hardware.org/?probe=f6b05c3b0b) | Mar 21, 2023 |
| System76      | Oryx Pro                    | [b784685da3](https://linux-hardware.org/?probe=b784685da3) | Mar 21, 2023 |
| System76      | Pangolin                    | [ee7dd00fbf](https://linux-hardware.org/?probe=ee7dd00fbf) | Mar 19, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [49df72f291](https://linux-hardware.org/?probe=49df72f291) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [1f939ee045](https://linux-hardware.org/?probe=1f939ee045) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [5e6e5276e3](https://linux-hardware.org/?probe=5e6e5276e3) | Mar 18, 2023 |
| Chuwi         | HeroBook Air                | [e9d0a5dd9a](https://linux-hardware.org/?probe=e9d0a5dd9a) | Mar 18, 2023 |
| Dell          | Latitude 3410               | [8c71ef60d0](https://linux-hardware.org/?probe=8c71ef60d0) | Mar 18, 2023 |
| Chuwi         | GemiBook Pro                | [7bd3a3e64c](https://linux-hardware.org/?probe=7bd3a3e64c) | Mar 18, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [593bd6b3ac](https://linux-hardware.org/?probe=593bd6b3ac) | Mar 17, 2023 |
| HUAWEI        | KLVL-WXX9                   | [7630033ffb](https://linux-hardware.org/?probe=7630033ffb) | Mar 15, 2023 |
| Acer          | Aspire A715-74G             | [54d17115b9](https://linux-hardware.org/?probe=54d17115b9) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | [79932e56ad](https://linux-hardware.org/?probe=79932e56ad) | Mar 13, 2023 |
| MSI           | GV62 7RE                    | [1de50d9986](https://linux-hardware.org/?probe=1de50d9986) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Acer          | Aspire A515-45              | [1fc9174c06](https://linux-hardware.org/?probe=1fc9174c06) | Mar 11, 2023 |
| Dell          | Inspiron 5420               | [9e6843fe2e](https://linux-hardware.org/?probe=9e6843fe2e) | Mar 10, 2023 |
| Dell          | Inspiron 5420               | [77d13c9c12](https://linux-hardware.org/?probe=77d13c9c12) | Mar 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [dd06fbb0f9](https://linux-hardware.org/?probe=dd06fbb0f9) | Mar 10, 2023 |
| Chuwi         | GemiBook Pro                | [23a97367b7](https://linux-hardware.org/?probe=23a97367b7) | Mar 09, 2023 |
| Dell          | Inspiron 7737               | [b46bb47333](https://linux-hardware.org/?probe=b46bb47333) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [42e5be35d6](https://linux-hardware.org/?probe=42e5be35d6) | Mar 08, 2023 |
| Lenovo        | Z51-70 80K6                 | [676eaa7960](https://linux-hardware.org/?probe=676eaa7960) | Mar 06, 2023 |
| Dell          | G7 7500                     | [d5abfa6d0d](https://linux-hardware.org/?probe=d5abfa6d0d) | Mar 06, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [a6c7741454](https://linux-hardware.org/?probe=a6c7741454) | Mar 06, 2023 |
| Dell          | G7 7500                     | [bfaad602b7](https://linux-hardware.org/?probe=bfaad602b7) | Mar 06, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [3e484b7bac](https://linux-hardware.org/?probe=3e484b7bac) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [edf5f00bf8](https://linux-hardware.org/?probe=edf5f00bf8) | Mar 01, 2023 |
| Sony          | VPCEH10EB                   | [9c8bb09559](https://linux-hardware.org/?probe=9c8bb09559) | Mar 01, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [eca37862f3](https://linux-hardware.org/?probe=eca37862f3) | Mar 01, 2023 |
| Toshiba       | Satellite C55-A             | [6bd63e7974](https://linux-hardware.org/?probe=6bd63e7974) | Mar 01, 2023 |
| Acer          | Swift SF314-43              | [4f2c05c854](https://linux-hardware.org/?probe=4f2c05c854) | Feb 28, 2023 |
| Lenovo        | ThinkPad L470 20J4003WGE    | [42f6425b2d](https://linux-hardware.org/?probe=42f6425b2d) | Feb 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS35H02    | [a396e54378](https://linux-hardware.org/?probe=a396e54378) | Feb 25, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [31bd9738ca](https://linux-hardware.org/?probe=31bd9738ca) | Feb 25, 2023 |
| Dell          | XPS 17 9710                 | [4066713adb](https://linux-hardware.org/?probe=4066713adb) | Feb 24, 2023 |
| ASUSTek       | X55VD                       | [6b71d8369a](https://linux-hardware.org/?probe=6b71d8369a) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [65f3a9d691](https://linux-hardware.org/?probe=65f3a9d691) | Feb 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [88be67bbc1](https://linux-hardware.org/?probe=88be67bbc1) | Feb 21, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [28a0794b08](https://linux-hardware.org/?probe=28a0794b08) | Feb 20, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [e87f489185](https://linux-hardware.org/?probe=e87f489185) | Feb 20, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [6f65703034](https://linux-hardware.org/?probe=6f65703034) | Feb 19, 2023 |
| HP            | ENVY 15                     | [7d53c3db41](https://linux-hardware.org/?probe=7d53c3db41) | Feb 19, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [2b1fc8eb09](https://linux-hardware.org/?probe=2b1fc8eb09) | Feb 19, 2023 |
| HP            | ENVY 15                     | [e59ac2cec0](https://linux-hardware.org/?probe=e59ac2cec0) | Feb 17, 2023 |
| Chuwi         | GemiBook Pro                | [af76238a5c](https://linux-hardware.org/?probe=af76238a5c) | Feb 17, 2023 |
| HP            | ZBook Studio G3             | [af86e6cb72](https://linux-hardware.org/?probe=af86e6cb72) | Feb 17, 2023 |
| Acer          | Predator PH315-52           | [480da10129](https://linux-hardware.org/?probe=480da10129) | Feb 12, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [6047c68386](https://linux-hardware.org/?probe=6047c68386) | Feb 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e4340c10db](https://linux-hardware.org/?probe=e4340c10db) | Feb 10, 2023 |
| System76      | Oryx Pro                    | [20fad7d628](https://linux-hardware.org/?probe=20fad7d628) | Feb 10, 2023 |
| HP            | Pavilion dv7                | [2f694f36cc](https://linux-hardware.org/?probe=2f694f36cc) | Feb 10, 2023 |
| HP            | EliteBook 840 G4            | [a60a4191b8](https://linux-hardware.org/?probe=a60a4191b8) | Feb 10, 2023 |
| Toshiba       | Satellite L70-B             | [f47ccc62c7](https://linux-hardware.org/?probe=f47ccc62c7) | Feb 09, 2023 |
| Toshiba       | Satellite L70-B             | [68ba5288c0](https://linux-hardware.org/?probe=68ba5288c0) | Feb 09, 2023 |
| Acer          | Aspire A515-51              | [d68fb933eb](https://linux-hardware.org/?probe=d68fb933eb) | Feb 09, 2023 |
| Dell          | Inspiron 3558               | [420ccdfca6](https://linux-hardware.org/?probe=420ccdfca6) | Feb 07, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | [2d40451b53](https://linux-hardware.org/?probe=2d40451b53) | Feb 06, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | [a865465884](https://linux-hardware.org/?probe=a865465884) | Feb 04, 2023 |
| Lenovo        | ThinkPad T460 20FMS07000    | [a41f5126d3](https://linux-hardware.org/?probe=a41f5126d3) | Feb 04, 2023 |
| Monster       | TULPAR T5 V20.1             | [b224ac6a46](https://linux-hardware.org/?probe=b224ac6a46) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS07000    | [62d193dd49](https://linux-hardware.org/?probe=62d193dd49) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS07000    | [181cdf6a58](https://linux-hardware.org/?probe=181cdf6a58) | Feb 03, 2023 |
| MSI           | Raider GE76 12UHS           | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| HP            | Folio 13                    | [214197bef4](https://linux-hardware.org/?probe=214197bef4) | Jan 25, 2023 |
| Acer          | Aspire A515-52G             | [a95489f0b7](https://linux-hardware.org/?probe=a95489f0b7) | Jan 24, 2023 |
| Chuwi         | GemiBook Pro                | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| Dell          | Inspiron 7472               | [6395ea422c](https://linux-hardware.org/?probe=6395ea422c) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [66287c2f72](https://linux-hardware.org/?probe=66287c2f72) | Jan 22, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [369b022d8e](https://linux-hardware.org/?probe=369b022d8e) | Jan 22, 2023 |
| Timi          | TM1701                      | [bec2d3a691](https://linux-hardware.org/?probe=bec2d3a691) | Jan 22, 2023 |
| Dell          | Latitude E5400              | [ee6e466820](https://linux-hardware.org/?probe=ee6e466820) | Jan 22, 2023 |
| Dell          | Latitude E5400              | [f61d1e0868](https://linux-hardware.org/?probe=f61d1e0868) | Jan 22, 2023 |
| Dell          | Latitude 7480               | [0d4396d043](https://linux-hardware.org/?probe=0d4396d043) | Jan 21, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [ae81429a64](https://linux-hardware.org/?probe=ae81429a64) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| MSI           | GL65 Leopard 10SFK          | [8aa69f1dae](https://linux-hardware.org/?probe=8aa69f1dae) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [09dbcb3ae4](https://linux-hardware.org/?probe=09dbcb3ae4) | Jan 20, 2023 |
| MSI           | GL65 Leopard 10SFK          | [0ea710bda6](https://linux-hardware.org/?probe=0ea710bda6) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [a929c23a1b](https://linux-hardware.org/?probe=a929c23a1b) | Jan 20, 2023 |
| Acer          | Aspire A715-75G             | [68d2fcbdcf](https://linux-hardware.org/?probe=68d2fcbdcf) | Jan 18, 2023 |
| Alienware     | M17xR4                      | [5cce1e5932](https://linux-hardware.org/?probe=5cce1e5932) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [0306622813](https://linux-hardware.org/?probe=0306622813) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [84edd23a21](https://linux-hardware.org/?probe=84edd23a21) | Jan 18, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [6643ab6cf1](https://linux-hardware.org/?probe=6643ab6cf1) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [91fed2c125](https://linux-hardware.org/?probe=91fed2c125) | Jan 16, 2023 |
| Chuwi         | GemiBook Pro                | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [0ece2f508b](https://linux-hardware.org/?probe=0ece2f508b) | Jan 14, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | [f34e2c982f](https://linux-hardware.org/?probe=f34e2c982f) | Jan 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e275cc7891](https://linux-hardware.org/?probe=e275cc7891) | Jan 13, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [d859e0ff10](https://linux-hardware.org/?probe=d859e0ff10) | Jan 12, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [a786384700](https://linux-hardware.org/?probe=a786384700) | Jan 10, 2023 |
| HP            | ENVY Notebook               | [ff8cd12017](https://linux-hardware.org/?probe=ff8cd12017) | Jan 10, 2023 |
| System76      | Oryx Pro                    | [e3f5a24a6e](https://linux-hardware.org/?probe=e3f5a24a6e) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [2923dcfe6f](https://linux-hardware.org/?probe=2923dcfe6f) | Jan 09, 2023 |
| Dell          | Precision M3800             | [ca9cfa3f5a](https://linux-hardware.org/?probe=ca9cfa3f5a) | Jan 07, 2023 |
| Dell          | Precision M3800             | [454d4b6b55](https://linux-hardware.org/?probe=454d4b6b55) | Jan 07, 2023 |
| Acer          | Predator G9-793             | [5256ec6943](https://linux-hardware.org/?probe=5256ec6943) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [b345c4d626](https://linux-hardware.org/?probe=b345c4d626) | Jan 06, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [9320df061f](https://linux-hardware.org/?probe=9320df061f) | Jan 06, 2023 |
| System76      | Pangolin                    | [823d50a20f](https://linux-hardware.org/?probe=823d50a20f) | Jan 06, 2023 |
| HP            | ENVY 15                     | [e91c6321b3](https://linux-hardware.org/?probe=e91c6321b3) | Jan 04, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [23bfcb7f4c](https://linux-hardware.org/?probe=23bfcb7f4c) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [2ede2771be](https://linux-hardware.org/?probe=2ede2771be) | Jan 03, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [9ba40bc6b5](https://linux-hardware.org/?probe=9ba40bc6b5) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | [893d1002f6](https://linux-hardware.org/?probe=893d1002f6) | Jan 02, 2023 |
| Dell          | Precision 7740              | [952da37737](https://linux-hardware.org/?probe=952da37737) | Jan 02, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [31a0bdb593](https://linux-hardware.org/?probe=31a0bdb593) | Jan 02, 2023 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [56e961b0ca](https://linux-hardware.org/?probe=56e961b0ca) | Jan 01, 2023 |
| HP            | Folio 13                    | [9f00cfe432](https://linux-hardware.org/?probe=9f00cfe432) | Dec 31, 2022 |
| HP            | Folio 13                    | [3ed5b405cb](https://linux-hardware.org/?probe=3ed5b405cb) | Dec 31, 2022 |
| HP            | EliteBook 830 G5            | [bdd6f3912d](https://linux-hardware.org/?probe=bdd6f3912d) | Dec 30, 2022 |
| Packard Be... | EasyNote TE69HW             | [9613dfc76b](https://linux-hardware.org/?probe=9613dfc76b) | Dec 28, 2022 |
| MSI           | Raider GE77HX 12UGS         | [9f7185ccd7](https://linux-hardware.org/?probe=9f7185ccd7) | Dec 27, 2022 |
| Dell          | Inspiron 7580               | [eb5b708877](https://linux-hardware.org/?probe=eb5b708877) | Dec 22, 2022 |
| Sony          | SVF15N26CXB                 | [ffc2ea8936](https://linux-hardware.org/?probe=ffc2ea8936) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4906017260](https://linux-hardware.org/?probe=4906017260) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [085b8c23b4](https://linux-hardware.org/?probe=085b8c23b4) | Dec 21, 2022 |
| MSI           | GL75 Leopard 10SDK          | [a269c3ef8a](https://linux-hardware.org/?probe=a269c3ef8a) | Dec 20, 2022 |
| ASUSTek       | X555QA                      | [3a7e8867bd](https://linux-hardware.org/?probe=3a7e8867bd) | Dec 19, 2022 |
| Dell          | Latitude 5580               | [c8b402d4df](https://linux-hardware.org/?probe=c8b402d4df) | Dec 18, 2022 |
| Dell          | Latitude 5580               | [b45e1798cc](https://linux-hardware.org/?probe=b45e1798cc) | Dec 18, 2022 |
| HP            | EliteBook 850 G1            | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| MSI           | GE72VR 6RF                  | [ce2ebf80a1](https://linux-hardware.org/?probe=ce2ebf80a1) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Apple         | MacBookAir6,2               | [65bc0e828c](https://linux-hardware.org/?probe=65bc0e828c) | Dec 08, 2022 |
| LG Electro... | C500                        | [078e13cadd](https://linux-hardware.org/?probe=078e13cadd) | Dec 08, 2022 |
| MSI           | GE72VR 6RF                  | [23a83a5e8e](https://linux-hardware.org/?probe=23a83a5e8e) | Dec 06, 2022 |
| ASUSTek       | X556UQK                     | [2f693620e1](https://linux-hardware.org/?probe=2f693620e1) | Dec 06, 2022 |
| Dell          | Inspiron 5502               | [311215d00b](https://linux-hardware.org/?probe=311215d00b) | Dec 05, 2022 |
| ASUSTek       | X550MD                      | [e5058b43c3](https://linux-hardware.org/?probe=e5058b43c3) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ac92442dbc](https://linux-hardware.org/?probe=ac92442dbc) | Dec 04, 2022 |
| ASUSTek       | X555QA                      | [677ef3b3f2](https://linux-hardware.org/?probe=677ef3b3f2) | Dec 03, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| MSI           | Katana GF76 11UD            | [186950bae6](https://linux-hardware.org/?probe=186950bae6) | Nov 29, 2022 |
| MSI           | Katana GF76 11UD            | [48bb9075a7](https://linux-hardware.org/?probe=48bb9075a7) | Nov 29, 2022 |
| Lenovo        | B51-80 80LM                 | [3c50a742a9](https://linux-hardware.org/?probe=3c50a742a9) | Nov 28, 2022 |
| System76      | Oryx Pro                    | [c7d2918a69](https://linux-hardware.org/?probe=c7d2918a69) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [b792955af6](https://linux-hardware.org/?probe=b792955af6) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [033e206fab](https://linux-hardware.org/?probe=033e206fab) | Nov 25, 2022 |
| HP            | EliteBook 840 G1            | [1071e10a2c](https://linux-hardware.org/?probe=1071e10a2c) | Nov 23, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [88bbdb925b](https://linux-hardware.org/?probe=88bbdb925b) | Nov 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | [f7ebd3f633](https://linux-hardware.org/?probe=f7ebd3f633) | Nov 20, 2022 |
| Fujitsu       | LIFEBOOK U759               | [945910eb8a](https://linux-hardware.org/?probe=945910eb8a) | Nov 18, 2022 |
| HUAWEI        | HLYL-WXX9                   | [560c24bf74](https://linux-hardware.org/?probe=560c24bf74) | Nov 18, 2022 |
| ASUSTek       | K52Jc                       | [375bc280d3](https://linux-hardware.org/?probe=375bc280d3) | Nov 18, 2022 |
| HP            | 250 G7 Notebook PC          | [10b5bb5eab](https://linux-hardware.org/?probe=10b5bb5eab) | Nov 17, 2022 |
| HP            | 250 G7 Notebook PC          | [c765249482](https://linux-hardware.org/?probe=c765249482) | Nov 17, 2022 |
| Dell          | Vostro 3550                 | [a195c7598f](https://linux-hardware.org/?probe=a195c7598f) | Nov 14, 2022 |
| Dell          | Vostro 3550                 | [2176ff6bc0](https://linux-hardware.org/?probe=2176ff6bc0) | Nov 14, 2022 |
| Toshiba       | Satellite L775              | [a8c9c0ffda](https://linux-hardware.org/?probe=a8c9c0ffda) | Nov 12, 2022 |
| Dell          | Latitude 3380               | [f770a70f68](https://linux-hardware.org/?probe=f770a70f68) | Nov 12, 2022 |
| HP            | EliteBook 840 G2            | [91bdce735b](https://linux-hardware.org/?probe=91bdce735b) | Nov 12, 2022 |
| Dell          | Precision 3571              | [039ece6391](https://linux-hardware.org/?probe=039ece6391) | Nov 10, 2022 |
| CSL-Comput... | R Evolve C14i               | [2a99a4d733](https://linux-hardware.org/?probe=2a99a4d733) | Nov 10, 2022 |
| Dell          | XPS 15 9570                 | [44c3eceeee](https://linux-hardware.org/?probe=44c3eceeee) | Nov 10, 2022 |
| Timi          | RedmiBook Pro 15S           | [02b3508a99](https://linux-hardware.org/?probe=02b3508a99) | Nov 09, 2022 |
| Dell          | Latitude E5470              | [a9c69c7418](https://linux-hardware.org/?probe=a9c69c7418) | Nov 09, 2022 |
| Dell          | Precision 3571              | [d305848533](https://linux-hardware.org/?probe=d305848533) | Nov 08, 2022 |
| Dell          | Precision 3571              | [681a655e1c](https://linux-hardware.org/?probe=681a655e1c) | Nov 08, 2022 |
| HP            | Pavilion dv6                | [f715c6e15c](https://linux-hardware.org/?probe=f715c6e15c) | Nov 07, 2022 |
| HP            | Laptop 15-da0xxx            | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [caf9066e2a](https://linux-hardware.org/?probe=caf9066e2a) | Nov 06, 2022 |
| TUXEDO        | Aura 15 Gen2                | [681d0b959b](https://linux-hardware.org/?probe=681d0b959b) | Nov 05, 2022 |
| Alienware     | 14                          | [0c11295ebe](https://linux-hardware.org/?probe=0c11295ebe) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | [813cfb5bdf](https://linux-hardware.org/?probe=813cfb5bdf) | Nov 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f790aefcad](https://linux-hardware.org/?probe=f790aefcad) | Nov 03, 2022 |
| Acer          | Aspire E1-571               | [d81e8b3ea2](https://linux-hardware.org/?probe=d81e8b3ea2) | Nov 01, 2022 |
| ASUSTek       | Zephyrus S GX531GS_GX531... | [4823244248](https://linux-hardware.org/?probe=4823244248) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | [69768228d4](https://linux-hardware.org/?probe=69768228d4) | Nov 01, 2022 |
| Dell          | Vostro 3500                 | [a3abf820e1](https://linux-hardware.org/?probe=a3abf820e1) | Oct 31, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [73aa3e4a7e](https://linux-hardware.org/?probe=73aa3e4a7e) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| HUAWEI        | VLT-WX0                     | [7b414a3c7c](https://linux-hardware.org/?probe=7b414a3c7c) | Oct 29, 2022 |
| Dell          | Inspiron 5590               | [f1a5637218](https://linux-hardware.org/?probe=f1a5637218) | Oct 27, 2022 |
| Dell          | Precision 7530              | [daee9e9524](https://linux-hardware.org/?probe=daee9e9524) | Oct 26, 2022 |
| Dell          | Inspiron 5590               | [802e0f0c61](https://linux-hardware.org/?probe=802e0f0c61) | Oct 24, 2022 |
| NEC Comput... | PC-VK27MXZCG                | [04c88c4087](https://linux-hardware.org/?probe=04c88c4087) | Oct 24, 2022 |
| Dell          | Latitude E6440              | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c16378c914](https://linux-hardware.org/?probe=c16378c914) | Oct 23, 2022 |
| Lenovo        | ThinkPad Edge S430 33643... | [a73e4a9246](https://linux-hardware.org/?probe=a73e4a9246) | Oct 23, 2022 |
| Toshiba       | Satellite L775              | [180b9ab9ae](https://linux-hardware.org/?probe=180b9ab9ae) | Oct 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [aca44a3eab](https://linux-hardware.org/?probe=aca44a3eab) | Oct 20, 2022 |
| Lenovo        | ThinkPad T450s 20BWA0DW0... | [117e1e8e03](https://linux-hardware.org/?probe=117e1e8e03) | Oct 20, 2022 |
| Acer          | Aspire 7720Z                | [164c89c324](https://linux-hardware.org/?probe=164c89c324) | Oct 20, 2022 |
| HUAWEI        | HLYL-WXX9                   | [6a7e7ac7ce](https://linux-hardware.org/?probe=6a7e7ac7ce) | Oct 19, 2022 |
| TUXEDO        | Aura 15 Gen2                | [f5d5e3fb86](https://linux-hardware.org/?probe=f5d5e3fb86) | Oct 19, 2022 |
| HP            | Pavilion g7                 | [19048aa8f0](https://linux-hardware.org/?probe=19048aa8f0) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [e1a32857ba](https://linux-hardware.org/?probe=e1a32857ba) | Oct 19, 2022 |
| Dell          | Latitude 3380               | [352bedd96b](https://linux-hardware.org/?probe=352bedd96b) | Oct 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [9357d641ef](https://linux-hardware.org/?probe=9357d641ef) | Oct 18, 2022 |
| Sony          | SVE14A27CXH                 | [85398590ee](https://linux-hardware.org/?probe=85398590ee) | Oct 18, 2022 |
| Sony          | SVE14A27CXH                 | [76a531edcf](https://linux-hardware.org/?probe=76a531edcf) | Oct 18, 2022 |
| LG Electro... | C500                        | [f688cc0536](https://linux-hardware.org/?probe=f688cc0536) | Oct 18, 2022 |
| Dell          | Latitude 3380               | [76a82ca1e6](https://linux-hardware.org/?probe=76a82ca1e6) | Oct 17, 2022 |
| Dell          | Latitude 3380               | [ab6969eabd](https://linux-hardware.org/?probe=ab6969eabd) | Oct 17, 2022 |
| HP            | Laptop 15s-eq2xxx           | [57436f7d31](https://linux-hardware.org/?probe=57436f7d31) | Oct 17, 2022 |
| Dell          | Latitude 3380               | [901d7614e5](https://linux-hardware.org/?probe=901d7614e5) | Oct 17, 2022 |
| Acer          | Aspire 5750G                | [f7e44be1b5](https://linux-hardware.org/?probe=f7e44be1b5) | Oct 17, 2022 |
| Dell          | Latitude 3350               | [4c634a0308](https://linux-hardware.org/?probe=4c634a0308) | Oct 16, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [411a334a74](https://linux-hardware.org/?probe=411a334a74) | Oct 16, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d928c22430](https://linux-hardware.org/?probe=d928c22430) | Oct 14, 2022 |
| Schenker      | SLIM_13_14_SSL13_14L18      | [b7bd0894f2](https://linux-hardware.org/?probe=b7bd0894f2) | Oct 13, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [11573d282c](https://linux-hardware.org/?probe=11573d282c) | Oct 13, 2022 |
| HP            | Laptop 14s-dk1xxx           | [1eb06e8e12](https://linux-hardware.org/?probe=1eb06e8e12) | Oct 12, 2022 |
| ASUSTek       | X705UDR                     | [5c8601bb4f](https://linux-hardware.org/?probe=5c8601bb4f) | Oct 11, 2022 |
| System76      | Oryx Pro                    | [5e2fd69a86](https://linux-hardware.org/?probe=5e2fd69a86) | Oct 11, 2022 |
| Acer          | Aspire E5-575G              | [ed74f1da66](https://linux-hardware.org/?probe=ed74f1da66) | Oct 10, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [593d28a4cf](https://linux-hardware.org/?probe=593d28a4cf) | Oct 08, 2022 |
| Dell          | Inspiron 7559               | [c963b4157a](https://linux-hardware.org/?probe=c963b4157a) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ae8f71dbd3](https://linux-hardware.org/?probe=ae8f71dbd3) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d389c9fa00](https://linux-hardware.org/?probe=d389c9fa00) | Oct 05, 2022 |
| MSI           | CR61 3M                     | [496910c25b](https://linux-hardware.org/?probe=496910c25b) | Oct 04, 2022 |
| Lenovo        | ThinkPad Edge 03193UG       | [49afe38831](https://linux-hardware.org/?probe=49afe38831) | Oct 04, 2022 |
| Sony          | SVE14A27CXH                 | [09cb572f35](https://linux-hardware.org/?probe=09cb572f35) | Oct 03, 2022 |
| MSI           | CR61 3M                     | [818a721825](https://linux-hardware.org/?probe=818a721825) | Oct 02, 2022 |
| HUAWEI        | HLYL-WXX9                   | [318010d949](https://linux-hardware.org/?probe=318010d949) | Oct 01, 2022 |
| ASUSTek       | X580VD                      | [e7ef06706d](https://linux-hardware.org/?probe=e7ef06706d) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [fdcdf06f55](https://linux-hardware.org/?probe=fdcdf06f55) | Sep 29, 2022 |
| Dell          | Latitude 3410               | [0f7ad40255](https://linux-hardware.org/?probe=0f7ad40255) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [113f7431d5](https://linux-hardware.org/?probe=113f7431d5) | Sep 28, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [cf8fefa8b5](https://linux-hardware.org/?probe=cf8fefa8b5) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [d0f2ed977a](https://linux-hardware.org/?probe=d0f2ed977a) | Sep 28, 2022 |
| Acer          | Aspire A715-75G             | [9489561c26](https://linux-hardware.org/?probe=9489561c26) | Sep 28, 2022 |
| Gigabyte      | AORUS 15P YD                | [61e297be71](https://linux-hardware.org/?probe=61e297be71) | Sep 28, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [03428c1a17](https://linux-hardware.org/?probe=03428c1a17) | Sep 21, 2022 |
| ASUSTek       | E402BA                      | [e672656164](https://linux-hardware.org/?probe=e672656164) | Sep 10, 2022 |
| Gigabyte      | AERO 15-SA                  | [5ec761c633](https://linux-hardware.org/?probe=5ec761c633) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [a877bbf17d](https://linux-hardware.org/?probe=a877bbf17d) | Sep 09, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| System76      | Oryx Pro                    | [66f701b53f](https://linux-hardware.org/?probe=66f701b53f) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| System76      | Oryx Pro                    | [78adcc218f](https://linux-hardware.org/?probe=78adcc218f) | Sep 04, 2022 |
| System76      | Oryx Pro                    | [0113a2a928](https://linux-hardware.org/?probe=0113a2a928) | Sep 04, 2022 |
| Apple         | MacBookAir7,2               | [73b50385f0](https://linux-hardware.org/?probe=73b50385f0) | Sep 01, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [748558225a](https://linux-hardware.org/?probe=748558225a) | Aug 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [777f18537c](https://linux-hardware.org/?probe=777f18537c) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Shuttle       | DS437                       | [9b866a79d6](https://linux-hardware.org/?probe=9b866a79d6) | Aug 27, 2022 |
| ASUSTek       | N61Jv                       | [a8b586b903](https://linux-hardware.org/?probe=a8b586b903) | Aug 27, 2022 |
| Samsung       | 550XDA                      | [505f5100d0](https://linux-hardware.org/?probe=505f5100d0) | Aug 25, 2022 |
| HP            | ProBook 450 G1              | [986bb07198](https://linux-hardware.org/?probe=986bb07198) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | [c7a1d435fb](https://linux-hardware.org/?probe=c7a1d435fb) | Aug 24, 2022 |
| Chuwi         | GemiBook Pro                | [03ed2d6805](https://linux-hardware.org/?probe=03ed2d6805) | Aug 22, 2022 |
| Unknown       | Unknown                     | [472eb48ecc](https://linux-hardware.org/?probe=472eb48ecc) | Aug 21, 2022 |
| Dell          | Vostro 3400                 | [3b7d550ab9](https://linux-hardware.org/?probe=3b7d550ab9) | Aug 19, 2022 |
| Dell          | Vostro 3400                 | [9b438d4bbf](https://linux-hardware.org/?probe=9b438d4bbf) | Aug 19, 2022 |
| Toshiba       | Satellite P55t-C            | [deac60d261](https://linux-hardware.org/?probe=deac60d261) | Aug 18, 2022 |
| Dell          | Inspiron 5570               | [a6de4113fa](https://linux-hardware.org/?probe=a6de4113fa) | Aug 17, 2022 |
| Dell          | G7 7588                     | [246c96a8ae](https://linux-hardware.org/?probe=246c96a8ae) | Aug 16, 2022 |
| HP            | EliteBook 8540p             | [e2799ec7f9](https://linux-hardware.org/?probe=e2799ec7f9) | Aug 15, 2022 |
| Chuwi         | HeroBook Air                | [dcf4a63c1e](https://linux-hardware.org/?probe=dcf4a63c1e) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| Lenovo        | ThinkPad X240 20AL00BNRT    | [72139648d3](https://linux-hardware.org/?probe=72139648d3) | Aug 10, 2022 |
| Acer          | Aspire E5-575G              | [5ebbabea13](https://linux-hardware.org/?probe=5ebbabea13) | Aug 10, 2022 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | [490109686e](https://linux-hardware.org/?probe=490109686e) | Aug 07, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [cd51b4a39c](https://linux-hardware.org/?probe=cd51b4a39c) | Aug 06, 2022 |
| Xplore        | iX104C5                     | [6ef6194939](https://linux-hardware.org/?probe=6ef6194939) | Aug 06, 2022 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [2f96d2d61a](https://linux-hardware.org/?probe=2f96d2d61a) | Aug 06, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [5ab9ae3992](https://linux-hardware.org/?probe=5ab9ae3992) | Aug 03, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [d3163f70f3](https://linux-hardware.org/?probe=d3163f70f3) | Aug 02, 2022 |
| Sony          | VPCF120FL                   | [75bd2bb218](https://linux-hardware.org/?probe=75bd2bb218) | Aug 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Dell          | Inspiron 5558               | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| Chuwi         | GemiBook Pro                | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c2bcea4cf1](https://linux-hardware.org/?probe=c2bcea4cf1) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| System76      | Oryx Pro                    | [b55d1a9fe5](https://linux-hardware.org/?probe=b55d1a9fe5) | Jul 25, 2022 |
| System76      | Oryx Pro                    | [3b91037c6f](https://linux-hardware.org/?probe=3b91037c6f) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | [437ba53b68](https://linux-hardware.org/?probe=437ba53b68) | Jul 25, 2022 |
| Dell          | Inspiron 14 5401            | [eaf315be72](https://linux-hardware.org/?probe=eaf315be72) | Jul 24, 2022 |
| HP            | Unknown                     | [01622a24ef](https://linux-hardware.org/?probe=01622a24ef) | Jul 17, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [3cc4a578df](https://linux-hardware.org/?probe=3cc4a578df) | Jul 17, 2022 |
| HP            | Notebook                    | [e5a1df8ba8](https://linux-hardware.org/?probe=e5a1df8ba8) | Jul 17, 2022 |
| System76      | Oryx Pro                    | [5cac9c78e6](https://linux-hardware.org/?probe=5cac9c78e6) | Jul 16, 2022 |
| System76      | Oryx Pro                    | [7cb7b3fd6a](https://linux-hardware.org/?probe=7cb7b3fd6a) | Jul 14, 2022 |
| Dell          | XPS 17 9710                 | [2438f42e95](https://linux-hardware.org/?probe=2438f42e95) | Jul 13, 2022 |
| Dell          | Vostro 15 3510              | [b44d77c9a0](https://linux-hardware.org/?probe=b44d77c9a0) | Jul 12, 2022 |
| Dell          | Inspiron N5050              | [8002a8ec0f](https://linux-hardware.org/?probe=8002a8ec0f) | Jul 10, 2022 |
| HP            | Laptop 15-da1xxx            | [ec18f88382](https://linux-hardware.org/?probe=ec18f88382) | Jul 07, 2022 |
| ASUSTek       | S551LN                      | [019c2b1194](https://linux-hardware.org/?probe=019c2b1194) | Jul 07, 2022 |
| ASUSTek       | S551LN                      | [1f47ada680](https://linux-hardware.org/?probe=1f47ada680) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire V5-571G              | [8476e2e1c3](https://linux-hardware.org/?probe=8476e2e1c3) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Acer          | Aspire V5-571G              | [add34d1f6a](https://linux-hardware.org/?probe=add34d1f6a) | Jul 05, 2022 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | [1773a0941f](https://linux-hardware.org/?probe=1773a0941f) | Jul 05, 2022 |
| Acer          | Aspire E5-576G              | [74f6e010da](https://linux-hardware.org/?probe=74f6e010da) | Jul 04, 2022 |
| MSI           | GL65 Leopard 10SEK          | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| System76      | Oryx Pro                    | [7fa7a1ca82](https://linux-hardware.org/?probe=7fa7a1ca82) | Jun 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5ebcb2f152](https://linux-hardware.org/?probe=5ebcb2f152) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Toshiba       | Satellite Pro S300          | [09f9ef25cd](https://linux-hardware.org/?probe=09f9ef25cd) | Jun 27, 2022 |
| HP            | EliteBook 840 G3            | [0d16a3f2ce](https://linux-hardware.org/?probe=0d16a3f2ce) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | [11d7e1ecc7](https://linux-hardware.org/?probe=11d7e1ecc7) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | [6452ae1060](https://linux-hardware.org/?probe=6452ae1060) | Jun 26, 2022 |
| ASUSTek       | All Series                  | [19dde83002](https://linux-hardware.org/?probe=19dde83002) | Jun 26, 2022 |
| Acer          | Aspire E1-572G              | [c2fceb2c81](https://linux-hardware.org/?probe=c2fceb2c81) | Jun 24, 2022 |
| Dell          | Inspiron 5459               | [d3a3e2cf32](https://linux-hardware.org/?probe=d3a3e2cf32) | Jun 22, 2022 |
| Acer          | Aspire ES1-571              | [cfbc040f69](https://linux-hardware.org/?probe=cfbc040f69) | Jun 21, 2022 |
| Lenovo        | ThinkPad T420 4236EF4       | [1894bb8853](https://linux-hardware.org/?probe=1894bb8853) | Jun 21, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1D00... | [eacaed715b](https://linux-hardware.org/?probe=eacaed715b) | Jun 21, 2022 |
| System76      | Oryx Pro                    | [c623d50d29](https://linux-hardware.org/?probe=c623d50d29) | Jun 20, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | [bf292ae80a](https://linux-hardware.org/?probe=bf292ae80a) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [1cf9eae6e5](https://linux-hardware.org/?probe=1cf9eae6e5) | Jun 20, 2022 |
| Lenovo        | B590 20206                  | [f9eddff413](https://linux-hardware.org/?probe=f9eddff413) | Jun 19, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [8845a2219f](https://linux-hardware.org/?probe=8845a2219f) | Jun 17, 2022 |
| Notebook      | PA70ES                      | [7024a9dc03](https://linux-hardware.org/?probe=7024a9dc03) | Jun 16, 2022 |
| HP            | ZBook Studio G3             | [0dda22b68b](https://linux-hardware.org/?probe=0dda22b68b) | Jun 12, 2022 |
| System76      | Oryx Pro                    | [8488dcacf9](https://linux-hardware.org/?probe=8488dcacf9) | Jun 11, 2022 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [5d49ce7763](https://linux-hardware.org/?probe=5d49ce7763) | Jun 10, 2022 |
| Razer         | Blade                       | [2d8524dc81](https://linux-hardware.org/?probe=2d8524dc81) | Jun 10, 2022 |
| HP            | Laptop 14-dk1xxx            | [f895a113f9](https://linux-hardware.org/?probe=f895a113f9) | Jun 09, 2022 |
| HP            | Laptop 14-dk1xxx            | [e29eb57530](https://linux-hardware.org/?probe=e29eb57530) | Jun 09, 2022 |
| Dell          | Latitude 5421               | [24665e8e4b](https://linux-hardware.org/?probe=24665e8e4b) | Jun 08, 2022 |
| HP            | Laptop 15-da1xxx            | [02f5bd70bb](https://linux-hardware.org/?probe=02f5bd70bb) | Jun 07, 2022 |
| ASUSTek       | GL703VD                     | [3a9d836e5e](https://linux-hardware.org/?probe=3a9d836e5e) | Jun 03, 2022 |
| ASUSTek       | GL703VD                     | [531d7297d9](https://linux-hardware.org/?probe=531d7297d9) | Jun 03, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [dca80e1df5](https://linux-hardware.org/?probe=dca80e1df5) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [4b11a98b62](https://linux-hardware.org/?probe=4b11a98b62) | May 31, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| System76      | Oryx Pro                    | [5f84134f5d](https://linux-hardware.org/?probe=5f84134f5d) | May 29, 2022 |
| Toshiba       | Satellite C675              | [72daf96a34](https://linux-hardware.org/?probe=72daf96a34) | May 28, 2022 |
| Unknown       | Unknown                     | [7ca69b6206](https://linux-hardware.org/?probe=7ca69b6206) | May 28, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| System76      | Oryx Pro                    | [2652ac64a4](https://linux-hardware.org/?probe=2652ac64a4) | May 25, 2022 |
| Lenovo        | ThinkPad L540 20AV0031GE    | [13f326fc7d](https://linux-hardware.org/?probe=13f326fc7d) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [7a1059d5cc](https://linux-hardware.org/?probe=7a1059d5cc) | May 25, 2022 |
| Toshiba       | PORTEGE R30-A               | [94cf17bcb6](https://linux-hardware.org/?probe=94cf17bcb6) | May 24, 2022 |
| MSI           | GF75 Thin 9SC               | [49b7f895e9](https://linux-hardware.org/?probe=49b7f895e9) | May 24, 2022 |
| LG Electro... | C500                        | [e59da09f71](https://linux-hardware.org/?probe=e59da09f71) | May 24, 2022 |
| Alienware     | m15 Ryzen Ed. R5            | [f451e1b307](https://linux-hardware.org/?probe=f451e1b307) | May 22, 2022 |
| HP            | Pavilion Notebook           | [f729776db3](https://linux-hardware.org/?probe=f729776db3) | May 21, 2022 |
| Sony          | SVE1712C1EW                 | [9410df7433](https://linux-hardware.org/?probe=9410df7433) | May 20, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [efd1b236a1](https://linux-hardware.org/?probe=efd1b236a1) | May 20, 2022 |
| HP            | Laptop 15-dy2xxx            | [75ec4a948b](https://linux-hardware.org/?probe=75ec4a948b) | May 18, 2022 |
| Lenovo        | ThinkPad T400 276521G       | [9a2f5118c5](https://linux-hardware.org/?probe=9a2f5118c5) | May 15, 2022 |
| HP            | Folio 13                    | [9c9cd2aa91](https://linux-hardware.org/?probe=9c9cd2aa91) | May 15, 2022 |
| System76      | Oryx Pro                    | [d740686b5e](https://linux-hardware.org/?probe=d740686b5e) | May 14, 2022 |
| Lenovo        | ThinkPad X200 7458WAY       | [1d845e69bd](https://linux-hardware.org/?probe=1d845e69bd) | May 11, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [3780dc0fe5](https://linux-hardware.org/?probe=3780dc0fe5) | May 10, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [09d0c5a57c](https://linux-hardware.org/?probe=09d0c5a57c) | May 10, 2022 |
| Samsung       | 550XDA                      | [d3d7a64817](https://linux-hardware.org/?probe=d3d7a64817) | May 08, 2022 |
| HP            | EliteBook 840 G3            | [ac1853274e](https://linux-hardware.org/?probe=ac1853274e) | May 08, 2022 |
| HP            | 250 G5 Notebook PC          | [a21e01fec5](https://linux-hardware.org/?probe=a21e01fec5) | May 07, 2022 |
| HP            | Laptop 17-cn0xxx            | [eab46c9089](https://linux-hardware.org/?probe=eab46c9089) | May 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [ac2c2a5969](https://linux-hardware.org/?probe=ac2c2a5969) | May 06, 2022 |
| Lenovo        | ThinkPad X220 4290LD4       | [0a28279824](https://linux-hardware.org/?probe=0a28279824) | May 05, 2022 |
| ASUSTek       | G752VT                      | [b007cf4ed2](https://linux-hardware.org/?probe=b007cf4ed2) | May 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [744b50ab3b](https://linux-hardware.org/?probe=744b50ab3b) | May 03, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [3835b6bdb8](https://linux-hardware.org/?probe=3835b6bdb8) | May 03, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [90aa5187ab](https://linux-hardware.org/?probe=90aa5187ab) | May 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c628f1d84](https://linux-hardware.org/?probe=5c628f1d84) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [3589ada8b3](https://linux-hardware.org/?probe=3589ada8b3) | Apr 30, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| Dell          | Latitude 3380               | [2aa3eacaee](https://linux-hardware.org/?probe=2aa3eacaee) | Apr 24, 2022 |
| HP            | Pavilion g7                 | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [0579e465d1](https://linux-hardware.org/?probe=0579e465d1) | Apr 19, 2022 |
| HP            | Pavilion g7                 | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| ASUSTek       | G752VSK                     | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| HP            | EliteBook 820 G3            | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| Dell          | Latitude E7250              | [532fb04297](https://linux-hardware.org/?probe=532fb04297) | Apr 15, 2022 |
| HP            | ProBook 4430s               | [79e30d321b](https://linux-hardware.org/?probe=79e30d321b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [afe37cb756](https://linux-hardware.org/?probe=afe37cb756) | Apr 14, 2022 |
| Dell          | Latitude E7250              | [a1e63550ab](https://linux-hardware.org/?probe=a1e63550ab) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291IU6       | [a4c2a2bff9](https://linux-hardware.org/?probe=a4c2a2bff9) | Apr 14, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b5375b9ffb](https://linux-hardware.org/?probe=b5375b9ffb) | Apr 13, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [85062520f7](https://linux-hardware.org/?probe=85062520f7) | Apr 13, 2022 |
| HP            | Laptop 15s-eq2xxx           | [542c9c6703](https://linux-hardware.org/?probe=542c9c6703) | Apr 11, 2022 |
| HP            | Laptop 15s-gr0xxx           | [36e02535fb](https://linux-hardware.org/?probe=36e02535fb) | Apr 11, 2022 |
| Dell          | Latitude E6230              | [67750bdf0f](https://linux-hardware.org/?probe=67750bdf0f) | Apr 10, 2022 |
| Dell          | Latitude E6230              | [db52ca23d3](https://linux-hardware.org/?probe=db52ca23d3) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| Dell          | Latitude E6430              | [c974a805b2](https://linux-hardware.org/?probe=c974a805b2) | Apr 05, 2022 |
| Apple         | MacBookPro11,1              | [f41079b495](https://linux-hardware.org/?probe=f41079b495) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| Notebook      | P65_P67RGRERA               | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Lenovo        | ThinkPad T410 2522AC1       | [b22a799f67](https://linux-hardware.org/?probe=b22a799f67) | Apr 04, 2022 |
| Sony          | SVE1712C1EW                 | [989843d8cf](https://linux-hardware.org/?probe=989843d8cf) | Apr 04, 2022 |
| Dell          | Latitude 5421               | [78ac6f00cd](https://linux-hardware.org/?probe=78ac6f00cd) | Apr 04, 2022 |
| Lenovo        | ThinkPad T480s 20L7001SG... | [440bfc13d9](https://linux-hardware.org/?probe=440bfc13d9) | Apr 03, 2022 |
| Sony          | SVE1712C1EW                 | [5e530d1a32](https://linux-hardware.org/?probe=5e530d1a32) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [35057588b4](https://linux-hardware.org/?probe=35057588b4) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [9050980874](https://linux-hardware.org/?probe=9050980874) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8e7fc0aef9](https://linux-hardware.org/?probe=8e7fc0aef9) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | [9a18c2ac1c](https://linux-hardware.org/?probe=9a18c2ac1c) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ceae86aef1](https://linux-hardware.org/?probe=ceae86aef1) | Mar 30, 2022 |
| Lenovo        | B550 20053                  | [e3c65a5e44](https://linux-hardware.org/?probe=e3c65a5e44) | Mar 30, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [339d70da8c](https://linux-hardware.org/?probe=339d70da8c) | Mar 30, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [799c1dfce8](https://linux-hardware.org/?probe=799c1dfce8) | Mar 26, 2022 |
| HP            | Laptop 15-dw0xxx            | [a2bd44d0a4](https://linux-hardware.org/?probe=a2bd44d0a4) | Mar 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [98b597334b](https://linux-hardware.org/?probe=98b597334b) | Mar 25, 2022 |
| System76      | Oryx Pro                    | [b128755fa4](https://linux-hardware.org/?probe=b128755fa4) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [40f5402f5a](https://linux-hardware.org/?probe=40f5402f5a) | Mar 21, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [92c8ac9161](https://linux-hardware.org/?probe=92c8ac9161) | Mar 21, 2022 |
| ASUSTek       | N550JK                      | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Dell          | Inspiron 7520               | [3617d07720](https://linux-hardware.org/?probe=3617d07720) | Mar 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| Lenovo        | ThinkPad T460s 20F9S02U0... | [f255ab814c](https://linux-hardware.org/?probe=f255ab814c) | Mar 17, 2022 |
| MSI           | GS66 Stealth 10SE           | [fb8d2216a5](https://linux-hardware.org/?probe=fb8d2216a5) | Mar 17, 2022 |
| Dell          | XPS 13 7390                 | [d0a87aedef](https://linux-hardware.org/?probe=d0a87aedef) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | [51409532cc](https://linux-hardware.org/?probe=51409532cc) | Mar 15, 2022 |
| Acer          | Aspire A515-52G             | [13775d028d](https://linux-hardware.org/?probe=13775d028d) | Mar 15, 2022 |
| Dell          | Precision 7540              | [9d4662756c](https://linux-hardware.org/?probe=9d4662756c) | Mar 15, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [cb2918a35e](https://linux-hardware.org/?probe=cb2918a35e) | Mar 12, 2022 |
| Dell          | Latitude E7240              | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [a83a1ffe1a](https://linux-hardware.org/?probe=a83a1ffe1a) | Mar 09, 2022 |
| System76      | Oryx Pro                    | [d36e30fa5b](https://linux-hardware.org/?probe=d36e30fa5b) | Mar 08, 2022 |
| Sony          | VPCEH25FM                   | [5a60a14cf4](https://linux-hardware.org/?probe=5a60a14cf4) | Mar 07, 2022 |
| Dell          | Precision M4800             | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [ee905a56c9](https://linux-hardware.org/?probe=ee905a56c9) | Mar 02, 2022 |
| Apple         | MacBookPro11,2              | [eb57cef46a](https://linux-hardware.org/?probe=eb57cef46a) | Feb 28, 2022 |
| Dell          | Latitude E5400              | [ab5ce36275](https://linux-hardware.org/?probe=ab5ce36275) | Feb 27, 2022 |
| Dell          | XPS 15 9570                 | [b531665e82](https://linux-hardware.org/?probe=b531665e82) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [36e7b3c4aa](https://linux-hardware.org/?probe=36e7b3c4aa) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a9bcae50d2](https://linux-hardware.org/?probe=a9bcae50d2) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [270aaf59b6](https://linux-hardware.org/?probe=270aaf59b6) | Feb 25, 2022 |
| Lenovo        | ThinkPad S430 68852BU       | [7d7bb498fe](https://linux-hardware.org/?probe=7d7bb498fe) | Feb 25, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [6423622186](https://linux-hardware.org/?probe=6423622186) | Feb 23, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [9a32d51389](https://linux-hardware.org/?probe=9a32d51389) | Feb 22, 2022 |
| Dell          | Latitude E7240              | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e24c41d802](https://linux-hardware.org/?probe=e24c41d802) | Feb 21, 2022 |
| HP            | ZBook 15 G5                 | [1947127ef5](https://linux-hardware.org/?probe=1947127ef5) | Feb 21, 2022 |
| Dell          | Inspiron 5567               | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [fb981fe5b0](https://linux-hardware.org/?probe=fb981fe5b0) | Feb 20, 2022 |
| Dell          | Inspiron 15-3567            | [0fd79af602](https://linux-hardware.org/?probe=0fd79af602) | Feb 19, 2022 |
| ASUSTek       | K54L                        | [5850a8dd22](https://linux-hardware.org/?probe=5850a8dd22) | Feb 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [3beffcfd3e](https://linux-hardware.org/?probe=3beffcfd3e) | Feb 19, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | [88c3891424](https://linux-hardware.org/?probe=88c3891424) | Feb 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [35ac77d812](https://linux-hardware.org/?probe=35ac77d812) | Feb 17, 2022 |
| ASUSTek       | K53E                        | [929e5d8462](https://linux-hardware.org/?probe=929e5d8462) | Feb 15, 2022 |
| HUAWEI        | KLVL-WXX9                   | [34bd2af067](https://linux-hardware.org/?probe=34bd2af067) | Feb 14, 2022 |
| Lenovo        | ThinkPad R61/R61i 8934A7... | [e60d5e52f2](https://linux-hardware.org/?probe=e60d5e52f2) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [ed2717ae86](https://linux-hardware.org/?probe=ed2717ae86) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | 255 G7 Notebook PC          | [cb0abbfe2d](https://linux-hardware.org/?probe=cb0abbfe2d) | Feb 10, 2022 |
| Lenovo        | V15-IIL 82C5                | [c50b098929](https://linux-hardware.org/?probe=c50b098929) | Feb 10, 2022 |
| Dell          | XPS 15 9570                 | [dbfb51d331](https://linux-hardware.org/?probe=dbfb51d331) | Feb 10, 2022 |
| Lenovo        | ThinkPad W510 4389BB4       | [ecaa14289f](https://linux-hardware.org/?probe=ecaa14289f) | Feb 09, 2022 |
| Compal        | PBL21                       | [7a0b26892e](https://linux-hardware.org/?probe=7a0b26892e) | Feb 09, 2022 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [e6bc24c5b9](https://linux-hardware.org/?probe=e6bc24c5b9) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| HP            | 255 G7 Notebook PC          | [587efdf773](https://linux-hardware.org/?probe=587efdf773) | Feb 06, 2022 |
| Acer          | Aspire A515-41G             | [0785fcc2af](https://linux-hardware.org/?probe=0785fcc2af) | Feb 06, 2022 |
| Fujitsu       | LIFEBOOK E756               | [92c26ed8dc](https://linux-hardware.org/?probe=92c26ed8dc) | Feb 06, 2022 |
| HP            | 255 G7 Notebook PC          | [b8aa657ab7](https://linux-hardware.org/?probe=b8aa657ab7) | Feb 05, 2022 |
| Dell          | Precision 5550              | [2853896d4c](https://linux-hardware.org/?probe=2853896d4c) | Feb 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| Notebook      | PA70ES                      | [794ffc9a83](https://linux-hardware.org/?probe=794ffc9a83) | Feb 02, 2022 |
| ASUSTek       | X750LN                      | [94a70cdd5d](https://linux-hardware.org/?probe=94a70cdd5d) | Feb 02, 2022 |
| Dell          | Latitude E5430 non-vPro     | [1c3c43b4ce](https://linux-hardware.org/?probe=1c3c43b4ce) | Feb 02, 2022 |
| Acer          | Aspire V3-771               | [f755eb7a78](https://linux-hardware.org/?probe=f755eb7a78) | Feb 01, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [88085159bf](https://linux-hardware.org/?probe=88085159bf) | Jan 31, 2022 |
| Casper        | EXCALIBUR G860              | [e6f107eb25](https://linux-hardware.org/?probe=e6f107eb25) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | [d2ebf4698b](https://linux-hardware.org/?probe=d2ebf4698b) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [9a1fb4d53e](https://linux-hardware.org/?probe=9a1fb4d53e) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Dell          | XPS 15 9500                 | [1db87d66c6](https://linux-hardware.org/?probe=1db87d66c6) | Jan 28, 2022 |
| Dell          | Latitude E6510              | [efc619cc61](https://linux-hardware.org/?probe=efc619cc61) | Jan 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [75082acc94](https://linux-hardware.org/?probe=75082acc94) | Jan 27, 2022 |
| Lenovo        | ThinkPad L460 20FVS0QQ00    | [470cd66ae6](https://linux-hardware.org/?probe=470cd66ae6) | Jan 27, 2022 |
| Dell          | XPS 17 9710                 | [d8e76e70e8](https://linux-hardware.org/?probe=d8e76e70e8) | Jan 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [a4172550fa](https://linux-hardware.org/?probe=a4172550fa) | Jan 26, 2022 |
| Casper        | EXCALIBUR G860              | [76a2a4e935](https://linux-hardware.org/?probe=76a2a4e935) | Jan 24, 2022 |
| HP            | ProBook 450 G1              | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | [22757e0dd9](https://linux-hardware.org/?probe=22757e0dd9) | Jan 23, 2022 |
| ASUSTek       | X580VD                      | [299f1c8cca](https://linux-hardware.org/?probe=299f1c8cca) | Jan 23, 2022 |
| Toshiba       | Satellite L640              | [280b5d9630](https://linux-hardware.org/?probe=280b5d9630) | Jan 22, 2022 |
| Standard      | MB50II                      | [aa719e1665](https://linux-hardware.org/?probe=aa719e1665) | Jan 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ae399035f5](https://linux-hardware.org/?probe=ae399035f5) | Jan 21, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4d77516c19](https://linux-hardware.org/?probe=4d77516c19) | Jan 19, 2022 |
| Lenovo        | IdeaPad Y580                | [2a4100e03c](https://linux-hardware.org/?probe=2a4100e03c) | Jan 18, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [0287de904c](https://linux-hardware.org/?probe=0287de904c) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0fddd05eae](https://linux-hardware.org/?probe=0fddd05eae) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6f87d7372b](https://linux-hardware.org/?probe=6f87d7372b) | Jan 18, 2022 |
| Dell          | Latitude 7480               | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| ASUSTek       | 1001PX                      | [5343777492](https://linux-hardware.org/?probe=5343777492) | Jan 16, 2022 |
| HP            | 250 G7 Notebook PC          | [6da1d84e76](https://linux-hardware.org/?probe=6da1d84e76) | Jan 16, 2022 |
| HP            | ProBook 450 G2              | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | [968c8c3b82](https://linux-hardware.org/?probe=968c8c3b82) | Jan 11, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [148b934acf](https://linux-hardware.org/?probe=148b934acf) | Jan 09, 2022 |
| Lenovo        | ThinkPad T560 20FH001TUS    | [f8400f7913](https://linux-hardware.org/?probe=f8400f7913) | Jan 09, 2022 |
| Acer          | Aspire A315-21              | [2f505d02d9](https://linux-hardware.org/?probe=2f505d02d9) | Jan 09, 2022 |
| Dell          | Latitude E5430 non-vPro     | [37d39e8efe](https://linux-hardware.org/?probe=37d39e8efe) | Jan 09, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [ad8e8b92cb](https://linux-hardware.org/?probe=ad8e8b92cb) | Jan 08, 2022 |
| Dell          | XPS 13 7390                 | [4026f1e18c](https://linux-hardware.org/?probe=4026f1e18c) | Jan 08, 2022 |
| Acer          | Extensa 5620                | [a10369e225](https://linux-hardware.org/?probe=a10369e225) | Jan 08, 2022 |
| Sony          | VPCEB2B4E                   | [4d3b6ede0c](https://linux-hardware.org/?probe=4d3b6ede0c) | Jan 08, 2022 |
| Lenovo        | ThinkPad T420 4180AJ3       | [d744cfb251](https://linux-hardware.org/?probe=d744cfb251) | Jan 06, 2022 |
| Monster       | ABRA A5 V11.1               | [0cc6ec8af7](https://linux-hardware.org/?probe=0cc6ec8af7) | Jan 03, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [14ca887c8f](https://linux-hardware.org/?probe=14ca887c8f) | Jan 02, 2022 |
| Dell          | XPS 17 9710                 | [23110f625c](https://linux-hardware.org/?probe=23110f625c) | Dec 31, 2021 |
| Lenovo        | ThinkPad T410 2522AC1       | [0cf80c2ee3](https://linux-hardware.org/?probe=0cf80c2ee3) | Dec 31, 2021 |
| Acer          | Aspire E5-575G              | [f6d8856ace](https://linux-hardware.org/?probe=f6d8856ace) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | [17548c6fc7](https://linux-hardware.org/?probe=17548c6fc7) | Dec 30, 2021 |
| Lenovo        | ThinkPad T460 20FMS80M0C    | [dfdcb1f759](https://linux-hardware.org/?probe=dfdcb1f759) | Dec 29, 2021 |
| Acer          | Nitro AN715-51              | [c3caffed3c](https://linux-hardware.org/?probe=c3caffed3c) | Dec 29, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [4a1c70f95f](https://linux-hardware.org/?probe=4a1c70f95f) | Dec 28, 2021 |
| Dell          | Latitude E4310              | [8b6976bdd2](https://linux-hardware.org/?probe=8b6976bdd2) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Acer          | Aspire 4736                 | [128ea022f0](https://linux-hardware.org/?probe=128ea022f0) | Dec 26, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| Apple         | MacBookPro8,1               | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire A715-75G             | [65a1aa570a](https://linux-hardware.org/?probe=65a1aa570a) | Dec 25, 2021 |
| Lenovo        | G40-45 80E1                 | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Monster       | ABRA A5 V11.1               | [00b9630631](https://linux-hardware.org/?probe=00b9630631) | Dec 24, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| Dell          | Latitude E4310              | [e5b46c1542](https://linux-hardware.org/?probe=e5b46c1542) | Dec 24, 2021 |
| ASUSTek       | X450LD                      | [b5e36a24f9](https://linux-hardware.org/?probe=b5e36a24f9) | Dec 24, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [0c879745b1](https://linux-hardware.org/?probe=0c879745b1) | Dec 24, 2021 |
| Timi          | TM1701                      | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| Dell          | XPS 15 9510                 | [9bd5592765](https://linux-hardware.org/?probe=9bd5592765) | Dec 23, 2021 |
| Medion        | E4213 MD99329               | [8801cfdb2a](https://linux-hardware.org/?probe=8801cfdb2a) | Dec 23, 2021 |
| Teclast       | F15S                        | [8be33fb7e2](https://linux-hardware.org/?probe=8be33fb7e2) | Dec 23, 2021 |
| MSI           | GE72 6QC                    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| Dell          | Latitude 3410               | [a0b79031ae](https://linux-hardware.org/?probe=a0b79031ae) | Dec 23, 2021 |
| ASUSTek       | E502NA                      | [66ade120a5](https://linux-hardware.org/?probe=66ade120a5) | Dec 23, 2021 |
| HP            | Laptop 15s-eq2xxx           | [d4fcc94659](https://linux-hardware.org/?probe=d4fcc94659) | Dec 22, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [fabd656de1](https://linux-hardware.org/?probe=fabd656de1) | Dec 21, 2021 |
| Acer          | Aspire A715-75G             | [c349552561](https://linux-hardware.org/?probe=c349552561) | Dec 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| Apple         | MacBookPro8,1               | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | [9da235adb3](https://linux-hardware.org/?probe=9da235adb3) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | [037f47a340](https://linux-hardware.org/?probe=037f47a340) | Dec 19, 2021 |
| Acer          | Aspire F5-573G              | [55e4486324](https://linux-hardware.org/?probe=55e4486324) | Dec 18, 2021 |
| Lenovo        | ThinkPad T430 2349DG5       | [9bd0a6e07d](https://linux-hardware.org/?probe=9bd0a6e07d) | Dec 18, 2021 |
| MSI           | GE72 6QC                    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| Acer          | Aspire 5741G                | [702be0b615](https://linux-hardware.org/?probe=702be0b615) | Dec 17, 2021 |
| Acer          | Aspire 5741G                | [60d68b4c13](https://linux-hardware.org/?probe=60d68b4c13) | Dec 17, 2021 |
| Dell          | Inspiron 3505               | [14ffa86838](https://linux-hardware.org/?probe=14ffa86838) | Dec 17, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [8218845f08](https://linux-hardware.org/?probe=8218845f08) | Dec 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [4c02cd3e26](https://linux-hardware.org/?probe=4c02cd3e26) | Dec 15, 2021 |
| Apple         | MacBookPro11,2              | [9cb226408e](https://linux-hardware.org/?probe=9cb226408e) | Dec 15, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| Lenovo        | ThinkPad T540p 20BFS31F0... | [b7b09dcc5e](https://linux-hardware.org/?probe=b7b09dcc5e) | Dec 15, 2021 |
| Lenovo        | ThinkPad W540 20BG0011US    | [ead3a18508](https://linux-hardware.org/?probe=ead3a18508) | Dec 15, 2021 |
| Dell          | Precision M4800             | [90109636fe](https://linux-hardware.org/?probe=90109636fe) | Dec 15, 2021 |
| Dell          | Precision M4800             | [0d1cfc9a0e](https://linux-hardware.org/?probe=0d1cfc9a0e) | Dec 15, 2021 |
| Notebook      | NH5xAx                      | [62f88112f1](https://linux-hardware.org/?probe=62f88112f1) | Dec 14, 2021 |
| Alienware     | 15 R3                       | [6394aa965a](https://linux-hardware.org/?probe=6394aa965a) | Dec 14, 2021 |
| Acer          | Aspire E5-532G              | [8cbbaee4ad](https://linux-hardware.org/?probe=8cbbaee4ad) | Dec 14, 2021 |
| Lenovo        | ThinkPad T410 2522E38       | [5faef7686a](https://linux-hardware.org/?probe=5faef7686a) | Dec 14, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [ba92d0772e](https://linux-hardware.org/?probe=ba92d0772e) | Dec 14, 2021 |
| HP            | Laptop 15-da0xxx            | [2b3ad3643a](https://linux-hardware.org/?probe=2b3ad3643a) | Dec 14, 2021 |
| Acer          | Extensa 5635ZG              | [d232d67b9e](https://linux-hardware.org/?probe=d232d67b9e) | Dec 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [91eeb42bcb](https://linux-hardware.org/?probe=91eeb42bcb) | Dec 13, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| Dell          | Precision 5550              | [9e88f6034f](https://linux-hardware.org/?probe=9e88f6034f) | Dec 12, 2021 |
| System76      | Galago Pro                  | [9fe1e9175f](https://linux-hardware.org/?probe=9fe1e9175f) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [6343dc8a43](https://linux-hardware.org/?probe=6343dc8a43) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [5cd58ae5d9](https://linux-hardware.org/?probe=5cd58ae5d9) | Dec 12, 2021 |
| Apple         | MacBookPro11,5              | [e59e1a3c29](https://linux-hardware.org/?probe=e59e1a3c29) | Dec 12, 2021 |
| Lenovo        | ThinkPad X201 3680KC5       | [64958365b3](https://linux-hardware.org/?probe=64958365b3) | Dec 12, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [da7c19f0b4](https://linux-hardware.org/?probe=da7c19f0b4) | Dec 12, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [85770fb8f5](https://linux-hardware.org/?probe=85770fb8f5) | Dec 12, 2021 |
| System76      | Darter Pro                  | [2e84db8ffb](https://linux-hardware.org/?probe=2e84db8ffb) | Dec 12, 2021 |
| Dell          | Inspiron 5570               | [1bed203660](https://linux-hardware.org/?probe=1bed203660) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| Acer          | Aspire A515-51G             | [dfa992fc24](https://linux-hardware.org/?probe=dfa992fc24) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [15e97e023d](https://linux-hardware.org/?probe=15e97e023d) | Dec 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [c5f999eb1e](https://linux-hardware.org/?probe=c5f999eb1e) | Dec 11, 2021 |
| Acer          | Swift SF314-41              | [4e9e6b5c99](https://linux-hardware.org/?probe=4e9e6b5c99) | Dec 11, 2021 |
| Apple         | MacBookPro11,2              | [debd9b86e1](https://linux-hardware.org/?probe=debd9b86e1) | Dec 11, 2021 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [9a01f01187](https://linux-hardware.org/?probe=9a01f01187) | Dec 09, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [8fe2d382de](https://linux-hardware.org/?probe=8fe2d382de) | Dec 08, 2021 |
| Dell          | Inspiron 5468               | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | [cf8576527d](https://linux-hardware.org/?probe=cf8576527d) | Dec 07, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [ee8b533768](https://linux-hardware.org/?probe=ee8b533768) | Dec 07, 2021 |
| HP            | ENVY Notebook               | [179bd0eae8](https://linux-hardware.org/?probe=179bd0eae8) | Dec 05, 2021 |
| HP            | ENVY Notebook               | [58488b0351](https://linux-hardware.org/?probe=58488b0351) | Dec 05, 2021 |
| Razer         | Blade Stealth               | [03738c7e11](https://linux-hardware.org/?probe=03738c7e11) | Dec 04, 2021 |
| Acer          | Aspire A315-21              | [322f9afcb0](https://linux-hardware.org/?probe=322f9afcb0) | Dec 04, 2021 |
| ASUSTek       | K501UX                      | [3f9b547c57](https://linux-hardware.org/?probe=3f9b547c57) | Dec 04, 2021 |
| HP            | Notebook                    | [9f7082bedb](https://linux-hardware.org/?probe=9f7082bedb) | Dec 03, 2021 |
| Lenovo        | V14-ADA 82C6                | [7fd0e9e7cd](https://linux-hardware.org/?probe=7fd0e9e7cd) | Dec 03, 2021 |
| ASUSTek       | K72Jr                       | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| Dell          | Inspiron 15-3552            | [7fbb6be9e3](https://linux-hardware.org/?probe=7fbb6be9e3) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| HP            | Pavilion g7                 | [da6e298046](https://linux-hardware.org/?probe=da6e298046) | Nov 29, 2021 |
| MSI           | Modern 14 B4MW              | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| Apple         | MacBookPro11,2              | [681845a2e3](https://linux-hardware.org/?probe=681845a2e3) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | [b022b376ee](https://linux-hardware.org/?probe=b022b376ee) | Nov 28, 2021 |
| Dell          | Inspiron 3505               | [d3cfe93dc6](https://linux-hardware.org/?probe=d3cfe93dc6) | Nov 28, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| HP            | Laptop 15s-eq2xxx           | [3d1d036e1e](https://linux-hardware.org/?probe=3d1d036e1e) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | V14-ADA 82C6                | [a0f72af8d9](https://linux-hardware.org/?probe=a0f72af8d9) | Nov 26, 2021 |
| ASUSTek       | X556UQK                     | [38ca30691b](https://linux-hardware.org/?probe=38ca30691b) | Nov 26, 2021 |
| HP            | Laptop 15-bw0xx             | [071447b964](https://linux-hardware.org/?probe=071447b964) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| Apple         | MacBookPro10,1              | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [485f0b0858](https://linux-hardware.org/?probe=485f0b0858) | Nov 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | [0110ddef8c](https://linux-hardware.org/?probe=0110ddef8c) | Nov 24, 2021 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [e215995139](https://linux-hardware.org/?probe=e215995139) | Nov 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| HP            | Laptop 14q-cs0xxx           | [c8edde8f8d](https://linux-hardware.org/?probe=c8edde8f8d) | Nov 23, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [81d28ee0b3](https://linux-hardware.org/?probe=81d28ee0b3) | Nov 23, 2021 |
| Dell          | Latitude E5450              | [a1c9396c75](https://linux-hardware.org/?probe=a1c9396c75) | Nov 23, 2021 |
| HP            | EliteBook 840 G1            | [8338e70267](https://linux-hardware.org/?probe=8338e70267) | Nov 22, 2021 |
| Notebook      | NV4XMB,ME,MZ                | [edaff183a5](https://linux-hardware.org/?probe=edaff183a5) | Nov 21, 2021 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [dcc60be203](https://linux-hardware.org/?probe=dcc60be203) | Nov 20, 2021 |
| HUAWEI        | WRT-WX9                     | [b94e6da627](https://linux-hardware.org/?probe=b94e6da627) | Nov 18, 2021 |
| Dell          | Precision 5550              | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Dell          | Inspiron 3558               | [b0f06cc210](https://linux-hardware.org/?probe=b0f06cc210) | Nov 18, 2021 |
| Dell          | Inspiron 3581               | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| Dell          | Inspiron 5579               | [0f7bccdef0](https://linux-hardware.org/?probe=0f7bccdef0) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [ab746b7399](https://linux-hardware.org/?probe=ab746b7399) | Nov 12, 2021 |
| Apple         | MacBook5,1                  | [6ddb5fdd76](https://linux-hardware.org/?probe=6ddb5fdd76) | Nov 12, 2021 |
| HUAWEI        | KPL-W0X                     | [bffba05735](https://linux-hardware.org/?probe=bffba05735) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [258e2f1594](https://linux-hardware.org/?probe=258e2f1594) | Nov 08, 2021 |
| HUAWEI        | KPL-W0X                     | [4a189c2903](https://linux-hardware.org/?probe=4a189c2903) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| Dell          | Inspiron 5721               | [d9146c3909](https://linux-hardware.org/?probe=d9146c3909) | Nov 07, 2021 |
| Dell          | Latitude E6440              | [38e3c1e18a](https://linux-hardware.org/?probe=38e3c1e18a) | Nov 06, 2021 |
| Dell          | Precision 7510              | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| HP            | 630                         | [f01c95d959](https://linux-hardware.org/?probe=f01c95d959) | Nov 03, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | [000c804ed5](https://linux-hardware.org/?probe=000c804ed5) | Nov 03, 2021 |
| Lenovo        | ThinkPad T470 20HES01100    | [d3c8a48b29](https://linux-hardware.org/?probe=d3c8a48b29) | Nov 03, 2021 |
| Acer          | Aspire ES1-311              | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| Acer          | Nitro AN515-44              | [f581cf8319](https://linux-hardware.org/?probe=f581cf8319) | Nov 01, 2021 |
| Apple         | MacBookPro8,1               | [6e17fb6ea4](https://linux-hardware.org/?probe=6e17fb6ea4) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | [1069b24865](https://linux-hardware.org/?probe=1069b24865) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | [9e32a01dc0](https://linux-hardware.org/?probe=9e32a01dc0) | Oct 31, 2021 |
| Dell          | XPS 13 9343                 | [0d89b6423c](https://linux-hardware.org/?probe=0d89b6423c) | Oct 31, 2021 |
| Razer         | Blade                       | [744799a3c4](https://linux-hardware.org/?probe=744799a3c4) | Oct 28, 2021 |
| Dell          | Latitude E6540              | [298ab39418](https://linux-hardware.org/?probe=298ab39418) | Oct 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2eac1bfc4f](https://linux-hardware.org/?probe=2eac1bfc4f) | Oct 24, 2021 |
| Lenovo        | G50-30 80G0                 | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Acer          | Nitro AN515-54              | [fe7a37dce1](https://linux-hardware.org/?probe=fe7a37dce1) | Oct 22, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [456b686d28](https://linux-hardware.org/?probe=456b686d28) | Oct 20, 2021 |
| ASUSTek       | X580VD                      | [aff8edafa4](https://linux-hardware.org/?probe=aff8edafa4) | Oct 20, 2021 |
| ASUSTek       | X555LD                      | [eef17ea12f](https://linux-hardware.org/?probe=eef17ea12f) | Oct 20, 2021 |
| Acer          | Aspire E5-523               | [fb8d7a6a25](https://linux-hardware.org/?probe=fb8d7a6a25) | Oct 18, 2021 |
| Dell          | Latitude E7440              | [98c988645f](https://linux-hardware.org/?probe=98c988645f) | Oct 18, 2021 |
| Acer          | Aspire SW5-173              | [38872d1422](https://linux-hardware.org/?probe=38872d1422) | Oct 17, 2021 |
| HUAWEI        | WRT-WX9                     | [d9cd722532](https://linux-hardware.org/?probe=d9cd722532) | Oct 17, 2021 |
| ASUSTek       | N53Jq                       | [3cd3bb5eae](https://linux-hardware.org/?probe=3cd3bb5eae) | Oct 16, 2021 |
| Dell          | Inspiron 3520               | [56fe4ab8a1](https://linux-hardware.org/?probe=56fe4ab8a1) | Oct 16, 2021 |
| Acer          | Nitro AN515-55              | [9bf062da25](https://linux-hardware.org/?probe=9bf062da25) | Oct 16, 2021 |
| Dell          | Precision M4800             | [87034ed159](https://linux-hardware.org/?probe=87034ed159) | Oct 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8fbafb0d7e](https://linux-hardware.org/?probe=8fbafb0d7e) | Oct 16, 2021 |
| System76      | Pangolin                    | [e4fb2b6b8a](https://linux-hardware.org/?probe=e4fb2b6b8a) | Oct 16, 2021 |
| UNITCOM       | W55xEU                      | [ced300109d](https://linux-hardware.org/?probe=ced300109d) | Oct 15, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [e16a7eaba9](https://linux-hardware.org/?probe=e16a7eaba9) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [eed2a8b965](https://linux-hardware.org/?probe=eed2a8b965) | Oct 15, 2021 |
| Lenovo        | G50-30 80G0                 | [3d5411b3f0](https://linux-hardware.org/?probe=3d5411b3f0) | Oct 13, 2021 |
| Dell          | Precision 7510              | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [6bd6fd9002](https://linux-hardware.org/?probe=6bd6fd9002) | Oct 12, 2021 |
| HP            | EliteBook 840 G3            | [b3f6912fdd](https://linux-hardware.org/?probe=b3f6912fdd) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0011AU     | [85c8487ca5](https://linux-hardware.org/?probe=85c8487ca5) | Oct 11, 2021 |
| Samsung       | 550P5C/550P7C               | [3c7018cbdf](https://linux-hardware.org/?probe=3c7018cbdf) | Oct 10, 2021 |
| Razer         | Blade Stealth               | [82e8aefe39](https://linux-hardware.org/?probe=82e8aefe39) | Oct 09, 2021 |
| TUXEDO        | Unknown                     | [59193a23d9](https://linux-hardware.org/?probe=59193a23d9) | Oct 08, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [168f21cc93](https://linux-hardware.org/?probe=168f21cc93) | Oct 08, 2021 |
| MSI           | GS66 Stealth 10SFS          | [2ff9b97589](https://linux-hardware.org/?probe=2ff9b97589) | Oct 06, 2021 |
| Alienware     | 17                          | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Dell          | Latitude 5410               | [6928f4237f](https://linux-hardware.org/?probe=6928f4237f) | Oct 01, 2021 |
| HP            | Pavilion dv6                | [ee806bc406](https://linux-hardware.org/?probe=ee806bc406) | Sep 30, 2021 |
| HP            | Pavilion dv6                | [252520800c](https://linux-hardware.org/?probe=252520800c) | Sep 30, 2021 |
| Chuwi         | GemiBook Pro                | [4ee2cf61ef](https://linux-hardware.org/?probe=4ee2cf61ef) | Sep 29, 2021 |
| Monster       | ABRA A5 V11.1               | [34b6bc562c](https://linux-hardware.org/?probe=34b6bc562c) | Sep 29, 2021 |
| Apple         | MacBookAir7,1               | [4642e930ca](https://linux-hardware.org/?probe=4642e930ca) | Sep 28, 2021 |
| Monster       | ABRA A5 V11.1               | [b70d12e2f5](https://linux-hardware.org/?probe=b70d12e2f5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [9cd2ba74a0](https://linux-hardware.org/?probe=9cd2ba74a0) | Sep 27, 2021 |
| Timi          | TM1607                      | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| Lenovo        | ThinkPad T450s 20BWS07N0... | [cb83c57f1c](https://linux-hardware.org/?probe=cb83c57f1c) | Sep 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S0230... | [04b5e431fe](https://linux-hardware.org/?probe=04b5e431fe) | Sep 24, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [de3b970f84](https://linux-hardware.org/?probe=de3b970f84) | Sep 23, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [7d9277109c](https://linux-hardware.org/?probe=7d9277109c) | Sep 23, 2021 |
| Toshiba       | IS 1442                     | [26b3724f40](https://linux-hardware.org/?probe=26b3724f40) | Sep 22, 2021 |
| Samsung       | QX311/QX411/QX412/QX511     | [9c968d26f7](https://linux-hardware.org/?probe=9c968d26f7) | Sep 21, 2021 |
| ASUSTek       | UX550VE                     | [72925fef5d](https://linux-hardware.org/?probe=72925fef5d) | Sep 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | [2aab2f6ffb](https://linux-hardware.org/?probe=2aab2f6ffb) | Sep 21, 2021 |
| Chuwi         | GemiBook Pro                | [17c3ec978f](https://linux-hardware.org/?probe=17c3ec978f) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| HP            | 250 G6 Notebook PC          | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| MSI           | GF63 Thin 10SCSR            | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| Dell          | Inspiron 1545               | [45b03d16ce](https://linux-hardware.org/?probe=45b03d16ce) | Sep 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [caa2e90160](https://linux-hardware.org/?probe=caa2e90160) | Sep 18, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [67449a33dc](https://linux-hardware.org/?probe=67449a33dc) | Sep 18, 2021 |
| ASUSTek       | UX303LN                     | [9c8bb62a98](https://linux-hardware.org/?probe=9c8bb62a98) | Sep 17, 2021 |
| MSI           | GP76 Leopard 10UE           | [547ee4e1ea](https://linux-hardware.org/?probe=547ee4e1ea) | Sep 16, 2021 |
| MSI           | GP76 Leopard 10UE           | [90168ebbeb](https://linux-hardware.org/?probe=90168ebbeb) | Sep 16, 2021 |
| Toshiba       | QOSMIO X75-A                | [8c87a96580](https://linux-hardware.org/?probe=8c87a96580) | Sep 14, 2021 |
| Fujitsu       | LIFEBOOK A357               | [efc14ead6c](https://linux-hardware.org/?probe=efc14ead6c) | Sep 13, 2021 |
| Toshiba       | QOSMIO X75-A                | [7fbbeca526](https://linux-hardware.org/?probe=7fbbeca526) | Sep 13, 2021 |
| LG Electro... | RD590-K.ADJCRE6             | [00da9ca38f](https://linux-hardware.org/?probe=00da9ca38f) | Sep 12, 2021 |
| Lenovo        | ThinkPad T490 20N3S19L00    | [a19eee5494](https://linux-hardware.org/?probe=a19eee5494) | Sep 11, 2021 |
| Fujitsu       | LIFEBOOK A357               | [6a38389900](https://linux-hardware.org/?probe=6a38389900) | Sep 11, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| HP            | ZBook Studio G3             | [d239ae254a](https://linux-hardware.org/?probe=d239ae254a) | Sep 09, 2021 |
| Pegatron      | T14AF                       | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [00e399c8d4](https://linux-hardware.org/?probe=00e399c8d4) | Sep 07, 2021 |
| Lenovo        | ThinkPad T450s 20BWS04K0... | [3c7ed2f9b7](https://linux-hardware.org/?probe=3c7ed2f9b7) | Sep 06, 2021 |
| Acer          | Aspire 7750G                | [2b645d2c16](https://linux-hardware.org/?probe=2b645d2c16) | Sep 05, 2021 |
| ASUSTek       | X510UA                      | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| Acer          | Swift SF114-32              | [41a2fef2aa](https://linux-hardware.org/?probe=41a2fef2aa) | Sep 05, 2021 |
| Dell          | XPS 15 9560                 | [4b8701a2b3](https://linux-hardware.org/?probe=4b8701a2b3) | Sep 05, 2021 |
| Dell          | Inspiron 5570               | [ffa40a366f](https://linux-hardware.org/?probe=ffa40a366f) | Sep 05, 2021 |
| HP            | Laptop 15q-bu0xx            | [bc433a2411](https://linux-hardware.org/?probe=bc433a2411) | Sep 04, 2021 |
| Lenovo        | ThinkPad W540 20BHS0LA00    | [d5b967eeee](https://linux-hardware.org/?probe=d5b967eeee) | Sep 04, 2021 |
| Dell          | Latitude E6420              | [0d79becf85](https://linux-hardware.org/?probe=0d79becf85) | Sep 03, 2021 |
| Dell          | XPS 13 9300                 | [9b10289848](https://linux-hardware.org/?probe=9b10289848) | Sep 02, 2021 |
| ASUSTek       | X555QG                      | [14d10602c8](https://linux-hardware.org/?probe=14d10602c8) | Sep 02, 2021 |
| HP            | ENVY Laptop 17-cg0xxx       | [1fd99ca58d](https://linux-hardware.org/?probe=1fd99ca58d) | Sep 02, 2021 |
| Acer          | Aspire 5750                 | [c3ae9f4793](https://linux-hardware.org/?probe=c3ae9f4793) | Sep 01, 2021 |
| Acer          | Nitro AN517-52              | [d534aba928](https://linux-hardware.org/?probe=d534aba928) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d40a00437d](https://linux-hardware.org/?probe=d40a00437d) | Aug 30, 2021 |
| Timi          | TM1607                      | [0dcb7e6611](https://linux-hardware.org/?probe=0dcb7e6611) | Aug 30, 2021 |
| ASUSTek       | G750JX                      | [53da9f0547](https://linux-hardware.org/?probe=53da9f0547) | Aug 29, 2021 |
| TUXEDO        | BC1510 1710                 | [9061a72f3a](https://linux-hardware.org/?probe=9061a72f3a) | Aug 29, 2021 |
| HP            | ENVY Laptop 17-cg0xxx       | [14f5f8a179](https://linux-hardware.org/?probe=14f5f8a179) | Aug 28, 2021 |
| Dell          | Inspiron 15-5568            | [81b3e142a3](https://linux-hardware.org/?probe=81b3e142a3) | Aug 28, 2021 |
| Dell          | Inspiron 5579               | [11d1c6d073](https://linux-hardware.org/?probe=11d1c6d073) | Aug 28, 2021 |
| Apple         | MacBookPro11,1              | [0edc78c136](https://linux-hardware.org/?probe=0edc78c136) | Aug 28, 2021 |
| Eluktronic... | MAG-15 2070                 | [28b869ed18](https://linux-hardware.org/?probe=28b869ed18) | Aug 28, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f6fa665265](https://linux-hardware.org/?probe=f6fa665265) | Aug 27, 2021 |
| Dell          | XPS 15 9500                 | [62f508237e](https://linux-hardware.org/?probe=62f508237e) | Aug 25, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6ab2831848](https://linux-hardware.org/?probe=6ab2831848) | Aug 25, 2021 |
| HP            | Laptop 15-bw0xx             | [e6c79ed475](https://linux-hardware.org/?probe=e6c79ed475) | Aug 24, 2021 |
| Lenovo        | ThinkPad E14 20RA0016FR     | [94091b0705](https://linux-hardware.org/?probe=94091b0705) | Aug 24, 2021 |
| System76      | Gazelle                     | [b1f5d2f5db](https://linux-hardware.org/?probe=b1f5d2f5db) | Aug 24, 2021 |
| System76      | Gazelle                     | [be7855ec0c](https://linux-hardware.org/?probe=be7855ec0c) | Aug 24, 2021 |
| Fujitsu       | LIFEBOOK E756               | [ad2bc5b140](https://linux-hardware.org/?probe=ad2bc5b140) | Aug 23, 2021 |
| HP            | Laptop 15-da0xxx            | [2aafbc0a72](https://linux-hardware.org/?probe=2aafbc0a72) | Aug 23, 2021 |
| Dell          | Inspiron 5579               | [4e844d3321](https://linux-hardware.org/?probe=4e844d3321) | Aug 22, 2021 |
| HP            | Laptop 15-db0xxx            | [83c1674e38](https://linux-hardware.org/?probe=83c1674e38) | Aug 21, 2021 |
| HP            | Laptop 15-db0xxx            | [6dbfd72cd8](https://linux-hardware.org/?probe=6dbfd72cd8) | Aug 21, 2021 |
| ASUSTek       | X580VD                      | [5df36dba53](https://linux-hardware.org/?probe=5df36dba53) | Aug 21, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [24bbd4d06f](https://linux-hardware.org/?probe=24bbd4d06f) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e7fd668005](https://linux-hardware.org/?probe=e7fd668005) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [e17fcec0b4](https://linux-hardware.org/?probe=e17fcec0b4) | Aug 21, 2021 |
| Dell          | Inspiron 15-5568            | [7fec9a3a5b](https://linux-hardware.org/?probe=7fec9a3a5b) | Aug 21, 2021 |
| Lenovo        | ThinkPad T440 20B70048US    | [14e8d60953](https://linux-hardware.org/?probe=14e8d60953) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 7661ZLF        | [d28b77f82f](https://linux-hardware.org/?probe=d28b77f82f) | Aug 19, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC1K    | [d693db633c](https://linux-hardware.org/?probe=d693db633c) | Aug 18, 2021 |
| Dell          | XPS 15 7590                 | [3d348a9d2a](https://linux-hardware.org/?probe=3d348a9d2a) | Aug 18, 2021 |
| ASUSTek       | X556UA                      | [04710b290b](https://linux-hardware.org/?probe=04710b290b) | Aug 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6339cd2e5b](https://linux-hardware.org/?probe=6339cd2e5b) | Aug 17, 2021 |
| Razer         | Blade                       | [b6bad1f725](https://linux-hardware.org/?probe=b6bad1f725) | Aug 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4cfe1daabe](https://linux-hardware.org/?probe=4cfe1daabe) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ffa5f6a0e](https://linux-hardware.org/?probe=1ffa5f6a0e) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d00e9f1724](https://linux-hardware.org/?probe=d00e9f1724) | Aug 14, 2021 |
| ASUSTek       | X580VD                      | [4a86f48291](https://linux-hardware.org/?probe=4a86f48291) | Aug 14, 2021 |
| ASUSTek       | K53SD                       | [865c697e6a](https://linux-hardware.org/?probe=865c697e6a) | Aug 13, 2021 |
| ASUSTek       | X580VD                      | [aeae754f0f](https://linux-hardware.org/?probe=aeae754f0f) | Aug 12, 2021 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [e42d32bf2a](https://linux-hardware.org/?probe=e42d32bf2a) | Aug 12, 2021 |
| Acer          | Aspire 7741                 | [9d26562113](https://linux-hardware.org/?probe=9d26562113) | Aug 10, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1f7bf82ef4](https://linux-hardware.org/?probe=1f7bf82ef4) | Aug 10, 2021 |
| HP            | Laptop 15q-bu1xx            | [5aced87a3f](https://linux-hardware.org/?probe=5aced87a3f) | Aug 09, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [e9d2ccb049](https://linux-hardware.org/?probe=e9d2ccb049) | Aug 09, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [d2e64a8d57](https://linux-hardware.org/?probe=d2e64a8d57) | Aug 08, 2021 |
| Dell          | Vostro 3500                 | [5f24fa8f98](https://linux-hardware.org/?probe=5f24fa8f98) | Aug 08, 2021 |
| Dell          | Vostro 3500                 | [51115b9f9f](https://linux-hardware.org/?probe=51115b9f9f) | Aug 08, 2021 |
| Lenovo        | ThinkPad W541 20EF0000US    | [6150ef8ebc](https://linux-hardware.org/?probe=6150ef8ebc) | Aug 07, 2021 |
| MSI           | Modern 14 B4MW              | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [268e93bc48](https://linux-hardware.org/?probe=268e93bc48) | Aug 05, 2021 |
| MSI           | Modern 14 B4MW              | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| Acer          | Nitro AN515-53              | [baf0ccecb1](https://linux-hardware.org/?probe=baf0ccecb1) | Aug 03, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [c434457251](https://linux-hardware.org/?probe=c434457251) | Aug 03, 2021 |
| AZW           | SEi                         | [de596531ae](https://linux-hardware.org/?probe=de596531ae) | Aug 02, 2021 |
| MSI           | Modern 14 B4MW              | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| Lenovo        | ThinkPad X201 3626GWG       | [3709f5744a](https://linux-hardware.org/?probe=3709f5744a) | Aug 01, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [0724f0e60d](https://linux-hardware.org/?probe=0724f0e60d) | Aug 01, 2021 |
| ASUSTek       | E200HA                      | [2b732e43eb](https://linux-hardware.org/?probe=2b732e43eb) | Aug 01, 2021 |
| ASUSTek       | E200HA                      | [68b431bc45](https://linux-hardware.org/?probe=68b431bc45) | Aug 01, 2021 |
| Apple         | MacBookPro9,2               | [a8e52318c8](https://linux-hardware.org/?probe=a8e52318c8) | Aug 01, 2021 |
| Apple         | MacBookPro9,2               | [949e4af6a7](https://linux-hardware.org/?probe=949e4af6a7) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [730d886e60](https://linux-hardware.org/?probe=730d886e60) | Jul 31, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [65d9b956bc](https://linux-hardware.org/?probe=65d9b956bc) | Jul 30, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e84e4c3d4c](https://linux-hardware.org/?probe=e84e4c3d4c) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e9fd822a6](https://linux-hardware.org/?probe=0e9fd822a6) | Jul 29, 2021 |
| Dell          | Precision 7520              | [bb1844c704](https://linux-hardware.org/?probe=bb1844c704) | Jul 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [423bc2b7a1](https://linux-hardware.org/?probe=423bc2b7a1) | Jul 28, 2021 |
| HP            | Compaq Presario CQ40        | [14b629549c](https://linux-hardware.org/?probe=14b629549c) | Jul 27, 2021 |
| HP            | Compaq Presario CQ40        | [b82622eb33](https://linux-hardware.org/?probe=b82622eb33) | Jul 25, 2021 |
| Unknown       | Unknown                     | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| Dell          | Latitude 5410               | [cb463b1fc3](https://linux-hardware.org/?probe=cb463b1fc3) | Jul 22, 2021 |
| HP            | Stream Notebook PC 13       | [6631c46029](https://linux-hardware.org/?probe=6631c46029) | Jul 22, 2021 |
| Dell          | Latitude 7370               | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Dell          | Vostro 5568                 | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| HP            | Laptop 15-da0xxx            | [4cb2daf424](https://linux-hardware.org/?probe=4cb2daf424) | Jul 16, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [be2edf1657](https://linux-hardware.org/?probe=be2edf1657) | Jul 14, 2021 |
| Acer          | Aspire E5-575G              | [672a2b3117](https://linux-hardware.org/?probe=672a2b3117) | Jul 14, 2021 |
| HP            | Notebook                    | [021a011da8](https://linux-hardware.org/?probe=021a011da8) | Jul 13, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [9779eaca87](https://linux-hardware.org/?probe=9779eaca87) | Jul 11, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [329bbc8c40](https://linux-hardware.org/?probe=329bbc8c40) | Jul 10, 2021 |
| MSI           | GP63 Leopard 8RE            | [2114ad4f9e](https://linux-hardware.org/?probe=2114ad4f9e) | Jul 10, 2021 |
| MSI           | GP63 Leopard 8RE            | [a469d525e3](https://linux-hardware.org/?probe=a469d525e3) | Jul 10, 2021 |
| Fujitsu       | LIFEBOOK S751               | [fc7d66f096](https://linux-hardware.org/?probe=fc7d66f096) | Jul 08, 2021 |
| Dell          | XPS 13 9360                 | [252e038506](https://linux-hardware.org/?probe=252e038506) | Jul 08, 2021 |
| Dell          | XPS 13 9360                 | [bb7d68bae6](https://linux-hardware.org/?probe=bb7d68bae6) | Jul 08, 2021 |
| Fujitsu       | LIFEBOOK T902               | [4ed05b4d7b](https://linux-hardware.org/?probe=4ed05b4d7b) | Jul 07, 2021 |
| Acer          | Aspire E5-573G              | [f1f413aced](https://linux-hardware.org/?probe=f1f413aced) | Jul 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6f489566ae](https://linux-hardware.org/?probe=6f489566ae) | Jul 06, 2021 |
| Fujitsu       | LIFEBOOK T902               | [4fb535811d](https://linux-hardware.org/?probe=4fb535811d) | Jul 05, 2021 |
| ASUSTek       | Q550LF                      | [3aafd6f8a6](https://linux-hardware.org/?probe=3aafd6f8a6) | Jul 05, 2021 |
| Dell          | Latitude 7480               | [827e1b8a21](https://linux-hardware.org/?probe=827e1b8a21) | Jul 04, 2021 |
| Fujitsu       | LIFEBOOK T902               | [7e6ee2f561](https://linux-hardware.org/?probe=7e6ee2f561) | Jul 04, 2021 |
| ASUSTek       | X510UNR                     | [3c8630ec48](https://linux-hardware.org/?probe=3c8630ec48) | Jul 04, 2021 |
| Notebook      | P95_HP                      | [8aa8037e16](https://linux-hardware.org/?probe=8aa8037e16) | Jul 03, 2021 |
| Dell          | Vostro 5568                 | [bec8a61ff4](https://linux-hardware.org/?probe=bec8a61ff4) | Jul 03, 2021 |
| Lenovo        | ThinkPad T440p 20AWX5140... | [e08d79f016](https://linux-hardware.org/?probe=e08d79f016) | Jul 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWX5140... | [06e8c86830](https://linux-hardware.org/?probe=06e8c86830) | Jul 02, 2021 |
| HP            | 250 G1                      | [bc56e9fe6f](https://linux-hardware.org/?probe=bc56e9fe6f) | Jul 02, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c0ed3a3c09](https://linux-hardware.org/?probe=c0ed3a3c09) | Jul 02, 2021 |
| Apple         | MacBookPro11,5              | [ea85c0f143](https://linux-hardware.org/?probe=ea85c0f143) | Jul 02, 2021 |
| Acer          | Swift SF314-41G             | [fe5e126da1](https://linux-hardware.org/?probe=fe5e126da1) | Jul 01, 2021 |
| Apple         | MacBookPro12,1              | [0a8dac703d](https://linux-hardware.org/?probe=0a8dac703d) | Jun 29, 2021 |
| Apple         | MacBookPro8,1               | [aac1bf4737](https://linux-hardware.org/?probe=aac1bf4737) | Jun 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [127874b25b](https://linux-hardware.org/?probe=127874b25b) | Jun 28, 2021 |
| ASUSTek       | K53E                        | [3ad8363a7d](https://linux-hardware.org/?probe=3ad8363a7d) | Jun 28, 2021 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [ceab39c39a](https://linux-hardware.org/?probe=ceab39c39a) | Jun 28, 2021 |
| Acer          | Predator G3-572             | [982137c856](https://linux-hardware.org/?probe=982137c856) | Jun 28, 2021 |
| Lenovo        | ThinkPad X240 20AM001RGE    | [5e80a2492e](https://linux-hardware.org/?probe=5e80a2492e) | Jun 28, 2021 |
| Apple         | MacBookPro11,5              | [29dedcc0c7](https://linux-hardware.org/?probe=29dedcc0c7) | Jun 28, 2021 |
| AZW           | GT-R                        | [feaf90902f](https://linux-hardware.org/?probe=feaf90902f) | Jun 28, 2021 |
| Lenovo        | ThinkPad T410 2522E38       | [5fd8e985e9](https://linux-hardware.org/?probe=5fd8e985e9) | Jun 28, 2021 |
| Dell          | XPS 17 9700                 | [cbf1953567](https://linux-hardware.org/?probe=cbf1953567) | Jun 27, 2021 |
| Alienware     | m15 Ryzen Ed. R5            | [d48faf5072](https://linux-hardware.org/?probe=d48faf5072) | Jun 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3fb422fa2e](https://linux-hardware.org/?probe=3fb422fa2e) | Jun 27, 2021 |
| Toshiba       | Satellite C600              | [2be9935e22](https://linux-hardware.org/?probe=2be9935e22) | Jun 25, 2021 |
| MSI           | Modern 14 A10M              | [a07552d987](https://linux-hardware.org/?probe=a07552d987) | Jun 24, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [e4ba771332](https://linux-hardware.org/?probe=e4ba771332) | Jun 22, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [495c04a536](https://linux-hardware.org/?probe=495c04a536) | Jun 22, 2021 |
| HP            | EliteBook 840 G4            | [1155abf435](https://linux-hardware.org/?probe=1155abf435) | Jun 22, 2021 |
| HUAWEI        | MACH-WX9                    | [4c0b858cde](https://linux-hardware.org/?probe=4c0b858cde) | Jun 19, 2021 |
| Dell          | Inspiron 13-5378            | [5246eabc5f](https://linux-hardware.org/?probe=5246eabc5f) | Jun 17, 2021 |
| Dell          | Inspiron 3593               | [ba202e6f1e](https://linux-hardware.org/?probe=ba202e6f1e) | Jun 17, 2021 |
| Schenker      | XMG CORE (M19, GTX 1650)    | [22aabc71ef](https://linux-hardware.org/?probe=22aabc71ef) | Jun 17, 2021 |
| Schenker      | XMG CORE (M19, GTX 1650)    | [99a0a332ec](https://linux-hardware.org/?probe=99a0a332ec) | Jun 17, 2021 |
| HP            | Pavilion Notebook           | [b81aa5226f](https://linux-hardware.org/?probe=b81aa5226f) | Jun 17, 2021 |
| Alienware     | 17                          | [9d281e3351](https://linux-hardware.org/?probe=9d281e3351) | Jun 16, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [ac8e80e0cc](https://linux-hardware.org/?probe=ac8e80e0cc) | Jun 15, 2021 |
| Apple         | MacBookAir1,1               | [a6cf581d50](https://linux-hardware.org/?probe=a6cf581d50) | Jun 14, 2021 |
| Apple         | MacBookAir1,1               | [48c28ecda7](https://linux-hardware.org/?probe=48c28ecda7) | Jun 14, 2021 |
| Dell          | Inspiron 5485 2n1           | [cda45b1f3c](https://linux-hardware.org/?probe=cda45b1f3c) | Jun 14, 2021 |
| Dell          | Latitude E6440              | [908df2d475](https://linux-hardware.org/?probe=908df2d475) | Jun 13, 2021 |
| Medion        | Erazer X7841 MD99556        | [a15e0c5ae0](https://linux-hardware.org/?probe=a15e0c5ae0) | Jun 12, 2021 |
| Dell          | XPS 17 9700                 | [f6b6b11c24](https://linux-hardware.org/?probe=f6b6b11c24) | Jun 12, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Fujitsu       | LIFEBOOK S751               | [20ff390b75](https://linux-hardware.org/?probe=20ff390b75) | Jun 11, 2021 |
| Acer          | Aspire A715-71G             | [64db1224d0](https://linux-hardware.org/?probe=64db1224d0) | Jun 10, 2021 |
| HP            | Laptop 15q-bu0xx            | [758cd92d87](https://linux-hardware.org/?probe=758cd92d87) | Jun 10, 2021 |
| Razer         | Blade                       | [e6ee630e9b](https://linux-hardware.org/?probe=e6ee630e9b) | Jun 06, 2021 |
| Apple         | MacBookPro11,1              | [f6f2cf5f89](https://linux-hardware.org/?probe=f6f2cf5f89) | Jun 05, 2021 |
| Lenovo        | ThinkPad X220 4290LD4       | [22bbadb3dd](https://linux-hardware.org/?probe=22bbadb3dd) | Jun 03, 2021 |
| Lenovo        | ThinkPad X230 2306CTO       | [fa237f560a](https://linux-hardware.org/?probe=fa237f560a) | Jun 02, 2021 |
| Lenovo        | ThinkPad X230 2306CTO       | [4d799b19db](https://linux-hardware.org/?probe=4d799b19db) | Jun 02, 2021 |
| Toshiba       | Satellite L635              | [c5883a9da8](https://linux-hardware.org/?probe=c5883a9da8) | Jun 01, 2021 |
| Toshiba       | Satellite L635              | [634bc5add8](https://linux-hardware.org/?probe=634bc5add8) | May 30, 2021 |
| System76      | Oryx Pro                    | [e18b16565f](https://linux-hardware.org/?probe=e18b16565f) | May 29, 2021 |
| Toshiba       | Satellite R630              | [0c557895be](https://linux-hardware.org/?probe=0c557895be) | May 29, 2021 |
| Daten Tecn... | ESTELAR                     | [f19e7920ca](https://linux-hardware.org/?probe=f19e7920ca) | May 29, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [1daf88898e](https://linux-hardware.org/?probe=1daf88898e) | May 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [302b62a5c7](https://linux-hardware.org/?probe=302b62a5c7) | May 20, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ae6af1c7e1](https://linux-hardware.org/?probe=ae6af1c7e1) | May 14, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | [0d44d30be1](https://linux-hardware.org/?probe=0d44d30be1) | May 13, 2021 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | [00aa4c11f4](https://linux-hardware.org/?probe=00aa4c11f4) | May 13, 2021 |
| Sony          | SVE14125CXP                 | [23d5e048cb](https://linux-hardware.org/?probe=23d5e048cb) | May 13, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [28f6f5a90b](https://linux-hardware.org/?probe=28f6f5a90b) | May 12, 2021 |
| Toshiba       | Satellite L50-A-19N         | [988020930b](https://linux-hardware.org/?probe=988020930b) | May 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [952093c613](https://linux-hardware.org/?probe=952093c613) | May 09, 2021 |
| HP            | Pavilion Notebook           | [da82b1b43f](https://linux-hardware.org/?probe=da82b1b43f) | May 09, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | [ab871dcbe2](https://linux-hardware.org/?probe=ab871dcbe2) | May 01, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | [f8bbdfd850](https://linux-hardware.org/?probe=f8bbdfd850) | Apr 30, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | [2df93a93d1](https://linux-hardware.org/?probe=2df93a93d1) | Apr 30, 2021 |
| HP            | 250 G1                      | [0810673d99](https://linux-hardware.org/?probe=0810673d99) | Apr 29, 2021 |
| Dell          | Latitude E6440              | [535815022c](https://linux-hardware.org/?probe=535815022c) | Apr 23, 2021 |
| HP            | 255 G2                      | [338785dab3](https://linux-hardware.org/?probe=338785dab3) | Apr 22, 2021 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | [f707b24713](https://linux-hardware.org/?probe=f707b24713) | Apr 22, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [16ab380d72](https://linux-hardware.org/?probe=16ab380d72) | Apr 21, 2021 |
| Dell          | Vostro 3550                 | [2b122eb7e6](https://linux-hardware.org/?probe=2b122eb7e6) | Apr 21, 2021 |
| ASUSTek       | UX430UAR                    | [a071188f1c](https://linux-hardware.org/?probe=a071188f1c) | Apr 21, 2021 |
| Lenovo        | G50-70 20351                | [44e6cc36ce](https://linux-hardware.org/?probe=44e6cc36ce) | Apr 20, 2021 |
| HP            | EliteBook 8460p             | [dc1e0bf320](https://linux-hardware.org/?probe=dc1e0bf320) | Apr 19, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [eeee3c8078](https://linux-hardware.org/?probe=eeee3c8078) | Apr 18, 2021 |
| HP            | 255 G7 Notebook PC          | [ba1e3ed32e](https://linux-hardware.org/?probe=ba1e3ed32e) | Apr 15, 2021 |
| Dell          | XPS 15 9570                 | [ee1c82a186](https://linux-hardware.org/?probe=ee1c82a186) | Apr 15, 2021 |
| Lenovo        | G50-45 80E3                 | [7633456df0](https://linux-hardware.org/?probe=7633456df0) | Apr 15, 2021 |
| ASUSTek       | N550JV                      | [61b2baa2d1](https://linux-hardware.org/?probe=61b2baa2d1) | Apr 13, 2021 |
| Chuwi         | GemiBook Pro                | [9909625298](https://linux-hardware.org/?probe=9909625298) | Apr 12, 2021 |
| Acer          | Predator PH315-52           | [97c81f4b56](https://linux-hardware.org/?probe=97c81f4b56) | Apr 11, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [76b41f73e8](https://linux-hardware.org/?probe=76b41f73e8) | Apr 11, 2021 |
| Toshiba       | PORTEGE Z30t-C              | [39dd5ca43b](https://linux-hardware.org/?probe=39dd5ca43b) | Apr 11, 2021 |
| Dell          | XPS 13 9380                 | [8ceda587e7](https://linux-hardware.org/?probe=8ceda587e7) | Apr 09, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | [dc8d311227](https://linux-hardware.org/?probe=dc8d311227) | Apr 09, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [337a0c3723](https://linux-hardware.org/?probe=337a0c3723) | Apr 08, 2021 |
| Acer          | NU-A515-44-R68D             | [7e8724905f](https://linux-hardware.org/?probe=7e8724905f) | Apr 06, 2021 |
| HP            | EliteBook 840 G3            | [5a663fff6e](https://linux-hardware.org/?probe=5a663fff6e) | Apr 05, 2021 |
| Lenovo        | ThinkPad X220 4291WF5       | [7cf8cfd8f8](https://linux-hardware.org/?probe=7cf8cfd8f8) | Apr 04, 2021 |
| Lenovo        | ThinkPad T480 20L6S27S0P    | [6fc0f5a4b6](https://linux-hardware.org/?probe=6fc0f5a4b6) | Apr 03, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [742b7afcc8](https://linux-hardware.org/?probe=742b7afcc8) | Apr 01, 2021 |
| Toshiba       | Satellite C55-A-1N0         | [53fe8e1c6c](https://linux-hardware.org/?probe=53fe8e1c6c) | Mar 31, 2021 |
| Dell          | Latitude E7440              | [e0c5eda63a](https://linux-hardware.org/?probe=e0c5eda63a) | Mar 31, 2021 |
| Dell          | Inspiron 5520               | [151b34a749](https://linux-hardware.org/?probe=151b34a749) | Mar 29, 2021 |
| Dell          | Latitude E7440              | [1c004faf2a](https://linux-hardware.org/?probe=1c004faf2a) | Mar 28, 2021 |
| Toshiba       | Satellite C55-A-1N0         | [7fe4a33a38](https://linux-hardware.org/?probe=7fe4a33a38) | Mar 27, 2021 |
| Lenovo        | ThinkPad T480s 20L7001LR... | [440edfbe7e](https://linux-hardware.org/?probe=440edfbe7e) | Mar 26, 2021 |
| Dell          | Latitude 3580               | [0de8d9cd4c](https://linux-hardware.org/?probe=0de8d9cd4c) | Mar 25, 2021 |
| Dell          | Latitude E6530              | [7cce6316f6](https://linux-hardware.org/?probe=7cce6316f6) | Mar 24, 2021 |
| Lenovo        | ThinkPad 11e 20D90020US     | [e5948a4e4c](https://linux-hardware.org/?probe=e5948a4e4c) | Mar 24, 2021 |
| Dell          | Inspiron 5593               | [0348f8af6b](https://linux-hardware.org/?probe=0348f8af6b) | Mar 23, 2021 |
| Dell          | Latitude E4310              | [16025a8970](https://linux-hardware.org/?probe=16025a8970) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | [da8880b543](https://linux-hardware.org/?probe=da8880b543) | Mar 19, 2021 |
| Dell          | Inspiron 5575               | [4b72276133](https://linux-hardware.org/?probe=4b72276133) | Mar 17, 2021 |
| Dell          | Latitude E6440              | [8eb5c8aaa9](https://linux-hardware.org/?probe=8eb5c8aaa9) | Mar 17, 2021 |
| Dell          | Inspiron 5555               | [4b3ec85962](https://linux-hardware.org/?probe=4b3ec85962) | Mar 16, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [e2e99630ca](https://linux-hardware.org/?probe=e2e99630ca) | Mar 14, 2021 |
| HP            | G62                         | [f586fad981](https://linux-hardware.org/?probe=f586fad981) | Mar 14, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ArcoLinux/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| ArcoLinux Rolling     | 769       | 88.19%  |
| ArcoLinux             | 82        | 9.4%    |
| ArcoLinux 20.6.5      | 7         | 0.8%    |
| ArcoLinux 20.7.5      | 4         | 0.46%   |
| ArcoLinux 20.3.4      | 2         | 0.23%   |
| ArcoLinux 20.3.3      | 2         | 0.23%   |
| ArcoLinux I3-v19.02.4 | 1         | 0.11%   |
| ArcoLinux 6.9.2       | 1         | 0.11%   |
| ArcoLinux 20.2.12     | 1         | 0.11%   |
| ArcoLinux 20.1.4      | 1         | 0.11%   |
| ArcoLinux 19.07.11    | 1         | 0.11%   |
| ArcoLinux 19.02.4     | 1         | 0.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ArcoLinux | 866       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.15.7-arch1-1  | 20        | 2.03%   |
| 5.15.10-arch1-1 | 19        | 1.93%   |
| 5.13.13-arch1-1 | 18        | 1.83%   |
| 5.14.14-arch1-1 | 14        | 1.42%   |
| 5.13.12-arch1-1 | 13        | 1.32%   |
| 6.2.8-arch1-1   | 12        | 1.22%   |
| 6.2.11-arch1-1  | 12        | 1.22%   |
| 6.1.12-arch1-1  | 12        | 1.22%   |
| 5.14.12-arch1-1 | 12        | 1.22%   |
| 5.17.1-arch1-1  | 11        | 1.12%   |
| 5.12.13-arch1-2 | 10        | 1.02%   |
| 5.15.11-arch2-1 | 9         | 0.91%   |
| 6.0.8-arch1-1   | 8         | 0.81%   |
| 5.9.8-arch1-1   | 8         | 0.81%   |
| 5.9.1-arch1-1   | 8         | 0.81%   |
| 5.16.10-arch1-1 | 8         | 0.81%   |
| 5.15.5-arch1-1  | 8         | 0.81%   |
| 5.12.15-arch1-1 | 8         | 0.81%   |
| 5.12.14-arch1-1 | 8         | 0.81%   |
| 5.17.4-arch1-1  | 7         | 0.71%   |
| 5.16.2-arch1-1  | 7         | 0.71%   |
| 5.16.16-arch1-1 | 7         | 0.71%   |
| 5.15.13-arch1-1 | 7         | 0.71%   |
| 5.12.10-arch1-1 | 7         | 0.71%   |
| 6.2.2-arch1-1   | 6         | 0.61%   |
| 6.1.1-arch1-1   | 6         | 0.61%   |
| 6.0.2-arch1-1   | 6         | 0.61%   |
| 6.0.10-arch2-1  | 6         | 0.61%   |
| 5.9.10-arch1-1  | 6         | 0.61%   |
| 5.19.13-arch1-1 | 6         | 0.61%   |
| 5.18.16-arch1-1 | 6         | 0.61%   |
| 5.17.5-arch1-1  | 6         | 0.61%   |
| 5.16.12-arch1-1 | 6         | 0.61%   |
| 5.14.9-arch2-1  | 6         | 0.61%   |
| 5.13.8-arch1-1  | 6         | 0.61%   |
| 5.12.12-arch1-1 | 6         | 0.61%   |
| 5.10.84-1-lts   | 6         | 0.61%   |
| 6.0.7-arch1-1   | 5         | 0.51%   |
| 6.0.12-arch1-1  | 5         | 0.51%   |
| 5.4.70-1-lts    | 5         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.7  | 24        | 2.44%   |
| 5.15.10 | 19        | 1.93%   |
| 5.13.13 | 18        | 1.83%   |
| 6.2.8   | 14        | 1.42%   |
| 6.1.12  | 14        | 1.42%   |
| 5.17.1  | 14        | 1.42%   |
| 5.14.14 | 14        | 1.42%   |
| 6.2.11  | 13        | 1.32%   |
| 5.14.12 | 13        | 1.32%   |
| 5.13.12 | 13        | 1.32%   |
| 5.9.8   | 12        | 1.22%   |
| 6.0.2   | 11        | 1.12%   |
| 6.0.8   | 10        | 1.02%   |
| 5.9.1   | 10        | 1.02%   |
| 5.12.13 | 10        | 1.02%   |
| 6.1.1   | 9         | 0.91%   |
| 5.16.2  | 9         | 0.91%   |
| 5.16.10 | 9         | 0.91%   |
| 5.15.5  | 9         | 0.91%   |
| 5.15.11 | 9         | 0.91%   |
| 5.12.15 | 9         | 0.91%   |
| 5.9.14  | 8         | 0.81%   |
| 5.14.9  | 8         | 0.81%   |
| 5.12.14 | 8         | 0.81%   |
| 5.10.16 | 8         | 0.81%   |
| 6.2.2   | 7         | 0.71%   |
| 6.1.6   | 7         | 0.71%   |
| 6.0.7   | 7         | 0.71%   |
| 6.0.10  | 7         | 0.71%   |
| 5.9.6   | 7         | 0.71%   |
| 5.9.10  | 7         | 0.71%   |
| 5.17.5  | 7         | 0.71%   |
| 5.17.4  | 7         | 0.71%   |
| 5.16.16 | 7         | 0.71%   |
| 5.15.13 | 7         | 0.71%   |
| 5.12.10 | 7         | 0.71%   |
| 6.1.9   | 6         | 0.61%   |
| 5.19.13 | 6         | 0.61%   |
| 5.19.11 | 6         | 0.61%   |
| 5.18.3  | 6         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 140       | 14.72%  |
| 5.10    | 124       | 13.04%  |
| 6.1     | 66        | 6.94%   |
| 5.16    | 64        | 6.73%   |
| 5.14    | 62        | 6.52%   |
| 5.13    | 60        | 6.31%   |
| 6.2     | 59        | 6.2%    |
| 5.9     | 57        | 5.99%   |
| 6.0     | 55        | 5.78%   |
| 5.12    | 54        | 5.68%   |
| 5.17    | 47        | 4.94%   |
| 5.18    | 43        | 4.52%   |
| 5.11    | 35        | 3.68%   |
| 5.4     | 33        | 3.47%   |
| 5.19    | 33        | 3.47%   |
| 5.8     | 6         | 0.63%   |
| 5.7     | 4         | 0.42%   |
| 5.5     | 3         | 0.32%   |
| 5.6     | 2         | 0.21%   |
| 5.2     | 1         | 0.11%   |
| 5.0     | 1         | 0.11%   |
| 4.20    | 1         | 0.11%   |
| 4.18    | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 866       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| XFCE           | 280       | 31.15%  |
| KDE5           | 147       | 16.35%  |
| i3             | 68        | 7.56%   |
| GNOME          | 64        | 7.12%   |
| awesome        | 56        | 6.23%   |
| qtile          | 42        | 4.67%   |
| bspwm          | 36        | 4%      |
| X-Cinnamon     | 32        | 3.56%   |
| xmonad         | 28        | 3.11%   |
| DWM            | 28        | 3.11%   |
| Hyprland       | 13        | 1.45%   |
| LeftWM         | 12        | 1.33%   |
| KDE            | 12        | 1.33%   |
| MATE           | 11        | 1.22%   |
| Unknown        | 11        | 1.22%   |
| Deepin         | 8         | 0.89%   |
| i3-with-shmlog | 7         | 0.78%   |
| herbstluftwm   | 7         | 0.78%   |
| Budgie         | 7         | 0.78%   |
| chadwm         | 5         | 0.56%   |
| LXQt           | 4         | 0.44%   |
| Cinnamon       | 4         | 0.44%   |
| sway           | 3         | 0.33%   |
| spectrwm       | 3         | 0.33%   |
| Unity          | 2         | 0.22%   |
| cwm            | 2         | 0.22%   |
| openbox        | 1         | 0.11%   |
| jwm            | 1         | 0.11%   |
| ICEWM          | 1         | 0.11%   |
| GNOME Classic  | 1         | 0.11%   |
| dwm-sc         | 1         | 0.11%   |
| dusk           | 1         | 0.11%   |
| Cutefish       | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 798       | 91.2%   |
| Wayland | 44        | 5.03%   |
| Tty     | 30        | 3.43%   |
| Unknown | 3         | 0.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 478       | 52.64%  |
| TDM     | 149       | 16.41%  |
| LightDM | 149       | 16.41%  |
| Unknown | 100       | 11.01%  |
| GDM     | 26        | 2.86%   |
| Ly      | 3         | 0.33%   |
| XDM     | 1         | 0.11%   |
| SLiM    | 1         | 0.11%   |
| LXDM    | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 503       | 57.42%  |
| en_GB   | 61        | 6.96%   |
| de_DE   | 52        | 5.94%   |
| en_IN   | 30        | 3.42%   |
| en_CA   | 29        | 3.31%   |
| fr_FR   | 19        | 2.17%   |
| pt_BR   | 14        | 1.6%    |
| en_AU   | 14        | 1.6%    |
| ru_RU   | 12        | 1.37%   |
| pl_PL   | 11        | 1.26%   |
| es_ES   | 10        | 1.14%   |
| it_IT   | 7         | 0.8%    |
| Unknown | 7         | 0.8%    |
| hu_HU   | 6         | 0.68%   |
| es_AR   | 6         | 0.68%   |
| C       | 6         | 0.68%   |
| tr_TR   | 5         | 0.57%   |
| es_MX   | 5         | 0.57%   |
| en_ZA   | 5         | 0.57%   |
| ru_UA   | 4         | 0.46%   |
| en_IE   | 4         | 0.46%   |
| nl_BE   | 3         | 0.34%   |
| fr_CA   | 3         | 0.34%   |
| fr_BE   | 3         | 0.34%   |
| es_CL   | 3         | 0.34%   |
| en_SG   | 3         | 0.34%   |
| en_PH   | 3         | 0.34%   |
| en_IL   | 3         | 0.34%   |
| en_DK   | 3         | 0.34%   |
| el_GR   | 3         | 0.34%   |
| sv_SE   | 2         | 0.23%   |
| ro_RO   | 2         | 0.23%   |
| nl_NL   | 2         | 0.23%   |
| nb_NO   | 2         | 0.23%   |
| ja_JP   | 2         | 0.23%   |
| fi_FI   | 2         | 0.23%   |
| es_CO   | 2         | 0.23%   |
| en_NZ   | 2         | 0.23%   |
| en_AG   | 2         | 0.23%   |
| de_ch   | 2         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 616       | 70.72%  |
| BIOS | 255       | 29.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 665       | 75.83%  |
| Btrfs   | 157       | 17.9%   |
| Overlay | 37        | 4.22%   |
| Xfs     | 12        | 1.37%   |
| F2fs    | 3         | 0.34%   |
| Tmpfs   | 1         | 0.11%   |
| Jfs     | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 629       | 71.97%  |
| MBR     | 153       | 17.51%  |
| Unknown | 92        | 10.53%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 715       | 80.88%  |
| Yes       | 169       | 19.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 576       | 66.21%  |
| Yes       | 294       | 33.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 243       | 28.06%  |
| Dell                  | 137       | 15.82%  |
| Hewlett-Packard       | 116       | 13.39%  |
| ASUSTek Computer      | 107       | 12.36%  |
| Acer                  | 65        | 7.51%   |
| Apple                 | 28        | 3.23%   |
| Toshiba               | 20        | 2.31%   |
| MSI                   | 20        | 2.31%   |
| Sony                  | 11        | 1.27%   |
| Samsung Electronics   | 10        | 1.15%   |
| HUAWEI                | 10        | 1.15%   |
| System76              | 9         | 1.04%   |
| Timi                  | 7         | 0.81%   |
| Razer                 | 7         | 0.81%   |
| Fujitsu               | 7         | 0.81%   |
| TUXEDO                | 6         | 0.69%   |
| Notebook              | 6         | 0.69%   |
| Medion                | 6         | 0.69%   |
| Alienware             | 6         | 0.69%   |
| Chuwi                 | 5         | 0.58%   |
| Unknown               | 4         | 0.46%   |
| Schenker              | 3         | 0.35%   |
| LG Electronics        | 3         | 0.35%   |
| Teclast               | 2         | 0.23%   |
| Packard Bell          | 2         | 0.23%   |
| Monster               | 2         | 0.23%   |
| Gigabyte Technology   | 2         | 0.23%   |
| Casper                | 2         | 0.23%   |
| AZW                   | 2         | 0.23%   |
| Xplore                | 1         | 0.12%   |
| UNITCOM               | 1         | 0.12%   |
| Standard              | 1         | 0.12%   |
| SLIMBOOK              | 1         | 0.12%   |
| Shuttle               | 1         | 0.12%   |
| Semp Toshiba          | 1         | 0.12%   |
| Positivo Bahia - VAIO | 1         | 0.12%   |
| Pegatron              | 1         | 0.12%   |
| NEC Computers         | 1         | 0.12%   |
| Intel Client Systems  | 1         | 0.12%   |
| Google                | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP Pavilion Notebook                 | 6         | 0.69%   |
| Unknown                              | 6         | 0.69%   |
| HP Notebook                          | 5         | 0.58%   |
| Razer Blade                          | 4         | 0.46%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ     | 4         | 0.46%   |
| HP Laptop 15s-eq2xxx                 | 4         | 0.46%   |
| HP EliteBook 840 G3                  | 4         | 0.46%   |
| Dell XPS 15 9570                     | 4         | 0.46%   |
| Timi TM1607                          | 3         | 0.35%   |
| System76 Pangolin                    | 3         | 0.35%   |
| Lenovo ThinkPad T14 Gen 1 20UDCTO1WW | 3         | 0.35%   |
| Lenovo Legion Y540-15IRH 81SX        | 3         | 0.35%   |
| Lenovo Legion 5 15ARH05 82B5         | 3         | 0.35%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 3         | 0.35%   |
| Lenovo IdeaPad 320-15ISK 80XH        | 3         | 0.35%   |
| HUAWEI KLVL-WXX9                     | 3         | 0.35%   |
| HP Pavilion Gaming Laptop 15-ec0xxx  | 3         | 0.35%   |
| HP Pavilion dv7                      | 3         | 0.35%   |
| HP Laptop 15-da0xxx                  | 3         | 0.35%   |
| HP ENVY Notebook                     | 3         | 0.35%   |
| HP ENVY 15                           | 3         | 0.35%   |
| HP EliteBook 8460p                   | 3         | 0.35%   |
| HP 255 G7 Notebook PC                | 3         | 0.35%   |
| HP 250 G7 Notebook PC                | 3         | 0.35%   |
| Dell Precision M4800                 | 3         | 0.35%   |
| Dell Latitude E6530                  | 3         | 0.35%   |
| Dell Latitude 7480                   | 3         | 0.35%   |
| Dell Latitude 3410                   | 3         | 0.35%   |
| Dell Inspiron 5570                   | 3         | 0.35%   |
| Dell Inspiron 3558                   | 3         | 0.35%   |
| Dell Inspiron 15 7000 Gaming         | 3         | 0.35%   |
| Chuwi GemiBook Pro                   | 3         | 0.35%   |
| Apple MacBookPro9,2                  | 3         | 0.35%   |
| Apple MacBookPro8,1                  | 3         | 0.35%   |
| Apple MacBookPro11,2                 | 3         | 0.35%   |
| Apple MacBookPro11,1                 | 3         | 0.35%   |
| Acer Swift SF314-41                  | 3         | 0.35%   |
| Acer Aspire E5-575G                  | 3         | 0.35%   |
| Toshiba Satellite L775               | 2         | 0.23%   |
| Timi TM1701                          | 2         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 132       | 15.24%  |
| Lenovo IdeaPad     | 55        | 6.35%   |
| Dell Inspiron      | 46        | 5.31%   |
| Dell Latitude      | 45        | 5.2%    |
| Acer Aspire        | 43        | 4.97%   |
| HP Pavilion        | 26        | 3%      |
| ASUS VivoBook      | 26        | 3%      |
| Lenovo Legion      | 24        | 2.77%   |
| Dell XPS           | 24        | 2.77%   |
| HP Laptop          | 22        | 2.54%   |
| HP EliteBook       | 22        | 2.54%   |
| Toshiba Satellite  | 17        | 1.96%   |
| Dell Precision     | 12        | 1.39%   |
| ASUS ROG           | 10        | 1.15%   |
| HP ENVY            | 9         | 1.04%   |
| Apple MacBookPro11 | 8         | 0.92%   |
| Acer Nitro         | 8         | 0.92%   |
| Razer Blade        | 7         | 0.81%   |
| HP ProBook         | 7         | 0.81%   |
| Fujitsu LIFEBOOK   | 7         | 0.81%   |
| Dell Vostro        | 7         | 0.81%   |
| ASUS TUF           | 7         | 0.81%   |
| Acer Swift         | 7         | 0.81%   |
| HP 250             | 6         | 0.69%   |
| ASUS Zenbook       | 6         | 0.69%   |
| Unknown            | 6         | 0.69%   |
| HP Notebook        | 5         | 0.58%   |
| Lenovo Yoga        | 4         | 0.46%   |
| HP OMEN            | 4         | 0.46%   |
| HP 255             | 4         | 0.46%   |
| ASUS Zephyrus      | 4         | 0.46%   |
| Acer Predator      | 4         | 0.46%   |
| Timi TM1607        | 3         | 0.35%   |
| System76 Pangolin  | 3         | 0.35%   |
| Lenovo ThinkBook   | 3         | 0.35%   |
| HUAWEI KLVL-WXX9   | 3         | 0.35%   |
| HP ZBook           | 3         | 0.35%   |
| Chuwi GemiBook     | 3         | 0.35%   |
| Apple MacBookPro9  | 3         | 0.35%   |
| Apple MacBookPro8  | 3         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 108       | 12.47%  |
| 2019 | 102       | 11.78%  |
| 2018 | 88        | 10.16%  |
| 2017 | 88        | 10.16%  |
| 2021 | 75        | 8.66%   |
| 2016 | 66        | 7.62%   |
| 2011 | 60        | 6.93%   |
| 2013 | 59        | 6.81%   |
| 2015 | 48        | 5.54%   |
| 2012 | 46        | 5.31%   |
| 2010 | 44        | 5.08%   |
| 2014 | 38        | 4.39%   |
| 2008 | 15        | 1.73%   |
| 2022 | 12        | 1.39%   |
| 2009 | 12        | 1.39%   |
| 2007 | 4         | 0.46%   |
| 2006 | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 866       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 866       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 861       | 99.42%  |
| Yes  | 5         | 0.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 288       | 32.99%  |
| 16.01-24.0  | 202       | 23.14%  |
| 8.01-16.0   | 164       | 18.79%  |
| 3.01-4.0    | 115       | 13.17%  |
| 32.01-64.0  | 61        | 6.99%   |
| 64.01-256.0 | 13        | 1.49%   |
| 1.01-2.0    | 13        | 1.49%   |
| 24.01-32.0  | 11        | 1.26%   |
| 2.01-3.0    | 6         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 298       | 31.77%  |
| 2.01-3.0   | 237       | 25.27%  |
| 3.01-4.0   | 136       | 14.5%   |
| 4.01-8.0   | 130       | 13.86%  |
| 0.51-1.0   | 89        | 9.49%   |
| 8.01-16.0  | 32        | 3.41%   |
| 0.01-0.5   | 12        | 1.28%   |
| 16.01-24.0 | 3         | 0.32%   |
| 24.01-32.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 577       | 65.57%  |
| 2      | 264       | 30%     |
| 3      | 30        | 3.41%   |
| 4      | 4         | 0.45%   |
| 0      | 3         | 0.34%   |
| 6      | 2         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 639       | 73.53%  |
| Yes       | 230       | 26.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 707       | 81.36%  |
| No        | 162       | 18.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 859       | 99.19%  |
| No        | 7         | 0.81%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 750       | 85.91%  |
| No        | 123       | 14.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 155       | 17.78%  |
| Germany      | 76        | 8.72%   |
| India        | 49        | 5.62%   |
| UK           | 41        | 4.7%    |
| Canada       | 37        | 4.24%   |
| France       | 31        | 3.56%   |
| Brazil       | 24        | 2.75%   |
| Italy        | 23        | 2.64%   |
| Belgium      | 23        | 2.64%   |
| Turkey       | 22        | 2.52%   |
| Russia       | 20        | 2.29%   |
| Poland       | 20        | 2.29%   |
| Spain        | 18        | 2.06%   |
| Netherlands  | 17        | 1.95%   |
| Switzerland  | 15        | 1.72%   |
| Australia    | 15        | 1.72%   |
| Sweden       | 14        | 1.61%   |
| Hungary      | 13        | 1.49%   |
| Ukraine      | 12        | 1.38%   |
| Indonesia    | 12        | 1.38%   |
| Romania      | 11        | 1.26%   |
| Argentina    | 10        | 1.15%   |
| Greece       | 9         | 1.03%   |
| Norway       | 8         | 0.92%   |
| Bangladesh   | 8         | 0.92%   |
| Mexico       | 7         | 0.8%    |
| Finland      | 7         | 0.8%    |
| Egypt        | 7         | 0.8%    |
| South Africa | 6         | 0.69%   |
| Portugal     | 6         | 0.69%   |
| Estonia      | 6         | 0.69%   |
| Czechia      | 6         | 0.69%   |
| Colombia     | 6         | 0.69%   |
| China        | 6         | 0.69%   |
| Bulgaria     | 6         | 0.69%   |
| Malaysia     | 5         | 0.57%   |
| Latvia       | 5         | 0.57%   |
| Ireland      | 5         | 0.57%   |
| Chile        | 5         | 0.57%   |
| Vietnam      | 4         | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 8         | 0.88%   |
| Berlin            | 8         | 0.88%   |
| Moscow            | 7         | 0.77%   |
| Tallinn           | 6         | 0.66%   |
| Pune              | 6         | 0.66%   |
| Milan             | 6         | 0.66%   |
| Madrid            | 6         | 0.66%   |
| Frankfurt am Main | 6         | 0.66%   |
| Ankara            | 6         | 0.66%   |
| Sydney            | 5         | 0.55%   |
| Spokane           | 5         | 0.55%   |
| Kolkata           | 5         | 0.55%   |
| Houston           | 5         | 0.55%   |
| Budapest          | 5         | 0.55%   |
| Bergheim          | 5         | 0.55%   |
| Zurich            | 4         | 0.44%   |
| Warsaw            | 4         | 0.44%   |
| Stockholm         | 4         | 0.44%   |
| Seville           | 4         | 0.44%   |
| Mumbai            | 4         | 0.44%   |
| Izmir             | 4         | 0.44%   |
| Helsinki          | 4         | 0.44%   |
| Hamburg           | 4         | 0.44%   |
| Dhaka             | 4         | 0.44%   |
| Cairo             | 4         | 0.44%   |
| Bursa             | 4         | 0.44%   |
| Brooklyn          | 4         | 0.44%   |
| Bogotá           | 4         | 0.44%   |
| Bengaluru         | 4         | 0.44%   |
| Athens            | 4         | 0.44%   |
| Toronto           | 3         | 0.33%   |
| Thessaloniki      | 3         | 0.33%   |
| Tehran            | 3         | 0.33%   |
| Sofia             | 3         | 0.33%   |
| Singapore         | 3         | 0.33%   |
| Scottsdale        | 3         | 0.33%   |
| Sao Paulo         | 3         | 0.33%   |
| Sao Luis          | 3         | 0.33%   |
| Santiago          | 3         | 0.33%   |
| Rio de Janeiro    | 3         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 220       | 279    | 19.08%  |
| WDC                         | 153       | 193    | 13.27%  |
| Seagate                     | 130       | 146    | 11.27%  |
| Toshiba                     | 91        | 105    | 7.89%   |
| SanDisk                     | 63        | 78     | 5.46%   |
| SK hynix                    | 60        | 67     | 5.2%    |
| Kingston                    | 53        | 65     | 4.6%    |
| Intel                       | 40        | 50     | 3.47%   |
| Crucial                     | 39        | 49     | 3.38%   |
| Unknown                     | 27        | 41     | 2.34%   |
| Micron Technology           | 27        | 27     | 2.34%   |
| HGST                        | 27        | 33     | 2.34%   |
| Apple                       | 18        | 22     | 1.56%   |
| Hitachi                     | 17        | 18     | 1.47%   |
| KIOXIA                      | 16        | 19     | 1.39%   |
| A-DATA Technology           | 16        | 18     | 1.39%   |
| PNY                         | 11        | 13     | 0.95%   |
| LITEON                      | 11        | 13     | 0.95%   |
| SPCC                        | 7         | 7      | 0.61%   |
| Phison                      | 7         | 9      | 0.61%   |
| LITEONIT                    | 7         | 7      | 0.61%   |
| Kingston Technology Company | 7         | 10     | 0.61%   |
| JMicron Technology          | 7         | 7      | 0.61%   |
| Intenso                     | 6         | 7      | 0.52%   |
| China                       | 6         | 6      | 0.52%   |
| Phison Electronics          | 5         | 5      | 0.43%   |
| Micron/Crucial Technology   | 5         | 8      | 0.43%   |
| Mushkin                     | 4         | 4      | 0.35%   |
| Corsair                     | 4         | 4      | 0.35%   |
| Transcend                   | 3         | 3      | 0.26%   |
| Plextor                     | 3         | 3      | 0.26%   |
| Lenovo                      | 3         | 4      | 0.26%   |
| KingSpec                    | 3         | 3      | 0.26%   |
| Hewlett-Packard             | 3         | 4      | 0.26%   |
| Union Memory                | 2         | 2      | 0.17%   |
| Team                        | 2         | 2      | 0.17%   |
| SSSTC                       | 2         | 2      | 0.17%   |
| Silicon Motion              | 2         | 3      | 0.17%   |
| Realtek Semiconductor       | 2         | 2      | 0.17%   |
| Patriot                     | 2         | 5      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB                   | 36        | 2.99%   |
| Toshiba MQ01ABD100 1TB                             | 20        | 1.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 20        | 1.66%   |
| Toshiba MQ04ABF100 1TB                             | 18        | 1.5%    |
| Samsung SSD 860 EVO 500GB                          | 17        | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 16        | 1.33%   |
| Kingston SA400S37240G 240GB SSD                    | 11        | 0.91%   |
| Seagate ST1000LM049-2GH172 1TB                     | 8         | 0.67%   |
| Seagate ST1000LM048-2E7172 1TB                     | 8         | 0.67%   |
| Samsung SSD 970 EVO Plus 1TB                       | 8         | 0.67%   |
| Crucial CT1000MX500SSD1 1TB                        | 8         | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 7         | 0.58%   |
| Kingston SA400S37480G 480GB SSD                    | 7         | 0.58%   |
| HGST HTS721010A9E630 1TB                           | 7         | 0.58%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 6         | 0.5%    |
| Toshiba MQ01ABF050 500GB                           | 6         | 0.5%    |
| JMicron Generic 1TB                                | 6         | 0.5%    |
| Intel SSD 660P Series 512GB                        | 6         | 0.5%    |
| WDC WDS500G2B0B-00YS70 500GB SSD                   | 5         | 0.42%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 5         | 0.42%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 5         | 0.42%   |
| Seagate ST2000LM007-1R8174 2TB                     | 5         | 0.42%   |
| Seagate Expansion 4TB                              | 5         | 0.42%   |
| SanDisk SSD PLUS 480GB                             | 5         | 0.42%   |
| Samsung SSD 860 EVO 250GB                          | 5         | 0.42%   |
| Samsung SSD 860 EVO 1TB                            | 5         | 0.42%   |
| Samsung SSD 850 EVO 500GB                          | 5         | 0.42%   |
| Samsung SSD 850 EVO 250GB                          | 5         | 0.42%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 5         | 0.42%   |
| HGST HTS545050A7E680 500GB                         | 5         | 0.42%   |
| Crucial CT500MX500SSD1 500GB                       | 5         | 0.42%   |
| Apple SSD SM0256F 256GB                            | 5         | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 4         | 0.33%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 4         | 0.33%   |
| WDC WD10SPZX-08Z10 1TB                             | 4         | 0.33%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 4         | 0.33%   |
| Unknown SD/MMC/MS PRO 249GB                        | 4         | 0.33%   |
| Unknown MMC Card  64GB                             | 4         | 0.33%   |
| SK hynix HFM512GDJTNG-8310A 512GB                  | 4         | 0.33%   |
| Seagate ST9320325AS 320GB                          | 4         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 126       | 139    | 37.61%  |
| WDC                 | 79        | 101    | 23.58%  |
| Toshiba             | 64        | 73     | 19.1%   |
| HGST                | 27        | 33     | 8.06%   |
| Hitachi             | 17        | 18     | 5.07%   |
| JMicron Technology  | 6         | 6      | 1.79%   |
| Unknown             | 4         | 4      | 1.19%   |
| Samsung Electronics | 3         | 4      | 0.9%    |
| Apple               | 3         | 3      | 0.9%    |
| USB3.0              | 1         | 2      | 0.3%    |
| LaCie               | 1         | 1      | 0.3%    |
| KESU                | 1         | 1      | 0.3%    |
| Intenso             | 1         | 1      | 0.3%    |
| Hewlett-Packard     | 1         | 2      | 0.3%    |
| ASMT                | 1         | 1      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 106       | 141    | 25.42%  |
| SanDisk             | 44        | 50     | 10.55%  |
| Kingston            | 39        | 46     | 9.35%   |
| WDC                 | 37        | 48     | 8.87%   |
| Crucial             | 35        | 41     | 8.39%   |
| SK hynix            | 16        | 17     | 3.84%   |
| Apple               | 12        | 14     | 2.88%   |
| PNY                 | 11        | 13     | 2.64%   |
| Micron Technology   | 11        | 11     | 2.64%   |
| Intel               | 10        | 13     | 2.4%    |
| A-DATA Technology   | 10        | 12     | 2.4%    |
| Toshiba             | 9         | 11     | 2.16%   |
| LITEON              | 9         | 11     | 2.16%   |
| SPCC                | 7         | 7      | 1.68%   |
| LITEONIT            | 7         | 7      | 1.68%   |
| China               | 6         | 6      | 1.44%   |
| Intenso             | 5         | 6      | 1.2%    |
| Transcend           | 3         | 3      | 0.72%   |
| Seagate             | 3         | 4      | 0.72%   |
| Plextor             | 3         | 3      | 0.72%   |
| KingSpec            | 3         | 3      | 0.72%   |
| Team                | 2         | 2      | 0.48%   |
| Patriot             | 2         | 5      | 0.48%   |
| Mushkin             | 2         | 2      | 0.48%   |
| Lexar               | 2         | 2      | 0.48%   |
| Hewlett-Packard     | 2         | 2      | 0.48%   |
| GOODRAM             | 2         | 4      | 0.48%   |
| BIWIN               | 2         | 2      | 0.48%   |
| XrayDisk            | 1         | 1      | 0.24%   |
| W800S               | 1         | 2      | 0.24%   |
| Unknown             | 1         | 1      | 0.24%   |
| SSSTC               | 1         | 1      | 0.24%   |
| Pioneer             | 1         | 1      | 0.24%   |
| OCZ                 | 1         | 1      | 0.24%   |
| NGFF                | 1         | 1      | 0.24%   |
| Netac               | 1         | 1      | 0.24%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.24%   |
| Kingmax             | 1         | 3      | 0.24%   |
| KingFast            | 1         | 1      | 0.24%   |
| HS256E              | 1         | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 377       | 507    | 34.81%  |
| NVMe    | 348       | 454    | 32.13%  |
| HDD     | 327       | 389    | 30.19%  |
| MMC     | 24        | 38     | 2.22%   |
| Unknown | 7         | 8      | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 595       | 836    | 58.28%  |
| NVMe | 347       | 451    | 33.99%  |
| SAS  | 55        | 71     | 5.39%   |
| MMC  | 24        | 38     | 2.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 398       | 524    | 56.86%  |
| 0.51-1.0   | 266       | 322    | 38%     |
| 1.01-2.0   | 25        | 39     | 3.57%   |
| 3.01-4.0   | 6         | 6      | 0.86%   |
| 4.01-10.0  | 4         | 4      | 0.57%   |
| 10.01-20.0 | 1         | 1      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 240       | 26.73%  |
| 251-500        | 206       | 22.94%  |
| 501-1000       | 139       | 15.48%  |
| 1001-2000      | 94        | 10.47%  |
| More than 3000 | 54        | 6.01%   |
| Unknown        | 50        | 5.57%   |
| 51-100         | 49        | 5.46%   |
| 1-20           | 37        | 4.12%   |
| 21-50          | 15        | 1.67%   |
| 2001-3000      | 14        | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 261       | 28.06%  |
| 21-50          | 189       | 20.32%  |
| 101-250        | 150       | 16.13%  |
| 51-100         | 122       | 13.12%  |
| 251-500        | 70        | 7.53%   |
| 501-1000       | 55        | 5.91%   |
| Unknown        | 50        | 5.38%   |
| 1001-2000      | 17        | 1.83%   |
| More than 3000 | 14        | 1.51%   |
| 2001-3000      | 1         | 0.11%   |
| 0              | 1         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 9         | 9      | 7.14%   |
| Toshiba MQ01ABD100 1TB                   | 7         | 7      | 5.56%   |
| Seagate ST1000LM035-1RK172 970GB         | 7         | 7      | 5.56%   |
| Toshiba MQ01ABF050 500GB                 | 4         | 4      | 3.17%   |
| Seagate ST9320325AS 320GB                | 3         | 3      | 2.38%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 1.59%   |
| Seagate ST9250315AS 250GB                | 2         | 2      | 1.59%   |
| Seagate ST500LM021-1KJ152 500GB          | 2         | 2      | 1.59%   |
| Seagate ST1000LX015-1U7172 1TB           | 2         | 2      | 1.59%   |
| Seagate ST1000LM049-2GH172 1TB           | 2         | 2      | 1.59%   |
| Seagate ST1000LM014-1EJ164 1TB           | 2         | 2      | 1.59%   |
| SanDisk SSD PLUS 1000GB                  | 2         | 2      | 1.59%   |
| Hitachi HTS547575A9E384 752GB            | 2         | 2      | 1.59%   |
| HGST HTS725050A7E630 500GB               | 2         | 3      | 1.59%   |
| HGST HTS545050A7E680 500GB               | 2         | 2      | 1.59%   |
| HGST HTS545050A7E380 500GB               | 2         | 3      | 1.59%   |
| HGST HTS541075A9E680 752GB               | 2         | 2      | 1.59%   |
| HGST HTS541010A9E680 1TB                 | 2         | 3      | 1.59%   |
| WDC WD6400BEVT-60A0RT0 640GB             | 1         | 2      | 0.79%   |
| WDC WD5000LPCX-24C6HT0 500GB             | 1         | 1      | 0.79%   |
| WDC WD5000L 500GB                        | 1         | 1      | 0.79%   |
| WDC WD5000BPVT-22HXZT1 500GB             | 1         | 1      | 0.79%   |
| WDC WD5000BPKX-22HPJT0 500GB             | 1         | 1      | 0.79%   |
| WDC WD3200BPVT-00JJ5T0 320GB             | 1         | 1      | 0.79%   |
| WDC WD3200BEVT-22ZCT0 320GB              | 1         | 1      | 0.79%   |
| WDC WD3200BEKT-75PVMT0 320GB             | 1         | 1      | 0.79%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 1      | 0.79%   |
| WDC WD2500BEKT-60PVMT0 250GB             | 1         | 1      | 0.79%   |
| WDC WD10SPZX-24Z10T0 1TB                 | 1         | 1      | 0.79%   |
| WDC WD10SPZX-08Z10 1TB                   | 1         | 1      | 0.79%   |
| WDC WD10JPVT-75A1YT0 1TB                 | 1         | 1      | 0.79%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 1         | 1      | 0.79%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB     | 1         | 1      | 0.79%   |
| USB3.0 Super Speed 128GB                 | 1         | 2      | 0.79%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.79%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.79%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 2      | 0.79%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.79%   |
| Toshiba MK7575GSX 752GB                  | 1         | 1      | 0.79%   |
| Toshiba MK5065GSX 500GB                  | 1         | 1      | 0.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 37        | 39     | 29.6%   |
| Toshiba                   | 20        | 21     | 16%     |
| WDC                       | 15        | 16     | 12%     |
| HGST                      | 11        | 15     | 8.8%    |
| SK hynix                  | 5         | 5      | 4%      |
| Sandisk                   | 5         | 5      | 4%      |
| Intel                     | 5         | 6      | 4%      |
| Hitachi                   | 5         | 5      | 4%      |
| Samsung Electronics       | 3         | 3      | 2.4%    |
| Micron Technology         | 3         | 3      | 2.4%    |
| LITEONIT                  | 2         | 2      | 1.6%    |
| Kingston                  | 2         | 2      | 1.6%    |
| Crucial                   | 2         | 2      | 1.6%    |
| USB3.0                    | 1         | 2      | 0.8%    |
| SSSTC                     | 1         | 1      | 0.8%    |
| Plextor                   | 1         | 1      | 0.8%    |
| Mushkin                   | 1         | 1      | 0.8%    |
| Micron/Crucial Technology | 1         | 2      | 0.8%    |
| Lenovo                    | 1         | 1      | 0.8%    |
| LaCie                     | 1         | 1      | 0.8%    |
| Corsair                   | 1         | 1      | 0.8%    |
| Apple                     | 1         | 1      | 0.8%    |
| A-DATA Technology         | 1         | 1      | 0.8%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 37        | 39     | 42.05%  |
| Toshiba | 18        | 19     | 20.45%  |
| WDC     | 14        | 15     | 15.91%  |
| HGST    | 11        | 15     | 12.5%   |
| Hitachi | 5         | 5      | 5.68%   |
| USB3.0  | 1         | 2      | 1.14%   |
| LaCie   | 1         | 1      | 1.14%   |
| Apple   | 1         | 1      | 1.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 88        | 97     | 70.97%  |
| SSD  | 29        | 31     | 23.39%  |
| NVMe | 7         | 8      | 5.65%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB   | 1         | 1      | 25%     |
| Seagate ST9320325AS 320GB  | 1         | 1      | 25%     |
| HGST HTS721010A9E630 1TB   | 1         | 1      | 25%     |
| HGST HTS545050A7E680 500GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 679       | 1027   | 70.29%  |
| Detected | 161       | 229    | 16.67%  |
| Malfunc  | 122       | 136    | 12.63%  |
| Failed   | 4         | 4      | 0.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 613       | 56.39%  |
| Samsung Electronics            | 126       | 11.59%  |
| AMD                            | 109       | 10.03%  |
| SanDisk                        | 57        | 5.24%   |
| SK hynix                       | 44        | 4.05%   |
| KIOXIA                         | 21        | 1.93%   |
| Kingston Technology Company    | 21        | 1.93%   |
| Phison Electronics             | 18        | 1.66%   |
| Micron Technology              | 16        | 1.47%   |
| Toshiba America Info Systems   | 15        | 1.38%   |
| Micron/Crucial Technology      | 9         | 0.83%   |
| ADATA Technology               | 7         | 0.64%   |
| Silicon Motion                 | 5         | 0.46%   |
| Nvidia                         | 5         | 0.46%   |
| Union Memory (Shenzhen)        | 4         | 0.37%   |
| Lenovo                         | 3         | 0.28%   |
| Apple                          | 3         | 0.28%   |
| Realtek Semiconductor          | 2         | 0.18%   |
| Marvell Technology Group       | 2         | 0.18%   |
| Lite-On Technology             | 2         | 0.18%   |
| Solid State Storage Technology | 1         | 0.09%   |
| Shenzhen Longsys Electronics   | 1         | 0.09%   |
| Netac Technology               | 1         | 0.09%   |
| INNOGRIT                       | 1         | 0.09%   |
| ASMedia Technology             | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 105       | 9.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 103       | 9.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 70        | 6.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 61        | 5.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 54        | 4.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 47        | 4.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 44        | 3.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 33        | 2.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 28        | 2.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 27        | 2.4%    |
| Samsung NVMe SSD Controller 980                                                  | 24        | 2.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 24        | 2.14%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 23        | 2.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 21        | 1.87%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 18        | 1.6%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 16        | 1.42%   |
| Micron NVMe Storage Controller                                                   | 16        | 1.42%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 16        | 1.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 15        | 1.33%   |
| Intel SSD 660P Series                                                            | 15        | 1.33%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 14        | 1.25%   |
| Intel Tiger Lake-LP SATA Controller                                              | 14        | 1.25%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 1.16%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 13        | 1.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 12        | 1.07%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 12        | 1.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 1.07%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 11        | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                            | 11        | 0.98%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 9         | 0.8%    |
| Phison E12 NVMe Controller                                                       | 9         | 0.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8         | 0.71%   |
| SK hynix Non-Volatile memory controller                                          | 6         | 0.53%   |
| SK hynix BC511                                                                   | 6         | 0.53%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 0.53%   |
| Samsung Apple PCIe SSD                                                           | 6         | 0.53%   |
| Intel Non-Volatile memory controller                                             | 6         | 0.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 640       | 59.15%  |
| NVMe | 349       | 32.26%  |
| RAID | 76        | 7.02%   |
| IDE  | 17        | 1.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 705       | 81.41%  |
| AMD    | 161       | 18.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 23        | 2.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 23        | 2.66%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 23        | 2.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 21        | 2.42%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 20        | 2.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 16        | 1.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 14        | 1.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 1.39%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 1.39%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 1.39%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 12        | 1.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 1.27%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 11        | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 10        | 1.15%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 10        | 1.15%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 1.15%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 1.04%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 9         | 1.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 1.04%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 1.04%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 1.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.92%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 8         | 0.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 0.92%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 8         | 0.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 0.81%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.81%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 7         | 0.81%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 0.81%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 6         | 0.69%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 6         | 0.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 0.69%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 6         | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 0.69%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 6         | 0.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 0.69%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 6         | 0.69%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 6         | 0.69%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 6         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 259       | 29.91%  |
| Intel Core i5                  | 257       | 29.68%  |
| Intel Core i3                  | 56        | 6.47%   |
| AMD Ryzen 7                    | 49        | 5.66%   |
| Other                          | 48        | 5.54%   |
| AMD Ryzen 5                    | 45        | 5.2%    |
| Intel Celeron                  | 25        | 2.89%   |
| Intel Pentium                  | 20        | 2.31%   |
| Intel Core 2 Duo               | 18        | 2.08%   |
| AMD Ryzen 3                    | 13        | 1.5%    |
| AMD Ryzen 9                    | 8         | 0.92%   |
| AMD Ryzen 7 PRO                | 8         | 0.92%   |
| AMD A6                         | 8         | 0.92%   |
| Intel Atom                     | 6         | 0.69%   |
| AMD A12                        | 6         | 0.69%   |
| AMD A10                        | 5         | 0.58%   |
| Intel Pentium Silver           | 4         | 0.46%   |
| Intel Pentium Dual-Core        | 4         | 0.46%   |
| Intel Xeon                     | 3         | 0.35%   |
| Intel Core m3                  | 3         | 0.35%   |
| Intel Core i9                  | 3         | 0.35%   |
| AMD A8                         | 3         | 0.35%   |
| AMD A4                         | 3         | 0.35%   |
| Intel Core 2                   | 2         | 0.23%   |
| AMD Ryzen 5 PRO                | 2         | 0.23%   |
| Intel Pentium Dual             | 1         | 0.12%   |
| Intel Core m7                  | 1         | 0.12%   |
| Intel Core M                   | 1         | 0.12%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.12%   |
| AMD Turion II Dual-Core        | 1         | 0.12%   |
| AMD E2                         | 1         | 0.12%   |
| AMD E1                         | 1         | 0.12%   |
| AMD Athlon II                  | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 404       | 46.65%  |
| 4      | 294       | 33.95%  |
| 6      | 88        | 10.16%  |
| 8      | 70        | 8.08%   |
| 14     | 4         | 0.46%   |
| 1      | 3         | 0.35%   |
| 16     | 1         | 0.12%   |
| 12     | 1         | 0.12%   |
| 10     | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 866       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 743       | 85.8%   |
| 1      | 123       | 14.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 865       | 99.88%  |
| Unknown        | 1         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 159       | 17.93%  |
| 0x206a7    | 53        | 5.98%   |
| 0x906ea    | 49        | 5.52%   |
| 0x406e3    | 43        | 4.85%   |
| 0x806ea    | 41        | 4.62%   |
| 0x806e9    | 41        | 4.62%   |
| 0x306a9    | 37        | 4.17%   |
| 0x306c3    | 36        | 4.06%   |
| 0x40651    | 29        | 3.27%   |
| 0x306d4    | 26        | 2.93%   |
| 0x806ec    | 25        | 2.82%   |
| 0xa0652    | 23        | 2.59%   |
| 0x906e9    | 23        | 2.59%   |
| 0x806c1    | 22        | 2.48%   |
| 0x20655    | 22        | 2.48%   |
| 0x08600106 | 22        | 2.48%   |
| 0x08108102 | 16        | 1.8%    |
| 0x0a50000c | 15        | 1.69%   |
| 0x08108109 | 14        | 1.58%   |
| 0x08608103 | 13        | 1.47%   |
| 0x706e5    | 12        | 1.35%   |
| 0x806eb    | 10        | 1.13%   |
| 0x30678    | 10        | 1.13%   |
| 0x506e3    | 9         | 1.01%   |
| 0x1067a    | 9         | 1.01%   |
| 0x806d1    | 8         | 0.9%    |
| 0x706a8    | 8         | 0.9%    |
| 0x10676    | 7         | 0.79%   |
| 0x08600104 | 7         | 0.79%   |
| 0x08600103 | 7         | 0.79%   |
| 0x0810100b | 7         | 0.79%   |
| 0x06006705 | 7         | 0.79%   |
| 0x20652    | 6         | 0.68%   |
| 0x106e5    | 6         | 0.68%   |
| 0x0600611a | 5         | 0.56%   |
| 0x406c4    | 4         | 0.45%   |
| 0x40661    | 4         | 0.45%   |
| 0x0a50000b | 4         | 0.45%   |
| 0x06006704 | 4         | 0.45%   |
| 0x906ed    | 3         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 233       | 26.87%  |
| Haswell          | 80        | 9.23%   |
| SandyBridge      | 63        | 7.27%   |
| Skylake          | 61        | 7.04%   |
| IvyBridge        | 51        | 5.88%   |
| Zen 2            | 39        | 4.5%    |
| Zen+             | 35        | 4.04%   |
| Westmere         | 34        | 3.92%   |
| Broadwell        | 32        | 3.69%   |
| TigerLake        | 28        | 3.23%   |
| CometLake        | 26        | 3%      |
| Excavator        | 25        | 2.88%   |
| Zen 3            | 23        | 2.65%   |
| Silvermont       | 20        | 2.31%   |
| Unknown          | 20        | 2.31%   |
| Penryn           | 19        | 2.19%   |
| Icelake          | 19        | 2.19%   |
| Goldmont plus    | 12        | 1.38%   |
| Zen              | 10        | 1.15%   |
| Nehalem          | 6         | 0.69%   |
| Core             | 6         | 0.69%   |
| Alderlake Hybrid | 6         | 0.69%   |
| Puma             | 3         | 0.35%   |
| Piledriver       | 3         | 0.35%   |
| Goldmont         | 3         | 0.35%   |
| Bonnell          | 3         | 0.35%   |
| Tremont          | 2         | 0.23%   |
| K10              | 2         | 0.23%   |
| Jaguar           | 2         | 0.23%   |
| K8 & K10 hybrid  | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 654       | 55.71%  |
| Nvidia | 319       | 27.17%  |
| AMD    | 201       | 17.12%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 57        | 4.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 55        | 4.59%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 48        | 4.01%   |
| Intel UHD Graphics 620                                                                   | 46        | 3.84%   |
| Intel HD Graphics 620                                                                    | 45        | 3.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 44        | 3.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 36        | 3.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 2.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 2.84%   |
| AMD Renoir                                                                               | 34        | 2.84%   |
| Intel HD Graphics 5500                                                                   | 28        | 2.34%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 2.26%   |
| Intel HD Graphics 630                                                                    | 25        | 2.09%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 25        | 2.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 2.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 1.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 20        | 1.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 18        | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 1.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 18        | 1.5%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 17        | 1.42%   |
| AMD Lucienne                                                                             | 17        | 1.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 14        | 1.17%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 1.09%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 1%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 1%      |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 11        | 0.92%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 11        | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 11        | 0.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 0.92%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 11        | 0.92%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 0.84%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 9         | 0.75%   |
| Intel HD Graphics 530                                                                    | 9         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 0.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 0.67%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 373       | 42.97%  |
| Intel + Nvidia | 238       | 27.42%  |
| 1 x AMD        | 118       | 13.59%  |
| 1 x Nvidia     | 52        | 5.99%   |
| Intel + AMD    | 40        | 4.61%   |
| AMD + Nvidia   | 28        | 3.23%   |
| 2 x AMD        | 15        | 1.73%   |
| 2 x Intel      | 3         | 0.35%   |
| 2 x Nvidia     | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 688       | 78.72%  |
| Proprietary | 177       | 20.25%  |
| Unknown     | 9         | 1.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 592       | 67.35%  |
| 0.01-0.5   | 92        | 10.47%  |
| 1.01-2.0   | 81        | 9.22%   |
| 0.51-1.0   | 43        | 4.89%   |
| 3.01-4.0   | 35        | 3.98%   |
| 5.01-6.0   | 22        | 2.5%    |
| 7.01-8.0   | 7         | 0.8%    |
| 8.01-16.0  | 4         | 0.46%   |
| 2.01-3.0   | 3         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 177       | 17.15%  |
| AU Optronics            | 170       | 16.47%  |
| Chimei Innolux          | 142       | 13.76%  |
| BOE                     | 142       | 13.76%  |
| Samsung Electronics     | 80        | 7.75%   |
| Sharp                   | 33        | 3.2%    |
| Dell                    | 33        | 3.2%    |
| Goldstar                | 27        | 2.62%   |
| Apple                   | 26        | 2.52%   |
| Lenovo                  | 21        | 2.03%   |
| PANDA                   | 19        | 1.84%   |
| Chi Mei Optoelectronics | 15        | 1.45%   |
| Hewlett-Packard         | 13        | 1.26%   |
| BenQ                    | 13        | 1.26%   |
| Acer                    | 11        | 1.07%   |
| CSO                     | 9         | 0.87%   |
| AOC                     | 9         | 0.87%   |
| Philips                 | 8         | 0.78%   |
| Sony                    | 6         | 0.58%   |
| Panasonic               | 6         | 0.58%   |
| InfoVision              | 6         | 0.58%   |
| Ancor Communications    | 5         | 0.48%   |
| ASUSTek Computer        | 4         | 0.39%   |
| ViewSonic               | 3         | 0.29%   |
| Sceptre Tech            | 3         | 0.29%   |
| Iiyama                  | 3         | 0.29%   |
| Eizo                    | 3         | 0.29%   |
| Medion                  | 2         | 0.19%   |
| LG Philips              | 2         | 0.19%   |
| InnoLux Display         | 2         | 0.19%   |
| HannStar                | 2         | 0.19%   |
| Fujitsu Siemens         | 2         | 0.19%   |
| CPT                     | 2         | 0.19%   |
| Unknown                 | 2         | 0.19%   |
| WST                     | 1         | 0.1%    |
| Westinghouse            | 1         | 0.1%    |
| VIE                     | 1         | 0.1%    |
| Unknown                 | 1         | 0.1%    |
| Toshiba                 | 1         | 0.1%    |
| TMX                     | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 13        | 1.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 12        | 1.16%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.77%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 7         | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.68%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 7         | 0.68%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 6         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.58%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 6         | 0.58%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 6         | 0.58%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 6         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 5         | 0.48%   |
| Panasonic VVY13F001G10 MEI96A2 1920x1080 344x193mm 15.5-inch          | 5         | 0.48%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.48%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 0.48%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 0.48%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 5         | 0.48%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 5         | 0.48%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 5         | 0.48%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 4         | 0.39%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 0.39%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 4         | 0.39%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 4         | 0.39%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 4         | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 4         | 0.39%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch | 3         | 0.29%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SDCA029 2560x1440 294x165mm 13.3-inch | 3         | 0.29%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.29%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 3         | 0.29%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 3         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 483       | 51%     |
| 1366x768 (WXGA)    | 227       | 23.97%  |
| 1600x900 (HD+)     | 46        | 4.86%   |
| 3840x2160 (4K)     | 36        | 3.8%    |
| 2560x1440 (QHD)    | 26        | 2.75%   |
| 1280x800 (WXGA)    | 23        | 2.43%   |
| 1440x900 (WXGA+)   | 14        | 1.48%   |
| 2880x1800          | 13        | 1.37%   |
| 1920x1200 (WUXGA)  | 11        | 1.16%   |
| 2560x1600          | 10        | 1.06%   |
| 2560x1080          | 8         | 0.84%   |
| 2160x1440          | 8         | 0.84%   |
| 1280x1024 (SXGA)   | 7         | 0.74%   |
| 3840x2400          | 6         | 0.63%   |
| 3200x1800 (QHD+)   | 6         | 0.63%   |
| 1680x1050 (WSXGA+) | 5         | 0.53%   |
| 3440x1440          | 3         | 0.32%   |
| 1360x768           | 3         | 0.32%   |
| 1920x540           | 2         | 0.21%   |
| 1024x600           | 2         | 0.21%   |
| 7280x1440          | 1         | 0.11%   |
| 3840x1600          | 1         | 0.11%   |
| 3840x1100          | 1         | 0.11%   |
| 3200x2000          | 1         | 0.11%   |
| 3000x2000          | 1         | 0.11%   |
| 2160x1350          | 1         | 0.11%   |
| 1024x768 (XGA)     | 1         | 0.11%   |
| Unknown            | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 423       | 41.23%  |
| 14      | 139       | 13.55%  |
| 13      | 124       | 12.09%  |
| 17      | 89        | 8.67%   |
| 24      | 42        | 4.09%   |
| 27      | 33        | 3.22%   |
| 12      | 32        | 3.12%   |
| 23      | 31        | 3.02%   |
| 21      | 24        | 2.34%   |
| 34      | 10        | 0.97%   |
| Unknown | 10        | 0.97%   |
| 16      | 8         | 0.78%   |
| 11      | 8         | 0.78%   |
| 31      | 7         | 0.68%   |
| 18      | 7         | 0.68%   |
| 19      | 6         | 0.58%   |
| 22      | 5         | 0.49%   |
| 32      | 4         | 0.39%   |
| 84      | 3         | 0.29%   |
| 54      | 3         | 0.29%   |
| 10      | 3         | 0.29%   |
| 40      | 2         | 0.19%   |
| 26      | 2         | 0.19%   |
| 72      | 1         | 0.1%    |
| 52      | 1         | 0.1%    |
| 49      | 1         | 0.1%    |
| 48      | 1         | 0.1%    |
| 47      | 1         | 0.1%    |
| 39      | 1         | 0.1%    |
| 37      | 1         | 0.1%    |
| 35      | 1         | 0.1%    |
| 28      | 1         | 0.1%    |
| 25      | 1         | 0.1%    |
| 20      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 620       | 61.02%  |
| 201-300     | 107       | 10.53%  |
| 501-600     | 103       | 10.14%  |
| 351-400     | 97        | 9.55%   |
| 401-500     | 40        | 3.94%   |
| 701-800     | 14        | 1.38%   |
| Unknown     | 10        | 0.98%   |
| 601-700     | 9         | 0.89%   |
| 1001-1500   | 7         | 0.69%   |
| 801-900     | 5         | 0.49%   |
| 1501-2000   | 4         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 766       | 85.87%  |
| 16/10   | 83        | 9.3%    |
| 3/2     | 14        | 1.57%   |
| 21/9    | 12        | 1.35%   |
| Unknown | 7         | 0.78%   |
| 5/4     | 4         | 0.45%   |
| 4/3     | 3         | 0.34%   |
| 6/5     | 2         | 0.22%   |
| 3.40    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 419       | 40.88%  |
| 81-90          | 214       | 20.88%  |
| 201-250        | 89        | 8.68%   |
| 121-130        | 82        | 8%      |
| 71-80          | 49        | 4.78%   |
| 301-350        | 35        | 3.41%   |
| 61-70          | 28        | 2.73%   |
| 351-500        | 24        | 2.34%   |
| 251-300        | 11        | 1.07%   |
| More than 1000 | 10        | 0.98%   |
| 51-60          | 10        | 0.98%   |
| 141-150        | 10        | 0.98%   |
| Unknown        | 10        | 0.98%   |
| 151-200        | 9         | 0.88%   |
| 91-100         | 8         | 0.78%   |
| 131-140        | 6         | 0.59%   |
| 111-120        | 5         | 0.49%   |
| 501-1000       | 4         | 0.39%   |
| 41-50          | 2         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 473       | 46.88%  |
| 101-120       | 260       | 25.77%  |
| 51-100        | 151       | 14.97%  |
| 161-240       | 72        | 7.14%   |
| More than 240 | 34        | 3.37%   |
| Unknown       | 10        | 0.99%   |
| 1-50          | 9         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 693       | 78.57%  |
| 2     | 161       | 18.25%  |
| 3     | 17        | 1.93%   |
| 0     | 11        | 1.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 505       | 37.44%  |
| Realtek Semiconductor             | 475       | 35.21%  |
| Qualcomm Atheros                  | 193       | 14.31%  |
| Broadcom                          | 59        | 4.37%   |
| MediaTek                          | 15        | 1.11%   |
| Broadcom Limited                  | 14        | 1.04%   |
| TP-Link                           | 9         | 0.67%   |
| Sierra Wireless                   | 8         | 0.59%   |
| Dell                              | 8         | 0.59%   |
| Marvell Technology Group          | 6         | 0.44%   |
| Ralink                            | 5         | 0.37%   |
| Ericsson Business Mobile Networks | 5         | 0.37%   |
| ASIX Electronics                  | 5         | 0.37%   |
| Samsung Electronics               | 4         | 0.3%    |
| Nvidia                            | 4         | 0.3%    |
| Lenovo                            | 4         | 0.3%    |
| Hewlett-Packard                   | 4         | 0.3%    |
| Ralink Technology                 | 3         | 0.22%   |
| Fibocom                           | 3         | 0.22%   |
| NetGear                           | 2         | 0.15%   |
| JMicron Technology                | 2         | 0.15%   |
| Huawei Technologies               | 2         | 0.15%   |
| DisplayLink                       | 2         | 0.15%   |
| Xiaomi                            | 1         | 0.07%   |
| U-Blox                            | 1         | 0.07%   |
| ROCCAT                            | 1         | 0.07%   |
| Qualcomm Atheros Communications   | 1         | 0.07%   |
| Qualcomm                          | 1         | 0.07%   |
| Novatel Wireless                  | 1         | 0.07%   |
| Motorola PCS                      | 1         | 0.07%   |
| Microsoft                         | 1         | 0.07%   |
| Google                            | 1         | 0.07%   |
| ASUSTek Computer                  | 1         | 0.07%   |
| Apple                             | 1         | 0.07%   |
| Android                           | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 335       | 20.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 60        | 3.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 59        | 3.58%   |
| Intel Wi-Fi 6 AX200                                               | 59        | 3.58%   |
| Intel Wireless 8265 / 8275                                        | 51        | 3.1%    |
| Intel Wireless 7260                                               | 39        | 2.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 39        | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 36        | 2.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 2%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 33        | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 1.94%   |
| Intel Wireless 8260                                               | 29        | 1.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 27        | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 25        | 1.52%   |
| Intel Wireless 7265                                               | 24        | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 22        | 1.34%   |
| Intel Wi-Fi 6 AX201                                               | 21        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 17        | 1.03%   |
| Intel Wireless 3165                                               | 17        | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 15        | 0.91%   |
| Intel Centrino Ultimate-N 6300                                    | 15        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.85%   |
| Intel Wireless 3160                                               | 13        | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 13        | 0.79%   |
| Intel Wireless-AC 9260                                            | 12        | 0.73%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 11        | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 0.67%   |
| Intel Centrino Advanced-N 6200                                    | 11        | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 10        | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 10        | 0.61%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.61%   |
| Intel Centrino Advanced-N 6235                                    | 10        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 491       | 54.98%  |
| Qualcomm Atheros                | 162       | 18.14%  |
| Realtek Semiconductor           | 136       | 15.23%  |
| Broadcom                        | 43        | 4.82%   |
| MediaTek                        | 15        | 1.68%   |
| Broadcom Limited                | 11        | 1.23%   |
| Sierra Wireless                 | 7         | 0.78%   |
| TP-Link                         | 6         | 0.67%   |
| Ralink                          | 5         | 0.56%   |
| Dell                            | 4         | 0.45%   |
| Ralink Technology               | 3         | 0.34%   |
| FIBOCOM                         | 3         | 0.34%   |
| NetGear                         | 2         | 0.22%   |
| Hewlett-Packard                 | 2         | 0.22%   |
| Qualcomm Atheros Communications | 1         | 0.11%   |
| Microsoft                       | 1         | 0.11%   |
| ASUSTek Computer                | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 59        | 6.59%   |
| Intel Wi-Fi 6 AX200                                            | 59        | 6.59%   |
| Intel Wireless 8265 / 8275                                     | 51        | 5.7%    |
| Intel Wireless 7260                                            | 39        | 4.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 39        | 4.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 36        | 4.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 33        | 3.69%   |
| Intel Wireless 8260                                            | 29        | 3.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 28        | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 27        | 3.02%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 25        | 2.79%   |
| Intel Wireless 7265                                            | 24        | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 22        | 2.46%   |
| Intel Wi-Fi 6 AX201                                            | 21        | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 17        | 1.9%    |
| Intel Wireless 3165                                            | 17        | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 15        | 1.68%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 1.56%   |
| Intel Wireless 3160                                            | 13        | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 1.45%   |
| Intel Wireless-AC 9260                                         | 12        | 1.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 11        | 1.23%   |
| Intel Centrino Advanced-N 6200                                 | 11        | 1.23%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 10        | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 10        | 1.12%   |
| Intel Centrino Advanced-N 6235                                 | 10        | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 1.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 9         | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8         | 0.89%   |
| Intel Centrino Wireless-N 2230                                 | 8         | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 7         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 7         | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 0.67%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 6         | 0.67%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 6         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 432       | 60%     |
| Intel                    | 174       | 24.17%  |
| Qualcomm Atheros         | 52        | 7.22%   |
| Broadcom                 | 25        | 3.47%   |
| Marvell Technology Group | 6         | 0.83%   |
| ASIX Electronics         | 5         | 0.69%   |
| Nvidia                   | 4         | 0.56%   |
| TP-Link                  | 3         | 0.42%   |
| Lenovo                   | 3         | 0.42%   |
| Broadcom Limited         | 3         | 0.42%   |
| JMicron Technology       | 2         | 0.28%   |
| DisplayLink              | 2         | 0.28%   |
| Xiaomi                   | 1         | 0.14%   |
| Sierra Wireless          | 1         | 0.14%   |
| Samsung Electronics      | 1         | 0.14%   |
| Qualcomm                 | 1         | 0.14%   |
| Novatel Wireless         | 1         | 0.14%   |
| Motorola PCS             | 1         | 0.14%   |
| MediaTek                 | 1         | 0.14%   |
| Google                   | 1         | 0.14%   |
| Apple                    | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 335       | 45.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 60        | 8.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 4.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 4.37%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 2.46%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 1.91%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 1.78%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 1.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 1.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 1.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 1.5%    |
| Intel Ethernet Connection (4) I219-V                              | 10        | 1.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.96%   |
| Intel Ethernet Connection I219-V                                  | 6         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.55%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.55%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.55%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 3         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.41%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 3         | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.41%   |
| Intel Ethernet Connection (10) I219-LM                            | 3         | 0.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 860       | 54.29%  |
| Ethernet | 704       | 44.44%  |
| Modem    | 18        | 1.14%   |
| Unknown  | 2         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 734       | 80.13%  |
| Ethernet | 182       | 19.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 652       | 75.2%   |
| 1     | 197       | 22.72%  |
| 3     | 12        | 1.38%   |
| 0     | 6         | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 681       | 77.47%  |
| Yes  | 198       | 22.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 398       | 52.86%  |
| Realtek Semiconductor           | 85        | 11.29%  |
| Qualcomm Atheros Communications | 72        | 9.56%   |
| IMC Networks                    | 43        | 5.71%   |
| Lite-On Technology              | 35        | 4.65%   |
| Broadcom                        | 34        | 4.52%   |
| Apple                           | 25        | 3.32%   |
| Foxconn / Hon Hai               | 24        | 3.19%   |
| Dell                            | 9         | 1.2%    |
| Cambridge Silicon Radio         | 6         | 0.8%    |
| Toshiba                         | 5         | 0.66%   |
| ASUSTek Computer                | 5         | 0.66%   |
| Realtek                         | 4         | 0.53%   |
| Hewlett-Packard                 | 2         | 0.27%   |
| Ralink Technology               | 1         | 0.13%   |
| Ralink                          | 1         | 0.13%   |
| Opticis                         | 1         | 0.13%   |
| MediaTek                        | 1         | 0.13%   |
| Dynex                           | 1         | 0.13%   |
| Chicony Electronics             | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 169       | 22.44%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 65        | 8.63%   |
| Intel AX201 Bluetooth                                                               | 59        | 7.84%   |
| Intel AX200 Bluetooth                                                               | 57        | 7.57%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 56        | 7.44%   |
| Realtek Bluetooth Radio                                                             | 47        | 6.24%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 24        | 3.19%   |
| Apple Bluetooth Host Controller                                                     | 18        | 2.39%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 17        | 2.26%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 17        | 2.26%   |
| IMC Networks Bluetooth Device                                                       | 15        | 1.99%   |
| IMC Networks Bluetooth Radio                                                        | 14        | 1.86%   |
| Lite-On Bluetooth Device                                                            | 13        | 1.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 1.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 12        | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 1.06%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 8         | 1.06%   |
| Realtek RTL8821A Bluetooth                                                          | 7         | 0.93%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 0.93%   |
| Apple Bluetooth USB Host Controller                                                 | 7         | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 6         | 0.8%    |
| IMC Networks Wireless_Device                                                        | 6         | 0.8%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 6         | 0.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 0.8%    |
| Intel Bluetooth Device                                                              | 5         | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 0.66%   |
| Realtek 802.11ac WLAN Adapter                                                       | 4         | 0.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.53%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 3         | 0.4%    |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.4%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 3         | 0.4%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.4%    |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.4%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.4%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 3         | 0.4%    |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.4%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.4%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 697       | 62.12%  |
| Nvidia                   | 191       | 17.02%  |
| AMD                      | 171       | 15.24%  |
| Logitech                 | 8         | 0.71%   |
| C-Media Electronics      | 6         | 0.53%   |
| Realtek Semiconductor    | 5         | 0.45%   |
| Lenovo                   | 4         | 0.36%   |
| Kingston Technology      | 3         | 0.27%   |
| GN Netcom                | 3         | 0.27%   |
| Generalplus Technology   | 3         | 0.27%   |
| BEHRINGER International  | 3         | 0.27%   |
| Samson Technologies      | 2         | 0.18%   |
| Focusrite-Novation       | 2         | 0.18%   |
| Corsair                  | 2         | 0.18%   |
| VIA Technologies         | 1         | 0.09%   |
| Texas Instruments        | 1         | 0.09%   |
| SteelSeries ApS          | 1         | 0.09%   |
| Sony                     | 1         | 0.09%   |
| Samsung Electronics      | 1         | 0.09%   |
| Razer USA                | 1         | 0.09%   |
| Plantronics              | 1         | 0.09%   |
| Nordic Semiconductor ASA | 1         | 0.09%   |
| No brand                 | 1         | 0.09%   |
| Microchip Technology     | 1         | 0.09%   |
| Mark of the Unicorn      | 1         | 0.09%   |
| LG Electronics           | 1         | 0.09%   |
| JMTek                    | 1         | 0.09%   |
| Hewlett-Packard          | 1         | 0.09%   |
| Global Sun Technology    | 1         | 0.09%   |
| Fujitsu                  | 1         | 0.09%   |
| FDUCE PRO AUDIO MADE     | 1         | 0.09%   |
| DSEA A/S                 | 1         | 0.09%   |
| Dell                     | 1         | 0.09%   |
| BR25                     | 1         | 0.09%   |
| Barco Display Systems    | 1         | 0.09%   |
| Asahi Kasei Microsystems | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 146       | 10.72%  |
| AMD Family 17h/19h HD Audio Controller                                     | 122       | 8.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 64        | 4.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 58        | 4.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 58        | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 56        | 4.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 45        | 3.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 40        | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 40        | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 35        | 2.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 34        | 2.5%    |
| Intel 8 Series HD Audio Controller                                         | 34        | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 32        | 2.35%   |
| Intel Broadwell-U Audio Controller                                         | 32        | 2.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 28        | 2.06%   |
| Intel CM238 HD Audio Controller                                            | 28        | 2.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 26        | 1.91%   |
| Intel Comet Lake PCH cAVS                                                  | 26        | 1.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 26        | 1.91%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 25        | 1.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 24        | 1.76%   |
| Nvidia GP107GL High Definition Audio Controller                            | 23        | 1.69%   |
| Intel Comet Lake PCH-LP cAVS                                               | 19        | 1.4%    |
| AMD Kabini HDMI/DP Audio                                                   | 16        | 1.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 14        | 1.03%   |
| AMD High Definition Audio Controller                                       | 14        | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                              | 12        | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 12        | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 12        | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 11        | 0.81%   |
| Nvidia GA106 High Definition Audio Controller                              | 11        | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 11        | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 10        | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10        | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                              | 9         | 0.66%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 0.59%   |
| AMD FCH Azalia Controller                                                  | 8         | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                              | 7         | 0.51%   |
| Nvidia GT216 HDMI Audio Controller                                         | 6         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 291       | 30.83%  |
| SK hynix            | 219       | 23.2%   |
| Micron Technology   | 127       | 13.45%  |
| Kingston            | 80        | 8.47%   |
| Crucial             | 51        | 5.4%    |
| Unknown             | 39        | 4.13%   |
| Ramaxel Technology  | 21        | 2.22%   |
| Nanya Technology    | 13        | 1.38%   |
| Elpida              | 13        | 1.38%   |
| A-DATA Technology   | 13        | 1.38%   |
| Corsair             | 8         | 0.85%   |
| Unknown (ABCD)      | 6         | 0.64%   |
| GOODRAM             | 6         | 0.64%   |
| Patriot             | 5         | 0.53%   |
| Apacer              | 5         | 0.53%   |
| Team                | 4         | 0.42%   |
| Avant               | 4         | 0.42%   |
| Transcend           | 3         | 0.32%   |
| Goldkey             | 3         | 0.32%   |
| G.Skill             | 3         | 0.32%   |
| ASint Technology    | 3         | 0.32%   |
| Unknown             | 3         | 0.32%   |
| Teikon              | 2         | 0.21%   |
| Silicon Power       | 2         | 0.21%   |
| PNY                 | 2         | 0.21%   |
| Neo Forza           | 2         | 0.21%   |
| CSX                 | 2         | 0.21%   |
| AMD                 | 2         | 0.21%   |
| Unknown (898F)      | 1         | 0.11%   |
| Unknown (0x8634)    | 1         | 0.11%   |
| Unknown (0x8319)    | 1         | 0.11%   |
| Unknown (09D5)      | 1         | 0.11%   |
| Timetec             | 1         | 0.11%   |
| Smart Brazil        | 1         | 0.11%   |
| Smart               | 1         | 0.11%   |
| Sesame              | 1         | 0.11%   |
| Saikano             | 1         | 0.11%   |
| EUDAR               | 1         | 0.11%   |
| DSL                 | 1         | 0.11%   |
| 48spaces            | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 20        | 1.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 18        | 1.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 18        | 1.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 17        | 1.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 1.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 1.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 1.29%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 1.29%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 12        | 1.19%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 12        | 1.19%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.09%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.99%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.99%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.89%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 8         | 0.79%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s         | 8         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.69%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 7         | 0.69%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.69%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 7         | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 6         | 0.6%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.6%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 6         | 0.6%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 6         | 0.6%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.6%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 6         | 0.6%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.6%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 5         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.5%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.5%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.5%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.5%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 422       | 54.1%   |
| DDR3    | 273       | 35%     |
| LPDDR3  | 30        | 3.85%   |
| LPDDR4  | 26        | 3.33%   |
| SDRAM   | 10        | 1.28%   |
| DDR2    | 10        | 1.28%   |
| DDR5    | 5         | 0.64%   |
| LPDDR5  | 2         | 0.26%   |
| Unknown | 2         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 719       | 91.24%  |
| Row Of Chips | 60        | 7.61%   |
| Chip         | 8         | 1.02%   |
| DIMM         | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 366       | 42.46%  |
| 4096  | 296       | 34.34%  |
| 16384 | 106       | 12.3%   |
| 2048  | 64        | 7.42%   |
| 32768 | 21        | 2.44%   |
| 1024  | 8         | 0.93%   |
| 64    | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 213       | 24.68%  |
| 1600    | 208       | 24.1%   |
| 3200    | 146       | 16.92%  |
| 2400    | 85        | 9.85%   |
| 2133    | 47        | 5.45%   |
| 1334    | 34        | 3.94%   |
| 1333    | 25        | 2.9%    |
| 3266    | 18        | 2.09%   |
| 1067    | 15        | 1.74%   |
| 1867    | 12        | 1.39%   |
| Unknown | 10        | 1.16%   |
| 4267    | 9         | 1.04%   |
| 4199    | 6         | 0.7%    |
| 667     | 6         | 0.7%    |
| 4800    | 5         | 0.58%   |
| 8400    | 4         | 0.46%   |
| 2048    | 3         | 0.35%   |
| 975     | 3         | 0.35%   |
| 800     | 3         | 0.35%   |
| 6400    | 2         | 0.23%   |
| 4266    | 2         | 0.23%   |
| 3733    | 1         | 0.12%   |
| 3000    | 1         | 0.12%   |
| 2933    | 1         | 0.12%   |
| 1776    | 1         | 0.12%   |
| 1639    | 1         | 0.12%   |
| 1066    | 1         | 0.12%   |
| 533     | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| MIIIW              | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| MIIIW MW Keyboard Air Mini  | 1         | 33.33%  |
| Canon G2000 series          | 1         | 33.33%  |
| Brother MFC-L3770CDW series | 1         | 33.33%  |

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
| Chicony Electronics                    | 217       | 27.26%  |
| IMC Networks                           | 105       | 13.19%  |
| Realtek Semiconductor                  | 72        | 9.05%   |
| Microdia                               | 64        | 8.04%   |
| Bison Electronics                      | 54        | 6.78%   |
| Sunplus Innovation Technology          | 43        | 5.4%    |
| Quanta                                 | 35        | 4.4%    |
| Cheng Uei Precision Industry (Foxlink) | 29        | 3.64%   |
| Acer                                   | 24        | 3.02%   |
| Syntek                                 | 22        | 2.76%   |
| Lite-On Technology                     | 21        | 2.64%   |
| Apple                                  | 20        | 2.51%   |
| Suyin                                  | 19        | 2.39%   |
| Logitech                               | 11        | 1.38%   |
| Lenovo                                 | 9         | 1.13%   |
| Silicon Motion                         | 8         | 1.01%   |
| Luxvisions Innotech Limited            | 7         | 0.88%   |
| Primax Electronics                     | 5         | 0.63%   |
| Samsung Electronics                    | 4         | 0.5%    |
| Alcor Micro                            | 4         | 0.5%    |
| Sonix Technology                       | 3         | 0.38%   |
| Ricoh                                  | 3         | 0.38%   |
| Importek                               | 3         | 0.38%   |
| Sunplus Technology                     | 2         | 0.25%   |
| icSpring                               | 2         | 0.25%   |
| Generalplus Technology                 | 2         | 0.25%   |
| WaveRider Communications               | 1         | 0.13%   |
| Microsoft                              | 1         | 0.13%   |
| Magic Control Technology               | 1         | 0.13%   |
| Intel                                  | 1         | 0.13%   |
| Creative Technology                    | 1         | 0.13%   |
| Asuscom Network                        | 1         | 0.13%   |
| ARC International                      | 1         | 0.13%   |
| Anker                                  | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 59        | 7.38%   |
| Microdia Integrated_Webcam_HD                       | 30        | 3.75%   |
| Realtek Integrated_Webcam_HD                        | 29        | 3.63%   |
| IMC Networks Integrated Camera                      | 29        | 3.63%   |
| Chicony HD WebCam                                   | 28        | 3.5%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 24        | 3%      |
| Sunplus Integrated_Webcam_HD                        | 15        | 1.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 15        | 1.88%   |
| Syntek Integrated Camera                            | 14        | 1.75%   |
| Lite-On Integrated Camera                           | 14        | 1.75%   |
| Bison Integrated Camera                             | 13        | 1.63%   |
| Chicony USB2.0 Camera                               | 11        | 1.38%   |
| Acer Integrated Camera                              | 11        | 1.38%   |
| Microdia Integrated Webcam                          | 9         | 1.13%   |
| Chicony HP TrueVision HD                            | 9         | 1.13%   |
| Quanta HD Webcam                                    | 8         | 1%      |
| Quanta HD User Facing                               | 8         | 1%      |
| Chicony USB2.0 VGA UVC WebCam                       | 8         | 1%      |
| Bison BisonCam,NB Pro                               | 8         | 1%      |
| Chicony TOSHIBA Web Camera - HD                     | 7         | 0.88%   |
| Bison HD Webcam                                     | 7         | 0.88%   |
| Apple Built-in iSight                               | 7         | 0.88%   |
| Microdia Laptop_Integrated_Webcam_HD                | 6         | 0.75%   |
| Lenovo Integrated Webcam [R5U877]                   | 6         | 0.75%   |
| IMC Networks Lenovo EasyCamera                      | 6         | 0.75%   |
| Chicony HP TrueVision HD Camera                     | 6         | 0.75%   |
| Chicony HP HD Webcam                                | 6         | 0.75%   |
| Chicony HP HD Camera                                | 6         | 0.75%   |
| Chicony HD User Facing                              | 6         | 0.75%   |
| Chicony EasyCamera                                  | 6         | 0.75%   |
| Bison EasyCamera                                    | 6         | 0.75%   |
| Apple FaceTime HD Camera                            | 6         | 0.75%   |
| Realtek Integrated Webcam HD                        | 5         | 0.63%   |
| Quanta HP TrueVision HD Camera                      | 5         | 0.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 5         | 0.63%   |
| IMC Networks VGA UVC WebCam                         | 5         | 0.63%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 5         | 0.63%   |
| Chicony Integrated Camera (1280x720@30)             | 5         | 0.63%   |
| Chicony HP Wide Vision HD Camera                    | 5         | 0.63%   |
| Chicony FJ Camera                                   | 5         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 68        | 43.87%  |
| Synaptics                  | 28        | 18.06%  |
| Shenzhen Goodix Technology | 23        | 14.84%  |
| Upek                       | 11        | 7.1%    |
| Elan Microelectronics      | 10        | 6.45%   |
| LighTuning Technology      | 8         | 5.16%   |
| AuthenTec                  | 6         | 3.87%   |
| STMicroelectronics         | 1         | 0.65%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 11.61%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 15        | 9.68%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 7.74%   |
| Shenzhen Goodix  FingerPrint Device                                        | 12        | 7.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 7.1%    |
| Validity Sensors Synaptics WBDI                                            | 8         | 5.16%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 4.52%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 4.52%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 4.52%   |
| Elan ELAN:Fingerprint                                                      | 7         | 4.52%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 3.87%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.87%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.23%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.58%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.58%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.29%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.29%   |
| Synaptics WBDI Device                                                      | 2         | 1.29%   |
| Synaptics  WBDI                                                            | 2         | 1.29%   |
| AuthenTec AES1600                                                          | 2         | 1.29%   |
| Validity Sensors VFS491                                                    | 1         | 0.65%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.65%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.65%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.65%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.65%   |
| Synaptics UWP WBDI                                                         | 1         | 0.65%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.65%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.65%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.65%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.65%   |
| AuthenTec AES2810                                                          | 1         | 0.65%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.65%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.65%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 29        | 43.28%  |
| Alcor Micro | 27        | 40.3%   |
| O2 Micro    | 5         | 7.46%   |
| Lenovo      | 4         | 5.97%   |
| Upek        | 2         | 2.99%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 40.3%   |
| Broadcom 5880                                                                | 8         | 11.94%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 10.45%  |
| Broadcom 58200                                                               | 7         | 10.45%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 8.96%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 5.97%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 5.97%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 2.99%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.49%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.49%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 562       | 63.5%   |
| 1     | 252       | 28.47%  |
| 2     | 67        | 7.57%   |
| 3     | 3         | 0.34%   |
| 4     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 155       | 39.74%  |
| Graphics card         | 89        | 22.82%  |
| Chipcard              | 67        | 17.18%  |
| Net/wireless          | 27        | 6.92%   |
| Camera                | 19        | 4.87%   |
| Multimedia controller | 18        | 4.62%   |
| Bluetooth             | 4         | 1.03%   |
| Net/ethernet          | 3         | 0.77%   |
| Network               | 2         | 0.51%   |
| Card reader           | 2         | 0.51%   |
| Wireless              | 1         | 0.26%   |
| Storage/nvme          | 1         | 0.26%   |
| Storage               | 1         | 0.26%   |
| Dvb card              | 1         | 0.26%   |

