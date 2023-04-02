Zorin - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Zorin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin/Desktop/README.md) and [notebooks](/Dist/Zorin/Notebook/README.md).

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

Total: 6959

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 1520                 | Notebook    | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| Acer          | Predator G3-605             | Desktop     | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | Notebook    | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [22d22e0742](https://linux-hardware.org/?probe=22d22e0742) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [2994622700](https://linux-hardware.org/?probe=2994622700) | Apr 01, 2023 |
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
| Dell          | 06X1TJ A01                  | Desktop     | [7e99e3d73e](https://linux-hardware.org/?probe=7e99e3d73e) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [cf226d028d](https://linux-hardware.org/?probe=cf226d028d) | Mar 27, 2023 |
| HP            | 8430 1000                   | All in one  | [c0d9a96bbf](https://linux-hardware.org/?probe=c0d9a96bbf) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | Desktop     | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| Dell          | 0GU083 A00                  | Desktop     | [e577b0129c](https://linux-hardware.org/?probe=e577b0129c) | Mar 26, 2023 |
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
| HP            | 255 G5                      | Notebook    | [99e2d83974](https://linux-hardware.org/?probe=99e2d83974) | Mar 24, 2023 |
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
| Acer          | TravelMate 2490             | Notebook    | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| Google        | Kip                         | Notebook    | [84b79bf446](https://linux-hardware.org/?probe=84b79bf446) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| Google        | Kip                         | Notebook    | [4e63ea7ac8](https://linux-hardware.org/?probe=4e63ea7ac8) | Mar 19, 2023 |
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
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | Notebook    | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| HP            | 09CCh                       | Desktop     | [e122b11e42](https://linux-hardware.org/?probe=e122b11e42) | Mar 12, 2023 |
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
| Dell          | Latitude E5470              | Notebook    | [86adaddcae](https://linux-hardware.org/?probe=86adaddcae) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Acer          | TravelMate B113             | Notebook    | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| Intel         | H61                         | Desktop     | [5650f6d211](https://linux-hardware.org/?probe=5650f6d211) | Mar 11, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e7e23885b7](https://linux-hardware.org/?probe=e7e23885b7) | Mar 11, 2023 |
| Acer          | WG43M                       | Desktop     | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | Desktop     | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| HP            | 09CCh                       | Desktop     | [9421be2c59](https://linux-hardware.org/?probe=9421be2c59) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [4b9462a4ff](https://linux-hardware.org/?probe=4b9462a4ff) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
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
| ASUSTek       | K50IJ                       | Notebook    | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
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
| ASUSTek       | K50IJ                       | Notebook    | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
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
| ASRock        | Wolfdale1333-D667           | Desktop     | [7dd4939e64](https://linux-hardware.org/?probe=7dd4939e64) | Mar 03, 2023 |
| Unknown       | Rev.00                      | Desktop     | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1237954f03](https://linux-hardware.org/?probe=1237954f03) | Mar 03, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [52b68672fc](https://linux-hardware.org/?probe=52b68672fc) | Mar 03, 2023 |
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
| Dell          | Inspiron N5010              | Notebook    | [480ff87a20](https://linux-hardware.org/?probe=480ff87a20) | Feb 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [b4be9a72dd](https://linux-hardware.org/?probe=b4be9a72dd) | Feb 28, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [66e63a311d](https://linux-hardware.org/?probe=66e63a311d) | Feb 28, 2023 |
| HP            | ENVY 17                     | Notebook    | [61d1252ef3](https://linux-hardware.org/?probe=61d1252ef3) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7478549a38](https://linux-hardware.org/?probe=7478549a38) | Feb 28, 2023 |
| Dell          | Latitude E6440              | Notebook    | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Lenovo        | ThinkPad R400 7439W2F       | Notebook    | [2673ce6bd9](https://linux-hardware.org/?probe=2673ce6bd9) | Feb 27, 2023 |
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
| ASUSTek       | P7H55-M/USB3                | Desktop     | [472721d72c](https://linux-hardware.org/?probe=472721d72c) | Feb 22, 2023 |
| DERE          | V14                         | Notebook    | [bb2d40e676](https://linux-hardware.org/?probe=bb2d40e676) | Feb 22, 2023 |
| HP            | 2129                        | Desktop     | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| HP            | ENVY 17                     | Notebook    | [ea0b2e63ef](https://linux-hardware.org/?probe=ea0b2e63ef) | Feb 21, 2023 |
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
| Toshiba       | Satellite L50D-B            | Notebook    | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
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
| HP            | ENVY 17                     | Notebook    | [de8af1b249](https://linux-hardware.org/?probe=de8af1b249) | Feb 18, 2023 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [59387e9081](https://linux-hardware.org/?probe=59387e9081) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| Medion        | E7220                       | Notebook    | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
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
| ASUSTek       | K50IJ                       | Notebook    | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
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
| Gigabyte      | 945GZM-S2                   | Desktop     | [e271dc0c66](https://linux-hardware.org/?probe=e271dc0c66) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | Notebook    | [a7aa67f64e](https://linux-hardware.org/?probe=a7aa67f64e) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | Notebook    | [eda645cefe](https://linux-hardware.org/?probe=eda645cefe) | Feb 14, 2023 |
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
| IBM           | 819046G                     | Desktop     | [a43370bbbd](https://linux-hardware.org/?probe=a43370bbbd) | Feb 11, 2023 |
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
| TWC           | Unknown                     | Notebook    | [4ea2803396](https://linux-hardware.org/?probe=4ea2803396) | Feb 06, 2023 |
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
| Unknown       | G41 Series                  | Desktop     | [69d4cb64a2](https://linux-hardware.org/?probe=69d4cb64a2) | Feb 03, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [5bfa4ad142](https://linux-hardware.org/?probe=5bfa4ad142) | Feb 02, 2023 |
| HP            | 1825                        | Desktop     | [fd942fd3ba](https://linux-hardware.org/?probe=fd942fd3ba) | Feb 02, 2023 |
| Intel         | Unknown                     | Notebook    | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| HP            | 09F8h                       | Desktop     | [19339c9512](https://linux-hardware.org/?probe=19339c9512) | Feb 02, 2023 |
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
| ASUSTek       | K50IJ                       | Notebook    | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
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
| HP            | 2ADE                        | Desktop     | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [db73b82761](https://linux-hardware.org/?probe=db73b82761) | Jan 24, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [dc93e9d9f0](https://linux-hardware.org/?probe=dc93e9d9f0) | Jan 24, 2023 |
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
| ASUSTek       | A6U                         | Notebook    | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | Notebook    | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
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
| HP            | Pavilion 17                 | Notebook    | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | Desktop     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f4232dc72a](https://linux-hardware.org/?probe=f4232dc72a) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [df8d69926f](https://linux-hardware.org/?probe=df8d69926f) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [0670d91eb0](https://linux-hardware.org/?probe=0670d91eb0) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Alienware     | 2                           | Desktop     | [97c74c0c7b](https://linux-hardware.org/?probe=97c74c0c7b) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| Sony          | VGN-SR16GN_B                | Notebook    | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| Tactus        | GeoPad 110                  | Tablet      | [810d937888](https://linux-hardware.org/?probe=810d937888) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [331b5e3efa](https://linux-hardware.org/?probe=331b5e3efa) | Jan 14, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [e5ab68f182](https://linux-hardware.org/?probe=e5ab68f182) | Jan 14, 2023 |
| Dell          | 0F0TGN A00                  | Desktop     | [38a44bb08b](https://linux-hardware.org/?probe=38a44bb08b) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | Notebook    | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| HP            | 18E7                        | Desktop     | [3acf05bf4e](https://linux-hardware.org/?probe=3acf05bf4e) | Jan 14, 2023 |
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
| Dell          | 0F0TGN A00                  | Desktop     | [dc548d070e](https://linux-hardware.org/?probe=dc548d070e) | Jan 13, 2023 |
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
| Standard      | X50-V2                      | Desktop     | [69b7593670](https://linux-hardware.org/?probe=69b7593670) | Jan 07, 2023 |
| HP            | 2B47                        | Desktop     | [8ad8cb5e8f](https://linux-hardware.org/?probe=8ad8cb5e8f) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [cc8d4f6e6d](https://linux-hardware.org/?probe=cc8d4f6e6d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [393397e25c](https://linux-hardware.org/?probe=393397e25c) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [76f452827f](https://linux-hardware.org/?probe=76f452827f) | Jan 06, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [6148bc3313](https://linux-hardware.org/?probe=6148bc3313) | Jan 06, 2023 |
| Multilaser    | PC024                       | Notebook    | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | Notebook    | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
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
| Lenovo        | ThinkPad W541 20EF0011IX    | Notebook    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | Notebook    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| HOUTER        | IPMIP-GS                    | Desktop     | [6fddf7d035](https://linux-hardware.org/?probe=6fddf7d035) | Dec 30, 2022 |
| HP            | Pavilion dv6                | Notebook    | [12a8186204](https://linux-hardware.org/?probe=12a8186204) | Dec 30, 2022 |
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
| HP            | 09CCh                       | Desktop     | [60d8cc87c7](https://linux-hardware.org/?probe=60d8cc87c7) | Dec 20, 2022 |
| Dell          | 0MGK50 A04                  | Desktop     | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [5212fb0d93](https://linux-hardware.org/?probe=5212fb0d93) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [9f456f73eb](https://linux-hardware.org/?probe=9f456f73eb) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0e5b8434fe](https://linux-hardware.org/?probe=0e5b8434fe) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| MSI           | MS-1035                     | Notebook    | [6a8a6b7de4](https://linux-hardware.org/?probe=6a8a6b7de4) | Dec 19, 2022 |
| GPD           | G1619-04                    | Notebook    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
| HP            | 8715                        | Mini pc     | [a6f7705fd4](https://linux-hardware.org/?probe=a6f7705fd4) | Dec 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [b1bd890ed0](https://linux-hardware.org/?probe=b1bd890ed0) | Dec 19, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cf1ccbf76a](https://linux-hardware.org/?probe=cf1ccbf76a) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [0d5c4254b7](https://linux-hardware.org/?probe=0d5c4254b7) | Dec 19, 2022 |
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
| Toshiba       | Satellite L500              | Notebook    | [3258bb06ef](https://linux-hardware.org/?probe=3258bb06ef) | Dec 08, 2022 |
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
| HP            | Laptop 15s-eq2xxx           | Notebook    | [686afd3c20](https://linux-hardware.org/?probe=686afd3c20) | Dec 02, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [71b49e89e9](https://linux-hardware.org/?probe=71b49e89e9) | Dec 02, 2022 |
| AZW           | U59                         | Desktop     | [6a7c9cb905](https://linux-hardware.org/?probe=6a7c9cb905) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | Notebook    | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| NZXT          | N7 Z590                     | Desktop     | [cc56e65209](https://linux-hardware.org/?probe=cc56e65209) | Dec 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Zorin 16 | 2814      | 60.84%  |
| Zorin 15 | 1615      | 34.92%  |
| Zorin 12 | 196       | 4.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Zorin | 4610      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 208       | 3.98%   |
| 5.11.0-38-generic | 179       | 3.42%   |
| 5.11.0-27-generic | 154       | 2.95%   |
| 5.15.0-46-generic | 152       | 2.91%   |
| 5.15.0-58-generic | 148       | 2.83%   |
| 5.15.0-52-generic | 145       | 2.77%   |
| 5.15.0-67-generic | 132       | 2.52%   |
| 5.13.0-30-generic | 125       | 2.39%   |
| 5.11.0-40-generic | 124       | 2.37%   |
| 5.13.0-39-generic | 120       | 2.3%    |
| 5.3.0-40-generic  | 110       | 2.1%    |
| 5.11.0-41-generic | 107       | 2.05%   |
| 5.11.0-37-generic | 107       | 2.05%   |
| 5.15.0-60-generic | 105       | 2.01%   |
| 5.11.0-43-generic | 101       | 1.93%   |
| 5.4.0-42-generic  | 99        | 1.89%   |
| 5.15.0-48-generic | 95        | 1.82%   |
| 5.11.0-34-generic | 94        | 1.8%    |
| 5.13.0-40-generic | 89        | 1.7%    |
| 5.15.0-53-generic | 79        | 1.51%   |
| 5.0.0-37-generic  | 79        | 1.51%   |
| 5.15.0-41-generic | 76        | 1.45%   |
| 5.13.0-44-generic | 76        | 1.45%   |
| 5.13.0-35-generic | 74        | 1.42%   |
| 5.3.0-46-generic  | 73        | 1.4%    |
| 5.13.0-28-generic | 73        | 1.4%    |
| 5.3.0-51-generic  | 65        | 1.24%   |
| 5.4.0-47-generic  | 60        | 1.15%   |
| 5.13.0-52-generic | 59        | 1.13%   |
| 5.13.0-27-generic | 59        | 1.13%   |
| 5.3.0-53-generic  | 54        | 1.03%   |
| 5.13.0-41-generic | 54        | 1.03%   |
| 5.4.0-58-generic  | 53        | 1.01%   |
| 5.3.0-42-generic  | 52        | 0.99%   |
| 5.4.0-48-generic  | 48        | 0.92%   |
| 5.4.0-65-generic  | 46        | 0.88%   |
| 5.4.0-45-generic  | 46        | 0.88%   |
| 5.4.0-72-generic  | 45        | 0.86%   |
| 5.13.0-51-generic | 42        | 0.8%    |
| 5.4.0-80-generic  | 41        | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 1141      | 23.69%  |
| 5.11.0  | 948       | 19.68%  |
| 5.4.0   | 938       | 19.48%  |
| 5.13.0  | 765       | 15.88%  |
| 5.3.0   | 487       | 10.11%  |
| 4.15.0  | 189       | 3.92%   |
| 5.0.0   | 153       | 3.18%   |
| 4.18.0  | 76        | 1.58%   |
| 5.8.0   | 54        | 1.12%   |
| 5.14.0  | 10        | 0.21%   |
| 4.4.0   | 6         | 0.12%   |
| 5.7.1   | 3         | 0.06%   |
| 5.7.0   | 2         | 0.04%   |
| 5.6.0   | 2         | 0.04%   |
| 5.19.12 | 2         | 0.04%   |
| 5.18.15 | 2         | 0.04%   |
| 5.17.5  | 2         | 0.04%   |
| 5.17.1  | 2         | 0.04%   |
| 5.16.0  | 2         | 0.04%   |
| 5.10.0  | 2         | 0.04%   |
| 4.13.0  | 2         | 0.04%   |
| 6.2.7   | 1         | 0.02%   |
| 6.1.7   | 1         | 0.02%   |
| 6.0.8   | 1         | 0.02%   |
| 6.0.19  | 1         | 0.02%   |
| 6.0.0   | 1         | 0.02%   |
| 5.9.12  | 1         | 0.02%   |
| 5.9.0   | 1         | 0.02%   |
| 5.8.5   | 1         | 0.02%   |
| 5.7.17  | 1         | 0.02%   |
| 5.4.180 | 1         | 0.02%   |
| 5.4.1   | 1         | 0.02%   |
| 5.19.9  | 1         | 0.02%   |
| 5.19.6  | 1         | 0.02%   |
| 5.19.2  | 1         | 0.02%   |
| 5.19.14 | 1         | 0.02%   |
| 5.19.1  | 1         | 0.02%   |
| 5.19.0  | 1         | 0.02%   |
| 5.18.6  | 1         | 0.02%   |
| 5.17.9  | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1144      | 23.75%  |
| 5.11    | 948       | 19.68%  |
| 5.4     | 940       | 19.52%  |
| 5.13    | 766       | 15.91%  |
| 5.3     | 487       | 10.11%  |
| 4.15    | 189       | 3.92%   |
| 5.0     | 153       | 3.18%   |
| 4.18    | 76        | 1.58%   |
| 5.8     | 55        | 1.14%   |
| 5.14    | 10        | 0.21%   |
| 5.19    | 8         | 0.17%   |
| 5.7     | 6         | 0.12%   |
| 4.4     | 6         | 0.12%   |
| 5.17    | 5         | 0.1%    |
| 5.16    | 5         | 0.1%    |
| 5.10    | 4         | 0.08%   |
| 6.0     | 3         | 0.06%   |
| 5.18    | 3         | 0.06%   |
| 5.9     | 2         | 0.04%   |
| 5.6     | 2         | 0.04%   |
| 4.13    | 2         | 0.04%   |
| 6.2     | 1         | 0.02%   |
| 6.1     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 4232      | 91.74%  |
| i686   | 381       | 8.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 3381      | 72.46%  |
| XFCE       | 961       | 20.6%   |
| Unknown    | 297       | 6.37%   |
| X-Cinnamon | 8         | 0.17%   |
| KDE        | 4         | 0.09%   |
| Unity      | 3         | 0.06%   |
| KDE5       | 3         | 0.06%   |
| Cinnamon   | 3         | 0.06%   |
| Budgie     | 3         | 0.06%   |
| MATE       | 1         | 0.02%   |
| LXDE       | 1         | 0.02%   |
| i3         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4396      | 94.58%  |
| Unknown | 182       | 3.92%   |
| Wayland | 69        | 1.48%   |
| Tty     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3795      | 81%     |
| GDM3    | 340       | 7.26%   |
| GDM     | 307       | 6.55%   |
| LightDM | 228       | 4.87%   |
| TDM     | 11        | 0.23%   |
| SDDM    | 3         | 0.06%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1679      | 36.14%  |
| de_DE   | 365       | 7.86%   |
| pt_BR   | 301       | 6.48%   |
| en_GB   | 284       | 6.11%   |
| Unknown | 230       | 4.95%   |
| it_IT   | 158       | 3.4%    |
| en_CA   | 131       | 2.82%   |
| fr_FR   | 129       | 2.78%   |
| en_IN   | 127       | 2.73%   |
| es_ES   | 120       | 2.58%   |
| pl_PL   | 101       | 2.17%   |
| en_AU   | 86        | 1.85%   |
| nl_NL   | 72        | 1.55%   |
| ru_RU   | 64        | 1.38%   |
| es_MX   | 62        | 1.33%   |
| pt_PT   | 52        | 1.12%   |
| es_AR   | 50        | 1.08%   |
| en_ZA   | 43        | 0.93%   |
| cs_CZ   | 43        | 0.93%   |
| hu_HU   | 31        | 0.67%   |
| tr_TR   | 30        | 0.65%   |
| sv_SE   | 30        | 0.65%   |
| C       | 29        | 0.62%   |
| es_CL   | 27        | 0.58%   |
| en_NZ   | 24        | 0.52%   |
| fr_CA   | 22        | 0.47%   |
| es_CO   | 22        | 0.47%   |
| de_AT   | 20        | 0.43%   |
| nl_BE   | 19        | 0.41%   |
| ja_JP   | 19        | 0.41%   |
| el_GR   | 17        | 0.37%   |
| de_CH   | 17        | 0.37%   |
| fr_BE   | 15        | 0.32%   |
| en_PH   | 14        | 0.3%    |
| da_DK   | 13        | 0.28%   |
| nb_NO   | 12        | 0.26%   |
| es_PE   | 12        | 0.26%   |
| fi_FI   | 10        | 0.22%   |
| bg_BG   | 10        | 0.22%   |
| ru_UA   | 9         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2524      | 54.09%  |
| EFI  | 2142      | 45.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4356      | 94.16%  |
| Overlay  | 97        | 2.1%    |
| Zfs      | 57        | 1.23%   |
| Btrfs    | 38        | 0.82%   |
| Ext2     | 33        | 0.71%   |
| Unknown  | 27        | 0.58%   |
| Ext3     | 9         | 0.19%   |
| Xfs      | 8         | 0.17%   |
| Reiserfs | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4139      | 89.01%  |
| GPT     | 379       | 8.15%   |
| MBR     | 132       | 2.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4367      | 94.14%  |
| Yes       | 272       | 5.86%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3786      | 81.49%  |
| Yes       | 860       | 18.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 802       | 17.4%   |
| ASUSTek Computer    | 662       | 14.36%  |
| Dell                | 606       | 13.15%  |
| Lenovo              | 527       | 11.43%  |
| Gigabyte Technology | 256       | 5.55%   |
| Acer                | 255       | 5.53%   |
| MSI                 | 189       | 4.1%    |
| Toshiba             | 149       | 3.23%   |
| ASRock              | 131       | 2.84%   |
| Apple               | 130       | 2.82%   |
| Intel               | 72        | 1.56%   |
| Samsung Electronics | 60        | 1.3%    |
| Unknown             | 54        | 1.17%   |
| Sony                | 48        | 1.04%   |
| Fujitsu             | 40        | 0.87%   |
| Packard Bell        | 32        | 0.69%   |
| Pegatron            | 27        | 0.59%   |
| Google              | 27        | 0.59%   |
| Positivo            | 26        | 0.56%   |
| Foxconn             | 23        | 0.5%    |
| Biostar             | 23        | 0.5%    |
| Microsoft           | 21        | 0.46%   |
| Medion              | 21        | 0.46%   |
| HUAWEI              | 19        | 0.41%   |
| Fujitsu Siemens     | 18        | 0.39%   |
| ECS                 | 18        | 0.39%   |
| Alienware           | 17        | 0.37%   |
| Gateway             | 13        | 0.28%   |
| AMI                 | 13        | 0.28%   |
| Notebook            | 11        | 0.24%   |
| eMachines           | 10        | 0.22%   |
| Panasonic           | 9         | 0.2%    |
| Chuwi               | 9         | 0.2%    |
| Multilaser          | 8         | 0.17%   |
| NEC Computers       | 7         | 0.15%   |
| IBM                 | 7         | 0.15%   |
| AZW                 | 7         | 0.15%   |
| Shuttle             | 6         | 0.13%   |
| Semp Toshiba        | 6         | 0.13%   |
| Quanta              | 6         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 85        | 1.84%   |
| ASUS All Series            | 36        | 0.78%   |
| HP Notebook                | 28        | 0.61%   |
| HP Pavilion Notebook       | 16        | 0.35%   |
| HP Pavilion dv6            | 15        | 0.33%   |
| HP 15                      | 12        | 0.26%   |
| HP Pavilion 15             | 11        | 0.24%   |
| Dell OptiPlex 7010         | 11        | 0.24%   |
| Toshiba Satellite C660     | 10        | 0.22%   |
| HP Pavilion dv7            | 10        | 0.22%   |
| Dell OptiPlex 790          | 10        | 0.22%   |
| Dell OptiPlex 780          | 10        | 0.22%   |
| Gigabyte A320M-S2H         | 9         | 0.2%    |
| Dell OptiPlex 380          | 9         | 0.2%    |
| Dell Latitude D630         | 9         | 0.2%    |
| Dell Inspiron 1545         | 9         | 0.2%    |
| Apple iMac12,2             | 9         | 0.2%    |
| MSI MS-7C02                | 8         | 0.17%   |
| MSI MS-7817                | 8         | 0.17%   |
| HP Pavilion g6             | 8         | 0.17%   |
| HP Laptop 15-bw0xx         | 8         | 0.17%   |
| Dell OptiPlex 755          | 8         | 0.17%   |
| Dell Latitude E6540        | 8         | 0.17%   |
| Dell Latitude E6400        | 8         | 0.17%   |
| Dell Inspiron 15-3567      | 8         | 0.17%   |
| ASUS M5A78L-M/USB3         | 8         | 0.17%   |
| Apple MacBookPro8,1        | 8         | 0.17%   |
| Lenovo MIIX 320-10ICR 80XF | 7         | 0.15%   |
| HP EliteBook 840 G1        | 7         | 0.15%   |
| Gigabyte 970A-DS3P         | 7         | 0.15%   |
| Dell OptiPlex 990          | 7         | 0.15%   |
| Dell Latitude E6410        | 7         | 0.15%   |
| Dell Inspiron 3521         | 7         | 0.15%   |
| Dell Inspiron 1525         | 7         | 0.15%   |
| ASUS M5A97 R2.0            | 7         | 0.15%   |
| Toshiba Satellite A100     | 6         | 0.13%   |
| HP ProDesk 600 G1 SFF      | 6         | 0.13%   |
| HP ProBook 640 G1          | 6         | 0.13%   |
| HP Pavilion g7             | 6         | 0.13%   |
| HP Pavilion dv6700         | 6         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 185       | 4.01%   |
| HP Pavilion           | 178       | 3.86%   |
| Lenovo ThinkPad       | 167       | 3.62%   |
| Acer Aspire           | 165       | 3.58%   |
| Dell Latitude         | 154       | 3.34%   |
| Lenovo IdeaPad        | 132       | 2.86%   |
| Toshiba Satellite     | 126       | 2.73%   |
| Dell OptiPlex         | 105       | 2.28%   |
| HP Compaq             | 102       | 2.21%   |
| Unknown               | 85        | 1.84%   |
| HP EliteBook          | 78        | 1.69%   |
| HP ProBook            | 66        | 1.43%   |
| HP Laptop             | 53        | 1.15%   |
| Lenovo ThinkCentre    | 50        | 1.08%   |
| ASUS ROG              | 50        | 1.08%   |
| ASUS PRIME            | 44        | 0.95%   |
| Dell Vostro           | 40        | 0.87%   |
| ASUS VivoBook         | 37        | 0.8%    |
| Dell Precision        | 36        | 0.78%   |
| ASUS All              | 36        | 0.78%   |
| HP ENVY               | 35        | 0.76%   |
| ASUS TUF              | 34        | 0.74%   |
| Dell XPS              | 31        | 0.67%   |
| Lenovo Yoga           | 29        | 0.63%   |
| HP Notebook           | 28        | 0.61%   |
| Packard Bell EasyNote | 26        | 0.56%   |
| Microsoft Surface     | 21        | 0.46%   |
| HP Stream             | 18        | 0.39%   |
| HP EliteDesk          | 18        | 0.39%   |
| Fujitsu ESPRIMO       | 18        | 0.39%   |
| Dell Studio           | 16        | 0.35%   |
| ASUS ZenBook          | 16        | 0.35%   |
| HP Presario           | 14        | 0.3%    |
| HP 15                 | 14        | 0.3%    |
| Apple iMac12          | 14        | 0.3%    |
| HP ProDesk            | 13        | 0.28%   |
| HP 255                | 13        | 0.28%   |
| Gigabyte B450         | 13        | 0.28%   |
| ASUS M5A78L-M         | 13        | 0.28%   |
| Lenovo MIIX           | 12        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 410       | 8.89%   |
| 2012    | 384       | 8.33%   |
| 2013    | 368       | 7.98%   |
| 2010    | 334       | 7.25%   |
| 2018    | 333       | 7.22%   |
| 2014    | 288       | 6.25%   |
| 2008    | 287       | 6.23%   |
| 2019    | 272       | 5.9%    |
| 2017    | 260       | 5.64%   |
| 2021    | 253       | 5.49%   |
| 2009    | 252       | 5.47%   |
| 2020    | 243       | 5.27%   |
| 2016    | 222       | 4.82%   |
| 2015    | 221       | 4.79%   |
| 2007    | 220       | 4.77%   |
| 2006    | 99        | 2.15%   |
| 2022    | 66        | 1.43%   |
| 2005    | 63        | 1.37%   |
| 2004    | 11        | 0.24%   |
| Unknown | 9         | 0.2%    |
| 2003    | 8         | 0.17%   |
| 2023    | 6         | 0.13%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2646      | 57.4%   |
| Desktop     | 1647      | 35.73%  |
| Convertible | 96        | 2.08%   |
| All in one  | 91        | 1.97%   |
| Tablet      | 61        | 1.32%   |
| Mini pc     | 59        | 1.28%   |
| Server      | 10        | 0.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4185      | 90.21%  |
| Enabled  | 454       | 9.79%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4578      | 99.31%  |
| Yes  | 32        | 0.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1185      | 25.46%  |
| 4.01-8.0        | 1091      | 23.44%  |
| 8.01-16.0       | 715       | 15.36%  |
| 16.01-24.0      | 613       | 13.17%  |
| 1.01-2.0        | 443       | 9.52%   |
| 32.01-64.0      | 266       | 5.71%   |
| 2.01-3.0        | 153       | 3.29%   |
| 0.51-1.0        | 92        | 1.98%   |
| 64.01-256.0     | 59        | 1.27%   |
| 24.01-32.0      | 37        | 0.79%   |
| More than 256.0 | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2116      | 42.46%  |
| 2.01-3.0   | 1362      | 27.33%  |
| 3.01-4.0   | 558       | 11.2%   |
| 4.01-8.0   | 436       | 8.75%   |
| 0.51-1.0   | 390       | 7.83%   |
| 8.01-16.0  | 66        | 1.32%   |
| 0.01-0.5   | 41        | 0.82%   |
| 16.01-24.0 | 9         | 0.18%   |
| 24.01-32.0 | 4         | 0.08%   |
| 32.01-64.0 | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3097      | 65.82%  |
| 2       | 1106      | 23.51%  |
| 3       | 261       | 5.55%   |
| 4       | 110       | 2.34%   |
| 5       | 51        | 1.08%   |
| 6       | 31        | 0.66%   |
| 0       | 23        | 0.49%   |
| 7       | 12        | 0.26%   |
| 8       | 9         | 0.19%   |
| 51      | 1         | 0.02%   |
| 30      | 1         | 0.02%   |
| 11      | 1         | 0.02%   |
| 10      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2330      | 50.28%  |
| Yes       | 2304      | 49.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4001      | 86.64%  |
| No        | 617       | 13.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3661      | 79.09%  |
| No        | 968       | 20.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2428      | 52.17%  |
| No        | 2226      | 47.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1056      | 22.82%  |
| Germany      | 419       | 9.05%   |
| Brazil       | 342       | 7.39%   |
| UK           | 283       | 6.11%   |
| Italy        | 176       | 3.8%    |
| Canada       | 176       | 3.8%    |
| India        | 136       | 2.94%   |
| Spain        | 135       | 2.92%   |
| France       | 129       | 2.79%   |
| Netherlands  | 125       | 2.7%    |
| Poland       | 104       | 2.25%   |
| Australia    | 95        | 2.05%   |
| Mexico       | 84        | 1.82%   |
| Argentina    | 65        | 1.4%    |
| Portugal     | 62        | 1.34%   |
| Russia       | 57        | 1.23%   |
| Sweden       | 52        | 1.12%   |
| South Africa | 52        | 1.12%   |
| Czechia      | 51        | 1.1%    |
| Belgium      | 51        | 1.1%    |
| Romania      | 43        | 0.93%   |
| Greece       | 43        | 0.93%   |
| Switzerland  | 42        | 0.91%   |
| Indonesia    | 40        | 0.86%   |
| Austria      | 38        | 0.82%   |
| Turkey       | 37        | 0.8%    |
| Hungary      | 37        | 0.8%    |
| Colombia     | 33        | 0.71%   |
| Chile        | 33        | 0.71%   |
| Norway       | 32        | 0.69%   |
| New Zealand  | 31        | 0.67%   |
| Japan        | 29        | 0.63%   |
| Serbia       | 28        | 0.61%   |
| Denmark      | 28        | 0.61%   |
| Egypt        | 25        | 0.54%   |
| Bulgaria     | 23        | 0.5%    |
| Philippines  | 20        | 0.43%   |
| Ukraine      | 19        | 0.41%   |
| Finland      | 17        | 0.37%   |
| Slovakia     | 15        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Berlin         | 39        | 0.81%   |
| Sao Paulo      | 36        | 0.75%   |
| Athens         | 32        | 0.66%   |
| Munich         | 29        | 0.6%    |
| Sydney         | 28        | 0.58%   |
| Rio de Janeiro | 24        | 0.5%    |
| Vienna         | 23        | 0.48%   |
| Madrid         | 23        | 0.48%   |
| Rome           | 22        | 0.46%   |
| Milan          | 22        | 0.46%   |
| Montreal       | 19        | 0.39%   |
| Perth          | 18        | 0.37%   |
| London         | 18        | 0.37%   |
| Toronto        | 17        | 0.35%   |
| New York       | 17        | 0.35%   |
| Johannesburg   | 17        | 0.35%   |
| Hamburg        | 17        | 0.35%   |
| Dallas         | 17        | 0.35%   |
| Bengaluru      | 17        | 0.35%   |
| Belgrade       | 17        | 0.35%   |
| Auckland       | 17        | 0.35%   |
| Istanbul       | 16        | 0.33%   |
| Buenos Aires   | 16        | 0.33%   |
| Bogotá        | 16        | 0.33%   |
| Cairo          | 15        | 0.31%   |
| Warsaw         | 14        | 0.29%   |
| Prague         | 14        | 0.29%   |
| Paris          | 14        | 0.29%   |
| Mexico City    | 14        | 0.29%   |
| Denver         | 14        | 0.29%   |
| Stockholm      | 13        | 0.27%   |
| Moscow         | 13        | 0.27%   |
| Jakarta        | 13        | 0.27%   |
| Bucharest      | 13        | 0.27%   |
| Brisbane       | 13        | 0.27%   |
| Zurich         | 12        | 0.25%   |
| Seattle        | 12        | 0.25%   |
| Melbourne      | 12        | 0.25%   |
| Cape Town      | 12        | 0.25%   |
| Budapest       | 12        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1039      | 1424   | 16.64%  |
| WDC                       | 926       | 1213   | 14.83%  |
| Samsung Electronics       | 762       | 1085   | 12.2%   |
| Toshiba                   | 492       | 613    | 7.88%   |
| Unknown                   | 361       | 511    | 5.78%   |
| SanDisk                   | 327       | 385    | 5.24%   |
| Kingston                  | 322       | 411    | 5.16%   |
| Hitachi                   | 297       | 367    | 4.76%   |
| Crucial                   | 203       | 243    | 3.25%   |
| Intel                     | 122       | 158    | 1.95%   |
| HGST                      | 112       | 138    | 1.79%   |
| SK hynix                  | 87        | 104    | 1.39%   |
| A-DATA Technology         | 74        | 84     | 1.19%   |
| China                     | 67        | 77     | 1.07%   |
| Micron Technology         | 63        | 75     | 1.01%   |
| Apple                     | 51        | 54     | 0.82%   |
| Phison                    | 46        | 58     | 0.74%   |
| Maxtor                    | 46        | 64     | 0.74%   |
| Intenso                   | 44        | 48     | 0.7%    |
| PNY                       | 43        | 54     | 0.69%   |
| Fujitsu                   | 41        | 43     | 0.66%   |
| Silicon Motion            | 34        | 42     | 0.54%   |
| SPCC                      | 31        | 35     | 0.5%    |
| Patriot                   | 31        | 43     | 0.5%    |
| OCZ                       | 27        | 31     | 0.43%   |
| JMicron Technology        | 24        | 30     | 0.38%   |
| KIOXIA                    | 23        | 25     | 0.37%   |
| Transcend                 | 22        | 43     | 0.35%   |
| LITEON                    | 22        | 27     | 0.35%   |
| Netac                     | 21        | 23     | 0.34%   |
| Micron/Crucial Technology | 21        | 22     | 0.34%   |
| GOODRAM                   | 20        | 21     | 0.32%   |
| Unknown                   | 18        | 20     | 0.29%   |
| LITEONIT                  | 17        | 20     | 0.27%   |
| Team                      | 16        | 19     | 0.26%   |
| SABRENT                   | 16        | 17     | 0.26%   |
| Hewlett-Packard           | 15        | 19     | 0.24%   |
| Lexar                     | 14        | 14     | 0.22%   |
| KingSpec                  | 12        | 14     | 0.19%   |
| Realtek Semiconductor     | 11        | 12     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 122       | 1.8%    |
| Unknown MMC Card  64GB                              | 97        | 1.43%   |
| Kingston SA400S37240G 240GB SSD                     | 78        | 1.15%   |
| Seagate ST500DM002-1BD142 500GB                     | 56        | 0.83%   |
| Toshiba MQ01ABF050 500GB                            | 50        | 0.74%   |
| Seagate ST1000LM035-1RK172 1TB                      | 49        | 0.72%   |
| Kingston SA400S37480G 480GB SSD                     | 46        | 0.68%   |
| Crucial CT240BX500SSD1 240GB                        | 45        | 0.66%   |
| Samsung SSD 860 EVO 500GB                           | 44        | 0.65%   |
| Kingston SA400S37120G 120GB SSD                     | 42        | 0.62%   |
| Toshiba MQ01ABD100 1TB                              | 41        | 0.6%    |
| Seagate ST500LT012-1DG142 500GB                     | 41        | 0.6%    |
| Unknown MMC Card  128GB                             | 40        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 39        | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB                      | 39        | 0.58%   |
| Toshiba MQ04ABF100 1TB                              | 35        | 0.52%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 34        | 0.5%    |
| Samsung SSD 850 EVO 500GB                           | 33        | 0.49%   |
| Samsung SSD 850 EVO 250GB                           | 33        | 0.49%   |
| Samsung NVMe SSD Drive 512GB                        | 33        | 0.49%   |
| Unknown SD/MMC/MS PRO 64GB                          | 31        | 0.46%   |
| Seagate ST9500325AS 500GB                           | 31        | 0.46%   |
| Seagate ST3500418AS 500GB                           | 30        | 0.44%   |
| Samsung NVMe SSD Drive 500GB                        | 30        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD                    | 30        | 0.44%   |
| Samsung NVMe SSD Drive 1TB                          | 29        | 0.43%   |
| Crucial CT500MX500SSD1 500GB                        | 29        | 0.43%   |
| Unknown MMC Card  16GB                              | 27        | 0.4%    |
| Toshiba DT01ACA100 1TB                              | 25        | 0.37%   |
| Seagate Expansion+ 2TB                              | 25        | 0.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 25        | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 24        | 0.35%   |
| Samsung SSD 860 EVO 250GB                           | 24        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 22        | 0.32%   |
| SanDisk NVMe SSD Drive 256GB                        | 22        | 0.32%   |
| Samsung SSD 840 EVO 250GB                           | 21        | 0.31%   |
| Seagate ST1000DM003-1ER162 1TB                      | 20        | 0.3%    |
| Seagate ST1000DM003-1CH162 1TB                      | 20        | 0.3%    |
| Intel NVMe SSD Drive 512GB                          | 20        | 0.3%    |
| HGST HTS541010A9E680 1TB                            | 20        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1027      | 1395   | 34.02%  |
| WDC                 | 829       | 1074   | 27.46%  |
| Toshiba             | 416       | 524    | 13.78%  |
| Hitachi             | 297       | 367    | 9.84%   |
| Samsung Electronics | 146       | 186    | 4.84%   |
| HGST                | 112       | 138    | 3.71%   |
| Maxtor              | 44        | 62     | 1.46%   |
| Fujitsu             | 41        | 43     | 1.36%   |
| Unknown             | 31        | 42     | 1.03%   |
| Apple               | 26        | 28     | 0.86%   |
| SABRENT             | 16        | 17     | 0.53%   |
| ASMT                | 7         | 7      | 0.23%   |
| USB3.0              | 4         | 5      | 0.13%   |
| IBM/Hitachi         | 4         | 5      | 0.13%   |
| Super Talent        | 3         | 4      | 0.1%    |
| Hewlett-Packard     | 3         | 6      | 0.1%    |
| T-CREATE            | 2         | 2      | 0.07%   |
| QUANTUM             | 2         | 2      | 0.07%   |
| JMicron Technology  | 2         | 2      | 0.07%   |
| Intenso             | 2         | 2      | 0.07%   |
| Pioneer             | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 2      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 396       | 547    | 19.95%  |
| Kingston            | 277       | 346    | 13.95%  |
| SanDisk             | 201       | 238    | 10.13%  |
| Crucial             | 196       | 234    | 9.87%   |
| WDC                 | 92        | 110    | 4.63%   |
| A-DATA Technology   | 68        | 78     | 3.43%   |
| China               | 64        | 74     | 3.22%   |
| Intel               | 57        | 67     | 2.87%   |
| PNY                 | 43        | 54     | 2.17%   |
| Toshiba             | 42        | 48     | 2.12%   |
| Micron Technology   | 34        | 40     | 1.71%   |
| SK hynix            | 32        | 36     | 1.61%   |
| Patriot             | 30        | 42     | 1.51%   |
| Intenso             | 30        | 33     | 1.51%   |
| SPCC                | 29        | 33     | 1.46%   |
| OCZ                 | 25        | 29     | 1.26%   |
| Transcend           | 22        | 43     | 1.11%   |
| LITEON              | 22        | 27     | 1.11%   |
| Netac               | 21        | 22     | 1.06%   |
| Apple               | 21        | 21     | 1.06%   |
| GOODRAM             | 19        | 20     | 0.96%   |
| LITEONIT            | 17        | 20     | 0.86%   |
| Team                | 16        | 19     | 0.81%   |
| JMicron Technology  | 14        | 19     | 0.71%   |
| Lexar               | 13        | 13     | 0.65%   |
| KingSpec            | 11        | 13     | 0.55%   |
| Hewlett-Packard     | 11        | 12     | 0.55%   |
| Apacer              | 11        | 12     | 0.55%   |
| Leven               | 9         | 10     | 0.45%   |
| Gigabyte Technology | 9         | 16     | 0.45%   |
| Corsair             | 8         | 12     | 0.4%    |
| Unknown             | 8         | 10     | 0.4%    |
| Plextor             | 7         | 8      | 0.35%   |
| OWC                 | 6         | 7      | 0.3%    |
| Verbatim            | 4         | 4      | 0.2%    |
| TCSUNBOW            | 4         | 4      | 0.2%    |
| Seagate             | 4         | 6      | 0.2%    |
| Mushkin             | 4         | 4      | 0.2%    |
| FORESEE             | 4         | 4      | 0.2%    |
| BHT                 | 4         | 5      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2638      | 3917   | 46.33%  |
| SSD     | 1793      | 2462   | 31.49%  |
| NVMe    | 798       | 1067   | 14.01%  |
| MMC     | 337       | 465    | 5.92%   |
| Unknown | 128       | 159    | 2.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3861      | 6207   | 73.91%  |
| NVMe | 797       | 1063   | 15.26%  |
| MMC  | 337       | 465    | 6.45%   |
| SAS  | 229       | 335    | 4.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 3029      | 4221   | 66.72%  |
| 0.51-1.0        | 1088      | 1486   | 23.96%  |
| 1.01-2.0        | 267       | 374    | 5.88%   |
| 3.01-4.0        | 60        | 141    | 1.32%   |
| 4.01-10.0       | 54        | 75     | 1.19%   |
| 2.01-3.0        | 37        | 65     | 0.81%   |
| 10.01-20.0      | 4         | 16     | 0.09%   |
| More than 100.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1559      | 32.71%  |
| 251-500        | 1164      | 24.42%  |
| 501-1000       | 625       | 13.11%  |
| 51-100         | 488       | 10.24%  |
| 21-50          | 281       | 5.9%    |
| 1001-2000      | 241       | 5.06%   |
| 1-20           | 143       | 3%      |
| More than 3000 | 140       | 2.94%   |
| 2001-3000      | 80        | 1.68%   |
| Unknown        | 45        | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2343      | 47.4%   |
| 21-50          | 1116      | 22.58%  |
| 51-100         | 518       | 10.48%  |
| 101-250        | 417       | 8.44%   |
| 251-500        | 229       | 4.63%   |
| 501-1000       | 128       | 2.59%   |
| 1001-2000      | 68        | 1.38%   |
| More than 3000 | 60        | 1.21%   |
| Unknown        | 45        | 0.91%   |
| 2001-3000      | 19        | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                   | 3         | 3      | 3.09%   |
| Seagate ST9500325AS 500GB                | 3         | 3      | 3.09%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 3.09%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 2.06%   |
| Seagate ST9500420AS 500GB                | 2         | 2      | 2.06%   |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 2.06%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 2.06%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 1.03%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 1.03%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 1.03%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 1.03%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1         | 1      | 1.03%   |
| WDC WD3200BPVT-55ZEST0 320GB             | 1         | 1      | 1.03%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 1.03%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 1.03%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 1      | 1.03%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 1.03%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.03%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 1.03%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 1.03%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 1.03%   |
| WDC WD Green 2.5 1000GB SSD              | 1         | 1      | 1.03%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 1.03%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 1.03%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 1.03%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 1.03%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 1.03%   |
| Toshiba MK5061GSY 500GB                  | 1         | 1      | 1.03%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 1.03%   |
| Toshiba MK2046GSX 200GB                  | 1         | 1      | 1.03%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 1.03%   |
| Teclast 128GB NS550-2242 SSD             | 1         | 1      | 1.03%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 1         | 1      | 1.03%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1         | 1      | 1.03%   |
| Seagate ST9320325AS 320GB                | 1         | 1      | 1.03%   |
| Seagate ST9320310AS 320GB                | 1         | 1      | 1.03%   |
| Seagate ST9250315AS 250GB                | 1         | 1      | 1.03%   |
| Seagate ST9200420ASG 200GB               | 1         | 1      | 1.03%   |
| Seagate ST9160411ASG 160GB               | 1         | 1      | 1.03%   |
| Seagate ST9160314AS 160GB                | 1         | 1      | 1.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 34     | 34.38%  |
| WDC                 | 15        | 16     | 15.63%  |
| Toshiba             | 14        | 14     | 14.58%  |
| HGST                | 7         | 7      | 7.29%   |
| Kingston            | 6         | 6      | 6.25%   |
| Hitachi             | 5         | 5      | 5.21%   |
| Samsung Electronics | 4         | 4      | 4.17%   |
| A-DATA Technology   | 2         | 2      | 2.08%   |
| Teclast             | 1         | 1      | 1.04%   |
| SK hynix            | 1         | 1      | 1.04%   |
| Silicon Motion      | 1         | 1      | 1.04%   |
| OCZ                 | 1         | 1      | 1.04%   |
| Micron Technology   | 1         | 1      | 1.04%   |
| Maxtor              | 1         | 1      | 1.04%   |
| LITEONIT            | 1         | 1      | 1.04%   |
| LITEON              | 1         | 1      | 1.04%   |
| Intel               | 1         | 1      | 1.04%   |
| Hewlett-Packard     | 1         | 1      | 1.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 34     | 44.59%  |
| WDC                 | 14        | 15     | 18.92%  |
| Toshiba             | 12        | 12     | 16.22%  |
| HGST                | 7         | 7      | 9.46%   |
| Hitachi             | 5         | 5      | 6.76%   |
| Samsung Electronics | 2         | 2      | 2.7%    |
| Maxtor              | 1         | 1      | 1.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 71        | 76     | 76.34%  |
| SSD  | 19        | 19     | 20.43%  |
| NVMe | 3         | 3      | 3.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4245      | 7386   | 90.4%   |
| Works    | 357       | 584    | 7.6%    |
| Malfunc  | 92        | 98     | 1.96%   |
| Failed   | 2         | 2      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3195      | 60.87%  |
| AMD                              | 847       | 16.14%  |
| Samsung Electronics              | 280       | 5.33%   |
| Nvidia                           | 136       | 2.59%   |
| SanDisk                          | 130       | 2.48%   |
| ASMedia Technology               | 63        | 1.2%    |
| Phison Electronics               | 59        | 1.12%   |
| JMicron Technology               | 59        | 1.12%   |
| Kingston Technology Company      | 56        | 1.07%   |
| SK hynix                         | 51        | 0.97%   |
| Marvell Technology Group         | 46        | 0.88%   |
| Silicon Motion                   | 36        | 0.69%   |
| VIA Technologies                 | 35        | 0.67%   |
| Toshiba America Info Systems     | 35        | 0.67%   |
| Silicon Integrated Systems [SiS] | 34        | 0.65%   |
| Micron Technology                | 30        | 0.57%   |
| Micron/Crucial Technology        | 28        | 0.53%   |
| KIOXIA                           | 25        | 0.48%   |
| ADATA Technology                 | 19        | 0.36%   |
| Silicon Image                    | 14        | 0.27%   |
| Realtek Semiconductor            | 12        | 0.23%   |
| Union Memory (Shenzhen)          | 7         | 0.13%   |
| Broadcom / LSI                   | 7         | 0.13%   |
| Lite-On Technology               | 6         | 0.11%   |
| Seagate Technology               | 5         | 0.1%    |
| LSI Logic / Symbios Logic        | 4         | 0.08%   |
| Apple                            | 4         | 0.08%   |
| Solid State Storage Technology   | 3         | 0.06%   |
| OCZ Technology Group             | 3         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| INNOGRIT                         | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| TenaFe                           | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 528       | 8.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 232       | 3.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 210       | 3.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 207       | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 189       | 2.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 168       | 2.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 159       | 2.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 150       | 2.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 144       | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 128       | 2.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 120       | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 119       | 1.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 118       | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 117       | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 111       | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 99        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 93        | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 89        | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 84        | 1.33%   |
| Intel SATA Controller [RAID mode]                                                       | 75        | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 74        | 1.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 69        | 1.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 65        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 64        | 1.01%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 61        | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 61        | 0.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 57        | 0.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 56        | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 55        | 0.87%   |
| Samsung NVMe SSD Controller 980                                                         | 52        | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 48        | 0.76%   |
| Nvidia MCP61 SATA Controller                                                            | 44        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 43        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 42        | 0.66%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 41        | 0.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 41        | 0.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 40        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 38        | 0.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 38        | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 37        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3280      | 59.54%  |
| IDE  | 1056      | 19.17%  |
| NVMe | 800       | 14.52%  |
| RAID | 358       | 6.5%    |
| SAS  | 9         | 0.16%   |
| SCSI | 6         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3601      | 78.11%  |
| AMD          | 1008      | 21.87%  |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 65        | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 0.89%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 36        | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 33        | 0.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 33        | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 31        | 0.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 31        | 0.67%   |
| AMD Ryzen 5 3600 6-Core Processor             | 29        | 0.63%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 28        | 0.61%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 27        | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 26        | 0.56%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 26        | 0.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 26        | 0.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 0.54%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 23        | 0.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 22        | 0.48%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 22        | 0.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 21        | 0.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 20        | 0.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 20        | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 20        | 0.43%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 20        | 0.43%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 19        | 0.41%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 19        | 0.41%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.41%   |
| Intel Pentium 4 CPU 3.00GHz                   | 18        | 0.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 18        | 0.39%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 18        | 0.39%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 18        | 0.39%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 18        | 0.39%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 18        | 0.39%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 18        | 0.39%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 17        | 0.37%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 17        | 0.37%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 17        | 0.37%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 17        | 0.37%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 17        | 0.37%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 17        | 0.37%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 17        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 929       | 20.12%  |
| Intel Core i7           | 579       | 12.54%  |
| Intel Core i3           | 421       | 9.12%   |
| Intel Core 2 Duo        | 325       | 7.04%   |
| Intel Celeron           | 305       | 6.61%   |
| Intel Atom              | 200       | 4.33%   |
| AMD Ryzen 5             | 173       | 3.75%   |
| Other                   | 150       | 3.25%   |
| Intel Pentium           | 139       | 3.01%   |
| AMD Ryzen 7             | 116       | 2.51%   |
| Intel Xeon              | 91        | 1.97%   |
| Intel Pentium Dual-Core | 84        | 1.82%   |
| AMD FX                  | 73        | 1.58%   |
| Intel Pentium Dual      | 69        | 1.49%   |
| AMD A6                  | 65        | 1.41%   |
| Intel Core 2 Quad       | 60        | 1.3%    |
| AMD A4                  | 54        | 1.17%   |
| Intel Genuine           | 46        | 1%      |
| Intel Core 2            | 45        | 0.97%   |
| AMD Ryzen 3             | 45        | 0.97%   |
| AMD A8                  | 44        | 0.95%   |
| Intel Pentium 4         | 41        | 0.89%   |
| AMD Ryzen 9             | 40        | 0.87%   |
| AMD Athlon 64 X2        | 39        | 0.84%   |
| AMD A10                 | 39        | 0.84%   |
| AMD Athlon II X2        | 31        | 0.67%   |
| Intel Pentium M         | 25        | 0.54%   |
| Intel Celeron M         | 25        | 0.54%   |
| AMD E1                  | 25        | 0.54%   |
| AMD Phenom II X4        | 22        | 0.48%   |
| AMD E                   | 21        | 0.45%   |
| AMD Athlon              | 21        | 0.45%   |
| AMD Sempron             | 17        | 0.37%   |
| AMD Turion 64 X2 Mobile | 16        | 0.35%   |
| Intel Core i9           | 15        | 0.32%   |
| Intel Pentium Silver    | 13        | 0.28%   |
| AMD Athlon II X4        | 12        | 0.26%   |
| Intel Pentium Gold      | 10        | 0.22%   |
| Intel Pentium D         | 10        | 0.22%   |
| Intel Core M            | 9         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2380      | 51.53%  |
| 4      | 1423      | 30.81%  |
| 1      | 274       | 5.93%   |
| 6      | 259       | 5.61%   |
| 8      | 182       | 3.94%   |
| 3      | 34        | 0.74%   |
| 12     | 26        | 0.56%   |
| 16     | 17        | 0.37%   |
| 10     | 16        | 0.35%   |
| 14     | 4         | 0.09%   |
| 20     | 2         | 0.04%   |
| 40     | 1         | 0.02%   |
| 28     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4590      | 99.57%  |
| 2      | 20        | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2470      | 53.57%  |
| 1      | 2141      | 46.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4462      | 96.77%  |
| 32-bit         | 146       | 3.17%   |
| Unknown        | 3         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 423       | 9.03%   |
| 0x206a7    | 386       | 8.24%   |
| 0x306a9    | 305       | 6.51%   |
| 0x1067a    | 287       | 6.12%   |
| 0x306c3    | 241       | 5.14%   |
| 0x40651    | 133       | 2.84%   |
| 0x6fd      | 132       | 2.82%   |
| 0x20655    | 121       | 2.58%   |
| 0x406e3    | 97        | 2.07%   |
| 0x806e9    | 95        | 2.03%   |
| 0x30678    | 92        | 1.96%   |
| 0x406c4    | 88        | 1.88%   |
| 0x306d4    | 87        | 1.86%   |
| 0x806ea    | 77        | 1.64%   |
| 0x806c1    | 77        | 1.64%   |
| 0x506e3    | 75        | 1.6%    |
| 0x906ea    | 69        | 1.47%   |
| 0x10676    | 66        | 1.41%   |
| 0x906e9    | 59        | 1.26%   |
| 0x806ec    | 59        | 1.26%   |
| 0x6fb      | 56        | 1.2%    |
| 0x06000852 | 53        | 1.13%   |
| 0x010000c8 | 52        | 1.11%   |
| 0x08701021 | 49        | 1.05%   |
| 0x06001119 | 49        | 1.05%   |
| 0x20652    | 48        | 1.02%   |
| 0x506c9    | 47        | 1%      |
| 0x406c3    | 44        | 0.94%   |
| 0x706a8    | 41        | 0.87%   |
| 0x08108109 | 39        | 0.83%   |
| 0x6f6      | 37        | 0.79%   |
| 0x06006705 | 37        | 0.79%   |
| 0x106ca    | 36        | 0.77%   |
| 0x0700010f | 33        | 0.7%    |
| 0x706e5    | 31        | 0.66%   |
| 0x6e8      | 31        | 0.66%   |
| 0x6d8      | 30        | 0.64%   |
| 0x07030105 | 29        | 0.62%   |
| 0x0800820d | 28        | 0.6%    |
| 0x05000119 | 27        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 446       | 9.67%   |
| Haswell          | 412       | 8.93%   |
| SandyBridge      | 411       | 8.91%   |
| Penryn           | 374       | 8.11%   |
| IvyBridge        | 328       | 7.11%   |
| Core             | 286       | 6.2%    |
| Silvermont       | 261       | 5.66%   |
| Westmere         | 189       | 4.1%    |
| Skylake          | 184       | 3.99%   |
| K10              | 117       | 2.54%   |
| Zen 2            | 115       | 2.49%   |
| Piledriver       | 110       | 2.38%   |
| Zen+             | 107       | 2.32%   |
| K8 Hammer        | 97        | 2.1%    |
| Broadwell        | 92        | 1.99%   |
| TigerLake        | 88        | 1.91%   |
| P6               | 85        | 1.84%   |
| Zen 3            | 79        | 1.71%   |
| Excavator        | 74        | 1.6%    |
| Bonnell          | 73        | 1.58%   |
| Zen              | 66        | 1.43%   |
| Goldmont plus    | 66        | 1.43%   |
| CometLake        | 64        | 1.39%   |
| NetBurst         | 59        | 1.28%   |
| Icelake          | 53        | 1.15%   |
| Goldmont         | 50        | 1.08%   |
| Puma             | 49        | 1.06%   |
| Unknown          | 47        | 1.02%   |
| Nehalem          | 44        | 0.95%   |
| Bobcat           | 42        | 0.91%   |
| Jaguar           | 40        | 0.87%   |
| K10 Llano        | 26        | 0.56%   |
| Steamroller      | 19        | 0.41%   |
| Bulldozer        | 17        | 0.37%   |
| Alderlake Hybrid | 16        | 0.35%   |
| K8 & K10 hybrid  | 15        | 0.33%   |
| Tremont          | 9         | 0.2%    |
| K6               | 3         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2723      | 52.4%   |
| Nvidia                           | 1226      | 23.59%  |
| AMD                              | 1195      | 22.99%  |
| Silicon Integrated Systems [SiS] | 27        | 0.52%   |
| VIA Technologies                 | 17        | 0.33%   |
| Matrox Electronics Systems       | 5         | 0.1%    |
| ASPEED Technology                | 2         | 0.04%   |
| Trident Microsystems             | 1         | 0.02%   |
| Silicon Motion                   | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 314       | 5.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 205       | 3.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 143       | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 136       | 2.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 127       | 2.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 125       | 2.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 116       | 2.13%   |
| Intel HD Graphics 620                                                                    | 93        | 1.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 87        | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 84        | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 77        | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 77        | 1.42%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 76        | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 74        | 1.36%   |
| Intel UHD Graphics 620                                                                   | 73        | 1.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 68        | 1.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 67        | 1.23%   |
| Intel HD Graphics 5500                                                                   | 62        | 1.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 59        | 1.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 58        | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 57        | 1.05%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 54        | 0.99%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 51        | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 49        | 0.9%    |
| Intel HD Graphics 630                                                                    | 47        | 0.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 46        | 0.85%   |
| AMD Renoir                                                                               | 45        | 0.83%   |
| Intel HD Graphics 530                                                                    | 44        | 0.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 43        | 0.79%   |
| Intel HD Graphics 500                                                                    | 42        | 0.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 0.74%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 37        | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 36        | 0.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 0.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 30        | 0.55%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 30        | 0.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 29        | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 28        | 0.51%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 28        | 0.51%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 27        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2194      | 47.42%  |
| 1 x AMD                  | 963       | 20.81%  |
| 1 x Nvidia               | 817       | 17.66%  |
| Intel + Nvidia           | 352       | 7.61%   |
| Intel + AMD              | 122       | 2.64%   |
| 2 x AMD                  | 70        | 1.51%   |
| AMD + Nvidia             | 39        | 0.84%   |
| 1 x SiS                  | 27        | 0.58%   |
| 1 x VIA                  | 17        | 0.37%   |
| 2 x Nvidia               | 9         | 0.19%   |
| Other                    | 7         | 0.15%   |
| 1 x Matrox               | 5         | 0.11%   |
| 2 x Intel                | 1         | 0.02%   |
| 1 x Trident Microsystems | 1         | 0.02%   |
| Nvidia + Silicon Motion  | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |
| 1 x ASPEED               | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3762      | 80.94%  |
| Proprietary | 666       | 14.33%  |
| Unknown     | 220       | 4.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2656      | 56.58%  |
| 0.01-0.5   | 720       | 15.34%  |
| 1.01-2.0   | 475       | 10.12%  |
| 0.51-1.0   | 405       | 8.63%   |
| 3.01-4.0   | 198       | 4.22%   |
| 7.01-8.0   | 122       | 2.6%    |
| 5.01-6.0   | 57        | 1.21%   |
| 8.01-16.0  | 32        | 0.68%   |
| 2.01-3.0   | 24        | 0.51%   |
| 16.01-24.0 | 4         | 0.09%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 635       | 13.97%  |
| AU Optronics            | 544       | 11.97%  |
| LG Display              | 414       | 9.11%   |
| Chimei Innolux          | 356       | 7.83%   |
| BOE                     | 319       | 7.02%   |
| Dell                    | 217       | 4.78%   |
| Goldstar                | 201       | 4.42%   |
| Hewlett-Packard         | 168       | 3.7%    |
| Acer                    | 134       | 2.95%   |
| Chi Mei Optoelectronics | 113       | 2.49%   |
| Apple                   | 112       | 2.46%   |
| AOC                     | 94        | 2.07%   |
| Philips                 | 91        | 2%      |
| Ancor Communications    | 81        | 1.78%   |
| BenQ                    | 72        | 1.58%   |
| LG Philips              | 70        | 1.54%   |
| Lenovo                  | 69        | 1.52%   |
| Sharp                   | 48        | 1.06%   |
| InfoVision              | 45        | 0.99%   |
| LG Electronics          | 41        | 0.9%    |
| ViewSonic               | 37        | 0.81%   |
| Unknown                 | 36        | 0.79%   |
| Sony                    | 35        | 0.77%   |
| PANDA                   | 29        | 0.64%   |
| Toshiba                 | 28        | 0.62%   |
| Vizio                   | 27        | 0.59%   |
| HannStar                | 25        | 0.55%   |
| Iiyama                  | 22        | 0.48%   |
| ASUSTek Computer        | 21        | 0.46%   |
| Unknown                 | 21        | 0.46%   |
| CPT                     | 20        | 0.44%   |
| Eizo                    | 17        | 0.37%   |
| NEC Computers           | 14        | 0.31%   |
| Fujitsu Siemens         | 14        | 0.31%   |
| Sceptre Tech            | 13        | 0.29%   |
| Panasonic               | 13        | 0.29%   |
| MSI                     | 12        | 0.26%   |
| Quanta Display          | 11        | 0.24%   |
| Gateway                 | 11        | 0.24%   |
| LGD                     | 10        | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 32        | 0.69%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 23        | 0.49%   |
| Unknown                                                                  | 21        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 20        | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 17        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 0.36%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 16        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 15        | 0.32%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 14        | 0.3%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 14        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 13        | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.26%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 11        | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 11        | 0.24%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.24%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 10        | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.21%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 10        | 0.21%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch             | 9         | 0.19%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 9         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.19%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.19%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 8         | 0.17%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 8         | 0.17%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 8         | 0.17%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 8         | 0.17%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 8         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.17%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 8         | 0.17%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 8         | 0.17%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 8         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1466      | 32.93%  |
| 1366x768 (WXGA)    | 1229      | 27.61%  |
| 1600x900 (HD+)     | 251       | 5.64%   |
| 1280x800 (WXGA)    | 217       | 4.87%   |
| 3840x2160 (4K)     | 186       | 4.18%   |
| 1280x1024 (SXGA)   | 147       | 3.3%    |
| 1440x900 (WXGA+)   | 145       | 3.26%   |
| 1680x1050 (WSXGA+) | 129       | 2.9%    |
| 2560x1440 (QHD)    | 105       | 2.36%   |
| Unknown            | 74        | 1.66%   |
| 1920x1200 (WUXGA)  | 71        | 1.59%   |
| 1360x768           | 64        | 1.44%   |
| 1024x600           | 46        | 1.03%   |
| 3440x1440          | 33        | 0.74%   |
| 3840x1080          | 27        | 0.61%   |
| 2560x1600          | 24        | 0.54%   |
| 1024x768 (XGA)     | 24        | 0.54%   |
| 2560x1080          | 22        | 0.49%   |
| 1920x540           | 22        | 0.49%   |
| 2736x1824          | 14        | 0.31%   |
| 2160x1440          | 10        | 0.22%   |
| 2256x1504          | 9         | 0.2%    |
| 5760x1080          | 8         | 0.18%   |
| 3200x1800 (QHD+)   | 8         | 0.18%   |
| 1600x1200          | 8         | 0.18%   |
| 1280x768           | 8         | 0.18%   |
| 2880x1800          | 6         | 0.13%   |
| 3840x2400          | 5         | 0.11%   |
| 3600x1080          | 5         | 0.11%   |
| 1280x720 (HD)      | 5         | 0.11%   |
| 5760x2160          | 4         | 0.09%   |
| 4480x1440          | 4         | 0.09%   |
| 3840x1600          | 4         | 0.09%   |
| 1680x945           | 4         | 0.09%   |
| 1400x1050          | 4         | 0.09%   |
| 2880x1920          | 3         | 0.07%   |
| 2048x1152          | 3         | 0.07%   |
| 1920x1280          | 3         | 0.07%   |
| 1152x864           | 3         | 0.07%   |
| 1024x576           | 3         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1247      | 27.66%  |
| 13      | 383       | 8.49%   |
| Unknown | 381       | 8.45%   |
| 14      | 326       | 7.23%   |
| 17      | 301       | 6.68%   |
| 27      | 202       | 4.48%   |
| 23      | 195       | 4.32%   |
| 21      | 194       | 4.3%    |
| 24      | 193       | 4.28%   |
| 19      | 134       | 2.97%   |
| 18      | 118       | 2.62%   |
| 11      | 110       | 2.44%   |
| 20      | 99        | 2.2%    |
| 12      | 87        | 1.93%   |
| 31      | 83        | 1.84%   |
| 22      | 80        | 1.77%   |
| 10      | 58        | 1.29%   |
| 34      | 45        | 1%      |
| 40      | 29        | 0.64%   |
| 72      | 26        | 0.58%   |
| 84      | 25        | 0.55%   |
| 54      | 21        | 0.47%   |
| 16      | 19        | 0.42%   |
| 32      | 17        | 0.38%   |
| 26      | 16        | 0.35%   |
| 25      | 10        | 0.22%   |
| 65      | 9         | 0.2%    |
| 52      | 9         | 0.2%    |
| 36      | 9         | 0.2%    |
| 42      | 7         | 0.16%   |
| 29      | 7         | 0.16%   |
| 49      | 6         | 0.13%   |
| 74      | 5         | 0.11%   |
| 47      | 5         | 0.11%   |
| 37      | 5         | 0.11%   |
| 33      | 5         | 0.11%   |
| 39      | 4         | 0.09%   |
| 8       | 4         | 0.09%   |
| 64      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1802      | 40.46%  |
| 501-600     | 561       | 12.6%   |
| 401-500     | 552       | 12.39%  |
| 201-300     | 436       | 9.79%   |
| Unknown     | 381       | 8.55%   |
| 351-400     | 351       | 7.88%   |
| 601-700     | 109       | 2.45%   |
| 701-800     | 76        | 1.71%   |
| 1001-1500   | 69        | 1.55%   |
| 1501-2000   | 59        | 1.32%   |
| 801-900     | 41        | 0.92%   |
| 901-1000    | 13        | 0.29%   |
| 101-200     | 4         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2994      | 71.23%  |
| 16/10   | 576       | 13.7%   |
| Unknown | 339       | 8.07%   |
| 5/4     | 130       | 3.09%   |
| 21/9    | 52        | 1.24%   |
| 4/3     | 47        | 1.12%   |
| 3/2     | 46        | 1.09%   |
| 32/9    | 11        | 0.26%   |
| 6/5     | 5         | 0.12%   |
| 3.73    | 2         | 0.05%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1242      | 27.72%  |
| 81-90          | 570       | 12.72%  |
| 201-250        | 519       | 11.58%  |
| Unknown        | 381       | 8.5%    |
| 151-200        | 320       | 7.14%   |
| 301-350        | 208       | 4.64%   |
| 121-130        | 173       | 3.86%   |
| 141-150        | 165       | 3.68%   |
| 351-500        | 160       | 3.57%   |
| 71-80          | 138       | 3.08%   |
| More than 1000 | 114       | 2.54%   |
| 51-60          | 112       | 2.5%    |
| 251-300        | 79        | 1.76%   |
| 61-70          | 78        | 1.74%   |
| 501-1000       | 72        | 1.61%   |
| 131-140        | 60        | 1.34%   |
| 41-50          | 56        | 1.25%   |
| 111-120        | 17        | 0.38%   |
| 91-100         | 13        | 0.29%   |
| 1-40           | 4         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1450      | 33.16%  |
| 51-100        | 1388      | 31.74%  |
| 121-160       | 825       | 18.87%  |
| Unknown       | 381       | 8.71%   |
| 161-240       | 162       | 3.7%    |
| 1-50          | 116       | 2.65%   |
| More than 240 | 51        | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3925      | 83.74%  |
| 2     | 489       | 10.43%  |
| 0     | 226       | 4.82%   |
| 3     | 43        | 0.92%   |
| 4     | 3         | 0.06%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2438      | 33.86%  |
| Intel                             | 1822      | 25.31%  |
| Qualcomm Atheros                  | 957       | 13.29%  |
| Broadcom                          | 589       | 8.18%   |
| Broadcom Limited                  | 183       | 2.54%   |
| Marvell Technology Group          | 130       | 1.81%   |
| Ralink Technology                 | 123       | 1.71%   |
| Nvidia                            | 117       | 1.63%   |
| Ralink                            | 94        | 1.31%   |
| TP-Link                           | 84        | 1.17%   |
| MediaTek                          | 51        | 0.71%   |
| Samsung Electronics               | 46        | 0.64%   |
| Xiaomi                            | 31        | 0.43%   |
| Silicon Integrated Systems [SiS]  | 31        | 0.43%   |
| ASIX Electronics                  | 30        | 0.42%   |
| VIA Technologies                  | 29        | 0.4%    |
| NetGear                           | 29        | 0.4%    |
| D-Link                            | 27        | 0.38%   |
| JMicron Technology                | 25        | 0.35%   |
| Qualcomm Atheros Communications   | 24        | 0.33%   |
| Huawei Technologies               | 22        | 0.31%   |
| D-Link System                     | 22        | 0.31%   |
| Dell                              | 20        | 0.28%   |
| Edimax Technology                 | 18        | 0.25%   |
| DisplayLink                       | 18        | 0.25%   |
| ASUSTek Computer                  | 17        | 0.24%   |
| Microsoft                         | 14        | 0.19%   |
| Hewlett-Packard                   | 14        | 0.19%   |
| Sierra Wireless                   | 13        | 0.18%   |
| OPPO Electronics                  | 12        | 0.17%   |
| Qualcomm                          | 10        | 0.14%   |
| Motorola PCS                      | 10        | 0.14%   |
| Ericsson Business Mobile Networks | 9         | 0.13%   |
| Belkin Components                 | 9         | 0.13%   |
| Linksys                           | 8         | 0.11%   |
| Aquantia                          | 8         | 0.11%   |
| AMD                               | 8         | 0.11%   |
| Attansic Technology               | 6         | 0.08%   |
| T & A Mobile Phones               | 5         | 0.07%   |
| Sitecom Europe                    | 4         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1458      | 17.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 457       | 5.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 195       | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 146       | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 136       | 1.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 127       | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 117       | 1.4%    |
| Intel Wireless 7260                                                     | 112       | 1.34%   |
| Intel Wi-Fi 6 AX200                                                     | 109       | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 91        | 1.09%   |
| Intel Wireless 8265 / 8275                                              | 87        | 1.04%   |
| Intel Wireless 7265                                                     | 87        | 1.04%   |
| Intel Ethernet Connection I217-LM                                       | 80        | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 78        | 0.93%   |
| Intel Wireless 3165                                                     | 72        | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 70        | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                           | 68        | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 67        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 64        | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 63        | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 63        | 0.75%   |
| Intel I211 Gigabit Network Connection                                   | 63        | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                       | 61        | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 61        | 0.73%   |
| Intel Wi-Fi 6 AX201                                                     | 61        | 0.73%   |
| Ralink MT7601U Wireless Adapter                                         | 59        | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 57        | 0.68%   |
| Intel Wireless 8260                                                     | 57        | 0.68%   |
| Realtek 802.11ac NIC                                                    | 52        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 49        | 0.58%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 48        | 0.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 46        | 0.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 46        | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 46        | 0.55%   |
| Intel WiFi Link 5100                                                    | 45        | 0.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 43        | 0.51%   |
| Nvidia MCP61 Ethernet                                                   | 41        | 0.49%   |
| Intel Ethernet Connection (2) I219-V                                    | 40        | 0.48%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 39        | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 37        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1338      | 33.91%  |
| Qualcomm Atheros                      | 763       | 19.34%  |
| Realtek Semiconductor                 | 745       | 18.88%  |
| Broadcom                              | 407       | 10.31%  |
| Ralink Technology                     | 123       | 3.12%   |
| Broadcom Limited                      | 116       | 2.94%   |
| Ralink                                | 94        | 2.38%   |
| TP-Link                               | 75        | 1.9%    |
| MediaTek                              | 40        | 1.01%   |
| NetGear                               | 28        | 0.71%   |
| D-Link                                | 27        | 0.68%   |
| Qualcomm Atheros Communications       | 24        | 0.61%   |
| Marvell Technology Group              | 19        | 0.48%   |
| Edimax Technology                     | 18        | 0.46%   |
| D-Link System                         | 18        | 0.46%   |
| ASUSTek Computer                      | 15        | 0.38%   |
| Sierra Wireless                       | 13        | 0.33%   |
| Microsoft                             | 11        | 0.28%   |
| Dell                                  | 9         | 0.23%   |
| Belkin Components                     | 9         | 0.23%   |
| Linksys                               | 8         | 0.2%    |
| Sitecom Europe                        | 4         | 0.1%    |
| Micro Star International              | 4         | 0.1%    |
| Gemtek                                | 4         | 0.1%    |
| ZyDAS                                 | 3         | 0.08%   |
| Hewlett-Packard                       | 3         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.08%   |
| ZyXEL Communications                  | 2         | 0.05%   |
| Xiaomi                                | 2         | 0.05%   |
| TRENDnet                              | 2         | 0.05%   |
| Senao                                 | 2         | 0.05%   |
| Philips (or NXP)                      | 2         | 0.05%   |
| IMC Networks                          | 2         | 0.05%   |
| FIBOCOM                               | 2         | 0.05%   |
| AVM                                   | 2         | 0.05%   |
| Qualcomm                              | 1         | 0.03%   |
| Qcom                                  | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Ovislink                              | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 146       | 3.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 136       | 3.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 127       | 3.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 117       | 2.94%   |
| Intel Wireless 7260                                                     | 112       | 2.81%   |
| Intel Wi-Fi 6 AX200                                                     | 109       | 2.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 91        | 2.28%   |
| Intel Wireless 8265 / 8275                                              | 87        | 2.18%   |
| Intel Wireless 7265                                                     | 87        | 2.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 78        | 1.96%   |
| Intel Wireless 3165                                                     | 72        | 1.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 70        | 1.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 68        | 1.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 67        | 1.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 63        | 1.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 61        | 1.53%   |
| Intel Wi-Fi 6 AX201                                                     | 61        | 1.53%   |
| Ralink MT7601U Wireless Adapter                                         | 59        | 1.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 57        | 1.43%   |
| Intel Wireless 8260                                                     | 57        | 1.43%   |
| Realtek 802.11ac NIC                                                    | 52        | 1.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 49        | 1.23%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 48        | 1.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 46        | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 46        | 1.15%   |
| Intel WiFi Link 5100                                                    | 45        | 1.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 43        | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 39        | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 37        | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 37        | 0.93%   |
| Intel Wireless 3160                                                     | 34        | 0.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 34        | 0.85%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 34        | 0.85%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 34        | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 33        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                          | 32        | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 29        | 0.73%   |
| Intel Centrino Wireless-N 2230                                          | 29        | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 28        | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 27        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2125      | 50.3%   |
| Intel                                  | 937       | 22.18%  |
| Qualcomm Atheros                       | 279       | 6.6%    |
| Broadcom                               | 256       | 6.06%   |
| Nvidia                                 | 117       | 2.77%   |
| Marvell Technology Group               | 111       | 2.63%   |
| Broadcom Limited                       | 73        | 1.73%   |
| Samsung Electronics                    | 45        | 1.07%   |
| ASIX Electronics                       | 30        | 0.71%   |
| Xiaomi                                 | 29        | 0.69%   |
| VIA Technologies                       | 29        | 0.69%   |
| Silicon Integrated Systems [SiS]       | 29        | 0.69%   |
| JMicron Technology                     | 25        | 0.59%   |
| Huawei Technologies                    | 18        | 0.43%   |
| DisplayLink                            | 18        | 0.43%   |
| OPPO Electronics                       | 12        | 0.28%   |
| MediaTek                               | 11        | 0.26%   |
| TP-Link                                | 9         | 0.21%   |
| Qualcomm                               | 9         | 0.21%   |
| Aquantia                               | 8         | 0.19%   |
| Motorola PCS                           | 7         | 0.17%   |
| Attansic Technology                    | 6         | 0.14%   |
| Google                                 | 4         | 0.09%   |
| D-Link System                          | 4         | 0.09%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.07%   |
| Hewlett-Packard                        | 3         | 0.07%   |
| Davicom Semiconductor                  | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.05%   |
| Microsoft                              | 2         | 0.05%   |
| HMD Global                             | 2         | 0.05%   |
| ASUSTek Computer                       | 2         | 0.05%   |
| Apple                                  | 2         | 0.05%   |
| T & A Mobile Phones                    | 1         | 0.02%   |
| Sun Microsystems                       | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Research In Motion                     | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Motorola BCS                           | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1458      | 34.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 457       | 10.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 195       | 4.56%   |
| Intel Ethernet Connection I217-LM                                 | 80        | 1.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 64        | 1.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 63        | 1.47%   |
| Intel I211 Gigabit Network Connection                             | 63        | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 61        | 1.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 46        | 1.08%   |
| Nvidia MCP61 Ethernet                                             | 41        | 0.96%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 33        | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 32        | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 31        | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 31        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 29        | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 29        | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 28        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 26        | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 24        | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 24        | 0.56%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 24        | 0.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 24        | 0.56%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 23        | 0.54%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 23        | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 23        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 22        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 21        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21        | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 21        | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 20        | 0.47%   |
| Intel 82566MM Gigabit Network Connection                          | 20        | 0.47%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 19        | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 19        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3994      | 51.4%   |
| WiFi     | 3660      | 47.1%   |
| Modem    | 103       | 1.33%   |
| Unknown  | 13        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2877      | 60.19%  |
| Ethernet | 1899      | 39.73%  |
| Modem    | 2         | 0.04%   |
| Unknown  | 2         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2640      | 57.06%  |
| 1     | 1767      | 38.19%  |
| 0     | 145       | 3.13%   |
| 3     | 68        | 1.47%   |
| 5     | 4         | 0.09%   |
| 4     | 2         | 0.04%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3624      | 77.55%  |
| Yes  | 1049      | 22.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 898       | 36.53%  |
| Realtek Semiconductor           | 277       | 11.27%  |
| Qualcomm Atheros Communications | 253       | 10.29%  |
| Broadcom                        | 175       | 7.12%   |
| Cambridge Silicon Radio         | 137       | 5.57%   |
| Apple                           | 124       | 5.04%   |
| IMC Networks                    | 109       | 4.43%   |
| Lite-On Technology              | 72        | 2.93%   |
| Dell                            | 66        | 2.69%   |
| Foxconn / Hon Hai               | 65        | 2.64%   |
| Hewlett-Packard                 | 60        | 2.44%   |
| Toshiba                         | 38        | 1.55%   |
| ASUSTek Computer                | 36        | 1.46%   |
| Ralink                          | 22        | 0.9%    |
| Marvell Semiconductor           | 15        | 0.61%   |
| Realtek                         | 14        | 0.57%   |
| Alps Electric                   | 14        | 0.57%   |
| Foxconn International           | 12        | 0.49%   |
| MediaTek                        | 10        | 0.41%   |
| Dynex                           | 9         | 0.37%   |
| TP-Link                         | 7         | 0.28%   |
| Integrated System Solution      | 7         | 0.28%   |
| Askey Computer                  | 6         | 0.24%   |
| Ralink Technology               | 5         | 0.2%    |
| Taiyo Yuden                     | 4         | 0.16%   |
| Micro Star International        | 4         | 0.16%   |
| Belkin Components               | 4         | 0.16%   |
| Chicony Electronics             | 3         | 0.12%   |
| Qcom                            | 2         | 0.08%   |
| Actions                         | 2         | 0.08%   |
| Sitecom Europe                  | 1         | 0.04%   |
| National Semiconductor          | 1         | 0.04%   |
| Mobile Action Technology        | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 423       | 17.2%   |
| Realtek Bluetooth Radio                             | 172       | 6.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 137       | 5.57%   |
| Intel AX201 Bluetooth                               | 109       | 4.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 107       | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 101       | 4.11%   |
| Intel AX200 Bluetooth                               | 94        | 3.82%   |
| Realtek  Bluetooth 4.2 Adapter                      | 76        | 3.09%   |
| Apple Bluetooth Host Controller                     | 57        | 2.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 49        | 1.99%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 43        | 1.75%   |
| IMC Networks Bluetooth Device                       | 41        | 1.67%   |
| Intel AX210 Bluetooth                               | 40        | 1.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 34        | 1.38%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 34        | 1.38%   |
| IMC Networks Bluetooth Radio                        | 32        | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                    | 31        | 1.26%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 31        | 1.26%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 28        | 1.14%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 26        | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 25        | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 1.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 24        | 0.98%   |
| Ralink RT3290 Bluetooth                             | 22        | 0.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 21        | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 20        | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 19        | 0.77%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 19        | 0.77%   |
| Dell DW375 Bluetooth Module                         | 18        | 0.73%   |
| Broadcom BCM2045B (BDC-2.1)                         | 18        | 0.73%   |
| Apple Bluetooth USB Host Controller                 | 18        | 0.73%   |
| Apple Bluetooth HCI                                 | 18        | 0.73%   |
| Foxconn / Hon Hai Bluetooth Device                  | 17        | 0.69%   |
| Lite-On Bluetooth Device                            | 15        | 0.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 15        | 0.61%   |
| Realtek Bluetooth Radio                             | 14        | 0.57%   |
| Marvell Bluetooth and Wireless LAN Composite        | 14        | 0.57%   |
| IMC Networks Wireless_Device                        | 13        | 0.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 0.53%   |
| Toshiba Bluetooth Device                            | 12        | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3354      | 56.61%  |
| AMD                                  | 1193      | 20.14%  |
| Nvidia                               | 915       | 15.44%  |
| C-Media Electronics                  | 78        | 1.32%   |
| Silicon Integrated Systems [SiS]     | 34        | 0.57%   |
| VIA Technologies                     | 32        | 0.54%   |
| Creative Labs                        | 32        | 0.54%   |
| Logitech                             | 26        | 0.44%   |
| Generalplus Technology               | 18        | 0.3%    |
| Texas Instruments                    | 17        | 0.29%   |
| JMTek                                | 16        | 0.27%   |
| Kingston Technology                  | 14        | 0.24%   |
| GN Netcom                            | 12        | 0.2%    |
| Realtek Semiconductor                | 11        | 0.19%   |
| Creative Technology                  | 10        | 0.17%   |
| ASUSTek Computer                     | 10        | 0.17%   |
| Tenx Technology                      | 9         | 0.15%   |
| Razer USA                            | 9         | 0.15%   |
| Plantronics                          | 9         | 0.15%   |
| SteelSeries ApS                      | 6         | 0.1%    |
| DCMT Technology                      | 5         | 0.08%   |
| Lenovo                               | 4         | 0.07%   |
| Focusrite-Novation                   | 4         | 0.07%   |
| Corsair                              | 4         | 0.07%   |
| Yamaha                               | 3         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.05%   |
| Samsung Electronics                  | 3         | 0.05%   |
| RODE Microphones                     | 3         | 0.05%   |
| Micro Star International             | 3         | 0.05%   |
| DSEA A/S                             | 3         | 0.05%   |
| Astro Gaming                         | 3         | 0.05%   |
| Turtle Beach                         | 2         | 0.03%   |
| Sony                                 | 2         | 0.03%   |
| SAVITECH                             | 2         | 0.03%   |
| OPPO Electronics                     | 2         | 0.03%   |
| Numark                               | 2         | 0.03%   |
| Micronas                             | 2         | 0.03%   |
| KTMicro                              | 2         | 0.03%   |
| Klipsch Audio                        | 2         | 0.03%   |
| Hewlett-Packard                      | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 377       | 5.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 342       | 4.89%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 290       | 4.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 284       | 4.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 235       | 3.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 219       | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 219       | 3.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 218       | 3.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 202       | 2.89%   |
| AMD FCH Azalia Controller                                                                         | 200       | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 164       | 2.34%   |
| Intel 8 Series HD Audio Controller                                                                | 139       | 1.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 135       | 1.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 133       | 1.9%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 108       | 1.54%   |
| AMD Kabini HDMI/DP Audio                                                                          | 105       | 1.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 98        | 1.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 97        | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 96        | 1.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 88        | 1.26%   |
| Intel Broadwell-U Audio Controller                                                                | 88        | 1.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 87        | 1.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 84        | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 82        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 82        | 1.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 82        | 1.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 71        | 1.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 66        | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 63        | 0.9%    |
| Nvidia High Definition Audio Controller                                                           | 60        | 0.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 59        | 0.84%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 55        | 0.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 55        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 52        | 0.74%   |
| AMD High Definition Audio Controller                                                              | 51        | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 50        | 0.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 48        | 0.69%   |
| Nvidia MCP61 High Definition Audio                                                                | 43        | 0.61%   |
| Intel 200 Series PCH HD Audio                                                                     | 43        | 0.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 43        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 208       | 21.55%  |
| SK hynix               | 182       | 18.86%  |
| Unknown                | 128       | 13.26%  |
| Micron Technology      | 89        | 9.22%   |
| Kingston               | 85        | 8.81%   |
| Crucial                | 41        | 4.25%   |
| Corsair                | 28        | 2.9%    |
| G.Skill                | 25        | 2.59%   |
| Unknown (ABCD)         | 21        | 2.18%   |
| Elpida                 | 20        | 2.07%   |
| Ramaxel Technology     | 19        | 1.97%   |
| Nanya Technology       | 18        | 1.87%   |
| A-DATA Technology      | 16        | 1.66%   |
| Team                   | 9         | 0.93%   |
| Smart                  | 7         | 0.73%   |
| Qimonda                | 6         | 0.62%   |
| Patriot                | 6         | 0.62%   |
| Unknown                | 4         | 0.41%   |
| Transcend              | 3         | 0.31%   |
| Avant                  | 3         | 0.31%   |
| Wilk                   | 2         | 0.21%   |
| Unifosa                | 2         | 0.21%   |
| Timetec                | 2         | 0.21%   |
| Teikon                 | 2         | 0.21%   |
| SHARETRONIC            | 2         | 0.21%   |
| High Bridge            | 2         | 0.21%   |
| ff                     | 2         | 0.21%   |
| fef5                   | 2         | 0.21%   |
| CSX                    | 2         | 0.21%   |
| 4ea5                   | 2         | 0.21%   |
| Walton Chaintech       | 1         | 0.1%    |
| Unknown (08B5)         | 1         | 0.1%    |
| Unknown (000080B30080) | 1         | 0.1%    |
| Toshiba                | 1         | 0.1%    |
| SUPER KINGSTEK         | 1         | 0.1%    |
| Strontium              | 1         | 0.1%    |
| Smart Brazil           | 1         | 0.1%    |
| Ramos Technology       | 1         | 0.1%    |
| PUSKILL                | 1         | 0.1%    |
| ProMos/Mosel Vitelic   | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 19        | 1.84%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 1.26%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.87%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.68%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 6         | 0.58%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.58%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.58%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.58%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 5         | 0.48%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.48%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.48%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.48%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.48%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 4         | 0.39%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 4         | 0.39%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.39%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 4         | 0.39%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.39%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 4         | 0.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.39%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.39%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.39%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.39%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.39%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.39%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.39%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 4         | 0.39%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 320       | 38.51%  |
| DDR4    | 277       | 33.33%  |
| DDR2    | 84        | 10.11%  |
| LPDDR4  | 44        | 5.29%   |
| SDRAM   | 36        | 4.33%   |
| Unknown | 29        | 3.49%   |
| LPDDR3  | 23        | 2.77%   |
| DDR     | 9         | 1.08%   |
| DRAM    | 6         | 0.72%   |
| DDR5    | 2         | 0.24%   |
| LPDDR5  | 1         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 512       | 62.67%  |
| DIMM         | 235       | 28.76%  |
| Row Of Chips | 59        | 7.22%   |
| Unknown      | 6         | 0.73%   |
| Chip         | 4         | 0.49%   |
| FB-DIMM      | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 292       | 31.5%   |
| 8192  | 279       | 30.1%   |
| 2048  | 187       | 20.17%  |
| 1024  | 74        | 7.98%   |
| 16384 | 66        | 7.12%   |
| 32768 | 15        | 1.62%   |
| 512   | 12        | 1.29%   |
| 256   | 2         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 203       | 22.56%  |
| 2667    | 98        | 10.89%  |
| 3200    | 89        | 9.89%   |
| 1333    | 68        | 7.56%   |
| 2400    | 60        | 6.67%   |
| 667     | 45        | 5%      |
| 1334    | 39        | 4.33%   |
| Unknown | 39        | 4.33%   |
| 2133    | 34        | 3.78%   |
| 800     | 27        | 3%      |
| 1066    | 21        | 2.33%   |
| 3600    | 17        | 1.89%   |
| 3266    | 16        | 1.78%   |
| 1867    | 15        | 1.67%   |
| 4267    | 13        | 1.44%   |
| 533     | 11        | 1.22%   |
| 4199    | 9         | 1%      |
| 975     | 9         | 1%      |
| 2048    | 8         | 0.89%   |
| 3000    | 6         | 0.67%   |
| 1866    | 6         | 0.67%   |
| 400     | 6         | 0.67%   |
| 1067    | 5         | 0.56%   |
| 2933    | 4         | 0.44%   |
| 2666    | 4         | 0.44%   |
| 1800    | 4         | 0.44%   |
| 333     | 4         | 0.44%   |
| 8400    | 3         | 0.33%   |
| 3866    | 3         | 0.33%   |
| 3733    | 3         | 0.33%   |
| 3466    | 3         | 0.33%   |
| 2800    | 3         | 0.33%   |
| 4800    | 2         | 0.22%   |
| 4266    | 2         | 0.22%   |
| 3800    | 2         | 0.22%   |
| 3666    | 2         | 0.22%   |
| 3400    | 2         | 0.22%   |
| 3333    | 2         | 0.22%   |
| 1639    | 2         | 0.22%   |
| 49926   | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 37        | 28.68%  |
| Canon                 | 29        | 22.48%  |
| Brother Industries    | 21        | 16.28%  |
| Seiko Epson           | 17        | 13.18%  |
| Samsung Electronics   | 15        | 11.63%  |
| STMicroelectronics    | 2         | 1.55%   |
| Lexmark International | 2         | 1.55%   |
| Zebra                 | 1         | 0.78%   |
| Toshiba TEC           | 1         | 0.78%   |
| Ricoh                 | 1         | 0.78%   |
| QinHeng Electronics   | 1         | 0.78%   |
| Pantum                | 1         | 0.78%   |
| Konica Minolta        | 1         | 0.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon TS3100 series                                       | 4         | 3.1%    |
| Seiko Epson L3110 Series                                  | 3         | 2.33%   |
| Canon PIXMA MG2500 Series                                 | 3         | 2.33%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.55%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 2         | 1.55%   |
| Samsung SCX-3400 Series                                   | 2         | 1.55%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.55%   |
| Samsung CLX-3300 Series                                   | 2         | 1.55%   |
| Samsung C460 Series                                       | 2         | 1.55%   |
| HP LaserJet Professional P 1102w                          | 2         | 1.55%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.55%   |
| HP ENVY 5000 series                                       | 2         | 1.55%   |
| HP ENVY 4520 series                                       | 2         | 1.55%   |
| HP DeskJet 2700 series                                    | 2         | 1.55%   |
| HP DeskJet 2130 series                                    | 2         | 1.55%   |
| HP DeskJet 1110 series                                    | 2         | 1.55%   |
| Canon PIXMA MX340                                         | 2         | 1.55%   |
| Canon MF4010 series                                       | 2         | 1.55%   |
| Canon LiDE 400                                            | 2         | 1.55%   |
| Brother HL-2140 series                                    | 2         | 1.55%   |
| Brother HL-2130 series                                    | 2         | 1.55%   |
| Zebra ZP 450 Printer                                      | 1         | 0.78%   |
| Toshiba TEC e-STD120 USB                                  | 1         | 0.78%   |
| Seiko Epson XP-7100 Series                                | 1         | 0.78%   |
| Seiko Epson XP-225 Series                                 | 1         | 0.78%   |
| Seiko Epson XP-200 Series                                 | 1         | 0.78%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.78%   |
| Seiko Epson Printer                                       | 1         | 0.78%   |
| Seiko Epson L365 Series                                   | 1         | 0.78%   |
| Seiko Epson L355 Series                                   | 1         | 0.78%   |
| Seiko Epson L220 Series                                   | 1         | 0.78%   |
| Seiko Epson L120 Series                                   | 1         | 0.78%   |
| Seiko Epson ET-2820 Series                                | 1         | 0.78%   |
| Seiko Epson ET-2810 Series                                | 1         | 0.78%   |
| Seiko Epson ET-2710 Series                                | 1         | 0.78%   |
| Samsung SCX-483x 5x3x Series                              | 1         | 0.78%   |
| Samsung SCX-4623 Series                                   | 1         | 0.78%   |
| Samsung SCX-4200 series                                   | 1         | 0.78%   |
| Samsung ML-2950 Series                                    | 1         | 0.78%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 0.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 73.33%  |
| Seiko Epson     | 2         | 13.33%  |
| Hewlett-Packard | 2         | 13.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 13.33%  |
| Canon CanoScan LIDE 25                      | 2         | 13.33%  |
| Canon CanoScan LiDE 100                     | 2         | 13.33%  |
| HP ScanJet 2400c                            | 1         | 6.67%   |
| HP PSC 1200                                 | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 6.67%   |
| Canon CanoScan LiDE 90                      | 1         | 6.67%   |
| Canon CanoScan LiDE 60                      | 1         | 6.67%   |
| Canon CanoScan LiDE 200                     | 1         | 6.67%   |
| Canon CanoScan LiDE 110                     | 1         | 6.67%   |
| Canon CanoScan D660U                        | 1         | 6.67%   |
| Canon CanoScan 8800F                        | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 581       | 22.61%  |
| Microdia                               | 238       | 9.26%   |
| Realtek Semiconductor                  | 195       | 7.59%   |
| IMC Networks                           | 179       | 6.96%   |
| Acer                                   | 141       | 5.49%   |
| Sunplus Innovation Technology          | 133       | 5.18%   |
| Suyin                                  | 123       | 4.79%   |
| Apple                                  | 118       | 4.59%   |
| Cheng Uei Precision Industry (Foxlink) | 112       | 4.36%   |
| Quanta                                 | 91        | 3.54%   |
| Logitech                               | 81        | 3.15%   |
| Syntek                                 | 60        | 2.33%   |
| Silicon Motion                         | 51        | 1.98%   |
| Lite-On Technology                     | 47        | 1.83%   |
| Alcor Micro                            | 43        | 1.67%   |
| Ricoh                                  | 32        | 1.25%   |
| Samsung Electronics                    | 26        | 1.01%   |
| Microsoft                              | 25        | 0.97%   |
| Bison Electronics                      | 23        | 0.89%   |
| Luxvisions Innotech Limited            | 17        | 0.66%   |
| Importek                               | 17        | 0.66%   |
| ALi                                    | 16        | 0.62%   |
| Z-Star Microelectronics                | 15        | 0.58%   |
| Primax Electronics                     | 14        | 0.54%   |
| GEMBIRD                                | 13        | 0.51%   |
| Generalplus Technology                 | 12        | 0.47%   |
| USB Camera                             | 11        | 0.43%   |
| Sonix Technology                       | 11        | 0.43%   |
| Lenovo                                 | 11        | 0.43%   |
| ARC International                      | 10        | 0.39%   |
| OmniVision Technologies                | 9         | 0.35%   |
| Genesys Logic                          | 7         | 0.27%   |
| Cubeternet                             | 7         | 0.27%   |
| SunplusIT                              | 5         | 0.19%   |
| Sunplus Technology                     | 5         | 0.19%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.19%   |
| Jieli Technology                       | 5         | 0.19%   |
| Razer USA                              | 4         | 0.16%   |
| Pixart Imaging                         | 4         | 0.16%   |
| Huawei Technologies                    | 4         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 68        | 2.63%   |
| Realtek Integrated_Webcam_HD                            | 44        | 1.7%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 42        | 1.62%   |
| Microdia Integrated_Webcam_HD                           | 40        | 1.55%   |
| Apple FaceTime HD Camera (Built-in)                     | 38        | 1.47%   |
| Microdia Integrated Webcam                              | 36        | 1.39%   |
| Chicony HP Truevision HD                                | 34        | 1.32%   |
| Chicony HD WebCam                                       | 32        | 1.24%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 31        | 1.2%    |
| Acer Lenovo EasyCamera                                  | 31        | 1.2%    |
| Acer Integrated Camera                                  | 29        | 1.12%   |
| Syntek Integrated Camera                                | 28        | 1.08%   |
| Chicony TOSHIBA Web Camera - HD                         | 28        | 1.08%   |
| Samsung Galaxy A5 (MTP)                                 | 26        | 1.01%   |
| Chicony USB 2.0 Camera                                  | 26        | 1.01%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 25        | 0.97%   |
| IMC Networks Integrated Camera                          | 25        | 0.97%   |
| Apple Built-in iSight                                   | 25        | 0.97%   |
| Chicony HP Truevision HD camera                         | 23        | 0.89%   |
| Logitech Webcam C270                                    | 22        | 0.85%   |
| Sunplus Integrated_Webcam_HD                            | 21        | 0.81%   |
| Chicony EasyCamera                                      | 21        | 0.81%   |
| Chicony Lenovo EasyCamera                               | 20        | 0.77%   |
| Sunplus HD WebCam                                       | 19        | 0.74%   |
| Realtek Integrated Webcam                               | 19        | 0.74%   |
| Chicony VGA WebCam                                      | 18        | 0.7%    |
| Chicony HP HD Webcam                                    | 18        | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 18        | 0.7%    |
| Realtek USB Camera                                      | 17        | 0.66%   |
| Alcor Micro USB 2.0 Camera                              | 17        | 0.66%   |
| Suyin HP Truevision HD                                  | 16        | 0.62%   |
| Microdia USB 2.0 Camera                                 | 16        | 0.62%   |
| Chicony USB2.0 VGA UVC WebCam                           | 16        | 0.62%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 15        | 0.58%   |
| Quanta HP TrueVision HD Camera                          | 15        | 0.58%   |
| Microdia Sonix USB 2.0 Camera                           | 15        | 0.58%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 15        | 0.58%   |
| Chicony HP Wide Vision HD Camera                        | 15        | 0.58%   |
| Chicony CNF9055 Toshiba Webcam                          | 15        | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 15        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 180       | 44.33%  |
| AuthenTec                  | 56        | 13.79%  |
| Synaptics                  | 43        | 10.59%  |
| Shenzhen Goodix Technology | 41        | 10.1%   |
| Upek                       | 32        | 7.88%   |
| Elan Microelectronics      | 22        | 5.42%   |
| STMicroelectronics         | 18        | 4.43%   |
| LighTuning Technology      | 10        | 2.46%   |
| Samsung Electronics        | 2         | 0.49%   |
| HOLTEK                     | 1         | 0.25%   |
| Focal-systems.Corp         | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 38        | 9.36%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 31        | 7.64%   |
| Shenzhen Goodix  Fingerprint Device                                        | 23        | 5.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 21        | 5.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 20        | 4.93%   |
| STMicroelectronics Fingerprint Reader                                      | 18        | 4.43%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 4.19%   |
| Validity Sensors VFS491                                                    | 17        | 4.19%   |
| AuthenTec AES2810                                                          | 17        | 4.19%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 4.19%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 3.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 3.69%   |
| Elan ELAN:Fingerprint                                                      | 11        | 2.71%   |
| Elan ELAN:ARM-M4                                                           | 11        | 2.71%   |
| Synaptics  WBDI                                                            | 9         | 2.22%   |
| AuthenTec AES1600                                                          | 9         | 2.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.97%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.97%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 1.72%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.48%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.48%   |
| Synaptics UWP WBDI                                                         | 6         | 1.48%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.48%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.23%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.23%   |
| Synaptics WBDI                                                             | 5         | 1.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 1.23%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.99%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 0.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 0.99%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.99%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.74%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.74%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.49%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.49%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.49%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 0.49%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.49%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 82        | 48.81%  |
| Alcor Micro                       | 28        | 16.67%  |
| O2 Micro                          | 25        | 14.88%  |
| Lenovo                            | 9         | 5.36%   |
| Upek                              | 7         | 4.17%   |
| Realtek Semiconductor             | 4         | 2.38%   |
| SCM Microsystems                  | 3         | 1.79%   |
| Yubico.com                        | 2         | 1.19%   |
| VASCO Data Security International | 2         | 1.19%   |
| Advanced Card Systems             | 2         | 1.19%   |
| Reiner SCT Kartensysteme          | 1         | 0.6%    |
| OmniKey                           | 1         | 0.6%    |
| Kobil Systems                     | 1         | 0.6%    |
| Fujitsu Siemens Computers         | 1         | 0.6%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 39        | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 15.98%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 12.43%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 20        | 11.83%  |
| Broadcom 5880                                                                | 17        | 10.06%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 5.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.14%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 2.96%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 2.37%   |
| Broadcom 58200                                                               | 4         | 2.37%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.18%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.18%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.18%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.59%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.59%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.59%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.59%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.59%   |
| Kobil Systems KOBIL Class 3 Reader                                           | 1         | 0.59%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.59%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.59%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.59%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.59%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3270      | 69.78%  |
| 1     | 1149      | 24.52%  |
| 2     | 244       | 5.21%   |
| 3     | 17        | 0.36%   |
| 4     | 4         | 0.09%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 433       | 26.23%  |
| Fingerprint reader       | 399       | 24.17%  |
| Net/wireless             | 278       | 16.84%  |
| Chipcard                 | 157       | 9.51%   |
| Multimedia controller    | 127       | 7.69%   |
| Modem                    | 45        | 2.73%   |
| Storage                  | 41        | 2.48%   |
| Communication controller | 41        | 2.48%   |
| Bluetooth                | 31        | 1.88%   |
| Sound                    | 21        | 1.27%   |
| Unassigned class         | 15        | 0.91%   |
| Camera                   | 15        | 0.91%   |
| Flash memory             | 12        | 0.73%   |
| Net/ethernet             | 8         | 0.48%   |
| Card reader              | 6         | 0.36%   |
| Storage/raid             | 5         | 0.3%    |
| Network                  | 5         | 0.3%    |
| Dvb card                 | 4         | 0.24%   |
| Storage/nvme             | 3         | 0.18%   |
| Storage/ide              | 3         | 0.18%   |
| Unclassified device      | 1         | 0.06%   |
| Storage/ata              | 1         | 0.06%   |

