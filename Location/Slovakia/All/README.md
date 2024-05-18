Linux in Slovakia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovakia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Slovakia/Desktop/README.md) and [notebooks](/Location/Slovakia/Notebook/README.md).

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

Total: 1541

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | GT60 2OC/2OD                | Notebook    | [aa9d5951b9](https://linux-hardware.org/?probe=aa9d5951b9) | May 08, 2024 |
| MSI           | GT60 2OC/2OD                | Notebook    | [d71303b21c](https://linux-hardware.org/?probe=d71303b21c) | May 06, 2024 |
| MSI           | GT60 2OC/2OD                | Notebook    | [3330ada128](https://linux-hardware.org/?probe=3330ada128) | May 06, 2024 |
| ASRock        | E350M1/USB3                 | Desktop     | [d82d76d3e5](https://linux-hardware.org/?probe=d82d76d3e5) | May 05, 2024 |
| Dell          | Latitude E6540              | Notebook    | [1e6dfd1900](https://linux-hardware.org/?probe=1e6dfd1900) | May 04, 2024 |
| OEM           | X79-Turbo                   | Desktop     | [9c9327fa63](https://linux-hardware.org/?probe=9c9327fa63) | May 03, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [efce8fa0ba](https://linux-hardware.org/?probe=efce8fa0ba) | May 02, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [90d5348bf5](https://linux-hardware.org/?probe=90d5348bf5) | Apr 28, 2024 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [15d91ebe7c](https://linux-hardware.org/?probe=15d91ebe7c) | Apr 28, 2024 |
| Dell          | Latitude 5420               | Notebook    | [1fa9f586bb](https://linux-hardware.org/?probe=1fa9f586bb) | Apr 27, 2024 |
| Dell          | Latitude 5420               | Notebook    | [5c878504f5](https://linux-hardware.org/?probe=5c878504f5) | Apr 27, 2024 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [e6fa07d931](https://linux-hardware.org/?probe=e6fa07d931) | Apr 25, 2024 |
| Dell          | Latitude 3120               | Convertible | [3b8679ada5](https://linux-hardware.org/?probe=3b8679ada5) | Apr 25, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [31838248fa](https://linux-hardware.org/?probe=31838248fa) | Apr 24, 2024 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [85b36d2613](https://linux-hardware.org/?probe=85b36d2613) | Apr 24, 2024 |
| HP            | Pavilion g7                 | Notebook    | [b700499e3c](https://linux-hardware.org/?probe=b700499e3c) | Apr 21, 2024 |
| Dell          | 0MN1TX A02                  | Desktop     | [2aa151f159](https://linux-hardware.org/?probe=2aa151f159) | Apr 20, 2024 |
| Dell          | 0MN1TX A02                  | Desktop     | [cfac7f54ed](https://linux-hardware.org/?probe=cfac7f54ed) | Apr 20, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [e25b6a6321](https://linux-hardware.org/?probe=e25b6a6321) | Apr 18, 2024 |
| HP            | Unknown                     | Notebook    | [9e1527f7a4](https://linux-hardware.org/?probe=9e1527f7a4) | Apr 17, 2024 |
| HP            | Unknown                     | Notebook    | [3a23f043ac](https://linux-hardware.org/?probe=3a23f043ac) | Apr 17, 2024 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [86ab252a30](https://linux-hardware.org/?probe=86ab252a30) | Apr 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [c5c95abb79](https://linux-hardware.org/?probe=c5c95abb79) | Apr 12, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [1a9697f39d](https://linux-hardware.org/?probe=1a9697f39d) | Apr 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [94f12b2951](https://linux-hardware.org/?probe=94f12b2951) | Apr 11, 2024 |
| HP            | Pavilion g7                 | Notebook    | [6d84e70e34](https://linux-hardware.org/?probe=6d84e70e34) | Apr 10, 2024 |
| Lenovo        | ThinkPad T550 20CKCTO1WW    | Notebook    | [616e9e6be4](https://linux-hardware.org/?probe=616e9e6be4) | Apr 07, 2024 |
| ASUSTek       | P5P43TD/USB3                | Desktop     | [e8ebc10509](https://linux-hardware.org/?probe=e8ebc10509) | Apr 06, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [da60008a10](https://linux-hardware.org/?probe=da60008a10) | Apr 06, 2024 |
| Dell          | Latitude E4300              | Notebook    | [43c75dde9f](https://linux-hardware.org/?probe=43c75dde9f) | Apr 05, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [86ccf9c2ca](https://linux-hardware.org/?probe=86ccf9c2ca) | Apr 05, 2024 |
| Dell          | Latitude E6430              | Notebook    | [c871f1007a](https://linux-hardware.org/?probe=c871f1007a) | Mar 31, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [c498cd96d4](https://linux-hardware.org/?probe=c498cd96d4) | Mar 31, 2024 |
| HP            | EliteBook 840 G4            | Notebook    | [79814f384f](https://linux-hardware.org/?probe=79814f384f) | Mar 28, 2024 |
| HP            | EliteBook 840 G4            | Notebook    | [eea8a3164d](https://linux-hardware.org/?probe=eea8a3164d) | Mar 27, 2024 |
| Acer          | Swift SF14-71T              | Notebook    | [0dcdd95ff5](https://linux-hardware.org/?probe=0dcdd95ff5) | Mar 25, 2024 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [280e11e5cc](https://linux-hardware.org/?probe=280e11e5cc) | Mar 24, 2024 |
| Dell          | 0RN474                      | Desktop     | [665f831546](https://linux-hardware.org/?probe=665f831546) | Mar 24, 2024 |
| HP            | Pavilion dv6                | Notebook    | [9070fdfab3](https://linux-hardware.org/?probe=9070fdfab3) | Mar 23, 2024 |
| Dell          | Latitude 3510               | Notebook    | [2324bf3720](https://linux-hardware.org/?probe=2324bf3720) | Mar 23, 2024 |
| Dell          | Latitude 5590               | Notebook    | [bae9210ad3](https://linux-hardware.org/?probe=bae9210ad3) | Mar 21, 2024 |
| MSI           | GT60 2OC/2OD                | Notebook    | [11156842cb](https://linux-hardware.org/?probe=11156842cb) | Mar 21, 2024 |
| MSI           | MS-7369                     | Desktop     | [0a36f4715f](https://linux-hardware.org/?probe=0a36f4715f) | Mar 21, 2024 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [d2662aa4ae](https://linux-hardware.org/?probe=d2662aa4ae) | Mar 17, 2024 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [a83e990b4e](https://linux-hardware.org/?probe=a83e990b4e) | Mar 13, 2024 |
| OEM           | X79-Turbo                   | Desktop     | [b19889facd](https://linux-hardware.org/?probe=b19889facd) | Mar 12, 2024 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [c50d470e19](https://linux-hardware.org/?probe=c50d470e19) | Mar 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [00ab8a1013](https://linux-hardware.org/?probe=00ab8a1013) | Mar 10, 2024 |
| Acer          | EM61SM/EM61PM               | Desktop     | [1823ab7a07](https://linux-hardware.org/?probe=1823ab7a07) | Mar 04, 2024 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | Notebook    | [9433e012df](https://linux-hardware.org/?probe=9433e012df) | Mar 03, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8e8844631e](https://linux-hardware.org/?probe=8e8844631e) | Feb 27, 2024 |
| Lenovo        | V15 G1 IML 82NB             | Notebook    | [b51e9d56f2](https://linux-hardware.org/?probe=b51e9d56f2) | Feb 27, 2024 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [44cc34fb38](https://linux-hardware.org/?probe=44cc34fb38) | Feb 27, 2024 |
| Acer          | EX5235                      | Notebook    | [98b84f5c24](https://linux-hardware.org/?probe=98b84f5c24) | Feb 27, 2024 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [5239851f48](https://linux-hardware.org/?probe=5239851f48) | Feb 26, 2024 |
| Samsung       | R530/R730/P530              | Notebook    | [a178c4f940](https://linux-hardware.org/?probe=a178c4f940) | Feb 26, 2024 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [d3f9302555](https://linux-hardware.org/?probe=d3f9302555) | Feb 25, 2024 |
| Samsung       | R530/R730/P530              | Notebook    | [4a557d45bc](https://linux-hardware.org/?probe=4a557d45bc) | Feb 25, 2024 |
| Dell          | 0RN474                      | Desktop     | [c2ca6576b9](https://linux-hardware.org/?probe=c2ca6576b9) | Feb 25, 2024 |
| MSI           | MS-7369                     | Desktop     | [d771ce7ed3](https://linux-hardware.org/?probe=d771ce7ed3) | Feb 25, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [6d570ec5af](https://linux-hardware.org/?probe=6d570ec5af) | Feb 24, 2024 |
| Acer          | EX5235                      | Notebook    | [898256f492](https://linux-hardware.org/?probe=898256f492) | Feb 24, 2024 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [f317a83d41](https://linux-hardware.org/?probe=f317a83d41) | Feb 22, 2024 |
| Dell          | Latitude 5590               | Notebook    | [97d36b66b8](https://linux-hardware.org/?probe=97d36b66b8) | Feb 20, 2024 |
| 10ZiG Tech... | 5900q                       | Notebook    | [99b0385f93](https://linux-hardware.org/?probe=99b0385f93) | Feb 19, 2024 |
| Dell          | Vostro 5625                 | Notebook    | [04e53619c6](https://linux-hardware.org/?probe=04e53619c6) | Feb 19, 2024 |
| HP            | Pavilion dv6                | Notebook    | [30a1d043d5](https://linux-hardware.org/?probe=30a1d043d5) | Feb 18, 2024 |
| Dell          | Latitude 5580               | Notebook    | [7525d4aa92](https://linux-hardware.org/?probe=7525d4aa92) | Feb 18, 2024 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [f521933e0c](https://linux-hardware.org/?probe=f521933e0c) | Feb 18, 2024 |
| Dell          | Latitude E5570              | Notebook    | [d1040245b4](https://linux-hardware.org/?probe=d1040245b4) | Feb 18, 2024 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [5214d7970e](https://linux-hardware.org/?probe=5214d7970e) | Feb 17, 2024 |
| Dell          | Inspiron 7566               | Notebook    | [9d3c279e4c](https://linux-hardware.org/?probe=9d3c279e4c) | Feb 16, 2024 |
| Dell          | Studio XPS 1640             | Notebook    | [79baf0c0bf](https://linux-hardware.org/?probe=79baf0c0bf) | Feb 15, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [71764575ba](https://linux-hardware.org/?probe=71764575ba) | Feb 15, 2024 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [7712fbd948](https://linux-hardware.org/?probe=7712fbd948) | Feb 15, 2024 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [9dc94d073a](https://linux-hardware.org/?probe=9dc94d073a) | Feb 15, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [2579f92bcd](https://linux-hardware.org/?probe=2579f92bcd) | Feb 15, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [5b8e7f1992](https://linux-hardware.org/?probe=5b8e7f1992) | Feb 14, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fe21d31fbd](https://linux-hardware.org/?probe=fe21d31fbd) | Feb 14, 2024 |
| TUXEDO        | Sirius 16 Gen1              | Notebook    | [44b101b616](https://linux-hardware.org/?probe=44b101b616) | Feb 14, 2024 |
| Dell          | Latitude 5580               | Notebook    | [37765cd0c7](https://linux-hardware.org/?probe=37765cd0c7) | Feb 12, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [5ba6bba9d7](https://linux-hardware.org/?probe=5ba6bba9d7) | Feb 11, 2024 |
| Lenovo        | ThinkPad E15 20RD001XMC     | Notebook    | [5fe617e8a5](https://linux-hardware.org/?probe=5fe617e8a5) | Feb 08, 2024 |
| Lenovo        | G770 20089                  | Notebook    | [d09f6449fa](https://linux-hardware.org/?probe=d09f6449fa) | Feb 08, 2024 |
| Lenovo        | G770 20089                  | Notebook    | [a11d054bb4](https://linux-hardware.org/?probe=a11d054bb4) | Feb 08, 2024 |
| HP            | ProBook 4545s               | Notebook    | [cc45a314f7](https://linux-hardware.org/?probe=cc45a314f7) | Feb 07, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e4d2896a38](https://linux-hardware.org/?probe=e4d2896a38) | Feb 06, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [89b53566aa](https://linux-hardware.org/?probe=89b53566aa) | Feb 06, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [ecd774856d](https://linux-hardware.org/?probe=ecd774856d) | Feb 06, 2024 |
| MSI           | GT60 2OC/2OD                | Notebook    | [77186f987a](https://linux-hardware.org/?probe=77186f987a) | Feb 05, 2024 |
| ASUSTek       | K53BR                       | Notebook    | [bd5284a0e8](https://linux-hardware.org/?probe=bd5284a0e8) | Feb 02, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [58f11b08b0](https://linux-hardware.org/?probe=58f11b08b0) | Feb 01, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [5f2635ae3a](https://linux-hardware.org/?probe=5f2635ae3a) | Feb 01, 2024 |
| Qualcomm T... | BENGAL IDP                  | Soc         | [0fa5d4252e](https://linux-hardware.org/?probe=0fa5d4252e) | Jan 30, 2024 |
| Qualcomm T... | BENGAL IDP                  | Soc         | [0b276689cb](https://linux-hardware.org/?probe=0b276689cb) | Jan 30, 2024 |
| MSI           | GT60 2OC/2OD                | Notebook    | [182643a957](https://linux-hardware.org/?probe=182643a957) | Jan 29, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [9a7978bd86](https://linux-hardware.org/?probe=9a7978bd86) | Jan 29, 2024 |
| HP            | Pavilion dv6                | Notebook    | [68d4e31014](https://linux-hardware.org/?probe=68d4e31014) | Jan 28, 2024 |
| Qualcomm T... | BENGAL IDP                  | Soc         | [6896cc7cae](https://linux-hardware.org/?probe=6896cc7cae) | Jan 26, 2024 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [961ba7a8a2](https://linux-hardware.org/?probe=961ba7a8a2) | Jan 24, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [88cd6c7ca6](https://linux-hardware.org/?probe=88cd6c7ca6) | Jan 23, 2024 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [1eeda8c8f1](https://linux-hardware.org/?probe=1eeda8c8f1) | Jan 23, 2024 |
| MSI           | GT60 2OC/2OD                | Notebook    | [2a30b19d47](https://linux-hardware.org/?probe=2a30b19d47) | Jan 23, 2024 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [9f48506578](https://linux-hardware.org/?probe=9f48506578) | Jan 23, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [f0a97be10f](https://linux-hardware.org/?probe=f0a97be10f) | Jan 22, 2024 |
| ASUSTek       | N61Jv                       | Notebook    | [ede176e0ca](https://linux-hardware.org/?probe=ede176e0ca) | Jan 21, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402NU... | Notebook    | [9c805e9195](https://linux-hardware.org/?probe=9c805e9195) | Jan 17, 2024 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [41076ef28d](https://linux-hardware.org/?probe=41076ef28d) | Jan 14, 2024 |
| HP            | ProBook 4330s               | Notebook    | [44ddddb2d1](https://linux-hardware.org/?probe=44ddddb2d1) | Jan 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0823cf66ec](https://linux-hardware.org/?probe=0823cf66ec) | Jan 13, 2024 |
| HP            | ProBook 4330s               | Notebook    | [35ef27eb5a](https://linux-hardware.org/?probe=35ef27eb5a) | Jan 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [bc2f7eea4c](https://linux-hardware.org/?probe=bc2f7eea4c) | Jan 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [4ee3e89964](https://linux-hardware.org/?probe=4ee3e89964) | Jan 07, 2024 |
| Acer          | Aspire VN7-791              | Notebook    | [f013dfcc3b](https://linux-hardware.org/?probe=f013dfcc3b) | Jan 05, 2024 |
| HP            | Pavilion dv6                | Notebook    | [d0a6270f74](https://linux-hardware.org/?probe=d0a6270f74) | Jan 04, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [7fc5a1c4d0](https://linux-hardware.org/?probe=7fc5a1c4d0) | Jan 04, 2024 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [bd15a62f1a](https://linux-hardware.org/?probe=bd15a62f1a) | Jan 02, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [1e34cd1559](https://linux-hardware.org/?probe=1e34cd1559) | Jan 01, 2024 |
| Acer          | EX5235                      | Notebook    | [c92709aa57](https://linux-hardware.org/?probe=c92709aa57) | Dec 31, 2023 |
| Acer          | EX5235                      | Notebook    | [4a0cb756ff](https://linux-hardware.org/?probe=4a0cb756ff) | Dec 31, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [815e8736a2](https://linux-hardware.org/?probe=815e8736a2) | Dec 31, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [4dd47839a4](https://linux-hardware.org/?probe=4dd47839a4) | Dec 31, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [895594b67d](https://linux-hardware.org/?probe=895594b67d) | Dec 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [aa1befaf25](https://linux-hardware.org/?probe=aa1befaf25) | Dec 29, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e29421585d](https://linux-hardware.org/?probe=e29421585d) | Dec 28, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [d0a3fb037a](https://linux-hardware.org/?probe=d0a3fb037a) | Dec 28, 2023 |
| Dell          | Latitude E6430              | Notebook    | [a5ce676225](https://linux-hardware.org/?probe=a5ce676225) | Dec 27, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e741a22dc6](https://linux-hardware.org/?probe=e741a22dc6) | Dec 27, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [ab14001c30](https://linux-hardware.org/?probe=ab14001c30) | Dec 27, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [52f704d54a](https://linux-hardware.org/?probe=52f704d54a) | Dec 26, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [9eccf6133e](https://linux-hardware.org/?probe=9eccf6133e) | Dec 25, 2023 |
| Lenovo        | 3115 SDK0J40697 WIN 3305... | All in one  | [69406da1d4](https://linux-hardware.org/?probe=69406da1d4) | Dec 23, 2023 |
| HP            | ProBook 4330s               | Notebook    | [fce67d52c0](https://linux-hardware.org/?probe=fce67d52c0) | Dec 22, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [980f7dfed7](https://linux-hardware.org/?probe=980f7dfed7) | Dec 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6311def15e](https://linux-hardware.org/?probe=6311def15e) | Dec 21, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [5fa215a8cd](https://linux-hardware.org/?probe=5fa215a8cd) | Dec 21, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [d33b5845ef](https://linux-hardware.org/?probe=d33b5845ef) | Dec 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [6235a63aa5](https://linux-hardware.org/?probe=6235a63aa5) | Dec 17, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [a845742a42](https://linux-hardware.org/?probe=a845742a42) | Dec 17, 2023 |
| Dell          | Latitude E7450              | Notebook    | [f429af38c1](https://linux-hardware.org/?probe=f429af38c1) | Dec 17, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [1909f0bbc0](https://linux-hardware.org/?probe=1909f0bbc0) | Dec 16, 2023 |
| ASUSTek       | P5E WS Pro                  | Desktop     | [9c68d265b1](https://linux-hardware.org/?probe=9c68d265b1) | Dec 12, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [5b6d840c0a](https://linux-hardware.org/?probe=5b6d840c0a) | Dec 12, 2023 |
| Dell          | Latitude 5400               | Notebook    | [b4317f7856](https://linux-hardware.org/?probe=b4317f7856) | Dec 11, 2023 |
| Acer          | Extensa 5630                | Notebook    | [4709657363](https://linux-hardware.org/?probe=4709657363) | Dec 11, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [2a22b3adb4](https://linux-hardware.org/?probe=2a22b3adb4) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8395e5f595](https://linux-hardware.org/?probe=8395e5f595) | Dec 08, 2023 |
| HP            | 8184 X4                     | Desktop     | [bad08bc9a0](https://linux-hardware.org/?probe=bad08bc9a0) | Dec 07, 2023 |
| ASUSTek       | K54C                        | Notebook    | [8f1abfdd9a](https://linux-hardware.org/?probe=8f1abfdd9a) | Dec 03, 2023 |
| ASUSTek       | K54C                        | Notebook    | [6702d5257d](https://linux-hardware.org/?probe=6702d5257d) | Dec 03, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [8b11ad9f77](https://linux-hardware.org/?probe=8b11ad9f77) | Dec 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0869816e7a](https://linux-hardware.org/?probe=0869816e7a) | Dec 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [6c2a58400d](https://linux-hardware.org/?probe=6c2a58400d) | Dec 01, 2023 |
| HP            | Pavilion dv6                | Notebook    | [6ee138ba11](https://linux-hardware.org/?probe=6ee138ba11) | Dec 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [9d88b4ad0b](https://linux-hardware.org/?probe=9d88b4ad0b) | Nov 28, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [f813230b08](https://linux-hardware.org/?probe=f813230b08) | Nov 27, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [206d92bed2](https://linux-hardware.org/?probe=206d92bed2) | Nov 27, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [bd533274c5](https://linux-hardware.org/?probe=bd533274c5) | Nov 27, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [23d18fc15e](https://linux-hardware.org/?probe=23d18fc15e) | Nov 27, 2023 |
| Lenovo        | ThinkPad L480 20LS0015UK    | Notebook    | [5f786955fc](https://linux-hardware.org/?probe=5f786955fc) | Nov 26, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [bb4bd3eceb](https://linux-hardware.org/?probe=bb4bd3eceb) | Nov 26, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [11086675c9](https://linux-hardware.org/?probe=11086675c9) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3545a1a483](https://linux-hardware.org/?probe=3545a1a483) | Nov 26, 2023 |
| HP            | Pavilion dv6                | Notebook    | [2f757867e7](https://linux-hardware.org/?probe=2f757867e7) | Nov 26, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [41443f69e3](https://linux-hardware.org/?probe=41443f69e3) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5a01c502bd](https://linux-hardware.org/?probe=5a01c502bd) | Nov 24, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [38e1d661bf](https://linux-hardware.org/?probe=38e1d661bf) | Nov 23, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [8806cbd1e7](https://linux-hardware.org/?probe=8806cbd1e7) | Nov 23, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [e2f9466842](https://linux-hardware.org/?probe=e2f9466842) | Nov 19, 2023 |
| UMAX          | 13Wa_Flex                   | Notebook    | [621a71f736](https://linux-hardware.org/?probe=621a71f736) | Nov 19, 2023 |
| ASUSTek       | Z97I-PLUS                   | Desktop     | [71d854d842](https://linux-hardware.org/?probe=71d854d842) | Nov 19, 2023 |
| Lenovo        | 3000 V100 076346G           | Notebook    | [039632f3f3](https://linux-hardware.org/?probe=039632f3f3) | Nov 18, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [8d6d23926d](https://linux-hardware.org/?probe=8d6d23926d) | Nov 17, 2023 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [8031c90846](https://linux-hardware.org/?probe=8031c90846) | Nov 17, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [a29bea944f](https://linux-hardware.org/?probe=a29bea944f) | Nov 16, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [3648bc5b55](https://linux-hardware.org/?probe=3648bc5b55) | Nov 16, 2023 |
| ASUSTek       | Pro H610T D4                | Desktop     | [efbbe2e3e0](https://linux-hardware.org/?probe=efbbe2e3e0) | Nov 15, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [1b5d69b7ed](https://linux-hardware.org/?probe=1b5d69b7ed) | Nov 14, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [9ffde477ac](https://linux-hardware.org/?probe=9ffde477ac) | Nov 12, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [c0932e879f](https://linux-hardware.org/?probe=c0932e879f) | Nov 11, 2023 |
| ASUSTek       | Pro H610T D4                | Desktop     | [3e803b61d3](https://linux-hardware.org/?probe=3e803b61d3) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [2a8696e0f5](https://linux-hardware.org/?probe=2a8696e0f5) | Nov 10, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [0ec19aab02](https://linux-hardware.org/?probe=0ec19aab02) | Nov 10, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [8bdabebc5b](https://linux-hardware.org/?probe=8bdabebc5b) | Nov 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [ca05ff684b](https://linux-hardware.org/?probe=ca05ff684b) | Nov 09, 2023 |
| HP            | 255 15.6 inch G10 Notebo... | Notebook    | [df5983435c](https://linux-hardware.org/?probe=df5983435c) | Nov 08, 2023 |
| Dell          | Latitude E7270              | Notebook    | [0410c1ba06](https://linux-hardware.org/?probe=0410c1ba06) | Nov 08, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [ef707f88ea](https://linux-hardware.org/?probe=ef707f88ea) | Nov 08, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [68f36bd8cc](https://linux-hardware.org/?probe=68f36bd8cc) | Nov 08, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [0d65b73ae2](https://linux-hardware.org/?probe=0d65b73ae2) | Nov 07, 2023 |
| ASUSTek       | Z10PA-D8 Series             | Desktop     | [b865e2f52d](https://linux-hardware.org/?probe=b865e2f52d) | Nov 07, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | Notebook    | [d0d84fed9a](https://linux-hardware.org/?probe=d0d84fed9a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| HP            | Pavilion dv6                | Notebook    | [bf6361ff84](https://linux-hardware.org/?probe=bf6361ff84) | Nov 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [0b00fd801c](https://linux-hardware.org/?probe=0b00fd801c) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [7c297acb1f](https://linux-hardware.org/?probe=7c297acb1f) | Nov 01, 2023 |
| Dell          | 0RN474                      | Desktop     | [0ae8ddb9b3](https://linux-hardware.org/?probe=0ae8ddb9b3) | Nov 01, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [27d8415c88](https://linux-hardware.org/?probe=27d8415c88) | Nov 01, 2023 |
| Lenovo        | ThinkPad T490 20N3000FRT    | Notebook    | [14710d3709](https://linux-hardware.org/?probe=14710d3709) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [b553bb2a36](https://linux-hardware.org/?probe=b553bb2a36) | Oct 31, 2023 |
| ASUSTek       | H81T                        | Desktop     | [7986b7269f](https://linux-hardware.org/?probe=7986b7269f) | Oct 31, 2023 |
| Dell          | Latitude E7250              | Notebook    | [a83b95ce44](https://linux-hardware.org/?probe=a83b95ce44) | Oct 30, 2023 |
| Lenovo        | B575 Brazos                 | Notebook    | [189361193e](https://linux-hardware.org/?probe=189361193e) | Oct 29, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [fa410ee23c](https://linux-hardware.org/?probe=fa410ee23c) | Oct 29, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [16417bdac2](https://linux-hardware.org/?probe=16417bdac2) | Oct 29, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b094266385](https://linux-hardware.org/?probe=b094266385) | Oct 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d0cea8f6bb](https://linux-hardware.org/?probe=d0cea8f6bb) | Oct 28, 2023 |
| HP            | 250 15.6 inch G10 Notebo... | Notebook    | [f5f8e6f37d](https://linux-hardware.org/?probe=f5f8e6f37d) | Oct 21, 2023 |
| HP            | ProBook 4535s               | Notebook    | [e52e92c95b](https://linux-hardware.org/?probe=e52e92c95b) | Oct 14, 2023 |
| Gigabyte      | HA65M-UD3H-B3               | Desktop     | [8e445c2bc4](https://linux-hardware.org/?probe=8e445c2bc4) | Oct 11, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [1d1d1e17eb](https://linux-hardware.org/?probe=1d1d1e17eb) | Oct 11, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [12d88836d5](https://linux-hardware.org/?probe=12d88836d5) | Oct 11, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [fd43a8ef45](https://linux-hardware.org/?probe=fd43a8ef45) | Oct 04, 2023 |
| Sony          | VPCEJ1L1E                   | Notebook    | [a51252de41](https://linux-hardware.org/?probe=a51252de41) | Oct 03, 2023 |
| MSI           | MS-1651 Ver                 | Notebook    | [7450925b18](https://linux-hardware.org/?probe=7450925b18) | Oct 02, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [f8033479b2](https://linux-hardware.org/?probe=f8033479b2) | Oct 02, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [0166816d1b](https://linux-hardware.org/?probe=0166816d1b) | Oct 01, 2023 |
| Dell          | Latitude E7270              | Notebook    | [bf1def4fc3](https://linux-hardware.org/?probe=bf1def4fc3) | Oct 01, 2023 |
| Packard Be... | DOT S                       | Notebook    | [ccf952e34c](https://linux-hardware.org/?probe=ccf952e34c) | Sep 28, 2023 |
| HP            | Notebook                    | Notebook    | [b13debd2fa](https://linux-hardware.org/?probe=b13debd2fa) | Sep 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [d656cacdd8](https://linux-hardware.org/?probe=d656cacdd8) | Sep 26, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [794f8f35c8](https://linux-hardware.org/?probe=794f8f35c8) | Sep 25, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [89ba5bd7dd](https://linux-hardware.org/?probe=89ba5bd7dd) | Sep 25, 2023 |
| MSI           | MS-1651 Ver                 | Notebook    | [93cfb04861](https://linux-hardware.org/?probe=93cfb04861) | Sep 23, 2023 |
| MSI           | MS-1651 Ver                 | Notebook    | [e71155ca01](https://linux-hardware.org/?probe=e71155ca01) | Sep 23, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [c86094eac8](https://linux-hardware.org/?probe=c86094eac8) | Sep 23, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [caa45f79f6](https://linux-hardware.org/?probe=caa45f79f6) | Sep 22, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [0b5a8a95dc](https://linux-hardware.org/?probe=0b5a8a95dc) | Sep 22, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [4f3d36e0bd](https://linux-hardware.org/?probe=4f3d36e0bd) | Sep 22, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [be3d2f3d77](https://linux-hardware.org/?probe=be3d2f3d77) | Sep 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [ed4753b8e2](https://linux-hardware.org/?probe=ed4753b8e2) | Sep 21, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [f0173f0458](https://linux-hardware.org/?probe=f0173f0458) | Sep 20, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | Notebook    | [b7d1f6f3cf](https://linux-hardware.org/?probe=b7d1f6f3cf) | Sep 20, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [128763445e](https://linux-hardware.org/?probe=128763445e) | Sep 14, 2023 |
| HP            | 86FB MVB A                  | Desktop     | [cdb3ae1787](https://linux-hardware.org/?probe=cdb3ae1787) | Sep 14, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| HP            | ProBook 4740s               | Notebook    | [7166a2d286](https://linux-hardware.org/?probe=7166a2d286) | Sep 12, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [752a87de3b](https://linux-hardware.org/?probe=752a87de3b) | Sep 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [dbad37486d](https://linux-hardware.org/?probe=dbad37486d) | Sep 11, 2023 |
| HP            | 304Ah                       | Desktop     | [fe71b825fd](https://linux-hardware.org/?probe=fe71b825fd) | Sep 11, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [5dde8dd026](https://linux-hardware.org/?probe=5dde8dd026) | Sep 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b5ea617856](https://linux-hardware.org/?probe=b5ea617856) | Sep 08, 2023 |
| ASUSTek       | PRIME B650M-A II            | Desktop     | [307ca05754](https://linux-hardware.org/?probe=307ca05754) | Sep 06, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [7ae653c6c1](https://linux-hardware.org/?probe=7ae653c6c1) | Sep 05, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [faac131992](https://linux-hardware.org/?probe=faac131992) | Sep 05, 2023 |
| ASUSTek       | P5P43TD/USB3                | Desktop     | [619032e1d0](https://linux-hardware.org/?probe=619032e1d0) | Sep 04, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [09e7a8c91b](https://linux-hardware.org/?probe=09e7a8c91b) | Sep 04, 2023 |
| HP            | Pavilion dv6                | Notebook    | [cf6a67d073](https://linux-hardware.org/?probe=cf6a67d073) | Sep 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [35e2cffa7f](https://linux-hardware.org/?probe=35e2cffa7f) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [db2e607ae6](https://linux-hardware.org/?probe=db2e607ae6) | Sep 02, 2023 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | Notebook    | [d70ba1aaf4](https://linux-hardware.org/?probe=d70ba1aaf4) | Sep 01, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [f341ee514c](https://linux-hardware.org/?probe=f341ee514c) | Aug 30, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [6f5bafed6c](https://linux-hardware.org/?probe=6f5bafed6c) | Aug 30, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [ed71da8f69](https://linux-hardware.org/?probe=ed71da8f69) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [48450e1a26](https://linux-hardware.org/?probe=48450e1a26) | Aug 29, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [998ee50b04](https://linux-hardware.org/?probe=998ee50b04) | Aug 27, 2023 |
| Toshiba       | Satellite P770              | Notebook    | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e6d5fa7bc](https://linux-hardware.org/?probe=7e6d5fa7bc) | Aug 25, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [037e041959](https://linux-hardware.org/?probe=037e041959) | Aug 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [0e86c5864d](https://linux-hardware.org/?probe=0e86c5864d) | Aug 24, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [475563b8b4](https://linux-hardware.org/?probe=475563b8b4) | Aug 24, 2023 |
| HC Technol... | HCAR357-NR                  | Desktop     | [3cd017db11](https://linux-hardware.org/?probe=3cd017db11) | Aug 24, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [7975d95ea8](https://linux-hardware.org/?probe=7975d95ea8) | Aug 21, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [e610051fdc](https://linux-hardware.org/?probe=e610051fdc) | Aug 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a6d62bc041](https://linux-hardware.org/?probe=a6d62bc041) | Aug 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [867105e269](https://linux-hardware.org/?probe=867105e269) | Aug 18, 2023 |
| Lenovo        | ThinkPad X200 7459Y8Y       | Notebook    | [3a707993c2](https://linux-hardware.org/?probe=3a707993c2) | Aug 16, 2023 |
| Lenovo        | ThinkPad X200 7459Y8Y       | Notebook    | [2f98dd0ac1](https://linux-hardware.org/?probe=2f98dd0ac1) | Aug 16, 2023 |
| ASRock        | Z270 Killer SLI             | Desktop     | [10d0229ef0](https://linux-hardware.org/?probe=10d0229ef0) | Aug 16, 2023 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [e54e05ccb1](https://linux-hardware.org/?probe=e54e05ccb1) | Aug 15, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e63deac9b1](https://linux-hardware.org/?probe=e63deac9b1) | Aug 13, 2023 |
| HP            | Pavilion g7                 | Notebook    | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Acer          | Extensa 5220                | Notebook    | [92605dd73d](https://linux-hardware.org/?probe=92605dd73d) | Aug 12, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [b92a6f8a9e](https://linux-hardware.org/?probe=b92a6f8a9e) | Aug 12, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [031ed1d4e7](https://linux-hardware.org/?probe=031ed1d4e7) | Aug 12, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [30c7051967](https://linux-hardware.org/?probe=30c7051967) | Aug 11, 2023 |
| HP            | ProBook 4330s               | Notebook    | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | Notebook    | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| ASUSTek       | F3L                         | Notebook    | [b97c082eff](https://linux-hardware.org/?probe=b97c082eff) | Aug 09, 2023 |
| Dell          | 0RN474                      | Desktop     | [61153fe575](https://linux-hardware.org/?probe=61153fe575) | Aug 09, 2023 |
| ASUSTek       | G750JW                      | Notebook    | [fe527d6231](https://linux-hardware.org/?probe=fe527d6231) | Aug 08, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [c160e44518](https://linux-hardware.org/?probe=c160e44518) | Aug 08, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [b4326c3c45](https://linux-hardware.org/?probe=b4326c3c45) | Aug 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [14114ca4aa](https://linux-hardware.org/?probe=14114ca4aa) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [946d81eb9d](https://linux-hardware.org/?probe=946d81eb9d) | Aug 07, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [64803a4cd7](https://linux-hardware.org/?probe=64803a4cd7) | Aug 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| Dell          | Latitude 3510               | Notebook    | [8bfe0fe5fb](https://linux-hardware.org/?probe=8bfe0fe5fb) | Jul 30, 2023 |
| Dell          | Latitude E5570              | Notebook    | [1f9be76313](https://linux-hardware.org/?probe=1f9be76313) | Jul 30, 2023 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [451cbfaee5](https://linux-hardware.org/?probe=451cbfaee5) | Jul 29, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [ec84069efb](https://linux-hardware.org/?probe=ec84069efb) | Jul 28, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [89557d5880](https://linux-hardware.org/?probe=89557d5880) | Jul 28, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [aad0018c0e](https://linux-hardware.org/?probe=aad0018c0e) | Jul 20, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [37a65534a3](https://linux-hardware.org/?probe=37a65534a3) | Jul 18, 2023 |
| ASUSTek       | X505BA                      | Notebook    | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [252f8adf16](https://linux-hardware.org/?probe=252f8adf16) | Jul 15, 2023 |
| Lenovo        | ThinkPad T460s 20FAS42W0... | Notebook    | [add1dac3cb](https://linux-hardware.org/?probe=add1dac3cb) | Jul 11, 2023 |
| ASUSTek       | N61Vn                       | Notebook    | [6bbb5b2105](https://linux-hardware.org/?probe=6bbb5b2105) | Jul 10, 2023 |
| ASUSTek       | N61Vn                       | Notebook    | [dd1a0f1acf](https://linux-hardware.org/?probe=dd1a0f1acf) | Jul 10, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [d36574de10](https://linux-hardware.org/?probe=d36574de10) | Jul 03, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [68daff498d](https://linux-hardware.org/?probe=68daff498d) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [f587b9a46c](https://linux-hardware.org/?probe=f587b9a46c) | Jul 02, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [f60ead06fd](https://linux-hardware.org/?probe=f60ead06fd) | Jun 28, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ec6a70b7d4](https://linux-hardware.org/?probe=ec6a70b7d4) | Jun 27, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [7fbf9c4e53](https://linux-hardware.org/?probe=7fbf9c4e53) | Jun 25, 2023 |
| Foxconn       | 945 7MC Series              | Desktop     | [dc2911bfae](https://linux-hardware.org/?probe=dc2911bfae) | Jun 25, 2023 |
| Foxconn       | 945 7MC Series              | Desktop     | [273bec93a4](https://linux-hardware.org/?probe=273bec93a4) | Jun 25, 2023 |
| ASUSTek       | P5K                         | Desktop     | [c33ff02489](https://linux-hardware.org/?probe=c33ff02489) | Jun 24, 2023 |
| ASUSTek       | P5K                         | Desktop     | [c87e87b883](https://linux-hardware.org/?probe=c87e87b883) | Jun 24, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [4e7d62b30a](https://linux-hardware.org/?probe=4e7d62b30a) | Jun 21, 2023 |
| Acer          | Aspire VN7-792G             | Notebook    | [ab55f9b492](https://linux-hardware.org/?probe=ab55f9b492) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5141d5dd1a](https://linux-hardware.org/?probe=5141d5dd1a) | Jun 15, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [5732495ae1](https://linux-hardware.org/?probe=5732495ae1) | Jun 14, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [9a8a71741e](https://linux-hardware.org/?probe=9a8a71741e) | Jun 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [5349772ea1](https://linux-hardware.org/?probe=5349772ea1) | Jun 14, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [edbcec7f32](https://linux-hardware.org/?probe=edbcec7f32) | Jun 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c0d6d68272](https://linux-hardware.org/?probe=c0d6d68272) | Jun 12, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [f5a1226b72](https://linux-hardware.org/?probe=f5a1226b72) | Jun 12, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [9d9872a84a](https://linux-hardware.org/?probe=9d9872a84a) | Jun 10, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [012e8255f3](https://linux-hardware.org/?probe=012e8255f3) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [bd22edfae7](https://linux-hardware.org/?probe=bd22edfae7) | Jun 09, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [a6c222681d](https://linux-hardware.org/?probe=a6c222681d) | Jun 09, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [3063c26aca](https://linux-hardware.org/?probe=3063c26aca) | Jun 08, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| MSI           | MS-7513                     | Desktop     | [ed69341f3c](https://linux-hardware.org/?probe=ed69341f3c) | Jun 07, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [ed3b6abc56](https://linux-hardware.org/?probe=ed3b6abc56) | Jun 05, 2023 |
| Dell          | Latitude E4300              | Notebook    | [cfd95b7e5e](https://linux-hardware.org/?probe=cfd95b7e5e) | Jun 05, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [d8f9165fec](https://linux-hardware.org/?probe=d8f9165fec) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7b513e678c](https://linux-hardware.org/?probe=7b513e678c) | Jun 03, 2023 |
| ASRock        | ALiveDual-eSATA2            | Desktop     | [0f490d3b39](https://linux-hardware.org/?probe=0f490d3b39) | Jun 01, 2023 |
| Lenovo        | ThinkPad X61 76738AG        | Notebook    | [7f52d18c2f](https://linux-hardware.org/?probe=7f52d18c2f) | May 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [5d33af1d5a](https://linux-hardware.org/?probe=5d33af1d5a) | May 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [6872b07bb6](https://linux-hardware.org/?probe=6872b07bb6) | May 30, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b0be576b32](https://linux-hardware.org/?probe=b0be576b32) | May 28, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [f2181d0270](https://linux-hardware.org/?probe=f2181d0270) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | Desktop     | [be58596103](https://linux-hardware.org/?probe=be58596103) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | Desktop     | [0eedc4211a](https://linux-hardware.org/?probe=0eedc4211a) | May 27, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [7284c23b76](https://linux-hardware.org/?probe=7284c23b76) | May 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [278fefa10a](https://linux-hardware.org/?probe=278fefa10a) | May 24, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6ab7e9c82d](https://linux-hardware.org/?probe=6ab7e9c82d) | May 23, 2023 |
| Lenovo        | ThinkPad T410s 2904FAG      | Notebook    | [742f2c09c5](https://linux-hardware.org/?probe=742f2c09c5) | May 21, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [60ec2d6e04](https://linux-hardware.org/?probe=60ec2d6e04) | May 21, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [51827f5ae5](https://linux-hardware.org/?probe=51827f5ae5) | May 19, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ada9095c92](https://linux-hardware.org/?probe=ada9095c92) | May 19, 2023 |
| UMAX          | VisionBook 13Wg Flex        | Convertible | [170db25383](https://linux-hardware.org/?probe=170db25383) | May 17, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [89e05e4477](https://linux-hardware.org/?probe=89e05e4477) | May 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [a1fb71ff2f](https://linux-hardware.org/?probe=a1fb71ff2f) | May 17, 2023 |
| ASUSTek       | P5E WS Pro                  | Desktop     | [97a221407d](https://linux-hardware.org/?probe=97a221407d) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Samsung       | R530/R730/P530              | Notebook    | [9f619133b7](https://linux-hardware.org/?probe=9f619133b7) | May 15, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [032080c4ef](https://linux-hardware.org/?probe=032080c4ef) | May 13, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a11f5f3f98](https://linux-hardware.org/?probe=a11f5f3f98) | May 13, 2023 |
| HP            | 1589                        | Desktop     | [c905464231](https://linux-hardware.org/?probe=c905464231) | May 11, 2023 |
| MSI           | MS-7513                     | Desktop     | [1e14e5d3e6](https://linux-hardware.org/?probe=1e14e5d3e6) | May 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [68afb54270](https://linux-hardware.org/?probe=68afb54270) | May 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [733703c761](https://linux-hardware.org/?probe=733703c761) | May 09, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [4ab42c06ea](https://linux-hardware.org/?probe=4ab42c06ea) | May 09, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [0952e2922b](https://linux-hardware.org/?probe=0952e2922b) | May 09, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [fca1201c9f](https://linux-hardware.org/?probe=fca1201c9f) | May 07, 2023 |
| HP            | Pavilion g6                 | Notebook    | [d6e340501e](https://linux-hardware.org/?probe=d6e340501e) | May 07, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ae040331e6](https://linux-hardware.org/?probe=ae040331e6) | May 06, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [eb774628af](https://linux-hardware.org/?probe=eb774628af) | May 06, 2023 |
| Unknown       | Unknown                     | Soc         | [2fedff1d10](https://linux-hardware.org/?probe=2fedff1d10) | May 06, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [c78f20f332](https://linux-hardware.org/?probe=c78f20f332) | May 06, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6c8f0f4521](https://linux-hardware.org/?probe=6c8f0f4521) | May 06, 2023 |
| MSI           | A75A-G55                    | Desktop     | [6ecb91213c](https://linux-hardware.org/?probe=6ecb91213c) | May 05, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [8754e79840](https://linux-hardware.org/?probe=8754e79840) | May 04, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [501d26e477](https://linux-hardware.org/?probe=501d26e477) | Apr 30, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [af5d37f4f7](https://linux-hardware.org/?probe=af5d37f4f7) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a2b832afa2](https://linux-hardware.org/?probe=a2b832afa2) | Apr 30, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c8d8595af5](https://linux-hardware.org/?probe=c8d8595af5) | Apr 29, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [7719e2a6c9](https://linux-hardware.org/?probe=7719e2a6c9) | Apr 28, 2023 |
| HP            | 802F                        | Desktop     | [b314d41043](https://linux-hardware.org/?probe=b314d41043) | Apr 28, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [a8e7de2e0b](https://linux-hardware.org/?probe=a8e7de2e0b) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e0f4a4d0f4](https://linux-hardware.org/?probe=e0f4a4d0f4) | Apr 26, 2023 |
| Dell          | 0RCGCR A04                  | Server      | [8ef63cb2de](https://linux-hardware.org/?probe=8ef63cb2de) | Apr 26, 2023 |
| Dell          | Latitude E5570              | Notebook    | [1a6b35e077](https://linux-hardware.org/?probe=1a6b35e077) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [bb520ff82e](https://linux-hardware.org/?probe=bb520ff82e) | Apr 21, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [040d876c1e](https://linux-hardware.org/?probe=040d876c1e) | Apr 16, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [2a389c9c58](https://linux-hardware.org/?probe=2a389c9c58) | Apr 16, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [af0678336d](https://linux-hardware.org/?probe=af0678336d) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [76db4c685b](https://linux-hardware.org/?probe=76db4c685b) | Apr 15, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [845e7bfdd1](https://linux-hardware.org/?probe=845e7bfdd1) | Apr 15, 2023 |
| Acer          | Aspire C24-1650             | All in one  | [9f1a2edf3b](https://linux-hardware.org/?probe=9f1a2edf3b) | Apr 15, 2023 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [e9b6076df4](https://linux-hardware.org/?probe=e9b6076df4) | Apr 13, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [abedf2741f](https://linux-hardware.org/?probe=abedf2741f) | Apr 12, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1a470a3b5a](https://linux-hardware.org/?probe=1a470a3b5a) | Apr 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d24ce5fa44](https://linux-hardware.org/?probe=d24ce5fa44) | Apr 09, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [f7435e4d65](https://linux-hardware.org/?probe=f7435e4d65) | Apr 09, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [53ed0bc068](https://linux-hardware.org/?probe=53ed0bc068) | Apr 09, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [436d55c73e](https://linux-hardware.org/?probe=436d55c73e) | Apr 09, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [90cb74d9f0](https://linux-hardware.org/?probe=90cb74d9f0) | Apr 08, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [95cf4404c3](https://linux-hardware.org/?probe=95cf4404c3) | Apr 08, 2023 |
| Dell          | Latitude E5570              | Notebook    | [7d6ff0e0d8](https://linux-hardware.org/?probe=7d6ff0e0d8) | Apr 07, 2023 |
| Dell          | 03GP4T A01                  | Server      | [621a5675e8](https://linux-hardware.org/?probe=621a5675e8) | Apr 06, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [ba90a2c123](https://linux-hardware.org/?probe=ba90a2c123) | Apr 05, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [dbbe4bbbc5](https://linux-hardware.org/?probe=dbbe4bbbc5) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7c95c976a9](https://linux-hardware.org/?probe=7c95c976a9) | Apr 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [c529f9d1cc](https://linux-hardware.org/?probe=c529f9d1cc) | Apr 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [b9a98e8656](https://linux-hardware.org/?probe=b9a98e8656) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3034a3d11a](https://linux-hardware.org/?probe=3034a3d11a) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2f2326e574](https://linux-hardware.org/?probe=2f2326e574) | Apr 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e45ad193f8](https://linux-hardware.org/?probe=e45ad193f8) | Apr 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [e9fe5cb307](https://linux-hardware.org/?probe=e9fe5cb307) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [59c335754f](https://linux-hardware.org/?probe=59c335754f) | Apr 01, 2023 |
| ASUSTek       | P5E WS Pro                  | Desktop     | [6c70ac23df](https://linux-hardware.org/?probe=6c70ac23df) | Mar 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fcb8359930](https://linux-hardware.org/?probe=fcb8359930) | Mar 28, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [2558605a4b](https://linux-hardware.org/?probe=2558605a4b) | Mar 28, 2023 |
| HP            | 0AACh                       | Desktop     | [43dbfddd1b](https://linux-hardware.org/?probe=43dbfddd1b) | Mar 28, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [502ff745d4](https://linux-hardware.org/?probe=502ff745d4) | Mar 27, 2023 |
| Toshiba       | Satellite C855-1TT          | Notebook    | [ac8e41d993](https://linux-hardware.org/?probe=ac8e41d993) | Mar 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ad7937aaf](https://linux-hardware.org/?probe=3ad7937aaf) | Mar 26, 2023 |
| Dell          | 0RN474                      | Desktop     | [1fb7cf06d1](https://linux-hardware.org/?probe=1fb7cf06d1) | Mar 25, 2023 |
| Dell          | 0RN474                      | Desktop     | [88b56f0530](https://linux-hardware.org/?probe=88b56f0530) | Mar 24, 2023 |
| HP            | 0AACh                       | Desktop     | [2a1f96ca8d](https://linux-hardware.org/?probe=2a1f96ca8d) | Mar 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c17f20a679](https://linux-hardware.org/?probe=c17f20a679) | Mar 23, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [789ca3dc74](https://linux-hardware.org/?probe=789ca3dc74) | Mar 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [468588ab96](https://linux-hardware.org/?probe=468588ab96) | Mar 21, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [60a7dc4c2e](https://linux-hardware.org/?probe=60a7dc4c2e) | Mar 20, 2023 |
| HP            | ProBook 6470b               | Notebook    | [dd23ab1a2e](https://linux-hardware.org/?probe=dd23ab1a2e) | Mar 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1ca9befb7a](https://linux-hardware.org/?probe=1ca9befb7a) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d1a16fdb17](https://linux-hardware.org/?probe=d1a16fdb17) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [08572d5e7c](https://linux-hardware.org/?probe=08572d5e7c) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [82914cf856](https://linux-hardware.org/?probe=82914cf856) | Mar 18, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9c24401930](https://linux-hardware.org/?probe=9c24401930) | Mar 18, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | Notebook    | [c145898fae](https://linux-hardware.org/?probe=c145898fae) | Mar 17, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | Notebook    | [293fe8b4ab](https://linux-hardware.org/?probe=293fe8b4ab) | Mar 17, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [374bab39d7](https://linux-hardware.org/?probe=374bab39d7) | Mar 17, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [4ce2092fe2](https://linux-hardware.org/?probe=4ce2092fe2) | Mar 17, 2023 |
| MSI           | CR500                       | Notebook    | [28eeb3bd71](https://linux-hardware.org/?probe=28eeb3bd71) | Mar 16, 2023 |
| Dell          | Latitude 5580               | Notebook    | [819b5d8dc2](https://linux-hardware.org/?probe=819b5d8dc2) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| Acer          | Aspire VN7-791              | Notebook    | [ca10594901](https://linux-hardware.org/?probe=ca10594901) | Mar 12, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [0b55f12ab3](https://linux-hardware.org/?probe=0b55f12ab3) | Mar 11, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [8e02302d63](https://linux-hardware.org/?probe=8e02302d63) | Mar 09, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [4adcb5ab0f](https://linux-hardware.org/?probe=4adcb5ab0f) | Mar 08, 2023 |
| Acer          | Aspire VN7-792G             | Notebook    | [3b4a3b74a1](https://linux-hardware.org/?probe=3b4a3b74a1) | Mar 07, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [b338e704d9](https://linux-hardware.org/?probe=b338e704d9) | Mar 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [925e02d1dc](https://linux-hardware.org/?probe=925e02d1dc) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [7d9acf8639](https://linux-hardware.org/?probe=7d9acf8639) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0c76255503](https://linux-hardware.org/?probe=0c76255503) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fc28c47011](https://linux-hardware.org/?probe=fc28c47011) | Mar 03, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [aa7d308d7e](https://linux-hardware.org/?probe=aa7d308d7e) | Mar 01, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [dda5eec4b9](https://linux-hardware.org/?probe=dda5eec4b9) | Feb 28, 2023 |
| Gigabyte      | X58A-UD5                    | Desktop     | [4cff35f888](https://linux-hardware.org/?probe=4cff35f888) | Feb 27, 2023 |
| Google        | Voxel                       | Notebook    | [ce917fe8ec](https://linux-hardware.org/?probe=ce917fe8ec) | Feb 25, 2023 |
| Google        | Voxel                       | Notebook    | [93ea143f69](https://linux-hardware.org/?probe=93ea143f69) | Feb 25, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | Notebook    | [faeee1c46c](https://linux-hardware.org/?probe=faeee1c46c) | Feb 24, 2023 |
| HP            | 3397                        | Desktop     | [e714a7b19d](https://linux-hardware.org/?probe=e714a7b19d) | Feb 23, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [db2686086b](https://linux-hardware.org/?probe=db2686086b) | Feb 21, 2023 |
| HP            | 829A                        | Mini pc     | [8791cd83c7](https://linux-hardware.org/?probe=8791cd83c7) | Feb 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [cc3e78f73f](https://linux-hardware.org/?probe=cc3e78f73f) | Feb 18, 2023 |
| ASRock        | B450M Pro4-F R2.0           | Desktop     | [f1082dcffa](https://linux-hardware.org/?probe=f1082dcffa) | Feb 17, 2023 |
| Medion        | P651x series                | Notebook    | [23b3fb7ce5](https://linux-hardware.org/?probe=23b3fb7ce5) | Feb 16, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [528ffce1c7](https://linux-hardware.org/?probe=528ffce1c7) | Feb 15, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [8689383fea](https://linux-hardware.org/?probe=8689383fea) | Feb 15, 2023 |
| HP            | ProBook 4340s               | Notebook    | [caed0e9f2d](https://linux-hardware.org/?probe=caed0e9f2d) | Feb 13, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [09dff429cd](https://linux-hardware.org/?probe=09dff429cd) | Feb 12, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [aef266643c](https://linux-hardware.org/?probe=aef266643c) | Feb 11, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [a4791d2bc4](https://linux-hardware.org/?probe=a4791d2bc4) | Feb 11, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e6c7ea049a](https://linux-hardware.org/?probe=e6c7ea049a) | Feb 10, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [9cbe5cf2b6](https://linux-hardware.org/?probe=9cbe5cf2b6) | Feb 10, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [a6e401a1d3](https://linux-hardware.org/?probe=a6e401a1d3) | Feb 09, 2023 |
| TYAN Compu... | S4985                       | Server      | [40ea5a6601](https://linux-hardware.org/?probe=40ea5a6601) | Feb 08, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [83b847229c](https://linux-hardware.org/?probe=83b847229c) | Feb 08, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [f396fdb21f](https://linux-hardware.org/?probe=f396fdb21f) | Feb 05, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [bac184b151](https://linux-hardware.org/?probe=bac184b151) | Feb 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1S    | Notebook    | [3f3e5b3a1e](https://linux-hardware.org/?probe=3f3e5b3a1e) | Feb 03, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [1cfa73407d](https://linux-hardware.org/?probe=1cfa73407d) | Jan 31, 2023 |
| Acer          | Aspire C24-1650             | All in one  | [221c45eb1b](https://linux-hardware.org/?probe=221c45eb1b) | Jan 29, 2023 |
| MSI           | MS-7513                     | Desktop     | [3953f1b447](https://linux-hardware.org/?probe=3953f1b447) | Jan 28, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d8e161e2b0](https://linux-hardware.org/?probe=d8e161e2b0) | Jan 25, 2023 |
| Gigabyte      | Z490M                       | Desktop     | [a53147a5e7](https://linux-hardware.org/?probe=a53147a5e7) | Jan 25, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [e589b4bd78](https://linux-hardware.org/?probe=e589b4bd78) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [92a3e34781](https://linux-hardware.org/?probe=92a3e34781) | Jan 24, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [7a3b58d6a7](https://linux-hardware.org/?probe=7a3b58d6a7) | Jan 24, 2023 |
| Acer          | Aspire C24-1650             | All in one  | [3731b0f907](https://linux-hardware.org/?probe=3731b0f907) | Jan 22, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [fde7baf9e8](https://linux-hardware.org/?probe=fde7baf9e8) | Jan 19, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [64976ae263](https://linux-hardware.org/?probe=64976ae263) | Jan 19, 2023 |
| HP            | 3397                        | Desktop     | [03c53827b5](https://linux-hardware.org/?probe=03c53827b5) | Jan 17, 2023 |
| PC Special... | Recoil II RTX               | Notebook    | [33850c8810](https://linux-hardware.org/?probe=33850c8810) | Jan 16, 2023 |
| Dell          | Precision 7520              | Notebook    | [c57fdfbe1e](https://linux-hardware.org/?probe=c57fdfbe1e) | Jan 15, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [8d5796c907](https://linux-hardware.org/?probe=8d5796c907) | Jan 15, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b10c786457](https://linux-hardware.org/?probe=b10c786457) | Jan 14, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| Dell          | Latitude E6410              | Notebook    | [a11818f59a](https://linux-hardware.org/?probe=a11818f59a) | Jan 13, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [cfa8ec5fcb](https://linux-hardware.org/?probe=cfa8ec5fcb) | Jan 13, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [22d0c82134](https://linux-hardware.org/?probe=22d0c82134) | Jan 12, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [ef2d9747e2](https://linux-hardware.org/?probe=ef2d9747e2) | Jan 12, 2023 |
| HP            | ProBook 6450b               | Notebook    | [0ae783d261](https://linux-hardware.org/?probe=0ae783d261) | Jan 11, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [5bf59df74c](https://linux-hardware.org/?probe=5bf59df74c) | Jan 10, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [b39213e4d0](https://linux-hardware.org/?probe=b39213e4d0) | Jan 09, 2023 |
| Dell          | 0654JC A01                  | Desktop     | [c3016e1823](https://linux-hardware.org/?probe=c3016e1823) | Jan 09, 2023 |
| Acer          | H57M01                      | Desktop     | [41ee28ae4b](https://linux-hardware.org/?probe=41ee28ae4b) | Jan 09, 2023 |
| MSI           | MS-7513                     | Desktop     | [6e63c2139f](https://linux-hardware.org/?probe=6e63c2139f) | Jan 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [8032d8e1be](https://linux-hardware.org/?probe=8032d8e1be) | Jan 07, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| MSI           | Prestige 14 A10RAS          | Notebook    | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Dell          | Latitude E5500              | Notebook    | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Google        | Voxel                       | Notebook    | [430244f188](https://linux-hardware.org/?probe=430244f188) | Dec 28, 2022 |
| ASUSTek       | K52Je                       | Notebook    | [28cac9b262](https://linux-hardware.org/?probe=28cac9b262) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| Dell          | Latitude 3510               | Notebook    | [ac931934de](https://linux-hardware.org/?probe=ac931934de) | Dec 27, 2022 |
| Dell          | Latitude 3510               | Notebook    | [5db1cf6cb6](https://linux-hardware.org/?probe=5db1cf6cb6) | Dec 27, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [705baed85a](https://linux-hardware.org/?probe=705baed85a) | Dec 26, 2022 |
| ASUSTek       | K52Je                       | Notebook    | [dc13c122ed](https://linux-hardware.org/?probe=dc13c122ed) | Dec 26, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [dde339b7c9](https://linux-hardware.org/?probe=dde339b7c9) | Dec 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [71d7947da6](https://linux-hardware.org/?probe=71d7947da6) | Dec 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [30c3f8d777](https://linux-hardware.org/?probe=30c3f8d777) | Dec 21, 2022 |
| MSI           | G41M4                       | Desktop     | [b651925b13](https://linux-hardware.org/?probe=b651925b13) | Dec 21, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [0d273375d6](https://linux-hardware.org/?probe=0d273375d6) | Dec 18, 2022 |
| MSI           | 790GX-G65                   | Desktop     | [7ad3c8f807](https://linux-hardware.org/?probe=7ad3c8f807) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| HP            | 1905                        | Desktop     | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b5662e5fec](https://linux-hardware.org/?probe=b5662e5fec) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c715acf0ea](https://linux-hardware.org/?probe=c715acf0ea) | Dec 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [18b2579f75](https://linux-hardware.org/?probe=18b2579f75) | Dec 09, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [ceff27eeef](https://linux-hardware.org/?probe=ceff27eeef) | Dec 07, 2022 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [b779cd6c2f](https://linux-hardware.org/?probe=b779cd6c2f) | Dec 06, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d2b43c2803](https://linux-hardware.org/?probe=d2b43c2803) | Dec 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | Notebook    | [fa46f1d34a](https://linux-hardware.org/?probe=fa46f1d34a) | Dec 04, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [cd75a3e13f](https://linux-hardware.org/?probe=cd75a3e13f) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c0f7c4b788](https://linux-hardware.org/?probe=c0f7c4b788) | Dec 03, 2022 |
| Google        | Voxel                       | Notebook    | [b64ebf7db7](https://linux-hardware.org/?probe=b64ebf7db7) | Dec 03, 2022 |
| HP            | 620                         | Notebook    | [6be09298b6](https://linux-hardware.org/?probe=6be09298b6) | Dec 01, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [c8dd66d6de](https://linux-hardware.org/?probe=c8dd66d6de) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [af7d162434](https://linux-hardware.org/?probe=af7d162434) | Nov 28, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [7df334aaa0](https://linux-hardware.org/?probe=7df334aaa0) | Nov 26, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| Shuttle       | FS61                        | Desktop     | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [19663894ff](https://linux-hardware.org/?probe=19663894ff) | Nov 18, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [99a32a02ce](https://linux-hardware.org/?probe=99a32a02ce) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d7992855ba](https://linux-hardware.org/?probe=d7992855ba) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8e17476123](https://linux-hardware.org/?probe=8e17476123) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f48e29fef2](https://linux-hardware.org/?probe=f48e29fef2) | Nov 16, 2022 |
| Acer          | Aspire VN7-791              | Notebook    | [736c2f5664](https://linux-hardware.org/?probe=736c2f5664) | Nov 14, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [4f40815737](https://linux-hardware.org/?probe=4f40815737) | Nov 12, 2022 |
| GPD           | G1619-04                    | Notebook    | [cf4cb47a12](https://linux-hardware.org/?probe=cf4cb47a12) | Nov 09, 2022 |
| MSI           | A78-G41 PC Mate             | Desktop     | [8487f5d19c](https://linux-hardware.org/?probe=8487f5d19c) | Nov 08, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| Acer          | Aspire C24-1650             | All in one  | [3dac8315d4](https://linux-hardware.org/?probe=3dac8315d4) | Nov 04, 2022 |
| Acer          | Aspire C24-1650             | All in one  | [adab8dea39](https://linux-hardware.org/?probe=adab8dea39) | Nov 03, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [a7bc380726](https://linux-hardware.org/?probe=a7bc380726) | Oct 30, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [995f7abb0c](https://linux-hardware.org/?probe=995f7abb0c) | Oct 25, 2022 |
| Acer          | Aspire C24-1650             | All in one  | [82e35bc925](https://linux-hardware.org/?probe=82e35bc925) | Oct 24, 2022 |
| Acer          | Aspire C24-1650             | All in one  | [b110eca1a8](https://linux-hardware.org/?probe=b110eca1a8) | Oct 23, 2022 |
| MSI           | H310M PRO-VD                | Desktop     | [9ce99513bc](https://linux-hardware.org/?probe=9ce99513bc) | Oct 21, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [6b78ca11b4](https://linux-hardware.org/?probe=6b78ca11b4) | Oct 14, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [52658eb393](https://linux-hardware.org/?probe=52658eb393) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [19c7d98b00](https://linux-hardware.org/?probe=19c7d98b00) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a12d335502](https://linux-hardware.org/?probe=a12d335502) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [fd49fda31a](https://linux-hardware.org/?probe=fd49fda31a) | Oct 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [72163c289e](https://linux-hardware.org/?probe=72163c289e) | Oct 05, 2022 |
| ASUSTek       | P5E WS Pro                  | Desktop     | [241e42fa0a](https://linux-hardware.org/?probe=241e42fa0a) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b0cc9bee74](https://linux-hardware.org/?probe=b0cc9bee74) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [45d676584c](https://linux-hardware.org/?probe=45d676584c) | Oct 02, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [996d72bd1e](https://linux-hardware.org/?probe=996d72bd1e) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [8394fca38a](https://linux-hardware.org/?probe=8394fca38a) | Sep 30, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e35b86c3b7](https://linux-hardware.org/?probe=e35b86c3b7) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [f9e71e7e05](https://linux-hardware.org/?probe=f9e71e7e05) | Sep 28, 2022 |
| Dell          | Vostro 5391                 | Notebook    | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [345959e0ed](https://linux-hardware.org/?probe=345959e0ed) | Sep 28, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [3cdcc8b18d](https://linux-hardware.org/?probe=3cdcc8b18d) | Sep 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d166d32749](https://linux-hardware.org/?probe=d166d32749) | Sep 26, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [8e87d041c3](https://linux-hardware.org/?probe=8e87d041c3) | Sep 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [bce9addcca](https://linux-hardware.org/?probe=bce9addcca) | Sep 26, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [98e8df2d3d](https://linux-hardware.org/?probe=98e8df2d3d) | Sep 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [afd66066bc](https://linux-hardware.org/?probe=afd66066bc) | Sep 21, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [50647a7656](https://linux-hardware.org/?probe=50647a7656) | Sep 17, 2022 |
| Lenovo        | G780                        | Notebook    | [04f924450d](https://linux-hardware.org/?probe=04f924450d) | Sep 17, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [9de0254ab0](https://linux-hardware.org/?probe=9de0254ab0) | Sep 13, 2022 |
| ASRock        | Z170 Gaming K6+             | Desktop     | [39027cdb44](https://linux-hardware.org/?probe=39027cdb44) | Sep 13, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [bec58f880f](https://linux-hardware.org/?probe=bec58f880f) | Sep 13, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [182bb36928](https://linux-hardware.org/?probe=182bb36928) | Sep 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [1dc4620833](https://linux-hardware.org/?probe=1dc4620833) | Sep 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ecaa040ba1](https://linux-hardware.org/?probe=ecaa040ba1) | Sep 04, 2022 |
| Dell          | Latitude 3510               | Notebook    | [9477575b26](https://linux-hardware.org/?probe=9477575b26) | Sep 03, 2022 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | Notebook    | [121c8e110b](https://linux-hardware.org/?probe=121c8e110b) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | Notebook    | [6ec2bd9539](https://linux-hardware.org/?probe=6ec2bd9539) | Aug 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [4b56f15871](https://linux-hardware.org/?probe=4b56f15871) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [dd415db306](https://linux-hardware.org/?probe=dd415db306) | Aug 28, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [dff587f11e](https://linux-hardware.org/?probe=dff587f11e) | Aug 28, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [a6d3642195](https://linux-hardware.org/?probe=a6d3642195) | Aug 24, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [8756581baa](https://linux-hardware.org/?probe=8756581baa) | Aug 21, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [f5f3761418](https://linux-hardware.org/?probe=f5f3761418) | Aug 19, 2022 |
| Gigabyte      | P43-ES3G                    | Desktop     | [de6e02672c](https://linux-hardware.org/?probe=de6e02672c) | Aug 18, 2022 |
| Lenovo        | 3098 0B98401 WIN            | Desktop     | [769802c689](https://linux-hardware.org/?probe=769802c689) | Aug 15, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| Gigabyte      | P43-ES3G                    | Desktop     | [2b0691bddd](https://linux-hardware.org/?probe=2b0691bddd) | Aug 15, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [af03bf80b5](https://linux-hardware.org/?probe=af03bf80b5) | Aug 10, 2022 |
| Packard Be... | P5N-E SLI                   | Desktop     | [6f2bf70c0b](https://linux-hardware.org/?probe=6f2bf70c0b) | Aug 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9a06c0c10c](https://linux-hardware.org/?probe=9a06c0c10c) | Aug 09, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [93bd067b5d](https://linux-hardware.org/?probe=93bd067b5d) | Aug 09, 2022 |
| Packard Be... | P5N-E SLI                   | Desktop     | [cdc88569bc](https://linux-hardware.org/?probe=cdc88569bc) | Aug 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [7e5a0c0004](https://linux-hardware.org/?probe=7e5a0c0004) | Aug 06, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [98ff02ebde](https://linux-hardware.org/?probe=98ff02ebde) | Aug 05, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [0ac4f27d0f](https://linux-hardware.org/?probe=0ac4f27d0f) | Jul 31, 2022 |
| Acer          | Aspire VN7-791G             | Notebook    | [3e72040097](https://linux-hardware.org/?probe=3e72040097) | Jul 31, 2022 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [5d4a26735e](https://linux-hardware.org/?probe=5d4a26735e) | Jul 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [b4a9542143](https://linux-hardware.org/?probe=b4a9542143) | Jul 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [4a3b630b27](https://linux-hardware.org/?probe=4a3b630b27) | Jul 26, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [793c5e80d4](https://linux-hardware.org/?probe=793c5e80d4) | Jul 26, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [ac78b76a30](https://linux-hardware.org/?probe=ac78b76a30) | Jul 25, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [210b75c48e](https://linux-hardware.org/?probe=210b75c48e) | Jul 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [17befc2dd5](https://linux-hardware.org/?probe=17befc2dd5) | Jul 20, 2022 |
| HP            | ProBook 440 G3              | Notebook    | [04b2ed9273](https://linux-hardware.org/?probe=04b2ed9273) | Jul 19, 2022 |
| UMAX          | VisionBook-N12R             | Notebook    | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
| HP            | ProBook 440 G3              | Notebook    | [c546e3b537](https://linux-hardware.org/?probe=c546e3b537) | Jul 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [11ddd8feab](https://linux-hardware.org/?probe=11ddd8feab) | Jul 11, 2022 |
| Acer          | Aspire C22-865              | All in one  | [2e0a195007](https://linux-hardware.org/?probe=2e0a195007) | Jul 09, 2022 |
| HP            | 8455                        | Desktop     | [9954a77308](https://linux-hardware.org/?probe=9954a77308) | Jul 07, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [779bc20f77](https://linux-hardware.org/?probe=779bc20f77) | Jul 05, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [bc0c9431e1](https://linux-hardware.org/?probe=bc0c9431e1) | Jul 04, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [539ce50149](https://linux-hardware.org/?probe=539ce50149) | Jul 04, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| MSI           | EX705                       | Notebook    | [d85dfacff5](https://linux-hardware.org/?probe=d85dfacff5) | Jun 30, 2022 |
| MSI           | EX705                       | Notebook    | [3de108279f](https://linux-hardware.org/?probe=3de108279f) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5ebcb2f152](https://linux-hardware.org/?probe=5ebcb2f152) | Jun 29, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [2e4663e8c3](https://linux-hardware.org/?probe=2e4663e8c3) | Jun 22, 2022 |
| HP            | Pavilion dv6                | Notebook    | [1ba5e6c491](https://linux-hardware.org/?probe=1ba5e6c491) | Jun 18, 2022 |
| Dell          | Latitude 3510               | Notebook    | [4b6e3aeb9e](https://linux-hardware.org/?probe=4b6e3aeb9e) | Jun 16, 2022 |
| Dell          | Latitude E5570              | Notebook    | [ce4d3bb373](https://linux-hardware.org/?probe=ce4d3bb373) | Jun 09, 2022 |
| Shuttle       | FH61V                       | Desktop     | [465dc41fdb](https://linux-hardware.org/?probe=465dc41fdb) | Jun 08, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [fdda1deb12](https://linux-hardware.org/?probe=fdda1deb12) | Jun 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Dell          | Latitude E6440              | Notebook    | [dd05b883a6](https://linux-hardware.org/?probe=dd05b883a6) | Jun 04, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [ae8649e10b](https://linux-hardware.org/?probe=ae8649e10b) | May 28, 2022 |
| MSI           | GT60 2OC/2OD                | Notebook    | [c3b5eb704d](https://linux-hardware.org/?probe=c3b5eb704d) | May 22, 2022 |
| MSI           | GT60 2OC/2OD                | Notebook    | [96f6fda5d5](https://linux-hardware.org/?probe=96f6fda5d5) | May 22, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [8baf319c52](https://linux-hardware.org/?probe=8baf319c52) | May 21, 2022 |
| Intel         | DG41KR AAE62839-304         | Desktop     | [d6fa39e82f](https://linux-hardware.org/?probe=d6fa39e82f) | May 16, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [215ded6566](https://linux-hardware.org/?probe=215ded6566) | May 16, 2022 |
| Acer          | H57M01                      | Desktop     | [9116ecebcb](https://linux-hardware.org/?probe=9116ecebcb) | May 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [0793a5608a](https://linux-hardware.org/?probe=0793a5608a) | May 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [52c0b4a6e0](https://linux-hardware.org/?probe=52c0b4a6e0) | May 14, 2022 |
| Acer          | H57M01                      | Desktop     | [42100344af](https://linux-hardware.org/?probe=42100344af) | May 14, 2022 |
| Gigabyte      | H55M-S2H                    | Desktop     | [0b3c6ab0f7](https://linux-hardware.org/?probe=0b3c6ab0f7) | May 14, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [d8361f7895](https://linux-hardware.org/?probe=d8361f7895) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3ba9de57d1](https://linux-hardware.org/?probe=3ba9de57d1) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [96be9cb5e7](https://linux-hardware.org/?probe=96be9cb5e7) | May 12, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [71e7f1c760](https://linux-hardware.org/?probe=71e7f1c760) | May 09, 2022 |
| MSI           | GT60 2OC/2OD                | Notebook    | [21f08dbab6](https://linux-hardware.org/?probe=21f08dbab6) | May 06, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [85901f28cb](https://linux-hardware.org/?probe=85901f28cb) | May 05, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [92f92ef4ee](https://linux-hardware.org/?probe=92f92ef4ee) | Apr 28, 2022 |
| Acer          | Extensa 5635G               | Notebook    | [6e69a86d63](https://linux-hardware.org/?probe=6e69a86d63) | Apr 28, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [fff58f97e8](https://linux-hardware.org/?probe=fff58f97e8) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| HP            | ProBook 4540s               | Notebook    | [17272efb83](https://linux-hardware.org/?probe=17272efb83) | Apr 22, 2022 |
| Unknown       | RS780-SB700                 | Desktop     | [eb3aa5fa60](https://linux-hardware.org/?probe=eb3aa5fa60) | Apr 20, 2022 |
| Dell          | G3 3579                     | Notebook    | [a85e01d9d0](https://linux-hardware.org/?probe=a85e01d9d0) | Apr 20, 2022 |
| Dell          | Latitude E6520              | Notebook    | [33502900d8](https://linux-hardware.org/?probe=33502900d8) | Apr 19, 2022 |
| Gigabyte      | Z490M                       | Desktop     | [2138ce9310](https://linux-hardware.org/?probe=2138ce9310) | Apr 18, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [64a66e1b61](https://linux-hardware.org/?probe=64a66e1b61) | Apr 12, 2022 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [54de39efb5](https://linux-hardware.org/?probe=54de39efb5) | Apr 12, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [e6aa0c6166](https://linux-hardware.org/?probe=e6aa0c6166) | Apr 09, 2022 |
| Acer          | Revo RL80                   | Desktop     | [414f1870b3](https://linux-hardware.org/?probe=414f1870b3) | Apr 04, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [a10a00d2f1](https://linux-hardware.org/?probe=a10a00d2f1) | Apr 03, 2022 |
| HP            | 15                          | Notebook    | [443dd5b9e8](https://linux-hardware.org/?probe=443dd5b9e8) | Apr 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ba7b7abd34](https://linux-hardware.org/?probe=ba7b7abd34) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| Fujitsu Si... | AMILO Pi 3525               | Notebook    | [b77907b9b6](https://linux-hardware.org/?probe=b77907b9b6) | Mar 31, 2022 |
| AMI           | Intel                       | Convertible | [b349c1e550](https://linux-hardware.org/?probe=b349c1e550) | Mar 29, 2022 |
| HP            | 18E5                        | Desktop     | [39cb47db55](https://linux-hardware.org/?probe=39cb47db55) | Mar 28, 2022 |
| HP            | ProBook 4340s               | Notebook    | [787443949a](https://linux-hardware.org/?probe=787443949a) | Mar 27, 2022 |
| HP            | 18E5                        | Desktop     | [061d716ce1](https://linux-hardware.org/?probe=061d716ce1) | Mar 27, 2022 |
| Intel         | S3210SH FRU Ver             | Server      | [d608f51576](https://linux-hardware.org/?probe=d608f51576) | Mar 23, 2022 |
| Shuttle       | FH61V                       | Desktop     | [9b18d7b2ed](https://linux-hardware.org/?probe=9b18d7b2ed) | Mar 23, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | Notebook    | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| HP            | EliteBook 8740w             | Notebook    | [3ae23e0d6b](https://linux-hardware.org/?probe=3ae23e0d6b) | Mar 22, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [02326ae250](https://linux-hardware.org/?probe=02326ae250) | Mar 22, 2022 |
| ASUSTek       | X555LNB                     | Notebook    | [ae49172b0f](https://linux-hardware.org/?probe=ae49172b0f) | Mar 21, 2022 |
| ASUSTek       | X555LNB                     | Notebook    | [33e081f100](https://linux-hardware.org/?probe=33e081f100) | Mar 21, 2022 |
| VIA Techno... | KM266-8235                  | Desktop     | [ad3f9e9e12](https://linux-hardware.org/?probe=ad3f9e9e12) | Mar 20, 2022 |
| Dell          | Latitude 3510               | Notebook    | [f24ba2791e](https://linux-hardware.org/?probe=f24ba2791e) | Mar 19, 2022 |
| ASUSTek       | N53SN                       | Notebook    | [f335baa4a4](https://linux-hardware.org/?probe=f335baa4a4) | Mar 18, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [9918c132f0](https://linux-hardware.org/?probe=9918c132f0) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [fd9ec44205](https://linux-hardware.org/?probe=fd9ec44205) | Mar 13, 2022 |
| HP            | ProBook 4340s               | Notebook    | [01af2dee98](https://linux-hardware.org/?probe=01af2dee98) | Mar 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [76e54baafe](https://linux-hardware.org/?probe=76e54baafe) | Mar 09, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [e508dbbb0f](https://linux-hardware.org/?probe=e508dbbb0f) | Mar 05, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| HP            | 339A                        | Desktop     | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| HP            | 339A                        | Desktop     | [118fee2993](https://linux-hardware.org/?probe=118fee2993) | Feb 26, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [d24a3aebe9](https://linux-hardware.org/?probe=d24a3aebe9) | Feb 23, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [7707d7dc14](https://linux-hardware.org/?probe=7707d7dc14) | Feb 23, 2022 |
| Sony          | VPCEH3S6E                   | Notebook    | [334451b6e7](https://linux-hardware.org/?probe=334451b6e7) | Feb 23, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [e667cfc4cf](https://linux-hardware.org/?probe=e667cfc4cf) | Feb 20, 2022 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [2e2c2de75c](https://linux-hardware.org/?probe=2e2c2de75c) | Feb 20, 2022 |
| Gigabyte      | H55M-S2H                    | Desktop     | [3031d8a880](https://linux-hardware.org/?probe=3031d8a880) | Feb 20, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | Desktop     | [2734c5a939](https://linux-hardware.org/?probe=2734c5a939) | Feb 19, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [c6e3cad977](https://linux-hardware.org/?probe=c6e3cad977) | Feb 19, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | Desktop     | [7baecb9fce](https://linux-hardware.org/?probe=7baecb9fce) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6cbb067e83](https://linux-hardware.org/?probe=6cbb067e83) | Feb 19, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [781ef18260](https://linux-hardware.org/?probe=781ef18260) | Feb 18, 2022 |
| HP            | 339A                        | Desktop     | [d35aeac271](https://linux-hardware.org/?probe=d35aeac271) | Feb 16, 2022 |
| HP            | 339A                        | Desktop     | [aac8acdafe](https://linux-hardware.org/?probe=aac8acdafe) | Feb 16, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [c9b5c461da](https://linux-hardware.org/?probe=c9b5c461da) | Feb 15, 2022 |
| Gigabyte      | Z77-HD3                     | Desktop     | [c72849033f](https://linux-hardware.org/?probe=c72849033f) | Feb 15, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [5306cc74cf](https://linux-hardware.org/?probe=5306cc74cf) | Feb 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [b4d07e8ab1](https://linux-hardware.org/?probe=b4d07e8ab1) | Feb 15, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [bfeed2f132](https://linux-hardware.org/?probe=bfeed2f132) | Feb 14, 2022 |
| Lenovo        | 36ED SDK0J40700 WIN 3258... | All in one  | [b5d4b3357a](https://linux-hardware.org/?probe=b5d4b3357a) | Feb 13, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [b6851e2e2d](https://linux-hardware.org/?probe=b6851e2e2d) | Feb 13, 2022 |
| ASUSTek       | P6T                         | Desktop     | [5084dfc411](https://linux-hardware.org/?probe=5084dfc411) | Feb 12, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [4a136af33b](https://linux-hardware.org/?probe=4a136af33b) | Feb 12, 2022 |
| Dell          | Latitude E6500              | Notebook    | [4b35cc763b](https://linux-hardware.org/?probe=4b35cc763b) | Feb 11, 2022 |
| Dell          | Latitude E6500              | Notebook    | [097664c430](https://linux-hardware.org/?probe=097664c430) | Feb 11, 2022 |
| ASUSTek       | P6T                         | Desktop     | [10a6e04458](https://linux-hardware.org/?probe=10a6e04458) | Feb 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [383572d5be](https://linux-hardware.org/?probe=383572d5be) | Feb 08, 2022 |
| Toshiba       | Satellite C855-1TT          | Notebook    | [87eacffdb8](https://linux-hardware.org/?probe=87eacffdb8) | Feb 07, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | Desktop     | [843210cfb0](https://linux-hardware.org/?probe=843210cfb0) | Feb 06, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [2b3c148135](https://linux-hardware.org/?probe=2b3c148135) | Feb 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ed2a250420](https://linux-hardware.org/?probe=ed2a250420) | Feb 04, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [ff4d3f33c9](https://linux-hardware.org/?probe=ff4d3f33c9) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d598fc04e1](https://linux-hardware.org/?probe=d598fc04e1) | Feb 04, 2022 |
| Lenovo        | 3176 NOK                    | Desktop     | [d3a3d5276b](https://linux-hardware.org/?probe=d3a3d5276b) | Feb 02, 2022 |
| MSI           | VR201                       | Notebook    | [5d514ac721](https://linux-hardware.org/?probe=5d514ac721) | Feb 01, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [5b4a8e5bc4](https://linux-hardware.org/?probe=5b4a8e5bc4) | Jan 29, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [39511f4010](https://linux-hardware.org/?probe=39511f4010) | Jan 29, 2022 |
| ASUSTek       | K50C                        | Notebook    | [a285a1e873](https://linux-hardware.org/?probe=a285a1e873) | Jan 27, 2022 |
| Dell          | Latitude E5570              | Notebook    | [7b6a4470d6](https://linux-hardware.org/?probe=7b6a4470d6) | Jan 27, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [11f5908f13](https://linux-hardware.org/?probe=11f5908f13) | Jan 26, 2022 |
| Lenovo        | ThinkPad 20TDZMS            | Notebook    | [143bc3f79b](https://linux-hardware.org/?probe=143bc3f79b) | Jan 23, 2022 |
| MSI           | MS-163B Ver                 | Notebook    | [2e2d0c47bd](https://linux-hardware.org/?probe=2e2d0c47bd) | Jan 23, 2022 |
| Shuttle       | FH61V                       | Desktop     | [6d6980d0bb](https://linux-hardware.org/?probe=6d6980d0bb) | Jan 18, 2022 |
| Dell          | Latitude 3510               | Notebook    | [47793faf9f](https://linux-hardware.org/?probe=47793faf9f) | Jan 18, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| MSI           | EX705                       | Notebook    | [bf23179311](https://linux-hardware.org/?probe=bf23179311) | Jan 17, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [0a01195a57](https://linux-hardware.org/?probe=0a01195a57) | Jan 16, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [a1f88f8fc7](https://linux-hardware.org/?probe=a1f88f8fc7) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop-c... | Notebook    | [bc679e8ef6](https://linux-hardware.org/?probe=bc679e8ef6) | Jan 14, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [3260495670](https://linux-hardware.org/?probe=3260495670) | Jan 13, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [2126180fa9](https://linux-hardware.org/?probe=2126180fa9) | Jan 06, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [ecaadc9cb3](https://linux-hardware.org/?probe=ecaadc9cb3) | Jan 04, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [bd181b10da](https://linux-hardware.org/?probe=bd181b10da) | Jan 04, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [e91280cb30](https://linux-hardware.org/?probe=e91280cb30) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [b5709d8fd1](https://linux-hardware.org/?probe=b5709d8fd1) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [b79036063e](https://linux-hardware.org/?probe=b79036063e) | Dec 31, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [56a6e6c9eb](https://linux-hardware.org/?probe=56a6e6c9eb) | Dec 29, 2021 |
| ASUSTek       | G751JY                      | Notebook    | [e7a5fad002](https://linux-hardware.org/?probe=e7a5fad002) | Dec 29, 2021 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [3edd9950f9](https://linux-hardware.org/?probe=3edd9950f9) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3867022c38](https://linux-hardware.org/?probe=3867022c38) | Dec 25, 2021 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [a4a8130a06](https://linux-hardware.org/?probe=a4a8130a06) | Dec 24, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [a2a0923008](https://linux-hardware.org/?probe=a2a0923008) | Dec 20, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [0cba25aac5](https://linux-hardware.org/?probe=0cba25aac5) | Dec 20, 2021 |
| Lenovo        | G505 20240                  | Notebook    | [e29df1e2a0](https://linux-hardware.org/?probe=e29df1e2a0) | Dec 19, 2021 |
| ASUSTek       | X555BP                      | Notebook    | [770e3752e6](https://linux-hardware.org/?probe=770e3752e6) | Dec 18, 2021 |
| Gigabyte      | Z77-HD3                     | Desktop     | [a9eceeac28](https://linux-hardware.org/?probe=a9eceeac28) | Dec 14, 2021 |
| Shuttle       | FH61V                       | Desktop     | [b4c8a91d0f](https://linux-hardware.org/?probe=b4c8a91d0f) | Dec 13, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [f17f39439e](https://linux-hardware.org/?probe=f17f39439e) | Dec 13, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [182ef61d4c](https://linux-hardware.org/?probe=182ef61d4c) | Dec 13, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5d4005ae4c](https://linux-hardware.org/?probe=5d4005ae4c) | Dec 13, 2021 |
| Gigabyte      | Z77-HD3                     | Desktop     | [75755e4033](https://linux-hardware.org/?probe=75755e4033) | Dec 12, 2021 |
| Gigabyte      | Z77-HD3                     | Desktop     | [7d3626d44d](https://linux-hardware.org/?probe=7d3626d44d) | Dec 12, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [be9daabc79](https://linux-hardware.org/?probe=be9daabc79) | Dec 10, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [eb723f5cb0](https://linux-hardware.org/?probe=eb723f5cb0) | Dec 09, 2021 |
| Dell          | Latitude 3510               | Notebook    | [e2834c5ef6](https://linux-hardware.org/?probe=e2834c5ef6) | Dec 08, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [67393b8c68](https://linux-hardware.org/?probe=67393b8c68) | Dec 03, 2021 |
| Dell          | Latitude 5401               | Notebook    | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| Gigabyte      | H410M S2H                   | Desktop     | [8b917483ef](https://linux-hardware.org/?probe=8b917483ef) | Nov 30, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [ad0c0d07cf](https://linux-hardware.org/?probe=ad0c0d07cf) | Nov 28, 2021 |
| Dell          | Latitude D630               | Notebook    | [6044bc3e07](https://linux-hardware.org/?probe=6044bc3e07) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [77a39f82ff](https://linux-hardware.org/?probe=77a39f82ff) | Nov 28, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [795a9ffd0f](https://linux-hardware.org/?probe=795a9ffd0f) | Nov 27, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [e23dea02cf](https://linux-hardware.org/?probe=e23dea02cf) | Nov 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e1827cbbc6](https://linux-hardware.org/?probe=e1827cbbc6) | Nov 24, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b718c829fa](https://linux-hardware.org/?probe=b718c829fa) | Nov 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| Dell          | Latitude 5590               | Notebook    | [d8b69c36bd](https://linux-hardware.org/?probe=d8b69c36bd) | Nov 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6189028e3d](https://linux-hardware.org/?probe=6189028e3d) | Nov 23, 2021 |
| Dell          | Latitude 7389               | Convertible | [4364726d94](https://linux-hardware.org/?probe=4364726d94) | Nov 21, 2021 |
| Toshiba       | Satellite Pro C850-1D5      | Notebook    | [22ed560714](https://linux-hardware.org/?probe=22ed560714) | Nov 21, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [cc38af1147](https://linux-hardware.org/?probe=cc38af1147) | Nov 20, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [55384cc552](https://linux-hardware.org/?probe=55384cc552) | Nov 18, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [bf7d34f5c1](https://linux-hardware.org/?probe=bf7d34f5c1) | Nov 15, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [d1e04ead11](https://linux-hardware.org/?probe=d1e04ead11) | Nov 15, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [4c1c718d65](https://linux-hardware.org/?probe=4c1c718d65) | Nov 14, 2021 |
| Acer          | EM61SM/EM61PM               | Desktop     | [6a42469739](https://linux-hardware.org/?probe=6a42469739) | Nov 13, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1386180677](https://linux-hardware.org/?probe=1386180677) | Nov 12, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [92517a0772](https://linux-hardware.org/?probe=92517a0772) | Nov 12, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eb16aedbc3](https://linux-hardware.org/?probe=eb16aedbc3) | Nov 11, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [82d6b16382](https://linux-hardware.org/?probe=82d6b16382) | Nov 08, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [70e2057cff](https://linux-hardware.org/?probe=70e2057cff) | Nov 07, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [fada2e4c02](https://linux-hardware.org/?probe=fada2e4c02) | Nov 06, 2021 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [d6285c81a2](https://linux-hardware.org/?probe=d6285c81a2) | Nov 05, 2021 |
| Toshiba       | Satellite U400              | Notebook    | [7b2364e53a](https://linux-hardware.org/?probe=7b2364e53a) | Nov 04, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [ef8b1adb4b](https://linux-hardware.org/?probe=ef8b1adb4b) | Nov 03, 2021 |
| Raspberry ... | Raspberry Pi Zero 2 Rev ... | Soc         | [992b4af8d4](https://linux-hardware.org/?probe=992b4af8d4) | Nov 03, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d4ee4ba59f](https://linux-hardware.org/?probe=d4ee4ba59f) | Nov 01, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [17d03d73f7](https://linux-hardware.org/?probe=17d03d73f7) | Oct 30, 2021 |
| HP            | Presario CQ57               | Notebook    | [8e3ceb5db9](https://linux-hardware.org/?probe=8e3ceb5db9) | Oct 23, 2021 |
| HP            | Presario CQ57               | Notebook    | [78828b2790](https://linux-hardware.org/?probe=78828b2790) | Oct 21, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [c74421666a](https://linux-hardware.org/?probe=c74421666a) | Oct 20, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [644553839a](https://linux-hardware.org/?probe=644553839a) | Oct 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [cdc6d847a7](https://linux-hardware.org/?probe=cdc6d847a7) | Oct 18, 2021 |
| ASUSTek       | K50C                        | Notebook    | [02e59a3759](https://linux-hardware.org/?probe=02e59a3759) | Oct 16, 2021 |
| ASUSTek       | K50C                        | Notebook    | [c47941a383](https://linux-hardware.org/?probe=c47941a383) | Oct 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bdf9cbc98c](https://linux-hardware.org/?probe=bdf9cbc98c) | Oct 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [dbfa388218](https://linux-hardware.org/?probe=dbfa388218) | Oct 10, 2021 |
| HP            | 15                          | Notebook    | [6974f988e3](https://linux-hardware.org/?probe=6974f988e3) | Oct 06, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [d0b704d0ff](https://linux-hardware.org/?probe=d0b704d0ff) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | Notebook    | [e54daea8f9](https://linux-hardware.org/?probe=e54daea8f9) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | Notebook    | [ed56dc2a85](https://linux-hardware.org/?probe=ed56dc2a85) | Oct 06, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [ef8dfe0673](https://linux-hardware.org/?probe=ef8dfe0673) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [0540c800c7](https://linux-hardware.org/?probe=0540c800c7) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a508d7f60d](https://linux-hardware.org/?probe=a508d7f60d) | Oct 02, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [1fce457ac6](https://linux-hardware.org/?probe=1fce457ac6) | Oct 01, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [1e0f7c12ef](https://linux-hardware.org/?probe=1e0f7c12ef) | Oct 01, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [7efbe48343](https://linux-hardware.org/?probe=7efbe48343) | Oct 01, 2021 |
| Dell          | Latitude E6440              | Notebook    | [14a1218871](https://linux-hardware.org/?probe=14a1218871) | Sep 26, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [fd875fbe8c](https://linux-hardware.org/?probe=fd875fbe8c) | Sep 24, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [57894a62f6](https://linux-hardware.org/?probe=57894a62f6) | Sep 21, 2021 |
| Lenovo        | G580                        | Notebook    | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [6924705831](https://linux-hardware.org/?probe=6924705831) | Sep 20, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [835f183d57](https://linux-hardware.org/?probe=835f183d57) | Sep 17, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b2f55e8760](https://linux-hardware.org/?probe=b2f55e8760) | Sep 16, 2021 |
| Lenovo        | ThinkPad T450 20BV003SMS    | Notebook    | [352b2b53b8](https://linux-hardware.org/?probe=352b2b53b8) | Sep 14, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [6207dd28b2](https://linux-hardware.org/?probe=6207dd28b2) | Sep 09, 2021 |
| UMAX          | VisionBook 11Wi-64G         | Tablet      | [6dcd6a1bf7](https://linux-hardware.org/?probe=6dcd6a1bf7) | Sep 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bef580a58c](https://linux-hardware.org/?probe=bef580a58c) | Sep 04, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e0b66566ad](https://linux-hardware.org/?probe=e0b66566ad) | Sep 04, 2021 |
| Dell          | Latitude 3510               | Notebook    | [797c9c49c9](https://linux-hardware.org/?probe=797c9c49c9) | Sep 02, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [48ef40abbf](https://linux-hardware.org/?probe=48ef40abbf) | Sep 02, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [05d2b6e067](https://linux-hardware.org/?probe=05d2b6e067) | Sep 01, 2021 |
| Dell          | Latitude E5570              | Notebook    | [7e6202db9d](https://linux-hardware.org/?probe=7e6202db9d) | Aug 31, 2021 |
| Dell          | Latitude E5570              | Notebook    | [95667a8c8f](https://linux-hardware.org/?probe=95667a8c8f) | Aug 31, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [268813fbf4](https://linux-hardware.org/?probe=268813fbf4) | Aug 28, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [fa6adf65a6](https://linux-hardware.org/?probe=fa6adf65a6) | Aug 23, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [71e3489cd9](https://linux-hardware.org/?probe=71e3489cd9) | Aug 18, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9bf7d4afd7](https://linux-hardware.org/?probe=9bf7d4afd7) | Aug 14, 2021 |
| ASUSTek       | X51R                        | Notebook    | [1d1aad3900](https://linux-hardware.org/?probe=1d1aad3900) | Aug 08, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [d827460e02](https://linux-hardware.org/?probe=d827460e02) | Aug 04, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [dc8f396ad8](https://linux-hardware.org/?probe=dc8f396ad8) | Aug 02, 2021 |
| Teclast       | F15S                        | Notebook    | [49f33bd674](https://linux-hardware.org/?probe=49f33bd674) | Jul 28, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [30b94a4a43](https://linux-hardware.org/?probe=30b94a4a43) | Jul 27, 2021 |
| ASUSTek       | N551JM                      | Notebook    | [4334fcb285](https://linux-hardware.org/?probe=4334fcb285) | Jul 27, 2021 |
| Dell          | Latitude E5470              | Notebook    | [f26e3c7b39](https://linux-hardware.org/?probe=f26e3c7b39) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [925ddff018](https://linux-hardware.org/?probe=925ddff018) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [756bb76029](https://linux-hardware.org/?probe=756bb76029) | Jul 25, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [f548a06642](https://linux-hardware.org/?probe=f548a06642) | Jul 23, 2021 |
| Timi          | TM1701                      | Notebook    | [2d44d6cccb](https://linux-hardware.org/?probe=2d44d6cccb) | Jul 23, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [04bf0287f0](https://linux-hardware.org/?probe=04bf0287f0) | Jul 21, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| HP            | Presario CQ57               | Notebook    | [3726c1e8c4](https://linux-hardware.org/?probe=3726c1e8c4) | Jul 15, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [4ffd108654](https://linux-hardware.org/?probe=4ffd108654) | Jul 15, 2021 |
| Lenovo        | ThinkPad L560 20F10029MC    | Notebook    | [a96e4cc1a5](https://linux-hardware.org/?probe=a96e4cc1a5) | Jul 12, 2021 |
| Intel         | S3000AHLX D40858-208        | Desktop     | [2acfd9617b](https://linux-hardware.org/?probe=2acfd9617b) | Jul 10, 2021 |
| HP            | 843C                        | Desktop     | [01dc34eeb4](https://linux-hardware.org/?probe=01dc34eeb4) | Jul 07, 2021 |
| HP            | 0A54h                       | Desktop     | [10aa52cef5](https://linux-hardware.org/?probe=10aa52cef5) | Jul 06, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [9d12a5bba7](https://linux-hardware.org/?probe=9d12a5bba7) | Jul 05, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e649a4f85c](https://linux-hardware.org/?probe=e649a4f85c) | Jun 30, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [83b2318c6a](https://linux-hardware.org/?probe=83b2318c6a) | Jun 26, 2021 |
| Foxconn       | 945 7AD Series              | Desktop     | [9a763d1e1e](https://linux-hardware.org/?probe=9a763d1e1e) | Jun 25, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [856b9bc825](https://linux-hardware.org/?probe=856b9bc825) | Jun 24, 2021 |
| Intel         | X99                         | Desktop     | [436dda258b](https://linux-hardware.org/?probe=436dda258b) | Jun 21, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [8ed58d00f1](https://linux-hardware.org/?probe=8ed58d00f1) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8d86cdfbad](https://linux-hardware.org/?probe=8d86cdfbad) | Jun 19, 2021 |
| Lenovo        | ThinkPad L540 20AUS0DW00    | Notebook    | [a3e83938c3](https://linux-hardware.org/?probe=a3e83938c3) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [44b174fec2](https://linux-hardware.org/?probe=44b174fec2) | Jun 18, 2021 |
| Unknown       | Unknown                     | Notebook    | [001462994e](https://linux-hardware.org/?probe=001462994e) | Jun 18, 2021 |
| Unknown       | Unknown                     | Notebook    | [049e5221b4](https://linux-hardware.org/?probe=049e5221b4) | Jun 18, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [56342fd485](https://linux-hardware.org/?probe=56342fd485) | Jun 17, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | Desktop     | [0cfd20f720](https://linux-hardware.org/?probe=0cfd20f720) | Jun 16, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | Desktop     | [e33a8c0c69](https://linux-hardware.org/?probe=e33a8c0c69) | Jun 16, 2021 |
| Dell          | Precision 7530              | Notebook    | [3e5d3c4292](https://linux-hardware.org/?probe=3e5d3c4292) | Jun 15, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a390d934b1](https://linux-hardware.org/?probe=a390d934b1) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [9048edb5d2](https://linux-hardware.org/?probe=9048edb5d2) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [93557b8c32](https://linux-hardware.org/?probe=93557b8c32) | Jun 13, 2021 |
| Intel         | S3000AHLX D40858-208        | Desktop     | [ab61e363eb](https://linux-hardware.org/?probe=ab61e363eb) | Jun 12, 2021 |
| HP            | 3397                        | Desktop     | [e171bcda3f](https://linux-hardware.org/?probe=e171bcda3f) | Jun 11, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [74201da57b](https://linux-hardware.org/?probe=74201da57b) | Jun 11, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [b90e553e8e](https://linux-hardware.org/?probe=b90e553e8e) | Jun 11, 2021 |
| HP            | ProLiant ML350 G5           | Desktop     | [297ef6b999](https://linux-hardware.org/?probe=297ef6b999) | Jun 06, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [7c519c91ca](https://linux-hardware.org/?probe=7c519c91ca) | Jun 02, 2021 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [7950140465](https://linux-hardware.org/?probe=7950140465) | Jun 02, 2021 |
| ASUSTek       | K54C                        | Notebook    | [dcdfadb154](https://linux-hardware.org/?probe=dcdfadb154) | May 31, 2021 |
| ASUSTek       | K54C                        | Notebook    | [252cf3ef89](https://linux-hardware.org/?probe=252cf3ef89) | May 31, 2021 |
| ASUSTek       | PRIME A320M-K 2020-03-20    | Desktop     | [500976e7d1](https://linux-hardware.org/?probe=500976e7d1) | May 30, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [07b30926e1](https://linux-hardware.org/?probe=07b30926e1) | May 29, 2021 |
| Lenovo        | 0.1                         | Desktop     | [77d8358e26](https://linux-hardware.org/?probe=77d8358e26) | May 28, 2021 |
| ASUSTek       | F3M                         | Notebook    | [05d9306fcc](https://linux-hardware.org/?probe=05d9306fcc) | May 28, 2021 |
| Lenovo        | 0.1                         | Desktop     | [d0fbef90ca](https://linux-hardware.org/?probe=d0fbef90ca) | May 27, 2021 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0b27475327](https://linux-hardware.org/?probe=0b27475327) | May 26, 2021 |
| eMachines     | E725                        | Notebook    | [f573488bda](https://linux-hardware.org/?probe=f573488bda) | May 25, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [794531a511](https://linux-hardware.org/?probe=794531a511) | May 25, 2021 |
| Lenovo        | Tiger Hill                  | Desktop     | [3f61f1be35](https://linux-hardware.org/?probe=3f61f1be35) | May 25, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [95b045c1a1](https://linux-hardware.org/?probe=95b045c1a1) | May 25, 2021 |
| ZOTAC         | ZBOXNANO-AQ02               | Mini pc     | [eb76ff1c3f](https://linux-hardware.org/?probe=eb76ff1c3f) | May 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [26f506ff94](https://linux-hardware.org/?probe=26f506ff94) | May 23, 2021 |
| HP            | Unknown                     | Notebook    | [3584a13ae5](https://linux-hardware.org/?probe=3584a13ae5) | May 22, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [535d153c75](https://linux-hardware.org/?probe=535d153c75) | May 21, 2021 |
| HP            | 3047h                       | Desktop     | [4fce80ed03](https://linux-hardware.org/?probe=4fce80ed03) | May 20, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | Notebook    | [01af2920f0](https://linux-hardware.org/?probe=01af2920f0) | May 19, 2021 |
| MSI           | A75A-G55                    | Desktop     | [f9773bff22](https://linux-hardware.org/?probe=f9773bff22) | May 17, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [c8ac6c4b93](https://linux-hardware.org/?probe=c8ac6c4b93) | May 16, 2021 |
| Acer          | Aspire C22-865              | All in one  | [0ef1f4f50d](https://linux-hardware.org/?probe=0ef1f4f50d) | May 16, 2021 |
| Intel         | DH87RL AAG74240-402         | Desktop     | [cdb24d5d69](https://linux-hardware.org/?probe=cdb24d5d69) | May 16, 2021 |
| Acer          | Aspire C22-865              | All in one  | [fdc38a2185](https://linux-hardware.org/?probe=fdc38a2185) | May 16, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [80ca4b15a5](https://linux-hardware.org/?probe=80ca4b15a5) | May 16, 2021 |
| Lenovo        | ThinkPad T490 20N20048GE    | Notebook    | [7c9dbf982e](https://linux-hardware.org/?probe=7c9dbf982e) | May 14, 2021 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [e311ba55e3](https://linux-hardware.org/?probe=e311ba55e3) | May 13, 2021 |
| Toshiba       | Satellite L735              | Notebook    | [177d534fdc](https://linux-hardware.org/?probe=177d534fdc) | May 11, 2021 |
| HP            | 843C                        | Desktop     | [e69ec57276](https://linux-hardware.org/?probe=e69ec57276) | May 10, 2021 |
| HP            | Pavilion dv6                | Notebook    | [63656472a4](https://linux-hardware.org/?probe=63656472a4) | May 10, 2021 |
| Toshiba       | Satellite L735              | Notebook    | [52e1221ae0](https://linux-hardware.org/?probe=52e1221ae0) | May 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| Dell          | Latitude 5401               | Notebook    | [660bb28d6a](https://linux-hardware.org/?probe=660bb28d6a) | May 04, 2021 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [6f0e0fcc43](https://linux-hardware.org/?probe=6f0e0fcc43) | May 03, 2021 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [6f147cab82](https://linux-hardware.org/?probe=6f147cab82) | May 03, 2021 |
| Lenovo        | ThinkPad X200T 7449FWG      | Notebook    | [2d8d1beca4](https://linux-hardware.org/?probe=2d8d1beca4) | May 03, 2021 |
| HP            | 3048h                       | Desktop     | [74f738bae1](https://linux-hardware.org/?probe=74f738bae1) | May 01, 2021 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [d4307627a7](https://linux-hardware.org/?probe=d4307627a7) | May 01, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [b4ef2db7c1](https://linux-hardware.org/?probe=b4ef2db7c1) | May 01, 2021 |
| Dell          | Latitude 5520               | Notebook    | [d339546263](https://linux-hardware.org/?probe=d339546263) | Apr 30, 2021 |
| Acer          | Aspire 3690                 | Notebook    | [96bd8e49db](https://linux-hardware.org/?probe=96bd8e49db) | Apr 27, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [995ec93eb1](https://linux-hardware.org/?probe=995ec93eb1) | Apr 27, 2021 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [530bf24d20](https://linux-hardware.org/?probe=530bf24d20) | Apr 25, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [228ac8147b](https://linux-hardware.org/?probe=228ac8147b) | Apr 24, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [19b23587fa](https://linux-hardware.org/?probe=19b23587fa) | Apr 20, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [80fac11897](https://linux-hardware.org/?probe=80fac11897) | Apr 20, 2021 |
| ASUSTek       | X550CA                      | Notebook    | [103cc770c2](https://linux-hardware.org/?probe=103cc770c2) | Apr 18, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [c6ed3bc2f4](https://linux-hardware.org/?probe=c6ed3bc2f4) | Apr 18, 2021 |
| Dell          | System XPS L702X            | Notebook    | [6752a255ca](https://linux-hardware.org/?probe=6752a255ca) | Apr 18, 2021 |
| Dell          | System XPS L702X            | Notebook    | [20c39630ac](https://linux-hardware.org/?probe=20c39630ac) | Apr 18, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [8648cefc80](https://linux-hardware.org/?probe=8648cefc80) | Apr 18, 2021 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [8aab148f59](https://linux-hardware.org/?probe=8aab148f59) | Apr 17, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | Notebook    | [1b8f927465](https://linux-hardware.org/?probe=1b8f927465) | Apr 16, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | Notebook    | [7878f15fa6](https://linux-hardware.org/?probe=7878f15fa6) | Apr 15, 2021 |
| Dell          | Latitude 5490               | Notebook    | [bb7e4cf726](https://linux-hardware.org/?probe=bb7e4cf726) | Apr 13, 2021 |
| Sony          | VGN-FW31ZJ                  | Notebook    | [b1bc398f58](https://linux-hardware.org/?probe=b1bc398f58) | Apr 10, 2021 |
| HP            | 872E                        | Mini pc     | [7791a24770](https://linux-hardware.org/?probe=7791a24770) | Apr 08, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [c6fc94dd62](https://linux-hardware.org/?probe=c6fc94dd62) | Apr 08, 2021 |
| Sony          | VGN-FW31ZJ                  | Notebook    | [9de66e685f](https://linux-hardware.org/?probe=9de66e685f) | Apr 05, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [79c0025946](https://linux-hardware.org/?probe=79c0025946) | Apr 04, 2021 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [0b11aa525b](https://linux-hardware.org/?probe=0b11aa525b) | Apr 04, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [051017604f](https://linux-hardware.org/?probe=051017604f) | Apr 04, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [aef62f4f18](https://linux-hardware.org/?probe=aef62f4f18) | Apr 02, 2021 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [b4b60c7e29](https://linux-hardware.org/?probe=b4b60c7e29) | Apr 02, 2021 |
| Dell          | Latitude E6400              | Notebook    | [f4e375c3e4](https://linux-hardware.org/?probe=f4e375c3e4) | Apr 01, 2021 |
| Dell          | Latitude E5440              | Notebook    | [757746e097](https://linux-hardware.org/?probe=757746e097) | Apr 01, 2021 |
| ASUSTek       | PRIME A320M-K 2020-03-20    | Desktop     | [19aaa9b56e](https://linux-hardware.org/?probe=19aaa9b56e) | Mar 30, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [b72dc7a1c6](https://linux-hardware.org/?probe=b72dc7a1c6) | Mar 29, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [0ee0070622](https://linux-hardware.org/?probe=0ee0070622) | Mar 27, 2021 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [d68e01744f](https://linux-hardware.org/?probe=d68e01744f) | Mar 26, 2021 |
| ASUSTek       | P5Q SE2                     | Desktop     | [bcc4de28fb](https://linux-hardware.org/?probe=bcc4de28fb) | Mar 26, 2021 |
| ASUSTek       | X550CL                      | Notebook    | [72ec76771c](https://linux-hardware.org/?probe=72ec76771c) | Mar 24, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [c3909a14fe](https://linux-hardware.org/?probe=c3909a14fe) | Mar 22, 2021 |
| Toshiba       | Satellite C850-13Z          | Notebook    | [f8b44b58ee](https://linux-hardware.org/?probe=f8b44b58ee) | Mar 21, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [67ef60c8b1](https://linux-hardware.org/?probe=67ef60c8b1) | Mar 20, 2021 |
| HP            | Pavilion dv5                | Notebook    | [f84bed8734](https://linux-hardware.org/?probe=f84bed8734) | Mar 19, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [2f2bf700ae](https://linux-hardware.org/?probe=2f2bf700ae) | Mar 18, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [0f7e04c439](https://linux-hardware.org/?probe=0f7e04c439) | Mar 17, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [60ad7c7aec](https://linux-hardware.org/?probe=60ad7c7aec) | Mar 17, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [285b5b2d08](https://linux-hardware.org/?probe=285b5b2d08) | Mar 17, 2021 |
| Dell          | Latitude 3510               | Notebook    | [24bc2a77b2](https://linux-hardware.org/?probe=24bc2a77b2) | Mar 16, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [fbebe98252](https://linux-hardware.org/?probe=fbebe98252) | Mar 13, 2021 |
| Shuttle       | FH61V                       | Desktop     | [3e811ec55d](https://linux-hardware.org/?probe=3e811ec55d) | Mar 13, 2021 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [dcc5bdef7d](https://linux-hardware.org/?probe=dcc5bdef7d) | Mar 12, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [4aae1e6d26](https://linux-hardware.org/?probe=4aae1e6d26) | Mar 11, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Slovakia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 102       | 10.13%  |
| Ubuntu 18.04       | 59        | 5.86%   |
| Ubuntu 22.04       | 54        | 5.36%   |
| BlackPanther 18.1  | 54        | 5.36%   |
| OpenMandriva 4.3   | 31        | 3.08%   |
| OpenMandriva 4.2   | 26        | 2.58%   |
| Linux Mint 21.1    | 19        | 1.89%   |
| Debian 11          | 19        | 1.89%   |
| Arch Rolling       | 18        | 1.79%   |
| Linux Mint 21.2    | 16        | 1.59%   |
| Zorin 16           | 15        | 1.49%   |
| ROSA R10           | 14        | 1.39%   |
| Pop!_OS 22.04      | 14        | 1.39%   |
| Linux Mint 20.2    | 14        | 1.39%   |
| Linux Mint 20.1    | 14        | 1.39%   |
| Debian 12          | 14        | 1.39%   |
| Linux Mint 21      | 13        | 1.29%   |
| Linux Mint 20.3    | 13        | 1.29%   |
| MX 19              | 12        | 1.19%   |
| Linux Mint 19.3    | 12        | 1.19%   |
| OpenMandriva 23.08 | 11        | 1.09%   |
| OpenMandriva 23.01 | 11        | 1.09%   |
| Fedora 34          | 11        | 1.09%   |
| OpenMandriva 23.03 | 10        | 0.99%   |
| Xubuntu 18.04      | 9         | 0.89%   |
| Ubuntu 20.10       | 9         | 0.89%   |
| Ubuntu 19.04       | 8         | 0.79%   |
| Linux Mint 20      | 8         | 0.79%   |
| Fedora 39          | 8         | 0.79%   |
| Fedora 37          | 8         | 0.79%   |
| Fedora 33          | 8         | 0.79%   |
| Fedora 31          | 8         | 0.79%   |
| Ubuntu 23.10       | 7         | 0.7%    |
| Ubuntu 19.10       | 7         | 0.7%    |
| Pop!_OS 21.10      | 7         | 0.7%    |
| Pop!_OS 20.10      | 7         | 0.7%    |
| MX 18              | 7         | 0.7%    |
| Manjaro            | 7         | 0.7%    |
| Fedora 38          | 7         | 0.7%    |
| Debian 10          | 7         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 254       | 27.14%  |
| Linux Mint    | 105       | 11.22%  |
| OpenMandriva  | 99        | 10.58%  |
| Fedora        | 61        | 6.52%   |
| BlackPanther  | 56        | 5.98%   |
| Debian        | 44        | 4.7%    |
| Pop!_OS       | 34        | 3.63%   |
| ROSA          | 32        | 3.42%   |
| Arch          | 25        | 2.67%   |
| Zorin         | 24        | 2.56%   |
| Xubuntu       | 21        | 2.24%   |
| Manjaro       | 21        | 2.24%   |
| MX            | 19        | 2.03%   |
| Kubuntu       | 19        | 2.03%   |
| KDE neon      | 11        | 1.18%   |
| Gentoo        | 9         | 0.96%   |
| Endless       | 8         | 0.85%   |
| openSUSE      | 7         | 0.75%   |
| Lubuntu       | 7         | 0.75%   |
| EndeavourOS   | 7         | 0.75%   |
| ArcoLinux     | 7         | 0.75%   |
| SteamOS       | 6         | 0.64%   |
| Ubuntu Unity  | 5         | 0.53%   |
| Elementary    | 5         | 0.53%   |
| Devuan        | 5         | 0.53%   |
| Raspbian      | 4         | 0.43%   |
| Kali          | 4         | 0.43%   |
| Ubuntu MATE   | 3         | 0.32%   |
| CentOS        | 3         | 0.32%   |
| Ubuntu Budgie | 2         | 0.21%   |
| Parrot        | 2         | 0.21%   |
| LMDE          | 2         | 0.21%   |
| Garuda Linux  | 2         | 0.21%   |
| Artix         | 2         | 0.21%   |
| antiX         | 2         | 0.21%   |
| Alpine        | 2         | 0.21%   |
| Ubuntu Studio | 1         | 0.11%   |
| TUXEDO OS     | 1         | 0.11%   |
| Rocky Linux   | 1         | 0.11%   |
| RHEL          | 1         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 4.18.16-desktop-1bP             | 44        | 3.91%   |
| 5.16.7-desktop-1omv4003         | 27        | 2.4%    |
| 5.10.14-desktop-1omv4002        | 25        | 2.22%   |
| 5.6.14-desktop-2bP              | 14        | 1.25%   |
| 5.4.0-58-generic                | 14        | 1.25%   |
| 5.15.0-56-generic               | 14        | 1.25%   |
| 6.1.1-desktop-1omv2290          | 11        | 0.98%   |
| 6.2.6-desktop-1omv2390          | 10        | 0.89%   |
| 5.4.0-42-generic                | 10        | 0.89%   |
| 6.2.0-26-generic                | 8         | 0.71%   |
| 5.4.0-52-generic                | 8         | 0.71%   |
| 5.15.0-58-generic               | 8         | 0.71%   |
| 4.19.0-13-amd64                 | 8         | 0.71%   |
| 6.4.11-desktop-1omv2390         | 7         | 0.62%   |
| 5.8.0-43-generic                | 7         | 0.62%   |
| 5.19.0-38-generic               | 7         | 0.62%   |
| 5.15.0-43-generic               | 7         | 0.62%   |
| 5.11.0-27-generic               | 7         | 0.62%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 7         | 0.62%   |
| 4.15.0-66-generic               | 7         | 0.62%   |
| 5.8.0-50-generic                | 6         | 0.53%   |
| 5.4.0-90-generic                | 6         | 0.53%   |
| 5.4.0-73-generic                | 6         | 0.53%   |
| 5.4.0-26-generic                | 6         | 0.53%   |
| 5.3.0-40-generic                | 6         | 0.53%   |
| 5.15.0-91-generic               | 6         | 0.53%   |
| 4.19.0-14-amd64                 | 6         | 0.53%   |
| 6.6.2-desktop-1omv2390          | 5         | 0.44%   |
| 6.2.0-36-generic                | 5         | 0.44%   |
| 6.2.0-33-generic                | 5         | 0.44%   |
| 5.8.0-44-generic                | 5         | 0.44%   |
| 5.4.0-65-generic                | 5         | 0.44%   |
| 5.4.0-47-generic                | 5         | 0.44%   |
| 5.3.0-26-generic                | 5         | 0.44%   |
| 5.15.85-desktop-1bP             | 5         | 0.44%   |
| 5.15.0-83-generic               | 5         | 0.44%   |
| 5.15.0-67-generic               | 5         | 0.44%   |
| 5.15.0-48-generic               | 5         | 0.44%   |
| 5.13.0-22-generic               | 5         | 0.44%   |
| 5.10.0-23-amd64                 | 5         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 123       | 11.84%  |
| 5.15.0  | 93        | 8.95%   |
| 4.15.0  | 59        | 5.68%   |
| 5.8.0   | 46        | 4.43%   |
| 4.18.16 | 45        | 4.33%   |
| 5.13.0  | 33        | 3.18%   |
| 5.3.0   | 31        | 2.98%   |
| 6.5.0   | 30        | 2.89%   |
| 5.19.0  | 29        | 2.79%   |
| 5.11.0  | 29        | 2.79%   |
| 6.2.0   | 27        | 2.6%    |
| 5.16.7  | 27        | 2.6%    |
| 5.10.14 | 25        | 2.41%   |
| 5.10.0  | 22        | 2.12%   |
| 5.0.0   | 18        | 1.73%   |
| 4.18.0  | 16        | 1.54%   |
| 6.1.0   | 15        | 1.44%   |
| 4.19.0  | 15        | 1.44%   |
| 5.6.14  | 14        | 1.35%   |
| 6.2.6   | 13        | 1.25%   |
| 6.1.1   | 11        | 1.06%   |
| 6.4.11  | 7         | 0.67%   |
| 4.9.60  | 7         | 0.67%   |
| 6.6.2   | 6         | 0.58%   |
| 4.9.20  | 6         | 0.58%   |
| 5.9.16  | 5         | 0.48%   |
| 5.15.85 | 5         | 0.48%   |
| 4.9.124 | 5         | 0.48%   |
| 6.8.0   | 4         | 0.38%   |
| 6.4.0   | 4         | 0.38%   |
| 6.0.10  | 4         | 0.38%   |
| 5.16.13 | 4         | 0.38%   |
| 4.4.0   | 4         | 0.38%   |
| 6.4.8   | 3         | 0.29%   |
| 6.4.12  | 3         | 0.29%   |
| 6.3.8   | 3         | 0.29%   |
| 6.1.52  | 3         | 0.29%   |
| 5.4.83  | 3         | 0.29%   |
| 5.18.12 | 3         | 0.29%   |
| 5.17.5  | 3         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 131       | 12.79%  |
| 5.15    | 121       | 11.82%  |
| 5.10    | 63        | 6.15%   |
| 4.18    | 61        | 5.96%   |
| 4.15    | 59        | 5.76%   |
| 5.8     | 51        | 4.98%   |
| 6.2     | 45        | 4.39%   |
| 6.1     | 45        | 4.39%   |
| 5.11    | 41        | 4%      |
| 6.5     | 40        | 3.91%   |
| 5.16    | 39        | 3.81%   |
| 5.13    | 39        | 3.81%   |
| 5.3     | 36        | 3.52%   |
| 5.19    | 34        | 3.32%   |
| 4.9     | 26        | 2.54%   |
| 4.19    | 22        | 2.15%   |
| 5.0     | 20        | 1.95%   |
| 6.4     | 19        | 1.86%   |
| 5.6     | 18        | 1.76%   |
| 6.6     | 17        | 1.66%   |
| 6.0     | 11        | 1.07%   |
| 5.9     | 10        | 0.98%   |
| 5.12    | 9         | 0.88%   |
| 6.3     | 8         | 0.78%   |
| 5.7     | 8         | 0.78%   |
| 5.5     | 7         | 0.68%   |
| 5.18    | 7         | 0.68%   |
| 5.17    | 7         | 0.68%   |
| 5.14    | 6         | 0.59%   |
| 6.8     | 5         | 0.49%   |
| 6.7     | 4         | 0.39%   |
| 4.4     | 4         | 0.39%   |
| 4.1     | 3         | 0.29%   |
| 5.2     | 2         | 0.2%    |
| 5.1     | 1         | 0.1%    |
| 4.7     | 1         | 0.1%    |
| 4.17    | 1         | 0.1%    |
| 4.16    | 1         | 0.1%    |
| 4.12    | 1         | 0.1%    |
| 4.11    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 840       | 92.51%  |
| i686    | 50        | 5.51%   |
| aarch64 | 12        | 1.32%   |
| armv7l  | 6         | 0.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 339       | 36.26%  |
| KDE5            | 233       | 24.92%  |
| Unknown         | 99        | 10.59%  |
| XFCE            | 87        | 9.3%    |
| X-Cinnamon      | 80        | 8.56%   |
| MATE            | 27        | 2.89%   |
| KDE4            | 14        | 1.5%    |
| KDE             | 11        | 1.18%   |
| LXQt            | 9         | 0.96%   |
| Cinnamon        | 8         | 0.86%   |
| LXDE            | 6         | 0.64%   |
| Unity           | 5         | 0.53%   |
| Pantheon        | 5         | 0.53%   |
| Budgie          | 3         | 0.32%   |
| Openbox         | 2         | 0.21%   |
| Hyprland        | 2         | 0.21%   |
| Trinity         | 1         | 0.11%   |
| KDE6            | 1         | 0.11%   |
| GNOME Flashback | 1         | 0.11%   |
| bspwm           | 1         | 0.11%   |
| awesome         | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 703       | 75.75%  |
| Wayland     | 158       | 17.03%  |
| Unknown     | 44        | 4.74%   |
| Tty         | 22        | 2.37%   |
| Unspecified | 1         | 0.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 401       | 42.93%  |
| SDDM    | 215       | 23.02%  |
| GDM3    | 98        | 10.49%  |
| LightDM | 97        | 10.39%  |
| GDM     | 79        | 8.46%   |
| TDM     | 21        | 2.25%   |
| KDM     | 14        | 1.5%    |
| SLiM    | 5         | 0.54%   |
| XDM     | 2         | 0.21%   |
| Ly      | 1         | 0.11%   |
| LXDM    | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 367       | 39.08%  |
| sk_SK       | 293       | 31.2%   |
| Unknown     | 170       | 18.1%   |
| cs_CZ       | 31        | 3.3%    |
| C           | 25        | 2.66%   |
| en_GB       | 22        | 2.34%   |
| hu_HU       | 11        | 1.17%   |
| ru_RU       | 5         | 0.53%   |
| sr_RS@latin | 2         | 0.21%   |
| pl_PL       | 2         | 0.21%   |
| en_CA       | 2         | 0.21%   |
| de_DE       | 2         | 0.21%   |
| uk_UA       | 1         | 0.11%   |
| ru_UA       | 1         | 0.11%   |
| POSIX       | 1         | 0.11%   |
| it_IT       | 1         | 0.11%   |
| en_US      | 1         | 0.11%   |
| en_AU       | 1         | 0.11%   |
| C.UTF8      | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 551       | 59.7%   |
| EFI  | 372       | 40.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 627       | 66.14%  |
| Overlay  | 147       | 15.51%  |
| Btrfs    | 88        | 9.28%   |
| Tmpfs    | 34        | 3.59%   |
| Unknown  | 27        | 2.85%   |
| Xfs      | 10        | 1.05%   |
| Zfs      | 8         | 0.84%   |
| Ext2     | 3         | 0.32%   |
| Ext3     | 2         | 0.21%   |
| F2fs     | 1         | 0.11%   |
| Bcachefs | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 424       | 45.49%  |
| GPT     | 314       | 33.69%  |
| MBR     | 194       | 20.82%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 775       | 82.45%  |
| Yes       | 165       | 17.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 633       | 68.95%  |
| Yes       | 285       | 31.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 193       | 21.4%   |
| Lenovo                  | 158       | 17.52%  |
| Hewlett-Packard         | 124       | 13.75%  |
| Dell                    | 95        | 10.53%  |
| Gigabyte Technology     | 53        | 5.88%   |
| Acer                    | 50        | 5.54%   |
| MSI                     | 47        | 5.21%   |
| ASRock                  | 27        | 2.99%   |
| Toshiba                 | 19        | 2.11%   |
| Intel                   | 15        | 1.66%   |
| Sony                    | 9         | 1%      |
| Apple                   | 9         | 1%      |
| Unknown                 | 8         | 0.89%   |
| UMAX                    | 7         | 0.78%   |
| Raspberry Pi Foundation | 7         | 0.78%   |
| Valve                   | 6         | 0.67%   |
| Samsung Electronics     | 6         | 0.67%   |
| Packard Bell            | 5         | 0.55%   |
| HUAWEI                  | 5         | 0.55%   |
| Fujitsu Siemens         | 5         | 0.55%   |
| Foxconn                 | 5         | 0.55%   |
| Fujitsu                 | 4         | 0.44%   |
| ZOTAC                   | 3         | 0.33%   |
| Timi                    | 3         | 0.33%   |
| Pegatron                | 3         | 0.33%   |
| Hardkernel              | 3         | 0.33%   |
| eMachines               | 3         | 0.33%   |
| Techvision              | 2         | 0.22%   |
| Shuttle                 | 2         | 0.22%   |
| Qualcomm Technologies   | 2         | 0.22%   |
| OEM                     | 2         | 0.22%   |
| Medion                  | 2         | 0.22%   |
| Google                  | 2         | 0.22%   |
| Xunlong                 | 1         | 0.11%   |
| XIAOMI                  | 1         | 0.11%   |
| VIA Technologies        | 1         | 0.11%   |
| TYAN Computer           | 1         | 0.11%   |
| TUXEDO                  | 1         | 0.11%   |
| Teclast                 | 1         | 0.11%   |
| sunxi                   | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| ASUS All Series                     | 14        | 1.55%   |
| Unknown                             | 10        | 1.11%   |
| Valve Jupiter                       | 6         | 0.67%   |
| HP Pavilion dv6                     | 5         | 0.55%   |
| ASUS TUF Gaming B550M-PLUS          | 5         | 0.55%   |
| RPi Raspberry Pi 4 Model B Rev 1.4  | 4         | 0.44%   |
| ASUS X550CC                         | 4         | 0.44%   |
| MSI MS-7D25                         | 3         | 0.33%   |
| Lenovo IdeaPadFlex 5 15IIL05 81X3   | 3         | 0.33%   |
| HP ProBook 4540s                    | 3         | 0.33%   |
| HP ProBook 4330s                    | 3         | 0.33%   |
| HP Pavilion g6                      | 3         | 0.33%   |
| Hardkernel ODROID-M1                | 3         | 0.33%   |
| Gigabyte H61M-S1                    | 3         | 0.33%   |
| Gigabyte F2A68HM-DS2                | 3         | 0.33%   |
| Dell OptiPlex 7010                  | 3         | 0.33%   |
| Dell Latitude E6540                 | 3         | 0.33%   |
| Acer Swift SF314-43                 | 3         | 0.33%   |
| UMAX VisionBook 14Wr Plus           | 2         | 0.22%   |
| Toshiba Satellite P300              | 2         | 0.22%   |
| Timi Redmi Book Pro 15 2022         | 2         | 0.22%   |
| Techvision TVI7309X                 | 2         | 0.22%   |
| Samsung R530/R730/P530              | 2         | 0.22%   |
| Qualcomm BENGAL IDP                 | 2         | 0.22%   |
| OEM X79-Turbo                       | 2         | 0.22%   |
| MSI VR610                           | 2         | 0.22%   |
| MSI MS-7C91                         | 2         | 0.22%   |
| MSI MS-7C02                         | 2         | 0.22%   |
| MSI MS-7592                         | 2         | 0.22%   |
| MSI GT60 2OC/2OD                    | 2         | 0.22%   |
| Lenovo Yoga Slim 7 Pro 14ITL5 82FX  | 2         | 0.22%   |
| Lenovo Y520-15IKBN 80WK             | 2         | 0.22%   |
| Lenovo ThinkPad P50 20EQS0VV2S      | 2         | 0.22%   |
| Lenovo ThinkBook 15 G3 ACL 21A4     | 2         | 0.22%   |
| Lenovo IdeaPad Z500 20202           | 2         | 0.22%   |
| Lenovo IdeaPad U260 20067           | 2         | 0.22%   |
| Lenovo IdeaPad S145-14AST 81ST      | 2         | 0.22%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2 | 2         | 0.22%   |
| Lenovo IdeaPad 5 15ABA7 82SG        | 2         | 0.22%   |
| Lenovo IdeaPad 320-15IAP 80XR       | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 59        | 6.54%   |
| Dell Latitude         | 40        | 4.43%   |
| Lenovo IdeaPad        | 38        | 4.21%   |
| HP ProBook            | 30        | 3.33%   |
| Acer Aspire           | 30        | 3.33%   |
| HP Pavilion           | 17        | 1.88%   |
| HP Compaq             | 17        | 1.88%   |
| Toshiba Satellite     | 16        | 1.77%   |
| HP EliteBook          | 16        | 1.77%   |
| ASUS ROG              | 15        | 1.66%   |
| ASUS PRIME            | 14        | 1.55%   |
| ASUS All              | 14        | 1.55%   |
| ASUS TUF              | 11        | 1.22%   |
| Lenovo Yoga           | 10        | 1.11%   |
| Dell XPS              | 10        | 1.11%   |
| Dell Vostro           | 10        | 1.11%   |
| Dell OptiPlex         | 10        | 1.11%   |
| ASUS VivoBook         | 10        | 1.11%   |
| Unknown               | 10        | 1.11%   |
| Dell Inspiron         | 9         | 1%      |
| Acer Swift            | 8         | 0.89%   |
| RPi Raspberry         | 7         | 0.78%   |
| Dell Precision        | 7         | 0.78%   |
| Valve Jupiter         | 6         | 0.67%   |
| Acer Extensa          | 6         | 0.67%   |
| UMAX VisionBook       | 5         | 0.55%   |
| Lenovo ThinkCentre    | 5         | 0.55%   |
| Lenovo IdeaCentre     | 5         | 0.55%   |
| HP ProLiant           | 5         | 0.55%   |
| ASUS Zenbook          | 5         | 0.55%   |
| Lenovo Legion         | 4         | 0.44%   |
| Lenovo IdeaPadFlex    | 4         | 0.44%   |
| HP ZBook              | 4         | 0.44%   |
| HP Laptop             | 4         | 0.44%   |
| ASUS X550CC           | 4         | 0.44%   |
| Packard Bell EasyNote | 3         | 0.33%   |
| MSI MS-7D25           | 3         | 0.33%   |
| Lenovo V15            | 3         | 0.33%   |
| Lenovo 3000           | 3         | 0.33%   |
| HP Spectre            | 3         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 85        | 9.42%   |
| 2013    | 71        | 7.87%   |
| 2020    | 67        | 7.43%   |
| 2019    | 63        | 6.98%   |
| 2011    | 63        | 6.98%   |
| 2008    | 57        | 6.32%   |
| 2009    | 56        | 6.21%   |
| 2018    | 53        | 5.88%   |
| 2021    | 47        | 5.21%   |
| 2010    | 43        | 4.77%   |
| 2017    | 42        | 4.66%   |
| 2014    | 42        | 4.66%   |
| 2007    | 42        | 4.66%   |
| 2022    | 38        | 4.21%   |
| 2016    | 38        | 4.21%   |
| 2015    | 35        | 3.88%   |
| 2006    | 23        | 2.55%   |
| 2023    | 15        | 1.66%   |
| Unknown | 15        | 1.66%   |
| 2005    | 3         | 0.33%   |
| 2024    | 1         | 0.11%   |
| 2002    | 1         | 0.11%   |
| 2001    | 1         | 0.11%   |
| 2000    | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 513       | 56.87%  |
| Desktop        | 316       | 35.03%  |
| Convertible    | 21        | 2.33%   |
| System on chip | 16        | 1.77%   |
| All in one     | 15        | 1.66%   |
| Mini pc        | 10        | 1.11%   |
| Server         | 6         | 0.67%   |
| Tablet         | 5         | 0.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 837       | 92.18%  |
| Enabled  | 71        | 7.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 900       | 99.78%  |
| Yes  | 2         | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 217       | 23.36%  |
| 4.01-8.0        | 211       | 22.71%  |
| 8.01-16.0       | 171       | 18.41%  |
| 16.01-24.0      | 149       | 16.04%  |
| 32.01-64.0      | 57        | 6.14%   |
| 1.01-2.0        | 49        | 5.27%   |
| 2.01-3.0        | 23        | 2.48%   |
| 64.01-256.0     | 21        | 2.26%   |
| 24.01-32.0      | 14        | 1.51%   |
| 0.51-1.0        | 12        | 1.29%   |
| 0.01-0.5        | 3         | 0.32%   |
| More than 256.0 | 2         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 354       | 34.98%  |
| 2.01-3.0   | 221       | 21.84%  |
| 0.51-1.0   | 118       | 11.66%  |
| 3.01-4.0   | 113       | 11.17%  |
| 4.01-8.0   | 108       | 10.67%  |
| 0.01-0.5   | 51        | 5.04%   |
| 8.01-16.0  | 40        | 3.95%   |
| 16.01-24.0 | 3         | 0.3%    |
| 32.01-64.0 | 2         | 0.2%    |
| 24.01-32.0 | 2         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 582       | 61.07%  |
| 2      | 237       | 24.87%  |
| 3      | 68        | 7.14%   |
| 5      | 19        | 1.99%   |
| 4      | 19        | 1.99%   |
| 0      | 17        | 1.78%   |
| 6      | 6         | 0.63%   |
| 31     | 1         | 0.1%    |
| 17     | 1         | 0.1%    |
| 13     | 1         | 0.1%    |
| 8      | 1         | 0.1%    |
| 7      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 522       | 57.24%  |
| Yes       | 390       | 42.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 775       | 85.73%  |
| No        | 129       | 14.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 650       | 71.27%  |
| No        | 262       | 28.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 489       | 53.5%   |
| No        | 425       | 46.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Slovakia | 902       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Bratislava             | 317       | 31.89%  |
| Košice                | 76        | 7.65%   |
| Banská Bystrica       | 40        | 4.02%   |
| Nitra                  | 37        | 3.72%   |
| Trnava                 | 22        | 2.21%   |
| Žilina                | 18        | 1.81%   |
| Prešov                | 16        | 1.61%   |
| Martin                 | 14        | 1.41%   |
| Nové Zámky           | 13        | 1.31%   |
| Poprad                 | 12        | 1.21%   |
| Humenné               | 12        | 1.21%   |
| Dolny Ohaj             | 12        | 1.21%   |
| Brezno                 | 11        | 1.11%   |
| Zvolen                 | 10        | 1.01%   |
| Bardejov               | 10        | 1.01%   |
| Trenčín              | 9         | 0.91%   |
| Tornaľa               | 8         | 0.8%    |
| Levice                 | 8         | 0.8%    |
| Soblahov               | 6         | 0.6%    |
| Ružomberok            | 6         | 0.6%    |
| Pezinok                | 6         | 0.6%    |
| Lučenec               | 6         | 0.6%    |
| Kysucké Nové Mesto   | 6         | 0.6%    |
| Galanta                | 6         | 0.6%    |
| Cechynce               | 6         | 0.6%    |
| Topoľčany            | 5         | 0.5%    |
| Senec                  | 5         | 0.5%    |
| Rožňava              | 5         | 0.5%    |
| Liptovský Mikuláš   | 5         | 0.5%    |
| Velky Krtis            | 4         | 0.4%    |
| Štúrovo              | 4         | 0.4%    |
| Skalica                | 4         | 0.4%    |
| Šaľa                 | 4         | 0.4%    |
| Rozhanovce             | 4         | 0.4%    |
| Rimavská Sobota       | 4         | 0.4%    |
| Partizánske           | 4         | 0.4%    |
| Nové Mesto nad Váhom | 4         | 0.4%    |
| Námestovo             | 4         | 0.4%    |
| Modra                  | 4         | 0.4%    |
| Kežmarok              | 4         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 217       | 437    | 16.69%  |
| Samsung Electronics         | 195       | 300    | 15%     |
| Seagate                     | 193       | 280    | 14.85%  |
| Toshiba                     | 70        | 115    | 5.38%   |
| Kingston                    | 66        | 85     | 5.08%   |
| SanDisk                     | 58        | 72     | 4.46%   |
| Unknown                     | 57        | 86     | 4.38%   |
| Hitachi                     | 50        | 66     | 3.85%   |
| A-DATA Technology           | 43        | 62     | 3.31%   |
| Intel                       | 41        | 60     | 3.15%   |
| Patriot                     | 38        | 65     | 2.92%   |
| SK hynix                    | 33        | 38     | 2.54%   |
| Micron Technology           | 26        | 34     | 2%      |
| Crucial                     | 24        | 29     | 1.85%   |
| HGST                        | 21        | 30     | 1.62%   |
| Apacer                      | 16        | 21     | 1.23%   |
| Verbatim                    | 8         | 10     | 0.62%   |
| Phison                      | 8         | 10     | 0.62%   |
| Maxtor                      | 8         | 14     | 0.62%   |
| Phison Electronics          | 7         | 7      | 0.54%   |
| KIOXIA                      | 6         | 18     | 0.46%   |
| Gigabyte Technology         | 6         | 8      | 0.46%   |
| Fujitsu                     | 6         | 7      | 0.46%   |
| China                       | 6         | 9      | 0.46%   |
| OCZ                         | 5         | 5      | 0.38%   |
| KingDian                    | 5         | 7      | 0.38%   |
| HS-SSD-E100                 | 5         | 5      | 0.38%   |
| Hewlett-Packard             | 5         | 7      | 0.38%   |
| Micron/Crucial Technology   | 4         | 4      | 0.31%   |
| LITEON                      | 4         | 4      | 0.31%   |
| Unknown                     | 4         | 4      | 0.31%   |
| Union Memory                | 3         | 3      | 0.23%   |
| Realtek Semiconductor       | 3         | 3      | 0.23%   |
| LITEONIT                    | 3         | 3      | 0.23%   |
| Kingston Technology Company | 3         | 6      | 0.23%   |
| Intenso                     | 3         | 7      | 0.23%   |
| IBM/Hitachi                 | 3         | 3      | 0.23%   |
| GOODRAM                     | 3         | 5      | 0.23%   |
| Apple                       | 3         | 4      | 0.23%   |
| XPG                         | 2         | 5      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                          | 16        | 1.11%   |
| Patriot Burst 240GB SSD                            | 14        | 0.97%   |
| Kingston SV300S37A120G 120GB SSD                   | 13        | 0.9%    |
| Samsung SSD 850 EVO 250GB                          | 11        | 0.76%   |
| Unknown MMC Card  64GB                             | 10        | 0.69%   |
| Samsung SSD 870 EVO 500GB                          | 10        | 0.69%   |
| Samsung SSD 860 EVO 250GB                          | 10        | 0.69%   |
| Samsung SSD 850 EVO 500GB                          | 10        | 0.69%   |
| Patriot Burst 120GB SSD                            | 10        | 0.69%   |
| Kingston SA400S37120G 120GB SSD                    | 10        | 0.69%   |
| Seagate ST9500325AS 500GB                          | 9         | 0.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 9         | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB                     | 8         | 0.55%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 7         | 0.49%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 7         | 0.49%   |
| Seagate ST3500418AS 500GB                          | 7         | 0.49%   |
| Seagate ST2000DM008-2FR102 2TB                     | 7         | 0.49%   |
| Patriot Burst 480GB SSD                            | 7         | 0.49%   |
| Apacer AS350 512GB SSD                             | 7         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 6         | 0.42%   |
| Seagate ST9500420AS 500GB                          | 6         | 0.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 6         | 0.42%   |
| SanDisk NVMe SSD Drive 512GB                       | 6         | 0.42%   |
| SanDisk NVMe SSD Drive 1024GB                      | 6         | 0.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB  | 6         | 0.42%   |
| Kingston SA400S37240G 240GB SSD                    | 6         | 0.42%   |
| HGST HTS721010A9E630 1TB                           | 6         | 0.42%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 5         | 0.35%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 5         | 0.35%   |
| Toshiba NVMe SSD Drive 512GB                       | 5         | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                     | 5         | 0.35%   |
| Samsung NVMe SSD Drive 500GB                       | 5         | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 5         | 0.35%   |
| Hitachi HTS545050B9A300 500GB                      | 5         | 0.35%   |
| Hitachi HTS543232A7A384 320GB                      | 5         | 0.35%   |
| HGST HTS725050A7E630 500GB                         | 5         | 0.35%   |
| A-DATA SU650 120GB SSD                             | 5         | 0.35%   |
| A-DATA SP600 32GB SSD                              | 5         | 0.35%   |
| WDC WD10JPLX-00MBPT0 1TB                           | 4         | 0.28%   |
| WDC WD10EZEX-00KUWA0 1TB                           | 4         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 191       | 277    | 34.6%   |
| WDC                 | 188       | 387    | 34.06%  |
| Toshiba             | 51        | 94     | 9.24%   |
| Hitachi             | 50        | 66     | 9.06%   |
| Samsung Electronics | 24        | 40     | 4.35%   |
| HGST                | 21        | 30     | 3.8%    |
| Maxtor              | 8         | 14     | 1.45%   |
| Fujitsu             | 6         | 7      | 1.09%   |
| Hewlett-Packard     | 4         | 6      | 0.72%   |
| IBM/Hitachi         | 3         | 3      | 0.54%   |
| HGST HTS            | 2         | 2      | 0.36%   |
| USB3.0              | 1         | 2      | 0.18%   |
| Unknown             | 1         | 1      | 0.18%   |
| StoreJet            | 1         | 1      | 0.18%   |
| ExcelStor           | 1         | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 99        | 140    | 23.68%  |
| Kingston            | 50        | 69     | 11.96%  |
| A-DATA Technology   | 37        | 55     | 8.85%   |
| Patriot             | 35        | 61     | 8.37%   |
| SanDisk             | 29        | 33     | 6.94%   |
| Intel               | 24        | 37     | 5.74%   |
| Crucial             | 24        | 29     | 5.74%   |
| WDC                 | 23        | 28     | 5.5%    |
| Apacer              | 12        | 17     | 2.87%   |
| Micron Technology   | 10        | 15     | 2.39%   |
| Toshiba             | 8         | 8      | 1.91%   |
| SK hynix            | 8         | 8      | 1.91%   |
| Verbatim            | 7         | 9      | 1.67%   |
| China               | 6         | 9      | 1.44%   |
| OCZ                 | 5         | 5      | 1.2%    |
| LITEON              | 4         | 4      | 0.96%   |
| Gigabyte Technology | 4         | 6      | 0.96%   |
| LITEONIT            | 3         | 3      | 0.72%   |
| KingDian            | 3         | 5      | 0.72%   |
| Intenso             | 3         | 7      | 0.72%   |
| GOODRAM             | 3         | 5      | 0.72%   |
| Union Memory        | 2         | 2      | 0.48%   |
| Transcend           | 2         | 2      | 0.48%   |
| FORESEE             | 2         | 3      | 0.48%   |
| WDC WDS2            | 1         | 1      | 0.24%   |
| ULTIMATE            | 1         | 2      | 0.24%   |
| PNY                 | 1         | 2      | 0.24%   |
| Netac               | 1         | 1      | 0.24%   |
| KingSpec            | 1         | 1      | 0.24%   |
| IM3D                | 1         | 1      | 0.24%   |
| HS-SSD-E100         | 1         | 1      | 0.24%   |
| HS-SSD-C100         | 1         | 3      | 0.24%   |
| Hewlett-Packard     | 1         | 1      | 0.24%   |
| Faspeed             | 1         | 1      | 0.24%   |
| Emtec               | 1         | 1      | 0.24%   |
| Corsair             | 1         | 1      | 0.24%   |
| Apple               | 1         | 1      | 0.24%   |
| AMD                 | 1         | 1      | 0.24%   |
| 2.5                 | 1         | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 455       | 931    | 39.33%  |
| SSD     | 374       | 579    | 32.32%  |
| NVMe    | 255       | 375    | 22.04%  |
| MMC     | 57        | 82     | 4.93%   |
| Unknown | 16        | 20     | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 675       | 1484   | 65.79%  |
| NVMe | 255       | 372    | 24.85%  |
| MMC  | 57        | 82     | 5.56%   |
| SAS  | 39        | 49     | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 560       | 981    | 66.19%  |
| 0.51-1.0   | 193       | 353    | 22.81%  |
| 1.01-2.0   | 52        | 89     | 6.15%   |
| 3.01-4.0   | 19        | 45     | 2.25%   |
| 2.01-3.0   | 13        | 27     | 1.54%   |
| 4.01-10.0  | 8         | 14     | 0.95%   |
| 10.01-20.0 | 1         | 1      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 242       | 24.44%  |
| 251-500        | 197       | 19.9%   |
| 501-1000       | 140       | 14.14%  |
| 1-20           | 114       | 11.52%  |
| Unknown        | 76        | 7.68%   |
| 51-100         | 67        | 6.77%   |
| 1001-2000      | 56        | 5.66%   |
| 21-50          | 54        | 5.45%   |
| More than 3000 | 26        | 2.63%   |
| 2001-3000      | 18        | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 403       | 39.82%  |
| 21-50          | 161       | 15.91%  |
| 101-250        | 120       | 11.86%  |
| 51-100         | 102       | 10.08%  |
| Unknown        | 76        | 7.51%   |
| 251-500        | 66        | 6.52%   |
| 501-1000       | 47        | 4.64%   |
| 1001-2000      | 22        | 2.17%   |
| More than 3000 | 11        | 1.09%   |
| 2001-3000      | 4         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba MK7575GSX 752GB          | 3         | 5      | 2.34%   |
| Seagate ST9500325AS 500GB        | 3         | 4      | 2.34%   |
| WDC WD50EFRX-68MYMN1 5TB         | 2         | 2      | 1.56%   |
| WDC WD5000BEKT-22KA9T0 500GB     | 2         | 8      | 1.56%   |
| WDC WD10JPLX-00MBPT0 1TB         | 2         | 14     | 1.56%   |
| WDC WD10EZEX-75WN4A0 1TB         | 2         | 3      | 1.56%   |
| WDC WD10EALX-009BA0 1TB          | 2         | 2      | 1.56%   |
| Toshiba HDWD110 1TB              | 2         | 2      | 1.56%   |
| Seagate ST980811AS 80GB          | 2         | 2      | 1.56%   |
| Seagate ST9250315AS 250GB        | 2         | 2      | 1.56%   |
| Seagate ST500LM000-SSHD-8GB      | 2         | 5      | 1.56%   |
| Seagate ST3320413CS 320GB        | 2         | 2      | 1.56%   |
| Seagate ST320LT007-9ZV142 320GB  | 2         | 2      | 1.56%   |
| Kingston SV300S37A60G 64GB SSD   | 2         | 3      | 1.56%   |
| Hitachi HTS543232A7A384 320GB    | 2         | 2      | 1.56%   |
| HGST HTS721010A9E630 1TB         | 2         | 6      | 1.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 1      | 0.78%   |
| WDC WD800JD-60LSA0 80GB          | 1         | 1      | 0.78%   |
| WDC WD7500BPVT-80HXZT3 752GB     | 1         | 1      | 0.78%   |
| WDC WD7500BPVT-24HXZT3 752GB     | 1         | 1      | 0.78%   |
| WDC WD7500AAVS-00D7B1 752GB      | 1         | 1      | 0.78%   |
| WDC WD5000LPVT-24G33T1 500GB     | 1         | 1      | 0.78%   |
| WDC WD5000LPLX-75ZNTT1 500GB     | 1         | 1      | 0.78%   |
| WDC WD5000BPVT-00HXZT1 500GB     | 1         | 1      | 0.78%   |
| WDC WD5000BEVT-22A0RT0 500GB     | 1         | 2      | 0.78%   |
| WDC WD5000AAVS-22G9B1 500GB      | 1         | 4      | 0.78%   |
| WDC WD5000AAKX-603CA0 500GB      | 1         | 1      | 0.78%   |
| WDC WD3200BEVT-75ZCT2 320GB      | 1         | 1      | 0.78%   |
| WDC WD3200AAKS-22L6A0 320GB      | 1         | 1      | 0.78%   |
| WDC WD3200AAJS-56B4A0 320GB      | 1         | 2      | 0.78%   |
| WDC WD2500AAKX-753CA1 250GB      | 1         | 2      | 0.78%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 1      | 0.78%   |
| WDC WD20EURS-63S48Y0 2TB         | 1         | 1      | 0.78%   |
| WDC WD1600JS-61MHB1 160GB        | 1         | 1      | 0.78%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1         | 1      | 0.78%   |
| WDC WD10EZEX-00RKKA0 1TB         | 1         | 1      | 0.78%   |
| WDC WD10EZEX-00KUWA0 1TB         | 1         | 1      | 0.78%   |
| Toshiba MQ01ABF050 500GB         | 1         | 3      | 0.78%   |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 0.78%   |
| Toshiba MQ01ABD075 752GB         | 1         | 1      | 0.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 43     | 26.4%   |
| WDC                 | 28        | 56     | 22.4%   |
| Hitachi             | 13        | 14     | 10.4%   |
| Toshiba             | 12        | 17     | 9.6%    |
| Samsung Electronics | 7         | 18     | 5.6%    |
| Kingston            | 5         | 6      | 4%      |
| SK hynix            | 4         | 4      | 3.2%    |
| Micron Technology   | 3         | 3      | 2.4%    |
| Maxtor              | 3         | 3      | 2.4%    |
| Intel               | 3         | 3      | 2.4%    |
| HGST                | 3         | 7      | 2.4%    |
| SanDisk             | 2         | 3      | 1.6%    |
| OCZ                 | 2         | 2      | 1.6%    |
| Lenovo              | 1         | 1      | 0.8%    |
| IM3D                | 1         | 1      | 0.8%    |
| IBM/Hitachi         | 1         | 1      | 0.8%    |
| Fujitsu             | 1         | 2      | 0.8%    |
| ExcelStor           | 1         | 1      | 0.8%    |
| Crucial             | 1         | 1      | 0.8%    |
| A-DATA Technology   | 1         | 1      | 0.8%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 43     | 33.67%  |
| WDC                 | 27        | 55     | 27.55%  |
| Hitachi             | 13        | 14     | 13.27%  |
| Toshiba             | 12        | 17     | 12.24%  |
| Samsung Electronics | 4         | 8      | 4.08%   |
| Maxtor              | 3         | 3      | 3.06%   |
| HGST                | 3         | 7      | 3.06%   |
| IBM/Hitachi         | 1         | 1      | 1.02%   |
| Fujitsu             | 1         | 2      | 1.02%   |
| ExcelStor           | 1         | 1      | 1.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 93        | 151    | 78.15%  |
| SSD  | 22        | 32     | 18.49%  |
| NVMe | 4         | 4      | 3.36%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba MK5065GSX 500GB           | 2         | 2      | 33.33%  |
| Seagate ST9320325AS 320GB         | 1         | 1      | 16.67%  |
| Seagate ST3500418AS 500GB         | 1         | 2      | 16.67%  |
| Seagate ST2000DM001-1CH164 2TB    | 1         | 1      | 16.67%  |
| Samsung Electronics HD321HJ 320GB | 1         | 2      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 50%     |
| Toshiba             | 2         | 2      | 33.33%  |
| Samsung Electronics | 1         | 2      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 509       | 969    | 50.9%   |
| Works    | 370       | 823    | 37%     |
| Malfunc  | 115       | 187    | 11.5%   |
| Failed   | 6         | 8      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 574       | 52.61%  |
| AMD                              | 170       | 15.58%  |
| Samsung Electronics              | 88        | 8.07%   |
| SanDisk                          | 42        | 3.85%   |
| Nvidia                           | 26        | 2.38%   |
| SK hynix                         | 25        | 2.29%   |
| JMicron Technology               | 22        | 2.02%   |
| Phison Electronics               | 21        | 1.92%   |
| Kingston Technology Company      | 20        | 1.83%   |
| Micron Technology                | 16        | 1.47%   |
| ASMedia Technology               | 13        | 1.19%   |
| Toshiba America Info Systems     | 11        | 1.01%   |
| ADATA Technology                 | 9         | 0.82%   |
| Marvell Technology Group         | 7         | 0.64%   |
| VIA Technologies                 | 6         | 0.55%   |
| KIOXIA                           | 6         | 0.55%   |
| Micron/Crucial Technology        | 4         | 0.37%   |
| LSI Logic / Symbios Logic        | 4         | 0.37%   |
| Silicon Motion                   | 3         | 0.27%   |
| Silicon Integrated Systems [SiS] | 3         | 0.27%   |
| Realtek Semiconductor            | 3         | 0.27%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.27%   |
| Hewlett-Packard                  | 3         | 0.27%   |
| Promise Technology               | 2         | 0.18%   |
| Apple                            | 2         | 0.18%   |
| Union Memory (Shenzhen)          | 1         | 0.09%   |
| ULi Electronics                  | 1         | 0.09%   |
| Solid State Storage Technology   | 1         | 0.09%   |
| Silicon Image                    | 1         | 0.09%   |
| O2 Micro                         | 1         | 0.09%   |
| Lenovo                           | 1         | 0.09%   |
| INNOGRIT                         | 1         | 0.09%   |
| Hosin Global Electronics         | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 94        | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 54        | 4.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 41        | 3.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 40        | 3.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 31        | 2.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 30        | 2.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 28        | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 27        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 26        | 1.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 26        | 1.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 24        | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 23        | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 22        | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 22        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 20        | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 19        | 1.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 18        | 1.37%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 18        | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 17        | 1.29%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 16        | 1.21%   |
| AMD 500 Series Chipset SATA Controller                                         | 16        | 1.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 15        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 15        | 1.14%   |
| JMicron JMB363 SATA/IDE Controller                                             | 14        | 1.06%   |
| AMD 400 Series Chipset SATA Controller                                         | 14        | 1.06%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 0.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 13        | 0.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 13        | 0.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 13        | 0.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 0.84%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 11        | 0.84%   |
| Intel SATA Controller [RAID mode]                                              | 10        | 0.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 0.76%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 10        | 0.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 9         | 0.68%   |
| Phison E12 NVMe Controller                                                     | 9         | 0.68%   |
| Nvidia MCP61 SATA Controller                                                   | 9         | 0.68%   |
| Nvidia MCP61 IDE                                                               | 9         | 0.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 604       | 53.5%   |
| NVMe | 256       | 22.67%  |
| IDE  | 203       | 17.98%  |
| RAID | 63        | 5.58%   |
| SAS  | 2         | 0.18%   |
| SCSI | 1         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 646       | 71.62%  |
| AMD          | 239       | 26.5%   |
| ARM          | 14        | 1.55%   |
| Qualcomm     | 2         | 0.22%   |
| CentaurHauls | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics  | 10        | 1.1%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 9         | 0.99%   |
| ARM Processor                           | 9         | 0.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 7         | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 7         | 0.77%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 7         | 0.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 7         | 0.77%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 7         | 0.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 7         | 0.77%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 6         | 0.66%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 6         | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 6         | 0.66%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 6         | 0.66%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz   | 6         | 0.66%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 6         | 0.66%   |
| AMD Custom APU 0405                     | 6         | 0.66%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 5         | 0.55%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 5         | 0.55%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 5         | 0.55%   |
| Intel Core i3-5010U CPU @ 2.10GHz       | 5         | 0.55%   |
| Intel Core i3 CPU M 350 @ 2.27GHz       | 5         | 0.55%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 5         | 0.55%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 5         | 0.55%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz  | 4         | 0.44%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 4         | 0.44%   |
| Intel Pentium CPU B960 @ 2.20GHz        | 4         | 0.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 0.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 0.44%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 4         | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 4         | 0.44%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 4         | 0.44%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 4         | 0.44%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 4         | 0.44%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 4         | 0.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 4         | 0.44%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 4         | 0.44%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 4         | 0.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 4         | 0.44%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz    | 4         | 0.44%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 4         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 165       | 18.19%  |
| Intel Core i7           | 113       | 12.46%  |
| Intel Core i3           | 80        | 8.82%   |
| Other                   | 63        | 6.95%   |
| Intel Core 2 Duo        | 56        | 6.17%   |
| Intel Celeron           | 48        | 5.29%   |
| AMD Ryzen 5             | 47        | 5.18%   |
| Intel Pentium           | 39        | 4.3%    |
| AMD Ryzen 7             | 35        | 3.86%   |
| Intel Xeon              | 20        | 2.21%   |
| Intel Core 2 Quad       | 18        | 1.98%   |
| Intel Atom              | 17        | 1.87%   |
| AMD Ryzen 9             | 15        | 1.65%   |
| Intel Pentium Dual-Core | 11        | 1.21%   |
| Intel Pentium Dual      | 11        | 1.21%   |
| AMD Athlon 64 X2        | 11        | 1.21%   |
| AMD Ryzen 3             | 10        | 1.1%    |
| AMD A8                  | 9         | 0.99%   |
| AMD FX                  | 8         | 0.88%   |
| AMD E                   | 7         | 0.77%   |
| AMD Athlon II X2        | 7         | 0.77%   |
| AMD A6                  | 7         | 0.77%   |
| AMD A10                 | 7         | 0.77%   |
| Intel Core 2            | 6         | 0.66%   |
| AMD Sempron             | 6         | 0.66%   |
| Intel Genuine           | 5         | 0.55%   |
| Intel Celeron M         | 5         | 0.55%   |
| Intel Celeron Dual-Core | 5         | 0.55%   |
| AMD Ryzen 5 PRO         | 5         | 0.55%   |
| AMD Phenom II X4        | 5         | 0.55%   |
| AMD Athlon              | 5         | 0.55%   |
| AMD A4                  | 5         | 0.55%   |
| ARM BCM                 | 4         | 0.44%   |
| AMD Ryzen 7 PRO         | 4         | 0.44%   |
| AMD Phenom              | 4         | 0.44%   |
| AMD Athlon X4           | 4         | 0.44%   |
| AMD Athlon 64           | 4         | 0.44%   |
| Intel Pentium 4         | 3         | 0.33%   |
| Intel Pentium M         | 2         | 0.22%   |
| ARM Allwinner           | 2         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 398       | 43.88%  |
| 4       | 310       | 34.18%  |
| 6       | 70        | 7.72%   |
| 8       | 51        | 5.62%   |
| 1       | 42        | 4.63%   |
| 12      | 9         | 0.99%   |
| 16      | 8         | 0.88%   |
| Unknown | 5         | 0.55%   |
| 10      | 4         | 0.44%   |
| 3       | 4         | 0.44%   |
| 20      | 2         | 0.22%   |
| 14      | 2         | 0.22%   |
| 32      | 1         | 0.11%   |
| 24      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 893       | 99%     |
| 2       | 6         | 0.67%   |
| Unknown | 2         | 0.22%   |
| 8       | 1         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 498       | 55.09%  |
| 1       | 399       | 44.14%  |
| Unknown | 5         | 0.55%   |
| 12      | 1         | 0.11%   |
| 4       | 1         | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 875       | 96.47%  |
| Unknown        | 17        | 1.87%   |
| 32-bit         | 13        | 1.43%   |
| 64-bit         | 2         | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 271       | 28.71%  |
| 0x306a9    | 65        | 6.89%   |
| 0x206a7    | 45        | 4.77%   |
| 0x1067a    | 43        | 4.56%   |
| 0x306c3    | 35        | 3.71%   |
| 0x6fb      | 19        | 2.01%   |
| 0x506e3    | 18        | 1.91%   |
| 0x6fd      | 17        | 1.8%    |
| 0x806ea    | 16        | 1.69%   |
| 0x906ea    | 14        | 1.48%   |
| 0x20655    | 14        | 1.48%   |
| 0x906e9    | 13        | 1.38%   |
| 0x806e9    | 13        | 1.38%   |
| 0x806c1    | 12        | 1.27%   |
| 0x10676    | 12        | 1.27%   |
| 0x806ec    | 11        | 1.17%   |
| 0x406e3    | 11        | 1.17%   |
| 0x0a50000c | 11        | 1.17%   |
| 0x06001119 | 10        | 1.06%   |
| 0x010000c8 | 10        | 1.06%   |
| 0x40651    | 9         | 0.95%   |
| 0x20652    | 9         | 0.95%   |
| 0x08608103 | 9         | 0.95%   |
| 0x706a1    | 8         | 0.85%   |
| 0x08108109 | 8         | 0.85%   |
| 0x706e5    | 7         | 0.74%   |
| 0x306d4    | 7         | 0.74%   |
| 0x30678    | 7         | 0.74%   |
| 0x0a50000d | 7         | 0.74%   |
| 0x6f2      | 6         | 0.64%   |
| 0x406c3    | 6         | 0.64%   |
| 0x08600106 | 6         | 0.64%   |
| 0x06006705 | 6         | 0.64%   |
| 0x08701021 | 5         | 0.53%   |
| 0x08108102 | 5         | 0.53%   |
| 0x0800820d | 5         | 0.53%   |
| 0x906ed    | 4         | 0.42%   |
| 0x906eb    | 4         | 0.42%   |
| 0x6d8      | 4         | 0.42%   |
| 0x506c9    | 4         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 105       | 11.62%  |
| IvyBridge        | 81        | 8.96%   |
| Penryn           | 65        | 7.19%   |
| Haswell          | 64        | 7.08%   |
| Unknown          | 64        | 7.08%   |
| SandyBridge      | 57        | 6.31%   |
| Core             | 55        | 6.08%   |
| Skylake          | 41        | 4.54%   |
| Zen 3            | 32        | 3.54%   |
| Westmere         | 30        | 3.32%   |
| Zen 2            | 29        | 3.21%   |
| K10              | 29        | 3.21%   |
| K8 Hammer        | 27        | 2.99%   |
| Silvermont       | 23        | 2.54%   |
| Zen+             | 21        | 2.32%   |
| TigerLake        | 20        | 2.21%   |
| Piledriver       | 18        | 1.99%   |
| Goldmont plus    | 13        | 1.44%   |
| Broadwell        | 13        | 1.44%   |
| Excavator        | 12        | 1.33%   |
| P6               | 10        | 1.11%   |
| Bonnell          | 10        | 1.11%   |
| Zen              | 9         | 1%      |
| IceLake          | 9         | 1%      |
| CometLake        | 8         | 0.88%   |
| Alderlake Hybrid | 8         | 0.88%   |
| Nehalem          | 7         | 0.77%   |
| Bobcat           | 7         | 0.77%   |
| Steamroller      | 6         | 0.66%   |
| Goldmont         | 6         | 0.66%   |
| Puma             | 4         | 0.44%   |
| NetBurst         | 4         | 0.44%   |
| Tremont          | 3         | 0.33%   |
| K8 & K10 hybrid  | 3         | 0.33%   |
| K10 Llano        | 3         | 0.33%   |
| Jaguar           | 3         | 0.33%   |
| Bulldozer        | 3         | 0.33%   |
| K6               | 1         | 0.11%   |
| Gracemont        | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 486       | 46.11%  |
| Nvidia                                       | 278       | 26.38%  |
| AMD                                          | 276       | 26.19%  |
| Matrox Electronics Systems                   | 7         | 0.66%   |
| VIA Technologies                             | 2         | 0.19%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.19%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.09%   |
| S3 Graphics                                  | 1         | 0.09%   |
| ASPEED Technology                            | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 48        | 4.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 47        | 4.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 1.98%   |
| Intel UHD Graphics 620                                                                   | 20        | 1.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 1.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 1.71%   |
| Intel HD Graphics 530                                                                    | 18        | 1.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 1.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 16        | 1.44%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 16        | 1.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.35%   |
| AMD Lucienne                                                                             | 15        | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.26%   |
| Intel HD Graphics 620                                                                    | 14        | 1.26%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 13        | 1.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 1.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 13        | 1.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 0.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 0.9%    |
| Intel HD Graphics 5500                                                                   | 10        | 0.9%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 0.81%   |
| Intel HD Graphics 630                                                                    | 9         | 0.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.81%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 9         | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 0.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 0.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 7         | 0.63%   |
| Intel Iris Plus Graphics G7                                                              | 7         | 0.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 0.63%   |
| AMD RS780L [Radeon 3000]                                                                 | 7         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 352       | 38.34%  |
| 1 x AMD         | 205       | 22.33%  |
| 1 x Nvidia      | 148       | 16.12%  |
| Intel + Nvidia  | 104       | 11.33%  |
| 2 x AMD         | 26        | 2.83%   |
| Intel + AMD     | 23        | 2.51%   |
| AMD + Nvidia    | 21        | 2.29%   |
| Other           | 16        | 1.74%   |
| 2 x Intel       | 5         | 0.54%   |
| 1 x Matrox      | 5         | 0.54%   |
| 2 x Nvidia      | 2         | 0.22%   |
| 1 x VIA         | 2         | 0.22%   |
| 1 x SiS         | 2         | 0.22%   |
| AMD + Matrox    | 2         | 0.22%   |
| 3 x AMD         | 1         | 0.11%   |
| 1 x S3 Graphics | 1         | 0.11%   |
| Nvidia + XGI    | 1         | 0.11%   |
| Nvidia + Matrox | 1         | 0.11%   |
| 1 x ASPEED      | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 752       | 81.56%  |
| Proprietary | 116       | 12.58%  |
| Unknown     | 54        | 5.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 480       | 51.01%  |
| 0.01-0.5   | 161       | 17.11%  |
| 1.01-2.0   | 116       | 12.33%  |
| 0.51-1.0   | 91        | 9.67%   |
| 3.01-4.0   | 45        | 4.78%   |
| 7.01-8.0   | 21        | 2.23%   |
| 5.01-6.0   | 12        | 1.28%   |
| 2.01-3.0   | 7         | 0.74%   |
| 8.01-16.0  | 6         | 0.64%   |
| 16.01-24.0 | 2         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 134       | 13.58%  |
| AU Optronics            | 106       | 10.74%  |
| LG Display              | 85        | 8.61%   |
| Chimei Innolux          | 71        | 7.19%   |
| BOE                     | 70        | 7.09%   |
| Dell                    | 53        | 5.37%   |
| Philips                 | 45        | 4.56%   |
| Goldstar                | 45        | 4.56%   |
| Hewlett-Packard         | 41        | 4.15%   |
| Chi Mei Optoelectronics | 33        | 3.34%   |
| BenQ                    | 32        | 3.24%   |
| Lenovo                  | 28        | 2.84%   |
| Acer                    | 22        | 2.23%   |
| Ancor Communications    | 21        | 2.13%   |
| AOC                     | 20        | 2.03%   |
| Sharp                   | 17        | 1.72%   |
| PANDA                   | 12        | 1.22%   |
| Apple                   | 12        | 1.22%   |
| NEC Computers           | 11        | 1.11%   |
| Iiyama                  | 10        | 1.01%   |
| Fujitsu Siemens         | 9         | 0.91%   |
| LG Philips              | 7         | 0.71%   |
| Eizo                    | 7         | 0.71%   |
| CSO                     | 6         | 0.61%   |
| ASUSTek Computer        | 6         | 0.61%   |
| Valve                   | 5         | 0.51%   |
| TMX                     | 5         | 0.51%   |
| Sony                    | 5         | 0.51%   |
| LG Electronics          | 5         | 0.51%   |
| Unknown                 | 4         | 0.41%   |
| InfoVision              | 4         | 0.41%   |
| HannStar                | 3         | 0.3%    |
| CVT                     | 3         | 0.3%    |
| Toshiba                 | 2         | 0.2%    |
| RTD                     | 2         | 0.2%    |
| QCM                     | 2         | 0.2%    |
| Panasonic               | 2         | 0.2%    |
| MSI                     | 2         | 0.2%    |
| MiTAC                   | 2         | 0.2%    |
| JDI                     | 2         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 8         | 0.78%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 7         | 0.69%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 7         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.69%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 6         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 6         | 0.59%   |
| NEC Computers LCD19WV NEC671C 1440x900 410x256mm 19.0-inch               | 5         | 0.49%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.49%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 4         | 0.39%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 4         | 0.39%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch    | 4         | 0.39%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 4         | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.39%   |
| Goldstar W2753VC GSM5765 1920x1080 598x336mm 27.0-inch                   | 4         | 0.39%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 4         | 0.39%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch        | 3         | 0.29%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch        | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch     | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 3         | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 3         | 0.29%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 3         | 0.29%   |
| Hewlett-Packard E243d HPN3511 1920x1080 527x296mm 23.8-inch              | 3         | 0.29%   |
| CVT CVTE TV CVT0003 1360x768 575x323mm 26.0-inch                         | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 3         | 0.29%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 3         | 0.29%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                    | 3         | 0.29%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 3         | 0.29%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                    | 3         | 0.29%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 3         | 0.29%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 3         | 0.29%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.29%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 381       | 40.62%  |
| 1366x768 (WXGA)    | 171       | 18.23%  |
| 2560x1440 (QHD)    | 45        | 4.8%    |
| 3840x2160 (4K)     | 40        | 4.26%   |
| 1280x800 (WXGA)    | 40        | 4.26%   |
| 1920x1200 (WUXGA)  | 38        | 4.05%   |
| 1600x900 (HD+)     | 38        | 4.05%   |
| 1280x1024 (SXGA)   | 37        | 3.94%   |
| 1680x1050 (WSXGA+) | 34        | 3.62%   |
| 1440x900 (WXGA+)   | 32        | 3.41%   |
| 1600x1200          | 9         | 0.96%   |
| 3440x1440          | 8         | 0.85%   |
| 1360x768           | 8         | 0.85%   |
| 1024x600           | 6         | 0.64%   |
| 2560x1600          | 5         | 0.53%   |
| 800x1280           | 4         | 0.43%   |
| 2880x1800          | 4         | 0.43%   |
| 1280x720 (HD)      | 4         | 0.43%   |
| 3840x2400          | 3         | 0.32%   |
| 3200x2000          | 3         | 0.32%   |
| 2160x1440          | 3         | 0.32%   |
| 1920x540           | 3         | 0.32%   |
| 1024x768 (XGA)     | 3         | 0.32%   |
| 2800x1752          | 2         | 0.21%   |
| 2560x1080          | 2         | 0.21%   |
| 2160x1350          | 2         | 0.21%   |
| 1920x1280          | 2         | 0.21%   |
| Unknown            | 2         | 0.21%   |
| 3200x1800 (QHD+)   | 1         | 0.11%   |
| 3200x1080          | 1         | 0.11%   |
| 3072x1920          | 1         | 0.11%   |
| 3000x2000          | 1         | 0.11%   |
| 2880x1620          | 1         | 0.11%   |
| 2256x1504          | 1         | 0.11%   |
| 1680x945           | 1         | 0.11%   |
| 1400x1050          | 1         | 0.11%   |
| 1280x960           | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 272       | 27.31%  |
| 24      | 102       | 10.24%  |
| 13      | 79        | 7.93%   |
| 14      | 64        | 6.43%   |
| 23      | 63        | 6.33%   |
| 21      | 57        | 5.72%   |
| 27      | 53        | 5.32%   |
| 17      | 48        | 4.82%   |
| 19      | 35        | 3.51%   |
| Unknown | 34        | 3.41%   |
| 18      | 23        | 2.31%   |
| 22      | 20        | 2.01%   |
| 12      | 19        | 1.91%   |
| 20      | 16        | 1.61%   |
| 11      | 14        | 1.41%   |
| 31      | 11        | 1.1%    |
| 25      | 11        | 1.1%    |
| 34      | 9         | 0.9%    |
| 16      | 9         | 0.9%    |
| 10      | 6         | 0.6%    |
| 84      | 5         | 0.5%    |
| 32      | 5         | 0.5%    |
| 26      | 5         | 0.5%    |
| 72      | 4         | 0.4%    |
| 46      | 4         | 0.4%    |
| 7       | 4         | 0.4%    |
| 54      | 3         | 0.3%    |
| 40      | 3         | 0.3%    |
| 39      | 3         | 0.3%    |
| 67      | 2         | 0.2%    |
| 65      | 2         | 0.2%    |
| 48      | 2         | 0.2%    |
| 37      | 2         | 0.2%    |
| 86      | 1         | 0.1%    |
| 75      | 1         | 0.1%    |
| 58      | 1         | 0.1%    |
| 50      | 1         | 0.1%    |
| 42      | 1         | 0.1%    |
| 35      | 1         | 0.1%    |
| 33      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 390       | 40%     |
| 501-600     | 207       | 21.23%  |
| 401-500     | 136       | 13.95%  |
| 201-300     | 84        | 8.62%   |
| 351-400     | 54        | 5.54%   |
| Unknown     | 34        | 3.49%   |
| 701-800     | 17        | 1.74%   |
| 601-700     | 15        | 1.54%   |
| 1001-1500   | 14        | 1.44%   |
| 1501-2000   | 10        | 1.03%   |
| 801-900     | 9         | 0.92%   |
| 1-100       | 4         | 0.41%   |
| 901-1000    | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 630       | 69.77%  |
| 16/10   | 164       | 18.16%  |
| 5/4     | 35        | 3.88%   |
| Unknown | 26        | 2.88%   |
| 4/3     | 15        | 1.66%   |
| 3/2     | 14        | 1.55%   |
| 21/9    | 10        | 1.11%   |
| 0.67    | 4         | 0.44%   |
| 0.45    | 2         | 0.22%   |
| 6/5     | 1         | 0.11%   |
| 32/9    | 1         | 0.11%   |
| 0.56    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 269       | 27.28%  |
| 201-250        | 188       | 19.07%  |
| 81-90          | 105       | 10.65%  |
| 151-200        | 65        | 6.59%   |
| 301-350        | 53        | 5.38%   |
| 251-300        | 49        | 4.97%   |
| 141-150        | 42        | 4.26%   |
| 71-80          | 37        | 3.75%   |
| Unknown        | 34        | 3.45%   |
| 351-500        | 27        | 2.74%   |
| More than 1000 | 21        | 2.13%   |
| 121-130        | 21        | 2.13%   |
| 61-70          | 18        | 1.83%   |
| 51-60          | 14        | 1.42%   |
| 501-1000       | 13        | 1.32%   |
| 111-120        | 9         | 0.91%   |
| 131-140        | 8         | 0.81%   |
| 41-50          | 6         | 0.61%   |
| 1-40           | 4         | 0.41%   |
| 91-100         | 3         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 373       | 39.22%  |
| 121-160       | 234       | 24.61%  |
| 101-120       | 223       | 23.45%  |
| 161-240       | 47        | 4.94%   |
| Unknown       | 34        | 3.58%   |
| More than 240 | 21        | 2.21%   |
| 1-50          | 19        | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 722       | 78.05%  |
| 2     | 143       | 15.46%  |
| 0     | 47        | 5.08%   |
| 3     | 13        | 1.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 480       | 35.9%   |
| Intel                                  | 370       | 27.67%  |
| Qualcomm Atheros                       | 173       | 12.94%  |
| Broadcom                               | 81        | 6.06%   |
| Marvell Technology Group               | 23        | 1.72%   |
| Ralink Technology                      | 22        | 1.65%   |
| TP-Link                                | 21        | 1.57%   |
| Nvidia                                 | 19        | 1.42%   |
| Broadcom Limited                       | 18        | 1.35%   |
| Ralink                                 | 16        | 1.2%    |
| MediaTek                               | 15        | 1.12%   |
| Qualcomm Atheros Communications        | 12        | 0.9%    |
| Dell                                   | 8         | 0.6%    |
| ASIX Electronics                       | 7         | 0.52%   |
| Xiaomi                                 | 5         | 0.37%   |
| Hewlett-Packard                        | 5         | 0.37%   |
| Sierra Wireless                        | 4         | 0.3%    |
| Samsung Electronics                    | 4         | 0.3%    |
| ASUSTek Computer                       | 4         | 0.3%    |
| Lenovo                                 | 3         | 0.22%   |
| JMicron Technology                     | 3         | 0.22%   |
| Huawei Technologies                    | 3         | 0.22%   |
| FIBOCOM                                | 3         | 0.22%   |
| Ericsson Business Mobile Networks      | 3         | 0.22%   |
| DisplayLink                            | 3         | 0.22%   |
| D-Link                                 | 3         | 0.22%   |
| VIA Technologies                       | 2         | 0.15%   |
| Edimax Technology                      | 2         | 0.15%   |
| ZyXEL Communications                   | 1         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.07%   |
| WiseGroup                              | 1         | 0.07%   |
| ULi Electronics                        | 1         | 0.07%   |
| Texas Instruments                      | 1         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.07%   |
| Spreadtrum Communications              | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.07%   |
| Sigma Sport                            | 1         | 0.07%   |
| Raspberry Pi                           | 1         | 0.07%   |
| Qualcomm                               | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 323       | 20.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 52        | 3.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 40        | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 31        | 2.01%   |
| Intel Wireless 8265 / 8275                                              | 29        | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 28        | 1.81%   |
| Intel Wi-Fi 6 AX200                                                     | 23        | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 20        | 1.29%   |
| Realtek RTL8125 2.5GbE Controller                                       | 19        | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 17        | 1.1%    |
| Intel Wireless 8260                                                     | 17        | 1.1%    |
| Intel Wi-Fi 6 AX201                                                     | 17        | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 0.84%   |
| Qualcomm Atheros AR9271 802.11n                                         | 12        | 0.78%   |
| Intel Wireless 7260                                                     | 12        | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 0.71%   |
| Intel Wireless 7265                                                     | 11        | 0.71%   |
| Intel Wireless 3165                                                     | 11        | 0.71%   |
| Intel I211 Gigabit Network Connection                                   | 11        | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 0.71%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 10        | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 9         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 9         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.58%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 0.58%   |
| Intel Ethernet Connection I217-LM                                       | 9         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                                    | 9         | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 0.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 8         | 0.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 8         | 0.52%   |
| Ralink MT7601U Wireless Adapter                                         | 8         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 8         | 0.52%   |
| Intel WiFi Link 5100                                                    | 8         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 282       | 41.41%  |
| Qualcomm Atheros                | 133       | 19.53%  |
| Realtek Semiconductor           | 94        | 13.8%   |
| Broadcom                        | 45        | 6.61%   |
| Ralink Technology               | 22        | 3.23%   |
| TP-Link                         | 21        | 3.08%   |
| Ralink                          | 16        | 2.35%   |
| MediaTek                        | 15        | 2.2%    |
| Qualcomm Atheros Communications | 12        | 1.76%   |
| Broadcom Limited                | 12        | 1.76%   |
| Dell                            | 6         | 0.88%   |
| Sierra Wireless                 | 4         | 0.59%   |
| ASUSTek Computer                | 4         | 0.59%   |
| FIBOCOM                         | 3         | 0.44%   |
| D-Link                          | 3         | 0.44%   |
| Edimax Technology               | 2         | 0.29%   |
| ZyXEL Communications            | 1         | 0.15%   |
| Texas Instruments               | 1         | 0.15%   |
| Qualcomm                        | 1         | 0.15%   |
| Microsoft                       | 1         | 0.15%   |
| Micro Star International        | 1         | 0.15%   |
| Accton Technology               | 1         | 0.15%   |
| Unknown                         | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 40        | 5.83%   |
| Intel Wireless 8265 / 8275                                              | 29        | 4.23%   |
| Intel Wi-Fi 6 AX200                                                     | 23        | 3.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 2.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 2.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 17        | 2.48%   |
| Intel Wireless 8260                                                     | 17        | 2.48%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 2.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 1.9%    |
| Qualcomm Atheros AR9271 802.11n                                         | 12        | 1.75%   |
| Intel Wireless 7260                                                     | 12        | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 1.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 1.6%    |
| Intel Wireless 7265                                                     | 11        | 1.6%    |
| Intel Wireless 3165                                                     | 11        | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 1.46%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 9         | 1.31%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.31%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 1.31%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 1.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 1.31%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 8         | 1.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 8         | 1.17%   |
| Ralink MT7601U Wireless Adapter                                         | 8         | 1.17%   |
| Intel WiFi Link 5100                                                    | 8         | 1.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.17%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 1.17%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 7         | 1.02%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 7         | 1.02%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 7         | 1.02%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.87%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 0.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 442       | 54.1%   |
| Intel                                  | 192       | 23.5%   |
| Qualcomm Atheros                       | 56        | 6.85%   |
| Broadcom                               | 38        | 4.65%   |
| Marvell Technology Group               | 23        | 2.82%   |
| Nvidia                                 | 19        | 2.33%   |
| ASIX Electronics                       | 7         | 0.86%   |
| Broadcom Limited                       | 6         | 0.73%   |
| Xiaomi                                 | 5         | 0.61%   |
| Samsung Electronics                    | 4         | 0.49%   |
| Lenovo                                 | 3         | 0.37%   |
| JMicron Technology                     | 3         | 0.37%   |
| DisplayLink                            | 3         | 0.37%   |
| VIA Technologies                       | 2         | 0.24%   |
| Huawei Technologies                    | 2         | 0.24%   |
| T & A Mobile Phones                    | 1         | 0.12%   |
| Spreadtrum Communications              | 1         | 0.12%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.12%   |
| Raspberry Pi                           | 1         | 0.12%   |
| QinHeng Electronics                    | 1         | 0.12%   |
| Prestigio                              | 1         | 0.12%   |
| Nokia Mobile Phones                    | 1         | 0.12%   |
| National Semiconductor                 | 1         | 0.12%   |
| Mellanox Technologies                  | 1         | 0.12%   |
| ICS Advent                             | 1         | 0.12%   |
| Google                                 | 1         | 0.12%   |
| Attansic Technology                    | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 323       | 38.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 52        | 6.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 31        | 3.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 28        | 3.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 20        | 2.38%   |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 2.26%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 1.31%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 10        | 1.19%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 1.07%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 1.07%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 7         | 0.83%   |
| Nvidia MCP61 Ethernet                                                  | 7         | 0.83%   |
| Intel Ethernet Controller I225-V                                       | 7         | 0.83%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 0.83%   |
| Intel 82579V Gigabit Network Connection                                | 7         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                               | 7         | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                                   | 6         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 5         | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 5         | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 5         | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 5         | 0.6%    |
| Intel Ethernet Connection I218-LM                                      | 5         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 0.6%    |
| Intel 82566DM-2 Gigabit Network Connection                             | 5         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 4         | 0.48%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 4         | 0.48%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4         | 0.48%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 4         | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 4         | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 775       | 53.67%  |
| WiFi     | 649       | 44.94%  |
| Modem    | 19        | 1.32%   |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 500       | 54.53%  |
| Ethernet | 417       | 45.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 481       | 52.92%  |
| 1     | 377       | 41.47%  |
| 0     | 32        | 3.52%   |
| 3     | 11        | 1.21%   |
| 4     | 7         | 0.77%   |
| 5     | 1         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 847       | 93.38%  |
| Yes  | 60        | 6.62%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 202       | 40.81%  |
| Realtek Semiconductor           | 47        | 9.49%   |
| Qualcomm Atheros Communications | 38        | 7.68%   |
| IMC Networks                    | 37        | 7.47%   |
| Broadcom                        | 29        | 5.86%   |
| Lite-On Technology              | 23        | 4.65%   |
| Cambridge Silicon Radio         | 20        | 4.04%   |
| Foxconn / Hon Hai               | 19        | 3.84%   |
| ASUSTek Computer                | 15        | 3.03%   |
| Ralink                          | 9         | 1.82%   |
| Hewlett-Packard                 | 9         | 1.82%   |
| Dell                            | 9         | 1.82%   |
| Apple                           | 9         | 1.82%   |
| Toshiba                         | 6         | 1.21%   |
| Micro Star International        | 4         | 0.81%   |
| Realtek                         | 3         | 0.61%   |
| Foxconn International           | 3         | 0.61%   |
| Taiyo Yuden                     | 2         | 0.4%    |
| HTC (High Tech Computer)        | 2         | 0.4%    |
| USI                             | 1         | 0.2%    |
| TP-Link                         | 1         | 0.2%    |
| Ralink Technology               | 1         | 0.2%    |
| MediaTek                        | 1         | 0.2%    |
| Integrated System Solution      | 1         | 0.2%    |
| Fujitsu                         | 1         | 0.2%    |
| Edimax Technology               | 1         | 0.2%    |
| Belkin Components               | 1         | 0.2%    |
| Alps Electric                   | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 43        | 8.69%   |
| Intel AX201 Bluetooth                               | 40        | 8.08%   |
| Intel Bluetooth Device                              | 37        | 7.47%   |
| Realtek Bluetooth Radio                             | 33        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 24        | 4.85%   |
| Intel AX200 Bluetooth                               | 23        | 4.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20        | 4.04%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 3.64%   |
| IMC Networks Bluetooth Radio                        | 15        | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 11        | 2.22%   |
| Ralink RT3290 Bluetooth                             | 9         | 1.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 1.82%   |
| IMC Networks Bluetooth Device                       | 9         | 1.82%   |
| Intel AX210 Bluetooth                               | 8         | 1.62%   |
| Lite-On Bluetooth Device                            | 7         | 1.41%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 7         | 1.41%   |
| Realtek RTL8821A Bluetooth                          | 6         | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.21%   |
| Intel AX211 Bluetooth                               | 6         | 1.21%   |
| Broadcom HP Portable SoftSailing                    | 6         | 1.21%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 6         | 1.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 1.01%   |
| IMC Networks Wireless_Device                        | 5         | 1.01%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 1.01%   |
| Lite-On Wireless_Device                             | 4         | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.81%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.81%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.81%   |
| Realtek Bluetooth Radio                             | 3         | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.61%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 0.61%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.61%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 3         | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.61%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 3         | 0.61%   |
| Dell Wireless 370 Bluetooth Mini-card               | 3         | 0.61%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 614       | 51.64%  |
| AMD                                          | 277       | 23.3%   |
| Nvidia                                       | 191       | 16.06%  |
| C-Media Electronics                          | 22        | 1.85%   |
| Creative Labs                                | 9         | 0.76%   |
| GN Netcom                                    | 8         | 0.67%   |
| Creative Technology                          | 8         | 0.67%   |
| VIA Technologies                             | 6         | 0.5%    |
| Lenovo                                       | 6         | 0.5%    |
| Realtek Semiconductor                        | 4         | 0.34%   |
| JMTek                                        | 4         | 0.34%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.25%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.25%   |
| Logitech                                     | 3         | 0.25%   |
| ASUSTek Computer                             | 3         | 0.25%   |
| Yamaha                                       | 2         | 0.17%   |
| Texas Instruments                            | 2         | 0.17%   |
| Samson Technologies                          | 2         | 0.17%   |
| Focusrite-Novation                           | 2         | 0.17%   |
| Blue Microphones                             | 2         | 0.17%   |
| AKAI Professional M.I.                       | 2         | 0.17%   |
| Valve Software                               | 1         | 0.08%   |
| ULi Electronics                              | 1         | 0.08%   |
| Trust                                        | 1         | 0.08%   |
| Textech International                        | 1         | 0.08%   |
| SteelSeries ApS                              | 1         | 0.08%   |
| Plantronics                                  | 1         | 0.08%   |
| Nordic Semiconductor ASA                     | 1         | 0.08%   |
| Micro Star International                     | 1         | 0.08%   |
| Kingston Technology                          | 1         | 0.08%   |
| Hewlett-Packard                              | 1         | 0.08%   |
| Fortemedia                                   | 1         | 0.08%   |
| DCMT Technology                              | 1         | 0.08%   |
| Behringer.......                             | 1         | 0.08%   |
| Barco Display Systems                        | 1         | 0.08%   |
| Apple                                        | 1         | 0.08%   |
| A4Tech                                       | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 79        | 5.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 78        | 5.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 52        | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 52        | 3.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 51        | 3.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 46        | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 44        | 3.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 43        | 3.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 39        | 2.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 32        | 2.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 32        | 2.26%   |
| AMD FCH Azalia Controller                                                  | 30        | 2.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 25        | 1.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 25        | 1.77%   |
| Intel Cannon Lake PCH cAVS                                                 | 24        | 1.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 22        | 1.56%   |
| AMD Starship/Matisse HD Audio Controller                                   | 21        | 1.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 20        | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                              | 18        | 1.27%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 18        | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 17        | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 14        | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 14        | 0.99%   |
| Intel 200 Series PCH HD Audio                                              | 14        | 0.99%   |
| Nvidia High Definition Audio Controller                                    | 13        | 0.92%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 13        | 0.92%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 0.85%   |
| Intel Broadwell-U Audio Controller                                         | 12        | 0.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 0.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11        | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 11        | 0.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 11        | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 10        | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10        | 0.71%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 10        | 0.71%   |
| Nvidia MCP61 High Definition Audio                                         | 9         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9         | 0.64%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 111       | 18.78%  |
| SK hynix            | 107       | 18.1%   |
| Samsung Electronics | 104       | 17.6%   |
| Unknown             | 92        | 15.57%  |
| Micron Technology   | 51        | 8.63%   |
| Crucial             | 28        | 4.74%   |
| Corsair             | 15        | 2.54%   |
| Elpida              | 14        | 2.37%   |
| Patriot             | 11        | 1.86%   |
| Ramaxel Technology  | 10        | 1.69%   |
| G.Skill             | 7         | 1.18%   |
| A-DATA Technology   | 7         | 1.18%   |
| Unknown             | 7         | 1.18%   |
| Unknown (ABCD)      | 6         | 1.02%   |
| Nanya Technology    | 5         | 0.85%   |
| Apacer              | 3         | 0.51%   |
| Transcend           | 2         | 0.34%   |
| Hewlett-Packard     | 2         | 0.34%   |
| ASint Technology    | 2         | 0.34%   |
| Unknown (8AC8)      | 1         | 0.17%   |
| Unknown (130B)      | 1         | 0.17%   |
| Unigen              | 1         | 0.17%   |
| SHARETRONIC         | 1         | 0.17%   |
| Patriot Memory      | 1         | 0.17%   |
| Atermiter           | 1         | 0.17%   |
| 48spaces            | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.06%   |
| Unknown                                                          | 7         | 1.06%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 6         | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 0.91%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.91%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.91%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 5         | 0.76%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.76%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.76%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.76%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 5         | 0.76%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s           | 5         | 0.76%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.61%   |
| Micron RAM MT8KTF51264HZ-1G6 4GB SODIMM DDR3 1600MT/s            | 4         | 0.61%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s              | 4         | 0.61%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s             | 4         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.45%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 3         | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                      | 3         | 0.45%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 3         | 0.45%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.45%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.45%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.45%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 3         | 0.45%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.45%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s              | 3         | 0.45%   |
| Patriot RAM PSD34G16002S 4GB SODIMM DDR3 1600MT/s                | 3         | 0.45%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 3         | 0.45%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 3         | 0.45%   |
| Kingston RAM KHX1866C11S3L/8G 8GB SODIMM DDR3 1867MT/s           | 3         | 0.45%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 3         | 0.45%   |
| Kingston RAM 99U5584-001.A00LF 4096MB DIMM DDR3 1600MT/s         | 3         | 0.45%   |
| Kingston RAM 9905624-033.A00G 8GB SODIMM DDR4 2400MT/s           | 3         | 0.45%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 3         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 177       | 35.26%  |
| DDR3    | 172       | 34.26%  |
| DDR2    | 50        | 9.96%   |
| SDRAM   | 27        | 5.38%   |
| Unknown | 26        | 5.18%   |
| LPDDR4  | 20        | 3.98%   |
| DDR5    | 8         | 1.59%   |
| DDR     | 8         | 1.59%   |
| LPDDR5  | 6         | 1.2%    |
| LPDDR3  | 6         | 1.2%    |
| DRAM    | 2         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 292       | 58.4%   |
| DIMM         | 170       | 34%     |
| Row Of Chips | 32        | 6.4%    |
| Chip         | 4         | 0.8%    |
| FB-DIMM      | 1         | 0.2%    |
| Unknown      | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 178       | 30.96%  |
| 4096  | 147       | 25.57%  |
| 2048  | 114       | 19.83%  |
| 16384 | 64        | 11.13%  |
| 1024  | 44        | 7.65%   |
| 32768 | 14        | 2.43%   |
| 512   | 9         | 1.57%   |
| 256   | 2         | 0.35%   |
| 3072  | 1         | 0.17%   |
| 128   | 1         | 0.17%   |
| 64    | 1         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 115       | 20.46%  |
| 3200    | 69        | 12.28%  |
| 2667    | 53        | 9.43%   |
| 1333    | 33        | 5.87%   |
| 667     | 33        | 5.87%   |
| 2400    | 31        | 5.52%   |
| 800     | 26        | 4.63%   |
| 2133    | 24        | 4.27%   |
| 1334    | 23        | 4.09%   |
| 3600    | 13        | 2.31%   |
| Unknown | 13        | 2.31%   |
| 4199    | 9         | 1.6%    |
| 1867    | 9         | 1.6%    |
| 1067    | 9         | 1.6%    |
| 3733    | 8         | 1.42%   |
| 6400    | 7         | 1.25%   |
| 1866    | 7         | 1.25%   |
| 533     | 7         | 1.25%   |
| 333     | 7         | 1.25%   |
| 4267    | 5         | 0.89%   |
| 4266    | 5         | 0.89%   |
| 2048    | 5         | 0.89%   |
| 4800    | 4         | 0.71%   |
| 3266    | 4         | 0.71%   |
| 400     | 4         | 0.71%   |
| 3800    | 3         | 0.53%   |
| 3466    | 3         | 0.53%   |
| 1800    | 3         | 0.53%   |
| 1066    | 3         | 0.53%   |
| 8400    | 2         | 0.36%   |
| 5600    | 2         | 0.36%   |
| 3933    | 2         | 0.36%   |
| 3000    | 2         | 0.36%   |
| 1639    | 2         | 0.36%   |
| 975     | 2         | 0.36%   |
| 57535   | 1         | 0.18%   |
| 6000    | 1         | 0.18%   |
| 5500    | 1         | 0.18%   |
| 4400    | 1         | 0.18%   |
| 4000    | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 14        | 70%     |
| Samsung Electronics   | 2         | 10%     |
| Star Micronics        | 1         | 5%      |
| Seiko Epson           | 1         | 5%      |
| Lexmark International | 1         | 5%      |
| Canon                 | 1         | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                | 4         | 20%     |
| HP Deskjet 1050 J410                            | 2         | 10%     |
| Star Micronics IP1000 Printer USB001            | 1         | 5%      |
| Seiko Epson L382 Series                         | 1         | 5%      |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 5%      |
| Samsung M2070 Series                            | 1         | 5%      |
| Lexmark International 2600 Series               | 1         | 5%      |
| HP OfficeJet 6950                               | 1         | 5%      |
| HP LaserJet P1006                               | 1         | 5%      |
| HP LaserJet M101-M106                           | 1         | 5%      |
| HP LaserJet CP 1025nw                           | 1         | 5%      |
| HP LaserJet 1150                                | 1         | 5%      |
| HP HP LaserJet M14-M17                          | 1         | 5%      |
| HP DeskJet 2700 series                          | 1         | 5%      |
| HP Deskjet 1510                                 | 1         | 5%      |
| Canon PIXMA MP230                               | 1         | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 60%     |
| Minolta         | 1         | 20%     |
| Hewlett-Packard | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Minolta Dimage Scan Dual III AF-2840 (2889) | 1         | 20%     |
| HP ScanJet 3800c                            | 1         | 20%     |
| Canon CanoScan LiDE 90                      | 1         | 20%     |
| Canon CanoScan LIDE 25                      | 1         | 20%     |
| Canon CanoScan LiDE 110                     | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 138       | 26.95%  |
| IMC Networks                           | 49        | 9.57%   |
| Microdia                               | 48        | 9.38%   |
| Realtek Semiconductor                  | 34        | 6.64%   |
| Syntek                                 | 26        | 5.08%   |
| Sunplus Innovation Technology          | 25        | 4.88%   |
| Bison Electronics                      | 25        | 4.88%   |
| Suyin                                  | 20        | 3.91%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 3.32%   |
| Quanta                                 | 15        | 2.93%   |
| Acer                                   | 15        | 2.93%   |
| Logitech                               | 14        | 2.73%   |
| Lite-On Technology                     | 9         | 1.76%   |
| Microsoft                              | 8         | 1.56%   |
| Apple                                  | 7         | 1.37%   |
| Alcor Micro                            | 6         | 1.17%   |
| GEMBIRD                                | 5         | 0.98%   |
| Z-Star Microelectronics                | 4         | 0.78%   |
| SunplusIT                              | 4         | 0.78%   |
| Sonix Technology                       | 3         | 0.59%   |
| Silicon Motion                         | 3         | 0.59%   |
| Samsung Electronics                    | 3         | 0.59%   |
| Ricoh                                  | 3         | 0.59%   |
| Luxvisions Innotech Limited            | 3         | 0.59%   |
| Creative Technology                    | 3         | 0.59%   |
| MacroSilicon                           | 2         | 0.39%   |
| LG Electronics                         | 2         | 0.39%   |
| Lenovo                                 | 2         | 0.39%   |
| Importek                               | 2         | 0.39%   |
| DigiTech                               | 2         | 0.39%   |
| Valve Software                         | 1         | 0.2%    |
| Unknown                                | 1         | 0.2%    |
| Tripath Technology                     | 1         | 0.2%    |
| Primax Electronics                     | 1         | 0.2%    |
| OnePlus Technology (Shenzhen)          | 1         | 0.2%    |
| OmniVision Technologies                | 1         | 0.2%    |
| KYE Systems (Mouse Systems)            | 1         | 0.2%    |
| icSpring                               | 1         | 0.2%    |
| GenesysLogic Technology                | 1         | 0.2%    |
| Generalplus Technology                 | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 30        | 5.81%   |
| Syntek Integrated Camera                          | 17        | 3.29%   |
| Microdia Integrated_Webcam_HD                     | 17        | 3.29%   |
| IMC Networks Integrated Camera                    | 13        | 2.52%   |
| Chicony HP HD Webcam [Fixed]                      | 10        | 1.94%   |
| Bison Integrated Camera                           | 10        | 1.94%   |
| Realtek Integrated_Webcam_HD                      | 9         | 1.74%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 9         | 1.74%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 9         | 1.74%   |
| Chicony HD WebCam                                 | 9         | 1.74%   |
| Realtek USB2.0 HD UVC WebCam                      | 7         | 1.36%   |
| Quanta HP HD Camera                               | 7         | 1.36%   |
| Sunplus Integrated_Webcam_HD                      | 6         | 1.16%   |
| Microdia Webcam Vitade AF                         | 6         | 1.16%   |
| Suyin Acer/HP Integrated Webcam [CN0314]          | 5         | 0.97%   |
| Microdia Integrated Webcam                        | 5         | 0.97%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 5         | 0.97%   |
| Chicony USB2.0 VGA UVC WebCam                     | 5         | 0.97%   |
| Chicony HP HD Camera                              | 5         | 0.97%   |
| Syntek Lenovo EasyCamera                          | 4         | 0.78%   |
| Suyin HP Webcam                                   | 4         | 0.78%   |
| Sunplus HP HD Webcam [Fixed]                      | 4         | 0.78%   |
| Sunplus HD WebCam                                 | 4         | 0.78%   |
| Lite-On HP HD Camera                              | 4         | 0.78%   |
| IMC Networks Integrated Webcam                    | 4         | 0.78%   |
| Chicony USB 2.0 Camera                            | 4         | 0.78%   |
| Chicony Lenovo EasyCamera                         | 4         | 0.78%   |
| Chicony Integrated Camera (1280x720@30)           | 4         | 0.78%   |
| Chicony HD User Facing                            | 4         | 0.78%   |
| Bison EasyCamera                                  | 4         | 0.78%   |
| Acer Lenovo EasyCamera                            | 4         | 0.78%   |
| SunplusIT XiaoMi USB 2.0 Webcam                   | 3         | 0.58%   |
| Samsung Galaxy series, misc. (MTP mode)           | 3         | 0.58%   |
| Realtek USB Camera                                | 3         | 0.58%   |
| Microdia Sonix USB 2.0 Camera                     | 3         | 0.58%   |
| Microdia Laptop_Integrated_Webcam_2M              | 3         | 0.58%   |
| Microdia Integrated_Webcam_FHD                    | 3         | 0.58%   |
| Lite-On Integrated Camera                         | 3         | 0.58%   |
| IMC Networks 2M Integrated Webcam                 | 3         | 0.58%   |
| Chicony WebCam                                    | 3         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 47        | 40.52%  |
| Synaptics                          | 35        | 30.17%  |
| Shenzhen Goodix Technology         | 11        | 9.48%   |
| AuthenTec                          | 9         | 7.76%   |
| LighTuning Technology              | 5         | 4.31%   |
| Upek                               | 3         | 2.59%   |
| STMicroelectronics                 | 3         | 2.59%   |
| Elan Microelectronics              | 2         | 1.72%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 10.34%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 8.62%   |
| Synaptics WBDI                                                             | 7         | 6.03%   |
| Shenzhen Goodix  Fingerprint Device                                        | 7         | 6.03%   |
| Validity Sensors VFS491                                                    | 6         | 5.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 4.31%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 4.31%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 3.45%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 3.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.59%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 2.59%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 2.59%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.59%   |
| Synaptics  WBDI                                                            | 3         | 2.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 2.59%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 2.59%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.59%   |
| AuthenTec AES2810                                                          | 3         | 2.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.72%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.72%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.72%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 1.72%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 1.72%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.72%   |
| AuthenTec AES1600                                                          | 2         | 1.72%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.86%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.86%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.86%   |
| Synaptics UWP WBDI                                                         | 1         | 0.86%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.86%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.86%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.86%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 21        | 38.89%  |
| Alcor Micro           | 18        | 33.33%  |
| O2 Micro              | 6         | 11.11%  |
| Gemalto (was Gemplus) | 3         | 5.56%   |
| Bit4id                | 3         | 5.56%   |
| Lenovo                | 2         | 3.7%    |
| OmniKey               | 1         | 1.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 33.33%  |
| Broadcom 5880                                                                | 8         | 14.81%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 11.11%  |
| Broadcom 58200                                                               | 5         | 9.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 7.41%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 5.56%   |
| Bit4id miniLector EVO                                                        | 3         | 5.56%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 3.7%    |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.7%    |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 1.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 623       | 67.06%  |
| 1     | 245       | 26.37%  |
| 2     | 48        | 5.17%   |
| 3     | 11        | 1.18%   |
| 4     | 2         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 116       | 31.69%  |
| Graphics card            | 86        | 23.5%   |
| Chipcard                 | 43        | 11.75%  |
| Net/wireless             | 32        | 8.74%   |
| Multimedia controller    | 20        | 5.46%   |
| Bluetooth                | 14        | 3.83%   |
| Communication controller | 11        | 3.01%   |
| Storage                  | 8         | 2.19%   |
| Card reader              | 7         | 1.91%   |
| Sound                    | 6         | 1.64%   |
| Modem                    | 6         | 1.64%   |
| Camera                   | 6         | 1.64%   |
| Unassigned class         | 3         | 0.82%   |
| Network                  | 3         | 0.82%   |
| Net/ethernet             | 2         | 0.55%   |
| Flash memory             | 2         | 0.55%   |
| Storage/ide              | 1         | 0.27%   |

