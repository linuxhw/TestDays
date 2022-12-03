Fedora - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 7867

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion S7 15ACH6 82K8       | [4ab89a8ad2](https://linux-hardware.org/?probe=4ab89a8ad2) | Dec 01, 2022 |
| Dell          | Latitude E5450              | [305bf364f6](https://linux-hardware.org/?probe=305bf364f6) | Dec 01, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [de34f148b9](https://linux-hardware.org/?probe=de34f148b9) | Dec 01, 2022 |
| Dell          | Latitude E5450              | [2b934a729c](https://linux-hardware.org/?probe=2b934a729c) | Dec 01, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [0128a48982](https://linux-hardware.org/?probe=0128a48982) | Dec 01, 2022 |
| HP            | ProBook 440 G7              | [a54a325001](https://linux-hardware.org/?probe=a54a325001) | Dec 01, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [f0ee9f78bd](https://linux-hardware.org/?probe=f0ee9f78bd) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| HP            | EliteBook 8570w             | [a4ae0cdd6a](https://linux-hardware.org/?probe=a4ae0cdd6a) | Dec 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [2436f4cf5e](https://linux-hardware.org/?probe=2436f4cf5e) | Nov 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [2df1670891](https://linux-hardware.org/?probe=2df1670891) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Notebook                    | [afac08b852](https://linux-hardware.org/?probe=afac08b852) | Nov 30, 2022 |
| Dell          | Inspiron 3580               | [6bc2705d99](https://linux-hardware.org/?probe=6bc2705d99) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S01Q3K    | [9fd6308179](https://linux-hardware.org/?probe=9fd6308179) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [38c4009dba](https://linux-hardware.org/?probe=38c4009dba) | Nov 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4a49152177](https://linux-hardware.org/?probe=4a49152177) | Nov 29, 2022 |
| Acer          | Nitro AN515-58              | [6bb64e8108](https://linux-hardware.org/?probe=6bb64e8108) | Nov 29, 2022 |
| Acer          | Nitro AN515-51              | [ba6d4f20e7](https://linux-hardware.org/?probe=ba6d4f20e7) | Nov 29, 2022 |
| Lenovo        | ThinkPad E550 20DF004RGE    | [a06fd97ee3](https://linux-hardware.org/?probe=a06fd97ee3) | Nov 29, 2022 |
| ASUSTek       | X756UXK                     | [a8fde1c59a](https://linux-hardware.org/?probe=a8fde1c59a) | Nov 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9216162e85](https://linux-hardware.org/?probe=9216162e85) | Nov 29, 2022 |
| Dell          | Latitude D620               | [9f6317405c](https://linux-hardware.org/?probe=9f6317405c) | Nov 29, 2022 |
| Dell          | Inspiron 16 5625            | [50912d5fa9](https://linux-hardware.org/?probe=50912d5fa9) | Nov 29, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [bb023e130b](https://linux-hardware.org/?probe=bb023e130b) | Nov 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [fd821a4b54](https://linux-hardware.org/?probe=fd821a4b54) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [39e771bd92](https://linux-hardware.org/?probe=39e771bd92) | Nov 28, 2022 |
| Dell          | Latitude 7480               | [409c2f27c8](https://linux-hardware.org/?probe=409c2f27c8) | Nov 28, 2022 |
| Dell          | Inspiron 16 5625            | [22da2f8729](https://linux-hardware.org/?probe=22da2f8729) | Nov 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [e1495dc120](https://linux-hardware.org/?probe=e1495dc120) | Nov 28, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [901fa6e871](https://linux-hardware.org/?probe=901fa6e871) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [86f58e68b6](https://linux-hardware.org/?probe=86f58e68b6) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | [624e6b243c](https://linux-hardware.org/?probe=624e6b243c) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | [54e985a956](https://linux-hardware.org/?probe=54e985a956) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [68e68e1e01](https://linux-hardware.org/?probe=68e68e1e01) | Nov 28, 2022 |
| Acer          | Nitro AN517-54              | [a9b90b8910](https://linux-hardware.org/?probe=a9b90b8910) | Nov 27, 2022 |
| Unknown       | Unknown                     | [4f73de3788](https://linux-hardware.org/?probe=4f73de3788) | Nov 27, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [415a8f0d8b](https://linux-hardware.org/?probe=415a8f0d8b) | Nov 27, 2022 |
| Acer          | Nitro AN517-54              | [445583d2bb](https://linux-hardware.org/?probe=445583d2bb) | Nov 27, 2022 |
| HP            | Laptop 15-da1xxx            | [8c4cae32db](https://linux-hardware.org/?probe=8c4cae32db) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | [ab9e6cc193](https://linux-hardware.org/?probe=ab9e6cc193) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | [a4d6ce5fa1](https://linux-hardware.org/?probe=a4d6ce5fa1) | Nov 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [bdc1a14cd4](https://linux-hardware.org/?probe=bdc1a14cd4) | Nov 27, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [26083dd909](https://linux-hardware.org/?probe=26083dd909) | Nov 27, 2022 |
| ASUSTek       | N53Jf                       | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| AVITA         | NS14A6                      | [b9cc8fe757](https://linux-hardware.org/?probe=b9cc8fe757) | Nov 27, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [f91c391079](https://linux-hardware.org/?probe=f91c391079) | Nov 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [dc561bb107](https://linux-hardware.org/?probe=dc561bb107) | Nov 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [336d829333](https://linux-hardware.org/?probe=336d829333) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | [bda395e731](https://linux-hardware.org/?probe=bda395e731) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | [0138561b29](https://linux-hardware.org/?probe=0138561b29) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [74fcf5cb22](https://linux-hardware.org/?probe=74fcf5cb22) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a4dbfc0da9](https://linux-hardware.org/?probe=a4dbfc0da9) | Nov 26, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [15d49eb71a](https://linux-hardware.org/?probe=15d49eb71a) | Nov 26, 2022 |
| Apple         | MacBookPro15,2              | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| MSI           | Modern 14 B5M               | [bf3c55e13b](https://linux-hardware.org/?probe=bf3c55e13b) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ab6ce548bc](https://linux-hardware.org/?probe=ab6ce548bc) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [848b6ab7b3](https://linux-hardware.org/?probe=848b6ab7b3) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [c34893c661](https://linux-hardware.org/?probe=c34893c661) | Nov 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [83a97530e1](https://linux-hardware.org/?probe=83a97530e1) | Nov 26, 2022 |
| Google        | Glimmer                     | [8ad30368c9](https://linux-hardware.org/?probe=8ad30368c9) | Nov 26, 2022 |
| GPD           | G1621-02                    | [f0e9e8442c](https://linux-hardware.org/?probe=f0e9e8442c) | Nov 26, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [d845cbb51d](https://linux-hardware.org/?probe=d845cbb51d) | Nov 26, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [18130ae317](https://linux-hardware.org/?probe=18130ae317) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | [376fc86892](https://linux-hardware.org/?probe=376fc86892) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | [f46e1bc341](https://linux-hardware.org/?probe=f46e1bc341) | Nov 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [4261949a3e](https://linux-hardware.org/?probe=4261949a3e) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [8acafcf4ab](https://linux-hardware.org/?probe=8acafcf4ab) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [682993f58f](https://linux-hardware.org/?probe=682993f58f) | Nov 25, 2022 |
| HP            | Laptop 14-dq1xxx            | [1e6fa19cc3](https://linux-hardware.org/?probe=1e6fa19cc3) | Nov 25, 2022 |
| Acer          | Nitro AN515-54              | [9226b4c616](https://linux-hardware.org/?probe=9226b4c616) | Nov 24, 2022 |
| Dell          | XPS 13 9300                 | [43fe4ed852](https://linux-hardware.org/?probe=43fe4ed852) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [95f653bddb](https://linux-hardware.org/?probe=95f653bddb) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [a4a2b60b09](https://linux-hardware.org/?probe=a4a2b60b09) | Nov 24, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [10e706472c](https://linux-hardware.org/?probe=10e706472c) | Nov 24, 2022 |
| Dell          | Inspiron 5370               | [469b2c3fd4](https://linux-hardware.org/?probe=469b2c3fd4) | Nov 24, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [0f96032f10](https://linux-hardware.org/?probe=0f96032f10) | Nov 24, 2022 |
| Toshiba       | Satellite S55-A             | [5466c61736](https://linux-hardware.org/?probe=5466c61736) | Nov 24, 2022 |
| ASUSTek       | Q550LF                      | [713f7b2c74](https://linux-hardware.org/?probe=713f7b2c74) | Nov 24, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [1c65fff6e7](https://linux-hardware.org/?probe=1c65fff6e7) | Nov 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d84bc82678](https://linux-hardware.org/?probe=d84bc82678) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [5b18e83e0d](https://linux-hardware.org/?probe=5b18e83e0d) | Nov 23, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [57dfd88985](https://linux-hardware.org/?probe=57dfd88985) | Nov 23, 2022 |
| HP            | Laptop 15-da0xxx            | [fa989478ad](https://linux-hardware.org/?probe=fa989478ad) | Nov 23, 2022 |
| HP            | Laptop 15-dw3xxx            | [fbf991818d](https://linux-hardware.org/?probe=fbf991818d) | Nov 23, 2022 |
| Apple         | MacBookPro9,2               | [3e176f0c26](https://linux-hardware.org/?probe=3e176f0c26) | Nov 22, 2022 |
| Acer          | Extensa 4220                | [af778b2ec9](https://linux-hardware.org/?probe=af778b2ec9) | Nov 22, 2022 |
| Acer          | Extensa 4220                | [04187e0d6e](https://linux-hardware.org/?probe=04187e0d6e) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [923ccf8b76](https://linux-hardware.org/?probe=923ccf8b76) | Nov 22, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [8a773e7358](https://linux-hardware.org/?probe=8a773e7358) | Nov 22, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [d49ca08585](https://linux-hardware.org/?probe=d49ca08585) | Nov 22, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [d48ad61c01](https://linux-hardware.org/?probe=d48ad61c01) | Nov 22, 2022 |
| Acer          | Aspire A515-45              | [0dcdb72cd6](https://linux-hardware.org/?probe=0dcdb72cd6) | Nov 22, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [a5dcbbbacd](https://linux-hardware.org/?probe=a5dcbbbacd) | Nov 22, 2022 |
| Acer          | Predator PH315-55           | [f411f75743](https://linux-hardware.org/?probe=f411f75743) | Nov 22, 2022 |
| HP            | Laptop 15-da0xxx            | [aef0888523](https://linux-hardware.org/?probe=aef0888523) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [8c624c76fa](https://linux-hardware.org/?probe=8c624c76fa) | Nov 21, 2022 |
| Acer          | Aspire A315-51              | [bcff111ecd](https://linux-hardware.org/?probe=bcff111ecd) | Nov 21, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [bce41d01ae](https://linux-hardware.org/?probe=bce41d01ae) | Nov 21, 2022 |
| Dell          | Precision 5510              | [63c0b8aa0c](https://linux-hardware.org/?probe=63c0b8aa0c) | Nov 21, 2022 |
| HP            | Laptop 17-cn0xxx            | [3b9a05e385](https://linux-hardware.org/?probe=3b9a05e385) | Nov 21, 2022 |
| HP            | Laptop 17-cn0xxx            | [489ded27aa](https://linux-hardware.org/?probe=489ded27aa) | Nov 21, 2022 |
| ASUSTek       | X45C                        | [02a232c4ef](https://linux-hardware.org/?probe=02a232c4ef) | Nov 21, 2022 |
| Dell          | XPS 15 9510                 | [09e98d8c02](https://linux-hardware.org/?probe=09e98d8c02) | Nov 21, 2022 |
| Dell          | Latitude D620               | [d45ad40496](https://linux-hardware.org/?probe=d45ad40496) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| Dell          | Inspiron 3505               | [634f7d190d](https://linux-hardware.org/?probe=634f7d190d) | Nov 21, 2022 |
| HP            | Laptop 17-by0xxx            | [4d903aa73b](https://linux-hardware.org/?probe=4d903aa73b) | Nov 21, 2022 |
| HP            | ZBook 15 G4                 | [3378343bab](https://linux-hardware.org/?probe=3378343bab) | Nov 21, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [0e9d717db2](https://linux-hardware.org/?probe=0e9d717db2) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [aa4d9601ee](https://linux-hardware.org/?probe=aa4d9601ee) | Nov 21, 2022 |
| MSI           | Stealth GS66 12UGS          | [ca3d88f38d](https://linux-hardware.org/?probe=ca3d88f38d) | Nov 21, 2022 |
| Dell          | Latitude 7420               | [ca5319fd67](https://linux-hardware.org/?probe=ca5319fd67) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [5739045caa](https://linux-hardware.org/?probe=5739045caa) | Nov 20, 2022 |
| HUAWEI        | MACH-WX9                    | [32fa69ea64](https://linux-hardware.org/?probe=32fa69ea64) | Nov 20, 2022 |
| Dell          | XPS 13 7390                 | [9f6c38b4ee](https://linux-hardware.org/?probe=9f6c38b4ee) | Nov 20, 2022 |
| Acer          | Aspire A515-45              | [11e00d597d](https://linux-hardware.org/?probe=11e00d597d) | Nov 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [678cfec38b](https://linux-hardware.org/?probe=678cfec38b) | Nov 20, 2022 |
| MSI           | Katana GF76 11UD            | [1f47d7c31b](https://linux-hardware.org/?probe=1f47d7c31b) | Nov 20, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [ade5f58f0e](https://linux-hardware.org/?probe=ade5f58f0e) | Nov 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [58c63522a4](https://linux-hardware.org/?probe=58c63522a4) | Nov 20, 2022 |
| Lenovo        | ThinkPad T460 20FN004CMD    | [1b7140151d](https://linux-hardware.org/?probe=1b7140151d) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMS56K00    | [5ff1608320](https://linux-hardware.org/?probe=5ff1608320) | Nov 19, 2022 |
| Apple         | MacBookPro11,5              | [3b5c35b319](https://linux-hardware.org/?probe=3b5c35b319) | Nov 19, 2022 |
| HASEE Comp... | V1x0PNPx                    | [e75868724e](https://linux-hardware.org/?probe=e75868724e) | Nov 19, 2022 |
| Google        | Celes                       | [00ed0ea4b5](https://linux-hardware.org/?probe=00ed0ea4b5) | Nov 19, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [f5cbe0bfa2](https://linux-hardware.org/?probe=f5cbe0bfa2) | Nov 19, 2022 |
| Sony          | SVE15133CNB                 | [3d78ceb657](https://linux-hardware.org/?probe=3d78ceb657) | Nov 19, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [bed1f98f04](https://linux-hardware.org/?probe=bed1f98f04) | Nov 19, 2022 |
| HUAWEI        | CREM-WXX9                   | [f9b8181279](https://linux-hardware.org/?probe=f9b8181279) | Nov 19, 2022 |
| Google        | Lick                        | [6d8750d974](https://linux-hardware.org/?probe=6d8750d974) | Nov 19, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [87d8a1ee6b](https://linux-hardware.org/?probe=87d8a1ee6b) | Nov 19, 2022 |
| Acer          | Aspire E1-572G              | [36c1e37d05](https://linux-hardware.org/?probe=36c1e37d05) | Nov 18, 2022 |
| ASUSTek       | M80TA                       | [d2427d8942](https://linux-hardware.org/?probe=d2427d8942) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L6S3L400    | [ae98e93989](https://linux-hardware.org/?probe=ae98e93989) | Nov 18, 2022 |
| Lenovo        | Legion 5 82B5               | [907810c0ac](https://linux-hardware.org/?probe=907810c0ac) | Nov 18, 2022 |
| Google        | Careena                     | [81dd8e9906](https://linux-hardware.org/?probe=81dd8e9906) | Nov 18, 2022 |
| HP            | EliteBook 840 14 inch G9... | [b5d4ff63a5](https://linux-hardware.org/?probe=b5d4ff63a5) | Nov 18, 2022 |
| HP            | Laptop 15-ef1xxx            | [2e47c9c20f](https://linux-hardware.org/?probe=2e47c9c20f) | Nov 18, 2022 |
| Dell          | XPS 13 7390                 | [19d18ac52c](https://linux-hardware.org/?probe=19d18ac52c) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [33113bb27d](https://linux-hardware.org/?probe=33113bb27d) | Nov 17, 2022 |
| Exo           | Smart XS1                   | [d51bf05ac5](https://linux-hardware.org/?probe=d51bf05ac5) | Nov 17, 2022 |
| NEC Comput... | NEC VERSA M160              | [a49b4b95b9](https://linux-hardware.org/?probe=a49b4b95b9) | Nov 17, 2022 |
| Dell          | Latitude 5530               | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [61f6e057e6](https://linux-hardware.org/?probe=61f6e057e6) | Nov 17, 2022 |
| Acer          | Aspire A515-51              | [ee9d0faeef](https://linux-hardware.org/?probe=ee9d0faeef) | Nov 17, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [190c6d9cc7](https://linux-hardware.org/?probe=190c6d9cc7) | Nov 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [450e658685](https://linux-hardware.org/?probe=450e658685) | Nov 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [6f2f504425](https://linux-hardware.org/?probe=6f2f504425) | Nov 16, 2022 |
| Lenovo        | ThinkPad Edge 03192AG       | [48da1b11bc](https://linux-hardware.org/?probe=48da1b11bc) | Nov 16, 2022 |
| Apple         | MacBookPro11,5              | [62586ed7f9](https://linux-hardware.org/?probe=62586ed7f9) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8b2d48cd24](https://linux-hardware.org/?probe=8b2d48cd24) | Nov 16, 2022 |
| MSI           | Katana GF76 11UD            | [fec345f330](https://linux-hardware.org/?probe=fec345f330) | Nov 16, 2022 |
| Dell          | XPS 15 9570                 | [69b281a787](https://linux-hardware.org/?probe=69b281a787) | Nov 16, 2022 |
| GPD           | G1619-04                    | [c1e365fd5d](https://linux-hardware.org/?probe=c1e365fd5d) | Nov 16, 2022 |
| Acer          | Aspire V3-571               | [7aa6773734](https://linux-hardware.org/?probe=7aa6773734) | Nov 16, 2022 |
| Acer          | Aspire V3-571               | [d5c4a2f02e](https://linux-hardware.org/?probe=d5c4a2f02e) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | [03426a19e5](https://linux-hardware.org/?probe=03426a19e5) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e7343719c2](https://linux-hardware.org/?probe=e7343719c2) | Nov 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [5d11a28230](https://linux-hardware.org/?probe=5d11a28230) | Nov 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [94983688d2](https://linux-hardware.org/?probe=94983688d2) | Nov 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [bafff409d9](https://linux-hardware.org/?probe=bafff409d9) | Nov 16, 2022 |
| Acer          | Aspire E5-573G              | [6b14e6a41b](https://linux-hardware.org/?probe=6b14e6a41b) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [1104a26017](https://linux-hardware.org/?probe=1104a26017) | Nov 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [119f9da4af](https://linux-hardware.org/?probe=119f9da4af) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [4c05f821c1](https://linux-hardware.org/?probe=4c05f821c1) | Nov 16, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [76d056b728](https://linux-hardware.org/?probe=76d056b728) | Nov 15, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6af7c2ad85](https://linux-hardware.org/?probe=6af7c2ad85) | Nov 15, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [d2cf28fbb9](https://linux-hardware.org/?probe=d2cf28fbb9) | Nov 15, 2022 |
| Kraftway      | ACCORD                      | [7021cedadf](https://linux-hardware.org/?probe=7021cedadf) | Nov 15, 2022 |
| MSI           | PS63 Modern 8RC             | [699ea2cc17](https://linux-hardware.org/?probe=699ea2cc17) | Nov 15, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d6b19cfd9d](https://linux-hardware.org/?probe=d6b19cfd9d) | Nov 15, 2022 |
| HP            | Laptop 17-by0xxx            | [ecdad4661a](https://linux-hardware.org/?probe=ecdad4661a) | Nov 15, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [465bc481e2](https://linux-hardware.org/?probe=465bc481e2) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [c332019d7e](https://linux-hardware.org/?probe=c332019d7e) | Nov 14, 2022 |
| Lenovo        | ThinkPad L450 20DSS1GD00    | [b0ea02b16c](https://linux-hardware.org/?probe=b0ea02b16c) | Nov 13, 2022 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [09285b9428](https://linux-hardware.org/?probe=09285b9428) | Nov 13, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| Dell          | G3 3579                     | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Alienware     | Area-51m                    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| Acer          | Swift SF314-512             | [eb533b483e](https://linux-hardware.org/?probe=eb533b483e) | Nov 12, 2022 |
| Lenovo        | Yoga 2 13 20344             | [deb10be02b](https://linux-hardware.org/?probe=deb10be02b) | Nov 12, 2022 |
| Dell          | Latitude E6420              | [056daa7806](https://linux-hardware.org/?probe=056daa7806) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | [eb5ece0bb3](https://linux-hardware.org/?probe=eb5ece0bb3) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [adf09c8455](https://linux-hardware.org/?probe=adf09c8455) | Nov 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [270045ffa3](https://linux-hardware.org/?probe=270045ffa3) | Nov 11, 2022 |
| HP            | Laptop 15s-eq2xxx           | [b64a32327f](https://linux-hardware.org/?probe=b64a32327f) | Nov 11, 2022 |
| ASUSTek       | X550JD                      | [9c88cc6c32](https://linux-hardware.org/?probe=9c88cc6c32) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0e3e3c885a](https://linux-hardware.org/?probe=0e3e3c885a) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [68e5509696](https://linux-hardware.org/?probe=68e5509696) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2421b6c5a4](https://linux-hardware.org/?probe=2421b6c5a4) | Nov 11, 2022 |
| Apple         | MacBookPro9,2               | [695b0b0356](https://linux-hardware.org/?probe=695b0b0356) | Nov 11, 2022 |
| Dell          | XPS 15 9510                 | [2db7764d25](https://linux-hardware.org/?probe=2db7764d25) | Nov 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3bcdc36fff](https://linux-hardware.org/?probe=3bcdc36fff) | Nov 11, 2022 |
| Dell          | Latitude 7480               | [cd19ef7ab8](https://linux-hardware.org/?probe=cd19ef7ab8) | Nov 10, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [f927960881](https://linux-hardware.org/?probe=f927960881) | Nov 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [b995c794aa](https://linux-hardware.org/?probe=b995c794aa) | Nov 10, 2022 |
| Monster       | ABRA A5 V15.6               | [3bf45390cc](https://linux-hardware.org/?probe=3bf45390cc) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fc22f217b3](https://linux-hardware.org/?probe=fc22f217b3) | Nov 10, 2022 |
| Dell          | Latitude 7480               | [100bc3303a](https://linux-hardware.org/?probe=100bc3303a) | Nov 10, 2022 |
| Acer          | Nitro AN515-46              | [741209999d](https://linux-hardware.org/?probe=741209999d) | Nov 10, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [7973c1467f](https://linux-hardware.org/?probe=7973c1467f) | Nov 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [4e535c916f](https://linux-hardware.org/?probe=4e535c916f) | Nov 10, 2022 |
| ASUSTek       | N752VX                      | [a5b6d827b2](https://linux-hardware.org/?probe=a5b6d827b2) | Nov 10, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [7638b6abf6](https://linux-hardware.org/?probe=7638b6abf6) | Nov 09, 2022 |
| Dell          | XPS 13 9300                 | [af6fa726d1](https://linux-hardware.org/?probe=af6fa726d1) | Nov 09, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [4366631db8](https://linux-hardware.org/?probe=4366631db8) | Nov 09, 2022 |
| Lenovo        | ThinkPad P53 20QQS44Q00     | [29ddbee669](https://linux-hardware.org/?probe=29ddbee669) | Nov 09, 2022 |
| MSI           | GP76 Leopard 11UG           | [5bccf91e38](https://linux-hardware.org/?probe=5bccf91e38) | Nov 09, 2022 |
| GPD           | G1619-04                    | [cf4cb47a12](https://linux-hardware.org/?probe=cf4cb47a12) | Nov 09, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [4a6aec2eb8](https://linux-hardware.org/?probe=4a6aec2eb8) | Nov 09, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [17c345f111](https://linux-hardware.org/?probe=17c345f111) | Nov 09, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [a2e9b34d94](https://linux-hardware.org/?probe=a2e9b34d94) | Nov 09, 2022 |
| MSI           | Modern 15 A11MU             | [b10bd50d9c](https://linux-hardware.org/?probe=b10bd50d9c) | Nov 09, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Dell          | Vostro 3401                 | [0b1b8bf15d](https://linux-hardware.org/?probe=0b1b8bf15d) | Nov 09, 2022 |
| Lenovo        | Legion 7 16IAX7 82TD        | [d224ed7da8](https://linux-hardware.org/?probe=d224ed7da8) | Nov 09, 2022 |
| Acer          | Aspire A515-45              | [73c9a3d81e](https://linux-hardware.org/?probe=73c9a3d81e) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [423a8f624c](https://linux-hardware.org/?probe=423a8f624c) | Nov 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S24N00    | [0b17fc5246](https://linux-hardware.org/?probe=0b17fc5246) | Nov 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c62cbe8eb5](https://linux-hardware.org/?probe=c62cbe8eb5) | Nov 08, 2022 |
| Acer          | SW5-017                     | [d4ff3ee29e](https://linux-hardware.org/?probe=d4ff3ee29e) | Nov 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [1cca3aa247](https://linux-hardware.org/?probe=1cca3aa247) | Nov 08, 2022 |
| Dell          | Inspiron 3580               | [33b2dbfcc2](https://linux-hardware.org/?probe=33b2dbfcc2) | Nov 08, 2022 |
| Dell          | Inspiron 3580               | [265707c6a3](https://linux-hardware.org/?probe=265707c6a3) | Nov 08, 2022 |
| Eluktronic... | P670RE3                     | [d96ecdf7ab](https://linux-hardware.org/?probe=d96ecdf7ab) | Nov 08, 2022 |
| HP            | Notebook                    | [5cbade7533](https://linux-hardware.org/?probe=5cbade7533) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fc4fb9249e](https://linux-hardware.org/?probe=fc4fb9249e) | Nov 08, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [f0c2157642](https://linux-hardware.org/?probe=f0c2157642) | Nov 07, 2022 |
| Acer          | Aspire A315-41              | [df6426eef5](https://linux-hardware.org/?probe=df6426eef5) | Nov 07, 2022 |
| Acer          | Aspire A315-41              | [bae4adcff9](https://linux-hardware.org/?probe=bae4adcff9) | Nov 07, 2022 |
| Dell          | Latitude 3410               | [f6532fe0ee](https://linux-hardware.org/?probe=f6532fe0ee) | Nov 07, 2022 |
| Acer          | Aspire VN7-591G             | [541d3bfeca](https://linux-hardware.org/?probe=541d3bfeca) | Nov 07, 2022 |
| HP            | ProBook 430 G5              | [e362ce5bdf](https://linux-hardware.org/?probe=e362ce5bdf) | Nov 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3f207bc4c3](https://linux-hardware.org/?probe=3f207bc4c3) | Nov 07, 2022 |
| Dell          | G3 3579                     | [b793526167](https://linux-hardware.org/?probe=b793526167) | Nov 06, 2022 |
| ASUSTek       | FX503VD                     | [0373b83f63](https://linux-hardware.org/?probe=0373b83f63) | Nov 06, 2022 |
| HP            | Pavilion g6                 | [43eefaca07](https://linux-hardware.org/?probe=43eefaca07) | Nov 06, 2022 |
| Dell          | Inspiron 7720               | [38d24e4b4a](https://linux-hardware.org/?probe=38d24e4b4a) | Nov 06, 2022 |
| Toshiba       | Satellite C660              | [47ca2c5cb7](https://linux-hardware.org/?probe=47ca2c5cb7) | Nov 06, 2022 |
| Quanta        | TWS                         | [1ad872afcd](https://linux-hardware.org/?probe=1ad872afcd) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [af69f66287](https://linux-hardware.org/?probe=af69f66287) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [256002ea80](https://linux-hardware.org/?probe=256002ea80) | Nov 06, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [d9952c90a5](https://linux-hardware.org/?probe=d9952c90a5) | Nov 05, 2022 |
| Dell          | Inspiron 15 3510            | [fb8bc290d6](https://linux-hardware.org/?probe=fb8bc290d6) | Nov 05, 2022 |
| TUXEDO        | Stellaris Intel Gen4        | [2b4987c9e8](https://linux-hardware.org/?probe=2b4987c9e8) | Nov 05, 2022 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [84bf8d9578](https://linux-hardware.org/?probe=84bf8d9578) | Nov 05, 2022 |
| ASUSTek       | FX503VD                     | [f80b5eaa0b](https://linux-hardware.org/?probe=f80b5eaa0b) | Nov 05, 2022 |
| Lenovo        | G50-70 20351                | [e29a593971](https://linux-hardware.org/?probe=e29a593971) | Nov 05, 2022 |
| Dell          | Vostro 13 5310              | [c25e192969](https://linux-hardware.org/?probe=c25e192969) | Nov 05, 2022 |
| Timi          | RedmiBook 14 II             | [374be77f36](https://linux-hardware.org/?probe=374be77f36) | Nov 05, 2022 |
| Dell          | Inspiron 15 3510            | [f0f862d5c5](https://linux-hardware.org/?probe=f0f862d5c5) | Nov 05, 2022 |
| ASUSTek       | X750JN                      | [3c8b130af7](https://linux-hardware.org/?probe=3c8b130af7) | Nov 05, 2022 |
| Dell          | Latitude 5591               | [e0e1ffe014](https://linux-hardware.org/?probe=e0e1ffe014) | Nov 05, 2022 |
| Dell          | Latitude 5591               | [b649030512](https://linux-hardware.org/?probe=b649030512) | Nov 05, 2022 |
| Acer          | Aspire 4820T                | [300aa32e45](https://linux-hardware.org/?probe=300aa32e45) | Nov 04, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [a2905cad90](https://linux-hardware.org/?probe=a2905cad90) | Nov 04, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3cb1f34e2a](https://linux-hardware.org/?probe=3cb1f34e2a) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | [80dbecb998](https://linux-hardware.org/?probe=80dbecb998) | Nov 04, 2022 |
| MSI           | Bravo 15 B5DD               | [2c605465bb](https://linux-hardware.org/?probe=2c605465bb) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | [3614ee4149](https://linux-hardware.org/?probe=3614ee4149) | Nov 04, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [4e666fbb8f](https://linux-hardware.org/?probe=4e666fbb8f) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | [c58816cb3d](https://linux-hardware.org/?probe=c58816cb3d) | Nov 04, 2022 |
| Acer          | Aspire E5-575G              | [af85812864](https://linux-hardware.org/?probe=af85812864) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [9d1ba43c71](https://linux-hardware.org/?probe=9d1ba43c71) | Nov 04, 2022 |
| Packard Be... | EasyNote LX                 | [41070f6bfe](https://linux-hardware.org/?probe=41070f6bfe) | Nov 04, 2022 |
| Lenovo        | Unknown                     | [0825807141](https://linux-hardware.org/?probe=0825807141) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [dac055fa29](https://linux-hardware.org/?probe=dac055fa29) | Nov 04, 2022 |
| ASUSTek       | Unknown                     | [f1a58eaa87](https://linux-hardware.org/?probe=f1a58eaa87) | Nov 04, 2022 |
| SLIMBOOK      | Executive                   | [cff86cc921](https://linux-hardware.org/?probe=cff86cc921) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9af713ef6e](https://linux-hardware.org/?probe=9af713ef6e) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | [2a802edc5a](https://linux-hardware.org/?probe=2a802edc5a) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [d87e75abbf](https://linux-hardware.org/?probe=d87e75abbf) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dae32fcba7](https://linux-hardware.org/?probe=dae32fcba7) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | [80e1206b6d](https://linux-hardware.org/?probe=80e1206b6d) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| HP            | ZBook 15 G4                 | [775987aacb](https://linux-hardware.org/?probe=775987aacb) | Nov 04, 2022 |
| Alienware     | x17 R2                      | [2e25d30db1](https://linux-hardware.org/?probe=2e25d30db1) | Nov 04, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [a2d3502165](https://linux-hardware.org/?probe=a2d3502165) | Nov 04, 2022 |
| UNOWHY        | Y13G011S4EI                 | [da784a5c82](https://linux-hardware.org/?probe=da784a5c82) | Nov 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0c186f330b](https://linux-hardware.org/?probe=0c186f330b) | Nov 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [2d53ffb628](https://linux-hardware.org/?probe=2d53ffb628) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 14S           | [9fbf084c28](https://linux-hardware.org/?probe=9fbf084c28) | Nov 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [41e941e3ca](https://linux-hardware.org/?probe=41e941e3ca) | Nov 03, 2022 |
| HP            | EliteBook 850 G6            | [3480a7be5a](https://linux-hardware.org/?probe=3480a7be5a) | Nov 03, 2022 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [7a2dab8dde](https://linux-hardware.org/?probe=7a2dab8dde) | Nov 03, 2022 |
| Dell          | XPS 15 9520                 | [24eea2c3f7](https://linux-hardware.org/?probe=24eea2c3f7) | Nov 03, 2022 |
| Acer          | Predator G9-591             | [ca65bba88a](https://linux-hardware.org/?probe=ca65bba88a) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [18b0671002](https://linux-hardware.org/?probe=18b0671002) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | [a189602082](https://linux-hardware.org/?probe=a189602082) | Nov 03, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [98e419a04d](https://linux-hardware.org/?probe=98e419a04d) | Nov 03, 2022 |
| HUAWEI        | CREM-WXX9                   | [870d04c833](https://linux-hardware.org/?probe=870d04c833) | Nov 03, 2022 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | [984c379f69](https://linux-hardware.org/?probe=984c379f69) | Nov 03, 2022 |
| Toshiba       | Satellite S55-A             | [cfc6040185](https://linux-hardware.org/?probe=cfc6040185) | Nov 03, 2022 |
| Dell          | Latitude E6430              | [2b6012cc1d](https://linux-hardware.org/?probe=2b6012cc1d) | Nov 02, 2022 |
| MSI           | Katana GF76 12UE            | [4359d2a528](https://linux-hardware.org/?probe=4359d2a528) | Nov 02, 2022 |
| Dell          | Inspiron 7577               | [2a280dc7df](https://linux-hardware.org/?probe=2a280dc7df) | Nov 02, 2022 |
| Lenovo        | ThinkPad T61 6464A13        | [5f850cbab6](https://linux-hardware.org/?probe=5f850cbab6) | Nov 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [4fa32ec6af](https://linux-hardware.org/?probe=4fa32ec6af) | Nov 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2d931f9e99](https://linux-hardware.org/?probe=2d931f9e99) | Nov 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [335af8b89b](https://linux-hardware.org/?probe=335af8b89b) | Nov 02, 2022 |
| HP            | Pavilion g6                 | [22b32d9bac](https://linux-hardware.org/?probe=22b32d9bac) | Nov 02, 2022 |
| HUAWEI        | BOD-WXX9                    | [d4ac3a5f04](https://linux-hardware.org/?probe=d4ac3a5f04) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [aa6c06f2bb](https://linux-hardware.org/?probe=aa6c06f2bb) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [584db1dcb2](https://linux-hardware.org/?probe=584db1dcb2) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [7b51138a0b](https://linux-hardware.org/?probe=7b51138a0b) | Nov 02, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [d3beec5427](https://linux-hardware.org/?probe=d3beec5427) | Nov 02, 2022 |
| HP            | Pavilion g6                 | [24c2a01761](https://linux-hardware.org/?probe=24c2a01761) | Nov 02, 2022 |
| Dell          | Latitude 5591               | [bcd8aef9a0](https://linux-hardware.org/?probe=bcd8aef9a0) | Nov 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | [379443a5d6](https://linux-hardware.org/?probe=379443a5d6) | Nov 01, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | [5e099af04c](https://linux-hardware.org/?probe=5e099af04c) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [766e7fb0d0](https://linux-hardware.org/?probe=766e7fb0d0) | Nov 01, 2022 |
| GPD           | G1619-04                    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| Unknown       | Unknown                     | [9608724116](https://linux-hardware.org/?probe=9608724116) | Nov 01, 2022 |
| Dell          | Venue 8 Pro 5830            | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| Dell          | Latitude 3420               | [9c2b9ab298](https://linux-hardware.org/?probe=9c2b9ab298) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | [d63c5de91b](https://linux-hardware.org/?probe=d63c5de91b) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [1d24aac4ce](https://linux-hardware.org/?probe=1d24aac4ce) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [2eb32b1bb3](https://linux-hardware.org/?probe=2eb32b1bb3) | Nov 01, 2022 |
| HP            | ZBook 15 G2                 | [7254a9a2fc](https://linux-hardware.org/?probe=7254a9a2fc) | Nov 01, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [566d83485b](https://linux-hardware.org/?probe=566d83485b) | Oct 31, 2022 |
| HUAWEI        | BOHB-WAX9                   | [274a3383db](https://linux-hardware.org/?probe=274a3383db) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Samsung       | 800G5M/800G5W               | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | [46f1da66b6](https://linux-hardware.org/?probe=46f1da66b6) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | [1409a7f78d](https://linux-hardware.org/?probe=1409a7f78d) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| ASUSTek       | X541UVK                     | [15bdbbf952](https://linux-hardware.org/?probe=15bdbbf952) | Oct 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [e993af2670](https://linux-hardware.org/?probe=e993af2670) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Dell          | Precision M6700             | [aa4b5e4400](https://linux-hardware.org/?probe=aa4b5e4400) | Oct 31, 2022 |
| HP            | ENVY 17                     | [5b845d9ee3](https://linux-hardware.org/?probe=5b845d9ee3) | Oct 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [073ba962ff](https://linux-hardware.org/?probe=073ba962ff) | Oct 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [221710c9ea](https://linux-hardware.org/?probe=221710c9ea) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [002ab67e5e](https://linux-hardware.org/?probe=002ab67e5e) | Oct 31, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [76906648cb](https://linux-hardware.org/?probe=76906648cb) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [cf460716f9](https://linux-hardware.org/?probe=cf460716f9) | Oct 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| HP            | 15                          | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | ProBook 470 G5              | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c52b1fe5fa](https://linux-hardware.org/?probe=c52b1fe5fa) | Oct 30, 2022 |
| Dell          | Inspiron 7720               | [f1478df888](https://linux-hardware.org/?probe=f1478df888) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [df654ca0b1](https://linux-hardware.org/?probe=df654ca0b1) | Oct 30, 2022 |
| Dell          | Latitude 7490               | [95d0006efb](https://linux-hardware.org/?probe=95d0006efb) | Oct 30, 2022 |
| Dell          | Latitude E7450              | [32a6333f4b](https://linux-hardware.org/?probe=32a6333f4b) | Oct 30, 2022 |
| Aquarius      | Cmp NS765                   | [5e519edbee](https://linux-hardware.org/?probe=5e519edbee) | Oct 30, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [1925c8ce1f](https://linux-hardware.org/?probe=1925c8ce1f) | Oct 29, 2022 |
| Acer          | Predator PH315-53           | [b3dd383a83](https://linux-hardware.org/?probe=b3dd383a83) | Oct 29, 2022 |
| ASUSTek       | X453MA                      | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| Dell          | XPS 13 9300                 | [cc62dbe2f6](https://linux-hardware.org/?probe=cc62dbe2f6) | Oct 29, 2022 |
| Dell          | XPS 13 9300                 | [301aab9126](https://linux-hardware.org/?probe=301aab9126) | Oct 29, 2022 |
| ASUSTek       | Q550LF                      | [383c45edce](https://linux-hardware.org/?probe=383c45edce) | Oct 29, 2022 |
| Dell          | Latitude E7450              | [012cd7214b](https://linux-hardware.org/?probe=012cd7214b) | Oct 29, 2022 |
| Dell          | Latitude E7450              | [635a60671d](https://linux-hardware.org/?probe=635a60671d) | Oct 29, 2022 |
| HP            | ZBook 15 G3                 | [c60b429baa](https://linux-hardware.org/?probe=c60b429baa) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [2f6e4235f7](https://linux-hardware.org/?probe=2f6e4235f7) | Oct 28, 2022 |
| Lenovo        | ThinkPad P52 20M9S1EM00     | [40de74c5c5](https://linux-hardware.org/?probe=40de74c5c5) | Oct 28, 2022 |
| HP            | Laptop 15s-fq4xxx           | [e06398e1bc](https://linux-hardware.org/?probe=e06398e1bc) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [83179a6cea](https://linux-hardware.org/?probe=83179a6cea) | Oct 28, 2022 |
| Sony          | VPCCB3S1R                   | [ee5b1465a1](https://linux-hardware.org/?probe=ee5b1465a1) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1d64fb48e7](https://linux-hardware.org/?probe=1d64fb48e7) | Oct 27, 2022 |
| Timi          | TM1701                      | [f246345845](https://linux-hardware.org/?probe=f246345845) | Oct 27, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [0c6a68368c](https://linux-hardware.org/?probe=0c6a68368c) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | [3a9f97607d](https://linux-hardware.org/?probe=3a9f97607d) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | [36b663cec7](https://linux-hardware.org/?probe=36b663cec7) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | [e00fd51503](https://linux-hardware.org/?probe=e00fd51503) | Oct 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [670823778e](https://linux-hardware.org/?probe=670823778e) | Oct 27, 2022 |
| MSI           | Prestige 14 A10SC           | [263d47772c](https://linux-hardware.org/?probe=263d47772c) | Oct 27, 2022 |
| HP            | EliteBook 8570w             | [7d30f96368](https://linux-hardware.org/?probe=7d30f96368) | Oct 27, 2022 |
| Lenovo        | ThinkPad X260 20F5S2WX05    | [710f95eab8](https://linux-hardware.org/?probe=710f95eab8) | Oct 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [85b4bc70fa](https://linux-hardware.org/?probe=85b4bc70fa) | Oct 26, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| LincPlus      | P1                          | [cc97e9ec36](https://linux-hardware.org/?probe=cc97e9ec36) | Oct 26, 2022 |
| MSI           | Modern 15 A11M              | [0a658be9fc](https://linux-hardware.org/?probe=0a658be9fc) | Oct 26, 2022 |
| Dell          | Latitude E7270              | [7f2c8b9e9c](https://linux-hardware.org/?probe=7f2c8b9e9c) | Oct 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [a8c29545e6](https://linux-hardware.org/?probe=a8c29545e6) | Oct 25, 2022 |
| Dell          | Inspiron 3501               | [6764a6860f](https://linux-hardware.org/?probe=6764a6860f) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | [c9123810fd](https://linux-hardware.org/?probe=c9123810fd) | Oct 25, 2022 |
| Dell          | Latitude 5500               | [6e1b321740](https://linux-hardware.org/?probe=6e1b321740) | Oct 25, 2022 |
| Apple         | MacBookPro11,4              | [29dd6b053b](https://linux-hardware.org/?probe=29dd6b053b) | Oct 25, 2022 |
| Timi          | Mi Laptop Pro 15            | [4474edfd79](https://linux-hardware.org/?probe=4474edfd79) | Oct 25, 2022 |
| Dell          | XPS 15 9510                 | [b14c37f999](https://linux-hardware.org/?probe=b14c37f999) | Oct 25, 2022 |
| Dell          | Latitude E7450              | [45e65cd626](https://linux-hardware.org/?probe=45e65cd626) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| ASUSTek       | X540SA                      | [a515dd93cd](https://linux-hardware.org/?probe=a515dd93cd) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [42647c28ba](https://linux-hardware.org/?probe=42647c28ba) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [e4d7dc5f38](https://linux-hardware.org/?probe=e4d7dc5f38) | Oct 25, 2022 |
| System76      | Galago UltraPro             | [caf6a992bb](https://linux-hardware.org/?probe=caf6a992bb) | Oct 24, 2022 |
| Acer          | Aspire ES1-520              | [44375f0b06](https://linux-hardware.org/?probe=44375f0b06) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [95ad909dc8](https://linux-hardware.org/?probe=95ad909dc8) | Oct 24, 2022 |
| HP            | 340S G7 Notebook PC         | [dc8eab937b](https://linux-hardware.org/?probe=dc8eab937b) | Oct 24, 2022 |
| HUAWEI        | KPL-W0X                     | [aea737fcab](https://linux-hardware.org/?probe=aea737fcab) | Oct 24, 2022 |
| Dell          | Latitude E6420              | [eb53f0d580](https://linux-hardware.org/?probe=eb53f0d580) | Oct 24, 2022 |
| ASUSTek       | UX310UQ                     | [5a928ace3b](https://linux-hardware.org/?probe=5a928ace3b) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [c1a4fde481](https://linux-hardware.org/?probe=c1a4fde481) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [80bf151a4d](https://linux-hardware.org/?probe=80bf151a4d) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| Lenovo        | ThinkPad X240 20AMS56K00    | [efa84f3716](https://linux-hardware.org/?probe=efa84f3716) | Oct 24, 2022 |
| Acer          | Nitro AN515-46              | [cb2480b22c](https://linux-hardware.org/?probe=cb2480b22c) | Oct 23, 2022 |
| Acer          | Nitro AN515-46              | [846cfe5273](https://linux-hardware.org/?probe=846cfe5273) | Oct 23, 2022 |
| HP            | 340S G7 Notebook PC         | [406538a0de](https://linux-hardware.org/?probe=406538a0de) | Oct 23, 2022 |
| Dell          | Inspiron 3580               | [41dce71fbf](https://linux-hardware.org/?probe=41dce71fbf) | Oct 23, 2022 |
| Acer          | Aspire E5-575G              | [b6b5c1468c](https://linux-hardware.org/?probe=b6b5c1468c) | Oct 23, 2022 |
| Dell          | Inspiron 1564               | [754b4a0f04](https://linux-hardware.org/?probe=754b4a0f04) | Oct 23, 2022 |
| HP            | Notebook                    | [d713217453](https://linux-hardware.org/?probe=d713217453) | Oct 23, 2022 |
| HP            | Notebook                    | [ef9adb0e8a](https://linux-hardware.org/?probe=ef9adb0e8a) | Oct 22, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [14830504a7](https://linux-hardware.org/?probe=14830504a7) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KY00     | [657b1ee865](https://linux-hardware.org/?probe=657b1ee865) | Oct 22, 2022 |
| Lenovo        | ThinkPad X260 20F5S5Q200    | [c2e041fd54](https://linux-hardware.org/?probe=c2e041fd54) | Oct 21, 2022 |
| HP            | ProBook 4530s               | [3cca675c88](https://linux-hardware.org/?probe=3cca675c88) | Oct 21, 2022 |
| HP            | ProBook 4530s               | [e87546da82](https://linux-hardware.org/?probe=e87546da82) | Oct 21, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [41bade1339](https://linux-hardware.org/?probe=41bade1339) | Oct 21, 2022 |
| Purism        | Librem 13 v2                | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| LG Electro... | 16Z90P-G.AP75D              | [1e1526e9d8](https://linux-hardware.org/?probe=1e1526e9d8) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| Google        | Swanky                      | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| ASUSTek       | Q550LF                      | [0d24151944](https://linux-hardware.org/?probe=0d24151944) | Oct 21, 2022 |
| Itautec       | Infoway N8755               | [7eaba382a5](https://linux-hardware.org/?probe=7eaba382a5) | Oct 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [b374c2dff6](https://linux-hardware.org/?probe=b374c2dff6) | Oct 20, 2022 |
| Lenovo        | B560                        | [3a61700f49](https://linux-hardware.org/?probe=3a61700f49) | Oct 20, 2022 |
| Dell          | Inspiron 7460               | [879fabd350](https://linux-hardware.org/?probe=879fabd350) | Oct 20, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | [f966d5d584](https://linux-hardware.org/?probe=f966d5d584) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06328b7f7c](https://linux-hardware.org/?probe=06328b7f7c) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7d35a56915](https://linux-hardware.org/?probe=7d35a56915) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [f81a40a71c](https://linux-hardware.org/?probe=f81a40a71c) | Oct 20, 2022 |
| Dell          | Precision 5510              | [bb7788ce01](https://linux-hardware.org/?probe=bb7788ce01) | Oct 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9594fcc1e0](https://linux-hardware.org/?probe=9594fcc1e0) | Oct 20, 2022 |
| ASUSTek       | K43SJ                       | [4c27c4945c](https://linux-hardware.org/?probe=4c27c4945c) | Oct 20, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [d0dcb7e6e3](https://linux-hardware.org/?probe=d0dcb7e6e3) | Oct 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [866d0f49a2](https://linux-hardware.org/?probe=866d0f49a2) | Oct 20, 2022 |
| Framework     | Laptop                      | [ade55fca33](https://linux-hardware.org/?probe=ade55fca33) | Oct 19, 2022 |
| Framework     | Laptop                      | [57af01b405](https://linux-hardware.org/?probe=57af01b405) | Oct 19, 2022 |
| Dell          | Latitude 7420               | [332d2cd420](https://linux-hardware.org/?probe=332d2cd420) | Oct 19, 2022 |
| System76      | Kudu                        | [49c0e1c400](https://linux-hardware.org/?probe=49c0e1c400) | Oct 19, 2022 |
| Dell          | Precision 7760              | [a5ab2793ae](https://linux-hardware.org/?probe=a5ab2793ae) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [680823db07](https://linux-hardware.org/?probe=680823db07) | Oct 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [71734a9abe](https://linux-hardware.org/?probe=71734a9abe) | Oct 19, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [f91daeac73](https://linux-hardware.org/?probe=f91daeac73) | Oct 19, 2022 |
| HP            | EliteBook 865 16 inch G9... | [8665ee6ba6](https://linux-hardware.org/?probe=8665ee6ba6) | Oct 19, 2022 |
| Lenovo        | Yoga 900-13ISK2 80UE        | [efadc96c65](https://linux-hardware.org/?probe=efadc96c65) | Oct 19, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [eab0779b74](https://linux-hardware.org/?probe=eab0779b74) | Oct 19, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [28a1d15220](https://linux-hardware.org/?probe=28a1d15220) | Oct 18, 2022 |
| MSI           | Modern 14 C12M              | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [aaa41de825](https://linux-hardware.org/?probe=aaa41de825) | Oct 18, 2022 |
| Lenovo        | B560                        | [717af973da](https://linux-hardware.org/?probe=717af973da) | Oct 18, 2022 |
| Dell          | Precision 5510              | [d56d0aceaf](https://linux-hardware.org/?probe=d56d0aceaf) | Oct 18, 2022 |
| Dell          | Inspiron M5010              | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| Acer          | Aspire E1-531               | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [76f9929a9c](https://linux-hardware.org/?probe=76f9929a9c) | Oct 17, 2022 |
| MSI           | Summit E16Flip A11UCT       | [f1ec40e34d](https://linux-hardware.org/?probe=f1ec40e34d) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | [9e1f6ae49e](https://linux-hardware.org/?probe=9e1f6ae49e) | Oct 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7f9219a85f](https://linux-hardware.org/?probe=7f9219a85f) | Oct 17, 2022 |
| Dell          | Inspiron 3584               | [c80df2b63c](https://linux-hardware.org/?probe=c80df2b63c) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | [2fd734cbfb](https://linux-hardware.org/?probe=2fd734cbfb) | Oct 17, 2022 |
| Acer          | Aspire A717-71G             | [969c0ac771](https://linux-hardware.org/?probe=969c0ac771) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [528fc3c5ec](https://linux-hardware.org/?probe=528fc3c5ec) | Oct 17, 2022 |
| Dell          | Inspiron 5759               | [f93d1bc535](https://linux-hardware.org/?probe=f93d1bc535) | Oct 17, 2022 |
| Dell          | Inspiron 13 5320            | [9ac52708ad](https://linux-hardware.org/?probe=9ac52708ad) | Oct 17, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [678415db20](https://linux-hardware.org/?probe=678415db20) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| Notebook      | W230SS                      | [abb5e7fda8](https://linux-hardware.org/?probe=abb5e7fda8) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [f98ff2b890](https://linux-hardware.org/?probe=f98ff2b890) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [f20a72be72](https://linux-hardware.org/?probe=f20a72be72) | Oct 16, 2022 |
| HP            | ProBook 450 G7              | [6a9b93fdeb](https://linux-hardware.org/?probe=6a9b93fdeb) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [77c8619d03](https://linux-hardware.org/?probe=77c8619d03) | Oct 16, 2022 |
| Dell          | XPS 13 7390                 | [c78fae026e](https://linux-hardware.org/?probe=c78fae026e) | Oct 16, 2022 |
| Acer          | Aspire E1-531               | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0cceedcb07](https://linux-hardware.org/?probe=0cceedcb07) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [dce51f4ce7](https://linux-hardware.org/?probe=dce51f4ce7) | Oct 16, 2022 |
| Lenovo        | ThinkPad X230 23257BG       | [6c8a42718a](https://linux-hardware.org/?probe=6c8a42718a) | Oct 16, 2022 |
| Dell          | Vostro 3400                 | [156e3942e5](https://linux-hardware.org/?probe=156e3942e5) | Oct 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2a36feb313](https://linux-hardware.org/?probe=2a36feb313) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| Lenovo        | V145-15AST 81MT             | [d73a82b798](https://linux-hardware.org/?probe=d73a82b798) | Oct 15, 2022 |
| Timi          | TM1701                      | [c2b709ff0c](https://linux-hardware.org/?probe=c2b709ff0c) | Oct 15, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [478b58f9b6](https://linux-hardware.org/?probe=478b58f9b6) | Oct 15, 2022 |
| Dell          | Latitude E5450              | [68e2c17e2f](https://linux-hardware.org/?probe=68e2c17e2f) | Oct 15, 2022 |
| Acer          | Aspire A314-22              | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Apple         | MacBookPro12,1              | [7979753fa9](https://linux-hardware.org/?probe=7979753fa9) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [bf6d77aefd](https://linux-hardware.org/?probe=bf6d77aefd) | Oct 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ab212a80b4](https://linux-hardware.org/?probe=ab212a80b4) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e1bc46388d](https://linux-hardware.org/?probe=e1bc46388d) | Oct 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49821787e4](https://linux-hardware.org/?probe=49821787e4) | Oct 14, 2022 |
| Dell          | Vostro 3400                 | [f9c2c298c4](https://linux-hardware.org/?probe=f9c2c298c4) | Oct 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [dbd2328d0f](https://linux-hardware.org/?probe=dbd2328d0f) | Oct 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3a8bdfb3f5](https://linux-hardware.org/?probe=3a8bdfb3f5) | Oct 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f4d190e864](https://linux-hardware.org/?probe=f4d190e864) | Oct 13, 2022 |
| Dell          | XPS 13 7390                 | [60b21aed9a](https://linux-hardware.org/?probe=60b21aed9a) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9b0a923899](https://linux-hardware.org/?probe=9b0a923899) | Oct 13, 2022 |
| HP            | Laptop 15s-du3xxx           | [5985f3564a](https://linux-hardware.org/?probe=5985f3564a) | Oct 13, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | [38739fd54f](https://linux-hardware.org/?probe=38739fd54f) | Oct 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [7af879de72](https://linux-hardware.org/?probe=7af879de72) | Oct 13, 2022 |
| UNOWHY        | Y13G011S4EI                 | [2be4dc3fc2](https://linux-hardware.org/?probe=2be4dc3fc2) | Oct 13, 2022 |
| Gigabyte      | P65Q                        | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| Dell          | XPS 13 9310                 | [8437ac2ffc](https://linux-hardware.org/?probe=8437ac2ffc) | Oct 12, 2022 |
| Acer          | Aspire A715-71G             | [2b0752150c](https://linux-hardware.org/?probe=2b0752150c) | Oct 12, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| Apple         | MacBookPro15,2              | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [0355b3f7b8](https://linux-hardware.org/?probe=0355b3f7b8) | Oct 11, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [60b02deb7f](https://linux-hardware.org/?probe=60b02deb7f) | Oct 11, 2022 |
| Dell          | Vostro 5402                 | [11f3146366](https://linux-hardware.org/?probe=11f3146366) | Oct 11, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [71c926fc14](https://linux-hardware.org/?probe=71c926fc14) | Oct 11, 2022 |
| Lenovo        | ThinkPad P50 20EQS5MP00     | [83858a99c3](https://linux-hardware.org/?probe=83858a99c3) | Oct 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5caff1861e](https://linux-hardware.org/?probe=5caff1861e) | Oct 10, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [dc3347c309](https://linux-hardware.org/?probe=dc3347c309) | Oct 10, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| HUAWEI        | BOD-WXX9                    | [49fff6123f](https://linux-hardware.org/?probe=49fff6123f) | Oct 10, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [59f6b7653c](https://linux-hardware.org/?probe=59f6b7653c) | Oct 10, 2022 |
| HP            | EliteBook 840 G6            | [29f63f8a32](https://linux-hardware.org/?probe=29f63f8a32) | Oct 10, 2022 |
| Apple         | MacBookPro9,2               | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| Dell          | Inspiron 5570               | [cab829a52b](https://linux-hardware.org/?probe=cab829a52b) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [6c2f880759](https://linux-hardware.org/?probe=6c2f880759) | Oct 09, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | [52658eb393](https://linux-hardware.org/?probe=52658eb393) | Oct 09, 2022 |
| Dell          | XPS 13 9380                 | [5d882bd47f](https://linux-hardware.org/?probe=5d882bd47f) | Oct 09, 2022 |
| HP            | 255 G8 Notebook PC          | [6a56a66eae](https://linux-hardware.org/?probe=6a56a66eae) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| Framework     | Laptop                      | [3d25e7f96c](https://linux-hardware.org/?probe=3d25e7f96c) | Oct 09, 2022 |
| Toshiba       | Satellite C660              | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| Acer          | Predator PH315-53           | [cc8b98a2ff](https://linux-hardware.org/?probe=cc8b98a2ff) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c0c2e0ca69](https://linux-hardware.org/?probe=c0c2e0ca69) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | [615578d390](https://linux-hardware.org/?probe=615578d390) | Oct 08, 2022 |
| Lenovo        | ThinkPad L470 20J4CTO1WW    | [3aee91df8c](https://linux-hardware.org/?probe=3aee91df8c) | Oct 08, 2022 |
| Dell          | Vostro 3501                 | [126b7b85f2](https://linux-hardware.org/?probe=126b7b85f2) | Oct 08, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3d968cc61a](https://linux-hardware.org/?probe=3d968cc61a) | Oct 08, 2022 |
| Lenovo        | Legion S7 16IAH7 82TF       | [9836cb655c](https://linux-hardware.org/?probe=9836cb655c) | Oct 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [973605d3af](https://linux-hardware.org/?probe=973605d3af) | Oct 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [74f6e9db69](https://linux-hardware.org/?probe=74f6e9db69) | Oct 07, 2022 |
| Dell          | XPS 15 7590                 | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | ProBook 455 G7              | [26dfdb5aed](https://linux-hardware.org/?probe=26dfdb5aed) | Oct 07, 2022 |
| HP            | Laptop 14s-dr1xxx           | [00d04b6a56](https://linux-hardware.org/?probe=00d04b6a56) | Oct 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [d67006c592](https://linux-hardware.org/?probe=d67006c592) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [08e98e28c2](https://linux-hardware.org/?probe=08e98e28c2) | Oct 07, 2022 |
| HP            | EliteBook 745 G6            | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| Dell          | Latitude 5580               | [4bcae73c95](https://linux-hardware.org/?probe=4bcae73c95) | Oct 07, 2022 |
| Acer          | Nitro AN515-58              | [6a9f611fd5](https://linux-hardware.org/?probe=6a9f611fd5) | Oct 07, 2022 |
| Apple         | MacBookPro9,2               | [d5247cbbc3](https://linux-hardware.org/?probe=d5247cbbc3) | Oct 06, 2022 |
| Dell          | Latitude 5400               | [00789b23c6](https://linux-hardware.org/?probe=00789b23c6) | Oct 06, 2022 |
| HP            | EliteBook 840 14 inch G9... | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [c8c6a428db](https://linux-hardware.org/?probe=c8c6a428db) | Oct 06, 2022 |
| ASUSTek       | X550LA                      | [c0c98c2051](https://linux-hardware.org/?probe=c0c98c2051) | Oct 06, 2022 |
| HP            | 15                          | [9f0981ed52](https://linux-hardware.org/?probe=9f0981ed52) | Oct 06, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | [4fe1810c2c](https://linux-hardware.org/?probe=4fe1810c2c) | Oct 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5dbeb45ba5](https://linux-hardware.org/?probe=5dbeb45ba5) | Oct 06, 2022 |
| Acer          | Aspire E5-475G              | [a545cecc64](https://linux-hardware.org/?probe=a545cecc64) | Oct 05, 2022 |
| Acer          | Aspire E5-475G              | [06fa787cb1](https://linux-hardware.org/?probe=06fa787cb1) | Oct 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [f6fc1950ac](https://linux-hardware.org/?probe=f6fc1950ac) | Oct 05, 2022 |
| Dell          | Latitude 5400               | [14ed107028](https://linux-hardware.org/?probe=14ed107028) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d0d3494971](https://linux-hardware.org/?probe=d0d3494971) | Oct 05, 2022 |
| Apple         | MacBookPro9,2               | [77176ee82a](https://linux-hardware.org/?probe=77176ee82a) | Oct 05, 2022 |
| Dell          | XPS 17 9710                 | [7590ca8bff](https://linux-hardware.org/?probe=7590ca8bff) | Oct 05, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [ddb0e3fb81](https://linux-hardware.org/?probe=ddb0e3fb81) | Oct 05, 2022 |
| Dell          | XPS 15 9510                 | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Apple         | MacBookPro14,1              | [3d5136540e](https://linux-hardware.org/?probe=3d5136540e) | Oct 05, 2022 |
| HP            | Laptop 15s-eq3xxx           | [2bd986670e](https://linux-hardware.org/?probe=2bd986670e) | Oct 04, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [b78c69e096](https://linux-hardware.org/?probe=b78c69e096) | Oct 04, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [cb204abf9b](https://linux-hardware.org/?probe=cb204abf9b) | Oct 04, 2022 |
| Dell          | Inspiron 13 5310            | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| HP            | Laptop                      | [3a26ec874f](https://linux-hardware.org/?probe=3a26ec874f) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [4ba3e28201](https://linux-hardware.org/?probe=4ba3e28201) | Oct 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [923a579655](https://linux-hardware.org/?probe=923a579655) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [a9c2a1eca0](https://linux-hardware.org/?probe=a9c2a1eca0) | Oct 03, 2022 |
| Timi          | A35S                        | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| HP            | EliteBook 850 G1            | [7bb0235bd2](https://linux-hardware.org/?probe=7bb0235bd2) | Oct 03, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2f9e023d1e](https://linux-hardware.org/?probe=2f9e023d1e) | Oct 03, 2022 |
| Apple         | MacBookPro11,1              | [45a46cdb72](https://linux-hardware.org/?probe=45a46cdb72) | Oct 03, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [92aca0d081](https://linux-hardware.org/?probe=92aca0d081) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [8f24127ac0](https://linux-hardware.org/?probe=8f24127ac0) | Oct 02, 2022 |
| HP            | ProBook 470 G5              | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [80a2948ff1](https://linux-hardware.org/?probe=80a2948ff1) | Oct 02, 2022 |
| Dell          | Inspiron 3543               | [9e5ab25f54](https://linux-hardware.org/?probe=9e5ab25f54) | Oct 02, 2022 |
| Dell          | Inspiron 17-7779            | [5bd534e938](https://linux-hardware.org/?probe=5bd534e938) | Oct 02, 2022 |
| MICROMAX      | Canvas Lapbook L1161        | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | [49bd2b0248](https://linux-hardware.org/?probe=49bd2b0248) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d5407763a0](https://linux-hardware.org/?probe=d5407763a0) | Sep 30, 2022 |
| Dell          | Latitude E4300              | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| GPD           | G1621-02                    | [6ae9fc596e](https://linux-hardware.org/?probe=6ae9fc596e) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| HP            | ProBook 6570b               | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | [b15bae8e77](https://linux-hardware.org/?probe=b15bae8e77) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | [126b8dd3ec](https://linux-hardware.org/?probe=126b8dd3ec) | Sep 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | [33353fc67c](https://linux-hardware.org/?probe=33353fc67c) | Sep 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS09L0... | [7c384e5578](https://linux-hardware.org/?probe=7c384e5578) | Sep 30, 2022 |
| SK hynix      | HyBook                      | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| A-DATA Tec... | XENIA 14                    | [251f390772](https://linux-hardware.org/?probe=251f390772) | Sep 30, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [d2a3575975](https://linux-hardware.org/?probe=d2a3575975) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2c6b161d0f](https://linux-hardware.org/?probe=2c6b161d0f) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [18afdc2116](https://linux-hardware.org/?probe=18afdc2116) | Sep 29, 2022 |
| Dell          | Latitude 7430               | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| HP            | ProBook 440 G7              | [99f729e814](https://linux-hardware.org/?probe=99f729e814) | Sep 29, 2022 |
| A-DATA Tec... | XENIA 14                    | [e819e5dc14](https://linux-hardware.org/?probe=e819e5dc14) | Sep 29, 2022 |
| Fujitsu       | LIFEBOOK P771               | [7325511d27](https://linux-hardware.org/?probe=7325511d27) | Sep 29, 2022 |
| ASUSTek       | X555LA                      | [5ec700ea0a](https://linux-hardware.org/?probe=5ec700ea0a) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| HP            | ZBook 15 G3                 | [1d612b997a](https://linux-hardware.org/?probe=1d612b997a) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| HP            | 15 Notebook PC              | [23c809d2a7](https://linux-hardware.org/?probe=23c809d2a7) | Sep 29, 2022 |
| Dell          | Precision 7550              | [75f2949521](https://linux-hardware.org/?probe=75f2949521) | Sep 29, 2022 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [9ac63cdce6](https://linux-hardware.org/?probe=9ac63cdce6) | Sep 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [d137298cb5](https://linux-hardware.org/?probe=d137298cb5) | Sep 28, 2022 |
| Dell          | Inspiron 5447               | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [84187f87ed](https://linux-hardware.org/?probe=84187f87ed) | Sep 28, 2022 |
| Medion        | Unknown                     | [821c3c8fed](https://linux-hardware.org/?probe=821c3c8fed) | Sep 28, 2022 |
| Alienware     | 14                          | [2d46ecc50e](https://linux-hardware.org/?probe=2d46ecc50e) | Sep 28, 2022 |
| ASUSTek       | X550CL                      | [ded047597e](https://linux-hardware.org/?probe=ded047597e) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Chuwi         | HeroBook Air                | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| MSI           | GS66 Stealth 10SGS          | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| HONOR         | HGE-WX6                     | [5c61df4d20](https://linux-hardware.org/?probe=5c61df4d20) | Sep 27, 2022 |
| Timi          | A35S                        | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6677830ce4](https://linux-hardware.org/?probe=6677830ce4) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [3d86bcf1b7](https://linux-hardware.org/?probe=3d86bcf1b7) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| HP            | ProBook 450 G4              | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [7c62f5131f](https://linux-hardware.org/?probe=7c62f5131f) | Sep 27, 2022 |
| MSI           | GT72 6QE                    | [5535b3367e](https://linux-hardware.org/?probe=5535b3367e) | Sep 26, 2022 |
| Acer          | Aspire E1-570G              | [ed657bfbb6](https://linux-hardware.org/?probe=ed657bfbb6) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [f1d78ca455](https://linux-hardware.org/?probe=f1d78ca455) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| MSI           | GT72 6QE                    | [d739812ce7](https://linux-hardware.org/?probe=d739812ce7) | Sep 26, 2022 |
| MSI           | GT72S 6QE                   | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| HP            | Laptop                      | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | [64fd780b2f](https://linux-hardware.org/?probe=64fd780b2f) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | [d557cdbe1c](https://linux-hardware.org/?probe=d557cdbe1c) | Sep 26, 2022 |
| HP            | Laptop                      | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [01cf3c6f99](https://linux-hardware.org/?probe=01cf3c6f99) | Sep 26, 2022 |
| HP            | EliteBook Folio 9480m       | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f8b76ec5f4](https://linux-hardware.org/?probe=f8b76ec5f4) | Sep 25, 2022 |
| AZW           | SEi                         | [063c3cc52e](https://linux-hardware.org/?probe=063c3cc52e) | Sep 25, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [d8b270de2b](https://linux-hardware.org/?probe=d8b270de2b) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9f37c7c4fa](https://linux-hardware.org/?probe=9f37c7c4fa) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0d790a94fa](https://linux-hardware.org/?probe=0d790a94fa) | Sep 25, 2022 |
| Dell          | XPS 15 9520                 | [fab5b34402](https://linux-hardware.org/?probe=fab5b34402) | Sep 25, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [2e96ddfdd1](https://linux-hardware.org/?probe=2e96ddfdd1) | Sep 25, 2022 |
| Apple         | MacBookPro14,1              | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Apple         | MacBookPro16,1              | [6e7d310781](https://linux-hardware.org/?probe=6e7d310781) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [96f4499ec5](https://linux-hardware.org/?probe=96f4499ec5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [91bd22b430](https://linux-hardware.org/?probe=91bd22b430) | Sep 25, 2022 |
| Dell          | XPS 13 9380                 | [332540a4c8](https://linux-hardware.org/?probe=332540a4c8) | Sep 24, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| HP            | Pavilion dv6                | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Lenovo        | ThinkPad T440s 20ARA0YL0... | [93eedc638b](https://linux-hardware.org/?probe=93eedc638b) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [b7f6ab8ad0](https://linux-hardware.org/?probe=b7f6ab8ad0) | Sep 23, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | [72caf18b5f](https://linux-hardware.org/?probe=72caf18b5f) | Sep 23, 2022 |
| Timi          | A35S                        | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [c30d8893ca](https://linux-hardware.org/?probe=c30d8893ca) | Sep 23, 2022 |
| Dell          | XPS 9320                    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| HONOR         | HGE-WX6                     | [337c1097ef](https://linux-hardware.org/?probe=337c1097ef) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a5e851730c](https://linux-hardware.org/?probe=a5e851730c) | Sep 23, 2022 |
| Acer          | Aspire A715-43G             | [5ecaaef0b1](https://linux-hardware.org/?probe=5ecaaef0b1) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [c916654073](https://linux-hardware.org/?probe=c916654073) | Sep 22, 2022 |
| VALE          | Notebook Classic C140       | [5a8e431c98](https://linux-hardware.org/?probe=5a8e431c98) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4d47a6bfcf](https://linux-hardware.org/?probe=4d47a6bfcf) | Sep 22, 2022 |
| Dell          | Precision 5540              | [0f09e447ea](https://linux-hardware.org/?probe=0f09e447ea) | Sep 22, 2022 |
| Dell          | Vostro 3558                 | [61f6c99c88](https://linux-hardware.org/?probe=61f6c99c88) | Sep 22, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [efaa235d34](https://linux-hardware.org/?probe=efaa235d34) | Sep 22, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [ba5fdd39e6](https://linux-hardware.org/?probe=ba5fdd39e6) | Sep 21, 2022 |
| Framework     | Laptop                      | [8e2d92c817](https://linux-hardware.org/?probe=8e2d92c817) | Sep 21, 2022 |
| HP            | 15 Notebook PC              | [9515dd24c0](https://linux-hardware.org/?probe=9515dd24c0) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [85cab20988](https://linux-hardware.org/?probe=85cab20988) | Sep 21, 2022 |
| Razer         | Blade                       | [c835fe2f90](https://linux-hardware.org/?probe=c835fe2f90) | Sep 21, 2022 |
| HP            | Pavilion 17                 | [0f7eec1f7a](https://linux-hardware.org/?probe=0f7eec1f7a) | Sep 21, 2022 |
| Acer          | Nitro AN515-57              | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| HP            | EliteBook 840 G3            | [deb8b0ca78](https://linux-hardware.org/?probe=deb8b0ca78) | Sep 21, 2022 |
| HP            | Pavilion Power Laptop 15... | [360e860fb1](https://linux-hardware.org/?probe=360e860fb1) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [7561f24877](https://linux-hardware.org/?probe=7561f24877) | Sep 20, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [32120dfcd4](https://linux-hardware.org/?probe=32120dfcd4) | Sep 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [98771092de](https://linux-hardware.org/?probe=98771092de) | Sep 20, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | [20c7b9dcf9](https://linux-hardware.org/?probe=20c7b9dcf9) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | [f4aade3998](https://linux-hardware.org/?probe=f4aade3998) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [21617c5cff](https://linux-hardware.org/?probe=21617c5cff) | Sep 20, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | [95c8201663](https://linux-hardware.org/?probe=95c8201663) | Sep 20, 2022 |
| HP            | ProBook 455 G7              | [80d61eb345](https://linux-hardware.org/?probe=80d61eb345) | Sep 20, 2022 |
| Lenovo        | ThinkPad T420 4180PBG       | [857b2acef0](https://linux-hardware.org/?probe=857b2acef0) | Sep 20, 2022 |
| Dell          | XPS 15 9550                 | [acf36b1555](https://linux-hardware.org/?probe=acf36b1555) | Sep 20, 2022 |
| HP            | ENVY 15                     | [6921f93893](https://linux-hardware.org/?probe=6921f93893) | Sep 20, 2022 |
| Acer          | Nitro AN517-51              | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1da95a964b](https://linux-hardware.org/?probe=1da95a964b) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| Apple         | MacBookPro9,2               | [a681a7cab8](https://linux-hardware.org/?probe=a681a7cab8) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [bed329dab4](https://linux-hardware.org/?probe=bed329dab4) | Sep 19, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0RK0... | [eaaf80509b](https://linux-hardware.org/?probe=eaaf80509b) | Sep 19, 2022 |
| Toshiba       | Satellite L40t-A            | [b09254248d](https://linux-hardware.org/?probe=b09254248d) | Sep 19, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [9b14ec4438](https://linux-hardware.org/?probe=9b14ec4438) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | [ede9aab3fb](https://linux-hardware.org/?probe=ede9aab3fb) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [db46d34737](https://linux-hardware.org/?probe=db46d34737) | Sep 19, 2022 |
| HUAWEI        | WRT-WX9                     | [4c8883345d](https://linux-hardware.org/?probe=4c8883345d) | Sep 19, 2022 |
| ASUSTek       | GL502VMK                    | [9776f2c20c](https://linux-hardware.org/?probe=9776f2c20c) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [474f619a29](https://linux-hardware.org/?probe=474f619a29) | Sep 19, 2022 |
| Dell          | Latitude E6520              | [ac5b5a53a2](https://linux-hardware.org/?probe=ac5b5a53a2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| Dell          | Precision 5560              | [5e70cfd82f](https://linux-hardware.org/?probe=5e70cfd82f) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [bb8fdeb489](https://linux-hardware.org/?probe=bb8fdeb489) | Sep 19, 2022 |
| Dell          | Latitude 5420               | [1e5a1652cc](https://linux-hardware.org/?probe=1e5a1652cc) | Sep 19, 2022 |
| Lenovo        | ThinkPad T430 2349S4D       | [0c4d98868f](https://linux-hardware.org/?probe=0c4d98868f) | Sep 19, 2022 |
| Dell          | Vostro 3500                 | [f114799ded](https://linux-hardware.org/?probe=f114799ded) | Sep 18, 2022 |
| Dell          | Latitude 3420               | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [b9bb35af47](https://linux-hardware.org/?probe=b9bb35af47) | Sep 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [2032e77931](https://linux-hardware.org/?probe=2032e77931) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [751df30316](https://linux-hardware.org/?probe=751df30316) | Sep 18, 2022 |
| Lenovo        | G580 20150                  | [fe325d1046](https://linux-hardware.org/?probe=fe325d1046) | Sep 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | [e09b077e89](https://linux-hardware.org/?probe=e09b077e89) | Sep 18, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [1f9f8ee511](https://linux-hardware.org/?probe=1f9f8ee511) | Sep 18, 2022 |
| Dell          | Inspiron N5110              | [fa2122b6ee](https://linux-hardware.org/?probe=fa2122b6ee) | Sep 18, 2022 |
| Unknown       | Unknown                     | [1e27521b13](https://linux-hardware.org/?probe=1e27521b13) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Apple         | MacBookPro12,1              | [ba54a7bf0c](https://linux-hardware.org/?probe=ba54a7bf0c) | Sep 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [3615e82cb6](https://linux-hardware.org/?probe=3615e82cb6) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Dell          | Vostro 3500                 | [fd0bcfd41d](https://linux-hardware.org/?probe=fd0bcfd41d) | Sep 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [3b0169723f](https://linux-hardware.org/?probe=3b0169723f) | Sep 17, 2022 |
| Irbis         | NB264                       | [e9361bf1c8](https://linux-hardware.org/?probe=e9361bf1c8) | Sep 17, 2022 |
| Apple         | MacBookPro16,1              | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| Toshiba       | Satellite C660              | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| Dell          | G3 3779                     | [5c24653999](https://linux-hardware.org/?probe=5c24653999) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [70a944e816](https://linux-hardware.org/?probe=70a944e816) | Sep 16, 2022 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [50669d6ff9](https://linux-hardware.org/?probe=50669d6ff9) | Sep 16, 2022 |
| Acidanther... | iMac19,2                    | [94b79ac6e5](https://linux-hardware.org/?probe=94b79ac6e5) | Sep 16, 2022 |
| Dell          | Latitude 5511               | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| Acer          | Nitro AN515-58              | [a29728a871](https://linux-hardware.org/?probe=a29728a871) | Sep 16, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| Dell          | Inspiron 5567               | [1cbebfbe09](https://linux-hardware.org/?probe=1cbebfbe09) | Sep 16, 2022 |
| ASUSTek       | X550JK                      | [5c399f4fb0](https://linux-hardware.org/?probe=5c399f4fb0) | Sep 15, 2022 |
| ASUSTek       | X550JK                      | [59df382a23](https://linux-hardware.org/?probe=59df382a23) | Sep 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [80638ed98f](https://linux-hardware.org/?probe=80638ed98f) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c70951aae5](https://linux-hardware.org/?probe=c70951aae5) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [4b19ce2aab](https://linux-hardware.org/?probe=4b19ce2aab) | Sep 15, 2022 |
| Dell          | Inspiron N5110              | [f566a009c8](https://linux-hardware.org/?probe=f566a009c8) | Sep 15, 2022 |
| HP            | Snappy                      | [d890c80994](https://linux-hardware.org/?probe=d890c80994) | Sep 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [6d4adb2a44](https://linux-hardware.org/?probe=6d4adb2a44) | Sep 14, 2022 |
| HP            | EliteBook 8460p             | [d34c655d2b](https://linux-hardware.org/?probe=d34c655d2b) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [efb36530f1](https://linux-hardware.org/?probe=efb36530f1) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ec8f0a9ebf](https://linux-hardware.org/?probe=ec8f0a9ebf) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [930ee68921](https://linux-hardware.org/?probe=930ee68921) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| System76      | Lemur Pro                   | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| Dell          | Latitude 5521               | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3f34e5ed01](https://linux-hardware.org/?probe=3f34e5ed01) | Sep 14, 2022 |
| Dell          | Inspiron 5575               | [1ae871a545](https://linux-hardware.org/?probe=1ae871a545) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [d1b95841a4](https://linux-hardware.org/?probe=d1b95841a4) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7326474aae](https://linux-hardware.org/?probe=7326474aae) | Sep 13, 2022 |
| Dell          | Precision 5560              | [78809c82c2](https://linux-hardware.org/?probe=78809c82c2) | Sep 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| HP            | EliteBook 745 G6            | [61da5fee97](https://linux-hardware.org/?probe=61da5fee97) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| Lanix         | AL V9                       | [e03f9aecc3](https://linux-hardware.org/?probe=e03f9aecc3) | Sep 12, 2022 |
| Dell          | Latitude 5495               | [23586ab4ef](https://linux-hardware.org/?probe=23586ab4ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad P1 20MD0014RT      | [4935debbce](https://linux-hardware.org/?probe=4935debbce) | Sep 12, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [a901769629](https://linux-hardware.org/?probe=a901769629) | Sep 12, 2022 |
| AZW           | SEi                         | [3a4d2086b0](https://linux-hardware.org/?probe=3a4d2086b0) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a54854cd7](https://linux-hardware.org/?probe=4a54854cd7) | Sep 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [5bbf96fe23](https://linux-hardware.org/?probe=5bbf96fe23) | Sep 12, 2022 |
| HP            | ProBook 4540s               | [1f46e342f0](https://linux-hardware.org/?probe=1f46e342f0) | Sep 12, 2022 |
| ASUSTek       | ROG Strix G713QR_G713QR     | [d05595b19e](https://linux-hardware.org/?probe=d05595b19e) | Sep 12, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [47b15d6b6c](https://linux-hardware.org/?probe=47b15d6b6c) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [edb2842417](https://linux-hardware.org/?probe=edb2842417) | Sep 12, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [c6df51fa3b](https://linux-hardware.org/?probe=c6df51fa3b) | Sep 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [7064ea27f5](https://linux-hardware.org/?probe=7064ea27f5) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| Acer          | Nitro AN515-58              | [49fe1c56a3](https://linux-hardware.org/?probe=49fe1c56a3) | Sep 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| Apple         | MacBookPro12,1              | [4bb5badf61](https://linux-hardware.org/?probe=4bb5badf61) | Sep 10, 2022 |
| ASUSTek       | UX310UQK                    | [dc650f1d77](https://linux-hardware.org/?probe=dc650f1d77) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [8fb4287325](https://linux-hardware.org/?probe=8fb4287325) | Sep 10, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [0a7b65b735](https://linux-hardware.org/?probe=0a7b65b735) | Sep 09, 2022 |
| Dell          | Inspiron 3543               | [7fc528e246](https://linux-hardware.org/?probe=7fc528e246) | Sep 09, 2022 |
| AXDIA Inte... | WINPAD V10                  | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| Dell          | XPS 15 9570                 | [a54dae9e4b](https://linux-hardware.org/?probe=a54dae9e4b) | Sep 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [cada1ee58d](https://linux-hardware.org/?probe=cada1ee58d) | Sep 09, 2022 |
| Apple         | MacBookPro9,2               | [9f2534b22e](https://linux-hardware.org/?probe=9f2534b22e) | Sep 09, 2022 |
| Notebook      | W230SS                      | [9ea483f3dd](https://linux-hardware.org/?probe=9ea483f3dd) | Sep 09, 2022 |
| Dell          | Inspiron 5566               | [7d9ebaa4f8](https://linux-hardware.org/?probe=7d9ebaa4f8) | Sep 09, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [8242cc3cab](https://linux-hardware.org/?probe=8242cc3cab) | Sep 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [30488e19df](https://linux-hardware.org/?probe=30488e19df) | Sep 08, 2022 |
| Dell          | Latitude E5450              | [305ef21301](https://linux-hardware.org/?probe=305ef21301) | Sep 08, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | [0bcf279fb8](https://linux-hardware.org/?probe=0bcf279fb8) | Sep 08, 2022 |
| Dell          | Precision 5770              | [41e44b27f4](https://linux-hardware.org/?probe=41e44b27f4) | Sep 08, 2022 |
| Dell          | XPS 13 9305                 | [bc21b4b2a8](https://linux-hardware.org/?probe=bc21b4b2a8) | Sep 07, 2022 |
| Dell          | XPS 13 7390                 | [f91eeba2bd](https://linux-hardware.org/?probe=f91eeba2bd) | Sep 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [dce2728dad](https://linux-hardware.org/?probe=dce2728dad) | Sep 07, 2022 |
| Dell          | Latitude E6420              | [8885f409d8](https://linux-hardware.org/?probe=8885f409d8) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | [a90b385c8e](https://linux-hardware.org/?probe=a90b385c8e) | Sep 07, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | [7a3494a230](https://linux-hardware.org/?probe=7a3494a230) | Sep 07, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | [673c26165e](https://linux-hardware.org/?probe=673c26165e) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [d3d092e789](https://linux-hardware.org/?probe=d3d092e789) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c905c86c47](https://linux-hardware.org/?probe=c905c86c47) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [424adc035f](https://linux-hardware.org/?probe=424adc035f) | Sep 07, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [ff127ee255](https://linux-hardware.org/?probe=ff127ee255) | Sep 06, 2022 |
| HP            | EliteBook 850 G6            | [7c202a088d](https://linux-hardware.org/?probe=7c202a088d) | Sep 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [826deb0c55](https://linux-hardware.org/?probe=826deb0c55) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [bffe658238](https://linux-hardware.org/?probe=bffe658238) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b327372b50](https://linux-hardware.org/?probe=b327372b50) | Sep 05, 2022 |
| MSI           | Prestige 15 A10SC           | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [3969240177](https://linux-hardware.org/?probe=3969240177) | Sep 05, 2022 |
| Dell          | Inspiron 16 5625            | [d38282759b](https://linux-hardware.org/?probe=d38282759b) | Sep 05, 2022 |
| Notebook      | NJ5x_NJ7xLU                 | [1cadc455a1](https://linux-hardware.org/?probe=1cadc455a1) | Sep 05, 2022 |
| Dell          | Latitude 7490               | [4a59725d2d](https://linux-hardware.org/?probe=4a59725d2d) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Samsung       | 550P5C/550P7C               | [9d9451305b](https://linux-hardware.org/?probe=9d9451305b) | Sep 05, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [4641fe397a](https://linux-hardware.org/?probe=4641fe397a) | Sep 05, 2022 |
| Dell          | Latitude 5511               | [3193c29c67](https://linux-hardware.org/?probe=3193c29c67) | Sep 04, 2022 |
| Chuwi         | Hi10 Go                     | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [57f8a4e96b](https://linux-hardware.org/?probe=57f8a4e96b) | Sep 04, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [f0bcadac2f](https://linux-hardware.org/?probe=f0bcadac2f) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 2320HPU       | [a8ba64ec12](https://linux-hardware.org/?probe=a8ba64ec12) | Sep 04, 2022 |
| HUAWEI        | KLVD-WXX9                   | [cc383de755](https://linux-hardware.org/?probe=cc383de755) | Sep 04, 2022 |
| Lenovo        | ThinkPad E560 20EV000RGE    | [5b69ce9986](https://linux-hardware.org/?probe=5b69ce9986) | Sep 04, 2022 |
| Acer          | AS VN7-571G                 | [1c14fbaf96](https://linux-hardware.org/?probe=1c14fbaf96) | Sep 04, 2022 |
| Dell          | Latitude 5420               | [b236b791c1](https://linux-hardware.org/?probe=b236b791c1) | Sep 04, 2022 |
| Lenovo        | 3000 N200 0769BAG           | [33fcb3e2b3](https://linux-hardware.org/?probe=33fcb3e2b3) | Sep 04, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [c4db289b99](https://linux-hardware.org/?probe=c4db289b99) | Sep 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a0b2975bf7](https://linux-hardware.org/?probe=a0b2975bf7) | Sep 04, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [dc3fd2d992](https://linux-hardware.org/?probe=dc3fd2d992) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | [109d233976](https://linux-hardware.org/?probe=109d233976) | Sep 03, 2022 |
| Samsung       | 550P5C/550P7C               | [6aac0a8c6c](https://linux-hardware.org/?probe=6aac0a8c6c) | Sep 03, 2022 |
| Dell          | Vostro 1320                 | [e66853cc37](https://linux-hardware.org/?probe=e66853cc37) | Sep 03, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [758f8d2184](https://linux-hardware.org/?probe=758f8d2184) | Sep 03, 2022 |
| ASUSTek       | UX310UQK                    | [ed392e6b79](https://linux-hardware.org/?probe=ed392e6b79) | Sep 03, 2022 |
| ASUSTek       | GL503VM                     | [43cbef1764](https://linux-hardware.org/?probe=43cbef1764) | Sep 03, 2022 |
| MSI           | GP72MVR 7RFX                | [f370d7bbc3](https://linux-hardware.org/?probe=f370d7bbc3) | Sep 03, 2022 |
| Dell          | XPS 15 9570                 | [b73e153667](https://linux-hardware.org/?probe=b73e153667) | Sep 03, 2022 |
| HP            | Stream Notebook PC 13       | [d6c9e33a55](https://linux-hardware.org/?probe=d6c9e33a55) | Sep 03, 2022 |
| MSI           | Modern 14 B11MOL            | [92d3e81be7](https://linux-hardware.org/?probe=92d3e81be7) | Sep 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [cec0b91aa9](https://linux-hardware.org/?probe=cec0b91aa9) | Sep 03, 2022 |
| Toshiba       | Satellite C850-C5K          | [51dbca1f4d](https://linux-hardware.org/?probe=51dbca1f4d) | Sep 03, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [1ce3a883a0](https://linux-hardware.org/?probe=1ce3a883a0) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001JIX     | [30eb9dcb39](https://linux-hardware.org/?probe=30eb9dcb39) | Sep 03, 2022 |
| Alienware     | 14                          | [f30f3ddf3d](https://linux-hardware.org/?probe=f30f3ddf3d) | Sep 03, 2022 |
| HP            | EliteBook 8470p             | [33ae7d4c4b](https://linux-hardware.org/?probe=33ae7d4c4b) | Sep 03, 2022 |
| Acer          | Swift SF315-41              | [634777751a](https://linux-hardware.org/?probe=634777751a) | Sep 02, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [006c26eaa0](https://linux-hardware.org/?probe=006c26eaa0) | Sep 02, 2022 |
| Acer          | Swift SF315-41              | [dd250df1ef](https://linux-hardware.org/?probe=dd250df1ef) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [aa9a637495](https://linux-hardware.org/?probe=aa9a637495) | Sep 02, 2022 |
| Lenovo        | V14-ADA 82C6                | [5e98ea70fb](https://linux-hardware.org/?probe=5e98ea70fb) | Sep 02, 2022 |
| Lenovo        | G50-45 80E3                 | [a8e1884f32](https://linux-hardware.org/?probe=a8e1884f32) | Sep 02, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [1f0f793a37](https://linux-hardware.org/?probe=1f0f793a37) | Sep 02, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [5730a9015f](https://linux-hardware.org/?probe=5730a9015f) | Sep 02, 2022 |
| Dell          | Inspiron 5558               | [203baa4d7f](https://linux-hardware.org/?probe=203baa4d7f) | Sep 02, 2022 |
| Dell          | Latitude E6400              | [c781ec4733](https://linux-hardware.org/?probe=c781ec4733) | Sep 02, 2022 |
| Chuwi         | HeroBook Air                | [1ac18273da](https://linux-hardware.org/?probe=1ac18273da) | Sep 02, 2022 |
| Dell          | Inspiron 5490               | [3ef6519b6d](https://linux-hardware.org/?probe=3ef6519b6d) | Sep 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [e4a4630b4e](https://linux-hardware.org/?probe=e4a4630b4e) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5ad5d3809b](https://linux-hardware.org/?probe=5ad5d3809b) | Sep 01, 2022 |
| HP            | ProBook 4540s               | [b5e6fa5a71](https://linux-hardware.org/?probe=b5e6fa5a71) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [b6b7c6dc62](https://linux-hardware.org/?probe=b6b7c6dc62) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [6b3c188071](https://linux-hardware.org/?probe=6b3c188071) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [b0d6660da8](https://linux-hardware.org/?probe=b0d6660da8) | Sep 01, 2022 |
| Dell          | Inspiron 3542               | [945ec7d987](https://linux-hardware.org/?probe=945ec7d987) | Sep 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [c86e73aed6](https://linux-hardware.org/?probe=c86e73aed6) | Sep 01, 2022 |
| ASUSTek       | X541UJ                      | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| Dell          | Latitude 7430               | [8876fb0448](https://linux-hardware.org/?probe=8876fb0448) | Aug 31, 2022 |
| Eluktronic... | MAG-15 2070                 | [d7fb373622](https://linux-hardware.org/?probe=d7fb373622) | Aug 31, 2022 |
| ASUSTek       | K401UQK                     | [4f026584d7](https://linux-hardware.org/?probe=4f026584d7) | Aug 31, 2022 |
| Dell          | Latitude E5570              | [91513d0ee3](https://linux-hardware.org/?probe=91513d0ee3) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| Acer          | TMP453-MG                   | [63efab9aef](https://linux-hardware.org/?probe=63efab9aef) | Aug 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [30457b898c](https://linux-hardware.org/?probe=30457b898c) | Aug 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [7399a32997](https://linux-hardware.org/?probe=7399a32997) | Aug 30, 2022 |
| HP            | 255 G8 Notebook PC          | [c96e8a8254](https://linux-hardware.org/?probe=c96e8a8254) | Aug 30, 2022 |
| Dell          | G3 3579                     | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| HP            | Laptop 14-fq1xxx            | [8ea91d6b4b](https://linux-hardware.org/?probe=8ea91d6b4b) | Aug 30, 2022 |
| HP            | 250 G7 Notebook PC          | [96a56c7cb9](https://linux-hardware.org/?probe=96a56c7cb9) | Aug 30, 2022 |
| Dell          | Inspiron 15 5510            | [346eda373e](https://linux-hardware.org/?probe=346eda373e) | Aug 29, 2022 |
| Dell          | Inspiron 15 5510            | [ecdb2875da](https://linux-hardware.org/?probe=ecdb2875da) | Aug 29, 2022 |
| Dell          | Inspiron 5721               | [d483434965](https://linux-hardware.org/?probe=d483434965) | Aug 29, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [473daa5ce3](https://linux-hardware.org/?probe=473daa5ce3) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| MSI           | Prestige 14Evo A11MO        | [22cf60f50b](https://linux-hardware.org/?probe=22cf60f50b) | Aug 29, 2022 |
| Infinix       | INBOOK X2                   | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [d82227c6d3](https://linux-hardware.org/?probe=d82227c6d3) | Aug 29, 2022 |
| Dell          | Precision 5750              | [2ee41b471e](https://linux-hardware.org/?probe=2ee41b471e) | Aug 28, 2022 |
| HUAWEI        | KLVL-WXXW                   | [829a45ed6f](https://linux-hardware.org/?probe=829a45ed6f) | Aug 28, 2022 |
| Google        | Eve                         | [4c83027c9a](https://linux-hardware.org/?probe=4c83027c9a) | Aug 28, 2022 |
| Dell          | Precision 5750              | [af9992756f](https://linux-hardware.org/?probe=af9992756f) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [af00be0ff8](https://linux-hardware.org/?probe=af00be0ff8) | Aug 28, 2022 |
| HP            | ProBook 650 G1              | [7738c266d6](https://linux-hardware.org/?probe=7738c266d6) | Aug 28, 2022 |
| Apple         | MacBookPro8,1               | [5efa863ca3](https://linux-hardware.org/?probe=5efa863ca3) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Dell          | Inspiron 3442               | [46a68b981e](https://linux-hardware.org/?probe=46a68b981e) | Aug 27, 2022 |
| Apple         | MacBookAir6,2               | [0454b1e087](https://linux-hardware.org/?probe=0454b1e087) | Aug 27, 2022 |
| Acidanther... | MacBookPro12,1              | [9e48c5e245](https://linux-hardware.org/?probe=9e48c5e245) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [559d6f0e42](https://linux-hardware.org/?probe=559d6f0e42) | Aug 27, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [f4dd9de519](https://linux-hardware.org/?probe=f4dd9de519) | Aug 27, 2022 |
| Acer          | Nitro AN515-57              | [8d314e1557](https://linux-hardware.org/?probe=8d314e1557) | Aug 27, 2022 |
| Lenovo        | G50-45 80E3                 | [be9921e0e0](https://linux-hardware.org/?probe=be9921e0e0) | Aug 27, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| HP            | EliteBook 840 G5            | [7bd19ce9a1](https://linux-hardware.org/?probe=7bd19ce9a1) | Aug 27, 2022 |
| Exo           | Smart Serie L               | [5cbaef571b](https://linux-hardware.org/?probe=5cbaef571b) | Aug 27, 2022 |
| Acer          | Aspire VN7-592G             | [cec4df79eb](https://linux-hardware.org/?probe=cec4df79eb) | Aug 26, 2022 |
| HP            | ProBook 4530s               | [be1270c998](https://linux-hardware.org/?probe=be1270c998) | Aug 26, 2022 |
| ASUSTek       | X541NA                      | [4755f121e3](https://linux-hardware.org/?probe=4755f121e3) | Aug 26, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Dell          | Inspiron 3593               | [c3ae4b86ac](https://linux-hardware.org/?probe=c3ae4b86ac) | Aug 26, 2022 |
| HP            | ENVY 15                     | [db06c354d4](https://linux-hardware.org/?probe=db06c354d4) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| MSI           | Modern 14 A10RAS            | [af216b7b4a](https://linux-hardware.org/?probe=af216b7b4a) | Aug 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [2b52864870](https://linux-hardware.org/?probe=2b52864870) | Aug 25, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| HP            | Pavilion dv6                | [7fd7791035](https://linux-hardware.org/?probe=7fd7791035) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [4378f177a8](https://linux-hardware.org/?probe=4378f177a8) | Aug 24, 2022 |
| HUAWEI        | BOD-WXX9                    | [fd6ff49314](https://linux-hardware.org/?probe=fd6ff49314) | Aug 24, 2022 |
| HP            | Laptop 15s-fq2xxx           | [f8213e35a4](https://linux-hardware.org/?probe=f8213e35a4) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | [f9090c46a9](https://linux-hardware.org/?probe=f9090c46a9) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | [ac93dd480f](https://linux-hardware.org/?probe=ac93dd480f) | Aug 24, 2022 |
| ASUSTek       | T100HAN                     | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [33c24103bf](https://linux-hardware.org/?probe=33c24103bf) | Aug 23, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [1b1c9cb460](https://linux-hardware.org/?probe=1b1c9cb460) | Aug 23, 2022 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | [2e88f854f8](https://linux-hardware.org/?probe=2e88f854f8) | Aug 23, 2022 |
| Dell          | Inspiron 5567               | [7b0f03259b](https://linux-hardware.org/?probe=7b0f03259b) | Aug 23, 2022 |
| Dell          | XPS L421X                   | [80a474140e](https://linux-hardware.org/?probe=80a474140e) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Aquarius      | Cmp NS765                   | [991487a61b](https://linux-hardware.org/?probe=991487a61b) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | [f25926e1fa](https://linux-hardware.org/?probe=f25926e1fa) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | [784c6d89a6](https://linux-hardware.org/?probe=784c6d89a6) | Aug 22, 2022 |
| Apple         | MacBookPro11,2              | [9856ca2463](https://linux-hardware.org/?probe=9856ca2463) | Aug 21, 2022 |
| Acer          | TravelMate P215-52G         | [1d36fcbc9f](https://linux-hardware.org/?probe=1d36fcbc9f) | Aug 21, 2022 |
| HP            | Compaq 15                   | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Fedora 36 | 1157      | 20.42%  |
| Fedora 35 | 954       | 16.84%  |
| Fedora 34 | 926       | 16.34%  |
| Fedora 33 | 851       | 15.02%  |
| Fedora 32 | 746       | 13.17%  |
| Fedora 31 | 503       | 8.88%   |
| Fedora 37 | 235       | 4.15%   |
| Fedora 30 | 162       | 2.86%   |
| Fedora 29 | 90        | 1.59%   |
| Fedora 28 | 22        | 0.39%   |
| Fedora 27 | 8         | 0.14%   |
| Fedora 24 | 4         | 0.07%   |
| Fedora 21 | 4         | 0.07%   |
| Fedora 38 | 2         | 0.04%   |
| Fedora 25 | 2         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Fedora | 5098      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64  | 107       | 1.69%   |
| 5.16.18-200.fc35.x86_64 | 92        | 1.45%   |
| 5.9.16-200.fc33.x86_64  | 90        | 1.42%   |
| 5.11.12-300.fc34.x86_64 | 75        | 1.19%   |
| 5.14.10-300.fc35.x86_64 | 69        | 1.09%   |
| 6.0.5-200.fc36.x86_64   | 67        | 1.06%   |
| 5.8.16-300.fc33.x86_64  | 64        | 1.01%   |
| 5.18.13-200.fc36.x86_64 | 61        | 0.96%   |
| 5.8.15-301.fc33.x86_64  | 60        | 0.95%   |
| 5.8.4-200.fc32.x86_64   | 57        | 0.9%    |
| 5.13.12-200.fc34.x86_64 | 54        | 0.85%   |
| 6.0.8-300.fc37.x86_64   | 51        | 0.81%   |
| 5.18.11-200.fc36.x86_64 | 50        | 0.79%   |
| 5.8.18-300.fc33.x86_64  | 46        | 0.73%   |
| 5.19.16-200.fc36.x86_64 | 46        | 0.73%   |
| 5.17.11-300.fc36.x86_64 | 46        | 0.73%   |
| 5.14.16-301.fc35.x86_64 | 46        | 0.73%   |
| 5.9.8-200.fc33.x86_64   | 45        | 0.71%   |
| 5.18.16-200.fc36.x86_64 | 45        | 0.71%   |
| 5.16.16-200.fc35.x86_64 | 44        | 0.7%    |
| 5.17.6-300.fc36.x86_64  | 43        | 0.68%   |
| 5.19.9-200.fc36.x86_64  | 42        | 0.66%   |
| 5.15.6-200.fc35.x86_64  | 42        | 0.66%   |
| 5.16.12-200.fc35.x86_64 | 41        | 0.65%   |
| 5.10.19-200.fc33.x86_64 | 41        | 0.65%   |
| 5.9.11-200.fc33.x86_64  | 40        | 0.63%   |
| 6.0.9-300.fc37.x86_64   | 39        | 0.62%   |
| 5.3.16-300.fc31.x86_64  | 39        | 0.62%   |
| 5.12.13-300.fc34.x86_64 | 39        | 0.62%   |
| 5.7.8-200.fc32.x86_64   | 38        | 0.6%    |
| 5.18.5-200.fc36.x86_64  | 38        | 0.6%    |
| 5.18.17-200.fc36.x86_64 | 38        | 0.6%    |
| 5.15.12-200.fc35.x86_64 | 38        | 0.6%    |
| 5.14.18-300.fc35.x86_64 | 38        | 0.6%    |
| 5.19.8-200.fc36.x86_64  | 37        | 0.58%   |
| 5.7.10-201.fc32.x86_64  | 36        | 0.57%   |
| 5.19.6-200.fc36.x86_64  | 36        | 0.57%   |
| 5.17.4-200.fc35.x86_64  | 36        | 0.57%   |
| 5.17.13-300.fc36.x86_64 | 36        | 0.57%   |
| 5.11.11-200.fc33.x86_64 | 36        | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 141       | 2.23%   |
| 5.9.16  | 96        | 1.52%   |
| 5.16.18 | 95        | 1.5%    |
| 5.8.15  | 87        | 1.38%   |
| 5.11.12 | 82        | 1.3%    |
| 5.8.16  | 81        | 1.28%   |
| 5.14.10 | 78        | 1.23%   |
| 5.19.16 | 74        | 1.17%   |
| 6.0.5   | 73        | 1.15%   |
| 5.11.11 | 66        | 1.04%   |
| 5.18.13 | 65        | 1.03%   |
| 5.8.18  | 64        | 1.01%   |
| 6.0.8   | 57        | 0.9%    |
| 5.8.4   | 57        | 0.9%    |
| 5.13.12 | 57        | 0.9%    |
| 5.14.18 | 54        | 0.85%   |
| 5.18.11 | 53        | 0.84%   |
| 5.14.16 | 52        | 0.82%   |
| 6.0.9   | 51        | 0.81%   |
| 5.9.8   | 51        | 0.81%   |
| 5.17.11 | 50        | 0.79%   |
| 5.15.6  | 50        | 0.79%   |
| 5.19.9  | 49        | 0.77%   |
| 5.19.8  | 49        | 0.77%   |
| 5.18.16 | 48        | 0.76%   |
| 5.17.6  | 47        | 0.74%   |
| 5.16.16 | 47        | 0.74%   |
| 5.16.12 | 46        | 0.73%   |
| 5.10.19 | 45        | 0.71%   |
| 5.6.6   | 44        | 0.7%    |
| 5.18.5  | 44        | 0.7%    |
| 5.9.11  | 43        | 0.68%   |
| 5.15.12 | 43        | 0.68%   |
| 5.19.15 | 42        | 0.66%   |
| 5.17.4  | 42        | 0.66%   |
| 5.14.9  | 42        | 0.66%   |
| 5.12.13 | 42        | 0.66%   |
| 5.9.10  | 40        | 0.63%   |
| 5.3.16  | 40        | 0.63%   |
| 5.18.17 | 39        | 0.62%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 498       | 8.22%   |
| 5.8     | 463       | 7.64%   |
| 5.11    | 447       | 7.38%   |
| 5.19    | 441       | 7.28%   |
| 5.18    | 408       | 6.73%   |
| 5.14    | 390       | 6.44%   |
| 5.16    | 382       | 6.3%    |
| 5.15    | 308       | 5.08%   |
| 5.9     | 304       | 5.02%   |
| 5.13    | 303       | 5%      |
| 5.10    | 291       | 4.8%    |
| 5.6     | 286       | 4.72%   |
| 5.12    | 282       | 4.65%   |
| 6.0     | 237       | 3.91%   |
| 5.7     | 221       | 3.65%   |
| 5.3     | 194       | 3.2%    |
| 5.5     | 183       | 3.02%   |
| 5.4     | 168       | 2.77%   |
| 5.0     | 61        | 1.01%   |
| 5.2     | 47        | 0.78%   |
| 5.1     | 43        | 0.71%   |
| 4.19    | 30        | 0.5%    |
| 4.18    | 27        | 0.45%   |
| 4.20    | 18        | 0.3%    |
| 6.1     | 6         | 0.1%    |
| 4.16    | 3         | 0.05%   |
| 4.15    | 3         | 0.05%   |
| 4.11    | 3         | 0.05%   |
| 4.1     | 3         | 0.05%   |
| 4.8     | 2         | 0.03%   |
| 4.17    | 2         | 0.03%   |
| 4.5     | 1         | 0.02%   |
| 4.14    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| 3.17    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 5090      | 99.82%  |
| i686    | 5         | 0.1%    |
| aarch64 | 3         | 0.06%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 3859      | 73.56%  |
| KDE5            | 517       | 9.86%   |
| Unknown         | 287       | 5.47%   |
| KDE             | 134       | 2.55%   |
| XFCE            | 108       | 2.06%   |
| MATE            | 75        | 1.43%   |
| X-Cinnamon      | 74        | 1.41%   |
| Cinnamon        | 64        | 1.22%   |
| i3              | 21        | 0.4%    |
| LXQt            | 20        | 0.38%   |
| GNOME Classic   | 20        | 0.38%   |
| LXDE            | 15        | 0.29%   |
| sway            | 12        | 0.23%   |
| Deepin          | 12        | 0.23%   |
| Pantheon        | 4         | 0.08%   |
| awesome         | 4         | 0.08%   |
| openbox         | 3         | 0.06%   |
| KDE4            | 3         | 0.06%   |
| GNOME Flashback | 3         | 0.06%   |
| fluxbox         | 3         | 0.06%   |
| Budgie          | 3         | 0.06%   |
| bspwm           | 2         | 0.04%   |
| xinit-compat    | 1         | 0.02%   |
| KDE:old         | 1         | 0.02%   |
| DWM             | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 3307      | 62.44%  |
| X11     | 1758      | 33.19%  |
| Unknown | 189       | 3.57%   |
| Tty     | 42        | 0.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2622      | 50.05%  |
| GDM     | 1976      | 37.72%  |
| SDDM    | 353       | 6.74%   |
| LightDM | 178       | 3.4%    |
| TDM     | 87        | 1.66%   |
| XDM     | 10        | 0.19%   |
| KDM     | 8         | 0.15%   |
| LXDM    | 4         | 0.08%   |
| Ly      | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2643      | 50.85%  |
| Unknown | 363       | 6.98%   |
| en_GB   | 345       | 6.64%   |
| pt_BR   | 247       | 4.75%   |
| ru_RU   | 216       | 4.16%   |
| de_DE   | 176       | 3.39%   |
| fr_FR   | 155       | 2.98%   |
| it_IT   | 143       | 2.75%   |
| pl_PL   | 85        | 1.64%   |
| es_ES   | 77        | 1.48%   |
| en_CA   | 73        | 1.4%    |
| en_AU   | 67        | 1.29%   |
| en_IN   | 62        | 1.19%   |
| es_MX   | 44        | 0.85%   |
| cs_CZ   | 36        | 0.69%   |
| es_AR   | 26        | 0.5%    |
| es_CL   | 25        | 0.48%   |
| tr_TR   | 24        | 0.46%   |
| nl_NL   | 24        | 0.46%   |
| zh_CN   | 20        | 0.38%   |
| pt_PT   | 19        | 0.37%   |
| en_NZ   | 19        | 0.37%   |
| sv_SE   | 18        | 0.35%   |
| de_AT   | 17        | 0.33%   |
| hu_HU   | 16        | 0.31%   |
| en_DK   | 15        | 0.29%   |
| C       | 15        | 0.29%   |
| en_IE   | 14        | 0.27%   |
| es_CO   | 13        | 0.25%   |
| ru_UA   | 11        | 0.21%   |
| fi_FI   | 11        | 0.21%   |
| fr_CA   | 10        | 0.19%   |
| en_ZA   | 10        | 0.19%   |
| uk_UA   | 8         | 0.15%   |
| nb_NO   | 8         | 0.15%   |
| fr_BE   | 8         | 0.15%   |
| de_CH   | 8         | 0.15%   |
| sk_SK   | 7         | 0.13%   |
| en_SG   | 7         | 0.13%   |
| da_DK   | 7         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 4056      | 78.5%   |
| BIOS | 1111      | 21.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Btrfs               | 2844      | 54.27%  |
| Ext4                | 2048      | 39.08%  |
| Unknown             | 195       | 3.72%   |
| Xfs                 | 137       | 2.61%   |
| Overlay             | 8         | 0.15%   |
| F2fs                | 3         | 0.06%   |
| Zfs                 | 2         | 0.04%   |
| Fuse.fuse-overlayfs | 2         | 0.04%   |
| Ext3                | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2621      | 50.25%  |
| GPT     | 2227      | 42.7%   |
| MBR     | 368       | 7.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4680      | 90.72%  |
| Yes       | 479       | 9.28%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4212      | 81.53%  |
| Yes       | 954       | 18.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1554      | 30.48%  |
| Dell                   | 944       | 18.52%  |
| Hewlett-Packard        | 750       | 14.71%  |
| ASUSTek Computer       | 494       | 9.69%   |
| Acer                   | 332       | 6.51%   |
| Apple                  | 137       | 2.69%   |
| MSI                    | 108       | 2.12%   |
| HUAWEI                 | 90        | 1.77%   |
| Toshiba                | 73        | 1.43%   |
| Samsung Electronics    | 67        | 1.31%   |
| Sony                   | 46        | 0.9%    |
| Notebook               | 43        | 0.84%   |
| Timi                   | 31        | 0.61%   |
| Unknown                | 28        | 0.55%   |
| Framework              | 27        | 0.53%   |
| Positivo               | 22        | 0.43%   |
| Fujitsu                | 21        | 0.41%   |
| Alienware              | 21        | 0.41%   |
| System76               | 17        | 0.33%   |
| LG Electronics         | 16        | 0.31%   |
| Google                 | 16        | 0.31%   |
| TUXEDO                 | 15        | 0.29%   |
| Razer                  | 14        | 0.27%   |
| Gigabyte Technology    | 9         | 0.18%   |
| Chuwi                  | 9         | 0.18%   |
| Avell High Performance | 9         | 0.18%   |
| PC Specialist          | 7         | 0.14%   |
| Panasonic              | 7         | 0.14%   |
| SLIMBOOK               | 6         | 0.12%   |
| Packard Bell           | 6         | 0.12%   |
| GPU Company            | 6         | 0.12%   |
| Fujitsu Siemens        | 6         | 0.12%   |
| Hampoo                 | 5         | 0.1%    |
| GPD                    | 5         | 0.1%    |
| Gateway                | 5         | 0.1%    |
| eMachines              | 5         | 0.1%    |
| Schenker               | 4         | 0.08%   |
| Medion                 | 4         | 0.08%   |
| Itautec                | 4         | 0.08%   |
| HONOR                  | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 46        | 0.9%    |
| HP Notebook                                | 27        | 0.53%   |
| Framework Laptop                           | 22        | 0.43%   |
| Dell XPS 15 9570                           | 21        | 0.41%   |
| Dell XPS 15 7590                           | 21        | 0.41%   |
| Dell XPS 13 9370                           | 21        | 0.41%   |
| Dell XPS 13 9360                           | 19        | 0.37%   |
| Dell XPS 15 9560                           | 18        | 0.35%   |
| Dell Latitude 7490                         | 18        | 0.35%   |
| HP EliteBook 840 G6                        | 17        | 0.33%   |
| HP Pavilion dv6                            | 16        | 0.31%   |
| Dell XPS 13 7390                           | 16        | 0.31%   |
| Dell Latitude E7450                        | 15        | 0.29%   |
| HP Pavilion 15                             | 14        | 0.27%   |
| Dell XPS 15 9550                           | 14        | 0.27%   |
| Dell XPS 15 9500                           | 14        | 0.27%   |
| Dell XPS 13 9310                           | 14        | 0.27%   |
| Dell XPS 13 9300                           | 13        | 0.26%   |
| Dell Latitude 5480                         | 13        | 0.26%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 12        | 0.24%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 12        | 0.24%   |
| HP Pavilion Notebook                       | 12        | 0.24%   |
| HP Laptop 15-da0xxx                        | 12        | 0.24%   |
| Dell Inspiron 5570                         | 12        | 0.24%   |
| Dell Inspiron 15 7000 Gaming               | 12        | 0.24%   |
| Apple MacBookPro12,1                       | 12        | 0.24%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 11        | 0.22%   |
| Dell Latitude E7440                        | 11        | 0.22%   |
| Dell Latitude E6420                        | 11        | 0.22%   |
| Acer Aspire E5-573G                        | 11        | 0.22%   |
| HP Pavilion dv7                            | 10        | 0.2%    |
| HP EliteBook 840 G3                        | 10        | 0.2%    |
| Dell XPS 13 9350                           | 10        | 0.2%    |
| Dell Latitude E6520                        | 10        | 0.2%    |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 10        | 0.2%    |
| Apple MacBookPro9,2                        | 10        | 0.2%    |
| Lenovo Legion 5 15ARH05 82B5               | 9         | 0.18%   |
| HUAWEI NBLK-WAX9X                          | 9         | 0.18%   |
| HUAWEI KLVL-WXX9                           | 9         | 0.18%   |
| Dell XPS 13 9380                           | 9         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 957       | 18.77%  |
| Lenovo IdeaPad     | 315       | 6.18%   |
| Dell Latitude      | 274       | 5.37%   |
| Dell Inspiron      | 268       | 5.26%   |
| Dell XPS           | 226       | 4.43%   |
| Acer Aspire        | 215       | 4.22%   |
| HP Pavilion        | 161       | 3.16%   |
| HP EliteBook       | 148       | 2.9%    |
| HP ProBook         | 122       | 2.39%   |
| HP Laptop          | 104       | 2.04%   |
| ASUS VivoBook      | 80        | 1.57%   |
| Dell Precision     | 78        | 1.53%   |
| ASUS ROG           | 77        | 1.51%   |
| Toshiba Satellite  | 62        | 1.22%   |
| Lenovo Legion      | 59        | 1.16%   |
| Lenovo ThinkBook   | 50        | 0.98%   |
| Unknown            | 46        | 0.9%    |
| Dell Vostro        | 45        | 0.88%   |
| HP ZBook           | 43        | 0.84%   |
| Lenovo Yoga        | 41        | 0.8%    |
| Acer Nitro         | 40        | 0.78%   |
| ASUS ASUS          | 38        | 0.75%   |
| ASUS ZenBook       | 37        | 0.73%   |
| Acer Swift         | 36        | 0.71%   |
| HP ENVY            | 33        | 0.65%   |
| HP Notebook        | 27        | 0.53%   |
| Framework Laptop   | 27        | 0.53%   |
| Apple MacBookPro11 | 26        | 0.51%   |
| ASUS TUF           | 25        | 0.49%   |
| HP OMEN            | 21        | 0.41%   |
| Fujitsu LIFEBOOK   | 17        | 0.33%   |
| Dell G5            | 16        | 0.31%   |
| MSI Modern         | 15        | 0.29%   |
| Acer Predator      | 14        | 0.27%   |
| Razer Blade        | 13        | 0.26%   |
| Dell G3            | 12        | 0.24%   |
| Apple MacBookPro9  | 12        | 0.24%   |
| Apple MacBookPro12 | 12        | 0.24%   |
| HP 250             | 11        | 0.22%   |
| HP 15              | 10        | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 702       | 13.77%  |
| 2020    | 697       | 13.67%  |
| 2018    | 576       | 11.3%   |
| 2021    | 516       | 10.12%  |
| 2017    | 423       | 8.3%    |
| 2015    | 356       | 6.98%   |
| 2016    | 329       | 6.45%   |
| 2013    | 298       | 5.85%   |
| 2012    | 294       | 5.77%   |
| 2014    | 254       | 4.98%   |
| 2011    | 244       | 4.79%   |
| 2010    | 127       | 2.49%   |
| 2022    | 126       | 2.47%   |
| 2008    | 73        | 1.43%   |
| 2009    | 60        | 1.18%   |
| 2007    | 14        | 0.27%   |
| 2006    | 5         | 0.1%    |
| Unknown | 3         | 0.06%   |
| 2003    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5098      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4170      | 80.53%  |
| Enabled  | 1008      | 19.47%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5067      | 99.39%  |
| Yes  | 31        | 0.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1553      | 30.04%  |
| 16.01-24.0  | 1248      | 24.14%  |
| 8.01-16.0   | 1005      | 19.44%  |
| 32.01-64.0  | 546       | 10.56%  |
| 3.01-4.0    | 518       | 10.02%  |
| 1.01-2.0    | 99        | 1.91%   |
| 64.01-256.0 | 86        | 1.66%   |
| 24.01-32.0  | 80        | 1.55%   |
| 2.01-3.0    | 23        | 0.44%   |
| 0.51-1.0    | 10        | 0.19%   |
| Unknown     | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1652      | 28.82%  |
| 4.01-8.0   | 1507      | 26.29%  |
| 3.01-4.0   | 1225      | 21.37%  |
| 1.01-2.0   | 825       | 14.39%  |
| 8.01-16.0  | 401       | 6.99%   |
| 0.51-1.0   | 62        | 1.08%   |
| 16.01-24.0 | 41        | 0.72%   |
| 24.01-32.0 | 10        | 0.17%   |
| 32.01-64.0 | 5         | 0.09%   |
| 0.01-0.5   | 3         | 0.05%   |
| Unknown    | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3740      | 72.02%  |
| 2      | 1241      | 23.9%   |
| 3      | 153       | 2.95%   |
| 0      | 28        | 0.54%   |
| 4      | 20        | 0.39%   |
| 5      | 6         | 0.12%   |
| 6      | 5         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3984      | 77.75%  |
| Yes       | 1140      | 22.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3843      | 74.94%  |
| No        | 1285      | 25.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4997      | 97.94%  |
| No        | 105       | 2.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4246      | 82.3%   |
| No        | 913       | 17.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 900       | 17.47%  |
| Brazil      | 382       | 7.41%   |
| Germany     | 346       | 6.72%   |
| Russia      | 317       | 6.15%   |
| Italy       | 241       | 4.68%   |
| France      | 213       | 4.13%   |
| India       | 199       | 3.86%   |
| UK          | 178       | 3.45%   |
| Netherlands | 154       | 2.99%   |
| Poland      | 153       | 2.97%   |
| Canada      | 134       | 2.6%    |
| Spain       | 126       | 2.45%   |
| Czechia     | 92        | 1.79%   |
| Mexico      | 88        | 1.71%   |
| Australia   | 83        | 1.61%   |
| Turkey      | 79        | 1.53%   |
| Sweden      | 68        | 1.32%   |
| Austria     | 67        | 1.3%    |
| Switzerland | 57        | 1.11%   |
| Ukraine     | 56        | 1.09%   |
| Portugal    | 50        | 0.97%   |
| Argentina   | 50        | 0.97%   |
| Indonesia   | 48        | 0.93%   |
| Romania     | 47        | 0.91%   |
| Norway      | 47        | 0.91%   |
| Finland     | 47        | 0.91%   |
| Belgium     | 47        | 0.91%   |
| Hungary     | 42        | 0.82%   |
| Chile       | 37        | 0.72%   |
| Denmark     | 36        | 0.7%    |
| China       | 33        | 0.64%   |
| Iran        | 31        | 0.6%    |
| Bulgaria    | 28        | 0.54%   |
| Greece      | 27        | 0.52%   |
| Colombia    | 27        | 0.52%   |
| Slovakia    | 26        | 0.5%    |
| Belarus     | 25        | 0.49%   |
| New Zealand | 24        | 0.47%   |
| Japan       | 23        | 0.45%   |
| Israel      | 23        | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 110       | 2.01%   |
| Sao Paulo         | 53        | 0.97%   |
| St Petersburg     | 44        | 0.8%    |
| Paris             | 43        | 0.78%   |
| Vienna            | 41        | 0.75%   |
| Amsterdam         | 39        | 0.71%   |
| Warsaw            | 38        | 0.69%   |
| Prague            | 38        | 0.69%   |
| Istanbul          | 38        | 0.69%   |
| Milan             | 36        | 0.66%   |
| Berlin            | 35        | 0.64%   |
| Oslo              | 29        | 0.53%   |
| Munich            | 29        | 0.53%   |
| Madrid            | 29        | 0.53%   |
| Bengaluru         | 27        | 0.49%   |
| Helsinki          | 26        | 0.47%   |
| Mexico City       | 25        | 0.46%   |
| Sydney            | 24        | 0.44%   |
| Rio de Janeiro    | 22        | 0.4%    |
| Melbourne         | 22        | 0.4%    |
| Kyiv              | 22        | 0.4%    |
| Budapest          | 21        | 0.38%   |
| Bucharest         | 20        | 0.36%   |
| Brisbane          | 20        | 0.36%   |
| Hamburg           | 19        | 0.35%   |
| Zurich            | 18        | 0.33%   |
| Singapore         | 18        | 0.33%   |
| Rome              | 18        | 0.33%   |
| Lisbon            | 18        | 0.33%   |
| Brno              | 18        | 0.33%   |
| Tehran            | 17        | 0.31%   |
| Sofia             | 17        | 0.31%   |
| Krakow            | 17        | 0.31%   |
| Jakarta           | 17        | 0.31%   |
| Frankfurt am Main | 17        | 0.31%   |
| Delft             | 17        | 0.31%   |
| Chicago           | 17        | 0.31%   |
| Seattle           | 16        | 0.29%   |
| Portland          | 16        | 0.29%   |
| Minsk             | 16        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1356      | 1971   | 20.95%  |
| WDC                       | 687       | 862    | 10.61%  |
| Seagate                   | 518       | 685    | 8%      |
| Toshiba                   | 461       | 576    | 7.12%   |
| SanDisk                   | 453       | 592    | 7%      |
| SK hynix                  | 376       | 458    | 5.81%   |
| Unknown                   | 348       | 461    | 5.38%   |
| Kingston                  | 309       | 379    | 4.77%   |
| Intel                     | 277       | 390    | 4.28%   |
| Crucial                   | 197       | 255    | 3.04%   |
| Micron Technology         | 181       | 234    | 2.8%    |
| HGST                      | 143       | 201    | 2.21%   |
| A-DATA Technology         | 100       | 115    | 1.54%   |
| KIOXIA                    | 85        | 118    | 1.31%   |
| Apple                     | 78        | 96     | 1.21%   |
| Hitachi                   | 73        | 85     | 1.13%   |
| LITEON                    | 64        | 69     | 0.99%   |
| Phison                    | 49        | 54     | 0.76%   |
| China                     | 37        | 41     | 0.57%   |
| Silicon Motion            | 36        | 52     | 0.56%   |
| Transcend                 | 35        | 52     | 0.54%   |
| PNY                       | 30        | 39     | 0.46%   |
| SPCC                      | 27        | 34     | 0.42%   |
| LITEONIT                  | 23        | 29     | 0.36%   |
| Lenovo                    | 19        | 22     | 0.29%   |
| Corsair                   | 18        | 23     | 0.28%   |
| ADATA Technology          | 18        | 18     | 0.28%   |
| XPG                       | 17        | 26     | 0.26%   |
| Patriot                   | 16        | 20     | 0.25%   |
| Team                      | 14        | 17     | 0.22%   |
| OCZ                       | 14        | 16     | 0.22%   |
| Micron/Crucial Technology | 14        | 15     | 0.22%   |
| Unknown                   | 14        | 16     | 0.22%   |
| Realtek Semiconductor     | 13        | 18     | 0.2%    |
| UMIS                      | 12        | 14     | 0.19%   |
| Lite-On                   | 12        | 18     | 0.19%   |
| KingSpec                  | 12        | 14     | 0.19%   |
| JMicron Technology        | 12        | 14     | 0.19%   |
| Hewlett-Packard           | 12        | 11     | 0.19%   |
| Intenso                   | 11        | 13     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB                      | 113       | 1.66%   |
| Seagate ST1000LM035-1RK172 1TB                    | 106       | 1.56%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB            | 83        | 1.22%   |
| SanDisk NVMe SSD Drive 512GB                      | 76        | 1.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 63        | 0.93%   |
| HGST HTS721010A9E630 1TB                          | 62        | 0.91%   |
| Kingston SA400S37240G 240GB SSD                   | 59        | 0.87%   |
| Unknown MMC Card  32GB                            | 52        | 0.77%   |
| SK hynix NVMe SSD Drive 512GB                     | 51        | 0.75%   |
| Samsung SSD 860 EVO 500GB                         | 51        | 0.75%   |
| Samsung NVMe SSD Drive 1024GB                     | 50        | 0.74%   |
| Toshiba MQ04ABF100 1TB                            | 49        | 0.72%   |
| Toshiba MQ01ABD100 1TB                            | 49        | 0.72%   |
| Unknown MMC Card  64GB                            | 46        | 0.68%   |
| SanDisk NVMe SSD Drive 256GB                      | 46        | 0.68%   |
| Intel NVMe SSD Drive 512GB                        | 46        | 0.68%   |
| Samsung NVMe SSD Drive 1TB                        | 43        | 0.63%   |
| Toshiba NVMe SSD Drive 512GB                      | 38        | 0.56%   |
| Samsung SSD 850 EVO 500GB                         | 38        | 0.56%   |
| Samsung SSD 850 EVO 250GB                         | 38        | 0.56%   |
| Kingston SA400S37480G 480GB SSD                   | 37        | 0.54%   |
| Unknown MMC Card  128GB                           | 33        | 0.49%   |
| Toshiba NVMe SSD Drive 256GB                      | 33        | 0.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 33        | 0.49%   |
| Samsung NVMe SSD Drive 500GB                      | 32        | 0.47%   |
| Seagate ST500LT012-1DG142 500GB                   | 31        | 0.46%   |
| SK hynix NVMe SSD Drive 256GB                     | 30        | 0.44%   |
| Seagate Expansion 1TB                             | 30        | 0.44%   |
| Samsung SSD 860 EVO 1TB                           | 30        | 0.44%   |
| Samsung SSD 860 EVO 250GB                         | 29        | 0.43%   |
| HGST HTS541010A9E680 1TB                          | 28        | 0.41%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 26        | 0.38%   |
| Samsung MZVLB512HBJQ-000L7 512GB                  | 25        | 0.37%   |
| WDC WD10SPZX-24Z10 1TB                            | 24        | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB                      | 24        | 0.35%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                    | 24        | 0.35%   |
| Crucial CT500MX500SSD1 500GB                      | 24        | 0.35%   |
| Crucial CT240BX500SSD1 240GB                      | 24        | 0.35%   |
| Crucial CT1000MX500SSD1 1TB                       | 24        | 0.35%   |
| SK hynix NVMe SSD Drive 1024GB                    | 23        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 501       | 659    | 37.47%  |
| WDC                 | 352       | 448    | 26.33%  |
| Toshiba             | 210       | 258    | 15.71%  |
| HGST                | 143       | 201    | 10.7%   |
| Hitachi             | 73        | 85     | 5.46%   |
| Unknown             | 17        | 24     | 1.27%   |
| Samsung Electronics | 13        | 16     | 0.97%   |
| Fujitsu             | 10        | 10     | 0.75%   |
| Apple               | 7         | 8      | 0.52%   |
| LIO-ORG             | 2         | 8      | 0.15%   |
| ASMT                | 2         | 2      | 0.15%   |
| Phison              | 1         | 2      | 0.07%   |
| LaCie               | 1         | 2      | 0.07%   |
| JMicron Technology  | 1         | 1      | 0.07%   |
| Inateck             | 1         | 1      | 0.07%   |
| IB-AC703            | 1         | 1      | 0.07%   |
| HGST HTS            | 1         | 1      | 0.07%   |
| External            | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 534       | 769    | 25.55%  |
| Kingston            | 226       | 275    | 10.81%  |
| SanDisk             | 224       | 312    | 10.72%  |
| Crucial             | 179       | 236    | 8.56%   |
| WDC                 | 107       | 138    | 5.12%   |
| Intel               | 86        | 135    | 4.11%   |
| A-DATA Technology   | 68        | 81     | 3.25%   |
| Micron Technology   | 67        | 81     | 3.21%   |
| SK hynix            | 55        | 65     | 2.63%   |
| Apple               | 52        | 58     | 2.49%   |
| LITEON              | 51        | 56     | 2.44%   |
| Toshiba             | 43        | 56     | 2.06%   |
| China               | 36        | 40     | 1.72%   |
| Transcend           | 30        | 43     | 1.44%   |
| PNY                 | 29        | 37     | 1.39%   |
| LITEONIT            | 23        | 29     | 1.1%    |
| SPCC                | 22        | 29     | 1.05%   |
| Patriot             | 14        | 17     | 0.67%   |
| OCZ                 | 13        | 15     | 0.62%   |
| Corsair             | 12        | 14     | 0.57%   |
| KingSpec            | 11        | 12     | 0.53%   |
| Intenso             | 10        | 12     | 0.48%   |
| GOODRAM             | 10        | 14     | 0.48%   |
| Team                | 9         | 12     | 0.43%   |
| Seagate             | 9         | 9      | 0.43%   |
| Gigabyte Technology | 9         | 10     | 0.43%   |
| Netac               | 8         | 8      | 0.38%   |
| Lexar               | 7         | 14     | 0.33%   |
| JMicron Technology  | 7         | 9      | 0.33%   |
| Unknown             | 6         | 6      | 0.29%   |
| Hewlett-Packard     | 6         | 6      | 0.29%   |
| Plextor             | 5         | 6      | 0.24%   |
| Apacer              | 5         | 5      | 0.24%   |
| Unknown             | 5         | 6      | 0.24%   |
| TO Exter            | 4         | 4      | 0.19%   |
| Mushkin             | 4         | 11     | 0.19%   |
| FORESEE             | 4         | 4      | 0.19%   |
| Dogfish             | 4         | 4      | 0.19%   |
| BIWIN               | 4         | 5      | 0.19%   |
| Vaseky              | 3         | 4      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2502      | 3493   | 40.9%   |
| SSD     | 1932      | 2754   | 31.58%  |
| HDD     | 1292      | 1728   | 21.12%  |
| MMC     | 321       | 437    | 5.25%   |
| Unknown | 70        | 80     | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2822      | 4299   | 48.25%  |
| NVMe | 2499      | 3478   | 42.73%  |
| MMC  | 321       | 437    | 5.49%   |
| SAS  | 207       | 278    | 3.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1994      | 2809   | 61.94%  |
| 0.51-1.0   | 1091      | 1482   | 33.89%  |
| 1.01-2.0   | 113       | 169    | 3.51%   |
| 4.01-10.0  | 12        | 12     | 0.37%   |
| 3.01-4.0   | 7         | 7      | 0.22%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |
| 0          | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1178      | 22.01%  |
| 501-1000       | 1097      | 20.5%   |
| 101-250        | 1069      | 19.97%  |
| 1-20           | 562       | 10.5%   |
| 1001-2000      | 526       | 9.83%   |
| Unknown        | 367       | 6.86%   |
| 51-100         | 232       | 4.33%   |
| 21-50          | 126       | 2.35%   |
| More than 3000 | 99        | 1.85%   |
| 2001-3000      | 96        | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1650      | 29.45%  |
| 21-50          | 998       | 17.81%  |
| 101-250        | 901       | 16.08%  |
| 51-100         | 762       | 13.6%   |
| 251-500        | 516       | 9.21%   |
| Unknown        | 367       | 6.55%   |
| 501-1000       | 289       | 5.16%   |
| 1001-2000      | 93        | 1.66%   |
| More than 3000 | 15        | 0.27%   |
| 2001-3000      | 11        | 0.2%    |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                | 9         | 9      | 3.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 18     | 3.64%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 2.83%   |
| Toshiba MQ01ABD100 1TB                         | 6         | 6      | 2.43%   |
| HGST HTS545050A7E680 500GB                     | 6         | 6      | 2.43%   |
| HGST HTS541010A9E680 1TB                       | 6         | 6      | 2.43%   |
| Seagate ST9500325AS 500GB                      | 5         | 7      | 2.02%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 5         | 5      | 2.02%   |
| HGST HTS721010A9E630 1TB                       | 5         | 7      | 2.02%   |
| Hitachi HTS547575A9E384 752GB                  | 4         | 6      | 1.62%   |
| Toshiba MQ01ABD075 752GB                       | 3         | 3      | 1.21%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 1.21%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 4      | 1.21%   |
| Hitachi HTS545050B9A300 500GB                  | 3         | 3      | 1.21%   |
| Crucial CT1000P1SSD8 1TB                       | 3         | 3      | 1.21%   |
| WDC WD10SPZX-24Z10 1TB                         | 2         | 2      | 0.81%   |
| Toshiba MQ01ACF050 500GB                       | 2         | 2      | 0.81%   |
| Toshiba MQ01ABD050V 500GB                      | 2         | 2      | 0.81%   |
| Toshiba MK3275GSX 320GB                        | 2         | 2      | 0.81%   |
| SPCC Solid State Disk 256GB                    | 2         | 2      | 0.81%   |
| SK hynix SC308 SATA 128GB SSD                  | 2         | 2      | 0.81%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 2         | 2      | 0.81%   |
| Seagate ST9500420AS 500GB                      | 2         | 3      | 0.81%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.81%   |
| SanDisk SSD PLUS 240GB                         | 2         | 2      | 0.81%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD            | 2         | 2      | 0.81%   |
| LITEON CV8-8E128-HP 128GB SSD                  | 2         | 2      | 0.81%   |
| Kingston SV300S37A480G 480GB SSD               | 2         | 2      | 0.81%   |
| Intel SSDSC2BF180A5L 180GB                     | 2         | 2      | 0.81%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 0.81%   |
| Hitachi HTS545025B9SA02 250GB                  | 2         | 3      | 0.81%   |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 0.81%   |
| Fujitsu MHY2120BH 120GB                        | 2         | 2      | 0.81%   |
| Crucial CT1050MX300SSD1 1TB                    | 2         | 8      | 0.81%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 1         | 1      | 0.4%    |
| WDC WD7500BPVX-60JC3T0 752GB                   | 1         | 1      | 0.4%    |
| WDC WD6400BPVT-75HXZT3 640GB                   | 1         | 1      | 0.4%    |
| WDC WD6400BEVT-22A0RT0 640GB                   | 1         | 1      | 0.4%    |
| WDC WD5000LPVX-28V0TT0 500GB                   | 1         | 1      | 0.4%    |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 68     | 21.14%  |
| WDC                 | 26        | 28     | 10.57%  |
| Toshiba             | 24        | 24     | 9.76%   |
| HGST                | 22        | 24     | 8.94%   |
| Hitachi             | 19        | 22     | 7.72%   |
| Samsung Electronics | 18        | 22     | 7.32%   |
| Intel               | 12        | 23     | 4.88%   |
| Micron Technology   | 11        | 14     | 4.47%   |
| SK hynix            | 10        | 11     | 4.07%   |
| SanDisk             | 10        | 11     | 4.07%   |
| Crucial             | 10        | 16     | 4.07%   |
| Kingston            | 6         | 6      | 2.44%   |
| A-DATA Technology   | 5         | 5      | 2.03%   |
| LITEON              | 4         | 4      | 1.63%   |
| Fujitsu             | 3         | 3      | 1.22%   |
| SPCC                | 2         | 2      | 0.81%   |
| LITEONIT            | 2         | 3      | 0.81%   |
| walram              | 1         | 1      | 0.41%   |
| Union Memory        | 1         | 1      | 0.41%   |
| Teclast             | 1         | 1      | 0.41%   |
| SSD                 | 1         | 1      | 0.41%   |
| PNY                 | 1         | 1      | 0.41%   |
| Plextor             | 1         | 1      | 0.41%   |
| Origin              | 1         | 1      | 0.41%   |
| OCZ-VERTEX3         | 1         | 1      | 0.41%   |
| Lenovo              | 1         | 2      | 0.41%   |
| China               | 1         | 1      | 0.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 68     | 35.37%  |
| WDC                 | 25        | 27     | 17.01%  |
| Toshiba             | 23        | 23     | 15.65%  |
| HGST                | 22        | 24     | 14.97%  |
| Hitachi             | 19        | 22     | 12.93%  |
| Samsung Electronics | 3         | 3      | 2.04%   |
| Fujitsu             | 3         | 3      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 146       | 170    | 59.84%  |
| SSD  | 80        | 106    | 32.79%  |
| NVMe | 18        | 21     | 7.38%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB | 1         | 1      | 20%     |
| Toshiba THNSN5512GPUK NVMe 512GB     | 1         | 1      | 20%     |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 20%     |
| Samsung Electronics SSD 980 500GB    | 1         | 1      | 20%     |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| Toshiba             | 1         | 1      | 20%     |
| Seagate             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| HGST                | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2891      | 4855   | 52.75%  |
| Works    | 2347      | 3335   | 42.82%  |
| Malfunc  | 238       | 297    | 4.34%   |
| Failed   | 5         | 5      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3236      | 51.5%   |
| Samsung Electronics              | 883       | 14.05%  |
| AMD                              | 518       | 8.24%   |
| SanDisk                          | 443       | 7.05%   |
| SK hynix                         | 307       | 4.89%   |
| Toshiba America Info Systems     | 207       | 3.29%   |
| Micron Technology                | 115       | 1.83%   |
| KIOXIA                           | 90        | 1.43%   |
| Kingston Technology Company      | 88        | 1.4%    |
| Phison Electronics               | 69        | 1.1%    |
| ADATA Technology                 | 60        | 0.95%   |
| Silicon Motion                   | 52        | 0.83%   |
| Micron/Crucial Technology        | 32        | 0.51%   |
| Union Memory (Shenzhen)          | 26        | 0.41%   |
| Lite-On Technology               | 25        | 0.4%    |
| Nvidia                           | 23        | 0.37%   |
| Lenovo                           | 19        | 0.3%    |
| Solid State Storage Technology   | 18        | 0.29%   |
| Realtek Semiconductor            | 18        | 0.29%   |
| Apple                            | 17        | 0.27%   |
| Seagate Technology               | 8         | 0.13%   |
| Yangtze Memory Technologies      | 5         | 0.08%   |
| Marvell Technology Group         | 5         | 0.08%   |
| JMicron Technology               | 4         | 0.06%   |
| Silicon Integrated Systems [SiS] | 2         | 0.03%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| Biwin Storage Technology         | 2         | 0.03%   |
| ULi Electronics                  | 1         | 0.02%   |
| Transcend                        | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Beijing Starblaze Technology     | 1         | 0.02%   |
| ASMedia Technology               | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 543       | 8.28%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 490       | 7.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 480       | 7.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 325       | 4.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 319       | 4.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 208       | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 203       | 3.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 186       | 2.84%   |
| Samsung NVMe SSD Controller 980                                                | 170       | 2.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 166       | 2.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 163       | 2.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 159       | 2.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 139       | 2.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 134       | 2.04%   |
| Micron Non-Volatile memory controller                                          | 115       | 1.75%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 105       | 1.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 95        | 1.45%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 89        | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 87        | 1.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 81        | 1.24%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 81        | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                          | 81        | 1.24%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 78        | 1.19%   |
| Intel SSD 660P Series                                                          | 76        | 1.16%   |
| Intel Tiger Lake-LP SATA Controller                                            | 75        | 1.14%   |
| SanDisk Non-Volatile memory controller                                         | 72        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 65        | 0.99%   |
| SK hynix Non-Volatile memory controller                                        | 63        | 0.96%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 57        | 0.87%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 56        | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 56        | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 54        | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 53        | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 50        | 0.76%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 48        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 48        | 0.73%   |
| SK hynix BC511                                                                 | 47        | 0.72%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 46        | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 45        | 0.69%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 45        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3240      | 51.11%  |
| NVMe | 2505      | 39.52%  |
| RAID | 500       | 7.89%   |
| IDE  | 94        | 1.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 4186      | 82.11%  |
| AMD     | 908       | 17.81%  |
| ARM     | 3         | 0.06%   |
| Unknown | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 144       | 2.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 115       | 2.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 105       | 2.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 99        | 1.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 98        | 1.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 94        | 1.84%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 89        | 1.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 88        | 1.73%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 87        | 1.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 86        | 1.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 85        | 1.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 79        | 1.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 77        | 1.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 73        | 1.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 72        | 1.41%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 62        | 1.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 58        | 1.14%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 57        | 1.12%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 55        | 1.08%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 54        | 1.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 54        | 1.06%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 52        | 1.02%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 47        | 0.92%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 45        | 0.88%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 42        | 0.82%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 41        | 0.8%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 39        | 0.76%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 39        | 0.76%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 38        | 0.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 36        | 0.71%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 36        | 0.71%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 34        | 0.67%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 33        | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 33        | 0.65%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 33        | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 32        | 0.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 31        | 0.61%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 31        | 0.61%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 30        | 0.59%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 30        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 1651      | 32.39%  |
| Intel Core i5                  | 1329      | 26.07%  |
| Other                          | 423       | 8.3%    |
| Intel Core i3                  | 318       | 6.24%   |
| AMD Ryzen 5                    | 282       | 5.53%   |
| AMD Ryzen 7                    | 259       | 5.08%   |
| Intel Celeron                  | 120       | 2.35%   |
| Intel Core 2 Duo               | 87        | 1.71%   |
| Intel Atom                     | 83        | 1.63%   |
| AMD Ryzen 7 PRO                | 65        | 1.28%   |
| AMD Ryzen 9                    | 63        | 1.24%   |
| Intel Pentium                  | 62        | 1.22%   |
| Intel Core i9                  | 48        | 0.94%   |
| AMD Ryzen 3                    | 37        | 0.73%   |
| AMD Ryzen 5 PRO                | 33        | 0.65%   |
| AMD A6                         | 27        | 0.53%   |
| AMD A10                        | 27        | 0.53%   |
| AMD A8                         | 22        | 0.43%   |
| Intel Pentium Silver           | 17        | 0.33%   |
| AMD A4                         | 17        | 0.33%   |
| Intel Xeon                     | 13        | 0.26%   |
| Intel Pentium Dual-Core        | 13        | 0.26%   |
| AMD E1                         | 10        | 0.2%    |
| AMD Athlon                     | 9         | 0.18%   |
| AMD E                          | 7         | 0.14%   |
| AMD A12                        | 7         | 0.14%   |
| Intel Pentium Dual             | 6         | 0.12%   |
| Intel Core m5                  | 6         | 0.12%   |
| Intel Genuine                  | 5         | 0.1%    |
| Intel Core m3                  | 5         | 0.1%    |
| Intel Core M                   | 5         | 0.1%    |
| Intel Core m7                  | 4         | 0.08%   |
| AMD PRO A10                    | 4         | 0.08%   |
| AMD Phenom II                  | 4         | 0.08%   |
| AMD E2                         | 4         | 0.08%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.06%   |
| AMD Athlon II                  | 3         | 0.06%   |
| Intel Core 2                   | 2         | 0.04%   |
| Intel Celeron Dual-Core        | 2         | 0.04%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 2131      | 41.78%  |
| 2       | 1962      | 38.47%  |
| 6       | 488       | 9.57%   |
| 8       | 434       | 8.51%   |
| 14      | 30        | 0.59%   |
| 12      | 23        | 0.45%   |
| 1       | 19        | 0.37%   |
| 10      | 9         | 0.18%   |
| 3       | 2         | 0.04%   |
| 16      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 5097      | 99.96%  |
| 2       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4455      | 87.25%  |
| 1       | 650       | 12.73%  |
| Unknown | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4962      | 96.93%  |
| Unknown        | 151       | 2.95%   |
| 32-bit         | 4         | 0.08%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 348       | 6.72%   |
| 0x806ea    | 338       | 6.53%   |
| 0x306a9    | 325       | 6.28%   |
| Unknown    | 298       | 5.75%   |
| 0x806c1    | 277       | 5.35%   |
| 0x206a7    | 257       | 4.96%   |
| 0x806e9    | 247       | 4.77%   |
| 0x406e3    | 241       | 4.65%   |
| 0x906ea    | 240       | 4.63%   |
| 0x40651    | 203       | 3.92%   |
| 0x306d4    | 194       | 3.75%   |
| 0x306c3    | 159       | 3.07%   |
| 0xa0652    | 138       | 2.66%   |
| 0x0a50000c | 116       | 2.24%   |
| 0x906e9    | 111       | 2.14%   |
| 0x08600106 | 104       | 2.01%   |
| 0x08108102 | 103       | 1.99%   |
| 0x506e3    | 97        | 1.87%   |
| 0x706e5    | 89        | 1.72%   |
| 0x08108109 | 86        | 1.66%   |
| 0x20655    | 77        | 1.49%   |
| 0x806eb    | 68        | 1.31%   |
| 0x30678    | 65        | 1.26%   |
| 0x1067a    | 63        | 1.22%   |
| 0x08600104 | 59        | 1.14%   |
| 0x906ed    | 54        | 1.04%   |
| 0x08608103 | 52        | 1%      |
| 0x906a3    | 48        | 0.93%   |
| 0x08600103 | 45        | 0.87%   |
| 0x806d1    | 42        | 0.81%   |
| 0x406c4    | 38        | 0.73%   |
| 0x706a8    | 31        | 0.6%    |
| 0x406c3    | 29        | 0.56%   |
| 0x0810100b | 29        | 0.56%   |
| 0x506c9    | 27        | 0.52%   |
| 0x10676    | 26        | 0.5%    |
| 0x20652    | 24        | 0.46%   |
| 0x08608102 | 24        | 0.46%   |
| 0x40661    | 23        | 0.44%   |
| 0x706a1    | 22        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1487      | 29.16%  |
| Haswell          | 400       | 7.84%   |
| Skylake          | 361       | 7.08%   |
| IvyBridge        | 335       | 6.57%   |
| TigerLake        | 304       | 5.96%   |
| SandyBridge      | 267       | 5.24%   |
| Zen 2            | 245       | 4.8%    |
| Broadwell        | 197       | 3.86%   |
| Zen+             | 196       | 3.84%   |
| CometLake        | 156       | 3.06%   |
| Silvermont       | 143       | 2.8%    |
| Zen 3            | 140       | 2.75%   |
| Icelake          | 139       | 2.73%   |
| Unknown          | 127       | 2.49%   |
| Westmere         | 106       | 2.08%   |
| Penryn           | 91        | 1.78%   |
| Alderlake Hybrid | 56        | 1.1%    |
| Goldmont plus    | 54        | 1.06%   |
| Zen              | 53        | 1.04%   |
| Excavator        | 45        | 0.88%   |
| Goldmont         | 28        | 0.55%   |
| Puma             | 27        | 0.53%   |
| Core             | 24        | 0.47%   |
| Piledriver       | 22        | 0.43%   |
| Nehalem          | 17        | 0.33%   |
| Jaguar           | 17        | 0.33%   |
| Bobcat           | 14        | 0.27%   |
| K10              | 10        | 0.2%    |
| K10 Llano        | 9         | 0.18%   |
| Tremont          | 8         | 0.16%   |
| Steamroller      | 5         | 0.1%    |
| K8 Hammer        | 4         | 0.08%   |
| K8 & K10 hybrid  | 4         | 0.08%   |
| Bonnell          | 4         | 0.08%   |
| P6               | 3         | 0.06%   |
| NetBurst         | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3936      | 58.38%  |
| Nvidia                           | 1623      | 24.07%  |
| AMD                              | 1182      | 17.53%  |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 353       | 5.15%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 310       | 4.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 278       | 4.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 259       | 3.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 246       | 3.59%   |
| Intel HD Graphics 620                                                                    | 245       | 3.57%   |
| AMD Renoir                                                                               | 238       | 3.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 235       | 3.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 220       | 3.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 206       | 3%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 196       | 2.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 186       | 2.71%   |
| Intel HD Graphics 5500                                                                   | 173       | 2.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 161       | 2.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 129       | 1.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 124       | 1.81%   |
| Intel HD Graphics 630                                                                    | 103       | 1.5%    |
| Intel HD Graphics 530                                                                    | 90        | 1.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 83        | 1.21%   |
| AMD Lucienne                                                                             | 79        | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 77        | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 76        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 76        | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 72        | 1.05%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 71        | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 67        | 0.98%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 61        | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 58        | 0.85%   |
| Nvidia GP108M [GeForce MX150]                                                            | 57        | 0.83%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 51        | 0.74%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 50        | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 49        | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 47        | 0.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 47        | 0.69%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 44        | 0.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 43        | 0.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 41        | 0.6%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 39        | 0.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 39        | 0.57%   |
| AMD Rembrandt [Radeon 680M]                                                              | 38        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2455      | 48%     |
| Intel + Nvidia     | 1261      | 24.65%  |
| 1 x AMD            | 721       | 14.1%   |
| Intel + AMD        | 218       | 4.26%   |
| 1 x Nvidia         | 206       | 4.03%   |
| AMD + Nvidia       | 156       | 3.05%   |
| 2 x AMD            | 87        | 1.7%    |
| Other              | 6         | 0.12%   |
| 2 x Nvidia         | 2         | 0.04%   |
| 2 x Intel          | 1         | 0.02%   |
| 1 x SiS            | 1         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4395      | 85.22%  |
| Proprietary | 704       | 13.65%  |
| Unknown     | 58        | 1.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3186      | 61.3%   |
| 1.01-2.0   | 723       | 13.91%  |
| 0.01-0.5   | 515       | 9.91%   |
| 3.01-4.0   | 336       | 6.47%   |
| 0.51-1.0   | 281       | 5.41%   |
| 7.01-8.0   | 62        | 1.19%   |
| 5.01-6.0   | 59        | 1.14%   |
| 2.01-3.0   | 21        | 0.4%    |
| 8.01-16.0  | 14        | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1139      | 17.96%  |
| BOE                     | 876       | 13.81%  |
| LG Display              | 864       | 13.63%  |
| Chimei Innolux          | 827       | 13.04%  |
| Samsung Electronics     | 498       | 7.85%   |
| Dell                    | 312       | 4.92%   |
| Sharp                   | 284       | 4.48%   |
| Goldstar                | 201       | 3.17%   |
| Lenovo                  | 138       | 2.18%   |
| Apple                   | 137       | 2.16%   |
| PANDA                   | 118       | 1.86%   |
| Hewlett-Packard         | 114       | 1.8%    |
| Philips                 | 69        | 1.09%   |
| Chi Mei Optoelectronics | 68        | 1.07%   |
| BenQ                    | 68        | 1.07%   |
| Acer                    | 64        | 1.01%   |
| CSO                     | 62        | 0.98%   |
| AOC                     | 57        | 0.9%    |
| InfoVision              | 55        | 0.87%   |
| Ancor Communications    | 53        | 0.84%   |
| Iiyama                  | 29        | 0.46%   |
| ViewSonic               | 26        | 0.41%   |
| TMX                     | 23        | 0.36%   |
| Panasonic               | 17        | 0.27%   |
| JDI                     | 17        | 0.27%   |
| ASUSTek Computer        | 17        | 0.27%   |
| Sony                    | 15        | 0.24%   |
| Toshiba                 | 12        | 0.19%   |
| Sceptre Tech            | 10        | 0.16%   |
| MSI                     | 10        | 0.16%   |
| CPT                     | 9         | 0.14%   |
| LG Philips              | 8         | 0.13%   |
| HannStar                | 8         | 0.13%   |
| Eizo                    | 7         | 0.11%   |
| Vizio                   | 6         | 0.09%   |
| Fujitsu Siemens         | 6         | 0.09%   |
| RTK                     | 5         | 0.08%   |
| NEC Computers           | 5         | 0.08%   |
| InnoLux Display         | 5         | 0.08%   |
| Vestel Elektronik       | 4         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 52        | 0.81%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 43        | 0.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 43        | 0.67%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 42        | 0.65%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 40        | 0.62%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 37        | 0.57%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 34        | 0.53%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 30        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 28        | 0.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 28        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 27        | 0.42%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 27        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 26        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 26        | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 25        | 0.39%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 24        | 0.37%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 22        | 0.34%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 22        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 22        | 0.34%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 21        | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 20        | 0.31%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 20        | 0.31%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 20        | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 20        | 0.31%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 19        | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 19        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 19        | 0.29%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 19        | 0.29%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 19        | 0.29%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 19        | 0.29%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 18        | 0.28%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 17        | 0.26%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 17        | 0.26%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 17        | 0.26%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 16        | 0.25%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 16        | 0.25%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 16        | 0.25%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 16        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 16        | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 16        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2965      | 51.09%  |
| 1366x768 (WXGA)    | 1178      | 20.3%   |
| 3840x2160 (4K)     | 341       | 5.88%   |
| 2560x1440 (QHD)    | 244       | 4.2%    |
| 1600x900 (HD+)     | 212       | 3.65%   |
| 1920x1200 (WUXGA)  | 158       | 2.72%   |
| 2560x1600          | 89        | 1.53%   |
| 1280x800 (WXGA)    | 88        | 1.52%   |
| 2880x1800          | 63        | 1.09%   |
| 2560x1080          | 57        | 0.98%   |
| 1440x900 (WXGA+)   | 54        | 0.93%   |
| 3440x1440          | 45        | 0.78%   |
| 1680x1050 (WSXGA+) | 37        | 0.64%   |
| 3840x2400          | 36        | 0.62%   |
| 3200x1800 (QHD+)   | 31        | 0.53%   |
| 2160x1440          | 31        | 0.53%   |
| 1280x1024 (SXGA)   | 30        | 0.52%   |
| 2256x1504          | 27        | 0.47%   |
| 1360x768           | 15        | 0.26%   |
| 3000x2000          | 14        | 0.24%   |
| 3456x2160          | 7         | 0.12%   |
| 3200x2000          | 7         | 0.12%   |
| 3072x1920          | 6         | 0.1%    |
| 2520x1680          | 6         | 0.1%    |
| 2240x1400          | 6         | 0.1%    |
| 3840x1600          | 5         | 0.09%   |
| 2160x1350          | 5         | 0.09%   |
| 1920x1280          | 5         | 0.09%   |
| 3840x1080          | 4         | 0.07%   |
| 1920x540           | 4         | 0.07%   |
| 1024x768 (XGA)     | 4         | 0.07%   |
| 1024x600           | 4         | 0.07%   |
| Unknown            | 3         | 0.05%   |
| 2880x1920          | 2         | 0.03%   |
| 2736x1824          | 2         | 0.03%   |
| 1920x515           | 2         | 0.03%   |
| 1680x945           | 2         | 0.03%   |
| 1600x1200          | 2         | 0.03%   |
| 9360x2160          | 1         | 0.02%   |
| 4680x2175          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2346      | 36.98%  |
| 13      | 1047      | 16.5%   |
| 14      | 881       | 13.89%  |
| 17      | 326       | 5.14%   |
| 27      | 306       | 4.82%   |
| 24      | 292       | 4.6%    |
| 23      | 209       | 3.29%   |
| 12      | 174       | 2.74%   |
| 21      | 150       | 2.36%   |
| 34      | 89        | 1.4%    |
| 31      | 66        | 1.04%   |
| 16      | 66        | 1.04%   |
| 18      | 63        | 0.99%   |
| 11      | 58        | 0.91%   |
| 19      | 32        | 0.5%    |
| 20      | 30        | 0.47%   |
| 22      | 26        | 0.41%   |
| Unknown | 21        | 0.33%   |
| 25      | 19        | 0.3%    |
| 40      | 15        | 0.24%   |
| 32      | 14        | 0.22%   |
| 84      | 13        | 0.2%    |
| 29      | 11        | 0.17%   |
| 35      | 10        | 0.16%   |
| 26      | 10        | 0.16%   |
| 10      | 10        | 0.16%   |
| 54      | 7         | 0.11%   |
| 72      | 6         | 0.09%   |
| 37      | 6         | 0.09%   |
| 48      | 5         | 0.08%   |
| 39      | 4         | 0.06%   |
| 28      | 4         | 0.06%   |
| 46      | 3         | 0.05%   |
| 33      | 3         | 0.05%   |
| 74      | 2         | 0.03%   |
| 63      | 2         | 0.03%   |
| 58      | 2         | 0.03%   |
| 57      | 2         | 0.03%   |
| 52      | 2         | 0.03%   |
| 43      | 2         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 3789      | 60.38%  |
| 501-600     | 749       | 11.94%  |
| 201-300     | 731       | 11.65%  |
| 351-400     | 393       | 6.26%   |
| 401-500     | 282       | 4.49%   |
| 601-700     | 113       | 1.8%    |
| 701-800     | 105       | 1.67%   |
| 801-900     | 37        | 0.59%   |
| 1001-1500   | 28        | 0.45%   |
| 1501-2000   | 22        | 0.35%   |
| Unknown     | 21        | 0.33%   |
| 901-1000    | 4         | 0.06%   |
| 101-200     | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4493      | 84.14%  |
| 16/10   | 579       | 10.84%  |
| 21/9    | 108       | 2.02%   |
| 3/2     | 98        | 1.84%   |
| 5/4     | 29        | 0.54%   |
| 4/3     | 10        | 0.19%   |
| Unknown | 9         | 0.17%   |
| 32/9    | 8         | 0.15%   |
| 6/5     | 2         | 0.04%   |
| 3.88    | 1         | 0.02%   |
| 3.73    | 1         | 0.02%   |
| 3.40    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2350      | 37.12%  |
| 81-90          | 1527      | 24.12%  |
| 201-250        | 535       | 8.45%   |
| 71-80          | 399       | 6.3%    |
| 301-350        | 316       | 4.99%   |
| 121-130        | 297       | 4.69%   |
| 351-500        | 190       | 3%      |
| 61-70          | 169       | 2.67%   |
| 251-300        | 126       | 1.99%   |
| 151-200        | 92        | 1.45%   |
| 141-150        | 66        | 1.04%   |
| 111-120        | 60        | 0.95%   |
| 51-60          | 59        | 0.93%   |
| More than 1000 | 41        | 0.65%   |
| 501-1000       | 39        | 0.62%   |
| 131-140        | 25        | 0.39%   |
| Unknown        | 21        | 0.33%   |
| 41-50          | 10        | 0.16%   |
| 91-100         | 6         | 0.09%   |
| 1-40           | 2         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2803      | 45.37%  |
| 101-120       | 1390      | 22.5%   |
| 51-100        | 980       | 15.86%  |
| 161-240       | 622       | 10.07%  |
| More than 240 | 327       | 5.29%   |
| 1-50          | 35        | 0.57%   |
| Unknown       | 21        | 0.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3861      | 73.21%  |
| 2     | 1144      | 21.69%  |
| 3     | 156       | 2.96%   |
| 0     | 102       | 1.93%   |
| 4     | 9         | 0.17%   |
| 5     | 2         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3131      | 40.35%  |
| Realtek Semiconductor             | 2502      | 32.25%  |
| Qualcomm Atheros                  | 935       | 12.05%  |
| Broadcom                          | 337       | 4.34%   |
| MediaTek                          | 128       | 1.65%   |
| Broadcom Limited                  | 82        | 1.06%   |
| Lenovo                            | 74        | 0.95%   |
| Sierra Wireless                   | 53        | 0.68%   |
| TP-Link                           | 49        | 0.63%   |
| ASIX Electronics                  | 47        | 0.61%   |
| Ralink                            | 37        | 0.48%   |
| Dell                              | 35        | 0.45%   |
| Marvell Technology Group          | 32        | 0.41%   |
| DisplayLink                       | 32        | 0.41%   |
| Ericsson Business Mobile Networks | 26        | 0.34%   |
| Ralink Technology                 | 24        | 0.31%   |
| Hewlett-Packard                   | 21        | 0.27%   |
| Qualcomm                          | 20        | 0.26%   |
| Samsung Electronics               | 17        | 0.22%   |
| Nvidia                            | 17        | 0.22%   |
| Huawei Technologies               | 15        | 0.19%   |
| ASUSTek Computer                  | 13        | 0.17%   |
| Xiaomi                            | 12        | 0.15%   |
| Apple                             | 12        | 0.15%   |
| Fibocom                           | 10        | 0.13%   |
| Google                            | 9         | 0.12%   |
| NetGear                           | 8         | 0.1%    |
| JMicron Technology                | 8         | 0.1%    |
| Qualcomm Atheros Communications   | 6         | 0.08%   |
| T & A Mobile Phones               | 5         | 0.06%   |
| Linksys                           | 5         | 0.06%   |
| D-Link                            | 5         | 0.06%   |
| OPPO Electronics                  | 4         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.05%   |
| Edimax Technology                 | 4         | 0.05%   |
| D-Link System                     | 4         | 0.05%   |
| Motorola PCS                      | 3         | 0.04%   |
| Microsoft                         | 3         | 0.04%   |
| Cypress Semiconductor             | 3         | 0.04%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1582      | 16.67%  |
| Intel Wi-Fi 6 AX200                                               | 397       | 4.18%   |
| Intel Wireless 8265 / 8275                                        | 348       | 3.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 344       | 3.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 281       | 2.96%   |
| Intel Wi-Fi 6 AX201                                               | 226       | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 223       | 2.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 210       | 2.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 208       | 2.19%   |
| Intel Wireless 8260                                               | 199       | 2.1%    |
| Intel Wireless 7260                                               | 185       | 1.95%   |
| Intel Wireless 7265                                               | 175       | 1.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 151       | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 149       | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 137       | 1.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 136       | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 135       | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 132       | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 126       | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 124       | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 123       | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 118       | 1.24%   |
| Intel Wireless 3165                                               | 96        | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 91        | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 82        | 0.86%   |
| Intel Wireless-AC 9260                                            | 82        | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 81        | 0.85%   |
| Intel Ethernet Connection (4) I219-V                              | 79        | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 75        | 0.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 72        | 0.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 70        | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 70        | 0.74%   |
| Intel Ethernet Connection I218-LM                                 | 66        | 0.7%    |
| Intel Centrino Ultimate-N 6300                                    | 62        | 0.65%   |
| Intel Ethernet Connection (6) I219-V                              | 61        | 0.64%   |
| Intel Wireless 3160                                               | 60        | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 60        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 59        | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 56        | 0.59%   |
| Intel Ethernet Connection I217-LM                                 | 54        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3046      | 58.11%  |
| Qualcomm Atheros                | 827       | 15.78%  |
| Realtek Semiconductor           | 658       | 12.55%  |
| Broadcom                        | 273       | 5.21%   |
| MediaTek                        | 123       | 2.35%   |
| Broadcom Limited                | 61        | 1.16%   |
| Sierra Wireless                 | 53        | 1.01%   |
| Ralink                          | 37        | 0.71%   |
| TP-Link                         | 34        | 0.65%   |
| Dell                            | 26        | 0.5%    |
| Ralink Technology               | 24        | 0.46%   |
| Qualcomm                        | 14        | 0.27%   |
| ASUSTek Computer                | 12        | 0.23%   |
| Fibocom                         | 10        | 0.19%   |
| Hewlett-Packard                 | 9         | 0.17%   |
| NetGear                         | 7         | 0.13%   |
| Qualcomm Atheros Communications | 6         | 0.11%   |
| Linksys                         | 4         | 0.08%   |
| Edimax Technology               | 4         | 0.08%   |
| D-Link System                   | 4         | 0.08%   |
| Microsoft                       | 3         | 0.06%   |
| D-Link                          | 2         | 0.04%   |
| Belkin Components               | 2         | 0.04%   |
| TRENDnet                        | 1         | 0.02%   |
| Quectel Wireless Solutions      | 1         | 0.02%   |
| IMC Networks                    | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 397       | 7.53%   |
| Intel Wireless 8265 / 8275                                     | 348       | 6.6%    |
| Intel Wi-Fi 6 AX201                                            | 226       | 4.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 223       | 4.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 208       | 3.94%   |
| Intel Wireless 8260                                            | 199       | 3.77%   |
| Intel Wireless 7260                                            | 185       | 3.51%   |
| Intel Wireless 7265                                            | 175       | 3.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 151       | 2.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 149       | 2.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 137       | 2.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 136       | 2.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 135       | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 132       | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 126       | 2.39%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 123       | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 118       | 2.24%   |
| Intel Wireless 3165                                            | 96        | 1.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 91        | 1.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 82        | 1.56%   |
| Intel Wireless-AC 9260                                         | 82        | 1.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 75        | 1.42%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 72        | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 70        | 1.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 70        | 1.33%   |
| Intel Centrino Ultimate-N 6300                                 | 62        | 1.18%   |
| Intel Wireless 3160                                            | 60        | 1.14%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 60        | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 56        | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                  | 48        | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 45        | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 41        | 0.78%   |
| Intel Centrino Advanced-N 6235                                 | 37        | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 34        | 0.64%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 31        | 0.59%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 30        | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 28        | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 27        | 0.51%   |
| Intel Centrino Advanced-N 6200                                 | 27        | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 26        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2242      | 55.03%  |
| Intel                            | 1184      | 29.06%  |
| Qualcomm Atheros                 | 194       | 4.76%   |
| Broadcom                         | 110       | 2.7%    |
| Lenovo                           | 73        | 1.79%   |
| ASIX Electronics                 | 47        | 1.15%   |
| Marvell Technology Group         | 32        | 0.79%   |
| DisplayLink                      | 32        | 0.79%   |
| Broadcom Limited                 | 21        | 0.52%   |
| TP-Link                          | 17        | 0.42%   |
| Samsung Electronics              | 17        | 0.42%   |
| Nvidia                           | 17        | 0.42%   |
| Xiaomi                           | 12        | 0.29%   |
| Apple                            | 12        | 0.29%   |
| Google                           | 9         | 0.22%   |
| JMicron Technology               | 8         | 0.2%    |
| Huawei Technologies              | 7         | 0.17%   |
| Qualcomm                         | 6         | 0.15%   |
| MediaTek                         | 5         | 0.12%   |
| OPPO Electronics                 | 4         | 0.1%    |
| OnePlus Technology (Shenzhen)    | 3         | 0.07%   |
| D-Link                           | 3         | 0.07%   |
| Cypress Semiconductor            | 3         | 0.07%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| vivo                             | 1         | 0.02%   |
| T & A Mobile Phones              | 1         | 0.02%   |
| Spreadtrum Communications        | 1         | 0.02%   |
| Novatel Wireless                 | 1         | 0.02%   |
| NetGear                          | 1         | 0.02%   |
| Motorola PCS                     | 1         | 0.02%   |
| Linksys                          | 1         | 0.02%   |
| LG Electronics                   | 1         | 0.02%   |
| HMD Global                       | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| ASUSTek Computer                 | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1582      | 38.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 344       | 8.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 281       | 6.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 210       | 5.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 124       | 3%      |
| Intel Ethernet Connection I219-LM                                 | 81        | 1.96%   |
| Intel Ethernet Connection (4) I219-V                              | 79        | 1.91%   |
| Intel Ethernet Connection I218-LM                                 | 66        | 1.59%   |
| Intel Ethernet Connection (6) I219-V                              | 61        | 1.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 59        | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 54        | 1.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 52        | 1.26%   |
| Intel Ethernet Connection (10) I219-V                             | 47        | 1.14%   |
| Intel Ethernet Connection (6) I219-LM                             | 45        | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                     | 42        | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 36        | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                             | 33        | 0.8%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 32        | 0.77%   |
| Intel Ethernet Connection I219-V                                  | 32        | 0.77%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 27        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 27        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 26        | 0.63%   |
| Intel Ethernet Connection (7) I219-V                              | 25        | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 22        | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 22        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.53%   |
| Intel Ethernet Connection (13) I219-V                             | 22        | 0.53%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 21        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 21        | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 20        | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 20        | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 19        | 0.46%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.39%   |
| Lenovo ThinkPad TBT3 LAN                                          | 16        | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                             | 15        | 0.36%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 14        | 0.34%   |
| Nvidia MCP79 Ethernet                                             | 14        | 0.34%   |
| Intel 82567LM Gigabit Network Connection                          | 14        | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 13        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5000      | 56.1%   |
| Ethernet | 3839      | 43.07%  |
| Modem    | 65        | 0.73%   |
| Unknown  | 9         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4357      | 79.99%  |
| Ethernet | 1088      | 19.97%  |
| Modem    | 2         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3463      | 67.85%  |
| 1     | 1483      | 29.06%  |
| 0     | 100       | 1.96%   |
| 3     | 58        | 1.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 4356      | 83.82%  |
| Yes     | 838       | 16.12%  |
| Unknown | 3         | 0.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2496      | 58.28%  |
| Qualcomm Atheros Communications | 408       | 9.53%   |
| Realtek Semiconductor           | 389       | 9.08%   |
| Broadcom                        | 180       | 4.2%    |
| IMC Networks                    | 172       | 4.02%   |
| Lite-On Technology              | 162       | 3.78%   |
| Foxconn / Hon Hai               | 138       | 3.22%   |
| Apple                           | 111       | 2.59%   |
| Realtek                         | 44        | 1.03%   |
| Cambridge Silicon Radio         | 39        | 0.91%   |
| Dell                            | 33        | 0.77%   |
| Ralink                          | 26        | 0.61%   |
| Hewlett-Packard                 | 22        | 0.51%   |
| Toshiba                         | 17        | 0.4%    |
| ASUSTek Computer                | 14        | 0.33%   |
| Foxconn International           | 9         | 0.21%   |
| Ralink Technology               | 4         | 0.09%   |
| Opticis                         | 3         | 0.07%   |
| MediaTek                        | 3         | 0.07%   |
| Alps Electric                   | 3         | 0.07%   |
| Unknown                         | 2         | 0.05%   |
| Qcom                            | 2         | 0.05%   |
| Chicony Electronics             | 2         | 0.05%   |
| USI                             | 1         | 0.02%   |
| Taiyo Yuden                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 984       | 22.96%  |
| Intel AX201 Bluetooth                               | 467       | 10.9%   |
| Intel AX200 Bluetooth                               | 386       | 9.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 374       | 8.73%   |
| Realtek Bluetooth Radio                             | 253       | 5.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 235       | 5.48%   |
| Realtek  Bluetooth 4.2 Adapter                      | 99        | 2.31%   |
| Apple Bluetooth Host Controller                     | 81        | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 72        | 1.68%   |
| Intel AX210 Bluetooth                               | 70        | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 68        | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 62        | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 60        | 1.4%    |
| IMC Networks Wireless_Device                        | 57        | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 54        | 1.26%   |
| IMC Networks Bluetooth Radio                        | 52        | 1.21%   |
| Realtek Bluetooth Radio                             | 44        | 1.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 44        | 1.03%   |
| Lite-On Bluetooth Device                            | 41        | 0.96%   |
| Foxconn / Hon Hai Wireless_Device                   | 41        | 0.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 39        | 0.91%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 37        | 0.86%   |
| Intel Bluetooth Device                              | 36        | 0.84%   |
| Broadcom BCM2045B (BDC-2.1)                         | 33        | 0.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 32        | 0.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 31        | 0.72%   |
| Ralink RT3290 Bluetooth                             | 26        | 0.61%   |
| IMC Networks Bluetooth Device                       | 26        | 0.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 22        | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 21        | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 0.49%   |
| Apple Bluetooth USB Host Controller                 | 19        | 0.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 0.42%   |
| HP Broadcom 2070 Bluetooth Combo                    | 17        | 0.4%    |
| Dell DW375 Bluetooth Module                         | 16        | 0.37%   |
| Realtek RTL8821A Bluetooth                          | 14        | 0.33%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.33%   |
| Lite-On Wireless_Device                             | 13        | 0.3%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.28%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 4074      | 62.22%  |
| AMD                         | 982       | 15%     |
| Nvidia                      | 867       | 13.24%  |
| Lenovo                      | 85        | 1.3%    |
| Realtek Semiconductor       | 66        | 1.01%   |
| C-Media Electronics         | 62        | 0.95%   |
| GN Netcom                   | 46        | 0.7%    |
| Logitech                    | 37        | 0.57%   |
| Plantronics                 | 30        | 0.46%   |
| Hewlett-Packard             | 23        | 0.35%   |
| JMTek                       | 18        | 0.27%   |
| Texas Instruments           | 14        | 0.21%   |
| Creative Technology         | 13        | 0.2%    |
| SteelSeries ApS             | 11        | 0.17%   |
| Kingston Technology         | 11        | 0.17%   |
| Apple                       | 11        | 0.17%   |
| Sennheiser Communications   | 10        | 0.15%   |
| Razer USA                   | 10        | 0.15%   |
| Sony                        | 9         | 0.14%   |
| Corsair                     | 9         | 0.14%   |
| Generalplus Technology      | 8         | 0.12%   |
| Samson Technologies         | 7         | 0.11%   |
| RODE Microphones            | 7         | 0.11%   |
| Blue Microphones            | 7         | 0.11%   |
| XMOS                        | 6         | 0.09%   |
| Dell                        | 6         | 0.09%   |
| Conexant Systems            | 6         | 0.09%   |
| CMX Systems                 | 6         | 0.09%   |
| SAVITECH                    | 5         | 0.08%   |
| Microsoft                   | 5         | 0.08%   |
| Tenx Technology             | 4         | 0.06%   |
| Samsung Electronics         | 4         | 0.06%   |
| No brand                    | 4         | 0.06%   |
| GYROCOM C&C                 | 4         | 0.06%   |
| FiiO Electronics Technology | 4         | 0.06%   |
| ASUSTek Computer            | 4         | 0.06%   |
| PreSonus Audio Electronics  | 3         | 0.05%   |
| M-Audio                     | 3         | 0.05%   |
| Focusrite-Novation          | 3         | 0.05%   |
| FIFINE Microphones          | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 876       | 11%     |
| AMD Family 17h/19h HD Audio Controller                                     | 722       | 9.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 390       | 4.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 369       | 4.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 303       | 3.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 301       | 3.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 250       | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 233       | 2.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 231       | 2.9%    |
| Intel Haswell-ULT HD Audio Controller                                      | 209       | 2.62%   |
| Intel 8 Series HD Audio Controller                                         | 209       | 2.62%   |
| Intel Comet Lake PCH-LP cAVS                                               | 201       | 2.52%   |
| Intel Broadwell-U Audio Controller                                         | 197       | 2.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 195       | 2.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 191       | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 157       | 1.97%   |
| Intel Comet Lake PCH cAVS                                                  | 141       | 1.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 131       | 1.65%   |
| Intel CM238 HD Audio Controller                                            | 122       | 1.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 122       | 1.53%   |
| Nvidia GP107GL High Definition Audio Controller                            | 117       | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 103       | 1.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 95        | 1.19%   |
| AMD FCH Azalia Controller                                                  | 88        | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                   | 71        | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 68        | 0.85%   |
| Realtek Semiconductor USB Audio                                            | 65        | 0.82%   |
| Nvidia GA106 High Definition Audio Controller                              | 61        | 0.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 60        | 0.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 58        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 56        | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 54        | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                         | 52        | 0.65%   |
| Nvidia TU116 High Definition Audio Controller                              | 49        | 0.62%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 45        | 0.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 44        | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 41        | 0.51%   |
| Nvidia GA104 High Definition Audio Controller                              | 35        | 0.44%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 34        | 0.43%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 33        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 961       | 29.59%  |
| SK hynix                                         | 732       | 22.54%  |
| Micron Technology                                | 454       | 13.98%  |
| Kingston                                         | 280       | 8.62%   |
| Crucial                                          | 180       | 5.54%   |
| Unknown                                          | 176       | 5.42%   |
| Ramaxel Technology                               | 79        | 2.43%   |
| A-DATA Technology                                | 74        | 2.28%   |
| Corsair                                          | 47        | 1.45%   |
| Elpida                                           | 29        | 0.89%   |
| Smart                                            | 25        | 0.77%   |
| Unknown (ABCD)                                   | 22        | 0.68%   |
| G.Skill                                          | 21        | 0.65%   |
| Team                                             | 16        | 0.49%   |
| Patriot                                          | 16        | 0.49%   |
| Nanya Technology                                 | 16        | 0.49%   |
| Unknown                                          | 13        | 0.4%    |
| Smart Brazil                                     | 11        | 0.34%   |
| Teikon                                           | 9         | 0.28%   |
| GOODRAM                                          | 9         | 0.28%   |
| Transcend                                        | 8         | 0.25%   |
| Avant                                            | 8         | 0.25%   |
| Goldkey                                          | 5         | 0.15%   |
| Silicon Power                                    | 4         | 0.12%   |
| Apacer                                           | 4         | 0.12%   |
| OnBoard                                          | 3         | 0.09%   |
| Kllisre                                          | 3         | 0.09%   |
| CSX                                              | 3         | 0.09%   |
| SHARETRONIC                                      | 2         | 0.06%   |
| Sesame                                           | 2         | 0.06%   |
| RZX                                              | 2         | 0.06%   |
| Qimonda                                          | 2         | 0.06%   |
| PNY                                              | 2         | 0.06%   |
| Memox                                            | 2         | 0.06%   |
| ChangXin Memory                                  | 2         | 0.06%   |
| ASint Technology                                 | 2         | 0.06%   |
| V-GEN                                            | 1         | 0.03%   |
| Uroad                                            | 1         | 0.03%   |
| Unknown (0x7301)                                 | 1         | 0.03%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 60        | 1.75%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 59        | 1.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 47        | 1.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 39        | 1.14%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 32        | 0.94%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 29        | 0.85%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 27        | 0.79%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 26        | 0.76%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 24        | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 24        | 0.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 24        | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 24        | 0.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.67%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 23        | 0.67%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 22        | 0.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 21        | 0.61%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.61%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 21        | 0.61%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 21        | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 20        | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 20        | 0.58%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 20        | 0.58%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 20        | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.53%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 18        | 0.53%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 18        | 0.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 0.53%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 18        | 0.53%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 16        | 0.47%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 16        | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 16        | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1532      | 56.64%  |
| DDR3    | 750       | 27.73%  |
| LPDDR3  | 170       | 6.28%   |
| LPDDR4  | 141       | 5.21%   |
| DDR2    | 36        | 1.33%   |
| DDR5    | 22        | 0.81%   |
| LPDDR5  | 19        | 0.7%    |
| SDRAM   | 17        | 0.63%   |
| Unknown | 14        | 0.52%   |
| DDR     | 3         | 0.11%   |
| DRAM    | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2332      | 84.49%  |
| Row Of Chips | 356       | 12.9%   |
| Chip         | 44        | 1.59%   |
| DIMM         | 18        | 0.65%   |
| Unknown      | 10        | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1237      | 41.99%  |
| 4096  | 829       | 28.14%  |
| 16384 | 530       | 17.99%  |
| 2048  | 217       | 7.37%   |
| 32768 | 92        | 3.12%   |
| 1024  | 37        | 1.26%   |
| 3072  | 2         | 0.07%   |
| 512   | 1         | 0.03%   |
| 64    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 723       | 24.72%  |
| 3200    | 593       | 20.27%  |
| 1600    | 542       | 18.53%  |
| 2400    | 246       | 8.41%   |
| 2133    | 219       | 7.49%   |
| 1333    | 98        | 3.35%   |
| 1334    | 90        | 3.08%   |
| 4267    | 69        | 2.36%   |
| 1867    | 65        | 2.22%   |
| 3266    | 47        | 1.61%   |
| 1067    | 33        | 1.13%   |
| 4800    | 28        | 0.96%   |
| Unknown | 25        | 0.85%   |
| 667     | 23        | 0.79%   |
| 8400    | 22        | 0.75%   |
| 6400    | 21        | 0.72%   |
| 4266    | 15        | 0.51%   |
| 4199    | 14        | 0.48%   |
| 1066    | 13        | 0.44%   |
| 3733    | 10        | 0.34%   |
| 800     | 10        | 0.34%   |
| 2933    | 5         | 0.17%   |
| 975     | 3         | 0.1%    |
| 533     | 2         | 0.07%   |
| 3400    | 1         | 0.03%   |
| 2800    | 1         | 0.03%   |
| 2048    | 1         | 0.03%   |
| 1866    | 1         | 0.03%   |
| 1777    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1200    | 1         | 0.03%   |
| 333     | 1         | 0.03%   |
| 133     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 25%     |
| Canon               | 7         | 21.88%  |
| Samsung Electronics | 6         | 18.75%  |
| Seiko Epson         | 3         | 9.38%   |
| Brother Industries  | 3         | 9.38%   |
| Prolific Technology | 2         | 6.25%   |
| Ricoh               | 1         | 3.13%   |
| Pantum              | 1         | 3.13%   |
| NXP Semiconductors  | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port        | 2         | 6.25%   |
| Seiko Epson WF-2830 Series           | 1         | 3.13%   |
| Seiko Epson L3150 Series             | 1         | 3.13%   |
| Seiko Epson L200 Series              | 1         | 3.13%   |
| Samsung SCX-4200 series              | 1         | 3.13%   |
| Samsung SCX-3200 Series              | 1         | 3.13%   |
| Samsung ML-331x Series Laser Printer | 1         | 3.13%   |
| Samsung M2070 Series                 | 1         | 3.13%   |
| Samsung CLX-6260 Series              | 1         | 3.13%   |
| Samsung C43x Series                  | 1         | 3.13%   |
| Ricoh SP 212SUw                      | 1         | 3.13%   |
| Pantum P2500W series                 | 1         | 3.13%   |
| NXP Semiconductors Printer-80        | 1         | 3.13%   |
| HP Photosmart B010 series            | 1         | 3.13%   |
| HP LaserJet 400 colorMFP M475dw      | 1         | 3.13%   |
| HP ENVY Pro 6400 series              | 1         | 3.13%   |
| HP ENVY 4500 series                  | 1         | 3.13%   |
| HP Deskjet 3510 series               | 1         | 3.13%   |
| HP Deskjet 3050A                     | 1         | 3.13%   |
| HP DeskJet 2300 series               | 1         | 3.13%   |
| HP DeskJet 2130 series               | 1         | 3.13%   |
| Canon TR8500 series                  | 1         | 3.13%   |
| Canon TR150 series                   | 1         | 3.13%   |
| Canon PIXMA MG3600 Series            | 1         | 3.13%   |
| Canon PIXMA MG3500 Series            | 1         | 3.13%   |
| Canon PIXMA MG3000 series            | 1         | 3.13%   |
| Canon MF220 Series                   | 1         | 3.13%   |
| Canon iP7200 series                  | 1         | 3.13%   |
| Brother Printer                      | 1         | 3.13%   |
| Brother HL-5250DN Printer            | 1         | 3.13%   |
| Brother DCP-T220                     | 1         | 3.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 5         | 62.5%   |
| Seiko Epson | 3         | 37.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                     | 2         | 25%     |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 12.5%   |
| Seiko Epson GT-X770 [Perfection V500]       | 1         | 12.5%   |
| Seiko Epson ES-D400 [GT-S80]                | 1         | 12.5%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 12.5%   |
| Canon CanoScan N650U/N656U                  | 1         | 12.5%   |
| Canon CanoScan LiDE 210                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1191      | 24.83%  |
| IMC Networks                           | 571       | 11.91%  |
| Acer                                   | 455       | 9.49%   |
| Realtek Semiconductor                  | 436       | 9.09%   |
| Microdia                               | 425       | 8.86%   |
| Sunplus Innovation Technology          | 261       | 5.44%   |
| Quanta                                 | 248       | 5.17%   |
| Cheng Uei Precision Industry (Foxlink) | 195       | 4.07%   |
| Lite-On Technology                     | 152       | 3.17%   |
| Syntek                                 | 130       | 2.71%   |
| Logitech                               | 110       | 2.29%   |
| Apple                                  | 105       | 2.19%   |
| Suyin                                  | 82        | 1.71%   |
| Luxvisions Innotech Limited            | 62        | 1.29%   |
| Silicon Motion                         | 59        | 1.23%   |
| Alcor Micro                            | 36        | 0.75%   |
| Samsung Electronics                    | 35        | 0.73%   |
| Ricoh                                  | 31        | 0.65%   |
| Lenovo                                 | 20        | 0.42%   |
| Primax Electronics                     | 19        | 0.4%    |
| Sonix Technology                       | 13        | 0.27%   |
| Microsoft                              | 13        | 0.27%   |
| Importek                               | 13        | 0.27%   |
| Z-Star Microelectronics                | 10        | 0.21%   |
| DJKANA19IDX53W                         | 8         | 0.17%   |
| USB Camera                             | 7         | 0.15%   |
| Generalplus Technology                 | 7         | 0.15%   |
| ARC International                      | 7         | 0.15%   |
| SunplusIT                              | 6         | 0.13%   |
| KYE Systems (Mouse Systems)            | 6         | 0.13%   |
| ALi                                    | 6         | 0.13%   |
| Pixart Imaging                         | 5         | 0.1%    |
| Intel                                  | 5         | 0.1%    |
| Unknown                                | 4         | 0.08%   |
| WaveRider Communications               | 3         | 0.06%   |
| Tripath Technology                     | 3         | 0.06%   |
| Tobii Technology AB                    | 3         | 0.06%   |
| Razer USA                              | 3         | 0.06%   |
| MacroSilicon                           | 3         | 0.06%   |
| Genesys Logic                          | 3         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 409       | 8.45%   |
| Microdia Integrated_Webcam_HD                                              | 246       | 5.08%   |
| IMC Networks Integrated Camera                                             | 239       | 4.94%   |
| Realtek Integrated_Webcam_HD                                               | 194       | 4.01%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 136       | 2.81%   |
| Acer Integrated Camera                                                     | 133       | 2.75%   |
| Chicony HD Webcam                                                          | 125       | 2.58%   |
| Sunplus Integrated_Webcam_HD                                               | 116       | 2.4%    |
| Syntek Integrated Camera                                                   | 82        | 1.69%   |
| Lite-On Integrated Camera                                                  | 72        | 1.49%   |
| Chicony Integrated Camera (1280x720@30)                                    | 69        | 1.43%   |
| Quanta HD User Facing                                                      | 55        | 1.14%   |
| Acer SunplusIT Integrated Camera                                           | 52        | 1.07%   |
| Chicony HP HD Camera                                                       | 51        | 1.05%   |
| Acer Lenovo EasyCamera                                                     | 51        | 1.05%   |
| Quanta HP TrueVision HD Camera                                             | 45        | 0.93%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 43        | 0.89%   |
| Microdia Integrated Webcam                                                 | 37        | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 37        | 0.76%   |
| Chicony USB2.0 Camera                                                      | 36        | 0.74%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 35        | 0.72%   |
| Acer HD Webcam                                                             | 35        | 0.72%   |
| Realtek USB Camera                                                         | 34        | 0.7%    |
| Quanta HD Webcam                                                           | 34        | 0.7%    |
| Lite-On HP HD Camera                                                       | 34        | 0.7%    |
| Realtek Integrated Webcam                                                  | 32        | 0.66%   |
| Sunplus HD WebCam                                                          | 31        | 0.64%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 31        | 0.64%   |
| Logitech HD Pro Webcam C920                                                | 30        | 0.62%   |
| Apple Built-in iSight                                                      | 30        | 0.62%   |
| Acer BisonCam, NB Pro                                                      | 30        | 0.62%   |
| Realtek Integrated Webcam HD                                               | 29        | 0.6%    |
| Quanta HP HD Camera                                                        | 29        | 0.6%    |
| Chicony HP Wide Vision HD Camera                                           | 29        | 0.6%    |
| Chicony HP TrueVision HD Camera                                            | 29        | 0.6%    |
| Chicony USB2.0 HD UVC WebCam                                               | 27        | 0.56%   |
| Microdia Integrated Webcam HD                                              | 26        | 0.54%   |
| IMC Networks HD Camera                                                     | 26        | 0.54%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 26        | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 26        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 452       | 35.4%   |
| Validity Sensors           | 410       | 32.11%  |
| Shenzhen Goodix Technology | 199       | 15.58%  |
| Elan Microelectronics      | 75        | 5.87%   |
| Upek                       | 54        | 4.23%   |
| LighTuning Technology      | 46        | 3.6%    |
| AuthenTec                  | 27        | 2.11%   |
| Samsung Electronics        | 5         | 0.39%   |
| STMicroelectronics         | 4         | 0.31%   |
| Focal-systems.Corp         | 4         | 0.31%   |
| Dell                       | 1         | 0.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 222       | 17.37%  |
| Shenzhen Goodix  FingerPrint Device                                        | 112       | 8.76%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 94        | 7.36%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 81        | 6.34%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 80        | 6.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 52        | 4.07%   |
| Unknown                                                                    | 50        | 3.91%   |
| Elan ELAN:Fingerprint                                                      | 49        | 3.83%   |
| Shenzhen Goodix FingerPrint                                                | 47        | 3.68%   |
| Validity Sensors Synaptics WBDI                                            | 41        | 3.21%   |
| Shenzhen Goodix Fingerprint Reader                                         | 40        | 3.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 38        | 2.97%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 37        | 2.9%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 34        | 2.66%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 26        | 2.03%   |
| Elan ELAN:ARM-M4                                                           | 25        | 1.96%   |
| Validity Sensors VFS491                                                    | 23        | 1.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 22        | 1.72%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 22        | 1.72%   |
| Synaptics  WBDI                                                            | 19        | 1.49%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 1.33%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 1.25%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 15        | 1.17%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 13        | 1.02%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 1.02%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 0.86%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 0.78%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.63%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 6         | 0.47%   |
| Synaptics WBDI Device                                                      | 6         | 0.47%   |
| AuthenTec AES2810                                                          | 5         | 0.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.39%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.31%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.31%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.31%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.31%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.31%   |
| Samsung Fingerprint Device                                                 | 3         | 0.23%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.23%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.16%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 204       | 42.5%   |
| Broadcom                   | 187       | 38.96%  |
| Upek                       | 30        | 6.25%   |
| Lenovo                     | 26        | 5.42%   |
| O2 Micro                   | 11        | 2.29%   |
| Gemalto (was Gemplus)      | 5         | 1.04%   |
| SCM Microsystems           | 3         | 0.63%   |
| OmniKey                    | 3         | 0.63%   |
| Aladdin Knowledge Systems  | 3         | 0.63%   |
| Realtek Semiconductor      | 2         | 0.42%   |
| Yubico.com                 | 1         | 0.21%   |
| Reiner SCT Kartensysteme   | 1         | 0.21%   |
| Hewlett-Packard            | 1         | 0.21%   |
| Chicony Electronics        | 1         | 0.21%   |
| Athena Smartcard Solutions | 1         | 0.21%   |
| Advanced Card Systems      | 1         | 0.21%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 203       | 42.29%  |
| Broadcom 5880                                                                | 63        | 13.13%  |
| Broadcom BCM5880 Secure Applications Processor                               | 47        | 9.79%   |
| Broadcom 58200                                                               | 42        | 8.75%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 33        | 6.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 30        | 6.25%   |
| Lenovo Integrated Smart Card Reader                                          | 26        | 5.42%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 1.88%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 4         | 0.83%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.63%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.42%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 0.42%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.42%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.21%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.21%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.21%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.21%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.21%   |
| OmniKey CardMan 4321                                                         | 1         | 0.21%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.21%   |
| OmniKey CardMan 1021                                                         | 1         | 0.21%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.21%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.21%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.21%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.21%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.21%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.21%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3062      | 58.22%  |
| 1     | 1809      | 34.4%   |
| 2     | 331       | 6.29%   |
| 3     | 45        | 0.86%   |
| 4     | 5         | 0.1%    |
| 6     | 3         | 0.06%   |
| 5     | 3         | 0.06%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1264      | 49.41%  |
| Graphics card            | 427       | 16.69%  |
| Multimedia controller    | 222       | 8.68%   |
| Chipcard                 | 178       | 6.96%   |
| Net/wireless             | 175       | 6.84%   |
| Camera                   | 96        | 3.75%   |
| Bluetooth                | 52        | 2.03%   |
| Storage                  | 41        | 1.6%    |
| Card reader              | 35        | 1.37%   |
| Net/ethernet             | 16        | 0.63%   |
| Network                  | 14        | 0.55%   |
| Communication controller | 14        | 0.55%   |
| Sound                    | 12        | 0.47%   |
| Modem                    | 8         | 0.31%   |
| Flash memory             | 2         | 0.08%   |
| Video                    | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

