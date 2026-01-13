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

Total: 288

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 3 15IML05 81WB      | [1ea64280f4](https://linux-hardware.org/?probe=1ea64280f4) | Jan 02, 2026 |
| Lenovo        | T480                        | [7d8bf16e2e](https://linux-hardware.org/?probe=7d8bf16e2e) | Dec 29, 2025 |
| Lenovo        | Z50-75 80EC                 | [12d924dd92](https://linux-hardware.org/?probe=12d924dd92) | Dec 29, 2025 |
| Lenovo        | Z50-75 80EC                 | [341e38736a](https://linux-hardware.org/?probe=341e38736a) | Dec 28, 2025 |
| Lenovo        | ThinkPad T480 20L6CT01WW    | [8ba7ce2c2b](https://linux-hardware.org/?probe=8ba7ce2c2b) | Dec 22, 2025 |
| HP            | 350 G2                      | [59c9ec6cf5](https://linux-hardware.org/?probe=59c9ec6cf5) | Dec 20, 2025 |
| HP            | Laptop 15-bs0xx             | [de0bc71076](https://linux-hardware.org/?probe=de0bc71076) | Dec 09, 2025 |
| TongFang      | GX5HRXL                     | [3e06a2975a](https://linux-hardware.org/?probe=3e06a2975a) | Dec 07, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [61da87ddfa](https://linux-hardware.org/?probe=61da87ddfa) | Dec 06, 2025 |
| Google        | Celes                       | [65f93b0828](https://linux-hardware.org/?probe=65f93b0828) | Nov 20, 2025 |
| HONOR         | BRI-XX                      | [a270fd36f0](https://linux-hardware.org/?probe=a270fd36f0) | Nov 20, 2025 |
| LG Electro... | A520-P.AC7BT                | [b9bc2c8178](https://linux-hardware.org/?probe=b9bc2c8178) | Nov 12, 2025 |
| Founder       | Veriton Balao               | [e8d347d21f](https://linux-hardware.org/?probe=e8d347d21f) | Nov 09, 2025 |
| Acer          | Nitro AN515-52              | [78330f0d61](https://linux-hardware.org/?probe=78330f0d61) | Nov 02, 2025 |
| HP            | Victus by Laptop 16-e1xx... | [b3ae3c01ee](https://linux-hardware.org/?probe=b3ae3c01ee) | Oct 30, 2025 |
| HP            | Laptop 17z-cp300            | [c0dc830c0e](https://linux-hardware.org/?probe=c0dc830c0e) | Oct 28, 2025 |
| HP            | Laptop 17z-cp300            | [80b34c767f](https://linux-hardware.org/?probe=80b34c767f) | Oct 28, 2025 |
| Lenovo        | ThinkPad T480 20L6SEYY00    | [dedd2b5651](https://linux-hardware.org/?probe=dedd2b5651) | Oct 17, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ad1b137bb5](https://linux-hardware.org/?probe=ad1b137bb5) | Oct 08, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61c4901311](https://linux-hardware.org/?probe=61c4901311) | Sep 21, 2025 |
| Apple         | MacBookAir7,2               | [589be7a88e](https://linux-hardware.org/?probe=589be7a88e) | Sep 19, 2025 |
| HP            | Laptop 15s-fq2xxx           | [a0f807ff68](https://linux-hardware.org/?probe=a0f807ff68) | Sep 11, 2025 |
| HP            | EliteBook 8460p             | [bf32030e39](https://linux-hardware.org/?probe=bf32030e39) | Aug 08, 2025 |
| Dell          | Latitude E5250              | [257b30e3ce](https://linux-hardware.org/?probe=257b30e3ce) | Jul 18, 2025 |
| Unknown       | M17S                        | [69910b7849](https://linux-hardware.org/?probe=69910b7849) | Jun 08, 2025 |
| HP            | 15                          | [d5b1383caf](https://linux-hardware.org/?probe=d5b1383caf) | May 28, 2025 |
| Acer          | Aspire E5-523G              | [1f16d0c700](https://linux-hardware.org/?probe=1f16d0c700) | May 23, 2025 |
| Lenovo        | ThinkPad X230 23253A2       | [0f3f789c17](https://linux-hardware.org/?probe=0f3f789c17) | Apr 30, 2025 |
| Gigabyte      | AORUS 15 BKF                | [82dc4059ce](https://linux-hardware.org/?probe=82dc4059ce) | Apr 19, 2025 |
| Gigabyte      | AORUS 15 BKF                | [f9f1923e20](https://linux-hardware.org/?probe=f9f1923e20) | Apr 19, 2025 |
| ASUSTek       | N61Jq                       | [47b566a509](https://linux-hardware.org/?probe=47b566a509) | Mar 30, 2025 |
| Toshiba       | Satellite L755              | [3efdfd83ea](https://linux-hardware.org/?probe=3efdfd83ea) | Feb 22, 2025 |
| Dell          | Latitude E6410              | [a5257434a1](https://linux-hardware.org/?probe=a5257434a1) | Feb 17, 2025 |
| Dell          | Latitude E6410              | [ca57c1faea](https://linux-hardware.org/?probe=ca57c1faea) | Feb 17, 2025 |
| Lenovo        | Legion 5 15ARH05 82B5       | [a20fa3b1d8](https://linux-hardware.org/?probe=a20fa3b1d8) | Jan 23, 2025 |
| Lenovo        | ThinkPad T410 2537LV1       | [09eae0c510](https://linux-hardware.org/?probe=09eae0c510) | Jan 13, 2025 |
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
| Artix Rolling  | 121       | 56.02%  |
| Artix          | 86        | 39.81%  |
| Artix 20230710 | 2         | 0.93%   |
| Artix 20251211 | 1         | 0.46%   |
| Artix 20240823 | 1         | 0.46%   |
| Artix 20230814 | 1         | 0.46%   |
| Artix 20220713 | 1         | 0.46%   |
| Artix 20220123 | 1         | 0.46%   |
| Artix 20201207 | 1         | 0.46%   |
| Artix 20201128 | 1         | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 211       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.9.14-artix1-1    | 6         | 2.46%   |
| 6.17.9-artix1-1    | 5         | 2.05%   |
| 6.3.2-artix1-1     | 4         | 1.64%   |
| 6.7.4-artix1-1     | 3         | 1.23%   |
| 6.5.7-artix1-1     | 3         | 1.23%   |
| 6.5.5-artix1-1     | 3         | 1.23%   |
| 6.4.10-artix1-1    | 3         | 1.23%   |
| 6.0.7-artix1-1     | 3         | 1.23%   |
| 5.7.6-artix1-1     | 3         | 1.23%   |
| 5.10.16-artix1-1   | 3         | 1.23%   |
| 6.8.4-artix1-1     | 2         | 0.82%   |
| 6.8.1-artix1-1     | 2         | 0.82%   |
| 6.7.1-artix1-1     | 2         | 0.82%   |
| 6.5.2-artix1-1     | 2         | 0.82%   |
| 6.3.3-artix1-1     | 2         | 0.82%   |
| 6.3.1-artix1-1     | 2         | 0.82%   |
| 6.17.7-zen1-1-zen  | 2         | 0.82%   |
| 6.14.6-artix1-1    | 2         | 0.82%   |
| 6.13.2-artix1-1    | 2         | 0.82%   |
| 6.12.4-artix1-1    | 2         | 0.82%   |
| 6.12.23-1-lts      | 2         | 0.82%   |
| 6.11.6-artix1-1    | 2         | 0.82%   |
| 6.1.8-artix1-1     | 2         | 0.82%   |
| 6.1.6-artix1-1     | 2         | 0.82%   |
| 6.1.10-zen1-1-zen  | 2         | 0.82%   |
| 6.0.12-artix1-1    | 2         | 0.82%   |
| 5.7.12-artix1-1    | 2         | 0.82%   |
| 5.19.12-artix1-1   | 2         | 0.82%   |
| 5.18.6-artix1-1    | 2         | 0.82%   |
| 5.18.10-artix1-1   | 2         | 0.82%   |
| 5.18.0-artix1-1    | 2         | 0.82%   |
| 5.17.1-artix1-1    | 2         | 0.82%   |
| 5.16.8-artix1-2    | 2         | 0.82%   |
| 5.16.10-artix1-1   | 2         | 0.82%   |
| 5.15.12-artix1-1   | 2         | 0.82%   |
| 5.14.16-artix1-1   | 2         | 0.82%   |
| 5.13.8-artix1-1    | 2         | 0.82%   |
| 5.12.8-artix1-1    | 2         | 0.82%   |
| 5.12.12-zen1-1-zen | 2         | 0.82%   |
| 5.12.12-artix1-1   | 2         | 0.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 7         | 2.87%   |
| 6.17.9  | 5         | 2.05%   |
| 6.7.4   | 4         | 1.64%   |
| 6.5.5   | 4         | 1.64%   |
| 6.3.2   | 4         | 1.64%   |
| 6.12.4  | 4         | 1.64%   |
| 6.1.10  | 4         | 1.64%   |
| 6.0.7   | 4         | 1.64%   |
| 5.12.12 | 4         | 1.64%   |
| 6.5.7   | 3         | 1.23%   |
| 6.4.10  | 3         | 1.23%   |
| 6.3.1   | 3         | 1.23%   |
| 6.17.7  | 3         | 1.23%   |
| 5.7.6   | 3         | 1.23%   |
| 5.17.1  | 3         | 1.23%   |
| 5.15.12 | 3         | 1.23%   |
| 5.12.8  | 3         | 1.23%   |
| 5.10.16 | 3         | 1.23%   |
| 6.8.4   | 2         | 0.82%   |
| 6.8.1   | 2         | 0.82%   |
| 6.7.3   | 2         | 0.82%   |
| 6.7.1   | 2         | 0.82%   |
| 6.6.9   | 2         | 0.82%   |
| 6.5.2   | 2         | 0.82%   |
| 6.3.3   | 2         | 0.82%   |
| 6.17.8  | 2         | 0.82%   |
| 6.17.5  | 2         | 0.82%   |
| 6.16.9  | 2         | 0.82%   |
| 6.14.6  | 2         | 0.82%   |
| 6.13.2  | 2         | 0.82%   |
| 6.12.23 | 2         | 0.82%   |
| 6.11.6  | 2         | 0.82%   |
| 6.10.3  | 2         | 0.82%   |
| 6.1.8   | 2         | 0.82%   |
| 6.1.6   | 2         | 0.82%   |
| 6.0.12  | 2         | 0.82%   |
| 5.9.0   | 2         | 0.82%   |
| 5.8.14  | 2         | 0.82%   |
| 5.7.12  | 2         | 0.82%   |
| 5.19.12 | 2         | 0.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 16        | 6.75%   |
| 6.17    | 14        | 5.91%   |
| 5.15    | 13        | 5.49%   |
| 5.18    | 12        | 5.06%   |
| 5.12    | 12        | 5.06%   |
| 6.3     | 11        | 4.64%   |
| 5.9     | 11        | 4.64%   |
| 5.10    | 11        | 4.64%   |
| 6.12    | 10        | 4.22%   |
| 6.7     | 9         | 3.8%    |
| 6.6     | 9         | 3.8%    |
| 6.5     | 9         | 3.8%    |
| 6.4     | 8         | 3.38%   |
| 6.0     | 8         | 3.38%   |
| 5.17    | 8         | 3.38%   |
| 5.16    | 8         | 3.38%   |
| 5.11    | 8         | 3.38%   |
| 6.16    | 6         | 2.53%   |
| 5.7     | 6         | 2.53%   |
| 5.19    | 6         | 2.53%   |
| 6.8     | 5         | 2.11%   |
| 5.8     | 5         | 2.11%   |
| 6.10    | 4         | 1.69%   |
| 5.14    | 4         | 1.69%   |
| 5.13    | 4         | 1.69%   |
| 6.9     | 3         | 1.27%   |
| 6.14    | 3         | 1.27%   |
| 6.13    | 3         | 1.27%   |
| 6.2     | 2         | 0.84%   |
| 6.11    | 2         | 0.84%   |
| 6.18    | 1         | 0.42%   |
| 6.15    | 1         | 0.42%   |
| 6.0.5   | 1         | 0.42%   |
| 5.6     | 1         | 0.42%   |
| 5.5     | 1         | 0.42%   |
| 5.4     | 1         | 0.42%   |
| 4.19    | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 211       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| KDE5                 | 44        | 19.82%  |
| XFCE                 | 41        | 18.47%  |
| Unknown              | 38        | 17.12%  |
| GNOME                | 21        | 9.46%   |
| X-Cinnamon           | 10        | 4.5%    |
| MATE                 | 9         | 4.05%   |
| KDE6                 | 9         | 4.05%   |
| i3                   | 8         | 3.6%    |
| Hyprland             | 8         | 3.6%    |
| LXQt                 | 7         | 3.15%   |
| LXDE                 | 5         | 2.25%   |
| KDE                  | 5         | 2.25%   |
| Sway                 | 3         | 1.35%   |
| Cinnamon             | 3         | 1.35%   |
| DesQ:Wayfire:wlroots | 2         | 0.9%    |
| bspwm                | 2         | 0.9%    |
| xmonad               | 1         | 0.45%   |
| xinitrc              | 1         | 0.45%   |
| sway-dbus            | 1         | 0.45%   |
| nxde                 | 1         | 0.45%   |
| Enlightenment        | 1         | 0.45%   |
| awesomeminimal       | 1         | 0.45%   |
| awesome              | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 130       | 59.91%  |
| Wayland | 35        | 16.13%  |
| Tty     | 33        | 15.21%  |
| Unknown | 19        | 8.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 98        | 45.37%  |
| LightDM | 56        | 25.93%  |
| SDDM    | 52        | 24.07%  |
| XDM     | 2         | 0.93%   |
| SLiM    | 2         | 0.93%   |
| Ly      | 2         | 0.93%   |
| LXDM    | 2         | 0.93%   |
| GDM     | 2         | 0.93%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 108       | 49.77%  |
| Unknown | 27        | 12.44%  |
| ru_RU   | 11        | 5.07%   |
| C       | 10        | 4.61%   |
| en_GB   | 9         | 4.15%   |
| es_ES   | 5         | 2.3%    |
| en_CA   | 5         | 2.3%    |
| de_DE   | 5         | 2.3%    |
| pt_BR   | 4         | 1.84%   |
| it_IT   | 4         | 1.84%   |
| fr_FR   | 4         | 1.84%   |
| pl_PL   | 3         | 1.38%   |
| en_IN   | 3         | 1.38%   |
| en_AU   | 3         | 1.38%   |
| es_AR   | 2         | 0.92%   |
| en_AG   | 2         | 0.92%   |
| vi_VN   | 1         | 0.46%   |
| uk_UA   | 1         | 0.46%   |
| tr_TR   | 1         | 0.46%   |
| ro_RO   | 1         | 0.46%   |
| pt_PT   | 1         | 0.46%   |
| fi_FI   | 1         | 0.46%   |
| es_MX   | 1         | 0.46%   |
| es_GT   | 1         | 0.46%   |
| es_CO   | 1         | 0.46%   |
| en_NZ   | 1         | 0.46%   |
| el_GR   | 1         | 0.46%   |
| cs_CZ   | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 141       | 66.51%  |
| BIOS | 71        | 33.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 155       | 72.43%  |
| Btrfs   | 46        | 21.5%   |
| Xfs     | 7         | 3.27%   |
| F2fs    | 4         | 1.87%   |
| Overlay | 2         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 143       | 67.45%  |
| Unknown | 39        | 18.4%   |
| MBR     | 30        | 14.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 184       | 86.38%  |
| Yes       | 29        | 13.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 164       | 77.73%  |
| Yes       | 47        | 22.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 57        | 27.01%  |
| Hewlett-Packard        | 35        | 16.59%  |
| ASUSTek Computer       | 28        | 13.27%  |
| Dell                   | 24        | 11.37%  |
| Acer                   | 21        | 9.95%   |
| Apple                  | 5         | 2.37%   |
| Timi                   | 4         | 1.9%    |
| Gigabyte Technology    | 4         | 1.9%    |
| Samsung Electronics    | 3         | 1.42%   |
| MSI                    | 3         | 1.42%   |
| HUAWEI                 | 3         | 1.42%   |
| Toshiba                | 2         | 0.95%   |
| Positivo               | 2         | 0.95%   |
| Notebook               | 2         | 0.95%   |
| LG Electronics         | 2         | 0.95%   |
| HONOR                  | 2         | 0.95%   |
| GPD                    | 2         | 0.95%   |
| Framework              | 2         | 0.95%   |
| UNOWHY                 | 1         | 0.47%   |
| TongFang               | 1         | 0.47%   |
| Quanta                 | 1         | 0.47%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.47%   |
| MOTILE                 | 1         | 0.47%   |
| Google                 | 1         | 0.47%   |
| Fujitsu                | 1         | 0.47%   |
| Founder                | 1         | 0.47%   |
| AXIOO                  | 1         | 0.47%   |
| Unknown                | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP 15                                                 | 4         | 1.9%    |
| Apple MacBookAir7,2                                   | 3         | 1.42%   |
| Timi RedmiBook 14 II                                  | 2         | 0.95%   |
| Lenovo IdeaPad 5 15IIL05 81YK                         | 2         | 0.95%   |
| HP Laptop 15s-eq2xxx                                  | 2         | 0.95%   |
| HP 255 G8 Notebook PC                                 | 2         | 0.95%   |
| GPD P2 MAX                                            | 2         | 0.95%   |
| Dell Precision M6600                                  | 2         | 0.95%   |
| Dell Precision 7550                                   | 2         | 0.95%   |
| Dell Latitude E6440                                   | 2         | 0.95%   |
| ASUS VivoBook_ASUSLaptop M1605YA_M1605YA              | 2         | 0.95%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA               | 2         | 0.95%   |
| ASUS Vivobook Go E1404FA_E1404FA                      | 2         | 0.95%   |
| Acer Nitro AN515-52                                   | 2         | 0.95%   |
| UNOWHY Y13G010S4EI                                    | 1         | 0.47%   |
| Toshiba Satellite P775                                | 1         | 0.47%   |
| Toshiba Satellite L755                                | 1         | 0.47%   |
| TongFang GX5HRXL                                      | 1         | 0.47%   |
| Timi RedmiBook 15                                     | 1         | 0.47%   |
| Timi A30                                              | 1         | 0.47%   |
| Samsung R425D/R525D                                   | 1         | 0.47%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.47%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.47%   |
| Quanta SWH                                            | 1         | 0.47%   |
| Positivo S14CT01                                      | 1         | 0.47%   |
| Positivo C14CU51                                      | 1         | 0.47%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 Pro                   | 1         | 0.47%   |
| Notebook N141CU                                       | 1         | 0.47%   |
| Notebook N130BU                                       | 1         | 0.47%   |
| MSI Modern 15 A11M                                    | 1         | 0.47%   |
| MSI GP72 7RDX                                         | 1         | 0.47%   |
| MSI GF65 Thin 10SDR                                   | 1         | 0.47%   |
| MOTILE M141                                           | 1         | 0.47%   |
| LG A520-P.AC7BT                                       | 1         | 0.47%   |
| LG 17Z990-R.AAC9U1                                    | 1         | 0.47%   |
| Lenovo Z50-75 80EC                                    | 1         | 0.47%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM                     | 1         | 0.47%   |
| Lenovo ThinkPad X230 2325TWT                          | 1         | 0.47%   |
| Lenovo ThinkPad X230 2325SDE                          | 1         | 0.47%   |
| Lenovo ThinkPad X230 23253A2                          | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 29        | 13.74%  |
| Lenovo IdeaPad                  | 15        | 7.11%   |
| Acer Aspire                     | 15        | 7.11%   |
| ASUS VivoBook                   | 14        | 6.64%   |
| HP Laptop                       | 11        | 5.21%   |
| Dell Precision                  | 8         | 3.79%   |
| Dell Latitude                   | 8         | 3.79%   |
| Dell Inspiron                   | 7         | 3.32%   |
| HP 15                           | 4         | 1.9%    |
| Timi RedmiBook                  | 3         | 1.42%   |
| Lenovo Legion                   | 3         | 1.42%   |
| HP EliteBook                    | 3         | 1.42%   |
| HP 255                          | 3         | 1.42%   |
| HP 250                          | 3         | 1.42%   |
| ASUS ASUS                       | 3         | 1.42%   |
| Apple MacBookAir7               | 3         | 1.42%   |
| Acer Nitro                      | 3         | 1.42%   |
| Toshiba Satellite               | 2         | 0.95%   |
| HP Victus                       | 2         | 0.95%   |
| HP ProBook                      | 2         | 0.95%   |
| HP Pavilion                     | 2         | 0.95%   |
| GPD P2                          | 2         | 0.95%   |
| Framework Laptop                | 2         | 0.95%   |
| Acer Swift                      | 2         | 0.95%   |
| UNOWHY Y13G010S4EI              | 1         | 0.47%   |
| TongFang GX5HRXL                | 1         | 0.47%   |
| Timi A30                        | 1         | 0.47%   |
| Samsung R425D                   | 1         | 0.47%   |
| Samsung 350V5C                  | 1         | 0.47%   |
| Samsung 300E5EV                 | 1         | 0.47%   |
| Quanta SWH                      | 1         | 0.47%   |
| Positivo S14CT01                | 1         | 0.47%   |
| Positivo C14CU51                | 1         | 0.47%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 | 1         | 0.47%   |
| Notebook N141CU                 | 1         | 0.47%   |
| Notebook N130BU                 | 1         | 0.47%   |
| MSI Modern                      | 1         | 0.47%   |
| MSI GP72                        | 1         | 0.47%   |
| MSI GF65                        | 1         | 0.47%   |
| MOTILE M141                     | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 38        | 18.01%  |
| 2018 | 21        | 9.95%   |
| 2019 | 18        | 8.53%   |
| 2021 | 17        | 8.06%   |
| 2011 | 17        | 8.06%   |
| 2013 | 15        | 7.11%   |
| 2022 | 12        | 5.69%   |
| 2014 | 12        | 5.69%   |
| 2015 | 10        | 4.74%   |
| 2012 | 9         | 4.27%   |
| 2017 | 8         | 3.79%   |
| 2016 | 7         | 3.32%   |
| 2023 | 6         | 2.84%   |
| 2010 | 6         | 2.84%   |
| 2024 | 5         | 2.37%   |
| 2008 | 3         | 1.42%   |
| 2006 | 3         | 1.42%   |
| 2009 | 2         | 0.95%   |
| 2025 | 1         | 0.47%   |
| 2007 | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 211       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 206       | 97.63%  |
| Enabled  | 5         | 2.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 204       | 96.68%  |
| Yes  | 7         | 3.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 65        | 30.66%  |
| 8.01-16.0   | 44        | 20.75%  |
| 16.01-24.0  | 38        | 17.92%  |
| 3.01-4.0    | 31        | 14.62%  |
| 32.01-64.0  | 16        | 7.55%   |
| 24.01-32.0  | 7         | 3.3%    |
| 1.01-2.0    | 7         | 3.3%    |
| 64.01-256.0 | 4         | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 58        | 24.89%  |
| 1.01-2.0   | 58        | 24.89%  |
| 4.01-8.0   | 50        | 21.46%  |
| 3.01-4.0   | 35        | 15.02%  |
| 0.51-1.0   | 18        | 7.73%   |
| 8.01-16.0  | 8         | 3.43%   |
| 0.01-0.5   | 5         | 2.15%   |
| 16.01-24.0 | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 166       | 77.93%  |
| 2      | 42        | 19.72%  |
| 3      | 4         | 1.88%   |
| 0      | 1         | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 160       | 75.83%  |
| Yes       | 51        | 24.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 71.56%  |
| No        | 60        | 28.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 96.68%  |
| No        | 7         | 3.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 81.69%  |
| No        | 39        | 18.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 41        | 19.25%  |
| Russia       | 17        | 7.98%   |
| India        | 10        | 4.69%   |
| Brazil       | 10        | 4.69%   |
| Germany      | 9         | 4.23%   |
| Canada       | 9         | 4.23%   |
| Turkey       | 8         | 3.76%   |
| Italy        | 7         | 3.29%   |
| Spain        | 6         | 2.82%   |
| Poland       | 6         | 2.82%   |
| UK           | 5         | 2.35%   |
| Netherlands  | 5         | 2.35%   |
| Indonesia    | 5         | 2.35%   |
| France       | 5         | 2.35%   |
| Ukraine      | 4         | 1.88%   |
| Switzerland  | 4         | 1.88%   |
| Romania      | 4         | 1.88%   |
| Czechia      | 4         | 1.88%   |
| Vietnam      | 3         | 1.41%   |
| Bulgaria     | 3         | 1.41%   |
| Australia    | 3         | 1.41%   |
| Argentina    | 3         | 1.41%   |
| Sweden       | 2         | 0.94%   |
| Slovakia     | 2         | 0.94%   |
| Serbia       | 2         | 0.94%   |
| Portugal     | 2         | 0.94%   |
| Pakistan     | 2         | 0.94%   |
| Lithuania    | 2         | 0.94%   |
| Kuwait       | 2         | 0.94%   |
| Israel       | 2         | 0.94%   |
| Iran         | 2         | 0.94%   |
| Finland      | 2         | 0.94%   |
| Colombia     | 2         | 0.94%   |
| Bangladesh   | 2         | 0.94%   |
| Uzbekistan   | 1         | 0.47%   |
| Uruguay      | 1         | 0.47%   |
| Slovenia     | 1         | 0.47%   |
| Saudi Arabia | 1         | 0.47%   |
| Réunion     | 1         | 0.47%   |
| Peru         | 1         | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Prague            | 4         | 1.82%   |
| Amsterdam         | 4         | 1.82%   |
| Warsaw            | 3         | 1.36%   |
| St Petersburg     | 3         | 1.36%   |
| Paris             | 3         | 1.36%   |
| Moscow            | 3         | 1.36%   |
| Los Angeles       | 3         | 1.36%   |
| Jakarta           | 3         | 1.36%   |
| Istanbul          | 3         | 1.36%   |
| Frankfurt am Main | 3         | 1.36%   |
| Vilnius           | 2         | 0.91%   |
| Tel Aviv          | 2         | 0.91%   |
| Tampere           | 2         | 0.91%   |
| Sorocaba          | 2         | 0.91%   |
| Sofia             | 2         | 0.91%   |
| Seville           | 2         | 0.91%   |
| San Ramon         | 2         | 0.91%   |
| Samara            | 2         | 0.91%   |
| Rio de Janeiro    | 2         | 0.91%   |
| Omaha             | 2         | 0.91%   |
| New York          | 2         | 0.91%   |
| Neuchatel         | 2         | 0.91%   |
| Mira              | 2         | 0.91%   |
| Milton            | 2         | 0.91%   |
| Mandi             | 2         | 0.91%   |
| Kuwait City       | 2         | 0.91%   |
| Iasi              | 2         | 0.91%   |
| Dnipro            | 2         | 0.91%   |
| Brisbane          | 2         | 0.91%   |
| Biel/Bienne       | 2         | 0.91%   |
| Bengaluru         | 2         | 0.91%   |
| Ankara            | 2         | 0.91%   |
| Zurich            | 1         | 0.45%   |
| Zaporizhzhya      | 1         | 0.45%   |
| Zagreb            | 1         | 0.45%   |
| Woodbridge        | 1         | 0.45%   |
| Wigan             | 1         | 0.45%   |
| Whittier          | 1         | 0.45%   |
| Wem               | 1         | 0.45%   |
| Vienna            | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 43        | 55     | 16.86%  |
| Seagate                      | 24        | 24     | 9.41%   |
| Sandisk                      | 21        | 21     | 8.24%   |
| WDC                          | 17        | 20     | 6.67%   |
| Toshiba                      | 17        | 19     | 6.67%   |
| Intel                        | 14        | 18     | 5.49%   |
| Kingston                     | 12        | 13     | 4.71%   |
| SK hynix                     | 11        | 17     | 4.31%   |
| Micron Technology            | 8         | 10     | 3.14%   |
| HGST                         | 8         | 8      | 3.14%   |
| Crucial                      | 8         | 12     | 3.14%   |
| Unknown                      | 7         | 8      | 2.75%   |
| Phison Electronics           | 6         | 9      | 2.35%   |
| Hitachi                      | 6         | 7      | 2.35%   |
| China                        | 4         | 4      | 1.57%   |
| Micron/Crucial Technology    | 3         | 3      | 1.18%   |
| LITEON                       | 3         | 3      | 1.18%   |
| KIOXIA                       | 3         | 3      | 1.18%   |
| Apple                        | 3         | 4      | 1.18%   |
| WALRAM                       | 2         | 2      | 0.78%   |
| Solid State Storage          | 2         | 2      | 0.78%   |
| PNY                          | 2         | 2      | 0.78%   |
| MAXIO Technology (Hangzhou)  | 2         | 2      | 0.78%   |
| JMicron Technology           | 2         | 2      | 0.78%   |
| ADATA Technology             | 2         | 3      | 0.78%   |
| A-DATA Technology            | 2         | 2      | 0.78%   |
| Unknown                      | 2         | 2      | 0.78%   |
| USB3.0                       | 1         | 1      | 0.39%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.39%   |
| Timetec                      | 1         | 2      | 0.39%   |
| SPCC                         | 1         | 1      | 0.39%   |
| Silicon Motion               | 1         | 2      | 0.39%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.39%   |
| Realtek Semiconductor        | 1         | 1      | 0.39%   |
| Phison                       | 1         | 1      | 0.39%   |
| Patriot                      | 1         | 1      | 0.39%   |
| Lite-On                      | 1         | 1      | 0.39%   |
| Linux                        | 1         | 1      | 0.39%   |
| Lenovo                       | 1         | 1      | 0.39%   |
| LDLC                         | 1         | 5      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 7         | 2.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 5         | 1.89%   |
| Seagate ST500LT012-1DG142 500GB                    | 4         | 1.52%   |
| SanDisk NVMe SSD Drive 512GB                       | 4         | 1.52%   |
| Unknown MMC Card  32GB                             | 3         | 1.14%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 1.14%   |
| Toshiba MQ01ABD100 1TB                             | 3         | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 3         | 1.14%   |
| Phison E12 NVMe Controller 1TB                     | 3         | 1.14%   |
| Crucial CT1000MX500SSD1 1TB                        | 3         | 1.14%   |
| China SATA SSD 960GB                               | 3         | 1.14%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 2         | 0.76%   |
| WALRAM 240G                                        | 2         | 0.76%   |
| Unknown MMC Card  128GB                            | 2         | 0.76%   |
| Toshiba MQ04ABF100 1TB                             | 2         | 0.76%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 2         | 0.76%   |
| Samsung NVMe SSD Drive 1TB                         | 2         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 0.76%   |
| Samsung MZVL4512HBLU-00BTW 512GB                   | 2         | 0.76%   |
| Samsung MZNLH512HALU-00000 512GB SSD               | 2         | 0.76%   |
| Phison PCIe SSD 500GB                              | 2         | 0.76%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                | 2         | 0.76%   |
| Kingston SA400S37240G 240GB SSD                    | 2         | 0.76%   |
| Kingston SA400S37120G 120GB SSD                    | 2         | 0.76%   |
| Kingston OM8PCP3512F-AI1 512GB                     | 2         | 0.76%   |
| Intel SSDPEKNW512GZL 512GB                         | 2         | 0.76%   |
| Intel SSDPEKNU512GZ 512GB                          | 2         | 0.76%   |
| Hitachi HTS547550A9E384 500GB                      | 2         | 0.76%   |
| HGST HTS545050A7E680 500GB                         | 2         | 0.76%   |
| HGST HTS541010A9E680 1TB                           | 2         | 0.76%   |
| Crucial CT240BX500SSD1 240GB                       | 2         | 0.76%   |
| Apple SSD SM0256G 256GB                            | 2         | 0.76%   |
| Unknown                                            | 2         | 0.76%   |
| WDC WDS500G2B0A 500GB SSD                          | 1         | 0.38%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                   | 1         | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.38%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                     | 1         | 0.38%   |
| WDC WD5000LPVX-75V0TT0 500GB                       | 1         | 0.38%   |
| WDC WD5000LPVX-55V0TT0 500GB                       | 1         | 0.38%   |
| WDC WD5000BPVT-22HXZT3 500GB                       | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 24        | 24     | 34.78%  |
| Toshiba            | 15        | 17     | 21.74%  |
| WDC                | 12        | 14     | 17.39%  |
| HGST               | 8         | 8      | 11.59%  |
| Hitachi            | 6         | 7      | 8.7%    |
| USB3.0             | 1         | 1      | 1.45%   |
| Unknown            | 1         | 1      | 1.45%   |
| JMicron Technology | 1         | 1      | 1.45%   |
| Colorful           | 1         | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 16     | 21.74%  |
| Kingston            | 8         | 8      | 11.59%  |
| Crucial             | 8         | 12     | 11.59%  |
| WDC                 | 5         | 6      | 7.25%   |
| Micron Technology   | 4         | 6      | 5.8%    |
| China               | 4         | 4      | 5.8%    |
| SanDisk             | 3         | 3      | 4.35%   |
| Apple               | 3         | 4      | 4.35%   |
| SK hynix            | 2         | 2      | 2.9%    |
| PNY                 | 2         | 2      | 2.9%    |
| LITEON              | 2         | 2      | 2.9%    |
| Toshiba             | 1         | 1      | 1.45%   |
| SPCC                | 1         | 1      | 1.45%   |
| Patriot             | 1         | 1      | 1.45%   |
| Linux               | 1         | 1      | 1.45%   |
| LDLC                | 1         | 5      | 1.45%   |
| Intenso             | 1         | 1      | 1.45%   |
| Intel               | 1         | 1      | 1.45%   |
| INNOVATION IT       | 1         | 1      | 1.45%   |
| Hewlett-Packard     | 1         | 1      | 1.45%   |
| FORESEE             | 1         | 1      | 1.45%   |
| Dogfish             | 1         | 1      | 1.45%   |
| Apacer              | 1         | 1      | 1.45%   |
| AGI                 | 1         | 1      | 1.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 96        | 132    | 39.83%  |
| HDD     | 68        | 74     | 28.22%  |
| SSD     | 65        | 82     | 26.97%  |
| MMC     | 6         | 7      | 2.49%   |
| Unknown | 6         | 7      | 2.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 124       | 155    | 53.22%  |
| NVMe | 96        | 132    | 41.2%   |
| SAS  | 7         | 8      | 3%      |
| MMC  | 6         | 7      | 2.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 97     | 61.83%  |
| 0.51-1.0   | 42        | 49     | 32.06%  |
| 1.01-2.0   | 6         | 8      | 4.58%   |
| 4.01-10.0  | 2         | 2      | 1.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 60        | 27.65%  |
| 101-250        | 58        | 26.73%  |
| 501-1000       | 36        | 16.59%  |
| 1001-2000      | 20        | 9.22%   |
| 51-100         | 10        | 4.61%   |
| More than 3000 | 9         | 4.15%   |
| Unknown        | 9         | 4.15%   |
| 1-20           | 7         | 3.23%   |
| 2001-3000      | 5         | 2.3%    |
| 21-50          | 3         | 1.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 59        | 25.76%  |
| 101-250        | 45        | 19.65%  |
| 21-50          | 35        | 15.28%  |
| 51-100         | 28        | 12.23%  |
| 251-500        | 23        | 10.04%  |
| 501-1000       | 15        | 6.55%   |
| 1001-2000      | 11        | 4.8%    |
| Unknown        | 9         | 3.93%   |
| More than 3000 | 2         | 0.87%   |
| 2001-3000      | 1         | 0.44%   |
| 0              | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                 | Notebooks | Drives | Percent |
|-------------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                                | 2         | 2      | 9.09%   |
| HGST HTS545050A7E680 500GB                            | 2         | 2      | 9.09%   |
| HGST HTS541010A9E680 1TB                              | 2         | 2      | 9.09%   |
| WDC WD5000LPVX-55V0TT0 500GB                          | 1         | 1      | 4.55%   |
| WDC WD3200LPVT-00FMCT0 320GB                          | 1         | 1      | 4.55%   |
| WDC WD3200BEKT-60F3T1 320GB                           | 1         | 1      | 4.55%   |
| WDC WD10SPCX-24HWST1 1TB                              | 1         | 1      | 4.55%   |
| Toshiba MQ01ACF032 320GB                              | 1         | 1      | 4.55%   |
| Toshiba MQ01ABF050 500GB                              | 1         | 1      | 4.55%   |
| Toshiba MK5065GSX 500GB                               | 1         | 1      | 4.55%   |
| Toshiba MK3276GSX 320GB                               | 1         | 1      | 4.55%   |
| Seagate ST500LT012-9WS142 500GB                       | 1         | 1      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB                       | 1         | 1      | 4.55%   |
| Seagate ST1000LM035-1RK172 1TB                        | 1         | 1      | 4.55%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD      | 1         | 1      | 4.55%   |
| Realtek Semiconductor RTS5762 NVMe SSD Controller 1TB | 1         | 1      | 4.55%   |
| LDLC SSD 120GB                                        | 1         | 3      | 4.55%   |
| Hitachi HTS547550A9E384 500GB                         | 1         | 1      | 4.55%   |
| Hitachi HTS542516K9SA00 160GB                         | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Toshiba               | 6         | 6      | 27.27%  |
| WDC                   | 4         | 4      | 18.18%  |
| HGST                  | 4         | 4      | 18.18%  |
| Seagate               | 3         | 3      | 13.64%  |
| Hitachi               | 2         | 2      | 9.09%   |
| Samsung Electronics   | 1         | 1      | 4.55%   |
| Realtek Semiconductor | 1         | 1      | 4.55%   |
| LDLC                  | 1         | 3      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 31.58%  |
| WDC     | 4         | 4      | 21.05%  |
| HGST    | 4         | 4      | 21.05%  |
| Seagate | 3         | 3      | 15.79%  |
| Hitachi | 2         | 2      | 10.53%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 19     | 86.36%  |
| SSD  | 2         | 4      | 9.09%   |
| NVMe | 1         | 1      | 4.55%   |

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
| Works    | 109       | 144    | 47.81%  |
| Detected | 97        | 134    | 42.54%  |
| Malfunc  | 22        | 24     | 9.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 128       | 50.2%   |
| AMD                            | 31        | 12.16%  |
| Samsung Electronics            | 30        | 11.76%  |
| SanDisk                        | 18        | 7.06%   |
| SK hynix                       | 9         | 3.53%   |
| Phison Electronics             | 6         | 2.35%   |
| Micron Technology              | 4         | 1.57%   |
| Kingston Technology Company    | 4         | 1.57%   |
| ADATA Technology               | 4         | 1.57%   |
| Micron/Crucial Technology      | 3         | 1.18%   |
| KIOXIA                         | 3         | 1.18%   |
| Union Memory (Shenzhen)        | 2         | 0.78%   |
| Solid State Storage Technology | 2         | 0.78%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.78%   |
| VIA Technologies               | 1         | 0.39%   |
| Toshiba America Info Systems   | 1         | 0.39%   |
| Silicon Motion                 | 1         | 0.39%   |
| Shenzhen Longsys Electronics   | 1         | 0.39%   |
| Realtek Semiconductor          | 1         | 0.39%   |
| Nvidia                         | 1         | 0.39%   |
| Marvell Technology Group       | 1         | 0.39%   |
| Lite-On Technology             | 1         | 0.39%   |
| Lenovo                         | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 28        | 10.57%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 18        | 6.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 17        | 6.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 13        | 4.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 12        | 4.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 11        | 4.15%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 9         | 3.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 8         | 3.02%   |
| Intel Volume Management Device NVMe RAID Controller                           | 8         | 3.02%   |
| Intel SSD 670p Series [Keystone Harbor]                                       | 6         | 2.26%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 5         | 1.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 5         | 1.89%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                         | 4         | 1.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 4         | 1.51%   |
| Phison E12 NVMe Controller                                                    | 4         | 1.51%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                 | 4         | 1.51%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                              | 4         | 1.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 4         | 1.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 4         | 1.51%   |
| SK hynix PC611 NVMe Solid State Drive                                         | 3         | 1.13%   |
| Intel Tiger Lake-LP SATA Controller                                           | 3         | 1.13%   |
| Intel SSD 660P Series                                                         | 3         | 1.13%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 3         | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 3         | 1.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 3         | 1.13%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                | 2         | 0.75%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                            | 2         | 0.75%   |
| SK hynix BC511 NVMe SSD                                                       | 2         | 0.75%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                  | 2         | 0.75%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 2         | 0.75%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)     | 2         | 0.75%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 2         | 0.75%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                 | 2         | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 0.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 2         | 0.75%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 2         | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 0.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                         | 2         | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 135       | 52.73%  |
| NVMe | 97        | 37.89%  |
| RAID | 21        | 8.2%    |
| IDE  | 3         | 1.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 153       | 72.51%  |
| AMD          | 57        | 27.01%  |
| CentaurHauls | 1         | 0.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 2.36%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 2.36%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.89%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 1.89%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.42%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 1.42%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 3         | 1.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.42%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 3         | 1.42%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.42%   |
| AMD Ryzen 7 8845HS w/ Radeon 780M Graphics    | 3         | 1.42%   |
| AMD Ryzen 7 7730U with Radeon Graphics        | 3         | 1.42%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.42%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.42%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.94%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.94%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.94%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.94%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.94%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.94%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.94%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 2         | 0.94%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.94%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.94%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.94%   |
| Intel 12th Gen Core i5-1240P                  | 2         | 0.94%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.94%   |
| AMD Ryzen 5 7520U with Radeon Graphics        | 2         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 45        | 21.33%  |
| Intel Core i7           | 42        | 19.91%  |
| AMD Ryzen 7             | 22        | 10.43%  |
| Other                   | 21        | 9.95%   |
| Intel Core i3           | 16        | 7.58%   |
| AMD Ryzen 5             | 14        | 6.64%   |
| Intel Celeron           | 10        | 4.74%   |
| Intel Pentium           | 7         | 3.32%   |
| AMD Ryzen 3             | 5         | 2.37%   |
| Intel Atom              | 3         | 1.42%   |
| AMD Ryzen 9             | 3         | 1.42%   |
| AMD Athlon              | 3         | 1.42%   |
| Intel Core m3           | 2         | 0.95%   |
| Intel Core i9           | 2         | 0.95%   |
| Intel Core 2 Duo        | 2         | 0.95%   |
| AMD E1                  | 2         | 0.95%   |
| AMD A10                 | 2         | 0.95%   |
| Intel Xeon              | 1         | 0.47%   |
| Intel Pentium Silver    | 1         | 0.47%   |
| Intel Pentium Dual-Core | 1         | 0.47%   |
| Intel Core 2 Extreme    | 1         | 0.47%   |
| CentaurHauls VIA Nano   | 1         | 0.47%   |
| AMD Ryzen 7 PRO         | 1         | 0.47%   |
| AMD Ryzen 5 PRO         | 1         | 0.47%   |
| AMD Phenom II           | 1         | 0.47%   |
| AMD A6                  | 1         | 0.47%   |
| AMD A4                  | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 86        | 40.76%  |
| 4      | 74        | 35.07%  |
| 8      | 27        | 12.8%   |
| 6      | 17        | 8.06%   |
| 12     | 3         | 1.42%   |
| 10     | 2         | 0.95%   |
| 14     | 1         | 0.47%   |
| 3      | 1         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 210       | 99.53%  |
| 2      | 1         | 0.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 167       | 79.15%  |
| 1      | 44        | 20.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 211       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 106       | 49.07%  |
| 0x306a9    | 10        | 4.63%   |
| 0x206a7    | 9         | 4.17%   |
| 0xa0652    | 6         | 2.78%   |
| 0x806ec    | 5         | 2.31%   |
| 0x806e9    | 5         | 2.31%   |
| 0x806c1    | 5         | 2.31%   |
| 0x40651    | 5         | 2.31%   |
| 0x306d4    | 5         | 2.31%   |
| 0x08600106 | 5         | 2.31%   |
| 0x806ea    | 4         | 1.85%   |
| 0x706e5    | 4         | 1.85%   |
| 0x706a1    | 4         | 1.85%   |
| 0x906ea    | 3         | 1.39%   |
| 0x906e9    | 3         | 1.39%   |
| 0x08608103 | 3         | 1.39%   |
| 0x08108109 | 3         | 1.39%   |
| 0x30678    | 2         | 0.93%   |
| 0x1067a    | 2         | 0.93%   |
| 0x08600103 | 2         | 0.93%   |
| 0x08108102 | 2         | 0.93%   |
| 0x08101007 | 2         | 0.93%   |
| 0x906ed    | 1         | 0.46%   |
| 0x906a3    | 1         | 0.46%   |
| 0x806eb    | 1         | 0.46%   |
| 0x806d1    | 1         | 0.46%   |
| 0x806c2    | 1         | 0.46%   |
| 0x506e3    | 1         | 0.46%   |
| 0x506c9    | 1         | 0.46%   |
| 0x406e3    | 1         | 0.46%   |
| 0x306c3    | 1         | 0.46%   |
| 0x20655    | 1         | 0.46%   |
| 0x0a704103 | 1         | 0.46%   |
| 0x0a50000c | 1         | 0.46%   |
| 0x08701013 | 1         | 0.46%   |
| 0x08600109 | 1         | 0.46%   |
| 0x08600104 | 1         | 0.46%   |
| 0x0810100b | 1         | 0.46%   |
| 0x08001137 | 1         | 0.46%   |
| 0x0700010b | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 40        | 18.96%  |
| Unknown          | 21        | 9.95%   |
| IvyBridge        | 19        | 9%      |
| SandyBridge      | 15        | 7.11%   |
| Zen 2            | 13        | 6.16%   |
| TigerLake        | 11        | 5.21%   |
| Broadwell        | 11        | 5.21%   |
| Zen+             | 10        | 4.74%   |
| Silvermont       | 8         | 3.79%   |
| Haswell          | 8         | 3.79%   |
| CometLake        | 7         | 3.32%   |
| Skylake          | 6         | 2.84%   |
| Zen 3            | 5         | 2.37%   |
| IceLake          | 5         | 2.37%   |
| Alderlake Hybrid | 5         | 2.37%   |
| Zen              | 4         | 1.9%    |
| Penryn           | 4         | 1.9%    |
| Goldmont plus    | 4         | 1.9%    |
| Westmere         | 3         | 1.42%   |
| Steamroller      | 2         | 0.95%   |
| Nehalem          | 2         | 0.95%   |
| Jaguar           | 2         | 0.95%   |
| Excavator        | 2         | 0.95%   |
| Puma             | 1         | 0.47%   |
| K10              | 1         | 0.47%   |
| Goldmont         | 1         | 0.47%   |
| Bonnell          | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 143       | 55.21%  |
| AMD              | 63        | 24.32%  |
| Nvidia           | 52        | 20.08%  |
| VIA Technologies | 1         | 0.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 6.42%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 13        | 4.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 4.91%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 11        | 4.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 3.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 3.4%    |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 8         | 3.02%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 7         | 2.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.64%   |
| AMD Lucienne                                                                             | 7         | 2.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.51%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 4         | 1.51%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.51%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.13%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.13%   |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 1.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.13%   |
| Intel Broadwell-U GT3 [HD Graphics 6000]                                                 | 3         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.13%   |
| AMD Mendocino [Radeon 610M]                                                              | 3         | 1.13%   |
| AMD HawkPoint1                                                                           | 3         | 1.13%   |
| AMD Barcelo                                                                              | 3         | 1.13%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                         | 2         | 0.75%   |
| Nvidia GP108M [GeForce MX330]                                                            | 2         | 0.75%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.75%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.75%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.75%   |
| Intel UHD Graphics 615                                                                   | 2         | 0.75%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.75%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 2         | 0.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 97        | 45.75%  |
| 1 x AMD        | 51        | 24.06%  |
| Intel + Nvidia | 40        | 18.87%  |
| 1 x Nvidia     | 8         | 3.77%   |
| 2 x AMD        | 5         | 2.36%   |
| Intel + AMD    | 4         | 1.89%   |
| AMD + Nvidia   | 4         | 1.89%   |
| 2 x Intel      | 2         | 0.94%   |
| 1 x VIA        | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 184       | 86.38%  |
| Proprietary | 26        | 12.21%  |
| Unknown     | 3         | 1.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 147       | 69.01%  |
| 0.01-0.5   | 26        | 12.21%  |
| 1.01-2.0   | 18        | 8.45%   |
| 0.51-1.0   | 8         | 3.76%   |
| 3.01-4.0   | 7         | 3.29%   |
| 7.01-8.0   | 3         | 1.41%   |
| 5.01-6.0   | 3         | 1.41%   |
| 2.01-3.0   | 1         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 48        | 19.67%  |
| BOE                     | 43        | 17.62%  |
| Chimei Innolux          | 37        | 15.16%  |
| LG Display              | 30        | 12.3%   |
| Samsung Electronics     | 17        | 6.97%   |
| Lenovo                  | 7         | 2.87%   |
| Chi Mei Optoelectronics | 6         | 2.46%   |
| Goldstar                | 5         | 2.05%   |
| Apple                   | 5         | 2.05%   |
| Dell                    | 4         | 1.64%   |
| ASUSTek Computer        | 4         | 1.64%   |
| Sharp                   | 3         | 1.23%   |
| Philips                 | 3         | 1.23%   |
| PANDA                   | 3         | 1.23%   |
| InfoVision              | 3         | 1.23%   |
| Hewlett-Packard         | 3         | 1.23%   |
| Acer                    | 3         | 1.23%   |
| ViewSonic               | 2         | 0.82%   |
| CSOT                    | 2         | 0.82%   |
| BenQ                    | 2         | 0.82%   |
| Unknown                 | 1         | 0.41%   |
| TMX                     | 1         | 0.41%   |
| Sony                    | 1         | 0.41%   |
| MTV                     | 1         | 0.41%   |
| MSI                     | 1         | 0.41%   |
| LGD                     | 1         | 0.41%   |
| KDC                     | 1         | 0.41%   |
| IBM                     | 1         | 0.41%   |
| HUAWEI                  | 1         | 0.41%   |
| HKC                     | 1         | 0.41%   |
| CSO                     | 1         | 0.41%   |
| Aosiman                 | 1         | 0.41%   |
| AOC                     | 1         | 0.41%   |
| Ancor Communications    | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 4         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 3         | 1.23%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 3         | 1.23%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 3         | 1.23%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 3         | 1.23%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 2         | 0.82%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.82%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 2         | 0.82%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 0.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch          | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch          | 2         | 0.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.82%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 0.82%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 0.82%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 0.82%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                     | 2         | 0.82%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                      | 2         | 0.82%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 0.82%   |
| BOE LCD Monitor BOE0618 1366x768 277x156mm 12.5-inch                      | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch            | 2         | 0.82%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch             | 1         | 0.41%   |
| ViewSonic VA2256 Series VSC3136 1920x1080 476x268mm 21.5-inch             | 1         | 0.41%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 0.41%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                   | 1         | 0.41%   |
| Sony BW8 MS_9001 2560x1600                                                | 1         | 0.41%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.41%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.41%   |
| Sharp LC-42D69U SHP0080 1920x1080 930x523mm 42.0-inch                     | 1         | 0.41%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.41%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.41%   |
| Samsung Electronics LS27A800U SAM71A1 3840x2160 597x336mm 27.0-inch       | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch      | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch      | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 107       | 46.72%  |
| 1366x768 (WXGA)    | 67        | 29.26%  |
| 2560x1600          | 9         | 3.93%   |
| 2560x1440 (QHD)    | 8         | 3.49%   |
| 3840x2160 (4K)     | 7         | 3.06%   |
| 1600x900 (HD+)     | 7         | 3.06%   |
| 1440x900 (WXGA+)   | 7         | 3.06%   |
| 1920x1200 (WUXGA)  | 6         | 2.62%   |
| 1680x1050 (WSXGA+) | 2         | 0.87%   |
| 3456x2160          | 1         | 0.44%   |
| 3440x1440          | 1         | 0.44%   |
| 3072x1920          | 1         | 0.44%   |
| 2880x1800          | 1         | 0.44%   |
| 2288x1287          | 1         | 0.44%   |
| 2256x1504          | 1         | 0.44%   |
| 2240x1400          | 1         | 0.44%   |
| 2160x1440          | 1         | 0.44%   |
| 1280x800 (WXGA)    | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 97        | 39.92%  |
| 14      | 37        | 15.23%  |
| 13      | 34        | 13.99%  |
| 17      | 13        | 5.35%   |
| 27      | 10        | 4.12%   |
| 24      | 9         | 3.7%    |
| 21      | 9         | 3.7%    |
| 16      | 9         | 3.7%    |
| 12      | 5         | 2.06%   |
| 11      | 5         | 2.06%   |
| 31      | 3         | 1.23%   |
| 23      | 3         | 1.23%   |
| 142     | 1         | 0.41%   |
| 42      | 1         | 0.41%   |
| 34      | 1         | 0.41%   |
| 32      | 1         | 0.41%   |
| 28      | 1         | 0.41%   |
| 20      | 1         | 0.41%   |
| 19      | 1         | 0.41%   |
| 8       | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 157       | 64.88%  |
| 201-300        | 23        | 9.5%    |
| 501-600        | 20        | 8.26%   |
| 351-400        | 19        | 7.85%   |
| 401-500        | 11        | 4.55%   |
| 601-700        | 6         | 2.48%   |
| 701-800        | 2         | 0.83%   |
| More than 2000 | 1         | 0.41%   |
| 101-200        | 1         | 0.41%   |
| 901-1000       | 1         | 0.41%   |
| Unknown        | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 178       | 84.36%  |
| 16/10   | 27        | 12.8%   |
| 3/2     | 2         | 0.95%   |
| 21/9    | 1         | 0.47%   |
| 1.00    | 1         | 0.47%   |
| 0.62    | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 99        | 40.91%  |
| 81-90          | 59        | 24.38%  |
| 201-250        | 17        | 7.02%   |
| 71-80          | 11        | 4.55%   |
| 121-130        | 11        | 4.55%   |
| 301-350        | 10        | 4.13%   |
| 111-120        | 7         | 2.89%   |
| 351-500        | 6         | 2.48%   |
| 61-70          | 5         | 2.07%   |
| 51-60          | 5         | 2.07%   |
| 251-300        | 3         | 1.24%   |
| 151-200        | 3         | 1.24%   |
| 131-140        | 2         | 0.83%   |
| More than 1000 | 1         | 0.41%   |
| 1-40           | 1         | 0.41%   |
| 501-1000       | 1         | 0.41%   |
| Unknown        | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 113       | 48.09%  |
| 101-120       | 62        | 26.38%  |
| 51-100        | 33        | 14.04%  |
| 161-240       | 20        | 8.51%   |
| More than 240 | 5         | 2.13%   |
| 1-50          | 1         | 0.43%   |
| Unknown       | 1         | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 174       | 81.31%  |
| 2     | 39        | 18.22%  |
| 0     | 1         | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 117       | 35.67%  |
| Intel                                  | 106       | 32.32%  |
| Qualcomm Atheros                       | 35        | 10.67%  |
| MediaTek                               | 16        | 4.88%   |
| Broadcom                               | 15        | 4.57%   |
| Qualcomm                               | 5         | 1.52%   |
| Broadcom Limited                       | 5         | 1.52%   |
| Samsung Electronics                    | 4         | 1.22%   |
| TP-Link                                | 3         | 0.91%   |
| Ralink                                 | 3         | 0.91%   |
| Xiaomi                                 | 2         | 0.61%   |
| ASIX Electronics                       | 2         | 0.61%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.3%    |
| Sierra Wireless                        | 1         | 0.3%    |
| Ralink Technology                      | 1         | 0.3%    |
| PAX                                    | 1         | 0.3%    |
| OPPO Electronics                       | 1         | 0.3%    |
| Marvell Technology Group               | 1         | 0.3%    |
| Linksys                                | 1         | 0.3%    |
| Lenovo                                 | 1         | 0.3%    |
| ICS Advent                             | 1         | 0.3%    |
| Huawei Technologies                    | 1         | 0.3%    |
| Dell                                   | 1         | 0.3%    |
| D-Link                                 | 1         | 0.3%    |
| Castles Technology                     | 1         | 0.3%    |
| Aquantia                               | 1         | 0.3%    |
| Apple                                  | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 66        | 16.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 4.6%    |
| Intel Wireless 8265 / 8275                                             | 16        | 4.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 14        | 3.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 3.32%   |
| Intel Wi-Fi 6 AX200                                                    | 12        | 3.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 2.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 2.05%   |
| Intel Wi-Fi 6 AX201                                                    | 8         | 2.05%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 7         | 1.79%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6         | 1.53%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 6         | 1.53%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 6         | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 1.28%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]   | 5         | 1.28%   |
| Intel Wireless 7265                                                    | 5         | 1.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 5         | 1.28%   |
| Realtek 802.11ac NIC                                                   | 4         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4         | 1.02%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 1.02%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 4         | 1.02%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 0.77%   |
| Intel Wireless 7260                                                    | 3         | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 3         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 0.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 0.77%   |
| Intel Centrino Wireless-N 2230                                         | 3         | 0.77%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.51%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                         | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 97        | 44.7%   |
| Realtek Semiconductor | 44        | 20.28%  |
| Qualcomm Atheros      | 30        | 13.82%  |
| MediaTek              | 16        | 7.37%   |
| Broadcom              | 14        | 6.45%   |
| Broadcom Limited      | 5         | 2.3%    |
| TP-Link               | 3         | 1.38%   |
| Ralink                | 3         | 1.38%   |
| Qualcomm              | 2         | 0.92%   |
| Sierra Wireless       | 1         | 0.46%   |
| Ralink Technology     | 1         | 0.46%   |
| D-Link                | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 16        | 7.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 14        | 6.36%   |
| Intel Wi-Fi 6 AX200                                                  | 12        | 5.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 10        | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 8         | 3.64%   |
| Intel Wi-Fi 6 AX201                                                  | 8         | 3.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 3.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 3.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 6         | 2.73%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 6         | 2.73%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 6         | 2.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5         | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 2.27%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310] | 5         | 2.27%   |
| Intel Wireless 7265                                                  | 5         | 2.27%   |
| Broadcom BCM43142 802.11b/g/n                                        | 5         | 2.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 2.27%   |
| Realtek 802.11ac NIC                                                 | 4         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 4         | 1.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 4         | 1.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 1.82%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 4         | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 3         | 1.36%   |
| Intel Wireless 7260                                                  | 3         | 1.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 1.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3         | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 3         | 1.36%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 1.36%   |
| Intel Centrino Ultimate-N 6300                                       | 3         | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 1.36%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                       | 2         | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2         | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2         | 0.91%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 2         | 0.91%   |
| Intel Wireless 3165                                                  | 2         | 0.91%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 0.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 2         | 0.91%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 94        | 56.97%  |
| Intel                                  | 40        | 24.24%  |
| Qualcomm Atheros                       | 9         | 5.45%   |
| Samsung Electronics                    | 4         | 2.42%   |
| Qualcomm                               | 3         | 1.82%   |
| Xiaomi                                 | 2         | 1.21%   |
| Broadcom                               | 2         | 1.21%   |
| ASIX Electronics                       | 2         | 1.21%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.61%   |
| OPPO Electronics                       | 1         | 0.61%   |
| Marvell Technology Group               | 1         | 0.61%   |
| Linksys                                | 1         | 0.61%   |
| Lenovo                                 | 1         | 0.61%   |
| ICS Advent                             | 1         | 0.61%   |
| Huawei Technologies                    | 1         | 0.61%   |
| Aquantia                               | 1         | 0.61%   |
| Apple                                  | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 66        | 39.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 10.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 7.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 5.36%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 4.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.79%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 1.19%   |
| Qualcomm YUPIK-QRD _SN:AC1D5909                                        | 2         | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.19%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.19%   |
| Intel Ethernet Connection (11) I219-LM                                 | 2         | 1.19%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 1         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.6%    |
| Qualcomm A0001                                                         | 1         | 0.6%    |
| OPPO Ace 3V                                                            | 1         | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.6%    |
| Linksys Gigabit Ethernet Adapter                                       | 1         | 0.6%    |
| Lenovo USB-C Dock Ethernet                                             | 1         | 0.6%    |
| Intel WiMAX Connection 2400m                                           | 1         | 0.6%    |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.6%    |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.6%    |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.6%    |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 0.6%    |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 0.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1         | 0.6%    |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 204       | 57.3%   |
| Ethernet | 151       | 42.42%  |
| Modem    | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 175       | 80.65%  |
| Ethernet | 41        | 18.89%  |
| Modem    | 1         | 0.46%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 131       | 61.79%  |
| 1     | 76        | 35.85%  |
| 3     | 3         | 1.42%   |
| 0     | 2         | 0.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 170       | 78.34%  |
| Yes  | 47        | 21.66%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 43.75%  |
| Realtek Semiconductor           | 28        | 15.91%  |
| IMC Networks                    | 17        | 9.66%   |
| Broadcom                        | 11        | 6.25%   |
| Foxconn / Hon Hai               | 9         | 5.11%   |
| Qualcomm Atheros Communications | 8         | 4.55%   |
| Lite-On Technology              | 7         | 3.98%   |
| Apple                           | 5         | 2.84%   |
| Realtek                         | 3         | 1.7%    |
| MediaTek                        | 3         | 1.7%    |
| Dell                            | 2         | 1.14%   |
| Cambridge Silicon Radio         | 2         | 1.14%   |
| Ralink                          | 1         | 0.57%   |
| Hewlett-Packard                 | 1         | 0.57%   |
| Foxconn International           | 1         | 0.57%   |
| ASUSTek Computer                | 1         | 0.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 24        | 13.56%  |
| Realtek Bluetooth Radio                             | 22        | 12.43%  |
| Intel AX201 Bluetooth                               | 18        | 10.17%  |
| Intel AX200 Bluetooth                               | 11        | 6.21%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 5.65%   |
| IMC Networks Wireless_Device                        | 10        | 5.65%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 2.82%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.26%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 2.26%   |
| Intel Bluetooth Device                              | 4         | 2.26%   |
| IMC Networks Bluetooth Device                       | 4         | 2.26%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 2.26%   |
| Realtek Bluetooth Radio                             | 3         | 1.69%   |
| MediaTek Wireless_Device                            | 3         | 1.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.69%   |
| Intel AX210 Bluetooth                               | 3         | 1.69%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.69%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.69%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.13%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 1.13%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 1.13%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.13%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.13%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.13%   |
| Apple Bluetooth Host Controller                     | 2         | 1.13%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.56%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.56%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.56%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.56%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.56%   |
| Lite-On Bluetooth Device                            | 1         | 0.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.56%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.56%   |
| Broadcom HP Portable Valentine                      | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 151       | 57.41%  |
| AMD                    | 60        | 22.81%  |
| Nvidia                 | 32        | 12.17%  |
| Realtek Semiconductor  | 3         | 1.14%   |
| C-Media Electronics    | 3         | 1.14%   |
| VIA Technologies       | 1         | 0.38%   |
| Texas Instruments      | 1         | 0.38%   |
| Plantronics            | 1         | 0.38%   |
| MV-SILICON             | 1         | 0.38%   |
| Lenovo                 | 1         | 0.38%   |
| Hewlett-Packard        | 1         | 0.38%   |
| Harman                 | 1         | 0.38%   |
| GN Netcom              | 1         | 0.38%   |
| Generalplus Technology | 1         | 0.38%   |
| Focusrite-Novation     | 1         | 0.38%   |
| DSEA A/S               | 1         | 0.38%   |
| Corsair                | 1         | 0.38%   |
| ASUSTek Computer       | 1         | 0.38%   |
| Apple                  | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 46        | 13.61%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 8.28%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 21        | 6.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 5.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 4.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 3.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 3.25%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 3.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 2.96%   |
| AMD Radeon High Definition Audio Controller                                                       | 10        | 2.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 2.07%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 1.78%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.48%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.48%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.18%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.18%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.18%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.18%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.89%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 3         | 0.89%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.89%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.59%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.59%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.59%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 0.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.59%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 64        | 28.7%   |
| SK hynix            | 49        | 21.97%  |
| Micron Technology   | 25        | 11.21%  |
| Kingston            | 21        | 9.42%   |
| Unknown             | 13        | 5.83%   |
| A-DATA Technology   | 8         | 3.59%   |
| Crucial             | 7         | 3.14%   |
| Unknown             | 5         | 2.24%   |
| Smart               | 4         | 1.79%   |
| Ramaxel Technology  | 4         | 1.79%   |
| Corsair             | 4         | 1.79%   |
| Team                | 3         | 1.35%   |
| Silicon Power       | 3         | 1.35%   |
| Nanya Technology    | 3         | 1.35%   |
| Unknown (ABCD)      | 2         | 0.9%    |
| Smart Brazil        | 1         | 0.45%   |
| Patriot             | 1         | 0.45%   |
| GOODRAM             | 1         | 0.45%   |
| Elpida              | 1         | 0.45%   |
| Avant               | 1         | 0.45%   |
| ASint Technology    | 1         | 0.45%   |
| Apacer              | 1         | 0.45%   |
| AMD                 | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 2.17%   |
| Unknown                                                          | 5         | 2.17%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.74%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 1.74%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.3%    |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 3         | 1.3%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.3%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 3         | 1.3%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.3%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.87%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.87%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.87%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.87%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.87%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.87%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.87%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.87%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 0.87%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.87%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.87%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.87%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.87%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.87%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.87%   |
| Micron RAM MT62F1G32D4DR-031 4GB SODIMM LPDDR5 5500MT/s          | 2         | 0.87%   |
| A-DATA RAM AD5S560016G-SFW 16GiB SODIMM DDR5 5600MT/s            | 2         | 0.87%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 87        | 50%     |
| DDR3    | 60        | 34.48%  |
| DDR5    | 7         | 4.02%   |
| LPDDR3  | 6         | 3.45%   |
| LPDDR5  | 5         | 2.87%   |
| LPDDR4  | 5         | 2.87%   |
| SDRAM   | 2         | 1.15%   |
| DDR2    | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 153       | 86.44%  |
| Row Of Chips | 19        | 10.73%  |
| DIMM         | 2         | 1.13%   |
| Unknown      | 2         | 1.13%   |
| Chip         | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 70        | 35.18%  |
| 8192  | 66        | 33.17%  |
| 16384 | 36        | 18.09%  |
| 2048  | 16        | 8.04%   |
| 32768 | 9         | 4.52%   |
| 1024  | 2         | 1.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 52        | 26.94%  |
| 3200  | 46        | 23.83%  |
| 2667  | 35        | 18.13%  |
| 2400  | 13        | 6.74%   |
| 1333  | 9         | 4.66%   |
| 2133  | 6         | 3.11%   |
| 1334  | 6         | 3.11%   |
| 4800  | 4         | 2.07%   |
| 5600  | 3         | 1.55%   |
| 7500  | 2         | 1.04%   |
| 5500  | 2         | 1.04%   |
| 4199  | 2         | 1.04%   |
| 3266  | 2         | 1.04%   |
| 1867  | 2         | 1.04%   |
| 800   | 2         | 1.04%   |
| 6400  | 1         | 0.52%   |
| 4267  | 1         | 0.52%   |
| 3800  | 1         | 0.52%   |
| 2933  | 1         | 0.52%   |
| 1067  | 1         | 0.52%   |
| 1066  | 1         | 0.52%   |
| 667   | 1         | 0.52%   |

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
| Chicony Electronics                    | 42        | 23.08%  |
| IMC Networks                           | 28        | 15.38%  |
| Bison Electronics                      | 20        | 10.99%  |
| Quanta                                 | 14        | 7.69%   |
| Realtek Semiconductor                  | 12        | 6.59%   |
| Microdia                               | 10        | 5.49%   |
| Syntek                                 | 7         | 3.85%   |
| Suyin                                  | 7         | 3.85%   |
| Luxvisions Innotech Limited            | 6         | 3.3%    |
| Sunplus Innovation Technology          | 5         | 2.75%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.75%   |
| Alcor Micro                            | 5         | 2.75%   |
| Sonix Technology                       | 4         | 2.2%    |
| Silicon Motion                         | 4         | 2.2%    |
| Lenovo                                 | 3         | 1.65%   |
| ShineTech                              | 2         | 1.1%    |
| SunplusIT                              | 1         | 0.55%   |
| ShineOptics                            | 1         | 0.55%   |
| Ricoh                                  | 1         | 0.55%   |
| Logitech                               | 1         | 0.55%   |
| Lite-On Technology                     | 1         | 0.55%   |
| LG Electronics                         | 1         | 0.55%   |
| kingcome                               | 1         | 0.55%   |
| Apple                                  | 1         | 0.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                 | 12        | 6.52%   |
| Chicony HD WebCam                                              | 8         | 4.35%   |
| Chicony Integrated Camera                                      | 7         | 3.8%    |
| Bison Integrated Camera                                        | 6         | 3.26%   |
| Sonix USB2.0 HD UVC WebCam                                     | 4         | 2.17%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 2.17%   |
| Microdia Integrated Webcam                                     | 4         | 2.17%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 4         | 2.17%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 4         | 2.17%   |
| Syntek Integrated Camera                                       | 3         | 1.63%   |
| Syntek EasyCamera                                              | 3         | 1.63%   |
| Sunplus HD WebCam                                              | 3         | 1.63%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 1.63%   |
| Microdia Integrated_Webcam_HD                                  | 3         | 1.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 3         | 1.63%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 3         | 1.63%   |
| Chicony Integrated Camera (1280x720@30)                        | 3         | 1.63%   |
| Chicony HP TrueVision HD Camera                                | 3         | 1.63%   |
| Bison Lenovo EasyCamera                                        | 3         | 1.63%   |
| Suyin HP Webcam                                                | 2         | 1.09%   |
| Silicon Motion 300k Pixel Camera                               | 2         | 1.09%   |
| ShineTech USB2.0 HD UVC WebCam                                 | 2         | 1.09%   |
| Realtek USB2.0 HD UVC WebCam                                   | 2         | 1.09%   |
| Realtek HD WebCam                                              | 2         | 1.09%   |
| Quanta VGA WebCam                                              | 2         | 1.09%   |
| Quanta USB2.0 VGA UVC WebCam                                   | 2         | 1.09%   |
| Quanta HP Webcam                                               | 2         | 1.09%   |
| Quanta HD Webcam                                               | 2         | 1.09%   |
| Lenovo UVC Camera                                              | 2         | 1.09%   |
| IMC Networks XiaoMi Webcam                                     | 2         | 1.09%   |
| IMC Networks 2M Integrated Webcam                              | 2         | 1.09%   |
| Chicony thinkpad t430s camera                                  | 2         | 1.09%   |
| Chicony Integrated IR Camera                                   | 2         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.09%   |
| Bison HD Webcam                                                | 2         | 1.09%   |
| Alcor Micro USB 2.0 Camera                                     | 2         | 1.09%   |
| Syntek HD WebCam                                               | 1         | 0.54%   |
| Suyin USB Webcam                                               | 1         | 0.54%   |
| Suyin NEC HD WebCam                                            | 1         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 34.62%  |
| Validity Sensors           | 6         | 23.08%  |
| Shenzhen Goodix Technology | 6         | 23.08%  |
| AuthenTec                  | 3         | 11.54%  |
| STMicroelectronics         | 1         | 3.85%   |
| Elan Microelectronics      | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 19.23%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 19.23%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 11.54%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 7.69%   |
| AuthenTec AES2810                                                          | 2         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.85%   |
| Validity Sensors VFS491                                                    | 1         | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 3.85%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.85%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 3.85%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 3.85%   |
| Elan ELAN:ARM-M4                                                           | 1         | 3.85%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 10        | 55.56%  |
| Alcor Micro      | 4         | 22.22%  |
| Lenovo           | 2         | 11.11%  |
| Upek             | 1         | 5.56%   |
| SCM Microsystems | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 11.11%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.56%   |
| SCM Microsystems SCT3522CC token                                             | 1         | 5.56%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 1         | 5.56%   |
| Broadcom 5880                                                                | 1         | 5.56%   |
| Broadcom 58200                                                               | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 135       | 62.79%  |
| 1     | 66        | 30.7%   |
| 2     | 11        | 5.12%   |
| 3     | 3         | 1.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 25        | 26.04%  |
| Graphics card            | 16        | 16.67%  |
| Chipcard                 | 15        | 15.63%  |
| Net/wireless             | 12        | 12.5%   |
| Multimedia controller    | 9         | 9.38%   |
| Camera                   | 6         | 6.25%   |
| Bluetooth                | 4         | 4.17%   |
| Communication controller | 3         | 3.13%   |
| Storage                  | 2         | 2.08%   |
| Net/ethernet             | 2         | 2.08%   |
| Network                  | 1         | 1.04%   |
| Dvb card                 | 1         | 1.04%   |

