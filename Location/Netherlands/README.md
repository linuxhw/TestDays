Linux in Netherlands - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Netherlands.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Netherlands/Desktop/README.md) and [notebooks](/Location/Netherlands/Notebook/README.md).

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

Total: 5435

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [5ef1391fb2](https://linux-hardware.org/?probe=5ef1391fb2) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [046d59655e](https://linux-hardware.org/?probe=046d59655e) | Apr 01, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [c1f349f579](https://linux-hardware.org/?probe=c1f349f579) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | Latitude E7450              | Notebook    | [8bf693a890](https://linux-hardware.org/?probe=8bf693a890) | Apr 01, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [ca8ae50d80](https://linux-hardware.org/?probe=ca8ae50d80) | Mar 31, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e18d9530c1](https://linux-hardware.org/?probe=e18d9530c1) | Mar 31, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [c3065ba2b6](https://linux-hardware.org/?probe=c3065ba2b6) | Mar 31, 2023 |
| Medion        | Iron238G                    | All in one  | [55cab5c7fa](https://linux-hardware.org/?probe=55cab5c7fa) | Mar 31, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [96107a824d](https://linux-hardware.org/?probe=96107a824d) | Mar 31, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [34bd6f42b1](https://linux-hardware.org/?probe=34bd6f42b1) | Mar 30, 2023 |
| HP            | 843F                        | Desktop     | [862f573134](https://linux-hardware.org/?probe=862f573134) | Mar 30, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [7edc7c9f47](https://linux-hardware.org/?probe=7edc7c9f47) | Mar 30, 2023 |
| Foxconn       | ETON                        | Desktop     | [52e92b5803](https://linux-hardware.org/?probe=52e92b5803) | Mar 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [6ade0ea04f](https://linux-hardware.org/?probe=6ade0ea04f) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [0028f21c3e](https://linux-hardware.org/?probe=0028f21c3e) | Mar 30, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| Acer          | FIH57                       | All in one  | [7a6b0e67f0](https://linux-hardware.org/?probe=7a6b0e67f0) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [61ede0b764](https://linux-hardware.org/?probe=61ede0b764) | Mar 29, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [39d6f86500](https://linux-hardware.org/?probe=39d6f86500) | Mar 29, 2023 |
| Acer          | Aspire E5-773G              | Notebook    | [3cb72ca21c](https://linux-hardware.org/?probe=3cb72ca21c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [799a14a5d5](https://linux-hardware.org/?probe=799a14a5d5) | Mar 28, 2023 |
| MSI           | H87-G41 PC Mate             | Desktop     | [0d1345af82](https://linux-hardware.org/?probe=0d1345af82) | Mar 28, 2023 |
| ZOTAC         | AMD M1                      | Desktop     | [2b2c8fd4fa](https://linux-hardware.org/?probe=2b2c8fd4fa) | Mar 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [68175ccbea](https://linux-hardware.org/?probe=68175ccbea) | Mar 27, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [af90cee242](https://linux-hardware.org/?probe=af90cee242) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [1988691e71](https://linux-hardware.org/?probe=1988691e71) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [dd081eb573](https://linux-hardware.org/?probe=dd081eb573) | Mar 27, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [05ecadea38](https://linux-hardware.org/?probe=05ecadea38) | Mar 26, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [5fff36a878](https://linux-hardware.org/?probe=5fff36a878) | Mar 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [79c876bced](https://linux-hardware.org/?probe=79c876bced) | Mar 25, 2023 |
| MSI           | 2AE0                        | Desktop     | [43a4a75176](https://linux-hardware.org/?probe=43a4a75176) | Mar 25, 2023 |
| Haier         | S15                         | Notebook    | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [c37a546614](https://linux-hardware.org/?probe=c37a546614) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [444375922e](https://linux-hardware.org/?probe=444375922e) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | Notebook    | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [8a7f87172d](https://linux-hardware.org/?probe=8a7f87172d) | Mar 24, 2023 |
| Framework     | Laptop                      | Notebook    | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [55f0bb1013](https://linux-hardware.org/?probe=55f0bb1013) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [1ee3769d23](https://linux-hardware.org/?probe=1ee3769d23) | Mar 24, 2023 |
| Acer          | FIH57                       | All in one  | [1f63978352](https://linux-hardware.org/?probe=1f63978352) | Mar 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [06d6af1db0](https://linux-hardware.org/?probe=06d6af1db0) | Mar 23, 2023 |
| Acer          | Aspire M1930                | Desktop     | [228747d646](https://linux-hardware.org/?probe=228747d646) | Mar 22, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [825332bfce](https://linux-hardware.org/?probe=825332bfce) | Mar 21, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| HP            | 1494                        | Desktop     | [e682c9975e](https://linux-hardware.org/?probe=e682c9975e) | Mar 21, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| Dell          | Latitude E6520              | Notebook    | [82f97b14f4](https://linux-hardware.org/?probe=82f97b14f4) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [b73f7b46c4](https://linux-hardware.org/?probe=b73f7b46c4) | Mar 20, 2023 |
| Dell          | Latitude E6520              | Notebook    | [7f92514d4e](https://linux-hardware.org/?probe=7f92514d4e) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Medion        | MS-7797                     | Desktop     | [180b0242e8](https://linux-hardware.org/?probe=180b0242e8) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| Lenovo        | [3633AC1] STC               | Server      | [aef7266e33](https://linux-hardware.org/?probe=aef7266e33) | Mar 20, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [53a3d14aa0](https://linux-hardware.org/?probe=53a3d14aa0) | Mar 20, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [9d7f6de46c](https://linux-hardware.org/?probe=9d7f6de46c) | Mar 19, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [149e050820](https://linux-hardware.org/?probe=149e050820) | Mar 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [92ae74e13d](https://linux-hardware.org/?probe=92ae74e13d) | Mar 19, 2023 |
| HP            | 8056                        | Desktop     | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e90a87f6f2](https://linux-hardware.org/?probe=e90a87f6f2) | Mar 18, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [5356d2a0ef](https://linux-hardware.org/?probe=5356d2a0ef) | Mar 18, 2023 |
| HP            | 198E                        | Desktop     | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | Desktop     | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [ba56245418](https://linux-hardware.org/?probe=ba56245418) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [c6ef926aa6](https://linux-hardware.org/?probe=c6ef926aa6) | Mar 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| HP            | Compaq 6730s                | Notebook    | [7e2310fcf0](https://linux-hardware.org/?probe=7e2310fcf0) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e0fa4709db](https://linux-hardware.org/?probe=e0fa4709db) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3e5167941c](https://linux-hardware.org/?probe=3e5167941c) | Mar 17, 2023 |
| Dell          | Latitude E7440              | Notebook    | [edf7e8521c](https://linux-hardware.org/?probe=edf7e8521c) | Mar 17, 2023 |
| Dell          | 072T6D A01                  | Server      | [ba5febe33b](https://linux-hardware.org/?probe=ba5febe33b) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [372deb4bed](https://linux-hardware.org/?probe=372deb4bed) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [d8e1601e65](https://linux-hardware.org/?probe=d8e1601e65) | Mar 16, 2023 |
| Acer          | Predator PO3-630            | Desktop     | [07ac5c2647](https://linux-hardware.org/?probe=07ac5c2647) | Mar 16, 2023 |
| Acer          | Aspire M3920                | Desktop     | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| HP            | 3397                        | Desktop     | [5f261fa554](https://linux-hardware.org/?probe=5f261fa554) | Mar 15, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d73bb5ec34](https://linux-hardware.org/?probe=d73bb5ec34) | Mar 15, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [a78f938382](https://linux-hardware.org/?probe=a78f938382) | Mar 15, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [1c6475f7da](https://linux-hardware.org/?probe=1c6475f7da) | Mar 15, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [fcb50f0e4f](https://linux-hardware.org/?probe=fcb50f0e4f) | Mar 14, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [fc7320db54](https://linux-hardware.org/?probe=fc7320db54) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b3e091147a](https://linux-hardware.org/?probe=b3e091147a) | Mar 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [e6d2f2a3b4](https://linux-hardware.org/?probe=e6d2f2a3b4) | Mar 14, 2023 |
| Samsung       | 930QED                      | Convertible | [a3182e0455](https://linux-hardware.org/?probe=a3182e0455) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [70e1aa9793](https://linux-hardware.org/?probe=70e1aa9793) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| Dell          | 09N44V A05                  | Server      | [d1a141052c](https://linux-hardware.org/?probe=d1a141052c) | Mar 13, 2023 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [659e2861d9](https://linux-hardware.org/?probe=659e2861d9) | Mar 13, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [9911027e53](https://linux-hardware.org/?probe=9911027e53) | Mar 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [66f70aa8f4](https://linux-hardware.org/?probe=66f70aa8f4) | Mar 12, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [eb987f6db2](https://linux-hardware.org/?probe=eb987f6db2) | Mar 12, 2023 |
| Medion        | E4251                       | Notebook    | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [7434247d21](https://linux-hardware.org/?probe=7434247d21) | Mar 12, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [53357f1807](https://linux-hardware.org/?probe=53357f1807) | Mar 11, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [66094e937a](https://linux-hardware.org/?probe=66094e937a) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | Notebook    | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [3283454c2d](https://linux-hardware.org/?probe=3283454c2d) | Mar 10, 2023 |
| Intel         | NUC11TNBi3 M11908-404       | Mini pc     | [14bbc3a006](https://linux-hardware.org/?probe=14bbc3a006) | Mar 10, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [21595cd5ed](https://linux-hardware.org/?probe=21595cd5ed) | Mar 09, 2023 |
| ASRock        | H87M Pro4                   | Desktop     | [49a012cecd](https://linux-hardware.org/?probe=49a012cecd) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [f4dd257e1d](https://linux-hardware.org/?probe=f4dd257e1d) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [c6119be13a](https://linux-hardware.org/?probe=c6119be13a) | Mar 07, 2023 |
| HP            | 3398                        | Desktop     | [024ce6b407](https://linux-hardware.org/?probe=024ce6b407) | Mar 06, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [98a2c9f264](https://linux-hardware.org/?probe=98a2c9f264) | Mar 06, 2023 |
| Google        | Rammus                      | Notebook    | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [53b112adac](https://linux-hardware.org/?probe=53b112adac) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [52169be881](https://linux-hardware.org/?probe=52169be881) | Mar 05, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [d841b24c32](https://linux-hardware.org/?probe=d841b24c32) | Mar 05, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [76243066c7](https://linux-hardware.org/?probe=76243066c7) | Mar 05, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [9667db85fc](https://linux-hardware.org/?probe=9667db85fc) | Mar 05, 2023 |
| HP            | 89B5 A                      | Desktop     | [b1f4e34d2d](https://linux-hardware.org/?probe=b1f4e34d2d) | Mar 04, 2023 |
| ASUSTek       | P5B-MX                      | Desktop     | [823575b2b0](https://linux-hardware.org/?probe=823575b2b0) | Mar 04, 2023 |
| Dell          | Studio XPS 1647             | Notebook    | [484c629656](https://linux-hardware.org/?probe=484c629656) | Mar 04, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [b5b5f89ca1](https://linux-hardware.org/?probe=b5b5f89ca1) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| HP            | 212B                        | Desktop     | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Alienware     | m15                         | Notebook    | [180a0251f5](https://linux-hardware.org/?probe=180a0251f5) | Mar 02, 2023 |
| HP            | 3398                        | Desktop     | [6479dbaa0e](https://linux-hardware.org/?probe=6479dbaa0e) | Mar 02, 2023 |
| HP            | Notebook                    | Notebook    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6b7925d129](https://linux-hardware.org/?probe=6b7925d129) | Mar 02, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [bbdc843fb2](https://linux-hardware.org/?probe=bbdc843fb2) | Mar 02, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [5cb58db69b](https://linux-hardware.org/?probe=5cb58db69b) | Mar 02, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f6b780ae7e](https://linux-hardware.org/?probe=f6b780ae7e) | Mar 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [80dca547fc](https://linux-hardware.org/?probe=80dca547fc) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [25112e4f96](https://linux-hardware.org/?probe=25112e4f96) | Mar 01, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [5bc379ea65](https://linux-hardware.org/?probe=5bc379ea65) | Mar 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [89fb184b09](https://linux-hardware.org/?probe=89fb184b09) | Mar 01, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [71b8cbeda5](https://linux-hardware.org/?probe=71b8cbeda5) | Feb 28, 2023 |
| ASUSTek       | N76VB                       | Notebook    | [0043164762](https://linux-hardware.org/?probe=0043164762) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| Sony          | VGN-FW11M                   | Notebook    | [06b355e1de](https://linux-hardware.org/?probe=06b355e1de) | Feb 28, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [6bf890e60c](https://linux-hardware.org/?probe=6bf890e60c) | Feb 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [979b4559fe](https://linux-hardware.org/?probe=979b4559fe) | Feb 27, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [323a03f1c6](https://linux-hardware.org/?probe=323a03f1c6) | Feb 27, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [c16b58c7ce](https://linux-hardware.org/?probe=c16b58c7ce) | Feb 26, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [9d8016f80e](https://linux-hardware.org/?probe=9d8016f80e) | Feb 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [8184285a7d](https://linux-hardware.org/?probe=8184285a7d) | Feb 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3aae5788cf](https://linux-hardware.org/?probe=3aae5788cf) | Feb 25, 2023 |
| HP            | Pavilion g7                 | Notebook    | [8f46d24897](https://linux-hardware.org/?probe=8f46d24897) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2978ec71b8](https://linux-hardware.org/?probe=2978ec71b8) | Feb 25, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [ca2ef50547](https://linux-hardware.org/?probe=ca2ef50547) | Feb 25, 2023 |
| Lenovo        | 851F 60072                  | Tablet      | [8466ce344b](https://linux-hardware.org/?probe=8466ce344b) | Feb 24, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [3899b2f13e](https://linux-hardware.org/?probe=3899b2f13e) | Feb 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [926fcff980](https://linux-hardware.org/?probe=926fcff980) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [f91140d700](https://linux-hardware.org/?probe=f91140d700) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [66b104fc61](https://linux-hardware.org/?probe=66b104fc61) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [7233b168b4](https://linux-hardware.org/?probe=7233b168b4) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [9398719812](https://linux-hardware.org/?probe=9398719812) | Feb 24, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [2cb9f58eae](https://linux-hardware.org/?probe=2cb9f58eae) | Feb 24, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fa08c93ecd](https://linux-hardware.org/?probe=fa08c93ecd) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a3d9851893](https://linux-hardware.org/?probe=a3d9851893) | Feb 23, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [f348e93361](https://linux-hardware.org/?probe=f348e93361) | Feb 23, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [1cca7fe830](https://linux-hardware.org/?probe=1cca7fe830) | Feb 22, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [de79cbb975](https://linux-hardware.org/?probe=de79cbb975) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [5e92cdeee7](https://linux-hardware.org/?probe=5e92cdeee7) | Feb 22, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [cd66af8994](https://linux-hardware.org/?probe=cd66af8994) | Feb 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [1ecf49cbaf](https://linux-hardware.org/?probe=1ecf49cbaf) | Feb 21, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e1c694b371](https://linux-hardware.org/?probe=e1c694b371) | Feb 20, 2023 |
| Dell          | Latitude 7300               | Notebook    | [65690f7efc](https://linux-hardware.org/?probe=65690f7efc) | Feb 20, 2023 |
| Dell          | Latitude E6320              | Notebook    | [0b5bcfefc5](https://linux-hardware.org/?probe=0b5bcfefc5) | Feb 20, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [8ca2b786db](https://linux-hardware.org/?probe=8ca2b786db) | Feb 19, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a28df01cad](https://linux-hardware.org/?probe=a28df01cad) | Feb 19, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [db95126414](https://linux-hardware.org/?probe=db95126414) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [c2e0245ec5](https://linux-hardware.org/?probe=c2e0245ec5) | Feb 19, 2023 |
| Dell          | Latitude E6320              | Notebook    | [8110ff7717](https://linux-hardware.org/?probe=8110ff7717) | Feb 19, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [0a015cdb94](https://linux-hardware.org/?probe=0a015cdb94) | Feb 18, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [5857177f10](https://linux-hardware.org/?probe=5857177f10) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [3886d9287f](https://linux-hardware.org/?probe=3886d9287f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [1b401aa3cf](https://linux-hardware.org/?probe=1b401aa3cf) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [c59694e05c](https://linux-hardware.org/?probe=c59694e05c) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [c614caec4a](https://linux-hardware.org/?probe=c614caec4a) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c273319d9d](https://linux-hardware.org/?probe=c273319d9d) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [4fe16ec4fe](https://linux-hardware.org/?probe=4fe16ec4fe) | Feb 16, 2023 |
| HP            | Notebook                    | Notebook    | [3de841fd56](https://linux-hardware.org/?probe=3de841fd56) | Feb 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [130fe12846](https://linux-hardware.org/?probe=130fe12846) | Feb 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [7ca9bf386b](https://linux-hardware.org/?probe=7ca9bf386b) | Feb 16, 2023 |
| Google        | Helios                      | Notebook    | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| HP            | 3031h                       | Desktop     | [2b0cc2bd6e](https://linux-hardware.org/?probe=2b0cc2bd6e) | Feb 16, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [940563622b](https://linux-hardware.org/?probe=940563622b) | Feb 16, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [38c3a4311b](https://linux-hardware.org/?probe=38c3a4311b) | Feb 16, 2023 |
| HP            | 870C                        | Desktop     | [76ae5c62cf](https://linux-hardware.org/?probe=76ae5c62cf) | Feb 15, 2023 |
| Medion        | MS-7616                     | Desktop     | [0655a4e58c](https://linux-hardware.org/?probe=0655a4e58c) | Feb 15, 2023 |
| Dell          | Latitude 3320               | Notebook    | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [3039ccd4b0](https://linux-hardware.org/?probe=3039ccd4b0) | Feb 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [d2754bf08f](https://linux-hardware.org/?probe=d2754bf08f) | Feb 14, 2023 |
| HP            | 3648h                       | Desktop     | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [0d16c9013f](https://linux-hardware.org/?probe=0d16c9013f) | Feb 14, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [dcfa5b1fc5](https://linux-hardware.org/?probe=dcfa5b1fc5) | Feb 13, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [3a4a4dedc3](https://linux-hardware.org/?probe=3a4a4dedc3) | Feb 13, 2023 |
| Dell          | Latitude E5570              | Notebook    | [16e090c63c](https://linux-hardware.org/?probe=16e090c63c) | Feb 13, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [7c1423b767](https://linux-hardware.org/?probe=7c1423b767) | Feb 13, 2023 |
| Acer          | Aspire M1930                | Desktop     | [3b78f6fb4e](https://linux-hardware.org/?probe=3b78f6fb4e) | Feb 13, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [ea169af948](https://linux-hardware.org/?probe=ea169af948) | Feb 13, 2023 |
| HP            | 843F                        | Desktop     | [3047a0ff5b](https://linux-hardware.org/?probe=3047a0ff5b) | Feb 13, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [672b71db3e](https://linux-hardware.org/?probe=672b71db3e) | Feb 12, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [86026e4f54](https://linux-hardware.org/?probe=86026e4f54) | Feb 12, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [480da10129](https://linux-hardware.org/?probe=480da10129) | Feb 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [5629f3ed8c](https://linux-hardware.org/?probe=5629f3ed8c) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| HP            | Compaq 6820s                | Notebook    | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [e1dc99210d](https://linux-hardware.org/?probe=e1dc99210d) | Feb 11, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [95875d4afc](https://linux-hardware.org/?probe=95875d4afc) | Feb 11, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [f5a8290d38](https://linux-hardware.org/?probe=f5a8290d38) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4340c10db](https://linux-hardware.org/?probe=e4340c10db) | Feb 10, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [845d2e4d52](https://linux-hardware.org/?probe=845d2e4d52) | Feb 10, 2023 |
| Dell          | Latitude 3120               | Convertible | [3bf2bfe867](https://linux-hardware.org/?probe=3bf2bfe867) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| Dell          | Precision 3571              | Notebook    | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [353bd3a5b2](https://linux-hardware.org/?probe=353bd3a5b2) | Feb 09, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [f3eb8a2592](https://linux-hardware.org/?probe=f3eb8a2592) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [eeafe897ae](https://linux-hardware.org/?probe=eeafe897ae) | Feb 09, 2023 |
| Medion        | MS-7797                     | Desktop     | [3421cd9be4](https://linux-hardware.org/?probe=3421cd9be4) | Feb 09, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [0779ef912a](https://linux-hardware.org/?probe=0779ef912a) | Feb 08, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [7091e6ba95](https://linux-hardware.org/?probe=7091e6ba95) | Feb 08, 2023 |
| Dell          | Latitude E7450              | Notebook    | [2513ec83c8](https://linux-hardware.org/?probe=2513ec83c8) | Feb 08, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [bb851866ac](https://linux-hardware.org/?probe=bb851866ac) | Feb 08, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [e92a6b0131](https://linux-hardware.org/?probe=e92a6b0131) | Feb 08, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [20d7058e4f](https://linux-hardware.org/?probe=20d7058e4f) | Feb 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [b376c55e80](https://linux-hardware.org/?probe=b376c55e80) | Feb 07, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [1e6a345b00](https://linux-hardware.org/?probe=1e6a345b00) | Feb 07, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [cdc1678cae](https://linux-hardware.org/?probe=cdc1678cae) | Feb 07, 2023 |
| Dell          | Latitude E6320              | Notebook    | [6d1fe4f041](https://linux-hardware.org/?probe=6d1fe4f041) | Feb 06, 2023 |
| Lenovo        | ThinkPad T510 4349AF5       | Notebook    | [5d737e59ae](https://linux-hardware.org/?probe=5d737e59ae) | Feb 06, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [2e581dc622](https://linux-hardware.org/?probe=2e581dc622) | Feb 06, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [3b4320a91a](https://linux-hardware.org/?probe=3b4320a91a) | Feb 06, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [33639358ab](https://linux-hardware.org/?probe=33639358ab) | Feb 06, 2023 |
| Standard      | Unknown                     | Notebook    | [c983c471de](https://linux-hardware.org/?probe=c983c471de) | Feb 05, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [b6333de3ab](https://linux-hardware.org/?probe=b6333de3ab) | Feb 05, 2023 |
| MSI           | MS-7376                     | Desktop     | [5f62748624](https://linux-hardware.org/?probe=5f62748624) | Feb 04, 2023 |
| MSI           | MS-7376                     | Desktop     | [33fa767f72](https://linux-hardware.org/?probe=33fa767f72) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [9f5df7e4e0](https://linux-hardware.org/?probe=9f5df7e4e0) | Feb 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [04c5cc4aec](https://linux-hardware.org/?probe=04c5cc4aec) | Feb 04, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [82a573d8cd](https://linux-hardware.org/?probe=82a573d8cd) | Feb 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [8dee1d9415](https://linux-hardware.org/?probe=8dee1d9415) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [1e38d08821](https://linux-hardware.org/?probe=1e38d08821) | Feb 03, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [b9e4e36496](https://linux-hardware.org/?probe=b9e4e36496) | Feb 03, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [ac1f8787af](https://linux-hardware.org/?probe=ac1f8787af) | Feb 03, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a899b18189](https://linux-hardware.org/?probe=a899b18189) | Feb 02, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [2a25e1c4d6](https://linux-hardware.org/?probe=2a25e1c4d6) | Feb 02, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [ecf260f299](https://linux-hardware.org/?probe=ecf260f299) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | Desktop     | [e68a009e8f](https://linux-hardware.org/?probe=e68a009e8f) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [66b96d9a0f](https://linux-hardware.org/?probe=66b96d9a0f) | Jan 31, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [798466ab86](https://linux-hardware.org/?probe=798466ab86) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [4dbe55873b](https://linux-hardware.org/?probe=4dbe55873b) | Jan 31, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [30a093116e](https://linux-hardware.org/?probe=30a093116e) | Jan 30, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [a434328de5](https://linux-hardware.org/?probe=a434328de5) | Jan 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [2469884587](https://linux-hardware.org/?probe=2469884587) | Jan 30, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [bdb3c91476](https://linux-hardware.org/?probe=bdb3c91476) | Jan 29, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [debdb8208f](https://linux-hardware.org/?probe=debdb8208f) | Jan 29, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [d17dc00a8a](https://linux-hardware.org/?probe=d17dc00a8a) | Jan 29, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [8bee986aca](https://linux-hardware.org/?probe=8bee986aca) | Jan 28, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [fb0dcf8d7e](https://linux-hardware.org/?probe=fb0dcf8d7e) | Jan 28, 2023 |
| HP            | 17E2                        | Mini pc     | [41fdb27963](https://linux-hardware.org/?probe=41fdb27963) | Jan 28, 2023 |
| HP            | 0A08h                       | Desktop     | [f9b0168de1](https://linux-hardware.org/?probe=f9b0168de1) | Jan 28, 2023 |
| Dell          | 0599V5 A12                  | Server      | [14f503ae4a](https://linux-hardware.org/?probe=14f503ae4a) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [a50b0e3645](https://linux-hardware.org/?probe=a50b0e3645) | Jan 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [97d1ab1b7d](https://linux-hardware.org/?probe=97d1ab1b7d) | Jan 28, 2023 |
| Acer          | Aspire E5-774               | Notebook    | [86e3285b31](https://linux-hardware.org/?probe=86e3285b31) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [b9793eca79](https://linux-hardware.org/?probe=b9793eca79) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [ee769c62bf](https://linux-hardware.org/?probe=ee769c62bf) | Jan 27, 2023 |
| HP            | 8055                        | Desktop     | [81fa44d8fa](https://linux-hardware.org/?probe=81fa44d8fa) | Jan 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1b1079b0bf](https://linux-hardware.org/?probe=1b1079b0bf) | Jan 27, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [c0468fe8fd](https://linux-hardware.org/?probe=c0468fe8fd) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [ab38ecfb97](https://linux-hardware.org/?probe=ab38ecfb97) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0P    | Notebook    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [cb8c4c9711](https://linux-hardware.org/?probe=cb8c4c9711) | Jan 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [076783b777](https://linux-hardware.org/?probe=076783b777) | Jan 26, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [b5cb34ea4d](https://linux-hardware.org/?probe=b5cb34ea4d) | Jan 26, 2023 |
| Toshiba       | Satellite C870-12F          | Notebook    | [fc9a6d3a7e](https://linux-hardware.org/?probe=fc9a6d3a7e) | Jan 25, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [4efa4db490](https://linux-hardware.org/?probe=4efa4db490) | Jan 25, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9b7c80b059](https://linux-hardware.org/?probe=9b7c80b059) | Jan 25, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | Notebook    | [dad68fd07f](https://linux-hardware.org/?probe=dad68fd07f) | Jan 24, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | Notebook    | [b61b0f981e](https://linux-hardware.org/?probe=b61b0f981e) | Jan 24, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [47ff2a2e42](https://linux-hardware.org/?probe=47ff2a2e42) | Jan 24, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [a3672f1d47](https://linux-hardware.org/?probe=a3672f1d47) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [3194fb8316](https://linux-hardware.org/?probe=3194fb8316) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [8e124bc501](https://linux-hardware.org/?probe=8e124bc501) | Jan 24, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [75362fb07d](https://linux-hardware.org/?probe=75362fb07d) | Jan 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [7630683952](https://linux-hardware.org/?probe=7630683952) | Jan 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [8c427938e2](https://linux-hardware.org/?probe=8c427938e2) | Jan 24, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [5ca72b0d88](https://linux-hardware.org/?probe=5ca72b0d88) | Jan 24, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [5e4253b22d](https://linux-hardware.org/?probe=5e4253b22d) | Jan 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [b4b7ebe3f9](https://linux-hardware.org/?probe=b4b7ebe3f9) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [54313c1c76](https://linux-hardware.org/?probe=54313c1c76) | Jan 23, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [459ab8ae3d](https://linux-hardware.org/?probe=459ab8ae3d) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| Medion        | E4251                       | Notebook    | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [0a3f1269f7](https://linux-hardware.org/?probe=0a3f1269f7) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [b2792832c2](https://linux-hardware.org/?probe=b2792832c2) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [9beaa4240c](https://linux-hardware.org/?probe=9beaa4240c) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [ffc0fa7fb5](https://linux-hardware.org/?probe=ffc0fa7fb5) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [7933a58a32](https://linux-hardware.org/?probe=7933a58a32) | Jan 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [733770beaf](https://linux-hardware.org/?probe=733770beaf) | Jan 22, 2023 |
| Dell          | Latitude 5520               | Notebook    | [a3541758f7](https://linux-hardware.org/?probe=a3541758f7) | Jan 22, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [40cc1bf7d9](https://linux-hardware.org/?probe=40cc1bf7d9) | Jan 21, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [325f9e8310](https://linux-hardware.org/?probe=325f9e8310) | Jan 21, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [eeea0542b8](https://linux-hardware.org/?probe=eeea0542b8) | Jan 21, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [5d606f2c60](https://linux-hardware.org/?probe=5d606f2c60) | Jan 21, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [acf0fd5893](https://linux-hardware.org/?probe=acf0fd5893) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | Notebook    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [4a2292e809](https://linux-hardware.org/?probe=4a2292e809) | Jan 19, 2023 |
| Acer          | Predator G3-710             | Desktop     | [c7f97640a5](https://linux-hardware.org/?probe=c7f97640a5) | Jan 19, 2023 |
| ASUSTek       | P6T                         | Desktop     | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [1a61029965](https://linux-hardware.org/?probe=1a61029965) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| HP            | Notebook                    | Notebook    | [63f0c0b90c](https://linux-hardware.org/?probe=63f0c0b90c) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [da0d1f442a](https://linux-hardware.org/?probe=da0d1f442a) | Jan 19, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [3591fb1d6c](https://linux-hardware.org/?probe=3591fb1d6c) | Jan 19, 2023 |
| Pegatron      | EVANS                       | Desktop     | [798a545fa8](https://linux-hardware.org/?probe=798a545fa8) | Jan 19, 2023 |
| Pegatron      | EVANS                       | Desktop     | [411db3ea66](https://linux-hardware.org/?probe=411db3ea66) | Jan 19, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [68d2fcbdcf](https://linux-hardware.org/?probe=68d2fcbdcf) | Jan 18, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [f0ce1e8b3f](https://linux-hardware.org/?probe=f0ce1e8b3f) | Jan 18, 2023 |
| Dell          | Latitude E6540              | Notebook    | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [62d01a5b26](https://linux-hardware.org/?probe=62d01a5b26) | Jan 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [09e31ee1c8](https://linux-hardware.org/?probe=09e31ee1c8) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [d50f9357b4](https://linux-hardware.org/?probe=d50f9357b4) | Jan 18, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f9325236bb](https://linux-hardware.org/?probe=f9325236bb) | Jan 17, 2023 |
| Dell          | Latitude 5530               | Notebook    | [fafa35ef88](https://linux-hardware.org/?probe=fafa35ef88) | Jan 17, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [2cc8923eb1](https://linux-hardware.org/?probe=2cc8923eb1) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a71c911bcf](https://linux-hardware.org/?probe=a71c911bcf) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [856324369f](https://linux-hardware.org/?probe=856324369f) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [9e2cd66ef5](https://linux-hardware.org/?probe=9e2cd66ef5) | Jan 16, 2023 |
| HP            | ProBook 4540s               | Notebook    | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [4da81f73f5](https://linux-hardware.org/?probe=4da81f73f5) | Jan 16, 2023 |
| Google        | Banon                       | Notebook    | [6bb3ed04f9](https://linux-hardware.org/?probe=6bb3ed04f9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | Notebook    | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [dc5f6d7ac6](https://linux-hardware.org/?probe=dc5f6d7ac6) | Jan 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [976f23d99e](https://linux-hardware.org/?probe=976f23d99e) | Jan 16, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [01c0e96288](https://linux-hardware.org/?probe=01c0e96288) | Jan 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [895f75daf7](https://linux-hardware.org/?probe=895f75daf7) | Jan 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [57cd4eaca3](https://linux-hardware.org/?probe=57cd4eaca3) | Jan 15, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [bdfc087b4d](https://linux-hardware.org/?probe=bdfc087b4d) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [dd0a234ebb](https://linux-hardware.org/?probe=dd0a234ebb) | Jan 14, 2023 |
| Dell          | Latitude E5410              | Notebook    | [909ca0fd93](https://linux-hardware.org/?probe=909ca0fd93) | Jan 14, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [116b26047d](https://linux-hardware.org/?probe=116b26047d) | Jan 14, 2023 |
| Supermicro    | A1SA2-2750F                 | Server      | [e134d7a317](https://linux-hardware.org/?probe=e134d7a317) | Jan 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [c4cfa1aa47](https://linux-hardware.org/?probe=c4cfa1aa47) | Jan 13, 2023 |
| HP            | ZBook Studio G4             | Notebook    | [67168cc8a9](https://linux-hardware.org/?probe=67168cc8a9) | Jan 13, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [85d6a0b721](https://linux-hardware.org/?probe=85d6a0b721) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | Notebook    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| realme        | CloudProXXXX                | Notebook    | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [178c6f90fa](https://linux-hardware.org/?probe=178c6f90fa) | Jan 13, 2023 |
| Dell          | Latitude 3350               | Notebook    | [065c4a4a95](https://linux-hardware.org/?probe=065c4a4a95) | Jan 12, 2023 |
| Lenovo        | G770 1037                   | Notebook    | [da21020be1](https://linux-hardware.org/?probe=da21020be1) | Jan 12, 2023 |
| HP            | 8648                        | Desktop     | [df76c90c20](https://linux-hardware.org/?probe=df76c90c20) | Jan 12, 2023 |
| Notebook      | NS50MU                      | Notebook    | [7d94a36b67](https://linux-hardware.org/?probe=7d94a36b67) | Jan 12, 2023 |
| Standard      | Unknown                     | Notebook    | [b6f4b12847](https://linux-hardware.org/?probe=b6f4b12847) | Jan 12, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [77c659307a](https://linux-hardware.org/?probe=77c659307a) | Jan 11, 2023 |
| HP            | Pavilion dv9500             | Notebook    | [0f8c99e8d7](https://linux-hardware.org/?probe=0f8c99e8d7) | Jan 11, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [3696db52a7](https://linux-hardware.org/?probe=3696db52a7) | Jan 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [379a5aa220](https://linux-hardware.org/?probe=379a5aa220) | Jan 11, 2023 |
| Sony          | VPCEB3L9E                   | Notebook    | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [7588fecfe8](https://linux-hardware.org/?probe=7588fecfe8) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [69b3403f94](https://linux-hardware.org/?probe=69b3403f94) | Jan 10, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [27b63fd8b1](https://linux-hardware.org/?probe=27b63fd8b1) | Jan 10, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [16a4dc82f5](https://linux-hardware.org/?probe=16a4dc82f5) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [be24cf68d4](https://linux-hardware.org/?probe=be24cf68d4) | Jan 10, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [1375baed6d](https://linux-hardware.org/?probe=1375baed6d) | Jan 09, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [4bbe8325bd](https://linux-hardware.org/?probe=4bbe8325bd) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5663965a51](https://linux-hardware.org/?probe=5663965a51) | Jan 09, 2023 |
| Gigabyte      | J1900N-D2H                  | Desktop     | [62be43a4a3](https://linux-hardware.org/?probe=62be43a4a3) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [1f97553f11](https://linux-hardware.org/?probe=1f97553f11) | Jan 08, 2023 |
| Dell          | 0WG855                      | Desktop     | [0a2e7733bf](https://linux-hardware.org/?probe=0a2e7733bf) | Jan 08, 2023 |
| Acer          | Aspire One 721              | Notebook    | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b39a58c2e6](https://linux-hardware.org/?probe=b39a58c2e6) | Jan 08, 2023 |
| Acer          | TravelMate P614-51-G2       | Notebook    | [0d0c035342](https://linux-hardware.org/?probe=0d0c035342) | Jan 08, 2023 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [8ca4d7b38b](https://linux-hardware.org/?probe=8ca4d7b38b) | Jan 08, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [ebf4546adf](https://linux-hardware.org/?probe=ebf4546adf) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [782467ee8c](https://linux-hardware.org/?probe=782467ee8c) | Jan 07, 2023 |
| Standard      | X50-V2                      | Desktop     | [69b7593670](https://linux-hardware.org/?probe=69b7593670) | Jan 07, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [67b5b9902a](https://linux-hardware.org/?probe=67b5b9902a) | Jan 06, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [1ff445305d](https://linux-hardware.org/?probe=1ff445305d) | Jan 06, 2023 |
| Unknown       | HX90                        | Desktop     | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e3c76a5b82](https://linux-hardware.org/?probe=e3c76a5b82) | Jan 05, 2023 |
| HP            | 8648                        | Desktop     | [2345926399](https://linux-hardware.org/?probe=2345926399) | Jan 05, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| HP            | Pavilion 17                 | Notebook    | [fe325358d6](https://linux-hardware.org/?probe=fe325358d6) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4335d83dfc](https://linux-hardware.org/?probe=4335d83dfc) | Jan 04, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [8027cc9eeb](https://linux-hardware.org/?probe=8027cc9eeb) | Jan 04, 2023 |
| Dell          | Latitude E6330              | Notebook    | [0341a89f2f](https://linux-hardware.org/?probe=0341a89f2f) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | Notebook    | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2f148d690a](https://linux-hardware.org/?probe=2f148d690a) | Jan 03, 2023 |
| ASUSTek       | F1A55-V                     | Desktop     | [fec2a24044](https://linux-hardware.org/?probe=fec2a24044) | Jan 03, 2023 |
| Acer          | Aspire E5-774               | Notebook    | [96c68886cf](https://linux-hardware.org/?probe=96c68886cf) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| Acer          | Aspire V3-574G              | Notebook    | [a889bba557](https://linux-hardware.org/?probe=a889bba557) | Jan 02, 2023 |
| Lenovo        | 31A7 SDK0J40697 WIN 3305... | Mini pc     | [efa2748c95](https://linux-hardware.org/?probe=efa2748c95) | Jan 02, 2023 |
| HP            | 3048h                       | Desktop     | [dabc36c98f](https://linux-hardware.org/?probe=dabc36c98f) | Jan 02, 2023 |
| Intel         | NUC5PPYB H76558-108         | Mini pc     | [e93bf27a59](https://linux-hardware.org/?probe=e93bf27a59) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f31ae01428](https://linux-hardware.org/?probe=f31ae01428) | Jan 02, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [0229b8166f](https://linux-hardware.org/?probe=0229b8166f) | Jan 02, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [6def847114](https://linux-hardware.org/?probe=6def847114) | Jan 01, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1E70... | Notebook    | [e8b6dd6f1f](https://linux-hardware.org/?probe=e8b6dd6f1f) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [500ce7ae28](https://linux-hardware.org/?probe=500ce7ae28) | Dec 31, 2022 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [d1f655b9b1](https://linux-hardware.org/?probe=d1f655b9b1) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP14... | Convertible | [195eb3e6eb](https://linux-hardware.org/?probe=195eb3e6eb) | Dec 31, 2022 |
| HP            | Pavilion 17                 | Notebook    | [c87d61d0cd](https://linux-hardware.org/?probe=c87d61d0cd) | Dec 31, 2022 |
| HP            | Pavilion 17                 | Notebook    | [bbf52af119](https://linux-hardware.org/?probe=bbf52af119) | Dec 31, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [fc108fb0d8](https://linux-hardware.org/?probe=fc108fb0d8) | Dec 31, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [9e794046d8](https://linux-hardware.org/?probe=9e794046d8) | Dec 30, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [c14cfe5386](https://linux-hardware.org/?probe=c14cfe5386) | Dec 29, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [9f431b484a](https://linux-hardware.org/?probe=9f431b484a) | Dec 29, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [b8cb61c70a](https://linux-hardware.org/?probe=b8cb61c70a) | Dec 29, 2022 |
| ASRock        | Z790 PG Riptide             | Desktop     | [19c8814aba](https://linux-hardware.org/?probe=19c8814aba) | Dec 29, 2022 |
| Alienware     | x17 R2                      | Notebook    | [5a7ea2683a](https://linux-hardware.org/?probe=5a7ea2683a) | Dec 28, 2022 |
| Gigabyte      | GB-BRR3H-4300               | Desktop     | [241d631981](https://linux-hardware.org/?probe=241d631981) | Dec 28, 2022 |
| Dell          | Latitude 2120               | Notebook    | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [488d26f3e8](https://linux-hardware.org/?probe=488d26f3e8) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| LG Electro... | 17Z90Q-G.AA79G              | Notebook    | [59d7266746](https://linux-hardware.org/?probe=59d7266746) | Dec 26, 2022 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [43c2d92e5f](https://linux-hardware.org/?probe=43c2d92e5f) | Dec 26, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [3d8320e362](https://linux-hardware.org/?probe=3d8320e362) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [5d95c28ac6](https://linux-hardware.org/?probe=5d95c28ac6) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [a98ca87f6a](https://linux-hardware.org/?probe=a98ca87f6a) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [00af244895](https://linux-hardware.org/?probe=00af244895) | Dec 25, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5047d29893](https://linux-hardware.org/?probe=5047d29893) | Dec 24, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [ce9fc7a224](https://linux-hardware.org/?probe=ce9fc7a224) | Dec 24, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [0c1d9b9b28](https://linux-hardware.org/?probe=0c1d9b9b28) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [000660b461](https://linux-hardware.org/?probe=000660b461) | Dec 23, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [82cc0b362d](https://linux-hardware.org/?probe=82cc0b362d) | Dec 23, 2022 |
| Intel         | X99                         | Desktop     | [191fefa053](https://linux-hardware.org/?probe=191fefa053) | Dec 23, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [313bf04928](https://linux-hardware.org/?probe=313bf04928) | Dec 22, 2022 |
| Lenovo        | IdeaPad 3 14IAU7 82RJ       | Notebook    | [b5c5aba33a](https://linux-hardware.org/?probe=b5c5aba33a) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF003QU... | Notebook    | [5145350f9a](https://linux-hardware.org/?probe=5145350f9a) | Dec 21, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [9b188c358e](https://linux-hardware.org/?probe=9b188c358e) | Dec 21, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [6a6ba7eba1](https://linux-hardware.org/?probe=6a6ba7eba1) | Dec 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [90331ea7da](https://linux-hardware.org/?probe=90331ea7da) | Dec 21, 2022 |
| Dell          | Latitude 5521               | Notebook    | [6fcbfd9271](https://linux-hardware.org/?probe=6fcbfd9271) | Dec 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [638667a90f](https://linux-hardware.org/?probe=638667a90f) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [82687103ac](https://linux-hardware.org/?probe=82687103ac) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [7f18d05353](https://linux-hardware.org/?probe=7f18d05353) | Dec 20, 2022 |
| HP            | 3048h                       | Desktop     | [4535cf0f5a](https://linux-hardware.org/?probe=4535cf0f5a) | Dec 20, 2022 |
| HP            | 3048h                       | Desktop     | [1d795fdd33](https://linux-hardware.org/?probe=1d795fdd33) | Dec 19, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2fa8510855](https://linux-hardware.org/?probe=2fa8510855) | Dec 19, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [8d876c21b0](https://linux-hardware.org/?probe=8d876c21b0) | Dec 18, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [71575f3d8c](https://linux-hardware.org/?probe=71575f3d8c) | Dec 18, 2022 |
| HP            | ProLiant ML350 G6           | Desktop     | [3b242628e4](https://linux-hardware.org/?probe=3b242628e4) | Dec 18, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [06f90011b2](https://linux-hardware.org/?probe=06f90011b2) | Dec 18, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [64f5eb2f4b](https://linux-hardware.org/?probe=64f5eb2f4b) | Dec 17, 2022 |
| ASUSTek       | K50IE                       | Notebook    | [5681babfa5](https://linux-hardware.org/?probe=5681babfa5) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [db147cf534](https://linux-hardware.org/?probe=db147cf534) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [fa2cc2d975](https://linux-hardware.org/?probe=fa2cc2d975) | Dec 17, 2022 |
| Acer          | Aspire XC-1660 V:1.1        | Desktop     | [88aa1f841a](https://linux-hardware.org/?probe=88aa1f841a) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [3fd939cef5](https://linux-hardware.org/?probe=3fd939cef5) | Dec 17, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [182e467ce6](https://linux-hardware.org/?probe=182e467ce6) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [41f02987e9](https://linux-hardware.org/?probe=41f02987e9) | Dec 16, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7b3f9b5af0](https://linux-hardware.org/?probe=7b3f9b5af0) | Dec 16, 2022 |
| Dell          | Latitude 3120               | Notebook    | [e886df2722](https://linux-hardware.org/?probe=e886df2722) | Dec 16, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [cb963df304](https://linux-hardware.org/?probe=cb963df304) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | Notebook    | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [bc8782be9a](https://linux-hardware.org/?probe=bc8782be9a) | Dec 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d320b71c77](https://linux-hardware.org/?probe=d320b71c77) | Dec 15, 2022 |
| HP            | 3048h                       | Desktop     | [63f57e3458](https://linux-hardware.org/?probe=63f57e3458) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [35ef32b165](https://linux-hardware.org/?probe=35ef32b165) | Dec 14, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b90d5cfed0](https://linux-hardware.org/?probe=b90d5cfed0) | Dec 14, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [de26ffa293](https://linux-hardware.org/?probe=de26ffa293) | Dec 14, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [dd65da9c9b](https://linux-hardware.org/?probe=dd65da9c9b) | Dec 14, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e94792b948](https://linux-hardware.org/?probe=e94792b948) | Dec 13, 2022 |
| Gigabyte      | P35-DS4                     | Desktop     | [3f787740f8](https://linux-hardware.org/?probe=3f787740f8) | Dec 12, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [ee22896cd2](https://linux-hardware.org/?probe=ee22896cd2) | Dec 12, 2022 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [e9c5ef16cd](https://linux-hardware.org/?probe=e9c5ef16cd) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| HP            | 339A                        | Desktop     | [63c184fafd](https://linux-hardware.org/?probe=63c184fafd) | Dec 12, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [f1aa6058e3](https://linux-hardware.org/?probe=f1aa6058e3) | Dec 12, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [56adac1fcb](https://linux-hardware.org/?probe=56adac1fcb) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2c52e941ea](https://linux-hardware.org/?probe=2c52e941ea) | Dec 11, 2022 |
| Medion        | E4251                       | Notebook    | [f7303bf4c9](https://linux-hardware.org/?probe=f7303bf4c9) | Dec 11, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [cd7399049b](https://linux-hardware.org/?probe=cd7399049b) | Dec 11, 2022 |
| Supermicro    | C7SIM-Q                     | Desktop     | [76cf2b62db](https://linux-hardware.org/?probe=76cf2b62db) | Dec 11, 2022 |
| Medion        | E4251                       | Notebook    | [a16b01515b](https://linux-hardware.org/?probe=a16b01515b) | Dec 10, 2022 |
| HP            | 3048h                       | Desktop     | [c2fd939c1f](https://linux-hardware.org/?probe=c2fd939c1f) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [173f4b722f](https://linux-hardware.org/?probe=173f4b722f) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [25d5b5623b](https://linux-hardware.org/?probe=25d5b5623b) | Dec 10, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [869e2a9671](https://linux-hardware.org/?probe=869e2a9671) | Dec 09, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [503b61f120](https://linux-hardware.org/?probe=503b61f120) | Dec 09, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [e5ba0c8749](https://linux-hardware.org/?probe=e5ba0c8749) | Dec 09, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [1a4bdc4874](https://linux-hardware.org/?probe=1a4bdc4874) | Dec 07, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [611fd80398](https://linux-hardware.org/?probe=611fd80398) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [27dc9420ed](https://linux-hardware.org/?probe=27dc9420ed) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [9b7c1953a6](https://linux-hardware.org/?probe=9b7c1953a6) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| Lenovo        | ThinkPad T510 4349AF5       | Notebook    | [a7d8d66fb7](https://linux-hardware.org/?probe=a7d8d66fb7) | Dec 07, 2022 |
| Dell          | XPS 9320                    | Notebook    | [34c3b0b6a0](https://linux-hardware.org/?probe=34c3b0b6a0) | Dec 06, 2022 |
| Medion        | E4251                       | Notebook    | [a515c5c071](https://linux-hardware.org/?probe=a515c5c071) | Dec 05, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [da82fb083d](https://linux-hardware.org/?probe=da82fb083d) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [05f6a48b4a](https://linux-hardware.org/?probe=05f6a48b4a) | Dec 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c22a748043](https://linux-hardware.org/?probe=c22a748043) | Dec 05, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [86e9e1e21e](https://linux-hardware.org/?probe=86e9e1e21e) | Dec 05, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [942312fe9e](https://linux-hardware.org/?probe=942312fe9e) | Dec 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [344b0c3082](https://linux-hardware.org/?probe=344b0c3082) | Dec 05, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [481a9c958a](https://linux-hardware.org/?probe=481a9c958a) | Dec 04, 2022 |
| ASRock        | X300-ITX                    | Desktop     | [77d8c41481](https://linux-hardware.org/?probe=77d8c41481) | Dec 04, 2022 |
| Intel         | Unknown                     | Desktop     | [d00187a52a](https://linux-hardware.org/?probe=d00187a52a) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8890572a5](https://linux-hardware.org/?probe=d8890572a5) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [2cf560b162](https://linux-hardware.org/?probe=2cf560b162) | Dec 03, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [c3f4fd226e](https://linux-hardware.org/?probe=c3f4fd226e) | Dec 03, 2022 |
| Medion        | E4251                       | Notebook    | [3167cbece1](https://linux-hardware.org/?probe=3167cbece1) | Dec 03, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [422dde5ae5](https://linux-hardware.org/?probe=422dde5ae5) | Dec 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c300b0a438](https://linux-hardware.org/?probe=c300b0a438) | Dec 03, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [b0437249b0](https://linux-hardware.org/?probe=b0437249b0) | Dec 03, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [f86e02dee0](https://linux-hardware.org/?probe=f86e02dee0) | Dec 03, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [5864876eff](https://linux-hardware.org/?probe=5864876eff) | Dec 02, 2022 |
| Acer          | Iconia W4-820               | Notebook    | [cf25eeba85](https://linux-hardware.org/?probe=cf25eeba85) | Dec 01, 2022 |
| MSI           | GL62M 7RE                   | Notebook    | [5fcb394edb](https://linux-hardware.org/?probe=5fcb394edb) | Dec 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [df74bf8e13](https://linux-hardware.org/?probe=df74bf8e13) | Dec 01, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [e8d75cbeed](https://linux-hardware.org/?probe=e8d75cbeed) | Dec 01, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [b461d54421](https://linux-hardware.org/?probe=b461d54421) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F2S2UR02    | Notebook    | [29c5e0f7b1](https://linux-hardware.org/?probe=29c5e0f7b1) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [cdd03a3498](https://linux-hardware.org/?probe=cdd03a3498) | Dec 01, 2022 |
| Lenovo        | 3000 V100 076346G           | Notebook    | [bb04272723](https://linux-hardware.org/?probe=bb04272723) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [2731961e4c](https://linux-hardware.org/?probe=2731961e4c) | Nov 30, 2022 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [8398d00a16](https://linux-hardware.org/?probe=8398d00a16) | Nov 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d7025eb475](https://linux-hardware.org/?probe=d7025eb475) | Nov 30, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [729bb4ef87](https://linux-hardware.org/?probe=729bb4ef87) | Nov 30, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e214cb1bb9](https://linux-hardware.org/?probe=e214cb1bb9) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK S       | Desktop     | [2c5c1d6071](https://linux-hardware.org/?probe=2c5c1d6071) | Nov 30, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [dae405ee81](https://linux-hardware.org/?probe=dae405ee81) | Nov 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [9216162e85](https://linux-hardware.org/?probe=9216162e85) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [39e771bd92](https://linux-hardware.org/?probe=39e771bd92) | Nov 28, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [43fa54b5bc](https://linux-hardware.org/?probe=43fa54b5bc) | Nov 28, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [219a616346](https://linux-hardware.org/?probe=219a616346) | Nov 28, 2022 |
| Dell          | Latitude E6320              | Notebook    | [bcbdb4bf67](https://linux-hardware.org/?probe=bcbdb4bf67) | Nov 28, 2022 |
| Dell          | Latitude E6320              | Notebook    | [f77e444066](https://linux-hardware.org/?probe=f77e444066) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4c6d3faf86](https://linux-hardware.org/?probe=4c6d3faf86) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cd98ebccb9](https://linux-hardware.org/?probe=cd98ebccb9) | Nov 28, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [c4bbe90221](https://linux-hardware.org/?probe=c4bbe90221) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [81b0ea6c7a](https://linux-hardware.org/?probe=81b0ea6c7a) | Nov 27, 2022 |
| HP            | ProBook 5330m               | Notebook    | [3763f505a0](https://linux-hardware.org/?probe=3763f505a0) | Nov 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [bee2852cb0](https://linux-hardware.org/?probe=bee2852cb0) | Nov 27, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [bda395e731](https://linux-hardware.org/?probe=bda395e731) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [0138561b29](https://linux-hardware.org/?probe=0138561b29) | Nov 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [521f5c20a9](https://linux-hardware.org/?probe=521f5c20a9) | Nov 26, 2022 |
| ASUSTek       | A6R                         | Notebook    | [68f38deab1](https://linux-hardware.org/?probe=68f38deab1) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [8de1db7f12](https://linux-hardware.org/?probe=8de1db7f12) | Nov 25, 2022 |
| Dell          | Latitude 3120               | Convertible | [bb40e36093](https://linux-hardware.org/?probe=bb40e36093) | Nov 24, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [e2a8d64086](https://linux-hardware.org/?probe=e2a8d64086) | Nov 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [fa4e2d1d61](https://linux-hardware.org/?probe=fa4e2d1d61) | Nov 23, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [eaab6a8319](https://linux-hardware.org/?probe=eaab6a8319) | Nov 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [6049221fab](https://linux-hardware.org/?probe=6049221fab) | Nov 23, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [4adc436e33](https://linux-hardware.org/?probe=4adc436e33) | Nov 23, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [84a0005ad3](https://linux-hardware.org/?probe=84a0005ad3) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [c799c028af](https://linux-hardware.org/?probe=c799c028af) | Nov 23, 2022 |
| HP            | 3397                        | Desktop     | [eb8968148c](https://linux-hardware.org/?probe=eb8968148c) | Nov 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5d3424245f](https://linux-hardware.org/?probe=5d3424245f) | Nov 22, 2022 |
| Dell          | Latitude 5401               | Notebook    | [f964652e0c](https://linux-hardware.org/?probe=f964652e0c) | Nov 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [e40986d2fb](https://linux-hardware.org/?probe=e40986d2fb) | Nov 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [14debbe3e5](https://linux-hardware.org/?probe=14debbe3e5) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [7e8b56ff73](https://linux-hardware.org/?probe=7e8b56ff73) | Nov 21, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [72406b1647](https://linux-hardware.org/?probe=72406b1647) | Nov 21, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [635e9fe863](https://linux-hardware.org/?probe=635e9fe863) | Nov 21, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [09e98d8c02](https://linux-hardware.org/?probe=09e98d8c02) | Nov 21, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [e80e97466d](https://linux-hardware.org/?probe=e80e97466d) | Nov 21, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [12799c9216](https://linux-hardware.org/?probe=12799c9216) | Nov 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e7b9730a4](https://linux-hardware.org/?probe=1e7b9730a4) | Nov 21, 2022 |
| HP            | Unknown                     | Notebook    | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [52c86bac3f](https://linux-hardware.org/?probe=52c86bac3f) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [9c9af5a79e](https://linux-hardware.org/?probe=9c9af5a79e) | Nov 20, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [acb3ae70b9](https://linux-hardware.org/?probe=acb3ae70b9) | Nov 20, 2022 |
| Unknown       | X99H                        | Desktop     | [1c931e307d](https://linux-hardware.org/?probe=1c931e307d) | Nov 20, 2022 |
| Unknown       | X99H                        | Desktop     | [06c69ccbcb](https://linux-hardware.org/?probe=06c69ccbcb) | Nov 20, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7d1d0390ba](https://linux-hardware.org/?probe=7d1d0390ba) | Nov 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [3b5c35b319](https://linux-hardware.org/?probe=3b5c35b319) | Nov 19, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [39a6819014](https://linux-hardware.org/?probe=39a6819014) | Nov 19, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [3e2911ed20](https://linux-hardware.org/?probe=3e2911ed20) | Nov 19, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [3b08108f59](https://linux-hardware.org/?probe=3b08108f59) | Nov 19, 2022 |
| Intel         | X99                         | Desktop     | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| HP            | Notebook                    | Notebook    | [ded915d6cd](https://linux-hardware.org/?probe=ded915d6cd) | Nov 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [a09398bb26](https://linux-hardware.org/?probe=a09398bb26) | Nov 18, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [f0fa194e20](https://linux-hardware.org/?probe=f0fa194e20) | Nov 18, 2022 |
| Lenovo        | ThinkPad L560 20F2S2UR02    | Notebook    | [5170b27e5c](https://linux-hardware.org/?probe=5170b27e5c) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [cd01bd7dad](https://linux-hardware.org/?probe=cd01bd7dad) | Nov 16, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [62586ed7f9](https://linux-hardware.org/?probe=62586ed7f9) | Nov 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [d5a16ba775](https://linux-hardware.org/?probe=d5a16ba775) | Nov 16, 2022 |
| HP            | Pavilion dv9500             | Notebook    | [65a473401c](https://linux-hardware.org/?probe=65a473401c) | Nov 16, 2022 |
| Acer          | Aspire X3470                | Desktop     | [ccaec6d2cb](https://linux-hardware.org/?probe=ccaec6d2cb) | Nov 15, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [4a80ba0608](https://linux-hardware.org/?probe=4a80ba0608) | Nov 15, 2022 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [6f1cef8a17](https://linux-hardware.org/?probe=6f1cef8a17) | Nov 15, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [d2cf28fbb9](https://linux-hardware.org/?probe=d2cf28fbb9) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [e9182b2177](https://linux-hardware.org/?probe=e9182b2177) | Nov 15, 2022 |
| Dell          | Latitude E6510              | Notebook    | [21a6415538](https://linux-hardware.org/?probe=21a6415538) | Nov 15, 2022 |
| Dell          | Latitude E6510              | Notebook    | [3ce2f9981f](https://linux-hardware.org/?probe=3ce2f9981f) | Nov 15, 2022 |
| Dell          | Latitude E7450              | Notebook    | [3020a4edfc](https://linux-hardware.org/?probe=3020a4edfc) | Nov 15, 2022 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [ab1c46c857](https://linux-hardware.org/?probe=ab1c46c857) | Nov 15, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [db1488b844](https://linux-hardware.org/?probe=db1488b844) | Nov 15, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [54afa1ee72](https://linux-hardware.org/?probe=54afa1ee72) | Nov 15, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [35f0fc8a5a](https://linux-hardware.org/?probe=35f0fc8a5a) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [1798f04a0b](https://linux-hardware.org/?probe=1798f04a0b) | Nov 14, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [bcce834785](https://linux-hardware.org/?probe=bcce834785) | Nov 14, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [26fad3df24](https://linux-hardware.org/?probe=26fad3df24) | Nov 14, 2022 |
| SLIMBOOK      | PROX14                      | Notebook    | [a109c5bf52](https://linux-hardware.org/?probe=a109c5bf52) | Nov 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [92eb4009f3](https://linux-hardware.org/?probe=92eb4009f3) | Nov 14, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [85c469c069](https://linux-hardware.org/?probe=85c469c069) | Nov 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [dc86aa7d1e](https://linux-hardware.org/?probe=dc86aa7d1e) | Nov 13, 2022 |
| Acer          | Predator G3-710             | Desktop     | [4be3a9e016](https://linux-hardware.org/?probe=4be3a9e016) | Nov 13, 2022 |
| Dell          | Latitude 3380               | Notebook    | [f770a70f68](https://linux-hardware.org/?probe=f770a70f68) | Nov 12, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b4f06e5e2f](https://linux-hardware.org/?probe=b4f06e5e2f) | Nov 12, 2022 |
| HP            | Compaq 6820s                | Notebook    | [c852376664](https://linux-hardware.org/?probe=c852376664) | Nov 12, 2022 |
| HP            | Compaq 6820s                | Notebook    | [dee9dbd56f](https://linux-hardware.org/?probe=dee9dbd56f) | Nov 12, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [7e2577bf51](https://linux-hardware.org/?probe=7e2577bf51) | Nov 10, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [70d68c6ca1](https://linux-hardware.org/?probe=70d68c6ca1) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6dd51f8707](https://linux-hardware.org/?probe=6dd51f8707) | Nov 10, 2022 |
| ASUSTek       | N752VX                      | Notebook    | [a5b6d827b2](https://linux-hardware.org/?probe=a5b6d827b2) | Nov 10, 2022 |
| Panasonic     | CF-R9KWCTDR                 | Notebook    | [2a414f5dc5](https://linux-hardware.org/?probe=2a414f5dc5) | Nov 10, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [89aa240b37](https://linux-hardware.org/?probe=89aa240b37) | Nov 09, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | Notebook    | [e7de2507a0](https://linux-hardware.org/?probe=e7de2507a0) | Nov 09, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8383f208a6](https://linux-hardware.org/?probe=8383f208a6) | Nov 09, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [b10bd50d9c](https://linux-hardware.org/?probe=b10bd50d9c) | Nov 09, 2022 |
| MSI           | MS-1688                     | Notebook    | [d8c76d2264](https://linux-hardware.org/?probe=d8c76d2264) | Nov 09, 2022 |
| Dell          | Precision 5550              | Notebook    | [16b375ce77](https://linux-hardware.org/?probe=16b375ce77) | Nov 08, 2022 |
| Dell          | Precision 5550              | Notebook    | [1499c28fe9](https://linux-hardware.org/?probe=1499c28fe9) | Nov 08, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [d29c069985](https://linux-hardware.org/?probe=d29c069985) | Nov 08, 2022 |
| Acer          | SW5-017                     | Notebook    | [d4ff3ee29e](https://linux-hardware.org/?probe=d4ff3ee29e) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [0373b83f63](https://linux-hardware.org/?probe=0373b83f63) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [3d53b3616f](https://linux-hardware.org/?probe=3d53b3616f) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [c383da71e1](https://linux-hardware.org/?probe=c383da71e1) | Nov 06, 2022 |
| HP            | Pavilion g6                 | Notebook    | [43eefaca07](https://linux-hardware.org/?probe=43eefaca07) | Nov 06, 2022 |
| ASUSTek       | K56CA                       | Notebook    | [032fa97b2a](https://linux-hardware.org/?probe=032fa97b2a) | Nov 05, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [f80b5eaa0b](https://linux-hardware.org/?probe=f80b5eaa0b) | Nov 05, 2022 |
| Lenovo        | ThinkPad L380 20M50013MH    | Notebook    | [80ac51627a](https://linux-hardware.org/?probe=80ac51627a) | Nov 05, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [02a767e075](https://linux-hardware.org/?probe=02a767e075) | Nov 04, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [eeda582315](https://linux-hardware.org/?probe=eeda582315) | Nov 04, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [afeb473322](https://linux-hardware.org/?probe=afeb473322) | Nov 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2ff0e6e61e](https://linux-hardware.org/?probe=2ff0e6e61e) | Nov 04, 2022 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [c165c40a7e](https://linux-hardware.org/?probe=c165c40a7e) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [d4d0f735d4](https://linux-hardware.org/?probe=d4d0f735d4) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [04e15fb2d7](https://linux-hardware.org/?probe=04e15fb2d7) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [29617200dd](https://linux-hardware.org/?probe=29617200dd) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [24f27140f8](https://linux-hardware.org/?probe=24f27140f8) | Nov 03, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [11d229ea2c](https://linux-hardware.org/?probe=11d229ea2c) | Nov 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [24eea2c3f7](https://linux-hardware.org/?probe=24eea2c3f7) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [08a8e0079a](https://linux-hardware.org/?probe=08a8e0079a) | Nov 03, 2022 |
| HP            | 3646h                       | Desktop     | [e49a380102](https://linux-hardware.org/?probe=e49a380102) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0235661dbe](https://linux-hardware.org/?probe=0235661dbe) | Nov 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b4f9d04f4d](https://linux-hardware.org/?probe=b4f9d04f4d) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [d1b0eff99b](https://linux-hardware.org/?probe=d1b0eff99b) | Nov 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [020d8fd7e0](https://linux-hardware.org/?probe=020d8fd7e0) | Nov 03, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [2ece2f7351](https://linux-hardware.org/?probe=2ece2f7351) | Nov 02, 2022 |
| HP            | 1589                        | Desktop     | [81a347a6a7](https://linux-hardware.org/?probe=81a347a6a7) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [22b32d9bac](https://linux-hardware.org/?probe=22b32d9bac) | Nov 02, 2022 |
| HP            | 212A                        | Desktop     | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [24c2a01761](https://linux-hardware.org/?probe=24c2a01761) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | ProBook 4530s               | Notebook    | [6490664312](https://linux-hardware.org/?probe=6490664312) | Nov 01, 2022 |
| HP            | 3646h                       | Desktop     | [f88c9632b4](https://linux-hardware.org/?probe=f88c9632b4) | Nov 01, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [cd300a0714](https://linux-hardware.org/?probe=cd300a0714) | Nov 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [45a2f4473b](https://linux-hardware.org/?probe=45a2f4473b) | Nov 01, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [a85aef0a90](https://linux-hardware.org/?probe=a85aef0a90) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [46f1da66b6](https://linux-hardware.org/?probe=46f1da66b6) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [1409a7f78d](https://linux-hardware.org/?probe=1409a7f78d) | Oct 31, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [678ca55a4c](https://linux-hardware.org/?probe=678ca55a4c) | Oct 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [221710c9ea](https://linux-hardware.org/?probe=221710c9ea) | Oct 31, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [3cb8d29f84](https://linux-hardware.org/?probe=3cb8d29f84) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [71de876615](https://linux-hardware.org/?probe=71de876615) | Oct 30, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [21aa0f31b3](https://linux-hardware.org/?probe=21aa0f31b3) | Oct 30, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [c54736f079](https://linux-hardware.org/?probe=c54736f079) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Lenovo        | Legion Y740-17ICHg 81HH     | Notebook    | [ea1c9e069e](https://linux-hardware.org/?probe=ea1c9e069e) | Oct 29, 2022 |
| Medion        | X682X                       | Notebook    | [f05dd25a08](https://linux-hardware.org/?probe=f05dd25a08) | Oct 29, 2022 |
| ASRock        | B85 Pro4                    | Desktop     | [856d32288b](https://linux-hardware.org/?probe=856d32288b) | Oct 29, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a0714fbb29](https://linux-hardware.org/?probe=a0714fbb29) | Oct 28, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [1b93a2f7df](https://linux-hardware.org/?probe=1b93a2f7df) | Oct 28, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [9a01d62b1e](https://linux-hardware.org/?probe=9a01d62b1e) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3e6896ee0a](https://linux-hardware.org/?probe=3e6896ee0a) | Oct 28, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [2b886c255e](https://linux-hardware.org/?probe=2b886c255e) | Oct 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [8e25520b70](https://linux-hardware.org/?probe=8e25520b70) | Oct 27, 2022 |
| Dell          | Inspiron 7773               | Notebook    | [34d97b7ea2](https://linux-hardware.org/?probe=34d97b7ea2) | Oct 26, 2022 |
| Dell          | Inspiron 7773               | Notebook    | [c2cff54e7c](https://linux-hardware.org/?probe=c2cff54e7c) | Oct 26, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [6cb48a4d86](https://linux-hardware.org/?probe=6cb48a4d86) | Oct 25, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [0cb3fb3efc](https://linux-hardware.org/?probe=0cb3fb3efc) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [28c38a498d](https://linux-hardware.org/?probe=28c38a498d) | Oct 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b14c37f999](https://linux-hardware.org/?probe=b14c37f999) | Oct 25, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [d761710495](https://linux-hardware.org/?probe=d761710495) | Oct 25, 2022 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [54710cefe5](https://linux-hardware.org/?probe=54710cefe5) | Oct 24, 2022 |
| HP            | 1589                        | Desktop     | [0be048ec45](https://linux-hardware.org/?probe=0be048ec45) | Oct 24, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [2c1e50d1a2](https://linux-hardware.org/?probe=2c1e50d1a2) | Oct 22, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [6437fb22e1](https://linux-hardware.org/?probe=6437fb22e1) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [a19b5987c6](https://linux-hardware.org/?probe=a19b5987c6) | Oct 22, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [2570a4e51f](https://linux-hardware.org/?probe=2570a4e51f) | Oct 22, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [0fd183c6a8](https://linux-hardware.org/?probe=0fd183c6a8) | Oct 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [2b377dce0a](https://linux-hardware.org/?probe=2b377dce0a) | Oct 21, 2022 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [b864fd7ffa](https://linux-hardware.org/?probe=b864fd7ffa) | Oct 20, 2022 |
| Gigabyte      | GA-6LXSV 00000001           | Desktop     | [ac15415eca](https://linux-hardware.org/?probe=ac15415eca) | Oct 20, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [51f4793383](https://linux-hardware.org/?probe=51f4793383) | Oct 20, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [c37d6f2369](https://linux-hardware.org/?probe=c37d6f2369) | Oct 20, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [e389da5691](https://linux-hardware.org/?probe=e389da5691) | Oct 20, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [ad9d78fb43](https://linux-hardware.org/?probe=ad9d78fb43) | Oct 19, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [d54932d557](https://linux-hardware.org/?probe=d54932d557) | Oct 19, 2022 |
| Dell          | Latitude 3380               | Notebook    | [352bedd96b](https://linux-hardware.org/?probe=352bedd96b) | Oct 18, 2022 |
| Acer          | Aspire M1930                | Desktop     | [5b9cbd4f58](https://linux-hardware.org/?probe=5b9cbd4f58) | Oct 18, 2022 |
| Dell          | Precision 5530              | Notebook    | [9b344fe820](https://linux-hardware.org/?probe=9b344fe820) | Oct 18, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [ff225777df](https://linux-hardware.org/?probe=ff225777df) | Oct 18, 2022 |
| Dell          | Latitude 7480               | Notebook    | [7919e68317](https://linux-hardware.org/?probe=7919e68317) | Oct 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [8ba8f257d2](https://linux-hardware.org/?probe=8ba8f257d2) | Oct 18, 2022 |
| HP            | ZBook 14u G5                | Notebook    | [151433ee2e](https://linux-hardware.org/?probe=151433ee2e) | Oct 18, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [1117fe6b9e](https://linux-hardware.org/?probe=1117fe6b9e) | Oct 17, 2022 |
| Dell          | Latitude 7480               | Notebook    | [8d55df4648](https://linux-hardware.org/?probe=8d55df4648) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [6243f8cdb8](https://linux-hardware.org/?probe=6243f8cdb8) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [9e1f6ae49e](https://linux-hardware.org/?probe=9e1f6ae49e) | Oct 17, 2022 |
| Dell          | Latitude 9420               | Convertible | [319c3b9f03](https://linux-hardware.org/?probe=319c3b9f03) | Oct 17, 2022 |
| Dell          | Latitude 9420               | Convertible | [d1b9bb0a39](https://linux-hardware.org/?probe=d1b9bb0a39) | Oct 17, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c19a6241e1](https://linux-hardware.org/?probe=c19a6241e1) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2fd734cbfb](https://linux-hardware.org/?probe=2fd734cbfb) | Oct 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [ab6969eabd](https://linux-hardware.org/?probe=ab6969eabd) | Oct 17, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| Acer          | Aspire M1930                | Desktop     | [9fa87ae442](https://linux-hardware.org/?probe=9fa87ae442) | Oct 16, 2022 |
| HP            | 3646h                       | Desktop     | [c7436e0f9e](https://linux-hardware.org/?probe=c7436e0f9e) | Oct 16, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [79a5162024](https://linux-hardware.org/?probe=79a5162024) | Oct 16, 2022 |
| Acer          | Predator G3-710             | Desktop     | [289b6c8a18](https://linux-hardware.org/?probe=289b6c8a18) | Oct 16, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [289b913df1](https://linux-hardware.org/?probe=289b913df1) | Oct 16, 2022 |
| Dell          | Latitude E7450              | Notebook    | [500311a1b8](https://linux-hardware.org/?probe=500311a1b8) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [6a6f7314c0](https://linux-hardware.org/?probe=6a6f7314c0) | Oct 15, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [e5f4bf84f8](https://linux-hardware.org/?probe=e5f4bf84f8) | Oct 14, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [fcf93f53f4](https://linux-hardware.org/?probe=fcf93f53f4) | Oct 13, 2022 |
| Dell          | 0JD6X3 A05                  | Server      | [746232aa34](https://linux-hardware.org/?probe=746232aa34) | Oct 13, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [b75d98cfc2](https://linux-hardware.org/?probe=b75d98cfc2) | Oct 13, 2022 |
| Dell          | Latitude E7250              | Notebook    | [f397f81353](https://linux-hardware.org/?probe=f397f81353) | Oct 12, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [c39709c3b2](https://linux-hardware.org/?probe=c39709c3b2) | Oct 12, 2022 |
| Lenovo        | Y310                        | Notebook    | [0fe2ca4221](https://linux-hardware.org/?probe=0fe2ca4221) | Oct 12, 2022 |
| Dell          | Latitude E6420              | Notebook    | [0083bd14b8](https://linux-hardware.org/?probe=0083bd14b8) | Oct 12, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| ASUSTek       | P7P55-M                     | Desktop     | [5f84ed0900](https://linux-hardware.org/?probe=5f84ed0900) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [93ca81946a](https://linux-hardware.org/?probe=93ca81946a) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [921c4a26d1](https://linux-hardware.org/?probe=921c4a26d1) | Oct 11, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5be6738277](https://linux-hardware.org/?probe=5be6738277) | Oct 11, 2022 |
| HP            | 304Ah                       | Desktop     | [69f11e2008](https://linux-hardware.org/?probe=69f11e2008) | Oct 11, 2022 |
| Dell          | 0D441T A01                  | Desktop     | [f74cee10ac](https://linux-hardware.org/?probe=f74cee10ac) | Oct 11, 2022 |
| Standard      | X50-V2                      | Desktop     | [fbcfd56903](https://linux-hardware.org/?probe=fbcfd56903) | Oct 11, 2022 |
| Acer          | Predator PH317-52           | Notebook    | [379aad9180](https://linux-hardware.org/?probe=379aad9180) | Oct 10, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [cc663da2bc](https://linux-hardware.org/?probe=cc663da2bc) | Oct 10, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [11b9941d1c](https://linux-hardware.org/?probe=11b9941d1c) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [6c2f880759](https://linux-hardware.org/?probe=6c2f880759) | Oct 09, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [1a6ea38863](https://linux-hardware.org/?probe=1a6ea38863) | Oct 09, 2022 |
| Acer          | Aspire G7750                | Desktop     | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| Medion        | H110H4-EM2                  | Desktop     | [7bd38709d3](https://linux-hardware.org/?probe=7bd38709d3) | Oct 09, 2022 |
| MSI           | GP60 2PE                    | Notebook    | [530a81df09](https://linux-hardware.org/?probe=530a81df09) | Oct 09, 2022 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [8858f6d8f3](https://linux-hardware.org/?probe=8858f6d8f3) | Oct 08, 2022 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [baed8b1258](https://linux-hardware.org/?probe=baed8b1258) | Oct 08, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [b3b9f964b7](https://linux-hardware.org/?probe=b3b9f964b7) | Oct 08, 2022 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [8ac874aef9](https://linux-hardware.org/?probe=8ac874aef9) | Oct 07, 2022 |
| Toshiba       | Satellite Pro P200          | Notebook    | [1ca9c6c574](https://linux-hardware.org/?probe=1ca9c6c574) | Oct 07, 2022 |
| Dell          | Latitude E6510              | Notebook    | [67f07a2413](https://linux-hardware.org/?probe=67f07a2413) | Oct 07, 2022 |
| HP            | 339A                        | Desktop     | [0cdc6fdbc0](https://linux-hardware.org/?probe=0cdc6fdbc0) | Oct 07, 2022 |
| Intel         | NUC6CAYB J26842-410         | Mini pc     | [e86f93cf49](https://linux-hardware.org/?probe=e86f93cf49) | Oct 07, 2022 |
| HP            | 339A                        | Desktop     | [2e2105c60b](https://linux-hardware.org/?probe=2e2105c60b) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [afeba82ecf](https://linux-hardware.org/?probe=afeba82ecf) | Oct 07, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [8130af2fab](https://linux-hardware.org/?probe=8130af2fab) | Oct 06, 2022 |
| HP            | 843B                        | Desktop     | [5a744e115f](https://linux-hardware.org/?probe=5a744e115f) | Oct 06, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [c8c6a428db](https://linux-hardware.org/?probe=c8c6a428db) | Oct 06, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [ae7f5753fd](https://linux-hardware.org/?probe=ae7f5753fd) | Oct 05, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [7fe9bf7f20](https://linux-hardware.org/?probe=7fe9bf7f20) | Oct 05, 2022 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [b30ac8d979](https://linux-hardware.org/?probe=b30ac8d979) | Oct 05, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [55afdd2a98](https://linux-hardware.org/?probe=55afdd2a98) | Oct 04, 2022 |
| Dell          | Precision 7560              | Notebook    | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Dell          | Latitude 3120               | Convertible | [60de9a1977](https://linux-hardware.org/?probe=60de9a1977) | Oct 04, 2022 |
| Lenovo        | ThinkPad T430s 2356B46      | Notebook    | [defefb2514](https://linux-hardware.org/?probe=defefb2514) | Oct 04, 2022 |
| Toshiba       | Satellite Pro P200          | Notebook    | [d08fe22261](https://linux-hardware.org/?probe=d08fe22261) | Oct 03, 2022 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [9f15eece8f](https://linux-hardware.org/?probe=9f15eece8f) | Oct 03, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [0d67980efe](https://linux-hardware.org/?probe=0d67980efe) | Oct 03, 2022 |
| Samsung       | 550XED                      | Notebook    | [f2e8965164](https://linux-hardware.org/?probe=f2e8965164) | Oct 03, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [36b32fe8c0](https://linux-hardware.org/?probe=36b32fe8c0) | Oct 03, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [971859f63e](https://linux-hardware.org/?probe=971859f63e) | Oct 02, 2022 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [23475045f2](https://linux-hardware.org/?probe=23475045f2) | Oct 02, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [42113dd7e3](https://linux-hardware.org/?probe=42113dd7e3) | Oct 01, 2022 |
| HP            | 843B                        | Desktop     | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6525098252](https://linux-hardware.org/?probe=6525098252) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [4c5134b8fc](https://linux-hardware.org/?probe=4c5134b8fc) | Oct 01, 2022 |
| System76      | Darter Pro                  | Notebook    | [2829e72506](https://linux-hardware.org/?probe=2829e72506) | Oct 01, 2022 |
| System76      | Darter Pro                  | Notebook    | [c142cf370a](https://linux-hardware.org/?probe=c142cf370a) | Oct 01, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [e7ef06706d](https://linux-hardware.org/?probe=e7ef06706d) | Sep 30, 2022 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [73e2559339](https://linux-hardware.org/?probe=73e2559339) | Sep 30, 2022 |
| Dell          | Latitude 5400               | Notebook    | [66a5bc26f0](https://linux-hardware.org/?probe=66a5bc26f0) | Sep 30, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [11e4602764](https://linux-hardware.org/?probe=11e4602764) | Sep 30, 2022 |
| Dell          | Latitude 3310               | Notebook    | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [d5c0e2c5d3](https://linux-hardware.org/?probe=d5c0e2c5d3) | Sep 30, 2022 |
| Dell          | Latitude 5400               | Notebook    | [4536a4b473](https://linux-hardware.org/?probe=4536a4b473) | Sep 29, 2022 |
| Dell          | Latitude 5400               | Notebook    | [972e4ab3fa](https://linux-hardware.org/?probe=972e4ab3fa) | Sep 29, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [b248539946](https://linux-hardware.org/?probe=b248539946) | Sep 29, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e228fa6546](https://linux-hardware.org/?probe=e228fa6546) | Sep 28, 2022 |
| Dell          | Latitude 3310               | Notebook    | [c21a321dce](https://linux-hardware.org/?probe=c21a321dce) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [2e9902fee0](https://linux-hardware.org/?probe=2e9902fee0) | Sep 28, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [10b723415e](https://linux-hardware.org/?probe=10b723415e) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [932a938506](https://linux-hardware.org/?probe=932a938506) | Sep 28, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [9489561c26](https://linux-hardware.org/?probe=9489561c26) | Sep 28, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [c3041b210f](https://linux-hardware.org/?probe=c3041b210f) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [4073c084df](https://linux-hardware.org/?probe=4073c084df) | Sep 28, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Samsung       | 750XED                      | Notebook    | [dcb54d69f8](https://linux-hardware.org/?probe=dcb54d69f8) | Sep 27, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [d0f8e8a0f6](https://linux-hardware.org/?probe=d0f8e8a0f6) | Sep 27, 2022 |
| Dell          | Latitude 3300               | Notebook    | [365349d964](https://linux-hardware.org/?probe=365349d964) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [af23e43e99](https://linux-hardware.org/?probe=af23e43e99) | Sep 27, 2022 |
| Dell          | Latitude 3310               | Notebook    | [313ab64584](https://linux-hardware.org/?probe=313ab64584) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [d46d96565b](https://linux-hardware.org/?probe=d46d96565b) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f5f99a7234](https://linux-hardware.org/?probe=f5f99a7234) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7cea84adb2](https://linux-hardware.org/?probe=7cea84adb2) | Sep 27, 2022 |
| Dell          | Precision M6800             | Notebook    | [a2f07e79d3](https://linux-hardware.org/?probe=a2f07e79d3) | Sep 27, 2022 |
| Dell          | Latitude 3120               | Convertible | [bc34bf4d73](https://linux-hardware.org/?probe=bc34bf4d73) | Sep 27, 2022 |
| Dell          | Latitude 3120               | Convertible | [56ac60a3dc](https://linux-hardware.org/?probe=56ac60a3dc) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [8736347f60](https://linux-hardware.org/?probe=8736347f60) | Sep 26, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ee7c1fce66](https://linux-hardware.org/?probe=ee7c1fce66) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9d1392e945](https://linux-hardware.org/?probe=9d1392e945) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0f1fb4687f](https://linux-hardware.org/?probe=0f1fb4687f) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [6ce0a09785](https://linux-hardware.org/?probe=6ce0a09785) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [a6ce17cd6b](https://linux-hardware.org/?probe=a6ce17cd6b) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [87af9a8980](https://linux-hardware.org/?probe=87af9a8980) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [9458cffde8](https://linux-hardware.org/?probe=9458cffde8) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [8c94cd9bd3](https://linux-hardware.org/?probe=8c94cd9bd3) | Sep 26, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [ac1ee4aab2](https://linux-hardware.org/?probe=ac1ee4aab2) | Sep 25, 2022 |
| Dell          | Latitude 13                 | Notebook    | [28d623103e](https://linux-hardware.org/?probe=28d623103e) | Sep 25, 2022 |
| Dell          | Precision M6800             | Notebook    | [83c3e91298](https://linux-hardware.org/?probe=83c3e91298) | Sep 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [08bd4079f4](https://linux-hardware.org/?probe=08bd4079f4) | Sep 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [ccba8f6c1a](https://linux-hardware.org/?probe=ccba8f6c1a) | Sep 24, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [e0eae2efbd](https://linux-hardware.org/?probe=e0eae2efbd) | Sep 24, 2022 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [977d73b98a](https://linux-hardware.org/?probe=977d73b98a) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [165b95bd2c](https://linux-hardware.org/?probe=165b95bd2c) | Sep 24, 2022 |
| Dell          | Latitude E5570              | Notebook    | [df18be69a3](https://linux-hardware.org/?probe=df18be69a3) | Sep 24, 2022 |
| Dell          | Latitude E6520              | Notebook    | [81612aa665](https://linux-hardware.org/?probe=81612aa665) | Sep 24, 2022 |
| Dell          | Latitude E6520              | Notebook    | [fc343204c6](https://linux-hardware.org/?probe=fc343204c6) | Sep 23, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [2fa25ddedf](https://linux-hardware.org/?probe=2fa25ddedf) | Sep 23, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [8e7d4a7aeb](https://linux-hardware.org/?probe=8e7d4a7aeb) | Sep 23, 2022 |
| Dell          | Latitude 3120               | Convertible | [5281ee08e1](https://linux-hardware.org/?probe=5281ee08e1) | Sep 23, 2022 |
| Dell          | Latitude E6520              | Notebook    | [79aa87fb47](https://linux-hardware.org/?probe=79aa87fb47) | Sep 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4c5dc33267](https://linux-hardware.org/?probe=4c5dc33267) | Sep 23, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [985fa1c4c7](https://linux-hardware.org/?probe=985fa1c4c7) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9c4d48864b](https://linux-hardware.org/?probe=9c4d48864b) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [443df1ca5c](https://linux-hardware.org/?probe=443df1ca5c) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [061ef6f153](https://linux-hardware.org/?probe=061ef6f153) | Sep 23, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [939f154314](https://linux-hardware.org/?probe=939f154314) | Sep 22, 2022 |
| Dell          | Latitude E6320              | Notebook    | [452304d040](https://linux-hardware.org/?probe=452304d040) | Sep 22, 2022 |
| Dell          | Latitude 3120               | Convertible | [524d713bc2](https://linux-hardware.org/?probe=524d713bc2) | Sep 22, 2022 |
| Dell          | XPS 9320                    | Notebook    | [6866f3105c](https://linux-hardware.org/?probe=6866f3105c) | Sep 22, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [efaa235d34](https://linux-hardware.org/?probe=efaa235d34) | Sep 22, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | Desktop     | [a4ab03ccc4](https://linux-hardware.org/?probe=a4ab03ccc4) | Sep 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [ce15d6d4bb](https://linux-hardware.org/?probe=ce15d6d4bb) | Sep 22, 2022 |
| ASUSTek       | 1201PN                      | Notebook    | [3dd4546344](https://linux-hardware.org/?probe=3dd4546344) | Sep 21, 2022 |
| ASUSTek       | 1201PN                      | Notebook    | [080d9c8964](https://linux-hardware.org/?probe=080d9c8964) | Sep 21, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [d0f94bde46](https://linux-hardware.org/?probe=d0f94bde46) | Sep 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [3e80cdec5b](https://linux-hardware.org/?probe=3e80cdec5b) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [f4aade3998](https://linux-hardware.org/?probe=f4aade3998) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [95c8201663](https://linux-hardware.org/?probe=95c8201663) | Sep 20, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [71339e0cfb](https://linux-hardware.org/?probe=71339e0cfb) | Sep 19, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [a0acb674df](https://linux-hardware.org/?probe=a0acb674df) | Sep 19, 2022 |
| HP            | 82B4                        | Desktop     | [f4b85399b3](https://linux-hardware.org/?probe=f4b85399b3) | Sep 19, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [6fd34fa73b](https://linux-hardware.org/?probe=6fd34fa73b) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0e1784b38d](https://linux-hardware.org/?probe=0e1784b38d) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [983266d6ba](https://linux-hardware.org/?probe=983266d6ba) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [374de3c13c](https://linux-hardware.org/?probe=374de3c13c) | Sep 19, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [4c8883345d](https://linux-hardware.org/?probe=4c8883345d) | Sep 19, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | Desktop     | [1abf3ddee3](https://linux-hardware.org/?probe=1abf3ddee3) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [bc2dd8505b](https://linux-hardware.org/?probe=bc2dd8505b) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [55332651e0](https://linux-hardware.org/?probe=55332651e0) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [e6b9b405e8](https://linux-hardware.org/?probe=e6b9b405e8) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [448ba707f6](https://linux-hardware.org/?probe=448ba707f6) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Notebook    | [558e95141d](https://linux-hardware.org/?probe=558e95141d) | Sep 19, 2022 |
| Dell          | Latitude 3300               | Notebook    | [a2513a9849](https://linux-hardware.org/?probe=a2513a9849) | Sep 19, 2022 |
| HP            | 212B                        | Desktop     | [c823e0060e](https://linux-hardware.org/?probe=c823e0060e) | Sep 19, 2022 |
| HP            | 0AA8h                       | Desktop     | [c79bdb21ed](https://linux-hardware.org/?probe=c79bdb21ed) | Sep 18, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [c6ec4f6320](https://linux-hardware.org/?probe=c6ec4f6320) | Sep 18, 2022 |
| Acer          | Aspire G7750                | Desktop     | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [daa76ef1c9](https://linux-hardware.org/?probe=daa76ef1c9) | Sep 18, 2022 |
| Acer          | Switch SA5-271P             | Tablet      | [c9900a8e2f](https://linux-hardware.org/?probe=c9900a8e2f) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [b0a2728114](https://linux-hardware.org/?probe=b0a2728114) | Sep 17, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [8c905d820d](https://linux-hardware.org/?probe=8c905d820d) | Sep 17, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [59369fa3fb](https://linux-hardware.org/?probe=59369fa3fb) | Sep 17, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [cf4e574788](https://linux-hardware.org/?probe=cf4e574788) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e472e7fdde](https://linux-hardware.org/?probe=e472e7fdde) | Sep 16, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [1ccce4a76a](https://linux-hardware.org/?probe=1ccce4a76a) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e04ec1834f](https://linux-hardware.org/?probe=e04ec1834f) | Sep 16, 2022 |
| Gigabyte      | Z97P-D3                     | Desktop     | [ca9e537823](https://linux-hardware.org/?probe=ca9e537823) | Sep 15, 2022 |
| Samsung       | 930MBE                      | Convertible | [7de986bc11](https://linux-hardware.org/?probe=7de986bc11) | Sep 14, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [c8abec750c](https://linux-hardware.org/?probe=c8abec750c) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [54ea6ab133](https://linux-hardware.org/?probe=54ea6ab133) | Sep 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [9817414c4e](https://linux-hardware.org/?probe=9817414c4e) | Sep 14, 2022 |
| Dell          | Latitude 3120               | Convertible | [a8315e1147](https://linux-hardware.org/?probe=a8315e1147) | Sep 13, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4105fc929e](https://linux-hardware.org/?probe=4105fc929e) | Sep 13, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b7eb07ec8d](https://linux-hardware.org/?probe=b7eb07ec8d) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [7064ea27f5](https://linux-hardware.org/?probe=7064ea27f5) | Sep 11, 2022 |
| HP            | 82B4                        | Desktop     | [855d078f26](https://linux-hardware.org/?probe=855d078f26) | Sep 11, 2022 |
| HP            | 82B4                        | Desktop     | [e39fbcb897](https://linux-hardware.org/?probe=e39fbcb897) | Sep 11, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [37681cbc64](https://linux-hardware.org/?probe=37681cbc64) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [81653ec6fc](https://linux-hardware.org/?probe=81653ec6fc) | Sep 11, 2022 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [a008db4da9](https://linux-hardware.org/?probe=a008db4da9) | Sep 11, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c0adc468b3](https://linux-hardware.org/?probe=c0adc468b3) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Netherlands/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 570       | 14.59%  |
| Ubuntu 18.04                 | 304       | 7.78%   |
| OpenMandriva 4.3             | 196       | 5.02%   |
| Ubuntu 22.04                 | 183       | 4.69%   |
| Debian 11                    | 90        | 2.3%    |
| Zorin 16                     | 78        | 2%      |
| Linux Mint 20.3              | 70        | 1.79%   |
| Ubuntu 20.10                 | 66        | 1.69%   |
| Arch                         | 66        | 1.69%   |
| Xubuntu 20.04                | 55        | 1.41%   |
| OpenMandriva 4.2             | 54        | 1.38%   |
| KDE neon 20.04               | 54        | 1.38%   |
| Fedora 34                    | 53        | 1.36%   |
| Linux Mint 20.2              | 52        | 1.33%   |
| Ubuntu 21.10                 | 51        | 1.31%   |
| Manjaro                      | 51        | 1.31%   |
| Fedora 36                    | 51        | 1.31%   |
| Arch Rolling                 | 51        | 1.31%   |
| Ubuntu 21.04                 | 46        | 1.18%   |
| Linux Mint 20.1              | 46        | 1.18%   |
| Linux Mint 19.3              | 46        | 1.18%   |
| Pop!_OS 22.04                | 45        | 1.15%   |
| openSUSE Tumbleweed-XXXXXXXX | 44        | 1.13%   |
| Ubuntu 19.10                 | 43        | 1.1%    |
| Pop!_OS 20.10                | 41        | 1.05%   |
| Fedora 33                    | 41        | 1.05%   |
| Fedora 37                    | 40        | 1.02%   |
| Pop!_OS 21.04                | 39        | 1%      |
| Pop!_OS 20.04                | 39        | 1%      |
| Fedora 35                    | 39        | 1%      |
| Zorin 15                     | 38        | 0.97%   |
| Kubuntu 20.04                | 38        | 0.97%   |
| Fedora 31                    | 38        | 0.97%   |
| Linux Mint 20                | 37        | 0.95%   |
| Ubuntu 19.04                 | 35        | 0.9%    |
| Pop!_OS 21.10                | 35        | 0.9%    |
| Ubuntu 22.10                 | 33        | 0.84%   |
| Fedora 32                    | 33        | 0.84%   |
| ArcoLinux Rolling            | 33        | 0.84%   |
| OpenMandriva 23.01           | 32        | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1304      | 35.23%  |
| Linux Mint    | 327       | 8.84%   |
| OpenMandriva  | 300       | 8.11%   |
| Fedora        | 267       | 7.21%   |
| Pop!_OS       | 191       | 5.16%   |
| Debian        | 146       | 3.94%   |
| Manjaro       | 142       | 3.84%   |
| Zorin         | 125       | 3.38%   |
| Arch          | 118       | 3.19%   |
| Xubuntu       | 96        | 2.59%   |
| Kubuntu       | 83        | 2.24%   |
| KDE neon      | 72        | 1.95%   |
| openSUSE      | 59        | 1.59%   |
| ArcoLinux     | 36        | 0.97%   |
| Kali          | 28        | 0.76%   |
| Gentoo        | 28        | 0.76%   |
| ROSA          | 26        | 0.7%    |
| EndeavourOS   | 26        | 0.7%    |
| Lubuntu       | 25        | 0.68%   |
| Elementary    | 24        | 0.65%   |
| Ubuntu Unity  | 22        | 0.59%   |
| Ubuntu MATE   | 20        | 0.54%   |
| Clear Linux   | 20        | 0.54%   |
| SteamOS       | 17        | 0.46%   |
| Endless       | 16        | 0.43%   |
| Ubuntu Budgie | 14        | 0.38%   |
| Parrot        | 12        | 0.32%   |
| MX            | 12        | 0.32%   |
| LMDE          | 12        | 0.32%   |
| Peppermint    | 10        | 0.27%   |
| CentOS        | 10        | 0.27%   |
| Raspbian      | 9         | 0.24%   |
| Garuda Linux  | 9         | 0.24%   |
| Solus         | 8         | 0.22%   |
| BlackPanther  | 6         | 0.16%   |
| RHEL          | 5         | 0.14%   |
| Reborn OS     | 5         | 0.14%   |
| Nobara        | 4         | 0.11%   |
| LinuxFX       | 4         | 0.11%   |
| Devuan        | 4         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 195       | 4.5%    |
| 5.4.0-42-generic         | 69        | 1.59%   |
| 5.10.14-desktop-1omv4002 | 53        | 1.22%   |
| 5.4.0-58-generic         | 43        | 0.99%   |
| 5.8.0-50-generic         | 41        | 0.95%   |
| 5.15.0-58-generic        | 37        | 0.85%   |
| 5.4.0-52-generic         | 36        | 0.83%   |
| 5.4.0-48-generic         | 35        | 0.81%   |
| 5.15.0-56-generic        | 35        | 0.81%   |
| 5.11.0-38-generic        | 33        | 0.76%   |
| 5.15.0-46-generic        | 30        | 0.69%   |
| 6.1.1-desktop-1omv2290   | 27        | 0.62%   |
| 5.8.0-43-generic         | 26        | 0.6%    |
| 5.13.0-28-generic        | 26        | 0.6%    |
| 5.11.0-27-generic        | 26        | 0.6%    |
| 5.4.0-77-generic         | 25        | 0.58%   |
| 5.4.0-26-generic         | 25        | 0.58%   |
| 5.15.0-52-generic        | 25        | 0.58%   |
| 5.4.0-40-generic         | 24        | 0.55%   |
| 5.15.0-43-generic        | 24        | 0.55%   |
| 5.19.0-35-generic        | 23        | 0.53%   |
| 5.4.0-37-generic         | 22        | 0.51%   |
| 5.15.0-60-generic        | 22        | 0.51%   |
| 5.15.0-48-generic        | 22        | 0.51%   |
| 5.8.0-53-generic         | 21        | 0.48%   |
| 5.4.0-65-generic         | 21        | 0.48%   |
| 5.13.0-39-generic        | 21        | 0.48%   |
| 5.11.0-7620-generic      | 21        | 0.48%   |
| 5.8.0-7630-generic       | 20        | 0.46%   |
| 5.4.0-56-generic         | 20        | 0.46%   |
| 5.4.0-33-generic         | 20        | 0.46%   |
| 5.4.0-29-generic         | 20        | 0.46%   |
| 5.15.0-67-generic        | 20        | 0.46%   |
| 5.3.0-46-generic         | 19        | 0.44%   |
| 5.8.0-48-generic         | 18        | 0.41%   |
| 5.4.0-54-generic         | 18        | 0.41%   |
| 5.4.0-47-generic         | 18        | 0.41%   |
| 5.11.0-43-generic        | 18        | 0.41%   |
| 4.15.0-29-generic        | 18        | 0.41%   |
| 5.8.0-44-generic         | 17        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 708       | 17.41%  |
| 5.15.0  | 333       | 8.19%   |
| 5.8.0   | 284       | 6.98%   |
| 4.15.0  | 240       | 5.9%    |
| 5.11.0  | 235       | 5.78%   |
| 5.16.7  | 198       | 4.87%   |
| 5.13.0  | 198       | 4.87%   |
| 5.3.0   | 141       | 3.47%   |
| 5.10.0  | 106       | 2.61%   |
| 5.0.0   | 106       | 2.61%   |
| 5.19.0  | 80        | 1.97%   |
| 4.18.0  | 72        | 1.77%   |
| 5.10.14 | 56        | 1.38%   |
| 4.19.0  | 36        | 0.89%   |
| 6.1.1   | 31        | 0.76%   |
| 5.14.0  | 22        | 0.54%   |
| 4.4.0   | 18        | 0.44%   |
| 5.6.0   | 16        | 0.39%   |
| 5.16.11 | 16        | 0.39%   |
| 5.17.5  | 15        | 0.37%   |
| 6.0.6   | 14        | 0.34%   |
| 5.9.16  | 14        | 0.34%   |
| 6.2.6   | 13        | 0.32%   |
| 6.1.0   | 13        | 0.32%   |
| 6.0.0   | 11        | 0.27%   |
| 5.3.18  | 11        | 0.27%   |
| 5.18.0  | 11        | 0.27%   |
| 5.17.1  | 11        | 0.27%   |
| 5.16.0  | 10        | 0.25%   |
| 6.0.12  | 9         | 0.22%   |
| 5.9.8   | 9         | 0.22%   |
| 5.9.0   | 9         | 0.22%   |
| 5.8.16  | 9         | 0.22%   |
| 5.17.0  | 9         | 0.22%   |
| 5.16.19 | 9         | 0.22%   |
| 5.15.5  | 9         | 0.22%   |
| 5.15.12 | 9         | 0.22%   |
| 5.14.14 | 9         | 0.22%   |
| 6.1.12  | 8         | 0.2%    |
| 6.0.5   | 8         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 772       | 19.2%   |
| 5.15    | 442       | 10.99%  |
| 5.8     | 335       | 8.33%   |
| 5.11    | 281       | 6.99%   |
| 5.16    | 264       | 6.57%   |
| 4.15    | 241       | 5.99%   |
| 5.13    | 239       | 5.94%   |
| 5.10    | 228       | 5.67%   |
| 5.3     | 173       | 4.3%    |
| 5.19    | 117       | 2.91%   |
| 5.0     | 110       | 2.74%   |
| 6.1     | 97        | 2.41%   |
| 4.18    | 86        | 2.14%   |
| 6.0     | 80        | 1.99%   |
| 5.17    | 68        | 1.69%   |
| 5.18    | 61        | 1.52%   |
| 5.14    | 61        | 1.52%   |
| 5.9     | 56        | 1.39%   |
| 5.6     | 51        | 1.27%   |
| 4.19    | 49        | 1.22%   |
| 5.12    | 36        | 0.9%    |
| 5.7     | 32        | 0.8%    |
| 5.5     | 28        | 0.7%    |
| 4.9     | 26        | 0.65%   |
| 6.2     | 25        | 0.62%   |
| 4.4     | 20        | 0.5%    |
| 5.2     | 9         | 0.22%   |
| 4.16    | 5         | 0.12%   |
| 4.10    | 5         | 0.12%   |
| 4.20    | 4         | 0.1%    |
| 4.14    | 4         | 0.1%    |
| 4.12    | 4         | 0.1%    |
| 3.10    | 3         | 0.07%   |
| 4.1     | 2         | 0.05%   |
| 3.16    | 2         | 0.05%   |
| 5.17.1  | 1         | 0.02%   |
| 5.1     | 1         | 0.02%   |
| 4.7     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3449      | 95.89%  |
| i686    | 100       | 2.78%   |
| aarch64 | 39        | 1.08%   |
| armv7l  | 7         | 0.19%   |
| armv8l  | 1         | 0.03%   |
| armv6l  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1654      | 44.27%  |
| KDE5             | 640       | 17.13%  |
| Unknown          | 520       | 13.92%  |
| XFCE             | 268       | 7.17%   |
| X-Cinnamon       | 243       | 6.5%    |
| KDE              | 93        | 2.49%   |
| MATE             | 77        | 2.06%   |
| Cinnamon         | 34        | 0.91%   |
| LXQt             | 27        | 0.72%   |
| Pantheon         | 24        | 0.64%   |
| Budgie           | 23        | 0.62%   |
| Unity            | 22        | 0.59%   |
| LXDE             | 21        | 0.56%   |
| i3               | 16        | 0.43%   |
| KDE4             | 15        | 0.4%    |
| GNOME Flashback  | 10        | 0.27%   |
| Openbox          | 6         | 0.16%   |
| Deepin           | 6         | 0.16%   |
| sway             | 5         | 0.13%   |
| icewm            | 5         | 0.13%   |
| qtile            | 4         | 0.11%   |
| Enlightenment    | 4         | 0.11%   |
| awesome          | 4         | 0.11%   |
| Trinity          | 2         | 0.05%   |
| lightdm-xsession | 2         | 0.05%   |
| GNOME Classic    | 2         | 0.05%   |
| xmonad           | 1         | 0.03%   |
| LeftWM           | 1         | 0.03%   |
| jwm              | 1         | 0.03%   |
| herbstluftwm     | 1         | 0.03%   |
| fluxbox          | 1         | 0.03%   |
| DWM              | 1         | 0.03%   |
| dusk             | 1         | 0.03%   |
| Core             | 1         | 0.03%   |
| bspwm            | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2809      | 76.27%  |
| Wayland | 540       | 14.66%  |
| Unknown | 255       | 6.92%   |
| Tty     | 78        | 2.12%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1932      | 51.88%  |
| SDDM    | 544       | 14.61%  |
| GDM     | 433       | 11.63%  |
| GDM3    | 379       | 10.18%  |
| LightDM | 307       | 8.24%   |
| TDM     | 94        | 2.52%   |
| KDM     | 14        | 0.38%   |
| XDM     | 8         | 0.21%   |
| Ly      | 4         | 0.11%   |
| SLiM    | 3         | 0.08%   |
| GREETD  | 3         | 0.08%   |
| NODM    | 1         | 0.03%   |
| MDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1741      | 47.27%  |
| nl_NL       | 1061      | 28.81%  |
| Unknown     | 427       | 11.59%  |
| en_GB       | 148       | 4.02%   |
| C           | 59        | 1.6%    |
| de_DE       | 36        | 0.98%   |
| pl_PL       | 33        | 0.9%    |
| ru_RU       | 24        | 0.65%   |
| en_IE       | 13        | 0.35%   |
| POSIX       | 10        | 0.27%   |
| fr_FR       | 10        | 0.27%   |
| en_NL       | 10        | 0.27%   |
| it_IT       | 8         | 0.22%   |
| en_CA       | 7         | 0.19%   |
| en_IN       | 6         | 0.16%   |
| nl_BE       | 5         | 0.14%   |
| fr_BE       | 5         | 0.14%   |
| es_ES       | 5         | 0.14%   |
| en_DK       | 5         | 0.14%   |
| ru_UA       | 4         | 0.11%   |
| pt_PT       | 4         | 0.11%   |
| en_AG       | 4         | 0.11%   |
| de_AT       | 4         | 0.11%   |
| C.UTF8      | 4         | 0.11%   |
| sv_SE       | 3         | 0.08%   |
| sk_SK       | 3         | 0.08%   |
| es_MX       | 3         | 0.08%   |
| en_US.utf-8 | 3         | 0.08%   |
| en_AU       | 3         | 0.08%   |
| cs_CZ       | 3         | 0.08%   |
| zh_CN       | 2         | 0.05%   |
| uk_UA       | 2         | 0.05%   |
| pt_BR       | 2         | 0.05%   |
| nl_AW       | 2         | 0.05%   |
| nb_NO       | 2         | 0.05%   |
| hu_HU       | 2         | 0.05%   |
| en_ZA       | 2         | 0.05%   |
| en_SG       | 2         | 0.05%   |
| ar_KW       | 2         | 0.05%   |
| tr_TR       | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1870      | 51.06%  |
| BIOS | 1792      | 48.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2794      | 76.21%  |
| Overlay | 339       | 9.25%   |
| Btrfs   | 290       | 7.91%   |
| Unknown | 125       | 3.41%   |
| Xfs     | 50        | 1.36%   |
| Zfs     | 38        | 1.04%   |
| Ext2    | 10        | 0.27%   |
| F2fs    | 8         | 0.22%   |
| Ext3    | 5         | 0.14%   |
| Tmpfs   | 3         | 0.08%   |
| Aufs    | 3         | 0.08%   |
| Jfs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2074      | 56.6%   |
| GPT     | 1278      | 34.88%  |
| MBR     | 312       | 8.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3131      | 85.59%  |
| Yes       | 527       | 14.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2554      | 70.07%  |
| Yes       | 1091      | 29.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 586       | 16.32%  |
| Hewlett-Packard         | 571       | 15.91%  |
| ASUSTek Computer        | 511       | 14.23%  |
| Lenovo                  | 395       | 11%     |
| Acer                    | 224       | 6.24%   |
| MSI                     | 204       | 5.68%   |
| Gigabyte Technology     | 199       | 5.54%   |
| ASRock                  | 145       | 4.04%   |
| Apple                   | 108       | 3.01%   |
| Intel                   | 73        | 2.03%   |
| Medion                  | 58        | 1.62%   |
| Toshiba                 | 53        | 1.48%   |
| Notebook                | 46        | 1.28%   |
| Raspberry Pi Foundation | 41        | 1.14%   |
| Unknown                 | 27        | 0.75%   |
| Packard Bell            | 26        | 0.72%   |
| Samsung Electronics     | 24        | 0.67%   |
| Fujitsu                 | 21        | 0.58%   |
| Google                  | 18        | 0.5%    |
| Valve                   | 15        | 0.42%   |
| Sony                    | 15        | 0.42%   |
| Microsoft               | 15        | 0.42%   |
| HUAWEI                  | 14        | 0.39%   |
| Fujitsu Siemens         | 12        | 0.33%   |
| Foxconn                 | 11        | 0.31%   |
| Alienware               | 10        | 0.28%   |
| Supermicro              | 8         | 0.22%   |
| Pegatron                | 8         | 0.22%   |
| Biostar                 | 7         | 0.19%   |
| TUXEDO                  | 6         | 0.17%   |
| Timi                    | 6         | 0.17%   |
| Shuttle                 | 6         | 0.17%   |
| ZOTAC                   | 5         | 0.14%   |
| AMI                     | 5         | 0.14%   |
| System76                | 4         | 0.11%   |
| PC Specialist           | 4         | 0.11%   |
| Insyde                  | 4         | 0.11%   |
| Chuwi                   | 4         | 0.11%   |
| BESSTAR Tech            | 4         | 0.11%   |
| TrekStor                | 3         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Dell Latitude 3120                  | 55        | 1.53%   |
| Dell Latitude 3190 2-in-1           | 41        | 1.14%   |
| Unknown                             | 38        | 1.06%   |
| Dell Latitude 3310                  | 31        | 0.86%   |
| ASUS All Series                     | 27        | 0.75%   |
| RPi Raspberry Pi                    | 17        | 0.47%   |
| Valve Jupiter                       | 15        | 0.42%   |
| Dell XPS 15 7590                    | 11        | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.4  | 10        | 0.28%   |
| HP Notebook                         | 10        | 0.28%   |
| Dell OptiPlex 7010                  | 10        | 0.28%   |
| MSI MS-7C02                         | 9         | 0.25%   |
| HP ZBook Studio G5                  | 8         | 0.22%   |
| HP Pavilion g7                      | 8         | 0.22%   |
| HP Pavilion dv7                     | 8         | 0.22%   |
| Dell XPS 15 9560                    | 8         | 0.22%   |
| Dell OptiPlex 3020                  | 8         | 0.22%   |
| Dell Latitude 3300                  | 8         | 0.22%   |
| ASRock B450M Pro4                   | 8         | 0.22%   |
| MSI MS-7C37                         | 7         | 0.19%   |
| MSI MS-7B86                         | 7         | 0.19%   |
| MSI MS-7817                         | 7         | 0.19%   |
| HP Pavilion Laptop 15-cw1xxx        | 7         | 0.19%   |
| HP Pavilion Gaming Laptop 15-cx0xxx | 7         | 0.19%   |
| HP Pavilion g6                      | 7         | 0.19%   |
| Dell XPS 13 9310                    | 7         | 0.19%   |
| Dell Latitude E6410                 | 7         | 0.19%   |
| Apple MacBookPro9,2                 | 7         | 0.19%   |
| MSI MS-7721                         | 6         | 0.17%   |
| Intel NUC8i3BEH                     | 6         | 0.17%   |
| HP ProBook 6570b                    | 6         | 0.17%   |
| HP Pavilion dv6                     | 6         | 0.17%   |
| HP EliteBook 8570w                  | 6         | 0.17%   |
| HP EliteBook 8460p                  | 6         | 0.17%   |
| HP Compaq Elite 8300 SFF            | 6         | 0.17%   |
| HP Compaq dc7900 Small Form Factor  | 6         | 0.17%   |
| Dell XPS 15 9570                    | 6         | 0.17%   |
| Dell XPS 15 9550                    | 6         | 0.17%   |
| Dell XPS 15 9500                    | 6         | 0.17%   |
| Dell XPS 13 9360                    | 6         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 299       | 8.33%   |
| Lenovo ThinkPad       | 205       | 5.71%   |
| Acer Aspire           | 156       | 4.35%   |
| HP Pavilion           | 100       | 2.79%   |
| HP Compaq             | 99        | 2.76%   |
| Dell XPS              | 93        | 2.59%   |
| HP EliteBook          | 90        | 2.51%   |
| Lenovo IdeaPad        | 65        | 1.81%   |
| HP ProBook            | 64        | 1.78%   |
| Dell OptiPlex         | 61        | 1.7%    |
| ASUS PRIME            | 58        | 1.62%   |
| Toshiba Satellite     | 48        | 1.34%   |
| Dell Inspiron         | 47        | 1.31%   |
| ASUS ROG              | 47        | 1.31%   |
| RPi Raspberry         | 41        | 1.14%   |
| Unknown               | 38        | 1.06%   |
| HP ZBook              | 33        | 0.92%   |
| Dell Precision        | 32        | 0.89%   |
| Lenovo Yoga           | 29        | 0.81%   |
| HP ENVY               | 29        | 0.81%   |
| ASUS All              | 27        | 0.75%   |
| Lenovo Legion         | 22        | 0.61%   |
| HP Laptop             | 20        | 0.56%   |
| ASUS VivoBook         | 20        | 0.56%   |
| Packard Bell EasyNote | 19        | 0.53%   |
| Gigabyte X570         | 19        | 0.53%   |
| ASUS TUF              | 19        | 0.53%   |
| Valve Jupiter         | 15        | 0.42%   |
| Microsoft Surface     | 15        | 0.42%   |
| Lenovo ThinkCentre    | 14        | 0.39%   |
| Fujitsu LIFEBOOK      | 13        | 0.36%   |
| Lenovo ThinkBook      | 12        | 0.33%   |
| HP ProDesk            | 12        | 0.33%   |
| Acer TravelMate       | 12        | 0.33%   |
| Acer Swift            | 12        | 0.33%   |
| HP Spectre            | 11        | 0.31%   |
| Dell Studio           | 11        | 0.31%   |
| ASUS ZenBook          | 11        | 0.31%   |
| ASRock B450M          | 11        | 0.31%   |
| HP Notebook           | 10        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 426       | 11.87%  |
| 2018    | 315       | 8.77%   |
| 2020    | 281       | 7.83%   |
| 2012    | 275       | 7.66%   |
| 2021    | 260       | 7.24%   |
| 2011    | 245       | 6.82%   |
| 2013    | 230       | 6.41%   |
| 2017    | 219       | 6.1%    |
| 2014    | 194       | 5.4%    |
| 2010    | 184       | 5.13%   |
| 2016    | 182       | 5.07%   |
| 2015    | 178       | 4.96%   |
| 2009    | 147       | 4.09%   |
| 2008    | 147       | 4.09%   |
| 2007    | 107       | 2.98%   |
| 2022    | 86        | 2.4%    |
| 2006    | 49        | 1.36%   |
| Unknown | 43        | 1.2%    |
| 2005    | 12        | 0.33%   |
| 2004    | 6         | 0.17%   |
| 2003    | 2         | 0.06%   |
| 2023    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1896      | 52.81%  |
| Desktop        | 1267      | 35.29%  |
| Convertible    | 189       | 5.26%   |
| Mini pc        | 82        | 2.28%   |
| All in one     | 46        | 1.28%   |
| System on chip | 45        | 1.25%   |
| Tablet         | 37        | 1.03%   |
| Server         | 26        | 0.72%   |
| Phone          | 2         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3315      | 91.73%  |
| Enabled  | 299       | 8.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3566      | 99.33%  |
| Yes  | 24        | 0.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 858       | 23.5%   |
| 16.01-24.0      | 746       | 20.43%  |
| 3.01-4.0        | 674       | 18.46%  |
| 8.01-16.0       | 616       | 16.87%  |
| 32.01-64.0      | 363       | 9.94%   |
| 1.01-2.0        | 136       | 3.73%   |
| 64.01-256.0     | 92        | 2.52%   |
| 2.01-3.0        | 69        | 1.89%   |
| 24.01-32.0      | 63        | 1.73%   |
| 0.51-1.0        | 32        | 0.88%   |
| More than 256.0 | 1         | 0.03%   |
| 0.01-0.5        | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1485      | 37.51%  |
| 2.01-3.0    | 928       | 23.44%  |
| 4.01-8.0    | 524       | 13.24%  |
| 3.01-4.0    | 502       | 12.68%  |
| 0.51-1.0    | 255       | 6.44%   |
| 8.01-16.0   | 181       | 4.57%   |
| 0.01-0.5    | 36        | 0.91%   |
| 16.01-24.0  | 34        | 0.86%   |
| 32.01-64.0  | 10        | 0.25%   |
| 24.01-32.0  | 3         | 0.08%   |
| 64.01-256.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2162      | 58.7%   |
| 2       | 913       | 24.79%  |
| 3       | 285       | 7.74%   |
| 4       | 141       | 3.83%   |
| 5       | 70        | 1.9%    |
| 0       | 48        | 1.3%    |
| 6       | 29        | 0.79%   |
| 7       | 19        | 0.52%   |
| 8       | 6         | 0.16%   |
| Unknown | 4         | 0.11%   |
| 9       | 3         | 0.08%   |
| 28      | 1         | 0.03%   |
| 27      | 1         | 0.03%   |
| 10      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2249      | 62.06%  |
| Yes       | 1375      | 37.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3017      | 83.76%  |
| No        | 585       | 16.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2652      | 73.52%  |
| No        | 955       | 26.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2158      | 59.11%  |
| No        | 1493      | 40.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Netherlands | 3590      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Amsterdam              | 668       | 17.49%  |
| The Hague              | 183       | 4.79%   |
| Schagen                | 142       | 3.72%   |
| Rotterdam              | 123       | 3.22%   |
| Utrecht                | 92        | 2.41%   |
| Haarlem                | 78        | 2.04%   |
| Delft                  | 72        | 1.89%   |
| Groningen              | 63        | 1.65%   |
| Almere Stad            | 57        | 1.49%   |
| Eindhoven              | 55        | 1.44%   |
| Tilburg                | 45        | 1.18%   |
| Amersfoort             | 44        | 1.15%   |
| Naaldwijk              | 43        | 1.13%   |
| Leiden                 | 37        | 0.97%   |
| Enschede               | 35        | 0.92%   |
| Nijmegen               | 33        | 0.86%   |
| Zoetermeer             | 32        | 0.84%   |
| Arnhem                 | 30        | 0.79%   |
| Breda                  | 28        | 0.73%   |
| Almelo                 | 28        | 0.73%   |
| Hilversum              | 27        | 0.71%   |
| Apeldoorn              | 27        | 0.71%   |
| Amstelveen             | 24        | 0.63%   |
| Zwolle                 | 23        | 0.6%    |
| Zeist                  | 23        | 0.6%    |
| Capelle aan den IJssel | 23        | 0.6%    |
| Assen                  | 21        | 0.55%   |
| Maastricht             | 20        | 0.52%   |
| Lelystad               | 20        | 0.52%   |
| Dordrecht              | 20        | 0.52%   |
| 's-Hertogenbosch       | 20        | 0.52%   |
| Roosendaal             | 19        | 0.5%    |
| Alkmaar                | 18        | 0.47%   |
| Schiedam               | 17        | 0.45%   |
| Purmerend              | 16        | 0.42%   |
| Leeuwarden             | 16        | 0.42%   |
| Heerlen                | 16        | 0.42%   |
| Hoofddorp              | 15        | 0.39%   |
| Gouda                  | 15        | 0.39%   |
| Waalwijk               | 14        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1184      | 1909   | 22.94%  |
| WDC                         | 683       | 1048   | 13.23%  |
| Seagate                     | 639       | 1005   | 12.38%  |
| Kingston                    | 314       | 411    | 6.08%   |
| Toshiba                     | 285       | 391    | 5.52%   |
| SanDisk                     | 228       | 305    | 4.42%   |
| Crucial                     | 222       | 288    | 4.3%    |
| Unknown                     | 217       | 271    | 4.2%    |
| SK hynix                    | 181       | 212    | 3.51%   |
| Intel                       | 158       | 212    | 3.06%   |
| Hitachi                     | 156       | 200    | 3.02%   |
| HGST                        | 94        | 116    | 1.82%   |
| Micron Technology           | 65        | 77     | 1.26%   |
| A-DATA Technology           | 59        | 64     | 1.14%   |
| KIOXIA                      | 47        | 61     | 0.91%   |
| Apple                       | 46        | 63     | 0.89%   |
| LITEON                      | 40        | 50     | 0.77%   |
| Maxtor                      | 30        | 41     | 0.58%   |
| OCZ                         | 29        | 37     | 0.56%   |
| Corsair                     | 27        | 36     | 0.52%   |
| Phison                      | 26        | 38     | 0.5%    |
| China                       | 25        | 35     | 0.48%   |
| Transcend                   | 23        | 28     | 0.45%   |
| LITEONIT                    | 23        | 26     | 0.45%   |
| PNY                         | 21        | 25     | 0.41%   |
| Fujitsu                     | 20        | 22     | 0.39%   |
| SSSTC                       | 19        | 20     | 0.37%   |
| Kingston Technology Company | 15        | 16     | 0.29%   |
| ASMT                        | 15        | 17     | 0.29%   |
| Gigabyte Technology         | 14        | 19     | 0.27%   |
| KingFast                    | 13        | 17     | 0.25%   |
| Intenso                     | 13        | 13     | 0.25%   |
| SPCC                        | 12        | 13     | 0.23%   |
| Patriot                     | 12        | 15     | 0.23%   |
| Micron/Crucial Technology   | 12        | 16     | 0.23%   |
| GOODRAM                     | 12        | 13     | 0.23%   |
| JMicron Technology          | 9         | 16     | 0.17%   |
| Unknown                     | 9         | 12     | 0.17%   |
| XPG                         | 8         | 10     | 0.15%   |
| Silicon Motion              | 8         | 9      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 92        | 1.58%   |
| Samsung SSD 860 EVO 500GB                           | 63        | 1.08%   |
| Samsung SSD 850 EVO 500GB                           | 57        | 0.98%   |
| Samsung NVMe SSD Drive 500GB                        | 47        | 0.81%   |
| Samsung NVMe SSD Drive 1TB                          | 46        | 0.79%   |
| Kingston SA400S37240G 240GB SSD                     | 45        | 0.77%   |
| Unknown MMC Card  32GB                              | 41        | 0.71%   |
| Kingston SA400S37120G 120GB SSD                     | 40        | 0.69%   |
| Samsung SSD 840 EVO 250GB                           | 39        | 0.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 39        | 0.67%   |
| Seagate Expansion+ 2TB                              | 32        | 0.55%   |
| Samsung SSD 840 EVO 120GB                           | 31        | 0.53%   |
| Samsung SSD 860 EVO 1TB                             | 29        | 0.5%    |
| Kingston SV300S37A120G 120GB SSD                    | 29        | 0.5%    |
| Crucial CT500MX500SSD1 500GB                        | 29        | 0.5%    |
| Unknown MMC Card  64GB                              | 28        | 0.48%   |
| Samsung SSD 970 EVO 1TB                             | 28        | 0.48%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 28        | 0.48%   |
| Seagate ST500DM002-1BD142 500GB                     | 27        | 0.46%   |
| Seagate ST2000DM008-2FR102 2TB                      | 26        | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB                      | 26        | 0.45%   |
| HGST HTS721010A9E630 1TB                            | 26        | 0.45%   |
| Samsung NVMe SSD Drive 512GB                        | 25        | 0.43%   |
| Samsung SSD 980 1TB                                 | 23        | 0.4%    |
| Crucial CT1000MX500SSD1 1TB                         | 23        | 0.4%    |
| SK hynix BC711 NVMe 128GB                           | 22        | 0.38%   |
| Seagate ST9500325AS 500GB                           | 22        | 0.38%   |
| Samsung NVMe SSD Drive 1024GB                       | 22        | 0.38%   |
| Toshiba MQ01ABF050 500GB                            | 21        | 0.36%   |
| Toshiba DT01ACA100 1TB                              | 21        | 0.36%   |
| Crucial CT240BX500SSD1 240GB                        | 21        | 0.36%   |
| Seagate ST1000DM010-2EP102 1TB                      | 20        | 0.34%   |
| Samsung SSD 970 EVO Plus 1TB                        | 20        | 0.34%   |
| Samsung SSD 860 QVO 1TB                             | 20        | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 20        | 0.34%   |
| Toshiba MQ01ABD100 1TB                              | 19        | 0.33%   |
| SanDisk NVMe SSD Drive 512GB                        | 19        | 0.33%   |
| Samsung SSD 870 QVO 1TB                             | 19        | 0.33%   |
| Samsung SSD 860 EVO 250GB                           | 19        | 0.33%   |
| Samsung SSD 850 EVO 120GB                           | 17        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 631       | 989    | 33.83%  |
| WDC                 | 551       | 855    | 29.54%  |
| Toshiba             | 194       | 276    | 10.4%   |
| Hitachi             | 156       | 200    | 8.36%   |
| Samsung Electronics | 131       | 208    | 7.02%   |
| HGST                | 94        | 116    | 5.04%   |
| Maxtor              | 30        | 41     | 1.61%   |
| Fujitsu             | 20        | 22     | 1.07%   |
| ASMT                | 12        | 14     | 0.64%   |
| Apple               | 11        | 14     | 0.59%   |
| Unknown             | 8         | 15     | 0.43%   |
| JMicron Technology  | 3         | 5      | 0.16%   |
| Intenso             | 3         | 3      | 0.16%   |
| HGST HTS            | 3         | 4      | 0.16%   |
| SABRENT             | 2         | 2      | 0.11%   |
| KESU                | 2         | 2      | 0.11%   |
| IBM/Hitachi         | 2         | 2      | 0.11%   |
| ExcelStor           | 2         | 2      | 0.11%   |
| ASMedia             | 2         | 2      | 0.11%   |
| Synology            | 1         | 1      | 0.05%   |
| QNAP                | 1         | 1      | 0.05%   |
| NAS                 | 1         | 10     | 0.05%   |
| Maxtor 6            | 1         | 2      | 0.05%   |
| Magnetic Data       | 1         | 1      | 0.05%   |
| LIO-ORG             | 1         | 4      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 634       | 942    | 34.16%  |
| Kingston            | 238       | 297    | 12.82%  |
| Crucial             | 212       | 278    | 11.42%  |
| SanDisk             | 151       | 187    | 8.14%   |
| WDC                 | 73        | 101    | 3.93%   |
| Intel               | 66        | 83     | 3.56%   |
| A-DATA Technology   | 50        | 55     | 2.69%   |
| SK hynix            | 41        | 52     | 2.21%   |
| LITEON              | 33        | 43     | 1.78%   |
| Micron Technology   | 32        | 41     | 1.72%   |
| OCZ                 | 29        | 37     | 1.56%   |
| Toshiba             | 25        | 30     | 1.35%   |
| China               | 25        | 35     | 1.35%   |
| Apple               | 25        | 29     | 1.35%   |
| LITEONIT            | 23        | 26     | 1.24%   |
| PNY                 | 21        | 25     | 1.13%   |
| Corsair             | 20        | 28     | 1.08%   |
| Transcend           | 19        | 24     | 1.02%   |
| SPCC                | 12        | 13     | 0.65%   |
| Patriot             | 12        | 15     | 0.65%   |
| GOODRAM             | 12        | 13     | 0.65%   |
| Intenso             | 8         | 8      | 0.43%   |
| Mushkin             | 5         | 7      | 0.27%   |
| KingSpec            | 5         | 6      | 0.27%   |
| KingFast            | 5         | 6      | 0.27%   |
| Gigabyte Technology | 5         | 9      | 0.27%   |
| Netac               | 4         | 4      | 0.22%   |
| JMicron Technology  | 4         | 4      | 0.22%   |
| Apacer              | 4         | 4      | 0.22%   |
| ACASIS              | 4         | 4      | 0.22%   |
| Unknown             | 4         | 7      | 0.22%   |
| Unknown             | 3         | 3      | 0.16%   |
| SSSTC               | 3         | 3      | 0.16%   |
| Plextor             | 3         | 4      | 0.16%   |
| Leven               | 3         | 3      | 0.16%   |
| ASMT                | 3         | 3      | 0.16%   |
| Vaseky              | 2         | 2      | 0.11%   |
| Team                | 2         | 4      | 0.11%   |
| Seagate             | 2         | 2      | 0.11%   |
| Phison              | 2         | 4      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1630      | 2480   | 34.89%  |
| HDD     | 1542      | 2793   | 33.01%  |
| NVMe    | 1241      | 1774   | 26.56%  |
| MMC     | 207       | 250    | 4.43%   |
| Unknown | 52        | 66     | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2533      | 5023   | 60.57%  |
| NVMe | 1239      | 1765   | 29.63%  |
| MMC  | 207       | 250    | 4.95%   |
| SAS  | 203       | 325    | 4.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 2071      | 3231   | 62.15%  |
| 0.51-1.0        | 785       | 1179   | 23.56%  |
| 1.01-2.0        | 280       | 463    | 8.4%    |
| 3.01-4.0        | 74        | 153    | 2.22%   |
| 2.01-3.0        | 60        | 84     | 1.8%    |
| 4.01-10.0       | 58        | 147    | 1.74%   |
| More than 100.0 | 2         | 2      | 0.06%   |
| 20.01-50.0      | 1         | 1      | 0.03%   |
| 10.01-20.0      | 1         | 13     | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1019      | 26.82%  |
| 251-500        | 740       | 19.47%  |
| 501-1000       | 498       | 13.11%  |
| 1-20           | 397       | 10.45%  |
| 1001-2000      | 316       | 8.32%   |
| 51-100         | 248       | 6.53%   |
| More than 3000 | 211       | 5.55%   |
| 21-50          | 166       | 4.37%   |
| 2001-3000      | 110       | 2.89%   |
| Unknown        | 95        | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1596      | 40.68%  |
| 21-50          | 570       | 14.53%  |
| 101-250        | 459       | 11.7%   |
| 51-100         | 417       | 10.63%  |
| 251-500        | 283       | 7.21%   |
| 501-1000       | 244       | 6.22%   |
| 1001-2000      | 118       | 3.01%   |
| Unknown        | 95        | 2.42%   |
| More than 3000 | 90        | 2.29%   |
| 2001-3000      | 49        | 1.25%   |
| 0              | 2         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4         | 4      | 1.81%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 4         | 4      | 1.81%   |
| Kingston SV300S37A120G 120GB SSD      | 4         | 5      | 1.81%   |
| WDC WD10EADS-22M2B0 1TB               | 3         | 3      | 1.36%   |
| Toshiba MQ01ABF050 500GB              | 3         | 3      | 1.36%   |
| Seagate ST9250410AS 250GB             | 3         | 3      | 1.36%   |
| Intel SSDSC2BW120A4 120GB             | 3         | 4      | 1.36%   |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.36%   |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 1.36%   |
| Crucial CT128MX100SSD1 128GB          | 3         | 3      | 1.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 0.9%    |
| WDC WD60EFRX-68MYMN1 6TB              | 2         | 2      | 0.9%    |
| WDC WD1002FAEX-00Z3A0 1TB             | 2         | 2      | 0.9%    |
| Toshiba MQ01ABD050 500GB              | 2         | 3      | 0.9%    |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 0.9%    |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.9%    |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 0.9%    |
| Seagate ST380011A 80GB                | 2         | 2      | 0.9%    |
| Seagate ST3500418AS 500GB             | 2         | 2      | 0.9%    |
| Seagate ST31000524AS 1TB              | 2         | 2      | 0.9%    |
| Seagate ST2000DM001-1CH164 2TB        | 2         | 2      | 0.9%    |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 0.9%    |
| Samsung Electronics HM500JI 500GB     | 2         | 2      | 0.9%    |
| Samsung Electronics HD103UJ 1TB       | 2         | 2      | 0.9%    |
| Kingston SUV400S37240G 240GB SSD      | 2         | 2      | 0.9%    |
| Kingston SA400S37120G 120GB SSD       | 2         | 3      | 0.9%    |
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 0.9%    |
| Intel SSDSA2M080G2GC 80GB             | 2         | 3      | 0.9%    |
| Hitachi HTS545050A7E380 500GB         | 2         | 3      | 0.9%    |
| Crucial CT525MX300SSD1 528GB          | 2         | 2      | 0.9%    |
| WDC WD800JD-00HKA0 80GB               | 1         | 1      | 0.45%   |
| WDC WD7500BPVT-08HXZT3 752GB          | 1         | 1      | 0.45%   |
| WDC WD6400AACS-00G8B1 640GB           | 1         | 1      | 0.45%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1         | 1      | 0.45%   |
| WDC WD600UE-22HCT0 64GB               | 1         | 1      | 0.45%   |
| WDC WD5000HHTZ-04N21V0 500GB          | 1         | 1      | 0.45%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 1         | 1      | 0.45%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1         | 1      | 0.45%   |
| WDC WD5000AAKX-001CA0 500GB           | 1         | 1      | 0.45%   |
| WDC WD5000AAKS-75V0A0 500GB           | 1         | 1      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 49        | 60     | 22.48%  |
| Seagate                     | 41        | 56     | 18.81%  |
| Samsung Electronics         | 15        | 17     | 6.88%   |
| Kingston                    | 15        | 17     | 6.88%   |
| Intel                       | 14        | 19     | 6.42%   |
| Hitachi                     | 14        | 15     | 6.42%   |
| Crucial                     | 12        | 19     | 5.5%    |
| Toshiba                     | 10        | 11     | 4.59%   |
| HGST                        | 10        | 12     | 4.59%   |
| SanDisk                     | 8         | 8      | 3.67%   |
| SK hynix                    | 5         | 5      | 2.29%   |
| Micron Technology           | 3         | 3      | 1.38%   |
| Maxtor                      | 3         | 5      | 1.38%   |
| Fujitsu                     | 3         | 3      | 1.38%   |
| OCZ                         | 2         | 2      | 0.92%   |
| LITEON                      | 2         | 4      | 0.92%   |
| Corsair                     | 2         | 4      | 0.92%   |
| A-DATA Technology           | 2         | 2      | 0.92%   |
| Realtek                     | 1         | 1      | 0.46%   |
| Patriot                     | 1         | 1      | 0.46%   |
| LITEONIT                    | 1         | 1      | 0.46%   |
| Kingston Technology Company | 1         | 1      | 0.46%   |
| GOODRAM                     | 1         | 1      | 0.46%   |
| C-Series                    | 1         | 1      | 0.46%   |
| Apple                       | 1         | 1      | 0.46%   |
| Anobit                      | 1         | 1      | 0.46%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 47        | 58     | 34.81%  |
| Seagate             | 41        | 56     | 30.37%  |
| Hitachi             | 14        | 15     | 10.37%  |
| HGST                | 10        | 12     | 7.41%   |
| Toshiba             | 9         | 10     | 6.67%   |
| Samsung Electronics | 7         | 7      | 5.19%   |
| Maxtor              | 3         | 5      | 2.22%   |
| Fujitsu             | 3         | 3      | 2.22%   |
| Apple               | 1         | 1      | 0.74%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 126       | 167    | 60.29%  |
| SSD  | 74        | 89     | 35.41%  |
| NVMe | 9         | 14     | 4.31%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22ZCT0 250GB       | 1         | 1      | 14.29%  |
| Toshiba MK5065GSXN 500GB          | 1         | 1      | 14.29%  |
| Seagate ST2000DL001-9VT156 2TB    | 1         | 1      | 14.29%  |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 14.29%  |
| Samsung Electronics HD161HJ 160GB | 1         | 1      | 14.29%  |
| Crucial M4-CT256M4SSD3 256GB      | 1         | 1      | 14.29%  |
| Apple HDD HTS541010A9E662 1TB     | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |
| Apple               | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2318      | 4847   | 60.74%  |
| Works    | 1291      | 2239   | 33.83%  |
| Malfunc  | 200       | 270    | 5.24%   |
| Failed   | 7         | 7      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2361      | 52.77%  |
| AMD                              | 561       | 12.54%  |
| Samsung Electronics              | 554       | 12.38%  |
| SanDisk                          | 145       | 3.24%   |
| SK hynix                         | 138       | 3.08%   |
| Kingston Technology Company      | 91        | 2.03%   |
| Toshiba America Info Systems     | 77        | 1.72%   |
| ASMedia Technology               | 67        | 1.5%    |
| JMicron Technology               | 58        | 1.3%    |
| Nvidia                           | 57        | 1.27%   |
| Phison Electronics               | 48        | 1.07%   |
| Marvell Technology Group         | 48        | 1.07%   |
| KIOXIA                           | 47        | 1.05%   |
| Micron Technology                | 34        | 0.76%   |
| Micron/Crucial Technology        | 20        | 0.45%   |
| Solid State Storage Technology   | 17        | 0.38%   |
| VIA Technologies                 | 15        | 0.34%   |
| Silicon Motion                   | 14        | 0.31%   |
| ADATA Technology                 | 14        | 0.31%   |
| Silicon Integrated Systems [SiS] | 13        | 0.29%   |
| Broadcom / LSI                   | 11        | 0.25%   |
| Apple                            | 11        | 0.25%   |
| Lite-On Technology               | 10        | 0.22%   |
| Silicon Image                    | 8         | 0.18%   |
| Seagate Technology               | 8         | 0.18%   |
| Realtek Semiconductor            | 8         | 0.18%   |
| LSI Logic / Symbios Logic        | 8         | 0.18%   |
| Union Memory (Shenzhen)          | 6         | 0.13%   |
| Hewlett-Packard                  | 5         | 0.11%   |
| O2 Micro                         | 3         | 0.07%   |
| Integrated Technology Express    | 3         | 0.07%   |
| Adaptec                          | 3         | 0.07%   |
| ULi Electronics                  | 2         | 0.04%   |
| Promise Technology               | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| Transcend                        | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 362       | 6.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 285       | 5.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 168       | 3.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 164       | 3.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 156       | 3.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 145       | 2.8%    |
| Samsung NVMe SSD Controller 980                                                | 124       | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 107       | 2.06%   |
| AMD 400 Series Chipset SATA Controller                                         | 93        | 1.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 85        | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 84        | 1.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 72        | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 70        | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 69        | 1.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 67        | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 67        | 1.29%   |
| Intel SATA Controller [RAID mode]                                              | 65        | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 64        | 1.23%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 63        | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 62        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 59        | 1.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 58        | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 56        | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 56        | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                            | 54        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 54        | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 52        | 1%      |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 51        | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 51        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 51        | 0.98%   |
| Kingston Company A2000 NVMe SSD                                                | 50        | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                         | 50        | 0.96%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 49        | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 48        | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 45        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 45        | 0.87%   |
| Intel SSD 660P Series                                                          | 42        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 42        | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 40        | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                          | 40        | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2422      | 53.29%  |
| NVMe | 1251      | 27.52%  |
| IDE  | 539       | 11.86%  |
| RAID | 318       | 7%      |
| SAS  | 8         | 0.18%   |
| SCSI | 7         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2823      | 78.64%  |
| AMD          | 717       | 19.97%  |
| ARM          | 47        | 1.31%   |
| CentaurHauls | 2         | 0.06%   |
| QUALCOMM     | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 57        | 1.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 43        | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 39        | 1.08%   |
| ARM Processor                                 | 37        | 1.03%   |
| AMD Ryzen 5 3600 6-Core Processor             | 37        | 1.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 34        | 0.95%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 34        | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 34        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 31        | 0.86%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 29        | 0.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 29        | 0.81%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 28        | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 26        | 0.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 25        | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 24        | 0.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 23        | 0.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 23        | 0.64%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 23        | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.58%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 0.58%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 21        | 0.58%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 20        | 0.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 19        | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 19        | 0.53%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 19        | 0.53%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 18        | 0.5%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 18        | 0.5%    |
| Intel Core i5-4460 CPU @ 3.20GHz              | 18        | 0.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 18        | 0.5%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 18        | 0.5%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 18        | 0.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 0.5%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 17        | 0.47%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 17        | 0.47%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 16        | 0.44%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 16        | 0.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 15        | 0.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 0.42%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 15        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 787       | 21.89%  |
| Intel Core i7           | 728       | 20.25%  |
| Intel Core i3           | 278       | 7.73%   |
| Other                   | 218       | 6.06%   |
| AMD Ryzen 5             | 173       | 4.81%   |
| Intel Core 2 Duo        | 162       | 4.51%   |
| AMD Ryzen 7             | 160       | 4.45%   |
| Intel Celeron           | 121       | 3.37%   |
| Intel Pentium Silver    | 104       | 2.89%   |
| Intel Pentium           | 83        | 2.31%   |
| Intel Xeon              | 77        | 2.14%   |
| Intel Atom              | 76        | 2.11%   |
| Intel Pentium Dual-Core | 53        | 1.47%   |
| AMD Ryzen 9             | 46        | 1.28%   |
| Intel Core 2 Quad       | 42        | 1.17%   |
| AMD FX                  | 32        | 0.89%   |
| Intel Core i9           | 31        | 0.86%   |
| Intel Core 2            | 29        | 0.81%   |
| AMD A6                  | 25        | 0.7%    |
| Intel Pentium Dual      | 24        | 0.67%   |
| Intel Genuine           | 22        | 0.61%   |
| AMD Ryzen 7 PRO         | 21        | 0.58%   |
| AMD A8                  | 20        | 0.56%   |
| AMD Ryzen 5 PRO         | 19        | 0.53%   |
| AMD Athlon 64 X2        | 19        | 0.53%   |
| AMD Phenom II X4        | 16        | 0.45%   |
| AMD A4                  | 16        | 0.45%   |
| AMD Ryzen 3             | 15        | 0.42%   |
| AMD A10                 | 15        | 0.42%   |
| Intel Pentium D         | 13        | 0.36%   |
| Intel Pentium 4         | 13        | 0.36%   |
| AMD E                   | 13        | 0.36%   |
| AMD Athlon II X2        | 13        | 0.36%   |
| AMD E1                  | 10        | 0.28%   |
| ARM BCM                 | 9         | 0.25%   |
| AMD Athlon II X4        | 8         | 0.22%   |
| AMD Athlon              | 8         | 0.22%   |
| AMD Ryzen Threadripper  | 7         | 0.19%   |
| Intel Core m3           | 6         | 0.17%   |
| AMD E2                  | 6         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1434      | 39.87%  |
| 2       | 1352      | 37.59%  |
| 6       | 349       | 9.7%    |
| 8       | 247       | 6.87%   |
| 1       | 84        | 2.34%   |
| 12      | 57        | 1.58%   |
| 10      | 23        | 0.64%   |
| 16      | 17        | 0.47%   |
| 14      | 11        | 0.31%   |
| 3       | 9         | 0.25%   |
| 24      | 5         | 0.14%   |
| Unknown | 5         | 0.14%   |
| 64      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 32      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3557      | 99.08%  |
| 2       | 28        | 0.78%   |
| Unknown | 3         | 0.08%   |
| 4       | 1         | 0.03%   |
| 3       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2291      | 63.75%  |
| 1       | 1297      | 36.09%  |
| Unknown | 5         | 0.14%   |
| 16      | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3477      | 96.58%  |
| Unknown        | 91        | 2.53%   |
| 32-bit         | 29        | 0.81%   |
| 64-bit         | 3         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 869       | 23.38%  |
| 0x306a9    | 203       | 5.46%   |
| 0x206a7    | 191       | 5.14%   |
| 0x306c3    | 164       | 4.41%   |
| 0x1067a    | 137       | 3.69%   |
| 0x806ec    | 118       | 3.17%   |
| 0x906ea    | 106       | 2.85%   |
| 0x806c1    | 74        | 1.99%   |
| 0x406e3    | 73        | 1.96%   |
| 0x806ea    | 72        | 1.94%   |
| 0x506e3    | 72        | 1.94%   |
| 0x40651    | 69        | 1.86%   |
| 0x806e9    | 64        | 1.72%   |
| 0x20655    | 63        | 1.69%   |
| 0x906e9    | 60        | 1.61%   |
| 0x906c0    | 58        | 1.56%   |
| 0x6fd      | 56        | 1.51%   |
| 0x08701021 | 52        | 1.4%    |
| 0x306d4    | 46        | 1.24%   |
| 0x30678    | 40        | 1.08%   |
| 0x08600106 | 40        | 1.08%   |
| 0x706a8    | 39        | 1.05%   |
| 0x6fb      | 34        | 0.91%   |
| 0x010000c8 | 33        | 0.89%   |
| 0x0a50000c | 32        | 0.86%   |
| 0x08701013 | 31        | 0.83%   |
| 0x806eb    | 30        | 0.81%   |
| 0xa0652    | 28        | 0.75%   |
| 0x10676    | 28        | 0.75%   |
| 0x0800820d | 26        | 0.7%    |
| 0x906ed    | 24        | 0.65%   |
| 0x706e5    | 24        | 0.65%   |
| 0x706a1    | 24        | 0.65%   |
| 0x20652    | 24        | 0.65%   |
| 0x106e5    | 24        | 0.65%   |
| 0x406c4    | 23        | 0.62%   |
| 0x08108102 | 23        | 0.62%   |
| 0x506c9    | 22        | 0.59%   |
| 0x08108109 | 22        | 0.59%   |
| 0x6f6      | 21        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 629       | 17.5%   |
| Haswell          | 318       | 8.85%   |
| IvyBridge        | 259       | 7.2%    |
| SandyBridge      | 249       | 6.93%   |
| Penryn           | 200       | 5.56%   |
| Skylake          | 198       | 5.51%   |
| Zen 2            | 182       | 5.06%   |
| Core             | 145       | 4.03%   |
| Unknown          | 125       | 3.48%   |
| Westmere         | 124       | 3.45%   |
| Silvermont       | 111       | 3.09%   |
| Zen+             | 95        | 2.64%   |
| Zen 3            | 95        | 2.64%   |
| TigerLake        | 89        | 2.48%   |
| Broadwell        | 68        | 1.89%   |
| Goldmont plus    | 66        | 1.84%   |
| CometLake        | 65        | 1.81%   |
| K10              | 55        | 1.53%   |
| Piledriver       | 52        | 1.45%   |
| Nehalem          | 52        | 1.45%   |
| Tremont          | 51        | 1.42%   |
| Zen              | 50        | 1.39%   |
| IceLake          | 45        | 1.25%   |
| K8 Hammer        | 35        | 0.97%   |
| NetBurst         | 30        | 0.83%   |
| Alderlake Hybrid | 30        | 0.83%   |
| Goldmont         | 28        | 0.78%   |
| Excavator        | 22        | 0.61%   |
| Bobcat           | 21        | 0.58%   |
| Bonnell          | 19        | 0.53%   |
| K10 Llano        | 17        | 0.47%   |
| P6               | 16        | 0.45%   |
| Jaguar           | 16        | 0.45%   |
| Steamroller      | 12        | 0.33%   |
| Puma             | 10        | 0.28%   |
| K8 & K10 hybrid  | 8         | 0.22%   |
| Bulldozer        | 7         | 0.19%   |
| CannonLake       | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2114      | 50.57%  |
| Nvidia                           | 1167      | 27.92%  |
| AMD                              | 860       | 20.57%  |
| Matrox Electronics Systems       | 15        | 0.36%   |
| ASPEED Technology                | 9         | 0.22%   |
| VIA Technologies                 | 7         | 0.17%   |
| Silicon Integrated Systems [SiS] | 7         | 0.17%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 183       | 4.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 151       | 3.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 108       | 2.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 108       | 2.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 81        | 1.89%   |
| Intel UHD Graphics 620                                                                   | 80        | 1.87%   |
| AMD Renoir                                                                               | 77        | 1.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 74        | 1.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 74        | 1.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 68        | 1.59%   |
| Intel HD Graphics 620                                                                    | 68        | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 65        | 1.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 63        | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 61        | 1.42%   |
| Intel JasperLake [UHD Graphics]                                                          | 60        | 1.4%    |
| Intel HD Graphics 630                                                                    | 60        | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 59        | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 58        | 1.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 57        | 1.33%   |
| Intel HD Graphics 530                                                                    | 55        | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 51        | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 49        | 1.14%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 47        | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 43        | 1%      |
| Intel HD Graphics 5500                                                                   | 42        | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 40        | 0.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 39        | 0.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 33        | 0.77%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 32        | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 31        | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 31        | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 30        | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 29        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 29        | 0.68%   |
| Nvidia GT218 [GeForce 210]                                                               | 26        | 0.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 26        | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 25        | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 22        | 0.51%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 22        | 0.51%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 22        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1537      | 42.48%  |
| 1 x AMD                  | 710       | 19.62%  |
| 1 x Nvidia               | 659       | 18.21%  |
| Intel + Nvidia           | 457       | 12.63%  |
| Intel + AMD              | 70        | 1.93%   |
| Other                    | 53        | 1.46%   |
| 2 x AMD                  | 41        | 1.13%   |
| AMD + Nvidia             | 37        | 1.02%   |
| 1 x Matrox               | 12        | 0.33%   |
| 2 x Nvidia               | 9         | 0.25%   |
| 1 x VIA                  | 7         | 0.19%   |
| 1 x SiS                  | 7         | 0.19%   |
| 2 x Intel                | 5         | 0.14%   |
| Nvidia + ASPEED          | 4         | 0.11%   |
| 1 x ASPEED               | 4         | 0.11%   |
| Nvidia + Matrox          | 2         | 0.06%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.06%   |
| AMD + Matrox             | 1         | 0.03%   |
| AMD + ASPEED             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2865      | 78.39%  |
| Proprietary | 617       | 16.88%  |
| Unknown     | 173       | 4.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2126      | 57.52%  |
| 1.01-2.0   | 399       | 10.8%   |
| 0.01-0.5   | 372       | 10.06%  |
| 0.51-1.0   | 275       | 7.44%   |
| 3.01-4.0   | 242       | 6.55%   |
| 7.01-8.0   | 154       | 4.17%   |
| 5.01-6.0   | 74        | 2%      |
| 8.01-16.0  | 28        | 0.76%   |
| 2.01-3.0   | 25        | 0.68%   |
| 16.01-24.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 519       | 13.15%  |
| Samsung Electronics     | 496       | 12.57%  |
| LG Display              | 327       | 8.28%   |
| BOE                     | 299       | 7.58%   |
| Chimei Innolux          | 261       | 6.61%   |
| Dell                    | 222       | 5.62%   |
| Philips                 | 176       | 4.46%   |
| Iiyama                  | 176       | 4.46%   |
| Goldstar                | 167       | 4.23%   |
| Hewlett-Packard         | 139       | 3.52%   |
| Acer                    | 122       | 3.09%   |
| Apple                   | 95        | 2.41%   |
| Sharp                   | 90        | 2.28%   |
| BenQ                    | 80        | 2.03%   |
| AOC                     | 80        | 2.03%   |
| Chi Mei Optoelectronics | 57        | 1.44%   |
| Ancor Communications    | 53        | 1.34%   |
| Lenovo                  | 46        | 1.17%   |
| LG Philips              | 34        | 0.86%   |
| Sony                    | 31        | 0.79%   |
| Medion                  | 31        | 0.79%   |
| Idek Iiyama             | 29        | 0.73%   |
| InfoVision              | 24        | 0.61%   |
| LG Electronics          | 22        | 0.56%   |
| Eizo                    | 19        | 0.48%   |
| PANDA                   | 16        | 0.41%   |
| MSI                     | 15        | 0.38%   |
| CSO                     | 15        | 0.38%   |
| ASUSTek Computer        | 15        | 0.38%   |
| Unknown                 | 14        | 0.35%   |
| Panasonic               | 12        | 0.3%    |
| Fujitsu Siemens         | 12        | 0.3%    |
| ViewSonic               | 11        | 0.28%   |
| Valve                   | 11        | 0.28%   |
| Packard Bell            | 11        | 0.28%   |
| NEC Computers           | 10        | 0.25%   |
| Vestel Elektronik       | 9         | 0.23%   |
| Toshiba                 | 9         | 0.23%   |
| HannStar                | 9         | 0.23%   |
| LGD                     | 8         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                      | 33        | 0.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 25        | 0.61%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch            | 22        | 0.54%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch             | 18        | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 17        | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 15        | 0.37%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 14        | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 14        | 0.34%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 14        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 13        | 0.32%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                      | 13        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 12        | 0.29%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch             | 12        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 11        | 0.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 10        | 0.24%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 9         | 0.22%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 9         | 0.22%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 9         | 0.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 9         | 0.22%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 8         | 0.2%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                   | 8         | 0.2%    |
| LGD LCD Monitor 1920x1080                                                 | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 8         | 0.2%    |
| BOE LCD Monitor BOE097B 1366x768 256x144mm 11.6-inch                      | 8         | 0.2%    |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                     | 8         | 0.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 7         | 0.17%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 7         | 0.17%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 7         | 0.17%   |
| Iiyama PLT1931 IVM483F 1280x1024 376x301mm 19.0-inch                      | 7         | 0.17%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                      | 7         | 0.17%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 7         | 0.17%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 7         | 0.17%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 7         | 0.17%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 7         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1600      | 41.98%  |
| 1366x768 (WXGA)    | 545       | 14.3%   |
| 3840x2160 (4K)     | 239       | 6.27%   |
| 2560x1440 (QHD)    | 216       | 5.67%   |
| 1600x900 (HD+)     | 167       | 4.38%   |
| 1280x1024 (SXGA)   | 141       | 3.7%    |
| 1680x1050 (WSXGA+) | 138       | 3.62%   |
| 1280x800 (WXGA)    | 106       | 2.78%   |
| 1920x1200 (WUXGA)  | 101       | 2.65%   |
| 1440x900 (WXGA+)   | 96        | 2.52%   |
| 3440x1440          | 60        | 1.57%   |
| Unknown            | 55        | 1.44%   |
| 2560x1080          | 43        | 1.13%   |
| 2560x1600          | 31        | 0.81%   |
| 1360x768           | 31        | 0.81%   |
| 3840x2400          | 25        | 0.66%   |
| 2880x1800          | 25        | 0.66%   |
| 3840x1080          | 19        | 0.5%    |
| 1024x768 (XGA)     | 18        | 0.47%   |
| 1920x540           | 13        | 0.34%   |
| 800x1280           | 11        | 0.29%   |
| 1280x720 (HD)      | 9         | 0.24%   |
| 2736x1824          | 8         | 0.21%   |
| 1600x1200          | 8         | 0.21%   |
| 2160x1440          | 7         | 0.18%   |
| 3200x1800 (QHD+)   | 6         | 0.16%   |
| 3600x1080          | 5         | 0.13%   |
| 3000x2000          | 5         | 0.13%   |
| 1400x1050          | 5         | 0.13%   |
| 7680x2160          | 4         | 0.1%    |
| 5760x1080          | 4         | 0.1%    |
| 3840x1600          | 4         | 0.1%    |
| 3840x1200          | 4         | 0.1%    |
| 3456x2160          | 4         | 0.1%    |
| 2256x1504          | 4         | 0.1%    |
| 2048x1152          | 4         | 0.1%    |
| 1280x960           | 4         | 0.1%    |
| 1024x600           | 4         | 0.1%    |
| 3072x1920          | 3         | 0.08%   |
| 1680x945           | 3         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 877       | 22.21%  |
| 13      | 332       | 8.41%   |
| 17      | 318       | 8.05%   |
| 24      | 282       | 7.14%   |
| 27      | 276       | 6.99%   |
| 23      | 243       | 6.16%   |
| Unknown | 237       | 6%      |
| 14      | 234       | 5.93%   |
| 21      | 187       | 4.74%   |
| 11      | 139       | 3.52%   |
| 19      | 110       | 2.79%   |
| 22      | 87        | 2.2%    |
| 12      | 85        | 2.15%   |
| 34      | 81        | 2.05%   |
| 31      | 66        | 1.67%   |
| 20      | 55        | 1.39%   |
| 18      | 41        | 1.04%   |
| 25      | 32        | 0.81%   |
| 84      | 30        | 0.76%   |
| 16      | 24        | 0.61%   |
| 40      | 23        | 0.58%   |
| 72      | 22        | 0.56%   |
| 10      | 14        | 0.35%   |
| 65      | 13        | 0.33%   |
| 54      | 12        | 0.3%    |
| 28      | 11        | 0.28%   |
| 32      | 10        | 0.25%   |
| 26      | 10        | 0.25%   |
| 33      | 8         | 0.2%    |
| 29      | 8         | 0.2%    |
| 7       | 8         | 0.2%    |
| 46      | 6         | 0.15%   |
| 37      | 6         | 0.15%   |
| 36      | 6         | 0.15%   |
| 35      | 6         | 0.15%   |
| 58      | 5         | 0.13%   |
| 57      | 4         | 0.1%    |
| 52      | 4         | 0.1%    |
| 47      | 4         | 0.1%    |
| 43      | 4         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1274      | 32.84%  |
| 501-600     | 768       | 19.8%   |
| 201-300     | 460       | 11.86%  |
| 401-500     | 394       | 10.16%  |
| 351-400     | 360       | 9.28%   |
| Unknown     | 237       | 6.11%   |
| 601-700     | 110       | 2.84%   |
| 701-800     | 101       | 2.6%    |
| 1001-1500   | 58        | 1.5%    |
| 1501-2000   | 54        | 1.39%   |
| 801-900     | 42        | 1.08%   |
| 901-1000    | 11        | 0.28%   |
| 1-100       | 8         | 0.21%   |
| 101-200     | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2520      | 70.35%  |
| 16/10   | 525       | 14.66%  |
| Unknown | 195       | 5.44%   |
| 5/4     | 133       | 3.71%   |
| 21/9    | 99        | 2.76%   |
| 4/3     | 41        | 1.14%   |
| 3/2     | 40        | 1.12%   |
| 0.67    | 8         | 0.22%   |
| 6/5     | 6         | 0.17%   |
| 32/9    | 6         | 0.17%   |
| 0.62    | 5         | 0.14%   |
| 3.40    | 1         | 0.03%   |
| 0.80    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |
| 0.45    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 870       | 22.21%  |
| 201-250        | 628       | 16.03%  |
| 81-90          | 379       | 9.68%   |
| 301-350        | 285       | 7.28%   |
| Unknown        | 237       | 6.05%   |
| 151-200        | 227       | 5.8%    |
| 121-130        | 206       | 5.26%   |
| 71-80          | 195       | 4.98%   |
| 351-500        | 188       | 4.8%    |
| 51-60          | 141       | 3.6%    |
| 251-300        | 135       | 3.45%   |
| More than 1000 | 99        | 2.53%   |
| 141-150        | 92        | 2.35%   |
| 61-70          | 73        | 1.86%   |
| 501-1000       | 63        | 1.61%   |
| 131-140        | 44        | 1.12%   |
| 111-120        | 28        | 0.71%   |
| 41-50          | 13        | 0.33%   |
| 1-40           | 10        | 0.26%   |
| 91-100         | 4         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1219      | 31.94%  |
| 121-160       | 1064      | 27.88%  |
| 101-120       | 830       | 21.75%  |
| 161-240       | 240       | 6.29%   |
| Unknown       | 237       | 6.21%   |
| More than 240 | 138       | 3.62%   |
| 1-50          | 88        | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2855      | 77.52%  |
| 2     | 593       | 16.1%   |
| 0     | 168       | 4.56%   |
| 3     | 62        | 1.68%   |
| 4     | 4         | 0.11%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1900      | 35.94%  |
| Realtek Semiconductor                 | 1733      | 32.78%  |
| Qualcomm Atheros                      | 523       | 9.89%   |
| Broadcom                              | 332       | 6.28%   |
| Broadcom Limited                      | 79        | 1.49%   |
| Marvell Technology Group              | 71        | 1.34%   |
| TP-Link                               | 65        | 1.23%   |
| Ralink Technology                     | 62        | 1.17%   |
| Ralink                                | 57        | 1.08%   |
| Nvidia                                | 45        | 0.85%   |
| MediaTek                              | 39        | 0.74%   |
| ASIX Electronics                      | 32        | 0.61%   |
| Dell                                  | 27        | 0.51%   |
| DisplayLink                           | 26        | 0.49%   |
| Hewlett-Packard                       | 24        | 0.45%   |
| Sitecom Europe                        | 15        | 0.28%   |
| Microsoft                             | 15        | 0.28%   |
| Huawei Technologies                   | 13        | 0.25%   |
| NetGear                               | 12        | 0.23%   |
| JMicron Technology                    | 12        | 0.23%   |
| Ericsson Business Mobile Networks     | 12        | 0.23%   |
| Sierra Wireless                       | 11        | 0.21%   |
| Samsung Electronics                   | 11        | 0.21%   |
| IMC Networks                          | 11        | 0.21%   |
| ASUSTek Computer                      | 11        | 0.21%   |
| Silicon Integrated Systems [SiS]      | 9         | 0.17%   |
| Qualcomm                              | 8         | 0.15%   |
| Lenovo                                | 8         | 0.15%   |
| VIA Technologies                      | 6         | 0.11%   |
| Gemtek                                | 6         | 0.11%   |
| Aquantia                              | 6         | 0.11%   |
| Mellanox Technologies                 | 5         | 0.09%   |
| D-Link                                | 5         | 0.09%   |
| Xiaomi                                | 4         | 0.08%   |
| U-Blox                                | 4         | 0.08%   |
| Microchip Technology                  | 4         | 0.08%   |
| Fibocom                               | 4         | 0.08%   |
| Edimax Technology                     | 4         | 0.08%   |
| Belkin Components                     | 4         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1253      | 20.31%  |
| Intel Wi-Fi 6 AX200                                               | 189       | 3.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 152       | 2.46%   |
| Intel Wireless 8265 / 8275                                        | 151       | 2.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 149       | 2.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 123       | 1.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 105       | 1.7%    |
| Intel Wireless 7265                                               | 88        | 1.43%   |
| Intel I211 Gigabit Network Connection                             | 87        | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 72        | 1.17%   |
| Intel Wi-Fi 6 AX201                                               | 70        | 1.13%   |
| Intel Wireless 7260                                               | 67        | 1.09%   |
| Intel Ethernet Connection (2) I219-V                              | 62        | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 60        | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 59        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 59        | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 58        | 0.94%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 57        | 0.92%   |
| Intel Wireless 8260                                               | 56        | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 53        | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 48        | 0.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 48        | 0.78%   |
| Intel Wireless 3165                                               | 45        | 0.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 44        | 0.71%   |
| Intel Wireless-AC 9260                                            | 43        | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 42        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 42        | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 41        | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 41        | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 38        | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 38        | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 35        | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 35        | 0.57%   |
| Intel Centrino Ultimate-N 6300                                    | 35        | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.5%    |
| Intel 82577LM Gigabit Network Connection                          | 31        | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 30        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 0.49%   |
| Intel Ethernet Connection I219-LM                                 | 30        | 0.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 30        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1452      | 51.91%  |
| Qualcomm Atheros                      | 414       | 14.8%   |
| Realtek Semiconductor                 | 327       | 11.69%  |
| Broadcom                              | 203       | 7.26%   |
| Ralink Technology                     | 62        | 2.22%   |
| TP-Link                               | 58        | 2.07%   |
| Ralink                                | 57        | 2.04%   |
| Broadcom Limited                      | 39        | 1.39%   |
| MediaTek                              | 37        | 1.32%   |
| Sitecom Europe                        | 15        | 0.54%   |
| Microsoft                             | 13        | 0.46%   |
| NetGear                               | 12        | 0.43%   |
| Marvell Technology Group              | 12        | 0.43%   |
| Sierra Wireless                       | 11        | 0.39%   |
| IMC Networks                          | 11        | 0.39%   |
| Dell                                  | 11        | 0.39%   |
| ASUSTek Computer                      | 11        | 0.39%   |
| Gemtek                                | 6         | 0.21%   |
| Qualcomm                              | 5         | 0.18%   |
| D-Link                                | 5         | 0.18%   |
| Hewlett-Packard                       | 4         | 0.14%   |
| Fibocom                               | 4         | 0.14%   |
| Edimax Technology                     | 4         | 0.14%   |
| Belkin Components                     | 4         | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.14%   |
| Qualcomm Atheros Communications       | 3         | 0.11%   |
| Linksys                               | 3         | 0.11%   |
| Senao                                 | 2         | 0.07%   |
| Sagem                                 | 2         | 0.07%   |
| Wilocity                              | 1         | 0.04%   |
| Tenda                                 | 1         | 0.04%   |
| Samsung Electronics                   | 1         | 0.04%   |
| CyberTAN Technology                   | 1         | 0.04%   |
| Cinterion                             | 1         | 0.04%   |
| BUFFALO                               | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 189       | 6.73%   |
| Intel Wireless 8265 / 8275                                              | 151       | 5.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 105       | 3.74%   |
| Intel Wireless 7265                                                     | 88        | 3.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 72        | 2.56%   |
| Intel Wi-Fi 6 AX201                                                     | 70        | 2.49%   |
| Intel Wireless 7260                                                     | 67        | 2.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 60        | 2.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 59        | 2.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 58        | 2.06%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 57        | 2.03%   |
| Intel Wireless 8260                                                     | 56        | 1.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 53        | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 48        | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 48        | 1.71%   |
| Intel Wireless 3165                                                     | 45        | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 44        | 1.57%   |
| Intel Wireless-AC 9260                                                  | 43        | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 42        | 1.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 42        | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 41        | 1.46%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 38        | 1.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 35        | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 35        | 1.25%   |
| Intel Centrino Ultimate-N 6300                                          | 35        | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 30        | 1.07%   |
| Intel Wireless 3160                                                     | 29        | 1.03%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 29        | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 28        | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                          | 28        | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 27        | 0.96%   |
| Intel Centrino Advanced-N 6200                                          | 27        | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 25        | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 0.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 22        | 0.78%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 22        | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 20        | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 20        | 0.71%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 20        | 0.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 19        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1602      | 50.11%  |
| Intel                                  | 926       | 28.96%  |
| Broadcom                               | 178       | 5.57%   |
| Qualcomm Atheros                       | 172       | 5.38%   |
| Marvell Technology Group               | 59        | 1.85%   |
| Nvidia                                 | 44        | 1.38%   |
| Broadcom Limited                       | 40        | 1.25%   |
| ASIX Electronics                       | 32        | 1%      |
| DisplayLink                            | 26        | 0.81%   |
| JMicron Technology                     | 12        | 0.38%   |
| Samsung Electronics                    | 10        | 0.31%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.28%   |
| Huawei Technologies                    | 9         | 0.28%   |
| Lenovo                                 | 8         | 0.25%   |
| TP-Link                                | 7         | 0.22%   |
| VIA Technologies                       | 6         | 0.19%   |
| Hewlett-Packard                        | 6         | 0.19%   |
| Aquantia                               | 6         | 0.19%   |
| Xiaomi                                 | 4         | 0.13%   |
| Mellanox Technologies                  | 4         | 0.13%   |
| Standard Microsystems                  | 3         | 0.09%   |
| Qualcomm                               | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.06%   |
| ULi Electronics                        | 2         | 0.06%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.06%   |
| Motorola PCS                           | 2         | 0.06%   |
| MosChip Semiconductor                  | 2         | 0.06%   |
| Microsoft                              | 2         | 0.06%   |
| Microchip Technology                   | 2         | 0.06%   |
| ICS Advent                             | 2         | 0.06%   |
| Accton Technology                      | 2         | 0.06%   |
| 3Com                                   | 2         | 0.06%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QLogic                                 | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| MediaTek                               | 1         | 0.03%   |
| Jolla Oy                               | 1         | 0.03%   |
| Google                                 | 1         | 0.03%   |
| Emulex                                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1253      | 38.24%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 152       | 4.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 149       | 4.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 123       | 3.75%   |
| Intel I211 Gigabit Network Connection                             | 87        | 2.65%   |
| Intel Ethernet Connection (2) I219-V                              | 62        | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 59        | 1.8%    |
| Intel Ethernet Connection I217-LM                                 | 41        | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 38        | 1.16%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 31        | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 30        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 0.92%   |
| Intel Ethernet Connection I219-LM                                 | 30        | 0.92%   |
| Intel Ethernet Connection I217-V                                  | 27        | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 27        | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 27        | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.79%   |
| Intel Ethernet Controller I225-V                                  | 25        | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 25        | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 0.73%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 23        | 0.7%    |
| Intel Ethernet Connection (7) I219-V                              | 22        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 0.64%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.55%   |
| Intel I210 Gigabit Network Connection                             | 17        | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 17        | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 16        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 16        | 0.49%   |
| Intel 82574L Gigabit Network Connection                           | 16        | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.46%   |
| Intel Ethernet Connection (2) I218-V                              | 14        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13        | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 13        | 0.4%    |
| Intel Ethernet Connection (6) I219-LM                             | 13        | 0.4%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 13        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3017      | 52.51%  |
| WiFi     | 2650      | 46.12%  |
| Modem    | 71        | 1.24%   |
| Unknown  | 8         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2027      | 53.8%   |
| Ethernet | 1740      | 46.18%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1879      | 52.18%  |
| 1     | 1535      | 42.63%  |
| 0     | 94        | 2.61%   |
| 3     | 65        | 1.81%   |
| 4     | 17        | 0.47%   |
| 5     | 4         | 0.11%   |
| 7     | 3         | 0.08%   |
| 6     | 3         | 0.08%   |
| 8     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2966      | 80.62%  |
| Yes  | 713       | 19.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1158      | 53.09%  |
| Cambridge Silicon Radio         | 181       | 8.3%    |
| Realtek Semiconductor           | 142       | 6.51%   |
| Qualcomm Atheros Communications | 121       | 5.55%   |
| Broadcom                        | 98        | 4.49%   |
| Apple                           | 97        | 4.45%   |
| IMC Networks                    | 76        | 3.48%   |
| Lite-On Technology              | 61        | 2.8%    |
| Foxconn / Hon Hai               | 51        | 2.34%   |
| Hewlett-Packard                 | 42        | 1.93%   |
| ASUSTek Computer                | 38        | 1.74%   |
| Dell                            | 36        | 1.65%   |
| Toshiba                         | 19        | 0.87%   |
| Marvell Semiconductor           | 12        | 0.55%   |
| Ralink                          | 10        | 0.46%   |
| MediaTek                        | 10        | 0.46%   |
| Realtek                         | 5         | 0.23%   |
| TP-Link                         | 4         | 0.18%   |
| Alps Electric                   | 4         | 0.18%   |
| Ralink Technology               | 3         | 0.14%   |
| Sitecom Europe                  | 2         | 0.09%   |
| Micro Star International        | 2         | 0.09%   |
| Integrated System Solution      | 2         | 0.09%   |
| Foxconn International           | 2         | 0.09%   |
| USI                             | 1         | 0.05%   |
| Roper                           | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 415       | 19.01%  |
| Intel AX201 Bluetooth                               | 213       | 9.76%   |
| Intel AX200 Bluetooth                               | 182       | 8.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 181       | 8.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 172       | 7.88%   |
| Realtek Bluetooth Radio                             | 81        | 3.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 43        | 1.97%   |
| Qualcomm Atheros  Bluetooth Device                  | 43        | 1.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 42        | 1.92%   |
| Apple Bluetooth Host Controller                     | 42        | 1.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 41        | 1.88%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 30        | 1.37%   |
| IMC Networks Bluetooth Radio                        | 30        | 1.37%   |
| Lite-On Bluetooth Device                            | 27        | 1.24%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 25        | 1.15%   |
| Intel Bluetooth Device                              | 25        | 1.15%   |
| Intel AX210 Bluetooth                               | 25        | 1.15%   |
| Foxconn / Hon Hai Bluetooth Device                  | 24        | 1.1%    |
| Apple Bluetooth USB Host Controller                 | 24        | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 22        | 1.01%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.96%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 0.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 20        | 0.92%   |
| Dell DW375 Bluetooth Module                         | 19        | 0.87%   |
| IMC Networks Bluetooth Device                       | 18        | 0.82%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 0.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 14        | 0.64%   |
| Broadcom HP Portable SoftSailing                    | 14        | 0.64%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 14        | 0.64%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.6%    |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.55%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.55%   |
| IMC Networks Wireless_Device                        | 11        | 0.5%    |
| Apple Bluetooth HCI                                 | 11        | 0.5%    |
| Ralink RT3290 Bluetooth                             | 10        | 0.46%   |
| Marvell Bluetooth and Wireless LAN Composite        | 10        | 0.46%   |
| MediaTek Wireless_Device                            | 9         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2649      | 53.83%  |
| AMD                              | 915       | 18.59%  |
| Nvidia                           | 826       | 16.79%  |
| C-Media Electronics              | 69        | 1.4%    |
| Logitech                         | 41        | 0.83%   |
| Realtek Semiconductor            | 34        | 0.69%   |
| Creative Labs                    | 32        | 0.65%   |
| GN Netcom                        | 25        | 0.51%   |
| Texas Instruments                | 23        | 0.47%   |
| Focusrite-Novation               | 17        | 0.35%   |
| Creative Technology              | 14        | 0.28%   |
| Silicon Integrated Systems [SiS] | 12        | 0.24%   |
| Plantronics                      | 12        | 0.24%   |
| SteelSeries ApS                  | 11        | 0.22%   |
| JMTek                            | 11        | 0.22%   |
| BEHRINGER International          | 11        | 0.22%   |
| VIA Technologies                 | 10        | 0.2%    |
| Kingston Technology              | 10        | 0.2%    |
| Corsair                          | 10        | 0.2%    |
| Hewlett-Packard                  | 9         | 0.18%   |
| Apple                            | 8         | 0.16%   |
| Sony                             | 7         | 0.14%   |
| GYROCOM C&C                      | 7         | 0.14%   |
| ASUSTek Computer                 | 7         | 0.14%   |
| Sennheiser Communications        | 6         | 0.12%   |
| RODE Microphones                 | 6         | 0.12%   |
| Razer USA                        | 6         | 0.12%   |
| Lenovo                           | 6         | 0.12%   |
| Generalplus Technology           | 6         | 0.12%   |
| Yamaha                           | 5         | 0.1%    |
| XMOS                             | 4         | 0.08%   |
| SAVITECH                         | 4         | 0.08%   |
| Native Instruments               | 4         | 0.08%   |
| Cambridge Silicon Radio          | 4         | 0.08%   |
| Valve Software                   | 3         | 0.06%   |
| Tenx Technology                  | 3         | 0.06%   |
| Samson Technologies              | 3         | 0.06%   |
| No brand                         | 3         | 0.06%   |
| Micro Star International         | 3         | 0.06%   |
| M-Audio                          | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 258       | 4.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 258       | 4.51%   |
| AMD Family 17h/19h HD Audio Controller                                     | 227       | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 226       | 3.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 188       | 3.28%   |
| Intel Cannon Lake PCH cAVS                                                 | 156       | 2.72%   |
| AMD Starship/Matisse HD Audio Controller                                   | 143       | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 136       | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 131       | 2.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 125       | 2.18%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 125       | 2.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 118       | 2.06%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 108       | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 100       | 1.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 94        | 1.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 89        | 1.55%   |
| AMD FCH Azalia Controller                                                  | 85        | 1.48%   |
| Nvidia GP107GL High Definition Audio Controller                            | 81        | 1.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 76        | 1.33%   |
| Intel 8 Series HD Audio Controller                                         | 76        | 1.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 72        | 1.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 68        | 1.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 67        | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 66        | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 65        | 1.14%   |
| Nvidia High Definition Audio Controller                                    | 64        | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 64        | 1.12%   |
| Intel Comet Lake PCH-LP cAVS                                               | 62        | 1.08%   |
| Intel Broadwell-U Audio Controller                                         | 61        | 1.07%   |
| Intel Jasper Lake HD Audio                                                 | 60        | 1.05%   |
| Intel 200 Series PCH HD Audio                                              | 59        | 1.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 58        | 1.01%   |
| Nvidia TU106 High Definition Audio Controller                              | 52        | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 52        | 0.91%   |
| Intel CM238 HD Audio Controller                                            | 51        | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 50        | 0.87%   |
| Intel Comet Lake PCH cAVS                                                  | 49        | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                              | 47        | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 45        | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                         | 44        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 449       | 22.43%  |
| Samsung Electronics | 394       | 19.68%  |
| Kingston            | 221       | 11.04%  |
| Micron Technology   | 213       | 10.64%  |
| Corsair             | 167       | 8.34%   |
| Unknown             | 153       | 7.64%   |
| Crucial             | 127       | 6.34%   |
| G.Skill             | 58        | 2.9%    |
| A-DATA Technology   | 32        | 1.6%    |
| Nanya Technology    | 29        | 1.45%   |
| Ramaxel Technology  | 27        | 1.35%   |
| Elpida              | 20        | 1%      |
| Unknown             | 12        | 0.6%    |
| Transcend           | 11        | 0.55%   |
| Unknown (ABCD)      | 8         | 0.4%    |
| Team                | 7         | 0.35%   |
| Qimonda             | 5         | 0.25%   |
| GOODRAM             | 5         | 0.25%   |
| ASint Technology    | 5         | 0.25%   |
| Patriot             | 4         | 0.2%    |
| 48spaces            | 4         | 0.2%    |
| Wilk                | 3         | 0.15%   |
| GeIL                | 3         | 0.15%   |
| Axiom               | 3         | 0.15%   |
| Toshiba             | 2         | 0.1%    |
| TakeMS              | 2         | 0.1%    |
| Goldkey             | 2         | 0.1%    |
| Atermiter           | 2         | 0.1%    |
| AMD                 | 2         | 0.1%    |
| A-DA                | 2         | 0.1%    |
| A Force             | 2         | 0.1%    |
| ZIFEI               | 1         | 0.05%   |
| zApacer             | 1         | 0.05%   |
| Unknown (AD8A)      | 1         | 0.05%   |
| Unknown (0x873E)    | 1         | 0.05%   |
| Unknown (08C8)      | 1         | 0.05%   |
| Timetec             | 1         | 0.05%   |
| Smart               | 1         | 0.05%   |
| SHARETRONIC         | 1         | 0.05%   |
| Sesame              | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 43        | 2.02%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 30        | 1.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 24        | 1.13%   |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 19        | 0.89%   |
| SK hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s         | 17        | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 16        | 0.75%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 15        | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 13        | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 13        | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s           | 13        | 0.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 12        | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 12        | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 12        | 0.56%   |
| Unknown                                                        | 12        | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 11        | 0.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 11        | 0.52%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 11        | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 11        | 0.52%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 10        | 0.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 10        | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 10        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 9         | 0.42%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 9         | 0.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 9         | 0.42%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 8         | 0.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 8         | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 8         | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 8         | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 8         | 0.38%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s           | 8         | 0.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 8         | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 8         | 0.38%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s          | 8         | 0.38%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s            | 7         | 0.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 7         | 0.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 7         | 0.33%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 7         | 0.33%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s         | 7         | 0.33%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s          | 7         | 0.33%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                    | 6         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 856       | 48.5%   |
| DDR3    | 542       | 30.71%  |
| LPDDR4  | 114       | 6.46%   |
| DDR2    | 73        | 4.14%   |
| LPDDR3  | 60        | 3.4%    |
| SDRAM   | 51        | 2.89%   |
| Unknown | 28        | 1.59%   |
| DDR5    | 16        | 0.91%   |
| DDR     | 12        | 0.68%   |
| LPDDR5  | 9         | 0.51%   |
| DRAM    | 3         | 0.17%   |
| EEPROM  | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1016      | 57.69%  |
| DIMM         | 539       | 30.61%  |
| Row Of Chips | 187       | 10.62%  |
| Unknown      | 9         | 0.51%   |
| Chip         | 8         | 0.45%   |
| RIMM         | 1         | 0.06%   |
| FB-DIMM      | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 747       | 39.15%  |
| 4096  | 501       | 26.26%  |
| 16384 | 286       | 14.99%  |
| 2048  | 237       | 12.42%  |
| 1024  | 71        | 3.72%   |
| 32768 | 54        | 2.83%   |
| 512   | 9         | 0.47%   |
| 256   | 1         | 0.05%   |
| 64    | 1         | 0.05%   |
| 1     | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 328       | 17.45%  |
| 2667    | 281       | 14.95%  |
| 3200    | 267       | 14.2%   |
| 2400    | 147       | 7.82%   |
| 1333    | 122       | 6.49%   |
| 2133    | 102       | 5.43%   |
| 4267    | 86        | 4.57%   |
| 1334    | 59        | 3.14%   |
| 3600    | 56        | 2.98%   |
| 1867    | 49        | 2.61%   |
| 800     | 43        | 2.29%   |
| 667     | 41        | 2.18%   |
| Unknown | 30        | 1.6%    |
| 1066    | 20        | 1.06%   |
| 3000    | 15        | 0.8%    |
| 3466    | 14        | 0.74%   |
| 3400    | 14        | 0.74%   |
| 2933    | 14        | 0.74%   |
| 4800    | 13        | 0.69%   |
| 1067    | 13        | 0.69%   |
| 3266    | 12        | 0.64%   |
| 1866    | 12        | 0.64%   |
| 8400    | 11        | 0.59%   |
| 2048    | 10        | 0.53%   |
| 6400    | 9         | 0.48%   |
| 3866    | 9         | 0.48%   |
| 4199    | 8         | 0.43%   |
| 3800    | 8         | 0.43%   |
| 400     | 8         | 0.43%   |
| 1639    | 7         | 0.37%   |
| 4266    | 6         | 0.32%   |
| 3733    | 5         | 0.27%   |
| 2800    | 5         | 0.27%   |
| 2666    | 5         | 0.27%   |
| 533     | 5         | 0.27%   |
| 1800    | 4         | 0.21%   |
| 49926   | 3         | 0.16%   |
| 6000    | 3         | 0.16%   |
| 3333    | 3         | 0.16%   |
| 333     | 3         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 28.92%  |
| Brother Industries  | 16        | 19.28%  |
| Canon               | 15        | 18.07%  |
| Samsung Electronics | 9         | 10.84%  |
| Dymo-CoStar         | 7         | 8.43%   |
| Seiko Epson         | 5         | 6.02%   |
| Citizen             | 4         | 4.82%   |
| Zebra               | 1         | 1.2%    |
| STMicroelectronics  | 1         | 1.2%    |
| Prolific Technology | 1         | 1.2%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Dymo-CoStar LabelWriter 450                               | 4         | 4.82%   |
| Citizen Thermal Receipt Printer [CT-E351]                 | 4         | 4.82%   |
| HP DeskJet 2600 series                                    | 3         | 3.61%   |
| HP Deskjet 2540 series                                    | 3         | 3.61%   |
| Samsung SCX-4600 Series                                   | 2         | 2.41%   |
| Samsung ML-1640 Series Laser Printer                      | 2         | 2.41%   |
| HP ENVY 5000 series                                       | 2         | 2.41%   |
| Canon TS3100 series                                       | 2         | 2.41%   |
| Canon PIXMA MX920 Series                                  | 2         | 2.41%   |
| Canon PIXMA MG2500 Series                                 | 2         | 2.41%   |
| Canon MG5600 series                                       | 2         | 2.41%   |
| Brother Printer                                           | 2         | 2.41%   |
| Brother HL-2030 Laser Printer                             | 2         | 2.41%   |
| Zebra Printer                                             | 1         | 1.2%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.2%    |
| Seiko Epson XP-200 Series                                 | 1         | 1.2%    |
| Seiko Epson Thermal Receipt Printer [TM-T20]              | 1         | 1.2%    |
| Seiko Epson Printer                                       | 1         | 1.2%    |
| Seiko Epson ET-2820 Series                                | 1         | 1.2%    |
| Seiko Epson ET-2720 Series                                | 1         | 1.2%    |
| Samsung SCX-4300 Series                                   | 1         | 1.2%    |
| Samsung ML-2240 Series                                    | 1         | 1.2%    |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.2%    |
| Samsung C48x Series                                       | 1         | 1.2%    |
| Samsung C43x Series                                       | 1         | 1.2%    |
| Prolific PL2305 Parallel Port                             | 1         | 1.2%    |
| HP Printing Support                                       | 1         | 1.2%    |
| HP OfficeJet Pro 8020 series                              | 1         | 1.2%    |
| HP OfficeJet 6950                                         | 1         | 1.2%    |
| HP OfficeJet 3830 series                                  | 1         | 1.2%    |
| HP LaserJet Professional P1102w                           | 1         | 1.2%    |
| HP LaserJet P1005                                         | 1         | 1.2%    |
| HP LaserJet 1320                                          | 1         | 1.2%    |
| HP Laser 107w                                             | 1         | 1.2%    |
| HP DeskJet F2100 Printer series                           | 1         | 1.2%    |
| HP Deskjet D1500 series                                   | 1         | 1.2%    |
| HP DeskJet 916C                                           | 1         | 1.2%    |
| HP DeskJet 6940 series                                    | 1         | 1.2%    |
| HP DeskJet 3630 series                                    | 1         | 1.2%    |
| HP DeskJet 2700 series                                    | 1         | 1.2%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 23        | 63.89%  |
| Seiko Epson     | 7         | 19.44%  |
| Mustek Systems  | 3         | 8.33%   |
| Hewlett-Packard | 2         | 5.56%   |
| Plustek         | 1         | 2.78%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                       | 4         | 10.81%  |
| Canon CanoScan LiDE 210                       | 4         | 10.81%  |
| Mustek Systems ScanExpress 1200 UB            | 3         | 8.11%   |
| Seiko Epson Scanner                           | 2         | 5.41%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 2         | 5.41%   |
| Seiko Epson GT-X770 [Perfection V500]         | 2         | 5.41%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 2         | 5.41%   |
| Canon CanoScan N650U/N656U                    | 2         | 5.41%   |
| Canon CanoScan LiDE 200                       | 2         | 5.41%   |
| Canon CanoScan LiDE 120                       | 2         | 5.41%   |
| Canon CanoScan LiDE 110                       | 2         | 5.41%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 2.7%    |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 2.7%    |
| Plustek 600dpi USB Scanner                    | 1         | 2.7%    |
| HP ScanJet 5590                               | 1         | 2.7%    |
| HP ScanJet 3300c                              | 1         | 2.7%    |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 2.7%    |
| Canon CanoScan LiDE 60                        | 1         | 2.7%    |
| Canon CanoScan FB630U                         | 1         | 2.7%    |
| Canon CanoScan 9000F Mark II                  | 1         | 2.7%    |
| Canon CanoScan 5600F                          | 1         | 2.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 456       | 20.94%  |
| Microdia                               | 255       | 11.71%  |
| Realtek Semiconductor                  | 217       | 9.96%   |
| IMC Networks                           | 169       | 7.76%   |
| Sunplus Innovation Technology          | 155       | 7.12%   |
| Logitech                               | 134       | 6.15%   |
| Acer                                   | 122       | 5.6%    |
| Cheng Uei Precision Industry (Foxlink) | 97        | 4.45%   |
| Apple                                  | 87        | 3.99%   |
| Quanta                                 | 71        | 3.26%   |
| Suyin                                  | 68        | 3.12%   |
| Lite-On Technology                     | 43        | 1.97%   |
| Syntek                                 | 29        | 1.33%   |
| Samsung Electronics                    | 21        | 0.96%   |
| Luxvisions Innotech Limited            | 21        | 0.96%   |
| Silicon Motion                         | 20        | 0.92%   |
| Bison Electronics                      | 19        | 0.87%   |
| Ricoh                                  | 18        | 0.83%   |
| Microsoft                              | 16        | 0.73%   |
| Lenovo                                 | 14        | 0.64%   |
| Primax Electronics                     | 13        | 0.6%    |
| Alcor Micro                            | 13        | 0.6%    |
| Trust                                  | 10        | 0.46%   |
| Sonix Technology                       | 6         | 0.28%   |
| Jieli Technology                       | 6         | 0.28%   |
| Importek                               | 6         | 0.28%   |
| Generalplus Technology                 | 6         | 0.28%   |
| SunplusIT                              | 5         | 0.23%   |
| MacroSilicon                           | 5         | 0.23%   |
| Sweex                                  | 4         | 0.18%   |
| Creative Technology                    | 4         | 0.18%   |
| ARC International                      | 4         | 0.18%   |
| ALi                                    | 4         | 0.18%   |
| Z-Star Microelectronics                | 3         | 0.14%   |
| Y Media                                | 3         | 0.14%   |
| Valve Software                         | 3         | 0.14%   |
| LG Electronics                         | 3         | 0.14%   |
| Genesys Logic                          | 3         | 0.14%   |
| Tobii Technology AB                    | 2         | 0.09%   |
| Ruision                                | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 157       | 7.05%   |
| Realtek Integrated_Webcam_HD                                               | 80        | 3.59%   |
| Chicony Integrated Camera                                                  | 79        | 3.55%   |
| Realtek Integrated_Webcam_5M                                               | 67        | 3.01%   |
| Sunplus Integrated_Webcam_HD                                               | 65        | 2.92%   |
| IMC Networks Integrated Camera                                             | 58        | 2.6%    |
| Chicony HD WebCam                                                          | 57        | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 35        | 1.57%   |
| Acer Integrated Camera                                                     | 33        | 1.48%   |
| Chicony HP HD Camera                                                       | 29        | 1.3%    |
| Apple Built-in iSight                                                      | 27        | 1.21%   |
| Logitech Webcam C270                                                       | 26        | 1.17%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 23        | 1.03%   |
| Chicony USB2.0 Camera                                                      | 22        | 0.99%   |
| Samsung Galaxy A5 (MTP)                                                    | 21        | 0.94%   |
| Logitech HD Pro Webcam C920                                                | 21        | 0.94%   |
| Microdia Integrated_Webcam_5M                                              | 20        | 0.9%    |
| Chicony HP Wide Vision HD Camera                                           | 20        | 0.9%    |
| Chicony USB 2.0 Camera                                                     | 18        | 0.81%   |
| Apple FaceTime HD Camera (Built-in)                                        | 18        | 0.81%   |
| Syntek Integrated Camera                                                   | 17        | 0.76%   |
| Chicony TOSHIBA Web Camera - HD                                            | 17        | 0.76%   |
| Acer BisonCam,NB Pro                                                       | 17        | 0.76%   |
| Sunplus HD WebCam                                                          | 16        | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 16        | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 15        | 0.67%   |
| Apple FaceTime HD Camera                                                   | 15        | 0.67%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 14        | 0.63%   |
| Logitech Webcam C310                                                       | 14        | 0.63%   |
| Realtek USB Camera                                                         | 13        | 0.58%   |
| Microdia Integrated Webcam                                                 | 13        | 0.58%   |
| Lite-On Integrated Camera                                                  | 12        | 0.54%   |
| IMC Networks Integrated Webcam                                             | 12        | 0.54%   |
| Chicony Integrated HP HD Webcam                                            | 12        | 0.54%   |
| Acer SunplusIT Integrated Camera                                           | 12        | 0.54%   |
| Quanta HP Wide Vision HD Camera                                            | 11        | 0.49%   |
| Quanta HD User Facing                                                      | 11        | 0.49%   |
| Primax HP HD Webcam [Fixed]                                                | 11        | 0.49%   |
| Logitech HD Webcam C525                                                    | 11        | 0.49%   |
| Lite-On HP HD Camera                                                       | 11        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 144       | 33.1%   |
| Synaptics                  | 138       | 31.72%  |
| Shenzhen Goodix Technology | 55        | 12.64%  |
| AuthenTec                  | 31        | 7.13%   |
| Elan Microelectronics      | 24        | 5.52%   |
| LighTuning Technology      | 20        | 4.6%    |
| Upek                       | 19        | 4.37%   |
| STMicroelectronics         | 3         | 0.69%   |
| Samsung Electronics        | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 47        | 10.8%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 39        | 8.97%   |
| Shenzhen Goodix  FingerPrint Device                                        | 23        | 5.29%   |
| Synaptics UWP WBDI                                                         | 20        | 4.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 4.37%   |
| Shenzhen Goodix FingerPrint                                                | 19        | 4.37%   |
| Validity Sensors VFS491                                                    | 18        | 4.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 3.22%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 2.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 2.99%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 2.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 2.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 2.76%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.76%   |
| Elan ELAN:ARM-M4                                                           | 12        | 2.76%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.76%   |
| Synaptics WBDI                                                             | 11        | 2.53%   |
| Synaptics  WBDI                                                            | 11        | 2.53%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 2.53%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 2.07%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 2.07%   |
| AuthenTec AES2810                                                          | 8         | 1.84%   |
| Unknown                                                                    | 7         | 1.61%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.38%   |
| AuthenTec AES1600                                                          | 6         | 1.38%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.15%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.15%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.15%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.15%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 0.92%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 0.92%   |
| Synaptics WBDI Device                                                      | 4         | 0.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.69%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.69%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.69%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.69%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.46%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.46%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.46%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 102       | 52.31%  |
| Alcor Micro                       | 50        | 25.64%  |
| O2 Micro                          | 23        | 11.79%  |
| Upek                              | 6         | 3.08%   |
| Lenovo                            | 6         | 3.08%   |
| VASCO Data Security International | 1         | 0.51%   |
| SCM Microsystems                  | 1         | 0.51%   |
| OmniKey                           | 1         | 0.51%   |
| Gemalto (was Gemplus)             | 1         | 0.51%   |
| Fujitsu Siemens Computers         | 1         | 0.51%   |
| Clay Logic                        | 1         | 0.51%   |
| Chicony Electronics               | 1         | 0.51%   |
| Advanced Card Systems             | 1         | 0.51%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 50        | 25.64%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 17.44%  |
| Broadcom 58200                                                               | 28        | 14.36%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 10.77%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 10.77%  |
| Broadcom 5880                                                                | 19        | 9.74%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 3.08%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3.08%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.03%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.51%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.51%   |
| OmniKey 5422 Smartcard Reader                                                | 1         | 0.51%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.51%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.51%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.51%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.51%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.51%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2493      | 67.67%  |
| 1     | 926       | 25.14%  |
| 2     | 214       | 5.81%   |
| 3     | 34        | 0.92%   |
| 4     | 10        | 0.27%   |
| 5     | 4         | 0.11%   |
| 6     | 3         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 430       | 29.35%  |
| Graphics card            | 318       | 21.71%  |
| Chipcard                 | 172       | 11.74%  |
| Net/wireless             | 143       | 9.76%   |
| Multimedia controller    | 135       | 9.22%   |
| Communication controller | 58        | 3.96%   |
| Camera                   | 45        | 3.07%   |
| Bluetooth                | 27        | 1.84%   |
| Unassigned class         | 26        | 1.77%   |
| Sound                    | 22        | 1.5%    |
| Storage                  | 20        | 1.37%   |
| Network                  | 15        | 1.02%   |
| Card reader              | 14        | 0.96%   |
| Net/ethernet             | 13        | 0.89%   |
| Flash memory             | 8         | 0.55%   |
| Storage/ide              | 4         | 0.27%   |
| Storage/ata              | 4         | 0.27%   |
| Modem                    | 3         | 0.2%    |
| Tv card                  | 2         | 0.14%   |
| Storage/raid             | 2         | 0.14%   |
| Storage/nvme             | 2         | 0.14%   |
| Firewire controller      | 1         | 0.07%   |
| Dvb card                 | 1         | 0.07%   |

