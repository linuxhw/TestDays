Linux in UK - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

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

Total: 4414

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 1545               | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| HP            | Notebook                    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| Valve         | Jupiter                     | [12f0d9358a](https://linux-hardware.org/?probe=12f0d9358a) | Oct 01, 2022 |
| Apple         | MacBookPro16,2              | [8eaded9cb5](https://linux-hardware.org/?probe=8eaded9cb5) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Acer          | Swift SF314-43              | [cfd0c22e29](https://linux-hardware.org/?probe=cfd0c22e29) | Sep 30, 2022 |
| Valve         | Jupiter                     | [dab0a00c02](https://linux-hardware.org/?probe=dab0a00c02) | Sep 30, 2022 |
| Valve         | Jupiter                     | [e9737fcadf](https://linux-hardware.org/?probe=e9737fcadf) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Dell          | XPS 13 7390                 | [c4ccdf9992](https://linux-hardware.org/?probe=c4ccdf9992) | Sep 30, 2022 |
| Dell          | Latitude 7430               | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| HP            | Compaq 6720s                | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Dell          | Inspiron 1564               | [d9dd05aa12](https://linux-hardware.org/?probe=d9dd05aa12) | Sep 29, 2022 |
| Dell          | XPS 13 9360                 | [6f1ecca2f0](https://linux-hardware.org/?probe=6f1ecca2f0) | Sep 28, 2022 |
| Lenovo        | G570 4334                   | [7b96f1db41](https://linux-hardware.org/?probe=7b96f1db41) | Sep 28, 2022 |
| Lenovo        | G570 4334                   | [601591c97e](https://linux-hardware.org/?probe=601591c97e) | Sep 26, 2022 |
| MSI           | GT72S 6QE                   | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Timi          | RedmiBook Pro 15S           | [533cc3b3ae](https://linux-hardware.org/?probe=533cc3b3ae) | Sep 26, 2022 |
| Valve         | Jupiter                     | [c3305d9bff](https://linux-hardware.org/?probe=c3305d9bff) | Sep 26, 2022 |
| Jumper        | EZbook                      | [1af58cd7e7](https://linux-hardware.org/?probe=1af58cd7e7) | Sep 25, 2022 |
| Dell          | XPS 15 9510                 | [1ccf6c5c41](https://linux-hardware.org/?probe=1ccf6c5c41) | Sep 25, 2022 |
| Acer          | Aspire A315-51              | [21121aa007](https://linux-hardware.org/?probe=21121aa007) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| Dell          | Inspiron 15 5510            | [cfda1aa63a](https://linux-hardware.org/?probe=cfda1aa63a) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 23476Y7       | [8488ad9e53](https://linux-hardware.org/?probe=8488ad9e53) | Sep 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [bdc8453efc](https://linux-hardware.org/?probe=bdc8453efc) | Sep 24, 2022 |
| Acer          | Swift SF315-52              | [b9e88a43d8](https://linux-hardware.org/?probe=b9e88a43d8) | Sep 24, 2022 |
| Lenovo        | ThinkPad T440s 20ARA0YL0... | [93eedc638b](https://linux-hardware.org/?probe=93eedc638b) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dc3a97d467](https://linux-hardware.org/?probe=dc3a97d467) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | [02787c733c](https://linux-hardware.org/?probe=02787c733c) | Sep 23, 2022 |
| ASUSTek       | N750JV                      | [f69fe7dacf](https://linux-hardware.org/?probe=f69fe7dacf) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | [fe7ae61ecd](https://linux-hardware.org/?probe=fe7ae61ecd) | Sep 23, 2022 |
| Dell          | Latitude E6330              | [5f1a272734](https://linux-hardware.org/?probe=5f1a272734) | Sep 23, 2022 |
| Dell          | Latitude 5411               | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| HP            | Laptop 15-bw0xx             | [c4915d8dd2](https://linux-hardware.org/?probe=c4915d8dd2) | Sep 22, 2022 |
| MSI           | GL73 8RD                    | [f197efe030](https://linux-hardware.org/?probe=f197efe030) | Sep 22, 2022 |
| MSI           | GL73 8RD                    | [0534ef55fc](https://linux-hardware.org/?probe=0534ef55fc) | Sep 22, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [03428c1a17](https://linux-hardware.org/?probe=03428c1a17) | Sep 21, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [c859bf5e24](https://linux-hardware.org/?probe=c859bf5e24) | Sep 21, 2022 |
| Valve         | Jupiter                     | [721ede2e11](https://linux-hardware.org/?probe=721ede2e11) | Sep 20, 2022 |
| Dell          | Inspiron 5570               | [16d661b4e5](https://linux-hardware.org/?probe=16d661b4e5) | Sep 20, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | [20c7b9dcf9](https://linux-hardware.org/?probe=20c7b9dcf9) | Sep 20, 2022 |
| Lenovo        | E50-80 80J2                 | [a399d96de2](https://linux-hardware.org/?probe=a399d96de2) | Sep 20, 2022 |
| Valve         | Jupiter                     | [e60653a4c7](https://linux-hardware.org/?probe=e60653a4c7) | Sep 20, 2022 |
| Lenovo        | Legion 5-15ACH6H 82JU       | [1f48647e32](https://linux-hardware.org/?probe=1f48647e32) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| HONOR         | NMH-WCX9                    | [dd2687098a](https://linux-hardware.org/?probe=dd2687098a) | Sep 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [6b6ad790c5](https://linux-hardware.org/?probe=6b6ad790c5) | Sep 19, 2022 |
| Lenovo        | Yoga 3 14 80JH              | [7b17bd93c0](https://linux-hardware.org/?probe=7b17bd93c0) | Sep 19, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| HONOR         | NMH-WCX9                    | [060f3bd895](https://linux-hardware.org/?probe=060f3bd895) | Sep 19, 2022 |
| Panasonic     | CF-53JAWZYDE                | [f8b1ca10d1](https://linux-hardware.org/?probe=f8b1ca10d1) | Sep 19, 2022 |
| Lenovo        | E50-80 80J2                 | [1a538a3132](https://linux-hardware.org/?probe=1a538a3132) | Sep 18, 2022 |
| Dell          | Studio 1737                 | [7218731367](https://linux-hardware.org/?probe=7218731367) | Sep 18, 2022 |
| ASUSTek       | X510UQ                      | [eb619ed1c5](https://linux-hardware.org/?probe=eb619ed1c5) | Sep 18, 2022 |
| Dell          | Precision 5530              | [8fc00af945](https://linux-hardware.org/?probe=8fc00af945) | Sep 18, 2022 |
| Unknown       | Unknown                     | [1e27521b13](https://linux-hardware.org/?probe=1e27521b13) | Sep 17, 2022 |
| Acer          | Aspire V3-571               | [3f20a5e69d](https://linux-hardware.org/?probe=3f20a5e69d) | Sep 17, 2022 |
| Dell          | Latitude 7390               | [64c9b13553](https://linux-hardware.org/?probe=64c9b13553) | Sep 17, 2022 |
| HUAWEI        | BOM-WXX9                    | [0c3d62f1c9](https://linux-hardware.org/?probe=0c3d62f1c9) | Sep 17, 2022 |
| Valve         | Jupiter                     | [c4dd2bf91f](https://linux-hardware.org/?probe=c4dd2bf91f) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| HP            | Laptop 15-da0xxx            | [6341f27d68](https://linux-hardware.org/?probe=6341f27d68) | Sep 16, 2022 |
| Apple         | MacBook6,1                  | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Acidanther... | iMac19,2                    | [94b79ac6e5](https://linux-hardware.org/?probe=94b79ac6e5) | Sep 16, 2022 |
| HP            | ProBook 4340s               | [acca12f9d4](https://linux-hardware.org/?probe=acca12f9d4) | Sep 16, 2022 |
| Valve         | Jupiter                     | [9adc000021](https://linux-hardware.org/?probe=9adc000021) | Sep 15, 2022 |
| Dell          | Latitude 7490               | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | Z70-80 80FG                 | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| HP            | Laptop 15-da0xxx            | [82140783de](https://linux-hardware.org/?probe=82140783de) | Sep 14, 2022 |
| Dell          | Latitude E7250              | [80a2e50cfc](https://linux-hardware.org/?probe=80a2e50cfc) | Sep 14, 2022 |
| Dell          | XPS 15 9510                 | [44be9b9134](https://linux-hardware.org/?probe=44be9b9134) | Sep 13, 2022 |
| HP            | EliteBook 850 G6            | [b284db5ac4](https://linux-hardware.org/?probe=b284db5ac4) | Sep 13, 2022 |
| Lenovo        | Flex 2-14 20404             | [a27c60fbde](https://linux-hardware.org/?probe=a27c60fbde) | Sep 13, 2022 |
| Dell          | Inspiron 3542               | [2c5a122ce9](https://linux-hardware.org/?probe=2c5a122ce9) | Sep 12, 2022 |
| Dell          | Inspiron 3542               | [ef3098c81a](https://linux-hardware.org/?probe=ef3098c81a) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a54854cd7](https://linux-hardware.org/?probe=4a54854cd7) | Sep 12, 2022 |
| Entroware     | Orion                       | [d96888edf9](https://linux-hardware.org/?probe=d96888edf9) | Sep 12, 2022 |
| Entroware     | Orion                       | [c06e53ad80](https://linux-hardware.org/?probe=c06e53ad80) | Sep 12, 2022 |
| Dell          | Inspiron 3537               | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| Dell          | XPS 13 9350                 | [e137564f6b](https://linux-hardware.org/?probe=e137564f6b) | Sep 12, 2022 |
| Acer          | Aspire E5-576G              | [ee2635dbc8](https://linux-hardware.org/?probe=ee2635dbc8) | Sep 11, 2022 |
| HP            | Pavilion 15                 | [1e6331a36b](https://linux-hardware.org/?probe=1e6331a36b) | Sep 11, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [576eec419f](https://linux-hardware.org/?probe=576eec419f) | Sep 10, 2022 |
| Tactus        | GeoBook 110                 | [d13211f478](https://linux-hardware.org/?probe=d13211f478) | Sep 09, 2022 |
| Dell          | Inspiron 1720               | [27de3ede0c](https://linux-hardware.org/?probe=27de3ede0c) | Sep 09, 2022 |
| Star Labs     | Lite                        | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f5c538e2c7](https://linux-hardware.org/?probe=f5c538e2c7) | Sep 09, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7c3cdfba24](https://linux-hardware.org/?probe=7c3cdfba24) | Sep 08, 2022 |
| ASUSTek       | UX430UAR                    | [478d0564a6](https://linux-hardware.org/?probe=478d0564a6) | Sep 08, 2022 |
| Dell          | Precision 5770              | [41e44b27f4](https://linux-hardware.org/?probe=41e44b27f4) | Sep 08, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGA039U... | [43c002ad40](https://linux-hardware.org/?probe=43c002ad40) | Sep 07, 2022 |
| Toshiba       | Satellite NB10t-A-101       | [b824e1e3d5](https://linux-hardware.org/?probe=b824e1e3d5) | Sep 06, 2022 |
| Toshiba       | Satellite A660              | [8a76871325](https://linux-hardware.org/?probe=8a76871325) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | [a4f8e52425](https://linux-hardware.org/?probe=a4f8e52425) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | [0daca2662d](https://linux-hardware.org/?probe=0daca2662d) | Sep 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [40d6a47565](https://linux-hardware.org/?probe=40d6a47565) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [a75fed8b3f](https://linux-hardware.org/?probe=a75fed8b3f) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [cd613ebcd2](https://linux-hardware.org/?probe=cd613ebcd2) | Sep 05, 2022 |
| Clevo         | P65_P67SE                   | [9a38027b73](https://linux-hardware.org/?probe=9a38027b73) | Sep 05, 2022 |
| HP            | OMEN by Laptop 17-cb1xxx    | [f0a6826f9d](https://linux-hardware.org/?probe=f0a6826f9d) | Sep 05, 2022 |
| Valve         | Jupiter                     | [04c7e44198](https://linux-hardware.org/?probe=04c7e44198) | Sep 05, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [4641fe397a](https://linux-hardware.org/?probe=4641fe397a) | Sep 05, 2022 |
| Acer          | Aspire V5-552               | [031439a681](https://linux-hardware.org/?probe=031439a681) | Sep 04, 2022 |
| Dell          | Inspiron 5558               | [2d4eeaf028](https://linux-hardware.org/?probe=2d4eeaf028) | Sep 03, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [1822ab5853](https://linux-hardware.org/?probe=1822ab5853) | Sep 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [2c5c9d2233](https://linux-hardware.org/?probe=2c5c9d2233) | Sep 02, 2022 |
| Dell          | Precision 5530              | [0151d15e28](https://linux-hardware.org/?probe=0151d15e28) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [9cabeefea8](https://linux-hardware.org/?probe=9cabeefea8) | Sep 01, 2022 |
| ASUSTek       | N552VW                      | [99d4a9be86](https://linux-hardware.org/?probe=99d4a9be86) | Sep 01, 2022 |
| Lenovo        | ThinkPad T400 6474W7T       | [f9a9b12b37](https://linux-hardware.org/?probe=f9a9b12b37) | Sep 01, 2022 |
| Dell          | Precision 5530              | [298ce27830](https://linux-hardware.org/?probe=298ce27830) | Sep 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [55073b08dc](https://linux-hardware.org/?probe=55073b08dc) | Sep 01, 2022 |
| Lenovo        | ThinkPad T400 6474W7T       | [b52974ac00](https://linux-hardware.org/?probe=b52974ac00) | Sep 01, 2022 |
| HUAWEI        | HKD-WXX                     | [7ff88a93c2](https://linux-hardware.org/?probe=7ff88a93c2) | Sep 01, 2022 |
| HP            | Pavilion g6                 | [cc725d880c](https://linux-hardware.org/?probe=cc725d880c) | Aug 31, 2022 |
| HP            | ProBook 450 G6              | [7763040d56](https://linux-hardware.org/?probe=7763040d56) | Aug 30, 2022 |
| Valve         | Jupiter                     | [1b38f48059](https://linux-hardware.org/?probe=1b38f48059) | Aug 30, 2022 |
| Acer          | Aspire 5680                 | [e58163df64](https://linux-hardware.org/?probe=e58163df64) | Aug 30, 2022 |
| Dell          | Precision M6400             | [3cf32e24fa](https://linux-hardware.org/?probe=3cf32e24fa) | Aug 30, 2022 |
| Standard      | Unknown                     | [62e0164e5b](https://linux-hardware.org/?probe=62e0164e5b) | Aug 29, 2022 |
| Dell          | XPS 13 9305                 | [d8bd3d6fc6](https://linux-hardware.org/?probe=d8bd3d6fc6) | Aug 28, 2022 |
| HP            | Laptop 15-db0xxx            | [d67f262815](https://linux-hardware.org/?probe=d67f262815) | Aug 28, 2022 |
| Dell          | Studio 1735                 | [912f409b37](https://linux-hardware.org/?probe=912f409b37) | Aug 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | [1d29556c76](https://linux-hardware.org/?probe=1d29556c76) | Aug 28, 2022 |
| Dell          | Inspiron 1525               | [148c6dd35a](https://linux-hardware.org/?probe=148c6dd35a) | Aug 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8841ba5f53](https://linux-hardware.org/?probe=8841ba5f53) | Aug 27, 2022 |
| Dell          | Latitude E6510              | [846791d8b9](https://linux-hardware.org/?probe=846791d8b9) | Aug 26, 2022 |
| HUAWEI        | KLVD-WXX9                   | [c8eb396b68](https://linux-hardware.org/?probe=c8eb396b68) | Aug 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [62ce95ce9c](https://linux-hardware.org/?probe=62ce95ce9c) | Aug 26, 2022 |
| Dell          | Vostro 5625                 | [741abbfe3d](https://linux-hardware.org/?probe=741abbfe3d) | Aug 26, 2022 |
| Acer          | Aspire 5680                 | [8ee728569a](https://linux-hardware.org/?probe=8ee728569a) | Aug 25, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [2a441a673b](https://linux-hardware.org/?probe=2a441a673b) | Aug 25, 2022 |
| Acer          | Aspire 5742G                | [dfe17e89f1](https://linux-hardware.org/?probe=dfe17e89f1) | Aug 25, 2022 |
| Valve         | Jupiter                     | [b74760105e](https://linux-hardware.org/?probe=b74760105e) | Aug 25, 2022 |
| Linx          | LINX1010B                   | [07194b77d4](https://linux-hardware.org/?probe=07194b77d4) | Aug 24, 2022 |
| Dell          | XPS 15 9520                 | [e4f7ce1ec7](https://linux-hardware.org/?probe=e4f7ce1ec7) | Aug 23, 2022 |
| Acer          | Nitro AN517-51              | [e53f196e21](https://linux-hardware.org/?probe=e53f196e21) | Aug 23, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [2ac415ca87](https://linux-hardware.org/?probe=2ac415ca87) | Aug 23, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [a48fff902b](https://linux-hardware.org/?probe=a48fff902b) | Aug 23, 2022 |
| Dell          | Inspiron 5567               | [7b0f03259b](https://linux-hardware.org/?probe=7b0f03259b) | Aug 23, 2022 |
| HUAWEI        | NBD-WXX9                    | [4391428197](https://linux-hardware.org/?probe=4391428197) | Aug 22, 2022 |
| Acer          | TravelMate 5760             | [3d9c208d81](https://linux-hardware.org/?probe=3d9c208d81) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [d08e00053f](https://linux-hardware.org/?probe=d08e00053f) | Aug 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f94ce7d00a](https://linux-hardware.org/?probe=f94ce7d00a) | Aug 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [5b8c529dab](https://linux-hardware.org/?probe=5b8c529dab) | Aug 22, 2022 |
| Apple         | MacBookPro12,1              | [e4dec4681f](https://linux-hardware.org/?probe=e4dec4681f) | Aug 22, 2022 |
| Acer          | Aspire 5740                 | [19158f2e35](https://linux-hardware.org/?probe=19158f2e35) | Aug 21, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [01416789ab](https://linux-hardware.org/?probe=01416789ab) | Aug 21, 2022 |
| Samsung       | R519/R719                   | [c0720d7924](https://linux-hardware.org/?probe=c0720d7924) | Aug 21, 2022 |
| HP            | ProBook 6570b               | [eba0cd02ec](https://linux-hardware.org/?probe=eba0cd02ec) | Aug 21, 2022 |
| HP            | Laptop 17-cp0xxx            | [6ba8616656](https://linux-hardware.org/?probe=6ba8616656) | Aug 20, 2022 |
| Acer          | Aspire one 1-431            | [cd1755e81d](https://linux-hardware.org/?probe=cd1755e81d) | Aug 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [b7c760ecee](https://linux-hardware.org/?probe=b7c760ecee) | Aug 19, 2022 |
| Valve         | Jupiter                     | [d6b92d1aa0](https://linux-hardware.org/?probe=d6b92d1aa0) | Aug 19, 2022 |
| Apple         | MacBookPro9,2               | [23fb1e2721](https://linux-hardware.org/?probe=23fb1e2721) | Aug 19, 2022 |
| Apple         | MacBookPro9,2               | [eb35a0b474](https://linux-hardware.org/?probe=eb35a0b474) | Aug 18, 2022 |
| Dell          | Inspiron 7570               | [7d353117aa](https://linux-hardware.org/?probe=7d353117aa) | Aug 18, 2022 |
| Dell          | Inspiron 7570               | [10609a18a8](https://linux-hardware.org/?probe=10609a18a8) | Aug 18, 2022 |
| Apple         | MacBookAir6,2               | [f27c089486](https://linux-hardware.org/?probe=f27c089486) | Aug 18, 2022 |
| Lenovo        | Z51-70 80K6                 | [f10fe1f561](https://linux-hardware.org/?probe=f10fe1f561) | Aug 18, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [e056c24d1d](https://linux-hardware.org/?probe=e056c24d1d) | Aug 18, 2022 |
| HP            | Laptop 14-cm0xxx            | [e6b2ec9760](https://linux-hardware.org/?probe=e6b2ec9760) | Aug 17, 2022 |
| Dell          | XPS 15 9560                 | [d971bbde47](https://linux-hardware.org/?probe=d971bbde47) | Aug 17, 2022 |
| Valve         | Jupiter                     | [c395a0f9db](https://linux-hardware.org/?probe=c395a0f9db) | Aug 16, 2022 |
| Lenovo        | G505s 20255                 | [58a439770d](https://linux-hardware.org/?probe=58a439770d) | Aug 15, 2022 |
| Apple         | MacBookPro10,1              | [c4738a316c](https://linux-hardware.org/?probe=c4738a316c) | Aug 15, 2022 |
| HP            | ProBook 6570b               | [b490a791c0](https://linux-hardware.org/?probe=b490a791c0) | Aug 15, 2022 |
| Lenovo        | IdeaPad Z580                | [f9d6b2f915](https://linux-hardware.org/?probe=f9d6b2f915) | Aug 14, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [1db8ed0da4](https://linux-hardware.org/?probe=1db8ed0da4) | Aug 14, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [105367d5d6](https://linux-hardware.org/?probe=105367d5d6) | Aug 14, 2022 |
| Notebook      | NL40_50CU                   | [dc6838dde5](https://linux-hardware.org/?probe=dc6838dde5) | Aug 14, 2022 |
| Notebook      | NL40_50CU                   | [84a0545593](https://linux-hardware.org/?probe=84a0545593) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [b3df3a51e0](https://linux-hardware.org/?probe=b3df3a51e0) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2043908eed](https://linux-hardware.org/?probe=2043908eed) | Aug 14, 2022 |
| HP            | Laptop 17-cn0xxx            | [0006dc34cf](https://linux-hardware.org/?probe=0006dc34cf) | Aug 14, 2022 |
| Notebook      | PCx0Dx                      | [b3df6d2bd8](https://linux-hardware.org/?probe=b3df6d2bd8) | Aug 13, 2022 |
| Notebook      | PCx0Dx                      | [a92687ac04](https://linux-hardware.org/?probe=a92687ac04) | Aug 13, 2022 |
| Toshiba       | Satellite C660              | [50d9a2d6fe](https://linux-hardware.org/?probe=50d9a2d6fe) | Aug 13, 2022 |
| HP            | ProBook 6570b               | [fb2fa26698](https://linux-hardware.org/?probe=fb2fa26698) | Aug 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SBD000    | [b0bbce7c9d](https://linux-hardware.org/?probe=b0bbce7c9d) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [dbbd0524d8](https://linux-hardware.org/?probe=dbbd0524d8) | Aug 12, 2022 |
| Valve         | Jupiter                     | [c6e02c54e7](https://linux-hardware.org/?probe=c6e02c54e7) | Aug 11, 2022 |
| HP            | Pavilion g6                 | [a03cc7e650](https://linux-hardware.org/?probe=a03cc7e650) | Aug 11, 2022 |
| Dell          | Inspiron 5570               | [b94818059a](https://linux-hardware.org/?probe=b94818059a) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | [8090e74c22](https://linux-hardware.org/?probe=8090e74c22) | Aug 10, 2022 |
| HP            | ProBook 6570b               | [0acbdaf806](https://linux-hardware.org/?probe=0acbdaf806) | Aug 10, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [6ca46e8126](https://linux-hardware.org/?probe=6ca46e8126) | Aug 09, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [ad3cfbb4c9](https://linux-hardware.org/?probe=ad3cfbb4c9) | Aug 09, 2022 |
| Acer          | Aspire 5740                 | [1934c32bc7](https://linux-hardware.org/?probe=1934c32bc7) | Aug 09, 2022 |
| HP            | G62                         | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Dell          | Inspiron 5593               | [1b59fcaefb](https://linux-hardware.org/?probe=1b59fcaefb) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [0e2f35ef5e](https://linux-hardware.org/?probe=0e2f35ef5e) | Aug 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [404319dfd4](https://linux-hardware.org/?probe=404319dfd4) | Aug 07, 2022 |
| Dell          | Latitude E5470              | [c39ddac6c9](https://linux-hardware.org/?probe=c39ddac6c9) | Aug 07, 2022 |
| Apple         | MacBookPro9,2               | [85dc12b4d1](https://linux-hardware.org/?probe=85dc12b4d1) | Aug 07, 2022 |
| Valve         | Jupiter                     | [d8ef9609a7](https://linux-hardware.org/?probe=d8ef9609a7) | Aug 07, 2022 |
| AMI           | Unknown                     | [d40dbd9414](https://linux-hardware.org/?probe=d40dbd9414) | Aug 07, 2022 |
| Acer          | Swift SF114-31              | [b1cba472dc](https://linux-hardware.org/?probe=b1cba472dc) | Aug 06, 2022 |
| ASUSTek       | G750JM                      | [0fc5828ad1](https://linux-hardware.org/?probe=0fc5828ad1) | Aug 06, 2022 |
| Lenovo        | V15-IIL 82C5                | [cc2c2e7ceb](https://linux-hardware.org/?probe=cc2c2e7ceb) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | [e0153e91b7](https://linux-hardware.org/?probe=e0153e91b7) | Aug 04, 2022 |
| Dell          | Latitude E6430              | [388b301ced](https://linux-hardware.org/?probe=388b301ced) | Aug 04, 2022 |
| Star Labs     | LabTop                      | [a32c7d706c](https://linux-hardware.org/?probe=a32c7d706c) | Aug 03, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c29778d816](https://linux-hardware.org/?probe=c29778d816) | Aug 03, 2022 |
| HP            | Notebook                    | [661237e74a](https://linux-hardware.org/?probe=661237e74a) | Aug 03, 2022 |
| MSI           | GE62VR 7RF                  | [e5f6f7e14c](https://linux-hardware.org/?probe=e5f6f7e14c) | Aug 03, 2022 |
| Valve         | Jupiter                     | [8689254ee7](https://linux-hardware.org/?probe=8689254ee7) | Aug 03, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [eb77f8f852](https://linux-hardware.org/?probe=eb77f8f852) | Aug 03, 2022 |
| HP            | ProBook 455 G7              | [86bdcba616](https://linux-hardware.org/?probe=86bdcba616) | Aug 02, 2022 |
| Dell          | Inspiron 5580               | [49d857e7bf](https://linux-hardware.org/?probe=49d857e7bf) | Aug 02, 2022 |
| Dell          | Latitude E7450              | [38051fe609](https://linux-hardware.org/?probe=38051fe609) | Aug 01, 2022 |
| Dell          | XPS 15 7590                 | [8a4cc1f177](https://linux-hardware.org/?probe=8a4cc1f177) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b2b969b0e3](https://linux-hardware.org/?probe=b2b969b0e3) | Aug 01, 2022 |
| Packard Be... | EasyNote TK13BZ             | [530d3ad8db](https://linux-hardware.org/?probe=530d3ad8db) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [b99b5ef83f](https://linux-hardware.org/?probe=b99b5ef83f) | Aug 01, 2022 |
| Dell          | XPS 13 9380                 | [75f131a86a](https://linux-hardware.org/?probe=75f131a86a) | Aug 01, 2022 |
| ASUSTek       | X555LAB                     | [33a1712f4d](https://linux-hardware.org/?probe=33a1712f4d) | Aug 01, 2022 |
| Toshiba       | TECRA Z40-C                 | [9612659f60](https://linux-hardware.org/?probe=9612659f60) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [105d26b09c](https://linux-hardware.org/?probe=105d26b09c) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [3898ce2b5f](https://linux-hardware.org/?probe=3898ce2b5f) | Aug 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS02R0G    | [0aa31e3c39](https://linux-hardware.org/?probe=0aa31e3c39) | Jul 31, 2022 |
| Dell          | Latitude E6400              | [6962d36f57](https://linux-hardware.org/?probe=6962d36f57) | Jul 31, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [b3dc6e72d5](https://linux-hardware.org/?probe=b3dc6e72d5) | Jul 31, 2022 |
| Dell          | Precision M6800             | [3584b1693d](https://linux-hardware.org/?probe=3584b1693d) | Jul 31, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [521b86d8af](https://linux-hardware.org/?probe=521b86d8af) | Jul 31, 2022 |
| PC Special... | NS50MU                      | [b5dd220296](https://linux-hardware.org/?probe=b5dd220296) | Jul 29, 2022 |
| Linx          | LINX1010B                   | [60a5211d09](https://linux-hardware.org/?probe=60a5211d09) | Jul 28, 2022 |
| HP            | ProBook 4515s               | [b9759d3b5d](https://linux-hardware.org/?probe=b9759d3b5d) | Jul 28, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c2bcea4cf1](https://linux-hardware.org/?probe=c2bcea4cf1) | Jul 28, 2022 |
| HP            | Presario CQ56               | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| Apple         | MacBookAir7,2               | [a33f728c24](https://linux-hardware.org/?probe=a33f728c24) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [f005e0566d](https://linux-hardware.org/?probe=f005e0566d) | Jul 27, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [44954e91a2](https://linux-hardware.org/?probe=44954e91a2) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [6ae47baf6d](https://linux-hardware.org/?probe=6ae47baf6d) | Jul 26, 2022 |
| Dell          | XPS 15 9520                 | [007bab123f](https://linux-hardware.org/?probe=007bab123f) | Jul 26, 2022 |
| Dell          | XPS 15 9520                 | [b45acaf9b7](https://linux-hardware.org/?probe=b45acaf9b7) | Jul 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [414aede111](https://linux-hardware.org/?probe=414aede111) | Jul 25, 2022 |
| Gigabyte      | AORUS 17 XE4                | [0bddb42774](https://linux-hardware.org/?probe=0bddb42774) | Jul 25, 2022 |
| HP            | G61                         | [1586fc0cba](https://linux-hardware.org/?probe=1586fc0cba) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bf2cecb453](https://linux-hardware.org/?probe=bf2cecb453) | Jul 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [375ba933ba](https://linux-hardware.org/?probe=375ba933ba) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e2a1804b90](https://linux-hardware.org/?probe=e2a1804b90) | Jul 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6740b94551](https://linux-hardware.org/?probe=6740b94551) | Jul 24, 2022 |
| Dell          | Latitude E5570              | [fa3d675cde](https://linux-hardware.org/?probe=fa3d675cde) | Jul 24, 2022 |
| Lenovo        | ThinkPad X280 20KES2SN00    | [202423ba73](https://linux-hardware.org/?probe=202423ba73) | Jul 24, 2022 |
| Valve         | Jupiter                     | [3e7b7cb8cd](https://linux-hardware.org/?probe=3e7b7cb8cd) | Jul 23, 2022 |
| HP            | Pavilion g6                 | [73061b2ed5](https://linux-hardware.org/?probe=73061b2ed5) | Jul 23, 2022 |
| Dell          | Inspiron 1545               | [893377b9f7](https://linux-hardware.org/?probe=893377b9f7) | Jul 23, 2022 |
| Dell          | XPS 13 9370                 | [21e10aa056](https://linux-hardware.org/?probe=21e10aa056) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| AZW           | GT-R                        | [eb7604ea1c](https://linux-hardware.org/?probe=eb7604ea1c) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | [fe5dae3d4a](https://linux-hardware.org/?probe=fe5dae3d4a) | Jul 22, 2022 |
| Toshiba       | EQUIUM A110                 | [4b6ace9122](https://linux-hardware.org/?probe=4b6ace9122) | Jul 22, 2022 |
| Dell          | Inspiron 1525               | [f1af5f5e45](https://linux-hardware.org/?probe=f1af5f5e45) | Jul 22, 2022 |
| Dell          | Inspiron 1525               | [6c43e1dfd6](https://linux-hardware.org/?probe=6c43e1dfd6) | Jul 22, 2022 |
| Acer          | Aspire A315-21              | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | G62                         | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Dell          | XPS 15 9520                 | [51ddccaf88](https://linux-hardware.org/?probe=51ddccaf88) | Jul 21, 2022 |
| Acer          | Acadia V1.45                | [f3e470d7cf](https://linux-hardware.org/?probe=f3e470d7cf) | Jul 21, 2022 |
| Panasonic     | CF-53JAWZYDE                | [c1c835cb11](https://linux-hardware.org/?probe=c1c835cb11) | Jul 21, 2022 |
| Apple         | MacBookAir7,2               | [b0cdba7434](https://linux-hardware.org/?probe=b0cdba7434) | Jul 20, 2022 |
| HP            | G62                         | [3c4aab40ae](https://linux-hardware.org/?probe=3c4aab40ae) | Jul 20, 2022 |
| Dell          | Latitude 5285               | [2b46125d79](https://linux-hardware.org/?probe=2b46125d79) | Jul 20, 2022 |
| Acer          | Aspire ES1-531              | [45be1164f5](https://linux-hardware.org/?probe=45be1164f5) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| Razer         | Blade 15 Advanced Model ... | [8f3842495f](https://linux-hardware.org/?probe=8f3842495f) | Jul 18, 2022 |
| Dell          | Vostro 3559                 | [3770ab3d4c](https://linux-hardware.org/?probe=3770ab3d4c) | Jul 18, 2022 |
| Dell          | Latitude D430               | [22c020a070](https://linux-hardware.org/?probe=22c020a070) | Jul 18, 2022 |
| Lenovo        | ThinkPad W550s 20E2000PU... | [ee30c1c248](https://linux-hardware.org/?probe=ee30c1c248) | Jul 16, 2022 |
| Acer          | Nitro AN517-54              | [68f6109054](https://linux-hardware.org/?probe=68f6109054) | Jul 16, 2022 |
| Dell          | Latitude E6440              | [eabdcd7622](https://linux-hardware.org/?probe=eabdcd7622) | Jul 15, 2022 |
| HP            | ProBook 4545s               | [12575a32d1](https://linux-hardware.org/?probe=12575a32d1) | Jul 15, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [7177bb644a](https://linux-hardware.org/?probe=7177bb644a) | Jul 15, 2022 |
| Fusion5       | S14+                        | [64668fa44f](https://linux-hardware.org/?probe=64668fa44f) | Jul 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [ea2c3cd9e9](https://linux-hardware.org/?probe=ea2c3cd9e9) | Jul 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [63c4a7a0bd](https://linux-hardware.org/?probe=63c4a7a0bd) | Jul 14, 2022 |
| Dell          | Inspiron 7570               | [872ca81b40](https://linux-hardware.org/?probe=872ca81b40) | Jul 13, 2022 |
| Acer          | Predator PH315-51           | [37b04a8093](https://linux-hardware.org/?probe=37b04a8093) | Jul 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [80bb428b2a](https://linux-hardware.org/?probe=80bb428b2a) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Google        | Lindar                      | [2e12af7cf7](https://linux-hardware.org/?probe=2e12af7cf7) | Jul 11, 2022 |
| Medion        | Erazer P6661 MD60303        | [35fbb2c055](https://linux-hardware.org/?probe=35fbb2c055) | Jul 10, 2022 |
| MSI           | GF63 Thin 9RCX              | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| Dell          | Inspiron 16 7610            | [25dce193df](https://linux-hardware.org/?probe=25dce193df) | Jul 10, 2022 |
| Packard Be... | EasyNote TE69KB             | [89403f1acb](https://linux-hardware.org/?probe=89403f1acb) | Jul 09, 2022 |
| Valve         | Jupiter                     | [0c2ea27c49](https://linux-hardware.org/?probe=0c2ea27c49) | Jul 09, 2022 |
| Acer          | Aspire R3-131T              | [36851c847b](https://linux-hardware.org/?probe=36851c847b) | Jul 08, 2022 |
| HP            | G56                         | [5c38722298](https://linux-hardware.org/?probe=5c38722298) | Jul 07, 2022 |
| AZW           | SEi                         | [7556cabcae](https://linux-hardware.org/?probe=7556cabcae) | Jul 07, 2022 |
| Sony          | VGN-FS415B                  | [0387163846](https://linux-hardware.org/?probe=0387163846) | Jul 06, 2022 |
| MSI           | Raider GE66 12UH            | [59726526b6](https://linux-hardware.org/?probe=59726526b6) | Jul 06, 2022 |
| Lenovo        | S21e-20 80M4                | [968f07d190](https://linux-hardware.org/?probe=968f07d190) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [850003c6da](https://linux-hardware.org/?probe=850003c6da) | Jul 05, 2022 |
| Medion        | Erazer P6661 MD60303        | [59417db2d7](https://linux-hardware.org/?probe=59417db2d7) | Jul 05, 2022 |
| Dell          | XPS 13 7390                 | [c5155b28a7](https://linux-hardware.org/?probe=c5155b28a7) | Jul 04, 2022 |
| Apple         | MacBookAir6,2               | [072608d8d8](https://linux-hardware.org/?probe=072608d8d8) | Jul 04, 2022 |
| LG Electro... | 17Z90N-V.AA55A1             | [272164819f](https://linux-hardware.org/?probe=272164819f) | Jul 04, 2022 |
| Linx          | LINX1010B                   | [ae94ac08d9](https://linux-hardware.org/?probe=ae94ac08d9) | Jul 03, 2022 |
| Dell          | Vostro 5568                 | [c3e4fb87d2](https://linux-hardware.org/?probe=c3e4fb87d2) | Jul 03, 2022 |
| Dell          | Inspiron 7520               | [18acc5233d](https://linux-hardware.org/?probe=18acc5233d) | Jul 03, 2022 |
| Dell          | XPS 13 7390                 | [00370cb2ff](https://linux-hardware.org/?probe=00370cb2ff) | Jul 03, 2022 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | [d90a910042](https://linux-hardware.org/?probe=d90a910042) | Jul 02, 2022 |
| AWOW          | AL34                        | [be240349b7](https://linux-hardware.org/?probe=be240349b7) | Jul 02, 2022 |
| Dell          | Latitude E6400              | [d7b28806a9](https://linux-hardware.org/?probe=d7b28806a9) | Jul 02, 2022 |
| Samsung       | Q210/P210                   | [dfc97062be](https://linux-hardware.org/?probe=dfc97062be) | Jul 01, 2022 |
| Acer          | Extensa 5220                | [1ee1e31b52](https://linux-hardware.org/?probe=1ee1e31b52) | Jul 01, 2022 |
| HP            | Presario CQ56               | [af108b4933](https://linux-hardware.org/?probe=af108b4933) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| Dell          | Inspiron N5110              | [142c1c4ef2](https://linux-hardware.org/?probe=142c1c4ef2) | Jun 30, 2022 |
| Acer          | Aspire 5735                 | [b930fd3fcd](https://linux-hardware.org/?probe=b930fd3fcd) | Jun 29, 2022 |
| Toshiba       | Satellite C850-1NU          | [2b83cb161e](https://linux-hardware.org/?probe=2b83cb161e) | Jun 29, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [828f0b9ef1](https://linux-hardware.org/?probe=828f0b9ef1) | Jun 29, 2022 |
| Lenovo        | ThinkPad E590 20NB001AUK    | [f52aacfbfe](https://linux-hardware.org/?probe=f52aacfbfe) | Jun 29, 2022 |
| Toshiba       | Satellite L750              | [e01155e6ba](https://linux-hardware.org/?probe=e01155e6ba) | Jun 28, 2022 |
| HP            | Pavilion TS 14              | [f851b6a57b](https://linux-hardware.org/?probe=f851b6a57b) | Jun 28, 2022 |
| HP            | Pavilion Notebook           | [6e098b9c49](https://linux-hardware.org/?probe=6e098b9c49) | Jun 27, 2022 |
| HP            | Pavilion 15                 | [9e7a0c1889](https://linux-hardware.org/?probe=9e7a0c1889) | Jun 27, 2022 |
| Toshiba       | Satellite C870-1H2          | [edc5098a6f](https://linux-hardware.org/?probe=edc5098a6f) | Jun 27, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| Dell          | XPS 17 9710                 | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| HP            | EliteBook 2560p             | [47b4db95ed](https://linux-hardware.org/?probe=47b4db95ed) | Jun 26, 2022 |
| ASUSTek       | FX503VD                     | [f0e913f715](https://linux-hardware.org/?probe=f0e913f715) | Jun 26, 2022 |
| Dell          | XPS 17 9710                 | [f37581d70e](https://linux-hardware.org/?probe=f37581d70e) | Jun 26, 2022 |
| Acer          | Aspire A515-55G             | [d05c52e40b](https://linux-hardware.org/?probe=d05c52e40b) | Jun 26, 2022 |
| Lenovo        | S20-30 Touch 20434          | [b4ebe70967](https://linux-hardware.org/?probe=b4ebe70967) | Jun 26, 2022 |
| Dell          | XPS 13 9310                 | [fa3d29c80b](https://linux-hardware.org/?probe=fa3d29c80b) | Jun 25, 2022 |
| HP            | EliteBook 820 G2            | [e568c96372](https://linux-hardware.org/?probe=e568c96372) | Jun 25, 2022 |
| Sony          | VGN-FS415B                  | [00d146d9f4](https://linux-hardware.org/?probe=00d146d9f4) | Jun 24, 2022 |
| Medion        | Erazer P6661 MD60303        | [a678044765](https://linux-hardware.org/?probe=a678044765) | Jun 23, 2022 |
| Medion        | Erazer P6661 MD60303        | [babd561a16](https://linux-hardware.org/?probe=babd561a16) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f2b61e1e02](https://linux-hardware.org/?probe=f2b61e1e02) | Jun 23, 2022 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [13a427bd3b](https://linux-hardware.org/?probe=13a427bd3b) | Jun 23, 2022 |
| Razer         | Blade                       | [6c8b201cd9](https://linux-hardware.org/?probe=6c8b201cd9) | Jun 23, 2022 |
| Valve         | Jupiter                     | [213fbe4dd2](https://linux-hardware.org/?probe=213fbe4dd2) | Jun 22, 2022 |
| Lenovo        | V15-ADA 82C7                | [98350f1274](https://linux-hardware.org/?probe=98350f1274) | Jun 22, 2022 |
| HUAWEI        | BOD-WXX9                    | [b0d232a3c9](https://linux-hardware.org/?probe=b0d232a3c9) | Jun 20, 2022 |
| Sony          | VGN-UX27GN                  | [ed20bd45a4](https://linux-hardware.org/?probe=ed20bd45a4) | Jun 20, 2022 |
| IBM           | ThinkPad X40 2371LBG        | [e7610b86d4](https://linux-hardware.org/?probe=e7610b86d4) | Jun 20, 2022 |
| Lenovo        | ThinkPad T430 2349I46       | [3a7df4ea17](https://linux-hardware.org/?probe=3a7df4ea17) | Jun 20, 2022 |
| Lenovo        | Flex 2-15 20405             | [0cae0765c9](https://linux-hardware.org/?probe=0cae0765c9) | Jun 20, 2022 |
| HP            | 15                          | [61e6eddc93](https://linux-hardware.org/?probe=61e6eddc93) | Jun 20, 2022 |
| AVITA         | NS14A6                      | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Dell          | Inspiron 1720               | [8cc15a5651](https://linux-hardware.org/?probe=8cc15a5651) | Jun 19, 2022 |
| Lenovo        | ThinkPad T470 20HD000EUK    | [6cc2ca4099](https://linux-hardware.org/?probe=6cc2ca4099) | Jun 19, 2022 |
| Dell          | Inspiron 7370               | [e8a53b7f1b](https://linux-hardware.org/?probe=e8a53b7f1b) | Jun 18, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f399990b6e](https://linux-hardware.org/?probe=f399990b6e) | Jun 18, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | [41945e4369](https://linux-hardware.org/?probe=41945e4369) | Jun 18, 2022 |
| Sony          | VGN-P11Z_Q                  | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Acer          | Acadia V1.45                | [198f6e8fca](https://linux-hardware.org/?probe=198f6e8fca) | Jun 16, 2022 |
| HP            | ProBook 455 G3              | [507dcf06fc](https://linux-hardware.org/?probe=507dcf06fc) | Jun 16, 2022 |
| HP            | ProBook 455 G3              | [64794fafd4](https://linux-hardware.org/?probe=64794fafd4) | Jun 16, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | [8e0da08d4d](https://linux-hardware.org/?probe=8e0da08d4d) | Jun 15, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | [cf4df37657](https://linux-hardware.org/?probe=cf4df37657) | Jun 15, 2022 |
| Lenovo        | ThinkPad T430 2349AZ6       | [7369a5bd6b](https://linux-hardware.org/?probe=7369a5bd6b) | Jun 15, 2022 |
| MSI           | GP60 2OD                    | [6edff2c2ad](https://linux-hardware.org/?probe=6edff2c2ad) | Jun 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5b6f3d52c5](https://linux-hardware.org/?probe=5b6f3d52c5) | Jun 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [c1be5f13af](https://linux-hardware.org/?probe=c1be5f13af) | Jun 13, 2022 |
| Apple         | MacBookPro11,1              | [d40967b111](https://linux-hardware.org/?probe=d40967b111) | Jun 13, 2022 |
| Dell          | Studio XPS 1640             | [aac66b6b7b](https://linux-hardware.org/?probe=aac66b6b7b) | Jun 13, 2022 |
| HP            | EliteBook 820 G2            | [45ca271974](https://linux-hardware.org/?probe=45ca271974) | Jun 13, 2022 |
| Toshiba       | Satellite C55-C             | [6eef40304f](https://linux-hardware.org/?probe=6eef40304f) | Jun 13, 2022 |
| Acer          | Nitro AN515-52              | [72ea50523c](https://linux-hardware.org/?probe=72ea50523c) | Jun 13, 2022 |
| Acer          | Nitro AN515-52              | [05b64cc5de](https://linux-hardware.org/?probe=05b64cc5de) | Jun 12, 2022 |
| MSI           | P65 Creator 9SE             | [da30629803](https://linux-hardware.org/?probe=da30629803) | Jun 11, 2022 |
| Dell          | Inspiron 16 7610            | [9967260c3c](https://linux-hardware.org/?probe=9967260c3c) | Jun 11, 2022 |
| HP            | EliteBook 820 G2            | [0a0828f262](https://linux-hardware.org/?probe=0a0828f262) | Jun 11, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [83f46a355b](https://linux-hardware.org/?probe=83f46a355b) | Jun 11, 2022 |
| ASUSTek       | X555LAB                     | [8e47a3c188](https://linux-hardware.org/?probe=8e47a3c188) | Jun 10, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [53c2e38d14](https://linux-hardware.org/?probe=53c2e38d14) | Jun 10, 2022 |
| Toshiba       | Satellite L50-B             | [ce4d95c7bf](https://linux-hardware.org/?probe=ce4d95c7bf) | Jun 10, 2022 |
| Dell          | Latitude E7270              | [8d8f0db52c](https://linux-hardware.org/?probe=8d8f0db52c) | Jun 10, 2022 |
| HUAWEI        | NBD-WXX9                    | [b8e097f983](https://linux-hardware.org/?probe=b8e097f983) | Jun 10, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d29d3120fb](https://linux-hardware.org/?probe=d29d3120fb) | Jun 09, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Lenovo        | S130-11IGM 81J1             | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude E6510              | [083f1d576d](https://linux-hardware.org/?probe=083f1d576d) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | [737a4183c8](https://linux-hardware.org/?probe=737a4183c8) | Jun 07, 2022 |
| Apple         | MacBookPro11,4              | [d6662c5acf](https://linux-hardware.org/?probe=d6662c5acf) | Jun 07, 2022 |
| Lenovo        | ThinkPad T480 20L5000AUK    | [0bf67e4018](https://linux-hardware.org/?probe=0bf67e4018) | Jun 06, 2022 |
| Dell          | Latitude E6400              | [e4f54892c2](https://linux-hardware.org/?probe=e4f54892c2) | Jun 05, 2022 |
| HYPA          | FLUX                        | [76b0337ef8](https://linux-hardware.org/?probe=76b0337ef8) | Jun 05, 2022 |
| HP            | Laptop 15-bs1xx             | [e579d912d0](https://linux-hardware.org/?probe=e579d912d0) | Jun 04, 2022 |
| HP            | G62                         | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [d147abfc52](https://linux-hardware.org/?probe=d147abfc52) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [eaad038fde](https://linux-hardware.org/?probe=eaad038fde) | Jun 03, 2022 |
| Notebook      | NL40_50CU                   | [df0357703d](https://linux-hardware.org/?probe=df0357703d) | Jun 03, 2022 |
| Lenovo        | G780 2182                   | [878e602f7d](https://linux-hardware.org/?probe=878e602f7d) | Jun 02, 2022 |
| ASUSTek       | S550CA                      | [e683ab1965](https://linux-hardware.org/?probe=e683ab1965) | Jun 02, 2022 |
| Alienware     | M11x R2                     | [0b6837debb](https://linux-hardware.org/?probe=0b6837debb) | Jun 01, 2022 |
| Acer          | Aspire S3                   | [a78c44019e](https://linux-hardware.org/?probe=a78c44019e) | Jun 01, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM    | [8db5953984](https://linux-hardware.org/?probe=8db5953984) | Jun 01, 2022 |
| Dell          | G7 7700                     | [25e22bc243](https://linux-hardware.org/?probe=25e22bc243) | May 31, 2022 |
| HP            | Presario C500 (RT155EA#A... | [5eb3ee9cc2](https://linux-hardware.org/?probe=5eb3ee9cc2) | May 31, 2022 |
| Dell          | Latitude E6400              | [85d314bfd8](https://linux-hardware.org/?probe=85d314bfd8) | May 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [dc3ee2e520](https://linux-hardware.org/?probe=dc3ee2e520) | May 31, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [aae8744a5c](https://linux-hardware.org/?probe=aae8744a5c) | May 31, 2022 |
| Dell          | Latitude E6400              | [f5ae9fef9c](https://linux-hardware.org/?probe=f5ae9fef9c) | May 31, 2022 |
| HYPA          | FLUX                        | [8a69e3a34e](https://linux-hardware.org/?probe=8a69e3a34e) | May 31, 2022 |
| Alienware     | M11x R2                     | [4a364390a6](https://linux-hardware.org/?probe=4a364390a6) | May 31, 2022 |
| Alienware     | M11x R2                     | [87e8835eba](https://linux-hardware.org/?probe=87e8835eba) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [5a813419eb](https://linux-hardware.org/?probe=5a813419eb) | May 30, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| Razer         | Blade                       | [d7271bb7c4](https://linux-hardware.org/?probe=d7271bb7c4) | May 30, 2022 |
| Dell          | Latitude E6540              | [ece4d207f3](https://linux-hardware.org/?probe=ece4d207f3) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| Toshiba       | Satellite C850-1KN          | [60b2c12831](https://linux-hardware.org/?probe=60b2c12831) | May 29, 2022 |
| AZW           | GT-R                        | [7823df6a86](https://linux-hardware.org/?probe=7823df6a86) | May 29, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [8d120a2350](https://linux-hardware.org/?probe=8d120a2350) | May 28, 2022 |
| PC Special... | NH5x_7xDCx_DDx              | [bd70d45ed2](https://linux-hardware.org/?probe=bd70d45ed2) | May 28, 2022 |
| Dell          | XPS 13 9305                 | [5dc9e065e3](https://linux-hardware.org/?probe=5dc9e065e3) | May 27, 2022 |
| Dell          | Precision 5530              | [2ecf3390bf](https://linux-hardware.org/?probe=2ecf3390bf) | May 27, 2022 |
| HP            | ZBook 15 G5                 | [4f083f0d35](https://linux-hardware.org/?probe=4f083f0d35) | May 25, 2022 |
| Dell          | Inspiron 3721               | [d4af21adb8](https://linux-hardware.org/?probe=d4af21adb8) | May 25, 2022 |
| Alienware     | x17 R1                      | [a4cfdafe9d](https://linux-hardware.org/?probe=a4cfdafe9d) | May 25, 2022 |
| Toshiba       | TECRA A50-C                 | [60a580cb3b](https://linux-hardware.org/?probe=60a580cb3b) | May 25, 2022 |
| Acer          | Aspire S3                   | [d91145e274](https://linux-hardware.org/?probe=d91145e274) | May 25, 2022 |
| HP            | ZBook 15 G5                 | [fea70c6484](https://linux-hardware.org/?probe=fea70c6484) | May 24, 2022 |
| Toshiba       | PORTEGE R30-A               | [94cf17bcb6](https://linux-hardware.org/?probe=94cf17bcb6) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Dell          | XPS 15 9560                 | [7152b312be](https://linux-hardware.org/?probe=7152b312be) | May 23, 2022 |
| BOX           | W54_W94_W955TU,-T,-C        | [a36f54939d](https://linux-hardware.org/?probe=a36f54939d) | May 23, 2022 |
| Entroware     | Apollo                      | [30881be24b](https://linux-hardware.org/?probe=30881be24b) | May 23, 2022 |
| Valve         | Jupiter                     | [7d3f9c0a5f](https://linux-hardware.org/?probe=7d3f9c0a5f) | May 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [fe1d187774](https://linux-hardware.org/?probe=fe1d187774) | May 22, 2022 |
| Dell          | XPS 13 9360                 | [47c446b3d8](https://linux-hardware.org/?probe=47c446b3d8) | May 22, 2022 |
| Lenovo        | S21e-20 80M4                | [90d0bb5bc0](https://linux-hardware.org/?probe=90d0bb5bc0) | May 22, 2022 |
| Lenovo        | S21e-20 80M4                | [48047cdaf6](https://linux-hardware.org/?probe=48047cdaf6) | May 22, 2022 |
| Valve         | Jupiter                     | [595b06f6c9](https://linux-hardware.org/?probe=595b06f6c9) | May 22, 2022 |
| Apple         | MacBookPro10,1              | [5bf86728dc](https://linux-hardware.org/?probe=5bf86728dc) | May 22, 2022 |
| Acer          | Aspire ES1-523              | [e856d4589a](https://linux-hardware.org/?probe=e856d4589a) | May 21, 2022 |
| Lenovo        | Z50-75 80EC                 | [adddbe7947](https://linux-hardware.org/?probe=adddbe7947) | May 21, 2022 |
| Entroware     | Triton                      | [2bfa3e5cc8](https://linux-hardware.org/?probe=2bfa3e5cc8) | May 20, 2022 |
| HP            | Laptop 15-bs0xx             | [5c989cad8d](https://linux-hardware.org/?probe=5c989cad8d) | May 20, 2022 |
| Lenovo        | V145-15AST 81MT             | [ab767eaa59](https://linux-hardware.org/?probe=ab767eaa59) | May 19, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [e30e3da709](https://linux-hardware.org/?probe=e30e3da709) | May 18, 2022 |
| Acer          | Aspire A315-21              | [8f9f8c2634](https://linux-hardware.org/?probe=8f9f8c2634) | May 18, 2022 |
| HP            | Pavilion Notebook           | [2e663e698c](https://linux-hardware.org/?probe=2e663e698c) | May 18, 2022 |
| Notebook      | NS50_70MU                   | [382192bd2c](https://linux-hardware.org/?probe=382192bd2c) | May 18, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| MSI           | Stealth GS66 12UGS          | [f92e29b330](https://linux-hardware.org/?probe=f92e29b330) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [b1afeba24a](https://linux-hardware.org/?probe=b1afeba24a) | May 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [06afc33451](https://linux-hardware.org/?probe=06afc33451) | May 16, 2022 |
| HP            | ZBook 15 G6                 | [6c433b3b60](https://linux-hardware.org/?probe=6c433b3b60) | May 16, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [ee54db9f9e](https://linux-hardware.org/?probe=ee54db9f9e) | May 16, 2022 |
| HP            | Unknown                     | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [0f70996b58](https://linux-hardware.org/?probe=0f70996b58) | May 15, 2022 |
| HP            | ProBook 6570b               | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Dell          | XPS 13 9305                 | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | Inspiron 1750               | [b37b4cdbbb](https://linux-hardware.org/?probe=b37b4cdbbb) | May 15, 2022 |
| Dell          | XPS 13 9305                 | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| Dell          | Inspiron N5110              | [2555fd899e](https://linux-hardware.org/?probe=2555fd899e) | May 15, 2022 |
| Fujitsu Si... | LIFEBOOK S7110              | [8586a581d0](https://linux-hardware.org/?probe=8586a581d0) | May 15, 2022 |
| Notebook      | NLx0MU                      | [b46632bd9a](https://linux-hardware.org/?probe=b46632bd9a) | May 14, 2022 |
| Lenovo        | ThinkPad T470 20HES1RB06    | [0d115ce977](https://linux-hardware.org/?probe=0d115ce977) | May 14, 2022 |
| HP            | Pavilion Notebook           | [44952d0fff](https://linux-hardware.org/?probe=44952d0fff) | May 13, 2022 |
| Star Labs     | Lite                        | [dbe031aada](https://linux-hardware.org/?probe=dbe031aada) | May 13, 2022 |
| AMI           | Cherry Trail CR             | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| Dell          | Precision M6600             | [730205ec1e](https://linux-hardware.org/?probe=730205ec1e) | May 11, 2022 |
| Lenovo        | ThinkPad T480 20L6S5M40M    | [f2213829f0](https://linux-hardware.org/?probe=f2213829f0) | May 11, 2022 |
| Acer          | Aspire E1-571               | [72b102de04](https://linux-hardware.org/?probe=72b102de04) | May 10, 2022 |
| HP            | EliteBook 2560p             | [debc8c7d47](https://linux-hardware.org/?probe=debc8c7d47) | May 10, 2022 |
| Acer          | Aspire E5-551               | [bef0e3659e](https://linux-hardware.org/?probe=bef0e3659e) | May 10, 2022 |
| ASUSTek       | N751JK                      | [bfdc40105f](https://linux-hardware.org/?probe=bfdc40105f) | May 10, 2022 |
| HP            | EliteBook 2730p             | [d4c5b7824d](https://linux-hardware.org/?probe=d4c5b7824d) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [20eb5bfb9f](https://linux-hardware.org/?probe=20eb5bfb9f) | May 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Clevo         | W55xEU                      | [7bdef594e1](https://linux-hardware.org/?probe=7bdef594e1) | May 09, 2022 |
| HP            | ENVY 17                     | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Acer          | Aspire 6930G                | [49228d9f61](https://linux-hardware.org/?probe=49228d9f61) | May 08, 2022 |
| Acer          | Aspire 6930G                | [912dbb8280](https://linux-hardware.org/?probe=912dbb8280) | May 08, 2022 |
| HUAWEI        | BOD-WXX9                    | [b0b389263a](https://linux-hardware.org/?probe=b0b389263a) | May 08, 2022 |
| Lenovo        | IdeaPad Z580                | [a0751c16d5](https://linux-hardware.org/?probe=a0751c16d5) | May 08, 2022 |
| Dell          | Inspiron 7501               | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| MSI           | GE63 Raider RGB 8RE         | [34bd31c9f9](https://linux-hardware.org/?probe=34bd31c9f9) | May 07, 2022 |
| HP            | ZBook 15 G5                 | [4a3960f047](https://linux-hardware.org/?probe=4a3960f047) | May 07, 2022 |
| HP            | ProBook 430 G4              | [cae67b53da](https://linux-hardware.org/?probe=cae67b53da) | May 06, 2022 |
| Acer          | Swift SF314-41              | [3dbf93ec7f](https://linux-hardware.org/?probe=3dbf93ec7f) | May 06, 2022 |
| Dell          | Inspiron 1525               | [67dbf0ac88](https://linux-hardware.org/?probe=67dbf0ac88) | May 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8aadfc9dc1](https://linux-hardware.org/?probe=8aadfc9dc1) | May 04, 2022 |
| Acer          | Aspire A515-45              | [e5f3e5b086](https://linux-hardware.org/?probe=e5f3e5b086) | May 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV0C     | [4ce87e4da1](https://linux-hardware.org/?probe=4ce87e4da1) | May 04, 2022 |
| HP            | EliteBook 820 G2            | [0e78293e95](https://linux-hardware.org/?probe=0e78293e95) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [584ec1055a](https://linux-hardware.org/?probe=584ec1055a) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [2e4fdc00b2](https://linux-hardware.org/?probe=2e4fdc00b2) | May 03, 2022 |
| ASUSTek       | E200HA                      | [399a40cb14](https://linux-hardware.org/?probe=399a40cb14) | May 03, 2022 |
| Lenovo        | Z50-75 80EC                 | [d16211782e](https://linux-hardware.org/?probe=d16211782e) | May 03, 2022 |
| Dell          | Latitude E7470              | [7991dfd7a5](https://linux-hardware.org/?probe=7991dfd7a5) | May 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [6a9dfa32d3](https://linux-hardware.org/?probe=6a9dfa32d3) | May 02, 2022 |
| Acer          | Aspire A515-45              | [8cf5364699](https://linux-hardware.org/?probe=8cf5364699) | May 02, 2022 |
| Toshiba       | Satellite P850              | [8e97662196](https://linux-hardware.org/?probe=8e97662196) | May 02, 2022 |
| Acer          | Aspire V5-573P              | [b64d1453d5](https://linux-hardware.org/?probe=b64d1453d5) | May 02, 2022 |
| ASUSTek       | UX310UA                     | [80fce5caed](https://linux-hardware.org/?probe=80fce5caed) | May 01, 2022 |
| Dell          | XPS 13 9310                 | [03b461596c](https://linux-hardware.org/?probe=03b461596c) | May 01, 2022 |
| Dell          | XPS 15 9570                 | [133b6670de](https://linux-hardware.org/?probe=133b6670de) | May 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [ab553d3a2f](https://linux-hardware.org/?probe=ab553d3a2f) | May 01, 2022 |
| Acer          | Aspire A515-45              | [a5fd51cc39](https://linux-hardware.org/?probe=a5fd51cc39) | May 01, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [3589ada8b3](https://linux-hardware.org/?probe=3589ada8b3) | Apr 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [31b081b116](https://linux-hardware.org/?probe=31b081b116) | Apr 30, 2022 |
| Valve         | Jupiter                     | [1c826aed5e](https://linux-hardware.org/?probe=1c826aed5e) | Apr 30, 2022 |
| Lenovo        | Z50-75 80EC                 | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| Lenovo        | ThinkPad T450 20BV001YMS    | [f38b762c83](https://linux-hardware.org/?probe=f38b762c83) | Apr 29, 2022 |
| Toshiba       | Satellite Pro R50-B         | [6a8bdd387c](https://linux-hardware.org/?probe=6a8bdd387c) | Apr 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [df82c076b8](https://linux-hardware.org/?probe=df82c076b8) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [34015c4874](https://linux-hardware.org/?probe=34015c4874) | Apr 29, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [06ef070e40](https://linux-hardware.org/?probe=06ef070e40) | Apr 28, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [8ef803f8c9](https://linux-hardware.org/?probe=8ef803f8c9) | Apr 28, 2022 |
| ASUSTek       | FX503VM                     | [c227966510](https://linux-hardware.org/?probe=c227966510) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | [1275aa643d](https://linux-hardware.org/?probe=1275aa643d) | Apr 27, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [37501fa5f3](https://linux-hardware.org/?probe=37501fa5f3) | Apr 27, 2022 |
| Dell          | Inspiron 5415               | [5edac5d5a6](https://linux-hardware.org/?probe=5edac5d5a6) | Apr 27, 2022 |
| Notebook      | W130SV                      | [a88535a3a5](https://linux-hardware.org/?probe=a88535a3a5) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [d23e7110f6](https://linux-hardware.org/?probe=d23e7110f6) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [3390e01a9c](https://linux-hardware.org/?probe=3390e01a9c) | Apr 27, 2022 |
| PC Special... | NJ50_70CU                   | [a9b4399cad](https://linux-hardware.org/?probe=a9b4399cad) | Apr 26, 2022 |
| MSI           | GF63 Thin 10SC              | [bc3cbdbc1f](https://linux-hardware.org/?probe=bc3cbdbc1f) | Apr 26, 2022 |
| Acer          | NC-E5-573-36PM              | [a98a807776](https://linux-hardware.org/?probe=a98a807776) | Apr 26, 2022 |
| MSI           | GP66 Leopard 11UH           | [549c216d66](https://linux-hardware.org/?probe=549c216d66) | Apr 26, 2022 |
| Dell          | XPS 13 9310                 | [1f95a73d57](https://linux-hardware.org/?probe=1f95a73d57) | Apr 26, 2022 |
| Apple         | MacBookPro11,1              | [a8626eb701](https://linux-hardware.org/?probe=a8626eb701) | Apr 26, 2022 |
| Acer          | Aspire E1-571               | [35824f9b37](https://linux-hardware.org/?probe=35824f9b37) | Apr 25, 2022 |
| HP            | Pavilion dv6                | [83093f24ef](https://linux-hardware.org/?probe=83093f24ef) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fbb2b97e0f](https://linux-hardware.org/?probe=fbb2b97e0f) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| Purism        | Librem 14                   | [9d078217f1](https://linux-hardware.org/?probe=9d078217f1) | Apr 23, 2022 |
| Acer          | Swift SF315-52              | [089d81a936](https://linux-hardware.org/?probe=089d81a936) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [0ca0b999d6](https://linux-hardware.org/?probe=0ca0b999d6) | Apr 23, 2022 |
| HP            | Pavilion g6                 | [796bf7f467](https://linux-hardware.org/?probe=796bf7f467) | Apr 23, 2022 |
| Dell          | Latitude E7450              | [5ce1623306](https://linux-hardware.org/?probe=5ce1623306) | Apr 22, 2022 |
| HP            | Pavilion dv6                | [16e2c4e6d3](https://linux-hardware.org/?probe=16e2c4e6d3) | Apr 22, 2022 |
| CyberPower... | Tracer II                   | [4582a60770](https://linux-hardware.org/?probe=4582a60770) | Apr 21, 2022 |
| Dynabook      | PORTEGE X30L-J              | [5894fd3a34](https://linux-hardware.org/?probe=5894fd3a34) | Apr 21, 2022 |
| Dell          | Latitude D430               | [00ddfbe46f](https://linux-hardware.org/?probe=00ddfbe46f) | Apr 20, 2022 |
| Dixonsxp      | Unknown                     | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| HP            | Notebook                    | [f6d84934cd](https://linux-hardware.org/?probe=f6d84934cd) | Apr 19, 2022 |
| Lenovo        | IdeaPad S540-15IML D 81N... | [58dc7c7bf2](https://linux-hardware.org/?probe=58dc7c7bf2) | Apr 19, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [6db9a3dea0](https://linux-hardware.org/?probe=6db9a3dea0) | Apr 18, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [c7f2c2e71c](https://linux-hardware.org/?probe=c7f2c2e71c) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [42db396ee8](https://linux-hardware.org/?probe=42db396ee8) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [4dc4e0af40](https://linux-hardware.org/?probe=4dc4e0af40) | Apr 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | [9868b4e681](https://linux-hardware.org/?probe=9868b4e681) | Apr 17, 2022 |
| Valve         | Jupiter                     | [4f23fab4fd](https://linux-hardware.org/?probe=4f23fab4fd) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| Lenovo        | ThinkPad L440 20ASA02800    | [697a90ffa2](https://linux-hardware.org/?probe=697a90ffa2) | Apr 16, 2022 |
| Dell          | Inspiron N5110              | [5ae4706be7](https://linux-hardware.org/?probe=5ae4706be7) | Apr 15, 2022 |
| Toshiba       | Satellite P50t-A            | [f2eef93c50](https://linux-hardware.org/?probe=f2eef93c50) | Apr 15, 2022 |
| HP            | ENVY 13                     | [4b0b543bdf](https://linux-hardware.org/?probe=4b0b543bdf) | Apr 14, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [4b3cedca6f](https://linux-hardware.org/?probe=4b3cedca6f) | Apr 14, 2022 |
| Framework     | Laptop                      | [8734154fb6](https://linux-hardware.org/?probe=8734154fb6) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [9e6fc630f4](https://linux-hardware.org/?probe=9e6fc630f4) | Apr 14, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [c9e8c79a2e](https://linux-hardware.org/?probe=c9e8c79a2e) | Apr 14, 2022 |
| Framework     | Laptop                      | [2550bb5cd7](https://linux-hardware.org/?probe=2550bb5cd7) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [960f707d0f](https://linux-hardware.org/?probe=960f707d0f) | Apr 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [9dd2675f34](https://linux-hardware.org/?probe=9dd2675f34) | Apr 14, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [260c012f44](https://linux-hardware.org/?probe=260c012f44) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | [89de41a490](https://linux-hardware.org/?probe=89de41a490) | Apr 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0517baf6ee](https://linux-hardware.org/?probe=0517baf6ee) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 429136G       | [92555ffe91](https://linux-hardware.org/?probe=92555ffe91) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [58ef1f3594](https://linux-hardware.org/?probe=58ef1f3594) | Apr 13, 2022 |
| HP            | EliteBook 840 G2            | [ec9869d115](https://linux-hardware.org/?probe=ec9869d115) | Apr 13, 2022 |
| Dell          | XPS 15 9500                 | [986cb2363c](https://linux-hardware.org/?probe=986cb2363c) | Apr 13, 2022 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | [a31cc5eb3b](https://linux-hardware.org/?probe=a31cc5eb3b) | Apr 13, 2022 |
| Toshiba       | TECRA X40-D                 | [d18cfd17bb](https://linux-hardware.org/?probe=d18cfd17bb) | Apr 13, 2022 |
| LG Electro... | 16Z90P-K.AA78A1             | [f7d44e9cd6](https://linux-hardware.org/?probe=f7d44e9cd6) | Apr 13, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [cfa1e38deb](https://linux-hardware.org/?probe=cfa1e38deb) | Apr 13, 2022 |
| Dell          | Precision 5530              | [3c4cc67cc4](https://linux-hardware.org/?probe=3c4cc67cc4) | Apr 13, 2022 |
| HP            | Pavilion g6                 | [44035cfa83](https://linux-hardware.org/?probe=44035cfa83) | Apr 13, 2022 |
| Dell          | Vostro 5515                 | [710d07a9bd](https://linux-hardware.org/?probe=710d07a9bd) | Apr 12, 2022 |
| Dell          | Vostro 5515                 | [677234b8b8](https://linux-hardware.org/?probe=677234b8b8) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| Dell          | Inspiron 5415               | [6c85a524a1](https://linux-hardware.org/?probe=6c85a524a1) | Apr 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [fcfc2b41a7](https://linux-hardware.org/?probe=fcfc2b41a7) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [34b32b5b14](https://linux-hardware.org/?probe=34b32b5b14) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f4d9933ef2](https://linux-hardware.org/?probe=f4d9933ef2) | Apr 10, 2022 |
| Acer          | Aspire E1-571               | [d7170319fc](https://linux-hardware.org/?probe=d7170319fc) | Apr 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [8a0974e971](https://linux-hardware.org/?probe=8a0974e971) | Apr 10, 2022 |
| HP            | Laptop 15-da0xxx            | [7187b2e6ee](https://linux-hardware.org/?probe=7187b2e6ee) | Apr 10, 2022 |
| ASUSTek       | UX310UA                     | [732364c253](https://linux-hardware.org/?probe=732364c253) | Apr 09, 2022 |
| Advent        | Tacto Purple                | [5ad7851c7a](https://linux-hardware.org/?probe=5ad7851c7a) | Apr 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [919af587bb](https://linux-hardware.org/?probe=919af587bb) | Apr 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [3b16991947](https://linux-hardware.org/?probe=3b16991947) | Apr 08, 2022 |
| CyberPower... | Tracer II                   | [735f98bbb9](https://linux-hardware.org/?probe=735f98bbb9) | Apr 08, 2022 |
| Dell          | G7 7700                     | [86fff99f90](https://linux-hardware.org/?probe=86fff99f90) | Apr 08, 2022 |
| Acer          | Aspire A315-31              | [afd87f36b2](https://linux-hardware.org/?probe=afd87f36b2) | Apr 08, 2022 |
| Lenovo        | Flex 2-15 20405             | [b7d6ae3171](https://linux-hardware.org/?probe=b7d6ae3171) | Apr 08, 2022 |
| Getac         | S400                        | [7f8a76a614](https://linux-hardware.org/?probe=7f8a76a614) | Apr 08, 2022 |
| Acer          | Aspire A315-54              | [596a2a878c](https://linux-hardware.org/?probe=596a2a878c) | Apr 08, 2022 |
| ARKA          | BOOK                        | [44809cec7b](https://linux-hardware.org/?probe=44809cec7b) | Apr 06, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [bb750c0f56](https://linux-hardware.org/?probe=bb750c0f56) | Apr 06, 2022 |
| Dell          | Inspiron 16 7610            | [8b2c078f25](https://linux-hardware.org/?probe=8b2c078f25) | Apr 06, 2022 |
| MSI           | GL63 9SD                    | [6b4f4b5c10](https://linux-hardware.org/?probe=6b4f4b5c10) | Apr 06, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [943191da55](https://linux-hardware.org/?probe=943191da55) | Apr 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [952a71b37e](https://linux-hardware.org/?probe=952a71b37e) | Apr 04, 2022 |
| Dell          | Latitude E6530              | [a63f363043](https://linux-hardware.org/?probe=a63f363043) | Apr 04, 2022 |
| Dell          | Inspiron 7559               | [4efbcf88a2](https://linux-hardware.org/?probe=4efbcf88a2) | Apr 04, 2022 |
| Lenovo        | ThinkPad T410 2522AC1       | [b22a799f67](https://linux-hardware.org/?probe=b22a799f67) | Apr 04, 2022 |
| Dell          | Inspiron 3576               | [b768d18e12](https://linux-hardware.org/?probe=b768d18e12) | Apr 04, 2022 |
| Sony          | VPCEB4L1E                   | [358783a077](https://linux-hardware.org/?probe=358783a077) | Apr 03, 2022 |
| Valve         | Jupiter                     | [ec05067a1d](https://linux-hardware.org/?probe=ec05067a1d) | Apr 03, 2022 |
| HP            | Notebook                    | [e1af57dc16](https://linux-hardware.org/?probe=e1af57dc16) | Apr 02, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | [82ec2ff5f6](https://linux-hardware.org/?probe=82ec2ff5f6) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | [7aefa77b4b](https://linux-hardware.org/?probe=7aefa77b4b) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [e81da10444](https://linux-hardware.org/?probe=e81da10444) | Apr 01, 2022 |
| Toshiba       | dynabook R73/A              | [42b60c90c7](https://linux-hardware.org/?probe=42b60c90c7) | Apr 01, 2022 |
| HP            | ProBook 6570b               | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| HP            | Laptop 14-cm0xxx            | [01f7a198c5](https://linux-hardware.org/?probe=01f7a198c5) | Mar 31, 2022 |
| Apple         | MacBookPro6,1               | [c55872162d](https://linux-hardware.org/?probe=c55872162d) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cc95f0e3ab](https://linux-hardware.org/?probe=cc95f0e3ab) | Mar 31, 2022 |
| Acer          | Aspire A315-21              | [b0bacf15b5](https://linux-hardware.org/?probe=b0bacf15b5) | Mar 31, 2022 |
| System76      | Lemur Pro                   | [34b16b2584](https://linux-hardware.org/?probe=34b16b2584) | Mar 31, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [b47301d663](https://linux-hardware.org/?probe=b47301d663) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [9db5eb67b3](https://linux-hardware.org/?probe=9db5eb67b3) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [90ec98a922](https://linux-hardware.org/?probe=90ec98a922) | Mar 31, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [05c02cbe41](https://linux-hardware.org/?probe=05c02cbe41) | Mar 31, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [10fe068865](https://linux-hardware.org/?probe=10fe068865) | Mar 30, 2022 |
| ASUSTek       | FX503VM                     | [1f2167e189](https://linux-hardware.org/?probe=1f2167e189) | Mar 30, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [48e596f082](https://linux-hardware.org/?probe=48e596f082) | Mar 30, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fab15ee731](https://linux-hardware.org/?probe=fab15ee731) | Mar 30, 2022 |
| Apple         | MacBookPro14,3              | [33107e3ea3](https://linux-hardware.org/?probe=33107e3ea3) | Mar 29, 2022 |
| Dell          | XPS 15 9500                 | [8cf6c58236](https://linux-hardware.org/?probe=8cf6c58236) | Mar 29, 2022 |
| Dell          | XPS 17 9710                 | [461d175c44](https://linux-hardware.org/?probe=461d175c44) | Mar 28, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [2b7fe29925](https://linux-hardware.org/?probe=2b7fe29925) | Mar 28, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [323ca65327](https://linux-hardware.org/?probe=323ca65327) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | [ecf7b98552](https://linux-hardware.org/?probe=ecf7b98552) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| MSI           | GE63 Raider RGB 8RE         | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| MSI           | GL63 9SD                    | [d82d8f7857](https://linux-hardware.org/?probe=d82d8f7857) | Mar 25, 2022 |
| Google        | Banon                       | [422e2dc398](https://linux-hardware.org/?probe=422e2dc398) | Mar 24, 2022 |
| Dell          | Vostro 5515                 | [b3f93f17bb](https://linux-hardware.org/?probe=b3f93f17bb) | Mar 24, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [c9775b9b30](https://linux-hardware.org/?probe=c9775b9b30) | Mar 23, 2022 |
| Valve         | Jupiter                     | [d181a912af](https://linux-hardware.org/?probe=d181a912af) | Mar 23, 2022 |
| Apple         | MacBookAir6,2               | [7c31f8a6ac](https://linux-hardware.org/?probe=7c31f8a6ac) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [713ff9dcb8](https://linux-hardware.org/?probe=713ff9dcb8) | Mar 23, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [5b74db2557](https://linux-hardware.org/?probe=5b74db2557) | Mar 22, 2022 |
| Lenovo        | Z50-70 20354                | [b03762a80b](https://linux-hardware.org/?probe=b03762a80b) | Mar 22, 2022 |
| HP            | Pavilion g7                 | [9d4d9b0c34](https://linux-hardware.org/?probe=9d4d9b0c34) | Mar 22, 2022 |
| HP            | Pavilion g6                 | [3568c4160a](https://linux-hardware.org/?probe=3568c4160a) | Mar 22, 2022 |
| Sony          | SVP1321B4E                  | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| HP            | 255 G7 Notebook PC          | [ce0d6584b2](https://linux-hardware.org/?probe=ce0d6584b2) | Mar 21, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [b708e920f3](https://linux-hardware.org/?probe=b708e920f3) | Mar 21, 2022 |
| HP            | Laptop 15-db0xxx            | [e0f906e560](https://linux-hardware.org/?probe=e0f906e560) | Mar 21, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [543e44c95a](https://linux-hardware.org/?probe=543e44c95a) | Mar 20, 2022 |
| Dell          | Latitude 7490               | [0799e0955b](https://linux-hardware.org/?probe=0799e0955b) | Mar 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7ad353e47f](https://linux-hardware.org/?probe=7ad353e47f) | Mar 20, 2022 |
| Lenovo        | G510 20238                  | [2de5cec732](https://linux-hardware.org/?probe=2de5cec732) | Mar 20, 2022 |
| HP            | G61                         | [833491ff37](https://linux-hardware.org/?probe=833491ff37) | Mar 19, 2022 |
| Dell          | Latitude 3540               | [6d95fdc85c](https://linux-hardware.org/?probe=6d95fdc85c) | Mar 19, 2022 |
| Dell          | Inspiron 5415               | [eab20e919d](https://linux-hardware.org/?probe=eab20e919d) | Mar 19, 2022 |
| HP            | Pavilion Notebook           | [02e461a122](https://linux-hardware.org/?probe=02e461a122) | Mar 19, 2022 |
| Dell          | XPS 15 7590                 | [df2a40363b](https://linux-hardware.org/?probe=df2a40363b) | Mar 18, 2022 |
| Valve         | Jupiter                     | [0b6a21cf35](https://linux-hardware.org/?probe=0b6a21cf35) | Mar 18, 2022 |
| Dell          | Inspiron 7577               | [1b90446e3a](https://linux-hardware.org/?probe=1b90446e3a) | Mar 17, 2022 |
| HP            | Presario CQ57               | [052d5a695c](https://linux-hardware.org/?probe=052d5a695c) | Mar 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9S02U0... | [f255ab814c](https://linux-hardware.org/?probe=f255ab814c) | Mar 17, 2022 |
| Apple         | MacBookPro1,1               | [4add06ac06](https://linux-hardware.org/?probe=4add06ac06) | Mar 17, 2022 |
| HP            | EliteBook 2740p             | [8cfadb8983](https://linux-hardware.org/?probe=8cfadb8983) | Mar 16, 2022 |
| Toshiba       | Satellite Pro C50-A-1E6     | [ad8e612da5](https://linux-hardware.org/?probe=ad8e612da5) | Mar 15, 2022 |
| Apple         | MacBookPro10,1              | [6b3e010244](https://linux-hardware.org/?probe=6b3e010244) | Mar 15, 2022 |
| Google        | Samus                       | [9e3da82a58](https://linux-hardware.org/?probe=9e3da82a58) | Mar 14, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [4d32980028](https://linux-hardware.org/?probe=4d32980028) | Mar 14, 2022 |
| Apple         | MacBookPro1,1               | [1f948586ca](https://linux-hardware.org/?probe=1f948586ca) | Mar 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [ef6a4d20a7](https://linux-hardware.org/?probe=ef6a4d20a7) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z580                | [b5a56fb84b](https://linux-hardware.org/?probe=b5a56fb84b) | Mar 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| Alienware     | M14xR1                      | [b98eb5e7cc](https://linux-hardware.org/?probe=b98eb5e7cc) | Mar 13, 2022 |
| MSI           | GP66 Leopard 11UH           | [1e2a1731f7](https://linux-hardware.org/?probe=1e2a1731f7) | Mar 13, 2022 |
| Lenovo        | ThinkPad T490 20N2S1CV00    | [b013642d11](https://linux-hardware.org/?probe=b013642d11) | Mar 12, 2022 |
| Packard Be... | EasyNote TN36               | [0af6d015a3](https://linux-hardware.org/?probe=0af6d015a3) | Mar 12, 2022 |
| HP            | EliteBook 2560p             | [b12027d55b](https://linux-hardware.org/?probe=b12027d55b) | Mar 12, 2022 |
| Jumper        | EZbook                      | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Toshiba       | Satellite L350D             | [9e9c1b741b](https://linux-hardware.org/?probe=9e9c1b741b) | Mar 11, 2022 |
| Dell          | Inspiron 5415               | [7adb5a975b](https://linux-hardware.org/?probe=7adb5a975b) | Mar 11, 2022 |
| Apple         | MacBookPro11,4              | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Clevo         | P15xEMx                     | [08e970fd6c](https://linux-hardware.org/?probe=08e970fd6c) | Mar 10, 2022 |
| Dell          | Latitude 7420               | [af5f1055fe](https://linux-hardware.org/?probe=af5f1055fe) | Mar 10, 2022 |
| Dell          | Vostro 3560                 | [42f4724835](https://linux-hardware.org/?probe=42f4724835) | Mar 09, 2022 |
| Apple         | MacBookPro1,1               | [6563e94c95](https://linux-hardware.org/?probe=6563e94c95) | Mar 09, 2022 |
| Apple         | MacBookPro11,4              | [f3eb9f941a](https://linux-hardware.org/?probe=f3eb9f941a) | Mar 08, 2022 |
| HP            | Stream Notebook             | [ef7dc93a65](https://linux-hardware.org/?probe=ef7dc93a65) | Mar 08, 2022 |
| Notebook      | PCx0Dx                      | [2819c9e72e](https://linux-hardware.org/?probe=2819c9e72e) | Mar 07, 2022 |
| Notebook      | PCx0Dx                      | [38c484b64e](https://linux-hardware.org/?probe=38c484b64e) | Mar 07, 2022 |
| Acer          | TP-W700-53334G12            | [61d5d1483d](https://linux-hardware.org/?probe=61d5d1483d) | Mar 07, 2022 |
| HP            | 255 G3                      | [cd0bde08da](https://linux-hardware.org/?probe=cd0bde08da) | Mar 07, 2022 |
| Toshiba       | Satellite Pro C50-A-1E5     | [ac3b4acda7](https://linux-hardware.org/?probe=ac3b4acda7) | Mar 06, 2022 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [35f0ef9cb6](https://linux-hardware.org/?probe=35f0ef9cb6) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ca93876528](https://linux-hardware.org/?probe=ca93876528) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | [2afe92c38f](https://linux-hardware.org/?probe=2afe92c38f) | Mar 06, 2022 |
| Dell          | XPS 13 9380                 | [efc6123d49](https://linux-hardware.org/?probe=efc6123d49) | Mar 06, 2022 |
| Acer          | TP-W700-53334G12            | [cf6bad7b5c](https://linux-hardware.org/?probe=cf6bad7b5c) | Mar 05, 2022 |
| HP            | EliteBook 2560p             | [0d4a567ac4](https://linux-hardware.org/?probe=0d4a567ac4) | Mar 05, 2022 |
| Acer          | Aspire E1-522               | [1d4f09c200](https://linux-hardware.org/?probe=1d4f09c200) | Mar 05, 2022 |
| Unknown       | Unknown                     | [c447074d2b](https://linux-hardware.org/?probe=c447074d2b) | Mar 05, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [2a1c30169a](https://linux-hardware.org/?probe=2a1c30169a) | Mar 05, 2022 |
| Jumper        | EZbook                      | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [61191e0c42](https://linux-hardware.org/?probe=61191e0c42) | Mar 04, 2022 |
| MSI           | GS60 6QE                    | [caec25c98b](https://linux-hardware.org/?probe=caec25c98b) | Mar 04, 2022 |
| MSI           | GS60 6QE                    | [3e98f59715](https://linux-hardware.org/?probe=3e98f59715) | Mar 04, 2022 |
| Apple         | MacBookPro11,4              | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [134d1cf65b](https://linux-hardware.org/?probe=134d1cf65b) | Mar 03, 2022 |
| HP            | 15                          | [1d090e42e2](https://linux-hardware.org/?probe=1d090e42e2) | Mar 03, 2022 |
| HP            | 15                          | [c9a13c5150](https://linux-hardware.org/?probe=c9a13c5150) | Mar 03, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [30565cb2f9](https://linux-hardware.org/?probe=30565cb2f9) | Mar 03, 2022 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [806101c474](https://linux-hardware.org/?probe=806101c474) | Mar 03, 2022 |
| Dell          | Latitude E6530              | [f13c84346e](https://linux-hardware.org/?probe=f13c84346e) | Mar 02, 2022 |
| Dell          | Inspiron 16 7610            | [da9f6479f1](https://linux-hardware.org/?probe=da9f6479f1) | Mar 02, 2022 |
| Jumper        | EZbook                      | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Apple         | MacBookPro9,2               | [7fc2d5d090](https://linux-hardware.org/?probe=7fc2d5d090) | Mar 02, 2022 |
| HP            | Unknown                     | [4c84c909eb](https://linux-hardware.org/?probe=4c84c909eb) | Mar 02, 2022 |
| MSI           | GF63 Thin 9SC               | [3327e56999](https://linux-hardware.org/?probe=3327e56999) | Mar 01, 2022 |
| MSI           | GF63 Thin 9SC               | [5e3f7f344c](https://linux-hardware.org/?probe=5e3f7f344c) | Mar 01, 2022 |
| HP            | ProBook 4340s               | [2b4257b1c2](https://linux-hardware.org/?probe=2b4257b1c2) | Mar 01, 2022 |
| Apple         | MacBookAir6,2               | [2660f37932](https://linux-hardware.org/?probe=2660f37932) | Mar 01, 2022 |
| Acer          | Aspire E1-522               | [4245cd910a](https://linux-hardware.org/?probe=4245cd910a) | Feb 28, 2022 |
| Acer          | Aspire A515-45              | [f2e18241da](https://linux-hardware.org/?probe=f2e18241da) | Feb 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c4b3104959](https://linux-hardware.org/?probe=c4b3104959) | Feb 28, 2022 |
| Notebook      | P15SM-A                     | [dfe7b95d25](https://linux-hardware.org/?probe=dfe7b95d25) | Feb 27, 2022 |
| Acer          | TP-W700-53334G12            | [4f274ebb66](https://linux-hardware.org/?probe=4f274ebb66) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | [24861666e2](https://linux-hardware.org/?probe=24861666e2) | Feb 27, 2022 |
| Entroware     | Hybris                      | [e7628c79c3](https://linux-hardware.org/?probe=e7628c79c3) | Feb 27, 2022 |
| Acer          | Swift SF114-34              | [49fb58c88b](https://linux-hardware.org/?probe=49fb58c88b) | Feb 27, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4365bdf905](https://linux-hardware.org/?probe=4365bdf905) | Feb 26, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [f719a93837](https://linux-hardware.org/?probe=f719a93837) | Feb 25, 2022 |
| Lenovo        | ThinkPad T410 2537A12       | [ec01c23749](https://linux-hardware.org/?probe=ec01c23749) | Feb 24, 2022 |
| SLIMBOOK      | TITAN                       | [182750aa6b](https://linux-hardware.org/?probe=182750aa6b) | Feb 23, 2022 |
| Google        | Edgar                       | [46f5948f03](https://linux-hardware.org/?probe=46f5948f03) | Feb 23, 2022 |
| Acer          | AO725                       | [65d4162ffe](https://linux-hardware.org/?probe=65d4162ffe) | Feb 23, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [742af9249b](https://linux-hardware.org/?probe=742af9249b) | Feb 23, 2022 |
| HP            | Pavilion dv7                | [e5544b291b](https://linux-hardware.org/?probe=e5544b291b) | Feb 22, 2022 |
| Google        | Lindar                      | [1a350b747f](https://linux-hardware.org/?probe=1a350b747f) | Feb 22, 2022 |
| Apple         | MacBookPro1,1               | [555ecdf4e9](https://linux-hardware.org/?probe=555ecdf4e9) | Feb 22, 2022 |
| Apple         | MacBookPro1,1               | [8ebe1ad906](https://linux-hardware.org/?probe=8ebe1ad906) | Feb 22, 2022 |
| Dell          | Inspiron 5759               | [89c67bc757](https://linux-hardware.org/?probe=89c67bc757) | Feb 21, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [d1f67de0fb](https://linux-hardware.org/?probe=d1f67de0fb) | Feb 21, 2022 |
| HP            | EliteBook 2560p             | [aea94057eb](https://linux-hardware.org/?probe=aea94057eb) | Feb 20, 2022 |
| Dell          | Latitude E7240              | [56e2e00db1](https://linux-hardware.org/?probe=56e2e00db1) | Feb 20, 2022 |
| Dell          | Latitude E7240              | [2d5df75b0d](https://linux-hardware.org/?probe=2d5df75b0d) | Feb 20, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [6205aed9e8](https://linux-hardware.org/?probe=6205aed9e8) | Feb 20, 2022 |
| Radxa         | ROCK Pi X v1.4              | [dd6d9dc630](https://linux-hardware.org/?probe=dd6d9dc630) | Feb 19, 2022 |
| Lenovo        | ThinkPad T410 2537A12       | [7326d20b88](https://linux-hardware.org/?probe=7326d20b88) | Feb 19, 2022 |
| Apple         | MacBook5,1                  | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [7ad48c7fcf](https://linux-hardware.org/?probe=7ad48c7fcf) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [5a0d00befe](https://linux-hardware.org/?probe=5a0d00befe) | Feb 19, 2022 |
| Lenovo        | ThinkPad X230 2325FG0       | [d8480748c7](https://linux-hardware.org/?probe=d8480748c7) | Feb 18, 2022 |
| Toshiba       | Satellite L350D             | [00eac655e9](https://linux-hardware.org/?probe=00eac655e9) | Feb 18, 2022 |
| HP            | Notebook                    | [aee3f5ce0b](https://linux-hardware.org/?probe=aee3f5ce0b) | Feb 18, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [b9dec24676](https://linux-hardware.org/?probe=b9dec24676) | Feb 17, 2022 |
| ASUSTek       | X556UB                      | [33eaab7189](https://linux-hardware.org/?probe=33eaab7189) | Feb 16, 2022 |
| Fujitsu       | LIFEBOOK E736               | [b5da44235a](https://linux-hardware.org/?probe=b5da44235a) | Feb 16, 2022 |
| Dell          | Latitude 5320               | [13c53062b6](https://linux-hardware.org/?probe=13c53062b6) | Feb 16, 2022 |
| Jumper        | EZbook                      | [4e3450d009](https://linux-hardware.org/?probe=4e3450d009) | Feb 16, 2022 |
| ASUSTek       | X550CA                      | [b889f04704](https://linux-hardware.org/?probe=b889f04704) | Feb 16, 2022 |
| Jumper        | EZbook                      | [f27f93bafe](https://linux-hardware.org/?probe=f27f93bafe) | Feb 16, 2022 |
| HP            | ProBook 430 G4              | [20bf4c2464](https://linux-hardware.org/?probe=20bf4c2464) | Feb 15, 2022 |
| HP            | Notebook                    | [7e7b9be307](https://linux-hardware.org/?probe=7e7b9be307) | Feb 15, 2022 |
| HP            | EliteBook 2570p             | [cd8a9df065](https://linux-hardware.org/?probe=cd8a9df065) | Feb 15, 2022 |
| Acer          | Aspire A517-52              | [1ae327b586](https://linux-hardware.org/?probe=1ae327b586) | Feb 15, 2022 |
| Toshiba       | Satellite L750              | [4a84859a37](https://linux-hardware.org/?probe=4a84859a37) | Feb 15, 2022 |
| Acer          | Nitro AN515-54              | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Dell          | XPS 13 9310                 | [c1227bf037](https://linux-hardware.org/?probe=c1227bf037) | Feb 14, 2022 |
| Jumper        | EZbook                      | [2a16a25836](https://linux-hardware.org/?probe=2a16a25836) | Feb 14, 2022 |
| Acer          | Aspire A514-53              | [5765e1b103](https://linux-hardware.org/?probe=5765e1b103) | Feb 14, 2022 |
| HP            | 255 G6 Notebook PC          | [3dc88df597](https://linux-hardware.org/?probe=3dc88df597) | Feb 13, 2022 |
| HP            | Compaq 6910p (GR670ET#UU... | [f21dcf572e](https://linux-hardware.org/?probe=f21dcf572e) | Feb 13, 2022 |
| HP            | Compaq 6910p (GR670ET#UU... | [7f07e2a9da](https://linux-hardware.org/?probe=7f07e2a9da) | Feb 13, 2022 |
| Acer          | Aspire A315-21              | [a8496ddfda](https://linux-hardware.org/?probe=a8496ddfda) | Feb 13, 2022 |
| Dell          | Latitude E6420              | [019b0aeeea](https://linux-hardware.org/?probe=019b0aeeea) | Feb 13, 2022 |
| Dell          | Inspiron 5579               | [8ae7432b94](https://linux-hardware.org/?probe=8ae7432b94) | Feb 13, 2022 |
| Dell          | Inspiron 5515               | [27dad40db4](https://linux-hardware.org/?probe=27dad40db4) | Feb 13, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | [0412384bc2](https://linux-hardware.org/?probe=0412384bc2) | Feb 13, 2022 |
| Dell          | Inspiron 5567               | [b2d1482541](https://linux-hardware.org/?probe=b2d1482541) | Feb 13, 2022 |
| PC Special... | NH5xAx                      | [5e0b855dbf](https://linux-hardware.org/?probe=5e0b855dbf) | Feb 13, 2022 |
| Lenovo        | ThinkPad L380 20M5S08R00    | [a505a2ae47](https://linux-hardware.org/?probe=a505a2ae47) | Feb 12, 2022 |
| Lenovo        | ThinkPad L380 20M5S08R00    | [315d27f7d7](https://linux-hardware.org/?probe=315d27f7d7) | Feb 12, 2022 |
| Dell          | Latitude 3390 2-in-1        | [c6fa52f6e0](https://linux-hardware.org/?probe=c6fa52f6e0) | Feb 12, 2022 |
| HONOR         | HLYL-WXX9                   | [1bce93c4ad](https://linux-hardware.org/?probe=1bce93c4ad) | Feb 12, 2022 |
| Lenovo        | Flex 2-15 20405             | [7ae6513197](https://linux-hardware.org/?probe=7ae6513197) | Feb 12, 2022 |
| Apple         | MacBookAir6,1               | [0d07efd7dd](https://linux-hardware.org/?probe=0d07efd7dd) | Feb 12, 2022 |
| HP            | 255 G3                      | [73426584f7](https://linux-hardware.org/?probe=73426584f7) | Feb 11, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [7ffdca7ea4](https://linux-hardware.org/?probe=7ffdca7ea4) | Feb 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c8c2ede566](https://linux-hardware.org/?probe=c8c2ede566) | Feb 11, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [c1ba1e4fe7](https://linux-hardware.org/?probe=c1ba1e4fe7) | Feb 11, 2022 |
| Dell          | XPS 15 7590                 | [4756364ef6](https://linux-hardware.org/?probe=4756364ef6) | Feb 10, 2022 |
| Sony          | VPCEL2S1E                   | [5bc3063386](https://linux-hardware.org/?probe=5bc3063386) | Feb 10, 2022 |
| Dell          | XPS 13 9370                 | [7360a72c44](https://linux-hardware.org/?probe=7360a72c44) | Feb 09, 2022 |
| HP            | Pavilion g6                 | [fc1a305abe](https://linux-hardware.org/?probe=fc1a305abe) | Feb 09, 2022 |
| Lenovo        | ThinkPad T430 2349GAG       | [b2cd2857d3](https://linux-hardware.org/?probe=b2cd2857d3) | Feb 09, 2022 |
| Dell          | XPS 13 9370                 | [d0bfe3fa56](https://linux-hardware.org/?probe=d0bfe3fa56) | Feb 09, 2022 |
| Timi          | TM1613                      | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| Acer          | Aspire A515-43              | [2b3ad05e55](https://linux-hardware.org/?probe=2b3ad05e55) | Feb 08, 2022 |
| Lenovo        | V15-ADA 82C7                | [85f930f1fc](https://linux-hardware.org/?probe=85f930f1fc) | Feb 08, 2022 |
| Radxa         | ROCK Pi X v1.4              | [6a3bd80ed5](https://linux-hardware.org/?probe=6a3bd80ed5) | Feb 08, 2022 |
| ASUSTek       | 1000HE                      | [5dd6246e59](https://linux-hardware.org/?probe=5dd6246e59) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0cc7c7e225](https://linux-hardware.org/?probe=0cc7c7e225) | Feb 08, 2022 |
| Viglen        | VUB1                        | [13f512e2d1](https://linux-hardware.org/?probe=13f512e2d1) | Feb 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [09af3e68dd](https://linux-hardware.org/?probe=09af3e68dd) | Feb 07, 2022 |
| Lenovo        | ThinkPad X201 3626AT7       | [92b79d9ade](https://linux-hardware.org/?probe=92b79d9ade) | Feb 07, 2022 |
| Toshiba       | Satellite L750              | [3e64e98234](https://linux-hardware.org/?probe=3e64e98234) | Feb 07, 2022 |
| Google        | Pantheon                    | [eebf10f1bb](https://linux-hardware.org/?probe=eebf10f1bb) | Feb 07, 2022 |
| Google        | Pantheon                    | [54f96033d0](https://linux-hardware.org/?probe=54f96033d0) | Feb 07, 2022 |
| Dell          | G5 5587                     | [33819e0316](https://linux-hardware.org/?probe=33819e0316) | Feb 06, 2022 |
| Dell          | G5 5587                     | [6fcaa54ab0](https://linux-hardware.org/?probe=6fcaa54ab0) | Feb 06, 2022 |
| Timi          | TM1613                      | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [da3b8d9778](https://linux-hardware.org/?probe=da3b8d9778) | Feb 06, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [dc86c1f5d5](https://linux-hardware.org/?probe=dc86c1f5d5) | Feb 05, 2022 |
| Apple         | MacBookPro7,1               | [ace4bb0837](https://linux-hardware.org/?probe=ace4bb0837) | Feb 05, 2022 |
| Apple         | MacBookPro7,1               | [beeb5ea0d7](https://linux-hardware.org/?probe=beeb5ea0d7) | Feb 05, 2022 |
| HP            | EliteBook 820 G2            | [7ca305cd80](https://linux-hardware.org/?probe=7ca305cd80) | Feb 05, 2022 |
| Apple         | MacBookPro9,2               | [63f2430481](https://linux-hardware.org/?probe=63f2430481) | Feb 05, 2022 |
| Acer          | Aspire 5551                 | [9287291d62](https://linux-hardware.org/?probe=9287291d62) | Feb 04, 2022 |
| Lenovo        | ThinkPad X131e 33711Q7      | [2423cfbdf7](https://linux-hardware.org/?probe=2423cfbdf7) | Feb 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [5ed9b5b2b8](https://linux-hardware.org/?probe=5ed9b5b2b8) | Feb 04, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [5828b467b9](https://linux-hardware.org/?probe=5828b467b9) | Feb 04, 2022 |
| Dell          | XPS 15 9500                 | [748e3fae6c](https://linux-hardware.org/?probe=748e3fae6c) | Feb 04, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [dc54fcc2ff](https://linux-hardware.org/?probe=dc54fcc2ff) | Feb 04, 2022 |
| Google        | Banon                       | [66f185fafb](https://linux-hardware.org/?probe=66f185fafb) | Feb 04, 2022 |
| Dell          | XPS 13 9310                 | [28544c13f5](https://linux-hardware.org/?probe=28544c13f5) | Feb 04, 2022 |
| Google        | Banon                       | [be4603cd8a](https://linux-hardware.org/?probe=be4603cd8a) | Feb 03, 2022 |
| Dell          | XPS 15 9550                 | [61f97dad6e](https://linux-hardware.org/?probe=61f97dad6e) | Feb 03, 2022 |
| Teclast       | F7S                         | [352c4a7941](https://linux-hardware.org/?probe=352c4a7941) | Feb 03, 2022 |
| Novatech      | 15.6 nSpire Laptop          | [6fe78d2f4b](https://linux-hardware.org/?probe=6fe78d2f4b) | Feb 02, 2022 |
| Dell          | XPS 15 9570                 | [d1f8ff2cb8](https://linux-hardware.org/?probe=d1f8ff2cb8) | Feb 02, 2022 |
| Dell          | Inspiron 7501               | [5f664815d0](https://linux-hardware.org/?probe=5f664815d0) | Feb 02, 2022 |
| Lenovo        | ThinkPad R61e 7649AL6       | [e7595e9b45](https://linux-hardware.org/?probe=e7595e9b45) | Feb 02, 2022 |
| Sony          | SVD1121Q2EB                 | [8e484b15d2](https://linux-hardware.org/?probe=8e484b15d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | [ae25a7a57d](https://linux-hardware.org/?probe=ae25a7a57d) | Feb 02, 2022 |
| Jumper        | EZbook                      | [93bb9c8e78](https://linux-hardware.org/?probe=93bb9c8e78) | Feb 01, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7db720ba39](https://linux-hardware.org/?probe=7db720ba39) | Feb 01, 2022 |
| PC Special... | NH5xAx                      | [6c8a746762](https://linux-hardware.org/?probe=6c8a746762) | Feb 01, 2022 |
| Toshiba       | Satellite Pro R850          | [8d5f88157a](https://linux-hardware.org/?probe=8d5f88157a) | Feb 01, 2022 |
| Toshiba       | Satellite C50-A-19T         | [7ea7ab684e](https://linux-hardware.org/?probe=7ea7ab684e) | Feb 01, 2022 |
| HP            | ProBook 650 G2              | [1835f9c2d4](https://linux-hardware.org/?probe=1835f9c2d4) | Jan 31, 2022 |
| Acer          | Aspire ES1-411              | [8d478b1936](https://linux-hardware.org/?probe=8d478b1936) | Jan 31, 2022 |
| Lenovo        | V145-15AST 81MT             | [83f9f7b941](https://linux-hardware.org/?probe=83f9f7b941) | Jan 31, 2022 |
| ASUSTek       | X555UJ                      | [a44843be2c](https://linux-hardware.org/?probe=a44843be2c) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [316ea97198](https://linux-hardware.org/?probe=316ea97198) | Jan 31, 2022 |
| AVITA         | NS14A6                      | [bbf5494b7f](https://linux-hardware.org/?probe=bbf5494b7f) | Jan 30, 2022 |
| AVITA         | NS14A6                      | [5cb93a7ead](https://linux-hardware.org/?probe=5cb93a7ead) | Jan 30, 2022 |
| HP            | Compaq nw9440 (EY615ET#A... | [6a5c3254ab](https://linux-hardware.org/?probe=6a5c3254ab) | Jan 30, 2022 |
| Dell          | Vostro 3560                 | [27250b902e](https://linux-hardware.org/?probe=27250b902e) | Jan 29, 2022 |
| GPD           | G1621-02                    | [7bc0adb6d3](https://linux-hardware.org/?probe=7bc0adb6d3) | Jan 28, 2022 |
| Dell          | XPS 15 9550                 | [bd70dabde4](https://linux-hardware.org/?probe=bd70dabde4) | Jan 28, 2022 |
| Dell          | Latitude E6510              | [a571bdc501](https://linux-hardware.org/?probe=a571bdc501) | Jan 28, 2022 |
| Toshiba       | Satellite L750              | [6a8c5526f8](https://linux-hardware.org/?probe=6a8c5526f8) | Jan 27, 2022 |
| Apple         | MacBookAir6,1               | [c7bf1e2cab](https://linux-hardware.org/?probe=c7bf1e2cab) | Jan 26, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [11d9c59e44](https://linux-hardware.org/?probe=11d9c59e44) | Jan 26, 2022 |
| Dell          | XPS 15 7590                 | [f31c2dda65](https://linux-hardware.org/?probe=f31c2dda65) | Jan 26, 2022 |
| Samsung       | 935XDB                      | [ef096190b6](https://linux-hardware.org/?probe=ef096190b6) | Jan 26, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [e3308423e5](https://linux-hardware.org/?probe=e3308423e5) | Jan 26, 2022 |
| HP            | ProBook 650 G5              | [fe61272ae2](https://linux-hardware.org/?probe=fe61272ae2) | Jan 25, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [f4ad8a6220](https://linux-hardware.org/?probe=f4ad8a6220) | Jan 25, 2022 |
| Dell          | Latitude D531               | [e9e8fa864a](https://linux-hardware.org/?probe=e9e8fa864a) | Jan 24, 2022 |
| Lenovo        | IdeaPad Y500 9541           | [f9fd02faac](https://linux-hardware.org/?probe=f9fd02faac) | Jan 23, 2022 |
| Lenovo        | IdeaPad Y500 9541           | [47e812ac04](https://linux-hardware.org/?probe=47e812ac04) | Jan 23, 2022 |
| Acer          | Aspire A615-51              | [a7cd7b1960](https://linux-hardware.org/?probe=a7cd7b1960) | Jan 23, 2022 |
| ASUSTek       | X450LD                      | [07edc503a1](https://linux-hardware.org/?probe=07edc503a1) | Jan 23, 2022 |
| Acer          | Aspire 8935G                | [a1b815e026](https://linux-hardware.org/?probe=a1b815e026) | Jan 23, 2022 |
| Acer          | Aspire 5738                 | [619ebd38aa](https://linux-hardware.org/?probe=619ebd38aa) | Jan 23, 2022 |
| Acer          | Aspire 5738                 | [cfb12999e8](https://linux-hardware.org/?probe=cfb12999e8) | Jan 23, 2022 |
| HP            | Laptop 14s-fq0xxx           | [05d9d96be4](https://linux-hardware.org/?probe=05d9d96be4) | Jan 23, 2022 |
| Alienware     | 17 R4                       | [d82171f734](https://linux-hardware.org/?probe=d82171f734) | Jan 22, 2022 |
| Lenovo        | ThinkPad T430 2349U4B       | [8cf6949b05](https://linux-hardware.org/?probe=8cf6949b05) | Jan 22, 2022 |
| Dell          | Latitude E6400              | [c18fa2fa99](https://linux-hardware.org/?probe=c18fa2fa99) | Jan 22, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [b8b6a312b1](https://linux-hardware.org/?probe=b8b6a312b1) | Jan 21, 2022 |
| Acer          | Aspire A515-44              | [f348809f89](https://linux-hardware.org/?probe=f348809f89) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK E753               | [d44da01e91](https://linux-hardware.org/?probe=d44da01e91) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [29fd90e072](https://linux-hardware.org/?probe=29fd90e072) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Jumper        | EZbook                      | [c6f783a8ad](https://linux-hardware.org/?probe=c6f783a8ad) | Jan 17, 2022 |
| Jumper        | EZbook                      | [f476b26c5b](https://linux-hardware.org/?probe=f476b26c5b) | Jan 17, 2022 |
| Acer          | Aspire 5740                 | [005887e692](https://linux-hardware.org/?probe=005887e692) | Jan 17, 2022 |
| Jumper        | EZbook                      | [6c949f1929](https://linux-hardware.org/?probe=6c949f1929) | Jan 17, 2022 |
| Viglen        | VUB1                        | [d16d7f30b3](https://linux-hardware.org/?probe=d16d7f30b3) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| Toshiba       | EQUIUM P200D                | [b28ab84bf8](https://linux-hardware.org/?probe=b28ab84bf8) | Jan 15, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [142bc361ba](https://linux-hardware.org/?probe=142bc361ba) | Jan 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [dae8d10589](https://linux-hardware.org/?probe=dae8d10589) | Jan 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [fb799bb9f5](https://linux-hardware.org/?probe=fb799bb9f5) | Jan 15, 2022 |
| Toshiba       | Satellite C55-C             | [80fb337bde](https://linux-hardware.org/?probe=80fb337bde) | Jan 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [779202413e](https://linux-hardware.org/?probe=779202413e) | Jan 15, 2022 |
| LG Electro... | 16Z90P-K.AA72A1             | [5c76ea5424](https://linux-hardware.org/?probe=5c76ea5424) | Jan 15, 2022 |
| Dell          | Inspiron 3583               | [fdac2f87fe](https://linux-hardware.org/?probe=fdac2f87fe) | Jan 14, 2022 |
| Dell          | Latitude D620               | [a43c35d2fa](https://linux-hardware.org/?probe=a43c35d2fa) | Jan 14, 2022 |
| Apple         | MacBook6,1                  | [e9f23e9f5f](https://linux-hardware.org/?probe=e9f23e9f5f) | Jan 13, 2022 |
| ASUSTek       | K54C                        | [048477ec85](https://linux-hardware.org/?probe=048477ec85) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | [85d81f357a](https://linux-hardware.org/?probe=85d81f357a) | Jan 13, 2022 |
| Packard Be... | EasyNote TE11HC             | [6e5a2e29f4](https://linux-hardware.org/?probe=6e5a2e29f4) | Jan 12, 2022 |
| Toshiba       | Satellite C650              | [07ead176f9](https://linux-hardware.org/?probe=07ead176f9) | Jan 12, 2022 |
| Toshiba       | Satellite C660D             | [99d2f2253d](https://linux-hardware.org/?probe=99d2f2253d) | Jan 11, 2022 |
| Dell          | Latitude 3410               | [f9933fb000](https://linux-hardware.org/?probe=f9933fb000) | Jan 11, 2022 |
| Dell          | Inspiron N5110              | [79eb4b2eee](https://linux-hardware.org/?probe=79eb4b2eee) | Jan 11, 2022 |
| Dell          | Latitude 7280               | [80f69f0294](https://linux-hardware.org/?probe=80f69f0294) | Jan 11, 2022 |
| HP            | G70                         | [5db05fe4eb](https://linux-hardware.org/?probe=5db05fe4eb) | Jan 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [1e31796586](https://linux-hardware.org/?probe=1e31796586) | Jan 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [bb8e7fc409](https://linux-hardware.org/?probe=bb8e7fc409) | Jan 10, 2022 |
| Dell          | Inspiron 1720               | [e3e7fc8951](https://linux-hardware.org/?probe=e3e7fc8951) | Jan 10, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [bbcda99dab](https://linux-hardware.org/?probe=bbcda99dab) | Jan 10, 2022 |
| Dell          | Latitude E6320              | [0e34f6fd45](https://linux-hardware.org/?probe=0e34f6fd45) | Jan 10, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [148b934acf](https://linux-hardware.org/?probe=148b934acf) | Jan 09, 2022 |
| Fujitsu Si... | AMILO PRO V3515             | [d537e0bc35](https://linux-hardware.org/?probe=d537e0bc35) | Jan 09, 2022 |
| Fujitsu Si... | AMILO PRO V3515             | [4bfe339a98](https://linux-hardware.org/?probe=4bfe339a98) | Jan 09, 2022 |
| Lenovo        | ThinkPad T570 20HAS11J00    | [8bcfe1042a](https://linux-hardware.org/?probe=8bcfe1042a) | Jan 09, 2022 |
| Dell          | Inspiron M5040              | [2fa8f23cb9](https://linux-hardware.org/?probe=2fa8f23cb9) | Jan 09, 2022 |
| Dell          | Inspiron M5040              | [a0b1a9f1d3](https://linux-hardware.org/?probe=a0b1a9f1d3) | Jan 09, 2022 |
| Acer          | Aspire 5551                 | [ce439720ef](https://linux-hardware.org/?probe=ce439720ef) | Jan 09, 2022 |
| Dell          | XPS 13 9310                 | [e0dfa537f4](https://linux-hardware.org/?probe=e0dfa537f4) | Jan 08, 2022 |
| HP            | Laptop 15-da0xxx            | [4e21fb8625](https://linux-hardware.org/?probe=4e21fb8625) | Jan 08, 2022 |
| HP            | Laptop 15-da0xxx            | [a6b32b67b4](https://linux-hardware.org/?probe=a6b32b67b4) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a23bb3d2c0](https://linux-hardware.org/?probe=a23bb3d2c0) | Jan 08, 2022 |
| Dell          | XPS 15 9510                 | [d3bd574234](https://linux-hardware.org/?probe=d3bd574234) | Jan 07, 2022 |
| Dell          | XPS 13 9310                 | [aa1ce4d9ca](https://linux-hardware.org/?probe=aa1ce4d9ca) | Jan 07, 2022 |
| Toshiba       | Satellite L755              | [df6cc34c45](https://linux-hardware.org/?probe=df6cc34c45) | Jan 07, 2022 |
| Samsung       | R530/R730                   | [d07e567173](https://linux-hardware.org/?probe=d07e567173) | Jan 07, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | [4a33da1bc1](https://linux-hardware.org/?probe=4a33da1bc1) | Jan 06, 2022 |
| Star Labs     | StarBook                    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Lenovo        | ThinkPad L380 20M6S1VV00    | [bc4fe37053](https://linux-hardware.org/?probe=bc4fe37053) | Jan 06, 2022 |
| HUAWEI        | MACHD-WXX9                  | [6c5e2e7851](https://linux-hardware.org/?probe=6c5e2e7851) | Jan 06, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| HP            | EliteBook 820 G2            | [b5ab89a508](https://linux-hardware.org/?probe=b5ab89a508) | Jan 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a568bef730](https://linux-hardware.org/?probe=a568bef730) | Jan 05, 2022 |
| HP            | Pavilion x2 Detachable      | [7b43e5d7fd](https://linux-hardware.org/?probe=7b43e5d7fd) | Jan 05, 2022 |
| Dell          | Latitude E6520              | [39a940ae21](https://linux-hardware.org/?probe=39a940ae21) | Jan 05, 2022 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [c7f2471bdf](https://linux-hardware.org/?probe=c7f2471bdf) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Star Labs     | LabTop                      | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| ASUSTek       | X555QG                      | [a10e6b5ec0](https://linux-hardware.org/?probe=a10e6b5ec0) | Jan 04, 2022 |
| Dell          | Inspiron 7591               | [4044cf11d2](https://linux-hardware.org/?probe=4044cf11d2) | Jan 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [e88914bd49](https://linux-hardware.org/?probe=e88914bd49) | Jan 04, 2022 |
| ASUSTek       | X555QG                      | [9062bc4b1d](https://linux-hardware.org/?probe=9062bc4b1d) | Jan 03, 2022 |
| HP            | Pavilion x2 Detachable      | [db6b6f9863](https://linux-hardware.org/?probe=db6b6f9863) | Jan 03, 2022 |
| Dell          | Latitude E5440              | [16fbe4c9c0](https://linux-hardware.org/?probe=16fbe4c9c0) | Jan 03, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDA03... | [59a73a8864](https://linux-hardware.org/?probe=59a73a8864) | Jan 02, 2022 |
| Unknown       | Unknown                     | [033354ee53](https://linux-hardware.org/?probe=033354ee53) | Jan 02, 2022 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [bcc27ef54b](https://linux-hardware.org/?probe=bcc27ef54b) | Jan 02, 2022 |
| Google        | Rammus                      | [aa3b26a209](https://linux-hardware.org/?probe=aa3b26a209) | Jan 02, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [4c8824cb05](https://linux-hardware.org/?probe=4c8824cb05) | Jan 01, 2022 |
| ASUSTek       | G771JMC                     | [8a937cb99d](https://linux-hardware.org/?probe=8a937cb99d) | Jan 01, 2022 |
| HP            | Pavilion x2 Detachable      | [9ab20c3fde](https://linux-hardware.org/?probe=9ab20c3fde) | Dec 31, 2021 |
| Acer          | Aspire 5920                 | [b492dec09b](https://linux-hardware.org/?probe=b492dec09b) | Dec 31, 2021 |
| Lenovo        | IdeaPad S540-13API 81XC     | [c599a26a65](https://linux-hardware.org/?probe=c599a26a65) | Dec 31, 2021 |
| Apple         | MacBookPro11,5              | [7e02c5721d](https://linux-hardware.org/?probe=7e02c5721d) | Dec 30, 2021 |
| HP            | Pavilion g6                 | [4c4cc2921d](https://linux-hardware.org/?probe=4c4cc2921d) | Dec 30, 2021 |
| Google        | Chell                       | [9a2a4a03ed](https://linux-hardware.org/?probe=9a2a4a03ed) | Dec 30, 2021 |
| Lenovo        | B50-30 80ES                 | [a1a074beba](https://linux-hardware.org/?probe=a1a074beba) | Dec 30, 2021 |
| Lenovo        | ThinkPad T430 2349U4B       | [3088a2d8ad](https://linux-hardware.org/?probe=3088a2d8ad) | Dec 29, 2021 |
| Dell          | Inspiron 1720               | [b40685ea7b](https://linux-hardware.org/?probe=b40685ea7b) | Dec 29, 2021 |
| Dell          | XPS 13 9370                 | [f20a77fa7e](https://linux-hardware.org/?probe=f20a77fa7e) | Dec 29, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [80d5326578](https://linux-hardware.org/?probe=80d5326578) | Dec 29, 2021 |
| Dell          | Latitude E7470              | [55e3078baf](https://linux-hardware.org/?probe=55e3078baf) | Dec 28, 2021 |
| Lenovo        | ThinkPad X201 3680MG1       | [54c076eb59](https://linux-hardware.org/?probe=54c076eb59) | Dec 28, 2021 |
| HP            | 255 G5                      | [0bf7bc5435](https://linux-hardware.org/?probe=0bf7bc5435) | Dec 28, 2021 |
| Fujitsu Si... | AMILO Li 1818               | [9189d1790a](https://linux-hardware.org/?probe=9189d1790a) | Dec 28, 2021 |
| Acer          | Aspire 5680                 | [3d8d482ea9](https://linux-hardware.org/?probe=3d8d482ea9) | Dec 27, 2021 |
| Acer          | Aspire 5680                 | [792445969b](https://linux-hardware.org/?probe=792445969b) | Dec 27, 2021 |
| HUAWEI        | KPL-W0X                     | [0551e72ef6](https://linux-hardware.org/?probe=0551e72ef6) | Dec 27, 2021 |
| HUAWEI        | KPL-W0X                     | [64d4de98ff](https://linux-hardware.org/?probe=64d4de98ff) | Dec 27, 2021 |
| Unknown       | Unknown                     | [ea795a97e1](https://linux-hardware.org/?probe=ea795a97e1) | Dec 26, 2021 |
| Lenovo        | IdeaPad S540-13API 81XC     | [c7612aac66](https://linux-hardware.org/?probe=c7612aac66) | Dec 26, 2021 |
| Acer          | Aspire 5750G                | [052954142f](https://linux-hardware.org/?probe=052954142f) | Dec 26, 2021 |
| Fusion5       | FWIN232_PLUS                | [ce10f25e8c](https://linux-hardware.org/?probe=ce10f25e8c) | Dec 25, 2021 |
| Dell          | Latitude E6400              | [ff2ee90fee](https://linux-hardware.org/?probe=ff2ee90fee) | Dec 25, 2021 |
| HP            | EliteBook 840 G3            | [d149e3e8cd](https://linux-hardware.org/?probe=d149e3e8cd) | Dec 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [93e3145404](https://linux-hardware.org/?probe=93e3145404) | Dec 24, 2021 |
| HP            | EliteBook 840 G6            | [459f0e8c25](https://linux-hardware.org/?probe=459f0e8c25) | Dec 24, 2021 |
| HP            | ZBook 14 G2                 | [65796f1946](https://linux-hardware.org/?probe=65796f1946) | Dec 24, 2021 |
| HP            | EliteBook 840 G5            | [f84bf4846c](https://linux-hardware.org/?probe=f84bf4846c) | Dec 24, 2021 |
| HP            | EliteBook 840 G5            | [a4f7e27b61](https://linux-hardware.org/?probe=a4f7e27b61) | Dec 24, 2021 |
| Dell          | Inspiron 1720               | [6d1e22e244](https://linux-hardware.org/?probe=6d1e22e244) | Dec 23, 2021 |
| HP            | EliteBook 840 G6            | [c658d7097b](https://linux-hardware.org/?probe=c658d7097b) | Dec 23, 2021 |
| Dell          | Latitude E5540              | [e289fc7147](https://linux-hardware.org/?probe=e289fc7147) | Dec 23, 2021 |
| Advent        | Monza T100                  | [7355d1ae53](https://linux-hardware.org/?probe=7355d1ae53) | Dec 23, 2021 |
| HP            | EliteBook 2540p             | [5ce9a3ea6c](https://linux-hardware.org/?probe=5ce9a3ea6c) | Dec 22, 2021 |
| Dell          | Latitude E6230              | [f0372edeb0](https://linux-hardware.org/?probe=f0372edeb0) | Dec 22, 2021 |
| Dell          | Inspiron 5570               | [a955b3649c](https://linux-hardware.org/?probe=a955b3649c) | Dec 22, 2021 |
| Advent        | Tacto Purple                | [ac9fd78933](https://linux-hardware.org/?probe=ac9fd78933) | Dec 22, 2021 |
| Dell          | Latitude E6230              | [686fb1e16d](https://linux-hardware.org/?probe=686fb1e16d) | Dec 22, 2021 |
| ASUSTek       | E402SA                      | [e76b0dc53f](https://linux-hardware.org/?probe=e76b0dc53f) | Dec 21, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 529       | 16.8%   |
| Ubuntu 18.04      | 271       | 8.61%   |
| Ubuntu 22.04      | 71        | 2.26%   |
| Linux Mint 19.3   | 68        | 2.16%   |
| Zorin 16          | 65        | 2.06%   |
| OpenMandriva 4.3  | 63        | 2%      |
| Ubuntu 19.04      | 62        | 1.97%   |
| OpenMandriva 4.2  | 59        | 1.87%   |
| Arch              | 56        | 1.78%   |
| Pop!_OS 20.04     | 55        | 1.75%   |
| Linux Mint 20.2   | 54        | 1.72%   |
| Ubuntu 20.10      | 53        | 1.68%   |
| Ubuntu 21.10      | 51        | 1.62%   |
| KDE neon 20.04    | 51        | 1.62%   |
| Linux Mint 20.1   | 50        | 1.59%   |
| Debian 11         | 50        | 1.59%   |
| Zorin 15          | 49        | 1.56%   |
| Ubuntu 19.10      | 49        | 1.56%   |
| Manjaro           | 47        | 1.49%   |
| Linux Mint 20.3   | 46        | 1.46%   |
| Pop!_OS 21.04     | 45        | 1.43%   |
| Ubuntu 21.04      | 43        | 1.37%   |
| Xubuntu 20.04     | 37        | 1.18%   |
| Arch Rolling      | 37        | 1.18%   |
| Linux Mint 20     | 35        | 1.11%   |
| Pop!_OS 20.10     | 34        | 1.08%   |
| Pop!_OS 21.10     | 33        | 1.05%   |
| Fedora 35         | 33        | 1.05%   |
| Fedora 34         | 33        | 1.05%   |
| Ubuntu 18.10      | 31        | 0.98%   |
| ArcoLinux Rolling | 31        | 0.98%   |
| Fedora 32         | 28        | 0.89%   |
| Fedora 31         | 28        | 0.89%   |
| Pop!_OS 22.04     | 25        | 0.79%   |
| Kubuntu 20.04     | 25        | 0.79%   |
| Fedora 36         | 25        | 0.79%   |
| Fedora 33         | 25        | 0.79%   |
| BlackPanther 18.1 | 25        | 0.79%   |
| Xubuntu 18.04     | 21        | 0.67%   |
| ROSA R10          | 18        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1134      | 37.5%   |
| Linux Mint    | 274       | 9.06%   |
| Pop!_OS       | 178       | 5.89%   |
| Fedora        | 174       | 5.75%   |
| OpenMandriva  | 138       | 4.56%   |
| Zorin         | 122       | 4.03%   |
| Manjaro       | 110       | 3.64%   |
| Arch          | 91        | 3.01%   |
| Debian        | 84        | 2.78%   |
| Xubuntu       | 75        | 2.48%   |
| Kubuntu       | 62        | 2.05%   |
| KDE neon      | 56        | 1.85%   |
| Elementary    | 38        | 1.26%   |
| ArcoLinux     | 35        | 1.16%   |
| ROSA          | 34        | 1.12%   |
| Lubuntu       | 33        | 1.09%   |
| Ubuntu MATE   | 28        | 0.93%   |
| Endless       | 27        | 0.89%   |
| BlackPanther  | 26        | 0.86%   |
| SteamOS       | 24        | 0.79%   |
| Ubuntu Unity  | 23        | 0.76%   |
| openSUSE      | 23        | 0.76%   |
| Gentoo        | 22        | 0.73%   |
| Kali          | 20        | 0.66%   |
| Clear Linux   | 18        | 0.6%    |
| LMDE          | 17        | 0.56%   |
| Garuda Linux  | 14        | 0.46%   |
| Peppermint    | 12        | 0.4%    |
| EndeavourOS   | 12        | 0.4%    |
| Ubuntu Budgie | 11        | 0.36%   |
| MX            | 11        | 0.36%   |
| Parrot        | 10        | 0.33%   |
| CentOS        | 9         | 0.3%    |
| RHEL          | 6         | 0.2%    |
| NixOS         | 5         | 0.17%   |
| PureOS        | 4         | 0.13%   |
| Artix         | 4         | 0.13%   |
| Alpine        | 4         | 0.13%   |
| Sparky        | 3         | 0.1%    |
| Solus         | 3         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 77        | 2.22%   |
| 5.16.7-desktop-1omv4003  | 60        | 1.73%   |
| 5.10.14-desktop-1omv4002 | 56        | 1.61%   |
| 5.4.0-48-generic         | 40        | 1.15%   |
| 5.4.0-52-generic         | 39        | 1.12%   |
| 5.4.0-29-generic         | 35        | 1.01%   |
| 5.3.0-40-generic         | 35        | 1.01%   |
| 5.11.0-27-generic        | 34        | 0.98%   |
| 5.4.0-26-generic         | 33        | 0.95%   |
| 5.3.0-28-generic         | 33        | 0.95%   |
| 5.15.0-46-generic        | 31        | 0.89%   |
| 5.4.0-58-generic         | 30        | 0.86%   |
| 5.4.0-40-generic         | 29        | 0.83%   |
| 5.0.0-32-generic         | 29        | 0.83%   |
| 5.11.0-38-generic        | 28        | 0.81%   |
| 5.8.0-43-generic         | 25        | 0.72%   |
| 5.3.0-42-generic         | 25        | 0.72%   |
| 5.11.0-37-generic        | 25        | 0.72%   |
| 5.11.0-25-generic        | 24        | 0.69%   |
| 5.4.0-65-generic         | 23        | 0.66%   |
| 5.4.0-91-generic         | 22        | 0.63%   |
| 5.4.0-7634-generic       | 22        | 0.63%   |
| 5.4.0-33-generic         | 22        | 0.63%   |
| 5.13.0-7614-generic      | 22        | 0.63%   |
| 5.0.0-37-generic         | 22        | 0.63%   |
| 5.8.0-50-generic         | 21        | 0.6%    |
| 5.8.0-44-generic         | 21        | 0.6%    |
| 5.4.0-56-generic         | 21        | 0.6%    |
| 5.4.0-54-generic         | 21        | 0.6%    |
| 5.3.0-46-generic         | 21        | 0.6%    |
| 5.13.0-28-generic        | 21        | 0.6%    |
| 4.18.16-desktop-1bP      | 20        | 0.58%   |
| 5.4.0-31-generic         | 19        | 0.55%   |
| 5.15.0-41-generic        | 19        | 0.55%   |
| 5.11.0-40-generic        | 19        | 0.55%   |
| 5.8.0-7630-generic       | 18        | 0.52%   |
| 5.4.0-37-generic         | 18        | 0.52%   |
| 5.11.0-43-generic        | 18        | 0.52%   |
| 5.4.0-66-generic         | 17        | 0.49%   |
| 5.13.0-30-generic        | 17        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 705       | 21.85%  |
| 5.11.0  | 239       | 7.41%   |
| 5.8.0   | 232       | 7.19%   |
| 5.3.0   | 204       | 6.32%   |
| 5.13.0  | 204       | 6.32%   |
| 4.15.0  | 197       | 6.1%    |
| 5.15.0  | 137       | 4.25%   |
| 5.0.0   | 137       | 4.25%   |
| 4.18.0  | 91        | 2.82%   |
| 5.10.0  | 72        | 2.23%   |
| 5.16.7  | 60        | 1.86%   |
| 5.10.14 | 56        | 1.74%   |
| 4.19.0  | 29        | 0.9%    |
| 4.18.16 | 21        | 0.65%   |
| 5.17.5  | 15        | 0.46%   |
| 5.14.0  | 14        | 0.43%   |
| 5.19.0  | 12        | 0.37%   |
| 4.9.60  | 12        | 0.37%   |
| 5.17.1  | 11        | 0.34%   |
| 5.16.0  | 11        | 0.34%   |
| 5.9.16  | 10        | 0.31%   |
| 5.15.12 | 10        | 0.31%   |
| 4.4.0   | 10        | 0.31%   |
| 5.9.0   | 8         | 0.25%   |
| 5.16.15 | 8         | 0.25%   |
| 5.16.11 | 8         | 0.25%   |
| 5.13.8  | 8         | 0.25%   |
| 5.12.13 | 8         | 0.25%   |
| 5.7.0   | 7         | 0.22%   |
| 5.3.18  | 7         | 0.22%   |
| 5.18.10 | 7         | 0.22%   |
| 5.17.0  | 7         | 0.22%   |
| 5.16.18 | 7         | 0.22%   |
| 5.15.15 | 7         | 0.22%   |
| 5.14.14 | 7         | 0.22%   |
| 5.12.4  | 7         | 0.22%   |
| 4.9.20  | 7         | 0.22%   |
| 5.9.11  | 6         | 0.19%   |
| 5.8.7   | 6         | 0.19%   |
| 5.8.11  | 6         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 741       | 23.16%  |
| 5.8     | 277       | 8.66%   |
| 5.11    | 262       | 8.19%   |
| 5.13    | 244       | 7.63%   |
| 5.3     | 227       | 7.1%    |
| 5.15    | 217       | 6.78%   |
| 4.15    | 198       | 6.19%   |
| 5.10    | 176       | 5.5%    |
| 5.0     | 144       | 4.5%    |
| 5.16    | 124       | 3.88%   |
| 4.18    | 114       | 3.56%   |
| 5.17    | 54        | 1.69%   |
| 5.14    | 47        | 1.47%   |
| 5.9     | 46        | 1.44%   |
| 4.19    | 45        | 1.41%   |
| 5.12    | 42        | 1.31%   |
| 5.19    | 41        | 1.28%   |
| 5.6     | 36        | 1.13%   |
| 4.9     | 33        | 1.03%   |
| 5.7     | 30        | 0.94%   |
| 5.18    | 29        | 0.91%   |
| 5.5     | 19        | 0.59%   |
| 5.2     | 11        | 0.34%   |
| 4.4     | 11        | 0.34%   |
| 5.1     | 8         | 0.25%   |
| 4.20    | 3         | 0.09%   |
| 4.16    | 3         | 0.09%   |
| 4.14    | 3         | 0.09%   |
| 3.10    | 3         | 0.09%   |
| 4.8     | 2         | 0.06%   |
| 4.12    | 2         | 0.06%   |
| 4.1     | 2         | 0.06%   |
| 6.0     | 1         | 0.03%   |
| 4.6     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2807      | 96.3%   |
| i686    | 107       | 3.67%   |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1397      | 45.79%  |
| Unknown         | 405       | 13.27%  |
| KDE5            | 402       | 13.18%  |
| X-Cinnamon      | 224       | 7.34%   |
| XFCE            | 217       | 7.11%   |
| KDE             | 83        | 2.72%   |
| MATE            | 80        | 2.62%   |
| Cinnamon        | 36        | 1.18%   |
| Pantheon        | 35        | 1.15%   |
| LXQt            | 31        | 1.02%   |
| Unity           | 24        | 0.79%   |
| LXDE            | 23        | 0.75%   |
| i3              | 17        | 0.56%   |
| Budgie          | 17        | 0.56%   |
| KDE4            | 14        | 0.46%   |
| GNOME Flashback | 14        | 0.46%   |
| qtile           | 5         | 0.16%   |
| sway            | 4         | 0.13%   |
| GNOME Classic   | 4         | 0.13%   |
| Deepin          | 3         | 0.1%    |
| awesome         | 3         | 0.1%    |
| xmonad          | 2         | 0.07%   |
| trinity         | 2         | 0.07%   |
| i3-with-shmlog  | 2         | 0.07%   |
| DWM             | 2         | 0.07%   |
| bspwm           | 2         | 0.07%   |
| Openbox         | 1         | 0.03%   |
| GNUstep         | 1         | 0.03%   |
| Cutefish        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2389      | 79.9%   |
| Wayland | 348       | 11.64%  |
| Unknown | 221       | 7.39%   |
| Tty     | 32        | 1.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1780      | 58.63%  |
| GDM     | 369       | 12.15%  |
| SDDM    | 357       | 11.76%  |
| LightDM | 212       | 6.98%   |
| GDM3    | 190       | 6.26%   |
| TDM     | 100       | 3.29%   |
| KDM     | 15        | 0.49%   |
| XDM     | 5         | 0.16%   |
| Ly      | 3         | 0.1%    |
| LXDM    | 2         | 0.07%   |
| NODM    | 1         | 0.03%   |
| GREETD  | 1         | 0.03%   |
| CDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_GB       | 2120      | 70.95%  |
| Unknown     | 404       | 13.52%  |
| en_US       | 317       | 10.61%  |
| C           | 34        | 1.14%   |
| pl_PL       | 33        | 1.1%    |
| POSIX       | 6         | 0.2%    |
| en_CA       | 6         | 0.2%    |
| de_DE       | 6         | 0.2%    |
| ru_RU       | 5         | 0.17%   |
| it_IT       | 5         | 0.17%   |
| en_IN       | 5         | 0.17%   |
| en_AU       | 5         | 0.17%   |
| cs_CZ       | 5         | 0.17%   |
| fr_FR       | 4         | 0.13%   |
| en_IE       | 4         | 0.13%   |
| zh_CN       | 3         | 0.1%    |
| ro_RO       | 3         | 0.1%    |
| hu_HU       | 3         | 0.1%    |
| es_ES       | 3         | 0.1%    |
| sk_SK       | 2         | 0.07%   |
| pt_PT       | 2         | 0.07%   |
| pt_BR       | 2         | 0.07%   |
| uk_UA       | 1         | 0.03%   |
| tr_TR       | 1         | 0.03%   |
| nl_BE       | 1         | 0.03%   |
| en_IL       | 1         | 0.03%   |
| en_HK       | 1         | 0.03%   |
| en_GG       | 1         | 0.03%   |
| en_GB.utf-8 | 1         | 0.03%   |
| en_AG       | 1         | 0.03%   |
| da_DK       | 1         | 0.03%   |
| C.UTF8      | 1         | 0.03%   |
| bg_BG       | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1526      | 51.31%  |
| BIOS | 1448      | 48.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2384      | 80.08%  |
| Btrfs   | 212       | 7.12%   |
| Overlay | 186       | 6.25%   |
| Unknown | 112       | 3.76%   |
| Xfs     | 39        | 1.31%   |
| Zfs     | 21        | 0.71%   |
| Ext2    | 9         | 0.3%    |
| Tmpfs   | 5         | 0.17%   |
| F2fs    | 5         | 0.17%   |
| Ext3    | 3         | 0.1%    |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1902      | 64.08%  |
| GPT     | 820       | 27.63%  |
| MBR     | 246       | 8.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2654      | 89.72%  |
| Yes       | 304       | 10.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2216      | 74.99%  |
| Yes       | 739       | 25.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 598       | 20.53%  |
| Lenovo              | 560       | 19.22%  |
| Hewlett-Packard     | 497       | 17.06%  |
| Acer                | 222       | 7.62%   |
| ASUSTek Computer    | 199       | 6.83%   |
| Toshiba             | 135       | 4.63%   |
| Apple               | 90        | 3.09%   |
| Samsung Electronics | 62        | 2.13%   |
| Sony                | 52        | 1.79%   |
| MSI                 | 44        | 1.51%   |
| PC Specialist       | 37        | 1.27%   |
| HUAWEI              | 35        | 1.2%    |
| Notebook            | 27        | 0.93%   |
| Valve               | 24        | 0.82%   |
| Google              | 23        | 0.79%   |
| Unknown             | 19        | 0.65%   |
| Fujitsu             | 17        | 0.58%   |
| Razer               | 16        | 0.55%   |
| Star Labs           | 15        | 0.51%   |
| Packard Bell        | 15        | 0.51%   |
| Dixonsxp            | 13        | 0.45%   |
| Fujitsu Siemens     | 12        | 0.41%   |
| Alienware           | 12        | 0.41%   |
| Entroware           | 11        | 0.38%   |
| Clevo               | 9         | 0.31%   |
| Jumper              | 8         | 0.27%   |
| Gigabyte Technology | 8         | 0.27%   |
| Advent              | 8         | 0.27%   |
| Panasonic           | 7         | 0.24%   |
| Linx                | 7         | 0.24%   |
| Intel               | 7         | 0.24%   |
| TUXEDO              | 6         | 0.21%   |
| Medion              | 5         | 0.17%   |
| LG Electronics      | 5         | 0.17%   |
| GEO                 | 5         | 0.17%   |
| eMachines           | 5         | 0.17%   |
| Timi                | 4         | 0.14%   |
| Teclast             | 4         | 0.14%   |
| Chuwi               | 4         | 0.14%   |
| Purism              | 3         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 40        | 1.37%   |
| Valve Jupiter                | 24        | 0.82%   |
| HP Pavilion g6               | 21        | 0.72%   |
| HP Pavilion 15               | 17        | 0.58%   |
| HP Pavilion Notebook         | 15        | 0.51%   |
| HP Notebook                  | 14        | 0.48%   |
| Dell Inspiron 1545           | 14        | 0.48%   |
| Dell XPS 13 9370             | 13        | 0.45%   |
| Dell XPS 15 9560             | 12        | 0.41%   |
| Dell XPS 15 7590             | 12        | 0.41%   |
| Dell XPS 13 9360             | 12        | 0.41%   |
| Dell XPS 15 9570             | 11        | 0.38%   |
| Dell Latitude E6410          | 11        | 0.38%   |
| Dell Latitude E6400          | 11        | 0.38%   |
| Lenovo V145-15AST 81MT       | 10        | 0.34%   |
| Dell XPS 13 9380             | 10        | 0.34%   |
| Dell Latitude E7240          | 10        | 0.34%   |
| Apple MacBookPro9,2          | 10        | 0.34%   |
| Lenovo Z50-75 80EC           | 9         | 0.31%   |
| HP Laptop 15-bw0xx           | 9         | 0.31%   |
| HP 15                        | 9         | 0.31%   |
| Dell XPS 15 9510             | 9         | 0.31%   |
| Dell Latitude E7450          | 9         | 0.31%   |
| Toshiba Satellite C660       | 8         | 0.27%   |
| HP Laptop 15-da0xxx          | 8         | 0.27%   |
| Dell XPS 15 9550             | 8         | 0.27%   |
| Dell XPS 13 9310             | 8         | 0.27%   |
| Dell XPS 13 7390             | 8         | 0.27%   |
| Dell Latitude E7440          | 8         | 0.27%   |
| Apple MacBookPro12,1         | 8         | 0.27%   |
| Acer Aspire ES1-531          | 8         | 0.27%   |
| Star Labs LabTop             | 7         | 0.24%   |
| HP Stream Laptop 14-ax0XX    | 7         | 0.24%   |
| HP Pavilion dv6              | 7         | 0.24%   |
| Dell Inspiron 15 7000 Gaming | 7         | 0.24%   |
| Apple MacBookPro5,5          | 7         | 0.24%   |
| Acer Aspire A315-21          | 7         | 0.24%   |
| Star Labs Lite               | 6         | 0.21%   |
| Samsung RF511/RF411/RF711    | 6         | 0.21%   |
| Razer Blade                  | 6         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 316       | 10.85%  |
| Dell Latitude         | 201       | 6.9%    |
| Acer Aspire           | 162       | 5.56%   |
| Dell Inspiron         | 159       | 5.46%   |
| Dell XPS              | 137       | 4.7%    |
| Toshiba Satellite     | 118       | 4.05%   |
| HP Pavilion           | 114       | 3.91%   |
| Lenovo IdeaPad        | 107       | 3.67%   |
| HP EliteBook          | 83        | 2.85%   |
| HP ProBook            | 50        | 1.72%   |
| HP Laptop             | 48        | 1.65%   |
| ASUS VivoBook         | 41        | 1.41%   |
| Unknown               | 40        | 1.37%   |
| Dell Precision        | 39        | 1.34%   |
| HP Compaq             | 29        | 1%      |
| HP ENVY               | 26        | 0.89%   |
| Valve Jupiter         | 24        | 0.82%   |
| HP Stream             | 23        | 0.79%   |
| Acer Swift            | 20        | 0.69%   |
| Dell Vostro           | 19        | 0.65%   |
| Razer Blade           | 16        | 0.55%   |
| Lenovo Legion         | 16        | 0.55%   |
| HP 255                | 15        | 0.51%   |
| Fujitsu LIFEBOOK      | 15        | 0.51%   |
| ASUS ZenBook          | 15        | 0.51%   |
| Packard Bell EasyNote | 14        | 0.48%   |
| Lenovo Yoga           | 14        | 0.48%   |
| HP ZBook              | 14        | 0.48%   |
| HP Presario           | 14        | 0.48%   |
| HP Notebook           | 14        | 0.48%   |
| Lenovo ThinkBook      | 13        | 0.45%   |
| Acer Nitro            | 13        | 0.45%   |
| Dell System           | 12        | 0.41%   |
| Apple MacBookPro9     | 12        | 0.41%   |
| HP OMEN               | 11        | 0.38%   |
| ASUS ROG              | 11        | 0.38%   |
| Lenovo V145-15AST     | 10        | 0.34%   |
| ASUS TUF              | 10        | 0.34%   |
| Lenovo Z50-75         | 9         | 0.31%   |
| HP 15                 | 9         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 284       | 9.75%   |
| 2019    | 256       | 8.79%   |
| 2012    | 232       | 7.96%   |
| 2020    | 230       | 7.9%    |
| 2013    | 214       | 7.35%   |
| 2011    | 210       | 7.21%   |
| 2017    | 197       | 6.76%   |
| 2015    | 187       | 6.42%   |
| 2016    | 179       | 6.14%   |
| 2014    | 168       | 5.77%   |
| 2021    | 162       | 5.56%   |
| 2010    | 159       | 5.46%   |
| 2008    | 138       | 4.74%   |
| 2009    | 126       | 4.33%   |
| 2007    | 79        | 2.71%   |
| 2022    | 41        | 1.41%   |
| 2006    | 36        | 1.24%   |
| 2005    | 7         | 0.24%   |
| Unknown | 6         | 0.21%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2913      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2595      | 88.15%  |
| Enabled  | 349       | 11.85%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2878      | 98.8%   |
| Yes  | 35        | 1.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 839       | 28.43%  |
| 3.01-4.0    | 626       | 21.21%  |
| 16.01-24.0  | 535       | 18.13%  |
| 8.01-16.0   | 453       | 15.35%  |
| 1.01-2.0    | 189       | 6.4%    |
| 32.01-64.0  | 165       | 5.59%   |
| 2.01-3.0    | 74        | 2.51%   |
| 0.51-1.0    | 30        | 1.02%   |
| 64.01-256.0 | 20        | 0.68%   |
| 24.01-32.0  | 19        | 0.64%   |
| 0.01-0.5    | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1286      | 40.12%  |
| 2.01-3.0   | 788       | 24.59%  |
| 4.01-8.0   | 389       | 12.14%  |
| 3.01-4.0   | 369       | 11.51%  |
| 0.51-1.0   | 241       | 7.52%   |
| 8.01-16.0  | 83        | 2.59%   |
| 0.01-0.5   | 34        | 1.06%   |
| 16.01-24.0 | 9         | 0.28%   |
| 24.01-32.0 | 4         | 0.12%   |
| 32.01-64.0 | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2177      | 73.23%  |
| 2      | 666       | 22.4%   |
| 3      | 75        | 2.52%   |
| 0      | 31        | 1.04%   |
| 4      | 15        | 0.5%    |
| 7      | 3         | 0.1%    |
| 5      | 3         | 0.1%    |
| 9      | 1         | 0.03%   |
| 8      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1790      | 61.09%  |
| Yes       | 1140      | 38.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2302      | 78.86%  |
| No        | 617       | 21.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2869      | 98.42%  |
| No        | 46        | 1.58%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2225      | 75.63%  |
| No        | 717       | 24.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UK      | 2913      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| London        | 176       | 5.54%   |
| Glasgow       | 56        | 1.76%   |
| Manchester    | 53        | 1.67%   |
| Birmingham    | 53        | 1.67%   |
| Edinburgh     | 49        | 1.54%   |
| Bristol       | 44        | 1.38%   |
| Sheffield     | 38        | 1.2%    |
| Islington     | 35        | 1.1%    |
| Nottingham    | 33        | 1.04%   |
| Leeds         | 33        | 1.04%   |
| Liverpool     | 32        | 1.01%   |
| Norwich       | 30        | 0.94%   |
| Cambridge     | 30        | 0.94%   |
| Reading       | 28        | 0.88%   |
| Coventry      | 25        | 0.79%   |
| Aberdeen      | 25        | 0.79%   |
| Leicester     | 23        | 0.72%   |
| Oxford        | 22        | 0.69%   |
| Milton Keynes | 22        | 0.69%   |
| Croydon       | 21        | 0.66%   |
| Kensington    | 20        | 0.63%   |
| Cardiff       | 19        | 0.6%    |
| Brighton      | 19        | 0.6%    |
| Southampton   | 18        | 0.57%   |
| Chesterfield  | 18        | 0.57%   |
| Harrow        | 17        | 0.54%   |
| Bolton        | 17        | 0.54%   |
| Wigan         | 16        | 0.5%    |
| Swindon       | 16        | 0.5%    |
| Gloucester    | 16        | 0.5%    |
| Camden        | 16        | 0.5%    |
| Wolverhampton | 15        | 0.47%   |
| Hackney       | 15        | 0.47%   |
| York          | 14        | 0.44%   |
| Walsall       | 14        | 0.44%   |
| Plymouth      | 14        | 0.44%   |
| Clapham       | 14        | 0.44%   |
| Bromley       | 14        | 0.44%   |
| Bradford      | 14        | 0.44%   |
| Belfast       | 14        | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 545       | 723    | 15.4%   |
| Seagate                   | 395       | 534    | 11.16%  |
| WDC                       | 372       | 468    | 10.51%  |
| Toshiba                   | 334       | 404    | 9.44%   |
| Unknown                   | 290       | 390    | 8.19%   |
| SanDisk                   | 214       | 264    | 6.05%   |
| Crucial                   | 154       | 203    | 4.35%   |
| Hitachi                   | 147       | 170    | 4.15%   |
| SK hynix                  | 138       | 158    | 3.9%    |
| Kingston                  | 135       | 170    | 3.81%   |
| HGST                      | 108       | 155    | 3.05%   |
| Intel                     | 98        | 116    | 2.77%   |
| Micron Technology         | 65        | 78     | 1.84%   |
| Apple                     | 38        | 48     | 1.07%   |
| Phison                    | 35        | 42     | 0.99%   |
| China                     | 32        | 41     | 0.9%    |
| A-DATA Technology         | 32        | 36     | 0.9%    |
| LITEON                    | 30        | 35     | 0.85%   |
| KIOXIA                    | 30        | 35     | 0.85%   |
| Fujitsu                   | 25        | 32     | 0.71%   |
| Transcend                 | 24        | 30     | 0.68%   |
| PNY                       | 24        | 28     | 0.68%   |
| LITEONIT                  | 21        | 26     | 0.59%   |
| Silicon Motion            | 14        | 17     | 0.4%    |
| Unknown                   | 11        | 11     | 0.31%   |
| OCZ                       | 10        | 11     | 0.28%   |
| Integral                  | 9         | 10     | 0.25%   |
| Team                      | 8         | 9      | 0.23%   |
| Corsair                   | 8         | 12     | 0.23%   |
| SPCC                      | 7         | 11     | 0.2%    |
| Lenovo                    | 7         | 7      | 0.2%    |
| TCSUNBOW                  | 6         | 9      | 0.17%   |
| Micron/Crucial Technology | 6         | 6      | 0.17%   |
| Star                      | 5         | 6      | 0.14%   |
| Drevo                     | 5         | 7      | 0.14%   |
| BHT                       | 5         | 8      | 0.14%   |
| XPG                       | 4         | 5      | 0.11%   |
| SABRENT                   | 4         | 4      | 0.11%   |
| Patriot                   | 4         | 9      | 0.11%   |
| O2 Micro                  | 4         | 4      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  32GB             | 81        | 2.19%   |
| Seagate ST1000LM035-1RK172 1TB     | 52        | 1.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 44        | 1.19%   |
| Toshiba MQ01ABD100 1TB             | 38        | 1.03%   |
| Samsung NVMe SSD Drive 512GB       | 37        | 1%      |
| Unknown MMC Card  64GB             | 30        | 0.81%   |
| Unknown MMC Card  128GB            | 30        | 0.81%   |
| Samsung NVMe SSD Drive 256GB       | 29        | 0.78%   |
| HGST HTS721010A9E630 1TB           | 28        | 0.76%   |
| HGST HTS541010A9E680 1TB           | 28        | 0.76%   |
| Toshiba NVMe SSD Drive 256GB       | 25        | 0.68%   |
| Toshiba MQ01ABF050 500GB           | 24        | 0.65%   |
| Samsung SSD 860 EVO 500GB          | 22        | 0.59%   |
| Samsung SSD 850 EVO 500GB          | 22        | 0.59%   |
| Crucial CT500MX500SSD1 500GB       | 22        | 0.59%   |
| Unknown MMC Card  16GB             | 20        | 0.54%   |
| SanDisk NVMe SSD Drive 512GB       | 20        | 0.54%   |
| Samsung NVMe SSD Drive 1024GB      | 20        | 0.54%   |
| Kingston SA400S37240G 240GB SSD    | 20        | 0.54%   |
| Kingston SA400S37120G 120GB SSD    | 19        | 0.51%   |
| SK hynix NVMe SSD Drive 512GB      | 18        | 0.49%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 18        | 0.49%   |
| Toshiba NVMe SSD Drive 512GB       | 17        | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB       | 17        | 0.46%   |
| Samsung SSD 850 EVO 250GB          | 17        | 0.46%   |
| Samsung NVMe SSD Drive 1TB         | 17        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB    | 16        | 0.43%   |
| SanDisk NVMe SSD Drive 256GB       | 16        | 0.43%   |
| Toshiba MQ04ABF100 1TB             | 15        | 0.41%   |
| Seagate ST9500325AS 500GB          | 15        | 0.41%   |
| Crucial CT240BX500SSD1 240GB       | 15        | 0.41%   |
| Unknown SD/MMC/MS PRO 2GB          | 14        | 0.38%   |
| Seagate Expansion 1TB              | 14        | 0.38%   |
| Samsung NVMe SSD Drive 500GB       | 14        | 0.38%   |
| Intel NVMe SSD Drive 512GB         | 14        | 0.38%   |
| HGST HTS725050A7E630 500GB         | 14        | 0.38%   |
| Crucial CT250MX500SSD1 250GB       | 14        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB        | 14        | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 13        | 0.35%   |
| WDC WD10JPCX-24UE4T0 1TB           | 13        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 382       | 514    | 32.57%  |
| WDC                 | 230       | 285    | 19.61%  |
| Toshiba             | 213       | 252    | 18.16%  |
| Hitachi             | 147       | 170    | 12.53%  |
| HGST                | 108       | 155    | 9.21%   |
| Samsung Electronics | 37        | 41     | 3.15%   |
| Fujitsu             | 25        | 32     | 2.13%   |
| Unknown             | 14        | 16     | 1.19%   |
| Apple               | 5         | 5      | 0.43%   |
| ASMT                | 3         | 26     | 0.26%   |
| IBM/Hitachi         | 2         | 2      | 0.17%   |
| PHD 3.0             | 1         | 1      | 0.09%   |
| Maxone              | 1         | 1      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| JMicron Technology  | 1         | 3      | 0.09%   |
| Intenso             | 1         | 1      | 0.09%   |
| HGST HTS            | 1         | 1      | 0.09%   |
| ASMedia             | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 257       | 348    | 21.87%  |
| Crucial             | 142       | 190    | 12.09%  |
| SanDisk             | 138       | 165    | 11.74%  |
| Kingston            | 109       | 132    | 9.28%   |
| WDC                 | 65        | 93     | 5.53%   |
| Intel               | 41        | 45     | 3.49%   |
| Micron Technology   | 35        | 43     | 2.98%   |
| Toshiba             | 31        | 39     | 2.64%   |
| SK hynix            | 31        | 39     | 2.64%   |
| China               | 30        | 39     | 2.55%   |
| LITEON              | 29        | 34     | 2.47%   |
| Apple               | 26        | 35     | 2.21%   |
| Transcend           | 24        | 30     | 2.04%   |
| A-DATA Technology   | 24        | 27     | 2.04%   |
| PNY                 | 23        | 26     | 1.96%   |
| LITEONIT            | 21        | 26     | 1.79%   |
| OCZ                 | 10        | 11     | 0.85%   |
| Integral            | 9         | 10     | 0.77%   |
| Seagate             | 8         | 8      | 0.68%   |
| Unknown             | 7         | 7      | 0.6%    |
| Team                | 7         | 8      | 0.6%    |
| SPCC                | 6         | 10     | 0.51%   |
| Corsair             | 6         | 10     | 0.51%   |
| TCSUNBOW            | 5         | 8      | 0.43%   |
| Star                | 5         | 6      | 0.43%   |
| Drevo               | 5         | 7      | 0.43%   |
| BHT                 | 5         | 8      | 0.43%   |
| Patriot             | 4         | 9      | 0.34%   |
| Lexar               | 4         | 5      | 0.34%   |
| ZTC                 | 3         | 6      | 0.26%   |
| Vaseky              | 3         | 4      | 0.26%   |
| NGFF                | 3         | 3      | 0.26%   |
| Netac               | 3         | 4      | 0.26%   |
| Maxtor              | 3         | 3      | 0.26%   |
| KingDian            | 3         | 6      | 0.26%   |
| BIWIN               | 3         | 3      | 0.26%   |
| Zheino              | 2         | 3      | 0.17%   |
| TO Exter            | 2         | 2      | 0.17%   |
| Plextor             | 2         | 3      | 0.17%   |
| ORTIAL              | 2         | 2      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1139      | 1507   | 33.83%  |
| SSD     | 1079      | 1503   | 32.05%  |
| NVMe    | 826       | 1073   | 24.53%  |
| MMC     | 284       | 387    | 8.43%   |
| Unknown | 39        | 47     | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2046      | 2909   | 62.92%  |
| NVMe | 821       | 1063   | 25.25%  |
| MMC  | 284       | 387    | 8.73%   |
| SAS  | 101       | 158    | 3.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1536      | 2088   | 69.03%  |
| 0.51-1.0   | 591       | 791    | 26.56%  |
| 1.01-2.0   | 86        | 114    | 3.87%   |
| 4.01-10.0  | 8         | 13     | 0.36%   |
| 3.01-4.0   | 2         | 2      | 0.09%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |
| 10.01-20.0 | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 972       | 31.85%  |
| 251-500        | 682       | 22.35%  |
| 501-1000       | 411       | 13.47%  |
| 51-100         | 233       | 7.63%   |
| 1-20           | 229       | 7.5%    |
| 21-50          | 201       | 6.59%   |
| 1001-2000      | 148       | 4.85%   |
| Unknown        | 85        | 2.79%   |
| More than 3000 | 48        | 1.57%   |
| 2001-3000      | 43        | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1416      | 44.71%  |
| 21-50          | 575       | 18.16%  |
| 101-250        | 387       | 12.22%  |
| 51-100         | 364       | 11.49%  |
| 251-500        | 186       | 5.87%   |
| 501-1000       | 86        | 2.72%   |
| Unknown        | 85        | 2.68%   |
| 1001-2000      | 46        | 1.45%   |
| 2001-3000      | 12        | 0.38%   |
| More than 3000 | 10        | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                 | 6         | 6      | 4.26%   |
| HGST HTS725050A7E630 500GB                     | 6         | 9      | 4.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 3         | 3      | 2.13%   |
| Hitachi HTS547575A9E384 752GB                  | 3         | 5      | 2.13%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 2.13%   |
| WDC WD2500BEVT-80A23T0 250GB                   | 2         | 4      | 1.42%   |
| Toshiba MK1656GSY 160GB                        | 2         | 2      | 1.42%   |
| Seagate ST9500325AS 500GB                      | 2         | 3      | 1.42%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 1.42%   |
| Seagate ST500LM021-1KJ152 500GB                | 2         | 2      | 1.42%   |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 3      | 1.42%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 1.42%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 2      | 1.42%   |
| LITEON CS1-SP32-11 M.2 2242 32GB SSD           | 2         | 2      | 1.42%   |
| Hitachi HTS547564A9E384 640GB                  | 2         | 2      | 1.42%   |
| Hitachi HTS545032B9A302 320GB                  | 2         | 3      | 1.42%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 1.42%   |
| Hitachi HTS545025B9A300 250GB                  | 2         | 2      | 1.42%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 1.42%   |
| Hitachi HTS542512K9SA00 120GB                  | 2         | 2      | 1.42%   |
| HGST HTS721010A9E630 1TB                       | 2         | 2      | 1.42%   |
| Crucial CT525MX300SSD4 528GB                   | 2         | 2      | 1.42%   |
| Zheino CHN mSATA02M 256 256GB SSD              | 1         | 2      | 0.71%   |
| WDC WD5000BPVT-55HXZT3 500GB                   | 1         | 1      | 0.71%   |
| WDC WD5000BEVT-75A0RT0 500GB                   | 1         | 1      | 0.71%   |
| WDC WD5000BEVT-60A0RT0 500GB                   | 1         | 2      | 0.71%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 0.71%   |
| WDC WD3200LPCX-24C6HT0 320GB                   | 1         | 1      | 0.71%   |
| WDC WD3200BEKT-75PVMT0 320GB                   | 1         | 1      | 0.71%   |
| WDC WD2500BEVT-75A23T0 250GB                   | 1         | 1      | 0.71%   |
| WDC WD2500BEVT-60A23T0 250GB                   | 1         | 1      | 0.71%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB           | 1         | 1      | 0.71%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD           | 1         | 1      | 0.71%   |
| Toshiba MK6475GSX 640GB                        | 1         | 1      | 0.71%   |
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 0.71%   |
| Toshiba MK3276GSX -63 320GB                    | 1         | 1      | 0.71%   |
| Toshiba MK3256GSY 320GB                        | 1         | 1      | 0.71%   |
| Toshiba MK1655GSXF 160GB                       | 1         | 1      | 0.71%   |
| Toshiba MK1629GSG 160GB                        | 1         | 1      | 0.71%   |
| Toshiba MK1214GAH 120GB                        | 1         | 1      | 0.71%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 40     | 26.95%  |
| Hitachi             | 26        | 29     | 18.44%  |
| HGST                | 15        | 18     | 10.64%  |
| Toshiba             | 12        | 12     | 8.51%   |
| WDC                 | 11        | 14     | 7.8%    |
| Crucial             | 9         | 9      | 6.38%   |
| Samsung Electronics | 5         | 5      | 3.55%   |
| SanDisk             | 4         | 4      | 2.84%   |
| Intel               | 4         | 4      | 2.84%   |
| Micron Technology   | 3         | 3      | 2.13%   |
| Fujitsu             | 3         | 3      | 2.13%   |
| LITEON              | 2         | 2      | 1.42%   |
| Kingston            | 2         | 2      | 1.42%   |
| A-DATA Technology   | 2         | 2      | 1.42%   |
| Zheino              | 1         | 2      | 0.71%   |
| Team                | 1         | 1      | 0.71%   |
| SK hynix            | 1         | 1      | 0.71%   |
| Drevo               | 1         | 1      | 0.71%   |
| Corsair             | 1         | 1      | 0.71%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 40     | 36.19%  |
| Hitachi             | 26        | 29     | 24.76%  |
| HGST                | 15        | 18     | 14.29%  |
| Toshiba             | 11        | 11     | 10.48%  |
| WDC                 | 10        | 13     | 9.52%   |
| Fujitsu             | 3         | 3      | 2.86%   |
| Samsung Electronics | 2         | 2      | 1.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 105       | 116    | 74.47%  |
| SSD  | 34        | 35     | 24.11%  |
| NVMe | 2         | 2      | 1.42%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 2      | 50%     |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 3      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1989      | 3131   | 65.3%   |
| Works    | 916       | 1230   | 30.07%  |
| Malfunc  | 139       | 153    | 4.56%   |
| Failed   | 2         | 3      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2046      | 61.87%  |
| AMD                              | 350       | 10.58%  |
| Samsung Electronics              | 296       | 8.95%   |
| SanDisk                          | 140       | 4.23%   |
| SK hynix                         | 102       | 3.08%   |
| Toshiba America Info Systems     | 96        | 2.9%    |
| Phison Electronics               | 44        | 1.33%   |
| Nvidia                           | 32        | 0.97%   |
| Micron Technology                | 32        | 0.97%   |
| KIOXIA                           | 30        | 0.91%   |
| Kingston Technology Company      | 30        | 0.91%   |
| Micron/Crucial Technology        | 17        | 0.51%   |
| Silicon Motion                   | 16        | 0.48%   |
| Silicon Integrated Systems [SiS] | 12        | 0.36%   |
| ADATA Technology                 | 12        | 0.36%   |
| Lenovo                           | 7         | 0.21%   |
| Apple                            | 6         | 0.18%   |
| Solid State Storage Technology   | 5         | 0.15%   |
| Marvell Technology Group         | 5         | 0.15%   |
| VIA Technologies                 | 4         | 0.12%   |
| O2 Micro                         | 4         | 0.12%   |
| Shenzhen Longsys Electronics     | 3         | 0.09%   |
| Lite-On Technology               | 3         | 0.09%   |
| JMicron Technology               | 3         | 0.09%   |
| Yangtze Memory Technologies      | 2         | 0.06%   |
| Union Memory (Shenzhen)          | 2         | 0.06%   |
| ASMedia Technology               | 2         | 0.06%   |
| Silicon Image                    | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| Realtek Semiconductor            | 1         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.03%   |
| Enmotus                          | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 289       | 8.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 229       | 6.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 200       | 5.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 196       | 5.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 160       | 4.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 153       | 4.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 139       | 3.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 101       | 2.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 97        | 2.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 88        | 2.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 75        | 2.11%   |
| Intel Volume Management Device NVMe RAID Controller                              | 67        | 1.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 64        | 1.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 63        | 1.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 62        | 1.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 62        | 1.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 53        | 1.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 45        | 1.27%   |
| Samsung NVMe SSD Controller 980                                                  | 45        | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 40        | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 38        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 38        | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 37        | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                            | 36        | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 36        | 1.01%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 35        | 0.98%   |
| SK hynix Gold P31 SSD                                                            | 34        | 0.96%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 33        | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 32        | 0.9%    |
| Micron Non-Volatile memory controller                                            | 32        | 0.9%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 32        | 0.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 32        | 0.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 31        | 0.87%   |
| SK hynix Non-Volatile memory controller                                          | 28        | 0.79%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 25        | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 25        | 0.7%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 24        | 0.67%   |
| Intel SSD 660P Series                                                            | 23        | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 22        | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 21        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2043      | 59.98%  |
| NVMe | 834       | 24.49%  |
| RAID | 267       | 7.84%   |
| IDE  | 262       | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2450      | 84.11%  |
| AMD    | 462       | 15.86%  |
| ARM    | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 49        | 1.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 43        | 1.48%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 40        | 1.37%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 37        | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 37        | 1.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 35        | 1.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 35        | 1.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 35        | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 34        | 1.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 33        | 1.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 33        | 1.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 33        | 1.13%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 31        | 1.06%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 31        | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 29        | 1%      |
| Intel Celeron CPU N2840 @ 2.16GHz             | 28        | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 27        | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 26        | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 0.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.86%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 24        | 0.82%   |
| AMD Custom APU 0405                           | 24        | 0.82%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 23        | 0.79%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 23        | 0.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 22        | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 22        | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.75%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 22        | 0.75%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 22        | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 20        | 0.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 19        | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 18        | 0.62%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 18        | 0.62%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 18        | 0.62%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 17        | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 17        | 0.58%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 17        | 0.58%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 16        | 0.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 16        | 0.55%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 16        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 727       | 24.95%  |
| Intel Core i7           | 673       | 23.1%   |
| Intel Core i3           | 205       | 7.04%   |
| Intel Celeron           | 202       | 6.93%   |
| Other                   | 171       | 5.87%   |
| Intel Core 2 Duo        | 166       | 5.7%    |
| Intel Pentium           | 89        | 3.05%   |
| AMD Ryzen 5             | 78        | 2.68%   |
| AMD Ryzen 7             | 70        | 2.4%    |
| Intel Atom              | 65        | 2.23%   |
| AMD A6                  | 51        | 1.75%   |
| AMD A8                  | 34        | 1.17%   |
| Intel Pentium Dual-Core | 30        | 1.03%   |
| Intel Core 2            | 28        | 0.96%   |
| AMD Ryzen 3             | 26        | 0.89%   |
| Intel Pentium Dual      | 24        | 0.82%   |
| Intel Genuine           | 23        | 0.79%   |
| Intel Celeron Dual-Core | 19        | 0.65%   |
| AMD A4                  | 17        | 0.58%   |
| Intel Core i9           | 15        | 0.51%   |
| AMD E1                  | 15        | 0.51%   |
| AMD E                   | 14        | 0.48%   |
| AMD A10                 | 14        | 0.48%   |
| Intel Celeron M         | 13        | 0.45%   |
| AMD E2                  | 11        | 0.38%   |
| AMD Ryzen 9             | 10        | 0.34%   |
| Intel Pentium Silver    | 9         | 0.31%   |
| Intel Pentium M         | 9         | 0.31%   |
| AMD Turion 64 X2 Mobile | 7         | 0.24%   |
| AMD FX                  | 7         | 0.24%   |
| AMD Athlon II           | 7         | 0.24%   |
| AMD Athlon              | 7         | 0.24%   |
| AMD Ryzen 7 PRO         | 6         | 0.21%   |
| AMD Athlon X2           | 6         | 0.21%   |
| AMD Turion 64 Mobile    | 5         | 0.17%   |
| AMD Phenom II           | 5         | 0.17%   |
| Intel Core m3           | 4         | 0.14%   |
| Intel Core M            | 4         | 0.14%   |
| AMD C-70                | 4         | 0.14%   |
| Intel Core Duo          | 3         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1659      | 56.93%  |
| 4      | 863       | 29.62%  |
| 6      | 167       | 5.73%   |
| 8      | 114       | 3.91%   |
| 1      | 93        | 3.19%   |
| 14     | 11        | 0.38%   |
| 12     | 3         | 0.1%    |
| 10     | 2         | 0.07%   |
| 3      | 2         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2912      | 99.97%  |
| 2      | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2005      | 68.83%  |
| 1      | 908       | 31.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2814      | 96.21%  |
| Unknown        | 57        | 1.95%   |
| 32-bit         | 54        | 1.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 612       | 20.37%  |
| 0x306a9    | 200       | 6.66%   |
| 0x206a7    | 183       | 6.09%   |
| 0x1067a    | 131       | 4.36%   |
| 0x806ea    | 102       | 3.4%    |
| 0x40651    | 102       | 3.4%    |
| 0x806ec    | 95        | 3.16%   |
| 0x406e3    | 94        | 3.13%   |
| 0x806e9    | 87        | 2.9%    |
| 0x20655    | 87        | 2.9%    |
| 0x306d4    | 81        | 2.7%    |
| 0x906ea    | 78        | 2.6%    |
| 0x806c1    | 64        | 2.13%   |
| 0x6fd      | 61        | 2.03%   |
| 0x406c4    | 57        | 1.9%    |
| 0x306c3    | 56        | 1.86%   |
| 0x30678    | 50        | 1.66%   |
| 0x906e9    | 43        | 1.43%   |
| 0xa0652    | 41        | 1.36%   |
| 0x506e3    | 37        | 1.23%   |
| 0x506c9    | 36        | 1.2%    |
| 0x06006705 | 35        | 1.17%   |
| 0x08108102 | 31        | 1.03%   |
| 0x08108109 | 29        | 0.97%   |
| 0x406c3    | 28        | 0.93%   |
| 0x07030105 | 28        | 0.93%   |
| 0x20652    | 27        | 0.9%    |
| 0x10676    | 27        | 0.9%    |
| 0x706e5    | 26        | 0.87%   |
| 0x706a1    | 25        | 0.83%   |
| 0x6f6      | 23        | 0.77%   |
| 0x806d1    | 22        | 0.73%   |
| 0x06006704 | 21        | 0.7%    |
| 0x806eb    | 19        | 0.63%   |
| 0x05000119 | 19        | 0.63%   |
| 0x08600106 | 17        | 0.57%   |
| 0x08600104 | 17        | 0.57%   |
| 0x906ed    | 15        | 0.5%    |
| 0x0a50000c | 15        | 0.5%    |
| 0x6d8      | 13        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 547       | 18.77%  |
| IvyBridge        | 229       | 7.86%   |
| SandyBridge      | 217       | 7.45%   |
| Haswell          | 211       | 7.24%   |
| Penryn           | 178       | 6.11%   |
| Silvermont       | 163       | 5.59%   |
| Skylake          | 151       | 5.18%   |
| Westmere         | 136       | 4.67%   |
| Core             | 130       | 4.46%   |
| Broadwell        | 109       | 3.74%   |
| TigerLake        | 83        | 2.85%   |
| Zen+             | 75        | 2.57%   |
| Excavator        | 70        | 2.4%    |
| CometLake        | 59        | 2.02%   |
| Unknown          | 57        | 1.96%   |
| IceLake          | 56        | 1.92%   |
| Zen 2            | 54        | 1.85%   |
| Puma             | 42        | 1.44%   |
| Goldmont         | 42        | 1.44%   |
| P6               | 38        | 1.3%    |
| Goldmont plus    | 36        | 1.24%   |
| Bobcat           | 30        | 1.03%   |
| Zen              | 27        | 0.93%   |
| Bonnell          | 26        | 0.89%   |
| Zen 3            | 25        | 0.86%   |
| K10              | 20        | 0.69%   |
| Piledriver       | 19        | 0.65%   |
| K8 Hammer        | 17        | 0.58%   |
| Jaguar           | 15        | 0.51%   |
| Alderlake Hybrid | 13        | 0.45%   |
| Steamroller      | 11        | 0.38%   |
| K8 & K10 hybrid  | 10        | 0.34%   |
| Nehalem          | 9         | 0.31%   |
| K10 Llano        | 5         | 0.17%   |
| Tremont          | 2         | 0.07%   |
| NetBurst         | 2         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2234      | 63.9%   |
| Nvidia                           | 684       | 19.57%  |
| AMD                              | 561       | 16.05%  |
| Silicon Integrated Systems [SiS] | 12        | 0.34%   |
| VIA Technologies                 | 4         | 0.11%   |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 218       | 6.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 206       | 5.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 141       | 3.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 122       | 3.37%   |
| Intel UHD Graphics 620                                                                   | 114       | 3.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 112       | 3.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 108       | 2.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 95        | 2.63%   |
| Intel HD Graphics 620                                                                    | 94        | 2.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 93        | 2.57%   |
| Intel HD Graphics 5500                                                                   | 84        | 2.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 80        | 2.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 77        | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 76        | 2.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 75        | 2.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 68        | 1.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 60        | 1.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 57        | 1.58%   |
| Intel HD Graphics 630                                                                    | 53        | 1.46%   |
| AMD Renoir                                                                               | 50        | 1.38%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 49        | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 47        | 1.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 47        | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 39        | 1.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 36        | 1%      |
| Intel HD Graphics 500                                                                    | 36        | 1%      |
| Intel HD Graphics 530                                                                    | 31        | 0.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 30        | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 29        | 0.8%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 29        | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 28        | 0.77%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 28        | 0.77%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 28        | 0.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25        | 0.69%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 24        | 0.66%   |
| AMD Cezanne                                                                              | 21        | 0.58%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 19        | 0.53%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 18        | 0.5%    |
| AMD Lucienne                                                                             | 18        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1690      | 57.84%  |
| Intel + Nvidia           | 482       | 16.5%   |
| 1 x AMD                  | 444       | 15.2%   |
| 1 x Nvidia               | 165       | 5.65%   |
| Intel + AMD              | 62        | 2.12%   |
| AMD + Nvidia             | 33        | 1.13%   |
| 2 x AMD                  | 21        | 0.72%   |
| 1 x SiS                  | 12        | 0.41%   |
| Other                    | 4         | 0.14%   |
| 1 x VIA                  | 4         | 0.14%   |
| 2 x Nvidia               | 2         | 0.07%   |
| 2 x Intel                | 1         | 0.03%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2522      | 85.61%  |
| Proprietary | 355       | 12.05%  |
| Unknown     | 69        | 2.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1970      | 66.04%  |
| 0.01-0.5   | 372       | 12.47%  |
| 1.01-2.0   | 273       | 9.15%   |
| 3.01-4.0   | 149       | 4.99%   |
| 0.51-1.0   | 127       | 4.26%   |
| 5.01-6.0   | 52        | 1.74%   |
| 7.01-8.0   | 31        | 1.04%   |
| 2.01-3.0   | 7         | 0.23%   |
| 8.01-16.0  | 2         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 642       | 20.32%  |
| LG Display              | 493       | 15.61%  |
| Chimei Innolux          | 373       | 11.81%  |
| Samsung Electronics     | 341       | 10.79%  |
| BOE                     | 333       | 10.54%  |
| Sharp                   | 154       | 4.87%   |
| Apple                   | 92        | 2.91%   |
| Dell                    | 74        | 2.34%   |
| Chi Mei Optoelectronics | 65        | 2.06%   |
| Lenovo                  | 63        | 1.99%   |
| PANDA                   | 51        | 1.61%   |
| Goldstar                | 46        | 1.46%   |
| LG Philips              | 42        | 1.33%   |
| Hewlett-Packard         | 30        | 0.95%   |
| InfoVision              | 28        | 0.89%   |
| Acer                    | 25        | 0.79%   |
| BenQ                    | 24        | 0.76%   |
| AOC                     | 21        | 0.66%   |
| ANX                     | 21        | 0.66%   |
| Iiyama                  | 18        | 0.57%   |
| Philips                 | 17        | 0.54%   |
| Ancor Communications    | 15        | 0.47%   |
| Sony                    | 14        | 0.44%   |
| Panasonic               | 13        | 0.41%   |
| Toshiba                 | 12        | 0.38%   |
| LGD                     | 12        | 0.38%   |
| InnoLux Display         | 10        | 0.32%   |
| HannStar                | 10        | 0.32%   |
| ViewSonic               | 9         | 0.28%   |
| CSO                     | 9         | 0.28%   |
| CPT                     | 7         | 0.22%   |
| Quanta Display          | 6         | 0.19%   |
| ASUSTek Computer        | 6         | 0.19%   |
| Vestel Elektronik       | 5         | 0.16%   |
| Seiko/Epson             | 5         | 0.16%   |
| Unknown                 | 3         | 0.09%   |
| TMX                     | 3         | 0.09%   |
| MSI                     | 3         | 0.09%   |
| Lenovo Group Limited    | 3         | 0.09%   |
| JDI                     | 3         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 37        | 1.16%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 28        | 0.88%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 27        | 0.85%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 26        | 0.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 24        | 0.75%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 24        | 0.75%   |
| ANX ANX7530 U ANX7539 800x1280                                       | 21        | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 20        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 16        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 15        | 0.47%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 13        | 0.41%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 13        | 0.41%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 13        | 0.41%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 13        | 0.41%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch              | 12        | 0.38%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch | 12        | 0.38%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 12        | 0.38%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 12        | 0.38%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 11        | 0.35%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch | 11        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 11        | 0.35%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 11        | 0.35%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 11        | 0.35%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 11        | 0.35%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch        | 11        | 0.35%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 10        | 0.31%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 10        | 0.31%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch              | 10        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 10        | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 10        | 0.31%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 10        | 0.31%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 9         | 0.28%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 9         | 0.28%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch          | 9         | 0.28%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch          | 9         | 0.28%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 9         | 0.28%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch        | 9         | 0.28%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 9         | 0.28%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 9         | 0.28%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch              | 8         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1161      | 38.3%   |
| 1366x768 (WXGA)    | 968       | 31.94%  |
| 1280x800 (WXGA)    | 178       | 5.87%   |
| 3840x2160 (4K)     | 132       | 4.35%   |
| 1600x900 (HD+)     | 127       | 4.19%   |
| 2560x1440 (QHD)    | 75        | 2.47%   |
| 1440x900 (WXGA+)   | 68        | 2.24%   |
| 1920x1200 (WUXGA)  | 47        | 1.55%   |
| 2560x1600          | 29        | 0.96%   |
| 1680x1050 (WSXGA+) | 25        | 0.82%   |
| 800x1280           | 24        | 0.79%   |
| 3840x2400          | 24        | 0.79%   |
| 3200x1800 (QHD+)   | 20        | 0.66%   |
| 1024x600           | 17        | 0.56%   |
| 3440x1440          | 16        | 0.53%   |
| 1280x1024 (SXGA)   | 14        | 0.46%   |
| 2880x1800          | 13        | 0.43%   |
| 2160x1440          | 11        | 0.36%   |
| 2560x1080          | 10        | 0.33%   |
| Unknown            | 10        | 0.33%   |
| 1360x768           | 8         | 0.26%   |
| 1024x768 (XGA)     | 6         | 0.2%    |
| 2256x1504          | 4         | 0.13%   |
| 1680x945           | 4         | 0.13%   |
| 3456x2160          | 3         | 0.1%    |
| 3072x1920          | 3         | 0.1%    |
| 1920x540           | 3         | 0.1%    |
| 1280x768           | 3         | 0.1%    |
| 3000x2000          | 2         | 0.07%   |
| 2880x1920          | 2         | 0.07%   |
| 2560x1700          | 2         | 0.07%   |
| 2520x1680          | 2         | 0.07%   |
| 2160x1350          | 2         | 0.07%   |
| 1920x1280          | 2         | 0.07%   |
| 1360x765           | 2         | 0.07%   |
| 8960x2160          | 1         | 0.03%   |
| 800x480            | 1         | 0.03%   |
| 7680x1080          | 1         | 0.03%   |
| 4800x1800          | 1         | 0.03%   |
| 3840x1600          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1331      | 42.25%  |
| 13      | 509       | 16.16%  |
| 14      | 306       | 9.71%   |
| 17      | 204       | 6.48%   |
| 12      | 146       | 4.63%   |
| 11      | 91        | 2.89%   |
| 27      | 80        | 2.54%   |
| Unknown | 77        | 2.44%   |
| 24      | 66        | 2.1%    |
| 21      | 57        | 1.81%   |
| 23      | 52        | 1.65%   |
| 18      | 24        | 0.76%   |
| 10      | 23        | 0.73%   |
| 34      | 22        | 0.7%    |
| 31      | 21        | 0.67%   |
| 16      | 19        | 0.6%    |
| 84      | 15        | 0.48%   |
| 19      | 14        | 0.44%   |
| 25      | 11        | 0.35%   |
| 22      | 11        | 0.35%   |
| 72      | 8         | 0.25%   |
| 54      | 7         | 0.22%   |
| 26      | 7         | 0.22%   |
| 8       | 6         | 0.19%   |
| 65      | 4         | 0.13%   |
| 48      | 4         | 0.13%   |
| 20      | 4         | 0.13%   |
| 50      | 3         | 0.1%    |
| 40      | 3         | 0.1%    |
| 35      | 3         | 0.1%    |
| 33      | 3         | 0.1%    |
| 32      | 3         | 0.1%    |
| 28      | 3         | 0.1%    |
| 49      | 2         | 0.06%   |
| 46      | 2         | 0.06%   |
| 99      | 1         | 0.03%   |
| 86      | 1         | 0.03%   |
| 75      | 1         | 0.03%   |
| 63      | 1         | 0.03%   |
| 55      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1815      | 57.78%  |
| 201-300        | 564       | 17.96%  |
| 351-400        | 261       | 8.31%   |
| 501-600        | 202       | 6.43%   |
| 401-500        | 97        | 3.09%   |
| Unknown        | 77        | 2.45%   |
| 601-700        | 32        | 1.02%   |
| 701-800        | 28        | 0.89%   |
| 1501-2000      | 25        | 0.8%    |
| 1001-1500      | 24        | 0.76%   |
| 801-900        | 7         | 0.22%   |
| 101-200        | 6         | 0.19%   |
| 901-1000       | 2         | 0.06%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2343      | 81.67%  |
| 16/10   | 366       | 12.76%  |
| Unknown | 48        | 1.67%   |
| 3/2     | 33        | 1.15%   |
| 21/9    | 27        | 0.94%   |
| 0.62    | 25        | 0.87%   |
| 4/3     | 13        | 0.45%   |
| 5/4     | 9         | 0.31%   |
| 6/5     | 3         | 0.1%    |
| 32/9    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1327      | 42.18%  |
| 81-90          | 563       | 17.9%   |
| 71-80          | 252       | 8.01%   |
| 121-130        | 168       | 5.34%   |
| 201-250        | 154       | 4.9%    |
| 61-70          | 141       | 4.48%   |
| 51-60          | 92        | 2.92%   |
| 301-350        | 85        | 2.7%    |
| Unknown        | 77        | 2.45%   |
| 351-500        | 54        | 1.72%   |
| More than 1000 | 47        | 1.49%   |
| 131-140        | 37        | 1.18%   |
| 251-300        | 33        | 1.05%   |
| 151-200        | 30        | 0.95%   |
| 141-150        | 23        | 0.73%   |
| 41-50          | 22        | 0.7%    |
| 111-120        | 18        | 0.57%   |
| 501-1000       | 9         | 0.29%   |
| 91-100         | 8         | 0.25%   |
| 1-40           | 6         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1199      | 38.57%  |
| 101-120       | 979       | 31.49%  |
| 51-100        | 434       | 13.96%  |
| 161-240       | 250       | 8.04%   |
| More than 240 | 130       | 4.18%   |
| Unknown       | 77        | 2.48%   |
| 1-50          | 40        | 1.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2499      | 84.37%  |
| 2     | 360       | 12.15%  |
| 0     | 68        | 2.3%    |
| 3     | 31        | 1.05%   |
| 4     | 3         | 0.1%    |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1595      | 34.98%  |
| Realtek Semiconductor             | 1353      | 29.67%  |
| Qualcomm Atheros                  | 666       | 14.61%  |
| Broadcom                          | 359       | 7.87%   |
| Broadcom Limited                  | 80        | 1.75%   |
| Marvell Technology Group          | 79        | 1.73%   |
| Ralink                            | 41        | 0.9%    |
| Ralink Technology                 | 37        | 0.81%   |
| Ericsson Business Mobile Networks | 35        | 0.77%   |
| TP-Link                           | 34        | 0.75%   |
| Dell                              | 29        | 0.64%   |
| MediaTek                          | 25        | 0.55%   |
| Nvidia                            | 23        | 0.5%    |
| DisplayLink                       | 18        | 0.39%   |
| Hewlett-Packard                   | 16        | 0.35%   |
| ASIX Electronics                  | 16        | 0.35%   |
| Lenovo                            | 14        | 0.31%   |
| Qualcomm                          | 13        | 0.29%   |
| Samsung Electronics               | 12        | 0.26%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.24%   |
| Huawei Technologies               | 10        | 0.22%   |
| JMicron Technology                | 9         | 0.2%    |
| Sierra Wireless                   | 8         | 0.18%   |
| Qualcomm Atheros Communications   | 6         | 0.13%   |
| NetGear                           | 5         | 0.11%   |
| Edimax Technology                 | 5         | 0.11%   |
| Belkin Components                 | 5         | 0.11%   |
| Attansic Technology               | 5         | 0.11%   |
| VIA Technologies                  | 4         | 0.09%   |
| Micro Star International          | 4         | 0.09%   |
| ICS Advent                        | 4         | 0.09%   |
| Apple                             | 4         | 0.09%   |
| Motorola PCS                      | 3         | 0.07%   |
| ASUSTek Computer                  | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.04%   |
| Linksys                           | 2         | 0.04%   |
| Google                            | 2         | 0.04%   |
| Arduino SA                        | 2         | 0.04%   |
| AMD                               | 2         | 0.04%   |
| ZyDAS                             | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 744       | 13.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 319       | 5.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 138       | 2.49%   |
| Intel Wi-Fi 6 AX200                                                     | 136       | 2.46%   |
| Intel Wireless 8265 / 8275                                              | 126       | 2.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 116       | 2.09%   |
| Intel Wireless 7260                                                     | 114       | 2.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 114       | 2.06%   |
| Intel Wireless 7265                                                     | 113       | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 105       | 1.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 90        | 1.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 87        | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 83        | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 74        | 1.34%   |
| Intel Wireless 8260                                                     | 73        | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 67        | 1.21%   |
| Intel Wireless 3165                                                     | 64        | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 62        | 1.12%   |
| Intel 82577LM Gigabit Network Connection                                | 61        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 60        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 55        | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 53        | 0.96%   |
| Intel Wi-Fi 6 AX201                                                     | 53        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 53        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 52        | 0.94%   |
| Intel Ethernet Connection I218-LM                                       | 51        | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 0.78%   |
| Intel Wireless 3160                                                     | 43        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                   | 43        | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 43        | 0.78%   |
| Intel WiFi Link 5100                                                    | 42        | 0.76%   |
| Intel Wireless-AC 9260                                                  | 41        | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 41        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 40        | 0.72%   |
| Intel Centrino Ultimate-N 6300                                          | 39        | 0.7%    |
| Intel Centrino Advanced-N 6200                                          | 39        | 0.7%    |
| Intel Centrino Advanced-N 6235                                          | 37        | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                   | 34        | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 34        | 0.61%   |
| Realtek 802.11ac NIC                                                    | 33        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1527      | 50.15%  |
| Qualcomm Atheros                  | 581       | 19.08%  |
| Realtek Semiconductor             | 411       | 13.5%   |
| Broadcom                          | 265       | 8.7%    |
| Broadcom Limited                  | 62        | 2.04%   |
| Ralink                            | 41        | 1.35%   |
| Ralink Technology                 | 37        | 1.22%   |
| TP-Link                           | 28        | 0.92%   |
| MediaTek                          | 20        | 0.66%   |
| Dell                              | 15        | 0.49%   |
| Sierra Wireless                   | 8         | 0.26%   |
| Qualcomm Atheros Communications   | 6         | 0.2%    |
| Qualcomm                          | 5         | 0.16%   |
| NetGear                           | 5         | 0.16%   |
| Ericsson Business Mobile Networks | 5         | 0.16%   |
| Edimax Technology                 | 5         | 0.16%   |
| Belkin Components                 | 5         | 0.16%   |
| Micro Star International          | 4         | 0.13%   |
| ASUSTek Computer                  | 2         | 0.07%   |
| ZyDAS                             | 1         | 0.03%   |
| Wacom                             | 1         | 0.03%   |
| Senao                             | 1         | 0.03%   |
| Microsoft                         | 1         | 0.03%   |
| Marvell Technology Group          | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| InProComm                         | 1         | 0.03%   |
| Hewlett-Packard                   | 1         | 0.03%   |
| Fujitsu Siemens Computers         | 1         | 0.03%   |
| FIBOCOM                           | 1         | 0.03%   |
| D-Link                            | 1         | 0.03%   |
| Apple                             | 1         | 0.03%   |
| 3Com                              | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 136       | 4.44%   |
| Intel Wireless 8265 / 8275                                              | 126       | 4.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 116       | 3.79%   |
| Intel Wireless 7260                                                     | 114       | 3.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 114       | 3.72%   |
| Intel Wireless 7265                                                     | 113       | 3.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 105       | 3.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 87        | 2.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 83        | 2.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 74        | 2.42%   |
| Intel Wireless 8260                                                     | 73        | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 67        | 2.19%   |
| Intel Wireless 3165                                                     | 64        | 2.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 62        | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 60        | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 55        | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 53        | 1.73%   |
| Intel Wi-Fi 6 AX201                                                     | 53        | 1.73%   |
| Broadcom BCM43142 802.11b/g/n                                           | 53        | 1.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 52        | 1.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 1.4%    |
| Intel Wireless 3160                                                     | 43        | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 43        | 1.4%    |
| Intel WiFi Link 5100                                                    | 42        | 1.37%   |
| Intel Wireless-AC 9260                                                  | 41        | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 41        | 1.34%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 40        | 1.31%   |
| Intel Centrino Ultimate-N 6300                                          | 39        | 1.27%   |
| Intel Centrino Advanced-N 6200                                          | 39        | 1.27%   |
| Intel Centrino Advanced-N 6235                                          | 37        | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 34        | 1.11%   |
| Realtek 802.11ac NIC                                                    | 33        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 31        | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 28        | 0.91%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 27        | 0.88%   |
| Intel Centrino Wireless-N 2230                                          | 26        | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 25        | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 25        | 0.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 24        | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 23        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1198      | 50.48%  |
| Intel                            | 607       | 25.58%  |
| Qualcomm Atheros                 | 157       | 6.62%   |
| Broadcom                         | 152       | 6.41%   |
| Marvell Technology Group         | 78        | 3.29%   |
| Nvidia                           | 23        | 0.97%   |
| Broadcom Limited                 | 21        | 0.88%   |
| DisplayLink                      | 18        | 0.76%   |
| ASIX Electronics                 | 16        | 0.67%   |
| Lenovo                           | 13        | 0.55%   |
| Samsung Electronics              | 12        | 0.51%   |
| Silicon Integrated Systems [SiS] | 10        | 0.42%   |
| JMicron Technology               | 9         | 0.38%   |
| Qualcomm                         | 8         | 0.34%   |
| Huawei Technologies              | 8         | 0.34%   |
| TP-Link                          | 6         | 0.25%   |
| Attansic Technology              | 5         | 0.21%   |
| VIA Technologies                 | 4         | 0.17%   |
| MediaTek                         | 4         | 0.17%   |
| ICS Advent                       | 4         | 0.17%   |
| Motorola PCS                     | 3         | 0.13%   |
| Hewlett-Packard                  | 3         | 0.13%   |
| Apple                            | 3         | 0.13%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.08%   |
| Google                           | 2         | 0.08%   |
| Xiaomi                           | 1         | 0.04%   |
| T & A Mobile Phones              | 1         | 0.04%   |
| OPPO Electronics                 | 1         | 0.04%   |
| Microchip Technology             | 1         | 0.04%   |
| Linksys                          | 1         | 0.04%   |
| ASUSTek Computer                 | 1         | 0.04%   |
| Aquantia                         | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 744       | 31.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 319       | 13.34%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 138       | 5.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 90        | 3.76%   |
| Intel 82577LM Gigabit Network Connection                          | 61        | 2.55%   |
| Intel Ethernet Connection I218-LM                                 | 51        | 2.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 43        | 1.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 34        | 1.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 31        | 1.3%    |
| Intel Ethernet Connection I219-LM                                 | 31        | 1.3%    |
| Intel 82567LM Gigabit Network Connection                          | 30        | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 1.21%   |
| Intel Ethernet Connection (4) I219-V                              | 27        | 1.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 23        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 22        | 0.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 21        | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 16        | 0.67%   |
| Intel Ethernet Connection I219-V                                  | 15        | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 15        | 0.63%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 14        | 0.59%   |
| Intel 82566MM Gigabit Network Connection                          | 13        | 0.54%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 13        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 12        | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 12        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 11        | 0.46%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 11        | 0.46%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 11        | 0.46%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 11        | 0.46%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 10        | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 10        | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                            | 10        | 0.42%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 10        | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 10        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2868      | 54.63%  |
| Ethernet | 2299      | 43.79%  |
| Modem    | 79        | 1.5%    |
| Unknown  | 4         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2468      | 80.52%  |
| Ethernet | 596       | 19.45%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2120      | 72.68%  |
| 1     | 739       | 25.33%  |
| 0     | 44        | 1.51%   |
| 3     | 13        | 0.45%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2659      | 89.89%  |
| Yes  | 299       | 10.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1079      | 48.02%  |
| Qualcomm Atheros Communications | 218       | 9.7%    |
| Realtek Semiconductor           | 175       | 7.79%   |
| Broadcom                        | 164       | 7.3%    |
| IMC Networks                    | 98        | 4.36%   |
| Apple                           | 83        | 3.69%   |
| Lite-On Technology              | 80        | 3.56%   |
| Foxconn / Hon Hai               | 70        | 3.12%   |
| Dell                            | 66        | 2.94%   |
| Cambridge Silicon Radio         | 54        | 2.4%    |
| Toshiba                         | 41        | 1.82%   |
| Hewlett-Packard                 | 36        | 1.6%    |
| Realtek                         | 19        | 0.85%   |
| Alps Electric                   | 17        | 0.76%   |
| Foxconn International           | 13        | 0.58%   |
| Ralink                          | 9         | 0.4%    |
| Askey Computer                  | 6         | 0.27%   |
| Ralink Technology               | 5         | 0.22%   |
| ASUSTek Computer                | 5         | 0.22%   |
| Taiyo Yuden                     | 4         | 0.18%   |
| Belkin Components               | 2         | 0.09%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 498       | 22.15%  |
| Intel AX201 Bluetooth                               | 156       | 6.94%   |
| Intel AX200 Bluetooth                               | 132       | 5.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 116       | 5.16%   |
| Realtek Bluetooth Radio                             | 104       | 4.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 81        | 3.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 57        | 2.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 56        | 2.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 55        | 2.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 54        | 2.4%    |
| Apple Bluetooth Host Controller                     | 51        | 2.27%   |
| Foxconn / Hon Hai Bluetooth Device                  | 43        | 1.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 41        | 1.82%   |
| Broadcom BCM2045B (BDC-2.1)                         | 35        | 1.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 34        | 1.51%   |
| Intel Wireless-AC 3168 Bluetooth                    | 34        | 1.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 33        | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 1.11%   |
| IMC Networks Bluetooth Radio                        | 24        | 1.07%   |
| IMC Networks 802.11ac WLAN Adapter                  | 24        | 1.07%   |
| Dell DW375 Bluetooth Module                         | 24        | 1.07%   |
| Apple Bluetooth USB Host Controller                 | 23        | 1.02%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 22        | 0.98%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 22        | 0.98%   |
| IMC Networks Bluetooth Device                       | 22        | 0.98%   |
| Intel AX210 Bluetooth                               | 21        | 0.93%   |
| Realtek Bluetooth Radio                             | 19        | 0.85%   |
| Lite-On Bluetooth Device                            | 18        | 0.8%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 18        | 0.8%    |
| Dell BCM20702A0 Bluetooth Module                    | 18        | 0.8%    |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.67%   |
| HP Broadcom 2070 Bluetooth Combo                    | 14        | 0.62%   |
| Foxconn International BCM43142A0 Bluetooth module   | 13        | 0.58%   |
| Toshiba Bluetooth Device                            | 12        | 0.53%   |
| Intel Bluetooth Device                              | 12        | 0.53%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.53%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.53%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.49%   |
| IMC Networks Wireless_Device                        | 11        | 0.49%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 10        | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2375      | 69.02%  |
| AMD                              | 507       | 14.73%  |
| Nvidia                           | 362       | 10.52%  |
| C-Media Electronics              | 23        | 0.67%   |
| Realtek Semiconductor            | 17        | 0.49%   |
| Plantronics                      | 13        | 0.38%   |
| GN Netcom                        | 13        | 0.38%   |
| Silicon Integrated Systems [SiS] | 12        | 0.35%   |
| Texas Instruments                | 10        | 0.29%   |
| Lenovo                           | 8         | 0.23%   |
| JMTek                            | 7         | 0.2%    |
| Creative Technology              | 7         | 0.2%    |
| Apple                            | 7         | 0.2%    |
| Logitech                         | 5         | 0.15%   |
| Conexant Systems                 | 5         | 0.15%   |
| VIA Technologies                 | 4         | 0.12%   |
| Corsair                          | 4         | 0.12%   |
| Blue Microphones                 | 4         | 0.12%   |
| Yamaha                           | 3         | 0.09%   |
| XMOS                             | 3         | 0.09%   |
| Sony                             | 3         | 0.09%   |
| RODE Microphones                 | 3         | 0.09%   |
| Hewlett-Packard                  | 3         | 0.09%   |
| Focusrite-Novation               | 3         | 0.09%   |
| Dell                             | 3         | 0.09%   |
| SteelSeries ApS                  | 2         | 0.06%   |
| Samsung Electronics              | 2         | 0.06%   |
| GYROCOM C&C                      | 2         | 0.06%   |
| Google                           | 2         | 0.06%   |
| Generalplus Technology           | 2         | 0.06%   |
| DSEA A/S                         | 2         | 0.06%   |
| AudioQuest                       | 2         | 0.06%   |
| AKAI Professional M.I.           | 2         | 0.06%   |
| Toshiba                          | 1         | 0.03%   |
| Tenx Technology                  | 1         | 0.03%   |
| PreSonus Audio Electronics       | 1         | 0.03%   |
| Native Instruments               | 1         | 0.03%   |
| NanosIC                          | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 332       | 8.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 265       | 6.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 195       | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 179       | 4.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 171       | 4.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 145       | 3.51%   |
| Intel 8 Series HD Audio Controller                                                                | 124       | 3%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 123       | 2.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 120       | 2.9%    |
| Intel Broadwell-U Audio Controller                                                                | 109       | 2.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 105       | 2.54%   |
| AMD FCH Azalia Controller                                                                         | 105       | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 95        | 2.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 88        | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 84        | 2.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 83        | 2.01%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 80        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 73        | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 73        | 1.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 72        | 1.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 71        | 1.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 68        | 1.65%   |
| AMD Kabini HDMI/DP Audio                                                                          | 67        | 1.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 64        | 1.55%   |
| AMD High Definition Audio Controller                                                              | 60        | 1.45%   |
| Intel CM238 HD Audio Controller                                                                   | 58        | 1.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 53        | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 53        | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 52        | 1.26%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 42        | 1.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 41        | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 39        | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 36        | 0.87%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 32        | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 31        | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 30        | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 29        | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 27        | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 26        | 0.63%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 24        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 435       | 27.34%  |
| SK hynix            | 387       | 24.32%  |
| Micron Technology   | 203       | 12.76%  |
| Crucial             | 126       | 7.92%   |
| Unknown             | 120       | 7.54%   |
| Kingston            | 116       | 7.29%   |
| Corsair             | 36        | 2.26%   |
| Ramaxel Technology  | 34        | 2.14%   |
| Elpida              | 29        | 1.82%   |
| Nanya Technology    | 26        | 1.63%   |
| A-DATA Technology   | 18        | 1.13%   |
| Unknown (ABCD)      | 12        | 0.75%   |
| Qimonda             | 5         | 0.31%   |
| Unknown             | 5         | 0.31%   |
| GOODRAM             | 4         | 0.25%   |
| Transcend           | 3         | 0.19%   |
| Toshiba             | 3         | 0.19%   |
| Patriot             | 3         | 0.19%   |
| ASint Technology    | 3         | 0.19%   |
| GSkill              | 2         | 0.13%   |
| G.Skill             | 2         | 0.13%   |
| Essencore           | 2         | 0.13%   |
| Apacer              | 2         | 0.13%   |
| A Force             | 2         | 0.13%   |
| V-Color             | 1         | 0.06%   |
| Unknown (F301)      | 1         | 0.06%   |
| Timetec             | 1         | 0.06%   |
| Smart               | 1         | 0.06%   |
| SHARETRONIC         | 1         | 0.06%   |
| OnBoard             | 1         | 0.06%   |
| Neo Forza           | 1         | 0.06%   |
| Miron               | 1         | 0.06%   |
| Memox               | 1         | 0.06%   |
| Foxline             | 1         | 0.06%   |
| ChangXin Memory     | 1         | 0.06%   |
| AMD                 | 1         | 0.06%   |
| Aeneon              | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 36        | 2.12%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 1.3%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 21        | 1.24%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 19        | 1.12%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 1.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 1.06%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 1.06%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 18        | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 1.06%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 1%      |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 15        | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 14        | 0.83%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 13        | 0.77%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 13        | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 12        | 0.71%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 12        | 0.71%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 12        | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.65%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 11        | 0.65%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.65%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s       | 11        | 0.65%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 10        | 0.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 10        | 0.59%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.53%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 9         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 8         | 0.47%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 8         | 0.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.47%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.47%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 8         | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.41%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 603       | 44.21%  |
| DDR3    | 466       | 34.16%  |
| DDR2    | 79        | 5.79%   |
| LPDDR3  | 76        | 5.57%   |
| LPDDR4  | 61        | 4.47%   |
| SDRAM   | 43        | 3.15%   |
| Unknown | 11        | 0.81%   |
| DDR5    | 9         | 0.66%   |
| DRAM    | 8         | 0.59%   |
| DDR     | 8         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1185      | 87.58%  |
| Row Of Chips | 139       | 10.27%  |
| Chip         | 14        | 1.03%   |
| Unknown      | 10        | 0.74%   |
| DIMM         | 5         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 537       | 36.19%  |
| 4096  | 476       | 32.08%  |
| 2048  | 200       | 13.48%  |
| 16384 | 176       | 11.86%  |
| 1024  | 64        | 4.31%   |
| 32768 | 20        | 1.35%   |
| 512   | 10        | 0.67%   |
| 256   | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 341       | 23.15%  |
| 2667    | 319       | 21.66%  |
| 3200    | 176       | 11.95%  |
| 2400    | 112       | 7.6%    |
| 2133    | 86        | 5.84%   |
| 1334    | 64        | 4.34%   |
| 1333    | 52        | 3.53%   |
| 1867    | 40        | 2.72%   |
| 667     | 40        | 2.72%   |
| Unknown | 37        | 2.51%   |
| 4267    | 29        | 1.97%   |
| 1067    | 29        | 1.97%   |
| 3266    | 21        | 1.43%   |
| 800     | 21        | 1.43%   |
| 4199    | 18        | 1.22%   |
| 2048    | 18        | 1.22%   |
| 1066    | 11        | 0.75%   |
| 4800    | 10        | 0.68%   |
| 975     | 10        | 0.68%   |
| 533     | 7         | 0.48%   |
| 1866    | 6         | 0.41%   |
| 8400    | 5         | 0.34%   |
| 4266    | 5         | 0.34%   |
| 3733    | 3         | 0.2%    |
| 3000    | 3         | 0.2%    |
| 1639    | 3         | 0.2%    |
| 400     | 3         | 0.2%    |
| 333     | 2         | 0.14%   |
| 1776    | 1         | 0.07%   |
| 933     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 25%     |
| Canon                 | 6         | 25%     |
| Samsung Electronics   | 3         | 12.5%   |
| Prolific Technology   | 2         | 8.33%   |
| Lexmark International | 2         | 8.33%   |
| Brother Industries    | 2         | 8.33%   |
| STMicroelectronics    | 1         | 4.17%   |
| Seiko Epson           | 1         | 4.17%   |
| Kyocera               | 1         | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                             | 2         | 8%      |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 4%      |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 4%      |
| Samsung CLX-6260 Series                                   | 1         | 4%      |
| Samsung CLP-300 Series                                    | 1         | 4%      |
| Samsung C43x Series                                       | 1         | 4%      |
| Lexmark International MS610de                             | 1         | 4%      |
| Lexmark International C544                                | 1         | 4%      |
| Kyocera FS-1041                                           | 1         | 4%      |
| HP Officejet 4630 series                                  | 1         | 4%      |
| HP LaserJet P2015 series                                  | 1         | 4%      |
| HP LaserJet 1010                                          | 1         | 4%      |
| HP ENVY Photo 6200 series                                 | 1         | 4%      |
| HP ENVY 4520 series                                       | 1         | 4%      |
| HP Deskjet 2540 series                                    | 1         | 4%      |
| Canon PIXMA MX490 Series                                  | 1         | 4%      |
| Canon PIXMA MG2500 Series                                 | 1         | 4%      |
| Canon MF4360-4390                                         | 1         | 4%      |
| Canon LiDE 400                                            | 1         | 4%      |
| Canon LiDE 300                                            | 1         | 4%      |
| Canon iX6500 series                                       | 1         | 4%      |
| Canon iP4800 series                                       | 1         | 4%      |
| Brother PT-9500PC                                         | 1         | 4%      |
| Brother DCP-L3510CDW                                      | 1         | 4%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 57.14%  |
| Seiko Epson     | 2         | 28.57%  |
| Hewlett-Packard | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                     | 2         | 28.57%  |
| Seiko Epson Scanner                         | 1         | 14.29%  |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 14.29%  |
| HP ScanJet 5300c/5370c                      | 1         | 14.29%  |
| Canon CanoScan LiDE 600F                    | 1         | 14.29%  |
| Canon CanoScan LiDE 220                     | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 645       | 25.64%  |
| Microdia                               | 293       | 11.65%  |
| Realtek Semiconductor                  | 228       | 9.06%   |
| IMC Networks                           | 209       | 8.31%   |
| Acer                                   | 176       | 7%      |
| Sunplus Innovation Technology          | 135       | 5.37%   |
| Cheng Uei Precision Industry (Foxlink) | 109       | 4.33%   |
| Suyin                                  | 94        | 3.74%   |
| Quanta                                 | 93        | 3.7%    |
| Apple                                  | 65        | 2.58%   |
| Lite-On Technology                     | 63        | 2.5%    |
| Syntek                                 | 52        | 2.07%   |
| Silicon Motion                         | 50        | 1.99%   |
| Alcor Micro                            | 44        | 1.75%   |
| Ricoh                                  | 42        | 1.67%   |
| Logitech                               | 37        | 1.47%   |
| Lenovo                                 | 27        | 1.07%   |
| Samsung Electronics                    | 15        | 0.6%    |
| Luxvisions Innotech Limited            | 13        | 0.52%   |
| ALi                                    | 12        | 0.48%   |
| Z-Star Microelectronics                | 11        | 0.44%   |
| Primax Electronics                     | 11        | 0.44%   |
| Microsoft                              | 7         | 0.28%   |
| Sonix Technology                       | 6         | 0.24%   |
| Importek                               | 6         | 0.24%   |
| Generalplus Technology                 | 6         | 0.24%   |
| Sunplus Technology                     | 5         | 0.2%    |
| OmniVision Technologies                | 5         | 0.2%    |
| DigiTech                               | 5         | 0.2%    |
| Intel                                  | 4         | 0.16%   |
| ARC International                      | 4         | 0.16%   |
| Unknown                                | 3         | 0.12%   |
| Genesys Logic                          | 3         | 0.12%   |
| GEMBIRD                                | 3         | 0.12%   |
| Foxconn / Hon Hai                      | 3         | 0.12%   |
| Y Media                                | 2         | 0.08%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.08%   |
| Razer USA                              | 2         | 0.08%   |
| Pixart Imaging                         | 2         | 0.08%   |
| Google                                 | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 147       | 5.81%   |
| Chicony Integrated Camera                               | 107       | 4.23%   |
| Realtek Integrated_Webcam_HD                            | 78        | 3.08%   |
| IMC Networks Integrated Camera                          | 60        | 2.37%   |
| Chicony HD WebCam                                       | 58        | 2.29%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 48        | 1.9%    |
| Sunplus Integrated_Webcam_HD                            | 45        | 1.78%   |
| Chicony TOSHIBA Web Camera - HD                         | 42        | 1.66%   |
| Acer Integrated Camera                                  | 33        | 1.3%    |
| Microdia Integrated Webcam                              | 32        | 1.26%   |
| Chicony USB2.0 Camera                                   | 32        | 1.26%   |
| Realtek USB Camera                                      | 31        | 1.23%   |
| Lite-On Integrated Camera                               | 29        | 1.15%   |
| Chicony HP TrueVision HD Camera                         | 26        | 1.03%   |
| Apple Built-in iSight                                   | 25        | 0.99%   |
| Chicony USB 2.0 Camera                                  | 23        | 0.91%   |
| Acer Lenovo EasyCamera                                  | 22        | 0.87%   |
| Apple FaceTime HD Camera                                | 21        | 0.83%   |
| Acer BisonCam,NB Pro                                    | 21        | 0.83%   |
| Chicony VGA Webcam                                      | 20        | 0.79%   |
| Syntek Lenovo EasyCamera                                | 19        | 0.75%   |
| Chicony HP TrueVision HD                                | 19        | 0.75%   |
| Chicony HP HD Camera                                    | 19        | 0.75%   |
| Chicony EasyCamera                                      | 19        | 0.75%   |
| Acer SunplusIT Integrated Camera                        | 19        | 0.75%   |
| Quanta HD User Facing                                   | 17        | 0.67%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 17        | 0.67%   |
| Lenovo Integrated Webcam [R5U877]                       | 16        | 0.63%   |
| Chicony Integrated Camera (1280x720@30)                 | 16        | 0.63%   |
| Chicony CNF9055 Toshiba Webcam                          | 16        | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 16        | 0.63%   |
| Samsung Galaxy A5 (MTP)                                 | 15        | 0.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 15        | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 15        | 0.59%   |
| Alcor Micro SHUNCCM2MP                                  | 15        | 0.59%   |
| Syntek Integrated Camera                                | 14        | 0.55%   |
| Syntek EasyCamera                                       | 14        | 0.55%   |
| Suyin HP Truevision HD                                  | 14        | 0.55%   |
| Realtek Integrated Webcam                               | 14        | 0.55%   |
| Realtek Integrated Webcam HD                            | 13        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 172       | 34.19%  |
| Synaptics                  | 115       | 22.86%  |
| Shenzhen Goodix Technology | 81        | 16.1%   |
| AuthenTec                  | 41        | 8.15%   |
| Upek                       | 37        | 7.36%   |
| LighTuning Technology      | 26        | 5.17%   |
| Elan Microelectronics      | 16        | 3.18%   |
| STMicroelectronics         | 13        | 2.58%   |
| Samsung Electronics        | 1         | 0.2%    |
| Focal-systems.Corp         | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 44        | 8.75%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 36        | 7.16%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 34        | 6.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 32        | 6.36%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 30        | 5.96%   |
| Unknown                                                                    | 28        | 5.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 4.17%   |
| Shenzhen Goodix FingerPrint                                                | 19        | 3.78%   |
| Shenzhen Goodix Fingerprint Reader                                         | 18        | 3.58%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 3.18%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 2.98%   |
| Validity Sensors VFS491                                                    | 13        | 2.58%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 2.58%   |
| STMicroelectronics Fingerprint Reader                                      | 13        | 2.58%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 2.39%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 11        | 2.19%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.19%   |
| Elan ELAN:Fingerprint                                                      | 11        | 2.19%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.99%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.99%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.79%   |
| AuthenTec AES2810                                                          | 8         | 1.59%   |
| Synaptics WBDI Device                                                      | 7         | 1.39%   |
| Synaptics  WBDI                                                            | 7         | 1.39%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.39%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 1.19%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.19%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.99%   |
| Elan ELAN:ARM-M4                                                           | 5         | 0.99%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.99%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.99%   |
| AuthenTec AES1600                                                          | 5         | 0.99%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 0.8%    |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.8%    |
| LighTuning Fingerprint Reader                                              | 4         | 0.8%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.6%    |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.4%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.2%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.2%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 140       | 53.23%  |
| Alcor Micro           | 56        | 21.29%  |
| Upek                  | 22        | 8.37%   |
| O2 Micro              | 18        | 6.84%   |
| Lenovo                | 17        | 6.46%   |
| Gemalto (was Gemplus) | 4         | 1.52%   |
| SCM Microsystems      | 3         | 1.14%   |
| Purism, SPC           | 1         | 0.38%   |
| Clay Logic            | 1         | 0.38%   |
| Chicony Electronics   | 1         | 0.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 62        | 23.57%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 55        | 20.91%  |
| Broadcom 5880                                                                | 32        | 12.17%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 27        | 10.27%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 8.37%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 6.46%   |
| Broadcom 58200                                                               | 17        | 6.46%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 13        | 4.94%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.9%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.14%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.76%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.38%   |
| Purism, SPC Librem Key                                                       | 1         | 0.38%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.38%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.38%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.38%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1869      | 62.72%  |
| 1     | 857       | 28.76%  |
| 2     | 221       | 7.42%   |
| 3     | 24        | 0.81%   |
| 5     | 3         | 0.1%    |
| 4     | 3         | 0.1%    |
| 8     | 1         | 0.03%   |
| 7     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 488       | 35.47%  |
| Chipcard                 | 245       | 17.81%  |
| Graphics card            | 198       | 14.39%  |
| Net/wireless             | 164       | 11.92%  |
| Multimedia controller    | 73        | 5.31%   |
| Communication controller | 37        | 2.69%   |
| Storage                  | 33        | 2.4%    |
| Bluetooth                | 30        | 2.18%   |
| Camera                   | 26        | 1.89%   |
| Sound                    | 17        | 1.24%   |
| Net/ethernet             | 14        | 1.02%   |
| Modem                    | 14        | 1.02%   |
| Card reader              | 13        | 0.94%   |
| Flash memory             | 8         | 0.58%   |
| Network                  | 6         | 0.44%   |
| Firewire controller      | 4         | 0.29%   |
| Unassigned class         | 2         | 0.15%   |
| Storage/nvme             | 2         | 0.15%   |
| Storage/ide              | 2         | 0.15%   |

