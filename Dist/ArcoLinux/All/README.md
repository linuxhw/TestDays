ArcoLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ArcoLinux/Desktop/README.md) and [notebooks](/Dist/ArcoLinux/Notebook/README.md).

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

Total: 3539

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b63a038c08](https://linux-hardware.org/?probe=b63a038c08) | Nov 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [e56fc59b28](https://linux-hardware.org/?probe=e56fc59b28) | Nov 06, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [ce42858c1f](https://linux-hardware.org/?probe=ce42858c1f) | Nov 06, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [99a6c38b5d](https://linux-hardware.org/?probe=99a6c38b5d) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8ee603dbfc](https://linux-hardware.org/?probe=8ee603dbfc) | Nov 05, 2023 |
| Dell          | 048DY8 A01                  | Desktop     | [2ef39546ef](https://linux-hardware.org/?probe=2ef39546ef) | Nov 05, 2023 |
| Unknown       | Unknown                     | Notebook    | [f90d872043](https://linux-hardware.org/?probe=f90d872043) | Nov 05, 2023 |
| Lenovo        | ThinkPad X250 20CM001UUK    | Notebook    | [b0fd9fa3c0](https://linux-hardware.org/?probe=b0fd9fa3c0) | Nov 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [c520e5a3b2](https://linux-hardware.org/?probe=c520e5a3b2) | Nov 05, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [907a7f6dd8](https://linux-hardware.org/?probe=907a7f6dd8) | Nov 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [20ffbbc165](https://linux-hardware.org/?probe=20ffbbc165) | Nov 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6fcd2a768b](https://linux-hardware.org/?probe=6fcd2a768b) | Nov 04, 2023 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [c2fa613f00](https://linux-hardware.org/?probe=c2fa613f00) | Nov 04, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [afbfce6e52](https://linux-hardware.org/?probe=afbfce6e52) | Nov 04, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [2aceaf7016](https://linux-hardware.org/?probe=2aceaf7016) | Nov 03, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [429b14ee32](https://linux-hardware.org/?probe=429b14ee32) | Nov 03, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [8ee912a147](https://linux-hardware.org/?probe=8ee912a147) | Nov 02, 2023 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [5c564324e2](https://linux-hardware.org/?probe=5c564324e2) | Nov 02, 2023 |
| Acer          | Swift SF314-55G             | Notebook    | [fee0e3c809](https://linux-hardware.org/?probe=fee0e3c809) | Nov 02, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [59d963de5b](https://linux-hardware.org/?probe=59d963de5b) | Nov 02, 2023 |
| Dell          | Latitude 5480               | Notebook    | [a88b4082b9](https://linux-hardware.org/?probe=a88b4082b9) | Nov 02, 2023 |
| Dell          | XPS L521X                   | Notebook    | [d3df01b854](https://linux-hardware.org/?probe=d3df01b854) | Nov 02, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [a60f1d4a52](https://linux-hardware.org/?probe=a60f1d4a52) | Nov 01, 2023 |
| Razer         | Blade                       | Notebook    | [e9ad529ed4](https://linux-hardware.org/?probe=e9ad529ed4) | Nov 01, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [d4630a5c8b](https://linux-hardware.org/?probe=d4630a5c8b) | Nov 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e5581c3920](https://linux-hardware.org/?probe=e5581c3920) | Nov 01, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [399fe59760](https://linux-hardware.org/?probe=399fe59760) | Nov 01, 2023 |
| Fujitsu       | D4017-A1 S26361-D4017-A1... | Desktop     | [939aebfa68](https://linux-hardware.org/?probe=939aebfa68) | Nov 01, 2023 |
| HP            | 2B01                        | Desktop     | [a345333330](https://linux-hardware.org/?probe=a345333330) | Oct 31, 2023 |
| Gigabyte      | B450M DS3H WIFI V2-CF       | Desktop     | [ac2f19109e](https://linux-hardware.org/?probe=ac2f19109e) | Oct 31, 2023 |
| HP            | 2B01                        | Desktop     | [b3a75824f5](https://linux-hardware.org/?probe=b3a75824f5) | Oct 31, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [d735ec288c](https://linux-hardware.org/?probe=d735ec288c) | Oct 31, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [517f8861a6](https://linux-hardware.org/?probe=517f8861a6) | Oct 31, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [859d23eed0](https://linux-hardware.org/?probe=859d23eed0) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [4e5ba58b35](https://linux-hardware.org/?probe=4e5ba58b35) | Oct 30, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [23fdd2c31d](https://linux-hardware.org/?probe=23fdd2c31d) | Oct 30, 2023 |
| Dell          | XPS L521X                   | Notebook    | [959fc8cb2d](https://linux-hardware.org/?probe=959fc8cb2d) | Oct 29, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [74a1a56aff](https://linux-hardware.org/?probe=74a1a56aff) | Oct 29, 2023 |
| Lenovo        | ThinkPad P53 20QN0050RT     | Notebook    | [179f2c7971](https://linux-hardware.org/?probe=179f2c7971) | Oct 29, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [01e0620386](https://linux-hardware.org/?probe=01e0620386) | Oct 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [1b0a34d774](https://linux-hardware.org/?probe=1b0a34d774) | Oct 29, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8ec254a9a6](https://linux-hardware.org/?probe=8ec254a9a6) | Oct 29, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [b6f56d4f6c](https://linux-hardware.org/?probe=b6f56d4f6c) | Oct 29, 2023 |
| HP            | Laptop 17-by2xxx            | Notebook    | [573a17cea0](https://linux-hardware.org/?probe=573a17cea0) | Oct 28, 2023 |
| Intel         | B75                         | Desktop     | [7b6b287377](https://linux-hardware.org/?probe=7b6b287377) | Oct 28, 2023 |
| Dell          | XPS L412Z                   | Notebook    | [3c2afbb9c4](https://linux-hardware.org/?probe=3c2afbb9c4) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L5000AIX    | Notebook    | [65b2874cbb](https://linux-hardware.org/?probe=65b2874cbb) | Oct 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [69a0449eee](https://linux-hardware.org/?probe=69a0449eee) | Oct 28, 2023 |
| Win elemen... | M600                        | Desktop     | [6a027c490c](https://linux-hardware.org/?probe=6a027c490c) | Oct 28, 2023 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [2ff3541961](https://linux-hardware.org/?probe=2ff3541961) | Oct 28, 2023 |
| Lenovo        | ThinkPad E490 20N80006UE    | Notebook    | [4bb8e497d3](https://linux-hardware.org/?probe=4bb8e497d3) | Oct 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c25324c2a2](https://linux-hardware.org/?probe=c25324c2a2) | Oct 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [220dddac59](https://linux-hardware.org/?probe=220dddac59) | Oct 28, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | Notebook    | [d59d45eb50](https://linux-hardware.org/?probe=d59d45eb50) | Oct 27, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [bc710e10c6](https://linux-hardware.org/?probe=bc710e10c6) | Oct 27, 2023 |
| HP            | 2B0A                        | All in one  | [e60260d9b2](https://linux-hardware.org/?probe=e60260d9b2) | Oct 26, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b65f692868](https://linux-hardware.org/?probe=b65f692868) | Oct 26, 2023 |
| HP            | Pavilion g7                 | Notebook    | [aca57140b6](https://linux-hardware.org/?probe=aca57140b6) | Oct 26, 2023 |
| HP            | Presario CQ56               | Notebook    | [10dbf7856b](https://linux-hardware.org/?probe=10dbf7856b) | Oct 26, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6c18f4a4ef](https://linux-hardware.org/?probe=6c18f4a4ef) | Oct 25, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [f4f26b1c2a](https://linux-hardware.org/?probe=f4f26b1c2a) | Oct 25, 2023 |
| ASUSTek       | X555UB                      | Notebook    | [f501faa5ac](https://linux-hardware.org/?probe=f501faa5ac) | Oct 25, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [796a2f6a53](https://linux-hardware.org/?probe=796a2f6a53) | Oct 25, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a70d4b8a0d](https://linux-hardware.org/?probe=a70d4b8a0d) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [4e7be30b13](https://linux-hardware.org/?probe=4e7be30b13) | Oct 25, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582ZM_... | Notebook    | [1ce9a81d10](https://linux-hardware.org/?probe=1ce9a81d10) | Oct 25, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [94f358053d](https://linux-hardware.org/?probe=94f358053d) | Oct 24, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [5d05be46df](https://linux-hardware.org/?probe=5d05be46df) | Oct 24, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [a71b3ca73a](https://linux-hardware.org/?probe=a71b3ca73a) | Oct 24, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [8764daeeab](https://linux-hardware.org/?probe=8764daeeab) | Oct 24, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [f99b06d89a](https://linux-hardware.org/?probe=f99b06d89a) | Oct 24, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [ccba40d7a9](https://linux-hardware.org/?probe=ccba40d7a9) | Oct 24, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [3daca4912e](https://linux-hardware.org/?probe=3daca4912e) | Oct 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b838b1d016](https://linux-hardware.org/?probe=b838b1d016) | Oct 23, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [a9dd51be33](https://linux-hardware.org/?probe=a9dd51be33) | Oct 23, 2023 |
| Intel         | HM570                       | Desktop     | [5dba972342](https://linux-hardware.org/?probe=5dba972342) | Oct 23, 2023 |
| AMI           | Intel                       | Desktop     | [5e579268b6](https://linux-hardware.org/?probe=5e579268b6) | Oct 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [f134292e10](https://linux-hardware.org/?probe=f134292e10) | Oct 23, 2023 |
| HP            | Folio 13                    | Notebook    | [b7ed500d93](https://linux-hardware.org/?probe=b7ed500d93) | Oct 22, 2023 |
| Intel         | B75                         | Desktop     | [96f9a95f89](https://linux-hardware.org/?probe=96f9a95f89) | Oct 22, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [b1a9053ac6](https://linux-hardware.org/?probe=b1a9053ac6) | Oct 22, 2023 |
| Gigabyte      | B85N PHOENIX-CF             | Desktop     | [a64a820d24](https://linux-hardware.org/?probe=a64a820d24) | Oct 22, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [38d48bd5b5](https://linux-hardware.org/?probe=38d48bd5b5) | Oct 22, 2023 |
| Acer          | Veriton S2680G              | Desktop     | [da6ff1f2f3](https://linux-hardware.org/?probe=da6ff1f2f3) | Oct 22, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [dd755eb3a0](https://linux-hardware.org/?probe=dd755eb3a0) | Oct 22, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [c511cce283](https://linux-hardware.org/?probe=c511cce283) | Oct 22, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [218908299a](https://linux-hardware.org/?probe=218908299a) | Oct 21, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [3b1d62c873](https://linux-hardware.org/?probe=3b1d62c873) | Oct 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [943199c6c3](https://linux-hardware.org/?probe=943199c6c3) | Oct 21, 2023 |
| Dell          | Precision 7530              | Notebook    | [9cdabb5579](https://linux-hardware.org/?probe=9cdabb5579) | Oct 21, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [3216d9052a](https://linux-hardware.org/?probe=3216d9052a) | Oct 21, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [0b9affbbb3](https://linux-hardware.org/?probe=0b9affbbb3) | Oct 21, 2023 |
| HP            | Folio 13                    | Notebook    | [99ff48ac3f](https://linux-hardware.org/?probe=99ff48ac3f) | Oct 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [150e0ba56b](https://linux-hardware.org/?probe=150e0ba56b) | Oct 20, 2023 |
| HP            | 3397                        | Desktop     | [d826d02943](https://linux-hardware.org/?probe=d826d02943) | Oct 20, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [fe4a9ec4d0](https://linux-hardware.org/?probe=fe4a9ec4d0) | Oct 20, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [ce1c3a6c86](https://linux-hardware.org/?probe=ce1c3a6c86) | Oct 20, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [2315267395](https://linux-hardware.org/?probe=2315267395) | Oct 20, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [43a57d26c9](https://linux-hardware.org/?probe=43a57d26c9) | Oct 20, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [6a3e8e996e](https://linux-hardware.org/?probe=6a3e8e996e) | Oct 20, 2023 |
| Lenovo        | XiaoXin Air 15IKBR 81GY     | Notebook    | [755849af68](https://linux-hardware.org/?probe=755849af68) | Oct 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7e7c4e7110](https://linux-hardware.org/?probe=7e7c4e7110) | Oct 19, 2023 |
| Acer          | Predator PO3-620            | Desktop     | [db0c739e61](https://linux-hardware.org/?probe=db0c739e61) | Oct 19, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [231faaeea5](https://linux-hardware.org/?probe=231faaeea5) | Oct 19, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [d906262d01](https://linux-hardware.org/?probe=d906262d01) | Oct 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5bf3d1073e](https://linux-hardware.org/?probe=5bf3d1073e) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [3e5a5380d7](https://linux-hardware.org/?probe=3e5a5380d7) | Oct 18, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [0f5885bc27](https://linux-hardware.org/?probe=0f5885bc27) | Oct 17, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [4e07ff33bd](https://linux-hardware.org/?probe=4e07ff33bd) | Oct 17, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [c430358d6a](https://linux-hardware.org/?probe=c430358d6a) | Oct 17, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [8dcfce6520](https://linux-hardware.org/?probe=8dcfce6520) | Oct 17, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [25ba718720](https://linux-hardware.org/?probe=25ba718720) | Oct 16, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [83cb446c19](https://linux-hardware.org/?probe=83cb446c19) | Oct 16, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [b0adb13b97](https://linux-hardware.org/?probe=b0adb13b97) | Oct 16, 2023 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [0a1c9e7aae](https://linux-hardware.org/?probe=0a1c9e7aae) | Oct 15, 2023 |
| Dell          | 00F82W A00                  | Desktop     | [410900bf0d](https://linux-hardware.org/?probe=410900bf0d) | Oct 15, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [9065a343c2](https://linux-hardware.org/?probe=9065a343c2) | Oct 15, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80bd4e2684](https://linux-hardware.org/?probe=80bd4e2684) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L5000AIX    | Notebook    | [c7b57a58b7](https://linux-hardware.org/?probe=c7b57a58b7) | Oct 15, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [cdd65525cc](https://linux-hardware.org/?probe=cdd65525cc) | Oct 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [23768d9009](https://linux-hardware.org/?probe=23768d9009) | Oct 15, 2023 |
| Dell          | G3 3579                     | Notebook    | [20cb75e8b8](https://linux-hardware.org/?probe=20cb75e8b8) | Oct 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [c12987d53a](https://linux-hardware.org/?probe=c12987d53a) | Oct 15, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [79a68614cb](https://linux-hardware.org/?probe=79a68614cb) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [73f73df16b](https://linux-hardware.org/?probe=73f73df16b) | Oct 14, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [42e5a09fe2](https://linux-hardware.org/?probe=42e5a09fe2) | Oct 14, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [e3a01650f1](https://linux-hardware.org/?probe=e3a01650f1) | Oct 14, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [c46d5e3dfd](https://linux-hardware.org/?probe=c46d5e3dfd) | Oct 13, 2023 |
| HP            | 18E7                        | Desktop     | [855ab006c1](https://linux-hardware.org/?probe=855ab006c1) | Oct 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8d41cb80bf](https://linux-hardware.org/?probe=8d41cb80bf) | Oct 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [339d1c4a25](https://linux-hardware.org/?probe=339d1c4a25) | Oct 13, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4d434ee41b](https://linux-hardware.org/?probe=4d434ee41b) | Oct 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f767f8dd4d](https://linux-hardware.org/?probe=f767f8dd4d) | Oct 12, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [ae56dcb316](https://linux-hardware.org/?probe=ae56dcb316) | Oct 12, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [3c84d02367](https://linux-hardware.org/?probe=3c84d02367) | Oct 12, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [0f40b40836](https://linux-hardware.org/?probe=0f40b40836) | Oct 11, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [c6eeac6337](https://linux-hardware.org/?probe=c6eeac6337) | Oct 11, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [89ae9695ef](https://linux-hardware.org/?probe=89ae9695ef) | Oct 11, 2023 |
| HP            | Notebook                    | Notebook    | [bb5bc1259a](https://linux-hardware.org/?probe=bb5bc1259a) | Oct 11, 2023 |
| BESSTAR Te... | X400                        | Notebook    | [c955c44ef3](https://linux-hardware.org/?probe=c955c44ef3) | Oct 10, 2023 |
| Dell          | 00F82W A00                  | Desktop     | [75fd02b856](https://linux-hardware.org/?probe=75fd02b856) | Oct 10, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [8f7a44301e](https://linux-hardware.org/?probe=8f7a44301e) | Oct 10, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | Notebook    | [ec64651cec](https://linux-hardware.org/?probe=ec64651cec) | Oct 10, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [be8f18157d](https://linux-hardware.org/?probe=be8f18157d) | Oct 10, 2023 |
| HP            | Presario CQ56               | Notebook    | [d554bda407](https://linux-hardware.org/?probe=d554bda407) | Oct 09, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [a2a5c14c8a](https://linux-hardware.org/?probe=a2a5c14c8a) | Oct 09, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [b3fd22ad8e](https://linux-hardware.org/?probe=b3fd22ad8e) | Oct 08, 2023 |
| Lenovo        | ThinkPad T490 20N3SDGJ02    | Notebook    | [43f05c011e](https://linux-hardware.org/?probe=43f05c011e) | Oct 08, 2023 |
| Extra Terr... | Unknown                     | Notebook    | [505b2e0823](https://linux-hardware.org/?probe=505b2e0823) | Oct 08, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [f010d626da](https://linux-hardware.org/?probe=f010d626da) | Oct 08, 2023 |
| HP            | Folio 13                    | Notebook    | [f4ed29d660](https://linux-hardware.org/?probe=f4ed29d660) | Oct 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [3f4a876b18](https://linux-hardware.org/?probe=3f4a876b18) | Oct 08, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [d036c55336](https://linux-hardware.org/?probe=d036c55336) | Oct 07, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [c9d4efa819](https://linux-hardware.org/?probe=c9d4efa819) | Oct 07, 2023 |
| Samsung       | 950QED                      | Convertible | [739568d199](https://linux-hardware.org/?probe=739568d199) | Oct 07, 2023 |
| ASUSTek       | ROG Strix G513QY            | Notebook    | [084087e7bb](https://linux-hardware.org/?probe=084087e7bb) | Oct 07, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [67df4157ef](https://linux-hardware.org/?probe=67df4157ef) | Oct 06, 2023 |
| Dell          | 0WWJRX A00                  | Desktop     | [331ecd3ee8](https://linux-hardware.org/?probe=331ecd3ee8) | Oct 06, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a716f2a182](https://linux-hardware.org/?probe=a716f2a182) | Oct 06, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [97dca67f82](https://linux-hardware.org/?probe=97dca67f82) | Oct 06, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [8619f7e43e](https://linux-hardware.org/?probe=8619f7e43e) | Oct 06, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [0a18c0ff5d](https://linux-hardware.org/?probe=0a18c0ff5d) | Oct 06, 2023 |
| Lenovo        | ThinkPad 3354DSG            | Notebook    | [4eb8d1761d](https://linux-hardware.org/?probe=4eb8d1761d) | Oct 06, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [096ea265ea](https://linux-hardware.org/?probe=096ea265ea) | Oct 05, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [0b0a1ecd08](https://linux-hardware.org/?probe=0b0a1ecd08) | Oct 05, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [e9195a4ac8](https://linux-hardware.org/?probe=e9195a4ac8) | Oct 05, 2023 |
| Lenovo        | ThinkPad T480 20L50010US    | Notebook    | [e7940adc14](https://linux-hardware.org/?probe=e7940adc14) | Oct 05, 2023 |
| Lenovo        | ThinkPad X220 4291C84       | Notebook    | [92cc269d09](https://linux-hardware.org/?probe=92cc269d09) | Oct 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [dbb516ab07](https://linux-hardware.org/?probe=dbb516ab07) | Oct 05, 2023 |
| HP            | 2B0D A01                    | All in one  | [28b1dc9b84](https://linux-hardware.org/?probe=28b1dc9b84) | Oct 05, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [381be666c0](https://linux-hardware.org/?probe=381be666c0) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [1deaeb248b](https://linux-hardware.org/?probe=1deaeb248b) | Oct 04, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [0c33815641](https://linux-hardware.org/?probe=0c33815641) | Oct 04, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [680e68d0c8](https://linux-hardware.org/?probe=680e68d0c8) | Oct 04, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [edbf3959ab](https://linux-hardware.org/?probe=edbf3959ab) | Oct 04, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [8959fc9294](https://linux-hardware.org/?probe=8959fc9294) | Oct 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [b3a1f027db](https://linux-hardware.org/?probe=b3a1f027db) | Oct 03, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [373685317f](https://linux-hardware.org/?probe=373685317f) | Oct 03, 2023 |
| Lenovo        | ThinkPad T490 20N3SDGJ02    | Notebook    | [57b94fa258](https://linux-hardware.org/?probe=57b94fa258) | Oct 02, 2023 |
| HP            | 87D6 SMVB                   | Desktop     | [ac72ba77a1](https://linux-hardware.org/?probe=ac72ba77a1) | Oct 02, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [7d748e38fb](https://linux-hardware.org/?probe=7d748e38fb) | Oct 02, 2023 |
| Samsung       | 750XED                      | Notebook    | [33e2bf8845](https://linux-hardware.org/?probe=33e2bf8845) | Oct 02, 2023 |
| EXPER         | H61H2-MV                    | Desktop     | [5cd287a613](https://linux-hardware.org/?probe=5cd287a613) | Oct 01, 2023 |
| EXPER         | H61H2-MV                    | Desktop     | [7b50b9b997](https://linux-hardware.org/?probe=7b50b9b997) | Oct 01, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [25211e6ce1](https://linux-hardware.org/?probe=25211e6ce1) | Oct 01, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [27e61d282f](https://linux-hardware.org/?probe=27e61d282f) | Oct 01, 2023 |
| Acer          | Aspire SW5-173              | Notebook    | [b990067acf](https://linux-hardware.org/?probe=b990067acf) | Oct 01, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [5d6364a866](https://linux-hardware.org/?probe=5d6364a866) | Oct 01, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [085fbda5a6](https://linux-hardware.org/?probe=085fbda5a6) | Sep 30, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [4575deef12](https://linux-hardware.org/?probe=4575deef12) | Sep 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S1K400    | Notebook    | [fd03530876](https://linux-hardware.org/?probe=fd03530876) | Sep 30, 2023 |
| ASRock        | A320M-DGS                   | Desktop     | [63aafe31f1](https://linux-hardware.org/?probe=63aafe31f1) | Sep 30, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [80ac43658d](https://linux-hardware.org/?probe=80ac43658d) | Sep 30, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [6bc3385414](https://linux-hardware.org/?probe=6bc3385414) | Sep 30, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [7f47d1f656](https://linux-hardware.org/?probe=7f47d1f656) | Sep 30, 2023 |
| Medion        | MS-7667                     | Desktop     | [a91527e825](https://linux-hardware.org/?probe=a91527e825) | Sep 30, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [4835df59b1](https://linux-hardware.org/?probe=4835df59b1) | Sep 30, 2023 |
| Dell          | Latitude 3301               | Notebook    | [3859ed5445](https://linux-hardware.org/?probe=3859ed5445) | Sep 29, 2023 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [6fc3fe7a63](https://linux-hardware.org/?probe=6fc3fe7a63) | Sep 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WY00    | Notebook    | [6a18fb9b21](https://linux-hardware.org/?probe=6a18fb9b21) | Sep 29, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e6d8dfa4a1](https://linux-hardware.org/?probe=e6d8dfa4a1) | Sep 29, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [cb2cbda84d](https://linux-hardware.org/?probe=cb2cbda84d) | Sep 28, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [51272b2713](https://linux-hardware.org/?probe=51272b2713) | Sep 28, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [1509f60079](https://linux-hardware.org/?probe=1509f60079) | Sep 28, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [555dfa4f2e](https://linux-hardware.org/?probe=555dfa4f2e) | Sep 28, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [35f0e18f04](https://linux-hardware.org/?probe=35f0e18f04) | Sep 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [eeb582da25](https://linux-hardware.org/?probe=eeb582da25) | Sep 28, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [6c167e69a4](https://linux-hardware.org/?probe=6c167e69a4) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [797275028d](https://linux-hardware.org/?probe=797275028d) | Sep 28, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [a53de5d0bd](https://linux-hardware.org/?probe=a53de5d0bd) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8c585051a3](https://linux-hardware.org/?probe=8c585051a3) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [fb82c6e942](https://linux-hardware.org/?probe=fb82c6e942) | Sep 27, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [7b6ee612cf](https://linux-hardware.org/?probe=7b6ee612cf) | Sep 27, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [8c38084e7e](https://linux-hardware.org/?probe=8c38084e7e) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [d14e65fadf](https://linux-hardware.org/?probe=d14e65fadf) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [1c764be0e3](https://linux-hardware.org/?probe=1c764be0e3) | Sep 26, 2023 |
| ASUSTek       | X555UB                      | Notebook    | [8496a9f79f](https://linux-hardware.org/?probe=8496a9f79f) | Sep 26, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1476ba44bb](https://linux-hardware.org/?probe=1476ba44bb) | Sep 26, 2023 |
| HP            | Folio 13                    | Notebook    | [a5a1ae29a7](https://linux-hardware.org/?probe=a5a1ae29a7) | Sep 26, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [7524eea19f](https://linux-hardware.org/?probe=7524eea19f) | Sep 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3420c7e013](https://linux-hardware.org/?probe=3420c7e013) | Sep 25, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [48fb2a7ee3](https://linux-hardware.org/?probe=48fb2a7ee3) | Sep 25, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [5e1dcb7163](https://linux-hardware.org/?probe=5e1dcb7163) | Sep 24, 2023 |
| Razer         | Blade                       | Notebook    | [b3b2eb7db8](https://linux-hardware.org/?probe=b3b2eb7db8) | Sep 24, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e6bd73a6e1](https://linux-hardware.org/?probe=e6bd73a6e1) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [575df2588e](https://linux-hardware.org/?probe=575df2588e) | Sep 23, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [6514ebc367](https://linux-hardware.org/?probe=6514ebc367) | Sep 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [539887ee9a](https://linux-hardware.org/?probe=539887ee9a) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [d6943b89de](https://linux-hardware.org/?probe=d6943b89de) | Sep 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1af364233f](https://linux-hardware.org/?probe=1af364233f) | Sep 23, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [1f76bcf230](https://linux-hardware.org/?probe=1f76bcf230) | Sep 23, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [0fb4baf82b](https://linux-hardware.org/?probe=0fb4baf82b) | Sep 23, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [feffc725af](https://linux-hardware.org/?probe=feffc725af) | Sep 23, 2023 |
| MSI           | CR610M                      | Notebook    | [5a9d9ba5ae](https://linux-hardware.org/?probe=5a9d9ba5ae) | Sep 22, 2023 |
| HP            | Folio 13                    | Notebook    | [66f8752b64](https://linux-hardware.org/?probe=66f8752b64) | Sep 22, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [a437fe8bcf](https://linux-hardware.org/?probe=a437fe8bcf) | Sep 21, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | Notebook    | [adee486a15](https://linux-hardware.org/?probe=adee486a15) | Sep 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [65044021bd](https://linux-hardware.org/?probe=65044021bd) | Sep 21, 2023 |
| Monster       | ABRA A7 V11.3               | Notebook    | [7d1ed0e1c5](https://linux-hardware.org/?probe=7d1ed0e1c5) | Sep 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [a085f48523](https://linux-hardware.org/?probe=a085f48523) | Sep 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4d1743c405](https://linux-hardware.org/?probe=4d1743c405) | Sep 20, 2023 |
| MSI           | Z270 GAMING M5              | Desktop     | [005d3394c9](https://linux-hardware.org/?probe=005d3394c9) | Sep 20, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [962ed87784](https://linux-hardware.org/?probe=962ed87784) | Sep 20, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [96a7016b7e](https://linux-hardware.org/?probe=96a7016b7e) | Sep 19, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [20eef756df](https://linux-hardware.org/?probe=20eef756df) | Sep 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1f26ced12d](https://linux-hardware.org/?probe=1f26ced12d) | Sep 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bf29b07e79](https://linux-hardware.org/?probe=bf29b07e79) | Sep 19, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | Notebook    | [65da9aa0c6](https://linux-hardware.org/?probe=65da9aa0c6) | Sep 19, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [28d0c94948](https://linux-hardware.org/?probe=28d0c94948) | Sep 19, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6233a0f825](https://linux-hardware.org/?probe=6233a0f825) | Sep 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [987e4c193b](https://linux-hardware.org/?probe=987e4c193b) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9d59b2b43d](https://linux-hardware.org/?probe=9d59b2b43d) | Sep 19, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [0f0607d7e4](https://linux-hardware.org/?probe=0f0607d7e4) | Sep 18, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [87f5275af6](https://linux-hardware.org/?probe=87f5275af6) | Sep 18, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [5701fbde3e](https://linux-hardware.org/?probe=5701fbde3e) | Sep 18, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [f6a841ea3d](https://linux-hardware.org/?probe=f6a841ea3d) | Sep 18, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [514a5308f2](https://linux-hardware.org/?probe=514a5308f2) | Sep 18, 2023 |
| Gigabyte      | Z270-Gaming 3               | Desktop     | [9e795a05f1](https://linux-hardware.org/?probe=9e795a05f1) | Sep 18, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [9f3bdc24af](https://linux-hardware.org/?probe=9f3bdc24af) | Sep 18, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [178981670d](https://linux-hardware.org/?probe=178981670d) | Sep 17, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [1875fb96e5](https://linux-hardware.org/?probe=1875fb96e5) | Sep 17, 2023 |
| Dell          | Latitude 5421               | Notebook    | [a42c87b953](https://linux-hardware.org/?probe=a42c87b953) | Sep 17, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [09a7651061](https://linux-hardware.org/?probe=09a7651061) | Sep 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [5e399c56a0](https://linux-hardware.org/?probe=5e399c56a0) | Sep 16, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [add3c0be93](https://linux-hardware.org/?probe=add3c0be93) | Sep 15, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [8a404c05c2](https://linux-hardware.org/?probe=8a404c05c2) | Sep 15, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1a4ae657dd](https://linux-hardware.org/?probe=1a4ae657dd) | Sep 15, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [f15272f431](https://linux-hardware.org/?probe=f15272f431) | Sep 15, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [8c1887fa93](https://linux-hardware.org/?probe=8c1887fa93) | Sep 15, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [c1f02dd477](https://linux-hardware.org/?probe=c1f02dd477) | Sep 15, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [2d0ccc33ef](https://linux-hardware.org/?probe=2d0ccc33ef) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [c3e468a36f](https://linux-hardware.org/?probe=c3e468a36f) | Sep 15, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [5e93e7c587](https://linux-hardware.org/?probe=5e93e7c587) | Sep 14, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [04d9ccd10f](https://linux-hardware.org/?probe=04d9ccd10f) | Sep 14, 2023 |
| HP            | EliteBook x360 1040 G7 N... | Convertible | [7baf2aedfc](https://linux-hardware.org/?probe=7baf2aedfc) | Sep 14, 2023 |
| A-DATA Tec... | XENIAXe15TI5G11GXELX        | Notebook    | [6c2fdbd791](https://linux-hardware.org/?probe=6c2fdbd791) | Sep 14, 2023 |
| HP            | Folio 13                    | Notebook    | [9ed048b9e4](https://linux-hardware.org/?probe=9ed048b9e4) | Sep 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S1FU00    | Notebook    | [d0e8034434](https://linux-hardware.org/?probe=d0e8034434) | Sep 14, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [8b7e93cd9d](https://linux-hardware.org/?probe=8b7e93cd9d) | Sep 14, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [9b982600ce](https://linux-hardware.org/?probe=9b982600ce) | Sep 14, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [7bf98a1052](https://linux-hardware.org/?probe=7bf98a1052) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [28116ad85d](https://linux-hardware.org/?probe=28116ad85d) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [675582a822](https://linux-hardware.org/?probe=675582a822) | Sep 12, 2023 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [7dc196091d](https://linux-hardware.org/?probe=7dc196091d) | Sep 12, 2023 |
| Dell          | Precision 7520              | Notebook    | [803e67f286](https://linux-hardware.org/?probe=803e67f286) | Sep 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e12c2067df](https://linux-hardware.org/?probe=e12c2067df) | Sep 11, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [aabd401f54](https://linux-hardware.org/?probe=aabd401f54) | Sep 11, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [a98de00f8f](https://linux-hardware.org/?probe=a98de00f8f) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7809da04f1](https://linux-hardware.org/?probe=7809da04f1) | Sep 10, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [16c285bb07](https://linux-hardware.org/?probe=16c285bb07) | Sep 10, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [2088909e8a](https://linux-hardware.org/?probe=2088909e8a) | Sep 10, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b52a6f9b59](https://linux-hardware.org/?probe=b52a6f9b59) | Sep 10, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [1285b4583d](https://linux-hardware.org/?probe=1285b4583d) | Sep 10, 2023 |
| Intel         | NUC8CYB J69922-405          | Mini pc     | [00ad48fba7](https://linux-hardware.org/?probe=00ad48fba7) | Sep 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [36c9a9e4d4](https://linux-hardware.org/?probe=36c9a9e4d4) | Sep 10, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8e988d79b7](https://linux-hardware.org/?probe=8e988d79b7) | Sep 09, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [a93bb80cb8](https://linux-hardware.org/?probe=a93bb80cb8) | Sep 09, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [c59551fc6f](https://linux-hardware.org/?probe=c59551fc6f) | Sep 09, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [c0bbe7d2b4](https://linux-hardware.org/?probe=c0bbe7d2b4) | Sep 09, 2023 |
| ASUSTek       | G750JW                      | Notebook    | [2e81baa143](https://linux-hardware.org/?probe=2e81baa143) | Sep 09, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [9d0bacfabd](https://linux-hardware.org/?probe=9d0bacfabd) | Sep 09, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6ed0b47516](https://linux-hardware.org/?probe=6ed0b47516) | Sep 08, 2023 |
| BESSTAR Te... | HX90                        | Desktop     | [f8c66085b0](https://linux-hardware.org/?probe=f8c66085b0) | Sep 08, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d6cfec3d58](https://linux-hardware.org/?probe=d6cfec3d58) | Sep 08, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [598ed8c100](https://linux-hardware.org/?probe=598ed8c100) | Sep 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [6dbe579385](https://linux-hardware.org/?probe=6dbe579385) | Sep 08, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [425b748769](https://linux-hardware.org/?probe=425b748769) | Sep 08, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [8fc5475fd3](https://linux-hardware.org/?probe=8fc5475fd3) | Sep 08, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [8d183a9972](https://linux-hardware.org/?probe=8d183a9972) | Sep 08, 2023 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [721c2adc46](https://linux-hardware.org/?probe=721c2adc46) | Sep 07, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [654a62e050](https://linux-hardware.org/?probe=654a62e050) | Sep 07, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [d635105967](https://linux-hardware.org/?probe=d635105967) | Sep 07, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [bedbf331b0](https://linux-hardware.org/?probe=bedbf331b0) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4fd02051b6](https://linux-hardware.org/?probe=4fd02051b6) | Sep 07, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [2385447c50](https://linux-hardware.org/?probe=2385447c50) | Sep 07, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [a4624a95da](https://linux-hardware.org/?probe=a4624a95da) | Sep 07, 2023 |
| Dell          | Latitude E5450              | Notebook    | [a705913b6e](https://linux-hardware.org/?probe=a705913b6e) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8c22ca23f2](https://linux-hardware.org/?probe=8c22ca23f2) | Sep 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S1FU00    | Notebook    | [f24dc99222](https://linux-hardware.org/?probe=f24dc99222) | Sep 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c890510220](https://linux-hardware.org/?probe=c890510220) | Sep 06, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [e47f10b579](https://linux-hardware.org/?probe=e47f10b579) | Sep 06, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [d1cf42c68c](https://linux-hardware.org/?probe=d1cf42c68c) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [4d1ca2eb79](https://linux-hardware.org/?probe=4d1ca2eb79) | Sep 06, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [995b1f100d](https://linux-hardware.org/?probe=995b1f100d) | Sep 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [a1c2c12b6f](https://linux-hardware.org/?probe=a1c2c12b6f) | Sep 06, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [99dd75f86a](https://linux-hardware.org/?probe=99dd75f86a) | Sep 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [cdabed6210](https://linux-hardware.org/?probe=cdabed6210) | Sep 05, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [054c5e3dc5](https://linux-hardware.org/?probe=054c5e3dc5) | Sep 05, 2023 |
| Dynabook      | Satellite Pro L50-G-193     | Notebook    | [6ab6bec7be](https://linux-hardware.org/?probe=6ab6bec7be) | Sep 05, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [8bca1f8244](https://linux-hardware.org/?probe=8bca1f8244) | Sep 05, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [e48cab52a7](https://linux-hardware.org/?probe=e48cab52a7) | Sep 05, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [dc22012520](https://linux-hardware.org/?probe=dc22012520) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | Desktop     | [77c07d0f70](https://linux-hardware.org/?probe=77c07d0f70) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | Desktop     | [a0aaf4be5d](https://linux-hardware.org/?probe=a0aaf4be5d) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e65692f205](https://linux-hardware.org/?probe=e65692f205) | Sep 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [106e2d1e98](https://linux-hardware.org/?probe=106e2d1e98) | Sep 04, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [5a9932b3b8](https://linux-hardware.org/?probe=5a9932b3b8) | Sep 04, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [def3f0d266](https://linux-hardware.org/?probe=def3f0d266) | Sep 04, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [a28ca9b2fb](https://linux-hardware.org/?probe=a28ca9b2fb) | Sep 04, 2023 |
| HP            | Pavilion g7                 | Notebook    | [a2a69279d6](https://linux-hardware.org/?probe=a2a69279d6) | Sep 04, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [8a8a236a44](https://linux-hardware.org/?probe=8a8a236a44) | Sep 04, 2023 |
| AZW           | MINI S                      | Desktop     | [331702f893](https://linux-hardware.org/?probe=331702f893) | Sep 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS24300    | Notebook    | [a28d4357d8](https://linux-hardware.org/?probe=a28d4357d8) | Sep 03, 2023 |
| HP            | Folio 13                    | Notebook    | [d5844cc9e8](https://linux-hardware.org/?probe=d5844cc9e8) | Sep 03, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | Notebook    | [b9de538f7e](https://linux-hardware.org/?probe=b9de538f7e) | Sep 03, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [884eaad43c](https://linux-hardware.org/?probe=884eaad43c) | Sep 03, 2023 |
| IP3 Tech      | rev1.0                      | All in one  | [d2c6f51ff8](https://linux-hardware.org/?probe=d2c6f51ff8) | Sep 03, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [d15e4d0045](https://linux-hardware.org/?probe=d15e4d0045) | Sep 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e05acf231c](https://linux-hardware.org/?probe=e05acf231c) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [78c449e398](https://linux-hardware.org/?probe=78c449e398) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [7f25cc995d](https://linux-hardware.org/?probe=7f25cc995d) | Sep 03, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [47ef8122dc](https://linux-hardware.org/?probe=47ef8122dc) | Sep 03, 2023 |
| Dell          | G3 3779                     | Notebook    | [56fa43078f](https://linux-hardware.org/?probe=56fa43078f) | Sep 02, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [9f8e38af3e](https://linux-hardware.org/?probe=9f8e38af3e) | Sep 02, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [59014a9e20](https://linux-hardware.org/?probe=59014a9e20) | Sep 02, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [19e076e3e1](https://linux-hardware.org/?probe=19e076e3e1) | Sep 01, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [4b8aead223](https://linux-hardware.org/?probe=4b8aead223) | Sep 01, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [773143cf61](https://linux-hardware.org/?probe=773143cf61) | Sep 01, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [b52faa8776](https://linux-hardware.org/?probe=b52faa8776) | Sep 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5f50ef24fe](https://linux-hardware.org/?probe=5f50ef24fe) | Sep 01, 2023 |
| Intel         | NUC7i3BNB J22859-310        | Mini pc     | [cd552285b0](https://linux-hardware.org/?probe=cd552285b0) | Sep 01, 2023 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [ad4df3d293](https://linux-hardware.org/?probe=ad4df3d293) | Aug 31, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [cef6754cd9](https://linux-hardware.org/?probe=cef6754cd9) | Aug 31, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [13ec5c53cf](https://linux-hardware.org/?probe=13ec5c53cf) | Aug 31, 2023 |
| Lenovo        | Legion Y920-17IKB Laptop... | Notebook    | [5976d2d9e9](https://linux-hardware.org/?probe=5976d2d9e9) | Aug 31, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a829cc0dce](https://linux-hardware.org/?probe=a829cc0dce) | Aug 31, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [c75a044974](https://linux-hardware.org/?probe=c75a044974) | Aug 30, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [ebcd50f639](https://linux-hardware.org/?probe=ebcd50f639) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [885c22f859](https://linux-hardware.org/?probe=885c22f859) | Aug 30, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [a31df2b8fe](https://linux-hardware.org/?probe=a31df2b8fe) | Aug 30, 2023 |
| HP            | 802F                        | Desktop     | [7d065f8fd1](https://linux-hardware.org/?probe=7d065f8fd1) | Aug 30, 2023 |
| Lenovo        | ThinkPad A475 20KMS0K20S    | Notebook    | [2685098cd9](https://linux-hardware.org/?probe=2685098cd9) | Aug 29, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [ca4dd5a11e](https://linux-hardware.org/?probe=ca4dd5a11e) | Aug 29, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [c392d83e8e](https://linux-hardware.org/?probe=c392d83e8e) | Aug 29, 2023 |
| Dell          | 0V8WGR A01                  | Desktop     | [9e5ed52b45](https://linux-hardware.org/?probe=9e5ed52b45) | Aug 29, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5a20b8cd20](https://linux-hardware.org/?probe=5a20b8cd20) | Aug 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [708fc220a9](https://linux-hardware.org/?probe=708fc220a9) | Aug 29, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [0789880eae](https://linux-hardware.org/?probe=0789880eae) | Aug 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [265430a40c](https://linux-hardware.org/?probe=265430a40c) | Aug 29, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [6bd291c8b0](https://linux-hardware.org/?probe=6bd291c8b0) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0f3d530e12](https://linux-hardware.org/?probe=0f3d530e12) | Aug 29, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [e27639a1f9](https://linux-hardware.org/?probe=e27639a1f9) | Aug 29, 2023 |
| HP            | 8061                        | Desktop     | [31a0fa50a3](https://linux-hardware.org/?probe=31a0fa50a3) | Aug 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6 82JF    | Notebook    | [0ccccd5c9d](https://linux-hardware.org/?probe=0ccccd5c9d) | Aug 28, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [5df3abe62e](https://linux-hardware.org/?probe=5df3abe62e) | Aug 28, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [3c5aa8e05a](https://linux-hardware.org/?probe=3c5aa8e05a) | Aug 28, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [0cda85fdd1](https://linux-hardware.org/?probe=0cda85fdd1) | Aug 28, 2023 |
| Acer          | Aspire M3470                | Desktop     | [60d18d6d6e](https://linux-hardware.org/?probe=60d18d6d6e) | Aug 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [269a4ac17d](https://linux-hardware.org/?probe=269a4ac17d) | Aug 28, 2023 |
| Lenovo        | ThinkPad X220 4291C84       | Notebook    | [623b0f76d1](https://linux-hardware.org/?probe=623b0f76d1) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8b82375189](https://linux-hardware.org/?probe=8b82375189) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [90474aa183](https://linux-hardware.org/?probe=90474aa183) | Aug 27, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [1112486ef3](https://linux-hardware.org/?probe=1112486ef3) | Aug 27, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f1422f4092](https://linux-hardware.org/?probe=f1422f4092) | Aug 27, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [99e5a7a753](https://linux-hardware.org/?probe=99e5a7a753) | Aug 27, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [8c616e6421](https://linux-hardware.org/?probe=8c616e6421) | Aug 27, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [8ee512db27](https://linux-hardware.org/?probe=8ee512db27) | Aug 27, 2023 |
| Acer          | Aspire M3470                | Desktop     | [7e6d230bf5](https://linux-hardware.org/?probe=7e6d230bf5) | Aug 27, 2023 |
| ASRock        | X570 Phantom Gaming 4S      | Desktop     | [1be18fe99f](https://linux-hardware.org/?probe=1be18fe99f) | Aug 27, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [512429f429](https://linux-hardware.org/?probe=512429f429) | Aug 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [bf1d0a62ed](https://linux-hardware.org/?probe=bf1d0a62ed) | Aug 26, 2023 |
| MSI           | GL73 8RC                    | Notebook    | [5ca33a6111](https://linux-hardware.org/?probe=5ca33a6111) | Aug 26, 2023 |
| Acer          | Predator G9-793             | Notebook    | [531f857477](https://linux-hardware.org/?probe=531f857477) | Aug 26, 2023 |
| HP            | 802F                        | Desktop     | [6759058353](https://linux-hardware.org/?probe=6759058353) | Aug 25, 2023 |
| Dell          | 0658N7 A01                  | Server      | [0b0ac21b18](https://linux-hardware.org/?probe=0b0ac21b18) | Aug 25, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [d28f06dcc5](https://linux-hardware.org/?probe=d28f06dcc5) | Aug 25, 2023 |
| System76      | Gazelle                     | Notebook    | [ee67365e0c](https://linux-hardware.org/?probe=ee67365e0c) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [aa3157f519](https://linux-hardware.org/?probe=aa3157f519) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [8d3738c790](https://linux-hardware.org/?probe=8d3738c790) | Aug 24, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [7fdfaacf03](https://linux-hardware.org/?probe=7fdfaacf03) | Aug 24, 2023 |
| AZW           | SER                         | Mini pc     | [309bc27af7](https://linux-hardware.org/?probe=309bc27af7) | Aug 24, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [3898bac5d4](https://linux-hardware.org/?probe=3898bac5d4) | Aug 24, 2023 |
| Intel         | NUC7i7DNB J83500-204        | Mini pc     | [de9c4fce3c](https://linux-hardware.org/?probe=de9c4fce3c) | Aug 24, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [a3de2e9813](https://linux-hardware.org/?probe=a3de2e9813) | Aug 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [68d3bc88e4](https://linux-hardware.org/?probe=68d3bc88e4) | Aug 23, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6fa7d1e35d](https://linux-hardware.org/?probe=6fa7d1e35d) | Aug 23, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [799390e547](https://linux-hardware.org/?probe=799390e547) | Aug 23, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [81b8c378f7](https://linux-hardware.org/?probe=81b8c378f7) | Aug 23, 2023 |
| Dell          | G3 3579                     | Notebook    | [49b4227da5](https://linux-hardware.org/?probe=49b4227da5) | Aug 22, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [353c7bca5a](https://linux-hardware.org/?probe=353c7bca5a) | Aug 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [39fa23e4b7](https://linux-hardware.org/?probe=39fa23e4b7) | Aug 22, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b4133748fc](https://linux-hardware.org/?probe=b4133748fc) | Aug 21, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e06223da9](https://linux-hardware.org/?probe=2e06223da9) | Aug 21, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9d07a3d5c7](https://linux-hardware.org/?probe=9d07a3d5c7) | Aug 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2a468a2183](https://linux-hardware.org/?probe=2a468a2183) | Aug 21, 2023 |
| ASUSTek       | K53E                        | Notebook    | [9cce7a150e](https://linux-hardware.org/?probe=9cce7a150e) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [e6dceda4bc](https://linux-hardware.org/?probe=e6dceda4bc) | Aug 21, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [8be90f267b](https://linux-hardware.org/?probe=8be90f267b) | Aug 20, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [048ca1ce02](https://linux-hardware.org/?probe=048ca1ce02) | Aug 20, 2023 |
| Dell          | System XPS L502X            | Notebook    | [e85150614a](https://linux-hardware.org/?probe=e85150614a) | Aug 20, 2023 |
| Acer          | TravelMate P645-S           | Notebook    | [658d88e2a5](https://linux-hardware.org/?probe=658d88e2a5) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [dedf0b23a3](https://linux-hardware.org/?probe=dedf0b23a3) | Aug 19, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | Notebook    | [498c86055c](https://linux-hardware.org/?probe=498c86055c) | Aug 19, 2023 |
| Dell          | G15 5511                    | Notebook    | [8032cca2b5](https://linux-hardware.org/?probe=8032cca2b5) | Aug 19, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d7805c8232](https://linux-hardware.org/?probe=d7805c8232) | Aug 19, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | Notebook    | [7a389ac976](https://linux-hardware.org/?probe=7a389ac976) | Aug 19, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [9f5242decc](https://linux-hardware.org/?probe=9f5242decc) | Aug 19, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d8de59f346](https://linux-hardware.org/?probe=d8de59f346) | Aug 19, 2023 |
| Dell          | XPS L521X                   | Notebook    | [fdd6adb89a](https://linux-hardware.org/?probe=fdd6adb89a) | Aug 18, 2023 |
| Toshiba       | Satellite L55-B             | Notebook    | [4b2bcc2231](https://linux-hardware.org/?probe=4b2bcc2231) | Aug 18, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [3c8853c045](https://linux-hardware.org/?probe=3c8853c045) | Aug 18, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [beddeba8b6](https://linux-hardware.org/?probe=beddeba8b6) | Aug 18, 2023 |
| MSI           | Indio                       | Desktop     | [162ed509d4](https://linux-hardware.org/?probe=162ed509d4) | Aug 18, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [bee6142eee](https://linux-hardware.org/?probe=bee6142eee) | Aug 17, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [b72192373b](https://linux-hardware.org/?probe=b72192373b) | Aug 17, 2023 |
| Dell          | G3 3579                     | Notebook    | [567acf505b](https://linux-hardware.org/?probe=567acf505b) | Aug 17, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [8478931432](https://linux-hardware.org/?probe=8478931432) | Aug 17, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [3f0a5a32cf](https://linux-hardware.org/?probe=3f0a5a32cf) | Aug 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [6a2e05ff64](https://linux-hardware.org/?probe=6a2e05ff64) | Aug 17, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [0ba07cce6b](https://linux-hardware.org/?probe=0ba07cce6b) | Aug 17, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [06aebc0204](https://linux-hardware.org/?probe=06aebc0204) | Aug 17, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [79d8f79efe](https://linux-hardware.org/?probe=79d8f79efe) | Aug 17, 2023 |
| ASUSTek       | GL552JX                     | Notebook    | [9594a231bd](https://linux-hardware.org/?probe=9594a231bd) | Aug 16, 2023 |
| Dell          | Inspiron 7370               | Notebook    | [2676762739](https://linux-hardware.org/?probe=2676762739) | Aug 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [bf65b5fe16](https://linux-hardware.org/?probe=bf65b5fe16) | Aug 16, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [122b800eae](https://linux-hardware.org/?probe=122b800eae) | Aug 16, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [b288a65e53](https://linux-hardware.org/?probe=b288a65e53) | Aug 16, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [948ab98a6f](https://linux-hardware.org/?probe=948ab98a6f) | Aug 15, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [fc92556049](https://linux-hardware.org/?probe=fc92556049) | Aug 15, 2023 |
| Lenovo        | ThinkPad T490 20N2004EGE    | Notebook    | [11552492c0](https://linux-hardware.org/?probe=11552492c0) | Aug 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [2ac8f6838a](https://linux-hardware.org/?probe=2ac8f6838a) | Aug 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b53cba2654](https://linux-hardware.org/?probe=b53cba2654) | Aug 15, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [64a1b8ad5d](https://linux-hardware.org/?probe=64a1b8ad5d) | Aug 14, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [65f7a020fe](https://linux-hardware.org/?probe=65f7a020fe) | Aug 14, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [fe4612b027](https://linux-hardware.org/?probe=fe4612b027) | Aug 14, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | Desktop     | [5a3c9080d8](https://linux-hardware.org/?probe=5a3c9080d8) | Aug 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9d7d216fc0](https://linux-hardware.org/?probe=9d7d216fc0) | Aug 14, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [da00873a9d](https://linux-hardware.org/?probe=da00873a9d) | Aug 14, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [e6da28e1fb](https://linux-hardware.org/?probe=e6da28e1fb) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [a65f824e07](https://linux-hardware.org/?probe=a65f824e07) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [2da924ecb2](https://linux-hardware.org/?probe=2da924ecb2) | Aug 13, 2023 |
| Notebook      | N141CU                      | Notebook    | [06c2f33fb5](https://linux-hardware.org/?probe=06c2f33fb5) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [c28cbbd2a1](https://linux-hardware.org/?probe=c28cbbd2a1) | Aug 13, 2023 |
| Monster       | ABRA A5 V17.2               | Notebook    | [0049202ca7](https://linux-hardware.org/?probe=0049202ca7) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [6d1e3a24e8](https://linux-hardware.org/?probe=6d1e3a24e8) | Aug 13, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [2461c78ff0](https://linux-hardware.org/?probe=2461c78ff0) | Aug 13, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [3d99363ed5](https://linux-hardware.org/?probe=3d99363ed5) | Aug 13, 2023 |
| HP            | Folio 13                    | Notebook    | [62fcebde8c](https://linux-hardware.org/?probe=62fcebde8c) | Aug 13, 2023 |
| Lenovo        | ThinkPad P53s 20N6S00B00    | Notebook    | [3170e56ed1](https://linux-hardware.org/?probe=3170e56ed1) | Aug 13, 2023 |
| MSI           | Z97 GAMING 7                | Desktop     | [8414f16824](https://linux-hardware.org/?probe=8414f16824) | Aug 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [b6b99bf7bd](https://linux-hardware.org/?probe=b6b99bf7bd) | Aug 12, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [3ea3856297](https://linux-hardware.org/?probe=3ea3856297) | Aug 12, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [e65db8d147](https://linux-hardware.org/?probe=e65db8d147) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [72899a615b](https://linux-hardware.org/?probe=72899a615b) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d387c8fec5](https://linux-hardware.org/?probe=d387c8fec5) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [c90f282238](https://linux-hardware.org/?probe=c90f282238) | Aug 11, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [6f323e0954](https://linux-hardware.org/?probe=6f323e0954) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9f30f8dd0](https://linux-hardware.org/?probe=a9f30f8dd0) | Aug 11, 2023 |
| HP            | 158A                        | Desktop     | [96e7fa3b8f](https://linux-hardware.org/?probe=96e7fa3b8f) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G513QY            | Notebook    | [eacd0cc54d](https://linux-hardware.org/?probe=eacd0cc54d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [c083cb5f2f](https://linux-hardware.org/?probe=c083cb5f2f) | Aug 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [980f6773f8](https://linux-hardware.org/?probe=980f6773f8) | Aug 10, 2023 |
| Lenovo        | ThinkPad P53s 20N6S00B00    | Notebook    | [c76e31ff8e](https://linux-hardware.org/?probe=c76e31ff8e) | Aug 10, 2023 |
| HP            | Folio 13                    | Notebook    | [67121fc711](https://linux-hardware.org/?probe=67121fc711) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [025afcb20d](https://linux-hardware.org/?probe=025afcb20d) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [6f422f386f](https://linux-hardware.org/?probe=6f422f386f) | Aug 10, 2023 |
| HP            | 829A                        | Mini pc     | [ae08c868cf](https://linux-hardware.org/?probe=ae08c868cf) | Aug 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e703bb179f](https://linux-hardware.org/?probe=e703bb179f) | Aug 10, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [60cfdb5283](https://linux-hardware.org/?probe=60cfdb5283) | Aug 10, 2023 |
| HP            | Folio 13                    | Notebook    | [889aae1772](https://linux-hardware.org/?probe=889aae1772) | Aug 10, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [817c5f9f93](https://linux-hardware.org/?probe=817c5f9f93) | Aug 09, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [12e0dbd72c](https://linux-hardware.org/?probe=12e0dbd72c) | Aug 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0cf2ab49c0](https://linux-hardware.org/?probe=0cf2ab49c0) | Aug 09, 2023 |
| HP            | Compaq 15                   | Notebook    | [387a3b8af2](https://linux-hardware.org/?probe=387a3b8af2) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [e22cd6fdac](https://linux-hardware.org/?probe=e22cd6fdac) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [2242417727](https://linux-hardware.org/?probe=2242417727) | Aug 09, 2023 |
| Lenovo        | ThinkPad X240 20AL00C6UK    | Notebook    | [d33c586eab](https://linux-hardware.org/?probe=d33c586eab) | Aug 09, 2023 |
| Dell          | 073Y7Y A00                  | Desktop     | [cbf4153713](https://linux-hardware.org/?probe=cbf4153713) | Aug 09, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [ccb4eadbca](https://linux-hardware.org/?probe=ccb4eadbca) | Aug 08, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [d79ab70370](https://linux-hardware.org/?probe=d79ab70370) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5babb790d3](https://linux-hardware.org/?probe=5babb790d3) | Aug 08, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [ff4ead4bd3](https://linux-hardware.org/?probe=ff4ead4bd3) | Aug 08, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [e5a8c891d0](https://linux-hardware.org/?probe=e5a8c891d0) | Aug 08, 2023 |
| Toshiba       | Satellite C50-A510          | Notebook    | [335af4e25a](https://linux-hardware.org/?probe=335af4e25a) | Aug 08, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [3ff7f02af7](https://linux-hardware.org/?probe=3ff7f02af7) | Aug 08, 2023 |
| Insyde        | BayTrail                    | Notebook    | [df18553ec6](https://linux-hardware.org/?probe=df18553ec6) | Aug 07, 2023 |
| HP            | 8876 11                     | Desktop     | [059d4c2db2](https://linux-hardware.org/?probe=059d4c2db2) | Aug 07, 2023 |
| HP            | 158A                        | Desktop     | [657812fbbf](https://linux-hardware.org/?probe=657812fbbf) | Aug 07, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [51c3d4511a](https://linux-hardware.org/?probe=51c3d4511a) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [5e64d2b59e](https://linux-hardware.org/?probe=5e64d2b59e) | Aug 06, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [458a26f70c](https://linux-hardware.org/?probe=458a26f70c) | Aug 06, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [5a254fe1d6](https://linux-hardware.org/?probe=5a254fe1d6) | Aug 06, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [f670b492a9](https://linux-hardware.org/?probe=f670b492a9) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [35bb5f3e65](https://linux-hardware.org/?probe=35bb5f3e65) | Aug 06, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [bd989967e7](https://linux-hardware.org/?probe=bd989967e7) | Aug 06, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [597461a5ac](https://linux-hardware.org/?probe=597461a5ac) | Aug 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [48cf16e31d](https://linux-hardware.org/?probe=48cf16e31d) | Aug 06, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [e815f65a97](https://linux-hardware.org/?probe=e815f65a97) | Aug 05, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [dfc4d46266](https://linux-hardware.org/?probe=dfc4d46266) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [eb92759c2a](https://linux-hardware.org/?probe=eb92759c2a) | Aug 05, 2023 |
| Dell          | G15 5520                    | Notebook    | [baca0d14f5](https://linux-hardware.org/?probe=baca0d14f5) | Aug 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fafbd706de](https://linux-hardware.org/?probe=fafbd706de) | Aug 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [dd1767aec1](https://linux-hardware.org/?probe=dd1767aec1) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [af4f153b11](https://linux-hardware.org/?probe=af4f153b11) | Aug 04, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [c163ae3710](https://linux-hardware.org/?probe=c163ae3710) | Aug 04, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [656e917b79](https://linux-hardware.org/?probe=656e917b79) | Aug 04, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [363bee1696](https://linux-hardware.org/?probe=363bee1696) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [31d1c3bfbc](https://linux-hardware.org/?probe=31d1c3bfbc) | Aug 03, 2023 |
| HP            | 21D0                        | Desktop     | [44e0cbb52e](https://linux-hardware.org/?probe=44e0cbb52e) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7f601fe313](https://linux-hardware.org/?probe=7f601fe313) | Aug 03, 2023 |
| HP            | 21D0                        | Desktop     | [099fea9193](https://linux-hardware.org/?probe=099fea9193) | Aug 02, 2023 |
| HP            | Pavilion g7                 | Notebook    | [882d2d9a16](https://linux-hardware.org/?probe=882d2d9a16) | Aug 02, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [75c36d43c3](https://linux-hardware.org/?probe=75c36d43c3) | Aug 02, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [e391326d89](https://linux-hardware.org/?probe=e391326d89) | Aug 02, 2023 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [251b811e9b](https://linux-hardware.org/?probe=251b811e9b) | Aug 02, 2023 |
| HP            | Notebook                    | Notebook    | [258f6a82ad](https://linux-hardware.org/?probe=258f6a82ad) | Aug 02, 2023 |
| MSI           | H170M PRO-DH                | Desktop     | [e0b553c4dd](https://linux-hardware.org/?probe=e0b553c4dd) | Aug 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [eb2554dce9](https://linux-hardware.org/?probe=eb2554dce9) | Aug 02, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [451bfcf27d](https://linux-hardware.org/?probe=451bfcf27d) | Aug 02, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [79c3c3612b](https://linux-hardware.org/?probe=79c3c3612b) | Aug 02, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [19aa30337f](https://linux-hardware.org/?probe=19aa30337f) | Aug 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [589f0a8599](https://linux-hardware.org/?probe=589f0a8599) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8da287a76b](https://linux-hardware.org/?probe=8da287a76b) | Aug 01, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [26cca552dd](https://linux-hardware.org/?probe=26cca552dd) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [93d193bdbc](https://linux-hardware.org/?probe=93d193bdbc) | Aug 01, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [8aaca0803f](https://linux-hardware.org/?probe=8aaca0803f) | Jul 31, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [18924cfab7](https://linux-hardware.org/?probe=18924cfab7) | Jul 31, 2023 |
| Samsung       | 535U3C                      | Notebook    | [8d0ebb957a](https://linux-hardware.org/?probe=8d0ebb957a) | Jul 31, 2023 |
| Samsung       | 535U3C                      | Notebook    | [030fc15fac](https://linux-hardware.org/?probe=030fc15fac) | Jul 31, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [93c8724c91](https://linux-hardware.org/?probe=93c8724c91) | Jul 31, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8559f3826b](https://linux-hardware.org/?probe=8559f3826b) | Jul 31, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [04b1a06dbd](https://linux-hardware.org/?probe=04b1a06dbd) | Jul 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e66bd4564e](https://linux-hardware.org/?probe=e66bd4564e) | Jul 30, 2023 |
| Apple         | MacBookAir1,1               | Notebook    | [ac140cf8c4](https://linux-hardware.org/?probe=ac140cf8c4) | Jul 30, 2023 |
| Unknown       | HX90                        | Desktop     | [2eba30b5be](https://linux-hardware.org/?probe=2eba30b5be) | Jul 30, 2023 |
| HP            | Folio 13                    | Notebook    | [baaa648a4b](https://linux-hardware.org/?probe=baaa648a4b) | Jul 29, 2023 |
| Dell          | Latitude E6230              | Notebook    | [462496c6db](https://linux-hardware.org/?probe=462496c6db) | Jul 29, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [60bf32a368](https://linux-hardware.org/?probe=60bf32a368) | Jul 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [fb2ba2d3eb](https://linux-hardware.org/?probe=fb2ba2d3eb) | Jul 29, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [1b9bb7c266](https://linux-hardware.org/?probe=1b9bb7c266) | Jul 29, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [51d9b57967](https://linux-hardware.org/?probe=51d9b57967) | Jul 29, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [081608e70c](https://linux-hardware.org/?probe=081608e70c) | Jul 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [e8368bcae8](https://linux-hardware.org/?probe=e8368bcae8) | Jul 28, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [32fcc0f81f](https://linux-hardware.org/?probe=32fcc0f81f) | Jul 28, 2023 |
| Intel         | HM570                       | Desktop     | [c969a88e87](https://linux-hardware.org/?probe=c969a88e87) | Jul 28, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [3c0f7ba188](https://linux-hardware.org/?probe=3c0f7ba188) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [d32fa8840b](https://linux-hardware.org/?probe=d32fa8840b) | Jul 27, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [1a6962dc65](https://linux-hardware.org/?probe=1a6962dc65) | Jul 27, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [0b04075e09](https://linux-hardware.org/?probe=0b04075e09) | Jul 27, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [20221ed288](https://linux-hardware.org/?probe=20221ed288) | Jul 27, 2023 |
| Lenovo        | 3743 SDK0J40700 WIN 3258... | Desktop     | [546f011b1a](https://linux-hardware.org/?probe=546f011b1a) | Jul 27, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [ba305b3271](https://linux-hardware.org/?probe=ba305b3271) | Jul 26, 2023 |
| HP            | Folio 13                    | Notebook    | [a3269c0930](https://linux-hardware.org/?probe=a3269c0930) | Jul 26, 2023 |
| Dell          | G3 3579                     | Notebook    | [b6b50ffa46](https://linux-hardware.org/?probe=b6b50ffa46) | Jul 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [aa34907e3a](https://linux-hardware.org/?probe=aa34907e3a) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [24c092f0b0](https://linux-hardware.org/?probe=24c092f0b0) | Jul 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [a5933aa510](https://linux-hardware.org/?probe=a5933aa510) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [74adf4cb3d](https://linux-hardware.org/?probe=74adf4cb3d) | Jul 26, 2023 |
| Lenovo        | Legion R9000X 2021 82HN     | Notebook    | [0079a4e7a0](https://linux-hardware.org/?probe=0079a4e7a0) | Jul 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [7cd1c7cdf2](https://linux-hardware.org/?probe=7cd1c7cdf2) | Jul 25, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [fcb6317c1b](https://linux-hardware.org/?probe=fcb6317c1b) | Jul 25, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [7da659326d](https://linux-hardware.org/?probe=7da659326d) | Jul 24, 2023 |
| Dell          | Latitude E6230              | Notebook    | [6f832e0bb3](https://linux-hardware.org/?probe=6f832e0bb3) | Jul 24, 2023 |
| SiS Techno... | 760                         | Desktop     | [1c5bd52522](https://linux-hardware.org/?probe=1c5bd52522) | Jul 24, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [176adf0a2b](https://linux-hardware.org/?probe=176adf0a2b) | Jul 24, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4a262a2a2d](https://linux-hardware.org/?probe=4a262a2a2d) | Jul 24, 2023 |
| ASUSTek       | PN61                        | Mini pc     | [78418a9a7f](https://linux-hardware.org/?probe=78418a9a7f) | Jul 24, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [df1a812c11](https://linux-hardware.org/?probe=df1a812c11) | Jul 24, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [bd66a96c97](https://linux-hardware.org/?probe=bd66a96c97) | Jul 24, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [579d5d5771](https://linux-hardware.org/?probe=579d5d5771) | Jul 24, 2023 |
| Dell          | Latitude 5410               | Notebook    | [29261ea2bb](https://linux-hardware.org/?probe=29261ea2bb) | Jul 24, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [f9bd193456](https://linux-hardware.org/?probe=f9bd193456) | Jul 23, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1e169f0ba8](https://linux-hardware.org/?probe=1e169f0ba8) | Jul 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ae4343c245](https://linux-hardware.org/?probe=ae4343c245) | Jul 23, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [b844b9a353](https://linux-hardware.org/?probe=b844b9a353) | Jul 23, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f2f1f87d0c](https://linux-hardware.org/?probe=f2f1f87d0c) | Jul 23, 2023 |
| Dell          | Latitude 5480               | Notebook    | [0595e16f65](https://linux-hardware.org/?probe=0595e16f65) | Jul 23, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [f291f72d81](https://linux-hardware.org/?probe=f291f72d81) | Jul 23, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [c4890b8f34](https://linux-hardware.org/?probe=c4890b8f34) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [23d73ededd](https://linux-hardware.org/?probe=23d73ededd) | Jul 23, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [af255054c3](https://linux-hardware.org/?probe=af255054c3) | Jul 22, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [afc4d3c307](https://linux-hardware.org/?probe=afc4d3c307) | Jul 22, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [be58f943df](https://linux-hardware.org/?probe=be58f943df) | Jul 22, 2023 |
| HP            | 21D0                        | Desktop     | [774375de1f](https://linux-hardware.org/?probe=774375de1f) | Jul 22, 2023 |
| Dell          | Latitude E7440              | Notebook    | [ffa2aad2b5](https://linux-hardware.org/?probe=ffa2aad2b5) | Jul 21, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [f3435d221b](https://linux-hardware.org/?probe=f3435d221b) | Jul 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [516853cca9](https://linux-hardware.org/?probe=516853cca9) | Jul 21, 2023 |
| Biostar       | A320MH                      | Desktop     | [5fd84925fd](https://linux-hardware.org/?probe=5fd84925fd) | Jul 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [874f8dff98](https://linux-hardware.org/?probe=874f8dff98) | Jul 20, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d1dee26c33](https://linux-hardware.org/?probe=d1dee26c33) | Jul 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [dc0a2fb7ef](https://linux-hardware.org/?probe=dc0a2fb7ef) | Jul 20, 2023 |
| Lenovo        | 330B SDK0T76530 WIN 3556... | Mini pc     | [f7218e4043](https://linux-hardware.org/?probe=f7218e4043) | Jul 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [13a6f964eb](https://linux-hardware.org/?probe=13a6f964eb) | Jul 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c8fa0f7219](https://linux-hardware.org/?probe=c8fa0f7219) | Jul 19, 2023 |
| Dell          | Latitude 5580               | Notebook    | [6efcf73621](https://linux-hardware.org/?probe=6efcf73621) | Jul 19, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d79851836e](https://linux-hardware.org/?probe=d79851836e) | Jul 19, 2023 |
| HP            | G62                         | Notebook    | [c36d4392da](https://linux-hardware.org/?probe=c36d4392da) | Jul 19, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [56e1ff54a3](https://linux-hardware.org/?probe=56e1ff54a3) | Jul 19, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | Notebook    | [dc091872ec](https://linux-hardware.org/?probe=dc091872ec) | Jul 18, 2023 |
| Acer          | One S1003                   | Tablet      | [380ae70fb2](https://linux-hardware.org/?probe=380ae70fb2) | Jul 18, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [ef3c6c941e](https://linux-hardware.org/?probe=ef3c6c941e) | Jul 18, 2023 |
| Google        | Kip                         | Notebook    | [00dd9a1c67](https://linux-hardware.org/?probe=00dd9a1c67) | Jul 18, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [5797e88a56](https://linux-hardware.org/?probe=5797e88a56) | Jul 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [322db1cde6](https://linux-hardware.org/?probe=322db1cde6) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [f0ecaa209e](https://linux-hardware.org/?probe=f0ecaa209e) | Jul 18, 2023 |
| Dell          | Latitude 5580               | Notebook    | [16f62b67d3](https://linux-hardware.org/?probe=16f62b67d3) | Jul 17, 2023 |
| Google        | Dragonair                   | Notebook    | [11d9394545](https://linux-hardware.org/?probe=11d9394545) | Jul 17, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a83e3b42b3](https://linux-hardware.org/?probe=a83e3b42b3) | Jul 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [553cbdb79d](https://linux-hardware.org/?probe=553cbdb79d) | Jul 17, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [56a9ce9630](https://linux-hardware.org/?probe=56a9ce9630) | Jul 17, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [e46543841d](https://linux-hardware.org/?probe=e46543841d) | Jul 16, 2023 |
| Dell          | G15 5520                    | Notebook    | [ed22e67151](https://linux-hardware.org/?probe=ed22e67151) | Jul 16, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [8977d2e0a3](https://linux-hardware.org/?probe=8977d2e0a3) | Jul 16, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [19b39ef686](https://linux-hardware.org/?probe=19b39ef686) | Jul 16, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [61ed023e0c](https://linux-hardware.org/?probe=61ed023e0c) | Jul 16, 2023 |
| HP            | 8053                        | Desktop     | [bcdddcb036](https://linux-hardware.org/?probe=bcdddcb036) | Jul 15, 2023 |
| Dell          | G3 3779                     | Notebook    | [87b8ecffa4](https://linux-hardware.org/?probe=87b8ecffa4) | Jul 15, 2023 |
| Acer          | One S1003                   | Tablet      | [0e200bc1a5](https://linux-hardware.org/?probe=0e200bc1a5) | Jul 15, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [56448b6dd8](https://linux-hardware.org/?probe=56448b6dd8) | Jul 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [10946f1220](https://linux-hardware.org/?probe=10946f1220) | Jul 15, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [064a46bc1d](https://linux-hardware.org/?probe=064a46bc1d) | Jul 14, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [c56d5e4e7b](https://linux-hardware.org/?probe=c56d5e4e7b) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f1bbc61bb6](https://linux-hardware.org/?probe=f1bbc61bb6) | Jul 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0ac2423aa2](https://linux-hardware.org/?probe=0ac2423aa2) | Jul 14, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1577fae8ee](https://linux-hardware.org/?probe=1577fae8ee) | Jul 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [76513f6a7d](https://linux-hardware.org/?probe=76513f6a7d) | Jul 14, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [7816d37e02](https://linux-hardware.org/?probe=7816d37e02) | Jul 14, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [67b2bb6155](https://linux-hardware.org/?probe=67b2bb6155) | Jul 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [91145d3929](https://linux-hardware.org/?probe=91145d3929) | Jul 13, 2023 |
| Lenovo        | ThinkPad X280 20KES73S06    | Notebook    | [b301164e01](https://linux-hardware.org/?probe=b301164e01) | Jul 13, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [fa3485dbc6](https://linux-hardware.org/?probe=fa3485dbc6) | Jul 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2f943c811e](https://linux-hardware.org/?probe=2f943c811e) | Jul 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [9430a42f8b](https://linux-hardware.org/?probe=9430a42f8b) | Jul 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f73994358d](https://linux-hardware.org/?probe=f73994358d) | Jul 13, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b189eebd1c](https://linux-hardware.org/?probe=b189eebd1c) | Jul 13, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [99c9883e16](https://linux-hardware.org/?probe=99c9883e16) | Jul 12, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [85d4919b9c](https://linux-hardware.org/?probe=85d4919b9c) | Jul 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a167d41a74](https://linux-hardware.org/?probe=a167d41a74) | Jul 12, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [6e7ff15b27](https://linux-hardware.org/?probe=6e7ff15b27) | Jul 11, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [72454f0f8e](https://linux-hardware.org/?probe=72454f0f8e) | Jul 11, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [ea833bb195](https://linux-hardware.org/?probe=ea833bb195) | Jul 11, 2023 |
| HP            | Folio 13                    | Notebook    | [864b74d611](https://linux-hardware.org/?probe=864b74d611) | Jul 11, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [cc4f862316](https://linux-hardware.org/?probe=cc4f862316) | Jul 11, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [0549d09ceb](https://linux-hardware.org/?probe=0549d09ceb) | Jul 11, 2023 |
| HP            | 21D0                        | Desktop     | [a6d51a414c](https://linux-hardware.org/?probe=a6d51a414c) | Jul 11, 2023 |
| HP            | Folio 13                    | Notebook    | [35d5a3c2a3](https://linux-hardware.org/?probe=35d5a3c2a3) | Jul 11, 2023 |
| Dell          | Inspiron 7573               | Notebook    | [7cc0dc9187](https://linux-hardware.org/?probe=7cc0dc9187) | Jul 11, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [cf79171424](https://linux-hardware.org/?probe=cf79171424) | Jul 10, 2023 |
| MSI           | MS-7309                     | Desktop     | [16f6545b66](https://linux-hardware.org/?probe=16f6545b66) | Jul 10, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [ef2ca9e804](https://linux-hardware.org/?probe=ef2ca9e804) | Jul 10, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [3924343595](https://linux-hardware.org/?probe=3924343595) | Jul 10, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [61ac758cca](https://linux-hardware.org/?probe=61ac758cca) | Jul 10, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [7790bc9f7b](https://linux-hardware.org/?probe=7790bc9f7b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [ea2102a05b](https://linux-hardware.org/?probe=ea2102a05b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [655b6ba155](https://linux-hardware.org/?probe=655b6ba155) | Jul 09, 2023 |
| Intel         | H61                         | Desktop     | [11e024727c](https://linux-hardware.org/?probe=11e024727c) | Jul 09, 2023 |
| HP            | ZBook Studio x360 G5        | Convertible | [e01e0e6f7e](https://linux-hardware.org/?probe=e01e0e6f7e) | Jul 09, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [db2be54a62](https://linux-hardware.org/?probe=db2be54a62) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [ee4b75fe8e](https://linux-hardware.org/?probe=ee4b75fe8e) | Jul 09, 2023 |
| Notebook      | N141CU                      | Notebook    | [6d98546fa9](https://linux-hardware.org/?probe=6d98546fa9) | Jul 09, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [e23beb2c2a](https://linux-hardware.org/?probe=e23beb2c2a) | Jul 08, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [8ef192f620](https://linux-hardware.org/?probe=8ef192f620) | Jul 08, 2023 |
| HP            | 83E2                        | Desktop     | [7764034dad](https://linux-hardware.org/?probe=7764034dad) | Jul 08, 2023 |
| Dell          | Latitude 3380               | Notebook    | [b4403e7b15](https://linux-hardware.org/?probe=b4403e7b15) | Jul 07, 2023 |
| HP            | Folio 13                    | Notebook    | [dd1a09fa9d](https://linux-hardware.org/?probe=dd1a09fa9d) | Jul 07, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [28b2f72ea7](https://linux-hardware.org/?probe=28b2f72ea7) | Jul 07, 2023 |
| Acer          | Predator G3600              | Desktop     | [79f515acf1](https://linux-hardware.org/?probe=79f515acf1) | Jul 07, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1327d1ff3b](https://linux-hardware.org/?probe=1327d1ff3b) | Jul 07, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [dd071cd632](https://linux-hardware.org/?probe=dd071cd632) | Jul 07, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [fdb4fd8cb4](https://linux-hardware.org/?probe=fdb4fd8cb4) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e7a7107e85](https://linux-hardware.org/?probe=e7a7107e85) | Jul 07, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [7d1d71b0fe](https://linux-hardware.org/?probe=7d1d71b0fe) | Jul 06, 2023 |
| HP            | 8053                        | Desktop     | [66ee68d1ba](https://linux-hardware.org/?probe=66ee68d1ba) | Jul 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [56609b5da2](https://linux-hardware.org/?probe=56609b5da2) | Jul 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e6d6494e7a](https://linux-hardware.org/?probe=e6d6494e7a) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [cd2c46c45c](https://linux-hardware.org/?probe=cd2c46c45c) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [54a88e79d1](https://linux-hardware.org/?probe=54a88e79d1) | Jul 04, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [941c70d512](https://linux-hardware.org/?probe=941c70d512) | Jul 04, 2023 |
| CompuLab      | fitlet                      | Mini pc     | [41b26129b6](https://linux-hardware.org/?probe=41b26129b6) | Jul 04, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [075cc6eb8a](https://linux-hardware.org/?probe=075cc6eb8a) | Jul 04, 2023 |
| Dell          | Inspiron 5765               | Notebook    | [7d34d64627](https://linux-hardware.org/?probe=7d34d64627) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [bba1bf2655](https://linux-hardware.org/?probe=bba1bf2655) | Jul 04, 2023 |
| Foxconn       | H81MXV/H81MXV-D             | Desktop     | [5920f3fec9](https://linux-hardware.org/?probe=5920f3fec9) | Jul 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [5d1b3596c1](https://linux-hardware.org/?probe=5d1b3596c1) | Jul 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [3290dd955a](https://linux-hardware.org/?probe=3290dd955a) | Jul 03, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [78bdc20fe8](https://linux-hardware.org/?probe=78bdc20fe8) | Jul 03, 2023 |
| HP            | 886C                        | Desktop     | [735b488512](https://linux-hardware.org/?probe=735b488512) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b7222ef19f](https://linux-hardware.org/?probe=b7222ef19f) | Jul 03, 2023 |
| HP            | Folio 13                    | Notebook    | [faf3cb7d1f](https://linux-hardware.org/?probe=faf3cb7d1f) | Jul 03, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [f78f6977d9](https://linux-hardware.org/?probe=f78f6977d9) | Jul 03, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6ce7d33591](https://linux-hardware.org/?probe=6ce7d33591) | Jul 03, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [8120591fdf](https://linux-hardware.org/?probe=8120591fdf) | Jul 02, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e3285ce484](https://linux-hardware.org/?probe=e3285ce484) | Jul 02, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [4f24850748](https://linux-hardware.org/?probe=4f24850748) | Jul 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f341618e19](https://linux-hardware.org/?probe=f341618e19) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5a84f67b67](https://linux-hardware.org/?probe=5a84f67b67) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80810e133e](https://linux-hardware.org/?probe=80810e133e) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [48df5942cf](https://linux-hardware.org/?probe=48df5942cf) | Jul 02, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [7bdc183ddc](https://linux-hardware.org/?probe=7bdc183ddc) | Jul 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f22f547276](https://linux-hardware.org/?probe=f22f547276) | Jul 01, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d3fb700ff1](https://linux-hardware.org/?probe=d3fb700ff1) | Jul 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a559729258](https://linux-hardware.org/?probe=a559729258) | Jul 01, 2023 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [6c8a67be9e](https://linux-hardware.org/?probe=6c8a67be9e) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [10467d9f3e](https://linux-hardware.org/?probe=10467d9f3e) | Jun 30, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [3e1517b7a7](https://linux-hardware.org/?probe=3e1517b7a7) | Jun 30, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [c959833db6](https://linux-hardware.org/?probe=c959833db6) | Jun 30, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [3932620fb9](https://linux-hardware.org/?probe=3932620fb9) | Jun 30, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [a73fd92e21](https://linux-hardware.org/?probe=a73fd92e21) | Jun 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [69cb8803e1](https://linux-hardware.org/?probe=69cb8803e1) | Jun 29, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [eb31590a2c](https://linux-hardware.org/?probe=eb31590a2c) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [b8194aee09](https://linux-hardware.org/?probe=b8194aee09) | Jun 28, 2023 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [031ec94437](https://linux-hardware.org/?probe=031ec94437) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [cb40f5d060](https://linux-hardware.org/?probe=cb40f5d060) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [13ac46e7fb](https://linux-hardware.org/?probe=13ac46e7fb) | Jun 28, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [966b21f9af](https://linux-hardware.org/?probe=966b21f9af) | Jun 28, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1ef6edecef](https://linux-hardware.org/?probe=1ef6edecef) | Jun 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [98ad52d973](https://linux-hardware.org/?probe=98ad52d973) | Jun 28, 2023 |
| AZW           | GTR V02                     | Desktop     | [d8a1975328](https://linux-hardware.org/?probe=d8a1975328) | Jun 27, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9128946047](https://linux-hardware.org/?probe=9128946047) | Jun 27, 2023 |
| HP            | 2B2C                        | Desktop     | [a8ec805431](https://linux-hardware.org/?probe=a8ec805431) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [dc32791d25](https://linux-hardware.org/?probe=dc32791d25) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [adf7a275be](https://linux-hardware.org/?probe=adf7a275be) | Jun 27, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [6958b0e619](https://linux-hardware.org/?probe=6958b0e619) | Jun 27, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9e3cbeb0f5](https://linux-hardware.org/?probe=9e3cbeb0f5) | Jun 27, 2023 |
| Dell          | Latitude E6230              | Notebook    | [b52e22e663](https://linux-hardware.org/?probe=b52e22e663) | Jun 27, 2023 |
| ASRock        | G31M-S                      | Desktop     | [2437008395](https://linux-hardware.org/?probe=2437008395) | Jun 26, 2023 |
| HP            | 859B                        | Desktop     | [63fdd4ed7e](https://linux-hardware.org/?probe=63fdd4ed7e) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [13c7f88d66](https://linux-hardware.org/?probe=13c7f88d66) | Jun 26, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [b598080123](https://linux-hardware.org/?probe=b598080123) | Jun 26, 2023 |
| MSI           | GP72MVR 7RGX                | Notebook    | [7fa12ec2d8](https://linux-hardware.org/?probe=7fa12ec2d8) | Jun 26, 2023 |
| HP            | 8599                        | Desktop     | [d72522f488](https://linux-hardware.org/?probe=d72522f488) | Jun 26, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [bc4e778aa5](https://linux-hardware.org/?probe=bc4e778aa5) | Jun 26, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [ad1a470baf](https://linux-hardware.org/?probe=ad1a470baf) | Jun 26, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [3b27404402](https://linux-hardware.org/?probe=3b27404402) | Jun 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3df76bbd0e](https://linux-hardware.org/?probe=3df76bbd0e) | Jun 26, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [49172baecf](https://linux-hardware.org/?probe=49172baecf) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1a21c582de](https://linux-hardware.org/?probe=1a21c582de) | Jun 26, 2023 |
| HP            | 2B2C                        | Desktop     | [3b82186362](https://linux-hardware.org/?probe=3b82186362) | Jun 26, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [1a5d46559c](https://linux-hardware.org/?probe=1a5d46559c) | Jun 25, 2023 |
| Intel         | X99H                        | Desktop     | [60f1f4a8ba](https://linux-hardware.org/?probe=60f1f4a8ba) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [62dd78e250](https://linux-hardware.org/?probe=62dd78e250) | Jun 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [f84d78f3cf](https://linux-hardware.org/?probe=f84d78f3cf) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5679200535](https://linux-hardware.org/?probe=5679200535) | Jun 24, 2023 |
| Intel         | H61                         | Desktop     | [0f1d3e1299](https://linux-hardware.org/?probe=0f1d3e1299) | Jun 24, 2023 |
| HP            | 0A54h                       | Desktop     | [7383b90fc8](https://linux-hardware.org/?probe=7383b90fc8) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [628fca0448](https://linux-hardware.org/?probe=628fca0448) | Jun 24, 2023 |
| AZW           | GT-R                        | Notebook    | [11f032f354](https://linux-hardware.org/?probe=11f032f354) | Jun 24, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b7ac1c1ba6](https://linux-hardware.org/?probe=b7ac1c1ba6) | Jun 24, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [cafe332307](https://linux-hardware.org/?probe=cafe332307) | Jun 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [007cf1edce](https://linux-hardware.org/?probe=007cf1edce) | Jun 23, 2023 |
| HP            | 0A54h                       | Desktop     | [8cf79bc35e](https://linux-hardware.org/?probe=8cf79bc35e) | Jun 23, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [abbe9c9751](https://linux-hardware.org/?probe=abbe9c9751) | Jun 23, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [70b7839ea8](https://linux-hardware.org/?probe=70b7839ea8) | Jun 23, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [645a24c7bc](https://linux-hardware.org/?probe=645a24c7bc) | Jun 23, 2023 |
| Dell          | G5 5505                     | Notebook    | [dbe52869d7](https://linux-hardware.org/?probe=dbe52869d7) | Jun 23, 2023 |
| Dell          | Latitude E6420              | Notebook    | [162293d893](https://linux-hardware.org/?probe=162293d893) | Jun 23, 2023 |
| Dell          | G5 5505                     | Notebook    | [f435440e91](https://linux-hardware.org/?probe=f435440e91) | Jun 23, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [7f87bb5b32](https://linux-hardware.org/?probe=7f87bb5b32) | Jun 23, 2023 |
| MSI           | GL73 8RD                    | Notebook    | [2739b46bbe](https://linux-hardware.org/?probe=2739b46bbe) | Jun 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [70b047f976](https://linux-hardware.org/?probe=70b047f976) | Jun 22, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [2807f81cc7](https://linux-hardware.org/?probe=2807f81cc7) | Jun 22, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [bbdbdd30a9](https://linux-hardware.org/?probe=bbdbdd30a9) | Jun 22, 2023 |
| HP            | 2B2C                        | Desktop     | [4303d28839](https://linux-hardware.org/?probe=4303d28839) | Jun 22, 2023 |
| HP            | 802F                        | Desktop     | [da2666b4b8](https://linux-hardware.org/?probe=da2666b4b8) | Jun 22, 2023 |
| Sony          | SVE1712C1EW                 | Notebook    | [12f0ee026f](https://linux-hardware.org/?probe=12f0ee026f) | Jun 22, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [3d506cafad](https://linux-hardware.org/?probe=3d506cafad) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [69dfee1765](https://linux-hardware.org/?probe=69dfee1765) | Jun 22, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [5199a5d1f8](https://linux-hardware.org/?probe=5199a5d1f8) | Jun 22, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [198b248306](https://linux-hardware.org/?probe=198b248306) | Jun 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [6609cc4a31](https://linux-hardware.org/?probe=6609cc4a31) | Jun 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [31d17d4d65](https://linux-hardware.org/?probe=31d17d4d65) | Jun 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [8845f67824](https://linux-hardware.org/?probe=8845f67824) | Jun 22, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [eba6a24be2](https://linux-hardware.org/?probe=eba6a24be2) | Jun 21, 2023 |
| MSI           | X99A SLI Krait Edition      | Desktop     | [2e86965134](https://linux-hardware.org/?probe=2e86965134) | Jun 21, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [fd3c5ae570](https://linux-hardware.org/?probe=fd3c5ae570) | Jun 21, 2023 |
| Emdoor        | AG958                       | Notebook    | [3574f89b15](https://linux-hardware.org/?probe=3574f89b15) | Jun 21, 2023 |
| HP            | 802F                        | Desktop     | [96b020f763](https://linux-hardware.org/?probe=96b020f763) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [fc06bc7209](https://linux-hardware.org/?probe=fc06bc7209) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0a36c0985d](https://linux-hardware.org/?probe=0a36c0985d) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0ccace2cfb](https://linux-hardware.org/?probe=0ccace2cfb) | Jun 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [3e09affd03](https://linux-hardware.org/?probe=3e09affd03) | Jun 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [529320d8fe](https://linux-hardware.org/?probe=529320d8fe) | Jun 20, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [b6b7fa0f5d](https://linux-hardware.org/?probe=b6b7fa0f5d) | Jun 19, 2023 |
| MSI           | Z170A GAMING M7             | Desktop     | [49e7c6d51b](https://linux-hardware.org/?probe=49e7c6d51b) | Jun 19, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [7b370bd18c](https://linux-hardware.org/?probe=7b370bd18c) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [63381e724a](https://linux-hardware.org/?probe=63381e724a) | Jun 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [3acc831573](https://linux-hardware.org/?probe=3acc831573) | Jun 19, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [6579287940](https://linux-hardware.org/?probe=6579287940) | Jun 18, 2023 |
| Razer         | Blade Stealth 13 (Early ... | Notebook    | [e3843be450](https://linux-hardware.org/?probe=e3843be450) | Jun 18, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [928b30815b](https://linux-hardware.org/?probe=928b30815b) | Jun 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [f4cf5bef09](https://linux-hardware.org/?probe=f4cf5bef09) | Jun 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [9fe2c6961e](https://linux-hardware.org/?probe=9fe2c6961e) | Jun 18, 2023 |
| Dell          | 06JWJY A01                  | Desktop     | [2131eadb5b](https://linux-hardware.org/?probe=2131eadb5b) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [8fe751618d](https://linux-hardware.org/?probe=8fe751618d) | Jun 18, 2023 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [8385742d7d](https://linux-hardware.org/?probe=8385742d7d) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [337d8e9d36](https://linux-hardware.org/?probe=337d8e9d36) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5c365e154b](https://linux-hardware.org/?probe=5c365e154b) | Jun 17, 2023 |
| Intel         | H55                         | Desktop     | [d47f462b1a](https://linux-hardware.org/?probe=d47f462b1a) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [4907b6927a](https://linux-hardware.org/?probe=4907b6927a) | Jun 16, 2023 |
| HP            | 886C                        | Desktop     | [ef429234c7](https://linux-hardware.org/?probe=ef429234c7) | Jun 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1412c501d2](https://linux-hardware.org/?probe=1412c501d2) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [896d66d33f](https://linux-hardware.org/?probe=896d66d33f) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [b26c331bfc](https://linux-hardware.org/?probe=b26c331bfc) | Jun 16, 2023 |
| Intel         | H55                         | Desktop     | [76c89618f1](https://linux-hardware.org/?probe=76c89618f1) | Jun 16, 2023 |
| CompuLab      | fitlet                      | Mini pc     | [82c3257031](https://linux-hardware.org/?probe=82c3257031) | Jun 16, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [4448a99385](https://linux-hardware.org/?probe=4448a99385) | Jun 16, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [16ad11571a](https://linux-hardware.org/?probe=16ad11571a) | Jun 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [c612df2e8c](https://linux-hardware.org/?probe=c612df2e8c) | Jun 15, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [9c446242a8](https://linux-hardware.org/?probe=9c446242a8) | Jun 15, 2023 |
| Intel         | H61                         | Desktop     | [ac2b137243](https://linux-hardware.org/?probe=ac2b137243) | Jun 15, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [74a69e5cca](https://linux-hardware.org/?probe=74a69e5cca) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [bd74568d10](https://linux-hardware.org/?probe=bd74568d10) | Jun 15, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [175aa8aae4](https://linux-hardware.org/?probe=175aa8aae4) | Jun 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [91af63490c](https://linux-hardware.org/?probe=91af63490c) | Jun 15, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [dba6acd01e](https://linux-hardware.org/?probe=dba6acd01e) | Jun 15, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [7670492b40](https://linux-hardware.org/?probe=7670492b40) | Jun 15, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [3dd5692b24](https://linux-hardware.org/?probe=3dd5692b24) | Jun 15, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [550aa0fda6](https://linux-hardware.org/?probe=550aa0fda6) | Jun 14, 2023 |
| ASRock        | Z97 Extreme6                | Desktop     | [8f727c50fb](https://linux-hardware.org/?probe=8f727c50fb) | Jun 14, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [0e499971b7](https://linux-hardware.org/?probe=0e499971b7) | Jun 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [5349772ea1](https://linux-hardware.org/?probe=5349772ea1) | Jun 14, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [192105166b](https://linux-hardware.org/?probe=192105166b) | Jun 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [3a8338d906](https://linux-hardware.org/?probe=3a8338d906) | Jun 13, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [0b917dc778](https://linux-hardware.org/?probe=0b917dc778) | Jun 13, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [e722fda49e](https://linux-hardware.org/?probe=e722fda49e) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [bd6a04d15d](https://linux-hardware.org/?probe=bd6a04d15d) | Jun 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [6a1f1e134c](https://linux-hardware.org/?probe=6a1f1e134c) | Jun 13, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [93cd1fd89c](https://linux-hardware.org/?probe=93cd1fd89c) | Jun 13, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c3ec3eaa27](https://linux-hardware.org/?probe=c3ec3eaa27) | Jun 13, 2023 |
| Acidanther... | Mac-AF89B6D9451A490B iMa... | All in one  | [b9e0fd4223](https://linux-hardware.org/?probe=b9e0fd4223) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [58235def6c](https://linux-hardware.org/?probe=58235def6c) | Jun 12, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [1fad9d3d52](https://linux-hardware.org/?probe=1fad9d3d52) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [98a4801b23](https://linux-hardware.org/?probe=98a4801b23) | Jun 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7be8732d39](https://linux-hardware.org/?probe=7be8732d39) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [66a01fdc35](https://linux-hardware.org/?probe=66a01fdc35) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [f92739d54b](https://linux-hardware.org/?probe=f92739d54b) | Jun 11, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [2fe8080014](https://linux-hardware.org/?probe=2fe8080014) | Jun 11, 2023 |
| HP            | OMEN by Laptop 15t-en000    | Notebook    | [cdda8d0103](https://linux-hardware.org/?probe=cdda8d0103) | Jun 11, 2023 |
| HP            | 2B0D A01                    | All in one  | [b4f5677d00](https://linux-hardware.org/?probe=b4f5677d00) | Jun 11, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [a192769f1b](https://linux-hardware.org/?probe=a192769f1b) | Jun 11, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [8a07e36a48](https://linux-hardware.org/?probe=8a07e36a48) | Jun 11, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [396e828c07](https://linux-hardware.org/?probe=396e828c07) | Jun 11, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [d71e612bbb](https://linux-hardware.org/?probe=d71e612bbb) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7eda1ce433](https://linux-hardware.org/?probe=7eda1ce433) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4fcc967374](https://linux-hardware.org/?probe=4fcc967374) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [864729436a](https://linux-hardware.org/?probe=864729436a) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [07dac575d9](https://linux-hardware.org/?probe=07dac575d9) | Jun 10, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [49ebfc0459](https://linux-hardware.org/?probe=49ebfc0459) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [7ab0866235](https://linux-hardware.org/?probe=7ab0866235) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [29085f8fb4](https://linux-hardware.org/?probe=29085f8fb4) | Jun 10, 2023 |
| MSI           | MS-B9321                    | Desktop     | [a7a878dbe6](https://linux-hardware.org/?probe=a7a878dbe6) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0eae3567d9](https://linux-hardware.org/?probe=0eae3567d9) | Jun 10, 2023 |
| ASRock        | B550AM Gaming               | Desktop     | [eca79c3bbb](https://linux-hardware.org/?probe=eca79c3bbb) | Jun 10, 2023 |
| Lenovo        | ThinkPad T440 20B6005RUS    | Notebook    | [e7ea5a9368](https://linux-hardware.org/?probe=e7ea5a9368) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [5446a0003e](https://linux-hardware.org/?probe=5446a0003e) | Jun 10, 2023 |
| HP            | Notebook                    | Notebook    | [9487146a2f](https://linux-hardware.org/?probe=9487146a2f) | Jun 09, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [9b52b20f3e](https://linux-hardware.org/?probe=9b52b20f3e) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [c5accf4cf8](https://linux-hardware.org/?probe=c5accf4cf8) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [45e51a6b5d](https://linux-hardware.org/?probe=45e51a6b5d) | Jun 09, 2023 |
| HP            | 2B0D A01                    | All in one  | [84275606e0](https://linux-hardware.org/?probe=84275606e0) | Jun 09, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [c14dcffa32](https://linux-hardware.org/?probe=c14dcffa32) | Jun 08, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3f04b950e8](https://linux-hardware.org/?probe=3f04b950e8) | Jun 08, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [4614addc21](https://linux-hardware.org/?probe=4614addc21) | Jun 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [b7f109f62e](https://linux-hardware.org/?probe=b7f109f62e) | Jun 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [8d48df5869](https://linux-hardware.org/?probe=8d48df5869) | Jun 07, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [73bc5d84c9](https://linux-hardware.org/?probe=73bc5d84c9) | Jun 07, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [281be42f34](https://linux-hardware.org/?probe=281be42f34) | Jun 07, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [6eeacffa3c](https://linux-hardware.org/?probe=6eeacffa3c) | Jun 07, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [db91b1b71c](https://linux-hardware.org/?probe=db91b1b71c) | Jun 07, 2023 |
| Dell          | 06D7TR A01                  | Desktop     | [8db1a8c132](https://linux-hardware.org/?probe=8db1a8c132) | Jun 06, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [d2c05f91c4](https://linux-hardware.org/?probe=d2c05f91c4) | Jun 06, 2023 |
| HP            | 8053                        | Desktop     | [29a84ce224](https://linux-hardware.org/?probe=29a84ce224) | Jun 06, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [249f9343d0](https://linux-hardware.org/?probe=249f9343d0) | Jun 06, 2023 |
| Win elemen... | M600                        | Desktop     | [360ab80d9b](https://linux-hardware.org/?probe=360ab80d9b) | Jun 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [bdfe605b6a](https://linux-hardware.org/?probe=bdfe605b6a) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a9ea51ea77](https://linux-hardware.org/?probe=a9ea51ea77) | Jun 06, 2023 |
| Dell          | Precision 7510              | Notebook    | [2a465173d3](https://linux-hardware.org/?probe=2a465173d3) | Jun 06, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [18663e1382](https://linux-hardware.org/?probe=18663e1382) | Jun 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [38882f47af](https://linux-hardware.org/?probe=38882f47af) | Jun 05, 2023 |
| Toshiba       | Satellite L305              | Notebook    | [c11012336c](https://linux-hardware.org/?probe=c11012336c) | Jun 05, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [917462f8c8](https://linux-hardware.org/?probe=917462f8c8) | Jun 05, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [50f682ce84](https://linux-hardware.org/?probe=50f682ce84) | Jun 04, 2023 |
| SYWZ          | S200 Series                 | Desktop     | [577c490fb7](https://linux-hardware.org/?probe=577c490fb7) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [87b33e1181](https://linux-hardware.org/?probe=87b33e1181) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [9a66179aaf](https://linux-hardware.org/?probe=9a66179aaf) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a39c2e8d55](https://linux-hardware.org/?probe=a39c2e8d55) | Jun 04, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [b0efe96508](https://linux-hardware.org/?probe=b0efe96508) | Jun 04, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [6f8af3d7af](https://linux-hardware.org/?probe=6f8af3d7af) | Jun 03, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [b92c18e955](https://linux-hardware.org/?probe=b92c18e955) | Jun 03, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [5ee3eec233](https://linux-hardware.org/?probe=5ee3eec233) | Jun 03, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [46920007ed](https://linux-hardware.org/?probe=46920007ed) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 2325SLU       | Notebook    | [3a1d630346](https://linux-hardware.org/?probe=3a1d630346) | Jun 03, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [30a95a3f53](https://linux-hardware.org/?probe=30a95a3f53) | Jun 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [e28ef4a6b7](https://linux-hardware.org/?probe=e28ef4a6b7) | Jun 03, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [7837922f5b](https://linux-hardware.org/?probe=7837922f5b) | Jun 02, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [3de77b392a](https://linux-hardware.org/?probe=3de77b392a) | Jun 02, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [b4ba7702cb](https://linux-hardware.org/?probe=b4ba7702cb) | Jun 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c9e073b763](https://linux-hardware.org/?probe=c9e073b763) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [ca1bce793b](https://linux-hardware.org/?probe=ca1bce793b) | Jun 01, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [1bd92e67d7](https://linux-hardware.org/?probe=1bd92e67d7) | Jun 01, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [d75bfc397f](https://linux-hardware.org/?probe=d75bfc397f) | Jun 01, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [6b3efa1ef7](https://linux-hardware.org/?probe=6b3efa1ef7) | May 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [270fcf5e69](https://linux-hardware.org/?probe=270fcf5e69) | May 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [79de4bed98](https://linux-hardware.org/?probe=79de4bed98) | May 31, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6c814f5bb5](https://linux-hardware.org/?probe=6c814f5bb5) | May 31, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [d21f59bea5](https://linux-hardware.org/?probe=d21f59bea5) | May 31, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [9131b2b568](https://linux-hardware.org/?probe=9131b2b568) | May 31, 2023 |
| Acer          | Predator G9-793             | Notebook    | [26ea66d872](https://linux-hardware.org/?probe=26ea66d872) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [eae4d1e9ba](https://linux-hardware.org/?probe=eae4d1e9ba) | May 31, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [2ad4b7fd55](https://linux-hardware.org/?probe=2ad4b7fd55) | May 30, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6dbaa9e2ff](https://linux-hardware.org/?probe=6dbaa9e2ff) | May 30, 2023 |
| HP            | 82DC 1000                   | All in one  | [8300907fc1](https://linux-hardware.org/?probe=8300907fc1) | May 30, 2023 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [4ed64d3d45](https://linux-hardware.org/?probe=4ed64d3d45) | May 30, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [5c089f9b06](https://linux-hardware.org/?probe=5c089f9b06) | May 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [8ec80f5e43](https://linux-hardware.org/?probe=8ec80f5e43) | May 30, 2023 |
| Dell          | 002KVM A01                  | Desktop     | [09d2d63c82](https://linux-hardware.org/?probe=09d2d63c82) | May 30, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8e0413af72](https://linux-hardware.org/?probe=8e0413af72) | May 30, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [9171b7f0f0](https://linux-hardware.org/?probe=9171b7f0f0) | May 29, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [829c193554](https://linux-hardware.org/?probe=829c193554) | May 29, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [b90162f812](https://linux-hardware.org/?probe=b90162f812) | May 29, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [1aa973f6bc](https://linux-hardware.org/?probe=1aa973f6bc) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [77e5b682ff](https://linux-hardware.org/?probe=77e5b682ff) | May 28, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [04e50de864](https://linux-hardware.org/?probe=04e50de864) | May 28, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [519e04a228](https://linux-hardware.org/?probe=519e04a228) | May 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [e92f94ecb3](https://linux-hardware.org/?probe=e92f94ecb3) | May 27, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [f7f07e78d5](https://linux-hardware.org/?probe=f7f07e78d5) | May 27, 2023 |
| ASRock        | H87M Pro4                   | Desktop     | [efd2db0783](https://linux-hardware.org/?probe=efd2db0783) | May 27, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [cb642c7b9d](https://linux-hardware.org/?probe=cb642c7b9d) | May 27, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [b5fd752412](https://linux-hardware.org/?probe=b5fd752412) | May 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d5d9543a5a](https://linux-hardware.org/?probe=d5d9543a5a) | May 26, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [07ecf79e17](https://linux-hardware.org/?probe=07ecf79e17) | May 26, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [ca130b5f89](https://linux-hardware.org/?probe=ca130b5f89) | May 26, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [184afbb9c3](https://linux-hardware.org/?probe=184afbb9c3) | May 26, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [3392305134](https://linux-hardware.org/?probe=3392305134) | May 26, 2023 |
| HP            | 8437                        | Desktop     | [c1c9154683](https://linux-hardware.org/?probe=c1c9154683) | May 26, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [89b7c17d00](https://linux-hardware.org/?probe=89b7c17d00) | May 26, 2023 |
| ASUSTek       | X751LAB                     | Notebook    | [02b17f35d9](https://linux-hardware.org/?probe=02b17f35d9) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [13906a8f3d](https://linux-hardware.org/?probe=13906a8f3d) | May 26, 2023 |
| A14CR         | Unknown                     | Notebook    | [a504061244](https://linux-hardware.org/?probe=a504061244) | May 25, 2023 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [b00cde0e71](https://linux-hardware.org/?probe=b00cde0e71) | May 25, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [52e1964d2c](https://linux-hardware.org/?probe=52e1964d2c) | May 25, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [7389c979b6](https://linux-hardware.org/?probe=7389c979b6) | May 25, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [e52868c107](https://linux-hardware.org/?probe=e52868c107) | May 25, 2023 |
| Dell          | Precision 7510              | Notebook    | [8c677420fa](https://linux-hardware.org/?probe=8c677420fa) | May 25, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [1387725836](https://linux-hardware.org/?probe=1387725836) | May 24, 2023 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [e51dec5daf](https://linux-hardware.org/?probe=e51dec5daf) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c309714d15](https://linux-hardware.org/?probe=c309714d15) | May 23, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [627afe1447](https://linux-hardware.org/?probe=627afe1447) | May 23, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3d594ff1da](https://linux-hardware.org/?probe=3d594ff1da) | May 23, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a2986e9b7a](https://linux-hardware.org/?probe=a2986e9b7a) | May 23, 2023 |
| Lenovo        | ThinkPad T550 20CJS0S800    | Notebook    | [b7efa91563](https://linux-hardware.org/?probe=b7efa91563) | May 23, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [e250801798](https://linux-hardware.org/?probe=e250801798) | May 23, 2023 |
| Dell          | Precision 7510              | Notebook    | [15458a1b29](https://linux-hardware.org/?probe=15458a1b29) | May 22, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [87b976a24c](https://linux-hardware.org/?probe=87b976a24c) | May 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [5e89fe1dc9](https://linux-hardware.org/?probe=5e89fe1dc9) | May 22, 2023 |
| Lenovo        | ThinkPad T550 20CJS1V900    | Notebook    | [9bc275ef54](https://linux-hardware.org/?probe=9bc275ef54) | May 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [a1fb857bcc](https://linux-hardware.org/?probe=a1fb857bcc) | May 22, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | Notebook    | [7cba5b3595](https://linux-hardware.org/?probe=7cba5b3595) | May 22, 2023 |
| HP            | 8599                        | Desktop     | [2e9caaf13a](https://linux-hardware.org/?probe=2e9caaf13a) | May 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ab21a2a608](https://linux-hardware.org/?probe=ab21a2a608) | May 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [ef28026334](https://linux-hardware.org/?probe=ef28026334) | May 22, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [5534aabaf1](https://linux-hardware.org/?probe=5534aabaf1) | May 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [cf10c1fb13](https://linux-hardware.org/?probe=cf10c1fb13) | May 21, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [9db5706bfc](https://linux-hardware.org/?probe=9db5706bfc) | May 21, 2023 |
| ASUSTek       | X540SC                      | Notebook    | [240bb6c246](https://linux-hardware.org/?probe=240bb6c246) | May 21, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [e7a27c7429](https://linux-hardware.org/?probe=e7a27c7429) | May 21, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [2df0364d3c](https://linux-hardware.org/?probe=2df0364d3c) | May 21, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [222ebac915](https://linux-hardware.org/?probe=222ebac915) | May 21, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [bc16fc021e](https://linux-hardware.org/?probe=bc16fc021e) | May 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8f2ccf9c6d](https://linux-hardware.org/?probe=8f2ccf9c6d) | May 21, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1fdf5742d0](https://linux-hardware.org/?probe=1fdf5742d0) | May 21, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ArcoLinux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ArcoLinux Rolling     | 2112      | 91.47%  |
| ArcoLinux             | 149       | 6.45%   |
| ArcoLinux 20.6.5      | 11        | 0.48%   |
| ArcoLinux 20.7.5      | 8         | 0.35%   |
| ArcoLinux 20.3.4      | 4         | 0.17%   |
| ArcoLinux 20.3.3      | 3         | 0.13%   |
| ArcoLinux 20.2.12     | 3         | 0.13%   |
| ArcoLinux 19.12.15    | 3         | 0.13%   |
| ArcoLinux 19.07.11    | 3         | 0.13%   |
| ArcoLinux 20.1.4      | 2         | 0.09%   |
| ArcoLinux 19.02.4     | 2         | 0.09%   |
| ArcoLinux I3-v19.02.4 | 1         | 0.04%   |
| ArcoLinux 6.9.2       | 1         | 0.04%   |
| ArcoLinux 6.9.1       | 1         | 0.04%   |
| ArcoLinux 20.5.7      | 1         | 0.04%   |
| ArcoLinux 20.5.2      | 1         | 0.04%   |
| ArcoLinux 20.4.11     | 1         | 0.04%   |
| ArcoLinux 20.2.9      | 1         | 0.04%   |
| ArcoLinux 19.11.3     | 1         | 0.04%   |
| ArcoLinux 19.03.3     | 1         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ArcoLinux | 2285      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.7-arch1-1    | 48        | 1.68%   |
| 6.4.12-arch1-1    | 45        | 1.57%   |
| 6.3.8-arch1-1     | 39        | 1.36%   |
| 5.15.10-arch1-1   | 39        | 1.36%   |
| 5.13.13-arch1-1   | 38        | 1.33%   |
| 6.3.9-arch1-1     | 29        | 1.01%   |
| 6.2.11-arch1-1    | 29        | 1.01%   |
| 6.3.2-arch1-1     | 26        | 0.91%   |
| 5.16.11-arch1-1   | 26        | 0.91%   |
| 5.14.14-arch1-1   | 26        | 0.91%   |
| 6.4.11-arch1-1    | 24        | 0.84%   |
| 6.5.3-arch1-1     | 23        | 0.8%    |
| 6.2.8-arch1-1     | 23        | 0.8%    |
| 5.13.12-arch1-1   | 22        | 0.77%   |
| 6.5.5-arch1-1     | 21        | 0.73%   |
| 5.14.12-arch1-1   | 21        | 0.73%   |
| 6.5.9-arch2-1     | 20        | 0.7%    |
| 6.4.10-arch1-1    | 20        | 0.7%    |
| 6.3.3-arch1-1     | 20        | 0.7%    |
| 6.1.12-arch1-1    | 20        | 0.7%    |
| 6.5.7-arch1-1     | 19        | 0.66%   |
| 6.3.7-arch1-1     | 19        | 0.66%   |
| 6.4.11-arch2-1    | 18        | 0.63%   |
| 5.17.1-arch1-1    | 18        | 0.63%   |
| 6.3.5-arch1-1     | 17        | 0.59%   |
| 5.8.14-arch1-1    | 16        | 0.56%   |
| 5.12.13-arch1-2   | 16        | 0.56%   |
| 6.5.8-arch1-1     | 15        | 0.52%   |
| 6.3.4-arch1-1     | 15        | 0.52%   |
| 5.9.14-arch1-1    | 15        | 0.52%   |
| 5.19.13-arch1-1   | 15        | 0.52%   |
| 5.16.2-arch1-1    | 15        | 0.52%   |
| 5.12.15-arch1-1   | 15        | 0.52%   |
| 6.4.8-arch1-1     | 14        | 0.49%   |
| 6.4.12-zen1-1-zen | 14        | 0.49%   |
| 6.3.6-arch1-1     | 14        | 0.49%   |
| 6.3.1-arch2-1     | 14        | 0.49%   |
| 6.0.8-arch1-1     | 14        | 0.49%   |
| 5.15.5-arch1-1    | 14        | 0.49%   |
| 5.15.11-arch2-1   | 14        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.12  | 59        | 2.06%   |
| 5.15.7  | 59        | 2.06%   |
| 6.3.8   | 55        | 1.92%   |
| 6.4.11  | 47        | 1.64%   |
| 5.15.10 | 41        | 1.43%   |
| 5.13.13 | 38        | 1.33%   |
| 6.3.2   | 35        | 1.22%   |
| 6.3.9   | 33        | 1.15%   |
| 6.3.1   | 33        | 1.15%   |
| 6.5.5   | 32        | 1.12%   |
| 6.2.11  | 32        | 1.12%   |
| 6.5.3   | 31        | 1.08%   |
| 5.16.11 | 29        | 1.01%   |
| 6.3.3   | 28        | 0.98%   |
| 6.1.12  | 28        | 0.98%   |
| 6.2.8   | 26        | 0.91%   |
| 5.14.14 | 26        | 0.91%   |
| 6.5.9   | 25        | 0.87%   |
| 6.5.7   | 25        | 0.87%   |
| 6.3.5   | 25        | 0.87%   |
| 6.0.2   | 25        | 0.87%   |
| 5.17.1  | 25        | 0.87%   |
| 6.4.2   | 24        | 0.84%   |
| 5.14.12 | 24        | 0.84%   |
| 5.13.12 | 24        | 0.84%   |
| 6.4.3   | 23        | 0.8%    |
| 6.4.10  | 22        | 0.77%   |
| 6.3.7   | 22        | 0.77%   |
| 6.3.4   | 22        | 0.77%   |
| 6.2.10  | 22        | 0.77%   |
| 6.4.7   | 20        | 0.7%    |
| 6.0.8   | 19        | 0.66%   |
| 5.9.14  | 19        | 0.66%   |
| 5.16.2  | 19        | 0.66%   |
| 6.4.8   | 18        | 0.63%   |
| 6.4.1   | 18        | 0.63%   |
| 5.9.8   | 18        | 0.63%   |
| 5.17.5  | 18        | 0.63%   |
| 5.15.4  | 18        | 0.63%   |
| 5.12.15 | 18        | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15     | 301       | 11.05%  |
| 6.3      | 258       | 9.47%   |
| 6.1      | 241       | 8.84%   |
| 6.4      | 239       | 8.77%   |
| 5.10     | 214       | 7.85%   |
| 6.5      | 151       | 5.54%   |
| 6.2      | 149       | 5.47%   |
| 5.16     | 133       | 4.88%   |
| 5.14     | 131       | 4.81%   |
| 6.0      | 122       | 4.48%   |
| 5.13     | 110       | 4.04%   |
| 5.9      | 109       | 4%      |
| 5.12     | 107       | 3.93%   |
| 5.17     | 92        | 3.38%   |
| 5.18     | 87        | 3.19%   |
| 5.11     | 77        | 2.83%   |
| 5.19     | 72        | 2.64%   |
| 5.4      | 60        | 2.2%    |
| 5.8      | 34        | 1.25%   |
| 5.6      | 7         | 0.26%   |
| 5.7      | 6         | 0.22%   |
| 5.5      | 5         | 0.18%   |
| 5.3      | 3         | 0.11%   |
| 5.0      | 3         | 0.11%   |
| 6.3.3    | 2         | 0.07%   |
| 5.15.96  | 2         | 0.07%   |
| 4.19     | 2         | 0.07%   |
| 6.5.2    | 1         | 0.04%   |
| 6.3.0    | 1         | 0.04%   |
| 6.2.0    | 1         | 0.04%   |
| 5.2      | 1         | 0.04%   |
| 5.15.107 | 1         | 0.04%   |
| 4.20     | 1         | 0.04%   |
| 4.18     | 1         | 0.04%   |
| 4.17     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 2285      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| XFCE           | 809       | 32.79%  |
| KDE5           | 503       | 20.39%  |
| i3             | 176       | 7.13%   |
| GNOME          | 175       | 7.09%   |
| awesome        | 117       | 4.74%   |
| qtile          | 81        | 3.28%   |
| X-Cinnamon     | 67        | 2.72%   |
| bspwm          | 65        | 2.63%   |
| Hyprland       | 57        | 2.31%   |
| Cinnamon       | 56        | 2.27%   |
| xmonad         | 53        | 2.15%   |
| DWM            | 45        | 1.82%   |
| Deepin         | 33        | 1.34%   |
| LeftWM         | 32        | 1.3%    |
| Unknown        | 29        | 1.18%   |
| Budgie         | 27        | 1.09%   |
| KDE            | 25        | 1.01%   |
| LXQt           | 20        | 0.81%   |
| chadwm         | 19        | 0.77%   |
| MATE           | 16        | 0.65%   |
| i3-with-shmlog | 12        | 0.49%   |
| herbstluftwm   | 12        | 0.49%   |
| sway           | 6         | 0.24%   |
| ICEWM          | 4         | 0.16%   |
| Cutefish       | 4         | 0.16%   |
| Unity          | 3         | 0.12%   |
| spectrwm       | 3         | 0.12%   |
| openbox        | 3         | 0.12%   |
| Hypr           | 3         | 0.12%   |
| cwm            | 3         | 0.12%   |
| GNOME Classic  | 2         | 0.08%   |
| dusk           | 2         | 0.08%   |
| XFCE:GNOME:    | 1         | 0.04%   |
| river          | 1         | 0.04%   |
| Pantheon       | 1         | 0.04%   |
| jwm            | 1         | 0.04%   |
| dwm-sc         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2050      | 87.72%  |
| Wayland | 157       | 6.72%   |
| Tty     | 102       | 4.36%   |
| Unknown | 28        | 1.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1457      | 60.06%  |
| LightDM | 405       | 16.69%  |
| TDM     | 295       | 12.16%  |
| Unknown | 191       | 7.87%   |
| GDM     | 61        | 2.51%   |
| Ly      | 8         | 0.33%   |
| LXDM    | 7         | 0.29%   |
| XDM     | 1         | 0.04%   |
| SLiM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1275      | 54.96%  |
| en_GB   | 190       | 8.19%   |
| de_DE   | 108       | 4.66%   |
| en_CA   | 76        | 3.28%   |
| en_IN   | 57        | 2.46%   |
| C       | 55        | 2.37%   |
| fr_FR   | 47        | 2.03%   |
| ru_RU   | 46        | 1.98%   |
| en_AU   | 44        | 1.9%    |
| pt_BR   | 41        | 1.77%   |
| es_ES   | 35        | 1.51%   |
| it_IT   | 29        | 1.25%   |
| es_MX   | 22        | 0.95%   |
| pl_PL   | 21        | 0.91%   |
| en_ZA   | 18        | 0.78%   |
| hu_HU   | 17        | 0.73%   |
| tr_TR   | 15        | 0.65%   |
| sv_SE   | 14        | 0.6%    |
| es_AR   | 14        | 0.6%    |
| Unknown | 14        | 0.6%    |
| zh_CN   | 10        | 0.43%   |
| nl_NL   | 10        | 0.43%   |
| fr_CA   | 8         | 0.34%   |
| en_IE   | 8         | 0.34%   |
| en_DK   | 8         | 0.34%   |
| pt_PT   | 7         | 0.3%    |
| en_PH   | 7         | 0.3%    |
| en_IL   | 7         | 0.3%    |
| ru_UA   | 6         | 0.26%   |
| nl_BE   | 6         | 0.26%   |
| ja_JP   | 6         | 0.26%   |
| fi_FI   | 6         | 0.26%   |
| en_SG   | 5         | 0.22%   |
| de_CH   | 5         | 0.22%   |
| da_DK   | 5         | 0.22%   |
| nb_NO   | 4         | 0.17%   |
| fr_BE   | 4         | 0.17%   |
| es_CO   | 4         | 0.17%   |
| es_CL   | 4         | 0.17%   |
| en_HK   | 4         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1710      | 73.9%   |
| BIOS | 604       | 26.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1664      | 70.84%  |
| Btrfs    | 506       | 21.54%  |
| Overlay  | 120       | 5.11%   |
| Xfs      | 28        | 1.19%   |
| F2fs     | 18        | 0.77%   |
| Unknown  | 8         | 0.34%   |
| Reiserfs | 2         | 0.09%   |
| Jfs      | 2         | 0.09%   |
| Tmpfs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1826      | 78.61%  |
| MBR     | 318       | 13.69%  |
| Unknown | 179       | 7.71%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1750      | 73.68%  |
| Yes       | 625       | 26.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1366      | 58.75%  |
| Yes       | 959       | 41.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 462       | 20.22%  |
| Lenovo              | 385       | 16.85%  |
| Hewlett-Packard     | 258       | 11.29%  |
| Dell                | 248       | 10.85%  |
| Gigabyte Technology | 190       | 8.32%   |
| MSI                 | 172       | 7.53%   |
| Acer                | 92        | 4.03%   |
| ASRock              | 90        | 3.94%   |
| Apple               | 55        | 2.41%   |
| Intel               | 26        | 1.14%   |
| Toshiba             | 25        | 1.09%   |
| Unknown             | 22        | 0.96%   |
| Supermicro          | 18        | 0.79%   |
| Samsung Electronics | 18        | 0.79%   |
| Sony                | 12        | 0.53%   |
| HUAWEI              | 12        | 0.53%   |
| Fujitsu             | 12        | 0.53%   |
| System76            | 11        | 0.48%   |
| Razer               | 11        | 0.48%   |
| Medion              | 11        | 0.48%   |
| AZW                 | 9         | 0.39%   |
| Alienware           | 9         | 0.39%   |
| TUXEDO              | 7         | 0.31%   |
| Timi                | 7         | 0.31%   |
| Notebook            | 7         | 0.31%   |
| Chuwi               | 7         | 0.31%   |
| BESSTAR Tech        | 5         | 0.22%   |
| Pegatron            | 4         | 0.18%   |
| Packard Bell        | 4         | 0.18%   |
| Monster             | 4         | 0.18%   |
| Microsoft           | 4         | 0.18%   |
| Google              | 4         | 0.18%   |
| Foxconn             | 4         | 0.18%   |
| Biostar             | 4         | 0.18%   |
| ZOTAC               | 3         | 0.13%   |
| Schenker            | 3         | 0.13%   |
| LG Electronics      | 3         | 0.13%   |
| Huanan              | 3         | 0.13%   |
| Casper              | 3         | 0.13%   |
| Teclast             | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 28        | 1.23%   |
| ASUS TUF Gaming X570-PLUS    | 19        | 0.83%   |
| ASUS All Series              | 19        | 0.83%   |
| ASUS ROG STRIX B550-F GAMING | 13        | 0.57%   |
| MSI MS-7C37                  | 11        | 0.48%   |
| Supermicro SYS-5019A-FTN4    | 10        | 0.44%   |
| ASUS PRIME X570-P            | 10        | 0.44%   |
| MSI MS-7C91                  | 8         | 0.35%   |
| HP Pavilion Notebook         | 8         | 0.35%   |
| ASUS PRIME X470-PRO          | 8         | 0.35%   |
| MSI MS-7C02                  | 7         | 0.31%   |
| MSI MS-7B89                  | 7         | 0.31%   |
| MSI MS-7B79                  | 7         | 0.31%   |
| HP Notebook                  | 7         | 0.31%   |
| Gigabyte X570 AORUS MASTER   | 7         | 0.31%   |
| Dell OptiPlex 7010           | 7         | 0.31%   |
| ASUS PRIME A320M-K           | 7         | 0.31%   |
| MSI MS-7A38                  | 6         | 0.26%   |
| HP Laptop 15s-eq2xxx         | 6         | 0.26%   |
| Gigabyte X570 AORUS ELITE    | 6         | 0.26%   |
| Dell OptiPlex 9010           | 6         | 0.26%   |
| ASRock B450M Pro4            | 6         | 0.26%   |
| Razer Blade                  | 5         | 0.22%   |
| MSI MS-7C95                  | 5         | 0.22%   |
| MSI MS-7971                  | 5         | 0.22%   |
| HP Laptop 15-da0xxx          | 5         | 0.22%   |
| Gigabyte X570 GAMING X       | 5         | 0.22%   |
| Gigabyte X570 AORUS PRO WIFI | 5         | 0.22%   |
| Gigabyte B450M DS3H V2       | 5         | 0.22%   |
| Gigabyte B450 AORUS ELITE    | 5         | 0.22%   |
| Dell XPS 15 9560             | 5         | 0.22%   |
| Dell OptiPlex 9020           | 5         | 0.22%   |
| AZW SER                      | 5         | 0.22%   |
| ASUS Z170 PRO GAMING         | 5         | 0.22%   |
| ASUS ROG CROSSHAIR VIII HERO | 5         | 0.22%   |
| ASUS PRIME B450M-A           | 5         | 0.22%   |
| ASUS M5A78L-M/USB3           | 5         | 0.22%   |
| MSI MS-7C56                  | 4         | 0.18%   |
| MSI MS-7B98                  | 4         | 0.18%   |
| MSI MS-7B86                  | 4         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 182       | 7.96%   |
| ASUS ROG                  | 84        | 3.68%   |
| ASUS PRIME                | 82        | 3.59%   |
| Lenovo IdeaPad            | 80        | 3.5%    |
| Dell Inspiron             | 71        | 3.11%   |
| Dell Latitude             | 55        | 2.41%   |
| ASUS TUF                  | 52        | 2.28%   |
| Acer Aspire               | 52        | 2.28%   |
| HP Pavilion               | 48        | 2.1%    |
| Dell OptiPlex             | 39        | 1.71%   |
| HP Laptop                 | 35        | 1.53%   |
| ASUS VivoBook             | 35        | 1.53%   |
| Dell XPS                  | 34        | 1.49%   |
| Lenovo Legion             | 33        | 1.44%   |
| HP EliteBook              | 30        | 1.31%   |
| Unknown                   | 28        | 1.23%   |
| Gigabyte X570             | 26        | 1.14%   |
| Toshiba Satellite         | 21        | 0.92%   |
| Dell Precision            | 21        | 0.92%   |
| HP ENVY                   | 20        | 0.88%   |
| ASUS All                  | 19        | 0.83%   |
| Lenovo Yoga               | 16        | 0.7%    |
| Lenovo ThinkCentre        | 15        | 0.66%   |
| Gigabyte B450M            | 15        | 0.66%   |
| Acer Nitro                | 14        | 0.61%   |
| Dell Vostro               | 13        | 0.57%   |
| HP OMEN                   | 12        | 0.53%   |
| ASUS ASUS                 | 12        | 0.53%   |
| MSI MS-7C37               | 11        | 0.48%   |
| HP EliteDesk              | 11        | 0.48%   |
| HP Compaq                 | 11        | 0.48%   |
| Gigabyte B450             | 11        | 0.48%   |
| ASRock B450M              | 11        | 0.48%   |
| Supermicro SYS-5019A-FTN4 | 10        | 0.44%   |
| Razer Blade               | 10        | 0.44%   |
| HP ProDesk                | 10        | 0.44%   |
| HP ProBook                | 10        | 0.44%   |
| ASUS ZenBook              | 10        | 0.44%   |
| Acer Predator             | 10        | 0.44%   |
| HP ZBook                  | 9         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 296       | 12.95%  |
| 2019    | 295       | 12.91%  |
| 2018    | 286       | 12.52%  |
| 2021    | 197       | 8.62%   |
| 2017    | 192       | 8.4%    |
| 2013    | 144       | 6.3%    |
| 2016    | 133       | 5.82%   |
| 2012    | 132       | 5.78%   |
| 2015    | 119       | 5.21%   |
| 2011    | 119       | 5.21%   |
| 2014    | 114       | 4.99%   |
| 2022    | 90        | 3.94%   |
| 2010    | 74        | 3.24%   |
| 2009    | 28        | 1.23%   |
| 2008    | 26        | 1.14%   |
| 2023    | 20        | 0.88%   |
| 2007    | 11        | 0.48%   |
| 2006    | 6         | 0.26%   |
| 2005    | 1         | 0.04%   |
| 2004    | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1178      | 51.55%  |
| Desktop     | 982       | 42.98%  |
| Convertible | 50        | 2.19%   |
| Mini pc     | 36        | 1.58%   |
| All in one  | 23        | 1.01%   |
| Tablet      | 9         | 0.39%   |
| Server      | 6         | 0.26%   |
| Stick pc    | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2282      | 99.87%  |
| Enabled  | 3         | 0.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2276      | 99.61%  |
| Yes  | 9         | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 619       | 26.73%  |
| 4.01-8.0        | 519       | 22.41%  |
| 8.01-16.0       | 402       | 17.36%  |
| 32.01-64.0      | 378       | 16.32%  |
| 3.01-4.0        | 199       | 8.59%   |
| 64.01-256.0     | 103       | 4.45%   |
| 24.01-32.0      | 61        | 2.63%   |
| 1.01-2.0        | 24        | 1.04%   |
| 2.01-3.0        | 9         | 0.39%   |
| More than 256.0 | 1         | 0.04%   |
| Unknown         | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 804       | 30.8%   |
| 2.01-3.0   | 649       | 24.87%  |
| 4.01-8.0   | 415       | 15.9%   |
| 3.01-4.0   | 385       | 14.75%  |
| 0.51-1.0   | 197       | 7.55%   |
| 8.01-16.0  | 118       | 4.52%   |
| 0.01-0.5   | 28        | 1.07%   |
| 16.01-24.0 | 12        | 0.46%   |
| 24.01-32.0 | 1         | 0.04%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1095      | 46.07%  |
| 2      | 689       | 28.99%  |
| 3      | 279       | 11.74%  |
| 4      | 158       | 6.65%   |
| 5      | 83        | 3.49%   |
| 6      | 35        | 1.47%   |
| 7      | 16        | 0.67%   |
| 0      | 6         | 0.25%   |
| 9      | 5         | 0.21%   |
| 8      | 4         | 0.17%   |
| 11     | 3         | 0.13%   |
| 10     | 2         | 0.08%   |
| 21     | 1         | 0.04%   |
| 19     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1722      | 74.97%  |
| Yes       | 575       | 25.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2008      | 87.53%  |
| No        | 286       | 12.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1746      | 76.08%  |
| No        | 549       | 23.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1597      | 68.87%  |
| No        | 722       | 31.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 506       | 22.01%  |
| Germany      | 170       | 7.39%   |
| UK           | 135       | 5.87%   |
| Canada       | 103       | 4.48%   |
| India        | 89        | 3.87%   |
| Brazil       | 85        | 3.7%    |
| France       | 68        | 2.96%   |
| Russia       | 60        | 2.61%   |
| Spain        | 58        | 2.52%   |
| Italy        | 51        | 2.22%   |
| Belgium      | 51        | 2.22%   |
| Australia    | 50        | 2.17%   |
| Netherlands  | 47        | 2.04%   |
| Turkey       | 44        | 1.91%   |
| Sweden       | 43        | 1.87%   |
| Poland       | 41        | 1.78%   |
| Mexico       | 35        | 1.52%   |
| Hungary      | 28        | 1.22%   |
| Romania      | 26        | 1.13%   |
| Argentina    | 26        | 1.13%   |
| Switzerland  | 24        | 1.04%   |
| Norway       | 23        | 1%      |
| Indonesia    | 22        | 0.96%   |
| Finland      | 20        | 0.87%   |
| Ukraine      | 19        | 0.83%   |
| South Africa | 19        | 0.83%   |
| Portugal     | 19        | 0.83%   |
| Greece       | 18        | 0.78%   |
| Austria      | 18        | 0.78%   |
| Czechia      | 17        | 0.74%   |
| Bulgaria     | 17        | 0.74%   |
| Denmark      | 15        | 0.65%   |
| Colombia     | 14        | 0.61%   |
| China        | 14        | 0.61%   |
| Malaysia     | 12        | 0.52%   |
| Japan        | 12        | 0.52%   |
| Ireland      | 12        | 0.52%   |
| Bangladesh   | 12        | 0.52%   |
| Philippines  | 11        | 0.48%   |
| Egypt        | 11        | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sydney            | 23        | 0.94%   |
| Berlin            | 23        | 0.94%   |
| Istanbul          | 19        | 0.78%   |
| Durham            | 17        | 0.69%   |
| Madrid            | 16        | 0.65%   |
| Toronto           | 14        | 0.57%   |
| Paris             | 14        | 0.57%   |
| Moscow            | 13        | 0.53%   |
| Warsaw            | 12        | 0.49%   |
| Vienna            | 12        | 0.49%   |
| Sao Paulo         | 12        | 0.49%   |
| New York          | 12        | 0.49%   |
| Amsterdam         | 12        | 0.49%   |
| Stockholm         | 11        | 0.45%   |
| Pune              | 11        | 0.45%   |
| Lier              | 11        | 0.45%   |
| Houston           | 11        | 0.45%   |
| Helsinki          | 11        | 0.45%   |
| Budapest          | 11        | 0.45%   |
| Rio de Janeiro    | 10        | 0.41%   |
| London            | 10        | 0.41%   |
| Bengaluru         | 10        | 0.41%   |
| Atlanta           | 10        | 0.41%   |
| Portland          | 9         | 0.37%   |
| Oslo              | 9         | 0.37%   |
| Los Angeles       | 9         | 0.37%   |
| Frankfurt am Main | 9         | 0.37%   |
| Tehran            | 8         | 0.33%   |
| St Petersburg     | 8         | 0.33%   |
| Sofia             | 8         | 0.33%   |
| Prague            | 8         | 0.33%   |
| Milan             | 8         | 0.33%   |
| Melbourne         | 8         | 0.33%   |
| Chicago           | 8         | 0.33%   |
| Brooklyn          | 8         | 0.33%   |
| Brisbane          | 8         | 0.33%   |
| Athens            | 8         | 0.33%   |
| Zurich            | 7         | 0.29%   |
| Wilrijk           | 7         | 0.29%   |
| Tallinn           | 7         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 745       | 1310   | 18.73%  |
| WDC                         | 585       | 984    | 14.71%  |
| Seagate                     | 497       | 771    | 12.49%  |
| Sandisk                     | 229       | 289    | 5.76%   |
| Toshiba                     | 227       | 293    | 5.71%   |
| Kingston                    | 209       | 311    | 5.25%   |
| Crucial                     | 161       | 231    | 4.05%   |
| SK hynix                    | 108       | 142    | 2.71%   |
| Intel                       | 102       | 150    | 2.56%   |
| Unknown                     | 77        | 113    | 1.94%   |
| Hitachi                     | 77        | 89     | 1.94%   |
| A-DATA Technology           | 64        | 81     | 1.61%   |
| Phison Electronics          | 52        | 76     | 1.31%   |
| Micron Technology           | 50        | 58     | 1.26%   |
| HGST                        | 50        | 67     | 1.26%   |
| Micron/Crucial Technology   | 38        | 51     | 0.96%   |
| Silicon Motion              | 35        | 44     | 0.88%   |
| Apple                       | 35        | 51     | 0.88%   |
| PNY                         | 34        | 48     | 0.85%   |
| KIOXIA                      | 30        | 36     | 0.75%   |
| China                       | 29        | 45     | 0.73%   |
| Phison                      | 28        | 45     | 0.7%    |
| Kingston Technology Company | 28        | 38     | 0.7%    |
| JMicron Technology          | 26        | 29     | 0.65%   |
| SPCC                        | 24        | 30     | 0.6%    |
| Corsair                     | 19        | 37     | 0.48%   |
| LITEON                      | 16        | 21     | 0.4%    |
| Hewlett-Packard             | 16        | 20     | 0.4%    |
| Realtek Semiconductor       | 15        | 18     | 0.38%   |
| SABRENT                     | 14        | 17     | 0.35%   |
| Patriot                     | 14        | 24     | 0.35%   |
| ADATA Technology            | 14        | 15     | 0.35%   |
| Transcend                   | 13        | 17     | 0.33%   |
| Gigabyte Technology         | 13        | 17     | 0.33%   |
| OCZ                         | 12        | 15     | 0.3%    |
| XPG                         | 11        | 14     | 0.28%   |
| Plextor                     | 11        | 12     | 0.28%   |
| LITEONIT                    | 11        | 11     | 0.28%   |
| Intenso                     | 11        | 18     | 0.28%   |
| Lexar                       | 9         | 9      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 112       | 2.47%   |
| Samsung SSD 860 EVO 500GB                             | 56        | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 55        | 1.21%   |
| Kingston SA400S37240G 240GB SSD                       | 50        | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB                        | 46        | 1.01%   |
| Samsung SSD 850 EVO 250GB                             | 43        | 0.95%   |
| Crucial CT1000MX500SSD1 1TB                           | 36        | 0.79%   |
| Toshiba MQ01ABD100 1TB                                | 34        | 0.75%   |
| Samsung SSD 860 EVO 1TB                               | 33        | 0.73%   |
| Kingston SA400S37480G 480GB SSD                       | 33        | 0.73%   |
| Seagate ST1000DM010-2EP102 1TB                        | 31        | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 28        | 0.62%   |
| Samsung SSD 850 EVO 500GB                             | 28        | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB                        | 27        | 0.6%    |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 27        | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB   | 25        | 0.55%   |
| Samsung SSD 860 EVO 250GB                             | 24        | 0.53%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 23        | 0.51%   |
| Samsung SSD 970 EVO Plus 500GB                        | 23        | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB                          | 23        | 0.51%   |
| Toshiba MQ04ABF100 1TB                                | 22        | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 22        | 0.49%   |
| Kingston SA400S37120G 120GB SSD                       | 21        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                          | 21        | 0.46%   |
| Samsung SSD 870 EVO 1TB                               | 20        | 0.44%   |
| Unknown SD/MMC/MS PRO 16GB                            | 19        | 0.42%   |
| Toshiba DT01ACA100 1TB                                | 19        | 0.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 19        | 0.42%   |
| Seagate ST2000DM001-1ER164 2TB                        | 19        | 0.42%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 19        | 0.42%   |
| Phison E12 NVMe Controller 1TB                        | 19        | 0.42%   |
| JMicron Generic 256GB                                 | 18        | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 17        | 0.37%   |
| Crucial CT240BX500SSD1 240GB                          | 17        | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 16        | 0.35%   |
| Toshiba HDWD110 1TB                                   | 16        | 0.35%   |
| Seagate Expansion 1TB                                 | 16        | 0.35%   |
| Phison E16 PCIe4 NVMe Controller 500GB                | 16        | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB                        | 15        | 0.33%   |
| Samsung SSD 980 1TB                                   | 15        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 482       | 736    | 36.6%   |
| WDC                 | 422       | 718    | 32.04%  |
| Toshiba             | 162       | 211    | 12.3%   |
| Hitachi             | 77        | 89     | 5.85%   |
| HGST                | 49        | 65     | 3.72%   |
| Samsung Electronics | 47        | 69     | 3.57%   |
| Unknown             | 21        | 29     | 1.59%   |
| Apple               | 11        | 19     | 0.84%   |
| Maxtor              | 6         | 8      | 0.46%   |
| External            | 5         | 9      | 0.38%   |
| SSK                 | 4         | 4      | 0.3%    |
| Hewlett-Packard     | 4         | 5      | 0.3%    |
| ASMT                | 4         | 8      | 0.3%    |
| Fujitsu             | 3         | 3      | 0.23%   |
| USB3.0              | 2         | 3      | 0.15%   |
| LaCie               | 2         | 2      | 0.15%   |
| Intenso             | 2         | 2      | 0.15%   |
| Fantom              | 2         | 5      | 0.15%   |
| ASMedia             | 2         | 3      | 0.15%   |
| WD MediaMax         | 1         | 1      | 0.08%   |
| RSH-319             | 1         | 1      | 0.08%   |
| Maxone              | 1         | 1      | 0.08%   |
| KESU                | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 3      | 0.08%   |
| HGST HUS            | 1         | 1      | 0.08%   |
| HGST HTS            | 1         | 1      | 0.08%   |
| H/W                 | 1         | 12     | 0.08%   |
| ExcelStor           | 1         | 2      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 387       | 646    | 26.45%  |
| Kingston            | 169       | 242    | 11.55%  |
| Crucial             | 144       | 200    | 9.84%   |
| WDC                 | 122       | 172    | 8.34%   |
| SanDisk             | 116       | 140    | 7.93%   |
| A-DATA Technology   | 46        | 61     | 3.14%   |
| PNY                 | 33        | 44     | 2.26%   |
| SK hynix            | 31        | 49     | 2.12%   |
| China               | 29        | 45     | 1.98%   |
| Toshiba             | 25        | 33     | 1.71%   |
| Intel               | 25        | 34     | 1.71%   |
| Micron Technology   | 22        | 26     | 1.5%    |
| Apple               | 22        | 24     | 1.5%    |
| SPCC                | 20        | 24     | 1.37%   |
| Patriot             | 14        | 24     | 0.96%   |
| LITEON              | 13        | 18     | 0.89%   |
| Transcend           | 12        | 16     | 0.82%   |
| OCZ                 | 12        | 15     | 0.82%   |
| SABRENT             | 11        | 14     | 0.75%   |
| LITEONIT            | 11        | 11     | 0.75%   |
| Hewlett-Packard     | 10        | 13     | 0.68%   |
| Plextor             | 9         | 10     | 0.62%   |
| Intenso             | 9         | 16     | 0.62%   |
| Team                | 8         | 9      | 0.55%   |
| Lexar               | 8         | 8      | 0.55%   |
| Corsair             | 8         | 18     | 0.55%   |
| Gigabyte Technology | 7         | 8      | 0.48%   |
| Seagate             | 6         | 9      | 0.41%   |
| KingSpec            | 6         | 6      | 0.41%   |
| GOODRAM             | 6         | 10     | 0.41%   |
| TO Exter            | 5         | 5      | 0.34%   |
| Mushkin             | 5         | 8      | 0.34%   |
| Apacer              | 5         | 5      | 0.34%   |
| Verbatim            | 4         | 5      | 0.27%   |
| HS-SSD-C100         | 4         | 5      | 0.27%   |
| ASMT                | 4         | 4      | 0.27%   |
| Acer                | 4         | 4      | 0.27%   |
| Unknown             | 4         | 4      | 0.27%   |
| Unknown             | 3         | 3      | 0.21%   |
| T-FORCE             | 3         | 3      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1184      | 2101   | 34.46%  |
| HDD     | 1084      | 2012   | 31.55%  |
| NVMe    | 1080      | 1728   | 31.43%  |
| MMC     | 53        | 76     | 1.54%   |
| Unknown | 35        | 49     | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1692      | 3844   | 55.82%  |
| NVMe | 1068      | 1699   | 35.24%  |
| SAS  | 218       | 347    | 7.19%   |
| MMC  | 53        | 76     | 1.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1186      | 2075   | 48.23%  |
| 0.51-1.0   | 835       | 1261   | 33.96%  |
| 1.01-2.0   | 257       | 462    | 10.45%  |
| 3.01-4.0   | 75        | 126    | 3.05%   |
| 2.01-3.0   | 51        | 78     | 2.07%   |
| 4.01-10.0  | 49        | 101    | 1.99%   |
| 10.01-20.0 | 6         | 10     | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 502       | 20.42%  |
| 251-500        | 495       | 20.14%  |
| 501-1000       | 392       | 15.95%  |
| More than 3000 | 312       | 12.69%  |
| 1001-2000      | 303       | 12.33%  |
| 2001-3000      | 108       | 4.39%   |
| 1-20           | 105       | 4.27%   |
| Unknown        | 105       | 4.27%   |
| 51-100         | 94        | 3.82%   |
| 21-50          | 42        | 1.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 646       | 25.05%  |
| 21-50          | 462       | 17.91%  |
| 101-250        | 384       | 14.89%  |
| 51-100         | 285       | 11.05%  |
| 251-500        | 249       | 9.65%   |
| 501-1000       | 202       | 7.83%   |
| 1001-2000      | 126       | 4.89%   |
| Unknown        | 105       | 4.07%   |
| More than 3000 | 69        | 2.68%   |
| 2001-3000      | 49        | 1.9%    |
| 0              | 2         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Computers | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                                        | 12        | 16     | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                            | 11        | 11     | 2.24%   |
| Seagate ST1000LM035-1RK172 1TB                                | 8         | 9      | 1.63%   |
| Samsung Electronics SSD 870 EVO 1TB                           | 8         | 12     | 1.63%   |
| Toshiba MQ01ABF050 500GB                                      | 7         | 7      | 1.43%   |
| Seagate ST9320325AS 320GB                                     | 6         | 8      | 1.22%   |
| Seagate ST3500413AS 500GB                                     | 6         | 7      | 1.22%   |
| Seagate ST1000DM003-1CH162 1TB                                | 6         | 8      | 1.22%   |
| Seagate ST31000528AS 1TB                                      | 5         | 5      | 1.02%   |
| Seagate ST1000DM003-9YN162 1TB                                | 5         | 5      | 1.02%   |
| Hitachi HTS547575A9E384 752GB                                 | 5         | 5      | 1.02%   |
| WDC WD20EARS-00MVWB0 2TB                                      | 4         | 8      | 0.81%   |
| Seagate ST9500325AS 500GB                                     | 4         | 4      | 0.81%   |
| Seagate ST500LT012-1DG142 500GB                               | 4         | 4      | 0.81%   |
| Seagate ST2000DM001-1ER164 2TB                                | 4         | 10     | 0.81%   |
| SanDisk SSD PLUS 1000GB                                       | 4         | 5      | 0.81%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 5      | 0.81%   |
| Hitachi HDS721010CLA332 1TB                                   | 4         | 5      | 0.81%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                              | 3         | 3      | 0.61%   |
| Toshiba DT01ACA100 1TB                                        | 3         | 5      | 0.61%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                          | 3         | 3      | 0.61%   |
| Seagate ST500LM021-1KJ152 500GB                               | 3         | 3      | 0.61%   |
| Seagate ST500DM002-1BD142 500GB                               | 3         | 3      | 0.61%   |
| Seagate ST3500312CS 500GB                                     | 3         | 5      | 0.61%   |
| Seagate ST31000524AS 1TB                                      | 3         | 3      | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB                                | 3         | 6      | 0.61%   |
| Seagate ST1000LM014-1EJ164 1TB                                | 3         | 3      | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB                                | 3         | 4      | 0.61%   |
| Samsung Electronics SSD 850 EVO 250GB                         | 3         | 4      | 0.61%   |
| Maxtor STM3250310AS 250GB                                     | 3         | 4      | 0.61%   |
| Hitachi HDS721050CLA662 500GB                                 | 3         | 4      | 0.61%   |
| HGST HTS725050A7E630 500GB                                    | 3         | 4      | 0.61%   |
| Apple HDD HTS545050A7E362 500GB                               | 3         | 3      | 0.61%   |
| WDC WDS500G1X0E-00AFY0 500GB                                  | 2         | 2      | 0.41%   |
| WDC WD6400AAKS-22A7B2 640GB                                   | 2         | 3      | 0.41%   |
| WDC WD5000AAKX-75U6AA0 500GB                                  | 2         | 3      | 0.41%   |
| WDC WD5000AAKX-603CA0 500GB                                   | 2         | 6      | 0.41%   |
| WDC WD5000AAKX-00ERMA0 500GB                                  | 2         | 2      | 0.41%   |
| WDC WD5000AAKX-001CA0 500GB                                   | 2         | 3      | 0.41%   |
| WDC WD40EFRX-68N32N0 4TB                                      | 2         | 6      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 124       | 158    | 26.44%  |
| WDC                       | 108       | 169    | 23.03%  |
| Samsung Electronics       | 41        | 58     | 8.74%   |
| Toshiba                   | 37        | 47     | 7.89%   |
| Hitachi                   | 29        | 33     | 6.18%   |
| HGST                      | 15        | 20     | 3.2%    |
| Intel                     | 13        | 20     | 2.77%   |
| SanDisk                   | 11        | 12     | 2.35%   |
| Kingston                  | 11        | 15     | 2.35%   |
| SK hynix                  | 9         | 10     | 1.92%   |
| Crucial                   | 8         | 9      | 1.71%   |
| Micron Technology         | 5         | 8      | 1.07%   |
| Maxtor                    | 5         | 7      | 1.07%   |
| A-DATA Technology         | 5         | 6      | 1.07%   |
| Hewlett-Packard           | 4         | 4      | 0.85%   |
| Corsair                   | 4         | 14     | 0.85%   |
| Transcend                 | 3         | 3      | 0.64%   |
| China                     | 3         | 4      | 0.64%   |
| Apple                     | 3         | 3      | 0.64%   |
| Realtek Semiconductor     | 2         | 2      | 0.43%   |
| Micron/Crucial Technology | 2         | 4      | 0.43%   |
| LITEONIT                  | 2         | 2      | 0.43%   |
| Drevo                     | 2         | 2      | 0.43%   |
| Colorful                  | 2         | 3      | 0.43%   |
| ASMedia                   | 2         | 3      | 0.43%   |
| Unknown                   | 2         | 2      | 0.43%   |
| XPG                       | 1         | 1      | 0.21%   |
| USB3.0                    | 1         | 2      | 0.21%   |
| Team                      | 1         | 1      | 0.21%   |
| Super Talent              | 1         | 1      | 0.21%   |
| SSSTC                     | 1         | 1      | 0.21%   |
| SPCC                      | 1         | 1      | 0.21%   |
| Silicon Motion            | 1         | 1      | 0.21%   |
| Plextor                   | 1         | 1      | 0.21%   |
| Patriot                   | 1         | 1      | 0.21%   |
| Mushkin                   | 1         | 1      | 0.21%   |
| Lenovo                    | 1         | 1      | 0.21%   |
| LaCie                     | 1         | 1      | 0.21%   |
| JMicron Technology        | 1         | 1      | 0.21%   |
| Inateck                   | 1         | 1      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 124       | 158    | 36.9%   |
| WDC                 | 103       | 161    | 30.65%  |
| Toshiba             | 34        | 43     | 10.12%  |
| Hitachi             | 29        | 33     | 8.63%   |
| HGST                | 15        | 20     | 4.46%   |
| Samsung Electronics | 14        | 17     | 4.17%   |
| Maxtor              | 5         | 7      | 1.49%   |
| Apple               | 3         | 3      | 0.89%   |
| Hewlett-Packard     | 2         | 2      | 0.6%    |
| ASMedia             | 2         | 3      | 0.6%    |
| USB3.0              | 1         | 2      | 0.3%    |
| LaCie               | 1         | 1      | 0.3%    |
| HGST HTS            | 1         | 1      | 0.3%    |
| Fujitsu             | 1         | 1      | 0.3%    |
| Unknown             | 1         | 1      | 0.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 311       | 453    | 70.2%   |
| SSD  | 103       | 143    | 23.25%  |
| NVMe | 29        | 40     | 6.55%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                  | 2         | 2      | 16.67%  |
| WDC WD5000AAKX-001CA0 500GB                      | 1         | 1      | 8.33%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 8.33%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 8.33%   |
| Seagate ST32000641AS 2TB                         | 1         | 2      | 8.33%   |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 8.33%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 8.33%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 33.33%  |
| Samsung Electronics | 4         | 4      | 33.33%  |
| WDC                 | 2         | 2      | 16.67%  |
| HGST                | 2         | 2      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1918      | 4512   | 68.87%  |
| Malfunc  | 429       | 636    | 15.4%   |
| Detected | 426       | 805    | 15.3%   |
| Failed   | 12        | 13     | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1430      | 43.18%  |
| AMD                              | 592       | 17.87%  |
| Samsung Electronics              | 420       | 12.68%  |
| SanDisk                          | 182       | 5.5%    |
| Phison Electronics               | 98        | 2.96%   |
| SK hynix                         | 78        | 2.36%   |
| Kingston Technology Company      | 73        | 2.2%    |
| ASMedia Technology               | 58        | 1.75%   |
| Micron/Crucial Technology        | 57        | 1.72%   |
| Silicon Motion                   | 41        | 1.24%   |
| Toshiba America Info Systems     | 37        | 1.12%   |
| KIOXIA                           | 35        | 1.06%   |
| Marvell Technology Group         | 34        | 1.03%   |
| ADATA Technology                 | 32        | 0.97%   |
| Micron Technology                | 30        | 0.91%   |
| Realtek Semiconductor            | 22        | 0.66%   |
| Nvidia                           | 16        | 0.48%   |
| Seagate Technology               | 11        | 0.33%   |
| JMicron Technology               | 11        | 0.33%   |
| Union Memory (Shenzhen)          | 9         | 0.27%   |
| Lite-On Technology               | 7         | 0.21%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.18%   |
| Shenzhen Longsys Electronics     | 4         | 0.12%   |
| Lenovo                           | 3         | 0.09%   |
| INNOGRIT                         | 3         | 0.09%   |
| Apple                            | 3         | 0.09%   |
| VIA Technologies                 | 2         | 0.06%   |
| Solid State Storage Technology   | 2         | 0.06%   |
| Silicon Image                    | 2         | 0.06%   |
| Netac Technology                 | 2         | 0.06%   |
| LSI Logic / Symbios Logic        | 2         | 0.06%   |
| Broadcom / LSI                   | 2         | 0.06%   |
| Biwin Storage Technology         | 2         | 0.06%   |
| Adaptec                          | 2         | 0.06%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| TenaFe                           | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 432       | 11.71%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 225       | 6.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 130       | 3.52%   |
| AMD 400 Series Chipset SATA Controller                                         | 125       | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 103       | 2.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 95        | 2.58%   |
| AMD 500 Series Chipset SATA Controller                                         | 79        | 2.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 77        | 2.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 73        | 1.98%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 71        | 1.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 71        | 1.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 69        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 66        | 1.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 57        | 1.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 56        | 1.52%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 56        | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 50        | 1.36%   |
| Phison E12 NVMe Controller                                                     | 49        | 1.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 48        | 1.3%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 46        | 1.25%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 43        | 1.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 42        | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller                            | 40        | 1.08%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 39        | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 38        | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 37        | 1%      |
| Intel SATA Controller [RAID mode]                                              | 35        | 0.95%   |
| Intel SSD 660P Series                                                          | 34        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 33        | 0.89%   |
| Phison E16 PCIe4 NVMe Controller                                               | 32        | 0.87%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 32        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 31        | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 30        | 0.81%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 29        | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 29        | 0.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 28        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 26        | 0.7%    |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 25        | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 25        | 0.68%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 25        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1787      | 56.3%   |
| NVMe | 1069      | 33.68%  |
| RAID | 191       | 6.02%   |
| IDE  | 121       | 3.81%   |
| SAS  | 4         | 0.13%   |
| SCSI | 2         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1587      | 69.45%  |
| AMD     | 697       | 30.5%   |
| Unknown | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 39        | 1.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 32        | 1.4%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 29        | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 29        | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 28        | 1.22%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 27        | 1.18%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 25        | 1.09%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 24        | 1.05%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 23        | 1%      |
| AMD Ryzen 9 3900X 12-Core Processor     | 23        | 1%      |
| AMD Ryzen 7 5800X 8-Core Processor      | 23        | 1%      |
| AMD Ryzen 7 2700X Eight-Core Processor  | 21        | 0.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 20        | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 20        | 0.87%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 20        | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 18        | 0.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 18        | 0.79%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 18        | 0.79%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 18        | 0.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 17        | 0.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 17        | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 17        | 0.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 16        | 0.7%    |
| AMD Ryzen 9 5950X 16-Core Processor     | 16        | 0.7%    |
| AMD Ryzen 5 2600 Six-Core Processor     | 16        | 0.7%    |
| Intel Core i7-7700K CPU @ 4.20GHz       | 15        | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 15        | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 14        | 0.61%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 14        | 0.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 13        | 0.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 13        | 0.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 13        | 0.57%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 13        | 0.57%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 13        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 12        | 0.52%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 12        | 0.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 12        | 0.52%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 12        | 0.52%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 12        | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 12        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 541       | 23.62%  |
| Intel Core i7           | 521       | 22.75%  |
| AMD Ryzen 5             | 226       | 9.87%   |
| AMD Ryzen 7             | 194       | 8.47%   |
| Other                   | 143       | 6.24%   |
| Intel Core i3           | 127       | 5.55%   |
| AMD Ryzen 9             | 92        | 4.02%   |
| Intel Xeon              | 52        | 2.27%   |
| Intel Celeron           | 52        | 2.27%   |
| Intel Pentium           | 45        | 1.97%   |
| AMD Ryzen 3             | 44        | 1.92%   |
| Intel Core 2 Duo        | 30        | 1.31%   |
| Intel Core i9           | 27        | 1.18%   |
| Intel Atom              | 25        | 1.09%   |
| AMD FX                  | 24        | 1.05%   |
| AMD A6                  | 16        | 0.7%    |
| AMD A10                 | 12        | 0.52%   |
| AMD Ryzen 7 PRO         | 10        | 0.44%   |
| AMD Ryzen Threadripper  | 8         | 0.35%   |
| Intel Pentium Dual-Core | 7         | 0.31%   |
| AMD Phenom II X4        | 7         | 0.31%   |
| AMD A8                  | 7         | 0.31%   |
| AMD A4                  | 7         | 0.31%   |
| AMD A12                 | 6         | 0.26%   |
| Intel Pentium Silver    | 5         | 0.22%   |
| Intel Pentium Dual      | 5         | 0.22%   |
| Intel Core 2 Quad       | 5         | 0.22%   |
| AMD Ryzen 5 PRO         | 5         | 0.22%   |
| AMD E1                  | 5         | 0.22%   |
| Intel Core 2            | 4         | 0.17%   |
| AMD Athlon 64 X2        | 4         | 0.17%   |
| AMD Athlon              | 4         | 0.17%   |
| Intel Xeon Silver       | 3         | 0.13%   |
| Intel Core m3           | 3         | 0.13%   |
| AMD E2                  | 3         | 0.13%   |
| AMD Athlon II X2        | 3         | 0.13%   |
| Intel Pentium Gold      | 2         | 0.09%   |
| Intel Genuine           | 2         | 0.09%   |
| AMD Phenom II X6        | 2         | 0.09%   |
| Intel Pentium 4         | 1         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 811       | 35.4%   |
| 2       | 652       | 28.46%  |
| 6       | 375       | 16.37%  |
| 8       | 286       | 12.48%  |
| 12      | 69        | 3.01%   |
| 16      | 30        | 1.31%   |
| 10      | 21        | 0.92%   |
| 1       | 14        | 0.61%   |
| 14      | 12        | 0.52%   |
| 3       | 11        | 0.48%   |
| 24      | 5         | 0.22%   |
| 18      | 2         | 0.09%   |
| 40      | 1         | 0.04%   |
| 32      | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2280      | 99.74%  |
| 2       | 5         | 0.22%   |
| Unknown | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1810      | 79.14%  |
| 1       | 476       | 20.81%  |
| Unknown | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2278      | 99.69%  |
| Unknown        | 7         | 0.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 661       | 27.76%  |
| 0x306c3    | 96        | 4.03%   |
| 0x906ea    | 91        | 3.82%   |
| 0x306a9    | 90        | 3.78%   |
| 0x206a7    | 80        | 3.36%   |
| 0x08701021 | 80        | 3.36%   |
| 0x906e9    | 65        | 2.73%   |
| 0x806ea    | 52        | 2.18%   |
| 0x806e9    | 50        | 2.1%    |
| 0x506e3    | 48        | 2.02%   |
| 0x0a50000c | 48        | 2.02%   |
| 0x0800820d | 47        | 1.97%   |
| 0x406e3    | 43        | 1.81%   |
| 0x0a201016 | 39        | 1.64%   |
| 0x806c1    | 36        | 1.51%   |
| 0x08600106 | 36        | 1.51%   |
| 0x08108109 | 36        | 1.51%   |
| 0x806ec    | 35        | 1.47%   |
| 0x40651    | 34        | 1.43%   |
| 0x306d4    | 29        | 1.22%   |
| 0x08701013 | 25        | 1.05%   |
| 0x08108102 | 25        | 1.05%   |
| 0xa0652    | 24        | 1.01%   |
| 0x20655    | 23        | 0.97%   |
| 0x08608103 | 23        | 0.97%   |
| 0x1067a    | 22        | 0.92%   |
| 0x0a201009 | 22        | 0.92%   |
| 0x0a50000d | 19        | 0.8%    |
| 0x706e5    | 16        | 0.67%   |
| 0xa0655    | 15        | 0.63%   |
| 0x08600104 | 14        | 0.59%   |
| 0x806d1    | 13        | 0.55%   |
| 0x08101016 | 13        | 0.55%   |
| 0x06006705 | 13        | 0.55%   |
| 0xa0653    | 12        | 0.5%    |
| 0x806eb    | 12        | 0.5%    |
| 0x106e5    | 12        | 0.5%    |
| 0x0a20120a | 12        | 0.5%    |
| 0x0810100b | 12        | 0.5%    |
| 0x30678    | 11        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 485       | 21.16%  |
| Haswell          | 207       | 9.03%   |
| Zen 2            | 187       | 8.16%   |
| Zen 3            | 171       | 7.46%   |
| IvyBridge        | 155       | 6.76%   |
| Skylake          | 140       | 6.11%   |
| Zen+             | 122       | 5.32%   |
| SandyBridge      | 120       | 5.24%   |
| CometLake        | 76        | 3.32%   |
| Unknown          | 59        | 2.57%   |
| TigerLake        | 55        | 2.4%    |
| Zen              | 51        | 2.23%   |
| Broadwell        | 49        | 2.14%   |
| Westmere         | 47        | 2.05%   |
| Alderlake Hybrid | 46        | 2.01%   |
| Icelake          | 45        | 1.96%   |
| Penryn           | 38        | 1.66%   |
| Silvermont       | 36        | 1.57%   |
| Excavator        | 35        | 1.53%   |
| Piledriver       | 31        | 1.35%   |
| Goldmont plus    | 22        | 0.96%   |
| Goldmont         | 19        | 0.83%   |
| Nehalem          | 17        | 0.74%   |
| K10              | 17        | 0.74%   |
| Core             | 16        | 0.7%    |
| Steamroller      | 8         | 0.35%   |
| K8 Hammer        | 6         | 0.26%   |
| Jaguar           | 6         | 0.26%   |
| Tremont          | 5         | 0.22%   |
| Puma             | 5         | 0.22%   |
| Bobcat           | 4         | 0.17%   |
| Bulldozer        | 3         | 0.13%   |
| Bonnell          | 3         | 0.13%   |
| K10 Llano        | 2         | 0.09%   |
| NetBurst         | 1         | 0.04%   |
| K8 & K10 hybrid  | 1         | 0.04%   |
| Gracemont        | 1         | 0.04%   |
| CannonLake       | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1202      | 42.97%  |
| Nvidia                     | 918       | 32.82%  |
| AMD                        | 659       | 23.56%  |
| ASPEED Technology          | 15        | 0.54%   |
| Matrox Electronics Systems | 2         | 0.07%   |
| ATI Technologies           | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 91        | 3.18%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 83        | 2.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 74        | 2.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 73        | 2.55%   |
| Intel HD Graphics 620                                                                    | 67        | 2.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 67        | 2.34%   |
| Intel UHD Graphics 620                                                                   | 65        | 2.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 63        | 2.2%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 59        | 2.06%   |
| Intel HD Graphics 630                                                                    | 56        | 1.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 53        | 1.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 52        | 1.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 48        | 1.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 48        | 1.68%   |
| Intel HD Graphics 530                                                                    | 43        | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 41        | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 40        | 1.4%    |
| Intel HD Graphics 5500                                                                   | 39        | 1.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 35        | 1.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 35        | 1.22%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 33        | 1.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 33        | 1.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 31        | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 29        | 1.01%   |
| AMD Lucienne                                                                             | 29        | 1.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 26        | 0.91%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 26        | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25        | 0.87%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 21        | 0.73%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 21        | 0.73%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 20        | 0.7%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 19        | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 19        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 19        | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 0.63%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 17        | 0.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 17        | 0.59%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 17        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 747       | 32.39%  |
| 1 x AMD        | 516       | 22.38%  |
| 1 x Nvidia     | 490       | 21.25%  |
| Intel + Nvidia | 372       | 16.13%  |
| AMD + Nvidia   | 54        | 2.34%   |
| Intel + AMD    | 51        | 2.21%   |
| 2 x AMD        | 41        | 1.78%   |
| 1 x ASPEED     | 14        | 0.61%   |
| 2 x Intel      | 10        | 0.43%   |
| 2 x Nvidia     | 5         | 0.22%   |
| Other          | 3         | 0.13%   |
| 1 x Matrox     | 2         | 0.09%   |
| AMD + ASPEED   | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1623      | 70.02%  |
| Proprietary | 642       | 27.7%   |
| Unknown     | 53        | 2.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1183      | 50.47%  |
| 1.01-2.0   | 221       | 9.43%   |
| 7.01-8.0   | 216       | 9.22%   |
| 0.01-0.5   | 199       | 8.49%   |
| 3.01-4.0   | 183       | 7.81%   |
| 5.01-6.0   | 105       | 4.48%   |
| 8.01-16.0  | 100       | 4.27%   |
| 0.51-1.0   | 97        | 4.14%   |
| 2.01-3.0   | 27        | 1.15%   |
| 16.01-24.0 | 10        | 0.43%   |
| 4.01-5.0   | 3         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 308       | 11.42%  |
| AU Optronics            | 259       | 9.6%    |
| LG Display              | 240       | 8.9%    |
| BOE                     | 214       | 7.93%   |
| Chimei Innolux          | 207       | 7.67%   |
| Dell                    | 196       | 7.26%   |
| Goldstar                | 184       | 6.82%   |
| Acer                    | 102       | 3.78%   |
| AOC                     | 87        | 3.22%   |
| Hewlett-Packard         | 83        | 3.08%   |
| Ancor Communications    | 81        | 3%      |
| BenQ                    | 75        | 2.78%   |
| Sharp                   | 49        | 1.82%   |
| Philips                 | 46        | 1.7%    |
| Apple                   | 44        | 1.63%   |
| Lenovo                  | 39        | 1.45%   |
| ASUSTek Computer        | 37        | 1.37%   |
| ViewSonic               | 32        | 1.19%   |
| PANDA                   | 29        | 1.07%   |
| Sony                    | 26        | 0.96%   |
| Iiyama                  | 24        | 0.89%   |
| MSI                     | 23        | 0.85%   |
| Unknown                 | 20        | 0.74%   |
| Chi Mei Optoelectronics | 19        | 0.7%    |
| Eizo                    | 16        | 0.59%   |
| CSO                     | 16        | 0.59%   |
| Vizio                   | 12        | 0.44%   |
| Sceptre Tech            | 12        | 0.44%   |
| LG Electronics          | 12        | 0.44%   |
| InfoVision              | 12        | 0.44%   |
| Gigabyte Technology     | 11        | 0.41%   |
| Toshiba                 | 10        | 0.37%   |
| Panasonic               | 10        | 0.37%   |
| HannStar                | 9         | 0.33%   |
| Unknown                 | 9         | 0.33%   |
| Vestel Elektronik       | 5         | 0.19%   |
| MStar                   | 5         | 0.19%   |
| VIE                     | 4         | 0.15%   |
| MiTAC                   | 4         | 0.15%   |
| Microstep               | 4         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 14        | 0.5%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 13        | 0.46%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 12        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 12        | 0.43%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 10        | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 10        | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 10        | 0.36%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9         | 0.32%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 9         | 0.32%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 9         | 0.32%   |
| Unknown                                                               | 9         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 8         | 0.28%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 8         | 0.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 8         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 8         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 8         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 0.28%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 8         | 0.28%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 7         | 0.25%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.25%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 7         | 0.25%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 7         | 0.25%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 7         | 0.25%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 7         | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 6         | 0.21%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.21%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 6         | 0.21%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 6         | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 6         | 0.21%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 6         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 6         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.21%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 6         | 0.21%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 6         | 0.21%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 6         | 0.21%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 5         | 0.18%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch     | 5         | 0.18%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 5         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1243      | 48.8%   |
| 1366x768 (WXGA)    | 348       | 13.66%  |
| 2560x1440 (QHD)    | 214       | 8.4%    |
| 3840x2160 (4K)     | 190       | 7.46%   |
| 1600x900 (HD+)     | 75        | 2.94%   |
| 2560x1080          | 53        | 2.08%   |
| 1920x1200 (WUXGA)  | 48        | 1.88%   |
| 1440x900 (WXGA+)   | 47        | 1.85%   |
| 1680x1050 (WSXGA+) | 44        | 1.73%   |
| 1280x1024 (SXGA)   | 36        | 1.41%   |
| 3440x1440          | 35        | 1.37%   |
| 1280x800 (WXGA)    | 28        | 1.1%    |
| Unknown            | 22        | 0.86%   |
| 3840x1080          | 20        | 0.79%   |
| 2880x1800          | 19        | 0.75%   |
| 2560x1600          | 17        | 0.67%   |
| 1360x768           | 16        | 0.63%   |
| 2288x1287          | 11        | 0.43%   |
| 2160x1440          | 11        | 0.43%   |
| 1920x540           | 10        | 0.39%   |
| 3840x2400          | 7         | 0.27%   |
| 1600x1200          | 7         | 0.27%   |
| 3200x1800 (QHD+)   | 6         | 0.24%   |
| 3840x1600          | 5         | 0.2%    |
| 2944x1080          | 2         | 0.08%   |
| 2160x1350          | 2         | 0.08%   |
| 2048x1152          | 2         | 0.08%   |
| 1024x768 (XGA)     | 2         | 0.08%   |
| 1024x600           | 2         | 0.08%   |
| 7280x1440          | 1         | 0.04%   |
| 6400x1440          | 1         | 0.04%   |
| 5760x2160          | 1         | 0.04%   |
| 5520x1080          | 1         | 0.04%   |
| 5360x1440          | 1         | 0.04%   |
| 5120x1440          | 1         | 0.04%   |
| 480x1920           | 1         | 0.04%   |
| 4480x1080          | 1         | 0.04%   |
| 4096x2160          | 1         | 0.04%   |
| 3840x2524          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 629       | 23.41%  |
| 27      | 272       | 10.12%  |
| 24      | 237       | 8.82%   |
| 14      | 197       | 7.33%   |
| 13      | 179       | 6.66%   |
| 23      | 175       | 6.51%   |
| 21      | 165       | 6.14%   |
| 17      | 130       | 4.84%   |
| 31      | 103       | 3.83%   |
| Unknown | 89        | 3.31%   |
| 34      | 72        | 2.68%   |
| 19      | 47        | 1.75%   |
| 12      | 47        | 1.75%   |
| 18      | 41        | 1.53%   |
| 22      | 33        | 1.23%   |
| 40      | 26        | 0.97%   |
| 20      | 24        | 0.89%   |
| 84      | 20        | 0.74%   |
| 72      | 19        | 0.71%   |
| 54      | 19        | 0.71%   |
| 32      | 19        | 0.71%   |
| 16      | 18        | 0.67%   |
| 25      | 12        | 0.45%   |
| 28      | 11        | 0.41%   |
| 142     | 10        | 0.37%   |
| 11      | 10        | 0.37%   |
| 48      | 8         | 0.3%    |
| 52      | 7         | 0.26%   |
| 26      | 7         | 0.26%   |
| 49      | 6         | 0.22%   |
| 29      | 6         | 0.22%   |
| 10      | 6         | 0.22%   |
| 42      | 5         | 0.19%   |
| 39      | 5         | 0.19%   |
| 65      | 4         | 0.15%   |
| 43      | 4         | 0.15%   |
| 37      | 4         | 0.15%   |
| 74      | 3         | 0.11%   |
| 46      | 3         | 0.11%   |
| 35      | 3         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 925       | 35.29%  |
| 501-600        | 624       | 23.81%  |
| 401-500        | 284       | 10.84%  |
| 201-300        | 163       | 6.22%   |
| 601-700        | 147       | 5.61%   |
| 351-400        | 141       | 5.38%   |
| 701-800        | 94        | 3.59%   |
| Unknown        | 89        | 3.4%    |
| 1001-1500      | 51        | 1.95%   |
| 1501-2000      | 43        | 1.64%   |
| 801-900        | 40        | 1.53%   |
| More than 2000 | 10        | 0.38%   |
| 901-1000       | 10        | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1874      | 79.17%  |
| 16/10   | 227       | 9.59%   |
| 21/9    | 91        | 3.84%   |
| Unknown | 70        | 2.96%   |
| 5/4     | 34        | 1.44%   |
| 3/2     | 23        | 0.97%   |
| 4/3     | 15        | 0.63%   |
| 32/9    | 12        | 0.51%   |
| 1.00    | 10        | 0.42%   |
| 6/5     | 5         | 0.21%   |
| 0.56    | 2         | 0.08%   |
| 3.40    | 1         | 0.04%   |
| 2.00    | 1         | 0.04%   |
| 0.80    | 1         | 0.04%   |
| 0.25    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 621       | 23.4%   |
| 201-250        | 499       | 18.8%   |
| 81-90          | 304       | 11.45%  |
| 301-350        | 277       | 10.44%  |
| 351-500        | 204       | 7.69%   |
| 151-200        | 105       | 3.96%   |
| 121-130        | 105       | 3.96%   |
| Unknown        | 89        | 3.35%   |
| More than 1000 | 88        | 3.32%   |
| 251-300        | 84        | 3.17%   |
| 71-80          | 71        | 2.68%   |
| 501-1000       | 59        | 2.22%   |
| 141-150        | 54        | 2.03%   |
| 61-70          | 43        | 1.62%   |
| 111-120        | 14        | 0.53%   |
| 51-60          | 12        | 0.45%   |
| 131-140        | 10        | 0.38%   |
| 91-100         | 10        | 0.38%   |
| 41-50          | 5         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 843       | 33.16%  |
| 121-160       | 728       | 28.64%  |
| 101-120       | 612       | 24.08%  |
| 161-240       | 142       | 5.59%   |
| Unknown       | 89        | 3.5%    |
| 1-50          | 70        | 2.75%   |
| More than 240 | 58        | 2.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1719      | 73.3%   |
| 2     | 498       | 21.24%  |
| 0     | 64        | 2.73%   |
| 3     | 60        | 2.56%   |
| 4     | 4         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1297      | 38.35%  |
| Intel                             | 1279      | 37.82%  |
| Qualcomm Atheros                  | 325       | 9.61%   |
| Broadcom                          | 124       | 3.67%   |
| MediaTek                          | 52        | 1.54%   |
| TP-Link                           | 32        | 0.95%   |
| Ralink Technology                 | 30        | 0.89%   |
| Broadcom Limited                  | 26        | 0.77%   |
| ASIX Electronics                  | 15        | 0.44%   |
| Marvell Technology Group          | 14        | 0.41%   |
| Nvidia                            | 13        | 0.38%   |
| Ralink                            | 12        | 0.35%   |
| Sierra Wireless                   | 11        | 0.33%   |
| Microsoft                         | 11        | 0.33%   |
| Samsung Electronics               | 9         | 0.27%   |
| Aquantia                          | 9         | 0.27%   |
| Ericsson Business Mobile Networks | 8         | 0.24%   |
| DisplayLink                       | 8         | 0.24%   |
| Dell                              | 8         | 0.24%   |
| Qualcomm                          | 7         | 0.21%   |
| D-Link System                     | 7         | 0.21%   |
| NetGear                           | 6         | 0.18%   |
| Qualcomm Atheros Communications   | 5         | 0.15%   |
| Lenovo                            | 5         | 0.15%   |
| Huawei Technologies               | 5         | 0.15%   |
| Xiaomi                            | 4         | 0.12%   |
| JMicron Technology                | 4         | 0.12%   |
| Insyde Software                   | 4         | 0.12%   |
| Hewlett-Packard                   | 4         | 0.12%   |
| Fibocom                           | 4         | 0.12%   |
| D-Link                            | 4         | 0.12%   |
| T & A Mobile Phones               | 3         | 0.09%   |
| ASUSTek Computer                  | 3         | 0.09%   |
| Tenda                             | 2         | 0.06%   |
| Oculus VR                         | 2         | 0.06%   |
| Motorola PCS                      | 2         | 0.06%   |
| Microchip Technology              | 2         | 0.06%   |
| Emulex                            | 2         | 0.06%   |
| vivo                              | 1         | 0.03%   |
| VIA Technologies                  | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 946       | 23.37%  |
| Intel Wi-Fi 6 AX200                                               | 186       | 4.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 107       | 2.64%   |
| Intel I211 Gigabit Network Connection                             | 107       | 2.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 79        | 1.95%   |
| Intel Wireless 8265 / 8275                                        | 79        | 1.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 78        | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 75        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 64        | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 62        | 1.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 61        | 1.51%   |
| Intel Wireless 7260                                               | 60        | 1.48%   |
| Intel Ethernet Connection (2) I219-V                              | 57        | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 51        | 1.26%   |
| Intel Ethernet Controller I225-V                                  | 49        | 1.21%   |
| Intel Wireless 7265                                               | 48        | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 48        | 1.19%   |
| Intel Wireless 8260                                               | 47        | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 43        | 1.06%   |
| Intel Wireless-AC 9260                                            | 41        | 1.01%   |
| Intel Wi-Fi 6 AX201                                               | 41        | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 38        | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 37        | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 37        | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 37        | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 36        | 0.89%   |
| Intel Wireless 3165                                               | 34        | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 26        | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 25        | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 25        | 0.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 23        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 21        | 0.52%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 21        | 0.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 20        | 0.49%   |
| Intel Wireless 3160                                               | 20        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 20        | 0.49%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 18        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 979       | 53.61%  |
| Realtek Semiconductor                 | 294       | 16.1%   |
| Qualcomm Atheros                      | 254       | 13.91%  |
| Broadcom                              | 91        | 4.98%   |
| MediaTek                              | 50        | 2.74%   |
| Ralink Technology                     | 30        | 1.64%   |
| TP-Link                               | 29        | 1.59%   |
| Broadcom Limited                      | 20        | 1.1%    |
| Ralink                                | 12        | 0.66%   |
| Sierra Wireless                       | 11        | 0.6%    |
| Microsoft                             | 11        | 0.6%    |
| NetGear                               | 6         | 0.33%   |
| Qualcomm Atheros Communications       | 5         | 0.27%   |
| Fibocom                               | 4         | 0.22%   |
| Dell                                  | 4         | 0.22%   |
| D-Link System                         | 4         | 0.22%   |
| D-Link                                | 4         | 0.22%   |
| Marvell Technology Group              | 3         | 0.16%   |
| ASUSTek Computer                      | 3         | 0.16%   |
| Tenda                                 | 2         | 0.11%   |
| Hewlett-Packard                       | 2         | 0.11%   |
| Ericsson Business Mobile Networks     | 2         | 0.11%   |
| Xiaomi                                | 1         | 0.05%   |
| Ovislink                              | 1         | 0.05%   |
| IMC Networks                          | 1         | 0.05%   |
| Edimax Technology                     | 1         | 0.05%   |
| CyberTAN Technology                   | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 186       | 10.13%  |
| Intel Wireless 8265 / 8275                                           | 79        | 4.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 75        | 4.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 64        | 3.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 62        | 3.38%   |
| Intel Wireless 7260                                                  | 60        | 3.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 51        | 2.78%   |
| Intel Wireless 7265                                                  | 48        | 2.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 48        | 2.61%   |
| Intel Wireless 8260                                                  | 47        | 2.56%   |
| Intel Wireless-AC 9260                                               | 41        | 2.23%   |
| Intel Wi-Fi 6 AX201                                                  | 41        | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 39        | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 37        | 2.02%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 37        | 2.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 37        | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 36        | 1.96%   |
| Intel Wireless 3165                                                  | 34        | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 26        | 1.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 25        | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 25        | 1.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 23        | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 21        | 1.14%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 21        | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 20        | 1.09%   |
| Intel Wireless 3160                                                  | 20        | 1.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 20        | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 18        | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 18        | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 16        | 0.87%   |
| Intel Centrino Ultimate-N 6300                                       | 16        | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 15        | 0.82%   |
| Ralink MT7601U Wireless Adapter                                      | 15        | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 15        | 0.82%   |
| Intel Centrino Advanced-N 6200                                       | 14        | 0.76%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 14        | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 13        | 0.71%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 13        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 13        | 0.71%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 13        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1190      | 56%     |
| Intel                                  | 660       | 31.06%  |
| Qualcomm Atheros                       | 98        | 4.61%   |
| Broadcom                               | 55        | 2.59%   |
| ASIX Electronics                       | 15        | 0.71%   |
| Nvidia                                 | 13        | 0.61%   |
| Marvell Technology Group               | 11        | 0.52%   |
| Samsung Electronics                    | 9         | 0.42%   |
| Aquantia                               | 9         | 0.42%   |
| DisplayLink                            | 8         | 0.38%   |
| Qualcomm                               | 7         | 0.33%   |
| Broadcom Limited                       | 6         | 0.28%   |
| Lenovo                                 | 4         | 0.19%   |
| JMicron Technology                     | 4         | 0.19%   |
| Insyde Software                        | 4         | 0.19%   |
| Xiaomi                                 | 3         | 0.14%   |
| TP-Link                                | 3         | 0.14%   |
| T & A Mobile Phones                    | 3         | 0.14%   |
| Huawei Technologies                    | 3         | 0.14%   |
| D-Link System                          | 3         | 0.14%   |
| Motorola PCS                           | 2         | 0.09%   |
| MediaTek                               | 2         | 0.09%   |
| Emulex                                 | 2         | 0.09%   |
| VIA Technologies                       | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Solarflare Communications              | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.05%   |
| Novatel Wireless                       | 1         | 0.05%   |
| Microchip Technology                   | 1         | 0.05%   |
| Mellanox Technologies                  | 1         | 0.05%   |
| ICS Advent                             | 1         | 0.05%   |
| Google                                 | 1         | 0.05%   |
| Apple                                  | 1         | 0.05%   |
| 3Com                                   | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 946       | 43.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 107       | 4.9%    |
| Intel I211 Gigabit Network Connection                             | 107       | 4.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 79        | 3.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 78        | 3.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 61        | 2.79%   |
| Intel Ethernet Connection (2) I219-V                              | 57        | 2.61%   |
| Intel Ethernet Controller I225-V                                  | 49        | 2.24%   |
| Intel Ethernet Connection I217-LM                                 | 43        | 1.97%   |
| Intel Ethernet Connection (7) I219-V                              | 38        | 1.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.92%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.82%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 0.73%   |
| Intel 82579V Gigabit Network Connection                           | 16        | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 0.69%   |
| Intel 82577LM Gigabit Network Connection                          | 15        | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.55%   |
| Intel I210 Gigabit Network Connection                             | 12        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 10        | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.46%   |
| Intel Ethernet Connection X553 1GbE                               | 10        | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                             | 10        | 0.46%   |
| Intel Ethernet Connection (2) I218-V                              | 10        | 0.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.46%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.41%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 9         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.37%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.37%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.32%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.27%   |
| Intel Ethernet Connection (12) I219-V                             | 6         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2004      | 53.04%  |
| WiFi     | 1746      | 46.21%  |
| Modem    | 26        | 0.69%   |
| Unknown  | 2         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1310      | 54.33%  |
| Ethernet | 1101      | 45.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1286      | 56.01%  |
| 1     | 901       | 39.24%  |
| 3     | 73        | 3.18%   |
| 4     | 20        | 0.87%   |
| 0     | 13        | 0.57%   |
| 5     | 2         | 0.09%   |
| 9     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1733      | 74.09%  |
| Yes  | 606       | 25.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 852       | 52.63%  |
| Realtek Semiconductor           | 167       | 10.32%  |
| Qualcomm Atheros Communications | 115       | 7.1%    |
| Cambridge Silicon Radio         | 99        | 6.11%   |
| IMC Networks                    | 77        | 4.76%   |
| Broadcom                        | 61        | 3.77%   |
| Apple                           | 56        | 3.46%   |
| ASUSTek Computer                | 43        | 2.66%   |
| Lite-On Technology              | 40        | 2.47%   |
| Foxconn / Hon Hai               | 32        | 1.98%   |
| MediaTek                        | 19        | 1.17%   |
| Dell                            | 10        | 0.62%   |
| Realtek                         | 7         | 0.43%   |
| Toshiba                         | 6         | 0.37%   |
| TP-Link                         | 5         | 0.31%   |
| Belkin Components               | 4         | 0.25%   |
| Ralink                          | 3         | 0.19%   |
| Hewlett-Packard                 | 3         | 0.19%   |
| Edimax Technology               | 3         | 0.19%   |
| Dynex                           | 3         | 0.19%   |
| Ralink Technology               | 2         | 0.12%   |
| Marvell Semiconductor           | 2         | 0.12%   |
| HTC (High Tech Computer)        | 2         | 0.12%   |
| Actions                         | 2         | 0.12%   |
| SINO WEALTH                     | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| Integrated System Solution      | 1         | 0.06%   |
| Foxconn International           | 1         | 0.06%   |
| Creative Technology             | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 280       | 17.27%  |
| Intel AX200 Bluetooth                               | 180       | 11.1%   |
| Intel AX201 Bluetooth                               | 120       | 7.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 114       | 7.03%   |
| Realtek Bluetooth Radio                             | 103       | 6.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 99        | 6.11%   |
| Qualcomm Atheros  Bluetooth Device                  | 74        | 4.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 47        | 2.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 42        | 2.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 42        | 2.59%   |
| Apple Bluetooth Host Controller                     | 31        | 1.91%   |
| Intel Bluetooth Device                              | 27        | 1.67%   |
| IMC Networks Bluetooth Radio                        | 26        | 1.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 1.36%   |
| Intel AX210 Bluetooth                               | 20        | 1.23%   |
| IMC Networks Bluetooth Device                       | 20        | 1.23%   |
| IMC Networks Wireless_Device                        | 19        | 1.17%   |
| Broadcom BCM2045B (BDC-2.1)                         | 19        | 1.17%   |
| Apple Bluetooth USB Host Controller                 | 19        | 1.17%   |
| MediaTek Wireless_Device                            | 18        | 1.11%   |
| Lite-On Bluetooth Device                            | 15        | 0.93%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 15        | 0.93%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 0.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 14        | 0.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 14        | 0.86%   |
| ASUS ASUS USB-BT500                                 | 14        | 0.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 0.8%    |
| Realtek RTL8821A Bluetooth                          | 10        | 0.62%   |
| Foxconn / Hon Hai Bluetooth Device                  | 9         | 0.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 0.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.49%   |
| Realtek Bluetooth Radio                             | 7         | 0.43%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.37%   |
| TP-Link UB500 Adapter                               | 5         | 0.31%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.31%   |
| Broadcom HP Portable Bumble Bee                     | 5         | 0.31%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 4         | 0.25%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1542      | 42.69%  |
| AMD                                  | 814       | 22.54%  |
| Nvidia                               | 731       | 20.24%  |
| C-Media Electronics                  | 74        | 2.05%   |
| Logitech                             | 52        | 1.44%   |
| Texas Instruments                    | 31        | 0.86%   |
| Kingston Technology                  | 26        | 0.72%   |
| JMTek                                | 24        | 0.66%   |
| Razer USA                            | 20        | 0.55%   |
| Focusrite-Novation                   | 20        | 0.55%   |
| Corsair                              | 15        | 0.42%   |
| ASUSTek Computer                     | 15        | 0.42%   |
| SteelSeries ApS                      | 14        | 0.39%   |
| Realtek Semiconductor                | 14        | 0.39%   |
| Creative Technology                  | 13        | 0.36%   |
| Creative Labs                        | 12        | 0.33%   |
| Generalplus Technology               | 10        | 0.28%   |
| GN Netcom                            | 9         | 0.25%   |
| BEHRINGER International              | 8         | 0.22%   |
| Samson Technologies                  | 7         | 0.19%   |
| RODE Microphones                     | 7         | 0.19%   |
| DSEA A/S                             | 7         | 0.19%   |
| SAVITECH                             | 6         | 0.17%   |
| Lenovo                               | 6         | 0.17%   |
| Blue Microphones                     | 6         | 0.17%   |
| Yamaha                               | 5         | 0.14%   |
| XMOS                                 | 5         | 0.14%   |
| Sony                                 | 5         | 0.14%   |
| PreSonus Audio Electronics           | 5         | 0.14%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.11%   |
| Plantronics                          | 4         | 0.11%   |
| Hewlett-Packard                      | 4         | 0.11%   |
| VIA Technologies                     | 3         | 0.08%   |
| Native Instruments                   | 3         | 0.08%   |
| Mark of the Unicorn                  | 3         | 0.08%   |
| Jieli Technology                     | 3         | 0.08%   |
| FiiO Electronics Technology          | 3         | 0.08%   |
| FIFINE Microphones                   | 3         | 0.08%   |
| Dell                                 | 3         | 0.08%   |
| Audio-Technica                       | 3         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 290       | 6.75%   |
| AMD Starship/Matisse HD Audio Controller                                   | 203       | 4.72%   |
| Intel Sunrise Point-LP HD Audio                                            | 199       | 4.63%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 144       | 3.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 143       | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 143       | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 123       | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 122       | 2.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 88        | 2.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 86        | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 84        | 1.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 82        | 1.91%   |
| Intel 200 Series PCH HD Audio                                              | 74        | 1.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 70        | 1.63%   |
| Nvidia TU116 High Definition Audio Controller                              | 62        | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 61        | 1.42%   |
| Nvidia GP106 High Definition Audio Controller                              | 61        | 1.42%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 59        | 1.37%   |
| Nvidia TU106 High Definition Audio Controller                              | 58        | 1.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 55        | 1.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 55        | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 54        | 1.26%   |
| Nvidia GP104 High Definition Audio Controller                              | 52        | 1.21%   |
| Intel Haswell-ULT HD Audio Controller                                      | 52        | 1.21%   |
| Intel 8 Series HD Audio Controller                                         | 52        | 1.21%   |
| Intel Comet Lake PCH cAVS                                                  | 48        | 1.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 46        | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 46        | 1.07%   |
| Intel Broadwell-U Audio Controller                                         | 46        | 1.07%   |
| Nvidia GA104 High Definition Audio Controller                              | 42        | 0.98%   |
| Intel CM238 HD Audio Controller                                            | 42        | 0.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 38        | 0.88%   |
| AMD Navi 10 HDMI Audio                                                     | 37        | 0.86%   |
| Nvidia TU104 HD Audio Controller                                           | 36        | 0.84%   |
| Intel Comet Lake PCH-LP cAVS                                               | 35        | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 35        | 0.81%   |
| AMD FCH Azalia Controller                                                  | 32        | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                              | 31        | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 26        | 0.6%    |
| Nvidia GA102 High Definition Audio Controller                              | 26        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 528       | 21.09%  |
| SK hynix            | 416       | 16.61%  |
| Kingston            | 269       | 10.74%  |
| Micron Technology   | 244       | 9.74%   |
| Corsair             | 232       | 9.27%   |
| Crucial             | 189       | 7.55%   |
| G.Skill             | 143       | 5.71%   |
| Unknown             | 131       | 5.23%   |
| A-DATA Technology   | 55        | 2.2%    |
| Ramaxel Technology  | 39        | 1.56%   |
| Team                | 34        | 1.36%   |
| Nanya Technology    | 25        | 1%      |
| Elpida              | 21        | 0.84%   |
| Patriot             | 17        | 0.68%   |
| Unknown (ABCD)      | 12        | 0.48%   |
| Unknown             | 11        | 0.44%   |
| GOODRAM             | 10        | 0.4%    |
| Apacer              | 9         | 0.36%   |
| Avant               | 7         | 0.28%   |
| Silicon Power       | 6         | 0.24%   |
| PNY                 | 6         | 0.24%   |
| Neo Forza           | 6         | 0.24%   |
| Transcend           | 5         | 0.2%    |
| Timetec             | 5         | 0.2%    |
| Smart               | 5         | 0.2%    |
| Goldkey             | 5         | 0.2%    |
| ASint Technology    | 5         | 0.2%    |
| AMD                 | 4         | 0.16%   |
| Sesame              | 3         | 0.12%   |
| Kingmax             | 3         | 0.12%   |
| CSX                 | 3         | 0.12%   |
| Unknown (0x0B5E)    | 2         | 0.08%   |
| Unifosa             | 2         | 0.08%   |
| Teikon              | 2         | 0.08%   |
| Smart Brazil        | 2         | 0.08%   |
| Lexar               | 2         | 0.08%   |
| Kllisre             | 2         | 0.08%   |
| Golden Empire       | 2         | 0.08%   |
| GeIL                | 2         | 0.08%   |
| Wodposit            | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 25        | 0.93%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 24        | 0.89%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 0.89%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 22        | 0.82%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 22        | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 20        | 0.74%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 0.74%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 16        | 0.59%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.59%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 16        | 0.59%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 14        | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 13        | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.48%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.48%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16384MB DIMM DDR4 3200MT/s         | 12        | 0.45%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 12        | 0.45%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 12        | 0.45%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.41%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 11        | 0.41%   |
| Unknown                                                          | 11        | 0.41%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 10        | 0.37%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 10        | 0.37%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.33%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 9         | 0.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.33%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2667MT/s            | 9         | 0.33%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 9         | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 0.3%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 8         | 0.3%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 8         | 0.3%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1281      | 60.14%  |
| DDR3    | 622       | 29.2%   |
| LPDDR4  | 49        | 2.3%    |
| LPDDR3  | 41        | 1.92%   |
| DDR5    | 39        | 1.83%   |
| Unknown | 33        | 1.55%   |
| DDR2    | 26        | 1.22%   |
| SDRAM   | 25        | 1.17%   |
| LPDDR5  | 10        | 0.47%   |
| DDR     | 3         | 0.14%   |
| DRAM    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1135      | 52.96%  |
| DIMM         | 878       | 40.97%  |
| Row Of Chips | 117       | 5.46%   |
| Chip         | 10        | 0.47%   |
| RIMM         | 2         | 0.09%   |
| Unknown      | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1064      | 45.22%  |
| 4096  | 579       | 24.61%  |
| 16384 | 432       | 18.36%  |
| 2048  | 149       | 6.33%   |
| 32768 | 102       | 4.33%   |
| 1024  | 20        | 0.85%   |
| 49152 | 2         | 0.08%   |
| 512   | 2         | 0.08%   |
| 12288 | 1         | 0.04%   |
| 64    | 1         | 0.04%   |
| 16    | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 443       | 18.69%  |
| 3200    | 422       | 17.81%  |
| 2667    | 387       | 16.33%  |
| 2400    | 191       | 8.06%   |
| 2133    | 109       | 4.6%    |
| 1333    | 109       | 4.6%    |
| 3600    | 105       | 4.43%   |
| 1334    | 41        | 1.73%   |
| 3733    | 39        | 1.65%   |
| 1867    | 38        | 1.6%    |
| 3000    | 31        | 1.31%   |
| 3400    | 30        | 1.27%   |
| 3266    | 26        | 1.1%    |
| 4800    | 23        | 0.97%   |
| 1067    | 23        | 0.97%   |
| 2666    | 19        | 0.8%    |
| 800     | 19        | 0.8%    |
| 4267    | 18        | 0.76%   |
| 3800    | 18        | 0.76%   |
| 1866    | 18        | 0.76%   |
| Unknown | 18        | 0.76%   |
| 667     | 17        | 0.72%   |
| 3533    | 16        | 0.68%   |
| 1800    | 16        | 0.68%   |
| 2933    | 15        | 0.63%   |
| 3866    | 14        | 0.59%   |
| 2800    | 13        | 0.55%   |
| 3466    | 12        | 0.51%   |
| 6400    | 10        | 0.42%   |
| 3666    | 8         | 0.34%   |
| 8400    | 7         | 0.3%    |
| 4199    | 7         | 0.3%    |
| 5200    | 6         | 0.25%   |
| 3534    | 6         | 0.25%   |
| 3334    | 6         | 0.25%   |
| 2000    | 6         | 0.25%   |
| 1648    | 6         | 0.25%   |
| 4266    | 5         | 0.21%   |
| 4000    | 5         | 0.21%   |
| 2465    | 5         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 19        | 36.54%  |
| Brother Industries    | 16        | 30.77%  |
| Canon                 | 6         | 11.54%  |
| Seiko Epson           | 5         | 9.62%   |
| Samsung Electronics   | 2         | 3.85%   |
| MIIIW                 | 1         | 1.92%   |
| Lexmark International | 1         | 1.92%   |
| Gprinter              | 1         | 1.92%   |
| Dymo-CoStar           | 1         | 1.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon PIXMA MG3600 Series              | 3         | 5.66%   |
| Seiko Epson ET-4700 Series             | 2         | 3.77%   |
| HP DeskJet F4100 Printer series        | 2         | 3.77%   |
| HP DeskJet 2600 series                 | 2         | 3.77%   |
| Brother Printer                        | 2         | 3.77%   |
| Brother DCP-7055 scanner/printer       | 2         | 3.77%   |
| Seiko Epson XP-240 Series              | 1         | 1.89%   |
| Seiko Epson XP-2100 Series             | 1         | 1.89%   |
| Seiko Epson ET-2710 Series             | 1         | 1.89%   |
| Samsung SCX-3400 Series                | 1         | 1.89%   |
| Samsung SCX-3200 Series                | 1         | 1.89%   |
| MIIIW MW Keyboard Air Mini             | 1         | 1.89%   |
| Lexmark International B2236dw          | 1         | 1.89%   |
| HP PSC 1400                            | 1         | 1.89%   |
| HP OfficeJet Pro 8020 series           | 1         | 1.89%   |
| HP OfficeJet Pro 6960                  | 1         | 1.89%   |
| HP OfficeJet 5200 series               | 1         | 1.89%   |
| HP OfficeJet 4650 series               | 1         | 1.89%   |
| HP LaserJet Professional P1102w        | 1         | 1.89%   |
| HP LaserJet P1005                      | 1         | 1.89%   |
| HP LaserJet M203-M206                  | 1         | 1.89%   |
| HP LaserJet 3050                       | 1         | 1.89%   |
| HP LaserJet 1015                       | 1         | 1.89%   |
| HP ENVY 6400 series                    | 1         | 1.89%   |
| HP ENVY 4500 series                    | 1         | 1.89%   |
| HP Deskjet 4640 series                 | 1         | 1.89%   |
| HP DeskJet 3700 series                 | 1         | 1.89%   |
| HP DeskJet 2700 series                 | 1         | 1.89%   |
| HP Deskjet 1050 J410                   | 1         | 1.89%   |
| Gprinter GP-58                         | 1         | 1.89%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 1.89%   |
| Canon TS5100 series                    | 1         | 1.89%   |
| Canon LiDE 300                         | 1         | 1.89%   |
| Canon G2000 series                     | 1         | 1.89%   |
| Brother MFC-L3770CDW series            | 1         | 1.89%   |
| Brother MFC-L3750CDW                   | 1         | 1.89%   |
| Brother MFC-J6545DW                    | 1         | 1.89%   |
| Brother MFC-J497DW                     | 1         | 1.89%   |
| Brother MFC-J485DW                     | 1         | 1.89%   |
| Brother MFC-J450DW                     | 1         | 1.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 2         | 40%     |
| Hewlett-Packard | 2         | 40%     |
| Canon           | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 20%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1         | 20%     |
| HP ScanJet 2400c                                        | 1         | 20%     |
| HP ScanJet 2200c                                        | 1         | 20%     |
| Canon CanoScan LiDE 200                                 | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 313       | 22.53%  |
| IMC Networks                           | 157       | 11.3%   |
| Logitech                               | 112       | 8.06%   |
| Microdia                               | 107       | 7.7%    |
| Realtek Semiconductor                  | 99        | 7.13%   |
| Bison Electronics                      | 91        | 6.55%   |
| Sunplus Innovation Technology          | 72        | 5.18%   |
| Quanta                                 | 58        | 4.18%   |
| Apple                                  | 45        | 3.24%   |
| Cheng Uei Precision Industry (Foxlink) | 40        | 2.88%   |
| Syntek                                 | 33        | 2.38%   |
| Acer                                   | 30        | 2.16%   |
| Lite-On Technology                     | 26        | 1.87%   |
| Suyin                                  | 22        | 1.58%   |
| Luxvisions Innotech Limited            | 16        | 1.15%   |
| Sonix Technology                       | 14        | 1.01%   |
| Silicon Motion                         | 13        | 0.94%   |
| Microsoft                              | 13        | 0.94%   |
| Samsung Electronics                    | 12        | 0.86%   |
| Lenovo                                 | 11        | 0.79%   |
| Alcor Micro                            | 7         | 0.5%    |
| Primax Electronics                     | 6         | 0.43%   |
| Generalplus Technology                 | 6         | 0.43%   |
| Razer USA                              | 5         | 0.36%   |
| KYE Systems (Mouse Systems)            | 5         | 0.36%   |
| GEMBIRD                                | 5         | 0.36%   |
| Creative Technology                    | 5         | 0.36%   |
| Hewlett-Packard                        | 4         | 0.29%   |
| Z-Star Microelectronics                | 3         | 0.22%   |
| Ricoh                                  | 3         | 0.22%   |
| MacroSilicon                           | 3         | 0.22%   |
| Importek                               | 3         | 0.22%   |
| ARC International                      | 3         | 0.22%   |
| WaveRider Communications               | 2         | 0.14%   |
| SunplusIT                              | 2         | 0.14%   |
| Sunplus Technology                     | 2         | 0.14%   |
| Ruision                                | 2         | 0.14%   |
| OPPO Electronics                       | 2         | 0.14%   |
| icSpring                               | 2         | 0.14%   |
| Hopewin Electronic Material            | 2         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 85        | 6.08%   |
| IMC Networks Integrated Camera                      | 49        | 3.51%   |
| Microdia Integrated_Webcam_HD                       | 43        | 3.08%   |
| Realtek Integrated_Webcam_HD                        | 38        | 2.72%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 38        | 2.72%   |
| Chicony HD WebCam                                   | 32        | 2.29%   |
| Logitech HD Pro Webcam C920                         | 25        | 1.79%   |
| Bison Integrated Camera                             | 23        | 1.65%   |
| Logitech Webcam C270                                | 22        | 1.57%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 22        | 1.57%   |
| Syntek Integrated Camera                            | 21        | 1.5%    |
| Sunplus Integrated_Webcam_HD                        | 21        | 1.5%    |
| Logitech C922 Pro Stream Webcam                     | 16        | 1.15%   |
| Lite-On Integrated Camera                           | 16        | 1.15%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 16        | 1.15%   |
| Acer Integrated Camera                              | 16        | 1.15%   |
| Chicony USB2.0 Camera                               | 14        | 1%      |
| Chicony HP Wide Vision HD Camera                    | 13        | 0.93%   |
| Samsung Galaxy series, misc. (MTP mode)             | 12        | 0.86%   |
| Chicony USB2.0 VGA UVC WebCam                       | 12        | 0.86%   |
| Bison HD Webcam                                     | 12        | 0.86%   |
| Apple Built-in iSight                               | 12        | 0.86%   |
| Quanta HP TrueVision HD Camera                      | 11        | 0.79%   |
| Chicony Integrated Camera (1280x720@30)             | 11        | 0.79%   |
| Chicony HP Truevision HD                            | 11        | 0.79%   |
| Quanta HD Webcam                                    | 10        | 0.72%   |
| Quanta HD User Facing                               | 10        | 0.72%   |
| Microdia Integrated Webcam                          | 10        | 0.72%   |
| Chicony HP TrueVision HD Camera                     | 10        | 0.72%   |
| Chicony HP HD Camera                                | 10        | 0.72%   |
| Chicony EasyCamera                                  | 10        | 0.72%   |
| Bison EasyCamera                                    | 10        | 0.72%   |
| Sonix USB2.0 HD UVC WebCam                          | 9         | 0.64%   |
| Bison BisonCam,NB Pro                               | 9         | 0.64%   |
| Sunplus Full HD webcam                              | 8         | 0.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 8         | 0.57%   |
| Chicony USB2.0 HD UVC WebCam                        | 8         | 0.57%   |
| Chicony TOSHIBA Web Camera - HD                     | 8         | 0.57%   |
| Chicony HD User Facing                              | 8         | 0.57%   |
| Bison Lenovo EasyCamera                             | 8         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 88        | 37.29%  |
| Synaptics                          | 65        | 27.54%  |
| Shenzhen Goodix Technology         | 35        | 14.83%  |
| Elan Microelectronics              | 15        | 6.36%   |
| Upek                               | 12        | 5.08%   |
| LighTuning Technology              | 12        | 5.08%   |
| AuthenTec                          | 6         | 2.54%   |
| STMicroelectronics                 | 1         | 0.42%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.42%   |
| DigitalPersona                     | 1         | 0.42%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 22        | 9.32%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 8.9%    |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 7.63%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 5.51%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 5.51%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 5.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 5.08%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 4.24%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 3.39%   |
| Elan ELAN:Fingerprint                                                      | 8         | 3.39%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 2.97%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.97%   |
| Synaptics  WBDI                                                            | 7         | 2.97%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 2.97%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 2.12%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 2.12%   |
| Elan ELAN:ARM-M4                                                           | 5         | 2.12%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.27%   |
| Synaptics WBDI                                                             | 3         | 1.27%   |
| Synaptics UWP WBDI                                                         | 3         | 1.27%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.27%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.85%   |
| Validity Sensors VFS491                                                    | 2         | 0.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.85%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.85%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.85%   |
| Synaptics WBDI Device                                                      | 2         | 0.85%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.85%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.85%   |
| AuthenTec AES1600                                                          | 2         | 0.85%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.42%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.42%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.42%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.42%   |
| Synaptics TouchPad                                                         | 1         | 0.42%   |
| Synaptics Fingerprint scanner                                              | 1         | 0.42%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 45        | 43.27%  |
| Broadcom              | 36        | 34.62%  |
| O2 Micro              | 6         | 5.77%   |
| Upek                  | 5         | 4.81%   |
| Lenovo                | 4         | 3.85%   |
| Gemalto (was Gemplus) | 2         | 1.92%   |
| Yubico.com            | 1         | 0.96%   |
| SCM Microsystems      | 1         | 0.96%   |
| OmniKey               | 1         | 0.96%   |
| Clay Logic            | 1         | 0.96%   |
| Cherry                | 1         | 0.96%   |
| Aladdin R.D.          | 1         | 0.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 45        | 43.27%  |
| Broadcom 5880                                                                | 14        | 13.46%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 7.69%   |
| Broadcom 58200                                                               | 7         | 6.73%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 5.77%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.81%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 4.81%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 3.85%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.92%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.96%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.96%   |
| OmniKey CardMan 1021                                                         | 1         | 0.96%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.96%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.96%   |
| Cherry Smart Card Reader USB                                                 | 1         | 0.96%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.96%   |
| Aladdin R.D. JaCarta LT                                                      | 1         | 0.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1726      | 73.95%  |
| 1     | 491       | 21.04%  |
| 2     | 108       | 4.63%   |
| 3     | 5         | 0.21%   |
| 4     | 4         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 236       | 33.33%  |
| Graphics card            | 177       | 25%     |
| Chipcard                 | 99        | 13.98%  |
| Net/wireless             | 61        | 8.62%   |
| Multimedia controller    | 33        | 4.66%   |
| Camera                   | 30        | 4.24%   |
| Unassigned class         | 18        | 2.54%   |
| Communication controller | 17        | 2.4%    |
| Bluetooth                | 11        | 1.55%   |
| Network                  | 5         | 0.71%   |
| Net/ethernet             | 5         | 0.71%   |
| Card reader              | 5         | 0.71%   |
| Storage/nvme             | 2         | 0.28%   |
| Storage                  | 2         | 0.28%   |
| Sound                    | 2         | 0.28%   |
| Modem                    | 2         | 0.28%   |
| Dvb card                 | 2         | 0.28%   |
| Wireless                 | 1         | 0.14%   |

