Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

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

Total: 4221

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 1520                 | Notebook    | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| Acer          | Predator G3-605             | Desktop     | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | Notebook    | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [ca6aacf14e](https://linux-hardware.org/?probe=ca6aacf14e) | Mar 31, 2023 |
| Positivo      | S14SL01                     | Notebook    | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | Benicia                     | Desktop     | [7332efabad](https://linux-hardware.org/?probe=7332efabad) | Mar 30, 2023 |
| HP            | kip                         | Notebook    | [fe84eac39e](https://linux-hardware.org/?probe=fe84eac39e) | Mar 30, 2023 |
| Positivo      | Q232A                       | Notebook    | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [0e8950a217](https://linux-hardware.org/?probe=0e8950a217) | Mar 30, 2023 |
| Positivo      | Q232A                       | Notebook    | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Acer          | FIH57                       | All in one  | [7a6b0e67f0](https://linux-hardware.org/?probe=7a6b0e67f0) | Mar 29, 2023 |
| Dell          | Precision M4500             | Notebook    | [cf7e033a17](https://linux-hardware.org/?probe=cf7e033a17) | Mar 29, 2023 |
| Dell          | Latitude 7430               | Notebook    | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| Dell          | Latitude 3590               | Notebook    | [9b5971401c](https://linux-hardware.org/?probe=9b5971401c) | Mar 29, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [c97dbb0917](https://linux-hardware.org/?probe=c97dbb0917) | Mar 28, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [90fa9585c9](https://linux-hardware.org/?probe=90fa9585c9) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [cf226d028d](https://linux-hardware.org/?probe=cf226d028d) | Mar 27, 2023 |
| HP            | 8430 1000                   | All in one  | [c0d9a96bbf](https://linux-hardware.org/?probe=c0d9a96bbf) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | Desktop     | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [05ecadea38](https://linux-hardware.org/?probe=05ecadea38) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c322e1c537](https://linux-hardware.org/?probe=c322e1c537) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [7fa1fc4759](https://linux-hardware.org/?probe=7fa1fc4759) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [cca501adf9](https://linux-hardware.org/?probe=cca501adf9) | Mar 26, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| AZW           | MINI S                      | Desktop     | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | Desktop     | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| WEIPAI        | S15                         | Notebook    | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| HP            | Stream Notebook             | Notebook    | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| Dell          | Latitude E5510              | Notebook    | [8a9a1eec2c](https://linux-hardware.org/?probe=8a9a1eec2c) | Mar 24, 2023 |
| Framework     | Laptop                      | Notebook    | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e859e77bc7](https://linux-hardware.org/?probe=e859e77bc7) | Mar 24, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [efab305a00](https://linux-hardware.org/?probe=efab305a00) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [ce7e17cb45](https://linux-hardware.org/?probe=ce7e17cb45) | Mar 24, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [05d4059f59](https://linux-hardware.org/?probe=05d4059f59) | Mar 24, 2023 |
| Acer          | FIH57                       | All in one  | [1f63978352](https://linux-hardware.org/?probe=1f63978352) | Mar 23, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [e992b8f3a0](https://linux-hardware.org/?probe=e992b8f3a0) | Mar 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [78fab808a1](https://linux-hardware.org/?probe=78fab808a1) | Mar 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| Intel         | G41                         | Desktop     | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d0b0015eb2](https://linux-hardware.org/?probe=d0b0015eb2) | Mar 22, 2023 |
| Orbsmart      | AW-11L                      | Mini pc     | [f66ed5bf1f](https://linux-hardware.org/?probe=f66ed5bf1f) | Mar 21, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9409e4e133](https://linux-hardware.org/?probe=9409e4e133) | Mar 20, 2023 |
| Acer          | Revo RL80                   | Desktop     | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| Dell          | Inspiron 5405               | Notebook    | [bb59d0b5e9](https://linux-hardware.org/?probe=bb59d0b5e9) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4b47e3ed6c](https://linux-hardware.org/?probe=4b47e3ed6c) | Mar 20, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [cddf0b016f](https://linux-hardware.org/?probe=cddf0b016f) | Mar 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [75996f8bcf](https://linux-hardware.org/?probe=75996f8bcf) | Mar 19, 2023 |
| HP            | 158A                        | Desktop     | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| Microtech     | CoreBook                    | Notebook    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| HP            | 2B01                        | Desktop     | [1a096f9b36](https://linux-hardware.org/?probe=1a096f9b36) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | Notebook    | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ee8b155a83](https://linux-hardware.org/?probe=ee8b155a83) | Mar 18, 2023 |
| Quanta        | XV1                         | All in one  | [2bbbb73d41](https://linux-hardware.org/?probe=2bbbb73d41) | Mar 18, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [c7b5ea67bb](https://linux-hardware.org/?probe=c7b5ea67bb) | Mar 18, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [211a71ed78](https://linux-hardware.org/?probe=211a71ed78) | Mar 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [5f4a932bcd](https://linux-hardware.org/?probe=5f4a932bcd) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| HP            | 83E1                        | Desktop     | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| HP            | Pavilion dm1                | Notebook    | [8707341105](https://linux-hardware.org/?probe=8707341105) | Mar 16, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [a029e62352](https://linux-hardware.org/?probe=a029e62352) | Mar 16, 2023 |
| HP            | 158A                        | Desktop     | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [06dd580c2e](https://linux-hardware.org/?probe=06dd580c2e) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [d9e1bb3da7](https://linux-hardware.org/?probe=d9e1bb3da7) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [3388dd991a](https://linux-hardware.org/?probe=3388dd991a) | Mar 15, 2023 |
| AZW           | GTR V01                     | Mini pc     | [98d84656e8](https://linux-hardware.org/?probe=98d84656e8) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | Notebook    | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f6a3a68640](https://linux-hardware.org/?probe=f6a3a68640) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | Notebook    | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [4987f344f2](https://linux-hardware.org/?probe=4987f344f2) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| Google        | Celes                       | Notebook    | [4fd0271747](https://linux-hardware.org/?probe=4fd0271747) | Mar 13, 2023 |
| HP            | 83E1                        | Desktop     | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| Soncview      | G41D3C                      | Desktop     | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| Quanta        | XV1                         | All in one  | [930e98f517](https://linux-hardware.org/?probe=930e98f517) | Mar 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9d5d0051ea](https://linux-hardware.org/?probe=9d5d0051ea) | Mar 13, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [178af6e35b](https://linux-hardware.org/?probe=178af6e35b) | Mar 12, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| HP            | 18E7                        | Desktop     | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | Notebook    | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Dell          | 0GM819                      | Desktop     | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | Desktop     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | Notebook    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | Desktop     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | Desktop     | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Acer          | TravelMate B113             | Notebook    | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| Acer          | WG43M                       | Desktop     | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | Desktop     | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [4b9462a4ff](https://linux-hardware.org/?probe=4b9462a4ff) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| HP            | 2B3B                        | All in one  | [cb25c51987](https://linux-hardware.org/?probe=cb25c51987) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Medion        | Akoya E1318T                | Notebook    | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [6648af3696](https://linux-hardware.org/?probe=6648af3696) | Mar 10, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [807d1626b4](https://linux-hardware.org/?probe=807d1626b4) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [3b0a7cfbf0](https://linux-hardware.org/?probe=3b0a7cfbf0) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [08bfa4188e](https://linux-hardware.org/?probe=08bfa4188e) | Mar 10, 2023 |
| HP            | ProBook 4530s               | Notebook    | [e9c9dd943e](https://linux-hardware.org/?probe=e9c9dd943e) | Mar 10, 2023 |
| Dell          | Precision M6700             | Notebook    | [7a02d78344](https://linux-hardware.org/?probe=7a02d78344) | Mar 10, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [565c8963d4](https://linux-hardware.org/?probe=565c8963d4) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | Notebook    | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [bd1ab8d62d](https://linux-hardware.org/?probe=bd1ab8d62d) | Mar 09, 2023 |
| Dell          | Latitude 3180               | Notebook    | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| HP            | 81C7 MVB 0C                 | Server      | [2ad477ea6c](https://linux-hardware.org/?probe=2ad477ea6c) | Mar 09, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [1599d2a2ef](https://linux-hardware.org/?probe=1599d2a2ef) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| Unknown       | HX90                        | Desktop     | [21530c00a4](https://linux-hardware.org/?probe=21530c00a4) | Mar 09, 2023 |
| Multilaser    | PC130                       | Notebook    | [37212994df](https://linux-hardware.org/?probe=37212994df) | Mar 09, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [8115c702cb](https://linux-hardware.org/?probe=8115c702cb) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [0dc84b30aa](https://linux-hardware.org/?probe=0dc84b30aa) | Mar 09, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0T500     | Notebook    | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d01b6ad50c](https://linux-hardware.org/?probe=d01b6ad50c) | Mar 08, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Dell          | Latitude E4310              | Notebook    | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a598fd0bed](https://linux-hardware.org/?probe=a598fd0bed) | Mar 08, 2023 |
| Lenovo        | YB1-X91F                    | Tablet      | [5582ce4ba9](https://linux-hardware.org/?probe=5582ce4ba9) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Dell          | Latitude 5310 2-in-1        | Convertible | [cccaedd7d3](https://linux-hardware.org/?probe=cccaedd7d3) | Mar 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | Desktop     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| Google        | Candy                       | Notebook    | [e74102ff2c](https://linux-hardware.org/?probe=e74102ff2c) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | Notebook    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0a85b4da67](https://linux-hardware.org/?probe=0a85b4da67) | Mar 07, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [3f1ebc8271](https://linux-hardware.org/?probe=3f1ebc8271) | Mar 07, 2023 |
| Google        | Lillipup                    | Notebook    | [33350c987b](https://linux-hardware.org/?probe=33350c987b) | Mar 07, 2023 |
| Chuwi         | HeroBox                     | Mini pc     | [6e8a20eb98](https://linux-hardware.org/?probe=6e8a20eb98) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | Notebook    | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| HP            | 81C7 MVB 0C                 | Server      | [e717a99f1f](https://linux-hardware.org/?probe=e717a99f1f) | Mar 06, 2023 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Google        | Lillipup                    | Notebook    | [214481f959](https://linux-hardware.org/?probe=214481f959) | Mar 06, 2023 |
| Dell          | 0JC474                      | Desktop     | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [657175938b](https://linux-hardware.org/?probe=657175938b) | Mar 05, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [47eeabee04](https://linux-hardware.org/?probe=47eeabee04) | Mar 05, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [f3c06b377f](https://linux-hardware.org/?probe=f3c06b377f) | Mar 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [05507dab01](https://linux-hardware.org/?probe=05507dab01) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Timi          | TM1701                      | Notebook    | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | Notebook    | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Unknown       | Rev.00                      | Desktop     | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1237954f03](https://linux-hardware.org/?probe=1237954f03) | Mar 03, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [03db87f6d8](https://linux-hardware.org/?probe=03db87f6d8) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| AZW           | GTR V01                     | Mini pc     | [fb4847e7ac](https://linux-hardware.org/?probe=fb4847e7ac) | Mar 03, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [81889ddc9c](https://linux-hardware.org/?probe=81889ddc9c) | Mar 02, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | Notebook    | [a3b6a280c1](https://linux-hardware.org/?probe=a3b6a280c1) | Mar 02, 2023 |
| HP            | Notebook                    | Notebook    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | Notebook    | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | Notebook    | [7b17e49d0f](https://linux-hardware.org/?probe=7b17e49d0f) | Mar 02, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [95b0a4d944](https://linux-hardware.org/?probe=95b0a4d944) | Mar 02, 2023 |
| HP            | 805D                        | Desktop     | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [e9b7ee04ec](https://linux-hardware.org/?probe=e9b7ee04ec) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| Toshiba       | Satellite S55t-B            | Notebook    | [69734289ba](https://linux-hardware.org/?probe=69734289ba) | Mar 01, 2023 |
| MSI           | Raider GE66 12UHS           | Notebook    | [3fcfdd9fba](https://linux-hardware.org/?probe=3fcfdd9fba) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [b4be9a72dd](https://linux-hardware.org/?probe=b4be9a72dd) | Feb 28, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [66e63a311d](https://linux-hardware.org/?probe=66e63a311d) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7478549a38](https://linux-hardware.org/?probe=7478549a38) | Feb 28, 2023 |
| Dell          | Latitude E6440              | Notebook    | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Google        | Buddy                       | Desktop     | [ac3d9aaed0](https://linux-hardware.org/?probe=ac3d9aaed0) | Feb 27, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [d7b51f6048](https://linux-hardware.org/?probe=d7b51f6048) | Feb 27, 2023 |
| AZW           | SER                         | Mini pc     | [e086890e6a](https://linux-hardware.org/?probe=e086890e6a) | Feb 27, 2023 |
| HP            | Pavilion dv7                | Notebook    | [d5da5f62b8](https://linux-hardware.org/?probe=d5da5f62b8) | Feb 27, 2023 |
| Acer          | TravelMate B113             | Notebook    | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [42acb38635](https://linux-hardware.org/?probe=42acb38635) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [e8c76a33fe](https://linux-hardware.org/?probe=e8c76a33fe) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| Dell          | Vostro 1540                 | Notebook    | [8f09ea4351](https://linux-hardware.org/?probe=8f09ea4351) | Feb 27, 2023 |
| HP            | ENVY m7 Notebook            | Notebook    | [14374fbcc8](https://linux-hardware.org/?probe=14374fbcc8) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [6c62bbbf3b](https://linux-hardware.org/?probe=6c62bbbf3b) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [2479c3c245](https://linux-hardware.org/?probe=2479c3c245) | Feb 27, 2023 |
| HP            | 1998                        | Desktop     | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [a21ea9613b](https://linux-hardware.org/?probe=a21ea9613b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| HP            | 620                         | Notebook    | [e3bf80caf7](https://linux-hardware.org/?probe=e3bf80caf7) | Feb 25, 2023 |
| Quanta        | XV1                         | All in one  | [fa596130ae](https://linux-hardware.org/?probe=fa596130ae) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1bc1cedec6](https://linux-hardware.org/?probe=1bc1cedec6) | Feb 25, 2023 |
| Dell          | Latitude E6440              | Notebook    | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7357439273](https://linux-hardware.org/?probe=7357439273) | Feb 25, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [7f88a11698](https://linux-hardware.org/?probe=7f88a11698) | Feb 25, 2023 |
| HP            | 2AF7                        | Desktop     | [a8eba0b0c4](https://linux-hardware.org/?probe=a8eba0b0c4) | Feb 25, 2023 |
| HP            | 2AF7                        | Desktop     | [3bf3afd1d5](https://linux-hardware.org/?probe=3bf3afd1d5) | Feb 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [bafb67390c](https://linux-hardware.org/?probe=bafb67390c) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [3b27d3609f](https://linux-hardware.org/?probe=3b27d3609f) | Feb 24, 2023 |
| HP            | ProBook 4545s               | Notebook    | [0f56422e2d](https://linux-hardware.org/?probe=0f56422e2d) | Feb 24, 2023 |
| HP            | 2129                        | Desktop     | [5118eb06d4](https://linux-hardware.org/?probe=5118eb06d4) | Feb 24, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [fd80b301db](https://linux-hardware.org/?probe=fd80b301db) | Feb 23, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [f283ae7cb2](https://linux-hardware.org/?probe=f283ae7cb2) | Feb 23, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [294c5c45e6](https://linux-hardware.org/?probe=294c5c45e6) | Feb 23, 2023 |
| DERE          | V14                         | Notebook    | [bb2d40e676](https://linux-hardware.org/?probe=bb2d40e676) | Feb 22, 2023 |
| HP            | 2129                        | Desktop     | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| ASUSTek       | F2A55-M                     | Desktop     | [c9d150f24c](https://linux-hardware.org/?probe=c9d150f24c) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [40e2157901](https://linux-hardware.org/?probe=40e2157901) | Feb 21, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [9a9c8192de](https://linux-hardware.org/?probe=9a9c8192de) | Feb 21, 2023 |
| Teclast       | F7                          | Notebook    | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5d32bc7f7c](https://linux-hardware.org/?probe=5d32bc7f7c) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a00e724475](https://linux-hardware.org/?probe=a00e724475) | Feb 21, 2023 |
| HP            | 1850                        | Desktop     | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| Dell          | System XPS L502X            | Notebook    | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [5002433b97](https://linux-hardware.org/?probe=5002433b97) | Feb 20, 2023 |
| HP            | 620                         | Notebook    | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Dell          | Latitude E5440              | Notebook    | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| HP            | Laptop 15s-dr0xxx           | Notebook    | [6733a448f9](https://linux-hardware.org/?probe=6733a448f9) | Feb 20, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [aeafa2dbee](https://linux-hardware.org/?probe=aeafa2dbee) | Feb 19, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [3c53a60245](https://linux-hardware.org/?probe=3c53a60245) | Feb 19, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| ASUSTek       | Zenbook UX562UG_Q508UG      | Convertible | [2bb870a042](https://linux-hardware.org/?probe=2bb870a042) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | Notebook    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [be0f73193d](https://linux-hardware.org/?probe=be0f73193d) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [752cdf5b2b](https://linux-hardware.org/?probe=752cdf5b2b) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [c784a261d4](https://linux-hardware.org/?probe=c784a261d4) | Feb 19, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [d6f4d9d8df](https://linux-hardware.org/?probe=d6f4d9d8df) | Feb 19, 2023 |
| Multilaser    | PC130                       | Notebook    | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | Notebook    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | Notebook    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| HP            | Unknown                     | Notebook    | [3fea6a053b](https://linux-hardware.org/?probe=3fea6a053b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | Notebook    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [59387e9081](https://linux-hardware.org/?probe=59387e9081) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| Medion        | E7220                       | Notebook    | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Google        | Robo                        | Notebook    | [303c72db93](https://linux-hardware.org/?probe=303c72db93) | Feb 17, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [529e0929d2](https://linux-hardware.org/?probe=529e0929d2) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [b997f44969](https://linux-hardware.org/?probe=b997f44969) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| Quanta        | XV1                         | All in one  | [6c4ea36dc2](https://linux-hardware.org/?probe=6c4ea36dc2) | Feb 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [c08ad0f295](https://linux-hardware.org/?probe=c08ad0f295) | Feb 16, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [1189701feb](https://linux-hardware.org/?probe=1189701feb) | Feb 15, 2023 |
| Acer          | Extensa 5230                | Notebook    | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Dell          | Latitude 3320               | Notebook    | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| MSI           | Z370M MORTAR                | Desktop     | [5ac9c9a924](https://linux-hardware.org/?probe=5ac9c9a924) | Feb 15, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [6c1c0027b1](https://linux-hardware.org/?probe=6c1c0027b1) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Dell          | System XPS L502X            | Notebook    | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [b9301138cc](https://linux-hardware.org/?probe=b9301138cc) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [03123ee601](https://linux-hardware.org/?probe=03123ee601) | Feb 14, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| Google        | Teemo                       | Desktop     | [53bf6d19ca](https://linux-hardware.org/?probe=53bf6d19ca) | Feb 14, 2023 |
| Samsung       | 700T1C                      | Notebook    | [66c15f037d](https://linux-hardware.org/?probe=66c15f037d) | Feb 14, 2023 |
| Samsung       | 700T1C                      | Notebook    | [9e154ea3a4](https://linux-hardware.org/?probe=9e154ea3a4) | Feb 14, 2023 |
| MSI           | MS-B9181                    | Desktop     | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [d1edc30dac](https://linux-hardware.org/?probe=d1edc30dac) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [ef1d9239ab](https://linux-hardware.org/?probe=ef1d9239ab) | Feb 12, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [59eeaafe59](https://linux-hardware.org/?probe=59eeaafe59) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [baa5f72e80](https://linux-hardware.org/?probe=baa5f72e80) | Feb 12, 2023 |
| HP            | Notebook                    | Notebook    | [a17adfd867](https://linux-hardware.org/?probe=a17adfd867) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [6f7c0f381e](https://linux-hardware.org/?probe=6f7c0f381e) | Feb 12, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [131d5052d1](https://linux-hardware.org/?probe=131d5052d1) | Feb 11, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a789235fe3](https://linux-hardware.org/?probe=a789235fe3) | Feb 11, 2023 |
| HP            | 8054                        | Desktop     | [55c5642509](https://linux-hardware.org/?probe=55c5642509) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [f3919f8d69](https://linux-hardware.org/?probe=f3919f8d69) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [518f413d2f](https://linux-hardware.org/?probe=518f413d2f) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [a24d7423c4](https://linux-hardware.org/?probe=a24d7423c4) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| Dell          | Latitude E6400              | Notebook    | [8c489c529a](https://linux-hardware.org/?probe=8c489c529a) | Feb 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [5e8a88b237](https://linux-hardware.org/?probe=5e8a88b237) | Feb 11, 2023 |
| ASUSTek       | P5K                         | Desktop     | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| Acer          | TravelMate P253             | Notebook    | [8947050124](https://linux-hardware.org/?probe=8947050124) | Feb 11, 2023 |
| HONOR         | HLYL-WXX9                   | Notebook    | [9d916e8e03](https://linux-hardware.org/?probe=9d916e8e03) | Feb 10, 2023 |
| Acer          | Aspire 5720                 | Notebook    | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [49b463f14c](https://linux-hardware.org/?probe=49b463f14c) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [477eb8ad3c](https://linux-hardware.org/?probe=477eb8ad3c) | Feb 10, 2023 |
| MSI           | GF615M-P31                  | Desktop     | [36dcd2e516](https://linux-hardware.org/?probe=36dcd2e516) | Feb 10, 2023 |
| Acer          | Predator G3-571             | Notebook    | [50fe192ea1](https://linux-hardware.org/?probe=50fe192ea1) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | Notebook    | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [dba0167a53](https://linux-hardware.org/?probe=dba0167a53) | Feb 09, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [ad403b2126](https://linux-hardware.org/?probe=ad403b2126) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [8513e7eb92](https://linux-hardware.org/?probe=8513e7eb92) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [458744c54d](https://linux-hardware.org/?probe=458744c54d) | Feb 09, 2023 |
| Positivo      | Smash2                      | Notebook    | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| Positivo      | Smash2                      | Notebook    | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [dd9b71e8d2](https://linux-hardware.org/?probe=dd9b71e8d2) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | Desktop     | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | Notebook    | [5c9ca6cd47](https://linux-hardware.org/?probe=5c9ca6cd47) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [dd76c764a1](https://linux-hardware.org/?probe=dd76c764a1) | Feb 08, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [37aec8a881](https://linux-hardware.org/?probe=37aec8a881) | Feb 08, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [e7ee51ecdd](https://linux-hardware.org/?probe=e7ee51ecdd) | Feb 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [0d0c6fe86c](https://linux-hardware.org/?probe=0d0c6fe86c) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| AZW           | GTR V01                     | Mini pc     | [69bc815c6d](https://linux-hardware.org/?probe=69bc815c6d) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [e32b918f95](https://linux-hardware.org/?probe=e32b918f95) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | Notebook    | [ae78404854](https://linux-hardware.org/?probe=ae78404854) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | Notebook    | [b2c3e0fa85](https://linux-hardware.org/?probe=b2c3e0fa85) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | Notebook    | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | Desktop     | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [1830edf54c](https://linux-hardware.org/?probe=1830edf54c) | Feb 07, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |
| Acer          | Okinawa                     | Notebook    | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [0e47e3afd8](https://linux-hardware.org/?probe=0e47e3afd8) | Feb 06, 2023 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [96f24866e0](https://linux-hardware.org/?probe=96f24866e0) | Feb 06, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [a57b142e05](https://linux-hardware.org/?probe=a57b142e05) | Feb 06, 2023 |
| Intel         | Unknown                     | Notebook    | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Sony          | VPCEG36FX                   | Notebook    | [d760d9e79b](https://linux-hardware.org/?probe=d760d9e79b) | Feb 06, 2023 |
| Acer          | TravelMate P253             | Notebook    | [050d7b5d68](https://linux-hardware.org/?probe=050d7b5d68) | Feb 06, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [f536be92d0](https://linux-hardware.org/?probe=f536be92d0) | Feb 06, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [00714979fe](https://linux-hardware.org/?probe=00714979fe) | Feb 06, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3bba794976](https://linux-hardware.org/?probe=3bba794976) | Feb 05, 2023 |
| Acer          | One S1002                   | Notebook    | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [b3ad379bdc](https://linux-hardware.org/?probe=b3ad379bdc) | Feb 05, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [0de7e3b318](https://linux-hardware.org/?probe=0de7e3b318) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| HP            | 2B47                        | Desktop     | [3db96ac186](https://linux-hardware.org/?probe=3db96ac186) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e5a1cf7284](https://linux-hardware.org/?probe=e5a1cf7284) | Feb 03, 2023 |
| Quanta        | XV1                         | All in one  | [8904f5e7fa](https://linux-hardware.org/?probe=8904f5e7fa) | Feb 03, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| MSI           | B85M-E45                    | Desktop     | [13453f924e](https://linux-hardware.org/?probe=13453f924e) | Feb 03, 2023 |
| Intel         | X58                         | Desktop     | [55a6a5bd82](https://linux-hardware.org/?probe=55a6a5bd82) | Feb 03, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [5bfa4ad142](https://linux-hardware.org/?probe=5bfa4ad142) | Feb 02, 2023 |
| HP            | 1825                        | Desktop     | [fd942fd3ba](https://linux-hardware.org/?probe=fd942fd3ba) | Feb 02, 2023 |
| Intel         | Unknown                     | Notebook    | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [e1da7f708a](https://linux-hardware.org/?probe=e1da7f708a) | Feb 02, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [741a1b90bd](https://linux-hardware.org/?probe=741a1b90bd) | Feb 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| MSI           | Raider GE66 12UHS           | Notebook    | [75e83dae8b](https://linux-hardware.org/?probe=75e83dae8b) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [d221bc6b8d](https://linux-hardware.org/?probe=d221bc6b8d) | Feb 01, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [92f6e450b8](https://linux-hardware.org/?probe=92f6e450b8) | Jan 31, 2023 |
| Dell          | Latitude E6540              | Notebook    | [156a047a82](https://linux-hardware.org/?probe=156a047a82) | Jan 31, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [a663152b7c](https://linux-hardware.org/?probe=a663152b7c) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [ae3838cc5d](https://linux-hardware.org/?probe=ae3838cc5d) | Jan 31, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9bb7eb28ed](https://linux-hardware.org/?probe=9bb7eb28ed) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [912213d849](https://linux-hardware.org/?probe=912213d849) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [456415a23e](https://linux-hardware.org/?probe=456415a23e) | Jan 30, 2023 |
| Dell          | Latitude E6520              | Notebook    | [f042c5966b](https://linux-hardware.org/?probe=f042c5966b) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1F20... | Notebook    | [39b709296b](https://linux-hardware.org/?probe=39b709296b) | Jan 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| HP            | 1791                        | Desktop     | [0cb5402c68](https://linux-hardware.org/?probe=0cb5402c68) | Jan 29, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [56622f5d6c](https://linux-hardware.org/?probe=56622f5d6c) | Jan 29, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [47438e081a](https://linux-hardware.org/?probe=47438e081a) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| Dell          | Precision 5530              | Notebook    | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [621aca8707](https://linux-hardware.org/?probe=621aca8707) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [55fe252b4e](https://linux-hardware.org/?probe=55fe252b4e) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [62b104b3d2](https://linux-hardware.org/?probe=62b104b3d2) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [b7cf9bee5c](https://linux-hardware.org/?probe=b7cf9bee5c) | Jan 28, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [bc4b6513bb](https://linux-hardware.org/?probe=bc4b6513bb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Dell          | Precision 5530              | Notebook    | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| HP            | 843F                        | Desktop     | [5e9a5d2afd](https://linux-hardware.org/?probe=5e9a5d2afd) | Jan 28, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [ad4f37d5a4](https://linux-hardware.org/?probe=ad4f37d5a4) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [cf4086f3e4](https://linux-hardware.org/?probe=cf4086f3e4) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| HP            | 2B47                        | Desktop     | [cce5f9ec07](https://linux-hardware.org/?probe=cce5f9ec07) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [8bd062dd40](https://linux-hardware.org/?probe=8bd062dd40) | Jan 27, 2023 |
| Dell          | Latitude E7470              | Notebook    | [4245585e75](https://linux-hardware.org/?probe=4245585e75) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| HP            | Notebook                    | Notebook    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [de7bee1cd6](https://linux-hardware.org/?probe=de7bee1cd6) | Jan 26, 2023 |
| Alienware     | M11xR3                      | Notebook    | [634b7f8eb0](https://linux-hardware.org/?probe=634b7f8eb0) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [756bf12bd7](https://linux-hardware.org/?probe=756bf12bd7) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| HP            | 625                         | Notebook    | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Google        | Blorb                       | Notebook    | [adae28c837](https://linux-hardware.org/?probe=adae28c837) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5dfd026f77](https://linux-hardware.org/?probe=5dfd026f77) | Jan 25, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | Notebook    | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [61d7aa3ef9](https://linux-hardware.org/?probe=61d7aa3ef9) | Jan 25, 2023 |
| Google        | Kip                         | Notebook    | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | Notebook    | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [da316254bb](https://linux-hardware.org/?probe=da316254bb) | Jan 24, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [af9518a90a](https://linux-hardware.org/?probe=af9518a90a) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [db73b82761](https://linux-hardware.org/?probe=db73b82761) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [6fd520f670](https://linux-hardware.org/?probe=6fd520f670) | Jan 23, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [788d350490](https://linux-hardware.org/?probe=788d350490) | Jan 23, 2023 |
| Acer          | RS880M05                    | Desktop     | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f72fec3364](https://linux-hardware.org/?probe=f72fec3364) | Jan 23, 2023 |
| Dell          | Latitude E7470              | Notebook    | [525bcdd915](https://linux-hardware.org/?probe=525bcdd915) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [20b73bd156](https://linux-hardware.org/?probe=20b73bd156) | Jan 23, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [37073c4323](https://linux-hardware.org/?probe=37073c4323) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6d5ca0b2e3](https://linux-hardware.org/?probe=6d5ca0b2e3) | Jan 22, 2023 |
| ASRock        | H61M                        | Desktop     | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| Dell          | Precision M6800             | Notebook    | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| HP            | 625                         | Notebook    | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [25013b14a9](https://linux-hardware.org/?probe=25013b14a9) | Jan 22, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1c3214e8c5](https://linux-hardware.org/?probe=1c3214e8c5) | Jan 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [b47caaf20b](https://linux-hardware.org/?probe=b47caaf20b) | Jan 22, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [1707a21fed](https://linux-hardware.org/?probe=1707a21fed) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | Notebook    | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| HP            | 625                         | Notebook    | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [aa8fbd29c9](https://linux-hardware.org/?probe=aa8fbd29c9) | Jan 21, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [548d331968](https://linux-hardware.org/?probe=548d331968) | Jan 21, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| Timi          | Mi Notebook Pro             | Notebook    | [1db1382f0b](https://linux-hardware.org/?probe=1db1382f0b) | Jan 21, 2023 |
| HP            | 89B5 A                      | Desktop     | [1b6e288840](https://linux-hardware.org/?probe=1b6e288840) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [f3af245bf8](https://linux-hardware.org/?probe=f3af245bf8) | Jan 20, 2023 |
| HP            | 843F                        | Desktop     | [07f6efa703](https://linux-hardware.org/?probe=07f6efa703) | Jan 20, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| ASUSTek       | M4A3000E                    | Desktop     | [650236c7cc](https://linux-hardware.org/?probe=650236c7cc) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [8131194ea1](https://linux-hardware.org/?probe=8131194ea1) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| HP            | 843F                        | Desktop     | [83ca70ac2d](https://linux-hardware.org/?probe=83ca70ac2d) | Jan 19, 2023 |
| HP            | ProBook 4740s               | Notebook    | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | Desktop     | [4f8a71f0c5](https://linux-hardware.org/?probe=4f8a71f0c5) | Jan 19, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [f3ab78c392](https://linux-hardware.org/?probe=f3ab78c392) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [4908236396](https://linux-hardware.org/?probe=4908236396) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [9e17ffeecc](https://linux-hardware.org/?probe=9e17ffeecc) | Jan 19, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [cfe9a9d924](https://linux-hardware.org/?probe=cfe9a9d924) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | 15                          | Notebook    | [cebe1b150e](https://linux-hardware.org/?probe=cebe1b150e) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | Notebook    | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| Google        | Kip                         | Notebook    | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | Notebook    | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| HP            | 3397                        | Desktop     | [a58c9ac196](https://linux-hardware.org/?probe=a58c9ac196) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d87fb3cf65](https://linux-hardware.org/?probe=d87fb3cf65) | Jan 17, 2023 |
| Fujitsu       | LIFEBOOK T726               | Convertible | [ab8e5c3c70](https://linux-hardware.org/?probe=ab8e5c3c70) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [473ae331ec](https://linux-hardware.org/?probe=473ae331ec) | Jan 16, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| Wortmann      | Mobile 1524                 | Notebook    | [17fc7e2f75](https://linux-hardware.org/?probe=17fc7e2f75) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | Desktop     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f4232dc72a](https://linux-hardware.org/?probe=f4232dc72a) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [df8d69926f](https://linux-hardware.org/?probe=df8d69926f) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [0670d91eb0](https://linux-hardware.org/?probe=0670d91eb0) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| Tactus        | GeoPad 110                  | Tablet      | [810d937888](https://linux-hardware.org/?probe=810d937888) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [331b5e3efa](https://linux-hardware.org/?probe=331b5e3efa) | Jan 14, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [e5ab68f182](https://linux-hardware.org/?probe=e5ab68f182) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | Notebook    | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [19531b68b1](https://linux-hardware.org/?probe=19531b68b1) | Jan 14, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [941c62872e](https://linux-hardware.org/?probe=941c62872e) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | Notebook    | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [845fca1774](https://linux-hardware.org/?probe=845fca1774) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | Notebook    | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [ddf679df3a](https://linux-hardware.org/?probe=ddf679df3a) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | Notebook    | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [250b4a09a0](https://linux-hardware.org/?probe=250b4a09a0) | Jan 13, 2023 |
| HP            | 3397                        | Desktop     | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Acer          | FRS690L                     | Desktop     | [5b27fe10aa](https://linux-hardware.org/?probe=5b27fe10aa) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | Notebook    | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [07cedbf55a](https://linux-hardware.org/?probe=07cedbf55a) | Jan 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [3d1b3bf218](https://linux-hardware.org/?probe=3d1b3bf218) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| GPU Compan... | GWTC116-2                   | Convertible | [a1c1965381](https://linux-hardware.org/?probe=a1c1965381) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| Acer          | Aspire 2920                 | Notebook    | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [78eb96d148](https://linux-hardware.org/?probe=78eb96d148) | Jan 11, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [9dfcb68d9a](https://linux-hardware.org/?probe=9dfcb68d9a) | Jan 11, 2023 |
| Wortmann      | TERRA_MOBILE_1062           | Tablet      | [d363c969bc](https://linux-hardware.org/?probe=d363c969bc) | Jan 10, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [fd9ae626c7](https://linux-hardware.org/?probe=fd9ae626c7) | Jan 10, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [8c41599fdd](https://linux-hardware.org/?probe=8c41599fdd) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d482768ec9](https://linux-hardware.org/?probe=d482768ec9) | Jan 09, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| Dell          | Latitude E6510              | Notebook    | [28cceb82e3](https://linux-hardware.org/?probe=28cceb82e3) | Jan 09, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [a8f14a8a8e](https://linux-hardware.org/?probe=a8f14a8a8e) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5bd32eb6f6](https://linux-hardware.org/?probe=5bd32eb6f6) | Jan 08, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [0ff44cdd4f](https://linux-hardware.org/?probe=0ff44cdd4f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [88ba7d805e](https://linux-hardware.org/?probe=88ba7d805e) | Jan 08, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [b5b4c3f6ef](https://linux-hardware.org/?probe=b5b4c3f6ef) | Jan 08, 2023 |
| HP            | 2129                        | Desktop     | [4d6113e60d](https://linux-hardware.org/?probe=4d6113e60d) | Jan 08, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [2b3261504f](https://linux-hardware.org/?probe=2b3261504f) | Jan 08, 2023 |
| MSI           | CR62 6M                     | Notebook    | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| Sony          | VAIO                        | All in one  | [1f521568e1](https://linux-hardware.org/?probe=1f521568e1) | Jan 07, 2023 |
| MAXSUN        | MS-TZZ A320M.2-VH           | Desktop     | [f3e00dc862](https://linux-hardware.org/?probe=f3e00dc862) | Jan 07, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [4c680e9948](https://linux-hardware.org/?probe=4c680e9948) | Jan 07, 2023 |
| HP            | Laptop 17-cp1xxx            | Notebook    | [d699356fd1](https://linux-hardware.org/?probe=d699356fd1) | Jan 07, 2023 |
| HP            | 2B47                        | Desktop     | [8ad8cb5e8f](https://linux-hardware.org/?probe=8ad8cb5e8f) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [6148bc3313](https://linux-hardware.org/?probe=6148bc3313) | Jan 06, 2023 |
| Multilaser    | PC024                       | Notebook    | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Multilaser    | PC024                       | Notebook    | [8d9a2a1304](https://linux-hardware.org/?probe=8d9a2a1304) | Jan 05, 2023 |
| Dell          | Precision M90               | Notebook    | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | ProBook 4540s               | Notebook    | [6e2638a12e](https://linux-hardware.org/?probe=6e2638a12e) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | Notebook    | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [4ec59dca55](https://linux-hardware.org/?probe=4ec59dca55) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | Notebook    | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [e597f176c2](https://linux-hardware.org/?probe=e597f176c2) | Jan 03, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [309e449325](https://linux-hardware.org/?probe=309e449325) | Jan 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [9ba9bcee90](https://linux-hardware.org/?probe=9ba9bcee90) | Jan 03, 2023 |
| Foxconn       | H67S/H61SP                  | Desktop     | [c7684d1f93](https://linux-hardware.org/?probe=c7684d1f93) | Jan 03, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [ce3dc1998f](https://linux-hardware.org/?probe=ce3dc1998f) | Jan 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [fcf5d132a5](https://linux-hardware.org/?probe=fcf5d132a5) | Jan 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f31ae01428](https://linux-hardware.org/?probe=f31ae01428) | Jan 02, 2023 |
| HP            | 8350                        | Desktop     | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| ASUSTek       | D300TA                      | Desktop     | [f522fa7b4d](https://linux-hardware.org/?probe=f522fa7b4d) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | Notebook    | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| Dell          | Latitude E5440              | Notebook    | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [0360bb01d0](https://linux-hardware.org/?probe=0360bb01d0) | Jan 01, 2023 |
| Dell          | Latitude E5500              | Notebook    | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [21638e1dfe](https://linux-hardware.org/?probe=21638e1dfe) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9220da7abb](https://linux-hardware.org/?probe=9220da7abb) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [c8da48f03c](https://linux-hardware.org/?probe=c8da48f03c) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| Biostar       | TA970                       | Desktop     | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e0e5f33e60](https://linux-hardware.org/?probe=e0e5f33e60) | Dec 30, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c841093094](https://linux-hardware.org/?probe=c841093094) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [59f6170d5b](https://linux-hardware.org/?probe=59f6170d5b) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [7ce6d4b3e3](https://linux-hardware.org/?probe=7ce6d4b3e3) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f828f74e07](https://linux-hardware.org/?probe=f828f74e07) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Dell          | 03KWTV A02                  | Desktop     | [82612358ac](https://linux-hardware.org/?probe=82612358ac) | Dec 28, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0c49efe5e1](https://linux-hardware.org/?probe=0c49efe5e1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| HP            | 2AF7                        | Desktop     | [9663a281c1](https://linux-hardware.org/?probe=9663a281c1) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [b65d5ce654](https://linux-hardware.org/?probe=b65d5ce654) | Dec 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [71c1ee486e](https://linux-hardware.org/?probe=71c1ee486e) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [2fe0a7fe8b](https://linux-hardware.org/?probe=2fe0a7fe8b) | Dec 27, 2022 |
| Acer          | Aspire XC-780               | Desktop     | [0d90d1884c](https://linux-hardware.org/?probe=0d90d1884c) | Dec 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [052cdcd8bb](https://linux-hardware.org/?probe=052cdcd8bb) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [940218d084](https://linux-hardware.org/?probe=940218d084) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | Notebook    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [047823ffbc](https://linux-hardware.org/?probe=047823ffbc) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | Notebook    | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [1ba51900a6](https://linux-hardware.org/?probe=1ba51900a6) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| HP            | 2AF7                        | Desktop     | [287696b4fc](https://linux-hardware.org/?probe=287696b4fc) | Dec 25, 2022 |
| Gigabyte      | GA-770T-USB3                | Desktop     | [08d1b04754](https://linux-hardware.org/?probe=08d1b04754) | Dec 25, 2022 |
| Sony          | VGN-NR32M_S                 | Notebook    | [6ad0da2e88](https://linux-hardware.org/?probe=6ad0da2e88) | Dec 25, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [2655b3c6b6](https://linux-hardware.org/?probe=2655b3c6b6) | Dec 24, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [1c2f8d9457](https://linux-hardware.org/?probe=1c2f8d9457) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [e968a4fe6d](https://linux-hardware.org/?probe=e968a4fe6d) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2415ad5980](https://linux-hardware.org/?probe=2415ad5980) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [9bcea5d857](https://linux-hardware.org/?probe=9bcea5d857) | Dec 24, 2022 |
| HP            | Pavilion dv7                | Notebook    | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| Intel         | H61                         | Desktop     | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| HP            | Pavilion g7                 | Notebook    | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| HP            | 2AF7                        | Desktop     | [7b79dd8352](https://linux-hardware.org/?probe=7b79dd8352) | Dec 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [3e8fb581f0](https://linux-hardware.org/?probe=3e8fb581f0) | Dec 23, 2022 |
| HP            | 2AF7                        | Desktop     | [5ef9ce3357](https://linux-hardware.org/?probe=5ef9ce3357) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [bb9724d53f](https://linux-hardware.org/?probe=bb9724d53f) | Dec 23, 2022 |
| Dell          | Latitude E4310              | Notebook    | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| ASRock        | G31M-S                      | Desktop     | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | Notebook    | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [cb9ec3d5ad](https://linux-hardware.org/?probe=cb9ec3d5ad) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [bfdc9d1e12](https://linux-hardware.org/?probe=bfdc9d1e12) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [79aabf81c4](https://linux-hardware.org/?probe=79aabf81c4) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | Desktop     | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | G31M-S                      | Desktop     | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [3caae1ba3b](https://linux-hardware.org/?probe=3caae1ba3b) | Dec 21, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| PCWare        | IPMH310 PRO 1.0             | Desktop     | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| Sony          | VJZ13A                      | Notebook    | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| Dell          | 0MGK50 A04                  | Desktop     | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [5212fb0d93](https://linux-hardware.org/?probe=5212fb0d93) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [9f456f73eb](https://linux-hardware.org/?probe=9f456f73eb) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0e5b8434fe](https://linux-hardware.org/?probe=0e5b8434fe) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| GPD           | G1619-04                    | Notebook    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
| HP            | 8715                        | Mini pc     | [a6f7705fd4](https://linux-hardware.org/?probe=a6f7705fd4) | Dec 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [b1bd890ed0](https://linux-hardware.org/?probe=b1bd890ed0) | Dec 19, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cf1ccbf76a](https://linux-hardware.org/?probe=cf1ccbf76a) | Dec 19, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [20b69069fa](https://linux-hardware.org/?probe=20b69069fa) | Dec 18, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [7064963568](https://linux-hardware.org/?probe=7064963568) | Dec 18, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [55cf134a8b](https://linux-hardware.org/?probe=55cf134a8b) | Dec 18, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d12b0d42fc](https://linux-hardware.org/?probe=d12b0d42fc) | Dec 17, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [e64e0ee27a](https://linux-hardware.org/?probe=e64e0ee27a) | Dec 17, 2022 |
| Fusion5       | C60Bv2-128GB                | Notebook    | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [be98ae95c3](https://linux-hardware.org/?probe=be98ae95c3) | Dec 17, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| HP            | Compaq 6910p (RM231UT#AB... | Notebook    | [4653b4877b](https://linux-hardware.org/?probe=4653b4877b) | Dec 17, 2022 |
| HP            | 250 G1                      | Notebook    | [07f20cc1ec](https://linux-hardware.org/?probe=07f20cc1ec) | Dec 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [010f6841e5](https://linux-hardware.org/?probe=010f6841e5) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [53ae51748b](https://linux-hardware.org/?probe=53ae51748b) | Dec 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [bbae74f641](https://linux-hardware.org/?probe=bbae74f641) | Dec 17, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [396db83818](https://linux-hardware.org/?probe=396db83818) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | Notebook    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [255499abee](https://linux-hardware.org/?probe=255499abee) | Dec 17, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [1a8c883ac5](https://linux-hardware.org/?probe=1a8c883ac5) | Dec 16, 2022 |
| Toshiba       | Satellite P500              | Notebook    | [58163fa1d7](https://linux-hardware.org/?probe=58163fa1d7) | Dec 16, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | Desktop     | [d9ee8a9854](https://linux-hardware.org/?probe=d9ee8a9854) | Dec 16, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ced1979abf](https://linux-hardware.org/?probe=ced1979abf) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| Google        | Blorb                       | Notebook    | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| HP            | 8750                        | Desktop     | [a4911352d1](https://linux-hardware.org/?probe=a4911352d1) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | Notebook    | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| Machcreato... | 14                          | Notebook    | [8b69842953](https://linux-hardware.org/?probe=8b69842953) | Dec 15, 2022 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [827fabbd5f](https://linux-hardware.org/?probe=827fabbd5f) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [34611b96d0](https://linux-hardware.org/?probe=34611b96d0) | Dec 15, 2022 |
| ASUSTek       | P5PL2-E                     | Desktop     | [d304b202fc](https://linux-hardware.org/?probe=d304b202fc) | Dec 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS2AN00    | Notebook    | [7db77c4fcd](https://linux-hardware.org/?probe=7db77c4fcd) | Dec 14, 2022 |
| Lenovo        | ThinkPad Helix 2nd 20CG0... | Tablet      | [e32ae95f08](https://linux-hardware.org/?probe=e32ae95f08) | Dec 14, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [3339909881](https://linux-hardware.org/?probe=3339909881) | Dec 14, 2022 |
| MSI           | MS-B9071                    | Desktop     | [fc31fe11a2](https://linux-hardware.org/?probe=fc31fe11a2) | Dec 14, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [1e8031daad](https://linux-hardware.org/?probe=1e8031daad) | Dec 13, 2022 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [c8c56f3e93](https://linux-hardware.org/?probe=c8c56f3e93) | Dec 13, 2022 |
| HP            | 1905                        | Desktop     | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| AZW           | GTR V01                     | Mini pc     | [7cae9d407c](https://linux-hardware.org/?probe=7cae9d407c) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | Desktop     | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| AZW           | GTR V01                     | Mini pc     | [9f1097843c](https://linux-hardware.org/?probe=9f1097843c) | Dec 12, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [09b233d518](https://linux-hardware.org/?probe=09b233d518) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [45ad14cbc2](https://linux-hardware.org/?probe=45ad14cbc2) | Dec 12, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [bc16110ca8](https://linux-hardware.org/?probe=bc16110ca8) | Dec 12, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [477bcdd546](https://linux-hardware.org/?probe=477bcdd546) | Dec 12, 2022 |
| Alienware     | 18                          | Notebook    | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Biostar       | A520MH                      | Desktop     | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [80281a1e7b](https://linux-hardware.org/?probe=80281a1e7b) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Sony          | VGN-NR32M_S                 | Notebook    | [f37234d095](https://linux-hardware.org/?probe=f37234d095) | Dec 10, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [e2a043a361](https://linux-hardware.org/?probe=e2a043a361) | Dec 10, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [097b783ae5](https://linux-hardware.org/?probe=097b783ae5) | Dec 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [9d7365bdd6](https://linux-hardware.org/?probe=9d7365bdd6) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [fbc5b65636](https://linux-hardware.org/?probe=fbc5b65636) | Dec 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [0f4312c32e](https://linux-hardware.org/?probe=0f4312c32e) | Dec 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [3e0d5dc490](https://linux-hardware.org/?probe=3e0d5dc490) | Dec 09, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [415b325dd0](https://linux-hardware.org/?probe=415b325dd0) | Dec 09, 2022 |
| Hampoo        | P02BD6_HI-122LP             | Tablet      | [fbbd6a06c8](https://linux-hardware.org/?probe=fbbd6a06c8) | Dec 09, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [69e83bcd80](https://linux-hardware.org/?probe=69e83bcd80) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [30bbadcb93](https://linux-hardware.org/?probe=30bbadcb93) | Dec 09, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [3a1ec09d8a](https://linux-hardware.org/?probe=3a1ec09d8a) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| HP            | 82FE 11                     | Desktop     | [6bf35b7005](https://linux-hardware.org/?probe=6bf35b7005) | Dec 08, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [54eaa6d2f3](https://linux-hardware.org/?probe=54eaa6d2f3) | Dec 07, 2022 |
| Dell          | Latitude 7490               | Notebook    | [6021de66f0](https://linux-hardware.org/?probe=6021de66f0) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [1c99985945](https://linux-hardware.org/?probe=1c99985945) | Dec 07, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| MSI           | K9A2 Platinum               | Desktop     | [3ce727deb7](https://linux-hardware.org/?probe=3ce727deb7) | Dec 06, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8442e3381c](https://linux-hardware.org/?probe=8442e3381c) | Dec 06, 2022 |
| Dell          | Latitude 7490               | Notebook    | [2b29482df2](https://linux-hardware.org/?probe=2b29482df2) | Dec 06, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [f8e7b50548](https://linux-hardware.org/?probe=f8e7b50548) | Dec 06, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [a4029fd324](https://linux-hardware.org/?probe=a4029fd324) | Dec 06, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [a28616ab1b](https://linux-hardware.org/?probe=a28616ab1b) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [5132e1aba1](https://linux-hardware.org/?probe=5132e1aba1) | Dec 05, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [d6f876fa52](https://linux-hardware.org/?probe=d6f876fa52) | Dec 05, 2022 |
| HP            | 8350                        | Desktop     | [f7768016d5](https://linux-hardware.org/?probe=f7768016d5) | Dec 05, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [586b9fe0a6](https://linux-hardware.org/?probe=586b9fe0a6) | Dec 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [9775fe7147](https://linux-hardware.org/?probe=9775fe7147) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [2ee93ad61d](https://linux-hardware.org/?probe=2ee93ad61d) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [d5ba349e44](https://linux-hardware.org/?probe=d5ba349e44) | Dec 04, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9a547affad](https://linux-hardware.org/?probe=9a547affad) | Dec 04, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [0e270ccc80](https://linux-hardware.org/?probe=0e270ccc80) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| MACHINIST     | E5-MR9A PRO V1.0            | Desktop     | [67fa9fb5aa](https://linux-hardware.org/?probe=67fa9fb5aa) | Dec 03, 2022 |
| MSI           | K9A2 Platinum               | Desktop     | [79c823558a](https://linux-hardware.org/?probe=79c823558a) | Dec 03, 2022 |
| HP            | 2AE2                        | Desktop     | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| MSI           | B75A-G41                    | Desktop     | [cbf02bbd94](https://linux-hardware.org/?probe=cbf02bbd94) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [e74106a982](https://linux-hardware.org/?probe=e74106a982) | Dec 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [26e6a987d0](https://linux-hardware.org/?probe=26e6a987d0) | Dec 03, 2022 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [dba5f63d66](https://linux-hardware.org/?probe=dba5f63d66) | Dec 03, 2022 |
| HP            | Pavilion g4                 | Notebook    | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| Biostar       | TPower X58                  | Desktop     | [320769fceb](https://linux-hardware.org/?probe=320769fceb) | Dec 02, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [d42891d37b](https://linux-hardware.org/?probe=d42891d37b) | Dec 02, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [71b49e89e9](https://linux-hardware.org/?probe=71b49e89e9) | Dec 02, 2022 |
| AZW           | U59                         | Desktop     | [6a7c9cb905](https://linux-hardware.org/?probe=6a7c9cb905) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | Notebook    | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| NZXT          | N7 Z590                     | Desktop     | [cc56e65209](https://linux-hardware.org/?probe=cc56e65209) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| MSI           | G41M-S03                    | Desktop     | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [7f91a09589](https://linux-hardware.org/?probe=7f91a09589) | Dec 01, 2022 |
| Sony          | VPCEB1M1E                   | Notebook    | [988c78f70d](https://linux-hardware.org/?probe=988c78f70d) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| HP            | 8433 11                     | Desktop     | [01f9a28da3](https://linux-hardware.org/?probe=01f9a28da3) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [ab421fd2d4](https://linux-hardware.org/?probe=ab421fd2d4) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [4f517e816d](https://linux-hardware.org/?probe=4f517e816d) | Dec 01, 2022 |
| Dell          | Latitude E5520              | Notebook    | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| Dell          | Studio 1558                 | Notebook    | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e214cb1bb9](https://linux-hardware.org/?probe=e214cb1bb9) | Nov 30, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [9d6aeff37c](https://linux-hardware.org/?probe=9d6aeff37c) | Nov 30, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Dell          | Latitude E6540              | Notebook    | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| Gateway       | SX2851                      | Desktop     | [b408695def](https://linux-hardware.org/?probe=b408695def) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [c4bbe90221](https://linux-hardware.org/?probe=c4bbe90221) | Nov 28, 2022 |
| Dell          | System XPS L502X            | Notebook    | [bd45da46bc](https://linux-hardware.org/?probe=bd45da46bc) | Nov 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNP           | Notebook    | [3dd83d6d9d](https://linux-hardware.org/?probe=3dd83d6d9d) | Nov 27, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [47782768eb](https://linux-hardware.org/?probe=47782768eb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | Notebook    | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [eda49557ae](https://linux-hardware.org/?probe=eda49557ae) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [6867d8eeaf](https://linux-hardware.org/?probe=6867d8eeaf) | Nov 27, 2022 |
| Dell          | Studio 1558                 | Notebook    | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | Notebook    | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | Desktop     | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [c26e52327e](https://linux-hardware.org/?probe=c26e52327e) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [543ca1307c](https://linux-hardware.org/?probe=543ca1307c) | Nov 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [5b531b7b41](https://linux-hardware.org/?probe=5b531b7b41) | Nov 26, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [def104dd7d](https://linux-hardware.org/?probe=def104dd7d) | Nov 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [5e51349002](https://linux-hardware.org/?probe=5e51349002) | Nov 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [f70a6fa6ae](https://linux-hardware.org/?probe=f70a6fa6ae) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [2eb5cc0a12](https://linux-hardware.org/?probe=2eb5cc0a12) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [c0102f2633](https://linux-hardware.org/?probe=c0102f2633) | Nov 25, 2022 |
| ASUSTek       | X202E                       | Notebook    | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | Notebook    | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Toshiba       | Satellite C50D-B            | Notebook    | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [1ed724b75e](https://linux-hardware.org/?probe=1ed724b75e) | Nov 25, 2022 |
| HP            | ENVY m6                     | Notebook    | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 18E7                        | Desktop     | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2c7485441f](https://linux-hardware.org/?probe=2c7485441f) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | Notebook    | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| ASUSTek       | M5401WUA                    | All in one  | [e49d5c5f9d](https://linux-hardware.org/?probe=e49d5c5f9d) | Nov 24, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [6bcefa911d](https://linux-hardware.org/?probe=6bcefa911d) | Nov 24, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [6cbdda4e27](https://linux-hardware.org/?probe=6cbdda4e27) | Nov 24, 2022 |
| Thomson       | GEN17V3C8WH256              | Notebook    | [7b1a510e2e](https://linux-hardware.org/?probe=7b1a510e2e) | Nov 24, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 208       | 6.55%   |
| 5.11.0-38-generic | 179       | 5.63%   |
| 5.11.0-27-generic | 154       | 4.85%   |
| 5.15.0-46-generic | 152       | 4.78%   |
| 5.15.0-58-generic | 148       | 4.66%   |
| 5.15.0-52-generic | 145       | 4.56%   |
| 5.15.0-67-generic | 132       | 4.15%   |
| 5.13.0-30-generic | 125       | 3.93%   |
| 5.11.0-40-generic | 124       | 3.9%    |
| 5.13.0-39-generic | 120       | 3.78%   |
| 5.11.0-41-generic | 107       | 3.37%   |
| 5.11.0-37-generic | 107       | 3.37%   |
| 5.15.0-60-generic | 105       | 3.31%   |
| 5.11.0-43-generic | 101       | 3.18%   |
| 5.15.0-48-generic | 95        | 2.99%   |
| 5.11.0-34-generic | 94        | 2.96%   |
| 5.13.0-40-generic | 89        | 2.8%    |
| 5.15.0-53-generic | 79        | 2.49%   |
| 5.15.0-41-generic | 76        | 2.39%   |
| 5.13.0-44-generic | 76        | 2.39%   |
| 5.13.0-35-generic | 74        | 2.33%   |
| 5.13.0-28-generic | 73        | 2.3%    |
| 5.13.0-52-generic | 59        | 1.86%   |
| 5.13.0-27-generic | 59        | 1.86%   |
| 5.13.0-41-generic | 54        | 1.7%    |
| 5.13.0-51-generic | 42        | 1.32%   |
| 5.15.0-43-generic | 40        | 1.26%   |
| 5.11.0-36-generic | 39        | 1.23%   |
| 5.11.0-46-generic | 35        | 1.1%    |
| 5.11.0-44-generic | 34        | 1.07%   |
| 5.15.0-57-generic | 33        | 1.04%   |
| 5.13.0-37-generic | 29        | 0.91%   |
| 5.13.0-48-generic | 22        | 0.69%   |
| 5.15.0-69-generic | 20        | 0.63%   |
| 5.15.0-50-generic | 20        | 0.63%   |
| 5.11.0-25-generic | 17        | 0.54%   |
| 5.8.0-53-generic  | 13        | 0.41%   |
| 5.8.0-50-generic  | 12        | 0.38%   |
| 5.8.0-59-generic  | 9         | 0.28%   |
| 5.8.0-55-generic  | 9         | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 1140      | 38.63%  |
| 5.11.0  | 948       | 32.12%  |
| 5.13.0  | 765       | 25.92%  |
| 5.8.0   | 53        | 1.8%    |
| 5.14.0  | 10        | 0.34%   |
| 5.4.0   | 2         | 0.07%   |
| 5.19.12 | 2         | 0.07%   |
| 5.18.15 | 2         | 0.07%   |
| 5.17.5  | 2         | 0.07%   |
| 5.17.1  | 2         | 0.07%   |
| 5.16.0  | 2         | 0.07%   |
| 5.10.0  | 2         | 0.07%   |
| 6.2.7   | 1         | 0.03%   |
| 6.1.7   | 1         | 0.03%   |
| 6.0.8   | 1         | 0.03%   |
| 6.0.19  | 1         | 0.03%   |
| 6.0.0   | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.6  | 1         | 0.03%   |
| 5.19.2  | 1         | 0.03%   |
| 5.19.14 | 1         | 0.03%   |
| 5.19.1  | 1         | 0.03%   |
| 5.19.0  | 1         | 0.03%   |
| 5.18.6  | 1         | 0.03%   |
| 5.17.9  | 1         | 0.03%   |
| 5.16.5  | 1         | 0.03%   |
| 5.16.14 | 1         | 0.03%   |
| 5.16.12 | 1         | 0.03%   |
| 5.15.49 | 1         | 0.03%   |
| 5.15.24 | 1         | 0.03%   |
| 5.15.13 | 1         | 0.03%   |
| 5.13.18 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1143      | 38.73%  |
| 5.11    | 948       | 32.12%  |
| 5.13    | 766       | 25.96%  |
| 5.8     | 53        | 1.8%    |
| 5.14    | 10        | 0.34%   |
| 5.19    | 8         | 0.27%   |
| 5.17    | 5         | 0.17%   |
| 5.16    | 5         | 0.17%   |
| 6.0     | 3         | 0.1%    |
| 5.4     | 3         | 0.1%    |
| 5.18    | 3         | 0.1%    |
| 5.10    | 2         | 0.07%   |
| 6.2     | 1         | 0.03%   |
| 6.1     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 2814      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 2457      | 86.76%  |
| XFCE       | 340       | 12.01%  |
| Unknown    | 18        | 0.64%   |
| X-Cinnamon | 4         | 0.14%   |
| Cinnamon   | 3         | 0.11%   |
| Budgie     | 3         | 0.11%   |
| KDE5       | 2         | 0.07%   |
| Unity      | 1         | 0.04%   |
| MATE       | 1         | 0.04%   |
| LXDE       | 1         | 0.04%   |
| KDE        | 1         | 0.04%   |
| i3         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2776      | 98.13%  |
| Wayland | 46        | 1.63%   |
| Unknown | 6         | 0.21%   |
| Tty     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2215      | 77.77%  |
| GDM     | 286       | 10.04%  |
| GDM3    | 258       | 9.06%   |
| LightDM | 85        | 2.98%   |
| SDDM    | 2         | 0.07%   |
| TDM     | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 1112      | 39.33%  |
| de_DE | 269       | 9.52%   |
| en_GB | 199       | 7.04%   |
| pt_BR | 166       | 5.87%   |
| fr_FR | 93        | 3.29%   |
| it_IT | 87        | 3.08%   |
| es_ES | 79        | 2.79%   |
| en_IN | 77        | 2.72%   |
| en_CA | 76        | 2.69%   |
| pl_PL | 66        | 2.33%   |
| en_AU | 62        | 2.19%   |
| nl_NL | 49        | 1.73%   |
| ru_RU | 42        | 1.49%   |
| es_MX | 39        | 1.38%   |
| en_ZA | 28        | 0.99%   |
| pt_PT | 26        | 0.92%   |
| cs_CZ | 24        | 0.85%   |
| hu_HU | 19        | 0.67%   |
| sv_SE | 18        | 0.64%   |
| es_AR | 18        | 0.64%   |
| tr_TR | 17        | 0.6%    |
| en_NZ | 16        | 0.57%   |
| nl_BE | 15        | 0.53%   |
| fr_BE | 15        | 0.53%   |
| es_CL | 14        | 0.5%    |
| de_CH | 13        | 0.46%   |
| de_AT | 11        | 0.39%   |
| ja_JP | 10        | 0.35%   |
| fr_CA | 10        | 0.35%   |
| es_CO | 10        | 0.35%   |
| nb_NO | 9         | 0.32%   |
| el_GR | 9         | 0.32%   |
| en_PH | 8         | 0.28%   |
| fi_FI | 7         | 0.25%   |
| es_VE | 6         | 0.21%   |
| es_CR | 6         | 0.21%   |
| ar_EG | 6         | 0.21%   |
| sk_SK | 5         | 0.18%   |
| en_IL | 5         | 0.18%   |
| da_DK | 5         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1619      | 56.89%  |
| BIOS | 1227      | 43.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2673      | 94.69%  |
| Zfs      | 57        | 2.02%   |
| Overlay  | 45        | 1.59%   |
| Btrfs    | 28        | 0.99%   |
| Xfs      | 8         | 0.28%   |
| Ext2     | 6         | 0.21%   |
| Ext3     | 5         | 0.18%   |
| Reiserfs | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2390      | 84.13%  |
| GPT     | 353       | 12.43%  |
| MBR     | 98        | 3.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2747      | 97.38%  |
| Yes       | 74        | 2.62%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2542      | 90.08%  |
| Yes       | 280       | 9.92%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 466       | 16.56%  |
| ASUSTek Computer    | 436       | 15.49%  |
| Dell                | 372       | 13.22%  |
| Lenovo              | 348       | 12.37%  |
| Gigabyte Technology | 167       | 5.93%   |
| Acer                | 142       | 5.05%   |
| MSI                 | 138       | 4.9%    |
| Apple               | 94        | 3.34%   |
| ASRock              | 78        | 2.77%   |
| Toshiba             | 68        | 2.42%   |
| Intel               | 45        | 1.6%    |
| Samsung Electronics | 32        | 1.14%   |
| Unknown             | 26        | 0.92%   |
| Sony                | 24        | 0.85%   |
| Google              | 23        | 0.82%   |
| Fujitsu             | 22        | 0.78%   |
| Packard Bell        | 18        | 0.64%   |
| Microsoft           | 18        | 0.64%   |
| Biostar             | 16        | 0.57%   |
| HUAWEI              | 14        | 0.5%    |
| Foxconn             | 13        | 0.46%   |
| Positivo            | 12        | 0.43%   |
| Alienware           | 11        | 0.39%   |
| Medion              | 9         | 0.32%   |
| Chuwi               | 9         | 0.32%   |
| Pegatron            | 8         | 0.28%   |
| Notebook            | 7         | 0.25%   |
| Multilaser          | 6         | 0.21%   |
| GPU Company         | 6         | 0.21%   |
| Gateway             | 6         | 0.21%   |
| AZW                 | 6         | 0.21%   |
| AMI                 | 6         | 0.21%   |
| Fujitsu Siemens     | 5         | 0.18%   |
| BESSTAR Tech        | 5         | 0.18%   |
| Thomson             | 4         | 0.14%   |
| Razer               | 4         | 0.14%   |
| OEM                 | 4         | 0.14%   |
| LG Electronics      | 4         | 0.14%   |
| Jumper              | 4         | 0.14%   |
| Framework           | 4         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 36        | 1.28%   |
| ASUS All Series            | 26        | 0.92%   |
| HP Notebook                | 19        | 0.68%   |
| HP Pavilion Notebook       | 13        | 0.46%   |
| HP 15                      | 8         | 0.28%   |
| Dell OptiPlex 790          | 8         | 0.28%   |
| Dell OptiPlex 7010         | 8         | 0.28%   |
| MSI MS-7817                | 7         | 0.25%   |
| HP Pavilion dv6            | 7         | 0.25%   |
| HP Pavilion 15             | 7         | 0.25%   |
| Apple MacBookPro8,1        | 7         | 0.25%   |
| Apple iMac12,2             | 7         | 0.25%   |
| MSI MS-7C02                | 6         | 0.21%   |
| Dell OptiPlex 780          | 6         | 0.21%   |
| Dell OptiPlex 380          | 6         | 0.21%   |
| Dell Latitude E6540        | 6         | 0.21%   |
| ASUS M5A78L-M/USB3         | 6         | 0.21%   |
| Microsoft Surface Pro 4    | 5         | 0.18%   |
| Microsoft Surface Pro      | 5         | 0.18%   |
| HP ProBook 640 G1          | 5         | 0.18%   |
| HP Pavilion dv7            | 5         | 0.18%   |
| GPU Company GWTC116-2      | 5         | 0.18%   |
| Gigabyte A320M-S2H         | 5         | 0.18%   |
| Dell OptiPlex 990          | 5         | 0.18%   |
| Dell OptiPlex 3010         | 5         | 0.18%   |
| Dell Inspiron 15-3567      | 5         | 0.18%   |
| Apple iMac12,1             | 5         | 0.18%   |
| Apple iMac10,1             | 5         | 0.18%   |
| Toshiba Satellite C660     | 4         | 0.14%   |
| Toshiba Satellite C55-C    | 4         | 0.14%   |
| Lenovo MIIX 320-10ICR 80XF | 4         | 0.14%   |
| HP ProDesk 600 G1 SFF      | 4         | 0.14%   |
| HP Pavilion g6             | 4         | 0.14%   |
| HP Laptop 15-bw0xx         | 4         | 0.14%   |
| HP EliteBook 840 G1        | 4         | 0.14%   |
| HP Compaq Pro 6300 SFF     | 4         | 0.14%   |
| Gigabyte X570 AORUS ELITE  | 4         | 0.14%   |
| Gigabyte B450 AORUS M      | 4         | 0.14%   |
| Framework Laptop           | 4         | 0.14%   |
| Dell XPS 13 9365           | 4         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 106       | 3.77%   |
| Dell Inspiron         | 106       | 3.77%   |
| Dell Latitude         | 99        | 3.52%   |
| HP Pavilion           | 96        | 3.41%   |
| Acer Aspire           | 94        | 3.34%   |
| Lenovo IdeaPad        | 90        | 3.2%    |
| Dell OptiPlex         | 65        | 2.31%   |
| Toshiba Satellite     | 54        | 1.92%   |
| HP EliteBook          | 47        | 1.67%   |
| ASUS ROG              | 44        | 1.56%   |
| HP Compaq             | 40        | 1.42%   |
| HP ProBook            | 39        | 1.39%   |
| ASUS PRIME            | 38        | 1.35%   |
| Unknown               | 36        | 1.28%   |
| Lenovo ThinkCentre    | 32        | 1.14%   |
| HP Laptop             | 32        | 1.14%   |
| ASUS VivoBook         | 32        | 1.14%   |
| HP ENVY               | 27        | 0.96%   |
| ASUS TUF              | 27        | 0.96%   |
| ASUS All              | 26        | 0.92%   |
| Dell Precision        | 25        | 0.89%   |
| Dell XPS              | 24        | 0.85%   |
| Dell Vostro           | 23        | 0.82%   |
| Lenovo Yoga           | 22        | 0.78%   |
| HP Notebook           | 19        | 0.68%   |
| Microsoft Surface     | 18        | 0.64%   |
| HP EliteDesk          | 15        | 0.53%   |
| Packard Bell EasyNote | 14        | 0.5%    |
| HP Stream             | 13        | 0.46%   |
| ASUS ZenBook          | 12        | 0.43%   |
| Apple iMac12          | 12        | 0.43%   |
| HP OMEN               | 11        | 0.39%   |
| Fujitsu ESPRIMO       | 11        | 0.39%   |
| Dell Studio           | 11        | 0.39%   |
| ASUS ASUS             | 11        | 0.39%   |
| HP ProDesk            | 10        | 0.36%   |
| HP 15                 | 10        | 0.36%   |
| Gigabyte B450         | 10        | 0.36%   |
| Gigabyte X570         | 9         | 0.32%   |
| ASUS M5A78L-M         | 9         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 251       | 8.92%   |
| 2021    | 246       | 8.74%   |
| 2011    | 243       | 8.64%   |
| 2013    | 239       | 8.49%   |
| 2018    | 222       | 7.89%   |
| 2020    | 211       | 7.5%    |
| 2019    | 206       | 7.32%   |
| 2014    | 188       | 6.68%   |
| 2017    | 166       | 5.9%    |
| 2010    | 166       | 5.9%    |
| 2016    | 154       | 5.47%   |
| 2015    | 140       | 4.98%   |
| 2008    | 119       | 4.23%   |
| 2009    | 98        | 3.48%   |
| 2007    | 69        | 2.45%   |
| 2022    | 66        | 2.35%   |
| 2006    | 17        | 0.6%    |
| 2023    | 5         | 0.18%   |
| 2005    | 5         | 0.18%   |
| Unknown | 3         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1544      | 54.87%  |
| Desktop     | 1030      | 36.6%   |
| Convertible | 73        | 2.59%   |
| All in one  | 68        | 2.42%   |
| Tablet      | 47        | 1.67%   |
| Mini pc     | 46        | 1.63%   |
| Server      | 6         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2484      | 87.5%   |
| Enabled  | 355       | 12.5%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2787      | 99.04%  |
| Yes  | 27        | 0.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 761       | 26.87%  |
| 3.01-4.0        | 629       | 22.21%  |
| 8.01-16.0       | 489       | 17.27%  |
| 16.01-24.0      | 469       | 16.56%  |
| 32.01-64.0      | 226       | 7.98%   |
| 1.01-2.0        | 137       | 4.84%   |
| 64.01-256.0     | 50        | 1.77%   |
| 2.01-3.0        | 37        | 1.31%   |
| 24.01-32.0      | 29        | 1.02%   |
| 0.51-1.0        | 4         | 0.14%   |
| More than 256.0 | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1192      | 39.13%  |
| 2.01-3.0   | 988       | 32.44%  |
| 3.01-4.0   | 408       | 13.39%  |
| 4.01-8.0   | 342       | 11.23%  |
| 8.01-16.0  | 52        | 1.71%   |
| 0.51-1.0   | 49        | 1.61%   |
| 16.01-24.0 | 8         | 0.26%   |
| 24.01-32.0 | 4         | 0.13%   |
| 32.01-64.0 | 2         | 0.07%   |
| 0.01-0.5   | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1811      | 63.1%   |
| 2      | 704       | 24.53%  |
| 3      | 170       | 5.92%   |
| 4      | 83        | 2.89%   |
| 5      | 39        | 1.36%   |
| 6      | 28        | 0.98%   |
| 0      | 14        | 0.49%   |
| 7      | 10        | 0.35%   |
| 8      | 8         | 0.28%   |
| 51     | 1         | 0.03%   |
| 30     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1596      | 56.46%  |
| Yes       | 1231      | 43.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2352      | 83.4%   |
| No        | 468       | 16.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2238      | 79.28%  |
| No        | 585       | 20.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1659      | 58.44%  |
| No        | 1180      | 41.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 671       | 23.77%  |
| Germany      | 288       | 10.2%   |
| Brazil       | 184       | 6.52%   |
| UK           | 182       | 6.45%   |
| Canada       | 98        | 3.47%   |
| Italy        | 97        | 3.44%   |
| Spain        | 91        | 3.22%   |
| France       | 84        | 2.98%   |
| India        | 80        | 2.83%   |
| Netherlands  | 78        | 2.76%   |
| Poland       | 65        | 2.3%    |
| Australia    | 62        | 2.2%    |
| Mexico       | 51        | 1.81%   |
| Russia       | 39        | 1.38%   |
| Belgium      | 39        | 1.38%   |
| South Africa | 33        | 1.17%   |
| Portugal     | 32        | 1.13%   |
| Sweden       | 31        | 1.1%    |
| Switzerland  | 27        | 0.96%   |
| Czechia      | 26        | 0.92%   |
| Austria      | 26        | 0.92%   |
| Argentina    | 26        | 0.92%   |
| Hungary      | 25        | 0.89%   |
| Turkey       | 24        | 0.85%   |
| Norway       | 23        | 0.81%   |
| Greece       | 22        | 0.78%   |
| Romania      | 21        | 0.74%   |
| New Zealand  | 18        | 0.64%   |
| Japan        | 18        | 0.64%   |
| Chile        | 18        | 0.64%   |
| Egypt        | 17        | 0.6%    |
| Denmark      | 15        | 0.53%   |
| Colombia     | 14        | 0.5%    |
| Indonesia    | 13        | 0.46%   |
| Finland      | 13        | 0.46%   |
| Serbia       | 11        | 0.39%   |
| Bulgaria     | 11        | 0.39%   |
| Malaysia     | 10        | 0.35%   |
| Slovenia     | 9         | 0.32%   |
| Philippines  | 9         | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 26        | 0.89%   |
| Munich            | 22        | 0.75%   |
| Athens            | 20        | 0.68%   |
| Sydney            | 17        | 0.58%   |
| Madrid            | 16        | 0.55%   |
| Rome              | 14        | 0.48%   |
| New York          | 14        | 0.48%   |
| Hamburg           | 14        | 0.48%   |
| Vienna            | 13        | 0.44%   |
| Sao Paulo         | 13        | 0.44%   |
| Rio de Janeiro    | 13        | 0.44%   |
| London            | 13        | 0.44%   |
| Montreal          | 12        | 0.41%   |
| Dallas            | 12        | 0.41%   |
| Amsterdam         | 11        | 0.38%   |
| Salt Lake City    | 10        | 0.34%   |
| Milan             | 10        | 0.34%   |
| Bengaluru         | 10        | 0.34%   |
| Perth             | 9         | 0.31%   |
| Paris             | 9         | 0.31%   |
| Melbourne         | 9         | 0.31%   |
| Johannesburg      | 9         | 0.31%   |
| Istanbul          | 9         | 0.31%   |
| Brisbane          | 9         | 0.31%   |
| Valencia          | 8         | 0.27%   |
| Stockholm         | 8         | 0.27%   |
| Seattle           | 8         | 0.27%   |
| Phoenix           | 8         | 0.27%   |
| Moscow            | 8         | 0.27%   |
| Mexico City       | 8         | 0.27%   |
| Glasgow           | 8         | 0.27%   |
| Frankfurt am Main | 8         | 0.27%   |
| Denver            | 8         | 0.27%   |
| Delhi             | 8         | 0.27%   |
| Cape Town         | 8         | 0.27%   |
| Cairo             | 8         | 0.27%   |
| Buenos Aires      | 8         | 0.27%   |
| Barcelona         | 8         | 0.27%   |
| Auckland          | 8         | 0.27%   |
| Toronto           | 7         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 619       | 881    | 15.53%  |
| Samsung Electronics       | 537       | 768    | 13.47%  |
| WDC                       | 516       | 690    | 12.94%  |
| Toshiba                   | 287       | 367    | 7.2%    |
| SanDisk                   | 243       | 279    | 6.09%   |
| Unknown                   | 232       | 321    | 5.82%   |
| Kingston                  | 215       | 283    | 5.39%   |
| Crucial                   | 151       | 182    | 3.79%   |
| Hitachi                   | 128       | 172    | 3.21%   |
| Intel                     | 87        | 115    | 2.18%   |
| SK hynix                  | 73        | 86     | 1.83%   |
| HGST                      | 66        | 83     | 1.66%   |
| A-DATA Technology         | 56        | 66     | 1.4%    |
| Micron Technology         | 51        | 61     | 1.28%   |
| China                     | 46        | 54     | 1.15%   |
| Apple                     | 37        | 40     | 0.93%   |
| Intenso                   | 32        | 34     | 0.8%    |
| Silicon Motion            | 31        | 38     | 0.78%   |
| Phison                    | 29        | 33     | 0.73%   |
| PNY                       | 25        | 32     | 0.63%   |
| SPCC                      | 22        | 25     | 0.55%   |
| Patriot                   | 22        | 27     | 0.55%   |
| Netac                     | 21        | 23     | 0.53%   |
| KIOXIA                    | 21        | 23     | 0.53%   |
| Unknown                   | 18        | 20     | 0.45%   |
| JMicron Technology        | 17        | 20     | 0.43%   |
| OCZ                       | 16        | 19     | 0.4%    |
| GOODRAM                   | 16        | 17     | 0.4%    |
| LITEON                    | 14        | 16     | 0.35%   |
| Lexar                     | 14        | 14     | 0.35%   |
| Micron/Crucial Technology | 13        | 13     | 0.33%   |
| Team                      | 12        | 15     | 0.3%    |
| Transcend                 | 11        | 28     | 0.28%   |
| Maxtor                    | 11        | 15     | 0.28%   |
| LITEONIT                  | 11        | 13     | 0.28%   |
| KingSpec                  | 11        | 13     | 0.28%   |
| Hewlett-Packard           | 11        | 15     | 0.28%   |
| Realtek Semiconductor     | 10        | 11     | 0.25%   |
| Phison Electronics        | 10        | 11     | 0.25%   |
| SABRENT                   | 9         | 10     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 72        | 1.64%   |
| Unknown MMC Card  64GB                              | 66        | 1.5%    |
| Kingston SA400S37240G 240GB SSD                     | 49        | 1.12%   |
| Seagate ST500DM002-1BD142 500GB                     | 41        | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB                      | 35        | 0.8%    |
| Samsung SSD 860 EVO 500GB                           | 34        | 0.77%   |
| Crucial CT240BX500SSD1 240GB                        | 33        | 0.75%   |
| Toshiba MQ01ABD100 1TB                              | 31        | 0.71%   |
| Unknown MMC Card  128GB                             | 29        | 0.66%   |
| Kingston SA400S37480G 480GB SSD                     | 29        | 0.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 27        | 0.61%   |
| Kingston SA400S37120G 120GB SSD                     | 27        | 0.61%   |
| Toshiba MQ01ABF050 500GB                            | 26        | 0.59%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 26        | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB                      | 25        | 0.57%   |
| Samsung NVMe SSD Drive 512GB                        | 25        | 0.57%   |
| Samsung NVMe SSD Drive 1TB                          | 25        | 0.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 25        | 0.57%   |
| Unknown SD/MMC/MS PRO 64GB                          | 24        | 0.55%   |
| Toshiba MQ04ABF100 1TB                              | 24        | 0.55%   |
| Samsung SSD 850 EVO 250GB                           | 23        | 0.52%   |
| Seagate ST500LT012-1DG142 500GB                     | 22        | 0.5%    |
| Samsung SSD 850 EVO 500GB                           | 22        | 0.5%    |
| SanDisk NVMe SSD Drive 256GB                        | 21        | 0.48%   |
| Samsung NVMe SSD Drive 500GB                        | 21        | 0.48%   |
| Crucial CT500MX500SSD1 500GB                        | 21        | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 18        | 0.41%   |
| Seagate ST9500325AS 500GB                           | 18        | 0.41%   |
| Seagate Expansion+ 2TB                              | 18        | 0.41%   |
| Samsung SSD 870 EVO 1TB                             | 18        | 0.41%   |
| Unknown                                             | 18        | 0.41%   |
| Unknown MMC Card  16GB                              | 17        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                    | 17        | 0.39%   |
| Seagate ST3500418AS 500GB                           | 16        | 0.36%   |
| SanDisk NVMe SSD Drive 1TB                          | 16        | 0.36%   |
| Seagate ST2000DM008-2FR102 2TB                      | 15        | 0.34%   |
| SanDisk NVMe SSD Drive 512GB                        | 15        | 0.34%   |
| Samsung SSD 860 EVO 250GB                           | 15        | 0.34%   |
| Samsung SSD 840 EVO 250GB                           | 15        | 0.34%   |
| Crucial CT1000MX500SSD1 1TB                         | 15        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 613       | 863    | 37.47%  |
| WDC                 | 444       | 588    | 27.14%  |
| Toshiba             | 227       | 296    | 13.88%  |
| Hitachi             | 128       | 172    | 7.82%   |
| HGST                | 66        | 83     | 4.03%   |
| Samsung Electronics | 65        | 82     | 3.97%   |
| Unknown             | 24        | 30     | 1.47%   |
| Apple               | 19        | 21     | 1.16%   |
| Maxtor              | 11        | 15     | 0.67%   |
| SABRENT             | 9         | 10     | 0.55%   |
| Fujitsu             | 8         | 9      | 0.49%   |
| ASMT                | 4         | 4      | 0.24%   |
| USB3.0              | 3         | 4      | 0.18%   |
| Super Talent        | 3         | 4      | 0.18%   |
| Hewlett-Packard     | 3         | 6      | 0.18%   |
| T-CREATE            | 2         | 2      | 0.12%   |
| JMicron Technology  | 2         | 2      | 0.12%   |
| Intenso             | 2         | 2      | 0.12%   |
| QUANTUM             | 1         | 1      | 0.06%   |
| KESU                | 1         | 1      | 0.06%   |
| ACASIS              | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 284       | 388    | 20.62%  |
| Kingston            | 177       | 226    | 12.85%  |
| Crucial             | 144       | 173    | 10.46%  |
| SanDisk             | 140       | 162    | 10.17%  |
| WDC                 | 61        | 73     | 4.43%   |
| A-DATA Technology   | 50        | 60     | 3.63%   |
| China               | 44        | 52     | 3.2%    |
| Toshiba             | 32        | 37     | 2.32%   |
| Intel               | 31        | 37     | 2.25%   |
| PNY                 | 25        | 32     | 1.82%   |
| Micron Technology   | 24        | 28     | 1.74%   |
| SK hynix            | 22        | 22     | 1.6%    |
| SPCC                | 21        | 24     | 1.53%   |
| Patriot             | 21        | 26     | 1.53%   |
| Netac               | 21        | 22     | 1.53%   |
| Intenso             | 20        | 21     | 1.45%   |
| OCZ                 | 15        | 18     | 1.09%   |
| GOODRAM             | 15        | 16     | 1.09%   |
| Apple               | 15        | 15     | 1.09%   |
| LITEON              | 14        | 16     | 1.02%   |
| Lexar               | 13        | 13     | 0.94%   |
| Team                | 12        | 15     | 0.87%   |
| Transcend           | 11        | 28     | 0.8%    |
| LITEONIT            | 11        | 13     | 0.8%    |
| KingSpec            | 10        | 12     | 0.73%   |
| JMicron Technology  | 9         | 11     | 0.65%   |
| Hewlett-Packard     | 8         | 9      | 0.58%   |
| Apacer              | 8         | 9      | 0.58%   |
| Unknown             | 8         | 10     | 0.58%   |
| Gigabyte Technology | 7         | 8      | 0.51%   |
| Leven               | 6         | 7      | 0.44%   |
| Plextor             | 4         | 5      | 0.29%   |
| FORESEE             | 4         | 4      | 0.29%   |
| Teclast             | 3         | 3      | 0.22%   |
| Seagate             | 3         | 5      | 0.22%   |
| OWC                 | 3         | 3      | 0.22%   |
| Mushkin             | 3         | 3      | 0.22%   |
| KIOXIA-EXCERIA      | 3         | 7      | 0.22%   |
| Corsair             | 3         | 6      | 0.22%   |
| BHT                 | 3         | 4      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1402      | 2196   | 38.67%  |
| SSD     | 1237      | 1708   | 34.11%  |
| NVMe    | 682       | 910    | 18.81%  |
| MMC     | 217       | 289    | 5.98%   |
| Unknown | 88        | 111    | 2.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2225      | 3776   | 67.69%  |
| NVMe | 682       | 908    | 20.75%  |
| MMC  | 217       | 289    | 6.6%    |
| SAS  | 163       | 241    | 4.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1663      | 2379   | 61.14%  |
| 0.51-1.0        | 736       | 1011   | 27.06%  |
| 1.01-2.0        | 203       | 280    | 7.46%   |
| 3.01-4.0        | 46        | 109    | 1.69%   |
| 4.01-10.0       | 40        | 59     | 1.47%   |
| 2.01-3.0        | 28        | 50     | 1.03%   |
| 10.01-20.0      | 3         | 15     | 0.11%   |
| More than 100.0 | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 926       | 31.87%  |
| 251-500        | 723       | 24.88%  |
| 501-1000       | 434       | 14.93%  |
| 51-100         | 247       | 8.5%    |
| 1001-2000      | 167       | 5.75%   |
| 21-50          | 144       | 4.96%   |
| More than 3000 | 104       | 3.58%   |
| 1-20           | 65        | 2.24%   |
| 2001-3000      | 57        | 1.96%   |
| Unknown        | 39        | 1.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1172      | 38.77%  |
| 21-50          | 823       | 27.22%  |
| 51-100         | 361       | 11.94%  |
| 101-250        | 284       | 9.39%   |
| 251-500        | 152       | 5.03%   |
| 501-1000       | 93        | 3.08%   |
| More than 3000 | 49        | 1.62%   |
| Unknown        | 39        | 1.29%   |
| 1001-2000      | 37        | 1.22%   |
| 2001-3000      | 13        | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                   | 3         | 3      | 3.66%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 3.66%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 2.44%   |
| Seagate ST9500420AS 500GB                | 2         | 2      | 2.44%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 2.44%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 1.22%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 1.22%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 1.22%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 1.22%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 1.22%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 1.22%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 1      | 1.22%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 1.22%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.22%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 1.22%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 1.22%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 1.22%   |
| WDC WD Green 2.5 1000GB SSD              | 1         | 1      | 1.22%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 1.22%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 1.22%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 1.22%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 1.22%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 1.22%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 1.22%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 1.22%   |
| Teclast 128GB NS550-2242 SSD             | 1         | 1      | 1.22%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 1         | 1      | 1.22%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1         | 1      | 1.22%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 1.22%   |
| Seagate ST9320310AS 320GB                | 1         | 1      | 1.22%   |
| Seagate ST9250315AS 250GB                | 1         | 1      | 1.22%   |
| Seagate ST9200420ASG 200GB               | 1         | 1      | 1.22%   |
| Seagate ST9160411ASG 160GB               | 1         | 1      | 1.22%   |
| Seagate ST8000DM004-2CX188 8TB           | 1         | 1      | 1.22%   |
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 1.22%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1      | 1.22%   |
| Seagate ST500LM000-SSHD-8GB              | 1         | 1      | 1.22%   |
| Seagate ST500DM002-1BD142 500GB          | 1         | 1      | 1.22%   |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 1      | 1.22%   |
| Seagate ST3500514NS 500GB                | 1         | 1      | 1.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 27     | 32.1%   |
| WDC                 | 13        | 14     | 16.05%  |
| Toshiba             | 12        | 12     | 14.81%  |
| HGST                | 7         | 7      | 8.64%   |
| Kingston            | 6         | 6      | 7.41%   |
| Samsung Electronics | 4         | 4      | 4.94%   |
| Hitachi             | 3         | 3      | 3.7%    |
| A-DATA Technology   | 2         | 2      | 2.47%   |
| Teclast             | 1         | 1      | 1.23%   |
| SK hynix            | 1         | 1      | 1.23%   |
| Silicon Motion      | 1         | 1      | 1.23%   |
| OCZ                 | 1         | 1      | 1.23%   |
| Maxtor              | 1         | 1      | 1.23%   |
| LITEONIT            | 1         | 1      | 1.23%   |
| Intel               | 1         | 1      | 1.23%   |
| Hewlett-Packard     | 1         | 1      | 1.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 27     | 42.62%  |
| WDC                 | 12        | 13     | 19.67%  |
| Toshiba             | 10        | 10     | 16.39%  |
| HGST                | 7         | 7      | 11.48%  |
| Hitachi             | 3         | 3      | 4.92%   |
| Samsung Electronics | 2         | 2      | 3.28%   |
| Maxtor              | 1         | 1      | 1.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 58        | 63     | 74.36%  |
| SSD  | 17        | 17     | 21.79%  |
| NVMe | 3         | 3      | 3.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2499      | 4591   | 86.14%  |
| Works    | 323       | 538    | 11.13%  |
| Malfunc  | 77        | 83     | 2.65%   |
| Failed   | 2         | 2      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1929      | 57.93%  |
| AMD                              | 543       | 16.31%  |
| Samsung Electronics              | 238       | 7.15%   |
| SanDisk                          | 112       | 3.36%   |
| SK hynix                         | 48        | 1.44%   |
| Kingston Technology Company      | 48        | 1.44%   |
| Nvidia                           | 46        | 1.38%   |
| ASMedia Technology               | 46        | 1.38%   |
| Phison Electronics               | 43        | 1.29%   |
| Silicon Motion                   | 33        | 0.99%   |
| Toshiba America Info Systems     | 28        | 0.84%   |
| Micron Technology                | 28        | 0.84%   |
| JMicron Technology               | 28        | 0.84%   |
| Marvell Technology Group         | 26        | 0.78%   |
| KIOXIA                           | 23        | 0.69%   |
| Micron/Crucial Technology        | 20        | 0.6%    |
| ADATA Technology                 | 18        | 0.54%   |
| Realtek Semiconductor            | 11        | 0.33%   |
| Silicon Image                    | 8         | 0.24%   |
| VIA Technologies                 | 7         | 0.21%   |
| Lite-On Technology               | 6         | 0.18%   |
| Union Memory (Shenzhen)          | 5         | 0.15%   |
| Seagate Technology               | 5         | 0.15%   |
| Broadcom / LSI                   | 4         | 0.12%   |
| Solid State Storage Technology   | 3         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.09%   |
| Apple                            | 3         | 0.09%   |
| Yangtze Memory Technologies      | 2         | 0.06%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| OCZ Technology Group             | 2         | 0.06%   |
| LSI Logic / Symbios Logic        | 2         | 0.06%   |
| INNOGRIT                         | 2         | 0.06%   |
| TenaFe                           | 1         | 0.03%   |
| Netac Technology                 | 1         | 0.03%   |
| Lenovo                           | 1         | 0.03%   |
| HighPoint Technologies           | 1         | 0.03%   |
| Dell                             | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| Beijing Starblaze Technology     | 1         | 0.03%   |
| Adaptec                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 367       | 9.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 155       | 4.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 145       | 3.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 132       | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 110       | 2.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 103       | 2.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 102       | 2.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 78        | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 77        | 2%      |
| AMD 400 Series Chipset SATA Controller                                                  | 68        | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 66        | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 65        | 1.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 62        | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 61        | 1.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 59        | 1.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 59        | 1.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 55        | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 55        | 1.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 52        | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 52        | 1.35%   |
| Samsung NVMe SSD Controller 980                                                         | 50        | 1.3%    |
| Intel SATA Controller [RAID mode]                                                       | 48        | 1.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 46        | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 44        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 43        | 1.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 42        | 1.09%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 42        | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 40        | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 39        | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 36        | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 35        | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 34        | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 32        | 0.83%   |
| AMD 500 Series Chipset SATA Controller                                                  | 30        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 29        | 0.75%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 28        | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 27        | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 26        | 0.67%   |
| Micron NVMe Storage Controller                                                          | 26        | 0.67%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 26        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2117      | 61.47%  |
| NVMe | 683       | 19.83%  |
| IDE  | 388       | 11.27%  |
| RAID | 247       | 7.17%   |
| SAS  | 6         | 0.17%   |
| SCSI | 3         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2191      | 77.86%  |
| AMD    | 623       | 22.14%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 41        | 1.46%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 33        | 1.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 0.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 26        | 0.92%   |
| AMD Ryzen 5 3600 6-Core Processor             | 25        | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 24        | 0.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 23        | 0.82%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 22        | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 19        | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 19        | 0.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.64%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 18        | 0.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 0.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 17        | 0.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 17        | 0.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 0.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 16        | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 15        | 0.53%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 15        | 0.53%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 15        | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 0.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 14        | 0.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 13        | 0.46%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 13        | 0.46%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 13        | 0.46%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 13        | 0.46%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 13        | 0.46%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 13        | 0.46%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 12        | 0.43%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 12        | 0.43%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.43%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 12        | 0.43%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 12        | 0.43%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 12        | 0.43%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 12        | 0.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 0.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.39%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 11        | 0.39%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 11        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 661       | 23.47%  |
| Intel Core i7           | 398       | 14.13%  |
| Intel Core i3           | 271       | 9.62%   |
| Intel Celeron           | 185       | 6.57%   |
| AMD Ryzen 5             | 146       | 5.18%   |
| Intel Core 2 Duo        | 143       | 5.08%   |
| Other                   | 141       | 5.01%   |
| AMD Ryzen 7             | 93        | 3.3%    |
| Intel Atom              | 88        | 3.13%   |
| Intel Pentium           | 85        | 3.02%   |
| Intel Xeon              | 64        | 2.27%   |
| AMD FX                  | 47        | 1.67%   |
| AMD Ryzen 9             | 37        | 1.31%   |
| AMD A6                  | 37        | 1.31%   |
| Intel Pentium Dual-Core | 35        | 1.24%   |
| AMD A10                 | 28        | 0.99%   |
| Intel Core 2 Quad       | 27        | 0.96%   |
| AMD A4                  | 27        | 0.96%   |
| AMD A8                  | 26        | 0.92%   |
| AMD Ryzen 3             | 25        | 0.89%   |
| Intel Pentium Dual      | 24        | 0.85%   |
| Intel Core 2            | 17        | 0.6%    |
| AMD E1                  | 15        | 0.53%   |
| AMD Athlon II X2        | 14        | 0.5%    |
| Intel Core i9           | 13        | 0.46%   |
| AMD Phenom II X4        | 12        | 0.43%   |
| Intel Pentium Silver    | 11        | 0.39%   |
| AMD Athlon              | 10        | 0.36%   |
| Intel Pentium Gold      | 9         | 0.32%   |
| Intel Core M            | 8         | 0.28%   |
| AMD E                   | 8         | 0.28%   |
| AMD Athlon 64 X2        | 8         | 0.28%   |
| AMD Turion 64 X2 Mobile | 7         | 0.25%   |
| AMD Phenom II X6        | 7         | 0.25%   |
| AMD Athlon II X4        | 7         | 0.25%   |
| Intel Pentium 4         | 5         | 0.18%   |
| AMD E2                  | 5         | 0.18%   |
| AMD Athlon II           | 5         | 0.18%   |
| Intel Core m5           | 4         | 0.14%   |
| AMD Ryzen 7 PRO         | 4         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1326      | 47.07%  |
| 4      | 1007      | 35.75%  |
| 6      | 220       | 7.81%   |
| 8      | 148       | 5.25%   |
| 1      | 37        | 1.31%   |
| 12     | 25        | 0.89%   |
| 3      | 19        | 0.67%   |
| 16     | 15        | 0.53%   |
| 10     | 14        | 0.5%    |
| 14     | 4         | 0.14%   |
| 40     | 1         | 0.04%   |
| 28     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2802      | 99.57%  |
| 2      | 12        | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1697      | 60.28%  |
| 1      | 1118      | 39.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2814      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 228       | 7.98%   |
| 0x306a9    | 222       | 7.77%   |
| Unknown    | 202       | 7.07%   |
| 0x306c3    | 161       | 5.64%   |
| 0x1067a    | 134       | 4.69%   |
| 0x40651    | 88        | 3.08%   |
| 0x806c1    | 77        | 2.7%    |
| 0x20655    | 76        | 2.66%   |
| 0x806e9    | 68        | 2.38%   |
| 0x406e3    | 66        | 2.31%   |
| 0x30678    | 65        | 2.28%   |
| 0x306d4    | 62        | 2.17%   |
| 0x406c4    | 59        | 2.07%   |
| 0x506e3    | 57        | 2%      |
| 0x906ea    | 55        | 1.93%   |
| 0x806ea    | 54        | 1.89%   |
| 0x08701021 | 46        | 1.61%   |
| 0x806ec    | 45        | 1.58%   |
| 0x6fd      | 43        | 1.51%   |
| 0x906e9    | 41        | 1.44%   |
| 0x706a8    | 39        | 1.37%   |
| 0x06000852 | 33        | 1.16%   |
| 0x506c9    | 31        | 1.09%   |
| 0x20652    | 31        | 1.09%   |
| 0x10676    | 31        | 1.09%   |
| 0x08108109 | 29        | 1.02%   |
| 0x706e5    | 27        | 0.95%   |
| 0x6fb      | 27        | 0.95%   |
| 0x406c3    | 25        | 0.88%   |
| 0x0a50000c | 24        | 0.84%   |
| 0x07030105 | 24        | 0.84%   |
| 0x010000c8 | 24        | 0.84%   |
| 0x06001119 | 22        | 0.77%   |
| 0x08600106 | 20        | 0.7%    |
| 0x0800820d | 20        | 0.7%    |
| 0x06006705 | 20        | 0.7%    |
| 0x0700010f | 19        | 0.67%   |
| 0xa0653    | 18        | 0.63%   |
| 0x0a201016 | 18        | 0.63%   |
| 0x08108102 | 18        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 329       | 11.69%  |
| Haswell          | 277       | 9.84%   |
| SandyBridge      | 248       | 8.81%   |
| IvyBridge        | 235       | 8.35%   |
| Penryn           | 169       | 6%      |
| Silvermont       | 159       | 5.65%   |
| Skylake          | 130       | 4.62%   |
| Westmere         | 116       | 4.12%   |
| Zen 2            | 99        | 3.52%   |
| Core             | 99        | 3.52%   |
| TigerLake        | 88        | 3.13%   |
| Zen 3            | 77        | 2.74%   |
| Zen+             | 73        | 2.59%   |
| Broadwell        | 66        | 2.34%   |
| Piledriver       | 61        | 2.17%   |
| K10              | 59        | 2.1%    |
| CometLake        | 57        | 2.02%   |
| Goldmont plus    | 54        | 1.92%   |
| Excavator        | 51        | 1.81%   |
| Icelake          | 49        | 1.74%   |
| Zen              | 42        | 1.49%   |
| Unknown          | 41        | 1.46%   |
| Puma             | 37        | 1.31%   |
| Goldmont         | 34        | 1.21%   |
| Nehalem          | 30        | 1.07%   |
| Jaguar           | 23        | 0.82%   |
| K8 Hammer        | 20        | 0.71%   |
| Alderlake Hybrid | 16        | 0.57%   |
| Bobcat           | 14        | 0.5%    |
| K10 Llano        | 12        | 0.43%   |
| Bulldozer        | 11        | 0.39%   |
| Steamroller      | 10        | 0.36%   |
| Tremont          | 9         | 0.32%   |
| NetBurst         | 8         | 0.28%   |
| Bonnell          | 8         | 0.28%   |
| K8 & K10 hybrid  | 4         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1696      | 52.65%  |
| Nvidia                           | 785       | 24.37%  |
| AMD                              | 732       | 22.73%  |
| VIA Technologies                 | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| Matrox Electronics Systems       | 2         | 0.06%   |
| ASPEED Technology                | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 190       | 5.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 140       | 4.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 89        | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 85        | 2.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 76        | 2.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 72        | 2.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 68        | 2.06%   |
| Intel HD Graphics 620                                                                    | 62        | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 59        | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 56        | 1.7%    |
| Intel UHD Graphics 620                                                                   | 53        | 1.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 50        | 1.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 49        | 1.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 47        | 1.42%   |
| Intel HD Graphics 5500                                                                   | 41        | 1.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 39        | 1.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 38        | 1.15%   |
| AMD Renoir                                                                               | 38        | 1.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 38        | 1.15%   |
| Intel HD Graphics 630                                                                    | 35        | 1.06%   |
| Intel HD Graphics 530                                                                    | 34        | 1.03%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 31        | 0.94%   |
| Intel HD Graphics 500                                                                    | 29        | 0.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 29        | 0.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 28        | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 0.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 27        | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 27        | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 26        | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 25        | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 25        | 0.76%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 24        | 0.73%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 23        | 0.7%    |
| AMD Lucienne                                                                             | 23        | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22        | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 20        | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 18        | 0.55%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 18        | 0.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1335      | 47.26%  |
| 1 x AMD        | 597       | 21.13%  |
| 1 x Nvidia     | 491       | 17.38%  |
| Intel + Nvidia | 248       | 8.78%   |
| Intel + AMD    | 69        | 2.44%   |
| AMD + Nvidia   | 34        | 1.2%    |
| 2 x AMD        | 33        | 1.17%   |
| 2 x Nvidia     | 5         | 0.18%   |
| Other          | 4         | 0.14%   |
| 1 x VIA        | 3         | 0.11%   |
| 1 x SiS        | 2         | 0.07%   |
| 1 x Matrox     | 2         | 0.07%   |
| 2 x Intel      | 1         | 0.04%   |
| 1 x ASPEED     | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2278      | 80.35%  |
| Proprietary | 473       | 16.68%  |
| Unknown     | 84        | 2.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1660      | 57.96%  |
| 0.01-0.5   | 337       | 11.77%  |
| 1.01-2.0   | 277       | 9.67%   |
| 0.51-1.0   | 248       | 8.66%   |
| 3.01-4.0   | 140       | 4.89%   |
| 7.01-8.0   | 98        | 3.42%   |
| 5.01-6.0   | 48        | 1.68%   |
| 8.01-16.0  | 31        | 1.08%   |
| 2.01-3.0   | 21        | 0.73%   |
| 16.01-24.0 | 4         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 362       | 12.61%  |
| AU Optronics            | 336       | 11.71%  |
| Chimei Innolux          | 258       | 8.99%   |
| LG Display              | 256       | 8.92%   |
| BOE                     | 232       | 8.08%   |
| Dell                    | 142       | 4.95%   |
| Goldstar                | 129       | 4.49%   |
| Hewlett-Packard         | 103       | 3.59%   |
| Acer                    | 85        | 2.96%   |
| Apple                   | 80        | 2.79%   |
| Philips                 | 68        | 2.37%   |
| AOC                     | 62        | 2.16%   |
| Chi Mei Optoelectronics | 57        | 1.99%   |
| Ancor Communications    | 53        | 1.85%   |
| BenQ                    | 50        | 1.74%   |
| Lenovo                  | 46        | 1.6%    |
| Sharp                   | 36        | 1.25%   |
| LG Electronics          | 26        | 0.91%   |
| Sony                    | 24        | 0.84%   |
| PANDA                   | 23        | 0.8%    |
| LG Philips              | 22        | 0.77%   |
| Unknown                 | 21        | 0.73%   |
| Unknown                 | 21        | 0.73%   |
| ViewSonic               | 20        | 0.7%    |
| InfoVision              | 20        | 0.7%    |
| Vizio                   | 19        | 0.66%   |
| ASUSTek Computer        | 18        | 0.63%   |
| Iiyama                  | 17        | 0.59%   |
| Fujitsu Siemens         | 11        | 0.38%   |
| Toshiba                 | 10        | 0.35%   |
| Sceptre Tech            | 10        | 0.35%   |
| HPN                     | 10        | 0.35%   |
| Eizo                    | 10        | 0.35%   |
| CPT                     | 10        | 0.35%   |
| Panasonic               | 9         | 0.31%   |
| NEC Computers           | 9         | 0.31%   |
| MSI                     | 9         | 0.31%   |
| HannStar                | 8         | 0.28%   |
| LGD                     | 6         | 0.21%   |
| AUS                     | 6         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 21        | 0.71%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 18        | 0.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 14        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 13        | 0.44%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 12        | 0.41%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 10        | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 10        | 0.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 10        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.34%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 10        | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 10        | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 9         | 0.31%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 8         | 0.27%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 8         | 0.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.27%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 7         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.24%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 7         | 0.24%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 7         | 0.24%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 7         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 6         | 0.2%    |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                         | 6         | 0.2%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 5         | 0.17%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch    | 5         | 0.17%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 5         | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 5         | 0.17%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.17%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 5         | 0.17%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 5         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1029      | 36.88%  |
| 1366x768 (WXGA)    | 725       | 25.99%  |
| 3840x2160 (4K)     | 147       | 5.27%   |
| 1600x900 (HD+)     | 147       | 5.27%   |
| 2560x1440 (QHD)    | 87        | 3.12%   |
| 1280x800 (WXGA)    | 83        | 2.97%   |
| 1680x1050 (WSXGA+) | 76        | 2.72%   |
| 1440x900 (WXGA+)   | 73        | 2.62%   |
| 1280x1024 (SXGA)   | 70        | 2.51%   |
| Unknown            | 55        | 1.97%   |
| 1920x1200 (WUXGA)  | 40        | 1.43%   |
| 1360x768           | 34        | 1.22%   |
| 3440x1440          | 27        | 0.97%   |
| 3840x1080          | 21        | 0.75%   |
| 2560x1600          | 19        | 0.68%   |
| 2560x1080          | 16        | 0.57%   |
| 1920x540           | 15        | 0.54%   |
| 2736x1824          | 13        | 0.47%   |
| 2256x1504          | 9         | 0.32%   |
| 2160x1440          | 9         | 0.32%   |
| 3200x1800 (QHD+)   | 7         | 0.25%   |
| 1600x1200          | 6         | 0.22%   |
| 1024x768 (XGA)     | 6         | 0.22%   |
| 3840x2400          | 5         | 0.18%   |
| 2880x1800          | 5         | 0.18%   |
| 5760x1080          | 4         | 0.14%   |
| 3840x1600          | 4         | 0.14%   |
| 4480x1440          | 3         | 0.11%   |
| 3600x1080          | 3         | 0.11%   |
| 2880x1920          | 3         | 0.11%   |
| 1920x1280          | 3         | 0.11%   |
| 1280x720 (HD)      | 3         | 0.11%   |
| 1024x600           | 3         | 0.11%   |
| 5760x2160          | 2         | 0.07%   |
| 4480x1600          | 2         | 0.07%   |
| 4480x1080          | 2         | 0.07%   |
| 3360x1080          | 2         | 0.07%   |
| 3200x1200          | 2         | 0.07%   |
| 3120x1050          | 2         | 0.07%   |
| 2944x1080          | 2         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 743       | 26.17%  |
| 13      | 263       | 9.26%   |
| Unknown | 236       | 8.31%   |
| 14      | 199       | 7.01%   |
| 17      | 173       | 6.09%   |
| 27      | 160       | 5.64%   |
| 24      | 136       | 4.79%   |
| 23      | 132       | 4.65%   |
| 21      | 129       | 4.54%   |
| 11      | 74        | 2.61%   |
| 19      | 72        | 2.54%   |
| 31      | 65        | 2.29%   |
| 12      | 61        | 2.15%   |
| 18      | 60        | 2.11%   |
| 20      | 59        | 2.08%   |
| 22      | 53        | 1.87%   |
| 34      | 33        | 1.16%   |
| 40      | 19        | 0.67%   |
| 84      | 18        | 0.63%   |
| 16      | 15        | 0.53%   |
| 72      | 14        | 0.49%   |
| 54      | 14        | 0.49%   |
| 32      | 13        | 0.46%   |
| 25      | 10        | 0.35%   |
| 10      | 10        | 0.35%   |
| 26      | 9         | 0.32%   |
| 36      | 7         | 0.25%   |
| 65      | 5         | 0.18%   |
| 52      | 5         | 0.18%   |
| 29      | 5         | 0.18%   |
| 49      | 4         | 0.14%   |
| 47      | 4         | 0.14%   |
| 37      | 4         | 0.14%   |
| 64      | 3         | 0.11%   |
| 48      | 3         | 0.11%   |
| 42      | 3         | 0.11%   |
| 35      | 3         | 0.11%   |
| 33      | 3         | 0.11%   |
| 74      | 2         | 0.07%   |
| 57      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1085      | 38.81%  |
| 501-600     | 401       | 14.34%  |
| 401-500     | 335       | 11.98%  |
| 201-300     | 278       | 9.94%   |
| Unknown     | 236       | 8.44%   |
| 351-400     | 201       | 7.19%   |
| 601-700     | 87        | 3.11%   |
| 701-800     | 56        | 2%      |
| 1001-1500   | 45        | 1.61%   |
| 1501-2000   | 37        | 1.32%   |
| 801-900     | 28        | 1%      |
| 901-1000    | 6         | 0.21%   |
| 101-200     | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1941      | 74%     |
| 16/10   | 294       | 11.21%  |
| Unknown | 214       | 8.16%   |
| 5/4     | 61        | 2.33%   |
| 3/2     | 41        | 1.56%   |
| 21/9    | 41        | 1.56%   |
| 4/3     | 20        | 0.76%   |
| 32/9    | 6         | 0.23%   |
| 6/5     | 2         | 0.08%   |
| 3.73    | 2         | 0.08%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 741       | 26.26%  |
| 81-90          | 364       | 12.9%   |
| 201-250        | 359       | 12.72%  |
| Unknown        | 236       | 8.36%   |
| 151-200        | 185       | 6.56%   |
| 301-350        | 165       | 5.85%   |
| 351-500        | 122       | 4.32%   |
| 121-130        | 121       | 4.29%   |
| 71-80          | 104       | 3.69%   |
| 141-150        | 81        | 2.87%   |
| 51-60          | 76        | 2.69%   |
| More than 1000 | 75        | 2.66%   |
| 61-70          | 53        | 1.88%   |
| 251-300        | 50        | 1.77%   |
| 501-1000       | 43        | 1.52%   |
| 131-140        | 18        | 0.64%   |
| 111-120        | 14        | 0.5%    |
| 41-50          | 8         | 0.28%   |
| 91-100         | 6         | 0.21%   |
| 1-40           | 1         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 854       | 31.01%  |
| 51-100        | 813       | 29.52%  |
| 121-160       | 597       | 21.68%  |
| Unknown       | 236       | 8.57%   |
| 161-240       | 134       | 4.87%   |
| 1-50          | 74        | 2.69%   |
| More than 240 | 46        | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2394      | 83.82%  |
| 2     | 344       | 12.04%  |
| 0     | 88        | 3.08%   |
| 3     | 27        | 0.95%   |
| 4     | 2         | 0.07%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1507      | 35.15%  |
| Intel                             | 1200      | 27.99%  |
| Qualcomm Atheros                  | 545       | 12.71%  |
| Broadcom                          | 315       | 7.35%   |
| Broadcom Limited                  | 88        | 2.05%   |
| Ralink Technology                 | 65        | 1.52%   |
| TP-Link                           | 61        | 1.42%   |
| Marvell Technology Group          | 55        | 1.28%   |
| Ralink                            | 50        | 1.17%   |
| MediaTek                          | 43        | 1%      |
| Nvidia                            | 40        | 0.93%   |
| Samsung Electronics               | 29        | 0.68%   |
| ASIX Electronics                  | 22        | 0.51%   |
| NetGear                           | 18        | 0.42%   |
| Xiaomi                            | 17        | 0.4%    |
| Dell                              | 15        | 0.35%   |
| Qualcomm Atheros Communications   | 14        | 0.33%   |
| DisplayLink                       | 14        | 0.33%   |
| Huawei Technologies               | 13        | 0.3%    |
| Microsoft                         | 12        | 0.28%   |
| Hewlett-Packard                   | 10        | 0.23%   |
| D-Link                            | 10        | 0.23%   |
| JMicron Technology                | 9         | 0.21%   |
| Edimax Technology                 | 9         | 0.21%   |
| D-Link System                     | 9         | 0.21%   |
| ASUSTek Computer                  | 8         | 0.19%   |
| Sierra Wireless                   | 7         | 0.16%   |
| Qualcomm                          | 7         | 0.16%   |
| OPPO Electronics                  | 7         | 0.16%   |
| Motorola PCS                      | 5         | 0.12%   |
| Linksys                           | 5         | 0.12%   |
| Ericsson Business Mobile Networks | 5         | 0.12%   |
| Aquantia                          | 5         | 0.12%   |
| T & A Mobile Phones               | 4         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.09%   |
| Google                            | 4         | 0.09%   |
| VIA Technologies                  | 3         | 0.07%   |
| Belkin Components                 | 3         | 0.07%   |
| ZyDAS                             | 2         | 0.05%   |
| U-Blox                            | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 950       | 19.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 231       | 4.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 134       | 2.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 97        | 1.94%   |
| Intel Wi-Fi 6 AX200                                               | 92        | 1.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 77        | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 76        | 1.52%   |
| Intel Wireless 7265                                               | 69        | 1.38%   |
| Intel Wireless 7260                                               | 69        | 1.38%   |
| Intel Wireless 8265 / 8275                                        | 66        | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 64        | 1.28%   |
| Intel Wi-Fi 6 AX201                                               | 61        | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 57        | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 56        | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 53        | 1.06%   |
| Intel I211 Gigabit Network Connection                             | 51        | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 49        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                     | 49        | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 47        | 0.94%   |
| Intel Wireless 3165                                               | 46        | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 43        | 0.86%   |
| Intel Wireless 8260                                               | 42        | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 40        | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 39        | 0.78%   |
| Realtek 802.11ac NIC                                              | 39        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 36        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 0.66%   |
| Intel Ethernet Connection (2) I219-V                              | 33        | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 31        | 0.62%   |
| Ralink MT7601U Wireless Adapter                                   | 30        | 0.6%    |
| Intel Ethernet Controller I225-V                                  | 29        | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 27        | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 27        | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 27        | 0.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 27        | 0.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 26        | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 24        | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 23        | 0.46%   |
| Intel WiFi Link 5100                                              | 21        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 904       | 37.73%  |
| Realtek Semiconductor                 | 446       | 18.61%  |
| Qualcomm Atheros                      | 433       | 18.07%  |
| Broadcom                              | 223       | 9.31%   |
| Ralink Technology                     | 65        | 2.71%   |
| Broadcom Limited                      | 55        | 2.3%    |
| TP-Link                               | 53        | 2.21%   |
| Ralink                                | 50        | 2.09%   |
| MediaTek                              | 37        | 1.54%   |
| NetGear                               | 18        | 0.75%   |
| Marvell Technology Group              | 15        | 0.63%   |
| Qualcomm Atheros Communications       | 14        | 0.58%   |
| D-Link                                | 10        | 0.42%   |
| Microsoft                             | 9         | 0.38%   |
| Edimax Technology                     | 9         | 0.38%   |
| Sierra Wireless                       | 7         | 0.29%   |
| Dell                                  | 7         | 0.29%   |
| D-Link System                         | 7         | 0.29%   |
| ASUSTek Computer                      | 7         | 0.29%   |
| Linksys                               | 5         | 0.21%   |
| Belkin Components                     | 3         | 0.13%   |
| ZyDAS                                 | 2         | 0.08%   |
| Gemtek                                | 2         | 0.08%   |
| Fibocom                               | 2         | 0.08%   |
| AVM                                   | 2         | 0.08%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| Xiaomi                                | 1         | 0.04%   |
| TRENDnet                              | 1         | 0.04%   |
| Qualcomm                              | 1         | 0.04%   |
| Panasonic (Matsushita)                | 1         | 0.04%   |
| Ovislink                              | 1         | 0.04%   |
| Mercucys                              | 1         | 0.04%   |
| Hewlett-Packard                       | 1         | 0.04%   |
| Askey Computer                        | 1         | 0.04%   |
| ADMtek                                | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 97        | 4.01%   |
| Intel Wi-Fi 6 AX200                                            | 92        | 3.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 77        | 3.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 76        | 3.14%   |
| Intel Wireless 7265                                            | 69        | 2.85%   |
| Intel Wireless 7260                                            | 69        | 2.85%   |
| Intel Wireless 8265 / 8275                                     | 66        | 2.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 64        | 2.64%   |
| Intel Wi-Fi 6 AX201                                            | 61        | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 56        | 2.31%   |
| Broadcom BCM43142 802.11b/g/n                                  | 49        | 2.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 47        | 1.94%   |
| Intel Wireless 3165                                            | 46        | 1.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 43        | 1.78%   |
| Intel Wireless 8260                                            | 42        | 1.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 40        | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 39        | 1.61%   |
| Realtek 802.11ac NIC                                           | 39        | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 36        | 1.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 31        | 1.28%   |
| Ralink MT7601U Wireless Adapter                                | 30        | 1.24%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 27        | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 27        | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 27        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 27        | 1.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 26        | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 24        | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 23        | 0.95%   |
| Intel WiFi Link 5100                                           | 21        | 0.87%   |
| Intel Centrino Ultimate-N 6300                                 | 21        | 0.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 21        | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 20        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 19        | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 18        | 0.74%   |
| Intel Wireless 3160                                            | 18        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 18        | 0.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 17        | 0.7%    |
| Intel Wireless-AC 9260                                         | 17        | 0.7%    |
| Intel Centrino Wireless-N 2230                                 | 17        | 0.7%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 17        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1311      | 52.8%   |
| Intel                             | 600       | 24.16%  |
| Qualcomm Atheros                  | 155       | 6.24%   |
| Broadcom                          | 136       | 5.48%   |
| Nvidia                            | 40        | 1.61%   |
| Marvell Technology Group          | 40        | 1.61%   |
| Broadcom Limited                  | 35        | 1.41%   |
| Samsung Electronics               | 28        | 1.13%   |
| ASIX Electronics                  | 22        | 0.89%   |
| Xiaomi                            | 16        | 0.64%   |
| DisplayLink                       | 14        | 0.56%   |
| Huawei Technologies               | 10        | 0.4%    |
| JMicron Technology                | 9         | 0.36%   |
| TP-Link                           | 8         | 0.32%   |
| OPPO Electronics                  | 7         | 0.28%   |
| Qualcomm                          | 6         | 0.24%   |
| MediaTek                          | 6         | 0.24%   |
| Aquantia                          | 5         | 0.2%    |
| Google                            | 4         | 0.16%   |
| VIA Technologies                  | 3         | 0.12%   |
| Motorola PCS                      | 3         | 0.12%   |
| Hewlett-Packard                   | 3         | 0.12%   |
| Sundance Technology Inc / IC Plus | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.08%   |
| Microsoft                         | 2         | 0.08%   |
| HMD Global                        | 2         | 0.08%   |
| D-Link System                     | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |
| Sun Microsystems                  | 1         | 0.04%   |
| Research In Motion                | 1         | 0.04%   |
| Novatel Wireless                  | 1         | 0.04%   |
| Motorola BCS                      | 1         | 0.04%   |
| LG Electronics                    | 1         | 0.04%   |
| Lenovo                            | 1         | 0.04%   |
| ICS Advent                        | 1         | 0.04%   |
| GoPro                             | 1         | 0.04%   |
| ASUSTek Computer                  | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 950       | 37.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 231       | 9.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 134       | 5.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 57        | 2.26%   |
| Intel Ethernet Connection I217-LM                                 | 53        | 2.1%    |
| Intel I211 Gigabit Network Connection                             | 51        | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 49        | 1.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 1.31%   |
| Intel Ethernet Connection (2) I219-V                              | 33        | 1.31%   |
| Intel Ethernet Controller I225-V                                  | 29        | 1.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 21        | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 20        | 0.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.67%   |
| Intel Ethernet Connection I219-LM                                 | 17        | 0.67%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 17        | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 17        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 15        | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 15        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 13        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.52%   |
| Intel 82579V Gigabit Network Connection                           | 13        | 0.52%   |
| Intel 82567LM Gigabit Network Connection                          | 13        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 12        | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 12        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.48%   |
| Nvidia MCP61 Ethernet                                             | 11        | 0.44%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 11        | 0.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10        | 0.4%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 10        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2346      | 50.61%  |
| WiFi     | 2239      | 48.31%  |
| Modem    | 39        | 0.84%   |
| Unknown  | 11        | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1760      | 60.17%  |
| Ethernet | 1161      | 39.69%  |
| Modem    | 2         | 0.07%   |
| Unknown  | 2         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1525      | 53.96%  |
| 1     | 1145      | 40.52%  |
| 0     | 100       | 3.54%   |
| 3     | 50        | 1.77%   |
| 5     | 3         | 0.11%   |
| 4     | 2         | 0.07%   |
| 7     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1949      | 68.31%  |
| Yes  | 904       | 31.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 682       | 40.52%  |
| Realtek Semiconductor           | 199       | 11.82%  |
| Qualcomm Atheros Communications | 161       | 9.57%   |
| Broadcom                        | 97        | 5.76%   |
| Cambridge Silicon Radio         | 93        | 5.53%   |
| Apple                           | 88        | 5.23%   |
| IMC Networks                    | 84        | 4.99%   |
| Foxconn / Hon Hai               | 45        | 2.67%   |
| Lite-On Technology              | 44        | 2.61%   |
| Dell                            | 33        | 1.96%   |
| ASUSTek Computer                | 26        | 1.54%   |
| Hewlett-Packard                 | 25        | 1.49%   |
| Toshiba                         | 23        | 1.37%   |
| Ralink                          | 13        | 0.77%   |
| Marvell Semiconductor           | 13        | 0.77%   |
| MediaTek                        | 9         | 0.53%   |
| Realtek                         | 7         | 0.42%   |
| TP-Link                         | 6         | 0.36%   |
| Foxconn International           | 6         | 0.36%   |
| Integrated System Solution      | 5         | 0.3%    |
| Alps Electric                   | 5         | 0.3%    |
| Dynex                           | 4         | 0.24%   |
| Belkin Components               | 2         | 0.12%   |
| Askey Computer                  | 2         | 0.12%   |
| Actions                         | 2         | 0.12%   |
| Sitecom Europe                  | 1         | 0.06%   |
| Ralink Technology               | 1         | 0.06%   |
| Qcom                            | 1         | 0.06%   |
| National Semiconductor          | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |
| D-Link System                   | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |
| Unknown                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 294       | 17.46%  |
| Realtek Bluetooth Radio                             | 130       | 7.72%   |
| Intel AX201 Bluetooth                               | 100       | 5.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 93        | 5.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 81        | 4.81%   |
| Intel AX200 Bluetooth                               | 78        | 4.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 68        | 4.04%   |
| Realtek  Bluetooth 4.2 Adapter                      | 44        | 2.61%   |
| Apple Bluetooth Host Controller                     | 42        | 2.49%   |
| Intel AX210 Bluetooth                               | 40        | 2.38%   |
| IMC Networks Bluetooth Device                       | 32        | 1.9%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 31        | 1.84%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 26        | 1.54%   |
| IMC Networks Bluetooth Radio                        | 24        | 1.43%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 24        | 1.43%   |
| Intel Wireless-AC 3168 Bluetooth                    | 22        | 1.31%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 22        | 1.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 21        | 1.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 18        | 1.07%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 17        | 1.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 16        | 0.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 0.89%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.89%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 0.83%   |
| Ralink RT3290 Bluetooth                             | 13        | 0.77%   |
| Marvell Bluetooth and Wireless LAN Composite        | 13        | 0.77%   |
| IMC Networks Wireless_Device                        | 13        | 0.77%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 13        | 0.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 12        | 0.71%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.71%   |
| Dell DW375 Bluetooth Module                         | 12        | 0.71%   |
| Apple Bluetooth USB Host Controller                 | 12        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 0.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 10        | 0.59%   |
| Apple Bluetooth HCI                                 | 10        | 0.59%   |
| Lite-On Bluetooth Device                            | 9         | 0.53%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 9         | 0.53%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 9         | 0.53%   |
| Toshiba Bluetooth Device                            | 8         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2071      | 54.92%  |
| AMD                                  | 784       | 20.79%  |
| Nvidia                               | 618       | 16.39%  |
| C-Media Electronics                  | 45        | 1.19%   |
| Creative Labs                        | 18        | 0.48%   |
| Logitech                             | 17        | 0.45%   |
| Texas Instruments                    | 14        | 0.37%   |
| Kingston Technology                  | 14        | 0.37%   |
| JMTek                                | 12        | 0.32%   |
| Generalplus Technology               | 12        | 0.32%   |
| Realtek Semiconductor                | 11        | 0.29%   |
| ASUSTek Computer                     | 10        | 0.27%   |
| Razer USA                            | 8         | 0.21%   |
| VIA Technologies                     | 7         | 0.19%   |
| Plantronics                          | 7         | 0.19%   |
| GN Netcom                            | 7         | 0.19%   |
| SteelSeries ApS                      | 6         | 0.16%   |
| Creative Technology                  | 6         | 0.16%   |
| DCMT Technology                      | 5         | 0.13%   |
| Tenx Technology                      | 4         | 0.11%   |
| Lenovo                               | 4         | 0.11%   |
| Focusrite-Novation                   | 4         | 0.11%   |
| RODE Microphones                     | 3         | 0.08%   |
| Micro Star International             | 3         | 0.08%   |
| DSEA A/S                             | 3         | 0.08%   |
| Corsair                              | 3         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.05%   |
| Sony                                 | 2         | 0.05%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.05%   |
| SAVITECH                             | 2         | 0.05%   |
| Samsung Electronics                  | 2         | 0.05%   |
| Numark                               | 2         | 0.05%   |
| KTMicro                              | 2         | 0.05%   |
| Dell                                 | 2         | 0.05%   |
| Cambridge Audio                      | 2         | 0.05%   |
| BR36                                 | 2         | 0.05%   |
| Blue Microphones                     | 2         | 0.05%   |
| BEHRINGER International              | 2         | 0.05%   |
| Audio-Technica                       | 2         | 0.05%   |
| Astro Gaming                         | 2         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 239       | 5.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 230       | 5.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 201       | 4.49%   |
| AMD Family 17h/19h HD Audio Controller                                     | 176       | 3.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 162       | 3.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 127       | 2.83%   |
| AMD FCH Azalia Controller                                                  | 115       | 2.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 108       | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 103       | 2.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 97        | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 93        | 2.08%   |
| Intel 8 Series HD Audio Controller                                         | 91        | 2.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 89        | 1.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 88        | 1.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 87        | 1.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 76        | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 76        | 1.7%    |
| AMD Kabini HDMI/DP Audio                                                   | 74        | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 67        | 1.5%    |
| Intel Broadwell-U Audio Controller                                         | 63        | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 60        | 1.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 59        | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                              | 56        | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 54        | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 51        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 51        | 1.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 48        | 1.07%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 48        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 41        | 0.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 39        | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 39        | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 36        | 0.8%    |
| Intel 200 Series PCH HD Audio                                              | 36        | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 34        | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                              | 33        | 0.74%   |
| Nvidia High Definition Audio Controller                                    | 33        | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 31        | 0.69%   |
| AMD High Definition Audio Controller                                       | 31        | 0.69%   |
| Intel Comet Lake PCH-LP cAVS                                               | 30        | 0.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 30        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 146       | 24.01%  |
| SK hynix               | 107       | 17.6%   |
| Micron Technology      | 61        | 10.03%  |
| Unknown                | 53        | 8.72%   |
| Kingston               | 51        | 8.39%   |
| Crucial                | 31        | 5.1%    |
| Unknown (ABCD)         | 19        | 3.13%   |
| G.Skill                | 19        | 3.13%   |
| Corsair                | 17        | 2.8%    |
| A-DATA Technology      | 14        | 2.3%    |
| Ramaxel Technology     | 11        | 1.81%   |
| Elpida                 | 10        | 1.64%   |
| Team                   | 8         | 1.32%   |
| Nanya Technology       | 7         | 1.15%   |
| Patriot                | 5         | 0.82%   |
| Smart                  | 4         | 0.66%   |
| Unknown                | 4         | 0.66%   |
| Avant                  | 3         | 0.49%   |
| Wilk                   | 2         | 0.33%   |
| Unifosa                | 2         | 0.33%   |
| Transcend              | 2         | 0.33%   |
| Timetec                | 2         | 0.33%   |
| Teikon                 | 2         | 0.33%   |
| Qimonda                | 2         | 0.33%   |
| ff                     | 2         | 0.33%   |
| fef5                   | 2         | 0.33%   |
| 4ea5                   | 2         | 0.33%   |
| Unknown (08B5)         | 1         | 0.16%   |
| Unknown (000080B30080) | 1         | 0.16%   |
| SUPER KINGSTEK         | 1         | 0.16%   |
| Strontium              | 1         | 0.16%   |
| SHARETRONIC            | 1         | 0.16%   |
| PUSKILL                | 1         | 0.16%   |
| ProMos/Mosel Vitelic   | 1         | 0.16%   |
| Patriot Memory         | 1         | 0.16%   |
| Netlist                | 1         | 0.16%   |
| Kllisre                | 1         | 0.16%   |
| Kingmax                | 1         | 0.16%   |
| GSkill                 | 1         | 0.16%   |
| Goldkey                | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 17        | 2.62%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 9         | 1.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 7         | 1.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 7         | 1.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 7         | 1.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 6         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 6         | 0.93%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 6         | 0.93%   |
| Unknown RAM Module 4096MB SODIMM DDR3                             | 4         | 0.62%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s            | 4         | 0.62%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s        | 4         | 0.62%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 4         | 0.62%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s             | 4         | 0.62%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 4         | 0.62%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 4         | 0.62%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s             | 4         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 4         | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s        | 4         | 0.62%   |
| Unknown                                                           | 4         | 0.62%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                      | 3         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 3         | 0.46%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 3         | 0.46%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 3         | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 3         | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s            | 3         | 0.46%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s            | 3         | 0.46%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s  | 3         | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 3         | 0.46%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s             | 3         | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.46%   |
| Micron RAM MT40A512M16TB-062E:J 4096MB Row Of Chips DDR4 3200MT/s | 3         | 0.46%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 3         | 0.46%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s              | 3         | 0.46%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 3         | 0.46%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 3         | 0.46%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s             | 3         | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 2         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 217       | 41.81%  |
| DDR3    | 193       | 37.19%  |
| LPDDR4  | 41        | 7.9%    |
| LPDDR3  | 21        | 4.05%   |
| DDR2    | 21        | 4.05%   |
| SDRAM   | 11        | 2.12%   |
| Unknown | 9         | 1.73%   |
| DDR     | 3         | 0.58%   |
| DDR5    | 2         | 0.39%   |
| LPDDR5  | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 314       | 60.74%  |
| DIMM         | 140       | 27.08%  |
| Row Of Chips | 53        | 10.25%  |
| Unknown      | 6         | 1.16%   |
| Chip         | 3         | 0.58%   |
| FB-DIMM      | 1         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 212       | 36.81%  |
| 4096  | 188       | 32.64%  |
| 2048  | 85        | 14.76%  |
| 16384 | 58        | 10.07%  |
| 1024  | 19        | 3.3%    |
| 32768 | 14        | 2.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 122       | 21.63%  |
| 3200    | 84        | 14.89%  |
| 2667    | 73        | 12.94%  |
| 2400    | 52        | 9.22%   |
| 1333    | 39        | 6.91%   |
| 1334    | 24        | 4.26%   |
| 2133    | 21        | 3.72%   |
| 1867    | 14        | 2.48%   |
| 4267    | 13        | 2.3%    |
| 3600    | 12        | 2.13%   |
| 667     | 12        | 2.13%   |
| 3266    | 11        | 1.95%   |
| 800     | 10        | 1.77%   |
| Unknown | 10        | 1.77%   |
| 1066    | 9         | 1.6%    |
| 3000    | 4         | 0.71%   |
| 1866    | 4         | 0.71%   |
| 1800    | 4         | 0.71%   |
| 8400    | 3         | 0.53%   |
| 2933    | 3         | 0.53%   |
| 2666    | 3         | 0.53%   |
| 2048    | 3         | 0.53%   |
| 1067    | 3         | 0.53%   |
| 4800    | 2         | 0.35%   |
| 4266    | 2         | 0.35%   |
| 4199    | 2         | 0.35%   |
| 3866    | 2         | 0.35%   |
| 3800    | 2         | 0.35%   |
| 3733    | 2         | 0.35%   |
| 3666    | 2         | 0.35%   |
| 3466    | 2         | 0.35%   |
| 3333    | 2         | 0.35%   |
| 975     | 2         | 0.35%   |
| 6400    | 1         | 0.18%   |
| 4000    | 1         | 0.18%   |
| 3500    | 1         | 0.18%   |
| 3467    | 1         | 0.18%   |
| 3400    | 1         | 0.18%   |
| 2800    | 1         | 0.18%   |
| 2200    | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 17        | 26.15%  |
| Canon                 | 13        | 20%     |
| Brother Industries    | 11        | 16.92%  |
| Seiko Epson           | 10        | 15.38%  |
| Samsung Electronics   | 9         | 13.85%  |
| Lexmark International | 2         | 3.08%   |
| Zebra                 | 1         | 1.54%   |
| QinHeng Electronics   | 1         | 1.54%   |
| Konica Minolta        | 1         | 1.54%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                     | 3         | 4.62%   |
| Samsung C460 Series                          | 2         | 3.08%   |
| HP ENVY Photo 6200 series                    | 2         | 3.08%   |
| HP DeskJet 2130 series                       | 2         | 3.08%   |
| Canon TS3100 series                          | 2         | 3.08%   |
| Canon LiDE 400                               | 2         | 3.08%   |
| Brother HL-2140 series                       | 2         | 3.08%   |
| Zebra ZP 450 Printer                         | 1         | 1.54%   |
| Seiko Epson XP-7100 Series                   | 1         | 1.54%   |
| Seiko Epson XP-200 Series                    | 1         | 1.54%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 1.54%   |
| Seiko Epson L355 Series                      | 1         | 1.54%   |
| Seiko Epson ET-2820 Series                   | 1         | 1.54%   |
| Seiko Epson ET-2810 Series                   | 1         | 1.54%   |
| Seiko Epson ET-2710 Series                   | 1         | 1.54%   |
| Samsung SCX-483x 5x3x Series                 | 1         | 1.54%   |
| Samsung SCX-4623 Series                      | 1         | 1.54%   |
| Samsung SCX-4200 series                      | 1         | 1.54%   |
| Samsung SCX-3400 Series                      | 1         | 1.54%   |
| Samsung ML-2950 Series                       | 1         | 1.54%   |
| Samsung ML-216x Series Laser Printer         | 1         | 1.54%   |
| Samsung M2020 Series                         | 1         | 1.54%   |
| QinHeng CH340S                               | 1         | 1.54%   |
| Lexmark International MX317dn                | 1         | 1.54%   |
| Lexmark International 2400 series            | 1         | 1.54%   |
| Konica Minolta PagePro 1380MF                | 1         | 1.54%   |
| HP Smart Tank 510 series                     | 1         | 1.54%   |
| HP PSC 1100 series                           | 1         | 1.54%   |
| HP OfficeJet Pro 9010 series                 | 1         | 1.54%   |
| HP Officejet 6600                            | 1         | 1.54%   |
| HP OfficeJet 5600 (USBHUB)                   | 1         | 1.54%   |
| HP OfficeJet 4650 series                     | 1         | 1.54%   |
| HP LaserJet Professional P1102w              | 1         | 1.54%   |
| HP LaserJet 1200                             | 1         | 1.54%   |
| HP LaserJet 1000                             | 1         | 1.54%   |
| HP ENVY 4520 series                          | 1         | 1.54%   |
| HP DeskJet 2700 series                       | 1         | 1.54%   |
| HP DeskJet 2300 series                       | 1         | 1.54%   |
| HP DeskJet 1110 series                       | 1         | 1.54%   |
| Canon TR4500 series                          | 1         | 1.54%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 63.64%  |
| Seiko Epson     | 2         | 18.18%  |
| Hewlett-Packard | 2         | 18.18%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 18.18%  |
| HP ScanJet 2400c                            | 1         | 9.09%   |
| HP PSC 1200                                 | 1         | 9.09%   |
| Canon CanoScan LiDE 90                      | 1         | 9.09%   |
| Canon CanoScan LiDE 60                      | 1         | 9.09%   |
| Canon CanoScan LIDE 25                      | 1         | 9.09%   |
| Canon CanoScan LiDE 110                     | 1         | 9.09%   |
| Canon CanoScan LiDE 100                     | 1         | 9.09%   |
| Canon CanoScan D660U                        | 1         | 9.09%   |
| Canon CanoScan 8800F                        | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 339       | 20.47%  |
| Microdia                               | 154       | 9.3%    |
| Realtek Semiconductor                  | 140       | 8.45%   |
| IMC Networks                           | 126       | 7.61%   |
| Sunplus Innovation Technology          | 93        | 5.62%   |
| Acer                                   | 88        | 5.31%   |
| Apple                                  | 82        | 4.95%   |
| Cheng Uei Precision Industry (Foxlink) | 76        | 4.59%   |
| Quanta                                 | 64        | 3.86%   |
| Suyin                                  | 62        | 3.74%   |
| Logitech                               | 62        | 3.74%   |
| Syntek                                 | 42        | 2.54%   |
| Lite-On Technology                     | 29        | 1.75%   |
| Silicon Motion                         | 26        | 1.57%   |
| Alcor Micro                            | 24        | 1.45%   |
| Ricoh                                  | 17        | 1.03%   |
| Samsung Electronics                    | 16        | 0.97%   |
| Microsoft                              | 16        | 0.97%   |
| Bison Electronics                      | 16        | 0.97%   |
| Luxvisions Innotech Limited            | 15        | 0.91%   |
| USB Camera                             | 11        | 0.66%   |
| Primax Electronics                     | 11        | 0.66%   |
| Sonix Technology                       | 10        | 0.6%    |
| Generalplus Technology                 | 10        | 0.6%    |
| ARC International                      | 10        | 0.6%    |
| Lenovo                                 | 8         | 0.48%   |
| GEMBIRD                                | 7         | 0.42%   |
| ALi                                    | 7         | 0.42%   |
| Z-Star Microelectronics                | 5         | 0.3%    |
| SunplusIT                              | 5         | 0.3%    |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.3%    |
| Importek                               | 5         | 0.3%    |
| Sunplus Technology                     | 4         | 0.24%   |
| Razer USA                              | 4         | 0.24%   |
| Jieli Technology                       | 4         | 0.24%   |
| Y Media                                | 3         | 0.18%   |
| Tobii Technology AB                    | 3         | 0.18%   |
| OmniVision Technologies                | 3         | 0.18%   |
| Huawei Technologies                    | 3         | 0.18%   |
| Genesys Logic                          | 3         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 50        | 3%      |
| Microdia Integrated_Webcam_HD                    | 33        | 1.98%   |
| IMC Networks USB2.0 HD UVC WebCam                | 33        | 1.98%   |
| Realtek Integrated_Webcam_HD                     | 32        | 1.92%   |
| Apple FaceTime HD Camera (Built-in)              | 31        | 1.86%   |
| Syntek Integrated Camera                         | 26        | 1.56%   |
| Microdia Integrated Webcam                       | 26        | 1.56%   |
| Chicony HP Truevision HD                         | 24        | 1.44%   |
| Chicony HD WebCam                                | 24        | 1.44%   |
| Acer Integrated Camera                           | 24        | 1.44%   |
| IMC Networks Integrated Camera                   | 21        | 1.26%   |
| Chicony TOSHIBA Web Camera - HD                  | 20        | 1.2%    |
| IMC Networks USB2.0 VGA UVC WebCam               | 18        | 1.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 18        | 1.08%   |
| Apple Built-in iSight                            | 18        | 1.08%   |
| Acer Lenovo EasyCamera                           | 18        | 1.08%   |
| Samsung Galaxy A5 (MTP)                          | 16        | 0.96%   |
| Logitech Webcam C270                             | 16        | 0.96%   |
| Realtek USB Camera                               | 15        | 0.9%    |
| Sunplus HD WebCam                                | 14        | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 13        | 0.78%   |
| Sunplus Integrated_Webcam_HD                     | 12        | 0.72%   |
| Logitech HD Pro Webcam C920                      | 12        | 0.72%   |
| Chicony Lenovo EasyCamera                        | 12        | 0.72%   |
| Chicony HP Truevision HD camera                  | 12        | 0.72%   |
| Apple FaceTime HD Camera                         | 12        | 0.72%   |
| USB Camera USB Camera                            | 11        | 0.66%   |
| Realtek Integrated Webcam                        | 11        | 0.66%   |
| Realtek HP Truevision HD                         | 11        | 0.66%   |
| Microdia Webcam Vitade AF                        | 11        | 0.66%   |
| Microdia USB 2.0 Camera                          | 11        | 0.66%   |
| Chicony USB2.0 VGA UVC WebCam                    | 11        | 0.66%   |
| Realtek Lenovo EasyCamera                        | 10        | 0.6%    |
| Chicony VGA WebCam                               | 10        | 0.6%    |
| Chicony HP Wide Vision HD Camera                 | 10        | 0.6%    |
| Chicony HP HD Webcam                             | 10        | 0.6%    |
| Chicony EasyCamera                               | 10        | 0.6%    |
| ARC International Camera                         | 10        | 0.6%    |
| Alcor Micro USB 2.0 Camera                       | 10        | 0.6%    |
| Quanta HP Wide Vision HD Camera                  | 9         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 106       | 41.9%   |
| Synaptics                  | 35        | 13.83%  |
| Shenzhen Goodix Technology | 34        | 13.44%  |
| AuthenTec                  | 24        | 9.49%   |
| Upek                       | 21        | 8.3%    |
| Elan Microelectronics      | 15        | 5.93%   |
| LighTuning Technology      | 8         | 3.16%   |
| STMicroelectronics         | 6         | 2.37%   |
| Samsung Electronics        | 2         | 0.79%   |
| HOLTEK                     | 1         | 0.4%    |
| Focal-systems.Corp         | 1         | 0.4%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 8.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 7.91%   |
| Shenzhen Goodix  Fingerprint Device                                        | 19        | 7.51%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 5.14%   |
| Validity Sensors VFS491                                                    | 12        | 4.74%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 4.35%   |
| Elan ELAN:ARM-M4                                                           | 10        | 3.95%   |
| AuthenTec AES2810                                                          | 10        | 3.95%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 3.56%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 3.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 3.16%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 2.77%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 2.37%   |
| Synaptics UWP WBDI                                                         | 6         | 2.37%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.37%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 2.37%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.98%   |
| Synaptics WBDI                                                             | 5         | 1.98%   |
| Synaptics  WBDI                                                            | 5         | 1.98%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 1.98%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.98%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.58%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.58%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 1.58%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.58%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.58%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.19%   |
| AuthenTec AES1600                                                          | 3         | 1.19%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.79%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.79%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.79%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 0.79%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.79%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.79%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.79%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.4%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.4%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.4%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.4%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 54        | 50.94%  |
| Alcor Micro                       | 16        | 15.09%  |
| O2 Micro                          | 11        | 10.38%  |
| Lenovo                            | 6         | 5.66%   |
| Upek                              | 5         | 4.72%   |
| Realtek Semiconductor             | 3         | 2.83%   |
| Yubico.com                        | 2         | 1.89%   |
| VASCO Data Security International | 2         | 1.89%   |
| SCM Microsystems                  | 2         | 1.89%   |
| Advanced Card Systems             | 2         | 1.89%   |
| Reiner SCT Kartensysteme          | 1         | 0.94%   |
| OmniKey                           | 1         | 0.94%   |
| Fujitsu Siemens Computers         | 1         | 0.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 21        | 19.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 15.09%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 15.09%  |
| Broadcom 5880                                                                | 11        | 10.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 9.43%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 5.66%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.72%   |
| Broadcom 58200                                                               | 4         | 3.77%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 2.83%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.89%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.89%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.94%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.94%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.94%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.94%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.94%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.94%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.94%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.94%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.94%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2067      | 72.22%  |
| 1     | 650       | 22.71%  |
| 2     | 135       | 4.72%   |
| 3     | 8         | 0.28%   |
| 8     | 1         | 0.03%   |
| 4     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 247       | 26.73%  |
| Graphics card            | 200       | 21.65%  |
| Net/wireless             | 157       | 16.99%  |
| Multimedia controller    | 104       | 11.26%  |
| Chipcard                 | 97        | 10.5%   |
| Storage                  | 21        | 2.27%   |
| Bluetooth                | 19        | 2.06%   |
| Communication controller | 15        | 1.62%   |
| Sound                    | 11        | 1.19%   |
| Unassigned class         | 9         | 0.97%   |
| Camera                   | 8         | 0.87%   |
| Modem                    | 7         | 0.76%   |
| Net/ethernet             | 5         | 0.54%   |
| Storage/raid             | 4         | 0.43%   |
| Network                  | 4         | 0.43%   |
| Dvb card                 | 4         | 0.43%   |
| Card reader              | 4         | 0.43%   |
| Storage/ide              | 3         | 0.32%   |
| Storage/nvme             | 2         | 0.22%   |
| Flash memory             | 2         | 0.22%   |
| Unclassified device      | 1         | 0.11%   |

