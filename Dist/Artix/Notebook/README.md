Artix - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Artix.

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

Total: 252

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook x360 1040 G5      | [997d557b49](https://linux-hardware.org/?probe=997d557b49) | Jan 02, 2025 |
| Acer          | Aspire V3-372               | [09b938a2da](https://linux-hardware.org/?probe=09b938a2da) | Dec 28, 2024 |
| Lenovo        | IdeaPad Pro 5 14AHP9 83D... | [b378ee4e63](https://linux-hardware.org/?probe=b378ee4e63) | Dec 27, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [f55ea0d7ff](https://linux-hardware.org/?probe=f55ea0d7ff) | Dec 21, 2024 |
| HP            | Laptop 15-ef2xxx            | [f2b2c52113](https://linux-hardware.org/?probe=f2b2c52113) | Dec 20, 2024 |
| HUAWEI        | HVY-WXX9                    | [5b9314f900](https://linux-hardware.org/?probe=5b9314f900) | Dec 12, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [2bca320988](https://linux-hardware.org/?probe=2bca320988) | Nov 12, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [a224456b66](https://linux-hardware.org/?probe=a224456b66) | Nov 05, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [c6d44375ae](https://linux-hardware.org/?probe=c6d44375ae) | Oct 19, 2024 |
| Acer          | Aspire V5-123               | [5566103993](https://linux-hardware.org/?probe=5566103993) | Oct 13, 2024 |
| Lenovo        | ThinkPad X230 2325TWT       | [617daeda56](https://linux-hardware.org/?probe=617daeda56) | Sep 28, 2024 |
| Toshiba       | Satellite L755              | [25ca4ce2bc](https://linux-hardware.org/?probe=25ca4ce2bc) | Aug 25, 2024 |
| HP            | 255 G8 Notebook PC          | [ac894331d2](https://linux-hardware.org/?probe=ac894331d2) | Aug 22, 2024 |
| Lenovo        | ThinkPad T480s 20L8S6JH0... | [ddd2754f8c](https://linux-hardware.org/?probe=ddd2754f8c) | Aug 01, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [c29c20403f](https://linux-hardware.org/?probe=c29c20403f) | Jul 16, 2024 |
| Toshiba       | Satellite L755              | [3a39db9d9b](https://linux-hardware.org/?probe=3a39db9d9b) | Jul 09, 2024 |
| Acer          | Aspire A315-24P             | [1e84221951](https://linux-hardware.org/?probe=1e84221951) | Jul 07, 2024 |
| Lenovo        | ThinkPad P50 20EQS3X10C     | [cfccc1ca5a](https://linux-hardware.org/?probe=cfccc1ca5a) | May 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e3b763c6bb](https://linux-hardware.org/?probe=e3b763c6bb) | May 14, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [826e5c0fc6](https://linux-hardware.org/?probe=826e5c0fc6) | May 05, 2024 |
| Acer          | Nitro AN515-52              | [397f8b0836](https://linux-hardware.org/?probe=397f8b0836) | Apr 15, 2024 |
| ASUSTek       | GL702ZC                     | [bf6ba63bb3](https://linux-hardware.org/?probe=bf6ba63bb3) | Apr 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [fdae689907](https://linux-hardware.org/?probe=fdae689907) | Mar 24, 2024 |
| Dell          | Latitude E6440              | [cca0b27697](https://linux-hardware.org/?probe=cca0b27697) | Mar 19, 2024 |
| Positivo      | S14CT01                     | [8272c84692](https://linux-hardware.org/?probe=8272c84692) | Mar 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [6d95912acb](https://linux-hardware.org/?probe=6d95912acb) | Feb 29, 2024 |
| Timi          | RedmiBook 15                | [bb1ccf65a1](https://linux-hardware.org/?probe=bb1ccf65a1) | Feb 20, 2024 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [f940559e53](https://linux-hardware.org/?probe=f940559e53) | Feb 16, 2024 |
| Dell          | Precision M4500             | [eb039bd770](https://linux-hardware.org/?probe=eb039bd770) | Feb 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [fc382a6e28](https://linux-hardware.org/?probe=fc382a6e28) | Feb 07, 2024 |
| Acer          | Swift SFX14-51G             | [9649ed5351](https://linux-hardware.org/?probe=9649ed5351) | Feb 05, 2024 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [33ad82eafa](https://linux-hardware.org/?probe=33ad82eafa) | Feb 05, 2024 |
| Lenovo        | ThinkPad X230 2325SDE       | [b8141f77e9](https://linux-hardware.org/?probe=b8141f77e9) | Feb 03, 2024 |
| Lenovo        | ThinkPad P52s 20LCS2Y800    | [cb08606d1d](https://linux-hardware.org/?probe=cb08606d1d) | Jan 30, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [594794b707](https://linux-hardware.org/?probe=594794b707) | Jan 23, 2024 |
| Positivo      | C14CU51                     | [efceb077f1](https://linux-hardware.org/?probe=efceb077f1) | Jan 10, 2024 |
| Lenovo        | IdeaPad 3 14IAU7 82RJ       | [9b3ba608ee](https://linux-hardware.org/?probe=9b3ba608ee) | Jan 06, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [a62110fad4](https://linux-hardware.org/?probe=a62110fad4) | Dec 31, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [895594b67d](https://linux-hardware.org/?probe=895594b67d) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [229d71f583](https://linux-hardware.org/?probe=229d71f583) | Dec 26, 2023 |
| Dell          | Latitude E6440              | [cf0bb02399](https://linux-hardware.org/?probe=cf0bb02399) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [82fd570b21](https://linux-hardware.org/?probe=82fd570b21) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b706d26f30](https://linux-hardware.org/?probe=b706d26f30) | Dec 07, 2023 |
| HP            | Victus by Gaming Laptop ... | [f150b37e9f](https://linux-hardware.org/?probe=f150b37e9f) | Dec 03, 2023 |
| Acer          | Nitro AN515-54              | [59580145e5](https://linux-hardware.org/?probe=59580145e5) | Nov 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | [e55e321a2e](https://linux-hardware.org/?probe=e55e321a2e) | Nov 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [80d949b057](https://linux-hardware.org/?probe=80d949b057) | Nov 04, 2023 |
| Acer          | Aspire E5-573G              | [7814bb818a](https://linux-hardware.org/?probe=7814bb818a) | Oct 23, 2023 |
| Apple         | MacBookPro10,2              | [f83f9bba48](https://linux-hardware.org/?probe=f83f9bba48) | Oct 15, 2023 |
| HP            | Grunt                       | [af80cd9bd6](https://linux-hardware.org/?probe=af80cd9bd6) | Oct 13, 2023 |
| Dell          | Precision 7560              | [7cffa06ab3](https://linux-hardware.org/?probe=7cffa06ab3) | Oct 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [58552d0532](https://linux-hardware.org/?probe=58552d0532) | Sep 30, 2023 |
| Dell          | Latitude 5431               | [d9ea685862](https://linux-hardware.org/?probe=d9ea685862) | Sep 27, 2023 |
| Lenovo        | ThinkPad T480 20L50018US    | [e28cf08ffe](https://linux-hardware.org/?probe=e28cf08ffe) | Sep 24, 2023 |
| Lenovo        | ThinkPad T480 20L50018US    | [46ee09f5bd](https://linux-hardware.org/?probe=46ee09f5bd) | Sep 21, 2023 |
| Timi          | A30                         | [7e932a59a6](https://linux-hardware.org/?probe=7e932a59a6) | Sep 13, 2023 |
| HP            | ProBook 455 G7              | [7ae653c6c1](https://linux-hardware.org/?probe=7ae653c6c1) | Sep 05, 2023 |
| HP            | 15                          | [db9d960b39](https://linux-hardware.org/?probe=db9d960b39) | Sep 03, 2023 |
| Dell          | Inspiron 15 3511            | [3713bc7b70](https://linux-hardware.org/?probe=3713bc7b70) | Aug 29, 2023 |
| Dell          | Inspiron 15 3511            | [08efa3dcf3](https://linux-hardware.org/?probe=08efa3dcf3) | Aug 24, 2023 |
| Lenovo        | ThinkPad R61 7732NDG        | [b0d510a7ad](https://linux-hardware.org/?probe=b0d510a7ad) | Aug 24, 2023 |
| Acer          | Aspire S5-371               | [210e2bbe4d](https://linux-hardware.org/?probe=210e2bbe4d) | Aug 16, 2023 |
| Acer          | Aspire S5-371               | [c5b4372bbf](https://linux-hardware.org/?probe=c5b4372bbf) | Aug 16, 2023 |
| HP            | 255 G8 Notebook PC          | [5b67a1f9cf](https://linux-hardware.org/?probe=5b67a1f9cf) | Aug 06, 2023 |
| Lenovo        | ThinkPad Edge E431 6277C... | [6c542a6490](https://linux-hardware.org/?probe=6c542a6490) | Aug 03, 2023 |
| Dell          | Inspiron 15-3552            | [3b317edaf6](https://linux-hardware.org/?probe=3b317edaf6) | Jul 25, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [25f87e7de3](https://linux-hardware.org/?probe=25f87e7de3) | Jul 13, 2023 |
| Lenovo        | ThinkPad T420 4180AG3       | [21fe808c05](https://linux-hardware.org/?probe=21fe808c05) | Jul 02, 2023 |
| ASUSTek       | K53E                        | [8e1f4ee31f](https://linux-hardware.org/?probe=8e1f4ee31f) | Jun 27, 2023 |
| HUAWEI        | HVY-WXX9                    | [8649d41483](https://linux-hardware.org/?probe=8649d41483) | Jun 15, 2023 |
| Notebook      | N141CU                      | [4af09bd0c3](https://linux-hardware.org/?probe=4af09bd0c3) | Jun 02, 2023 |
| GPD           | P2 MAX                      | [3c083ee96d](https://linux-hardware.org/?probe=3c083ee96d) | May 29, 2023 |
| ASUSTek       | GL702ZC                     | [c60d7fabbb](https://linux-hardware.org/?probe=c60d7fabbb) | May 25, 2023 |
| Acer          | Nitro AN515-52              | [b5a283de1d](https://linux-hardware.org/?probe=b5a283de1d) | May 25, 2023 |
| Acer          | Nitro AN515-52              | [0a65452634](https://linux-hardware.org/?probe=0a65452634) | May 24, 2023 |
| ASUSTek       | GL702ZC                     | [9764417bf8](https://linux-hardware.org/?probe=9764417bf8) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [a1e2fa6222](https://linux-hardware.org/?probe=a1e2fa6222) | May 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b3eaf738e4](https://linux-hardware.org/?probe=b3eaf738e4) | May 18, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | [429d4451c9](https://linux-hardware.org/?probe=429d4451c9) | May 16, 2023 |
| HP            | EliteBook 2560p             | [2a50b288f8](https://linux-hardware.org/?probe=2a50b288f8) | May 15, 2023 |
| Lenovo        | S20-30 20421                | [cc4f992884](https://linux-hardware.org/?probe=cc4f992884) | May 12, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [ea808c2e80](https://linux-hardware.org/?probe=ea808c2e80) | May 08, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [382b81c0d1](https://linux-hardware.org/?probe=382b81c0d1) | May 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f2ad30321e](https://linux-hardware.org/?probe=f2ad30321e) | Apr 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [6c2d6d52e9](https://linux-hardware.org/?probe=6c2d6d52e9) | Apr 17, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [a2ba637448](https://linux-hardware.org/?probe=a2ba637448) | Mar 29, 2023 |
| Dell          | G3 3500                     | [aa79addc8c](https://linux-hardware.org/?probe=aa79addc8c) | Mar 29, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [6c74aa3736](https://linux-hardware.org/?probe=6c74aa3736) | Mar 02, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [245d23aff3](https://linux-hardware.org/?probe=245d23aff3) | Feb 26, 2023 |
| HP            | 245 G8 Notebook PC          | [1236b5c48f](https://linux-hardware.org/?probe=1236b5c48f) | Feb 19, 2023 |
| HUAWEI        | KPR-WX9                     | [1f44fd5a86](https://linux-hardware.org/?probe=1f44fd5a86) | Feb 18, 2023 |
| ONE-NETBOO... | One-Mix3 Pro                | [9869b4dd9c](https://linux-hardware.org/?probe=9869b4dd9c) | Feb 15, 2023 |
| Gigabyte      | RC14UD                      | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Fujitsu       | LIFEBOOK A512               | [92cac1a802](https://linux-hardware.org/?probe=92cac1a802) | Feb 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7S... | [84411df81a](https://linux-hardware.org/?probe=84411df81a) | Feb 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [bd7e955a3e](https://linux-hardware.org/?probe=bd7e955a3e) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [1f74ea5c27](https://linux-hardware.org/?probe=1f74ea5c27) | Jan 27, 2023 |
| Lenovo        | B50-80 80EW                 | [5f584c387e](https://linux-hardware.org/?probe=5f584c387e) | Jan 25, 2023 |
| Toshiba       | Satellite P775              | [4ac7834c5f](https://linux-hardware.org/?probe=4ac7834c5f) | Jan 16, 2023 |
| Toshiba       | Satellite P775              | [99e632c9a9](https://linux-hardware.org/?probe=99e632c9a9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T430 23427YU       | [3ca2dd056d](https://linux-hardware.org/?probe=3ca2dd056d) | Jan 16, 2023 |
| HONOR         | BMH-WCX9                    | [815525e6d2](https://linux-hardware.org/?probe=815525e6d2) | Dec 27, 2022 |
| ASUSTek       | GL702ZC                     | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Acer          | Aspire A315-56              | [a1ec8cb1b2](https://linux-hardware.org/?probe=a1ec8cb1b2) | Nov 29, 2022 |
| ASUSTek       | N53SV                       | [f42473e3f6](https://linux-hardware.org/?probe=f42473e3f6) | Nov 14, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [75c1d24fcd](https://linux-hardware.org/?probe=75c1d24fcd) | Nov 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [189dd51cc3](https://linux-hardware.org/?probe=189dd51cc3) | Nov 13, 2022 |
| Samsung       | R425D/R525D                 | [85d17374e7](https://linux-hardware.org/?probe=85d17374e7) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [31e940a232](https://linux-hardware.org/?probe=31e940a232) | Nov 10, 2022 |
| HP            | Pavilion 15                 | [93ef42ccbf](https://linux-hardware.org/?probe=93ef42ccbf) | Nov 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [eeb167d869](https://linux-hardware.org/?probe=eeb167d869) | Nov 02, 2022 |
| MSI           | GF65 Thin 10SDR             | [debce2faa6](https://linux-hardware.org/?probe=debce2faa6) | Oct 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| HP            | Pavilion g4                 | [19fe60b14c](https://linux-hardware.org/?probe=19fe60b14c) | Oct 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7d1f20cf17](https://linux-hardware.org/?probe=7d1f20cf17) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dfd00dd2d1](https://linux-hardware.org/?probe=dfd00dd2d1) | Oct 03, 2022 |
| Acer          | Predator PH315-51           | [68f7384e7a](https://linux-hardware.org/?probe=68f7384e7a) | Sep 30, 2022 |
| Acer          | Aspire VN7-592G             | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| Notebook      | N141CU                      | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a37633e1e2](https://linux-hardware.org/?probe=a37633e1e2) | Aug 24, 2022 |
| Dell          | Inspiron 5520               | [6b03bfc62e](https://linux-hardware.org/?probe=6b03bfc62e) | Aug 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| Dell          | Inspiron 3541               | [ab643dc6b0](https://linux-hardware.org/?probe=ab643dc6b0) | Jul 30, 2022 |
| Dell          | Latitude E7440              | [deea307e9b](https://linux-hardware.org/?probe=deea307e9b) | Jul 27, 2022 |
| Dell          | Latitude E7440              | [e2d8510882](https://linux-hardware.org/?probe=e2d8510882) | Jul 27, 2022 |
| Acer          | Aspire A315-23              | [304f750248](https://linux-hardware.org/?probe=304f750248) | Jul 08, 2022 |
| MOTILE        | M141                        | [59c616a04e](https://linux-hardware.org/?probe=59c616a04e) | Jun 30, 2022 |
| HUAWEI        | WRT-WX9                     | [8ddbebd4b1](https://linux-hardware.org/?probe=8ddbebd4b1) | Jun 28, 2022 |
| AXIOO         | Mybook 14E                  | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Timi          | RedmiBook 14 II             | [a4b535cdee](https://linux-hardware.org/?probe=a4b535cdee) | Jun 15, 2022 |
| Lenovo        | ThinkPad T440s 20ARS0MV0... | [3c23c9dfc6](https://linux-hardware.org/?probe=3c23c9dfc6) | Jun 08, 2022 |
| ASUSTek       | X553MA                      | [2a3ac45d9c](https://linux-hardware.org/?probe=2a3ac45d9c) | Jun 05, 2022 |
| Dell          | Precision M6600             | [bb044c066c](https://linux-hardware.org/?probe=bb044c066c) | Jun 05, 2022 |
| Dell          | Latitude 5490               | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [dfacdafc7f](https://linux-hardware.org/?probe=dfacdafc7f) | May 11, 2022 |
| Acer          | Nitro AN515-52              | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | [9792863fc7](https://linux-hardware.org/?probe=9792863fc7) | May 08, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | [bba77106b4](https://linux-hardware.org/?probe=bba77106b4) | May 08, 2022 |
| HP            | 15                          | [d9ed47d44c](https://linux-hardware.org/?probe=d9ed47d44c) | Apr 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [85b1934bfd](https://linux-hardware.org/?probe=85b1934bfd) | Apr 21, 2022 |
| ASUSTek       | GX501VIK                    | [076208c6fd](https://linux-hardware.org/?probe=076208c6fd) | Apr 15, 2022 |
| ASUSTek       | GX501VIK                    | [15c4c7877b](https://linux-hardware.org/?probe=15c4c7877b) | Apr 15, 2022 |
| Lenovo        | ThinkPad T430 2350BC6       | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| HP            | 246                         | [4ef673dd00](https://linux-hardware.org/?probe=4ef673dd00) | Apr 10, 2022 |
| Lenovo        | ThinkPad T430 2347H76       | [493f378237](https://linux-hardware.org/?probe=493f378237) | Mar 10, 2022 |
| HP            | Laptop 14s-dq2xxx           | [92db061239](https://linux-hardware.org/?probe=92db061239) | Mar 09, 2022 |
| Lenovo        | IdeaPad Y500 20193          | [604362a51f](https://linux-hardware.org/?probe=604362a51f) | Feb 18, 2022 |
| Notebook      | N141CU                      | [029f48bc53](https://linux-hardware.org/?probe=029f48bc53) | Feb 16, 2022 |
| Acer          | Aspire V3-472PG             | [70c80ae356](https://linux-hardware.org/?probe=70c80ae356) | Feb 16, 2022 |
| HP            | Laptop 15-ef1xxx            | [6cf7935dcc](https://linux-hardware.org/?probe=6cf7935dcc) | Feb 14, 2022 |
| ASUSTek       | 1225C                       | [b780589dd0](https://linux-hardware.org/?probe=b780589dd0) | Feb 07, 2022 |
| HP            | Laptop 15-ef1xxx            | [6a49ff6317](https://linux-hardware.org/?probe=6a49ff6317) | Jan 18, 2022 |
| Lenovo        | G400s 20244                 | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| MSI           | Modern 15 A11M              | [bef1d4552a](https://linux-hardware.org/?probe=bef1d4552a) | Jan 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a568bef730](https://linux-hardware.org/?probe=a568bef730) | Jan 05, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [a6c63e1079](https://linux-hardware.org/?probe=a6c63e1079) | Dec 17, 2021 |
| Dell          | Latitude E6440              | [5e572f557c](https://linux-hardware.org/?probe=5e572f557c) | Dec 16, 2021 |
| Dell          | Latitude E6440              | [ac94463e37](https://linux-hardware.org/?probe=ac94463e37) | Dec 16, 2021 |
| ASUSTek       | K50IE                       | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [0e12642e78](https://linux-hardware.org/?probe=0e12642e78) | Nov 27, 2021 |
| Timi          | RedmiBook 14 II             | [3e700c917e](https://linux-hardware.org/?probe=3e700c917e) | Nov 25, 2021 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [9a5098383d](https://linux-hardware.org/?probe=9a5098383d) | Nov 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | [76be488014](https://linux-hardware.org/?probe=76be488014) | Nov 07, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | [f96363ccf5](https://linux-hardware.org/?probe=f96363ccf5) | Nov 07, 2021 |
| HP            | ProBook 450 G6              | [ded9086b7c](https://linux-hardware.org/?probe=ded9086b7c) | Nov 06, 2021 |
| Timi          | RedmiBook 14 II             | [038c0ad664](https://linux-hardware.org/?probe=038c0ad664) | Nov 03, 2021 |
| Timi          | RedmiBook 14 II             | [d8ae8a047c](https://linux-hardware.org/?probe=d8ae8a047c) | Nov 02, 2021 |
| Acer          | Swift SF314-59              | [c764d879fb](https://linux-hardware.org/?probe=c764d879fb) | Sep 27, 2021 |
| Acer          | Swift SF314-59              | [9426a6d4df](https://linux-hardware.org/?probe=9426a6d4df) | Sep 23, 2021 |
| Acer          | Aspire E5-575               | [d32c769f65](https://linux-hardware.org/?probe=d32c769f65) | Sep 22, 2021 |
| HP            | Laptop 14s-cf3xxx           | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| Dell          | Precision M6600             | [3c06ad8f67](https://linux-hardware.org/?probe=3c06ad8f67) | Sep 06, 2021 |
| ASUSTek       | GL702ZC                     | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| ASUSTek       | GL702ZC                     | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| GPD           | P2 MAX                      | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD           | P2 MAX                      | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| GPD           | P2 MAX                      | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| HP            | 250 G3                      | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| Dell          | Inspiron 3442               | [a4e06ddea2](https://linux-hardware.org/?probe=a4e06ddea2) | Jul 02, 2021 |
| Lenovo        | LaVie Z 20FF0012US          | [789d556ef6](https://linux-hardware.org/?probe=789d556ef6) | Jul 01, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [89bbafa02e](https://linux-hardware.org/?probe=89bbafa02e) | Jun 22, 2021 |
| HP            | 15                          | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| Apple         | MacBookAir7,2               | [6a459ac265](https://linux-hardware.org/?probe=6a459ac265) | Jun 16, 2021 |
| HP            | 250 G7 Notebook PC          | [10803bcbc4](https://linux-hardware.org/?probe=10803bcbc4) | Jun 07, 2021 |
| HP            | 250 G7 Notebook PC          | [445e09faa7](https://linux-hardware.org/?probe=445e09faa7) | Jun 07, 2021 |
| Dell          | Precision 7550              | [5d7ecb9bbb](https://linux-hardware.org/?probe=5d7ecb9bbb) | Jun 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [de11ab3cc4](https://linux-hardware.org/?probe=de11ab3cc4) | May 31, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Dell          | Precision 7550              | [206eeb06c9](https://linux-hardware.org/?probe=206eeb06c9) | May 23, 2021 |
| UNOWHY        | Y13G010S4EI                 | [62d883cffd](https://linux-hardware.org/?probe=62d883cffd) | May 18, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [85def78a94](https://linux-hardware.org/?probe=85def78a94) | May 02, 2021 |
| HP            | Laptop 17z-ca300            | [ea09357867](https://linux-hardware.org/?probe=ea09357867) | Apr 26, 2021 |
| Acer          | Aspire V3-572PG             | [a874b34c2a](https://linux-hardware.org/?probe=a874b34c2a) | Apr 12, 2021 |
| Apple         | MacBookAir7,2               | [7f14077ecc](https://linux-hardware.org/?probe=7f14077ecc) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Apple         | MacBookPro11,1              | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| MSI           | GP72 7RDX                   | [a60abbdcd4](https://linux-hardware.org/?probe=a60abbdcd4) | Mar 18, 2021 |
| Quanta        | SWH                         | [dc6df30340](https://linux-hardware.org/?probe=dc6df30340) | Mar 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [c2599a37c2](https://linux-hardware.org/?probe=c2599a37c2) | Mar 08, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell          | Precision 7550              | [c1c4fd3b1a](https://linux-hardware.org/?probe=c1c4fd3b1a) | Feb 21, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [b25144d80b](https://linux-hardware.org/?probe=b25144d80b) | Feb 18, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [838f747450](https://linux-hardware.org/?probe=838f747450) | Feb 14, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [214d72ae23](https://linux-hardware.org/?probe=214d72ae23) | Feb 12, 2021 |
| Acer          | Aspire 5733Z                | [b15b48fb21](https://linux-hardware.org/?probe=b15b48fb21) | Jan 29, 2021 |
| ASUSTek       | K53SC                       | [11547cb913](https://linux-hardware.org/?probe=11547cb913) | Jan 22, 2021 |
| ASUSTek       | K53SC                       | [061c52c2ff](https://linux-hardware.org/?probe=061c52c2ff) | Jan 22, 2021 |
| HP            | ProBook 450 G6              | [40e4f5d2fb](https://linux-hardware.org/?probe=40e4f5d2fb) | Jan 21, 2021 |
| Dell          | Precision 5520              | [a714973647](https://linux-hardware.org/?probe=a714973647) | Jan 16, 2021 |
| ASUSTek       | E402NA                      | [ac894b264b](https://linux-hardware.org/?probe=ac894b264b) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Acer          | Aspire A315-53              | [abac7a5b07](https://linux-hardware.org/?probe=abac7a5b07) | Jan 02, 2021 |
| Dell          | Precision 7550              | [9c8b2f2ad6](https://linux-hardware.org/?probe=9c8b2f2ad6) | Dec 30, 2020 |
| Gigabyte      | B450M DS3H-CF               | [b9c02872aa](https://linux-hardware.org/?probe=b9c02872aa) | Dec 29, 2020 |
| Dell          | Latitude E6530              | [46704587d1](https://linux-hardware.org/?probe=46704587d1) | Dec 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | [d2701aa534](https://linux-hardware.org/?probe=d2701aa534) | Dec 24, 2020 |
| HP            | 250 G4 Notebook PC          | [178de0b283](https://linux-hardware.org/?probe=178de0b283) | Dec 24, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | [a905f1377a](https://linux-hardware.org/?probe=a905f1377a) | Dec 20, 2020 |
| GPD           | P2 MAX                      | [f6249e6387](https://linux-hardware.org/?probe=f6249e6387) | Dec 11, 2020 |
| Sony          | VPCCB17FG                   | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| Acer          | Aspire A315-53              | [bc80dc5050](https://linux-hardware.org/?probe=bc80dc5050) | Nov 25, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [53a1586791](https://linux-hardware.org/?probe=53a1586791) | Nov 12, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [61653c183a](https://linux-hardware.org/?probe=61653c183a) | Oct 30, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [f18b33a8f0](https://linux-hardware.org/?probe=f18b33a8f0) | Oct 25, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [acc8c4e663](https://linux-hardware.org/?probe=acc8c4e663) | Oct 25, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | [7c29a97dff](https://linux-hardware.org/?probe=7c29a97dff) | Oct 21, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | [961c0be28a](https://linux-hardware.org/?probe=961c0be28a) | Oct 18, 2020 |
| Dell          | Inspiron 5570               | [038ef2ebaa](https://linux-hardware.org/?probe=038ef2ebaa) | Oct 15, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [b877caba0b](https://linux-hardware.org/?probe=b877caba0b) | Oct 13, 2020 |
| HP            | 255 G7 Notebook PC          | [026a4d80f6](https://linux-hardware.org/?probe=026a4d80f6) | Oct 08, 2020 |
| Dell          | Precision 7550              | [c574758854](https://linux-hardware.org/?probe=c574758854) | Sep 19, 2020 |
| Dell          | Precision 7550              | [14d1876313](https://linux-hardware.org/?probe=14d1876313) | Aug 31, 2020 |
| Dell          | Precision 7550              | [d44c1dbf60](https://linux-hardware.org/?probe=d44c1dbf60) | Aug 31, 2020 |
| Dell          | Precision 7550              | [25d7f344e9](https://linux-hardware.org/?probe=25d7f344e9) | Aug 29, 2020 |
| Acer          | Nitro AN515-51              | [4f2724d5ad](https://linux-hardware.org/?probe=4f2724d5ad) | Aug 16, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [aae7fd244a](https://linux-hardware.org/?probe=aae7fd244a) | Aug 06, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [5e3d9be29a](https://linux-hardware.org/?probe=5e3d9be29a) | Aug 01, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [d5b2c55949](https://linux-hardware.org/?probe=d5b2c55949) | Jul 27, 2020 |
| Lenovo        | ThinkPad T420 4236H45       | [61fd4ce395](https://linux-hardware.org/?probe=61fd4ce395) | Jul 20, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [0af3ac770f](https://linux-hardware.org/?probe=0af3ac770f) | Jul 06, 2020 |
| Notebook      | N130BU                      | [e1b81e4880](https://linux-hardware.org/?probe=e1b81e4880) | Jul 05, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [051fa5784a](https://linux-hardware.org/?probe=051fa5784a) | Jul 02, 2020 |
| Gigabyte      | AERO 15-X9                  | [7cb20a8170](https://linux-hardware.org/?probe=7cb20a8170) | Jul 01, 2020 |
| Gigabyte      | AERO 15-X9                  | [efaa58fcc8](https://linux-hardware.org/?probe=efaa58fcc8) | Jun 14, 2020 |
| Gigabyte      | AERO 15-X9                  | [b5fee1bf94](https://linux-hardware.org/?probe=b5fee1bf94) | Jun 12, 2020 |
| Acer          | Aspire E5-575G              | [cd633c729b](https://linux-hardware.org/?probe=cd633c729b) | Apr 29, 2020 |
| Dell          | Precision 3540              | [3e582eb1b9](https://linux-hardware.org/?probe=3e582eb1b9) | Mar 30, 2020 |
| Dell          | Precision 3540              | [2a446cd098](https://linux-hardware.org/?probe=2a446cd098) | Feb 15, 2020 |
| Lenovo        | B590 20206                  | [a2066c32a9](https://linux-hardware.org/?probe=a2066c32a9) | Oct 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Artix Rolling  | 105       | 56.45%  |
| Artix          | 73        | 39.25%  |
| Artix 20230710 | 2         | 1.08%   |
| Artix 20240823 | 1         | 0.54%   |
| Artix 20230814 | 1         | 0.54%   |
| Artix 20220713 | 1         | 0.54%   |
| Artix 20220123 | 1         | 0.54%   |
| Artix 20201207 | 1         | 0.54%   |
| Artix 20201128 | 1         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 181       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.9.14-artix1-1    | 6         | 2.83%   |
| 6.3.2-artix1-1     | 4         | 1.89%   |
| 6.7.4-artix1-1     | 3         | 1.42%   |
| 6.5.7-artix1-1     | 3         | 1.42%   |
| 6.5.5-artix1-1     | 3         | 1.42%   |
| 6.4.10-artix1-1    | 3         | 1.42%   |
| 6.0.7-artix1-1     | 3         | 1.42%   |
| 5.7.6-artix1-1     | 3         | 1.42%   |
| 5.10.16-artix1-1   | 3         | 1.42%   |
| 6.8.4-artix1-1     | 2         | 0.94%   |
| 6.8.1-artix1-1     | 2         | 0.94%   |
| 6.7.1-artix1-1     | 2         | 0.94%   |
| 6.5.2-artix1-1     | 2         | 0.94%   |
| 6.3.3-artix1-1     | 2         | 0.94%   |
| 6.3.1-artix1-1     | 2         | 0.94%   |
| 6.12.4-artix1-1    | 2         | 0.94%   |
| 6.11.6-artix1-1    | 2         | 0.94%   |
| 6.1.8-artix1-1     | 2         | 0.94%   |
| 6.1.6-artix1-1     | 2         | 0.94%   |
| 6.1.10-zen1-1-zen  | 2         | 0.94%   |
| 6.0.12-artix1-1    | 2         | 0.94%   |
| 5.7.12-artix1-1    | 2         | 0.94%   |
| 5.19.12-artix1-1   | 2         | 0.94%   |
| 5.18.6-artix1-1    | 2         | 0.94%   |
| 5.18.10-artix1-1   | 2         | 0.94%   |
| 5.18.0-artix1-1    | 2         | 0.94%   |
| 5.17.1-artix1-1    | 2         | 0.94%   |
| 5.16.8-artix1-2    | 2         | 0.94%   |
| 5.16.10-artix1-1   | 2         | 0.94%   |
| 5.15.12-artix1-1   | 2         | 0.94%   |
| 5.14.16-artix1-1   | 2         | 0.94%   |
| 5.13.8-artix1-1    | 2         | 0.94%   |
| 5.12.8-artix1-1    | 2         | 0.94%   |
| 5.12.12-zen1-1-zen | 2         | 0.94%   |
| 5.12.12-artix1-1   | 2         | 0.94%   |
| 5.11.6-artix1-1    | 2         | 0.94%   |
| 5.10.6-artix1-1    | 2         | 0.94%   |
| 5.10.4-artix2-1    | 2         | 0.94%   |
| 6.9.7-artix1-1     | 1         | 0.47%   |
| 6.9.4-artix1-1     | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 7         | 3.3%    |
| 6.7.4   | 4         | 1.89%   |
| 6.5.5   | 4         | 1.89%   |
| 6.3.2   | 4         | 1.89%   |
| 6.12.4  | 4         | 1.89%   |
| 6.1.10  | 4         | 1.89%   |
| 6.0.7   | 4         | 1.89%   |
| 5.12.12 | 4         | 1.89%   |
| 6.5.7   | 3         | 1.42%   |
| 6.4.10  | 3         | 1.42%   |
| 6.3.1   | 3         | 1.42%   |
| 5.7.6   | 3         | 1.42%   |
| 5.17.1  | 3         | 1.42%   |
| 5.15.12 | 3         | 1.42%   |
| 5.12.8  | 3         | 1.42%   |
| 5.10.16 | 3         | 1.42%   |
| 6.8.4   | 2         | 0.94%   |
| 6.8.1   | 2         | 0.94%   |
| 6.7.3   | 2         | 0.94%   |
| 6.7.1   | 2         | 0.94%   |
| 6.6.9   | 2         | 0.94%   |
| 6.5.2   | 2         | 0.94%   |
| 6.3.3   | 2         | 0.94%   |
| 6.11.6  | 2         | 0.94%   |
| 6.10.3  | 2         | 0.94%   |
| 6.1.8   | 2         | 0.94%   |
| 6.1.6   | 2         | 0.94%   |
| 6.0.12  | 2         | 0.94%   |
| 5.9.0   | 2         | 0.94%   |
| 5.8.14  | 2         | 0.94%   |
| 5.7.12  | 2         | 0.94%   |
| 5.19.12 | 2         | 0.94%   |
| 5.18.6  | 2         | 0.94%   |
| 5.18.10 | 2         | 0.94%   |
| 5.18.0  | 2         | 0.94%   |
| 5.16.8  | 2         | 0.94%   |
| 5.16.10 | 2         | 0.94%   |
| 5.14.16 | 2         | 0.94%   |
| 5.13.8  | 2         | 0.94%   |
| 5.12.14 | 2         | 0.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 16        | 7.8%    |
| 5.15    | 13        | 6.34%   |
| 5.18    | 12        | 5.85%   |
| 5.12    | 12        | 5.85%   |
| 6.3     | 11        | 5.37%   |
| 5.9     | 11        | 5.37%   |
| 5.10    | 11        | 5.37%   |
| 6.7     | 9         | 4.39%   |
| 6.6     | 9         | 4.39%   |
| 6.5     | 9         | 4.39%   |
| 6.4     | 8         | 3.9%    |
| 6.0     | 8         | 3.9%    |
| 5.17    | 8         | 3.9%    |
| 5.16    | 8         | 3.9%    |
| 5.11    | 8         | 3.9%    |
| 6.12    | 6         | 2.93%   |
| 5.7     | 6         | 2.93%   |
| 5.19    | 6         | 2.93%   |
| 6.8     | 5         | 2.44%   |
| 5.8     | 5         | 2.44%   |
| 6.10    | 4         | 1.95%   |
| 5.14    | 4         | 1.95%   |
| 5.13    | 4         | 1.95%   |
| 6.9     | 3         | 1.46%   |
| 6.2     | 2         | 0.98%   |
| 6.11    | 2         | 0.98%   |
| 6.0.5   | 1         | 0.49%   |
| 5.6     | 1         | 0.49%   |
| 5.5     | 1         | 0.49%   |
| 5.4     | 1         | 0.49%   |
| 4.19    | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 181       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| KDE5                 | 44        | 22.92%  |
| XFCE                 | 34        | 17.71%  |
| Unknown              | 33        | 17.19%  |
| GNOME                | 19        | 9.9%    |
| X-Cinnamon           | 8         | 4.17%   |
| MATE                 | 8         | 4.17%   |
| LXQt                 | 7         | 3.65%   |
| i3                   | 6         | 3.13%   |
| LXDE                 | 4         | 2.08%   |
| KDE6                 | 4         | 2.08%   |
| KDE                  | 4         | 2.08%   |
| Hyprland             | 4         | 2.08%   |
| Sway                 | 3         | 1.56%   |
| Cinnamon             | 3         | 1.56%   |
| DesQ:Wayfire:wlroots | 2         | 1.04%   |
| bspwm                | 2         | 1.04%   |
| xmonad               | 1         | 0.52%   |
| xinitrc              | 1         | 0.52%   |
| sway-dbus            | 1         | 0.52%   |
| nxde                 | 1         | 0.52%   |
| Enlightenment        | 1         | 0.52%   |
| awesomeminimal       | 1         | 0.52%   |
| awesome              | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 118       | 63.1%   |
| Tty     | 27        | 14.44%  |
| Wayland | 26        | 13.9%   |
| Unknown | 16        | 8.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 79        | 42.47%  |
| LightDM | 51        | 27.42%  |
| SDDM    | 46        | 24.73%  |
| XDM     | 2         | 1.08%   |
| SLiM    | 2         | 1.08%   |
| Ly      | 2         | 1.08%   |
| LXDM    | 2         | 1.08%   |
| GDM     | 2         | 1.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 89        | 47.59%  |
| Unknown | 24        | 12.83%  |
| ru_RU   | 10        | 5.35%   |
| C       | 10        | 5.35%   |
| en_GB   | 9         | 4.81%   |
| en_CA   | 5         | 2.67%   |
| pt_BR   | 4         | 2.14%   |
| fr_FR   | 4         | 2.14%   |
| es_ES   | 4         | 2.14%   |
| pl_PL   | 3         | 1.6%    |
| en_IN   | 3         | 1.6%    |
| de_DE   | 3         | 1.6%    |
| it_IT   | 2         | 1.07%   |
| en_AU   | 2         | 1.07%   |
| en_AG   | 2         | 1.07%   |
| vi_VN   | 1         | 0.53%   |
| uk_UA   | 1         | 0.53%   |
| tr_TR   | 1         | 0.53%   |
| ro_RO   | 1         | 0.53%   |
| pt_PT   | 1         | 0.53%   |
| fi_FI   | 1         | 0.53%   |
| es_MX   | 1         | 0.53%   |
| es_GT   | 1         | 0.53%   |
| es_CO   | 1         | 0.53%   |
| es_AR   | 1         | 0.53%   |
| en_NZ   | 1         | 0.53%   |
| el_GR   | 1         | 0.53%   |
| cs_CZ   | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 125       | 68.68%  |
| BIOS | 57        | 31.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 130       | 70.65%  |
| Btrfs   | 44        | 23.91%  |
| Xfs     | 4         | 2.17%   |
| F2fs    | 4         | 2.17%   |
| Overlay | 2         | 1.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 126       | 69.23%  |
| Unknown | 31        | 17.03%  |
| MBR     | 25        | 13.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 155       | 85.16%  |
| Yes       | 27        | 14.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 139       | 76.8%   |
| Yes       | 42        | 23.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 49        | 27.07%  |
| Hewlett-Packard        | 28        | 15.47%  |
| ASUSTek Computer       | 25        | 13.81%  |
| Dell                   | 22        | 12.15%  |
| Acer                   | 20        | 11.05%  |
| Timi                   | 4         | 2.21%   |
| Apple                  | 4         | 2.21%   |
| Samsung Electronics    | 3         | 1.66%   |
| MSI                    | 3         | 1.66%   |
| HUAWEI                 | 3         | 1.66%   |
| Gigabyte Technology    | 3         | 1.66%   |
| Toshiba                | 2         | 1.1%    |
| Positivo               | 2         | 1.1%    |
| Notebook               | 2         | 1.1%    |
| GPD                    | 2         | 1.1%    |
| UNOWHY                 | 1         | 0.55%   |
| Quanta                 | 1         | 0.55%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.55%   |
| MOTILE                 | 1         | 0.55%   |
| LG Electronics         | 1         | 0.55%   |
| HONOR                  | 1         | 0.55%   |
| Fujitsu                | 1         | 0.55%   |
| Framework              | 1         | 0.55%   |
| AXIOO                  | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP 15                                                 | 3         | 1.66%   |
| Timi RedmiBook 14 II                                  | 2         | 1.1%    |
| Lenovo IdeaPad 5 15IIL05 81YK                         | 2         | 1.1%    |
| HP Laptop 15s-eq2xxx                                  | 2         | 1.1%    |
| HP 255 G8 Notebook PC                                 | 2         | 1.1%    |
| GPD P2 MAX                                            | 2         | 1.1%    |
| Dell Precision M6600                                  | 2         | 1.1%    |
| Dell Precision 7550                                   | 2         | 1.1%    |
| Dell Latitude E6440                                   | 2         | 1.1%    |
| ASUS VivoBook_ASUSLaptop M1605YA_M1605YA              | 2         | 1.1%    |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA               | 2         | 1.1%    |
| ASUS Vivobook Go E1404FA_E1404FA                      | 2         | 1.1%    |
| Apple MacBookAir7,2                                   | 2         | 1.1%    |
| Acer Nitro AN515-52                                   | 2         | 1.1%    |
| UNOWHY Y13G010S4EI                                    | 1         | 0.55%   |
| Toshiba Satellite P775                                | 1         | 0.55%   |
| Toshiba Satellite L755                                | 1         | 0.55%   |
| Timi RedmiBook 15                                     | 1         | 0.55%   |
| Timi A30                                              | 1         | 0.55%   |
| Samsung R425D/R525D                                   | 1         | 0.55%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.55%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.55%   |
| Quanta SWH                                            | 1         | 0.55%   |
| Positivo S14CT01                                      | 1         | 0.55%   |
| Positivo C14CU51                                      | 1         | 0.55%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 Pro                   | 1         | 0.55%   |
| Notebook N141CU                                       | 1         | 0.55%   |
| Notebook N130BU                                       | 1         | 0.55%   |
| MSI Modern 15 A11M                                    | 1         | 0.55%   |
| MSI GP72 7RDX                                         | 1         | 0.55%   |
| MSI GF65 Thin 10SDR                                   | 1         | 0.55%   |
| MOTILE M141                                           | 1         | 0.55%   |
| LG 17Z990-R.AAC9U1                                    | 1         | 0.55%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM                     | 1         | 0.55%   |
| Lenovo ThinkPad X230 2325TWT                          | 1         | 0.55%   |
| Lenovo ThinkPad X230 2325SDE                          | 1         | 0.55%   |
| Lenovo ThinkPad W520 4284W2U                          | 1         | 0.55%   |
| Lenovo ThinkPad W500 4063CJ5                          | 1         | 0.55%   |
| Lenovo ThinkPad T480s 20L8S6JH00                      | 1         | 0.55%   |
| Lenovo ThinkPad T480s 20L8S3D400                      | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 25        | 13.81%  |
| Lenovo IdeaPad                  | 14        | 7.73%   |
| Acer Aspire                     | 14        | 7.73%   |
| ASUS VivoBook                   | 13        | 7.18%   |
| HP Laptop                       | 8         | 4.42%   |
| Dell Precision                  | 8         | 4.42%   |
| Dell Inspiron                   | 7         | 3.87%   |
| Dell Latitude                   | 6         | 3.31%   |
| Timi RedmiBook                  | 3         | 1.66%   |
| HP 255                          | 3         | 1.66%   |
| HP 250                          | 3         | 1.66%   |
| HP 15                           | 3         | 1.66%   |
| ASUS ASUS                       | 3         | 1.66%   |
| Acer Nitro                      | 3         | 1.66%   |
| Toshiba Satellite               | 2         | 1.1%    |
| Lenovo Legion                   | 2         | 1.1%    |
| HP ProBook                      | 2         | 1.1%    |
| HP Pavilion                     | 2         | 1.1%    |
| HP EliteBook                    | 2         | 1.1%    |
| GPD P2                          | 2         | 1.1%    |
| Apple MacBookAir7               | 2         | 1.1%    |
| Acer Swift                      | 2         | 1.1%    |
| UNOWHY Y13G010S4EI              | 1         | 0.55%   |
| Timi A30                        | 1         | 0.55%   |
| Samsung R425D                   | 1         | 0.55%   |
| Samsung 350V5C                  | 1         | 0.55%   |
| Samsung 300E5EV                 | 1         | 0.55%   |
| Quanta SWH                      | 1         | 0.55%   |
| Positivo S14CT01                | 1         | 0.55%   |
| Positivo C14CU51                | 1         | 0.55%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 | 1         | 0.55%   |
| Notebook N141CU                 | 1         | 0.55%   |
| Notebook N130BU                 | 1         | 0.55%   |
| MSI Modern                      | 1         | 0.55%   |
| MSI GP72                        | 1         | 0.55%   |
| MSI GF65                        | 1         | 0.55%   |
| MOTILE M141                     | 1         | 0.55%   |
| LG 17Z990-R.AAC9U1              | 1         | 0.55%   |
| Lenovo XiaoXinPro-13ARE         | 1         | 0.55%   |
| Lenovo ThinkBook                | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 35        | 19.34%  |
| 2019 | 18        | 9.94%   |
| 2018 | 18        | 9.94%   |
| 2021 | 16        | 8.84%   |
| 2013 | 14        | 7.73%   |
| 2011 | 14        | 7.73%   |
| 2022 | 11        | 6.08%   |
| 2015 | 10        | 5.52%   |
| 2014 | 9         | 4.97%   |
| 2012 | 9         | 4.97%   |
| 2017 | 7         | 3.87%   |
| 2016 | 6         | 3.31%   |
| 2010 | 4         | 2.21%   |
| 2023 | 3         | 1.66%   |
| 2007 | 3         | 1.66%   |
| 2008 | 2         | 1.1%    |
| 2024 | 1         | 0.55%   |
| 2009 | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 181       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 176       | 97.24%  |
| Enabled  | 5         | 2.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 178       | 98.34%  |
| Yes  | 3         | 1.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 58        | 31.87%  |
| 8.01-16.0   | 38        | 20.88%  |
| 16.01-24.0  | 35        | 19.23%  |
| 3.01-4.0    | 25        | 13.74%  |
| 32.01-64.0  | 10        | 5.49%   |
| 1.01-2.0    | 7         | 3.85%   |
| 24.01-32.0  | 5         | 2.75%   |
| 64.01-256.0 | 4         | 2.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 48        | 23.88%  |
| 2.01-3.0   | 47        | 23.38%  |
| 4.01-8.0   | 46        | 22.89%  |
| 3.01-4.0   | 31        | 15.42%  |
| 0.51-1.0   | 17        | 8.46%   |
| 8.01-16.0  | 8         | 3.98%   |
| 0.01-0.5   | 3         | 1.49%   |
| 16.01-24.0 | 1         | 0.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 144       | 78.69%  |
| 2      | 35        | 19.13%  |
| 3      | 4         | 2.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 138       | 76.24%  |
| Yes       | 43        | 23.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 72.93%  |
| No        | 49        | 27.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 95.6%   |
| No        | 8         | 4.4%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 80.87%  |
| No        | 35        | 19.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| USA             | 33        | 18.03%  |
| Russia          | 16        | 8.74%   |
| India           | 10        | 5.46%   |
| Brazil          | 10        | 5.46%   |
| Canada          | 7         | 3.83%   |
| Poland          | 6         | 3.28%   |
| Germany         | 6         | 3.28%   |
| UK              | 5         | 2.73%   |
| Turkey          | 5         | 2.73%   |
| Italy           | 5         | 2.73%   |
| France          | 5         | 2.73%   |
| Ukraine         | 4         | 2.19%   |
| Switzerland     | 4         | 2.19%   |
| Spain           | 4         | 2.19%   |
| Romania         | 4         | 2.19%   |
| Netherlands     | 4         | 2.19%   |
| Indonesia       | 4         | 2.19%   |
| Czechia         | 4         | 2.19%   |
| Bulgaria        | 3         | 1.64%   |
| Argentina       | 3         | 1.64%   |
| Vietnam         | 2         | 1.09%   |
| Slovakia        | 2         | 1.09%   |
| Serbia          | 2         | 1.09%   |
| Portugal        | 2         | 1.09%   |
| Pakistan        | 2         | 1.09%   |
| Kuwait          | 2         | 1.09%   |
| Israel          | 2         | 1.09%   |
| Finland         | 2         | 1.09%   |
| Colombia        | 2         | 1.09%   |
| Bangladesh      | 2         | 1.09%   |
| Australia       | 2         | 1.09%   |
| Uzbekistan      | 1         | 0.55%   |
| Sweden          | 1         | 0.55%   |
| Slovenia        | 1         | 0.55%   |
| Saudi Arabia    | 1         | 0.55%   |
| Peru            | 1         | 0.55%   |
| North Macedonia | 1         | 0.55%   |
| Luxembourg      | 1         | 0.55%   |
| Lithuania       | 1         | 0.55%   |
| Japan           | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Prague            | 4         | 2.12%   |
| Warsaw            | 3         | 1.59%   |
| St Petersburg     | 3         | 1.59%   |
| Paris             | 3         | 1.59%   |
| Los Angeles       | 3         | 1.59%   |
| Jakarta           | 3         | 1.59%   |
| Amsterdam         | 3         | 1.59%   |
| Tel Aviv          | 2         | 1.06%   |
| Tampere           | 2         | 1.06%   |
| Sorocaba          | 2         | 1.06%   |
| Sofia             | 2         | 1.06%   |
| San Ramon         | 2         | 1.06%   |
| Samara            | 2         | 1.06%   |
| Rio de Janeiro    | 2         | 1.06%   |
| Omaha             | 2         | 1.06%   |
| New York          | 2         | 1.06%   |
| Neuchatel         | 2         | 1.06%   |
| Moscow            | 2         | 1.06%   |
| Mira              | 2         | 1.06%   |
| Milton            | 2         | 1.06%   |
| Mandi             | 2         | 1.06%   |
| Kuwait City       | 2         | 1.06%   |
| Iasi              | 2         | 1.06%   |
| Frankfurt am Main | 2         | 1.06%   |
| Dnipro            | 2         | 1.06%   |
| Brisbane          | 2         | 1.06%   |
| Biel/Bienne       | 2         | 1.06%   |
| Bengaluru         | 2         | 1.06%   |
| Ankara            | 2         | 1.06%   |
| Zurich            | 1         | 0.53%   |
| Zaporizhzhya      | 1         | 0.53%   |
| Zagreb            | 1         | 0.53%   |
| Woodbridge        | 1         | 0.53%   |
| Wigan             | 1         | 0.53%   |
| Wem               | 1         | 0.53%   |
| Vilnius           | 1         | 0.53%   |
| Vienna            | 1         | 0.53%   |
| Vichy             | 1         | 0.53%   |
| Varna             | 1         | 0.53%   |
| Vancouver         | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 39        | 50     | 17.49%  |
| Seagate                      | 23        | 23     | 10.31%  |
| WDC                          | 16        | 19     | 7.17%   |
| Toshiba                      | 15        | 16     | 6.73%   |
| Sandisk                      | 15        | 15     | 6.73%   |
| Intel                        | 13        | 17     | 5.83%   |
| SK hynix                     | 9         | 15     | 4.04%   |
| Kingston                     | 9         | 10     | 4.04%   |
| HGST                         | 8         | 8      | 3.59%   |
| Crucial                      | 8         | 12     | 3.59%   |
| Micron Technology            | 7         | 8      | 3.14%   |
| Unknown                      | 6         | 6      | 2.69%   |
| Phison Electronics           | 5         | 8      | 2.24%   |
| Hitachi                      | 5         | 6      | 2.24%   |
| China                        | 4         | 4      | 1.79%   |
| Micron/Crucial Technology    | 3         | 3      | 1.35%   |
| LITEON                       | 3         | 3      | 1.35%   |
| Apple                        | 3         | 4      | 1.35%   |
| WALRAM                       | 2         | 2      | 0.9%    |
| Solid State Storage          | 2         | 2      | 0.9%    |
| JMicron Technology           | 2         | 2      | 0.9%    |
| A-DATA Technology            | 2         | 2      | 0.9%    |
| USB3.0                       | 1         | 1      | 0.45%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.45%   |
| Timetec                      | 1         | 2      | 0.45%   |
| SPCC                         | 1         | 1      | 0.45%   |
| Silicon Motion               | 1         | 2      | 0.45%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.45%   |
| PNY                          | 1         | 1      | 0.45%   |
| Phison                       | 1         | 1      | 0.45%   |
| Patriot                      | 1         | 1      | 0.45%   |
| MAXIO Technology (Hangzhou)  | 1         | 1      | 0.45%   |
| Lite-On                      | 1         | 1      | 0.45%   |
| Linux                        | 1         | 1      | 0.45%   |
| Lenovo                       | 1         | 1      | 0.45%   |
| LDLC                         | 1         | 5      | 0.45%   |
| KIOXIA                       | 1         | 1      | 0.45%   |
| Intenso                      | 1         | 1      | 0.45%   |
| INNOVATION IT                | 1         | 1      | 0.45%   |
| Hewlett-Packard              | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                       | 7         | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 5         | 2.16%   |
| SanDisk NVMe SSD Drive 512GB                         | 4         | 1.73%   |
| Toshiba MQ01ABF050 500GB                             | 3         | 1.3%    |
| Seagate ST500LT012-1DG142 500GB                      | 3         | 1.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 1.3%    |
| Phison E12 NVMe Controller 480GB                     | 3         | 1.3%    |
| Crucial CT1000MX500SSD1 1TB                          | 3         | 1.3%    |
| China SATA SSD 960GB                                 | 3         | 1.3%    |
| WDC WD10JPVX-22JC3T0 1TB                             | 2         | 0.87%   |
| WALRAM 240G                                          | 2         | 0.87%   |
| Unknown MMC Card  32GB                               | 2         | 0.87%   |
| Toshiba MQ04ABF100 1TB                               | 2         | 0.87%   |
| Toshiba MQ01ABD100 1TB                               | 2         | 0.87%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 2         | 0.87%   |
| Samsung NVMe SSD Drive 1TB                           | 2         | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 2         | 0.87%   |
| Samsung MZVL4512HBLU-00BTW 512GB                     | 2         | 0.87%   |
| Samsung MZNLH512HALU-00000 512GB SSD                 | 2         | 0.87%   |
| Phison PCIe SSD 512GB                                | 2         | 0.87%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                  | 2         | 0.87%   |
| Kingston SA400S37240G 240GB SSD                      | 2         | 0.87%   |
| Kingston OM8PCP3512F-AI1 512GB                       | 2         | 0.87%   |
| Intel SSDPEKNW512GZL 512GB                           | 2         | 0.87%   |
| Intel SSDPEKNU512GZ 512GB                            | 2         | 0.87%   |
| HGST HTS545050A7E680 500GB                           | 2         | 0.87%   |
| HGST HTS541010A9E680 1TB                             | 2         | 0.87%   |
| Crucial CT240BX500SSD1 240GB                         | 2         | 0.87%   |
| Apple SSD SM0256G 256GB                              | 2         | 0.87%   |
| WDC WDS500G2B0A 500GB SSD                            | 1         | 0.43%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                     | 1         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1         | 0.43%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                       | 1         | 0.43%   |
| WDC WD5000LPVX-75V0TT0 500GB                         | 1         | 0.43%   |
| WDC WD5000LPVX-55V0TT0 500GB                         | 1         | 0.43%   |
| WDC WD5000BPVT-22HXZT3 500GB                         | 1         | 0.43%   |
| WDC WD50 00LPVX-75V0TT0 500GB                        | 1         | 0.43%   |
| WDC WD3200LPVT-00FMCT0 320GB                         | 1         | 0.43%   |
| WDC WD3200BEKT-60F3T1 320GB                          | 1         | 0.43%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 23        | 23     | 36.51%  |
| Toshiba            | 13        | 14     | 20.63%  |
| WDC                | 12        | 14     | 19.05%  |
| HGST               | 8         | 8      | 12.7%   |
| Hitachi            | 5         | 6      | 7.94%   |
| Unknown            | 1         | 1      | 1.59%   |
| JMicron Technology | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 13     | 20%     |
| Crucial             | 8         | 12     | 13.33%  |
| Kingston            | 5         | 5      | 8.33%   |
| WDC                 | 4         | 5      | 6.67%   |
| Micron Technology   | 4         | 5      | 6.67%   |
| China               | 4         | 4      | 6.67%   |
| Apple               | 3         | 4      | 5%      |
| SanDisk             | 2         | 2      | 3.33%   |
| LITEON              | 2         | 2      | 3.33%   |
| USB3.0              | 1         | 1      | 1.67%   |
| Toshiba             | 1         | 1      | 1.67%   |
| SPCC                | 1         | 1      | 1.67%   |
| SK hynix            | 1         | 1      | 1.67%   |
| PNY                 | 1         | 1      | 1.67%   |
| Patriot             | 1         | 1      | 1.67%   |
| Linux               | 1         | 1      | 1.67%   |
| LDLC                | 1         | 5      | 1.67%   |
| Intenso             | 1         | 1      | 1.67%   |
| Intel               | 1         | 1      | 1.67%   |
| INNOVATION IT       | 1         | 1      | 1.67%   |
| Hewlett-Packard     | 1         | 1      | 1.67%   |
| FORESEE             | 1         | 1      | 1.67%   |
| Dogfish             | 1         | 1      | 1.67%   |
| Apacer              | 1         | 1      | 1.67%   |
| AGI                 | 1         | 1      | 1.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 82        | 115    | 39.05%  |
| HDD     | 62        | 67     | 29.52%  |
| SSD     | 56        | 72     | 26.67%  |
| MMC     | 5         | 5      | 2.38%   |
| Unknown | 5         | 6      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 109       | 137    | 53.69%  |
| NVMe | 82        | 115    | 40.39%  |
| SAS  | 7         | 8      | 3.45%   |
| MMC  | 5         | 5      | 2.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 70        | 83     | 59.83%  |
| 0.51-1.0   | 40        | 47     | 34.19%  |
| 1.01-2.0   | 5         | 7      | 4.27%   |
| 3.01-4.0   | 1         | 1      | 0.85%   |
| 4.01-10.0  | 1         | 1      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 52        | 27.81%  |
| 101-250        | 47        | 25.13%  |
| 501-1000       | 30        | 16.04%  |
| 1001-2000      | 20        | 10.7%   |
| 51-100         | 9         | 4.81%   |
| Unknown        | 9         | 4.81%   |
| More than 3000 | 8         | 4.28%   |
| 1-20           | 6         | 3.21%   |
| 21-50          | 3         | 1.6%    |
| 2001-3000      | 3         | 1.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 51        | 25.63%  |
| 101-250        | 36        | 18.09%  |
| 21-50          | 27        | 13.57%  |
| 51-100         | 27        | 13.57%  |
| 251-500        | 22        | 11.06%  |
| 501-1000       | 15        | 7.54%   |
| Unknown        | 9         | 4.52%   |
| 1001-2000      | 8         | 4.02%   |
| More than 3000 | 2         | 1.01%   |
| 2001-3000      | 1         | 0.5%    |
| 0              | 1         | 0.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 10%     |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 10%     |
| HGST HTS541010A9E680 1TB                         | 2         | 2      | 10%     |
| WDC WD5000LPVX-55V0TT0 500GB                     | 1         | 1      | 5%      |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 5%      |
| WDC WD3200BEKT-60F3T1 320GB                      | 1         | 1      | 5%      |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1      | 5%      |
| Toshiba MQ01ACF032 320GB                         | 1         | 1      | 5%      |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 5%      |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 5%      |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 5%      |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 5%      |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 5%      |
| LDLC SSD 120GB                                   | 1         | 3      | 5%      |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 5%      |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 5         | 5      | 25%     |
| WDC                 | 4         | 4      | 20%     |
| HGST                | 4         | 4      | 20%     |
| Seagate             | 3         | 3      | 15%     |
| Hitachi             | 2         | 2      | 10%     |
| Samsung Electronics | 1         | 1      | 5%      |
| LDLC                | 1         | 3      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 27.78%  |
| WDC     | 4         | 4      | 22.22%  |
| HGST    | 4         | 4      | 22.22%  |
| Seagate | 3         | 3      | 16.67%  |
| Hitachi | 2         | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 18     | 90%     |
| SSD  | 2         | 4      | 10%     |

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
| Works    | 98        | 131    | 49.75%  |
| Detected | 79        | 112    | 40.1%   |
| Malfunc  | 20        | 22     | 10.15%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 112       | 50.91%  |
| Samsung Electronics            | 29        | 13.18%  |
| AMD                            | 27        | 12.27%  |
| SanDisk                        | 13        | 5.91%   |
| SK hynix                       | 8         | 3.64%   |
| Phison Electronics             | 5         | 2.27%   |
| Kingston Technology Company    | 4         | 1.82%   |
| Micron/Crucial Technology      | 3         | 1.36%   |
| Micron Technology              | 3         | 1.36%   |
| ADATA Technology               | 3         | 1.36%   |
| Union Memory (Shenzhen)        | 2         | 0.91%   |
| Solid State Storage Technology | 2         | 0.91%   |
| Toshiba America Info Systems   | 1         | 0.45%   |
| Silicon Motion                 | 1         | 0.45%   |
| Shenzhen Longsys Electronics   | 1         | 0.45%   |
| Nvidia                         | 1         | 0.45%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.45%   |
| Marvell Technology Group       | 1         | 0.45%   |
| Lite-On Technology             | 1         | 0.45%   |
| Lenovo                         | 1         | 0.45%   |
| KIOXIA                         | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 24        | 10.48%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 18        | 7.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 15        | 6.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 11        | 4.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 11        | 4.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 11        | 4.8%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 8         | 3.49%   |
| Intel Volume Management Device NVMe RAID Controller                           | 7         | 3.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 5         | 2.18%   |
| Intel SSD 670p Series [Keystone Harbor]                                       | 5         | 2.18%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 4         | 1.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 4         | 1.75%   |
| Phison E12 NVMe Controller                                                    | 4         | 1.75%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                 | 4         | 1.75%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                              | 4         | 1.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 4         | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 4         | 1.75%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 4         | 1.75%   |
| SK hynix PC611 NVMe Solid State Drive                                         | 3         | 1.31%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                         | 3         | 1.31%   |
| Intel Tiger Lake-LP SATA Controller                                           | 3         | 1.31%   |
| Intel SSD 660P Series                                                         | 3         | 1.31%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 3         | 1.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 3         | 1.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 3         | 1.31%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                | 2         | 0.87%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                            | 2         | 0.87%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD       | 2         | 0.87%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)     | 2         | 0.87%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 2         | 0.87%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                 | 2         | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 0.87%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 2         | 0.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 0.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 0.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.87%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB               | 1         | 0.44%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                         | 1         | 0.44%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)           | 1         | 0.44%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                   | 1         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 119       | 53.6%   |
| NVMe | 83        | 37.39%  |
| RAID | 18        | 8.11%   |
| IDE  | 2         | 0.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 133       | 73.48%  |
| AMD    | 48        | 26.52%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 2.75%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 2.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.2%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 2.2%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 2.2%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 3         | 1.65%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.65%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.65%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 1.1%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.1%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.1%    |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 1.1%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.1%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.1%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.1%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.1%    |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 1.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.1%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.1%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.1%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.1%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.1%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.1%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.1%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.1%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.1%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.1%    |
| Intel 12th Gen Core i5-1240P                  | 2         | 1.1%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.1%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 1.1%    |
| AMD Ryzen 7 7730U with Radeon Graphics        | 2         | 1.1%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.1%    |
| AMD Ryzen 5 7520U with Radeon Graphics        | 2         | 1.1%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.1%    |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 1.1%    |
| AMD Ryzen 3 3250U with Radeon Graphics        | 2         | 1.1%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 38        | 20.99%  |
| Intel Core i7           | 37        | 20.44%  |
| Other                   | 18        | 9.94%   |
| AMD Ryzen 7             | 16        | 8.84%   |
| AMD Ryzen 5             | 14        | 7.73%   |
| Intel Core i3           | 13        | 7.18%   |
| Intel Celeron           | 10        | 5.52%   |
| Intel Pentium           | 6         | 3.31%   |
| AMD Ryzen 3             | 5         | 2.76%   |
| AMD Athlon              | 3         | 1.66%   |
| Intel Core m3           | 2         | 1.1%    |
| Intel Core i9           | 2         | 1.1%    |
| Intel Core 2 Duo        | 2         | 1.1%    |
| Intel Atom              | 2         | 1.1%    |
| AMD Ryzen 9             | 2         | 1.1%    |
| AMD E1                  | 2         | 1.1%    |
| Intel Xeon              | 1         | 0.55%   |
| Intel Pentium Silver    | 1         | 0.55%   |
| Intel Pentium Dual-Core | 1         | 0.55%   |
| AMD Ryzen 7 PRO         | 1         | 0.55%   |
| AMD Ryzen 5 PRO         | 1         | 0.55%   |
| AMD Phenom II           | 1         | 0.55%   |
| AMD A6                  | 1         | 0.55%   |
| AMD A4                  | 1         | 0.55%   |
| AMD A10                 | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 77        | 42.54%  |
| 4      | 62        | 34.25%  |
| 8      | 20        | 11.05%  |
| 6      | 17        | 9.39%   |
| 12     | 3         | 1.66%   |
| 14     | 1         | 0.55%   |
| 10     | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 181       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 145       | 80.11%  |
| 1      | 36        | 19.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 181       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 40.86%  |
| 0x306a9    | 10        | 5.38%   |
| 0x206a7    | 9         | 4.84%   |
| 0xa0652    | 6         | 3.23%   |
| 0x806ec    | 5         | 2.69%   |
| 0x806e9    | 5         | 2.69%   |
| 0x806c1    | 5         | 2.69%   |
| 0x40651    | 5         | 2.69%   |
| 0x306d4    | 5         | 2.69%   |
| 0x08600106 | 5         | 2.69%   |
| 0x806ea    | 4         | 2.15%   |
| 0x706e5    | 4         | 2.15%   |
| 0x706a1    | 4         | 2.15%   |
| 0x906ea    | 3         | 1.61%   |
| 0x906e9    | 3         | 1.61%   |
| 0x08608103 | 3         | 1.61%   |
| 0x08108109 | 3         | 1.61%   |
| 0x30678    | 2         | 1.08%   |
| 0x1067a    | 2         | 1.08%   |
| 0x08600103 | 2         | 1.08%   |
| 0x08108102 | 2         | 1.08%   |
| 0x08101007 | 2         | 1.08%   |
| 0x906ed    | 1         | 0.54%   |
| 0x906a3    | 1         | 0.54%   |
| 0x806eb    | 1         | 0.54%   |
| 0x806d1    | 1         | 0.54%   |
| 0x806c2    | 1         | 0.54%   |
| 0x506e3    | 1         | 0.54%   |
| 0x506c9    | 1         | 0.54%   |
| 0x406e3    | 1         | 0.54%   |
| 0x306c3    | 1         | 0.54%   |
| 0x20655    | 1         | 0.54%   |
| 0x0a704103 | 1         | 0.54%   |
| 0x0a50000c | 1         | 0.54%   |
| 0x08701013 | 1         | 0.54%   |
| 0x08600109 | 1         | 0.54%   |
| 0x08600104 | 1         | 0.54%   |
| 0x0810100b | 1         | 0.54%   |
| 0x08001137 | 1         | 0.54%   |
| 0x0700010b | 1         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 19.34%  |
| IvyBridge        | 18        | 9.94%   |
| Unknown          | 16        | 8.84%   |
| SandyBridge      | 14        | 7.73%   |
| Zen 2            | 12        | 6.63%   |
| Zen+             | 10        | 5.52%   |
| TigerLake        | 10        | 5.52%   |
| Haswell          | 8         | 4.42%   |
| CometLake        | 7         | 3.87%   |
| Broadwell        | 7         | 3.87%   |
| Silvermont       | 6         | 3.31%   |
| Skylake          | 5         | 2.76%   |
| IceLake          | 5         | 2.76%   |
| Zen              | 4         | 2.21%   |
| Goldmont plus    | 4         | 2.21%   |
| Alderlake Hybrid | 4         | 2.21%   |
| Zen 3            | 3         | 1.66%   |
| Penryn           | 3         | 1.66%   |
| Jaguar           | 2         | 1.1%    |
| Westmere         | 1         | 0.55%   |
| Steamroller      | 1         | 0.55%   |
| Puma             | 1         | 0.55%   |
| Nehalem          | 1         | 0.55%   |
| K10              | 1         | 0.55%   |
| Goldmont         | 1         | 0.55%   |
| Excavator        | 1         | 0.55%   |
| Bonnell          | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 124       | 56.11%  |
| AMD    | 53        | 23.98%  |
| Nvidia | 44        | 19.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 7.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 5.33%   |
| Intel UHD Graphics 620                                                                   | 10        | 4.44%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 10        | 4.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 4.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 3.56%   |
| Intel HD Graphics 620                                                                    | 7         | 3.11%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 3.11%   |
| AMD Lucienne                                                                             | 7         | 3.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 2.22%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.22%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.33%   |
| AMD Mendocino                                                                            | 3         | 1.33%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                         | 2         | 0.89%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.89%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.89%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.89%   |
| Intel UHD Graphics 615                                                                   | 2         | 0.89%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.89%   |
| Intel HD Graphics 630                                                                    | 2         | 0.89%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.89%   |
| Intel HD Graphics 530                                                                    | 2         | 0.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.89%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 0.89%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                    | 2         | 0.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.89%   |
| AMD Saturn XT [FirePro M6100]                                                            | 2         | 0.89%   |
| AMD Barcelo                                                                              | 2         | 0.89%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.44%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 84        | 46.15%  |
| 1 x AMD        | 46        | 25.27%  |
| Intel + Nvidia | 35        | 19.23%  |
| 1 x Nvidia     | 8         | 4.4%    |
| Intel + AMD    | 4         | 2.2%    |
| 2 x AMD        | 3         | 1.65%   |
| 2 x Intel      | 1         | 0.55%   |
| AMD + Nvidia   | 1         | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 153       | 84.53%  |
| Proprietary | 27        | 14.92%  |
| Unknown     | 1         | 0.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 123       | 67.21%  |
| 0.01-0.5   | 23        | 12.57%  |
| 1.01-2.0   | 17        | 9.29%   |
| 0.51-1.0   | 7         | 3.83%   |
| 3.01-4.0   | 6         | 3.28%   |
| 7.01-8.0   | 3         | 1.64%   |
| 5.01-6.0   | 3         | 1.64%   |
| 2.01-3.0   | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 43        | 20.57%  |
| BOE                     | 35        | 16.75%  |
| Chimei Innolux          | 32        | 15.31%  |
| LG Display              | 28        | 13.4%   |
| Samsung Electronics     | 16        | 7.66%   |
| Chi Mei Optoelectronics | 5         | 2.39%   |
| Goldstar                | 4         | 1.91%   |
| Dell                    | 4         | 1.91%   |
| Apple                   | 4         | 1.91%   |
| Philips                 | 3         | 1.44%   |
| PANDA                   | 3         | 1.44%   |
| Lenovo                  | 3         | 1.44%   |
| InfoVision              | 3         | 1.44%   |
| Hewlett-Packard         | 3         | 1.44%   |
| ASUSTek Computer        | 3         | 1.44%   |
| Acer                    | 3         | 1.44%   |
| Sharp                   | 2         | 0.96%   |
| BenQ                    | 2         | 0.96%   |
| ViewSonic               | 1         | 0.48%   |
| Unknown                 | 1         | 0.48%   |
| Sony                    | 1         | 0.48%   |
| MTV                     | 1         | 0.48%   |
| MSI                     | 1         | 0.48%   |
| LGD                     | 1         | 0.48%   |
| KDC                     | 1         | 0.48%   |
| HUAWEI                  | 1         | 0.48%   |
| HKC                     | 1         | 0.48%   |
| CSO                     | 1         | 0.48%   |
| Aosiman                 | 1         | 0.48%   |
| AOC                     | 1         | 0.48%   |
| Ancor Communications    | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch      | 4         | 1.91%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 1.44%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 3         | 1.44%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 2         | 0.96%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.96%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 2         | 0.96%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch               | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch          | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch          | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 2         | 0.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.96%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 0.96%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 0.96%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 0.96%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                      | 2         | 0.96%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch            | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.96%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 0.96%   |
| ViewSonic VA2256 Series VSC3136 1920x1080 476x268mm 21.5-inch             | 1         | 0.48%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 0.48%   |
| Sony BW8 MS_9001 2560x1600                                                | 1         | 0.48%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.48%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.48%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.48%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.48%   |
| Samsung Electronics LS27A800U SAM71A1 3840x2160 597x336mm 27.0-inch       | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch      | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch      | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch      | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC419F 2880x1800 302x189mm 14.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch     | 1         | 0.48%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch                  | 1         | 0.48%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 94        | 47.96%  |
| 1366x768 (WXGA)    | 59        | 30.1%   |
| 3840x2160 (4K)     | 7         | 3.57%   |
| 2560x1600          | 7         | 3.57%   |
| 1600x900 (HD+)     | 6         | 3.06%   |
| 1920x1200 (WUXGA)  | 5         | 2.55%   |
| 2560x1440 (QHD)    | 4         | 2.04%   |
| 1440x900 (WXGA+)   | 4         | 2.04%   |
| 3456x2160          | 1         | 0.51%   |
| 3440x1440          | 1         | 0.51%   |
| 3072x1920          | 1         | 0.51%   |
| 2880x1800          | 1         | 0.51%   |
| 2288x1287          | 1         | 0.51%   |
| 2256x1504          | 1         | 0.51%   |
| 2240x1400          | 1         | 0.51%   |
| 2160x1440          | 1         | 0.51%   |
| 1680x1050 (WSXGA+) | 1         | 0.51%   |
| 1280x800 (WXGA)    | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 86        | 41.35%  |
| 14      | 32        | 15.38%  |
| 13      | 32        | 15.38%  |
| 17      | 10        | 4.81%   |
| 27      | 8         | 3.85%   |
| 24      | 7         | 3.37%   |
| 21      | 7         | 3.37%   |
| 16      | 6         | 2.88%   |
| 11      | 4         | 1.92%   |
| 23      | 3         | 1.44%   |
| 12      | 3         | 1.44%   |
| 31      | 2         | 0.96%   |
| 142     | 1         | 0.48%   |
| 34      | 1         | 0.48%   |
| 32      | 1         | 0.48%   |
| 28      | 1         | 0.48%   |
| 20      | 1         | 0.48%   |
| 19      | 1         | 0.48%   |
| 8       | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 138       | 66.67%  |
| 201-300        | 19        | 9.18%   |
| 501-600        | 16        | 7.73%   |
| 351-400        | 15        | 7.25%   |
| 401-500        | 9         | 4.35%   |
| 601-700        | 5         | 2.42%   |
| 701-800        | 2         | 0.97%   |
| More than 2000 | 1         | 0.48%   |
| 101-200        | 1         | 0.48%   |
| Unknown        | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 155       | 85.64%  |
| 16/10   | 20        | 11.05%  |
| 3/2     | 2         | 1.1%    |
| 21/9    | 1         | 0.55%   |
| 1.00    | 1         | 0.55%   |
| 0.62    | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 87        | 42.03%  |
| 81-90          | 53        | 25.6%   |
| 201-250        | 13        | 6.28%   |
| 71-80          | 10        | 4.83%   |
| 121-130        | 9         | 4.35%   |
| 301-350        | 8         | 3.86%   |
| 351-500        | 5         | 2.42%   |
| 111-120        | 5         | 2.42%   |
| 51-60          | 4         | 1.93%   |
| 61-70          | 3         | 1.45%   |
| 251-300        | 3         | 1.45%   |
| 151-200        | 3         | 1.45%   |
| More than 1000 | 1         | 0.48%   |
| 1-40           | 1         | 0.48%   |
| 131-140        | 1         | 0.48%   |
| Unknown        | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 96        | 48%     |
| 101-120       | 54        | 27%     |
| 51-100        | 27        | 13.5%   |
| 161-240       | 16        | 8%      |
| More than 240 | 5         | 2.5%    |
| 1-50          | 1         | 0.5%    |
| Unknown       | 1         | 0.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 151       | 82.07%  |
| 2     | 32        | 17.39%  |
| 0     | 1         | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 105       | 36.97%  |
| Intel                    | 91        | 32.04%  |
| Qualcomm Atheros         | 30        | 10.56%  |
| MediaTek                 | 13        | 4.58%   |
| Broadcom                 | 13        | 4.58%   |
| Broadcom Limited         | 4         | 1.41%   |
| TP-Link                  | 3         | 1.06%   |
| Samsung Electronics      | 3         | 1.06%   |
| Qualcomm                 | 3         | 1.06%   |
| Xiaomi                   | 2         | 0.7%    |
| Ralink                   | 2         | 0.7%    |
| ASIX Electronics         | 2         | 0.7%    |
| Sierra Wireless          | 1         | 0.35%   |
| Ralink Technology        | 1         | 0.35%   |
| PAX                      | 1         | 0.35%   |
| OPPO Electronics         | 1         | 0.35%   |
| Marvell Technology Group | 1         | 0.35%   |
| Linksys                  | 1         | 0.35%   |
| Lenovo                   | 1         | 0.35%   |
| ICS Advent               | 1         | 0.35%   |
| Huawei Technologies      | 1         | 0.35%   |
| Dell                     | 1         | 0.35%   |
| Castles Technology       | 1         | 0.35%   |
| Aquantia                 | 1         | 0.35%   |
| Apple                    | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 59        | 17.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 5.03%   |
| Intel Wireless 8265 / 8275                                             | 14        | 4.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 13        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 3.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 2.96%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 2.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 2.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 2.07%   |
| Intel Wi-Fi 6 AX201                                                    | 7         | 2.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 7         | 2.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 1.78%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.78%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 6         | 1.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 1.48%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 5         | 1.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 5         | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 1.18%   |
| Realtek 802.11ac NIC                                                   | 4         | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4         | 1.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 4         | 1.18%   |
| Intel Wireless 7265                                                    | 4         | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                          | 4         | 1.18%   |
| Intel Wireless 7260                                                    | 3         | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 3         | 0.89%   |
| Intel Centrino Wireless-N 2230                                         | 3         | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.89%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.59%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.59%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                         | 2         | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 0.59%   |
| Intel Wireless 3165                                                    | 2         | 0.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 0.59%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.59%   |
| Intel Ethernet Connection (11) I219-LM                                 | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 86        | 46.49%  |
| Realtek Semiconductor | 39        | 21.08%  |
| Qualcomm Atheros      | 26        | 14.05%  |
| Broadcom              | 12        | 6.49%   |
| MediaTek              | 10        | 5.41%   |
| Broadcom Limited      | 4         | 2.16%   |
| TP-Link               | 3         | 1.62%   |
| Ralink                | 2         | 1.08%   |
| Sierra Wireless       | 1         | 0.54%   |
| Ralink Technology     | 1         | 0.54%   |
| Qualcomm              | 1         | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 14        | 7.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 13        | 6.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 10        | 5.35%   |
| Intel Wi-Fi 6 AX200                                                  | 10        | 5.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 3.74%   |
| Intel Wi-Fi 6 AX201                                                  | 7         | 3.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 3.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 3.21%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 6         | 3.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 2.67%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 5         | 2.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 5         | 2.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 2.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 2.14%   |
| Realtek 802.11ac NIC                                                 | 4         | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 4         | 2.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 4         | 2.14%   |
| Intel Wireless 7265                                                  | 4         | 2.14%   |
| Broadcom BCM43142 802.11b/g/n                                        | 4         | 2.14%   |
| Intel Wireless 7260                                                  | 3         | 1.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 1.6%    |
| Intel Centrino Wireless-N 2230                                       | 3         | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 1.6%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 1.6%    |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                       | 2         | 1.07%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2         | 1.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 1.07%   |
| Intel Wireless 3165                                                  | 2         | 1.07%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2         | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 1.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1.07%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 1.07%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.07%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 2         | 1.07%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.53%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1         | 0.53%   |
| TP-Link 802.11n NIC                                                  | 1         | 0.53%   |
| Sierra Wireless MC7750                                               | 1         | 0.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 85        | 59.03%  |
| Intel                    | 32        | 22.22%  |
| Qualcomm Atheros         | 7         | 4.86%   |
| MediaTek                 | 3         | 2.08%   |
| Xiaomi                   | 2         | 1.39%   |
| Qualcomm                 | 2         | 1.39%   |
| Broadcom                 | 2         | 1.39%   |
| ASIX Electronics         | 2         | 1.39%   |
| Samsung Electronics      | 1         | 0.69%   |
| OPPO Electronics         | 1         | 0.69%   |
| Marvell Technology Group | 1         | 0.69%   |
| Linksys                  | 1         | 0.69%   |
| Lenovo                   | 1         | 0.69%   |
| ICS Advent               | 1         | 0.69%   |
| Huawei Technologies      | 1         | 0.69%   |
| Aquantia                 | 1         | 0.69%   |
| Apple                    | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 59        | 40.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 11.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 8.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 6.16%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 4.11%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 2.05%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 1.37%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.37%   |
| Intel Ethernet Connection (11) I219-LM                                 | 2         | 1.37%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.68%   |
| Qualcomm POCO F3                                                       | 1         | 0.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.68%   |
| Qualcomm A0001                                                         | 1         | 0.68%   |
| OPPO OnePlus Nord 4                                                    | 1         | 0.68%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.68%   |
| Linksys Gigabit Ethernet Adapter                                       | 1         | 0.68%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 0.68%   |
| Intel WiMAX Connection 2400m                                           | 1         | 0.68%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.68%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.68%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.68%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 0.68%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.68%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 0.68%   |
| ICS Advent USB 10/100 LAN                                              | 1         | 0.68%   |
| Huawei E353/E3131                                                      | 1         | 0.68%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 0.68%   |
| ASIX AX88772                                                           | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 174       | 56.31%  |
| Ethernet | 132       | 42.72%  |
| Modem    | 3         | 0.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 78.19%  |
| Ethernet | 40        | 21.28%  |
| Modem    | 1         | 0.53%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 112       | 61.54%  |
| 1     | 65        | 35.71%  |
| 3     | 3         | 1.65%   |
| 0     | 2         | 1.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 148       | 79.14%  |
| Yes  | 39        | 20.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 44.97%  |
| Realtek Semiconductor           | 25        | 16.78%  |
| IMC Networks                    | 13        | 8.72%   |
| Broadcom                        | 10        | 6.71%   |
| Qualcomm Atheros Communications | 7         | 4.7%    |
| Foxconn / Hon Hai               | 7         | 4.7%    |
| Lite-On Technology              | 6         | 4.03%   |
| Apple                           | 4         | 2.68%   |
| Realtek                         | 3         | 2.01%   |
| MediaTek                        | 2         | 1.34%   |
| Cambridge Silicon Radio         | 2         | 1.34%   |
| Ralink                          | 1         | 0.67%   |
| Dell                            | 1         | 0.67%   |
| ASUSTek Computer                | 1         | 0.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 14%     |
| Intel AX201 Bluetooth                               | 17        | 11.33%  |
| Realtek Bluetooth Radio                             | 16        | 10.67%  |
| Intel AX200 Bluetooth                               | 10        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 6%      |
| IMC Networks Wireless_Device                        | 8         | 5.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 2.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 2.67%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 2%      |
| Realtek Bluetooth Radio                             | 3         | 2%      |
| Intel AX211 Bluetooth                               | 3         | 2%      |
| IMC Networks Bluetooth Radio                        | 3         | 2%      |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 2%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.33%   |
| MediaTek Wireless_Device                            | 2         | 1.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.33%   |
| IMC Networks Bluetooth Device                       | 2         | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.33%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 1.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 1.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.33%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.33%   |
| Apple Bluetooth Host Controller                     | 2         | 1.33%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.67%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.67%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.67%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.67%   |
| Lite-On Bluetooth Device                            | 1         | 0.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.67%   |
| Intel AX210 Bluetooth                               | 1         | 0.67%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.67%   |
| Broadcom HP Portable Valentine                      | 1         | 0.67%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.67%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 131       | 57.96%  |
| AMD                    | 50        | 22.12%  |
| Nvidia                 | 27        | 11.95%  |
| Realtek Semiconductor  | 3         | 1.33%   |
| C-Media Electronics    | 3         | 1.33%   |
| Texas Instruments      | 1         | 0.44%   |
| Plantronics            | 1         | 0.44%   |
| Lenovo                 | 1         | 0.44%   |
| Hewlett-Packard        | 1         | 0.44%   |
| Harman                 | 1         | 0.44%   |
| GN Netcom              | 1         | 0.44%   |
| Generalplus Technology | 1         | 0.44%   |
| DSEA A/S               | 1         | 0.44%   |
| Corsair                | 1         | 0.44%   |
| ASUSTek Computer       | 1         | 0.44%   |
| Arylic                 | 1         | 0.44%   |
| Apple                  | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 39        | 13.49%  |
| Intel Sunrise Point-LP HD Audio                                            | 23        | 7.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 19        | 6.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19        | 6.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 4.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 4.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 3.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 2.42%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 2.42%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 2.42%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 2.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 2.08%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 2.08%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6         | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 1.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.38%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.38%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 1.38%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.04%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.04%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.69%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.69%   |
| Nvidia GA107 High Definition Audio Controller                              | 2         | 0.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.69%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 0.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 0.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 0.69%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 0.69%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2         | 0.69%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.35%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                          | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 57        | 29.53%  |
| SK hynix            | 44        | 22.8%   |
| Micron Technology   | 22        | 11.4%   |
| Kingston            | 18        | 9.33%   |
| Unknown             | 10        | 5.18%   |
| A-DATA Technology   | 5         | 2.59%   |
| Smart               | 4         | 2.07%   |
| Crucial             | 4         | 2.07%   |
| Corsair             | 4         | 2.07%   |
| Unknown             | 4         | 2.07%   |
| Team                | 3         | 1.55%   |
| Silicon Power       | 3         | 1.55%   |
| Ramaxel Technology  | 3         | 1.55%   |
| Nanya Technology    | 3         | 1.55%   |
| Unknown (ABCD)      | 2         | 1.04%   |
| Smart Brazil        | 1         | 0.52%   |
| Patriot             | 1         | 0.52%   |
| GOODRAM             | 1         | 0.52%   |
| Elpida              | 1         | 0.52%   |
| Avant               | 1         | 0.52%   |
| ASint Technology    | 1         | 0.52%   |
| AMD                 | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 3%      |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 5         | 2.5%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 2%      |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 2%      |
| Unknown                                                          | 4         | 2%      |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.5%    |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 3         | 1.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.5%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.5%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 1%      |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1%      |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1%      |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1%      |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1%      |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1%      |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1%      |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1%      |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1%      |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1%      |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1%      |
| Micron RAM MT62F1G32D4DR-031 4GB SODIMM LPDDR5 5500MT/s          | 2         | 1%      |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM LPDDR4 2400MT/s                    | 1         | 0.5%    |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.5%    |
| Unknown RAM DDR4 NB 16G 16GB SODIMM DDR4 2667MT/s                | 1         | 0.5%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.5%    |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 79        | 51.97%  |
| DDR3    | 52        | 34.21%  |
| LPDDR4  | 5         | 3.29%   |
| LPDDR5  | 4         | 2.63%   |
| LPDDR3  | 4         | 2.63%   |
| DDR5    | 4         | 2.63%   |
| SDRAM   | 2         | 1.32%   |
| DDR2    | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 134       | 87.01%  |
| Row Of Chips | 17        | 11.04%  |
| DIMM         | 1         | 0.65%   |
| Chip         | 1         | 0.65%   |
| Unknown      | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 60        | 34.48%  |
| 4096  | 60        | 34.48%  |
| 16384 | 31        | 17.82%  |
| 2048  | 13        | 7.47%   |
| 32768 | 8         | 4.6%    |
| 1024  | 2         | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 45        | 27.44%  |
| 3200  | 40        | 24.39%  |
| 2667  | 33        | 20.12%  |
| 2400  | 11        | 6.71%   |
| 1333  | 7         | 4.27%   |
| 1334  | 5         | 3.05%   |
| 2133  | 4         | 2.44%   |
| 4800  | 3         | 1.83%   |
| 5500  | 2         | 1.22%   |
| 4199  | 2         | 1.22%   |
| 3266  | 2         | 1.22%   |
| 7500  | 1         | 0.61%   |
| 6400  | 1         | 0.61%   |
| 5600  | 1         | 0.61%   |
| 4267  | 1         | 0.61%   |
| 3800  | 1         | 0.61%   |
| 2933  | 1         | 0.61%   |
| 1867  | 1         | 0.61%   |
| 1066  | 1         | 0.61%   |
| 800   | 1         | 0.61%   |
| 667   | 1         | 0.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Brother HL-L3270CDW series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Mustek Systems BearPaw 1200 TA/CS | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 38        | 23.9%   |
| IMC Networks                           | 24        | 15.09%  |
| Quanta                                 | 14        | 8.81%   |
| Bison Electronics                      | 13        | 8.18%   |
| Realtek Semiconductor                  | 12        | 7.55%   |
| Microdia                               | 9         | 5.66%   |
| Suyin                                  | 6         | 3.77%   |
| Luxvisions Innotech Limited            | 6         | 3.77%   |
| Sunplus Innovation Technology          | 5         | 3.14%   |
| Alcor Micro                            | 5         | 3.14%   |
| Syntek                                 | 4         | 2.52%   |
| Sonix Technology                       | 4         | 2.52%   |
| Silicon Motion                         | 4         | 2.52%   |
| Acer                                   | 4         | 2.52%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.89%   |
| ShineTech                              | 2         | 1.26%   |
| Ricoh                                  | 1         | 0.63%   |
| Logitech                               | 1         | 0.63%   |
| Lite-On Technology                     | 1         | 0.63%   |
| LG Electronics                         | 1         | 0.63%   |
| Lenovo                                 | 1         | 0.63%   |
| Apple                                  | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 10        | 6.21%   |
| Chicony Integrated Camera                           | 7         | 4.35%   |
| Chicony HD WebCam                                   | 7         | 4.35%   |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 2.48%   |
| Realtek Integrated_Webcam_HD                        | 4         | 2.48%   |
| Microdia Integrated Webcam                          | 4         | 2.48%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 2.48%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.48%   |
| Bison Integrated Camera                             | 4         | 2.48%   |
| Syntek EasyCamera                                   | 3         | 1.86%   |
| Sunplus HD WebCam                                   | 3         | 1.86%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.86%   |
| Microdia Integrated_Webcam_HD                       | 3         | 1.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 1.86%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 1.86%   |
| Chicony HP TrueVision HD Camera                     | 3         | 1.86%   |
| Suyin HP Webcam                                     | 2         | 1.24%   |
| Silicon Motion 300k Pixel Camera                    | 2         | 1.24%   |
| ShineTech USB2.0 HD UVC WebCam                      | 2         | 1.24%   |
| Realtek USB2.0 HD UVC WebCam                        | 2         | 1.24%   |
| Realtek HD WebCam                                   | 2         | 1.24%   |
| Quanta VGA WebCam                                   | 2         | 1.24%   |
| Quanta USB2.0 VGA UVC WebCam                        | 2         | 1.24%   |
| Quanta HP Webcam                                    | 2         | 1.24%   |
| Quanta HD Webcam                                    | 2         | 1.24%   |
| IMC Networks XiaoMi Webcam                          | 2         | 1.24%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.24%   |
| Chicony USB2.0 Camera                               | 2         | 1.24%   |
| Chicony thinkpad t430s camera                       | 2         | 1.24%   |
| Chicony Integrated IR Camera                        | 2         | 1.24%   |
| Bison Lenovo EasyCamera                             | 2         | 1.24%   |
| Bison HD Webcam                                     | 2         | 1.24%   |
| Alcor Micro USB 2.0 Camera                          | 2         | 1.24%   |
| Acer Integrated Camera                              | 2         | 1.24%   |
| Syntek Integrated Camera                            | 1         | 0.62%   |
| Suyin USB Webcam                                    | 1         | 0.62%   |
| Suyin NEC HD WebCam                                 | 1         | 0.62%   |
| Suyin Laptop_Integrated_Webcam_HD                   | 1         | 0.62%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.62%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 33.33%  |
| Shenzhen Goodix Technology | 6         | 28.57%  |
| Validity Sensors           | 5         | 23.81%  |
| STMicroelectronics         | 1         | 4.76%   |
| Elan Microelectronics      | 1         | 4.76%   |
| AuthenTec                  | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 23.81%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 14.29%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 9.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 4.76%   |
| Validity Sensors VFS491                                                    | 1         | 4.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.76%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 4.76%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 4.76%   |
| Elan ELAN:ARM-M4                                                           | 1         | 4.76%   |
| AuthenTec AES2810                                                          | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 8         | 53.33%  |
| Alcor Micro      | 4         | 26.67%  |
| Upek             | 1         | 6.67%   |
| SCM Microsystems | 1         | 6.67%   |
| Lenovo           | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 26.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 13.33%  |
| Broadcom 58200                                                               | 2         | 13.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 6.67%   |
| SCM Microsystems SCT3522CC token                                             | 1         | 6.67%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 6.67%   |
| Broadcom 5880                                                                | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 118       | 64.13%  |
| 1     | 55        | 29.89%  |
| 2     | 9         | 4.89%   |
| 3     | 2         | 1.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 20        | 25.32%  |
| Net/wireless             | 12        | 15.19%  |
| Chipcard                 | 12        | 15.19%  |
| Graphics card            | 10        | 12.66%  |
| Multimedia controller    | 7         | 8.86%   |
| Camera                   | 6         | 7.59%   |
| Bluetooth                | 4         | 5.06%   |
| Communication controller | 3         | 3.8%    |
| Storage                  | 2         | 2.53%   |
| Network                  | 1         | 1.27%   |
| Net/ethernet             | 1         | 1.27%   |
| Dvb card                 | 1         | 1.27%   |

