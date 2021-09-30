Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv7                | Notebook    | [590a48aff9](https://linux-hardware.org/?probe=590a48aff9) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [359171629f](https://linux-hardware.org/?probe=359171629f) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [4e125287e4](https://linux-hardware.org/?probe=4e125287e4) | Sep 30, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [d0c34db7d4](https://linux-hardware.org/?probe=d0c34db7d4) | Sep 29, 2021 |
| HP            | ENVY 15                     | Notebook    | [4b949c1a1b](https://linux-hardware.org/?probe=4b949c1a1b) | Sep 29, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [3688fae067](https://linux-hardware.org/?probe=3688fae067) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [3befe3f6e3](https://linux-hardware.org/?probe=3befe3f6e3) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [401d1460e9](https://linux-hardware.org/?probe=401d1460e9) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| Lenovo        | IdeaCentre K330             | Desktop     | [ed6e765fea](https://linux-hardware.org/?probe=ed6e765fea) | Sep 29, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [8f7adb6cd3](https://linux-hardware.org/?probe=8f7adb6cd3) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [9e3d0f86c2](https://linux-hardware.org/?probe=9e3d0f86c2) | Sep 28, 2021 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [1d15930339](https://linux-hardware.org/?probe=1d15930339) | Sep 28, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5b8eb94d7](https://linux-hardware.org/?probe=d5b8eb94d7) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [cc9cc9e925](https://linux-hardware.org/?probe=cc9cc9e925) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [6cf7de2b6b](https://linux-hardware.org/?probe=6cf7de2b6b) | Sep 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7e0b76f736](https://linux-hardware.org/?probe=7e0b76f736) | Sep 28, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [d36367eb22](https://linux-hardware.org/?probe=d36367eb22) | Sep 28, 2021 |
| Acer          | Aspire A315-56              | Notebook    | [3fc47b2c92](https://linux-hardware.org/?probe=3fc47b2c92) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [f322cce11b](https://linux-hardware.org/?probe=f322cce11b) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| Dell          | 0TNXNR A01                  | Desktop     | [781c19cc33](https://linux-hardware.org/?probe=781c19cc33) | Sep 27, 2021 |
| Dell          | Latitude E5570              | Notebook    | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | Notebook    | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | Notebook    | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [0625659706](https://linux-hardware.org/?probe=0625659706) | Sep 27, 2021 |
| Dell          | 0NYCKR A00                  | All in one  | [aefac2fb50](https://linux-hardware.org/?probe=aefac2fb50) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| Dell          | 0NYCKR A00                  | All in one  | [e0e687f0f9](https://linux-hardware.org/?probe=e0e687f0f9) | Sep 27, 2021 |
| MSI           | MS-B1061                    | All in one  | [1bc488324f](https://linux-hardware.org/?probe=1bc488324f) | Sep 27, 2021 |
| ASUSTek       | X405UA                      | Notebook    | [3a78f7edf5](https://linux-hardware.org/?probe=3a78f7edf5) | Sep 26, 2021 |
| Dell          | 0TP406                      | Desktop     | [39f9e67ae2](https://linux-hardware.org/?probe=39f9e67ae2) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| HP            | 18E7                        | Desktop     | [94f692683b](https://linux-hardware.org/?probe=94f692683b) | Sep 26, 2021 |
| Lenovo        | ThinkPad T520 4242W19       | Notebook    | [0bbb8d9004](https://linux-hardware.org/?probe=0bbb8d9004) | Sep 26, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [4bc5eb3bbc](https://linux-hardware.org/?probe=4bc5eb3bbc) | Sep 25, 2021 |
| eMachines     | EL1850G                     | Desktop     | [f5b47069bb](https://linux-hardware.org/?probe=f5b47069bb) | Sep 25, 2021 |
| HP            | 8245 001                    | All in one  | [8ea38831d5](https://linux-hardware.org/?probe=8ea38831d5) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [8bc152aa27](https://linux-hardware.org/?probe=8bc152aa27) | Sep 25, 2021 |
| Lenovo        | ThinkCentre M58 3231W2Y     | Desktop     | [a2da2733ac](https://linux-hardware.org/?probe=a2da2733ac) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [5cc1a01b2f](https://linux-hardware.org/?probe=5cc1a01b2f) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [2b341862f1](https://linux-hardware.org/?probe=2b341862f1) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [9267f59e81](https://linux-hardware.org/?probe=9267f59e81) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [5404d5874a](https://linux-hardware.org/?probe=5404d5874a) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Dell          | Latitude E6220              | Notebook    | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [9d3daebd14](https://linux-hardware.org/?probe=9d3daebd14) | Sep 25, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [65ebe53761](https://linux-hardware.org/?probe=65ebe53761) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [6b6f1c017d](https://linux-hardware.org/?probe=6b6f1c017d) | Sep 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [953ed13df8](https://linux-hardware.org/?probe=953ed13df8) | Sep 24, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [663af51c43](https://linux-hardware.org/?probe=663af51c43) | Sep 24, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [4d4844cfbe](https://linux-hardware.org/?probe=4d4844cfbe) | Sep 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [a65f8af3ac](https://linux-hardware.org/?probe=a65f8af3ac) | Sep 24, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [2d0d6ceff3](https://linux-hardware.org/?probe=2d0d6ceff3) | Sep 24, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | Desktop     | [dc87018670](https://linux-hardware.org/?probe=dc87018670) | Sep 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8617cbbc27](https://linux-hardware.org/?probe=8617cbbc27) | Sep 24, 2021 |
| ASRock        | 775VM800                    | Desktop     | [e07158e4ab](https://linux-hardware.org/?probe=e07158e4ab) | Sep 24, 2021 |
| KOGAN         | KAL11C250SB                 | Notebook    | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1af2027db5](https://linux-hardware.org/?probe=1af2027db5) | Sep 24, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5e66bde0c9](https://linux-hardware.org/?probe=5e66bde0c9) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | Notebook    | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| HP            | Presario V6000 (GM018UA#... | Notebook    | [944d6af89a](https://linux-hardware.org/?probe=944d6af89a) | Sep 23, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [fe99af6254](https://linux-hardware.org/?probe=fe99af6254) | Sep 23, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [4d2aa790e0](https://linux-hardware.org/?probe=4d2aa790e0) | Sep 23, 2021 |
| HP            | 18E7                        | Desktop     | [29fa39d7e9](https://linux-hardware.org/?probe=29fa39d7e9) | Sep 23, 2021 |
| ASRock        | 880GMH/U3S3                 | Desktop     | [ec55312287](https://linux-hardware.org/?probe=ec55312287) | Sep 23, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [cb23f25d7f](https://linux-hardware.org/?probe=cb23f25d7f) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [74410f0d0c](https://linux-hardware.org/?probe=74410f0d0c) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ad81766325](https://linux-hardware.org/?probe=ad81766325) | Sep 23, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [bc7d0dc232](https://linux-hardware.org/?probe=bc7d0dc232) | Sep 22, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | Desktop     | [529a9f4c74](https://linux-hardware.org/?probe=529a9f4c74) | Sep 22, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [bfa3ee0eda](https://linux-hardware.org/?probe=bfa3ee0eda) | Sep 22, 2021 |
| Cube          | SurfTab twin 11.6           | Convertible | [74fe90715f](https://linux-hardware.org/?probe=74fe90715f) | Sep 22, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [effa7b0365](https://linux-hardware.org/?probe=effa7b0365) | Sep 22, 2021 |
| HP            | Notebook                    | Notebook    | [91d439a6a4](https://linux-hardware.org/?probe=91d439a6a4) | Sep 22, 2021 |
| Dynabook      | dynabook PORTEGE A30-E      | Notebook    | [93fd738472](https://linux-hardware.org/?probe=93fd738472) | Sep 21, 2021 |
| Dynabook      | dynabook PORTEGE A30-E      | Notebook    | [0ec5acd020](https://linux-hardware.org/?probe=0ec5acd020) | Sep 21, 2021 |
| HP            | 213D A01                    | Desktop     | [8d4dd8359c](https://linux-hardware.org/?probe=8d4dd8359c) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a43f2dc4bf](https://linux-hardware.org/?probe=a43f2dc4bf) | Sep 21, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [3354edcb58](https://linux-hardware.org/?probe=3354edcb58) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [069c0cafd0](https://linux-hardware.org/?probe=069c0cafd0) | Sep 21, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [10baeecbf5](https://linux-hardware.org/?probe=10baeecbf5) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [c514cd3934](https://linux-hardware.org/?probe=c514cd3934) | Sep 21, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [fdb65b8597](https://linux-hardware.org/?probe=fdb65b8597) | Sep 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [699803b74c](https://linux-hardware.org/?probe=699803b74c) | Sep 21, 2021 |
| Dell          | 09CGW2 A13                  | Server      | [46d07193b2](https://linux-hardware.org/?probe=46d07193b2) | Sep 21, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3ef59689e6](https://linux-hardware.org/?probe=3ef59689e6) | Sep 21, 2021 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [70511c9675](https://linux-hardware.org/?probe=70511c9675) | Sep 21, 2021 |
| Lenovo        | G580                        | Notebook    | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [91055c07be](https://linux-hardware.org/?probe=91055c07be) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [ae16407ef3](https://linux-hardware.org/?probe=ae16407ef3) | Sep 20, 2021 |
| MSI           | H81M-E33                    | Desktop     | [5ef84c22e6](https://linux-hardware.org/?probe=5ef84c22e6) | Sep 20, 2021 |
| MSI           | H81M-E33                    | Desktop     | [db96085729](https://linux-hardware.org/?probe=db96085729) | Sep 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a0b7d0cf25](https://linux-hardware.org/?probe=a0b7d0cf25) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c05636068f](https://linux-hardware.org/?probe=c05636068f) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [1a012b3021](https://linux-hardware.org/?probe=1a012b3021) | Sep 20, 2021 |
| Dell          | 09CGW2 A13                  | Server      | [97926688ff](https://linux-hardware.org/?probe=97926688ff) | Sep 20, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [c294748851](https://linux-hardware.org/?probe=c294748851) | Sep 20, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [39f083f836](https://linux-hardware.org/?probe=39f083f836) | Sep 20, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [59eb49e544](https://linux-hardware.org/?probe=59eb49e544) | Sep 20, 2021 |
| Acer          | Aspire E1-532               | Notebook    | [b0407bdd1c](https://linux-hardware.org/?probe=b0407bdd1c) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [b9259e3604](https://linux-hardware.org/?probe=b9259e3604) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [9eb1254056](https://linux-hardware.org/?probe=9eb1254056) | Sep 19, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [c86625aa34](https://linux-hardware.org/?probe=c86625aa34) | Sep 19, 2021 |
| HP            | 2B28                        | Desktop     | [14681c925a](https://linux-hardware.org/?probe=14681c925a) | Sep 19, 2021 |
| TianBei       | TB-H7                       | Notebook    | [06300b96a7](https://linux-hardware.org/?probe=06300b96a7) | Sep 19, 2021 |
| Sapphire T... | PURE PLATINUM 970A-PLUS     | Desktop     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | Notebook    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [6129e531d9](https://linux-hardware.org/?probe=6129e531d9) | Sep 19, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [37f34b16c5](https://linux-hardware.org/?probe=37f34b16c5) | Sep 19, 2021 |
| Acer          | Aspire 4352                 | Notebook    | [3a9aedb538](https://linux-hardware.org/?probe=3a9aedb538) | Sep 19, 2021 |
| ASUSTek       | U31F                        | Notebook    | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [183fc0dd5e](https://linux-hardware.org/?probe=183fc0dd5e) | Sep 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [bc3e2da7f3](https://linux-hardware.org/?probe=bc3e2da7f3) | Sep 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e8f361170f](https://linux-hardware.org/?probe=e8f361170f) | Sep 18, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [4dda7e9a7e](https://linux-hardware.org/?probe=4dda7e9a7e) | Sep 18, 2021 |
| ASUSTek       | U31F                        | Notebook    | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Dell          | XPS L321X                   | Notebook    | [2345076968](https://linux-hardware.org/?probe=2345076968) | Sep 18, 2021 |
| Dell          | Latitude E6430              | Notebook    | [2d96c4a645](https://linux-hardware.org/?probe=2d96c4a645) | Sep 17, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [30f36dc15d](https://linux-hardware.org/?probe=30f36dc15d) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [42d68963c6](https://linux-hardware.org/?probe=42d68963c6) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [50f90e7684](https://linux-hardware.org/?probe=50f90e7684) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [73a4cd0692](https://linux-hardware.org/?probe=73a4cd0692) | Sep 17, 2021 |
| HP            | Unknown                     | Notebook    | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [518209a322](https://linux-hardware.org/?probe=518209a322) | Sep 17, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [b3a1acb0f6](https://linux-hardware.org/?probe=b3a1acb0f6) | Sep 17, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [b7fe3ed969](https://linux-hardware.org/?probe=b7fe3ed969) | Sep 17, 2021 |
| Dell          | Latitude E5470              | Notebook    | [9a036a26a4](https://linux-hardware.org/?probe=9a036a26a4) | Sep 17, 2021 |
| HP            | Notebook                    | Notebook    | [6b2785c2e0](https://linux-hardware.org/?probe=6b2785c2e0) | Sep 17, 2021 |
| Dell          | Latitude E5500              | Notebook    | [286c99863b](https://linux-hardware.org/?probe=286c99863b) | Sep 16, 2021 |
| HP            | 245 G5 Notebook PC          | Notebook    | [ece740cf39](https://linux-hardware.org/?probe=ece740cf39) | Sep 16, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [042032eec7](https://linux-hardware.org/?probe=042032eec7) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | Notebook    | [04ba56c326](https://linux-hardware.org/?probe=04ba56c326) | Sep 16, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [142e3e40c2](https://linux-hardware.org/?probe=142e3e40c2) | Sep 16, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [152dd3680d](https://linux-hardware.org/?probe=152dd3680d) | Sep 16, 2021 |
| Jumper        | EZpad .A002                 | Notebook    | [c62d842a68](https://linux-hardware.org/?probe=c62d842a68) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | Notebook    | [6d381b570b](https://linux-hardware.org/?probe=6d381b570b) | Sep 15, 2021 |
| HP            | 255 G4 Notebook PC          | Notebook    | [c8a384ed00](https://linux-hardware.org/?probe=c8a384ed00) | Sep 15, 2021 |
| Acer          | One S1003                   | Tablet      | [e021ddcbf1](https://linux-hardware.org/?probe=e021ddcbf1) | Sep 15, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Latitude E7440              | Notebook    | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| Dell          | Latitude E6520              | Notebook    | [1bd8b6a82f](https://linux-hardware.org/?probe=1bd8b6a82f) | Sep 15, 2021 |
| Intel         | X99                         | Desktop     | [814b3326d1](https://linux-hardware.org/?probe=814b3326d1) | Sep 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [983922cfbf](https://linux-hardware.org/?probe=983922cfbf) | Sep 15, 2021 |
| NCR           | Talladega                   | Desktop     | [95445fa221](https://linux-hardware.org/?probe=95445fa221) | Sep 14, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Notebook                    | Notebook    | [d6825ad86c](https://linux-hardware.org/?probe=d6825ad86c) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [93a071ca7e](https://linux-hardware.org/?probe=93a071ca7e) | Sep 14, 2021 |
| Foxconn       | 17A0                        | Desktop     | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [874dcada55](https://linux-hardware.org/?probe=874dcada55) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [199ae9a9dd](https://linux-hardware.org/?probe=199ae9a9dd) | Sep 14, 2021 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [68ad9fb8e9](https://linux-hardware.org/?probe=68ad9fb8e9) | Sep 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [b3b1991c64](https://linux-hardware.org/?probe=b3b1991c64) | Sep 14, 2021 |
| Dell          | Latitude E5470              | Notebook    | [032f256bab](https://linux-hardware.org/?probe=032f256bab) | Sep 14, 2021 |
| Sony          | VPCF215FX                   | Notebook    | [173d8636d4](https://linux-hardware.org/?probe=173d8636d4) | Sep 14, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [93db4618cc](https://linux-hardware.org/?probe=93db4618cc) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b054524aac](https://linux-hardware.org/?probe=b054524aac) | Sep 14, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [864dde8a99](https://linux-hardware.org/?probe=864dde8a99) | Sep 13, 2021 |
| Acer          | One S1003                   | Tablet      | [a049a2a4d3](https://linux-hardware.org/?probe=a049a2a4d3) | Sep 13, 2021 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [d4a19b90eb](https://linux-hardware.org/?probe=d4a19b90eb) | Sep 13, 2021 |
| ASUSTek       | Benicia                     | Desktop     | [2a764dd662](https://linux-hardware.org/?probe=2a764dd662) | Sep 13, 2021 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [3818ff8f07](https://linux-hardware.org/?probe=3818ff8f07) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [6928772253](https://linux-hardware.org/?probe=6928772253) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [93a0d7ac6a](https://linux-hardware.org/?probe=93a0d7ac6a) | Sep 12, 2021 |
| HP            | Victus by HP Laptop 16-e... | Notebook    | [6a980ac620](https://linux-hardware.org/?probe=6a980ac620) | Sep 12, 2021 |
| HP            | 339A                        | Desktop     | [9284a70a92](https://linux-hardware.org/?probe=9284a70a92) | Sep 12, 2021 |
| Dell          | Latitude E6430              | Notebook    | [aff84b5ec1](https://linux-hardware.org/?probe=aff84b5ec1) | Sep 12, 2021 |
| Google        | Kindred                     | Notebook    | [c9ee8560b8](https://linux-hardware.org/?probe=c9ee8560b8) | Sep 12, 2021 |
| Dell          | XPS M1330                   | Notebook    | [404d33775d](https://linux-hardware.org/?probe=404d33775d) | Sep 12, 2021 |
| Dell          | Latitude E5500              | Notebook    | [1e20247950](https://linux-hardware.org/?probe=1e20247950) | Sep 12, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [8693b86435](https://linux-hardware.org/?probe=8693b86435) | Sep 12, 2021 |
| NCR           | Talladega                   | Desktop     | [6de6d8c2a3](https://linux-hardware.org/?probe=6de6d8c2a3) | Sep 12, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [6b02d3fa6f](https://linux-hardware.org/?probe=6b02d3fa6f) | Sep 11, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8b0f703471](https://linux-hardware.org/?probe=8b0f703471) | Sep 11, 2021 |
| Lenovo        | SDK0E50519 WIN              | Desktop     | [7c58527193](https://linux-hardware.org/?probe=7c58527193) | Sep 11, 2021 |
| Intel         | X79M-S                      | Desktop     | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| Dell          | XPS M1330                   | Notebook    | [3dcddbd59e](https://linux-hardware.org/?probe=3dcddbd59e) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [728e0facd6](https://linux-hardware.org/?probe=728e0facd6) | Sep 11, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [4e69ac73e4](https://linux-hardware.org/?probe=4e69ac73e4) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [33fd6d8c8f](https://linux-hardware.org/?probe=33fd6d8c8f) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [fa33f94b27](https://linux-hardware.org/?probe=fa33f94b27) | Sep 11, 2021 |
| MSI           | GE75 Raider 8RF             | Notebook    | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| Toshiba       | Satellite Pro L450D         | Notebook    | [a15c916899](https://linux-hardware.org/?probe=a15c916899) | Sep 10, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [1ff7b16ce4](https://linux-hardware.org/?probe=1ff7b16ce4) | Sep 10, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [dab9a23b27](https://linux-hardware.org/?probe=dab9a23b27) | Sep 10, 2021 |
| Toshiba       | Satellite C850-1CP          | Notebook    | [8cec9884a8](https://linux-hardware.org/?probe=8cec9884a8) | Sep 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Dell          | Latitude E5470              | Notebook    | [f6d8fa5367](https://linux-hardware.org/?probe=f6d8fa5367) | Sep 10, 2021 |
| Dell          | Latitude E5470              | Notebook    | [87b52d41c7](https://linux-hardware.org/?probe=87b52d41c7) | Sep 10, 2021 |
| HP            | Notebook                    | Notebook    | [24690d1b8b](https://linux-hardware.org/?probe=24690d1b8b) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [6ab68f26ba](https://linux-hardware.org/?probe=6ab68f26ba) | Sep 09, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [34e6b7697f](https://linux-hardware.org/?probe=34e6b7697f) | Sep 09, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [5ce713a2f7](https://linux-hardware.org/?probe=5ce713a2f7) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [52b22746e0](https://linux-hardware.org/?probe=52b22746e0) | Sep 09, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7fdf917680](https://linux-hardware.org/?probe=7fdf917680) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [15f063a517](https://linux-hardware.org/?probe=15f063a517) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [5b8b652e27](https://linux-hardware.org/?probe=5b8b652e27) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [e3e702ab7b](https://linux-hardware.org/?probe=e3e702ab7b) | Sep 09, 2021 |
| HP            | 2187 A01                    | Desktop     | [0c11e3b726](https://linux-hardware.org/?probe=0c11e3b726) | Sep 09, 2021 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | Notebook    | [ccb4dc3d9a](https://linux-hardware.org/?probe=ccb4dc3d9a) | Sep 09, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [0f52ac751b](https://linux-hardware.org/?probe=0f52ac751b) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [97b34f8c7f](https://linux-hardware.org/?probe=97b34f8c7f) | Sep 08, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [f3c9b271f1](https://linux-hardware.org/?probe=f3c9b271f1) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [7dbf053877](https://linux-hardware.org/?probe=7dbf053877) | Sep 08, 2021 |
| MSI           | H81M-P33                    | Desktop     | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 20RAS1Q800     | Notebook    | [a4d93ee5d2](https://linux-hardware.org/?probe=a4d93ee5d2) | Sep 08, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [6bff88fb9e](https://linux-hardware.org/?probe=6bff88fb9e) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | Notebook    | [3fc588a18d](https://linux-hardware.org/?probe=3fc588a18d) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | Notebook    | [fd38e5bf9d](https://linux-hardware.org/?probe=fd38e5bf9d) | Sep 08, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [22d88098a9](https://linux-hardware.org/?probe=22d88098a9) | Sep 08, 2021 |
| Dell          | 0D28YY A03                  | Desktop     | [3eb7b9cb7b](https://linux-hardware.org/?probe=3eb7b9cb7b) | Sep 08, 2021 |
| RCA           | W101-CS                     | Tablet      | [7ba24072d5](https://linux-hardware.org/?probe=7ba24072d5) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [be8d4bd453](https://linux-hardware.org/?probe=be8d4bd453) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [47317abce2](https://linux-hardware.org/?probe=47317abce2) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [98874d48b2](https://linux-hardware.org/?probe=98874d48b2) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f872b42a74](https://linux-hardware.org/?probe=f872b42a74) | Sep 07, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [2f680da4b8](https://linux-hardware.org/?probe=2f680da4b8) | Sep 07, 2021 |
| Acer          | V5-171                      | Notebook    | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| HP            | Notebook                    | Notebook    | [62a2618cde](https://linux-hardware.org/?probe=62a2618cde) | Sep 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [b00795951c](https://linux-hardware.org/?probe=b00795951c) | Sep 07, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [92d22f65bf](https://linux-hardware.org/?probe=92d22f65bf) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Dell          | Precision 3520              | Notebook    | [15e6e2c91d](https://linux-hardware.org/?probe=15e6e2c91d) | Sep 07, 2021 |
| Dell          | Precision 5550              | Notebook    | [8ae36d685d](https://linux-hardware.org/?probe=8ae36d685d) | Sep 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [368f488133](https://linux-hardware.org/?probe=368f488133) | Sep 07, 2021 |
| MSI           | GL62 7RDX                   | Notebook    | [be53fd4c86](https://linux-hardware.org/?probe=be53fd4c86) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [807eed7553](https://linux-hardware.org/?probe=807eed7553) | Sep 06, 2021 |
| ASRock        | Q1900M                      | Desktop     | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock        | Q1900M                      | Desktop     | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| Intel         | X79M-S                      | Desktop     | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [28754f0456](https://linux-hardware.org/?probe=28754f0456) | Sep 06, 2021 |
| HP            | Pavilion dv5                | Notebook    | [27607d962e](https://linux-hardware.org/?probe=27607d962e) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [46499caf7a](https://linux-hardware.org/?probe=46499caf7a) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | Notebook    | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d94c35ce11](https://linux-hardware.org/?probe=d94c35ce11) | Sep 05, 2021 |
| Acer          | One S1003                   | Tablet      | [879a8ee9da](https://linux-hardware.org/?probe=879a8ee9da) | Sep 05, 2021 |
| Acer          | One S1003                   | Tablet      | [e5d901c7a5](https://linux-hardware.org/?probe=e5d901c7a5) | Sep 05, 2021 |
| MSI           | IONA                        | Desktop     | [8a4454604a](https://linux-hardware.org/?probe=8a4454604a) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [791768dfbd](https://linux-hardware.org/?probe=791768dfbd) | Sep 04, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [ff8f35986b](https://linux-hardware.org/?probe=ff8f35986b) | Sep 04, 2021 |
| MSI           | IONA                        | Desktop     | [b775cef84a](https://linux-hardware.org/?probe=b775cef84a) | Sep 04, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [920ab9b385](https://linux-hardware.org/?probe=920ab9b385) | Sep 04, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | Desktop     | [149099265c](https://linux-hardware.org/?probe=149099265c) | Sep 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [391c101a92](https://linux-hardware.org/?probe=391c101a92) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [263eeefef0](https://linux-hardware.org/?probe=263eeefef0) | Sep 04, 2021 |
| HP            | 2B4B                        | Desktop     | [d36296bddf](https://linux-hardware.org/?probe=d36296bddf) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8cd745db58](https://linux-hardware.org/?probe=8cd745db58) | Sep 04, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [9e6ccaa1f3](https://linux-hardware.org/?probe=9e6ccaa1f3) | Sep 04, 2021 |
| Biostar       | X470NH                      | Desktop     | [f0449b9946](https://linux-hardware.org/?probe=f0449b9946) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | 255 G3                      | Notebook    | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | Notebook    | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [980716e0a8](https://linux-hardware.org/?probe=980716e0a8) | Sep 03, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [126d9974b1](https://linux-hardware.org/?probe=126d9974b1) | Sep 03, 2021 |
| ASUSTek       | GR8                         | Notebook    | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | Notebook    | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire E5-521G              | Notebook    | [d1aa71f003](https://linux-hardware.org/?probe=d1aa71f003) | Sep 02, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Toshiba       | Satellite C850D-11C         | Notebook    | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | 1497                        | Desktop     | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [3c88709f8a](https://linux-hardware.org/?probe=3c88709f8a) | Sep 01, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | Notebook    | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| Insyde        | i101c                       | Notebook    | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [baa289fe51](https://linux-hardware.org/?probe=baa289fe51) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [cc326a093e](https://linux-hardware.org/?probe=cc326a093e) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [4c711d446d](https://linux-hardware.org/?probe=4c711d446d) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [efb9bccc60](https://linux-hardware.org/?probe=efb9bccc60) | Aug 31, 2021 |
| HP            | Pavilion 15                 | Notebook    | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | Notebook    | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [000d760a55](https://linux-hardware.org/?probe=000d760a55) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [3b05a7b317](https://linux-hardware.org/?probe=3b05a7b317) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | Notebook    | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | Notebook    | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | Notebook    | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| MSI           | Z87-G43                     | Desktop     | [a219ff197d](https://linux-hardware.org/?probe=a219ff197d) | Aug 29, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [01a43874df](https://linux-hardware.org/?probe=01a43874df) | Aug 28, 2021 |
| Acer          | Aspire 5100                 | Notebook    | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | Notebook    | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | Notebook    | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [5cd3f43e28](https://linux-hardware.org/?probe=5cd3f43e28) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6ed5f8c32b](https://linux-hardware.org/?probe=6ed5f8c32b) | Aug 27, 2021 |
| ASRock        | Z390 Phantom Gaming 4-IB    | Desktop     | [b01269fbc1](https://linux-hardware.org/?probe=b01269fbc1) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [c59a1fff0d](https://linux-hardware.org/?probe=c59a1fff0d) | Aug 26, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [accc3b9ebb](https://linux-hardware.org/?probe=accc3b9ebb) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| Acer          | AO722                       | Notebook    | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| HP            | 802E                        | Desktop     | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [8620323354](https://linux-hardware.org/?probe=8620323354) | Aug 25, 2021 |
| TianBei       | TB-H7                       | Notebook    | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Dell          | 0TP406                      | Desktop     | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| HP            | 2B4B                        | Desktop     | [4c5411522b](https://linux-hardware.org/?probe=4c5411522b) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | Notebook    | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | Notebook    | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [a720e3326a](https://linux-hardware.org/?probe=a720e3326a) | Aug 23, 2021 |
| Acer          | Aspire 8940G                | Notebook    | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | Notebook    | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | Notebook    | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [e6f053c5be](https://linux-hardware.org/?probe=e6f053c5be) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [8eed93b589](https://linux-hardware.org/?probe=8eed93b589) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [372a125910](https://linux-hardware.org/?probe=372a125910) | Aug 22, 2021 |
| Lenovo        | Board                       | Desktop     | [b4e9579228](https://linux-hardware.org/?probe=b4e9579228) | Aug 21, 2021 |
| Lenovo        | Board                       | Desktop     | [12088eed17](https://linux-hardware.org/?probe=12088eed17) | Aug 21, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [68c6a2734b](https://linux-hardware.org/?probe=68c6a2734b) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | Notebook    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | Notebook    | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | Notebook    | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | Notebook    | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [4bbb9f60f9](https://linux-hardware.org/?probe=4bbb9f60f9) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [0acfc1ab65](https://linux-hardware.org/?probe=0acfc1ab65) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [27898f0b8e](https://linux-hardware.org/?probe=27898f0b8e) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | Notebook    | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | Notebook    | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d78450d852](https://linux-hardware.org/?probe=d78450d852) | Aug 19, 2021 |
| Acer          | Aspire XC-605G              | Desktop     | [8bb6f8ef72](https://linux-hardware.org/?probe=8bb6f8ef72) | Aug 18, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [daf6bf889f](https://linux-hardware.org/?probe=daf6bf889f) | Aug 18, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [3be5b7f90e](https://linux-hardware.org/?probe=3be5b7f90e) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [06872ddde7](https://linux-hardware.org/?probe=06872ddde7) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [65567a1be4](https://linux-hardware.org/?probe=65567a1be4) | Aug 10, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | Desktop     | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [01e77d1c5f](https://linux-hardware.org/?probe=01e77d1c5f) | Aug 04, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [c5d61df0df](https://linux-hardware.org/?probe=c5d61df0df) | Aug 03, 2021 |
| Gigabyte      | B550M H                     | Desktop     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [733eb370f2](https://linux-hardware.org/?probe=733eb370f2) | Jul 27, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [79b20f33a0](https://linux-hardware.org/?probe=79b20f33a0) | Jul 24, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [94ef768b69](https://linux-hardware.org/?probe=94ef768b69) | Jul 24, 2021 |
| Acer          | Aspire E5-551G              | Notebook    | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [3bed53aab7](https://linux-hardware.org/?probe=3bed53aab7) | Jul 14, 2021 |
| Dell          | 0V8WGR A00                  | Desktop     | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Dell          | XPS L501X                   | Notebook    | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | Notebook    | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI           | 2AE0                        | Desktop     | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI           | 2AE0                        | Desktop     | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| Dell          | Inspiron 3582               | Notebook    | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [b9d86eb932](https://linux-hardware.org/?probe=b9d86eb932) | Jun 17, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [71de5617aa](https://linux-hardware.org/?probe=71de5617aa) | Jun 17, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | Notebook    | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| HP            | 843C                        | Desktop     | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | Notebook    | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP            | 8591                        | Desktop     | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP            | 8591                        | Desktop     | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| HP            | Unknown                     | Notebook    | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | Notebook    | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar       | A320MH                      | Desktop     | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar       | A320MH                      | Desktop     | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c41eec9cd3](https://linux-hardware.org/?probe=c41eec9cd3) | May 21, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | Notebook    | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Quanta        | XV1                         | All in one  | [d3b0fddedf](https://linux-hardware.org/?probe=d3b0fddedf) | May 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Quanta        | XV1                         | All in one  | [5d38d7934e](https://linux-hardware.org/?probe=5d38d7934e) | Apr 30, 2021 |
| Pegatron      | Benicia                     | Desktop     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [236ed4432a](https://linux-hardware.org/?probe=236ed4432a) | Apr 24, 2021 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek       | P5K                         | Desktop     | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell          | 0PGKWF A02                  | Desktop     | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0761ed6181](https://linux-hardware.org/?probe=0761ed6181) | Apr 16, 2021 |
| Acer          | Aspire XC-605G              | Desktop     | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-27-generic | 143       | 41.33%  |
| 5.11.0-34-generic | 92        | 26.59%  |
| 5.11.0-36-generic | 37        | 10.69%  |
| 5.8.0-53-generic  | 13        | 3.76%   |
| 5.11.0-25-generic | 13        | 3.76%   |
| 5.8.0-50-generic  | 12        | 3.47%   |
| 5.8.0-55-generic  | 10        | 2.89%   |
| 5.8.0-59-generic  | 8         | 2.31%   |
| 5.11.0-37-generic | 6         | 1.73%   |
| 5.8.0-63-generic  | 4         | 1.16%   |
| 5.8.0-49-generic  | 4         | 1.16%   |
| 5.8.0-45-generic  | 1         | 0.29%   |
| 5.4.0-42-generic  | 1         | 0.29%   |
| 5.13.18-xanmod1   | 1         | 0.29%   |
| 5.10.0-1044-oem   | 1         | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 287       | 84.16%  |
| 5.8.0   | 51        | 14.96%  |
| 5.4.0   | 1         | 0.29%   |
| 5.13.18 | 1         | 0.29%   |
| 5.10.0  | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 287       | 84.16%  |
| 5.8     | 51        | 14.96%  |
| 5.4     | 1         | 0.29%   |
| 5.13    | 1         | 0.29%   |
| 5.10    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 336       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME    | 329       | 97.63%  |
| XFCE     | 3         | 0.89%   |
| Unknown  | 3         | 0.89%   |
| Cinnamon | 1         | 0.3%    |
| Budgie   | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 332       | 98.52%  |
| Wayland | 4         | 1.19%   |
| Unknown | 1         | 0.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 297       | 88.39%  |
| GDM     | 33        | 9.82%   |
| GDM3    | 5         | 1.49%   |
| TDM     | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 122       | 36.31%  |
| de_DE | 33        | 9.82%   |
| en_GB | 32        | 9.52%   |
| pt_BR | 24        | 7.14%   |
| en_IN | 15        | 4.46%   |
| es_ES | 11        | 3.27%   |
| en_CA | 9         | 2.68%   |
| es_MX | 8         | 2.38%   |
| it_IT | 7         | 2.08%   |
| en_AU | 7         | 2.08%   |
| pl_PL | 6         | 1.79%   |
| fr_FR | 6         | 1.79%   |
| nl_NL | 5         | 1.49%   |
| es_CL | 5         | 1.49%   |
| en_ZA | 5         | 1.49%   |
| cs_CZ | 5         | 1.49%   |
| pt_PT | 4         | 1.19%   |
| en_NZ | 4         | 1.19%   |
| hu_HU | 3         | 0.89%   |
| sv_SE | 2         | 0.6%    |
| fr_CA | 2         | 0.6%    |
| es_PE | 2         | 0.6%    |
| es_CO | 2         | 0.6%    |
| de_CH | 2         | 0.6%    |
| zh_TW | 1         | 0.3%    |
| zh_CN | 1         | 0.3%    |
| sk_SK | 1         | 0.3%    |
| ru_UA | 1         | 0.3%    |
| ru_RU | 1         | 0.3%    |
| nl_BE | 1         | 0.3%    |
| ja_JP | 1         | 0.3%    |
| fr_BE | 1         | 0.3%    |
| fi_FI | 1         | 0.3%    |
| es_PA | 1         | 0.3%    |
| es_GT | 1         | 0.3%    |
| en_SG | 1         | 0.3%    |
| en_PH | 1         | 0.3%    |
| de_AT | 1         | 0.3%    |
| bg_BG | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 203       | 60.24%  |
| BIOS | 134       | 39.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 314       | 93.45%  |
| Zfs     | 8         | 2.38%   |
| Overlay | 6         | 1.79%   |
| Btrfs   | 4         | 1.19%   |
| Ext3    | 2         | 0.6%    |
| Xfs     | 1         | 0.3%    |
| Ext2    | 1         | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 300       | 89.29%  |
| GPT     | 33        | 9.82%   |
| MBR     | 3         | 0.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 331       | 98.22%  |
| Yes       | 6         | 1.78%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 295       | 87.8%   |
| Yes       | 41        | 12.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 60        | 17.86%  |
| Hewlett-Packard             | 52        | 15.48%  |
| Lenovo                      | 46        | 13.69%  |
| Dell                        | 45        | 13.39%  |
| Acer                        | 28        | 8.33%   |
| Gigabyte Technology         | 20        | 5.95%   |
| MSI                         | 17        | 5.06%   |
| Apple                       | 12        | 3.57%   |
| Toshiba                     | 9         | 2.68%   |
| Intel                       | 8         | 2.38%   |
| ASRock                      | 7         | 2.08%   |
| LG Electronics              | 4         | 1.19%   |
| Sony                        | 3         | 0.89%   |
| Fujitsu                     | 2         | 0.6%    |
| Biostar                     | 2         | 0.6%    |
| Unknown                     | 2         | 0.6%    |
| UNOWHY                      | 1         | 0.3%    |
| TianBei                     | 1         | 0.3%    |
| Sapphire Technology Limited | 1         | 0.3%    |
| Samsung Electronics         | 1         | 0.3%    |
| RCA                         | 1         | 0.3%    |
| Razer                       | 1         | 0.3%    |
| Quanta                      | 1         | 0.3%    |
| Positivo                    | 1         | 0.3%    |
| Pegatron                    | 1         | 0.3%    |
| Packard Bell                | 1         | 0.3%    |
| NCR                         | 1         | 0.3%    |
| KOGAN                       | 1         | 0.3%    |
| Jumper                      | 1         | 0.3%    |
| Insyde                      | 1         | 0.3%    |
| Google                      | 1         | 0.3%    |
| Foxconn                     | 1         | 0.3%    |
| eMachines                   | 1         | 0.3%    |
| Dynabook                    | 1         | 0.3%    |
| Cube                        | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 4         | 1.19%   |
| HP Notebook                              | 3         | 0.89%   |
| Gigabyte A320M-S2H                       | 3         | 0.89%   |
| Dell OptiPlex 990                        | 3         | 0.89%   |
| ASUS All Series                          | 3         | 0.89%   |
| MSI MS-7817                              | 2         | 0.6%    |
| Intel DQ77MK-R01                         | 2         | 0.6%    |
| HP ENVY Sleekbook 4 PC                   | 2         | 0.6%    |
| Dell XPS420                              | 2         | 0.6%    |
| Dell Latitude E6430                      | 2         | 0.6%    |
| Dell Inspiron 5566                       | 2         | 0.6%    |
| Dell Inspiron 15 7000 Gaming             | 2         | 0.6%    |
| ASUS X405UA                              | 2         | 0.6%    |
| ASUS PRIME B450M-GAMING/BR               | 2         | 0.6%    |
| ASUS M5A97 LE R2.0                       | 2         | 0.6%    |
| ASUS M5A78L-M/USB3                       | 2         | 0.6%    |
| Acer One S1003                           | 2         | 0.6%    |
| Acer Aspire V3-571G                      | 2         | 0.6%    |
| Acer Aspire ES1-512                      | 2         | 0.6%    |
| UNOWHY Y13G011S4EI                       | 1         | 0.3%    |
| Toshiba Satellite S75Dt-A                | 1         | 0.3%    |
| Toshiba Satellite Pro L450D              | 1         | 0.3%    |
| Toshiba Satellite L755                   | 1         | 0.3%    |
| Toshiba Satellite C870-1C2               | 1         | 0.3%    |
| Toshiba Satellite C850D-11C              | 1         | 0.3%    |
| Toshiba Satellite C850-1CP               | 1         | 0.3%    |
| Toshiba Satellite C75D-B                 | 1         | 0.3%    |
| Toshiba PORTEGE Z30-A                    | 1         | 0.3%    |
| Toshiba PORTEGE R700                     | 1         | 0.3%    |
| TianBei TB-H7                            | 1         | 0.3%    |
| Sony VPCS135FX                           | 1         | 0.3%    |
| Sony VPCF215FX                           | 1         | 0.3%    |
| Sony VGN-SR5                             | 1         | 0.3%    |
| Sapphire Limited PURE PLATINUM 970A-PLUS | 1         | 0.3%    |
| Samsung 550P5C/550P7C                    | 1         | 0.3%    |
| RCA W101-CS                              | 1         | 0.3%    |
| Razer Book 13 - RZ09-0357                | 1         | 0.3%    |
| Quanta CA27                              | 1         | 0.3%    |
| Positivo POS-PIH81DI                     | 1         | 0.3%    |
| Pegatron NE502AV-ABA a6750t              | 1         | 0.3%    |
| Packard Bell DOT S                       | 1         | 0.3%    |
| NCR xxxx-xxxx-xxxx                       | 1         | 0.3%    |
| MSI WE136AA-UUZ p6337ch                  | 1         | 0.3%    |
| MSI Pro 3515 Series                      | 1         | 0.3%    |
| MSI MS-B10611                            | 1         | 0.3%    |
| MSI MS-7D18                              | 1         | 0.3%    |
| MSI MS-7C37                              | 1         | 0.3%    |
| MSI MS-7B89                              | 1         | 0.3%    |
| MSI MS-7B84                              | 1         | 0.3%    |
| MSI MS-7A71                              | 1         | 0.3%    |
| MSI MS-7914                              | 1         | 0.3%    |
| MSI MS-7816                              | 1         | 0.3%    |
| MSI MS-7798                              | 1         | 0.3%    |
| MSI Modern 15 A11M                       | 1         | 0.3%    |
| MSI GS75 Stealth 10SF                    | 1         | 0.3%    |
| MSI GL62 7RDX                            | 1         | 0.3%    |
| MSI GE75 Raider 8RF                      | 1         | 0.3%    |
| LG S460-G.BG31P1                         | 1         | 0.3%    |
| LG C400-G.BC22P1                         | 1         | 0.3%    |
| LG A410-K.BE47P1                         | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 21        | 6.25%   |
| Lenovo ThinkPad       | 12        | 3.57%   |
| Dell Inspiron         | 12        | 3.57%   |
| Lenovo IdeaPad        | 11        | 3.27%   |
| HP Pavilion           | 10        | 2.98%   |
| Dell Latitude         | 9         | 2.68%   |
| Dell XPS              | 8         | 2.38%   |
| Toshiba Satellite     | 7         | 2.08%   |
| HP ENVY               | 6         | 1.79%   |
| HP EliteBook          | 6         | 1.79%   |
| ASUS PRIME            | 6         | 1.79%   |
| Lenovo Yoga           | 5         | 1.49%   |
| Lenovo ThinkCentre    | 5         | 1.49%   |
| Dell OptiPlex         | 5         | 1.49%   |
| ASUS VivoBook         | 5         | 1.49%   |
| ASUS ROG              | 5         | 1.49%   |
| HP ProBook            | 4         | 1.19%   |
| Dell Precision        | 4         | 1.19%   |
| ASUS M5A97            | 4         | 1.19%   |
| Unknown               | 4         | 1.19%   |
| HP Notebook           | 3         | 0.89%   |
| HP Compaq             | 3         | 0.89%   |
| HP 255                | 3         | 0.89%   |
| Gigabyte A320M-S2H    | 3         | 0.89%   |
| Dell Vostro           | 3         | 0.89%   |
| ASUS TUF              | 3         | 0.89%   |
| ASUS M5A78L-M         | 3         | 0.89%   |
| ASUS All              | 3         | 0.89%   |
| Toshiba PORTEGE       | 2         | 0.6%    |
| MSI MS-7817           | 2         | 0.6%    |
| Lenovo MIIX           | 2         | 0.6%    |
| Lenovo IdeaCentre     | 2         | 0.6%    |
| Intel DQ77MK-R01      | 2         | 0.6%    |
| HP t620               | 2         | 0.6%    |
| Gigabyte B550M        | 2         | 0.6%    |
| Gigabyte B450         | 2         | 0.6%    |
| Dell XPS420           | 2         | 0.6%    |
| ASUS ZenBook          | 2         | 0.6%    |
| ASUS X405UA           | 2         | 0.6%    |
| ASUS P8Z77-V          | 2         | 0.6%    |
| ASUS P8H61-M          | 2         | 0.6%    |
| ASUS ASUS             | 2         | 0.6%    |
| Apple MacBookPro11    | 2         | 0.6%    |
| Acer Swift            | 2         | 0.6%    |
| Acer One              | 2         | 0.6%    |
| UNOWHY Y13G011S4EI    | 1         | 0.3%    |
| TianBei TB-H7         | 1         | 0.3%    |
| Sony VPCS135FX        | 1         | 0.3%    |
| Sony VPCF215FX        | 1         | 0.3%    |
| Sony VGN-SR5          | 1         | 0.3%    |
| Sapphire Limited PURE | 1         | 0.3%    |
| Samsung 550P5C        | 1         | 0.3%    |
| RCA W101-CS           | 1         | 0.3%    |
| Razer Book            | 1         | 0.3%    |
| Quanta CA27           | 1         | 0.3%    |
| Positivo POS-PIH81DI  | 1         | 0.3%    |
| Pegatron NE502AV-ABA  | 1         | 0.3%    |
| Packard Bell DOT      | 1         | 0.3%    |
| NCR xxxx-xxxx-xxxx    | 1         | 0.3%    |
| MSI WE136AA-UUZ       | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 55        | 16.37%  |
| 2020 | 54        | 16.07%  |
| 2019 | 33        | 9.82%   |
| 2018 | 31        | 9.23%   |
| 2014 | 27        | 8.04%   |
| 2011 | 26        | 7.74%   |
| 2012 | 21        | 6.25%   |
| 2013 | 18        | 5.36%   |
| 2015 | 16        | 4.76%   |
| 2016 | 13        | 3.87%   |
| 2017 | 10        | 2.98%   |
| 2010 | 10        | 2.98%   |
| 2008 | 9         | 2.68%   |
| 2009 | 7         | 2.08%   |
| 2007 | 4         | 1.19%   |
| 2006 | 2         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 187       | 55.65%  |
| Desktop     | 122       | 36.31%  |
| All in one  | 9         | 2.68%   |
| Convertible | 8         | 2.38%   |
| Tablet      | 5         | 1.49%   |
| Mini pc     | 4         | 1.19%   |
| Server      | 1         | 0.3%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 293       | 87.2%   |
| Enabled  | 43        | 12.8%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 335       | 99.7%   |
| Yes  | 1         | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 90        | 26.55%  |
| 8.01-16.0   | 75        | 22.12%  |
| 3.01-4.0    | 72        | 21.24%  |
| 16.01-24.0  | 55        | 16.22%  |
| 32.01-64.0  | 30        | 8.85%   |
| 1.01-2.0    | 10        | 2.95%   |
| 64.01-256.0 | 4         | 1.18%   |
| 2.01-3.0    | 2         | 0.59%   |
| 24.01-32.0  | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 153       | 44.09%  |
| 2.01-3.0   | 112       | 32.28%  |
| 3.01-4.0   | 47        | 13.54%  |
| 4.01-8.0   | 28        | 8.07%   |
| 0.51-1.0   | 4         | 1.15%   |
| 24.01-32.0 | 1         | 0.29%   |
| 16.01-24.0 | 1         | 0.29%   |
| 8.01-16.0  | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 200       | 59.52%  |
| 2      | 87        | 25.89%  |
| 3      | 24        | 7.14%   |
| 4      | 13        | 3.87%   |
| 5      | 7         | 2.08%   |
| 8      | 2         | 0.6%    |
| 6      | 2         | 0.6%    |
| 0      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 187       | 55.33%  |
| Yes       | 151       | 44.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 297       | 88.13%  |
| No        | 40        | 11.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 260       | 77.38%  |
| No        | 76        | 22.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 207       | 61.61%  |
| No        | 129       | 38.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 69        | 20.54%  |
| Germany      | 36        | 10.71%  |
| Brazil       | 30        | 8.93%   |
| UK           | 28        | 8.33%   |
| India        | 16        | 4.76%   |
| Canada       | 12        | 3.57%   |
| Spain        | 11        | 3.27%   |
| Mexico       | 10        | 2.98%   |
| Australia    | 9         | 2.68%   |
| Italy        | 8         | 2.38%   |
| South Africa | 7         | 2.08%   |
| Netherlands  | 7         | 2.08%   |
| Hungary      | 6         | 1.79%   |
| France       | 6         | 1.79%   |
| Chile        | 6         | 1.79%   |
| Poland       | 5         | 1.49%   |
| Czechia      | 5         | 1.49%   |
| Switzerland  | 4         | 1.19%   |
| Sweden       | 4         | 1.19%   |
| New Zealand  | 4         | 1.19%   |
| Austria      | 4         | 1.19%   |
| Romania      | 3         | 0.89%   |
| Colombia     | 3         | 0.89%   |
| Thailand     | 2         | 0.6%    |
| Taiwan       | 2         | 0.6%    |
| Portugal     | 2         | 0.6%    |
| Philippines  | 2         | 0.6%    |
| Morocco      | 2         | 0.6%    |
| Malaysia     | 2         | 0.6%    |
| Indonesia    | 2         | 0.6%    |
| Greece       | 2         | 0.6%    |
| Belgium      | 2         | 0.6%    |
| Vietnam      | 1         | 0.3%    |
| Ukraine      | 1         | 0.3%    |
| Turkey       | 1         | 0.3%    |
| Tanzania     | 1         | 0.3%    |
| Slovakia     | 1         | 0.3%    |
| Serbia       | 1         | 0.3%    |
| Russia       | 1         | 0.3%    |
| Peru         | 1         | 0.3%    |
| Panama       | 1         | 0.3%    |
| Norway       | 1         | 0.3%    |
| Nepal        | 1         | 0.3%    |
| Mozambique   | 1         | 0.3%    |
| Madagascar   | 1         | 0.3%    |
| Kenya        | 1         | 0.3%    |
| Japan        | 1         | 0.3%    |
| Israel       | 1         | 0.3%    |
| Guatemala    | 1         | 0.3%    |
| Finland      | 1         | 0.3%    |
| El Salvador  | 1         | 0.3%    |
| Denmark      | 1         | 0.3%    |
| China        | 1         | 0.3%    |
| Bulgaria     | 1         | 0.3%    |
| Belarus      | 1         | 0.3%    |
| Argentina    | 1         | 0.3%    |
| Angola       | 1         | 0.3%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Rome                   | 4         | 1.19%   |
| Vienna                 | 3         | 0.89%   |
| S??o Lu?­s             | 3         | 0.89%   |
| Rio de Janeiro         | 3         | 0.89%   |
| Paris                  | 3         | 0.89%   |
| Hyderabad              | 3         | 0.89%   |
| Berlin                 | 3         | 0.89%   |
| Zurich                 | 2         | 0.59%   |
| Vancouver              | 2         | 0.59%   |
| Taboao da Serra        | 2         | 0.59%   |
| Stockholm              | 2         | 0.59%   |
| Santiago               | 2         | 0.59%   |
| Montreal               | 2         | 0.59%   |
| Milan                  | 2         | 0.59%   |
| Miami                  | 2         | 0.59%   |
| Mentor                 | 2         | 0.59%   |
| Melbourne              | 2         | 0.59%   |
| Madrid                 | 2         | 0.59%   |
| Maca?©                 | 2         | 0.59%   |
| London                 | 2         | 0.59%   |
| Livingston             | 2         | 0.59%   |
| Kuala Lumpur           | 2         | 0.59%   |
| Johannesburg           | 2         | 0.59%   |
| Glasgow                | 2         | 0.59%   |
| Ernakulam              | 2         | 0.59%   |
| Dunedin                | 2         | 0.59%   |
| Drummondville          | 2         | 0.59%   |
| Dortmund               | 2         | 0.59%   |
| Contagem               | 2         | 0.59%   |
| Chennai                | 2         | 0.59%   |
| Budapest               | 2         | 0.59%   |
| Brisbane               | 2         | 0.59%   |
| Auckland               | 2         | 0.59%   |
| Athens                 | 2         | 0.59%   |
| Ahmedabad              | 2         | 0.59%   |
| Zionsville             | 1         | 0.3%    |
| Zaventem               | 1         | 0.3%    |
| Zacatecas City         | 1         | 0.3%    |
| Zabrze                 | 1         | 0.3%    |
| Yokohama               | 1         | 0.3%    |
| Xalapa                 | 1         | 0.3%    |
| Wylie                  | 1         | 0.3%    |
| Wigan                  | 1         | 0.3%    |
| West Jordan            | 1         | 0.3%    |
| Warrenton              | 1         | 0.3%    |
| Wandsworth             | 1         | 0.3%    |
| Vespasiano             | 1         | 0.3%    |
| Veracruz               | 1         | 0.3%    |
| Valley Stream          | 1         | 0.3%    |
| Vadodara               | 1         | 0.3%    |
| Utrecht                | 1         | 0.3%    |
| Unterschleissheim      | 1         | 0.3%    |
| Twinsburg              | 1         | 0.3%    |
| Tucson                 | 1         | 0.3%    |
| Trujillo               | 1         | 0.3%    |
| Thame                  | 1         | 0.3%    |
| Tangier                | 1         | 0.3%    |
| Taby                   | 1         | 0.3%    |
| SÃ£o Bernardo do Campo | 1         | 0.3%    |
| Szombathely            | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 81        | 96     | 16.5%   |
| Samsung Electronics            | 73        | 95     | 14.87%  |
| WDC                            | 64        | 80     | 13.03%  |
| Toshiba                        | 36        | 36     | 7.33%   |
| SanDisk                        | 30        | 39     | 6.11%   |
| Unknown                        | 25        | 32     | 5.09%   |
| Kingston                       | 23        | 27     | 4.68%   |
| Hitachi                        | 18        | 20     | 3.67%   |
| Crucial                        | 15        | 17     | 3.05%   |
| HGST                           | 12        | 14     | 2.44%   |
| A-DATA Technology              | 10        | 11     | 2.04%   |
| SK Hynix                       | 9         | 11     | 1.83%   |
| Intel                          | 7         | 10     | 1.43%   |
| Apple                          | 7         | 8      | 1.43%   |
| Phison                         | 6         | 7      | 1.22%   |
| Micron Technology              | 6         | 7      | 1.22%   |
| Silicon Motion                 | 5         | 9      | 1.02%   |
| SPCC                           | 4         | 4      | 0.81%   |
| Intenso                        | 4         | 4      | 0.81%   |
| China                          | 4         | 5      | 0.81%   |
| Micron/Crucial Technology      | 3         | 3      | 0.61%   |
| LITEONIT                       | 3         | 4      | 0.61%   |
| Lexar                          | 3         | 3      | 0.61%   |
| Fujitsu                        | 3         | 4      | 0.61%   |
| Verbatim                       | 2         | 2      | 0.41%   |
| Team                           | 2         | 2      | 0.41%   |
| SABRENT                        | 2         | 2      | 0.41%   |
| PNY                            | 2         | 3      | 0.41%   |
| Patriot                        | 2         | 2      | 0.41%   |
| Lite-On                        | 2         | 2      | 0.41%   |
| KIOXIA                         | 2         | 2      | 0.41%   |
| KingSpec                       | 2         | 3      | 0.41%   |
| JMicron                        | 2         | 4      | 0.41%   |
| Hewlett-Packard                | 2         | 2      | 0.41%   |
| Gigabyte Technology            | 2         | 2      | 0.41%   |
| XPG                            | 1         | 1      | 0.2%    |
| Vaseky                         | 1         | 2      | 0.2%    |
| USB30                          | 1         | 2      | 0.2%    |
| T-FORCE                        | 1         | 1      | 0.2%    |
| Super Talent                   | 1         | 1      | 0.2%    |
| Solid State Storage Technology | 1         | 1      | 0.2%    |
| Realtek Semiconductor          | 1         | 1      | 0.2%    |
| OWC                            | 1         | 1      | 0.2%    |
| OCZ                            | 1         | 1      | 0.2%    |
| Netac                          | 1         | 1      | 0.2%    |
| MAXTOR                         | 1         | 1      | 0.2%    |
| KIOXIA-EXCERIA                 | 1         | 1      | 0.2%    |
| KingFast                       | 1         | 1      | 0.2%    |
| GOODRAM                        | 1         | 1      | 0.2%    |
| Config                         | 1         | 1      | 0.2%    |
| BUFFALO                        | 1         | 1      | 0.2%    |
| Apacer                         | 1         | 1      | 0.2%    |
| Unknown                        | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                  | 7         | 1.28%   |
| Seagate ST1000LM035-1RK172 1TB          | 7         | 1.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 7         | 1.28%   |
| Unknown SD/MMC/MS PRO 128GB             | 6         | 1.09%   |
| Seagate ST500DM002-1BD142 500GB         | 6         | 1.09%   |
| Samsung SSD 860 EVO 500GB               | 6         | 1.09%   |
| Samsung NVMe SSD Drive 256GB            | 6         | 1.09%   |
| Unknown MMC Card  32GB                  | 5         | 0.91%   |
| Toshiba MQ01ABF050 500GB                | 5         | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB          | 5         | 0.91%   |
| Samsung SSD 850 EVO 500GB               | 5         | 0.91%   |
| Samsung NVMe SSD Drive 500GB            | 5         | 0.91%   |
| Kingston SA400S37240G 240GB SSD         | 5         | 0.91%   |
| Crucial CT240BX500SSD1 240GB            | 5         | 0.91%   |
| WDC WD10EZEX-08WN4A0 1TB                | 4         | 0.73%   |
| Seagate ST9500325AS 500GB               | 4         | 0.73%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 4         | 0.73%   |
| Seagate ST2000DM001-9YN164 2TB          | 4         | 0.73%   |
| Samsung SSD 860 EVO 250GB               | 4         | 0.73%   |
| Samsung SSD 840 EVO 250GB               | 4         | 0.73%   |
| Samsung NVMe SSD Drive 512GB            | 4         | 0.73%   |
| Samsung NVMe SSD Drive 1TB              | 4         | 0.73%   |
| Kingston SA400S37120G 120GB SSD         | 4         | 0.73%   |
| WDC WD10EZEX-60WN4A0 1TB                | 3         | 0.55%   |
| Unknown MMC Card  128GB                 | 3         | 0.55%   |
| Toshiba HDWD110 1TB                     | 3         | 0.55%   |
| SK Hynix NVMe SSD Drive 256GB           | 3         | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB          | 3         | 0.55%   |
| SanDisk SSD PLUS 1000GB                 | 3         | 0.55%   |
| SanDisk SDSSDA240G 240GB                | 3         | 0.55%   |
| Sandisk NVMe SSD Drive 512GB            | 3         | 0.55%   |
| Sandisk NVMe SSD Drive 256GB            | 3         | 0.55%   |
| Samsung SSD 860 EVO 1TB                 | 3         | 0.55%   |
| Samsung HD103UJ 1TB                     | 3         | 0.55%   |
| Phison NVMe SSD Drive 1TB               | 3         | 0.55%   |
| Kingston SV300S37A120G 120GB SSD        | 3         | 0.55%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.55%   |
| HGST HTS725050A7E630 500GB              | 3         | 0.55%   |
| HGST HTS721010A9E630 1TB                | 3         | 0.55%   |
| Crucial CT480BX500SSD1 480GB            | 3         | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 2         | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 2         | 0.36%   |
| WDC WD6400BEVT-22A0RT0 640GB            | 2         | 0.36%   |
| WDC WD5000AAKX-08U6AA0 500GB            | 2         | 0.36%   |
| WDC WD1600AAJS-75M0A0 160GB             | 2         | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.36%   |
| WDC WD10EZEX-60M2NA0 1TB                | 2         | 0.36%   |
| WDC WD10EZEX-22BN5A0 1TB                | 2         | 0.36%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.36%   |
| Toshiba MQ02ABD100H 1TB                 | 2         | 0.36%   |
| Toshiba MQ01ABD032 320GB                | 2         | 0.36%   |
| Toshiba MK3265GSX 320GB                 | 2         | 0.36%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 0.36%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 2         | 0.36%   |
| Toshiba DT01ACA200 2TB                  | 2         | 0.36%   |
| Toshiba DT01ACA050 500GB                | 2         | 0.36%   |
| SPCC SPCCSolidStateDisk 256GB SSD       | 2         | 0.36%   |
| SK Hynix NVMe SSD Drive 512GB           | 2         | 0.36%   |
| Silicon Motion NVMe SSD Drive 128GB     | 2         | 0.36%   |
| Seagate ST9500420AS 500GB               | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 80        | 92     | 36.53%  |
| WDC                 | 58        | 71     | 26.48%  |
| Toshiba             | 27        | 27     | 12.33%  |
| Hitachi             | 18        | 20     | 8.22%   |
| HGST                | 12        | 14     | 5.48%   |
| Samsung Electronics | 9         | 11     | 4.11%   |
| Unknown             | 6         | 8      | 2.74%   |
| Fujitsu             | 3         | 4      | 1.37%   |
| Apple               | 3         | 3      | 1.37%   |
| Hewlett-Packard     | 2         | 2      | 0.91%   |
| MAXTOR              | 1         | 1      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 47     | 24.55%  |
| Kingston            | 20        | 24     | 11.98%  |
| SanDisk             | 19        | 26     | 11.38%  |
| Crucial             | 14        | 16     | 8.38%   |
| A-DATA Technology   | 8         | 9      | 4.79%   |
| WDC                 | 6         | 6      | 3.59%   |
| Toshiba             | 4         | 4      | 2.4%    |
| SPCC                | 4         | 4      | 2.4%    |
| Micron Technology   | 4         | 5      | 2.4%    |
| Intenso             | 4         | 4      | 2.4%    |
| China               | 4         | 5      | 2.4%    |
| SK Hynix            | 3         | 3      | 1.8%    |
| LITEONIT            | 3         | 4      | 1.8%    |
| Lexar               | 3         | 3      | 1.8%    |
| Apple               | 3         | 3      | 1.8%    |
| Verbatim            | 2         | 2      | 1.2%    |
| Team                | 2         | 2      | 1.2%    |
| SABRENT             | 2         | 2      | 1.2%    |
| PNY                 | 2         | 3      | 1.2%    |
| Patriot             | 2         | 2      | 1.2%    |
| KingSpec            | 2         | 3      | 1.2%    |
| Intel               | 2         | 2      | 1.2%    |
| Gigabyte Technology | 2         | 2      | 1.2%    |
| USB30               | 1         | 2      | 0.6%    |
| Super Talent        | 1         | 1      | 0.6%    |
| Seagate             | 1         | 1      | 0.6%    |
| PHISON              | 1         | 1      | 0.6%    |
| OWC                 | 1         | 1      | 0.6%    |
| OCZ                 | 1         | 1      | 0.6%    |
| Netac               | 1         | 1      | 0.6%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.6%    |
| GOODRAM             | 1         | 1      | 0.6%    |
| BUFFALO             | 1         | 1      | 0.6%    |
| Apacer              | 1         | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 184       | 253    | 41.91%  |
| SSD     | 142       | 193    | 32.35%  |
| NVMe    | 86        | 111    | 19.59%  |
| MMC     | 16        | 20     | 3.64%   |
| Unknown | 11        | 15     | 2.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 271       | 435    | 68.96%  |
| NVMe | 85        | 109    | 21.63%  |
| SAS  | 21        | 28     | 5.34%   |
| MMC  | 16        | 20     | 4.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 203       | 261    | 58.67%  |
| 0.51-1.0   | 107       | 139    | 30.92%  |
| 1.01-2.0   | 25        | 32     | 7.23%   |
| 3.01-4.0   | 6         | 8      | 1.73%   |
| 4.01-10.0  | 4         | 4      | 1.16%   |
| 2.01-3.0   | 1         | 2      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 100       | 29.76%  |
| 251-500        | 86        | 25.6%   |
| 501-1000       | 55        | 16.37%  |
| 51-100         | 37        | 11.01%  |
| 1001-2000      | 21        | 6.25%   |
| 21-50          | 9         | 2.68%   |
| More than 3000 | 8         | 2.38%   |
| 2001-3000      | 7         | 2.08%   |
| 1-20           | 7         | 2.08%   |
| Unknown        | 6         | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 161       | 47.08%  |
| 21-50          | 82        | 23.98%  |
| 101-250        | 32        | 9.36%   |
| 51-100         | 28        | 8.19%   |
| 251-500        | 11        | 3.22%   |
| 501-1000       | 11        | 3.22%   |
| Unknown        | 6         | 1.75%   |
| More than 3000 | 5         | 1.46%   |
| 1001-2000      | 5         | 1.46%   |
| 2001-3000      | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB        | 2         | 2      | 22.22%  |
| WDC WD10JPVX-22JC3T0 1TB       | 1         | 1      | 11.11%  |
| WDC WD10EZEX-21M2NA0 1TB       | 1         | 2      | 11.11%  |
| Toshiba MK3265GSX 320GB        | 1         | 1      | 11.11%  |
| Seagate ST9500420AS 500GB      | 1         | 1      | 11.11%  |
| Seagate ST9200420ASG 200GB     | 1         | 1      | 11.11%  |
| Seagate ST4000DM004-2CV104 4TB | 1         | 1      | 11.11%  |
| HGST HTS725050A7E630 500GB     | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 33.33%  |
| Seagate | 3         | 3      | 33.33%  |
| WDC     | 2         | 3      | 22.22%  |
| HGST    | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 33.33%  |
| Seagate | 3         | 3      | 33.33%  |
| WDC     | 2         | 3      | 22.22%  |
| HGST    | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                 | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 302       | 530    | 86.78%  |
| Works    | 36        | 51     | 10.34%  |
| Malfunc  | 9         | 10     | 2.59%   |
| Failed   | 1         | 1      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 233       | 57.39%  |
| AMD                              | 69        | 17%     |
| Samsung Electronics              | 34        | 8.37%   |
| Sandisk                          | 13        | 3.2%    |
| SK Hynix                         | 6         | 1.48%   |
| Phison Electronics               | 6         | 1.48%   |
| ASMedia Technology               | 6         | 1.48%   |
| Silicon Motion                   | 5         | 1.23%   |
| Toshiba America Info Systems     | 4         | 0.99%   |
| Micron/Crucial Technology        | 3         | 0.74%   |
| KIOXIA                           | 3         | 0.74%   |
| Kingston Technology Company      | 3         | 0.74%   |
| ADATA Technology                 | 3         | 0.74%   |
| VIA Technologies                 | 2         | 0.49%   |
| Silicon Image                    | 2         | 0.49%   |
| Nvidia                           | 2         | 0.49%   |
| Micron Technology                | 2         | 0.49%   |
| Marvell Technology Group         | 2         | 0.49%   |
| Lite-On Technology               | 2         | 0.49%   |
| Solid State Storage Technology   | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| Realtek Semiconductor            | 1         | 0.25%   |
| LSI Logic / Symbios Logic        | 1         | 0.25%   |
| JMicron Technology               | 1         | 0.25%   |
| Apple                            | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 44        | 9.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 22        | 4.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 17        | 3.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17        | 3.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 14        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 14        | 3.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 13        | 2.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12        | 2.63%   |
| Intel SATA Controller [RAID mode]                                                       | 11        | 2.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 2.19%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10        | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9         | 1.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8         | 1.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 1.54%   |
| Samsung NVMe SSD Controller 980                                                         | 6         | 1.32%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.32%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 1.32%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 1.32%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5         | 1.1%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 5         | 1.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5         | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 5         | 1.1%    |
| AMD FCH SATA Controller D                                                               | 5         | 1.1%    |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 4         | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.88%   |
| Intel SSD 660P Series                                                                   | 4         | 0.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.88%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 4         | 0.88%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 0.66%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3         | 0.66%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3         | 0.66%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 0.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.66%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.66%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 0.66%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2         | 0.44%   |
| SK Hynix BC511                                                                          | 2         | 0.44%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 0.44%   |
| Sandisk PC SN520 NVMe SSD                                                               | 2         | 0.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.44%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.44%   |
| Micron Non-Volatile memory controller                                                   | 2         | 0.44%   |
| Lite-On Non-Volatile memory controller                                                  | 2         | 0.44%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 0.44%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 0.44%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 0.44%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 0.44%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 252       | 61.02%  |
| NVMe | 85        | 20.58%  |
| IDE  | 44        | 10.65%  |
| RAID | 32        | 7.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 258       | 76.79%  |
| AMD    | 78        | 23.21%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 2.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 2.08%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 2.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.49%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 5         | 1.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.49%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 5         | 1.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 1.19%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.19%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.89%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 3         | 0.89%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.89%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 3         | 0.89%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.89%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.89%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 3         | 0.89%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 3         | 0.89%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.89%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3         | 0.89%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 2         | 0.6%    |
| Intel Pentium CPU P6200 @ 2.13GHz             | 2         | 0.6%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 2         | 0.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.6%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.6%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.6%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.6%    |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.6%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.6%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.6%    |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 0.6%    |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.6%    |
| Intel Core i5-3340 CPU @ 3.10GHz              | 2         | 0.6%    |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.6%    |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.6%    |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 0.6%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.6%    |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2         | 0.6%    |
| Intel Core i3-6100U CPU @ 2.30GHz             | 2         | 0.6%    |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.6%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.6%    |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 0.6%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.6%    |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 2         | 0.6%    |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.6%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.6%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 0.6%    |
| Intel Celeron CPU N2940 @ 1.83GHz             | 2         | 0.6%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.6%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 0.6%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.6%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 0.6%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2         | 0.6%    |
| AMD FX-8320E Eight-Core Processor             | 2         | 0.6%    |
| AMD A6-7310 APU with AMD Radeon R4 Graphics   | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 94        | 27.98%  |
| Intel Core i7                        | 55        | 16.37%  |
| Intel Core i3                        | 31        | 9.23%   |
| AMD Ryzen 5                          | 20        | 5.95%   |
| Intel Celeron                        | 17        | 5.06%   |
| Intel Core 2 Duo                     | 13        | 3.87%   |
| Other                                | 10        | 2.98%   |
| AMD FX                               | 10        | 2.98%   |
| Intel Pentium                        | 9         | 2.68%   |
| AMD Ryzen 7                          | 8         | 2.38%   |
| AMD Ryzen 3                          | 8         | 2.38%   |
| AMD A6                               | 8         | 2.38%   |
| Intel Atom                           | 7         | 2.08%   |
| Intel Xeon                           | 6         | 1.79%   |
| Intel Core 2 Quad                    | 5         | 1.49%   |
| Intel Pentium Dual-Core              | 3         | 0.89%   |
| Intel Pentium Dual                   | 3         | 0.89%   |
| Intel Pentium Silver                 | 2         | 0.6%    |
| AMD Phenom II X4                     | 2         | 0.6%    |
| AMD GX                               | 2         | 0.6%    |
| AMD E1                               | 2         | 0.6%    |
| AMD A10                              | 2         | 0.6%    |
| Intel Pentium Gold                   | 1         | 0.3%    |
| Intel Pentium 4                      | 1         | 0.3%    |
| Intel Core i9                        | 1         | 0.3%    |
| Intel Core 2                         | 1         | 0.3%    |
| Intel Celeron M                      | 1         | 0.3%    |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.3%    |
| AMD Turion 64 Mobile                 | 1         | 0.3%    |
| AMD Ryzen 9                          | 1         | 0.3%    |
| AMD Ryzen 7 PRO                      | 1         | 0.3%    |
| AMD Opteron                          | 1         | 0.3%    |
| AMD E2                               | 1         | 0.3%    |
| AMD E                                | 1         | 0.3%    |
| AMD C-60                             | 1         | 0.3%    |
| AMD Athlon X4                        | 1         | 0.3%    |
| AMD Athlon II X3                     | 1         | 0.3%    |
| AMD Athlon 64 X2                     | 1         | 0.3%    |
| AMD Athlon                           | 1         | 0.3%    |
| AMD A8                               | 1         | 0.3%    |
| AMD A4                               | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 150       | 44.64%  |
| 2      | 140       | 41.67%  |
| 6      | 21        | 6.25%   |
| 8      | 13        | 3.87%   |
| 1      | 5         | 1.49%   |
| 3      | 4         | 1.19%   |
| 12     | 2         | 0.6%    |
| 10     | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 335       | 99.7%   |
| 2      | 1         | 0.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 213       | 63.39%  |
| 1      | 123       | 36.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 336       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 29        | 8.58%   |
| 0x206a7    | 29        | 8.58%   |
| Unknown    | 24        | 7.1%    |
| 0x306c3    | 20        | 5.92%   |
| 0x806ea    | 14        | 4.14%   |
| 0x506e3    | 12        | 3.55%   |
| 0x08701021 | 11        | 3.25%   |
| 0x40651    | 10        | 2.96%   |
| 0x1067a    | 10        | 2.96%   |
| 0x806ec    | 8         | 2.37%   |
| 0x6fb      | 8         | 2.37%   |
| 0x06000852 | 8         | 2.37%   |
| 0x806c1    | 7         | 2.07%   |
| 0x30678    | 7         | 2.07%   |
| 0x806e9    | 6         | 1.78%   |
| 0x406e3    | 6         | 1.78%   |
| 0x406c4    | 6         | 1.78%   |
| 0x306d4    | 6         | 1.78%   |
| 0x20655    | 6         | 1.78%   |
| 0x906ea    | 5         | 1.48%   |
| 0x506c9    | 5         | 1.48%   |
| 0x08108109 | 5         | 1.48%   |
| 0x08108102 | 5         | 1.48%   |
| 0x06001119 | 5         | 1.48%   |
| 0x906e9    | 4         | 1.18%   |
| 0x706a1    | 4         | 1.18%   |
| 0x6fd      | 4         | 1.18%   |
| 0xa0655    | 3         | 0.89%   |
| 0xa0652    | 3         | 0.89%   |
| 0x806eb    | 3         | 0.89%   |
| 0x706e5    | 3         | 0.89%   |
| 0x20652    | 3         | 0.89%   |
| 0x10676    | 3         | 0.89%   |
| 0x08600106 | 3         | 0.89%   |
| 0x07030106 | 3         | 0.89%   |
| 0x07030105 | 3         | 0.89%   |
| 0x05000119 | 3         | 0.89%   |
| 0x010000c8 | 3         | 0.89%   |
| 0xa0653    | 2         | 0.59%   |
| 0x906eb    | 2         | 0.59%   |
| 0x6f6      | 2         | 0.59%   |
| 0x40661    | 2         | 0.59%   |
| 0x206c2    | 2         | 0.59%   |
| 0x08701013 | 2         | 0.59%   |
| 0x08600104 | 2         | 0.59%   |
| 0x08101016 | 2         | 0.59%   |
| 0x0800820d | 2         | 0.59%   |
| 0x0700010f | 2         | 0.59%   |
| 0x0600063e | 2         | 0.59%   |
| 0xf43      | 1         | 0.3%    |
| 0x906ec    | 1         | 0.3%    |
| 0x906c0    | 1         | 0.3%    |
| 0x706a8    | 1         | 0.3%    |
| 0x6fa      | 1         | 0.3%    |
| 0x306f2    | 1         | 0.3%    |
| 0x306e4    | 1         | 0.3%    |
| 0x30661    | 1         | 0.3%    |
| 0x106e5    | 1         | 0.3%    |
| 0x0a201016 | 1         | 0.3%    |
| 0x08608102 | 1         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 51        | 15.18%  |
| Haswell         | 35        | 10.42%  |
| SandyBridge     | 30        | 8.93%   |
| IvyBridge       | 30        | 8.93%   |
| Skylake         | 19        | 5.65%   |
| Zen 2           | 18        | 5.36%   |
| Core            | 15        | 4.46%   |
| Silvermont      | 14        | 4.17%   |
| Zen+            | 13        | 3.87%   |
| Piledriver      | 13        | 3.87%   |
| Penryn          | 13        | 3.87%   |
| Westmere        | 12        | 3.57%   |
| CometLake       | 8         | 2.38%   |
| TigerLake       | 7         | 2.08%   |
| Puma            | 7         | 2.08%   |
| Broadwell       | 6         | 1.79%   |
| Zen             | 5         | 1.49%   |
| Goldmont plus   | 5         | 1.49%   |
| Goldmont        | 5         | 1.49%   |
| Jaguar          | 4         | 1.19%   |
| K10             | 3         | 0.89%   |
| IceLake         | 3         | 0.89%   |
| Bobcat          | 3         | 0.89%   |
| Zen 3           | 2         | 0.6%    |
| Nehalem         | 2         | 0.6%    |
| K8 Hammer       | 2         | 0.6%    |
| Excavator       | 2         | 0.6%    |
| Bulldozer       | 2         | 0.6%    |
| Tremont         | 1         | 0.3%    |
| Steamroller     | 1         | 0.3%    |
| NetBurst        | 1         | 0.3%    |
| K8 & K10 hybrid | 1         | 0.3%    |
| K10 Llano       | 1         | 0.3%    |
| Bonnell         | 1         | 0.3%    |
| Unknown         | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 190       | 49.48%  |
| Nvidia                           | 106       | 27.6%   |
| AMD                              | 85        | 22.14%  |
| VIA Technologies                 | 1         | 0.26%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |
| Matrox Electronics Systems       | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 5.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 4.06%   |
| Intel UHD Graphics 620                                                                   | 14        | 3.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 2.79%   |
| AMD Picasso                                                                              | 10        | 2.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 2.03%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7         | 1.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.78%   |
| Intel HD Graphics 630                                                                    | 7         | 1.78%   |
| Intel HD Graphics 620                                                                    | 7         | 1.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.27%   |
| AMD Renoir                                                                               | 5         | 1.27%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 1.27%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 4         | 1.02%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.02%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 1.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.02%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 4         | 1.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.76%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.76%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 0.76%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.76%   |
| Intel HD Graphics 530                                                                    | 3         | 0.76%   |
| Intel HD Graphics 500                                                                    | 3         | 0.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.76%   |
| AMD RS780L [Radeon 3000]                                                                 | 3         | 0.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.76%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 0.76%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 3         | 0.76%   |
| Nvidia TU117M                                                                            | 2         | 0.51%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.51%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 2         | 0.51%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.51%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.51%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2         | 0.51%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 2         | 0.51%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.51%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.51%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.51%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.51%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.51%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.51%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 2         | 0.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 147       | 43.62%  |
| 1 x AMD        | 71        | 21.07%  |
| 1 x Nvidia     | 68        | 20.18%  |
| Intel + Nvidia | 32        | 9.5%    |
| AMD + Nvidia   | 6         | 1.78%   |
| Intel + AMD    | 5         | 1.48%   |
| 2 x AMD        | 4         | 1.19%   |
| 2 x Intel      | 1         | 0.3%    |
| 1 x VIA        | 1         | 0.3%    |
| 1 x SiS        | 1         | 0.3%    |
| 1 x Matrox     | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 255       | 75.89%  |
| Proprietary | 70        | 20.83%  |
| Unknown     | 11        | 3.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 180       | 53.41%  |
| 1.01-2.0   | 46        | 13.65%  |
| 0.51-1.0   | 37        | 10.98%  |
| 0.01-0.5   | 29        | 8.61%   |
| 3.01-4.0   | 21        | 6.23%   |
| 7.01-8.0   | 10        | 2.97%   |
| 5.01-6.0   | 9         | 2.67%   |
| 2.01-3.0   | 3         | 0.89%   |
| 16.01-24.0 | 1         | 0.3%    |
| 8.01-16.0  | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 43        | 12.65%  |
| Samsung Electronics     | 41        | 12.06%  |
| Chimei Innolux          | 34        | 10%     |
| BOE                     | 28        | 8.24%   |
| LG Display              | 27        | 7.94%   |
| Goldstar                | 14        | 4.12%   |
| Acer                    | 14        | 4.12%   |
| Dell                    | 13        | 3.82%   |
| Hewlett-Packard         | 10        | 2.94%   |
| Apple                   | 10        | 2.94%   |
| AOC                     | 10        | 2.94%   |
| Sharp                   | 9         | 2.65%   |
| Lenovo                  | 8         | 2.35%   |
| Philips                 | 7         | 2.06%   |
| Chi Mei Optoelectronics | 7         | 2.06%   |
| BenQ                    | 7         | 2.06%   |
| Unknown                 | 5         | 1.47%   |
| PANDA                   | 5         | 1.47%   |
| LG Electronics          | 5         | 1.47%   |
| Vizio                   | 4         | 1.18%   |
| Ancor Communications    | 4         | 1.18%   |
| Sony                    | 3         | 0.88%   |
| Iiyama                  | 3         | 0.88%   |
| HPN                     | 3         | 0.88%   |
| Vestel                  | 2         | 0.59%   |
| Sceptre Tech            | 2         | 0.59%   |
| NEC Computers           | 2         | 0.59%   |
| LGD                     | 2         | 0.59%   |
| InfoVision              | 2         | 0.59%   |
| AUS                     | 2         | 0.59%   |
| Xiaomi                  | 1         | 0.29%   |
| ViewSonic               | 1         | 0.29%   |
| Vestel Elektronik       | 1         | 0.29%   |
| PKB                     | 1         | 0.29%   |
| Panasonic               | 1         | 0.29%   |
| ONN                     | 1         | 0.29%   |
| OEM                     | 1         | 0.29%   |
| LG Philips              | 1         | 0.29%   |
| InnoLux Display         | 1         | 0.29%   |
| HannStar                | 1         | 0.29%   |
| Gigabyte Technology     | 1         | 0.29%   |
| Gateway                 | 1         | 0.29%   |
| Fujitsu Siemens         | 1         | 0.29%   |
| CPT                     | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch         | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch           | 3         | 0.86%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 2         | 0.57%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                 | 2         | 0.57%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch             | 2         | 0.57%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 2         | 0.57%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 0.57%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 2         | 0.57%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                 | 2         | 0.57%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 2         | 0.57%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch             | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch         | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch         | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch         | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch         | 2         | 0.57%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 2         | 0.57%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 2         | 0.57%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                      | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch           | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch          | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch           | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch           | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch           | 2         | 0.57%   |
| Apple Color LCD APP9C5B 1280x800 290x180mm 13.4-inch                    | 2         | 0.57%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                      | 1         | 0.29%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch               | 1         | 0.29%   |
| Vizio PC VIZCA27 1920x1080 597x336mm 27.0-inch                          | 1         | 0.29%   |
| Vizio E43u-D2 VIZ1018 3840x2160 953x543mm 43.2-inch                     | 1         | 0.29%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 0.29%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                           | 1         | 0.29%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.29%   |
| Unknown LCD Monitor SAMSUNG 2464x900                                    | 1         | 0.29%   |
| Unknown LCD Monitor RTK                                                 | 1         | 0.29%   |
| Unknown LCD Monitor OPD PX227H-HDMI1 4160x1440                          | 1         | 0.29%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                               | 1         | 0.29%   |
| Unknown LCD Monitor Kingston Technology 40'TV 1834x1031                 | 1         | 0.29%   |
| Unknown LCD Monitor GKK MONITOR 1920x1080                               | 1         | 0.29%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                      | 1         | 0.29%   |
| Sony TV *00 SNYA405 3840x2160 952x535mm 43.0-inch                       | 1         | 0.29%   |
| Sony AVAMP SNY9301 1280x720 708x398mm 32.0-inch                         | 1         | 0.29%   |
| Sharp LQ134R1JX48 SHP1528 3840x2400 288x180mm 13.4-inch                 | 1         | 0.29%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                 | 1         | 0.29%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                 | 1         | 0.29%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                 | 1         | 0.29%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                 | 1         | 0.29%   |
| Sharp LCD Monitor SHP146B 3200x1800 294x165mm 13.3-inch                 | 1         | 0.29%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                 | 1         | 0.29%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                 | 1         | 0.29%   |
| Sharp HDMI SHP101E 1920x1080 820x460mm 37.0-inch                        | 1         | 0.29%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1         | 0.29%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch           | 1         | 0.29%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1         | 0.29%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 133       | 39.82%  |
| 1366x768 (WXGA)    | 88        | 26.35%  |
| 3840x2160 (4K)     | 24        | 7.19%   |
| 1600x900 (HD+)     | 12        | 3.59%   |
| Unknown            | 12        | 3.59%   |
| 1280x800 (WXGA)    | 8         | 2.4%    |
| 3840x1080          | 7         | 2.1%    |
| 1680x1050 (WSXGA+) | 6         | 1.8%    |
| 1920x1200 (WUXGA)  | 5         | 1.5%    |
| 2560x1440 (QHD)    | 4         | 1.2%    |
| 3440x1440          | 3         | 0.9%    |
| 3200x1800 (QHD+)   | 3         | 0.9%    |
| 3840x2400          | 2         | 0.6%    |
| 2880x1800          | 2         | 0.6%    |
| 2560x1600          | 2         | 0.6%    |
| 2560x1080          | 2         | 0.6%    |
| 1440x900 (WXGA+)   | 2         | 0.6%    |
| 1280x1024 (SXGA)   | 2         | 0.6%    |
| 5760x2160          | 1         | 0.3%    |
| 4160x1440          | 1         | 0.3%    |
| 3840x1200          | 1         | 0.3%    |
| 3600x1080          | 1         | 0.3%    |
| 3360x1080          | 1         | 0.3%    |
| 3120x1050          | 1         | 0.3%    |
| 2944x1080          | 1         | 0.3%    |
| 2464x900           | 1         | 0.3%    |
| 2256x1504          | 1         | 0.3%    |
| 1920x540           | 1         | 0.3%    |
| 1920x515           | 1         | 0.3%    |
| 1834x1031          | 1         | 0.3%    |
| 1600x1200          | 1         | 0.3%    |
| 1360x768           | 1         | 0.3%    |
| 1280x720 (HD)      | 1         | 0.3%    |
| 1024x768 (XGA)     | 1         | 0.3%    |
| 1024x600           | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 94        | 28.31%  |
| 13      | 45        | 13.55%  |
| Unknown | 44        | 13.25%  |
| 24      | 22        | 6.63%   |
| 14      | 19        | 5.72%   |
| 27      | 16        | 4.82%   |
| 23      | 16        | 4.82%   |
| 17      | 12        | 3.61%   |
| 21      | 11        | 3.31%   |
| 31      | 8         | 2.41%   |
| 11      | 6         | 1.81%   |
| 34      | 5         | 1.51%   |
| 18      | 5         | 1.51%   |
| 84      | 4         | 1.2%    |
| 22      | 4         | 1.2%    |
| 19      | 3         | 0.9%    |
| 48      | 2         | 0.6%    |
| 46      | 2         | 0.6%    |
| 25      | 2         | 0.6%    |
| 74      | 1         | 0.3%    |
| 55      | 1         | 0.3%    |
| 43      | 1         | 0.3%    |
| 41      | 1         | 0.3%    |
| 40      | 1         | 0.3%    |
| 37      | 1         | 0.3%    |
| 36      | 1         | 0.3%    |
| 32      | 1         | 0.3%    |
| 20      | 1         | 0.3%    |
| 16      | 1         | 0.3%    |
| 12      | 1         | 0.3%    |
| 10      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 133       | 40.55%  |
| 501-600     | 51        | 15.55%  |
| Unknown     | 44        | 13.41%  |
| 201-300     | 33        | 10.06%  |
| 401-500     | 22        | 6.71%   |
| 351-400     | 14        | 4.27%   |
| 601-700     | 10        | 3.05%   |
| 701-800     | 7         | 2.13%   |
| 1501-2000   | 5         | 1.52%   |
| 1001-1500   | 5         | 1.52%   |
| 801-900     | 2         | 0.61%   |
| 901-1000    | 2         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 227       | 73.7%   |
| Unknown | 41        | 13.31%  |
| 16/10   | 29        | 9.42%   |
| 21/9    | 5         | 1.62%   |
| 4/3     | 2         | 0.65%   |
| 5/4     | 1         | 0.32%   |
| 32/9    | 1         | 0.32%   |
| 3/2     | 1         | 0.32%   |
| 3.73    | 1         | 0.32%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 95        | 28.7%   |
| 81-90          | 45        | 13.6%   |
| 201-250        | 44        | 13.29%  |
| Unknown        | 44        | 13.29%  |
| 71-80          | 19        | 5.74%   |
| 301-350        | 16        | 4.83%   |
| 351-500        | 14        | 4.23%   |
| 121-130        | 10        | 3.02%   |
| 251-300        | 8         | 2.42%   |
| 501-1000       | 8         | 2.42%   |
| More than 1000 | 7         | 2.11%   |
| 51-60          | 6         | 1.81%   |
| 151-200        | 6         | 1.81%   |
| 141-150        | 5         | 1.51%   |
| 61-70          | 1         | 0.3%    |
| 41-50          | 1         | 0.3%    |
| 131-140        | 1         | 0.3%    |
| 91-100         | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 107       | 33.13%  |
| 51-100        | 76        | 23.53%  |
| 121-160       | 64        | 19.81%  |
| Unknown       | 44        | 13.62%  |
| 161-240       | 15        | 4.64%   |
| More than 240 | 10        | 3.1%    |
| 1-50          | 7         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 283       | 83.73%  |
| 2     | 44        | 13.02%  |
| 0     | 10        | 2.96%   |
| 3     | 1         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 183       | 35.47%  |
| Intel                            | 148       | 28.68%  |
| Qualcomm Atheros                 | 66        | 12.79%  |
| Broadcom                         | 34        | 6.59%   |
| Broadcom Limited                 | 10        | 1.94%   |
| Ralink Technology                | 8         | 1.55%   |
| Ralink                           | 8         | 1.55%   |
| TP-Link                          | 7         | 1.36%   |
| Marvell Technology Group         | 5         | 0.97%   |
| DisplayLink                      | 5         | 0.97%   |
| Xiaomi                           | 4         | 0.78%   |
| Samsung Electronics              | 3         | 0.58%   |
| Huawei Technologies              | 3         | 0.58%   |
| D-Link System                    | 3         | 0.58%   |
| Qualcomm                         | 2         | 0.39%   |
| OPPO                             | 2         | 0.39%   |
| Nvidia                           | 2         | 0.39%   |
| NetGear                          | 2         | 0.39%   |
| MediaTek                         | 2         | 0.39%   |
| Google                           | 2         | 0.39%   |
| Dell                             | 2         | 0.39%   |
| ASIX Electronics                 | 2         | 0.39%   |
| ZyXEL Communications             | 1         | 0.19%   |
| T & A Mobile Phones              | 1         | 0.19%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| Sierra Wireless                  | 1         | 0.19%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.19%   |
| Motorola PCS                     | 1         | 0.19%   |
| Microsoft                        | 1         | 0.19%   |
| Linksys                          | 1         | 0.19%   |
| Lenovo                           | 1         | 0.19%   |
| ICS Advent                       | 1         | 0.19%   |
| Gemtek                           | 1         | 0.19%   |
| FIBOCOM                          | 1         | 0.19%   |
| Edimax Technology                | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 132       | 21.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 3.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 3.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.81%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 1.81%   |
| Realtek 802.11ac NIC                                              | 9         | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.31%   |
| Intel Wireless 7260                                               | 8         | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.15%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.15%   |
| Intel Wireless 8260                                               | 7         | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.99%   |
| Intel Wireless 3165                                               | 6         | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 5         | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 0.82%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 0.82%   |
| Intel Wireless 7265                                               | 5         | 0.82%   |
| Intel WiFi Link 5100                                              | 5         | 0.82%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.82%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.66%   |
| Intel Wireless 3160                                               | 4         | 0.66%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3         | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.49%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.49%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.49%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.49%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.49%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.49%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.49%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2         | 0.33%   |
| TP-Link 802.11ac NIC                                              | 2         | 0.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 110       | 39.71%  |
| Realtek Semiconductor | 54        | 19.49%  |
| Qualcomm Atheros      | 49        | 17.69%  |
| Broadcom              | 21        | 7.58%   |
| Ralink Technology     | 8         | 2.89%   |
| Ralink                | 8         | 2.89%   |
| TP-Link               | 7         | 2.53%   |
| Broadcom Limited      | 7         | 2.53%   |
| NetGear               | 2         | 0.72%   |
| D-Link System         | 2         | 0.72%   |
| ZyXEL Communications  | 1         | 0.36%   |
| Sierra Wireless       | 1         | 0.36%   |
| Qualcomm              | 1         | 0.36%   |
| Microsoft             | 1         | 0.36%   |
| Linksys               | 1         | 0.36%   |
| Gemtek                | 1         | 0.36%   |
| FIBOCOM               | 1         | 0.36%   |
| Edimax Technology     | 1         | 0.36%   |
| Dell                  | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 4.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 3.96%   |
| Intel Wi-Fi 6 AX200                                            | 11        | 3.96%   |
| Realtek 802.11ac NIC                                           | 9         | 3.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 2.88%   |
| Intel Wireless 7260                                            | 8         | 2.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 2.52%   |
| Intel Wireless 8265 / 8275                                     | 7         | 2.52%   |
| Intel Wireless 8260                                            | 7         | 2.52%   |
| Intel Wireless 3165                                            | 6         | 2.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 2.16%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 2.16%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 5         | 1.8%    |
| Ralink MT7601U Wireless Adapter                                | 5         | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 1.8%    |
| Intel Wireless 7265                                            | 5         | 1.8%    |
| Intel WiFi Link 5100                                           | 5         | 1.8%    |
| Intel Wi-Fi 6 AX201                                            | 5         | 1.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.44%   |
| Intel Wireless 3160                                            | 4         | 1.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3         | 1.08%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.08%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.08%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.08%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.08%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2         | 0.72%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.72%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 0.72%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.72%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.72%   |
| Intel Wireless-AC 9260                                         | 2         | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 0.72%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 0.72%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.72%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 0.72%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 2         | 0.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 0.72%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 0.72%   |
| ZyXEL NWD-270N Wireless N-lite USB Adapter                     | 1         | 0.36%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.36%   |
| TP-Link TL-WN722N v2                                           | 1         | 0.36%   |
| TP-Link Archer T4U ver.3                                       | 1         | 0.36%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A            | 1         | 0.36%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.36%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.36%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.36%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 168       | 52.5%   |
| Intel                            | 72        | 22.5%   |
| Qualcomm Atheros                 | 23        | 7.19%   |
| Broadcom                         | 17        | 5.31%   |
| Marvell Technology Group         | 5         | 1.56%   |
| DisplayLink                      | 5         | 1.56%   |
| Xiaomi                           | 4         | 1.25%   |
| Broadcom Limited                 | 4         | 1.25%   |
| Samsung Electronics              | 3         | 0.94%   |
| Huawei Technologies              | 3         | 0.94%   |
| OPPO                             | 2         | 0.63%   |
| Nvidia                           | 2         | 0.63%   |
| MediaTek                         | 2         | 0.63%   |
| Google                           | 2         | 0.63%   |
| ASIX Electronics                 | 2         | 0.63%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Qualcomm                         | 1         | 0.31%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.31%   |
| Motorola PCS                     | 1         | 0.31%   |
| ICS Advent                       | 1         | 0.31%   |
| D-Link System                    | 1         | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 132       | 40.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 6.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 6.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.52%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.52%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 1.52%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.91%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3         | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.91%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.91%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.91%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.91%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.91%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.91%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.61%   |
| OPPO SDM665-IDP _SN:6A6C23F9                                      | 2         | 0.61%   |
| MediaTek Titan                                                    | 2         | 0.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.61%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.61%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.61%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.61%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.61%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 2         | 0.61%   |
| Huawei SPN-AL00                                                   | 2         | 0.61%   |
| Google Nexus/Pixel Device (tether)                                | 2         | 0.61%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.61%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.3%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.3%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.3%    |
| Qualcomm SM8250-APOLLO _SN:B760817D                               | 1         | 0.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.3%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.3%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.3%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.3%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.3%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.3%    |
| OnePlus (Shenzhen) IN2013                                         | 1         | 0.3%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.3%    |
| Nvidia MCP61 Ethernet                                             | 1         | 0.3%    |
| Motorola PCS moto e5                                              | 1         | 0.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.3%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 297       | 53.04%  |
| WiFi     | 260       | 46.43%  |
| Unknown  | 2         | 0.36%   |
| Modem    | 1         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 271       | 53.03%  |
| WiFi     | 238       | 46.58%  |
| Unknown  | 2         | 0.39%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 195       | 58.04%  |
| 1     | 130       | 38.69%  |
| 0     | 8         | 2.38%   |
| 3     | 3         | 0.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 237       | 70.12%  |
| Yes  | 101       | 29.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 88        | 41.9%   |
| Realtek Semiconductor           | 22        | 10.48%  |
| Qualcomm Atheros Communications | 20        | 9.52%   |
| Apple                           | 11        | 5.24%   |
| Lite-On Technology              | 10        | 4.76%   |
| IMC Networks                    | 10        | 4.76%   |
| Foxconn / Hon Hai               | 10        | 4.76%   |
| Cambridge Silicon Radio         | 10        | 4.76%   |
| Broadcom                        | 9         | 4.29%   |
| Dell                            | 5         | 2.38%   |
| Toshiba                         | 3         | 1.43%   |
| Ralink                          | 3         | 1.43%   |
| ASUSTek Computer                | 3         | 1.43%   |
| Foxconn International           | 2         | 0.95%   |
| Micro Star International        | 1         | 0.48%   |
| Integrated System Solution      | 1         | 0.48%   |
| Belkin Components               | 1         | 0.48%   |
| Alps Electric                   | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 49        | 23.33%  |
| Intel Bluetooth wireless interface                                                  | 26        | 12.38%  |
| Realtek Bluetooth Radio                                                             | 15        | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 12        | 5.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 4.76%   |
| Intel AX200 Bluetooth                                                               | 9         | 4.29%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 3.33%   |
| Lite-On Bluetooth Device                                                            | 6         | 2.86%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 2.38%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.9%    |
| Apple Bluetooth USB Host Controller                                                 | 4         | 1.9%    |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.43%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.43%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.43%   |
| Dell BCM20702A0                                                                     | 3         | 1.43%   |
| Apple Bluetooth HCI                                                                 | 3         | 1.43%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.95%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.95%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.95%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.95%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.95%   |
| Dell BT Mini-Receiver                                                               | 2         | 0.95%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.95%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 2         | 0.95%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.95%   |
| Apple Bluetooth Host Controller                                                     | 2         | 0.95%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.48%   |
| Toshiba BRCM Bluetooth Controller BCM2070                                           | 1         | 0.48%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.48%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.48%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.48%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.48%   |
| IMC Networks Bluetooth                                                              | 1         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.48%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.48%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.48%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.48%   |
| Broadcom Bluetooth                                                                  | 1         | 0.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.48%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.48%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.48%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 1         | 0.48%   |
| ASUS Qualcomm Bluetooth 4.1                                                         | 1         | 0.48%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 246       | 53.59%  |
| AMD                              | 97        | 21.13%  |
| Nvidia                           | 85        | 18.52%  |
| C-Media Electronics              | 5         | 1.09%   |
| Creative Labs                    | 3         | 0.65%   |
| Texas Instruments                | 2         | 0.44%   |
| Razer USA                        | 2         | 0.44%   |
| JMTek                            | 2         | 0.44%   |
| Corsair                          | 2         | 0.44%   |
| XMOS                             | 1         | 0.22%   |
| VIA Technologies                 | 1         | 0.22%   |
| Valve Software                   | 1         | 0.22%   |
| SteelSeries ApS                  | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Samsung Electronics              | 1         | 0.22%   |
| Numark                           | 1         | 0.22%   |
| Logitech                         | 1         | 0.22%   |
| Klipsch Audio                    | 1         | 0.22%   |
| iConnectivity                    | 1         | 0.22%   |
| GN Netcom                        | 1         | 0.22%   |
| GEMBIRD                          | 1         | 0.22%   |
| Focusrite-Novation               | 1         | 0.22%   |
| FIFINE Microphones               | 1         | 0.22%   |
| ASUSTek Computer                 | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 31        | 5.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 31        | 5.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 29        | 5.32%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 22        | 4.04%   |
| AMD FCH Azalia Controller                                                         | 20        | 3.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 19        | 3.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 15        | 2.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 13        | 2.39%   |
| AMD Starship/Matisse HD Audio Controller                                          | 13        | 2.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 12        | 2.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 12        | 2.2%    |
| Intel Haswell-ULT HD Audio Controller                                             | 11        | 2.02%   |
| Intel 8 Series HD Audio Controller                                                | 11        | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 11        | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 11        | 2.02%   |
| AMD Kabini HDMI/DP Audio                                                          | 11        | 2.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 9         | 1.65%   |
| Nvidia GF108 High Definition Audio Controller                                     | 8         | 1.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 8         | 1.47%   |
| Intel Cannon Lake PCH cAVS                                                        | 8         | 1.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 7         | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 7         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 6         | 1.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 6         | 1.1%    |
| Nvidia GF119 HDMI Audio Controller                                                | 6         | 1.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.1%    |
| Intel Comet Lake PCH-LP cAVS                                                      | 6         | 1.1%    |
| Intel CM238 HD Audio Controller                                                   | 6         | 1.1%    |
| Intel Broadwell-U Audio Controller                                                | 6         | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 6         | 1.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 6         | 1.1%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 6         | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                                     | 5         | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 5         | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                                     | 5         | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5         | 0.92%   |
| Intel Comet Lake PCH cAVS                                                         | 5         | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 5         | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 5         | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 5         | 0.92%   |
| Nvidia GM204 High Definition Audio Controller                                     | 4         | 0.73%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 4         | 0.73%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 4         | 0.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 4         | 0.73%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4         | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                                | 3         | 0.55%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 3         | 0.55%   |
| AMD Wrestler HDMI Audio                                                           | 3         | 0.55%   |
| AMD Trinity HDMI Audio Controller                                                 | 3         | 0.55%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3         | 0.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3         | 0.55%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3         | 0.55%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2         | 0.37%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2         | 0.37%   |
| Nvidia Audio device                                                               | 2         | 0.37%   |
| JMTek USB PnP Audio Device                                                        | 2         | 0.37%   |
| Intel Audio device                                                                | 2         | 0.37%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2         | 0.37%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2         | 0.37%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 24.24%  |
| SK Hynix            | 11        | 16.67%  |
| Micron Technology   | 8         | 12.12%  |
| Unknown             | 7         | 10.61%  |
| A-DATA Technology   | 5         | 7.58%   |
| Kingston            | 4         | 6.06%   |
| Crucial             | 4         | 6.06%   |
| Corsair             | 3         | 4.55%   |
| Ramaxel Technology  | 2         | 3.03%   |
| G.Skill             | 2         | 3.03%   |
| Unknown (ABCD)      | 1         | 1.52%   |
| Team                | 1         | 1.52%   |
| Strontium           | 1         | 1.52%   |
| Nanya Technology    | 1         | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 3         | 4.05%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 2         | 2.7%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s             | 2         | 2.7%    |
| Kingston RAM ACR16D3LS1KFG/4G 4096MB SODIMM DDR3 1600MT/s           | 2         | 2.7%    |
| A-DATA RAM AE4S240038G17-BHYA 8192MB SODIMM DDR4 2400MT/s           | 2         | 2.7%    |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                           | 1         | 1.35%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s             | 1         | 1.35%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                           | 1         | 1.35%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s                        | 1         | 1.35%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 1.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1         | 1.35%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                      | 1         | 1.35%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 1.35%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 1         | 1.35%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s                  | 1         | 1.35%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.35%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s               | 1         | 1.35%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s                | 1         | 1.35%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.35%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.35%   |
| SK Hynix RAM HMT325U6EFR8C-PB 2048MB DIMM DDR3 1600MT/s             | 1         | 1.35%   |
| SK Hynix RAM HMT112S6BFR6C-G7 1024MB SODIMM DDR3 1067MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 1.35%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 1.35%   |
| SK Hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.35%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 1.35%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.35%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 1.35%   |
| Samsung RAM M471B5773EB0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s            | 1         | 1.35%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 1.35%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.35%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Samsung RAM M471B2873FHS-CH9 1024MB SODIMM DDR3 1334MT/s            | 1         | 1.35%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s      | 1         | 1.35%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.35%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.35%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.35%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                 | 1         | 1.35%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s                 | 1         | 1.35%   |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 1.35%   |
| Nanya RAM NT1GT64U8HB0BN-3C 1024MB SODIMM DDR 667MT/s               | 1         | 1.35%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s   | 1         | 1.35%   |
| Micron RAM Module 2GB SODIMM DDR2 800MT/s                           | 1         | 1.35%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 1         | 1.35%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s       | 1         | 1.35%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| Kingston RAM K821PJ-MID 16384MB SODIMM DDR4 2400MT/s                | 1         | 1.35%   |
| Kingston RAM 99U5403-065.A00LF 4GB DIMM DDR3 1600MT/s               | 1         | 1.35%   |
| G.Skill RAM F4-3600C19-8GVRB 8192MB DIMM DDR4 2933MT/s              | 1         | 1.35%   |
| G.Skill RAM F4-2666C15-8GVR 8GB DIMM DDR4 2800MT/s                  | 1         | 1.35%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s              | 1         | 1.35%   |
| Crucial RAM CT51264BA160BJ.C8F 4GB DIMM DDR3 1600MT/s               | 1         | 1.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 29        | 50%     |
| DDR3    | 16        | 27.59%  |
| LPDDR4  | 4         | 6.9%    |
| DDR2    | 3         | 5.17%   |
| SDRAM   | 2         | 3.45%   |
| LPDDR3  | 2         | 3.45%   |
| Unknown | 2         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 64.29%  |
| DIMM         | 14        | 25%     |
| Row Of Chips | 6         | 10.71%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 24        | 38.1%   |
| 4096  | 24        | 38.1%   |
| 2048  | 10        | 15.87%  |
| 32768 | 2         | 3.17%   |
| 1024  | 2         | 3.17%   |
| 16384 | 1         | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 13        | 20.63%  |
| 2667  | 11        | 17.46%  |
| 3200  | 7         | 11.11%  |
| 2400  | 6         | 9.52%   |
| 2133  | 5         | 7.94%   |
| 3266  | 3         | 4.76%   |
| 1333  | 3         | 4.76%   |
| 4267  | 2         | 3.17%   |
| 4199  | 2         | 3.17%   |
| 1334  | 2         | 3.17%   |
| 800   | 2         | 3.17%   |
| 667   | 2         | 3.17%   |
| 3600  | 1         | 1.59%   |
| 2933  | 1         | 1.59%   |
| 2800  | 1         | 1.59%   |
| 1867  | 1         | 1.59%   |
| 1067  | 1         | 1.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 50%     |
| Canon               | 2         | 33.33%  |
| Samsung Electronics | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SCX-3400 Series         | 1         | 16.67%  |
| HP OfficeJet 4650 series        | 1         | 16.67%  |
| HP LaserJet Professional P1102w | 1         | 16.67%  |
| HP DeskJet 2700 series          | 1         | 16.67%  |
| Canon PIXMA MG2500 Series       | 1         | 16.67%  |
| Canon LiDE 400                  | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 8800F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 17.35%  |
| Realtek Semiconductor                  | 23        | 11.73%  |
| IMC Networks                           | 20        | 10.2%   |
| Microdia                               | 15        | 7.65%   |
| Sunplus Innovation Technology          | 14        | 7.14%   |
| Acer                                   | 14        | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 5.61%   |
| Quanta                                 | 10        | 5.1%    |
| Suyin                                  | 7         | 3.57%   |
| Lite-On Technology                     | 7         | 3.57%   |
| Apple                                  | 7         | 3.57%   |
| Logitech                               | 5         | 2.55%   |
| Syntek                                 | 4         | 2.04%   |
| Generalplus Technology                 | 3         | 1.53%   |
| Ricoh                                  | 2         | 1.02%   |
| Primax Electronics                     | 2         | 1.02%   |
| Alcor Micro                            | 2         | 1.02%   |
| YGTek                                  | 1         | 0.51%   |
| Teslong Camera                         | 1         | 0.51%   |
| Sunplus Technology                     | 1         | 0.51%   |
| Silicon Motion                         | 1         | 0.51%   |
| Samsung Electronics                    | 1         | 0.51%   |
| Razer USA                              | 1         | 0.51%   |
| OmniVision Technologies                | 1         | 0.51%   |
| Microsoft                              | 1         | 0.51%   |
| KYE Systems (Mouse Systems)            | 1         | 0.51%   |
| Jieli Technology                       | 1         | 0.51%   |
| Importek                               | 1         | 0.51%   |
| Genesys Logic                          | 1         | 0.51%   |
| GEMBIRD                                | 1         | 0.51%   |
| DJKCVA1BIDQ8CL                         | 1         | 0.51%   |
| ARC International                      | 1         | 0.51%   |
| ALi                                    | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 8         | 4.08%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 7         | 3.57%   |
| Chicony TOSHIBA Web Camera - HD                     | 6         | 3.06%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 2.55%   |
| Acer Lenovo EasyCamera                              | 5         | 2.55%   |
| Realtek USB Camera                                  | 4         | 2.04%   |
| Realtek Integrated Webcam                           | 4         | 2.04%   |
| Microdia Integrated_Webcam_HD                       | 4         | 2.04%   |
| Microdia Integrated Webcam                          | 4         | 2.04%   |
| IMC Networks Integrated Camera                      | 4         | 2.04%   |
| Chicony HD WebCam                                   | 4         | 2.04%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 2.04%   |
| Syntek Integrated Camera                            | 3         | 1.53%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 1.53%   |
| Quanta HP Wide Vision HD Camera                     | 3         | 1.53%   |
| Generalplus GENERAL WEBCAM                          | 3         | 1.53%   |
| Chicony VGA Webcam                                  | 3         | 1.53%   |
| Chicony Integrated Camera                           | 3         | 1.53%   |
| Chicony HP Truevision HD                            | 3         | 1.53%   |
| Chicony EasyCamera                                  | 3         | 1.53%   |
| Acer Integrated Camera                              | 3         | 1.53%   |
| Suyin HP Truevision HD                              | 2         | 1.02%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 1.02%   |
| Sunplus Integrated Webcam                           | 2         | 1.02%   |
| Sunplus HD WebCam                                   | 2         | 1.02%   |
| Realtek Lenovo EasyCamera                           | 2         | 1.02%   |
| Realtek HD WebCam                                   | 2         | 1.02%   |
| Quanta VGA WebCam                                   | 2         | 1.02%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.02%   |
| Quanta HD User Facing                               | 2         | 1.02%   |
| Microdia USB 2.0 Camera                             | 2         | 1.02%   |
| Logitech HD Pro Webcam C920                         | 2         | 1.02%   |
| Lite-On HP HD Camera                                | 2         | 1.02%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 1.02%   |
| YGTek webcam                                        | 1         | 0.51%   |
| Teslong Camera Teslong Camera                       | 1         | 0.51%   |
| Syntek USB Camera Device                            | 1         | 0.51%   |
| Suyin WebCam                                        | 1         | 0.51%   |
| Suyin Acer HD Crystal Eye webcam                    | 1         | 0.51%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.51%   |
| Sunplus 1.3M HD WebCam                              | 1         | 0.51%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.51%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.51%   |
| Sunplus Laptop_Integrated_Webcam_1.3M               | 1         | 0.51%   |
| Sunplus HP Wide Vision HD                           | 1         | 0.51%   |
| Sunplus HD User Facing                              | 1         | 0.51%   |
| Sunplus HD 720P webcam                              | 1         | 0.51%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 0.51%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 0.51%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 0.51%   |
| Ricoh Visual Communication Camera VGP-VCC9 [R5U870] | 1         | 0.51%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.51%   |
| Realtek LG Webcam                                   | 1         | 0.51%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.51%   |
| Realtek 2SF001                                      | 1         | 0.51%   |
| Razer USA Razer Kiyo                                | 1         | 0.51%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 1         | 0.51%   |
| Primax Villem                                       | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 48.65%  |
| Upek                       | 6         | 16.22%  |
| Shenzhen Goodix Technology | 6         | 16.22%  |
| LighTuning Technology      | 2         | 5.41%   |
| AuthenTec                  | 2         | 5.41%   |
| Synaptics                  | 1         | 2.7%    |
| STMicroelectronics         | 1         | 2.7%    |
| Focal-systems.Corp         | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 13.51%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 8.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 8.11%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 8.11%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 5.41%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 5.41%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 5.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.7%    |
| Validity Sensors VFS491                                                    | 1         | 2.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.7%    |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.7%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.7%    |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.7%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 2.7%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 2.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.7%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 2.7%    |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.7%    |
| LighTuning Fingerprint Reader                                              | 1         | 2.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.7%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.7%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.7%    |
| AuthenTec AES1600                                                          | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 7         | 50%     |
| Alcor Micro           | 3         | 21.43%  |
| Lenovo                | 2         | 14.29%  |
| O2 Micro              | 1         | 7.14%   |
| Advanced Card Systems | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 21.43%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 21.43%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 14.29%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 7.14%   |
| Broadcom 5880                                                                | 1         | 7.14%   |
| Advanced Card Systems ACR39U                                                 | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 230       | 68.05%  |
| 1     | 88        | 26.04%  |
| 2     | 19        | 5.62%   |
| 3     | 1         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 37        | 29.6%   |
| Graphics card            | 27        | 21.6%   |
| Net/wireless             | 25        | 20%     |
| Chipcard                 | 12        | 9.6%    |
| Multimedia controller    | 11        | 8.8%    |
| Bluetooth                | 3         | 2.4%    |
| Storage                  | 2         | 1.6%    |
| Unassigned class         | 1         | 0.8%    |
| Storage/ide              | 1         | 0.8%    |
| Sound                    | 1         | 0.8%    |
| Net/ethernet             | 1         | 0.8%    |
| Flash memory             | 1         | 0.8%    |
| Dvb card                 | 1         | 0.8%    |
| Communication controller | 1         | 0.8%    |
| Camera                   | 1         | 0.8%    |

