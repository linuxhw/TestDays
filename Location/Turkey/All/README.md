Linux in Turkey - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Turkey.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Turkey/Desktop/README.md) and [notebooks](/Location/Turkey/Notebook/README.md).

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

Total: 3318

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | GA-770TA-UD3                | Desktop     | [5fad364df3](https://linux-hardware.org/?probe=5fad364df3) | May 09, 2024 |
| Unknown       | MT6785V/CC (DT)             | Soc         | [e3e06b8a94](https://linux-hardware.org/?probe=e3e06b8a94) | May 08, 2024 |
| Lenovo        | 375C No DPK                 | All in one  | [46bbdf2453](https://linux-hardware.org/?probe=46bbdf2453) | May 07, 2024 |
| ASUSTek       | X405UQ                      | Notebook    | [aa39bc4676](https://linux-hardware.org/?probe=aa39bc4676) | May 06, 2024 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | Notebook    | [ae77241a92](https://linux-hardware.org/?probe=ae77241a92) | May 06, 2024 |
| Monster       | ABRA A7 V13.2               | Notebook    | [fef4f4d7d4](https://linux-hardware.org/?probe=fef4f4d7d4) | May 06, 2024 |
| Dell          | 0V8WGR A00                  | Desktop     | [826e11d8af](https://linux-hardware.org/?probe=826e11d8af) | May 05, 2024 |
| Pegatron      | IPXSB-H61                   | Desktop     | [2a449d83d3](https://linux-hardware.org/?probe=2a449d83d3) | May 05, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [ca15c39fa7](https://linux-hardware.org/?probe=ca15c39fa7) | May 05, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [eb9fc84dcf](https://linux-hardware.org/?probe=eb9fc84dcf) | May 05, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [5c3ab00eb7](https://linux-hardware.org/?probe=5c3ab00eb7) | May 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8a0a1ade7b](https://linux-hardware.org/?probe=8a0a1ade7b) | May 04, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f584b00194](https://linux-hardware.org/?probe=f584b00194) | May 02, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6dbbe3a7b2](https://linux-hardware.org/?probe=6dbbe3a7b2) | May 02, 2024 |
| Lenovo        | ThinkPad T470s 20HGS3RJ0... | Notebook    | [dee93d35ca](https://linux-hardware.org/?probe=dee93d35ca) | May 02, 2024 |
| Acer          | Aspire SW5-173              | Notebook    | [e72a0709d4](https://linux-hardware.org/?probe=e72a0709d4) | May 01, 2024 |
| ASUSTek       | H81M-D                      | Desktop     | [9fb933dd16](https://linux-hardware.org/?probe=9fb933dd16) | May 01, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [52327486f3](https://linux-hardware.org/?probe=52327486f3) | Apr 30, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [37adfa528f](https://linux-hardware.org/?probe=37adfa528f) | Apr 30, 2024 |
| Pegatron      | A15                         | Notebook    | [259d4c4051](https://linux-hardware.org/?probe=259d4c4051) | Apr 30, 2024 |
| Pegatron      | A15                         | Notebook    | [555c8aa911](https://linux-hardware.org/?probe=555c8aa911) | Apr 30, 2024 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [2282169665](https://linux-hardware.org/?probe=2282169665) | Apr 29, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [a05a4bbcc2](https://linux-hardware.org/?probe=a05a4bbcc2) | Apr 28, 2024 |
| ASUSTek       | K55VJ                       | Notebook    | [dee27f64b0](https://linux-hardware.org/?probe=dee27f64b0) | Apr 28, 2024 |
| ASUSTek       | K55VJ                       | Notebook    | [ade9763073](https://linux-hardware.org/?probe=ade9763073) | Apr 28, 2024 |
| Pegatron      | IPXSB-H61                   | Desktop     | [202618ccd6](https://linux-hardware.org/?probe=202618ccd6) | Apr 27, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [00f2fc6455](https://linux-hardware.org/?probe=00f2fc6455) | Apr 27, 2024 |
| Monster       | ABRA A5 V16.5               | Notebook    | [dafa6ffefd](https://linux-hardware.org/?probe=dafa6ffefd) | Apr 26, 2024 |
| Monster       | ABRA A5 V20.2               | Notebook    | [7c8b0185ad](https://linux-hardware.org/?probe=7c8b0185ad) | Apr 26, 2024 |
| Dell          | Precision 3551              | Notebook    | [f5fbef6c5d](https://linux-hardware.org/?probe=f5fbef6c5d) | Apr 26, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [b5d2df5a85](https://linux-hardware.org/?probe=b5d2df5a85) | Apr 26, 2024 |
| Dell          | Precision 3551              | Notebook    | [4a88987cea](https://linux-hardware.org/?probe=4a88987cea) | Apr 25, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [e89543357b](https://linux-hardware.org/?probe=e89543357b) | Apr 25, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [353dfb074d](https://linux-hardware.org/?probe=353dfb074d) | Apr 25, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [91dc4d43de](https://linux-hardware.org/?probe=91dc4d43de) | Apr 25, 2024 |
| Acer          | Aspire A315-59G             | Notebook    | [0a16aa62ad](https://linux-hardware.org/?probe=0a16aa62ad) | Apr 23, 2024 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [6f1ba910cd](https://linux-hardware.org/?probe=6f1ba910cd) | Apr 23, 2024 |
| HP            | Victus by Gaming Laptop     | Notebook    | [7178fbf1eb](https://linux-hardware.org/?probe=7178fbf1eb) | Apr 23, 2024 |
| MSI           | CSM-H81M-P32                | Desktop     | [056face9de](https://linux-hardware.org/?probe=056face9de) | Apr 22, 2024 |
| Monster       | ABRA A5 V9.1                | Notebook    | [de1c33f8ea](https://linux-hardware.org/?probe=de1c33f8ea) | Apr 22, 2024 |
| Gigabyte      | MH310BP-R6                  | Desktop     | [68e0a22e4d](https://linux-hardware.org/?probe=68e0a22e4d) | Apr 22, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [d3e9e01950](https://linux-hardware.org/?probe=d3e9e01950) | Apr 21, 2024 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [6e6ef1d063](https://linux-hardware.org/?probe=6e6ef1d063) | Apr 21, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [be0672ea72](https://linux-hardware.org/?probe=be0672ea72) | Apr 21, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [661b2a53b2](https://linux-hardware.org/?probe=661b2a53b2) | Apr 21, 2024 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [d2e7817b97](https://linux-hardware.org/?probe=d2e7817b97) | Apr 21, 2024 |
| SGIN          | M15                         | Notebook    | [68c2d94db7](https://linux-hardware.org/?probe=68c2d94db7) | Apr 20, 2024 |
| Monster       | ABRA A5 V9.1                | Notebook    | [a438f99e4d](https://linux-hardware.org/?probe=a438f99e4d) | Apr 20, 2024 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [c823822177](https://linux-hardware.org/?probe=c823822177) | Apr 20, 2024 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [7985c3ea99](https://linux-hardware.org/?probe=7985c3ea99) | Apr 19, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [8e0d1cf973](https://linux-hardware.org/?probe=8e0d1cf973) | Apr 19, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [c0cb351a9c](https://linux-hardware.org/?probe=c0cb351a9c) | Apr 18, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [f225a565f5](https://linux-hardware.org/?probe=f225a565f5) | Apr 18, 2024 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [58824cb080](https://linux-hardware.org/?probe=58824cb080) | Apr 18, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [e045e6c6c3](https://linux-hardware.org/?probe=e045e6c6c3) | Apr 17, 2024 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6727adfce1](https://linux-hardware.org/?probe=6727adfce1) | Apr 17, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [a9de65b3dc](https://linux-hardware.org/?probe=a9de65b3dc) | Apr 16, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [a596d334bf](https://linux-hardware.org/?probe=a596d334bf) | Apr 16, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [be2b691a57](https://linux-hardware.org/?probe=be2b691a57) | Apr 15, 2024 |
| Lenovo        | ThinkPad T480 20L6S68A00    | Notebook    | [d480b5dc92](https://linux-hardware.org/?probe=d480b5dc92) | Apr 15, 2024 |
| HP            | 1494                        | Desktop     | [6dc287f96f](https://linux-hardware.org/?probe=6dc287f96f) | Apr 14, 2024 |
| HP            | ProBook 4540s               | Notebook    | [ace6254b85](https://linux-hardware.org/?probe=ace6254b85) | Apr 14, 2024 |
| HP            | ProBook 4540s               | Notebook    | [1d64c374de](https://linux-hardware.org/?probe=1d64c374de) | Apr 14, 2024 |
| HP            | 250 G4 Notebook PC          | Notebook    | [2fcb542c43](https://linux-hardware.org/?probe=2fcb542c43) | Apr 14, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [73379ea508](https://linux-hardware.org/?probe=73379ea508) | Apr 13, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [20e54ade99](https://linux-hardware.org/?probe=20e54ade99) | Apr 13, 2024 |
| Gigabyte      | 945PLM-S2                   | Desktop     | [caa84a8e1f](https://linux-hardware.org/?probe=caa84a8e1f) | Apr 13, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [07844c11ad](https://linux-hardware.org/?probe=07844c11ad) | Apr 13, 2024 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [5296079f86](https://linux-hardware.org/?probe=5296079f86) | Apr 12, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [30d9e28258](https://linux-hardware.org/?probe=30d9e28258) | Apr 12, 2024 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [a97e21eb8a](https://linux-hardware.org/?probe=a97e21eb8a) | Apr 11, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [c7d6945bb3](https://linux-hardware.org/?probe=c7d6945bb3) | Apr 11, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [918934ed68](https://linux-hardware.org/?probe=918934ed68) | Apr 11, 2024 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b215419382](https://linux-hardware.org/?probe=b215419382) | Apr 10, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [e9e940ec8a](https://linux-hardware.org/?probe=e9e940ec8a) | Apr 10, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [823f3c3138](https://linux-hardware.org/?probe=823f3c3138) | Apr 09, 2024 |
| HP            | 1494                        | Desktop     | [8888d5839f](https://linux-hardware.org/?probe=8888d5839f) | Apr 08, 2024 |
| HP            | 1494                        | Desktop     | [d338a69cee](https://linux-hardware.org/?probe=d338a69cee) | Apr 08, 2024 |
| ASUSTek       | P8H77-V                     | Desktop     | [721926ded3](https://linux-hardware.org/?probe=721926ded3) | Apr 08, 2024 |
| MSI           | PRO B760M-A WIFI            | Desktop     | [e69bf7c4c3](https://linux-hardware.org/?probe=e69bf7c4c3) | Apr 07, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [acf90db418](https://linux-hardware.org/?probe=acf90db418) | Apr 06, 2024 |
| MSI           | PRO B760M-A WIFI            | Desktop     | [adb9de77ef](https://linux-hardware.org/?probe=adb9de77ef) | Apr 06, 2024 |
| HUAWEI        | KLVF-XX                     | Notebook    | [775f139f3b](https://linux-hardware.org/?probe=775f139f3b) | Apr 06, 2024 |
| HUAWEI        | KLVF-XX                     | Notebook    | [6d24eb8f58](https://linux-hardware.org/?probe=6d24eb8f58) | Apr 06, 2024 |
| Casper        | EXCALIBUR G770              | Notebook    | [3accfd7d7b](https://linux-hardware.org/?probe=3accfd7d7b) | Apr 05, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [772e8d7f15](https://linux-hardware.org/?probe=772e8d7f15) | Apr 05, 2024 |
| Casper        | EXCALIBUR G770              | Notebook    | [00d364c46f](https://linux-hardware.org/?probe=00d364c46f) | Apr 05, 2024 |
| Lenovo        | ThinkPad T430 2349RQ3       | Notebook    | [6988a75b14](https://linux-hardware.org/?probe=6988a75b14) | Apr 05, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [b30ba46617](https://linux-hardware.org/?probe=b30ba46617) | Apr 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [7bb2773966](https://linux-hardware.org/?probe=7bb2773966) | Apr 05, 2024 |
| Dell          | G15 5530                    | Notebook    | [a1b2877a39](https://linux-hardware.org/?probe=a1b2877a39) | Apr 05, 2024 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [15b41ef5b3](https://linux-hardware.org/?probe=15b41ef5b3) | Apr 04, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [c139fcd8d6](https://linux-hardware.org/?probe=c139fcd8d6) | Apr 04, 2024 |
| Dell          | 0WR7PY A00                  | Desktop     | [16d748639f](https://linux-hardware.org/?probe=16d748639f) | Apr 04, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [72f797f01f](https://linux-hardware.org/?probe=72f797f01f) | Apr 04, 2024 |
| HP            | Pavilion g6                 | Notebook    | [1857b80f6f](https://linux-hardware.org/?probe=1857b80f6f) | Apr 04, 2024 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [cb68928e99](https://linux-hardware.org/?probe=cb68928e99) | Apr 03, 2024 |
| ASUSTek       | N53SV                       | Notebook    | [12ab7fe764](https://linux-hardware.org/?probe=12ab7fe764) | Apr 01, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d98f7f3516](https://linux-hardware.org/?probe=d98f7f3516) | Apr 01, 2024 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [b13340abe1](https://linux-hardware.org/?probe=b13340abe1) | Apr 01, 2024 |
| ASUSTek       | UX410UQK                    | Notebook    | [9b11a1c1ad](https://linux-hardware.org/?probe=9b11a1c1ad) | Mar 31, 2024 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [0b0b2cfaba](https://linux-hardware.org/?probe=0b0b2cfaba) | Mar 30, 2024 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [640e524f35](https://linux-hardware.org/?probe=640e524f35) | Mar 30, 2024 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [d310b775e9](https://linux-hardware.org/?probe=d310b775e9) | Mar 29, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d26eb0b735](https://linux-hardware.org/?probe=d26eb0b735) | Mar 28, 2024 |
| Insyde        | i101c                       | Notebook    | [fd15a3a81f](https://linux-hardware.org/?probe=fd15a3a81f) | Mar 28, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [831e41730c](https://linux-hardware.org/?probe=831e41730c) | Mar 27, 2024 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [05bab22d87](https://linux-hardware.org/?probe=05bab22d87) | Mar 27, 2024 |
| ASUSTek       | X555LNB                     | Notebook    | [45dec21dcc](https://linux-hardware.org/?probe=45dec21dcc) | Mar 27, 2024 |
| ASUSTek       | X555LNB                     | Notebook    | [cc09f69f8c](https://linux-hardware.org/?probe=cc09f69f8c) | Mar 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [e128a63580](https://linux-hardware.org/?probe=e128a63580) | Mar 26, 2024 |
| Intel         | H55                         | Desktop     | [5d58a28cd9](https://linux-hardware.org/?probe=5d58a28cd9) | Mar 26, 2024 |
| Toshiba       | Satellite C75-A             | Notebook    | [f153e82f42](https://linux-hardware.org/?probe=f153e82f42) | Mar 26, 2024 |
| Toshiba       | Satellite C75-A             | Notebook    | [1152d85ee1](https://linux-hardware.org/?probe=1152d85ee1) | Mar 26, 2024 |
| Lenovo        | Z50-70 20354                | Notebook    | [68838b01fa](https://linux-hardware.org/?probe=68838b01fa) | Mar 26, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [bddc045346](https://linux-hardware.org/?probe=bddc045346) | Mar 26, 2024 |
| Intel         | H55                         | Desktop     | [be179dfade](https://linux-hardware.org/?probe=be179dfade) | Mar 26, 2024 |
| Dell          | 0WR7PY A00                  | Desktop     | [b645536aff](https://linux-hardware.org/?probe=b645536aff) | Mar 25, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e2f8f7ac57](https://linux-hardware.org/?probe=e2f8f7ac57) | Mar 24, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4788b61821](https://linux-hardware.org/?probe=4788b61821) | Mar 24, 2024 |
| HP            | ProBook 430 G4              | Notebook    | [d199369cfc](https://linux-hardware.org/?probe=d199369cfc) | Mar 24, 2024 |
| HP            | ProBook 430 G4              | Notebook    | [16dd8d0203](https://linux-hardware.org/?probe=16dd8d0203) | Mar 24, 2024 |
| Casper        | EXCALIBUR G900              | Notebook    | [f5b2fe66ff](https://linux-hardware.org/?probe=f5b2fe66ff) | Mar 24, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [633d507169](https://linux-hardware.org/?probe=633d507169) | Mar 24, 2024 |
| HP            | EliteBook 8530w             | Notebook    | [68ee7621ae](https://linux-hardware.org/?probe=68ee7621ae) | Mar 24, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [c52682f980](https://linux-hardware.org/?probe=c52682f980) | Mar 23, 2024 |
| Monster       | ABRA A5 V17.4               | Notebook    | [153af2c8d9](https://linux-hardware.org/?probe=153af2c8d9) | Mar 23, 2024 |
| HP            | 8054                        | Desktop     | [269251e535](https://linux-hardware.org/?probe=269251e535) | Mar 21, 2024 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [6428f854e6](https://linux-hardware.org/?probe=6428f854e6) | Mar 21, 2024 |
| MSI           | Z170A GAMING M3             | Desktop     | [8e89b3ef32](https://linux-hardware.org/?probe=8e89b3ef32) | Mar 20, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [9ca2b22999](https://linux-hardware.org/?probe=9ca2b22999) | Mar 20, 2024 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [8c89af327d](https://linux-hardware.org/?probe=8c89af327d) | Mar 20, 2024 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [8b6f721112](https://linux-hardware.org/?probe=8b6f721112) | Mar 20, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03577ae940](https://linux-hardware.org/?probe=03577ae940) | Mar 19, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [0fa9c73550](https://linux-hardware.org/?probe=0fa9c73550) | Mar 19, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | Notebook    | [93f757d8b3](https://linux-hardware.org/?probe=93f757d8b3) | Mar 18, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [fb281cfb94](https://linux-hardware.org/?probe=fb281cfb94) | Mar 18, 2024 |
| Intel         | H61 V1.1                    | Desktop     | [eb0d3daea7](https://linux-hardware.org/?probe=eb0d3daea7) | Mar 18, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d9f0d873c4](https://linux-hardware.org/?probe=d9f0d873c4) | Mar 18, 2024 |
| Fujitsu Si... | D2750-A2 S26361-D2750-A2    | Desktop     | [35962081a4](https://linux-hardware.org/?probe=35962081a4) | Mar 17, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [67c8bbbbec](https://linux-hardware.org/?probe=67c8bbbbec) | Mar 17, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [8dcb3c6e6e](https://linux-hardware.org/?probe=8dcb3c6e6e) | Mar 17, 2024 |
| Acer          | Swift SF314-41G             | Notebook    | [22ac3144fc](https://linux-hardware.org/?probe=22ac3144fc) | Mar 17, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [507e652893](https://linux-hardware.org/?probe=507e652893) | Mar 17, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e7849fe0ba](https://linux-hardware.org/?probe=e7849fe0ba) | Mar 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [3f171c561b](https://linux-hardware.org/?probe=3f171c561b) | Mar 16, 2024 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [df438763ef](https://linux-hardware.org/?probe=df438763ef) | Mar 15, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [49ccd4595e](https://linux-hardware.org/?probe=49ccd4595e) | Mar 15, 2024 |
| ARCELIK       | GNB 1150 B1 N2              | Notebook    | [ebe974790a](https://linux-hardware.org/?probe=ebe974790a) | Mar 14, 2024 |
| ARCELIK       | GNB 1150 B1 N2              | Notebook    | [abb3de4578](https://linux-hardware.org/?probe=abb3de4578) | Mar 14, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [30a3327d61](https://linux-hardware.org/?probe=30a3327d61) | Mar 14, 2024 |
| Dell          | 0VNM11 A03                  | Desktop     | [178c559906](https://linux-hardware.org/?probe=178c559906) | Mar 14, 2024 |
| Dell          | 0VNM11 A03                  | Desktop     | [c56a91f121](https://linux-hardware.org/?probe=c56a91f121) | Mar 14, 2024 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [53ffb858c0](https://linux-hardware.org/?probe=53ffb858c0) | Mar 14, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [92707b25ae](https://linux-hardware.org/?probe=92707b25ae) | Mar 14, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5f739cf4a3](https://linux-hardware.org/?probe=5f739cf4a3) | Mar 12, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [ed5b898404](https://linux-hardware.org/?probe=ed5b898404) | Mar 12, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [4a79c1e432](https://linux-hardware.org/?probe=4a79c1e432) | Mar 12, 2024 |
| MSI           | H610M BOMBER DDR4           | Desktop     | [8795e218dc](https://linux-hardware.org/?probe=8795e218dc) | Mar 10, 2024 |
| MSI           | GF75 Thin 10SC              | Notebook    | [a415956dc4](https://linux-hardware.org/?probe=a415956dc4) | Mar 10, 2024 |
| HP            | ProBook 450 G7              | Notebook    | [2226e08e91](https://linux-hardware.org/?probe=2226e08e91) | Mar 09, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [5c9ff73ab5](https://linux-hardware.org/?probe=5c9ff73ab5) | Mar 09, 2024 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [f2300b0ebd](https://linux-hardware.org/?probe=f2300b0ebd) | Mar 09, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | Notebook    | [bd5a3177a0](https://linux-hardware.org/?probe=bd5a3177a0) | Mar 09, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bc116e452e](https://linux-hardware.org/?probe=bc116e452e) | Mar 08, 2024 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [84d939804b](https://linux-hardware.org/?probe=84d939804b) | Mar 07, 2024 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [7b9efc67c9](https://linux-hardware.org/?probe=7b9efc67c9) | Mar 07, 2024 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [63ebde2f79](https://linux-hardware.org/?probe=63ebde2f79) | Mar 07, 2024 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [caa7537216](https://linux-hardware.org/?probe=caa7537216) | Mar 07, 2024 |
| Dell          | Latitude E6410              | Notebook    | [2d821e2d6c](https://linux-hardware.org/?probe=2d821e2d6c) | Mar 07, 2024 |
| Monster       | TULPAR T7 V20.3             | Notebook    | [df8b4e385a](https://linux-hardware.org/?probe=df8b4e385a) | Mar 06, 2024 |
| Sony          | SVF1521NSTB                 | Notebook    | [b9f4d235c9](https://linux-hardware.org/?probe=b9f4d235c9) | Mar 06, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [cad73d3451](https://linux-hardware.org/?probe=cad73d3451) | Mar 06, 2024 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c63bca0fdc](https://linux-hardware.org/?probe=c63bca0fdc) | Mar 05, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [585ba3971c](https://linux-hardware.org/?probe=585ba3971c) | Mar 05, 2024 |
| Monster       | TULPAR T7 V21.8             | Notebook    | [608b9e154e](https://linux-hardware.org/?probe=608b9e154e) | Mar 05, 2024 |
| ASUSTek       | ROG Strix G614JU_G614JU     | Notebook    | [c557a3eccf](https://linux-hardware.org/?probe=c557a3eccf) | Mar 04, 2024 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [e3a0187ed0](https://linux-hardware.org/?probe=e3a0187ed0) | Mar 03, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [c259f8ec51](https://linux-hardware.org/?probe=c259f8ec51) | Mar 03, 2024 |
| HP            | Pavilion g6                 | Notebook    | [0590dc2c6d](https://linux-hardware.org/?probe=0590dc2c6d) | Mar 02, 2024 |
| Monster       | Huma H5 V3.2                | Notebook    | [36511aa895](https://linux-hardware.org/?probe=36511aa895) | Mar 02, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [6286320fc9](https://linux-hardware.org/?probe=6286320fc9) | Mar 02, 2024 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [b85a5f54e0](https://linux-hardware.org/?probe=b85a5f54e0) | Mar 02, 2024 |
| Dell          | Precision 7760              | Notebook    | [e032c1878e](https://linux-hardware.org/?probe=e032c1878e) | Mar 01, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [f610fa6db2](https://linux-hardware.org/?probe=f610fa6db2) | Mar 01, 2024 |
| ASUSTek       | P8H61-M PLUS2               | Desktop     | [9539fc46cc](https://linux-hardware.org/?probe=9539fc46cc) | Feb 29, 2024 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [29f6262e4e](https://linux-hardware.org/?probe=29f6262e4e) | Feb 28, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7ea1563009](https://linux-hardware.org/?probe=7ea1563009) | Feb 28, 2024 |
| ASUSTek       | E205SA                      | Notebook    | [447990dcac](https://linux-hardware.org/?probe=447990dcac) | Feb 27, 2024 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [48e3020e8e](https://linux-hardware.org/?probe=48e3020e8e) | Feb 27, 2024 |
| Dell          | Latitude E6430              | Notebook    | [c5a0f97c32](https://linux-hardware.org/?probe=c5a0f97c32) | Feb 27, 2024 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [ba96bddc39](https://linux-hardware.org/?probe=ba96bddc39) | Feb 27, 2024 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [19a2ccc504](https://linux-hardware.org/?probe=19a2ccc504) | Feb 27, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [5c829afa05](https://linux-hardware.org/?probe=5c829afa05) | Feb 27, 2024 |
| Lenovo        | ThinkPad T480 20L6S2CB00    | Notebook    | [eff836bcb1](https://linux-hardware.org/?probe=eff836bcb1) | Feb 27, 2024 |
| Intel         | B75                         | Desktop     | [096f58af21](https://linux-hardware.org/?probe=096f58af21) | Feb 26, 2024 |
| Lenovo        | ThinkPad T480 20L6S2CB00    | Notebook    | [a78eb227db](https://linux-hardware.org/?probe=a78eb227db) | Feb 26, 2024 |
| Dell          | Inspiron 14 5401            | Notebook    | [58f0a8c87c](https://linux-hardware.org/?probe=58f0a8c87c) | Feb 25, 2024 |
| Monster       | ABRA A5 V18.1               | Notebook    | [fb4a45369d](https://linux-hardware.org/?probe=fb4a45369d) | Feb 25, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [6988401a58](https://linux-hardware.org/?probe=6988401a58) | Feb 24, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [39ed74cf97](https://linux-hardware.org/?probe=39ed74cf97) | Feb 24, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [f31eac8a5d](https://linux-hardware.org/?probe=f31eac8a5d) | Feb 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [c6cff98a84](https://linux-hardware.org/?probe=c6cff98a84) | Feb 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [448ad7f7cf](https://linux-hardware.org/?probe=448ad7f7cf) | Feb 24, 2024 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [75ca2d004c](https://linux-hardware.org/?probe=75ca2d004c) | Feb 23, 2024 |
| HP            | 240 14 inch G9              | Notebook    | [54ea49a49a](https://linux-hardware.org/?probe=54ea49a49a) | Feb 23, 2024 |
| Dell          | 0TKWC4 A00                  | All in one  | [de2db89e95](https://linux-hardware.org/?probe=de2db89e95) | Feb 23, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [6a88d5ebaf](https://linux-hardware.org/?probe=6a88d5ebaf) | Feb 23, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [340e79c73f](https://linux-hardware.org/?probe=340e79c73f) | Feb 22, 2024 |
| Sony          | VPCSB1Z9E                   | Notebook    | [aeb30cde62](https://linux-hardware.org/?probe=aeb30cde62) | Feb 22, 2024 |
| Lenovo        | 3763                        | All in one  | [8df8dcd26b](https://linux-hardware.org/?probe=8df8dcd26b) | Feb 21, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [3b908d0f13](https://linux-hardware.org/?probe=3b908d0f13) | Feb 20, 2024 |
| Acer          | Swift SF314-42              | Notebook    | [c998a6d3ea](https://linux-hardware.org/?probe=c998a6d3ea) | Feb 20, 2024 |
| HP            | 550                         | Notebook    | [760294d146](https://linux-hardware.org/?probe=760294d146) | Feb 19, 2024 |
| Sony          | VPCSB1Z9E                   | Notebook    | [e80db1062b](https://linux-hardware.org/?probe=e80db1062b) | Feb 19, 2024 |
| Sony          | VPCSB1Z9E                   | Notebook    | [8f990384cb](https://linux-hardware.org/?probe=8f990384cb) | Feb 18, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [b7b3adc644](https://linux-hardware.org/?probe=b7b3adc644) | Feb 18, 2024 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [231f712a1e](https://linux-hardware.org/?probe=231f712a1e) | Feb 17, 2024 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d18785d54f](https://linux-hardware.org/?probe=d18785d54f) | Feb 16, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [39da02c65d](https://linux-hardware.org/?probe=39da02c65d) | Feb 16, 2024 |
| HUAWEI        | RLEF-XX                     | Notebook    | [3a25485178](https://linux-hardware.org/?probe=3a25485178) | Feb 15, 2024 |
| HP            | G62                         | Notebook    | [a4ec67ec47](https://linux-hardware.org/?probe=a4ec67ec47) | Feb 14, 2024 |
| Lenovo        | ThinkPad T480 20L6S68A00    | Notebook    | [f116cb1689](https://linux-hardware.org/?probe=f116cb1689) | Feb 14, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [f3d4535f87](https://linux-hardware.org/?probe=f3d4535f87) | Feb 13, 2024 |
| Monster       | ABRA A7 V13.2               | Notebook    | [43b70d4c02](https://linux-hardware.org/?probe=43b70d4c02) | Feb 13, 2024 |
| Dell          | 05WXFV A02                  | Desktop     | [9c231dbc1a](https://linux-hardware.org/?probe=9c231dbc1a) | Feb 13, 2024 |
| HP            | G62                         | Notebook    | [7df01c03a4](https://linux-hardware.org/?probe=7df01c03a4) | Feb 13, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [fda923c904](https://linux-hardware.org/?probe=fda923c904) | Feb 13, 2024 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [6fb885473c](https://linux-hardware.org/?probe=6fb885473c) | Feb 12, 2024 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [8d1d5db604](https://linux-hardware.org/?probe=8d1d5db604) | Feb 11, 2024 |
| Casper        | NIRVANA NB X700             | Notebook    | [47af353e0f](https://linux-hardware.org/?probe=47af353e0f) | Feb 11, 2024 |
| Casper        | NIRVANA NB X700             | Notebook    | [5ac31b9a80](https://linux-hardware.org/?probe=5ac31b9a80) | Feb 11, 2024 |
| Monster       | ABRA A7 V11.5               | Notebook    | [4d2e3f43ac](https://linux-hardware.org/?probe=4d2e3f43ac) | Feb 10, 2024 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [5ecacd2214](https://linux-hardware.org/?probe=5ecacd2214) | Feb 09, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [ba8e24ef8f](https://linux-hardware.org/?probe=ba8e24ef8f) | Feb 08, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [142b258a2b](https://linux-hardware.org/?probe=142b258a2b) | Feb 08, 2024 |
| Intel         | H55                         | Desktop     | [144f21d04f](https://linux-hardware.org/?probe=144f21d04f) | Feb 08, 2024 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [5372f5846e](https://linux-hardware.org/?probe=5372f5846e) | Feb 08, 2024 |
| Intel         | H55                         | Desktop     | [cadc3711e0](https://linux-hardware.org/?probe=cadc3711e0) | Feb 07, 2024 |
| Acer          | Nitro AN515-45              | Notebook    | [8c58790505](https://linux-hardware.org/?probe=8c58790505) | Feb 06, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [f5ec3d3bcb](https://linux-hardware.org/?probe=f5ec3d3bcb) | Feb 06, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [53d2b2f04b](https://linux-hardware.org/?probe=53d2b2f04b) | Feb 06, 2024 |
| Dell          | G15 5530                    | Notebook    | [8e3d4bec39](https://linux-hardware.org/?probe=8e3d4bec39) | Feb 06, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [a36801175e](https://linux-hardware.org/?probe=a36801175e) | Feb 06, 2024 |
| Acer          | Aspire 5742G                | Notebook    | [1fdb1cdc5f](https://linux-hardware.org/?probe=1fdb1cdc5f) | Feb 06, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [ea1ca63d23](https://linux-hardware.org/?probe=ea1ca63d23) | Feb 06, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [d5bdc5d0a6](https://linux-hardware.org/?probe=d5bdc5d0a6) | Feb 06, 2024 |
| Lenovo        | ThinkPad T480 20L6S68A00    | Notebook    | [41402a4115](https://linux-hardware.org/?probe=41402a4115) | Feb 06, 2024 |
| Dell          | G15 5530                    | Notebook    | [4f11246f1c](https://linux-hardware.org/?probe=4f11246f1c) | Feb 06, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [50d7951466](https://linux-hardware.org/?probe=50d7951466) | Feb 05, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [a688c4fc6e](https://linux-hardware.org/?probe=a688c4fc6e) | Feb 05, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b5ec65e8ab](https://linux-hardware.org/?probe=b5ec65e8ab) | Feb 05, 2024 |
| HP            | Victus by Gaming Laptop     | Notebook    | [4869fafc84](https://linux-hardware.org/?probe=4869fafc84) | Feb 03, 2024 |
| HP            | Victus by Gaming Laptop     | Notebook    | [d9c4fe247a](https://linux-hardware.org/?probe=d9c4fe247a) | Feb 03, 2024 |
| Rockchip      | RK3318 BOX                  | Soc         | [14fed775b0](https://linux-hardware.org/?probe=14fed775b0) | Feb 03, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [1fe97c9103](https://linux-hardware.org/?probe=1fe97c9103) | Feb 02, 2024 |
| ASRock        | A320M-ITX                   | Desktop     | [7c3ebbb23c](https://linux-hardware.org/?probe=7c3ebbb23c) | Feb 02, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [654e691a5d](https://linux-hardware.org/?probe=654e691a5d) | Feb 02, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [279e68de12](https://linux-hardware.org/?probe=279e68de12) | Feb 02, 2024 |
| Toshiba       | Satellite L750              | Notebook    | [a1e1f9075d](https://linux-hardware.org/?probe=a1e1f9075d) | Feb 01, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [7cd644d30e](https://linux-hardware.org/?probe=7cd644d30e) | Jan 31, 2024 |
| HP            | Pavilion g6                 | Notebook    | [acd0ae9c04](https://linux-hardware.org/?probe=acd0ae9c04) | Jan 31, 2024 |
| Valve         | Jupiter                     | Notebook    | [574ab05eb4](https://linux-hardware.org/?probe=574ab05eb4) | Jan 31, 2024 |
| Dell          | Inspiron 1520               | Notebook    | [371f061c1d](https://linux-hardware.org/?probe=371f061c1d) | Jan 31, 2024 |
| ASUSTek       | Maximus V GENE              | Desktop     | [a56cd980bb](https://linux-hardware.org/?probe=a56cd980bb) | Jan 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [4690cc047a](https://linux-hardware.org/?probe=4690cc047a) | Jan 30, 2024 |
| ARCELIK       | GNB 1150 B1 N2              | Notebook    | [eb35406b7e](https://linux-hardware.org/?probe=eb35406b7e) | Jan 29, 2024 |
| MSI           | G41M-P23                    | Desktop     | [74ac4742e0](https://linux-hardware.org/?probe=74ac4742e0) | Jan 28, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [765673ce15](https://linux-hardware.org/?probe=765673ce15) | Jan 27, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [1f1d3ff8f9](https://linux-hardware.org/?probe=1f1d3ff8f9) | Jan 27, 2024 |
| ASUSTek       | K52JT                       | Notebook    | [dd44051584](https://linux-hardware.org/?probe=dd44051584) | Jan 27, 2024 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [4490f8e838](https://linux-hardware.org/?probe=4490f8e838) | Jan 27, 2024 |
| Monster       | ABRA A7 V13.3               | Notebook    | [08516ca0c2](https://linux-hardware.org/?probe=08516ca0c2) | Jan 26, 2024 |
| HP            | 82F2 A01                    | Desktop     | [437bec28fa](https://linux-hardware.org/?probe=437bec28fa) | Jan 26, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [9a3ff54cf8](https://linux-hardware.org/?probe=9a3ff54cf8) | Jan 26, 2024 |
| Toshiba       | Satellite P50T-A-114        | Notebook    | [5286decec5](https://linux-hardware.org/?probe=5286decec5) | Jan 26, 2024 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [fc297eda09](https://linux-hardware.org/?probe=fc297eda09) | Jan 25, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fd825e1d58](https://linux-hardware.org/?probe=fd825e1d58) | Jan 25, 2024 |
| MSI           | B560M PRO-E                 | Desktop     | [898383016a](https://linux-hardware.org/?probe=898383016a) | Jan 25, 2024 |
| Lenovo        | Unknown                     | Notebook    | [ae59a4d618](https://linux-hardware.org/?probe=ae59a4d618) | Jan 25, 2024 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [90a5837b3c](https://linux-hardware.org/?probe=90a5837b3c) | Jan 24, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [cf3c2deee4](https://linux-hardware.org/?probe=cf3c2deee4) | Jan 23, 2024 |
| Intel         | H61                         | Desktop     | [d3895696ad](https://linux-hardware.org/?probe=d3895696ad) | Jan 23, 2024 |
| Dell          | Latitude 5480               | Notebook    | [45ac237d79](https://linux-hardware.org/?probe=45ac237d79) | Jan 23, 2024 |
| Acer          | Predator PH315-53           | Notebook    | [74ca3f63e2](https://linux-hardware.org/?probe=74ca3f63e2) | Jan 22, 2024 |
| ASUSTek       | A55BM-E                     | Desktop     | [3d3b63f7c5](https://linux-hardware.org/?probe=3d3b63f7c5) | Jan 22, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [ea8cc27b1a](https://linux-hardware.org/?probe=ea8cc27b1a) | Jan 21, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [c72427a053](https://linux-hardware.org/?probe=c72427a053) | Jan 21, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [97e1f1353f](https://linux-hardware.org/?probe=97e1f1353f) | Jan 21, 2024 |
| Casper        | NIRVANA NOTEBOOK            | Desktop     | [af055c48ff](https://linux-hardware.org/?probe=af055c48ff) | Jan 21, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [73fe1f94d6](https://linux-hardware.org/?probe=73fe1f94d6) | Jan 20, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [c765a21a05](https://linux-hardware.org/?probe=c765a21a05) | Jan 18, 2024 |
| AZW           | SEi                         | Notebook    | [b144837b91](https://linux-hardware.org/?probe=b144837b91) | Jan 18, 2024 |
| Acer          | Aspire A315-57G             | Notebook    | [8c8ccb9324](https://linux-hardware.org/?probe=8c8ccb9324) | Jan 17, 2024 |
| Acer          | Aspire A315-57G             | Notebook    | [f7eb7dc2e9](https://linux-hardware.org/?probe=f7eb7dc2e9) | Jan 17, 2024 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [27cfeb78bf](https://linux-hardware.org/?probe=27cfeb78bf) | Jan 17, 2024 |
| Monster       | ABRA A5 V16.6               | Notebook    | [181ed8314a](https://linux-hardware.org/?probe=181ed8314a) | Jan 17, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e6e63ec982](https://linux-hardware.org/?probe=e6e63ec982) | Jan 17, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [d2b4053179](https://linux-hardware.org/?probe=d2b4053179) | Jan 16, 2024 |
| Lenovo        | ThinkPad T490 20N3S3XR00    | Notebook    | [63ec999c70](https://linux-hardware.org/?probe=63ec999c70) | Jan 16, 2024 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [6578340c93](https://linux-hardware.org/?probe=6578340c93) | Jan 15, 2024 |
| HP            | Laptop 15-da1xxx            | Notebook    | [cd726b3a5a](https://linux-hardware.org/?probe=cd726b3a5a) | Jan 15, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [ad209d60d3](https://linux-hardware.org/?probe=ad209d60d3) | Jan 15, 2024 |
| Casper        | EXCALIBUR G900              | Notebook    | [8531ff6e44](https://linux-hardware.org/?probe=8531ff6e44) | Jan 15, 2024 |
| Casper        | EXCALIBUR G900              | Notebook    | [efb49fa361](https://linux-hardware.org/?probe=efb49fa361) | Jan 15, 2024 |
| AZW           | SEi                         | Notebook    | [b8f32bfbbc](https://linux-hardware.org/?probe=b8f32bfbbc) | Jan 14, 2024 |
| HONOR         | BMH-WCX9                    | Notebook    | [11d4c3f75d](https://linux-hardware.org/?probe=11d4c3f75d) | Jan 14, 2024 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [569afd2c6a](https://linux-hardware.org/?probe=569afd2c6a) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [53a45b597e](https://linux-hardware.org/?probe=53a45b597e) | Jan 13, 2024 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a3e108e50d](https://linux-hardware.org/?probe=a3e108e50d) | Jan 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [f35fb9dd1c](https://linux-hardware.org/?probe=f35fb9dd1c) | Jan 13, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [df073dcede](https://linux-hardware.org/?probe=df073dcede) | Jan 12, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1bad1acfa2](https://linux-hardware.org/?probe=1bad1acfa2) | Jan 11, 2024 |
| MSI           | A75A-G35                    | Desktop     | [288caa413e](https://linux-hardware.org/?probe=288caa413e) | Jan 09, 2024 |
| Fujitsu Si... | D2581-A5 S26361-D2581-A5    | Desktop     | [986a67391f](https://linux-hardware.org/?probe=986a67391f) | Jan 09, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [513efe6ed6](https://linux-hardware.org/?probe=513efe6ed6) | Jan 09, 2024 |
| Gigabyte      | B450M K-CF                  | Desktop     | [6ffbab86cc](https://linux-hardware.org/?probe=6ffbab86cc) | Jan 07, 2024 |
| Gigabyte      | B85M-HD3                    | Desktop     | [5229c0698f](https://linux-hardware.org/?probe=5229c0698f) | Jan 07, 2024 |
| Acer          | Extensa 215-54G             | Notebook    | [3c25dd10dd](https://linux-hardware.org/?probe=3c25dd10dd) | Jan 06, 2024 |
| Acer          | Aspire A715-43G             | Notebook    | [023677517d](https://linux-hardware.org/?probe=023677517d) | Jan 06, 2024 |
| Acer          | Extensa 215-54G             | Notebook    | [031b668bcb](https://linux-hardware.org/?probe=031b668bcb) | Jan 06, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [555cd52c4c](https://linux-hardware.org/?probe=555cd52c4c) | Jan 05, 2024 |
| ASUSTek       | P553UJ                      | Notebook    | [6e0de808da](https://linux-hardware.org/?probe=6e0de808da) | Jan 05, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [de57acd268](https://linux-hardware.org/?probe=de57acd268) | Jan 03, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [2c8c483194](https://linux-hardware.org/?probe=2c8c483194) | Jan 03, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [68e2ccb6e6](https://linux-hardware.org/?probe=68e2ccb6e6) | Jan 03, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [f96513dd00](https://linux-hardware.org/?probe=f96513dd00) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [21c267752a](https://linux-hardware.org/?probe=21c267752a) | Jan 02, 2024 |
| Dell          | 0V8F20 A01                  | Desktop     | [ceebdc4f9e](https://linux-hardware.org/?probe=ceebdc4f9e) | Jan 01, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [934f756965](https://linux-hardware.org/?probe=934f756965) | Dec 31, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [d508dc8f38](https://linux-hardware.org/?probe=d508dc8f38) | Dec 31, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [76869cc8d4](https://linux-hardware.org/?probe=76869cc8d4) | Dec 31, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [ff8e890649](https://linux-hardware.org/?probe=ff8e890649) | Dec 30, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [06e3a35d05](https://linux-hardware.org/?probe=06e3a35d05) | Dec 29, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | Notebook    | [0f8be1187e](https://linux-hardware.org/?probe=0f8be1187e) | Dec 28, 2023 |
| Packard Be... | EasyNote MH35               | Notebook    | [2b8b39d335](https://linux-hardware.org/?probe=2b8b39d335) | Dec 27, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [73bbd42b1f](https://linux-hardware.org/?probe=73bbd42b1f) | Dec 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S24N3J    | Notebook    | [b6b0c2c889](https://linux-hardware.org/?probe=b6b0c2c889) | Dec 27, 2023 |
| Lenovo        | B51-35 80LH                 | Notebook    | [85a89b00af](https://linux-hardware.org/?probe=85a89b00af) | Dec 26, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [a8acfd11f6](https://linux-hardware.org/?probe=a8acfd11f6) | Dec 25, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [3ac6a566ab](https://linux-hardware.org/?probe=3ac6a566ab) | Dec 24, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [dc269fb33a](https://linux-hardware.org/?probe=dc269fb33a) | Dec 24, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [b1342e1524](https://linux-hardware.org/?probe=b1342e1524) | Dec 23, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [498753636e](https://linux-hardware.org/?probe=498753636e) | Dec 22, 2023 |
| MSI           | Creator 15M A10SD           | Notebook    | [5ed074ddfb](https://linux-hardware.org/?probe=5ed074ddfb) | Dec 19, 2023 |
| HP            | 82DD                        | All in one  | [5d63cf94b5](https://linux-hardware.org/?probe=5d63cf94b5) | Dec 19, 2023 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [f3149a6f22](https://linux-hardware.org/?probe=f3149a6f22) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [2b7376d8a1](https://linux-hardware.org/?probe=2b7376d8a1) | Dec 18, 2023 |
| HP            | 82DD                        | All in one  | [04f88f72a8](https://linux-hardware.org/?probe=04f88f72a8) | Dec 18, 2023 |
| HP            | 82DD                        | All in one  | [3ffc09317f](https://linux-hardware.org/?probe=3ffc09317f) | Dec 18, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [8425b10899](https://linux-hardware.org/?probe=8425b10899) | Dec 17, 2023 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [b7a7aa8d5d](https://linux-hardware.org/?probe=b7a7aa8d5d) | Dec 17, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [3a2290dbe0](https://linux-hardware.org/?probe=3a2290dbe0) | Dec 16, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [a2a4eb520c](https://linux-hardware.org/?probe=a2a4eb520c) | Dec 16, 2023 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [a7dd86011c](https://linux-hardware.org/?probe=a7dd86011c) | Dec 16, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [a9b6f1553d](https://linux-hardware.org/?probe=a9b6f1553d) | Dec 16, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [15c3d23fc9](https://linux-hardware.org/?probe=15c3d23fc9) | Dec 15, 2023 |
| HP            | 82DD                        | All in one  | [0ea0ece8c7](https://linux-hardware.org/?probe=0ea0ece8c7) | Dec 15, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d32726759c](https://linux-hardware.org/?probe=d32726759c) | Dec 15, 2023 |
| Dell          | Precision 7560              | Notebook    | [0f83098df3](https://linux-hardware.org/?probe=0f83098df3) | Dec 15, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [0b19e954c5](https://linux-hardware.org/?probe=0b19e954c5) | Dec 14, 2023 |
| MSI           | PRO B650-VC WIFI            | Desktop     | [fc0a02d2d1](https://linux-hardware.org/?probe=fc0a02d2d1) | Dec 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [cc4a45597c](https://linux-hardware.org/?probe=cc4a45597c) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [ef4cd6f316](https://linux-hardware.org/?probe=ef4cd6f316) | Dec 12, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [16bb3367f0](https://linux-hardware.org/?probe=16bb3367f0) | Dec 11, 2023 |
| Casper        | *SP*                        | Notebook    | [5fb7fac59d](https://linux-hardware.org/?probe=5fb7fac59d) | Dec 10, 2023 |
| Casper        | *SP*                        | Notebook    | [5a1d880754](https://linux-hardware.org/?probe=5a1d880754) | Dec 10, 2023 |
| HP            | Notebook                    | Notebook    | [19c87ca6c5](https://linux-hardware.org/?probe=19c87ca6c5) | Dec 10, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [fab1403ca7](https://linux-hardware.org/?probe=fab1403ca7) | Dec 10, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [d9d22e25cb](https://linux-hardware.org/?probe=d9d22e25cb) | Dec 09, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [1435c0e9db](https://linux-hardware.org/?probe=1435c0e9db) | Dec 09, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [25627a5644](https://linux-hardware.org/?probe=25627a5644) | Dec 08, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [7824421836](https://linux-hardware.org/?probe=7824421836) | Dec 08, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [b1c2f80587](https://linux-hardware.org/?probe=b1c2f80587) | Dec 07, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [b4da4c1d8a](https://linux-hardware.org/?probe=b4da4c1d8a) | Dec 07, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [b21bc9aa81](https://linux-hardware.org/?probe=b21bc9aa81) | Dec 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c6f72287f3](https://linux-hardware.org/?probe=c6f72287f3) | Dec 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9960314986](https://linux-hardware.org/?probe=9960314986) | Dec 06, 2023 |
| HP            | 82DD                        | All in one  | [a70d193fa2](https://linux-hardware.org/?probe=a70d193fa2) | Dec 06, 2023 |
| HP            | 82DD                        | All in one  | [c45bd18bc5](https://linux-hardware.org/?probe=c45bd18bc5) | Dec 06, 2023 |
| Toshiba       | Satellite C55D-C            | Notebook    | [888584071d](https://linux-hardware.org/?probe=888584071d) | Dec 05, 2023 |
| HP            | 82DD                        | All in one  | [b302adc5f9](https://linux-hardware.org/?probe=b302adc5f9) | Dec 05, 2023 |
| ASUSTek       | P553UJ                      | Notebook    | [e5ed994bf9](https://linux-hardware.org/?probe=e5ed994bf9) | Dec 05, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [bab7262ca5](https://linux-hardware.org/?probe=bab7262ca5) | Dec 04, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [b8a831d450](https://linux-hardware.org/?probe=b8a831d450) | Dec 04, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [6c7f7fe382](https://linux-hardware.org/?probe=6c7f7fe382) | Dec 04, 2023 |
| Monster       | TULPAR T7 V20.2             | Notebook    | [1d83d3589e](https://linux-hardware.org/?probe=1d83d3589e) | Dec 03, 2023 |
| Monster       | TULPAR T7 V21.8             | Notebook    | [0f6162aabe](https://linux-hardware.org/?probe=0f6162aabe) | Dec 02, 2023 |
| Sony          | VPCF11M1E                   | Notebook    | [f185cc14da](https://linux-hardware.org/?probe=f185cc14da) | Dec 01, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [f5e978e47d](https://linux-hardware.org/?probe=f5e978e47d) | Dec 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [8524905e3f](https://linux-hardware.org/?probe=8524905e3f) | Nov 30, 2023 |
| Toshiba       | Satellite L850D-131         | Notebook    | [483c7cfdf6](https://linux-hardware.org/?probe=483c7cfdf6) | Nov 30, 2023 |
| ASUSTek       | V161GAR                     | All in one  | [e0032832bd](https://linux-hardware.org/?probe=e0032832bd) | Nov 30, 2023 |
| Dell          | Precision M6800             | Notebook    | [0112706077](https://linux-hardware.org/?probe=0112706077) | Nov 29, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [0a673a3528](https://linux-hardware.org/?probe=0a673a3528) | Nov 28, 2023 |
| Acer          | Aspire E5-521G              | Notebook    | [d639f77bd9](https://linux-hardware.org/?probe=d639f77bd9) | Nov 28, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [bd498a1e04](https://linux-hardware.org/?probe=bd498a1e04) | Nov 27, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [e86c1bf644](https://linux-hardware.org/?probe=e86c1bf644) | Nov 27, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [d597be352c](https://linux-hardware.org/?probe=d597be352c) | Nov 27, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [dedc54db8f](https://linux-hardware.org/?probe=dedc54db8f) | Nov 27, 2023 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [088789a558](https://linux-hardware.org/?probe=088789a558) | Nov 27, 2023 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [fa45cae3d1](https://linux-hardware.org/?probe=fa45cae3d1) | Nov 27, 2023 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [c2a7190ba8](https://linux-hardware.org/?probe=c2a7190ba8) | Nov 27, 2023 |
| HP            | 0B54h D                     | Desktop     | [0fccef5d79](https://linux-hardware.org/?probe=0fccef5d79) | Nov 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [ce68d047a6](https://linux-hardware.org/?probe=ce68d047a6) | Nov 26, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c686cc4ca0](https://linux-hardware.org/?probe=c686cc4ca0) | Nov 26, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [fbec470224](https://linux-hardware.org/?probe=fbec470224) | Nov 26, 2023 |
| HP            | 1497                        | Desktop     | [1cbc2dbbc9](https://linux-hardware.org/?probe=1cbc2dbbc9) | Nov 26, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [1e4a3ed089](https://linux-hardware.org/?probe=1e4a3ed089) | Nov 25, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [a2fbff15e7](https://linux-hardware.org/?probe=a2fbff15e7) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [7c92224aed](https://linux-hardware.org/?probe=7c92224aed) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [57a3d9064a](https://linux-hardware.org/?probe=57a3d9064a) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [a4c63ff9b4](https://linux-hardware.org/?probe=a4c63ff9b4) | Nov 25, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [6e47e7fce4](https://linux-hardware.org/?probe=6e47e7fce4) | Nov 24, 2023 |
| Lenovo        | MAHOBAY Win8 STD EM DPK ... | All in one  | [a86dba284f](https://linux-hardware.org/?probe=a86dba284f) | Nov 24, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [2127112b3a](https://linux-hardware.org/?probe=2127112b3a) | Nov 23, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [206b5d76fb](https://linux-hardware.org/?probe=206b5d76fb) | Nov 23, 2023 |
| Toshiba       | Satellite L850D-131         | Notebook    | [8810505a5a](https://linux-hardware.org/?probe=8810505a5a) | Nov 23, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [1ec9d0635f](https://linux-hardware.org/?probe=1ec9d0635f) | Nov 23, 2023 |
| ASUSTek       | M3N78-VM                    | Desktop     | [1790fdb82e](https://linux-hardware.org/?probe=1790fdb82e) | Nov 22, 2023 |
| Gigabyte      | P67A-UD3P-B3                | Desktop     | [182a1c4293](https://linux-hardware.org/?probe=182a1c4293) | Nov 21, 2023 |
| Dell          | Vostro 15 5501              | Notebook    | [ebb962a4ff](https://linux-hardware.org/?probe=ebb962a4ff) | Nov 21, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [b528cb2139](https://linux-hardware.org/?probe=b528cb2139) | Nov 19, 2023 |
| ASUSTek       | TP500LB                     | Notebook    | [697dfb4387](https://linux-hardware.org/?probe=697dfb4387) | Nov 19, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [1ee7faaeb4](https://linux-hardware.org/?probe=1ee7faaeb4) | Nov 18, 2023 |
| Monster       | ABRA A5 V17.2               | Notebook    | [130ef88703](https://linux-hardware.org/?probe=130ef88703) | Nov 17, 2023 |
| Monster       | ABRA A5 V17.2               | Notebook    | [76653a926b](https://linux-hardware.org/?probe=76653a926b) | Nov 17, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [be914025c2](https://linux-hardware.org/?probe=be914025c2) | Nov 17, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [58e714af7e](https://linux-hardware.org/?probe=58e714af7e) | Nov 16, 2023 |
| ASUSTek       | H81-GAMER                   | Desktop     | [c5a2208642](https://linux-hardware.org/?probe=c5a2208642) | Nov 15, 2023 |
| ASUSTek       | H81-GAMER                   | Desktop     | [8891aedb5d](https://linux-hardware.org/?probe=8891aedb5d) | Nov 15, 2023 |
| HUAWEI        | HBB-WX9                     | Notebook    | [d3d635372e](https://linux-hardware.org/?probe=d3d635372e) | Nov 15, 2023 |
| Monster       | ABRA A5 V17.4               | Notebook    | [2645ae8296](https://linux-hardware.org/?probe=2645ae8296) | Nov 15, 2023 |
| Acer          | Aspire A715-43G             | Notebook    | [e0e5d2b93e](https://linux-hardware.org/?probe=e0e5d2b93e) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [392c269f06](https://linux-hardware.org/?probe=392c269f06) | Nov 14, 2023 |
| Dell          | G5 5505                     | Notebook    | [be553804bd](https://linux-hardware.org/?probe=be553804bd) | Nov 13, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [c7be71a544](https://linux-hardware.org/?probe=c7be71a544) | Nov 13, 2023 |
| Dell          | G5 5505                     | Notebook    | [574ccd4e6f](https://linux-hardware.org/?probe=574ccd4e6f) | Nov 13, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [5a7374e5b0](https://linux-hardware.org/?probe=5a7374e5b0) | Nov 13, 2023 |
| Google        | Hanawl                      | Notebook    | [39b8f28b8e](https://linux-hardware.org/?probe=39b8f28b8e) | Nov 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [3172a3c77c](https://linux-hardware.org/?probe=3172a3c77c) | Nov 12, 2023 |
| Google        | Hana                        | Notebook    | [80ae861cdf](https://linux-hardware.org/?probe=80ae861cdf) | Nov 12, 2023 |
| Google        | cozmo                       | Soc         | [71a554097a](https://linux-hardware.org/?probe=71a554097a) | Nov 12, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [c1b89d8187](https://linux-hardware.org/?probe=c1b89d8187) | Nov 12, 2023 |
| HUAWEI        | RLEFG-XX                    | Notebook    | [5f413be4fc](https://linux-hardware.org/?probe=5f413be4fc) | Nov 12, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [091eaf746f](https://linux-hardware.org/?probe=091eaf746f) | Nov 12, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [0ba73e8306](https://linux-hardware.org/?probe=0ba73e8306) | Nov 11, 2023 |
| Gigabyte      | H610M H V2 DDR4             | Desktop     | [bafab6bf21](https://linux-hardware.org/?probe=bafab6bf21) | Nov 10, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [31d4fc8694](https://linux-hardware.org/?probe=31d4fc8694) | Nov 09, 2023 |
| ECS           | H81H3-M7                    | Desktop     | [d2afbe33c7](https://linux-hardware.org/?probe=d2afbe33c7) | Nov 09, 2023 |
| ECS           | H81H3-M7                    | Desktop     | [e5ea8b4820](https://linux-hardware.org/?probe=e5ea8b4820) | Nov 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [12d30e16b4](https://linux-hardware.org/?probe=12d30e16b4) | Nov 07, 2023 |
| Dell          | G3 3779                     | Notebook    | [74ef4d1941](https://linux-hardware.org/?probe=74ef4d1941) | Nov 06, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [a782c6c087](https://linux-hardware.org/?probe=a782c6c087) | Nov 05, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [a2fbd58a8c](https://linux-hardware.org/?probe=a2fbd58a8c) | Nov 05, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [124c666940](https://linux-hardware.org/?probe=124c666940) | Nov 05, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [9eeeda059e](https://linux-hardware.org/?probe=9eeeda059e) | Nov 05, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [4c97723997](https://linux-hardware.org/?probe=4c97723997) | Nov 04, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [0a0e80ef0f](https://linux-hardware.org/?probe=0a0e80ef0f) | Nov 04, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [ba8e987366](https://linux-hardware.org/?probe=ba8e987366) | Nov 03, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [6844fc4fcf](https://linux-hardware.org/?probe=6844fc4fcf) | Nov 03, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [5bb358c66e](https://linux-hardware.org/?probe=5bb358c66e) | Nov 02, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [7d589af687](https://linux-hardware.org/?probe=7d589af687) | Nov 02, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [b5c8e35523](https://linux-hardware.org/?probe=b5c8e35523) | Nov 02, 2023 |
| AOpen         | D2644 S26361-D2644          | Desktop     | [db682d636c](https://linux-hardware.org/?probe=db682d636c) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G634JZ            | Notebook    | [62ed235c2f](https://linux-hardware.org/?probe=62ed235c2f) | Nov 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [9422d2efb5](https://linux-hardware.org/?probe=9422d2efb5) | Nov 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [dd9715f35d](https://linux-hardware.org/?probe=dd9715f35d) | Oct 31, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4f0b8be2f6](https://linux-hardware.org/?probe=4f0b8be2f6) | Oct 30, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [ff941d75c9](https://linux-hardware.org/?probe=ff941d75c9) | Oct 29, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [307134fa91](https://linux-hardware.org/?probe=307134fa91) | Oct 29, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [186a763d8a](https://linux-hardware.org/?probe=186a763d8a) | Oct 29, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [c90dd43290](https://linux-hardware.org/?probe=c90dd43290) | Oct 29, 2023 |
| Acer          | Aspire A715-43G             | Notebook    | [d9337e90a8](https://linux-hardware.org/?probe=d9337e90a8) | Oct 28, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [84c2a8040c](https://linux-hardware.org/?probe=84c2a8040c) | Oct 28, 2023 |
| Lenovo        | YogaAir 14s APU8 83AA       | Notebook    | [4f120347b7](https://linux-hardware.org/?probe=4f120347b7) | Oct 27, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [47336d64a9](https://linux-hardware.org/?probe=47336d64a9) | Oct 27, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [609cfbdfa5](https://linux-hardware.org/?probe=609cfbdfa5) | Oct 26, 2023 |
| Intel         | H55                         | Desktop     | [edff4a2637](https://linux-hardware.org/?probe=edff4a2637) | Oct 25, 2023 |
| ASUSTek       | X555UB                      | Notebook    | [f501faa5ac](https://linux-hardware.org/?probe=f501faa5ac) | Oct 25, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [d105da96dd](https://linux-hardware.org/?probe=d105da96dd) | Oct 25, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [6cd6569138](https://linux-hardware.org/?probe=6cd6569138) | Oct 25, 2023 |
| Acer          | Veriton S2680G              | Desktop     | [da9a811b04](https://linux-hardware.org/?probe=da9a811b04) | Oct 25, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [15ac9c0529](https://linux-hardware.org/?probe=15ac9c0529) | Oct 24, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [5a0abfcf6f](https://linux-hardware.org/?probe=5a0abfcf6f) | Oct 24, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [8a67a1a41a](https://linux-hardware.org/?probe=8a67a1a41a) | Oct 24, 2023 |
| Colorful T... | BATTLE-AX B450M-HD V14      | Desktop     | [314500a8ed](https://linux-hardware.org/?probe=314500a8ed) | Oct 23, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [8711389e77](https://linux-hardware.org/?probe=8711389e77) | Oct 22, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6d454c05e2](https://linux-hardware.org/?probe=6d454c05e2) | Oct 21, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [1f4b7f796f](https://linux-hardware.org/?probe=1f4b7f796f) | Oct 21, 2023 |
| Unknown       | H5104M-D                    | Desktop     | [24e459ac22](https://linux-hardware.org/?probe=24e459ac22) | Oct 21, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6cc2145e11](https://linux-hardware.org/?probe=6cc2145e11) | Oct 21, 2023 |
| Acer          | Aspire A315-58G             | Notebook    | [248f2fa5c4](https://linux-hardware.org/?probe=248f2fa5c4) | Oct 21, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e145bc3637](https://linux-hardware.org/?probe=e145bc3637) | Oct 21, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [b50515e464](https://linux-hardware.org/?probe=b50515e464) | Oct 20, 2023 |
| ASUSTek       | UN62                        | Desktop     | [a1cb1227bf](https://linux-hardware.org/?probe=a1cb1227bf) | Oct 20, 2023 |
| ASUSTek       | UN62                        | Desktop     | [48e1c6f6e2](https://linux-hardware.org/?probe=48e1c6f6e2) | Oct 20, 2023 |
| Toshiba       | Satellite A500              | Notebook    | [15b78585e0](https://linux-hardware.org/?probe=15b78585e0) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | Notebook    | [0d2e2856a9](https://linux-hardware.org/?probe=0d2e2856a9) | Oct 19, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [b7f7dc5f46](https://linux-hardware.org/?probe=b7f7dc5f46) | Oct 19, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [f10e780f12](https://linux-hardware.org/?probe=f10e780f12) | Oct 19, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [011e35b011](https://linux-hardware.org/?probe=011e35b011) | Oct 15, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [4e2a3f7606](https://linux-hardware.org/?probe=4e2a3f7606) | Oct 15, 2023 |
| ASUSTek       | H81-GAMER                   | Desktop     | [4db3cdfdca](https://linux-hardware.org/?probe=4db3cdfdca) | Oct 15, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [94d47a3e29](https://linux-hardware.org/?probe=94d47a3e29) | Oct 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [00d3c32a60](https://linux-hardware.org/?probe=00d3c32a60) | Oct 13, 2023 |
| Toshiba       | Satellite C55D-C            | Notebook    | [2d067797db](https://linux-hardware.org/?probe=2d067797db) | Oct 12, 2023 |
| ASUSTek       | H81-GAMER                   | Desktop     | [d0271d3735](https://linux-hardware.org/?probe=d0271d3735) | Oct 11, 2023 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [5a8c03bc6a](https://linux-hardware.org/?probe=5a8c03bc6a) | Oct 11, 2023 |
| Toshiba       | Satellite C870-D7K          | Notebook    | [150f57bc3d](https://linux-hardware.org/?probe=150f57bc3d) | Oct 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a5c5f58ddb](https://linux-hardware.org/?probe=a5c5f58ddb) | Oct 11, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [bad4423bfe](https://linux-hardware.org/?probe=bad4423bfe) | Oct 10, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b7f6af41f9](https://linux-hardware.org/?probe=b7f6af41f9) | Oct 09, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [d400853f78](https://linux-hardware.org/?probe=d400853f78) | Oct 08, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [3f3879060f](https://linux-hardware.org/?probe=3f3879060f) | Oct 07, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [2b58fa8ba6](https://linux-hardware.org/?probe=2b58fa8ba6) | Oct 06, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [8437cd6631](https://linux-hardware.org/?probe=8437cd6631) | Oct 06, 2023 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [c5c7ad01ed](https://linux-hardware.org/?probe=c5c7ad01ed) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [e627afd34e](https://linux-hardware.org/?probe=e627afd34e) | Oct 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [204a97a06f](https://linux-hardware.org/?probe=204a97a06f) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [25aa854661](https://linux-hardware.org/?probe=25aa854661) | Oct 03, 2023 |
| Toshiba       | KIRAbook                    | Notebook    | [802a0e1afd](https://linux-hardware.org/?probe=802a0e1afd) | Oct 02, 2023 |
| IX1401        | Unknown                     | Notebook    | [8014a1028b](https://linux-hardware.org/?probe=8014a1028b) | Oct 02, 2023 |
| EXPER         | H61H2-MV                    | Desktop     | [5cd287a613](https://linux-hardware.org/?probe=5cd287a613) | Oct 01, 2023 |
| EXPER         | H61H2-MV                    | Desktop     | [7b50b9b997](https://linux-hardware.org/?probe=7b50b9b997) | Oct 01, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [6e0e08c45e](https://linux-hardware.org/?probe=6e0e08c45e) | Oct 01, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [16354c8d94](https://linux-hardware.org/?probe=16354c8d94) | Oct 01, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [a8c796cebf](https://linux-hardware.org/?probe=a8c796cebf) | Oct 01, 2023 |
| Acer          | Aspire SW5-173              | Notebook    | [b990067acf](https://linux-hardware.org/?probe=b990067acf) | Oct 01, 2023 |
| Dell          | Latitude 5520               | Notebook    | [024af71640](https://linux-hardware.org/?probe=024af71640) | Oct 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [1a9c5d539b](https://linux-hardware.org/?probe=1a9c5d539b) | Oct 01, 2023 |
| IX1401        | Unknown                     | Notebook    | [c77c1d010e](https://linux-hardware.org/?probe=c77c1d010e) | Sep 30, 2023 |
| Casper        | NIRVANA N240                | Notebook    | [fa2c4e6569](https://linux-hardware.org/?probe=fa2c4e6569) | Sep 29, 2023 |
| Toshiba       | Satellite P50-B-117         | Notebook    | [cecfba4e8f](https://linux-hardware.org/?probe=cecfba4e8f) | Sep 28, 2023 |
| Biostar       | B450MH                      | Desktop     | [e932e22b99](https://linux-hardware.org/?probe=e932e22b99) | Sep 28, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [0a51882a60](https://linux-hardware.org/?probe=0a51882a60) | Sep 28, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [cf0c9cc177](https://linux-hardware.org/?probe=cf0c9cc177) | Sep 28, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [96ee1b2b2a](https://linux-hardware.org/?probe=96ee1b2b2a) | Sep 28, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [a32eb9fe02](https://linux-hardware.org/?probe=a32eb9fe02) | Sep 28, 2023 |
| Toshiba       | Satellite P50-B-117         | Notebook    | [3931144171](https://linux-hardware.org/?probe=3931144171) | Sep 27, 2023 |
| Lenovo        | S10-3c 20074                | Notebook    | [b8adc3cf3e](https://linux-hardware.org/?probe=b8adc3cf3e) | Sep 27, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [f11867f0b7](https://linux-hardware.org/?probe=f11867f0b7) | Sep 26, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [45b934b885](https://linux-hardware.org/?probe=45b934b885) | Sep 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [b6cd63eedc](https://linux-hardware.org/?probe=b6cd63eedc) | Sep 26, 2023 |
| ASUSTek       | X555UB                      | Notebook    | [8496a9f79f](https://linux-hardware.org/?probe=8496a9f79f) | Sep 26, 2023 |
| HP            | Notebook                    | Notebook    | [b59281115b](https://linux-hardware.org/?probe=b59281115b) | Sep 25, 2023 |
| HP            | Notebook                    | Notebook    | [896e2216de](https://linux-hardware.org/?probe=896e2216de) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [45d1ad03f8](https://linux-hardware.org/?probe=45d1ad03f8) | Sep 25, 2023 |
| ASUSTek       | N56VZ                       | Notebook    | [3d727dfaf6](https://linux-hardware.org/?probe=3d727dfaf6) | Sep 24, 2023 |
| Acer          | TravelMate P215-53G         | Notebook    | [ddda10c87f](https://linux-hardware.org/?probe=ddda10c87f) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [7f88191a7b](https://linux-hardware.org/?probe=7f88191a7b) | Sep 23, 2023 |
| Casper        | NIRVANA NB F500             | Notebook    | [1f66f22544](https://linux-hardware.org/?probe=1f66f22544) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d21f140b5e](https://linux-hardware.org/?probe=d21f140b5e) | Sep 23, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [11ce4105e1](https://linux-hardware.org/?probe=11ce4105e1) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c40dbfbd1d](https://linux-hardware.org/?probe=c40dbfbd1d) | Sep 23, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [2676f29c41](https://linux-hardware.org/?probe=2676f29c41) | Sep 22, 2023 |
| ASUSTek       | N56VZ                       | Notebook    | [86c85c5aab](https://linux-hardware.org/?probe=86c85c5aab) | Sep 22, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [c416e12adb](https://linux-hardware.org/?probe=c416e12adb) | Sep 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [0f097b1b88](https://linux-hardware.org/?probe=0f097b1b88) | Sep 22, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [152021b3b1](https://linux-hardware.org/?probe=152021b3b1) | Sep 22, 2023 |
| Monster       | ABRA A7 V11.3               | Notebook    | [7d1ed0e1c5](https://linux-hardware.org/?probe=7d1ed0e1c5) | Sep 21, 2023 |
| Acer          | Veriton S2680G              | Desktop     | [76f872c7bb](https://linux-hardware.org/?probe=76f872c7bb) | Sep 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [cbc4ec2df0](https://linux-hardware.org/?probe=cbc4ec2df0) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [9fdc142c76](https://linux-hardware.org/?probe=9fdc142c76) | Sep 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [3b365e2d8e](https://linux-hardware.org/?probe=3b365e2d8e) | Sep 18, 2023 |
| Hometech      | Ultra Tab 8W                | Notebook    | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | Notebook    | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [ae6215005e](https://linux-hardware.org/?probe=ae6215005e) | Sep 17, 2023 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [613d6735a3](https://linux-hardware.org/?probe=613d6735a3) | Sep 17, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [96a8945a17](https://linux-hardware.org/?probe=96a8945a17) | Sep 17, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | Notebook    | [1b2e11b609](https://linux-hardware.org/?probe=1b2e11b609) | Sep 16, 2023 |
| ASUSTek       | X405UQ                      | Notebook    | [d642c4640f](https://linux-hardware.org/?probe=d642c4640f) | Sep 16, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [d8716b2645](https://linux-hardware.org/?probe=d8716b2645) | Sep 16, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [054463900e](https://linux-hardware.org/?probe=054463900e) | Sep 15, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [cdc9163353](https://linux-hardware.org/?probe=cdc9163353) | Sep 15, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [430657ed88](https://linux-hardware.org/?probe=430657ed88) | Sep 14, 2023 |
| Monster       | TULPAR T7 V20.4             | Notebook    | [d83fee9f1b](https://linux-hardware.org/?probe=d83fee9f1b) | Sep 14, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [8e517319b7](https://linux-hardware.org/?probe=8e517319b7) | Sep 14, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [02b6e4991e](https://linux-hardware.org/?probe=02b6e4991e) | Sep 13, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d4a65d06e2](https://linux-hardware.org/?probe=d4a65d06e2) | Sep 13, 2023 |
| HUAWEI        | WRT-WX9                     | Notebook    | [6bc54e3a67](https://linux-hardware.org/?probe=6bc54e3a67) | Sep 13, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [ac50c36768](https://linux-hardware.org/?probe=ac50c36768) | Sep 13, 2023 |
| Acer          | TravelMate P215-53G         | Notebook    | [eaa5b75106](https://linux-hardware.org/?probe=eaa5b75106) | Sep 13, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [74ab1950fb](https://linux-hardware.org/?probe=74ab1950fb) | Sep 13, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [3b15d88a26](https://linux-hardware.org/?probe=3b15d88a26) | Sep 13, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [5ea02e4106](https://linux-hardware.org/?probe=5ea02e4106) | Sep 12, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [0c4fdafbd2](https://linux-hardware.org/?probe=0c4fdafbd2) | Sep 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [3ef24a5b48](https://linux-hardware.org/?probe=3ef24a5b48) | Sep 12, 2023 |
| HP            | 8446                        | All in one  | [0305fb029e](https://linux-hardware.org/?probe=0305fb029e) | Sep 11, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [053a34d1f9](https://linux-hardware.org/?probe=053a34d1f9) | Sep 10, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | Notebook    | [fea8aeff9e](https://linux-hardware.org/?probe=fea8aeff9e) | Sep 10, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [7340842ec5](https://linux-hardware.org/?probe=7340842ec5) | Sep 10, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [1285b4583d](https://linux-hardware.org/?probe=1285b4583d) | Sep 10, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [9ad28d6747](https://linux-hardware.org/?probe=9ad28d6747) | Sep 09, 2023 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [35f1ceedcb](https://linux-hardware.org/?probe=35f1ceedcb) | Sep 09, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [c320e0c618](https://linux-hardware.org/?probe=c320e0c618) | Sep 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [97fc2d4d2c](https://linux-hardware.org/?probe=97fc2d4d2c) | Sep 09, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [4e756a7c7d](https://linux-hardware.org/?probe=4e756a7c7d) | Sep 08, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2c64750e2e](https://linux-hardware.org/?probe=2c64750e2e) | Sep 08, 2023 |
| Dell          | 0J37VM A01                  | Desktop     | [cfd16871a7](https://linux-hardware.org/?probe=cfd16871a7) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [905f93bc0a](https://linux-hardware.org/?probe=905f93bc0a) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [e87517b925](https://linux-hardware.org/?probe=e87517b925) | Sep 08, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [db6d9f2293](https://linux-hardware.org/?probe=db6d9f2293) | Sep 08, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [6b0747dcb4](https://linux-hardware.org/?probe=6b0747dcb4) | Sep 07, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [56a481c501](https://linux-hardware.org/?probe=56a481c501) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f59dbec9af](https://linux-hardware.org/?probe=f59dbec9af) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [83c77f6733](https://linux-hardware.org/?probe=83c77f6733) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [dd18138503](https://linux-hardware.org/?probe=dd18138503) | Sep 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [a1c2c12b6f](https://linux-hardware.org/?probe=a1c2c12b6f) | Sep 06, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [5b7ab92e89](https://linux-hardware.org/?probe=5b7ab92e89) | Sep 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7be68f9c9a](https://linux-hardware.org/?probe=7be68f9c9a) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [82fd19c99e](https://linux-hardware.org/?probe=82fd19c99e) | Sep 05, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [5dbf7515d1](https://linux-hardware.org/?probe=5dbf7515d1) | Sep 05, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [44c55bd588](https://linux-hardware.org/?probe=44c55bd588) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [229ca6e8cb](https://linux-hardware.org/?probe=229ca6e8cb) | Sep 05, 2023 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [d5abd666d9](https://linux-hardware.org/?probe=d5abd666d9) | Sep 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [9bc8520da8](https://linux-hardware.org/?probe=9bc8520da8) | Sep 04, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | Notebook    | [13b7789482](https://linux-hardware.org/?probe=13b7789482) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [4a93cea12b](https://linux-hardware.org/?probe=4a93cea12b) | Sep 04, 2023 |
| Monster       | Huma H5 V3.2                | Notebook    | [75d95e264e](https://linux-hardware.org/?probe=75d95e264e) | Sep 04, 2023 |
| Acer          | Veriton S2680G              | Desktop     | [e1fdce5232](https://linux-hardware.org/?probe=e1fdce5232) | Sep 04, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [9c788645a1](https://linux-hardware.org/?probe=9c788645a1) | Sep 03, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [2da95fb8e8](https://linux-hardware.org/?probe=2da95fb8e8) | Sep 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [56520c8e8d](https://linux-hardware.org/?probe=56520c8e8d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3900a91c0b](https://linux-hardware.org/?probe=3900a91c0b) | Sep 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | Notebook    | [13ea608a94](https://linux-hardware.org/?probe=13ea608a94) | Sep 03, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b53be4cf36](https://linux-hardware.org/?probe=b53be4cf36) | Sep 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [d00f64dfcf](https://linux-hardware.org/?probe=d00f64dfcf) | Sep 02, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [78037f5e38](https://linux-hardware.org/?probe=78037f5e38) | Sep 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [56fa43078f](https://linux-hardware.org/?probe=56fa43078f) | Sep 02, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [04acccf8e2](https://linux-hardware.org/?probe=04acccf8e2) | Sep 02, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [9224e20101](https://linux-hardware.org/?probe=9224e20101) | Sep 01, 2023 |
| Acer          | Veriton S2680G              | Desktop     | [17206d19f9](https://linux-hardware.org/?probe=17206d19f9) | Sep 01, 2023 |
| HP            | Pavilion 13                 | Notebook    | [ccf98e410b](https://linux-hardware.org/?probe=ccf98e410b) | Sep 01, 2023 |
| HP            | Pavilion 13                 | Notebook    | [b3e756ad21](https://linux-hardware.org/?probe=b3e756ad21) | Sep 01, 2023 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [5e0da96bdd](https://linux-hardware.org/?probe=5e0da96bdd) | Sep 01, 2023 |
| HP            | 82DD 0001                   | All in one  | [4d67f21aa7](https://linux-hardware.org/?probe=4d67f21aa7) | Aug 31, 2023 |
| Dell          | Precision 7730              | Notebook    | [11c494a20e](https://linux-hardware.org/?probe=11c494a20e) | Aug 30, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [9ed00c6987](https://linux-hardware.org/?probe=9ed00c6987) | Aug 30, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [3713bc7b70](https://linux-hardware.org/?probe=3713bc7b70) | Aug 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [8c492a4b3d](https://linux-hardware.org/?probe=8c492a4b3d) | Aug 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [320e8d218f](https://linux-hardware.org/?probe=320e8d218f) | Aug 28, 2023 |
| Dell          | G5 5505                     | Notebook    | [a96b02c261](https://linux-hardware.org/?probe=a96b02c261) | Aug 28, 2023 |
| Dell          | G5 5505                     | Notebook    | [01201d16aa](https://linux-hardware.org/?probe=01201d16aa) | Aug 28, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V805    | Notebook    | [ec4b2fa095](https://linux-hardware.org/?probe=ec4b2fa095) | Aug 28, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [3903bc9e14](https://linux-hardware.org/?probe=3903bc9e14) | Aug 27, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [7423f83594](https://linux-hardware.org/?probe=7423f83594) | Aug 27, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [bb8b8a594d](https://linux-hardware.org/?probe=bb8b8a594d) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [d526f12390](https://linux-hardware.org/?probe=d526f12390) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [0bda6b93da](https://linux-hardware.org/?probe=0bda6b93da) | Aug 27, 2023 |
| Dell          | Vostro 5468                 | Notebook    | [2ee2b86d87](https://linux-hardware.org/?probe=2ee2b86d87) | Aug 27, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [b59ee89595](https://linux-hardware.org/?probe=b59ee89595) | Aug 26, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [95ff13464e](https://linux-hardware.org/?probe=95ff13464e) | Aug 25, 2023 |
| Casper        | NIRVANA NB X400             | Notebook    | [e8aa46ffbc](https://linux-hardware.org/?probe=e8aa46ffbc) | Aug 25, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [01636af413](https://linux-hardware.org/?probe=01636af413) | Aug 25, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [1bd1add449](https://linux-hardware.org/?probe=1bd1add449) | Aug 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [ab538d0486](https://linux-hardware.org/?probe=ab538d0486) | Aug 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f7580a556b](https://linux-hardware.org/?probe=f7580a556b) | Aug 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [c86d5e890a](https://linux-hardware.org/?probe=c86d5e890a) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [68d28831a5](https://linux-hardware.org/?probe=68d28831a5) | Aug 22, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a1d2ccf421](https://linux-hardware.org/?probe=a1d2ccf421) | Aug 22, 2023 |
| Acer          | TravelMate P215-52G         | Notebook    | [e8673e8d9c](https://linux-hardware.org/?probe=e8673e8d9c) | Aug 21, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ccecca0639](https://linux-hardware.org/?probe=ccecca0639) | Aug 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c62fc8773a](https://linux-hardware.org/?probe=c62fc8773a) | Aug 21, 2023 |
| Pegatron      | A15                         | Notebook    | [624757036f](https://linux-hardware.org/?probe=624757036f) | Aug 20, 2023 |
| HP            | Pavilion g6                 | Notebook    | [45830a7769](https://linux-hardware.org/?probe=45830a7769) | Aug 20, 2023 |
| HP            | Pavilion g6                 | Notebook    | [d4ba2c046d](https://linux-hardware.org/?probe=d4ba2c046d) | Aug 20, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [19ecc69fc4](https://linux-hardware.org/?probe=19ecc69fc4) | Aug 19, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [caae17275e](https://linux-hardware.org/?probe=caae17275e) | Aug 17, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [684ece88c0](https://linux-hardware.org/?probe=684ece88c0) | Aug 17, 2023 |
| HP            | 3032h                       | Desktop     | [34a300f540](https://linux-hardware.org/?probe=34a300f540) | Aug 17, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [8ddf822ac7](https://linux-hardware.org/?probe=8ddf822ac7) | Aug 16, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [b0c33014c5](https://linux-hardware.org/?probe=b0c33014c5) | Aug 15, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [4b88db67fc](https://linux-hardware.org/?probe=4b88db67fc) | Aug 15, 2023 |
| MSI           | H510M PRO                   | Desktop     | [df350cd466](https://linux-hardware.org/?probe=df350cd466) | Aug 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGS... | Notebook    | [52f2042a47](https://linux-hardware.org/?probe=52f2042a47) | Aug 14, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [17d837907e](https://linux-hardware.org/?probe=17d837907e) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [a65f824e07](https://linux-hardware.org/?probe=a65f824e07) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [2da924ecb2](https://linux-hardware.org/?probe=2da924ecb2) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [ab5728ee52](https://linux-hardware.org/?probe=ab5728ee52) | Aug 13, 2023 |
| Monster       | ABRA A5 V17.2               | Notebook    | [0049202ca7](https://linux-hardware.org/?probe=0049202ca7) | Aug 13, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [def5f9423e](https://linux-hardware.org/?probe=def5f9423e) | Aug 12, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [e65db8d147](https://linux-hardware.org/?probe=e65db8d147) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3a7d1d1f9b](https://linux-hardware.org/?probe=3a7d1d1f9b) | Aug 11, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [6f323e0954](https://linux-hardware.org/?probe=6f323e0954) | Aug 11, 2023 |
| Lenovo        | ThinkPad L520 5017BW5       | Notebook    | [1a9bbdc058](https://linux-hardware.org/?probe=1a9bbdc058) | Aug 11, 2023 |
| HP            | 3032h                       | Desktop     | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Gigabyte      | P67A-UD3P-B3                | Desktop     | [a1c6469145](https://linux-hardware.org/?probe=a1c6469145) | Aug 11, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [3c239efc46](https://linux-hardware.org/?probe=3c239efc46) | Aug 11, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [c7c0f2ad91](https://linux-hardware.org/?probe=c7c0f2ad91) | Aug 10, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [6aaa92df1c](https://linux-hardware.org/?probe=6aaa92df1c) | Aug 10, 2023 |
| HP            | 3032h                       | Desktop     | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [a58ca66b2f](https://linux-hardware.org/?probe=a58ca66b2f) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [52bf9ffa35](https://linux-hardware.org/?probe=52bf9ffa35) | Aug 06, 2023 |
| Dell          | Latitude E7270              | Notebook    | [e7209c4bb7](https://linux-hardware.org/?probe=e7209c4bb7) | Aug 06, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [41b594c2c7](https://linux-hardware.org/?probe=41b594c2c7) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [ae42e537d2](https://linux-hardware.org/?probe=ae42e537d2) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [51f2c38666](https://linux-hardware.org/?probe=51f2c38666) | Aug 05, 2023 |
| MSI           | GF75 Thin 10SCXR            | Notebook    | [21d2f0b558](https://linux-hardware.org/?probe=21d2f0b558) | Aug 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [731ae84313](https://linux-hardware.org/?probe=731ae84313) | Aug 04, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [f29d0b0571](https://linux-hardware.org/?probe=f29d0b0571) | Aug 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [1db8a01118](https://linux-hardware.org/?probe=1db8a01118) | Aug 03, 2023 |
| Lenovo        | ThinkPad T400 6475R1G       | Notebook    | [481e1aa044](https://linux-hardware.org/?probe=481e1aa044) | Aug 03, 2023 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [aa6b646b24](https://linux-hardware.org/?probe=aa6b646b24) | Aug 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [363bee1696](https://linux-hardware.org/?probe=363bee1696) | Aug 03, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [80498caa0d](https://linux-hardware.org/?probe=80498caa0d) | Aug 03, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [33674f8b81](https://linux-hardware.org/?probe=33674f8b81) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [fc2f2f7f45](https://linux-hardware.org/?probe=fc2f2f7f45) | Aug 02, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [00311486d2](https://linux-hardware.org/?probe=00311486d2) | Aug 01, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [e5193cc5d3](https://linux-hardware.org/?probe=e5193cc5d3) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [e24869945e](https://linux-hardware.org/?probe=e24869945e) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [a2148fe49f](https://linux-hardware.org/?probe=a2148fe49f) | Aug 01, 2023 |
| Unknown       | HP Chromebook 14            | Notebook    | [ef963f6148](https://linux-hardware.org/?probe=ef963f6148) | Jul 31, 2023 |
| Google        | Snow                        | Notebook    | [422a01e612](https://linux-hardware.org/?probe=422a01e612) | Jul 31, 2023 |
| Google        | Peach Pit Rev 6+            | Notebook    | [18fff1679c](https://linux-hardware.org/?probe=18fff1679c) | Jul 31, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7486c0a60b](https://linux-hardware.org/?probe=7486c0a60b) | Jul 31, 2023 |
| Google        | Mighty                      | Notebook    | [6ed9cfe2d0](https://linux-hardware.org/?probe=6ed9cfe2d0) | Jul 31, 2023 |
| Google        | cozmo                       | Soc         | [d77d083f89](https://linux-hardware.org/?probe=d77d083f89) | Jul 31, 2023 |
| Google        | Hana                        | Soc         | [3f818b53ed](https://linux-hardware.org/?probe=3f818b53ed) | Jul 31, 2023 |
| Google        | Hana                        | Soc         | [b6d842b749](https://linux-hardware.org/?probe=b6d842b749) | Jul 31, 2023 |
| Google        | Hanawl                      | Notebook    | [08995c0e52](https://linux-hardware.org/?probe=08995c0e52) | Jul 31, 2023 |
| Google        | Kevin                       | Soc         | [19b1046480](https://linux-hardware.org/?probe=19b1046480) | Jul 31, 2023 |
| MSI           | U90/U100                    | Notebook    | [015b95ba2a](https://linux-hardware.org/?probe=015b95ba2a) | Jul 31, 2023 |
| Google        | Kevin                       | Notebook    | [ca1037f6ca](https://linux-hardware.org/?probe=ca1037f6ca) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [54462345a7](https://linux-hardware.org/?probe=54462345a7) | Jul 31, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [961a4eebbd](https://linux-hardware.org/?probe=961a4eebbd) | Jul 31, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [9e9caad8ea](https://linux-hardware.org/?probe=9e9caad8ea) | Jul 31, 2023 |
| I-Life Dig... | ZED Air CX7                 | Notebook    | [2c897f0413](https://linux-hardware.org/?probe=2c897f0413) | Jul 30, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [2c6149347b](https://linux-hardware.org/?probe=2c6149347b) | Jul 30, 2023 |
| Sony          | SVE14A2V2RS                 | Notebook    | [adc151e590](https://linux-hardware.org/?probe=adc151e590) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [f7dce38938](https://linux-hardware.org/?probe=f7dce38938) | Jul 28, 2023 |
| HP            | 250 G3                      | Notebook    | [49b5a143cf](https://linux-hardware.org/?probe=49b5a143cf) | Jul 28, 2023 |
| HP            | 82DD 0001                   | All in one  | [e6da7743f0](https://linux-hardware.org/?probe=e6da7743f0) | Jul 28, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [1b416b9f01](https://linux-hardware.org/?probe=1b416b9f01) | Jul 28, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [1d4e6c23cf](https://linux-hardware.org/?probe=1d4e6c23cf) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | Notebook    | [045470ba6d](https://linux-hardware.org/?probe=045470ba6d) | Jul 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6d6fe6a05b](https://linux-hardware.org/?probe=6d6fe6a05b) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [c2cf59f878](https://linux-hardware.org/?probe=c2cf59f878) | Jul 25, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c49c2e7a5a](https://linux-hardware.org/?probe=c49c2e7a5a) | Jul 24, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [b54465e0da](https://linux-hardware.org/?probe=b54465e0da) | Jul 23, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [83d48bc8eb](https://linux-hardware.org/?probe=83d48bc8eb) | Jul 22, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VU_GZ3... | Tablet      | [7387b87abf](https://linux-hardware.org/?probe=7387b87abf) | Jul 21, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [4b7b13a46d](https://linux-hardware.org/?probe=4b7b13a46d) | Jul 20, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [69a47b22c4](https://linux-hardware.org/?probe=69a47b22c4) | Jul 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [d688be2c92](https://linux-hardware.org/?probe=d688be2c92) | Jul 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5d3e13fc77](https://linux-hardware.org/?probe=5d3e13fc77) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [13ba381894](https://linux-hardware.org/?probe=13ba381894) | Jul 17, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [16715e16b9](https://linux-hardware.org/?probe=16715e16b9) | Jul 17, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [56a9ce9630](https://linux-hardware.org/?probe=56a9ce9630) | Jul 17, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [c659d8d6b5](https://linux-hardware.org/?probe=c659d8d6b5) | Jul 17, 2023 |
| Dell          | Latitude D610               | Notebook    | [791cabd713](https://linux-hardware.org/?probe=791cabd713) | Jul 16, 2023 |
| ASUSTek       | PRIME B650M-A II            | Desktop     | [bf4a6e7eea](https://linux-hardware.org/?probe=bf4a6e7eea) | Jul 15, 2023 |
| Dell          | G3 3779                     | Notebook    | [87b8ecffa4](https://linux-hardware.org/?probe=87b8ecffa4) | Jul 15, 2023 |
| Notebook      | NH5x_7xRCx,RDx              | Notebook    | [9e8ab59ea8](https://linux-hardware.org/?probe=9e8ab59ea8) | Jul 14, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [14b5fe64fa](https://linux-hardware.org/?probe=14b5fe64fa) | Jul 14, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [db28c39c19](https://linux-hardware.org/?probe=db28c39c19) | Jul 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [be97a731d4](https://linux-hardware.org/?probe=be97a731d4) | Jul 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a86a73b50c](https://linux-hardware.org/?probe=a86a73b50c) | Jul 13, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a9b5963254](https://linux-hardware.org/?probe=a9b5963254) | Jul 13, 2023 |
| Unknown       | Unknown                     | Soc         | [4bd4266d4b](https://linux-hardware.org/?probe=4bd4266d4b) | Jul 13, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [91d748c376](https://linux-hardware.org/?probe=91d748c376) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [7256e6a7b2](https://linux-hardware.org/?probe=7256e6a7b2) | Jul 11, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [61ac758cca](https://linux-hardware.org/?probe=61ac758cca) | Jul 10, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [a14d8855bc](https://linux-hardware.org/?probe=a14d8855bc) | Jul 10, 2023 |
| ASUSTek       | X550DP                      | Notebook    | [4cfcff7d7e](https://linux-hardware.org/?probe=4cfcff7d7e) | Jul 10, 2023 |
| Dell          | Latitude E6220              | Notebook    | [5e17659f32](https://linux-hardware.org/?probe=5e17659f32) | Jul 09, 2023 |
| Monster       | ABRA A5 V17.3               | Notebook    | [2b65146842](https://linux-hardware.org/?probe=2b65146842) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [ae008e5343](https://linux-hardware.org/?probe=ae008e5343) | Jul 07, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [c93db722a7](https://linux-hardware.org/?probe=c93db722a7) | Jul 06, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [d1a5adf1ef](https://linux-hardware.org/?probe=d1a5adf1ef) | Jul 06, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [cda93de5a6](https://linux-hardware.org/?probe=cda93de5a6) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d8206bf6c6](https://linux-hardware.org/?probe=d8206bf6c6) | Jul 05, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [53bd77d836](https://linux-hardware.org/?probe=53bd77d836) | Jul 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fea629b2e8](https://linux-hardware.org/?probe=fea629b2e8) | Jul 04, 2023 |
| Google        | Lick                        | Notebook    | [f2b9397a8b](https://linux-hardware.org/?probe=f2b9397a8b) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [19a254cdee](https://linux-hardware.org/?probe=19a254cdee) | Jul 03, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [36fed79d81](https://linux-hardware.org/?probe=36fed79d81) | Jul 01, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [969994628c](https://linux-hardware.org/?probe=969994628c) | Jun 30, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [53a5b9567e](https://linux-hardware.org/?probe=53a5b9567e) | Jun 30, 2023 |
| ASUSTek       | K501UX                      | Notebook    | [a7fb172b7d](https://linux-hardware.org/?probe=a7fb172b7d) | Jun 30, 2023 |
| Monster       | TULPAR T7 V21.7             | Notebook    | [046803a297](https://linux-hardware.org/?probe=046803a297) | Jun 30, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [5a88d6945d](https://linux-hardware.org/?probe=5a88d6945d) | Jun 29, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [8ef6f6f24a](https://linux-hardware.org/?probe=8ef6f6f24a) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [253fb546a2](https://linux-hardware.org/?probe=253fb546a2) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e5b49b2807](https://linux-hardware.org/?probe=e5b49b2807) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [49c7e22c1e](https://linux-hardware.org/?probe=49c7e22c1e) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [29203c5ffe](https://linux-hardware.org/?probe=29203c5ffe) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [c6edbe5681](https://linux-hardware.org/?probe=c6edbe5681) | Jun 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [a7df01b153](https://linux-hardware.org/?probe=a7df01b153) | Jun 24, 2023 |
| HP            | G62                         | Notebook    | [e8187f4fb6](https://linux-hardware.org/?probe=e8187f4fb6) | Jun 24, 2023 |
| MSI           | PRO H410M-B                 | Desktop     | [76dd0fc5f1](https://linux-hardware.org/?probe=76dd0fc5f1) | Jun 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [38ae545c1c](https://linux-hardware.org/?probe=38ae545c1c) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [af46eedb6f](https://linux-hardware.org/?probe=af46eedb6f) | Jun 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [6609cc4a31](https://linux-hardware.org/?probe=6609cc4a31) | Jun 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [cbf5b19c76](https://linux-hardware.org/?probe=cbf5b19c76) | Jun 21, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [9fef8732b6](https://linux-hardware.org/?probe=9fef8732b6) | Jun 21, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [4f5e2f9201](https://linux-hardware.org/?probe=4f5e2f9201) | Jun 21, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [eea8633642](https://linux-hardware.org/?probe=eea8633642) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [bff08fbf94](https://linux-hardware.org/?probe=bff08fbf94) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1595a5adbd](https://linux-hardware.org/?probe=1595a5adbd) | Jun 20, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [0cb6da57db](https://linux-hardware.org/?probe=0cb6da57db) | Jun 19, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [17a4ba54ac](https://linux-hardware.org/?probe=17a4ba54ac) | Jun 19, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [f49534dfa4](https://linux-hardware.org/?probe=f49534dfa4) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d09c902c57](https://linux-hardware.org/?probe=d09c902c57) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [6e1e0b2f1c](https://linux-hardware.org/?probe=6e1e0b2f1c) | Jun 19, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [4681ff2f7d](https://linux-hardware.org/?probe=4681ff2f7d) | Jun 19, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [e7f63885d1](https://linux-hardware.org/?probe=e7f63885d1) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [8fe751618d](https://linux-hardware.org/?probe=8fe751618d) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [337d8e9d36](https://linux-hardware.org/?probe=337d8e9d36) | Jun 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [fe97518345](https://linux-hardware.org/?probe=fe97518345) | Jun 17, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [d5ba369651](https://linux-hardware.org/?probe=d5ba369651) | Jun 17, 2023 |
| Dell          | Latitude E6410              | Notebook    | [5eff7cff21](https://linux-hardware.org/?probe=5eff7cff21) | Jun 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS        | Desktop     | [05923edc6b](https://linux-hardware.org/?probe=05923edc6b) | Jun 15, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [e37a7072fd](https://linux-hardware.org/?probe=e37a7072fd) | Jun 13, 2023 |
| MSI           | H510M PRO                   | Desktop     | [08e44766fe](https://linux-hardware.org/?probe=08e44766fe) | Jun 13, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [3528d095e0](https://linux-hardware.org/?probe=3528d095e0) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2db1bbb316](https://linux-hardware.org/?probe=2db1bbb316) | Jun 13, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [6febc3ef2e](https://linux-hardware.org/?probe=6febc3ef2e) | Jun 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [dc3b9443ef](https://linux-hardware.org/?probe=dc3b9443ef) | Jun 13, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [e18c667ddc](https://linux-hardware.org/?probe=e18c667ddc) | Jun 13, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [ceae8212bf](https://linux-hardware.org/?probe=ceae8212bf) | Jun 12, 2023 |
| Toshiba       | Satellite R630              | Notebook    | [aac5cdbb4f](https://linux-hardware.org/?probe=aac5cdbb4f) | Jun 12, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59a9e7e2e8](https://linux-hardware.org/?probe=59a9e7e2e8) | Jun 11, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [d71e612bbb](https://linux-hardware.org/?probe=d71e612bbb) | Jun 11, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [1de48a4515](https://linux-hardware.org/?probe=1de48a4515) | Jun 10, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [c31b0e5f30](https://linux-hardware.org/?probe=c31b0e5f30) | Jun 10, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [95bc101c80](https://linux-hardware.org/?probe=95bc101c80) | Jun 09, 2023 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [3371099509](https://linux-hardware.org/?probe=3371099509) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [662e292b55](https://linux-hardware.org/?probe=662e292b55) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [024a1f80a1](https://linux-hardware.org/?probe=024a1f80a1) | Jun 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [53cb8df21f](https://linux-hardware.org/?probe=53cb8df21f) | Jun 06, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [ba0e7c7d59](https://linux-hardware.org/?probe=ba0e7c7d59) | Jun 04, 2023 |
| Acer          | AO722                       | Notebook    | [b8f2636f02](https://linux-hardware.org/?probe=b8f2636f02) | Jun 04, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [5ee3eec233](https://linux-hardware.org/?probe=5ee3eec233) | Jun 03, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Hometech      | Alfa 470C                   | Notebook    | [ee3bd9eb81](https://linux-hardware.org/?probe=ee3bd9eb81) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3a51aa06b9](https://linux-hardware.org/?probe=3a51aa06b9) | Jun 02, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [a7c067f896](https://linux-hardware.org/?probe=a7c067f896) | Jun 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [d61bd0903e](https://linux-hardware.org/?probe=d61bd0903e) | Jun 02, 2023 |
| Dell          | G3 3579                     | Notebook    | [4e5b0f9800](https://linux-hardware.org/?probe=4e5b0f9800) | May 31, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [f6f91b620c](https://linux-hardware.org/?probe=f6f91b620c) | May 31, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [bb8f972443](https://linux-hardware.org/?probe=bb8f972443) | May 31, 2023 |
| Toshiba       | Satellite R630              | Notebook    | [5bf801ac1f](https://linux-hardware.org/?probe=5bf801ac1f) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [5839982a52](https://linux-hardware.org/?probe=5839982a52) | May 29, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [5bd3cb3a3a](https://linux-hardware.org/?probe=5bd3cb3a3a) | May 29, 2023 |
| Dell          | Latitude 5430               | Notebook    | [a0697218cc](https://linux-hardware.org/?probe=a0697218cc) | May 27, 2023 |
| Monster       | Huma H5 V3.1                | Notebook    | [ed569fe821](https://linux-hardware.org/?probe=ed569fe821) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| IX1401        | Unknown                     | Notebook    | [f1799b6c3a](https://linux-hardware.org/?probe=f1799b6c3a) | May 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [54bddcb324](https://linux-hardware.org/?probe=54bddcb324) | May 24, 2023 |
| ASUSTek       | Maximus V GENE              | Desktop     | [64085de9fe](https://linux-hardware.org/?probe=64085de9fe) | May 24, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [0c665ebdd8](https://linux-hardware.org/?probe=0c665ebdd8) | May 23, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [ef088af2df](https://linux-hardware.org/?probe=ef088af2df) | May 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S3XR00    | Notebook    | [0f80e19e5b](https://linux-hardware.org/?probe=0f80e19e5b) | May 23, 2023 |
| Medion        | E6224                       | Notebook    | [65c26a4a09](https://linux-hardware.org/?probe=65c26a4a09) | May 23, 2023 |
| Medion        | E6224                       | Notebook    | [8e10b22b1f](https://linux-hardware.org/?probe=8e10b22b1f) | May 23, 2023 |
| Lenovo        | Unknown                     | Notebook    | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [d784b0822d](https://linux-hardware.org/?probe=d784b0822d) | May 22, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [8b3acda484](https://linux-hardware.org/?probe=8b3acda484) | May 22, 2023 |
| ASUSTek       | X555LNB                     | Notebook    | [a1aa3cf4b2](https://linux-hardware.org/?probe=a1aa3cf4b2) | May 22, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [3a448141db](https://linux-hardware.org/?probe=3a448141db) | May 21, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VU_GZ3... | Tablet      | [3e94769b79](https://linux-hardware.org/?probe=3e94769b79) | May 20, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [6bce5f1ff0](https://linux-hardware.org/?probe=6bce5f1ff0) | May 20, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [e33e3678c6](https://linux-hardware.org/?probe=e33e3678c6) | May 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [cb9ac11e18](https://linux-hardware.org/?probe=cb9ac11e18) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | Notebook    | [d07aa12d74](https://linux-hardware.org/?probe=d07aa12d74) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | Notebook    | [d2908ee6a9](https://linux-hardware.org/?probe=d2908ee6a9) | May 17, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [5553ae2ec9](https://linux-hardware.org/?probe=5553ae2ec9) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [f297fbda85](https://linux-hardware.org/?probe=f297fbda85) | May 16, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [ce2cf2a89a](https://linux-hardware.org/?probe=ce2cf2a89a) | May 15, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [c585628bc8](https://linux-hardware.org/?probe=c585628bc8) | May 14, 2023 |
| Unknown       | Unknown                     | Phone       | [1276781281](https://linux-hardware.org/?probe=1276781281) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c164fc1080](https://linux-hardware.org/?probe=c164fc1080) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b4c4fde79d](https://linux-hardware.org/?probe=b4c4fde79d) | May 14, 2023 |
| MSI           | GS75 Stealth 10SFS          | Notebook    | [a2116b61ea](https://linux-hardware.org/?probe=a2116b61ea) | May 14, 2023 |
| ASUSTek       | S451LB                      | Notebook    | [f43e2b2679](https://linux-hardware.org/?probe=f43e2b2679) | May 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [194f7f96e5](https://linux-hardware.org/?probe=194f7f96e5) | May 13, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [16954b8f95](https://linux-hardware.org/?probe=16954b8f95) | May 13, 2023 |
| Acer          | Aspire A315-58G             | Notebook    | [996701dcbd](https://linux-hardware.org/?probe=996701dcbd) | May 12, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [71f2dc616d](https://linux-hardware.org/?probe=71f2dc616d) | May 12, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6b9e3d06b1](https://linux-hardware.org/?probe=6b9e3d06b1) | May 11, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a7cc3561af](https://linux-hardware.org/?probe=a7cc3561af) | May 10, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [68720e9d6b](https://linux-hardware.org/?probe=68720e9d6b) | May 10, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [c2392e1f40](https://linux-hardware.org/?probe=c2392e1f40) | May 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [fa734dc49a](https://linux-hardware.org/?probe=fa734dc49a) | May 09, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [4dc1934f7b](https://linux-hardware.org/?probe=4dc1934f7b) | May 09, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6a93900fb9](https://linux-hardware.org/?probe=6a93900fb9) | May 07, 2023 |
| HT            | C20C WSTKA001               | Notebook    | [a7ffbb2fe3](https://linux-hardware.org/?probe=a7ffbb2fe3) | May 07, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [93aaae065b](https://linux-hardware.org/?probe=93aaae065b) | May 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [2a8bbbef3d](https://linux-hardware.org/?probe=2a8bbbef3d) | May 06, 2023 |
| Monster       | ABRA A5 V16.4               | Notebook    | [a5507638d0](https://linux-hardware.org/?probe=a5507638d0) | May 06, 2023 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [fff5650658](https://linux-hardware.org/?probe=fff5650658) | May 05, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [e788d3fee0](https://linux-hardware.org/?probe=e788d3fee0) | May 04, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [99870f2da6](https://linux-hardware.org/?probe=99870f2da6) | May 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [c68576fce8](https://linux-hardware.org/?probe=c68576fce8) | Apr 30, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [1c67ba3f8a](https://linux-hardware.org/?probe=1c67ba3f8a) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [6f6a016997](https://linux-hardware.org/?probe=6f6a016997) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Monster       | TULPAR T5 V21.7             | Notebook    | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [8c4ba894b4](https://linux-hardware.org/?probe=8c4ba894b4) | Apr 28, 2023 |
| Supermicro    | X12SPL-F                    | Server      | [8382988ca9](https://linux-hardware.org/?probe=8382988ca9) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| Lenovo        | QIWY3                       | Notebook    | [a7c04857e4](https://linux-hardware.org/?probe=a7c04857e4) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [d49ace71b4](https://linux-hardware.org/?probe=d49ace71b4) | Apr 27, 2023 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [aca5bf366f](https://linux-hardware.org/?probe=aca5bf366f) | Apr 26, 2023 |
| IBM           | P4M900/VT8251/DME1737       | Desktop     | [8cbd1dce35](https://linux-hardware.org/?probe=8cbd1dce35) | Apr 26, 2023 |
| IBM           | P4M900/VT8251/DME1737       | Desktop     | [ef0df72346](https://linux-hardware.org/?probe=ef0df72346) | Apr 26, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [f9671dc0a4](https://linux-hardware.org/?probe=f9671dc0a4) | Apr 26, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [2b0ee4d542](https://linux-hardware.org/?probe=2b0ee4d542) | Apr 26, 2023 |
| HP            | 240 G8                      | Notebook    | [ab322ed08e](https://linux-hardware.org/?probe=ab322ed08e) | Apr 25, 2023 |
| HP            | 240 G8                      | Notebook    | [8cf9892fe9](https://linux-hardware.org/?probe=8cf9892fe9) | Apr 25, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [a433dd6737](https://linux-hardware.org/?probe=a433dd6737) | Apr 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [9e6ce2eb71](https://linux-hardware.org/?probe=9e6ce2eb71) | Apr 25, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [2d0269750e](https://linux-hardware.org/?probe=2d0269750e) | Apr 24, 2023 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [6a6beb844d](https://linux-hardware.org/?probe=6a6beb844d) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [66d61baf71](https://linux-hardware.org/?probe=66d61baf71) | Apr 23, 2023 |
| HP            | ProBook 4540s               | Notebook    | [854f17fcac](https://linux-hardware.org/?probe=854f17fcac) | Apr 23, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [bb1a40d839](https://linux-hardware.org/?probe=bb1a40d839) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS       | Desktop     | [28631c09aa](https://linux-hardware.org/?probe=28631c09aa) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [8b18bb529f](https://linux-hardware.org/?probe=8b18bb529f) | Apr 21, 2023 |
| HP            | ZBook Studio x360 G5        | Convertible | [6d24ab2a04](https://linux-hardware.org/?probe=6d24ab2a04) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [990cf467d8](https://linux-hardware.org/?probe=990cf467d8) | Apr 19, 2023 |
| Intel         | NUC5CPYB H61145-407         | Mini pc     | [43fc15779a](https://linux-hardware.org/?probe=43fc15779a) | Apr 19, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [10e8cc92f1](https://linux-hardware.org/?probe=10e8cc92f1) | Apr 19, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [1e59096b86](https://linux-hardware.org/?probe=1e59096b86) | Apr 19, 2023 |
| Lenovo        | Unknown                     | Notebook    | [99a0c76ea9](https://linux-hardware.org/?probe=99a0c76ea9) | Apr 18, 2023 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| Lenovo        | Unknown                     | Notebook    | [653cf225b8](https://linux-hardware.org/?probe=653cf225b8) | Apr 17, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3d14cefd78](https://linux-hardware.org/?probe=3d14cefd78) | Apr 17, 2023 |
| ASUSTek       | X55A                        | Notebook    | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [da31814636](https://linux-hardware.org/?probe=da31814636) | Apr 15, 2023 |
| Biostar       | G31D-M7                     | Desktop     | [bb518a8623](https://linux-hardware.org/?probe=bb518a8623) | Apr 14, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [6e07b5d9d1](https://linux-hardware.org/?probe=6e07b5d9d1) | Apr 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [3f719938aa](https://linux-hardware.org/?probe=3f719938aa) | Apr 14, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [a23067158f](https://linux-hardware.org/?probe=a23067158f) | Apr 14, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [62dd8e069f](https://linux-hardware.org/?probe=62dd8e069f) | Apr 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [cc0b87e611](https://linux-hardware.org/?probe=cc0b87e611) | Apr 13, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [5e772c9376](https://linux-hardware.org/?probe=5e772c9376) | Apr 13, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [8152bff1b3](https://linux-hardware.org/?probe=8152bff1b3) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| Sony          | VPCEB3J1E                   | Notebook    | [1405405cbb](https://linux-hardware.org/?probe=1405405cbb) | Apr 11, 2023 |
| HP            | 18E6                        | Desktop     | [d7cf5918eb](https://linux-hardware.org/?probe=d7cf5918eb) | Apr 11, 2023 |
| MSI           | 970A GAMING PRO CARBON      | Desktop     | [b6cae4ec58](https://linux-hardware.org/?probe=b6cae4ec58) | Apr 11, 2023 |
| HP            | 829C                        | All in one  | [91f5a10ba1](https://linux-hardware.org/?probe=91f5a10ba1) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2a108e9eed](https://linux-hardware.org/?probe=2a108e9eed) | Apr 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fc305814c4](https://linux-hardware.org/?probe=fc305814c4) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [11ecb91fec](https://linux-hardware.org/?probe=11ecb91fec) | Apr 09, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [396850fd22](https://linux-hardware.org/?probe=396850fd22) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c2e1cb3f46](https://linux-hardware.org/?probe=c2e1cb3f46) | Apr 09, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [023591084f](https://linux-hardware.org/?probe=023591084f) | Apr 07, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [683dea4da0](https://linux-hardware.org/?probe=683dea4da0) | Apr 07, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5349814c06](https://linux-hardware.org/?probe=5349814c06) | Apr 07, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [ab450c0ddd](https://linux-hardware.org/?probe=ab450c0ddd) | Apr 06, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [5d0731fb7a](https://linux-hardware.org/?probe=5d0731fb7a) | Apr 05, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| Acer          | Aspire 5220                 | Notebook    | [d22076fd54](https://linux-hardware.org/?probe=d22076fd54) | Apr 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b55be43d4c](https://linux-hardware.org/?probe=b55be43d4c) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [e6a732e9b0](https://linux-hardware.org/?probe=e6a732e9b0) | Apr 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [78bda6a16c](https://linux-hardware.org/?probe=78bda6a16c) | Apr 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [38dc8922e4](https://linux-hardware.org/?probe=38dc8922e4) | Apr 03, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d928981385](https://linux-hardware.org/?probe=d928981385) | Apr 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [bc5dd02c14](https://linux-hardware.org/?probe=bc5dd02c14) | Apr 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [804bf25c27](https://linux-hardware.org/?probe=804bf25c27) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | Notebook    | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [9148a1d487](https://linux-hardware.org/?probe=9148a1d487) | Apr 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6eb533f1d7](https://linux-hardware.org/?probe=6eb533f1d7) | Apr 01, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [d527726a1c](https://linux-hardware.org/?probe=d527726a1c) | Mar 31, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [6915349237](https://linux-hardware.org/?probe=6915349237) | Mar 31, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [282031e979](https://linux-hardware.org/?probe=282031e979) | Mar 30, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [920f4a2dc2](https://linux-hardware.org/?probe=920f4a2dc2) | Mar 30, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [159d154fca](https://linux-hardware.org/?probe=159d154fca) | Mar 30, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [31a96824ea](https://linux-hardware.org/?probe=31a96824ea) | Mar 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [b960038661](https://linux-hardware.org/?probe=b960038661) | Mar 27, 2023 |
| Pegatron      | IPMIP-H55-GEN               | Desktop     | [7dcf9e9b51](https://linux-hardware.org/?probe=7dcf9e9b51) | Mar 27, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Turkey/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 240       | 10%     |
| Ubuntu 22.04                 | 185       | 7.71%   |
| Ubuntu 18.04                 | 170       | 7.08%   |
| Arch Rolling                 | 75        | 3.13%   |
| ArcoLinux Rolling            | 51        | 2.13%   |
| OpenMandriva 4.3             | 43        | 1.79%   |
| Fedora 38                    | 43        | 1.79%   |
| Fedora 39                    | 40        | 1.67%   |
| Debian 11                    | 40        | 1.67%   |
| Zorin 16                     | 38        | 1.58%   |
| Pop!_OS 22.04                | 36        | 1.5%    |
| Fedora 37                    | 35        | 1.46%   |
| Fedora 36                    | 34        | 1.42%   |
| Arch                         | 33        | 1.38%   |
| EndeavourOS Rolling          | 32        | 1.33%   |
| Manjaro                      | 31        | 1.29%   |
| Debian 12                    | 31        | 1.29%   |
| Linux Mint 21.2              | 28        | 1.17%   |
| Fedora 33                    | 26        | 1.08%   |
| OpenMandriva 23.08           | 25        | 1.04%   |
| Linux Mint 21.1              | 25        | 1.04%   |
| KDE neon 20.04               | 25        | 1.04%   |
| Ubuntu 23.10                 | 23        | 0.96%   |
| Linux Mint 20.3              | 23        | 0.96%   |
| Fedora 35                    | 22        | 0.92%   |
| OpenMandriva 23.01           | 21        | 0.88%   |
| Linux Mint 20.1              | 19        | 0.79%   |
| Ubuntu 21.10                 | 18        | 0.75%   |
| Linux Mint 21                | 18        | 0.75%   |
| Linux Mint 20                | 18        | 0.75%   |
| Elementary 6.1               | 17        | 0.71%   |
| Ubuntu 23.04                 | 16        | 0.67%   |
| ROSA R10                     | 16        | 0.67%   |
| Fedora 34                    | 16        | 0.67%   |
| KDE neon 22.04               | 15        | 0.63%   |
| openSUSE Tumbleweed-XXXXXXXX | 14        | 0.58%   |
| Linux Mint 20.2              | 14        | 0.58%   |
| Xero Rolling                 | 13        | 0.54%   |
| Ubuntu 22.10                 | 13        | 0.54%   |
| Ubuntu 20.10                 | 13        | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 717       | 31.34%  |
| Fedora        | 207       | 9.05%   |
| Linux Mint    | 173       | 7.56%   |
| OpenMandriva  | 130       | 5.68%   |
| Arch          | 105       | 4.59%   |
| Debian        | 102       | 4.46%   |
| Pop!_OS       | 71        | 3.1%    |
| Manjaro       | 71        | 3.1%    |
| Pardus        | 68        | 2.97%   |
| Zorin         | 58        | 2.53%   |
| ArcoLinux     | 54        | 2.36%   |
| KDE neon      | 45        | 1.97%   |
| Kubuntu       | 40        | 1.75%   |
| Kali          | 35        | 1.53%   |
| ROSA          | 34        | 1.49%   |
| EndeavourOS   | 33        | 1.44%   |
| Elementary    | 32        | 1.4%    |
| Endless       | 27        | 1.18%   |
| Xubuntu       | 25        | 1.09%   |
| openSUSE      | 20        | 0.87%   |
| Lubuntu       | 20        | 0.87%   |
| Ubuntu Unity  | 15        | 0.66%   |
| Ubuntu MATE   | 14        | 0.61%   |
| Xero          | 13        | 0.57%   |
| Gentoo        | 13        | 0.57%   |
| Garuda Linux  | 11        | 0.48%   |
| LMDE          | 10        | 0.44%   |
| MX            | 9         | 0.39%   |
| Clear Linux   | 9         | 0.39%   |
| PostmarketOS  | 8         | 0.35%   |
| Nobara        | 7         | 0.31%   |
| Artix         | 7         | 0.31%   |
| Deepin        | 6         | 0.26%   |
| SteamOS       | 5         | 0.22%   |
| Parrot        | 5         | 0.22%   |
| CentOS        | 5         | 0.22%   |
| CachyOS       | 5         | 0.22%   |
| Archman       | 5         | 0.22%   |
| Alpine        | 5         | 0.22%   |
| Ubuntu Budgie | 4         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 41        | 1.58%   |
| 6.4.11-desktop-1omv2390  | 25        | 0.96%   |
| 5.4.0-42-generic         | 25        | 0.96%   |
| 5.4.0-58-generic         | 22        | 0.85%   |
| 6.1.1-desktop-1omv2290   | 21        | 0.81%   |
| 5.15.0-56-generic        | 21        | 0.81%   |
| 5.15.0-58-generic        | 20        | 0.77%   |
| 6.2.0-26-generic         | 18        | 0.69%   |
| 5.0.0-37-generic         | 15        | 0.58%   |
| 5.4.0-48-generic         | 14        | 0.54%   |
| 5.4.0-26-generic         | 14        | 0.54%   |
| 5.15.0-52-generic        | 14        | 0.54%   |
| 4.18.0-15-generic        | 14        | 0.54%   |
| 6.6.2-desktop-1omv2390   | 13        | 0.5%    |
| 5.3.0-40-generic         | 13        | 0.5%    |
| 5.15.0-48-generic        | 13        | 0.5%    |
| 5.10.0-21-amd64          | 13        | 0.5%    |
| 6.1.0-17-amd64           | 12        | 0.46%   |
| 5.19.0-32-generic        | 12        | 0.46%   |
| 5.15.0-43-generic        | 12        | 0.46%   |
| 5.10.14-desktop-1omv4002 | 12        | 0.46%   |
| 6.5.0-26-generic         | 11        | 0.42%   |
| 6.2.0-32-generic         | 11        | 0.42%   |
| 5.8.0-14-generic         | 11        | 0.42%   |
| 5.3.0-46-generic         | 11        | 0.42%   |
| 5.15.0-46-generic        | 11        | 0.42%   |
| 5.11.0-27-generic        | 11        | 0.42%   |
| 6.5.0-14-generic         | 10        | 0.39%   |
| 6.2.0-20-generic         | 10        | 0.39%   |
| 5.8.0-43-generic         | 10        | 0.39%   |
| 5.4.0-37-generic         | 10        | 0.39%   |
| 5.4.0-29-generic         | 10        | 0.39%   |
| 5.15.0-27-generic        | 10        | 0.39%   |
| 5.13.0-39-generic        | 10        | 0.39%   |
| 5.13.0-30-generic        | 10        | 0.39%   |
| 6.2.6-desktop-1omv2390   | 9         | 0.35%   |
| 5.8.0-48-generic         | 9         | 0.35%   |
| 5.8.0-44-generic         | 9         | 0.35%   |
| 5.4.0-74-generic         | 9         | 0.35%   |
| 5.4.0-73-generic         | 9         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 285       | 11.41%  |
| 5.15.0  | 230       | 9.21%   |
| 5.10.0  | 96        | 3.84%   |
| 5.8.0   | 94        | 3.76%   |
| 6.2.0   | 88        | 3.52%   |
| 4.15.0  | 86        | 3.44%   |
| 5.11.0  | 85        | 3.4%    |
| 5.13.0  | 76        | 3.04%   |
| 6.5.0   | 74        | 2.96%   |
| 5.3.0   | 65        | 2.6%    |
| 5.19.0  | 59        | 2.36%   |
| 5.0.0   | 57        | 2.28%   |
| 6.1.0   | 56        | 2.24%   |
| 4.18.0  | 46        | 1.84%   |
| 5.16.7  | 43        | 1.72%   |
| 4.19.0  | 30        | 1.2%    |
| 6.4.11  | 29        | 1.16%   |
| 6.1.1   | 25        | 1%      |
| 6.2.6   | 19        | 0.76%   |
| 6.6.2   | 16        | 0.64%   |
| 6.4.12  | 15        | 0.6%    |
| 5.10.14 | 13        | 0.52%   |
| 6.4.6   | 11        | 0.44%   |
| 6.0.12  | 11        | 0.44%   |
| 6.5.6   | 10        | 0.4%    |
| 5.17.5  | 10        | 0.4%    |
| 6.2.9   | 9         | 0.36%   |
| 5.6.0   | 9         | 0.36%   |
| 5.14.0  | 9         | 0.36%   |
| 4.9.60  | 9         | 0.36%   |
| 6.7.9   | 8         | 0.32%   |
| 6.3.8   | 8         | 0.32%   |
| 6.8.0   | 7         | 0.28%   |
| 6.6.9   | 7         | 0.28%   |
| 6.5.5   | 7         | 0.28%   |
| 6.4.3   | 7         | 0.28%   |
| 6.2.10  | 7         | 0.28%   |
| 5.18.0  | 7         | 0.28%   |
| 5.17.1  | 7         | 0.28%   |
| 5.11.11 | 7         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 302       | 12.33%  |
| 5.15    | 291       | 11.88%  |
| 6.2     | 148       | 6.04%   |
| 5.10    | 146       | 5.96%   |
| 6.1     | 135       | 5.51%   |
| 6.5     | 121       | 4.94%   |
| 5.11    | 116       | 4.74%   |
| 5.8     | 111       | 4.53%   |
| 6.4     | 89        | 3.63%   |
| 5.13    | 88        | 3.59%   |
| 4.15    | 86        | 3.51%   |
| 5.19    | 81        | 3.31%   |
| 5.16    | 77        | 3.14%   |
| 5.3     | 76        | 3.1%    |
| 6.6     | 70        | 2.86%   |
| 5.0     | 59        | 2.41%   |
| 6.0     | 49        | 2%      |
| 4.18    | 49        | 2%      |
| 6.3     | 37        | 1.51%   |
| 5.18    | 36        | 1.47%   |
| 6.7     | 34        | 1.39%   |
| 4.19    | 32        | 1.31%   |
| 5.17    | 31        | 1.27%   |
| 6.8     | 29        | 1.18%   |
| 5.9     | 29        | 1.18%   |
| 4.9     | 23        | 0.94%   |
| 5.14    | 22        | 0.9%    |
| 5.6     | 17        | 0.69%   |
| 5.7     | 16        | 0.65%   |
| 5.12    | 16        | 0.65%   |
| 5.5     | 5         | 0.2%    |
| 4.4     | 5         | 0.2%    |
| 5.2     | 4         | 0.16%   |
| 5.1     | 4         | 0.16%   |
| 4.14    | 3         | 0.12%   |
| 4.1     | 3         | 0.12%   |
| 4.13    | 2         | 0.08%   |
| 4.10    | 2         | 0.08%   |
| 6.0.5   | 1         | 0.04%   |
| 4.16    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2086      | 96.44%  |
| i686    | 49        | 2.27%   |
| aarch64 | 19        | 0.88%   |
| armv7l  | 9         | 0.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1028      | 45.07%  |
| KDE5             | 368       | 16.13%  |
| Unknown          | 238       | 10.43%  |
| XFCE             | 230       | 10.08%  |
| X-Cinnamon       | 121       | 5.3%    |
| MATE             | 47        | 2.06%   |
| KDE              | 40        | 1.75%   |
| Pantheon         | 32        | 1.4%    |
| LXQt             | 28        | 1.23%   |
| Cinnamon         | 21        | 0.92%   |
| KDE4             | 17        | 0.75%   |
| i3               | 16        | 0.7%    |
| Unity            | 15        | 0.66%   |
| KDE6             | 11        | 0.48%   |
| LXDE             | 10        | 0.44%   |
| Deepin           | 10        | 0.44%   |
| Hyprland         | 9         | 0.39%   |
| sway             | 8         | 0.35%   |
| Budgie           | 6         | 0.26%   |
| Trinity          | 4         | 0.18%   |
| GNOME Classic    | 3         | 0.13%   |
| DWM              | 3         | 0.13%   |
| xmonad           | 2         | 0.09%   |
| openbox          | 2         | 0.09%   |
| bspwm            | 2         | 0.09%   |
| qtile            | 1         | 0.04%   |
| Phosh:GNOME      | 1         | 0.04%   |
| LXDE-pi-wayfire  | 1         | 0.04%   |
| Lingmo           | 1         | 0.04%   |
| lightdm-xsession | 1         | 0.04%   |
| GNOME Flashback  | 1         | 0.04%   |
| Endless:GNOME    | 1         | 0.04%   |
| default          | 1         | 0.04%   |
| DDE              | 1         | 0.04%   |
| awesome          | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1579      | 70.18%  |
| Wayland | 526       | 23.38%  |
| Unknown | 102       | 4.53%   |
| Tty     | 43        | 1.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1019      | 44.83%  |
| SDDM    | 346       | 15.22%  |
| GDM3    | 316       | 13.9%   |
| GDM     | 267       | 11.75%  |
| LightDM | 238       | 10.47%  |
| TDM     | 62        | 2.73%   |
| KDM     | 17        | 0.75%   |
| XDM     | 2         | 0.09%   |
| SLiM    | 2         | 0.09%   |
| Ly      | 2         | 0.09%   |
| LXDM    | 2         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 987       | 44.62%  |
| tr_TR       | 868       | 39.24%  |
| Unknown     | 199       | 9%      |
| en_GB       | 64        | 2.89%   |
| C           | 40        | 1.81%   |
| ru_RU       | 18        | 0.81%   |
| de_DE       | 7         | 0.32%   |
| POSIX       | 3         | 0.14%   |
| ar_EG       | 3         | 0.14%   |
| en_US.UTF8  | 2         | 0.09%   |
| en_CA       | 2         | 0.09%   |
| zh_CN       | 1         | 0.05%   |
| tr_TR.UTF8  | 1         | 0.05%   |
| tr_CY       | 1         | 0.05%   |
| ru_UA       | 1         | 0.05%   |
| nl_BE       | 1         | 0.05%   |
| fr_FR       | 1         | 0.05%   |
| fa_IR       | 1         | 0.05%   |
| es_ES       | 1         | 0.05%   |
| en_US-UTF-8 | 1         | 0.05%   |
| en_NZ       | 1         | 0.05%   |
| en_IE       | 1         | 0.05%   |
| en_GB.UTF8  | 1         | 0.05%   |
| en_DK       | 1         | 0.05%   |
| en_AU       | 1         | 0.05%   |
| en_150      | 1         | 0.05%   |
| el_GR       | 1         | 0.05%   |
| de_AT       | 1         | 0.05%   |
| C.UTF8      | 1         | 0.05%   |
| az_AZ       | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1198      | 54.13%  |
| BIOS | 1015      | 45.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1597      | 70.79%  |
| Btrfs   | 302       | 13.39%  |
| Overlay | 143       | 6.34%   |
| Tmpfs   | 99        | 4.39%   |
| Unknown | 60        | 2.66%   |
| Xfs     | 20        | 0.89%   |
| Ext2    | 14        | 0.62%   |
| Zfs     | 12        | 0.53%   |
| Ext3    | 4         | 0.18%   |
| F2fs    | 3         | 0.13%   |
| Aufs    | 2         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1067      | 47.8%   |
| GPT     | 969       | 43.41%  |
| MBR     | 196       | 8.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1894      | 85.82%  |
| Yes       | 313       | 14.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1478      | 66.4%   |
| Yes       | 748       | 33.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 383       | 17.72%  |
| Lenovo                  | 332       | 15.36%  |
| Hewlett-Packard         | 286       | 13.23%  |
| Dell                    | 160       | 7.4%    |
| MSI                     | 152       | 7.03%   |
| Acer                    | 133       | 6.15%   |
| Gigabyte Technology     | 113       | 5.23%   |
| Monster                 | 73        | 3.38%   |
| Toshiba                 | 62        | 2.87%   |
| HUAWEI                  | 56        | 2.59%   |
| Apple                   | 53        | 2.45%   |
| Casper                  | 42        | 1.94%   |
| Samsung Electronics     | 34        | 1.57%   |
| Sony                    | 33        | 1.53%   |
| Unknown                 | 27        | 1.25%   |
| Intel                   | 21        | 0.97%   |
| Pegatron                | 20        | 0.93%   |
| Packard Bell            | 18        | 0.83%   |
| ASRock                  | 15        | 0.69%   |
| Google                  | 12        | 0.56%   |
| Hometech                | 11        | 0.51%   |
| Clevo                   | 11        | 0.51%   |
| Foxconn                 | 8         | 0.37%   |
| ECS                     | 8         | 0.37%   |
| Fujitsu                 | 6         | 0.28%   |
| ARCELIK                 | 6         | 0.28%   |
| Raspberry Pi Foundation | 5         | 0.23%   |
| Fujitsu Siemens         | 5         | 0.23%   |
| Vestel                  | 4         | 0.19%   |
| Notebook                | 4         | 0.19%   |
| AMI                     | 4         | 0.19%   |
| Alienware               | 4         | 0.19%   |
| Valve                   | 3         | 0.14%   |
| Insyde                  | 3         | 0.14%   |
| Huanan                  | 3         | 0.14%   |
| HONOR                   | 3         | 0.14%   |
| Biostar                 | 3         | 0.14%   |
| Rockchip                | 2         | 0.09%   |
| Quanta                  | 2         | 0.09%   |
| Nvidia                  | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 37        | 1.71%   |
| HP Pavilion g6                       | 22        | 1.02%   |
| ASUS All Series                      | 13        | 0.6%    |
| Casper NIRVANA NOTEBOOK              | 12        | 0.56%   |
| HP Pavilion dv6                      | 9         | 0.42%   |
| HP Notebook                          | 9         | 0.42%   |
| HUAWEI BOD-WXX9                      | 8         | 0.37%   |
| Gigabyte B450M S2H                   | 8         | 0.37%   |
| HP Pavilion 15                       | 7         | 0.32%   |
| HP 15                                | 7         | 0.32%   |
| Casper EXCALIBUR G770                | 7         | 0.32%   |
| ASUS X550VX                          | 7         | 0.32%   |
| Acer Aspire 5750G                    | 7         | 0.32%   |
| MSI MS-7C02                          | 6         | 0.28%   |
| Lenovo V15 G2 ALC 82KD               | 6         | 0.28%   |
| Lenovo IdeaPad 3 15ITL6 82H8         | 6         | 0.28%   |
| Intel H55                            | 6         | 0.28%   |
| HUAWEI HVY-WXX9                      | 6         | 0.28%   |
| HP Pavilion Notebook                 | 6         | 0.28%   |
| ASUS X555UB                          | 6         | 0.28%   |
| Acer Nitro AN515-58                  | 6         | 0.28%   |
| Toshiba Satellite L655               | 5         | 0.23%   |
| MSI MS-7C52                          | 5         | 0.23%   |
| MSI MS-7996                          | 5         | 0.23%   |
| MSI MS-7693                          | 5         | 0.23%   |
| HUAWEI NBLK-WAX9X                    | 5         | 0.23%   |
| HUAWEI KLVL-WXX9                     | 5         | 0.23%   |
| HUAWEI BOHK-WAX9X                    | 5         | 0.23%   |
| HP G62                               | 5         | 0.23%   |
| HP 250 G3                            | 5         | 0.23%   |
| Gigabyte G31M-ES2L                   | 5         | 0.23%   |
| Gigabyte A320M-S2H                   | 5         | 0.23%   |
| Dell Inspiron 7577                   | 5         | 0.23%   |
| Dell Inspiron 3542                   | 5         | 0.23%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 5         | 0.23%   |
| ASUS N550JV                          | 5         | 0.23%   |
| Apple MacBookAir7,2                  | 5         | 0.23%   |
| Toshiba Satellite C650               | 4         | 0.19%   |
| Pegatron IPXSB-H61                   | 4         | 0.19%   |
| Pegatron A15                         | 4         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 111       | 5.13%   |
| Lenovo IdeaPad        | 83        | 3.84%   |
| Acer Aspire           | 78        | 3.61%   |
| HP Pavilion           | 74        | 3.42%   |
| Dell Inspiron         | 63        | 2.91%   |
| Toshiba Satellite     | 57        | 2.64%   |
| Monster ABRA          | 40        | 1.85%   |
| ASUS PRIME            | 39        | 1.8%    |
| ASUS ROG              | 38        | 1.76%   |
| Unknown               | 37        | 1.71%   |
| Dell Latitude         | 33        | 1.53%   |
| HP Laptop             | 31        | 1.43%   |
| ASUS VivoBook         | 30        | 1.39%   |
| ASUS TUF              | 26        | 1.2%    |
| HP ProBook            | 25        | 1.16%   |
| HP EliteBook          | 22        | 1.02%   |
| Casper NIRVANA        | 22        | 1.02%   |
| Monster TULPAR        | 21        | 0.97%   |
| Acer Nitro            | 21        | 0.97%   |
| Dell Vostro           | 20        | 0.93%   |
| Lenovo Yoga           | 19        | 0.88%   |
| HP 250                | 19        | 0.88%   |
| HP Victus             | 18        | 0.83%   |
| Packard Bell EasyNote | 17        | 0.79%   |
| Lenovo Legion         | 15        | 0.69%   |
| Gigabyte B450M        | 13        | 0.6%    |
| Dell Precision        | 13        | 0.6%    |
| ASUS All              | 13        | 0.6%    |
| HP Compaq             | 12        | 0.56%   |
| ASUS ASUS             | 12        | 0.56%   |
| Monster HUMA          | 11        | 0.51%   |
| Lenovo ThinkBook      | 11        | 0.51%   |
| Acer Swift            | 11        | 0.51%   |
| Lenovo V15            | 10        | 0.46%   |
| HP ENVY               | 10        | 0.46%   |
| Dell OptiPlex         | 10        | 0.46%   |
| Casper EXCALIBUR      | 10        | 0.46%   |
| HP Notebook           | 9         | 0.42%   |
| Dell G3               | 9         | 0.42%   |
| Lenovo ThinkCentre    | 8         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 226       | 10.45%  |
| 2018    | 192       | 8.88%   |
| 2019    | 188       | 8.7%    |
| 2021    | 169       | 7.82%   |
| 2017    | 154       | 7.12%   |
| 2011    | 142       | 6.57%   |
| 2012    | 140       | 6.48%   |
| 2013    | 131       | 6.06%   |
| 2010    | 117       | 5.41%   |
| 2014    | 115       | 5.32%   |
| 2022    | 106       | 4.9%    |
| 2015    | 106       | 4.9%    |
| 2016    | 101       | 4.67%   |
| 2009    | 68        | 3.15%   |
| 2008    | 61        | 2.82%   |
| 2023    | 50        | 2.31%   |
| 2007    | 40        | 1.85%   |
| Unknown | 29        | 1.34%   |
| 2006    | 18        | 0.83%   |
| 2005    | 6         | 0.28%   |
| 2024    | 1         | 0.05%   |
| 2004    | 1         | 0.05%   |
| 2003    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1513      | 69.98%  |
| Desktop        | 538       | 24.88%  |
| All in one     | 29        | 1.34%   |
| Convertible    | 28        | 1.3%    |
| System on chip | 16        | 0.74%   |
| Tablet         | 15        | 0.69%   |
| Mini pc        | 15        | 0.69%   |
| Server         | 5         | 0.23%   |
| Phone          | 3         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2020      | 92.11%  |
| Enabled  | 173       | 7.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2159      | 99.86%  |
| Yes  | 3         | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 561       | 25.51%  |
| 16.01-24.0      | 441       | 20.05%  |
| 8.01-16.0       | 416       | 18.92%  |
| 3.01-4.0        | 379       | 17.24%  |
| 32.01-64.0      | 153       | 6.96%   |
| 1.01-2.0        | 118       | 5.37%   |
| 2.01-3.0        | 42        | 1.91%   |
| 64.01-256.0     | 38        | 1.73%   |
| 24.01-32.0      | 34        | 1.55%   |
| 0.51-1.0        | 16        | 0.73%   |
| More than 256.0 | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 745       | 30.75%  |
| 2.01-3.0   | 634       | 26.17%  |
| 3.01-4.0   | 392       | 16.18%  |
| 4.01-8.0   | 390       | 16.1%   |
| 0.51-1.0   | 131       | 5.41%   |
| 8.01-16.0  | 91        | 3.76%   |
| 0.01-0.5   | 27        | 1.11%   |
| 16.01-24.0 | 7         | 0.29%   |
| 24.01-32.0 | 3         | 0.12%   |
| 32.01-64.0 | 2         | 0.08%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1396      | 62.94%  |
| 2      | 607       | 27.37%  |
| 3      | 129       | 5.82%   |
| 4      | 43        | 1.94%   |
| 5      | 20        | 0.9%    |
| 0      | 13        | 0.59%   |
| 7      | 6         | 0.27%   |
| 6      | 4         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1513      | 69.28%  |
| Yes       | 671       | 30.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1845      | 85.06%  |
| No        | 324       | 14.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1786      | 82.42%  |
| No        | 381       | 17.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1483      | 67.9%   |
| No        | 701       | 32.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Turkey  | 2162      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Istanbul            | 822       | 35.57%  |
| Ankara              | 318       | 13.76%  |
| Izmir               | 212       | 9.17%   |
| Bursa               | 101       | 4.37%   |
| Antalya             | 101       | 4.37%   |
| Adana               | 41        | 1.77%   |
| Konya               | 37        | 1.6%    |
| Kosekoy             | 34        | 1.47%   |
| Kayseri             | 28        | 1.21%   |
| Balıkesir          | 25        | 1.08%   |
| Mersin              | 24        | 1.04%   |
| İzmit              | 24        | 1.04%   |
| Gaziantep           | 23        | 1%      |
| Aydin               | 20        | 0.87%   |
| Mugla               | 18        | 0.78%   |
| Samsun              | 17        | 0.74%   |
| Denizli             | 17        | 0.74%   |
| Antakya             | 16        | 0.69%   |
| Tekirdağ           | 14        | 0.61%   |
| Magnesia ad Sipylum | 14        | 0.61%   |
| Adapazarı          | 13        | 0.56%   |
| Trabzon             | 12        | 0.52%   |
| Şişli             | 12        | 0.52%   |
| Çanakkale          | 10        | 0.43%   |
| Yalova              | 9         | 0.39%   |
| Ordu                | 9         | 0.39%   |
| Kartal              | 9         | 0.39%   |
| Diyarbakır         | 9         | 0.39%   |
| Osmaniye            | 8         | 0.35%   |
| Malatya             | 8         | 0.35%   |
| Kırklareli         | 8         | 0.35%   |
| Eskişehir          | 8         | 0.35%   |
| Erzurum             | 8         | 0.35%   |
| Zonguldak           | 7         | 0.3%    |
| Edirne              | 7         | 0.3%    |
| Batman              | 7         | 0.3%    |
| Van                 | 6         | 0.26%   |
| Sanliurfa           | 6         | 0.26%   |
| Cankaya             | 6         | 0.26%   |
| Alanya              | 6         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 465       | 660    | 15.21%  |
| Seagate                     | 392       | 502    | 12.82%  |
| WDC                         | 372       | 520    | 12.17%  |
| SanDisk                     | 273       | 334    | 8.93%   |
| Toshiba                     | 240       | 286    | 7.85%   |
| Kingston                    | 164       | 223    | 5.36%   |
| Unknown                     | 119       | 152    | 3.89%   |
| Micron Technology           | 77        | 88     | 2.52%   |
| SK hynix                    | 76        | 98     | 2.49%   |
| HGST                        | 70        | 79     | 2.29%   |
| Hitachi                     | 64        | 72     | 2.09%   |
| Intel                       | 58        | 75     | 1.9%    |
| Crucial                     | 55        | 68     | 1.8%    |
| China                       | 51        | 62     | 1.67%   |
| A-DATA Technology           | 44        | 51     | 1.44%   |
| KIOXIA                      | 37        | 46     | 1.21%   |
| Apple                       | 30        | 40     | 0.98%   |
| KIOXIA-EXCERIA              | 28        | 32     | 0.92%   |
| Corsair                     | 26        | 35     | 0.85%   |
| Kingston Technology Company | 24        | 31     | 0.79%   |
| Phison                      | 22        | 22     | 0.72%   |
| Silicon Motion              | 18        | 20     | 0.59%   |
| Phison Electronics          | 16        | 19     | 0.52%   |
| Fujitsu                     | 16        | 16     | 0.52%   |
| Micron/Crucial Technology   | 15        | 18     | 0.49%   |
| JAMESDONKEY                 | 15        | 16     | 0.49%   |
| HS-SSD-C100                 | 14        | 14     | 0.46%   |
| OCZ                         | 12        | 14     | 0.39%   |
| Lexar                       | 11        | 17     | 0.36%   |
| Team                        | 10        | 10     | 0.33%   |
| Netac                       | 10        | 11     | 0.33%   |
| Unknown                     | 10        | 11     | 0.33%   |
| UMIS                        | 9         | 11     | 0.29%   |
| LITEON                      | 8         | 9      | 0.26%   |
| Gigabyte Technology         | 8         | 15     | 0.26%   |
| ADATA Technology            | 8         | 11     | 0.26%   |
| Union Memory                | 7         | 15     | 0.23%   |
| JMicron Technology          | 7         | 7      | 0.23%   |
| Union Memory (Shenzhen)     | 6         | 10     | 0.2%    |
| TwinMOS                     | 6         | 7      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 48        | 1.47%   |
| SanDisk SSD PLUS 240GB                             | 44        | 1.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 37        | 1.13%   |
| HGST HTS721010A9E630 1TB                           | 37        | 1.13%   |
| Unknown MMC Card  32GB                             | 31        | 0.95%   |
| Toshiba MQ04ABF100 1TB                             | 25        | 0.77%   |
| Toshiba MQ01ABD100 1TB                             | 25        | 0.77%   |
| Toshiba MQ01ABF050 500GB                           | 22        | 0.67%   |
| Seagate ST500DM002-1BD142 500GB                    | 22        | 0.67%   |
| Samsung SSD 860 EVO 250GB                          | 21        | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 19        | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB                     | 19        | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 19        | 0.58%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 18        | 0.55%   |
| Seagate ST500LT012-1DG142 500GB                    | 17        | 0.52%   |
| SanDisk SSD PLUS 120GB                             | 17        | 0.52%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 16        | 0.49%   |
| Samsung NVMe SSD Drive 512GB                       | 15        | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 14        | 0.43%   |
| Toshiba MQ01ABD075 752GB                           | 14        | 0.43%   |
| Kingston SA400S37240G 240GB SSD                    | 14        | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 13        | 0.4%    |
| Seagate ST9500325AS 500GB                          | 13        | 0.4%    |
| Seagate ST1000LM049-2GH172 1TB                     | 13        | 0.4%    |
| Kingston SV300S37A120G 120GB SSD                   | 13        | 0.4%    |
| SanDisk NVMe SSD Drive 256GB                       | 12        | 0.37%   |
| Samsung SSD 860 EVO 500GB                          | 12        | 0.37%   |
| KIOXIA-EXCERIA SATA SSD 240GB                      | 12        | 0.37%   |
| A-DATA SU650 120GB SSD                             | 12        | 0.37%   |
| Unknown MMC Card  64GB                             | 11        | 0.34%   |
| Toshiba TR200 240GB SSD                            | 11        | 0.34%   |
| Seagate ST3500418AS 500GB                          | 11        | 0.34%   |
| Seagate Expansion 2TB                              | 11        | 0.34%   |
| SanDisk SSD PLUS 480GB                             | 11        | 0.34%   |
| Kingston Company SNV2S1000G 1TB                    | 11        | 0.34%   |
| Intel NVMe SSD Drive 512GB                         | 11        | 0.34%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 10        | 0.31%   |
| Unknown SD/MMC/MS PRO 128GB                        | 10        | 0.31%   |
| Unknown MMC Card  128GB                            | 10        | 0.31%   |
| Seagate ST1000DM003-1ER162 1TB                     | 10        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives  | Percent |
|---------------------|-----------|---------|---------|
| Seagate             | 384       | 488     | 34.44%  |
| WDC                 | 291       | 415     | 26.1%   |
| Toshiba             | 178       | 202     | 15.96%  |
| Samsung Electronics | 81        | 105     | 7.26%   |
| HGST                | 70        | 79      | 6.28%   |
| Hitachi             | 64        | 72      | 5.74%   |
| Fujitsu             | 16        | 16      | 1.43%   |
| Unknown             | 10        | 13      | 0.9%    |
| Maxtor              | 5         | 5       | 0.45%   |
| Apple               | 5         | 9       | 0.45%   |
| JMicron Technology  | 3         | 3       | 0.27%   |
| Intenso             | 2         | 3       | 0.18%   |
| TO Exter            | 1         | 3       | 0.09%   |
| SABRENT             | 1         | 1       | 0.09%   |
| Initio              | 1         | Unknown | 0.09%   |
| ExcelStor           | 1         | 1       | 0.09%   |
| China               | 1         | 1       | 0.09%   |
| 128MB               | 1         | 1       | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 177       | 221    | 18.93%  |
| Samsung Electronics | 158       | 214    | 16.9%   |
| Kingston            | 119       | 165    | 12.73%  |
| WDC                 | 51        | 61     | 5.45%   |
| China               | 46        | 53     | 4.92%   |
| Crucial             | 37        | 48     | 3.96%   |
| A-DATA Technology   | 32        | 37     | 3.42%   |
| Toshiba             | 29        | 31     | 3.1%    |
| KIOXIA-EXCERIA      | 22        | 25     | 2.35%   |
| Micron Technology   | 21        | 25     | 2.25%   |
| Corsair             | 21        | 25     | 2.25%   |
| Apple               | 17        | 19     | 1.82%   |
| SK hynix            | 15        | 19     | 1.6%    |
| JAMESDONKEY         | 13        | 14     | 1.39%   |
| OCZ                 | 12        | 14     | 1.28%   |
| Intel               | 11        | 17     | 1.18%   |
| Netac               | 10        | 11     | 1.07%   |
| Lexar               | 9         | 15     | 0.96%   |
| Team                | 8         | 8      | 0.86%   |
| LITEON              | 8         | 9      | 0.86%   |
| Seagate             | 7         | 8      | 0.75%   |
| TwinMOS             | 6         | 7      | 0.64%   |
| Pioneer             | 6         | 22     | 0.64%   |
| KingSpec            | 6         | 6      | 0.64%   |
| HS-SSD-C100         | 6         | 6      | 0.64%   |
| Gigabyte Technology | 6         | 12     | 0.64%   |
| Hewlett-Packard     | 5         | 5      | 0.53%   |
| EZCOOL              | 5         | 6      | 0.53%   |
| SPCC                | 4         | 4      | 0.43%   |
| LITEONIT            | 4         | 5      | 0.43%   |
| HI-LEVEL            | 4         | 4      | 0.43%   |
| Turbox              | 3         | 3      | 0.32%   |
| Transcend           | 3         | 3      | 0.32%   |
| PNY                 | 3         | 3      | 0.32%   |
| Patriot             | 3         | 4      | 0.32%   |
| KingFast            | 3         | 5      | 0.32%   |
| GOODRAM             | 3         | 6      | 0.32%   |
| Apacer              | 3         | 3      | 0.32%   |
| 2.5"                | 3         | 3      | 0.32%   |
| WDC WDS2            | 2         | 2      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 992       | 1417   | 35.39%  |
| SSD     | 843       | 1189   | 30.07%  |
| NVMe    | 812       | 1133   | 28.97%  |
| MMC     | 110       | 141    | 3.92%   |
| Unknown | 46        | 61     | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1507      | 2557   | 60.02%  |
| NVMe | 812       | 1130   | 32.34%  |
| MMC  | 110       | 141    | 4.38%   |
| SAS  | 82        | 113    | 3.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1164      | 1726   | 64.13%  |
| 0.51-1.0   | 530       | 704    | 29.2%   |
| 1.01-2.0   | 71        | 107    | 3.91%   |
| 3.01-4.0   | 27        | 36     | 1.49%   |
| 2.01-3.0   | 12        | 18     | 0.66%   |
| 4.01-10.0  | 9         | 12     | 0.5%    |
| 10.01-20.0 | 1         | 1      | 0.06%   |
| 0          | 1         | 2      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 679       | 29.12%  |
| 251-500        | 532       | 22.81%  |
| 501-1000       | 313       | 13.42%  |
| 51-100         | 185       | 7.93%   |
| 1-20           | 171       | 7.33%   |
| 1001-2000      | 169       | 7.25%   |
| 21-50          | 128       | 5.49%   |
| More than 3000 | 60        | 2.57%   |
| 2001-3000      | 59        | 2.53%   |
| Unknown        | 36        | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 943       | 39.23%  |
| 21-50          | 481       | 20.01%  |
| 101-250        | 295       | 12.27%  |
| 51-100         | 291       | 12.1%   |
| 251-500        | 159       | 6.61%   |
| 501-1000       | 116       | 4.83%   |
| 1001-2000      | 48        | 2%      |
| Unknown        | 36        | 1.5%    |
| More than 3000 | 18        | 0.75%   |
| 2001-3000      | 17        | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 9         | 10     | 3.81%   |
| Seagate ST500LT012-1DG142 500GB       | 6         | 8      | 2.54%   |
| Toshiba MQ01ABD100 1TB                | 5         | 5      | 2.12%   |
| SanDisk SSD PLUS 240GB                | 5         | 5      | 2.12%   |
| HGST HTS721010A9E630 1TB              | 5         | 6      | 2.12%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 4      | 1.69%   |
| Seagate ST1000LM014-SSHD-8GB          | 4         | 4      | 1.69%   |
| Kingston SV300S37A120G 120GB SSD      | 4         | 5      | 1.69%   |
| Toshiba MQ01ABF050 500GB              | 3         | 4      | 1.27%   |
| Toshiba MQ01ABD075 752GB              | 3         | 3      | 1.27%   |
| Toshiba MQ01ABD050 500GB              | 3         | 4      | 1.27%   |
| Toshiba MK3252GSX 320GB               | 3         | 3      | 1.27%   |
| Seagate ST9500325AS 500GB             | 3         | 3      | 1.27%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 1.27%   |
| Seagate ST1000DM003-1CH162 1TB        | 3         | 4      | 1.27%   |
| Samsung Electronics SSD 870 EVO 500GB | 3         | 5      | 1.27%   |
| Samsung Electronics HD161HJ 160GB     | 3         | 3      | 1.27%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 1.27%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 3      | 0.85%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 2      | 0.85%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 2         | 2      | 0.85%   |
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 0.85%   |
| Toshiba MQ02ABD100H 1TB               | 2         | 4      | 0.85%   |
| Toshiba DT01ACA050 500GB              | 2         | 2      | 0.85%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 0.85%   |
| Seagate ST9160821AS 160GB             | 2         | 2      | 0.85%   |
| Seagate ST3500630AS 500GB             | 2         | 2      | 0.85%   |
| Seagate ST3500418AS 500GB             | 2         | 4      | 0.85%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 3      | 0.85%   |
| SanDisk SDSSDX120GG25 120GB           | 2         | 2      | 0.85%   |
| Kingston SVP200S37A120G 120GB SSD     | 2         | 2      | 0.85%   |
| Kingston SUV400S37240G 240GB SSD      | 2         | 2      | 0.85%   |
| JMicron Technology Tech 250GB         | 2         | 2      | 0.85%   |
| Indilinx IND-S325S120G 120GB SSD      | 2         | 4      | 0.85%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.85%   |
| Hitachi HTS543232A7A384 320GB         | 2         | 2      | 0.85%   |
| Hitachi HTS542516K9SA00 160GB         | 2         | 2      | 0.85%   |
| Fujitsu MHY2120BH 120GB               | 2         | 2      | 0.85%   |
| 2.5" SATA SSD 3TG6-P 2TB              | 2         | 2      | 0.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 72     | 25.65%  |
| Toshiba             | 30        | 34     | 13.04%  |
| WDC                 | 28        | 34     | 12.17%  |
| Samsung Electronics | 18        | 23     | 7.83%   |
| Hitachi             | 17        | 17     | 7.39%   |
| SanDisk             | 13        | 14     | 5.65%   |
| HGST                | 12        | 13     | 5.22%   |
| Kingston            | 11        | 12     | 4.78%   |
| A-DATA Technology   | 9         | 9      | 3.91%   |
| Fujitsu             | 5         | 5      | 2.17%   |
| Maxtor              | 3         | 3      | 1.3%    |
| Crucial             | 3         | 3      | 1.3%    |
| China               | 3         | 3      | 1.3%    |
| SK hynix            | 2         | 3      | 0.87%   |
| JMicron Technology  | 2         | 2      | 0.87%   |
| Indilinx            | 2         | 4      | 0.87%   |
| 2.5"                | 2         | 2      | 0.87%   |
| SSD-S400            | 1         | 1      | 0.43%   |
| OCZ                 | 1         | 2      | 0.43%   |
| Micron Technology   | 1         | 1      | 0.43%   |
| LITEONIT            | 1         | 2      | 0.43%   |
| LITEON              | 1         | 1      | 0.43%   |
| JD                  | 1         | 1      | 0.43%   |
| Intenso             | 1         | 1      | 0.43%   |
| Intel               | 1         | 1      | 0.43%   |
| Corsair             | 1         | 2      | 0.43%   |
| C-S12               | 1         | 1      | 0.43%   |
| Apple               | 1         | 2      | 0.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 72     | 35.98%  |
| Toshiba             | 30        | 34     | 18.29%  |
| WDC                 | 25        | 30     | 15.24%  |
| Hitachi             | 17        | 17     | 10.37%  |
| Samsung Electronics | 12        | 15     | 7.32%   |
| HGST                | 12        | 13     | 7.32%   |
| Fujitsu             | 5         | 5      | 3.05%   |
| Maxtor              | 3         | 3      | 1.83%   |
| Apple               | 1         | 2      | 0.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 155       | 191    | 70.14%  |
| SSD     | 58        | 69     | 26.24%  |
| NVMe    | 6         | 6      | 2.71%   |
| Unknown | 2         | 2      | 0.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 25%     |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 25%     |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 25%     |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 25%     |
| HGST                | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1302      | 2245   | 54.94%  |
| Works    | 848       | 1424   | 35.78%  |
| Malfunc  | 216       | 268    | 9.11%   |
| Failed   | 4         | 4      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1421      | 52.47%  |
| AMD                                     | 355       | 13.11%  |
| Samsung Electronics                     | 268       | 9.9%    |
| SanDisk                                 | 120       | 4.43%   |
| Kingston Technology Company             | 66        | 2.44%   |
| SK hynix                                | 59        | 2.18%   |
| Micron Technology                       | 56        | 2.07%   |
| KIOXIA                                  | 49        | 1.81%   |
| Phison Electronics                      | 47        | 1.74%   |
| Micron/Crucial Technology               | 31        | 1.14%   |
| Toshiba America Info Systems            | 27        | 1%      |
| Silicon Motion                          | 26        | 0.96%   |
| Nvidia                                  | 23        | 0.85%   |
| Marvell Technology Group                | 20        | 0.74%   |
| Union Memory (Shenzhen)                 | 19        | 0.7%    |
| JMicron Technology                      | 19        | 0.7%    |
| ADATA Technology                        | 19        | 0.7%    |
| ASMedia Technology                      | 17        | 0.63%   |
| Silicon Integrated Systems [SiS]        | 13        | 0.48%   |
| Realtek Semiconductor                   | 11        | 0.41%   |
| Apple                                   | 7         | 0.26%   |
| Yangtze Memory Technologies             | 5         | 0.18%   |
| VIA Technologies                        | 4         | 0.15%   |
| Solidigm                                | 3         | 0.11%   |
| Solid State Storage Technology          | 3         | 0.11%   |
| Seagate Technology                      | 3         | 0.11%   |
| Lite-On Technology                      | 3         | 0.11%   |
| Innodisk                                | 3         | 0.11%   |
| Transcend                               | 2         | 0.07%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.07%   |
| LSI Logic / Symbios Logic               | 2         | 0.07%   |
| ULi Electronics                         | 1         | 0.04%   |
| Shenzhen Unionmemory Information System | 1         | 0.04%   |
| Shenzhen Longsys Electronics            | 1         | 0.04%   |
| Promise Technology                      | 1         | 0.04%   |
| OCZ Technology Group                    | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 242       | 7.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 126       | 4.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 110       | 3.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 105       | 3.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 87        | 2.85%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 83        | 2.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 77        | 2.52%   |
| AMD 400 Series Chipset SATA Controller                                         | 64        | 2.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 60        | 1.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 57        | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 57        | 1.87%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 52        | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 51        | 1.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 49        | 1.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 47        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 45        | 1.47%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 41        | 1.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 40        | 1.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 40        | 1.31%   |
| Intel Comet Lake SATA AHCI Controller                                          | 37        | 1.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 37        | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 34        | 1.11%   |
| Intel Tiger Lake-LP SATA Controller                                            | 31        | 1.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 31        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 31        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 31        | 1.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 26        | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 25        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 25        | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 24        | 0.79%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 24        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 24        | 0.79%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 23        | 0.75%   |
| Intel SSD 660P Series                                                          | 22        | 0.72%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 20        | 0.65%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 20        | 0.65%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 20        | 0.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 20        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 19        | 0.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 18        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1542      | 56.26%  |
| NVMe | 814       | 29.7%   |
| IDE  | 242       | 8.83%   |
| RAID | 141       | 5.14%   |
| SCSI | 2         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1634      | 75.58%  |
| AMD          | 498       | 23.03%  |
| ARM          | 28        | 1.3%    |
| CentaurHauls | 2         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 44        | 2.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 35        | 1.62%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 34        | 1.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 1.29%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 1.2%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 23        | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 23        | 1.06%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 23        | 1.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 1.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 1.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 20        | 0.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 20        | 0.92%   |
| ARM Processor                                 | 19        | 0.88%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 19        | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 18        | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 0.83%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 18        | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 17        | 0.78%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 17        | 0.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 16        | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.69%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 15        | 0.69%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 15        | 0.69%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 14        | 0.65%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 14        | 0.65%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 14        | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.6%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 13        | 0.6%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 13        | 0.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 13        | 0.6%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 13        | 0.6%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 12        | 0.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 0.55%   |
| Intel 12th Gen Core i7-12700H                 | 12        | 0.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 12        | 0.55%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 12        | 0.55%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 12        | 0.55%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 12        | 0.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 492       | 22.73%  |
| Intel Core i7           | 412       | 19.03%  |
| Other                   | 230       | 10.62%  |
| AMD Ryzen 5             | 173       | 7.99%   |
| Intel Core i3           | 152       | 7.02%   |
| AMD Ryzen 7             | 117       | 5.4%    |
| Intel Celeron           | 81        | 3.74%   |
| Intel Core 2 Duo        | 75        | 3.46%   |
| Intel Atom              | 45        | 2.08%   |
| Intel Pentium           | 44        | 2.03%   |
| AMD Ryzen 3             | 32        | 1.48%   |
| Intel Xeon              | 26        | 1.2%    |
| Intel Pentium Dual-Core | 24        | 1.11%   |
| AMD FX                  | 22        | 1.02%   |
| Intel Core 2 Quad       | 21        | 0.97%   |
| AMD A8                  | 20        | 0.92%   |
| Intel Pentium Dual      | 18        | 0.83%   |
| AMD Ryzen 9             | 17        | 0.79%   |
| Intel Core 2            | 15        | 0.69%   |
| AMD A10                 | 15        | 0.69%   |
| Intel Core i9           | 10        | 0.46%   |
| AMD Phenom II X4        | 8         | 0.37%   |
| AMD A6                  | 8         | 0.37%   |
| AMD A4                  | 8         | 0.37%   |
| AMD Ryzen 7 PRO         | 7         | 0.32%   |
| AMD Ryzen 5 PRO         | 7         | 0.32%   |
| Intel Pentium Silver    | 6         | 0.28%   |
| AMD Athlon 64 X2        | 5         | 0.23%   |
| Intel Pentium 4         | 4         | 0.18%   |
| Intel Genuine           | 4         | 0.18%   |
| AMD Athlon II X3        | 4         | 0.18%   |
| AMD Athlon II X2        | 4         | 0.18%   |
| AMD Athlon              | 4         | 0.18%   |
| AMD A12                 | 4         | 0.18%   |
| AMD Phenom II X6        | 3         | 0.14%   |
| AMD Phenom              | 3         | 0.14%   |
| AMD E2                  | 3         | 0.14%   |
| AMD C-60                | 3         | 0.14%   |
| AMD Athlon II X4        | 3         | 0.14%   |
| Intel Xeon Silver       | 2         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 845       | 39.03%  |
| 4       | 751       | 34.69%  |
| 6       | 260       | 12.01%  |
| 8       | 165       | 7.62%   |
| 1       | 37        | 1.71%   |
| 12      | 28        | 1.29%   |
| 10      | 23        | 1.06%   |
| 14      | 22        | 1.02%   |
| 3       | 14        | 0.65%   |
| 16      | 8         | 0.37%   |
| 24      | 7         | 0.32%   |
| 20      | 2         | 0.09%   |
| Unknown | 2         | 0.09%   |
| 64      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2154      | 99.63%  |
| 2       | 6         | 0.28%   |
| Unknown | 2         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1558      | 71.96%  |
| 1       | 602       | 27.81%  |
| 8       | 2         | 0.09%   |
| Unknown | 2         | 0.09%   |
| 4       | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2109      | 97.37%  |
| Unknown        | 41        | 1.89%   |
| 32-bit         | 15        | 0.69%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 767       | 34.06%  |
| 0x306a9    | 100       | 4.44%   |
| 0x206a7    | 99        | 4.4%    |
| 0x306c3    | 61        | 2.71%   |
| 0x1067a    | 54        | 2.4%    |
| 0x906e9    | 52        | 2.31%   |
| 0x40651    | 44        | 1.95%   |
| 0x806ea    | 42        | 1.87%   |
| 0x906ea    | 40        | 1.78%   |
| 0x806e9    | 38        | 1.69%   |
| 0xa0652    | 37        | 1.64%   |
| 0x806ec    | 37        | 1.64%   |
| 0x806c1    | 35        | 1.55%   |
| 0x306d4    | 35        | 1.55%   |
| 0x506e3    | 33        | 1.47%   |
| 0x406e3    | 33        | 1.47%   |
| 0x20655    | 33        | 1.47%   |
| 0x08108109 | 29        | 1.29%   |
| 0x6fd      | 26        | 1.15%   |
| 0x08608103 | 24        | 1.07%   |
| 0x08600106 | 24        | 1.07%   |
| 0x30678    | 22        | 0.98%   |
| 0x0a50000c | 22        | 0.98%   |
| 0x08108102 | 22        | 0.98%   |
| 0x706e5    | 20        | 0.89%   |
| 0x406c4    | 20        | 0.89%   |
| 0x0a50000d | 20        | 0.89%   |
| 0x20652    | 18        | 0.8%    |
| 0x10676    | 18        | 0.8%    |
| 0x08701021 | 16        | 0.71%   |
| 0x506c9    | 15        | 0.67%   |
| 0x906a3    | 14        | 0.62%   |
| 0x0800820d | 14        | 0.62%   |
| 0x06000852 | 14        | 0.62%   |
| 0x806d1    | 12        | 0.53%   |
| 0x906a4    | 11        | 0.49%   |
| 0x06006705 | 11        | 0.49%   |
| 0x406c3    | 10        | 0.44%   |
| 0x08600104 | 10        | 0.44%   |
| 0x08001138 | 10        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 339       | 15.64%  |
| Haswell          | 157       | 7.25%   |
| SandyBridge      | 145       | 6.69%   |
| IvyBridge        | 144       | 6.65%   |
| Unknown          | 143       | 6.6%    |
| Penryn           | 102       | 4.71%   |
| Skylake          | 98        | 4.52%   |
| Zen 2            | 97        | 4.48%   |
| Zen+             | 83        | 3.83%   |
| CometLake        | 79        | 3.65%   |
| TigerLake        | 76        | 3.51%   |
| Westmere         | 75        | 3.46%   |
| Zen 3            | 74        | 3.41%   |
| Silvermont       | 70        | 3.23%   |
| Core             | 62        | 2.86%   |
| Alderlake Hybrid | 56        | 2.58%   |
| IceLake          | 55        | 2.54%   |
| Broadwell        | 50        | 2.31%   |
| Zen              | 42        | 1.94%   |
| Piledriver       | 34        | 1.57%   |
| K10              | 29        | 1.34%   |
| Excavator        | 23        | 1.06%   |
| Goldmont plus    | 21        | 0.97%   |
| Puma             | 19        | 0.88%   |
| Goldmont         | 19        | 0.88%   |
| Bonnell          | 16        | 0.74%   |
| Nehalem          | 13        | 0.6%    |
| K8 Hammer        | 9         | 0.42%   |
| Bobcat           | 9         | 0.42%   |
| P6               | 6         | 0.28%   |
| NetBurst         | 6         | 0.28%   |
| K10 Llano        | 6         | 0.28%   |
| Steamroller      | 4         | 0.18%   |
| Bulldozer        | 3         | 0.14%   |
| Tremont          | 1         | 0.05%   |
| K6               | 1         | 0.05%   |
| Jaguar           | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1301      | 45.39%  |
| Nvidia                           | 862       | 30.08%  |
| AMD                              | 686       | 23.94%  |
| Silicon Integrated Systems [SiS] | 11        | 0.38%   |
| VIA Technologies                 | 3         | 0.1%    |
| Matrox Electronics Systems       | 2         | 0.07%   |
| ASPEED Technology                | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 112       | 3.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 98        | 3.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 70        | 2.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 62        | 2.08%   |
| Intel HD Graphics 620                                                                    | 60        | 2.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 60        | 2.01%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 55        | 1.85%   |
| Intel UHD Graphics 620                                                                   | 54        | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 51        | 1.71%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 1.61%   |
| Intel HD Graphics 630                                                                    | 47        | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 45        | 1.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 42        | 1.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 40        | 1.34%   |
| Intel HD Graphics 5500                                                                   | 40        | 1.34%   |
| Intel Core Processor Integrated Graphics Controller                                      | 40        | 1.34%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 37        | 1.24%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 37        | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 35        | 1.18%   |
| AMD Lucienne                                                                             | 34        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 33        | 1.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 1.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 31        | 1.04%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 30        | 1.01%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 29        | 0.97%   |
| Intel HD Graphics 530                                                                    | 28        | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 27        | 0.91%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 26        | 0.87%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 26        | 0.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 24        | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 23        | 0.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 23        | 0.77%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 22        | 0.74%   |
| Nvidia GM108M [GeForce 840M]                                                             | 22        | 0.74%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 21        | 0.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 21        | 0.71%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 21        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 20        | 0.67%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 18        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 629       | 28.87%  |
| Intel + Nvidia  | 515       | 23.63%  |
| 1 x AMD         | 418       | 19.18%  |
| 1 x Nvidia      | 290       | 13.31%  |
| Intel + AMD     | 135       | 6.2%    |
| 2 x AMD         | 75        | 3.44%   |
| AMD + Nvidia    | 59        | 2.71%   |
| Other           | 32        | 1.47%   |
| 1 x SiS         | 11        | 0.5%    |
| 2 x Intel       | 6         | 0.28%   |
| 1 x VIA         | 3         | 0.14%   |
| 2 x Nvidia      | 2         | 0.09%   |
| 1 x Matrox      | 2         | 0.09%   |
| Intel + 2 x AMD | 1         | 0.05%   |
| 1 x ASPEED      | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1663      | 75.25%  |
| Proprietary | 443       | 20.05%  |
| Unknown     | 104       | 4.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1202      | 53.64%  |
| 1.01-2.0   | 312       | 13.92%  |
| 0.01-0.5   | 212       | 9.46%   |
| 0.51-1.0   | 193       | 8.61%   |
| 3.01-4.0   | 179       | 7.99%   |
| 5.01-6.0   | 59        | 2.63%   |
| 7.01-8.0   | 48        | 2.14%   |
| 8.01-16.0  | 22        | 0.98%   |
| 2.01-3.0   | 10        | 0.45%   |
| 16.01-24.0 | 3         | 0.13%   |
| 4.01-5.0   | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 318       | 14.03%  |
| BOE                     | 295       | 13.02%  |
| LG Display              | 261       | 11.52%  |
| Samsung Electronics     | 243       | 10.72%  |
| Chimei Innolux          | 237       | 10.46%  |
| Goldstar                | 84        | 3.71%   |
| Philips                 | 70        | 3.09%   |
| Dell                    | 55        | 2.43%   |
| Apple                   | 50        | 2.21%   |
| Hewlett-Packard         | 46        | 2.03%   |
| Ancor Communications    | 46        | 2.03%   |
| AOC                     | 44        | 1.94%   |
| Lenovo                  | 41        | 1.81%   |
| Chi Mei Optoelectronics | 41        | 1.81%   |
| Acer                    | 41        | 1.81%   |
| ViewSonic               | 38        | 1.68%   |
| PANDA                   | 36        | 1.59%   |
| ASUSTek Computer        | 31        | 1.37%   |
| BenQ                    | 24        | 1.06%   |
| Sharp                   | 23        | 1.02%   |
| MSI                     | 15        | 0.66%   |
| LG Philips              | 12        | 0.53%   |
| InfoVision              | 11        | 0.49%   |
| Vestel Elektronik       | 10        | 0.44%   |
| CPT                     | 9         | 0.4%    |
| Sony                    | 8         | 0.35%   |
| SAC                     | 8         | 0.35%   |
| LG Electronics          | 8         | 0.35%   |
| Unknown                 | 7         | 0.31%   |
| AGO                     | 7         | 0.31%   |
| LGD                     | 6         | 0.26%   |
| CSO                     | 6         | 0.26%   |
| Beko                    | 6         | 0.26%   |
| VIE                     | 5         | 0.22%   |
| SANYO                   | 5         | 0.22%   |
| Plain Tree Systems      | 5         | 0.22%   |
| Mi                      | 5         | 0.22%   |
| KTC                     | 5         | 0.22%   |
| HKC                     | 5         | 0.22%   |
| Fujitsu Siemens         | 5         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 24        | 1.04%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 21        | 0.91%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 20        | 0.87%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 19        | 0.82%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 17        | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 17        | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 17        | 0.74%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 14        | 0.61%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 12        | 0.52%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 11        | 0.48%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 11        | 0.48%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 11        | 0.48%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 10        | 0.43%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 10        | 0.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.43%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 9         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 9         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 9         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 9         | 0.39%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 9         | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 9         | 0.39%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 8         | 0.35%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 8         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 8         | 0.35%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 8         | 0.35%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 8         | 0.35%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 7         | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 7         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 7         | 0.3%    |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 7         | 0.3%    |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 7         | 0.3%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 7         | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 6         | 0.26%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 6         | 0.26%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 6         | 0.26%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch              | 6         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1043      | 48.58%  |
| 1366x768 (WXGA)    | 541       | 25.2%   |
| 3840x2160 (4K)     | 77        | 3.59%   |
| 2560x1440 (QHD)    | 73        | 3.4%    |
| 1440x900 (WXGA+)   | 49        | 2.28%   |
| 1600x900 (HD+)     | 46        | 2.14%   |
| 1280x800 (WXGA)    | 45        | 2.1%    |
| 1280x1024 (SXGA)   | 35        | 1.63%   |
| 1920x1200 (WUXGA)  | 32        | 1.49%   |
| 1680x1050 (WSXGA+) | 28        | 1.3%    |
| Unknown            | 24        | 1.12%   |
| 2560x1600          | 21        | 0.98%   |
| 2160x1440          | 16        | 0.75%   |
| 2560x1080          | 15        | 0.7%    |
| 2880x1800          | 12        | 0.56%   |
| 1360x768           | 12        | 0.56%   |
| 1024x600           | 11        | 0.51%   |
| 3440x1440          | 9         | 0.42%   |
| 3840x1080          | 8         | 0.37%   |
| 3200x1800 (QHD+)   | 5         | 0.23%   |
| 1920x540           | 4         | 0.19%   |
| 1024x768 (XGA)     | 4         | 0.19%   |
| 800x1280           | 3         | 0.14%   |
| 2520x1680          | 3         | 0.14%   |
| 1680x945           | 3         | 0.14%   |
| 4480x1440          | 2         | 0.09%   |
| 3840x2400          | 2         | 0.09%   |
| 3000x2000          | 2         | 0.09%   |
| 800x600            | 1         | 0.05%   |
| 7920x1440          | 1         | 0.05%   |
| 6000x1440          | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 3840x2560          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |
| 3750x1280          | 1         | 0.05%   |
| 3360x1050          | 1         | 0.05%   |
| 3240x2160          | 1         | 0.05%   |
| 3200x2000          | 1         | 0.05%   |
| 3072x1920          | 1         | 0.05%   |
| 3046x1050          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 917       | 40.5%   |
| 13      | 194       | 8.57%   |
| 23      | 126       | 5.57%   |
| 21      | 126       | 5.57%   |
| 14      | 111       | 4.9%    |
| 27      | 109       | 4.81%   |
| 24      | 101       | 4.46%   |
| 17      | 99        | 4.37%   |
| Unknown | 81        | 3.58%   |
| 18      | 58        | 2.56%   |
| 16      | 53        | 2.34%   |
| 19      | 40        | 1.77%   |
| 12      | 32        | 1.41%   |
| 11      | 31        | 1.37%   |
| 31      | 28        | 1.24%   |
| 20      | 25        | 1.1%    |
| 34      | 22        | 0.97%   |
| 10      | 17        | 0.75%   |
| 84      | 14        | 0.62%   |
| 22      | 14        | 0.62%   |
| 72      | 11        | 0.49%   |
| 26      | 7         | 0.31%   |
| 54      | 6         | 0.27%   |
| 40      | 5         | 0.22%   |
| 32      | 5         | 0.22%   |
| 28      | 4         | 0.18%   |
| 57      | 3         | 0.13%   |
| 46      | 3         | 0.13%   |
| 43      | 3         | 0.13%   |
| 33      | 3         | 0.13%   |
| 29      | 3         | 0.13%   |
| 7       | 3         | 0.13%   |
| 60      | 2         | 0.09%   |
| 36      | 2         | 0.09%   |
| 86      | 1         | 0.04%   |
| 65      | 1         | 0.04%   |
| 64      | 1         | 0.04%   |
| 55      | 1         | 0.04%   |
| 52      | 1         | 0.04%   |
| 25      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1144      | 50.96%  |
| 501-600     | 310       | 13.81%  |
| 401-500     | 263       | 11.71%  |
| 201-300     | 185       | 8.24%   |
| 351-400     | 128       | 5.7%    |
| Unknown     | 81        | 3.61%   |
| 601-700     | 47        | 2.09%   |
| 701-800     | 32        | 1.43%   |
| 1501-2000   | 25        | 1.11%   |
| 1001-1500   | 19        | 0.85%   |
| 801-900     | 5         | 0.22%   |
| 901-1000    | 3         | 0.13%   |
| 1-100       | 3         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1669      | 81.89%  |
| 16/10   | 189       | 9.27%   |
| Unknown | 71        | 3.48%   |
| 3/2     | 33        | 1.62%   |
| 5/4     | 28        | 1.37%   |
| 21/9    | 22        | 1.08%   |
| 4/3     | 21        | 1.03%   |
| 0.67    | 3         | 0.15%   |
| 6/5     | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 934       | 41.55%  |
| 201-250        | 303       | 13.48%  |
| 81-90          | 228       | 10.14%  |
| 301-350        | 112       | 4.98%   |
| 151-200        | 100       | 4.45%   |
| 71-80          | 81        | 3.6%    |
| Unknown        | 81        | 3.6%    |
| 121-130        | 79        | 3.51%   |
| 141-150        | 69        | 3.07%   |
| 351-500        | 65        | 2.89%   |
| More than 1000 | 41        | 1.82%   |
| 51-60          | 31        | 1.38%   |
| 251-300        | 28        | 1.25%   |
| 111-120        | 28        | 1.25%   |
| 61-70          | 24        | 1.07%   |
| 41-50          | 17        | 0.76%   |
| 501-1000       | 13        | 0.58%   |
| 91-100         | 6         | 0.27%   |
| 131-140        | 5         | 0.22%   |
| 1-40           | 3         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 756       | 34.21%  |
| 101-120       | 602       | 27.24%  |
| 51-100        | 579       | 26.2%   |
| 161-240       | 133       | 6.02%   |
| Unknown       | 81        | 3.67%   |
| 1-50          | 32        | 1.45%   |
| More than 240 | 27        | 1.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1798      | 81.14%  |
| 2     | 298       | 13.45%  |
| 0     | 108       | 4.87%   |
| 3     | 12        | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1404      | 41.65%  |
| Intel                                  | 869       | 25.78%  |
| Qualcomm Atheros                       | 415       | 12.31%  |
| Broadcom                               | 188       | 5.58%   |
| Ralink Technology                      | 69        | 2.05%   |
| MediaTek                               | 67        | 1.99%   |
| Broadcom Limited                       | 39        | 1.16%   |
| Ralink                                 | 34        | 1.01%   |
| Marvell Technology Group               | 33        | 0.98%   |
| TP-Link                                | 29        | 0.86%   |
| ASUSTek Computer                       | 27        | 0.8%    |
| Samsung Electronics                    | 23        | 0.68%   |
| Qualcomm Atheros Communications        | 21        | 0.62%   |
| Nvidia                                 | 20        | 0.59%   |
| Xiaomi                                 | 15        | 0.44%   |
| Silicon Integrated Systems [SiS]       | 14        | 0.42%   |
| ASIX Electronics                       | 9         | 0.27%   |
| JMicron Technology                     | 6         | 0.18%   |
| Huawei Technologies                    | 6         | 0.18%   |
| Ericsson Business Mobile Networks      | 6         | 0.18%   |
| Apple                                  | 6         | 0.18%   |
| ZyXEL Communications                   | 5         | 0.15%   |
| Edimax Technology                      | 5         | 0.15%   |
| ICS Advent                             | 4         | 0.12%   |
| Dell                                   | 4         | 0.12%   |
| Aquantia                               | 4         | 0.12%   |
| Qualcomm                               | 3         | 0.09%   |
| Microchip Technology                   | 3         | 0.09%   |
| Tenda                                  | 2         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.06%   |
| Sierra Wireless                        | 2         | 0.06%   |
| OPPO Electronics                       | 2         | 0.06%   |
| Motorola PCS                           | 2         | 0.06%   |
| Lenovo                                 | 2         | 0.06%   |
| Attansic Technology                    | 2         | 0.06%   |
| Accton Technology                      | 2         | 0.06%   |
| Wilocity                               | 1         | 0.03%   |
| VIA Technologies                       | 1         | 0.03%   |
| ULi Electronics                        | 1         | 0.03%   |
| U-Blox                                 | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 968       | 25.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 198       | 5.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 74        | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 73        | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 70        | 1.81%   |
| Intel Wi-Fi 6 AX200                                                    | 69        | 1.79%   |
| Intel Wi-Fi 6 AX201                                                    | 62        | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 56        | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 55        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 53        | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 51        | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                      | 50        | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 48        | 1.24%   |
| Intel Wireless 7265                                                    | 47        | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 44        | 1.14%   |
| Intel Wireless 8265 / 8275                                             | 40        | 1.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 38        | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 38        | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 35        | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 35        | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 33        | 0.86%   |
| Ralink MT7601U Wireless Adapter                                        | 32        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 31        | 0.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 29        | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                          | 27        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 26        | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 26        | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 25        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 23        | 0.6%    |
| Intel Wireless 3160                                                    | 23        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 22        | 0.57%   |
| Intel Wireless 3165                                                    | 22        | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 21        | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 21        | 0.54%   |
| Intel Wireless 7260                                                    | 21        | 0.54%   |
| Intel I211 Gigabit Network Connection                                  | 20        | 0.52%   |
| Intel Ethernet Connection (2) I219-V                                   | 20        | 0.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 20        | 0.52%   |
| Intel Wireless 8260                                                    | 18        | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 16        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 753       | 39.93%  |
| Realtek Semiconductor            | 367       | 19.46%  |
| Qualcomm Atheros                 | 318       | 16.86%  |
| Broadcom                         | 147       | 7.79%   |
| Ralink Technology                | 69        | 3.66%   |
| MediaTek                         | 66        | 3.5%    |
| Ralink                           | 34        | 1.8%    |
| TP-Link                          | 27        | 1.43%   |
| Broadcom Limited                 | 27        | 1.43%   |
| ASUSTek Computer                 | 27        | 1.43%   |
| Qualcomm Atheros Communications  | 21        | 1.11%   |
| ZyXEL Communications             | 5         | 0.27%   |
| Edimax Technology                | 5         | 0.27%   |
| Marvell Technology Group         | 3         | 0.16%   |
| Dell                             | 3         | 0.16%   |
| Tenda                            | 2         | 0.11%   |
| Sierra Wireless                  | 2         | 0.11%   |
| Accton Technology                | 2         | 0.11%   |
| Wilocity                         | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| Qcom                             | 1         | 0.05%   |
| Linksys                          | 1         | 0.05%   |
| IMC Networks                     | 1         | 0.05%   |
| FIBOCOM                          | 1         | 0.05%   |
| Belkin Components                | 1         | 0.05%   |
| AirTies Wireless Networks        | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 74        | 3.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 73        | 3.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 70        | 3.7%    |
| Intel Wi-Fi 6 AX200                                            | 69        | 3.65%   |
| Intel Wi-Fi 6 AX201                                            | 62        | 3.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 56        | 2.96%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 55        | 2.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 53        | 2.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 51        | 2.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 48        | 2.54%   |
| Intel Wireless 7265                                            | 47        | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 44        | 2.33%   |
| Intel Wireless 8265 / 8275                                     | 40        | 2.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 38        | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 38        | 2.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 35        | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 35        | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 33        | 1.75%   |
| Ralink MT7601U Wireless Adapter                                | 32        | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 31        | 1.64%   |
| Broadcom BCM43142 802.11b/g/n                                  | 27        | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 26        | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 26        | 1.37%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 25        | 1.32%   |
| Intel Wireless 3160                                            | 23        | 1.22%   |
| Intel Wireless 3165                                            | 22        | 1.16%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 21        | 1.11%   |
| Intel Wireless 7260                                            | 21        | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 20        | 1.06%   |
| Intel Wireless 8260                                            | 18        | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 16        | 0.85%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 16        | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                | 16        | 0.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 16        | 0.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 15        | 0.79%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 15        | 0.79%   |
| Intel Centrino Wireless-N 2230                                 | 15        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 15        | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 14        | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 14        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1278      | 66.6%   |
| Intel                                  | 248       | 12.92%  |
| Qualcomm Atheros                       | 143       | 7.45%   |
| Broadcom                               | 74        | 3.86%   |
| Marvell Technology Group               | 30        | 1.56%   |
| Samsung Electronics                    | 23        | 1.2%    |
| Nvidia                                 | 19        | 0.99%   |
| Xiaomi                                 | 15        | 0.78%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.68%   |
| Broadcom Limited                       | 12        | 0.63%   |
| ASIX Electronics                       | 9         | 0.47%   |
| JMicron Technology                     | 6         | 0.31%   |
| Huawei Technologies                    | 6         | 0.31%   |
| Apple                                  | 6         | 0.31%   |
| ICS Advent                             | 4         | 0.21%   |
| Aquantia                               | 4         | 0.21%   |
| Qualcomm                               | 3         | 0.16%   |
| Microchip Technology                   | 3         | 0.16%   |
| TP-Link                                | 2         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 2         | 0.1%    |
| OPPO Electronics                       | 2         | 0.1%    |
| Motorola PCS                           | 2         | 0.1%    |
| Attansic Technology                    | 2         | 0.1%    |
| VIA Technologies                       | 1         | 0.05%   |
| ULi Electronics                        | 1         | 0.05%   |
| T & A Mobile Phones                    | 1         | 0.05%   |
| Standard Microsystems                  | 1         | 0.05%   |
| Raspberry Pi                           | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| Mellanox Technologies                  | 1         | 0.05%   |
| MediaTek                               | 1         | 0.05%   |
| LSI                                    | 1         | 0.05%   |
| Lenovo                                 | 1         | 0.05%   |
| Insyde Software                        | 1         | 0.05%   |
| HTC (High Tech Computer)               | 1         | 0.05%   |
| Davicom Semiconductor                  | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 968       | 49.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 198       | 10.17%  |
| Realtek RTL8125 2.5GbE Controller                                      | 50        | 2.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 29        | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 23        | 1.18%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 22        | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 21        | 1.08%   |
| Intel I211 Gigabit Network Connection                                  | 20        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                   | 20        | 1.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 16        | 0.82%   |
| Realtek Killer E2600 GbE Controller                                    | 15        | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 14        | 0.72%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 13        | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 13        | 0.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 13        | 0.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 12        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                                  | 12        | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 12        | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 11        | 0.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 11        | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 10        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 10        | 0.51%   |
| Intel 82579V Gigabit Network Connection                                | 10        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9         | 0.46%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 8         | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 8         | 0.41%   |
| Intel I210 Gigabit Network Connection                                  | 8         | 0.41%   |
| Intel Ethernet Connection I217-V                                       | 8         | 0.41%   |
| Nvidia MCP61 Ethernet                                                  | 7         | 0.36%   |
| Intel Ethernet Controller I225-V                                       | 7         | 0.36%   |
| Intel Ethernet Connection I218-LM                                      | 7         | 0.36%   |
| Intel Ethernet Connection (14) I219-V                                  | 7         | 0.36%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 7         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 6         | 0.31%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 0.31%   |
| Huawei VTR-L09                                                         | 6         | 0.31%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 6         | 0.31%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 6         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1840      | 50.47%  |
| WiFi     | 1786      | 48.99%  |
| Modem    | 17        | 0.47%   |
| Unknown  | 3         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1457      | 66.68%  |
| Ethernet | 728       | 33.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1325      | 61.17%  |
| 1     | 755       | 34.86%  |
| 0     | 62        | 2.86%   |
| 3     | 18        | 0.83%   |
| 4     | 3         | 0.14%   |
| 16    | 1         | 0.05%   |
| 7     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2111      | 97.19%  |
| Yes  | 61        | 2.81%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 636       | 42.48%  |
| Realtek Semiconductor           | 176       | 11.76%  |
| IMC Networks                    | 120       | 8.02%   |
| Qualcomm Atheros Communications | 118       | 7.88%   |
| Cambridge Silicon Radio         | 77        | 5.14%   |
| Lite-On Technology              | 57        | 3.81%   |
| Broadcom                        | 54        | 3.61%   |
| Foxconn / Hon Hai               | 51        | 3.41%   |
| Apple                           | 42        | 2.81%   |
| Toshiba                         | 28        | 1.87%   |
| ASUSTek Computer                | 27        | 1.8%    |
| Realtek                         | 26        | 1.74%   |
| Ralink                          | 21        | 1.4%    |
| Dell                            | 15        | 1%      |
| Hewlett-Packard                 | 14        | 0.94%   |
| MediaTek                        | 10        | 0.67%   |
| TP-Link                         | 9         | 0.6%    |
| Ralink Technology               | 4         | 0.27%   |
| Foxconn International           | 3         | 0.2%    |
| Alps Electric                   | 3         | 0.2%    |
| Marvell Semiconductor           | 2         | 0.13%   |
| Qcom                            | 1         | 0.07%   |
| Logitech                        | 1         | 0.07%   |
| Integrated System Solution      | 1         | 0.07%   |
| HTC (High Tech Computer)        | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 158       | 10.54%  |
| Intel Bluetooth wireless interface                  | 135       | 9.01%   |
| Realtek Bluetooth Radio                             | 111       | 7.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 102       | 6.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 77        | 5.14%   |
| Intel AX200 Bluetooth                               | 68        | 4.54%   |
| Qualcomm Atheros  Bluetooth Device                  | 58        | 3.87%   |
| Intel Bluetooth Device                              | 55        | 3.67%   |
| IMC Networks Bluetooth Radio                        | 36        | 2.4%    |
| Intel Wireless-AC 3168 Bluetooth                    | 31        | 2.07%   |
| Intel AX211 Bluetooth                               | 27        | 1.8%    |
| Realtek Bluetooth Radio                             | 26        | 1.73%   |
| IMC Networks Wireless_Device                        | 25        | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 24        | 1.6%    |
| Apple Bluetooth Host Controller                     | 24        | 1.6%    |
| Realtek  Bluetooth 4.2 Adapter                      | 23        | 1.53%   |
| IMC Networks Bluetooth Device                       | 22        | 1.47%   |
| Ralink RT3290 Bluetooth                             | 21        | 1.4%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 1.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 17        | 1.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 15        | 1%      |
| Lite-On Bluetooth Device                            | 15        | 1%      |
| Realtek 802.11ac WLAN Adapter                       | 14        | 0.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 0.93%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 13        | 0.87%   |
| Apple Bluetooth USB Host Controller                 | 13        | 0.87%   |
| Intel AX210 Bluetooth                               | 12        | 0.8%    |
| IMC Networks Bluetooth USB Host Controller          | 12        | 0.8%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 12        | 0.8%    |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.8%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 0.73%   |
| Lite-On Wireless_Device                             | 10        | 0.67%   |
| IMC Networks Bluetooth                              | 10        | 0.67%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 10        | 0.67%   |
| TP-Link UB500 Adapter                               | 9         | 0.6%    |
| MediaTek Wireless_Device                            | 9         | 0.6%    |
| Realtek RTL8723B Bluetooth                          | 8         | 0.53%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.53%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1571      | 53.86%  |
| AMD                                          | 632       | 21.67%  |
| Nvidia                                       | 529       | 18.14%  |
| C-Media Electronics                          | 27        | 0.93%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.45%   |
| Barco Display Systems                        | 11        | 0.38%   |
| Logitech                                     | 10        | 0.34%   |
| ASUSTek Computer                             | 9         | 0.31%   |
| JMTek                                        | 8         | 0.27%   |
| Generalplus Technology                       | 8         | 0.27%   |
| Texas Instruments                            | 7         | 0.24%   |
| SteelSeries ApS                              | 7         | 0.24%   |
| Kingston Technology                          | 7         | 0.24%   |
| Creative Labs                                | 6         | 0.21%   |
| VIA Technologies                             | 5         | 0.17%   |
| Tenx Technology                              | 5         | 0.17%   |
| Apple                                        | 5         | 0.17%   |
| Realtek Semiconductor                        | 4         | 0.14%   |
| Yamaha                                       | 3         | 0.1%    |
| M-Audio                                      | 3         | 0.1%    |
| GN Netcom                                    | 3         | 0.1%    |
| Trust                                        | 2         | 0.07%   |
| Micro Star International                     | 2         | 0.07%   |
| LG Electronics                               | 2         | 0.07%   |
| GYROCOM C&C                                  | 2         | 0.07%   |
| Focusrite-Novation                           | 2         | 0.07%   |
| Elite Silicon                                | 2         | 0.07%   |
| DSEA A/S                                     | 2         | 0.07%   |
| Creative Technology                          | 2         | 0.07%   |
| Corsair                                      | 2         | 0.07%   |
| Blue Microphones                             | 2         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| Yealink Network Technology                   | 1         | 0.03%   |
| ULi Electronics                              | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| Sony                                         | 1         | 0.03%   |
| RODE Microphones                             | 1         | 0.03%   |
| Razer USA                                    | 1         | 0.03%   |
| Native Instruments                           | 1         | 0.03%   |
| Medeli Electronics                           | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 245       | 7.05%   |
| Intel Sunrise Point-LP HD Audio                                            | 167       | 4.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 143       | 4.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 138       | 3.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 132       | 3.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 84        | 2.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 81        | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 81        | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 76        | 2.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 71        | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 68        | 1.96%   |
| Intel Comet Lake PCH cAVS                                                  | 64        | 1.84%   |
| Intel Haswell-ULT HD Audio Controller                                      | 63        | 1.81%   |
| Intel 8 Series HD Audio Controller                                         | 63        | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 62        | 1.78%   |
| Nvidia Audio device                                                        | 60        | 1.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 56        | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 56        | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 55        | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                            | 55        | 1.58%   |
| AMD Starship/Matisse HD Audio Controller                                   | 53        | 1.52%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 53        | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 51        | 1.47%   |
| Intel Broadwell-U Audio Controller                                         | 48        | 1.38%   |
| AMD FCH Azalia Controller                                                  | 48        | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 47        | 1.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 45        | 1.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 44        | 1.27%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 40        | 1.15%   |
| Nvidia TU116 High Definition Audio Controller                              | 38        | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                               | 38        | 1.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 37        | 1.06%   |
| Intel CM238 HD Audio Controller                                            | 36        | 1.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 32        | 0.92%   |
| Intel 200 Series PCH HD Audio                                              | 31        | 0.89%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 31        | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 29        | 0.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 29        | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                   | 29        | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                              | 28        | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 353       | 25.29%  |
| SK hynix            | 233       | 16.69%  |
| Kingston            | 196       | 14.04%  |
| Micron Technology   | 141       | 10.1%   |
| Unknown             | 129       | 9.24%   |
| Crucial             | 75        | 5.37%   |
| Corsair             | 50        | 3.58%   |
| G.Skill             | 41        | 2.94%   |
| A-DATA Technology   | 35        | 2.51%   |
| Ramaxel Technology  | 24        | 1.72%   |
| Nanya Technology    | 19        | 1.36%   |
| Unknown             | 16        | 1.15%   |
| Elpida              | 11        | 0.79%   |
| Transcend           | 8         | 0.57%   |
| Unknown (ABCD)      | 7         | 0.5%    |
| Team                | 7         | 0.5%    |
| Goldkey             | 7         | 0.5%    |
| Timetec             | 5         | 0.36%   |
| Apacer              | 5         | 0.36%   |
| Neo Forza           | 3         | 0.21%   |
| ChangXin Memory     | 3         | 0.21%   |
| Kllisre             | 2         | 0.14%   |
| Hikvision           | 2         | 0.14%   |
| Gold Key            | 2         | 0.14%   |
| Avant               | 2         | 0.14%   |
| ASint Technology    | 2         | 0.14%   |
| AMD                 | 2         | 0.14%   |
| Unknown (F288)      | 1         | 0.07%   |
| Unknown (0x4509)    | 1         | 0.07%   |
| Unknown (0x29E)     | 1         | 0.07%   |
| Unknown (0B38)      | 1         | 0.07%   |
| Unknown (07FB)      | 1         | 0.07%   |
| Unifosa             | 1         | 0.07%   |
| pqi                 | 1         | 0.07%   |
| Patriot             | 1         | 0.07%   |
| Lexar Co Limited    | 1         | 0.07%   |
| Innodisk            | 1         | 0.07%   |
| Good Wealth         | 1         | 0.07%   |
| Golden Empire       | 1         | 0.07%   |
| ff                  | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 21        | 1.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 19        | 1.27%   |
| Unknown                                                      | 16        | 1.07%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 15        | 1.01%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s  | 14        | 0.94%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 14        | 0.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 13        | 0.87%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 13        | 0.87%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 12        | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 12        | 0.8%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 12        | 0.8%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 11        | 0.74%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 10        | 0.67%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 9         | 0.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 9         | 0.6%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 9         | 0.6%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 9         | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 9         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3                           | 8         | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 8         | 0.54%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 8         | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 8         | 0.54%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 8         | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 8         | 0.54%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s     | 7         | 0.47%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 7         | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 7         | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 7         | 0.47%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 7         | 0.47%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 6         | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 6         | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s         | 6         | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 6         | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 6         | 0.4%    |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s       | 6         | 0.4%    |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s         | 6         | 0.4%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 5         | 0.34%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 5         | 0.34%   |
| Unknown RAM Module 1GB SODIMM DDR2                           | 5         | 0.34%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 622       | 52.89%  |
| DDR3    | 343       | 29.17%  |
| LPDDR4  | 41        | 3.49%   |
| Unknown | 34        | 2.89%   |
| SDRAM   | 32        | 2.72%   |
| DDR2    | 32        | 2.72%   |
| DDR5    | 27        | 2.3%    |
| LPDDR3  | 21        | 1.79%   |
| LPDDR5  | 12        | 1.02%   |
| DDR     | 7         | 0.6%    |
| DRAM    | 4         | 0.34%   |
| EEPROM  | 1         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 810       | 69.11%  |
| DIMM         | 255       | 21.76%  |
| Row Of Chips | 101       | 8.62%   |
| Unknown      | 4         | 0.34%   |
| Chip         | 2         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 531       | 40.57%  |
| 4096    | 350       | 26.74%  |
| 16384   | 188       | 14.36%  |
| 2048    | 144       | 11%     |
| 32768   | 46        | 3.51%   |
| 1024    | 40        | 3.06%   |
| 512     | 4         | 0.31%   |
| 1536    | 2         | 0.15%   |
| 65536   | 1         | 0.08%   |
| 256     | 1         | 0.08%   |
| 1       | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 294       | 23.2%   |
| 1600    | 224       | 17.68%  |
| 2667    | 209       | 16.5%   |
| 2400    | 90        | 7.1%    |
| 1333    | 59        | 4.66%   |
| 2133    | 47        | 3.71%   |
| Unknown | 40        | 3.16%   |
| 1334    | 38        | 3%      |
| 3600    | 26        | 2.05%   |
| 667     | 26        | 2.05%   |
| 1067    | 19        | 1.5%    |
| 800     | 18        | 1.42%   |
| 1867    | 17        | 1.34%   |
| 4800    | 14        | 1.1%    |
| 4199    | 14        | 1.1%    |
| 4267    | 13        | 1.03%   |
| 6400    | 11        | 0.87%   |
| 3733    | 8         | 0.63%   |
| 3000    | 8         | 0.63%   |
| 5600    | 6         | 0.47%   |
| 4266    | 6         | 0.47%   |
| 3400    | 6         | 0.47%   |
| 1066    | 6         | 0.47%   |
| 3266    | 5         | 0.39%   |
| 3066    | 5         | 0.39%   |
| 400     | 5         | 0.39%   |
| 6000    | 4         | 0.32%   |
| 2048    | 4         | 0.32%   |
| 1866    | 4         | 0.32%   |
| 8400    | 3         | 0.24%   |
| 3866    | 3         | 0.24%   |
| 2800    | 3         | 0.24%   |
| 2666    | 3         | 0.24%   |
| 5500    | 2         | 0.16%   |
| 3800    | 2         | 0.16%   |
| 3466    | 2         | 0.16%   |
| 2933    | 2         | 0.16%   |
| 1639    | 2         | 0.16%   |
| 975     | 2         | 0.16%   |
| 533     | 2         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 14        | 32.56%  |
| Hewlett-Packard     | 12        | 27.91%  |
| Seiko Epson         | 6         | 13.95%  |
| Zebra               | 4         | 9.3%    |
| Samsung Electronics | 3         | 6.98%   |
| Brother Industries  | 2         | 4.65%   |
| XiaoMi              | 1         | 2.33%   |
| QinHeng Electronics | 1         | 2.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Zebra TLP2844                        | 3         | 6.82%   |
| Canon E410 series                    | 3         | 6.82%   |
| Seiko Epson L3110 Series             | 2         | 4.55%   |
| HP Officejet 4500 G510g-m            | 2         | 4.55%   |
| HP LaserJet P2055 series             | 2         | 4.55%   |
| Canon LBP6030w/6018w                 | 2         | 4.55%   |
| Canon CAPT USB Device                | 2         | 4.55%   |
| Zebra Zebra GC420d Label Printer     | 1         | 2.27%   |
| XiaoMi MIIIW MECH-KBPro              | 1         | 2.27%   |
| Seiko Epson L405 Series              | 1         | 2.27%   |
| Seiko Epson L210 Series              | 1         | 2.27%   |
| Seiko Epson FX-2190IIN               | 1         | 2.27%   |
| Seiko Epson ET-2710 Series           | 1         | 2.27%   |
| Samsung ML-216x Series Laser Printer | 1         | 2.27%   |
| Samsung M2020 Series                 | 1         | 2.27%   |
| Samsung CLP-325 Color Laser Printer  | 1         | 2.27%   |
| QinHeng CH340S                       | 1         | 2.27%   |
| HP LaserJet P1102                    | 1         | 2.27%   |
| HP LaserJet M101-M106                | 1         | 2.27%   |
| HP LaserJet 1020                     | 1         | 2.27%   |
| HP LaserJet 1010                     | 1         | 2.27%   |
| HP DeskJet F2100 Printer series      | 1         | 2.27%   |
| HP DeskJet 3830 series               | 1         | 2.27%   |
| HP DeskJet 2600 series               | 1         | 2.27%   |
| HP DeskJet 2130 series               | 1         | 2.27%   |
| HP Deskjet 1050 J410                 | 1         | 2.27%   |
| Canon PIXMA MX340                    | 1         | 2.27%   |
| Canon PIXMA MG3000 series            | 1         | 2.27%   |
| Canon LBP6000                        | 1         | 2.27%   |
| Canon imageRUNNER1133 series         | 1         | 2.27%   |
| Canon G3020 series                   | 1         | 2.27%   |
| Canon G3010 series                   | 1         | 2.27%   |
| Canon E460 series                    | 1         | 2.27%   |
| Brother Printer                      | 1         | 2.27%   |
| Brother DCP-1510                     | 1         | 2.27%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 50%     |
| Canon          | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 50%     |
| Canon CanoScan LiDE 210            | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 357       | 23.6%   |
| IMC Networks                           | 176       | 11.63%  |
| Realtek Semiconductor                  | 127       | 8.39%   |
| Quanta                                 | 100       | 6.61%   |
| Microdia                               | 90        | 5.95%   |
| Bison Electronics                      | 89        | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 75        | 4.96%   |
| Acer                                   | 55        | 3.64%   |
| Sunplus Innovation Technology          | 54        | 3.57%   |
| Syntek                                 | 47        | 3.11%   |
| Apple                                  | 39        | 2.58%   |
| Suyin                                  | 35        | 2.31%   |
| Luxvisions Innotech Limited            | 33        | 2.18%   |
| Logitech                               | 27        | 1.78%   |
| Silicon Motion                         | 25        | 1.65%   |
| Alcor Micro                            | 22        | 1.45%   |
| Lite-On Technology                     | 20        | 1.32%   |
| Z-Star Microelectronics                | 16        | 1.06%   |
| Sonix Technology                       | 13        | 0.86%   |
| Ricoh                                  | 12        | 0.79%   |
| Samsung Electronics                    | 11        | 0.73%   |
| Importek                               | 9         | 0.59%   |
| ALi                                    | 7         | 0.46%   |
| ShineTech                              | 5         | 0.33%   |
| BTF-230906-J                           | 4         | 0.26%   |
| SunplusIT                              | 3         | 0.2%    |
| Novatek Microelectronics               | 3         | 0.2%    |
| Microsoft                              | 3         | 0.2%    |
| MacroSilicon                           | 3         | 0.2%    |
| LG Electronics                         | 3         | 0.2%    |
| Lenovo                                 | 3         | 0.2%    |
| Jieli Technology                       | 3         | 0.2%    |
| Genesys Logic                          | 3         | 0.2%    |
| Generalplus Technology                 | 3         | 0.2%    |
| Foxconn / Hon Hai                      | 3         | 0.2%    |
| Arkmicro Technologies                  | 3         | 0.2%    |
| Sunplus Technology                     | 2         | 0.13%   |
| Primax Electronics                     | 2         | 0.13%   |
| kingcome                               | 2         | 0.13%   |
| GEMBIRD                                | 2         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 50        | 3.29%   |
| IMC Networks Integrated Camera                          | 45        | 2.96%   |
| Chicony HD WebCam                                       | 43        | 2.83%   |
| Microdia Integrated_Webcam_HD                           | 42        | 2.76%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 35        | 2.3%    |
| Realtek Integrated_Webcam_HD                            | 31        | 2.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 29        | 1.91%   |
| Syntek Integrated Camera                                | 27        | 1.78%   |
| Acer Integrated Camera                                  | 23        | 1.51%   |
| IMC Networks HD Camera                                  | 21        | 1.38%   |
| Chicony USB2.0 VGA UVC WebCam                           | 21        | 1.38%   |
| Chicony USB2.0 Camera                                   | 21        | 1.38%   |
| Bison HD Webcam                                         | 19        | 1.25%   |
| Quanta HD User Facing                                   | 18        | 1.18%   |
| Chicony USB2.0 HD UVC WebCam                            | 17        | 1.12%   |
| Bison Integrated Camera                                 | 16        | 1.05%   |
| Quanta ACER HD User Facing                              | 15        | 0.99%   |
| Realtek USB2.0 VGA UVC WebCam                           | 14        | 0.92%   |
| Chicony HP HD Camera                                    | 14        | 0.92%   |
| Chicony TOSHIBA Web Camera - HD                         | 13        | 0.86%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 13        | 0.86%   |
| Realtek USB Camera                                      | 12        | 0.79%   |
| Chicony HP Webcam                                       | 12        | 0.79%   |
| Chicony EasyCamera                                      | 12        | 0.79%   |
| Sunplus Integrated_Webcam_HD                            | 11        | 0.72%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 11        | 0.72%   |
| Chicony USB 2.0 Camera                                  | 11        | 0.72%   |
| Realtek USB2.0 HD UVC WebCam                            | 10        | 0.66%   |
| Quanta USB HD Webcam                                    | 10        | 0.66%   |
| Quanta ov9734_techfront_camera                          | 10        | 0.66%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera    | 10        | 0.66%   |
| Lite-On Integrated Camera                               | 10        | 0.66%   |
| Chicony Lenovo EasyCamera                               | 10        | 0.66%   |
| Chicony HD User Facing                                  | 10        | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 10        | 0.66%   |
| Bison SunplusIT Integrated Camera                       | 10        | 0.66%   |
| Apple FaceTime HD Camera (Built-in)                     | 10        | 0.66%   |
| Syntek EasyCamera                                       | 9         | 0.59%   |
| Realtek Lenovo EasyCamera                               | 9         | 0.59%   |
| Chicony Integrated IR Camera                            | 9         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 79        | 38.35%  |
| Synaptics                          | 46        | 22.33%  |
| Validity Sensors                   | 40        | 19.42%  |
| LighTuning Technology              | 16        | 7.77%   |
| AuthenTec                          | 11        | 5.34%   |
| Upek                               | 8         | 3.88%   |
| Elan Microelectronics              | 5         | 2.43%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.49%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 59        | 28.64%  |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 9.22%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 5.83%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 4.37%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 3.88%   |
| Synaptics  WBDI                                                            | 7         | 3.4%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 3.4%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 3.4%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.91%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.91%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 2.91%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 2.91%   |
| Synaptics WBDI                                                             | 5         | 2.43%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 1.94%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.94%   |
| AuthenTec AES2810                                                          | 4         | 1.94%   |
| Validity Sensors VFS491                                                    | 3         | 1.46%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.46%   |
| Synaptics UWP WBDI                                                         | 3         | 1.46%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.46%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.46%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.46%   |
| AuthenTec AES1600                                                          | 3         | 1.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.97%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 0.97%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.97%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.49%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.49%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.49%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.49%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.49%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.49%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.49%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 22        | 40%     |
| Alcor Micro           | 19        | 34.55%  |
| Advanced Card Systems | 6         | 10.91%  |
| Upek                  | 2         | 3.64%   |
| O2 Micro              | 2         | 3.64%   |
| Lenovo                | 2         | 3.64%   |
| Gemalto (was Gemplus) | 2         | 3.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 34.55%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 14.55%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 10.91%  |
| Broadcom 58200                                                               | 5         | 9.09%   |
| Broadcom 5880                                                                | 3         | 5.45%   |
| Advanced Card Systems ACR39U                                                 | 3         | 5.45%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 5.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.64%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.64%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.64%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 3.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1533      | 68.87%  |
| 1     | 551       | 24.75%  |
| 2     | 118       | 5.3%    |
| 3     | 15        | 0.67%   |
| 4     | 5         | 0.22%   |
| 6     | 2         | 0.09%   |
| 5     | 2         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 259       | 31.28%  |
| Fingerprint reader       | 206       | 24.88%  |
| Net/wireless             | 74        | 8.94%   |
| Multimedia controller    | 59        | 7.13%   |
| Camera                   | 53        | 6.4%    |
| Chipcard                 | 47        | 5.68%   |
| Bluetooth                | 35        | 4.23%   |
| Communication controller | 33        | 3.99%   |
| Net/ethernet             | 17        | 2.05%   |
| Sound                    | 13        | 1.57%   |
| Storage                  | 9         | 1.09%   |
| Network                  | 6         | 0.72%   |
| Card reader              | 5         | 0.6%    |
| Unassigned class         | 4         | 0.48%   |
| Storage/raid             | 2         | 0.24%   |
| Flash memory             | 2         | 0.24%   |
| Wireless                 | 1         | 0.12%   |
| Storage/ide              | 1         | 0.12%   |
| Storage/ata              | 1         | 0.12%   |
| Modem                    | 1         | 0.12%   |

