Arch - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Arch.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Arch/Desktop/README.md) and [notebooks](/Dist/Arch/Notebook/README.md).

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

Total: 7405

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | X570S AORUS PRO AX          | Notebook    | [253135f8dc](https://linux-hardware.org/?probe=253135f8dc) | Dec 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [7ff54a3b05](https://linux-hardware.org/?probe=7ff54a3b05) | Dec 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d57de89542](https://linux-hardware.org/?probe=d57de89542) | Dec 01, 2022 |
| Lenovo        | B40-70 20392                | Notebook    | [a527c5b6e6](https://linux-hardware.org/?probe=a527c5b6e6) | Dec 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5b86ca0927](https://linux-hardware.org/?probe=5b86ca0927) | Dec 01, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | Notebook    | [cccb2da575](https://linux-hardware.org/?probe=cccb2da575) | Dec 01, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [8de79673ea](https://linux-hardware.org/?probe=8de79673ea) | Dec 01, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [e2f97abdea](https://linux-hardware.org/?probe=e2f97abdea) | Nov 30, 2022 |
| Samsung       | 730QAA                      | Convertible | [7ec4c2ecfd](https://linux-hardware.org/?probe=7ec4c2ecfd) | Nov 30, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [c117ba54ea](https://linux-hardware.org/?probe=c117ba54ea) | Nov 30, 2022 |
| Dell          | 0WWJRX A00                  | Desktop     | [83ef480c7d](https://linux-hardware.org/?probe=83ef480c7d) | Nov 30, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b4c010a2b2](https://linux-hardware.org/?probe=b4c010a2b2) | Nov 30, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [47131749a5](https://linux-hardware.org/?probe=47131749a5) | Nov 30, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [d3a1f181d5](https://linux-hardware.org/?probe=d3a1f181d5) | Nov 30, 2022 |
| Positivo B... | S14SL03                     | Notebook    | [a42ebacec4](https://linux-hardware.org/?probe=a42ebacec4) | Nov 29, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [50a779c35d](https://linux-hardware.org/?probe=50a779c35d) | Nov 29, 2022 |
| IBM           | MSI-9151 Boards             | Desktop     | [720ff829b9](https://linux-hardware.org/?probe=720ff829b9) | Nov 29, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [9f473cbdeb](https://linux-hardware.org/?probe=9f473cbdeb) | Nov 29, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ff119f84e6](https://linux-hardware.org/?probe=ff119f84e6) | Nov 29, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [b06377f324](https://linux-hardware.org/?probe=b06377f324) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [d258962c35](https://linux-hardware.org/?probe=d258962c35) | Nov 28, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [a3c2004787](https://linux-hardware.org/?probe=a3c2004787) | Nov 28, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ceb78dbe4e](https://linux-hardware.org/?probe=ceb78dbe4e) | Nov 28, 2022 |
| Timi          | TM1613                      | Notebook    | [37036a425d](https://linux-hardware.org/?probe=37036a425d) | Nov 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [becbfa5cc7](https://linux-hardware.org/?probe=becbfa5cc7) | Nov 28, 2022 |
| Dell          | G15 5520                    | Notebook    | [251078d1b4](https://linux-hardware.org/?probe=251078d1b4) | Nov 28, 2022 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [ccc431ef2e](https://linux-hardware.org/?probe=ccc431ef2e) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [0d99651537](https://linux-hardware.org/?probe=0d99651537) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [3f660318ea](https://linux-hardware.org/?probe=3f660318ea) | Nov 28, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [f18a4c8031](https://linux-hardware.org/?probe=f18a4c8031) | Nov 28, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b0078eda9b](https://linux-hardware.org/?probe=b0078eda9b) | Nov 27, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [15909202b8](https://linux-hardware.org/?probe=15909202b8) | Nov 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [d8bb1b1d38](https://linux-hardware.org/?probe=d8bb1b1d38) | Nov 27, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [e5ac492508](https://linux-hardware.org/?probe=e5ac492508) | Nov 27, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c2c27cf47f](https://linux-hardware.org/?probe=c2c27cf47f) | Nov 27, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [4825bcbe78](https://linux-hardware.org/?probe=4825bcbe78) | Nov 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [7bdb03388b](https://linux-hardware.org/?probe=7bdb03388b) | Nov 27, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [847b1cb39a](https://linux-hardware.org/?probe=847b1cb39a) | Nov 26, 2022 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [9b3a058fda](https://linux-hardware.org/?probe=9b3a058fda) | Nov 26, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [1b3355afbc](https://linux-hardware.org/?probe=1b3355afbc) | Nov 26, 2022 |
| ASUSTek       | K70AB                       | Notebook    | [8b7e3c4b9e](https://linux-hardware.org/?probe=8b7e3c4b9e) | Nov 26, 2022 |
| Dell          | Latitude 5490               | Notebook    | [7aedc1fbd7](https://linux-hardware.org/?probe=7aedc1fbd7) | Nov 26, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [0e3f081937](https://linux-hardware.org/?probe=0e3f081937) | Nov 26, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [098116b1d6](https://linux-hardware.org/?probe=098116b1d6) | Nov 26, 2022 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [0cd6df782e](https://linux-hardware.org/?probe=0cd6df782e) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [cd9478ab62](https://linux-hardware.org/?probe=cd9478ab62) | Nov 26, 2022 |
| ASRock        | B460M-HDV                   | Desktop     | [00c07e7aa9](https://linux-hardware.org/?probe=00c07e7aa9) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [1f2bd09174](https://linux-hardware.org/?probe=1f2bd09174) | Nov 25, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [9768df6ae0](https://linux-hardware.org/?probe=9768df6ae0) | Nov 25, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [1564025817](https://linux-hardware.org/?probe=1564025817) | Nov 25, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [c639db74cb](https://linux-hardware.org/?probe=c639db74cb) | Nov 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [2d1c8c7ea5](https://linux-hardware.org/?probe=2d1c8c7ea5) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ce5f08445d](https://linux-hardware.org/?probe=ce5f08445d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [4efc557c1b](https://linux-hardware.org/?probe=4efc557c1b) | Nov 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [d2d484b35b](https://linux-hardware.org/?probe=d2d484b35b) | Nov 24, 2022 |
| Gateway       | SX2803                      | Desktop     | [68a008f332](https://linux-hardware.org/?probe=68a008f332) | Nov 24, 2022 |
| MECER         | YA13Q20-DP_PRO              | Notebook    | [c51a900a73](https://linux-hardware.org/?probe=c51a900a73) | Nov 23, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ed9d641fda](https://linux-hardware.org/?probe=ed9d641fda) | Nov 23, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [4f6911ae2c](https://linux-hardware.org/?probe=4f6911ae2c) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [51ca9fa048](https://linux-hardware.org/?probe=51ca9fa048) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [0ca1ce1d74](https://linux-hardware.org/?probe=0ca1ce1d74) | Nov 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [47d808147c](https://linux-hardware.org/?probe=47d808147c) | Nov 23, 2022 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [2f32726e0d](https://linux-hardware.org/?probe=2f32726e0d) | Nov 23, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RJ0... | Notebook    | [43f6a19d9a](https://linux-hardware.org/?probe=43f6a19d9a) | Nov 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [65a3383e83](https://linux-hardware.org/?probe=65a3383e83) | Nov 22, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [7d952c2b0d](https://linux-hardware.org/?probe=7d952c2b0d) | Nov 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [0584338e31](https://linux-hardware.org/?probe=0584338e31) | Nov 22, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b7bd63db1c](https://linux-hardware.org/?probe=b7bd63db1c) | Nov 22, 2022 |
| HP            | EliteBook 8460w             | Notebook    | [cdb72eea80](https://linux-hardware.org/?probe=cdb72eea80) | Nov 22, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [fdafa2db2a](https://linux-hardware.org/?probe=fdafa2db2a) | Nov 22, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [3f9c0d5b63](https://linux-hardware.org/?probe=3f9c0d5b63) | Nov 22, 2022 |
| ASUSTek       | GL503VS                     | Notebook    | [18fa411a6d](https://linux-hardware.org/?probe=18fa411a6d) | Nov 22, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [57b2e84560](https://linux-hardware.org/?probe=57b2e84560) | Nov 22, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [70267d756a](https://linux-hardware.org/?probe=70267d756a) | Nov 21, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [308968646b](https://linux-hardware.org/?probe=308968646b) | Nov 21, 2022 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [c14020107c](https://linux-hardware.org/?probe=c14020107c) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8de96e0012](https://linux-hardware.org/?probe=8de96e0012) | Nov 20, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [cd2b457ffb](https://linux-hardware.org/?probe=cd2b457ffb) | Nov 20, 2022 |
| HP            | Notebook                    | Notebook    | [1278403b39](https://linux-hardware.org/?probe=1278403b39) | Nov 20, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2db5ac853d](https://linux-hardware.org/?probe=2db5ac853d) | Nov 20, 2022 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [ecafbb7acb](https://linux-hardware.org/?probe=ecafbb7acb) | Nov 20, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9b0f3f926d](https://linux-hardware.org/?probe=9b0f3f926d) | Nov 20, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [ba2c2a39ed](https://linux-hardware.org/?probe=ba2c2a39ed) | Nov 20, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [07985535f4](https://linux-hardware.org/?probe=07985535f4) | Nov 20, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [9484c00cb6](https://linux-hardware.org/?probe=9484c00cb6) | Nov 20, 2022 |
| HP            | 8055                        | Desktop     | [65b0ad04f1](https://linux-hardware.org/?probe=65b0ad04f1) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [08372f6535](https://linux-hardware.org/?probe=08372f6535) | Nov 20, 2022 |
| Dell          | XPS 9320                    | Notebook    | [e590d602a9](https://linux-hardware.org/?probe=e590d602a9) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7ac338ce0d](https://linux-hardware.org/?probe=7ac338ce0d) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [50bd30f30d](https://linux-hardware.org/?probe=50bd30f30d) | Nov 19, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [85e0869ac9](https://linux-hardware.org/?probe=85e0869ac9) | Nov 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [9d276a36d8](https://linux-hardware.org/?probe=9d276a36d8) | Nov 19, 2022 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [4956957df8](https://linux-hardware.org/?probe=4956957df8) | Nov 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [362cf69f1f](https://linux-hardware.org/?probe=362cf69f1f) | Nov 19, 2022 |
| Dell          | Latitude E5440              | Notebook    | [f423bbe9b0](https://linux-hardware.org/?probe=f423bbe9b0) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [865fa07274](https://linux-hardware.org/?probe=865fa07274) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [68d651f36b](https://linux-hardware.org/?probe=68d651f36b) | Nov 19, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [87219ba8e3](https://linux-hardware.org/?probe=87219ba8e3) | Nov 19, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [6a39161e50](https://linux-hardware.org/?probe=6a39161e50) | Nov 19, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9b19115bc7](https://linux-hardware.org/?probe=9b19115bc7) | Nov 18, 2022 |
| Dell          | Latitude E5440              | Notebook    | [0f98fe6066](https://linux-hardware.org/?probe=0f98fe6066) | Nov 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [0cdd3b10fc](https://linux-hardware.org/?probe=0cdd3b10fc) | Nov 18, 2022 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [7c8a72cae4](https://linux-hardware.org/?probe=7c8a72cae4) | Nov 18, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [54f40f8c4b](https://linux-hardware.org/?probe=54f40f8c4b) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [469ead98f8](https://linux-hardware.org/?probe=469ead98f8) | Nov 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [018a2825bf](https://linux-hardware.org/?probe=018a2825bf) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bb2db87e9a](https://linux-hardware.org/?probe=bb2db87e9a) | Nov 17, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [8a9570e828](https://linux-hardware.org/?probe=8a9570e828) | Nov 17, 2022 |
| Alienware     | m17                         | Notebook    | [e3e14a271a](https://linux-hardware.org/?probe=e3e14a271a) | Nov 17, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [d62ee2298d](https://linux-hardware.org/?probe=d62ee2298d) | Nov 16, 2022 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | Notebook    | [69f54ed610](https://linux-hardware.org/?probe=69f54ed610) | Nov 16, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [c53f301391](https://linux-hardware.org/?probe=c53f301391) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [91268b9919](https://linux-hardware.org/?probe=91268b9919) | Nov 16, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [b0c0ad46de](https://linux-hardware.org/?probe=b0c0ad46de) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [e2982c0c35](https://linux-hardware.org/?probe=e2982c0c35) | Nov 16, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5ce6a414cd](https://linux-hardware.org/?probe=5ce6a414cd) | Nov 16, 2022 |
| HP            | 83EE                        | Desktop     | [182682b17c](https://linux-hardware.org/?probe=182682b17c) | Nov 16, 2022 |
| HP            | 83EE                        | Desktop     | [65d7bade6e](https://linux-hardware.org/?probe=65d7bade6e) | Nov 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [ca24381492](https://linux-hardware.org/?probe=ca24381492) | Nov 15, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | Notebook    | [96db8793b2](https://linux-hardware.org/?probe=96db8793b2) | Nov 15, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | Notebook    | [c576805c81](https://linux-hardware.org/?probe=c576805c81) | Nov 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [35cb137655](https://linux-hardware.org/?probe=35cb137655) | Nov 15, 2022 |
| Alienware     | m17                         | Notebook    | [4140c68e95](https://linux-hardware.org/?probe=4140c68e95) | Nov 15, 2022 |
| ASUSTek       | A58M-A/USB3                 | Desktop     | [f6342a3d18](https://linux-hardware.org/?probe=f6342a3d18) | Nov 15, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [403bc1b6b5](https://linux-hardware.org/?probe=403bc1b6b5) | Nov 14, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [6209796b42](https://linux-hardware.org/?probe=6209796b42) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [d28a778811](https://linux-hardware.org/?probe=d28a778811) | Nov 14, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [1501d641b4](https://linux-hardware.org/?probe=1501d641b4) | Nov 14, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [dc808c4131](https://linux-hardware.org/?probe=dc808c4131) | Nov 14, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [d584008808](https://linux-hardware.org/?probe=d584008808) | Nov 14, 2022 |
| Fujitsu       | LIFEBOOK U7511              | Notebook    | [66656bedcf](https://linux-hardware.org/?probe=66656bedcf) | Nov 14, 2022 |
| Dell          | 03KWTV A02                  | Desktop     | [2853121816](https://linux-hardware.org/?probe=2853121816) | Nov 14, 2022 |
| Lenovo        | XiaoXinPro 14ACH 2021 82... | Notebook    | [d74b37eebb](https://linux-hardware.org/?probe=d74b37eebb) | Nov 13, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [dcb6d439d4](https://linux-hardware.org/?probe=dcb6d439d4) | Nov 13, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [c16c0f7d8f](https://linux-hardware.org/?probe=c16c0f7d8f) | Nov 13, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [7290725ced](https://linux-hardware.org/?probe=7290725ced) | Nov 13, 2022 |
| HP            | 88BE                        | Desktop     | [1c03e5957d](https://linux-hardware.org/?probe=1c03e5957d) | Nov 13, 2022 |
| EVGA          | Z690 CLASSIFIED.0           | Desktop     | [aabaab5ceb](https://linux-hardware.org/?probe=aabaab5ceb) | Nov 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0bc3c759d6](https://linux-hardware.org/?probe=0bc3c759d6) | Nov 13, 2022 |
| HONOR         | BOD-WXX9                    | Notebook    | [ca8b207b30](https://linux-hardware.org/?probe=ca8b207b30) | Nov 12, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [768efc0c32](https://linux-hardware.org/?probe=768efc0c32) | Nov 12, 2022 |
| ASUSTek       | P8P67 EVO                   | Desktop     | [c033c311f3](https://linux-hardware.org/?probe=c033c311f3) | Nov 12, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [2d2cdbb40b](https://linux-hardware.org/?probe=2d2cdbb40b) | Nov 12, 2022 |
| Packard Be... | EasyNote LJ65               | Notebook    | [1de1737600](https://linux-hardware.org/?probe=1de1737600) | Nov 12, 2022 |
| Gigabyte      | G5 KE                       | Notebook    | [aefbee04fd](https://linux-hardware.org/?probe=aefbee04fd) | Nov 12, 2022 |
| Acer          | AO722                       | Notebook    | [5c51412f98](https://linux-hardware.org/?probe=5c51412f98) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d134c6d6bf](https://linux-hardware.org/?probe=d134c6d6bf) | Nov 12, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [842f768168](https://linux-hardware.org/?probe=842f768168) | Nov 12, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [7fded9a538](https://linux-hardware.org/?probe=7fded9a538) | Nov 12, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [361f37b08d](https://linux-hardware.org/?probe=361f37b08d) | Nov 11, 2022 |
| Google        | Blooglet                    | Notebook    | [bd55466988](https://linux-hardware.org/?probe=bd55466988) | Nov 11, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [8bbd88e580](https://linux-hardware.org/?probe=8bbd88e580) | Nov 11, 2022 |
| Komplett      | LAPQC71B                    | Notebook    | [b5ee8960c6](https://linux-hardware.org/?probe=b5ee8960c6) | Nov 11, 2022 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [38763f3628](https://linux-hardware.org/?probe=38763f3628) | Nov 11, 2022 |
| MSI           | D2415 S26361-D2415-A10      | Desktop     | [924e18bdcc](https://linux-hardware.org/?probe=924e18bdcc) | Nov 10, 2022 |
| ASUSTek       | K54C                        | Notebook    | [e347d4a0f5](https://linux-hardware.org/?probe=e347d4a0f5) | Nov 10, 2022 |
| MSI           | GV62 8RC                    | Notebook    | [859227b2bb](https://linux-hardware.org/?probe=859227b2bb) | Nov 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d6fd1a5ecd](https://linux-hardware.org/?probe=d6fd1a5ecd) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [f20eddfba9](https://linux-hardware.org/?probe=f20eddfba9) | Nov 10, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [34e25768ae](https://linux-hardware.org/?probe=34e25768ae) | Nov 10, 2022 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [39b6ceb06c](https://linux-hardware.org/?probe=39b6ceb06c) | Nov 10, 2022 |
| Panasonic     | CF-R9KWCTDR                 | Notebook    | [2a414f5dc5](https://linux-hardware.org/?probe=2a414f5dc5) | Nov 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9c6a00b034](https://linux-hardware.org/?probe=9c6a00b034) | Nov 09, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | Notebook    | [abbb784ea9](https://linux-hardware.org/?probe=abbb784ea9) | Nov 09, 2022 |
| MSI           | GL63 8RD                    | Notebook    | [e10069a2f8](https://linux-hardware.org/?probe=e10069a2f8) | Nov 09, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [0847b8a5d7](https://linux-hardware.org/?probe=0847b8a5d7) | Nov 09, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [a5446ab998](https://linux-hardware.org/?probe=a5446ab998) | Nov 09, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [6642f568d4](https://linux-hardware.org/?probe=6642f568d4) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [e69d9794fd](https://linux-hardware.org/?probe=e69d9794fd) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [3e90cd2d25](https://linux-hardware.org/?probe=3e90cd2d25) | Nov 09, 2022 |
| OKI Brasil    | ST 4280 Padrao              | Desktop     | [f2841b0f4d](https://linux-hardware.org/?probe=f2841b0f4d) | Nov 08, 2022 |
| DERE          | V14                         | Notebook    | [0431077216](https://linux-hardware.org/?probe=0431077216) | Nov 08, 2022 |
| OKI Brasil    | ST 4280 Padrao              | Desktop     | [58cb07d7e1](https://linux-hardware.org/?probe=58cb07d7e1) | Nov 08, 2022 |
| ASRock        | X370 Gaming K4              | Desktop     | [f0634d863e](https://linux-hardware.org/?probe=f0634d863e) | Nov 08, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [d8bae2c402](https://linux-hardware.org/?probe=d8bae2c402) | Nov 08, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [f36e8a56db](https://linux-hardware.org/?probe=f36e8a56db) | Nov 08, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [2670a536f0](https://linux-hardware.org/?probe=2670a536f0) | Nov 08, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [b4d22497e8](https://linux-hardware.org/?probe=b4d22497e8) | Nov 08, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [ee895bde1f](https://linux-hardware.org/?probe=ee895bde1f) | Nov 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0e2747c7ab](https://linux-hardware.org/?probe=0e2747c7ab) | Nov 08, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [d19fce3e6c](https://linux-hardware.org/?probe=d19fce3e6c) | Nov 08, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [47ac77d647](https://linux-hardware.org/?probe=47ac77d647) | Nov 08, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [a35aee6ec2](https://linux-hardware.org/?probe=a35aee6ec2) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [95b5d8b8ca](https://linux-hardware.org/?probe=95b5d8b8ca) | Nov 07, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [b49062def4](https://linux-hardware.org/?probe=b49062def4) | Nov 07, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [c2e7afc800](https://linux-hardware.org/?probe=c2e7afc800) | Nov 07, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [79475d514b](https://linux-hardware.org/?probe=79475d514b) | Nov 07, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [442c68f23d](https://linux-hardware.org/?probe=442c68f23d) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b414369067](https://linux-hardware.org/?probe=b414369067) | Nov 07, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [82bf0e80f0](https://linux-hardware.org/?probe=82bf0e80f0) | Nov 06, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [28af0c9803](https://linux-hardware.org/?probe=28af0c9803) | Nov 06, 2022 |
| Dell          | 0GDG8Y A02                  | Desktop     | [e61ccb96d0](https://linux-hardware.org/?probe=e61ccb96d0) | Nov 06, 2022 |
| Packard Be... | EasyNote LJ65               | Notebook    | [c75f470cf8](https://linux-hardware.org/?probe=c75f470cf8) | Nov 06, 2022 |
| Teclast       | F6 Pro                      | Notebook    | [bfba140f45](https://linux-hardware.org/?probe=bfba140f45) | Nov 06, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [0d7567fb3f](https://linux-hardware.org/?probe=0d7567fb3f) | Nov 06, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [c3a3d8d222](https://linux-hardware.org/?probe=c3a3d8d222) | Nov 06, 2022 |
| HP            | ProBook 6570b               | Notebook    | [1fec197471](https://linux-hardware.org/?probe=1fec197471) | Nov 06, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [006e91ea03](https://linux-hardware.org/?probe=006e91ea03) | Nov 06, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [3409bf9968](https://linux-hardware.org/?probe=3409bf9968) | Nov 06, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e351ee8496](https://linux-hardware.org/?probe=e351ee8496) | Nov 06, 2022 |
| MSI           | 880GMS-E41                  | Desktop     | [2f53fa13ed](https://linux-hardware.org/?probe=2f53fa13ed) | Nov 06, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [690e470acf](https://linux-hardware.org/?probe=690e470acf) | Nov 06, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3A... | Notebook    | [d53e6cef83](https://linux-hardware.org/?probe=d53e6cef83) | Nov 06, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [5db0a08b25](https://linux-hardware.org/?probe=5db0a08b25) | Nov 06, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c7a85b52dc](https://linux-hardware.org/?probe=c7a85b52dc) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [958f0c8551](https://linux-hardware.org/?probe=958f0c8551) | Nov 05, 2022 |
| ASRock        | X670E Taichi                | Desktop     | [c5227abc14](https://linux-hardware.org/?probe=c5227abc14) | Nov 05, 2022 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [f59d3d75ed](https://linux-hardware.org/?probe=f59d3d75ed) | Nov 05, 2022 |
| Dell          | Latitude 3390 2-in-1        | Convertible | [56d14a3b3f](https://linux-hardware.org/?probe=56d14a3b3f) | Nov 05, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [1c2a17391f](https://linux-hardware.org/?probe=1c2a17391f) | Nov 05, 2022 |
| Clevo         | Modified by dsanke          | Notebook    | [b0c6c10d48](https://linux-hardware.org/?probe=b0c6c10d48) | Nov 05, 2022 |
| HP            | 83E9                        | Desktop     | [837b4320c1](https://linux-hardware.org/?probe=837b4320c1) | Nov 05, 2022 |
| COLORFUL      | X15 XS 22                   | Notebook    | [38bc70c9b2](https://linux-hardware.org/?probe=38bc70c9b2) | Nov 04, 2022 |
| COLORFUL      | X15 XS 22                   | Notebook    | [342a90f101](https://linux-hardware.org/?probe=342a90f101) | Nov 04, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [e8364f4018](https://linux-hardware.org/?probe=e8364f4018) | Nov 04, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | Notebook    | [fbe5c4578c](https://linux-hardware.org/?probe=fbe5c4578c) | Nov 04, 2022 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [8598cf3c36](https://linux-hardware.org/?probe=8598cf3c36) | Nov 04, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [72b1a49ec9](https://linux-hardware.org/?probe=72b1a49ec9) | Nov 04, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [eeda582315](https://linux-hardware.org/?probe=eeda582315) | Nov 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [27bc8e172c](https://linux-hardware.org/?probe=27bc8e172c) | Nov 04, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [b46456d0c2](https://linux-hardware.org/?probe=b46456d0c2) | Nov 04, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [e57ec28998](https://linux-hardware.org/?probe=e57ec28998) | Nov 03, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [97d8c001ef](https://linux-hardware.org/?probe=97d8c001ef) | Nov 03, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [0847d7c7e6](https://linux-hardware.org/?probe=0847d7c7e6) | Nov 03, 2022 |
| Avell High... | B.ON                        | Notebook    | [f0ea745f7d](https://linux-hardware.org/?probe=f0ea745f7d) | Nov 03, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [fe997bad04](https://linux-hardware.org/?probe=fe997bad04) | Nov 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [e2f82d9c90](https://linux-hardware.org/?probe=e2f82d9c90) | Nov 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [ec7425c123](https://linux-hardware.org/?probe=ec7425c123) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [608c7f56e6](https://linux-hardware.org/?probe=608c7f56e6) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [209e99f964](https://linux-hardware.org/?probe=209e99f964) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [f12fc289fa](https://linux-hardware.org/?probe=f12fc289fa) | Nov 02, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [de1cd69b53](https://linux-hardware.org/?probe=de1cd69b53) | Nov 02, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [2c9714bc6b](https://linux-hardware.org/?probe=2c9714bc6b) | Nov 02, 2022 |
| ASUSTek       | H81T                        | Desktop     | [7598a634e6](https://linux-hardware.org/?probe=7598a634e6) | Nov 02, 2022 |
| GPD           | P3 MAX                      | Notebook    | [8b198da775](https://linux-hardware.org/?probe=8b198da775) | Nov 02, 2022 |
| GPD           | P3 MAX                      | Notebook    | [aea8f8bb50](https://linux-hardware.org/?probe=aea8f8bb50) | Nov 02, 2022 |
| Notebook      | P65xHP                      | Notebook    | [68d40fd2c7](https://linux-hardware.org/?probe=68d40fd2c7) | Nov 02, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [454939df34](https://linux-hardware.org/?probe=454939df34) | Nov 02, 2022 |
| ASUSTek       | N53Jg                       | Notebook    | [8e4782c668](https://linux-hardware.org/?probe=8e4782c668) | Nov 01, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [4c80b212c6](https://linux-hardware.org/?probe=4c80b212c6) | Nov 01, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [4e92800709](https://linux-hardware.org/?probe=4e92800709) | Nov 01, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7603f28400](https://linux-hardware.org/?probe=7603f28400) | Nov 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [321eae8d23](https://linux-hardware.org/?probe=321eae8d23) | Nov 01, 2022 |
| ASUSTek       | K54C                        | Notebook    | [dd4f63b1e4](https://linux-hardware.org/?probe=dd4f63b1e4) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [689b5a4022](https://linux-hardware.org/?probe=689b5a4022) | Nov 01, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [a5d58af861](https://linux-hardware.org/?probe=a5d58af861) | Oct 31, 2022 |
| Avell High... | B.ON                        | Notebook    | [1eb1bf21ed](https://linux-hardware.org/?probe=1eb1bf21ed) | Oct 31, 2022 |
| Lenovo        | Legion Y7000 2019 1050 8... | Notebook    | [3821dabcb9](https://linux-hardware.org/?probe=3821dabcb9) | Oct 31, 2022 |
| ASRock        | X670E Pro RS                | Desktop     | [5ebdf73c67](https://linux-hardware.org/?probe=5ebdf73c67) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [b1027d78bc](https://linux-hardware.org/?probe=b1027d78bc) | Oct 31, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [472a3f2707](https://linux-hardware.org/?probe=472a3f2707) | Oct 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [71de876615](https://linux-hardware.org/?probe=71de876615) | Oct 30, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0d67856d8a](https://linux-hardware.org/?probe=0d67856d8a) | Oct 30, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [9845791d39](https://linux-hardware.org/?probe=9845791d39) | Oct 30, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [224f9c8141](https://linux-hardware.org/?probe=224f9c8141) | Oct 30, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [c128f85cdc](https://linux-hardware.org/?probe=c128f85cdc) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [93d25dfb1f](https://linux-hardware.org/?probe=93d25dfb1f) | Oct 30, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [f8c58b7061](https://linux-hardware.org/?probe=f8c58b7061) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [8384c9e137](https://linux-hardware.org/?probe=8384c9e137) | Oct 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [1f7df5159e](https://linux-hardware.org/?probe=1f7df5159e) | Oct 30, 2022 |
| ASUSTek       | P6TD DELUXE                 | Desktop     | [faa61ea635](https://linux-hardware.org/?probe=faa61ea635) | Oct 30, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [70a0354dba](https://linux-hardware.org/?probe=70a0354dba) | Oct 30, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [0a7776630f](https://linux-hardware.org/?probe=0a7776630f) | Oct 30, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [c5955c7440](https://linux-hardware.org/?probe=c5955c7440) | Oct 29, 2022 |
| MSI           | Prestige 14 A10SC           | Notebook    | [1504398ef8](https://linux-hardware.org/?probe=1504398ef8) | Oct 29, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [957fc9af86](https://linux-hardware.org/?probe=957fc9af86) | Oct 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [1753d78397](https://linux-hardware.org/?probe=1753d78397) | Oct 29, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [610be75cca](https://linux-hardware.org/?probe=610be75cca) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4234f1fe02](https://linux-hardware.org/?probe=4234f1fe02) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6ab822b64c](https://linux-hardware.org/?probe=6ab822b64c) | Oct 29, 2022 |
| HP            | Pavilion dv5                | Notebook    | [8bd42e12c3](https://linux-hardware.org/?probe=8bd42e12c3) | Oct 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [be41a03a4d](https://linux-hardware.org/?probe=be41a03a4d) | Oct 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [893d006e2f](https://linux-hardware.org/?probe=893d006e2f) | Oct 29, 2022 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [0d76cc7e31](https://linux-hardware.org/?probe=0d76cc7e31) | Oct 29, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [59c02d4967](https://linux-hardware.org/?probe=59c02d4967) | Oct 28, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [0dde1fbb38](https://linux-hardware.org/?probe=0dde1fbb38) | Oct 28, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [8cf64e81cd](https://linux-hardware.org/?probe=8cf64e81cd) | Oct 28, 2022 |
| Avell High... | B.ON                        | Notebook    | [194a1eddc3](https://linux-hardware.org/?probe=194a1eddc3) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2ad60a938a](https://linux-hardware.org/?probe=2ad60a938a) | Oct 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [7d99f01f0e](https://linux-hardware.org/?probe=7d99f01f0e) | Oct 28, 2022 |
| Lenovo        | ThinkPad W540 20BHS0730D    | Notebook    | [f24dc12e06](https://linux-hardware.org/?probe=f24dc12e06) | Oct 28, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [ebdd62cbe3](https://linux-hardware.org/?probe=ebdd62cbe3) | Oct 28, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [060c8aadd1](https://linux-hardware.org/?probe=060c8aadd1) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [a03935aadd](https://linux-hardware.org/?probe=a03935aadd) | Oct 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [639503102e](https://linux-hardware.org/?probe=639503102e) | Oct 27, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [84acb8d19b](https://linux-hardware.org/?probe=84acb8d19b) | Oct 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [069ce9d405](https://linux-hardware.org/?probe=069ce9d405) | Oct 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [19859b5baf](https://linux-hardware.org/?probe=19859b5baf) | Oct 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [810ec3e083](https://linux-hardware.org/?probe=810ec3e083) | Oct 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0d31bc8f88](https://linux-hardware.org/?probe=0d31bc8f88) | Oct 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [abadd71c90](https://linux-hardware.org/?probe=abadd71c90) | Oct 27, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [6650af69ad](https://linux-hardware.org/?probe=6650af69ad) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [51877edd1e](https://linux-hardware.org/?probe=51877edd1e) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aca9e00b3d](https://linux-hardware.org/?probe=aca9e00b3d) | Oct 27, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5YM0... | Notebook    | [c348de09bf](https://linux-hardware.org/?probe=c348de09bf) | Oct 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [82fcc1ecc7](https://linux-hardware.org/?probe=82fcc1ecc7) | Oct 26, 2022 |
| Lenovo        | ThinkPad T480 20L50000IX    | Notebook    | [bcb1b11c50](https://linux-hardware.org/?probe=bcb1b11c50) | Oct 26, 2022 |
| Intel         | H55                         | Desktop     | [f634aefb9a](https://linux-hardware.org/?probe=f634aefb9a) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| MSI           | ZH77A-G43                   | Desktop     | [ff43c876e9](https://linux-hardware.org/?probe=ff43c876e9) | Oct 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [d4ebaa71a2](https://linux-hardware.org/?probe=d4ebaa71a2) | Oct 26, 2022 |
| Dell          | Precision 5570              | Notebook    | [67d7b55dab](https://linux-hardware.org/?probe=67d7b55dab) | Oct 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8a718e0ade](https://linux-hardware.org/?probe=8a718e0ade) | Oct 26, 2022 |
| Timi          | A7S                         | Notebook    | [004df6b9a1](https://linux-hardware.org/?probe=004df6b9a1) | Oct 26, 2022 |
| Dell          | Latitude E6440              | Notebook    | [307356784a](https://linux-hardware.org/?probe=307356784a) | Oct 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b05308c0f0](https://linux-hardware.org/?probe=b05308c0f0) | Oct 26, 2022 |
| Dell          | Latitude E5570              | Notebook    | [2d59f069b4](https://linux-hardware.org/?probe=2d59f069b4) | Oct 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [40447b0a52](https://linux-hardware.org/?probe=40447b0a52) | Oct 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [040b99188b](https://linux-hardware.org/?probe=040b99188b) | Oct 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7b20f93496](https://linux-hardware.org/?probe=7b20f93496) | Oct 26, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [042ffc026d](https://linux-hardware.org/?probe=042ffc026d) | Oct 26, 2022 |
| Timi          | A7S                         | Notebook    | [77a87009dd](https://linux-hardware.org/?probe=77a87009dd) | Oct 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [212ce8900d](https://linux-hardware.org/?probe=212ce8900d) | Oct 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [53e6b23ebf](https://linux-hardware.org/?probe=53e6b23ebf) | Oct 26, 2022 |
| Dell          | Latitude E6430              | Notebook    | [f196a9762f](https://linux-hardware.org/?probe=f196a9762f) | Oct 25, 2022 |
| Dell          | Latitude E6430              | Notebook    | [8062ec17fd](https://linux-hardware.org/?probe=8062ec17fd) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [2d7fa062e3](https://linux-hardware.org/?probe=2d7fa062e3) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [cca91f3fe8](https://linux-hardware.org/?probe=cca91f3fe8) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [8f34a9c24c](https://linux-hardware.org/?probe=8f34a9c24c) | Oct 25, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [dee13eac1d](https://linux-hardware.org/?probe=dee13eac1d) | Oct 25, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [1bc80461df](https://linux-hardware.org/?probe=1bc80461df) | Oct 25, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [1f939e0414](https://linux-hardware.org/?probe=1f939e0414) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [040714e135](https://linux-hardware.org/?probe=040714e135) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [72b73a6552](https://linux-hardware.org/?probe=72b73a6552) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [26415e4b74](https://linux-hardware.org/?probe=26415e4b74) | Oct 25, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [2a1b8eb060](https://linux-hardware.org/?probe=2a1b8eb060) | Oct 25, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [30c305f07c](https://linux-hardware.org/?probe=30c305f07c) | Oct 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3146a3d644](https://linux-hardware.org/?probe=3146a3d644) | Oct 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c55b37c393](https://linux-hardware.org/?probe=c55b37c393) | Oct 25, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [20278229cd](https://linux-hardware.org/?probe=20278229cd) | Oct 25, 2022 |
| Microsoft     | Surface Laptop 4            | Tablet      | [4bff3b131d](https://linux-hardware.org/?probe=4bff3b131d) | Oct 25, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4584821ae6](https://linux-hardware.org/?probe=4584821ae6) | Oct 25, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [169601c723](https://linux-hardware.org/?probe=169601c723) | Oct 25, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [efb9c3d448](https://linux-hardware.org/?probe=efb9c3d448) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a55a6ef774](https://linux-hardware.org/?probe=a55a6ef774) | Oct 25, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [52a4b91a1e](https://linux-hardware.org/?probe=52a4b91a1e) | Oct 25, 2022 |
| Lenovo        | B51-80 80LM                 | Notebook    | [aaed1997fd](https://linux-hardware.org/?probe=aaed1997fd) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6e98085fc5](https://linux-hardware.org/?probe=6e98085fc5) | Oct 25, 2022 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [e176b2ac7c](https://linux-hardware.org/?probe=e176b2ac7c) | Oct 25, 2022 |
| MSI           | Z170A GAMING M7             | Desktop     | [3326f67ecf](https://linux-hardware.org/?probe=3326f67ecf) | Oct 25, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [5a6d4ce6e7](https://linux-hardware.org/?probe=5a6d4ce6e7) | Oct 25, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [6818d9b7e2](https://linux-hardware.org/?probe=6818d9b7e2) | Oct 24, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [f569841512](https://linux-hardware.org/?probe=f569841512) | Oct 24, 2022 |
| Microsoft     | Surface Laptop 4            | Tablet      | [bdb6b876db](https://linux-hardware.org/?probe=bdb6b876db) | Oct 24, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [4948eb3b16](https://linux-hardware.org/?probe=4948eb3b16) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b4f3e516e3](https://linux-hardware.org/?probe=b4f3e516e3) | Oct 24, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [581fb21345](https://linux-hardware.org/?probe=581fb21345) | Oct 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [c76c6f0a0e](https://linux-hardware.org/?probe=c76c6f0a0e) | Oct 24, 2022 |
| Lenovo        | ThinkPad T480 20L5000AIX    | Notebook    | [43650773c9](https://linux-hardware.org/?probe=43650773c9) | Oct 24, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [d663683611](https://linux-hardware.org/?probe=d663683611) | Oct 24, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [baf284f131](https://linux-hardware.org/?probe=baf284f131) | Oct 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [417beae8e5](https://linux-hardware.org/?probe=417beae8e5) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [7733e4f8d5](https://linux-hardware.org/?probe=7733e4f8d5) | Oct 24, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [19ccd70ee8](https://linux-hardware.org/?probe=19ccd70ee8) | Oct 24, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [01c09a61ae](https://linux-hardware.org/?probe=01c09a61ae) | Oct 24, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [a8ab16a5c5](https://linux-hardware.org/?probe=a8ab16a5c5) | Oct 24, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [20dcade848](https://linux-hardware.org/?probe=20dcade848) | Oct 24, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [37a0403fc9](https://linux-hardware.org/?probe=37a0403fc9) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [d4c62f39e3](https://linux-hardware.org/?probe=d4c62f39e3) | Oct 24, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [b39d63f4f2](https://linux-hardware.org/?probe=b39d63f4f2) | Oct 24, 2022 |
| ASUSTek       | K54C                        | Notebook    | [acf64b4ced](https://linux-hardware.org/?probe=acf64b4ced) | Oct 24, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c9b4dc7a70](https://linux-hardware.org/?probe=c9b4dc7a70) | Oct 24, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b237965d1c](https://linux-hardware.org/?probe=b237965d1c) | Oct 24, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [25db15ea87](https://linux-hardware.org/?probe=25db15ea87) | Oct 24, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [d7e99b5869](https://linux-hardware.org/?probe=d7e99b5869) | Oct 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [c24c3f0836](https://linux-hardware.org/?probe=c24c3f0836) | Oct 23, 2022 |
| Dell          | Vostro 3491                 | Notebook    | [8809be3a93](https://linux-hardware.org/?probe=8809be3a93) | Oct 23, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6EH0... | Notebook    | [794fa1859f](https://linux-hardware.org/?probe=794fa1859f) | Oct 23, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [ce7a9a3171](https://linux-hardware.org/?probe=ce7a9a3171) | Oct 23, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [76c1dffd95](https://linux-hardware.org/?probe=76c1dffd95) | Oct 23, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [e2d21dcb54](https://linux-hardware.org/?probe=e2d21dcb54) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [e21d202e50](https://linux-hardware.org/?probe=e21d202e50) | Oct 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [514642847b](https://linux-hardware.org/?probe=514642847b) | Oct 22, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [edf45abefe](https://linux-hardware.org/?probe=edf45abefe) | Oct 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [a22e54462c](https://linux-hardware.org/?probe=a22e54462c) | Oct 21, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [07acd27a70](https://linux-hardware.org/?probe=07acd27a70) | Oct 21, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [837845f259](https://linux-hardware.org/?probe=837845f259) | Oct 20, 2022 |
| Dell          | Latitude E6500              | Notebook    | [d64ffd6f2e](https://linux-hardware.org/?probe=d64ffd6f2e) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [4c0b27f18e](https://linux-hardware.org/?probe=4c0b27f18e) | Oct 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [7cd6e349f0](https://linux-hardware.org/?probe=7cd6e349f0) | Oct 20, 2022 |
| Acer          | Predator PO3-630            | Desktop     | [aae61f30c7](https://linux-hardware.org/?probe=aae61f30c7) | Oct 20, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d042d922e5](https://linux-hardware.org/?probe=d042d922e5) | Oct 20, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [e8dc04cc0e](https://linux-hardware.org/?probe=e8dc04cc0e) | Oct 20, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [68b839f16e](https://linux-hardware.org/?probe=68b839f16e) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6be0c6ee5f](https://linux-hardware.org/?probe=6be0c6ee5f) | Oct 20, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [79ec522ef8](https://linux-hardware.org/?probe=79ec522ef8) | Oct 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8b459ac79b](https://linux-hardware.org/?probe=8b459ac79b) | Oct 20, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [e389da5691](https://linux-hardware.org/?probe=e389da5691) | Oct 20, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [ad9d78fb43](https://linux-hardware.org/?probe=ad9d78fb43) | Oct 19, 2022 |
| HP            | Pavilion dm4                | Notebook    | [d96f382cc2](https://linux-hardware.org/?probe=d96f382cc2) | Oct 19, 2022 |
| HP            | Pavilion dm4                | Notebook    | [171745a6e8](https://linux-hardware.org/?probe=171745a6e8) | Oct 19, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [4dac48ea7f](https://linux-hardware.org/?probe=4dac48ea7f) | Oct 19, 2022 |
| MOTILE        | M141                        | Notebook    | [a6da22306f](https://linux-hardware.org/?probe=a6da22306f) | Oct 19, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [0022d7c5ef](https://linux-hardware.org/?probe=0022d7c5ef) | Oct 19, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2f69a96661](https://linux-hardware.org/?probe=2f69a96661) | Oct 18, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [f2750b0a70](https://linux-hardware.org/?probe=f2750b0a70) | Oct 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8bc82af4e5](https://linux-hardware.org/?probe=8bc82af4e5) | Oct 18, 2022 |
| HP            | 8056                        | Desktop     | [37ed8a6b64](https://linux-hardware.org/?probe=37ed8a6b64) | Oct 18, 2022 |
| Gigabyte      | X99-UD7 WIFI-CF             | Desktop     | [9c484b6d22](https://linux-hardware.org/?probe=9c484b6d22) | Oct 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [437cb780cb](https://linux-hardware.org/?probe=437cb780cb) | Oct 18, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [549fe857a6](https://linux-hardware.org/?probe=549fe857a6) | Oct 18, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7891f1e18c](https://linux-hardware.org/?probe=7891f1e18c) | Oct 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [36c0e4dd87](https://linux-hardware.org/?probe=36c0e4dd87) | Oct 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8d774a5771](https://linux-hardware.org/?probe=8d774a5771) | Oct 18, 2022 |
| Avell High... | B.ON                        | Notebook    | [fc8b4d7534](https://linux-hardware.org/?probe=fc8b4d7534) | Oct 18, 2022 |
| Dell          | Vostro 7580                 | Notebook    | [69cc3a8c62](https://linux-hardware.org/?probe=69cc3a8c62) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d727afe327](https://linux-hardware.org/?probe=d727afe327) | Oct 17, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [cb651a5071](https://linux-hardware.org/?probe=cb651a5071) | Oct 17, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [9d4d455bb2](https://linux-hardware.org/?probe=9d4d455bb2) | Oct 17, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | Notebook    | [e3eba59f05](https://linux-hardware.org/?probe=e3eba59f05) | Oct 17, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [5fbae9cfcf](https://linux-hardware.org/?probe=5fbae9cfcf) | Oct 17, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [2f952f7898](https://linux-hardware.org/?probe=2f952f7898) | Oct 17, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [e39622cea9](https://linux-hardware.org/?probe=e39622cea9) | Oct 17, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [f7b9f3cab2](https://linux-hardware.org/?probe=f7b9f3cab2) | Oct 17, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e38add57d6](https://linux-hardware.org/?probe=e38add57d6) | Oct 17, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [fec2e273f7](https://linux-hardware.org/?probe=fec2e273f7) | Oct 17, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [4fe1c6d3e8](https://linux-hardware.org/?probe=4fe1c6d3e8) | Oct 17, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [cde154a026](https://linux-hardware.org/?probe=cde154a026) | Oct 16, 2022 |
| Intel         | D955XBK AAC96732-501        | Desktop     | [57a5e6cd9a](https://linux-hardware.org/?probe=57a5e6cd9a) | Oct 16, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [24c63dcc9e](https://linux-hardware.org/?probe=24c63dcc9e) | Oct 16, 2022 |
| Lenovo        | ThinkPad P50 20EQS6DV00     | Notebook    | [472b64041d](https://linux-hardware.org/?probe=472b64041d) | Oct 16, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [babb66e9c9](https://linux-hardware.org/?probe=babb66e9c9) | Oct 16, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [e71107e8cd](https://linux-hardware.org/?probe=e71107e8cd) | Oct 16, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [70494f7310](https://linux-hardware.org/?probe=70494f7310) | Oct 16, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4aa372d298](https://linux-hardware.org/?probe=4aa372d298) | Oct 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2495f40df9](https://linux-hardware.org/?probe=2495f40df9) | Oct 16, 2022 |
| Alienware     | m15 R6                      | Notebook    | [3cb0cb3e9d](https://linux-hardware.org/?probe=3cb0cb3e9d) | Oct 15, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ba8acdb280](https://linux-hardware.org/?probe=ba8acdb280) | Oct 15, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [7a8b3b953d](https://linux-hardware.org/?probe=7a8b3b953d) | Oct 15, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [d56a8a035a](https://linux-hardware.org/?probe=d56a8a035a) | Oct 15, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [6adb156840](https://linux-hardware.org/?probe=6adb156840) | Oct 15, 2022 |
| Dell          | Precision M4500             | Notebook    | [36048a8407](https://linux-hardware.org/?probe=36048a8407) | Oct 15, 2022 |
| Lenovo        | ThinkPad L420 78545EG       | Notebook    | [d2c975644c](https://linux-hardware.org/?probe=d2c975644c) | Oct 15, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [ade1f0f879](https://linux-hardware.org/?probe=ade1f0f879) | Oct 14, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [fbb018d1ef](https://linux-hardware.org/?probe=fbb018d1ef) | Oct 14, 2022 |
| Dell          | Precision M4800             | Notebook    | [aa9a1680fd](https://linux-hardware.org/?probe=aa9a1680fd) | Oct 14, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | Desktop     | [89060aa147](https://linux-hardware.org/?probe=89060aa147) | Oct 13, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [973f501233](https://linux-hardware.org/?probe=973f501233) | Oct 13, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [f80eb01da1](https://linux-hardware.org/?probe=f80eb01da1) | Oct 13, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [3d832d1780](https://linux-hardware.org/?probe=3d832d1780) | Oct 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [d3ade506f7](https://linux-hardware.org/?probe=d3ade506f7) | Oct 12, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [212c135857](https://linux-hardware.org/?probe=212c135857) | Oct 12, 2022 |
| ASUSTek       | P6T SE                      | Desktop     | [4ba4bc909d](https://linux-hardware.org/?probe=4ba4bc909d) | Oct 12, 2022 |
| Intel         | DH87RL AAG74240-400         | Desktop     | [82d2063927](https://linux-hardware.org/?probe=82d2063927) | Oct 12, 2022 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [8b554dcfe0](https://linux-hardware.org/?probe=8b554dcfe0) | Oct 12, 2022 |
| Dell          | Latitude E6420              | Notebook    | [0083bd14b8](https://linux-hardware.org/?probe=0083bd14b8) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [ec470df515](https://linux-hardware.org/?probe=ec470df515) | Oct 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [ac743b08fa](https://linux-hardware.org/?probe=ac743b08fa) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [9d281c015c](https://linux-hardware.org/?probe=9d281c015c) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [6c351b94ff](https://linux-hardware.org/?probe=6c351b94ff) | Oct 11, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [e464adc2d9](https://linux-hardware.org/?probe=e464adc2d9) | Oct 11, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [2bcf719742](https://linux-hardware.org/?probe=2bcf719742) | Oct 11, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [f44ca565c1](https://linux-hardware.org/?probe=f44ca565c1) | Oct 11, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [7d3c652547](https://linux-hardware.org/?probe=7d3c652547) | Oct 11, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | Notebook    | [7d923eff3f](https://linux-hardware.org/?probe=7d923eff3f) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2f346a2afb](https://linux-hardware.org/?probe=2f346a2afb) | Oct 11, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a2b8a7d46c](https://linux-hardware.org/?probe=a2b8a7d46c) | Oct 11, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [8e1e663189](https://linux-hardware.org/?probe=8e1e663189) | Oct 10, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d6e11d36a8](https://linux-hardware.org/?probe=d6e11d36a8) | Oct 10, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0bbe955a36](https://linux-hardware.org/?probe=0bbe955a36) | Oct 10, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [e60a581f5f](https://linux-hardware.org/?probe=e60a581f5f) | Oct 10, 2022 |
| Framework     | Laptop                      | Notebook    | [b5fe425089](https://linux-hardware.org/?probe=b5fe425089) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cde031e816](https://linux-hardware.org/?probe=cde031e816) | Oct 10, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [e7545a94b2](https://linux-hardware.org/?probe=e7545a94b2) | Oct 09, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [b938a96086](https://linux-hardware.org/?probe=b938a96086) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [62e134c294](https://linux-hardware.org/?probe=62e134c294) | Oct 09, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [17f73f4f28](https://linux-hardware.org/?probe=17f73f4f28) | Oct 09, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [f756c2bb92](https://linux-hardware.org/?probe=f756c2bb92) | Oct 09, 2022 |
| HP            | 2B4B                        | Desktop     | [b36dc773b0](https://linux-hardware.org/?probe=b36dc773b0) | Oct 09, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [be9437ed6b](https://linux-hardware.org/?probe=be9437ed6b) | Oct 08, 2022 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [696f55a7c4](https://linux-hardware.org/?probe=696f55a7c4) | Oct 07, 2022 |
| ASRock        | Z490 Steel Legend           | Desktop     | [ac371fb998](https://linux-hardware.org/?probe=ac371fb998) | Oct 07, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [92998a2fa1](https://linux-hardware.org/?probe=92998a2fa1) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [a431b20f04](https://linux-hardware.org/?probe=a431b20f04) | Oct 07, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f4a339aa76](https://linux-hardware.org/?probe=f4a339aa76) | Oct 07, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [db5dd33683](https://linux-hardware.org/?probe=db5dd33683) | Oct 07, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [f8d3a419e6](https://linux-hardware.org/?probe=f8d3a419e6) | Oct 07, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [87936d87c6](https://linux-hardware.org/?probe=87936d87c6) | Oct 06, 2022 |
| Fujitsu       | D3071-S1 S26361-D3071-S1    | Desktop     | [852194f41b](https://linux-hardware.org/?probe=852194f41b) | Oct 06, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [6d338f36ef](https://linux-hardware.org/?probe=6d338f36ef) | Oct 06, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [5ace2d0c1f](https://linux-hardware.org/?probe=5ace2d0c1f) | Oct 06, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b5cf733c51](https://linux-hardware.org/?probe=b5cf733c51) | Oct 06, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [abe6a3fde2](https://linux-hardware.org/?probe=abe6a3fde2) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [bb71e0e8c3](https://linux-hardware.org/?probe=bb71e0e8c3) | Oct 05, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [9395944d67](https://linux-hardware.org/?probe=9395944d67) | Oct 05, 2022 |
| MSI           | X470 GAMING PRO MAX         | Desktop     | [2e45442f11](https://linux-hardware.org/?probe=2e45442f11) | Oct 05, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [035a9bb7fa](https://linux-hardware.org/?probe=035a9bb7fa) | Oct 05, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [3338607f1a](https://linux-hardware.org/?probe=3338607f1a) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [74130061ff](https://linux-hardware.org/?probe=74130061ff) | Oct 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [72a5f6b03c](https://linux-hardware.org/?probe=72a5f6b03c) | Oct 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a51c98849b](https://linux-hardware.org/?probe=a51c98849b) | Oct 05, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [0edf82b5be](https://linux-hardware.org/?probe=0edf82b5be) | Oct 05, 2022 |
| Avell High... | B.ON                        | Notebook    | [2b629889c7](https://linux-hardware.org/?probe=2b629889c7) | Oct 05, 2022 |
| HP            | 2AA2                        | Desktop     | [e6bc6050b6](https://linux-hardware.org/?probe=e6bc6050b6) | Oct 05, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a430b0d43a](https://linux-hardware.org/?probe=a430b0d43a) | Oct 05, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6207d55486](https://linux-hardware.org/?probe=6207d55486) | Oct 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a4b830a39b](https://linux-hardware.org/?probe=a4b830a39b) | Oct 04, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [1bd18c9a15](https://linux-hardware.org/?probe=1bd18c9a15) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [16f99421ab](https://linux-hardware.org/?probe=16f99421ab) | Oct 04, 2022 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [59bc735625](https://linux-hardware.org/?probe=59bc735625) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [62b67bffae](https://linux-hardware.org/?probe=62b67bffae) | Oct 04, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [e07e70b822](https://linux-hardware.org/?probe=e07e70b822) | Oct 04, 2022 |
| HP            | 1850                        | Desktop     | [f111f19884](https://linux-hardware.org/?probe=f111f19884) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [790114327c](https://linux-hardware.org/?probe=790114327c) | Oct 04, 2022 |
| Gigabyte      | B360M D2V                   | Desktop     | [e0bf78b6b1](https://linux-hardware.org/?probe=e0bf78b6b1) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [85bcec60e7](https://linux-hardware.org/?probe=85bcec60e7) | Oct 04, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [339dcddca7](https://linux-hardware.org/?probe=339dcddca7) | Oct 03, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [6cdbcf8067](https://linux-hardware.org/?probe=6cdbcf8067) | Oct 03, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [00ecde42a1](https://linux-hardware.org/?probe=00ecde42a1) | Oct 02, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ff11bc4efb](https://linux-hardware.org/?probe=ff11bc4efb) | Oct 02, 2022 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [5c4c517651](https://linux-hardware.org/?probe=5c4c517651) | Oct 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9a2de7b77f](https://linux-hardware.org/?probe=9a2de7b77f) | Oct 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1043db8cf](https://linux-hardware.org/?probe=e1043db8cf) | Oct 02, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [26df10ca7d](https://linux-hardware.org/?probe=26df10ca7d) | Oct 02, 2022 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [014d8c23f8](https://linux-hardware.org/?probe=014d8c23f8) | Oct 01, 2022 |
| Google        | Blooglet                    | Notebook    | [0081fa7064](https://linux-hardware.org/?probe=0081fa7064) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0a022a22c6](https://linux-hardware.org/?probe=0a022a22c6) | Oct 01, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [6f96dc34e2](https://linux-hardware.org/?probe=6f96dc34e2) | Oct 01, 2022 |
| HP            | 655                         | Notebook    | [6b10f9eda8](https://linux-hardware.org/?probe=6b10f9eda8) | Oct 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [fca2e4409a](https://linux-hardware.org/?probe=fca2e4409a) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [82e89b9263](https://linux-hardware.org/?probe=82e89b9263) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [e64a9cf0e2](https://linux-hardware.org/?probe=e64a9cf0e2) | Oct 01, 2022 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [cffd9dadf8](https://linux-hardware.org/?probe=cffd9dadf8) | Oct 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4d1cbd14c2](https://linux-hardware.org/?probe=4d1cbd14c2) | Oct 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [00ded2a3ed](https://linux-hardware.org/?probe=00ded2a3ed) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bc6bcfe3f2](https://linux-hardware.org/?probe=bc6bcfe3f2) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [2d1e938e68](https://linux-hardware.org/?probe=2d1e938e68) | Oct 01, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [cfd0c22e29](https://linux-hardware.org/?probe=cfd0c22e29) | Sep 30, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [71ef5c4f0e](https://linux-hardware.org/?probe=71ef5c4f0e) | Sep 30, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [97e7d2d80f](https://linux-hardware.org/?probe=97e7d2d80f) | Sep 30, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [16f1ddb076](https://linux-hardware.org/?probe=16f1ddb076) | Sep 30, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1472407523](https://linux-hardware.org/?probe=1472407523) | Sep 30, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c4ccdf9992](https://linux-hardware.org/?probe=c4ccdf9992) | Sep 30, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [8ded1bb1f8](https://linux-hardware.org/?probe=8ded1bb1f8) | Sep 30, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [aa0eeeda6b](https://linux-hardware.org/?probe=aa0eeeda6b) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| TUXEDO        | Book_XA1510                 | Notebook    | [f39b64916d](https://linux-hardware.org/?probe=f39b64916d) | Sep 29, 2022 |
| HP            | 8464                        | Desktop     | [52d29e8721](https://linux-hardware.org/?probe=52d29e8721) | Sep 29, 2022 |
| Lenovo        | ThinkPad T430 23501K0       | Notebook    | [124afba97e](https://linux-hardware.org/?probe=124afba97e) | Sep 28, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [ec3962c685](https://linux-hardware.org/?probe=ec3962c685) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [b12e5d06a3](https://linux-hardware.org/?probe=b12e5d06a3) | Sep 28, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [10b723415e](https://linux-hardware.org/?probe=10b723415e) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [960c35d712](https://linux-hardware.org/?probe=960c35d712) | Sep 28, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [d4797ada2a](https://linux-hardware.org/?probe=d4797ada2a) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [4073c084df](https://linux-hardware.org/?probe=4073c084df) | Sep 28, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [03fff6add6](https://linux-hardware.org/?probe=03fff6add6) | Sep 27, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [3553d42d14](https://linux-hardware.org/?probe=3553d42d14) | Sep 27, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [04fbd64661](https://linux-hardware.org/?probe=04fbd64661) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [88f0d42935](https://linux-hardware.org/?probe=88f0d42935) | Sep 27, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d7dcd834e2](https://linux-hardware.org/?probe=d7dcd834e2) | Sep 27, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [56131c4db0](https://linux-hardware.org/?probe=56131c4db0) | Sep 27, 2022 |
| Timi          | TM1604                      | Notebook    | [2ee795db1a](https://linux-hardware.org/?probe=2ee795db1a) | Sep 27, 2022 |
| ASRock        | AB350 Gaming K4             | Desktop     | [184070d232](https://linux-hardware.org/?probe=184070d232) | Sep 26, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [89303afdb5](https://linux-hardware.org/?probe=89303afdb5) | Sep 26, 2022 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [e53b87c0fd](https://linux-hardware.org/?probe=e53b87c0fd) | Sep 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [95c0fd6047](https://linux-hardware.org/?probe=95c0fd6047) | Sep 26, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d9187e470e](https://linux-hardware.org/?probe=d9187e470e) | Sep 26, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dce9d30a10](https://linux-hardware.org/?probe=dce9d30a10) | Sep 26, 2022 |
| Dell          | G15 5511                    | Notebook    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [75087953dd](https://linux-hardware.org/?probe=75087953dd) | Sep 26, 2022 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [21d9eb0a71](https://linux-hardware.org/?probe=21d9eb0a71) | Sep 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [109d0ef34c](https://linux-hardware.org/?probe=109d0ef34c) | Sep 26, 2022 |
| MSI           | GS65 Stealth 9SE            | Notebook    | [0c8e0eb1f5](https://linux-hardware.org/?probe=0c8e0eb1f5) | Sep 26, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [6af4756d35](https://linux-hardware.org/?probe=6af4756d35) | Sep 25, 2022 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [382798365a](https://linux-hardware.org/?probe=382798365a) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0f4b7501b3](https://linux-hardware.org/?probe=0f4b7501b3) | Sep 25, 2022 |
| Intel         | NUC11ATBC4 M53051-302       | Mini pc     | [a398ca1184](https://linux-hardware.org/?probe=a398ca1184) | Sep 25, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [ba4b216db1](https://linux-hardware.org/?probe=ba4b216db1) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [c6c3ce5c04](https://linux-hardware.org/?probe=c6c3ce5c04) | Sep 25, 2022 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [e939330716](https://linux-hardware.org/?probe=e939330716) | Sep 25, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [18246c5a9e](https://linux-hardware.org/?probe=18246c5a9e) | Sep 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [1ccf6c5c41](https://linux-hardware.org/?probe=1ccf6c5c41) | Sep 25, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0047e2de0e](https://linux-hardware.org/?probe=0047e2de0e) | Sep 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [bdc8453efc](https://linux-hardware.org/?probe=bdc8453efc) | Sep 24, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [0a4522a059](https://linux-hardware.org/?probe=0a4522a059) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| Dell          | Precision 7560              | Notebook    | [8124a7a3eb](https://linux-hardware.org/?probe=8124a7a3eb) | Sep 24, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [7565f85860](https://linux-hardware.org/?probe=7565f85860) | Sep 24, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [efe1609ac0](https://linux-hardware.org/?probe=efe1609ac0) | Sep 24, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [6ccd3b916a](https://linux-hardware.org/?probe=6ccd3b916a) | Sep 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2b886fd64c](https://linux-hardware.org/?probe=2b886fd64c) | Sep 24, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [055cd5f884](https://linux-hardware.org/?probe=055cd5f884) | Sep 23, 2022 |
| Lenovo        | ThinkPad P52s 20LCS03L38    | Notebook    | [5d9c8cd268](https://linux-hardware.org/?probe=5d9c8cd268) | Sep 23, 2022 |
| Intel         | NUC8BEB J72688-309          | Mini pc     | [7d035aef45](https://linux-hardware.org/?probe=7d035aef45) | Sep 23, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [31f002c762](https://linux-hardware.org/?probe=31f002c762) | Sep 23, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [0121aac33a](https://linux-hardware.org/?probe=0121aac33a) | Sep 22, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [74dcd96704](https://linux-hardware.org/?probe=74dcd96704) | Sep 22, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [672d6f2fc8](https://linux-hardware.org/?probe=672d6f2fc8) | Sep 22, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [5657597c18](https://linux-hardware.org/?probe=5657597c18) | Sep 22, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [d79e046c6d](https://linux-hardware.org/?probe=d79e046c6d) | Sep 22, 2022 |
| Intel         | DN2800MT AAG23738-801       | Desktop     | [0019b51cff](https://linux-hardware.org/?probe=0019b51cff) | Sep 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [52bb32a60c](https://linux-hardware.org/?probe=52bb32a60c) | Sep 21, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| ASRock        | Z690 Pro RS                 | Desktop     | [787589762f](https://linux-hardware.org/?probe=787589762f) | Sep 21, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [628fd0d32d](https://linux-hardware.org/?probe=628fd0d32d) | Sep 21, 2022 |
| Intel         | H55                         | Desktop     | [6de435d14c](https://linux-hardware.org/?probe=6de435d14c) | Sep 20, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [88cbbeaee6](https://linux-hardware.org/?probe=88cbbeaee6) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [3aeb184ce4](https://linux-hardware.org/?probe=3aeb184ce4) | Sep 20, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [6fc004b792](https://linux-hardware.org/?probe=6fc004b792) | Sep 20, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [7bbcf621e1](https://linux-hardware.org/?probe=7bbcf621e1) | Sep 20, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [16d661b4e5](https://linux-hardware.org/?probe=16d661b4e5) | Sep 20, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [06d6be8b85](https://linux-hardware.org/?probe=06d6be8b85) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [b84e8d2682](https://linux-hardware.org/?probe=b84e8d2682) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [4779dfc2b0](https://linux-hardware.org/?probe=4779dfc2b0) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [37673aa4e2](https://linux-hardware.org/?probe=37673aa4e2) | Sep 20, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [38234e238c](https://linux-hardware.org/?probe=38234e238c) | Sep 20, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a1f237c86a](https://linux-hardware.org/?probe=a1f237c86a) | Sep 20, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [b07937de6a](https://linux-hardware.org/?probe=b07937de6a) | Sep 20, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [54d0318e27](https://linux-hardware.org/?probe=54d0318e27) | Sep 20, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [97426638ff](https://linux-hardware.org/?probe=97426638ff) | Sep 20, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [5367a8e71f](https://linux-hardware.org/?probe=5367a8e71f) | Sep 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [b6192d691a](https://linux-hardware.org/?probe=b6192d691a) | Sep 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [fed50b9211](https://linux-hardware.org/?probe=fed50b9211) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [9d26eb4243](https://linux-hardware.org/?probe=9d26eb4243) | Sep 19, 2022 |
| Huanan        | X99-F8 Gaming 2021          | Desktop     | [8a290737bd](https://linux-hardware.org/?probe=8a290737bd) | Sep 19, 2022 |
| Dell          | Latitude 7390               | Notebook    | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [8c4a94cb33](https://linux-hardware.org/?probe=8c4a94cb33) | Sep 19, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [42bc6e4e69](https://linux-hardware.org/?probe=42bc6e4e69) | Sep 19, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a479d9ef5f](https://linux-hardware.org/?probe=a479d9ef5f) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [e149495b74](https://linux-hardware.org/?probe=e149495b74) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f454a8f6a5](https://linux-hardware.org/?probe=f454a8f6a5) | Sep 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [57ab60faec](https://linux-hardware.org/?probe=57ab60faec) | Sep 19, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [3862ccf53f](https://linux-hardware.org/?probe=3862ccf53f) | Sep 19, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [f52b35d82d](https://linux-hardware.org/?probe=f52b35d82d) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [06f5febda2](https://linux-hardware.org/?probe=06f5febda2) | Sep 19, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [9d61a37458](https://linux-hardware.org/?probe=9d61a37458) | Sep 19, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [58d84150d6](https://linux-hardware.org/?probe=58d84150d6) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [cd1441d5a4](https://linux-hardware.org/?probe=cd1441d5a4) | Sep 18, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [6ba309be15](https://linux-hardware.org/?probe=6ba309be15) | Sep 18, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [aa3908e5fc](https://linux-hardware.org/?probe=aa3908e5fc) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [36a7673265](https://linux-hardware.org/?probe=36a7673265) | Sep 17, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [980e4272fb](https://linux-hardware.org/?probe=980e4272fb) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [abca74f17e](https://linux-hardware.org/?probe=abca74f17e) | Sep 17, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e6c4a47a86](https://linux-hardware.org/?probe=e6c4a47a86) | Sep 17, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [3ba3a4becf](https://linux-hardware.org/?probe=3ba3a4becf) | Sep 16, 2022 |
| Gateway       | SX2803                      | Desktop     | [870c8a3ff4](https://linux-hardware.org/?probe=870c8a3ff4) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fbe2b37462](https://linux-hardware.org/?probe=fbe2b37462) | Sep 16, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a26e1ad502](https://linux-hardware.org/?probe=a26e1ad502) | Sep 15, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [800fd51ccb](https://linux-hardware.org/?probe=800fd51ccb) | Sep 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6ff152e455](https://linux-hardware.org/?probe=6ff152e455) | Sep 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [9e0c10b8e3](https://linux-hardware.org/?probe=9e0c10b8e3) | Sep 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7f6ce1e4ea](https://linux-hardware.org/?probe=7f6ce1e4ea) | Sep 14, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [efde420a70](https://linux-hardware.org/?probe=efde420a70) | Sep 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [d0d43b3cc5](https://linux-hardware.org/?probe=d0d43b3cc5) | Sep 14, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [b7ed5c7f4a](https://linux-hardware.org/?probe=b7ed5c7f4a) | Sep 14, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [962c59a3ba](https://linux-hardware.org/?probe=962c59a3ba) | Sep 13, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| Acer          | Aspire X3990                | Desktop     | [64cddc5f85](https://linux-hardware.org/?probe=64cddc5f85) | Sep 13, 2022 |
| Samsung       | 950XED                      | Notebook    | [f8a15210f0](https://linux-hardware.org/?probe=f8a15210f0) | Sep 13, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [5d27ea49aa](https://linux-hardware.org/?probe=5d27ea49aa) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3c37d36ba8](https://linux-hardware.org/?probe=3c37d36ba8) | Sep 13, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1b8d9a04ae](https://linux-hardware.org/?probe=1b8d9a04ae) | Sep 13, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [5ae6fea41e](https://linux-hardware.org/?probe=5ae6fea41e) | Sep 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [93567a4d15](https://linux-hardware.org/?probe=93567a4d15) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7fb82d496f](https://linux-hardware.org/?probe=7fb82d496f) | Sep 12, 2022 |
| Toshiba       | Satellite U845W             | Notebook    | [030a371841](https://linux-hardware.org/?probe=030a371841) | Sep 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [321432c752](https://linux-hardware.org/?probe=321432c752) | Sep 12, 2022 |
| HP            | 3047h                       | Desktop     | [097b5b2f29](https://linux-hardware.org/?probe=097b5b2f29) | Sep 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [8b44500d70](https://linux-hardware.org/?probe=8b44500d70) | Sep 12, 2022 |
| Chuwi         | UBook                       | Tablet      | [89a54f0af1](https://linux-hardware.org/?probe=89a54f0af1) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [410b905321](https://linux-hardware.org/?probe=410b905321) | Sep 11, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [c55fd8d477](https://linux-hardware.org/?probe=c55fd8d477) | Sep 11, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [c59ebfd9e8](https://linux-hardware.org/?probe=c59ebfd9e8) | Sep 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [46c51b7097](https://linux-hardware.org/?probe=46c51b7097) | Sep 11, 2022 |
| Dell          | Latitude 7424 Rugged Ext... | Notebook    | [0e5e98a9e2](https://linux-hardware.org/?probe=0e5e98a9e2) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d2c057ed6e](https://linux-hardware.org/?probe=d2c057ed6e) | Sep 11, 2022 |
| Lenovo        | Yoga 720-15IKB              | Convertible | [078c865d26](https://linux-hardware.org/?probe=078c865d26) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | Notebook    | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ee06685499](https://linux-hardware.org/?probe=ee06685499) | Sep 11, 2022 |
| Samsung       | 750XED                      | Notebook    | [ea68f0910d](https://linux-hardware.org/?probe=ea68f0910d) | Sep 10, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [be7516b088](https://linux-hardware.org/?probe=be7516b088) | Sep 10, 2022 |
| Samsung       | 750XED                      | Notebook    | [475088329e](https://linux-hardware.org/?probe=475088329e) | Sep 10, 2022 |
| Framework     | Laptop                      | Notebook    | [b0b7801b11](https://linux-hardware.org/?probe=b0b7801b11) | Sep 10, 2022 |
| Lenovo        | ThinkPad X230 23252QG       | Notebook    | [4146ff55f9](https://linux-hardware.org/?probe=4146ff55f9) | Sep 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [3c214d75b2](https://linux-hardware.org/?probe=3c214d75b2) | Sep 10, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e8c2730c9](https://linux-hardware.org/?probe=1e8c2730c9) | Sep 10, 2022 |
| Dell          | 0VNM11 A00                  | Desktop     | [9ae0ae5ac4](https://linux-hardware.org/?probe=9ae0ae5ac4) | Sep 10, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [80626826a3](https://linux-hardware.org/?probe=80626826a3) | Sep 10, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [4911a898bd](https://linux-hardware.org/?probe=4911a898bd) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d9c6274ead](https://linux-hardware.org/?probe=d9c6274ead) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f5c538e2c7](https://linux-hardware.org/?probe=f5c538e2c7) | Sep 09, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [c61b5df29b](https://linux-hardware.org/?probe=c61b5df29b) | Sep 09, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [8e84bc9dac](https://linux-hardware.org/?probe=8e84bc9dac) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [43311add57](https://linux-hardware.org/?probe=43311add57) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c13cd2c2ac](https://linux-hardware.org/?probe=c13cd2c2ac) | Sep 09, 2022 |
| Medion        | S4216                       | Notebook    | [1f1e6b24bf](https://linux-hardware.org/?probe=1f1e6b24bf) | Sep 08, 2022 |
| Dell          | Latitude 7350               | Notebook    | [4a30d9431e](https://linux-hardware.org/?probe=4a30d9431e) | Sep 08, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [b2cd3df6bc](https://linux-hardware.org/?probe=b2cd3df6bc) | Sep 08, 2022 |
| Google        | Rabbid                      | Notebook    | [636b8205ae](https://linux-hardware.org/?probe=636b8205ae) | Sep 08, 2022 |
| Google        | Rabbid                      | Notebook    | [f33074ee09](https://linux-hardware.org/?probe=f33074ee09) | Sep 08, 2022 |
| LG Electro... | 17Z90P-G.AA86D              | Notebook    | [1f304e9792](https://linux-hardware.org/?probe=1f304e9792) | Sep 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [a5fdc97073](https://linux-hardware.org/?probe=a5fdc97073) | Sep 07, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [c89a7d5488](https://linux-hardware.org/?probe=c89a7d5488) | Sep 07, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [52f4b6e022](https://linux-hardware.org/?probe=52f4b6e022) | Sep 07, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [b5270dfd32](https://linux-hardware.org/?probe=b5270dfd32) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e88363a341](https://linux-hardware.org/?probe=e88363a341) | Sep 07, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [c8a237d75e](https://linux-hardware.org/?probe=c8a237d75e) | Sep 07, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [ec22409311](https://linux-hardware.org/?probe=ec22409311) | Sep 07, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [803410686e](https://linux-hardware.org/?probe=803410686e) | Sep 07, 2022 |
| Fujitsu       | LIFEBOOK U9311X             | Convertible | [934e3e7ff1](https://linux-hardware.org/?probe=934e3e7ff1) | Sep 06, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [893afb133c](https://linux-hardware.org/?probe=893afb133c) | Sep 06, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [bddf00d17f](https://linux-hardware.org/?probe=bddf00d17f) | Sep 06, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5733156bf5](https://linux-hardware.org/?probe=5733156bf5) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [a4f8e52425](https://linux-hardware.org/?probe=a4f8e52425) | Sep 06, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d88badf739](https://linux-hardware.org/?probe=d88badf739) | Sep 06, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [3ce6c0f44c](https://linux-hardware.org/?probe=3ce6c0f44c) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [0daca2662d](https://linux-hardware.org/?probe=0daca2662d) | Sep 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [acb5c353ed](https://linux-hardware.org/?probe=acb5c353ed) | Sep 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [d55d359a3e](https://linux-hardware.org/?probe=d55d359a3e) | Sep 05, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e37ba07a92](https://linux-hardware.org/?probe=e37ba07a92) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [92d04feeca](https://linux-hardware.org/?probe=92d04feeca) | Sep 05, 2022 |
| Dell          | Precision 3571              | Notebook    | [d9939fbfd4](https://linux-hardware.org/?probe=d9939fbfd4) | Sep 05, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e12af15c84](https://linux-hardware.org/?probe=e12af15c84) | Sep 05, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [43f7cbff06](https://linux-hardware.org/?probe=43f7cbff06) | Sep 05, 2022 |
| Google        | Coral                       | Notebook    | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [aa90cb0d30](https://linux-hardware.org/?probe=aa90cb0d30) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [bf4936f3bc](https://linux-hardware.org/?probe=bf4936f3bc) | Sep 04, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [a746f6faa6](https://linux-hardware.org/?probe=a746f6faa6) | Sep 04, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [c9d51bfae8](https://linux-hardware.org/?probe=c9d51bfae8) | Sep 04, 2022 |
| Samsung       | 950QDB                      | Convertible | [ec7cdfdff7](https://linux-hardware.org/?probe=ec7cdfdff7) | Sep 04, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [3064d08dc1](https://linux-hardware.org/?probe=3064d08dc1) | Sep 03, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [87a6f9162a](https://linux-hardware.org/?probe=87a6f9162a) | Sep 03, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [1394aca8b2](https://linux-hardware.org/?probe=1394aca8b2) | Sep 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [6de688d21a](https://linux-hardware.org/?probe=6de688d21a) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [e30f86bc30](https://linux-hardware.org/?probe=e30f86bc30) | Sep 03, 2022 |
| Dell          | Latitude 7350               | Notebook    | [f52406cbf2](https://linux-hardware.org/?probe=f52406cbf2) | Sep 03, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [b313706909](https://linux-hardware.org/?probe=b313706909) | Sep 03, 2022 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [0151fa47ef](https://linux-hardware.org/?probe=0151fa47ef) | Sep 03, 2022 |
| TUXEDO        | Book_XA1510                 | Notebook    | [e379f966da](https://linux-hardware.org/?probe=e379f966da) | Sep 03, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [0f5aab705f](https://linux-hardware.org/?probe=0f5aab705f) | Sep 03, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [7ec410bfe6](https://linux-hardware.org/?probe=7ec410bfe6) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [08cfa37b81](https://linux-hardware.org/?probe=08cfa37b81) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6b62abaaaf](https://linux-hardware.org/?probe=6b62abaaaf) | Sep 03, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [9c22b70a4f](https://linux-hardware.org/?probe=9c22b70a4f) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ec466abbf7](https://linux-hardware.org/?probe=ec466abbf7) | Sep 03, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [5d6b0d60df](https://linux-hardware.org/?probe=5d6b0d60df) | Sep 03, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [65bfdaa6ea](https://linux-hardware.org/?probe=65bfdaa6ea) | Sep 03, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [4d9025cf5c](https://linux-hardware.org/?probe=4d9025cf5c) | Sep 03, 2022 |
| HP            | 15                          | Notebook    | [48493c0282](https://linux-hardware.org/?probe=48493c0282) | Sep 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [2199481d0a](https://linux-hardware.org/?probe=2199481d0a) | Sep 03, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [4489539bae](https://linux-hardware.org/?probe=4489539bae) | Sep 03, 2022 |
| Lenovo        | ThinkPad L390 20NSS11E00    | Notebook    | [d5dbbd658f](https://linux-hardware.org/?probe=d5dbbd658f) | Sep 03, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [e7e5ddf474](https://linux-hardware.org/?probe=e7e5ddf474) | Sep 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [7c04c344cb](https://linux-hardware.org/?probe=7c04c344cb) | Sep 02, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7829cfc920](https://linux-hardware.org/?probe=7829cfc920) | Sep 02, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [b06eacf424](https://linux-hardware.org/?probe=b06eacf424) | Sep 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [cd935b0146](https://linux-hardware.org/?probe=cd935b0146) | Sep 02, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| MSI           | X99A GAMING 7               | Desktop     | [347f4d8534](https://linux-hardware.org/?probe=347f4d8534) | Sep 02, 2022 |
| Gigabyte      | H310N x.x                   | Desktop     | [c6c8617f48](https://linux-hardware.org/?probe=c6c8617f48) | Sep 02, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [f1cfdb5e32](https://linux-hardware.org/?probe=f1cfdb5e32) | Sep 02, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [fadbc676b4](https://linux-hardware.org/?probe=fadbc676b4) | Sep 02, 2022 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [d510db88c4](https://linux-hardware.org/?probe=d510db88c4) | Sep 02, 2022 |
| Toshiba       | Satellite C55D-B            | Notebook    | [4f9267de27](https://linux-hardware.org/?probe=4f9267de27) | Sep 02, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [6456a1b04f](https://linux-hardware.org/?probe=6456a1b04f) | Sep 02, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [1918459ea4](https://linux-hardware.org/?probe=1918459ea4) | Sep 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cfdc88587a](https://linux-hardware.org/?probe=cfdc88587a) | Sep 02, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b0750b0e0a](https://linux-hardware.org/?probe=b0750b0e0a) | Sep 02, 2022 |
| HP            | EliteBook x360 830 G6       | Convertible | [751aeabd5d](https://linux-hardware.org/?probe=751aeabd5d) | Sep 01, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [f88772c4dc](https://linux-hardware.org/?probe=f88772c4dc) | Sep 01, 2022 |
| Purism        | Librem 14                   | Notebook    | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8fc60cb459](https://linux-hardware.org/?probe=8fc60cb459) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [c9841acd77](https://linux-hardware.org/?probe=c9841acd77) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8e1734f31a](https://linux-hardware.org/?probe=8e1734f31a) | Sep 01, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [7ff88a93c2](https://linux-hardware.org/?probe=7ff88a93c2) | Sep 01, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [bbe5fe0eac](https://linux-hardware.org/?probe=bbe5fe0eac) | Aug 31, 2022 |
| HP            | 18E5                        | Desktop     | [e7c5ab6cc4](https://linux-hardware.org/?probe=e7c5ab6cc4) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | Notebook    | [121c8e110b](https://linux-hardware.org/?probe=121c8e110b) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | Notebook    | [6ec2bd9539](https://linux-hardware.org/?probe=6ec2bd9539) | Aug 31, 2022 |
| Notebook      | NH5xAx                      | Notebook    | [e8487cd15f](https://linux-hardware.org/?probe=e8487cd15f) | Aug 31, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [ef34b3c3aa](https://linux-hardware.org/?probe=ef34b3c3aa) | Aug 31, 2022 |
| 16512-2316... | MPG X570 GAMING EDGE WIF... | Desktop     | [d523a89d9b](https://linux-hardware.org/?probe=d523a89d9b) | Aug 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3d7c0ee13d](https://linux-hardware.org/?probe=3d7c0ee13d) | Aug 30, 2022 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [dcdfb21686](https://linux-hardware.org/?probe=dcdfb21686) | Aug 30, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [393cb25da2](https://linux-hardware.org/?probe=393cb25da2) | Aug 30, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [c5a0ce2143](https://linux-hardware.org/?probe=c5a0ce2143) | Aug 30, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [2e6d572c33](https://linux-hardware.org/?probe=2e6d572c33) | Aug 30, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [d972083fa3](https://linux-hardware.org/?probe=d972083fa3) | Aug 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [4ea311ca8e](https://linux-hardware.org/?probe=4ea311ca8e) | Aug 30, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [1a8ff186c7](https://linux-hardware.org/?probe=1a8ff186c7) | Aug 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [4b37519faf](https://linux-hardware.org/?probe=4b37519faf) | Aug 29, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1ff074d641](https://linux-hardware.org/?probe=1ff074d641) | Aug 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c44a50e117](https://linux-hardware.org/?probe=c44a50e117) | Aug 29, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [c107217cf8](https://linux-hardware.org/?probe=c107217cf8) | Aug 28, 2022 |
| MSI           | B75A-G41                    | Desktop     | [1d0e275f3e](https://linux-hardware.org/?probe=1d0e275f3e) | Aug 28, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [9a83e7ee58](https://linux-hardware.org/?probe=9a83e7ee58) | Aug 28, 2022 |
| Framework     | Laptop                      | Notebook    | [71c896cd39](https://linux-hardware.org/?probe=71c896cd39) | Aug 28, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [b40621d5f6](https://linux-hardware.org/?probe=b40621d5f6) | Aug 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | Notebook    | [1d29556c76](https://linux-hardware.org/?probe=1d29556c76) | Aug 28, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [25e4d6c064](https://linux-hardware.org/?probe=25e4d6c064) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [d056fbc982](https://linux-hardware.org/?probe=d056fbc982) | Aug 28, 2022 |
| BBEN          | G16                         | Notebook    | [6b0b170e1c](https://linux-hardware.org/?probe=6b0b170e1c) | Aug 28, 2022 |
| BBEN          | G16                         | Notebook    | [66fc9bd46b](https://linux-hardware.org/?probe=66fc9bd46b) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [aa84c700c6](https://linux-hardware.org/?probe=aa84c700c6) | Aug 28, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [638f08fc43](https://linux-hardware.org/?probe=638f08fc43) | Aug 27, 2022 |
| Dell          | Latitude 3150               | Notebook    | [09f1514148](https://linux-hardware.org/?probe=09f1514148) | Aug 27, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [8ccf243309](https://linux-hardware.org/?probe=8ccf243309) | Aug 27, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [24164369fd](https://linux-hardware.org/?probe=24164369fd) | Aug 27, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8841ba5f53](https://linux-hardware.org/?probe=8841ba5f53) | Aug 27, 2022 |
| HP            | 8054                        | Desktop     | [af4f950786](https://linux-hardware.org/?probe=af4f950786) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [37bdc91d97](https://linux-hardware.org/?probe=37bdc91d97) | Aug 26, 2022 |
| Dell          | Latitude 7350               | Notebook    | [c784fd2743](https://linux-hardware.org/?probe=c784fd2743) | Aug 26, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [c0b89ea222](https://linux-hardware.org/?probe=c0b89ea222) | Aug 26, 2022 |
| Lenovo        | ThinkPad T430 2344BMU       | Notebook    | [c164d20c15](https://linux-hardware.org/?probe=c164d20c15) | Aug 26, 2022 |
| Dell          | Latitude 7424 Rugged Ext... | Notebook    | [9770e301cd](https://linux-hardware.org/?probe=9770e301cd) | Aug 26, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [5c8244526c](https://linux-hardware.org/?probe=5c8244526c) | Aug 25, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [da0b51aa63](https://linux-hardware.org/?probe=da0b51aa63) | Aug 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d8286d5ca0](https://linux-hardware.org/?probe=d8286d5ca0) | Aug 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b7263cf041](https://linux-hardware.org/?probe=b7263cf041) | Aug 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [13cd1e5eed](https://linux-hardware.org/?probe=13cd1e5eed) | Aug 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [866cc080e0](https://linux-hardware.org/?probe=866cc080e0) | Aug 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [fcfd89bb32](https://linux-hardware.org/?probe=fcfd89bb32) | Aug 25, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [c579b49e4c](https://linux-hardware.org/?probe=c579b49e4c) | Aug 25, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [156da35e98](https://linux-hardware.org/?probe=156da35e98) | Aug 24, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b8af477a84](https://linux-hardware.org/?probe=b8af477a84) | Aug 24, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [e51675ce88](https://linux-hardware.org/?probe=e51675ce88) | Aug 24, 2022 |
| ASRock        | AD2550-ITX                  | Desktop     | [79e491790d](https://linux-hardware.org/?probe=79e491790d) | Aug 24, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [7ce95dab0a](https://linux-hardware.org/?probe=7ce95dab0a) | Aug 24, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [e3d3a359b5](https://linux-hardware.org/?probe=e3d3a359b5) | Aug 24, 2022 |
| MSI           | MEG Z490 GODLIKE            | Desktop     | [eb92b93947](https://linux-hardware.org/?probe=eb92b93947) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Samsung       | 730QAA                      | Convertible | [be9b44a8c5](https://linux-hardware.org/?probe=be9b44a8c5) | Aug 24, 2022 |
| Dell          | XPS L421X                   | Notebook    | [227df9dc9e](https://linux-hardware.org/?probe=227df9dc9e) | Aug 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8af1d0e421](https://linux-hardware.org/?probe=8af1d0e421) | Aug 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [98c26372c2](https://linux-hardware.org/?probe=98c26372c2) | Aug 23, 2022 |
| LG Electro... | S430-G.BC33P1               | Notebook    | [d0b4cf47fe](https://linux-hardware.org/?probe=d0b4cf47fe) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [1d0c242f30](https://linux-hardware.org/?probe=1d0c242f30) | Aug 23, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| MSI           | GS73VR 6RF                  | Notebook    | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [f6f358dde8](https://linux-hardware.org/?probe=f6f358dde8) | Aug 23, 2022 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [d7dee32799](https://linux-hardware.org/?probe=d7dee32799) | Aug 23, 2022 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [7004b23b33](https://linux-hardware.org/?probe=7004b23b33) | Aug 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [46c6096b6e](https://linux-hardware.org/?probe=46c6096b6e) | Aug 23, 2022 |
| ASRock        | Z170M Pro4S                 | Desktop     | [0bfb94df6e](https://linux-hardware.org/?probe=0bfb94df6e) | Aug 23, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [93f28535f8](https://linux-hardware.org/?probe=93f28535f8) | Aug 23, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [6cc47c9a0d](https://linux-hardware.org/?probe=6cc47c9a0d) | Aug 23, 2022 |
| Acer          | Predator G3-710             | Desktop     | [7a58c9348e](https://linux-hardware.org/?probe=7a58c9348e) | Aug 22, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [e3169f9b1c](https://linux-hardware.org/?probe=e3169f9b1c) | Aug 22, 2022 |
| Dell          | Latitude 7390               | Notebook    | [0d626db6e1](https://linux-hardware.org/?probe=0d626db6e1) | Aug 22, 2022 |
| ASRock        | Z75 Pro3                    | Desktop     | [4fbe3d2710](https://linux-hardware.org/?probe=4fbe3d2710) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [d08e00053f](https://linux-hardware.org/?probe=d08e00053f) | Aug 22, 2022 |
| Dell          | 052RF2 A01                  | Server      | [82830908ab](https://linux-hardware.org/?probe=82830908ab) | Aug 22, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [8898d24c48](https://linux-hardware.org/?probe=8898d24c48) | Aug 22, 2022 |
| Toshiba       | Satellite P55t-C            | Notebook    | [70560700a6](https://linux-hardware.org/?probe=70560700a6) | Aug 22, 2022 |
| ASUSTek       | X555UB                      | Notebook    | [a1db92c63c](https://linux-hardware.org/?probe=a1db92c63c) | Aug 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [cb533d9c12](https://linux-hardware.org/?probe=cb533d9c12) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [ada7663387](https://linux-hardware.org/?probe=ada7663387) | Aug 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [14cade3bfe](https://linux-hardware.org/?probe=14cade3bfe) | Aug 21, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [750425c2c2](https://linux-hardware.org/?probe=750425c2c2) | Aug 21, 2022 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [f01fb4784c](https://linux-hardware.org/?probe=f01fb4784c) | Aug 21, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [4875c1533b](https://linux-hardware.org/?probe=4875c1533b) | Aug 21, 2022 |
| BBEN          | G16                         | Notebook    | [f9768aedb9](https://linux-hardware.org/?probe=f9768aedb9) | Aug 21, 2022 |
| BBEN          | G16                         | Notebook    | [d491f08ce0](https://linux-hardware.org/?probe=d491f08ce0) | Aug 21, 2022 |
| HP            | Pavilion g4                 | Notebook    | [f8c2fc628e](https://linux-hardware.org/?probe=f8c2fc628e) | Aug 21, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [8b1a8497c7](https://linux-hardware.org/?probe=8b1a8497c7) | Aug 21, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [e31fb3f3cf](https://linux-hardware.org/?probe=e31fb3f3cf) | Aug 21, 2022 |
| HP            | ENVY 15                     | Notebook    | [5d984dedf6](https://linux-hardware.org/?probe=5d984dedf6) | Aug 20, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [9a8166de9b](https://linux-hardware.org/?probe=9a8166de9b) | Aug 20, 2022 |
| realme        | RMNBXXXX                    | Notebook    | [d98be8821f](https://linux-hardware.org/?probe=d98be8821f) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [4f711bf806](https://linux-hardware.org/?probe=4f711bf806) | Aug 20, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [c1b5d9ffc1](https://linux-hardware.org/?probe=c1b5d9ffc1) | Aug 19, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [001ac5c374](https://linux-hardware.org/?probe=001ac5c374) | Aug 19, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [c6bb19402d](https://linux-hardware.org/?probe=c6bb19402d) | Aug 19, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [e32743d60f](https://linux-hardware.org/?probe=e32743d60f) | Aug 19, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [8af519565f](https://linux-hardware.org/?probe=8af519565f) | Aug 18, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Framework     | Laptop                      | Notebook    | [a8988f1665](https://linux-hardware.org/?probe=a8988f1665) | Aug 18, 2022 |
| Dell          | Latitude 7390               | Notebook    | [d726450b55](https://linux-hardware.org/?probe=d726450b55) | Aug 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [83d7ac44e3](https://linux-hardware.org/?probe=83d7ac44e3) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [16b9aa5d1b](https://linux-hardware.org/?probe=16b9aa5d1b) | Aug 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0dbc32a26d](https://linux-hardware.org/?probe=0dbc32a26d) | Aug 17, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6a95ac6709](https://linux-hardware.org/?probe=6a95ac6709) | Aug 17, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [abad46b854](https://linux-hardware.org/?probe=abad46b854) | Aug 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| TPVAOC        | AA183M                      | Notebook    | [089472ea13](https://linux-hardware.org/?probe=089472ea13) | Aug 16, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [3e3ab3842f](https://linux-hardware.org/?probe=3e3ab3842f) | Aug 16, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [1d2b1aa4bf](https://linux-hardware.org/?probe=1d2b1aa4bf) | Aug 16, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [8341abd9e2](https://linux-hardware.org/?probe=8341abd9e2) | Aug 16, 2022 |
| Lenovo        | Yoga 720-15IKB              | Convertible | [33bd89a7e0](https://linux-hardware.org/?probe=33bd89a7e0) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [eb37729065](https://linux-hardware.org/?probe=eb37729065) | Aug 16, 2022 |
| HP            | ENVY m7                     | Notebook    | [9142b4fff0](https://linux-hardware.org/?probe=9142b4fff0) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | Notebook    | [6132aea83b](https://linux-hardware.org/?probe=6132aea83b) | Aug 16, 2022 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | Notebook    | [0a48289c39](https://linux-hardware.org/?probe=0a48289c39) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [3799febe71](https://linux-hardware.org/?probe=3799febe71) | Aug 16, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [35cd057234](https://linux-hardware.org/?probe=35cd057234) | Aug 16, 2022 |
| Dell          | 0H21J3 A04                  | Server      | [14f7add408](https://linux-hardware.org/?probe=14f7add408) | Aug 16, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [f223d64d8f](https://linux-hardware.org/?probe=f223d64d8f) | Aug 15, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [855a5955c8](https://linux-hardware.org/?probe=855a5955c8) | Aug 15, 2022 |
| Acer          | Celadon-RN                  | Notebook    | [043b0c9fd7](https://linux-hardware.org/?probe=043b0c9fd7) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | Notebook    | [94309eee94](https://linux-hardware.org/?probe=94309eee94) | Aug 15, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [4e05ac232c](https://linux-hardware.org/?probe=4e05ac232c) | Aug 15, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [08bf3d620e](https://linux-hardware.org/?probe=08bf3d620e) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | Notebook    | [3e084bba8b](https://linux-hardware.org/?probe=3e084bba8b) | Aug 15, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [1e198f7c54](https://linux-hardware.org/?probe=1e198f7c54) | Aug 15, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [1db8ed0da4](https://linux-hardware.org/?probe=1db8ed0da4) | Aug 14, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [105367d5d6](https://linux-hardware.org/?probe=105367d5d6) | Aug 14, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [7817924a07](https://linux-hardware.org/?probe=7817924a07) | Aug 14, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [286fd1791a](https://linux-hardware.org/?probe=286fd1791a) | Aug 14, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [d0831907e8](https://linux-hardware.org/?probe=d0831907e8) | Aug 14, 2022 |
| Dell          | 0978PJ A03                  | Server      | [382f999542](https://linux-hardware.org/?probe=382f999542) | Aug 14, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4e7f1dc861](https://linux-hardware.org/?probe=4e7f1dc861) | Aug 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97f75c2be0](https://linux-hardware.org/?probe=97f75c2be0) | Aug 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1C00... | Notebook    | [dbbae31450](https://linux-hardware.org/?probe=dbbae31450) | Aug 13, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [ee2f627cb6](https://linux-hardware.org/?probe=ee2f627cb6) | Aug 13, 2022 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Convertible | [c926de11d3](https://linux-hardware.org/?probe=c926de11d3) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [c001e6e62b](https://linux-hardware.org/?probe=c001e6e62b) | Aug 12, 2022 |
| ASUSTek       | GL552VX                     | Notebook    | [16c1976ac6](https://linux-hardware.org/?probe=16c1976ac6) | Aug 12, 2022 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [0045f412a9](https://linux-hardware.org/?probe=0045f412a9) | Aug 12, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [c63936c0ef](https://linux-hardware.org/?probe=c63936c0ef) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [e3be6b79c1](https://linux-hardware.org/?probe=e3be6b79c1) | Aug 12, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [fad6aace6a](https://linux-hardware.org/?probe=fad6aace6a) | Aug 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [69843536ef](https://linux-hardware.org/?probe=69843536ef) | Aug 11, 2022 |
| HP            | 2B4B                        | Desktop     | [6763057a55](https://linux-hardware.org/?probe=6763057a55) | Aug 11, 2022 |
| HP            | ProBook 640 G5              | Notebook    | [321cb5faf4](https://linux-hardware.org/?probe=321cb5faf4) | Aug 11, 2022 |
| HP            | ProBook 640 G5              | Notebook    | [b71c89e139](https://linux-hardware.org/?probe=b71c89e139) | Aug 11, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [3f67c470be](https://linux-hardware.org/?probe=3f67c470be) | Aug 11, 2022 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [673ef8a276](https://linux-hardware.org/?probe=673ef8a276) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [d61320f9c5](https://linux-hardware.org/?probe=d61320f9c5) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [bc7a8afe56](https://linux-hardware.org/?probe=bc7a8afe56) | Aug 11, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [27b3fb870a](https://linux-hardware.org/?probe=27b3fb870a) | Aug 11, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [94a67b764b](https://linux-hardware.org/?probe=94a67b764b) | Aug 11, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [0009de2dbb](https://linux-hardware.org/?probe=0009de2dbb) | Aug 11, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [534c1142c2](https://linux-hardware.org/?probe=534c1142c2) | Aug 10, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0724d34f68](https://linux-hardware.org/?probe=0724d34f68) | Aug 10, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [644f2ccaaf](https://linux-hardware.org/?probe=644f2ccaaf) | Aug 10, 2022 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [df3068aea1](https://linux-hardware.org/?probe=df3068aea1) | Aug 10, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5c904a18b2](https://linux-hardware.org/?probe=5c904a18b2) | Aug 10, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [aebd9902eb](https://linux-hardware.org/?probe=aebd9902eb) | Aug 10, 2022 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [a85b442a71](https://linux-hardware.org/?probe=a85b442a71) | Aug 09, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [598febc046](https://linux-hardware.org/?probe=598febc046) | Aug 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e59d15ee54](https://linux-hardware.org/?probe=e59d15ee54) | Aug 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [a4e02af6d9](https://linux-hardware.org/?probe=a4e02af6d9) | Aug 09, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [1b55fc7b56](https://linux-hardware.org/?probe=1b55fc7b56) | Aug 09, 2022 |
| ECS           | A55F-M4                     | Desktop     | [9c032723ab](https://linux-hardware.org/?probe=9c032723ab) | Aug 09, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [73e439f7f9](https://linux-hardware.org/?probe=73e439f7f9) | Aug 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [fc8542afef](https://linux-hardware.org/?probe=fc8542afef) | Aug 09, 2022 |
| Alienware     | x15 R1                      | Notebook    | [59b6412e2f](https://linux-hardware.org/?probe=59b6412e2f) | Aug 09, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [726b790d1a](https://linux-hardware.org/?probe=726b790d1a) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [1636ef38d5](https://linux-hardware.org/?probe=1636ef38d5) | Aug 09, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [16b59e0aae](https://linux-hardware.org/?probe=16b59e0aae) | Aug 08, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [f833eca9da](https://linux-hardware.org/?probe=f833eca9da) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330s-15ARR 81FB     | Notebook    | [4546912e7b](https://linux-hardware.org/?probe=4546912e7b) | Aug 08, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [b075418a73](https://linux-hardware.org/?probe=b075418a73) | Aug 07, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [949598482f](https://linux-hardware.org/?probe=949598482f) | Aug 07, 2022 |
| ASRock        | H81M-HDS                    | Desktop     | [1d636956f2](https://linux-hardware.org/?probe=1d636956f2) | Aug 07, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [409cc97b53](https://linux-hardware.org/?probe=409cc97b53) | Aug 07, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [457fa11671](https://linux-hardware.org/?probe=457fa11671) | Aug 07, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3f8908c77d](https://linux-hardware.org/?probe=3f8908c77d) | Aug 07, 2022 |
| Lenovo        | ThinkPad E14 20RA004WUS     | Notebook    | [b140ac0aea](https://linux-hardware.org/?probe=b140ac0aea) | Aug 07, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3f71cac385](https://linux-hardware.org/?probe=3f71cac385) | Aug 06, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [9bc488a1b5](https://linux-hardware.org/?probe=9bc488a1b5) | Aug 06, 2022 |
| Acer          | Predator G3-571             | Notebook    | [e5e720b21b](https://linux-hardware.org/?probe=e5e720b21b) | Aug 06, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [21d06392bc](https://linux-hardware.org/?probe=21d06392bc) | Aug 06, 2022 |
| MECHREVO      | Code 01 Series PF5NU1G      | Notebook    | [3c42214ad0](https://linux-hardware.org/?probe=3c42214ad0) | Aug 06, 2022 |
| Lenovo        | ThinkPad T61 6457VE6        | Notebook    | [a6a1de13e4](https://linux-hardware.org/?probe=a6a1de13e4) | Aug 05, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [36bc9464db](https://linux-hardware.org/?probe=36bc9464db) | Aug 05, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [034cd98301](https://linux-hardware.org/?probe=034cd98301) | Aug 05, 2022 |
| Dell          | Latitude E5440              | Notebook    | [7d828eb093](https://linux-hardware.org/?probe=7d828eb093) | Aug 05, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [dd98f4e118](https://linux-hardware.org/?probe=dd98f4e118) | Aug 05, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [ab52d0fc52](https://linux-hardware.org/?probe=ab52d0fc52) | Aug 05, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [7a3c7a2886](https://linux-hardware.org/?probe=7a3c7a2886) | Aug 04, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [ff8fd29d96](https://linux-hardware.org/?probe=ff8fd29d96) | Aug 03, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2f1b2efe5b](https://linux-hardware.org/?probe=2f1b2efe5b) | Aug 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [900f1d3f01](https://linux-hardware.org/?probe=900f1d3f01) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [4c75e1d374](https://linux-hardware.org/?probe=4c75e1d374) | Aug 03, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [76414b53ee](https://linux-hardware.org/?probe=76414b53ee) | Aug 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [66c117c18e](https://linux-hardware.org/?probe=66c117c18e) | Aug 03, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [62a6f6b85a](https://linux-hardware.org/?probe=62a6f6b85a) | Aug 02, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [f93096f2ff](https://linux-hardware.org/?probe=f93096f2ff) | Aug 02, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [9beb1b8221](https://linux-hardware.org/?probe=9beb1b8221) | Aug 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [563bd9cecd](https://linux-hardware.org/?probe=563bd9cecd) | Aug 02, 2022 |
| ASRock        | X370 Pro4                   | Desktop     | [674f15b7f7](https://linux-hardware.org/?probe=674f15b7f7) | Aug 02, 2022 |
| ASRock        | X370 Pro4                   | Desktop     | [d907eedbad](https://linux-hardware.org/?probe=d907eedbad) | Aug 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [e650b177cc](https://linux-hardware.org/?probe=e650b177cc) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [d9c5b6d4c5](https://linux-hardware.org/?probe=d9c5b6d4c5) | Aug 02, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [dd8b9dc221](https://linux-hardware.org/?probe=dd8b9dc221) | Aug 02, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [049630bcaa](https://linux-hardware.org/?probe=049630bcaa) | Aug 02, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [a008ad925d](https://linux-hardware.org/?probe=a008ad925d) | Aug 01, 2022 |
| Acidanther... | MacBookPro13,1              | Notebook    | [5c8158f059](https://linux-hardware.org/?probe=5c8158f059) | Aug 01, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [64a21844e4](https://linux-hardware.org/?probe=64a21844e4) | Aug 01, 2022 |
| HP            | Spectre                     | Convertible | [afab893436](https://linux-hardware.org/?probe=afab893436) | Aug 01, 2022 |
| HP            | Spectre                     | Convertible | [60d75d422c](https://linux-hardware.org/?probe=60d75d422c) | Aug 01, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Arch             | 2984      | 55.7%   |
| Arch Rolling     | 2349      | 43.85%  |
| Arch V20.4.11    | 3         | 0.06%   |
| Arch V19.11.3    | 3         | 0.06%   |
| Arch V20.5.7     | 2         | 0.04%   |
| Arch V20.3.4     | 2         | 0.04%   |
| Arch V19.04.4    | 2         | 0.04%   |
| Arch Workstation | 1         | 0.02%   |
| Arch V6.9.2      | 1         | 0.02%   |
| Arch V19.09.1    | 1         | 0.02%   |
| Arch V19.07.9    | 1         | 0.02%   |
| Arch V19.07.11   | 1         | 0.02%   |
| Arch V19.06.1    | 1         | 0.02%   |
| Arch V19.05.2    | 1         | 0.02%   |
| Arch V19.01.4    | 1         | 0.02%   |
| Arch Breaking    | 1         | 0.02%   |
| Arch 2020.09.05  | 1         | 0.02%   |
| Arch 20.08.3     | 1         | 0.02%   |
| Arch 2.7         | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Arch | 5217      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 85        | 1.38%   |
| 6.0.2-arch1-1   | 71        | 1.16%   |
| 5.8.5-arch1-1   | 70        | 1.14%   |
| 5.9.14-arch1-1  | 61        | 0.99%   |
| 5.9.1-arch1-1   | 60        | 0.98%   |
| 5.17.5-arch1-1  | 53        | 0.86%   |
| 5.17.9-arch1-1  | 50        | 0.81%   |
| 5.8.12-arch1-1  | 48        | 0.78%   |
| 5.8.10-arch1-1  | 48        | 0.78%   |
| 5.8.14-arch1-1  | 47        | 0.77%   |
| 5.7.12-arch1-1  | 46        | 0.75%   |
| 5.13.13-arch1-1 | 45        | 0.73%   |
| 5.8.1-arch1-1   | 43        | 0.7%    |
| 5.11.16-arch1-1 | 42        | 0.68%   |
| 5.6.15-arch1-1  | 37        | 0.6%    |
| 5.18.16-arch1-1 | 34        | 0.55%   |
| 5.11.6-arch1-1  | 34        | 0.55%   |
| 5.11.11-arch1-1 | 34        | 0.55%   |
| 5.12.15-arch1-1 | 33        | 0.54%   |
| 5.10.16-arch1-1 | 33        | 0.54%   |
| 5.18.1-arch1-1  | 32        | 0.52%   |
| 5.8.3-arch1-1   | 31        | 0.5%    |
| 5.15.7-arch1-1  | 31        | 0.5%    |
| 5.14.14-arch1-1 | 31        | 0.5%    |
| 6.0.9-arch1-1   | 30        | 0.49%   |
| 6.0.7-arch1-1   | 30        | 0.49%   |
| 5.9.11-arch2-1  | 30        | 0.49%   |
| 5.9.10-arch1-1  | 30        | 0.49%   |
| 5.19.7-arch1-1  | 30        | 0.49%   |
| 5.13.12-arch1-1 | 30        | 0.49%   |
| 6.0.8-arch1-1   | 29        | 0.47%   |
| 5.7.6-arch1-1   | 29        | 0.47%   |
| 5.6.13-arch1-1  | 29        | 0.47%   |
| 5.19.13-arch1-1 | 29        | 0.47%   |
| 5.18.5-arch1-1  | 29        | 0.47%   |
| 5.11.2-arch1-1  | 29        | 0.47%   |
| 5.12.14-arch1-1 | 28        | 0.46%   |
| 5.18.12-arch1-1 | 27        | 0.44%   |
| 5.14.8-arch1-1  | 27        | 0.44%   |
| 5.8.7-arch1-1   | 26        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 105       | 1.71%   |
| 5.8.5   | 92        | 1.5%    |
| 6.0.2   | 90        | 1.47%   |
| 5.9.1   | 77        | 1.25%   |
| 5.8.12  | 73        | 1.19%   |
| 5.9.14  | 72        | 1.17%   |
| 5.17.5  | 70        | 1.14%   |
| 5.8.14  | 63        | 1.03%   |
| 5.8.10  | 62        | 1.01%   |
| 5.17.9  | 60        | 0.98%   |
| 5.13.13 | 56        | 0.91%   |
| 5.8.1   | 53        | 0.86%   |
| 5.7.12  | 53        | 0.86%   |
| 5.11.6  | 52        | 0.85%   |
| 5.11.16 | 51        | 0.83%   |
| 5.11.2  | 43        | 0.7%    |
| 5.12.15 | 42        | 0.68%   |
| 5.10.16 | 42        | 0.68%   |
| 6.0.8   | 41        | 0.67%   |
| 5.18.16 | 41        | 0.67%   |
| 5.11.11 | 41        | 0.67%   |
| 5.19.7  | 40        | 0.65%   |
| 6.0.9   | 39        | 0.64%   |
| 5.7.6   | 38        | 0.62%   |
| 5.6.15  | 38        | 0.62%   |
| 5.18.1  | 38        | 0.62%   |
| 5.15.7  | 38        | 0.62%   |
| 5.14.14 | 38        | 0.62%   |
| 5.12.14 | 38        | 0.62%   |
| 5.16.2  | 37        | 0.6%    |
| 6.0.7   | 36        | 0.59%   |
| 5.8.3   | 36        | 0.59%   |
| 5.19.13 | 36        | 0.59%   |
| 5.16.16 | 36        | 0.59%   |
| 5.14.8  | 36        | 0.59%   |
| 5.13.12 | 36        | 0.59%   |
| 5.12.9  | 36        | 0.59%   |
| 5.9.11  | 35        | 0.57%   |
| 5.6.13  | 35        | 0.57%   |
| 5.18.5  | 35        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 522       | 8.81%   |
| 5.15    | 436       | 7.36%   |
| 5.9     | 384       | 6.48%   |
| 5.18    | 361       | 6.09%   |
| 5.10    | 354       | 5.97%   |
| 5.4     | 353       | 5.96%   |
| 5.11    | 350       | 5.91%   |
| 5.17    | 340       | 5.74%   |
| 5.19    | 336       | 5.67%   |
| 5.12    | 309       | 5.21%   |
| 5.16    | 305       | 5.15%   |
| 6.0     | 296       | 4.99%   |
| 5.6     | 263       | 4.44%   |
| 5.7     | 260       | 4.39%   |
| 5.14    | 236       | 3.98%   |
| 5.13    | 233       | 3.93%   |
| 5.5     | 148       | 2.5%    |
| 5.3     | 114       | 1.92%   |
| 4.19    | 56        | 0.94%   |
| 5.2     | 54        | 0.91%   |
| 5.0     | 41        | 0.69%   |
| 4.18    | 37        | 0.62%   |
| 5.1     | 32        | 0.54%   |
| 4.20    | 22        | 0.37%   |
| 4.17    | 19        | 0.32%   |
| 4.15    | 14        | 0.24%   |
| 4.14    | 10        | 0.17%   |
| 4.16    | 9         | 0.15%   |
| 4.9     | 5         | 0.08%   |
| 4.7     | 4         | 0.07%   |
| 4.6     | 4         | 0.07%   |
| 4.11    | 4         | 0.07%   |
| 4.8     | 3         | 0.05%   |
| 4.4     | 3         | 0.05%   |
| 4.13    | 3         | 0.05%   |
| 6.1     | 2         | 0.03%   |
| 4.10    | 2         | 0.03%   |
| 4.12    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 5213      | 99.92%  |
| i686   | 4         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 1747      | 32.15%  |
| KDE5                     | 1259      | 23.17%  |
| Unknown                  | 732       | 13.47%  |
| XFCE                     | 438       | 8.06%   |
| KDE                      | 286       | 5.26%   |
| i3                       | 278       | 5.12%   |
| MATE                     | 79        | 1.45%   |
| Budgie                   | 79        | 1.45%   |
| Cinnamon                 | 74        | 1.36%   |
| sway                     | 69        | 1.27%   |
| X-Cinnamon               | 68        | 1.25%   |
| Deepin                   | 64        | 1.18%   |
| LXQt                     | 43        | 0.79%   |
| LXDE                     | 34        | 0.63%   |
| awesome                  | 28        | 0.52%   |
| bspwm                    | 26        | 0.48%   |
| qtile                    | 17        | 0.31%   |
| openbox                  | 17        | 0.31%   |
| GNOME Flashback          | 15        | 0.28%   |
| xmonad                   | 11        | 0.2%    |
| Hyprland                 | 11        | 0.2%    |
| Unity                    | 10        | 0.18%   |
| DWM                      | 9         | 0.17%   |
| GNOME Classic            | 6         | 0.11%   |
| i3-with-shmlog           | 5         | 0.09%   |
| Enlightenment            | 4         | 0.07%   |
| river                    | 2         | 0.04%   |
| leftwm                   | 2         | 0.04%   |
| jwm                      | 2         | 0.04%   |
| ICEWM                    | 2         | 0.04%   |
| GNUstep                  | 2         | 0.04%   |
| dusk                     | 2         | 0.04%   |
| default                  | 2         | 0.04%   |
| /usr/bin/openbox-session | 2         | 0.04%   |
| Yaru:ubuntu:GNOME        | 1         | 0.02%   |
| xinitrc                  | 1         | 0.02%   |
| X-Generic                | 1         | 0.02%   |
| Wayfire                  | 1         | 0.02%   |
| sway:Unity               | 1         | 0.02%   |
| Pantheon                 | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3329      | 61.81%  |
| Wayland | 1166      | 21.65%  |
| Tty     | 517       | 9.6%    |
| Unknown | 373       | 6.93%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2248      | 41.74%  |
| SDDM    | 1223      | 22.71%  |
| GDM     | 766       | 14.22%  |
| LightDM | 541       | 10.04%  |
| TDM     | 398       | 7.39%   |
| Ly      | 63        | 1.17%   |
| XDM     | 55        | 1.02%   |
| LXDM    | 46        | 0.85%   |
| SLiM    | 22        | 0.41%   |
| GREETD  | 14        | 0.26%   |
| NODM    | 4         | 0.07%   |
| EMPTTY  | 3         | 0.06%   |
| XINIT   | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 2574      | 48.2%   |
| Unknown    | 587       | 10.99%  |
| en_GB      | 311       | 5.82%   |
| C          | 239       | 4.48%   |
| de_DE      | 215       | 4.03%   |
| it_IT      | 157       | 2.94%   |
| ru_RU      | 155       | 2.9%    |
| pt_BR      | 145       | 2.72%   |
| fr_FR      | 122       | 2.28%   |
| pl_PL      | 74        | 1.39%   |
| en_IN      | 61        | 1.14%   |
| es_ES      | 60        | 1.12%   |
| en_CA      | 59        | 1.1%    |
| zh_CN      | 50        | 0.94%   |
| en_AU      | 50        | 0.94%   |
| en_IE      | 31        | 0.58%   |
| en_DK      | 23        | 0.43%   |
| es_MX      | 21        | 0.39%   |
| de_AT      | 19        | 0.36%   |
| hu_HU      | 18        | 0.34%   |
| ja_JP      | 16        | 0.3%    |
| es_AR      | 16        | 0.3%    |
| en_NZ      | 15        | 0.28%   |
| nl_NL      | 14        | 0.26%   |
| tr_TR      | 13        | 0.24%   |
| ru_UA      | 13        | 0.24%   |
| es_CL      | 13        | 0.24%   |
| cs_CZ      | 12        | 0.22%   |
| es_CO      | 11        | 0.21%   |
| pt_PT      | 10        | 0.19%   |
| en_US.UTF8 | 10        | 0.19%   |
| en_SG      | 10        | 0.19%   |
| en_ZA      | 9         | 0.17%   |
| en_DE      | 9         | 0.17%   |
| sv_SE      | 8         | 0.15%   |
| de_CH      | 8         | 0.15%   |
| uk_UA      | 7         | 0.13%   |
| lv_LV      | 7         | 0.13%   |
| ca_ES      | 7         | 0.13%   |
| zh_TW      | 6         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3292      | 61.73%  |
| BIOS | 2041      | 38.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3823      | 72.28%  |
| Btrfs    | 1008      | 19.06%  |
| Unknown  | 176       | 3.33%   |
| Xfs      | 132       | 2.5%    |
| F2fs     | 77        | 1.46%   |
| Overlay  | 28        | 0.53%   |
| Zfs      | 27        | 0.51%   |
| Ext2     | 8         | 0.15%   |
| XXXXX    | 4         | 0.08%   |
| Ext3     | 2         | 0.04%   |
| XXX4     | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3319      | 62.67%  |
| Unknown | 1507      | 28.46%  |
| MBR     | 470       | 8.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4536      | 85.76%  |
| Yes       | 753       | 14.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3628      | 68.44%  |
| Yes       | 1673      | 31.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 1011      | 19.38%  |
| Lenovo                 | 942       | 18.06%  |
| Dell                   | 557       | 10.68%  |
| Hewlett-Packard        | 542       | 10.39%  |
| MSI                    | 443       | 8.49%   |
| Gigabyte Technology    | 432       | 8.28%   |
| ASRock                 | 276       | 5.29%   |
| Acer                   | 249       | 4.77%   |
| Apple                  | 83        | 1.59%   |
| Intel                  | 66        | 1.27%   |
| Samsung Electronics    | 54        | 1.04%   |
| HUAWEI                 | 45        | 0.86%   |
| Toshiba                | 36        | 0.69%   |
| Unknown                | 28        | 0.54%   |
| Notebook               | 27        | 0.52%   |
| Microsoft              | 25        | 0.48%   |
| Timi                   | 20        | 0.38%   |
| Google                 | 20        | 0.38%   |
| Sony                   | 19        | 0.36%   |
| Framework              | 17        | 0.33%   |
| Fujitsu                | 16        | 0.31%   |
| Alienware              | 15        | 0.29%   |
| TUXEDO                 | 14        | 0.27%   |
| Razer                  | 13        | 0.25%   |
| Biostar                | 13        | 0.25%   |
| Pegatron               | 10        | 0.19%   |
| LG Electronics         | 10        | 0.19%   |
| ECS                    | 10        | 0.19%   |
| Medion                 | 9         | 0.17%   |
| Avell High Performance | 9         | 0.17%   |
| System76               | 8         | 0.15%   |
| Positivo               | 8         | 0.15%   |
| Packard Bell           | 8         | 0.15%   |
| Supermicro             | 7         | 0.13%   |
| Schenker               | 7         | 0.13%   |
| MECHREVO               | 6         | 0.12%   |
| Huanan                 | 6         | 0.12%   |
| Chuwi                  | 6         | 0.12%   |
| Teclast                | 5         | 0.1%    |
| ZOTAC                  | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 56        | 1.07%   |
| Unknown                          | 48        | 0.92%   |
| MSI MS-7C37                      | 28        | 0.54%   |
| ASUS TUF Gaming X570-PLUS        | 25        | 0.48%   |
| MSI MS-7C02                      | 23        | 0.44%   |
| MSI MS-7B86                      | 22        | 0.42%   |
| Gigabyte B450M DS3H              | 21        | 0.4%    |
| MSI MS-7A34                      | 16        | 0.31%   |
| Framework Laptop                 | 16        | 0.31%   |
| ASUS ROG STRIX B450-F GAMING     | 15        | 0.29%   |
| ASUS PRIME X470-PRO              | 15        | 0.29%   |
| ASUS PRIME X370-PRO              | 15        | 0.29%   |
| MSI MS-7C91                      | 14        | 0.27%   |
| MSI MS-7B89                      | 14        | 0.27%   |
| MSI MS-7A38                      | 14        | 0.27%   |
| HP Notebook                      | 14        | 0.27%   |
| Dell XPS 15 9570                 | 14        | 0.27%   |
| MSI MS-7B79                      | 13        | 0.25%   |
| Gigabyte X570 AORUS ELITE        | 13        | 0.25%   |
| Gigabyte X470 AORUS ULTRA GAMING | 13        | 0.25%   |
| ASUS PRIME B450M-A               | 13        | 0.25%   |
| Dell XPS 15 9500                 | 12        | 0.23%   |
| Gigabyte 970A-DS3P               | 11        | 0.21%   |
| Dell XPS 13 9360                 | 11        | 0.21%   |
| ASUS ROG STRIX B550-F GAMING     | 11        | 0.21%   |
| ASRock X570 Taichi               | 11        | 0.21%   |
| Gigabyte B450 AORUS ELITE        | 10        | 0.19%   |
| Dell XPS 13 9380                 | 10        | 0.19%   |
| Dell Inspiron 15 7000 Gaming     | 10        | 0.19%   |
| ASUS ROG STRIX X570-E GAMING     | 10        | 0.19%   |
| MSI MS-7C56                      | 9         | 0.17%   |
| HUAWEI NBLK-WAX9X                | 9         | 0.17%   |
| HP EliteBook 840 G6              | 9         | 0.17%   |
| Dell XPS 15 7590                 | 9         | 0.17%   |
| Dell XPS 13 9370                 | 9         | 0.17%   |
| ASUS TUF Gaming B550-PLUS        | 9         | 0.17%   |
| ASUS ROG STRIX X470-F GAMING     | 9         | 0.17%   |
| ASRock B450M Pro4                | 9         | 0.17%   |
| Lenovo IdeaPad 5 14ARE05 81YM    | 8         | 0.15%   |
| HP EliteBook x360 1030 G2        | 8         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 514       | 9.85%   |
| ASUS ROG          | 178       | 3.41%   |
| ASUS PRIME        | 164       | 3.14%   |
| Lenovo IdeaPad    | 156       | 2.99%   |
| Acer Aspire       | 145       | 2.78%   |
| Dell Inspiron     | 144       | 2.76%   |
| Dell XPS          | 132       | 2.53%   |
| Dell Latitude     | 122       | 2.34%   |
| ASUS TUF          | 114       | 2.19%   |
| HP Pavilion       | 98        | 1.88%   |
| HP EliteBook      | 91        | 1.74%   |
| ASUS All          | 56        | 1.07%   |
| HP ENVY           | 55        | 1.05%   |
| Lenovo Legion     | 53        | 1.02%   |
| Lenovo Yoga       | 52        | 1%      |
| HP ProBook        | 50        | 0.96%   |
| HP Laptop         | 50        | 0.96%   |
| Dell Precision    | 49        | 0.94%   |
| ASUS VivoBook     | 49        | 0.94%   |
| Unknown           | 48        | 0.92%   |
| Gigabyte X570     | 47        | 0.9%    |
| Dell OptiPlex     | 43        | 0.82%   |
| Acer Nitro        | 35        | 0.67%   |
| Gigabyte B450M    | 31        | 0.59%   |
| Toshiba Satellite | 28        | 0.54%   |
| MSI MS-7C37       | 28        | 0.54%   |
| Dell Vostro       | 28        | 0.54%   |
| Gigabyte B450     | 27        | 0.52%   |
| ASRock X570       | 27        | 0.52%   |
| Microsoft Surface | 25        | 0.48%   |
| Lenovo ThinkBook  | 25        | 0.48%   |
| ASUS ZenBook      | 25        | 0.48%   |
| Acer Swift        | 25        | 0.48%   |
| MSI MS-7C02       | 23        | 0.44%   |
| HP Spectre        | 23        | 0.44%   |
| MSI MS-7B86       | 22        | 0.42%   |
| ASUS ASUS         | 21        | 0.4%    |
| HP OMEN           | 20        | 0.38%   |
| HP Compaq         | 20        | 0.38%   |
| ASUS STRIX        | 20        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 805       | 15.43%  |
| 2019    | 771       | 14.78%  |
| 2020    | 667       | 12.79%  |
| 2017    | 474       | 9.09%   |
| 2021    | 393       | 7.53%   |
| 2016    | 321       | 6.15%   |
| 2012    | 298       | 5.71%   |
| 2015    | 282       | 5.41%   |
| 2013    | 280       | 5.37%   |
| 2014    | 266       | 5.1%    |
| 2011    | 233       | 4.47%   |
| 2010    | 138       | 2.65%   |
| 2022    | 95        | 1.82%   |
| 2008    | 82        | 1.57%   |
| 2009    | 70        | 1.34%   |
| 2007    | 25        | 0.48%   |
| 2006    | 11        | 0.21%   |
| Unknown | 3         | 0.06%   |
| 2005    | 2         | 0.04%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2824      | 54.13%  |
| Desktop     | 2069      | 39.66%  |
| Convertible | 181       | 3.47%   |
| Tablet      | 48        | 0.92%   |
| Mini pc     | 45        | 0.86%   |
| All in one  | 31        | 0.59%   |
| Server      | 18        | 0.35%   |
| Stick pc    | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5178      | 99.08%  |
| Enabled  | 48        | 0.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5181      | 99.31%  |
| Yes  | 36        | 0.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1556      | 29.39%  |
| 8.01-16.0       | 1033      | 19.51%  |
| 4.01-8.0        | 994       | 18.77%  |
| 32.01-64.0      | 825       | 15.58%  |
| 3.01-4.0        | 455       | 8.59%   |
| 64.01-256.0     | 190       | 3.59%   |
| 24.01-32.0      | 128       | 2.42%   |
| 1.01-2.0        | 66        | 1.25%   |
| 2.01-3.0        | 28        | 0.53%   |
| 0.51-1.0        | 11        | 0.21%   |
| More than 256.0 | 7         | 0.13%   |
| Unknown         | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1361      | 23.68%  |
| 4.01-8.0    | 1317      | 22.91%  |
| 1.01-2.0    | 1299      | 22.6%   |
| 3.01-4.0    | 920       | 16.01%  |
| 8.01-16.0   | 464       | 8.07%   |
| 0.51-1.0    | 210       | 3.65%   |
| 16.01-24.0  | 77        | 1.34%   |
| 0.01-0.5    | 52        | 0.9%    |
| 24.01-32.0  | 31        | 0.54%   |
| 32.01-64.0  | 14        | 0.24%   |
| Unknown     | 2         | 0.03%   |
| 64.01-256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2623      | 48.89%  |
| 2      | 1492      | 27.81%  |
| 3      | 612       | 11.41%  |
| 4      | 292       | 5.44%   |
| 5      | 164       | 3.06%   |
| 6      | 75        | 1.4%    |
| 7      | 41        | 0.76%   |
| 0      | 19        | 0.35%   |
| 8      | 17        | 0.32%   |
| 9      | 15        | 0.28%   |
| 11     | 4         | 0.07%   |
| 12     | 3         | 0.06%   |
| 10     | 3         | 0.06%   |
| 14     | 2         | 0.04%   |
| 22     | 1         | 0.02%   |
| 17     | 1         | 0.02%   |
| 15     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4070      | 77.49%  |
| Yes       | 1182      | 22.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4412      | 84.26%  |
| No        | 824       | 15.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4031      | 76.85%  |
| No        | 1214      | 23.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3597      | 68.16%  |
| No        | 1680      | 31.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 1007      | 19.17%  |
| Germany     | 503       | 9.58%   |
| Russia      | 337       | 6.42%   |
| Brazil      | 278       | 5.29%   |
| Italy       | 257       | 4.89%   |
| France      | 233       | 4.44%   |
| UK          | 201       | 3.83%   |
| India       | 167       | 3.18%   |
| Poland      | 159       | 3.03%   |
| Canada      | 138       | 2.63%   |
| Spain       | 117       | 2.23%   |
| Netherlands | 108       | 2.06%   |
| China       | 88        | 1.68%   |
| Ukraine     | 86        | 1.64%   |
| Australia   | 84        | 1.6%    |
| Austria     | 83        | 1.58%   |
| Sweden      | 80        | 1.52%   |
| Turkey      | 59        | 1.12%   |
| Finland     | 57        | 1.09%   |
| Switzerland | 49        | 0.93%   |
| Czechia     | 49        | 0.93%   |
| Mexico      | 46        | 0.88%   |
| Hungary     | 44        | 0.84%   |
| Belgium     | 44        | 0.84%   |
| Romania     | 41        | 0.78%   |
| Indonesia   | 40        | 0.76%   |
| Argentina   | 39        | 0.74%   |
| Greece      | 38        | 0.72%   |
| Japan       | 37        | 0.7%    |
| Norway      | 36        | 0.69%   |
| Denmark     | 33        | 0.63%   |
| Chile       | 32        | 0.61%   |
| Portugal    | 30        | 0.57%   |
| Vietnam     | 29        | 0.55%   |
| Iran        | 29        | 0.55%   |
| New Zealand | 28        | 0.53%   |
| Colombia    | 26        | 0.5%    |
| Serbia      | 22        | 0.42%   |
| Bulgaria    | 21        | 0.4%    |
| Lithuania   | 20        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 96        | 1.74%   |
| Paris             | 56        | 1.01%   |
| St Petersburg     | 54        | 0.98%   |
| Berlin            | 48        | 0.87%   |
| Vienna            | 44        | 0.8%    |
| Sao Paulo         | 44        | 0.8%    |
| Warsaw            | 41        | 0.74%   |
| Milan             | 38        | 0.69%   |
| Munich            | 33        | 0.6%    |
| Helsinki          | 30        | 0.54%   |
| Frankfurt am Main | 29        | 0.52%   |
| Amsterdam         | 29        | 0.52%   |
| Sydney            | 27        | 0.49%   |
| Los Angeles       | 27        | 0.49%   |
| Melbourne         | 25        | 0.45%   |
| Prague            | 23        | 0.42%   |
| Kyiv              | 23        | 0.42%   |
| Valencia          | 22        | 0.4%    |
| Hamburg           | 22        | 0.4%    |
| New York          | 21        | 0.38%   |
| London            | 21        | 0.38%   |
| Istanbul          | 20        | 0.36%   |
| Athens            | 20        | 0.36%   |
| Seattle           | 19        | 0.34%   |
| Rome              | 19        | 0.34%   |
| Budapest          | 18        | 0.33%   |
| Bengaluru         | 18        | 0.33%   |
| Phoenix           | 17        | 0.31%   |
| Montreal          | 17        | 0.31%   |
| Madrid            | 17        | 0.31%   |
| Krakow            | 17        | 0.31%   |
| Cologne           | 17        | 0.31%   |
| Dallas            | 16        | 0.29%   |
| Singapore         | 15        | 0.27%   |
| Shanghai          | 15        | 0.27%   |
| Chicago           | 15        | 0.27%   |
| Belgrade          | 15        | 0.27%   |
| Beijing           | 15        | 0.27%   |
| Zurich            | 14        | 0.25%   |
| Tallinn           | 14        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1774      | 2778   | 20.35%  |
| WDC                       | 1301      | 1993   | 14.93%  |
| Seagate                   | 1097      | 1644   | 12.59%  |
| Toshiba                   | 582       | 770    | 6.68%   |
| SanDisk                   | 564       | 737    | 6.47%   |
| Kingston                  | 450       | 584    | 5.16%   |
| Crucial                   | 382       | 541    | 4.38%   |
| SK hynix                  | 260       | 313    | 2.98%   |
| Intel                     | 244       | 320    | 2.8%    |
| Unknown                   | 213       | 257    | 2.44%   |
| HGST                      | 154       | 192    | 1.77%   |
| Hitachi                   | 150       | 189    | 1.72%   |
| A-DATA Technology         | 136       | 191    | 1.56%   |
| Micron Technology         | 131       | 153    | 1.5%    |
| Phison                    | 110       | 143    | 1.26%   |
| Apple                     | 56        | 67     | 0.64%   |
| Silicon Motion            | 53        | 63     | 0.61%   |
| China                     | 51        | 62     | 0.59%   |
| OCZ                       | 47        | 65     | 0.54%   |
| Corsair                   | 47        | 60     | 0.54%   |
| Micron/Crucial Technology | 45        | 51     | 0.52%   |
| SPCC                      | 44        | 48     | 0.5%    |
| KIOXIA                    | 42        | 53     | 0.48%   |
| Transcend                 | 41        | 52     | 0.47%   |
| LITEON                    | 40        | 43     | 0.46%   |
| PNY                       | 36        | 43     | 0.41%   |
| Patriot                   | 35        | 41     | 0.4%    |
| Phison Electronics        | 29        | 33     | 0.33%   |
| XPG                       | 26        | 36     | 0.3%    |
| GOODRAM                   | 22        | 25     | 0.25%   |
| Plextor                   | 20        | 29     | 0.23%   |
| Hewlett-Packard           | 20        | 21     | 0.23%   |
| ADATA Technology          | 20        | 24     | 0.23%   |
| Realtek Semiconductor     | 17        | 21     | 0.2%    |
| Lenovo                    | 17        | 19     | 0.2%    |
| JMicron Technology        | 17        | 17     | 0.2%    |
| LITEONIT                  | 16        | 16     | 0.18%   |
| Intenso                   | 16        | 17     | 0.18%   |
| Lexar                     | 15        | 19     | 0.17%   |
| Gigabyte Technology       | 15        | 17     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 500GB                            | 106       | 1.07%   |
| Samsung SSD 860 EVO 500GB                            | 101       | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB                       | 89        | 0.9%    |
| Samsung NVMe SSD Drive 512GB                         | 82        | 0.82%   |
| Kingston SA400S37240G 240GB SSD                      | 78        | 0.78%   |
| Samsung SSD 860 EVO 1TB                              | 76        | 0.76%   |
| Samsung SSD 850 EVO 250GB                            | 76        | 0.76%   |
| Samsung SSD 970 EVO Plus 1TB                         | 75        | 0.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 73        | 0.73%   |
| Samsung NVMe SSD Drive 1TB                           | 67        | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB                       | 65        | 0.65%   |
| Samsung SSD 970 EVO Plus 500GB                       | 65        | 0.65%   |
| Samsung NVMe SSD Drive 500GB                         | 64        | 0.64%   |
| Crucial CT500MX500SSD1 500GB                         | 62        | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                          | 55        | 0.55%   |
| HGST HTS721010A9E630 1TB                             | 52        | 0.52%   |
| Toshiba MQ01ABD100 1TB                               | 51        | 0.51%   |
| Kingston SA400S37120G 120GB SSD                      | 51        | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 50        | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                       | 50        | 0.5%    |
| Samsung SSD 860 EVO 250GB                            | 50        | 0.5%    |
| SanDisk NVMe SSD Drive 1TB                           | 49        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                         | 48        | 0.48%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 48        | 0.48%   |
| Kingston SA400S37480G 480GB SSD                      | 46        | 0.46%   |
| Toshiba DT01ACA100 1TB                               | 45        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 44        | 0.44%   |
| Seagate ST2000DM006-2DM164 2TB                       | 44        | 0.44%   |
| SK hynix NVMe SSD Drive 512GB                        | 43        | 0.43%   |
| Seagate ST500DM002-1BD142 500GB                      | 40        | 0.4%    |
| Seagate ST4000DM004-2CV104 4TB                       | 38        | 0.38%   |
| Samsung SSD 860 QVO 1TB                              | 38        | 0.38%   |
| Samsung SSD 970 EVO 500GB                            | 37        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD                     | 37        | 0.37%   |
| Toshiba MQ04ABF100 1TB                               | 36        | 0.36%   |
| Samsung SSD 840 EVO 250GB                            | 35        | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 34        | 0.34%   |
| Samsung SSD 970 EVO 1TB                              | 33        | 0.33%   |
| WDC WD20EZRZ-00Z5HB0 2TB                             | 32        | 0.32%   |
| Toshiba HDWD110 1TB                                  | 32        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1076      | 1606   | 36.28%  |
| WDC                 | 982       | 1485   | 33.11%  |
| Toshiba             | 408       | 528    | 13.76%  |
| HGST                | 152       | 190    | 5.12%   |
| Hitachi             | 150       | 189    | 5.06%   |
| Samsung Electronics | 101       | 135    | 3.41%   |
| Unknown             | 24        | 30     | 0.81%   |
| Apple               | 20        | 20     | 0.67%   |
| Fujitsu             | 9         | 9      | 0.3%    |
| ASMT                | 9         | 11     | 0.3%    |
| Maxtor              | 5         | 5      | 0.17%   |
| HGST HTS            | 3         | 3      | 0.1%    |
| USB3.0              | 2         | 3      | 0.07%   |
| LaCie               | 2         | 2      | 0.07%   |
| Hewlett-Packard     | 2         | 2      | 0.07%   |
| USB                 | 1         | 1      | 0.03%   |
| TrueNAS             | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SAGE                | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| NeoTech             | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LIO-ORG             | 1         | 2      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| H/W                 | 1         | 1      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| Config              | 1         | 1      | 0.03%   |
| ASUSTOR             | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 864       | 1222   | 28.8%   |
| Kingston            | 356       | 452    | 11.87%  |
| Crucial             | 343       | 484    | 11.43%  |
| SanDisk             | 308       | 417    | 10.27%  |
| WDC                 | 207       | 268    | 6.9%    |
| A-DATA Technology   | 87        | 127    | 2.9%    |
| Intel               | 74        | 87     | 2.47%   |
| China               | 51        | 62     | 1.7%    |
| Toshiba             | 47        | 77     | 1.57%   |
| OCZ                 | 47        | 65     | 1.57%   |
| SK hynix            | 45        | 53     | 1.5%    |
| Transcend           | 39        | 50     | 1.3%    |
| Micron Technology   | 39        | 48     | 1.3%    |
| SPCC                | 36        | 38     | 1.2%    |
| Patriot             | 35        | 41     | 1.17%   |
| LITEON              | 35        | 37     | 1.17%   |
| PNY                 | 31        | 38     | 1.03%   |
| Apple               | 28        | 29     | 0.93%   |
| GOODRAM             | 20        | 23     | 0.67%   |
| Corsair             | 20        | 25     | 0.67%   |
| Plextor             | 17        | 18     | 0.57%   |
| LITEONIT            | 16        | 16     | 0.53%   |
| Intenso             | 15        | 16     | 0.5%    |
| KingSpec            | 14        | 15     | 0.47%   |
| Lexar               | 13        | 16     | 0.43%   |
| JMicron Technology  | 12        | 13     | 0.4%    |
| Hewlett-Packard     | 9         | 9      | 0.3%    |
| Mushkin             | 8         | 13     | 0.27%   |
| TO Exter            | 7         | 8      | 0.23%   |
| Seagate             | 7         | 7      | 0.23%   |
| Netac               | 7         | 7      | 0.23%   |
| Gigabyte Technology | 7         | 7      | 0.23%   |
| Team                | 6         | 7      | 0.2%    |
| FORESEE             | 6         | 8      | 0.2%    |
| KingDian            | 5         | 6      | 0.17%   |
| Unknown             | 5         | 5      | 0.17%   |
| Unknown             | 4         | 4      | 0.13%   |
| AMD                 | 4         | 5      | 0.13%   |
| Teclast             | 3         | 3      | 0.1%    |
| TCSUNBOW            | 3         | 4      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2512      | 3685   | 32.66%  |
| SSD     | 2500      | 3979   | 32.51%  |
| HDD     | 2430      | 4240   | 31.6%   |
| MMC     | 179       | 215    | 2.33%   |
| Unknown | 70        | 79     | 0.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3614      | 7970   | 55.05%  |
| NVMe | 2500      | 3657   | 38.08%  |
| SAS  | 272       | 356    | 4.14%   |
| MMC  | 179       | 215    | 2.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2589      | 4107   | 48.85%  |
| 0.51-1.0   | 1679      | 2430   | 31.68%  |
| 1.01-2.0   | 560       | 855    | 10.57%  |
| 3.01-4.0   | 184       | 313    | 3.47%   |
| 4.01-10.0  | 139       | 265    | 2.62%   |
| 2.01-3.0   | 125       | 194    | 2.36%   |
| 10.01-20.0 | 24        | 55     | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1180      | 21.66%  |
| 101-250        | 1179      | 21.64%  |
| 501-1000       | 1015      | 18.63%  |
| 1001-2000      | 731       | 13.42%  |
| More than 3000 | 530       | 9.73%   |
| 2001-3000      | 312       | 5.73%   |
| 51-100         | 206       | 3.78%   |
| Unknown        | 141       | 2.59%   |
| 21-50          | 83        | 1.52%   |
| 1-20           | 70        | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1019      | 18.03%  |
| 101-250        | 991       | 17.54%  |
| 21-50          | 790       | 13.98%  |
| 251-500        | 712       | 12.6%   |
| 51-100         | 695       | 12.3%   |
| 501-1000       | 600       | 10.62%  |
| 1001-2000      | 356       | 6.3%    |
| More than 3000 | 202       | 3.57%   |
| 2001-3000      | 145       | 2.57%   |
| Unknown        | 141       | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 11        | 13     | 1.78%   |
| Seagate ST1000LM035-1RK172 1TB        | 11        | 11     | 1.78%   |
| HGST HTS721010A9E630 1TB              | 9         | 9      | 1.45%   |
| HGST HTS541010A9E680 1TB              | 7         | 7      | 1.13%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 6         | 6      | 0.97%   |
| OCZ VERTEX4 256GB SSD                 | 6         | 9      | 0.97%   |
| Kingston SV300S37A120G 120GB SSD      | 6         | 6      | 0.97%   |
| WDC WD5000AAKX-001CA0 500GB           | 5         | 6      | 0.81%   |
| Toshiba MQ01ABD100 1TB                | 5         | 8      | 0.81%   |
| Seagate ST500LT012-1DG142 500GB       | 5         | 5      | 0.81%   |
| Seagate ST31000528AS 1TB              | 5         | 5      | 0.81%   |
| Seagate ST2000DM008-2FR102 2TB        | 5         | 8      | 0.81%   |
| Seagate ST2000DM006-2DM164 2TB        | 5         | 6      | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 5         | 8      | 0.81%   |
| Seagate ST1000LM014-SSHD-8GB          | 5         | 5      | 0.81%   |
| Seagate ST1000DM003-9YN162 1TB        | 5         | 5      | 0.81%   |
| Samsung Electronics SSD 960 EVO 250GB | 5         | 11     | 0.81%   |
| HGST HTS725050A7E630 500GB            | 5         | 5      | 0.81%   |
| HGST HTS545050A7E680 500GB            | 5         | 6      | 0.81%   |
| WDC WD20EARX-00PASB0 2TB              | 4         | 4      | 0.65%   |
| WDC WD20EARS-00MVWB0 2TB              | 4         | 5      | 0.65%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 4         | 4      | 0.65%   |
| Seagate ST9500325AS 500GB             | 4         | 4      | 0.65%   |
| Seagate ST3320620AS 320GB             | 4         | 4      | 0.65%   |
| Seagate ST2000LM007-1R8174 2TB        | 4         | 4      | 0.65%   |
| Seagate ST1000LX015-1U7172 1TB        | 4         | 5      | 0.65%   |
| Seagate ST1000DM003-1ER162 1TB        | 4         | 4      | 0.65%   |
| Samsung Electronics HD103SJ 1TB       | 4         | 6      | 0.65%   |
| LITEON CV8-8E128-HP 128GB SSD         | 4         | 4      | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB              | 3         | 3      | 0.48%   |
| WDC WD10EARS-00Y5B1 1TB               | 3         | 4      | 0.48%   |
| Toshiba MK3261GSYN 320GB              | 3         | 3      | 0.48%   |
| Toshiba DT01ACA100 1TB                | 3         | 3      | 0.48%   |
| Seagate ST9250315AS 250GB             | 3         | 3      | 0.48%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 0.48%   |
| Seagate ST500LM021-1KJ152 500GB       | 3         | 3      | 0.48%   |
| Seagate ST4000DM004-2CV104 4TB        | 3         | 3      | 0.48%   |
| Seagate ST3500418AS 500GB             | 3         | 4      | 0.48%   |
| Seagate ST3500312CS 500GB             | 3         | 4      | 0.48%   |
| Seagate ST31000524AS 1TB              | 3         | 3      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 169       | 199    | 28.31%  |
| WDC                   | 129       | 165    | 21.61%  |
| Samsung Electronics   | 51        | 68     | 8.54%   |
| Toshiba               | 43        | 54     | 7.2%    |
| Hitachi               | 38        | 41     | 6.37%   |
| HGST                  | 31        | 32     | 5.19%   |
| Kingston              | 19        | 20     | 3.18%   |
| Intel                 | 18        | 21     | 3.02%   |
| SanDisk               | 15        | 16     | 2.51%   |
| Crucial               | 15        | 17     | 2.51%   |
| SK hynix              | 10        | 11     | 1.68%   |
| OCZ                   | 10        | 17     | 1.68%   |
| A-DATA Technology     | 7         | 8      | 1.17%   |
| LITEON                | 5         | 5      | 0.84%   |
| Transcend             | 3         | 7      | 0.5%    |
| Micron Technology     | 3         | 4      | 0.5%    |
| Hewlett-Packard       | 3         | 3      | 0.5%    |
| Drevo                 | 3         | 4      | 0.5%    |
| Corsair               | 3         | 3      | 0.5%    |
| SPCC                  | 2         | 3      | 0.34%   |
| PNY                   | 2         | 3      | 0.34%   |
| Plextor               | 2         | 9      | 0.34%   |
| Patriot               | 2         | 2      | 0.34%   |
| ASMT                  | 2         | 2      | 0.34%   |
| XrayDisk              | 1         | 1      | 0.17%   |
| SSSTC                 | 1         | 1      | 0.17%   |
| Realtek Semiconductor | 1         | 1      | 0.17%   |
| KingSpec              | 1         | 1      | 0.17%   |
| Kingrich              | 1         | 1      | 0.17%   |
| JMicron Technology    | 1         | 1      | 0.17%   |
| INNOVATION IT         | 1         | 1      | 0.17%   |
| GLOWAY                | 1         | 1      | 0.17%   |
| Gigabyte Technology   | 1         | 1      | 0.17%   |
| China                 | 1         | 1      | 0.17%   |
| BAITITON              | 1         | 4      | 0.17%   |
| Apple                 | 1         | 1      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 169       | 199    | 39.95%  |
| WDC                 | 125       | 160    | 29.55%  |
| Hitachi             | 38        | 41     | 8.98%   |
| Toshiba             | 37        | 48     | 8.75%   |
| HGST                | 31        | 32     | 7.33%   |
| Samsung Electronics | 20        | 24     | 4.73%   |
| Hewlett-Packard     | 1         | 1      | 0.24%   |
| ASMT                | 1         | 1      | 0.24%   |
| Apple               | 1         | 1      | 0.24%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 391       | 507    | 69.82%  |
| SSD  | 135       | 168    | 24.11%  |
| NVMe | 34        | 54     | 6.07%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD                 | 2         | 2      | 20%     |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 10%     |
| WDC WD2500BEVT-22ZCT0 250GB                      | 1         | 1      | 10%     |
| Transcend TS128GMTE850 128GB                     | 1         | 1      | 10%     |
| Seagate ST32000644NS 2TB                         | 1         | 1      | 10%     |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 10%     |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 10%     |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 10%     |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 30%     |
| WDC                 | 2         | 2      | 20%     |
| Kingston            | 2         | 2      | 20%     |
| Transcend           | 1         | 1      | 10%     |
| Seagate             | 1         | 1      | 10%     |
| Phison              | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2755      | 6072   | 46.58%  |
| Detected | 2611      | 5386   | 44.15%  |
| Malfunc  | 538       | 729    | 9.1%    |
| Failed   | 10        | 11     | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2968      | 40.59%  |
| AMD                              | 1427      | 19.51%  |
| Samsung Electronics              | 1030      | 14.08%  |
| SanDisk                          | 414       | 5.66%   |
| SK hynix                         | 212       | 2.9%    |
| Phison Electronics               | 185       | 2.53%   |
| ASMedia Technology               | 153       | 2.09%   |
| Toshiba America Info Systems     | 127       | 1.74%   |
| Kingston Technology Company      | 114       | 1.56%   |
| Micron Technology                | 97        | 1.33%   |
| Micron/Crucial Technology        | 81        | 1.11%   |
| ADATA Technology                 | 80        | 1.09%   |
| Silicon Motion                   | 74        | 1.01%   |
| Marvell Technology Group         | 64        | 0.88%   |
| KIOXIA                           | 45        | 0.62%   |
| JMicron Technology               | 37        | 0.51%   |
| Realtek Semiconductor            | 27        | 0.37%   |
| Union Memory (Shenzhen)          | 19        | 0.26%   |
| Lite-On Technology               | 17        | 0.23%   |
| Lenovo                           | 15        | 0.21%   |
| Nvidia                           | 14        | 0.19%   |
| Broadcom / LSI                   | 12        | 0.16%   |
| Apple                            | 12        | 0.16%   |
| LSI Logic / Symbios Logic        | 11        | 0.15%   |
| Adaptec                          | 9         | 0.12%   |
| Yangtze Memory Technologies      | 8         | 0.11%   |
| Seagate Technology               | 8         | 0.11%   |
| Solid State Storage Technology   | 7         | 0.1%    |
| Silicon Image                    | 7         | 0.1%    |
| VIA Technologies                 | 6         | 0.08%   |
| Hewlett-Packard                  | 6         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.07%   |
| Silicon Integrated Systems [SiS] | 4         | 0.05%   |
| Shenzhen Longsys Electronics     | 4         | 0.05%   |
| OCZ Technology Group             | 4         | 0.05%   |
| Biwin Storage Technology         | 3         | 0.04%   |
| Integrated Technology Express    | 2         | 0.03%   |
| INNOGRIT                         | 2         | 0.03%   |
| Promise Technology               | 1         | 0.01%   |
| Netac Technology                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1081      | 13.17%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 639       | 7.79%   |
| AMD 400 Series Chipset SATA Controller                                         | 352       | 4.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 298       | 3.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 195       | 2.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 176       | 2.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 174       | 2.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 170       | 2.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 151       | 1.84%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 148       | 1.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 144       | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 139       | 1.69%   |
| AMD 500 Series Chipset SATA Controller                                         | 136       | 1.66%   |
| Samsung NVMe SSD Controller 980                                                | 130       | 1.58%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 120       | 1.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 118       | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 113       | 1.38%   |
| Phison E12 NVMe Controller                                                     | 104       | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 104       | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 102       | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 96        | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 95        | 1.16%   |
| Micron Non-Volatile memory controller                                          | 95        | 1.16%   |
| Intel SSD 660P Series                                                          | 90        | 1.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 83        | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 80        | 0.97%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 78        | 0.95%   |
| Intel Volume Management Device NVMe RAID Controller                            | 73        | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 71        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 69        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 65        | 0.79%   |
| AMD 300 Series Chipset SATA Controller                                         | 65        | 0.79%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 64        | 0.78%   |
| Intel SATA Controller [RAID mode]                                              | 62        | 0.76%   |
| AMD X370 Series Chipset SATA Controller                                        | 60        | 0.73%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 59        | 0.72%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 59        | 0.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 58        | 0.71%   |
| SanDisk Non-Volatile memory controller                                         | 54        | 0.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 54        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3905      | 55.19%  |
| NVMe | 2515      | 35.54%  |
| RAID | 353       | 4.99%   |
| IDE  | 278       | 3.93%   |
| SAS  | 17        | 0.24%   |
| SCSI | 8         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3497      | 67.03%  |
| AMD    | 1720      | 32.97%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor            | 95        | 1.82%   |
| AMD Ryzen 5 3600 6-Core Processor             | 95        | 1.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 87        | 1.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 79        | 1.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 73        | 1.4%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 71        | 1.36%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 65        | 1.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 65        | 1.24%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 65        | 1.24%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 64        | 1.22%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 60        | 1.15%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 59        | 1.13%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 49        | 0.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 47        | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 46        | 0.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 46        | 0.88%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 45        | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 42        | 0.8%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 42        | 0.8%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 42        | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 40        | 0.76%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 38        | 0.73%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 38        | 0.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 36        | 0.69%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 36        | 0.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 35        | 0.67%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 35        | 0.67%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 34        | 0.65%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 34        | 0.65%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 33        | 0.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 32        | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 32        | 0.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 31        | 0.59%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 31        | 0.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 31        | 0.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 30        | 0.57%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 29        | 0.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 29        | 0.55%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 29        | 0.55%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 28        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1253      | 23.99%  |
| Intel Core i5           | 1143      | 21.88%  |
| AMD Ryzen 5             | 564       | 10.8%   |
| AMD Ryzen 7             | 518       | 9.92%   |
| Other                   | 266       | 5.09%   |
| Intel Core i3           | 251       | 4.81%   |
| AMD Ryzen 9             | 174       | 3.33%   |
| Intel Celeron           | 124       | 2.37%   |
| Intel Xeon              | 102       | 1.95%   |
| Intel Core 2 Duo        | 91        | 1.74%   |
| Intel Pentium           | 82        | 1.57%   |
| AMD Ryzen 3             | 79        | 1.51%   |
| AMD FX                  | 78        | 1.49%   |
| Intel Core i9           | 58        | 1.11%   |
| AMD Ryzen 7 PRO         | 55        | 1.05%   |
| Intel Atom              | 41        | 0.78%   |
| AMD A8                  | 28        | 0.54%   |
| AMD Ryzen Threadripper  | 27        | 0.52%   |
| AMD Ryzen 5 PRO         | 23        | 0.44%   |
| Intel Core 2 Quad       | 22        | 0.42%   |
| AMD A10                 | 22        | 0.42%   |
| AMD A6                  | 21        | 0.4%    |
| Intel Pentium Dual-Core | 17        | 0.33%   |
| AMD Athlon              | 15        | 0.29%   |
| AMD A4                  | 15        | 0.29%   |
| Intel Pentium Silver    | 14        | 0.27%   |
| AMD Phenom II X4        | 13        | 0.25%   |
| Intel Core m3           | 8         | 0.15%   |
| Intel Genuine           | 7         | 0.13%   |
| Intel Core 2            | 7         | 0.13%   |
| AMD E2                  | 7         | 0.13%   |
| AMD E                   | 7         | 0.13%   |
| AMD Athlon II X4        | 7         | 0.13%   |
| AMD Athlon II X2        | 7         | 0.13%   |
| AMD Phenom II X6        | 6         | 0.11%   |
| AMD Athlon 64 X2        | 6         | 0.11%   |
| Intel Pentium Dual      | 5         | 0.1%    |
| Intel Core m5           | 5         | 0.1%    |
| AMD E1                  | 4         | 0.08%   |
| Intel Pentium 4         | 3         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2028      | 38.81%  |
| 2       | 1377      | 26.35%  |
| 6       | 810       | 15.5%   |
| 8       | 710       | 13.59%  |
| 12      | 122       | 2.33%   |
| 16      | 69        | 1.32%   |
| 1       | 29        | 0.55%   |
| 3       | 24        | 0.46%   |
| 10      | 18        | 0.34%   |
| 14      | 12        | 0.23%   |
| 24      | 8         | 0.15%   |
| 32      | 7         | 0.13%   |
| 64      | 4         | 0.08%   |
| 18      | 2         | 0.04%   |
| Unknown | 2         | 0.04%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 20      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 5189      | 99.46%  |
| 2      | 28        | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4128      | 79%     |
| 1       | 1095      | 20.96%  |
| Unknown | 2         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5109      | 97.74%  |
| Unknown        | 114       | 2.18%   |
| 32-bit         | 4         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1521      | 28.05%  |
| 0x306a9    | 199       | 3.67%   |
| 0x906ea    | 195       | 3.6%    |
| 0x306c3    | 193       | 3.56%   |
| 0x08701021 | 180       | 3.32%   |
| 0x206a7    | 167       | 3.08%   |
| 0x906e9    | 165       | 3.04%   |
| 0x806ea    | 156       | 2.88%   |
| 0x0800820d | 137       | 2.53%   |
| 0x806ec    | 127       | 2.34%   |
| 0x506e3    | 118       | 2.18%   |
| 0x406e3    | 109       | 2.01%   |
| 0x806c1    | 108       | 1.99%   |
| 0x806e9    | 96        | 1.77%   |
| 0x08701013 | 91        | 1.68%   |
| 0x306d4    | 89        | 1.64%   |
| 0x40651    | 83        | 1.53%   |
| 0x08108102 | 83        | 1.53%   |
| 0x0a50000c | 77        | 1.42%   |
| 0x08600106 | 68        | 1.25%   |
| 0x1067a    | 64        | 1.18%   |
| 0x08108109 | 63        | 1.16%   |
| 0xa0652    | 54        | 1%      |
| 0x08001138 | 54        | 1%      |
| 0x20655    | 49        | 0.9%    |
| 0x0a201009 | 49        | 0.9%    |
| 0x08600104 | 49        | 0.9%    |
| 0x806eb    | 44        | 0.81%   |
| 0x0a201016 | 41        | 0.76%   |
| 0x08600103 | 40        | 0.74%   |
| 0x0810100b | 35        | 0.65%   |
| 0x906ed    | 32        | 0.59%   |
| 0x706e5    | 32        | 0.59%   |
| 0x08608103 | 29        | 0.53%   |
| 0x06000852 | 26        | 0.48%   |
| 0x406c4    | 24        | 0.44%   |
| 0x08001137 | 24        | 0.44%   |
| 0x10676    | 22        | 0.41%   |
| 0x08101016 | 22        | 0.41%   |
| 0x706a1    | 21        | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1183      | 22.62%  |
| Zen 2            | 544       | 10.4%   |
| Haswell          | 412       | 7.88%   |
| Zen+             | 365       | 6.98%   |
| Skylake          | 339       | 6.48%   |
| IvyBridge        | 285       | 5.45%   |
| Zen 3            | 262       | 5.01%   |
| SandyBridge      | 244       | 4.67%   |
| Zen              | 203       | 3.88%   |
| TigerLake        | 158       | 3.02%   |
| Unknown          | 144       | 2.75%   |
| CometLake        | 132       | 2.52%   |
| Broadwell        | 131       | 2.51%   |
| Penryn           | 125       | 2.39%   |
| Piledriver       | 96        | 1.84%   |
| Westmere         | 89        | 1.7%    |
| Silvermont       | 80        | 1.53%   |
| Icelake          | 78        | 1.49%   |
| K10              | 46        | 0.88%   |
| Goldmont plus    | 43        | 0.82%   |
| Nehalem          | 36        | 0.69%   |
| Core             | 34        | 0.65%   |
| Excavator        | 33        | 0.63%   |
| Goldmont         | 27        | 0.52%   |
| Alderlake Hybrid | 23        | 0.44%   |
| K10 Llano        | 18        | 0.34%   |
| Steamroller      | 17        | 0.33%   |
| Bonnell          | 17        | 0.33%   |
| Bobcat           | 15        | 0.29%   |
| Puma             | 10        | 0.19%   |
| Jaguar           | 10        | 0.19%   |
| K8 Hammer        | 9         | 0.17%   |
| Tremont          | 6         | 0.11%   |
| NetBurst         | 6         | 0.11%   |
| Bulldozer        | 5         | 0.1%    |
| P6               | 2         | 0.04%   |
| K8 & K10 hybrid  | 2         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2686      | 41.6%   |
| Nvidia                           | 2027      | 31.4%   |
| AMD                              | 1716      | 26.58%  |
| Matrox Electronics Systems       | 11        | 0.17%   |
| ASPEED Technology                | 9         | 0.14%   |
| Silicon Integrated Systems [SiS] | 4         | 0.06%   |
| ATI Technologies                 | 2         | 0.03%   |
| VIA Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 261       | 3.96%   |
| Intel UHD Graphics 620                                                                   | 208       | 3.16%   |
| AMD Renoir                                                                               | 193       | 2.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 187       | 2.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 170       | 2.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 168       | 2.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 167       | 2.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 149       | 2.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 145       | 2.2%    |
| Intel HD Graphics 630                                                                    | 140       | 2.12%   |
| Intel HD Graphics 620                                                                    | 127       | 1.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 124       | 1.88%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 119       | 1.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 114       | 1.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 109       | 1.65%   |
| Intel HD Graphics 5500                                                                   | 96        | 1.46%   |
| Intel HD Graphics 530                                                                    | 86        | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 85        | 1.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 80        | 1.21%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 77        | 1.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 76        | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 72        | 1.09%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 72        | 1.09%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 71        | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 68        | 1.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 67        | 1.02%   |
| AMD Lucienne                                                                             | 63        | 0.96%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 62        | 0.94%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 56        | 0.85%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 53        | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 51        | 0.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 50        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 50        | 0.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 47        | 0.71%   |
| Nvidia GP108M [GeForce MX150]                                                            | 45        | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 43        | 0.65%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 43        | 0.65%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 42        | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 38        | 0.58%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 38        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1642      | 31.2%   |
| 1 x AMD                  | 1334      | 25.35%  |
| 1 x Nvidia               | 1000      | 19%     |
| Intel + Nvidia           | 836       | 15.89%  |
| AMD + Nvidia             | 165       | 3.14%   |
| Intel + AMD              | 141       | 2.68%   |
| 2 x AMD                  | 77        | 1.46%   |
| 2 x Nvidia               | 27        | 0.51%   |
| 1 x Matrox               | 9         | 0.17%   |
| Other                    | 6         | 0.11%   |
| 1 x ASPEED               | 5         | 0.1%    |
| 1 x SiS                  | 4         | 0.08%   |
| 2 x Intel                | 3         | 0.06%   |
| AMD + ASPEED             | 3         | 0.06%   |
| Intel + 2 x Nvidia       | 2         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.04%   |
| AMD + Matrox             | 2         | 0.04%   |
| 3 x Nvidia               | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.02%   |
| 1 x VIA                  | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3794      | 72.01%  |
| Proprietary | 1431      | 27.16%  |
| Unknown     | 44        | 0.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2832      | 52.77%  |
| 7.01-8.0   | 541       | 10.08%  |
| 1.01-2.0   | 528       | 9.84%   |
| 3.01-4.0   | 438       | 8.16%   |
| 0.01-0.5   | 388       | 7.23%   |
| 0.51-1.0   | 234       | 4.36%   |
| 5.01-6.0   | 213       | 3.97%   |
| 8.01-16.0  | 136       | 2.53%   |
| 2.01-3.0   | 48        | 0.89%   |
| 16.01-24.0 | 6         | 0.11%   |
| 4.01-5.0   | 3         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 724       | 11.27%  |
| Samsung Electronics     | 704       | 10.96%  |
| BOE                     | 548       | 8.53%   |
| LG Display              | 491       | 7.64%   |
| Chimei Innolux          | 479       | 7.45%   |
| Dell                    | 474       | 7.38%   |
| Goldstar                | 412       | 6.41%   |
| Acer                    | 262       | 4.08%   |
| AOC                     | 209       | 3.25%   |
| BenQ                    | 198       | 3.08%   |
| Hewlett-Packard         | 187       | 2.91%   |
| Ancor Communications    | 179       | 2.79%   |
| Sharp                   | 172       | 2.68%   |
| Philips                 | 129       | 2.01%   |
| Lenovo                  | 108       | 1.68%   |
| PANDA                   | 88        | 1.37%   |
| ViewSonic               | 86        | 1.34%   |
| Apple                   | 77        | 1.2%    |
| Iiyama                  | 75        | 1.17%   |
| ASUSTek Computer        | 61        | 0.95%   |
| InfoVision              | 47        | 0.73%   |
| LG Electronics          | 44        | 0.68%   |
| Sony                    | 37        | 0.58%   |
| NEC Computers           | 34        | 0.53%   |
| Unknown                 | 33        | 0.51%   |
| MSI                     | 32        | 0.5%    |
| CSO                     | 28        | 0.44%   |
| Chi Mei Optoelectronics | 27        | 0.42%   |
| Eizo                    | 22        | 0.34%   |
| Fujitsu Siemens         | 19        | 0.3%    |
| Panasonic               | 17        | 0.26%   |
| Sceptre Tech            | 16        | 0.25%   |
| Gigabyte Technology     | 16        | 0.25%   |
| Toshiba                 | 15        | 0.23%   |
| Vizio                   | 13        | 0.2%    |
| HannStar                | 13        | 0.2%    |
| Valve                   | 10        | 0.16%   |
| Pixio                   | 10        | 0.16%   |
| Medion                  | 9         | 0.14%   |
| Hitachi                 | 9         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 40        | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 40        | 0.59%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 30        | 0.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 30        | 0.45%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 28        | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 27        | 0.4%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 23        | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 22        | 0.33%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 22        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 22        | 0.33%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 21        | 0.31%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 21        | 0.31%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                    | 21        | 0.31%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 21        | 0.31%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch          | 20        | 0.3%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 18        | 0.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 17        | 0.25%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 17        | 0.25%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 17        | 0.25%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 17        | 0.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 15        | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 15        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 15        | 0.22%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 14        | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 14        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 14        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 14        | 0.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 14        | 0.21%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch     | 14        | 0.21%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 13        | 0.19%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 13        | 0.19%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                      | 13        | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 12        | 0.18%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 12        | 0.18%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 12        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 12        | 0.18%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 12        | 0.18%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 11        | 0.16%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 11        | 0.16%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 11        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2946      | 48.82%  |
| 1366x768 (WXGA)    | 711       | 11.78%  |
| 3840x2160 (4K)     | 488       | 8.09%   |
| 2560x1440 (QHD)    | 455       | 7.54%   |
| 1600x900 (HD+)     | 173       | 2.87%   |
| 1920x1200 (WUXGA)  | 170       | 2.82%   |
| 1680x1050 (WSXGA+) | 126       | 2.09%   |
| 1280x1024 (SXGA)   | 105       | 1.74%   |
| 3440x1440          | 103       | 1.71%   |
| Unknown            | 97        | 1.61%   |
| 1440x900 (WXGA+)   | 88        | 1.46%   |
| 2560x1080          | 75        | 1.24%   |
| 1280x800 (WXGA)    | 53        | 0.88%   |
| 2560x1600          | 45        | 0.75%   |
| 3840x1080          | 40        | 0.66%   |
| 1360x768           | 36        | 0.6%    |
| 2880x1800          | 32        | 0.53%   |
| 3840x2400          | 25        | 0.41%   |
| 2256x1504          | 20        | 0.33%   |
| 3200x1800 (QHD+)   | 19        | 0.31%   |
| 3840x1600          | 17        | 0.28%   |
| 2160x1440          | 17        | 0.28%   |
| 1920x540           | 14        | 0.23%   |
| 2736x1824          | 10        | 0.17%   |
| 7680x2160          | 9         | 0.15%   |
| 3000x2000          | 9         | 0.15%   |
| 3072x1920          | 7         | 0.12%   |
| 1920x1280          | 7         | 0.12%   |
| 1024x768 (XGA)     | 7         | 0.12%   |
| 5120x1440          | 6         | 0.1%    |
| 4480x1440          | 6         | 0.1%    |
| 2240x1400          | 6         | 0.1%    |
| 1280x720 (HD)      | 6         | 0.1%    |
| 1024x600           | 6         | 0.1%    |
| 5760x1080          | 5         | 0.08%   |
| 1600x1200          | 5         | 0.08%   |
| 6400x2160          | 4         | 0.07%   |
| 6400x1440          | 4         | 0.07%   |
| 3840x1200          | 4         | 0.07%   |
| 3286x1080          | 4         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1430      | 22.4%   |
| 27      | 663       | 10.38%  |
| 13      | 644       | 10.09%  |
| 24      | 633       | 9.91%   |
| 14      | 517       | 8.1%    |
| 23      | 441       | 6.91%   |
| 21      | 363       | 5.69%   |
| Unknown | 297       | 4.65%   |
| 17      | 225       | 3.52%   |
| 34      | 148       | 2.32%   |
| 19      | 133       | 2.08%   |
| 31      | 130       | 2.04%   |
| 12      | 112       | 1.75%   |
| 22      | 86        | 1.35%   |
| 18      | 85        | 1.33%   |
| 20      | 60        | 0.94%   |
| 11      | 42        | 0.66%   |
| 16      | 39        | 0.61%   |
| 84      | 36        | 0.56%   |
| 25      | 34        | 0.53%   |
| 72      | 33        | 0.52%   |
| 54      | 20        | 0.31%   |
| 48      | 20        | 0.31%   |
| 28      | 20        | 0.31%   |
| 26      | 18        | 0.28%   |
| 10      | 16        | 0.25%   |
| 37      | 14        | 0.22%   |
| 32      | 14        | 0.22%   |
| 29      | 14        | 0.22%   |
| 46      | 11        | 0.17%   |
| 40      | 10        | 0.16%   |
| 35      | 7         | 0.11%   |
| 33      | 7         | 0.11%   |
| 49      | 6         | 0.09%   |
| 43      | 6         | 0.09%   |
| 42      | 5         | 0.08%   |
| 39      | 5         | 0.08%   |
| 74      | 4         | 0.06%   |
| 65      | 4         | 0.06%   |
| 38      | 4         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2268      | 36.83%  |
| 501-600        | 1545      | 25.09%  |
| 401-500        | 640       | 10.39%  |
| 201-300        | 524       | 8.51%   |
| Unknown        | 297       | 4.82%   |
| 351-400        | 281       | 4.56%   |
| 601-700        | 225       | 3.65%   |
| 701-800        | 170       | 2.76%   |
| 1001-1500      | 78        | 1.27%   |
| 1501-2000      | 74        | 1.2%    |
| 801-900        | 40        | 0.65%   |
| 901-1000       | 13        | 0.21%   |
| 101-200        | 2         | 0.03%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4257      | 76.81%  |
| 16/10   | 592       | 10.68%  |
| Unknown | 252       | 4.55%   |
| 21/9    | 180       | 3.25%   |
| 5/4     | 109       | 1.97%   |
| 3/2     | 89        | 1.61%   |
| 4/3     | 26        | 0.47%   |
| 32/9    | 26        | 0.47%   |
| 2.65    | 4         | 0.07%   |
| 0.62    | 2         | 0.04%   |
| 3.40    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.57    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1427      | 22.73%  |
| 201-250        | 1182      | 18.83%  |
| 81-90          | 862       | 13.73%  |
| 301-350        | 680       | 10.83%  |
| 351-500        | 321       | 5.11%   |
| 71-80          | 299       | 4.76%   |
| Unknown        | 297       | 4.73%   |
| 151-200        | 261       | 4.16%   |
| 251-300        | 242       | 3.86%   |
| 121-130        | 154       | 2.45%   |
| 141-150        | 120       | 1.91%   |
| More than 1000 | 117       | 1.86%   |
| 61-70          | 102       | 1.62%   |
| 501-1000       | 82        | 1.31%   |
| 51-60          | 44        | 0.7%    |
| 111-120        | 30        | 0.48%   |
| 131-140        | 21        | 0.33%   |
| 91-100         | 20        | 0.32%   |
| 41-50          | 15        | 0.24%   |
| 1-40           | 1         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1820      | 30.11%  |
| 121-160       | 1812      | 29.98%  |
| 101-120       | 1320      | 21.84%  |
| 161-240       | 491       | 8.12%   |
| Unknown       | 297       | 4.91%   |
| More than 240 | 207       | 3.42%   |
| 1-50          | 97        | 1.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3873      | 72.42%  |
| 2     | 1168      | 21.84%  |
| 3     | 195       | 3.65%   |
| 0     | 94        | 1.76%   |
| 4     | 15        | 0.28%   |
| 5     | 2         | 0.04%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2962      | 38.09%  |
| Realtek Semiconductor             | 2814      | 36.18%  |
| Qualcomm Atheros                  | 776       | 9.98%   |
| Broadcom                          | 282       | 3.63%   |
| MediaTek                          | 91        | 1.17%   |
| TP-Link                           | 74        | 0.95%   |
| Ralink Technology                 | 69        | 0.89%   |
| Microsoft                         | 56        | 0.72%   |
| Broadcom Limited                  | 53        | 0.68%   |
| Marvell Technology Group          | 50        | 0.64%   |
| Ralink                            | 42        | 0.54%   |
| Lenovo                            | 36        | 0.46%   |
| ASIX Electronics                  | 34        | 0.44%   |
| Sierra Wireless                   | 26        | 0.33%   |
| Ericsson Business Mobile Networks | 25        | 0.32%   |
| Samsung Electronics               | 22        | 0.28%   |
| Aquantia                          | 22        | 0.28%   |
| Xiaomi                            | 21        | 0.27%   |
| Qualcomm                          | 21        | 0.27%   |
| DisplayLink                       | 21        | 0.27%   |
| D-Link                            | 19        | 0.24%   |
| NetGear                           | 18        | 0.23%   |
| Hewlett-Packard                   | 14        | 0.18%   |
| Dell                              | 14        | 0.18%   |
| Qualcomm Atheros Communications   | 13        | 0.17%   |
| Apple                             | 13        | 0.17%   |
| Nvidia                            | 12        | 0.15%   |
| Huawei Technologies               | 12        | 0.15%   |
| Google                            | 12        | 0.15%   |
| Microchip Technology              | 10        | 0.13%   |
| Mellanox Technologies             | 10        | 0.13%   |
| Linksys                           | 8         | 0.1%    |
| Cypress Semiconductor             | 8         | 0.1%    |
| D-Link System                     | 7         | 0.09%   |
| JMicron Technology                | 6         | 0.08%   |
| Edimax Technology                 | 6         | 0.08%   |
| ASUSTek Computer                  | 6         | 0.08%   |
| Fibocom                           | 5         | 0.06%   |
| Arduino SA                        | 5         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2039      | 22.24%  |
| Intel Wi-Fi 6 AX200                                               | 472       | 5.15%   |
| Intel I211 Gigabit Network Connection                             | 329       | 3.59%   |
| Intel Wireless 8265 / 8275                                        | 226       | 2.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 215       | 2.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 165       | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 156       | 1.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 148       | 1.61%   |
| Intel Ethernet Connection (2) I219-V                              | 147       | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 140       | 1.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 137       | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 134       | 1.46%   |
| Intel Wireless 8260                                               | 123       | 1.34%   |
| Intel Wireless 7265                                               | 121       | 1.32%   |
| Intel Wi-Fi 6 AX201                                               | 111       | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 110       | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 110       | 1.2%    |
| Intel Wireless 7260                                               | 93        | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 89        | 0.97%   |
| Intel Wireless-AC 9260                                            | 88        | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 88        | 0.96%   |
| Intel Wireless 3165                                               | 86        | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 83        | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 82        | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 80        | 0.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 79        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 76        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 71        | 0.77%   |
| Intel Ethernet Connection (7) I219-V                              | 68        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 67        | 0.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 61        | 0.67%   |
| Intel Ethernet Connection I217-LM                                 | 60        | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 58        | 0.63%   |
| Intel Ethernet Controller I225-V                                  | 58        | 0.63%   |
| Intel Ethernet Connection (4) I219-V                              | 50        | 0.55%   |
| Intel Wireless 3160                                               | 47        | 0.51%   |
| Intel Ethernet Connection (6) I219-V                              | 46        | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 44        | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 44        | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 43        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2305      | 54.61%  |
| Qualcomm Atheros                | 599       | 14.19%  |
| Realtek Semiconductor           | 581       | 13.76%  |
| Broadcom                        | 216       | 5.12%   |
| MediaTek                        | 87        | 2.06%   |
| Ralink Technology               | 69        | 1.63%   |
| TP-Link                         | 62        | 1.47%   |
| Microsoft                       | 50        | 1.18%   |
| Ralink                          | 42        | 1%      |
| Broadcom Limited                | 39        | 0.92%   |
| Sierra Wireless                 | 26        | 0.62%   |
| Qualcomm                        | 18        | 0.43%   |
| NetGear                         | 16        | 0.38%   |
| D-Link                          | 16        | 0.38%   |
| Marvell Technology Group        | 15        | 0.36%   |
| Qualcomm Atheros Communications | 13        | 0.31%   |
| Linksys                         | 8         | 0.19%   |
| Hewlett-Packard                 | 8         | 0.19%   |
| Dell                            | 7         | 0.17%   |
| Edimax Technology               | 6         | 0.14%   |
| ASUSTek Computer                | 6         | 0.14%   |
| Fibocom                         | 5         | 0.12%   |
| AVM                             | 4         | 0.09%   |
| Wilocity                        | 3         | 0.07%   |
| Mercucys                        | 3         | 0.07%   |
| D-Link System                   | 3         | 0.07%   |
| Belkin Components               | 3         | 0.07%   |
| Xiaomi                          | 2         | 0.05%   |
| Micro Star International        | 2         | 0.05%   |
| IMC Networks                    | 2         | 0.05%   |
| ZyXEL Communications            | 1         | 0.02%   |
| Tenda                           | 1         | 0.02%   |
| Sagem                           | 1         | 0.02%   |
| Quectel Wireless Solutions      | 1         | 0.02%   |
| AboCom Systems                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 472       | 11.13%  |
| Intel Wireless 8265 / 8275                                     | 226       | 5.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 148       | 3.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 140       | 3.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 134       | 3.16%   |
| Intel Wireless 8260                                            | 123       | 2.9%    |
| Intel Wireless 7265                                            | 121       | 2.85%   |
| Intel Wi-Fi 6 AX201                                            | 111       | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 110       | 2.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 110       | 2.59%   |
| Intel Wireless 7260                                            | 93        | 2.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 89        | 2.1%    |
| Intel Wireless-AC 9260                                         | 88        | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 88        | 2.08%   |
| Intel Wireless 3165                                            | 86        | 2.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 83        | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 82        | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 80        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 79        | 1.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 76        | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 71        | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 67        | 1.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 61        | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 58        | 1.37%   |
| Intel Wireless 3160                                            | 47        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 39        | 0.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 37        | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 36        | 0.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 36        | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 34        | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 31        | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 30        | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 28        | 0.66%   |
| Microsoft Xbox 360 Wireless Adapter                            | 28        | 0.66%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 25        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                 | 25        | 0.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 25        | 0.59%   |
| Ralink MT7601U Wireless Adapter                                | 24        | 0.57%   |
| Realtek 802.11ac NIC                                           | 23        | 0.54%   |
| Intel Centrino Advanced-N 6235                                 | 23        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                        | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Semiconductor                         | 2564      | 54.37%  |
| Intel                                         | 1484      | 31.47%  |
| Qualcomm Atheros                              | 233       | 4.94%   |
| Broadcom                                      | 102       | 2.16%   |
| Lenovo                                        | 36        | 0.76%   |
| Marvell Technology Group                      | 35        | 0.74%   |
| ASIX Electronics                              | 34        | 0.72%   |
| Samsung Electronics                           | 22        | 0.47%   |
| Aquantia                                      | 22        | 0.47%   |
| DisplayLink                                   | 21        | 0.45%   |
| Xiaomi                                        | 19        | 0.4%    |
| Broadcom Limited                              | 14        | 0.3%    |
| Apple                                         | 13        | 0.28%   |
| TP-Link                                       | 12        | 0.25%   |
| Nvidia                                        | 12        | 0.25%   |
| Google                                        | 11        | 0.23%   |
| Mellanox Technologies                         | 10        | 0.21%   |
| Cypress Semiconductor                         | 8         | 0.17%   |
| JMicron Technology                            | 6         | 0.13%   |
| Huawei Technologies                           | 6         | 0.13%   |
| Microsoft                                     | 5         | 0.11%   |
| Silicon Integrated Systems [SiS]              | 4         | 0.08%   |
| Motorola PCS                                  | 4         | 0.08%   |
| MediaTek                                      | 4         | 0.08%   |
| D-Link System                                 | 4         | 0.08%   |
| Qualcomm                                      | 3         | 0.06%   |
| OPPO Electronics                              | 3         | 0.06%   |
| ICS Advent                                    | 3         | 0.06%   |
| D-Link                                        | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM                    | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)                 | 2         | 0.04%   |
| NetGear                                       | 2         | 0.04%   |
| HMD Global                                    | 2         | 0.04%   |
| VIA Technologies                              | 1         | 0.02%   |
| Standard Microsystems [SMC]                   | 1         | 0.02%   |
| QNAP System                                   | 1         | 0.02%   |
| Netchip Technology                            | 1         | 0.02%   |
| Linux 2.6.35.3-571-gcca29a0 with fsl-usb2-udc | 1         | 0.02%   |
| LG Electronics                                | 1         | 0.02%   |
| Hisense                                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2039      | 42.16%  |
| Intel I211 Gigabit Network Connection                             | 329       | 6.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 215       | 4.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 165       | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 156       | 3.23%   |
| Intel Ethernet Connection (2) I219-V                              | 147       | 3.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 137       | 2.83%   |
| Intel Ethernet Connection (7) I219-V                              | 68        | 1.41%   |
| Intel Ethernet Connection I217-LM                                 | 60        | 1.24%   |
| Intel Ethernet Controller I225-V                                  | 58        | 1.2%    |
| Intel Ethernet Connection (4) I219-V                              | 50        | 1.03%   |
| Intel Ethernet Connection (6) I219-V                              | 46        | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                             | 44        | 0.91%   |
| Intel Ethernet Connection (2) I218-V                              | 44        | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 43        | 0.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 38        | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 36        | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 36        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 34        | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 33        | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 32        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 31        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 29        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                          | 28        | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 28        | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 26        | 0.54%   |
| Intel I210 Gigabit Network Connection                             | 26        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 24        | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23        | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 23        | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 22        | 0.45%   |
| Intel Ethernet Connection (6) I219-LM                             | 21        | 0.43%   |
| Intel Ethernet Connection (10) I219-V                             | 20        | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 20        | 0.41%   |
| Intel Ethernet Connection I219-V                                  | 18        | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 16        | 0.33%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 16        | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.27%   |
| Intel Ethernet Connection (14) I219-V                             | 13        | 0.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4404      | 51.68%  |
| WiFi     | 4028      | 47.27%  |
| Modem    | 81        | 0.95%   |
| Unknown  | 9         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3077      | 55.9%   |
| Ethernet | 2425      | 44.06%  |
| Modem    | 2         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2803      | 53.54%  |
| 1     | 2217      | 42.35%  |
| 3     | 150       | 2.87%   |
| 0     | 42        | 0.8%    |
| 4     | 15        | 0.29%   |
| 6     | 4         | 0.08%   |
| 5     | 4         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4517      | 85.39%  |
| Yes  | 773       | 14.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1991      | 54.58%  |
| Realtek Semiconductor           | 311       | 8.53%   |
| Cambridge Silicon Radio         | 267       | 7.32%   |
| Qualcomm Atheros Communications | 229       | 6.28%   |
| Broadcom                        | 152       | 4.17%   |
| IMC Networks                    | 125       | 3.43%   |
| Lite-On Technology              | 116       | 3.18%   |
| ASUSTek Computer                | 94        | 2.58%   |
| Foxconn / Hon Hai               | 87        | 2.38%   |
| Apple                           | 77        | 2.11%   |
| Realtek                         | 33        | 0.9%    |
| Dell                            | 31        | 0.85%   |
| Hewlett-Packard                 | 16        | 0.44%   |
| MediaTek                        | 15        | 0.41%   |
| Marvell Semiconductor           | 14        | 0.38%   |
| HTC (High Tech Computer)        | 13        | 0.36%   |
| TP-Link                         | 10        | 0.27%   |
| Toshiba                         | 9         | 0.25%   |
| Ralink                          | 9         | 0.25%   |
| Edimax Technology               | 7         | 0.19%   |
| Foxconn International           | 6         | 0.16%   |
| USI                             | 5         | 0.14%   |
| Dynex                           | 4         | 0.11%   |
| Micro Star International        | 3         | 0.08%   |
| Integrated System Solution      | 3         | 0.08%   |
| Chicony Electronics             | 3         | 0.08%   |
| Askey Computer                  | 3         | 0.08%   |
| Unknown                         | 2         | 0.05%   |
| Ralink Technology               | 2         | 0.05%   |
| Belkin Components               | 2         | 0.05%   |
| Alps Electric                   | 2         | 0.05%   |
| Syntek                          | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Roper                           | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 669       | 18.3%   |
| Intel AX200 Bluetooth                                                | 448       | 12.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 269       | 7.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 267       | 7.3%    |
| Intel AX201 Bluetooth                                                | 262       | 7.17%   |
| Realtek Bluetooth Radio                                              | 205       | 5.61%   |
| Qualcomm Atheros  Bluetooth Device                                   | 119       | 3.25%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 107       | 2.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 83        | 2.27%   |
| Intel AX210 Bluetooth                                                | 83        | 2.27%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 77        | 2.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 49        | 1.34%   |
| Lite-On Bluetooth Device                                             | 45        | 1.23%   |
| IMC Networks Bluetooth Radio                                         | 43        | 1.18%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 42        | 1.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 38        | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 38        | 1.04%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 38        | 1.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 35        | 0.96%   |
| IMC Networks Bluetooth Device                                        | 34        | 0.93%   |
| Realtek Bluetooth Radio                                              | 33        | 0.9%    |
| Apple Bluetooth USB Host Controller                                  | 33        | 0.9%    |
| IMC Networks Wireless_Device                                         | 31        | 0.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 29        | 0.79%   |
| Apple Bluetooth Host Controller                                      | 28        | 0.77%   |
| Intel Bluetooth Device                                               | 27        | 0.74%   |
| Foxconn / Hon Hai Wireless_Device                                    | 26        | 0.71%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 24        | 0.66%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 22        | 0.6%    |
| Qualcomm Atheros AR3011 Bluetooth                                    | 20        | 0.55%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 16        | 0.44%   |
| MediaTek Wireless_Device                                             | 14        | 0.38%   |
| ASUS Bluetooth Radio                                                 | 14        | 0.38%   |
| Realtek RTL8821A Bluetooth                                           | 13        | 0.36%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 13        | 0.36%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 13        | 0.36%   |
| Realtek RTL8723B Bluetooth                                           | 12        | 0.33%   |
| Lite-On Wireless_Device                                              | 12        | 0.33%   |
| Dell DW375 Bluetooth Module                                          | 12        | 0.33%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 11        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3387      | 41.23%  |
| AMD                                  | 1995      | 24.28%  |
| Nvidia                               | 1507      | 18.34%  |
| C-Media Electronics                  | 192       | 2.34%   |
| Logitech                             | 93        | 1.13%   |
| Kingston Technology                  | 65        | 0.79%   |
| Focusrite-Novation                   | 62        | 0.75%   |
| Texas Instruments                    | 56        | 0.68%   |
| JMTek                                | 48        | 0.58%   |
| SteelSeries ApS                      | 47        | 0.57%   |
| Realtek Semiconductor                | 45        | 0.55%   |
| Razer USA                            | 42        | 0.51%   |
| Creative Labs                        | 41        | 0.5%    |
| Lenovo                               | 37        | 0.45%   |
| Creative Technology                  | 35        | 0.43%   |
| Corsair                              | 33        | 0.4%    |
| Blue Microphones                     | 30        | 0.37%   |
| Samson Technologies                  | 23        | 0.28%   |
| Valve Software                       | 19        | 0.23%   |
| GYROCOM C&C                          | 17        | 0.21%   |
| GN Netcom                            | 17        | 0.21%   |
| BEHRINGER International              | 17        | 0.21%   |
| Apple                                | 17        | 0.21%   |
| Generalplus Technology               | 16        | 0.19%   |
| Yamaha                               | 15        | 0.18%   |
| ASUSTek Computer                     | 14        | 0.17%   |
| SAVITECH                             | 13        | 0.16%   |
| Plantronics                          | 13        | 0.16%   |
| XMOS                                 | 12        | 0.15%   |
| Sony                                 | 11        | 0.13%   |
| FiiO Electronics Technology          | 11        | 0.13%   |
| Audio-Technica                       | 11        | 0.13%   |
| RODE Microphones                     | 10        | 0.12%   |
| M-Audio                              | 10        | 0.12%   |
| Sennheiser Communications            | 9         | 0.11%   |
| Dell                                 | 9         | 0.11%   |
| Cambridge Silicon Radio              | 8         | 0.1%    |
| Microsoft                            | 7         | 0.09%   |
| Giga-Byte Technology                 | 7         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 652       | 6.6%    |
| Intel Sunrise Point-LP HD Audio                                            | 500       | 5.06%   |
| AMD Starship/Matisse HD Audio Controller                                   | 465       | 4.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 317       | 3.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 294       | 2.98%   |
| Intel Cannon Lake PCH cAVS                                                 | 289       | 2.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 270       | 2.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 261       | 2.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 228       | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 220       | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 208       | 2.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 206       | 2.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 172       | 1.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 162       | 1.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 158       | 1.6%    |
| Nvidia GP104 High Definition Audio Controller                              | 154       | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 154       | 1.56%   |
| Intel 200 Series PCH HD Audio                                              | 152       | 1.54%   |
| AMD Navi 10 HDMI Audio                                                     | 151       | 1.53%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 131       | 1.33%   |
| Nvidia GP106 High Definition Audio Controller                              | 124       | 1.26%   |
| Intel Broadwell-U Audio Controller                                         | 116       | 1.17%   |
| Intel Haswell-ULT HD Audio Controller                                      | 115       | 1.16%   |
| Intel 8 Series HD Audio Controller                                         | 115       | 1.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 111       | 1.12%   |
| Intel CM238 HD Audio Controller                                            | 108       | 1.09%   |
| Nvidia TU106 High Definition Audio Controller                              | 104       | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 97        | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 97        | 0.98%   |
| Intel Comet Lake PCH cAVS                                                  | 95        | 0.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 93        | 0.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 90        | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                               | 88        | 0.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 88        | 0.89%   |
| Nvidia TU104 HD Audio Controller                                           | 82        | 0.83%   |
| AMD FCH Azalia Controller                                                  | 78        | 0.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 73        | 0.74%   |
| Nvidia GM204 High Definition Audio Controller                              | 72        | 0.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 71        | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                              | 69        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 913       | 20.62%  |
| SK hynix            | 681       | 15.38%  |
| Kingston            | 569       | 12.85%  |
| Corsair             | 455       | 10.28%  |
| Micron Technology   | 413       | 9.33%   |
| Crucial             | 355       | 8.02%   |
| G.Skill             | 290       | 6.55%   |
| Unknown             | 242       | 5.47%   |
| A-DATA Technology   | 81        | 1.83%   |
| Ramaxel Technology  | 74        | 1.67%   |
| Elpida              | 44        | 0.99%   |
| Patriot             | 39        | 0.88%   |
| Team                | 37        | 0.84%   |
| Goodram             | 21        | 0.47%   |
| Nanya Technology    | 20        | 0.45%   |
| Unknown (ABCD)      | 18        | 0.41%   |
| Smart               | 17        | 0.38%   |
| Transcend           | 16        | 0.36%   |
| AMD                 | 11        | 0.25%   |
| Unknown             | 11        | 0.25%   |
| PNY                 | 10        | 0.23%   |
| Goldkey             | 9         | 0.2%    |
| Apacer              | 6         | 0.14%   |
| Teikon              | 5         | 0.11%   |
| Smart Brazil        | 5         | 0.11%   |
| GeIL                | 5         | 0.11%   |
| Wilk Elektronik     | 4         | 0.09%   |
| Silicon Power       | 4         | 0.09%   |
| Neo Forza           | 4         | 0.09%   |
| Golden Empire       | 4         | 0.09%   |
| V-GeN               | 3         | 0.07%   |
| KLEVV               | 3         | 0.07%   |
| Kingmax             | 3         | 0.07%   |
| Avant               | 3         | 0.07%   |
| 48spaces            | 3         | 0.07%   |
| Thermaltake         | 2         | 0.05%   |
| PKI/Kingston        | 2         | 0.05%   |
| Kllisre             | 2         | 0.05%   |
| High Bridge         | 2         | 0.05%   |
| Hewlett-Packard     | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 60        | 1.27%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 57        | 1.2%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 52        | 1.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 51        | 1.08%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 47        | 0.99%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 39        | 0.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 33        | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 28        | 0.59%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s          | 28        | 0.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 24        | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 23        | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 22        | 0.46%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 21        | 0.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.44%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 21        | 0.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 21        | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.42%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 0.42%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.42%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 20        | 0.42%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 20        | 0.42%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 20        | 0.42%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.4%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 19        | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.38%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.36%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 17        | 0.36%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 17        | 0.36%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 17        | 0.36%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s           | 17        | 0.36%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.34%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 16        | 0.34%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 16        | 0.34%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 16        | 0.34%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 16        | 0.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2396      | 62.97%  |
| DDR3    | 959       | 25.2%   |
| LPDDR4  | 126       | 3.31%   |
| LPDDR3  | 117       | 3.07%   |
| Unknown | 57        | 1.5%    |
| DDR2    | 50        | 1.31%   |
| SDRAM   | 48        | 1.26%   |
| LPDDR5  | 25        | 0.66%   |
| DDR5    | 13        | 0.34%   |
| DDR     | 13        | 0.34%   |
| DRAM    | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1975      | 51.99%  |
| DIMM         | 1496      | 39.38%  |
| Row Of Chips | 287       | 7.55%   |
| Chip         | 30        | 0.79%   |
| Unknown      | 8         | 0.21%   |
| RIMM         | 2         | 0.05%   |
| FB-DIMM      | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1908      | 46.39%  |
| 4096  | 973       | 23.66%  |
| 16384 | 739       | 17.97%  |
| 2048  | 278       | 6.76%   |
| 32768 | 160       | 3.89%   |
| 1024  | 48        | 1.17%   |
| 512   | 6         | 0.15%   |
| 65536 | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 709       | 16.97%  |
| 3200    | 680       | 16.27%  |
| 1600    | 637       | 15.24%  |
| 2400    | 375       | 8.97%   |
| 2133    | 243       | 5.81%   |
| 3600    | 231       | 5.53%   |
| 1333    | 176       | 4.21%   |
| 1867    | 106       | 2.54%   |
| 1334    | 84        | 2.01%   |
| 3466    | 74        | 1.77%   |
| 4267    | 66        | 1.58%   |
| 3400    | 62        | 1.48%   |
| 3266    | 61        | 1.46%   |
| 3000    | 54        | 1.29%   |
| 3733    | 45        | 1.08%   |
| 2933    | 44        | 1.05%   |
| 667     | 41        | 0.98%   |
| 3800    | 30        | 0.72%   |
| 1866    | 28        | 0.67%   |
| 1067    | 28        | 0.67%   |
| Unknown | 28        | 0.67%   |
| 2800    | 27        | 0.65%   |
| 1066    | 27        | 0.65%   |
| 6400    | 25        | 0.6%    |
| 800     | 25        | 0.6%    |
| 3866    | 24        | 0.57%   |
| 2666    | 23        | 0.55%   |
| 8400    | 15        | 0.36%   |
| 4266    | 15        | 0.36%   |
| 4199    | 15        | 0.36%   |
| 4800    | 14        | 0.34%   |
| 3666    | 11        | 0.26%   |
| 400     | 11        | 0.26%   |
| 3333    | 10        | 0.24%   |
| 3066    | 9         | 0.22%   |
| 2733    | 9         | 0.22%   |
| 2048    | 9         | 0.22%   |
| 4000    | 8         | 0.19%   |
| 1800    | 8         | 0.19%   |
| 3151    | 7         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 29        | 36.25%  |
| Brother Industries       | 15        | 18.75%  |
| Samsung Electronics      | 13        | 16.25%  |
| Canon                    | 9         | 11.25%  |
| Seiko Epson              | 3         | 3.75%   |
| Prolific Technology      | 3         | 3.75%   |
| Dymo-CoStar              | 3         | 3.75%   |
| Zebra                    | 1         | 1.25%   |
| STMicroelectronics       | 1         | 1.25%   |
| Ricoh                    | 1         | 1.25%   |
| Magic Control Technology | 1         | 1.25%   |
| Fuji Xerox               | 1         | 1.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung M2070 Series                                      | 3         | 3.75%   |
| Prolific PL2305 Parallel Port                             | 3         | 3.75%   |
| HP DeskJet 2130 series                                    | 3         | 3.75%   |
| Samsung SCX-4100 Scanner                                  | 2         | 2.5%    |
| HP Officejet Pro 8100                                     | 2         | 2.5%    |
| HP LaserJet P2015 series                                  | 2         | 2.5%    |
| HP Deskjet 3050 J610 series                               | 2         | 2.5%    |
| HP DeskJet 2620 All-in-One Printer                        | 2         | 2.5%    |
| Dymo-CoStar LabelWriter 450                               | 2         | 2.5%    |
| Brother Printer                                           | 2         | 2.5%    |
| Brother HL-5370DW series                                  | 2         | 2.5%    |
| Zebra LP2844 Printer                                      | 1         | 1.25%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.25%   |
| Seiko Epson XP-7100 Series                                | 1         | 1.25%   |
| Seiko Epson WF-2530 Series                                | 1         | 1.25%   |
| Seiko Epson Printer                                       | 1         | 1.25%   |
| Samsung SCX-4200 series                                   | 1         | 1.25%   |
| Samsung SCX-3200 Series                                   | 1         | 1.25%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.25%   |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 1.25%   |
| Samsung M267x 287x Series                                 | 1         | 1.25%   |
| Samsung M2020 Series                                      | 1         | 1.25%   |
| Samsung CLP-325 Color Laser Printer                       | 1         | 1.25%   |
| Samsung C1860 Series                                      | 1         | 1.25%   |
| Ricoh SP 150SU                                            | 1         | 1.25%   |
| Magic Control BAY-3U1S1P Parallel Port                    | 1         | 1.25%   |
| HP OfficeJet 5600 (USBHUB)                                | 1         | 1.25%   |
| HP Officejet 4500 G510g-m                                 | 1         | 1.25%   |
| HP LaserJet P1005                                         | 1         | 1.25%   |
| HP LaserJet M14-M17                                       | 1         | 1.25%   |
| HP LaserJet 1320                                          | 1         | 1.25%   |
| HP LaserJet 1200                                          | 1         | 1.25%   |
| HP LaserJet 1022                                          | 1         | 1.25%   |
| HP LaserJet 1020                                          | 1         | 1.25%   |
| HP LaserJet 1018                                          | 1         | 1.25%   |
| HP LaserJet 1012                                          | 1         | 1.25%   |
| HP Ink Tank 310 series                                    | 1         | 1.25%   |
| HP ENVY Photo 6200 series                                 | 1         | 1.25%   |
| HP ENVY 5540 series                                       | 1         | 1.25%   |
| HP ENVY 5000 series                                       | 1         | 1.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 8         | 57.14%  |
| Seiko Epson    | 4         | 28.57%  |
| Mustek Systems | 2         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan N650U/N656U                                  | 2         | 14.29%  |
| Canon CanoScan LiDE 200                                     | 2         | 14.29%  |
| Seiko Epson GT-X820 [Perfection V600 Photo]                 | 1         | 7.14%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 1         | 7.14%   |
| Seiko Epson GT-F700 [Perfection V350]                       | 1         | 7.14%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 7.14%   |
| Mustek Systems ScanExpress 1200 UB                          | 1         | 7.14%   |
| Mustek Systems BearPaw 1200 CU Plus                         | 1         | 7.14%   |
| Canon CanoScan LiDE 60                                      | 1         | 7.14%   |
| Canon CanoScan LIDE 25                                      | 1         | 7.14%   |
| Canon CanoScan LiDE 210                                     | 1         | 7.14%   |
| Canon CanoScan LiDE 110                                     | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 670       | 20.11%  |
| IMC Networks                           | 352       | 10.57%  |
| Logitech                               | 297       | 8.92%   |
| Microdia                               | 282       | 8.47%   |
| Acer                                   | 282       | 8.47%   |
| Realtek Semiconductor                  | 230       | 6.9%    |
| Quanta                                 | 171       | 5.13%   |
| Sunplus Innovation Technology          | 148       | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 111       | 3.33%   |
| Syntek                                 | 87        | 2.61%   |
| Lite-On Technology                     | 87        | 2.61%   |
| Apple                                  | 73        | 2.19%   |
| Suyin                                  | 55        | 1.65%   |
| Samsung Electronics                    | 41        | 1.23%   |
| Microsoft                              | 41        | 1.23%   |
| Luxvisions Innotech Limited            | 39        | 1.17%   |
| Silicon Motion                         | 38        | 1.14%   |
| Alcor Micro                            | 36        | 1.08%   |
| Lenovo                                 | 24        | 0.72%   |
| Z-Star Microelectronics                | 21        | 0.63%   |
| Valve Software                         | 17        | 0.51%   |
| MacroSilicon                           | 16        | 0.48%   |
| ARC International                      | 12        | 0.36%   |
| Ricoh                                  | 10        | 0.3%    |
| KYE Systems (Mouse Systems)            | 10        | 0.3%    |
| ALi                                    | 10        | 0.3%    |
| Unknown                                | 9         | 0.27%   |
| Razer USA                              | 9         | 0.27%   |
| Importek                               | 9         | 0.27%   |
| Sonix Technology                       | 8         | 0.24%   |
| Primax Electronics                     | 8         | 0.24%   |
| Generalplus Technology                 | 8         | 0.24%   |
| LG Electronics                         | 7         | 0.21%   |
| Creative Technology                    | 7         | 0.21%   |
| SunplusIT                              | 6         | 0.18%   |
| Jieli Technology                       | 6         | 0.18%   |
| Google                                 | 6         | 0.18%   |
| DJKANA19IDX53W                         | 5         | 0.15%   |
| Trust                                  | 4         | 0.12%   |
| Huawei Technologies                    | 4         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 193       | 5.72%   |
| Microdia Integrated_Webcam_HD                                              | 135       | 4%      |
| IMC Networks Integrated Camera                                             | 124       | 3.68%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 103       | 3.05%   |
| Acer Integrated Camera                                                     | 97        | 2.88%   |
| Realtek Integrated_Webcam_HD                                               | 84        | 2.49%   |
| Chicony HD Webcam                                                          | 78        | 2.31%   |
| Logitech HD Pro Webcam C920                                                | 64        | 1.9%    |
| Sunplus Integrated_Webcam_HD                                               | 58        | 1.72%   |
| Logitech Webcam C270                                                       | 54        | 1.6%    |
| Syntek Integrated Camera                                                   | 53        | 1.57%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 41        | 1.22%   |
| Quanta HD User Facing                                                      | 41        | 1.22%   |
| Lite-On Integrated Camera                                                  | 40        | 1.19%   |
| Acer SunplusIT Integrated Camera                                           | 34        | 1.01%   |
| Acer HD Webcam                                                             | 34        | 1.01%   |
| Chicony Integrated Camera (1280x720@30)                                    | 29        | 0.86%   |
| Chicony HP Wide Vision HD Camera                                           | 29        | 0.86%   |
| Apple FaceTime HD Camera (Built-in)                                        | 28        | 0.83%   |
| Realtek USB Camera                                                         | 27        | 0.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 27        | 0.8%    |
| Chicony USB2.0 Camera                                                      | 27        | 0.8%    |
| Logitech C922 Pro Stream Webcam                                            | 26        | 0.77%   |
| Microdia Integrated Webcam                                                 | 24        | 0.71%   |
| Chicony HP HD Camera                                                       | 24        | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 23        | 0.68%   |
| Chicony HD User Facing                                                     | 22        | 0.65%   |
| Chicony EasyCamera                                                         | 22        | 0.65%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 22        | 0.65%   |
| Acer Lenovo EasyCamera                                                     | 22        | 0.65%   |
| Realtek Integrated Webcam                                                  | 19        | 0.56%   |
| Quanta HP Wide Vision HD Camera                                            | 19        | 0.56%   |
| Microdia Webcam Vitade AF                                                  | 19        | 0.56%   |
| IMC Networks ov9734_azurewave_camera                                       | 19        | 0.56%   |
| Chicony USB2.0 HD UVC WebCam                                               | 19        | 0.56%   |
| Syntek Lenovo EasyCamera                                                   | 18        | 0.53%   |
| Logitech Webcam C310                                                       | 18        | 0.53%   |
| Lite-On HP HD Camera                                                       | 18        | 0.53%   |
| Chicony ThinkPad T490 Webcam                                               | 18        | 0.53%   |
| Acer EasyCamera                                                            | 18        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 274       | 38.32%  |
| Validity Sensors                   | 185       | 25.87%  |
| Shenzhen Goodix Technology         | 129       | 18.04%  |
| Elan Microelectronics              | 41        | 5.73%   |
| Upek                               | 26        | 3.64%   |
| LighTuning Technology              | 25        | 3.5%    |
| AuthenTec                          | 20        | 2.8%    |
| STMicroelectronics                 | 8         | 1.12%   |
| Samsung Electronics                | 3         | 0.42%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.28%   |
| Microsoft                          | 1         | 0.14%   |
| Focal-systems.Corp                 | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 102       | 14.27%  |
| Shenzhen Goodix  FingerPrint Device                                        | 66        | 9.23%   |
| Unknown                                                                    | 64        | 8.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 42        | 5.87%   |
| Shenzhen Goodix Fingerprint Reader                                         | 39        | 5.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 34        | 4.76%   |
| Elan ELAN:Fingerprint                                                      | 28        | 3.92%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 3.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 3.36%   |
| Shenzhen Goodix FingerPrint                                                | 24        | 3.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 22        | 3.08%   |
| Synaptics  WBDI                                                            | 21        | 2.94%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 17        | 2.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 16        | 2.24%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 15        | 2.1%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 15        | 2.1%    |
| Validity Sensors VFS491                                                    | 13        | 1.82%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 12        | 1.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 11        | 1.54%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 1.54%   |
| Elan ELAN:ARM-M4                                                           | 11        | 1.54%   |
| AuthenTec AES2810                                                          | 11        | 1.54%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.26%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 1.12%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 0.98%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 0.84%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 0.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.56%   |
| Synaptics WBDI Device                                                      | 4         | 0.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.42%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.42%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.42%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.28%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.28%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.28%   |
| Samsung Fingerprint Device                                                 | 2         | 0.28%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.28%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.28%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 112       | 40%     |
| Broadcom                          | 99        | 35.36%  |
| Upek                              | 16        | 5.71%   |
| Lenovo                            | 10        | 3.57%   |
| Clay Logic                        | 7         | 2.5%    |
| Advanced Card Systems             | 6         | 2.14%   |
| Yubico.com                        | 5         | 1.79%   |
| O2 Micro                          | 5         | 1.79%   |
| SCM Microsystems                  | 4         | 1.43%   |
| Reiner SCT Kartensysteme          | 4         | 1.43%   |
| Gemalto (was Gemplus)             | 3         | 1.07%   |
| Aladdin Knowledge Systems         | 2         | 0.71%   |
| VASCO Data Security International | 1         | 0.36%   |
| OmniKey                           | 1         | 0.36%   |
| Hewlett-Packard                   | 1         | 0.36%   |
| Fujitsu Siemens Computers         | 1         | 0.36%   |
| Chicony Electronics               | 1         | 0.36%   |
| Aladdin R.D.                      | 1         | 0.36%   |
| Aktiv                             | 1         | 0.36%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 110       | 39.29%  |
| Broadcom 5880                                                                | 28        | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 27        | 9.64%   |
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 7.86%   |
| Broadcom 58200                                                               | 20        | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 16        | 5.71%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 3.57%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 5         | 1.79%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 1.43%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 1.07%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 1.07%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.71%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 2         | 0.71%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.71%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.71%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.71%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.71%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.36%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.36%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.36%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.36%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.36%   |
| OmniKey Smart Card Reader USB                                                | 1         | 0.36%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.36%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.36%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.36%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.36%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.36%   |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                            | 1         | 0.36%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.36%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.36%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.36%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.36%   |
| Aktiv Rutoken lite                                                           | 1         | 0.36%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.36%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.36%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.36%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3750      | 70.4%   |
| 1     | 1256      | 23.58%  |
| 2     | 251       | 4.71%   |
| 3     | 59        | 1.11%   |
| 4     | 9         | 0.17%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 700       | 36.5%   |
| Graphics card            | 333       | 17.36%  |
| Chipcard                 | 241       | 12.57%  |
| Net/wireless             | 164       | 8.55%   |
| Multimedia controller    | 124       | 6.47%   |
| Camera                   | 109       | 5.68%   |
| Unassigned class         | 49        | 2.55%   |
| Bluetooth                | 40        | 2.09%   |
| Communication controller | 38        | 1.98%   |
| Sound                    | 31        | 1.62%   |
| Net/ethernet             | 22        | 1.15%   |
| Network                  | 19        | 0.99%   |
| Storage                  | 17        | 0.89%   |
| Card reader              | 11        | 0.57%   |
| Modem                    | 4         | 0.21%   |
| Dvb card                 | 4         | 0.21%   |
| Wireless                 | 2         | 0.1%    |
| Storage/raid             | 2         | 0.1%    |
| Storage/nvme             | 2         | 0.1%    |
| Storage/ide              | 2         | 0.1%    |
| Tv card                  | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |
| Flash memory             | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |

