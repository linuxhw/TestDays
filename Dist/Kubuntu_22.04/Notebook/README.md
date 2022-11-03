Kubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

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

Total: 304

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Dell          | Latitude 5521               | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| Acer          | Aspire E5-571               | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| Acer          | Nitro AN517-51              | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| HP            | ProBook 450 G5              | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Precision M6700             | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| GPU Compan... | GWTC116-2                   | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| HP            | ZBook 15 G6                 | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| HP            | 255 G8 Notebook PC          | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Google        | Blooglet                    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Acer          | Aspire S3-391               | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Google        | Treeya                      | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| Dell          | G15 5511                    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| Dell          | Latitude 7430               | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Acer          | Predator G3-571             | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Samsung       | 270E5G/270E5U               | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| HP            | Notebook                    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| Dell          | Latitude 9420               | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| Apple         | MacBookPro11,1              | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Toshiba       | Satellite P70-B             | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| MSI           | GF75 Thin 10SCXR            | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Apple         | MacBookPro11,1              | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Dell          | Precision 3571              | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| Dell          | Latitude 5590               | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | EliteBook 8470p             | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Dell          | Latitude 5420               | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| Dell          | XPS 15 9520                 | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Dell          | Latitude 5590               | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Intel         | Unknown                     | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| Dell          | Latitude 5590               | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Unknown       | Unknown                     | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| Toshiba       | TECRA S11                   | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Chuwi         | CoreBook X                  | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| Dell          | Latitude 7530               | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Jumper        | EZpad                       | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Haier         | A1420EM                     | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Dell          | Latitude 5590               | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Lenovo        | V130-15IGM 81HL             | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Apple         | MacBookPro15,2              | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| Toshiba       | Satellite L655              | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| Apple         | MacBookPro5,3               | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| Jumper        | EZpad                       | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 15-3567            | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | Pavilion dv6                | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| System76      | Kudu Professional           | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| Dell          | Latitude 5590               | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| MSI           | CX61 2PC                    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| Dell          | Latitude 7420               | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| HUAWEI        | CREM-WXX9                   | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| HP            | ProBook 6470b               | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| HP            | Unknown                     | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| HP            | ProBook 6570b               | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Apple         | MacBookPro13,2              | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| HUAWEI        | CREM-WXX9                   | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| Dell          | XPS 13 9370                 | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite C650D             | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| HP            | ProBook 6470b               | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| Apple         | MacBookPro11,2              | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | 2000                        | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| Toshiba       | Satellite C650D             | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| Lenovo        | Z50-75 80EC                 | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Acer          | Swift SF314-43              | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| ASUSTek       | G550JK                      | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Shanghai Z... | ZXE CRB                     | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6540              | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| Timi          | Mi Laptop Air 12.5          | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| Dell          | Latitude E6320              | [ae7b660be1](https://linux-hardware.org/?probe=ae7b660be1) | Feb 16, 2022 |
| Apple         | MacBookPro8,1               | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [aba110f180](https://linux-hardware.org/?probe=aba110f180) | Feb 10, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| Unknown       | Unknown                     | [d88cb8b5ae](https://linux-hardware.org/?probe=d88cb8b5ae) | Dec 27, 2021 |
| HP            | Laptop 15s-eq0xxx           | [5bb4e443f9](https://linux-hardware.org/?probe=5bb4e443f9) | Oct 26, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.15.0-48-generic       | 22        | 8.98%   |
| 5.15.0-47-generic       | 21        | 8.57%   |
| 5.15.0-52-generic       | 20        | 8.16%   |
| 5.15.0-46-generic       | 17        | 6.94%   |
| 5.15.0-41-generic       | 17        | 6.94%   |
| 5.15.0-40-generic       | 15        | 6.12%   |
| 5.15.0-25-generic       | 13        | 5.31%   |
| 5.15.0-50-generic       | 12        | 4.9%    |
| 5.15.0-27-generic       | 12        | 4.9%    |
| 5.15.0-43-generic       | 11        | 4.49%   |
| 5.15.0-33-generic       | 10        | 4.08%   |
| 5.15.0-39-generic       | 6         | 2.45%   |
| 5.15.0-37-generic       | 5         | 2.04%   |
| 5.15.0-43-lowlatency    | 4         | 1.63%   |
| 5.15.0-35-generic       | 4         | 1.63%   |
| 5.15.0-30-generic       | 4         | 1.63%   |
| 5.15.0-18-generic       | 4         | 1.63%   |
| 5.15.0-46-lowlatency    | 3         | 1.22%   |
| 5.19.5-051905-generic   | 2         | 0.82%   |
| 5.15.0-52-lowlatency    | 2         | 0.82%   |
| 5.15.0-48-lowlatency    | 2         | 0.82%   |
| 5.15.0-32-generic       | 2         | 0.82%   |
| 5.15.0-30-lowlatency    | 2         | 0.82%   |
| 5.15.0-23-generic       | 2         | 0.82%   |
| 5.15.0-10033-tuxedo     | 2         | 0.82%   |
| 5.13.0-19-generic       | 2         | 0.82%   |
| 6.0.1-060001-generic    | 1         | 0.41%   |
| 6.0.0-t2                | 1         | 0.41%   |
| 6.0.0-060000rc3-generic | 1         | 0.41%   |
| 5.19.2-051902-generic   | 1         | 0.41%   |
| 5.19.11-051911-generic  | 1         | 0.41%   |
| 5.18.6-051806-generic   | 1         | 0.41%   |
| 5.18.15-051815-generic  | 1         | 0.41%   |
| 5.18.10-051810-generic  | 1         | 0.41%   |
| 5.17.5-051705-generic   | 1         | 0.41%   |
| 5.17.4-051704-generic   | 1         | 0.41%   |
| 5.17.2-051702-generic   | 1         | 0.41%   |
| 5.17.0-1020-oem         | 1         | 0.41%   |
| 5.17.0-1017-oem         | 1         | 0.41%   |
| 5.17.0-1016-oem         | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 211       | 89.79%  |
| 5.17.0  | 4         | 1.7%    |
| 5.13.0  | 3         | 1.28%   |
| 6.0.0   | 2         | 0.85%   |
| 5.19.5  | 2         | 0.85%   |
| 6.0.1   | 1         | 0.43%   |
| 5.19.2  | 1         | 0.43%   |
| 5.19.11 | 1         | 0.43%   |
| 5.18.6  | 1         | 0.43%   |
| 5.18.15 | 1         | 0.43%   |
| 5.18.10 | 1         | 0.43%   |
| 5.17.5  | 1         | 0.43%   |
| 5.17.4  | 1         | 0.43%   |
| 5.17.2  | 1         | 0.43%   |
| 5.16.2  | 1         | 0.43%   |
| 5.16.11 | 1         | 0.43%   |
| 5.15.65 | 1         | 0.43%   |
| 5.15.34 | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 212       | 90.6%   |
| 5.17    | 7         | 2.99%   |
| 5.19    | 4         | 1.71%   |
| 6.0     | 3         | 1.28%   |
| 5.18    | 3         | 1.28%   |
| 5.13    | 3         | 1.28%   |
| 5.16    | 2         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 232       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 227       | 97.42%  |
| GNOME      | 2         | 0.86%   |
| X-Cinnamon | 1         | 0.43%   |
| MATE       | 1         | 0.43%   |
| i3         | 1         | 0.43%   |
| GNUstep    | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 216       | 93.1%   |
| Wayland | 13        | 5.6%    |
| Tty     | 3         | 1.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 174       | 75%     |
| Unknown | 40        | 17.24%  |
| GDM3    | 12        | 5.17%   |
| LightDM | 4         | 1.72%   |
| SLiM    | 1         | 0.43%   |
| LXDM    | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 122       | 52.36%  |
| it_IT   | 16        | 6.87%   |
| de_DE   | 13        | 5.58%   |
| ru_RU   | 11        | 4.72%   |
| en_GB   | 9         | 3.86%   |
| fr_FR   | 8         | 3.43%   |
| pl_PL   | 6         | 2.58%   |
| en_IN   | 6         | 2.58%   |
| en_AU   | 6         | 2.58%   |
| es_ES   | 5         | 2.15%   |
| en_CA   | 4         | 1.72%   |
| hu_HU   | 3         | 1.29%   |
| en_PH   | 3         | 1.29%   |
| en_NZ   | 3         | 1.29%   |
| pt_BR   | 2         | 0.86%   |
| es_CL   | 2         | 0.86%   |
| en_SG   | 2         | 0.86%   |
| Default | 2         | 0.86%   |
| tr_TR   | 1         | 0.43%   |
| sl_SI   | 1         | 0.43%   |
| ru_UA   | 1         | 0.43%   |
| nl_BE   | 1         | 0.43%   |
| ko_KR   | 1         | 0.43%   |
| et_EE   | 1         | 0.43%   |
| es_MX   | 1         | 0.43%   |
| es_EC   | 1         | 0.43%   |
| es_CR   | 1         | 0.43%   |
| en_ZA   | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 135       | 57.45%  |
| BIOS | 100       | 42.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 213       | 91.42%  |
| Overlay | 10        | 4.29%   |
| Btrfs   | 7         | 3%      |
| Xfs     | 2         | 0.86%   |
| Ext2    | 1         | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 149       | 63.68%  |
| Unknown | 77        | 32.91%  |
| MBR     | 8         | 3.42%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 217       | 93.53%  |
| Yes       | 15        | 6.47%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 141       | 60.52%  |
| Yes       | 92        | 39.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 59        | 25.43%  |
| Hewlett-Packard                | 42        | 18.1%   |
| Dell                           | 33        | 14.22%  |
| ASUSTek Computer               | 22        | 9.48%   |
| Acer                           | 14        | 6.03%   |
| Apple                          | 8         | 3.45%   |
| Toshiba                        | 6         | 2.59%   |
| Samsung Electronics            | 5         | 2.16%   |
| MSI                            | 5         | 2.16%   |
| HUAWEI                         | 5         | 2.16%   |
| TUXEDO                         | 3         | 1.29%   |
| Google                         | 3         | 1.29%   |
| System76                       | 2         | 0.86%   |
| Sony                           | 2         | 0.86%   |
| Panasonic                      | 2         | 0.86%   |
| HONOR                          | 2         | 0.86%   |
| Gigabyte Technology            | 2         | 0.86%   |
| Unknown                        | 2         | 0.86%   |
| Timi                           | 1         | 0.43%   |
| Tactus                         | 1         | 0.43%   |
| Standard                       | 1         | 0.43%   |
| SLIMBOOK                       | 1         | 0.43%   |
| SK hynix                       | 1         | 0.43%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.43%   |
| Schenker                       | 1         | 0.43%   |
| Razer                          | 1         | 0.43%   |
| Notebook                       | 1         | 0.43%   |
| LG Electronics                 | 1         | 0.43%   |
| Jumper                         | 1         | 0.43%   |
| Intel                          | 1         | 0.43%   |
| Haier                          | 1         | 0.43%   |
| GPU Company                    | 1         | 0.43%   |
| Chuwi                          | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 5         | 2.16%   |
| Lenovo IdeaPad 5 15ARE05 81YQ   | 2         | 0.86%   |
| HUAWEI CREM-WXX9                | 2         | 0.86%   |
| HP ProBook 6470b                | 2         | 0.86%   |
| HP ProBook 440 G8 Notebook PC   | 2         | 0.86%   |
| HP Pavilion Laptop 15-eh1xxx    | 2         | 0.86%   |
| HP Pavilion g6                  | 2         | 0.86%   |
| HP Pavilion dv6                 | 2         | 0.86%   |
| HP OMEN Laptop 15-en0xxx        | 2         | 0.86%   |
| HP EliteBook 845 G7 Notebook PC | 2         | 0.86%   |
| HP 255 G8 Notebook PC           | 2         | 0.86%   |
| Dell XPS 15 9560                | 2         | 0.86%   |
| Acer Aspire E5-575G             | 2         | 0.86%   |
| TUXEDO Stellaris AMD Gen3 (CZN) | 1         | 0.43%   |
| TUXEDO Polaris 15 AMD Gen1      | 1         | 0.43%   |
| TUXEDO InfinityBook S 15 Gen6   | 1         | 0.43%   |
| Toshiba TECRA S11               | 1         | 0.43%   |
| Toshiba Satellite P70-B         | 1         | 0.43%   |
| Toshiba Satellite NB10t-A-102   | 1         | 0.43%   |
| Toshiba Satellite L850          | 1         | 0.43%   |
| Toshiba Satellite L655          | 1         | 0.43%   |
| Toshiba Satellite C650D         | 1         | 0.43%   |
| Timi Mi Laptop Air 12.5         | 1         | 0.43%   |
| Tactus GeoBook 140              | 1         | 0.43%   |
| System76 Lemur Ultra            | 1         | 0.43%   |
| System76 Kudu Professional      | 1         | 0.43%   |
| Sony VGN-NR11Z_T                | 1         | 0.43%   |
| Sony SVE1512J6EW                | 1         | 0.43%   |
| SLIMBOOK PROX15-AMD             | 1         | 0.43%   |
| SK hynix Onnyx III              | 1         | 0.43%   |
| Shanghai Zhaoxin ZXE CRB        | 1         | 0.43%   |
| Schenker XMG APEX (Mid 2021)    | 1         | 0.43%   |
| Samsung R430/P430/R480          | 1         | 0.43%   |
| Samsung 870Z5E/880Z5E/680Z5E    | 1         | 0.43%   |
| Samsung 767XCL                  | 1         | 0.43%   |
| Samsung 300E4C/300E5C/300E7C    | 1         | 0.43%   |
| Samsung 270E5G/270E5U           | 1         | 0.43%   |
| Razer Blade 15 Mid 2019-Base    | 1         | 0.43%   |
| Panasonic CF-53JSWZGFF          | 1         | 0.43%   |
| Panasonic CF-31WBLEHLM          | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 23        | 9.91%   |
| Lenovo IdeaPad       | 17        | 7.33%   |
| Dell Latitude        | 13        | 5.6%    |
| HP Pavilion          | 11        | 4.74%   |
| HP ProBook           | 8         | 3.45%   |
| Acer Aspire          | 8         | 3.45%   |
| Lenovo ThinkBook     | 6         | 2.59%   |
| Dell XPS             | 6         | 2.59%   |
| Dell Inspiron        | 6         | 2.59%   |
| Toshiba Satellite    | 5         | 2.16%   |
| HP Laptop            | 5         | 2.16%   |
| HP EliteBook         | 5         | 2.16%   |
| ASUS VivoBook        | 5         | 2.16%   |
| Unknown              | 5         | 2.16%   |
| Lenovo Legion        | 4         | 1.72%   |
| ASUS ROG             | 4         | 1.72%   |
| HP OMEN              | 3         | 1.29%   |
| Dell Vostro          | 3         | 1.29%   |
| Lenovo Yoga          | 2         | 0.86%   |
| HUAWEI CREM-WXX9     | 2         | 0.86%   |
| HP 255               | 2         | 0.86%   |
| Dell Precision       | 2         | 0.86%   |
| Apple MacBookPro11   | 2         | 0.86%   |
| Acer Swift           | 2         | 0.86%   |
| Acer Predator        | 2         | 0.86%   |
| Acer Nitro           | 2         | 0.86%   |
| TUXEDO Stellaris     | 1         | 0.43%   |
| TUXEDO Polaris       | 1         | 0.43%   |
| TUXEDO InfinityBook  | 1         | 0.43%   |
| Toshiba TECRA        | 1         | 0.43%   |
| Timi Mi              | 1         | 0.43%   |
| Tactus GeoBook       | 1         | 0.43%   |
| System76 Lemur       | 1         | 0.43%   |
| System76 Kudu        | 1         | 0.43%   |
| Sony VGN-NR11Z       | 1         | 0.43%   |
| Sony SVE1512J6EW     | 1         | 0.43%   |
| SLIMBOOK PROX15-AMD  | 1         | 0.43%   |
| SK hynix Onnyx       | 1         | 0.43%   |
| Shanghai Zhaoxin ZXE | 1         | 0.43%   |
| Schenker XMG         | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 52        | 22.41%  |
| 2020 | 45        | 19.4%   |
| 2022 | 20        | 8.62%   |
| 2012 | 20        | 8.62%   |
| 2019 | 17        | 7.33%   |
| 2016 | 11        | 4.74%   |
| 2014 | 10        | 4.31%   |
| 2011 | 10        | 4.31%   |
| 2018 | 9         | 3.88%   |
| 2017 | 9         | 3.88%   |
| 2013 | 9         | 3.88%   |
| 2015 | 8         | 3.45%   |
| 2010 | 6         | 2.59%   |
| 2008 | 3         | 1.29%   |
| 2007 | 2         | 0.86%   |
| 2009 | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 232       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 201       | 86.27%  |
| Enabled  | 32        | 13.73%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 229       | 98.71%  |
| Yes  | 3         | 1.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 66        | 28.21%  |
| 4.01-8.0    | 64        | 27.35%  |
| 8.01-16.0   | 55        | 23.5%   |
| 3.01-4.0    | 22        | 9.4%    |
| 32.01-64.0  | 14        | 5.98%   |
| 64.01-256.0 | 6         | 2.56%   |
| 24.01-32.0  | 4         | 1.71%   |
| 2.01-3.0    | 3         | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 68        | 27.98%  |
| 4.01-8.0  | 56        | 23.05%  |
| 3.01-4.0  | 54        | 22.22%  |
| 1.01-2.0  | 50        | 20.58%  |
| 8.01-16.0 | 14        | 5.76%   |
| 0.51-1.0  | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 155       | 65.96%  |
| 2      | 70        | 29.79%  |
| 3      | 7         | 2.98%   |
| 4      | 3         | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 188       | 81.03%  |
| Yes       | 44        | 18.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 170       | 73.28%  |
| No        | 62        | 26.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 231       | 99.57%  |
| No        | 1         | 0.43%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 203       | 87.12%  |
| No        | 30        | 12.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 38        | 16.38%  |
| Italy        | 23        | 9.91%   |
| Russia       | 20        | 8.62%   |
| Germany      | 17        | 7.33%   |
| France       | 13        | 5.6%    |
| Spain        | 8         | 3.45%   |
| Poland       | 8         | 3.45%   |
| UK           | 7         | 3.02%   |
| India        | 6         | 2.59%   |
| Indonesia    | 5         | 2.16%   |
| Hungary      | 5         | 2.16%   |
| Canada       | 5         | 2.16%   |
| Brazil       | 5         | 2.16%   |
| Australia    | 5         | 2.16%   |
| Philippines  | 4         | 1.72%   |
| Mexico       | 4         | 1.72%   |
| Estonia      | 4         | 1.72%   |
| Switzerland  | 3         | 1.29%   |
| Slovenia     | 3         | 1.29%   |
| New Zealand  | 3         | 1.29%   |
| Turkey       | 2         | 0.86%   |
| Sweden       | 2         | 0.86%   |
| Singapore    | 2         | 0.86%   |
| Netherlands  | 2         | 0.86%   |
| Ireland      | 2         | 0.86%   |
| Greece       | 2         | 0.86%   |
| Ecuador      | 2         | 0.86%   |
| Denmark      | 2         | 0.86%   |
| Czechia      | 2         | 0.86%   |
| China        | 2         | 0.86%   |
| Chile        | 2         | 0.86%   |
| Bulgaria     | 2         | 0.86%   |
| Vietnam      | 1         | 0.43%   |
| Ukraine      | 1         | 0.43%   |
| UAE          | 1         | 0.43%   |
| Thailand     | 1         | 0.43%   |
| Taiwan       | 1         | 0.43%   |
| South Korea  | 1         | 0.43%   |
| South Africa | 1         | 0.43%   |
| Serbia       | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Milan                   | 7         | 2.97%   |
| Moscow                  | 6         | 2.54%   |
| St Petersburg           | 4         | 1.69%   |
| Wroclaw                 | 3         | 1.27%   |
| Tallinn                 | 3         | 1.27%   |
| Paris                   | 3         | 1.27%   |
| Budapest                | 3         | 1.27%   |
| Berlin                  | 3         | 1.27%   |
| Bengaluru               | 3         | 1.27%   |
| Vladivostok             | 2         | 0.85%   |
| Turin                   | 2         | 0.85%   |
| Singapore               | 2         | 0.85%   |
| Sao Paulo               | 2         | 0.85%   |
| Quito                   | 2         | 0.85%   |
| Parma                   | 2         | 0.85%   |
| Murska Sobota           | 2         | 0.85%   |
| Marseille               | 2         | 0.85%   |
| Madrid                  | 2         | 0.85%   |
| Katerini                | 2         | 0.85%   |
| Jakarta                 | 2         | 0.85%   |
| Granozzo con Monticello | 2         | 0.85%   |
| Dublin                  | 2         | 0.85%   |
| Brooklyn                | 2         | 0.85%   |
| Auckland                | 2         | 0.85%   |
| Zurich                  | 1         | 0.42%   |
| Zagreb                  | 1         | 0.42%   |
| Ypsilanti               | 1         | 0.42%   |
| Yekaterinburg           | 1         | 0.42%   |
| Yangon                  | 1         | 0.42%   |
| Woodbine                | 1         | 0.42%   |
| Washington              | 1         | 0.42%   |
| Warsaw                  | 1         | 0.42%   |
| Walbach                 | 1         | 0.42%   |
| Vitoria-Gasteiz         | 1         | 0.42%   |
| Vilnius                 | 1         | 0.42%   |
| Vermilion               | 1         | 0.42%   |
| Varna                   | 1         | 0.42%   |
| Valdosta                | 1         | 0.42%   |
| Valdivia                | 1         | 0.42%   |
| Ufa                     | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 53        | 60     | 17.38%  |
| WDC                            | 31        | 36     | 10.16%  |
| SK hynix                       | 20        | 21     | 6.56%   |
| SanDisk                        | 20        | 22     | 6.56%   |
| Toshiba                        | 19        | 24     | 6.23%   |
| Kingston                       | 19        | 19     | 6.23%   |
| Unknown                        | 16        | 21     | 5.25%   |
| Seagate                        | 16        | 21     | 5.25%   |
| Intel                          | 12        | 14     | 3.93%   |
| Crucial                        | 11        | 12     | 3.61%   |
| Micron Technology              | 9         | 9      | 2.95%   |
| KIOXIA                         | 7         | 7      | 2.3%    |
| Hitachi                        | 6         | 6      | 1.97%   |
| HGST                           | 6         | 6      | 1.97%   |
| Apple                          | 6         | 7      | 1.97%   |
| China                          | 4         | 4      | 1.31%   |
| A-DATA Technology              | 4         | 4      | 1.31%   |
| SSSTC                          | 3         | 3      | 0.98%   |
| PNY                            | 3         | 3      | 0.98%   |
| Patriot                        | 3         | 3      | 0.98%   |
| LITEON                         | 3         | 3      | 0.98%   |
| Smart                          | 2         | 2      | 0.66%   |
| Silicon Motion                 | 2         | 2      | 0.66%   |
| Phison                         | 2         | 2      | 0.66%   |
| Netac                          | 2         | 2      | 0.66%   |
| Micron/Crucial Technology      | 2         | 3      | 0.66%   |
| LITEONIT                       | 2         | 2      | 0.66%   |
| Emtec                          | 2         | 2      | 0.66%   |
| Unknown                        | 2         | 2      | 0.66%   |
| Verbatim                       | 1         | 1      | 0.33%   |
| USB3.0                         | 1         | 1      | 0.33%   |
| UMIS                           | 1         | 1      | 0.33%   |
| Team                           | 1         | 1      | 0.33%   |
| Solid State Storage Technology | 1         | 2      | 0.33%   |
| SABRENT                        | 1         | 3      | 0.33%   |
| Realtek Semiconductor          | 1         | 1      | 0.33%   |
| Phison Electronics             | 1         | 1      | 0.33%   |
| Lexar                          | 1         | 1      | 0.33%   |
| KingSpec                       | 1         | 1      | 0.33%   |
| KESU                           | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 5         | 1.56%   |
| Toshiba MQ04ABF100 1TB                 | 3         | 0.94%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 0.94%   |
| SK hynix NVMe SSD Drive 512GB          | 3         | 0.94%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.94%   |
| Samsung SSD 980 PRO 1TB                | 3         | 0.94%   |
| Samsung SSD 970 EVO Plus 500GB         | 3         | 0.94%   |
| Samsung SSD 860 QVO 1TB                | 3         | 0.94%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.94%   |
| Samsung NVMe SSD Drive 512GB           | 3         | 0.94%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 0.94%   |
| Crucial CT500MX500SSD1 500GB           | 3         | 0.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 0.63%   |
| WDC WD10SPZX-24Z10 1TB                 | 2         | 0.63%   |
| WDC PC SN730 SDBPNTY-512G              | 2         | 0.63%   |
| Unknown MMC Card  64GB                 | 2         | 0.63%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 2         | 0.63%   |
| SK hynix PC801 NVMe 1TB                | 2         | 0.63%   |
| SK hynix HFS256G39TND-N210A 256GB SSD  | 2         | 0.63%   |
| SK hynix BC711 HFM512GD3JX013N 512GB   | 2         | 0.63%   |
| Seagate ST9750420AS 752GB              | 2         | 0.63%   |
| Seagate ST2000LM007-1R8174 2TB         | 2         | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.63%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB     | 2         | 0.63%   |
| Samsung SSD 970 EVO Plus 250GB         | 2         | 0.63%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 0.63%   |
| Samsung PM9A1 NVMe 512GB               | 2         | 0.63%   |
| Samsung MZVLB512HBJQ-000L2 512GB       | 2         | 0.63%   |
| Samsung MZVLB512HBJQ-000H1 512GB       | 2         | 0.63%   |
| Patriot Burst 240GB SSD                | 2         | 0.63%   |
| Micron 3400_MTFDKBA1T0TFH 1TB          | 2         | 0.63%   |
| Kingston SA400S37480G 480GB SSD        | 2         | 0.63%   |
| Kingston SA2000M81000G 1TB             | 2         | 0.63%   |
| Kingston OM8PDP3512B-AA1 512GB         | 2         | 0.63%   |
| HGST HTS545050A7E680 500GB             | 2         | 0.63%   |
| HGST HTS545050A7E380 500GB             | 2         | 0.63%   |
| Crucial CT500P2SSD8 500GB              | 2         | 0.63%   |
| Crucial CT1000BX500SSD1 1TB            | 2         | 0.63%   |
| Unknown                                | 2         | 0.63%   |
| WDC WDS480G2G0C-00AJM0 480GB           | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 15        | 20     | 28.3%   |
| WDC      | 11        | 11     | 20.75%  |
| Toshiba  | 10        | 12     | 18.87%  |
| Hitachi  | 6         | 6      | 11.32%  |
| HGST     | 6         | 6      | 11.32%  |
| USB3.0   | 1         | 1      | 1.89%   |
| Unknown  | 1         | 1      | 1.89%   |
| SABRENT  | 1         | 3      | 1.89%   |
| KESU     | 1         | 1      | 1.89%   |
| HGST HTS | 1         | 1      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 30     | 26.53%  |
| SanDisk             | 11        | 12     | 11.22%  |
| Kingston            | 11        | 11     | 11.22%  |
| Crucial             | 8         | 9      | 8.16%   |
| WDC                 | 4         | 7      | 4.08%   |
| Patriot             | 3         | 3      | 3.06%   |
| LITEON              | 3         | 3      | 3.06%   |
| Intel               | 3         | 3      | 3.06%   |
| China               | 3         | 3      | 3.06%   |
| Apple               | 3         | 3      | 3.06%   |
| A-DATA Technology   | 3         | 3      | 3.06%   |
| Smart               | 2         | 2      | 2.04%   |
| SK hynix            | 2         | 2      | 2.04%   |
| Netac               | 2         | 2      | 2.04%   |
| LITEONIT            | 2         | 2      | 2.04%   |
| Emtec               | 2         | 2      | 2.04%   |
| Verbatim            | 1         | 1      | 1.02%   |
| Toshiba             | 1         | 3      | 1.02%   |
| Team                | 1         | 1      | 1.02%   |
| PNY                 | 1         | 1      | 1.02%   |
| Micron Technology   | 1         | 1      | 1.02%   |
| KingSpec            | 1         | 1      | 1.02%   |
| Dogfish             | 1         | 1      | 1.02%   |
| Corsair             | 1         | 1      | 1.02%   |
| BAITITON            | 1         | 1      | 1.02%   |
| Unknown             | 1         | 1      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 122       | 148    | 43.88%  |
| SSD     | 85        | 109    | 30.58%  |
| HDD     | 51        | 62     | 18.35%  |
| MMC     | 17        | 21     | 6.12%   |
| Unknown | 3         | 3      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 121       | 147    | 45.66%  |
| SATA | 114       | 155    | 43.02%  |
| MMC  | 17        | 21     | 6.42%   |
| SAS  | 13        | 20     | 4.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 85        | 107    | 62.04%  |
| 0.51-1.0   | 43        | 50     | 31.39%  |
| 1.01-2.0   | 7         | 9      | 5.11%   |
| 3.01-4.0   | 1         | 4      | 0.73%   |
| 4.01-10.0  | 1         | 1      | 0.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 65        | 27.66%  |
| 101-250        | 58        | 24.68%  |
| 501-1000       | 45        | 19.15%  |
| 1001-2000      | 25        | 10.64%  |
| 51-100         | 19        | 8.09%   |
| 1-20           | 10        | 4.26%   |
| 21-50          | 5         | 2.13%   |
| More than 3000 | 4         | 1.7%    |
| 2001-3000      | 4         | 1.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 66        | 28.09%  |
| 101-250        | 44        | 18.72%  |
| 21-50          | 43        | 18.3%   |
| 251-500        | 33        | 14.04%  |
| 51-100         | 25        | 10.64%  |
| 501-1000       | 17        | 7.23%   |
| 1001-2000      | 5         | 2.13%   |
| More than 3000 | 2         | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 5.88%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 5.88%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 5.88%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 1         | 1      | 5.88%   |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 5.88%   |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 5.88%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 5.88%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 5.88%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 1         | 1      | 5.88%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 5.88%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 5.88%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 5.88%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 5.88%   |
| Crucial CT128M550SSD1 128GB                         | 1         | 1      | 5.88%   |
| BAITITON BT58SSD09S 240GB                           | 1         | 1      | 5.88%   |
| A-DATA Technology XM11 256GB-V2 SSD                 | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 3         | 3      | 17.65%  |
| Toshiba           | 2         | 2      | 11.76%  |
| SK hynix          | 2         | 2      | 11.76%  |
| Hitachi           | 2         | 2      | 11.76%  |
| HGST              | 2         | 2      | 11.76%  |
| WDC               | 1         | 1      | 5.88%   |
| SanDisk           | 1         | 1      | 5.88%   |
| Micron Technology | 1         | 1      | 5.88%   |
| Crucial           | 1         | 1      | 5.88%   |
| BAITITON          | 1         | 1      | 5.88%   |
| A-DATA Technology | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 33.33%  |
| Toshiba | 2         | 2      | 22.22%  |
| Hitachi | 2         | 2      | 22.22%  |
| HGST    | 2         | 2      | 22.22%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 56.25%  |
| SSD  | 5         | 6      | 31.25%  |
| NVMe | 2         | 2      | 12.5%   |

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
| Works    | 134       | 165    | 53.17%  |
| Detected | 102       | 161    | 40.48%  |
| Malfunc  | 16        | 17     | 6.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 137       | 45.36%  |
| AMD                            | 35        | 11.59%  |
| Samsung Electronics            | 28        | 9.27%   |
| SanDisk                        | 26        | 8.61%   |
| SK hynix                       | 18        | 5.96%   |
| Toshiba America Info Systems   | 11        | 3.64%   |
| Micron Technology              | 8         | 2.65%   |
| Kingston Technology Company    | 8         | 2.65%   |
| Phison Electronics             | 6         | 1.99%   |
| Micron/Crucial Technology      | 5         | 1.66%   |
| Solid State Storage Technology | 4         | 1.32%   |
| KIOXIA                         | 4         | 1.32%   |
| Apple                          | 3         | 0.99%   |
| Silicon Motion                 | 2         | 0.66%   |
| Zhaoxin                        | 1         | 0.33%   |
| Union Memory (Shenzhen)        | 1         | 0.33%   |
| Shenzhen Longsys Electronics   | 1         | 0.33%   |
| Realtek Semiconductor          | 1         | 0.33%   |
| Nvidia                         | 1         | 0.33%   |
| Marvell Technology Group       | 1         | 0.33%   |
| ADATA Technology               | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 32        | 9.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 23        | 7.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 19        | 5.9%    |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 4.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 3.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 3.42%   |
| SK hynix Gold P31 SSD                                                          | 10        | 3.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 3.11%   |
| Samsung NVMe SSD Controller 980                                                | 9         | 2.8%    |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 2.8%    |
| SanDisk Non-Volatile memory controller                                         | 8         | 2.48%   |
| Micron Non-Volatile memory controller                                          | 8         | 2.48%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 2.17%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 6         | 1.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.86%   |
| SK hynix Non-Volatile memory controller                                        | 5         | 1.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 1.55%   |
| Intel SSD 660P Series                                                          | 5         | 1.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1.55%   |
| Solid State Storage Non-Volatile memory controller                             | 4         | 1.24%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 4         | 1.24%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 4         | 1.24%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 0.93%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 0.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.93%   |
| SK hynix BC511                                                                 | 2         | 0.62%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.62%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 0.62%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 0.62%   |
| Intel Non-Volatile memory controller                                           | 2         | 0.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 151       | 49.51%  |
| NVMe | 121       | 39.67%  |
| RAID | 27        | 8.85%   |
| IDE  | 6         | 1.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 174       | 75%     |
| AMD          | 57        | 24.57%  |
| CentaurHauls | 1         | 0.43%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 9         | 3.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 9         | 3.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 8         | 3.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 8         | 3.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 7         | 3.02%   |
| Intel 12th Gen Core i7-12700H              | 7         | 3.02%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 2.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 5         | 2.16%   |
| Intel Celeron N4020 CPU @ 1.10GHz          | 5         | 2.16%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 5         | 2.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 4         | 1.72%   |
| AMD Ryzen 9 5900HX with Radeon Graphics    | 4         | 1.72%   |
| AMD Ryzen 5 5500U with Radeon Graphics     | 4         | 1.72%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz         | 3         | 1.29%   |
| Intel Core i7-3632QM CPU @ 2.20GHz         | 3         | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 3         | 1.29%   |
| Intel Core i5-10300H CPU @ 2.50GHz         | 3         | 1.29%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 3         | 1.29%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 3         | 1.29%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz    | 3         | 1.29%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 3         | 1.29%   |
| AMD Ryzen 5 4600H with Radeon Graphics     | 3         | 1.29%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 0.86%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 0.86%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 2         | 0.86%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz         | 2         | 0.86%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 2         | 0.86%   |
| Intel Core i7-3612QM CPU @ 2.10GHz         | 2         | 0.86%   |
| Intel Core i7-2670QM CPU @ 2.20GHz         | 2         | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 0.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 2         | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 2         | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 2         | 0.86%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz       | 2         | 0.86%   |
| Intel Celeron CPU N3450 @ 1.10GHz          | 2         | 0.86%   |
| Intel 12th Gen Core i7-1255U               | 2         | 0.86%   |
| Intel 11th Gen Core i5-1155G7 @ 2.50GHz    | 2         | 0.86%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz    | 2         | 0.86%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 0.86%   |
| AMD Ryzen 7 5825U with Radeon Graphics     | 2         | 0.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 56        | 24.14%  |
| Intel Core i5           | 46        | 19.83%  |
| Other                   | 45        | 19.4%   |
| AMD Ryzen 7             | 23        | 9.91%   |
| AMD Ryzen 5             | 15        | 6.47%   |
| Intel Celeron           | 11        | 4.74%   |
| AMD Ryzen 9             | 6         | 2.59%   |
| Intel Core i3           | 5         | 2.16%   |
| Intel Core 2 Duo        | 4         | 1.72%   |
| AMD Ryzen 3             | 4         | 1.72%   |
| Intel Pentium Silver    | 2         | 0.86%   |
| Intel Pentium           | 2         | 0.86%   |
| AMD Ryzen 7 PRO         | 2         | 0.86%   |
| AMD E                   | 2         | 0.86%   |
| Intel Core m3           | 1         | 0.43%   |
| Intel Core i9           | 1         | 0.43%   |
| Intel Core 2            | 1         | 0.43%   |
| Intel Celeron Dual-Core | 1         | 0.43%   |
| AMD Ryzen 5 PRO         | 1         | 0.43%   |
| AMD FX                  | 1         | 0.43%   |
| AMD A6                  | 1         | 0.43%   |
| AMD A4                  | 1         | 0.43%   |
| AMD A10                 | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 88        | 37.93%  |
| 2      | 72        | 31.03%  |
| 8      | 34        | 14.66%  |
| 6      | 25        | 10.78%  |
| 14     | 8         | 3.45%   |
| 12     | 2         | 0.86%   |
| 10     | 2         | 0.86%   |
| 5      | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 232       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 202       | 86.7%   |
| 1      | 31        | 13.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 232       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 38.98%  |
| 0x806c1    | 16        | 6.78%   |
| 0x306a9    | 14        | 5.93%   |
| 0x0a50000c | 12        | 5.08%   |
| 0x08600106 | 9         | 3.81%   |
| 0x906ea    | 8         | 3.39%   |
| 0x906a3    | 7         | 2.97%   |
| 0x08608103 | 7         | 2.97%   |
| 0x806ea    | 6         | 2.54%   |
| 0x306c3    | 6         | 2.54%   |
| 0x806ec    | 5         | 2.12%   |
| 0x806e9    | 5         | 2.12%   |
| 0x406e3    | 5         | 2.12%   |
| 0x206a7    | 4         | 1.69%   |
| 0x08608102 | 4         | 1.69%   |
| 0xa0652    | 3         | 1.27%   |
| 0x806d1    | 3         | 1.27%   |
| 0x08108109 | 3         | 1.27%   |
| 0x906a4    | 2         | 0.85%   |
| 0x806c2    | 2         | 0.85%   |
| 0x706a8    | 2         | 0.85%   |
| 0x506c9    | 2         | 0.85%   |
| 0x40661    | 2         | 0.85%   |
| 0x40651    | 2         | 0.85%   |
| 0x20652    | 2         | 0.85%   |
| 0x08600103 | 2         | 0.85%   |
| 0x906e9    | 1         | 0.42%   |
| 0x806a1    | 1         | 0.42%   |
| 0x6fb      | 1         | 0.42%   |
| 0x6f6      | 1         | 0.42%   |
| 0x30673    | 1         | 0.42%   |
| 0x1067a    | 1         | 0.42%   |
| 0x08108102 | 1         | 0.42%   |
| 0x06006705 | 1         | 0.42%   |
| 0x06001119 | 1         | 0.42%   |
| 0x05000119 | 1         | 0.42%   |
| 0x03000027 | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 40        | 17.24%  |
| TigerLake        | 28        | 12.07%  |
| IvyBridge        | 24        | 10.34%  |
| Zen 3            | 19        | 8.19%   |
| Unknown          | 18        | 7.76%   |
| Haswell          | 17        | 7.33%   |
| Zen 2            | 13        | 5.6%    |
| Skylake          | 10        | 4.31%   |
| Alderlake Hybrid | 9         | 3.88%   |
| SandyBridge      | 8         | 3.45%   |
| Goldmont plus    | 8         | 3.45%   |
| Zen+             | 6         | 2.59%   |
| CometLake        | 5         | 2.16%   |
| Westmere         | 4         | 1.72%   |
| Penryn           | 3         | 1.29%   |
| Icelake          | 3         | 1.29%   |
| Goldmont         | 3         | 1.29%   |
| Core             | 3         | 1.29%   |
| Silvermont       | 2         | 0.86%   |
| Bobcat           | 2         | 0.86%   |
| Zen              | 1         | 0.43%   |
| Steamroller      | 1         | 0.43%   |
| Piledriver       | 1         | 0.43%   |
| Nehalem          | 1         | 0.43%   |
| K10 Llano        | 1         | 0.43%   |
| Excavator        | 1         | 0.43%   |
| Broadwell        | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 161       | 51.94%  |
| Nvidia  | 76        | 24.52%  |
| AMD     | 72        | 23.23%  |
| Zhaoxin | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 24        | 7.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 22        | 6.94%   |
| AMD Cezanne                                                                           | 15        | 4.73%   |
| AMD Renoir                                                                            | 13        | 4.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 11        | 3.47%   |
| AMD Lucienne                                                                          | 11        | 3.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 2.84%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 9         | 2.84%   |
| Intel UHD Graphics 620                                                                | 8         | 2.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 8         | 2.52%   |
| Intel HD Graphics 620                                                                 | 8         | 2.52%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 7         | 2.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 7         | 2.21%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 6         | 1.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 1.89%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 5         | 1.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 5         | 1.58%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 5         | 1.58%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 1.26%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.26%   |
| Intel HD Graphics 630                                                                 | 4         | 1.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 1.26%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 4         | 1.26%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 3         | 0.95%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 3         | 0.95%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                         | 3         | 0.95%   |
| Intel Tiger Lake UHD Graphics                                                         | 3         | 0.95%   |
| Intel HD Graphics 500                                                                 | 3         | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 2         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 0.63%   |
| Nvidia TU117M                                                                         | 2         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 0.63%   |
| Nvidia GM107 [GeForce 940MX]                                                          | 2         | 0.63%   |
| Nvidia GK107M [GeForce GT 650M]                                                       | 2         | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 2         | 0.63%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                              | 2         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 97        | 41.81%  |
| Intel + Nvidia | 49        | 21.12%  |
| 1 x AMD        | 40        | 17.24%  |
| AMD + Nvidia   | 15        | 6.47%   |
| Intel + AMD    | 14        | 6.03%   |
| 1 x Nvidia     | 11        | 4.74%   |
| 2 x AMD        | 3         | 1.29%   |
| Other          | 1         | 0.43%   |
| 2 x Nvidia     | 1         | 0.43%   |
| 1 x Zhaoxin    | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 169       | 72.84%  |
| Proprietary | 57        | 24.57%  |
| Unknown     | 6         | 2.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 166       | 71.24%  |
| 0.01-0.5   | 28        | 12.02%  |
| 1.01-2.0   | 18        | 7.73%   |
| 3.01-4.0   | 7         | 3%      |
| 0.51-1.0   | 6         | 2.58%   |
| 5.01-6.0   | 5         | 2.15%   |
| 7.01-8.0   | 2         | 0.86%   |
| 8.01-16.0  | 1         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 46        | 17.1%   |
| Chimei Innolux          | 45        | 16.73%  |
| BOE                     | 40        | 14.87%  |
| LG Display              | 35        | 13.01%  |
| Samsung Electronics     | 22        | 8.18%   |
| Sharp                   | 11        | 4.09%   |
| Goldstar                | 10        | 3.72%   |
| Hewlett-Packard         | 8         | 2.97%   |
| Apple                   | 8         | 2.97%   |
| Dell                    | 6         | 2.23%   |
| CSO                     | 5         | 1.86%   |
| Chi Mei Optoelectronics | 5         | 1.86%   |
| BenQ                    | 4         | 1.49%   |
| Philips                 | 3         | 1.12%   |
| Lenovo                  | 3         | 1.12%   |
| InfoVision              | 3         | 1.12%   |
| Acer                    | 3         | 1.12%   |
| PANDA                   | 2         | 0.74%   |
| Vizio                   | 1         | 0.37%   |
| SLD                     | 1         | 0.37%   |
| Panasonic               | 1         | 0.37%   |
| MSI                     | 1         | 0.37%   |
| IBM                     | 1         | 0.37%   |
| HKC                     | 1         | 0.37%   |
| Gigabyte Technology     | 1         | 0.37%   |
| CVT                     | 1         | 0.37%   |
| ASUSTek Computer        | 1         | 0.37%   |
| AOC                     | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 1.82%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.82%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch         | 3         | 1.09%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 3         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 1.09%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 0.73%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 2         | 0.73%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch             | 2         | 0.73%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch             | 2         | 0.73%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch             | 2         | 0.73%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 2         | 0.73%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.73%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                    | 2         | 0.73%   |
| BOE LCD Monitor BOE08B9 1920x1080 344x194mm 15.5-inch                    | 2         | 0.73%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.73%   |
| BOE LCD Monitor BOE069B 1600x900 382x215mm 17.3-inch                     | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.73%   |
| Vizio E390-A1 VIZ0098 1920x1080 850x480mm 38.4-inch                      | 1         | 0.36%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 1         | 0.36%   |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch                  | 1         | 0.36%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch                  | 1         | 0.36%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 0.36%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP1450 3840x2160 350x190mm 15.7-inch                  | 1         | 0.36%   |
| Sharp HDMI SHP113E 1920x1080 1330x748mm 60.1-inch                        | 1         | 0.36%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch        | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 130       | 52.21%  |
| 1366x768 (WXGA)    | 49        | 19.68%  |
| 2560x1440 (QHD)    | 12        | 4.82%   |
| 2560x1600          | 9         | 3.61%   |
| 1600x900 (HD+)     | 9         | 3.61%   |
| 3840x2160 (4K)     | 8         | 3.21%   |
| 2880x1800          | 7         | 2.81%   |
| 1920x1200 (WUXGA)  | 6         | 2.41%   |
| 2560x1080          | 4         | 1.61%   |
| 2520x1680          | 2         | 0.8%    |
| 1280x800 (WXGA)    | 2         | 0.8%    |
| 1024x768 (XGA)     | 2         | 0.8%    |
| 3440x1440          | 1         | 0.4%    |
| 3072x1920          | 1         | 0.4%    |
| 2240x1400          | 1         | 0.4%    |
| 2160x1440          | 1         | 0.4%    |
| 2160x1350          | 1         | 0.4%    |
| 1920x540           | 1         | 0.4%    |
| 1680x1050 (WSXGA+) | 1         | 0.4%    |
| 1440x900 (WXGA+)   | 1         | 0.4%    |
| 1280x1024 (SXGA)   | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 116       | 42.96%  |
| 14     | 33        | 12.22%  |
| 13     | 30        | 11.11%  |
| 17     | 19        | 7.04%   |
| 16     | 13        | 4.81%   |
| 24     | 9         | 3.33%   |
| 27     | 8         | 2.96%   |
| 23     | 8         | 2.96%   |
| 21     | 8         | 2.96%   |
| 12     | 5         | 1.85%   |
| 11     | 5         | 1.85%   |
| 34     | 4         | 1.48%   |
| 31     | 3         | 1.11%   |
| 84     | 1         | 0.37%   |
| 78     | 1         | 0.37%   |
| 65     | 1         | 0.37%   |
| 60     | 1         | 0.37%   |
| 54     | 1         | 0.37%   |
| 42     | 1         | 0.37%   |
| 28     | 1         | 0.37%   |
| 22     | 1         | 0.37%   |
| 18     | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 171       | 64.29%  |
| 201-300     | 25        | 9.4%    |
| 351-400     | 24        | 9.02%   |
| 501-600     | 22        | 8.27%   |
| 401-500     | 10        | 3.76%   |
| 701-800     | 4         | 1.5%    |
| 601-700     | 4         | 1.5%    |
| 1001-1500   | 3         | 1.13%   |
| 1501-2000   | 2         | 0.75%   |
| 901-1000    | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 191       | 81.97%  |
| 16/10 | 31        | 13.3%   |
| 21/9  | 5         | 2.15%   |
| 3/2   | 3         | 1.29%   |
| 4/3   | 2         | 0.86%   |
| 5/4   | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 118       | 44.03%  |
| 81-90          | 51        | 19.03%  |
| 201-250        | 18        | 6.72%   |
| 121-130        | 18        | 6.72%   |
| 71-80          | 13        | 4.85%   |
| 111-120        | 10        | 3.73%   |
| 301-350        | 8         | 2.99%   |
| 351-500        | 7         | 2.61%   |
| More than 1000 | 5         | 1.87%   |
| 51-60          | 5         | 1.87%   |
| 61-70          | 4         | 1.49%   |
| 251-300        | 4         | 1.49%   |
| 151-200        | 3         | 1.12%   |
| 141-150        | 2         | 0.75%   |
| 501-1000       | 1         | 0.37%   |
| 91-100         | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 127       | 48.29%  |
| 101-120       | 57        | 21.67%  |
| 51-100        | 34        | 12.93%  |
| 161-240       | 33        | 12.55%  |
| More than 240 | 8         | 3.04%   |
| 1-50          | 4         | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 182       | 77.12%  |
| 2     | 40        | 16.95%  |
| 0     | 7         | 2.97%   |
| 3     | 6         | 2.54%   |
| 4     | 1         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 138       | 37.6%   |
| Intel                             | 124       | 33.79%  |
| Qualcomm Atheros                  | 37        | 10.08%  |
| Broadcom                          | 20        | 5.45%   |
| MediaTek                          | 18        | 4.9%    |
| Samsung Electronics               | 4         | 1.09%   |
| ASIX Electronics                  | 4         | 1.09%   |
| Broadcom Limited                  | 3         | 0.82%   |
| Sierra Wireless                   | 2         | 0.54%   |
| Ralink Technology                 | 2         | 0.54%   |
| Marvell Technology Group          | 2         | 0.54%   |
| Apple                             | 2         | 0.54%   |
| TP-Link                           | 1         | 0.27%   |
| Qualcomm                          | 1         | 0.27%   |
| Nvidia                            | 1         | 0.27%   |
| Motorola PCS                      | 1         | 0.27%   |
| Lenovo                            | 1         | 0.27%   |
| Huawei Technologies               | 1         | 0.27%   |
| Google                            | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| Dell                              | 1         | 0.27%   |
| D-Link System                     | 1         | 0.27%   |
| Belkin Components                 | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 83        | 19.35%  |
| Intel Wi-Fi 6 AX201                                               | 20        | 4.66%   |
| Intel Wi-Fi 6 AX200                                               | 18        | 4.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 16        | 3.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 16        | 3.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 2.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 11        | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 2.1%    |
| Intel Wireless 7260                                               | 9         | 2.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.4%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 5         | 1.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.93%   |
| Intel Wireless 8265 / 8275                                        | 4         | 0.93%   |
| Intel Wireless 8260                                               | 4         | 0.93%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.93%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3         | 0.7%    |
| Realtek 802.11n WLAN Adapter                                      | 3         | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.7%    |
| Intel Wireless 7265                                               | 3         | 0.7%    |
| Intel Wireless 3165                                               | 3         | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.7%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.7%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.7%    |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 118       | 49.17%  |
| Realtek Semiconductor | 46        | 19.17%  |
| Qualcomm Atheros      | 29        | 12.08%  |
| MediaTek              | 18        | 7.5%    |
| Broadcom              | 18        | 7.5%    |
| Broadcom Limited      | 3         | 1.25%   |
| Sierra Wireless       | 2         | 0.83%   |
| Ralink Technology     | 2         | 0.83%   |
| Qualcomm              | 1         | 0.42%   |
| Dell                  | 1         | 0.42%   |
| D-Link System         | 1         | 0.42%   |
| Belkin Components     | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 20        | 8.3%    |
| Intel Wi-Fi 6 AX200                                            | 18        | 7.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 16        | 6.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 16        | 6.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 4.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 3.73%   |
| Intel Wireless 7260                                            | 9         | 3.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 3.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 3.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 2.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 2.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 2.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 2.07%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2.07%   |
| Intel Wireless 8265 / 8275                                     | 4         | 1.66%   |
| Intel Wireless 8260                                            | 4         | 1.66%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 1.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 1.24%   |
| Realtek 802.11n WLAN Adapter                                   | 3         | 1.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 1.24%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.24%   |
| Intel Wireless 7265                                            | 3         | 1.24%   |
| Intel Wireless 3165                                            | 3         | 1.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.24%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.24%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.24%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.24%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.83%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 0.83%   |
| MediaTek WLAN controller                                       | 2         | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.83%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.83%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter             | 2         | 0.83%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 0.83%   |
| Sierra Wireless MC7750                                         | 1         | 0.41%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 112       | 62.22%  |
| Intel                    | 38        | 21.11%  |
| Qualcomm Atheros         | 9         | 5%      |
| Samsung Electronics      | 4         | 2.22%   |
| Broadcom                 | 4         | 2.22%   |
| ASIX Electronics         | 4         | 2.22%   |
| Marvell Technology Group | 2         | 1.11%   |
| Apple                    | 2         | 1.11%   |
| TP-Link                  | 1         | 0.56%   |
| Nvidia                   | 1         | 0.56%   |
| Lenovo                   | 1         | 0.56%   |
| Huawei Technologies      | 1         | 0.56%   |
| Google                   | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 83        | 44.62%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 6.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 5.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 5.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 2.15%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 2.15%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 2.15%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.61%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.61%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.08%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.08%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.08%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.54%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.54%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.54%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.54%   |
| Lenovo Android                                                    | 1         | 0.54%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.54%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.54%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.54%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.54%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.54%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.54%   |
| Huawei LYA-L09                                                    | 1         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 231       | 57.32%  |
| Ethernet | 170       | 42.18%  |
| Modem    | 1         | 0.25%   |
| Unknown  | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 200       | 80.65%  |
| Ethernet | 48        | 19.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 153       | 65.95%  |
| 1     | 73        | 31.47%  |
| 0     | 5         | 2.16%   |
| 3     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 175       | 75.11%  |
| Yes  | 58        | 24.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 97        | 47.09%  |
| Realtek Semiconductor           | 27        | 13.11%  |
| Qualcomm Atheros Communications | 15        | 7.28%   |
| IMC Networks                    | 12        | 5.83%   |
| Lite-On Technology              | 11        | 5.34%   |
| Foxconn / Hon Hai               | 11        | 5.34%   |
| Broadcom                        | 10        | 4.85%   |
| Apple                           | 5         | 2.43%   |
| Toshiba                         | 4         | 1.94%   |
| Realtek                         | 3         | 1.46%   |
| Cambridge Silicon Radio         | 3         | 1.46%   |
| Dell                            | 2         | 0.97%   |
| TP-Link                         | 1         | 0.49%   |
| Hewlett-Packard                 | 1         | 0.49%   |
| Foxconn International           | 1         | 0.49%   |
| Edimax Technology               | 1         | 0.49%   |
| ASUSTek Computer                | 1         | 0.49%   |
| Alps Electric                   | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 25        | 12.14%  |
| Realtek Bluetooth Radio                             | 23        | 11.17%  |
| Intel Bluetooth wireless interface                  | 22        | 10.68%  |
| Intel AX200 Bluetooth                               | 17        | 8.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 15        | 7.28%   |
| Intel Bluetooth Device                              | 10        | 4.85%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 3.4%    |
| IMC Networks Wireless_Device                        | 6         | 2.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.43%   |
| Lite-On Wireless_Device                             | 5         | 2.43%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.94%   |
| Intel AX210 Bluetooth                               | 4         | 1.94%   |
| Apple Bluetooth Host Controller                     | 4         | 1.94%   |
| Realtek Bluetooth Radio                             | 3         | 1.46%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.46%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.46%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.97%   |
| IMC Networks Bluetooth Radio                        | 2         | 0.97%   |
| TP-Link TPuLink UB500 Adapter                       | 1         | 0.49%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.49%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.49%   |
| Toshiba Bluetooth Device                            | 1         | 0.49%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.49%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.49%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.49%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.49%   |
| Lite-On Bluetooth Device                            | 1         | 0.49%   |
| Lite-On BCM43142A0                                  | 1         | 0.49%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.49%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.49%   |
| IMC Networks Bluetooth Device                       | 1         | 0.49%   |
| IMC Networks Bluetooth                              | 1         | 0.49%   |
| IMC Networks BCM20702A0                             | 1         | 0.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.49%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 172       | 56.58%  |
| AMD                 | 61        | 20.07%  |
| Nvidia              | 50        | 16.45%  |
| C-Media Electronics | 3         | 0.99%   |
| Apple               | 2         | 0.66%   |
| ZOOM                | 1         | 0.33%   |
| Zhaoxin             | 1         | 0.33%   |
| TerraTec Electronic | 1         | 0.33%   |
| Sony                | 1         | 0.33%   |
| Razer USA           | 1         | 0.33%   |
| Logitech            | 1         | 0.33%   |
| Lenovo              | 1         | 0.33%   |
| JMTek               | 1         | 0.33%   |
| Hewlett-Packard     | 1         | 0.33%   |
| GN Netcom           | 1         | 0.33%   |
| Focusrite-Novation  | 1         | 0.33%   |
| DisplayLink         | 1         | 0.33%   |
| Cyber Acoustics     | 1         | 0.33%   |
| Creative Technology | 1         | 0.33%   |
| Corsair             | 1         | 0.33%   |
| Arturia             | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 50        | 13.55%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 33        | 8.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 28        | 7.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 27        | 7.32%   |
| Intel Sunrise Point-LP HD Audio                                            | 26        | 7.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 3.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 12        | 3.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 2.98%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 2.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 1.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.63%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 1.63%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.36%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 1.36%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 1.36%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.36%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.08%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.08%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 0.81%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 0.81%   |
| AMD FCH Azalia Controller                                                  | 3         | 0.81%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.54%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.54%   |
| Nvidia Audio device                                                        | 2         | 0.54%   |
| Intel Crystal Well HD Audio Controller                                     | 2         | 0.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.54%   |
| Apple Audio Device                                                         | 2         | 0.54%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.54%   |
| ZOOM U-24                                                                  | 1         | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 71        | 36.98%  |
| SK hynix            | 39        | 20.31%  |
| Micron Technology   | 22        | 11.46%  |
| Kingston            | 14        | 7.29%   |
| Crucial             | 13        | 6.77%   |
| A-DATA Technology   | 5         | 2.6%    |
| Unknown (ABCD)      | 4         | 2.08%   |
| Unknown             | 3         | 1.56%   |
| Elpida              | 3         | 1.56%   |
| Unknown             | 3         | 1.56%   |
| Nanya Technology    | 2         | 1.04%   |
| Wilk                | 1         | 0.52%   |
| Unknown (8A02)      | 1         | 0.52%   |
| Teikon              | 1         | 0.52%   |
| Silicon Power       | 1         | 0.52%   |
| Shenzhen Zhongteng  | 1         | 0.52%   |
| Shenzhen WODPOSIT   | 1         | 0.52%   |
| Ramaxel Technology  | 1         | 0.52%   |
| Qimonda             | 1         | 0.52%   |
| Patriot             | 1         | 0.52%   |
| GOODRAM             | 1         | 0.52%   |
| Corsair             | 1         | 0.52%   |
| Atermiter           | 1         | 0.52%   |
| AMD                 | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.96%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 1.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 1.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.47%   |
| Unknown                                                          | 3         | 1.47%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.98%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.98%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.98%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.98%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.98%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.98%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.98%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.98%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.98%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.98%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 2         | 0.98%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.98%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 0.98%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 0.98%   |
| Wilk RAM GR3200S464L22S/8G 8GB SODIMM DDR4 3200MT/s              | 1         | 0.49%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s     | 1         | 0.49%   |
| Unknown (8A02) RAM DDR3 1600 4G 4GB SODIMM DDR3 1600MT/s         | 1         | 0.49%   |
| Unknown (8A02) RAM DDR3 1600 4G 4GB Chip DDR3 1600MT/s           | 1         | 0.49%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s           | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 93        | 58.86%  |
| DDR3    | 39        | 24.68%  |
| LPDDR4  | 13        | 8.23%   |
| DDR5    | 4         | 2.53%   |
| LPDDR5  | 3         | 1.9%    |
| LPDDR3  | 2         | 1.27%   |
| DDR2    | 2         | 1.27%   |
| SDRAM   | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 134       | 81.71%  |
| Row Of Chips | 28        | 17.07%  |
| DIMM         | 1         | 0.61%   |
| Chip         | 1         | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 82        | 47.67%  |
| 4096  | 45        | 26.16%  |
| 16384 | 23        | 13.37%  |
| 2048  | 11        | 6.4%    |
| 32768 | 8         | 4.65%   |
| 1024  | 3         | 1.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 58        | 34.73%  |
| 1600    | 29        | 17.37%  |
| 2667    | 27        | 16.17%  |
| 2400    | 12        | 7.19%   |
| 4267    | 6         | 3.59%   |
| 4800    | 5         | 2.99%   |
| 1334    | 5         | 2.99%   |
| 1333    | 5         | 2.99%   |
| 2133    | 4         | 2.4%    |
| 6400    | 3         | 1.8%    |
| 1867    | 3         | 1.8%    |
| 4266    | 2         | 1.2%    |
| 667     | 2         | 1.2%    |
| 8400    | 1         | 0.6%    |
| 3266    | 1         | 0.6%    |
| 2666    | 1         | 0.6%    |
| 2048    | 1         | 0.6%    |
| 1067    | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3110 Series | 1         | 33.33%  |
| Canon iP2600 series      | 1         | 33.33%  |
| Brother HL-2230 series   | 1         | 33.33%  |

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
| Chicony Electronics                    | 48        | 22.54%  |
| Microdia                               | 25        | 11.74%  |
| IMC Networks                           | 23        | 10.8%   |
| Acer                                   | 23        | 10.8%   |
| Quanta                                 | 16        | 7.51%   |
| Realtek Semiconductor                  | 15        | 7.04%   |
| Luxvisions Innotech Limited            | 9         | 4.23%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.29%   |
| Sunplus Innovation Technology          | 6         | 2.82%   |
| Logitech                               | 6         | 2.82%   |
| Lite-On Technology                     | 6         | 2.82%   |
| Apple                                  | 5         | 2.35%   |
| Syntek                                 | 4         | 1.88%   |
| Silicon Motion                         | 3         | 1.41%   |
| Y Media                                | 2         | 0.94%   |
| SunplusIT                              | 2         | 0.94%   |
| Alcor Micro                            | 2         | 0.94%   |
| Z-Star Microelectronics                | 1         | 0.47%   |
| Xiaomi                                 | 1         | 0.47%   |
| Suyin                                  | 1         | 0.47%   |
| ShineTech                              | 1         | 0.47%   |
| Samsung Electronics                    | 1         | 0.47%   |
| Novatek Microelectronics               | 1         | 0.47%   |
| Importek                               | 1         | 0.47%   |
| icSpring                               | 1         | 0.47%   |
| Goodong Industry                       | 1         | 0.47%   |
| Goodong                                | 1         | 0.47%   |
| eMPIA Technology                       | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 13        | 6.07%   |
| Acer Integrated Camera                                          | 12        | 5.61%   |
| Microdia Integrated_Webcam_HD                                   | 10        | 4.67%   |
| IMC Networks Integrated Camera                                  | 8         | 3.74%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 7         | 3.27%   |
| Chicony HD WebCam                                               | 6         | 2.8%    |
| Quanta HP TrueVision HD Camera                                  | 4         | 1.87%   |
| Microdia Integrated_Webcam_FHD                                  | 4         | 1.87%   |
| Chicony HD User Facing                                          | 4         | 1.87%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 1.87%   |
| Syntek Integrated Camera                                        | 3         | 1.4%    |
| Sunplus Integrated_Webcam_HD                                    | 3         | 1.4%    |
| Realtek Integrated_Webcam_HD                                    | 3         | 1.4%    |
| Quanta HP Wide Vision HD Camera                                 | 3         | 1.4%    |
| Quanta HD User Facing                                           | 3         | 1.4%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 3         | 1.4%    |
| Chicony USB2.0 Camera                                           | 3         | 1.4%    |
| Chicony HP HD Camera                                            | 3         | 1.4%    |
| Y Media USB Camera                                              | 2         | 0.93%   |
| Realtek USB Camera                                              | 2         | 0.93%   |
| Realtek Integrated Webcam HD                                    | 2         | 0.93%   |
| Microdia Webcam Vitade AF                                       | 2         | 0.93%   |
| Microdia USB Live camera                                        | 2         | 0.93%   |
| Microdia Integrated Webcam                                      | 2         | 0.93%   |
| Luxvisions Innotech Limited Integrated Camera                   | 2         | 0.93%   |
| Luxvisions Innotech Limited HP HD Camera                        | 2         | 0.93%   |
| Logitech Webcam C310                                            | 2         | 0.93%   |
| Lite-On Integrated Camera                                       | 2         | 0.93%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 2         | 0.93%   |
| IMC Networks USB Camera                                         | 2         | 0.93%   |
| IMC Networks HD Camera                                          | 2         | 0.93%   |
| Chicony USB2.0 HD UVC WebCam                                    | 2         | 0.93%   |
| Chicony Lenovo EasyCamera                                       | 2         | 0.93%   |
| Chicony HP TrueVision HD Camera                                 | 2         | 0.93%   |
| Chicony HP TrueVision HD                                        | 2         | 0.93%   |
| Chicony EasyCamera                                              | 2         | 0.93%   |
| Apple FaceTime HD Camera (Built-in)                             | 2         | 0.93%   |
| Acer ThinkPad P50 Integrated Camera                             | 2         | 0.93%   |
| Z-Star Webcam                                                   | 1         | 0.47%   |
| Xiaomi MI 9                                                     | 1         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 19        | 40.43%  |
| Validity Sensors           | 11        | 23.4%   |
| Synaptics                  | 10        | 21.28%  |
| Elan Microelectronics      | 4         | 8.51%   |
| AuthenTec                  | 2         | 4.26%   |
| STMicroelectronics         | 1         | 2.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                        | 17        | 36.17%  |
| Elan ELAN:ARM-M4                                           | 4         | 8.51%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 6.38%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 3         | 6.38%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 3         | 6.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 2         | 4.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.26%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 4.26%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 1         | 2.13%   |
| Validity Sensors VFS491                                    | 1         | 2.13%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.13%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 2.13%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.13%   |
| Synaptics  WBDI                                            | 1         | 2.13%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.13%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.13%   |
| AuthenTec Fingerprint Sensor                               | 1         | 2.13%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 2.13%   |
| Unknown                                                    | 1         | 2.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 50%     |
| Alcor Micro | 5         | 31.25%  |
| Upek        | 1         | 6.25%   |
| O2 Micro    | 1         | 6.25%   |
| BIT4ID      | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 31.25%  |
| Broadcom 5880                                                                | 3         | 18.75%  |
| Broadcom 58200                                                               | 3         | 18.75%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 6.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 6.25%   |
| BIT4ID miniLector EVO                                                        | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 145       | 61.97%  |
| 1     | 68        | 29.06%  |
| 2     | 18        | 7.69%   |
| 9     | 1         | 0.43%   |
| 4     | 1         | 0.43%   |
| 3     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 47        | 42.34%  |
| Chipcard                 | 15        | 13.51%  |
| Graphics card            | 13        | 11.71%  |
| Camera                   | 9         | 8.11%   |
| Multimedia controller    | 8         | 7.21%   |
| Net/wireless             | 5         | 4.5%    |
| Sound                    | 4         | 3.6%    |
| Bluetooth                | 4         | 3.6%    |
| Communication controller | 3         | 2.7%    |
| Network                  | 2         | 1.8%    |
| Net/ethernet             | 1         | 0.9%    |

