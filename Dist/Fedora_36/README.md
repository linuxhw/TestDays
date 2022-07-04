Fedora 36 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_36/Desktop/README.md) and [notebooks](/Dist/Fedora_36/Notebook/README.md).

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

Total: 883

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T480 20L6S2EQ00    | Notebook    | [1b45ef7d10](https://linux-hardware.org/?probe=1b45ef7d10) | Jul 01, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [16413aeb23](https://linux-hardware.org/?probe=16413aeb23) | Jul 01, 2022 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8e6d23cf01](https://linux-hardware.org/?probe=8e6d23cf01) | Jul 01, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a32cb9b3f1](https://linux-hardware.org/?probe=a32cb9b3f1) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c9d0d64896](https://linux-hardware.org/?probe=c9d0d64896) | Jul 01, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [febb798e92](https://linux-hardware.org/?probe=febb798e92) | Jul 01, 2022 |
| Framework     | Laptop                      | Notebook    | [1089f37daf](https://linux-hardware.org/?probe=1089f37daf) | Jul 01, 2022 |
| Dell          | 0M9KCM A00                  | Desktop     | [e72232ee43](https://linux-hardware.org/?probe=e72232ee43) | Jul 01, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [c38c4e9cb9](https://linux-hardware.org/?probe=c38c4e9cb9) | Jun 30, 2022 |
| Dell          | 0M9KCM A00                  | Desktop     | [5e80242b43](https://linux-hardware.org/?probe=5e80242b43) | Jun 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | Notebook    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7e14880c80](https://linux-hardware.org/?probe=7e14880c80) | Jun 30, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [28479b3edf](https://linux-hardware.org/?probe=28479b3edf) | Jun 30, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [cea6c9ea52](https://linux-hardware.org/?probe=cea6c9ea52) | Jun 30, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [2049536427](https://linux-hardware.org/?probe=2049536427) | Jun 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [e6d7a2a642](https://linux-hardware.org/?probe=e6d7a2a642) | Jun 30, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [9c512247ff](https://linux-hardware.org/?probe=9c512247ff) | Jun 30, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | Notebook    | [4e15b37546](https://linux-hardware.org/?probe=4e15b37546) | Jun 30, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [85b8793585](https://linux-hardware.org/?probe=85b8793585) | Jun 29, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [1f9d3b4a6c](https://linux-hardware.org/?probe=1f9d3b4a6c) | Jun 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [01d9100427](https://linux-hardware.org/?probe=01d9100427) | Jun 29, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ddfd26738](https://linux-hardware.org/?probe=8ddfd26738) | Jun 29, 2022 |
| ASUSTek       | UX302LA                     | Notebook    | [6092e85ae8](https://linux-hardware.org/?probe=6092e85ae8) | Jun 29, 2022 |
| Getac         | B300-X                      | Notebook    | [eb752b6c15](https://linux-hardware.org/?probe=eb752b6c15) | Jun 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1eed1dcced](https://linux-hardware.org/?probe=1eed1dcced) | Jun 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [9c3e14320e](https://linux-hardware.org/?probe=9c3e14320e) | Jun 29, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [392d5c7c12](https://linux-hardware.org/?probe=392d5c7c12) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [43c87260b2](https://linux-hardware.org/?probe=43c87260b2) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Alienware     | 17                          | Notebook    | [715b5b0dce](https://linux-hardware.org/?probe=715b5b0dce) | Jun 29, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [c3172fd9cf](https://linux-hardware.org/?probe=c3172fd9cf) | Jun 28, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [b6cfc5d2df](https://linux-hardware.org/?probe=b6cfc5d2df) | Jun 28, 2022 |
| Dell          | Precision M6800             | Notebook    | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| Dell          | Latitude 5511               | Notebook    | [c361c37273](https://linux-hardware.org/?probe=c361c37273) | Jun 28, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [4ba4d14a1a](https://linux-hardware.org/?probe=4ba4d14a1a) | Jun 28, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [20de16a046](https://linux-hardware.org/?probe=20de16a046) | Jun 28, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d240efa39f](https://linux-hardware.org/?probe=d240efa39f) | Jun 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Toshiba       | Satellite C855-12R          | Notebook    | [e94a109546](https://linux-hardware.org/?probe=e94a109546) | Jun 28, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [239e8c86c0](https://linux-hardware.org/?probe=239e8c86c0) | Jun 28, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [c450ce45a6](https://linux-hardware.org/?probe=c450ce45a6) | Jun 28, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [5d2f94f859](https://linux-hardware.org/?probe=5d2f94f859) | Jun 28, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [ba68b99167](https://linux-hardware.org/?probe=ba68b99167) | Jun 27, 2022 |
| Dell          | Latitude E6520              | Notebook    | [f688527838](https://linux-hardware.org/?probe=f688527838) | Jun 27, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [d2b55252d8](https://linux-hardware.org/?probe=d2b55252d8) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [f20fc8c349](https://linux-hardware.org/?probe=f20fc8c349) | Jun 27, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3a651b23fb](https://linux-hardware.org/?probe=3a651b23fb) | Jun 26, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [2c7959c607](https://linux-hardware.org/?probe=2c7959c607) | Jun 26, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [3eb97735b3](https://linux-hardware.org/?probe=3eb97735b3) | Jun 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | Notebook    | [de3ca4e422](https://linux-hardware.org/?probe=de3ca4e422) | Jun 26, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [25e6653354](https://linux-hardware.org/?probe=25e6653354) | Jun 26, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [db6195eed2](https://linux-hardware.org/?probe=db6195eed2) | Jun 26, 2022 |
| Timi          | A35S                        | Notebook    | [606e376264](https://linux-hardware.org/?probe=606e376264) | Jun 26, 2022 |
| Dell          | Latitude 7300               | Notebook    | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [2f4500ddad](https://linux-hardware.org/?probe=2f4500ddad) | Jun 26, 2022 |
| HP            | 3398                        | Desktop     | [4241fd0ba0](https://linux-hardware.org/?probe=4241fd0ba0) | Jun 26, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [9a853085ea](https://linux-hardware.org/?probe=9a853085ea) | Jun 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [400eaba39f](https://linux-hardware.org/?probe=400eaba39f) | Jun 26, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [519e378380](https://linux-hardware.org/?probe=519e378380) | Jun 25, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [6c6d94e4b7](https://linux-hardware.org/?probe=6c6d94e4b7) | Jun 25, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [5948b56a82](https://linux-hardware.org/?probe=5948b56a82) | Jun 25, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [fa3d29c80b](https://linux-hardware.org/?probe=fa3d29c80b) | Jun 25, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [e8a4e37cc6](https://linux-hardware.org/?probe=e8a4e37cc6) | Jun 25, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [81a9b9847d](https://linux-hardware.org/?probe=81a9b9847d) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | Desktop     | [47cf388077](https://linux-hardware.org/?probe=47cf388077) | Jun 25, 2022 |
| Dell          | Inspiron 5437               | Notebook    | [e206b319a2](https://linux-hardware.org/?probe=e206b319a2) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [c3c48bb18e](https://linux-hardware.org/?probe=c3c48bb18e) | Jun 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d2e82f01d9](https://linux-hardware.org/?probe=d2e82f01d9) | Jun 25, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [c6c59e12b6](https://linux-hardware.org/?probe=c6c59e12b6) | Jun 25, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [607f489961](https://linux-hardware.org/?probe=607f489961) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [66f845b63e](https://linux-hardware.org/?probe=66f845b63e) | Jun 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [6e62883390](https://linux-hardware.org/?probe=6e62883390) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | Desktop     | [73eb3e0db6](https://linux-hardware.org/?probe=73eb3e0db6) | Jun 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [3b78b34416](https://linux-hardware.org/?probe=3b78b34416) | Jun 24, 2022 |
| HP            | 89D8 SMVB                   | Desktop     | [f92ff0c37f](https://linux-hardware.org/?probe=f92ff0c37f) | Jun 24, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [3e16709617](https://linux-hardware.org/?probe=3e16709617) | Jun 24, 2022 |
| HP            | Elite Dragonfly G2 Noteb... | Convertible | [7c532e5712](https://linux-hardware.org/?probe=7c532e5712) | Jun 24, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [d292d79bbe](https://linux-hardware.org/?probe=d292d79bbe) | Jun 24, 2022 |
| Lenovo        | ThinkPad T520 4243VE1       | Notebook    | [7fcfec26eb](https://linux-hardware.org/?probe=7fcfec26eb) | Jun 24, 2022 |
| MSI           | IONA                        | Desktop     | [9f4e8871a7](https://linux-hardware.org/?probe=9f4e8871a7) | Jun 24, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [2c0b9c6402](https://linux-hardware.org/?probe=2c0b9c6402) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [bb8541d805](https://linux-hardware.org/?probe=bb8541d805) | Jun 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a4d7f0fbeb](https://linux-hardware.org/?probe=a4d7f0fbeb) | Jun 24, 2022 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [f022b1b430](https://linux-hardware.org/?probe=f022b1b430) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [afce38a95a](https://linux-hardware.org/?probe=afce38a95a) | Jun 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Dell          | Precision 5550              | Notebook    | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ac634d8aa9](https://linux-hardware.org/?probe=ac634d8aa9) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [5129e4893a](https://linux-hardware.org/?probe=5129e4893a) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [dbfad9b8fe](https://linux-hardware.org/?probe=dbfad9b8fe) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [6f13e0f8a0](https://linux-hardware.org/?probe=6f13e0f8a0) | Jun 23, 2022 |
| Dell          | Precision 5550              | Notebook    | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [926d4055f7](https://linux-hardware.org/?probe=926d4055f7) | Jun 23, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [223e43004a](https://linux-hardware.org/?probe=223e43004a) | Jun 23, 2022 |
| Medion        | AXA                         | All in one  | [0cbda6d693](https://linux-hardware.org/?probe=0cbda6d693) | Jun 23, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6ec1b55ac0](https://linux-hardware.org/?probe=6ec1b55ac0) | Jun 23, 2022 |
| Unknown       | HX90                        | Desktop     | [837e70229a](https://linux-hardware.org/?probe=837e70229a) | Jun 23, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [1b382e0eb0](https://linux-hardware.org/?probe=1b382e0eb0) | Jun 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9f67f6836e](https://linux-hardware.org/?probe=9f67f6836e) | Jun 23, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [32a4f6d3e0](https://linux-hardware.org/?probe=32a4f6d3e0) | Jun 23, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [167acd417b](https://linux-hardware.org/?probe=167acd417b) | Jun 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [5dd91493a8](https://linux-hardware.org/?probe=5dd91493a8) | Jun 23, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [d11995947a](https://linux-hardware.org/?probe=d11995947a) | Jun 23, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [65344cb089](https://linux-hardware.org/?probe=65344cb089) | Jun 23, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [92944b1e97](https://linux-hardware.org/?probe=92944b1e97) | Jun 22, 2022 |
| HP            | 2B05                        | Desktop     | [677bb9d569](https://linux-hardware.org/?probe=677bb9d569) | Jun 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [45871f6d61](https://linux-hardware.org/?probe=45871f6d61) | Jun 22, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [f002062377](https://linux-hardware.org/?probe=f002062377) | Jun 22, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [7a571de1b9](https://linux-hardware.org/?probe=7a571de1b9) | Jun 22, 2022 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [58c9da7f20](https://linux-hardware.org/?probe=58c9da7f20) | Jun 22, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f140cafa9f](https://linux-hardware.org/?probe=f140cafa9f) | Jun 22, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [1967dad271](https://linux-hardware.org/?probe=1967dad271) | Jun 22, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [b60cfda63f](https://linux-hardware.org/?probe=b60cfda63f) | Jun 22, 2022 |
| MSI           | B85M-E45                    | Desktop     | [f5e1312d31](https://linux-hardware.org/?probe=f5e1312d31) | Jun 22, 2022 |
| Gigabyte      | H61M-S2P                    | Desktop     | [ac99674975](https://linux-hardware.org/?probe=ac99674975) | Jun 22, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [e02fbb350d](https://linux-hardware.org/?probe=e02fbb350d) | Jun 22, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [77c5ca4f1e](https://linux-hardware.org/?probe=77c5ca4f1e) | Jun 22, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [11151bb62c](https://linux-hardware.org/?probe=11151bb62c) | Jun 22, 2022 |
| Acer          | NC-E5-774G-75TJ             | Notebook    | [55fce68116](https://linux-hardware.org/?probe=55fce68116) | Jun 22, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [04927da7b6](https://linux-hardware.org/?probe=04927da7b6) | Jun 22, 2022 |
| HP            | ZBook 17 G4                 | Notebook    | [bf03eb0fa7](https://linux-hardware.org/?probe=bf03eb0fa7) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [dda5fb9c20](https://linux-hardware.org/?probe=dda5fb9c20) | Jun 21, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [7c7d9af667](https://linux-hardware.org/?probe=7c7d9af667) | Jun 21, 2022 |
| Microsoft     | Surface Laptop              | Tablet      | [8c621a2c68](https://linux-hardware.org/?probe=8c621a2c68) | Jun 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [ae54449547](https://linux-hardware.org/?probe=ae54449547) | Jun 21, 2022 |
| GEO           | GeoBook 240                 | Notebook    | [f08637137c](https://linux-hardware.org/?probe=f08637137c) | Jun 21, 2022 |
| Lenovo        | ThinkPad L13 Yoga 20R5CT... | Convertible | [79c59719f7](https://linux-hardware.org/?probe=79c59719f7) | Jun 21, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [f3176204c8](https://linux-hardware.org/?probe=f3176204c8) | Jun 21, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [dc134b17e9](https://linux-hardware.org/?probe=dc134b17e9) | Jun 21, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [eeeee7321e](https://linux-hardware.org/?probe=eeeee7321e) | Jun 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [490076a383](https://linux-hardware.org/?probe=490076a383) | Jun 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [b7a6099e25](https://linux-hardware.org/?probe=b7a6099e25) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [3193cbe3fd](https://linux-hardware.org/?probe=3193cbe3fd) | Jun 20, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012G... | Notebook    | [92638f1b46](https://linux-hardware.org/?probe=92638f1b46) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [52aa806063](https://linux-hardware.org/?probe=52aa806063) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [a384703b5e](https://linux-hardware.org/?probe=a384703b5e) | Jun 20, 2022 |
| Panasonic     | CFSV9-1                     | Notebook    | [4b7dd23ccd](https://linux-hardware.org/?probe=4b7dd23ccd) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Google        | Droid                       | Notebook    | [5a175a2a78](https://linux-hardware.org/?probe=5a175a2a78) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [9a543a0273](https://linux-hardware.org/?probe=9a543a0273) | Jun 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [bbb3795dc2](https://linux-hardware.org/?probe=bbb3795dc2) | Jun 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [9cf3c1f84c](https://linux-hardware.org/?probe=9cf3c1f84c) | Jun 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [df2017f7d5](https://linux-hardware.org/?probe=df2017f7d5) | Jun 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [560fa88cad](https://linux-hardware.org/?probe=560fa88cad) | Jun 19, 2022 |
| HP            | 2B05                        | Desktop     | [a49ebb4aed](https://linux-hardware.org/?probe=a49ebb4aed) | Jun 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [4fc1134f6d](https://linux-hardware.org/?probe=4fc1134f6d) | Jun 19, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [a59676f7be](https://linux-hardware.org/?probe=a59676f7be) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [707f314c74](https://linux-hardware.org/?probe=707f314c74) | Jun 19, 2022 |
| Micro Elec... | MG-VCP17I-3070              | Notebook    | [e09cfb9236](https://linux-hardware.org/?probe=e09cfb9236) | Jun 19, 2022 |
| HP            | Pavilion dv7                | Notebook    | [ab34fbb528](https://linux-hardware.org/?probe=ab34fbb528) | Jun 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [3c8a4e8226](https://linux-hardware.org/?probe=3c8a4e8226) | Jun 18, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [b9d3cb4755](https://linux-hardware.org/?probe=b9d3cb4755) | Jun 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a71adbf68f](https://linux-hardware.org/?probe=a71adbf68f) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [76f5dd0027](https://linux-hardware.org/?probe=76f5dd0027) | Jun 18, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [32713d6759](https://linux-hardware.org/?probe=32713d6759) | Jun 18, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [4a1a0294d8](https://linux-hardware.org/?probe=4a1a0294d8) | Jun 18, 2022 |
| Dell          | Precision 3571              | Notebook    | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | Notebook    | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [91af0ec6df](https://linux-hardware.org/?probe=91af0ec6df) | Jun 18, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [a6116d2e8c](https://linux-hardware.org/?probe=a6116d2e8c) | Jun 18, 2022 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [df304b4da1](https://linux-hardware.org/?probe=df304b4da1) | Jun 17, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [674addd96b](https://linux-hardware.org/?probe=674addd96b) | Jun 17, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [292cc4bcab](https://linux-hardware.org/?probe=292cc4bcab) | Jun 17, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [e0b7e5c636](https://linux-hardware.org/?probe=e0b7e5c636) | Jun 17, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [9cbdc324b7](https://linux-hardware.org/?probe=9cbdc324b7) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [f54dda344d](https://linux-hardware.org/?probe=f54dda344d) | Jun 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [cb6bf6ab7c](https://linux-hardware.org/?probe=cb6bf6ab7c) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [6647ddd346](https://linux-hardware.org/?probe=6647ddd346) | Jun 17, 2022 |
| Sony          | SVE15128CNB                 | Notebook    | [029a230c77](https://linux-hardware.org/?probe=029a230c77) | Jun 17, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dfed0867e1](https://linux-hardware.org/?probe=dfed0867e1) | Jun 17, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [2a28e582b5](https://linux-hardware.org/?probe=2a28e582b5) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [7205fff536](https://linux-hardware.org/?probe=7205fff536) | Jun 17, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [df4b512aa8](https://linux-hardware.org/?probe=df4b512aa8) | Jun 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [a7431ef0c5](https://linux-hardware.org/?probe=a7431ef0c5) | Jun 17, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [9074247e52](https://linux-hardware.org/?probe=9074247e52) | Jun 17, 2022 |
| Samsung       | 500R5M/500R5W/501R5M        | Notebook    | [91f1df8a58](https://linux-hardware.org/?probe=91f1df8a58) | Jun 17, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [7e65c001a5](https://linux-hardware.org/?probe=7e65c001a5) | Jun 17, 2022 |
| Dell          | 0XC7MM A01                  | Desktop     | [8c8a1ef522](https://linux-hardware.org/?probe=8c8a1ef522) | Jun 16, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e4d5856a72](https://linux-hardware.org/?probe=e4d5856a72) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [4e53a55031](https://linux-hardware.org/?probe=4e53a55031) | Jun 16, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [7dbb9f4adf](https://linux-hardware.org/?probe=7dbb9f4adf) | Jun 16, 2022 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [527aea0d6e](https://linux-hardware.org/?probe=527aea0d6e) | Jun 16, 2022 |
| Micro Elec... | MG-VCP17I-3070              | Notebook    | [c6d123b5ec](https://linux-hardware.org/?probe=c6d123b5ec) | Jun 16, 2022 |
| Micro Elec... | MG-VCP17I-3070              | Notebook    | [d28d429121](https://linux-hardware.org/?probe=d28d429121) | Jun 16, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [7d8683dfac](https://linux-hardware.org/?probe=7d8683dfac) | Jun 16, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [42fd0dcad9](https://linux-hardware.org/?probe=42fd0dcad9) | Jun 16, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [08527d664b](https://linux-hardware.org/?probe=08527d664b) | Jun 16, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [f83da947b8](https://linux-hardware.org/?probe=f83da947b8) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [8d106f8677](https://linux-hardware.org/?probe=8d106f8677) | Jun 16, 2022 |
| Itautec       | Infoway w7430               | Notebook    | [776d876064](https://linux-hardware.org/?probe=776d876064) | Jun 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [388285efe8](https://linux-hardware.org/?probe=388285efe8) | Jun 15, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [6b73227c17](https://linux-hardware.org/?probe=6b73227c17) | Jun 15, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [155af690bd](https://linux-hardware.org/?probe=155af690bd) | Jun 15, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [041f94473b](https://linux-hardware.org/?probe=041f94473b) | Jun 15, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [03140c6f93](https://linux-hardware.org/?probe=03140c6f93) | Jun 15, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [6f25a1e394](https://linux-hardware.org/?probe=6f25a1e394) | Jun 15, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [788b7856ca](https://linux-hardware.org/?probe=788b7856ca) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [131a938c5e](https://linux-hardware.org/?probe=131a938c5e) | Jun 14, 2022 |
| Foxconn       | nT-i1000 Series PCB         | Desktop     | [e61344b416](https://linux-hardware.org/?probe=e61344b416) | Jun 14, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [cc88cec642](https://linux-hardware.org/?probe=cc88cec642) | Jun 14, 2022 |
| Dell          | Precision 3551              | Notebook    | [3499839fd0](https://linux-hardware.org/?probe=3499839fd0) | Jun 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6f26fecef](https://linux-hardware.org/?probe=b6f26fecef) | Jun 14, 2022 |
| HP            | Notebook                    | Notebook    | [390f55db2e](https://linux-hardware.org/?probe=390f55db2e) | Jun 14, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [61104911ed](https://linux-hardware.org/?probe=61104911ed) | Jun 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [b10e894950](https://linux-hardware.org/?probe=b10e894950) | Jun 14, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [35cbb5ff8b](https://linux-hardware.org/?probe=35cbb5ff8b) | Jun 14, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [1bb2aa2c68](https://linux-hardware.org/?probe=1bb2aa2c68) | Jun 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e2385e525c](https://linux-hardware.org/?probe=e2385e525c) | Jun 14, 2022 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [605cab3041](https://linux-hardware.org/?probe=605cab3041) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [cf08ff4333](https://linux-hardware.org/?probe=cf08ff4333) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [4b4bd76de7](https://linux-hardware.org/?probe=4b4bd76de7) | Jun 14, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [2b87adfa9f](https://linux-hardware.org/?probe=2b87adfa9f) | Jun 13, 2022 |
| Dell          | Inspiron 5400 2n1           | Convertible | [33c22b2507](https://linux-hardware.org/?probe=33c22b2507) | Jun 13, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [dc89caf09f](https://linux-hardware.org/?probe=dc89caf09f) | Jun 13, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [61d456c166](https://linux-hardware.org/?probe=61d456c166) | Jun 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [20bd05081e](https://linux-hardware.org/?probe=20bd05081e) | Jun 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d147676849](https://linux-hardware.org/?probe=d147676849) | Jun 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302FEA... | Convertible | [a5d23b52d1](https://linux-hardware.org/?probe=a5d23b52d1) | Jun 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [b8b4869fa1](https://linux-hardware.org/?probe=b8b4869fa1) | Jun 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [221099208b](https://linux-hardware.org/?probe=221099208b) | Jun 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [0a985a9f53](https://linux-hardware.org/?probe=0a985a9f53) | Jun 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e69ce900b7](https://linux-hardware.org/?probe=e69ce900b7) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | Desktop     | [1c5488bdf7](https://linux-hardware.org/?probe=1c5488bdf7) | Jun 13, 2022 |
| ASUSTek       | H87-PLUS                    | Desktop     | [fd8af28ed5](https://linux-hardware.org/?probe=fd8af28ed5) | Jun 13, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [6153f90073](https://linux-hardware.org/?probe=6153f90073) | Jun 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [17d6efccfa](https://linux-hardware.org/?probe=17d6efccfa) | Jun 12, 2022 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [08a04e0c7c](https://linux-hardware.org/?probe=08a04e0c7c) | Jun 12, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [967ef390e0](https://linux-hardware.org/?probe=967ef390e0) | Jun 12, 2022 |
| HP            | 18E5                        | Desktop     | [275b8ca77c](https://linux-hardware.org/?probe=275b8ca77c) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [dbe7d6b6bf](https://linux-hardware.org/?probe=dbe7d6b6bf) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [554002fe47](https://linux-hardware.org/?probe=554002fe47) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | Notebook    | [b791797ef3](https://linux-hardware.org/?probe=b791797ef3) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | Notebook    | [d573a80e21](https://linux-hardware.org/?probe=d573a80e21) | Jun 12, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0c0715a9b2](https://linux-hardware.org/?probe=0c0715a9b2) | Jun 12, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [f0fe22dfe7](https://linux-hardware.org/?probe=f0fe22dfe7) | Jun 12, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [a677849f96](https://linux-hardware.org/?probe=a677849f96) | Jun 12, 2022 |
| ASUSTek       | P5G41T-M                    | Desktop     | [0fd96bfcf3](https://linux-hardware.org/?probe=0fd96bfcf3) | Jun 12, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [6748bf6f1e](https://linux-hardware.org/?probe=6748bf6f1e) | Jun 11, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [8f468e1fc9](https://linux-hardware.org/?probe=8f468e1fc9) | Jun 11, 2022 |
| Lenovo        | ThinkPad T420 4180BE1       | Notebook    | [a3c2ffc8e0](https://linux-hardware.org/?probe=a3c2ffc8e0) | Jun 11, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [18240b9552](https://linux-hardware.org/?probe=18240b9552) | Jun 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [3c8959c8dc](https://linux-hardware.org/?probe=3c8959c8dc) | Jun 11, 2022 |
| HP            | Laptop 17-bs1xx             | Notebook    | [aa23e1d53e](https://linux-hardware.org/?probe=aa23e1d53e) | Jun 11, 2022 |
| Gigabyte      | GA-MA69GM-S2H               | Desktop     | [a382b54934](https://linux-hardware.org/?probe=a382b54934) | Jun 11, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [13dcf888fe](https://linux-hardware.org/?probe=13dcf888fe) | Jun 10, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [63f76026b7](https://linux-hardware.org/?probe=63f76026b7) | Jun 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [1967d32245](https://linux-hardware.org/?probe=1967d32245) | Jun 10, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f37ad0aba6](https://linux-hardware.org/?probe=f37ad0aba6) | Jun 10, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [14e32dc3cb](https://linux-hardware.org/?probe=14e32dc3cb) | Jun 10, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [661f4f701b](https://linux-hardware.org/?probe=661f4f701b) | Jun 10, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [b771c75e31](https://linux-hardware.org/?probe=b771c75e31) | Jun 10, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [272c6283d4](https://linux-hardware.org/?probe=272c6283d4) | Jun 10, 2022 |
| Gigabyte      | H55M-S2                     | Desktop     | [86b61f1ef6](https://linux-hardware.org/?probe=86b61f1ef6) | Jun 10, 2022 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | Notebook    | [c97b8918a0](https://linux-hardware.org/?probe=c97b8918a0) | Jun 10, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [4458c8a8ca](https://linux-hardware.org/?probe=4458c8a8ca) | Jun 09, 2022 |
| HP            | ZBook 15                    | Notebook    | [540fada7d4](https://linux-hardware.org/?probe=540fada7d4) | Jun 09, 2022 |
| HP            | ZBook 15                    | Notebook    | [5e3ff70430](https://linux-hardware.org/?probe=5e3ff70430) | Jun 09, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [158a18f6d1](https://linux-hardware.org/?probe=158a18f6d1) | Jun 09, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [321a2df7db](https://linux-hardware.org/?probe=321a2df7db) | Jun 09, 2022 |
| Intel         | X79 V2.4E                   | Desktop     | [12a530acde](https://linux-hardware.org/?probe=12a530acde) | Jun 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [e934effe87](https://linux-hardware.org/?probe=e934effe87) | Jun 09, 2022 |
| HP            | ENVY dv7                    | Notebook    | [f7401e6566](https://linux-hardware.org/?probe=f7401e6566) | Jun 09, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [e0505ec400](https://linux-hardware.org/?probe=e0505ec400) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [1f5918622d](https://linux-hardware.org/?probe=1f5918622d) | Jun 08, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [35b29ccf1d](https://linux-hardware.org/?probe=35b29ccf1d) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [20a629adc2](https://linux-hardware.org/?probe=20a629adc2) | Jun 08, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [4ce4c3ad20](https://linux-hardware.org/?probe=4ce4c3ad20) | Jun 08, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e12c11bc94](https://linux-hardware.org/?probe=e12c11bc94) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 6475AJ1       | Notebook    | [3ef905b44a](https://linux-hardware.org/?probe=3ef905b44a) | Jun 08, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [0d87deee9d](https://linux-hardware.org/?probe=0d87deee9d) | Jun 08, 2022 |
| VIT           | M2420                       | Notebook    | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | Notebook    | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
| Microsoft     | Surface 3                   | Tablet      | [7f2eeb5b16](https://linux-hardware.org/?probe=7f2eeb5b16) | Jun 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [73823d7212](https://linux-hardware.org/?probe=73823d7212) | Jun 07, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [1a79b3a2ab](https://linux-hardware.org/?probe=1a79b3a2ab) | Jun 07, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c45207e9ed](https://linux-hardware.org/?probe=c45207e9ed) | Jun 07, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [feaff6859d](https://linux-hardware.org/?probe=feaff6859d) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [14a3f31e7d](https://linux-hardware.org/?probe=14a3f31e7d) | Jun 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5cd425083f](https://linux-hardware.org/?probe=5cd425083f) | Jun 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f4120531ac](https://linux-hardware.org/?probe=f4120531ac) | Jun 07, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fa7cd44609](https://linux-hardware.org/?probe=fa7cd44609) | Jun 07, 2022 |
| HP            | 8710                        | Mini pc     | [a4b6fd8f8a](https://linux-hardware.org/?probe=a4b6fd8f8a) | Jun 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c446ea33eb](https://linux-hardware.org/?probe=c446ea33eb) | Jun 07, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c8e7bd54a3](https://linux-hardware.org/?probe=c8e7bd54a3) | Jun 07, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [937c62f908](https://linux-hardware.org/?probe=937c62f908) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [f23f59523b](https://linux-hardware.org/?probe=f23f59523b) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [2e5071518f](https://linux-hardware.org/?probe=2e5071518f) | Jun 07, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [8fcf9a9913](https://linux-hardware.org/?probe=8fcf9a9913) | Jun 07, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [8446232909](https://linux-hardware.org/?probe=8446232909) | Jun 07, 2022 |
| HP            | Laptop 15-dy0xxx            | Notebook    | [e2a9ba60e2](https://linux-hardware.org/?probe=e2a9ba60e2) | Jun 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [6c562bbebb](https://linux-hardware.org/?probe=6c562bbebb) | Jun 06, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [0d56225d08](https://linux-hardware.org/?probe=0d56225d08) | Jun 06, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [5f55cd1869](https://linux-hardware.org/?probe=5f55cd1869) | Jun 06, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [75d7cde897](https://linux-hardware.org/?probe=75d7cde897) | Jun 06, 2022 |
| HP            | EliteBook 8740w             | Notebook    | [178b330cc1](https://linux-hardware.org/?probe=178b330cc1) | Jun 06, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [9fe17edc24](https://linux-hardware.org/?probe=9fe17edc24) | Jun 06, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [d1409ca910](https://linux-hardware.org/?probe=d1409ca910) | Jun 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [bec76e5f74](https://linux-hardware.org/?probe=bec76e5f74) | Jun 06, 2022 |
| Dell          | 0XC7MM A01                  | Desktop     | [ed376c819b](https://linux-hardware.org/?probe=ed376c819b) | Jun 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| HP            | 250 G5                      | Notebook    | [1cbf1a1c53](https://linux-hardware.org/?probe=1cbf1a1c53) | Jun 06, 2022 |
| Lenovo        | 81WE                        | Notebook    | [31217f3c4a](https://linux-hardware.org/?probe=31217f3c4a) | Jun 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0b042e37b3](https://linux-hardware.org/?probe=0b042e37b3) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | Notebook    | [e7e658bc95](https://linux-hardware.org/?probe=e7e658bc95) | Jun 06, 2022 |
| Dell          | 08K0X7 A00                  | Desktop     | [28a29e32c6](https://linux-hardware.org/?probe=28a29e32c6) | Jun 06, 2022 |
| Dell          | 06JWJY A00                  | Desktop     | [577bbe62e1](https://linux-hardware.org/?probe=577bbe62e1) | Jun 06, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [568a879289](https://linux-hardware.org/?probe=568a879289) | Jun 06, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [28c5fad176](https://linux-hardware.org/?probe=28c5fad176) | Jun 06, 2022 |
| HP            | Elite Dragonfly Max Note... | Convertible | [3b16bdeb2c](https://linux-hardware.org/?probe=3b16bdeb2c) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | Notebook    | [e51b9086bd](https://linux-hardware.org/?probe=e51b9086bd) | Jun 06, 2022 |
| HP            | 250 G5                      | Notebook    | [7cbd2a6796](https://linux-hardware.org/?probe=7cbd2a6796) | Jun 06, 2022 |
| HP            | 250 G5                      | Notebook    | [6668b9ad94](https://linux-hardware.org/?probe=6668b9ad94) | Jun 06, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [f5ded88514](https://linux-hardware.org/?probe=f5ded88514) | Jun 06, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [f9ac66019f](https://linux-hardware.org/?probe=f9ac66019f) | Jun 06, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [8fbfe75f53](https://linux-hardware.org/?probe=8fbfe75f53) | Jun 06, 2022 |
| Intel         | AB2L .A001                  | All in one  | [21da21e426](https://linux-hardware.org/?probe=21da21e426) | Jun 06, 2022 |
| Lenovo        | ThinkPad T420 4177CTO       | Notebook    | [fe28db8adc](https://linux-hardware.org/?probe=fe28db8adc) | Jun 06, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [9cd1c3d383](https://linux-hardware.org/?probe=9cd1c3d383) | Jun 05, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [8b87017c24](https://linux-hardware.org/?probe=8b87017c24) | Jun 05, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [afb7427d61](https://linux-hardware.org/?probe=afb7427d61) | Jun 05, 2022 |
| Foxconn       | H81MXV FAB A                | Desktop     | [1f880ea008](https://linux-hardware.org/?probe=1f880ea008) | Jun 05, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [63a565a5e1](https://linux-hardware.org/?probe=63a565a5e1) | Jun 05, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [9e49a2cbac](https://linux-hardware.org/?probe=9e49a2cbac) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7084316e82](https://linux-hardware.org/?probe=7084316e82) | Jun 05, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [f1becc237d](https://linux-hardware.org/?probe=f1becc237d) | Jun 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [155a8dd1a5](https://linux-hardware.org/?probe=155a8dd1a5) | Jun 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [feb1fc06d4](https://linux-hardware.org/?probe=feb1fc06d4) | Jun 05, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [0c40d3f3d2](https://linux-hardware.org/?probe=0c40d3f3d2) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [84d72b2b06](https://linux-hardware.org/?probe=84d72b2b06) | Jun 05, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [feec15b490](https://linux-hardware.org/?probe=feec15b490) | Jun 04, 2022 |
| Positivo      | POS-PIH55BO                 | Desktop     | [cffe8043b8](https://linux-hardware.org/?probe=cffe8043b8) | Jun 04, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [be6fcc008b](https://linux-hardware.org/?probe=be6fcc008b) | Jun 04, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1813b3a9a5](https://linux-hardware.org/?probe=1813b3a9a5) | Jun 04, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [31de2e546e](https://linux-hardware.org/?probe=31de2e546e) | Jun 04, 2022 |
| ASUSTek       | CROSSHAIR                   | Desktop     | [11834759e2](https://linux-hardware.org/?probe=11834759e2) | Jun 04, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [d0797577a9](https://linux-hardware.org/?probe=d0797577a9) | Jun 04, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2e9cc784ac](https://linux-hardware.org/?probe=2e9cc784ac) | Jun 03, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [68a1616b4a](https://linux-hardware.org/?probe=68a1616b4a) | Jun 03, 2022 |
| Dell          | Precision 5540              | Notebook    | [641aabe445](https://linux-hardware.org/?probe=641aabe445) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [909d9cb8d5](https://linux-hardware.org/?probe=909d9cb8d5) | Jun 03, 2022 |
| Intel         | AB2L .A001                  | All in one  | [84023f2b4d](https://linux-hardware.org/?probe=84023f2b4d) | Jun 03, 2022 |
| Chuwi         | UBOOK                       | Convertible | [6e2b3d6ee7](https://linux-hardware.org/?probe=6e2b3d6ee7) | Jun 03, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [df0357703d](https://linux-hardware.org/?probe=df0357703d) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9829bd8f60](https://linux-hardware.org/?probe=9829bd8f60) | Jun 03, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [38de8409ef](https://linux-hardware.org/?probe=38de8409ef) | Jun 02, 2022 |
| Framework     | Laptop                      | Notebook    | [625917cfcd](https://linux-hardware.org/?probe=625917cfcd) | Jun 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3aa4194ab3](https://linux-hardware.org/?probe=3aa4194ab3) | Jun 02, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| ASUSTek       | N82JV                       | Notebook    | [623436f0c3](https://linux-hardware.org/?probe=623436f0c3) | Jun 02, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [2e9996424a](https://linux-hardware.org/?probe=2e9996424a) | Jun 02, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [ff63d0c19b](https://linux-hardware.org/?probe=ff63d0c19b) | Jun 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [978a80c358](https://linux-hardware.org/?probe=978a80c358) | Jun 02, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [d81154a7e1](https://linux-hardware.org/?probe=d81154a7e1) | Jun 02, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | Notebook    | [ad66932f23](https://linux-hardware.org/?probe=ad66932f23) | Jun 02, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [2a09c108e5](https://linux-hardware.org/?probe=2a09c108e5) | Jun 02, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [c2d9f4b84b](https://linux-hardware.org/?probe=c2d9f4b84b) | Jun 02, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [70ad46aa8e](https://linux-hardware.org/?probe=70ad46aa8e) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [38fb3963cd](https://linux-hardware.org/?probe=38fb3963cd) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [6f5f1c9373](https://linux-hardware.org/?probe=6f5f1c9373) | Jun 01, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [aed2597085](https://linux-hardware.org/?probe=aed2597085) | Jun 01, 2022 |
| Lenovo        | Edge 15 80K9                | Notebook    | [5c8bb97759](https://linux-hardware.org/?probe=5c8bb97759) | Jun 01, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [86b732afda](https://linux-hardware.org/?probe=86b732afda) | Jun 01, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [88d5e21b42](https://linux-hardware.org/?probe=88d5e21b42) | Jun 01, 2022 |
| ASUSTek       | Maximus VII IMPACT          | Desktop     | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ae39e96b1a](https://linux-hardware.org/?probe=ae39e96b1a) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [0d91ffc3e9](https://linux-hardware.org/?probe=0d91ffc3e9) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [6190087942](https://linux-hardware.org/?probe=6190087942) | Jun 01, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0f84f94a6a](https://linux-hardware.org/?probe=0f84f94a6a) | Jun 01, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [af6a91d3c7](https://linux-hardware.org/?probe=af6a91d3c7) | Jun 01, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [b68bcf6b84](https://linux-hardware.org/?probe=b68bcf6b84) | Jun 01, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [942b343fff](https://linux-hardware.org/?probe=942b343fff) | Jun 01, 2022 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [1ab6112525](https://linux-hardware.org/?probe=1ab6112525) | Jun 01, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [1e6ab0f183](https://linux-hardware.org/?probe=1e6ab0f183) | May 31, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [3d32754542](https://linux-hardware.org/?probe=3d32754542) | May 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [dc3ee2e520](https://linux-hardware.org/?probe=dc3ee2e520) | May 31, 2022 |
| Lenovo        | Edge 15 80K9                | Notebook    | [9bbdfc95bb](https://linux-hardware.org/?probe=9bbdfc95bb) | May 31, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [956299505f](https://linux-hardware.org/?probe=956299505f) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [9b53c4df9d](https://linux-hardware.org/?probe=9b53c4df9d) | May 31, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [2f8215fb0a](https://linux-hardware.org/?probe=2f8215fb0a) | May 31, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [92acbd4c3f](https://linux-hardware.org/?probe=92acbd4c3f) | May 31, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [38f4cc4c5a](https://linux-hardware.org/?probe=38f4cc4c5a) | May 31, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [4d4c32223e](https://linux-hardware.org/?probe=4d4c32223e) | May 31, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [066f6369b2](https://linux-hardware.org/?probe=066f6369b2) | May 31, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [53dbc2fe14](https://linux-hardware.org/?probe=53dbc2fe14) | May 31, 2022 |
| HP            | 255 G1                      | Notebook    | [86f7198193](https://linux-hardware.org/?probe=86f7198193) | May 31, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ece9950c65](https://linux-hardware.org/?probe=ece9950c65) | May 31, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [cf41cc78f7](https://linux-hardware.org/?probe=cf41cc78f7) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [5a813419eb](https://linux-hardware.org/?probe=5a813419eb) | May 30, 2022 |
| Lenovo        | Edge 15 80K9                | Notebook    | [586a31368f](https://linux-hardware.org/?probe=586a31368f) | May 30, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [07a1bcfa9e](https://linux-hardware.org/?probe=07a1bcfa9e) | May 30, 2022 |
| Google        | Droid                       | Notebook    | [35e3edeab3](https://linux-hardware.org/?probe=35e3edeab3) | May 30, 2022 |
| Framework     | Laptop                      | Notebook    | [f1c2a80b70](https://linux-hardware.org/?probe=f1c2a80b70) | May 30, 2022 |
| Lenovo        | ThinkPad X240 20AM0040BR    | Notebook    | [e0ff07b590](https://linux-hardware.org/?probe=e0ff07b590) | May 30, 2022 |
| IT Channel... | PA70Hx                      | Notebook    | [091ad22c2d](https://linux-hardware.org/?probe=091ad22c2d) | May 30, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [60a88b2d81](https://linux-hardware.org/?probe=60a88b2d81) | May 30, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [378e6ca9c6](https://linux-hardware.org/?probe=378e6ca9c6) | May 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7b27373492](https://linux-hardware.org/?probe=7b27373492) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | Desktop     | [386a88c2b6](https://linux-hardware.org/?probe=386a88c2b6) | May 30, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [eee1a317b6](https://linux-hardware.org/?probe=eee1a317b6) | May 30, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [1e15d749ee](https://linux-hardware.org/?probe=1e15d749ee) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | Desktop     | [5a51cc8767](https://linux-hardware.org/?probe=5a51cc8767) | May 30, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [c1fd0c2d4f](https://linux-hardware.org/?probe=c1fd0c2d4f) | May 30, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [b52762040d](https://linux-hardware.org/?probe=b52762040d) | May 30, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [cdc051336a](https://linux-hardware.org/?probe=cdc051336a) | May 30, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [2e1fd846a3](https://linux-hardware.org/?probe=2e1fd846a3) | May 30, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [15fb1b0353](https://linux-hardware.org/?probe=15fb1b0353) | May 30, 2022 |
| Dell          | 0R6PCT A01                  | Desktop     | [23c83c37e6](https://linux-hardware.org/?probe=23c83c37e6) | May 29, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [7d8d96d851](https://linux-hardware.org/?probe=7d8d96d851) | May 29, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [c7c6e27cae](https://linux-hardware.org/?probe=c7c6e27cae) | May 29, 2022 |
| Dell          | Latitude E7470              | Notebook    | [159516aefb](https://linux-hardware.org/?probe=159516aefb) | May 29, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [33a2de91a2](https://linux-hardware.org/?probe=33a2de91a2) | May 29, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bd9b967f9b](https://linux-hardware.org/?probe=bd9b967f9b) | May 29, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [75d345243e](https://linux-hardware.org/?probe=75d345243e) | May 29, 2022 |
| Notebook      | P65_P67SG                   | Notebook    | [a2aecd5cd3](https://linux-hardware.org/?probe=a2aecd5cd3) | May 29, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [84d5af4ebe](https://linux-hardware.org/?probe=84d5af4ebe) | May 29, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [c8d325a744](https://linux-hardware.org/?probe=c8d325a744) | May 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [077be5d10b](https://linux-hardware.org/?probe=077be5d10b) | May 28, 2022 |
| Dell          | Precision 7710              | Notebook    | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [ae8649e10b](https://linux-hardware.org/?probe=ae8649e10b) | May 28, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [4c4689f4b7](https://linux-hardware.org/?probe=4c4689f4b7) | May 28, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [df2d7a274d](https://linux-hardware.org/?probe=df2d7a274d) | May 28, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [512d3f18ce](https://linux-hardware.org/?probe=512d3f18ce) | May 28, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [da2a67f904](https://linux-hardware.org/?probe=da2a67f904) | May 28, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [8d120a2350](https://linux-hardware.org/?probe=8d120a2350) | May 28, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| Samsung       | 950QDB                      | Convertible | [99178c7961](https://linux-hardware.org/?probe=99178c7961) | May 27, 2022 |
| Timi          | A35S                        | Notebook    | [8a1bee3210](https://linux-hardware.org/?probe=8a1bee3210) | May 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [93d1ebbb72](https://linux-hardware.org/?probe=93d1ebbb72) | May 27, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [8409764263](https://linux-hardware.org/?probe=8409764263) | May 27, 2022 |
| Login Info... | LOG-QAL30                   | Notebook    | [5643c9fb9b](https://linux-hardware.org/?probe=5643c9fb9b) | May 27, 2022 |
| Login Info... | LOG-QAL30                   | Notebook    | [644f3a8dbc](https://linux-hardware.org/?probe=644f3a8dbc) | May 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| Lenovo        | 14w 81MQS02H00              | Notebook    | [e31087bfa9](https://linux-hardware.org/?probe=e31087bfa9) | May 27, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [3171915433](https://linux-hardware.org/?probe=3171915433) | May 27, 2022 |
| Sony          | VPCEE3S1E                   | Notebook    | [f3c7988996](https://linux-hardware.org/?probe=f3c7988996) | May 27, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS3... | Notebook    | [88aabea122](https://linux-hardware.org/?probe=88aabea122) | May 27, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [5507c9109e](https://linux-hardware.org/?probe=5507c9109e) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [9b4287fa8b](https://linux-hardware.org/?probe=9b4287fa8b) | May 26, 2022 |
| HP            | EliteBook x360 830 G6       | Convertible | [f9df0f4196](https://linux-hardware.org/?probe=f9df0f4196) | May 26, 2022 |
| HP            | Pavilion TS 14              | Notebook    | [b7b3d504e2](https://linux-hardware.org/?probe=b7b3d504e2) | May 26, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [90ee31b219](https://linux-hardware.org/?probe=90ee31b219) | May 26, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [4aa126f1e7](https://linux-hardware.org/?probe=4aa126f1e7) | May 26, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [bf6cb72634](https://linux-hardware.org/?probe=bf6cb72634) | May 26, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [ebb7ce2605](https://linux-hardware.org/?probe=ebb7ce2605) | May 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [ad9da27671](https://linux-hardware.org/?probe=ad9da27671) | May 26, 2022 |
| Samsung       | 550XDA                      | Notebook    | [807781d70e](https://linux-hardware.org/?probe=807781d70e) | May 26, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [f754f78f66](https://linux-hardware.org/?probe=f754f78f66) | May 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [6f5b6d8d03](https://linux-hardware.org/?probe=6f5b6d8d03) | May 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [06e3526c59](https://linux-hardware.org/?probe=06e3526c59) | May 25, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| ZoomSmart     | A8006                       | Tablet      | [c5ae648f10](https://linux-hardware.org/?probe=c5ae648f10) | May 25, 2022 |
| HP            | Notebook                    | Notebook    | [05e785c8c2](https://linux-hardware.org/?probe=05e785c8c2) | May 25, 2022 |
| HP            | Notebook                    | Notebook    | [17ca21b3a4](https://linux-hardware.org/?probe=17ca21b3a4) | May 25, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [18ec1a6a1a](https://linux-hardware.org/?probe=18ec1a6a1a) | May 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [dcbaf5defc](https://linux-hardware.org/?probe=dcbaf5defc) | May 25, 2022 |
| HP            | Unknown                     | Notebook    | [c6b346ecc6](https://linux-hardware.org/?probe=c6b346ecc6) | May 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04B00    | Notebook    | [376f43287f](https://linux-hardware.org/?probe=376f43287f) | May 25, 2022 |
| ASUSTek       | KCMA-D8                     | Desktop     | [2d8bea4f55](https://linux-hardware.org/?probe=2d8bea4f55) | May 24, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| Dell          | 0PU052                      | Desktop     | [4e3e3cc0fd](https://linux-hardware.org/?probe=4e3e3cc0fd) | May 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [93c67e62e7](https://linux-hardware.org/?probe=93c67e62e7) | May 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [00baf8a2ff](https://linux-hardware.org/?probe=00baf8a2ff) | May 24, 2022 |
| ROCK Pi       | Unknown                     | Notebook    | [aa891c0178](https://linux-hardware.org/?probe=aa891c0178) | May 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [282c849b82](https://linux-hardware.org/?probe=282c849b82) | May 24, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [24c2ad0798](https://linux-hardware.org/?probe=24c2ad0798) | May 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [71657d24c1](https://linux-hardware.org/?probe=71657d24c1) | May 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [385a286d0d](https://linux-hardware.org/?probe=385a286d0d) | May 24, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [eccd990241](https://linux-hardware.org/?probe=eccd990241) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [4f43d0fc78](https://linux-hardware.org/?probe=4f43d0fc78) | May 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7e8bde85cc](https://linux-hardware.org/?probe=7e8bde85cc) | May 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [02c35436fd](https://linux-hardware.org/?probe=02c35436fd) | May 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [da5f6c9ba0](https://linux-hardware.org/?probe=da5f6c9ba0) | May 23, 2022 |
| Lenovo        | ThinkPad W540 20BHS04B00    | Notebook    | [8d62205131](https://linux-hardware.org/?probe=8d62205131) | May 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1RS0... | Notebook    | [174f6e2270](https://linux-hardware.org/?probe=174f6e2270) | May 23, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [7d35f08c28](https://linux-hardware.org/?probe=7d35f08c28) | May 23, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [49ebd9e68d](https://linux-hardware.org/?probe=49ebd9e68d) | May 23, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [377330c2b5](https://linux-hardware.org/?probe=377330c2b5) | May 23, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [afb47f4860](https://linux-hardware.org/?probe=afb47f4860) | May 23, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [413a708e81](https://linux-hardware.org/?probe=413a708e81) | May 23, 2022 |
| Gigabyte      | P34V5                       | Notebook    | [6fa844b91e](https://linux-hardware.org/?probe=6fa844b91e) | May 23, 2022 |
| Gigabyte      | P34V5                       | Notebook    | [3ad8e4b239](https://linux-hardware.org/?probe=3ad8e4b239) | May 23, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [2034bf506d](https://linux-hardware.org/?probe=2034bf506d) | May 23, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [a76a3417d7](https://linux-hardware.org/?probe=a76a3417d7) | May 23, 2022 |
| Toshiba       | Unknown                     | Notebook    | [56ac954440](https://linux-hardware.org/?probe=56ac954440) | May 23, 2022 |
| Lenovo        | ThinkPad X230 2325AC7       | Notebook    | [bf82ad1cc3](https://linux-hardware.org/?probe=bf82ad1cc3) | May 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2bd8d64c3b](https://linux-hardware.org/?probe=2bd8d64c3b) | May 22, 2022 |
| Sony          | VPCSA2Z9R                   | Notebook    | [5697622de7](https://linux-hardware.org/?probe=5697622de7) | May 22, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | Notebook    | [f17079bdce](https://linux-hardware.org/?probe=f17079bdce) | May 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [bdb9536c9c](https://linux-hardware.org/?probe=bdb9536c9c) | May 22, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [d49880e4c2](https://linux-hardware.org/?probe=d49880e4c2) | May 22, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [40d5ca6bab](https://linux-hardware.org/?probe=40d5ca6bab) | May 22, 2022 |
| ASUSTek       | P8P67-M                     | Desktop     | [83917315b7](https://linux-hardware.org/?probe=83917315b7) | May 22, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [0ea1ce7372](https://linux-hardware.org/?probe=0ea1ce7372) | May 22, 2022 |
| HP            | 15-dc1018ur                 | Notebook    | [aceb1a1011](https://linux-hardware.org/?probe=aceb1a1011) | May 22, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [afca2e1045](https://linux-hardware.org/?probe=afca2e1045) | May 22, 2022 |
| Lenovo        | ThinkPad W520 42763JF       | Notebook    | [2b87bae835](https://linux-hardware.org/?probe=2b87bae835) | May 22, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a84132c514](https://linux-hardware.org/?probe=a84132c514) | May 22, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [4be19d46e1](https://linux-hardware.org/?probe=4be19d46e1) | May 21, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [a44f38fd50](https://linux-hardware.org/?probe=a44f38fd50) | May 21, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [1c2288918d](https://linux-hardware.org/?probe=1c2288918d) | May 21, 2022 |
| HP            | Unknown                     | Notebook    | [2277c14d4d](https://linux-hardware.org/?probe=2277c14d4d) | May 21, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [06943bb7f1](https://linux-hardware.org/?probe=06943bb7f1) | May 21, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [478550abf1](https://linux-hardware.org/?probe=478550abf1) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [49223fe44b](https://linux-hardware.org/?probe=49223fe44b) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [40cb336486](https://linux-hardware.org/?probe=40cb336486) | May 21, 2022 |
| Dell          | Latitude 5490               | Notebook    | [450756ee49](https://linux-hardware.org/?probe=450756ee49) | May 21, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [fce678a9e8](https://linux-hardware.org/?probe=fce678a9e8) | May 21, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [702e495c23](https://linux-hardware.org/?probe=702e495c23) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [01e2d063e8](https://linux-hardware.org/?probe=01e2d063e8) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [f3986d7e7d](https://linux-hardware.org/?probe=f3986d7e7d) | May 21, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [c90fe96957](https://linux-hardware.org/?probe=c90fe96957) | May 21, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [1984313b19](https://linux-hardware.org/?probe=1984313b19) | May 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [d5b9f1fd4a](https://linux-hardware.org/?probe=d5b9f1fd4a) | May 20, 2022 |
| HP            | Pavilion g4                 | Notebook    | [b29455a037](https://linux-hardware.org/?probe=b29455a037) | May 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [567c91351f](https://linux-hardware.org/?probe=567c91351f) | May 20, 2022 |
| HP            | Pavilion g4                 | Notebook    | [001f7d91d2](https://linux-hardware.org/?probe=001f7d91d2) | May 20, 2022 |
| Acer          | Aspire 8940G                | Notebook    | [f6f8622b30](https://linux-hardware.org/?probe=f6f8622b30) | May 20, 2022 |
| Google        | Glimmer                     | Notebook    | [78c39ceda9](https://linux-hardware.org/?probe=78c39ceda9) | May 20, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [ea99252046](https://linux-hardware.org/?probe=ea99252046) | May 20, 2022 |
| Samsung       | 550XDA                      | Notebook    | [1f77e9f8f6](https://linux-hardware.org/?probe=1f77e9f8f6) | May 19, 2022 |
| Samsung       | 550XDA                      | Notebook    | [8c31783747](https://linux-hardware.org/?probe=8c31783747) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [e8df231af7](https://linux-hardware.org/?probe=e8df231af7) | May 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [711e483bb9](https://linux-hardware.org/?probe=711e483bb9) | May 19, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [68d0cdd597](https://linux-hardware.org/?probe=68d0cdd597) | May 19, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [28b26566bf](https://linux-hardware.org/?probe=28b26566bf) | May 19, 2022 |
| eMachines     | E525                        | Notebook    | [2c397d4229](https://linux-hardware.org/?probe=2c397d4229) | May 19, 2022 |
| eMachines     | E525                        | Notebook    | [7a1e439150](https://linux-hardware.org/?probe=7a1e439150) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0e0fc0905a](https://linux-hardware.org/?probe=0e0fc0905a) | May 19, 2022 |
| SKIKK         | GREEN 4                     | Notebook    | [f58c4904f7](https://linux-hardware.org/?probe=f58c4904f7) | May 19, 2022 |
| Toshiba       | Satellite U940              | Notebook    | [249374be01](https://linux-hardware.org/?probe=249374be01) | May 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [94d2bd3233](https://linux-hardware.org/?probe=94d2bd3233) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [56d6c8d749](https://linux-hardware.org/?probe=56d6c8d749) | May 19, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [7f0fc0c72e](https://linux-hardware.org/?probe=7f0fc0c72e) | May 19, 2022 |
| Lenovo        | ThinkPad P50 20EQS1DD00     | Notebook    | [819420bd66](https://linux-hardware.org/?probe=819420bd66) | May 19, 2022 |
| Lenovo        | ThinkPad P50 20EQS1DD00     | Notebook    | [479ab8b5d7](https://linux-hardware.org/?probe=479ab8b5d7) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [6e0efeba1d](https://linux-hardware.org/?probe=6e0efeba1d) | May 19, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [4a971be254](https://linux-hardware.org/?probe=4a971be254) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [592a32a1af](https://linux-hardware.org/?probe=592a32a1af) | May 18, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [e83ddc569f](https://linux-hardware.org/?probe=e83ddc569f) | May 18, 2022 |
| HP            | 8767 A                      | Desktop     | [0f564fe004](https://linux-hardware.org/?probe=0f564fe004) | May 18, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [9c3b90c60d](https://linux-hardware.org/?probe=9c3b90c60d) | May 18, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [d39e962536](https://linux-hardware.org/?probe=d39e962536) | May 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [98752f9fb4](https://linux-hardware.org/?probe=98752f9fb4) | May 18, 2022 |
| Dell          | Latitude E6420              | Notebook    | [0f06571934](https://linux-hardware.org/?probe=0f06571934) | May 18, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [8a6fc346c5](https://linux-hardware.org/?probe=8a6fc346c5) | May 18, 2022 |
| ASUSTek       | X556URK                     | Notebook    | [b217fd2c65](https://linux-hardware.org/?probe=b217fd2c65) | May 18, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [ac9f539524](https://linux-hardware.org/?probe=ac9f539524) | May 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [5e6298871c](https://linux-hardware.org/?probe=5e6298871c) | May 18, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a46fea4edb](https://linux-hardware.org/?probe=a46fea4edb) | May 18, 2022 |
| HP            | 8767 A                      | Desktop     | [caad4001f1](https://linux-hardware.org/?probe=caad4001f1) | May 18, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [8d8783e43f](https://linux-hardware.org/?probe=8d8783e43f) | May 18, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [6e01c5c9f5](https://linux-hardware.org/?probe=6e01c5c9f5) | May 18, 2022 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [a3931c5e60](https://linux-hardware.org/?probe=a3931c5e60) | May 17, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [6f48a71a87](https://linux-hardware.org/?probe=6f48a71a87) | May 17, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9e7bf270db](https://linux-hardware.org/?probe=9e7bf270db) | May 17, 2022 |
| Dell          | Latitude E6230              | Notebook    | [1afeba4362](https://linux-hardware.org/?probe=1afeba4362) | May 17, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [ef70fd2699](https://linux-hardware.org/?probe=ef70fd2699) | May 17, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d831b6cb22](https://linux-hardware.org/?probe=d831b6cb22) | May 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f86ea538c8](https://linux-hardware.org/?probe=f86ea538c8) | May 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [331099a3da](https://linux-hardware.org/?probe=331099a3da) | May 17, 2022 |
| Microsoft     | Surface 3                   | Tablet      | [9159a8f839](https://linux-hardware.org/?probe=9159a8f839) | May 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [c006d01be7](https://linux-hardware.org/?probe=c006d01be7) | May 17, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [2179a16a87](https://linux-hardware.org/?probe=2179a16a87) | May 17, 2022 |
| Notebook      | N8xEJEK                     | Notebook    | [5c2c66e8f5](https://linux-hardware.org/?probe=5c2c66e8f5) | May 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [de37f2b586](https://linux-hardware.org/?probe=de37f2b586) | May 17, 2022 |
| Microsoft     | Surface 3                   | Tablet      | [94494528f6](https://linux-hardware.org/?probe=94494528f6) | May 16, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [ffee0745b6](https://linux-hardware.org/?probe=ffee0745b6) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [21b3b45491](https://linux-hardware.org/?probe=21b3b45491) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [81e0a19eaa](https://linux-hardware.org/?probe=81e0a19eaa) | May 16, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d1dbcd7651](https://linux-hardware.org/?probe=d1dbcd7651) | May 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [61c1716210](https://linux-hardware.org/?probe=61c1716210) | May 16, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [e99a8117ba](https://linux-hardware.org/?probe=e99a8117ba) | May 16, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [cf7f597752](https://linux-hardware.org/?probe=cf7f597752) | May 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [06afc33451](https://linux-hardware.org/?probe=06afc33451) | May 16, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [efe02f8593](https://linux-hardware.org/?probe=efe02f8593) | May 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [2f12c77058](https://linux-hardware.org/?probe=2f12c77058) | May 16, 2022 |
| Lenovo        | ThinkPad T440p 20AW000KU... | Notebook    | [66fc91a0d0](https://linux-hardware.org/?probe=66fc91a0d0) | May 16, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [7f7463682a](https://linux-hardware.org/?probe=7f7463682a) | May 16, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [2dac9974af](https://linux-hardware.org/?probe=2dac9974af) | May 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [fa17134027](https://linux-hardware.org/?probe=fa17134027) | May 16, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [26f332bc9c](https://linux-hardware.org/?probe=26f332bc9c) | May 16, 2022 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [16bd9d3c6d](https://linux-hardware.org/?probe=16bd9d3c6d) | May 16, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [ee54db9f9e](https://linux-hardware.org/?probe=ee54db9f9e) | May 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [a15788c695](https://linux-hardware.org/?probe=a15788c695) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [12d277d32c](https://linux-hardware.org/?probe=12d277d32c) | May 15, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [4e824e7eac](https://linux-hardware.org/?probe=4e824e7eac) | May 15, 2022 |
| Positivo      | H14BU08                     | Notebook    | [ba7d402358](https://linux-hardware.org/?probe=ba7d402358) | May 15, 2022 |
| ASRock        | 880GMH/U3S3                 | Desktop     | [57c85dd37a](https://linux-hardware.org/?probe=57c85dd37a) | May 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [74cb2084ef](https://linux-hardware.org/?probe=74cb2084ef) | May 15, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b95acee640](https://linux-hardware.org/?probe=b95acee640) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [a442279a0b](https://linux-hardware.org/?probe=a442279a0b) | May 15, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [3e3380c801](https://linux-hardware.org/?probe=3e3380c801) | May 15, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [ec0ec5ea27](https://linux-hardware.org/?probe=ec0ec5ea27) | May 15, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [6c635e0f3d](https://linux-hardware.org/?probe=6c635e0f3d) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [88c0d2c252](https://linux-hardware.org/?probe=88c0d2c252) | May 15, 2022 |
| Acer          | AO532h                      | Notebook    | [6055013560](https://linux-hardware.org/?probe=6055013560) | May 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a2ae5d95dd](https://linux-hardware.org/?probe=a2ae5d95dd) | May 15, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6fc56522d6](https://linux-hardware.org/?probe=6fc56522d6) | May 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1bde2ca3e7](https://linux-hardware.org/?probe=1bde2ca3e7) | May 14, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [70809098f6](https://linux-hardware.org/?probe=70809098f6) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6adb7e22c5](https://linux-hardware.org/?probe=6adb7e22c5) | May 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [3112931a28](https://linux-hardware.org/?probe=3112931a28) | May 14, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [210d27dd90](https://linux-hardware.org/?probe=210d27dd90) | May 14, 2022 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [b04a0b8046](https://linux-hardware.org/?probe=b04a0b8046) | May 13, 2022 |
| ASRock        | B560M-C                     | Desktop     | [b4946d836b](https://linux-hardware.org/?probe=b4946d836b) | May 13, 2022 |
| ASRock        | B560M-C                     | Desktop     | [16360de6cd](https://linux-hardware.org/?probe=16360de6cd) | May 13, 2022 |
| Gigabyte      | GA-K8NF-9                   | Desktop     | [f9d59e3770](https://linux-hardware.org/?probe=f9d59e3770) | May 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [8c71a3bd1b](https://linux-hardware.org/?probe=8c71a3bd1b) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2c8d1eec1e](https://linux-hardware.org/?probe=2c8d1eec1e) | May 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [074043a5ca](https://linux-hardware.org/?probe=074043a5ca) | May 13, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [fca86a854a](https://linux-hardware.org/?probe=fca86a854a) | May 13, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [ec4bd74f0b](https://linux-hardware.org/?probe=ec4bd74f0b) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [deb6fa57ef](https://linux-hardware.org/?probe=deb6fa57ef) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [fc7562c140](https://linux-hardware.org/?probe=fc7562c140) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [810fda94b1](https://linux-hardware.org/?probe=810fda94b1) | May 12, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [50946adee3](https://linux-hardware.org/?probe=50946adee3) | May 12, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [46481247b1](https://linux-hardware.org/?probe=46481247b1) | May 12, 2022 |
| Dell          | Latitude 5420               | Notebook    | [ac04d4cb5b](https://linux-hardware.org/?probe=ac04d4cb5b) | May 12, 2022 |
| ICL           | Unknown                     | Notebook    | [cfb2a7c82f](https://linux-hardware.org/?probe=cfb2a7c82f) | May 12, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9baa4a9f57](https://linux-hardware.org/?probe=9baa4a9f57) | May 12, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6212c4d612](https://linux-hardware.org/?probe=6212c4d612) | May 12, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [da0e4e32b4](https://linux-hardware.org/?probe=da0e4e32b4) | May 12, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [bbf4ef2a08](https://linux-hardware.org/?probe=bbf4ef2a08) | May 11, 2022 |
| Lenovo        | ThinkPad X395 20NL0007US    | Notebook    | [aea9571086](https://linux-hardware.org/?probe=aea9571086) | May 11, 2022 |
| Acer          | Aspire M3985                | Desktop     | [e650ae1a26](https://linux-hardware.org/?probe=e650ae1a26) | May 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b0951956fa](https://linux-hardware.org/?probe=b0951956fa) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [927afa0c20](https://linux-hardware.org/?probe=927afa0c20) | May 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c703872774](https://linux-hardware.org/?probe=c703872774) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b9766a94d7](https://linux-hardware.org/?probe=b9766a94d7) | May 11, 2022 |
| Lenovo        | ThinkPad T480 20L6S5M40M    | Notebook    | [f2213829f0](https://linux-hardware.org/?probe=f2213829f0) | May 11, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [607c0a2833](https://linux-hardware.org/?probe=607c0a2833) | May 11, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | Notebook    | [a22c347eaf](https://linux-hardware.org/?probe=a22c347eaf) | May 11, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [61327f1e21](https://linux-hardware.org/?probe=61327f1e21) | May 11, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [9ead3d53b0](https://linux-hardware.org/?probe=9ead3d53b0) | May 11, 2022 |
| Positivo      | C41TB                       | Notebook    | [2df08b295b](https://linux-hardware.org/?probe=2df08b295b) | May 11, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [7dd92b7a41](https://linux-hardware.org/?probe=7dd92b7a41) | May 11, 2022 |
| Positivo      | C41TB                       | Notebook    | [164d3a45c4](https://linux-hardware.org/?probe=164d3a45c4) | May 11, 2022 |
| Lenovo        | B40-70 80F30017BR           | Notebook    | [352c705bf3](https://linux-hardware.org/?probe=352c705bf3) | May 11, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [565dfeea66](https://linux-hardware.org/?probe=565dfeea66) | May 11, 2022 |
| Gigabyte      | Q35M-S2                     | Desktop     | [784ac96428](https://linux-hardware.org/?probe=784ac96428) | May 11, 2022 |
| Lenovo        | B40-70 80F30017BR           | Notebook    | [cb100c3884](https://linux-hardware.org/?probe=cb100c3884) | May 11, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [173fac4f5b](https://linux-hardware.org/?probe=173fac4f5b) | May 11, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [9762e9155b](https://linux-hardware.org/?probe=9762e9155b) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [a8c09f53de](https://linux-hardware.org/?probe=a8c09f53de) | May 10, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [cc3411e0b4](https://linux-hardware.org/?probe=cc3411e0b4) | May 10, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [a5630f81ad](https://linux-hardware.org/?probe=a5630f81ad) | May 10, 2022 |
| ASRock        | 880GMH/U3S3                 | Desktop     | [73e6cb3b6b](https://linux-hardware.org/?probe=73e6cb3b6b) | May 10, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [fb1d5703eb](https://linux-hardware.org/?probe=fb1d5703eb) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [03fc6852e2](https://linux-hardware.org/?probe=03fc6852e2) | May 10, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [f43f2e2bee](https://linux-hardware.org/?probe=f43f2e2bee) | May 10, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [3d0c46dc84](https://linux-hardware.org/?probe=3d0c46dc84) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [20eb5bfb9f](https://linux-hardware.org/?probe=20eb5bfb9f) | May 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2c069935d3](https://linux-hardware.org/?probe=2c069935d3) | May 10, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a0dd43509d](https://linux-hardware.org/?probe=a0dd43509d) | May 09, 2022 |
| Standard      | Unknown                     | Notebook    | [3d9f8907fd](https://linux-hardware.org/?probe=3d9f8907fd) | May 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [d7e92b0ac7](https://linux-hardware.org/?probe=d7e92b0ac7) | May 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ef9c4b3841](https://linux-hardware.org/?probe=ef9c4b3841) | May 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [86acc529d3](https://linux-hardware.org/?probe=86acc529d3) | May 09, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [fbe61c70ff](https://linux-hardware.org/?probe=fbe61c70ff) | May 09, 2022 |
| LG Electro... | 16Z90P-K.AAS9U1             | Notebook    | [26536e15bf](https://linux-hardware.org/?probe=26536e15bf) | May 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [11cb46c902](https://linux-hardware.org/?probe=11cb46c902) | May 08, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a1f8265785](https://linux-hardware.org/?probe=a1f8265785) | May 08, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [a7927b8b27](https://linux-hardware.org/?probe=a7927b8b27) | May 08, 2022 |
| ASUSTek       | N76VZ                       | Notebook    | [f1e06f5c2f](https://linux-hardware.org/?probe=f1e06f5c2f) | May 08, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [76e67361ea](https://linux-hardware.org/?probe=76e67361ea) | May 08, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d24bbea844](https://linux-hardware.org/?probe=d24bbea844) | May 08, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f12944a9bd](https://linux-hardware.org/?probe=f12944a9bd) | May 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [7894bd4591](https://linux-hardware.org/?probe=7894bd4591) | May 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [8fda480b12](https://linux-hardware.org/?probe=8fda480b12) | May 06, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [be200c9e57](https://linux-hardware.org/?probe=be200c9e57) | May 06, 2022 |
| Huanan        | X99-BD4 V1.1, NALEX         | Desktop     | [e69b3ef962](https://linux-hardware.org/?probe=e69b3ef962) | May 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [52d956751f](https://linux-hardware.org/?probe=52d956751f) | May 06, 2022 |
| MSI           | B550M PRO-DASH              | Desktop     | [585987ecf7](https://linux-hardware.org/?probe=585987ecf7) | May 06, 2022 |
| Dell          | Precision 3520              | Notebook    | [2d5c4aa671](https://linux-hardware.org/?probe=2d5c4aa671) | May 05, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [ddc4d88d20](https://linux-hardware.org/?probe=ddc4d88d20) | May 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f255a41930](https://linux-hardware.org/?probe=f255a41930) | May 05, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [8ca57528af](https://linux-hardware.org/?probe=8ca57528af) | May 04, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [3bc61ca207](https://linux-hardware.org/?probe=3bc61ca207) | May 04, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [302e27b974](https://linux-hardware.org/?probe=302e27b974) | May 04, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a9cf3bc268](https://linux-hardware.org/?probe=a9cf3bc268) | May 04, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8fbc520a1b](https://linux-hardware.org/?probe=8fbc520a1b) | May 03, 2022 |
| ASUSTek       | N76VZ                       | Notebook    | [b9c2a28ba0](https://linux-hardware.org/?probe=b9c2a28ba0) | May 03, 2022 |
| HP            | 1589                        | Desktop     | [79df2c00dc](https://linux-hardware.org/?probe=79df2c00dc) | May 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [7636de5c44](https://linux-hardware.org/?probe=7636de5c44) | May 02, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [72f6ebfc11](https://linux-hardware.org/?probe=72f6ebfc11) | May 01, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [0205c9da07](https://linux-hardware.org/?probe=0205c9da07) | May 01, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [03b461596c](https://linux-hardware.org/?probe=03b461596c) | May 01, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [133b6670de](https://linux-hardware.org/?probe=133b6670de) | May 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [428509b262](https://linux-hardware.org/?probe=428509b262) | May 01, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [6d0ad0b8f2](https://linux-hardware.org/?probe=6d0ad0b8f2) | May 01, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [6cefd4f4de](https://linux-hardware.org/?probe=6cefd4f4de) | May 01, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [cb6d49fe71](https://linux-hardware.org/?probe=cb6d49fe71) | Apr 30, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [fb58cab830](https://linux-hardware.org/?probe=fb58cab830) | Apr 30, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [83e47f9c91](https://linux-hardware.org/?probe=83e47f9c91) | Apr 30, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [c4d7dc5e80](https://linux-hardware.org/?probe=c4d7dc5e80) | Apr 30, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [07cb268e5e](https://linux-hardware.org/?probe=07cb268e5e) | Apr 30, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [6cdff366fa](https://linux-hardware.org/?probe=6cdff366fa) | Apr 28, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [2999ff1487](https://linux-hardware.org/?probe=2999ff1487) | Apr 28, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [bf0a56358c](https://linux-hardware.org/?probe=bf0a56358c) | Apr 27, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [99527fd065](https://linux-hardware.org/?probe=99527fd065) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [5456280ec0](https://linux-hardware.org/?probe=5456280ec0) | Apr 26, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [620718bb9e](https://linux-hardware.org/?probe=620718bb9e) | Apr 26, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [128cdc0a61](https://linux-hardware.org/?probe=128cdc0a61) | Apr 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [0d3c8ed904](https://linux-hardware.org/?probe=0d3c8ed904) | Apr 25, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [b4577b2374](https://linux-hardware.org/?probe=b4577b2374) | Apr 25, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7ad22b030d](https://linux-hardware.org/?probe=7ad22b030d) | Apr 24, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [187db4f8e4](https://linux-hardware.org/?probe=187db4f8e4) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b9ea98672f](https://linux-hardware.org/?probe=b9ea98672f) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | Notebook    | [762843e768](https://linux-hardware.org/?probe=762843e768) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | Notebook    | [11ec4d291b](https://linux-hardware.org/?probe=11ec4d291b) | Apr 23, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [8c3b142c85](https://linux-hardware.org/?probe=8c3b142c85) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c3f809fc02](https://linux-hardware.org/?probe=c3f809fc02) | Apr 23, 2022 |
| Dell          | Latitude E7450              | Notebook    | [5ce1623306](https://linux-hardware.org/?probe=5ce1623306) | Apr 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [b6a457c33a](https://linux-hardware.org/?probe=b6a457c33a) | Apr 21, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [68a04098ec](https://linux-hardware.org/?probe=68a04098ec) | Apr 21, 2022 |
| Wiltronic     | iVIEW i896QW                | Notebook    | [34e1873984](https://linux-hardware.org/?probe=34e1873984) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [466f67adb3](https://linux-hardware.org/?probe=466f67adb3) | Apr 20, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [85082e6de6](https://linux-hardware.org/?probe=85082e6de6) | Apr 19, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [9e1d98199a](https://linux-hardware.org/?probe=9e1d98199a) | Apr 18, 2022 |
| Lenovo        | ThinkPad W530 2463A49       | Notebook    | [202b5d34a1](https://linux-hardware.org/?probe=202b5d34a1) | Apr 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [81b837dc13](https://linux-hardware.org/?probe=81b837dc13) | Apr 18, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [b895187681](https://linux-hardware.org/?probe=b895187681) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [66ef9c9e5f](https://linux-hardware.org/?probe=66ef9c9e5f) | Apr 16, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [5bff5642ba](https://linux-hardware.org/?probe=5bff5642ba) | Apr 15, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [9468123a43](https://linux-hardware.org/?probe=9468123a43) | Apr 15, 2022 |
| Dell          | Studio 1537                 | Notebook    | [56c84908d2](https://linux-hardware.org/?probe=56c84908d2) | Apr 15, 2022 |
| Nvidia        | Jetson Xavier NX Develop... | Soc         | [a786d1f74e](https://linux-hardware.org/?probe=a786d1f74e) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [7436528d4f](https://linux-hardware.org/?probe=7436528d4f) | Apr 14, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [22a1a17a81](https://linux-hardware.org/?probe=22a1a17a81) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [719a1712f2](https://linux-hardware.org/?probe=719a1712f2) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [5781ceb5ca](https://linux-hardware.org/?probe=5781ceb5ca) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [84abfd3112](https://linux-hardware.org/?probe=84abfd3112) | Apr 14, 2022 |
| MSI           | FM2-A75IA-E53               | Desktop     | [25ffe3d211](https://linux-hardware.org/?probe=25ffe3d211) | Apr 14, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [77a3c1a7ce](https://linux-hardware.org/?probe=77a3c1a7ce) | Apr 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [9dd2675f34](https://linux-hardware.org/?probe=9dd2675f34) | Apr 14, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [0175e41474](https://linux-hardware.org/?probe=0175e41474) | Apr 14, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [48c7781b77](https://linux-hardware.org/?probe=48c7781b77) | Apr 14, 2022 |
| Dell          | Precision 7540              | Notebook    | [2aff9a81ff](https://linux-hardware.org/?probe=2aff9a81ff) | Apr 13, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [c6fe138c8f](https://linux-hardware.org/?probe=c6fe138c8f) | Apr 13, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [d1b267f496](https://linux-hardware.org/?probe=d1b267f496) | Apr 13, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [43769378a7](https://linux-hardware.org/?probe=43769378a7) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c1beed0e9b](https://linux-hardware.org/?probe=c1beed0e9b) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e5a9e99dbc](https://linux-hardware.org/?probe=e5a9e99dbc) | Apr 13, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [95cff2fbb1](https://linux-hardware.org/?probe=95cff2fbb1) | Apr 13, 2022 |
| Dell          | 0GWHMW A03                  | Desktop     | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| Dell          | 00NH4P A14                  | Server      | [274931609f](https://linux-hardware.org/?probe=274931609f) | Apr 13, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [c3d7c67155](https://linux-hardware.org/?probe=c3d7c67155) | Apr 12, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [73bb0eeab0](https://linux-hardware.org/?probe=73bb0eeab0) | Apr 12, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [7349c76e13](https://linux-hardware.org/?probe=7349c76e13) | Apr 11, 2022 |
| Intel         | W7650                       | Notebook    | [4bd778e810](https://linux-hardware.org/?probe=4bd778e810) | Apr 11, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [5589b339ed](https://linux-hardware.org/?probe=5589b339ed) | Apr 11, 2022 |
| Dell          | Studio 1537                 | Notebook    | [048fceac96](https://linux-hardware.org/?probe=048fceac96) | Apr 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5a60603c45](https://linux-hardware.org/?probe=5a60603c45) | Apr 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [c913cb5a4a](https://linux-hardware.org/?probe=c913cb5a4a) | Apr 11, 2022 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [84927bf894](https://linux-hardware.org/?probe=84927bf894) | Apr 10, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [5b861faffd](https://linux-hardware.org/?probe=5b861faffd) | Apr 09, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [31ecc9c776](https://linux-hardware.org/?probe=31ecc9c776) | Apr 09, 2022 |
| Biostar       | B550MH                      | Desktop     | [abd373497b](https://linux-hardware.org/?probe=abd373497b) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [1a4b90c894](https://linux-hardware.org/?probe=1a4b90c894) | Apr 08, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [f00fb05977](https://linux-hardware.org/?probe=f00fb05977) | Apr 07, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [92966a1240](https://linux-hardware.org/?probe=92966a1240) | Apr 06, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [45a343796d](https://linux-hardware.org/?probe=45a343796d) | Apr 06, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [bd6f031bc8](https://linux-hardware.org/?probe=bd6f031bc8) | Apr 06, 2022 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [f0472bcf0d](https://linux-hardware.org/?probe=f0472bcf0d) | Apr 05, 2022 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [9ee2f76c12](https://linux-hardware.org/?probe=9ee2f76c12) | Apr 05, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [3947799e36](https://linux-hardware.org/?probe=3947799e36) | Apr 05, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [29b43c3e27](https://linux-hardware.org/?probe=29b43c3e27) | Apr 05, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [564cfd1f31](https://linux-hardware.org/?probe=564cfd1f31) | Apr 04, 2022 |
| ASUSTek       | B150M-K                     | Desktop     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [eb69a7978b](https://linux-hardware.org/?probe=eb69a7978b) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1cc5b6fbc3](https://linux-hardware.org/?probe=1cc5b6fbc3) | Apr 03, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [8c1841d2d0](https://linux-hardware.org/?probe=8c1841d2d0) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5eef69398a](https://linux-hardware.org/?probe=5eef69398a) | Apr 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [ba4863a7bb](https://linux-hardware.org/?probe=ba4863a7bb) | Apr 02, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [cd942b0305](https://linux-hardware.org/?probe=cd942b0305) | Apr 02, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [718a7d42cc](https://linux-hardware.org/?probe=718a7d42cc) | Apr 02, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [9e35cab29a](https://linux-hardware.org/?probe=9e35cab29a) | Apr 02, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | Desktop     | [f7946783ea](https://linux-hardware.org/?probe=f7946783ea) | Mar 31, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [4c0c1422e7](https://linux-hardware.org/?probe=4c0c1422e7) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | Notebook    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cc95f0e3ab](https://linux-hardware.org/?probe=cc95f0e3ab) | Mar 31, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [05c02cbe41](https://linux-hardware.org/?probe=05c02cbe41) | Mar 31, 2022 |
| HP            | EliteBook x360 830 G5       | Convertible | [d384ca307e](https://linux-hardware.org/?probe=d384ca307e) | Mar 30, 2022 |
| Avell High... | B.ON                        | Notebook    | [697fc1d4ec](https://linux-hardware.org/?probe=697fc1d4ec) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a22656afee](https://linux-hardware.org/?probe=a22656afee) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [461d175c44](https://linux-hardware.org/?probe=461d175c44) | Mar 28, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [fd1c735c98](https://linux-hardware.org/?probe=fd1c735c98) | Mar 27, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [16ac712c84](https://linux-hardware.org/?probe=16ac712c84) | Mar 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [927252e84e](https://linux-hardware.org/?probe=927252e84e) | Mar 20, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [be2a3fd33b](https://linux-hardware.org/?probe=be2a3fd33b) | Mar 20, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [97eedd34f4](https://linux-hardware.org/?probe=97eedd34f4) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [841ab4ffe2](https://linux-hardware.org/?probe=841ab4ffe2) | Mar 01, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [930ce5581f](https://linux-hardware.org/?probe=930ce5581f) | Feb 25, 2022 |
| Biostar       | H55 HD                      | Desktop     | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| Biostar       | H55 HD                      | Desktop     | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [033354ee53](https://linux-hardware.org/?probe=033354ee53) | Jan 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [ea795a97e1](https://linux-hardware.org/?probe=ea795a97e1) | Dec 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [2b26e185d0](https://linux-hardware.org/?probe=2b26e185d0) | Dec 06, 2021 |
| Lenovo        | ThinkPad 10 20C10027SP      | Tablet      | [1c4e6ab62b](https://linux-hardware.org/?probe=1c4e6ab62b) | Nov 29, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [53054c8f7a](https://linux-hardware.org/?probe=53054c8f7a) | Nov 20, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [1734da4566](https://linux-hardware.org/?probe=1734da4566) | Nov 13, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [2da0673527](https://linux-hardware.org/?probe=2da0673527) | Nov 01, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [f1a1a21c56](https://linux-hardware.org/?probe=f1a1a21c56) | Oct 26, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ff356cba89](https://linux-hardware.org/?probe=ff356cba89) | Oct 22, 2021 |
| Notebook      | PCx0Dx                      | Notebook    | [b1a527acdc](https://linux-hardware.org/?probe=b1a527acdc) | Oct 11, 2021 |
| Notebook      | PCx0Dx                      | Notebook    | [90d4556fdf](https://linux-hardware.org/?probe=90d4556fdf) | Oct 11, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [bcf7dcdd2c](https://linux-hardware.org/?probe=bcf7dcdd2c) | Oct 09, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [0b3691d096](https://linux-hardware.org/?probe=0b3691d096) | Oct 09, 2021 |
| Unknown       | Unknown                     | Notebook    | [af4bbffabf](https://linux-hardware.org/?probe=af4bbffabf) | Sep 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [81fd834473](https://linux-hardware.org/?probe=81fd834473) | Sep 26, 2021 |
| HP            | ProBook 4740s               | Notebook    | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| HP            | 304Ah                       | Desktop     | [047d1b0887](https://linux-hardware.org/?probe=047d1b0887) | Aug 18, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [2ca8cc81b1](https://linux-hardware.org/?probe=2ca8cc81b1) | Aug 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                                       | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| 5.17.6-300.fc36.x86_64                                        | 74        | 10.31%  |
| 5.18.5-200.fc36.x86_64                                        | 73        | 10.17%  |
| 5.17.5-300.fc36.x86_64                                        | 73        | 10.17%  |
| 5.17.11-300.fc36.x86_64                                       | 71        | 9.89%   |
| 5.17.13-300.fc36.x86_64                                       | 53        | 7.38%   |
| 5.17.12-300.fc36.x86_64                                       | 46        | 6.41%   |
| 5.17.8-300.fc36.x86_64                                        | 43        | 5.99%   |
| 5.18.6-200.fc36.x86_64                                        | 36        | 5.01%   |
| 5.17.7-300.fc36.x86_64                                        | 33        | 4.6%    |
| 5.17.9-300.fc36.x86_64                                        | 29        | 4.04%   |
| 5.17.1-300.fc36.x86_64                                        | 29        | 4.04%   |
| 5.17.2-300.fc36.x86_64                                        | 25        | 3.48%   |
| 5.17.3-302.fc36.x86_64                                        | 20        | 2.79%   |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 18        | 2.51%   |
| 5.18.7-200.fc36.x86_64                                        | 13        | 1.81%   |
| 5.17.14-300.fc36.x86_64                                       | 7         | 0.97%   |
| 5.18.1-200.fc36.x86_64                                        | 5         | 0.7%    |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 5         | 0.7%    |
| 5.18.5-201.fsync.fc36.x86_64                                  | 4         | 0.56%   |
| 5.17.4-300.fc36.x86_64                                        | 4         | 0.56%   |
| 5.17.0-300.fc36.x86_64                                        | 4         | 0.56%   |
| 5.17.5-301.fsync.fc36.x86_64                                  | 3         | 0.42%   |
| 5.18.2-200.fc36.x86_64                                        | 2         | 0.28%   |
| 5.18.1-602.inttf.fc36.x86_64                                  | 2         | 0.28%   |
| 5.17.7-301.fsync.fc36.x86_64                                  | 2         | 0.28%   |
| 5.17.11-602.inttf.fc36.x86_64                                 | 2         | 0.28%   |
| 5.15.0-0.rc6.47.fc36.x86_64                                   | 2         | 0.28%   |
| 5.14.0-0.rc5.20210813gitf8e6dfc64f61.46.fc36.x86_64           | 2         | 0.28%   |
| 5.18.7-1.surface.fc36.x86_64                                  | 1         | 0.14%   |
| 5.18.6-201.fsync.fc36.x86_64                                  | 1         | 0.14%   |
| 5.18.5-gnu                                                    | 1         | 0.14%   |
| 5.18.5-250.vanilla.1.fc36.x86_64                              | 1         | 0.14%   |
| 5.18.4-xm1.0.fc36.x86_64                                      | 1         | 0.14%   |
| 5.18.4-125.vanilla.1.fc36.x86_64                              | 1         | 0.14%   |
| 5.18.4-1.surface.fc36.x86_64                                  | 1         | 0.14%   |
| 5.18.2-rc1_MY                                                 | 1         | 0.14%   |
| 5.18.0-0.rc4.20220428git8f4dd16603ce834.36.fc37.x86_64        | 1         | 0.14%   |
| 5.18.0-0.rc3.220422.d569e86915b7f2f.31.vanilla.1.fc36.x86_64  | 1         | 0.14%   |
| 5.18.0                                                        | 1         | 0.14%   |
| 5.17.9-602.inttf.fc36.x86_64                                  | 1         | 0.14%   |
| 5.17.9-302.fsync.fc36.x86_64                                  | 1         | 0.14%   |
| 5.17.9-301.fsync.fc36.x86_64                                  | 1         | 0.14%   |
| 5.17.6-602.inttf.fc36.x86_64                                  | 1         | 0.14%   |
| 5.17.6-300.mbp.fc33.x86_64                                    | 1         | 0.14%   |
| 5.17.6-300.fc36.aarch64                                       | 1         | 0.14%   |
| 5.17.3-301.fsync.fc36.x86_64                                  | 1         | 0.14%   |
| 5.17.3-300.fc36.aarch64                                       | 1         | 0.14%   |
| 5.17.2-300.fc36.aarch64                                       | 1         | 0.14%   |
| 5.17.12-301.fsync.fc36.x86_64                                 | 1         | 0.14%   |
| 5.17.11-301.fsync.fc36.x86_64                                 | 1         | 0.14%   |
| 5.17.1-xanmod1                                                | 1         | 0.14%   |
| 5.17.0-0.rc0.20220112gitdaadb3bd0e8d.63.fc36.x86_64           | 1         | 0.14%   |
| 5.16.9-200.rog.fc35.x86_64                                    | 1         | 0.14%   |
| 5.16.9-200.fc35.x86_64                                        | 1         | 0.14%   |
| 5.16.17-200.fc35.x86_64                                       | 1         | 0.14%   |
| 5.16.16-200.fc35.x86_64                                       | 1         | 0.14%   |
| 5.16.0-0.rc7.20211231git4f3d93c6eaff.52.vanilla.1.fc36.x86_64 | 1         | 0.14%   |
| 5.16.0-0.rc2.20211126gita4849f6000e2.21.fc36.x86_64           | 1         | 0.14%   |
| 5.15.0-60.fc36.x86_64                                         | 1         | 0.14%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.fc36.x86_64           | 1         | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18.5  | 79        | 11.02%  |
| 5.17.6  | 77        | 10.74%  |
| 5.17.5  | 76        | 10.6%   |
| 5.17.11 | 74        | 10.32%  |
| 5.17.13 | 53        | 7.39%   |
| 5.17.12 | 47        | 6.56%   |
| 5.17.8  | 43        | 6%      |
| 5.18.6  | 37        | 5.16%   |
| 5.17.7  | 35        | 4.88%   |
| 5.17.9  | 32        | 4.46%   |
| 5.17.1  | 30        | 4.18%   |
| 5.17.0  | 27        | 3.77%   |
| 5.17.2  | 26        | 3.63%   |
| 5.17.3  | 22        | 3.07%   |
| 5.18.7  | 14        | 1.95%   |
| 5.15.0  | 8         | 1.12%   |
| 5.18.1  | 7         | 0.98%   |
| 5.17.14 | 7         | 0.98%   |
| 5.17.4  | 4         | 0.56%   |
| 5.18.4  | 3         | 0.42%   |
| 5.18.2  | 3         | 0.42%   |
| 5.18.0  | 3         | 0.42%   |
| 5.16.9  | 2         | 0.28%   |
| 5.16.0  | 2         | 0.28%   |
| 5.14.0  | 2         | 0.28%   |
| 5.16.17 | 1         | 0.14%   |
| 5.16.16 | 1         | 0.14%   |
| 5.14.14 | 1         | 0.14%   |
| 5.14.10 | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17    | 533       | 76.58%  |
| 5.18    | 145       | 20.83%  |
| 5.15    | 8         | 1.15%   |
| 5.16    | 6         | 0.86%   |
| 5.14    | 4         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 681       | 99.56%  |
| aarch64 | 3         | 0.44%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 523       | 76.13%  |
| KDE5          | 107       | 15.57%  |
| Unknown       | 20        | 2.91%   |
| XFCE          | 9         | 1.31%   |
| X-Cinnamon    | 8         | 1.16%   |
| Cinnamon      | 8         | 1.16%   |
| i3            | 4         | 0.58%   |
| MATE          | 3         | 0.44%   |
| awesome       | 2         | 0.29%   |
| LXQt          | 1         | 0.15%   |
| GNOME Classic | 1         | 0.15%   |
| Deepin        | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 512       | 74.42%  |
| X11     | 150       | 21.8%   |
| Tty     | 17        | 2.47%   |
| Unknown | 8         | 1.16%   |
| Web     | 1         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 384       | 56.06%  |
| GDM     | 223       | 32.55%  |
| SDDM    | 49        | 7.15%   |
| LightDM | 28        | 4.09%   |
| Ly      | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 376       | 54.89%  |
| ru_RU   | 45        | 6.57%   |
| en_GB   | 41        | 5.99%   |
| pt_BR   | 33        | 4.82%   |
| de_DE   | 21        | 3.07%   |
| en_AU   | 19        | 2.77%   |
| fr_FR   | 17        | 2.48%   |
| pl_PL   | 16        | 2.34%   |
| it_IT   | 12        | 1.75%   |
| en_IN   | 9         | 1.31%   |
| es_ES   | 8         | 1.17%   |
| es_AR   | 8         | 1.17%   |
| en_CA   | 7         | 1.02%   |
| nl_BE   | 5         | 0.73%   |
| es_MX   | 5         | 0.73%   |
| cs_CZ   | 5         | 0.73%   |
| tr_TR   | 3         | 0.44%   |
| nl_NL   | 3         | 0.44%   |
| es_CL   | 3         | 0.44%   |
| en_NZ   | 3         | 0.44%   |
| zh_CN   | 2         | 0.29%   |
| pt_PT   | 2         | 0.29%   |
| ja_JP   | 2         | 0.29%   |
| hu_HU   | 2         | 0.29%   |
| hr_HR   | 2         | 0.29%   |
| fr_BE   | 2         | 0.29%   |
| fi_FI   | 2         | 0.29%   |
| es_EC   | 2         | 0.29%   |
| en_IL   | 2         | 0.29%   |
| en_DK   | 2         | 0.29%   |
| de_CH   | 2         | 0.29%   |
| de_AT   | 2         | 0.29%   |
| da_DK   | 2         | 0.29%   |
| C       | 2         | 0.29%   |
| sv_SE   | 1         | 0.15%   |
| sr_RS   | 1         | 0.15%   |
| nb_NO   | 1         | 0.15%   |
| id_ID   | 1         | 0.15%   |
| fr_CA   | 1         | 0.15%   |
| es_VE   | 1         | 0.15%   |
| es_UY   | 1         | 0.15%   |
| es_SV   | 1         | 0.15%   |
| es_CO   | 1         | 0.15%   |
| en_ZA   | 1         | 0.15%   |
| en_SG   | 1         | 0.15%   |
| en_NL   | 1         | 0.15%   |
| en_IE   | 1         | 0.15%   |
| el_GR   | 1         | 0.15%   |
| ca_ES   | 1         | 0.15%   |
| ba_RU   | 1         | 0.15%   |
| ar_SA   | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 561       | 81.9%   |
| BIOS | 124       | 18.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 557       | 81.43%  |
| Ext4    | 106       | 15.5%   |
| Xfs     | 19        | 2.78%   |
| F2fs    | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 381       | 55.54%  |
| GPT     | 266       | 38.78%  |
| MBR     | 39        | 5.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 611       | 89.2%   |
| Yes       | 74        | 10.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 550       | 80.29%  |
| Yes       | 135       | 19.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 151       | 22.08%  |
| ASUSTek Computer        | 121       | 17.69%  |
| Hewlett-Packard         | 89        | 13.01%  |
| Dell                    | 80        | 11.7%   |
| Gigabyte Technology     | 51        | 7.46%   |
| MSI                     | 40        | 5.85%   |
| Acer                    | 25        | 3.65%   |
| ASRock                  | 19        | 2.78%   |
| Apple                   | 19        | 2.78%   |
| HUAWEI                  | 7         | 1.02%   |
| Intel                   | 6         | 0.88%   |
| Toshiba                 | 5         | 0.73%   |
| Samsung Electronics     | 5         | 0.73%   |
| Positivo                | 5         | 0.73%   |
| Microsoft               | 5         | 0.73%   |
| Sony                    | 4         | 0.58%   |
| Notebook                | 4         | 0.58%   |
| Framework               | 4         | 0.58%   |
| Unknown                 | 4         | 0.58%   |
| Timi                    | 3         | 0.44%   |
| Raspberry Pi Foundation | 2         | 0.29%   |
| Foxconn                 | 2         | 0.29%   |
| Chuwi                   | 2         | 0.29%   |
| Biostar                 | 2         | 0.29%   |
| BESSTAR Tech            | 2         | 0.29%   |
| ZoomSmart               | 1         | 0.15%   |
| Wiltronic               | 1         | 0.15%   |
| VIT                     | 1         | 0.15%   |
| VALE                    | 1         | 0.15%   |
| TUXEDO                  | 1         | 0.15%   |
| System76                | 1         | 0.15%   |
| Standard                | 1         | 0.15%   |
| SKIKK                   | 1         | 0.15%   |
| ROCK Pi                 | 1         | 0.15%   |
| Panasonic               | 1         | 0.15%   |
| Packard Bell            | 1         | 0.15%   |
| Nvidia                  | 1         | 0.15%   |
| Micro Electronics       | 1         | 0.15%   |
| Medion                  | 1         | 0.15%   |
| Login Informatica       | 1         | 0.15%   |
| LG Electronics          | 1         | 0.15%   |
| Itautec                 | 1         | 0.15%   |
| IT Channel Pty          | 1         | 0.15%   |
| ICL                     | 1         | 0.15%   |
| Huanan                  | 1         | 0.15%   |
| Google                  | 1         | 0.15%   |
| Getac                   | 1         | 0.15%   |
| GEO                     | 1         | 0.15%   |
| Fujitsu                 | 1         | 0.15%   |
| eMachines               | 1         | 0.15%   |
| Avell High Performance  | 1         | 0.15%   |
| Alienware               | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 10        | 1.46%   |
| MSI MS-7A38                           | 5         | 0.73%   |
| ASUS All Series                       | 5         | 0.73%   |
| Framework Laptop                      | 4         | 0.58%   |
| ASUS ROG STRIX B550-F GAMING          | 4         | 0.58%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 3         | 0.44%   |
| HP EliteBook 8470p                    | 3         | 0.44%   |
| Dell XPS 15 9570                      | 3         | 0.44%   |
| Dell XPS 13 9310                      | 3         | 0.44%   |
| ASUS TUF Gaming B550M-PLUS            | 3         | 0.44%   |
| ASUS ROG Zephyrus G14 GA402RJ_GA402RJ | 3         | 0.44%   |
| ASUS CROSSHAIR V FORMULA-Z            | 3         | 0.44%   |
| Timi A35S                             | 2         | 0.29%   |
| Samsung 550XDA                        | 2         | 0.29%   |
| MSI MS-7C95                           | 2         | 0.29%   |
| MSI MS-7B79                           | 2         | 0.29%   |
| Microsoft Surface Pro 7               | 2         | 0.29%   |
| Lenovo ThinkBook 16p Gen 2 20YM       | 2         | 0.29%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 2         | 0.29%   |
| Lenovo ThinkBook 14 G3 ACL 21A2       | 2         | 0.29%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 2         | 0.29%   |
| Lenovo IdeaPad 530S-14IKB 81EU        | 2         | 0.29%   |
| Intel DH77EB AAG39073-304             | 2         | 0.29%   |
| HUAWEI KLVL-WXX9                      | 2         | 0.29%   |
| HP ProBook 470 G5                     | 2         | 0.29%   |
| HP Pavilion Laptop 15-cw1xxx          | 2         | 0.29%   |
| HP Pavilion g6                        | 2         | 0.29%   |
| HP Pavilion Aero Laptop 13-be0xxx     | 2         | 0.29%   |
| HP Notebook                           | 2         | 0.29%   |
| HP ENVY x360 Convertible 13-ay0xxx    | 2         | 0.29%   |
| HP 250 G7 Notebook PC                 | 2         | 0.29%   |
| Gigabyte B450 AORUS M                 | 2         | 0.29%   |
| Dell XPS 13 9370                      | 2         | 0.29%   |
| Dell XPS 13 9310 2-in-1               | 2         | 0.29%   |
| Dell XPS 13 7390                      | 2         | 0.29%   |
| Dell OptiPlex 9020                    | 2         | 0.29%   |
| Dell Inspiron 7472                    | 2         | 0.29%   |
| Dell Inspiron 3542                    | 2         | 0.29%   |
| ASUS ROG Strix G513QY_G513QY          | 2         | 0.29%   |
| ASUS ROG Strix G513QM_G513QM          | 2         | 0.29%   |
| ASUS ProArt Z690-CREATOR WIFI         | 2         | 0.29%   |
| ASUS PRIME Z370-A                     | 2         | 0.29%   |
| ASRock X470 Taichi                    | 2         | 0.29%   |
| Apple MacBookPro12,1                  | 2         | 0.29%   |
| Apple iMac16,2                        | 2         | 0.29%   |
| Acer Swift SF114-32                   | 2         | 0.29%   |
| Acer Aspire E5-573G                   | 2         | 0.29%   |
| ZoomSmart A8006                       | 1         | 0.15%   |
| Wiltronic iVIEW i896QW                | 1         | 0.15%   |
| VIT M2420                             | 1         | 0.15%   |
| VALE Notebook Slim S132               | 1         | 0.15%   |
| TUXEDO Pulse 14 Gen1                  | 1         | 0.15%   |
| Toshiba Satellite U940                | 1         | 0.15%   |
| Toshiba Satellite U840                | 1         | 0.15%   |
| Toshiba Satellite C855-12R            | 1         | 0.15%   |
| Toshiba Satellite C50-A               | 1         | 0.15%   |
| Timi Redmi Book Pro 15 2022           | 1         | 0.15%   |
| System76 Thelio Mira                  | 1         | 0.15%   |
| Sony VPCSA2Z9R                        | 1         | 0.15%   |
| Sony VPCEE3S1E                        | 1         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 80        | 11.7%   |
| Lenovo IdeaPad     | 36        | 5.26%   |
| ASUS ROG           | 32        | 4.68%   |
| Dell XPS           | 25        | 3.65%   |
| HP Pavilion        | 21        | 3.07%   |
| Dell Inspiron      | 19        | 2.78%   |
| ASUS PRIME         | 16        | 2.34%   |
| HP Laptop          | 13        | 1.9%    |
| Dell Precision     | 13        | 1.9%    |
| ASUS TUF           | 13        | 1.9%    |
| HP EliteBook       | 12        | 1.75%   |
| Dell Latitude      | 12        | 1.75%   |
| ASUS VivoBook      | 12        | 1.75%   |
| Acer Aspire        | 11        | 1.61%   |
| Unknown            | 10        | 1.46%   |
| HP ENVY            | 9         | 1.32%   |
| Lenovo ThinkBook   | 8         | 1.17%   |
| Lenovo Yoga        | 7         | 1.02%   |
| HP ProBook         | 7         | 1.02%   |
| Dell OptiPlex      | 7         | 1.02%   |
| ASUS ASUS          | 7         | 1.02%   |
| Acer Swift         | 7         | 1.02%   |
| MSI MS-7A38        | 5         | 0.73%   |
| Microsoft Surface  | 5         | 0.73%   |
| ASUS All           | 5         | 0.73%   |
| Toshiba Satellite  | 4         | 0.58%   |
| Lenovo Legion      | 4         | 0.58%   |
| HP ZBook           | 4         | 0.58%   |
| Framework Laptop   | 4         | 0.58%   |
| ASUS CROSSHAIR     | 4         | 0.58%   |
| HP OMEN            | 3         | 0.44%   |
| HP Compaq          | 3         | 0.44%   |
| HP 250             | 3         | 0.44%   |
| Gigabyte B550      | 3         | 0.44%   |
| Gigabyte B450      | 3         | 0.44%   |
| ASUS ZenBook       | 3         | 0.44%   |
| ASUS ProArt        | 3         | 0.44%   |
| Acer Nitro         | 3         | 0.44%   |
| Timi A35S          | 2         | 0.29%   |
| Samsung 550XDA     | 2         | 0.29%   |
| RPi Raspberry      | 2         | 0.29%   |
| MSI MS-7C95        | 2         | 0.29%   |
| MSI MS-7B79        | 2         | 0.29%   |
| Lenovo ThinkCentre | 2         | 0.29%   |
| Intel DH77EB       | 2         | 0.29%   |
| HUAWEI KLVL-WXX9   | 2         | 0.29%   |
| HP Notebook        | 2         | 0.29%   |
| HP EliteDesk       | 2         | 0.29%   |
| HP Elite           | 2         | 0.29%   |
| Gigabyte H410M     | 2         | 0.29%   |
| Dell Vostro        | 2         | 0.29%   |
| ASRock X470        | 2         | 0.29%   |
| ASRock B450        | 2         | 0.29%   |
| Apple MacBookPro8  | 2         | 0.29%   |
| Apple MacBookPro12 | 2         | 0.29%   |
| Apple iMac16       | 2         | 0.29%   |
| ZoomSmart A8006    | 1         | 0.15%   |
| Wiltronic iVIEW    | 1         | 0.15%   |
| VIT M2420          | 1         | 0.15%   |
| VALE Notebook      | 1         | 0.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 124       | 18.13%  |
| 2020    | 123       | 17.98%  |
| 2018    | 77        | 11.26%  |
| 2019    | 72        | 10.53%  |
| 2017    | 42        | 6.14%   |
| 2012    | 37        | 5.41%   |
| 2013    | 36        | 5.26%   |
| 2015    | 31        | 4.53%   |
| 2016    | 28        | 4.09%   |
| 2014    | 27        | 3.95%   |
| 2011    | 26        | 3.8%    |
| 2022    | 23        | 3.36%   |
| 2010    | 13        | 1.9%    |
| 2008    | 10        | 1.46%   |
| 2009    | 8         | 1.17%   |
| 2007    | 4         | 0.58%   |
| 2006    | 1         | 0.15%   |
| 2005    | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 412       | 60.23%  |
| Desktop        | 214       | 31.29%  |
| Convertible    | 32        | 4.68%   |
| Tablet         | 10        | 1.46%   |
| All in one     | 8         | 1.17%   |
| Mini pc        | 4         | 0.58%   |
| System on chip | 3         | 0.44%   |
| Server         | 1         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 553       | 80.85%  |
| Enabled  | 131       | 19.15%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 683       | 99.85%  |
| Yes  | 1         | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 166       | 24.23%  |
| 16.01-24.0  | 165       | 24.09%  |
| 8.01-16.0   | 144       | 21.02%  |
| 32.01-64.0  | 117       | 17.08%  |
| 3.01-4.0    | 52        | 7.59%   |
| 64.01-256.0 | 26        | 3.8%    |
| 24.01-32.0  | 9         | 1.31%   |
| 1.01-2.0    | 4         | 0.58%   |
| 2.01-3.0    | 1         | 0.15%   |
| 0.51-1.0    | 1         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 217       | 30.82%  |
| 2.01-3.0   | 191       | 27.13%  |
| 3.01-4.0   | 162       | 23.01%  |
| 1.01-2.0   | 74        | 10.51%  |
| 8.01-16.0  | 41        | 5.82%   |
| 0.51-1.0   | 9         | 1.28%   |
| 16.01-24.0 | 6         | 0.85%   |
| 0.01-0.5   | 3         | 0.43%   |
| 24.01-32.0 | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 404       | 58.64%  |
| 2      | 171       | 24.82%  |
| 3      | 64        | 9.29%   |
| 4      | 34        | 4.93%   |
| 5      | 6         | 0.87%   |
| 6      | 5         | 0.73%   |
| 7      | 3         | 0.44%   |
| 10     | 1         | 0.15%   |
| 0      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 548       | 80.12%  |
| Yes       | 136       | 19.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 517       | 75.58%  |
| No        | 167       | 24.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 576       | 84.21%  |
| No        | 108       | 15.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 518       | 75.73%  |
| No        | 166       | 24.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 140       | 20.41%  |
| Russia       | 54        | 7.87%   |
| Brazil       | 43        | 6.27%   |
| Germany      | 40        | 5.83%   |
| India        | 29        | 4.23%   |
| Poland       | 28        | 4.08%   |
| UK           | 27        | 3.94%   |
| Italy        | 25        | 3.64%   |
| Australia    | 22        | 3.21%   |
| France       | 21        | 3.06%   |
| Netherlands  | 17        | 2.48%   |
| Mexico       | 15        | 2.19%   |
| Belgium      | 15        | 2.19%   |
| Spain        | 13        | 1.9%    |
| Canada       | 12        | 1.75%   |
| Argentina    | 11        | 1.6%    |
| Turkey       | 10        | 1.46%   |
| Indonesia    | 10        | 1.46%   |
| Switzerland  | 8         | 1.17%   |
| Norway       | 8         | 1.17%   |
| Israel       | 8         | 1.17%   |
| Sweden       | 7         | 1.02%   |
| Finland      | 7         | 1.02%   |
| Czechia      | 7         | 1.02%   |
| Hungary      | 6         | 0.87%   |
| Romania      | 5         | 0.73%   |
| Belarus      | 5         | 0.73%   |
| Portugal     | 4         | 0.58%   |
| Japan        | 4         | 0.58%   |
| Greece       | 4         | 0.58%   |
| Colombia     | 4         | 0.58%   |
| Austria      | 4         | 0.58%   |
| Taiwan       | 3         | 0.44%   |
| South Africa | 3         | 0.44%   |
| Singapore    | 3         | 0.44%   |
| Saudi Arabia | 3         | 0.44%   |
| New Zealand  | 3         | 0.44%   |
| Ireland      | 3         | 0.44%   |
| Estonia      | 3         | 0.44%   |
| Ecuador      | 3         | 0.44%   |
| Denmark      | 3         | 0.44%   |
| Croatia      | 3         | 0.44%   |
| Chile        | 3         | 0.44%   |
| Bulgaria     | 3         | 0.44%   |
| Venezuela    | 2         | 0.29%   |
| Ukraine      | 2         | 0.29%   |
| Thailand     | 2         | 0.29%   |
| Slovakia     | 2         | 0.29%   |
| Puerto Rico  | 2         | 0.29%   |
| Moldova      | 2         | 0.29%   |
| Hong Kong    | 2         | 0.29%   |
| El Salvador  | 2         | 0.29%   |
| China        | 2         | 0.29%   |
| Uzbekistan   | 1         | 0.15%   |
| Slovenia     | 1         | 0.15%   |
| Serbia       | 1         | 0.15%   |
| Philippines  | 1         | 0.15%   |
| Peru         | 1         | 0.15%   |
| Nepal        | 1         | 0.15%   |
| Myanmar      | 1         | 0.15%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 15        | 2.16%   |
| St Petersburg  | 12        | 1.73%   |
| Warsaw         | 8         | 1.15%   |
| Sao Paulo      | 8         | 1.15%   |
| Melbourne      | 7         | 1.01%   |
| Berlin         | 6         | 0.87%   |
| Paris          | 5         | 0.72%   |
| Oslo           | 5         | 0.72%   |
| Minsk          | 5         | 0.72%   |
| Launceston     | 5         | 0.72%   |
| Kolkata        | 5         | 0.72%   |
| New York       | 4         | 0.58%   |
| Munich         | 4         | 0.58%   |
| Montreal       | 4         | 0.58%   |
| Marietta       | 4         | 0.58%   |
| Istanbul       | 4         | 0.58%   |
| Chicago        | 4         | 0.58%   |
| Budapest       | 4         | 0.58%   |
| Brussels       | 4         | 0.58%   |
| Tel Aviv       | 3         | 0.43%   |
| Tallinn        | 3         | 0.43%   |
| Sydney         | 3         | 0.43%   |
| Singapore      | 3         | 0.43%   |
| Rostov-on-Don  | 3         | 0.43%   |
| Rome           | 3         | 0.43%   |
| Pasco          | 3         | 0.43%   |
| Parker         | 3         | 0.43%   |
| Oulu           | 3         | 0.43%   |
| Milan          | 3         | 0.43%   |
| Mexico City    | 3         | 0.43%   |
| Liverpool      | 3         | 0.43%   |
| Lima           | 3         | 0.43%   |
| Las Vegas      | 3         | 0.43%   |
| Krakow         | 3         | 0.43%   |
| Jakarta        | 3         | 0.43%   |
| Bucharest      | 3         | 0.43%   |
| Brooklyn       | 3         | 0.43%   |
| Brisbane       | 3         | 0.43%   |
| Bogotá        | 3         | 0.43%   |
| Bengaluru      | 3         | 0.43%   |
| Athens         | 3         | 0.43%   |
| Antwerp        | 3         | 0.43%   |
| Allen          | 3         | 0.43%   |
| Zurich         | 2         | 0.29%   |
| Zagreb         | 2         | 0.29%   |
| Yaroslavl      | 2         | 0.29%   |
| Wroclaw        | 2         | 0.29%   |
| Stockholm      | 2         | 0.29%   |
| Santiago       | 2         | 0.29%   |
| San Juan       | 2         | 0.29%   |
| San Jose       | 2         | 0.29%   |
| San Antonio    | 2         | 0.29%   |
| Samara         | 2         | 0.29%   |
| Rotterdam      | 2         | 0.29%   |
| Rosario        | 2         | 0.29%   |
| Rio de Janeiro | 2         | 0.29%   |
| Regina         | 2         | 0.29%   |
| Raleigh        | 2         | 0.29%   |
| Quito          | 2         | 0.29%   |
| Prague         | 2         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 212       | 276    | 20.62%  |
| WDC                            | 122       | 165    | 11.87%  |
| Seagate                        | 107       | 129    | 10.41%  |
| SanDisk                        | 61        | 71     | 5.93%   |
| Kingston                       | 59        | 64     | 5.74%   |
| Toshiba                        | 55        | 58     | 5.35%   |
| Crucial                        | 45        | 48     | 4.38%   |
| SK hynix                       | 40        | 42     | 3.89%   |
| Intel                          | 35        | 44     | 3.4%    |
| Unknown                        | 31        | 40     | 3.02%   |
| Micron Technology              | 23        | 26     | 2.24%   |
| KIOXIA                         | 20        | 26     | 1.95%   |
| A-DATA Technology              | 18        | 19     | 1.75%   |
| Phison                         | 14        | 15     | 1.36%   |
| Hitachi                        | 11        | 12     | 1.07%   |
| HGST                           | 11        | 13     | 1.07%   |
| China                          | 11        | 12     | 1.07%   |
| Apple                          | 11        | 11     | 1.07%   |
| XPG                            | 8         | 10     | 0.78%   |
| PNY                            | 8         | 11     | 0.78%   |
| Unknown                        | 7         | 7      | 0.68%   |
| Corsair                        | 6         | 7      | 0.58%   |
| UMIS                           | 5         | 5      | 0.49%   |
| Silicon Motion                 | 5         | 5      | 0.49%   |
| SABRENT                        | 5         | 6      | 0.49%   |
| Micron/Crucial Technology      | 5         | 5      | 0.49%   |
| LITEON                         | 5         | 5      | 0.49%   |
| SSSTC                          | 4         | 4      | 0.39%   |
| Patriot                        | 4         | 4      | 0.39%   |
| Intenso                        | 4         | 5      | 0.39%   |
| SPCC                           | 3         | 6      | 0.29%   |
| Solid State Storage Technology | 3         | 3      | 0.29%   |
| Realtek Semiconductor          | 3         | 3      | 0.29%   |
| OCZ                            | 3         | 3      | 0.29%   |
| Netac                          | 3         | 3      | 0.29%   |
| Lite-On                        | 3         | 3      | 0.29%   |
| Hewlett-Packard                | 3         | 3      | 0.29%   |
| Goodram                        | 3         | 3      | 0.29%   |
| Gigabyte Technology            | 3         | 4      | 0.29%   |
| Transcend                      | 2         | 2      | 0.19%   |
| MAXIO Technology (Hangzhou)    | 2         | 2      | 0.19%   |
| LITEONIT                       | 2         | 2      | 0.19%   |
| Lexar                          | 2         | 2      | 0.19%   |
| KingFast                       | 2         | 2      | 0.19%   |
| KingDian                       | 2         | 2      | 0.19%   |
| JMicron Technology             | 2         | 2      | 0.19%   |
| Fujitsu                        | 2         | 2      | 0.19%   |
| Apacer                         | 2         | 2      | 0.19%   |
| AMicro                         | 2         | 2      | 0.19%   |
| ADATA Technology               | 2         | 2      | 0.19%   |
| WXC-M3                         | 1         | 1      | 0.1%    |
| WDC WDS2                       | 1         | 1      | 0.1%    |
| Vaseky                         | 1         | 1      | 0.1%    |
| USB3.0                         | 1         | 1      | 0.1%    |
| USB                            | 1         | 1      | 0.1%    |
| SSK                            | 1         | 2      | 0.1%    |
| Realtek                        | 1         | 1      | 0.1%    |
| RCESSD                         | 1         | 1      | 0.1%    |
| Origin                         | 1         | 1      | 0.1%    |
| OCZ-VERTEX3                    | 1         | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB           | 16        | 1.43%   |
| Samsung NVMe SSD Drive 1TB             | 16        | 1.43%   |
| Kingston SA400S37240G 240GB SSD        | 15        | 1.34%   |
| SanDisk NVMe SSD Drive 512GB           | 13        | 1.16%   |
| Intel NVMe SSD Drive 512GB             | 13        | 1.16%   |
| Samsung SSD 850 EVO 250GB              | 12        | 1.07%   |
| Samsung NVMe SSD Drive 1024GB          | 12        | 1.07%   |
| Seagate ST1000DM010-2EP102 1TB         | 10        | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB         | 9         | 0.8%    |
| SanDisk NVMe SSD Drive 1TB             | 9         | 0.8%    |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 9         | 0.8%    |
| Samsung NVMe SSD Drive 256GB           | 9         | 0.8%    |
| Unknown MMC Card  64GB                 | 8         | 0.71%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 8         | 0.71%   |
| SK hynix NVMe SSD Drive 512GB          | 8         | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 8         | 0.71%   |
| KIOXIA NVMe SSD Drive 512GB            | 8         | 0.71%   |
| HGST HTS721010A9E630 1TB               | 8         | 0.71%   |
| Crucial CT500MX500SSD1 500GB           | 8         | 0.71%   |
| Samsung SSD 970 EVO Plus 500GB         | 7         | 0.62%   |
| Samsung NVMe SSD Drive 2TB             | 7         | 0.62%   |
| Kingston SA400S37120G 120GB SSD        | 7         | 0.62%   |
| Crucial CT480BX500SSD1 480GB           | 7         | 0.62%   |
| Unknown                                | 7         | 0.62%   |
| Unknown MMC Card  32GB                 | 6         | 0.54%   |
| Toshiba MQ01ABD100 1TB                 | 6         | 0.54%   |
| Seagate ST500DM002-1BD142 500GB        | 6         | 0.54%   |
| SanDisk NVMe SSD Drive 500GB           | 6         | 0.54%   |
| Samsung SSD 870 EVO 500GB              | 6         | 0.54%   |
| Samsung SSD 860 EVO 500GB              | 6         | 0.54%   |
| Samsung SSD 860 EVO 250GB              | 6         | 0.54%   |
| Crucial CT240BX500SSD1 240GB           | 6         | 0.54%   |
| Crucial CT1000MX500SSD1 1TB            | 6         | 0.54%   |
| WDC WD40EFRX-68N32N0 4TB               | 5         | 0.45%   |
| SanDisk NVMe SSD Drive 1024GB          | 5         | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB           | 5         | 0.45%   |
| Samsung SSD 860 EVO 1TB                | 5         | 0.45%   |
| Samsung SSD 850 EVO 500GB              | 5         | 0.45%   |
| Samsung SSD 850 EVO 1TB                | 5         | 0.45%   |
| Samsung SSD 840 EVO 250GB              | 5         | 0.45%   |
| Samsung NVMe SSD Drive 250GB           | 5         | 0.45%   |
| SABRENT Disk 1TB                       | 5         | 0.45%   |
| Kingston NVMe SSD Drive 1TB            | 5         | 0.45%   |
| Crucial CT2000MX500SSD1 2TB            | 5         | 0.45%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 4         | 0.36%   |
| WDC WD10EZEX-00WN4A0 1TB               | 4         | 0.36%   |
| Unknown MMC Card  128GB                | 4         | 0.36%   |
| Toshiba NVMe SSD Drive 512GB           | 4         | 0.36%   |
| Seagate ST500LT012-1DG142 500GB        | 4         | 0.36%   |
| Seagate ST2000DM008-2FR102 2TB         | 4         | 0.36%   |
| Seagate ST2000DM001-1ER164 2TB         | 4         | 0.36%   |
| Samsung SSD 860 QVO 1TB                | 4         | 0.36%   |
| Samsung MZVLB1T0HBLR-000L7 1TB         | 4         | 0.36%   |
| PNY CS900 240GB SSD                    | 4         | 0.36%   |
| Micron NVMe SSD Drive 1024GB           | 4         | 0.36%   |
| Kingston NVMe SSD Drive 500GB          | 4         | 0.36%   |
| Crucial CT1000P2SSD8 1TB               | 4         | 0.36%   |
| XPG NVMe SSD Drive 1024GB              | 3         | 0.27%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 3         | 0.27%   |
| WDC WD10SPZX-24Z10 1TB                 | 3         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 102       | 123    | 39.69%  |
| WDC                 | 85        | 120    | 33.07%  |
| Toshiba             | 29        | 31     | 11.28%  |
| Hitachi             | 11        | 12     | 4.28%   |
| HGST                | 11        | 13     | 4.28%   |
| Samsung Electronics | 5         | 5      | 1.95%   |
| Unknown             | 3         | 3      | 1.17%   |
| Apple               | 3         | 3      | 1.17%   |
| Fujitsu             | 2         | 2      | 0.78%   |
| USB                 | 1         | 1      | 0.39%   |
| Maxtor              | 1         | 2      | 0.39%   |
| JMicron Technology  | 1         | 1      | 0.39%   |
| IB-AC703            | 1         | 1      | 0.39%   |
| Hewlett-Packard     | 1         | 1      | 0.39%   |
| ASMT                | 1         | 1      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 90        | 117    | 28.04%  |
| Kingston            | 40        | 44     | 12.46%  |
| Crucial             | 40        | 43     | 12.46%  |
| SanDisk             | 27        | 28     | 8.41%   |
| WDC                 | 15        | 20     | 4.67%   |
| China               | 10        | 11     | 3.12%   |
| Intel               | 9         | 9      | 2.8%    |
| A-DATA Technology   | 8         | 9      | 2.49%   |
| PNY                 | 7         | 9      | 2.18%   |
| Apple               | 7         | 7      | 2.18%   |
| Micron Technology   | 6         | 6      | 1.87%   |
| Corsair             | 5         | 6      | 1.56%   |
| Patriot             | 4         | 4      | 1.25%   |
| LITEON              | 4         | 4      | 1.25%   |
| Intenso             | 4         | 5      | 1.25%   |
| Toshiba             | 3         | 3      | 0.93%   |
| SPCC                | 3         | 6      | 0.93%   |
| Seagate             | 3         | 3      | 0.93%   |
| OCZ                 | 3         | 3      | 0.93%   |
| Netac               | 3         | 3      | 0.93%   |
| Goodram             | 3         | 3      | 0.93%   |
| Gigabyte Technology | 3         | 4      | 0.93%   |
| Transcend           | 2         | 2      | 0.62%   |
| SK hynix            | 2         | 2      | 0.62%   |
| LITEONIT            | 2         | 2      | 0.62%   |
| Lexar               | 2         | 2      | 0.62%   |
| Apacer              | 2         | 2      | 0.62%   |
| WDC WDS2            | 1         | 1      | 0.31%   |
| Vaseky              | 1         | 1      | 0.31%   |
| USB3.0              | 1         | 1      | 0.31%   |
| Origin              | 1         | 1      | 0.31%   |
| OCZ-VERTEX3         | 1         | 1      | 0.31%   |
| Leven               | 1         | 1      | 0.31%   |
| KUIJIA              | 1         | 1      | 0.31%   |
| KingSpec            | 1         | 1      | 0.31%   |
| KingFast            | 1         | 1      | 0.31%   |
| KingDian            | 1         | 1      | 0.31%   |
| HPE                 | 1         | 1      | 0.31%   |
| EAGET               | 1         | 1      | 0.31%   |
| Drevo               | 1         | 1      | 0.31%   |
| Dogfish             | 1         | 1      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 387       | 474    | 41.7%   |
| SSD     | 267       | 371    | 28.77%  |
| HDD     | 224       | 319    | 24.14%  |
| MMC     | 30        | 41     | 3.23%   |
| Unknown | 20        | 24     | 2.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 395       | 674    | 46.8%   |
| NVMe | 384       | 467    | 45.5%   |
| SAS  | 35        | 47     | 4.15%   |
| MMC  | 30        | 41     | 3.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 264       | 363    | 50.29%  |
| 0.51-1.0   | 173       | 203    | 32.95%  |
| 1.01-2.0   | 46        | 66     | 8.76%   |
| 3.01-4.0   | 25        | 35     | 4.76%   |
| 4.01-10.0  | 10        | 16     | 1.9%    |
| 2.01-3.0   | 6         | 6      | 1.14%   |
| 10.01-20.0 | 1         | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 146       | 21.16%  |
| 251-500        | 128       | 18.55%  |
| 1001-2000      | 107       | 15.51%  |
| 101-250        | 82        | 11.88%  |
| 1-20           | 69        | 10%     |
| Unknown        | 49        | 7.1%    |
| More than 3000 | 47        | 6.81%   |
| 2001-3000      | 31        | 4.49%   |
| 51-100         | 23        | 3.33%   |
| 21-50          | 8         | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 217       | 31.18%  |
| 21-50          | 101       | 14.51%  |
| 101-250        | 83        | 11.93%  |
| 51-100         | 78        | 11.21%  |
| 251-500        | 75        | 10.78%  |
| Unknown        | 49        | 7.04%   |
| 501-1000       | 40        | 5.75%   |
| 1001-2000      | 34        | 4.89%   |
| More than 3000 | 14        | 2.01%   |
| 2001-3000      | 5         | 0.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB              | 2         | 2      | 5.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 5.41%   |
| Samsung Electronics HD322HJ 320GB            | 2         | 2      | 5.41%   |
| WDC WD5000LPCX-24C6HT0 500GB                 | 1         | 1      | 2.7%    |
| WDC WD3200AAKS-75B3A0 320GB                  | 1         | 1      | 2.7%    |
| WDC WD30EZRX-00SPEB0 3TB                     | 1         | 1      | 2.7%    |
| WDC WD20EZRX-00D8PB0 2TB                     | 1         | 1      | 2.7%    |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 1      | 2.7%    |
| WDC WD2003FYYS-02W0B1 2TB                    | 1         | 6      | 2.7%    |
| WDC WD10EZEX-60ZF5A0 1TB                     | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 2.7%    |
| Toshiba MK5055GSX 500GB                      | 1         | 1      | 2.7%    |
| SPCC Solid State Disk 1TB                    | 1         | 2      | 2.7%    |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 2.7%    |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 2.7%    |
| Seagate ST4000VN008-2DR166 4TB               | 1         | 1      | 2.7%    |
| Seagate ST32000542AS 2TB                     | 1         | 2      | 2.7%    |
| Seagate ST31000528AS 1TB                     | 1         | 1      | 2.7%    |
| Seagate ST1000DM010-2EP102 1TB               | 1         | 1      | 2.7%    |
| SanDisk SD6PP4M-256G-1006 256GB SSD          | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 870 EVO 2TB          | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 870 EVO 1TB          | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 840 Series 250GB     | 1         | 1      | 2.7%    |
| Samsung Electronics HD502HJ 500GB            | 1         | 1      | 2.7%    |
| Origin Inception TLC830 Pro Series 256GB SSD | 1         | 1      | 2.7%    |
| OCZ-VERTEX3 MI 240GB SSD                     | 1         | 1      | 2.7%    |
| Lenovo LENSE20512GMSP34MEAT2TA 512GB         | 1         | 1      | 2.7%    |
| Intel SSDSC2CT120A3 120GB                    | 1         | 1      | 2.7%    |
| Hitachi HTS725032A9A364 320GB                | 1         | 1      | 2.7%    |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 2.7%    |
| Hitachi HDS721010CLA332 1TB                  | 1         | 1      | 2.7%    |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 2.7%    |
| Fujitsu MJA2500BH G1 500GB                   | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 27.78%  |
| Samsung Electronics | 7         | 7      | 19.44%  |
| WDC                 | 6         | 12     | 16.67%  |
| Hitachi             | 3         | 3      | 8.33%   |
| Toshiba             | 2         | 2      | 5.56%   |
| SPCC                | 1         | 2      | 2.78%   |
| SanDisk             | 1         | 1      | 2.78%   |
| Origin              | 1         | 1      | 2.78%   |
| OCZ-VERTEX3         | 1         | 1      | 2.78%   |
| Lenovo              | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| HGST                | 1         | 1      | 2.78%   |
| Fujitsu             | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 38.46%  |
| WDC                 | 6         | 12     | 23.08%  |
| Samsung Electronics | 3         | 3      | 11.54%  |
| Hitachi             | 3         | 3      | 11.54%  |
| Toshiba             | 2         | 2      | 7.69%   |
| HGST                | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 33     | 71.43%  |
| SSD  | 9         | 10     | 25.71%  |
| NVMe | 1         | 1      | 2.86%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 412       | 751    | 56.44%  |
| Works    | 283       | 432    | 38.77%  |
| Malfunc  | 34        | 44     | 4.66%   |
| Failed   | 1         | 2      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 383       | 40.32%  |
| AMD                            | 140       | 14.74%  |
| Samsung Electronics            | 137       | 14.42%  |
| SanDisk                        | 57        | 6%      |
| SK hynix                       | 37        | 3.89%   |
| Toshiba America Info Systems   | 27        | 2.84%   |
| Kingston Technology Company    | 19        | 2%      |
| ADATA Technology               | 18        | 1.89%   |
| Micron Technology              | 17        | 1.79%   |
| ASMedia Technology             | 17        | 1.79%   |
| Phison Electronics             | 16        | 1.68%   |
| KIOXIA                         | 16        | 1.68%   |
| Micron/Crucial Technology      | 10        | 1.05%   |
| Marvell Technology Group       | 7         | 0.74%   |
| Solid State Storage Technology | 6         | 0.63%   |
| Silicon Motion                 | 6         | 0.63%   |
| JMicron Technology             | 6         | 0.63%   |
| Union Memory (Shenzhen)        | 5         | 0.53%   |
| Nvidia                         | 5         | 0.53%   |
| Realtek Semiconductor          | 4         | 0.42%   |
| Lite-On Technology             | 4         | 0.42%   |
| Unknown                        | 2         | 0.21%   |
| Silicon Image                  | 2         | 0.21%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.21%   |
| VIA Technologies               | 1         | 0.11%   |
| ULi Electronics                | 1         | 0.11%   |
| Seagate Technology             | 1         | 0.11%   |
| LSI Logic / Symbios Logic      | 1         | 0.11%   |
| Lenovo                         | 1         | 0.11%   |
| Broadcom / LSI                 | 1         | 0.11%   |
| Apple                          | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 94        | 9.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 59        | 5.67%   |
| Intel Volume Management Device NVMe RAID Controller                            | 36        | 3.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 33        | 3.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 31        | 2.98%   |
| AMD 400 Series Chipset SATA Controller                                         | 30        | 2.88%   |
| Samsung NVMe SSD Controller 980                                                | 29        | 2.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 28        | 2.69%   |
| AMD 500 Series Chipset SATA Controller                                         | 25        | 2.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 23        | 2.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 23        | 2.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 21        | 2.02%   |
| SanDisk Non-Volatile memory controller                                         | 17        | 1.63%   |
| Micron Non-Volatile memory controller                                          | 17        | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 17        | 1.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 16        | 1.54%   |
| KIOXIA Non-Volatile memory controller                                          | 16        | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 16        | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 1.54%   |
| SK hynix Gold P31 SSD                                                          | 15        | 1.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 15        | 1.44%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 14        | 1.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 14        | 1.34%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 12        | 1.15%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 12        | 1.15%   |
| Intel Non-Volatile memory controller                                           | 11        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 1.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 11        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 11        | 1.06%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 10        | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10        | 0.96%   |
| Phison E12 NVMe Controller                                                     | 9         | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 0.86%   |
| Intel SSD 660P Series                                                          | 9         | 0.86%   |
| Intel SATA Controller [RAID mode]                                              | 9         | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 0.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 9         | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 8         | 0.77%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 7         | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 0.67%   |
| Solid State Storage Non-Volatile memory controller                             | 6         | 0.58%   |
| SK hynix BC511                                                                 | 6         | 0.58%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 6         | 0.58%   |
| Kingston Company A2000 NVMe SSD                                                | 6         | 0.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 0.58%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 0.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 0.58%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 5         | 0.48%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 5         | 0.48%   |
| Samsung Electronics SATA controller                                            | 5         | 0.48%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5         | 0.48%   |
| Kingston Company Company Non-Volatile memory controller                        | 5         | 0.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 0.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 0.48%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 0.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 0.48%   |
| SK hynix Non-Volatile memory controller                                        | 4         | 0.38%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 4         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 448       | 47.51%  |
| NVMe | 384       | 40.72%  |
| RAID | 76        | 8.06%   |
| IDE  | 33        | 3.5%    |
| SAS  | 2         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 474       | 69.3%   |
| AMD     | 206       | 30.12%  |
| ARM     | 2         | 0.29%   |
| Unknown | 2         | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 24        | 3.51%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 17        | 2.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.9%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 11        | 1.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.46%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 10        | 1.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 1.32%   |
| AMD Ryzen 5 3600 6-Core Processor             | 9         | 1.32%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 1.02%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 7         | 1.02%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 7         | 1.02%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 6         | 0.88%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 6         | 0.88%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 6         | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 0.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.73%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 5         | 0.73%   |
| AMD Ryzen 9 6900HS with Radeon Graphics       | 5         | 0.73%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 5         | 0.73%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 5         | 0.73%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.73%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 0.73%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 4         | 0.58%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 0.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.58%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.58%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 4         | 0.58%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 4         | 0.58%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 4         | 0.58%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 4         | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.58%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 4         | 0.58%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.58%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3         | 0.44%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 3         | 0.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.44%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 0.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.44%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.44%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 3         | 0.44%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 0.44%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 3         | 0.44%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.44%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 3         | 0.44%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3         | 0.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.44%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.44%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 3         | 0.44%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 0.44%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 3         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 149       | 21.78%  |
| Intel Core i7           | 148       | 21.64%  |
| Other                   | 89        | 13.01%  |
| AMD Ryzen 5             | 79        | 11.55%  |
| AMD Ryzen 7             | 45        | 6.58%   |
| AMD Ryzen 9             | 31        | 4.53%   |
| Intel Core i3           | 30        | 4.39%   |
| Intel Celeron           | 14        | 2.05%   |
| Intel Core 2 Duo        | 12        | 1.75%   |
| AMD Ryzen 7 PRO         | 11        | 1.61%   |
| AMD Ryzen 3             | 11        | 1.61%   |
| Intel Xeon              | 9         | 1.32%   |
| Intel Atom              | 8         | 1.17%   |
| AMD FX                  | 8         | 1.17%   |
| Intel Core i9           | 6         | 0.88%   |
| Intel Pentium           | 5         | 0.73%   |
| Intel Pentium Silver    | 4         | 0.58%   |
| AMD A10                 | 4         | 0.58%   |
| AMD A6                  | 3         | 0.44%   |
| Intel Core 2 Quad       | 2         | 0.29%   |
| AMD Phenom II X4        | 2         | 0.29%   |
| AMD Athlon 64 X2        | 2         | 0.29%   |
| Intel Pentium Dual-Core | 1         | 0.15%   |
| Intel Genuine           | 1         | 0.15%   |
| AMD Ryzen 5 PRO         | 1         | 0.15%   |
| AMD Phenom II X2        | 1         | 0.15%   |
| AMD Phenom II           | 1         | 0.15%   |
| AMD Opteron             | 1         | 0.15%   |
| AMD E1                  | 1         | 0.15%   |
| AMD Athlon X4           | 1         | 0.15%   |
| AMD Athlon II           | 1         | 0.15%   |
| AMD Athlon Dual Core    | 1         | 0.15%   |
| AMD Athlon 64           | 1         | 0.15%   |
| AMD A8                  | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 278       | 40.64%  |
| 2       | 163       | 23.83%  |
| 6       | 112       | 16.37%  |
| 8       | 88        | 12.87%  |
| 12      | 19        | 2.78%   |
| 16      | 8         | 1.17%   |
| 14      | 5         | 0.73%   |
| 3       | 4         | 0.58%   |
| Unknown | 3         | 0.44%   |
| 10      | 2         | 0.29%   |
| 1       | 2         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 678       | 99.12%  |
| 2       | 3         | 0.44%   |
| Unknown | 3         | 0.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 568       | 83.04%  |
| 1       | 113       | 16.52%  |
| Unknown | 3         | 0.44%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 683       | 99.85%  |
| 64-bit         | 1         | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 56        | 8.19%   |
| 0x306a9    | 35        | 5.12%   |
| 0x306c3    | 34        | 4.97%   |
| 0x0a50000c | 30        | 4.39%   |
| 0x806ea    | 29        | 4.24%   |
| 0x906ea    | 28        | 4.09%   |
| Unknown    | 27        | 3.95%   |
| 0x206a7    | 26        | 3.8%    |
| 0x806ec    | 24        | 3.51%   |
| 0xa0652    | 20        | 2.92%   |
| 0x40651    | 18        | 2.63%   |
| 0x806e9    | 17        | 2.49%   |
| 0x08701021 | 17        | 2.49%   |
| 0x906e9    | 16        | 2.34%   |
| 0x0a201016 | 14        | 2.05%   |
| 0x08600106 | 14        | 2.05%   |
| 0x08108109 | 14        | 2.05%   |
| 0x506e3    | 13        | 1.9%    |
| 0x306d4    | 13        | 1.9%    |
| 0x08608103 | 11        | 1.61%   |
| 0x0800820d | 11        | 1.61%   |
| 0x08108102 | 10        | 1.46%   |
| 0x706e5    | 9         | 1.32%   |
| 0x406e3    | 9         | 1.32%   |
| 0xa0671    | 7         | 1.02%   |
| 0x90672    | 7         | 1.02%   |
| 0x1067a    | 7         | 1.02%   |
| 0x0a404101 | 7         | 1.02%   |
| 0x08600104 | 7         | 1.02%   |
| 0xa0653    | 6         | 0.88%   |
| 0x806eb    | 6         | 0.88%   |
| 0x106e5    | 6         | 0.88%   |
| 0x906a3    | 5         | 0.73%   |
| 0x706a8    | 5         | 0.73%   |
| 0x506c9    | 5         | 0.73%   |
| 0x20655    | 5         | 0.73%   |
| 0x10676    | 5         | 0.73%   |
| 0x0a201009 | 5         | 0.73%   |
| 0xa0655    | 4         | 0.58%   |
| 0x906ed    | 4         | 0.58%   |
| 0x806d1    | 4         | 0.58%   |
| 0x30678    | 4         | 0.58%   |
| 0x08600103 | 4         | 0.58%   |
| 0x08101016 | 4         | 0.58%   |
| 0x0810100b | 4         | 0.58%   |
| 0x06000822 | 4         | 0.58%   |
| 0x906c0    | 3         | 0.44%   |
| 0x6fb      | 3         | 0.44%   |
| 0x406c4    | 3         | 0.44%   |
| 0x306f2    | 3         | 0.44%   |
| 0x20652    | 3         | 0.44%   |
| 0x0a50000b | 3         | 0.44%   |
| 0x08701013 | 3         | 0.44%   |
| 0x08608102 | 3         | 0.44%   |
| 0x08001137 | 3         | 0.44%   |
| 0x906ec    | 2         | 0.29%   |
| 0x806c2    | 2         | 0.29%   |
| 0x706a1    | 2         | 0.29%   |
| 0x406c3    | 2         | 0.29%   |
| 0x40671    | 2         | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 130       | 19.01%  |
| Zen 3            | 61        | 8.92%   |
| TigerLake        | 59        | 8.63%   |
| Haswell          | 57        | 8.33%   |
| Zen 2            | 46        | 6.73%   |
| Zen+             | 36        | 5.26%   |
| IvyBridge        | 35        | 5.12%   |
| CometLake        | 32        | 4.68%   |
| SandyBridge      | 28        | 4.09%   |
| Unknown          | 28        | 4.09%   |
| Skylake          | 25        | 3.65%   |
| IceLake          | 20        | 2.92%   |
| Broadwell        | 15        | 2.19%   |
| Zen              | 13        | 1.9%    |
| Penryn           | 13        | 1.9%    |
| Alderlake Hybrid | 12        | 1.75%   |
| Westmere         | 10        | 1.46%   |
| Silvermont       | 9         | 1.32%   |
| Piledriver       | 9         | 1.32%   |
| Goldmont plus    | 7         | 1.02%   |
| Nehalem          | 6         | 0.88%   |
| K10              | 6         | 0.88%   |
| Excavator        | 6         | 0.88%   |
| Goldmont         | 5         | 0.73%   |
| K8 Hammer        | 4         | 0.58%   |
| Tremont          | 3         | 0.44%   |
| Core             | 3         | 0.44%   |
| Bonnell          | 3         | 0.44%   |
| Jaguar           | 1         | 0.15%   |
| Bulldozer        | 1         | 0.15%   |
| Bobcat           | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 380       | 44.97%  |
| Nvidia                     | 237       | 28.05%  |
| AMD                        | 226       | 26.75%  |
| Matrox Electronics Systems | 1         | 0.12%   |
| ASPEED Technology          | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 55        | 6.37%   |
| AMD Cezanne                                                                              | 34        | 3.94%   |
| Intel UHD Graphics 620                                                                   | 30        | 3.47%   |
| AMD Renoir                                                                               | 26        | 3.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 24        | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 2.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 2.31%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 2.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 18        | 2.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 1.97%   |
| Intel HD Graphics 620                                                                    | 16        | 1.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 15        | 1.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 15        | 1.74%   |
| AMD Lucienne                                                                             | 14        | 1.62%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 11        | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 1.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 1.16%   |
| Intel HD Graphics 5500                                                                   | 10        | 1.16%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 10        | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 9         | 1.04%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 9         | 1.04%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 0.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 0.93%   |
| AMD Rembrandt [Radeon 680M]                                                              | 8         | 0.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 0.93%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8         | 0.93%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 7         | 0.81%   |
| Intel HD Graphics 630                                                                    | 7         | 0.81%   |
| Intel HD Graphics 530                                                                    | 7         | 0.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 0.81%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 7         | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.69%   |
| Intel AlderLake-S GT1                                                                    | 6         | 0.69%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 6         | 0.69%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 5         | 0.58%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.58%   |
| Intel HD Graphics 500                                                                    | 5         | 0.58%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.58%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 0.58%   |
| Nvidia TU117M                                                                            | 4         | 0.46%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 4         | 0.46%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 4         | 0.46%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 4         | 0.46%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.46%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.46%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 4         | 0.46%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.46%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 4         | 0.46%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 4         | 0.46%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.46%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 0.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.46%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.46%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.46%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 4         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 236       | 34.5%   |
| 1 x AMD         | 174       | 25.44%  |
| Intel + Nvidia  | 114       | 16.67%  |
| 1 x Nvidia      | 101       | 14.77%  |
| AMD + Nvidia    | 21        | 3.07%   |
| Intel + AMD     | 16        | 2.34%   |
| 2 x AMD         | 14        | 2.05%   |
| Other           | 4         | 0.58%   |
| 2 x Nvidia      | 1         | 0.15%   |
| 1 x Matrox      | 1         | 0.15%   |
| Intel + 2 x AMD | 1         | 0.15%   |
| 1 x ASPEED      | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 559       | 81.25%  |
| Proprietary | 111       | 16.13%  |
| Unknown     | 18        | 2.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 324       | 47.16%  |
| 1.01-2.0   | 104       | 15.14%  |
| 0.01-0.5   | 78        | 11.35%  |
| 3.01-4.0   | 59        | 8.59%   |
| 7.01-8.0   | 46        | 6.7%    |
| 0.51-1.0   | 38        | 5.53%   |
| 5.01-6.0   | 18        | 2.62%   |
| 8.01-16.0  | 15        | 2.18%   |
| 2.01-3.0   | 5         | 0.73%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 111       | 14.21%  |
| BOE                     | 88        | 11.27%  |
| Chimei Innolux          | 71        | 9.09%   |
| Samsung Electronics     | 70        | 8.96%   |
| LG Display              | 69        | 8.83%   |
| Goldstar                | 48        | 6.15%   |
| Dell                    | 47        | 6.02%   |
| Philips                 | 26        | 3.33%   |
| Sharp                   | 22        | 2.82%   |
| Hewlett-Packard         | 21        | 2.69%   |
| Apple                   | 19        | 2.43%   |
| Lenovo                  | 18        | 2.3%    |
| AOC                     | 17        | 2.18%   |
| BenQ                    | 16        | 2.05%   |
| Acer                    | 15        | 1.92%   |
| Ancor Communications    | 11        | 1.41%   |
| ViewSonic               | 10        | 1.28%   |
| CSO                     | 9         | 1.15%   |
| Iiyama                  | 8         | 1.02%   |
| PANDA                   | 7         | 0.9%    |
| InfoVision              | 7         | 0.9%    |
| Gigabyte Technology     | 6         | 0.77%   |
| Chi Mei Optoelectronics | 6         | 0.77%   |
| Sceptre Tech            | 5         | 0.64%   |
| ASUSTek Computer        | 5         | 0.64%   |
| TMX                     | 4         | 0.51%   |
| MSI                     | 4         | 0.51%   |
| Sony                    | 2         | 0.26%   |
| SKY                     | 2         | 0.26%   |
| RTK                     | 2         | 0.26%   |
| Mitsubishi              | 2         | 0.26%   |
| Mi                      | 2         | 0.26%   |
| Marantz                 | 2         | 0.26%   |
| Insignia                | 2         | 0.26%   |
| HUAWEI                  | 2         | 0.26%   |
| HannStar                | 2         | 0.26%   |
| Eizo                    | 2         | 0.26%   |
| Vizio                   | 1         | 0.13%   |
| Unknown (CEC)           | 1         | 0.13%   |
| Unknown (1080)          | 1         | 0.13%   |
| Unknown                 | 1         | 0.13%   |
| Toshiba                 | 1         | 0.13%   |
| SGT                     | 1         | 0.13%   |
| Pixio                   | 1         | 0.13%   |
| Panasonic               | 1         | 0.13%   |
| Packard Bell            | 1         | 0.13%   |
| ONN                     | 1         | 0.13%   |
| Onkyo                   | 1         | 0.13%   |
| MIT                     | 1         | 0.13%   |
| Medion                  | 1         | 0.13%   |
| JDI                     | 1         | 0.13%   |
| HKC                     | 1         | 0.13%   |
| Fujitsu Siemens         | 1         | 0.13%   |
| FOX                     | 1         | 0.13%   |
| DMG                     | 1         | 0.13%   |
| CHD                     | 1         | 0.13%   |
| Aosiman                 | 1         | 0.13%   |
| AGO                     | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.62%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 5         | 0.62%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 0.5%    |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 4         | 0.5%    |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 4         | 0.5%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4         | 0.5%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch      | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 4         | 0.5%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 3         | 0.37%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 3         | 0.37%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 3         | 0.37%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 3         | 0.37%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 3         | 0.37%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 3         | 0.37%   |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch                 | 3         | 0.37%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.37%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch         | 3         | 0.37%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 2         | 0.25%   |
| TMX TL156MDMP01-1 TMX1560 3200x2000 336x210mm 15.6-inch               | 2         | 0.25%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 2         | 0.25%   |
| SKY TV-PHILCO SKY0104 1920x1080 885x498mm 40.0-inch                   | 2         | 0.25%   |
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch               | 2         | 0.25%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 2         | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 2         | 0.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.25%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 2         | 0.25%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 2         | 0.25%   |
| Marantz AVR MJI0031 1920x1080 2210x1250mm 100.0-inch                  | 2         | 0.25%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 2         | 0.25%   |
| LG Display LCD Monitor LGD0597 1920x1080 294x165mm 13.3-inch          | 2         | 0.25%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.25%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.25%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 2         | 0.25%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                  | 2         | 0.25%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 338x270mm 17.0-inch              | 2         | 0.25%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 0.25%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch          | 2         | 0.25%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 2         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 390       | 52.63%  |
| 1366x768 (WXGA)    | 80        | 10.8%   |
| 3840x2160 (4K)     | 61        | 8.23%   |
| 2560x1440 (QHD)    | 50        | 6.75%   |
| 1920x1200 (WUXGA)  | 26        | 3.51%   |
| 1600x900 (HD+)     | 21        | 2.83%   |
| 3440x1440          | 19        | 2.56%   |
| 2560x1600          | 11        | 1.48%   |
| 2560x1080          | 10        | 1.35%   |
| 1280x1024 (SXGA)   | 9         | 1.21%   |
| 1440x900 (WXGA+)   | 8         | 1.08%   |
| 3840x2400          | 6         | 0.81%   |
| 1680x1050 (WSXGA+) | 6         | 0.81%   |
| 3456x2160          | 5         | 0.67%   |
| 1280x800 (WXGA)    | 5         | 0.67%   |
| 2880x1800          | 4         | 0.54%   |
| 2256x1504          | 4         | 0.54%   |
| 2160x1440          | 4         | 0.54%   |
| 2736x1824          | 3         | 0.4%    |
| 3840x1600          | 2         | 0.27%   |
| 3840x1080          | 2         | 0.27%   |
| 3200x2000          | 2         | 0.27%   |
| 1920x540           | 2         | 0.27%   |
| 1920x1280          | 2         | 0.27%   |
| 1360x768           | 2         | 0.27%   |
| 3200x1800 (QHD+)   | 1         | 0.13%   |
| 3000x2000          | 1         | 0.13%   |
| 2288x1287          | 1         | 0.13%   |
| 2240x1400          | 1         | 0.13%   |
| 1920x550           | 1         | 0.13%   |
| 1024x768 (XGA)     | 1         | 0.13%   |
| 1024x600           | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 193       | 24.52%  |
| 13      | 108       | 13.72%  |
| 14      | 85        | 10.8%   |
| 27      | 77        | 9.78%   |
| 24      | 60        | 7.62%   |
| 21      | 48        | 6.1%    |
| 23      | 40        | 5.08%   |
| 17      | 28        | 3.56%   |
| 31      | 24        | 3.05%   |
| 34      | 23        | 2.92%   |
| 12      | 16        | 2.03%   |
| 18      | 9         | 1.14%   |
| 32      | 7         | 0.89%   |
| 20      | 7         | 0.89%   |
| 22      | 6         | 0.76%   |
| 16      | 6         | 0.76%   |
| 11      | 6         | 0.76%   |
| 72      | 5         | 0.64%   |
| 19      | 5         | 0.64%   |
| 40      | 4         | 0.51%   |
| Unknown | 4         | 0.51%   |
| 84      | 3         | 0.38%   |
| 10      | 3         | 0.38%   |
| 100     | 2         | 0.25%   |
| 54      | 2         | 0.25%   |
| 48      | 2         | 0.25%   |
| 39      | 2         | 0.25%   |
| 37      | 2         | 0.25%   |
| 29      | 2         | 0.25%   |
| 25      | 2         | 0.25%   |
| 142     | 1         | 0.13%   |
| 75      | 1         | 0.13%   |
| 49      | 1         | 0.13%   |
| 46      | 1         | 0.13%   |
| 42      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 329       | 42.56%  |
| 501-600        | 160       | 20.7%   |
| 201-300        | 85        | 11%     |
| 401-500        | 70        | 9.06%   |
| 601-700        | 36        | 4.66%   |
| 351-400        | 33        | 4.27%   |
| 701-800        | 30        | 3.88%   |
| 1501-2000      | 9         | 1.16%   |
| 801-900        | 6         | 0.78%   |
| 1001-1500      | 5         | 0.65%   |
| Unknown        | 4         | 0.52%   |
| More than 2000 | 3         | 0.39%   |
| 901-1000       | 3         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 552       | 80%     |
| 16/10   | 78        | 11.3%   |
| 21/9    | 28        | 4.06%   |
| 3/2     | 15        | 2.17%   |
| 5/4     | 6         | 0.87%   |
| 4/3     | 3         | 0.43%   |
| 32/9    | 3         | 0.43%   |
| 6/5     | 2         | 0.29%   |
| 1.96    | 1         | 0.14%   |
| 1.00    | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 194       | 25%     |
| 81-90          | 142       | 18.3%   |
| 201-250        | 114       | 14.69%  |
| 301-350        | 79        | 10.18%  |
| 71-80          | 54        | 6.96%   |
| 351-500        | 53        | 6.83%   |
| 151-200        | 30        | 3.87%   |
| 121-130        | 23        | 2.96%   |
| 251-300        | 20        | 2.58%   |
| More than 1000 | 14        | 1.8%    |
| 501-1000       | 12        | 1.55%   |
| 61-70          | 11        | 1.42%   |
| 141-150        | 9         | 1.16%   |
| 51-60          | 6         | 0.77%   |
| 111-120        | 5         | 0.64%   |
| Unknown        | 4         | 0.52%   |
| 41-50          | 3         | 0.39%   |
| 131-140        | 2         | 0.26%   |
| 91-100         | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 272       | 35.65%  |
| 51-100        | 194       | 25.43%  |
| 101-120       | 155       | 20.31%  |
| 161-240       | 95        | 12.45%  |
| More than 240 | 33        | 4.33%   |
| 1-50          | 10        | 1.31%   |
| Unknown       | 4         | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 534       | 77.62%  |
| 2     | 113       | 16.42%  |
| 0     | 22        | 3.2%    |
| 3     | 14        | 2.03%   |
| 4     | 4         | 0.58%   |
| 5     | 1         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 386       | 39.07%  |
| Realtek Semiconductor             | 348       | 35.22%  |
| Qualcomm Atheros                  | 78        | 7.89%   |
| Broadcom                          | 34        | 3.44%   |
| MediaTek                          | 25        | 2.53%   |
| TP-Link                           | 12        | 1.21%   |
| Broadcom Limited                  | 9         | 0.91%   |
| Marvell Technology Group          | 7         | 0.71%   |
| Lenovo                            | 7         | 0.71%   |
| Ralink                            | 6         | 0.61%   |
| Aquantia                          | 6         | 0.61%   |
| Ralink Technology                 | 5         | 0.51%   |
| Nvidia                            | 5         | 0.51%   |
| ASIX Electronics                  | 5         | 0.51%   |
| Sierra Wireless                   | 4         | 0.4%    |
| Qualcomm Atheros Communications   | 4         | 0.4%    |
| Microsoft                         | 4         | 0.4%    |
| D-Link                            | 4         | 0.4%    |
| Xiaomi                            | 3         | 0.3%    |
| Qualcomm                          | 3         | 0.3%    |
| Ericsson Business Mobile Networks | 3         | 0.3%    |
| Belkin Components                 | 3         | 0.3%    |
| ASUSTek Computer                  | 3         | 0.3%    |
| Apple                             | 3         | 0.3%    |
| MicroPython                       | 2         | 0.2%    |
| Edimax Technology                 | 2         | 0.2%    |
| U-Blox                            | 1         | 0.1%    |
| Samsung Electronics               | 1         | 0.1%    |
| Prolific Technology               | 1         | 0.1%    |
| PLANEX                            | 1         | 0.1%    |
| OPPO Electronics                  | 1         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.1%    |
| NetGear                           | 1         | 0.1%    |
| Microchip Technology              | 1         | 0.1%    |
| Mellanox Technologies             | 1         | 0.1%    |
| LSI                               | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |
| InterBiometrics                   | 1         | 0.1%    |
| Hewlett-Packard                   | 1         | 0.1%    |
| Fibocom                           | 1         | 0.1%    |
| DisplayLink                       | 1         | 0.1%    |
| Dell                              | 1         | 0.1%    |
| Adafruit                          | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 213       | 17.84%  |
| Intel Wi-Fi 6 AX200                                               | 58        | 4.86%   |
| Intel Wi-Fi 6 AX201                                               | 45        | 3.77%   |
| Intel Wireless 8265 / 8275                                        | 27        | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 26        | 2.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 2.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 24        | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 1.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 21        | 1.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 20        | 1.68%   |
| Intel I211 Gigabit Network Connection                             | 20        | 1.68%   |
| Intel Ethernet Controller I225-V                                  | 20        | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 15        | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 15        | 1.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 1.17%   |
| Intel Wireless 7260                                               | 13        | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 12        | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 0.92%   |
| Intel Wireless-AC 9260                                            | 11        | 0.92%   |
| Intel Wireless 7265                                               | 11        | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 0.92%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 10        | 0.84%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 10        | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10        | 0.84%   |
| Intel Wireless 8260                                               | 9         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 9         | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 0.75%   |
| Intel Wireless 3165                                               | 8         | 0.67%   |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.67%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 7         | 0.59%   |
| Intel Centrino Ultimate-N 6300                                    | 7         | 0.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 0.59%   |
| Intel Wireless 3160                                               | 6         | 0.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 6         | 0.5%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 6         | 0.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.42%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.42%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.42%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.42%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.34%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 4         | 0.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.34%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.34%   |
| MediaTek WLAN controller                                          | 4         | 0.34%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4         | 0.34%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.34%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.34%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 319       | 52.55%  |
| Realtek Semiconductor           | 111       | 18.29%  |
| Qualcomm Atheros                | 62        | 10.21%  |
| Broadcom                        | 28        | 4.61%   |
| MediaTek                        | 25        | 4.12%   |
| TP-Link                         | 11        | 1.81%   |
| Broadcom Limited                | 8         | 1.32%   |
| Ralink                          | 6         | 0.99%   |
| Ralink Technology               | 5         | 0.82%   |
| Sierra Wireless                 | 4         | 0.66%   |
| Qualcomm Atheros Communications | 4         | 0.66%   |
| Microsoft                       | 4         | 0.66%   |
| Qualcomm                        | 3         | 0.49%   |
| Marvell Technology Group        | 3         | 0.49%   |
| D-Link                          | 3         | 0.49%   |
| Belkin Components               | 3         | 0.49%   |
| Edimax Technology               | 2         | 0.33%   |
| ASUSTek Computer                | 2         | 0.33%   |
| PLANEX                          | 1         | 0.16%   |
| NetGear                         | 1         | 0.16%   |
| Linksys                         | 1         | 0.16%   |
| Fibocom                         | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 58        | 9.52%   |
| Intel Wi-Fi 6 AX201                                            | 45        | 7.39%   |
| Intel Wireless 8265 / 8275                                     | 27        | 4.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 26        | 4.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 21        | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20        | 3.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 20        | 3.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 15        | 2.46%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 15        | 2.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 2.3%    |
| Intel Wireless 7260                                            | 13        | 2.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 12        | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 1.81%   |
| Intel Wireless-AC 9260                                         | 11        | 1.81%   |
| Intel Wireless 7265                                            | 11        | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 11        | 1.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 10        | 1.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10        | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10        | 1.64%   |
| Intel Wireless 8260                                            | 9         | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 1.48%   |
| Intel Wireless 3165                                            | 8         | 1.31%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                 | 7         | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 1.15%   |
| Intel Wireless 3160                                            | 6         | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6         | 0.99%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 0.66%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 0.66%   |
| MediaTek WLAN controller                                       | 4         | 0.66%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 0.66%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 4         | 0.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.49%   |
| Realtek 802.11ac NIC                                           | 3         | 0.49%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 0.49%   |
| Microsoft Xbox 360 Wireless Adapter                            | 3         | 0.49%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 3         | 0.49%   |
| Intel WiFi Link 5100                                           | 3         | 0.49%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 0.49%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.49%   |
| D-Link 802.11ac NIC                                            | 3         | 0.49%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 0.49%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 0.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 0.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 0.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.33%   |
| TP-Link Archer T4U ver.3                                       | 2         | 0.33%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.33%   |
| Sierra Wireless EM7455                                         | 2         | 0.33%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2         | 0.33%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 291       | 52.34%  |
| Intel                    | 185       | 33.27%  |
| Qualcomm Atheros         | 26        | 4.68%   |
| Broadcom                 | 13        | 2.34%   |
| Lenovo                   | 7         | 1.26%   |
| Aquantia                 | 6         | 1.08%   |
| Nvidia                   | 5         | 0.9%    |
| ASIX Electronics         | 5         | 0.9%    |
| Marvell Technology Group | 4         | 0.72%   |
| Xiaomi                   | 3         | 0.54%   |
| Apple                    | 3         | 0.54%   |
| TP-Link                  | 1         | 0.18%   |
| Samsung Electronics      | 1         | 0.18%   |
| OPPO Electronics         | 1         | 0.18%   |
| Microchip Technology     | 1         | 0.18%   |
| DisplayLink              | 1         | 0.18%   |
| D-Link                   | 1         | 0.18%   |
| Broadcom Limited         | 1         | 0.18%   |
| ASUSTek Computer         | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 213       | 37.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 26        | 4.56%   |
| Realtek RTL8125 2.5GbE Controller                                   | 24        | 4.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 22        | 3.86%   |
| Intel I211 Gigabit Network Connection                               | 20        | 3.51%   |
| Intel Ethernet Controller I225-V                                    | 20        | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 19        | 3.33%   |
| Intel Ethernet Connection I217-LM                                   | 10        | 1.75%   |
| Intel Ethernet Connection (4) I219-LM                               | 10        | 1.75%   |
| Intel Ethernet Connection (2) I219-V                                | 9         | 1.58%   |
| Intel Ethernet Connection (7) I219-V                                | 8         | 1.4%    |
| Intel Ethernet Connection (2) I219-LM                               | 8         | 1.4%    |
| Intel Ethernet Connection (13) I219-V                               | 8         | 1.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 5         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 5         | 0.88%   |
| Intel Ethernet Connection (2) I218-V                                | 5         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                               | 5         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                       | 5         | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4         | 0.7%    |
| Intel Ethernet Connection I219-LM                                   | 4         | 0.7%    |
| Intel Ethernet Connection I218-LM                                   | 4         | 0.7%    |
| Intel Ethernet Connection I217-V                                    | 4         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                            | 4         | 0.7%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 4         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                               | 3         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 3         | 0.53%   |
| Lenovo ThinkPad TBT 3 Dock                                          | 3         | 0.53%   |
| Lenovo ThinkPad Lan                                                 | 3         | 0.53%   |
| Intel I210 Gigabit Network Connection                               | 3         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                               | 3         | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                               | 3         | 0.53%   |
| Intel Ethernet Connection (13) I219-LM                              | 3         | 0.53%   |
| Intel Ethernet Connection (11) I219-V                               | 3         | 0.53%   |
| Intel Ethernet Connection (11) I219-LM                              | 3         | 0.53%   |
| Intel 82583V Gigabit Network Connection                             | 3         | 0.53%   |
| Intel 82579V Gigabit Network Connection                             | 3         | 0.53%   |
| Intel 82574L Gigabit Network Connection                             | 3         | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 3         | 0.53%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                   | 3         | 0.53%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                | 2         | 0.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 2         | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 2         | 0.35%   |
| Realtek Killer E3000 2.5GbE Controller                              | 2         | 0.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 2         | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                              | 2         | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 2         | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                               | 2         | 0.35%   |
| Nvidia MCP79 Ethernet                                               | 2         | 0.35%   |
| Intel Ethernet Connection (6) I219-V                                | 2         | 0.35%   |
| Intel Ethernet Connection (6) I219-LM                               | 2         | 0.35%   |
| Intel Ethernet Connection (4) I219-V                                | 2         | 0.35%   |
| Intel Ethernet Connection (3) I218-LM                               | 2         | 0.35%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 2         | 0.35%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                   | 2         | 0.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2         | 0.35%   |
| Apple iPad 4/Mini1                                                  | 2         | 0.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1         | 0.18%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1         | 0.18%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1         | 0.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 576       | 52.03%  |
| Ethernet | 516       | 46.61%  |
| Modem    | 11        | 0.99%   |
| Unknown  | 4         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 474       | 67.04%  |
| Ethernet | 233       | 32.96%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 343       | 50.15%  |
| 1     | 306       | 44.74%  |
| 3     | 24        | 3.51%   |
| 0     | 9         | 1.32%   |
| 4     | 2         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 505       | 73.62%  |
| Yes  | 181       | 26.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 278       | 52.95%  |
| Realtek Semiconductor           | 70        | 13.33%  |
| Qualcomm Atheros Communications | 34        | 6.48%   |
| IMC Networks                    | 23        | 4.38%   |
| Cambridge Silicon Radio         | 20        | 3.81%   |
| Broadcom                        | 18        | 3.43%   |
| Apple                           | 18        | 3.43%   |
| Foxconn / Hon Hai               | 17        | 3.24%   |
| Lite-On Technology              | 12        | 2.29%   |
| ASUSTek Computer                | 10        | 1.9%    |
| Ralink                          | 4         | 0.76%   |
| MediaTek                        | 4         | 0.76%   |
| TP-Link                         | 3         | 0.57%   |
| Realtek                         | 3         | 0.57%   |
| Marvell Semiconductor           | 3         | 0.57%   |
| Toshiba                         | 2         | 0.38%   |
| Hewlett-Packard                 | 2         | 0.38%   |
| Dell                            | 2         | 0.38%   |
| Qcom                            | 1         | 0.19%   |
| Opticis                         | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 72        | 13.71%  |
| Intel Bluetooth Device                                                              | 71        | 13.52%  |
| Intel AX200 Bluetooth                                                               | 55        | 10.48%  |
| Realtek Bluetooth Radio                                                             | 48        | 9.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 35        | 6.67%   |
| Intel AX210 Bluetooth                                                               | 20        | 3.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 20        | 3.81%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 3.05%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 13        | 2.48%   |
| IMC Networks Wireless_Device                                                        | 11        | 2.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 10        | 1.9%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 9         | 1.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 1.33%   |
| Apple Bluetooth USB Host Controller                                                 | 7         | 1.33%   |
| Apple Bluetooth Host Controller                                                     | 7         | 1.33%   |
| IMC Networks Bluetooth Radio                                                        | 6         | 1.14%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.14%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 5         | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 0.95%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 0.95%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 0.76%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 0.76%   |
| MediaTek Wireless_Device                                                            | 4         | 0.76%   |
| Lite-On Wireless_Device                                                             | 4         | 0.76%   |
| TP-Link UB500 Adapter                                                               | 3         | 0.57%   |
| Realtek Bluetooth Radio                                                             | 3         | 0.57%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 3         | 0.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 0.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.57%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 0.57%   |
| ASUS Bluetooth Radio                                                                | 3         | 0.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 0.57%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.38%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.38%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.38%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.38%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.38%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.38%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.38%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 2         | 0.38%   |
| ASUS ASUS USB-BT500                                                                 | 2         | 0.38%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.19%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.19%   |
| Realtek Bluetooth 5.1 Radio                                                         | 1         | 0.19%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.19%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.19%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.19%   |
| Opticis Bluetooth Radio                                                             | 1         | 0.19%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.19%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.19%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.19%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.19%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.19%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.19%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.19%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.19%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.19%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 465       | 45.59%  |
| AMD                         | 240       | 23.53%  |
| Nvidia                      | 169       | 16.57%  |
| C-Media Electronics         | 20        | 1.96%   |
| Logitech                    | 10        | 0.98%   |
| Lenovo                      | 8         | 0.78%   |
| Corsair                     | 7         | 0.69%   |
| Texas Instruments           | 6         | 0.59%   |
| Plantronics                 | 6         | 0.59%   |
| Creative Technology         | 6         | 0.59%   |
| Creative Labs               | 6         | 0.59%   |
| JMTek                       | 5         | 0.49%   |
| Focusrite-Novation          | 5         | 0.49%   |
| XMOS                        | 4         | 0.39%   |
| Realtek Semiconductor       | 4         | 0.39%   |
| Razer USA                   | 4         | 0.39%   |
| GN Netcom                   | 4         | 0.39%   |
| Sony                        | 3         | 0.29%   |
| Conexant Systems            | 3         | 0.29%   |
| Blue Microphones            | 3         | 0.29%   |
| SteelSeries ApS             | 2         | 0.2%    |
| Sennheiser Communications   | 2         | 0.2%    |
| Samson Technologies         | 2         | 0.2%    |
| RODE Microphones            | 2         | 0.2%    |
| Native Instruments          | 2         | 0.2%    |
| Kingston Technology         | 2         | 0.2%    |
| Hewlett-Packard             | 2         | 0.2%    |
| Generalplus Technology      | 2         | 0.2%    |
| FIFINE Microphones          | 2         | 0.2%    |
| Yamaha                      | 1         | 0.1%    |
| USB PnP Sound Device        | 1         | 0.1%    |
| Turtle Beach                | 1         | 0.1%    |
| Trust                       | 1         | 0.1%    |
| Tenx Technology             | 1         | 0.1%    |
| Schiit Audio                | 1         | 0.1%    |
| Samsung Electronics         | 1         | 0.1%    |
| PreSonus Audio Electronics  | 1         | 0.1%    |
| No brand                    | 1         | 0.1%    |
| Microdia                    | 1         | 0.1%    |
| Micro Star International    | 1         | 0.1%    |
| M-Audio                     | 1         | 0.1%    |
| KORG                        | 1         | 0.1%    |
| GYROCOM C&C                 | 1         | 0.1%    |
| Giga-Byte Technology        | 1         | 0.1%    |
| FiiO Electronics Technology | 1         | 0.1%    |
| fifinemicrophone.com        | 1         | 0.1%    |
| Dell                        | 1         | 0.1%    |
| Cooler Master               | 1         | 0.1%    |
| Cambridge Silicon Radio     | 1         | 0.1%    |
| Bose                        | 1         | 0.1%    |
| Astro Gaming                | 1         | 0.1%    |
| Apple                       | 1         | 0.1%    |
| AOKEO                       | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 114       | 9.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 68        | 5.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 59        | 4.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 59        | 4.76%   |
| AMD Starship/Matisse HD Audio Controller                                   | 41        | 3.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 39        | 3.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 32        | 2.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 31        | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 28        | 2.26%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 25        | 2.02%   |
| Intel Comet Lake PCH cAVS                                                  | 24        | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 22        | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 19        | 1.53%   |
| Intel Haswell-ULT HD Audio Controller                                      | 18        | 1.45%   |
| Intel 8 Series HD Audio Controller                                         | 18        | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                               | 16        | 1.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 16        | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16        | 1.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16        | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 15        | 1.21%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 1.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 15        | 1.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 15        | 1.21%   |
| Nvidia Audio device                                                        | 14        | 1.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 1.05%   |
| Nvidia GA104 High Definition Audio Controller                              | 12        | 0.97%   |
| Intel 200 Series PCH HD Audio                                              | 12        | 0.97%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 11        | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11        | 0.89%   |
| AMD Navi 10 HDMI Audio                                                     | 10        | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9         | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 9         | 0.73%   |
| Intel Alder Lake-S HD Audio Controller                                     | 9         | 0.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 9         | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 0.65%   |
| Nvidia GM206 High Definition Audio Controller                              | 8         | 0.65%   |
| Intel CM238 HD Audio Controller                                            | 8         | 0.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 0.65%   |
| Nvidia TU104 HD Audio Controller                                           | 7         | 0.56%   |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 0.56%   |
| Nvidia GM204 High Definition Audio Controller                              | 7         | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                         | 7         | 0.56%   |
| Nvidia GK104 HDMI Audio Controller                                         | 7         | 0.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 0.56%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7         | 0.56%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 0.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 0.48%   |
| C-Media Electronics USB Audio Device                                       | 6         | 0.48%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 6         | 0.48%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 0.48%   |
| Nvidia GF119 HDMI Audio Controller                                         | 5         | 0.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 0.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 0.4%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5         | 0.4%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5         | 0.4%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 0.4%    |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 0.4%    |
| AMD FCH Azalia Controller                                                  | 5         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 96        | 26.09%  |
| SK hynix            | 74        | 20.11%  |
| Micron Technology   | 38        | 10.33%  |
| Kingston            | 33        | 8.97%   |
| Crucial             | 27        | 7.34%   |
| G.Skill             | 22        | 5.98%   |
| Unknown             | 21        | 5.71%   |
| Corsair             | 13        | 3.53%   |
| Ramaxel Technology  | 8         | 2.17%   |
| Unknown (ABCD)      | 5         | 1.36%   |
| A-DATA Technology   | 5         | 1.36%   |
| Nanya Technology    | 3         | 0.82%   |
| Unknown             | 3         | 0.82%   |
| Team                | 2         | 0.54%   |
| Smart               | 2         | 0.54%   |
| Patriot             | 2         | 0.54%   |
| V-GeN               | 1         | 0.27%   |
| Timetec             | 1         | 0.27%   |
| Silicon Power       | 1         | 0.27%   |
| Sesame              | 1         | 0.27%   |
| Samsung 1           | 1         | 0.27%   |
| PNY                 | 1         | 0.27%   |
| Neo Forza           | 1         | 0.27%   |
| Mushkin             | 1         | 0.27%   |
| Kllisre             | 1         | 0.27%   |
| Hikvision           | 1         | 0.27%   |
| Goodram             | 1         | 0.27%   |
| Elpida              | 1         | 0.27%   |
| AMD                 | 1         | 0.27%   |
| A-TECH              | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 8         | 2.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 6         | 1.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 1.28%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 1.28%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 5         | 1.28%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 4         | 1.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 1.03%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s           | 4         | 1.03%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 4         | 1.03%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 0.77%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.77%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 3         | 0.77%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 0.77%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.77%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 0.77%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 3         | 0.77%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                | 3         | 0.77%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s               | 3         | 0.77%   |
| Unknown                                                             | 3         | 0.77%   |
| Unknown RAM Module 4GB DIMM 400MT/s                                 | 2         | 0.51%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 2         | 0.51%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 2         | 0.51%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                 | 2         | 0.51%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 2         | 0.51%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 2         | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.51%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.51%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s             | 2         | 0.51%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 2         | 0.51%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.51%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 2         | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 2         | 0.51%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 2         | 0.51%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s    | 2         | 0.51%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                         | 2         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.51%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 2         | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 0.51%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.51%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 0.51%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s            | 2         | 0.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 0.51%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s                  | 2         | 0.51%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s                 | 2         | 0.51%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s           | 2         | 0.51%   |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.51%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 2         | 0.51%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 0.51%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 2         | 0.51%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s               | 2         | 0.51%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                   | 2         | 0.51%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s               | 2         | 0.51%   |
| G.Skill RAM F4-3200C14-8GTZR 8GB DIMM DDR4 3200MT/s                 | 2         | 0.51%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1867MT/s                | 2         | 0.51%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s          | 2         | 0.51%   |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s                       | 1         | 0.26%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 186       | 59.05%  |
| DDR3    | 67        | 21.27%  |
| LPDDR4  | 24        | 7.62%   |
| Unknown | 19        | 6.03%   |
| LPDDR3  | 14        | 4.44%   |
| DDR2    | 3         | 0.95%   |
| SDRAM   | 1         | 0.32%   |
| DDR     | 1         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 186       | 57.94%  |
| DIMM         | 84        | 26.17%  |
| Row Of Chips | 46        | 14.33%  |
| RIMM         | 2         | 0.62%   |
| Chip         | 2         | 0.62%   |
| Unknown      | 1         | 0.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 144       | 42.11%  |
| 4096  | 96        | 28.07%  |
| 16384 | 57        | 16.67%  |
| 2048  | 25        | 7.31%   |
| 32768 | 14        | 4.09%   |
| 1024  | 5         | 1.46%   |
| 3072  | 1         | 0.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 88        | 26.04%  |
| 2667    | 51        | 15.09%  |
| 1600    | 50        | 14.79%  |
| 2400    | 24        | 7.1%    |
| 2133    | 22        | 6.51%   |
| 4267    | 14        | 4.14%   |
| 1867    | 13        | 3.85%   |
| 3600    | 10        | 2.96%   |
| 1333    | 8         | 2.37%   |
| 4800    | 7         | 2.07%   |
| 3266    | 5         | 1.48%   |
| 3466    | 4         | 1.18%   |
| 2933    | 4         | 1.18%   |
| Unknown | 4         | 1.18%   |
| 6400    | 3         | 0.89%   |
| 1334    | 3         | 0.89%   |
| 800     | 3         | 0.89%   |
| 400     | 3         | 0.89%   |
| 4266    | 2         | 0.59%   |
| 3866    | 2         | 0.59%   |
| 1067    | 2         | 0.59%   |
| 667     | 2         | 0.59%   |
| 8400    | 1         | 0.3%    |
| 3733    | 1         | 0.3%    |
| 3333    | 1         | 0.3%    |
| 3000    | 1         | 0.3%    |
| 2800    | 1         | 0.3%    |
| 2733    | 1         | 0.3%    |
| 2666    | 1         | 0.3%    |
| 2600    | 1         | 0.3%    |
| 2048    | 1         | 0.3%    |
| 1639    | 1         | 0.3%    |
| 1200    | 1         | 0.3%    |
| 1066    | 1         | 0.3%    |
| 333     | 1         | 0.3%    |
| 200     | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 33.33%  |
| Brother Industries | 2         | 33.33%  |
| Kyocera            | 1         | 16.67%  |
| Graphtec America   | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Kyocera ECOSYS M5521cdw           | 1         | 16.67%  |
| HP Neverstop Laser 100x           | 1         | 16.67%  |
| HP Ink Tank 310 series            | 1         | 16.67%  |
| Graphtec America Graphtec Printer | 1         | 16.67%  |
| Brother Printer                   | 1         | 16.67%  |
| Brother DCP-T510W                 | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 5         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 100 | 2         | 40%     |
| Canon CanoScan LiDE 220 | 1         | 20%     |
| Canon CanoScan LiDE 210 | 1         | 20%     |
| Canon CanoScan LiDE 200 | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 101       | 21.13%  |
| IMC Networks                           | 63        | 13.18%  |
| Microdia                               | 38        | 7.95%   |
| Acer                                   | 37        | 7.74%   |
| Realtek Semiconductor                  | 31        | 6.49%   |
| Logitech                               | 31        | 6.49%   |
| Quanta                                 | 27        | 5.65%   |
| Syntek                                 | 22        | 4.6%    |
| Sunplus Innovation Technology          | 19        | 3.97%   |
| Lite-On Technology                     | 16        | 3.35%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 2.93%   |
| Apple                                  | 14        | 2.93%   |
| Luxvisions Innotech Limited            | 12        | 2.51%   |
| Suyin                                  | 5         | 1.05%   |
| Ricoh                                  | 5         | 1.05%   |
| Microsoft                              | 5         | 1.05%   |
| SunplusIT                              | 4         | 0.84%   |
| Silicon Motion                         | 4         | 0.84%   |
| Samsung Electronics                    | 3         | 0.63%   |
| Lenovo                                 | 3         | 0.63%   |
| KYE Systems (Mouse Systems)            | 3         | 0.63%   |
| Unknown                                | 2         | 0.42%   |
| Sonix Technology                       | 2         | 0.42%   |
| Primax Electronics                     | 2         | 0.42%   |
| Hewlett-Packard                        | 2         | 0.42%   |
| Creative Technology                    | 2         | 0.42%   |
| Alcor Micro                            | 2         | 0.42%   |
| Z-Star Microelectronics                | 1         | 0.21%   |
| OPPO Electronics                       | 1         | 0.21%   |
| MacroSilicon                           | 1         | 0.21%   |
| icSpring                               | 1         | 0.21%   |
| Generalplus Technology                 | 1         | 0.21%   |
| FPL-2053-191010                        | 1         | 0.21%   |
| Asuscom Network                        | 1         | 0.21%   |
| ARC International                      | 1         | 0.21%   |
| 8SSC20F27145V1SR1BX02P8                | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 34        | 7.02%   |
| Microdia Integrated_Webcam_HD                        | 29        | 5.99%   |
| IMC Networks Integrated Camera                       | 25        | 5.17%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 21        | 4.34%   |
| Syntek Integrated Camera                             | 14        | 2.89%   |
| Chicony HD WebCam                                    | 14        | 2.89%   |
| Acer Integrated Camera                               | 14        | 2.89%   |
| Realtek Integrated_Webcam_HD                         | 13        | 2.69%   |
| Logitech HD Pro Webcam C920                          | 11        | 2.27%   |
| Lite-On Integrated Camera                            | 8         | 1.65%   |
| Chicony Integrated Camera (1280x720@30)              | 8         | 1.65%   |
| Chicony HP Wide Vision HD Camera                     | 8         | 1.65%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 7         | 1.45%   |
| Apple FaceTime HD Camera (Built-in)                  | 7         | 1.45%   |
| Quanta HD User Facing                                | 6         | 1.24%   |
| Chicony HP TrueVision HD Camera                      | 6         | 1.24%   |
| Quanta HP TrueVision HD Camera                       | 5         | 1.03%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 5         | 1.03%   |
| Sunplus Full HD webcam                               | 4         | 0.83%   |
| Realtek Integrated Webcam                            | 4         | 0.83%   |
| Quanta HP HD Camera                                  | 4         | 0.83%   |
| Logitech C920 PRO HD Webcam                          | 4         | 0.83%   |
| Lite-On HP Wide Vision HD Camera                     | 4         | 0.83%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 4         | 0.83%   |
| Acer Lenovo EasyCamera                               | 4         | 0.83%   |
| Syntek Lenovo EasyCamera                             | 3         | 0.62%   |
| Syntek EasyCamera                                    | 3         | 0.62%   |
| Sunplus Integrated_Webcam_HD                         | 3         | 0.62%   |
| Sunplus HD WebCam                                    | 3         | 0.62%   |
| Samsung Galaxy series, misc. (MTP mode)              | 3         | 0.62%   |
| Quanta HP Webcam                                     | 3         | 0.62%   |
| Logitech BRIO Ultra HD Webcam                        | 3         | 0.62%   |
| Lite-On HP HD Camera                                 | 3         | 0.62%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera           | 3         | 0.62%   |
| IMC Networks HD Camera                               | 3         | 0.62%   |
| Chicony HP HD Camera                                 | 3         | 0.62%   |
| Apple Built-in iSight                                | 3         | 0.62%   |
| Acer BisonCam,NB Pro                                 | 3         | 0.62%   |
| Syntek Integrated RGB Camera                         | 2         | 0.41%   |
| SunplusIT MTD camera                                 | 2         | 0.41%   |
| Sunplus Asus Webcam                                  | 2         | 0.41%   |
| Sonix USB2.0 HD UVC WebCam                           | 2         | 0.41%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 2         | 0.41%   |
| Realtek Laptop Camera                                | 2         | 0.41%   |
| Realtek Intergrated Camera 5M                        | 2         | 0.41%   |
| Realtek Front Camera                                 | 2         | 0.41%   |
| Quanta VGA WebCam                                    | 2         | 0.41%   |
| Primax HP HD Webcam [Fixed]                          | 2         | 0.41%   |
| Microsoft LifeCam HD-3000                            | 2         | 0.41%   |
| Microdia USB 2.0 Camera                              | 2         | 0.41%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.41%   |
| Luxvisions Innotech Limited HP HD Camera             | 2         | 0.41%   |
| Logitech Webcam C925e                                | 2         | 0.41%   |
| Logitech Webcam C310                                 | 2         | 0.41%   |
| Logitech Webcam C270                                 | 2         | 0.41%   |
| Logitech HD Webcam C525                              | 2         | 0.41%   |
| IMC Networks XiaoMi Webcam                           | 2         | 0.41%   |
| Chicony USB2.0 HD UVC WebCam                         | 2         | 0.41%   |
| Chicony USB2.0 Camera                                | 2         | 0.41%   |
| Chicony USB 2.0 Camera                               | 2         | 0.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 57        | 44.53%  |
| Validity Sensors           | 25        | 19.53%  |
| Shenzhen Goodix Technology | 24        | 18.75%  |
| LighTuning Technology      | 7         | 5.47%   |
| Elan Microelectronics      | 6         | 4.69%   |
| Upek                       | 4         | 3.13%   |
| AuthenTec                  | 3         | 2.34%   |
| Focal-systems.Corp         | 1         | 0.78%   |
| DigitalPersona             | 1         | 0.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 27        | 21.09%  |
| Unknown                                                     | 15        | 11.72%  |
| Shenzhen Goodix  FingerPrint Device                         | 13        | 10.16%  |
| Shenzhen Goodix Fingerprint Reader                          | 6         | 4.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 5         | 3.91%   |
| Shenzhen Goodix FingerPrint                                 | 5         | 3.91%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 5         | 3.91%   |
| Validity Sensors VFS495 Fingerprint Reader                  | 4         | 3.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 4         | 3.13%   |
| Validity Sensors Synaptics WBDI                             | 4         | 3.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 4         | 3.13%   |
| Elan ELAN:ARM-M4                                            | 4         | 3.13%   |
| Validity Sensors VFS491                                     | 3         | 2.34%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint  | 3         | 2.34%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 3         | 2.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 2         | 1.56%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 2         | 1.56%   |
| Synaptics  WBDI                                             | 2         | 1.56%   |
| Elan ELAN:Fingerprint                                       | 2         | 1.56%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor           | 1         | 0.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 1         | 0.78%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 1         | 0.78%   |
| Validity Sensors VFS301 Fingerprint Reader                  | 1         | 0.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 0.78%   |
| Validity Sensors Fingerprint scanner                        | 1         | 0.78%   |
| Synaptics WBDI Device                                       | 1         | 0.78%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 0.78%   |
| LighTuning Fingerprint Reader                               | 1         | 0.78%   |
| LighTuning ES603 Swipe Fingerprint Sensor                   | 1         | 0.78%   |
| Focal-systems.Corp FT9201Fingerprint.                       | 1         | 0.78%   |
| DigitalPersona Fingerprint Reader                           | 1         | 0.78%   |
| AuthenTec AES2810                                           | 1         | 0.78%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 1         | 0.78%   |
| AuthenTec AES1660 Fingerprint Sensor                        | 1         | 0.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 18        | 47.37%  |
| Broadcom              | 15        | 39.47%  |
| Upek                  | 1         | 2.63%   |
| SCM Microsystems      | 1         | 2.63%   |
| Realtek Semiconductor | 1         | 2.63%   |
| OmniKey               | 1         | 2.63%   |
| Gemalto (was Gemplus) | 1         | 2.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 44.74%  |
| Broadcom 58200                                                               | 6         | 15.79%  |
| Broadcom 5880                                                                | 4         | 10.53%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 7.89%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5.26%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 2.63%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 2.63%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 2.63%   |
| OmniKey CardMan 1021                                                         | 1         | 2.63%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2.63%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 2.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 434       | 62.9%   |
| 1     | 200       | 28.99%  |
| 2     | 45        | 6.52%   |
| 3     | 10        | 1.45%   |
| 4     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 126       | 41.31%  |
| Graphics card            | 64        | 20.98%  |
| Net/wireless             | 31        | 10.16%  |
| Multimedia controller    | 31        | 10.16%  |
| Camera                   | 11        | 3.61%   |
| Chipcard                 | 7         | 2.3%    |
| Card reader              | 7         | 2.3%    |
| Bluetooth                | 7         | 2.3%    |
| Unassigned class         | 4         | 1.31%   |
| Sound                    | 4         | 1.31%   |
| Modem                    | 4         | 1.31%   |
| Network                  | 3         | 0.98%   |
| Storage                  | 2         | 0.66%   |
| Communication controller | 2         | 0.66%   |
| Net/ethernet             | 1         | 0.33%   |
| Firewire controller      | 1         | 0.33%   |

